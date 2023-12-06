
# Pystats results

- benchmark: regex_compile
- fork: python
- ref: eb3c94ea669561a0dfacaca715d4b2723bb2c6f4
- commit hash: eb3c94e
- commit date: 2023-11-17T20:58:13-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 218,515,380 | 20.3% | 20.3% |  |
| POP_JUMP_IF_FALSE | 67,542,820 | 6.3% | 26.6% |  |
| STORE_FAST | 65,549,200 | 6.1% | 32.6% |  |
| LOAD_GLOBAL_MODULE | 56,230,200 | 5.2% | 37.9% |  |
| LOAD_CONST | 52,870,660 | 4.9% | 42.8% |  |
| LOAD_GLOBAL_BUILTIN | 42,498,220 | 3.9% | 46.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 39,289,940 | 3.6% | 50.4% |  |
| RESUME_CHECK | 34,970,740 | 3.2% | 53.6% |  |
| POP_TOP | 26,714,720 | 2.5% | 56.1% |  |
| PUSH_NULL | 26,686,680 | 2.5% | 58.6% |  |
| LOAD_FAST_LOAD_FAST | 25,776,220 | 2.4% | 61.0% |  |
| EXTENDED_ARG | 25,532,500 | 2.4% | 63.3% |  |
| RETURN_VALUE | 22,455,320 | 2.1% | 65.4% |  |
| ENTER_EXECUTOR | 18,202,220 | 1.7% | 67.1% |  |
| CALL_BUILTIN_O | 17,348,680 | 1.6% | 68.7% |  |
| TO_BOOL_BOOL | 14,914,880 | 1.4% | 70.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,629,200 | 1.4% | 71.4% |  |
| CONTAINS_OP | 13,826,720 | 1.3% | 72.7% |  |
| IS_OP | 13,781,000 | 1.3% | 74.0% |  |
| RETURN_CONST | 13,171,840 | 1.2% | 75.2% |  |
| POP_JUMP_IF_TRUE | 12,061,700 | 1.1% | 76.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,297,000 | 1.0% | 77.4% |  |
| CALL_ISINSTANCE | 11,211,680 | 1.0% | 78.4% |  |
| CALL_LEN | 11,017,760 | 1.0% | 79.5% |  |
| COMPARE_OP_STR | 10,712,700 | 1.0% | 80.5% | 1.5% |
| BINARY_OP_ADD_INT | 10,351,400 | 1.0% | 81.4% |  |
| TO_BOOL_INT | 10,300,060 | 1.0% | 82.4% |  |
| CALL_PY_EXACT_ARGS | 10,272,280 | 1.0% | 83.3% |  |
| BINARY_SUBSCR_LIST_INT | 10,134,920 | 0.9% | 84.3% | 12.6% |
| BINARY_OP | 9,821,560 | 0.9% | 85.2% |  |
| STORE_FAST_STORE_FAST | 9,376,460 | 0.9% | 86.1% |  |
| JUMP_FORWARD | 8,824,920 | 0.8% | 86.9% |  |
| INTERPRETER_EXIT | 7,991,280 | 0.7% | 87.6% |  |
| BUILD_TUPLE | 7,939,000 | 0.7% | 88.4% |  |
| LOAD_ATTR | 7,589,580 | 0.7% | 89.1% |  |
| BINARY_SUBSCR_STR_INT | 6,989,320 | 0.6% | 89.7% | 3.3% |
| CALL | 6,831,700 | 0.6% | 90.3% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,721,040 | 0.6% | 91.0% |  |
| NOP | 6,082,880 | 0.6% | 91.5% |  |
| GET_ITER | 5,982,220 | 0.6% | 92.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,907,720 | 0.5% | 92.6% |  |
| BINARY_SUBSCR_GETITEM | 5,288,720 | 0.5% | 93.1% |  |
| FOR_ITER_LIST | 4,908,120 | 0.5% | 93.6% | 0.6% |
| FOR_ITER | 4,824,980 | 0.4% | 94.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,806,360 | 0.4% | 94.5% |  |
| POP_JUMP_IF_NOT_NONE | 4,265,000 | 0.4% | 94.9% |  |
| CALL_LIST_APPEND | 4,252,400 | 0.4% | 95.3% |  |
| BUILD_LIST | 4,059,800 | 0.4% | 95.6% |  |
| BINARY_OP_SUBTRACT_INT | 3,232,800 | 0.3% | 95.9% |  |
| COPY | 3,039,520 | 0.3% | 96.2% |  |
| FOR_ITER_RANGE | 2,807,500 | 0.3% | 96.5% |  |
| COMPARE_OP_INT | 2,585,940 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 2,497,600 | 0.2% | 97.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 2,454,360 | 0.2% | 97.2% |  |
| TO_BOOL_NONE | 2,382,620 | 0.2% | 97.4% | 5.3% |
| TO_BOOL_LIST | 1,926,080 | 0.2% | 97.6% | 0.9% |
| STORE_SUBSCR_LIST_INT | 1,748,420 | 0.2% | 97.7% |  |
| BINARY_SUBSCR | 1,568,180 | 0.1% | 97.9% |  |
| CALL_BUILTIN_CLASS | 1,506,460 | 0.1% | 98.0% |  |
| UNARY_NOT | 1,403,120 | 0.1% | 98.2% |  |
| TO_BOOL | 1,335,900 | 0.1% | 98.3% |  |
| BUILD_SLICE | 1,274,480 | 0.1% | 98.4% |  |
| STORE_SUBSCR | 1,233,620 | 0.1% | 98.5% |  |
| JUMP_BACKWARD | 1,189,780 | 0.1% | 98.6% |  |
| LOAD_ATTR_MODULE | 1,112,380 | 0.1% | 98.7% |  |
| COMPARE_OP | 991,620 | 0.1% | 98.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 840,800 | 0.1% | 98.9% |  |
| TO_BOOL_STR | 799,520 | 0.1% | 99.0% | 1.0% |
| BINARY_SUBSCR_DICT | 719,860 | 0.1% | 99.0% |  |
| LOAD_ATTR_PROPERTY | 708,480 | 0.1% | 99.1% |  |
| STORE_FAST_LOAD_FAST | 618,560 | 0.1% | 99.2% |  |
| EXIT_INIT_CHECK | 613,040 | 0.1% | 99.2% |  |
| CALL_ALLOC_AND_ENTER_INIT | 613,040 | 0.1% | 99.3% |  |
| CALL_TYPE_1 | 602,800 | 0.1% | 99.3% |  |
| UNPACK_SEQUENCE_TUPLE | 598,720 | 0.1% | 99.4% |  |
| CHECK_EXC_MATCH | 566,480 | 0.1% | 99.4% |  |
| POP_EXCEPT | 566,480 | 0.1% | 99.5% |  |
| PUSH_EXC_INFO | 566,480 | 0.1% | 99.5% |  |
| CALL_PY_WITH_DEFAULTS | 453,200 | 0.0% | 99.6% |  |
| STORE_SUBSCR_DICT | 449,200 | 0.0% | 99.6% |  |
| BUILD_MAP | 448,880 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 447,840 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 447,840 | 0.0% | 99.8% |  |
| BINARY_OP_MULTIPLY_INT | 445,040 | 0.0% | 99.8% |  |
| BINARY_SLICE | 338,640 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 293,680 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 292,960 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 226,100 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 223,920 | 0.0% | 99.9% |  |
| CALL_TUPLE_1 | 223,920 | 0.0% | 99.9% |  |
| UNARY_INVERT | 162,800 | 0.0% | 100.0% |  |
| SWAP | 107,200 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 79,840 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 52,420 | 0.0% | 100.0% | 100.0% |
| STORE_SLICE | 46,240 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 33,840 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 32,800 | 0.0% | 100.0% |  |
| LIST_APPEND | 32,800 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 32,800 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 14,640 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,780 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 540 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| RESUME | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 56,575,840 | 5.3% | 5.3% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 35,160,560 | 3.3% | 8.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 32,983,180 | 3.1% | 11.6% |
| STORE_FAST LOAD_FAST | 27,801,320 | 2.6% | 14.2% |
| LOAD_FAST PUSH_NULL | 25,171,240 | 2.3% | 16.5% |
| LOAD_FAST LOAD_CONST | 24,178,620 | 2.2% | 18.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 22,540,540 | 2.1% | 20.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 14,769,880 | 1.4% | 22.2% |
| POP_TOP LOAD_FAST | 14,650,600 | 1.4% | 23.6% |
| PUSH_NULL LOAD_FAST | 14,239,700 | 1.3% | 24.9% |
| CALL_BUILTIN_O POP_TOP | 13,870,400 | 1.3% | 26.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 13,562,360 | 1.3% | 27.4% |
| LOAD_GLOBAL_MODULE IS_OP | 13,316,600 | 1.2% | 28.7% |
| RESUME_CHECK LOAD_FAST | 13,085,600 | 1.2% | 29.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 12,353,200 | 1.1% | 31.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 10,645,840 | 1.0% | 32.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 10,539,920 | 1.0% | 33.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,272,280 | 1.0% | 33.9% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 10,087,920 | 0.9% | 34.9% |
| IS_OP POP_JUMP_IF_FALSE | 10,058,660 | 0.9% | 35.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 9,974,080 | 0.9% | 36.7% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 9,931,020 | 0.9% | 37.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 9,737,320 | 0.9% | 38.6% |
| LOAD_FAST CALL_BUILTIN_O | 9,536,100 | 0.9% | 39.5% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 9,361,520 | 0.9% | 40.3% |
| CACHE RESUME_CHECK | 9,244,080 | 0.9% | 41.2% |
| LOAD_CONST COMPARE_OP_STR | 8,798,040 | 0.8% | 42.0% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 8,680,600 | 0.8% | 42.8% |
| RETURN_CONST POP_TOP | 8,535,480 | 0.8% | 43.6% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 8,423,200 | 0.8% | 44.4% |
| EXTENDED_ARG ENTER_EXECUTOR | 8,176,700 | 0.8% | 45.1% |
| LOAD_GLOBAL_MODULE BINARY_OP | 8,120,740 | 0.8% | 45.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,724,120 | 0.7% | 46.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 7,626,760 | 0.7% | 47.3% |
| LOAD_FAST LOAD_ATTR | 7,534,360 | 0.7% | 48.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 7,338,040 | 0.7% | 48.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 7,195,060 | 0.7% | 49.4% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 6,936,120 | 0.6% | 50.0% |
| LOAD_ATTR STORE_FAST | 6,860,440 | 0.6% | 50.6% |
| BINARY_OP_ADD_INT STORE_FAST | 6,738,880 | 0.6% | 51.3% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 6,721,040 | 0.6% | 51.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,672,360 | 0.6% | 52.5% |
| LOAD_CONST STORE_FAST | 6,635,140 | 0.6% | 53.1% |
| BINARY_OP TO_BOOL_INT | 6,564,900 | 0.6% | 53.7% |
| STORE_FAST LOAD_CONST | 6,461,360 | 0.6% | 54.3% |
| RETURN_VALUE INTERPRETER_EXIT | 6,444,320 | 0.6% | 54.9% |
| LOAD_GLOBAL_MODULE STORE_FAST | 6,364,160 | 0.6% | 55.5% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 6,103,280 | 0.6% | 56.1% |
| LOAD_FAST CALL_LEN | 6,078,240 | 0.6% | 56.7% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 5,887,340 | 0.5% | 57.2% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 5,820,300 | 0.5% | 57.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 5,809,340 | 0.5% | 58.3% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 5,582,880 | 0.5% | 58.8% |
| NOP LOAD_FAST | 5,389,360 | 0.5% | 59.3% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 5,288,720 | 0.5% | 59.8% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 5,236,160 | 0.5% | 60.3% |
| STORE_FAST NOP | 5,026,120 | 0.5% | 60.7% |
| EXTENDED_ARG JUMP_FORWARD | 4,933,360 | 0.5% | 61.2% |
| STORE_FAST STORE_FAST | 4,756,320 | 0.4% | 61.6% |
| STORE_FAST_STORE_FAST LOAD_FAST | 4,679,420 | 0.4% | 62.1% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 4,670,260 | 0.4% | 62.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 4,654,000 | 0.4% | 62.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,525,380 | 0.4% | 63.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 4,510,360 | 0.4% | 63.8% |
| JUMP_FORWARD EXTENDED_ARG | 4,508,640 | 0.4% | 64.2% |
| LOAD_FAST RETURN_VALUE | 4,419,000 | 0.4% | 64.6% |
| EXTENDED_ARG FOR_ITER | 4,351,160 | 0.4% | 65.0% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 4,310,060 | 0.4% | 65.4% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,268,600 | 0.4% | 65.8% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 3,916,720 | 0.4% | 66.2% |
| LOAD_GLOBAL_BUILTIN STORE_FAST | 3,914,880 | 0.4% | 66.5% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 3,884,800 | 0.4% | 66.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 3,862,160 | 0.4% | 67.3% |
| LOAD_CONST BINARY_SUBSCR_STR_INT | 3,856,360 | 0.4% | 67.6% |
| CALL STORE_FAST | 3,741,300 | 0.3% | 68.0% |
| BINARY_SUBSCR_STR_INT LOAD_CONST | 3,719,720 | 0.3% | 68.3% |
| IS_OP POP_JUMP_IF_TRUE | 3,705,780 | 0.3% | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,703,760 | 0.3% | 69.0% |
| CALL_LEN RETURN_VALUE | 3,683,280 | 0.3% | 69.3% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 3,683,280 | 0.3% | 69.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 3,670,240 | 0.3% | 70.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 3,602,000 | 0.3% | 70.4% |
| LOAD_FAST CALL_LIST_APPEND | 3,573,680 | 0.3% | 70.7% |
| CALL_LIST_APPEND RETURN_CONST | 3,573,680 | 0.3% | 71.0% |
| POP_TOP EXTENDED_ARG | 3,570,800 | 0.3% | 71.3% |
| CONTAINS_OP EXTENDED_ARG | 3,567,120 | 0.3% | 71.7% |
| LOAD_FAST LOAD_FAST | 3,503,200 | 0.3% | 72.0% |
| ENTER_EXECUTOR EXTENDED_ARG | 3,493,620 | 0.3% | 72.3% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 3,471,740 | 0.3% | 72.7% |
| BUILD_LIST STORE_FAST | 3,470,040 | 0.3% | 73.0% |
| PUSH_NULL LOAD_CONST | 3,395,760 | 0.3% | 73.3% |
| LOAD_FAST TO_BOOL_INT | 3,369,400 | 0.3% | 73.6% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 3,293,040 | 0.3% | 73.9% |
| EXTENDED_ARG FOR_ITER_LIST | 3,285,000 | 0.3% | 74.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 3,226,440 | 0.3% | 74.5% |
| BUILD_TUPLE CALL_BOUND_METHOD_EXACT_ARGS | 3,196,280 | 0.3% | 74.8% |
| BINARY_OP_ADD_INT LOAD_FAST | 3,185,720 | 0.3% | 75.1% |
| STORE_FAST EXTENDED_ARG | 3,143,680 | 0.3% | 75.4% |
| CALL_BUILTIN_O BUILD_TUPLE | 3,096,760 | 0.3% | 75.7% |
| RETURN_VALUE STORE_FAST | 3,086,720 | 0.3% | 76.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 304,800 | 90.0% |
| LOAD_FAST | 32,800 | 9.7% |
| BINARY_OP_ADD_INT | 1,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 304,560 | 89.9% |
| LOAD_CONST | 33,840 | 10.0% |
| CALL_BUILTIN_CLASS | 240 | 0.1% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 45,200 | 97.8% |
| LOAD_CONST | 1,040 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 45,200 | 97.8% |
| LOAD_FAST | 1,040 | 2.2% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,244,080 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 289,520 | 98.8% |
| RETURN_VALUE | 1,340 | 0.5% |
| ENTER_EXECUTOR | 1,040 | 0.4% |
| LOAD_FAST_LOAD_FAST | 1,040 | 0.4% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 291,920 | 99.6% |
| LOAD_GLOBAL_BUILTIN | 1,040 | 0.4% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 1,274,480 | 81.3% |
| LOAD_FAST | 165,200 | 10.5% |
| LOAD_CONST | 127,860 | 8.2% |
| BINARY_SUBSCR | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,241,680 | 79.2% |
| CALL_ALLOC_AND_ENTER_INIT | 165,200 | 10.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 127,840 | 8.2% |
| STORE_FAST | 32,800 | 2.1% |
| BINARY_SUBSCR | 640 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 566,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 566,480 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,720 | 72.0% |
| LOAD_CONST | 1,060 | 28.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,720 | 72.0% |
| ENTER_EXECUTOR | 1,020 | 27.0% |
| JUMP_BACKWARD | 40 | 1.1% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 613,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 613,040 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,222,180 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,908,160 | 31.9% |
| BINARY_SUBSCR | 1,241,680 | 20.8% |
| BINARY_SUBSCR_TUPLE_INT | 235,560 | 3.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 223,920 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,035,840 | 50.7% |
| FOR_ITER_RANGE | 1,384,380 | 23.1% |
| FOR_ITER_LIST | 1,072,440 | 17.9% |
| FOR_ITER | 449,160 | 7.5% |
| LOAD_FAST_AND_CLEAR | 32,800 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,444,320 | 80.6% |
| RETURN_CONST | 1,546,960 | 19.4% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,026,120 | 82.6% |
| POP_JUMP_IF_FALSE | 501,520 | 8.2% |
| NOP | 173,260 | 2.8% |
| STORE_FAST_STORE_FAST | 173,120 | 2.8% |
| RESUME_CHECK | 115,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,389,360 | 88.6% |
| LOAD_FAST_LOAD_FAST | 289,520 | 4.8% |
| NOP | 173,260 | 2.8% |
| LOAD_CONST | 92,340 | 1.5% |
| BUILD_LIST | 92,160 | 1.5% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 341,520 | 60.3% |
| STORE_ATTR_INSTANCE_VALUE | 223,920 | 39.5% |
| STORE_FAST | 1,040 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 341,520 | 60.3% |
| RETURN_CONST | 223,920 | 39.5% |
| EXTENDED_ARG | 1,040 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 13,870,400 | 51.9% |
| RETURN_CONST | 8,535,480 | 32.0% |
| POP_JUMP_IF_FALSE | 1,886,240 | 7.1% |
| RETURN_VALUE | 1,839,320 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 293,680 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,650,600 | 54.8% |
| EXTENDED_ARG | 3,570,800 | 13.4% |
| ENTER_EXECUTOR | 2,898,660 | 10.9% |
| RETURN_CONST | 1,562,880 | 5.9% |
| JUMP_FORWARD | 1,094,320 | 4.1% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 304,160 | 53.7% |
| BINARY_SUBSCR_STR_INT | 223,920 | 39.5% |
| BINARY_SUBSCR_DICT | 37,360 | 6.6% |
| STORE_SUBSCR | 1,040 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 566,480 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,171,240 | 94.3% |
| LOAD_ATTR_MODULE | 896,620 | 3.4% |
| STORE_FAST_LOAD_FAST | 618,560 | 2.3% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,239,700 | 53.4% |
| LOAD_GLOBAL_MODULE | 5,887,340 | 22.1% |
| LOAD_CONST | 3,395,760 | 12.7% |
| LOAD_FAST_LOAD_FAST | 1,668,400 | 6.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,387,860 | 5.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 8,423,200 | 37.5% |
| LOAD_FAST | 4,419,000 | 19.7% |
| CALL_LEN | 3,683,280 | 16.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,598,240 | 7.1% |
| BINARY_OP_SUBTRACT_INT | 808,400 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 6,444,320 | 28.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 6,103,280 | 27.2% |
| STORE_FAST | 3,086,720 | 13.7% |
| POP_TOP | 1,839,320 | 8.2% |
| CALL_BUILTIN_O | 1,241,680 | 5.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 854,560 | 69.3% |
| LOAD_FAST | 210,400 | 17.1% |
| LOAD_CONST | 165,200 | 13.4% |
| BINARY_OP | 2,640 | 0.2% |
| STORE_SUBSCR | 820 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 797,520 | 64.6% |
| RETURN_CONST | 210,400 | 17.1% |
| EXTENDED_ARG | 165,200 | 13.4% |
| ENTER_EXECUTOR | 35,380 | 2.9% |
| LOAD_FAST_LOAD_FAST | 21,200 | 1.7% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 824,540 | 61.7% |
| BINARY_OP | 223,920 | 16.8% |
| LOAD_ATTR | 223,920 | 16.8% |
| ENTER_EXECUTOR | 57,080 | 4.3% |
| TO_BOOL | 4,540 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,033,520 | 77.4% |
| POP_JUMP_IF_TRUE | 295,900 | 22.1% |
| TO_BOOL | 4,540 | 0.3% |
| TO_BOOL_NONE | 1,860 | 0.1% |
| TO_BOOL_BOOL | 40 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 162,800 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 32,800 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_LIST | 996,000 | 71.0% |
| TO_BOOL_INT | 407,120 | 29.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 996,000 | 71.0% |
| COPY | 407,120 | 29.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,120,740 | 82.7% |
| LOAD_FAST_LOAD_FAST | 731,440 | 7.4% |
| LOAD_FAST | 234,120 | 2.4% |
| RETURN_VALUE | 224,980 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 223,920 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 6,564,900 | 66.8% |
| STORE_FAST | 1,827,040 | 18.6% |
| LOAD_FAST | 387,760 | 3.9% |
| TO_BOOL | 223,920 | 2.3% |
| CALL | 223,920 | 2.3% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,333,840 | 32.9% |
| RESUME_CHECK | 833,280 | 20.5% |
| STORE_FAST | 664,000 | 16.4% |
| LOAD_CONST | 554,800 | 13.7% |
| POP_JUMP_IF_FALSE | 288,840 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,470,040 | 85.5% |
| LOAD_FAST | 447,840 | 11.0% |
| LOAD_GLOBAL_BUILTIN | 106,960 | 2.6% |
| SWAP | 32,800 | 0.8% |
| CALL_METHOD_DESCRIPTOR_O | 1,040 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 447,840 | 99.8% |
| STORE_FAST | 1,040 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 447,840 | 99.8% |
| STORE_FAST | 1,040 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,274,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 1,274,480 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 3,096,760 | 39.0% |
| LOAD_FAST_LOAD_FAST | 1,440,160 | 18.1% |
| CALL | 1,431,200 | 18.0% |
| LOAD_FAST | 662,480 | 8.3% |
| BUILD_TUPLE | 483,120 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 3,196,280 | 40.3% |
| LOAD_FAST | 1,596,400 | 20.1% |
| CALL_BUILTIN_O | 806,880 | 10.2% |
| RETURN_VALUE | 564,480 | 7.1% |
| BUILD_TUPLE | 483,120 | 6.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,862,400 | 41.9% |
| LOAD_FAST_LOAD_FAST | 1,824,040 | 26.7% |
| LOAD_FAST | 1,563,620 | 22.9% |
| BINARY_OP | 223,920 | 3.3% |
| ENTER_EXECUTOR | 179,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,741,300 | 54.8% |
| BUILD_TUPLE | 1,431,200 | 20.9% |
| LOAD_GLOBAL_BUILTIN | 1,431,200 | 20.9% |
| RETURN_VALUE | 223,920 | 3.3% |
| CALL | 2,500 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| RESUME_CHECK | 60 | 37.5% |
| RESUME | 20 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 670,720 | 67.6% |
| LOAD_FAST | 178,340 | 18.0% |
| LOAD_ATTR_INSTANCE_VALUE | 135,380 | 13.7% |
| COMPARE_OP | 4,020 | 0.4% |
| COMPARE_OP_STR | 3,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 777,060 | 78.4% |
| POP_JUMP_IF_TRUE | 207,360 | 20.9% |
| COMPARE_OP | 4,020 | 0.4% |
| COMPARE_OP_STR | 3,160 | 0.3% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,680,600 | 62.8% |
| LOAD_FAST_LOAD_FAST | 3,884,800 | 28.1% |
| LOAD_CONST | 1,260,280 | 9.1% |
| LOAD_FAST | 1,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,087,920 | 73.0% |
| EXTENDED_ARG | 3,567,120 | 25.8% |
| RETURN_VALUE | 141,680 | 1.0% |
| POP_JUMP_IF_TRUE | 30,000 | 0.2% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,431,520 | 47.1% |
| LOAD_ATTR_INSTANCE_VALUE | 808,400 | 26.6% |
| UNARY_NOT | 407,120 | 13.4% |
| LOAD_FAST | 193,040 | 6.4% |
| BINARY_OP | 182,880 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,431,200 | 47.1% |
| TO_BOOL_STR | 798,720 | 26.3% |
| TO_BOOL_BOOL | 423,680 | 13.9% |
| TO_BOOL_INT | 365,760 | 12.0% |
| TO_BOOL_NONE | 9,680 | 0.3% |


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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 8,176,700 | 44.9% |
| POP_JUMP_IF_TRUE | 3,471,740 | 19.1% |
| POP_TOP | 2,898,660 | 15.9% |
| STORE_FAST | 2,157,440 | 11.9% |
| STORE_SUBSCR_LIST_INT | 1,084,580 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,936,120 | 38.1% |
| EXTENDED_ARG | 3,493,620 | 19.2% |
| BINARY_SUBSCR_GETITEM | 2,994,180 | 16.4% |
| RESUME_CHECK | 1,669,760 | 9.2% |
| FOR_ITER_RANGE | 1,390,240 | 7.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 4,508,640 | 17.7% |
| POP_TOP | 3,570,800 | 14.0% |
| CONTAINS_OP | 3,567,120 | 14.0% |
| ENTER_EXECUTOR | 3,493,620 | 13.7% |
| STORE_FAST | 3,143,680 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,176,700 | 32.0% |
| JUMP_FORWARD | 4,933,360 | 19.3% |
| POP_JUMP_IF_FALSE | 4,670,260 | 18.3% |
| FOR_ITER | 4,351,160 | 17.0% |
| FOR_ITER_LIST | 3,285,000 | 12.9% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 4,351,160 | 90.2% |
| GET_ITER | 449,160 | 9.3% |
| JUMP_BACKWARD | 20,680 | 0.4% |
| FOR_ITER | 3,420 | 0.1% |
| FOR_ITER_LIST | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,948,980 | 61.1% |
| RETURN_CONST | 1,402,180 | 29.1% |
| LOAD_FAST | 223,920 | 4.6% |
| LOAD_GLOBAL_MODULE | 223,920 | 4.6% |
| STORE_FAST | 21,220 | 0.4% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,316,600 | 96.6% |
| LOAD_FAST | 223,920 | 1.6% |
| LOAD_GLOBAL_BUILTIN | 223,920 | 1.6% |
| LOAD_CONST | 16,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,058,660 | 73.0% |
| POP_JUMP_IF_TRUE | 3,705,780 | 26.9% |
| COPY | 16,320 | 0.1% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,052,420 | 88.5% |
| EXTENDED_ARG | 116,020 | 9.8% |
| POP_JUMP_IF_TRUE | 19,540 | 1.6% |
| FOR_ITER_TUPLE | 1,120 | 0.1% |
| POP_JUMP_IF_FALSE | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 1,167,040 | 98.1% |
| FOR_ITER | 20,680 | 1.7% |
| NOP | 700 | 0.1% |
| FOR_ITER_LIST | 700 | 0.1% |
| ENTER_EXECUTOR | 260 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 4,933,360 | 55.9% |
| POP_TOP | 1,094,320 | 12.4% |
| STORE_FAST | 951,920 | 10.8% |
| STORE_SUBSCR | 797,520 | 9.0% |
| POP_JUMP_IF_TRUE | 407,120 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 4,508,640 | 51.1% |
| LOAD_GLOBAL_BUILTIN | 2,097,280 | 23.8% |
| LOAD_FAST | 1,541,760 | 17.5% |
| LOAD_GLOBAL_MODULE | 381,800 | 4.3% |
| LOAD_FAST_LOAD_FAST | 203,280 | 2.3% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 32,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 32,800 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,534,360 | 99.3% |
| LOAD_GLOBAL_BUILTIN | 51,440 | 0.7% |
| LOAD_ATTR | 3,100 | 0.0% |
| LOAD_GLOBAL_MODULE | 520 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,860,440 | 90.4% |
| LOAD_FAST | 275,360 | 3.6% |
| TO_BOOL | 223,920 | 3.0% |
| LOAD_FAST_LOAD_FAST | 223,920 | 3.0% |
| LOAD_ATTR | 3,100 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,178,620 | 45.7% |
| STORE_FAST | 6,461,360 | 12.2% |
| BINARY_SUBSCR_STR_INT | 3,719,720 | 7.0% |
| PUSH_NULL | 3,395,760 | 6.4% |
| LOAD_CONST | 2,858,960 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 9,737,320 | 18.4% |
| COMPARE_OP_STR | 8,798,040 | 16.6% |
| STORE_FAST | 6,635,140 | 12.5% |
| BINARY_SUBSCR_STR_INT | 3,856,360 | 7.3% |
| LOAD_FAST | 3,026,320 | 5.7% |


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
| POP_JUMP_IF_FALSE | 56,575,840 | 25.9% |
| STORE_FAST | 27,801,320 | 12.7% |
| LOAD_GLOBAL_BUILTIN | 22,540,540 | 10.3% |
| POP_TOP | 14,650,600 | 6.7% |
| PUSH_NULL | 14,239,700 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 35,160,560 | 16.1% |
| LOAD_GLOBAL_MODULE | 32,983,180 | 15.1% |
| PUSH_NULL | 25,171,240 | 11.5% |
| LOAD_CONST | 24,178,620 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 10,645,840 | 4.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 32,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 32,800 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 79,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 79,840 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,916,720 | 15.2% |
| STORE_FAST_STORE_FAST | 3,293,040 | 12.8% |
| STORE_ATTR_INSTANCE_VALUE | 3,226,440 | 12.5% |
| LOAD_GLOBAL_MODULE | 2,833,760 | 11.0% |
| LOAD_GLOBAL_BUILTIN | 2,273,680 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 6,672,360 | 25.9% |
| CONTAINS_OP | 3,884,800 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,992,000 | 11.6% |
| CALL | 1,824,040 | 7.1% |
| STORE_SUBSCR_LIST_INT | 1,533,540 | 5.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 22.2% |
| RETURN_VALUE | 40 | 7.4% |
| LOAD_FAST | 40 | 7.4% |
| POP_JUMP_IF_FALSE | 40 | 7.4% |
| STORE_FAST | 40 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 300 | 55.6% |
| LOAD_ATTR | 160 | 29.6% |
| LOAD_GLOBAL_BUILTIN | 60 | 11.1% |
| LOAD_FAST | 20 | 3.7% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 12,353,200 | 18.3% |
| CONTAINS_OP | 10,087,920 | 14.9% |
| IS_OP | 10,058,660 | 14.9% |
| COMPARE_OP_STR | 9,931,020 | 14.7% |
| ENTER_EXECUTOR | 6,936,120 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,575,840 | 83.8% |
| LOAD_GLOBAL_MODULE | 2,509,680 | 3.7% |
| POP_TOP | 1,886,240 | 2.8% |
| LOAD_CONST | 1,156,900 | 1.7% |
| LOAD_FAST_LOAD_FAST | 1,066,320 | 1.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,822,400 | 73.0% |
| LOAD_FAST | 675,200 | 27.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,431,200 | 57.3% |
| LOAD_FAST | 889,440 | 35.6% |
| ENTER_EXECUTOR | 113,760 | 4.6% |
| LOAD_GLOBAL_BUILTIN | 62,960 | 2.5% |
| RETURN_CONST | 240 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,862,160 | 90.6% |
| ENTER_EXECUTOR | 402,840 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,816,920 | 42.6% |
| BUILD_LIST | 1,333,840 | 31.3% |
| LOAD_GLOBAL_BUILTIN | 421,360 | 9.9% |
| EXTENDED_ARG | 223,920 | 5.3% |
| LOAD_GLOBAL_MODULE | 223,920 | 5.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 4,310,060 | 35.7% |
| IS_OP | 3,705,780 | 30.7% |
| TO_BOOL_BOOL | 2,297,440 | 19.0% |
| TO_BOOL_STR | 798,720 | 6.6% |
| TO_BOOL_LIST | 338,920 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,809,340 | 48.2% |
| ENTER_EXECUTOR | 3,471,740 | 28.8% |
| CALL_LEN | 799,040 | 6.6% |
| JUMP_FORWARD | 407,120 | 3.4% |
| LOAD_GLOBAL_MODULE | 387,840 | 3.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 4,510,360 | 34.2% |
| CALL_LIST_APPEND | 3,573,680 | 27.1% |
| POP_TOP | 1,562,880 | 11.9% |
| FOR_ITER | 1,402,180 | 10.6% |
| POP_JUMP_IF_FALSE | 987,680 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,535,480 | 64.8% |
| TO_BOOL_BOOL | 2,025,720 | 15.4% |
| INTERPRETER_EXIT | 1,546,960 | 11.7% |
| EXIT_INIT_CHECK | 613,040 | 4.7% |
| STORE_FAST | 450,600 | 3.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 6,860,440 | 10.5% |
| BINARY_OP_ADD_INT | 6,738,880 | 10.3% |
| LOAD_CONST | 6,635,140 | 10.1% |
| LOAD_GLOBAL_MODULE | 6,364,160 | 9.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,820,300 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,801,320 | 42.4% |
| LOAD_GLOBAL_MODULE | 7,338,040 | 11.2% |
| LOAD_CONST | 6,461,360 | 9.9% |
| LOAD_GLOBAL_BUILTIN | 5,236,160 | 8.0% |
| NOP | 5,026,120 | 7.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 618,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 618,560 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,626,760 | 81.3% |
| COPY | 1,431,200 | 15.3% |
| UNPACK_SEQUENCE_TUPLE | 285,760 | 3.0% |
| STORE_FAST_STORE_FAST | 32,720 | 0.3% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,679,420 | 49.9% |
| LOAD_FAST_LOAD_FAST | 3,293,040 | 35.1% |
| LOAD_GLOBAL_BUILTIN | 912,000 | 9.7% |
| STORE_FAST | 253,040 | 2.7% |
| NOP | 173,120 | 1.8% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 32,800 | 30.6% |
| LOAD_FAST_AND_CLEAR | 32,800 | 30.6% |
| FOR_ITER_RANGE | 32,800 | 30.6% |
| BINARY_OP | 8,800 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 32,800 | 30.6% |
| STORE_FAST | 32,800 | 30.6% |
| FOR_ITER_RANGE | 32,800 | 30.6% |
| STORE_ATTR_INSTANCE_VALUE | 8,800 | 8.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20 | 50.0% |
| FOR_ITER_LIST | 20 | 50.0% |

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
| CALL | 20 | 33.3% |
| CALL_FUNCTION_EX | 20 | 33.3% |
| COPY_FREE_VARS | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 66.7% |
| LOAD_DEREF | 20 | 33.3% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,737,320 | 94.1% |
| LOAD_FAST_LOAD_FAST | 430,240 | 4.2% |
| BINARY_OP_MULTIPLY_INT | 183,840 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,738,880 | 65.1% |
| LOAD_FAST | 3,185,720 | 30.8% |
| CALL_PY_EXACT_ARGS | 183,200 | 1.8% |
| CALL_BUILTIN_O | 130,080 | 1.3% |
| STORE_SLICE | 45,200 | 0.4% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 260,160 | 58.5% |
| BINARY_SUBSCR_TUPLE_INT | 183,840 | 41.3% |
| LOAD_ATTR | 1,040 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 183,840 | 41.3% |
| LOAD_CONST | 130,080 | 29.2% |
| CALL_BUILTIN_O | 130,080 | 29.2% |
| LOAD_GLOBAL_BUILTIN | 1,040 | 0.2% |


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
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,595,360 | 49.3% |
| LOAD_CONST | 829,040 | 25.6% |
| CALL_LEN | 808,400 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,445,760 | 44.7% |
| RETURN_VALUE | 808,400 | 25.0% |
| LOAD_FAST | 341,520 | 10.6% |
| LOAD_CONST | 292,160 | 9.0% |
| STORE_FAST | 236,080 | 7.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 485,780 | 67.5% |
| LOAD_FAST_LOAD_FAST | 196,720 | 27.3% |
| BUILD_TUPLE | 37,360 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 251,780 | 35.0% |
| RETURN_VALUE | 223,920 | 31.1% |
| LOAD_CONST | 189,120 | 26.3% |
| PUSH_EXC_INFO | 37,360 | 5.2% |
| STORE_FAST | 8,800 | 1.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,994,180 | 56.6% |
| LOAD_FAST | 1,240,080 | 23.4% |
| LOAD_CONST | 1,054,460 | 19.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,288,720 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,361,520 | 92.4% |
| LOAD_CONST | 486,020 | 4.8% |
| LOAD_FAST_LOAD_FAST | 175,520 | 1.7% |
| BINARY_OP_SUBTRACT_INT | 87,760 | 0.9% |
| BINARY_SUBSCR_LIST_INT | 24,080 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,423,200 | 94.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 116,280 | 1.3% |
| STORE_FAST | 94,720 | 1.1% |
| LOAD_FAST_LOAD_FAST | 87,760 | 1.0% |
| COMPARE_OP_INT | 87,760 | 1.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,856,360 | 55.2% |
| LOAD_FAST | 3,031,000 | 43.4% |
| ENTER_EXECUTOR | 97,600 | 1.4% |
| BINARY_SUBSCR_STR_INT | 4,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,719,720 | 53.2% |
| STORE_FAST | 2,614,760 | 37.4% |
| BINARY_OP_INPLACE_ADD_UNICODE | 289,520 | 4.1% |
| PUSH_EXC_INFO | 223,920 | 3.2% |
| CALL_BUILTIN_O | 137,040 | 2.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,454,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 805,920 | 32.8% |
| CALL_BUILTIN_O | 561,280 | 22.9% |
| GET_ITER | 235,560 | 9.6% |
| LOAD_FAST | 200,400 | 8.2% |
| BINARY_OP_MULTIPLY_INT | 183,840 | 7.5% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 223,920 | 36.5% |
| LOAD_GLOBAL_MODULE | 223,920 | 36.5% |
| BINARY_SUBSCR | 165,200 | 26.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 613,040 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 3,196,280 | 47.6% |
| LOAD_CONST | 1,861,320 | 27.7% |
| PUSH_NULL | 1,387,860 | 20.6% |
| LOAD_FAST | 275,200 | 4.1% |
| BINARY_SUBSCR_LIST_INT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,721,040 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,348,640 | 89.5% |
| CALL_BUILTIN_FAST | 51,440 | 3.4% |
| LOAD_CONST | 34,880 | 2.3% |
| BINARY_OP_ADD_INT | 34,880 | 2.3% |
| UNARY_NEGATIVE | 32,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,241,680 | 82.4% |
| GET_ITER | 143,120 | 9.5% |
| RETURN_VALUE | 51,440 | 3.4% |
| STORE_FAST | 35,820 | 2.4% |
| LIST_APPEND | 32,800 | 2.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,440 | 98.1% |
| CALL_BUILTIN_FAST | 980 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 51,440 | 98.1% |
| CALL_BUILTIN_FAST | 980 | 1.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 223,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 223,920 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,536,100 | 55.0% |
| LOAD_GLOBAL_MODULE | 1,999,600 | 11.5% |
| LOAD_CONST | 1,534,400 | 8.8% |
| RETURN_VALUE | 1,241,680 | 7.2% |
| CALL_LEN | 1,018,960 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,870,400 | 80.0% |
| BUILD_TUPLE | 3,096,760 | 17.9% |
| TO_BOOL_BOOL | 243,440 | 1.4% |
| STORE_FAST | 138,080 | 0.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 9,974,080 | 89.0% |
| BUILD_TUPLE | 447,840 | 4.0% |
| LOAD_GLOBAL_MODULE | 341,920 | 3.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 223,920 | 2.0% |
| LOAD_ATTR_SLOT | 223,920 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,539,920 | 94.0% |
| RETURN_VALUE | 447,840 | 4.0% |
| LOAD_FAST | 223,920 | 2.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,078,240 | 55.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,683,280 | 33.4% |
| POP_JUMP_IF_TRUE | 799,040 | 7.3% |
| LOAD_GLOBAL_MODULE | 447,840 | 4.1% |
| LOAD_CONST | 9,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,683,280 | 33.4% |
| LOAD_FAST | 1,531,600 | 13.9% |
| CALL_BUILTIN_CLASS | 1,348,640 | 12.2% |
| LOAD_CONST | 1,061,840 | 9.6% |
| CALL_BUILTIN_O | 1,018,960 | 9.2% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,573,680 | 84.0% |
| BUILD_TUPLE | 295,920 | 7.0% |
| LOAD_GLOBAL_MODULE | 223,920 | 5.3% |
| LOAD_CONST | 130,080 | 3.1% |
| ENTER_EXECUTOR | 28,800 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,573,680 | 84.0% |
| LOAD_FAST | 354,000 | 8.3% |
| ENTER_EXECUTOR | 168,320 | 4.0% |
| EXTENDED_ARG | 120,960 | 2.8% |
| LOAD_FAST_LOAD_FAST | 32,800 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 436,160 | 51.9% |
| LOAD_CONST | 341,520 | 40.6% |
| LOAD_FAST_LOAD_FAST | 60,560 | 7.2% |
| BUILD_TUPLE | 2,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 838,240 | 99.7% |
| POP_TOP | 2,560 | 0.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 32,800 | 96.9% |
| LOAD_CONST | 1,040 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,800 | 96.9% |
| STORE_FAST | 1,040 | 3.1% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 225,680 | 99.8% |
| LOAD_ATTR | 360 | 0.2% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 223,920 | 99.0% |
| POP_TOP | 1,140 | 0.5% |
| RETURN_VALUE | 1,040 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 185,680 | 63.2% |
| RETURN_VALUE | 106,960 | 36.4% |
| BUILD_LIST | 1,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 293,680 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,268,600 | 41.6% |
| LOAD_FAST | 2,288,020 | 22.3% |
| LOAD_FAST_LOAD_FAST | 1,334,920 | 13.0% |
| UNARY_NOT | 996,000 | 9.7% |
| LOAD_CONST | 406,800 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,272,280 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,280 | 50.6% |
| LOAD_FAST_LOAD_FAST | 223,920 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 453,200 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 223,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 223,920 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 602,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 378,880 | 62.9% |
| LOAD_FAST | 223,920 | 37.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,748,020 | 67.6% |
| LOAD_GLOBAL_MODULE | 577,920 | 22.3% |
| CALL_LEN | 141,360 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 87,760 | 3.4% |
| LOAD_FAST | 29,340 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,583,620 | 99.9% |
| POP_JUMP_IF_TRUE | 2,080 | 0.1% |
| COPY | 240 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,798,040 | 82.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,908,860 | 17.8% |
| COMPARE_OP | 3,160 | 0.0% |
| LOAD_FAST | 2,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,931,020 | 92.7% |
| EXTENDED_ARG | 778,560 | 7.3% |
| COMPARE_OP | 3,120 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,285,000 | 66.9% |
| GET_ITER | 1,072,440 | 21.9% |
| ENTER_EXECUTOR | 549,400 | 11.2% |
| JUMP_BACKWARD | 700 | 0.0% |
| FOR_ITER | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,110,120 | 43.0% |
| LOAD_GLOBAL_BUILTIN | 1,431,200 | 29.2% |
| STORE_FAST | 506,000 | 10.3% |
| LOAD_FAST | 298,000 | 6.1% |
| LOAD_FAST_LOAD_FAST | 274,880 | 5.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,390,240 | 49.5% |
| GET_ITER | 1,384,380 | 49.3% |
| SWAP | 32,800 | 1.2% |
| JUMP_BACKWARD | 60 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,390,700 | 49.5% |
| LOAD_FAST | 1,349,680 | 48.1% |
| JUMP_FORWARD | 33,200 | 1.2% |
| SWAP | 32,800 | 1.2% |
| LOAD_GLOBAL_MODULE | 1,080 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,600 | 51.9% |
| ENTER_EXECUTOR | 6,840 | 46.7% |
| JUMP_BACKWARD | 200 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,600 | 51.9% |
| LOAD_FAST | 5,920 | 40.4% |
| JUMP_BACKWARD | 1,120 | 7.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,160,560 | 89.5% |
| LOAD_FAST_LOAD_FAST | 2,992,000 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,119,840 | 2.9% |
| COPY | 8,800 | 0.0% |
| ENTER_EXECUTOR | 8,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,562,360 | 34.5% |
| STORE_FAST | 5,820,300 | 14.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,703,760 | 9.4% |
| CALL_LEN | 3,683,280 | 9.4% |
| COMPARE_OP_STR | 1,908,860 | 4.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,703,760 | 62.7% |
| LOAD_FAST | 1,363,920 | 23.1% |
| LOAD_GLOBAL_MODULE | 838,960 | 14.2% |
| CALL | 1,040 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,654,000 | 78.8% |
| LOAD_GLOBAL_MODULE | 429,840 | 7.3% |
| LOAD_CONST | 423,760 | 7.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 225,680 | 3.8% |
| LOAD_FAST_LOAD_FAST | 174,400 | 3.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,525,380 | 94.2% |
| BINARY_SUBSCR_TUPLE_INT | 152,080 | 3.2% |
| BINARY_SUBSCR | 127,840 | 2.7% |
| LOAD_FAST_LOAD_FAST | 1,040 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,268,600 | 88.8% |
| LOAD_FAST | 261,440 | 5.4% |
| LOAD_CONST | 183,920 | 3.8% |
| LOAD_GLOBAL_MODULE | 92,140 | 1.9% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,112,280 | 100.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 896,620 | 80.6% |
| STORE_FAST | 162,720 | 14.6% |
| RETURN_VALUE | 52,000 | 4.7% |
| COMPARE_OP_INT | 1,040 | 0.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 223,920 | 50.0% |
| LOAD_FAST_LOAD_FAST | 223,920 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 223,920 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 223,920 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 447,840 | 63.2% |
| LOAD_FAST | 260,160 | 36.7% |
| LOAD_FAST_LOAD_FAST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 708,480 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 223,920 | 50.0% |
| LOAD_FAST_LOAD_FAST | 223,920 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 223,920 | 50.0% |
| CALL_ISINSTANCE | 223,920 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,769,880 | 34.8% |
| LOAD_FAST | 10,645,840 | 25.1% |
| STORE_FAST | 5,236,160 | 12.3% |
| JUMP_FORWARD | 2,097,280 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 1,774,320 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,540,540 | 53.0% |
| CALL_ISINSTANCE | 9,974,080 | 23.5% |
| STORE_FAST | 3,914,880 | 9.2% |
| LOAD_FAST_LOAD_FAST | 2,273,680 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 1,774,320 | 4.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,983,180 | 58.7% |
| STORE_FAST | 7,338,040 | 13.0% |
| PUSH_NULL | 5,887,340 | 10.5% |
| POP_JUMP_IF_FALSE | 2,509,680 | 4.5% |
| RESUME_CHECK | 1,917,320 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 13,316,600 | 23.7% |
| CONTAINS_OP | 8,680,600 | 15.4% |
| BINARY_OP | 8,120,740 | 14.4% |
| LOAD_FAST | 7,195,060 | 12.8% |
| STORE_FAST | 6,364,160 | 11.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,272,280 | 29.4% |
| CACHE | 9,244,080 | 26.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,721,040 | 19.2% |
| BINARY_SUBSCR_GETITEM | 5,288,720 | 15.1% |
| ENTER_EXECUTOR | 1,669,760 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 14,769,880 | 42.2% |
| LOAD_FAST | 13,085,600 | 37.4% |
| LOAD_FAST_LOAD_FAST | 3,916,720 | 11.2% |
| LOAD_GLOBAL_MODULE | 1,917,320 | 5.5% |
| BUILD_LIST | 833,280 | 2.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,724,120 | 52.8% |
| LOAD_FAST_LOAD_FAST | 6,672,360 | 45.6% |
| LOAD_ATTR_INSTANCE_VALUE | 223,920 | 1.5% |
| SWAP | 8,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,510,360 | 30.8% |
| LOAD_FAST | 3,602,000 | 24.6% |
| LOAD_FAST_LOAD_FAST | 3,226,440 | 22.1% |
| LOAD_CONST | 2,394,720 | 16.4% |
| BUILD_MAP | 447,840 | 3.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 449,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,280 | 50.2% |
| LOAD_GLOBAL_BUILTIN | 223,920 | 49.8% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,533,540 | 87.7% |
| LOAD_FAST | 214,880 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,084,580 | 62.0% |
| RETURN_CONST | 352,960 | 20.2% |
| EXTENDED_ARG | 286,960 | 16.4% |
| LOAD_FAST | 23,920 | 1.4% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 10,539,920 | 70.7% |
| RETURN_CONST | 2,025,720 | 13.6% |
| LOAD_FAST | 763,440 | 5.1% |
| RETURN_VALUE | 606,080 | 4.1% |
| COPY | 423,680 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,353,200 | 82.8% |
| POP_JUMP_IF_TRUE | 2,297,440 | 15.4% |
| EXTENDED_ARG | 264,240 | 1.8% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 6,564,900 | 63.7% |
| LOAD_FAST | 3,369,400 | 32.7% |
| COPY | 365,760 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,582,880 | 54.2% |
| POP_JUMP_IF_TRUE | 4,310,060 | 41.8% |
| UNARY_NOT | 407,120 | 4.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,809,720 | 94.0% |
| LOAD_ATTR_INSTANCE_VALUE | 116,040 | 6.0% |
| TO_BOOL_NONE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNARY_NOT | 996,000 | 51.7% |
| POP_JUMP_IF_FALSE | 590,840 | 30.7% |
| POP_JUMP_IF_TRUE | 338,920 | 17.6% |
| TO_BOOL_NONE | 320 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,370,240 | 99.5% |
| COPY | 9,680 | 0.4% |
| TO_BOOL | 1,860 | 0.1% |
| ENTER_EXECUTOR | 360 | 0.0% |
| TO_BOOL_LIST | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,370,600 | 99.5% |
| POP_JUMP_IF_TRUE | 9,680 | 0.4% |
| TO_BOOL | 1,860 | 0.1% |
| TO_BOOL_LIST | 320 | 0.0% |
| TO_BOOL_STR | 160 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 798,720 | 99.9% |
| LOAD_FAST | 600 | 0.1% |
| TO_BOOL_NONE | 160 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 798,720 | 99.9% |
| POP_JUMP_IF_FALSE | 640 | 0.1% |
| TO_BOOL_NONE | 160 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 321,760 | 53.7% |
| RETURN_VALUE | 253,040 | 42.3% |
| BINARY_SUBSCR_TUPLE_INT | 23,920 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 312,960 | 52.3% |
| STORE_FAST_STORE_FAST | 285,760 | 47.7% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,103,280 | 54.0% |
| FOR_ITER | 2,948,980 | 26.1% |
| FOR_ITER_LIST | 2,110,120 | 18.7% |
| BINARY_SUBSCR_LIST_INT | 116,280 | 1.0% |
| LOAD_CONST | 18,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 7,626,760 | 67.5% |
| STORE_FAST | 3,670,240 | 32.5% |


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
|     deferred | 9,815,560 | 40.7% |
|          hit | 14,322,260 | 59.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 0.7% |
| Failure | 5,960 | 99.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 4,180 | 70.1% |
| or | 840 | 14.1% |
| add other | 420 | 7.0% |
| multiply different types | 260 | 4.4% |
| add different types | 100 | 1.7% |
| and different types | 100 | 1.7% |
| floor divide | 60 | 1.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>


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
|     deferred | 1,539,080 | 5.7% |
|          hit | 24,078,020 | 88.7% |
|         miss | 1,509,160 | 5.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 28,460 | 97.8% |
| Failure | 640 | 2.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 340 | 53.1% |
| out of range | 100 | 15.6% |
| list slice | 100 | 15.6% |
| buffer slice | 100 | 15.6% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,827,940 | 8.6% |
|          hit | 72,562,640 | 91.3% |
|         miss | 52,420 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,260 | 33.5% |
| Failure | 2,500 | 66.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 1,280 | 51.2% |
| wrong number arguments | 460 | 18.4% |
| class no vectorcall | 340 | 13.6% |
| meth descr varargs | 220 | 8.8% |
| class mutable | 120 | 4.8% |
| cfunc noargs | 60 | 2.4% |
| str | 20 | 0.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 981,300 | 6.9% |
|          hit | 13,132,860 | 91.9% |
|         miss | 165,780 | 1.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,180 | 30.8% |
| Failure | 7,140 | 69.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 6,540 | 91.6% |
| other | 260 | 3.6% |
| big int | 200 | 2.8% |
| tuple | 140 | 2.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,820,400 | 38.4% |
|          hit | 7,700,580 | 61.3% |
|         miss | 29,680 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 13.1% |
| Failure | 3,980 | 86.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| seq iter | 3,700 | 93.0% |
| dict keys | 100 | 2.5% |
| dict items | 100 | 2.5% |
| map | 80 | 2.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,586,260 | 12.6% |
|          hit | 52,720,560 | 87.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 6.6% |
| Failure | 3,100 | 93.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 2,420 | 78.1% |
| metaclass attribute | 360 | 11.6% |
| not managed dict | 180 | 5.8% |
| builtin class method | 100 | 3.2% |
| mutable class | 40 | 1.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 180 | 0.0% |
|          hit | 98,728,420 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 360 | 100.0% |
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
|          hit | 14,629,200 | 100.0% |


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
|     deferred | 1,232,800 | 35.9% |
|          hit | 2,197,620 | 64.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 820 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 560 | 68.3% |
| py simple | 160 | 19.5% |
| out of range | 100 | 12.2% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,326,600 | 4.2% |
|          hit | 30,172,520 | 95.3% |
|         miss | 150,640 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,900 | 31.2% |
| Failure | 6,400 | 68.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 4,980 | 77.8% |
| mapping | 500 | 7.8% |
| other | 440 | 6.9% |
| dict | 380 | 5.9% |
| number | 100 | 1.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 11,895,720 | 100.0% |

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
| Basic | 584,078,560 | 54.2% |
| Not specialized | 121,242,680 | 11.3% |
| Specialized hits | 370,097,140 | 34.4% |
| Specialized misses | 1,907,680 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 9,815,560 | 28.8% |
| LOAD_ATTR | 7,586,260 | 22.2% |
| CALL | 6,827,940 | 20.0% |
| FOR_ITER | 4,820,400 | 14.1% |
| BINARY_SUBSCR | 1,539,080 | 4.5% |
| TO_BOOL | 1,326,600 | 3.9% |
| STORE_SUBSCR | 1,232,800 | 3.6% |
| COMPARE_OP | 981,300 | 2.9% |
| LOAD_GLOBAL | 180 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 1,276,880 | 66.9% |
| BINARY_SUBSCR_STR_INT | 232,280 | 12.2% |
| COMPARE_OP_STR | 165,780 | 8.7% |
| TO_BOOL_NONE | 125,520 | 6.6% |
| CALL_BUILTIN_FAST | 52,420 | 2.7% |
| FOR_ITER_LIST | 29,680 | 1.6% |
| TO_BOOL_LIST | 16,960 | 0.9% |
| TO_BOOL_STR | 8,160 | 0.4% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 9,244,080 | 27.8% |
| Calls to Python functions inlined | 24,056,960 | 72.2% |
| Calls via PyEval_EvalFrame (total) | 9,244,080 | 27.8% |
| Calls via PyEval_EvalFrame (vector) | 9,244,080 | 27.8% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 9,244,080 | 27.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 7,649,360 | 23.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 3,072,080 | 9.2% |
| Frames pushed | 32,422,200 | 97.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 22,463,640 | 26.3% |
| Frees to freelist | 22,472,620 |  |
| Allocations | 62,948,820 | 73.7% |
| Allocations to 512 bytes | 62,906,700 | 73.7% |
| Allocations to 4 kbytes | 40,040 | 0.0% |
| Allocations over 4 kbytes | 2,080 | 0.0% |
| Frees | 65,641,505 |  |
| New values | 1,333,840 |  |
| Interpreter increfs | 565,617,840 | 83.8% |
| Interpreter decrefs | 612,248,340 | 80.7% |
| Increfs | 109,595,986 | 16.2% |
| Decrefs | 146,518,112 | 19.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 8,207,105 |  |
| Method cache misses | 75 |  |
| Method cache collisions | 75 |  |
| Method cache dunder hits | 20,382,335 |  |
| Method cache dunder misses | 5 |  |


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
| Optimization attempts | 1,180 |  |
| Traces created | 260 | 22.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 40 | 3.4% |
| Trace too short | 920 | 78.0% |
| Inner loop found | 20 | 1.7% |
| Recursive call | 0 | 0.0% |
| Traces executed | 18,202,220 |  |
| Uops executed | 880,077,560 | 48.35 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 80 | 30.8% |
| <= 64 | 60 | 23.1% |
| <= 128 | 20 | 7.7% |
| <= 256 | 100 | 38.5% |


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
| <= 16 | 80 | 30.8% |
| <= 32 | 60 | 23.1% |
| <= 64 | 20 | 7.7% |
| <= 128 | 60 | 23.1% |
| <= 256 | 40 | 15.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 1,693,880 | 9.3% |
| <= 2 | 2,095,860 | 11.5% |
| <= 4 | 1,281,840 | 7.0% |
| <= 8 | 340,680 | 1.9% |
| <= 16 | 5,040,760 | 27.7% |
| <= 32 | 4,445,000 | 24.4% |
| <= 64 | 210,540 | 1.2% |
| <= 128 | 2,836,680 | 15.6% |
| <= 256 | 150,540 | 0.8% |
| <= 512 | 51,540 | 0.3% |
| <= 1,024 | 53,220 | 0.3% |
| <= 2,048 | 240 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 80 | 0.0% |
| <= 16,384 | 960 | 0.0% |
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 0 | 0.0% |
| <= 131,072 | 0 | 0.0% |
| <= 262,144 | 0 | 0.0% |
| <= 524,288 | 0 | 0.0% |
| <= 1,048,576 | 400 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 141,956,260 | 16.1% | 16.1% |  |
| _SET_IP | 105,393,580 | 12.0% | 28.1% |  |
| _CHECK_VALIDITY | 95,212,440 | 10.8% | 38.9% |  |
| STORE_FAST | 55,075,000 | 6.3% | 45.2% |  |
| LOAD_CONST | 42,173,260 | 4.8% | 50.0% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 31,134,880 | 3.5% | 53.5% | 4.5% |
| _ITER_CHECK_RANGE | 31,134,880 | 3.5% | 57.0% |  |
| _ITER_NEXT_RANGE | 29,744,640 | 3.4% | 60.4% |  |
| _JUMP_TO_TOP | 29,447,540 | 3.3% | 63.8% |  |
| _STORE_SUBSCR | 27,057,280 | 3.1% | 66.8% |  |
| _GUARD_TYPE_VERSION | 19,724,900 | 2.2% | 69.1% |  |
| _GUARD_GLOBALS_VERSION | 16,437,400 | 1.9% | 71.0% |  |
| _GUARD_IS_FALSE_POP | 16,095,980 | 1.8% | 72.8% | 18.5% |
| _LOAD_GLOBAL_MODULE | 15,782,520 | 1.8% | 74.6% |  |
| _ITER_CHECK_LIST | 11,820,260 | 1.3% | 75.9% | 14.3% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,127,420 | 1.3% | 77.2% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,127,420 | 1.3% | 78.5% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 10,126,380 | 1.2% | 79.6% | 22.6% |
| PUSH_NULL | 8,448,520 | 1.0% | 80.6% |  |
| POP_TOP | 7,986,240 | 0.9% | 81.5% |  |
| IS_OP | 7,974,600 | 0.9% | 82.4% |  |
| _ITER_NEXT_LIST | 7,837,580 | 0.9% | 83.3% |  |
| _CHECK_PEP_523 | 7,752,400 | 0.9% | 84.1% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 7,752,400 | 0.9% | 85.0% |  |
| _CHECK_STACK_SPACE | 7,752,400 | 0.9% | 85.9% |  |
| _INIT_CALL_PY_EXACT_ARGS | 7,752,400 | 0.9% | 86.8% |  |
| _PUSH_FRAME | 7,752,400 | 0.9% | 87.7% |  |
| _SAVE_RETURN_OFFSET | 7,752,400 | 0.9% | 88.6% |  |
| _GUARD_IS_TRUE_POP | 7,308,200 | 0.8% | 89.4% | 55.8% |
| CONTAINS_OP | 6,924,960 | 0.8% | 90.2% |  |
| RESUME_CHECK | 6,082,640 | 0.7% | 90.9% |  |
| _GUARD_BOTH_INT | 5,246,600 | 0.6% | 91.5% |  |
| _EXIT_TRACE | 4,898,200 | 0.6% | 92.0% |  |
| _POP_FRAME | 4,786,520 | 0.5% | 92.6% |  |
| _GUARD_DORV_VALUES | 4,443,920 | 0.5% | 93.1% |  |
| _STORE_ATTR_INSTANCE_VALUE | 4,443,920 | 0.5% | 93.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,423,780 | 0.5% | 94.1% |  |
| _BINARY_OP_ADD_INT | 3,943,720 | 0.4% | 94.5% |  |
| TO_BOOL_INT | 3,796,980 | 0.4% | 94.9% |  |
| _GUARD_IS_NOT_NONE_POP | 3,720,240 | 0.4% | 95.4% | 6.0% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,325,560 | 0.4% | 95.8% |  |
| _GUARD_KEYS_VERSION | 3,325,560 | 0.4% | 96.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 3,325,560 | 0.4% | 96.5% |  |
| BINARY_SUBSCR_STR_INT | 2,519,440 | 0.3% | 96.8% | 3.9% |
| CALL_BUILTIN_O | 2,517,800 | 0.3% | 97.1% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 2,510,080 | 0.3% | 97.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 2,510,080 | 0.3% | 97.6% |  |
| COMPARE_OP_STR | 2,505,520 | 0.3% | 97.9% |  |
| CALL_LEN | 1,664,000 | 0.2% | 98.1% |  |
| TO_BOOL_BOOL | 1,370,000 | 0.2% | 98.3% |  |
| _BINARY_OP_SUBTRACT_INT | 1,302,880 | 0.1% | 98.4% |  |
| _BINARY_OP | 1,071,500 | 0.1% | 98.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,023,360 | 0.1% | 98.7% |  |
| STORE_SUBSCR_LIST_INT | 1,016,380 | 0.1% | 98.8% |  |
| _TO_BOOL | 977,940 | 0.1% | 98.9% |  |
| COPY | 836,720 | 0.1% | 99.0% |  |
| UNARY_NOT | 834,560 | 0.1% | 99.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 828,000 | 0.1% | 99.2% |  |
| _CHECK_ATTR_MODULE | 682,240 | 0.1% | 99.3% |  |
| _LOAD_ATTR_MODULE | 682,240 | 0.1% | 99.3% |  |
| _GUARD_BUILTINS_VERSION | 654,880 | 0.1% | 99.4% |  |
| _LOAD_GLOBAL_BUILTINS | 654,880 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_DICT | 619,100 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 587,080 | 0.1% | 99.6% |  |
| BINARY_SLICE | 514,640 | 0.1% | 99.7% |  |
| COMPARE_OP_INT | 418,700 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 372,040 | 0.0% | 99.8% |  |
| _LOAD_ATTR | 342,600 | 0.0% | 99.8% |  |
| CALL_ISINSTANCE | 341,120 | 0.0% | 99.8% |  |
| CALL_TYPE_1 | 304,160 | 0.0% | 99.9% |  |
| TO_BOOL_NONE | 304,080 | 0.0% | 99.9% | 18.9% |
| LIST_APPEND | 249,440 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 249,440 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 178,320 | 0.0% | 100.0% | 100.0% |
| BINARY_SUBSCR_TUPLE_INT | 39,880 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 23,400 | 0.0% | 100.0% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 12,760 | 0.0% | 100.0% | 53.6% |
| _ITER_CHECK_TUPLE | 12,760 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 5,920 | 0.0% | 100.0% |  |
| GET_ITER | 2,340 | 0.0% | 100.0% |  |
| _BINARY_SUBSCR | 2,240 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 2,160 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 1,660 | 0.0% | 100.0% |  |
| BUILD_LIST | 1,480 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 920 |
| BINARY_SUBSCR_GETITEM | 80 |
| CALL_LIST_APPEND | 20 |


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
Stats gathered on: 2023-11-19
