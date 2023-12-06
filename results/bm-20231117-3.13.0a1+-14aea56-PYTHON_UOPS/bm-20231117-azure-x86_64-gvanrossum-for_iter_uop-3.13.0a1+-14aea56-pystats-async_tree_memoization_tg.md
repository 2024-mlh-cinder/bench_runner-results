
# Pystats results

- benchmark: async_tree_memoization_tg
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 462,012,798 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 129,913,029 | 5.8% | 26.5% |  |
| POP_JUMP_IF_FALSE | 125,146,819 | 5.6% | 32.1% |  |
| RESUME_CHECK | 118,662,530 | 5.3% | 37.4% | 0.0% |
| LOAD_FAST_LOAD_FAST | 103,453,090 | 4.6% | 42.1% |  |
| POP_TOP | 96,663,970 | 4.3% | 46.4% |  |
| LOAD_CONST | 92,940,910 | 4.2% | 50.6% |  |
| STORE_FAST | 83,705,550 | 3.8% | 54.3% |  |
| STORE_ATTR_SLOT | 75,466,690 | 3.4% | 57.7% | 6.2% |
| TO_BOOL_BOOL | 71,264,800 | 3.2% | 60.9% | 0.0% |
| RETURN_VALUE | 69,027,300 | 3.1% | 64.0% |  |
| RETURN_CONST | 57,476,040 | 2.6% | 66.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 55,612,090 | 2.5% | 69.1% |  |
| INTERPRETER_EXIT | 51,855,200 | 2.3% | 71.4% |  |
| LOAD_GLOBAL_MODULE | 50,365,619 | 2.3% | 73.6% |  |
| CALL_PY_EXACT_ARGS | 47,774,600 | 2.1% | 75.8% |  |
| LOAD_ATTR_SLOT | 44,009,700 | 2.0% | 77.8% | 1.6% |
| CALL | 40,701,250 | 1.8% | 79.6% |  |
| LOAD_ATTR | 38,094,210 | 1.7% | 81.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 35,839,300 | 1.6% | 82.9% | 0.0% |
| PUSH_NULL | 34,037,530 | 1.5% | 84.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 32,471,750 | 1.5% | 85.9% | 0.0% |
| POP_JUMP_IF_NOT_NONE | 30,605,070 | 1.4% | 87.2% |  |
| TO_BOOL_NONE | 26,498,020 | 1.2% | 88.4% | 0.0% |
| LOAD_ATTR_MODULE | 25,375,420 | 1.1% | 89.6% |  |
| COMPARE_OP_INT | 20,234,840 | 0.9% | 90.5% |  |
| CALL_BUILTIN_O | 16,124,630 | 0.7% | 91.2% |  |
| ENTER_EXECUTOR | 15,157,600 | 0.7% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 13,811,970 | 0.6% | 92.5% | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 11,946,640 | 0.5% | 93.0% |  |
| POP_JUMP_IF_NONE | 11,944,720 | 0.5% | 93.6% |  |
| TO_BOOL | 11,205,730 | 0.5% | 94.1% |  |
| CALL_FUNCTION_EX | 10,821,540 | 0.5% | 94.5% |  |
| POP_JUMP_IF_TRUE | 10,453,400 | 0.5% | 95.0% |  |
| RETURN_GENERATOR | 10,449,160 | 0.5% | 95.5% |  |
| SEND_GEN | 7,833,600 | 0.4% | 95.8% |  |
| BINARY_OP_ADD_INT | 7,464,980 | 0.3% | 96.2% |  |
| END_SEND | 7,088,980 | 0.3% | 96.5% |  |
| GET_AWAITABLE | 7,088,980 | 0.3% | 96.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,706,340 | 0.3% | 97.1% | 0.0% |
| CALL_KW | 5,597,900 | 0.3% | 97.4% |  |
| TO_BOOL_LIST | 5,229,570 | 0.2% | 97.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,493,320 | 0.2% | 97.8% | 16.9% |
| JUMP_FORWARD | 4,483,190 | 0.2% | 98.0% |  |
| BINARY_OP_SUBTRACT_INT | 4,479,260 | 0.2% | 98.2% |  |
| COMPARE_OP_FLOAT | 4,459,279 | 0.2% | 98.4% |  |
| CALL_ISINSTANCE | 4,459,220 | 0.2% | 98.6% |  |
| CALL_PY_WITH_DEFAULTS | 4,105,120 | 0.2% | 98.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,362,160 | 0.2% | 98.9% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 2,982,320 | 0.1% | 99.1% |  |
| YIELD_VALUE | 2,982,320 | 0.1% | 99.2% |  |
| SEND | 2,238,780 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 1,497,140 | 0.1% | 99.4% |  |
| NOP | 1,496,620 | 0.1% | 99.4% |  |
| CALL_BUILTIN_CLASS | 1,495,450 | 0.1% | 99.5% |  |
| BUILD_LIST | 1,495,260 | 0.1% | 99.6% |  |
| GET_ITER | 752,230 | 0.0% | 99.6% |  |
| IS_OP | 746,880 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 746,710 | 0.0% | 99.7% |  |
| LIST_EXTEND | 746,710 | 0.0% | 99.7% |  |
| EXIT_INIT_CHECK | 746,580 | 0.0% | 99.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 746,580 | 0.0% | 99.8% |  |
| BEFORE_ASYNC_WITH | 746,480 | 0.0% | 99.8% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 746,460 | 0.0% | 99.8% |  |
| LOAD_DEREF | 745,820 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 745,660 | 0.0% | 99.9% |  |
| LOAD_SUPER_ATTR_METHOD | 745,180 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_FLOAT | 374,090 | 0.0% | 99.9% |  |
| COMPARE_OP | 373,400 | 0.0% | 100.0% |  |
| BUILD_MAP | 372,700 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 372,520 | 0.0% | 100.0% |  |
| CALL_LEN | 5,430 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,660 | 0.0% | 100.0% |  |
| STORE_ATTR | 3,700 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 3,680 | 0.0% | 100.0% |  |
| COPY | 2,570 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 2,190 | 0.0% | 100.0% |  |
| RESUME | 2,040 | 0.0% | 100.0% | 1,517.2% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,010 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 1,840 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,720 | 0.0% | 100.0% |  |
| BINARY_OP | 1,149 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 640 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 580 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 460 | 0.0% | 100.0% |  |
| FOR_ITER | 440 | 0.0% | 100.0% |  |
| SWAP | 340 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 240 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 240 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 180 | 0.0% | 100.0% |  |
| POP_EXCEPT | 180 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| UNARY_INVERT | 160 | 0.0% | 100.0% |  |
| UNARY_NOT | 160 | 0.0% | 100.0% |  |
| CONTAINS_OP | 160 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 160 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 140 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 140 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 100 | 0.0% | 100.0% |  |
| IMPORT_NAME | 100 | 0.0% | 100.0% |  |
| DICT_MERGE | 80 | 0.0% | 100.0% |  |
| MAKE_CELL | 80 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 80 | 0.0% | 100.0% |  |
| RERAISE | 80 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 40 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 40 | 0.0% | 100.0% |  |
| IMPORT_FROM | 20 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 20 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 20 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 20 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 125,431,729 | 5.6% | 5.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 90,950,479 | 4.1% | 9.7% |
| RESUME_CHECK LOAD_FAST | 89,570,080 | 4.0% | 13.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 65,294,180 | 2.9% | 16.6% |
| STORE_FAST LOAD_FAST | 55,254,020 | 2.5% | 19.1% |
| CACHE RESUME_CHECK | 45,510,520 | 2.0% | 21.1% |
| POP_TOP LOAD_FAST | 44,415,440 | 2.0% | 23.1% |
| LOAD_FAST LOAD_ATTR_SLOT | 43,623,850 | 2.0% | 25.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 42,550,140 | 1.9% | 27.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 42,168,420 | 1.9% | 28.9% |
| LOAD_CONST LOAD_FAST | 41,797,650 | 1.9% | 30.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 40,682,800 | 1.8% | 32.6% |
| LOAD_FAST RETURN_VALUE | 37,891,370 | 1.7% | 34.3% |
| LOAD_FAST LOAD_ATTR | 36,209,960 | 1.6% | 35.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 35,457,000 | 1.6% | 37.5% |
| LOAD_FAST STORE_ATTR_SLOT | 33,209,450 | 1.5% | 39.0% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 32,471,730 | 1.5% | 40.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 31,359,110 | 1.4% | 41.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 31,348,030 | 1.4% | 43.2% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 31,347,180 | 1.4% | 44.6% |
| RETURN_CONST INTERPRETER_EXIT | 28,737,780 | 1.3% | 45.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 27,992,530 | 1.3% | 47.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 26,875,930 | 1.2% | 48.4% |
| RETURN_CONST POP_TOP | 26,872,660 | 1.2% | 49.6% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 26,498,000 | 1.2% | 50.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 25,374,300 | 1.1% | 51.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 24,256,000 | 1.1% | 53.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 23,886,310 | 1.1% | 54.1% |
| STORE_ATTR_SLOT LOAD_CONST | 21,642,900 | 1.0% | 55.1% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 21,270,100 | 1.0% | 56.0% |
| RETURN_VALUE INTERPRETER_EXIT | 20,505,680 | 0.9% | 56.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 20,234,840 | 0.9% | 57.8% |
| CALL STORE_FAST | 20,152,260 | 0.9% | 58.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 19,407,250 | 0.9% | 59.6% |
| RETURN_VALUE STORE_FAST | 19,035,270 | 0.9% | 60.5% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 16,419,540 | 0.7% | 61.2% |
| LOAD_FAST CALL_BUILTIN_O | 16,123,980 | 0.7% | 61.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 16,047,360 | 0.7% | 62.6% |
| CALL_BUILTIN_O STORE_FAST | 15,752,230 | 0.7% | 63.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 15,300,660 | 0.7% | 64.0% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 14,928,200 | 0.7% | 64.7% |
| POP_TOP ENTER_EXECUTOR | 14,927,200 | 0.7% | 65.4% |
| POP_TOP RETURN_CONST | 14,554,940 | 0.7% | 66.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 14,186,100 | 0.6% | 66.6% |
| LOAD_FAST LOAD_CONST | 14,184,170 | 0.6% | 67.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 13,809,140 | 0.6% | 67.9% |
| LOAD_CONST COMPARE_OP_INT | 11,946,030 | 0.5% | 68.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 11,945,020 | 0.5% | 69.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 11,943,920 | 0.5% | 69.5% |
| POP_JUMP_IF_FALSE LOAD_CONST | 11,573,640 | 0.5% | 70.0% |
| POP_TOP LOAD_CONST | 11,570,350 | 0.5% | 70.5% |
| LOAD_CONST STORE_FAST | 11,204,710 | 0.5% | 71.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 11,199,390 | 0.5% | 71.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 11,197,900 | 0.5% | 72.1% |
| STORE_ATTR_SLOT LOAD_FAST | 11,194,290 | 0.5% | 72.6% |
| STORE_ATTR_SLOT RETURN_CONST | 11,193,840 | 0.5% | 73.1% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 11,193,640 | 0.5% | 73.6% |
| RETURN_VALUE TO_BOOL_BOOL | 10,821,860 | 0.5% | 74.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,453,920 | 0.5% | 74.5% |
| STORE_FAST RETURN_CONST | 10,450,830 | 0.5% | 75.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 10,449,480 | 0.5% | 75.4% |
| LOAD_FAST_LOAD_FAST CALL | 10,449,200 | 0.5% | 75.9% |
| CALL_FUNCTION_EX POP_TOP | 10,449,160 | 0.5% | 76.4% |
| POP_TOP RESUME_CHECK | 10,449,000 | 0.5% | 76.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 10,076,960 | 0.5% | 77.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 10,076,700 | 0.5% | 77.8% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 10,076,500 | 0.5% | 78.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 10,076,460 | 0.5% | 78.7% |
| ENTER_EXECUTOR CALL_FUNCTION_EX | 10,074,590 | 0.5% | 79.1% |
| LOAD_ATTR LOAD_FAST | 9,331,320 | 0.4% | 79.5% |
| CALL RESUME_CHECK | 9,330,720 | 0.4% | 79.9% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 9,330,500 | 0.4% | 80.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 9,311,850 | 0.4% | 80.8% |
| LOAD_FAST PUSH_NULL | 9,033,820 | 0.4% | 81.2% |
| LOAD_ATTR CALL | 8,959,720 | 0.4% | 81.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 8,659,540 | 0.4% | 82.0% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 8,211,520 | 0.4% | 82.3% |
| PUSH_NULL LOAD_FAST | 7,912,200 | 0.4% | 82.7% |
| GET_AWAITABLE LOAD_CONST | 7,088,980 | 0.3% | 83.0% |
| TO_BOOL POP_JUMP_IF_FALSE | 6,719,520 | 0.3% | 83.3% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,718,880 | 0.3% | 83.6% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 6,718,340 | 0.3% | 83.9% |
| PUSH_NULL CALL | 6,345,470 | 0.3% | 84.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 5,972,050 | 0.3% | 84.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,970,560 | 0.3% | 84.7% |
| END_SEND POP_TOP | 5,970,200 | 0.3% | 85.0% |
| SEND_GEN POP_TOP | 5,970,060 | 0.3% | 85.3% |
| LOAD_CONST SEND_GEN | 5,969,960 | 0.3% | 85.5% |
| CALL POP_TOP | 5,598,480 | 0.3% | 85.8% |
| LOAD_CONST CALL_KW | 5,597,900 | 0.3% | 86.0% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 5,229,570 | 0.2% | 86.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 5,229,470 | 0.2% | 86.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 5,227,390 | 0.2% | 86.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 5,226,060 | 0.2% | 87.0% |
| LOAD_FAST CALL | 5,225,800 | 0.2% | 87.2% |
| LOAD_CONST LOAD_CONST | 5,225,620 | 0.2% | 87.4% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 5,225,580 | 0.2% | 87.7% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 4,851,540 | 0.2% | 87.9% |
| RETURN_VALUE END_SEND | 4,851,260 | 0.2% | 88.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 4,833,810 | 0.2% | 88.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 45,510,520 | 87.8% |
| POP_TOP | 4,478,960 | 8.6% |
| RETURN_GENERATOR | 1,492,960 | 2.9% |
| COPY_FREE_VARS | 372,420 | 0.7% |
| RESUME | 340 | 0.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 746,460 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 746,480 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 40 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 66.7% |
| LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 40 | 33.3% |
| PUSH_EXC_INFO | 20 | 16.7% |
| LOAD_ATTR | 20 | 16.7% |
| STORE_FAST | 20 | 16.7% |
| BINARY_SUBSCR_DICT | 20 | 16.7% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160 | 88.9% |
| LOAD_GLOBAL | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 180 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,851,260 | 68.4% |
| RETURN_CONST | 1,118,940 | 15.8% |
| SEND | 1,118,780 | 15.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,970,200 | 84.2% |
| STORE_FAST | 746,480 | 10.5% |
| LOAD_FAST | 372,300 | 5.3% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 746,580 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 746,580 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 748,330 | 99.5% |
| LOAD_FAST | 3,680 | 0.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 160 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 748,270 | 99.5% |
| FOR_ITER_LIST | 3,620 | 0.5% |
| FOR_ITER | 320 | 0.0% |
| FOR_ITER_TUPLE | 20 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 28,737,780 | 55.4% |
| RETURN_VALUE | 20,505,680 | 39.5% |
| RETURN_GENERATOR | 1,492,960 | 2.9% |
| YIELD_VALUE | 1,118,780 | 2.2% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 240 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 746,460 | 49.9% |
| RESUME_CHECK | 375,030 | 25.1% |
| STORE_FAST | 374,290 | 25.0% |
| POP_TOP | 400 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,496,060 | 100.0% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 100 | 55.6% |
| COPY | 80 | 44.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 100 | 55.6% |
| RERAISE | 80 | 44.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 32,471,730 | 33.6% |
| RETURN_CONST | 26,872,660 | 27.8% |
| CALL_FUNCTION_EX | 10,449,160 | 10.8% |
| END_SEND | 5,970,200 | 6.2% |
| SEND_GEN | 5,970,060 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,415,440 | 45.9% |
| ENTER_EXECUTOR | 14,927,200 | 15.4% |
| RETURN_CONST | 14,554,940 | 15.1% |
| LOAD_CONST | 11,570,350 | 12.0% |
| RESUME_CHECK | 10,449,000 | 10.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 80 | 44.4% |
| BINARY_SUBSCR_DICT | 80 | 44.4% |
| BINARY_SUBSCR | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160 | 88.9% |
| LOAD_GLOBAL | 20 | 11.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 24,256,000 | 71.3% |
| LOAD_FAST | 9,033,820 | 26.5% |
| LOAD_ATTR | 747,630 | 2.2% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,928,200 | 43.9% |
| LOAD_FAST | 7,912,200 | 23.2% |
| CALL | 6,345,470 | 18.6% |
| LOAD_CONST | 3,732,720 | 11.0% |
| CALL_ALLOC_AND_ENTER_INIT | 746,480 | 2.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,851,540 | 46.4% |
| ENTER_EXECUTOR | 3,732,120 | 35.7% |
| CACHE | 1,492,960 | 14.3% |
| CALL_PY_WITH_DEFAULTS | 372,280 | 3.6% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,478,920 | 42.9% |
| GET_AWAITABLE | 4,477,240 | 42.8% |
| INTERPRETER_EXIT | 1,492,960 | 14.3% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,891,370 | 54.9% |
| LOAD_ATTR_INSTANCE_VALUE | 16,419,540 | 23.8% |
| COMPARE_OP_FLOAT | 4,458,700 | 6.5% |
| RETURN_VALUE | 3,732,960 | 5.4% |
| BINARY_OP_ADD_INT | 3,732,460 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 20,505,680 | 29.7% |
| STORE_FAST | 19,035,270 | 27.6% |
| TO_BOOL_BOOL | 10,821,860 | 15.7% |
| END_SEND | 4,851,260 | 7.0% |
| POP_TOP | 4,479,120 | 6.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 40.0% |
| STORE_SUBSCR_DICT | 40 | 40.0% |
| LOAD_CONST | 20 | 20.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 11,199,390 | 99.9% |
| TO_BOOL | 3,800 | 0.0% |
| LOAD_ATTR | 760 | 0.0% |
| RETURN_VALUE | 480 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,719,520 | 60.0% |
| POP_JUMP_IF_TRUE | 4,480,970 | 40.0% |
| TO_BOOL | 3,800 | 0.0% |
| TO_BOOL_BOOL | 980 | 0.0% |
| TO_BOOL_INT | 160 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 80 | 50.0% |
| LOAD_ATTR_MODULE | 60 | 37.5% |
| LOAD_ATTR | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 160 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 37.5% |
| TO_BOOL_INT | 60 | 37.5% |
| TO_BOOL | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229 | 19.9% |
| LOAD_GLOBAL_MODULE | 180 | 15.7% |
| UNARY_INVERT | 160 | 13.9% |
| BINARY_OP | 160 | 13.9% |
| LOAD_CONST | 160 | 13.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 220 | 19.1% |
| BINARY_OP | 160 | 13.9% |
| COPY | 160 | 13.9% |
| LOAD_GLOBAL_MODULE | 109 | 9.5% |
| UNARY_INVERT | 80 | 7.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 746,680 | 49.9% |
| LOAD_ATTR_SLOT | 374,390 | 25.0% |
| LOAD_FAST | 372,300 | 24.9% |
| STORE_FAST | 1,830 | 0.1% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,493,430 | 99.9% |
| STORE_FAST | 1,830 | 0.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 372,300 | 99.9% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 0.0% |
| POP_TOP | 80 | 0.0% |
| BUILD_TUPLE | 80 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 372,300 | 99.9% |
| LOAD_FAST | 400 | 0.1% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 37.5% |
| CALL | 80 | 12.5% |
| LOAD_CONST | 80 | 12.5% |
| LOAD_FAST_LOAD_FAST | 80 | 12.5% |
| LOAD_GLOBAL_MODULE | 80 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 37.5% |
| CALL | 160 | 25.0% |
| RETURN_VALUE | 80 | 12.5% |
| BUILD_MAP | 80 | 12.5% |
| CALL_ISINSTANCE | 40 | 6.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,449,200 | 25.7% |
| LOAD_ATTR | 8,959,720 | 22.0% |
| PUSH_NULL | 6,345,470 | 15.6% |
| LOAD_FAST | 5,225,800 | 12.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,479,120 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,152,260 | 49.5% |
| RESUME_CHECK | 9,330,720 | 22.9% |
| POP_TOP | 5,598,480 | 13.8% |
| CALL_METHOD_DESCRIPTOR_O | 4,479,120 | 11.0% |
| LOAD_FAST | 747,140 | 1.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 10,074,590 | 93.1% |
| CALL_INTRINSIC_1 | 374,410 | 3.5% |
| BUILD_MAP | 372,300 | 3.4% |
| DICT_MERGE | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,449,160 | 96.6% |
| STORE_FAST | 372,300 | 3.4% |
| COPY_FREE_VARS | 80 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 746,710 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 374,410 | 50.1% |
| LOAD_CONST | 372,300 | 49.9% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,597,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,478,960 | 80.0% |
| RETURN_VALUE | 1,118,780 | 20.0% |
| POP_TOP | 80 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| RESUME | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 372,600 | 99.8% |
| COMPARE_OP | 320 | 0.1% |
| CALL_BUILTIN_CLASS | 140 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 372,760 | 99.8% |
| COMPARE_OP | 320 | 0.1% |
| COMPARE_OP_INT | 220 | 0.1% |
| COMPARE_OP_FLOAT | 60 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 60 | 37.5% |
| LOAD_GLOBAL_MODULE | 60 | 37.5% |
| LOAD_ATTR | 20 | 12.5% |
| LOAD_GLOBAL | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 160 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,810 | 70.4% |
| BINARY_OP | 160 | 6.2% |
| LOAD_FAST | 160 | 6.2% |
| CALL_BUILTIN_FAST | 140 | 5.4% |
| UNARY_NOT | 80 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,870 | 72.8% |
| TO_BOOL | 240 | 9.3% |
| TO_BOOL_BOOL | 200 | 7.8% |
| POP_EXCEPT | 80 | 3.1% |
| LOAD_ATTR | 80 | 3.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 372,920 | 50.0% |
| CACHE | 372,420 | 49.9% |
| CALL | 180 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 745,260 | 99.9% |
| RESUME | 240 | 0.0% |
| RETURN_GENERATOR | 80 | 0.0% |
| MAKE_CELL | 80 | 0.0% |


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
| POP_TOP | 14,927,200 | 98.5% |
| POP_JUMP_IF_FALSE | 230,300 | 1.5% |
| JUMP_BACKWARD | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 10,074,590 | 66.5% |
| RETURN_GENERATOR | 3,732,120 | 24.6% |
| FOR_ITER_RANGE | 748,230 | 4.9% |
| LOAD_ATTR_SLOT | 372,300 | 2.5% |
| RETURN_VALUE | 178,640 | 1.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 320 | 72.7% |
| FOR_ITER | 80 | 18.2% |
| JUMP_BACKWARD | 40 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 27.3% |
| LOAD_FAST | 100 | 22.7% |
| FOR_ITER | 80 | 18.2% |
| FOR_ITER_LIST | 60 | 13.6% |
| STORE_FAST | 40 | 9.1% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 4,477,240 | 63.2% |
| BEFORE_ASYNC_WITH | 746,480 | 10.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 746,460 | 10.5% |
| LOAD_ATTR_INSTANCE_VALUE | 746,460 | 10.5% |
| LOAD_FAST | 372,300 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,088,980 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 80.0% |
| IMPORT_FROM | 20 | 20.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 746,460 | 99.9% |
| LOAD_CONST | 400 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 746,480 | 99.9% |
| RETURN_VALUE | 400 | 0.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,040 | 60.5% |
| POP_TOP | 680 | 39.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 980 | 57.0% |
| FOR_ITER_RANGE | 600 | 34.9% |
| ENTER_EXECUTOR | 100 | 5.8% |
| FOR_ITER | 40 | 2.3% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,982,160 | 100.0% |
| RESUME | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 1,863,500 | 62.5% |
| SEND | 1,118,820 | 37.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,482,940 | 100.0% |
| POP_JUMP_IF_FALSE | 150 | 0.0% |
| POP_TOP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,481,190 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 1,860 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_FAST_CHECK | 20 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 374,390 | 50.1% |
| LOAD_FAST | 372,300 | 49.9% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 746,710 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,209,960 | 95.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,493,560 | 3.9% |
| LOAD_ATTR_SLOT | 374,510 | 1.0% |
| LOAD_ATTR | 13,320 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,076,500 | 26.5% |
| LOAD_FAST | 9,331,320 | 24.5% |
| CALL | 8,959,720 | 23.5% |
| TO_BOOL_NONE | 4,478,920 | 11.8% |
| STORE_FAST | 3,732,640 | 9.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 21,642,900 | 23.3% |
| LOAD_FAST | 14,184,170 | 15.3% |
| POP_JUMP_IF_FALSE | 11,573,640 | 12.5% |
| POP_TOP | 11,570,350 | 12.4% |
| LOAD_FAST_LOAD_FAST | 8,211,520 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,797,650 | 45.0% |
| COMPARE_OP_INT | 11,946,030 | 12.9% |
| STORE_FAST | 11,204,710 | 12.1% |
| SEND_GEN | 5,969,960 | 6.4% |
| CALL_KW | 5,597,900 | 6.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 745,180 | 99.9% |
| LOAD_GLOBAL | 240 | 0.0% |
| STORE_FAST | 160 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 745,420 | 99.9% |
| LOAD_CONST | 160 | 0.0% |
| PUSH_NULL | 80 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 80 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 90,950,479 | 19.7% |
| RESUME_CHECK | 89,570,080 | 19.4% |
| STORE_FAST | 55,254,020 | 12.0% |
| POP_TOP | 44,415,440 | 9.6% |
| LOAD_CONST | 41,797,650 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 125,431,729 | 27.1% |
| LOAD_ATTR_SLOT | 43,623,850 | 9.4% |
| RETURN_VALUE | 37,891,370 | 8.2% |
| LOAD_ATTR | 36,209,960 | 7.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 35,457,000 | 7.7% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 31,347,180 | 30.3% |
| LOAD_FAST_LOAD_FAST | 15,300,660 | 14.8% |
| PUSH_NULL | 14,928,200 | 14.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,809,140 | 13.3% |
| POP_JUMP_IF_NOT_NONE | 10,076,700 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 42,168,420 | 40.8% |
| LOAD_FAST_LOAD_FAST | 15,300,660 | 14.8% |
| LOAD_FAST | 10,449,480 | 10.1% |
| CALL | 10,449,200 | 10.1% |
| LOAD_CONST | 8,211,520 | 7.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME | 600 | 12.9% |
| RESUME_CHECK | 580 | 12.4% |
| LOAD_FAST | 540 | 11.6% |
| POP_TOP | 500 | 10.7% |
| POP_JUMP_IF_FALSE | 460 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,600 | 34.3% |
| LOAD_ATTR | 980 | 21.0% |
| LOAD_GLOBAL_BUILTIN | 660 | 14.2% |
| LOAD_FAST | 400 | 8.6% |
| CALL | 300 | 6.4% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 220 | 47.8% |
| CALL | 140 | 30.4% |
| LOAD_FAST | 60 | 13.0% |
| LOAD_FAST_LOAD_FAST | 40 | 8.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 65,294,180 | 52.2% |
| TO_BOOL_NONE | 26,498,000 | 21.2% |
| COMPARE_OP_INT | 20,234,840 | 16.2% |
| TO_BOOL | 6,719,520 | 5.4% |
| TO_BOOL_LIST | 5,229,570 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 90,950,479 | 72.7% |
| RETURN_CONST | 16,047,360 | 12.8% |
| LOAD_CONST | 11,573,640 | 9.2% |
| LOAD_FAST_LOAD_FAST | 4,104,880 | 3.3% |
| LOAD_GLOBAL_MODULE | 2,236,110 | 1.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,718,880 | 56.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,225,580 | 43.7% |
| CALL | 160 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,943,920 | 100.0% |
| RETURN_CONST | 480 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,886,310 | 78.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,718,340 | 22.0% |
| LOAD_GLOBAL_MODULE | 220 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,076,700 | 32.9% |
| LOAD_GLOBAL_MODULE | 9,330,500 | 30.5% |
| LOAD_FAST | 5,972,050 | 19.5% |
| RETURN_CONST | 4,478,880 | 14.6% |
| LOAD_CONST | 746,500 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,970,560 | 57.1% |
| TO_BOOL | 4,480,970 | 42.9% |
| TO_BOOL_INT | 1,870 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,076,960 | 96.4% |
| LOAD_CONST | 374,210 | 3.6% |
| STORE_FAST | 1,830 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| POP_TOP | 80 | 0.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 80 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,047,360 | 27.9% |
| POP_TOP | 14,554,940 | 25.3% |
| STORE_ATTR_SLOT | 11,193,840 | 19.5% |
| STORE_FAST | 10,450,830 | 18.2% |
| POP_JUMP_IF_NOT_NONE | 4,478,880 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 28,737,780 | 50.0% |
| POP_TOP | 26,872,660 | 46.8% |
| END_SEND | 1,118,940 | 1.9% |
| EXIT_INIT_CHECK | 746,580 | 1.3% |
| TO_BOOL | 40 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,119,020 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,118,820 | 50.0% |
| SEND | 940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 1,118,780 | 50.0% |
| YIELD_VALUE | 1,118,780 | 50.0% |
| SEND | 940 | 0.0% |
| POP_TOP | 140 | 0.0% |
| SEND_GEN | 140 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,860 | 77.3% |
| LOAD_FAST_LOAD_FAST | 340 | 9.2% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 7.6% |
| STORE_ATTR | 100 | 2.7% |
| SWAP | 80 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,280 | 34.6% |
| LOAD_FAST | 620 | 16.8% |
| LOAD_CONST | 520 | 14.1% |
| RETURN_CONST | 520 | 14.1% |
| STORE_ATTR_SLOT | 340 | 9.2% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 20,152,260 | 24.1% |
| RETURN_VALUE | 19,035,270 | 22.7% |
| CALL_BUILTIN_O | 15,752,230 | 18.8% |
| LOAD_CONST | 11,204,710 | 13.4% |
| CALL_KW | 4,478,960 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,254,020 | 66.0% |
| RETURN_CONST | 10,450,830 | 12.5% |
| LOAD_FAST_LOAD_FAST | 8,659,540 | 10.3% |
| JUMP_FORWARD | 4,482,940 | 5.4% |
| LOAD_GLOBAL_MODULE | 3,732,640 | 4.5% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 75.0% |
| UNPACK_SEQUENCE | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 50.0% |
| LOAD_GLOBAL | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 80 | 23.5% |
| LOAD_FAST | 80 | 23.5% |
| BINARY_OP_ADD_INT | 60 | 17.6% |
| BINARY_OP_SUBTRACT_INT | 60 | 17.6% |
| BINARY_OP | 40 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 100 | 29.4% |
| STORE_ATTR | 80 | 23.5% |
| STORE_FAST | 80 | 23.5% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 23.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 33.3% |
| CALL | 40 | 33.3% |
| STORE_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 50.0% |
| STORE_FAST_STORE_FAST | 40 | 33.3% |
| LOAD_FAST | 20 | 16.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 1,863,540 | 62.5% |
| SEND | 1,118,780 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 1,863,540 | 62.5% |
| INTERPRETER_EXIT | 1,118,780 | 37.5% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,160 | 56.9% |
| CACHE | 340 | 16.7% |
| COPY_FREE_VARS | 240 | 11.8% |
| POP_TOP | 160 | 7.8% |
| SEND_GEN | 100 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 47.1% |
| LOAD_GLOBAL | 600 | 29.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 160 | 7.8% |
| LOAD_CONST | 140 | 6.9% |
| NOP | 100 | 4.9% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 372,260 | 99.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,790 | 0.5% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 372,280 | 99.5% |
| STORE_FAST | 1,810 | 0.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,732,480 | 50.0% |
| RETURN_VALUE | 3,732,440 | 50.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,732,460 | 50.0% |
| CALL_PY_WITH_DEFAULTS | 3,732,440 | 50.0% |
| SWAP | 60 | 0.0% |
| CALL | 20 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 3,732,440 | 83.3% |
| LOAD_CONST | 746,760 | 16.7% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,732,460 | 83.3% |
| CALL_PY_EXACT_ARGS | 746,720 | 16.7% |
| SWAP | 60 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 57.1% |
| LOAD_FAST | 40 | 28.6% |
| BINARY_SUBSCR | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 80 | 57.1% |
| RETURN_VALUE | 60 | 42.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540 | 93.1% |
| BINARY_SUBSCR | 40 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 450 | 77.6% |
| LOAD_ATTR_SLOT | 110 | 19.0% |
| LOAD_ATTR | 20 | 3.4% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 746,480 | 100.0% |
| CALL | 60 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 746,520 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,478,880 | 99.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,340 | 0.3% |
| CALL | 60 | 0.0% |
| PUSH_NULL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,732,460 | 83.1% |
| GET_AWAITABLE | 746,460 | 16.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,340 | 0.3% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 746,660 | 49.9% |
| LOAD_GLOBAL_MODULE | 746,440 | 49.9% |
| LOAD_FAST | 1,970 | 0.1% |
| CALL | 180 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 748,330 | 50.0% |
| LOAD_FAST | 746,700 | 49.9% |
| COMPARE_OP | 140 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 372,260 | 99.9% |
| LOAD_CONST | 180 | 0.0% |
| CALL | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 372,280 | 99.9% |
| COPY | 140 | 0.0% |
| TO_BOOL_BOOL | 80 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 746,440 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 746,460 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,123,980 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 430 | 0.0% |
| CALL | 180 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,752,230 | 97.7% |
| TO_BOOL_BOOL | 372,260 | 2.3% |
| POP_TOP | 120 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,458,720 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 380 | 0.0% |
| CALL | 80 | 0.0% |
| BUILD_TUPLE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,459,140 | 100.0% |
| TO_BOOL | 80 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,370 | 98.9% |
| CALL | 60 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,620 | 66.7% |
| COPY | 1,810 | 33.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,361,940 | 100.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| CALL | 60 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,359,540 | 99.9% |
| TO_BOOL_NONE | 2,400 | 0.1% |
| RETURN_VALUE | 140 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,790 | 89.1% |
| LOAD_CONST | 80 | 4.0% |
| CALL | 60 | 3.0% |
| LOAD_ATTR | 40 | 2.0% |
| LOAD_FAST | 40 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,810 | 90.0% |
| POP_TOP | 120 | 6.0% |
| RETURN_VALUE | 80 | 4.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 10,076,500 | 73.0% |
| LOAD_ATTR_METHOD_NO_DICT | 3,734,950 | 27.0% |
| CALL | 400 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,076,460 | 73.0% |
| STORE_FAST | 3,734,550 | 27.0% |
| POP_TOP | 380 | 0.0% |
| GET_ITER | 160 | 0.0% |
| CALL | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,992,530 | 86.2% |
| CALL | 4,479,120 | 13.8% |
| LOAD_CONST | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 32,471,730 | 100.0% |
| LOAD_CONST | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 31,348,030 | 65.6% |
| LOAD_FAST | 14,186,100 | 29.7% |
| LOAD_ATTR_METHOD_NO_DICT | 746,750 | 1.6% |
| BINARY_OP_SUBTRACT_INT | 746,720 | 1.6% |
| LOAD_SUPER_ATTR_METHOD | 372,460 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 42,550,140 | 89.1% |
| RETURN_GENERATOR | 4,851,540 | 10.2% |
| COPY_FREE_VARS | 372,920 | 0.8% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 3,732,440 | 90.9% |
| LOAD_GLOBAL_MODULE | 372,260 | 9.1% |
| CALL | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,732,840 | 90.9% |
| RETURN_GENERATOR | 372,280 | 9.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 4,458,680 | 100.0% |
| LOAD_FAST | 430 | 0.0% |
| LOAD_GLOBAL_MODULE | 109 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,458,700 | 100.0% |
| POP_JUMP_IF_FALSE | 579 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,946,030 | 59.0% |
| LOAD_FAST_LOAD_FAST | 4,554,360 | 22.5% |
| LOAD_GLOBAL_MODULE | 3,734,230 | 18.5% |
| COMPARE_OP | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20,234,840 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,620 | 98.4% |
| FOR_ITER | 60 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,870 | 50.8% |
| LOAD_FAST | 1,810 | 49.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 748,270 | 50.0% |
| ENTER_EXECUTOR | 748,230 | 50.0% |
| JUMP_BACKWARD | 600 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 748,830 | 50.0% |
| LOAD_CONST | 748,310 | 50.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 20 | 50.0% |
| ENTER_EXECUTOR | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 50.0% |
| STORE_FAST | 20 | 50.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 85.7% |
| LOAD_ATTR | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,431,729 | 96.6% |
| LOAD_FAST_LOAD_FAST | 4,479,120 | 3.4% |
| LOAD_ATTR | 1,980 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 40,682,800 | 31.3% |
| LOAD_ATTR_METHOD_NO_DICT | 31,359,110 | 24.1% |
| RETURN_VALUE | 16,419,540 | 12.6% |
| TO_BOOL | 11,199,390 | 8.6% |
| POP_JUMP_IF_NOT_NONE | 6,718,340 | 5.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 31,359,110 | 87.5% |
| LOAD_FAST | 4,479,430 | 12.5% |
| LOAD_ATTR | 620 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,875,930 | 75.0% |
| LOAD_GLOBAL_MODULE | 4,478,960 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,734,950 | 10.4% |
| CALL_PY_EXACT_ARGS | 746,750 | 2.1% |
| LOAD_FAST_LOAD_FAST | 1,950 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,457,000 | 63.8% |
| LOAD_ATTR_SLOT | 11,193,640 | 20.1% |
| LOAD_ATTR_INSTANCE_VALUE | 5,227,390 | 9.4% |
| LOAD_FAST_LOAD_FAST | 3,732,480 | 6.7% |
| LOAD_ATTR | 1,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 31,348,030 | 56.4% |
| LOAD_FAST_LOAD_FAST | 13,809,140 | 24.8% |
| LOAD_FAST | 10,453,920 | 18.8% |
| CALL | 700 | 0.0% |
| LOAD_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 25,374,300 | 100.0% |
| LOAD_ATTR | 1,000 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 24,256,000 | 95.6% |
| IS_OP | 746,460 | 2.9% |
| LOAD_FAST_LOAD_FAST | 372,280 | 1.5% |
| LOAD_ATTR | 200 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


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
| LOAD_FAST | 43,623,850 | 99.1% |
| ENTER_EXECUTOR | 372,300 | 0.8% |
| LOAD_ATTR_SLOT | 12,880 | 0.0% |
| LOAD_ATTR | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 110 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 21,270,100 | 48.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,193,640 | 25.4% |
| LOAD_FAST | 4,459,150 | 10.1% |
| COMPARE_OP_FLOAT | 4,458,680 | 10.1% |
| TO_BOOL_BOOL | 1,491,340 | 3.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,833,810 | 72.1% |
| STORE_FAST | 748,290 | 11.2% |
| STORE_ATTR_INSTANCE_VALUE | 746,580 | 11.1% |
| POP_TOP | 372,460 | 5.6% |
| JUMP_FORWARD | 1,860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,467,240 | 66.6% |
| CALL_BUILTIN_CLASS | 746,660 | 11.1% |
| LOAD_GLOBAL_MODULE | 746,480 | 11.1% |
| LOAD_DEREF | 745,180 | 11.1% |
| CALL_ISINSTANCE | 380 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,407,250 | 38.5% |
| POP_JUMP_IF_NOT_NONE | 9,330,500 | 18.5% |
| LOAD_FAST | 9,311,850 | 18.5% |
| LOAD_ATTR_METHOD_NO_DICT | 4,478,960 | 8.9% |
| STORE_FAST | 3,732,640 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 25,374,300 | 50.4% |
| LOAD_FAST | 11,197,900 | 22.2% |
| LOAD_FAST_LOAD_FAST | 4,479,200 | 8.9% |
| CALL_ISINSTANCE | 4,458,720 | 8.9% |
| COMPARE_OP_INT | 3,734,230 | 7.4% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 744,960 | 100.0% |
| LOAD_SUPER_ATTR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 372,460 | 50.0% |
| LOAD_FAST_LOAD_FAST | 372,340 | 50.0% |
| LOAD_FAST | 260 | 0.0% |
| CALL | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 45,510,520 | 38.4% |
| CALL_PY_EXACT_ARGS | 42,550,140 | 35.9% |
| POP_TOP | 10,449,000 | 8.8% |
| CALL | 9,330,720 | 7.9% |
| CALL_PY_WITH_DEFAULTS | 3,732,840 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,570,080 | 75.5% |
| LOAD_GLOBAL_MODULE | 19,407,250 | 16.4% |
| LOAD_GLOBAL_BUILTIN | 4,833,810 | 4.1% |
| JUMP_BACKWARD_NO_INTERRUPT | 2,982,160 | 2.5% |
| LOAD_CONST | 1,493,380 | 1.3% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,969,960 | 76.2% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,863,500 | 23.8% |
| SEND | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,970,060 | 76.2% |
| RESUME_CHECK | 1,863,440 | 23.8% |
| RESUME | 100 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,945,020 | 100.0% |
| STORE_ATTR | 1,280 | 0.0% |
| LOAD_FAST_LOAD_FAST | 260 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,226,060 | 43.7% |
| LOAD_FAST | 2,986,600 | 25.0% |
| RETURN_CONST | 747,120 | 6.3% |
| LOAD_GLOBAL_MODULE | 746,800 | 6.3% |
| BUILD_LIST | 746,680 | 6.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 42,168,420 | 55.9% |
| LOAD_FAST | 33,209,450 | 44.0% |
| STORE_ATTR_SLOT | 88,480 | 0.1% |
| STORE_ATTR | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 31,347,180 | 41.5% |
| LOAD_CONST | 21,642,900 | 28.7% |
| LOAD_FAST | 11,194,290 | 14.8% |
| RETURN_CONST | 11,193,840 | 14.8% |
| STORE_ATTR_SLOT | 88,480 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,760 | 95.7% |
| STORE_SUBSCR | 40 | 2.2% |
| LOAD_ATTR | 40 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,840 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,682,800 | 57.1% |
| RETURN_VALUE | 10,821,860 | 15.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,076,460 | 14.1% |
| CALL_ISINSTANCE | 4,459,140 | 6.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,359,540 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 65,294,180 | 91.6% |
| POP_JUMP_IF_TRUE | 5,970,560 | 8.4% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,870 | 85.4% |
| TO_BOOL | 160 | 7.3% |
| LOAD_FAST | 80 | 3.7% |
| BINARY_OP | 40 | 1.8% |
| LOAD_ATTR_SLOT | 40 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,870 | 85.4% |
| POP_JUMP_IF_FALSE | 260 | 11.9% |
| UNARY_NOT | 60 | 2.7% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,229,470 | 100.0% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,229,570 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,270,100 | 80.3% |
| LOAD_ATTR | 4,478,920 | 16.9% |
| LOAD_FAST | 746,440 | 2.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,400 | 0.0% |
| TO_BOOL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 26,498,000 | 100.0% |
| TO_BOOL_BOOL | 20 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE | 60 | 33.3% |
| RETURN_VALUE | 40 | 22.2% |
| CALL | 40 | 22.2% |
| STORE_FAST | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |


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
|     deferred | 809 | 0.0% |
|          hit | 12,318,390 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 52.9% |
| Failure | 160 | 47.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 80 | 50.0% |
| or | 40 | 25.0% |
| true divide other | 40 | 25.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 6.4% |
|          hit | 820 | 87.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40,670,330 | 23.3% |
|          hit | 132,942,620 | 76.2% |
|         miss | 761,180 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 17,520 | 56.7% |
| Failure | 13,400 | 43.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 3,280 | 24.5% |
| no dict | 2,960 | 22.1% |
| code complex parameters | 2,900 | 21.6% |
| cfunc noargs | 1,380 | 10.3% |
| class no vectorcall | 1,340 | 10.0% |
| other | 1,280 | 9.6% |
| class mutable | 80 | 0.6% |
| wrong number arguments | 40 | 0.3% |
| cfunc varargs | 40 | 0.3% |
| operator wrapper | 40 | 0.3% |
| cmethod | 20 | 0.1% |
| cfunc varargs keywords | 20 | 0.1% |
| init not simple | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 372,800 | 1.5% |
|          hit | 24,694,139 | 98.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 46.7% |
| Failure | 320 | 53.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 280 | 87.5% |
| bool | 40 | 12.5% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 260 | 0.0% |
|          hit | 1,500,860 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 55.6% |
| Failure | 80 | 44.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 38,063,450 | 11.6% |
|          hit | 290,061,709 | 88.2% |
|         miss | 688,030 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,320 | 59.6% |
| Failure | 12,440 | 40.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 7,840 | 63.0% |
| method | 3,080 | 24.8% |
| class attr descriptor | 1,280 | 10.3% |
| not managed dict | 140 | 1.1% |
| metaclass attribute | 60 | 0.5% |
| class attr simple | 40 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,480 | 0.0% |
|        deopt | 80 | 0.0% |
|          hit | 57,071,879 | 100.0% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,260 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 745,180 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 100.0% |
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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,237,700 | 22.2% |
|          hit | 7,833,600 | 77.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 13.0% |
| Failure | 940 | 87.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 940 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 368,934,881,474,190,945,820 | 422,040,054,980,352.1% |
|          hit | 82,719,450 | 94.6% |
|         miss | 4,693,880 | 5.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 90,100 | 99.9% |
| Failure | 100 | 0.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 80 | 80.0% |
| overriding descriptor | 20 | 20.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 3.1% |
|          hit | 1,840 | 94.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 11,200,510 | 9.8% |
|          hit | 102,993,100 | 90.2% |
|         miss | 1,480 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,420 | 27.2% |
| Failure | 3,800 | 72.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 3,700 | 97.4% |
| sequence | 100 | 2.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 20.0% |
|          hit | 180 | 60.0% |

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
| Basic | 1,127,175,538 | 50.5% |
| Not specialized | 270,774,128 | 12.1% |
| Specialized hits | 827,782,827 | 37.1% |
| Specialized misses | 6,175,600 | 0.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 368,934,881,474,190,945,820 | 100.0% |
| CALL | 40,670,330 | 0.0% |
| LOAD_ATTR | 38,063,450 | 0.0% |
| TO_BOOL | 11,200,510 | 0.0% |
| SEND | 2,237,700 | 0.0% |
| COMPARE_OP | 372,800 | 0.0% |
| LOAD_GLOBAL | 2,480 | 0.0% |
| BINARY_OP | 809 | 0.0% |
| FOR_ITER | 260 | 0.0% |
| LOAD_SUPER_ATTR | 240 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 4,693,880 | 75.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 760,800 | 12.3% |
| LOAD_ATTR_SLOT | 684,560 | 11.0% |
| RESUME | 30,950 | 0.5% |
| RESUME_CHECK | 30,950 | 0.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,470 | 0.1% |
| TO_BOOL_NONE | 1,060 | 0.0% |
| TO_BOOL_BOOL | 420 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 260 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 51,855,200 | 41.4% |
| Calls to Python functions inlined | 73,524,980 | 58.6% |
| Calls via PyEval_EvalFrame (total) | 51,855,200 | 41.4% |
| Calls via PyEval_EvalFrame (vector) | 46,257,460 | 36.9% |
| Calls via PyEval_EvalFrame (generator) | 5,597,740 | 4.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 46,257,460 | 36.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 4,458,720 | 3.6% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 4,479,100 | 3.6% |
| Calls via PyEval_EvalFrame (method) | 20,153,400 | 16.1% |
| Frame objects created | 180 | 0.0% |
| Frames pushed | 70,913,620 | 56.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 56,534,665 | 33.9% |
| Frees to freelist | 56,875,169 |  |
| Allocations | 110,187,542 | 66.1% |
| Allocations to 512 bytes | 109,378,821 | 65.6% |
| Allocations to 4 kbytes | 808,583 | 0.5% |
| Allocations over 4 kbytes | 138 | 0.0% |
| Frees | 110,102,458 |  |
| New values | 320 |  |
| Interpreter increfs | 1,291,732,035 | 79.2% |
| Interpreter decrefs | 1,366,807,600 | 76.9% |
| Increfs | 338,620,765 | 20.8% |
| Decrefs | 410,070,144 | 23.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 73,635,568 |  |
| Method cache misses | 71,482 |  |
| Method cache collisions | 71,167 |  |
| Method cache dunder hits | 16,402,083 |  |
| Method cache dunder misses | 437 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 55,349 | 2,040 | 378,646,312 |
| 1 | 5,021 | 0 | 392,390,974 |
| 2 | 451 | 0 | 1,015,050,898 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 100 |  |
| Traces created | 100 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 20.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 20 | 20.0% |
| Traces executed | 15,157,600 |  |
| Uops executed | 821,206,030 | 54.18 |

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
| <= 32 | 40 | 40.0% |
| <= 64 | 20 | 20.0% |
| <= 128 | 40 | 40.0% |


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
| <= 16 | 40 | 40.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 40 | 40.0% |
| <= 128 | 20 | 20.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 20 | 0.0% |
| <= 4 | 748,230 | 4.9% |
| <= 8 | 0 | 0.0% |
| <= 16 | 230,190 | 1.5% |
| <= 32 | 372,300 | 2.5% |
| <= 64 | 3,732,120 | 24.6% |
| <= 128 | 10,074,590 | 66.5% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 1 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 3 | 0.0% |
| <= 131,072 | 66 | 0.0% |
| <= 262,144 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 113,516,640 | 13.8% | 13.8% |  |
| _CHECK_VALIDITY | 105,302,740 | 12.8% | 26.6% |  |
| _GUARD_TYPE_VERSION | 91,782,240 | 11.2% | 37.8% | 0.4% |
| LOAD_FAST | 86,533,050 | 10.5% | 48.4% |  |
| _LOAD_ATTR_SLOT | 40,670,260 | 5.0% | 53.3% |  |
| STORE_FAST | 25,598,390 | 3.1% | 56.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 22,008,870 | 2.7% | 59.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 22,008,870 | 2.7% | 61.8% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 20,893,310 | 2.5% | 64.3% |  |
| _GUARD_IS_FALSE_POP | 20,749,840 | 2.5% | 66.9% | 0.2% |
| TO_BOOL_BOOL | 20,149,180 | 2.5% | 69.3% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 14,927,240 | 1.8% | 71.1% | 5.0% |
| _ITER_CHECK_RANGE | 14,927,240 | 1.8% | 72.9% |  |
| _ITER_NEXT_RANGE | 14,179,010 | 1.7% | 74.7% |  |
| _EXIT_TRACE | 13,986,780 | 1.7% | 76.4% |  |
| _CHECK_PEP_523 | 13,808,140 | 1.7% | 78.1% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 13,808,140 | 1.7% | 79.7% |  |
| _CHECK_STACK_SPACE | 13,808,140 | 1.7% | 81.4% |  |
| _INIT_CALL_PY_EXACT_ARGS | 13,808,140 | 1.7% | 83.1% |  |
| _PUSH_FRAME | 13,808,140 | 1.7% | 84.8% |  |
| _SAVE_RETURN_OFFSET | 13,808,140 | 1.7% | 86.5% |  |
| PUSH_NULL | 10,675,180 | 1.3% | 87.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,446,890 | 1.3% | 89.0% |  |
| BUILD_LIST | 10,074,590 | 1.2% | 90.3% |  |
| CALL_INTRINSIC_1 | 10,074,590 | 1.2% | 91.5% |  |
| LIST_EXTEND | 10,074,590 | 1.2% | 92.7% |  |
| RESUME_CHECK | 10,074,590 | 1.2% | 93.9% |  |
| _LOAD_ATTR | 10,074,590 | 1.2% | 95.2% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 7,465,670 | 0.9% | 96.1% |  |
| _GUARD_KEYS_VERSION | 7,465,670 | 0.9% | 97.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 7,465,670 | 0.9% | 97.9% |  |
| LOAD_CONST | 4,475,850 | 0.5% | 98.4% |  |
| _GUARD_BOTH_INT | 3,732,120 | 0.5% | 98.9% |  |
| _BINARY_OP_SUBTRACT_INT | 3,732,120 | 0.5% | 99.4% |  |
| CALL_BUILTIN_O | 600,590 | 0.1% | 99.4% |  |
| BINARY_SUBSCR_LIST_INT | 371,900 | 0.0% | 99.5% |  |
| COMPARE_OP_FLOAT | 371,900 | 0.0% | 99.5% |  |
| _GUARD_IS_TRUE_POP | 371,830 | 0.0% | 99.6% | 0.0% |
| POP_TOP | 371,830 | 0.0% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 371,830 | 0.0% | 99.7% |  |
| TO_BOOL_LIST | 371,830 | 0.0% | 99.7% |  |
| _GUARD_GLOBALS_VERSION | 371,830 | 0.0% | 99.7% |  |
| _LOAD_GLOBAL_MODULE | 371,830 | 0.0% | 99.8% |  |
| _CHECK_ATTR_MODULE | 371,830 | 0.0% | 99.8% |  |
| _LOAD_ATTR_MODULE | 371,830 | 0.0% | 99.9% |  |
| _STORE_ATTR_SLOT | 371,830 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 371,750 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 228,760 | 0.0% | 100.0% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 20 | 0.0% | 100.0% | 100.0% |
| _ITER_CHECK_TUPLE | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL_FUNCTION_EX | 20 |


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
Stats gathered on: 2023-11-18