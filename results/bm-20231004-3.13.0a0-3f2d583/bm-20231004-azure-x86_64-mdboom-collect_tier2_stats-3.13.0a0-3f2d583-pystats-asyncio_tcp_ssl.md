
# Pystats results

- benchmark: asyncio_tcp_ssl
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 77,654,987 | 22.2% | 22.2% |  |
| POP_JUMP_IF_FALSE | 19,983,695 | 5.7% | 28.0% |  |
| STORE_FAST | 19,653,411 | 5.6% | 33.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 17,387,451 | 5.0% | 38.6% |  |
| RESUME_CHECK | 15,913,595 | 4.6% | 43.1% |  |
| TO_BOOL_BOOL | 13,984,069 | 4.0% | 47.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 10,570,110 | 3.0% | 50.2% |  |
| LOAD_CONST | 10,408,940 | 3.0% | 53.1% |  |
| POP_TOP | 10,350,739 | 3.0% | 56.1% |  |
| POP_JUMP_IF_TRUE | 8,387,444 | 2.4% | 58.5% |  |
| LOAD_ATTR | 8,176,980 | 2.3% | 60.8% |  |
| CALL_PY_EXACT_ARGS | 8,108,022 | 2.3% | 63.2% |  |
| RETURN_VALUE | 7,930,840 | 2.3% | 65.4% |  |
| LOAD_ATTR_WITH_HINT | 7,623,322 | 2.2% | 67.6% |  |
| RETURN_CONST | 7,540,673 | 2.2% | 69.8% |  |
| CALL | 6,622,906 | 1.9% | 71.7% |  |
| ENTER_EXECUTOR | 5,887,340 | 1.7% | 73.4% |  |
| TO_BOOL | 5,634,160 | 1.6% | 75.0% |  |
| LOAD_FAST_LOAD_FAST | 5,575,903 | 1.6% | 76.6% |  |
| POP_JUMP_IF_NONE | 5,553,015 | 1.6% | 78.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,911,803 | 1.4% | 79.6% | 0.0% |
| LOAD_GLOBAL_MODULE | 4,825,223 | 1.4% | 81.0% |  |
| CALL_PY_WITH_DEFAULTS | 4,088,583 | 1.2% | 82.1% |  |
| CALL_LIST_APPEND | 3,634,438 | 1.0% | 83.2% |  |
| LOAD_FAST_CHECK | 3,599,696 | 1.0% | 84.2% |  |
| STORE_ATTR_SLOT | 3,498,144 | 1.0% | 85.2% | 0.1% |
| COMPARE_OP_INT | 3,495,569 | 1.0% | 86.2% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 3,131,374 | 0.9% | 87.1% | 0.0% |
| LOAD_ATTR_SLOT | 3,099,386 | 0.9% | 88.0% | 0.0% |
| NOP | 2,995,886 | 0.9% | 88.8% |  |
| TO_BOOL_INT | 2,324,186 | 0.7% | 89.5% |  |
| CALL_LEN | 2,226,078 | 0.6% | 90.1% |  |
| LOAD_ATTR_MODULE | 1,796,277 | 0.5% | 90.7% |  |
| INTERPRETER_EXIT | 1,757,233 | 0.5% | 91.2% |  |
| BINARY_OP | 1,590,841 | 0.5% | 91.6% |  |
| PUSH_NULL | 1,531,575 | 0.4% | 92.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,303,571 | 0.4% | 92.4% | 0.0% |
| LOAD_DEREF | 1,237,025 | 0.4% | 92.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,229,646 | 0.4% | 93.1% |  |
| SEND_GEN | 1,228,570 | 0.4% | 93.5% |  |
| POP_JUMP_IF_NOT_NONE | 1,023,670 | 0.3% | 93.8% |  |
| BUILD_TUPLE | 1,017,067 | 0.3% | 94.1% |  |
| JUMP_FORWARD | 990,908 | 0.3% | 94.4% |  |
| YIELD_VALUE | 981,308 | 0.3% | 94.6% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 981,188 | 0.3% | 94.9% |  |
| TO_BOOL_NONE | 978,844 | 0.3% | 95.2% |  |
| COPY | 772,028 | 0.2% | 95.4% |  |
| CALL_FUNCTION_EX | 764,106 | 0.2% | 95.6% |  |
| GET_AWAITABLE | 740,826 | 0.2% | 95.8% |  |
| END_SEND | 740,826 | 0.2% | 96.1% |  |
| COMPARE_OP | 739,305 | 0.2% | 96.3% |  |
| GET_ITER | 737,226 | 0.2% | 96.5% |  |
| STORE_FAST_STORE_FAST | 729,607 | 0.2% | 96.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 729,487 | 0.2% | 96.9% |  |
| BUILD_LIST | 724,748 | 0.2% | 97.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 525,545 | 0.2% | 97.3% | 0.2% |
| STORE_ATTR_WITH_HINT | 518,640 | 0.1% | 97.4% |  |
| BINARY_SLICE | 516,006 | 0.1% | 97.6% |  |
| BINARY_OP_ADD_INT | 500,224 | 0.1% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 495,065 | 0.1% | 97.8% |  |
| RETURN_GENERATOR | 494,404 | 0.1% | 98.0% |  |
| SEND | 493,844 | 0.1% | 98.1% |  |
| CONTAINS_OP | 488,222 | 0.1% | 98.3% |  |
| FOR_ITER_LIST | 484,024 | 0.1% | 98.4% |  |
| TO_BOOL_LIST | 483,964 | 0.1% | 98.5% |  |
| CALL_BUILTIN_CLASS | 288,245 | 0.1% | 98.6% |  |
| COPY_FREE_VARS | 262,143 | 0.1% | 98.7% |  |
| SWAP | 260,943 | 0.1% | 98.8% |  |
| CALL_KW | 255,303 | 0.1% | 98.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 246,663 | 0.1% | 98.9% |  |
| DELETE_SUBSCR | 246,482 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 242,522 | 0.1% | 99.1% | 0.0% |
| LIST_EXTEND | 241,922 | 0.1% | 99.1% |  |
| CALL_INTRINSIC_1 | 241,922 | 0.1% | 99.2% |  |
| FOR_ITER_RANGE | 241,622 | 0.1% | 99.3% |  |
| BINARY_OP_ADD_FLOAT | 241,622 | 0.1% | 99.3% |  |
| LOAD_ATTR_PROPERTY | 241,322 | 0.1% | 99.4% |  |
| PUSH_EXC_INFO | 241,262 | 0.1% | 99.5% |  |
| POP_EXCEPT | 241,262 | 0.1% | 99.5% |  |
| CHECK_EXC_MATCH | 241,262 | 0.1% | 99.6% |  |
| MAKE_CELL | 241,140 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 240,722 | 0.1% | 99.7% |  |
| SET_FUNCTION_ATTRIBUTE | 240,660 | 0.1% | 99.8% |  |
| MAKE_FUNCTION | 240,660 | 0.1% | 99.9% |  |
| BUILD_SLICE | 240,482 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,082 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 21,362 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 12,360 | 0.0% | 100.0% |  |
| FOR_ITER | 12,300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 9,896 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,021 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 6,839 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,781 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 6,160 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 6,120 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 4,858 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,371,669 | 5.0% | 5.0% |
| STORE_FAST LOAD_FAST | 13,177,190 | 3.8% | 8.7% |
| RESUME_CHECK LOAD_FAST | 12,374,285 | 3.5% | 12.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 12,207,814 | 3.5% | 15.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 10,165,312 | 2.9% | 18.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 9,237,793 | 2.6% | 21.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,606,839 | 2.2% | 23.5% |
| LOAD_FAST TO_BOOL_BOOL | 7,446,779 | 2.1% | 25.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,628,766 | 1.9% | 27.6% |
| RETURN_CONST POP_TOP | 6,272,984 | 1.8% | 29.4% |
| RETURN_VALUE STORE_FAST | 5,836,456 | 1.7% | 31.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,600,635 | 1.6% | 32.6% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 5,427,974 | 1.6% | 34.2% |
| TO_BOOL POP_JUMP_IF_TRUE | 5,371,637 | 1.5% | 35.7% |
| LOAD_FAST RETURN_VALUE | 5,339,054 | 1.5% | 37.2% |
| POP_JUMP_IF_NONE LOAD_FAST | 5,310,133 | 1.5% | 38.8% |
| CALL STORE_FAST | 5,112,252 | 1.5% | 40.2% |
| LOAD_FAST TO_BOOL | 4,821,430 | 1.4% | 41.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,817,529 | 1.4% | 43.0% |
| LOAD_FAST CALL | 4,577,586 | 1.3% | 44.3% |
| LOAD_FAST LOAD_ATTR | 4,264,220 | 1.2% | 45.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 4,088,463 | 1.2% | 46.7% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 3,840,000 | 1.1% | 47.8% |
| LOAD_CONST LOAD_FAST | 3,727,884 | 1.1% | 48.9% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 3,634,138 | 1.0% | 49.9% |
| POP_TOP RETURN_CONST | 3,519,499 | 1.0% | 50.9% |
| LOAD_CONST STORE_FAST | 3,427,052 | 1.0% | 51.9% |
| LOAD_FAST CALL_LIST_APPEND | 3,359,334 | 1.0% | 52.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_CHECK | 3,359,214 | 1.0% | 53.8% |
| LOAD_FAST_CHECK LOAD_ATTR_METHOD_NO_DICT | 3,359,214 | 1.0% | 54.8% |
| POP_TOP LOAD_FAST | 3,267,151 | 0.9% | 55.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,254,427 | 0.9% | 56.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 3,088,208 | 0.9% | 57.5% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 2,943,094 | 0.8% | 58.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 2,941,201 | 0.8% | 59.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 2,868,630 | 0.8% | 60.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,771,906 | 0.8% | 60.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,619,182 | 0.8% | 61.6% |
| NOP LOAD_FAST | 2,500,340 | 0.7% | 62.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,980,372 | 0.6% | 62.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,977,315 | 0.6% | 63.4% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 1,961,170 | 0.6% | 64.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,804,060 | 0.5% | 64.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,794,937 | 0.5% | 65.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,775,955 | 0.5% | 65.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 1,701,808 | 0.5% | 66.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,555,578 | 0.4% | 66.5% |
| LOAD_FAST STORE_ATTR_SLOT | 1,517,772 | 0.4% | 66.9% |
| CACHE RESUME_CHECK | 1,514,953 | 0.4% | 67.3% |
| POP_TOP LOAD_CONST | 1,487,770 | 0.4% | 67.8% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,484,709 | 0.4% | 68.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_WITH_HINT | 1,462,028 | 0.4% | 68.6% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 1,461,908 | 0.4% | 69.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 1,326,136 | 0.4% | 69.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,297,451 | 0.4% | 69.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,276,794 | 0.4% | 70.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,269,650 | 0.4% | 70.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,258,934 | 0.4% | 70.9% |
| LOAD_FAST LOAD_CONST | 1,239,734 | 0.4% | 71.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,223,946 | 0.4% | 71.6% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 1,210,886 | 0.3% | 71.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,204,868 | 0.3% | 72.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,040,468 | 0.3% | 72.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,033,988 | 0.3% | 72.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,019,187 | 0.3% | 73.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,016,830 | 0.3% | 73.4% |
| RETURN_CONST INTERPRETER_EXIT | 1,013,887 | 0.3% | 73.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,013,148 | 0.3% | 74.0% |
| STORE_FAST RETURN_CONST | 1,004,708 | 0.3% | 74.3% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 997,990 | 0.3% | 74.6% |
| POP_JUMP_IF_FALSE NOP | 996,906 | 0.3% | 74.9% |
| STORE_ATTR_SLOT LOAD_CONST | 996,787 | 0.3% | 75.2% |
| STORE_FAST JUMP_FORWARD | 984,432 | 0.3% | 75.4% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 981,188 | 0.3% | 75.7% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 978,844 | 0.3% | 76.0% |
| LOAD_CONST COMPARE_OP_INT | 977,770 | 0.3% | 76.3% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 977,404 | 0.3% | 76.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 975,244 | 0.3% | 76.8% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 843,251 | 0.2% | 77.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 833,772 | 0.2% | 77.3% |
| POP_TOP ENTER_EXECUTOR | 803,408 | 0.2% | 77.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 781,568 | 0.2% | 77.8% |
| LOAD_FAST CALL_LEN | 780,468 | 0.2% | 78.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 780,367 | 0.2% | 78.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 772,687 | 0.2% | 78.4% |
| CALL_FUNCTION_EX POP_TOP | 763,446 | 0.2% | 78.7% |
| COPY TO_BOOL_INT | 757,928 | 0.2% | 78.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 757,628 | 0.2% | 79.1% |
| LOAD_ATTR LOAD_FAST | 744,367 | 0.2% | 79.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 741,545 | 0.2% | 79.5% |
| GET_AWAITABLE LOAD_CONST | 740,826 | 0.2% | 79.7% |
| COMPARE_OP POP_JUMP_IF_FALSE | 737,945 | 0.2% | 79.9% |
| LOAD_ATTR COMPARE_OP | 736,985 | 0.2% | 80.2% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR | 734,544 | 0.2% | 80.4% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 734,526 | 0.2% | 80.6% |
| YIELD_VALUE YIELD_VALUE | 734,466 | 0.2% | 80.8% |
| SEND_GEN RESUME_CHECK | 734,466 | 0.2% | 81.0% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 734,466 | 0.2% | 81.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 729,367 | 0.2% | 81.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 728,767 | 0.2% | 81.6% |


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
| LOAD_CONST | 34,862 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 268,803 | 52.1% |
| CALL | 240,482 | 46.6% |
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
| RESUME_CHECK | 1,514,953 | 86.2% |
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
| RETURN_CONST | 1,013,887 | 57.7% |
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
| POP_JUMP_IF_FALSE | 996,906 | 33.3% |
| POP_JUMP_IF_TRUE | 487,925 | 16.3% |
| STORE_FAST | 483,784 | 16.1% |
| NOP | 481,264 | 16.1% |
| RESUME_CHECK | 268,925 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,500,340 | 83.5% |
| NOP | 481,264 | 16.1% |
| LOAD_GLOBAL_MODULE | 13,662 | 0.5% |
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
| ENTER_EXECUTOR | 240,542 | 99.7% |
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
| RETURN_CONST | 6,272,984 | 60.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,297,451 | 12.5% |
| CALL_FUNCTION_EX | 763,446 | 7.4% |
| END_SEND | 499,684 | 4.8% |
| SEND_GEN | 494,104 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,519,499 | 34.0% |
| LOAD_FAST | 3,267,151 | 31.6% |
| LOAD_CONST | 1,487,770 | 14.4% |
| ENTER_EXECUTOR | 803,408 | 7.8% |
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
| LOAD_ATTR_MODULE | 1,269,650 | 82.9% |
| LOAD_ATTR | 242,302 | 15.8% |
| LOAD_DEREF | 18,063 | 1.2% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 537,308 | 35.1% |
| LOAD_FAST_LOAD_FAST | 502,024 | 32.8% |
| CALL | 491,463 | 32.1% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 253,082 | 51.2% |
| ENTER_EXECUTOR | 240,422 | 48.6% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |

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
| LOAD_FAST | 5,339,054 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 780,367 | 9.8% |
| CALL | 517,626 | 6.5% |
| LOAD_ATTR | 480,842 | 6.1% |
| BINARY_OP_ADD_INT | 253,082 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,836,456 | 73.6% |
| TO_BOOL_BOOL | 520,944 | 6.6% |
| LOAD_FAST | 517,506 | 6.5% |
| INTERPRETER_EXIT | 496,204 | 6.3% |
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
| LOAD_FAST | 4,821,430 | 85.6% |
| LOAD_ATTR_INSTANCE_VALUE | 557,128 | 9.9% |
| LOAD_ATTR_WITH_HINT | 252,602 | 4.5% |
| TO_BOOL | 1,800 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,371,637 | 95.3% |
| POP_JUMP_IF_FALSE | 259,623 | 4.6% |
| TO_BOOL | 1,800 | 0.0% |
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
| LOAD_GLOBAL_MODULE | 757,628 | 47.6% |
| LOAD_ATTR_MODULE | 521,647 | 32.8% |
| LOAD_ATTR | 274,924 | 17.3% |
| POP_JUMP_IF_FALSE | 34,502 | 2.2% |
| BINARY_OP | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 516,546 | 32.5% |
| TO_BOOL_INT | 516,006 | 32.4% |
| STORE_FAST | 276,244 | 17.4% |
| BUILD_TUPLE | 274,924 | 17.3% |
| LOAD_FAST_LOAD_FAST | 5,941 | 0.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,502 | 33.3% |
| LOAD_ATTR_SLOT | 241,382 | 33.3% |
| LOAD_FAST | 241,084 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 482,226 | 66.5% |
| LOAD_FAST | 242,162 | 33.4% |
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
| LOAD_ATTR | 486,962 | 47.9% |
| BINARY_OP | 274,924 | 27.0% |
| LOAD_FAST | 241,140 | 23.7% |
| LOAD_FAST_LOAD_FAST | 6,781 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 6,600 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 486,962 | 47.9% |
| CALL_LIST_APPEND | 274,924 | 27.0% |
| LOAD_CONST | 240,660 | 23.7% |
| CALL_ISINSTANCE | 6,460 | 0.6% |
| CALL_PY_EXACT_ARGS | 6,321 | 0.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,577,586 | 69.1% |
| LOAD_FAST_LOAD_FAST | 495,303 | 7.5% |
| PUSH_NULL | 491,463 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 487,805 | 7.4% |
| LOAD_CONST | 253,783 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,112,252 | 77.2% |
| RETURN_VALUE | 517,626 | 7.8% |
| POP_TOP | 248,222 | 3.7% |
| RESUME_CHECK | 247,821 | 3.7% |
| PUSH_EXC_INFO | 240,542 | 3.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 521,824 | 68.3% |
| CALL_INTRINSIC_1 | 241,682 | 31.6% |
| BUILD_MAP | 240 | 0.0% |
| LOAD_FAST | 180 | 0.0% |
| DICT_MERGE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 763,446 | 99.9% |
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
| LIST_EXTEND | 241,922 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 241,682 | 99.9% |
| LOAD_CONST | 240 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 255,303 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,782 | 96.7% |
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
| LOAD_ATTR | 736,985 | 99.7% |
| COMPARE_OP | 940 | 0.1% |
| LOAD_ATTR_MODULE | 780 | 0.1% |
| LOAD_CONST | 440 | 0.1% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 737,945 | 99.8% |
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
| BINARY_OP | 516,546 | 66.9% |
| CALL_LEN | 241,382 | 31.3% |
| LOAD_FAST | 12,960 | 1.7% |
| SWAP | 540 | 0.1% |
| UNARY_NOT | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 757,928 | 98.2% |
| LOAD_ATTR_WITH_HINT | 12,120 | 1.6% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 3,634,138 | 61.7% |
| POP_TOP | 803,408 | 13.6% |
| JUMP_FORWARD | 480,786 | 8.2% |
| POP_JUMP_IF_FALSE | 241,322 | 4.1% |
| POP_JUMP_IF_TRUE | 240,722 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 3,840,000 | 65.2% |
| CALL_FUNCTION_EX | 521,824 | 8.9% |
| LOAD_FAST | 275,222 | 4.7% |
| RESUME_CHECK | 241,322 | 4.1% |
| LOAD_CONST | 241,322 | 4.1% |


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
| POP_TOP | 6,240 | 91.2% |
| POP_JUMP_IF_FALSE | 359 | 5.2% |
| CALL_LIST_APPEND | 120 | 1.8% |
| LIST_APPEND | 60 | 0.9% |
| ENTER_EXECUTOR | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 6,000 | 87.7% |
| FOR_ITER_LIST | 480 | 7.0% |
| LOAD_FAST | 179 | 2.6% |
| FOR_ITER_RANGE | 120 | 1.8% |
| FOR_ITER_TUPLE | 60 | 0.9% |


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
| STORE_FAST | 984,432 | 99.3% |
| POP_JUMP_IF_FALSE | 4,798 | 0.5% |
| POP_TOP | 838 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 0.0% |
| STORE_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 480,786 | 48.5% |
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
| LOAD_ATTR_SLOT | 241,382 | 99.8% |
| LOAD_FAST | 360 | 0.1% |
| BINARY_SLICE | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 241,922 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,264,220 | 52.1% |
| LOAD_GLOBAL_MODULE | 1,701,808 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 975,244 | 11.9% |
| LOAD_ATTR_WITH_HINT | 734,544 | 9.0% |
| LOAD_ATTR_SLOT | 241,582 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,943,094 | 36.0% |
| LOAD_FAST | 744,367 | 9.1% |
| COMPARE_OP | 736,985 | 9.0% |
| LOAD_CONST | 487,984 | 6.0% |
| BUILD_TUPLE | 486,962 | 6.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,977,315 | 19.0% |
| POP_TOP | 1,487,770 | 14.3% |
| LOAD_FAST | 1,239,734 | 11.9% |
| STORE_ATTR_SLOT | 996,787 | 9.6% |
| GET_AWAITABLE | 740,826 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,727,884 | 35.8% |
| STORE_FAST | 3,427,052 | 32.9% |
| COMPARE_OP_INT | 977,770 | 9.4% |
| SEND_GEN | 493,984 | 4.7% |
| CALL_PY_EXACT_ARGS | 481,524 | 4.6% |


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
| STORE_FAST | 13,177,190 | 17.0% |
| RESUME_CHECK | 12,374,285 | 15.9% |
| POP_JUMP_IF_FALSE | 10,165,312 | 13.1% |
| LOAD_ATTR_METHOD_NO_DICT | 9,237,793 | 11.9% |
| POP_JUMP_IF_TRUE | 6,628,766 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,371,669 | 22.4% |
| TO_BOOL_BOOL | 7,446,779 | 9.6% |
| LOAD_ATTR_WITH_HINT | 5,427,974 | 7.0% |
| RETURN_VALUE | 5,339,054 | 6.9% |
| TO_BOOL | 4,821,430 | 6.2% |


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
| POP_JUMP_IF_FALSE | 3,359,214 | 93.3% |
| STORE_FAST | 240,364 | 6.7% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 38 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,359,214 | 93.3% |
| LOAD_FAST | 240,364 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 0.0% |
| CALL | 40 | 0.0% |
| CALL_PY_EXACT_ARGS | 18 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,484,709 | 26.6% |
| STORE_FAST | 1,040,468 | 18.7% |
| POP_JUMP_IF_FALSE | 741,545 | 13.3% |
| LOAD_ATTR_METHOD_NO_DICT | 557,289 | 10.0% |
| PUSH_NULL | 502,024 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,980,372 | 35.5% |
| LOAD_ATTR_WITH_HINT | 1,462,028 | 26.2% |
| LOAD_FAST | 772,687 | 13.9% |
| CALL | 495,303 | 8.9% |
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
| TO_BOOL_BOOL | 12,207,814 | 61.1% |
| COMPARE_OP_INT | 3,254,427 | 16.3% |
| TO_BOOL_INT | 1,326,136 | 6.6% |
| TO_BOOL_NONE | 978,844 | 4.9% |
| COMPARE_OP | 737,945 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,165,312 | 50.9% |
| LOAD_FAST_CHECK | 3,359,214 | 16.8% |
| LOAD_CONST | 1,977,315 | 9.9% |
| RETURN_CONST | 1,258,934 | 6.3% |
| NOP | 996,906 | 5.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,817,529 | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE | 734,526 | 13.2% |
| LOAD_ATTR | 480 | 0.0% |
| LOAD_ATTR_WITH_HINT | 240 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,310,133 | 95.6% |
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
| LOAD_FAST | 525,967 | 51.4% |
| LOAD_GLOBAL_MODULE | 248,681 | 24.3% |
| LOAD_FAST_LOAD_FAST | 247,742 | 24.2% |
| LOAD_GLOBAL_BUILTIN | 380 | 0.0% |
| RETURN_CONST | 360 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 5,371,637 | 64.0% |
| TO_BOOL_BOOL | 1,775,955 | 21.2% |
| TO_BOOL_INT | 997,990 | 11.9% |
| COMPARE_OP_INT | 241,142 | 2.9% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,628,766 | 79.0% |
| NOP | 487,925 | 5.8% |
| RETURN_CONST | 275,404 | 3.3% |
| LOAD_CONST | 271,743 | 3.2% |
| STORE_FAST | 241,382 | 2.9% |


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
| POP_TOP | 3,519,499 | 46.7% |
| POP_JUMP_IF_FALSE | 1,258,934 | 16.7% |
| STORE_FAST | 1,004,708 | 13.3% |
| STORE_ATTR_SLOT | 502,204 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 482,882 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,272,984 | 83.2% |
| INTERPRETER_EXIT | 1,013,887 | 13.4% |
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
| RETURN_VALUE | 5,836,456 | 29.7% |
| CALL | 5,112,252 | 26.0% |
| LOAD_CONST | 3,427,052 | 17.4% |
| CALL_LEN | 522,905 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 516,606 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,177,190 | 67.0% |
| LOAD_FAST_LOAD_FAST | 1,040,468 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,016,830 | 5.2% |
| RETURN_CONST | 1,004,708 | 5.1% |
| JUMP_FORWARD | 984,432 | 5.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 729,367 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 728,767 | 99.9% |
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
| LOAD_ATTR | 247,083 | 94.7% |
| BINARY_OP_ADD_INT | 6,600 | 2.5% |
| BINARY_OP_SUBTRACT_INT | 6,360 | 2.4% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |
| CALL_LEN | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 247,083 | 94.7% |
| STORE_ATTR_WITH_HINT | 12,120 | 4.6% |
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
| LOAD_CONST | 9,876 | 99.8% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,098 | 51.5% |
| STORE_FAST | 4,738 | 47.9% |
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
| CALL_BUILTIN_CLASS | 6,001 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,662 | 97.6% |
| COPY_FREE_VARS | 6,001 | 2.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,603 | 85.9% |
| LOAD_ATTR_INSTANCE_VALUE | 40,242 | 14.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 241,562 | 83.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,082 | 13.9% |
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
| CALL_BUILTIN_CLASS | 40,082 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40,082 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 14,322 | 67.0% |
| BUILD_TUPLE | 6,460 | 30.2% |
| LOAD_GLOBAL_MODULE | 280 | 1.3% |
| LOAD_ATTR_MODULE | 160 | 0.7% |
| CALL | 140 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 21,222 | 99.3% |
| TO_BOOL | 140 | 0.7% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,204,868 | 54.1% |
| LOAD_FAST | 780,468 | 35.1% |
| LOAD_ATTR_WITH_HINT | 240,662 | 10.8% |
| CALL | 40 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,905 | 23.5% |
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
| BUILD_TUPLE | 274,924 | 7.6% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,634,138 | 100.0% |
| JUMP_FORWARD | 120 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 247,142 | 49.9% |
| LOAD_FAST | 240,902 | 48.7% |
| LOAD_FAST_LOAD_FAST | 6,721 | 1.4% |
| RETURN_VALUE | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 488,104 | 98.6% |
| RETURN_VALUE | 6,841 | 1.4% |
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
| LOAD_ATTR_METHOD_NO_DICT | 277,603 | 52.8% |
| LOAD_ATTR | 247,162 | 47.0% |
| CALL | 440 | 0.1% |
| LOAD_FAST | 300 | 0.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 275,643 | 52.4% |
| TO_BOOL_BOOL | 247,122 | 47.0% |
| POP_TOP | 780 | 0.1% |
| RETURN_VALUE | 540 | 0.1% |
| LOAD_FAST | 420 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,033,988 | 79.3% |
| BINARY_SLICE | 268,803 | 20.6% |
| CALL | 480 | 0.0% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_FAST_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,297,451 | 99.5% |
| RETURN_VALUE | 6,000 | 0.5% |
| PUSH_EXC_INFO | 60 | 0.0% |
| CALL_PY_EXACT_ARGS | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 2,943,094 | 36.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,619,182 | 32.3% |
| LOAD_FAST | 1,804,060 | 22.3% |
| LOAD_CONST | 481,524 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 248,263 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,606,839 | 93.8% |
| RETURN_GENERATOR | 253,082 | 3.1% |
| MAKE_CELL | 240,300 | 3.0% |
| COPY_FREE_VARS | 7,801 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,840,000 | 93.9% |
| LOAD_ATTR | 240,842 | 5.9% |
| LOAD_FAST | 6,721 | 0.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,088,463 | 100.0% |
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
| LOAD_FAST | 4,738 | 97.5% |
| LOAD_ATTR_SLOT | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,738 | 97.5% |
| RETURN_VALUE | 120 | 2.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 1,461,908 | 41.8% |
| LOAD_CONST | 977,770 | 28.0% |
| LOAD_GLOBAL_MODULE | 241,382 | 6.9% |
| LOAD_FAST | 240,662 | 6.9% |
| BINARY_OP_MULTIPLY_INT | 240,462 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,254,427 | 93.1% |
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
| GET_ITER | 483,404 | 99.9% |
| JUMP_BACKWARD | 480 | 0.1% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 481,564 | 99.5% |
| STORE_FAST | 780 | 0.2% |
| RETURN_CONST | 780 | 0.2% |
| LOAD_FAST | 600 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 241,502 | 100.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,562 | 100.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 6,060 | 99.0% |
| JUMP_BACKWARD | 60 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,060 | 99.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.7% |
| LOAD_GLOBAL | 20 | 0.3% |


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
| LOAD_FAST | 17,371,669 | 99.9% |
| LOAD_FAST_LOAD_FAST | 7,041 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,721 | 0.0% |
| LOAD_ATTR | 1,180 | 0.0% |
| COPY | 760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,600,635 | 32.2% |
| TO_BOOL_BOOL | 2,941,201 | 16.9% |
| CALL_LEN | 1,204,868 | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,019,187 | 5.9% |
| LOAD_ATTR | 975,244 | 5.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,600,635 | 53.0% |
| LOAD_FAST_CHECK | 3,359,214 | 31.8% |
| LOAD_FAST | 833,772 | 7.9% |
| LOAD_ATTR_WITH_HINT | 494,044 | 4.7% |
| LOAD_ATTR | 282,105 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,237,793 | 87.4% |
| LOAD_FAST_LOAD_FAST | 557,289 | 5.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 277,603 | 2.6% |
| CALL_PY_EXACT_ARGS | 248,263 | 2.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 247,142 | 2.3% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,868,630 | 58.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,019,187 | 20.7% |
| LOAD_ATTR_SLOT | 508,125 | 10.3% |
| LOAD_ATTR_WITH_HINT | 506,900 | 10.3% |
| RETURN_VALUE | 6,921 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,619,182 | 53.3% |
| LOAD_FAST | 1,555,578 | 31.7% |
| LOAD_FAST_LOAD_FAST | 495,003 | 10.1% |
| LOAD_CONST | 240,722 | 4.9% |
| CALL | 640 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,794,937 | 99.9% |
| LOAD_ATTR | 1,220 | 0.1% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,269,650 | 70.7% |
| BINARY_OP | 521,647 | 29.0% |
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
| ENTER_EXECUTOR | 240,304 | 99.6% |
| LOAD_FAST | 878 | 0.4% |
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
| LOAD_FAST | 3,088,208 | 99.6% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.2% |
| BINARY_SUBSCR_LIST_INT | 5,098 | 0.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 977,404 | 31.5% |
| TO_BOOL_BOOL | 843,251 | 27.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 508,125 | 16.4% |
| LOAD_ATTR | 241,582 | 7.8% |
| LIST_EXTEND | 241,382 | 7.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,427,974 | 71.2% |
| LOAD_FAST_LOAD_FAST | 1,462,028 | 19.2% |
| LOAD_DEREF | 721,140 | 9.5% |
| COPY | 12,120 | 0.2% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,961,170 | 25.7% |
| COMPARE_OP_INT | 1,461,908 | 19.2% |
| LOAD_GLOBAL_MODULE | 1,210,886 | 15.9% |
| LOAD_ATTR | 734,544 | 9.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 506,900 | 6.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,016,830 | 32.5% |
| POP_JUMP_IF_FALSE | 477,204 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 333,766 | 10.7% |
| RESUME_CHECK | 304,686 | 9.7% |
| LOAD_FAST | 261,244 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,771,906 | 88.5% |
| LOAD_GLOBAL_BUILTIN | 333,766 | 10.7% |
| CALL_ISINSTANCE | 14,322 | 0.5% |
| BUILD_TUPLE | 6,600 | 0.2% |
| LOAD_DEREF | 3,360 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,276,794 | 26.5% |
| LOAD_ATTR_WITH_HINT | 1,210,886 | 25.1% |
| RESUME_CHECK | 1,013,148 | 21.0% |
| LOAD_ATTR | 482,122 | 10.0% |
| POP_TOP | 282,065 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,794,937 | 37.2% |
| LOAD_ATTR | 1,701,808 | 35.3% |
| BINARY_OP | 757,628 | 15.7% |
| COMPARE_OP_INT | 241,382 | 5.0% |
| CHECK_EXC_MATCH | 240,782 | 5.0% |


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
| CALL_PY_EXACT_ARGS | 7,606,839 | 47.8% |
| CALL_PY_WITH_DEFAULTS | 4,088,463 | 25.7% |
| CACHE | 1,514,953 | 9.5% |
| SEND_GEN | 734,466 | 4.6% |
| POP_TOP | 494,404 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,374,285 | 77.8% |
| LOAD_GLOBAL_MODULE | 1,013,148 | 6.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 981,188 | 6.2% |
| LOAD_DEREF | 486,781 | 3.1% |
| LOAD_CONST | 483,002 | 3.0% |


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
| LOAD_FAST_LOAD_FAST | 1,980,372 | 56.6% |
| LOAD_FAST | 1,517,772 | 43.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,484,709 | 42.4% |
| LOAD_CONST | 996,787 | 28.5% |
| LOAD_FAST | 502,444 | 14.4% |
| RETURN_CONST | 502,204 | 14.4% |
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
| ENTER_EXECUTOR | 6,000 | 1.2% |
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
| LOAD_FAST | 7,446,779 | 53.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,941,201 | 21.0% |
| LOAD_ATTR_WITH_HINT | 1,961,170 | 14.0% |
| LOAD_ATTR_SLOT | 843,251 | 6.0% |
| RETURN_VALUE | 520,944 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,207,814 | 87.3% |
| POP_JUMP_IF_TRUE | 1,775,955 | 12.7% |
| UNARY_NOT | 300 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 757,928 | 32.6% |
| BINARY_OP | 516,006 | 22.2% |
| CALL_LEN | 487,684 | 21.0% |
| LOAD_FAST | 281,404 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 281,104 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,326,136 | 57.1% |
| POP_JUMP_IF_TRUE | 997,990 | 42.9% |
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
| FOR_ITER_LIST | 481,564 | 66.0% |
| STORE_FAST | 247,083 | 33.9% |
| RETURN_VALUE | 320 | 0.0% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 729,367 | 100.0% |
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
|          hit |        17217 | 73.6% |

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
| specialization.deferred |      5631260 | 24.1% |
|          hit |     17771543 | 75.9% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,100 | 37.9% |
| Failure | 1,800 | 62.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 1,160 | 64.4% |
| sequence | 340 | 18.9% |
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
| specialization.deferred |      1589961 | 61.5% |
|          hit |       995228 | 38.5% |

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
| specialization.deferred |      6616066 | 23.6% |
|          hit |     21467559 | 76.4% |
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
| specialization.deferred |       738125 | 17.4% |
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
| specialization.deferred |        12120 | 1.6% |
|          hit |       731766 | 98.3% |

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
| specialization.deferred |      8166180 | 15.2% |
|          hit |     45629611 | 84.8% |
|         miss |         1080 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,760 | 44.1% |
| Failure | 6,040 | 55.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 2,820 | 46.7% |
| metaclass attribute | 1,360 | 22.5% |
| not managed dict | 800 | 13.2% |
| method | 620 | 10.3% |
| shadowed | 200 | 3.3% |
| non object slot | 100 | 1.7% |
| class method obj | 60 | 1.0% |
| class attr simple | 40 | 0.7% |
| class attr descriptor | 20 | 0.3% |
| builtin class method | 20 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      7956537 | 100.0% |
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
|          hit |      5244030 | 99.9% |
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
|          hit |       729667 | 100.0% |

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
| Basic | 169,486,895 | 48.5% |
| Not specialized | 58,759,525 | 16.8% |
| Specialized | 120,949,468 | 34.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 8,166,180 | 35.1% |
| CALL | 6,616,066 | 28.4% |
| TO_BOOL | 5,631,260 | 24.2% |
| BINARY_OP | 1,589,961 | 6.8% |
| COMPARE_OP | 738,125 | 3.2% |
| SEND | 493,444 | 2.1% |
| FOR_ITER | 12,120 | 0.1% |
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
| Calls to PyEval_EvalDefault | 1,757,233 | 11.0% |
| Calls to Python functions inlined | 14,169,022 | 89.0% |
| Calls via PyEval_EvalFrame (total) | 1,757,233 | 11.0% |
| Calls via PyEval_EvalFrame (vector) | 1,510,091 | 9.5% |
| Calls via PyEval_EvalFrame (generator) | 247,142 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,510,091 | 9.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,080 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,764 | 3.1% |
| Frames pushed | 15,712,655 | 98.7% |
| Frame objects created | 482,344 | 3.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,005,272 | 41.3% |
| Frees to freelist | 11,011,573 |  |
| Allocations | 15,652,992 | 58.7% |
| Allocations to 512 bytes | 10,844,231 | 40.7% |
| Allocations to 4 kbytes | 241,018 | 0.9% |
| Allocations over 4 kbytes | 4,567,743 | 17.1% |
| Frees | 15,956,412 |  |
| New values | 780 |  |
| Interpreter increfs | 147,095,836 | 65.1% |
| Interpreter decrefs | 169,891,409 | 67.7% |
| Increfs | 78,982,924 | 34.9% |
| Decrefs | 81,230,035 | 32.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 120 | 15.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,313,346 |  |
| Method cache misses | 5,918 |  |
| Method cache collisions | 7,432 |  |
| Method cache dunder hits | 781,461 |  |
| Method cache dunder misses | 1,527 |  |


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
| Optimization attempts | 360 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 5,887,340 |  |
| Uops executed | 119,482,328 | 20 |
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
| <= 8 | 729,004 | 12.4% |
| <= 16 | 4,081,502 | 69.3% |
| <= 32 | 240,482 | 4.1% |
| <= 64 | 308,588 | 5.2% |
| <= 128 | 527,764 | 9.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 32,893,088 | 27.5% | 27.5% |
| _GUARD_TYPE_VERSION | 13,121,270 | 11.0% | 38.5% |
| LOAD_FAST | 13,068,720 | 10.9% | 49.4% |
| _EXIT_TRACE | 5,887,340 | 4.9% | 54.4% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 4,573,928 | 3.8% | 58.2% |
| _GUARD_KEYS_VERSION | 4,573,928 | 3.8% | 62.0% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 4,573,928 | 3.8% | 65.9% |
| LOAD_ATTR | 4,447,928 | 3.7% | 69.6% |
| _LOAD_ATTR_WITH_HINT | 4,086,244 | 3.4% | 73.0% |
| _CHECK_ATTR_WITH_HINT | 4,086,244 | 3.4% | 76.4% |
| _POP_JUMP_IF_TRUE | 2,883,930 | 2.4% | 78.8% |
| _LOAD_ATTR_SLOT | 2,087,356 | 1.7% | 80.6% |
| TO_BOOL_BOOL | 1,530,674 | 1.3% | 81.9% |
| STORE_FAST | 1,322,844 | 1.1% | 83.0% |
| _LOAD_ATTR_METHOD_NO_DICT | 1,318,154 | 1.1% | 84.1% |
| _SAVE_CURRENT_IP | 1,261,692 | 1.1% | 85.1% |
| _PUSH_FRAME | 1,261,692 | 1.1% | 86.2% |
| _INIT_CALL_PY_EXACT_ARGS | 1,261,692 | 1.1% | 87.2% |
| _CHECK_STACK_SPACE | 1,261,692 | 1.1% | 88.3% |
| _CHECK_PEP_523 | 1,261,692 | 1.1% | 89.4% |
| _CHECK_FUNCTION_EXACT_ARGS | 1,261,692 | 1.1% | 90.4% |
| _LOAD_ATTR_INSTANCE_VALUE | 1,055,588 | 0.9% | 91.3% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,055,588 | 0.9% | 92.2% |
| RESUME_CHECK | 779,948 | 0.7% | 92.8% |
| _ITER_CHECK_RANGE | 769,206 | 0.6% | 93.5% |
| _IS_ITER_EXHAUSTED_RANGE | 769,206 | 0.6% | 94.1% |
| POP_TOP | 728,946 | 0.6% | 94.7% |
| _ITER_CHECK_LIST | 549,848 | 0.5% | 95.2% |
| _IS_ITER_EXHAUSTED_LIST | 549,848 | 0.5% | 95.6% |
| _ITER_NEXT_RANGE | 527,824 | 0.4% | 96.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 521,884 | 0.4% | 96.5% |
| PUSH_NULL | 521,824 | 0.4% | 97.0% |
| LIST_EXTEND | 521,824 | 0.4% | 97.4% |
| CALL_INTRINSIC_1 | 521,824 | 0.4% | 97.8% |
| BUILD_LIST | 521,824 | 0.4% | 98.3% |
| _GUARD_GLOBALS_VERSION | 344,346 | 0.3% | 98.6% |
| _LOAD_GLOBAL_MODULE | 320,586 | 0.3% | 98.8% |
| LOAD_FAST_CHECK | 240,304 | 0.2% | 99.0% |
| LOAD_CONST | 240,304 | 0.2% | 99.2% |
| CALL_METHOD_DESCRIPTOR_O | 240,304 | 0.2% | 99.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 102,426 | 0.1% | 99.5% |
| _POP_JUMP_IF_FALSE | 80,164 | 0.1% | 99.6% |
| _ITER_NEXT_LIST | 68,284 | 0.1% | 99.6% |
| TO_BOOL_INT | 68,284 | 0.1% | 99.7% |
| BINARY_OP | 68,284 | 0.1% | 99.8% |
| TO_BOOL | 40,082 | 0.0% | 99.8% |
| _LOAD_ATTR_MODULE | 34,142 | 0.0% | 99.8% |
| _CHECK_ATTR_MODULE | 34,142 | 0.0% | 99.8% |
| SWAP | 34,142 | 0.0% | 99.9% |
| COPY | 34,142 | 0.0% | 99.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 34,142 | 0.0% | 99.9% |
| _LOAD_GLOBAL_BUILTINS | 23,760 | 0.0% | 100.0% |
| _GUARD_BUILTINS_VERSION | 23,760 | 0.0% | 100.0% |
| BUILD_TUPLE | 11,880 | 0.0% | 100.0% |
| _ITER_CHECK_TUPLE | 6,000 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 6,000 | 0.0% | 100.0% |
| CALL_ISINSTANCE | 5,940 | 0.0% | 100.0% |


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
Stats gathered on: 2023-10-04
