
# Pystats results

- benchmark: regex_compile
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 224,510,740 | 20.6% | 20.6% |  |
| STORE_FAST | 65,879,180 | 6.0% | 26.6% |  |
| POP_JUMP_IF_FALSE | 63,634,440 | 5.8% | 32.4% |  |
| LOAD_GLOBAL_MODULE | 57,079,200 | 5.2% | 37.7% |  |
| LOAD_CONST | 53,275,860 | 4.9% | 42.5% |  |
| LOAD_GLOBAL_BUILTIN | 42,499,440 | 3.9% | 46.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 39,308,200 | 3.6% | 50.0% |  |
| RESUME_CHECK | 34,998,980 | 3.2% | 53.2% |  |
| POP_TOP | 29,890,900 | 2.7% | 56.0% |  |
| PUSH_NULL | 27,873,980 | 2.6% | 58.5% |  |
| LOAD_FAST_LOAD_FAST | 26,667,660 | 2.4% | 61.0% |  |
| EXTENDED_ARG | 25,141,280 | 2.3% | 63.3% |  |
| RETURN_VALUE | 22,464,000 | 2.1% | 65.3% |  |
| CALL_BUILTIN_O | 18,508,960 | 1.7% | 67.0% |  |
| ENTER_EXECUTOR | 16,663,980 | 1.5% | 68.6% |  |
| TO_BOOL_BOOL | 15,028,460 | 1.4% | 69.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,629,160 | 1.3% | 71.3% |  |
| CONTAINS_OP | 14,572,180 | 1.3% | 72.6% |  |
| IS_OP | 13,795,800 | 1.3% | 73.9% |  |
| RETURN_CONST | 13,171,780 | 1.2% | 75.1% |  |
| TO_BOOL_INT | 13,093,220 | 1.2% | 76.3% |  |
| POP_JUMP_IF_TRUE | 12,653,160 | 1.2% | 77.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,868,140 | 1.1% | 78.5% |  |
| CALL_ISINSTANCE | 11,211,660 | 1.0% | 79.5% |  |
| CALL_LEN | 11,019,020 | 1.0% | 80.6% |  |
| COMPARE_OP_STR | 10,767,120 | 1.0% | 81.5% | 1.5% |
| BINARY_OP_ADD_INT | 10,663,220 | 1.0% | 82.5% |  |
| BINARY_OP | 10,458,200 | 1.0% | 83.5% |  |
| CALL_PY_EXACT_ARGS | 10,242,660 | 0.9% | 84.4% |  |
| BINARY_SUBSCR_LIST_INT | 10,134,900 | 0.9% | 85.3% | 12.6% |
| STORE_FAST_STORE_FAST | 9,947,600 | 0.9% | 86.3% |  |
| JUMP_FORWARD | 8,824,900 | 0.8% | 87.1% |  |
| BUILD_TUPLE | 8,294,240 | 0.8% | 87.8% |  |
| INTERPRETER_EXIT | 7,991,280 | 0.7% | 88.6% |  |
| LOAD_ATTR | 7,589,540 | 0.7% | 89.2% |  |
| BINARY_SUBSCR_STR_INT | 6,997,980 | 0.6% | 89.9% | 3.3% |
| CALL | 6,831,700 | 0.6% | 90.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,748,100 | 0.6% | 91.1% |  |
| NOP | 6,082,740 | 0.6% | 91.7% |  |
| GET_ITER | 5,982,180 | 0.5% | 92.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,919,680 | 0.5% | 92.8% |  |
| BINARY_SUBSCR_GETITEM | 5,288,720 | 0.5% | 93.3% |  |
| FOR_ITER | 5,156,420 | 0.5% | 93.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,775,540 | 0.4% | 94.2% |  |
| CALL_LIST_APPEND | 4,252,400 | 0.4% | 94.6% |  |
| BUILD_LIST | 4,059,780 | 0.4% | 94.9% |  |
| POP_JUMP_IF_NOT_NONE | 3,862,100 | 0.4% | 95.3% |  |
| JUMP_BACKWARD | 3,398,320 | 0.3% | 95.6% |  |
| BINARY_OP_SUBTRACT_INT | 3,244,800 | 0.3% | 95.9% |  |
| COPY | 3,039,520 | 0.3% | 96.2% |  |
| FOR_ITER_LIST | 2,972,480 | 0.3% | 96.4% | 2.0% |
| COMPARE_OP_INT | 2,587,180 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 2,497,600 | 0.2% | 96.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 2,446,580 | 0.2% | 97.1% |  |
| TO_BOOL_NONE | 2,382,620 | 0.2% | 97.4% | 5.3% |
| TO_BOOL_LIST | 1,947,020 | 0.2% | 97.5% | 0.9% |
| STORE_SUBSCR_LIST_INT | 1,748,400 | 0.2% | 97.7% |  |
| BINARY_SUBSCR | 1,570,420 | 0.1% | 97.8% |  |
| CALL_BUILTIN_CLASS | 1,506,460 | 0.1% | 98.0% |  |
| FOR_ITER_RANGE | 1,417,260 | 0.1% | 98.1% |  |
| UNARY_NOT | 1,403,120 | 0.1% | 98.2% |  |
| TO_BOOL | 1,335,860 | 0.1% | 98.4% |  |
| BUILD_SLICE | 1,274,480 | 0.1% | 98.5% |  |
| STORE_SUBSCR | 1,233,620 | 0.1% | 98.6% |  |
| LOAD_ATTR_MODULE | 1,112,340 | 0.1% | 98.7% |  |
| BINARY_SUBSCR_DICT | 1,026,000 | 0.1% | 98.8% |  |
| COMPARE_OP | 991,620 | 0.1% | 98.9% |  |
| CALL_TYPE_1 | 906,960 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 840,800 | 0.1% | 99.0% |  |
| TO_BOOL_STR | 799,520 | 0.1% | 99.1% | 1.0% |
| LOAD_ATTR_PROPERTY | 708,480 | 0.1% | 99.2% |  |
| STORE_FAST_LOAD_FAST | 618,560 | 0.1% | 99.2% |  |
| EXIT_INIT_CHECK | 613,040 | 0.1% | 99.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 613,040 | 0.1% | 99.3% |  |
| UNPACK_SEQUENCE_TUPLE | 598,720 | 0.1% | 99.4% |  |
| CHECK_EXC_MATCH | 566,480 | 0.1% | 99.4% |  |
| POP_EXCEPT | 566,480 | 0.1% | 99.5% |  |
| PUSH_EXC_INFO | 566,480 | 0.1% | 99.6% |  |
| CALL_PY_WITH_DEFAULTS | 453,200 | 0.0% | 99.6% |  |
| STORE_SUBSCR_DICT | 449,200 | 0.0% | 99.6% |  |
| BUILD_MAP | 448,880 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 447,840 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 447,840 | 0.0% | 99.8% |  |
| BINARY_OP_MULTIPLY_INT | 445,040 | 0.0% | 99.8% |  |
| BINARY_SLICE | 338,640 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 293,680 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 292,960 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 226,040 | 0.0% | 99.9% |  |
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
| FOR_ITER_TUPLE | 7,780 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,760 | 0.0% | 100.0% |  |
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
| POP_JUMP_IF_FALSE LOAD_FAST | 54,468,600 | 5.0% | 5.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 35,169,100 | 3.2% | 8.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 33,790,000 | 3.1% | 11.3% |
| STORE_FAST LOAD_FAST | 27,975,420 | 2.6% | 13.9% |
| LOAD_FAST PUSH_NULL | 26,358,580 | 2.4% | 16.3% |
| LOAD_FAST LOAD_CONST | 24,528,180 | 2.2% | 18.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 22,541,760 | 2.1% | 20.6% |
| POP_TOP LOAD_FAST | 17,312,420 | 1.6% | 22.2% |
| PUSH_NULL LOAD_FAST | 15,398,000 | 1.4% | 23.6% |
| CALL_BUILTIN_O POP_TOP | 14,890,000 | 1.4% | 25.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 14,771,140 | 1.4% | 26.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 13,562,340 | 1.2% | 27.5% |
| LOAD_GLOBAL_MODULE IS_OP | 13,331,400 | 1.2% | 28.8% |
| RESUME_CHECK LOAD_FAST | 13,094,220 | 1.2% | 30.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 12,353,180 | 1.1% | 31.1% |
| LOAD_FAST CALL_BUILTIN_O | 10,670,400 | 1.0% | 32.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 10,645,840 | 1.0% | 33.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 10,539,900 | 1.0% | 34.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 10,262,180 | 0.9% | 35.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,242,660 | 0.9% | 35.9% |
| IS_OP POP_JUMP_IF_FALSE | 10,054,280 | 0.9% | 36.8% |
| LOAD_CONST BINARY_OP_ADD_INT | 10,049,140 | 0.9% | 37.7% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 9,985,440 | 0.9% | 38.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 9,974,080 | 0.9% | 39.6% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 9,361,520 | 0.9% | 40.4% |
| CACHE RESUME_CHECK | 9,244,080 | 0.8% | 41.3% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 8,836,160 | 0.8% | 42.1% |
| LOAD_CONST COMPARE_OP_STR | 8,834,060 | 0.8% | 42.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 8,757,220 | 0.8% | 43.7% |
| RETURN_CONST POP_TOP | 8,535,440 | 0.8% | 44.5% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 8,423,200 | 0.8% | 45.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 8,197,900 | 0.8% | 46.0% |
| EXTENDED_ARG ENTER_EXECUTOR | 7,921,880 | 0.7% | 46.7% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 7,853,040 | 0.7% | 47.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,724,100 | 0.7% | 48.1% |
| LOAD_FAST LOAD_ATTR | 7,534,340 | 0.7% | 48.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 7,338,040 | 0.7% | 49.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 7,237,380 | 0.7% | 50.2% |
| BINARY_OP TO_BOOL_INT | 7,201,380 | 0.7% | 50.8% |
| BINARY_OP_ADD_INT STORE_FAST | 7,050,720 | 0.6% | 51.5% |
| LOAD_ATTR STORE_FAST | 6,860,420 | 0.6% | 52.1% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 6,748,100 | 0.6% | 52.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,672,340 | 0.6% | 53.3% |
| LOAD_CONST STORE_FAST | 6,635,120 | 0.6% | 53.9% |
| STORE_FAST LOAD_CONST | 6,461,360 | 0.6% | 54.5% |
| RETURN_VALUE INTERPRETER_EXIT | 6,444,320 | 0.6% | 55.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,401,140 | 0.6% | 55.7% |
| LOAD_GLOBAL_MODULE STORE_FAST | 6,364,160 | 0.6% | 56.3% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 6,103,280 | 0.6% | 56.9% |
| LOAD_FAST CALL_LEN | 6,079,500 | 0.6% | 57.4% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 5,898,000 | 0.5% | 58.0% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 5,820,220 | 0.5% | 58.5% |
| LOAD_FAST TO_BOOL_INT | 5,526,080 | 0.5% | 59.0% |
| NOP LOAD_FAST | 5,389,280 | 0.5% | 59.5% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 5,288,720 | 0.5% | 60.0% |
| ENTER_EXECUTOR LOAD_FAST | 5,269,560 | 0.5% | 60.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 5,236,140 | 0.5% | 60.9% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 5,181,120 | 0.5% | 61.4% |
| STORE_FAST NOP | 5,026,100 | 0.5% | 61.9% |
| EXTENDED_ARG JUMP_FORWARD | 4,933,360 | 0.5% | 62.3% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 4,833,060 | 0.4% | 62.8% |
| STORE_FAST STORE_FAST | 4,756,320 | 0.4% | 63.2% |
| EXTENDED_ARG FOR_ITER | 4,679,840 | 0.4% | 63.6% |
| STORE_FAST_STORE_FAST LOAD_FAST | 4,679,380 | 0.4% | 64.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 4,654,000 | 0.4% | 64.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,525,360 | 0.4% | 64.9% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 4,510,340 | 0.4% | 65.3% |
| JUMP_FORWARD EXTENDED_ARG | 4,508,640 | 0.4% | 65.7% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 4,453,760 | 0.4% | 66.1% |
| LOAD_FAST RETURN_VALUE | 4,418,980 | 0.4% | 66.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,237,780 | 0.4% | 66.9% |
| CONTAINS_OP EXTENDED_ARG | 4,138,320 | 0.4% | 67.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 3,935,120 | 0.4% | 67.7% |
| LOAD_GLOBAL_BUILTIN STORE_FAST | 3,914,880 | 0.4% | 68.0% |
| LOAD_CONST BINARY_SUBSCR_STR_INT | 3,865,040 | 0.4% | 68.4% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 3,864,240 | 0.4% | 68.7% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 3,862,100 | 0.4% | 69.1% |
| CALL STORE_FAST | 3,741,300 | 0.3% | 69.4% |
| BINARY_SUBSCR_STR_INT LOAD_CONST | 3,728,400 | 0.3% | 69.8% |
| IS_OP POP_JUMP_IF_TRUE | 3,724,960 | 0.3% | 70.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,703,760 | 0.3% | 70.4% |
| CALL_LEN RETURN_VALUE | 3,683,280 | 0.3% | 70.8% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 3,683,280 | 0.3% | 71.1% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 3,670,240 | 0.3% | 71.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 3,602,000 | 0.3% | 71.8% |
| LOAD_FAST CALL_LIST_APPEND | 3,573,680 | 0.3% | 72.1% |
| CALL_LIST_APPEND RETURN_CONST | 3,573,680 | 0.3% | 72.4% |
| POP_TOP EXTENDED_ARG | 3,570,800 | 0.3% | 72.8% |
| LOAD_FAST LOAD_FAST | 3,515,200 | 0.3% | 73.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 3,471,760 | 0.3% | 73.4% |
| BUILD_LIST STORE_FAST | 3,470,020 | 0.3% | 73.7% |
| PUSH_NULL LOAD_CONST | 3,414,160 | 0.3% | 74.0% |
| JUMP_BACKWARD EXTENDED_ARG | 3,375,840 | 0.3% | 74.3% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 3,335,740 | 0.3% | 74.7% |
| STORE_FAST EXTENDED_ARG | 3,299,600 | 0.3% | 75.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 3,226,420 | 0.3% | 75.3% |
| BUILD_TUPLE CALL_BOUND_METHOD_EXACT_ARGS | 3,204,960 | 0.3% | 75.5% |
| BINARY_OP_ADD_INT LOAD_FAST | 3,185,700 | 0.3% | 75.8% |
| CALL_BUILTIN_O BUILD_TUPLE | 3,123,840 | 0.3% | 76.1% |
| RETURN_VALUE STORE_FAST | 3,086,720 | 0.3% | 76.4% |


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
| BUILD_SLICE | 1,274,480 | 81.2% |
| LOAD_FAST | 165,200 | 10.5% |
| LOAD_CONST | 130,100 | 8.3% |
| BINARY_SUBSCR | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,241,680 | 79.1% |
| CALL_ALLOC_AND_ENTER_INIT | 165,200 | 10.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 130,080 | 8.3% |
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
| LOAD_FAST | 2,720 | 72.3% |
| LOAD_CONST | 1,040 | 27.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,720 | 72.3% |
| ENTER_EXECUTOR | 1,020 | 27.1% |
| JUMP_BACKWARD | 20 | 0.5% |


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
| LOAD_FAST | 2,222,160 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,908,160 | 31.9% |
| BINARY_SUBSCR | 1,241,680 | 20.8% |
| BINARY_SUBSCR_TUPLE_INT | 235,540 | 3.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 223,920 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,035,840 | 50.7% |
| FOR_ITER_RANGE | 1,384,380 | 23.1% |
| FOR_ITER_LIST | 1,072,400 | 17.9% |
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
| STORE_FAST | 5,026,100 | 82.6% |
| POP_JUMP_IF_FALSE | 501,500 | 8.2% |
| NOP | 173,240 | 2.8% |
| STORE_FAST_STORE_FAST | 173,120 | 2.8% |
| RESUME_CHECK | 115,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,389,280 | 88.6% |
| LOAD_FAST_LOAD_FAST | 289,520 | 4.8% |
| NOP | 173,240 | 2.8% |
| LOAD_CONST | 92,320 | 1.5% |
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
| CALL_BUILTIN_O | 14,890,000 | 49.8% |
| RETURN_CONST | 8,535,440 | 28.6% |
| ENTER_EXECUTOR | 2,921,240 | 9.8% |
| RETURN_VALUE | 1,848,000 | 6.2% |
| POP_JUMP_IF_FALSE | 1,113,320 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,312,420 | 57.9% |
| EXTENDED_ARG | 3,570,800 | 11.9% |
| JUMP_BACKWARD | 2,850,320 | 9.5% |
| ENTER_EXECUTOR | 1,615,200 | 5.4% |
| RETURN_CONST | 1,562,860 | 5.2% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 341,520 | 60.3% |
| BINARY_SUBSCR_STR_INT | 223,920 | 39.5% |
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
| LOAD_FAST | 26,358,580 | 94.6% |
| LOAD_ATTR_MODULE | 896,580 | 3.2% |
| STORE_FAST_LOAD_FAST | 618,560 | 2.2% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,398,000 | 55.2% |
| LOAD_GLOBAL_MODULE | 5,898,000 | 21.2% |
| LOAD_CONST | 3,414,160 | 12.2% |
| LOAD_FAST_LOAD_FAST | 1,668,380 | 6.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,387,840 | 5.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 8,423,200 | 37.5% |
| LOAD_FAST | 4,418,980 | 19.7% |
| CALL_LEN | 3,683,280 | 16.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,598,240 | 7.1% |
| BINARY_OP_SUBTRACT_INT | 808,400 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 6,444,320 | 28.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 6,103,280 | 27.2% |
| STORE_FAST | 3,086,720 | 13.7% |
| POP_TOP | 1,848,000 | 8.2% |
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
| ENTER_EXECUTOR | 35,400 | 2.9% |
| LOAD_FAST_LOAD_FAST | 21,200 | 1.7% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 824,500 | 61.7% |
| BINARY_OP | 223,920 | 16.8% |
| LOAD_ATTR | 223,920 | 16.8% |
| ENTER_EXECUTOR | 57,080 | 4.3% |
| TO_BOOL | 4,540 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,033,520 | 77.4% |
| POP_JUMP_IF_TRUE | 295,860 | 22.1% |
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
| LOAD_GLOBAL_MODULE | 8,757,220 | 83.7% |
| LOAD_FAST_LOAD_FAST | 731,440 | 7.0% |
| LOAD_FAST | 234,120 | 2.2% |
| RETURN_VALUE | 224,980 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 223,920 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 7,201,380 | 68.9% |
| STORE_FAST | 1,827,040 | 17.5% |
| LOAD_FAST | 387,760 | 3.7% |
| TO_BOOL | 223,920 | 2.1% |
| CALL | 223,920 | 2.1% |


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
| POP_JUMP_IF_FALSE | 288,820 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,470,020 | 85.5% |
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
| CALL_BUILTIN_O | 3,123,840 | 37.7% |
| LOAD_FAST_LOAD_FAST | 1,744,320 | 21.0% |
| CALL | 1,431,200 | 17.3% |
| LOAD_FAST | 662,480 | 8.0% |
| BUILD_TUPLE | 495,120 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 3,204,960 | 38.6% |
| LOAD_FAST | 1,596,400 | 19.2% |
| CALL_BUILTIN_O | 806,880 | 9.7% |
| RETURN_VALUE | 564,480 | 6.8% |
| BUILD_TUPLE | 495,120 | 6.0% |


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
| LOAD_GLOBAL_MODULE | 8,836,160 | 60.6% |
| LOAD_FAST_LOAD_FAST | 4,453,760 | 30.6% |
| LOAD_CONST | 1,281,220 | 8.8% |
| LOAD_FAST | 1,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,262,180 | 70.4% |
| EXTENDED_ARG | 4,138,320 | 28.4% |
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
| EXTENDED_ARG | 7,921,880 | 47.5% |
| POP_JUMP_IF_TRUE | 3,471,760 | 20.8% |
| STORE_FAST | 2,157,440 | 12.9% |
| POP_TOP | 1,615,200 | 9.7% |
| STORE_SUBSCR_LIST_INT | 1,084,560 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,269,560 | 31.6% |
| BINARY_SUBSCR_GETITEM | 2,992,460 | 18.0% |
| POP_TOP | 2,921,240 | 17.5% |
| RESUME_CHECK | 1,700,560 | 10.2% |
| EXTENDED_ARG | 1,491,120 | 8.9% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 4,508,640 | 17.9% |
| CONTAINS_OP | 4,138,320 | 16.5% |
| POP_TOP | 3,570,800 | 14.2% |
| JUMP_BACKWARD | 3,375,840 | 13.4% |
| STORE_FAST | 3,299,600 | 13.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,921,880 | 31.5% |
| POP_JUMP_IF_FALSE | 5,181,120 | 20.6% |
| JUMP_FORWARD | 4,933,360 | 19.6% |
| FOR_ITER | 4,679,840 | 18.6% |
| FOR_ITER_LIST | 1,898,320 | 7.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 4,679,840 | 90.8% |
| GET_ITER | 449,160 | 8.7% |
| JUMP_BACKWARD | 20,680 | 0.4% |
| FOR_ITER | 5,620 | 0.1% |
| FOR_ITER_LIST | 1,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,335,740 | 64.7% |
| RETURN_CONST | 1,344,100 | 26.1% |
| LOAD_FAST | 223,920 | 4.3% |
| LOAD_GLOBAL_MODULE | 223,920 | 4.3% |
| STORE_FAST | 21,220 | 0.4% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,331,400 | 96.6% |
| LOAD_FAST | 223,920 | 1.6% |
| LOAD_GLOBAL_BUILTIN | 223,920 | 1.6% |
| LOAD_CONST | 16,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,054,280 | 72.9% |
| POP_JUMP_IF_TRUE | 3,724,960 | 27.0% |
| COPY | 16,320 | 0.1% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,850,320 | 83.9% |
| EXTENDED_ARG | 526,760 | 15.5% |
| POP_JUMP_IF_TRUE | 19,520 | 0.6% |
| ENTER_EXECUTOR | 1,020 | 0.0% |
| POP_JUMP_IF_FALSE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,375,840 | 99.3% |
| FOR_ITER | 20,680 | 0.6% |
| NOP | 620 | 0.0% |
| FOR_ITER_LIST | 620 | 0.0% |
| ENTER_EXECUTOR | 220 | 0.0% |


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
| LOAD_GLOBAL_MODULE | 381,780 | 4.3% |
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
| LOAD_FAST | 7,534,340 | 99.3% |
| LOAD_GLOBAL_BUILTIN | 51,440 | 0.7% |
| LOAD_ATTR | 3,100 | 0.0% |
| LOAD_GLOBAL_MODULE | 500 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,860,420 | 90.4% |
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
| LOAD_FAST | 24,528,180 | 46.0% |
| STORE_FAST | 6,461,360 | 12.1% |
| BINARY_SUBSCR_STR_INT | 3,728,400 | 7.0% |
| PUSH_NULL | 3,414,160 | 6.4% |
| LOAD_CONST | 2,858,960 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 10,049,140 | 18.9% |
| COMPARE_OP_STR | 8,834,060 | 16.6% |
| STORE_FAST | 6,635,120 | 12.5% |
| BINARY_SUBSCR_STR_INT | 3,865,040 | 7.3% |
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
| POP_JUMP_IF_FALSE | 54,468,600 | 24.3% |
| STORE_FAST | 27,975,420 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 22,541,760 | 10.0% |
| POP_TOP | 17,312,420 | 7.7% |
| PUSH_NULL | 15,398,000 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 35,169,100 | 15.7% |
| LOAD_GLOBAL_MODULE | 33,790,000 | 15.1% |
| PUSH_NULL | 26,358,580 | 11.7% |
| LOAD_CONST | 24,528,180 | 10.9% |
| CALL_BUILTIN_O | 10,670,400 | 4.8% |


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
| RESUME_CHECK | 3,935,120 | 14.8% |
| STORE_FAST_STORE_FAST | 3,864,240 | 14.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,226,420 | 12.1% |
| LOAD_GLOBAL_MODULE | 2,833,740 | 10.6% |
| LOAD_GLOBAL_BUILTIN | 2,273,680 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 6,672,340 | 25.0% |
| CONTAINS_OP | 4,453,760 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,010,400 | 11.3% |
| CALL | 1,824,040 | 6.8% |
| BUILD_TUPLE | 1,744,320 | 6.5% |


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
| TO_BOOL_BOOL | 12,353,180 | 19.4% |
| CONTAINS_OP | 10,262,180 | 16.1% |
| IS_OP | 10,054,280 | 15.8% |
| COMPARE_OP_STR | 9,985,440 | 15.7% |
| TO_BOOL_INT | 7,853,040 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,468,600 | 85.6% |
| LOAD_GLOBAL_MODULE | 2,519,280 | 4.0% |
| LOAD_CONST | 1,156,880 | 1.8% |
| POP_TOP | 1,113,320 | 1.7% |
| LOAD_FAST_LOAD_FAST | 1,058,400 | 1.7% |


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
| LOAD_FAST | 3,862,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,637,700 | 42.4% |
| BUILD_LIST | 1,333,840 | 34.5% |
| LOAD_GLOBAL_BUILTIN | 421,360 | 10.9% |
| LOAD_GLOBAL_MODULE | 223,920 | 5.8% |
| LOAD_FAST_LOAD_FAST | 165,200 | 4.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 4,833,060 | 38.2% |
| IS_OP | 3,724,960 | 29.4% |
| TO_BOOL_BOOL | 2,411,040 | 19.1% |
| TO_BOOL_STR | 798,720 | 6.3% |
| TO_BOOL_LIST | 338,900 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,401,140 | 50.6% |
| ENTER_EXECUTOR | 3,471,760 | 27.4% |
| CALL_LEN | 799,040 | 6.3% |
| JUMP_FORWARD | 407,120 | 3.2% |
| LOAD_GLOBAL_MODULE | 387,840 | 3.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 4,510,340 | 34.2% |
| CALL_LIST_APPEND | 3,573,680 | 27.1% |
| POP_TOP | 1,562,860 | 11.9% |
| FOR_ITER | 1,344,100 | 10.2% |
| POP_JUMP_IF_FALSE | 987,680 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,535,440 | 64.8% |
| TO_BOOL_BOOL | 2,025,720 | 15.4% |
| INTERPRETER_EXIT | 1,546,960 | 11.7% |
| EXIT_INIT_CHECK | 613,040 | 4.7% |
| STORE_FAST | 450,580 | 3.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 7,050,720 | 10.7% |
| LOAD_ATTR | 6,860,420 | 10.4% |
| LOAD_CONST | 6,635,120 | 10.1% |
| LOAD_GLOBAL_MODULE | 6,364,160 | 9.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,820,220 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,975,420 | 42.5% |
| LOAD_GLOBAL_MODULE | 7,338,040 | 11.1% |
| LOAD_CONST | 6,461,360 | 9.8% |
| LOAD_GLOBAL_BUILTIN | 5,236,140 | 7.9% |
| NOP | 5,026,100 | 7.6% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 8,197,900 | 82.4% |
| COPY | 1,431,200 | 14.4% |
| UNPACK_SEQUENCE_TUPLE | 285,760 | 2.9% |
| STORE_FAST_STORE_FAST | 32,720 | 0.3% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,679,380 | 47.0% |
| LOAD_FAST_LOAD_FAST | 3,864,240 | 38.8% |
| LOAD_GLOBAL_BUILTIN | 912,000 | 9.2% |
| STORE_FAST | 253,040 | 2.5% |
| NOP | 173,120 | 1.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 32,800 | 30.6% |
| ENTER_EXECUTOR | 32,800 | 30.6% |
| LOAD_FAST_AND_CLEAR | 32,800 | 30.6% |
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
| LOAD_CONST | 10,049,140 | 94.2% |
| LOAD_FAST_LOAD_FAST | 430,240 | 4.0% |
| BINARY_OP_MULTIPLY_INT | 183,840 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,050,720 | 66.1% |
| LOAD_FAST | 3,185,700 | 29.9% |
| CALL_PY_EXACT_ARGS | 183,200 | 1.7% |
| CALL_BUILTIN_O | 130,080 | 1.2% |
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
| LOAD_FAST | 1,595,360 | 49.2% |
| LOAD_CONST | 841,040 | 25.9% |
| CALL_LEN | 808,400 | 24.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,445,760 | 44.6% |
| RETURN_VALUE | 808,400 | 24.9% |
| LOAD_FAST | 341,520 | 10.5% |
| LOAD_CONST | 292,160 | 9.0% |
| STORE_FAST | 236,080 | 7.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 487,760 | 47.5% |
| BUILD_TUPLE | 341,520 | 33.3% |
| LOAD_FAST_LOAD_FAST | 196,720 | 19.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 341,520 | 33.3% |
| CALL_BUILTIN_O | 253,760 | 24.7% |
| RETURN_VALUE | 223,920 | 21.8% |
| LOAD_CONST | 189,120 | 18.4% |
| STORE_FAST | 8,800 | 0.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,992,460 | 56.6% |
| LOAD_FAST | 1,240,080 | 23.4% |
| LOAD_CONST | 1,056,180 | 20.0% |

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
| LOAD_CONST | 486,000 | 4.8% |
| LOAD_FAST_LOAD_FAST | 175,520 | 1.7% |
| BINARY_OP_SUBTRACT_INT | 87,760 | 0.9% |
| BINARY_SUBSCR_LIST_INT | 24,080 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,423,200 | 94.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 116,260 | 1.3% |
| STORE_FAST | 94,720 | 1.1% |
| LOAD_FAST_LOAD_FAST | 87,760 | 1.0% |
| COMPARE_OP_INT | 87,760 | 1.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,865,040 | 55.2% |
| LOAD_FAST | 3,030,980 | 43.3% |
| ENTER_EXECUTOR | 97,600 | 1.4% |
| BINARY_SUBSCR_STR_INT | 4,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,728,400 | 53.3% |
| STORE_FAST | 2,614,740 | 37.4% |
| BINARY_OP_INPLACE_ADD_UNICODE | 289,520 | 4.1% |
| PUSH_EXC_INFO | 223,920 | 3.2% |
| CALL_BUILTIN_O | 137,040 | 2.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,446,580 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 805,920 | 32.9% |
| CALL_BUILTIN_O | 585,280 | 23.9% |
| GET_ITER | 235,540 | 9.6% |
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
| BUILD_TUPLE | 3,204,960 | 47.5% |
| LOAD_CONST | 1,879,720 | 27.9% |
| PUSH_NULL | 1,387,840 | 20.6% |
| LOAD_FAST | 275,200 | 4.1% |
| BINARY_SUBSCR_LIST_INT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,748,100 | 100.0% |


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
| LOAD_FAST | 10,670,400 | 57.6% |
| LOAD_GLOBAL_MODULE | 1,999,600 | 10.8% |
| LOAD_CONST | 1,534,400 | 8.3% |
| RETURN_VALUE | 1,241,680 | 6.7% |
| CALL_LEN | 1,018,960 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,890,000 | 80.4% |
| BUILD_TUPLE | 3,123,840 | 16.9% |
| TO_BOOL_BOOL | 357,040 | 1.9% |
| STORE_FAST | 138,080 | 0.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 9,974,080 | 89.0% |
| BUILD_TUPLE | 447,840 | 4.0% |
| LOAD_GLOBAL_MODULE | 341,900 | 3.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 223,920 | 2.0% |
| LOAD_ATTR_SLOT | 223,920 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,539,900 | 94.0% |
| RETURN_VALUE | 447,840 | 4.0% |
| LOAD_FAST | 223,920 | 2.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,079,500 | 55.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,683,280 | 33.4% |
| POP_JUMP_IF_TRUE | 799,040 | 7.3% |
| LOAD_GLOBAL_MODULE | 447,840 | 4.1% |
| LOAD_CONST | 9,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,683,280 | 33.4% |
| LOAD_FAST | 1,531,600 | 13.9% |
| CALL_BUILTIN_CLASS | 1,348,640 | 12.2% |
| LOAD_CONST | 1,063,100 | 9.6% |
| CALL_BUILTIN_O | 1,018,960 | 9.2% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,573,680 | 84.0% |
| BUILD_TUPLE | 307,920 | 7.2% |
| LOAD_GLOBAL_MODULE | 223,920 | 5.3% |
| LOAD_CONST | 130,080 | 3.1% |
| ENTER_EXECUTOR | 16,800 | 0.4% |

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
| LOAD_ATTR_METHOD_NO_DICT | 225,640 | 99.8% |
| LOAD_ATTR | 340 | 0.2% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 223,920 | 99.1% |
| POP_TOP | 1,080 | 0.5% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 4,237,780 | 41.4% |
| LOAD_FAST | 2,288,000 | 22.3% |
| LOAD_FAST_LOAD_FAST | 1,334,880 | 13.0% |
| UNARY_NOT | 996,000 | 9.7% |
| LOAD_CONST | 406,800 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,242,660 | 100.0% |


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
| LOAD_FAST | 906,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 683,040 | 75.3% |
| LOAD_FAST | 223,920 | 24.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,749,260 | 67.6% |
| LOAD_GLOBAL_MODULE | 577,920 | 22.3% |
| CALL_LEN | 141,360 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 87,760 | 3.4% |
| LOAD_FAST | 29,340 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,584,860 | 99.9% |
| POP_JUMP_IF_TRUE | 2,080 | 0.1% |
| COPY | 240 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,834,060 | 82.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,927,260 | 17.9% |
| COMPARE_OP | 3,160 | 0.0% |
| LOAD_FAST | 2,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,985,440 | 92.7% |
| EXTENDED_ARG | 778,560 | 7.2% |
| COMPARE_OP | 3,120 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 1,898,320 | 63.9% |
| GET_ITER | 1,072,400 | 36.1% |
| FOR_ITER | 1,140 | 0.0% |
| JUMP_BACKWARD | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,294,520 | 77.2% |
| STORE_FAST | 505,920 | 17.0% |
| LOAD_FAST_LOAD_FAST | 108,320 | 3.6% |
| RETURN_CONST | 60,780 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 1,760 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,384,380 | 97.7% |
| SWAP | 32,800 | 2.3% |
| JUMP_BACKWARD | 60 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,390,700 | 98.1% |
| LOAD_FAST | 26,480 | 1.9% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,600 | 97.7% |
| JUMP_BACKWARD | 180 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,600 | 97.7% |
| JUMP_BACKWARD | 180 | 2.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,169,100 | 89.5% |
| LOAD_FAST_LOAD_FAST | 3,010,400 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,119,840 | 2.8% |
| COPY | 8,800 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,562,340 | 34.5% |
| STORE_FAST | 5,820,220 | 14.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,703,760 | 9.4% |
| CALL_LEN | 3,683,280 | 9.4% |
| COMPARE_OP_STR | 1,927,260 | 4.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,703,760 | 62.6% |
| LOAD_FAST | 1,375,920 | 23.2% |
| LOAD_GLOBAL_MODULE | 838,920 | 14.2% |
| CALL | 1,040 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,654,000 | 78.6% |
| LOAD_GLOBAL_MODULE | 441,840 | 7.5% |
| LOAD_CONST | 423,760 | 7.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 225,640 | 3.8% |
| LOAD_FAST_LOAD_FAST | 174,400 | 2.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,525,360 | 94.8% |
| BINARY_SUBSCR | 130,080 | 2.7% |
| BINARY_SUBSCR_TUPLE_INT | 119,040 | 2.5% |
| LOAD_FAST_LOAD_FAST | 1,040 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,237,780 | 88.7% |
| LOAD_FAST | 261,440 | 5.5% |
| LOAD_CONST | 183,920 | 3.9% |
| LOAD_GLOBAL_MODULE | 92,140 | 1.9% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,112,240 | 100.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 896,580 | 80.6% |
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
| RESUME_CHECK | 14,771,140 | 34.8% |
| LOAD_FAST | 10,645,840 | 25.0% |
| STORE_FAST | 5,236,140 | 12.3% |
| JUMP_FORWARD | 2,097,280 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 1,774,320 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,541,760 | 53.0% |
| CALL_ISINSTANCE | 9,974,080 | 23.5% |
| STORE_FAST | 3,914,880 | 9.2% |
| LOAD_FAST_LOAD_FAST | 2,273,680 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,774,320 | 4.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,790,000 | 59.2% |
| STORE_FAST | 7,338,040 | 12.9% |
| PUSH_NULL | 5,898,000 | 10.3% |
| POP_JUMP_IF_FALSE | 2,519,280 | 4.4% |
| RESUME_CHECK | 1,917,280 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 13,331,400 | 23.4% |
| CONTAINS_OP | 8,836,160 | 15.5% |
| BINARY_OP | 8,757,220 | 15.3% |
| LOAD_FAST | 7,237,380 | 12.7% |
| STORE_FAST | 6,364,160 | 11.1% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,242,660 | 29.3% |
| CACHE | 9,244,080 | 26.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,748,100 | 19.3% |
| BINARY_SUBSCR_GETITEM | 5,288,720 | 15.1% |
| ENTER_EXECUTOR | 1,700,560 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 14,771,140 | 42.2% |
| LOAD_FAST | 13,094,220 | 37.4% |
| LOAD_FAST_LOAD_FAST | 3,935,120 | 11.2% |
| LOAD_GLOBAL_MODULE | 1,917,280 | 5.5% |
| BUILD_LIST | 833,280 | 2.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,724,100 | 52.8% |
| LOAD_FAST_LOAD_FAST | 6,672,340 | 45.6% |
| LOAD_ATTR_INSTANCE_VALUE | 223,920 | 1.5% |
| SWAP | 8,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,510,340 | 30.8% |
| LOAD_FAST | 3,602,000 | 24.6% |
| LOAD_FAST_LOAD_FAST | 3,226,420 | 22.1% |
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
| LOAD_FAST_LOAD_FAST | 1,533,520 | 87.7% |
| LOAD_FAST | 214,880 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,084,560 | 62.0% |
| RETURN_CONST | 352,960 | 20.2% |
| EXTENDED_ARG | 286,960 | 16.4% |
| LOAD_FAST | 23,920 | 1.4% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 10,539,900 | 70.1% |
| RETURN_CONST | 2,025,720 | 13.5% |
| LOAD_FAST | 763,440 | 5.1% |
| RETURN_VALUE | 606,080 | 4.0% |
| COPY | 423,680 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,353,180 | 82.2% |
| POP_JUMP_IF_TRUE | 2,411,040 | 16.0% |
| EXTENDED_ARG | 264,240 | 1.8% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 7,201,380 | 55.0% |
| LOAD_FAST | 5,526,080 | 42.2% |
| COPY | 365,760 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,853,040 | 60.0% |
| POP_JUMP_IF_TRUE | 4,833,060 | 36.9% |
| UNARY_NOT | 407,120 | 3.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,830,680 | 94.0% |
| LOAD_ATTR_INSTANCE_VALUE | 116,020 | 6.0% |
| TO_BOOL_NONE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNARY_NOT | 996,000 | 51.2% |
| POP_JUMP_IF_FALSE | 611,800 | 31.4% |
| POP_JUMP_IF_TRUE | 338,900 | 17.4% |
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
| RETURN_VALUE | 6,103,280 | 51.4% |
| FOR_ITER | 3,335,740 | 28.1% |
| FOR_ITER_LIST | 2,294,520 | 19.3% |
| BINARY_SUBSCR_LIST_INT | 116,260 | 1.0% |
| LOAD_CONST | 18,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 8,197,900 | 69.1% |
| STORE_FAST | 3,670,240 | 30.9% |


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
|     deferred | 10,452,040 | 41.6% |
|          hit | 14,646,080 | 58.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 0.6% |
| Failure | 6,120 | 99.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 4,340 | 70.9% |
| or | 840 | 13.7% |
| add other | 420 | 6.9% |
| multiply different types | 260 | 4.2% |
| add different types | 100 | 1.6% |
| and different types | 100 | 1.6% |
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
|     deferred | 1,541,320 | 5.6% |
|          hit | 24,385,020 | 88.8% |
|         miss | 1,509,160 | 5.5% |

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
|     deferred | 6,827,940 | 8.4% |
|          hit | 74,052,760 | 91.5% |
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
|     deferred | 981,300 | 6.8% |
|          hit | 13,188,520 | 91.9% |
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
|     deferred | 5,148,520 | 53.9% |
|          hit | 4,338,160 | 45.4% |
|         miss | 59,360 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,160 | 14.7% |
| Failure | 6,740 | 85.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| seq iter | 6,460 | 95.8% |
| dict keys | 100 | 1.5% |
| dict items | 100 | 1.5% |
| map | 80 | 1.2% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,586,220 | 12.6% |
|          hit | 52,719,920 | 87.4% |

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
|          hit | 99,578,640 | 100.0% |

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
|          hit | 14,629,160 | 100.0% |


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
|          hit | 2,197,600 | 64.0% |

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
|     deferred | 1,326,560 | 3.8% |
|          hit | 33,100,200 | 95.7% |
|         miss | 150,640 | 0.4% |

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
|          hit | 12,466,860 | 100.0% |

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
| Basic | 598,038,120 | 54.8% |
| Not specialized | 118,493,100 | 10.9% |
| Specialized hits | 373,260,840 | 34.2% |
| Specialized misses | 1,937,360 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 10,452,040 | 29.8% |
| LOAD_ATTR | 7,586,220 | 21.6% |
| CALL | 6,827,940 | 19.5% |
| FOR_ITER | 5,148,520 | 14.7% |
| BINARY_SUBSCR | 1,541,320 | 4.4% |
| TO_BOOL | 1,326,560 | 3.8% |
| STORE_SUBSCR | 1,232,800 | 3.5% |
| COMPARE_OP | 981,300 | 2.8% |
| LOAD_GLOBAL | 180 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 1,276,880 | 65.9% |
| BINARY_SUBSCR_STR_INT | 232,280 | 12.0% |
| COMPARE_OP_STR | 165,780 | 8.6% |
| TO_BOOL_NONE | 125,520 | 6.5% |
| FOR_ITER_LIST | 59,360 | 3.1% |
| CALL_BUILTIN_FAST | 52,420 | 2.7% |
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
| Calls to Python functions inlined | 24,054,400 | 72.2% |
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
| Allocations | 62,948,780 | 73.7% |
| Allocations to 512 bytes | 62,906,640 | 73.7% |
| Allocations to 4 kbytes | 40,060 | 0.0% |
| Allocations over 4 kbytes | 2,080 | 0.0% |
| Frees | 65,641,500 |  |
| New values | 1,333,840 |  |
| Interpreter increfs | 564,402,180 | 83.8% |
| Interpreter decrefs | 610,755,640 | 80.7% |
| Increfs | 109,273,753 | 16.2% |
| Decrefs | 146,472,913 | 19.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 8,207,065 |  |
| Method cache misses | 115 |  |
| Method cache collisions | 837 |  |
| Method cache dunder hits | 20,381,602 |  |
| Method cache dunder misses | 738 |  |


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
| Optimization attempts | 280 |  |
| Traces created | 220 | 78.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 100 | 35.7% |
| Trace too short | 60 | 21.4% |
| Inner loop found | 20 | 7.1% |
| Recursive call | 0 | 0.0% |
| Traces executed | 16,663,980 |  |
| Uops executed | 902,410,100 | 54.15 |

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
| <= 32 | 80 | 36.4% |
| <= 64 | 40 | 18.2% |
| <= 128 | 100 | 45.5% |


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
| <= 16 | 60 | 27.3% |
| <= 32 | 40 | 18.2% |
| <= 64 | 20 | 9.1% |
| <= 128 | 100 | 45.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 166,480 | 1.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 3,453,920 | 20.7% |
| <= 16 | 4,420,540 | 26.5% |
| <= 32 | 2,611,940 | 15.7% |
| <= 64 | 3,044,800 | 18.3% |
| <= 128 | 2,791,900 | 16.8% |
| <= 256 | 94,160 | 0.6% |
| <= 512 | 41,920 | 0.3% |
| <= 1,024 | 36,640 | 0.2% |
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
| _SET_IP | 194,784,200 | 21.6% | 21.6% |  |
| LOAD_FAST | 134,178,020 | 14.9% | 36.5% |  |
| _POP_JUMP_IF_TRUE | 59,527,600 | 6.6% | 43.1% |  |
| STORE_FAST | 53,602,740 | 5.9% | 49.0% |  |
| LOAD_CONST | 41,768,120 | 4.6% | 53.6% |  |
| _ITER_CHECK_RANGE | 31,134,880 | 3.5% | 57.1% |  |
| _IS_ITER_EXHAUSTED_RANGE | 31,134,880 | 3.5% | 60.5% |  |
| _ITER_NEXT_RANGE | 29,744,640 | 3.3% | 63.8% |  |
| _JUMP_TO_TOP | 28,777,200 | 3.2% | 67.0% |  |
| _STORE_SUBSCR | 27,057,280 | 3.0% | 70.0% |  |
| _GUARD_TYPE_VERSION | 19,725,540 | 2.2% | 72.2% |  |
| _EXIT_TRACE | 16,342,460 | 1.8% | 74.0% |  |
| _GUARD_GLOBALS_VERSION | 15,587,180 | 1.7% | 75.7% |  |
| _LOAD_GLOBAL_MODULE | 14,933,520 | 1.7% | 77.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,109,160 | 1.2% | 78.6% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,109,160 | 1.2% | 79.8% |  |
| _ITER_CHECK_LIST | 9,611,580 | 1.1% | 80.9% | 1.7% |
| _IS_ITER_EXHAUSTED_LIST | 9,445,100 | 1.0% | 82.0% |  |
| POP_TOP | 8,385,760 | 0.9% | 82.9% |  |
| IS_OP | 7,959,800 | 0.9% | 83.8% |  |
| _CHECK_PEP_523 | 7,754,960 | 0.9% | 84.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 7,754,960 | 0.9% | 85.5% |  |
| _CHECK_STACK_SPACE | 7,754,960 | 0.9% | 86.3% |  |
| _INIT_CALL_PY_EXACT_ARGS | 7,754,960 | 0.9% | 87.2% |  |
| _PUSH_FRAME | 7,754,960 | 0.9% | 88.1% |  |
| _SAVE_RETURN_OFFSET | 7,754,960 | 0.9% | 88.9% |  |
| _ITER_NEXT_LIST | 7,266,500 | 0.8% | 89.7% |  |
| PUSH_NULL | 7,261,220 | 0.8% | 90.5% |  |
| CONTAINS_OP | 6,179,500 | 0.7% | 91.2% |  |
| RESUME_CHECK | 6,054,400 | 0.7% | 91.9% |  |
| _GUARD_BOTH_INT | 4,922,780 | 0.5% | 92.4% |  |
| _POP_FRAME | 4,777,900 | 0.5% | 93.0% |  |
| _POP_JUMP_IF_FALSE | 4,622,660 | 0.5% | 93.5% |  |
| _GUARD_DORV_VALUES | 4,443,960 | 0.5% | 94.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 4,443,960 | 0.5% | 94.5% |  |
| _IS_NONE | 3,898,620 | 0.4% | 94.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,852,640 | 0.4% | 95.3% |  |
| _BINARY_OP_ADD_INT | 3,631,900 | 0.4% | 95.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,356,380 | 0.4% | 96.1% |  |
| _GUARD_KEYS_VERSION | 3,356,380 | 0.4% | 96.5% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 3,356,380 | 0.4% | 96.8% |  |
| BINARY_SUBSCR_STR_INT | 2,510,780 | 0.3% | 97.1% | 3.9% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 2,483,020 | 0.3% | 97.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 2,483,020 | 0.3% | 97.7% |  |
| COMPARE_OP_STR | 2,451,100 | 0.3% | 97.9% |  |
| CALL_LEN | 1,662,740 | 0.2% | 98.1% |  |
| CALL_BUILTIN_O | 1,357,520 | 0.2% | 98.3% |  |
| _BINARY_OP_SUBTRACT_INT | 1,290,880 | 0.1% | 98.4% |  |
| TO_BOOL_BOOL | 1,256,420 | 0.1% | 98.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,023,420 | 0.1% | 98.7% |  |
| STORE_SUBSCR_LIST_INT | 1,016,400 | 0.1% | 98.8% |  |
| TO_BOOL_INT | 1,003,820 | 0.1% | 98.9% |  |
| _TO_BOOL | 977,980 | 0.1% | 99.0% |  |
| COPY | 836,720 | 0.1% | 99.1% |  |
| UNARY_NOT | 834,560 | 0.1% | 99.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 816,040 | 0.1% | 99.3% |  |
| _CHECK_ATTR_MODULE | 682,280 | 0.1% | 99.4% |  |
| _LOAD_ATTR_MODULE | 682,280 | 0.1% | 99.4% |  |
| _GUARD_BUILTINS_VERSION | 653,660 | 0.1% | 99.5% |  |
| _LOAD_GLOBAL_BUILTINS | 653,660 | 0.1% | 99.6% |  |
| BINARY_SUBSCR_LIST_INT | 587,100 | 0.1% | 99.6% |  |
| BINARY_SLICE | 514,640 | 0.1% | 99.7% |  |
| _BINARY_OP | 435,020 | 0.0% | 99.7% |  |
| COMPARE_OP_INT | 417,460 | 0.0% | 99.8% |  |
| _LOAD_ATTR | 342,640 | 0.0% | 99.8% |  |
| CALL_ISINSTANCE | 341,140 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 312,960 | 0.0% | 99.9% |  |
| TO_BOOL_NONE | 304,080 | 0.0% | 99.9% | 18.9% |
| LIST_APPEND | 249,440 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 249,440 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 47,660 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 16,800 | 0.0% | 100.0% |  |
| _ITER_CHECK_TUPLE | 12,780 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 12,780 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 5,920 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 2,460 | 0.0% | 100.0% |  |
| GET_ITER | 2,380 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 2,160 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 1,680 | 0.0% | 100.0% |  |
| BUILD_LIST | 1,500 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 60 |
| BINARY_SUBSCR_GETITEM | 40 |
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
Stats gathered on: 2023-11-08
