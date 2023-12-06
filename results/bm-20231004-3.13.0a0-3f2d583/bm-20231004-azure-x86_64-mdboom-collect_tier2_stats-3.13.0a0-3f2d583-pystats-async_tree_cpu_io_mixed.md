
# Pystats results

- benchmark: async_tree_cpu_io_mixed
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 296,454,500 | 17.9% | 17.9% |  |
| POP_JUMP_IF_FALSE | 95,804,820 | 5.8% | 23.6% |  |
| RESUME_CHECK | 86,541,480 | 5.2% | 28.9% | 0.0% |
| LOAD_FAST_LOAD_FAST | 77,733,420 | 4.7% | 33.5% |  |
| LOAD_CONST | 72,679,640 | 4.4% | 37.9% |  |
| STORE_FAST | 64,459,680 | 3.9% | 41.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 59,936,740 | 3.6% | 45.4% |  |
| POP_TOP | 56,986,140 | 3.4% | 48.9% |  |
| TO_BOOL_BOOL | 54,608,000 | 3.3% | 52.1% |  |
| STORE_ATTR_SLOT | 53,796,460 | 3.2% | 55.4% | 3.5% |
| RETURN_VALUE | 48,453,400 | 2.9% | 58.3% |  |
| LOAD_GLOBAL_MODULE | 47,334,980 | 2.9% | 61.2% |  |
| RETURN_CONST | 44,242,680 | 2.7% | 63.8% |  |
| CALL_PY_EXACT_ARGS | 40,612,880 | 2.4% | 66.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 40,188,200 | 2.4% | 68.7% |  |
| INTERPRETER_EXIT | 35,561,160 | 2.1% | 70.8% |  |
| CALL | 32,910,040 | 2.0% | 72.8% |  |
| PUSH_NULL | 31,816,080 | 1.9% | 74.7% |  |
| LOAD_ATTR_SLOT | 30,543,380 | 1.8% | 76.6% | 0.9% |
| LOAD_DEREF | 30,514,540 | 1.8% | 78.4% |  |
| LOAD_ATTR_MODULE | 26,043,780 | 1.6% | 80.0% |  |
| LOAD_ATTR | 23,810,140 | 1.4% | 81.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 23,805,180 | 1.4% | 82.9% | 0.0% |
| POP_JUMP_IF_NOT_NONE | 23,240,980 | 1.4% | 84.3% |  |
| TO_BOOL_NONE | 18,618,820 | 1.1% | 85.4% |  |
| ENTER_EXECUTOR | 17,724,800 | 1.1% | 86.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 15,605,600 | 0.9% | 87.4% | 21.9% |
| CALL_METHOD_DESCRIPTOR_O | 14,137,580 | 0.9% | 88.2% | 0.0% |
| COMPARE_OP_INT | 12,637,820 | 0.8% | 89.0% |  |
| POP_JUMP_IF_NONE | 10,078,200 | 0.6% | 89.6% |  |
| LOAD_GLOBAL_BUILTIN | 9,671,360 | 0.6% | 90.2% | 0.0% |
| BINARY_OP_ADD_INT | 9,521,620 | 0.6% | 90.8% |  |
| STORE_DEREF | 9,517,620 | 0.6% | 91.3% |  |
| CALL_FUNCTION_EX | 8,260,140 | 0.5% | 91.8% |  |
| CALL_KW | 7,978,820 | 0.5% | 92.3% |  |
| RETURN_GENERATOR | 7,841,520 | 0.5% | 92.8% |  |
| POP_JUMP_IF_TRUE | 7,562,800 | 0.5% | 93.3% |  |
| CALL_BUILTIN_O | 7,454,840 | 0.4% | 93.7% |  |
| CALL_LIST_APPEND | 6,718,320 | 0.4% | 94.1% |  |
| GET_AWAITABLE | 5,182,760 | 0.3% | 94.4% |  |
| END_SEND | 5,182,760 | 0.3% | 94.7% |  |
| SEND_GEN | 5,044,820 | 0.3% | 95.0% |  |
| COMPARE_OP_FLOAT | 4,343,740 | 0.3% | 95.3% |  |
| NOP | 4,204,180 | 0.3% | 95.5% |  |
| COPY_FREE_VARS | 4,201,000 | 0.3% | 95.8% |  |
| TO_BOOL | 3,921,960 | 0.2% | 96.0% |  |
| STORE_ATTR | 3,921,140 | 0.2% | 96.3% |  |
| CONTAINS_OP | 3,919,140 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST | 3,499,940 | 0.2% | 96.7% |  |
| JUMP_FORWARD | 3,362,400 | 0.2% | 96.9% |  |
| TO_BOOL_LIST | 3,362,160 | 0.2% | 97.1% |  |
| COPY | 3,361,080 | 0.2% | 97.3% |  |
| IS_OP | 3,359,460 | 0.2% | 97.5% |  |
| STORE_SUBSCR_DICT | 3,359,220 | 0.2% | 97.7% |  |
| CALL_TYPE_1 | 3,359,220 | 0.2% | 97.9% |  |
| LIST_APPEND | 3,359,160 | 0.2% | 98.1% |  |
| MAKE_CELL | 2,799,360 | 0.2% | 98.3% |  |
| BUILD_LIST | 2,523,580 | 0.2% | 98.5% |  |
| GET_ITER | 2,243,760 | 0.1% | 98.6% |  |
| BINARY_OP_SUBTRACT_INT | 1,961,540 | 0.1% | 98.7% |  |
| SWAP | 1,679,820 | 0.1% | 98.8% |  |
| CALL_ISINSTANCE | 1,544,560 | 0.1% | 98.9% |  |
| CALL_PY_WITH_DEFAULTS | 1,542,580 | 0.1% | 99.0% |  |
| LOAD_ATTR_CLASS | 1,401,740 | 0.1% | 99.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,401,680 | 0.1% | 99.2% |  |
| SEND | 1,401,260 | 0.1% | 99.3% |  |
| YIELD_VALUE | 1,262,980 | 0.1% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 1,262,980 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,261,200 | 0.1% | 99.5% |  |
| FOR_ITER_LIST | 1,122,540 | 0.1% | 99.6% |  |
| LOAD_SUPER_ATTR_METHOD | 841,660 | 0.1% | 99.6% |  |
| BUILD_MAP | 700,700 | 0.0% | 99.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 562,740 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 561,840 | 0.0% | 99.7% |  |
| FOR_ITER_RANGE | 561,240 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 560,340 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 560,040 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 560,040 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 559,860 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 559,860 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 559,860 | 0.0% | 99.9% |  |
| LIST_EXTEND | 282,580 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 282,580 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 141,980 | 0.0% | 100.0% |  |
| COMPARE_OP | 140,800 | 0.0% | 100.0% |  |
| CALL_LEN | 4,140 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 1,740 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,560 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,160 | 0.0% | 100.0% |  |
| BINARY_OP | 680 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| FOR_ITER | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 160 | 0.0% | 100.0% |  |
| UNARY_NOT | 120 | 0.0% | 100.0% |  |
| UNARY_INVERT | 120 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 120 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 120 | 0.0% | 100.0% |  |
| POP_EXCEPT | 120 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| DICT_MERGE | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 56,016,700 | 3.4% | 3.4% |
| RESUME_CHECK LOAD_FAST | 56,006,280 | 3.4% | 6.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 50,231,900 | 3.0% | 9.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 47,607,820 | 2.9% | 12.6% |
| STORE_FAST LOAD_FAST | 43,696,720 | 2.6% | 15.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 35,570,180 | 2.1% | 17.4% |
| LOAD_FAST LOAD_ATTR_SLOT | 30,397,440 | 1.8% | 19.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 30,378,840 | 1.8% | 21.1% |
| CACHE RESUME_CHECK | 28,142,260 | 1.7% | 22.8% |
| LOAD_CONST LOAD_FAST | 27,443,580 | 1.7% | 24.4% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 26,464,120 | 1.6% | 26.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 26,043,080 | 1.6% | 27.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 25,902,520 | 1.6% | 29.2% |
| LOAD_FAST LOAD_ATTR | 23,660,300 | 1.4% | 30.6% |
| LOAD_FAST STORE_ATTR_SLOT | 23,382,340 | 1.4% | 32.0% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 22,678,680 | 1.4% | 33.4% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 21,842,460 | 1.3% | 34.7% |
| RETURN_CONST INTERPRETER_EXIT | 21,697,260 | 1.3% | 36.0% |
| LOAD_FAST RETURN_VALUE | 21,215,720 | 1.3% | 37.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 19,881,520 | 1.2% | 38.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 19,181,740 | 1.2% | 39.6% |
| RETURN_CONST POP_TOP | 19,045,360 | 1.1% | 40.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 18,757,760 | 1.1% | 41.9% |
| POP_TOP LOAD_FAST | 18,621,640 | 1.1% | 43.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 18,618,820 | 1.1% | 44.1% |
| CALL STORE_FAST | 18,478,580 | 1.1% | 45.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 17,644,820 | 1.1% | 46.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 17,218,260 | 1.0% | 47.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,804,460 | 1.0% | 48.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 15,401,880 | 0.9% | 49.3% |
| STORE_ATTR_SLOT LOAD_CONST | 15,400,500 | 0.9% | 50.2% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 15,259,600 | 0.9% | 51.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 14,421,480 | 0.9% | 52.0% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 14,137,580 | 0.9% | 52.9% |
| RETURN_VALUE INTERPRETER_EXIT | 13,163,440 | 0.8% | 53.7% |
| RETURN_VALUE STORE_FAST | 13,022,720 | 0.8% | 54.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 12,637,820 | 0.8% | 55.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 11,760,200 | 0.7% | 55.9% |
| LOAD_CONST STORE_FAST | 11,485,480 | 0.7% | 56.6% |
| POP_TOP RETURN_CONST | 11,060,100 | 0.7% | 57.3% |
| RETURN_VALUE TO_BOOL_BOOL | 11,059,880 | 0.7% | 57.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 11,059,620 | 0.7% | 58.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 10,919,020 | 0.7% | 59.3% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 10,918,900 | 0.7% | 59.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 10,778,240 | 0.6% | 60.6% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 10,778,060 | 0.6% | 61.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 10,778,020 | 0.6% | 61.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 10,218,200 | 0.6% | 62.5% |
| PUSH_NULL LOAD_FAST | 9,694,620 | 0.6% | 63.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 8,820,520 | 0.5% | 63.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 8,405,460 | 0.5% | 64.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 8,269,060 | 0.5% | 64.6% |
| LOAD_FAST LOAD_CONST | 8,125,040 | 0.5% | 65.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 8,119,980 | 0.5% | 65.6% |
| POP_TOP RESUME_CHECK | 7,841,520 | 0.5% | 66.1% |
| STORE_ATTR_SLOT LOAD_FAST | 7,841,060 | 0.5% | 66.5% |
| STORE_ATTR_SLOT RETURN_CONST | 7,840,940 | 0.5% | 67.0% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 7,840,820 | 0.5% | 67.5% |
| PUSH_NULL CALL | 7,702,360 | 0.5% | 67.9% |
| POP_TOP LOAD_CONST | 7,701,960 | 0.5% | 68.4% |
| STORE_FAST RETURN_CONST | 7,560,880 | 0.5% | 68.9% |
| LOAD_FAST CALL | 7,560,080 | 0.5% | 69.3% |
| CALL_FUNCTION_EX POP_TOP | 7,559,620 | 0.5% | 69.8% |
| LOAD_FAST_LOAD_FAST CALL | 7,559,560 | 0.5% | 70.2% |
| POP_TOP ENTER_EXECUTOR | 7,559,500 | 0.5% | 70.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,419,080 | 0.4% | 71.1% |
| ENTER_EXECUTOR CALL_FUNCTION_EX | 7,417,520 | 0.4% | 71.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 7,000,120 | 0.4% | 72.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,718,740 | 0.4% | 72.4% |
| LOAD_DEREF LOAD_CONST | 6,718,440 | 0.4% | 72.8% |
| POP_JUMP_IF_NONE LOAD_DEREF | 6,718,320 | 0.4% | 73.2% |
| LOAD_FAST CALL_LIST_APPEND | 6,718,320 | 0.4% | 73.6% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 6,718,320 | 0.4% | 74.0% |
| BINARY_OP_ADD_INT STORE_DEREF | 6,718,320 | 0.4% | 74.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 6,165,360 | 0.4% | 74.8% |
| LOAD_CONST COMPARE_OP_INT | 6,164,240 | 0.4% | 75.2% |
| LOAD_FAST CALL_BUILTIN_O | 6,056,900 | 0.4% | 75.5% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 6,021,560 | 0.4% | 75.9% |
| CALL_BUILTIN_O STORE_FAST | 5,916,380 | 0.4% | 76.3% |
| LOAD_FAST PUSH_NULL | 5,630,780 | 0.3% | 76.6% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 5,320,760 | 0.3% | 76.9% |
| GET_AWAITABLE LOAD_CONST | 5,182,760 | 0.3% | 77.2% |
| LOAD_CONST CALL_KW | 5,179,520 | 0.3% | 77.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 5,043,700 | 0.3% | 77.9% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 4,901,500 | 0.3% | 78.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS STORE_FAST | 4,762,160 | 0.3% | 78.4% |
| RETURN_VALUE RETURN_VALUE | 4,761,140 | 0.3% | 78.7% |
| STORE_FAST LOAD_GLOBAL_MODULE | 4,761,000 | 0.3% | 79.0% |
| SEND_GEN POP_TOP | 4,482,300 | 0.3% | 79.3% |
| RETURN_GENERATOR GET_AWAITABLE | 4,482,300 | 0.3% | 79.5% |
| LOAD_CONST SEND_GEN | 4,482,300 | 0.3% | 79.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 4,481,800 | 0.3% | 80.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 4,373,580 | 0.3% | 80.4% |
| RETURN_VALUE END_SEND | 4,341,580 | 0.3% | 80.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 4,205,280 | 0.3% | 80.9% |
| NOP LOAD_FAST | 4,203,640 | 0.3% | 81.1% |
| COPY_FREE_VARS RESUME_CHECK | 4,200,880 | 0.3% | 81.4% |
| CALL POP_TOP | 4,059,920 | 0.2% | 81.6% |
| CACHE COPY_FREE_VARS | 4,059,680 | 0.2% | 81.9% |
| LOAD_ATTR CALL | 3,919,400 | 0.2% | 82.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 28,142,260 | 79.1% |
| COPY_FREE_VARS | 4,059,680 | 11.4% |
| POP_TOP | 3,359,220 | 9.4% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 100.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,341,580 | 83.8% |
| SEND | 700,460 | 13.5% |
| RETURN_CONST | 140,720 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,640,540 | 70.2% |
| RETURN_VALUE | 1,401,620 | 27.0% |
| LOAD_FAST | 140,600 | 2.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,122,480 | 50.0% |
| CALL_BUILTIN_CLASS | 561,300 | 25.0% |
| LOAD_DEREF | 559,860 | 25.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,122,520 | 50.0% |
| LOAD_FAST_AND_CLEAR | 559,860 | 25.0% |
| FOR_ITER_TUPLE | 559,860 | 25.0% |
| FOR_ITER_RANGE | 1,380 | 0.1% |
| FOR_ITER | 140 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 21,697,260 | 61.0% |
| RETURN_VALUE | 13,163,440 | 37.0% |
| YIELD_VALUE | 700,460 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 560,040 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 2,799,420 | 66.6% |
| RESUME_CHECK | 702,320 | 16.7% |
| STORE_FAST | 702,020 | 16.7% |
| POP_TOP | 300 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,203,640 | 100.0% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 50.0% |
| COPY | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| RERAISE | 60 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 19,045,360 | 33.4% |
| CALL_METHOD_DESCRIPTOR_O | 14,137,580 | 24.8% |
| CALL_FUNCTION_EX | 7,559,620 | 13.3% |
| SEND_GEN | 4,482,300 | 7.9% |
| CALL | 4,059,920 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,621,640 | 32.7% |
| RETURN_CONST | 11,060,100 | 19.4% |
| RESUME_CHECK | 7,841,520 | 13.8% |
| LOAD_CONST | 7,701,960 | 13.5% |
| ENTER_EXECUTOR | 7,559,500 | 13.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 60 | 50.0% |
| BINARY_SUBSCR_DICT | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 25,902,520 | 81.4% |
| LOAD_FAST | 5,630,780 | 17.7% |
| LOAD_ATTR | 282,720 | 0.9% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,918,900 | 34.3% |
| LOAD_FAST | 9,694,620 | 30.5% |
| CALL | 7,702,360 | 24.2% |
| LOAD_GLOBAL_MODULE | 1,538,340 | 4.8% |
| LOAD_CONST | 1,401,800 | 4.4% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,901,500 | 62.5% |
| ENTER_EXECUTOR | 2,799,300 | 35.7% |
| CALL_PY_WITH_DEFAULTS | 140,600 | 1.8% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 4,482,300 | 57.2% |
| LIST_APPEND | 3,359,160 | 42.8% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,215,720 | 43.8% |
| LOAD_ATTR_INSTANCE_VALUE | 11,760,200 | 24.3% |
| RETURN_VALUE | 4,761,140 | 9.8% |
| POP_JUMP_IF_FALSE | 3,359,280 | 6.9% |
| COMPARE_OP_FLOAT | 1,544,140 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 13,163,440 | 27.2% |
| STORE_FAST | 13,022,720 | 26.9% |
| TO_BOOL_BOOL | 11,059,880 | 22.8% |
| RETURN_VALUE | 4,761,140 | 9.8% |
| END_SEND | 4,341,580 | 9.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,360,660 | 85.7% |
| LOAD_FAST | 559,920 | 14.3% |
| TO_BOOL | 1,000 | 0.0% |
| RETURN_VALUE | 160 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,359,220 | 85.7% |
| POP_JUMP_IF_TRUE | 561,240 | 14.3% |
| TO_BOOL | 1,000 | 0.0% |
| TO_BOOL_BOOL | 380 | 0.0% |
| TO_BOOL_INT | 120 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 50.0% |
| BINARY_OP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 120 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 60 | 50.0% |
| TO_BOOL_BOOL | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| COPY | 60 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 26.5% |
| LOAD_FAST | 140 | 20.6% |
| BINARY_OP | 140 | 20.6% |
| UNARY_INVERT | 120 | 17.6% |
| POP_JUMP_IF_FALSE | 60 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 140 | 20.6% |
| STORE_FAST | 120 | 17.6% |
| LOAD_GLOBAL_MODULE | 120 | 17.6% |
| COPY | 120 | 17.6% |
| UNARY_INVERT | 60 | 8.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 561,240 | 22.2% |
| SWAP | 559,860 | 22.2% |
| STORE_DEREF | 559,860 | 22.2% |
| POP_JUMP_IF_FALSE | 559,860 | 22.2% |
| LOAD_ATTR_SLOT | 141,980 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,121,100 | 44.4% |
| SWAP | 559,860 | 22.2% |
| STORE_DEREF | 559,860 | 22.2% |
| LOAD_FAST | 282,760 | 11.2% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 79.9% |
| LOAD_FAST | 140,600 | 20.1% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 79.9% |
| CALL_FUNCTION_EX | 140,600 | 20.1% |
| LOAD_FAST | 240 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,040 | 99.9% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560,040 | 99.9% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| BUILD_MAP | 60 | 0.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,702,360 | 23.4% |
| LOAD_FAST | 7,560,080 | 23.0% |
| LOAD_FAST_LOAD_FAST | 7,559,560 | 23.0% |
| LOAD_ATTR | 3,919,400 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,260 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,478,580 | 56.1% |
| POP_TOP | 4,059,920 | 12.3% |
| RESUME_CHECK | 3,499,940 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 3,359,260 | 10.2% |
| LOAD_GLOBAL_MODULE | 2,799,420 | 8.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,417,520 | 89.8% |
| STORE_FAST | 559,860 | 6.8% |
| CALL_INTRINSIC_1 | 141,980 | 1.7% |
| BUILD_MAP | 140,600 | 1.7% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,559,620 | 91.5% |
| MAKE_CELL | 559,860 | 6.8% |
| STORE_FAST | 140,600 | 1.7% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 282,580 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 141,980 | 50.2% |
| LOAD_CONST | 140,600 | 49.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,179,520 | 64.9% |
| ENTER_EXECUTOR | 2,799,300 | 35.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,359,220 | 42.1% |
| RESUME_CHECK | 3,359,220 | 42.1% |
| POP_TOP | 559,920 | 7.0% |
| STORE_DEREF | 559,860 | 7.0% |
| RETURN_VALUE | 140,600 | 1.8% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 140,620 | 99.9% |
| CALL_BUILTIN_CLASS | 120 | 0.1% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140,720 | 99.9% |
| COMPARE_OP | 60 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,359,220 | 85.7% |
| LOAD_FAST_LOAD_FAST | 559,860 | 14.3% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,919,140 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,359,280 | 99.9% |
| CALL_LEN | 1,380 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| BINARY_OP | 120 | 0.0% |
| UNARY_NOT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,359,360 | 99.9% |
| TO_BOOL_INT | 1,460 | 0.0% |
| TO_BOOL | 80 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| POP_EXCEPT | 60 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 4,059,680 | 96.6% |
| CALL_PY_EXACT_ARGS | 141,200 | 3.4% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,200,880 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,559,500 | 42.6% |
| CALL_LIST_APPEND | 6,718,320 | 37.9% |
| LIST_APPEND | 3,359,160 | 19.0% |
| POP_JUMP_IF_FALSE | 69,220 | 0.4% |
| ENTER_EXECUTOR | 18,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 7,417,520 | 41.8% |
| RETURN_GENERATOR | 2,799,300 | 15.8% |
| CALL_KW | 2,799,300 | 15.8% |
| CALL | 2,799,300 | 15.8% |
| SWAP | 559,860 | 3.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 140 | 77.8% |
| FOR_ITER | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |
| FOR_ITER | 40 | 22.2% |
| FOR_ITER_LIST | 20 | 11.1% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 4,482,300 | 86.5% |
| RETURN_VALUE | 559,860 | 10.8% |
| LOAD_FAST | 140,600 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,182,760 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,359,160 | 100.0% |
| LOAD_CONST | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,359,160 | 100.0% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,262,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 700,460 | 55.5% |
| SEND_GEN | 562,520 | 44.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,359,220 | 99.9% |
| STORE_FAST | 3,060 | 0.1% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |
| ENTER_EXECUTOR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,359,160 | 99.9% |
| LOAD_FAST | 1,740 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 1,440 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,359,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,359,160 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 141,980 | 50.2% |
| LOAD_FAST | 140,600 | 49.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 282,580 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,660,300 | 99.4% |
| LOAD_ATTR_SLOT | 142,040 | 0.6% |
| LOAD_ATTR | 6,320 | 0.0% |
| LOAD_GLOBAL_MODULE | 580 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,778,060 | 45.3% |
| CALL | 3,919,400 | 16.5% |
| LOAD_FAST | 3,500,060 | 14.7% |
| TO_BOOL_NONE | 3,359,220 | 14.1% |
| STORE_FAST | 1,961,540 | 8.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 15,400,500 | 21.2% |
| POP_JUMP_IF_FALSE | 14,421,480 | 19.8% |
| LOAD_FAST | 8,125,040 | 11.2% |
| POP_TOP | 7,701,960 | 10.6% |
| LOAD_DEREF | 6,718,440 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,443,580 | 37.8% |
| STORE_FAST | 11,485,480 | 15.8% |
| BINARY_OP_ADD_INT | 8,119,980 | 11.2% |
| COMPARE_OP_INT | 6,164,240 | 8.5% |
| CALL_KW | 5,179,520 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,718,320 | 22.0% |
| POP_JUMP_IF_FALSE | 3,919,020 | 12.8% |
| RESUME_CHECK | 3,359,220 | 11.0% |
| STORE_DEREF | 3,359,160 | 11.0% |
| STORE_ATTR | 3,359,160 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,718,440 | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,919,020 | 12.8% |
| TO_BOOL_BOOL | 3,359,160 | 11.0% |
| POP_JUMP_IF_NONE | 3,359,160 | 11.0% |
| LOAD_DEREF | 3,359,160 | 11.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 56,006,280 | 18.9% |
| POP_JUMP_IF_FALSE | 50,231,900 | 16.9% |
| STORE_FAST | 43,696,720 | 14.7% |
| LOAD_CONST | 27,443,580 | 9.3% |
| LOAD_ATTR_METHOD_NO_DICT | 18,757,760 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 56,016,700 | 18.9% |
| LOAD_ATTR_SLOT | 30,397,440 | 10.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 26,464,120 | 8.9% |
| LOAD_ATTR | 23,660,300 | 8.0% |
| STORE_ATTR_SLOT | 23,382,340 | 7.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 559,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 559,860 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 22,678,680 | 29.2% |
| LOAD_FAST_LOAD_FAST | 11,059,620 | 14.2% |
| PUSH_NULL | 10,918,900 | 14.0% |
| POP_JUMP_IF_NOT_NONE | 10,218,200 | 13.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,820,520 | 11.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 30,378,840 | 39.1% |
| LOAD_FAST_LOAD_FAST | 11,059,620 | 14.2% |
| LOAD_FAST | 10,919,020 | 14.0% |
| CALL | 7,559,560 | 9.7% |
| LOAD_CONST | 5,320,760 | 6.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 220 | 19.0% |
| POP_TOP | 220 | 19.0% |
| LOAD_FAST | 140 | 12.1% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 10.3% |
| STORE_FAST | 100 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 860 | 74.1% |
| LOAD_GLOBAL_BUILTIN | 280 | 24.1% |
| LOAD_ATTR | 20 | 1.7% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 160 | 100.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,239,440 | 80.0% |
| CALL_FUNCTION_EX | 559,860 | 20.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,239,440 | 80.0% |
| RESUME_CHECK | 559,920 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 47,607,820 | 49.7% |
| TO_BOOL_NONE | 18,618,820 | 19.4% |
| COMPARE_OP_INT | 12,637,820 | 13.2% |
| CONTAINS_OP | 3,919,140 | 4.1% |
| TO_BOOL_LIST | 3,362,160 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,231,900 | 52.4% |
| RETURN_CONST | 17,218,260 | 18.0% |
| LOAD_CONST | 14,421,480 | 15.1% |
| LOAD_GLOBAL_MODULE | 4,481,800 | 4.7% |
| LOAD_DEREF | 3,919,020 | 4.1% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,718,740 | 66.7% |
| LOAD_DEREF | 3,359,160 | 33.3% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 6,718,320 | 66.7% |
| LOAD_FAST | 3,359,340 | 33.3% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,881,520 | 85.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,220 | 14.5% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,218,200 | 44.0% |
| LOAD_GLOBAL_MODULE | 6,021,560 | 25.9% |
| LOAD_FAST | 3,641,920 | 15.7% |
| NOP | 2,799,420 | 12.0% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,000,120 | 92.6% |
| TO_BOOL | 561,240 | 7.4% |
| TO_BOOL_INT | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,419,080 | 98.1% |
| LOAD_CONST | 142,040 | 1.9% |
| STORE_FAST | 1,380 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 60 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 60 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,218,260 | 38.9% |
| POP_TOP | 11,060,100 | 25.0% |
| STORE_ATTR_SLOT | 7,840,940 | 17.7% |
| STORE_FAST | 7,560,880 | 17.1% |
| STORE_ATTR_INSTANCE_VALUE | 560,460 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 21,697,260 | 49.0% |
| POP_TOP | 19,045,360 | 43.0% |
| TO_BOOL_BOOL | 3,359,220 | 7.6% |
| END_SEND | 140,720 | 0.3% |
| EXIT_INIT_CHECK | 120 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 700,460 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 700,460 | 50.0% |
| SEND | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 700,460 | 50.0% |
| END_SEND | 700,460 | 50.0% |
| SEND | 340 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 560,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 560,040 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,920 | 85.7% |
| LOAD_FAST_LOAD_FAST | 559,920 | 14.3% |
| STORE_ATTR | 1,020 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| SWAP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,359,160 | 85.7% |
| LOAD_CONST | 559,860 | 14.3% |
| STORE_ATTR | 1,020 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 800 | 0.0% |
| LOAD_FAST | 180 | 0.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,718,320 | 70.6% |
| LOAD_CONST | 1,679,580 | 17.6% |
| CALL_KW | 559,860 | 5.9% |
| BUILD_LIST | 559,860 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,359,160 | 35.3% |
| LOAD_DEREF | 3,359,160 | 35.3% |
| LOAD_FAST | 1,119,720 | 11.8% |
| LOAD_CONST | 1,119,720 | 11.8% |
| BUILD_LIST | 559,860 | 5.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 18,478,580 | 28.7% |
| RETURN_VALUE | 13,022,720 | 20.2% |
| LOAD_CONST | 11,485,480 | 17.8% |
| CALL_BUILTIN_O | 5,916,380 | 9.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,762,160 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,696,720 | 67.8% |
| RETURN_CONST | 7,560,880 | 11.7% |
| LOAD_GLOBAL_MODULE | 4,761,000 | 7.4% |
| LOAD_FAST_LOAD_FAST | 4,373,580 | 6.8% |
| LOAD_CONST | 1,119,900 | 1.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 559,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 559,860 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 559,860 | 33.3% |
| ENTER_EXECUTOR | 559,860 | 33.3% |
| BUILD_LIST | 559,860 | 33.3% |
| LOAD_FAST | 60 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,920 | 33.3% |
| FOR_ITER_RANGE | 559,860 | 33.3% |
| BUILD_LIST | 559,860 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| POP_EXCEPT | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 33.3% |
| RETURN_VALUE | 20 | 33.3% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 700,460 | 55.5% |
| YIELD_VALUE | 562,520 | 44.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 700,460 | 55.5% |
| YIELD_VALUE | 562,520 | 44.5% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,600 | 99.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,380 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,600 | 99.0% |
| STORE_FAST | 1,380 | 1.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,119,980 | 85.3% |
| RETURN_VALUE | 1,401,620 | 14.7% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 6,718,320 | 70.6% |
| RETURN_VALUE | 1,401,620 | 14.7% |
| CALL_PY_WITH_DEFAULTS | 1,401,620 | 14.7% |
| SWAP | 60 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 1,401,620 | 71.5% |
| LOAD_CONST | 559,900 | 28.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,401,620 | 71.5% |
| CALL_PY_EXACT_ARGS | 559,860 | 28.5% |
| SWAP | 60 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_FAST | 40 | 33.3% |
| BINARY_SUBSCR | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| PUSH_EXC_INFO | 60 | 50.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 50.0% |
| LOAD_ATTR_SLOT | 120 | 50.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,401,620 | 100.0% |
| PUSH_NULL | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,401,620 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 559,860 | 99.6% |
| LOAD_FAST | 1,560 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 561,300 | 99.9% |
| LOAD_FAST | 180 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| COMPARE_OP | 120 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,359,340 | 96.0% |
| LOAD_FAST | 140,600 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,359,280 | 96.0% |
| POP_TOP | 140,600 | 4.0% |
| TO_BOOL_BOOL | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,056,900 | 81.2% |
| LOAD_GLOBAL_MODULE | 1,397,740 | 18.7% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,916,380 | 79.4% |
| RETURN_VALUE | 1,397,740 | 18.7% |
| TO_BOOL_BOOL | 140,600 | 1.9% |
| POP_TOP | 120 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,544,180 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| CALL | 40 | 0.0% |
| BUILD_TUPLE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,544,520 | 100.0% |
| TO_BOOL | 40 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,760 | 66.7% |
| COPY | 1,380 | 33.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,718,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,718,320 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,261,020 | 100.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,261,020 | 100.0% |
| RETURN_VALUE | 120 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,380 | 88.5% |
| LOAD_CONST | 60 | 3.8% |
| LOAD_FAST | 40 | 2.6% |
| LOAD_ATTR | 40 | 2.6% |
| CALL | 40 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,380 | 88.5% |
| POP_TOP | 120 | 7.7% |
| RETURN_VALUE | 60 | 3.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 10,778,060 | 69.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,359,160 | 21.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,403,440 | 9.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.4% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,778,020 | 69.1% |
| STORE_FAST | 4,762,160 | 30.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.4% |
| POP_TOP | 360 | 0.0% |
| CALL | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,778,240 | 76.2% |
| CALL | 3,359,260 | 23.8% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,137,580 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 21,842,460 | 53.8% |
| LOAD_FAST | 17,644,820 | 43.4% |
| BINARY_OP_SUBTRACT_INT | 559,860 | 1.4% |
| LOAD_ATTR_METHOD_NO_DICT | 282,700 | 0.7% |
| LOAD_SUPER_ATTR_METHOD | 140,800 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 35,570,180 | 87.6% |
| RETURN_GENERATOR | 4,901,500 | 12.1% |
| COPY_FREE_VARS | 141,200 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,401,620 | 90.9% |
| LOAD_GLOBAL_MODULE | 140,600 | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,401,980 | 90.9% |
| RETURN_GENERATOR | 140,600 | 9.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,359,220 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,799,480 | 64.4% |
| LOAD_ATTR_SLOT | 1,544,140 | 35.5% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,799,600 | 64.5% |
| RETURN_VALUE | 1,544,140 | 35.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,164,240 | 48.8% |
| LOAD_DEREF | 3,359,160 | 26.6% |
| LOAD_FAST_LOAD_FAST | 1,711,400 | 13.5% |
| LOAD_GLOBAL_MODULE | 1,403,000 | 11.1% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,637,820 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,122,520 | 100.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 49.9% |
| LOAD_DEREF | 559,860 | 49.9% |
| RETURN_CONST | 1,440 | 0.1% |
| LOAD_FAST | 1,380 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 559,860 | 99.8% |
| GET_ITER | 1,380 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 559,860 | 99.8% |
| STORE_FAST | 1,380 | 0.2% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 559,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,401,620 | 100.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,401,740 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,016,700 | 93.5% |
| LOAD_FAST_LOAD_FAST | 3,359,380 | 5.6% |
| LOAD_DEREF | 559,860 | 0.9% |
| LOAD_ATTR | 600 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 19,181,740 | 32.0% |
| LOAD_ATTR_METHOD_NO_DICT | 15,401,880 | 25.7% |
| RETURN_VALUE | 11,760,200 | 19.6% |
| TO_BOOL_LIST | 3,362,160 | 5.6% |
| TO_BOOL | 3,360,660 | 5.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 15,401,880 | 64.7% |
| LOAD_FAST | 5,043,700 | 21.2% |
| LOAD_DEREF | 3,359,160 | 14.1% |
| LOAD_ATTR | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,757,760 | 78.8% |
| LOAD_GLOBAL_MODULE | 3,359,220 | 14.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,403,440 | 5.9% |
| CALL_PY_EXACT_ARGS | 282,700 | 1.2% |
| LOAD_FAST_LOAD_FAST | 1,500 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,464,120 | 65.9% |
| LOAD_ATTR_SLOT | 7,840,820 | 19.5% |
| LOAD_DEREF | 3,919,020 | 9.8% |
| LOAD_FAST_LOAD_FAST | 1,401,660 | 3.5% |
| STORE_FAST_LOAD_FAST | 559,860 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 21,842,460 | 54.4% |
| LOAD_FAST_LOAD_FAST | 8,820,520 | 21.9% |
| LOAD_FAST | 6,165,360 | 15.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,359,160 | 8.4% |
| CALL | 400 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 26,043,080 | 100.0% |
| LOAD_ATTR | 580 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 25,902,520 | 99.5% |
| LOAD_FAST_LOAD_FAST | 140,600 | 0.5% |
| LOAD_ATTR | 260 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| UNARY_INVERT | 60 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,397,440 | 99.5% |
| ENTER_EXECUTOR | 140,600 | 0.5% |
| LOAD_ATTR_SLOT | 5,200 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 15,259,600 | 50.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,840,820 | 25.7% |
| LOAD_CONST | 3,359,400 | 11.0% |
| LOAD_FAST | 1,544,260 | 5.1% |
| COMPARE_OP_FLOAT | 1,544,140 | 5.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,405,460 | 86.9% |
| PUSH_NULL | 559,860 | 5.8% |
| POP_JUMP_IF_NOT_NONE | 559,860 | 5.8% |
| POP_TOP | 140,780 | 1.5% |
| JUMP_FORWARD | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,269,060 | 85.5% |
| LOAD_DEREF | 841,660 | 8.7% |
| LOAD_GLOBAL_MODULE | 559,900 | 5.8% |
| CALL_ISINSTANCE | 300 | 0.0% |
| CALL_BUILTIN_CLASS | 180 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,804,460 | 35.5% |
| POP_JUMP_IF_NOT_NONE | 6,021,560 | 12.7% |
| STORE_FAST | 4,761,000 | 10.1% |
| POP_JUMP_IF_FALSE | 4,481,800 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,359,220 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 26,043,080 | 55.0% |
| LOAD_FAST | 4,205,280 | 8.9% |
| LOAD_FAST_LOAD_FAST | 3,919,320 | 8.3% |
| CONTAINS_OP | 3,359,220 | 7.1% |
| COMPARE_OP_FLOAT | 2,799,480 | 5.9% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 841,500 | 100.0% |
| LOAD_SUPER_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,100 | 66.5% |
| CALL_PY_EXACT_ARGS | 140,800 | 16.7% |
| LOAD_FAST_LOAD_FAST | 140,660 | 16.7% |
| CALL | 100 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,570,180 | 41.1% |
| CACHE | 28,142,260 | 32.5% |
| POP_TOP | 7,841,520 | 9.1% |
| COPY_FREE_VARS | 4,200,880 | 4.9% |
| CALL | 3,499,940 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,006,280 | 64.7% |
| LOAD_GLOBAL_MODULE | 16,804,460 | 19.4% |
| LOAD_GLOBAL_BUILTIN | 8,405,460 | 9.7% |
| LOAD_DEREF | 3,359,220 | 3.9% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,262,980 | 1.5% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,482,300 | 88.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 562,520 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,482,300 | 88.8% |
| RESUME_CHECK | 562,520 | 11.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 561,620 | 99.8% |
| STORE_ATTR | 800 | 0.1% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 560,460 | 99.6% |
| LOAD_CONST | 780 | 0.1% |
| LOAD_FAST | 720 | 0.1% |
| LOAD_GLOBAL_MODULE | 300 | 0.1% |
| BUILD_LIST | 180 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 30,378,840 | 56.5% |
| LOAD_FAST | 23,382,340 | 43.5% |
| STORE_ATTR_SLOT | 35,280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 22,678,680 | 42.2% |
| LOAD_CONST | 15,400,500 | 28.6% |
| LOAD_FAST | 7,841,060 | 14.6% |
| RETURN_CONST | 7,840,940 | 14.6% |
| STORE_ATTR_SLOT | 35,280 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,160 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,220 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 19,181,740 | 35.1% |
| RETURN_VALUE | 11,059,880 | 20.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,778,020 | 19.7% |
| COPY | 3,359,360 | 6.2% |
| RETURN_CONST | 3,359,220 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 47,607,820 | 87.2% |
| POP_JUMP_IF_TRUE | 7,000,120 | 12.8% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,460 | 83.9% |
| TO_BOOL | 120 | 6.9% |
| LOAD_FAST | 80 | 4.6% |
| LOAD_ATTR | 40 | 2.3% |
| BINARY_OP | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,440 | 82.8% |
| POP_JUMP_IF_FALSE | 240 | 13.8% |
| UNARY_NOT | 60 | 3.4% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,362,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,362,160 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 15,259,600 | 82.0% |
| LOAD_ATTR | 3,359,220 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,618,820 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE | 60 | 33.3% |
| STORE_FAST | 40 | 22.2% |
| RETURN_VALUE | 40 | 22.2% |
| CALL | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          420 | 95.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3359220 | 100.0% |

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
| specialization.deferred |      3920460 | 4.9% |
|          hit |     76590720 | 95.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 33.3% |
| Failure | 1,000 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 820 | 82.0% |
| tuple | 140 | 14.0% |
| sequence | 40 | 4.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          480 | 0.0% |
|          hit |     11625200 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 30.0% |
| Failure | 140 | 70.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 80 | 57.1% |
| or | 40 | 28.6% |
| true divide other | 20 | 14.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     32899880 | 24.9% |
| specialization.deopt |        64600 | 0.0% |
|          hit |     95683620 | 72.5% |
|         miss |      3424120 | 2.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 66,180 | 88.5% |
| Failure | 8,580 | 11.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 2,700 | 31.5% |
| no dict | 1,860 | 21.7% |
| cfunc noargs | 1,080 | 12.6% |
| code complex parameters | 900 | 10.5% |
| class no vectorcall | 860 | 10.0% |
| other | 820 | 9.6% |
| cmethod | 140 | 1.6% |
| class mutable | 80 | 0.9% |
| cfunc varargs | 40 | 0.5% |
| wrong number arguments | 40 | 0.5% |
| init not simple | 20 | 0.2% |
| operator wrapper | 20 | 0.2% |
| cfunc varargs keywords | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       140720 | 0.8% |
|          hit |     16981560 | 99.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 25.0% |
| Failure | 60 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 40 | 66.7% |
| bool | 20 | 33.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 0.0% |
|          hit |      2243640 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 33.3% |
| Failure | 40 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 40 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     23801580 | 11.6% |
| specialization.deopt |         5240 | 0.0% |
|          hit |    181641660 | 88.3% |
|         miss |       277420 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,480 | 54.2% |
| Failure | 6,320 | 45.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 4,580 | 72.5% |
| class attr descriptor | 820 | 13.0% |
| method | 660 | 10.4% |
| not managed dict | 140 | 2.2% |
| class attr simple | 40 | 0.6% |
| metaclass attribute | 40 | 0.6% |
| non object slot | 40 | 0.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     57006280 | 100.0% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,140 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       841660 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1400920 | 21.7% |
|          hit |      5044820 | 78.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 340 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 340 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3919320 | 6.7% |
| specialization.deopt |        35280 | 0.1% |
|          hit |     52492120 | 90.1% |
|         miss |      1867080 | 3.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 36,080 | 97.3% |
| Failure | 1,020 | 2.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overriding descriptor | 840 | 82.4% |
| no dict | 140 | 13.7% |
| overridden | 40 | 3.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          180 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 862,195,640 | 52.0% |
| Not specialized | 208,397,820 | 12.6% |
| Specialized | 588,616,180 | 35.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,190,997,600 | 100.0% |
| CALL | 32,899,880 | 0.0% |
| LOAD_ATTR | 23,801,580 | 0.0% |
| TO_BOOL | 3,920,460 | 0.0% |
| STORE_ATTR | 3,919,320 | 0.0% |
| SEND | 1,400,920 | 0.0% |
| COMPARE_OP | 140,720 | 0.0% |
| BINARY_OP | 480 | 0.0% |
| FOR_ITER | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,424,000 | 60.7% |
| STORE_ATTR_SLOT | 1,867,080 | 33.1% |
| LOAD_ATTR_SLOT | 275,300 | 4.9% |
| RESUME_CHECK | 34,720 | 0.6% |
| RESUME | 34,720 | 0.6% |
| LOAD_ATTR_METHOD_NO_DICT | 2,120 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 35,561,160 | 38.8% |
| Calls to Python functions inlined | 56,021,220 | 61.2% |
| Calls via PyEval_EvalFrame (total) | 35,561,160 | 38.8% |
| Calls via PyEval_EvalFrame (vector) | 31,501,480 | 34.4% |
| Calls via PyEval_EvalFrame (generator) | 4,059,680 | 4.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 31,501,480 | 34.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 1,544,140 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 559,920 | 0.6% |
| Calls via PyEval_EvalFrame (api) | 3,359,280 | 3.7% |
| Calls via PyEval_EvalFrame (method) | 14,837,800 | 16.2% |
| Frames pushed | 92,696,140 | 101.2% |
| Frame objects created | 120 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 48,787,723 | 18.4% |
| Frees to freelist | 49,108,623 |  |
| Allocations | 216,608,102 | 81.6% |
| Allocations to 512 bytes | 215,165,534 | 81.1% |
| Allocations to 4 kbytes | 1,442,560 | 0.5% |
| Allocations over 4 kbytes | 8 | 0.0% |
| Frees | 218,284,598 |  |
| New values | 180 |  |
| Interpreter increfs | 841,386,500 | 68.0% |
| Interpreter decrefs | 896,390,340 | 60.3% |
| Increfs | 396,190,340 | 32.0% |
| Decrefs | 590,755,099 | 39.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 66,686,296 |  |
| Method cache misses | 560,584 |  |
| Method cache collisions | 562,867 |  |
| Method cache dunder hits | 9,661,630 |  |
| Method cache dunder misses | 3,050 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 38,520 | 0 | 257,214,000 |
| 1 | 3,500 | 0 | 259,181,760 |
| 2 | 320 | 0 | 641,340,480 |


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
| Traces executed | 17,724,800 |  |
| Uops executed | 717,843,400 | 40 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,680,960 | 9.5% |
| <= 16 | 87,700 | 0.5% |
| <= 32 | 8,538,500 | 48.2% |
| <= 64 | 0 | 0.0% |
| <= 128 | 7,417,520 | 41.8% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1024 | 0 | 0.0% |
| <= 2048 | 0 | 0.0% |
| <= 4096 | 0 | 0.0% |
| <= 8192 | 0 | 0.0% |
| <= 16384 | 40 | 0.0% |
| <= 32768 | 20 | 0.0% |
| <= 65536 | 0 | 0.0% |
| <= 131072 | 60 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 199,576,040 | 27.8% | 27.8% |
| LOAD_FAST | 76,136,880 | 10.6% | 38.4% |
| _GUARD_TYPE_VERSION | 63,546,060 | 8.9% | 47.3% |
| _POP_JUMP_IF_TRUE | 35,498,240 | 4.9% | 52.2% |
| _LOAD_ATTR_SLOT | 29,810,620 | 4.2% | 56.4% |
| STORE_FAST | 23,881,540 | 3.3% | 59.7% |
| TO_BOOL_BOOL | 17,634,340 | 2.5% | 62.1% |
| _EXIT_TRACE | 17,584,200 | 2.4% | 64.6% |
| _LOAD_ATTR_INSTANCE_VALUE | 15,537,620 | 2.2% | 66.8% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 15,537,620 | 2.2% | 68.9% |
| _LOAD_ATTR_METHOD_NO_DICT | 15,116,120 | 2.1% | 71.0% |
| LOAD_ATTR | 13,016,120 | 1.8% | 72.8% |
| _ITER_CHECK_RANGE | 10,918,660 | 1.5% | 74.4% |
| _IS_ITER_EXHAUSTED_RANGE | 10,918,660 | 1.5% | 75.9% |
| _ITER_NEXT_RANGE | 10,357,420 | 1.4% | 77.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,357,420 | 1.4% | 78.8% |
| _SAVE_CURRENT_IP | 10,218,140 | 1.4% | 80.2% |
| _PUSH_FRAME | 10,218,140 | 1.4% | 81.6% |
| _INIT_CALL_PY_EXACT_ARGS | 10,218,140 | 1.4% | 83.0% |
| _CHECK_STACK_SPACE | 10,218,140 | 1.4% | 84.5% |
| _CHECK_PEP_523 | 10,218,140 | 1.4% | 85.9% |
| _CHECK_FUNCTION_EXACT_ARGS | 10,218,140 | 1.4% | 87.3% |
| PUSH_NULL | 7,644,380 | 1.1% | 88.4% |
| RESUME_CHECK | 7,417,520 | 1.0% | 89.4% |
| LIST_EXTEND | 7,417,520 | 1.0% | 90.4% |
| CALL_INTRINSIC_1 | 7,417,520 | 1.0% | 91.5% |
| BUILD_LIST | 7,417,520 | 1.0% | 92.5% |
| LOAD_CONST | 5,879,620 | 0.8% | 93.3% |
| _ITER_CHECK_TUPLE | 3,359,160 | 0.5% | 93.8% |
| _ITER_CHECK_LIST | 3,359,160 | 0.5% | 94.3% |
| _IS_ITER_EXHAUSTED_TUPLE | 3,359,160 | 0.5% | 94.7% |
| _IS_ITER_EXHAUSTED_LIST | 3,359,160 | 0.5% | 95.2% |
| _POP_JUMP_IF_FALSE | 2,939,780 | 0.4% | 95.6% |
| _LOAD_GLOBAL_MODULE | 2,939,780 | 0.4% | 96.0% |
| _GUARD_GLOBALS_VERSION | 2,939,780 | 0.4% | 96.4% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,800,620 | 0.4% | 96.8% |
| _GUARD_KEYS_VERSION | 2,800,620 | 0.4% | 97.2% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,800,620 | 0.4% | 97.6% |
| _ITER_NEXT_TUPLE | 2,799,300 | 0.4% | 98.0% |
| _ITER_NEXT_LIST | 2,799,300 | 0.4% | 98.4% |
| _GUARD_BOTH_INT | 2,799,300 | 0.4% | 98.8% |
| _BINARY_OP_SUBTRACT_INT | 2,799,300 | 0.4% | 99.2% |
| CONTAINS_OP | 2,799,300 | 0.4% | 99.5% |
| POP_TOP | 1,821,440 | 0.3% | 99.8% |
| CALL_BUILTIN_O | 226,860 | 0.0% | 99.8% |
| COMPARE_OP_FLOAT | 140,540 | 0.0% | 99.9% |
| BINARY_SUBSCR_LIST_INT | 140,540 | 0.0% | 99.9% |
| _STORE_ATTR_SLOT | 140,480 | 0.0% | 99.9% |
| _LOAD_ATTR_MODULE | 140,480 | 0.0% | 99.9% |
| _CHECK_ATTR_MODULE | 140,480 | 0.0% | 99.9% |
| TO_BOOL_LIST | 140,480 | 0.0% | 99.9% |
| CALL_METHOD_DESCRIPTOR_O | 140,480 | 0.0% | 100.0% |
| _JUMP_TO_TOP | 140,420 | 0.0% | 100.0% |
| COMPARE_OP_INT | 86,380 | 0.0% | 100.0% |


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
Stats gathered on: 2023-10-04
