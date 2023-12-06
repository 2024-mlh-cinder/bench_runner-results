
# Pystats results

- benchmark: scimark
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 855,564,320 | 19.4% | 19.4% |  |
| POP_JUMP_IF_FALSE | 325,267,860 | 7.4% | 26.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 303,372,020 | 6.9% | 33.7% |  |
| LOAD_FAST_LOAD_FAST | 270,397,020 | 6.1% | 39.8% |  |
| COMPARE_OP_INT | 212,252,720 | 4.8% | 44.6% |  |
| LOAD_CONST | 189,274,080 | 4.3% | 48.9% |  |
| RESUME_CHECK | 178,720,520 | 4.1% | 53.0% |  |
| RETURN_VALUE | 175,916,060 | 4.0% | 57.0% |  |
| LOAD_GLOBAL_BUILTIN | 172,962,960 | 3.9% | 60.9% |  |
| SWAP | 145,868,240 | 3.3% | 64.2% |  |
| COPY | 145,859,920 | 3.3% | 67.5% |  |
| BINARY_SUBSCR | 129,069,360 | 2.9% | 70.4% |  |
| BINARY_SUBSCR_GETITEM | 118,050,820 | 2.7% | 73.1% |  |
| JUMP_FORWARD | 94,194,080 | 2.1% | 75.2% |  |
| TO_BOOL_BOOL | 92,206,580 | 2.1% | 77.3% |  |
| CALL_ISINSTANCE | 80,450,280 | 1.8% | 79.2% |  |
| BINARY_SUBSCR_LIST_INT | 80,435,080 | 1.8% | 81.0% |  |
| BINARY_OP_ADD_INT | 74,440,440 | 1.7% | 82.7% |  |
| ENTER_EXECUTOR | 71,207,300 | 1.6% | 84.3% |  |
| BINARY_OP_MULTIPLY_FLOAT | 67,236,180 | 1.5% | 85.8% |  |
| STORE_FAST | 64,841,980 | 1.5% | 87.3% |  |
| STORE_SUBSCR | 56,379,540 | 1.3% | 88.6% |  |
| STORE_FAST_STORE_FAST | 52,148,800 | 1.2% | 89.8% |  |
| CALL_PY_EXACT_ARGS | 51,370,060 | 1.2% | 90.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 51,348,620 | 1.2% | 92.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,899,520 | 1.1% | 93.1% |  |
| BINARY_OP_MULTIPLY_INT | 46,504,780 | 1.1% | 94.2% |  |
| BINARY_OP_SUBTRACT_FLOAT | 39,652,160 | 0.9% | 95.1% |  |
| BUILD_TUPLE | 39,217,740 | 0.9% | 96.0% |  |
| BINARY_OP_ADD_FLOAT | 37,464,320 | 0.8% | 96.8% |  |
| BINARY_OP_SUBTRACT_INT | 29,943,460 | 0.7% | 97.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 23,151,560 | 0.5% | 98.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 15,873,980 | 0.4% | 98.4% | 0.1% |
| CALL_BUILTIN_CLASS | 12,053,000 | 0.3% | 98.7% |  |
| FOR_ITER_RANGE | 10,431,140 | 0.2% | 98.9% |  |
| RETURN_CONST | 8,523,520 | 0.2% | 99.1% |  |
| INTERPRETER_EXIT | 8,499,020 | 0.2% | 99.3% |  |
| POP_JUMP_IF_TRUE | 7,398,720 | 0.2% | 99.5% |  |
| COMPARE_OP_FLOAT | 6,811,380 | 0.2% | 99.6% |  |
| BINARY_OP | 5,330,260 | 0.1% | 99.7% |  |
| COMPARE_OP | 5,260,140 | 0.1% | 99.9% |  |
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
| LOAD_FAST_AND_CLEAR | 240 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 240 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 237,758,120 | 5.4% | 5.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 212,236,760 | 4.8% | 10.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 204,764,240 | 4.6% | 14.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 148,067,520 | 3.4% | 18.2% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 118,050,820 | 2.7% | 20.9% |
| LOAD_CONST LOAD_FAST | 100,304,360 | 2.3% | 23.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 92,341,100 | 2.1% | 25.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 92,206,580 | 2.1% | 27.4% |
| LOAD_FAST SWAP | 92,198,400 | 2.1% | 29.4% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 92,198,400 | 2.1% | 31.5% |
| SWAP COPY | 92,198,400 | 2.1% | 33.6% |
| COPY COMPARE_OP_INT | 92,198,320 | 2.1% | 35.7% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 92,198,320 | 2.1% | 37.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 80,450,480 | 1.8% | 39.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 80,450,240 | 1.8% | 41.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 80,450,240 | 1.8% | 43.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 80,450,240 | 1.8% | 45.1% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 79,635,100 | 1.8% | 46.9% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 79,635,080 | 1.8% | 48.7% |
| RETURN_VALUE LOAD_FAST | 79,619,760 | 1.8% | 50.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 65,613,220 | 1.5% | 52.0% |
| LOAD_FAST LOAD_CONST | 64,831,200 | 1.5% | 53.5% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 57,787,520 | 1.3% | 54.8% |
| LOAD_FAST BINARY_SUBSCR | 52,955,960 | 1.2% | 56.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 52,592,480 | 1.2% | 57.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 51,370,000 | 1.2% | 58.4% |
| RESUME_CHECK LOAD_FAST | 51,364,920 | 1.2% | 59.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 51,347,960 | 1.2% | 60.7% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 48,094,880 | 1.1% | 61.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 46,899,520 | 1.1% | 62.9% |
| LOAD_FAST BINARY_OP_ADD_INT | 46,393,460 | 1.1% | 63.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 46,111,440 | 1.0% | 64.9% |
| RESUME_CHECK LOAD_CONST | 46,103,620 | 1.0% | 66.0% |
| JUMP_FORWARD LOAD_CONST | 46,099,200 | 1.0% | 67.0% |
| BINARY_OP_ADD_INT RETURN_VALUE | 46,099,180 | 1.0% | 68.1% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 46,099,180 | 1.0% | 69.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 46,099,160 | 1.0% | 70.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 46,099,160 | 1.0% | 71.2% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 46,099,120 | 1.0% | 72.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 39,216,000 | 0.9% | 73.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 39,001,980 | 0.9% | 74.0% |
| BINARY_SUBSCR RETURN_VALUE | 38,416,020 | 0.9% | 74.9% |
| RETURN_VALUE BINARY_SUBSCR | 38,416,000 | 0.9% | 75.8% |
| STORE_SUBSCR ENTER_EXECUTOR | 35,789,800 | 0.8% | 76.6% |
| ENTER_EXECUTOR BINARY_SUBSCR_GETITEM | 34,724,420 | 0.8% | 77.4% |
| LOAD_FAST BUILD_TUPLE | 31,532,800 | 0.7% | 78.1% |
| BUILD_TUPLE BINARY_SUBSCR_GETITEM | 30,733,620 | 0.7% | 78.8% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 28,862,740 | 0.7% | 79.5% |
| COPY BINARY_SUBSCR | 26,830,760 | 0.6% | 80.1% |
| COPY COPY | 26,830,760 | 0.6% | 80.7% |
| SWAP STORE_SUBSCR | 26,830,760 | 0.6% | 81.3% |
| SWAP SWAP | 26,830,760 | 0.6% | 81.9% |
| LOAD_FAST COPY | 26,664,000 | 0.6% | 82.5% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 26,557,160 | 0.6% | 83.1% |
| BINARY_SUBSCR BINARY_OP_MULTIPLY_FLOAT | 26,268,940 | 0.6% | 83.7% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 26,267,980 | 0.6% | 84.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 25,360,740 | 0.6% | 84.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 24,079,740 | 0.5% | 85.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 23,149,840 | 0.5% | 85.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 23,149,720 | 0.5% | 86.5% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 23,125,800 | 0.5% | 87.0% |
| RETURN_VALUE BINARY_OP_ADD_FLOAT | 23,049,480 | 0.5% | 87.5% |
| LOAD_CONST COMPARE_OP_INT | 22,421,740 | 0.5% | 88.0% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 22,242,280 | 0.5% | 88.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 21,101,340 | 0.5% | 89.0% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 15,714,140 | 0.4% | 89.4% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 15,558,800 | 0.4% | 89.7% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 14,244,280 | 0.3% | 90.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 12,975,200 | 0.3% | 90.3% |
| BINARY_OP_ADD_INT STORE_FAST | 12,312,480 | 0.3% | 90.6% |
| LOAD_FAST STORE_SUBSCR | 12,308,340 | 0.3% | 90.9% |
| STORE_FAST ENTER_EXECUTOR | 12,251,900 | 0.3% | 91.2% |
| LOAD_FAST CALL_BUILTIN_CLASS | 11,969,580 | 0.3% | 91.4% |
| CALL_BUILTIN_CLASS BINARY_OP_MULTIPLY_FLOAT | 11,764,520 | 0.3% | 91.7% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,760,440 | 0.3% | 92.0% |
| BINARY_OP_MULTIPLY_FLOAT RETURN_VALUE | 11,756,360 | 0.3% | 92.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 11,756,240 | 0.3% | 92.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_GLOBAL_BUILTIN | 11,756,240 | 0.3% | 92.8% |
| STORE_FAST LOAD_FAST | 11,224,940 | 0.3% | 93.0% |
| STORE_SUBSCR LOAD_FAST | 11,016,300 | 0.2% | 93.3% |
| RETURN_VALUE STORE_FAST | 10,871,780 | 0.2% | 93.5% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 10,664,860 | 0.2% | 93.8% |
| ENTER_EXECUTOR FOR_ITER_RANGE | 10,137,100 | 0.2% | 94.0% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 9,389,920 | 0.2% | 94.2% |
| FOR_ITER_RANGE ENTER_EXECUTOR | 8,673,680 | 0.2% | 94.4% |
| CACHE RESUME_CHECK | 8,498,820 | 0.2% | 94.6% |
| RETURN_CONST INTERPRETER_EXIT | 8,498,700 | 0.2% | 94.8% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 8,490,760 | 0.2% | 95.0% |
| STORE_SUBSCR RETURN_CONST | 8,483,220 | 0.2% | 95.2% |
| BUILD_TUPLE STORE_SUBSCR | 8,483,200 | 0.2% | 95.4% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST_LOAD_FAST | 7,917,780 | 0.2% | 95.5% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 7,845,640 | 0.2% | 95.7% |
| BINARY_OP_ADD_INT LOAD_FAST | 7,787,740 | 0.2% | 95.9% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 7,691,480 | 0.2% | 96.1% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 7,683,600 | 0.2% | 96.2% |
| RETURN_VALUE STORE_SUBSCR | 7,683,200 | 0.2% | 96.4% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 7,683,180 | 0.2% | 96.6% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST | 7,683,180 | 0.2% | 96.8% |
| RETURN_VALUE BINARY_OP_MULTIPLY_FLOAT | 7,683,160 | 0.2% | 96.9% |
| BINARY_OP_ADD_FLOAT BINARY_OP_MULTIPLY_FLOAT | 7,683,160 | 0.2% | 97.1% |


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
| LOAD_FAST | 52,955,960 | 41.0% |
| RETURN_VALUE | 38,416,000 | 29.8% |
| COPY | 26,830,760 | 20.8% |
| LOAD_FAST_LOAD_FAST | 10,664,860 | 8.3% |
| BINARY_OP_ADD_INT | 163,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 57,787,520 | 44.8% |
| RETURN_VALUE | 38,416,020 | 29.8% |
| BINARY_OP_MULTIPLY_FLOAT | 26,268,940 | 20.4% |
| BINARY_OP_SUBTRACT_FLOAT | 5,249,000 | 4.1% |
| LOAD_FAST | 725,380 | 0.6% |


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

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 79,635,100 | 45.3% |
| BINARY_OP_ADD_INT | 46,099,180 | 26.2% |
| BINARY_SUBSCR | 38,416,020 | 21.8% |
| BINARY_OP_MULTIPLY_FLOAT | 11,756,360 | 6.7% |
| LOAD_FAST | 8,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,619,760 | 45.3% |
| BINARY_SUBSCR | 38,416,000 | 21.8% |
| BINARY_OP_ADD_FLOAT | 23,049,480 | 13.1% |
| STORE_FAST | 10,871,780 | 6.2% |
| LOAD_FAST_LOAD_FAST | 8,490,760 | 4.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,830,760 | 47.6% |
| LOAD_FAST | 12,308,340 | 21.8% |
| BUILD_TUPLE | 8,483,200 | 15.0% |
| RETURN_VALUE | 7,683,200 | 13.6% |
| BINARY_SUBSCR_TUPLE_INT | 799,980 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 35,789,800 | 63.5% |
| LOAD_FAST | 11,016,300 | 19.5% |
| RETURN_CONST | 8,483,220 | 15.0% |
| JUMP_BACKWARD | 803,740 | 1.4% |
| LOAD_FAST_LOAD_FAST | 268,140 | 0.5% |


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
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 4,109,460 | 77.1% |
| LOAD_CONST | 1,136,360 | 21.3% |
| LOAD_FAST | 38,200 | 0.7% |
| BINARY_OP | 15,400 | 0.3% |
| LOAD_FAST_LOAD_FAST | 9,200 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,253,560 | 98.6% |
| LIST_APPEND | 16,000 | 0.3% |
| BINARY_OP | 15,400 | 0.3% |
| BINARY_OP_ADD_FLOAT | 8,280 | 0.2% |
| CALL_BUILTIN_O | 8,280 | 0.2% |


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
| LOAD_CONST | 5,257,640 | 100.0% |
| COMPARE_OP | 1,860 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| BINARY_OP | 80 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,257,620 | 100.0% |
| COMPARE_OP | 1,860 | 0.0% |
| COMPARE_OP_INT | 540 | 0.0% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |
| COMPARE_OP_FLOAT | 40 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 92,198,400 | 63.2% |
| COPY | 26,830,760 | 18.4% |
| LOAD_FAST | 26,664,000 | 18.3% |
| LOAD_FAST_LOAD_FAST | 85,540 | 0.1% |
| BINARY_OP_ADD_INT | 81,180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 92,198,320 | 63.2% |
| BINARY_SUBSCR | 26,830,760 | 18.4% |
| COPY | 26,830,760 | 18.4% |
| COMPARE_OP | 80 | 0.0% |


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
| STORE_SUBSCR | 35,789,800 | 50.3% |
| STORE_FAST | 12,251,900 | 17.2% |
| ENTER_EXECUTOR | 9,389,920 | 13.2% |
| FOR_ITER_RANGE | 8,673,680 | 12.2% |
| POP_JUMP_IF_TRUE | 2,073,880 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 34,724,420 | 48.8% |
| POP_JUMP_IF_FALSE | 15,558,800 | 21.9% |
| FOR_ITER_RANGE | 10,137,100 | 14.2% |
| ENTER_EXECUTOR | 9,389,920 | 13.2% |
| YIELD_VALUE | 799,280 | 1.1% |


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
| LOAD_FAST | 64,831,200 | 34.3% |
| RESUME_CHECK | 46,103,620 | 24.4% |
| JUMP_FORWARD | 46,099,200 | 24.4% |
| LOAD_FAST_LOAD_FAST | 15,714,140 | 8.3% |
| BINARY_OP_MULTIPLY_FLOAT | 7,691,480 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,304,360 | 53.0% |
| BINARY_OP_SUBTRACT_INT | 28,862,740 | 15.2% |
| COMPARE_OP_INT | 22,421,740 | 11.8% |
| BINARY_OP_ADD_INT | 21,101,340 | 11.1% |
| COMPARE_OP_FLOAT | 6,415,380 | 3.4% |


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
| POP_JUMP_IF_FALSE | 204,764,240 | 23.9% |
| LOAD_ATTR_INSTANCE_VALUE | 148,067,520 | 17.3% |
| LOAD_CONST | 100,304,360 | 11.7% |
| LOAD_GLOBAL_BUILTIN | 92,341,100 | 10.8% |
| RETURN_VALUE | 79,619,760 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 237,758,120 | 27.8% |
| SWAP | 92,198,400 | 10.8% |
| LOAD_GLOBAL_BUILTIN | 80,450,240 | 9.4% |
| BINARY_SUBSCR_LIST_INT | 79,635,080 | 9.3% |
| LOAD_CONST | 64,831,200 | 7.6% |


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

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 57,787,520 | 21.4% |
| JUMP_FORWARD | 48,094,880 | 17.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 46,099,160 | 17.0% |
| STORE_FAST | 39,001,980 | 14.4% |
| POP_JUMP_IF_FALSE | 24,079,740 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 65,613,220 | 24.3% |
| BINARY_SUBSCR_GETITEM | 52,592,480 | 19.5% |
| CALL_PY_EXACT_ARGS | 46,111,440 | 17.1% |
| LOAD_FAST | 25,360,740 | 9.4% |
| STORE_ATTR_INSTANCE_VALUE | 23,149,840 | 8.6% |


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
| COMPARE_OP_INT | 212,236,760 | 65.2% |
| TO_BOOL_BOOL | 92,206,580 | 28.3% |
| ENTER_EXECUTOR | 15,558,800 | 4.8% |
| COMPARE_OP | 5,257,620 | 1.6% |
| EXTENDED_ARG | 8,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 204,764,240 | 63.0% |
| JUMP_FORWARD | 92,198,400 | 28.3% |
| LOAD_FAST_LOAD_FAST | 24,079,740 | 7.4% |
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
| COMPARE_OP_FLOAT | 6,811,380 | 92.1% |
| ENTER_EXECUTOR | 579,300 | 7.8% |
| COMPARE_OP_INT | 7,980 | 0.1% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,316,160 | 71.9% |
| ENTER_EXECUTOR | 2,073,880 | 28.0% |
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
| BINARY_OP_SUBTRACT_INT | 22,242,280 | 34.3% |
| BINARY_OP_ADD_INT | 12,312,480 | 19.0% |
| RETURN_VALUE | 10,871,780 | 16.8% |
| BINARY_OP_SUBTRACT_FLOAT | 5,466,100 | 8.4% |
| BINARY_OP | 5,253,560 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 39,001,980 | 60.1% |
| ENTER_EXECUTOR | 12,251,900 | 18.9% |
| LOAD_FAST | 11,224,940 | 17.3% |
| JUMP_FORWARD | 1,995,680 | 3.1% |
| LOAD_CONST | 213,700 | 0.3% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 46,899,520 | 89.9% |
| LOAD_ATTR_INSTANCE_VALUE | 5,249,120 | 10.1% |
| LOAD_ATTR | 80 | 0.0% |
| UNPACK_SEQUENCE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,216,000 | 75.2% |
| LOAD_FAST_LOAD_FAST | 7,683,600 | 14.7% |
| STORE_FAST | 5,249,120 | 10.1% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,198,400 | 63.2% |
| SWAP | 26,830,760 | 18.4% |
| BINARY_OP_SUBTRACT_FLOAT | 26,267,980 | 18.0% |
| BINARY_OP_MULTIPLY_FLOAT | 400,280 | 0.3% |
| BINARY_OP_ADD_FLOAT | 162,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 92,198,400 | 63.2% |
| STORE_SUBSCR | 26,830,760 | 18.4% |
| SWAP | 26,830,760 | 18.4% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.0% |
| BUILD_LIST | 240 | 0.0% |


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
| RETURN_VALUE | 23,049,480 | 61.5% |
| BINARY_OP_MULTIPLY_FLOAT | 14,244,280 | 38.0% |
| LOAD_FAST | 162,280 | 0.4% |
| BINARY_OP | 8,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,125,800 | 61.7% |
| BINARY_OP_MULTIPLY_FLOAT | 7,683,160 | 20.5% |
| LOAD_CONST | 6,415,400 | 17.1% |
| SWAP | 162,360 | 0.4% |
| STORE_FAST | 73,560 | 0.2% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,393,460 | 62.3% |
| LOAD_CONST | 21,101,340 | 28.3% |
| LOAD_FAST_LOAD_FAST | 6,945,000 | 9.3% |
| BINARY_OP | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 46,099,180 | 61.9% |
| STORE_FAST | 12,312,480 | 16.5% |
| LOAD_FAST | 7,787,740 | 10.5% |
| BUILD_TUPLE | 7,683,180 | 10.3% |
| BINARY_SUBSCR | 163,640 | 0.2% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 26,268,940 | 39.1% |
| LOAD_FAST_LOAD_FAST | 12,975,200 | 19.3% |
| CALL_BUILTIN_CLASS | 11,764,520 | 17.5% |
| RETURN_VALUE | 7,683,160 | 11.4% |
| BINARY_OP_ADD_FLOAT | 7,683,160 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 26,557,160 | 39.5% |
| BINARY_OP_ADD_FLOAT | 14,244,280 | 21.2% |
| RETURN_VALUE | 11,756,360 | 17.5% |
| LOAD_CONST | 7,691,480 | 11.4% |
| LOAD_FAST_LOAD_FAST | 6,416,400 | 9.5% |


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
| BINARY_OP_MULTIPLY_FLOAT | 26,557,160 | 67.0% |
| LOAD_FAST | 7,845,640 | 19.8% |
| BINARY_SUBSCR | 5,249,000 | 13.2% |
| BINARY_OP | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,267,980 | 66.2% |
| LOAD_FAST_LOAD_FAST | 7,917,780 | 20.0% |
| STORE_FAST | 5,466,100 | 13.8% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,862,740 | 96.4% |
| LOAD_FAST_LOAD_FAST | 1,080,440 | 3.6% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,242,280 | 74.3% |
| LOAD_FAST | 7,683,180 | 25.7% |
| COMPARE_OP_INT | 15,920 | 0.1% |
| BUILD_TUPLE | 1,000 | 0.0% |
| CALL_BUILTIN_CLASS | 1,000 | 0.0% |


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
| LOAD_FAST | 11,969,580 | 99.3% |
| BINARY_OP_MULTIPLY_INT | 80,500 | 0.7% |
| BINARY_OP_SUBTRACT_INT | 1,000 | 0.0% |
| CALL | 740 | 0.0% |
| BINARY_SUBSCR | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 11,764,520 | 97.6% |
| GET_ITER | 284,060 | 2.4% |
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

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,111,440 | 89.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,249,000 | 10.2% |
| LOAD_FAST | 4,760 | 0.0% |
| LOAD_CONST | 4,320 | 0.0% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 51,370,000 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,415,380 | 94.2% |
| LOAD_FAST_LOAD_FAST | 395,960 | 5.8% |
| COMPARE_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,811,380 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 92,198,320 | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE | 92,198,320 | 43.4% |
| LOAD_CONST | 22,421,740 | 10.6% |
| LOAD_FAST_LOAD_FAST | 5,409,920 | 2.5% |
| BINARY_OP_SUBTRACT_INT | 15,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 212,236,760 | 100.0% |
| POP_JUMP_IF_TRUE | 7,980 | 0.0% |
| EXTENDED_ARG | 7,980 | 0.0% |


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
| LOAD_FAST | 237,758,120 | 78.4% |
| LOAD_FAST_LOAD_FAST | 65,613,220 | 21.6% |
| LOAD_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 148,067,520 | 48.8% |
| COMPARE_OP_INT | 92,198,320 | 30.4% |
| BINARY_OP_MULTIPLY_INT | 46,099,160 | 15.2% |
| TO_BOOL_BOOL | 11,756,240 | 3.9% |
| STORE_FAST_STORE_FAST | 5,249,120 | 1.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,347,960 | 100.0% |
| STORE_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR | 260 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,099,160 | 89.8% |
| CALL_PY_EXACT_ARGS | 5,249,000 | 10.2% |
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
| LOAD_FAST | 11,760,440 | 74.1% |
| LOAD_FAST_LOAD_FAST | 4,110,000 | 25.9% |
| ENTER_EXECUTOR | 2,880 | 0.0% |
| LOAD_ATTR | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 11,756,240 | 74.1% |
| BINARY_OP | 4,109,460 | 25.9% |
| LOAD_CONST | 4,020 | 0.0% |
| LOAD_FAST | 4,020 | 0.0% |
| CALL | 180 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80,450,480 | 46.5% |
| LOAD_FAST | 80,450,240 | 46.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,756,240 | 6.8% |
| STORE_FAST | 128,380 | 0.1% |
| FOR_ITER_RANGE | 80,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,341,100 | 53.4% |
| CALL_ISINSTANCE | 80,450,240 | 46.5% |
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
| BINARY_SUBSCR_GETITEM | 118,050,820 | 66.1% |
| CALL_PY_EXACT_ARGS | 51,370,000 | 28.7% |
| CACHE | 8,498,820 | 4.8% |
| FOR_ITER_GEN | 799,980 | 0.4% |
| CALL_FUNCTION_EX | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 80,450,480 | 45.0% |
| LOAD_FAST | 51,364,920 | 28.7% |
| LOAD_CONST | 46,103,620 | 25.8% |
| POP_TOP | 799,980 | 0.4% |
| LOAD_GLOBAL_MODULE | 560 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,149,840 | 100.0% |
| LOAD_FAST | 1,000 | 0.0% |
| STORE_ATTR | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,149,720 | 100.0% |
| LOAD_CONST | 720 | 0.0% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% |
| LOAD_FAST_LOAD_FAST | 200 | 0.0% |


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

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 80,450,240 | 87.2% |
| LOAD_ATTR_INSTANCE_VALUE | 11,756,240 | 12.7% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 92,206,580 | 100.0% |


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
|     deferred | 5,321,140 | 1.8% |
|          hit | 295,241,340 | 98.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,460 | 27.0% |
| Failure | 6,660 | 73.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 1,720 | 25.8% |
| multiply different types | 1,400 | 21.0% |
| true divide other | 840 | 12.6% |
| remainder | 780 | 11.7% |
| rshift | 600 | 9.0% |
| lshift | 420 | 6.3% |
| true divide float | 420 | 6.3% |
| floor divide | 340 | 5.1% |
| true divide different types | 140 | 2.1% |


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
|     deferred | 129,032,320 | 39.2% |
|          hit | 200,085,860 | 60.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 1.0% |
| Failure | 36,660 | 99.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 36,660 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,280 | 0.0% |
|          hit | 144,294,260 | 100.0% |

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
|     deferred | 5,257,700 | 2.3% |
|          hit | 219,064,100 | 97.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 580 | 23.8% |
| Failure | 1,860 | 76.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 1,860 | 100.0% |


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
|          hit | 370,608,180 | 100.0% |
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
|          hit | 173,011,680 | 100.0% |

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
|          hit | 23,151,560 | 100.0% |

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
|     deferred | 56,361,280 | 99.9% |
|          hit | 15,180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.1% |
| Failure | 18,240 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 15,520 | 85.1% |
| py simple | 2,720 | 14.9% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 92,206,580 | 100.0% |

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
| Basic | 2,124,448,960 | 48.2% |
| Not specialized | 528,740,720 | 12.0% |
| Specialized hits | 1,754,529,980 | 39.8% |
| Specialized misses | 12,240 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 129,032,320 | 65.8% |
| STORE_SUBSCR | 56,361,280 | 28.8% |
| BINARY_OP | 5,321,140 | 2.7% |
| COMPARE_OP | 5,257,700 | 2.7% |
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
| END_FOR | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_GENERATOR | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,499,020 | 4.8% |
| Calls to Python functions inlined | 170,222,420 | 95.2% |
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
| Frames pushed | 181,146,760 | 101.4% |


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
| Allocations to 4 kbytes | 16,440 | 0.0% |
| Allocations over 4 kbytes | 600 | 0.0% |
| Frees | 606,286,573 |  |
| New values | 300 |  |
| Interpreter increfs | 3,613,056,500 | 83.3% |
| Interpreter decrefs | 5,054,766,800 | 87.7% |
| Increfs | 722,599,781 | 16.7% |
| Decrefs | 705,861,042 | 12.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 16,110 |  |
| Method cache misses | 1,130 |  |
| Method cache collisions | 903 |  |
| Method cache dunder hits | 88,188,840 |  |
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
| Trace too long | 0 | 0.0% |
| Trace too short | 520 | 44.1% |
| Inner loop found | 120 | 10.2% |
| Recursive call | 0 | 0.0% |
| Traces executed | 71,207,300 |  |
| Uops executed | 9,975,824,680 | 140.10 |

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
| <= 256 | 80 | 12.1% |
| <= 512 | 100 | 15.2% |


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
| <= 128 | 180 | 27.3% |
| <= 256 | 80 | 12.1% |
| <= 512 | 40 | 6.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 4,684,940 | 6.6% |
| <= 8 | 0 | 0.0% |
| <= 16 | 27,461,680 | 38.6% |
| <= 32 | 12,722,620 | 17.9% |
| <= 64 | 5,733,840 | 8.1% |
| <= 128 | 2,641,920 | 3.7% |
| <= 256 | 13,173,040 | 18.5% |
| <= 512 | 2,199,820 | 3.1% |
| <= 1,024 | 718,520 | 1.0% |
| <= 2,048 | 1,370,920 | 1.9% |
| <= 4,096 | 256,000 | 0.4% |
| <= 8,192 | 128,000 | 0.2% |
| <= 16,384 | 64,000 | 0.1% |
| <= 32,768 | 32,020 | 0.0% |
| <= 65,536 | 19,980 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,258,618,120 | 22.6% | 22.6% |  |
| _SET_IP | 1,440,497,860 | 14.4% | 37.1% |  |
| _CHECK_VALIDITY | 965,746,600 | 9.7% | 46.8% |  |
| STORE_FAST | 621,769,060 | 6.2% | 53.0% |  |
| _GUARD_BOTH_FLOAT | 589,820,040 | 5.9% | 58.9% |  |
| _BINARY_SUBSCR | 487,395,660 | 4.9% | 63.8% |  |
| _GUARD_BOTH_INT | 413,173,760 | 4.1% | 67.9% |  |
| LOAD_CONST | 364,783,760 | 3.7% | 71.6% |  |
| _BINARY_OP_ADD_INT | 293,749,480 | 2.9% | 74.5% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 251,472,840 | 2.5% | 77.1% |  |
| _STORE_SUBSCR | 197,524,340 | 2.0% | 79.0% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 188,874,940 | 1.9% | 80.9% | 5.4% |
| _ITER_CHECK_RANGE | 188,874,940 | 1.9% | 82.8% |  |
| _BINARY_OP_ADD_FLOAT | 188,076,280 | 1.9% | 84.7% |  |
| COPY | 179,890,480 | 1.8% | 86.5% |  |
| SWAP | 179,890,480 | 1.8% | 88.3% |  |
| _ITER_NEXT_RANGE | 178,737,840 | 1.8% | 90.1% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 150,270,920 | 1.5% | 91.6% |  |
| _JUMP_TO_TOP | 111,973,660 | 1.1% | 92.7% |  |
| _BINARY_OP_MULTIPLY_INT | 93,862,420 | 0.9% | 93.7% |  |
| _GUARD_TYPE_VERSION | 78,469,180 | 0.8% | 94.5% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 46,385,300 | 0.5% | 94.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 46,385,300 | 0.5% | 95.4% |  |
| _EXIT_TRACE | 44,929,140 | 0.5% | 95.8% |  |
| _BINARY_OP | 36,229,560 | 0.4% | 96.2% |  |
| COMPARE_OP_INT | 30,847,460 | 0.3% | 96.5% |  |
| _GUARD_IS_TRUE_POP | 26,570,320 | 0.3% | 96.8% | 45.8% |
| _BINARY_OP_SUBTRACT_INT | 25,561,860 | 0.3% | 97.0% |  |
| _GUARD_IS_FALSE_POP | 22,783,920 | 0.2% | 97.3% | 17.5% |
| _GUARD_KEYS_VERSION | 21,305,840 | 0.2% | 97.5% | 0.0% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 21,305,840 | 0.2% | 97.7% |  |
| _GUARD_GLOBALS_VERSION | 15,776,260 | 0.2% | 97.9% |  |
| _GUARD_BUILTINS_VERSION | 15,534,900 | 0.2% | 98.0% |  |
| _LOAD_GLOBAL_BUILTINS | 15,534,900 | 0.2% | 98.2% |  |
| CALL_BUILTIN_CLASS | 15,139,860 | 0.2% | 98.3% |  |
| RESUME_CHECK | 11,725,520 | 0.1% | 98.4% |  |
| _CHECK_PEP_523 | 11,725,520 | 0.1% | 98.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 11,725,520 | 0.1% | 98.7% |  |
| _CHECK_STACK_SPACE | 11,725,520 | 0.1% | 98.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 11,725,520 | 0.1% | 98.9% |  |
| _PUSH_FRAME | 11,725,520 | 0.1% | 99.0% |  |
| _SAVE_RETURN_OFFSET | 11,725,520 | 0.1% | 99.1% |  |
| _COMPARE_OP | 11,714,720 | 0.1% | 99.3% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 11,714,720 | 0.1% | 99.4% |  |
| _GUARD_DORV_VALUES | 10,778,040 | 0.1% | 99.5% |  |
| _STORE_ATTR_INSTANCE_VALUE | 10,778,040 | 0.1% | 99.6% |  |
| GET_ITER | 9,860,700 | 0.1% | 99.7% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 9,588,240 | 0.1% | 99.8% |  |
| BUILD_TUPLE | 8,481,460 | 0.1% | 99.9% |  |
| TO_BOOL_BOOL | 5,207,480 | 0.1% | 99.9% |  |
| _POP_FRAME | 5,207,480 | 0.1% | 100.0% |  |
| COMPARE_OP_FLOAT | 1,584,580 | 0.0% | 100.0% |  |
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
Stats gathered on: 2023-11-19
