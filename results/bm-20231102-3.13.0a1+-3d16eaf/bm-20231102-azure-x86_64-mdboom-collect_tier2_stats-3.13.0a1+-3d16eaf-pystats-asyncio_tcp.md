
# Pystats results

- benchmark: asyncio_tcp
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 88,121,730 | 21.3% | 21.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 30,302,920 | 7.3% | 28.7% |  |
| RESUME_CHECK | 21,537,925 | 5.2% | 33.9% |  |
| STORE_FAST | 19,670,117 | 4.8% | 38.7% |  |
| POP_JUMP_IF_FALSE | 18,128,268 | 4.4% | 43.1% |  |
| CALL_PY_EXACT_ARGS | 15,270,754 | 3.7% | 46.8% |  |
| LOAD_CONST | 14,515,840 | 3.5% | 50.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,328,736 | 3.2% | 53.5% |  |
| TO_BOOL_BOOL | 13,173,862 | 3.2% | 56.7% |  |
| POP_TOP | 12,844,698 | 3.1% | 59.8% |  |
| RETURN_VALUE | 12,548,990 | 3.0% | 62.8% |  |
| LOAD_GLOBAL_MODULE | 8,508,217 | 2.1% | 64.9% |  |
| LOAD_FAST_LOAD_FAST | 8,097,020 | 2.0% | 66.9% |  |
| RETURN_CONST | 7,762,919 | 1.9% | 68.7% |  |
| LOAD_GLOBAL_BUILTIN | 7,686,679 | 1.9% | 70.6% | 0.0% |
| LOAD_ATTR_SLOT | 6,831,902 | 1.7% | 72.3% |  |
| POP_JUMP_IF_TRUE | 6,738,586 | 1.6% | 73.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,179,266 | 1.5% | 75.4% |  |
| STORE_ATTR_SLOT | 5,612,429 | 1.4% | 76.8% |  |
| LOAD_ATTR | 5,591,150 | 1.4% | 78.1% |  |
| NOP | 4,959,373 | 1.2% | 79.3% |  |
| CALL | 4,372,923 | 1.1% | 80.4% |  |
| BINARY_OP | 4,230,288 | 1.0% | 81.4% |  |
| TO_BOOL_INT | 4,217,654 | 1.0% | 82.4% |  |
| COMPARE_OP_INT | 3,711,309 | 0.9% | 83.3% |  |
| LOAD_ATTR_MODULE | 3,421,390 | 0.8% | 84.1% |  |
| PUSH_NULL | 3,088,945 | 0.7% | 84.9% |  |
| CALL_LEN | 2,952,803 | 0.7% | 85.6% |  |
| COPY | 2,701,600 | 0.7% | 86.3% |  |
| INTERPRETER_EXIT | 2,666,422 | 0.6% | 86.9% |  |
| JUMP_FORWARD | 2,613,852 | 0.6% | 87.5% |  |
| TO_BOOL | 2,451,725 | 0.6% | 88.1% |  |
| ENTER_EXECUTOR | 2,417,631 | 0.6% | 88.7% |  |
| POP_JUMP_IF_NOT_NONE | 2,334,725 | 0.6% | 89.3% |  |
| POP_JUMP_IF_NONE | 2,287,517 | 0.6% | 89.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 2,268,555 | 0.5% | 90.4% |  |
| GET_ITER | 1,933,294 | 0.5% | 90.9% |  |
| BUILD_LIST | 1,666,669 | 0.4% | 91.3% |  |
| SEND_GEN | 1,636,485 | 0.4% | 91.7% |  |
| TO_BOOL_LIST | 1,595,457 | 0.4% | 92.0% |  |
| STORE_FAST_STORE_FAST | 1,457,016 | 0.4% | 92.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,456,576 | 0.4% | 92.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,350,352 | 0.3% | 93.1% |  |
| CALL_ISINSTANCE | 1,315,116 | 0.3% | 93.4% |  |
| YIELD_VALUE | 1,307,668 | 0.3% | 93.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 1,307,508 | 0.3% | 94.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,297,716 | 0.3% | 94.3% |  |
| FOR_ITER_LIST | 1,284,636 | 0.3% | 94.7% |  |
| UNARY_NOT | 1,280,164 | 0.3% | 95.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,094,085 | 0.3% | 95.2% | 0.0% |
| BUILD_TUPLE | 1,032,311 | 0.3% | 95.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,025,633 | 0.2% | 95.7% | 0.1% |
| CALL_FUNCTION_EX | 1,024,431 | 0.2% | 96.0% |  |
| CALL_INTRINSIC_1 | 1,023,951 | 0.2% | 96.2% |  |
| LIST_EXTEND | 1,023,951 | 0.2% | 96.5% |  |
| END_SEND | 987,031 | 0.2% | 96.7% |  |
| GET_AWAITABLE | 987,031 | 0.2% | 97.0% |  |
| LOAD_DEREF | 727,162 | 0.2% | 97.1% |  |
| CALL_BUILTIN_CLASS | 719,110 | 0.2% | 97.3% |  |
| SWAP | 710,650 | 0.2% | 97.5% |  |
| COPY_FREE_VARS | 691,490 | 0.2% | 97.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 664,372 | 0.2% | 97.8% |  |
| TO_BOOL_NONE | 661,994 | 0.2% | 98.0% |  |
| SEND | 659,234 | 0.2% | 98.1% |  |
| RETURN_GENERATOR | 658,634 | 0.2% | 98.3% |  |
| CALL_PY_WITH_DEFAULTS | 657,498 | 0.2% | 98.4% |  |
| UNARY_INVERT | 648,540 | 0.2% | 98.6% |  |
| LOAD_SUPER_ATTR_METHOD | 642,422 | 0.2% | 98.8% |  |
| FOR_ITER_RANGE | 642,178 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT | 641,258 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 373,693 | 0.1% | 99.2% |  |
| BINARY_SLICE | 373,633 | 0.1% | 99.2% |  |
| CALL_KW | 346,833 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 336,617 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 336,073 | 0.1% | 99.5% |  |
| CONTAINS_OP | 321,441 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 321,137 | 0.1% | 99.6% |  |
| BINARY_OP_ADD_INT | 320,597 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 320,317 | 0.1% | 99.8% |  |
| BUILD_SLICE | 320,317 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 320,277 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60,816 | 0.0% | 100.0% |  |
| COMPARE_OP | 19,076 | 0.0% | 100.0% |  |
| FOR_ITER | 17,240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 16,936 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 11,222 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 9,580 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 8,100 | 0.0% | 100.0% |  |
| STORE_ATTR | 7,460 | 0.0% | 100.0% |  |
| RESUME | 4,320 | 0.0% | 100.0% |  |
| MAKE_CELL | 1,440 | 0.0% | 100.0% |  |
| IS_OP | 1,360 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 940 | 0.0% | 100.0% |  |
| STORE_DEREF | 880 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 860 | 0.0% | 100.0% |  |
| BUILD_MAP | 720 | 0.0% | 100.0% |  |
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
| UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 160 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 29,304,265 | 7.1% | 7.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 14,275,839 | 3.5% | 10.6% |
| RESUME_CHECK LOAD_FAST | 13,585,689 | 3.3% | 13.8% |
| STORE_FAST LOAD_FAST | 11,886,906 | 2.9% | 16.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 9,760,679 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 8,925,231 | 2.2% | 21.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 7,040,573 | 1.7% | 23.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 6,823,142 | 1.7% | 24.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,429,355 | 1.6% | 26.2% |
| RETURN_CONST POP_TOP | 6,388,733 | 1.5% | 27.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 6,268,971 | 1.5% | 29.2% |
| LOAD_CONST LOAD_FAST | 5,883,874 | 1.4% | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 5,833,972 | 1.4% | 32.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,618,193 | 1.4% | 33.4% |
| POP_TOP LOAD_FAST | 5,334,126 | 1.3% | 34.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,284,552 | 1.3% | 36.0% |
| LOAD_FAST RETURN_VALUE | 4,593,536 | 1.1% | 37.1% |
| LOAD_FAST LOAD_ATTR | 4,517,067 | 1.1% | 38.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,964,800 | 1.0% | 39.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 3,955,948 | 1.0% | 40.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,776,465 | 0.9% | 41.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 3,768,743 | 0.9% | 42.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,711,049 | 0.9% | 42.9% |
| LOAD_CONST STORE_FAST | 3,646,767 | 0.9% | 43.7% |
| NOP LOAD_FAST | 3,645,137 | 0.9% | 44.6% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 3,613,693 | 0.9% | 45.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,419,370 | 0.8% | 46.3% |
| RETURN_VALUE STORE_FAST | 3,303,282 | 0.8% | 47.1% |
| LOAD_FAST LOAD_CONST | 3,279,700 | 0.8% | 47.9% |
| RETURN_VALUE TO_BOOL_BOOL | 3,259,420 | 0.8% | 48.7% |
| LOAD_FAST STORE_ATTR_SLOT | 2,977,265 | 0.7% | 49.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,968,607 | 0.7% | 50.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,874,784 | 0.7% | 50.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,779,490 | 0.7% | 51.5% |
| POP_TOP RETURN_CONST | 2,721,300 | 0.7% | 52.2% |
| CACHE RESUME_CHECK | 2,663,822 | 0.6% | 52.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,658,712 | 0.6% | 53.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 2,634,704 | 0.6% | 54.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 2,563,792 | 0.6% | 54.7% |
| TO_BOOL POP_JUMP_IF_TRUE | 2,426,409 | 0.6% | 55.3% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,310,227 | 0.6% | 55.9% |
| STORE_FAST JUMP_FORWARD | 2,292,391 | 0.6% | 56.4% |
| RESUME_CHECK NOP | 2,291,951 | 0.6% | 57.0% |
| LOAD_CONST COMPARE_OP_INT | 2,283,987 | 0.6% | 57.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,263,375 | 0.5% | 58.1% |
| COPY TO_BOOL_INT | 2,060,018 | 0.5% | 58.6% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,059,638 | 0.5% | 59.1% |
| CALL STORE_FAST | 2,026,880 | 0.5% | 59.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,014,066 | 0.5% | 60.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,013,008 | 0.5% | 60.6% |
| POP_TOP LOAD_CONST | 2,002,802 | 0.5% | 61.0% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,975,688 | 0.5% | 61.5% |
| JUMP_FORWARD LOAD_FAST | 1,971,914 | 0.5% | 62.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,964,480 | 0.5% | 62.5% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,962,834 | 0.5% | 62.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,831,815 | 0.4% | 63.4% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,777,039 | 0.4% | 63.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,732,123 | 0.4% | 64.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,682,789 | 0.4% | 64.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,675,089 | 0.4% | 65.1% |
| STORE_ATTR_SLOT LOAD_CONST | 1,645,751 | 0.4% | 65.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,634,733 | 0.4% | 65.8% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,595,337 | 0.4% | 66.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,595,217 | 0.4% | 66.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,456,456 | 0.4% | 67.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,456,216 | 0.4% | 67.3% |
| BINARY_OP COPY | 1,419,020 | 0.3% | 67.7% |
| LOAD_ATTR LOAD_FAST | 1,370,168 | 0.3% | 68.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,369,222 | 0.3% | 68.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,366,472 | 0.3% | 68.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,361,208 | 0.3% | 69.0% |
| LOAD_FAST TO_BOOL | 1,359,118 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE POP_TOP | 1,358,230 | 0.3% | 69.7% |
| STORE_FAST RETURN_CONST | 1,345,068 | 0.3% | 70.0% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,342,810 | 0.3% | 70.3% |
| CALL RETURN_VALUE | 1,336,152 | 0.3% | 70.6% |
| CALL_LEN STORE_FAST | 1,335,434 | 0.3% | 71.0% |
| RETURN_VALUE RETURN_VALUE | 1,314,936 | 0.3% | 71.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,314,856 | 0.3% | 71.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,314,136 | 0.3% | 71.9% |
| LOAD_FAST STORE_FAST | 1,313,456 | 0.3% | 72.2% |
| POP_JUMP_IF_TRUE LOAD_CONST | 1,313,418 | 0.3% | 72.5% |
| NOP LOAD_GLOBAL_MODULE | 1,313,396 | 0.3% | 72.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,308,828 | 0.3% | 73.2% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 1,307,028 | 0.3% | 73.5% |
| RETURN_VALUE INTERPRETER_EXIT | 1,300,756 | 0.3% | 73.8% |
| STORE_FAST NOP | 1,299,076 | 0.3% | 74.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 1,298,920 | 0.3% | 74.4% |
| LOAD_FAST GET_ITER | 1,283,456 | 0.3% | 74.8% |
| GET_ITER FOR_ITER_LIST | 1,283,076 | 0.3% | 75.1% |
| TO_BOOL_BOOL UNARY_NOT | 1,280,024 | 0.3% | 75.4% |
| PUSH_NULL LOAD_FAST | 1,119,895 | 0.3% | 75.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,094,005 | 0.3% | 75.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 1,076,727 | 0.3% | 76.2% |
| BINARY_OP TO_BOOL_INT | 1,066,987 | 0.3% | 76.4% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,048,187 | 0.3% | 76.7% |
| BINARY_OP STORE_FAST | 1,038,049 | 0.3% | 76.9% |
| RETURN_CONST INTERPRETER_EXIT | 1,036,309 | 0.3% | 77.2% |
| LOAD_ATTR PUSH_NULL | 1,025,311 | 0.2% | 77.4% |
| BUILD_LIST LOAD_FAST | 1,024,271 | 0.2% | 77.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,317 | 85.7% |
| LOAD_CONST | 53,316 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 320,357 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 44,898 | 12.0% |
| STORE_FAST | 7,898 | 2.1% |
| LIST_EXTEND | 240 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 200 | 0.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,663,822 | 99.9% |
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
| BUILD_SLICE | 320,317 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,317 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 336,877 | 34.1% |
| SEND | 328,797 | 33.3% |
| RETURN_VALUE | 321,357 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 665,834 | 67.5% |
| STORE_FAST | 320,797 | 32.5% |
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
| YIELD_VALUE | 328,957 | 12.3% |
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
| RESUME_CHECK | 2,291,951 | 46.2% |
| STORE_FAST | 1,299,076 | 26.2% |
| POP_JUMP_IF_FALSE | 694,514 | 14.0% |
| POP_JUMP_IF_TRUE | 328,455 | 6.6% |
| STORE_ATTR_INSTANCE_VALUE | 320,297 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,645,137 | 73.5% |
| LOAD_GLOBAL_MODULE | 1,313,396 | 26.5% |
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
| RETURN_CONST | 6,388,733 | 49.7% |
| POP_JUMP_IF_FALSE | 1,358,230 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,094,005 | 8.5% |
| CALL_FUNCTION_EX | 1,023,871 | 8.0% |
| END_SEND | 665,834 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,334,126 | 41.5% |
| RETURN_CONST | 2,721,300 | 21.2% |
| LOAD_CONST | 2,002,802 | 15.6% |
| ENTER_EXECUTOR | 763,606 | 5.9% |
| LOAD_GLOBAL_MODULE | 702,332 | 5.5% |


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
| LOAD_ATTR_MODULE | 2,014,066 | 65.2% |
| LOAD_ATTR | 1,025,311 | 33.2% |
| LOAD_DEREF | 47,468 | 1.5% |
| LOAD_FAST | 2,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,119,895 | 36.3% |
| LOAD_FAST_LOAD_FAST | 995,533 | 32.2% |
| CALL | 972,717 | 31.5% |
| LOAD_CONST | 480 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 337,257 | 51.2% |
| ENTER_EXECUTOR | 319,917 | 48.6% |
| CALL_KW | 400 | 0.1% |
| CACHE | 320 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 657,834 | 99.9% |
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
| LOAD_FAST | 4,593,536 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,613,693 | 28.8% |
| CALL | 1,336,152 | 10.6% |
| RETURN_VALUE | 1,314,936 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 656,798 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,303,282 | 26.3% |
| TO_BOOL_BOOL | 3,259,420 | 26.0% |
| RETURN_VALUE | 1,314,936 | 10.5% |
| INTERPRETER_EXIT | 1,300,756 | 10.4% |
| LOAD_FAST | 1,015,051 | 8.1% |


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
| LOAD_FAST | 1,359,118 | 55.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,076,727 | 43.9% |
| ENTER_EXECUTOR | 7,720 | 0.3% |
| TO_BOOL | 2,840 | 0.1% |
| LOAD_ATTR | 2,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,426,409 | 99.0% |
| POP_JUMP_IF_FALSE | 19,376 | 0.8% |
| TO_BOOL | 2,840 | 0.1% |
| TO_BOOL_BOOL | 2,300 | 0.1% |
| TO_BOOL_INT | 400 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 328,179 | 50.6% |
| BINARY_OP | 320,321 | 49.4% |
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
| TO_BOOL_BOOL | 1,280,024 | 100.0% |
| TO_BOOL | 80 | 0.0% |
| TO_BOOL_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 640,082 | 50.0% |
| RETURN_VALUE | 640,002 | 50.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 978,711 | 74.8% |
| SEND | 328,797 | 25.1% |
| LOAD_CONST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 978,711 | 74.8% |
| INTERPRETER_EXIT | 328,957 | 25.2% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,059,638 | 48.7% |
| LOAD_ATTR_MODULE | 754,624 | 17.8% |
| UNARY_INVERT | 648,540 | 15.3% |
| POP_JUMP_IF_FALSE | 381,135 | 9.0% |
| LOAD_ATTR | 373,533 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,419,020 | 33.5% |
| TO_BOOL_INT | 1,066,987 | 25.2% |
| STORE_FAST | 1,038,049 | 24.5% |
| BUILD_TUPLE | 373,393 | 8.8% |
| UNARY_INVERT | 320,321 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 703,610 | 42.2% |
| STORE_FAST | 641,438 | 38.5% |
| LOAD_FAST_LOAD_FAST | 320,081 | 19.2% |
| LOAD_FAST | 640 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,024,271 | 61.5% |
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
| BUILD_TUPLE | 240 | 33.3% |
| POP_TOP | 80 | 11.1% |
| LOAD_FAST | 80 | 11.1% |
| POP_JUMP_IF_NOT_NONE | 80 | 11.1% |
| STORE_FAST | 80 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 66.7% |
| STORE_FAST | 240 | 33.3% |


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
| LOAD_FAST | 320,317 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 320,317 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 373,393 | 36.2% |
| LOAD_CONST | 328,139 | 31.8% |
| LOAD_FAST | 321,041 | 31.1% |
| LOAD_FAST_LOAD_FAST | 8,698 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 373,353 | 36.2% |
| CALL_PY_EXACT_ARGS | 335,957 | 32.5% |
| CALL | 320,601 | 31.1% |
| LOAD_CONST | 560 | 0.1% |
| RETURN_VALUE | 400 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 972,717 | 22.2% |
| LOAD_FAST_LOAD_FAST | 667,234 | 15.3% |
| LOAD_CONST | 658,396 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 649,612 | 14.9% |
| LOAD_ATTR | 324,421 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,026,880 | 46.4% |
| RETURN_VALUE | 1,336,152 | 30.6% |
| POP_TOP | 331,437 | 7.6% |
| RESUME_CHECK | 330,499 | 7.6% |
| LOAD_CONST | 320,437 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,023,951 | 100.0% |
| DICT_MERGE | 240 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,023,871 | 99.9% |
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
| LIST_EXTEND | 1,023,951 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,023,951 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 346,833 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 328,877 | 94.8% |
| COPY_FREE_VARS | 15,796 | 4.6% |
| STORE_FAST | 800 | 0.2% |
| RETURN_GENERATOR | 400 | 0.1% |
| RESUME_CHECK | 340 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 16,036 | 84.1% |
| LOAD_CONST | 1,020 | 5.3% |
| LOAD_ATTR_MODULE | 940 | 4.9% |
| COMPARE_OP | 540 | 2.8% |
| CALL_BUILTIN_CLASS | 140 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,756 | 93.1% |
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
| LOAD_ATTR_INSTANCE_VALUE | 320,301 | 99.6% |
| BUILD_SET | 400 | 0.1% |
| LOAD_FAST | 240 | 0.1% |
| LOAD_GLOBAL_MODULE | 220 | 0.1% |
| LOAD_ATTR_SLOT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 321,201 | 99.9% |
| POP_JUMP_IF_TRUE | 240 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,419,020 | 52.5% |
| CALL_LEN | 641,258 | 23.7% |
| UNARY_NOT | 640,082 | 23.7% |
| LOAD_FAST | 480 | 0.0% |
| CALL_BUILTIN_FAST | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,060,018 | 76.3% |
| TO_BOOL_BOOL | 640,282 | 23.7% |
| TO_BOOL | 480 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.0% |
| LOAD_ATTR | 200 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 657,658 | 95.1% |
| CALL_KW | 15,796 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 15,776 | 2.3% |
| CACHE | 1,000 | 0.1% |
| LOAD_ATTR_PROPERTY | 580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 690,750 | 99.9% |
| RESUME | 580 | 0.1% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 763,606 | 31.6% |
| POP_JUMP_IF_FALSE | 640,878 | 26.5% |
| CALL_LIST_APPEND | 373,053 | 15.4% |
| POP_JUMP_IF_TRUE | 320,057 | 13.2% |
| STORE_FAST | 319,897 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 641,078 | 26.5% |
| RESUME_CHECK | 640,878 | 26.5% |
| LOAD_FAST | 373,053 | 15.4% |
| RETURN_CONST | 372,633 | 15.4% |
| RETURN_GENERATOR | 319,917 | 13.2% |


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
| RETURN_GENERATOR | 657,834 | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE | 320,297 | 32.5% |
| LOAD_FAST | 8,240 | 0.8% |
| RETURN_VALUE | 240 | 0.0% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 987,031 | 100.0% |


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
| POP_TOP | 9,480 | 84.5% |
| POP_JUMP_IF_FALSE | 482 | 4.3% |
| CALL_LIST_APPEND | 440 | 3.9% |
| POP_JUMP_IF_TRUE | 340 | 3.0% |
| STORE_FAST | 340 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 8,260 | 73.6% |
| FOR_ITER_LIST | 1,260 | 11.2% |
| LOAD_FAST | 762 | 6.8% |
| FOR_ITER_RANGE | 740 | 6.6% |
| ENTER_EXECUTOR | 140 | 1.2% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,307,028 | 100.0% |
| RESUME | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 978,371 | 74.8% |
| SEND | 329,137 | 25.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,292,391 | 87.7% |
| POP_TOP | 320,841 | 12.3% |
| STORE_ATTR | 180 | 0.0% |
| CALL_LIST_APPEND | 140 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,971,914 | 75.4% |
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
| LOAD_ATTR_SLOT | 703,610 | 68.7% |
| LOAD_FAST | 320,081 | 31.3% |
| BINARY_SLICE | 240 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,023,951 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,517,067 | 80.8% |
| LOAD_ATTR_SLOT | 961,879 | 17.2% |
| ENTER_EXECUTOR | 62,292 | 1.1% |
| LOAD_FAST_LOAD_FAST | 32,172 | 0.6% |
| LOAD_ATTR | 10,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,370,168 | 24.5% |
| PUSH_NULL | 1,025,311 | 18.3% |
| SWAP | 709,510 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 382,411 | 6.8% |
| BINARY_OP | 373,533 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,279,700 | 22.6% |
| POP_JUMP_IF_FALSE | 2,310,227 | 15.9% |
| POP_TOP | 2,002,802 | 13.8% |
| STORE_ATTR_SLOT | 1,645,751 | 11.3% |
| POP_JUMP_IF_TRUE | 1,313,418 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,883,874 | 40.5% |
| STORE_FAST | 3,646,767 | 25.1% |
| COMPARE_OP_INT | 2,283,987 | 15.7% |
| CALL | 658,396 | 4.5% |
| SEND_GEN | 657,654 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 643,102 | 88.4% |
| LOAD_ATTR | 31,632 | 4.4% |
| STORE_FAST | 16,276 | 2.2% |
| RESUME_CHECK | 16,096 | 2.2% |
| CALL_LEN | 15,776 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 659,578 | 90.7% |
| PUSH_NULL | 47,468 | 6.5% |
| COMPARE_OP_INT | 15,796 | 2.2% |
| LOAD_ATTR | 760 | 0.1% |
| LOAD_CONST | 560 | 0.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,585,689 | 15.4% |
| STORE_FAST | 11,886,906 | 13.5% |
| POP_JUMP_IF_FALSE | 9,760,679 | 11.1% |
| LOAD_CONST | 5,883,874 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,618,193 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 29,304,265 | 33.3% |
| LOAD_ATTR_SLOT | 6,823,142 | 7.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,429,355 | 7.3% |
| CALL_PY_EXACT_ARGS | 6,268,971 | 7.1% |
| RETURN_VALUE | 4,593,536 | 5.2% |


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
| STORE_ATTR_SLOT | 1,975,688 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,732,123 | 21.4% |
| PUSH_NULL | 995,533 | 12.3% |
| LOAD_FAST_LOAD_FAST | 652,638 | 8.1% |
| LOAD_GLOBAL_MODULE | 641,862 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 2,634,704 | 32.5% |
| LOAD_FAST | 1,682,789 | 20.8% |
| CALL | 667,234 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 656,758 | 8.1% |
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
| STORE_FAST | 800 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,080 | 32.2% |
| LOAD_ATTR | 1,900 | 19.8% |
| LOAD_GLOBAL_BUILTIN | 1,640 | 17.1% |
| LOAD_FAST | 800 | 8.4% |
| LOAD_DEREF | 500 | 5.2% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 380 | 44.2% |
| LOAD_FAST | 180 | 20.9% |
| CALL | 140 | 16.3% |
| LOAD_FAST_LOAD_FAST | 80 | 9.3% |
| LOAD_GLOBAL | 40 | 4.7% |


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
| TO_BOOL_BOOL | 8,925,231 | 49.2% |
| COMPARE_OP_INT | 3,711,049 | 20.5% |
| TO_BOOL_INT | 2,874,784 | 15.9% |
| TO_BOOL_LIST | 1,595,337 | 8.8% |
| TO_BOOL_NONE | 661,994 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,760,679 | 53.8% |
| LOAD_CONST | 2,310,227 | 12.7% |
| RETURN_CONST | 1,369,222 | 7.6% |
| POP_TOP | 1,358,230 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 961,379 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,308,828 | 57.2% |
| LOAD_ATTR_INSTANCE_VALUE | 977,929 | 42.8% |
| LOAD_ATTR | 440 | 0.0% |
| CALL | 160 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,964,480 | 85.9% |
| LOAD_CONST | 320,477 | 14.0% |
| RETURN_CONST | 1,200 | 0.1% |
| LOAD_FAST_LOAD_FAST | 400 | 0.0% |
| LOAD_GLOBAL | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,013,008 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 321,197 | 13.8% |
| LOAD_GLOBAL_MODULE | 220 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,361,208 | 58.3% |
| LOAD_FAST_LOAD_FAST | 330,237 | 14.1% |
| LOAD_GLOBAL_MODULE | 329,739 | 14.1% |
| LOAD_CONST | 312,181 | 13.4% |
| LOAD_GLOBAL | 400 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,968,607 | 44.1% |
| TO_BOOL | 2,426,409 | 36.0% |
| TO_BOOL_INT | 1,342,810 | 19.9% |
| COMPARE_OP_INT | 260 | 0.0% |
| CONTAINS_OP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,768,743 | 55.9% |
| LOAD_CONST | 1,313,418 | 19.5% |
| STORE_FAST | 641,278 | 9.5% |
| NOP | 328,455 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 320,297 | 4.8% |


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
| POP_TOP | 2,721,300 | 35.1% |
| POP_JUMP_IF_FALSE | 1,369,222 | 17.6% |
| STORE_FAST | 1,345,068 | 17.3% |
| STORE_ATTR_SLOT | 987,515 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 641,858 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,388,733 | 82.3% |
| INTERPRETER_EXIT | 1,036,309 | 13.3% |
| END_SEND | 336,877 | 4.3% |
| EXIT_INIT_CHECK | 440 | 0.0% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 329,377 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 329,137 | 49.9% |
| SEND | 720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 328,797 | 49.9% |
| YIELD_VALUE | 328,797 | 49.9% |
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
| LOAD_FAST | 4,940 | 66.2% |
| LOAD_FAST_LOAD_FAST | 1,540 | 20.6% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 3.8% |
| STORE_ATTR | 260 | 3.5% |
| LOAD_DEREF | 200 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,640 | 35.4% |
| LOAD_FAST | 1,200 | 16.1% |
| LOAD_CONST | 1,140 | 15.3% |
| RETURN_CONST | 780 | 10.5% |
| STORE_ATTR_SLOT | 460 | 6.2% |


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
| LOAD_CONST | 3,646,767 | 18.5% |
| RETURN_VALUE | 3,303,282 | 16.8% |
| CALL | 2,026,880 | 10.3% |
| CALL_LEN | 1,335,434 | 6.8% |
| LOAD_FAST | 1,313,456 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,886,906 | 60.4% |
| JUMP_FORWARD | 2,292,391 | 11.7% |
| RETURN_CONST | 1,345,068 | 6.8% |
| NOP | 1,299,076 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 709,350 | 3.6% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,456,456 | 100.0% |
| UNPACK_SEQUENCE | 260 | 0.0% |
| POP_TOP | 80 | 0.0% |
| COPY | 80 | 0.0% |
| STORE_FAST_STORE_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,456,216 | 99.9% |
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
| LOAD_ATTR | 709,510 | 99.8% |
| BINARY_OP_ADD_INT | 260 | 0.0% |
| BUILD_TUPLE | 240 | 0.0% |
| LOAD_FAST_LOAD_FAST | 160 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 709,510 | 99.8% |
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

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,060 | 47.7% |
| CACHE | 660 | 15.3% |
| COPY_FREE_VARS | 580 | 13.4% |
| POP_TOP | 480 | 11.1% |
| SEND_GEN | 400 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,220 | 51.4% |
| LOAD_GLOBAL | 920 | 21.3% |
| JUMP_BACKWARD_NO_INTERRUPT | 480 | 11.1% |
| LOAD_CONST | 240 | 5.6% |
| NOP | 180 | 4.2% |


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
| CALL_LEN | 320,197 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320,217 | 99.9% |
| SWAP | 260 | 0.1% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 320,197 | 100.0% |
| BINARY_OP | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 320,237 | 100.0% |
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
| RETURN_VALUE | 15,836 | 93.5% |
| LOAD_FAST | 1,040 | 6.1% |
| BINARY_SUBSCR | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,776 | 93.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 320,277 | 95.3% |
| CALL_BUILTIN_CLASS | 15,756 | 4.7% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,297 | 95.3% |
| COPY_FREE_VARS | 15,776 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 657,414 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 60,956 | 8.5% |
| CALL | 280 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 220 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 641,438 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60,796 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 15,756 | 2.2% |
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
| CALL_BUILTIN_CLASS | 60,796 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60,816 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 1,314,136 | 99.9% |
| BUILD_TUPLE | 400 | 0.0% |
| CALL | 260 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,314,856 | 100.0% |
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
| STORE_FAST | 1,335,434 | 45.2% |
| COPY | 641,258 | 21.7% |
| LOAD_CONST | 320,217 | 10.8% |
| BINARY_OP_ADD_INT | 320,197 | 10.8% |
| LOAD_FAST | 319,901 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 373,353 | 99.9% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 373,053 | 99.8% |
| JUMP_BACKWARD | 440 | 0.1% |
| JUMP_FORWARD | 140 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 656,758 | 48.6% |
| LOAD_FAST | 373,233 | 27.6% |
| RETURN_VALUE | 320,281 | 23.7% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 693,554 | 51.4% |
| RETURN_VALUE | 656,798 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 641,238 | 49.4% |
| LOAD_FAST | 336,037 | 25.9% |
| LOAD_ATTR | 320,281 | 24.7% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 656,378 | 50.6% |
| STORE_FAST | 641,258 | 49.4% |
| RETURN_VALUE | 80 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 695,456 | 67.8% |
| LOAD_ATTR | 329,037 | 32.1% |
| CALL | 740 | 0.1% |
| LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 694,496 | 67.7% |
| TO_BOOL_BOOL | 328,997 | 32.1% |
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
| BINARY_SLICE | 44,898 | 4.1% |
| CALL | 740 | 0.1% |
| LOAD_CONST | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,094,005 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |
| LOAD_CONST | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 7,040,573 | 46.1% |
| LOAD_FAST | 6,268,971 | 41.1% |
| LOAD_ATTR_METHOD_NO_DICT | 969,957 | 6.4% |
| BUILD_TUPLE | 335,957 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 328,139 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,275,839 | 93.5% |
| COPY_FREE_VARS | 657,658 | 4.3% |
| RETURN_GENERATOR | 337,257 | 2.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 656,518 | 99.9% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 0.1% |
| LOAD_CONST | 240 | 0.0% |
| CALL | 220 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 657,378 | 100.0% |
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
| LOAD_CONST | 2,283,987 | 61.5% |
| LOAD_GLOBAL_MODULE | 641,238 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 320,237 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 319,881 | 8.6% |
| LOAD_ATTR_SLOT | 60,756 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,711,049 | 100.0% |
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
| GET_ITER | 1,283,076 | 99.9% |
| JUMP_BACKWARD | 1,260 | 0.1% |
| FOR_ITER | 240 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 746,466 | 58.1% |
| RETURN_CONST | 268,825 | 20.9% |
| LOAD_FAST | 268,305 | 20.9% |
| STORE_FAST | 660 | 0.1% |
| LOAD_DEREF | 140 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 641,378 | 99.9% |
| JUMP_BACKWARD | 740 | 0.1% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 641,978 | 100.0% |
| LOAD_CONST | 200 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 50.0% |
| JUMP_BACKWARD | 60 | 37.5% |
| FOR_ITER | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 50.0% |
| LOAD_GLOBAL | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |


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
| LOAD_FAST | 29,304,265 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 656,638 | 2.2% |
| LOAD_FAST_LOAD_FAST | 336,877 | 1.1% |
| LOAD_ATTR | 4,340 | 0.0% |
| LOAD_DEREF | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,833,972 | 19.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,964,800 | 13.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,955,948 | 13.1% |
| RETURN_VALUE | 3,613,693 | 11.9% |
| CALL_LEN | 2,563,792 | 8.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,964,800 | 64.2% |
| LOAD_FAST | 1,831,815 | 29.6% |
| LOAD_ATTR | 382,411 | 6.2% |
| LOAD_ATTR_SLOT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,779,490 | 45.0% |
| LOAD_FAST_LOAD_FAST | 1,732,123 | 28.0% |
| CALL_PY_EXACT_ARGS | 969,957 | 15.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 695,456 | 11.3% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,429,355 | 48.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,955,948 | 29.7% |
| LOAD_ATTR_SLOT | 1,962,834 | 14.7% |
| RETURN_VALUE | 656,718 | 4.9% |
| LOAD_FAST_LOAD_FAST | 320,281 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,040,573 | 52.8% |
| LOAD_FAST | 5,618,193 | 42.2% |
| LOAD_FAST_LOAD_FAST | 346,713 | 2.6% |
| LOAD_CONST | 320,557 | 2.4% |
| CALL | 1,700 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,419,370 | 99.9% |
| LOAD_ATTR | 1,900 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,014,066 | 58.9% |
| BINARY_OP | 754,624 | 22.1% |
| UNARY_INVERT | 328,179 | 9.6% |
| LOAD_FAST | 320,421 | 9.4% |
| COMPARE_OP | 940 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 664,252 | 100.0% |
| LOAD_ATTR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 336,137 | 50.6% |
| CALL | 320,297 | 48.2% |
| BINARY_OP | 7,938 | 1.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,757 | 99.9% |
| LOAD_ATTR | 220 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,557 | 99.8% |
| COPY_FREE_VARS | 580 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,823,142 | 99.9% |
| LOAD_FAST_LOAD_FAST | 7,960 | 0.1% |
| LOAD_ATTR | 800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,962,834 | 28.7% |
| TO_BOOL_BOOL | 1,777,039 | 26.0% |
| LOAD_ATTR | 961,879 | 14.1% |
| BUILD_LIST | 703,610 | 10.3% |
| LIST_EXTEND | 703,610 | 10.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,658,712 | 34.6% |
| LOAD_FAST | 1,634,733 | 21.3% |
| POP_JUMP_IF_FALSE | 961,379 | 12.5% |
| STORE_FAST | 702,494 | 9.1% |
| JUMP_FORWARD | 641,478 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,284,552 | 68.7% |
| CALL_ISINSTANCE | 1,314,136 | 17.1% |
| LOAD_DEREF | 643,102 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 442,749 | 5.8% |
| BUILD_TUPLE | 560 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,776,465 | 44.4% |
| RESUME_CHECK | 1,675,089 | 19.7% |
| NOP | 1,313,396 | 15.4% |
| POP_TOP | 702,332 | 8.3% |
| POP_JUMP_IF_NOT_NONE | 329,739 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,419,370 | 40.2% |
| BINARY_OP | 2,059,638 | 24.2% |
| LOAD_FAST | 1,366,472 | 16.1% |
| LOAD_FAST_LOAD_FAST | 641,862 | 7.5% |
| COMPARE_OP_INT | 641,238 | 7.5% |


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
| LOAD_FAST | 642,042 | 99.9% |
| LOAD_SUPER_ATTR | 380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 321,261 | 50.0% |
| LOAD_FAST_LOAD_FAST | 320,721 | 49.9% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |
| CALL | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 14,275,839 | 66.3% |
| CACHE | 2,663,822 | 12.4% |
| SEND_GEN | 978,311 | 4.5% |
| COPY_FREE_VARS | 690,750 | 3.2% |
| POP_TOP | 658,154 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,585,689 | 63.1% |
| LOAD_GLOBAL_BUILTIN | 2,658,712 | 12.3% |
| NOP | 2,291,951 | 10.6% |
| LOAD_GLOBAL_MODULE | 1,675,089 | 7.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,307,028 | 6.1% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 978,371 | 59.8% |
| LOAD_CONST | 657,654 | 40.2% |
| SEND | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 978,311 | 59.8% |
| POP_TOP | 657,774 | 40.2% |
| RESUME | 400 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,263,375 | 99.8% |
| STORE_ATTR | 2,640 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,900 | 0.1% |
| LOAD_DEREF | 360 | 0.0% |
| SWAP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,298,920 | 57.3% |
| RETURN_CONST | 641,858 | 28.3% |
| NOP | 320,297 | 14.1% |
| LOAD_CONST | 4,160 | 0.2% |
| LOAD_FAST_LOAD_FAST | 780 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,977,265 | 53.0% |
| LOAD_FAST_LOAD_FAST | 2,634,704 | 46.9% |
| STORE_ATTR | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,975,688 | 35.2% |
| LOAD_CONST | 1,645,751 | 29.3% |
| LOAD_FAST | 987,515 | 17.6% |
| RETURN_CONST | 987,515 | 17.6% |
| NOP | 15,960 | 0.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 336,037 | 99.8% |
| LOAD_CONST | 280 | 0.1% |
| LOAD_FAST | 160 | 0.0% |
| STORE_SUBSCR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 336,137 | 99.9% |
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
| LOAD_ATTR_INSTANCE_VALUE | 5,833,972 | 44.3% |
| RETURN_VALUE | 3,259,420 | 24.7% |
| LOAD_ATTR_SLOT | 1,777,039 | 13.5% |
| CALL_ISINSTANCE | 1,314,856 | 10.0% |
| COPY | 640,282 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,925,231 | 67.7% |
| POP_JUMP_IF_TRUE | 2,968,607 | 22.5% |
| UNARY_NOT | 1,280,024 | 9.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,060,018 | 48.8% |
| BINARY_OP | 1,066,987 | 25.3% |
| LOAD_FAST | 709,176 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 381,033 | 9.0% |
| TO_BOOL | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,874,784 | 68.2% |
| POP_JUMP_IF_TRUE | 1,342,810 | 31.8% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,595,217 | 100.0% |
| TO_BOOL | 160 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,595,337 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 660,554 | 99.8% |
| LOAD_FAST | 920 | 0.1% |
| LOAD_ATTR | 360 | 0.1% |
| TO_BOOL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 661,994 | 100.0% |


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
| FOR_ITER_LIST | 746,466 | 51.2% |
| STORE_FAST | 709,350 | 48.7% |
| UNPACK_SEQUENCE | 280 | 0.0% |
| BINARY_SLICE | 200 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,456,456 | 100.0% |
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
|     deferred | 4,225,968 | 76.5% |
|          hit | 1,290,292 | 23.4% |

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
|          hit | 17,396 | 98.9% |

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
|     deferred | 4,360,083 | 14.0% |
|          hit | 26,790,062 | 86.0% |
|         miss | 1,960 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,220 | 48.4% |
| Failure | 6,620 | 51.6% |

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
|     deferred | 17,956 | 0.5% |
|          hit | 3,711,509 | 99.5% |

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
|     deferred | 16,640 | 0.9% |
|          hit | 1,926,974 | 99.1% |

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
|     deferred | 5,571,170 | 8.4% |
|          hit | 61,050,103 | 91.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,000 | 60.1% |
| Failure | 7,980 | 39.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 3,620 | 45.4% |
| method | 1,560 | 19.5% |
| has managed dict | 1,500 | 18.8% |
| shadowed | 720 | 9.0% |
| metaclass attribute | 180 | 2.3% |
| class method obj | 160 | 2.0% |
| non object slot | 120 | 1.5% |
| class attr descriptor | 60 | 0.8% |
| class attr simple | 40 | 0.5% |
| builtin class method | 20 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,940 | 0.0% |
|        deopt | 80 | 0.0% |
|          hit | 16,194,816 | 99.9% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,720 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 440 | 0.1% |
|          hit | 643,102 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 100.0% |
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
|     deferred | 658,054 | 28.7% |
|          hit | 1,636,485 | 71.3% |

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
|     deferred | 4,100 | 0.1% |
|          hit | 7,880,984 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,100 | 92.3% |
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
|          hit | 336,617 | 99.9% |

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
|     deferred | 2,445,865 | 11.1% |
|          hit | 19,648,967 | 88.9% |

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
|          hit | 1,456,756 | 100.0% |

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
| Basic | 201,810,288 | 48.9% |
| Not specialized | 47,223,645 | 11.4% |
| Specialized hits | 163,785,915 | 39.7% |
| Specialized misses | 2,040 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 5,571,170 | 32.2% |
| CALL | 4,360,083 | 25.2% |
| BINARY_OP | 4,225,968 | 24.4% |
| TO_BOOL | 2,445,865 | 14.1% |
| SEND | 658,054 | 3.8% |
| COMPARE_OP | 17,956 | 0.1% |
| FOR_ITER | 16,640 | 0.1% |
| LOAD_GLOBAL | 4,940 | 0.0% |
| STORE_ATTR | 4,100 | 0.0% |
| LOAD_SUPER_ATTR | 440 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,420 | 69.6% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 23.5% |
| LOAD_GLOBAL_BUILTIN | 80 | 3.9% |
| CALL_BUILTIN_O | 60 | 2.9% |
| CACHE | 0 | 0.0% |
| BEFORE_ASYNC_WITH | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| DELETE_SUBSCR | 0 | 0.0% |
| END_SEND | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,666,442 | 12.6% |
| Calls to Python functions inlined | 18,573,642 | 87.4% |
| Calls via PyEval_EvalFrame (total) | 2,666,442 | 12.6% |
| Calls via PyEval_EvalFrame (vector) | 2,337,085 | 11.0% |
| Calls via PyEval_EvalFrame (generator) | 329,357 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,337,085 | 11.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 180 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 400 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,400 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 659,434 | 3.1% |
| Frame objects created | 1,060 | 0.0% |
| Frames pushed | 17,624,889 | 83.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 9,610,840 | 43.1% |
| Frees to freelist | 9,627,616 |  |
| Allocations | 12,701,650 | 56.9% |
| Allocations to 512 bytes | 12,059,884 | 54.0% |
| Allocations to 4 kbytes | 520 | 0.0% |
| Allocations over 4 kbytes | 641,246 | 2.9% |
| Frees | 13,167,134 |  |
| New values | 700 |  |
| Interpreter increfs | 175,884,265 | 84.5% |
| Interpreter decrefs | 191,817,400 | 83.9% |
| Increfs | 32,303,768 | 15.5% |
| Decrefs | 36,732,501 | 16.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 6,249,622 |  |
| Method cache misses | 7,862 |  |
| Method cache collisions | 7,181 |  |
| Method cache dunder hits | 1,695,142 |  |
| Method cache dunder misses | 1,085 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 40 | 1,980 | 160,800 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 600 |  |
| Traces created | 140 | 23.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 460 | 76.7% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 2,417,631 |  |
| Uops executed | 28,893,596 | 11.95 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 14.3% |
| <= 32 | 80 | 57.1% |
| <= 64 | 0 | 0.0% |
| <= 128 | 40 | 28.6% |


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
| <= 16 | 60 | 42.9% |
| <= 32 | 40 | 28.6% |
| <= 64 | 20 | 14.3% |
| <= 128 | 20 | 14.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,386,764 | 57.4% |
| <= 16 | 640,998 | 26.5% |
| <= 32 | 320,097 | 13.2% |
| <= 64 | 62,172 | 2.6% |
| <= 128 | 7,600 | 0.3% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 460 |
| LOAD_ATTR | 60 |
| TO_BOOL | 40 |
| RETURN_GENERATOR | 20 |


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
Stats gathered on: 2023-11-02
