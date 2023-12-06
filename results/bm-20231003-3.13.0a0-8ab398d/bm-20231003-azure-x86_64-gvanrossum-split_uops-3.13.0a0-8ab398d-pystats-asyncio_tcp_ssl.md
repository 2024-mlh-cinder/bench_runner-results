
# Pystats results

- benchmark: asyncio_tcp_ssl
- fork: gvanrossum
- ref: split-uops
- commit hash: 8ab398d
- commit date: 2023-10-03T16:05:03-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 90,723,782 | 23.1% | 23.1% |  |
| POP_JUMP_IF_FALSE | 21,336,256 | 5.4% | 28.6% |  |
| STORE_FAST | 20,771,421 | 5.3% | 33.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,443,048 | 4.7% | 38.6% |  |
| RESUME_CHECK | 16,693,540 | 4.3% | 42.8% |  |
| TO_BOOL_BOOL | 15,514,749 | 4.0% | 46.8% |  |
| LOAD_ATTR | 12,626,092 | 3.2% | 50.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 11,888,306 | 3.0% | 53.0% |  |
| LOAD_ATTR_WITH_HINT | 11,709,567 | 3.0% | 56.0% |  |
| LOAD_CONST | 10,649,214 | 2.7% | 58.7% |  |
| POP_TOP | 10,350,778 | 2.6% | 61.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,485,735 | 2.4% | 63.8% | 0.0% |
| CALL_PY_EXACT_ARGS | 9,369,721 | 2.4% | 66.2% |  |
| POP_JUMP_IF_TRUE | 8,673,974 | 2.2% | 68.4% |  |
| RETURN_VALUE | 7,930,816 | 2.0% | 70.4% |  |
| RETURN_CONST | 7,540,694 | 1.9% | 72.3% |  |
| CALL | 6,622,899 | 1.7% | 74.0% |  |
| JUMP_BACKWARD | 5,894,200 | 1.5% | 75.5% |  |
| TO_BOOL | 5,674,294 | 1.4% | 77.0% |  |
| LOAD_FAST_LOAD_FAST | 5,575,888 | 1.4% | 78.4% |  |
| POP_JUMP_IF_NONE | 5,553,012 | 1.4% | 79.8% |  |
| LOAD_ATTR_SLOT | 5,186,772 | 1.3% | 81.1% | 0.0% |
| LOAD_GLOBAL_MODULE | 5,145,836 | 1.3% | 82.4% |  |
| CALL_PY_WITH_DEFAULTS | 4,088,580 | 1.0% | 83.5% |  |
| LOAD_FAST_CHECK | 3,840,000 | 1.0% | 84.5% |  |
| CALL_LIST_APPEND | 3,634,444 | 0.9% | 85.4% |  |
| NOP | 3,517,710 | 0.9% | 86.3% |  |
| STORE_ATTR_SLOT | 3,498,114 | 0.9% | 87.2% | 0.1% |
| COMPARE_OP_INT | 3,495,572 | 0.9% | 88.1% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 3,155,146 | 0.8% | 88.9% | 0.0% |
| TO_BOOL_INT | 2,392,506 | 0.6% | 89.5% |  |
| CALL_LEN | 2,226,084 | 0.6% | 90.1% |  |
| PUSH_NULL | 2,053,396 | 0.5% | 90.6% |  |
| LOAD_ATTR_MODULE | 1,830,428 | 0.5% | 91.0% |  |
| INTERPRETER_EXIT | 1,757,236 | 0.4% | 91.5% |  |
| BINARY_OP | 1,659,158 | 0.4% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,543,890 | 0.4% | 92.3% | 0.0% |
| BUILD_LIST | 1,246,578 | 0.3% | 92.6% |  |
| LOAD_DEREF | 1,237,010 | 0.3% | 92.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,229,646 | 0.3% | 93.3% |  |
| SEND_GEN | 1,228,570 | 0.3% | 93.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,047,444 | 0.3% | 93.8% | 0.1% |
| FOR_ITER_LIST | 1,033,884 | 0.3% | 94.1% |  |
| BUILD_TUPLE | 1,028,950 | 0.3% | 94.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,023,670 | 0.3% | 94.6% |  |
| FOR_ITER_RANGE | 1,010,834 | 0.3% | 94.9% |  |
| JUMP_FORWARD | 990,899 | 0.3% | 95.1% |  |
| YIELD_VALUE | 981,308 | 0.3% | 95.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 981,188 | 0.3% | 95.6% |  |
| TO_BOOL_NONE | 978,844 | 0.2% | 95.9% |  |
| STORE_FAST_STORE_FAST | 832,048 | 0.2% | 96.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 831,928 | 0.2% | 96.3% |  |
| COPY | 806,182 | 0.2% | 96.5% |  |
| CALL_FUNCTION_EX | 764,112 | 0.2% | 96.7% |  |
| LIST_EXTEND | 763,752 | 0.2% | 96.9% |  |
| CALL_INTRINSIC_1 | 763,752 | 0.2% | 97.1% |  |
| GET_AWAITABLE | 740,826 | 0.2% | 97.3% |  |
| END_SEND | 740,826 | 0.2% | 97.5% |  |
| COMPARE_OP | 739,302 | 0.2% | 97.7% |  |
| GET_ITER | 737,226 | 0.2% | 97.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 529,210 | 0.1% | 98.0% |  |
| STORE_ATTR_WITH_HINT | 518,640 | 0.1% | 98.1% |  |
| BINARY_SLICE | 516,012 | 0.1% | 98.2% |  |
| BINARY_OP_ADD_INT | 500,224 | 0.1% | 98.4% |  |
| RETURN_GENERATOR | 494,404 | 0.1% | 98.5% |  |
| SEND | 493,844 | 0.1% | 98.6% |  |
| CONTAINS_OP | 488,222 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 483,964 | 0.1% | 98.9% |  |
| SWAP | 295,088 | 0.1% | 99.0% |  |
| CALL_BUILTIN_CLASS | 288,248 | 0.1% | 99.0% |  |
| COPY_FREE_VARS | 262,134 | 0.1% | 99.1% |  |
| CALL_KW | 255,300 | 0.1% | 99.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 246,660 | 0.1% | 99.2% |  |
| DELETE_SUBSCR | 246,482 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 242,522 | 0.1% | 99.3% | 0.0% |
| BINARY_OP_ADD_FLOAT | 241,622 | 0.1% | 99.4% |  |
| LOAD_ATTR_PROPERTY | 241,322 | 0.1% | 99.5% |  |
| PUSH_EXC_INFO | 241,262 | 0.1% | 99.5% |  |
| POP_EXCEPT | 241,262 | 0.1% | 99.6% |  |
| CHECK_EXC_MATCH | 241,262 | 0.1% | 99.7% |  |
| MAKE_CELL | 241,140 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 240,722 | 0.1% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 240,660 | 0.1% | 99.8% |  |
| MAKE_FUNCTION | 240,660 | 0.1% | 99.9% |  |
| BUILD_SLICE | 240,482 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,088 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 27,296 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 12,360 | 0.0% | 100.0% |  |
| FOR_ITER | 12,300 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 12,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 9,890 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,018 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,778 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 6,160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 4,855 | 0.0% | 100.0% |  |
| STORE_ATTR | 3,720 | 0.0% | 100.0% |  |
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
| BINARY_OP_SUBTRACT_FLOAT | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 140 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 120 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| LIST_APPEND | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 18,427,272 | 4.7% | 4.7% |
| STORE_FAST LOAD_FAST | 14,261,055 | 3.6% | 8.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 13,492,067 | 3.4% | 11.8% |
| RESUME_CHECK LOAD_FAST | 12,626,466 | 3.2% | 15.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 11,483,662 | 2.9% | 17.9% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 9,514,219 | 2.4% | 20.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 9,271,950 | 2.4% | 22.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,628,119 | 2.2% | 24.9% |
| LOAD_FAST LOAD_ATTR | 8,172,509 | 2.1% | 27.0% |
| LOAD_FAST TO_BOOL_BOOL | 7,927,802 | 2.0% | 29.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,915,296 | 1.8% | 30.8% |
| RETURN_CONST POP_TOP | 6,273,002 | 1.6% | 32.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 6,122,528 | 1.6% | 33.9% |
| RETURN_VALUE STORE_FAST | 5,836,444 | 1.5% | 35.4% |
| TO_BOOL POP_JUMP_IF_TRUE | 5,411,734 | 1.4% | 36.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,407,458 | 1.4% | 38.2% |
| LOAD_FAST RETURN_VALUE | 5,339,036 | 1.4% | 39.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 5,310,130 | 1.4% | 40.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,175,597 | 1.3% | 42.2% |
| CALL STORE_FAST | 5,112,246 | 1.3% | 43.5% |
| LOAD_FAST TO_BOOL | 4,861,512 | 1.2% | 44.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,817,526 | 1.2% | 46.0% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_WITH_VALUES | 4,587,205 | 1.2% | 47.2% |
| LOAD_FAST CALL | 4,577,580 | 1.2% | 48.3% |
| JUMP_BACKWARD LOAD_FAST | 4,562,468 | 1.2% | 49.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 4,088,460 | 1.0% | 50.5% |
| LOAD_ATTR CALL_PY_WITH_DEFAULTS | 4,080,842 | 1.0% | 51.6% |
| LOAD_CONST LOAD_FAST | 3,727,866 | 1.0% | 52.5% |
| CALL_LIST_APPEND JUMP_BACKWARD | 3,634,264 | 0.9% | 53.5% |
| POP_TOP RETURN_CONST | 3,519,514 | 0.9% | 54.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 3,463,028 | 0.9% | 55.2% |
| LOAD_CONST STORE_FAST | 3,427,052 | 0.9% | 56.1% |
| LOAD_FAST CALL_LIST_APPEND | 3,359,334 | 0.9% | 57.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_CHECK | 3,359,214 | 0.9% | 57.8% |
| LOAD_FAST_CHECK LOAD_ATTR_METHOD_NO_DICT | 3,359,214 | 0.9% | 58.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,356,338 | 0.9% | 59.5% |
| POP_TOP LOAD_FAST | 3,267,154 | 0.8% | 60.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,254,430 | 0.8% | 61.2% |
| NOP LOAD_FAST | 3,022,170 | 0.8% | 62.0% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 2,943,094 | 0.8% | 62.7% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,860,510 | 0.7% | 63.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,777,852 | 0.7% | 64.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,022,382 | 0.5% | 64.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,980,360 | 0.5% | 65.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,977,306 | 0.5% | 65.7% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 1,961,170 | 0.5% | 66.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,829,088 | 0.5% | 66.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,815,940 | 0.5% | 67.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 1,713,688 | 0.4% | 67.5% |
| LOAD_FAST STORE_ATTR_SLOT | 1,517,754 | 0.4% | 67.9% |
| CACHE RESUME_CHECK | 1,514,956 | 0.4% | 68.3% |
| POP_TOP LOAD_CONST | 1,487,776 | 0.4% | 68.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,484,700 | 0.4% | 69.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_WITH_HINT | 1,462,028 | 0.4% | 69.4% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 1,461,908 | 0.4% | 69.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 1,394,450 | 0.4% | 70.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,389,768 | 0.4% | 70.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,365,153 | 0.3% | 70.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,345,102 | 0.3% | 71.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,297,466 | 0.3% | 71.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,269,650 | 0.3% | 71.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,258,934 | 0.3% | 72.2% |
| LOAD_FAST LOAD_CONST | 1,239,722 | 0.3% | 72.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,223,946 | 0.3% | 72.8% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 1,216,826 | 0.3% | 73.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,204,868 | 0.3% | 73.4% |
| PUSH_NULL LOAD_FAST | 1,059,138 | 0.3% | 73.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,040,468 | 0.3% | 74.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,033,994 | 0.3% | 74.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,025,118 | 0.3% | 74.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,016,836 | 0.3% | 74.8% |
| RETURN_CONST INTERPRETER_EXIT | 1,013,890 | 0.3% | 75.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,013,154 | 0.3% | 75.3% |
| STORE_FAST RETURN_CONST | 1,004,714 | 0.3% | 75.5% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 997,996 | 0.3% | 75.8% |
| POP_JUMP_IF_FALSE NOP | 996,912 | 0.3% | 76.0% |
| STORE_ATTR_SLOT LOAD_CONST | 996,778 | 0.3% | 76.3% |
| STORE_FAST JUMP_FORWARD | 984,426 | 0.3% | 76.5% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 981,188 | 0.3% | 76.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 981,184 | 0.3% | 77.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 978,844 | 0.2% | 77.3% |
| LOAD_CONST COMPARE_OP_INT | 977,764 | 0.2% | 77.5% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 977,404 | 0.2% | 77.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 831,808 | 0.2% | 78.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 831,208 | 0.2% | 78.2% |
| POP_TOP JUMP_BACKWARD | 809,660 | 0.2% | 78.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 799,502 | 0.2% | 78.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS STORE_FAST | 797,542 | 0.2% | 78.8% |
| COPY TO_BOOL_INT | 792,082 | 0.2% | 79.0% |
| LOAD_GLOBAL_MODULE BINARY_OP | 791,782 | 0.2% | 79.2% |
| RESUME_CHECK NOP | 790,746 | 0.2% | 79.4% |
| LOAD_ATTR LOAD_FAST | 784,452 | 0.2% | 79.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 781,568 | 0.2% | 79.8% |
| LOAD_FAST CALL_LEN | 780,474 | 0.2% | 80.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 780,358 | 0.2% | 80.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 772,690 | 0.2% | 80.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 770,090 | 0.2% | 80.6% |
| FOR_ITER_RANGE STORE_FAST | 769,392 | 0.2% | 80.8% |
| JUMP_BACKWARD FOR_ITER_RANGE | 769,332 | 0.2% | 81.0% |
| LOAD_ATTR PUSH_NULL | 764,132 | 0.2% | 81.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,144 | 93.2% |
| LOAD_CONST | 34,868 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 268,812 | 52.1% |
| CALL | 240,482 | 46.6% |
| STORE_FAST | 6,298 | 1.2% |
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
| RESUME_CHECK | 1,514,956 | 86.2% |
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
| LOAD_GLOBAL_MODULE | 240,782 | 99.8% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.1% |
| BUILD_TUPLE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 241,262 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 240,482 | 97.6% |
| LOAD_CONST | 6,000 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 246,482 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,842 | 34.1% |
| SEND | 246,722 | 33.3% |
| RETURN_VALUE | 241,262 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,684 | 67.4% |
| STORE_FAST | 240,842 | 32.5% |
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
| LOAD_FAST | 489,424 | 66.4% |
| CALL_BUILTIN_CLASS | 241,562 | 32.8% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 483,404 | 65.6% |
| FOR_ITER_RANGE | 241,502 | 32.8% |
| FOR_ITER | 6,200 | 0.8% |
| FOR_ITER_TUPLE | 6,060 | 0.8% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,013,890 | 57.7% |
| RETURN_VALUE | 496,204 | 28.2% |
| YIELD_VALUE | 246,842 | 14.0% |
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
| POP_JUMP_IF_FALSE | 996,912 | 28.3% |
| RESUME_CHECK | 790,746 | 22.5% |
| POP_JUMP_IF_TRUE | 487,922 | 13.9% |
| STORE_FAST | 483,784 | 13.8% |
| NOP | 481,264 | 13.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,022,170 | 85.9% |
| NOP | 481,264 | 13.7% |
| LOAD_GLOBAL_MODULE | 13,656 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 241,142 | 100.0% |
| SWAP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240,542 | 99.7% |
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
| RETURN_CONST | 6,273,002 | 60.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,297,466 | 12.5% |
| CALL_FUNCTION_EX | 763,452 | 7.4% |
| POP_JUMP_IF_FALSE | 516,912 | 5.0% |
| END_SEND | 499,684 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,519,514 | 34.0% |
| LOAD_FAST | 3,267,154 | 31.6% |
| LOAD_CONST | 1,487,776 | 14.4% |
| JUMP_BACKWARD | 809,660 | 7.8% |
| RESUME_CHECK | 494,404 | 4.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,542 | 99.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300 | 0.1% |
| BINARY_SUBSCR_DICT | 300 | 0.1% |
| RERAISE | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240,762 | 99.8% |
| LOAD_GLOBAL_BUILTIN | 440 | 0.2% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,269,650 | 61.8% |
| LOAD_ATTR | 764,132 | 37.2% |
| LOAD_DEREF | 18,054 | 0.9% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,059,138 | 51.6% |
| LOAD_FAST_LOAD_FAST | 502,018 | 24.4% |
| CALL | 491,460 | 23.9% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,504 | 99.8% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,804 | 99.9% |
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
| LOAD_FAST | 5,339,036 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 780,358 | 9.8% |
| CALL | 517,632 | 6.5% |
| LOAD_ATTR | 480,842 | 6.1% |
| BINARY_OP_ADD_INT | 253,082 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,836,444 | 73.6% |
| TO_BOOL_BOOL | 520,938 | 6.6% |
| LOAD_FAST | 517,512 | 6.5% |
| INTERPRETER_EXIT | 496,204 | 6.3% |
| POP_TOP | 254,336 | 3.2% |


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
| LOAD_FAST | 4,861,512 | 85.7% |
| LOAD_ATTR_INSTANCE_VALUE | 557,140 | 9.8% |
| LOAD_ATTR_WITH_HINT | 252,602 | 4.5% |
| TO_BOOL | 1,840 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,411,734 | 95.4% |
| POP_JUMP_IF_FALSE | 259,620 | 4.6% |
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
| LOAD_GLOBAL_MODULE | 791,782 | 47.7% |
| LOAD_ATTR_MODULE | 555,798 | 33.5% |
| LOAD_ATTR | 274,930 | 16.6% |
| POP_JUMP_IF_FALSE | 34,508 | 2.1% |
| BINARY_OP | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 550,700 | 33.2% |
| TO_BOOL_INT | 550,160 | 33.2% |
| STORE_FAST | 276,250 | 16.7% |
| BUILD_TUPLE | 274,930 | 16.6% |
| LOAD_FAST_LOAD_FAST | 5,938 | 0.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 763,212 | 61.2% |
| STORE_FAST | 241,502 | 19.4% |
| LOAD_FAST | 241,084 | 19.3% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,992 | 61.3% |
| STORE_FAST | 482,226 | 38.7% |
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
| LOAD_FAST | 240,482 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,482 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 486,962 | 47.3% |
| BINARY_OP | 274,930 | 26.7% |
| LOAD_FAST | 247,080 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 12,540 | 1.2% |
| LOAD_FAST_LOAD_FAST | 6,778 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 486,962 | 47.3% |
| CALL_LIST_APPEND | 274,930 | 26.7% |
| LOAD_CONST | 240,660 | 23.4% |
| CALL_ISINSTANCE | 12,400 | 1.2% |
| CALL_PY_EXACT_ARGS | 12,258 | 1.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,577,580 | 69.1% |
| LOAD_FAST_LOAD_FAST | 495,300 | 7.5% |
| PUSH_NULL | 491,460 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 487,802 | 7.4% |
| LOAD_CONST | 253,780 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,112,246 | 77.2% |
| RETURN_VALUE | 517,632 | 7.8% |
| POP_TOP | 248,222 | 3.7% |
| RESUME_CHECK | 247,817 | 3.7% |
| PUSH_EXC_INFO | 240,542 | 3.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 763,512 | 99.9% |
| BUILD_MAP | 240 | 0.0% |
| LOAD_FAST | 180 | 0.0% |
| DICT_MERGE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 763,452 | 99.9% |
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
| LIST_EXTEND | 763,752 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 763,512 | 100.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 255,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,782 | 96.7% |
| COPY_FREE_VARS | 5,998 | 2.3% |
| STORE_FAST | 840 | 0.3% |
| RESUME_CHECK | 600 | 0.2% |
| POP_TOP | 360 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 736,982 | 99.7% |
| COMPARE_OP | 940 | 0.1% |
| LOAD_ATTR_MODULE | 780 | 0.1% |
| LOAD_CONST | 440 | 0.1% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 737,942 | 99.8% |
| COMPARE_OP | 940 | 0.1% |
| POP_JUMP_IF_TRUE | 180 | 0.0% |
| COMPARE_OP_INT | 160 | 0.0% |
| COMPARE_OP_STR | 80 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 486,962 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 300 | 0.1% |
| BUILD_SET | 300 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 488,042 | 100.0% |
| POP_JUMP_IF_TRUE | 180 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 550,700 | 68.3% |
| CALL_LEN | 241,382 | 29.9% |
| LOAD_FAST | 12,960 | 1.6% |
| SWAP | 540 | 0.1% |
| UNARY_NOT | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 792,082 | 98.3% |
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
| CALL_PY_EXACT_ARGS | 7,798 | 3.0% |
| CALL_KW | 5,998 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,998 | 2.3% |
| LOAD_ATTR_PROPERTY | 540 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 262,014 | 100.0% |
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
| RETURN_GENERATOR | 493,804 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 240,422 | 32.5% |
| LOAD_FAST | 6,120 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,826 | 100.0% |


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
| CALL_LIST_APPEND | 3,634,264 | 61.7% |
| POP_TOP | 809,660 | 13.7% |
| JUMP_FORWARD | 480,786 | 8.2% |
| POP_JUMP_IF_FALSE | 241,744 | 4.1% |
| POP_JUMP_IF_TRUE | 240,722 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,562,468 | 77.4% |
| FOR_ITER_RANGE | 769,332 | 13.1% |
| FOR_ITER_LIST | 550,340 | 9.3% |
| FOR_ITER_TUPLE | 6,060 | 0.1% |
| FOR_ITER | 6,000 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 981,188 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,466 | 74.9% |
| SEND | 246,722 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 984,426 | 99.3% |
| POP_JUMP_IF_FALSE | 4,795 | 0.5% |
| POP_TOP | 838 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 0.0% |
| STORE_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 480,786 | 48.5% |
| LOAD_FAST | 262,976 | 26.5% |
| LOAD_GLOBAL_BUILTIN | 246,357 | 24.9% |
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
| LOAD_ATTR_SLOT | 763,212 | 99.9% |
| LOAD_FAST | 360 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 763,752 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,172,509 | 64.7% |
| LOAD_GLOBAL_MODULE | 1,713,688 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 981,184 | 7.8% |
| LOAD_ATTR_SLOT | 763,412 | 6.0% |
| LOAD_ATTR_WITH_HINT | 734,544 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 4,080,842 | 32.3% |
| CALL_PY_EXACT_ARGS | 2,943,094 | 23.3% |
| LOAD_FAST | 784,452 | 6.2% |
| PUSH_NULL | 764,132 | 6.1% |
| COMPARE_OP | 736,982 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,977,306 | 18.6% |
| POP_TOP | 1,487,776 | 14.0% |
| LOAD_FAST | 1,239,722 | 11.6% |
| STORE_ATTR_SLOT | 996,778 | 9.4% |
| GET_AWAITABLE | 740,826 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,727,866 | 35.0% |
| STORE_FAST | 3,427,052 | 32.2% |
| COMPARE_OP_INT | 977,764 | 9.2% |
| SEND_GEN | 493,984 | 4.6% |
| CALL_PY_EXACT_ARGS | 481,524 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 486,778 | 39.4% |
| STORE_FAST | 246,598 | 19.9% |
| POP_JUMP_IF_FALSE | 240,660 | 19.5% |
| LOAD_CONST | 240,300 | 19.4% |
| LOAD_ATTR | 11,996 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 721,140 | 58.3% |
| LOAD_ATTR | 240,520 | 19.4% |
| STORE_ATTR_WITH_HINT | 240,300 | 19.4% |
| PUSH_NULL | 18,054 | 1.5% |
| LOAD_FAST | 9,478 | 0.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,261,055 | 15.7% |
| RESUME_CHECK | 12,626,466 | 13.9% |
| POP_JUMP_IF_FALSE | 11,483,662 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 9,271,950 | 10.2% |
| POP_JUMP_IF_TRUE | 6,915,296 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 18,427,272 | 20.3% |
| LOAD_ATTR_WITH_HINT | 9,514,219 | 10.5% |
| LOAD_ATTR | 8,172,509 | 9.0% |
| TO_BOOL_BOOL | 7,927,802 | 8.7% |
| RETURN_VALUE | 5,339,036 | 5.9% |


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
| POP_JUMP_IF_FALSE | 3,359,214 | 87.5% |
| STORE_FAST | 240,364 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 240,364 | 6.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 39 | 0.0% |
| LOAD_ATTR | 19 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,359,214 | 87.5% |
| LOAD_FAST | 240,364 | 6.3% |
| CALL_METHOD_DESCRIPTOR_O | 240,364 | 6.3% |
| CALL | 39 | 0.0% |
| CALL_PY_EXACT_ARGS | 19 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,484,700 | 26.6% |
| STORE_FAST | 1,040,468 | 18.7% |
| POP_JUMP_IF_FALSE | 741,542 | 13.3% |
| LOAD_ATTR_METHOD_NO_DICT | 557,298 | 10.0% |
| PUSH_NULL | 502,018 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,980,360 | 35.5% |
| LOAD_ATTR_WITH_HINT | 1,462,028 | 26.2% |
| LOAD_FAST | 772,690 | 13.9% |
| CALL | 495,300 | 8.9% |
| LOAD_FAST_LOAD_FAST | 490,742 | 8.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320 | 12.9% |
| POP_TOP | 300 | 12.1% |
| STORE_FAST | 260 | 10.5% |
| LOAD_FAST | 260 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 4.8% |

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
| TO_BOOL_BOOL | 13,492,067 | 63.2% |
| COMPARE_OP_INT | 3,254,430 | 15.3% |
| TO_BOOL_INT | 1,394,450 | 6.5% |
| TO_BOOL_NONE | 978,844 | 4.6% |
| COMPARE_OP | 737,942 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,483,662 | 53.8% |
| LOAD_FAST_CHECK | 3,359,214 | 15.7% |
| LOAD_CONST | 1,977,306 | 9.3% |
| RETURN_CONST | 1,258,934 | 5.9% |
| NOP | 996,912 | 4.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,817,526 | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE | 734,526 | 13.2% |
| LOAD_ATTR | 480 | 0.0% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,310,130 | 95.6% |
| LOAD_CONST | 240,782 | 4.3% |
| RETURN_CONST | 1,140 | 0.0% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 781,568 | 76.3% |
| LOAD_ATTR_INSTANCE_VALUE | 241,202 | 23.6% |
| LOAD_ATTR_WITH_HINT | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 525,970 | 51.4% |
| LOAD_GLOBAL_MODULE | 248,678 | 24.3% |
| LOAD_FAST_LOAD_FAST | 247,742 | 24.2% |
| LOAD_GLOBAL_BUILTIN | 380 | 0.0% |
| RETURN_CONST | 360 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 5,411,734 | 62.4% |
| TO_BOOL_BOOL | 2,022,382 | 23.3% |
| TO_BOOL_INT | 997,996 | 11.5% |
| COMPARE_OP_INT | 241,142 | 2.8% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,915,296 | 79.7% |
| NOP | 487,922 | 5.6% |
| RETURN_CONST | 275,410 | 3.2% |
| LOAD_CONST | 271,740 | 3.1% |
| STORE_FAST | 241,382 | 2.8% |


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
| POP_TOP | 3,519,514 | 46.7% |
| POP_JUMP_IF_FALSE | 1,258,934 | 16.7% |
| STORE_FAST | 1,004,714 | 13.3% |
| STORE_ATTR_SLOT | 502,198 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 482,882 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,273,002 | 83.2% |
| INTERPRETER_EXIT | 1,013,890 | 13.4% |
| END_SEND | 252,842 | 3.4% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,842 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,722 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,722 | 50.0% |
| END_SEND | 246,722 | 50.0% |
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
| LOAD_FAST | 2,580 | 69.4% |
| LOAD_FAST_LOAD_FAST | 420 | 11.3% |
| STORE_ATTR | 400 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 6.5% |
| SWAP | 80 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,340 | 36.0% |
| LOAD_FAST | 1,020 | 27.4% |
| LOAD_CONST | 420 | 11.3% |
| STORE_ATTR | 400 | 10.8% |
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
| RETURN_VALUE | 5,836,444 | 28.1% |
| CALL | 5,112,246 | 24.6% |
| LOAD_CONST | 3,427,052 | 16.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 797,542 | 3.8% |
| FOR_ITER_RANGE | 769,392 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,261,055 | 68.7% |
| LOAD_FAST_LOAD_FAST | 1,040,468 | 5.0% |
| LOAD_GLOBAL_BUILTIN | 1,016,836 | 4.9% |
| RETURN_CONST | 1,004,714 | 4.8% |
| JUMP_FORWARD | 984,426 | 4.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 831,808 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 831,208 | 99.9% |
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
| LOAD_ATTR | 281,228 | 95.3% |
| BINARY_OP_ADD_INT | 6,600 | 2.2% |
| BINARY_OP_SUBTRACT_INT | 6,360 | 2.2% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |
| CALL_LEN | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 281,228 | 95.3% |
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
| YIELD_VALUE | 734,466 | 74.8% |
| SEND | 246,722 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,466 | 74.8% |
| INTERPRETER_EXIT | 246,842 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 241,382 | 99.9% |
| LOAD_FAST | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,382 | 99.9% |
| LOAD_FAST | 240 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 253,082 | 50.6% |
| CALL_LEN | 246,422 | 49.3% |
| LOAD_CONST | 640 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 253,082 | 50.6% |
| STORE_FAST | 240,422 | 48.1% |
| SWAP | 6,600 | 1.3% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

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
| LOAD_ATTR_INSTANCE_VALUE | 240,422 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,462 | 99.9% |
| STORE_FAST | 240 | 0.1% |
| COMPARE_OP | 20 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 66.7% |
| LOAD_FAST | 40 | 22.2% |
| BINARY_OP | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 66.7% |
| STORE_FAST | 60 | 33.3% |


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
| RETURN_VALUE | 6,058 | 86.3% |
| LOAD_FAST | 940 | 13.4% |
| BINARY_SUBSCR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,998 | 85.5% |
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
| LOAD_CONST | 9,870 | 99.8% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,095 | 51.5% |
| STORE_FAST | 4,735 | 47.9% |
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
| LOAD_ATTR_INSTANCE_VALUE | 240,662 | 97.6% |
| CALL_BUILTIN_CLASS | 5,998 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,662 | 97.6% |
| COPY_FREE_VARS | 5,998 | 2.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,600 | 85.9% |
| LOAD_ATTR_INSTANCE_VALUE | 40,248 | 14.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 241,562 | 83.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,088 | 13.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,998 | 2.1% |
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
| CALL_BUILTIN_CLASS | 40,088 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40,088 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240 | 40.0% |
| LOAD_FAST | 120 | 20.0% |
| BINARY_OP_MULTIPLY_FLOAT | 120 | 20.0% |
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
| LOAD_GLOBAL_BUILTIN | 14,316 | 52.4% |
| BUILD_TUPLE | 12,400 | 45.4% |
| LOAD_GLOBAL_MODULE | 280 | 1.0% |
| LOAD_ATTR_MODULE | 160 | 0.6% |
| CALL | 140 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 27,156 | 99.5% |
| TO_BOOL | 140 | 0.5% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,204,868 | 54.1% |
| LOAD_FAST | 780,474 | 35.1% |
| LOAD_ATTR_WITH_HINT | 240,662 | 10.8% |
| CALL | 40 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,914 | 23.5% |
| TO_BOOL_INT | 487,684 | 21.9% |
| LOAD_FAST | 480,962 | 21.6% |
| BINARY_OP_ADD_INT | 246,422 | 11.1% |
| COPY | 241,382 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,334 | 92.4% |
| BUILD_TUPLE | 274,930 | 7.6% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,634,264 | 100.0% |
| JUMP_FORWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,050 | 52.0% |
| LOAD_ATTR_METHOD_NO_DICT | 247,142 | 46.7% |
| LOAD_FAST_LOAD_FAST | 6,718 | 1.3% |
| RETURN_VALUE | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,252 | 98.7% |
| RETURN_VALUE | 6,838 | 1.3% |
| POP_TOP | 120 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 241,382 | 99.5% |
| LOAD_FAST | 420 | 0.2% |
| LOAD_ATTR | 300 | 0.1% |
| LOAD_CONST | 220 | 0.1% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,502 | 99.6% |
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
| LOAD_ATTR_METHOD_NO_DICT | 799,502 | 76.3% |
| LOAD_ATTR | 247,162 | 23.6% |
| CALL | 440 | 0.0% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 797,542 | 76.1% |
| TO_BOOL_BOOL | 247,122 | 23.6% |
| POP_TOP | 780 | 0.1% |
| RETURN_VALUE | 540 | 0.1% |
| LOAD_FAST | 420 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,033,994 | 67.0% |
| BINARY_SLICE | 268,812 | 17.4% |
| LOAD_FAST_CHECK | 240,364 | 15.6% |
| CALL | 480 | 0.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,297,466 | 84.0% |
| CALL_PY_EXACT_ARGS | 240,364 | 15.6% |
| RETURN_VALUE | 6,000 | 0.4% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 2,943,094 | 31.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,860,510 | 30.5% |
| LOAD_FAST | 1,815,940 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 770,090 | 8.2% |
| LOAD_CONST | 481,524 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,628,119 | 92.1% |
| RETURN_GENERATOR | 493,504 | 5.3% |
| MAKE_CELL | 240,300 | 2.6% |
| COPY_FREE_VARS | 7,798 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,080,842 | 99.8% |
| LOAD_FAST | 6,718 | 0.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,088,460 | 100.0% |
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
| LOAD_FAST | 4,735 | 97.5% |
| LOAD_ATTR_SLOT | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,735 | 97.5% |
| RETURN_VALUE | 120 | 2.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 1,461,908 | 41.8% |
| LOAD_CONST | 977,764 | 28.0% |
| LOAD_GLOBAL_MODULE | 241,382 | 6.9% |
| LOAD_FAST | 240,662 | 6.9% |
| BINARY_OP_MULTIPLY_INT | 240,462 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,254,430 | 93.1% |
| POP_JUMP_IF_TRUE | 241,142 | 6.9% |


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
| JUMP_BACKWARD | 550,340 | 53.2% |
| GET_ITER | 483,404 | 46.8% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 549,860 | 53.2% |
| RETURN_CONST | 241,562 | 23.4% |
| LOAD_FAST | 241,382 | 23.3% |
| STORE_FAST | 780 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 769,332 | 76.1% |
| GET_ITER | 241,502 | 23.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 769,392 | 76.1% |
| LOAD_CONST | 241,382 | 23.9% |
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
| LOAD_FAST | 18,427,272 | 99.9% |
| LOAD_FAST_LOAD_FAST | 7,038 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,718 | 0.0% |
| LOAD_ATTR | 1,180 | 0.0% |
| COPY | 760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,122,528 | 33.2% |
| TO_BOOL_BOOL | 3,463,028 | 18.8% |
| CALL_LEN | 1,204,868 | 6.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,025,118 | 5.6% |
| LOAD_ATTR | 981,184 | 5.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,122,528 | 51.5% |
| LOAD_FAST_CHECK | 3,359,214 | 28.3% |
| LOAD_FAST | 1,389,768 | 11.7% |
| LOAD_ATTR_WITH_HINT | 494,044 | 4.2% |
| LOAD_ATTR | 282,108 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,271,950 | 78.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 799,502 | 6.7% |
| CALL_PY_EXACT_ARGS | 770,090 | 6.5% |
| LOAD_FAST_LOAD_FAST | 557,298 | 4.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 247,142 | 2.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 4,587,205 | 48.4% |
| LOAD_FAST | 3,356,338 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,025,118 | 10.8% |
| LOAD_ATTR_SLOT | 508,116 | 5.4% |
| RETURN_VALUE | 6,918 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,407,458 | 57.0% |
| CALL_PY_EXACT_ARGS | 2,860,510 | 30.2% |
| LOAD_FAST_LOAD_FAST | 495,000 | 5.2% |
| LOAD_CONST | 481,026 | 5.1% |
| LOAD_GLOBAL_MODULE | 240,562 | 2.5% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,829,088 | 99.9% |
| LOAD_ATTR | 1,220 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,269,650 | 69.4% |
| BINARY_OP | 555,798 | 30.4% |
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
| LOAD_FAST | 241,182 | 99.9% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,782 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,175,597 | 99.8% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 5,095 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,365,153 | 26.3% |
| TO_BOOL_NONE | 977,404 | 18.8% |
| LOAD_ATTR | 763,412 | 14.7% |
| LIST_EXTEND | 763,212 | 14.7% |
| BUILD_LIST | 763,212 | 14.7% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,514,219 | 81.3% |
| LOAD_FAST_LOAD_FAST | 1,462,028 | 12.5% |
| LOAD_DEREF | 721,140 | 6.2% |
| COPY | 12,120 | 0.1% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,587,205 | 39.2% |
| TO_BOOL_BOOL | 1,961,170 | 16.7% |
| COMPARE_OP_INT | 1,461,908 | 12.5% |
| LOAD_GLOBAL_MODULE | 1,216,826 | 10.4% |
| LOAD_ATTR | 734,544 | 6.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,016,836 | 32.2% |
| POP_JUMP_IF_FALSE | 477,207 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 345,658 | 11.0% |
| RESUME_CHECK | 310,626 | 9.8% |
| LOAD_FAST | 267,178 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,777,852 | 88.0% |
| LOAD_GLOBAL_BUILTIN | 345,658 | 11.0% |
| CALL_ISINSTANCE | 14,316 | 0.5% |
| BUILD_TUPLE | 12,540 | 0.4% |
| LOAD_DEREF | 3,360 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,345,102 | 26.1% |
| LOAD_ATTR_WITH_HINT | 1,216,826 | 23.6% |
| RESUME_CHECK | 1,013,154 | 19.7% |
| LOAD_ATTR | 494,002 | 9.6% |
| POP_TOP | 282,068 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,829,088 | 35.5% |
| LOAD_ATTR | 1,713,688 | 33.3% |
| BINARY_OP | 791,782 | 15.4% |
| COMPARE_OP_INT | 241,382 | 4.7% |
| CALL_PY_EXACT_ARGS | 241,342 | 4.7% |


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
| CALL_PY_EXACT_ARGS | 8,628,119 | 51.7% |
| CALL_PY_WITH_DEFAULTS | 4,088,460 | 24.5% |
| CACHE | 1,514,956 | 9.1% |
| SEND_GEN | 734,466 | 4.4% |
| POP_TOP | 494,404 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,626,466 | 75.6% |
| LOAD_GLOBAL_MODULE | 1,013,154 | 6.1% |
| JUMP_BACKWARD_NO_INTERRUPT | 981,188 | 5.9% |
| NOP | 790,746 | 4.7% |
| LOAD_DEREF | 486,778 | 2.9% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,466 | 59.8% |
| LOAD_CONST | 493,984 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,466 | 59.8% |
| POP_TOP | 494,104 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,223,946 | 99.5% |
| LOAD_FAST_LOAD_FAST | 3,360 | 0.3% |
| STORE_ATTR | 1,340 | 0.1% |
| SWAP | 760 | 0.1% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 496,622 | 40.4% |
| RETURN_CONST | 482,882 | 39.3% |
| NOP | 240,422 | 19.6% |
| LOAD_CONST | 5,160 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,380 | 0.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,980,360 | 56.6% |
| LOAD_FAST | 1,517,754 | 43.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,484,700 | 42.4% |
| LOAD_CONST | 996,778 | 28.5% |
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
| LOAD_ATTR | 6,298 | 92.9% |
| LOAD_CONST | 280 | 4.1% |
| LOAD_FAST | 160 | 2.4% |
| STORE_SUBSCR | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,358 | 93.8% |
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
| LOAD_FAST | 7,927,802 | 51.1% |
| LOAD_ATTR_INSTANCE_VALUE | 3,463,028 | 22.3% |
| LOAD_ATTR_WITH_HINT | 1,961,170 | 12.6% |
| LOAD_ATTR_SLOT | 1,365,153 | 8.8% |
| RETURN_VALUE | 520,938 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,492,067 | 87.0% |
| POP_JUMP_IF_TRUE | 2,022,382 | 13.0% |
| UNARY_NOT | 300 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 792,082 | 33.1% |
| BINARY_OP | 550,160 | 23.0% |
| CALL_LEN | 487,684 | 20.4% |
| LOAD_FAST | 281,410 | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE | 281,110 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,394,450 | 58.3% |
| POP_JUMP_IF_TRUE | 997,996 | 41.7% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 483,844 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 483,844 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 977,404 | 99.9% |
| LOAD_FAST | 860 | 0.1% |
| LOAD_ATTR | 540 | 0.1% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 978,844 | 100.0% |


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
| FOR_ITER_LIST | 549,860 | 66.1% |
| STORE_FAST | 281,228 | 33.8% |
| RETURN_VALUE | 320 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 831,808 | 100.0% |
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
|          hit |        17208 | 73.6% |

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
|          hit |         6778 | 97.4% |

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
| specialization.deferred |      5671354 | 22.6% |
|          hit |     19370543 | 77.3% |
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
| specialization.deferred |      1658278 | 62.5% |
|          hit |       995228 | 37.5% |

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
| specialization.deferred |      6616059 | 21.9% |
|          hit |     23531567 | 78.0% |
|         miss |         1920 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,980 | 43.6% |
| Failure | 3,860 | 56.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 1,160 | 30.1% |
| class no vectorcall | 500 | 13.0% |
| code complex parameters | 460 | 11.9% |
| meth descr method fastcall keywords | 360 | 9.3% |
| cfunc noargs | 360 | 9.3% |
| no dict | 260 | 6.7% |
| class mutable | 200 | 5.2% |
| cfunc varargs keywords | 160 | 4.1% |
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
| specialization.deferred |       738122 | 17.4% |
|          hit |      3500547 | 82.6% |
|         miss |          120 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 20.3% |
| Failure | 940 | 79.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 660 | 70.2% |
| other | 160 | 17.0% |
| different types | 60 | 6.4% |
| tuple | 40 | 4.3% |
| bool | 20 | 2.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        12120 | 0.6% |
|          hit |      2056838 | 99.4% |

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
| specialization.deferred |     12614112 | 17.7% |
|          hit |     58785118 | 82.3% |
|         miss |         1080 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,760 | 39.7% |
| Failure | 7,220 | 60.3% |

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
|          hit |      8300922 | 100.0% |
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
| specialization.deferred |       493444 | 28.6% |
|          hit |      1228570 | 71.3% |

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
|          hit |      5244000 | 99.9% |
|         miss |         2400 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 77.0% |
| Failure | 400 | 23.0% |

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
|          hit |       832108 | 100.0% |

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
| Basic | 181,058,690 | 46.2% |
| Not specialized | 70,843,533 | 18.1% |
| Specialized | 140,319,787 | 35.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 12,614,112 | 45.4% |
| CALL | 6,616,059 | 23.8% |
| TO_BOOL | 5,671,354 | 20.4% |
| BINARY_OP | 1,658,278 | 6.0% |
| COMPARE_OP | 738,122 | 2.7% |
| SEND | 493,444 | 1.8% |
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
| Calls to PyEval_EvalDefault | 1,757,236 | 10.2% |
| Calls to Python functions inlined | 15,430,708 | 89.8% |
| Calls via PyEval_EvalFrame (total) | 1,757,236 | 10.2% |
| Calls via PyEval_EvalFrame (vector) | 1,510,094 | 8.8% |
| Calls via PyEval_EvalFrame (generator) | 247,142 | 1.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,510,094 | 8.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,080 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,764 | 2.9% |
| Frames pushed | 15,712,652 | 91.4% |
| Frame objects created | 482,344 | 2.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,005,290 | 41.3% |
| Frees to freelist | 11,011,588 |  |
| Allocations | 15,653,042 | 58.7% |
| Allocations to 512 bytes | 10,844,266 | 40.7% |
| Allocations to 4 kbytes | 241,018 | 0.9% |
| Allocations over 4 kbytes | 4,567,758 | 17.1% |
| Frees | 15,956,491 |  |
| New values | 780 |  |
| Interpreter increfs | 167,461,635 | 76.0% |
| Interpreter decrefs | 185,959,517 | 75.8% |
| Increfs | 52,796,999 | 24.0% |
| Decrefs | 59,341,869 | 24.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 120 | 15.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,246,150 |  |
| Method cache misses | 74,218 |  |
| Method cache collisions | 74,427 |  |
| Method cache dunder hits | 782,771 |  |
| Method cache dunder misses | 217 |  |


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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-10-04
