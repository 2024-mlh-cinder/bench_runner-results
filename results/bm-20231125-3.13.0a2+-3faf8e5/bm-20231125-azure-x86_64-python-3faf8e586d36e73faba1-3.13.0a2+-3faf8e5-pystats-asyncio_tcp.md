
# Pystats results

- benchmark: asyncio_tcp
- fork: python
- ref: 3faf8e586d36e73faba13d9b61663afed6a24cb4
- commit hash: 3faf8e5
- commit date: 2023-11-25T15:40:19-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 89,455,189 | 21.3% | 21.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 30,450,209 | 7.3% | 28.6% |  |
| RESUME_CHECK | 21,615,377 | 5.2% | 33.8% | 0.0% |
| STORE_FAST | 19,802,410 | 4.7% | 38.5% |  |
| POP_JUMP_IF_FALSE | 18,260,371 | 4.4% | 42.9% |  |
| CALL_PY_EXACT_ARGS | 16,308,984 | 3.9% | 46.8% |  |
| LOAD_CONST | 14,515,958 | 3.5% | 50.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,304,735 | 3.4% | 53.6% |  |
| TO_BOOL_BOOL | 13,313,471 | 3.2% | 56.8% |  |
| POP_TOP | 12,844,780 | 3.1% | 59.9% |  |
| RETURN_VALUE | 12,549,008 | 3.0% | 62.9% |  |
| LOAD_GLOBAL_MODULE | 8,828,131 | 2.1% | 65.0% |  |
| LOAD_FAST_LOAD_FAST | 8,097,121 | 1.9% | 66.9% |  |
| RETURN_CONST | 7,762,997 | 1.9% | 68.8% |  |
| LOAD_GLOBAL_BUILTIN | 7,717,136 | 1.8% | 70.6% | 0.0% |
| LOAD_ATTR_SLOT | 6,956,418 | 1.7% | 72.3% |  |
| POP_JUMP_IF_TRUE | 6,746,181 | 1.6% | 73.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,303,782 | 1.5% | 75.4% |  |
| STORE_ATTR_SLOT | 5,612,446 | 1.3% | 76.7% |  |
| LOAD_ATTR | 5,591,089 | 1.3% | 78.0% |  |
| NOP | 5,021,554 | 1.2% | 79.2% |  |
| CALL | 4,372,972 | 1.0% | 80.3% |  |
| BINARY_OP | 4,230,286 | 1.0% | 81.3% |  |
| TO_BOOL_INT | 4,217,646 | 1.0% | 82.3% |  |
| COMPARE_OP_INT | 3,711,316 | 0.9% | 83.2% |  |
| LOAD_ATTR_MODULE | 3,421,389 | 0.8% | 84.0% |  |
| PUSH_NULL | 3,088,956 | 0.7% | 84.7% |  |
| CALL_LEN | 2,952,803 | 0.7% | 85.5% |  |
| COPY | 2,701,600 | 0.6% | 86.1% |  |
| INTERPRETER_EXIT | 2,666,423 | 0.6% | 86.7% |  |
| JUMP_FORWARD | 2,613,856 | 0.6% | 87.4% |  |
| TO_BOOL | 2,451,727 | 0.6% | 87.9% |  |
| JUMP_BACKWARD | 2,428,707 | 0.6% | 88.5% |  |
| POP_JUMP_IF_NOT_NONE | 2,334,727 | 0.6% | 89.1% |  |
| POP_JUMP_IF_NONE | 2,295,208 | 0.5% | 89.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 2,268,614 | 0.5% | 90.2% |  |
| FOR_ITER_LIST | 2,030,458 | 0.5% | 90.7% |  |
| GET_ITER | 1,933,294 | 0.5% | 91.1% |  |
| BUILD_LIST | 1,666,667 | 0.4% | 91.5% |  |
| SEND_GEN | 1,636,490 | 0.4% | 91.9% |  |
| TO_BOOL_LIST | 1,595,456 | 0.4% | 92.3% |  |
| STORE_FAST_STORE_FAST | 1,457,253 | 0.3% | 92.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,456,813 | 0.3% | 93.0% |  |
| FOR_ITER_RANGE | 1,353,167 | 0.3% | 93.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,350,471 | 0.3% | 93.6% |  |
| CALL_ISINSTANCE | 1,322,720 | 0.3% | 93.9% |  |
| YIELD_VALUE | 1,307,672 | 0.3% | 94.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 1,307,512 | 0.3% | 94.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,297,718 | 0.3% | 94.9% |  |
| UNARY_NOT | 1,280,160 | 0.3% | 95.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,094,080 | 0.3% | 95.4% | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,087,860 | 0.3% | 95.7% | 0.1% |
| BUILD_TUPLE | 1,039,911 | 0.2% | 95.9% |  |
| CALL_FUNCTION_EX | 1,024,429 | 0.2% | 96.2% |  |
| CALL_INTRINSIC_1 | 1,023,949 | 0.2% | 96.4% |  |
| LIST_EXTEND | 1,023,949 | 0.2% | 96.7% |  |
| END_SEND | 987,034 | 0.2% | 96.9% |  |
| GET_AWAITABLE | 987,034 | 0.2% | 97.2% |  |
| LOAD_DEREF | 727,260 | 0.2% | 97.3% |  |
| CALL_BUILTIN_CLASS | 719,111 | 0.2% | 97.5% |  |
| SWAP | 710,651 | 0.2% | 97.7% |  |
| COPY_FREE_VARS | 691,580 | 0.2% | 97.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 664,378 | 0.2% | 98.0% |  |
| TO_BOOL_NONE | 661,996 | 0.2% | 98.1% |  |
| SEND | 659,236 | 0.2% | 98.3% |  |
| RETURN_GENERATOR | 658,636 | 0.2% | 98.5% |  |
| CALL_PY_WITH_DEFAULTS | 657,500 | 0.2% | 98.6% |  |
| UNARY_INVERT | 648,540 | 0.2% | 98.8% |  |
| LOAD_SUPER_ATTR_METHOD | 642,480 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT | 641,258 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 373,691 | 0.1% | 99.2% |  |
| BINARY_SLICE | 373,631 | 0.1% | 99.3% |  |
| CALL_KW | 346,838 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 336,620 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 336,078 | 0.1% | 99.5% |  |
| CONTAINS_OP | 321,520 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 321,138 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_INT | 320,598 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 320,318 | 0.1% | 99.8% |  |
| BUILD_SLICE | 320,318 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 320,278 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60,813 | 0.0% | 100.0% |  |
| COMPARE_OP | 19,080 | 0.0% | 100.0% |  |
| FOR_ITER | 17,240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 16,940 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 9,620 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 8,100 | 0.0% | 100.0% |  |
| STORE_ATTR | 7,500 | 0.0% | 100.0% |  |
| RESUME | 4,340 | 0.0% | 100.0% | 0.5% |
| MAKE_CELL | 1,440 | 0.0% | 100.0% |  |
| IS_OP | 1,360 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 940 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 900 | 0.0% | 100.0% |  |
| STORE_DEREF | 880 | 0.0% | 100.0% |  |
| BUILD_MAP | 800 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 680 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 680 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 680 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 660 | 0.0% | 100.0% |  |
| POP_EXCEPT | 660 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 660 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 560 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 560 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 500 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 440 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 440 | 0.0% | 100.0% |  |
| BUILD_SET | 400 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 380 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 380 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 240 | 0.0% | 100.0% | 25.0% |
| DICT_MERGE | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 200 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 200 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |  |
| IMPORT_NAME | 100 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 80 | 0.0% | 100.0% |  |
| LIST_APPEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 80 | 0.0% | 100.0% |  |
| RERAISE | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 40 | 0.0% | 100.0% |  |
| IMPORT_FROM | 20 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 20 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 20 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 29,451,489 | 7.0% | 7.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 14,994,088 | 3.6% | 10.6% |
| RESUME_CHECK LOAD_FAST | 13,593,298 | 3.2% | 13.9% |
| STORE_FAST LOAD_FAST | 12,019,098 | 2.9% | 16.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 9,892,639 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 9,057,246 | 2.2% | 21.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 7,681,445 | 1.8% | 23.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 7,397,743 | 1.8% | 24.8% |
| LOAD_FAST LOAD_ATTR_SLOT | 6,947,538 | 1.7% | 26.5% |
| RETURN_CONST POP_TOP | 6,388,810 | 1.5% | 28.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 6,284,214 | 1.5% | 29.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 5,903,751 | 1.4% | 30.9% |
| LOAD_CONST LOAD_FAST | 5,883,884 | 1.4% | 32.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,633,396 | 1.3% | 33.7% |
| POP_TOP LOAD_FAST | 5,334,212 | 1.3% | 35.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,292,152 | 1.3% | 36.2% |
| LOAD_FAST RETURN_VALUE | 4,593,552 | 1.1% | 37.3% |
| LOAD_FAST LOAD_ATTR | 4,517,200 | 1.1% | 38.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,027,034 | 1.0% | 39.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 3,963,554 | 0.9% | 40.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,776,462 | 0.9% | 41.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 3,776,338 | 0.9% | 42.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,711,056 | 0.9% | 43.0% |
| NOP LOAD_FAST | 3,707,314 | 0.9% | 43.9% |
| LOAD_CONST STORE_FAST | 3,646,859 | 0.9% | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 3,613,696 | 0.9% | 45.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,419,369 | 0.8% | 46.4% |
| RETURN_VALUE STORE_FAST | 3,303,294 | 0.8% | 47.2% |
| LOAD_FAST LOAD_CONST | 3,279,712 | 0.8% | 48.0% |
| RETURN_VALUE TO_BOOL_BOOL | 3,259,418 | 0.8% | 48.8% |
| LOAD_FAST STORE_ATTR_SLOT | 2,977,274 | 0.7% | 49.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,976,205 | 0.7% | 50.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,874,777 | 0.7% | 50.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,779,609 | 0.7% | 51.5% |
| POP_TOP RETURN_CONST | 2,721,296 | 0.6% | 52.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,666,311 | 0.6% | 52.8% |
| CACHE RESUME_CHECK | 2,663,823 | 0.6% | 53.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 2,634,712 | 0.6% | 54.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 2,563,792 | 0.6% | 54.7% |
| TO_BOOL POP_JUMP_IF_TRUE | 2,426,407 | 0.6% | 55.3% |
| RESUME_CHECK NOP | 2,354,129 | 0.6% | 55.8% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,310,314 | 0.6% | 56.4% |
| STORE_FAST JUMP_FORWARD | 2,292,396 | 0.5% | 56.9% |
| LOAD_CONST COMPARE_OP_INT | 2,283,994 | 0.5% | 57.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,263,414 | 0.5% | 58.0% |
| COPY TO_BOOL_INT | 2,060,020 | 0.5% | 58.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,059,640 | 0.5% | 59.0% |
| CALL STORE_FAST | 2,026,887 | 0.5% | 59.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,014,067 | 0.5% | 60.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,013,009 | 0.5% | 60.5% |
| POP_TOP LOAD_CONST | 2,002,805 | 0.5% | 60.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,975,694 | 0.5% | 61.4% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,972,090 | 0.5% | 61.9% |
| JUMP_FORWARD LOAD_FAST | 1,971,918 | 0.5% | 62.3% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,962,838 | 0.5% | 62.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,894,097 | 0.5% | 63.3% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,839,264 | 0.4% | 63.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,732,122 | 0.4% | 64.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,682,789 | 0.4% | 64.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,675,087 | 0.4% | 64.9% |
| STORE_ATTR_SLOT LOAD_CONST | 1,645,756 | 0.4% | 65.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,642,338 | 0.4% | 65.7% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,595,336 | 0.4% | 66.1% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,595,216 | 0.4% | 66.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,456,693 | 0.3% | 66.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,456,453 | 0.3% | 67.2% |
| BINARY_OP COPY | 1,419,022 | 0.3% | 67.5% |
| LOAD_ATTR LOAD_FAST | 1,370,171 | 0.3% | 67.8% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,369,227 | 0.3% | 68.2% |
| LOAD_FAST TO_BOOL | 1,366,845 | 0.3% | 68.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,366,473 | 0.3% | 68.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,361,209 | 0.3% | 69.1% |
| POP_JUMP_IF_FALSE POP_TOP | 1,358,231 | 0.3% | 69.5% |
| STORE_FAST RETURN_CONST | 1,345,067 | 0.3% | 69.8% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,342,809 | 0.3% | 70.1% |
| CALL RETURN_VALUE | 1,336,149 | 0.3% | 70.4% |
| CALL_LEN STORE_FAST | 1,335,429 | 0.3% | 70.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,322,460 | 0.3% | 71.0% |
| RETURN_VALUE RETURN_VALUE | 1,314,940 | 0.3% | 71.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,314,140 | 0.3% | 71.7% |
| LOAD_FAST STORE_FAST | 1,313,460 | 0.3% | 72.0% |
| POP_JUMP_IF_TRUE LOAD_CONST | 1,313,418 | 0.3% | 72.3% |
| NOP LOAD_GLOBAL_MODULE | 1,313,400 | 0.3% | 72.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,308,914 | 0.3% | 72.9% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 1,307,032 | 0.3% | 73.2% |
| RETURN_VALUE INTERPRETER_EXIT | 1,300,756 | 0.3% | 73.6% |
| STORE_FAST NOP | 1,299,078 | 0.3% | 73.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 1,298,918 | 0.3% | 74.2% |
| LOAD_FAST GET_ITER | 1,283,456 | 0.3% | 74.5% |
| GET_ITER FOR_ITER_LIST | 1,283,076 | 0.3% | 74.8% |
| TO_BOOL_BOOL UNARY_NOT | 1,280,020 | 0.3% | 75.1% |
| PUSH_NULL LOAD_FAST | 1,119,900 | 0.3% | 75.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,094,000 | 0.3% | 75.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 1,076,722 | 0.3% | 75.9% |
| BINARY_OP TO_BOOL_INT | 1,066,982 | 0.3% | 76.1% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,048,187 | 0.3% | 76.4% |
| BINARY_OP STORE_FAST | 1,038,051 | 0.2% | 76.6% |
| RETURN_CONST INTERPRETER_EXIT | 1,036,309 | 0.2% | 76.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 1,032,129 | 0.2% | 77.1% |
| LOAD_ATTR PUSH_NULL | 1,025,309 | 0.2% | 77.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,318 | 85.7% |
| LOAD_CONST | 53,313 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 320,358 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 44,893 | 12.0% |
| STORE_FAST | 7,900 | 2.1% |
| LIST_EXTEND | 240 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 200 | 0.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,663,823 | 99.9% |
| COPY_FREE_VARS | 1,000 | 0.0% |
| RESUME | 660 | 0.0% |
| POP_TOP | 400 | 0.0% |
| RETURN_GENERATOR | 320 | 0.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 80 | 100.0% |


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
| LOAD_FAST | 120 | 60.0% |
| RETURN_VALUE | 40 | 20.0% |
| LOAD_CONST | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 60 | 33.3% |
| PUSH_EXC_INFO | 40 | 22.2% |
| STORE_FAST | 20 | 11.1% |
| UNPACK_SEQUENCE | 20 | 11.1% |
| BINARY_SUBSCR_GETITEM | 20 | 11.1% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 460 | 69.7% |
| BUILD_TUPLE | 160 | 24.2% |
| LOAD_GLOBAL | 40 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 660 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 320,318 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,318 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 336,878 | 34.1% |
| SEND | 328,798 | 33.3% |
| RETURN_VALUE | 321,358 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 665,836 | 67.5% |
| STORE_FAST | 320,798 | 32.5% |
| UNPACK_SEQUENCE | 120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 440 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,283,456 | 66.4% |
| CALL_BUILTIN_CLASS | 641,438 | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,040 | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 160 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,283,076 | 66.4% |
| FOR_ITER_RANGE | 641,378 | 33.2% |
| FOR_ITER | 8,680 | 0.4% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |
| FOR_ITER_TUPLE | 80 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,300,756 | 48.8% |
| RETURN_CONST | 1,036,309 | 38.9% |
| YIELD_VALUE | 328,958 | 12.3% |
| RETURN_GENERATOR | 400 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 560 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,354,129 | 46.9% |
| STORE_FAST | 1,299,078 | 25.9% |
| POP_JUMP_IF_FALSE | 694,511 | 13.8% |
| POP_JUMP_IF_TRUE | 328,458 | 6.5% |
| STORE_ATTR_INSTANCE_VALUE | 320,298 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,707,314 | 73.8% |
| LOAD_GLOBAL_MODULE | 1,313,400 | 26.2% |
| LOAD_GLOBAL_BUILTIN | 320 | 0.0% |
| LOAD_GLOBAL | 280 | 0.0% |
| LOAD_DEREF | 160 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480 | 72.7% |
| SWAP | 100 | 15.2% |
| COPY | 80 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 320 | 48.5% |
| RETURN_VALUE | 100 | 15.2% |
| POP_TOP | 80 | 12.1% |
| LOAD_CONST | 80 | 12.1% |
| RERAISE | 80 | 12.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,388,810 | 49.7% |
| POP_JUMP_IF_FALSE | 1,358,231 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,094,000 | 8.5% |
| CALL_FUNCTION_EX | 1,023,869 | 8.0% |
| END_SEND | 665,836 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,334,212 | 41.5% |
| RETURN_CONST | 2,721,296 | 21.2% |
| LOAD_CONST | 2,002,805 | 15.6% |
| JUMP_BACKWARD | 773,082 | 6.0% |
| LOAD_GLOBAL_MODULE | 702,331 | 5.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 380 | 57.6% |
| RERAISE | 80 | 12.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 12.1% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 9.1% |
| BINARY_SUBSCR | 40 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 520 | 78.8% |
| LOAD_GLOBAL | 140 | 21.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,014,067 | 65.2% |
| LOAD_ATTR | 1,025,309 | 33.2% |
| LOAD_DEREF | 47,480 | 1.5% |
| LOAD_FAST | 2,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,119,900 | 36.3% |
| LOAD_FAST_LOAD_FAST | 995,538 | 32.2% |
| CALL | 972,718 | 31.5% |
| LOAD_CONST | 480 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 657,176 | 99.8% |
| CALL_KW | 400 | 0.1% |
| CACHE | 320 | 0.0% |
| CALL | 300 | 0.0% |
| MAKE_CELL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 657,836 | 99.9% |
| INTERPRETER_EXIT | 400 | 0.1% |
| STORE_FAST | 160 | 0.0% |
| CALL | 120 | 0.0% |
| LIST_APPEND | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,593,552 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,613,696 | 28.8% |
| CALL | 1,336,149 | 10.6% |
| RETURN_VALUE | 1,314,940 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 656,800 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,303,294 | 26.3% |
| TO_BOOL_BOOL | 3,259,418 | 26.0% |
| RETURN_VALUE | 1,314,940 | 10.5% |
| INTERPRETER_EXIT | 1,300,756 | 10.4% |
| LOAD_FAST | 1,015,049 | 8.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 140 | 28.0% |
| LOAD_CONST | 120 | 24.0% |
| LOAD_ATTR | 100 | 20.0% |
| LOAD_FAST | 100 | 20.0% |
| STORE_SUBSCR | 40 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 36.0% |
| STORE_SUBSCR_DICT | 140 | 28.0% |
| LOAD_FAST | 60 | 12.0% |
| STORE_SUBSCR | 40 | 8.0% |
| LOAD_CONST | 40 | 8.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,366,845 | 55.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,076,722 | 43.9% |
| TO_BOOL | 2,840 | 0.1% |
| LOAD_ATTR | 2,000 | 0.1% |
| RETURN_VALUE | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,426,407 | 99.0% |
| POP_JUMP_IF_FALSE | 19,380 | 0.8% |
| TO_BOOL | 2,840 | 0.1% |
| TO_BOOL_BOOL | 2,300 | 0.1% |
| TO_BOOL_INT | 400 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 328,180 | 50.6% |
| BINARY_OP | 320,320 | 49.4% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 648,540 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,280,020 | 100.0% |
| TO_BOOL | 80 | 0.0% |
| TO_BOOL_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 640,080 | 50.0% |
| RETURN_VALUE | 640,000 | 50.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,059,640 | 48.7% |
| LOAD_ATTR_MODULE | 754,622 | 17.8% |
| UNARY_INVERT | 648,540 | 15.3% |
| POP_JUMP_IF_FALSE | 381,133 | 9.0% |
| LOAD_ATTR | 373,531 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,419,022 | 33.5% |
| TO_BOOL_INT | 1,066,982 | 25.2% |
| STORE_FAST | 1,038,051 | 24.5% |
| BUILD_TUPLE | 373,391 | 8.8% |
| UNARY_INVERT | 320,320 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 703,609 | 42.2% |
| STORE_FAST | 641,438 | 38.5% |
| LOAD_FAST_LOAD_FAST | 320,080 | 19.2% |
| LOAD_FAST | 640 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,024,269 | 61.5% |
| STORE_FAST | 641,918 | 38.5% |
| RETURN_VALUE | 240 | 0.0% |
| STORE_DEREF | 160 | 0.0% |
| SWAP | 80 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 240 | 30.0% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 17.5% |
| POP_TOP | 80 | 10.0% |
| LOAD_FAST | 80 | 10.0% |
| POP_JUMP_IF_NOT_NONE | 80 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560 | 70.0% |
| STORE_FAST | 240 | 30.0% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 360 | 90.0% |
| LOAD_ATTR | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 400 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,318 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 320,318 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 373,391 | 35.9% |
| LOAD_CONST | 328,140 | 31.6% |
| LOAD_FAST | 321,040 | 30.9% |
| LOAD_FAST_LOAD_FAST | 8,700 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 8,160 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 373,351 | 35.9% |
| CALL_PY_EXACT_ARGS | 335,960 | 32.3% |
| CALL | 320,600 | 30.8% |
| CALL_ISINSTANCE | 8,000 | 0.8% |
| LOAD_CONST | 560 | 0.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 972,718 | 22.2% |
| LOAD_FAST_LOAD_FAST | 667,238 | 15.3% |
| LOAD_CONST | 658,398 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 649,616 | 14.9% |
| LOAD_ATTR | 324,420 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,026,887 | 46.4% |
| RETURN_VALUE | 1,336,149 | 30.6% |
| POP_TOP | 331,438 | 7.6% |
| RESUME_CHECK | 330,500 | 7.6% |
| LOAD_CONST | 320,438 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,023,949 | 100.0% |
| DICT_MERGE | 240 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,023,869 | 99.9% |
| RESUME_CHECK | 220 | 0.0% |
| GET_AWAITABLE | 160 | 0.0% |
| COPY_FREE_VARS | 80 | 0.0% |
| MAKE_CELL | 80 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,023,949 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,023,949 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 346,838 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 328,878 | 94.8% |
| COPY_FREE_VARS | 15,800 | 4.6% |
| STORE_FAST | 800 | 0.2% |
| RETURN_GENERATOR | 400 | 0.1% |
| RESUME_CHECK | 340 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 16,040 | 84.1% |
| LOAD_CONST | 1,020 | 5.3% |
| LOAD_ATTR_MODULE | 940 | 4.9% |
| COMPARE_OP | 540 | 2.8% |
| CALL_BUILTIN_CLASS | 140 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,760 | 93.1% |
| COMPARE_OP | 540 | 2.8% |
| COMPARE_OP_INT | 520 | 2.7% |
| POP_JUMP_IF_TRUE | 140 | 0.7% |
| COMPARE_OP_STR | 60 | 0.3% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 320,360 | 99.6% |
| BUILD_SET | 400 | 0.1% |
| LOAD_FAST | 240 | 0.1% |
| LOAD_GLOBAL_MODULE | 220 | 0.1% |
| LOAD_ATTR_SLOT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 321,280 | 99.9% |
| POP_JUMP_IF_TRUE | 240 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,419,022 | 52.5% |
| CALL_LEN | 641,258 | 23.7% |
| UNARY_NOT | 640,080 | 23.7% |
| LOAD_FAST | 480 | 0.0% |
| CALL_BUILTIN_FAST | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,060,020 | 76.3% |
| TO_BOOL_BOOL | 640,280 | 23.7% |
| TO_BOOL | 480 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.0% |
| LOAD_ATTR | 200 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 657,720 | 95.1% |
| CALL_KW | 15,800 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 15,780 | 2.3% |
| CACHE | 1,000 | 0.1% |
| LOAD_ATTR_PROPERTY | 580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 690,820 | 99.9% |
| RESUME | 600 | 0.1% |
| RETURN_GENERATOR | 80 | 0.0% |
| MAKE_CELL | 80 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 240 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,680 | 50.3% |
| JUMP_BACKWARD | 8,260 | 47.9% |
| FOR_ITER | 280 | 1.6% |
| SWAP | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,300 | 48.1% |
| RETURN_CONST | 8,140 | 47.2% |
| FOR_ITER | 280 | 1.6% |
| FOR_ITER_LIST | 240 | 1.4% |
| LOAD_FAST | 100 | 0.6% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 657,836 | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE | 320,298 | 32.5% |
| LOAD_FAST | 8,240 | 0.8% |
| RETURN_VALUE | 240 | 0.0% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 987,034 | 100.0% |


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
| LOAD_FAST | 720 | 52.9% |
| LOAD_CONST | 560 | 41.2% |
| LOAD_FAST_LOAD_FAST | 80 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 800 | 58.8% |
| RETURN_VALUE | 400 | 29.4% |
| LOAD_DEREF | 160 | 11.8% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 773,082 | 31.8% |
| POP_JUMP_IF_FALSE | 641,418 | 26.4% |
| CALL_LIST_APPEND | 373,491 | 15.4% |
| POP_JUMP_IF_TRUE | 320,398 | 13.2% |
| STORE_FAST | 320,238 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 961,556 | 39.6% |
| FOR_ITER_LIST | 747,082 | 30.8% |
| FOR_ITER_RANGE | 711,729 | 29.3% |
| FOR_ITER | 8,260 | 0.3% |
| FOR_ITER_TUPLE | 80 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,307,032 | 100.0% |
| RESUME | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 978,374 | 74.8% |
| SEND | 329,138 | 25.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,292,396 | 87.7% |
| POP_TOP | 320,840 | 12.3% |
| STORE_ATTR | 180 | 0.0% |
| CALL_LIST_APPEND | 140 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,971,918 | 75.4% |
| LOAD_GLOBAL_BUILTIN | 641,478 | 24.5% |
| LOAD_GLOBAL | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| NOP | 80 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 80 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 703,609 | 68.7% |
| LOAD_FAST | 320,080 | 31.3% |
| BINARY_SLICE | 240 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,023,949 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,517,200 | 80.8% |
| LOAD_ATTR_SLOT | 1,024,049 | 18.3% |
| LOAD_FAST_LOAD_FAST | 32,220 | 0.6% |
| LOAD_ATTR | 9,960 | 0.2% |
| LOAD_GLOBAL_MODULE | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,370,171 | 24.5% |
| PUSH_NULL | 1,025,309 | 18.3% |
| SWAP | 709,511 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 382,411 | 6.8% |
| BINARY_OP | 373,531 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,279,712 | 22.6% |
| POP_JUMP_IF_FALSE | 2,310,314 | 15.9% |
| POP_TOP | 2,002,805 | 13.8% |
| STORE_ATTR_SLOT | 1,645,756 | 11.3% |
| POP_JUMP_IF_TRUE | 1,313,418 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,883,884 | 40.5% |
| STORE_FAST | 3,646,859 | 25.1% |
| COMPARE_OP_INT | 2,283,994 | 15.7% |
| CALL | 658,398 | 4.5% |
| SEND_GEN | 657,656 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 643,160 | 88.4% |
| LOAD_ATTR | 31,640 | 4.4% |
| STORE_FAST | 16,280 | 2.2% |
| RESUME_CHECK | 16,100 | 2.2% |
| CALL_LEN | 15,780 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 659,660 | 90.7% |
| PUSH_NULL | 47,480 | 6.5% |
| COMPARE_OP_INT | 15,800 | 2.2% |
| LOAD_ATTR | 760 | 0.1% |
| LOAD_CONST | 560 | 0.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,593,298 | 15.2% |
| STORE_FAST | 12,019,098 | 13.4% |
| POP_JUMP_IF_FALSE | 9,892,639 | 11.1% |
| LOAD_CONST | 5,883,884 | 6.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,633,396 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 29,451,489 | 32.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,397,743 | 8.3% |
| LOAD_ATTR_SLOT | 6,947,538 | 7.8% |
| CALL_PY_EXACT_ARGS | 6,284,214 | 7.0% |
| RETURN_VALUE | 4,593,552 | 5.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 80 | 100.0% |


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
| STORE_ATTR_SLOT | 1,975,694 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,732,122 | 21.4% |
| PUSH_NULL | 995,538 | 12.3% |
| LOAD_FAST_LOAD_FAST | 652,638 | 8.1% |
| LOAD_GLOBAL_MODULE | 641,860 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 2,634,712 | 32.5% |
| LOAD_FAST | 1,682,789 | 20.8% |
| CALL | 667,238 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 656,760 | 8.1% |
| LOAD_FAST_LOAD_FAST | 652,638 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,420 | 14.8% |
| POP_TOP | 940 | 9.8% |
| RESUME | 920 | 9.6% |
| RESUME_CHECK | 900 | 9.4% |
| STORE_FAST | 840 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,080 | 32.0% |
| LOAD_ATTR | 1,900 | 19.8% |
| LOAD_GLOBAL_BUILTIN | 1,660 | 17.3% |
| LOAD_FAST | 800 | 8.3% |
| LOAD_DEREF | 520 | 5.4% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 400 | 44.4% |
| LOAD_FAST | 200 | 22.2% |
| CALL | 140 | 15.6% |
| LOAD_FAST_LOAD_FAST | 80 | 8.9% |
| LOAD_GLOBAL | 40 | 4.4% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 880 | 61.1% |
| CACHE | 240 | 16.7% |
| CALL_KW | 160 | 11.1% |
| CALL_FUNCTION_EX | 80 | 5.6% |
| COPY_FREE_VARS | 80 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 880 | 61.1% |
| RESUME_CHECK | 260 | 18.1% |
| RETURN_GENERATOR | 240 | 16.7% |
| RESUME | 60 | 4.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 9,057,246 | 49.6% |
| COMPARE_OP_INT | 3,711,056 | 20.3% |
| TO_BOOL_INT | 2,874,777 | 15.7% |
| TO_BOOL_LIST | 1,595,336 | 8.7% |
| TO_BOOL_NONE | 661,996 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,892,639 | 54.2% |
| LOAD_CONST | 2,310,314 | 12.7% |
| RETURN_CONST | 1,369,227 | 7.5% |
| POP_TOP | 1,358,231 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 961,378 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,308,914 | 57.0% |
| LOAD_ATTR_INSTANCE_VALUE | 985,534 | 42.9% |
| LOAD_ATTR | 440 | 0.0% |
| CALL | 160 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,972,090 | 85.9% |
| LOAD_CONST | 320,478 | 14.0% |
| RETURN_CONST | 1,280 | 0.1% |
| LOAD_FAST_LOAD_FAST | 400 | 0.0% |
| LOAD_GLOBAL | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,013,009 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 321,198 | 13.8% |
| LOAD_GLOBAL_MODULE | 220 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,361,209 | 58.3% |
| LOAD_FAST_LOAD_FAST | 330,238 | 14.1% |
| LOAD_GLOBAL_MODULE | 329,740 | 14.1% |
| LOAD_CONST | 312,180 | 13.4% |
| LOAD_GLOBAL | 400 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,976,205 | 44.1% |
| TO_BOOL | 2,426,407 | 36.0% |
| TO_BOOL_INT | 1,342,809 | 19.9% |
| COMPARE_OP_INT | 260 | 0.0% |
| CONTAINS_OP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,776,338 | 56.0% |
| LOAD_CONST | 1,313,418 | 19.5% |
| STORE_FAST | 641,278 | 9.5% |
| NOP | 328,458 | 4.9% |
| JUMP_BACKWARD | 320,398 | 4.7% |


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
| POP_TOP | 2,721,296 | 35.1% |
| POP_JUMP_IF_FALSE | 1,369,227 | 17.6% |
| STORE_FAST | 1,345,067 | 17.3% |
| STORE_ATTR_SLOT | 987,518 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 641,858 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,388,810 | 82.3% |
| INTERPRETER_EXIT | 1,036,309 | 13.3% |
| END_SEND | 336,878 | 4.3% |
| EXIT_INIT_CHECK | 440 | 0.0% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 329,378 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 329,138 | 49.9% |
| SEND | 720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 328,798 | 49.9% |
| YIELD_VALUE | 328,798 | 49.9% |
| SEND | 720 | 0.1% |
| POP_TOP | 460 | 0.1% |
| SEND_GEN | 460 | 0.1% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 85.7% |
| LOAD_FAST_LOAD_FAST | 80 | 14.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,980 | 66.4% |
| LOAD_FAST_LOAD_FAST | 1,540 | 20.5% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 3.7% |
| STORE_ATTR | 260 | 3.5% |
| LOAD_DEREF | 200 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,660 | 35.5% |
| LOAD_FAST | 1,200 | 16.0% |
| LOAD_CONST | 1,140 | 15.2% |
| RETURN_CONST | 780 | 10.4% |
| STORE_ATTR_SLOT | 460 | 6.1% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 36.4% |
| BUILD_LIST | 160 | 18.2% |
| CALL_KW | 160 | 18.2% |
| BINARY_OP_ADD_INT | 120 | 13.6% |
| CALL | 80 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 54.5% |
| LOAD_CONST | 160 | 18.2% |
| BUILD_LIST | 80 | 9.1% |
| LOAD_DEREF | 80 | 9.1% |
| LOAD_FAST_LOAD_FAST | 80 | 9.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,646,859 | 18.4% |
| RETURN_VALUE | 3,303,294 | 16.7% |
| CALL | 2,026,887 | 10.2% |
| CALL_LEN | 1,335,429 | 6.7% |
| LOAD_FAST | 1,313,460 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,019,098 | 60.7% |
| JUMP_FORWARD | 2,292,396 | 11.6% |
| RETURN_CONST | 1,345,067 | 6.8% |
| NOP | 1,299,078 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 709,351 | 3.6% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,456,693 | 100.0% |
| UNPACK_SEQUENCE | 260 | 0.0% |
| POP_TOP | 80 | 0.0% |
| COPY | 80 | 0.0% |
| STORE_FAST_STORE_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,456,453 | 99.9% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


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
| LOAD_ATTR | 709,511 | 99.8% |
| BINARY_OP_ADD_INT | 260 | 0.0% |
| BUILD_TUPLE | 240 | 0.0% |
| LOAD_FAST_LOAD_FAST | 160 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 709,511 | 99.8% |
| STORE_ATTR_INSTANCE_VALUE | 280 | 0.0% |
| POP_TOP | 240 | 0.0% |
| STORE_ATTR | 200 | 0.0% |
| COPY | 160 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 23.5% |
| END_SEND | 120 | 17.6% |
| RETURN_VALUE | 80 | 11.8% |
| LOAD_FAST | 80 | 11.8% |
| FOR_ITER_LIST | 80 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 280 | 41.2% |
| STORE_FAST_STORE_FAST | 260 | 38.2% |
| UNPACK_SEQUENCE_TUPLE | 60 | 8.8% |
| STORE_FAST | 40 | 5.9% |
| POP_TOP | 20 | 2.9% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 978,714 | 74.8% |
| SEND | 328,798 | 25.1% |
| LOAD_CONST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 978,714 | 74.8% |
| INTERPRETER_EXIT | 328,958 | 25.2% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,060 | 47.5% |
| CACHE | 660 | 15.2% |
| COPY_FREE_VARS | 600 | 13.8% |
| POP_TOP | 480 | 11.1% |
| SEND_GEN | 400 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,220 | 51.2% |
| LOAD_GLOBAL | 920 | 21.2% |
| JUMP_BACKWARD_NO_INTERRUPT | 480 | 11.1% |
| LOAD_CONST | 240 | 5.5% |
| NOP | 180 | 4.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 641,238 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 641,258 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 320,198 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320,218 | 99.9% |
| SWAP | 260 | 0.1% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 320,198 | 100.0% |
| BINARY_OP | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 320,238 | 100.0% |
| COMPARE_OP | 40 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 7,960 | 98.3% |
| LOAD_CONST | 80 | 1.0% |
| BINARY_OP | 60 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,980 | 98.5% |
| SWAP | 120 | 1.5% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,840 | 93.5% |
| LOAD_FAST | 1,040 | 6.1% |
| BINARY_SUBSCR | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,780 | 93.2% |
| RETURN_VALUE | 780 | 4.6% |
| PUSH_EXC_INFO | 380 | 2.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 73.7% |
| LOAD_FAST_LOAD_FAST | 80 | 21.1% |
| BINARY_SUBSCR | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 380 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 160 | 36.4% |
| CALL | 120 | 27.3% |
| LOAD_FAST | 80 | 18.2% |
| PUSH_NULL | 40 | 9.1% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 54.5% |
| COPY_FREE_VARS | 200 | 45.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 320,278 | 95.3% |
| CALL_BUILTIN_CLASS | 15,760 | 4.7% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,298 | 95.3% |
| COPY_FREE_VARS | 15,780 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 657,418 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 60,953 | 8.5% |
| CALL | 280 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 220 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 641,438 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60,793 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 15,760 | 2.2% |
| STORE_FAST | 500 | 0.1% |
| LOAD_FAST | 240 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 460 | 67.6% |
| LOAD_ATTR_SLOT | 120 | 17.6% |
| CALL | 80 | 11.8% |
| LOAD_FAST_LOAD_FAST | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 280 | 41.2% |
| COPY | 220 | 32.4% |
| POP_TOP | 140 | 20.6% |
| TO_BOOL | 40 | 5.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 60,793 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60,813 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 1,314,140 | 99.4% |
| BUILD_TUPLE | 8,000 | 0.6% |
| CALL | 260 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,322,460 | 100.0% |
| TO_BOOL | 260 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,563,792 | 86.8% |
| LOAD_FAST | 388,851 | 13.2% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,335,429 | 45.2% |
| COPY | 641,258 | 21.7% |
| LOAD_CONST | 320,218 | 10.8% |
| BINARY_OP_ADD_INT | 320,198 | 10.8% |
| LOAD_FAST | 319,900 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 373,351 | 99.9% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 373,491 | 99.9% |
| JUMP_FORWARD | 140 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 656,760 | 48.6% |
| LOAD_FAST | 373,351 | 27.6% |
| RETURN_VALUE | 320,280 | 23.7% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 693,671 | 51.4% |
| RETURN_VALUE | 656,800 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 641,238 | 49.4% |
| LOAD_FAST | 336,040 | 25.9% |
| LOAD_ATTR | 320,280 | 24.7% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 656,380 | 50.6% |
| STORE_FAST | 641,258 | 49.4% |
| RETURN_VALUE | 80 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 757,682 | 69.6% |
| LOAD_ATTR | 329,038 | 30.2% |
| CALL | 740 | 0.1% |
| LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 756,722 | 69.6% |
| TO_BOOL_BOOL | 328,998 | 30.2% |
| POP_TOP | 620 | 0.1% |
| LOAD_FAST | 460 | 0.0% |
| TO_BOOL | 320 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,048,187 | 95.8% |
| BINARY_SLICE | 44,893 | 4.1% |
| CALL | 740 | 0.1% |
| LOAD_CONST | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,094,000 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |
| LOAD_CONST | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 7,681,445 | 47.1% |
| LOAD_FAST | 6,284,214 | 38.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,032,129 | 6.3% |
| BUILD_TUPLE | 335,960 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 328,140 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,994,088 | 91.9% |
| COPY_FREE_VARS | 657,720 | 4.0% |
| RETURN_GENERATOR | 657,176 | 4.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 656,520 | 99.9% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 0.1% |
| LOAD_CONST | 240 | 0.0% |
| CALL | 220 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 657,380 | 100.0% |
| RETURN_GENERATOR | 120 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920 | 97.9% |
| CALL | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 76.6% |
| LOAD_GLOBAL_MODULE | 200 | 21.3% |
| LOAD_GLOBAL | 20 | 2.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,283,994 | 61.5% |
| LOAD_GLOBAL_MODULE | 641,238 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 320,238 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 319,880 | 8.6% |
| LOAD_ATTR_SLOT | 60,753 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,711,056 | 100.0% |
| POP_JUMP_IF_TRUE | 260 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 140 | 70.0% |
| COMPARE_OP | 60 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 80 | 40.0% |
| COPY | 60 | 30.0% |
| STORE_FAST | 60 | 30.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,283,076 | 63.2% |
| JUMP_BACKWARD | 747,082 | 36.8% |
| FOR_ITER | 240 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 746,702 | 36.8% |
| RETURN_CONST | 641,458 | 31.6% |
| LOAD_FAST | 641,258 | 31.6% |
| STORE_FAST | 660 | 0.0% |
| LOAD_DEREF | 140 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 711,729 | 52.6% |
| GET_ITER | 641,378 | 47.4% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 711,809 | 52.6% |
| LOAD_CONST | 641,278 | 47.4% |
| LOAD_FAST | 80 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 44.4% |
| JUMP_BACKWARD | 80 | 44.4% |
| FOR_ITER | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 44.4% |
| LOAD_GLOBAL | 40 | 22.2% |
| LOAD_GLOBAL_MODULE | 40 | 22.2% |
| LOAD_FAST | 20 | 11.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 94.7% |
| LOAD_ATTR | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,451,489 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 656,640 | 2.2% |
| LOAD_FAST_LOAD_FAST | 336,920 | 1.1% |
| LOAD_ATTR | 4,360 | 0.0% |
| LOAD_DEREF | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,903,751 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 4,027,034 | 13.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,963,554 | 13.0% |
| RETURN_VALUE | 3,613,696 | 11.9% |
| CALL_LEN | 2,563,792 | 8.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,027,034 | 63.9% |
| LOAD_FAST | 1,894,097 | 30.0% |
| LOAD_ATTR | 382,411 | 6.1% |
| LOAD_ATTR_SLOT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,779,609 | 44.1% |
| LOAD_FAST_LOAD_FAST | 1,732,122 | 27.5% |
| CALL_PY_EXACT_ARGS | 1,032,129 | 16.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 757,682 | 12.0% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,397,743 | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,963,554 | 27.7% |
| LOAD_ATTR_SLOT | 1,962,838 | 13.7% |
| RETURN_VALUE | 656,720 | 4.6% |
| LOAD_FAST_LOAD_FAST | 320,280 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,681,445 | 53.7% |
| LOAD_FAST | 5,633,396 | 39.4% |
| LOAD_FAST_LOAD_FAST | 346,718 | 2.4% |
| LOAD_CONST | 320,558 | 2.2% |
| LOAD_GLOBAL_MODULE | 320,478 | 2.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,419,369 | 99.9% |
| LOAD_ATTR | 1,900 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,014,067 | 58.9% |
| BINARY_OP | 754,622 | 22.1% |
| UNARY_INVERT | 328,180 | 9.6% |
| LOAD_FAST | 320,420 | 9.4% |
| COMPARE_OP | 940 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 664,258 | 100.0% |
| LOAD_ATTR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 336,140 | 50.6% |
| CALL | 320,298 | 48.2% |
| BINARY_OP | 7,940 | 1.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,758 | 99.9% |
| LOAD_ATTR | 220 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,558 | 99.8% |
| COPY_FREE_VARS | 580 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,947,538 | 99.9% |
| LOAD_FAST_LOAD_FAST | 7,960 | 0.1% |
| LOAD_ATTR | 840 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,962,838 | 28.2% |
| TO_BOOL_BOOL | 1,839,264 | 26.4% |
| LOAD_ATTR | 1,024,049 | 14.7% |
| BUILD_LIST | 703,609 | 10.1% |
| LIST_EXTEND | 703,609 | 10.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,666,311 | 34.6% |
| LOAD_FAST | 1,642,338 | 21.3% |
| POP_JUMP_IF_FALSE | 961,378 | 12.5% |
| STORE_FAST | 702,531 | 9.1% |
| JUMP_FORWARD | 641,478 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,292,152 | 68.6% |
| CALL_ISINSTANCE | 1,314,140 | 17.0% |
| LOAD_DEREF | 643,160 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 457,944 | 5.9% |
| BUILD_TUPLE | 8,160 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,776,462 | 42.8% |
| RESUME_CHECK | 1,675,087 | 19.0% |
| NOP | 1,313,400 | 14.9% |
| POP_TOP | 702,331 | 8.0% |
| POP_JUMP_IF_NOT_NONE | 329,740 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,419,369 | 38.7% |
| BINARY_OP | 2,059,640 | 23.3% |
| LOAD_FAST | 1,366,473 | 15.5% |
| LOAD_FAST_LOAD_FAST | 641,860 | 7.3% |
| COMPARE_OP_INT | 641,238 | 7.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 94.1% |
| LOAD_SUPER_ATTR | 40 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 640 | 94.1% |
| LOAD_GLOBAL | 40 | 5.9% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 642,080 | 99.9% |
| LOAD_SUPER_ATTR | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 321,320 | 50.0% |
| LOAD_FAST_LOAD_FAST | 320,720 | 49.9% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |
| CALL | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 14,994,088 | 69.4% |
| CACHE | 2,663,823 | 12.3% |
| SEND_GEN | 978,314 | 4.5% |
| COPY_FREE_VARS | 690,820 | 3.2% |
| POP_TOP | 658,156 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,593,298 | 62.9% |
| LOAD_GLOBAL_BUILTIN | 2,666,311 | 12.3% |
| NOP | 2,354,129 | 10.9% |
| LOAD_GLOBAL_MODULE | 1,675,087 | 7.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,307,032 | 6.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 978,374 | 59.8% |
| LOAD_CONST | 657,656 | 40.2% |
| SEND | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 978,314 | 59.8% |
| POP_TOP | 657,776 | 40.2% |
| RESUME | 400 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,263,414 | 99.8% |
| STORE_ATTR | 2,660 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,900 | 0.1% |
| LOAD_DEREF | 360 | 0.0% |
| SWAP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,298,918 | 57.3% |
| RETURN_CONST | 641,858 | 28.3% |
| NOP | 320,298 | 14.1% |
| LOAD_CONST | 4,160 | 0.2% |
| LOAD_FAST_LOAD_FAST | 780 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,977,274 | 53.0% |
| LOAD_FAST_LOAD_FAST | 2,634,712 | 46.9% |
| STORE_ATTR | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,975,694 | 35.2% |
| LOAD_CONST | 1,645,756 | 29.3% |
| LOAD_FAST | 987,518 | 17.6% |
| RETURN_CONST | 987,518 | 17.6% |
| NOP | 15,960 | 0.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 336,040 | 99.8% |
| LOAD_CONST | 280 | 0.1% |
| LOAD_FAST | 160 | 0.0% |
| STORE_SUBSCR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 336,140 | 99.9% |
| NOP | 140 | 0.0% |
| LOAD_CONST | 140 | 0.0% |
| RETURN_CONST | 140 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,903,751 | 44.3% |
| RETURN_VALUE | 3,259,418 | 24.5% |
| LOAD_ATTR_SLOT | 1,839,264 | 13.8% |
| CALL_ISINSTANCE | 1,322,460 | 9.9% |
| COPY | 640,280 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,057,246 | 68.0% |
| POP_JUMP_IF_TRUE | 2,976,205 | 22.4% |
| UNARY_NOT | 1,280,020 | 9.6% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,060,020 | 48.8% |
| BINARY_OP | 1,066,982 | 25.3% |
| LOAD_FAST | 709,173 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 381,031 | 9.0% |
| TO_BOOL | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,874,777 | 68.2% |
| POP_JUMP_IF_TRUE | 1,342,809 | 31.8% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,595,216 | 100.0% |
| TO_BOOL | 160 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,595,336 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 660,556 | 99.8% |
| LOAD_FAST | 920 | 0.1% |
| LOAD_ATTR | 360 | 0.1% |
| TO_BOOL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 661,996 | 100.0% |


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
| POP_TOP | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
| STORE_FAST_STORE_FAST | 60 | 33.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 746,702 | 51.3% |
| STORE_FAST | 709,351 | 48.7% |
| UNPACK_SEQUENCE | 280 | 0.0% |
| BINARY_SLICE | 200 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,456,693 | 100.0% |
| LOAD_FAST | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |


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
|     deferred | 4,225,966 | 76.5% |
|          hit | 1,290,294 | 23.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 6.0% |
| Failure | 4,060 | 94.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,900 | 71.4% |
| or | 1,100 | 27.1% |
| floor divide | 40 | 1.0% |
| multiply different types | 20 | 0.5% |


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
|     deferred | 100 | 0.6% |
|          hit | 17,400 | 98.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,360,112 | 13.5% |
|          hit | 27,898,247 | 86.4% |
|         miss | 1,960 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,240 | 48.5% |
| Failure | 6,620 | 51.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 1,140 | 17.2% |
| cfunc noargs | 880 | 13.3% |
| code complex parameters | 800 | 12.1% |
| meth descr method fastcall keywords | 780 | 11.8% |
| no dict | 720 | 10.9% |
| meth descr varargs | 700 | 10.6% |
| cfunc varargs keywords | 460 | 6.9% |
| class mutable | 460 | 6.9% |
| other | 380 | 5.7% |
| cfunc varargs | 100 | 1.5% |
| operator wrapper | 100 | 1.5% |
| wrong number arguments | 40 | 0.6% |
| cmethod | 40 | 0.6% |
| init not simple | 20 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 17,960 | 0.5% |
|          hit | 3,711,516 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 580 | 51.8% |
| Failure | 540 | 48.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 220 | 40.7% |
| tuple | 160 | 29.6% |
| different types | 120 | 22.2% |
| bool | 40 | 7.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 16,640 | 0.5% |
|          hit | 3,383,805 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 53.3% |
| Failure | 280 | 46.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 160 | 57.1% |
| dict items | 80 | 28.6% |
| set | 40 | 14.3% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,571,089 | 8.2% |
|          hit | 62,422,429 | 91.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,060 | 60.3% |
| Failure | 7,940 | 39.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 3,620 | 45.6% |
| method | 1,560 | 19.6% |
| has managed dict | 1,500 | 18.9% |
| shadowed | 720 | 9.1% |
| metaclass attribute | 180 | 2.3% |
| class method obj | 160 | 2.0% |
| non object slot | 80 | 1.0% |
| class attr descriptor | 60 | 0.8% |
| class attr simple | 40 | 0.5% |
| builtin class method | 20 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,960 | 0.0% |
|        deopt | 80 | 0.0% |
|          hit | 16,545,187 | 99.9% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,740 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 460 | 0.1% |
|          hit | 643,160 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 100.0% |
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
|     deferred | 658,056 | 28.7% |
|          hit | 1,636,490 | 71.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 460 | 39.0% |
| Failure | 720 | 61.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 720 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,120 | 0.1% |
|          hit | 7,881,060 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,120 | 92.3% |
| Failure | 260 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 120 | 46.2% |
| overridden | 80 | 30.8% |
| overriding descriptor | 40 | 15.4% |
| no dict | 20 | 7.7% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 320 | 0.1% |
|          hit | 336,620 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 77.8% |
| Failure | 40 | 22.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 40 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,445,867 | 11.0% |
|          hit | 19,788,569 | 89.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,020 | 51.5% |
| Failure | 2,840 | 48.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 920 | 32.4% |
| sequence | 920 | 32.4% |
| mapping | 280 | 9.9% |
| bytearray | 260 | 9.2% |
| dict | 180 | 6.3% |
| memory view | 140 | 4.9% |
| set | 100 | 3.5% |
| float | 20 | 0.7% |
| tuple | 20 | 0.7% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 340 | 0.0% |
|          hit | 1,456,993 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 203,346,704 | 48.5% |
| Not specialized | 47,371,148 | 11.3% |
| Specialized hits | 168,291,049 | 40.2% |
| Specialized misses | 2,060 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 5,571,089 | 32.2% |
| CALL | 4,360,112 | 25.2% |
| BINARY_OP | 4,225,966 | 24.4% |
| TO_BOOL | 2,445,867 | 14.1% |
| SEND | 658,056 | 3.8% |
| COMPARE_OP | 17,960 | 0.1% |
| FOR_ITER | 16,640 | 0.1% |
| LOAD_GLOBAL | 4,960 | 0.0% |
| STORE_ATTR | 4,120 | 0.0% |
| LOAD_SUPER_ATTR | 460 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,420 | 68.3% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 23.1% |
| LOAD_GLOBAL_BUILTIN | 80 | 3.8% |
| CALL_BUILTIN_O | 60 | 2.9% |
| RESUME | 20 | 1.0% |
| RESUME_CHECK | 20 | 1.0% |
| CACHE | 0 | 0.0% |
| BEFORE_ASYNC_WITH | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,666,443 | 12.0% |
| Calls to Python functions inlined | 19,611,910 | 88.0% |
| Calls via PyEval_EvalFrame (total) | 2,666,443 | 12.0% |
| Calls via PyEval_EvalFrame (vector) | 2,337,085 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 329,358 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,337,085 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 180 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 400 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,400 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 659,436 | 3.0% |
| Frame objects created | 1,060 | 0.0% |
| Frames pushed | 17,624,960 | 79.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 9,610,932 | 43.1% |
| Frees to freelist | 9,627,712 |  |
| Allocations | 12,701,563 | 56.9% |
| Allocations to 512 bytes | 12,059,847 | 54.0% |
| Allocations to 4 kbytes | 480 | 0.0% |
| Allocations over 4 kbytes | 641,236 | 2.9% |
| Frees | 13,167,123 |  |
| New values | 700 |  |
| Interpreter increfs | 173,450,714 | 84.3% |
| Interpreter decrefs | 189,400,910 | 83.8% |
| Increfs | 32,320,797 | 15.7% |
| Decrefs | 36,732,568 | 16.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 6,249,615 |  |
| Method cache misses | 7,850 |  |
| Method cache collisions | 7,120 |  |
| Method cache dunder hits | 1,695,309 |  |
| Method cache dunder misses | 920 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 40 | 1,980 | 160,280 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
Stats gathered on: 2023-11-26
