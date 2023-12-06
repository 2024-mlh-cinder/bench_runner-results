
# Pystats results

- benchmark: scimark
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 907,278,000 | 18.5% | 18.5% |  |
| POP_JUMP_IF_FALSE | 332,098,200 | 6.8% | 25.3% |  |
| LOAD_FAST_LOAD_FAST | 327,413,240 | 6.7% | 32.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 316,759,120 | 6.5% | 38.5% |  |
| LOAD_CONST | 226,610,520 | 4.6% | 43.1% |  |
| COMPARE_OP_INT | 215,858,580 | 4.4% | 47.5% |  |
| SWAP | 202,953,600 | 4.1% | 51.7% |  |
| RESUME_CHECK | 181,523,420 | 3.7% | 55.4% |  |
| COPY | 178,273,600 | 3.6% | 59.0% |  |
| RETURN_VALUE | 177,528,300 | 3.6% | 62.6% |  |
| LOAD_GLOBAL_BUILTIN | 174,575,200 | 3.6% | 66.2% |  |
| BINARY_SUBSCR | 160,419,660 | 3.3% | 69.5% |  |
| BINARY_SUBSCR_GETITEM | 118,050,820 | 2.4% | 71.9% |  |
| STORE_SUBSCR | 115,275,700 | 2.4% | 74.3% |  |
| BINARY_OP_ADD_INT | 99,684,300 | 2.0% | 76.3% |  |
| ENTER_EXECUTOR | 96,884,260 | 2.0% | 78.3% |  |
| JUMP_FORWARD | 94,194,080 | 1.9% | 80.2% |  |
| TO_BOOL_BOOL | 93,818,820 | 1.9% | 82.1% |  |
| CALL_ISINSTANCE | 80,450,280 | 1.6% | 83.8% |  |
| BINARY_SUBSCR_LIST_INT | 80,435,080 | 1.6% | 85.4% |  |
| STORE_FAST | 79,064,860 | 1.6% | 87.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 72,017,580 | 1.5% | 88.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 59,339,320 | 1.2% | 89.7% |  |
| STORE_FAST_STORE_FAST | 55,700,800 | 1.1% | 90.8% |  |
| BINARY_OP_ADD_FLOAT | 55,255,740 | 1.1% | 92.0% |  |
| CALL_PY_EXACT_ARGS | 51,397,720 | 1.1% | 93.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 51,376,280 | 1.0% | 94.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,899,520 | 1.0% | 95.0% |  |
| BINARY_OP_MULTIPLY_INT | 46,504,780 | 1.0% | 96.0% |  |
| BUILD_TUPLE | 39,217,740 | 0.8% | 96.8% |  |
| BINARY_OP_SUBTRACT_INT | 33,293,600 | 0.7% | 97.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 26,501,700 | 0.5% | 98.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 18,637,440 | 0.4% | 98.4% | 0.1% |
| CALL_BUILTIN_CLASS | 13,665,240 | 0.3% | 98.7% |  |
| FOR_ITER_RANGE | 10,431,140 | 0.2% | 98.9% |  |
| COMPARE_OP | 8,813,000 | 0.2% | 99.1% |  |
| RETURN_CONST | 8,523,520 | 0.2% | 99.2% |  |
| INTERPRETER_EXIT | 8,499,020 | 0.2% | 99.4% |  |
| POP_JUMP_IF_TRUE | 8,404,000 | 0.2% | 99.6% |  |
| COMPARE_OP_FLOAT | 8,395,960 | 0.2% | 99.7% |  |
| BINARY_OP | 6,481,760 | 0.1% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,599,960 | 0.0% | 99.9% |  |
| POP_TOP | 825,120 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 811,620 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 800,060 | 0.0% | 100.0% |  |
| YIELD_VALUE | 800,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 420,740 | 0.0% | 100.0% |  |
| GET_ITER | 285,140 | 0.0% | 100.0% |  |
| LIST_APPEND | 108,940 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 80,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 48,720 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 25,800 | 0.0% | 100.0% |  |
| CALL | 22,620 | 0.0% | 100.0% |  |
| PUSH_NULL | 18,720 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 15,180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 3,960 | 0.0% | 100.0% |  |
| LOAD_ATTR | 3,920 | 0.0% | 100.0% |  |
| BUILD_LIST | 1,920 | 0.0% | 100.0% |  |
| FOR_ITER | 1,740 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,440 | 0.0% | 100.0% |  |
| LOAD_DEREF | 1,200 | 0.0% | 100.0% |  |
| RESUME | 840 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 800 | 0.0% | 100.0% |  |
| STORE_SLICE | 480 | 0.0% | 100.0% |  |
| NOP | 400 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 400 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 400 | 0.0% | 100.0% |  |
| LIST_EXTEND | 400 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 400 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 240 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 240 | 0.0% | 100.0% |  |
| TO_BOOL | 200 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 180 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 160 | 0.0% | 100.0% |  |
| BINARY_SLICE | 80 | 0.0% | 100.0% |  |
| END_FOR | 80 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 80 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 248,528,160 | 5.1% | 5.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 215,842,620 | 4.4% | 9.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 209,726,620 | 4.3% | 13.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 156,290,380 | 3.2% | 17.0% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 118,050,820 | 2.4% | 19.4% |
| LOAD_CONST LOAD_FAST | 100,304,360 | 2.0% | 21.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 93,953,340 | 1.9% | 23.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 93,818,820 | 1.9% | 25.3% |
| LOAD_FAST SWAP | 92,198,400 | 1.9% | 27.1% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 92,198,400 | 1.9% | 29.0% |
| SWAP COPY | 92,198,400 | 1.9% | 30.9% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 92,198,320 | 1.9% | 32.8% |
| COPY COMPARE_OP_INT | 92,198,320 | 1.9% | 34.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 80,450,480 | 1.6% | 36.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 80,450,240 | 1.6% | 38.0% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 80,450,240 | 1.6% | 39.6% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 80,450,240 | 1.6% | 41.3% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 79,635,100 | 1.6% | 42.9% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 79,635,080 | 1.6% | 44.5% |
| RETURN_VALUE LOAD_FAST | 79,619,760 | 1.6% | 46.1% |
| LOAD_FAST LOAD_CONST | 76,344,480 | 1.6% | 47.7% |
| STORE_SUBSCR ENTER_EXECUTOR | 68,564,900 | 1.4% | 49.1% |
| SWAP STORE_SUBSCR | 67,709,280 | 1.4% | 50.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 67,481,180 | 1.4% | 51.9% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 61,339,520 | 1.3% | 53.1% |
| RESUME_CHECK LOAD_FAST | 54,167,820 | 1.1% | 54.2% |
| LOAD_FAST BINARY_SUBSCR | 52,955,960 | 1.1% | 55.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 52,592,480 | 1.1% | 56.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 51,397,660 | 1.1% | 57.4% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 51,375,620 | 1.0% | 58.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 48,639,920 | 1.0% | 59.5% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 48,094,880 | 1.0% | 60.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 46,899,520 | 1.0% | 61.4% |
| LOAD_FAST BINARY_OP_ADD_INT | 46,393,460 | 0.9% | 62.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 46,345,200 | 0.9% | 63.3% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 46,111,440 | 0.9% | 64.2% |
| RESUME_CHECK LOAD_CONST | 46,103,620 | 0.9% | 65.2% |
| JUMP_FORWARD LOAD_CONST | 46,099,200 | 0.9% | 66.1% |
| BINARY_OP_ADD_INT RETURN_VALUE | 46,099,180 | 0.9% | 67.1% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 46,099,180 | 0.9% | 68.0% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 46,099,160 | 0.9% | 69.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 46,099,160 | 0.9% | 69.9% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 46,099,120 | 0.9% | 70.8% |
| COPY BINARY_SUBSCR | 43,037,600 | 0.9% | 71.7% |
| COPY COPY | 43,037,600 | 0.9% | 72.6% |
| SWAP SWAP | 43,037,600 | 0.9% | 73.5% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 39,952,720 | 0.8% | 74.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 39,216,000 | 0.8% | 75.1% |
| BINARY_SUBSCR RETURN_VALUE | 38,416,020 | 0.8% | 75.9% |
| RETURN_VALUE BINARY_SUBSCR | 38,416,000 | 0.8% | 76.7% |
| ENTER_EXECUTOR BINARY_SUBSCR_GETITEM | 34,724,420 | 0.7% | 77.4% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 32,212,880 | 0.7% | 78.0% |
| LOAD_FAST BUILD_TUPLE | 31,532,800 | 0.6% | 78.7% |
| BUILD_TUPLE BINARY_SUBSCR_GETITEM | 30,733,620 | 0.6% | 79.3% |
| LOAD_FAST COPY | 26,664,000 | 0.5% | 79.9% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 26,557,160 | 0.5% | 80.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 26,499,980 | 0.5% | 80.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 26,499,860 | 0.5% | 81.5% |
| BINARY_SUBSCR BINARY_OP_MULTIPLY_FLOAT | 26,268,940 | 0.5% | 82.0% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 26,267,980 | 0.5% | 82.6% |
| LOAD_CONST COMPARE_OP_INT | 26,027,600 | 0.5% | 83.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 25,947,700 | 0.5% | 83.6% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 25,592,420 | 0.5% | 84.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 25,360,740 | 0.5% | 84.7% |
| BINARY_SUBSCR LOAD_FAST | 24,963,960 | 0.5% | 85.2% |
| ENTER_EXECUTOR SWAP | 24,671,680 | 0.5% | 85.7% |
| STORE_SUBSCR LOAD_FAST_LOAD_FAST | 24,506,720 | 0.5% | 86.2% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST_LOAD_FAST | 24,052,940 | 0.5% | 86.7% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 23,125,800 | 0.5% | 87.1% |
| RETURN_VALUE BINARY_OP_ADD_FLOAT | 23,049,480 | 0.5% | 87.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 17,768,860 | 0.4% | 88.0% |
| BINARY_OP_ADD_FLOAT SWAP | 16,369,200 | 0.3% | 88.3% |
| LOAD_FAST BINARY_OP_ADD_FLOAT | 16,369,120 | 0.3% | 88.6% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 16,144,360 | 0.3% | 89.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 15,949,060 | 0.3% | 89.3% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 15,828,860 | 0.3% | 89.6% |
| STORE_FAST LOAD_FAST | 14,804,600 | 0.3% | 89.9% |
| LOAD_FAST STORE_SUBSCR | 14,176,300 | 0.3% | 90.2% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 13,619,040 | 0.3% | 90.5% |
| LOAD_FAST CALL_BUILTIN_CLASS | 13,581,820 | 0.3% | 90.8% |
| CALL_BUILTIN_CLASS BINARY_OP_MULTIPLY_FLOAT | 13,376,760 | 0.3% | 91.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 13,372,680 | 0.3% | 91.3% |
| BINARY_OP_MULTIPLY_FLOAT RETURN_VALUE | 13,368,600 | 0.3% | 91.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 13,368,480 | 0.3% | 91.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_GLOBAL_BUILTIN | 13,368,480 | 0.3% | 92.1% |
| BINARY_OP_ADD_INT STORE_FAST | 13,317,760 | 0.3% | 92.4% |
| STORE_FAST ENTER_EXECUTOR | 13,257,180 | 0.3% | 92.7% |
| STORE_SUBSCR LOAD_FAST | 12,884,260 | 0.3% | 92.9% |
| RETURN_VALUE STORE_FAST | 12,484,020 | 0.3% | 93.2% |
| ENTER_EXECUTOR FOR_ITER_RANGE | 10,137,100 | 0.2% | 93.4% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 9,018,100 | 0.2% | 93.6% |
| LOAD_CONST COMPARE_OP | 8,809,640 | 0.2% | 93.8% |
| COMPARE_OP POP_JUMP_IF_FALSE | 8,809,620 | 0.2% | 93.9% |
| STORE_FAST_STORE_FAST STORE_FAST | 8,801,120 | 0.2% | 94.1% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST_STORE_FAST | 8,801,120 | 0.2% | 94.3% |
| BINARY_SUBSCR BINARY_OP_SUBTRACT_FLOAT | 8,801,000 | 0.2% | 94.5% |
| FOR_ITER_RANGE ENTER_EXECUTOR | 8,673,680 | 0.2% | 94.7% |
| CACHE RESUME_CHECK | 8,498,820 | 0.2% | 94.8% |
| RETURN_CONST INTERPRETER_EXIT | 8,498,700 | 0.2% | 95.0% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 8,490,760 | 0.2% | 95.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 340 | 70.8% |
| LOAD_FAST | 80 | 16.7% |
| ENTER_EXECUTOR | 60 | 12.5% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,498,820 | 100.0% |
| RESUME | 180 | 0.0% |
| POP_TOP | 20 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,955,960 | 33.0% |
| COPY | 43,037,600 | 26.8% |
| RETURN_VALUE | 38,416,000 | 23.9% |
| LOAD_FAST_LOAD_FAST | 17,768,860 | 11.1% |
| BINARY_OP_ADD_INT | 8,195,380 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 61,339,520 | 38.2% |
| RETURN_VALUE | 38,416,020 | 23.9% |
| BINARY_OP_MULTIPLY_FLOAT | 26,268,940 | 16.4% |
| LOAD_FAST | 24,963,960 | 15.6% |
| BINARY_OP_SUBTRACT_FLOAT | 8,801,000 | 5.5% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 180 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 284,060 | 99.6% |
| CALL | 600 | 0.2% |
| LOAD_FAST | 400 | 0.1% |
| RETURN_GENERATOR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 284,140 | 99.6% |
| FOR_ITER | 700 | 0.2% |
| LOAD_FAST_AND_CLEAR | 240 | 0.1% |
| FOR_ITER_GEN | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,498,700 | 100.0% |
| RETURN_VALUE | 300 | 0.0% |
| YIELD_VALUE | 20 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 400 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 799,980 | 97.0% |
| RETURN_CONST | 24,560 | 3.0% |
| CALL | 400 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |
| FOR_ITER_GEN | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 803,320 | 97.4% |
| LOAD_CONST | 12,240 | 1.5% |
| RETURN_CONST | 4,080 | 0.5% |
| LOAD_GLOBAL_MODULE | 4,000 | 0.5% |
| JUMP_BACKWARD | 920 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 17,500 | 93.5% |
| LOAD_DEREF | 800 | 4.3% |
| LOAD_ATTR | 340 | 1.8% |
| LOAD_FAST | 80 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,440 | 93.2% |
| CALL | 1,200 | 6.4% |
| LOAD_FAST_LOAD_FAST | 80 | 0.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 79,635,100 | 44.9% |
| BINARY_OP_ADD_INT | 46,099,180 | 26.0% |
| BINARY_SUBSCR | 38,416,020 | 21.6% |
| BINARY_OP_MULTIPLY_FLOAT | 13,368,600 | 7.5% |
| LOAD_FAST | 8,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,619,760 | 44.8% |
| BINARY_SUBSCR | 38,416,000 | 21.6% |
| BINARY_OP_ADD_FLOAT | 23,049,480 | 13.0% |
| STORE_FAST | 12,484,020 | 7.0% |
| LOAD_FAST_LOAD_FAST | 8,490,760 | 4.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 67,709,280 | 58.7% |
| LOAD_FAST | 14,176,300 | 12.3% |
| BUILD_TUPLE | 8,483,200 | 7.4% |
| BINARY_OP_ADD_INT | 8,262,280 | 7.2% |
| LOAD_FAST_LOAD_FAST | 8,128,480 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 68,564,900 | 59.5% |
| LOAD_FAST_LOAD_FAST | 24,506,720 | 21.3% |
| LOAD_FAST | 12,884,260 | 11.2% |
| RETURN_CONST | 8,483,220 | 7.4% |
| JUMP_BACKWARD | 803,740 | 0.7% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 60 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 30.0% |
| CALL | 40 | 20.0% |
| CALL_ISINSTANCE | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 100 | 50.0% |
| TO_BOOL_BOOL | 100 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 5,260,680 | 81.2% |
| LOAD_CONST | 1,136,360 | 17.5% |
| LOAD_FAST | 38,200 | 0.6% |
| BINARY_OP | 15,680 | 0.2% |
| LOAD_FAST_LOAD_FAST | 9,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,404,780 | 98.8% |
| LIST_APPEND | 16,000 | 0.2% |
| BINARY_OP | 15,680 | 0.2% |
| BINARY_OP_ADD_FLOAT | 8,280 | 0.1% |
| CALL_BUILTIN_O | 8,280 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,280 | 66.7% |
| LOAD_FAST | 400 | 20.8% |
| SWAP | 240 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,280 | 66.7% |
| LOAD_DEREF | 400 | 20.8% |
| SWAP | 240 | 12.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,520 | 68.6% |
| LOAD_FAST | 1,680 | 7.4% |
| BUILD_LIST | 1,280 | 5.7% |
| PUSH_NULL | 1,200 | 5.3% |
| CALL | 900 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,900 | 74.7% |
| STORE_FAST | 1,240 | 5.5% |
| CALL | 900 | 4.0% |
| CALL_BUILTIN_CLASS | 740 | 3.3% |
| GET_ITER | 600 | 2.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 400 | 50.0% |
| LOAD_FAST | 400 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 400 | 50.0% |
| RESUME_CHECK | 300 | 37.5% |
| RESUME | 100 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 400 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,809,640 | 100.0% |
| COMPARE_OP | 2,720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| BINARY_OP | 80 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,809,620 | 100.0% |
| COMPARE_OP | 2,720 | 0.0% |
| COMPARE_OP_INT | 540 | 0.0% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |
| COMPARE_OP_FLOAT | 40 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 75.0% |
| RESUME | 100 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 68,564,900 | 70.8% |
| STORE_FAST | 13,257,180 | 13.7% |
| FOR_ITER_RANGE | 8,673,680 | 9.0% |
| POP_JUMP_IF_TRUE | 2,073,880 | 2.1% |
| POP_JUMP_IF_FALSE | 2,044,160 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 34,724,420 | 35.8% |
| SWAP | 24,671,680 | 25.5% |
| POP_JUMP_IF_FALSE | 13,619,040 | 14.1% |
| FOR_ITER_RANGE | 10,137,100 | 10.5% |
| BINARY_OP_SUBTRACT_FLOAT | 8,031,740 | 8.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 940 | 54.0% |
| GET_ITER | 700 | 40.2% |
| FOR_ITER | 60 | 3.4% |
| SWAP | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 620 | 35.6% |
| STORE_FAST | 580 | 33.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 360 | 20.7% |
| FOR_ITER | 60 | 3.4% |
| UNPACK_SEQUENCE | 60 | 3.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 803,740 | 99.0% |
| FOR_ITER_RANGE | 2,800 | 0.3% |
| STORE_FAST | 1,360 | 0.2% |
| POP_TOP | 920 | 0.1% |
| POP_JUMP_IF_TRUE | 760 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 799,980 | 98.6% |
| FOR_ITER_RANGE | 9,080 | 1.1% |
| FOR_ITER | 940 | 0.1% |
| ENTER_EXECUTOR | 660 | 0.1% |
| LOAD_CONST | 320 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 92,198,400 | 97.9% |
| STORE_FAST | 1,995,680 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,094,880 | 51.1% |
| LOAD_CONST | 46,099,200 | 48.9% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 400 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,000 | 51.0% |
| LOAD_FAST_LOAD_FAST | 1,120 | 28.6% |
| LOAD_GLOBAL | 360 | 9.2% |
| LOAD_GLOBAL_MODULE | 360 | 9.2% |
| STORE_FAST_LOAD_FAST | 40 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 680 | 17.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 660 | 16.8% |
| LOAD_FAST | 540 | 13.8% |
| BINARY_OP | 460 | 11.7% |
| LOAD_ATTR_MODULE | 360 | 9.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,344,480 | 33.7% |
| RESUME_CHECK | 46,103,620 | 20.3% |
| JUMP_FORWARD | 46,099,200 | 20.3% |
| LOAD_FAST_LOAD_FAST | 39,952,720 | 17.6% |
| BINARY_OP_ADD_FLOAT | 7,999,980 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,304,360 | 44.3% |
| BINARY_OP_ADD_INT | 46,345,200 | 20.5% |
| BINARY_OP_SUBTRACT_INT | 32,212,880 | 14.2% |
| COMPARE_OP_INT | 26,027,600 | 11.5% |
| COMPARE_OP | 8,809,640 | 3.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 400 | 33.3% |
| BUILD_LIST | 400 | 33.3% |
| RESUME_CHECK | 300 | 25.0% |
| RESUME | 100 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 800 | 66.7% |
| LIST_EXTEND | 400 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 209,726,620 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 156,290,380 | 17.2% |
| LOAD_CONST | 100,304,360 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 93,953,340 | 10.4% |
| RETURN_VALUE | 79,619,760 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 248,528,160 | 27.4% |
| SWAP | 92,198,400 | 10.2% |
| LOAD_GLOBAL_BUILTIN | 80,450,240 | 8.9% |
| BINARY_SUBSCR_LIST_INT | 79,635,080 | 8.8% |
| LOAD_CONST | 76,344,480 | 8.4% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 61,339,520 | 18.7% |
| STORE_FAST | 48,639,920 | 14.9% |
| JUMP_FORWARD | 48,094,880 | 14.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 46,099,160 | 14.1% |
| POP_JUMP_IF_FALSE | 25,947,700 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 67,481,180 | 20.6% |
| BINARY_SUBSCR_GETITEM | 52,592,480 | 16.1% |
| CALL_PY_EXACT_ARGS | 46,111,440 | 14.1% |
| LOAD_CONST | 39,952,720 | 12.2% |
| STORE_ATTR_INSTANCE_VALUE | 26,499,980 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,880 | 47.5% |
| FOR_ITER_RANGE | 320 | 8.1% |
| RESUME | 280 | 7.1% |
| RESUME_CHECK | 280 | 7.1% |
| RETURN_VALUE | 200 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,020 | 25.8% |
| LOAD_GLOBAL_MODULE | 960 | 24.2% |
| LOAD_FAST | 740 | 18.7% |
| LOAD_CONST | 500 | 12.6% |
| LOAD_ATTR | 360 | 9.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 215,842,620 | 65.0% |
| TO_BOOL_BOOL | 93,818,820 | 28.3% |
| ENTER_EXECUTOR | 13,619,040 | 4.1% |
| COMPARE_OP | 8,809,620 | 2.7% |
| EXTENDED_ARG | 8,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 209,726,620 | 63.2% |
| JUMP_FORWARD | 92,198,400 | 27.8% |
| LOAD_FAST_LOAD_FAST | 25,947,700 | 7.8% |
| ENTER_EXECUTOR | 2,044,160 | 0.6% |
| LOAD_CONST | 2,012,240 | 0.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 8,395,960 | 99.9% |
| COMPARE_OP_INT | 7,980 | 0.1% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,321,440 | 75.2% |
| ENTER_EXECUTOR | 2,073,880 | 24.7% |
| LOAD_GLOBAL_BUILTIN | 7,880 | 0.1% |
| JUMP_BACKWARD | 760 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 8,483,220 | 99.5% |
| STORE_SUBSCR_LIST_INT | 15,180 | 0.2% |
| FOR_ITER_RANGE | 12,240 | 0.1% |
| POP_JUMP_IF_FALSE | 8,000 | 0.1% |
| POP_TOP | 4,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 8,498,700 | 99.7% |
| POP_TOP | 24,560 | 0.3% |
| EXIT_INIT_CHECK | 180 | 0.0% |
| END_FOR | 80 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920 | 63.9% |
| LOAD_FAST_LOAD_FAST | 520 | 36.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 720 | 50.0% |
| LOAD_CONST | 240 | 16.7% |
| LOAD_FAST | 160 | 11.1% |
| LOAD_GLOBAL | 160 | 11.1% |
| RETURN_CONST | 120 | 8.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 25,592,420 | 32.4% |
| BINARY_OP_ADD_INT | 13,317,760 | 16.8% |
| RETURN_VALUE | 12,484,020 | 15.8% |
| BINARY_OP_SUBTRACT_FLOAT | 9,018,100 | 11.4% |
| STORE_FAST_STORE_FAST | 8,801,120 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,639,920 | 61.5% |
| LOAD_FAST | 14,804,600 | 18.7% |
| ENTER_EXECUTOR | 13,257,180 | 16.8% |
| JUMP_FORWARD | 1,995,680 | 2.5% |
| LOAD_CONST | 213,700 | 0.3% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 46,899,520 | 84.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,801,120 | 15.8% |
| LOAD_ATTR | 80 | 0.0% |
| UNPACK_SEQUENCE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,216,000 | 70.4% |
| STORE_FAST | 8,801,120 | 15.8% |
| LOAD_FAST_LOAD_FAST | 7,683,600 | 13.8% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 50.0% |
| FOR_ITER | 60 | 37.5% |
| YIELD_VALUE | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 80 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 420 | 50.0% |
| CACHE | 180 | 21.4% |
| CALL_FUNCTION_EX | 100 | 11.9% |
| COPY_FREE_VARS | 100 | 11.9% |
| POP_TOP | 20 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 33.3% |
| LOAD_GLOBAL | 280 | 33.3% |
| LOAD_DEREF | 100 | 11.9% |
| LOAD_FAST_LOAD_FAST | 100 | 11.9% |
| LOAD_CONST | 60 | 7.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 23,049,480 | 41.7% |
| LOAD_FAST | 16,369,120 | 29.6% |
| BINARY_OP_MULTIPLY_FLOAT | 15,828,860 | 28.6% |
| BINARY_OP | 8,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,125,800 | 41.9% |
| SWAP | 16,369,200 | 29.6% |
| LOAD_CONST | 7,999,980 | 14.5% |
| BINARY_OP_MULTIPLY_FLOAT | 7,683,160 | 13.9% |
| STORE_FAST | 73,560 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,393,460 | 46.5% |
| LOAD_CONST | 46,345,200 | 46.5% |
| LOAD_FAST_LOAD_FAST | 6,945,000 | 7.0% |
| BINARY_OP | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 46,099,180 | 46.2% |
| STORE_FAST | 13,317,760 | 13.4% |
| STORE_SUBSCR | 8,262,280 | 8.3% |
| BINARY_SUBSCR | 8,195,380 | 8.2% |
| COPY | 8,184,600 | 8.2% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 26,268,940 | 36.5% |
| LOAD_FAST_LOAD_FAST | 16,144,360 | 22.4% |
| CALL_BUILTIN_CLASS | 13,376,760 | 18.6% |
| RETURN_VALUE | 7,683,160 | 10.7% |
| BINARY_OP_ADD_FLOAT | 7,683,160 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 26,557,160 | 36.9% |
| BINARY_OP_ADD_FLOAT | 15,828,860 | 22.0% |
| RETURN_VALUE | 13,368,600 | 18.6% |
| LOAD_FAST_LOAD_FAST | 8,000,980 | 11.1% |
| LOAD_CONST | 7,691,480 | 10.7% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 46,099,160 | 99.1% |
| BINARY_OP_ADD_INT | 153,680 | 0.3% |
| LOAD_FAST | 89,140 | 0.2% |
| LOAD_CONST | 84,640 | 0.2% |
| LOAD_FAST_LOAD_FAST | 77,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,099,180 | 99.1% |
| STORE_FAST | 248,300 | 0.5% |
| CALL_BUILTIN_CLASS | 80,500 | 0.2% |
| LOAD_FAST_LOAD_FAST | 76,700 | 0.2% |
| BINARY_OP | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 26,557,160 | 44.8% |
| LOAD_FAST | 15,949,060 | 26.9% |
| BINARY_SUBSCR | 8,801,000 | 14.8% |
| ENTER_EXECUTOR | 8,031,740 | 13.5% |
| BINARY_OP | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,267,980 | 44.3% |
| LOAD_FAST_LOAD_FAST | 24,052,940 | 40.5% |
| STORE_FAST | 9,018,100 | 15.2% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,212,880 | 96.8% |
| LOAD_FAST_LOAD_FAST | 1,080,440 | 3.2% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 25,592,420 | 76.9% |
| LOAD_FAST | 7,683,180 | 23.1% |
| COMPARE_OP_INT | 15,920 | 0.0% |
| BUILD_TUPLE | 1,000 | 0.0% |
| CALL_BUILTIN_CLASS | 1,000 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 66.7% |
| CALL | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,581,820 | 99.4% |
| BINARY_OP_MULTIPLY_INT | 80,500 | 0.6% |
| BINARY_OP_SUBTRACT_INT | 1,000 | 0.0% |
| CALL | 740 | 0.0% |
| BINARY_SUBSCR | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 13,376,760 | 97.9% |
| GET_ITER | 284,060 | 2.1% |
| BINARY_OP | 4,060 | 0.0% |
| STORE_FAST | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 403,920 | 96.0% |
| LOAD_FAST | 8,400 | 2.0% |
| BINARY_OP | 8,280 | 2.0% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 420,740 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,111,440 | 89.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,276,660 | 10.3% |
| LOAD_FAST | 4,760 | 0.0% |
| LOAD_CONST | 4,320 | 0.0% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 51,397,660 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,999,960 | 95.3% |
| LOAD_FAST_LOAD_FAST | 395,960 | 4.7% |
| COMPARE_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 8,395,960 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 92,198,320 | 42.7% |
| COPY | 92,198,320 | 42.7% |
| LOAD_CONST | 26,027,600 | 12.1% |
| LOAD_FAST_LOAD_FAST | 5,409,920 | 2.5% |
| BINARY_OP_SUBTRACT_INT | 15,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 215,842,620 | 100.0% |
| POP_JUMP_IF_TRUE | 7,980 | 0.0% |
| EXTENDED_ARG | 7,980 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 10,137,100 | 97.2% |
| GET_ITER | 284,140 | 2.7% |
| JUMP_BACKWARD | 9,080 | 0.1% |
| FOR_ITER | 620 | 0.0% |
| SWAP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,673,680 | 83.2% |
| LOAD_FAST_LOAD_FAST | 1,295,920 | 12.4% |
| STORE_FAST | 285,100 | 2.7% |
| LOAD_GLOBAL_BUILTIN | 80,000 | 0.8% |
| LOAD_FAST | 79,980 | 0.8% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 248,528,160 | 78.5% |
| LOAD_FAST_LOAD_FAST | 67,481,180 | 21.3% |
| ENTER_EXECUTOR | 749,100 | 0.2% |
| LOAD_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,290,380 | 49.3% |
| COMPARE_OP_INT | 92,198,320 | 29.1% |
| BINARY_OP_MULTIPLY_INT | 46,099,160 | 14.6% |
| TO_BOOL_BOOL | 13,368,480 | 4.2% |
| STORE_FAST_STORE_FAST | 8,801,120 | 2.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,375,620 | 100.0% |
| STORE_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR | 260 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,099,160 | 89.7% |
| CALL_PY_EXACT_ARGS | 5,276,660 | 10.3% |
| LOAD_FAST | 300 | 0.0% |
| CALL | 100 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 25,440 | 98.6% |
| LOAD_ATTR | 360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 17,500 | 67.8% |
| BINARY_OP_MULTIPLY_FLOAT | 8,280 | 32.1% |
| BINARY_OP | 20 | 0.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,372,680 | 71.8% |
| LOAD_FAST_LOAD_FAST | 5,261,220 | 28.2% |
| ENTER_EXECUTOR | 2,880 | 0.0% |
| LOAD_ATTR | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 13,368,480 | 71.7% |
| BINARY_OP | 5,260,680 | 28.2% |
| LOAD_CONST | 4,020 | 0.0% |
| LOAD_FAST | 4,020 | 0.0% |
| CALL | 180 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80,450,480 | 46.1% |
| LOAD_FAST | 80,450,240 | 46.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 13,368,480 | 7.7% |
| STORE_FAST | 128,380 | 0.1% |
| FOR_ITER_RANGE | 80,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,953,340 | 53.8% |
| CALL_ISINSTANCE | 80,450,240 | 46.1% |
| LOAD_CONST | 161,740 | 0.1% |
| LOAD_FAST_LOAD_FAST | 9,840 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,080 | 45.3% |
| POP_JUMP_IF_FALSE | 12,320 | 25.3% |
| BINARY_OP | 8,280 | 17.0% |
| POP_TOP | 4,000 | 8.2% |
| LOAD_GLOBAL | 960 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 25,440 | 52.2% |
| LOAD_FAST_LOAD_FAST | 17,000 | 34.9% |
| LOAD_FAST | 4,500 | 9.2% |
| LOAD_CONST | 1,420 | 2.9% |
| LOAD_ATTR | 360 | 0.7% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 118,050,820 | 65.0% |
| CALL_PY_EXACT_ARGS | 51,397,660 | 28.3% |
| CACHE | 8,498,820 | 4.7% |
| ENTER_EXECUTOR | 2,775,240 | 1.5% |
| FOR_ITER_GEN | 799,980 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 80,450,480 | 44.3% |
| LOAD_FAST | 54,167,820 | 29.8% |
| LOAD_CONST | 46,103,620 | 25.4% |
| POP_TOP | 799,980 | 0.4% |
| LOAD_GLOBAL_MODULE | 560 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,499,980 | 100.0% |
| LOAD_FAST | 1,000 | 0.0% |
| STORE_ATTR | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,499,860 | 100.0% |
| LOAD_CONST | 720 | 0.0% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% |
| LOAD_FAST_LOAD_FAST | 200 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 80,450,240 | 85.8% |
| LOAD_ATTR_INSTANCE_VALUE | 13,368,480 | 14.2% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 93,818,820 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,532,800 | 80.4% |
| BINARY_OP_ADD_INT | 7,683,180 | 19.6% |
| BINARY_OP_SUBTRACT_INT | 1,000 | 0.0% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 30,733,620 | 78.4% |
| STORE_SUBSCR | 8,483,200 | 21.6% |
| YIELD_VALUE | 720 | 0.0% |
| BINARY_SUBSCR | 200 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 92,198,400 | 51.7% |
| COPY | 43,037,600 | 24.1% |
| LOAD_FAST | 26,664,000 | 15.0% |
| LOAD_FAST_LOAD_FAST | 8,188,960 | 4.6% |
| BINARY_OP_ADD_INT | 8,184,600 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 92,198,320 | 51.7% |
| BINARY_SUBSCR | 43,037,600 | 24.1% |
| COPY | 43,037,600 | 24.1% |
| COMPARE_OP | 80 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,198,400 | 45.4% |
| SWAP | 43,037,600 | 21.2% |
| BINARY_OP_SUBTRACT_FLOAT | 26,267,980 | 12.9% |
| ENTER_EXECUTOR | 24,671,680 | 12.2% |
| BINARY_OP_ADD_FLOAT | 16,369,200 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 92,198,400 | 45.4% |
| STORE_SUBSCR | 67,709,280 | 33.4% |
| SWAP | 43,037,600 | 21.2% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.0% |
| BUILD_LIST | 240 | 0.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 52,592,480 | 44.6% |
| ENTER_EXECUTOR | 34,724,420 | 29.4% |
| BUILD_TUPLE | 30,733,620 | 26.0% |
| BINARY_SUBSCR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 118,050,820 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,099,120 | 98.3% |
| YIELD_VALUE | 799,960 | 1.7% |
| FOR_ITER | 360 | 0.0% |
| UNPACK_SEQUENCE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 46,899,520 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 92,940 | 85.3% |
| BINARY_OP | 16,000 | 14.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 108,260 | 99.4% |
| JUMP_BACKWARD | 680 | 0.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 240 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 799,280 | 99.9% |
| BUILD_TUPLE | 720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 799,960 | 100.0% |
| INTERPRETER_EXIT | 20 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,635,080 | 99.0% |
| BINARY_SUBSCR_TUPLE_INT | 799,960 | 1.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 79,635,100 | 99.0% |
| LOAD_FAST | 799,980 | 1.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,599,920 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 799,980 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 799,960 | 50.0% |
| BINARY_SUBSCR | 20 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 80,450,240 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 80,450,240 | 100.0% |
| TO_BOOL | 40 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 799,980 | 100.0% |
| GET_ITER | 60 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 799,980 | 100.0% |
| POP_TOP | 60 | 0.0% |
| RESUME | 20 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,160 | 99.9% |
| STORE_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 15,180 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 72,000 | 90.0% |
| COMPARE_OP_INT | 7,980 | 10.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 71,660 | 89.6% |
| POP_JUMP_IF_FALSE | 8,000 | 10.0% |
| JUMP_BACKWARD | 340 | 0.4% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 380 | 95.0% |
| FOR_ITER | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 90.0% |
| LOAD_ATTR | 40 | 10.0% |


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
|     deferred | 6,472,360 | 1.7% |
|          hit | 366,095,320 | 98.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,460 | 26.2% |
| Failure | 6,940 | 73.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 2,000 | 28.8% |
| multiply different types | 1,400 | 20.2% |
| true divide other | 840 | 12.1% |
| remainder | 780 | 11.2% |
| rshift | 600 | 8.6% |
| lshift | 420 | 6.1% |
| true divide float | 420 | 6.1% |
| floor divide | 340 | 4.9% |
| true divide different types | 140 | 2.0% |


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
|     deferred | 160,374,900 | 44.5% |
|          hit | 200,085,860 | 55.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 0.8% |
| Failure | 44,380 | 99.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 44,380 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,280 | 0.0% |
|          hit | 145,934,160 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,480 | 63.2% |
| Failure | 860 | 36.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 420 | 48.8% |
| cfunc noargs | 300 | 34.9% |
| cfunc varargs keywords | 80 | 9.3% |
| wrong number arguments | 60 | 7.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,809,700 | 3.8% |
|          hit | 224,254,540 | 96.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 580 | 17.6% |
| Failure | 2,720 | 82.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 2,720 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,040 | 0.0% |
|          hit | 11,231,200 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 640 | 91.4% |
| Failure | 60 | 8.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| zip | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,960 | 0.0% |
|          hit | 386,786,400 | 100.0% |
|         miss | 12,240 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,960 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,980 | 0.0% |
|          hit | 174,623,920 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,980 | 100.0% |
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
|     deferred | 720 | 0.0% |
|          hit | 26,501,700 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 720 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 115,242,920 | 100.0% |
|          hit | 15,180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.1% |
| Failure | 32,760 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 30,040 | 91.7% |
| py simple | 2,720 | 8.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 93,818,820 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 0.0% |
|          hit | 46,899,520 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,405,078,420 | 49.1% |
| Not specialized | 631,527,160 | 12.9% |
| Specialized hits | 1,857,770,040 | 38.0% |
| Specialized misses | 12,240 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 160,374,900 | 55.1% |
| STORE_SUBSCR | 115,242,920 | 39.6% |
| COMPARE_OP | 8,809,700 | 3.0% |
| BINARY_OP | 6,472,360 | 2.2% |
| CALL | 20,280 | 0.0% |
| LOAD_GLOBAL | 1,980 | 0.0% |
| LOAD_ATTR | 1,960 | 0.0% |
| FOR_ITER | 1,040 | 0.0% |
| STORE_ATTR | 720 | 0.0% |
| TO_BOOL | 100 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 12,240 | 100.0% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| BUILD_LIST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,499,020 | 4.8% |
| Calls to Python functions inlined | 170,250,080 | 95.2% |
| Calls via PyEval_EvalFrame (total) | 8,499,020 | 4.8% |
| Calls via PyEval_EvalFrame (vector) | 8,499,000 | 4.8% |
| Calls via PyEval_EvalFrame (generator) | 20 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,499,000 | 4.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 8,498,700 | 4.8% |
| Calls via PyEval_EvalFrame (function ex) | 800 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 181,146,760 | 101.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 818,723,360 | 57.5% |
| Frees to freelist | 818,725,940 |  |
| Allocations | 606,286,540 | 42.5% |
| Allocations to 512 bytes | 606,269,500 | 42.5% |
| Allocations to 4 kbytes | 16,480 | 0.0% |
| Allocations over 4 kbytes | 560 | 0.0% |
| Frees | 606,286,585 |  |
| New values | 300 |  |
| Interpreter increfs | 3,638,733,460 | 83.4% |
| Interpreter decrefs | 5,080,443,760 | 87.8% |
| Increfs | 722,599,781 | 16.6% |
| Decrefs | 705,861,054 | 12.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 16,112 |  |
| Method cache misses | 1,128 |  |
| Method cache collisions | 903 |  |
| Method cache dunder hits | 88,196,560 |  |
| Method cache dunder misses | 280 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,980 | 135,840 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,180 |  |
| Traces created | 660 | 55.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 100 | 8.5% |
| Trace too short | 520 | 44.1% |
| Inner loop found | 80 | 6.8% |
| Recursive call | 0 | 0.0% |
| Traces executed | 96,884,260 |  |
| Uops executed | 9,098,910,060 | 93.92 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 6.1% |
| <= 32 | 120 | 18.2% |
| <= 64 | 160 | 24.2% |
| <= 128 | 160 | 24.2% |
| <= 256 | 180 | 27.3% |


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
| <= 16 | 160 | 24.2% |
| <= 32 | 160 | 24.2% |
| <= 64 | 40 | 6.1% |
| <= 128 | 200 | 30.3% |
| <= 256 | 100 | 15.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 8,701,020 | 9.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 27,461,680 | 28.3% |
| <= 32 | 12,722,620 | 13.1% |
| <= 64 | 6,248,200 | 6.4% |
| <= 128 | 10,751,480 | 11.1% |
| <= 256 | 29,553,060 | 30.5% |
| <= 512 | 22,760 | 0.0% |
| <= 1,024 | 11,400 | 0.0% |
| <= 2,048 | 1,368,040 | 1.4% |
| <= 4,096 | 8,000 | 0.0% |
| <= 8,192 | 8,000 | 0.0% |
| <= 16,384 | 8,000 | 0.0% |
| <= 32,768 | 8,000 | 0.0% |
| <= 65,536 | 12,000 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,092,872,000 | 23.0% | 23.0% |  |
| _SET_IP | 1,305,156,040 | 14.3% | 37.3% |  |
| _CHECK_VALIDITY | 861,762,240 | 9.5% | 46.8% |  |
| STORE_FAST | 600,442,180 | 6.6% | 53.4% |  |
| _GUARD_BOTH_FLOAT | 547,560,060 | 6.0% | 59.4% |  |
| _BINARY_SUBSCR | 456,053,080 | 5.0% | 64.4% |  |
| _GUARD_BOTH_INT | 384,579,760 | 4.2% | 68.7% |  |
| LOAD_CONST | 327,447,320 | 3.6% | 72.3% |  |
| _BINARY_OP_ADD_INT | 268,505,620 | 3.0% | 75.2% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 246,691,440 | 2.7% | 77.9% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 188,874,940 | 2.1% | 80.0% | 5.4% |
| _ITER_CHECK_RANGE | 188,874,940 | 2.1% | 82.1% |  |
| _ITER_NEXT_RANGE | 178,737,840 | 2.0% | 84.0% |  |
| _BINARY_OP_ADD_FLOAT | 170,284,860 | 1.9% | 85.9% |  |
| COPY | 147,476,800 | 1.6% | 87.5% |  |
| _STORE_SUBSCR | 138,642,700 | 1.5% | 89.1% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 130,583,760 | 1.4% | 90.5% |  |
| SWAP | 122,805,120 | 1.3% | 91.9% |  |
| _BINARY_OP_MULTIPLY_INT | 93,862,420 | 1.0% | 92.9% |  |
| _JUMP_TO_TOP | 86,296,700 | 0.9% | 93.8% |  |
| _EXIT_TRACE | 73,125,160 | 0.8% | 94.6% |  |
| _GUARD_TYPE_VERSION | 58,940,820 | 0.6% | 95.3% |  |
| _BINARY_OP | 35,078,340 | 0.4% | 95.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 32,998,200 | 0.4% | 96.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 32,998,200 | 0.4% | 96.4% |  |
| COMPARE_OP_INT | 27,241,600 | 0.3% | 96.7% |  |
| _GUARD_IS_TRUE_POP | 22,777,600 | 0.3% | 96.9% | 46.2% |
| _BINARY_OP_SUBTRACT_INT | 22,211,720 | 0.2% | 97.2% |  |
| _GUARD_KEYS_VERSION | 18,514,720 | 0.2% | 97.4% | 0.0% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 18,514,720 | 0.2% | 97.6% |  |
| _GUARD_IS_FALSE_POP | 16,221,960 | 0.2% | 97.8% | 19.1% |
| _GUARD_GLOBALS_VERSION | 14,164,020 | 0.2% | 97.9% |  |
| _GUARD_BUILTINS_VERSION | 13,922,660 | 0.2% | 98.1% |  |
| _LOAD_GLOBAL_BUILTINS | 13,922,660 | 0.2% | 98.2% |  |
| CALL_BUILTIN_CLASS | 13,527,620 | 0.1% | 98.4% |  |
| _CHECK_PEP_523 | 11,697,860 | 0.1% | 98.5% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 11,697,860 | 0.1% | 98.6% |  |
| _CHECK_STACK_SPACE | 11,697,860 | 0.1% | 98.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 11,697,860 | 0.1% | 98.9% |  |
| _PUSH_FRAME | 11,697,860 | 0.1% | 99.0% |  |
| _SAVE_RETURN_OFFSET | 11,697,860 | 0.1% | 99.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 11,687,060 | 0.1% | 99.3% |  |
| GET_ITER | 9,860,700 | 0.1% | 99.4% |  |
| RESUME_CHECK | 8,922,620 | 0.1% | 99.5% |  |
| BUILD_TUPLE | 8,481,460 | 0.1% | 99.6% |  |
| _COMPARE_OP | 8,162,720 | 0.1% | 99.7% |  |
| _GUARD_DORV_VALUES | 7,427,900 | 0.1% | 99.8% |  |
| _STORE_ATTR_INSTANCE_VALUE | 7,427,900 | 0.1% | 99.8% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 6,824,780 | 0.1% | 99.9% |  |
| TO_BOOL_BOOL | 3,595,240 | 0.0% | 99.9% |  |
| _POP_FRAME | 3,595,240 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_MODULE | 241,360 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 215,040 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 215,040 | 0.0% | 100.0% |  |
| PUSH_NULL | 143,360 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 143,360 | 0.0% | 100.0% |  |
| LIST_APPEND | 70,900 | 0.0% | 100.0% |  |
| BUILD_LIST | 15,520 | 0.0% | 100.0% |  |
| _FOR_ITER_TIER_TWO | 7,680 | 0.0% | 100.0% | 1.0% |
| STORE_SLICE | 7,600 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,600 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 520 |
| BINARY_SUBSCR_GETITEM | 180 |
| YIELD_VALUE | 40 |
| CALL | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 100 |


</details>

---
Stats gathered on: 2023-11-18
