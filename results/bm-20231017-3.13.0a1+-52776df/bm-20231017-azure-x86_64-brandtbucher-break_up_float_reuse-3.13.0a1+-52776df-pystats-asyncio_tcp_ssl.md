
# Pystats results

- benchmark: asyncio_tcp_ssl
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 52776df
- commit date: 2023-10-17T21:47:13-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 90,724,179 | 23.1% | 23.1% |  |
| POP_JUMP_IF_FALSE | 21,336,409 | 5.4% | 28.6% |  |
| STORE_FAST | 20,771,158 | 5.3% | 33.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,443,097 | 4.7% | 38.6% |  |
| RESUME_CHECK | 16,693,612 | 4.3% | 42.8% |  |
| TO_BOOL_BOOL | 15,514,710 | 4.0% | 46.8% |  |
| LOAD_ATTR | 12,626,129 | 3.2% | 50.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 11,888,235 | 3.0% | 53.0% |  |
| LOAD_ATTR_WITH_HINT | 11,709,545 | 3.0% | 56.0% |  |
| LOAD_CONST | 10,649,326 | 2.7% | 58.7% |  |
| POP_TOP | 10,350,813 | 2.6% | 61.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,485,827 | 2.4% | 63.8% | 0.0% |
| CALL_PY_EXACT_ARGS | 9,369,798 | 2.4% | 66.2% |  |
| POP_JUMP_IF_TRUE | 8,673,921 | 2.2% | 68.4% |  |
| RETURN_VALUE | 7,930,824 | 2.0% | 70.4% |  |
| RETURN_CONST | 7,540,763 | 1.9% | 72.3% |  |
| CALL | 6,622,652 | 1.7% | 74.0% |  |
| JUMP_BACKWARD | 5,894,166 | 1.5% | 75.5% |  |
| TO_BOOL | 5,674,269 | 1.4% | 77.0% |  |
| LOAD_FAST_LOAD_FAST | 5,575,764 | 1.4% | 78.4% |  |
| POP_JUMP_IF_NONE | 5,553,068 | 1.4% | 79.8% |  |
| LOAD_ATTR_SLOT | 5,186,715 | 1.3% | 81.1% | 0.0% |
| LOAD_GLOBAL_MODULE | 5,145,780 | 1.3% | 82.4% |  |
| CALL_PY_WITH_DEFAULTS | 4,088,582 | 1.0% | 83.5% |  |
| LOAD_FAST_CHECK | 3,840,000 | 1.0% | 84.5% |  |
| CALL_LIST_APPEND | 3,634,438 | 0.9% | 85.4% |  |
| NOP | 3,517,695 | 0.9% | 86.3% |  |
| STORE_ATTR_SLOT | 3,498,137 | 0.9% | 87.2% | 0.1% |
| COMPARE_OP_INT | 3,495,554 | 0.9% | 88.1% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 3,154,875 | 0.8% | 88.9% | 0.0% |
| TO_BOOL_INT | 2,392,449 | 0.6% | 89.5% |  |
| CALL_LEN | 2,226,068 | 0.6% | 90.1% |  |
| PUSH_NULL | 2,053,390 | 0.5% | 90.6% |  |
| LOAD_ATTR_MODULE | 1,830,408 | 0.5% | 91.0% |  |
| INTERPRETER_EXIT | 1,757,226 | 0.4% | 91.5% |  |
| BINARY_OP | 1,659,107 | 0.4% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,543,865 | 0.4% | 92.3% | 0.0% |
| BUILD_LIST | 1,246,565 | 0.3% | 92.6% |  |
| LOAD_DEREF | 1,237,025 | 0.3% | 92.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,229,823 | 0.3% | 93.3% |  |
| SEND_GEN | 1,228,565 | 0.3% | 93.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,047,422 | 0.3% | 93.8% | 0.1% |
| FOR_ITER_LIST | 1,033,864 | 0.3% | 94.1% |  |
| BUILD_TUPLE | 1,028,943 | 0.3% | 94.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,023,665 | 0.3% | 94.6% |  |
| FOR_ITER_RANGE | 1,010,823 | 0.3% | 94.9% |  |
| JUMP_FORWARD | 990,905 | 0.3% | 95.1% |  |
| YIELD_VALUE | 981,304 | 0.3% | 95.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 981,184 | 0.3% | 95.6% |  |
| TO_BOOL_NONE | 978,842 | 0.2% | 95.9% |  |
| STORE_FAST_STORE_FAST | 832,024 | 0.2% | 96.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 831,904 | 0.2% | 96.3% |  |
| COPY | 806,163 | 0.2% | 96.5% |  |
| CALL_FUNCTION_EX | 764,102 | 0.2% | 96.7% |  |
| LIST_EXTEND | 763,742 | 0.2% | 96.9% |  |
| CALL_INTRINSIC_1 | 763,742 | 0.2% | 97.1% |  |
| GET_AWAITABLE | 740,823 | 0.2% | 97.3% |  |
| END_SEND | 740,823 | 0.2% | 97.5% |  |
| COMPARE_OP | 739,583 | 0.2% | 97.7% |  |
| GET_ITER | 737,223 | 0.2% | 97.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 529,203 | 0.1% | 98.0% |  |
| STORE_ATTR_WITH_HINT | 518,640 | 0.1% | 98.1% |  |
| BINARY_SLICE | 516,002 | 0.1% | 98.2% |  |
| BINARY_OP_ADD_INT | 500,222 | 0.1% | 98.4% |  |
| RETURN_GENERATOR | 494,402 | 0.1% | 98.5% |  |
| SEND | 493,842 | 0.1% | 98.6% |  |
| CONTAINS_OP | 488,221 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 483,962 | 0.1% | 98.9% |  |
| SWAP | 295,082 | 0.1% | 99.0% |  |
| CALL_BUILTIN_CLASS | 288,242 | 0.1% | 99.0% |  |
| COPY_FREE_VARS | 262,143 | 0.1% | 99.1% |  |
| CALL_KW | 255,302 | 0.1% | 99.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 246,662 | 0.1% | 99.2% |  |
| DELETE_SUBSCR | 246,481 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 242,521 | 0.1% | 99.3% | 0.0% |
| BINARY_OP_ADD_FLOAT_LHS | 241,621 | 0.1% | 99.4% |  |
| LOAD_ATTR_PROPERTY | 241,321 | 0.1% | 99.5% |  |
| PUSH_EXC_INFO | 241,261 | 0.1% | 99.5% |  |
| POP_EXCEPT | 241,261 | 0.1% | 99.6% |  |
| CHECK_EXC_MATCH | 241,261 | 0.1% | 99.7% |  |
| MAKE_CELL | 241,140 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 240,721 | 0.1% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 240,660 | 0.1% | 99.8% |  |
| MAKE_FUNCTION | 240,660 | 0.1% | 99.9% |  |
| BUILD_SLICE | 240,481 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,080 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 27,302 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 12,360 | 0.0% | 100.0% |  |
| FOR_ITER | 12,300 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 12,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 9,898 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,021 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,781 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 6,160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 4,859 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 18,427,275 | 4.7% | 4.7% |
| STORE_FAST LOAD_FAST | 14,261,007 | 3.6% | 8.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 13,492,041 | 3.4% | 11.8% |
| RESUME_CHECK LOAD_FAST | 12,626,435 | 3.2% | 15.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 11,483,848 | 2.9% | 17.9% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 9,514,201 | 2.4% | 20.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 9,271,925 | 2.4% | 22.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,628,195 | 2.2% | 24.9% |
| LOAD_FAST LOAD_ATTR | 8,172,559 | 2.1% | 27.0% |
| LOAD_FAST TO_BOOL_BOOL | 7,927,803 | 2.0% | 29.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,915,252 | 1.8% | 30.8% |
| RETURN_CONST POP_TOP | 6,273,079 | 1.6% | 32.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 6,122,508 | 1.6% | 33.9% |
| RETURN_VALUE STORE_FAST | 5,836,450 | 1.5% | 35.4% |
| TO_BOOL POP_JUMP_IF_TRUE | 5,411,707 | 1.4% | 36.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,407,449 | 1.4% | 38.2% |
| LOAD_FAST RETURN_VALUE | 5,339,050 | 1.4% | 39.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 5,310,127 | 1.4% | 40.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,175,536 | 1.3% | 42.2% |
| CALL STORE_FAST | 5,112,067 | 1.3% | 43.5% |
| LOAD_FAST TO_BOOL | 4,861,506 | 1.2% | 44.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,817,525 | 1.2% | 46.0% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_WITH_VALUES | 4,587,204 | 1.2% | 47.2% |
| LOAD_FAST CALL | 4,577,584 | 1.2% | 48.3% |
| JUMP_BACKWARD LOAD_FAST | 4,562,462 | 1.2% | 49.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 4,088,462 | 1.0% | 50.5% |
| LOAD_ATTR CALL_PY_WITH_DEFAULTS | 4,080,841 | 1.0% | 51.6% |
| LOAD_CONST LOAD_FAST | 3,727,995 | 1.0% | 52.5% |
| CALL_LIST_APPEND JUMP_BACKWARD | 3,634,258 | 0.9% | 53.5% |
| POP_TOP RETURN_CONST | 3,519,547 | 0.9% | 54.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 3,463,012 | 0.9% | 55.2% |
| LOAD_CONST STORE_FAST | 3,427,036 | 0.9% | 56.1% |
| LOAD_FAST CALL_LIST_APPEND | 3,359,337 | 0.9% | 57.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_CHECK | 3,359,217 | 0.9% | 57.8% |
| LOAD_FAST_CHECK LOAD_ATTR_METHOD_NO_DICT | 3,359,217 | 0.9% | 58.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,356,493 | 0.9% | 59.5% |
| POP_TOP LOAD_FAST | 3,267,195 | 0.8% | 60.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,254,413 | 0.8% | 61.2% |
| NOP LOAD_FAST | 3,022,271 | 0.8% | 62.0% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 2,943,087 | 0.8% | 62.7% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,860,571 | 0.7% | 63.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,777,832 | 0.7% | 64.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,022,369 | 0.5% | 64.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,980,368 | 0.5% | 65.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,977,309 | 0.5% | 65.7% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 1,961,165 | 0.5% | 66.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,829,068 | 0.5% | 66.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,815,930 | 0.5% | 67.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 1,713,684 | 0.4% | 67.5% |
| LOAD_FAST STORE_ATTR_SLOT | 1,517,769 | 0.4% | 67.9% |
| CACHE RESUME_CHECK | 1,514,946 | 0.4% | 68.3% |
| POP_TOP LOAD_CONST | 1,487,824 | 0.4% | 68.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,484,706 | 0.4% | 69.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_WITH_HINT | 1,462,024 | 0.4% | 69.4% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 1,461,904 | 0.4% | 69.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 1,394,405 | 0.4% | 70.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,389,724 | 0.4% | 70.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,365,124 | 0.3% | 70.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,345,185 | 0.3% | 71.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,297,443 | 0.3% | 71.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,269,645 | 0.3% | 71.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,258,927 | 0.3% | 72.2% |
| LOAD_FAST LOAD_CONST | 1,239,849 | 0.3% | 72.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,224,063 | 0.3% | 72.8% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 1,216,823 | 0.3% | 73.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,204,864 | 0.3% | 73.4% |
| PUSH_NULL LOAD_FAST | 1,059,125 | 0.3% | 73.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,040,464 | 0.3% | 74.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,033,983 | 0.3% | 74.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,025,125 | 0.3% | 74.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,016,704 | 0.3% | 74.8% |
| RETURN_CONST INTERPRETER_EXIT | 1,013,883 | 0.3% | 75.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,013,143 | 0.3% | 75.3% |
| STORE_FAST RETURN_CONST | 1,004,703 | 0.3% | 75.5% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 997,984 | 0.3% | 75.8% |
| POP_JUMP_IF_FALSE NOP | 996,902 | 0.3% | 76.0% |
| STORE_ATTR_SLOT LOAD_CONST | 996,785 | 0.3% | 76.3% |
| STORE_FAST JUMP_FORWARD | 984,427 | 0.3% | 76.5% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 981,184 | 0.3% | 76.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 981,182 | 0.3% | 77.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 978,842 | 0.2% | 77.3% |
| LOAD_CONST COMPARE_OP_INT | 977,766 | 0.2% | 77.5% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 977,402 | 0.2% | 77.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 831,784 | 0.2% | 78.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 831,184 | 0.2% | 78.2% |
| POP_TOP JUMP_BACKWARD | 809,642 | 0.2% | 78.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 799,481 | 0.2% | 78.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS STORE_FAST | 797,521 | 0.2% | 78.8% |
| COPY TO_BOOL_INT | 792,063 | 0.2% | 79.0% |
| LOAD_GLOBAL_MODULE BINARY_OP | 791,763 | 0.2% | 79.2% |
| RESUME_CHECK NOP | 790,805 | 0.2% | 79.4% |
| LOAD_ATTR LOAD_FAST | 784,444 | 0.2% | 79.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 781,564 | 0.2% | 79.8% |
| LOAD_FAST CALL_LEN | 780,463 | 0.2% | 80.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 780,365 | 0.2% | 80.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 772,683 | 0.2% | 80.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 770,083 | 0.2% | 80.6% |
| FOR_ITER_RANGE STORE_FAST | 769,382 | 0.2% | 80.8% |
| JUMP_BACKWARD FOR_ITER_RANGE | 769,322 | 0.2% | 81.0% |
| LOAD_ATTR PUSH_NULL | 764,122 | 0.2% | 81.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,142 | 93.2% |
| LOAD_CONST | 34,860 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 268,800 | 52.1% |
| CALL | 240,481 | 46.6% |
| STORE_FAST | 6,301 | 1.2% |
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
| RESUME_CHECK | 1,514,946 | 86.2% |
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
| LOAD_GLOBAL_MODULE | 240,781 | 99.8% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.1% |
| BUILD_TUPLE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 241,261 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 240,481 | 97.6% |
| LOAD_CONST | 6,000 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 246,481 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,841 | 34.1% |
| SEND | 246,721 | 33.3% |
| RETURN_VALUE | 241,261 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,682 | 67.4% |
| STORE_FAST | 240,841 | 32.5% |
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
| LOAD_FAST | 489,422 | 66.4% |
| CALL_BUILTIN_CLASS | 241,561 | 32.8% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 483,402 | 65.6% |
| FOR_ITER_RANGE | 241,501 | 32.8% |
| FOR_ITER | 6,200 | 0.8% |
| FOR_ITER_TUPLE | 6,060 | 0.8% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,013,883 | 57.7% |
| RETURN_VALUE | 496,202 | 28.2% |
| YIELD_VALUE | 246,841 | 14.0% |
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
| POP_JUMP_IF_FALSE | 996,902 | 28.3% |
| RESUME_CHECK | 790,805 | 22.5% |
| POP_JUMP_IF_TRUE | 487,923 | 13.9% |
| STORE_FAST | 483,722 | 13.8% |
| NOP | 481,262 | 13.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,022,271 | 85.9% |
| NOP | 481,262 | 13.7% |
| LOAD_GLOBAL_MODULE | 13,622 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 241,141 | 100.0% |
| SWAP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240,541 | 99.7% |
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
| RETURN_CONST | 6,273,079 | 60.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,297,443 | 12.5% |
| CALL_FUNCTION_EX | 763,442 | 7.4% |
| POP_JUMP_IF_FALSE | 516,902 | 5.0% |
| END_SEND | 499,682 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,519,547 | 34.0% |
| LOAD_FAST | 3,267,195 | 31.6% |
| LOAD_CONST | 1,487,824 | 14.4% |
| JUMP_BACKWARD | 809,642 | 7.8% |
| RESUME_CHECK | 494,402 | 4.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,541 | 99.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300 | 0.1% |
| BINARY_SUBSCR_DICT | 300 | 0.1% |
| RERAISE | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240,761 | 99.8% |
| LOAD_GLOBAL_BUILTIN | 440 | 0.2% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,269,645 | 61.8% |
| LOAD_ATTR | 764,122 | 37.2% |
| LOAD_DEREF | 18,063 | 0.9% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,059,125 | 51.6% |
| LOAD_FAST_LOAD_FAST | 502,023 | 24.4% |
| CALL | 491,462 | 23.9% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,502 | 99.8% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,802 | 99.9% |
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
| LOAD_FAST | 5,339,050 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 780,365 | 9.8% |
| CALL | 517,622 | 6.5% |
| LOAD_ATTR | 480,841 | 6.1% |
| BINARY_OP_ADD_INT | 253,081 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,836,450 | 73.6% |
| TO_BOOL_BOOL | 520,943 | 6.6% |
| LOAD_FAST | 517,502 | 6.5% |
| INTERPRETER_EXIT | 496,202 | 6.3% |
| POP_TOP | 254,342 | 3.2% |


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
| LOAD_FAST | 4,861,506 | 85.7% |
| LOAD_ATTR_INSTANCE_VALUE | 557,122 | 9.8% |
| LOAD_ATTR_WITH_HINT | 252,601 | 4.5% |
| TO_BOOL | 1,840 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,411,707 | 95.4% |
| POP_JUMP_IF_FALSE | 259,622 | 4.6% |
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
| LOAD_GLOBAL_MODULE | 791,763 | 47.7% |
| LOAD_ATTR_MODULE | 555,783 | 33.5% |
| LOAD_ATTR | 274,921 | 16.6% |
| POP_JUMP_IF_FALSE | 34,500 | 2.1% |
| BINARY_OP | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 550,682 | 33.2% |
| TO_BOOL_INT | 550,142 | 33.2% |
| STORE_FAST | 276,241 | 16.6% |
| BUILD_TUPLE | 274,921 | 16.6% |
| LOAD_FAST_LOAD_FAST | 5,941 | 0.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 763,202 | 61.2% |
| STORE_FAST | 241,501 | 19.4% |
| LOAD_FAST | 241,082 | 19.3% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,982 | 61.3% |
| STORE_FAST | 482,223 | 38.7% |
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
| LOAD_FAST | 240,481 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,481 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 486,961 | 47.3% |
| BINARY_OP | 274,921 | 26.7% |
| LOAD_FAST | 247,080 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 12,540 | 1.2% |
| LOAD_FAST_LOAD_FAST | 6,781 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 486,961 | 47.3% |
| CALL_LIST_APPEND | 274,921 | 26.7% |
| LOAD_CONST | 240,660 | 23.4% |
| CALL_ISINSTANCE | 12,400 | 1.2% |
| CALL_PY_EXACT_ARGS | 12,261 | 1.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,577,584 | 69.1% |
| LOAD_FAST_LOAD_FAST | 495,302 | 7.5% |
| PUSH_NULL | 491,462 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 487,803 | 7.4% |
| LOAD_CONST | 253,782 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,112,067 | 77.2% |
| RETURN_VALUE | 517,622 | 7.8% |
| POP_TOP | 248,221 | 3.7% |
| RESUME_CHECK | 247,819 | 3.7% |
| PUSH_EXC_INFO | 240,541 | 3.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 763,502 | 99.9% |
| BUILD_MAP | 240 | 0.0% |
| DICT_MERGE | 180 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 763,442 | 99.9% |
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
| LIST_EXTEND | 763,742 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 763,502 | 100.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 255,302 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,781 | 96.7% |
| COPY_FREE_VARS | 6,001 | 2.4% |
| STORE_FAST | 840 | 0.3% |
| RESUME_CHECK | 600 | 0.2% |
| POP_TOP | 360 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 736,983 | 99.6% |
| COMPARE_OP | 980 | 0.1% |
| LOAD_ATTR_MODULE | 780 | 0.1% |
| LOAD_CONST | 560 | 0.1% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 738,183 | 99.8% |
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
| BUILD_TUPLE | 486,961 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 300 | 0.1% |
| BUILD_SET | 300 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 488,041 | 100.0% |
| POP_JUMP_IF_TRUE | 180 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 550,682 | 68.3% |
| CALL_LEN | 241,381 | 29.9% |
| LOAD_FAST | 12,960 | 1.6% |
| SWAP | 540 | 0.1% |
| UNARY_NOT | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 792,063 | 98.3% |
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
| CALL_PY_EXACT_ARGS | 7,801 | 3.0% |
| CALL_KW | 6,001 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,001 | 2.3% |
| LOAD_ATTR_PROPERTY | 540 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 262,023 | 100.0% |
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
| RETURN_GENERATOR | 493,802 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 240,421 | 32.5% |
| LOAD_FAST | 6,120 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,823 | 100.0% |


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
| POP_TOP | 809,642 | 13.7% |
| JUMP_FORWARD | 480,783 | 8.2% |
| POP_JUMP_IF_FALSE | 241,740 | 4.1% |
| POP_JUMP_IF_TRUE | 240,721 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,562,462 | 77.4% |
| FOR_ITER_RANGE | 769,322 | 13.1% |
| FOR_ITER_LIST | 550,322 | 9.3% |
| FOR_ITER_TUPLE | 6,060 | 0.1% |
| FOR_ITER | 6,000 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 981,184 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,463 | 74.9% |
| SEND | 246,721 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 984,427 | 99.3% |
| POP_JUMP_IF_FALSE | 4,799 | 0.5% |
| POP_TOP | 839 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 0.0% |
| STORE_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 480,783 | 48.5% |
| LOAD_FAST | 262,982 | 26.5% |
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
| LOAD_ATTR_SLOT | 763,202 | 99.9% |
| LOAD_FAST | 360 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 763,742 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,172,559 | 64.7% |
| LOAD_GLOBAL_MODULE | 1,713,684 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 981,182 | 7.8% |
| LOAD_ATTR_SLOT | 763,402 | 6.0% |
| LOAD_ATTR_WITH_HINT | 734,542 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 4,080,841 | 32.3% |
| CALL_PY_EXACT_ARGS | 2,943,087 | 23.3% |
| LOAD_FAST | 784,444 | 6.2% |
| PUSH_NULL | 764,122 | 6.1% |
| COMPARE_OP | 736,983 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,977,309 | 18.6% |
| POP_TOP | 1,487,824 | 14.0% |
| LOAD_FAST | 1,239,849 | 11.6% |
| STORE_ATTR_SLOT | 996,785 | 9.4% |
| GET_AWAITABLE | 740,823 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,727,995 | 35.0% |
| STORE_FAST | 3,427,036 | 32.2% |
| COMPARE_OP_INT | 977,766 | 9.2% |
| SEND_GEN | 493,982 | 4.6% |
| CALL_PY_EXACT_ARGS | 481,522 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 486,781 | 39.4% |
| STORE_FAST | 246,601 | 19.9% |
| POP_JUMP_IF_FALSE | 240,660 | 19.5% |
| LOAD_CONST | 240,300 | 19.4% |
| LOAD_ATTR | 12,002 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 721,140 | 58.3% |
| LOAD_ATTR | 240,520 | 19.4% |
| STORE_ATTR_WITH_HINT | 240,300 | 19.4% |
| PUSH_NULL | 18,063 | 1.5% |
| LOAD_FAST | 9,481 | 0.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,261,007 | 15.7% |
| RESUME_CHECK | 12,626,435 | 13.9% |
| POP_JUMP_IF_FALSE | 11,483,848 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 9,271,925 | 10.2% |
| POP_JUMP_IF_TRUE | 6,915,252 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 18,427,275 | 20.3% |
| LOAD_ATTR_WITH_HINT | 9,514,201 | 10.5% |
| LOAD_ATTR | 8,172,559 | 9.0% |
| TO_BOOL_BOOL | 7,927,803 | 8.7% |
| RETURN_VALUE | 5,339,050 | 5.9% |


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
| POP_JUMP_IF_FALSE | 3,359,217 | 87.5% |
| STORE_FAST | 240,362 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 240,362 | 6.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 41 | 0.0% |
| LOAD_ATTR | 18 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,359,217 | 87.5% |
| LOAD_FAST | 240,362 | 6.3% |
| CALL_METHOD_DESCRIPTOR_O | 240,362 | 6.3% |
| CALL | 38 | 0.0% |
| CALL_PY_EXACT_ARGS | 21 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,484,706 | 26.6% |
| STORE_FAST | 1,040,464 | 18.7% |
| POP_JUMP_IF_FALSE | 741,543 | 13.3% |
| LOAD_ATTR_METHOD_NO_DICT | 557,283 | 10.0% |
| PUSH_NULL | 502,023 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,980,368 | 35.5% |
| LOAD_ATTR_WITH_HINT | 1,462,024 | 26.2% |
| LOAD_FAST | 772,683 | 13.9% |
| CALL | 495,302 | 8.9% |
| LOAD_FAST_LOAD_FAST | 490,741 | 8.8% |


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
| TO_BOOL_BOOL | 13,492,041 | 63.2% |
| COMPARE_OP_INT | 3,254,413 | 15.3% |
| TO_BOOL_INT | 1,394,405 | 6.5% |
| TO_BOOL_NONE | 978,842 | 4.6% |
| COMPARE_OP | 738,183 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,483,848 | 53.8% |
| LOAD_FAST_CHECK | 3,359,217 | 15.7% |
| LOAD_CONST | 1,977,309 | 9.3% |
| RETURN_CONST | 1,258,927 | 5.9% |
| NOP | 996,902 | 4.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,817,525 | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE | 734,583 | 13.2% |
| LOAD_ATTR | 480 | 0.0% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,310,127 | 95.6% |
| LOAD_CONST | 240,781 | 4.3% |
| RETURN_CONST | 1,140 | 0.0% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 781,564 | 76.3% |
| LOAD_ATTR_INSTANCE_VALUE | 241,201 | 23.6% |
| LOAD_ATTR_WITH_HINT | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 525,963 | 51.4% |
| LOAD_GLOBAL_MODULE | 248,681 | 24.3% |
| LOAD_FAST_LOAD_FAST | 247,741 | 24.2% |
| LOAD_GLOBAL_BUILTIN | 380 | 0.0% |
| RETURN_CONST | 360 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 5,411,707 | 62.4% |
| TO_BOOL_BOOL | 2,022,369 | 23.3% |
| TO_BOOL_INT | 997,984 | 11.5% |
| COMPARE_OP_INT | 241,141 | 2.8% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,915,252 | 79.7% |
| NOP | 487,923 | 5.6% |
| RETURN_CONST | 275,401 | 3.2% |
| LOAD_CONST | 271,742 | 3.1% |
| STORE_FAST | 241,381 | 2.8% |


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
| POP_TOP | 3,519,547 | 46.7% |
| POP_JUMP_IF_FALSE | 1,258,927 | 16.7% |
| STORE_FAST | 1,004,703 | 13.3% |
| STORE_ATTR_SLOT | 502,203 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 482,941 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,273,079 | 83.2% |
| INTERPRETER_EXIT | 1,013,883 | 13.4% |
| END_SEND | 252,841 | 3.4% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,841 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,721 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,721 | 50.0% |
| END_SEND | 246,721 | 50.0% |
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
| RETURN_VALUE | 5,836,450 | 28.1% |
| CALL | 5,112,067 | 24.6% |
| LOAD_CONST | 3,427,036 | 16.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 797,521 | 3.8% |
| FOR_ITER_RANGE | 769,382 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,261,007 | 68.7% |
| LOAD_FAST_LOAD_FAST | 1,040,464 | 5.0% |
| LOAD_GLOBAL_BUILTIN | 1,016,704 | 4.9% |
| RETURN_CONST | 1,004,703 | 4.8% |
| JUMP_FORWARD | 984,427 | 4.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 831,784 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 831,184 | 99.9% |
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
| LOAD_ATTR | 281,222 | 95.3% |
| BINARY_OP_ADD_INT | 6,600 | 2.2% |
| BINARY_OP_SUBTRACT_INT | 6,360 | 2.2% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |
| CALL_LEN | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 281,222 | 95.3% |
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
| YIELD_VALUE | 734,463 | 74.8% |
| SEND | 246,721 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,463 | 74.8% |
| INTERPRETER_EXIT | 246,841 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 241,381 | 99.9% |
| LOAD_FAST | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,381 | 99.9% |
| LOAD_FAST | 240 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 253,081 | 50.6% |
| CALL_LEN | 246,421 | 49.3% |
| LOAD_CONST | 640 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 253,081 | 50.6% |
| STORE_FAST | 240,421 | 48.1% |
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
| LOAD_ATTR_INSTANCE_VALUE | 240,421 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,461 | 99.9% |
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
| RETURN_VALUE | 6,061 | 86.3% |
| LOAD_FAST | 940 | 13.4% |
| BINARY_SUBSCR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,001 | 85.5% |
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
| LOAD_CONST | 9,878 | 99.8% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,099 | 51.5% |
| STORE_FAST | 4,739 | 47.9% |
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
| LOAD_ATTR_INSTANCE_VALUE | 240,661 | 97.6% |
| CALL_BUILTIN_CLASS | 6,001 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,661 | 97.6% |
| COPY_FREE_VARS | 6,001 | 2.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,602 | 85.9% |
| LOAD_ATTR_INSTANCE_VALUE | 40,240 | 14.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 241,561 | 83.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,080 | 13.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,001 | 2.1% |
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
| CALL_BUILTIN_CLASS | 40,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40,080 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 14,322 | 52.5% |
| BUILD_TUPLE | 12,400 | 45.4% |
| LOAD_GLOBAL_MODULE | 280 | 1.0% |
| LOAD_ATTR_MODULE | 160 | 0.6% |
| CALL | 140 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 27,162 | 99.5% |
| TO_BOOL | 140 | 0.5% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,204,864 | 54.1% |
| LOAD_FAST | 780,463 | 35.1% |
| LOAD_ATTR_WITH_HINT | 240,661 | 10.8% |
| CALL | 40 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,901 | 23.5% |
| TO_BOOL_INT | 487,682 | 21.9% |
| LOAD_FAST | 480,961 | 21.6% |
| BINARY_OP_ADD_INT | 246,421 | 11.1% |
| COPY | 241,381 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,337 | 92.4% |
| BUILD_TUPLE | 274,921 | 7.6% |
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
| LOAD_FAST | 275,041 | 52.0% |
| LOAD_ATTR_METHOD_NO_DICT | 247,141 | 46.7% |
| LOAD_FAST_LOAD_FAST | 6,721 | 1.3% |
| RETURN_VALUE | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,242 | 98.7% |
| RETURN_VALUE | 6,841 | 1.3% |
| POP_TOP | 120 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 241,381 | 99.5% |
| LOAD_FAST | 420 | 0.2% |
| LOAD_ATTR | 300 | 0.1% |
| LOAD_CONST | 220 | 0.1% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,501 | 99.6% |
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
| LOAD_ATTR_METHOD_NO_DICT | 799,481 | 76.3% |
| LOAD_ATTR | 247,161 | 23.6% |
| CALL | 440 | 0.0% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 797,521 | 76.1% |
| TO_BOOL_BOOL | 247,121 | 23.6% |
| POP_TOP | 780 | 0.1% |
| RETURN_VALUE | 540 | 0.1% |
| LOAD_FAST | 420 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,033,983 | 67.0% |
| BINARY_SLICE | 268,800 | 17.4% |
| LOAD_FAST_CHECK | 240,362 | 15.6% |
| CALL | 480 | 0.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,297,443 | 84.0% |
| CALL_PY_EXACT_ARGS | 240,362 | 15.6% |
| RETURN_VALUE | 6,000 | 0.4% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 2,943,087 | 31.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,860,571 | 30.5% |
| LOAD_FAST | 1,815,930 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 770,083 | 8.2% |
| LOAD_CONST | 481,522 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,628,195 | 92.1% |
| RETURN_GENERATOR | 493,502 | 5.3% |
| MAKE_CELL | 240,300 | 2.6% |
| COPY_FREE_VARS | 7,801 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,080,841 | 99.8% |
| LOAD_FAST | 6,721 | 0.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,088,462 | 100.0% |
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
| LOAD_FAST | 4,739 | 97.5% |
| LOAD_ATTR_SLOT | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,739 | 97.5% |
| RETURN_VALUE | 120 | 2.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 1,461,904 | 41.8% |
| LOAD_CONST | 977,766 | 28.0% |
| LOAD_GLOBAL_MODULE | 241,381 | 6.9% |
| LOAD_FAST | 240,661 | 6.9% |
| BINARY_OP_MULTIPLY_INT | 240,461 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,254,413 | 93.1% |
| POP_JUMP_IF_TRUE | 241,141 | 6.9% |


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
| JUMP_BACKWARD | 550,322 | 53.2% |
| GET_ITER | 483,402 | 46.8% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 549,842 | 53.2% |
| RETURN_CONST | 241,561 | 23.4% |
| LOAD_FAST | 241,381 | 23.3% |
| STORE_FAST | 780 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 769,322 | 76.1% |
| GET_ITER | 241,501 | 23.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 769,382 | 76.1% |
| LOAD_CONST | 241,381 | 23.9% |
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
| LOAD_FAST | 18,427,275 | 99.9% |
| LOAD_FAST_LOAD_FAST | 7,041 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,721 | 0.0% |
| LOAD_ATTR | 1,220 | 0.0% |
| COPY | 760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,122,508 | 33.2% |
| TO_BOOL_BOOL | 3,463,012 | 18.8% |
| CALL_LEN | 1,204,864 | 6.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,025,125 | 5.6% |
| LOAD_ATTR | 981,182 | 5.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,122,508 | 51.5% |
| LOAD_FAST_CHECK | 3,359,217 | 28.3% |
| LOAD_FAST | 1,389,724 | 11.7% |
| LOAD_ATTR_WITH_HINT | 494,042 | 4.2% |
| LOAD_ATTR | 282,102 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,271,925 | 78.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 799,481 | 6.7% |
| CALL_PY_EXACT_ARGS | 770,083 | 6.5% |
| LOAD_FAST_LOAD_FAST | 557,283 | 4.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 247,141 | 2.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 4,587,204 | 48.4% |
| LOAD_FAST | 3,356,493 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,025,125 | 10.8% |
| LOAD_ATTR_SLOT | 508,124 | 5.4% |
| RETURN_VALUE | 6,921 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,407,449 | 57.0% |
| CALL_PY_EXACT_ARGS | 2,860,571 | 30.2% |
| LOAD_FAST_LOAD_FAST | 495,002 | 5.2% |
| LOAD_CONST | 481,023 | 5.1% |
| LOAD_GLOBAL_MODULE | 240,561 | 2.5% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,829,068 | 99.9% |
| LOAD_ATTR | 1,220 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,269,645 | 69.4% |
| BINARY_OP | 555,783 | 30.4% |
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
| LOAD_FAST | 241,181 | 99.9% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,781 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,175,536 | 99.8% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 5,099 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,365,124 | 26.3% |
| TO_BOOL_NONE | 977,402 | 18.8% |
| LOAD_ATTR | 763,402 | 14.7% |
| LIST_EXTEND | 763,202 | 14.7% |
| BUILD_LIST | 763,202 | 14.7% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,514,201 | 81.3% |
| LOAD_FAST_LOAD_FAST | 1,462,024 | 12.5% |
| LOAD_DEREF | 721,140 | 6.2% |
| COPY | 12,120 | 0.1% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,587,204 | 39.2% |
| TO_BOOL_BOOL | 1,961,165 | 16.7% |
| COMPARE_OP_INT | 1,461,904 | 12.5% |
| LOAD_GLOBAL_MODULE | 1,216,823 | 10.4% |
| LOAD_ATTR | 734,542 | 6.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,016,704 | 32.2% |
| POP_JUMP_IF_FALSE | 477,202 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 345,521 | 11.0% |
| RESUME_CHECK | 310,623 | 9.8% |
| LOAD_FAST | 267,183 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,777,832 | 88.0% |
| LOAD_GLOBAL_BUILTIN | 345,521 | 11.0% |
| CALL_ISINSTANCE | 14,322 | 0.5% |
| BUILD_TUPLE | 12,540 | 0.4% |
| LOAD_DEREF | 3,360 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,345,185 | 26.1% |
| LOAD_ATTR_WITH_HINT | 1,216,823 | 23.6% |
| RESUME_CHECK | 1,013,143 | 19.7% |
| LOAD_ATTR | 494,001 | 9.6% |
| POP_TOP | 282,022 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,829,068 | 35.5% |
| LOAD_ATTR | 1,713,684 | 33.3% |
| BINARY_OP | 791,763 | 15.4% |
| COMPARE_OP_INT | 241,381 | 4.7% |
| CALL_PY_EXACT_ARGS | 241,341 | 4.7% |


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
| CALL_PY_EXACT_ARGS | 8,628,195 | 51.7% |
| CALL_PY_WITH_DEFAULTS | 4,088,462 | 24.5% |
| CACHE | 1,514,946 | 9.1% |
| SEND_GEN | 734,463 | 4.4% |
| POP_TOP | 494,402 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,626,435 | 75.6% |
| LOAD_GLOBAL_MODULE | 1,013,143 | 6.1% |
| JUMP_BACKWARD_NO_INTERRUPT | 981,184 | 5.9% |
| NOP | 790,805 | 4.7% |
| LOAD_DEREF | 486,781 | 2.9% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,463 | 59.8% |
| LOAD_CONST | 493,982 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,463 | 59.8% |
| POP_TOP | 494,102 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,224,063 | 99.5% |
| LOAD_FAST_LOAD_FAST | 3,360 | 0.3% |
| STORE_ATTR | 1,400 | 0.1% |
| SWAP | 760 | 0.1% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 496,621 | 40.4% |
| RETURN_CONST | 482,941 | 39.3% |
| NOP | 240,421 | 19.5% |
| LOAD_CONST | 5,220 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,420 | 0.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,980,368 | 56.6% |
| LOAD_FAST | 1,517,769 | 43.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,484,706 | 42.4% |
| LOAD_CONST | 996,785 | 28.5% |
| LOAD_FAST | 502,443 | 14.4% |
| RETURN_CONST | 502,203 | 14.4% |
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
| LOAD_ATTR | 6,301 | 92.9% |
| LOAD_CONST | 280 | 4.1% |
| LOAD_FAST | 160 | 2.4% |
| STORE_SUBSCR | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,361 | 93.8% |
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
| LOAD_FAST | 7,927,803 | 51.1% |
| LOAD_ATTR_INSTANCE_VALUE | 3,463,012 | 22.3% |
| LOAD_ATTR_WITH_HINT | 1,961,165 | 12.6% |
| LOAD_ATTR_SLOT | 1,365,124 | 8.8% |
| RETURN_VALUE | 520,943 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,492,041 | 87.0% |
| POP_JUMP_IF_TRUE | 2,022,369 | 13.0% |
| UNARY_NOT | 300 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 792,063 | 33.1% |
| BINARY_OP | 550,142 | 23.0% |
| CALL_LEN | 487,682 | 20.4% |
| LOAD_FAST | 281,401 | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE | 281,101 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,394,405 | 58.3% |
| POP_JUMP_IF_TRUE | 997,984 | 41.7% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 483,842 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 483,842 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 977,402 | 99.9% |
| LOAD_FAST | 860 | 0.1% |
| LOAD_ATTR | 540 | 0.1% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 978,842 | 100.0% |


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
| FOR_ITER_LIST | 549,842 | 66.1% |
| STORE_FAST | 281,222 | 33.8% |
| RETURN_VALUE | 320 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 831,784 | 100.0% |
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
|          hit |         6781 | 97.4% |

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
| specialization.deferred |      5671329 | 22.6% |
|          hit |     19370443 | 77.3% |
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
| specialization.deferred |      1658227 | 62.5% |
|          hit |       995224 | 37.5% |

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
| specialization.deferred |      6615812 | 21.9% |
|          hit |     23531565 | 78.0% |
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
| specialization.deferred |       738363 | 17.4% |
|          hit |      3500533 | 82.6% |
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
|          hit |      2056807 | 99.4% |

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
| specialization.deferred |     12614069 | 17.7% |
|          hit |     58785088 | 82.3% |
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
|          hit |      8300595 | 100.0% |
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
| specialization.deferred |       493442 | 28.6% |
|          hit |      1228565 | 71.3% |

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
|          hit |      5244200 | 99.9% |
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
|          hit |       832084 | 100.0% |

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
| Basic | 181,058,801 | 46.2% |
| Not specialized | 70,843,693 | 18.1% |
| Specialized | 140,319,534 | 35.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 12,614,069 | 45.4% |
| CALL | 6,615,812 | 23.8% |
| TO_BOOL | 5,671,329 | 20.4% |
| BINARY_OP | 1,658,227 | 6.0% |
| COMPARE_OP | 738,363 | 2.7% |
| SEND | 493,442 | 1.8% |
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
| Calls to PyEval_EvalDefault | 1,757,226 | 10.2% |
| Calls to Python functions inlined | 15,430,788 | 89.8% |
| Calls via PyEval_EvalFrame (total) | 1,757,226 | 10.2% |
| Calls via PyEval_EvalFrame (vector) | 1,510,085 | 8.8% |
| Calls via PyEval_EvalFrame (generator) | 247,141 | 1.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,510,085 | 8.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,080 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,762 | 2.9% |
| Frames pushed | 15,712,728 | 91.4% |
| Frame objects created | 482,342 | 2.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,005,033 | 41.3% |
| Frees to freelist | 11,011,294 |  |
| Allocations | 15,652,635 | 58.7% |
| Allocations to 512 bytes | 10,843,877 | 40.7% |
| Allocations to 4 kbytes | 241,019 | 0.9% |
| Allocations over 4 kbytes | 4,567,739 | 17.1% |
| Frees | 15,956,097 |  |
| New values | 780 |  |
| Interpreter increfs | 167,461,592 | 76.0% |
| Interpreter decrefs | 185,959,102 | 75.8% |
| Increfs | 52,750,242 | 24.0% |
| Decrefs | 59,294,837 | 24.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 120 | 15.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,291,383 |  |
| Method cache misses | 29,074 |  |
| Method cache collisions | 29,283 |  |
| Method cache dunder hits | 782,769 |  |
| Method cache dunder misses | 215 |  |


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
Stats gathered on: 2023-10-19
