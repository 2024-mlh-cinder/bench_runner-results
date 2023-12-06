
# Pystats results

- benchmark: regex_compile
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 2dde229
- commit date: 2023-10-19T19:17:27-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 217,911,780 | 19.1% | 19.1% |  |
| STORE_FAST | 83,241,120 | 7.3% | 26.5% |  |
| LOAD_CONST | 69,359,520 | 6.1% | 32.5% |  |
| POP_JUMP_IF_FALSE | 61,610,400 | 5.4% | 38.0% |  |
| LOAD_GLOBAL_MODULE | 54,009,640 | 4.7% | 42.7% |  |
| LOAD_FAST_LOAD_FAST | 45,242,940 | 4.0% | 46.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 37,813,020 | 3.3% | 50.0% |  |
| JUMP_BACKWARD | 36,629,460 | 3.2% | 53.2% |  |
| LOAD_GLOBAL_BUILTIN | 32,364,840 | 2.8% | 56.1% |  |
| RESUME_CHECK | 30,790,080 | 2.7% | 58.8% |  |
| PUSH_NULL | 26,351,400 | 2.3% | 61.1% |  |
| POP_TOP | 26,025,720 | 2.3% | 63.4% |  |
| FOR_ITER_RANGE | 24,414,120 | 2.1% | 65.5% |  |
| EXTENDED_ARG | 22,609,020 | 2.0% | 67.5% |  |
| STORE_SUBSCR | 21,222,860 | 1.9% | 69.4% |  |
| RETURN_VALUE | 18,507,960 | 1.6% | 71.0% |  |
| IS_OP | 16,316,700 | 1.4% | 72.4% |  |
| CONTAINS_OP | 15,563,760 | 1.4% | 73.8% |  |
| CALL_BUILTIN_O | 14,899,860 | 1.3% | 75.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,304,840 | 1.3% | 76.3% |  |
| TO_BOOL_BOOL | 12,213,660 | 1.1% | 77.4% |  |
| RETURN_CONST | 11,802,300 | 1.0% | 78.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,790,600 | 1.0% | 79.5% |  |
| CALL_PY_EXACT_ARGS | 11,635,980 | 1.0% | 80.5% |  |
| BINARY_OP_ADD_INT | 10,721,340 | 0.9% | 81.5% |  |
| TO_BOOL_INT | 10,572,780 | 0.9% | 82.4% |  |
| POP_JUMP_IF_TRUE | 10,349,460 | 0.9% | 83.3% |  |
| STORE_FAST_STORE_FAST | 10,335,660 | 0.9% | 84.2% |  |
| COMPARE_OP_STR | 9,913,560 | 0.9% | 85.1% | 1.3% |
| FOR_ITER_LIST | 9,612,780 | 0.8% | 85.9% | 2.1% |
| CALL_LEN | 9,511,320 | 0.8% | 86.8% |  |
| CALL_ISINSTANCE | 8,664,600 | 0.8% | 87.5% |  |
| BINARY_OP | 8,168,300 | 0.7% | 88.2% |  |
| BINARY_SUBSCR_LIST_INT | 8,041,500 | 0.7% | 88.9% | 11.9% |
| NOP | 7,834,680 | 0.7% | 89.6% |  |
| BINARY_SUBSCR_STR_INT | 7,058,360 | 0.6% | 90.2% | 2.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,923,340 | 0.6% | 90.9% |  |
| JUMP_FORWARD | 6,620,520 | 0.6% | 91.4% |  |
| BUILD_TUPLE | 6,233,280 | 0.5% | 92.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,098,940 | 0.5% | 92.5% |  |
| INTERPRETER_EXIT | 5,993,460 | 0.5% | 93.0% |  |
| LOAD_ATTR | 5,948,400 | 0.5% | 93.6% |  |
| POP_JUMP_IF_NOT_NONE | 5,820,540 | 0.5% | 94.1% |  |
| CALL | 5,336,480 | 0.5% | 94.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,051,820 | 0.4% | 95.0% |  |
| GET_ITER | 4,488,420 | 0.4% | 95.4% |  |
| BINARY_SUBSCR_GETITEM | 3,966,540 | 0.3% | 95.7% |  |
| FOR_ITER | 3,580,080 | 0.3% | 96.0% |  |
| BINARY_OP_SUBTRACT_INT | 3,401,760 | 0.3% | 96.3% |  |
| CALL_LIST_APPEND | 3,189,300 | 0.3% | 96.6% |  |
| BUILD_LIST | 3,045,960 | 0.3% | 96.9% |  |
| COPY | 2,907,180 | 0.3% | 97.2% |  |
| COMPARE_OP_INT | 2,253,480 | 0.2% | 97.3% |  |
| STORE_SUBSCR_LIST_INT | 2,073,600 | 0.2% | 97.5% |  |
| TO_BOOL_NONE | 1,964,920 | 0.2% | 97.7% | 5.4% |
| POP_JUMP_IF_NONE | 1,873,200 | 0.2% | 97.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,870,680 | 0.2% | 98.0% |  |
| TO_BOOL | 1,743,280 | 0.2% | 98.2% |  |
| UNARY_NOT | 1,678,260 | 0.1% | 98.3% |  |
| TO_BOOL_LIST | 1,461,960 | 0.1% | 98.5% | 0.9% |
| LOAD_ATTR_MODULE | 1,346,020 | 0.1% | 98.6% |  |
| BINARY_SUBSCR | 1,177,680 | 0.1% | 98.7% |  |
| CALL_BUILTIN_CLASS | 1,103,820 | 0.1% | 98.8% |  |
| STORE_FAST_LOAD_FAST | 1,084,320 | 0.1% | 98.9% |  |
| BINARY_SUBSCR_DICT | 1,004,220 | 0.1% | 99.0% |  |
| BUILD_SLICE | 955,860 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 937,140 | 0.1% | 99.1% |  |
| COMPARE_OP | 743,500 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 680,220 | 0.1% | 99.3% |  |
| BINARY_SLICE | 639,960 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 630,600 | 0.1% | 99.4% |  |
| TO_BOOL_STR | 599,700 | 0.1% | 99.4% | 1.0% |
| LOAD_ATTR_PROPERTY | 531,360 | 0.0% | 99.5% |  |
| EXIT_INIT_CHECK | 459,780 | 0.0% | 99.5% |  |
| CALL_ALLOC_AND_ENTER_INIT | 459,780 | 0.0% | 99.5% |  |
| UNPACK_SEQUENCE_TUPLE | 449,040 | 0.0% | 99.6% |  |
| PUSH_EXC_INFO | 424,860 | 0.0% | 99.6% |  |
| POP_EXCEPT | 424,860 | 0.0% | 99.7% |  |
| CHECK_EXC_MATCH | 424,860 | 0.0% | 99.7% |  |
| CALL_PY_WITH_DEFAULTS | 339,900 | 0.0% | 99.7% |  |
| STORE_SUBSCR_DICT | 338,520 | 0.0% | 99.8% |  |
| BUILD_MAP | 336,660 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 335,880 | 0.0% | 99.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 335,880 | 0.0% | 99.8% |  |
| BINARY_OP_MULTIPLY_INT | 333,780 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 220,260 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 219,720 | 0.0% | 99.9% |  |
| LIST_APPEND | 211,680 | 0.0% | 99.9% |  |
| CALL_TUPLE_1 | 167,940 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 167,940 | 0.0% | 100.0% |  |
| UNARY_INVERT | 122,100 | 0.0% | 100.0% |  |
| SWAP | 80,400 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 59,880 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 39,320 | 0.0% | 100.0% | 100.0% |
| STORE_SLICE | 34,680 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 25,380 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 24,600 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 24,600 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 15,420 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 4,080 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 52,945,140 | 4.7% | 4.7% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 34,708,740 | 3.0% | 7.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 33,436,020 | 2.9% | 10.6% |
| STORE_FAST LOAD_FAST | 32,225,880 | 2.8% | 13.5% |
| LOAD_FAST LOAD_CONST | 25,871,040 | 2.3% | 15.7% |
| STORE_FAST LOAD_CONST | 24,941,280 | 2.2% | 17.9% |
| LOAD_FAST PUSH_NULL | 24,082,740 | 2.1% | 20.0% |
| FOR_ITER_RANGE STORE_FAST | 23,351,520 | 2.1% | 22.1% |
| JUMP_BACKWARD FOR_ITER_RANGE | 23,351,220 | 2.1% | 24.1% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 20,920,380 | 1.8% | 26.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR | 20,736,180 | 1.8% | 27.8% |
| STORE_SUBSCR JUMP_BACKWARD | 20,318,040 | 1.8% | 29.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 17,396,580 | 1.5% | 31.1% |
| LOAD_GLOBAL_MODULE IS_OP | 15,968,400 | 1.4% | 32.5% |
| POP_TOP LOAD_FAST | 14,719,980 | 1.3% | 33.8% |
| RESUME_CHECK LOAD_FAST | 13,547,040 | 1.2% | 35.0% |
| IS_OP POP_JUMP_IF_FALSE | 13,508,100 | 1.2% | 36.2% |
| PUSH_NULL LOAD_FAST | 13,143,960 | 1.2% | 37.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 12,256,320 | 1.1% | 38.4% |
| CALL_BUILTIN_O POP_TOP | 12,085,140 | 1.1% | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 12,034,020 | 1.1% | 40.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 11,635,980 | 1.0% | 41.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 11,334,220 | 1.0% | 42.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 10,831,080 | 1.0% | 43.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 10,260,780 | 0.9% | 44.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 10,146,660 | 0.9% | 45.3% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 9,327,300 | 0.8% | 46.1% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 9,023,400 | 0.8% | 46.9% |
| LOAD_CONST COMPARE_OP_STR | 8,463,900 | 0.7% | 47.7% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 8,367,960 | 0.7% | 48.4% |
| LOAD_FAST CALL_BUILTIN_O | 8,357,460 | 0.7% | 49.1% |
| RETURN_CONST POP_TOP | 8,323,920 | 0.7% | 49.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 8,160,780 | 0.7% | 50.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 7,984,380 | 0.7% | 51.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 7,480,560 | 0.7% | 51.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,459,560 | 0.7% | 52.6% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 7,021,140 | 0.6% | 53.2% |
| CACHE RESUME_CHECK | 6,933,060 | 0.6% | 53.8% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 6,923,340 | 0.6% | 54.4% |
| LOAD_GLOBAL_MODULE BINARY_OP | 6,694,860 | 0.6% | 55.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,670,740 | 0.6% | 55.6% |
| NOP LOAD_FAST | 6,498,300 | 0.6% | 56.2% |
| EXTENDED_ARG JUMP_BACKWARD | 6,451,980 | 0.6% | 56.7% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 6,317,400 | 0.6% | 57.3% |
| JUMP_BACKWARD EXTENDED_ARG | 6,219,360 | 0.5% | 57.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 5,954,340 | 0.5% | 58.4% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,876,700 | 0.5% | 58.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 5,820,540 | 0.5% | 59.4% |
| LOAD_FAST CALL_LEN | 5,806,680 | 0.5% | 59.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,695,620 | 0.5% | 60.4% |
| LOAD_FAST LOAD_ATTR | 5,651,820 | 0.5% | 60.9% |
| STORE_FAST NOP | 5,631,840 | 0.5% | 61.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 5,619,120 | 0.5% | 61.9% |
| LOAD_FAST LOAD_FAST | 5,547,540 | 0.5% | 62.4% |
| BINARY_OP TO_BOOL_INT | 5,527,980 | 0.5% | 62.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 5,520,660 | 0.5% | 63.3% |
| BINARY_OP_ADD_INT STORE_FAST | 5,520,660 | 0.5% | 63.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 5,503,540 | 0.5% | 64.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 5,466,900 | 0.5% | 64.8% |
| EXTENDED_ARG FOR_ITER_LIST | 5,283,000 | 0.5% | 65.3% |
| LOAD_ATTR STORE_FAST | 5,146,440 | 0.5% | 65.7% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 5,092,500 | 0.4% | 66.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,049,240 | 0.4% | 66.6% |
| LOAD_FAST RETURN_VALUE | 4,980,720 | 0.4% | 67.0% |
| LOAD_CONST STORE_FAST | 4,977,000 | 0.4% | 67.5% |
| RETURN_VALUE INTERPRETER_EXIT | 4,833,240 | 0.4% | 67.9% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 4,822,920 | 0.4% | 68.3% |
| LOAD_GLOBAL_MODULE STORE_FAST | 4,773,120 | 0.4% | 68.7% |
| LOAD_FAST TO_BOOL_INT | 4,770,480 | 0.4% | 69.2% |
| BINARY_OP_ADD_INT LOAD_FAST | 4,681,680 | 0.4% | 69.6% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 4,577,460 | 0.4% | 70.0% |
| LOAD_FAST BINARY_SUBSCR_STR_INT | 4,135,500 | 0.4% | 70.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 4,086,300 | 0.4% | 70.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 3,984,480 | 0.3% | 71.0% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 3,966,540 | 0.3% | 71.4% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 3,960,780 | 0.3% | 71.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,933,360 | 0.3% | 72.1% |
| BINARY_SUBSCR_STR_INT STORE_FAST | 3,750,420 | 0.3% | 72.4% |
| EXTENDED_ARG JUMP_FORWARD | 3,700,020 | 0.3% | 72.7% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 3,687,180 | 0.3% | 73.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 3,627,480 | 0.3% | 73.4% |
| STORE_FAST STORE_FAST | 3,581,760 | 0.3% | 73.7% |
| POP_TOP JUMP_BACKWARD | 3,577,200 | 0.3% | 74.0% |
| LOAD_CONST CONTAINS_OP | 3,533,760 | 0.3% | 74.3% |
| JUMP_BACKWARD FOR_ITER_LIST | 3,519,900 | 0.3% | 74.6% |
| JUMP_BACKWARD LOAD_FAST | 3,505,380 | 0.3% | 74.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,490,500 | 0.3% | 75.2% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 3,462,360 | 0.3% | 75.5% |
| JUMP_FORWARD EXTENDED_ARG | 3,381,480 | 0.3% | 75.8% |
| EXTENDED_ARG FOR_ITER | 3,213,240 | 0.3% | 76.1% |
| PUSH_NULL LOAD_CONST | 3,181,020 | 0.3% | 76.4% |
| CONTAINS_OP EXTENDED_ARG | 3,178,680 | 0.3% | 76.7% |
| RETURN_VALUE POP_TOP | 2,997,000 | 0.3% | 76.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 2,973,120 | 0.3% | 77.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 2,951,340 | 0.3% | 77.5% |
| FOR_ITER_LIST STORE_FAST | 2,941,680 | 0.3% | 77.7% |
| LOAD_GLOBAL_BUILTIN STORE_FAST | 2,936,160 | 0.3% | 78.0% |
| LOAD_CONST BINARY_SUBSCR_STR_INT | 2,919,600 | 0.3% | 78.2% |
| PUSH_NULL CALL_BOUND_METHOD_EXACT_ARGS | 2,903,160 | 0.3% | 78.5% |
| BINARY_SUBSCR_STR_INT LOAD_CONST | 2,816,820 | 0.2% | 78.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 228,600 | 35.7% |
| LOAD_FAST | 211,680 | 33.1% |
| BINARY_OP_ADD_INT | 199,680 | 31.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 427,320 | 66.8% |
| LOAD_CONST | 212,460 | 33.2% |
| CALL | 180 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 33,900 | 97.8% |
| LOAD_CONST | 780 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 33,900 | 97.8% |
| LOAD_FAST | 780 | 2.2% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,933,060 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 217,140 | 98.8% |
| LOAD_FAST_LOAD_FAST | 1,560 | 0.7% |
| RETURN_VALUE | 1,020 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 218,940 | 99.6% |
| LOAD_GLOBAL_BUILTIN | 780 | 0.4% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 955,860 | 81.2% |
| LOAD_FAST | 123,900 | 10.5% |
| LOAD_CONST | 97,560 | 8.3% |
| BINARY_SUBSCR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 931,260 | 79.1% |
| CALL_ALLOC_AND_ENTER_INIT | 123,900 | 10.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 97,560 | 8.3% |
| STORE_FAST | 24,600 | 2.1% |
| BINARY_SUBSCR | 360 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 424,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 424,860 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040 | 50.0% |
| LOAD_CONST | 2,040 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,040 | 50.0% |
| JUMP_BACKWARD | 2,040 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 459,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 459,780 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,667,280 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,431,120 | 31.9% |
| BINARY_SUBSCR | 931,260 | 20.7% |
| BINARY_SUBSCR_TUPLE_INT | 177,780 | 4.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 167,940 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 2,276,880 | 50.7% |
| FOR_ITER_RANGE | 1,038,300 | 23.1% |
| FOR_ITER_LIST | 806,100 | 18.0% |
| FOR_ITER | 336,840 | 7.5% |
| LOAD_FAST_AND_CLEAR | 24,600 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,833,240 | 80.6% |
| RETURN_CONST | 1,160,220 | 19.4% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,631,840 | 71.9% |
| NOP | 717,420 | 9.2% |
| STORE_FAST_STORE_FAST | 716,640 | 9.1% |
| POP_JUMP_IF_FALSE | 604,260 | 7.7% |
| RESUME_CHECK | 86,940 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,498,300 | 82.9% |
| NOP | 717,420 | 9.2% |
| LOAD_GLOBAL_MODULE | 262,740 | 3.4% |
| LOAD_FAST_LOAD_FAST | 217,140 | 2.8% |
| LOAD_CONST | 69,900 | 0.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 256,140 | 60.3% |
| STORE_ATTR_INSTANCE_VALUE | 167,940 | 39.5% |
| STORE_FAST | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 256,140 | 60.3% |
| RETURN_CONST | 167,940 | 39.5% |
| EXTENDED_ARG | 780 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 12,085,140 | 46.4% |
| RETURN_CONST | 8,323,920 | 32.0% |
| RETURN_VALUE | 2,997,000 | 11.5% |
| POP_JUMP_IF_FALSE | 1,414,680 | 5.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 768,420 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,719,980 | 56.6% |
| JUMP_BACKWARD | 3,577,200 | 13.7% |
| EXTENDED_ARG | 2,678,100 | 10.3% |
| LOAD_GLOBAL_MODULE | 1,946,580 | 7.5% |
| RETURN_CONST | 1,428,000 | 5.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 256,140 | 60.3% |
| BINARY_SUBSCR_STR_INT | 167,940 | 39.5% |
| STORE_SUBSCR | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 424,860 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,082,740 | 91.4% |
| LOAD_ATTR_MODULE | 1,184,200 | 4.5% |
| STORE_FAST_LOAD_FAST | 1,084,320 | 4.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,143,960 | 49.9% |
| LOAD_GLOBAL_MODULE | 5,092,500 | 19.3% |
| LOAD_CONST | 3,181,020 | 12.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,903,160 | 11.0% |
| LOAD_FAST_LOAD_FAST | 1,694,220 | 6.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,317,400 | 34.1% |
| LOAD_FAST | 4,980,720 | 26.9% |
| CALL_LEN | 2,762,460 | 14.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,198,680 | 6.5% |
| BINARY_OP_SUBTRACT_INT | 606,300 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 4,833,240 | 26.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,577,460 | 24.7% |
| POP_TOP | 2,997,000 | 16.2% |
| STORE_FAST | 2,364,000 | 12.8% |
| CALL_BUILTIN_O | 931,260 | 5.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,736,180 | 97.7% |
| BINARY_OP | 199,680 | 0.9% |
| LOAD_FAST | 157,800 | 0.7% |
| LOAD_CONST | 123,900 | 0.6% |
| STORE_SUBSCR | 5,300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,318,040 | 95.7% |
| JUMP_FORWARD | 598,140 | 2.8% |
| RETURN_CONST | 157,800 | 0.7% |
| EXTENDED_ARG | 123,900 | 0.6% |
| LOAD_FAST_LOAD_FAST | 15,900 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,401,960 | 80.4% |
| LOAD_ATTR | 167,940 | 9.6% |
| BINARY_OP | 167,940 | 9.6% |
| TO_BOOL | 3,820 | 0.2% |
| TO_BOOL_NONE | 1,620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 955,380 | 54.8% |
| POP_JUMP_IF_FALSE | 782,480 | 44.9% |
| TO_BOOL | 3,820 | 0.2% |
| TO_BOOL_NONE | 1,600 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 122,100 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 24,600 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 931,260 | 55.5% |
| TO_BOOL_LIST | 747,000 | 44.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 931,260 | 55.5% |
| CALL_PY_EXACT_ARGS | 747,000 | 44.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,694,860 | 82.0% |
| LOAD_FAST_LOAD_FAST | 548,580 | 6.7% |
| LOAD_CONST | 200,460 | 2.5% |
| LOAD_FAST | 177,200 | 2.2% |
| RETURN_VALUE | 168,720 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 5,527,980 | 67.7% |
| STORE_FAST | 1,371,900 | 16.8% |
| LOAD_FAST | 290,820 | 3.6% |
| STORE_SUBSCR | 199,680 | 2.4% |
| TO_BOOL | 167,940 | 2.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,000,380 | 32.8% |
| RESUME_CHECK | 624,960 | 20.5% |
| STORE_FAST | 498,000 | 16.3% |
| LOAD_CONST | 416,100 | 13.7% |
| POP_JUMP_IF_FALSE | 217,740 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,603,640 | 85.5% |
| LOAD_FAST | 335,880 | 11.0% |
| LOAD_GLOBAL_BUILTIN | 80,220 | 2.6% |
| SWAP | 24,600 | 0.8% |
| LOAD_GLOBAL_MODULE | 780 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 335,880 | 99.8% |
| STORE_FAST | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 335,880 | 99.8% |
| STORE_FAST | 780 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 955,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 955,860 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 2,342,880 | 37.6% |
| LOAD_FAST_LOAD_FAST | 1,315,560 | 21.1% |
| CALL | 1,074,180 | 17.2% |
| LOAD_FAST | 502,140 | 8.1% |
| BUILD_TUPLE | 371,340 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 2,403,720 | 38.6% |
| LOAD_FAST | 1,197,300 | 19.2% |
| CALL_BUILTIN_O | 605,160 | 9.7% |
| RETURN_VALUE | 423,360 | 6.8% |
| BUILD_TUPLE | 371,340 | 6.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,146,800 | 40.2% |
| LOAD_FAST_LOAD_FAST | 1,368,000 | 25.6% |
| LOAD_FAST | 1,307,720 | 24.5% |
| LOAD_CONST | 343,140 | 6.4% |
| BINARY_OP | 167,940 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,806,620 | 52.6% |
| BUILD_TUPLE | 1,074,180 | 20.1% |
| LOAD_GLOBAL_BUILTIN | 1,073,400 | 20.1% |
| LIST_APPEND | 211,680 | 4.0% |
| RETURN_VALUE | 167,940 | 3.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_INTRINSIC_1 | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 503,040 | 67.7% |
| LOAD_FAST | 133,740 | 18.0% |
| LOAD_ATTR_INSTANCE_VALUE | 101,640 | 13.7% |
| COMPARE_OP | 2,740 | 0.4% |
| COMPARE_OP_STR | 2,340 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 582,900 | 78.4% |
| POP_JUMP_IF_TRUE | 155,520 | 20.9% |
| COMPARE_OP | 2,740 | 0.4% |
| COMPARE_OP_STR | 2,340 | 0.3% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,367,960 | 53.8% |
| LOAD_CONST | 3,533,760 | 22.7% |
| LOAD_FAST_LOAD_FAST | 3,462,360 | 22.2% |
| LOAD_FAST | 199,680 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,256,320 | 78.7% |
| EXTENDED_ARG | 3,178,680 | 20.4% |
| RETURN_VALUE | 106,260 | 0.7% |
| POP_JUMP_IF_TRUE | 22,500 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,073,640 | 36.9% |
| UNARY_NOT | 931,260 | 32.0% |
| LOAD_ATTR_INSTANCE_VALUE | 606,300 | 20.9% |
| LOAD_FAST | 146,400 | 5.0% |
| BINARY_OP | 137,160 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,073,400 | 36.9% |
| TO_BOOL_BOOL | 943,680 | 32.5% |
| TO_BOOL_STR | 599,100 | 20.6% |
| TO_BOOL_INT | 274,320 | 9.4% |
| TO_BOOL_NONE | 7,200 | 0.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,219,360 | 27.5% |
| JUMP_FORWARD | 3,381,480 | 15.0% |
| CONTAINS_OP | 3,178,680 | 14.1% |
| POP_TOP | 2,678,100 | 11.8% |
| STORE_FAST | 2,590,200 | 11.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,451,980 | 28.5% |
| FOR_ITER_LIST | 5,283,000 | 23.4% |
| POP_JUMP_IF_FALSE | 3,960,780 | 17.5% |
| JUMP_FORWARD | 3,700,020 | 16.4% |
| FOR_ITER | 3,213,240 | 14.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,213,240 | 89.8% |
| GET_ITER | 336,840 | 9.4% |
| JUMP_BACKWARD | 15,480 | 0.4% |
| FOR_ITER | 10,740 | 0.3% |
| FOR_ITER_LIST | 3,780 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,287,440 | 63.9% |
| RETURN_CONST | 925,800 | 25.9% |
| LOAD_GLOBAL_MODULE | 167,940 | 4.7% |
| LOAD_FAST | 167,940 | 4.7% |
| STORE_FAST | 15,900 | 0.4% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,968,400 | 97.9% |
| LOAD_GLOBAL_BUILTIN | 167,940 | 1.0% |
| LOAD_FAST | 167,940 | 1.0% |
| LOAD_CONST | 12,420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,508,100 | 82.8% |
| POP_JUMP_IF_TRUE | 2,796,180 | 17.1% |
| COPY | 12,240 | 0.1% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 20,318,040 | 55.5% |
| EXTENDED_ARG | 6,451,980 | 17.6% |
| POP_TOP | 3,577,200 | 9.8% |
| POP_JUMP_IF_TRUE | 2,618,460 | 7.1% |
| STORE_FAST | 1,619,700 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 23,351,220 | 63.7% |
| EXTENDED_ARG | 6,219,360 | 17.0% |
| FOR_ITER_LIST | 3,519,900 | 9.6% |
| LOAD_FAST | 3,505,380 | 9.6% |
| FOR_ITER | 15,480 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,700,020 | 55.9% |
| POP_TOP | 820,740 | 12.4% |
| STORE_FAST | 713,940 | 10.8% |
| STORE_SUBSCR | 598,140 | 9.0% |
| POP_JUMP_IF_TRUE | 305,340 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,381,480 | 51.1% |
| LOAD_GLOBAL_BUILTIN | 1,572,960 | 23.8% |
| LOAD_FAST | 1,156,320 | 17.5% |
| LOAD_GLOBAL_MODULE | 288,180 | 4.4% |
| LOAD_FAST_LOAD_FAST | 152,460 | 2.3% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 211,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 211,680 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,651,820 | 95.0% |
| LOAD_GLOBAL_MODULE | 256,200 | 4.3% |
| LOAD_GLOBAL_BUILTIN | 38,580 | 0.6% |
| LOAD_ATTR | 1,780 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,146,440 | 86.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 256,140 | 4.3% |
| LOAD_FAST | 206,520 | 3.5% |
| TO_BOOL | 167,940 | 2.8% |
| LOAD_FAST_LOAD_FAST | 167,940 | 2.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,871,040 | 37.3% |
| STORE_FAST | 24,941,280 | 36.0% |
| PUSH_NULL | 3,181,020 | 4.6% |
| BINARY_SUBSCR_STR_INT | 2,816,820 | 4.1% |
| LOAD_CONST | 2,144,220 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,920,380 | 30.2% |
| BINARY_OP_ADD_INT | 10,260,780 | 14.8% |
| COMPARE_OP_STR | 8,463,900 | 12.2% |
| STORE_FAST | 4,977,000 | 7.2% |
| CONTAINS_OP | 3,533,760 | 5.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 66.7% |
| LIST_EXTEND | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 52,945,140 | 24.3% |
| STORE_FAST | 32,225,880 | 14.8% |
| LOAD_GLOBAL_BUILTIN | 17,396,580 | 8.0% |
| POP_TOP | 14,719,980 | 6.8% |
| RESUME_CHECK | 13,547,040 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 34,708,740 | 15.9% |
| LOAD_GLOBAL_MODULE | 33,436,020 | 15.3% |
| LOAD_CONST | 25,871,040 | 11.9% |
| PUSH_NULL | 24,082,740 | 11.1% |
| CALL_BUILTIN_O | 8,357,460 | 3.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 24,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 24,600 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 59,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,880 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,920,380 | 46.2% |
| STORE_ATTR_INSTANCE_VALUE | 4,086,300 | 9.0% |
| LOAD_GLOBAL_MODULE | 3,627,480 | 8.0% |
| STORE_FAST_STORE_FAST | 2,973,120 | 6.6% |
| RESUME_CHECK | 2,951,340 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 20,736,180 | 45.8% |
| STORE_ATTR_INSTANCE_VALUE | 6,670,740 | 14.7% |
| CONTAINS_OP | 3,462,360 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,257,800 | 5.0% |
| LOAD_FAST | 2,137,020 | 4.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 40.0% |
| STORE_FAST | 20 | 20.0% |
| RESUME_CHECK | 20 | 20.0% |
| FOR_ITER_RANGE | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 20.0% |
| LOAD_ATTR | 20 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 13,508,100 | 21.9% |
| CONTAINS_OP | 12,256,320 | 19.9% |
| TO_BOOL_BOOL | 10,146,660 | 16.5% |
| COMPARE_OP_STR | 9,327,300 | 15.1% |
| TO_BOOL_INT | 5,954,340 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,945,140 | 85.9% |
| LOAD_GLOBAL_MODULE | 1,897,020 | 3.1% |
| POP_TOP | 1,414,680 | 2.3% |
| LOAD_CONST | 1,009,560 | 1.6% |
| LOAD_FAST_LOAD_FAST | 805,200 | 1.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,366,800 | 73.0% |
| LOAD_FAST | 506,400 | 27.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,073,400 | 57.3% |
| LOAD_FAST | 667,080 | 35.6% |
| JUMP_BACKWARD | 85,320 | 4.6% |
| LOAD_GLOBAL_BUILTIN | 47,220 | 2.5% |
| RETURN_CONST | 180 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,820,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,984,480 | 68.5% |
| BUILD_LIST | 1,000,380 | 17.2% |
| LOAD_GLOBAL_BUILTIN | 316,020 | 5.4% |
| LOAD_GLOBAL_MODULE | 167,940 | 2.9% |
| EXTENDED_ARG | 167,940 | 2.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,687,180 | 35.6% |
| IS_OP | 2,796,180 | 27.0% |
| TO_BOOL_BOOL | 1,868,820 | 18.1% |
| TO_BOOL | 955,380 | 9.2% |
| TO_BOOL_STR | 599,100 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,619,120 | 54.3% |
| JUMP_BACKWARD | 2,618,460 | 25.3% |
| CALL_LEN | 599,280 | 5.8% |
| LOAD_FAST_LOAD_FAST | 311,880 | 3.0% |
| JUMP_FORWARD | 305,340 | 3.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,049,240 | 42.8% |
| CALL_LIST_APPEND | 2,680,260 | 22.7% |
| POP_TOP | 1,428,000 | 12.1% |
| FOR_ITER | 925,800 | 7.8% |
| POP_JUMP_IF_FALSE | 740,760 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,323,920 | 70.5% |
| TO_BOOL_BOOL | 1,519,320 | 12.9% |
| INTERPRETER_EXIT | 1,160,220 | 9.8% |
| EXIT_INIT_CHECK | 459,780 | 3.9% |
| STORE_FAST | 339,060 | 2.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 23,351,520 | 28.1% |
| LOAD_ATTR_INSTANCE_VALUE | 10,831,080 | 13.0% |
| BINARY_OP_ADD_INT | 5,520,660 | 6.6% |
| LOAD_ATTR | 5,146,440 | 6.2% |
| LOAD_CONST | 4,977,000 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,225,880 | 38.7% |
| LOAD_CONST | 24,941,280 | 30.0% |
| NOP | 5,631,840 | 6.8% |
| LOAD_GLOBAL_MODULE | 5,503,540 | 6.6% |
| LOAD_GLOBAL_BUILTIN | 3,933,360 | 4.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,084,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,084,320 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 9,023,400 | 87.3% |
| COPY | 1,073,400 | 10.4% |
| UNPACK_SEQUENCE_TUPLE | 214,320 | 2.1% |
| STORE_FAST_STORE_FAST | 24,540 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,466,900 | 52.9% |
| LOAD_FAST_LOAD_FAST | 2,973,120 | 28.8% |
| NOP | 716,640 | 6.9% |
| LOAD_GLOBAL_BUILTIN | 684,000 | 6.6% |
| LOAD_GLOBAL_MODULE | 280,680 | 2.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 24,600 | 30.6% |
| FOR_ITER_RANGE | 24,600 | 30.6% |
| BUILD_LIST | 24,600 | 30.6% |
| BINARY_OP | 6,600 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,600 | 30.6% |
| FOR_ITER_RANGE | 24,600 | 30.6% |
| BUILD_LIST | 24,600 | 30.6% |
| STORE_ATTR_INSTANCE_VALUE | 6,600 | 8.2% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,260,780 | 95.7% |
| LOAD_FAST_LOAD_FAST | 322,680 | 3.0% |
| BINARY_OP_MULTIPLY_INT | 137,880 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,520,660 | 51.5% |
| LOAD_FAST | 4,681,680 | 43.7% |
| BINARY_SLICE | 199,680 | 1.9% |
| CALL_PY_EXACT_ARGS | 137,400 | 1.3% |
| CALL_BUILTIN_O | 97,560 | 0.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 195,120 | 58.5% |
| BINARY_SUBSCR_TUPLE_INT | 137,880 | 41.3% |
| LOAD_ATTR | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 137,880 | 41.3% |
| LOAD_CONST | 97,560 | 29.2% |
| CALL_BUILTIN_O | 97,560 | 29.2% |
| LOAD_GLOBAL_BUILTIN | 780 | 0.2% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,018,520 | 59.3% |
| LOAD_CONST | 776,940 | 22.8% |
| CALL_LEN | 606,300 | 17.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,084,320 | 31.9% |
| LOAD_FAST | 1,063,620 | 31.3% |
| RETURN_VALUE | 606,300 | 17.8% |
| LOAD_CONST | 233,640 | 6.9% |
| BINARY_SUBSCR_LIST_INT | 211,980 | 6.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,540 | 59.8% |
| BUILD_TUPLE | 256,140 | 25.5% |
| LOAD_FAST_LOAD_FAST | 147,540 | 14.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 256,140 | 25.5% |
| CALL_BUILTIN_O | 228,960 | 22.8% |
| LOAD_FAST | 197,040 | 19.6% |
| RETURN_VALUE | 167,940 | 16.7% |
| LOAD_CONST | 141,840 | 14.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,610,360 | 65.8% |
| LOAD_CONST | 1,356,180 | 34.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,966,540 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,021,140 | 87.3% |
| LOAD_FAST_LOAD_FAST | 423,960 | 5.3% |
| LOAD_CONST | 366,360 | 4.6% |
| BINARY_OP_SUBTRACT_INT | 211,980 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 18,060 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,317,400 | 89.0% |
| STORE_FAST | 217,200 | 3.1% |
| LOAD_FAST_LOAD_FAST | 211,980 | 3.0% |
| COMPARE_OP_INT | 211,980 | 3.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 89,040 | 1.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,135,500 | 58.6% |
| LOAD_CONST | 2,919,600 | 41.4% |
| BINARY_SUBSCR_STR_INT | 3,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,750,420 | 53.1% |
| LOAD_CONST | 2,816,820 | 39.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 217,140 | 3.1% |
| PUSH_EXC_INFO | 167,940 | 2.4% |
| CALL_BUILTIN_O | 102,780 | 1.5% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,870,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 604,440 | 32.3% |
| CALL_BUILTIN_O | 438,960 | 23.5% |
| GET_ITER | 177,780 | 9.5% |
| LOAD_FAST | 150,300 | 8.0% |
| BINARY_OP_MULTIPLY_INT | 137,880 | 7.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 167,940 | 36.5% |
| LOAD_FAST | 167,940 | 36.5% |
| BINARY_SUBSCR | 123,900 | 26.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 459,780 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,903,160 | 41.9% |
| BUILD_TUPLE | 2,403,720 | 34.7% |
| LOAD_CONST | 1,409,820 | 20.4% |
| LOAD_FAST | 206,400 | 3.0% |
| BINARY_SUBSCR_LIST_INT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,923,340 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,011,480 | 91.6% |
| CALL_BUILTIN_FAST | 38,580 | 3.5% |
| BINARY_OP_ADD_INT | 26,160 | 2.4% |
| UNARY_NEGATIVE | 24,600 | 2.2% |
| LOAD_FAST_LOAD_FAST | 1,380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 931,260 | 84.4% |
| GET_ITER | 107,340 | 9.7% |
| RETURN_VALUE | 38,580 | 3.5% |
| STORE_FAST | 26,220 | 2.4% |
| CALL_BUILTIN_O | 420 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,580 | 98.1% |
| CALL_BUILTIN_FAST | 740 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 38,580 | 98.1% |
| CALL_BUILTIN_FAST | 740 | 1.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 167,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 167,940 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,357,460 | 56.1% |
| LOAD_CONST | 1,771,200 | 11.9% |
| LOAD_GLOBAL_MODULE | 1,504,140 | 10.1% |
| RETURN_VALUE | 931,260 | 6.3% |
| CALL_LEN | 764,220 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,085,140 | 81.1% |
| BUILD_TUPLE | 2,342,880 | 15.7% |
| TO_BOOL_BOOL | 328,320 | 2.2% |
| STORE_FAST | 143,520 | 1.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,480,560 | 86.3% |
| LOAD_GLOBAL_MODULE | 512,280 | 5.9% |
| BUILD_TUPLE | 335,880 | 3.9% |
| LOAD_ATTR_SLOT | 167,940 | 1.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 167,940 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 8,160,780 | 94.2% |
| RETURN_VALUE | 335,880 | 3.9% |
| LOAD_FAST | 167,940 | 1.9% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,806,680 | 61.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,762,460 | 29.0% |
| POP_JUMP_IF_TRUE | 599,280 | 6.3% |
| LOAD_GLOBAL_MODULE | 335,880 | 3.5% |
| LOAD_CONST | 7,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,762,460 | 29.0% |
| LOAD_FAST | 1,769,100 | 18.6% |
| STORE_FAST_LOAD_FAST | 1,084,320 | 11.4% |
| CALL_BUILTIN_CLASS | 1,011,480 | 10.6% |
| LOAD_CONST | 803,580 | 8.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,680,260 | 84.0% |
| BUILD_TUPLE | 243,540 | 7.6% |
| LOAD_GLOBAL_MODULE | 167,940 | 5.3% |
| LOAD_CONST | 97,560 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,680,260 | 84.0% |
| LOAD_FAST | 265,500 | 8.3% |
| JUMP_BACKWARD | 126,240 | 4.0% |
| EXTENDED_ARG | 90,720 | 2.8% |
| LOAD_FAST_LOAD_FAST | 24,600 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 327,120 | 51.9% |
| LOAD_CONST | 256,140 | 40.6% |
| LOAD_FAST_LOAD_FAST | 45,420 | 7.2% |
| BUILD_TUPLE | 1,920 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 628,680 | 99.7% |
| POP_TOP | 1,920 | 0.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 24,600 | 96.9% |
| LOAD_CONST | 780 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,600 | 96.9% |
| STORE_FAST | 780 | 3.1% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 681,000 | 72.7% |
| LOAD_ATTR | 256,140 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 768,420 | 82.0% |
| GET_ITER | 167,940 | 17.9% |
| RETURN_VALUE | 780 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,260 | 63.2% |
| RETURN_VALUE | 80,220 | 36.4% |
| BUILD_LIST | 780 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 220,260 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,695,620 | 48.9% |
| LOAD_FAST | 2,338,260 | 20.1% |
| LOAD_FAST_LOAD_FAST | 1,512,900 | 13.0% |
| UNARY_NOT | 747,000 | 6.4% |
| LOAD_CONST | 305,100 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,635,980 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 171,960 | 50.6% |
| LOAD_FAST_LOAD_FAST | 167,940 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 339,900 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 167,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 167,940 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 512,280 | 75.3% |
| LOAD_FAST | 167,940 | 24.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,478,880 | 65.6% |
| LOAD_GLOBAL_MODULE | 433,440 | 19.2% |
| BINARY_SUBSCR_LIST_INT | 211,980 | 9.4% |
| CALL_LEN | 106,020 | 4.7% |
| LOAD_FAST | 22,020 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,251,740 | 99.9% |
| POP_JUMP_IF_TRUE | 1,560 | 0.1% |
| COPY | 180 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,463,900 | 85.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,445,340 | 14.6% |
| COMPARE_OP | 2,340 | 0.0% |
| LOAD_FAST | 1,980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,327,300 | 94.1% |
| EXTENDED_ARG | 583,920 | 5.9% |
| COMPARE_OP | 2,340 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 5,283,000 | 55.0% |
| JUMP_BACKWARD | 3,519,900 | 36.6% |
| GET_ITER | 806,100 | 8.4% |
| FOR_ITER | 3,780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 4,822,920 | 50.2% |
| STORE_FAST | 2,941,680 | 30.6% |
| LOAD_GLOBAL_BUILTIN | 1,073,400 | 11.2% |
| LOAD_FAST | 223,500 | 2.3% |
| LOAD_FAST_LOAD_FAST | 206,160 | 2.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 23,351,220 | 95.6% |
| GET_ITER | 1,038,300 | 4.3% |
| SWAP | 24,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,351,520 | 95.6% |
| LOAD_FAST | 1,012,260 | 4.1% |
| JUMP_FORWARD | 24,900 | 0.1% |
| SWAP | 24,600 | 0.1% |
| LOAD_GLOBAL_MODULE | 820 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 9,720 | 63.0% |
| GET_ITER | 5,700 | 37.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,140 | 65.8% |
| LOAD_FAST | 4,440 | 28.8% |
| JUMP_BACKWARD | 840 | 5.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,708,740 | 91.8% |
| LOAD_FAST_LOAD_FAST | 2,257,800 | 6.0% |
| LOAD_ATTR_INSTANCE_VALUE | 839,880 | 2.2% |
| COPY | 6,600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,034,020 | 31.8% |
| STORE_FAST | 10,831,080 | 28.6% |
| LOAD_ATTR_METHOD_NO_DICT | 2,777,820 | 7.3% |
| CALL_LEN | 2,762,460 | 7.3% |
| COMPARE_OP_STR | 1,445,340 | 3.8% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,777,820 | 55.0% |
| LOAD_GLOBAL_MODULE | 1,140,960 | 22.6% |
| LOAD_FAST | 1,132,260 | 22.4% |
| CALL | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,490,500 | 69.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 681,000 | 13.5% |
| LOAD_CONST | 405,540 | 8.0% |
| LOAD_GLOBAL_MODULE | 336,660 | 6.7% |
| LOAD_FAST_LOAD_FAST | 138,120 | 2.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,876,700 | 96.4% |
| BINARY_SUBSCR_TUPLE_INT | 123,900 | 2.0% |
| BINARY_SUBSCR | 97,560 | 1.6% |
| LOAD_FAST_LOAD_FAST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,695,620 | 93.4% |
| LOAD_FAST | 196,080 | 3.2% |
| LOAD_CONST | 137,940 | 2.3% |
| LOAD_GLOBAL_MODULE | 69,120 | 1.1% |
| LOAD_FAST_LOAD_FAST | 180 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,345,960 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,184,200 | 88.0% |
| STORE_FAST | 122,040 | 9.1% |
| RETURN_VALUE | 39,000 | 2.9% |
| COMPARE_OP_INT | 780 | 0.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 167,940 | 50.0% |
| LOAD_FAST | 167,940 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 167,940 | 50.0% |
| CALL_ISINSTANCE | 167,940 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 335,880 | 63.2% |
| LOAD_FAST | 195,120 | 36.7% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 531,360 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 167,940 | 50.0% |
| LOAD_FAST | 167,940 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 167,940 | 50.0% |
| CALL_ISINSTANCE | 167,940 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,334,220 | 35.0% |
| LOAD_FAST | 7,984,380 | 24.7% |
| STORE_FAST | 3,933,360 | 12.2% |
| JUMP_FORWARD | 1,572,960 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 1,330,740 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,396,580 | 53.8% |
| CALL_ISINSTANCE | 7,480,560 | 23.1% |
| STORE_FAST | 2,936,160 | 9.1% |
| LOAD_FAST_LOAD_FAST | 1,705,260 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,330,740 | 4.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,436,020 | 61.9% |
| STORE_FAST | 5,503,540 | 10.2% |
| PUSH_NULL | 5,092,500 | 9.4% |
| RESUME_CHECK | 1,996,560 | 3.7% |
| POP_TOP | 1,946,580 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 15,968,400 | 29.6% |
| CONTAINS_OP | 8,367,960 | 15.5% |
| BINARY_OP | 6,694,860 | 12.4% |
| LOAD_FAST | 5,520,660 | 10.2% |
| STORE_FAST | 4,773,120 | 8.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 11,635,980 | 37.8% |
| CACHE | 6,933,060 | 22.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,923,340 | 22.5% |
| BINARY_SUBSCR_GETITEM | 3,966,540 | 12.9% |
| LOAD_ATTR_PROPERTY | 531,360 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,547,040 | 44.0% |
| LOAD_GLOBAL_BUILTIN | 11,334,220 | 36.8% |
| LOAD_FAST_LOAD_FAST | 2,951,340 | 9.6% |
| LOAD_GLOBAL_MODULE | 1,996,560 | 6.5% |
| BUILD_LIST | 624,960 | 2.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,459,560 | 52.1% |
| LOAD_FAST_LOAD_FAST | 6,670,740 | 46.6% |
| LOAD_ATTR_INSTANCE_VALUE | 167,940 | 1.2% |
| SWAP | 6,600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,049,240 | 35.3% |
| LOAD_FAST_LOAD_FAST | 4,086,300 | 28.6% |
| LOAD_FAST | 2,701,500 | 18.9% |
| LOAD_CONST | 1,796,040 | 12.6% |
| BUILD_MAP | 335,880 | 2.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 338,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 170,580 | 50.4% |
| LOAD_GLOBAL_BUILTIN | 167,940 | 49.6% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,292,040 | 62.3% |
| LOAD_FAST | 781,560 | 37.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,575,720 | 76.0% |
| RETURN_CONST | 264,720 | 12.8% |
| EXTENDED_ARG | 215,220 | 10.4% |
| LOAD_FAST | 17,940 | 0.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 8,160,780 | 66.8% |
| RETURN_CONST | 1,519,320 | 12.4% |
| COPY | 943,680 | 7.7% |
| LOAD_FAST | 572,580 | 4.7% |
| RETURN_VALUE | 454,560 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,146,660 | 83.1% |
| POP_JUMP_IF_TRUE | 1,868,820 | 15.3% |
| EXTENDED_ARG | 198,180 | 1.6% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 5,527,980 | 52.3% |
| LOAD_FAST | 4,770,480 | 45.1% |
| COPY | 274,320 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,954,340 | 56.3% |
| POP_JUMP_IF_TRUE | 3,687,180 | 34.9% |
| UNARY_NOT | 931,260 | 8.8% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,372,860 | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE | 88,860 | 6.1% |
| TO_BOOL_NONE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNARY_NOT | 747,000 | 51.1% |
| POP_JUMP_IF_FALSE | 458,700 | 31.4% |
| POP_JUMP_IF_TRUE | 256,020 | 17.5% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,955,760 | 99.5% |
| COPY | 7,200 | 0.4% |
| TO_BOOL | 1,600 | 0.1% |
| TO_BOOL_LIST | 240 | 0.0% |
| TO_BOOL_STR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,955,740 | 99.5% |
| POP_JUMP_IF_TRUE | 7,200 | 0.4% |
| TO_BOOL | 1,620 | 0.1% |
| TO_BOOL_LIST | 240 | 0.0% |
| TO_BOOL_STR | 120 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 599,100 | 99.9% |
| LOAD_FAST | 480 | 0.1% |
| TO_BOOL_NONE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 599,100 | 99.9% |
| POP_JUMP_IF_FALSE | 480 | 0.1% |
| TO_BOOL_NONE | 120 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,320 | 53.7% |
| RETURN_VALUE | 189,780 | 42.3% |
| BINARY_SUBSCR_TUPLE_INT | 17,940 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 234,720 | 52.3% |
| STORE_FAST_STORE_FAST | 214,320 | 47.7% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,822,920 | 40.9% |
| RETURN_VALUE | 4,577,460 | 38.8% |
| FOR_ITER | 2,287,440 | 19.4% |
| BINARY_SUBSCR_LIST_INT | 89,040 | 0.8% |
| LOAD_CONST | 13,740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 9,023,400 | 76.5% |
| STORE_FAST | 2,767,200 | 23.5% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1177320 | 5.1% |
| specialization.deopt |        21320 | 0.1% |
|          hit |     20809440 | 90.0% |
|         miss |      1131860 | 4.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 21,320 | 98.3% |
| Failure | 360 | 1.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 240 | 66.7% |
| buffer slice | 40 | 11.1% |
| list slice | 40 | 11.1% |
| out of range | 40 | 11.1% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21217560 | 89.8% |
|          hit |      2412120 | 10.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 5,300 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 5,200 | 98.1% |
| py simple | 60 | 1.1% |
| out of range | 40 | 0.8% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1737860 | 6.1% |
| specialization.deopt |         2340 | 0.0% |
|          hit |     26688580 | 93.5% |
|         miss |       124440 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,320 | 29.9% |
| Failure | 5,440 | 70.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 3,780 | 69.5% |
| other | 1,120 | 20.6% |
| mapping | 320 | 5.9% |
| dict | 180 | 3.3% |
| number | 40 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8165280 | 35.7% |
|          hit |     14676660 | 64.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.7% |
| Failure | 3,000 | 99.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,200 | 73.3% |
| or | 320 | 10.7% |
| add other | 200 | 6.7% |
| multiply different types | 120 | 4.0% |
| floor divide | 60 | 2.0% |
| add different types | 60 | 2.0% |
| and different types | 40 | 1.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5334720 | 7.4% |
| specialization.deopt |          740 | 0.0% |
|          hit |     66480720 | 92.5% |
|         miss |        39320 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 30.4% |
| Failure | 1,740 | 69.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 880 | 50.6% |
| class no vectorcall | 360 | 20.7% |
| wrong number arguments | 280 | 16.1% |
| meth descr varargs | 100 | 5.7% |
| cfunc noargs | 60 | 3.4% |
| class mutable | 40 | 2.3% |
| str | 20 | 1.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       738420 | 5.7% |
| specialization.deopt |         2340 | 0.0% |
|          hit |     12043020 | 93.3% |
|         miss |       124020 | 1.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,340 | 31.5% |
| Failure | 5,080 | 68.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 4,880 | 96.1% |
| big int | 80 | 1.6% |
| other | 80 | 1.6% |
| tuple | 40 | 0.8% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3565560 | 9.5% |
| specialization.deopt |         3780 | 0.0% |
|          hit |     33841980 | 90.0% |
|         miss |       200340 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,780 | 20.7% |
| Failure | 14,520 | 79.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| seq iter | 14,400 | 99.2% |
| map | 40 | 0.3% |
| dict items | 40 | 0.3% |
| dict keys | 40 | 0.3% |


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
| specialization.deferred |      5946560 | 10.3% |
|          hit |     51512920 | 89.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.3% |
| Failure | 1,780 | 96.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,440 | 80.9% |
| not managed dict | 140 | 7.9% |
| metaclass attribute | 120 | 6.7% |
| builtin class method | 40 | 2.2% |
| mutable class | 40 | 2.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     86374480 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>

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
|          hit |     14304840 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     12239640 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 606,708,660 | 53.3% |
| Not specialized | 166,498,360 | 14.6% |
| Specialized | 365,251,140 | 32.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_SUBSCR | 21,217,560 | 44.3% |
| BINARY_OP | 8,165,280 | 17.1% |
| LOAD_ATTR | 5,946,560 | 12.4% |
| CALL | 5,334,720 | 11.1% |
| FOR_ITER | 3,565,560 | 7.4% |
| TO_BOOL | 1,737,860 | 3.6% |
| BINARY_SUBSCR | 1,177,320 | 2.5% |
| COMPARE_OP | 738,420 | 1.5% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 957,660 | 59.1% |
| FOR_ITER_LIST | 200,340 | 12.4% |
| BINARY_SUBSCR_STR_INT | 174,200 | 10.8% |
| COMPARE_OP_STR | 124,020 | 7.7% |
| TO_BOOL_NONE | 105,540 | 6.5% |
| CALL_BUILTIN_FAST | 39,320 | 2.4% |
| TO_BOOL_LIST | 12,720 | 0.8% |
| TO_BOOL_STR | 6,180 | 0.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 6,933,060 | 22.5% |
| Calls to Python functions inlined | 23,857,020 | 77.5% |
| Calls via PyEval_EvalFrame (total) | 6,933,060 | 22.5% |
| Calls via PyEval_EvalFrame (vector) | 6,933,060 | 22.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 6,933,060 | 22.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,737,020 | 18.6% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 31,249,860 | 101.5% |
| Frame objects created | 2,304,060 | 7.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 17,063,460 | 26.5% |
| Frees to freelist | 17,063,460 |  |
| Allocations | 47,208,780 | 73.5% |
| Allocations to 512 bytes | 47,177,280 | 73.4% |
| Allocations to 4 kbytes | 29,940 | 0.0% |
| Allocations over 4 kbytes | 1,560 | 0.0% |
| Frees | 49,228,980 |  |
| New values | 1,000,380 |  |
| Interpreter increfs | 410,926,840 | 83.4% |
| Interpreter decrefs | 445,589,400 | 80.2% |
| Increfs | 82,058,565 | 16.6% |
| Decrefs | 110,249,425 | 19.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 6,154,775 |  |
| Method cache misses | 5 |  |
| Method cache collisions | 29,048 |  |
| Method cache dunder hits | 15,257,537 |  |
| Method cache dunder misses | 29,043 |  |


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
Stats gathered on: 2023-10-20
