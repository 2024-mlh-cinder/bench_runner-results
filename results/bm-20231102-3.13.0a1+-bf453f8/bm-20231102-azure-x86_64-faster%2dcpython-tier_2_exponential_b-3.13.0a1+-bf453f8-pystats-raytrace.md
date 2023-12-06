
# Pystats results

- benchmark: raytrace
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 755,440,800 | 22.4% | 22.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 507,269,620 | 15.0% | 37.5% | 0.1% |
| RESUME_CHECK | 221,609,580 | 6.6% | 44.0% |  |
| RETURN_VALUE | 189,277,120 | 5.6% | 49.6% |  |
| LOAD_FAST_LOAD_FAST | 180,749,880 | 5.4% | 55.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 172,145,380 | 5.1% | 60.1% | 5.4% |
| CALL_PY_EXACT_ARGS | 151,663,760 | 4.5% | 64.6% | 1.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 142,968,140 | 4.2% | 68.8% | 1.5% |
| STORE_ATTR_INSTANCE_VALUE | 128,143,400 | 3.8% | 72.6% | 0.0% |
| BINARY_OP_ADD_FLOAT | 92,345,380 | 2.7% | 75.4% | 8.8% |
| RETURN_CONST | 84,603,600 | 2.5% | 77.9% |  |
| STORE_FAST | 72,967,060 | 2.2% | 80.1% |  |
| BINARY_OP | 72,879,720 | 2.2% | 82.2% |  |
| BINARY_OP_SUBTRACT_FLOAT | 67,918,880 | 2.0% | 84.2% | 29.7% |
| LOAD_CONST | 54,765,320 | 1.6% | 85.9% |  |
| LOAD_GLOBAL_MODULE | 53,887,300 | 1.6% | 87.5% | 0.0% |
| EXIT_INIT_CHECK | 44,517,200 | 1.3% | 88.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 44,517,200 | 1.3% | 90.1% |  |
| POP_JUMP_IF_FALSE | 43,041,040 | 1.3% | 91.4% |  |
| POP_TOP | 42,787,820 | 1.3% | 92.6% |  |
| INTERPRETER_EXIT | 25,483,520 | 0.8% | 93.4% |  |
| TO_BOOL_BOOL | 24,682,420 | 0.7% | 94.1% |  |
| ENTER_EXECUTOR | 22,179,000 | 0.7% | 94.8% |  |
| BINARY_OP_MULTIPLY_INT | 18,128,660 | 0.5% | 95.3% | 63.4% |
| COMPARE_OP | 16,460,520 | 0.5% | 95.8% |  |
| BUILD_TUPLE | 11,050,720 | 0.3% | 96.1% |  |
| CALL_BUILTIN_O | 10,271,320 | 0.3% | 96.4% |  |
| PUSH_NULL | 10,146,320 | 0.3% | 96.7% |  |
| LIST_APPEND | 9,769,600 | 0.3% | 97.0% |  |
| LOAD_GLOBAL_BUILTIN | 9,478,300 | 0.3% | 97.3% |  |
| LOAD_ATTR_MODULE | 9,346,000 | 0.3% | 97.6% |  |
| POP_JUMP_IF_NOT_NONE | 9,070,280 | 0.3% | 97.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 8,925,880 | 0.3% | 98.1% |  |
| BINARY_OP_SUBTRACT_INT | 6,505,540 | 0.2% | 98.3% | 7.2% |
| CALL | 5,233,360 | 0.2% | 98.5% |  |
| POP_JUMP_IF_TRUE | 4,291,440 | 0.1% | 98.6% |  |
| BINARY_OP_ADD_INT | 4,240,740 | 0.1% | 98.7% | 0.0% |
| FOR_ITER_LIST | 3,726,120 | 0.1% | 98.8% |  |
| GET_ITER | 3,723,420 | 0.1% | 99.0% |  |
| UNARY_NEGATIVE | 3,533,840 | 0.1% | 99.1% |  |
| CALL_BUILTIN_CLASS | 3,326,180 | 0.1% | 99.2% |  |
| STORE_SUBSCR | 3,201,520 | 0.1% | 99.2% |  |
| COMPARE_OP_FLOAT | 2,619,220 | 0.1% | 99.3% |  |
| BUILD_LIST | 2,448,160 | 0.1% | 99.4% |  |
| LOAD_FAST_AND_CLEAR | 2,442,400 | 0.1% | 99.5% |  |
| SWAP | 2,442,400 | 0.1% | 99.5% |  |
| STORE_FAST_STORE_FAST | 2,075,500 | 0.1% | 99.6% |  |
| TO_BOOL | 2,040,960 | 0.1% | 99.7% |  |
| NOP | 2,015,840 | 0.1% | 99.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,648,820 | 0.0% | 99.8% |  |
| COMPARE_OP_INT | 1,226,620 | 0.0% | 99.8% |  |
| LOAD_ATTR | 1,115,280 | 0.0% | 99.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 821,600 | 0.0% | 99.9% |  |
| CALL_LIST_APPEND | 819,620 | 0.0% | 99.9% |  |
| CALL_FUNCTION_EX | 800,240 | 0.0% | 99.9% |  |
| CALL_INTRINSIC_1 | 800,080 | 0.0% | 99.9% |  |
| LIST_EXTEND | 800,080 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 451,120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 426,620 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 308,540 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 5,180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,520 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,980 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,980 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,060 | 0.0% | 100.0% |  |
| RESUME | 720 | 0.0% | 100.0% |  |
| CALL_KW | 560 | 0.0% | 100.0% |  |
| FOR_ITER | 400 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 320 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 240 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |  |
| BUILD_MAP | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| DICT_MERGE | 80 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 469,490,820 | 13.9% | 13.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 224,310,120 | 6.7% | 20.6% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_FLOAT | 157,546,120 | 4.7% | 25.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 151,608,360 | 4.5% | 29.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 134,162,560 | 4.0% | 33.7% |
| RESUME_CHECK LOAD_FAST | 130,726,920 | 3.9% | 37.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 117,843,980 | 3.5% | 41.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 83,054,320 | 2.5% | 43.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 73,326,680 | 2.2% | 45.7% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 70,109,240 | 2.1% | 47.8% |
| STORE_FAST LOAD_FAST | 64,419,140 | 1.9% | 49.7% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 51,536,660 | 1.5% | 51.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 47,445,280 | 1.4% | 52.7% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 46,980,640 | 1.4% | 54.1% |
| RETURN_VALUE RETURN_VALUE | 45,571,120 | 1.4% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 45,312,780 | 1.3% | 56.8% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 44,634,960 | 1.3% | 58.1% |
| EXIT_INIT_CHECK RETURN_VALUE | 44,517,200 | 1.3% | 59.4% |
| RETURN_CONST EXIT_INIT_CHECK | 44,517,200 | 1.3% | 60.7% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 44,517,200 | 1.3% | 62.0% |
| LOAD_FAST RETURN_VALUE | 43,718,240 | 1.3% | 63.3% |
| RETURN_VALUE POP_TOP | 41,952,240 | 1.2% | 64.6% |
| POP_TOP LOAD_FAST | 40,790,080 | 1.2% | 65.8% |
| BINARY_OP_ADD_FLOAT RETURN_VALUE | 40,682,960 | 1.2% | 67.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 37,762,840 | 1.1% | 68.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_FLOAT | 36,709,640 | 1.1% | 69.2% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST | 36,284,440 | 1.1% | 70.3% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 36,025,300 | 1.1% | 71.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 33,122,680 | 1.0% | 72.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 26,704,240 | 0.8% | 73.1% |
| BINARY_OP CALL_ALLOC_AND_ENTER_INIT | 26,509,880 | 0.8% | 73.9% |
| CACHE RESUME_CHECK | 25,483,300 | 0.8% | 74.7% |
| RETURN_VALUE STORE_FAST | 25,351,180 | 0.8% | 75.4% |
| RETURN_VALUE INTERPRETER_EXIT | 24,682,480 | 0.7% | 76.1% |
| RETURN_CONST TO_BOOL_BOOL | 24,682,360 | 0.7% | 76.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 24,682,320 | 0.7% | 77.6% |
| LOAD_FAST LOAD_CONST | 24,239,120 | 0.7% | 78.3% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 23,940,720 | 0.7% | 79.0% |
| RESUME_CHECK RETURN_CONST | 23,829,160 | 0.7% | 79.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 23,829,160 | 0.7% | 80.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 20,770,480 | 0.6% | 81.1% |
| LOAD_CONST COMPARE_OP | 16,455,400 | 0.5% | 81.6% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 16,396,600 | 0.5% | 82.0% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 15,712,820 | 0.5% | 82.5% |
| COMPARE_OP POP_JUMP_IF_FALSE | 15,636,500 | 0.5% | 83.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 14,932,140 | 0.4% | 83.4% |
| BINARY_OP STORE_FAST | 14,736,120 | 0.4% | 83.9% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 14,356,880 | 0.4% | 84.3% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 14,356,560 | 0.4% | 84.7% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 14,356,520 | 0.4% | 85.1% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 14,316,580 | 0.4% | 85.6% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 0.4% | 86.0% |
| ENTER_EXECUTOR BINARY_OP | 13,905,940 | 0.4% | 86.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 13,807,280 | 0.4% | 86.8% |
| BINARY_OP LOAD_FAST | 12,160,200 | 0.4% | 87.2% |
| BINARY_OP_MULTIPLY_FLOAT CALL_ALLOC_AND_ENTER_INIT | 11,970,360 | 0.4% | 87.5% |
| LOAD_CONST LOAD_FAST | 11,568,360 | 0.3% | 87.9% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_FLOAT | 11,249,600 | 0.3% | 88.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 10,298,800 | 0.3% | 88.5% |
| RETURN_VALUE LOAD_FAST | 9,774,300 | 0.3% | 88.8% |
| LOAD_FAST BUILD_TUPLE | 9,769,680 | 0.3% | 89.1% |
| BUILD_TUPLE LIST_APPEND | 9,769,600 | 0.3% | 89.4% |
| LIST_APPEND ENTER_EXECUTOR | 9,769,260 | 0.3% | 89.7% |
| RETURN_VALUE BINARY_OP | 9,644,240 | 0.3% | 89.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_CONST | 9,526,120 | 0.3% | 90.2% |
| PUSH_NULL LOAD_FAST | 9,346,000 | 0.3% | 90.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 9,345,940 | 0.3% | 90.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 9,345,840 | 0.3% | 91.1% |
| BINARY_OP CALL_PY_EXACT_ARGS | 9,099,440 | 0.3% | 91.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 9,076,280 | 0.3% | 91.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 9,070,280 | 0.3% | 91.9% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 8,925,720 | 0.3% | 92.1% |
| CALL_BUILTIN_O RETURN_VALUE | 8,790,940 | 0.3% | 92.4% |
| RETURN_VALUE CALL_BUILTIN_O | 8,790,920 | 0.3% | 92.7% |
| RETURN_CONST LOAD_FAST | 8,275,840 | 0.2% | 92.9% |
| RETURN_VALUE CALL_PY_EXACT_ARGS | 7,480,360 | 0.2% | 93.1% |
| POP_JUMP_IF_NOT_NONE ENTER_EXECUTOR | 6,572,480 | 0.2% | 93.3% |
| RETURN_CONST STORE_FAST | 6,326,000 | 0.2% | 93.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_FLOAT | 5,300,080 | 0.2% | 93.7% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 5,226,560 | 0.2% | 93.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 4,949,000 | 0.1% | 94.0% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 4,799,760 | 0.1% | 94.1% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 4,396,240 | 0.1% | 94.2% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 4,066,100 | 0.1% | 94.4% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 3,864,240 | 0.1% | 94.5% |
| BINARY_SUBSCR_TUPLE_INT LOAD_FAST_LOAD_FAST | 3,839,700 | 0.1% | 94.6% |
| BINARY_SUBSCR_TUPLE_INT BINARY_OP | 3,785,880 | 0.1% | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_INT | 3,675,500 | 0.1% | 94.8% |
| BINARY_OP_SUBTRACT_INT CALL_ALLOC_AND_ENTER_INIT | 3,545,160 | 0.1% | 94.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,457,920 | 0.1% | 95.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,326,060 | 0.1% | 95.1% |
| LOAD_FAST BINARY_OP | 3,259,040 | 0.1% | 95.2% |
| BINARY_OP RETURN_VALUE | 2,999,040 | 0.1% | 95.3% |
| ENTER_EXECUTOR LOAD_FAST | 2,966,060 | 0.1% | 95.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,893,280 | 0.1% | 95.5% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,874,520 | 0.1% | 95.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 2,821,440 | 0.1% | 95.6% |
| COMPARE_OP_FLOAT POP_JUMP_IF_TRUE | 2,619,220 | 0.1% | 95.7% |
| GET_ITER FOR_ITER_LIST | 2,501,420 | 0.1% | 95.8% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,466,720 | 0.1% | 95.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,483,300 | 100.0% |
| RESUME | 220 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 160 | 50.0% |
| BINARY_OP | 60 | 18.8% |
| LOAD_FAST_LOAD_FAST | 60 | 18.8% |
| COMPARE_OP | 20 | 6.2% |
| STORE_FAST | 20 | 6.2% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 44,517,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 44,517,200 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,074,800 | 55.7% |
| LOAD_FAST | 1,221,280 | 32.8% |
| RETURN_VALUE | 426,640 | 11.5% |
| CALL_BUILTIN_CLASS | 560 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 2,501,420 | 67.2% |
| LOAD_FAST_AND_CLEAR | 1,221,200 | 32.8% |
| FOR_ITER_RANGE | 560 | 0.0% |
| FOR_ITER | 160 | 0.0% |
| EXTENDED_ARG | 80 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 24,682,480 | 96.9% |
| RETURN_CONST | 801,040 | 3.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,221,200 | 60.6% |
| POP_JUMP_IF_NOT_NONE | 794,560 | 39.4% |
| POP_TOP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,015,760 | 100.0% |
| LOAD_DEREF | 80 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 41,952,240 | 98.0% |
| CALL_FUNCTION_EX | 800,000 | 1.9% |
| POP_JUMP_IF_TRUE | 34,400 | 0.1% |
| RETURN_CONST | 1,040 | 0.0% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,790,080 | 95.3% |
| LOAD_GLOBAL_MODULE | 853,360 | 2.0% |
| ENTER_EXECUTOR | 799,800 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 308,560 | 0.7% |
| RETURN_CONST | 34,440 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 9,345,940 | 92.1% |
| LOAD_ATTR | 800,220 | 7.9% |
| LOAD_DEREF | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,346,000 | 92.1% |
| LOAD_FAST_LOAD_FAST | 800,000 | 7.9% |
| CALL | 240 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,571,120 | 24.1% |
| EXIT_INIT_CHECK | 44,517,200 | 23.5% |
| LOAD_FAST | 43,718,240 | 23.1% |
| BINARY_OP_ADD_FLOAT | 40,682,960 | 21.5% |
| CALL_BUILTIN_O | 8,790,940 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,571,120 | 24.1% |
| POP_TOP | 41,952,240 | 22.2% |
| STORE_FAST | 25,351,180 | 13.4% |
| INTERPRETER_EXIT | 24,682,480 | 13.0% |
| LOAD_FAST_LOAD_FAST | 14,356,560 | 7.6% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,600,340 | 50.0% |
| LOAD_FAST | 800,000 | 25.0% |
| ENTER_EXECUTOR | 799,600 | 25.0% |
| STORE_SUBSCR | 1,520 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,599,920 | 50.0% |
| RETURN_CONST | 800,000 | 25.0% |
| ENTER_EXECUTOR | 799,660 | 25.0% |
| STORE_SUBSCR | 1,520 | 0.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040,120 | 100.0% |
| TO_BOOL | 680 | 0.0% |
| RETURN_CONST | 120 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,040,160 | 100.0% |
| TO_BOOL | 680 | 0.0% |
| TO_BOOL_BOOL | 60 | 0.0% |
| POP_JUMP_IF_TRUE | 20 | 0.0% |
| TO_BOOL_INT | 20 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040,080 | 57.7% |
| LOAD_GLOBAL_MODULE | 1,493,740 | 42.3% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,040,080 | 57.7% |
| COMPARE_OP_FLOAT | 1,493,720 | 42.3% |
| COMPARE_OP | 40 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 36,025,300 | 49.4% |
| ENTER_EXECUTOR | 13,905,940 | 19.1% |
| RETURN_VALUE | 9,644,240 | 13.2% |
| BINARY_SUBSCR_TUPLE_INT | 3,785,880 | 5.2% |
| LOAD_FAST | 3,259,040 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 26,509,880 | 36.4% |
| STORE_FAST | 14,736,120 | 20.2% |
| LOAD_FAST | 12,160,200 | 16.7% |
| CALL_PY_EXACT_ARGS | 9,099,440 | 12.5% |
| BINARY_OP_ADD_FLOAT | 4,066,100 | 5.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,221,200 | 49.9% |
| LOAD_FAST_LOAD_FAST | 800,000 | 32.7% |
| RESUME_CHECK | 426,680 | 17.4% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,221,200 | 49.9% |
| LOAD_FAST | 800,160 | 32.7% |
| STORE_FAST | 426,640 | 17.4% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,769,680 | 88.4% |
| BINARY_OP_ADD_FLOAT | 1,271,860 | 11.5% |
| BINARY_OP | 8,060 | 0.1% |
| LOAD_FAST_LOAD_FAST | 640 | 0.0% |
| LOAD_CONST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 9,769,600 | 88.4% |
| RETURN_VALUE | 1,279,920 | 11.6% |
| CALL_LIST_APPEND | 600 | 0.0% |
| LOAD_CONST | 480 | 0.0% |
| BUILD_MAP | 80 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,402,860 | 45.9% |
| CALL_BUILTIN_CLASS | 2,399,940 | 45.9% |
| LOAD_FAST | 427,520 | 8.2% |
| BINARY_OP | 620 | 0.0% |
| LOAD_CONST | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,402,860 | 45.9% |
| LOAD_FAST | 2,400,280 | 45.9% |
| STORE_FAST | 426,860 | 8.2% |
| CALL_PY_EXACT_ARGS | 960 | 0.0% |
| RESUME_CHECK | 520 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 800,080 | 100.0% |
| DICT_MERGE | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 800,000 | 100.0% |
| RESUME_CHECK | 140 | 0.0% |
| COPY_FREE_VARS | 80 | 0.0% |
| RESUME | 20 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 800,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 800,080 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 480 | 85.7% |
| CALL | 80 | 14.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,455,400 | 100.0% |
| COMPARE_OP | 5,000 | 0.0% |
| UNARY_NEGATIVE | 40 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,636,500 | 95.0% |
| POP_JUMP_IF_TRUE | 818,940 | 5.0% |
| COMPARE_OP | 5,000 | 0.0% |
| COMPARE_OP_FLOAT | 60 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 9,769,260 | 44.0% |
| POP_JUMP_IF_NOT_NONE | 6,572,480 | 29.6% |
| POP_JUMP_IF_TRUE | 2,255,900 | 10.2% |
| STORE_FAST | 1,155,400 | 5.2% |
| CALL_LIST_APPEND | 818,540 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 13,905,940 | 62.7% |
| LOAD_FAST | 2,966,060 | 13.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,039,960 | 9.2% |
| STORE_FAST | 1,221,160 | 5.5% |
| RETURN_CONST | 818,680 | 3.7% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 33.3% |
| POP_TOP | 80 | 33.3% |
| JUMP_BACKWARD | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 120 | 50.0% |
| JUMP_BACKWARD | 80 | 33.3% |
| FOR_ITER | 40 | 16.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 180 | 45.0% |
| GET_ITER | 160 | 40.0% |
| EXTENDED_ARG | 40 | 10.0% |
| SWAP | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 40.0% |
| FOR_ITER_LIST | 100 | 25.0% |
| FOR_ITER_RANGE | 100 | 25.0% |
| UNPACK_SEQUENCE | 40 | 10.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,700 | 32.8% |
| POP_TOP | 700 | 13.5% |
| POP_JUMP_IF_NOT_NONE | 680 | 13.1% |
| STORE_FAST | 680 | 13.1% |
| STORE_SUBSCR | 340 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,420 | 66.0% |
| FOR_ITER_RANGE | 1,200 | 23.2% |
| ENTER_EXECUTOR | 300 | 5.8% |
| FOR_ITER | 180 | 3.5% |
| EXTENDED_ARG | 80 | 1.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 9,769,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,769,260 | 100.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800,000 | 100.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 800,080 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 804,560 | 72.1% |
| LOAD_GLOBAL_MODULE | 308,940 | 27.7% |
| LOAD_ATTR | 840 | 0.1% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_GLOBAL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 800,220 | 71.8% |
| BINARY_OP | 309,020 | 27.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,680 | 0.2% |
| LOAD_FAST | 1,060 | 0.1% |
| LOAD_ATTR | 840 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,239,120 | 44.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,526,120 | 17.4% |
| LOAD_GLOBAL_BUILTIN | 5,226,560 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,949,000 | 9.0% |
| LOAD_FAST_LOAD_FAST | 3,864,240 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 16,455,400 | 30.0% |
| LOAD_FAST | 11,568,360 | 21.1% |
| BINARY_SUBSCR_TUPLE_INT | 8,925,720 | 16.3% |
| LOAD_GLOBAL_BUILTIN | 4,799,760 | 8.8% |
| BINARY_OP_ADD_INT | 2,821,440 | 5.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| BUILD_LIST | 80 | 33.3% |
| RESUME_CHECK | 60 | 25.0% |
| RESUME | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 66.7% |
| LIST_EXTEND | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 224,310,120 | 29.7% |
| RESUME_CHECK | 130,726,920 | 17.3% |
| STORE_FAST | 64,419,140 | 8.5% |
| BINARY_OP_MULTIPLY_FLOAT | 51,536,660 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 47,445,280 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 469,490,820 | 62.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 134,162,560 | 17.8% |
| RETURN_VALUE | 43,718,240 | 5.8% |
| CALL_PY_EXACT_ARGS | 33,122,680 | 4.4% |
| LOAD_CONST | 24,239,120 | 3.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,221,200 | 50.0% |
| LOAD_FAST_AND_CLEAR | 1,221,200 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 1,221,200 | 50.0% |
| SWAP | 1,221,200 | 50.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 73,326,680 | 40.6% |
| RESUME_CHECK | 44,634,960 | 24.7% |
| BINARY_OP_MULTIPLY_FLOAT | 23,940,720 | 13.2% |
| LOAD_GLOBAL_MODULE | 14,932,140 | 8.3% |
| RETURN_VALUE | 14,356,560 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 117,843,980 | 65.2% |
| LOAD_ATTR_INSTANCE_VALUE | 37,762,840 | 20.9% |
| BINARY_OP_MULTIPLY_FLOAT | 14,356,520 | 7.9% |
| LOAD_CONST | 3,864,240 | 2.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,074,680 | 1.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 19.0% |
| LOAD_CONST | 240 | 9.5% |
| POP_TOP | 160 | 6.3% |
| LOAD_ATTR | 160 | 6.3% |
| LOAD_FAST | 160 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 840 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 420 | 16.7% |
| LOAD_FAST | 340 | 13.5% |
| LOAD_CONST | 320 | 12.7% |
| LOAD_ATTR | 260 | 10.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 23,829,160 | 55.4% |
| COMPARE_OP | 15,636,500 | 36.3% |
| TO_BOOL | 2,040,160 | 4.7% |
| COMPARE_OP_INT | 1,226,620 | 2.8% |
| TO_BOOL_INT | 308,540 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 24,682,320 | 57.3% |
| RETURN_CONST | 13,807,280 | 32.1% |
| LOAD_CONST | 2,466,720 | 5.7% |
| NOP | 1,221,200 | 2.8% |
| LOAD_FAST | 863,360 | 2.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 451,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 426,640 | 94.6% |
| LOAD_FAST_LOAD_FAST | 24,480 | 5.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,070,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,572,480 | 72.5% |
| LOAD_FAST | 1,702,560 | 18.8% |
| NOP | 794,560 | 8.8% |
| JUMP_BACKWARD | 680 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 2,619,220 | 61.0% |
| TO_BOOL_BOOL | 853,260 | 19.9% |
| COMPARE_OP | 818,940 | 19.1% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,255,900 | 52.6% |
| LOAD_FAST | 1,274,160 | 29.7% |
| LOAD_FAST_LOAD_FAST | 725,280 | 16.9% |
| POP_TOP | 34,400 | 0.8% |
| JUMP_BACKWARD | 1,700 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 45,312,780 | 53.6% |
| RESUME_CHECK | 23,829,160 | 28.2% |
| POP_JUMP_IF_FALSE | 13,807,280 | 16.3% |
| ENTER_EXECUTOR | 818,680 | 1.0% |
| STORE_SUBSCR | 800,000 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 44,517,200 | 52.6% |
| TO_BOOL_BOOL | 24,682,360 | 29.2% |
| LOAD_FAST | 8,275,840 | 9.8% |
| STORE_FAST | 6,326,000 | 7.5% |
| INTERPRETER_EXIT | 801,040 | 0.9% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 67.9% |
| LOAD_FAST_LOAD_FAST | 340 | 32.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 560 | 52.8% |
| RETURN_CONST | 180 | 17.0% |
| LOAD_FAST | 120 | 11.3% |
| LOAD_CONST | 60 | 5.7% |
| LOAD_GLOBAL | 60 | 5.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 25,351,180 | 34.7% |
| BINARY_OP | 14,736,120 | 20.2% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,580 | 19.6% |
| RETURN_CONST | 6,326,000 | 8.7% |
| STORE_FAST | 2,442,400 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,419,140 | 88.3% |
| LOAD_GLOBAL_MODULE | 2,874,520 | 3.9% |
| STORE_FAST | 2,442,400 | 3.3% |
| ENTER_EXECUTOR | 1,155,400 | 1.6% |
| LOAD_FAST_LOAD_FAST | 846,960 | 1.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,648,820 | 79.4% |
| UNPACK_SEQUENCE_TUPLE | 426,620 | 20.6% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,221,480 | 58.9% |
| LOAD_FAST | 427,380 | 20.6% |
| STORE_FAST | 426,640 | 20.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 1,221,200 | 50.0% |
| LOAD_FAST_AND_CLEAR | 1,221,200 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 1,221,200 | 50.0% |
| FOR_ITER_LIST | 1,221,180 | 50.0% |
| FOR_ITER | 20 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |
| FOR_ITER_LIST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 33.3% |
| UNPACK_SEQUENCE_TUPLE | 20 | 16.7% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 400 | 55.6% |
| CACHE | 220 | 30.6% |
| CALL_PY_EXACT_ARGS | 60 | 8.3% |
| CALL_FUNCTION_EX | 20 | 2.8% |
| COPY_FREE_VARS | 20 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 58.3% |
| LOAD_GLOBAL | 100 | 13.9% |
| LOAD_FAST_LOAD_FAST | 80 | 11.1% |
| BUILD_LIST | 40 | 5.6% |
| RETURN_CONST | 40 | 5.6% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 70,109,240 | 75.9% |
| BINARY_OP_MULTIPLY_INT | 11,249,600 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,300,080 | 5.7% |
| BINARY_OP | 4,066,100 | 4.4% |
| LOAD_CONST | 925,560 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,980,640 | 50.9% |
| RETURN_VALUE | 40,682,960 | 44.1% |
| CALL_ALLOC_AND_ENTER_INIT | 1,636,760 | 1.8% |
| BUILD_TUPLE | 1,271,860 | 1.4% |
| CALL_BUILTIN_CLASS | 925,560 | 1.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,821,440 | 66.5% |
| LOAD_FAST | 799,960 | 18.9% |
| CALL_BUILTIN_CLASS | 617,040 | 14.6% |
| BINARY_OP_MULTIPLY_INT | 2,140 | 0.1% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 1,600,340 | 37.7% |
| LOAD_FAST | 1,222,240 | 28.8% |
| LOAD_CONST | 1,108,520 | 26.1% |
| LOAD_GLOBAL_BUILTIN | 308,520 | 7.3% |
| RETURN_VALUE | 1,060 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 157,546,120 | 91.5% |
| LOAD_FAST_LOAD_FAST | 14,356,520 | 8.3% |
| BINARY_OP_MULTIPLY_INT | 149,580 | 0.1% |
| BINARY_SUBSCR_TUPLE_INT | 53,820 | 0.0% |
| BINARY_OP | 25,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 70,109,240 | 40.7% |
| LOAD_FAST | 51,536,660 | 29.9% |
| LOAD_FAST_LOAD_FAST | 23,940,720 | 13.9% |
| BINARY_OP_SUBTRACT_FLOAT | 14,356,880 | 8.3% |
| CALL_ALLOC_AND_ENTER_INIT | 11,970,360 | 7.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 15,712,820 | 86.7% |
| LOAD_CONST | 2,199,020 | 12.1% |
| BINARY_OP | 182,820 | 1.0% |
| BINARY_OP_MULTIPLY_FLOAT | 33,920 | 0.2% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 11,249,600 | 62.1% |
| LOAD_FAST | 4,396,240 | 24.3% |
| CALL_BUILTIN_CLASS | 1,398,760 | 7.7% |
| STORE_FAST | 799,980 | 4.4% |
| BINARY_OP_MULTIPLY_FLOAT | 149,580 | 0.8% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 36,709,640 | 54.0% |
| BINARY_OP_MULTIPLY_FLOAT | 14,356,880 | 21.1% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 21.1% |
| LOAD_FAST | 1,599,960 | 2.4% |
| CALL_BUILTIN_O | 554,680 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,284,440 | 53.4% |
| STORE_FAST | 14,316,580 | 21.1% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 21.1% |
| CALL_PY_EXACT_ARGS | 1,599,920 | 2.4% |
| RETURN_VALUE | 554,700 | 0.8% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,675,500 | 56.5% |
| LOAD_CONST | 2,021,160 | 31.1% |
| LOAD_FAST | 799,960 | 12.3% |
| BINARY_OP | 8,200 | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 3,545,160 | 54.5% |
| LOAD_FAST | 2,151,420 | 33.1% |
| LOAD_CONST | 799,980 | 12.3% |
| BINARY_OP | 8,260 | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 700 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,925,720 | 100.0% |
| BINARY_SUBSCR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,839,700 | 43.0% |
| BINARY_OP | 3,785,880 | 42.4% |
| STORE_FAST | 1,222,020 | 13.7% |
| BINARY_OP_MULTIPLY_FLOAT | 53,820 | 0.6% |
| COMPARE_OP_FLOAT | 24,440 | 0.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 26,509,880 | 59.5% |
| BINARY_OP_MULTIPLY_FLOAT | 11,970,360 | 26.9% |
| BINARY_OP_SUBTRACT_INT | 3,545,160 | 8.0% |
| BINARY_OP_ADD_FLOAT | 1,636,760 | 3.7% |
| RETURN_VALUE | 426,600 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 44,517,200 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 1,398,760 | 42.1% |
| BINARY_OP | 1,001,160 | 30.1% |
| BINARY_OP_ADD_FLOAT | 925,560 | 27.8% |
| LOAD_ATTR_INSTANCE_VALUE | 400 | 0.0% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,399,940 | 72.2% |
| BINARY_OP_ADD_INT | 617,040 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 308,520 | 9.3% |
| GET_ITER | 560 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,790,920 | 85.6% |
| LOAD_ATTR_INSTANCE_VALUE | 925,560 | 9.0% |
| LOAD_FAST | 554,720 | 5.4% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,790,940 | 85.6% |
| LOAD_CONST | 925,620 | 9.0% |
| BINARY_OP_SUBTRACT_FLOAT | 554,680 | 5.4% |
| STORE_FAST | 60 | 0.0% |
| BINARY_OP | 20 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 818,960 | 99.9% |
| BUILD_TUPLE | 600 | 0.1% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 818,540 | 99.9% |
| RETURN_CONST | 760 | 0.1% |
| JUMP_BACKWARD | 320 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,880 | 94.9% |
| CALL | 100 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,980 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 83,054,320 | 54.8% |
| LOAD_FAST | 33,122,680 | 21.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,396,600 | 10.8% |
| BINARY_OP | 9,099,440 | 6.0% |
| RETURN_VALUE | 7,480,360 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 151,608,360 | 100.0% |
| CALL_PY_EXACT_ARGS | 55,340 | 0.0% |
| RESUME | 60 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNARY_NEGATIVE | 1,493,720 | 57.0% |
| LOAD_GLOBAL_MODULE | 1,101,000 | 42.0% |
| BINARY_SUBSCR_TUPLE_INT | 24,440 | 0.9% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,619,220 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,226,600 | 100.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,226,620 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,501,420 | 67.1% |
| SWAP | 1,221,180 | 32.8% |
| JUMP_BACKWARD | 3,420 | 0.1% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,069,200 | 55.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,648,780 | 44.2% |
| LOAD_GLOBAL_BUILTIN | 7,080 | 0.2% |
| LOAD_FAST | 700 | 0.0% |
| RETURN_CONST | 280 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,200 | 60.6% |
| GET_ITER | 560 | 28.3% |
| EXTENDED_ARG | 120 | 6.1% |
| FOR_ITER | 100 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,860 | 93.9% |
| LOAD_FAST | 40 | 2.0% |
| LOAD_GLOBAL | 40 | 2.0% |
| LOAD_GLOBAL_MODULE | 40 | 2.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 469,490,820 | 92.6% |
| LOAD_FAST_LOAD_FAST | 37,762,840 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 14,280 | 0.0% |
| LOAD_ATTR | 1,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 224,310,120 | 44.2% |
| BINARY_OP_MULTIPLY_FLOAT | 157,546,120 | 31.1% |
| BINARY_OP_SUBTRACT_FLOAT | 36,709,640 | 7.2% |
| BINARY_OP | 36,025,300 | 7.1% |
| CALL_PY_EXACT_ARGS | 16,396,600 | 3.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 820,720 | 99.9% |
| LOAD_ATTR_INSTANCE_VALUE | 720 | 0.1% |
| LOAD_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 819,000 | 99.7% |
| LOAD_CONST | 1,980 | 0.2% |
| LOAD_FAST_LOAD_FAST | 620 | 0.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 134,162,560 | 93.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,893,280 | 2.0% |
| LOAD_FAST_LOAD_FAST | 2,074,680 | 1.5% |
| ENTER_EXECUTOR | 2,039,960 | 1.4% |
| BINARY_OP | 936,880 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 83,054,320 | 58.1% |
| LOAD_FAST | 47,445,280 | 33.2% |
| LOAD_CONST | 9,526,120 | 6.7% |
| LOAD_FAST_LOAD_FAST | 1,654,300 | 1.2% |
| LOAD_GLOBAL_MODULE | 1,246,700 | 0.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,345,840 | 100.0% |
| LOAD_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 9,345,940 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,799,760 | 50.6% |
| STORE_SUBSCR | 1,599,920 | 16.9% |
| LOAD_GLOBAL_BUILTIN | 925,560 | 9.8% |
| STORE_FAST | 800,360 | 8.4% |
| ENTER_EXECUTOR | 419,520 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,226,560 | 55.1% |
| LOAD_FAST | 3,326,060 | 35.1% |
| LOAD_GLOBAL_BUILTIN | 925,560 | 9.8% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 24,682,320 | 45.8% |
| RESUME_CHECK | 20,770,480 | 38.5% |
| LOAD_FAST | 3,457,920 | 6.4% |
| STORE_FAST | 2,874,520 | 5.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,246,700 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,704,240 | 49.6% |
| LOAD_FAST_LOAD_FAST | 14,932,140 | 27.7% |
| LOAD_ATTR_MODULE | 9,345,840 | 17.3% |
| UNARY_NEGATIVE | 1,493,740 | 2.8% |
| COMPARE_OP_FLOAT | 1,101,000 | 2.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 151,608,360 | 68.4% |
| CALL_ALLOC_AND_ENTER_INIT | 44,517,200 | 20.1% |
| CACHE | 25,483,300 | 11.5% |
| CALL | 520 | 0.0% |
| CALL_FUNCTION_EX | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,726,920 | 59.0% |
| LOAD_FAST_LOAD_FAST | 44,634,960 | 20.1% |
| RETURN_CONST | 23,829,160 | 10.8% |
| LOAD_GLOBAL_MODULE | 20,770,480 | 9.4% |
| LOAD_CONST | 1,221,180 | 0.6% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 117,843,980 | 92.0% |
| LOAD_FAST | 10,298,800 | 8.0% |
| STORE_ATTR | 560 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 73,326,680 | 57.2% |
| RETURN_CONST | 45,312,780 | 35.4% |
| LOAD_FAST | 9,076,280 | 7.1% |
| RETURN_VALUE | 426,620 | 0.3% |
| LOAD_CONST | 740 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 24,682,360 | 100.0% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,829,160 | 96.5% |
| POP_JUMP_IF_TRUE | 853,260 | 3.5% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 308,520 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 308,540 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| TO_BOOL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 426,600 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 426,620 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,648,780 | 100.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,648,820 | 100.0% |


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
|     deferred | 70,784,940 | 16.3% |
|          hit | 311,787,880 | 71.8% |
|         miss | 49,496,700 | 11.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 934,840 | 44.6% |
| Failure | 1,159,940 | 55.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract different types | 771,820 | 66.5% |
| multiply different types | 219,060 | 18.9% |
| add different types | 157,880 | 13.6% |
| subtract other | 6,680 | 0.6% |
| true divide float | 2,360 | 0.2% |
| true divide different types | 1,120 | 0.1% |
| add other | 760 | 0.1% |
| remainder | 260 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 160 | 0.0% |
|          hit | 8,925,880 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,173,520 | 2.4% |
|          hit | 207,666,900 | 96.2% |
|         miss | 2,933,160 | 1.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 57,160 | 95.5% |
| Failure | 2,680 | 4.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 2,580 | 96.3% |
| cfunc noargs | 60 | 2.2% |
| class no vectorcall | 20 | 0.7% |
| init not simple | 20 | 0.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 16,455,440 | 81.0% |
|          hit | 3,845,840 | 18.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 1.6% |
| Failure | 5,000 | 98.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 5,000 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 3,728,100 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,056,420 | 0.2% |
|          hit | 657,473,720 | 99.4% |
|         miss | 2,931,640 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 58,140 | 98.8% |
| Failure | 720 | 1.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 380 | 52.8% |
| mutable class | 320 | 44.4% |
| metaclass attribute | 20 | 2.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,220 | 0.0% |
|          hit | 63,363,480 | 100.0% |
|         miss | 2,120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,300 | 100.0% |
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
|     deferred | 440 | 0.0% |
|          hit | 128,140,500 | 100.0% |
|         miss | 2,900 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,200,000 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 1,520 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 1,520 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,040,180 | 7.5% |
|          hit | 24,991,020 | 92.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 12.8% |
| Failure | 680 | 87.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float | 680 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 2,075,440 | 100.0% |

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
| Basic | 1,524,827,100 | 45.2% |
| Not specialized | 157,789,660 | 4.7% |
| Specialized hits | 1,633,608,340 | 48.5% |
| Specialized misses | 55,366,520 | 1.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 70,784,940 | 71.7% |
| COMPARE_OP | 16,455,440 | 16.7% |
| CALL | 5,173,520 | 5.2% |
| STORE_SUBSCR | 3,200,000 | 3.2% |
| TO_BOOL | 2,040,180 | 2.1% |
| LOAD_ATTR | 1,056,420 | 1.1% |
| LOAD_GLOBAL | 1,220 | 0.0% |
| STORE_ATTR | 440 | 0.0% |
| FOR_ITER | 200 | 0.0% |
| BINARY_SUBSCR | 160 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 20,189,880 | 36.5% |
| BINARY_OP_MULTIPLY_INT | 11,484,580 | 20.7% |
| BINARY_OP_MULTIPLY_FLOAT | 9,253,780 | 16.7% |
| BINARY_OP_ADD_FLOAT | 8,097,820 | 14.6% |
| CALL_PY_EXACT_ARGS | 2,933,160 | 5.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,174,640 | 3.9% |
| LOAD_ATTR_INSTANCE_VALUE | 757,000 | 1.4% |
| BINARY_OP_SUBTRACT_INT | 468,520 | 0.8% |
| STORE_ATTR_INSTANCE_VALUE | 2,900 | 0.0% |
| BINARY_OP_ADD_INT | 2,120 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 25,483,520 | 11.5% |
| Calls to Python functions inlined | 196,126,780 | 88.5% |
| Calls via PyEval_EvalFrame (total) | 25,483,520 | 11.5% |
| Calls via PyEval_EvalFrame (vector) | 25,483,520 | 11.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 25,483,520 | 11.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 24,682,480 | 11.1% |
| Calls via PyEval_EvalFrame (function ex) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 245,518,220 | 110.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 307,926,220 | 73.1% |
| Frees to freelist | 307,928,820 |  |
| Allocations | 113,548,320 | 26.9% |
| Allocations to 512 bytes | 113,548,080 | 26.9% |
| Allocations to 4 kbytes | 80 | 0.0% |
| Allocations over 4 kbytes | 160 | 0.0% |
| Frees | 115,186,445 |  |
| New values | 1,040 |  |
| Interpreter increfs | 2,364,500,600 | 96.3% |
| Interpreter decrefs | 2,576,431,960 | 91.0% |
| Increfs | 91,127,496 | 3.7% |
| Decrefs | 254,550,128 | 9.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,358,580 |  |
| Method cache misses | 1,160 |  |
| Method cache collisions | 845 |  |
| Method cache dunder hits | 24,683,893 |  |
| Method cache dunder misses | 227 |  |


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
| Optimization attempts | 300 |  |
| Traces created | 300 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 22,179,000 |  |
| Uops executed | 641,549,680 | 28.93 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 13.3% |
| <= 32 | 180 | 60.0% |
| <= 64 | 40 | 13.3% |
| <= 128 | 40 | 13.3% |


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
| <= 16 | 40 | 13.3% |
| <= 32 | 180 | 60.0% |
| <= 64 | 80 | 26.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 4,114,620 | 18.6% |
| <= 16 | 3,299,040 | 14.9% |
| <= 32 | 5,772,400 | 26.0% |
| <= 64 | 7,797,740 | 35.2% |
| <= 128 | 1,195,200 | 5.4% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 135,301,220 | 21.1% | 21.1% |  |
| LOAD_FAST | 85,021,840 | 13.3% | 34.3% |  |
| STORE_FAST | 49,022,260 | 7.6% | 42.0% |  |
| _GUARD_TYPE_VERSION | 31,860,820 | 5.0% | 46.9% | 6.4% |
| _POP_JUMP_IF_TRUE | 29,841,540 | 4.7% | 51.6% |  |
| _ITER_CHECK_LIST | 28,226,740 | 4.4% | 56.0% |  |
| _IS_ITER_EXHAUSTED_LIST | 28,226,740 | 4.4% | 60.4% |  |
| _ITER_NEXT_LIST | 24,120,320 | 3.8% | 64.2% |  |
| _EXIT_TRACE | 20,139,040 | 3.1% | 67.3% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 15,887,380 | 2.5% | 69.8% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 15,887,380 | 2.5% | 72.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 14,747,780 | 2.3% | 74.6% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 13,933,480 | 2.2% | 76.7% |  |
| _GUARD_KEYS_VERSION | 13,933,480 | 2.2% | 78.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 13,933,480 | 2.2% | 81.1% |  |
| LOAD_CONST | 10,946,600 | 1.7% | 82.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 8,547,560 | 1.3% | 84.1% |  |
| _IS_NONE | 8,547,560 | 1.3% | 85.4% |  |
| _POP_JUMP_IF_FALSE | 8,547,560 | 1.3% | 86.8% |  |
| RESUME_CHECK | 7,753,220 | 1.2% | 88.0% |  |
| _CHECK_PEP_523 | 7,753,220 | 1.2% | 89.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 7,753,220 | 1.2% | 90.4% |  |
| _CHECK_STACK_SPACE | 7,753,220 | 1.2% | 91.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 7,753,220 | 1.2% | 92.8% |  |
| _PUSH_FRAME | 7,753,220 | 1.2% | 94.0% |  |
| _SAVE_RETURN_OFFSET | 7,753,220 | 1.2% | 95.2% |  |
| _JUMP_TO_TOP | 7,228,680 | 1.1% | 96.4% |  |
| _GUARD_GLOBALS_VERSION | 5,388,700 | 0.8% | 97.2% |  |
| _LOAD_GLOBAL_MODULE | 5,381,100 | 0.8% | 98.0% |  |
| POP_TOP | 4,114,620 | 0.6% | 98.7% |  |
| _ITER_CHECK_RANGE | 1,614,800 | 0.3% | 98.9% |  |
| _IS_ITER_EXHAUSTED_RANGE | 1,614,800 | 0.3% | 99.2% |  |
| _ITER_NEXT_RANGE | 1,606,600 | 0.3% | 99.4% |  |
| _GUARD_BOTH_INT | 1,599,200 | 0.2% | 99.7% |  |
| _BINARY_OP_MULTIPLY_INT | 799,600 | 0.1% | 99.8% |  |
| _BINARY_OP_ADD_INT | 799,600 | 0.1% | 99.9% |  |
| GET_ITER | 433,860 | 0.1% | 100.0% |  |
| CALL_BUILTIN_CLASS | 7,600 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 7,600 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 7,600 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_OP | 200 |
| STORE_SUBSCR | 20 |


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
