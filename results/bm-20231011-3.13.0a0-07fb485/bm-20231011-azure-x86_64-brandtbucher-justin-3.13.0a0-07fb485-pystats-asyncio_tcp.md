
# Pystats results

- benchmark: asyncio_tcp
- fork: brandtbucher
- ref: justin
- commit hash: 07fb485
- commit date: 2023-10-11T15:47:19+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 65,982,375 | 21.3% | 21.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 22,723,215 | 7.4% | 28.7% |  |
| RESUME_CHECK | 16,155,660 | 5.2% | 33.9% |  |
| STORE_FAST | 14,751,825 | 4.8% | 38.7% |  |
| POP_JUMP_IF_FALSE | 13,589,280 | 4.4% | 43.1% |  |
| CALL_PY_EXACT_ARGS | 11,454,495 | 3.7% | 46.8% |  |
| LOAD_CONST | 10,886,370 | 3.5% | 50.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,997,845 | 3.2% | 53.6% |  |
| TO_BOOL_BOOL | 9,881,220 | 3.2% | 56.8% |  |
| POP_TOP | 9,633,090 | 3.1% | 59.9% |  |
| RETURN_VALUE | 9,411,660 | 3.0% | 62.9% |  |
| LOAD_GLOBAL_MODULE | 6,383,035 | 2.1% | 65.0% |  |
| LOAD_FAST_LOAD_FAST | 6,072,585 | 2.0% | 66.9% |  |
| RETURN_CONST | 5,821,905 | 1.9% | 68.8% |  |
| LOAD_GLOBAL_BUILTIN | 5,765,280 | 1.9% | 70.7% | 0.0% |
| POP_JUMP_IF_TRUE | 5,047,740 | 1.6% | 72.3% |  |
| LOAD_ATTR_SLOT | 5,030,625 | 1.6% | 74.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,635,180 | 1.5% | 75.4% |  |
| STORE_ATTR_SLOT | 4,209,270 | 1.4% | 76.8% |  |
| LOAD_ATTR | 4,129,565 | 1.3% | 78.1% |  |
| NOP | 3,719,430 | 1.2% | 79.4% |  |
| CALL | 3,270,825 | 1.1% | 80.4% |  |
| BINARY_OP | 3,170,290 | 1.0% | 81.4% |  |
| TO_BOOL_INT | 3,157,455 | 1.0% | 82.5% |  |
| COMPARE_OP_INT | 2,783,925 | 0.9% | 83.4% |  |
| LOAD_ATTR_MODULE | 2,567,335 | 0.8% | 84.2% |  |
| PUSH_NULL | 2,269,905 | 0.7% | 84.9% |  |
| CALL_LEN | 2,214,750 | 0.7% | 85.6% |  |
| COPY | 2,026,110 | 0.7% | 86.3% |  |
| INTERPRETER_EXIT | 1,999,350 | 0.6% | 86.9% |  |
| JUMP_FORWARD | 1,960,380 | 0.6% | 87.6% |  |
| TO_BOOL | 1,827,890 | 0.6% | 88.2% |  |
| ENTER_EXECUTOR | 1,814,895 | 0.6% | 88.8% |  |
| POP_JUMP_IF_NOT_NONE | 1,750,920 | 0.6% | 89.3% |  |
| POP_JUMP_IF_NONE | 1,715,355 | 0.6% | 89.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,703,160 | 0.6% | 90.4% |  |
| GET_ITER | 1,449,960 | 0.5% | 90.9% |  |
| SEND_GEN | 1,227,720 | 0.4% | 91.3% |  |
| BUILD_LIST | 1,203,240 | 0.4% | 91.7% |  |
| TO_BOOL_LIST | 1,196,700 | 0.4% | 92.1% |  |
| STORE_FAST_STORE_FAST | 1,092,645 | 0.4% | 92.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,525 | 0.4% | 92.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,012,815 | 0.3% | 93.1% |  |
| CALL_ISINSTANCE | 986,280 | 0.3% | 93.4% |  |
| YIELD_VALUE | 980,760 | 0.3% | 93.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 980,640 | 0.3% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 973,350 | 0.3% | 94.4% |  |
| FOR_ITER_LIST | 962,940 | 0.3% | 94.7% |  |
| UNARY_NOT | 960,120 | 0.3% | 95.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 820,785 | 0.3% | 95.3% | 0.1% |
| BUILD_TUPLE | 773,955 | 0.3% | 95.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 769,620 | 0.2% | 95.8% | 0.2% |
| CALL_FUNCTION_EX | 768,285 | 0.2% | 96.0% |  |
| GET_AWAITABLE | 740,280 | 0.2% | 96.2% |  |
| END_SEND | 740,280 | 0.2% | 96.5% |  |
| LIST_EXTEND | 721,200 | 0.2% | 96.7% |  |
| CALL_INTRINSIC_1 | 721,200 | 0.2% | 97.0% |  |
| LOAD_DEREF | 543,810 | 0.2% | 97.1% |  |
| CALL_BUILTIN_CLASS | 539,235 | 0.2% | 97.3% |  |
| SWAP | 532,875 | 0.2% | 97.5% |  |
| COPY_FREE_VARS | 518,550 | 0.2% | 97.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 498,375 | 0.2% | 97.8% |  |
| TO_BOOL_NONE | 496,500 | 0.2% | 98.0% |  |
| RETURN_GENERATOR | 493,980 | 0.2% | 98.1% |  |
| SEND | 493,600 | 0.2% | 98.3% |  |
| CALL_PY_WITH_DEFAULTS | 493,290 | 0.2% | 98.4% |  |
| UNARY_INVERT | 486,405 | 0.2% | 98.6% |  |
| LOAD_SUPER_ATTR_METHOD | 482,100 | 0.2% | 98.8% |  |
| FOR_ITER_RANGE | 481,200 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT | 480,960 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 280,365 | 0.1% | 99.2% |  |
| BINARY_SLICE | 280,245 | 0.1% | 99.2% |  |
| CALL_KW | 260,130 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 252,570 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 252,090 | 0.1% | 99.5% |  |
| CONTAINS_OP | 241,080 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 241,020 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_INT | 240,540 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 240,240 | 0.1% | 99.8% |  |
| BUILD_SLICE | 240,240 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 240,240 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,645 | 0.0% | 100.0% |  |
| COMPARE_OP | 13,470 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 12,750 | 0.0% | 100.0% |  |
| FOR_ITER | 12,420 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 6,615 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 6,120 | 0.0% | 100.0% |  |
| STORE_ATTR | 2,200 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,100 | 0.0% | 100.0% |  |
| IS_OP | 1,020 | 0.0% | 100.0% |  |
| MAKE_CELL | 840 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 720 | 0.0% | 100.0% |  |
| STORE_DEREF | 660 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 540 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 540 | 0.0% | 100.0% |  |
| BUILD_MAP | 540 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 480 | 0.0% | 100.0% |  |
| POP_EXCEPT | 480 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 480 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 420 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 420 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 360 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 360 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 300 | 0.0% | 100.0% |  |
| BUILD_SET | 300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 300 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 240 | 0.0% | 100.0% | 25.0% |
| UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 180 | 0.0% | 100.0% |  |
| DICT_MERGE | 180 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 140 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 120 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| LIST_APPEND | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,970,455 | 7.1% | 7.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,708,065 | 3.5% | 10.6% |
| RESUME_CHECK LOAD_FAST | 10,190,550 | 3.3% | 13.9% |
| STORE_FAST LOAD_FAST | 8,914,515 | 2.9% | 16.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,313,850 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,694,470 | 2.2% | 21.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,281,805 | 1.7% | 23.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,024,525 | 1.6% | 24.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,823,045 | 1.6% | 26.2% |
| RETURN_CONST POP_TOP | 4,791,375 | 1.6% | 27.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,702,430 | 1.5% | 29.3% |
| LOAD_CONST LOAD_FAST | 4,412,670 | 1.4% | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 4,375,875 | 1.4% | 32.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,214,130 | 1.4% | 33.5% |
| POP_TOP LOAD_FAST | 4,000,545 | 1.3% | 34.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,963,690 | 1.3% | 36.0% |
| LOAD_FAST RETURN_VALUE | 3,445,035 | 1.1% | 37.1% |
| LOAD_FAST LOAD_ATTR | 3,378,845 | 1.1% | 38.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,973,925 | 1.0% | 39.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,967,710 | 1.0% | 40.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,832,805 | 0.9% | 41.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,820,330 | 0.9% | 42.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,783,685 | 0.9% | 42.9% |
| LOAD_CONST STORE_FAST | 2,735,055 | 0.9% | 43.8% |
| NOP LOAD_FAST | 2,733,630 | 0.9% | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,710,305 | 0.9% | 45.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,566,115 | 0.8% | 46.4% |
| RETURN_VALUE STORE_FAST | 2,477,520 | 0.8% | 47.2% |
| LOAD_FAST LOAD_CONST | 2,459,775 | 0.8% | 48.0% |
| RETURN_VALUE TO_BOOL_BOOL | 2,445,075 | 0.8% | 48.8% |
| LOAD_FAST STORE_ATTR_SLOT | 2,233,170 | 0.7% | 49.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,226,690 | 0.7% | 50.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,150,205 | 0.7% | 50.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,084,910 | 0.7% | 51.6% |
| POP_TOP RETURN_CONST | 2,040,930 | 0.7% | 52.2% |
| CACHE RESUME_CHECK | 1,998,210 | 0.6% | 52.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,994,385 | 0.6% | 53.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,976,100 | 0.6% | 54.2% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,923,000 | 0.6% | 54.8% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,813,260 | 0.6% | 55.4% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,732,620 | 0.6% | 55.9% |
| STORE_FAST JUMP_FORWARD | 1,719,300 | 0.6% | 56.5% |
| RESUME_CHECK NOP | 1,718,910 | 0.6% | 57.0% |
| LOAD_CONST COMPARE_OP_INT | 1,713,320 | 0.6% | 57.6% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,699,620 | 0.5% | 58.1% |
| COPY TO_BOOL_INT | 1,545,150 | 0.5% | 58.6% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,544,790 | 0.5% | 59.1% |
| CALL STORE_FAST | 1,520,190 | 0.5% | 59.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,511,275 | 0.5% | 60.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,509,720 | 0.5% | 60.6% |
| POP_TOP LOAD_CONST | 1,501,935 | 0.5% | 61.1% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,481,655 | 0.5% | 61.6% |
| JUMP_FORWARD LOAD_FAST | 1,478,940 | 0.5% | 62.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,473,135 | 0.5% | 62.5% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,472,480 | 0.5% | 63.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,374,465 | 0.4% | 63.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,332,900 | 0.4% | 63.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,299,225 | 0.4% | 64.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,262,115 | 0.4% | 64.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,256,725 | 0.4% | 65.1% |
| STORE_ATTR_SLOT LOAD_CONST | 1,234,275 | 0.4% | 65.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,226,040 | 0.4% | 65.9% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,196,580 | 0.4% | 66.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,196,580 | 0.4% | 66.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,092,405 | 0.4% | 67.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,092,045 | 0.4% | 67.4% |
| BINARY_OP COPY | 1,064,190 | 0.3% | 67.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,026,900 | 0.3% | 68.1% |
| LOAD_ATTR LOAD_FAST | 1,025,925 | 0.3% | 68.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,024,965 | 0.3% | 68.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,020,915 | 0.3% | 69.1% |
| LOAD_FAST TO_BOOL | 1,018,760 | 0.3% | 69.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,018,560 | 0.3% | 69.7% |
| STORE_FAST RETURN_CONST | 1,008,765 | 0.3% | 70.1% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,007,190 | 0.3% | 70.4% |
| CALL RETURN_VALUE | 1,002,045 | 0.3% | 70.7% |
| CALL_LEN STORE_FAST | 1,001,640 | 0.3% | 71.0% |
| RETURN_VALUE RETURN_VALUE | 986,220 | 0.3% | 71.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 986,180 | 0.3% | 71.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 985,760 | 0.3% | 72.0% |
| NOP LOAD_GLOBAL_MODULE | 985,180 | 0.3% | 72.3% |
| LOAD_FAST STORE_FAST | 985,080 | 0.3% | 72.6% |
| POP_JUMP_IF_TRUE LOAD_CONST | 985,065 | 0.3% | 72.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 981,570 | 0.3% | 73.3% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 980,640 | 0.3% | 73.6% |
| RETURN_VALUE INTERPRETER_EXIT | 975,300 | 0.3% | 73.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 975,000 | 0.3% | 74.2% |
| STORE_FAST NOP | 974,370 | 0.3% | 74.5% |
| LOAD_FAST GET_ITER | 962,580 | 0.3% | 74.8% |
| GET_ITER FOR_ITER_LIST | 962,500 | 0.3% | 75.1% |
| TO_BOOL_BOOL UNARY_NOT | 960,060 | 0.3% | 75.5% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 820,725 | 0.3% | 75.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 807,210 | 0.3% | 76.0% |
| BINARY_OP TO_BOOL_INT | 800,250 | 0.3% | 76.2% |
| PUSH_NULL LOAD_FAST | 793,185 | 0.3% | 76.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 786,345 | 0.3% | 76.8% |
| BINARY_OP STORE_FAST | 778,500 | 0.3% | 77.0% |
| RETURN_CONST INTERPRETER_EXIT | 777,030 | 0.3% | 77.3% |
| CALL_FUNCTION_EX POP_TOP | 767,865 | 0.2% | 77.5% |
| RETURN_VALUE LOAD_FAST | 761,505 | 0.2% | 77.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,240 | 85.7% |
| LOAD_CONST | 40,005 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,240 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 33,720 | 12.0% |
| STORE_FAST | 5,925 | 2.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.1% |
| LIST_EXTEND | 180 | 0.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,998,210 | 99.9% |
| COPY_FREE_VARS | 540 | 0.0% |
| POP_TOP | 300 | 0.0% |
| RETURN_GENERATOR | 240 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 60 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 50.0% |
| LOAD_CONST | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 20 | 50.0% |
| BINARY_SUBSCR_DICT | 20 | 50.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 360 | 75.0% |
| BUILD_TUPLE | 120 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 480 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 240,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,240 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,660 | 34.1% |
| SEND | 246,600 | 33.3% |
| RETURN_VALUE | 241,020 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,380 | 67.5% |
| STORE_FAST | 240,600 | 32.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 0.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 420 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 962,580 | 66.4% |
| CALL_BUILTIN_CLASS | 481,140 | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE | 6,060 | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 962,500 | 66.4% |
| FOR_ITER_RANGE | 481,080 | 33.2% |
| FOR_ITER | 6,260 | 0.4% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 975,300 | 48.8% |
| RETURN_CONST | 777,030 | 38.9% |
| YIELD_VALUE | 246,720 | 12.3% |
| RETURN_GENERATOR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 360 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,718,910 | 46.2% |
| STORE_FAST | 974,370 | 26.2% |
| POP_JUMP_IF_FALSE | 520,905 | 14.0% |
| POP_JUMP_IF_TRUE | 246,345 | 6.6% |
| STORE_ATTR_INSTANCE_VALUE | 240,240 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,733,630 | 73.5% |
| LOAD_GLOBAL_MODULE | 985,180 | 26.5% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 360 | 75.0% |
| SWAP | 60 | 12.5% |
| COPY | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 50.0% |
| RETURN_VALUE | 60 | 12.5% |
| RERAISE | 60 | 12.5% |
| POP_TOP | 60 | 12.5% |
| LOAD_CONST | 60 | 12.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,791,375 | 49.7% |
| POP_JUMP_IF_FALSE | 1,018,560 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 820,725 | 8.5% |
| CALL_FUNCTION_EX | 767,865 | 8.0% |
| END_SEND | 499,380 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,000,545 | 41.5% |
| RETURN_CONST | 2,040,930 | 21.2% |
| LOAD_CONST | 1,501,935 | 15.6% |
| ENTER_EXECUTOR | 573,450 | 6.0% |
| LOAD_GLOBAL_MODULE | 527,130 | 5.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 300 | 62.5% |
| RERAISE | 60 | 12.5% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 440 | 91.7% |
| LOAD_GLOBAL | 40 | 8.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,511,275 | 66.6% |
| LOAD_ATTR | 721,460 | 31.8% |
| LOAD_DEREF | 35,610 | 1.6% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 793,185 | 34.9% |
| LOAD_FAST_LOAD_FAST | 746,595 | 32.9% |
| CALL | 729,465 | 32.1% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 252,900 | 51.2% |
| ENTER_EXECUTOR | 240,180 | 48.6% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,380 | 99.9% |
| INTERPRETER_EXIT | 300 | 0.1% |
| STORE_FAST | 120 | 0.0% |
| CALL | 80 | 0.0% |
| LIST_APPEND | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,445,035 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,710,305 | 28.8% |
| CALL | 1,002,045 | 10.6% |
| RETURN_VALUE | 986,220 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,630 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,477,520 | 26.3% |
| TO_BOOL_BOOL | 2,445,075 | 26.0% |
| RETURN_VALUE | 986,220 | 10.5% |
| INTERPRETER_EXIT | 975,300 | 10.4% |
| LOAD_FAST | 761,505 | 8.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 66.7% |
| STORE_SUBSCR | 20 | 11.1% |
| LOAD_FAST | 20 | 11.1% |
| LOAD_CONST | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 66.7% |
| STORE_SUBSCR_DICT | 40 | 22.2% |
| STORE_SUBSCR | 20 | 11.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,018,760 | 55.7% |
| LOAD_ATTR_INSTANCE_VALUE | 807,210 | 44.2% |
| TO_BOOL | 740 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,813,260 | 99.2% |
| POP_JUMP_IF_FALSE | 12,870 | 0.7% |
| TO_BOOL_BOOL | 860 | 0.0% |
| TO_BOOL | 740 | 0.0% |
| TO_BOOL_NONE | 100 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 246,165 | 50.6% |
| BINARY_OP | 240,240 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 486,405 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 960,060 | 100.0% |
| TO_BOOL_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 480,060 | 50.0% |
| RETURN_VALUE | 480,000 | 50.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,544,790 | 48.7% |
| LOAD_ATTR_MODULE | 565,935 | 17.9% |
| UNARY_INVERT | 486,405 | 15.3% |
| POP_JUMP_IF_FALSE | 285,870 | 9.0% |
| LOAD_ATTR | 280,065 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,064,190 | 33.6% |
| TO_BOOL_INT | 800,250 | 25.2% |
| STORE_FAST | 778,500 | 24.6% |
| BUILD_TUPLE | 280,065 | 8.8% |
| UNARY_INVERT | 240,240 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 481,080 | 40.0% |
| LOAD_ATTR_SLOT | 480,960 | 40.0% |
| LOAD_FAST_LOAD_FAST | 240,060 | 20.0% |
| LOAD_FAST | 480 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 721,440 | 60.0% |
| STORE_FAST | 481,440 | 40.0% |
| RETURN_VALUE | 180 | 0.0% |
| STORE_DEREF | 120 | 0.0% |
| SWAP | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 180 | 33.3% |
| STORE_FAST | 60 | 11.1% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 11.1% |
| RESUME_CHECK | 60 | 11.1% |
| POP_TOP | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 66.7% |
| STORE_FAST | 180 | 33.3% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 300 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,240 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 280,065 | 36.2% |
| LOAD_CONST | 246,105 | 31.8% |
| LOAD_FAST | 240,720 | 31.1% |
| LOAD_FAST_LOAD_FAST | 6,525 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 280,065 | 36.2% |
| CALL_PY_EXACT_ARGS | 252,070 | 32.6% |
| CALL | 240,280 | 31.0% |
| LOAD_CONST | 360 | 0.0% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 729,465 | 22.3% |
| LOAD_FAST_LOAD_FAST | 500,190 | 15.3% |
| LOAD_CONST | 493,505 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 487,125 | 14.9% |
| LOAD_ATTR | 240,760 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,520,190 | 46.5% |
| RETURN_VALUE | 1,002,045 | 30.6% |
| POP_TOP | 247,980 | 7.6% |
| RESUME_CHECK | 247,005 | 7.6% |
| LOAD_CONST | 240,300 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 721,200 | 93.9% |
| ENTER_EXECUTOR | 46,725 | 6.1% |
| LOAD_FAST | 180 | 0.0% |
| DICT_MERGE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 767,865 | 99.9% |
| RESUME_CHECK | 180 | 0.0% |
| GET_AWAITABLE | 120 | 0.0% |
| MAKE_CELL | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 721,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 721,200 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 260,130 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,660 | 94.8% |
| COPY_FREE_VARS | 11,850 | 4.6% |
| STORE_FAST | 600 | 0.2% |
| RETURN_GENERATOR | 300 | 0.1% |
| RESUME_CHECK | 300 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 11,850 | 88.0% |
| LOAD_ATTR_MODULE | 780 | 5.8% |
| LOAD_CONST | 400 | 3.0% |
| COMPARE_OP | 280 | 2.1% |
| CALL_BUILTIN_CLASS | 120 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,930 | 96.0% |
| COMPARE_OP | 280 | 2.1% |
| COMPARE_OP_INT | 140 | 1.0% |
| POP_JUMP_IF_TRUE | 60 | 0.4% |
| COMPARE_OP_STR | 60 | 0.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,240 | 99.7% |
| BUILD_SET | 300 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.1% |
| LOAD_FAST | 180 | 0.1% |
| LOAD_ATTR_SLOT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 240,900 | 99.9% |
| POP_JUMP_IF_TRUE | 180 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,064,190 | 52.5% |
| CALL_LEN | 480,960 | 23.7% |
| UNARY_NOT | 480,060 | 23.7% |
| LOAD_FAST | 360 | 0.0% |
| CALL_BUILTIN_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,545,150 | 76.3% |
| TO_BOOL_BOOL | 480,300 | 23.7% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.0% |
| COMPARE_OP_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,530 | 95.2% |
| CALL_KW | 11,850 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,850 | 2.3% |
| LOAD_ATTR_PROPERTY | 540 | 0.1% |
| CACHE | 540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 518,430 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 180 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 573,450 | 31.6% |
| POP_JUMP_IF_FALSE | 480,900 | 26.5% |
| CALL_LIST_APPEND | 280,065 | 15.4% |
| POP_JUMP_IF_TRUE | 240,300 | 13.2% |
| STORE_FAST | 240,180 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 480,900 | 26.5% |
| LOAD_CONST | 480,900 | 26.5% |
| LOAD_FAST | 280,125 | 15.4% |
| RETURN_CONST | 279,945 | 15.4% |
| RETURN_GENERATOR | 240,180 | 13.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 6,260 | 50.4% |
| JUMP_BACKWARD | 6,060 | 48.8% |
| FOR_ITER | 100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,060 | 48.8% |
| RETURN_CONST | 6,060 | 48.8% |
| FOR_ITER | 100 | 0.8% |
| FOR_ITER_LIST | 80 | 0.6% |
| LOAD_FAST | 60 | 0.5% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 493,380 | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE | 240,240 | 32.5% |
| LOAD_FAST | 6,180 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,280 | 100.0% |


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
| LOAD_FAST | 540 | 52.9% |
| LOAD_CONST | 420 | 41.2% |
| LOAD_FAST_LOAD_FAST | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 600 | 58.8% |
| RETURN_VALUE | 300 | 29.4% |
| LOAD_FAST | 120 | 11.8% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,300 | 95.2% |
| CALL_LIST_APPEND | 120 | 1.8% |
| POP_JUMP_IF_FALSE | 75 | 1.1% |
| LIST_APPEND | 60 | 0.9% |
| ENTER_EXECUTOR | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 6,060 | 91.6% |
| FOR_ITER_LIST | 300 | 4.5% |
| FOR_ITER_RANGE | 120 | 1.8% |
| LOAD_FAST | 75 | 1.1% |
| FOR_ITER_TUPLE | 60 | 0.9% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 980,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,040 | 74.9% |
| SEND | 246,600 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,719,300 | 87.7% |
| POP_TOP | 240,600 | 12.3% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| STORE_ATTR | 120 | 0.0% |
| CALL_LIST_APPEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,478,940 | 75.4% |
| LOAD_GLOBAL_BUILTIN | 481,200 | 24.5% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| NOP | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 480,960 | 66.7% |
| LOAD_FAST | 240,060 | 33.3% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 721,200 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,378,845 | 81.8% |
| LOAD_ATTR_SLOT | 721,120 | 17.5% |
| LOAD_FAST_LOAD_FAST | 23,860 | 0.6% |
| LOAD_ATTR | 2,760 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,025,925 | 24.8% |
| PUSH_NULL | 721,460 | 17.5% |
| SWAP | 532,035 | 12.9% |
| LOAD_ATTR_METHOD_NO_DICT | 286,550 | 6.9% |
| BINARY_OP | 280,065 | 6.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,459,775 | 22.6% |
| POP_JUMP_IF_FALSE | 1,732,620 | 15.9% |
| POP_TOP | 1,501,935 | 13.8% |
| STORE_ATTR_SLOT | 1,234,275 | 11.3% |
| POP_JUMP_IF_TRUE | 985,065 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,412,670 | 40.5% |
| STORE_FAST | 2,735,055 | 25.1% |
| COMPARE_OP_INT | 1,713,320 | 15.7% |
| SEND_GEN | 493,560 | 4.5% |
| CALL | 493,505 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 482,640 | 88.8% |
| LOAD_ATTR | 23,700 | 4.4% |
| STORE_FAST | 12,150 | 2.2% |
| RESUME_CHECK | 12,030 | 2.2% |
| CALL_LEN | 11,850 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 494,610 | 91.0% |
| PUSH_NULL | 35,610 | 6.5% |
| COMPARE_OP_INT | 11,890 | 2.2% |
| LOAD_CONST | 420 | 0.1% |
| LOAD_ATTR | 220 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,190,550 | 15.4% |
| STORE_FAST | 8,914,515 | 13.5% |
| POP_JUMP_IF_FALSE | 7,313,850 | 11.1% |
| LOAD_CONST | 4,412,670 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,214,130 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,970,455 | 33.3% |
| LOAD_ATTR_SLOT | 5,024,525 | 7.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,823,045 | 7.3% |
| CALL_PY_EXACT_ARGS | 4,702,430 | 7.1% |
| RETURN_VALUE | 3,445,035 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,481,655 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,299,225 | 21.4% |
| PUSH_NULL | 746,595 | 12.3% |
| LOAD_FAST_LOAD_FAST | 489,420 | 8.1% |
| LOAD_GLOBAL_MODULE | 481,620 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,976,100 | 32.5% |
| LOAD_FAST | 1,262,115 | 20.8% |
| CALL | 500,190 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,630 | 8.1% |
| LOAD_FAST_LOAD_FAST | 489,420 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320 | 15.2% |
| POP_TOP | 300 | 14.3% |
| STORE_FAST | 280 | 13.3% |
| LOAD_FAST | 200 | 9.5% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,560 | 74.3% |
| LOAD_GLOBAL_BUILTIN | 520 | 24.8% |
| LOAD_ATTR | 20 | 1.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 140 | 100.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 540 | 64.3% |
| CALL_KW | 120 | 14.3% |
| COPY_FREE_VARS | 60 | 7.1% |
| CALL_FUNCTION_EX | 60 | 7.1% |
| CACHE | 60 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 540 | 64.3% |
| RETURN_GENERATOR | 180 | 21.4% |
| RESUME_CHECK | 120 | 14.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,694,470 | 49.3% |
| COMPARE_OP_INT | 2,783,685 | 20.5% |
| TO_BOOL_INT | 2,150,205 | 15.8% |
| TO_BOOL_LIST | 1,196,580 | 8.8% |
| TO_BOOL_NONE | 496,500 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,313,850 | 53.8% |
| LOAD_CONST | 1,732,620 | 12.7% |
| RETURN_CONST | 1,026,900 | 7.6% |
| POP_TOP | 1,018,560 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 721,120 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 981,570 | 57.2% |
| LOAD_ATTR_INSTANCE_VALUE | 733,425 | 42.8% |
| LOAD_ATTR | 120 | 0.0% |
| CALL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,473,135 | 85.9% |
| LOAD_CONST | 240,360 | 14.0% |
| RETURN_CONST | 900 | 0.1% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,509,720 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240,900 | 13.8% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020,915 | 58.3% |
| LOAD_FAST_LOAD_FAST | 247,620 | 14.1% |
| LOAD_GLOBAL_MODULE | 247,465 | 14.1% |
| LOAD_CONST | 234,120 | 13.4% |
| RETURN_CONST | 240 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,226,690 | 44.1% |
| TO_BOOL | 1,813,260 | 35.9% |
| TO_BOOL_INT | 1,007,190 | 20.0% |
| COMPARE_OP_INT | 240 | 0.0% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,820,330 | 55.9% |
| LOAD_CONST | 985,065 | 19.5% |
| STORE_FAST | 480,960 | 9.5% |
| NOP | 246,345 | 4.9% |
| ENTER_EXECUTOR | 240,300 | 4.8% |


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
| POP_TOP | 2,040,930 | 35.1% |
| POP_JUMP_IF_FALSE | 1,026,900 | 17.6% |
| STORE_FAST | 1,008,765 | 17.3% |
| STORE_ATTR_SLOT | 740,670 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 481,680 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,791,375 | 82.3% |
| INTERPRETER_EXIT | 777,030 | 13.3% |
| END_SEND | 252,660 | 4.3% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,720 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,600 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,600 | 50.0% |
| END_SEND | 246,600 | 50.0% |
| SEND | 280 | 0.1% |
| SEND_GEN | 120 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300 | 83.3% |
| LOAD_FAST_LOAD_FAST | 60 | 16.7% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320 | 60.0% |
| LOAD_FAST_LOAD_FAST | 400 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 10.9% |
| STORE_ATTR | 160 | 7.3% |
| SWAP | 80 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,260 | 57.3% |
| LOAD_FAST | 300 | 13.6% |
| LOAD_CONST | 180 | 8.2% |
| STORE_ATTR | 160 | 7.3% |
| RETURN_CONST | 120 | 5.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 36.4% |
| CALL_KW | 120 | 18.2% |
| BUILD_LIST | 120 | 18.2% |
| BINARY_OP_ADD_INT | 120 | 18.2% |
| CALL | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 54.5% |
| LOAD_CONST | 120 | 18.2% |
| LOAD_FAST_LOAD_FAST | 60 | 9.1% |
| LOAD_DEREF | 60 | 9.1% |
| BUILD_LIST | 60 | 9.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,735,055 | 18.5% |
| RETURN_VALUE | 2,477,520 | 16.8% |
| CALL | 1,520,190 | 10.3% |
| CALL_LEN | 1,001,640 | 6.8% |
| LOAD_FAST | 985,080 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,914,515 | 60.4% |
| JUMP_FORWARD | 1,719,300 | 11.7% |
| RETURN_CONST | 1,008,765 | 6.8% |
| NOP | 974,370 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 532,035 | 3.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,405 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,092,045 | 99.9% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 532,035 | 99.8% |
| BINARY_OP_ADD_INT | 240 | 0.0% |
| BUILD_TUPLE | 180 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 532,035 | 99.8% |
| STORE_ATTR_INSTANCE_VALUE | 280 | 0.1% |
| POP_TOP | 180 | 0.0% |
| COPY | 120 | 0.0% |
| STORE_ATTR | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 60 | 30.0% |
| RETURN_VALUE | 40 | 20.0% |
| LOAD_FAST | 40 | 20.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 20 | 10.0% |
| CALL | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 140 | 70.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 30.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,040 | 74.8% |
| SEND | 246,600 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,040 | 74.8% |
| INTERPRETER_EXIT | 246,720 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 480,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,960 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 240,180 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,180 | 99.9% |
| SWAP | 240 | 0.1% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,180 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,220 | 100.0% |
| COMPARE_OP | 20 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 6,000 | 98.0% |
| LOAD_CONST | 80 | 1.3% |
| BINARY_OP | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000 | 98.0% |
| SWAP | 120 | 2.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,910 | 93.4% |
| LOAD_FAST | 820 | 6.4% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,850 | 92.9% |
| RETURN_VALUE | 600 | 4.7% |
| PUSH_EXC_INFO | 300 | 2.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 80.0% |
| LOAD_FAST_LOAD_FAST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 40 | 66.7% |
| UNPACK_SEQUENCE | 20 | 33.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 160 | 38.1% |
| CALL | 100 | 23.8% |
| LOAD_FAST | 80 | 19.0% |
| PUSH_NULL | 40 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 57.1% |
| COPY_FREE_VARS | 180 | 42.9% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,240 | 95.3% |
| CALL_BUILTIN_CLASS | 11,850 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,240 | 95.3% |
| COPY_FREE_VARS | 11,850 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 493,030 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 45,805 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,140 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,645 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,850 | 2.2% |
| LOAD_FAST | 180 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 77.8% |
| LOAD_ATTR_SLOT | 120 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 240 | 44.4% |
| COPY | 180 | 33.3% |
| POP_TOP | 120 | 22.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 45,645 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,645 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 50.0% |
| CALL | 80 | 33.3% |
| LOAD_CONST | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 75.0% |
| CALL_BUILTIN_CLASS | 40 | 16.7% |
| CALL | 20 | 8.3% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 985,760 | 99.9% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| CALL | 100 | 0.0% |
| BUILD_TUPLE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 986,180 | 100.0% |
| TO_BOOL | 100 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,923,000 | 86.8% |
| LOAD_FAST | 291,750 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,001,640 | 45.2% |
| COPY | 480,960 | 21.7% |
| LOAD_CONST | 240,180 | 10.8% |
| BINARY_OP_ADD_INT | 240,180 | 10.8% |
| LOAD_FAST | 239,940 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 280,065 | 99.9% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 280,065 | 99.9% |
| JUMP_FORWARD | 120 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 492,630 | 48.6% |
| LOAD_FAST | 279,945 | 27.6% |
| RETURN_VALUE | 240,240 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,185 | 51.4% |
| RETURN_VALUE | 492,630 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,960 | 49.4% |
| LOAD_FAST | 252,090 | 25.9% |
| LOAD_ATTR | 240,240 | 24.7% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 492,330 | 50.6% |
| STORE_FAST | 480,960 | 49.4% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 521,800 | 67.8% |
| LOAD_ATTR | 247,040 | 32.1% |
| CALL | 440 | 0.1% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,800 | 67.7% |
| TO_BOOL_BOOL | 247,000 | 32.1% |
| POP_TOP | 540 | 0.1% |
| LOAD_FAST | 420 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 786,345 | 95.8% |
| BINARY_SLICE | 33,720 | 4.1% |
| CALL | 480 | 0.1% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 820,725 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,281,805 | 46.1% |
| LOAD_FAST | 4,702,430 | 41.1% |
| LOAD_ATTR_METHOD_NO_DICT | 727,525 | 6.4% |
| BUILD_TUPLE | 252,070 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 246,265 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,708,065 | 93.5% |
| COPY_FREE_VARS | 493,530 | 4.3% |
| RETURN_GENERATOR | 252,900 | 2.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 492,510 | 99.8% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.1% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 493,170 | 100.0% |
| RETURN_GENERATOR | 120 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 75.0% |
| LOAD_GLOBAL_MODULE | 180 | 25.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,713,320 | 61.5% |
| LOAD_GLOBAL_MODULE | 480,960 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 240,220 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 239,940 | 8.6% |
| LOAD_ATTR_SLOT | 45,645 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,783,685 | 100.0% |
| POP_JUMP_IF_TRUE | 240 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 66.7% |
| COMPARE_OP | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| POP_JUMP_IF_FALSE | 60 | 33.3% |
| COPY | 60 | 33.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 962,500 | 100.0% |
| JUMP_BACKWARD | 300 | 0.0% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 559,890 | 58.1% |
| RETURN_CONST | 201,195 | 20.9% |
| LOAD_FAST | 201,015 | 20.9% |
| STORE_FAST | 600 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,080 | 100.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 481,140 | 100.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,970,455 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 492,510 | 2.2% |
| LOAD_FAST_LOAD_FAST | 252,830 | 1.1% |
| ENTER_EXECUTOR | 5,940 | 0.0% |
| LOAD_ATTR | 1,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,375,875 | 19.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,973,925 | 13.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,967,710 | 13.1% |
| RETURN_VALUE | 2,710,305 | 11.9% |
| CALL_LEN | 1,923,000 | 8.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,973,925 | 64.2% |
| LOAD_FAST | 1,374,465 | 29.7% |
| LOAD_ATTR | 286,550 | 6.2% |
| LOAD_ATTR_SLOT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,084,910 | 45.0% |
| LOAD_FAST_LOAD_FAST | 1,299,225 | 28.0% |
| CALL_PY_EXACT_ARGS | 727,525 | 15.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 521,800 | 11.3% |
| LOAD_GLOBAL_MODULE | 620 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,823,045 | 48.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,967,710 | 29.7% |
| LOAD_ATTR_SLOT | 1,472,480 | 14.7% |
| RETURN_VALUE | 492,710 | 4.9% |
| LOAD_FAST_LOAD_FAST | 240,240 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,281,805 | 52.8% |
| LOAD_FAST | 4,214,130 | 42.2% |
| LOAD_FAST_LOAD_FAST | 260,190 | 2.6% |
| LOAD_CONST | 240,480 | 2.4% |
| CALL | 720 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,566,115 | 100.0% |
| LOAD_ATTR | 1,100 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,511,275 | 58.9% |
| BINARY_OP | 565,935 | 22.0% |
| UNARY_INVERT | 246,165 | 9.6% |
| LOAD_FAST | 240,360 | 9.4% |
| COMPARE_OP | 780 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,355 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,150 | 50.6% |
| CALL | 240,240 | 48.2% |
| BINARY_OP | 5,985 | 1.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,860 | 99.9% |
| LOAD_ATTR | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,480 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,024,525 | 99.9% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,472,480 | 29.3% |
| TO_BOOL_BOOL | 1,332,900 | 26.5% |
| LOAD_ATTR | 721,120 | 14.3% |
| TO_BOOL_NONE | 495,360 | 9.8% |
| LIST_EXTEND | 480,960 | 9.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,994,385 | 34.6% |
| LOAD_FAST | 1,226,040 | 21.3% |
| POP_JUMP_IF_FALSE | 721,120 | 12.5% |
| STORE_FAST | 527,025 | 9.1% |
| JUMP_FORWARD | 481,200 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,963,690 | 68.8% |
| CALL_ISINSTANCE | 985,760 | 17.1% |
| LOAD_DEREF | 482,640 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 331,810 | 5.8% |
| CHECK_EXC_MATCH | 360 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,805 | 44.4% |
| RESUME_CHECK | 1,256,725 | 19.7% |
| NOP | 985,180 | 15.4% |
| POP_TOP | 527,130 | 8.3% |
| POP_JUMP_IF_NOT_NONE | 247,465 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,566,115 | 40.2% |
| BINARY_OP | 1,544,790 | 24.2% |
| LOAD_FAST | 1,024,965 | 16.1% |
| LOAD_FAST_LOAD_FAST | 481,620 | 7.5% |
| COMPARE_OP_INT | 480,960 | 7.5% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 540 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,960 | 100.0% |
| LOAD_SUPER_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,080 | 50.0% |
| LOAD_FAST_LOAD_FAST | 240,600 | 49.9% |
| CALL_PY_EXACT_ARGS | 320 | 0.1% |
| CALL | 100 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,708,065 | 66.3% |
| CACHE | 1,998,210 | 12.4% |
| SEND_GEN | 734,040 | 4.5% |
| COPY_FREE_VARS | 518,430 | 3.2% |
| POP_TOP | 493,980 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,190,550 | 63.1% |
| LOAD_GLOBAL_BUILTIN | 1,994,385 | 12.3% |
| NOP | 1,718,910 | 10.6% |
| LOAD_GLOBAL_MODULE | 1,256,725 | 7.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 980,640 | 6.1% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,040 | 59.8% |
| LOAD_CONST | 493,560 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,040 | 59.8% |
| POP_TOP | 493,680 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,699,620 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,000 | 0.1% |
| STORE_ATTR | 1,260 | 0.1% |
| SWAP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 975,000 | 57.2% |
| RETURN_CONST | 481,680 | 28.3% |
| NOP | 240,240 | 14.1% |
| LOAD_CONST | 3,720 | 0.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,233,170 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,976,100 | 46.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,481,655 | 35.2% |
| LOAD_CONST | 1,234,275 | 29.3% |
| RETURN_CONST | 740,670 | 17.6% |
| LOAD_FAST | 740,670 | 17.6% |
| NOP | 12,000 | 0.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,090 | 99.8% |
| LOAD_CONST | 280 | 0.1% |
| LOAD_FAST | 160 | 0.1% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,150 | 99.8% |
| RETURN_CONST | 120 | 0.0% |
| NOP | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,375,875 | 44.3% |
| RETURN_VALUE | 2,445,075 | 24.7% |
| LOAD_ATTR_SLOT | 1,332,900 | 13.5% |
| CALL_ISINSTANCE | 986,180 | 10.0% |
| COPY | 480,300 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,694,470 | 67.7% |
| POP_JUMP_IF_TRUE | 2,226,690 | 22.5% |
| UNARY_NOT | 960,060 | 9.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,545,150 | 48.9% |
| BINARY_OP | 800,250 | 25.3% |
| LOAD_FAST | 532,050 | 16.9% |
| LOAD_ATTR_INSTANCE_VALUE | 279,945 | 8.9% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,150,205 | 68.1% |
| POP_JUMP_IF_TRUE | 1,007,190 | 31.9% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,196,580 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,196,580 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 495,360 | 99.8% |
| LOAD_FAST | 740 | 0.1% |
| LOAD_ATTR | 300 | 0.1% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 496,500 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 44.4% |
| UNPACK_SEQUENCE | 60 | 33.3% |
| BINARY_SUBSCR_LIST_INT | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
| POP_TOP | 60 | 33.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 559,890 | 51.2% |
| STORE_FAST | 532,035 | 48.7% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,092,405 | 100.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        13110 | 99.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 0.0% |
|          hit |       252570 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 66.7% |
| Failure | 20 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1826130 | 11.0% |
|          hit |     14843445 | 89.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 58.0% |
| Failure | 740 | 42.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 260 | 35.1% |
| bytes | 180 | 24.3% |
| mapping | 60 | 8.1% |
| dict | 60 | 8.1% |
| bytearray | 60 | 8.1% |
| set | 40 | 5.4% |
| memory view | 40 | 5.4% |
| tuple | 20 | 2.7% |
| float | 20 | 2.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3169170 | 76.6% |
|          hit |       967920 | 23.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 14.3% |
| Failure | 960 | 85.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 660 | 68.8% |
| or | 260 | 27.1% |
| multiply different types | 20 | 2.1% |
| floor divide | 20 | 2.1% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3265485 | 13.5% |
|          hit |     20927460 | 86.5% |
|         miss |         1800 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,720 | 50.9% |
| Failure | 2,620 | 49.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 420 | 16.0% |
| class no vectorcall | 400 | 15.3% |
| code complex parameters | 400 | 15.3% |
| meth descr method fastcall keywords | 360 | 13.7% |
| meth descr varargs | 220 | 8.4% |
| class mutable | 200 | 7.6% |
| no dict | 180 | 6.9% |
| cfunc varargs keywords | 120 | 4.6% |
| other | 120 | 4.6% |
| cfunc varargs | 80 | 3.1% |
| operator wrapper | 40 | 1.5% |
| wrong number arguments | 40 | 1.5% |
| init not simple | 20 | 0.8% |
| cmethod | 20 | 0.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        12990 | 0.5% |
|          hit |      2784105 | 99.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 41.7% |
| Failure | 280 | 58.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 160 | 57.1% |
| different types | 60 | 21.4% |
| tuple | 40 | 14.3% |
| bool | 20 | 7.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        12240 | 0.8% |
|          hit |      1444260 | 99.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 44.4% |
| Failure | 100 | 55.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 40 | 40.0% |
| other | 40 | 40.0% |
| set | 20 | 20.0% |


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
| specialization.deferred |      4122305 | 8.1% |
|          hit |     46824835 | 91.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,500 | 62.0% |
| Failure | 2,760 | 38.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 880 | 31.9% |
| has managed dict | 700 | 25.4% |
| method | 640 | 23.2% |
| shadowed | 200 | 7.2% |
| metaclass attribute | 120 | 4.3% |
| non object slot | 100 | 3.6% |
| class attr simple | 40 | 1.4% |
| class method obj | 40 | 1.4% |
| class attr descriptor | 20 | 0.7% |
| builtin class method | 20 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     12412435 | 100.0% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,080 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       482640 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
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
| specialization.deferred |       493200 | 28.7% |
|          hit |      1227720 | 71.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 30.0% |
| Failure | 280 | 70.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 280 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          780 | 0.0% |
|          hit |      5912430 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,260 | 88.7% |
| Failure | 160 | 11.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 60 | 37.5% |
| overriding descriptor | 40 | 25.0% |
| overridden | 40 | 25.0% |
| no dict | 20 | 12.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1093065 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
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
| Basic | 151,046,235 | 48.9% |
| Not specialized | 35,314,935 | 11.4% |
| Specialized | 122,749,985 | 39.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 4,122,305 | 31.9% |
| CALL | 3,265,485 | 25.3% |
| BINARY_OP | 3,169,170 | 24.6% |
| TO_BOOL | 1,826,130 | 14.2% |
| SEND | 493,200 | 3.8% |
| COMPARE_OP | 12,990 | 0.1% |
| FOR_ITER | 12,240 | 0.1% |
| STORE_ATTR | 780 | 0.0% |
| STORE_SUBSCR | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,260 | 67.7% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 25.8% |
| LOAD_GLOBAL_BUILTIN | 60 | 3.2% |
| CALL_BUILTIN_O | 60 | 3.2% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNARY_NOT | 0 | 0.0% |
| UNARY_INVERT | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,999,350 | 12.0% |
| Calls to Python functions inlined | 14,708,895 | 88.0% |
| Calls via PyEval_EvalFrame (total) | 1,999,350 | 12.0% |
| Calls via PyEval_EvalFrame (vector) | 1,752,330 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 247,020 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,752,330 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 840 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,520 | 3.0% |
| Frames pushed | 15,233,925 | 91.2% |
| Frame objects created | 780 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 7,208,220 | 43.1% |
| Frees to freelist | 7,220,190 |  |
| Allocations | 9,524,417 | 56.9% |
| Allocations to 512 bytes | 9,043,127 | 54.0% |
| Allocations to 4 kbytes | 360 | 0.0% |
| Allocations over 4 kbytes | 480,930 | 2.9% |
| Frees | 9,871,909 |  |
| New values | 420 |  |
| Interpreter increfs | 128,809,225 | 82.5% |
| Interpreter decrefs | 139,878,600 | 81.6% |
| Increfs | 27,313,686 | 17.5% |
| Decrefs | 31,509,768 | 18.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,672,440 |  |
| Method cache misses | 690 |  |
| Method cache collisions | 793 |  |
| Method cache dunder hits | 1,271,705 |  |
| Method cache dunder misses | 135 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 0 | 19,200 |
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
| Optimization attempts | 360 |  |
| Traces created | 0 | 0.0% |
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
| FOR_ITER | 360 |


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
Stats gathered on: 2023-10-12
