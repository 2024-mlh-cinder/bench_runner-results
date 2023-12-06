
# Pystats results

- benchmark: async_tree_memoization
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 384,420,220 | 18.9% | 18.9% |  |
| POP_JUMP_IF_FALSE | 120,014,860 | 5.9% | 24.8% |  |
| RESUME_CHECK | 102,018,640 | 5.0% | 29.9% | 0.0% |
| LOAD_FAST_LOAD_FAST | 85,932,740 | 4.2% | 34.1% |  |
| STORE_FAST | 85,407,280 | 4.2% | 38.3% |  |
| LOAD_CONST | 83,912,900 | 4.1% | 42.4% |  |
| TO_BOOL_BOOL | 74,625,580 | 3.7% | 46.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 71,067,920 | 3.5% | 49.6% |  |
| LOAD_ATTR_SLOT | 66,710,880 | 3.3% | 52.9% | 0.8% |
| POP_TOP | 58,160,760 | 2.9% | 55.8% |  |
| STORE_ATTR_SLOT | 56,809,180 | 2.8% | 58.6% | 6.1% |
| RETURN_VALUE | 54,488,520 | 2.7% | 61.3% |  |
| CALL_PY_EXACT_ARGS | 52,856,940 | 2.6% | 63.9% |  |
| LOAD_GLOBAL_MODULE | 48,047,180 | 2.4% | 66.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 47,272,820 | 2.3% | 68.6% |  |
| RETURN_CONST | 45,866,520 | 2.3% | 70.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 42,528,900 | 2.1% | 72.9% | 0.0% |
| PUSH_NULL | 40,039,540 | 2.0% | 74.9% |  |
| INTERPRETER_EXIT | 38,263,400 | 1.9% | 76.8% |  |
| LOAD_ATTR | 33,304,280 | 1.6% | 78.4% |  |
| CALL | 31,057,420 | 1.5% | 79.9% |  |
| LOAD_DEREF | 30,785,180 | 1.5% | 81.5% |  |
| POP_JUMP_IF_NOT_NONE | 25,180,000 | 1.2% | 82.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,967,420 | 1.2% | 83.9% | 13.7% |
| LOAD_ATTR_MODULE | 24,873,420 | 1.2% | 85.2% |  |
| TO_BOOL_NONE | 19,295,420 | 1.0% | 86.1% |  |
| COMPARE_OP_INT | 18,536,700 | 0.9% | 87.0% |  |
| ENTER_EXECUTOR | 18,355,040 | 0.9% | 87.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 14,548,700 | 0.7% | 88.6% | 0.0% |
| CALL_BUILTIN_O | 12,367,100 | 0.6% | 89.2% |  |
| BINARY_OP_ADD_INT | 12,317,100 | 0.6% | 89.9% |  |
| NOP | 12,027,660 | 0.6% | 90.4% |  |
| LOAD_GLOBAL_BUILTIN | 11,697,000 | 0.6% | 91.0% | 0.0% |
| BUILD_LIST | 10,347,060 | 0.5% | 91.5% |  |
| POP_JUMP_IF_NONE | 10,078,200 | 0.5% | 92.0% |  |
| STORE_DEREF | 9,517,620 | 0.5% | 92.5% |  |
| CALL_FUNCTION_EX | 8,666,100 | 0.4% | 92.9% |  |
| CALL_KW | 8,114,140 | 0.4% | 93.3% |  |
| LIST_EXTEND | 8,106,060 | 0.4% | 93.7% |  |
| CALL_INTRINSIC_1 | 8,106,060 | 0.4% | 94.1% |  |
| POP_JUMP_IF_TRUE | 7,833,440 | 0.4% | 94.5% |  |
| CALL_LIST_APPEND | 6,718,320 | 0.3% | 94.8% |  |
| RETURN_GENERATOR | 6,710,540 | 0.3% | 95.2% |  |
| BINARY_OP_SUBTRACT_INT | 6,158,580 | 0.3% | 95.5% |  |
| COPY_FREE_VARS | 4,471,640 | 0.2% | 95.7% |  |
| GET_AWAITABLE | 4,187,100 | 0.2% | 95.9% |  |
| END_SEND | 4,187,100 | 0.2% | 96.1% |  |
| SEND_GEN | 4,179,200 | 0.2% | 96.3% |  |
| TO_BOOL | 3,921,960 | 0.2% | 96.5% |  |
| STORE_ATTR | 3,921,140 | 0.2% | 96.7% |  |
| CONTAINS_OP | 3,919,140 | 0.2% | 96.9% |  |
| TO_BOOL_LIST | 3,637,960 | 0.2% | 97.1% |  |
| CALL_BUILTIN_FAST | 3,635,260 | 0.2% | 97.2% |  |
| COMPARE_OP_FLOAT | 3,575,240 | 0.2% | 97.4% |  |
| JUMP_FORWARD | 3,362,400 | 0.2% | 97.6% |  |
| COPY | 3,361,080 | 0.2% | 97.8% |  |
| IS_OP | 3,359,460 | 0.2% | 97.9% |  |
| STORE_SUBSCR_DICT | 3,359,220 | 0.2% | 98.1% |  |
| CALL_TYPE_1 | 3,359,220 | 0.2% | 98.3% |  |
| LIST_APPEND | 3,359,160 | 0.2% | 98.4% |  |
| CALL_ISINSTANCE | 3,299,560 | 0.2% | 98.6% |  |
| CALL_PY_WITH_DEFAULTS | 3,075,640 | 0.2% | 98.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,799,420 | 0.1% | 98.9% |  |
| MAKE_CELL | 2,799,360 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,523,620 | 0.1% | 99.1% |  |
| GET_ITER | 2,243,760 | 0.1% | 99.2% |  |
| SWAP | 1,679,820 | 0.1% | 99.3% |  |
| SEND | 1,671,980 | 0.1% | 99.4% |  |
| YIELD_VALUE | 1,663,660 | 0.1% | 99.5% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 1,663,660 | 0.1% | 99.6% |  |
| FOR_ITER_LIST | 1,122,540 | 0.1% | 99.6% |  |
| LOAD_SUPER_ATTR_METHOD | 1,112,300 | 0.1% | 99.7% |  |
| BUILD_MAP | 836,020 | 0.0% | 99.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 562,740 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 561,840 | 0.0% | 99.8% |  |
| FOR_ITER_RANGE | 561,240 | 0.0% | 99.8% |  |
| BUILD_TUPLE | 560,340 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 560,040 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 560,040 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 559,860 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 559,860 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 559,860 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 277,300 | 0.0% | 100.0% |  |
| COMPARE_OP | 276,140 | 0.0% | 100.0% |  |
| CALL_LEN | 4,140 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 1,740 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,560 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,320 | 0.0% | 100.0% |  |
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
| LOAD_ATTR_CLASS | 120 | 0.0% | 100.0% |  |
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
| POP_JUMP_IF_FALSE LOAD_FAST | 73,736,820 | 3.6% | 3.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 67,354,760 | 3.3% | 7.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 67,147,880 | 3.3% | 10.3% |
| LOAD_FAST LOAD_ATTR_SLOT | 66,424,520 | 3.3% | 13.5% |
| RESUME_CHECK LOAD_FAST | 60,966,880 | 3.0% | 16.5% |
| STORE_FAST LOAD_FAST | 59,326,100 | 2.9% | 19.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 46,145,920 | 2.3% | 21.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 31,596,720 | 1.6% | 23.3% |
| CACHE RESUME_CHECK | 30,709,180 | 1.5% | 24.8% |
| LOAD_CONST LOAD_FAST | 29,343,220 | 1.4% | 26.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 28,810,420 | 1.4% | 27.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 27,411,180 | 1.4% | 29.0% |
| LOAD_FAST LOAD_ATTR | 25,464,000 | 1.3% | 30.3% |
| LOAD_FAST STORE_ATTR_SLOT | 25,146,660 | 1.2% | 31.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 24,872,720 | 1.2% | 32.7% |
| LOAD_ATTR_MODULE PUSH_NULL | 24,596,840 | 1.2% | 33.9% |
| LOAD_FAST RETURN_VALUE | 24,485,920 | 1.2% | 35.1% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 23,490,600 | 1.2% | 36.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 22,926,340 | 1.1% | 37.4% |
| RETURN_CONST INTERPRETER_EXIT | 22,103,220 | 1.1% | 38.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 21,820,540 | 1.1% | 39.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 20,431,300 | 1.0% | 40.6% |
| RETURN_CONST POP_TOP | 20,127,920 | 1.0% | 41.6% |
| PUSH_NULL LOAD_FAST | 19,905,520 | 1.0% | 42.6% |
| POP_TOP LOAD_FAST | 19,574,040 | 1.0% | 43.5% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 19,295,420 | 1.0% | 44.5% |
| CALL STORE_FAST | 19,019,860 | 0.9% | 45.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 18,536,700 | 0.9% | 46.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 17,911,580 | 0.9% | 47.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 17,624,220 | 0.9% | 48.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 17,341,860 | 0.9% | 48.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 17,075,420 | 0.8% | 49.8% |
| STORE_ATTR_SLOT LOAD_CONST | 16,212,420 | 0.8% | 50.6% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 15,936,200 | 0.8% | 51.4% |
| RETURN_VALUE INTERPRETER_EXIT | 15,324,400 | 0.8% | 52.1% |
| POP_JUMP_IF_FALSE LOAD_CONST | 14,827,440 | 0.7% | 52.9% |
| RETURN_VALUE STORE_FAST | 14,826,420 | 0.7% | 53.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 14,548,700 | 0.7% | 54.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 14,264,920 | 0.7% | 55.0% |
| LOAD_FAST LOAD_CONST | 13,990,460 | 0.7% | 55.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS STORE_FAST | 13,988,660 | 0.7% | 56.4% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 12,301,480 | 0.6% | 57.0% |
| LOAD_FAST CALL_BUILTIN_O | 12,091,100 | 0.6% | 57.6% |
| CALL_BUILTIN_O STORE_FAST | 12,091,060 | 0.6% | 58.2% |
| NOP LOAD_FAST | 12,027,120 | 0.6% | 58.8% |
| LOAD_CONST STORE_FAST | 11,756,120 | 0.6% | 59.4% |
| POP_TOP RETURN_CONST | 11,466,060 | 0.6% | 59.9% |
| RETURN_VALUE TO_BOOL_BOOL | 11,465,840 | 0.6% | 60.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 11,465,580 | 0.6% | 61.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 11,189,660 | 0.6% | 61.6% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 11,189,540 | 0.6% | 62.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 11,189,360 | 0.6% | 62.7% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 10,913,380 | 0.5% | 63.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 10,913,340 | 0.5% | 63.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,633,040 | 0.5% | 64.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 10,629,940 | 0.5% | 64.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,353,580 | 0.5% | 65.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 10,353,520 | 0.5% | 65.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 10,295,780 | 0.5% | 66.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 10,024,060 | 0.5% | 66.8% |
| LOAD_CONST BINARY_OP_ADD_INT | 9,517,720 | 0.5% | 67.3% |
| LOAD_CONST COMPARE_OP_INT | 8,959,720 | 0.4% | 67.8% |
| STORE_ATTR_SLOT LOAD_FAST | 8,658,140 | 0.4% | 68.2% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 8,658,080 | 0.4% | 68.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 8,398,500 | 0.4% | 69.0% |
| RESUME_CHECK NOP | 8,390,480 | 0.4% | 69.4% |
| STORE_ATTR_SLOT RETURN_CONST | 8,382,220 | 0.4% | 69.8% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 8,382,100 | 0.4% | 70.3% |
| POP_TOP LOAD_CONST | 8,107,920 | 0.4% | 70.7% |
| BUILD_LIST LOAD_FAST | 8,106,240 | 0.4% | 71.1% |
| LOAD_ATTR PUSH_NULL | 8,106,200 | 0.4% | 71.5% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 8,106,180 | 0.4% | 71.9% |
| LIST_EXTEND CALL_INTRINSIC_1 | 8,106,060 | 0.4% | 72.3% |
| STORE_FAST RETURN_CONST | 7,831,520 | 0.4% | 72.6% |
| LOAD_FAST CALL | 7,830,720 | 0.4% | 73.0% |
| CALL_FUNCTION_EX POP_TOP | 7,830,260 | 0.4% | 73.4% |
| LOAD_FAST_LOAD_FAST CALL | 7,830,200 | 0.4% | 73.8% |
| LOAD_ATTR_SLOT LOAD_ATTR | 7,830,200 | 0.4% | 74.2% |
| POP_TOP ENTER_EXECUTOR | 7,830,140 | 0.4% | 74.6% |
| LOAD_ATTR_SLOT LIST_EXTEND | 7,830,140 | 0.4% | 75.0% |
| LOAD_ATTR_SLOT BUILD_LIST | 7,830,140 | 0.4% | 75.3% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 7,830,140 | 0.4% | 75.7% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_NO_DICT | 7,828,760 | 0.4% | 76.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 7,612,300 | 0.4% | 76.5% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 7,554,620 | 0.4% | 76.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,554,400 | 0.4% | 77.2% |
| LOAD_FAST PUSH_NULL | 7,336,440 | 0.4% | 77.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 7,270,760 | 0.4% | 78.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,718,740 | 0.3% | 78.3% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 6,718,500 | 0.3% | 78.6% |
| LOAD_DEREF LOAD_CONST | 6,718,440 | 0.3% | 78.9% |
| POP_JUMP_IF_NONE LOAD_DEREF | 6,718,320 | 0.3% | 79.3% |
| LOAD_FAST CALL_LIST_APPEND | 6,718,320 | 0.3% | 79.6% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 6,718,320 | 0.3% | 79.9% |
| BINARY_OP_ADD_INT STORE_DEREF | 6,718,320 | 0.3% | 80.3% |
| POP_TOP RESUME_CHECK | 6,710,540 | 0.3% | 80.6% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 6,434,500 | 0.3% | 80.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 6,376,040 | 0.3% | 81.2% |
| RETURN_VALUE RETURN_VALUE | 6,158,880 | 0.3% | 81.5% |
| STORE_FAST LOAD_GLOBAL_MODULE | 6,158,740 | 0.3% | 81.8% |


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
| RESUME_CHECK | 30,709,180 | 80.3% |
| COPY_FREE_VARS | 4,195,000 | 11.0% |
| POP_TOP | 3,359,220 | 8.8% |


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
| RETURN_VALUE | 3,075,280 | 73.4% |
| SEND | 835,780 | 20.0% |
| RETURN_CONST | 276,040 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,911,180 | 93.4% |
| LOAD_FAST | 275,920 | 6.6% |


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
| RETURN_CONST | 22,103,220 | 57.8% |
| RETURN_VALUE | 15,324,400 | 40.0% |
| YIELD_VALUE | 835,780 | 2.2% |

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
| RESUME_CHECK | 8,390,480 | 69.8% |
| POP_JUMP_IF_NOT_NONE | 2,799,420 | 23.3% |
| STORE_FAST | 837,340 | 7.0% |
| POP_TOP | 300 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,027,120 | 100.0% |
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
| RETURN_CONST | 20,127,920 | 34.6% |
| CALL_METHOD_DESCRIPTOR_O | 14,548,700 | 25.0% |
| CALL_FUNCTION_EX | 7,830,260 | 13.5% |
| CALL | 4,195,240 | 7.2% |
| END_SEND | 3,911,180 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,574,040 | 33.7% |
| RETURN_CONST | 11,466,060 | 19.7% |
| LOAD_CONST | 8,107,920 | 13.9% |
| ENTER_EXECUTOR | 7,830,140 | 13.5% |
| RESUME_CHECK | 6,710,540 | 11.5% |


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
| LOAD_ATTR_MODULE | 24,596,840 | 61.4% |
| LOAD_ATTR | 8,106,200 | 20.2% |
| LOAD_FAST | 7,336,440 | 18.3% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,905,520 | 49.7% |
| LOAD_FAST_LOAD_FAST | 11,189,540 | 27.9% |
| CALL | 5,308,960 | 13.3% |
| LOAD_CONST | 2,799,540 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 1.4% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,434,500 | 95.9% |
| CALL_PY_WITH_DEFAULTS | 275,920 | 4.1% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 3,359,160 | 50.1% |
| GET_AWAITABLE | 3,351,320 | 49.9% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,485,920 | 44.9% |
| LOAD_ATTR_INSTANCE_VALUE | 12,301,480 | 22.6% |
| RETURN_VALUE | 6,158,880 | 11.3% |
| POP_JUMP_IF_FALSE | 3,359,280 | 6.2% |
| COMPARE_OP_FLOAT | 3,299,140 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 15,324,400 | 28.1% |
| STORE_FAST | 14,826,420 | 27.2% |
| TO_BOOL_BOOL | 11,465,840 | 21.0% |
| RETURN_VALUE | 6,158,880 | 11.3% |
| END_SEND | 3,075,280 | 5.6% |


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
| LOAD_ATTR_SLOT | 7,830,140 | 75.7% |
| STORE_FAST | 561,240 | 5.4% |
| SWAP | 559,860 | 5.4% |
| STORE_DEREF | 559,860 | 5.4% |
| POP_JUMP_IF_FALSE | 559,860 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,106,240 | 78.3% |
| STORE_FAST | 1,121,100 | 10.8% |
| SWAP | 559,860 | 5.4% |
| STORE_DEREF | 559,860 | 5.4% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 67.0% |
| LOAD_FAST | 275,920 | 33.0% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 67.0% |
| CALL_FUNCTION_EX | 275,920 | 33.0% |
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
| LOAD_FAST | 7,830,720 | 25.2% |
| LOAD_FAST_LOAD_FAST | 7,830,200 | 25.2% |
| PUSH_NULL | 5,308,960 | 17.1% |
| LOAD_ATTR | 3,919,400 | 12.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,260 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 19,019,860 | 61.2% |
| POP_TOP | 4,195,240 | 13.5% |
| RESUME_CHECK | 3,635,260 | 11.7% |
| CALL_METHOD_DESCRIPTOR_O | 3,359,260 | 10.8% |
| RETURN_VALUE | 837,340 | 2.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 7,830,140 | 90.4% |
| STORE_FAST | 559,860 | 6.5% |
| BUILD_MAP | 275,920 | 3.2% |
| LOAD_FAST | 120 | 0.0% |
| DICT_MERGE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,830,260 | 90.4% |
| MAKE_CELL | 559,860 | 6.5% |
| STORE_FAST | 275,920 | 3.2% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 8,106,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 7,830,140 | 96.6% |
| LOAD_CONST | 275,920 | 3.4% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,314,840 | 65.5% |
| ENTER_EXECUTOR | 2,799,300 | 34.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,359,220 | 41.4% |
| RESUME_CHECK | 3,359,220 | 41.4% |
| POP_TOP | 559,920 | 6.9% |
| STORE_DEREF | 559,860 | 6.9% |
| RETURN_VALUE | 275,920 | 3.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 275,940 | 99.9% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| COMPARE_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 276,040 | 100.0% |
| COMPARE_OP | 80 | 0.0% |
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
| CACHE | 4,195,000 | 93.8% |
| CALL_PY_EXACT_ARGS | 276,520 | 6.2% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,471,520 | 100.0% |
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
| POP_TOP | 7,830,140 | 42.7% |
| CALL_LIST_APPEND | 6,718,320 | 36.6% |
| LIST_APPEND | 3,359,160 | 18.3% |
| POP_JUMP_IF_FALSE | 410,200 | 2.2% |
| ENTER_EXECUTOR | 37,220 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 7,828,760 | 42.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,799,300 | 15.3% |
| CALL_KW | 2,799,300 | 15.3% |
| CALL | 2,799,300 | 15.3% |
| SWAP | 559,860 | 3.1% |


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
| RETURN_GENERATOR | 3,351,320 | 80.0% |
| RETURN_VALUE | 559,860 | 13.4% |
| LOAD_FAST | 275,920 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,187,100 | 100.0% |


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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320 | 100.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,663,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 835,780 | 50.2% |
| SEND_GEN | 827,880 | 49.8% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,359,220 | 99.9% |
| STORE_FAST | 3,060 | 0.1% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |

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
| LOAD_ATTR_SLOT | 7,830,140 | 96.6% |
| LOAD_FAST | 275,920 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 8,106,060 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,464,000 | 76.5% |
| LOAD_ATTR_SLOT | 7,830,200 | 23.5% |
| LOAD_ATTR | 8,600 | 0.0% |
| LOAD_GLOBAL_MODULE | 580 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,913,380 | 32.8% |
| PUSH_NULL | 8,106,200 | 24.3% |
| CALL | 3,919,400 | 11.8% |
| LOAD_FAST | 3,635,380 | 10.9% |
| STORE_FAST | 3,359,280 | 10.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 16,212,420 | 19.3% |
| POP_JUMP_IF_FALSE | 14,827,440 | 17.7% |
| LOAD_FAST | 13,990,460 | 16.7% |
| POP_TOP | 8,107,920 | 9.7% |
| LOAD_FAST_LOAD_FAST | 6,718,500 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,343,220 | 35.0% |
| STORE_FAST | 11,756,120 | 14.0% |
| BINARY_OP_ADD_INT | 9,517,720 | 11.3% |
| COMPARE_OP_INT | 8,959,720 | 10.7% |
| CALL_KW | 5,314,840 | 6.3% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,718,320 | 21.8% |
| POP_JUMP_IF_FALSE | 3,919,020 | 12.7% |
| RESUME_CHECK | 3,359,220 | 10.9% |
| STORE_DEREF | 3,359,160 | 10.9% |
| STORE_ATTR | 3,359,160 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,718,440 | 21.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,919,020 | 12.7% |
| TO_BOOL_BOOL | 3,359,160 | 10.9% |
| POP_JUMP_IF_NONE | 3,359,160 | 10.9% |
| LOAD_DEREF | 3,359,160 | 10.9% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 73,736,820 | 19.2% |
| RESUME_CHECK | 60,966,880 | 15.9% |
| STORE_FAST | 59,326,100 | 15.4% |
| LOAD_CONST | 29,343,220 | 7.6% |
| LOAD_ATTR_METHOD_NO_DICT | 20,431,300 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 67,147,880 | 17.5% |
| LOAD_ATTR_SLOT | 66,424,520 | 17.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 28,810,420 | 7.5% |
| LOAD_ATTR | 25,464,000 | 6.6% |
| STORE_ATTR_SLOT | 25,146,660 | 6.5% |


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
| STORE_ATTR_SLOT | 23,490,600 | 27.3% |
| LOAD_FAST_LOAD_FAST | 11,465,580 | 13.3% |
| PUSH_NULL | 11,189,540 | 13.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,353,580 | 12.0% |
| POP_JUMP_IF_NOT_NONE | 10,353,520 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 31,596,720 | 36.8% |
| LOAD_FAST_LOAD_FAST | 11,465,580 | 13.3% |
| LOAD_FAST | 11,189,660 | 13.0% |
| CALL | 7,830,200 | 9.1% |
| LOAD_CONST | 6,718,500 | 7.8% |


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
| TO_BOOL_BOOL | 67,354,760 | 56.1% |
| TO_BOOL_NONE | 19,295,420 | 16.1% |
| COMPARE_OP_INT | 18,536,700 | 15.4% |
| CONTAINS_OP | 3,919,140 | 3.3% |
| TO_BOOL_LIST | 3,637,960 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,736,820 | 61.4% |
| RETURN_CONST | 17,624,220 | 14.7% |
| LOAD_CONST | 14,827,440 | 12.4% |
| LOAD_DEREF | 3,919,020 | 3.3% |
| RETURN_VALUE | 3,359,280 | 2.8% |


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
| LOAD_FAST | 21,820,540 | 86.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,220 | 13.3% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,353,520 | 41.1% |
| LOAD_GLOBAL_MODULE | 7,554,620 | 30.0% |
| LOAD_FAST | 3,912,560 | 15.5% |
| NOP | 2,799,420 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 2.2% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,270,760 | 92.8% |
| TO_BOOL | 561,240 | 7.2% |
| TO_BOOL_INT | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,554,400 | 96.4% |
| LOAD_CONST | 277,360 | 3.5% |
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
| POP_JUMP_IF_FALSE | 17,624,220 | 38.4% |
| POP_TOP | 11,466,060 | 25.0% |
| STORE_ATTR_SLOT | 8,382,220 | 18.3% |
| STORE_FAST | 7,831,520 | 17.1% |
| STORE_ATTR_INSTANCE_VALUE | 560,460 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,103,220 | 48.2% |
| POP_TOP | 20,127,920 | 43.9% |
| TO_BOOL_BOOL | 3,359,220 | 7.3% |
| END_SEND | 276,040 | 0.6% |
| EXIT_INIT_CHECK | 120 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 835,780 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 835,780 | 50.0% |
| SEND | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 835,780 | 50.0% |
| END_SEND | 835,780 | 50.0% |
| SEND | 420 | 0.0% |


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
| CALL | 19,019,860 | 22.3% |
| RETURN_VALUE | 14,826,420 | 17.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 13,988,660 | 16.4% |
| CALL_BUILTIN_O | 12,091,060 | 14.2% |
| LOAD_CONST | 11,756,120 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,326,100 | 69.5% |
| RETURN_CONST | 7,831,520 | 9.2% |
| LOAD_FAST_LOAD_FAST | 7,612,300 | 8.9% |
| LOAD_GLOBAL_MODULE | 6,158,740 | 7.2% |
| LOAD_CONST | 1,395,700 | 1.6% |


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
| SEND | 835,780 | 50.2% |
| YIELD_VALUE | 827,880 | 49.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 835,780 | 50.2% |
| YIELD_VALUE | 827,880 | 49.8% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,920 | 99.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,380 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,920 | 99.5% |
| STORE_FAST | 1,380 | 0.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,517,720 | 77.3% |
| RETURN_VALUE | 2,799,360 | 22.7% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 6,718,320 | 54.5% |
| RETURN_VALUE | 2,799,360 | 22.7% |
| CALL_PY_WITH_DEFAULTS | 2,799,360 | 22.7% |
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
| LOAD_CONST | 3,359,200 | 54.5% |
| LOAD_FAST_LOAD_FAST | 2,799,360 | 45.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,359,160 | 54.5% |
| STORE_FAST | 2,799,360 | 45.5% |
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
| LOAD_CONST | 2,799,360 | 100.0% |
| PUSH_NULL | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,799,360 | 100.0% |
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
| LOAD_CONST | 3,359,340 | 92.4% |
| LOAD_FAST | 275,920 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,359,280 | 92.4% |
| POP_TOP | 275,920 | 7.6% |
| TO_BOOL_BOOL | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,091,100 | 97.8% |
| LOAD_ATTR_INSTANCE_VALUE | 275,920 | 2.2% |
| LOAD_CONST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,091,060 | 97.8% |
| TO_BOOL_BOOL | 275,920 | 2.2% |
| POP_TOP | 120 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,299,180 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| CALL | 40 | 0.0% |
| BUILD_TUPLE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,299,520 | 100.0% |
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
| LOAD_FAST | 2,523,440 | 100.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,523,440 | 100.0% |
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
| LOAD_ATTR | 10,913,380 | 43.7% |
| LOAD_ATTR_METHOD_NO_DICT | 10,629,940 | 42.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,359,160 | 13.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.3% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,988,660 | 56.0% |
| TO_BOOL_BOOL | 10,913,340 | 43.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.3% |
| POP_TOP | 360 | 0.0% |
| CALL | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,189,360 | 76.9% |
| CALL | 3,359,260 | 23.1% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,548,700 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 22,926,340 | 43.4% |
| LOAD_FAST | 17,911,580 | 33.9% |
| LOAD_ATTR_METHOD_NO_DICT | 8,106,180 | 15.3% |
| BINARY_OP_SUBTRACT_INT | 3,359,160 | 6.4% |
| LOAD_SUPER_ATTR_METHOD | 276,120 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 46,145,920 | 87.3% |
| RETURN_GENERATOR | 6,434,500 | 12.2% |
| COPY_FREE_VARS | 276,520 | 0.5% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,799,360 | 91.0% |
| LOAD_GLOBAL_MODULE | 275,920 | 9.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,799,720 | 91.0% |
| RETURN_GENERATOR | 275,920 | 9.0% |


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
| LOAD_ATTR_SLOT | 3,299,140 | 92.3% |
| LOAD_FAST | 275,980 | 7.7% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,299,140 | 92.3% |
| POP_JUMP_IF_FALSE | 276,100 | 7.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,959,720 | 48.3% |
| LOAD_FAST_LOAD_FAST | 3,417,060 | 18.4% |
| LOAD_DEREF | 3,359,160 | 18.1% |
| LOAD_GLOBAL_MODULE | 2,800,740 | 15.1% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,536,700 | 100.0% |


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
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,147,880 | 94.5% |
| LOAD_FAST_LOAD_FAST | 3,359,380 | 4.7% |
| LOAD_DEREF | 559,860 | 0.8% |
| LOAD_ATTR | 600 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 27,411,180 | 38.6% |
| LOAD_ATTR_METHOD_NO_DICT | 17,075,420 | 24.0% |
| RETURN_VALUE | 12,301,480 | 17.3% |
| TO_BOOL_LIST | 3,637,960 | 5.1% |
| TO_BOOL | 3,360,660 | 4.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,075,420 | 40.2% |
| LOAD_FAST | 14,264,920 | 33.5% |
| ENTER_EXECUTOR | 7,828,760 | 18.4% |
| LOAD_DEREF | 3,359,160 | 7.9% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,431,300 | 48.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,629,940 | 25.0% |
| CALL_PY_EXACT_ARGS | 8,106,180 | 19.1% |
| LOAD_GLOBAL_MODULE | 3,359,220 | 7.9% |
| LOAD_FAST_LOAD_FAST | 1,500 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,810,420 | 60.9% |
| LOAD_ATTR_SLOT | 8,382,100 | 17.7% |
| LOAD_DEREF | 3,919,020 | 8.3% |
| LOAD_FAST_LOAD_FAST | 2,799,400 | 5.9% |
| ENTER_EXECUTOR | 2,799,300 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 22,926,340 | 48.5% |
| LOAD_FAST | 10,633,040 | 22.5% |
| LOAD_FAST_LOAD_FAST | 10,353,580 | 21.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,359,160 | 7.1% |
| CALL | 400 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 24,872,720 | 100.0% |
| LOAD_ATTR | 580 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 24,596,840 | 98.9% |
| LOAD_FAST_LOAD_FAST | 275,920 | 1.1% |
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
| LOAD_FAST | 66,424,520 | 99.6% |
| ENTER_EXECUTOR | 275,860 | 0.4% |
| LOAD_ATTR_SLOT | 10,360 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 15,936,200 | 23.9% |
| TO_BOOL_BOOL | 8,658,080 | 13.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,382,100 | 12.6% |
| LOAD_ATTR | 7,830,200 | 11.7% |
| LIST_EXTEND | 7,830,140 | 11.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,295,780 | 88.0% |
| PUSH_NULL | 559,860 | 4.8% |
| POP_JUMP_IF_NOT_NONE | 559,860 | 4.8% |
| POP_TOP | 276,100 | 2.4% |
| JUMP_FORWARD | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,024,060 | 85.7% |
| LOAD_DEREF | 1,112,300 | 9.5% |
| LOAD_GLOBAL_MODULE | 559,900 | 4.8% |
| CALL_ISINSTANCE | 300 | 0.0% |
| CALL_BUILTIN_CLASS | 180 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 17,341,860 | 36.1% |
| POP_JUMP_IF_NOT_NONE | 7,554,620 | 15.7% |
| LOAD_FAST | 6,376,040 | 13.3% |
| STORE_FAST | 6,158,740 | 12.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,359,220 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 24,872,720 | 51.8% |
| LOAD_FAST | 8,398,500 | 17.5% |
| LOAD_FAST_LOAD_FAST | 3,919,320 | 8.2% |
| CONTAINS_OP | 3,359,220 | 7.0% |
| CALL_ISINSTANCE | 3,299,180 | 6.9% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,112,140 | 100.0% |
| LOAD_SUPER_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,100 | 50.4% |
| CALL_PY_EXACT_ARGS | 276,120 | 24.8% |
| LOAD_FAST_LOAD_FAST | 275,980 | 24.8% |
| CALL | 100 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 46,145,920 | 45.2% |
| CACHE | 30,709,180 | 30.1% |
| POP_TOP | 6,710,540 | 6.6% |
| COPY_FREE_VARS | 4,471,520 | 4.4% |
| CALL | 3,635,260 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,966,880 | 59.8% |
| LOAD_GLOBAL_MODULE | 17,341,860 | 17.0% |
| LOAD_GLOBAL_BUILTIN | 10,295,780 | 10.1% |
| NOP | 8,390,480 | 8.2% |
| LOAD_DEREF | 3,359,220 | 3.3% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,351,320 | 80.2% |
| JUMP_BACKWARD_NO_INTERRUPT | 827,880 | 19.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,351,320 | 80.2% |
| RESUME_CHECK | 827,880 | 19.8% |


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
| LOAD_FAST_LOAD_FAST | 31,596,720 | 55.6% |
| LOAD_FAST | 25,146,660 | 44.3% |
| STORE_ATTR_SLOT | 65,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,490,600 | 41.4% |
| LOAD_CONST | 16,212,420 | 28.5% |
| LOAD_FAST | 8,658,140 | 15.2% |
| RETURN_CONST | 8,382,220 | 14.8% |
| STORE_ATTR_SLOT | 65,800 | 0.1% |


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
| LOAD_ATTR_INSTANCE_VALUE | 27,411,180 | 36.7% |
| RETURN_VALUE | 11,465,840 | 15.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,913,340 | 14.6% |
| LOAD_ATTR_SLOT | 8,658,080 | 11.6% |
| COPY | 3,359,360 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 67,354,760 | 90.3% |
| POP_JUMP_IF_TRUE | 7,270,760 | 9.7% |
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
| LOAD_ATTR_INSTANCE_VALUE | 3,637,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,637,960 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 15,936,200 | 82.6% |
| LOAD_ATTR | 3,359,220 | 17.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,295,420 | 100.0% |


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
| specialization.deferred |      3920460 | 3.9% |
|          hit |     97560700 | 96.1% |

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
|          hit |     18753040 | 100.0% |

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
| specialization.deferred |     31047760 | 18.9% |
| specialization.deopt |        64600 | 0.0% |
|          hit |    130094160 | 79.0% |
|         miss |      3424120 | 2.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 66,180 | 89.1% |
| Failure | 8,080 | 10.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 2,720 | 33.7% |
| no dict | 1,940 | 24.0% |
| code complex parameters | 920 | 11.4% |
| class no vectorcall | 860 | 10.6% |
| other | 820 | 10.1% |
| cfunc noargs | 460 | 5.7% |
| cmethod | 140 | 1.7% |
| class mutable | 80 | 1.0% |
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
| specialization.deferred |       276040 | 1.2% |
|          hit |     22111940 | 98.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 20.0% |
| Failure | 80 | 80.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 60 | 75.0% |
| bool | 20 | 25.0% |


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
| specialization.deferred |     33293440 | 11.7% |
| specialization.deopt |        10600 | 0.0% |
|          hit |    251892180 | 88.1% |
|         miss |       561940 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,840 | 59.9% |
| Failure | 8,600 | 40.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 4,620 | 53.7% |
| method | 2,900 | 33.7% |
| class attr descriptor | 820 | 9.5% |
| not managed dict | 140 | 1.6% |
| class attr simple | 40 | 0.5% |
| metaclass attribute | 40 | 0.5% |
| non object slot | 40 | 0.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     59744120 | 100.0% |
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
|          hit |      1112300 | 100.0% |

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
| specialization.deferred |      1671560 | 28.6% |
|          hit |      4179200 | 71.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 420 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 420 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3919320 | 6.4% |
| specialization.deopt |        65800 | 0.1% |
|          hit |     53884200 | 87.9% |
|         miss |      3487720 | 5.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 66,600 | 98.5% |
| Failure | 1,020 | 1.5% |

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
| Basic | 1,041,121,920 | 51.3% |
| Not specialized | 244,774,606 | 12.1% |
| Specialized | 744,116,774 | 36.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,190,994,574 | 100.0% |
| LOAD_ATTR | 33,293,440 | 0.0% |
| CALL | 31,047,760 | 0.0% |
| TO_BOOL | 3,920,460 | 0.0% |
| STORE_ATTR | 3,919,320 | 0.0% |
| SEND | 1,671,560 | 0.0% |
| COMPARE_OP | 276,040 | 0.0% |
| BINARY_OP | 480 | 0.0% |
| FOR_ITER | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 3,487,720 | 46.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,424,000 | 45.4% |
| LOAD_ATTR_SLOT | 549,220 | 7.3% |
| RESUME_CHECK | 37,746 | 0.5% |
| RESUME | 37,746 | 0.5% |
| LOAD_ATTR_METHOD_NO_DICT | 12,720 | 0.2% |
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
| Calls to PyEval_EvalDefault | 38,263,400 | 35.2% |
| Calls to Python functions inlined | 70,465,780 | 64.8% |
| Calls via PyEval_EvalFrame (total) | 38,263,400 | 35.2% |
| Calls via PyEval_EvalFrame (vector) | 34,068,400 | 31.3% |
| Calls via PyEval_EvalFrame (generator) | 4,195,000 | 3.9% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 34,068,400 | 31.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,299,140 | 3.0% |
| Calls via PyEval_EvalFrame (function ex) | 559,920 | 0.5% |
| Calls via PyEval_EvalFrame (api) | 3,359,280 | 3.1% |
| Calls via PyEval_EvalFrame (method) | 15,108,440 | 13.9% |
| Frames pushed | 100,355,100 | 92.3% |
| Frame objects created | 120 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 48,009,528 | 36.8% |
| Frees to freelist | 48,340,847 |  |
| Allocations | 82,505,385 | 63.2% |
| Allocations to 512 bytes | 82,459,094 | 63.2% |
| Allocations to 4 kbytes | 46,277 | 0.0% |
| Allocations over 4 kbytes | 14 | 0.0% |
| Frees | 84,182,823 |  |
| New values | 180 |  |
| Interpreter increfs | 992,258,280 | 75.3% |
| Interpreter decrefs | 1,033,445,880 | 72.2% |
| Increfs | 325,421,017 | 24.7% |
| Decrefs | 397,946,163 | 27.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 70,861,237 |  |
| Method cache misses | 638,063 |  |
| Method cache collisions | 639,761 |  |
| Method cache dunder hits | 11,687,832 |  |
| Method cache dunder misses | 2,488 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 39,923 | 0 | 274,628,992 |
| 1 | 3,620 | 0 | 277,815,510 |
| 2 | 340 | 0 | 696,792,770 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 80 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 18,355,040 |  |
| Uops executed | 250,782,640 | 13 |
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
| <= 8 | 1,680,960 | 9.2% |
| <= 16 | 11,075,480 | 60.3% |
| <= 32 | 5,598,600 | 30.5% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 61,782,060 | 24.6% | 24.6% |
| LOAD_FAST | 28,796,160 | 11.5% | 36.1% |
| _POP_JUMP_IF_TRUE | 20,878,480 | 8.3% | 44.4% |
| _EXIT_TRACE | 18,355,040 | 7.3% | 51.8% |
| STORE_FAST | 16,674,080 | 6.6% | 58.4% |
| _ITER_CHECK_RANGE | 11,189,300 | 4.5% | 62.9% |
| _IS_ITER_EXHAUSTED_RANGE | 11,189,300 | 4.5% | 67.3% |
| _ITER_NEXT_RANGE | 10,628,060 | 4.2% | 71.6% |
| _LOAD_ATTR_INSTANCE_VALUE | 8,104,620 | 3.2% | 74.8% |
| _GUARD_TYPE_VERSION | 8,104,620 | 3.2% | 78.0% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 8,104,620 | 3.2% | 81.3% |
| LOAD_ATTR | 5,598,600 | 2.2% | 83.5% |
| _ITER_CHECK_TUPLE | 3,359,160 | 1.3% | 84.8% |
| _ITER_CHECK_LIST | 3,359,160 | 1.3% | 86.2% |
| _IS_ITER_EXHAUSTED_TUPLE | 3,359,160 | 1.3% | 87.5% |
| _IS_ITER_EXHAUSTED_LIST | 3,359,160 | 1.3% | 88.9% |
| LOAD_CONST | 3,075,160 | 1.2% | 90.1% |
| _POP_JUMP_IF_FALSE | 2,799,300 | 1.1% | 91.2% |
| _LOAD_GLOBAL_MODULE | 2,799,300 | 1.1% | 92.3% |
| _ITER_NEXT_TUPLE | 2,799,300 | 1.1% | 93.4% |
| _ITER_NEXT_LIST | 2,799,300 | 1.1% | 94.5% |
| _GUARD_GLOBALS_VERSION | 2,799,300 | 1.1% | 95.7% |
| TO_BOOL_BOOL | 2,799,300 | 1.1% | 96.8% |
| CONTAINS_OP | 2,799,300 | 1.1% | 97.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,799,300 | 1.1% | 99.0% |
| POP_TOP | 1,680,960 | 0.7% | 99.7% |
| BINARY_SUBSCR_LIST_INT | 275,860 | 0.1% | 99.8% |
| PUSH_NULL | 171,560 | 0.1% | 99.9% |
| COMPARE_OP_INT | 171,560 | 0.1% | 99.9% |
| CALL_BUILTIN_O | 171,560 | 0.1% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_METHOD_WITH_VALUES | 80 |


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
Stats gathered on: 2023-10-03
