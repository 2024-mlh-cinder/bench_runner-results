
# Pystats results

- benchmark: scimark
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,083,414,320 | 18.5% | 18.5% |  |
| LOAD_FAST_LOAD_FAST | 433,810,380 | 7.4% | 26.0% |  |
| POP_JUMP_IF_FALSE | 328,114,940 | 5.6% | 31.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 321,103,120 | 5.5% | 37.1% |  |
| SWAP | 293,175,920 | 5.0% | 42.1% |  |
| LOAD_CONST | 292,953,980 | 5.0% | 47.1% |  |
| COPY | 276,960,200 | 4.7% | 51.8% |  |
| BINARY_SUBSCR | 234,162,560 | 4.0% | 55.8% |  |
| COMPARE_OP_INT | 221,899,180 | 3.8% | 59.6% |  |
| RESUME_CHECK | 182,272,400 | 3.1% | 62.8% |  |
| RETURN_VALUE | 181,123,540 | 3.1% | 65.9% |  |
| LOAD_GLOBAL_BUILTIN | 178,170,180 | 3.0% | 68.9% |  |
| STORE_SUBSCR | 172,808,220 | 3.0% | 71.9% |  |
| BINARY_OP_ADD_INT | 158,521,860 | 2.7% | 74.6% |  |
| STORE_FAST | 125,788,060 | 2.2% | 76.7% |  |
| BINARY_OP_ADD_FLOAT | 120,734,300 | 2.1% | 78.8% |  |
| BINARY_SUBSCR_GETITEM | 118,050,820 | 2.0% | 80.8% |  |
| BINARY_OP_MULTIPLY_FLOAT | 107,739,420 | 1.8% | 82.7% |  |
| ENTER_EXECUTOR | 106,307,180 | 1.8% | 84.5% |  |
| TO_BOOL_BOOL | 97,414,060 | 1.7% | 86.1% |  |
| JUMP_FORWARD | 94,194,080 | 1.6% | 87.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 92,114,220 | 1.6% | 89.3% |  |
| CALL_ISINSTANCE | 80,450,280 | 1.4% | 90.7% |  |
| BINARY_SUBSCR_LIST_INT | 80,435,080 | 1.4% | 92.1% |  |
| STORE_FAST_STORE_FAST | 55,708,340 | 1.0% | 93.0% |  |
| CALL_PY_EXACT_ARGS | 54,921,940 | 0.9% | 94.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 54,900,560 | 0.9% | 94.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,907,120 | 0.8% | 95.7% |  |
| BINARY_OP_MULTIPLY_INT | 46,576,140 | 0.8% | 96.5% |  |
| BUILD_TUPLE | 39,217,640 | 0.7% | 97.2% |  |
| BINARY_OP_SUBTRACT_INT | 36,888,680 | 0.6% | 97.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 30,096,920 | 0.5% | 98.3% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 22,232,420 | 0.4% | 98.7% | 0.1% |
| CALL_BUILTIN_CLASS | 17,260,280 | 0.3% | 99.0% |  |
| BINARY_OP | 9,489,640 | 0.2% | 99.2% |  |
| COMPARE_OP | 8,812,940 | 0.2% | 99.3% |  |
| RETURN_CONST | 8,523,520 | 0.1% | 99.5% |  |
| INTERPRETER_EXIT | 8,499,020 | 0.1% | 99.6% |  |
| POP_JUMP_IF_TRUE | 8,404,000 | 0.1% | 99.7% |  |
| COMPARE_OP_FLOAT | 8,395,960 | 0.1% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,599,960 | 0.0% | 99.9% |  |
| POP_TOP | 825,120 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 818,640 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 800,060 | 0.0% | 100.0% |  |
| YIELD_VALUE | 800,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 420,700 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 293,280 | 0.0% | 100.0% |  |
| GET_ITER | 284,960 | 0.0% | 100.0% |  |
| LIST_APPEND | 179,840 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 80,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 48,580 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 25,740 | 0.0% | 100.0% |  |
| CALL | 22,620 | 0.0% | 100.0% |  |
| PUSH_NULL | 18,680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 15,180 | 0.0% | 100.0% |  |
| FOR_ITER | 9,500 | 0.0% | 100.0% |  |
| STORE_SLICE | 8,080 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 3,960 | 0.0% | 100.0% |  |
| LOAD_ATTR | 3,920 | 0.0% | 100.0% |  |
| BUILD_LIST | 1,900 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,440 | 0.0% | 100.0% |  |
| LOAD_DEREF | 1,200 | 0.0% | 100.0% |  |
| RESUME | 840 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 800 | 0.0% | 100.0% |  |
| NOP | 400 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 400 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 400 | 0.0% | 100.0% |  |
| LIST_EXTEND | 400 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 380 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 253,621,280 | 4.3% | 4.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 221,883,220 | 3.8% | 8.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 216,159,980 | 3.7% | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 157,039,280 | 2.7% | 14.5% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 118,050,820 | 2.0% | 16.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 103,863,360 | 1.8% | 18.3% |
| SWAP STORE_SUBSCR | 100,484,600 | 1.7% | 20.0% |
| SWAP SWAP | 100,484,600 | 1.7% | 21.8% |
| LOAD_CONST LOAD_FAST | 100,304,060 | 1.7% | 23.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 97,548,500 | 1.7% | 25.1% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 97,478,540 | 1.7% | 26.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 97,414,060 | 1.7% | 28.5% |
| COPY BINARY_SUBSCR | 92,380,900 | 1.6% | 30.1% |
| COPY COPY | 92,380,900 | 1.6% | 31.6% |
| LOAD_FAST SWAP | 92,198,400 | 1.6% | 33.2% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 92,198,400 | 1.6% | 34.8% |
| SWAP COPY | 92,198,400 | 1.6% | 36.4% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 92,198,320 | 1.6% | 37.9% |
| COPY COMPARE_OP_INT | 92,198,320 | 1.6% | 39.5% |
| BINARY_SUBSCR LOAD_FAST | 82,482,280 | 1.4% | 40.9% |
| LOAD_FAST LOAD_CONST | 82,197,900 | 1.4% | 42.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 80,450,480 | 1.4% | 43.7% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 80,450,240 | 1.4% | 45.1% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 80,450,240 | 1.4% | 46.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 80,450,240 | 1.4% | 47.8% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 79,635,100 | 1.4% | 49.2% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 79,635,080 | 1.4% | 50.6% |
| RETURN_VALUE LOAD_FAST | 79,619,760 | 1.4% | 51.9% |
| STORE_SUBSCR ENTER_EXECUTOR | 76,668,680 | 1.3% | 53.2% |
| STORE_SUBSCR LOAD_FAST_LOAD_FAST | 73,921,600 | 1.3% | 54.5% |
| BINARY_OP_ADD_FLOAT SWAP | 73,816,220 | 1.3% | 55.8% |
| LOAD_FAST BINARY_OP_ADD_FLOAT | 73,816,140 | 1.3% | 57.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 71,520,600 | 1.2% | 58.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 67,481,160 | 1.2% | 59.4% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 61,339,360 | 1.0% | 60.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 54,921,880 | 0.9% | 61.4% |
| RESUME_CHECK LOAD_FAST | 54,916,840 | 0.9% | 62.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 54,899,920 | 0.9% | 63.3% |
| LOAD_FAST BINARY_SUBSCR | 52,955,960 | 0.9% | 64.2% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 52,592,360 | 0.9% | 65.1% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST_LOAD_FAST | 48,796,220 | 0.8% | 65.9% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 48,724,100 | 0.8% | 66.8% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 48,094,880 | 0.8% | 67.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 46,907,120 | 0.8% | 68.4% |
| LOAD_FAST BINARY_OP_ADD_INT | 46,393,300 | 0.8% | 69.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 46,111,420 | 0.8% | 70.0% |
| RESUME_CHECK LOAD_CONST | 46,103,600 | 0.8% | 70.8% |
| JUMP_FORWARD LOAD_CONST | 46,099,200 | 0.8% | 71.5% |
| BINARY_OP_ADD_INT RETURN_VALUE | 46,099,180 | 0.8% | 72.3% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 46,099,180 | 0.8% | 73.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 46,099,160 | 0.8% | 73.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 46,099,160 | 0.8% | 74.7% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 46,099,120 | 0.8% | 75.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 39,216,000 | 0.7% | 76.2% |
| BINARY_SUBSCR RETURN_VALUE | 38,416,020 | 0.7% | 76.8% |
| RETURN_VALUE BINARY_SUBSCR | 38,416,000 | 0.7% | 77.5% |
| STORE_FAST LOAD_FAST | 37,399,860 | 0.6% | 78.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 35,058,880 | 0.6% | 78.7% |
| ENTER_EXECUTOR BINARY_SUBSCR_GETITEM | 34,724,600 | 0.6% | 79.3% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 34,588,820 | 0.6% | 79.9% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 33,975,340 | 0.6% | 80.5% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 32,978,180 | 0.6% | 81.0% |
| BINARY_OP_ADD_INT STORE_SUBSCR | 32,933,840 | 0.6% | 81.6% |
| LOAD_FAST_LOAD_FAST COPY | 32,860,600 | 0.6% | 82.2% |
| BINARY_OP_ADD_INT COPY | 32,856,260 | 0.6% | 82.7% |
| ENTER_EXECUTOR LOAD_FAST | 32,855,320 | 0.6% | 83.3% |
| LOAD_FAST LOAD_FAST | 32,562,280 | 0.6% | 83.8% |
| LOAD_FAST BUILD_TUPLE | 31,532,800 | 0.5% | 84.4% |
| BUILD_TUPLE BINARY_SUBSCR_GETITEM | 30,733,560 | 0.5% | 84.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 30,095,200 | 0.5% | 85.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 30,095,080 | 0.5% | 85.9% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 29,187,620 | 0.5% | 86.4% |
| LOAD_CONST COMPARE_OP_INT | 28,984,780 | 0.5% | 86.9% |
| LOAD_FAST COPY | 26,664,000 | 0.5% | 87.4% |
| BINARY_SUBSCR BINARY_OP_MULTIPLY_FLOAT | 26,268,900 | 0.4% | 87.8% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 26,267,980 | 0.4% | 88.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 25,360,560 | 0.4% | 88.7% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 23,860,520 | 0.4% | 89.1% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 23,125,720 | 0.4% | 89.5% |
| RETURN_VALUE BINARY_OP_ADD_FLOAT | 23,049,480 | 0.4% | 89.9% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 20,689,780 | 0.4% | 90.3% |
| LOAD_FAST CALL_BUILTIN_CLASS | 17,177,000 | 0.3% | 90.6% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 17,049,720 | 0.3% | 90.9% |
| CALL_BUILTIN_CLASS BINARY_OP_MULTIPLY_FLOAT | 16,971,980 | 0.3% | 91.2% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 16,967,860 | 0.3% | 91.4% |
| BINARY_OP_MULTIPLY_FLOAT RETURN_VALUE | 16,963,840 | 0.3% | 91.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 16,963,720 | 0.3% | 92.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_GLOBAL_BUILTIN | 16,963,720 | 0.3% | 92.3% |
| BINARY_OP_ADD_INT BINARY_SUBSCR | 16,370,340 | 0.3% | 92.6% |
| BINARY_SUBSCR STORE_FAST | 16,370,180 | 0.3% | 92.9% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 16,216,840 | 0.3% | 93.2% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 16,144,320 | 0.3% | 93.4% |
| RETURN_VALUE STORE_FAST | 16,008,360 | 0.3% | 93.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 15,905,100 | 0.3% | 94.0% |
| BINARY_OP_ADD_INT STORE_FAST | 14,565,640 | 0.2% | 94.2% |
| STORE_FAST ENTER_EXECUTOR | 14,505,140 | 0.2% | 94.5% |
| LOAD_FAST STORE_SUBSCR | 14,176,200 | 0.2% | 94.7% |
| STORE_SUBSCR LOAD_FAST | 12,884,220 | 0.2% | 94.9% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 9,960,400 | 0.2% | 95.1% |
| BINARY_OP STORE_FAST | 9,412,340 | 0.2% | 95.3% |


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
| LOAD_CONST | 8,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 8,000 | 99.0% |
| LOAD_FAST | 80 | 1.0% |


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
| COPY | 92,380,900 | 39.5% |
| LOAD_FAST | 52,955,960 | 22.6% |
| RETURN_VALUE | 38,416,000 | 16.4% |
| LOAD_FAST_LOAD_FAST | 33,975,340 | 14.5% |
| BINARY_OP_ADD_INT | 16,370,340 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 82,482,280 | 35.2% |
| LOAD_FAST_LOAD_FAST | 61,339,360 | 26.2% |
| RETURN_VALUE | 38,416,020 | 16.4% |
| BINARY_OP_MULTIPLY_FLOAT | 26,268,900 | 11.2% |
| STORE_FAST | 16,370,180 | 7.0% |


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
| CALL_BUILTIN_CLASS | 283,880 | 99.6% |
| CALL | 600 | 0.2% |
| LOAD_FAST | 400 | 0.1% |
| RETURN_GENERATOR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 283,960 | 99.6% |
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
| ENTER_EXECUTOR | 803,360 | 97.4% |
| LOAD_CONST | 12,240 | 1.5% |
| RETURN_CONST | 4,080 | 0.5% |
| LOAD_GLOBAL_MODULE | 4,000 | 0.5% |
| JUMP_BACKWARD | 880 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 17,460 | 93.5% |
| LOAD_DEREF | 800 | 4.3% |
| LOAD_ATTR | 340 | 1.8% |
| LOAD_FAST | 80 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,400 | 93.1% |
| CALL | 1,200 | 6.4% |
| LOAD_FAST_LOAD_FAST | 80 | 0.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 79,635,100 | 44.0% |
| BINARY_OP_ADD_INT | 46,099,180 | 25.5% |
| BINARY_SUBSCR | 38,416,020 | 21.2% |
| BINARY_OP_MULTIPLY_FLOAT | 16,963,840 | 9.4% |
| LOAD_FAST | 8,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,619,760 | 44.0% |
| BINARY_SUBSCR | 38,416,000 | 21.2% |
| BINARY_OP_ADD_FLOAT | 23,049,480 | 12.7% |
| STORE_FAST | 16,008,360 | 8.8% |
| LOAD_FAST_LOAD_FAST | 8,490,760 | 4.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 100,484,600 | 58.1% |
| BINARY_OP_ADD_INT | 32,933,840 | 19.1% |
| LOAD_FAST | 14,176,200 | 8.2% |
| BUILD_TUPLE | 8,483,200 | 4.9% |
| LOAD_FAST_LOAD_FAST | 8,200,100 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 76,668,680 | 44.4% |
| LOAD_FAST_LOAD_FAST | 73,921,600 | 42.8% |
| LOAD_FAST | 12,884,220 | 7.5% |
| RETURN_CONST | 8,483,220 | 4.9% |
| JUMP_BACKWARD | 803,520 | 0.5% |


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
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 5,260,540 | 55.4% |
| LOAD_CONST | 4,144,020 | 43.7% |
| LOAD_FAST | 38,120 | 0.4% |
| BINARY_OP | 16,280 | 0.2% |
| LOAD_FAST_LOAD_FAST | 9,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,412,340 | 99.2% |
| BINARY_OP | 16,280 | 0.2% |
| LIST_APPEND | 16,000 | 0.2% |
| CALL_BUILTIN_O | 8,260 | 0.1% |
| LOAD_GLOBAL_MODULE | 8,260 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,260 | 66.3% |
| LOAD_FAST | 400 | 21.1% |
| SWAP | 240 | 12.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,260 | 66.3% |
| LOAD_DEREF | 400 | 21.1% |
| SWAP | 240 | 12.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,540 | 68.7% |
| LOAD_FAST | 1,680 | 7.4% |
| BUILD_LIST | 1,260 | 5.6% |
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
| LOAD_CONST | 8,809,580 | 100.0% |
| COMPARE_OP | 2,720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| BINARY_OP | 80 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,809,560 | 100.0% |
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
| STORE_SUBSCR | 76,668,680 | 72.1% |
| STORE_FAST | 14,505,140 | 13.6% |
| ENTER_EXECUTOR | 9,960,400 | 9.4% |
| POP_JUMP_IF_TRUE | 2,073,920 | 2.0% |
| POP_JUMP_IF_FALSE | 2,044,160 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 34,724,600 | 32.7% |
| LOAD_FAST | 32,855,320 | 30.9% |
| LOAD_FAST_LOAD_FAST | 20,689,780 | 19.5% |
| ENTER_EXECUTOR | 9,960,400 | 9.4% |
| LOAD_CONST | 3,255,440 | 3.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 8,620 | 90.7% |
| GET_ITER | 700 | 7.4% |
| FOR_ITER | 140 | 1.5% |
| SWAP | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,960 | 83.8% |
| FOR_ITER_RANGE | 620 | 6.5% |
| STORE_FAST | 580 | 6.1% |
| FOR_ITER | 140 | 1.5% |
| RETURN_CONST | 80 | 0.8% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 803,520 | 98.2% |
| STORE_SLICE | 8,000 | 1.0% |
| ENTER_EXECUTOR | 2,640 | 0.3% |
| STORE_FAST | 1,280 | 0.2% |
| POP_TOP | 880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 799,980 | 97.7% |
| FOR_ITER | 8,620 | 1.1% |
| FOR_ITER_RANGE | 8,500 | 1.0% |
| ENTER_EXECUTOR | 640 | 0.1% |
| LOAD_CONST | 300 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 97,478,540 | 33.3% |
| LOAD_FAST | 82,197,900 | 28.1% |
| RESUME_CHECK | 46,103,600 | 15.7% |
| JUMP_FORWARD | 46,099,200 | 15.7% |
| BINARY_OP_ADD_FLOAT | 7,999,980 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 103,863,360 | 35.5% |
| LOAD_FAST | 100,304,060 | 34.2% |
| BINARY_OP_SUBTRACT_INT | 35,058,880 | 12.0% |
| COMPARE_OP_INT | 28,984,780 | 9.9% |
| COMPARE_OP | 8,809,580 | 3.0% |


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
| POP_JUMP_IF_FALSE | 216,159,980 | 20.0% |
| LOAD_ATTR_INSTANCE_VALUE | 157,039,280 | 14.5% |
| LOAD_CONST | 100,304,060 | 9.3% |
| LOAD_GLOBAL_BUILTIN | 97,548,500 | 9.0% |
| BINARY_SUBSCR | 82,482,280 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 253,621,280 | 23.4% |
| SWAP | 92,198,400 | 8.5% |
| LOAD_CONST | 82,197,900 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 80,450,240 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 79,635,080 | 7.4% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 73,921,600 | 17.0% |
| STORE_FAST | 71,520,600 | 16.5% |
| BINARY_SUBSCR | 61,339,360 | 14.1% |
| BINARY_OP_SUBTRACT_FLOAT | 48,796,220 | 11.2% |
| JUMP_FORWARD | 48,094,880 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 97,478,540 | 22.5% |
| LOAD_ATTR_INSTANCE_VALUE | 67,481,160 | 15.6% |
| BINARY_SUBSCR_GETITEM | 52,592,360 | 12.1% |
| CALL_PY_EXACT_ARGS | 46,111,420 | 10.6% |
| BINARY_SUBSCR | 33,975,340 | 7.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,880 | 47.5% |
| RESUME | 280 | 7.1% |
| RESUME_CHECK | 280 | 7.1% |
| RETURN_VALUE | 200 | 5.1% |
| ENTER_EXECUTOR | 160 | 4.0% |

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
| COMPARE_OP_INT | 221,883,220 | 67.6% |
| TO_BOOL_BOOL | 97,414,060 | 29.7% |
| COMPARE_OP | 8,809,560 | 2.7% |
| EXTENDED_ARG | 8,000 | 0.0% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 216,159,980 | 65.9% |
| JUMP_FORWARD | 92,198,400 | 28.1% |
| LOAD_FAST_LOAD_FAST | 15,905,100 | 4.8% |
| ENTER_EXECUTOR | 2,044,160 | 0.6% |
| LOAD_CONST | 1,714,280 | 0.5% |


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
| ENTER_EXECUTOR | 2,073,920 | 24.7% |
| LOAD_GLOBAL_BUILTIN | 7,880 | 0.1% |
| JUMP_BACKWARD | 720 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 8,483,220 | 99.5% |
| STORE_SUBSCR_LIST_INT | 15,180 | 0.2% |
| ENTER_EXECUTOR | 12,140 | 0.1% |
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
| BINARY_OP_SUBTRACT_INT | 29,187,620 | 23.2% |
| BINARY_OP_SUBTRACT_FLOAT | 17,049,720 | 13.6% |
| BINARY_SUBSCR | 16,370,180 | 13.0% |
| RETURN_VALUE | 16,008,360 | 12.7% |
| BINARY_OP_ADD_INT | 14,565,640 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,520,600 | 56.9% |
| LOAD_FAST | 37,399,860 | 29.7% |
| ENTER_EXECUTOR | 14,505,140 | 11.5% |
| JUMP_FORWARD | 1,995,680 | 1.6% |
| LOAD_CONST | 213,400 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 46,907,120 | 84.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,801,060 | 15.8% |
| LOAD_ATTR | 80 | 0.0% |
| UNPACK_SEQUENCE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,216,000 | 70.4% |
| STORE_FAST | 8,801,060 | 15.8% |
| LOAD_FAST_LOAD_FAST | 7,691,200 | 13.8% |
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
| LOAD_FAST | 73,816,140 | 61.1% |
| BINARY_OP_MULTIPLY_FLOAT | 23,860,520 | 19.8% |
| RETURN_VALUE | 23,049,480 | 19.1% |
| BINARY_OP | 8,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 73,816,220 | 61.1% |
| LOAD_FAST_LOAD_FAST | 23,125,720 | 19.2% |
| STORE_FAST | 8,105,240 | 6.7% |
| LOAD_CONST | 7,999,980 | 6.6% |
| BINARY_OP_MULTIPLY_FLOAT | 7,683,160 | 6.4% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 103,863,360 | 65.5% |
| LOAD_FAST | 46,393,300 | 29.3% |
| LOAD_FAST_LOAD_FAST | 8,264,560 | 5.2% |
| BINARY_OP | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 46,099,180 | 29.1% |
| STORE_SUBSCR | 32,933,840 | 20.8% |
| COPY | 32,856,260 | 20.7% |
| BINARY_SUBSCR | 16,370,340 | 10.3% |
| STORE_FAST | 14,565,640 | 9.2% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,978,180 | 30.6% |
| BINARY_SUBSCR | 26,268,900 | 24.4% |
| CALL_BUILTIN_CLASS | 16,971,980 | 15.8% |
| LOAD_FAST_LOAD_FAST | 16,144,320 | 15.0% |
| RETURN_VALUE | 7,683,160 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 34,588,820 | 32.1% |
| BINARY_OP_ADD_FLOAT | 23,860,520 | 22.1% |
| RETURN_VALUE | 16,963,840 | 15.7% |
| LOAD_FAST | 16,216,840 | 15.1% |
| LOAD_FAST_LOAD_FAST | 8,000,920 | 7.4% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 46,099,160 | 99.0% |
| BINARY_OP_ADD_INT | 225,260 | 0.5% |
| LOAD_FAST | 89,060 | 0.2% |
| LOAD_CONST | 84,600 | 0.2% |
| LOAD_FAST_LOAD_FAST | 77,740 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,099,180 | 99.0% |
| STORE_FAST | 319,740 | 0.7% |
| CALL_BUILTIN_CLASS | 80,460 | 0.2% |
| LOAD_FAST_LOAD_FAST | 76,660 | 0.2% |
| BINARY_OP | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,724,100 | 52.9% |
| BINARY_OP_MULTIPLY_FLOAT | 34,588,820 | 37.5% |
| BINARY_SUBSCR | 8,800,940 | 9.6% |
| BINARY_OP | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,796,220 | 53.0% |
| SWAP | 26,267,980 | 28.5% |
| STORE_FAST | 17,049,720 | 18.5% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 35,058,880 | 95.0% |
| LOAD_FAST_LOAD_FAST | 1,080,420 | 2.9% |
| ENTER_EXECUTOR | 749,100 | 2.0% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,187,620 | 79.1% |
| LOAD_FAST | 7,683,180 | 20.8% |
| COMPARE_OP_INT | 15,920 | 0.0% |
| BUILD_TUPLE | 940 | 0.0% |
| CALL_BUILTIN_CLASS | 940 | 0.0% |


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
| LOAD_FAST | 17,177,000 | 99.5% |
| BINARY_OP_MULTIPLY_INT | 80,460 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 940 | 0.0% |
| CALL | 740 | 0.0% |
| BINARY_SUBSCR | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 16,971,980 | 98.3% |
| GET_ITER | 283,880 | 1.6% |
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
| LOAD_FAST | 8,380 | 2.0% |
| BINARY_OP | 8,260 | 2.0% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 420,700 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,111,420 | 84.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,800,940 | 16.0% |
| LOAD_FAST | 4,740 | 0.0% |
| LOAD_CONST | 4,300 | 0.0% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 54,921,880 | 100.0% |
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
| LOAD_ATTR_INSTANCE_VALUE | 92,198,320 | 41.5% |
| COPY | 92,198,320 | 41.5% |
| LOAD_CONST | 28,984,780 | 13.1% |
| LOAD_FAST_LOAD_FAST | 8,417,640 | 3.8% |
| ENTER_EXECUTOR | 75,700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 221,883,220 | 100.0% |
| POP_JUMP_IF_TRUE | 7,980 | 0.0% |
| EXTENDED_ARG | 7,980 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 283,960 | 96.8% |
| JUMP_BACKWARD | 8,500 | 2.9% |
| FOR_ITER | 620 | 0.2% |
| SWAP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 284,380 | 97.0% |
| LOAD_FAST | 8,040 | 2.7% |
| STORE_FAST_LOAD_FAST | 360 | 0.1% |
| LOAD_GLOBAL | 160 | 0.1% |
| LOAD_GLOBAL_MODULE | 160 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 253,621,280 | 79.0% |
| LOAD_FAST_LOAD_FAST | 67,481,160 | 21.0% |
| LOAD_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 157,039,280 | 48.9% |
| COMPARE_OP_INT | 92,198,320 | 28.7% |
| BINARY_OP_MULTIPLY_INT | 46,099,160 | 14.4% |
| TO_BOOL_BOOL | 16,963,720 | 5.3% |
| STORE_FAST_STORE_FAST | 8,801,060 | 2.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,899,920 | 100.0% |
| STORE_FAST_LOAD_FAST | 340 | 0.0% |
| LOAD_ATTR | 260 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,099,160 | 84.0% |
| CALL_PY_EXACT_ARGS | 8,800,940 | 16.0% |
| LOAD_FAST | 300 | 0.0% |
| CALL | 100 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 25,380 | 98.6% |
| LOAD_ATTR | 360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 17,460 | 67.8% |
| BINARY_OP_MULTIPLY_FLOAT | 8,260 | 32.1% |
| BINARY_OP | 20 | 0.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,967,860 | 76.3% |
| LOAD_FAST_LOAD_FAST | 5,261,020 | 23.7% |
| ENTER_EXECUTOR | 2,880 | 0.0% |
| LOAD_ATTR | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 16,963,720 | 76.3% |
| BINARY_OP | 5,260,540 | 23.7% |
| LOAD_CONST | 3,960 | 0.0% |
| LOAD_FAST | 3,960 | 0.0% |
| CALL | 180 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80,450,480 | 45.2% |
| LOAD_FAST | 80,450,240 | 45.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 16,963,720 | 9.5% |
| ENTER_EXECUTOR | 156,000 | 0.1% |
| STORE_FAST | 128,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,548,500 | 54.8% |
| CALL_ISINSTANCE | 80,450,240 | 45.2% |
| LOAD_CONST | 161,640 | 0.1% |
| LOAD_FAST_LOAD_FAST | 9,760 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,000 | 45.3% |
| POP_JUMP_IF_FALSE | 12,300 | 25.3% |
| BINARY_OP | 8,260 | 17.0% |
| POP_TOP | 4,000 | 8.2% |
| LOAD_GLOBAL | 960 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 25,380 | 52.2% |
| LOAD_FAST_LOAD_FAST | 16,960 | 34.9% |
| LOAD_FAST | 4,480 | 9.2% |
| LOAD_CONST | 1,400 | 2.9% |
| LOAD_ATTR | 360 | 0.7% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 118,050,820 | 64.8% |
| CALL_PY_EXACT_ARGS | 54,921,880 | 30.1% |
| CACHE | 8,498,820 | 4.7% |
| FOR_ITER_GEN | 799,980 | 0.4% |
| CALL_FUNCTION_EX | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 80,450,480 | 44.1% |
| LOAD_FAST | 54,916,840 | 30.1% |
| LOAD_CONST | 46,103,600 | 25.3% |
| POP_TOP | 799,980 | 0.4% |
| LOAD_GLOBAL_MODULE | 540 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 30,095,200 | 100.0% |
| LOAD_FAST | 1,000 | 0.0% |
| STORE_ATTR | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,095,080 | 100.0% |
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
| CALL_ISINSTANCE | 80,450,240 | 82.6% |
| LOAD_ATTR_INSTANCE_VALUE | 16,963,720 | 17.4% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 97,414,060 | 100.0% |


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

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,532,800 | 80.4% |
| BINARY_OP_ADD_INT | 7,683,180 | 19.6% |
| BINARY_OP_SUBTRACT_INT | 940 | 0.0% |
| LOAD_FAST_LOAD_FAST | 680 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 30,733,560 | 78.4% |
| STORE_SUBSCR | 8,483,200 | 21.6% |
| YIELD_VALUE | 680 | 0.0% |
| BINARY_SUBSCR | 200 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 92,380,900 | 33.4% |
| SWAP | 92,198,400 | 33.3% |
| LOAD_FAST_LOAD_FAST | 32,860,600 | 11.9% |
| BINARY_OP_ADD_INT | 32,856,260 | 11.9% |
| LOAD_FAST | 26,664,000 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 92,380,900 | 33.4% |
| COPY | 92,380,900 | 33.4% |
| COMPARE_OP_INT | 92,198,320 | 33.3% |
| COMPARE_OP | 80 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 163,840 | 91.1% |
| BINARY_OP | 16,000 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 179,200 | 99.6% |
| JUMP_BACKWARD | 640 | 0.4% |


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

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 100,484,600 | 34.3% |
| LOAD_FAST | 92,198,400 | 31.4% |
| BINARY_OP_ADD_FLOAT | 73,816,220 | 25.2% |
| BINARY_OP_SUBTRACT_FLOAT | 26,267,980 | 9.0% |
| BINARY_OP_MULTIPLY_FLOAT | 400,260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 100,484,600 | 34.3% |
| SWAP | 100,484,600 | 34.3% |
| COPY | 92,198,400 | 31.4% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.0% |
| BUILD_LIST | 240 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 799,320 | 99.9% |
| BUILD_TUPLE | 680 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 799,960 | 100.0% |
| INTERPRETER_EXIT | 20 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 52,592,360 | 44.6% |
| ENTER_EXECUTOR | 34,724,600 | 29.4% |
| BUILD_TUPLE | 30,733,560 | 26.0% |
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

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,099,120 | 98.3% |
| YIELD_VALUE | 799,960 | 1.7% |
| FOR_ITER | 7,960 | 0.0% |
| UNPACK_SEQUENCE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 46,907,120 | 100.0% |


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
| ENTER_EXECUTOR | 71,680 | 89.6% |
| POP_JUMP_IF_FALSE | 8,000 | 10.0% |
| JUMP_BACKWARD | 320 | 0.4% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 360 | 94.7% |
| FOR_ITER | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 340 | 89.5% |
| LOAD_ATTR | 40 | 10.5% |


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
|     deferred | 9,479,520 | 1.7% |
|          hit | 562,574,620 | 98.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,460 | 24.3% |
| Failure | 7,660 | 75.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 2,000 | 26.1% |
| multiply different types | 1,400 | 18.3% |
| rshift | 1,320 | 17.2% |
| true divide other | 840 | 11.0% |
| remainder | 780 | 10.2% |
| lshift | 420 | 5.5% |
| true divide float | 420 | 5.5% |
| floor divide | 340 | 4.4% |
| true divide different types | 140 | 1.8% |


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
|     deferred | 234,099,600 | 53.9% |
|          hit | 200,085,860 | 46.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 0.6% |
| Failure | 62,580 | 99.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 62,580 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,280 | 0.0% |
|          hit | 153,053,380 | 100.0% |

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
|     deferred | 8,809,640 | 3.7% |
|          hit | 230,295,140 | 96.3% |

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
|     deferred | 8,720 | 0.8% |
|          hit | 1,093,340 | 99.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 640 | 82.1% |
| Failure | 140 | 17.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| zip | 140 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,960 | 0.0% |
|          hit | 398,249,600 | 100.0% |
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
|          hit | 178,218,760 | 100.0% |

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
|          hit | 30,096,920 | 100.0% |

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
|     deferred | 172,761,320 | 100.0% |
|          hit | 15,180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.0% |
| Failure | 46,880 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 44,160 | 94.2% |
| py simple | 2,720 | 5.8% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 97,414,060 | 100.0% |

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
|          hit | 46,907,120 | 100.0% |

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
| Basic | 3,002,690,720 | 51.4% |
| Not specialized | 761,842,500 | 13.0% |
| Specialized hits | 2,080,276,380 | 35.6% |
| Specialized misses | 12,240 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 234,099,600 | 55.1% |
| STORE_SUBSCR | 172,761,320 | 40.6% |
| BINARY_OP | 9,479,520 | 2.2% |
| COMPARE_OP | 8,809,640 | 2.1% |
| CALL | 20,280 | 0.0% |
| FOR_ITER | 8,720 | 0.0% |
| LOAD_GLOBAL | 1,980 | 0.0% |
| LOAD_ATTR | 1,960 | 0.0% |
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
| Calls to PyEval_EvalDefault | 8,499,020 | 4.7% |
| Calls to Python functions inlined | 173,774,300 | 95.3% |
| Calls via PyEval_EvalFrame (total) | 8,499,020 | 4.7% |
| Calls via PyEval_EvalFrame (vector) | 8,499,000 | 4.7% |
| Calls via PyEval_EvalFrame (generator) | 20 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,499,000 | 4.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 8,498,700 | 4.7% |
| Calls via PyEval_EvalFrame (function ex) | 800 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 181,146,760 | 99.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 818,723,360 | 57.5% |
| Frees to freelist | 818,725,940 |  |
| Allocations | 606,286,520 | 42.5% |
| Allocations to 512 bytes | 606,269,480 | 42.5% |
| Allocations to 4 kbytes | 16,480 | 0.0% |
| Allocations over 4 kbytes | 560 | 0.0% |
| Frees | 606,286,616 |  |
| New values | 300 |  |
| Interpreter increfs | 3,648,156,380 | 83.5% |
| Interpreter decrefs | 5,089,866,680 | 87.8% |
| Increfs | 722,599,790 | 16.5% |
| Decrefs | 705,861,103 | 12.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 16,068 |  |
| Method cache misses | 1,172 |  |
| Method cache collisions | 1,006 |  |
| Method cache dunder hits | 88,214,742 |  |
| Method cache dunder misses | 298 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,980 | 142,880 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 680 |  |
| Traces created | 640 | 94.1% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 160 | 23.5% |
| Trace too short | 40 | 5.9% |
| Inner loop found | 80 | 11.8% |
| Recursive call | 0 | 0.0% |
| Traces executed | 106,307,180 |  |
| Uops executed | 7,557,139,940 | 71.09 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 6.2% |
| <= 32 | 180 | 28.1% |
| <= 64 | 100 | 15.6% |
| <= 128 | 320 | 50.0% |


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
| <= 16 | 60 | 9.4% |
| <= 32 | 200 | 31.2% |
| <= 64 | 80 | 12.5% |
| <= 128 | 300 | 46.9% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 8,773,060 | 8.3% |
| <= 16 | 27,461,820 | 25.8% |
| <= 32 | 13,234,700 | 12.4% |
| <= 64 | 6,282,460 | 5.9% |
| <= 128 | 49,175,180 | 46.3% |
| <= 256 | 15,960 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 40 | 0.0% |
| <= 2,048 | 1,359,960 | 1.3% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 4,000 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 1,732,042,760 | 22.9% | 22.9% |  |
| LOAD_FAST | 1,703,941,420 | 22.5% | 45.5% |  |
| STORE_FAST | 553,703,920 | 7.3% | 52.8% |  |
| _GUARD_BOTH_FLOAT | 413,584,760 | 5.5% | 58.3% |  |
| _BINARY_SUBSCR | 382,328,380 | 5.1% | 63.3% |  |
| _GUARD_BOTH_INT | 322,075,760 | 4.3% | 67.6% |  |
| LOAD_CONST | 261,103,860 | 3.5% | 71.0% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 210,969,600 | 2.8% | 73.8% |  |
| _BINARY_OP_ADD_INT | 209,668,060 | 2.8% | 76.6% |  |
| _POP_JUMP_IF_TRUE | 195,461,700 | 2.6% | 79.2% |  |
| _ITER_CHECK_RANGE | 188,875,700 | 2.5% | 81.7% |  |
| _IS_ITER_EXHAUSTED_RANGE | 188,875,700 | 2.5% | 84.2% |  |
| _ITER_NEXT_RANGE | 178,738,580 | 2.4% | 86.6% |  |
| _EXIT_TRACE | 106,304,300 | 1.4% | 88.0% |  |
| _BINARY_OP_ADD_FLOAT | 104,806,300 | 1.4% | 89.4% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 97,808,860 | 1.3% | 90.6% |  |
| _BINARY_OP_MULTIPLY_INT | 93,791,060 | 1.2% | 91.9% |  |
| _STORE_SUBSCR | 81,124,300 | 1.1% | 93.0% |  |
| _JUMP_TO_TOP | 76,866,740 | 1.0% | 94.0% |  |
| COPY | 48,790,200 | 0.6% | 94.6% |  |
| _GUARD_TYPE_VERSION | 43,882,340 | 0.6% | 95.2% |  |
| SWAP | 32,582,800 | 0.4% | 95.6% |  |
| _BINARY_OP | 32,071,180 | 0.4% | 96.1% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 28,654,200 | 0.4% | 96.4% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 28,654,200 | 0.4% | 96.8% |  |
| _POP_JUMP_IF_FALSE | 22,777,780 | 0.3% | 97.1% |  |
| COMPARE_OP_INT | 21,201,000 | 0.3% | 97.4% |  |
| _BINARY_OP_SUBTRACT_INT | 18,616,640 | 0.2% | 97.6% |  |
| _GUARD_KEYS_VERSION | 11,395,460 | 0.2% | 97.8% | 0.0% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 11,395,460 | 0.2% | 97.9% |  |
| _GUARD_GLOBALS_VERSION | 10,569,180 | 0.1% | 98.1% |  |
| _GUARD_BUILTINS_VERSION | 10,327,680 | 0.1% | 98.2% |  |
| _LOAD_GLOBAL_BUILTINS | 10,327,680 | 0.1% | 98.4% |  |
| POP_TOP | 10,137,120 | 0.1% | 98.5% |  |
| CALL_BUILTIN_CLASS | 9,932,580 | 0.1% | 98.6% |  |
| GET_ITER | 9,860,880 | 0.1% | 98.8% |  |
| BUILD_TUPLE | 8,481,560 | 0.1% | 98.9% |  |
| RESUME_CHECK | 8,173,640 | 0.1% | 99.0% |  |
| _CHECK_PEP_523 | 8,173,640 | 0.1% | 99.1% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 8,173,640 | 0.1% | 99.2% |  |
| _CHECK_STACK_SPACE | 8,173,640 | 0.1% | 99.3% |  |
| _INIT_CALL_PY_EXACT_ARGS | 8,173,640 | 0.1% | 99.4% |  |
| _PUSH_FRAME | 8,173,640 | 0.1% | 99.5% |  |
| _SAVE_RETURN_OFFSET | 8,173,640 | 0.1% | 99.6% |  |
| _COMPARE_OP | 8,162,780 | 0.1% | 99.7% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 8,162,780 | 0.1% | 99.8% |  |
| _GUARD_DORV_VALUES | 3,832,680 | 0.1% | 99.9% |  |
| _STORE_ATTR_INSTANCE_VALUE | 3,832,680 | 0.1% | 99.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,229,800 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_MODULE | 241,500 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 215,100 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 215,100 | 0.0% | 100.0% |  |
| PUSH_NULL | 143,400 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 143,400 | 0.0% | 100.0% |  |
| BUILD_LIST | 15,540 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_SUBSCR_GETITEM | 180 |
| YIELD_VALUE | 40 |
| CALL | 20 |
| FOR_ITER | 20 |
| FOR_ITER_GEN | 20 |


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
Stats gathered on: 2023-11-08
