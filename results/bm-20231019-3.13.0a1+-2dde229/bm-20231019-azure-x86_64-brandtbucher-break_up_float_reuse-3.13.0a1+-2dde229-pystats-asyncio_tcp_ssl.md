
# Pystats results

- benchmark: asyncio_tcp_ssl
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 2dde229
- commit date: 2023-10-19T19:17:27-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 90,723,817 | 23.1% | 23.1% |  |
| POP_JUMP_IF_FALSE | 21,336,327 | 5.4% | 28.6% |  |
| STORE_FAST | 20,771,067 | 5.3% | 33.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,443,009 | 4.7% | 38.6% |  |
| RESUME_CHECK | 16,693,531 | 4.3% | 42.8% |  |
| TO_BOOL_BOOL | 15,514,663 | 4.0% | 46.8% |  |
| LOAD_ATTR | 12,626,078 | 3.2% | 50.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 11,888,202 | 3.0% | 53.0% |  |
| LOAD_ATTR_WITH_HINT | 11,709,522 | 3.0% | 56.0% |  |
| LOAD_CONST | 10,649,264 | 2.7% | 58.7% |  |
| POP_TOP | 10,350,761 | 2.6% | 61.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,485,783 | 2.4% | 63.8% | 0.0% |
| CALL_PY_EXACT_ARGS | 9,369,740 | 2.4% | 66.2% |  |
| POP_JUMP_IF_TRUE | 8,673,888 | 2.2% | 68.4% |  |
| RETURN_VALUE | 7,930,784 | 2.0% | 70.4% |  |
| RETURN_CONST | 7,540,727 | 1.9% | 72.3% |  |
| CALL | 6,622,628 | 1.7% | 74.0% |  |
| JUMP_BACKWARD | 5,894,155 | 1.5% | 75.5% |  |
| TO_BOOL | 5,674,252 | 1.4% | 77.0% |  |
| LOAD_FAST_LOAD_FAST | 5,575,723 | 1.4% | 78.4% |  |
| POP_JUMP_IF_NONE | 5,553,059 | 1.4% | 79.8% |  |
| LOAD_ATTR_SLOT | 5,186,680 | 1.3% | 81.1% | 0.0% |
| LOAD_GLOBAL_MODULE | 5,145,741 | 1.3% | 82.4% |  |
| CALL_PY_WITH_DEFAULTS | 4,088,579 | 1.0% | 83.5% |  |
| LOAD_FAST_CHECK | 3,840,000 | 1.0% | 84.5% |  |
| CALL_LIST_APPEND | 3,634,438 | 0.9% | 85.4% |  |
| NOP | 3,517,672 | 0.9% | 86.3% |  |
| STORE_ATTR_SLOT | 3,498,110 | 0.9% | 87.2% | 0.1% |
| COMPARE_OP_INT | 3,495,533 | 0.9% | 88.1% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 3,154,848 | 0.8% | 88.9% | 0.0% |
| TO_BOOL_INT | 2,392,428 | 0.6% | 89.5% |  |
| CALL_LEN | 2,226,058 | 0.6% | 90.1% |  |
| PUSH_NULL | 2,053,371 | 0.5% | 90.6% |  |
| LOAD_ATTR_MODULE | 1,830,391 | 0.5% | 91.0% |  |
| INTERPRETER_EXIT | 1,757,217 | 0.4% | 91.5% |  |
| BINARY_OP | 1,659,087 | 0.4% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,543,857 | 0.4% | 92.3% | 0.0% |
| BUILD_LIST | 1,246,558 | 0.3% | 92.6% |  |
| LOAD_DEREF | 1,237,015 | 0.3% | 92.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,229,820 | 0.3% | 93.3% |  |
| SEND_GEN | 1,228,560 | 0.3% | 93.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,047,417 | 0.3% | 93.8% | 0.1% |
| FOR_ITER_LIST | 1,033,856 | 0.3% | 94.1% |  |
| BUILD_TUPLE | 1,028,937 | 0.3% | 94.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,023,656 | 0.3% | 94.6% |  |
| FOR_ITER_RANGE | 1,010,818 | 0.3% | 94.9% |  |
| JUMP_FORWARD | 990,898 | 0.3% | 95.1% |  |
| YIELD_VALUE | 981,300 | 0.3% | 95.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 981,180 | 0.3% | 95.6% |  |
| TO_BOOL_NONE | 978,840 | 0.2% | 95.9% |  |
| STORE_FAST_STORE_FAST | 832,013 | 0.2% | 96.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 831,893 | 0.2% | 96.3% |  |
| COPY | 806,156 | 0.2% | 96.5% |  |
| CALL_FUNCTION_EX | 764,098 | 0.2% | 96.7% |  |
| LIST_EXTEND | 763,738 | 0.2% | 96.9% |  |
| CALL_INTRINSIC_1 | 763,738 | 0.2% | 97.1% |  |
| GET_AWAITABLE | 740,820 | 0.2% | 97.3% |  |
| END_SEND | 740,820 | 0.2% | 97.5% |  |
| COMPARE_OP | 739,579 | 0.2% | 97.7% |  |
| GET_ITER | 737,220 | 0.2% | 97.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 529,197 | 0.1% | 98.0% |  |
| STORE_ATTR_WITH_HINT | 518,640 | 0.1% | 98.1% |  |
| BINARY_SLICE | 515,998 | 0.1% | 98.2% |  |
| BINARY_OP_ADD_INT | 500,220 | 0.1% | 98.4% |  |
| RETURN_GENERATOR | 494,400 | 0.1% | 98.5% |  |
| SEND | 493,840 | 0.1% | 98.6% |  |
| CONTAINS_OP | 488,220 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 483,960 | 0.1% | 98.9% |  |
| SWAP | 295,077 | 0.1% | 99.0% |  |
| CALL_BUILTIN_CLASS | 288,237 | 0.1% | 99.0% |  |
| COPY_FREE_VARS | 262,137 | 0.1% | 99.1% |  |
| CALL_KW | 255,299 | 0.1% | 99.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 246,659 | 0.1% | 99.2% |  |
| DELETE_SUBSCR | 246,480 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 242,520 | 0.1% | 99.3% | 0.0% |
| BINARY_OP_ADD_FLOAT_LHS | 241,620 | 0.1% | 99.4% |  |
| LOAD_ATTR_PROPERTY | 241,320 | 0.1% | 99.5% |  |
| PUSH_EXC_INFO | 241,260 | 0.1% | 99.5% |  |
| POP_EXCEPT | 241,260 | 0.1% | 99.6% |  |
| CHECK_EXC_MATCH | 241,260 | 0.1% | 99.7% |  |
| MAKE_CELL | 241,140 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 240,720 | 0.1% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 240,660 | 0.1% | 99.8% |  |
| MAKE_FUNCTION | 240,660 | 0.1% | 99.9% |  |
| BUILD_SLICE | 240,480 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,078 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 27,298 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 12,360 | 0.0% | 100.0% |  |
| FOR_ITER | 12,300 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 12,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 9,900 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,019 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,779 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 6,160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 4,860 | 0.0% | 100.0% |  |
| STORE_ATTR | 3,780 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 2,820 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,480 | 0.0% | 100.0% |  |
| IS_OP | 1,020 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 900 | 0.0% | 100.0% |  |
| BUILD_MAP | 780 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 720 | 0.0% | 100.0% | 16.7% |
| CALL_TYPE_1 | 720 | 0.0% | 100.0% |  |
| UNARY_INVERT | 660 | 0.0% | 100.0% |  |
| STORE_DEREF | 660 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 660 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 600 | 0.0% | 100.0% | 10.0% |
| EXIT_INIT_CHECK | 420 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 420 | 0.0% | 100.0% |  |
| UNARY_NOT | 360 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 300 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 300 | 0.0% | 100.0% |  |
| BUILD_SET | 300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 300 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 240 | 0.0% | 100.0% | 25.0% |
| COMPARE_OP_STR | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 180 | 0.0% | 100.0% |  |
| DICT_MERGE | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 140 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_RHS | 120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT_NEW | 120 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| LIST_APPEND | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 60 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 18,427,191 | 4.7% | 4.7% |
| STORE_FAST LOAD_FAST | 14,260,962 | 3.6% | 8.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 13,492,006 | 3.4% | 11.8% |
| RESUME_CHECK LOAD_FAST | 12,626,383 | 3.2% | 15.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 11,483,800 | 2.9% | 17.9% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 9,514,182 | 2.4% | 20.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 9,271,913 | 2.4% | 22.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,628,141 | 2.2% | 24.9% |
| LOAD_FAST LOAD_ATTR | 8,172,524 | 2.1% | 27.0% |
| LOAD_FAST TO_BOOL_BOOL | 7,927,799 | 2.0% | 29.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,915,232 | 1.8% | 30.8% |
| RETURN_CONST POP_TOP | 6,273,050 | 1.6% | 32.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 6,122,495 | 1.6% | 33.9% |
| RETURN_VALUE STORE_FAST | 5,836,436 | 1.5% | 35.4% |
| TO_BOOL POP_JUMP_IF_TRUE | 5,411,693 | 1.4% | 36.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,407,432 | 1.4% | 38.2% |
| LOAD_FAST RETURN_VALUE | 5,339,034 | 1.4% | 39.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 5,310,119 | 1.4% | 40.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,175,500 | 1.3% | 42.2% |
| CALL STORE_FAST | 5,112,054 | 1.3% | 43.5% |
| LOAD_FAST TO_BOOL | 4,861,496 | 1.2% | 44.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,817,519 | 1.2% | 46.0% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_WITH_VALUES | 4,587,202 | 1.2% | 47.2% |
| LOAD_FAST CALL | 4,577,578 | 1.2% | 48.3% |
| JUMP_BACKWARD LOAD_FAST | 4,562,461 | 1.2% | 49.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 4,088,459 | 1.0% | 50.5% |
| LOAD_ATTR CALL_PY_WITH_DEFAULTS | 4,080,840 | 1.0% | 51.6% |
| LOAD_CONST LOAD_FAST | 3,727,974 | 1.0% | 52.5% |
| CALL_LIST_APPEND JUMP_BACKWARD | 3,634,258 | 0.9% | 53.5% |
| POP_TOP RETURN_CONST | 3,519,537 | 0.9% | 54.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 3,462,997 | 0.9% | 55.2% |
| LOAD_CONST STORE_FAST | 3,427,016 | 0.9% | 56.1% |
| LOAD_FAST CALL_LIST_APPEND | 3,359,340 | 0.9% | 57.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_CHECK | 3,359,220 | 0.9% | 57.8% |
| LOAD_FAST_CHECK LOAD_ATTR_METHOD_NO_DICT | 3,359,220 | 0.9% | 58.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,356,468 | 0.9% | 59.5% |
| POP_TOP LOAD_FAST | 3,267,173 | 0.8% | 60.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,254,393 | 0.8% | 61.2% |
| NOP LOAD_FAST | 3,022,254 | 0.8% | 62.0% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 2,943,080 | 0.8% | 62.7% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,860,550 | 0.7% | 63.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,777,814 | 0.7% | 64.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,022,357 | 0.5% | 64.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,980,356 | 0.5% | 65.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,977,297 | 0.5% | 65.7% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 1,961,160 | 0.5% | 66.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,829,051 | 0.5% | 66.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,815,912 | 0.5% | 67.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 1,713,680 | 0.4% | 67.5% |
| LOAD_FAST STORE_ATTR_SLOT | 1,517,754 | 0.4% | 67.9% |
| CACHE RESUME_CHECK | 1,514,937 | 0.4% | 68.3% |
| POP_TOP LOAD_CONST | 1,487,818 | 0.4% | 68.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,484,697 | 0.4% | 69.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_WITH_HINT | 1,462,020 | 0.4% | 69.4% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 1,461,900 | 0.4% | 69.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 1,394,390 | 0.4% | 70.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,389,710 | 0.4% | 70.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,365,111 | 0.3% | 70.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,345,172 | 0.3% | 71.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,297,437 | 0.3% | 71.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,269,636 | 0.3% | 71.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,258,916 | 0.3% | 72.2% |
| LOAD_FAST LOAD_CONST | 1,239,836 | 0.3% | 72.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,224,060 | 0.3% | 72.8% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 1,216,820 | 0.3% | 73.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,204,860 | 0.3% | 73.4% |
| PUSH_NULL LOAD_FAST | 1,059,114 | 0.3% | 73.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,040,456 | 0.3% | 74.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,033,978 | 0.3% | 74.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,025,117 | 0.3% | 74.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,016,698 | 0.3% | 74.8% |
| RETURN_CONST INTERPRETER_EXIT | 1,013,877 | 0.3% | 75.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,013,138 | 0.3% | 75.3% |
| STORE_FAST RETURN_CONST | 1,004,698 | 0.3% | 75.5% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 997,978 | 0.3% | 75.8% |
| POP_JUMP_IF_FALSE NOP | 996,898 | 0.3% | 76.0% |
| STORE_ATTR_SLOT LOAD_CONST | 996,777 | 0.3% | 76.3% |
| STORE_FAST JUMP_FORWARD | 984,418 | 0.3% | 76.5% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 981,180 | 0.3% | 76.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 981,180 | 0.3% | 77.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 978,840 | 0.2% | 77.3% |
| LOAD_CONST COMPARE_OP_INT | 977,758 | 0.2% | 77.5% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 977,400 | 0.2% | 77.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 831,773 | 0.2% | 78.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 831,173 | 0.2% | 78.2% |
| POP_TOP JUMP_BACKWARD | 809,636 | 0.2% | 78.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 799,477 | 0.2% | 78.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS STORE_FAST | 797,517 | 0.2% | 78.8% |
| COPY TO_BOOL_INT | 792,056 | 0.2% | 79.0% |
| LOAD_GLOBAL_MODULE BINARY_OP | 791,756 | 0.2% | 79.2% |
| RESUME_CHECK NOP | 790,795 | 0.2% | 79.4% |
| LOAD_ATTR LOAD_FAST | 784,437 | 0.2% | 79.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 781,556 | 0.2% | 79.8% |
| LOAD_FAST CALL_LEN | 780,458 | 0.2% | 80.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 780,357 | 0.2% | 80.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 772,677 | 0.2% | 80.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 770,077 | 0.2% | 80.6% |
| FOR_ITER_RANGE STORE_FAST | 769,378 | 0.2% | 80.8% |
| JUMP_BACKWARD FOR_ITER_RANGE | 769,318 | 0.2% | 81.0% |
| LOAD_ATTR PUSH_NULL | 764,118 | 0.2% | 81.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,140 | 93.2% |
| LOAD_CONST | 34,858 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 268,799 | 52.1% |
| CALL | 240,480 | 46.6% |
| STORE_FAST | 6,299 | 1.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% |
| LIST_EXTEND | 180 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,514,937 | 86.2% |
| COPY_FREE_VARS | 241,680 | 13.8% |
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
| LOAD_CONST | 6,080 | 98.7% |
| BINARY_SUBSCR | 60 | 1.0% |
| LOAD_FAST | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000 | 97.4% |
| BINARY_SUBSCR | 60 | 1.0% |
| CALL_LEN | 40 | 0.6% |
| CALL | 20 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.3% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240,780 | 99.8% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.1% |
| BUILD_TUPLE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 241,260 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 240,480 | 97.6% |
| LOAD_CONST | 6,000 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 246,480 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,840 | 34.1% |
| SEND | 246,720 | 33.3% |
| RETURN_VALUE | 241,260 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,680 | 67.4% |
| STORE_FAST | 240,840 | 32.5% |
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
| LOAD_FAST | 489,420 | 66.4% |
| CALL_BUILTIN_CLASS | 241,560 | 32.8% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 483,400 | 65.6% |
| FOR_ITER_RANGE | 241,500 | 32.8% |
| FOR_ITER | 6,200 | 0.8% |
| FOR_ITER_TUPLE | 6,060 | 0.8% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,013,877 | 57.7% |
| RETURN_VALUE | 496,200 | 28.2% |
| YIELD_VALUE | 246,840 | 14.0% |
| RETURN_GENERATOR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 240,660 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 996,898 | 28.3% |
| RESUME_CHECK | 790,795 | 22.5% |
| POP_JUMP_IF_TRUE | 487,919 | 13.9% |
| STORE_FAST | 483,720 | 13.8% |
| NOP | 481,260 | 13.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,022,254 | 85.9% |
| NOP | 481,260 | 13.7% |
| LOAD_GLOBAL_MODULE | 13,618 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 241,140 | 100.0% |
| SWAP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240,540 | 99.7% |
| RETURN_CONST | 480 | 0.2% |
| RETURN_VALUE | 60 | 0.0% |
| RERAISE | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,273,050 | 60.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,297,437 | 12.5% |
| CALL_FUNCTION_EX | 763,438 | 7.4% |
| POP_JUMP_IF_FALSE | 516,898 | 5.0% |
| END_SEND | 499,680 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,519,537 | 34.0% |
| LOAD_FAST | 3,267,173 | 31.6% |
| LOAD_CONST | 1,487,818 | 14.4% |
| JUMP_BACKWARD | 809,636 | 7.8% |
| RESUME_CHECK | 494,400 | 4.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,540 | 99.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300 | 0.1% |
| BINARY_SUBSCR_DICT | 300 | 0.1% |
| RERAISE | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240,760 | 99.8% |
| LOAD_GLOBAL_BUILTIN | 440 | 0.2% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,269,636 | 61.8% |
| LOAD_ATTR | 764,118 | 37.2% |
| LOAD_DEREF | 18,057 | 0.9% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,059,114 | 51.6% |
| LOAD_FAST_LOAD_FAST | 502,018 | 24.4% |
| CALL | 491,459 | 23.9% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,500 | 99.8% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,800 | 99.9% |
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
| LOAD_FAST | 5,339,034 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 780,357 | 9.8% |
| CALL | 517,618 | 6.5% |
| LOAD_ATTR | 480,840 | 6.1% |
| BINARY_OP_ADD_INT | 253,080 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,836,436 | 73.6% |
| TO_BOOL_BOOL | 520,938 | 6.6% |
| LOAD_FAST | 517,498 | 6.5% |
| INTERPRETER_EXIT | 496,200 | 6.3% |
| POP_TOP | 254,338 | 3.2% |


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
| LOAD_FAST | 4,861,496 | 85.7% |
| LOAD_ATTR_INSTANCE_VALUE | 557,116 | 9.8% |
| LOAD_ATTR_WITH_HINT | 252,600 | 4.5% |
| TO_BOOL | 1,840 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,411,693 | 95.4% |
| POP_JUMP_IF_FALSE | 259,619 | 4.6% |
| TO_BOOL | 1,840 | 0.0% |
| TO_BOOL_BOOL | 900 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 60 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 360 | 54.5% |
| BINARY_OP | 300 | 45.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 660 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 300 | 83.3% |
| TO_BOOL_INT | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 180 | 50.0% |
| RETURN_VALUE | 120 | 33.3% |
| STORE_FAST | 60 | 16.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 791,756 | 47.7% |
| LOAD_ATTR_MODULE | 555,775 | 33.5% |
| LOAD_ATTR | 274,918 | 16.6% |
| POP_JUMP_IF_FALSE | 34,498 | 2.1% |
| BINARY_OP | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 550,676 | 33.2% |
| TO_BOOL_INT | 550,136 | 33.2% |
| STORE_FAST | 276,238 | 16.7% |
| BUILD_TUPLE | 274,918 | 16.6% |
| LOAD_FAST_LOAD_FAST | 5,939 | 0.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 763,198 | 61.2% |
| STORE_FAST | 241,500 | 19.4% |
| LOAD_FAST | 241,080 | 19.3% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,978 | 61.3% |
| STORE_FAST | 482,220 | 38.7% |
| RETURN_VALUE | 180 | 0.0% |
| STORE_DEREF | 120 | 0.0% |
| SWAP | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 38.5% |
| BUILD_TUPLE | 180 | 23.1% |
| STORE_FAST | 60 | 7.7% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 7.7% |
| RESUME_CHECK | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 46.2% |
| CALL_FUNCTION_EX | 240 | 30.8% |
| STORE_FAST | 180 | 23.1% |


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
| LOAD_FAST | 240,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,480 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 486,960 | 47.3% |
| BINARY_OP | 274,918 | 26.7% |
| LOAD_FAST | 247,080 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 12,540 | 1.2% |
| LOAD_FAST_LOAD_FAST | 6,779 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 486,960 | 47.3% |
| CALL_LIST_APPEND | 274,918 | 26.7% |
| LOAD_CONST | 240,660 | 23.4% |
| CALL_ISINSTANCE | 12,400 | 1.2% |
| CALL_PY_EXACT_ARGS | 12,259 | 1.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,577,578 | 69.1% |
| LOAD_FAST_LOAD_FAST | 495,299 | 7.5% |
| PUSH_NULL | 491,459 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 487,799 | 7.4% |
| LOAD_CONST | 253,779 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,112,054 | 77.2% |
| RETURN_VALUE | 517,618 | 7.8% |
| POP_TOP | 248,220 | 3.7% |
| RESUME_CHECK | 247,817 | 3.7% |
| PUSH_EXC_INFO | 240,540 | 3.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 763,498 | 99.9% |
| BUILD_MAP | 240 | 0.0% |
| DICT_MERGE | 180 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 763,438 | 99.9% |
| STORE_FAST | 240 | 0.0% |
| RESUME_CHECK | 180 | 0.0% |
| GET_AWAITABLE | 120 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 763,738 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 763,498 | 100.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 255,299 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,780 | 96.7% |
| COPY_FREE_VARS | 5,999 | 2.3% |
| STORE_FAST | 840 | 0.3% |
| RESUME_CHECK | 600 | 0.2% |
| POP_TOP | 360 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 736,979 | 99.6% |
| COMPARE_OP | 980 | 0.1% |
| LOAD_ATTR_MODULE | 780 | 0.1% |
| LOAD_CONST | 560 | 0.1% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 738,179 | 99.8% |
| COMPARE_OP | 980 | 0.1% |
| POP_JUMP_IF_TRUE | 180 | 0.0% |
| COMPARE_OP_INT | 160 | 0.0% |
| COMPARE_OP_STR | 80 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 486,960 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 300 | 0.1% |
| BUILD_SET | 300 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 488,040 | 100.0% |
| POP_JUMP_IF_TRUE | 180 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 550,676 | 68.3% |
| CALL_LEN | 241,380 | 29.9% |
| LOAD_FAST | 12,960 | 1.6% |
| SWAP | 540 | 0.1% |
| UNARY_NOT | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 792,056 | 98.3% |
| LOAD_ATTR_WITH_HINT | 12,120 | 1.5% |
| LOAD_ATTR_INSTANCE_VALUE | 760 | 0.1% |
| COMPARE_OP_INT | 540 | 0.1% |
| TO_BOOL_BOOL | 420 | 0.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 241,680 | 92.2% |
| CALL_PY_EXACT_ARGS | 7,799 | 3.0% |
| CALL_KW | 5,999 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,999 | 2.3% |
| LOAD_ATTR_PROPERTY | 540 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 262,017 | 100.0% |
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

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 6,200 | 50.4% |
| JUMP_BACKWARD | 6,000 | 48.8% |
| FOR_ITER | 100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000 | 48.8% |
| RETURN_CONST | 6,000 | 48.8% |
| FOR_ITER | 100 | 0.8% |
| FOR_ITER_LIST | 80 | 0.7% |
| LOAD_FAST | 60 | 0.5% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 493,800 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 240,420 | 32.5% |
| LOAD_FAST | 6,120 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,820 | 100.0% |


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
| CALL_LIST_APPEND | 3,634,258 | 61.7% |
| POP_TOP | 809,636 | 13.7% |
| JUMP_FORWARD | 480,780 | 8.2% |
| POP_JUMP_IF_FALSE | 241,741 | 4.1% |
| POP_JUMP_IF_TRUE | 240,720 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,562,461 | 77.4% |
| FOR_ITER_RANGE | 769,318 | 13.1% |
| FOR_ITER_LIST | 550,316 | 9.3% |
| FOR_ITER_TUPLE | 6,060 | 0.1% |
| FOR_ITER | 6,000 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 981,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,460 | 74.9% |
| SEND | 246,720 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 984,418 | 99.3% |
| POP_JUMP_IF_FALSE | 4,800 | 0.5% |
| POP_TOP | 840 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 0.0% |
| STORE_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 480,780 | 48.5% |
| LOAD_FAST | 262,978 | 26.5% |
| LOAD_GLOBAL_BUILTIN | 246,360 | 24.9% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| NOP | 240 | 0.0% |


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
| LOAD_ATTR_SLOT | 763,198 | 99.9% |
| LOAD_FAST | 360 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 763,738 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,172,524 | 64.7% |
| LOAD_GLOBAL_MODULE | 1,713,680 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 981,180 | 7.8% |
| LOAD_ATTR_SLOT | 763,398 | 6.0% |
| LOAD_ATTR_WITH_HINT | 734,540 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 4,080,840 | 32.3% |
| CALL_PY_EXACT_ARGS | 2,943,080 | 23.3% |
| LOAD_FAST | 784,437 | 6.2% |
| PUSH_NULL | 764,118 | 6.1% |
| COMPARE_OP | 736,979 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,977,297 | 18.6% |
| POP_TOP | 1,487,818 | 14.0% |
| LOAD_FAST | 1,239,836 | 11.6% |
| STORE_ATTR_SLOT | 996,777 | 9.4% |
| GET_AWAITABLE | 740,820 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,727,974 | 35.0% |
| STORE_FAST | 3,427,016 | 32.2% |
| COMPARE_OP_INT | 977,758 | 9.2% |
| SEND_GEN | 493,980 | 4.6% |
| CALL_PY_EXACT_ARGS | 481,520 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 486,779 | 39.4% |
| STORE_FAST | 246,599 | 19.9% |
| POP_JUMP_IF_FALSE | 240,660 | 19.5% |
| LOAD_CONST | 240,300 | 19.4% |
| LOAD_ATTR | 11,998 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 721,140 | 58.3% |
| LOAD_ATTR | 240,520 | 19.4% |
| STORE_ATTR_WITH_HINT | 240,300 | 19.4% |
| PUSH_NULL | 18,057 | 1.5% |
| LOAD_FAST | 9,479 | 0.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,260,962 | 15.7% |
| RESUME_CHECK | 12,626,383 | 13.9% |
| POP_JUMP_IF_FALSE | 11,483,800 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 9,271,913 | 10.2% |
| POP_JUMP_IF_TRUE | 6,915,232 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 18,427,191 | 20.3% |
| LOAD_ATTR_WITH_HINT | 9,514,182 | 10.5% |
| LOAD_ATTR | 8,172,524 | 9.0% |
| TO_BOOL_BOOL | 7,927,799 | 8.7% |
| RETURN_VALUE | 5,339,034 | 5.9% |


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

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,359,220 | 87.5% |
| STORE_FAST | 240,360 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 240,360 | 6.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 42 | 0.0% |
| LOAD_ATTR | 18 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,359,220 | 87.5% |
| LOAD_FAST | 240,360 | 6.3% |
| CALL_METHOD_DESCRIPTOR_O | 240,360 | 6.3% |
| CALL | 38 | 0.0% |
| CALL_PY_EXACT_ARGS | 22 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,484,697 | 26.6% |
| STORE_FAST | 1,040,456 | 18.7% |
| POP_JUMP_IF_FALSE | 741,539 | 13.3% |
| LOAD_ATTR_METHOD_NO_DICT | 557,275 | 10.0% |
| PUSH_NULL | 502,018 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,980,356 | 35.5% |
| LOAD_ATTR_WITH_HINT | 1,462,020 | 26.2% |
| LOAD_FAST | 772,677 | 13.9% |
| CALL | 495,299 | 8.9% |
| LOAD_FAST_LOAD_FAST | 490,740 | 8.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320 | 12.9% |
| POP_TOP | 280 | 11.3% |
| STORE_FAST | 260 | 10.5% |
| LOAD_FAST | 260 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,820 | 73.4% |
| LOAD_GLOBAL_BUILTIN | 640 | 25.8% |
| LOAD_ATTR | 20 | 0.8% |


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
| CALL_PY_EXACT_ARGS | 240,300 | 99.7% |
| MAKE_CELL | 540 | 0.2% |
| CALL_KW | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,420 | 99.7% |
| MAKE_CELL | 540 | 0.2% |
| RETURN_GENERATOR | 180 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 13,492,006 | 63.2% |
| COMPARE_OP_INT | 3,254,393 | 15.3% |
| TO_BOOL_INT | 1,394,390 | 6.5% |
| TO_BOOL_NONE | 978,840 | 4.6% |
| COMPARE_OP | 738,179 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,483,800 | 53.8% |
| LOAD_FAST_CHECK | 3,359,220 | 15.7% |
| LOAD_CONST | 1,977,297 | 9.3% |
| RETURN_CONST | 1,258,916 | 5.9% |
| NOP | 996,898 | 4.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,817,519 | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE | 734,580 | 13.2% |
| LOAD_ATTR | 480 | 0.0% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,310,119 | 95.6% |
| LOAD_CONST | 240,780 | 4.3% |
| RETURN_CONST | 1,140 | 0.0% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 781,556 | 76.3% |
| LOAD_ATTR_INSTANCE_VALUE | 241,200 | 23.6% |
| LOAD_ATTR_WITH_HINT | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 525,957 | 51.4% |
| LOAD_GLOBAL_MODULE | 248,679 | 24.3% |
| LOAD_FAST_LOAD_FAST | 247,740 | 24.2% |
| LOAD_GLOBAL_BUILTIN | 380 | 0.0% |
| RETURN_CONST | 360 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 5,411,693 | 62.4% |
| TO_BOOL_BOOL | 2,022,357 | 23.3% |
| TO_BOOL_INT | 997,978 | 11.5% |
| COMPARE_OP_INT | 241,140 | 2.8% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,915,232 | 79.7% |
| NOP | 487,919 | 5.6% |
| RETURN_CONST | 275,398 | 3.2% |
| LOAD_CONST | 271,739 | 3.1% |
| STORE_FAST | 241,380 | 2.8% |


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
| POP_TOP | 3,519,537 | 46.7% |
| POP_JUMP_IF_FALSE | 1,258,916 | 16.7% |
| STORE_FAST | 1,004,698 | 13.3% |
| STORE_ATTR_SLOT | 502,198 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 482,940 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,273,050 | 83.2% |
| INTERPRETER_EXIT | 1,013,877 | 13.4% |
| END_SEND | 252,840 | 3.4% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,840 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,720 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,720 | 50.0% |
| END_SEND | 246,720 | 50.0% |
| SEND | 280 | 0.1% |
| SEND_GEN | 120 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 240,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,600 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640 | 69.8% |
| LOAD_FAST_LOAD_FAST | 420 | 11.1% |
| STORE_ATTR | 400 | 10.6% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 6.3% |
| SWAP | 80 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,400 | 37.0% |
| LOAD_FAST | 1,020 | 27.0% |
| LOAD_CONST | 420 | 11.1% |
| STORE_ATTR | 400 | 10.6% |
| JUMP_FORWARD | 180 | 4.8% |


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
| RETURN_VALUE | 5,836,436 | 28.1% |
| CALL | 5,112,054 | 24.6% |
| LOAD_CONST | 3,427,016 | 16.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 797,517 | 3.8% |
| FOR_ITER_RANGE | 769,378 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,260,962 | 68.7% |
| LOAD_FAST_LOAD_FAST | 1,040,456 | 5.0% |
| LOAD_GLOBAL_BUILTIN | 1,016,698 | 4.9% |
| RETURN_CONST | 1,004,698 | 4.8% |
| JUMP_FORWARD | 984,418 | 4.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 831,773 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 831,173 | 99.9% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 281,217 | 95.3% |
| BINARY_OP_ADD_INT | 6,600 | 2.2% |
| BINARY_OP_SUBTRACT_INT | 6,360 | 2.2% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |
| CALL_LEN | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 281,217 | 95.3% |
| STORE_ATTR_WITH_HINT | 12,120 | 4.1% |
| STORE_ATTR_INSTANCE_VALUE | 760 | 0.3% |
| COPY | 540 | 0.2% |
| POP_TOP | 180 | 0.1% |


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
| YIELD_VALUE | 734,460 | 74.8% |
| SEND | 246,720 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,460 | 74.8% |
| INTERPRETER_EXIT | 246,840 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 241,380 | 99.9% |
| LOAD_FAST | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,380 | 99.9% |
| LOAD_FAST | 240 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 253,080 | 50.6% |
| CALL_LEN | 246,420 | 49.3% |
| LOAD_CONST | 640 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 253,080 | 50.6% |
| STORE_FAST | 240,420 | 48.1% |
| SWAP | 6,600 | 1.3% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT_NEW

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT_NEW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 120 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,420 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,460 | 99.9% |
| STORE_FAST | 240 | 0.1% |
| COMPARE_OP | 20 | 0.0% |


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
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_RHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_RHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000 | 48.5% |
| LOAD_FAST | 6,000 | 48.5% |
| LOAD_CONST | 320 | 2.6% |
| BINARY_OP | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 6,360 | 51.5% |
| STORE_FAST | 6,000 | 48.5% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,059 | 86.3% |
| LOAD_FAST | 940 | 13.4% |
| BINARY_SUBSCR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,999 | 85.5% |
| RETURN_VALUE | 720 | 10.3% |
| PUSH_EXC_INFO | 300 | 4.3% |


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
| LOAD_CONST | 9,880 | 99.8% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,100 | 51.5% |
| STORE_FAST | 4,740 | 47.9% |
| UNPACK_SEQUENCE_TUPLE | 40 | 0.4% |
| UNPACK_SEQUENCE | 20 | 0.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 47.6% |
| CALL | 100 | 23.8% |
| PUSH_NULL | 40 | 9.5% |
| LOAD_FAST_LOAD_FAST | 40 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 360 | 85.7% |
| COPY_FREE_VARS | 60 | 14.3% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,660 | 97.6% |
| CALL_BUILTIN_CLASS | 5,999 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,660 | 97.6% |
| COPY_FREE_VARS | 5,999 | 2.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,599 | 85.9% |
| LOAD_ATTR_INSTANCE_VALUE | 40,238 | 14.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 241,560 | 83.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,078 | 13.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,999 | 2.1% |
| LOAD_FAST | 180 | 0.1% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540 | 60.0% |
| LOAD_FAST | 240 | 26.7% |
| LOAD_ATTR_SLOT | 120 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 360 | 40.0% |
| POP_TOP | 360 | 40.0% |
| COPY | 180 | 20.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40,078 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40,078 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240 | 40.0% |
| LOAD_FAST | 120 | 20.0% |
| BINARY_OP_MULTIPLY_FLOAT_NEW | 120 | 20.0% |
| CALL | 80 | 13.3% |
| LOAD_CONST | 40 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 40.0% |
| POP_TOP | 180 | 30.0% |
| LOAD_CONST | 120 | 20.0% |
| CALL_BUILTIN_CLASS | 40 | 6.7% |
| CALL | 20 | 3.3% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 14,318 | 52.5% |
| BUILD_TUPLE | 12,400 | 45.4% |
| LOAD_GLOBAL_MODULE | 280 | 1.0% |
| LOAD_ATTR_MODULE | 160 | 0.6% |
| CALL | 140 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 27,158 | 99.5% |
| TO_BOOL | 140 | 0.5% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,204,860 | 54.1% |
| LOAD_FAST | 780,458 | 35.1% |
| LOAD_ATTR_WITH_HINT | 240,660 | 10.8% |
| CALL | 40 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,899 | 23.5% |
| TO_BOOL_INT | 487,680 | 21.9% |
| LOAD_FAST | 480,960 | 21.6% |
| BINARY_OP_ADD_INT | 246,420 | 11.1% |
| COPY | 241,380 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,340 | 92.4% |
| BUILD_TUPLE | 274,918 | 7.6% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,634,258 | 100.0% |
| JUMP_FORWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,038 | 52.0% |
| LOAD_ATTR_METHOD_NO_DICT | 247,140 | 46.7% |
| LOAD_FAST_LOAD_FAST | 6,719 | 1.3% |
| RETURN_VALUE | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,238 | 98.7% |
| RETURN_VALUE | 6,839 | 1.3% |
| POP_TOP | 120 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 241,380 | 99.5% |
| LOAD_FAST | 420 | 0.2% |
| LOAD_ATTR | 300 | 0.1% |
| LOAD_CONST | 220 | 0.1% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,500 | 99.6% |
| POP_TOP | 840 | 0.3% |
| RETURN_VALUE | 120 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 799,477 | 76.3% |
| LOAD_ATTR | 247,160 | 23.6% |
| CALL | 440 | 0.0% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 797,517 | 76.1% |
| TO_BOOL_BOOL | 247,120 | 23.6% |
| POP_TOP | 780 | 0.1% |
| RETURN_VALUE | 540 | 0.1% |
| LOAD_FAST | 420 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,033,978 | 67.0% |
| BINARY_SLICE | 268,799 | 17.4% |
| LOAD_FAST_CHECK | 240,360 | 15.6% |
| CALL | 480 | 0.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,297,437 | 84.0% |
| CALL_PY_EXACT_ARGS | 240,360 | 15.6% |
| RETURN_VALUE | 6,000 | 0.4% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 2,943,080 | 31.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,860,550 | 30.5% |
| LOAD_FAST | 1,815,912 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 770,077 | 8.2% |
| LOAD_CONST | 481,520 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,628,141 | 92.1% |
| RETURN_GENERATOR | 493,500 | 5.3% |
| MAKE_CELL | 240,300 | 2.6% |
| COPY_FREE_VARS | 7,799 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,080,840 | 99.8% |
| LOAD_FAST | 6,719 | 0.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,088,459 | 100.0% |
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

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,740 | 97.5% |
| LOAD_ATTR_SLOT | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,740 | 97.5% |
| RETURN_VALUE | 120 | 2.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 1,461,900 | 41.8% |
| LOAD_CONST | 977,758 | 28.0% |
| LOAD_GLOBAL_MODULE | 241,380 | 6.9% |
| LOAD_FAST | 240,660 | 6.9% |
| BINARY_OP_MULTIPLY_INT | 240,460 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,254,393 | 93.1% |
| POP_JUMP_IF_TRUE | 241,140 | 6.9% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 66.7% |
| COMPARE_OP | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 50.0% |
| STORE_FAST | 60 | 25.0% |
| COPY | 60 | 25.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 550,316 | 53.2% |
| GET_ITER | 483,400 | 46.8% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 549,836 | 53.2% |
| RETURN_CONST | 241,560 | 23.4% |
| LOAD_FAST | 241,380 | 23.3% |
| STORE_FAST | 780 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 769,318 | 76.1% |
| GET_ITER | 241,500 | 23.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 769,378 | 76.1% |
| LOAD_CONST | 241,380 | 23.9% |
| LOAD_FAST | 60 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,060 | 50.0% |
| GET_ITER | 6,060 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,060 | 50.0% |
| NOP | 6,000 | 49.5% |
| LOAD_GLOBAL_MODULE | 40 | 0.3% |
| LOAD_GLOBAL | 20 | 0.2% |


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
| LOAD_FAST | 18,427,191 | 99.9% |
| LOAD_FAST_LOAD_FAST | 7,039 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,719 | 0.0% |
| LOAD_ATTR | 1,220 | 0.0% |
| COPY | 760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,122,495 | 33.2% |
| TO_BOOL_BOOL | 3,462,997 | 18.8% |
| CALL_LEN | 1,204,860 | 6.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,025,117 | 5.6% |
| LOAD_ATTR | 981,180 | 5.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,122,495 | 51.5% |
| LOAD_FAST_CHECK | 3,359,220 | 28.3% |
| LOAD_FAST | 1,389,710 | 11.7% |
| LOAD_ATTR_WITH_HINT | 494,040 | 4.2% |
| LOAD_ATTR | 282,097 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,271,913 | 78.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 799,477 | 6.7% |
| CALL_PY_EXACT_ARGS | 770,077 | 6.5% |
| LOAD_FAST_LOAD_FAST | 557,275 | 4.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 247,140 | 2.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 4,587,202 | 48.4% |
| LOAD_FAST | 3,356,468 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,025,117 | 10.8% |
| LOAD_ATTR_SLOT | 508,117 | 5.4% |
| RETURN_VALUE | 6,919 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,407,432 | 57.0% |
| CALL_PY_EXACT_ARGS | 2,860,550 | 30.2% |
| LOAD_FAST_LOAD_FAST | 494,999 | 5.2% |
| LOAD_CONST | 481,020 | 5.1% |
| LOAD_GLOBAL_MODULE | 240,560 | 2.5% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,829,051 | 99.9% |
| LOAD_ATTR | 1,220 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,269,636 | 69.4% |
| BINARY_OP | 555,775 | 30.4% |
| COMPARE_OP | 780 | 0.0% |
| LOAD_GLOBAL_MODULE | 500 | 0.0% |
| LOAD_ATTR | 500 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 94.4% |
| LOAD_ATTR | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 66.7% |
| CALL | 120 | 16.7% |
| BINARY_OP | 120 | 16.7% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,180 | 99.9% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,780 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,175,500 | 99.8% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 5,100 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,365,111 | 26.3% |
| TO_BOOL_NONE | 977,400 | 18.8% |
| LOAD_ATTR | 763,398 | 14.7% |
| LIST_EXTEND | 763,198 | 14.7% |
| BUILD_LIST | 763,198 | 14.7% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,514,182 | 81.3% |
| LOAD_FAST_LOAD_FAST | 1,462,020 | 12.5% |
| LOAD_DEREF | 721,140 | 6.2% |
| COPY | 12,120 | 0.1% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,587,202 | 39.2% |
| TO_BOOL_BOOL | 1,961,160 | 16.7% |
| COMPARE_OP_INT | 1,461,900 | 12.5% |
| LOAD_GLOBAL_MODULE | 1,216,820 | 10.4% |
| LOAD_ATTR | 734,540 | 6.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,016,698 | 32.2% |
| POP_JUMP_IF_FALSE | 477,200 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 345,516 | 11.0% |
| RESUME_CHECK | 310,616 | 9.8% |
| LOAD_FAST | 267,178 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,777,814 | 88.0% |
| LOAD_GLOBAL_BUILTIN | 345,516 | 11.0% |
| CALL_ISINSTANCE | 14,318 | 0.5% |
| BUILD_TUPLE | 12,540 | 0.4% |
| LOAD_DEREF | 3,360 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,345,172 | 26.1% |
| LOAD_ATTR_WITH_HINT | 1,216,820 | 23.6% |
| RESUME_CHECK | 1,013,138 | 19.7% |
| LOAD_ATTR | 494,000 | 9.6% |
| POP_TOP | 282,017 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,829,051 | 35.5% |
| LOAD_ATTR | 1,713,680 | 33.3% |
| BINARY_OP | 791,756 | 15.4% |
| COMPARE_OP_INT | 241,380 | 4.7% |
| CALL_PY_EXACT_ARGS | 241,340 | 4.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 81.8% |
| LOAD_GLOBAL_MODULE | 120 | 18.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 540 | 81.8% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 18.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,680 | 95.0% |
| LOAD_SUPER_ATTR | 140 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,140 | 40.4% |
| LOAD_FAST_LOAD_FAST | 900 | 31.9% |
| CALL_PY_EXACT_ARGS | 680 | 24.1% |
| CALL | 100 | 3.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 8,628,141 | 51.7% |
| CALL_PY_WITH_DEFAULTS | 4,088,459 | 24.5% |
| CACHE | 1,514,937 | 9.1% |
| SEND_GEN | 734,460 | 4.4% |
| POP_TOP | 494,400 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,626,383 | 75.6% |
| LOAD_GLOBAL_MODULE | 1,013,138 | 6.1% |
| JUMP_BACKWARD_NO_INTERRUPT | 981,180 | 5.9% |
| NOP | 790,795 | 4.7% |
| LOAD_DEREF | 486,779 | 2.9% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,460 | 59.8% |
| LOAD_CONST | 493,980 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,460 | 59.8% |
| POP_TOP | 494,100 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,224,060 | 99.5% |
| LOAD_FAST_LOAD_FAST | 3,360 | 0.3% |
| STORE_ATTR | 1,400 | 0.1% |
| SWAP | 760 | 0.1% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 496,620 | 40.4% |
| RETURN_CONST | 482,940 | 39.3% |
| NOP | 240,420 | 19.5% |
| LOAD_CONST | 5,220 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,420 | 0.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,980,356 | 56.6% |
| LOAD_FAST | 1,517,754 | 43.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,484,697 | 42.4% |
| LOAD_CONST | 996,777 | 28.5% |
| LOAD_FAST | 502,438 | 14.4% |
| RETURN_CONST | 502,198 | 14.4% |
| NOP | 12,000 | 0.3% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 265,260 | 51.1% |
| LOAD_DEREF | 240,300 | 46.3% |
| SWAP | 12,120 | 2.3% |
| LOAD_FAST_LOAD_FAST | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 253,140 | 48.8% |
| RETURN_CONST | 247,140 | 47.7% |
| NOP | 11,880 | 2.3% |
| JUMP_BACKWARD | 6,000 | 1.2% |
| LOAD_CONST | 360 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 6,299 | 92.9% |
| LOAD_CONST | 280 | 4.1% |
| LOAD_FAST | 160 | 2.4% |
| STORE_SUBSCR | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,359 | 93.8% |
| RETURN_CONST | 120 | 1.8% |
| NOP | 120 | 1.8% |
| LOAD_CONST | 120 | 1.8% |
| LOAD_FAST_LOAD_FAST | 60 | 0.9% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 80.0% |
| TO_BOOL | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 180 | 60.0% |
| POP_JUMP_IF_TRUE | 120 | 40.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,927,799 | 51.1% |
| LOAD_ATTR_INSTANCE_VALUE | 3,462,997 | 22.3% |
| LOAD_ATTR_WITH_HINT | 1,961,160 | 12.6% |
| LOAD_ATTR_SLOT | 1,365,111 | 8.8% |
| RETURN_VALUE | 520,938 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,492,006 | 87.0% |
| POP_JUMP_IF_TRUE | 2,022,357 | 13.0% |
| UNARY_NOT | 300 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 792,056 | 33.1% |
| BINARY_OP | 550,136 | 23.0% |
| CALL_LEN | 487,680 | 20.4% |
| LOAD_FAST | 281,398 | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE | 281,098 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,394,390 | 58.3% |
| POP_JUMP_IF_TRUE | 997,978 | 41.7% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 483,840 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 483,840 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 977,400 | 99.9% |
| LOAD_FAST | 860 | 0.1% |
| LOAD_ATTR | 540 | 0.1% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 978,840 | 100.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 83.3% |
| TO_BOOL | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 120 | 50.0% |
| POP_JUMP_IF_FALSE | 120 | 50.0% |


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
| FOR_ITER_LIST | 549,836 | 66.1% |
| STORE_FAST | 281,217 | 33.8% |
| RETURN_VALUE | 320 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 831,773 | 100.0% |
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
| specialization.deferred |         6060 | 25.9% |
|          hit |        17219 | 73.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 40.0% |
| Failure | 60 | 60.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 40 | 66.7% |
| out of range | 20 | 33.3% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 1.7% |
|          hit |         6779 | 97.4% |

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
| specialization.deferred |      5671312 | 22.6% |
|          hit |     19370371 | 77.3% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,100 | 37.4% |
| Failure | 1,840 | 62.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 1,200 | 65.2% |
| sequence | 340 | 18.5% |
| mapping | 60 | 3.3% |
| dict | 60 | 3.3% |
| bytearray | 60 | 3.3% |
| set | 40 | 2.2% |
| memory view | 40 | 2.2% |
| tuple | 20 | 1.1% |
| float | 20 | 1.1% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1658207 | 62.5% |
|          hit |       995220 | 37.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 18.2% |
| Failure | 720 | 81.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 460 | 63.9% |
| or | 160 | 22.2% |
| floor divide | 60 | 8.3% |
| multiply different types | 40 | 5.6% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6615788 | 21.9% |
|          hit |     23531457 | 78.0% |
|         miss |         1920 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,020 | 44.2% |
| Failure | 3,820 | 55.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 1,160 | 30.4% |
| class no vectorcall | 500 | 13.1% |
| code complex parameters | 460 | 12.0% |
| meth descr method fastcall keywords | 360 | 9.4% |
| cfunc noargs | 360 | 9.4% |
| no dict | 260 | 6.8% |
| class mutable | 200 | 5.2% |
| cfunc varargs keywords | 120 | 3.1% |
| other | 120 | 3.1% |
| cfunc varargs | 80 | 2.1% |
| operator wrapper | 60 | 1.6% |
| meth descr varargs keywords | 60 | 1.6% |
| wrong number arguments | 40 | 1.0% |
| init not simple | 20 | 0.5% |
| cmethod | 20 | 0.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       738359 | 17.4% |
|          hit |      3500513 | 82.6% |
|         miss |          120 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 19.7% |
| Failure | 980 | 80.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 660 | 67.3% |
| other | 160 | 16.3% |
| different types | 60 | 6.1% |
| float long | 40 | 4.1% |
| tuple | 40 | 4.1% |
| bool | 20 | 2.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        12120 | 0.6% |
|          hit |      2056794 | 99.4% |

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
| specialization.deferred |     12614018 | 17.7% |
|          hit |     58784847 | 82.3% |
|         miss |         1080 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,840 | 40.1% |
| Failure | 7,220 | 59.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 3,800 | 52.6% |
| metaclass attribute | 1,440 | 19.9% |
| not managed dict | 800 | 11.1% |
| method | 740 | 10.2% |
| shadowed | 200 | 2.8% |
| non object slot | 100 | 1.4% |
| class method obj | 60 | 0.8% |
| class attr simple | 40 | 0.6% |
| class attr descriptor | 20 | 0.3% |
| builtin class method | 20 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      8300529 | 100.0% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,460 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         3480 | 96.1% |

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
| specialization.deferred |       493440 | 28.6% |
|          hit |      1228560 | 71.3% |

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
| specialization.deferred |         1980 | 0.0% |
|          hit |      5244170 | 99.9% |
|         miss |         2400 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,400 | 77.8% |
| Failure | 400 | 22.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 160 | 40.0% |
| overriding descriptor | 80 | 20.0% |
| not in dict | 40 | 10.0% |
| property | 40 | 10.0% |
| overridden | 40 | 10.0% |
| not in keys | 20 | 5.0% |
| no dict | 20 | 5.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       832073 | 100.0% |

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
| Basic | 181,057,967 | 46.2% |
| Not specialized | 70,843,427 | 18.1% |
| Specialized | 140,318,884 | 35.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 12,614,018 | 45.4% |
| CALL | 6,615,788 | 23.8% |
| TO_BOOL | 5,671,312 | 20.4% |
| BINARY_OP | 1,658,207 | 6.0% |
| COMPARE_OP | 738,359 | 2.7% |
| SEND | 493,440 | 1.8% |
| FOR_ITER | 12,120 | 0.0% |
| BINARY_SUBSCR | 6,060 | 0.0% |
| STORE_ATTR | 1,980 | 0.0% |
| STORE_SUBSCR | 120 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 2,400 | 42.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,260 | 22.3% |
| LOAD_ATTR_SLOT | 720 | 12.8% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 8.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 240 | 4.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 120 | 2.1% |
| COMPARE_OP_INT | 120 | 2.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 120 | 2.1% |
| TO_BOOL_STR | 60 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 60 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,757,217 | 10.2% |
| Calls to Python functions inlined | 15,430,714 | 89.8% |
| Calls via PyEval_EvalFrame (total) | 1,757,217 | 10.2% |
| Calls via PyEval_EvalFrame (vector) | 1,510,077 | 8.8% |
| Calls via PyEval_EvalFrame (generator) | 247,140 | 1.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,510,077 | 8.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,080 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,760 | 2.9% |
| Frames pushed | 15,712,651 | 91.4% |
| Frame objects created | 482,340 | 2.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,004,974 | 41.3% |
| Frees to freelist | 11,011,233 |  |
| Allocations | 15,652,558 | 58.7% |
| Allocations to 512 bytes | 10,843,793 | 40.7% |
| Allocations to 4 kbytes | 241,020 | 0.9% |
| Allocations over 4 kbytes | 4,567,745 | 17.1% |
| Frees | 15,956,017 |  |
| New values | 780 |  |
| Interpreter increfs | 167,460,848 | 76.0% |
| Interpreter decrefs | 185,958,275 | 75.8% |
| Increfs | 52,748,150 | 24.0% |
| Decrefs | 59,292,706 | 24.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 120 | 15.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,293,242 |  |
| Method cache misses | 27,156 |  |
| Method cache collisions | 27,405 |  |
| Method cache dunder hits | 782,717 |  |
| Method cache dunder misses | 259 |  |


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
