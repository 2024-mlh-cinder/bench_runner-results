
# Pystats results

- benchmark: genshi
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 52776df
- commit date: 2023-10-17T21:47:13-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 284,968,380 | 18.7% | 18.7% |  |
| STORE_FAST | 103,776,000 | 6.8% | 25.6% |  |
| LOAD_GLOBAL_MODULE | 102,359,960 | 6.7% | 32.3% | 0.0% |
| POP_JUMP_IF_FALSE | 97,453,380 | 6.4% | 38.7% |  |
| RESUME_CHECK | 86,499,720 | 5.7% | 44.4% | 0.0% |
| IS_OP | 71,966,880 | 4.7% | 49.1% |  |
| POP_TOP | 71,920,980 | 4.7% | 53.8% |  |
| JUMP_BACKWARD | 61,712,880 | 4.1% | 57.9% |  |
| YIELD_VALUE | 57,069,420 | 3.8% | 61.7% |  |
| LOAD_CONST | 56,976,420 | 3.7% | 65.4% |  |
| FOR_ITER_GEN | 45,607,840 | 3.0% | 68.4% | 0.0% |
| LOAD_FAST_LOAD_FAST | 37,366,260 | 2.5% | 70.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 31,086,240 | 2.0% | 72.9% |  |
| EXTENDED_ARG | 30,134,820 | 2.0% | 74.9% |  |
| RETURN_VALUE | 25,707,180 | 1.7% | 76.6% |  |
| PUSH_NULL | 25,039,860 | 1.6% | 78.2% |  |
| LOAD_GLOBAL_BUILTIN | 20,032,280 | 1.3% | 79.5% | 0.0% |
| TO_BOOL_BOOL | 16,870,920 | 1.1% | 80.6% |  |
| BUILD_TUPLE | 16,765,380 | 1.1% | 81.7% |  |
| POP_JUMP_IF_TRUE | 16,631,820 | 1.1% | 82.8% |  |
| LOAD_ATTR | 16,544,060 | 1.1% | 83.9% |  |
| STORE_FAST_STORE_FAST | 16,157,160 | 1.1% | 85.0% |  |
| UNPACK_SEQUENCE_TUPLE | 16,148,040 | 1.1% | 86.1% |  |
| INTERPRETER_EXIT | 15,480,380 | 1.0% | 87.1% |  |
| CALL_PY_EXACT_ARGS | 13,822,580 | 0.9% | 88.0% | 0.0% |
| FOR_ITER_LIST | 13,337,740 | 0.9% | 88.9% | 0.0% |
| LOAD_ATTR_MODULE | 10,687,160 | 0.7% | 89.6% |  |
| CALL_STR_1 | 10,081,020 | 0.7% | 90.2% |  |
| FOR_ITER | 9,860,120 | 0.6% | 90.9% |  |
| TO_BOOL | 8,956,780 | 0.6% | 91.5% |  |
| GET_ITER | 8,479,500 | 0.6% | 92.0% |  |
| CALL_BUILTIN_FAST | 8,003,460 | 0.5% | 92.5% |  |
| LOAD_NAME | 7,501,200 | 0.5% | 93.0% |  |
| CALL_ISINSTANCE | 7,454,160 | 0.5% | 93.5% |  |
| TO_BOOL_LIST | 7,263,300 | 0.5% | 94.0% |  |
| LOAD_ATTR_SLOT | 7,209,460 | 0.5% | 94.5% | 0.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 7,204,400 | 0.5% | 95.0% | 0.0% |
| CALL | 6,614,160 | 0.4% | 95.4% |  |
| CONTAINS_OP | 5,230,080 | 0.3% | 95.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,753,800 | 0.3% | 96.0% |  |
| CALL_BUILTIN_O | 4,321,140 | 0.3% | 96.3% |  |
| CALL_TYPE_1 | 4,026,900 | 0.3% | 96.6% |  |
| CALL_PY_WITH_DEFAULTS | 3,960,960 | 0.3% | 96.9% |  |
| BUILD_MAP | 3,904,980 | 0.3% | 97.1% |  |
| RETURN_CONST | 3,724,200 | 0.2% | 97.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 3,639,000 | 0.2% | 97.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,614,460 | 0.2% | 97.8% | 0.0% |
| POP_JUMP_IF_NOT_NONE | 3,315,720 | 0.2% | 98.0% |  |
| SWAP | 3,312,600 | 0.2% | 98.3% |  |
| COPY_FREE_VARS | 3,301,380 | 0.2% | 98.5% |  |
| BINARY_SUBSCR_DICT | 3,301,080 | 0.2% | 98.7% |  |
| STORE_SUBSCR_DICT | 3,301,020 | 0.2% | 98.9% |  |
| BUILD_CONST_KEY_MAP | 3,300,960 | 0.2% | 99.1% |  |
| POP_JUMP_IF_NONE | 2,642,100 | 0.2% | 99.3% |  |
| TO_BOOL_INT | 2,040,240 | 0.1% | 99.4% |  |
| CALL_KW | 845,700 | 0.1% | 99.5% |  |
| CALL_LEN | 735,540 | 0.0% | 99.5% |  |
| COMPARE_OP_INT | 733,860 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 669,360 | 0.0% | 99.6% |  |
| COMPARE_OP | 666,880 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 665,760 | 0.0% | 99.7% |  |
| TO_BOOL_STR | 386,700 | 0.0% | 99.8% | 82.2% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 363,900 | 0.0% | 99.8% |  |
| NOP | 309,360 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 305,340 | 0.0% | 99.8% |  |
| BINARY_SLICE | 303,780 | 0.0% | 99.8% |  |
| CALL_FUNCTION_EX | 303,720 | 0.0% | 99.9% |  |
| RETURN_GENERATOR | 303,600 | 0.0% | 99.9% |  |
| JUMP_FORWARD | 303,120 | 0.0% | 99.9% |  |
| DICT_MERGE | 303,000 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_LIST_INT | 302,820 | 0.0% | 99.9% |  |
| END_FOR | 302,200 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 302,160 | 0.0% | 100.0% |  |
| LIST_APPEND | 121,080 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 120,540 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 15,660 | 0.0% | 100.0% |  |
| BUILD_LIST | 12,660 | 0.0% | 100.0% |  |
| COPY | 11,400 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP | 8,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 6,720 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 6,460 | 0.0% | 100.0% |  |
| LOAD_DEREF | 6,000 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 4,440 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 3,740 | 0.0% | 100.0% | 4.3% |
| STORE_ATTR | 3,480 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 3,120 | 0.0% | 100.0% |  |
| POP_EXCEPT | 3,120 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 3,120 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 2,940 | 0.0% | 100.0% |  |
| MAKE_CELL | 2,760 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,720 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 2,340 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,280 | 0.0% | 100.0% |  |
| IMPORT_NAME | 2,220 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 2,160 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 2,040 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 1,980 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,740 | 0.0% | 100.0% | 6.9% |
| STORE_SUBSCR_LIST_INT | 1,680 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 1,680 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,620 | 0.0% | 100.0% |  |
| IMPORT_FROM | 1,500 | 0.0% | 100.0% |  |
| BUILD_STRING | 1,440 | 0.0% | 100.0% |  |
| BUILD_SLICE | 1,080 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 1,080 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 1,020 | 0.0% | 100.0% |  |
| STORE_DEREF | 840 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 780 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 720 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 720 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 720 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 600 | 0.0% | 100.0% | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 500 | 0.0% | 100.0% |  |
| LIST_EXTEND | 420 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 420 | 0.0% | 100.0% |  |
| RESUME | 360 | 0.0% | 100.0% | 261.1% |
| LOAD_ATTR_PROPERTY | 300 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 240 | 0.0% | 100.0% |  |
| STORE_SLICE | 240 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 240 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 240 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 180 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 120 | 0.0% | 100.0% |  |
| DELETE_ATTR | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 91,491,720 | 6.0% | 6.0% |
| LOAD_GLOBAL_MODULE IS_OP | 67,940,100 | 4.5% | 10.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 65,926,620 | 4.3% | 14.8% |
| IS_OP POP_JUMP_IF_FALSE | 64,283,340 | 4.2% | 19.0% |
| RESUME_CHECK POP_TOP | 57,069,420 | 3.8% | 22.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 56,844,800 | 3.7% | 26.5% |
| POP_TOP JUMP_BACKWARD | 47,295,360 | 3.1% | 29.6% |
| FOR_ITER_GEN RESUME_CHECK | 45,304,780 | 3.0% | 32.6% |
| LOAD_FAST YIELD_VALUE | 35,583,240 | 2.3% | 35.0% |
| LOAD_FAST LOAD_CONST | 35,129,580 | 2.3% | 37.3% |
| YIELD_VALUE STORE_FAST | 31,202,760 | 2.1% | 39.3% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 31,086,240 | 2.0% | 41.4% |
| JUMP_BACKWARD FOR_ITER_GEN | 29,163,180 | 1.9% | 43.3% |
| BINARY_SUBSCR_TUPLE_INT LOAD_GLOBAL_MODULE | 22,141,740 | 1.5% | 44.7% |
| JUMP_BACKWARD EXTENDED_ARG | 17,885,520 | 1.2% | 45.9% |
| LOAD_FAST LOAD_ATTR | 16,521,960 | 1.1% | 47.0% |
| EXTENDED_ARG FOR_ITER_GEN | 16,443,140 | 1.1% | 48.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 16,397,280 | 1.1% | 49.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 16,254,120 | 1.1% | 50.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 16,207,260 | 1.1% | 51.3% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 16,147,500 | 1.1% | 52.4% |
| STORE_FAST_STORE_FAST STORE_FAST | 16,147,440 | 1.1% | 53.4% |
| RESUME_CHECK LOAD_FAST | 15,308,940 | 1.0% | 54.4% |
| CACHE RESUME_CHECK | 15,176,540 | 1.0% | 55.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 14,704,740 | 1.0% | 56.4% |
| RETURN_VALUE STORE_FAST | 14,528,520 | 1.0% | 57.3% |
| LOAD_FAST BUILD_TUPLE | 14,112,420 | 0.9% | 58.3% |
| YIELD_VALUE UNPACK_SEQUENCE_TUPLE | 14,101,600 | 0.9% | 59.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 13,819,760 | 0.9% | 60.1% |
| BUILD_TUPLE YIELD_VALUE | 13,805,340 | 0.9% | 61.0% |
| LOAD_FAST PUSH_NULL | 12,553,020 | 0.8% | 61.8% |
| LOAD_FAST RETURN_VALUE | 12,372,600 | 0.8% | 62.7% |
| PUSH_NULL LOAD_FAST | 11,828,700 | 0.8% | 63.4% |
| YIELD_VALUE INTERPRETER_EXIT | 11,765,040 | 0.8% | 64.2% |
| EXTENDED_ARG JUMP_BACKWARD | 11,645,100 | 0.8% | 65.0% |
| POP_TOP EXTENDED_ARG | 11,042,100 | 0.7% | 65.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 10,743,900 | 0.7% | 66.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 10,685,860 | 0.7% | 67.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 10,684,680 | 0.7% | 67.8% |
| LOAD_FAST CALL_STR_1 | 10,081,020 | 0.7% | 68.5% |
| JUMP_BACKWARD FOR_ITER_LIST | 10,029,120 | 0.7% | 69.1% |
| FOR_ITER_LIST STORE_FAST | 10,028,820 | 0.7% | 69.8% |
| LOAD_ATTR LOAD_FAST | 9,906,300 | 0.7% | 70.4% |
| LOAD_FAST TO_BOOL_BOOL | 9,188,380 | 0.6% | 71.0% |
| LOAD_FAST TO_BOOL | 8,263,860 | 0.5% | 71.6% |
| LOAD_CONST STORE_FAST | 7,870,980 | 0.5% | 72.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 7,682,600 | 0.5% | 72.6% |
| IS_OP POP_JUMP_IF_TRUE | 7,681,560 | 0.5% | 73.1% |
| BINARY_SUBSCR_TUPLE_INT STORE_FAST | 7,680,720 | 0.5% | 73.6% |
| CALL_STR_1 YIELD_VALUE | 7,680,480 | 0.5% | 74.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 7,453,880 | 0.5% | 74.6% |
| LOAD_FAST TO_BOOL_LIST | 7,263,300 | 0.5% | 75.1% |
| TO_BOOL POP_JUMP_IF_FALSE | 7,261,080 | 0.5% | 75.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 7,209,020 | 0.5% | 76.0% |
| RESUME_CHECK LOAD_CONST | 7,203,480 | 0.5% | 76.5% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 7,203,400 | 0.5% | 77.0% |
| FOR_ITER STORE_FAST | 7,199,940 | 0.5% | 77.5% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 6,962,700 | 0.5% | 77.9% |
| LOAD_ATTR_SLOT LOAD_FAST | 6,601,500 | 0.4% | 78.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 6,308,680 | 0.4% | 78.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 6,303,720 | 0.4% | 79.2% |
| POP_TOP LOAD_FAST | 6,066,600 | 0.4% | 79.6% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 5,942,160 | 0.4% | 80.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 5,299,020 | 0.3% | 80.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 5,050,140 | 0.3% | 80.7% |
| LOAD_CONST LOAD_FAST | 4,756,680 | 0.3% | 81.0% |
| LOAD_FAST LOAD_FAST | 4,624,740 | 0.3% | 81.3% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 4,621,080 | 0.3% | 81.6% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 4,560,840 | 0.3% | 81.9% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 4,440,480 | 0.3% | 82.2% |
| LOAD_FAST CALL_BUILTIN_O | 4,320,420 | 0.3% | 82.5% |
| CALL_BUILTIN_O POP_TOP | 4,320,420 | 0.3% | 82.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 4,202,000 | 0.3% | 83.0% |
| PUSH_NULL LOAD_NAME | 4,200,900 | 0.3% | 83.3% |
| LOAD_FAST CALL_TYPE_1 | 4,026,880 | 0.3% | 83.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,972,540 | 0.3% | 83.8% |
| GET_ITER FOR_ITER | 3,908,400 | 0.3% | 84.1% |
| JUMP_BACKWARD FOR_ITER | 3,907,440 | 0.3% | 84.3% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 3,906,420 | 0.3% | 84.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,902,240 | 0.3% | 84.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 3,901,200 | 0.3% | 85.1% |
| LOAD_NAME PUSH_NULL | 3,900,600 | 0.3% | 85.4% |
| LOAD_CONST CALL_BOUND_METHOD_EXACT_ARGS | 3,899,280 | 0.3% | 85.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,731,720 | 0.2% | 85.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 3,630,440 | 0.2% | 86.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,612,580 | 0.2% | 86.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 3,608,220 | 0.2% | 86.6% |
| POP_TOP LOAD_GLOBAL_MODULE | 3,601,320 | 0.2% | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 3,601,080 | 0.2% | 87.0% |
| CALL_BUILTIN_FAST RETURN_VALUE | 3,600,840 | 0.2% | 87.3% |
| LOAD_NAME LOAD_CONST | 3,600,600 | 0.2% | 87.5% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 3,600,600 | 0.2% | 87.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 3,315,360 | 0.2% | 88.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,310,360 | 0.2% | 88.2% |
| RETURN_CONST POP_TOP | 3,307,560 | 0.2% | 88.4% |
| LOAD_GLOBAL_BUILTIN IS_OP | 3,305,760 | 0.2% | 88.6% |
| CALL_TYPE_1 LOAD_GLOBAL_BUILTIN | 3,305,740 | 0.2% | 88.8% |
| GET_ITER FOR_ITER_LIST | 3,303,960 | 0.2% | 89.1% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 3,303,740 | 0.2% | 89.3% |
| RETURN_VALUE INTERPRETER_EXIT | 3,303,540 | 0.2% | 89.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 303,180 | 99.8% |
| LOAD_FAST | 360 | 0.1% |
| LOAD_FAST_LOAD_FAST | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 301,740 | 99.3% |
| BUILD_TUPLE | 600 | 0.2% |
| LIST_EXTEND | 300 | 0.1% |
| CALL | 300 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.1% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 120 | 50.0% |
| EXTENDED_ARG | 120 | 50.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,176,540 | 98.0% |
| RETURN_GENERATOR | 301,320 | 1.9% |
| POP_TOP | 1,740 | 0.0% |
| MAKE_CELL | 420 | 0.0% |
| RESUME | 360 | 0.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 120 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,060 | 93.8% |
| BINARY_SUBSCR | 300 | 4.6% |
| BUILD_SLICE | 60 | 0.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 20 | 0.3% |
| BINARY_OP_ADD_INT | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 4,200 | 65.0% |
| STORE_FAST | 780 | 12.1% |
| LOAD_FAST | 480 | 7.4% |
| CALL_LEN | 480 | 7.4% |
| BINARY_SUBSCR | 300 | 4.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,120 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 1,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 840 | 82.4% |
| EXTENDED_ARG | 180 | 17.6% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 302,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300,640 | 99.5% |
| RETURN_CONST | 1,140 | 0.4% |
| JUMP_BACKWARD | 240 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 720 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 1,440 | 66.7% |
| LOAD_ATTR | 720 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 1,440 | 66.7% |
| LOAD_CONST | 720 | 33.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,601,080 | 42.5% |
| RETURN_VALUE | 3,300,000 | 38.9% |
| LOAD_FAST | 1,569,780 | 18.5% |
| CALL | 3,420 | 0.0% |
| LOAD_ATTR | 2,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 3,908,400 | 46.1% |
| FOR_ITER_LIST | 3,303,960 | 39.0% |
| FOR_ITER_TUPLE | 662,220 | 7.8% |
| EXTENDED_ARG | 601,860 | 7.1% |
| FOR_ITER_GEN | 1,500 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 11,765,040 | 76.0% |
| RETURN_VALUE | 3,303,540 | 21.3% |
| RETURN_GENERATOR | 301,440 | 1.9% |
| RETURN_CONST | 110,360 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,440 | 61.5% |
| STORE_FAST | 540 | 23.1% |
| LOAD_CONST | 360 | 15.4% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 304,680 | 98.5% |
| POP_JUMP_IF_FALSE | 3,600 | 1.2% |
| RESUME_CHECK | 360 | 0.1% |
| FOR_ITER_LIST | 240 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 303,240 | 98.0% |
| LOAD_FAST | 5,280 | 1.7% |
| LOAD_GLOBAL_MODULE | 520 | 0.2% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,120 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 57,069,420 | 79.4% |
| CALL_BUILTIN_O | 4,320,420 | 6.0% |
| RETURN_CONST | 3,307,560 | 4.6% |
| CALL | 3,300,360 | 4.6% |
| SWAP | 3,300,300 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 47,295,360 | 65.8% |
| EXTENDED_ARG | 11,042,100 | 15.4% |
| LOAD_FAST | 6,066,600 | 8.4% |
| LOAD_GLOBAL_MODULE | 3,601,320 | 5.0% |
| RETURN_VALUE | 3,300,300 | 4.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,120 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,553,020 | 50.1% |
| LOAD_ATTR_MODULE | 7,682,600 | 30.7% |
| LOAD_NAME | 3,900,600 | 15.6% |
| RETURN_VALUE | 600,600 | 2.4% |
| BINARY_SUBSCR_LIST_INT | 300,300 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,828,700 | 47.2% |
| LOAD_FAST_LOAD_FAST | 5,942,160 | 23.7% |
| LOAD_NAME | 4,200,900 | 16.8% |
| LOAD_CONST | 1,441,140 | 5.8% |
| CALL_BUILTIN_FAST | 1,020,420 | 4.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 301,320 | 99.2% |
| CALL_PY_EXACT_ARGS | 1,380 | 0.5% |
| CALL_KW | 720 | 0.2% |
| MAKE_CELL | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 301,440 | 99.3% |
| LOAD_CONST | 540 | 0.2% |
| GET_ITER | 540 | 0.2% |
| CALL | 400 | 0.1% |
| CALL_PY_EXACT_ARGS | 220 | 0.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,372,600 | 48.1% |
| CALL_BUILTIN_FAST | 3,600,840 | 14.0% |
| POP_TOP | 3,300,300 | 12.8% |
| BUILD_CONST_KEY_MAP | 3,300,300 | 12.8% |
| RETURN_VALUE | 3,004,200 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,528,520 | 56.5% |
| INTERPRETER_EXIT | 3,303,540 | 12.9% |
| GET_ITER | 3,300,000 | 12.8% |
| RETURN_VALUE | 3,004,200 | 11.7% |
| LOAD_CONST | 960,120 | 3.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,263,860 | 92.3% |
| BINARY_SUBSCR_TUPLE_INT | 660,060 | 7.4% |
| TO_BOOL | 26,240 | 0.3% |
| TO_BOOL_STR | 6,000 | 0.1% |
| CALL_ISINSTANCE | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,261,080 | 81.1% |
| POP_JUMP_IF_TRUE | 1,662,760 | 18.6% |
| TO_BOOL | 26,240 | 0.3% |
| TO_BOOL_STR | 6,080 | 0.1% |
| TO_BOOL_BOOL | 460 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,920 | 59.1% |
| LOAD_FAST | 820 | 9.9% |
| RETURN_VALUE | 600 | 7.2% |
| BINARY_OP | 560 | 6.7% |
| POP_JUMP_IF_TRUE | 360 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,920 | 59.1% |
| STORE_FAST | 1,200 | 14.4% |
| CALL | 800 | 9.6% |
| BINARY_OP | 560 | 6.7% |
| LOAD_FAST | 360 | 4.3% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,300,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,300,300 | 100.0% |
| LOAD_FAST | 660 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,100 | 16.6% |
| RESUME_CHECK | 1,860 | 14.7% |
| SWAP | 1,440 | 11.4% |
| STORE_FAST | 1,440 | 11.4% |
| POP_JUMP_IF_FALSE | 960 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800 | 37.9% |
| LOAD_FAST | 2,340 | 18.5% |
| CALL | 1,800 | 14.2% |
| SWAP | 1,440 | 11.4% |
| LOAD_DEREF | 840 | 6.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,301,440 | 84.5% |
| BUILD_TUPLE | 301,260 | 7.7% |
| STORE_FAST | 300,660 | 7.7% |
| LOAD_CONST | 660 | 0.0% |
| RESUME_CHECK | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,300,300 | 84.5% |
| LOAD_FAST | 303,180 | 7.8% |
| STORE_FAST | 300,960 | 7.7% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 0.0% |
| STORE_DEREF | 180 | 0.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 1,020 | 94.4% |
| BINARY_SUBSCR | 60 | 5.6% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 1,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 720 | 50.0% |
| LOAD_GLOBAL_MODULE | 720 | 50.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,112,420 | 84.2% |
| LOAD_FAST_LOAD_FAST | 2,641,680 | 15.8% |
| LOAD_GLOBAL_BUILTIN | 7,200 | 0.0% |
| LOAD_ATTR | 1,080 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 13,805,340 | 82.3% |
| CALL_BUILTIN_FAST | 2,640,240 | 15.7% |
| BUILD_MAP | 301,260 | 1.8% |
| CALL_ISINSTANCE | 7,160 | 0.0% |
| CALL_LIST_APPEND | 4,240 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,300,820 | 49.9% |
| LOAD_FAST | 2,166,480 | 32.8% |
| CALL | 726,900 | 11.0% |
| PUSH_NULL | 304,720 | 4.6% |
| LOAD_CONST | 108,000 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,300,360 | 49.9% |
| LOAD_FAST | 1,320,840 | 20.0% |
| CALL | 726,900 | 11.0% |
| STORE_FAST | 726,720 | 11.0% |
| CALL_BUILTIN_FAST | 300,060 | 4.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 303,000 | 99.8% |
| CALL_INTRINSIC_1 | 420 | 0.1% |
| BINARY_OP | 180 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 301,620 | 99.3% |
| RETURN_VALUE | 1,140 | 0.4% |
| RESUME_CHECK | 420 | 0.1% |
| LOAD_FAST | 240 | 0.1% |
| GET_ITER | 180 | 0.1% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 420 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 845,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 721,980 | 85.4% |
| LIST_APPEND | 120,000 | 14.2% |
| STORE_FAST | 840 | 0.1% |
| POP_TOP | 840 | 0.1% |
| RETURN_GENERATOR | 720 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 660,120 | 99.0% |
| BINARY_SUBSCR | 4,200 | 0.6% |
| LOAD_FAST | 1,660 | 0.2% |
| COMPARE_OP | 440 | 0.1% |
| RETURN_VALUE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 665,340 | 99.8% |
| POP_JUMP_IF_TRUE | 720 | 0.1% |
| COMPARE_OP | 440 | 0.1% |
| RETURN_VALUE | 180 | 0.0% |
| COMPARE_OP_INT | 140 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,906,420 | 74.7% |
| LOAD_FAST | 1,321,980 | 25.3% |
| LOAD_GLOBAL_MODULE | 900 | 0.0% |
| RETURN_VALUE | 600 | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,560,840 | 87.2% |
| POP_JUMP_IF_FALSE | 669,240 | 12.8% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,360 | 55.8% |
| LOAD_CONST | 2,280 | 20.0% |
| COPY | 1,680 | 14.7% |
| LOAD_ATTR_SLOT | 300 | 2.6% |
| CALL_KW | 300 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,320 | 46.7% |
| COPY | 1,680 | 14.7% |
| BINARY_SUBSCR_LIST_INT | 1,680 | 14.7% |
| TO_BOOL_STR | 1,140 | 10.0% |
| STORE_FAST_STORE_FAST | 600 | 5.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 3,300,000 | 100.0% |
| CALL_PY_EXACT_ARGS | 1,020 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 240 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,301,320 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 303,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 303,000 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 17,885,520 | 59.4% |
| POP_TOP | 11,042,100 | 36.6% |
| GET_ITER | 601,860 | 2.0% |
| STORE_FAST | 300,720 | 1.0% |
| JUMP_FORWARD | 300,360 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 16,443,140 | 54.6% |
| JUMP_BACKWARD | 11,645,100 | 38.6% |
| FOR_ITER | 2,040,660 | 6.8% |
| FOR_ITER_LIST | 3,580 | 0.0% |
| POP_JUMP_IF_FALSE | 1,800 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,908,400 | 39.6% |
| JUMP_BACKWARD | 3,907,440 | 39.6% |
| EXTENDED_ARG | 2,040,660 | 20.7% |
| FOR_ITER | 3,320 | 0.0% |
| SWAP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,199,940 | 73.0% |
| UNPACK_SEQUENCE_TUPLE | 2,041,080 | 20.7% |
| LOAD_FAST | 307,400 | 3.1% |
| RETURN_CONST | 300,720 | 3.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,180 | 0.1% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 1,500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,500 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,500 | 67.6% |
| STORE_FAST | 720 | 32.4% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 67,940,100 | 94.4% |
| LOAD_GLOBAL_BUILTIN | 3,305,760 | 4.6% |
| LOAD_FAST | 721,020 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 64,283,340 | 89.3% |
| POP_JUMP_IF_TRUE | 7,681,560 | 10.7% |
| EXTENDED_ARG | 1,800 | 0.0% |
| COPY | 180 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 47,295,360 | 76.6% |
| EXTENDED_ARG | 11,645,100 | 18.9% |
| STORE_FAST | 2,041,920 | 3.3% |
| POP_JUMP_IF_TRUE | 600,420 | 1.0% |
| LIST_APPEND | 121,080 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 29,163,180 | 47.3% |
| EXTENDED_ARG | 17,885,520 | 29.0% |
| FOR_ITER_LIST | 10,029,120 | 16.3% |
| FOR_ITER | 3,907,440 | 6.3% |
| LOAD_FAST | 600,720 | 1.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 300,420 | 99.1% |
| STORE_FAST | 1,980 | 0.7% |
| EXTENDED_ARG | 540 | 0.2% |
| STORE_SLICE | 120 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 300,360 | 99.1% |
| LOAD_FAST_LOAD_FAST | 1,020 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 720 | 0.2% |
| LOAD_FAST | 420 | 0.1% |
| LOAD_GLOBAL_MODULE | 360 | 0.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 120,000 | 99.1% |
| RETURN_VALUE | 600 | 0.5% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 240 | 0.2% |
| BUILD_TUPLE | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 121,080 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 300 | 71.4% |
| LOAD_DEREF | 120 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 420 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,521,960 | 99.9% |
| LOAD_ATTR | 7,000 | 0.0% |
| LOAD_GLOBAL_MODULE | 6,260 | 0.0% |
| LOAD_ATTR_SLOT | 4,920 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,906,300 | 59.9% |
| LOAD_GLOBAL_MODULE | 3,301,580 | 20.0% |
| CALL | 3,300,820 | 20.0% |
| LOAD_ATTR | 7,000 | 0.0% |
| BINARY_OP | 4,920 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,129,580 | 61.7% |
| RESUME_CHECK | 7,203,480 | 12.6% |
| LOAD_NAME | 3,600,600 | 6.3% |
| LOAD_GLOBAL_MODULE | 3,303,480 | 5.8% |
| LOAD_CONST | 2,592,060 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 31,086,240 | 54.6% |
| STORE_FAST | 7,870,980 | 13.8% |
| LOAD_FAST | 4,756,680 | 8.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 3,899,280 | 6.8% |
| BUILD_CONST_KEY_MAP | 3,300,960 | 5.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 960 | 16.0% |
| BUILD_LIST | 840 | 14.0% |
| LOAD_FAST | 720 | 12.0% |
| LOAD_ATTR | 600 | 10.0% |
| STORE_DEREF | 480 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,080 | 18.0% |
| STORE_ATTR_INSTANCE_VALUE | 960 | 16.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 960 | 16.0% |
| LOAD_FAST_LOAD_FAST | 720 | 12.0% |
| STORE_ATTR | 660 | 11.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 91,491,720 | 32.1% |
| POP_JUMP_IF_FALSE | 65,926,620 | 23.1% |
| LOAD_FAST_LOAD_FAST | 16,397,280 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 16,254,120 | 5.7% |
| RESUME_CHECK | 15,308,940 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 56,844,800 | 19.9% |
| YIELD_VALUE | 35,583,240 | 12.5% |
| LOAD_CONST | 35,129,580 | 12.3% |
| LOAD_ATTR | 16,521,960 | 5.8% |
| BUILD_TUPLE | 14,112,420 | 5.0% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,440 | 85.7% |
| LOAD_FAST_AND_CLEAR | 240 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,440 | 85.7% |
| LOAD_FAST_AND_CLEAR | 240 | 14.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,743,900 | 28.8% |
| LOAD_GLOBAL_MODULE | 6,303,720 | 16.9% |
| PUSH_NULL | 5,942,160 | 15.9% |
| POP_JUMP_IF_TRUE | 4,621,080 | 12.4% |
| STORE_FAST | 3,901,200 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,397,280 | 43.9% |
| CONTAINS_OP | 3,906,420 | 10.5% |
| CALL_PY_EXACT_ARGS | 3,902,240 | 10.4% |
| LOAD_FAST_LOAD_FAST | 3,301,860 | 8.8% |
| BINARY_SUBSCR_DICT | 3,300,300 | 8.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 380 | 14.0% |
| RESUME_CHECK | 380 | 14.0% |
| LOAD_FAST | 300 | 11.0% |
| POP_JUMP_IF_TRUE | 280 | 10.3% |
| LOAD_GLOBAL_MODULE | 220 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,700 | 62.5% |
| LOAD_GLOBAL_BUILTIN | 980 | 36.0% |
| LOAD_ATTR | 40 | 1.5% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,200,900 | 56.0% |
| RESUME_CHECK | 3,299,940 | 44.0% |
| RESUME | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,900,600 | 52.0% |
| LOAD_CONST | 3,600,600 | 48.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 900 | 32.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 720 | 26.1% |
| CALL_PY_EXACT_ARGS | 420 | 15.2% |
| CACHE | 420 | 15.2% |
| CALL_KW | 300 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,740 | 63.0% |
| MAKE_CELL | 900 | 32.6% |
| RETURN_GENERATOR | 120 | 4.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 64,283,340 | 66.0% |
| TO_BOOL_BOOL | 16,207,260 | 16.6% |
| TO_BOOL | 7,261,080 | 7.5% |
| TO_BOOL_LIST | 6,962,700 | 7.1% |
| COMPARE_OP_INT | 733,080 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,926,620 | 67.6% |
| LOAD_GLOBAL_MODULE | 14,704,740 | 15.1% |
| LOAD_FAST_LOAD_FAST | 10,743,900 | 11.0% |
| LOAD_GLOBAL_BUILTIN | 5,299,020 | 5.4% |
| LOAD_CONST | 663,540 | 0.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640,660 | 99.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,140 | 0.0% |
| LOAD_DEREF | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,321,500 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,319,940 | 50.0% |
| LOAD_CONST | 660 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,315,360 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,007,700 | 90.7% |
| LOAD_FAST | 307,140 | 9.3% |
| LOAD_CONST | 600 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 7,681,560 | 46.2% |
| CONTAINS_OP | 4,560,840 | 27.4% |
| TO_BOOL | 1,662,760 | 10.0% |
| TO_BOOL_INT | 1,380,180 | 8.3% |
| TO_BOOL_BOOL | 663,660 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,684,680 | 64.2% |
| LOAD_FAST_LOAD_FAST | 4,621,080 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 721,160 | 4.3% |
| JUMP_BACKWARD | 600,420 | 3.6% |
| LOAD_CONST | 1,380 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 3,300,000 | 88.6% |
| FOR_ITER | 300,720 | 8.1% |
| POP_JUMP_IF_FALSE | 106,140 | 2.9% |
| STORE_ATTR_INSTANCE_VALUE | 7,560 | 0.2% |
| POP_TOP | 5,820 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,307,560 | 88.8% |
| END_FOR | 302,200 | 8.1% |
| INTERPRETER_EXIT | 110,360 | 3.0% |
| STORE_FAST | 3,360 | 0.1% |
| EXIT_INIT_CHECK | 720 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,440 | 72.7% |
| SET_FUNCTION_ATTRIBUTE | 540 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 48.5% |
| SET_FUNCTION_ATTRIBUTE | 540 | 27.3% |
| STORE_DEREF | 480 | 24.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,700 | 48.9% |
| LOAD_DEREF | 660 | 19.0% |
| LOAD_FAST_LOAD_FAST | 620 | 17.8% |
| STORE_ATTR | 480 | 13.8% |
| SWAP | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,320 | 37.9% |
| LOAD_FAST | 780 | 22.4% |
| STORE_ATTR | 480 | 13.8% |
| LOAD_DEREF | 300 | 8.6% |
| BUILD_LIST | 300 | 8.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 480 | 57.1% |
| BUILD_MAP | 180 | 21.4% |
| STORE_FAST_STORE_FAST | 60 | 7.1% |
| RETURN_GENERATOR | 60 | 7.1% |
| CALL_BUILTIN_CLASS | 60 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 480 | 57.1% |
| LOAD_FAST | 240 | 28.6% |
| LOAD_GLOBAL_MODULE | 80 | 9.5% |
| LOAD_GLOBAL | 40 | 4.8% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 31,202,760 | 30.1% |
| STORE_FAST_STORE_FAST | 16,147,440 | 15.6% |
| RETURN_VALUE | 14,528,520 | 14.0% |
| FOR_ITER_LIST | 10,028,820 | 9.7% |
| LOAD_CONST | 7,870,980 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,491,720 | 88.2% |
| LOAD_FAST_LOAD_FAST | 3,901,200 | 3.8% |
| LOAD_GLOBAL_BUILTIN | 3,731,720 | 3.6% |
| JUMP_BACKWARD | 2,041,920 | 2.0% |
| LOAD_GLOBAL_MODULE | 726,920 | 0.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 240 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 16,147,500 | 99.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 8,520 | 0.1% |
| COPY | 600 | 0.0% |
| STORE_FAST_STORE_FAST | 300 | 0.0% |
| UNPACK_SEQUENCE_LIST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,147,440 | 99.9% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.0% |
| LOAD_FAST | 1,800 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 540 | 0.0% |
| LOAD_GLOBAL_MODULE | 420 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 3,300,300 | 99.6% |
| BINARY_OP_ADD_UNICODE | 5,280 | 0.2% |
| SWAP | 1,680 | 0.1% |
| BINARY_OP_ADD_INT | 1,680 | 0.1% |
| LOAD_FAST_AND_CLEAR | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,300,300 | 99.6% |
| STORE_ATTR_INSTANCE_VALUE | 5,320 | 0.2% |
| SWAP | 1,680 | 0.1% |
| STORE_SUBSCR_LIST_INT | 1,680 | 0.1% |
| BUILD_LIST | 1,440 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 360 | 72.0% |
| UNPACK_SEQUENCE | 40 | 8.0% |
| RETURN_VALUE | 40 | 8.0% |
| YIELD_VALUE | 20 | 4.0% |
| LOAD_FAST | 20 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 72.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 12.0% |
| UNPACK_SEQUENCE_TUPLE | 40 | 8.0% |
| UNPACK_SEQUENCE | 40 | 8.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,583,240 | 62.4% |
| BUILD_TUPLE | 13,805,340 | 24.2% |
| CALL_STR_1 | 7,680,480 | 13.5% |
| RETURN_VALUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,202,760 | 54.7% |
| UNPACK_SEQUENCE_TUPLE | 14,101,600 | 24.7% |
| INTERPRETER_EXIT | 11,765,040 | 20.6% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 360 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,680 | 57.1% |
| LOAD_CONST | 700 | 23.8% |
| BINARY_OP_SUBTRACT_INT | 480 | 16.3% |
| BINARY_OP | 80 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,680 | 57.1% |
| STORE_FAST | 1,140 | 38.8% |
| LOAD_FAST | 60 | 2.0% |
| BINARY_SUBSCR_STR_INT | 40 | 1.4% |
| BINARY_SUBSCR | 20 | 0.7% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,820 | 86.6% |
| LOAD_CONST | 540 | 8.0% |
| BINARY_OP_ADD_UNICODE | 360 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 5,280 | 78.6% |
| LOAD_ATTR_METHOD_NO_DICT | 600 | 8.9% |
| BINARY_OP_ADD_UNICODE | 360 | 5.4% |
| LOAD_FAST | 180 | 2.7% |
| CALL | 180 | 2.7% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| BINARY_OP | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820 | 75.9% |
| CALL_LEN | 240 | 22.2% |
| BINARY_OP | 20 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 480 | 44.4% |
| STORE_FAST | 300 | 27.8% |
| LOAD_CONST | 240 | 22.2% |
| COMPARE_OP_INT | 40 | 3.7% |
| COMPARE_OP | 20 | 1.9% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,300,300 | 100.0% |
| LOAD_FAST | 360 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 280 | 0.0% |
| BUILD_TUPLE | 120 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,300,300 | 100.0% |
| STORE_FAST | 660 | 0.0% |
| RETURN_VALUE | 120 | 0.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 301,080 | 99.4% |
| COPY | 1,680 | 0.6% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 300,300 | 99.2% |
| LOAD_GLOBAL_BUILTIN | 1,680 | 0.6% |
| STORE_FAST | 240 | 0.1% |
| LOAD_ATTR | 240 | 0.1% |
| RETURN_VALUE | 180 | 0.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,086,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 22,141,740 | 71.2% |
| STORE_FAST | 7,680,720 | 24.7% |
| TO_BOOL | 660,060 | 2.1% |
| LOAD_FAST | 300,780 | 1.0% |
| LOAD_FAST_LOAD_FAST | 300,540 | 1.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 360 | 50.0% |
| LOAD_FAST | 360 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 720 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,899,280 | 54.1% |
| LOAD_FAST | 3,303,740 | 45.9% |
| LOAD_FAST_LOAD_FAST | 780 | 0.0% |
| CALL | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,203,400 | 100.0% |
| MAKE_CELL | 720 | 0.0% |
| COPY_FREE_VARS | 240 | 0.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 301,460 | 99.8% |
| CALL | 340 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| BUILD_TUPLE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300,540 | 99.5% |
| UNPACK_SEQUENCE | 360 | 0.1% |
| LOAD_FAST | 360 | 0.1% |
| GET_ITER | 300 | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.1% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 3,300,300 | 41.2% |
| BUILD_TUPLE | 2,640,240 | 33.0% |
| PUSH_NULL | 1,020,420 | 12.7% |
| LOAD_FAST | 309,100 | 3.9% |
| LOAD_FAST_LOAD_FAST | 302,880 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,600,840 | 45.0% |
| STORE_FAST | 3,247,920 | 40.6% |
| LOAD_CONST | 720,120 | 9.0% |
| LOAD_FAST | 300,960 | 3.8% |
| TO_BOOL_BOOL | 120,640 | 1.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 59.3% |
| LOAD_ATTR | 600 | 37.0% |
| LOAD_CONST | 40 | 2.5% |
| CALL | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 900 | 55.6% |
| RETURN_VALUE | 600 | 37.0% |
| COPY | 120 | 7.4% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,320,420 | 100.0% |
| LOAD_ATTR | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,320,420 | 100.0% |
| CALL_PY_EXACT_ARGS | 720 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,440,480 | 59.6% |
| LOAD_ATTR_MODULE | 3,002,120 | 40.3% |
| BUILD_TUPLE | 7,160 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 2,960 | 0.0% |
| LOAD_ATTR | 1,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,453,880 | 100.0% |
| TO_BOOL | 280 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 728,600 | 99.1% |
| LOAD_ATTR_INSTANCE_VALUE | 5,920 | 0.8% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 480 | 0.1% |
| BINARY_SUBSCR | 480 | 0.1% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 732,300 | 99.6% |
| BINARY_OP_ADD_INT | 1,680 | 0.2% |
| LOAD_FAST | 600 | 0.1% |
| STORE_FAST | 540 | 0.1% |
| BINARY_OP_SUBTRACT_INT | 240 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 4,240 | 47.1% |
| LOAD_FAST | 4,080 | 45.3% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 4.0% |
| LOAD_CONST | 180 | 2.0% |
| CALL | 100 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,260 | 47.3% |
| LOAD_FAST | 1,800 | 20.0% |
| EXTENDED_ARG | 1,320 | 14.7% |
| RETURN_CONST | 720 | 8.0% |
| LOAD_CONST | 720 | 8.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 300,300 | 98.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,120 | 0.7% |
| LOAD_FAST | 1,280 | 0.4% |
| LOAD_CONST | 1,000 | 0.3% |
| LOAD_GLOBAL_MODULE | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 302,460 | 99.1% |
| POP_TOP | 960 | 0.3% |
| RETURN_VALUE | 480 | 0.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 360 | 0.1% |
| TO_BOOL_STR | 360 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 361,960 | 99.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,680 | 0.5% |
| LOAD_FAST | 240 | 0.1% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 240,240 | 66.0% |
| STORE_FAST | 122,460 | 33.7% |
| CALL_LEN | 480 | 0.1% |
| UNPACK_SEQUENCE_LIST | 240 | 0.1% |
| LIST_APPEND | 240 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 500 | 92.6% |
| CALL | 40 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 280 | 51.9% |
| LOAD_FAST | 180 | 33.3% |
| GET_ITER | 60 | 11.1% |
| BINARY_SUBSCR | 20 | 3.7% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 44.7% |
| LOAD_GLOBAL_MODULE | 360 | 15.8% |
| CALL_BUILTIN_CLASS | 280 | 12.3% |
| BUILD_LIST | 240 | 10.5% |
| BINARY_SLICE | 240 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840 | 36.8% |
| CALL_PY_EXACT_ARGS | 520 | 22.8% |
| RETURN_VALUE | 360 | 15.8% |
| STORE_FAST | 240 | 10.5% |
| CALL | 200 | 8.8% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,308,680 | 45.6% |
| LOAD_FAST_LOAD_FAST | 3,902,240 | 28.2% |
| LOAD_GLOBAL_MODULE | 3,600,600 | 26.0% |
| LOAD_CONST | 3,120 | 0.0% |
| LOAD_ATTR | 3,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,819,760 | 100.0% |
| RETURN_GENERATOR | 1,380 | 0.0% |
| COPY_FREE_VARS | 1,020 | 0.0% |
| MAKE_CELL | 420 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,300,000 | 83.3% |
| LOAD_FAST | 660,300 | 16.7% |
| CALL | 280 | 0.0% |
| BUILD_TUPLE | 220 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 3,300,000 | 83.3% |
| RESUME_CHECK | 660,960 | 16.7% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,081,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,680,480 | 76.2% |
| LOAD_FAST | 2,400,180 | 23.8% |
| SWAP | 360 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 82.1% |
| STORE_FAST | 80 | 10.3% |
| CALL | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 76.9% |
| BINARY_OP | 120 | 15.4% |
| BUILD_TUPLE | 60 | 7.7% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,026,880 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,305,740 | 82.1% |
| LOAD_FAST | 721,020 | 17.9% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 732,740 | 99.8% |
| LOAD_FAST_LOAD_FAST | 900 | 0.1% |
| COMPARE_OP | 140 | 0.0% |
| CALL_LEN | 40 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 733,080 | 99.9% |
| POP_JUMP_IF_TRUE | 780 | 0.1% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,720 | 84.3% |
| LOAD_FAST | 260 | 12.7% |
| COMPARE_OP | 60 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,920 | 94.1% |
| POP_JUMP_IF_TRUE | 120 | 5.9% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 29,163,180 | 63.9% |
| EXTENDED_ARG | 16,443,140 | 36.1% |
| GET_ITER | 1,500 | 0.0% |
| FOR_ITER_LIST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 45,304,780 | 99.3% |
| POP_TOP | 301,800 | 0.7% |
| UNPACK_SEQUENCE_TUPLE | 960 | 0.0% |
| LOAD_FAST | 280 | 0.0% |
| FOR_ITER_LIST | 20 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,029,120 | 75.2% |
| GET_ITER | 3,303,960 | 24.8% |
| EXTENDED_ARG | 3,580 | 0.0% |
| SWAP | 960 | 0.0% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,028,820 | 75.2% |
| LOAD_FAST | 3,301,880 | 24.8% |
| UNPACK_SEQUENCE_TUPLE | 4,200 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,080 | 0.0% |
| RETURN_CONST | 780 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 120,300 | 99.8% |
| SWAP | 120 | 0.1% |
| GET_ITER | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120,420 | 99.9% |
| LOAD_GLOBAL_MODULE | 80 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 662,220 | 99.5% |
| JUMP_BACKWARD | 3,420 | 0.5% |
| SWAP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 662,040 | 99.4% |
| STORE_FAST | 3,240 | 0.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| SWAP | 120 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,630,440 | 99.8% |
| COPY | 5,320 | 0.1% |
| LOAD_DEREF | 1,080 | 0.0% |
| LOAD_FAST_LOAD_FAST | 860 | 0.0% |
| LOAD_ATTR | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,601,080 | 99.0% |
| LOAD_FAST | 11,880 | 0.3% |
| LOAD_CONST | 6,180 | 0.2% |
| LOAD_ATTR_METHOD_NO_DICT | 6,080 | 0.2% |
| CALL_LEN | 5,920 | 0.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 66.7% |
| LOAD_FAST | 40 | 22.2% |
| LOAD_ATTR | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 22.2% |
| CALL | 20 | 11.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,202,000 | 88.4% |
| LOAD_GLOBAL_MODULE | 300,780 | 6.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 240,240 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 6,080 | 0.1% |
| LOAD_CONST | 1,780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,972,540 | 83.6% |
| LOAD_CONST | 470,280 | 9.9% |
| LOAD_FAST_LOAD_FAST | 304,200 | 6.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,120 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,680 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,612,580 | 99.9% |
| LOAD_DEREF | 960 | 0.0% |
| LOAD_ATTR | 380 | 0.0% |
| RETURN_VALUE | 360 | 0.0% |
| LOAD_FAST_LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,608,220 | 99.8% |
| LOAD_CONST | 2,880 | 0.1% |
| CALL_PY_EXACT_ARGS | 1,320 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 720 | 0.0% |
| LOAD_GLOBAL_MODULE | 680 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 10,685,860 | 100.0% |
| LOAD_FAST | 720 | 0.0% |
| LOAD_ATTR | 500 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,682,600 | 71.9% |
| CALL_ISINSTANCE | 3,002,120 | 28.1% |
| LOAD_ATTR | 760 | 0.0% |
| LOAD_CONST | 720 | 0.0% |
| LOAD_FAST | 660 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 360 | 50.0% |
| LOAD_FAST | 360 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 360 | 50.0% |
| LOAD_CONST | 360 | 50.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,140 | 65.5% |
| LOAD_FAST_LOAD_FAST | 460 | 26.4% |
| LOAD_ATTR | 140 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 600 | 34.5% |
| LOAD_ATTR_METHOD_NO_DICT | 480 | 27.6% |
| STORE_FAST | 300 | 17.2% |
| CONTAINS_OP | 180 | 10.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 4.6% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 93.3% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,209,020 | 100.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR_SLOT | 40 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,601,500 | 91.6% |
| STORE_FAST | 301,020 | 4.2% |
| LOAD_FAST_LOAD_FAST | 300,300 | 4.2% |
| LOAD_ATTR | 4,920 | 0.1% |
| CALL | 720 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,299,020 | 26.5% |
| STORE_FAST | 3,731,720 | 18.6% |
| RESUME_CHECK | 3,310,360 | 16.5% |
| CALL_TYPE_1 | 3,305,740 | 16.5% |
| POP_JUMP_IF_NOT_NONE | 3,007,700 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,254,120 | 81.1% |
| IS_OP | 3,305,760 | 16.5% |
| LOAD_FAST_LOAD_FAST | 311,880 | 1.6% |
| LOAD_CONST | 120,840 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 25,060 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,844,800 | 55.5% |
| BINARY_SUBSCR_TUPLE_INT | 22,141,740 | 21.6% |
| POP_JUMP_IF_FALSE | 14,704,740 | 14.4% |
| POP_TOP | 3,601,320 | 3.5% |
| LOAD_ATTR | 3,301,580 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 67,940,100 | 66.4% |
| LOAD_ATTR_MODULE | 10,685,860 | 10.4% |
| LOAD_FAST_LOAD_FAST | 6,303,720 | 6.2% |
| LOAD_FAST | 5,050,140 | 4.9% |
| CALL_ISINSTANCE | 4,440,480 | 4.3% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 240 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 45,304,780 | 52.4% |
| CACHE | 15,176,540 | 17.5% |
| CALL_PY_EXACT_ARGS | 13,819,760 | 16.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 7,203,400 | 8.3% |
| COPY_FREE_VARS | 3,301,320 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 57,069,420 | 66.0% |
| LOAD_FAST | 15,308,940 | 17.7% |
| LOAD_CONST | 7,203,480 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 3,310,360 | 3.8% |
| LOAD_NAME | 3,299,940 | 3.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,700 | 42.8% |
| SWAP | 5,320 | 34.0% |
| LOAD_FAST_LOAD_FAST | 1,360 | 8.7% |
| STORE_ATTR | 1,320 | 8.4% |
| LOAD_DEREF | 960 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 7,560 | 48.3% |
| LOAD_CONST | 2,880 | 18.4% |
| LOAD_FAST | 2,280 | 14.6% |
| LOAD_FAST_LOAD_FAST | 780 | 5.0% |
| BUILD_LIST | 720 | 4.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880 | 64.9% |
| LOAD_FAST_LOAD_FAST | 1,560 | 35.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040 | 45.9% |
| RETURN_CONST | 1,020 | 23.0% |
| LOAD_GLOBAL_MODULE | 960 | 21.6% |
| LOAD_FAST_LOAD_FAST | 420 | 9.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,300,040 | 100.0% |
| BUILD_TUPLE | 840 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,300,000 | 100.0% |
| LOAD_FAST | 1,020 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,200 | 71.4% |
| LOAD_FAST | 480 | 28.6% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 50.0% |
| COPY | 300 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 600 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,188,380 | 54.5% |
| CALL_ISINSTANCE | 7,453,880 | 44.2% |
| CALL_BUILTIN_FAST | 120,640 | 0.7% |
| CALL | 106,320 | 0.6% |
| TO_BOOL | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,207,260 | 96.1% |
| POP_JUMP_IF_TRUE | 663,660 | 3.9% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,380,180 | 67.6% |
| POP_JUMP_IF_FALSE | 660,060 | 32.4% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,263,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,962,700 | 95.9% |
| POP_JUMP_IF_TRUE | 300,600 | 4.1% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 2,160 | 57.8% |
| LOAD_FAST | 1,180 | 31.6% |
| TO_BOOL | 160 | 4.3% |
| COPY | 160 | 4.3% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,940 | 78.6% |
| POP_JUMP_IF_TRUE | 800 | 21.4% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 379,120 | 98.0% |
| TO_BOOL | 6,080 | 1.6% |
| COPY | 1,140 | 0.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 379,200 | 98.1% |
| TO_BOOL | 6,000 | 1.6% |
| POP_JUMP_IF_FALSE | 1,500 | 0.4% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 240 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 14,101,600 | 87.3% |
| FOR_ITER | 2,041,080 | 12.6% |
| FOR_ITER_LIST | 4,200 | 0.0% |
| FOR_ITER_GEN | 960 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 16,147,500 | 100.0% |
| STORE_FAST | 540 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 661,000 | 98.8% |
| FOR_ITER | 7,180 | 1.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 360 | 0.1% |
| RETURN_VALUE | 340 | 0.1% |
| CALL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 660,840 | 98.7% |
| STORE_FAST_STORE_FAST | 8,520 | 1.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 66.7% |
| BINARY_OP_ADD_INT | 40 | 22.2% |
| BINARY_SUBSCR | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 100.0% |


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
| specialization.deferred |         6060 | 0.0% |
|          hit |     34690500 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 25.0% |
| Failure | 300 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 280 | 93.3% |
| tuple slice | 20 | 6.7% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3302700 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8923840 | 25.1% |
| specialization.deopt |         6000 | 0.0% |
|          hit |     26247280 | 73.9% |
|         miss |       318220 | 0.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,700 | 17.2% |
| Failure | 32,240 | 82.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 30,500 | 94.6% |
| dict | 1,640 | 5.1% |
| tuple | 100 | 0.3% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         7620 | 39.5% |
|          hit |        10980 | 56.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 20.0% |
| Failure | 560 | 80.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 320 | 57.1% |
| multiply different types | 120 | 21.4% |
| add other | 120 | 21.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6606480 | 8.9% |
| specialization.deopt |           40 | 0.0% |
|          hit |     67797220 | 91.1% |
|         miss |         3680 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,600 | 33.7% |
| Failure | 5,120 | 66.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 2,040 | 39.8% |
| class mutable | 1,100 | 21.5% |
| code complex parameters | 440 | 8.6% |
| cmethod | 420 | 8.2% |
| class no vectorcall | 300 | 5.9% |
| meth descr varargs | 220 | 4.3% |
| meth descr method fastcall keywords | 160 | 3.1% |
| cfunc varargs keywords | 120 | 2.3% |
| wrong number arguments | 100 | 2.0% |
| other | 100 | 2.0% |
| no dict | 80 | 1.6% |
| init not python | 20 | 0.4% |
| cfunc varargs | 20 | 0.4% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       666240 | 47.5% |
|          hit |       735900 | 52.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 31.2% |
| Failure | 440 | 68.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 240 | 54.5% |
| tuple | 160 | 36.4% |
| other | 40 | 9.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      9856700 | 14.2% |
| specialization.deopt |          100 | 0.0% |
|          hit |     59725180 | 85.8% |
|         miss |         6700 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 4.0% |
| Failure | 3,380 | 96.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict values | 1,480 | 43.8% |
| other | 1,020 | 30.2% |
| itertools | 580 | 17.2% |
| dict keys | 120 | 3.6% |
| zip | 100 | 3.0% |
| set | 40 | 1.2% |
| enumerate | 20 | 0.6% |
| dict items | 20 | 0.6% |


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
| specialization.deferred |     16534660 | 35.6% |
| specialization.deopt |           40 | 0.0% |
|          hit |     29902960 | 64.4% |
|         miss |         3860 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,440 | 25.8% |
| Failure | 7,000 | 74.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class method obj | 2,520 | 36.0% |
| shadowed | 1,600 | 22.9% |
| not managed dict | 960 | 13.7% |
| method | 820 | 11.7% |
| module attr not found | 520 | 7.4% |
| metaclass attribute | 460 | 6.6% |
| class attr simple | 120 | 1.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           40 | 0.0% |
| specialization.deopt |           80 | 0.0% |
|          hit |    122388780 | 100.0% |
|         miss |         3460 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,760 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          240 | 100.0% |


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
| specialization.deferred |         1680 | 7.1% |
|          hit |        20100 | 85.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,320 | 73.3% |
| Failure | 480 | 26.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overriding descriptor | 300 | 62.5% |
| method | 120 | 25.0% |
| no dict | 40 | 8.3% |
| property | 20 | 4.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          360 | 0.0% |
|          hit |     16817640 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 71.4% |
| Failure | 40 | 28.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 40 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 854,936,460 | 56.2% |
| Not specialized | 225,060,280 | 14.8% |
| Specialized | 440,933,860 | 29.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,380 | 100.0% |
| LOAD_ATTR | 16,534,660 | 0.0% |
| FOR_ITER | 9,856,700 | 0.0% |
| TO_BOOL | 8,923,840 | 0.0% |
| CALL | 6,606,480 | 0.0% |
| COMPARE_OP | 666,240 | 0.0% |
| BINARY_OP | 7,620 | 0.0% |
| BINARY_SUBSCR | 6,060 | 0.0% |
| STORE_ATTR | 1,680 | 0.0% |
| UNPACK_SEQUENCE | 360 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_STR | 318,000 | 94.1% |
| FOR_ITER_LIST | 5,440 | 1.6% |
| LOAD_ATTR_SLOT | 3,620 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 2,860 | 0.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,200 | 0.7% |
| CALL_PY_EXACT_ARGS | 1,480 | 0.4% |
| FOR_ITER_GEN | 1,260 | 0.4% |
| RESUME_CHECK | 940 | 0.3% |
| RESUME | 940 | 0.3% |
| LOAD_GLOBAL_MODULE | 600 | 0.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 15,480,380 | 17.8% |
| Calls to Python functions inlined | 71,323,300 | 82.2% |
| Calls via PyEval_EvalFrame (total) | 15,480,380 | 17.8% |
| Calls via PyEval_EvalFrame (vector) | 3,714,000 | 4.3% |
| Calls via PyEval_EvalFrame (generator) | 11,766,380 | 13.6% |
| Calls via PyEval_EvalFrame (legacy) | 3,300,300 | 3.8% |
| Calls via PyEval_EvalFrame (function vectorcall) | 413,700 | 0.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 540 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,020 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 29,431,440 | 33.9% |
| Frame objects created | 5,280 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 34,764,860 | 47.7% |
| Frees to freelist | 34,765,920 |  |
| Allocations | 38,082,660 | 52.3% |
| Allocations to 512 bytes | 38,077,920 | 52.3% |
| Allocations to 4 kbytes | 2,340 | 0.0% |
| Allocations over 4 kbytes | 2,400 | 0.0% |
| Frees | 40,922,767 |  |
| New values | 1,260 |  |
| Interpreter increfs | 593,792,640 | 80.6% |
| Interpreter decrefs | 623,309,260 | 78.3% |
| Increfs | 142,814,912 | 19.4% |
| Decrefs | 172,658,889 | 21.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 26,789,360 |  |
| Method cache misses | 5,980 |  |
| Method cache collisions | 5,206 |  |
| Method cache dunder hits | 6,778,281 |  |
| Method cache dunder misses | 859 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 1,080 | 2,400 | 1,612,400 |
| 1 | 100 | 2,620 | 2,795,560 |
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
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-10-19
