
# Pystats results

- benchmark: tornado_http
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 74,104,562 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 25,153,427 | 7.0% | 27.7% | 0.1% |
| RESUME_CHECK | 19,585,841 | 5.5% | 33.2% | 0.0% |
| LOAD_CONST | 15,995,673 | 4.5% | 37.7% |  |
| POP_JUMP_IF_FALSE | 13,927,189 | 3.9% | 41.6% |  |
| RETURN_VALUE | 11,572,054 | 3.2% | 44.8% |  |
| CALL_PY_EXACT_ARGS | 10,877,225 | 3.0% | 47.8% | 0.6% |
| STORE_FAST | 10,797,361 | 3.0% | 50.9% |  |
| LOAD_GLOBAL_MODULE | 10,546,424 | 2.9% | 53.8% | 0.0% |
| LOAD_FAST_LOAD_FAST | 10,268,313 | 2.9% | 56.7% |  |
| POP_TOP | 10,133,290 | 2.8% | 59.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,753,936 | 2.4% | 62.0% | 0.9% |
| TO_BOOL_BOOL | 8,741,184 | 2.4% | 64.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 8,118,692 | 2.3% | 66.7% | 0.1% |
| RETURN_CONST | 7,905,709 | 2.2% | 68.9% |  |
| LOAD_GLOBAL_BUILTIN | 6,955,489 | 1.9% | 70.8% | 0.1% |
| CALL | 6,252,724 | 1.7% | 72.6% |  |
| INTERPRETER_EXIT | 5,725,240 | 1.6% | 74.2% |  |
| LOAD_ATTR | 5,587,111 | 1.6% | 75.7% |  |
| POP_JUMP_IF_NONE | 5,411,864 | 1.5% | 77.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,338,463 | 1.2% | 78.5% | 0.6% |
| POP_JUMP_IF_TRUE | 4,090,461 | 1.1% | 79.6% |  |
| STORE_ATTR_SLOT | 3,620,106 | 1.0% | 80.6% | 19.2% |
| COMPARE_OP_INT | 3,393,693 | 0.9% | 81.6% | 0.0% |
| PUSH_NULL | 3,218,340 | 0.9% | 82.5% |  |
| LOAD_ATTR_MODULE | 3,083,654 | 0.9% | 83.3% | 0.0% |
| NOP | 2,990,984 | 0.8% | 84.1% |  |
| LOAD_ATTR_SLOT | 2,760,594 | 0.8% | 84.9% | 10.7% |
| COPY | 2,398,308 | 0.7% | 85.6% |  |
| LOAD_DEREF | 2,094,036 | 0.6% | 86.2% |  |
| CALL_ISINSTANCE | 2,085,543 | 0.6% | 86.8% |  |
| CALL_BUILTIN_FAST | 1,654,760 | 0.5% | 87.2% |  |
| POP_JUMP_IF_NOT_NONE | 1,651,015 | 0.5% | 87.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,512,631 | 0.4% | 88.1% | 8.3% |
| TO_BOOL_NONE | 1,418,789 | 0.4% | 88.5% | 1.6% |
| BUILD_TUPLE | 1,389,026 | 0.4% | 88.9% |  |
| SWAP | 1,382,676 | 0.4% | 89.3% |  |
| ENTER_EXECUTOR | 1,264,261 | 0.4% | 89.6% |  |
| TO_BOOL | 1,260,231 | 0.4% | 90.0% |  |
| BINARY_OP | 1,105,037 | 0.3% | 90.3% |  |
| BINARY_OP_ADD_INT | 1,083,945 | 0.3% | 90.6% |  |
| CALL_FUNCTION_EX | 1,080,646 | 0.3% | 90.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,001,257 | 0.3% | 91.2% | 3.7% |
| CALL_LEN | 987,431 | 0.3% | 91.5% |  |
| STORE_FAST_STORE_FAST | 968,345 | 0.3% | 91.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 957,320 | 0.3% | 92.0% |  |
| BINARY_SUBSCR_DICT | 904,469 | 0.3% | 92.2% |  |
| BUILD_LIST | 887,247 | 0.2% | 92.5% |  |
| BINARY_OP_SUBTRACT_INT | 837,603 | 0.2% | 92.7% |  |
| CONTAINS_OP | 799,620 | 0.2% | 92.9% |  |
| BUILD_MAP | 793,620 | 0.2% | 93.2% |  |
| TO_BOOL_INT | 790,547 | 0.2% | 93.4% | 0.8% |
| GET_ITER | 790,082 | 0.2% | 93.6% |  |
| COPY_FREE_VARS | 781,913 | 0.2% | 93.8% |  |
| LOAD_ATTR_WITH_HINT | 764,616 | 0.2% | 94.0% | 2.1% |
| JUMP_FORWARD | 742,580 | 0.2% | 94.3% |  |
| LOAD_ATTR_CLASS | 733,220 | 0.2% | 94.5% | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 727,245 | 0.2% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 712,497 | 0.2% | 94.9% |  |
| YIELD_VALUE | 577,520 | 0.2% | 95.0% |  |
| IS_OP | 568,900 | 0.2% | 95.2% |  |
| CALL_PY_WITH_DEFAULTS | 568,645 | 0.2% | 95.3% |  |
| STORE_SUBSCR_DICT | 565,080 | 0.2% | 95.5% |  |
| BINARY_SLICE | 554,160 | 0.2% | 95.6% |  |
| BINARY_SUBSCR_GETITEM | 492,680 | 0.1% | 95.8% |  |
| DICT_MERGE | 480,760 | 0.1% | 95.9% |  |
| CALL_KW | 463,065 | 0.1% | 96.1% |  |
| GET_AWAITABLE | 456,000 | 0.1% | 96.2% |  |
| PUSH_EXC_INFO | 453,464 | 0.1% | 96.3% |  |
| POP_EXCEPT | 453,344 | 0.1% | 96.4% |  |
| END_SEND | 444,000 | 0.1% | 96.6% |  |
| CHECK_EXC_MATCH | 443,674 | 0.1% | 96.7% |  |
| FOR_ITER_LIST | 425,027 | 0.1% | 96.8% | 0.0% |
| JUMP_BACKWARD | 386,860 | 0.1% | 96.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 372,480 | 0.1% | 97.0% | 3.2% |
| MAKE_FUNCTION | 365,721 | 0.1% | 97.1% |  |
| MAKE_CELL | 363,301 | 0.1% | 97.2% |  |
| FOR_ITER | 357,069 | 0.1% | 97.3% |  |
| COMPARE_OP_FLOAT | 348,140 | 0.1% | 97.4% | 0.0% |
| BINARY_SUBSCR | 342,720 | 0.1% | 97.5% |  |
| SEND | 338,220 | 0.1% | 97.6% |  |
| RETURN_GENERATOR | 337,000 | 0.1% | 97.7% |  |
| EXIT_INIT_CHECK | 324,640 | 0.1% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 324,640 | 0.1% | 97.9% |  |
| LIST_EXTEND | 314,157 | 0.1% | 98.0% |  |
| CALL_INTRINSIC_1 | 302,137 | 0.1% | 98.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 293,919 | 0.1% | 98.1% | 46.5% |
| TO_BOOL_STR | 289,500 | 0.1% | 98.2% | 2.0% |
| STORE_ATTR | 289,100 | 0.1% | 98.3% |  |
| SEND_GEN | 287,800 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 277,940 | 0.1% | 98.5% | 0.0% |
| FOR_ITER_GEN | 275,940 | 0.1% | 98.5% |  |
| CALL_LIST_APPEND | 256,628 | 0.1% | 98.6% |  |
| CALL_BUILTIN_CLASS | 247,066 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 242,920 | 0.1% | 98.7% |  |
| BEFORE_WITH | 233,885 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 229,280 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 228,740 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 212,703 | 0.1% | 99.0% |  |
| DELETE_FAST | 208,325 | 0.1% | 99.0% |  |
| STORE_FAST_LOAD_FAST | 206,500 | 0.1% | 99.1% |  |
| EXTENDED_ARG | 206,360 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 205,260 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 194,280 | 0.1% | 99.3% |  |
| COMPARE_OP | 185,217 | 0.1% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 168,000 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 139,033 | 0.0% | 99.4% | 0.1% |
| BINARY_OP_ADD_FLOAT | 121,957 | 0.0% | 99.4% |  |
| STORE_DEREF | 121,560 | 0.0% | 99.5% |  |
| LOAD_ATTR_PROPERTY | 120,560 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 120,440 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 119,980 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 119,960 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 108,700 | 0.0% | 99.6% | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 92,001 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 86,660 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 84,280 | 0.0% | 99.7% |  |
| LOAD_FAST_AND_CLEAR | 73,440 | 0.0% | 99.7% |  |
| BUILD_SLICE | 72,060 | 0.0% | 99.8% |  |
| RERAISE | 72,020 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_LIST_INT | 68,684 | 0.0% | 99.8% | 0.1% |
| FORMAT_SIMPLE | 60,400 | 0.0% | 99.8% |  |
| CONVERT_VALUE | 60,320 | 0.0% | 99.8% |  |
| UNARY_INVERT | 60,180 | 0.0% | 99.8% |  |
| END_FOR | 59,980 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 59,012 | 0.0% | 99.9% | 9.0% |
| CALL_BUILTIN_O | 56,697 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 48,240 | 0.0% | 99.9% | 0.1% |
| LOAD_FAST_CHECK | 40,022 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 31,286 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 28,720 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 28,102 | 0.0% | 99.9% | 0.9% |
| RAISE_VARARGS | 24,420 | 0.0% | 100.0% |  |
| BUILD_STRING | 24,240 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 23,960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 13,960 | 0.0% | 100.0% |  |
| LIST_APPEND | 13,100 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 13,004 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 12,240 | 0.0% | 100.0% |  |
| UNARY_NOT | 12,140 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 12,080 | 0.0% | 100.0% |  |
| BUILD_SET | 12,020 | 0.0% | 100.0% |  |
| RESUME | 9,300 | 0.0% | 100.0% | 12.8% |
| LOAD_NAME | 4,500 | 0.0% | 100.0% |  |
| STORE_NAME | 4,480 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 1,440 | 0.0% | 100.0% |  |
| IMPORT_FROM | 1,280 | 0.0% | 100.0% |  |
| IMPORT_NAME | 1,140 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 880 | 0.0% | 100.0% |  |
| CALL_STR_1 | 360 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 240 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 220 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 100 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 60 | 0.0% | 100.0% |  |
| SET_UPDATE | 20 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,774,116 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 11,390,698 | 3.2% | 9.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,203,466 | 2.9% | 12.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,299,477 | 2.0% | 14.2% |
| STORE_FAST LOAD_FAST | 6,647,858 | 1.9% | 16.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,366,845 | 1.8% | 17.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,985,104 | 1.7% | 19.5% |
| CACHE RESUME_CHECK | 5,376,256 | 1.5% | 21.0% |
| RETURN_CONST POP_TOP | 5,220,343 | 1.5% | 22.4% |
| LOAD_CONST LOAD_FAST | 5,174,570 | 1.4% | 23.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,140,289 | 1.4% | 25.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,942,391 | 1.4% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,469,942 | 1.2% | 27.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,461,635 | 1.2% | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 4,173,536 | 1.2% | 30.4% |
| POP_TOP LOAD_FAST | 3,925,038 | 1.1% | 31.5% |
| RETURN_VALUE INTERPRETER_EXIT | 3,735,115 | 1.0% | 32.5% |
| LOAD_FAST LOAD_ATTR | 3,601,439 | 1.0% | 33.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,344,885 | 0.9% | 34.4% |
| LOAD_FAST LOAD_CONST | 3,337,724 | 0.9% | 35.4% |
| LOAD_FAST RETURN_VALUE | 3,170,481 | 0.9% | 36.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,068,514 | 0.9% | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 3,035,568 | 0.8% | 38.0% |
| POP_TOP RETURN_CONST | 2,958,222 | 0.8% | 38.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,813,565 | 0.8% | 39.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,777,672 | 0.8% | 40.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,763,531 | 0.8% | 41.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,691,182 | 0.8% | 41.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,660,981 | 0.7% | 42.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 2,608,270 | 0.7% | 43.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,275,722 | 0.6% | 44.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 2,249,566 | 0.6% | 44.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,242,439 | 0.6% | 45.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,181,612 | 0.6% | 45.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,138,519 | 0.6% | 46.4% |
| RETURN_VALUE STORE_FAST | 2,136,179 | 0.6% | 47.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,039,684 | 0.6% | 47.6% |
| LOAD_FAST CALL | 2,006,235 | 0.6% | 48.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,992,573 | 0.6% | 48.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,968,303 | 0.6% | 49.3% |
| CALL STORE_FAST | 1,947,347 | 0.5% | 49.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,919,828 | 0.5% | 50.4% |
| RETURN_VALUE TO_BOOL_BOOL | 1,887,222 | 0.5% | 50.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,884,359 | 0.5% | 51.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,880,223 | 0.5% | 51.9% |
| LOAD_FAST STORE_ATTR_SLOT | 1,808,891 | 0.5% | 52.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,797,788 | 0.5% | 52.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,738,557 | 0.5% | 53.4% |
| LOAD_CONST COMPARE_OP_INT | 1,717,024 | 0.5% | 53.9% |
| RETURN_CONST INTERPRETER_EXIT | 1,712,485 | 0.5% | 54.4% |
| NOP LOAD_FAST | 1,695,284 | 0.5% | 54.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,681,942 | 0.5% | 55.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,673,096 | 0.5% | 55.8% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,484,889 | 0.4% | 56.2% |
| PUSH_NULL LOAD_FAST | 1,361,339 | 0.4% | 56.6% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,303,986 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,280,717 | 0.4% | 57.3% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 1,214,534 | 0.3% | 57.7% |
| LOAD_CONST STORE_FAST | 1,210,270 | 0.3% | 58.0% |
| RESUME_CHECK NOP | 1,203,664 | 0.3% | 58.3% |
| LOAD_ATTR LOAD_FAST | 1,177,627 | 0.3% | 58.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,165,752 | 0.3% | 59.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,131,323 | 0.3% | 59.3% |
| LOAD_FAST COPY | 1,117,388 | 0.3% | 59.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,093,580 | 0.3% | 59.9% |
| LOAD_CONST LOAD_CONST | 1,081,417 | 0.3% | 60.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,064,057 | 0.3% | 60.5% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,057,955 | 0.3% | 60.8% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,056,275 | 0.3% | 61.1% |
| STORE_ATTR_SLOT LOAD_CONST | 1,047,824 | 0.3% | 61.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,047,515 | 0.3% | 61.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,043,920 | 0.3% | 62.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,008,424 | 0.3% | 62.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 997,280 | 0.3% | 62.5% |
| CALL POP_TOP | 990,381 | 0.3% | 62.8% |
| RETURN_VALUE RETURN_VALUE | 973,720 | 0.3% | 63.1% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 953,897 | 0.3% | 63.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 927,442 | 0.3% | 63.6% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 924,388 | 0.3% | 63.9% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 924,388 | 0.3% | 64.1% |
| POP_TOP LOAD_CONST | 916,983 | 0.3% | 64.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 901,060 | 0.3% | 64.6% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 894,124 | 0.2% | 64.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 875,265 | 0.2% | 65.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 872,725 | 0.2% | 65.4% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 855,964 | 0.2% | 65.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 849,895 | 0.2% | 65.9% |
| LOAD_FAST CALL_BUILTIN_FAST | 837,640 | 0.2% | 66.1% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 827,995 | 0.2% | 66.3% |
| CALL LOAD_FAST | 825,257 | 0.2% | 66.6% |
| CALL_BUILTIN_FAST STORE_FAST | 814,460 | 0.2% | 66.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 813,214 | 0.2% | 67.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 797,400 | 0.2% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 791,180 | 0.2% | 67.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 785,360 | 0.2% | 67.7% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 763,644 | 0.2% | 67.9% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 760,630 | 0.2% | 68.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 734,522 | 0.2% | 68.3% |
| COPY_FREE_VARS RESUME_CHECK | 732,353 | 0.2% | 68.5% |
| PUSH_NULL CALL | 731,468 | 0.2% | 68.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 311,940 | 56.3% |
| LOAD_CONST | 193,620 | 34.9% |
| LOAD_FAST | 48,540 | 8.8% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 251,960 | 45.5% |
| STORE_FAST | 132,340 | 23.9% |
| CALL_PY_EXACT_ARGS | 60,200 | 10.9% |
| GET_ITER | 36,240 | 6.5% |
| RETURN_VALUE | 24,000 | 4.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,376,256 | 93.7% |
| COPY_FREE_VARS | 238,164 | 4.2% |
| POP_TOP | 97,060 | 1.7% |
| MAKE_CELL | 12,360 | 0.2% |
| RETURN_GENERATOR | 12,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 112,425 | 48.1% |
| RETURN_VALUE | 108,100 | 46.2% |
| LOAD_GLOBAL_MODULE | 12,540 | 5.4% |
| CALL | 380 | 0.2% |
| LOAD_ATTR | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 233,805 | 100.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 40.0% |
| BINARY_SUBSCR_STR_INT | 40 | 40.0% |
| BINARY_OP | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 40.0% |
| LOAD_GLOBAL_MODULE | 40 | 40.0% |
| LOAD_GLOBAL | 20 | 20.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 338,000 | 98.6% |
| BINARY_SUBSCR | 2,940 | 0.9% |
| BUILD_TUPLE | 640 | 0.2% |
| LOAD_FAST | 460 | 0.1% |
| LOAD_NAME | 340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 180,180 | 52.6% |
| LOAD_FAST | 60,140 | 17.5% |
| CONVERT_VALUE | 24,000 | 7.0% |
| LOAD_CONST | 12,960 | 3.8% |
| BINARY_SUBSCR_LIST_INT | 12,300 | 3.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 391,109 | 88.2% |
| BUILD_TUPLE | 24,080 | 5.4% |
| LOAD_ATTR_MODULE | 16,205 | 3.7% |
| LOAD_GLOBAL_MODULE | 11,980 | 2.7% |
| LOAD_GLOBAL | 260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 443,674 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 72,000 | 59.8% |
| LOAD_FAST | 48,280 | 40.1% |
| LOAD_CONST | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,120 | 59.9% |
| RETURN_CONST | 36,080 | 30.0% |
| LOAD_FAST | 12,000 | 10.0% |
| JUMP_BACKWARD | 160 | 0.1% |
| LOAD_GLOBAL_MODULE | 80 | 0.1% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 59,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 59,980 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 276,000 | 62.2% |
| RETURN_CONST | 132,000 | 29.7% |
| RETURN_VALUE | 36,000 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 288,000 | 64.9% |
| POP_TOP | 144,000 | 32.4% |
| UNPACK_SEQUENCE_TUPLE | 11,960 | 2.7% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 324,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,640 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 60,320 | 99.9% |
| LOAD_FAST_LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60,320 | 99.9% |
| BUILD_STRING | 80 | 0.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 325,343 | 41.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 144,140 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 96,553 | 12.2% |
| LOAD_ATTR | 72,140 | 9.1% |
| BINARY_SLICE | 36,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 404,447 | 51.2% |
| FOR_ITER | 148,069 | 18.7% |
| FOR_ITER_TUPLE | 73,020 | 9.2% |
| CALL_PY_EXACT_ARGS | 72,720 | 9.2% |
| LOAD_FAST_AND_CLEAR | 49,440 | 6.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,735,115 | 65.2% |
| RETURN_CONST | 1,712,485 | 29.9% |
| YIELD_VALUE | 253,560 | 4.4% |
| RETURN_GENERATOR | 24,080 | 0.4% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 180 | 81.8% |
| POP_TOP | 20 | 9.1% |
| POP_JUMP_IF_FALSE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 220 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 365,721 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 161,021 | 44.0% |
| CALL | 120,080 | 32.8% |
| LOAD_FAST | 48,400 | 13.2% |
| CALL_PY_EXACT_ARGS | 23,920 | 6.5% |
| STORE_DEREF | 12,000 | 3.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,203,664 | 40.2% |
| POP_JUMP_IF_FALSE | 449,811 | 15.0% |
| STORE_FAST | 389,396 | 13.0% |
| STORE_ATTR_INSTANCE_VALUE | 306,304 | 10.2% |
| POP_JUMP_IF_TRUE | 274,999 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,695,284 | 56.7% |
| LOAD_GLOBAL_MODULE | 547,115 | 18.3% |
| LOAD_FAST_LOAD_FAST | 300,220 | 10.0% |
| LOAD_DEREF | 134,769 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 120,140 | 4.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 328,699 | 72.5% |
| SWAP | 60,080 | 13.3% |
| COPY | 36,020 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 12,120 | 2.7% |
| STORE_SUBSCR_DICT | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 290,490 | 64.1% |
| RETURN_VALUE | 60,080 | 13.3% |
| RERAISE | 36,020 | 7.9% |
| DELETE_FAST | 24,000 | 5.3% |
| ENTER_EXECUTOR | 15,505 | 3.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,220,343 | 51.5% |
| CALL | 990,381 | 9.8% |
| CALL_METHOD_DESCRIPTOR_O | 827,995 | 8.2% |
| POP_JUMP_IF_FALSE | 604,787 | 6.0% |
| CALL_FUNCTION_EX | 500,181 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,925,038 | 38.7% |
| RETURN_CONST | 2,958,222 | 29.2% |
| LOAD_CONST | 916,983 | 9.0% |
| ENTER_EXECUTOR | 704,530 | 7.0% |
| RESUME_CHECK | 336,620 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 348,440 | 76.8% |
| RERAISE | 36,020 | 7.9% |
| CALL | 30,475 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 12,047 | 2.7% |
| ENTER_EXECUTOR | 12,013 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400,759 | 88.4% |
| LOAD_GLOBAL_MODULE | 40,085 | 8.8% |
| LOAD_FAST | 12,000 | 2.6% |
| LOAD_GLOBAL | 620 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,681,942 | 52.3% |
| LOAD_ATTR | 669,122 | 20.8% |
| LOAD_FAST | 468,576 | 14.6% |
| LOAD_DEREF | 204,500 | 6.4% |
| RETURN_VALUE | 132,080 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,361,339 | 42.3% |
| CALL | 731,468 | 22.7% |
| LOAD_FAST_LOAD_FAST | 713,271 | 22.2% |
| LOAD_GLOBAL_MODULE | 108,380 | 3.4% |
| LOAD_CONST | 96,100 | 3.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 264,140 | 78.4% |
| COPY_FREE_VARS | 24,600 | 7.3% |
| CACHE | 12,000 | 3.6% |
| CALL_KW | 12,000 | 3.6% |
| MAKE_CELL | 12,000 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 84,000 | 24.9% |
| RETURN_VALUE | 60,000 | 17.8% |
| GET_AWAITABLE | 60,000 | 17.8% |
| CALL | 36,240 | 10.8% |
| GET_ITER | 36,000 | 10.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,170,481 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,691,182 | 23.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 622,560 | 5.4% |
| CALL | 621,806 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 3,735,115 | 32.3% |
| STORE_FAST | 2,136,179 | 18.5% |
| TO_BOOL_BOOL | 1,887,222 | 16.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| LOAD_FAST | 604,397 | 5.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,580 | 44.7% |
| LOAD_CONST | 96,180 | 39.6% |
| LOAD_FAST_LOAD_FAST | 36,000 | 14.8% |
| STORE_SUBSCR | 1,760 | 0.7% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 108,240 | 44.6% |
| LOAD_FAST | 48,240 | 19.9% |
| JUMP_BACKWARD | 36,020 | 14.8% |
| LOAD_CONST | 24,060 | 9.9% |
| LOAD_DEREF | 24,000 | 9.9% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,138 | 44.4% |
| LOAD_ATTR_INSTANCE_VALUE | 515,357 | 40.9% |
| LOAD_ATTR | 122,800 | 9.7% |
| COPY | 36,800 | 2.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,380 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,056,275 | 83.8% |
| POP_JUMP_IF_TRUE | 190,526 | 15.1% |
| TO_BOOL | 5,847 | 0.5% |
| TO_BOOL_BOOL | 5,200 | 0.4% |
| TO_BOOL_NONE | 1,063 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 36,040 | 59.9% |
| BINARY_OP | 24,100 | 40.0% |
| LOAD_ATTR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 60,180 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 11,980 | 98.7% |
| TO_BOOL_INT | 60 | 0.5% |
| TO_BOOL_LIST | 60 | 0.5% |
| TO_BOOL | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000 | 98.8% |
| COPY | 80 | 0.7% |
| CALL_PY_EXACT_ARGS | 60 | 0.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 187,762 | 17.0% |
| LOAD_CONST | 169,964 | 15.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 155,880 | 14.1% |
| LOAD_FAST | 105,077 | 9.5% |
| LOAD_ATTR_CLASS | 96,080 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 290,247 | 26.3% |
| STORE_FAST | 208,324 | 18.9% |
| COPY | 134,383 | 12.2% |
| LOAD_FAST | 96,640 | 8.7% |
| RETURN_VALUE | 96,120 | 8.7% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 12,000 | 98.0% |
| RETURN_VALUE | 80 | 0.7% |
| LOAD_FAST | 80 | 0.7% |
| STORE_FAST | 80 | 0.7% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,940 | 43.2% |
| STORE_FAST | 111,917 | 12.6% |
| LOAD_FAST_LOAD_FAST | 107,540 | 12.1% |
| RESUME_CHECK | 72,940 | 8.2% |
| SWAP | 49,440 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 662,957 | 74.7% |
| STORE_FAST | 137,550 | 15.5% |
| SWAP | 49,440 | 5.6% |
| LOAD_CONST | 24,120 | 2.7% |
| CALL_BUILTIN_CLASS | 11,960 | 1.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 277,040 | 34.9% |
| CALL_INTRINSIC_1 | 154,660 | 19.5% |
| RESUME_CHECK | 96,080 | 12.1% |
| STORE_ATTR_INSTANCE_VALUE | 72,420 | 9.1% |
| BUILD_TUPLE | 72,120 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 649,700 | 81.9% |
| CALL_FUNCTION_EX | 59,200 | 7.5% |
| STORE_FAST | 48,380 | 6.1% |
| RETURN_VALUE | 24,000 | 3.0% |
| LOAD_DEREF | 12,020 | 1.5% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 11,980 | 99.7% |
| LOAD_GLOBAL | 20 | 0.2% |
| STORE_NAME | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 12,000 | 99.8% |
| LOAD_CONST | 20 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 71,980 | 99.9% |
| LOAD_CONST | 60 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 72,000 | 99.9% |
| BINARY_SUBSCR | 60 | 0.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,160 | 99.7% |
| FORMAT_SIMPLE | 80 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,000 | 49.5% |
| CALL_PY_EXACT_ARGS | 11,960 | 49.3% |
| CALL | 200 | 0.8% |
| STORE_DEREF | 80 | 0.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 512,564 | 36.9% |
| LOAD_FAST_LOAD_FAST | 384,540 | 27.7% |
| LOAD_GLOBAL_BUILTIN | 156,640 | 11.3% |
| LOAD_GLOBAL_MODULE | 99,540 | 7.2% |
| LOAD_ATTR_MODULE | 71,940 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 191,840 | 13.8% |
| RETURN_VALUE | 180,760 | 13.0% |
| LOAD_CONST | 160,641 | 11.6% |
| CALL_ISINSTANCE | 157,180 | 11.3% |
| CONTAINS_OP | 121,400 | 8.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,006,235 | 32.1% |
| PUSH_NULL | 731,468 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 613,100 | 9.8% |
| LOAD_GLOBAL_MODULE | 590,051 | 9.4% |
| LOAD_CONST | 468,274 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,947,347 | 31.1% |
| POP_TOP | 990,381 | 15.8% |
| LOAD_FAST | 825,257 | 13.2% |
| RETURN_VALUE | 621,806 | 9.9% |
| BINARY_SUBSCR_DICT | 420,140 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 480,760 | 44.5% |
| ENTER_EXECUTOR | 363,764 | 33.7% |
| LOAD_FAST | 100,565 | 9.3% |
| CALL_INTRINSIC_1 | 76,277 | 7.1% |
| BUILD_MAP | 59,200 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 500,181 | 46.3% |
| RETURN_VALUE | 221,285 | 20.5% |
| RESUME_CHECK | 132,220 | 12.2% |
| STORE_FAST | 119,360 | 11.0% |
| CALL | 83,300 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 290,137 | 96.0% |
| RERAISE | 12,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 154,660 | 51.2% |
| CALL_FUNCTION_EX | 76,277 | 25.2% |
| LOAD_CONST | 59,200 | 19.6% |
| RERAISE | 12,000 | 4.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 403,365 | 87.1% |
| ENTER_EXECUTOR | 59,700 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 265,420 | 57.3% |
| STORE_FAST | 100,365 | 21.7% |
| COPY_FREE_VARS | 24,000 | 5.2% |
| RETURN_VALUE | 12,440 | 2.7% |
| LOAD_FAST | 12,180 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 119,593 | 64.6% |
| LOAD_ATTR | 24,440 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,340 | 6.7% |
| LOAD_FAST_LOAD_FAST | 12,000 | 6.5% |
| LOAD_ATTR_CLASS | 12,000 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120,557 | 65.1% |
| POP_JUMP_IF_TRUE | 60,580 | 32.7% |
| COMPARE_OP | 1,928 | 1.0% |
| COMPARE_OP_INT | 1,452 | 0.8% |
| COMPARE_OP_STR | 460 | 0.2% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 204,420 | 25.6% |
| LOAD_CONST | 145,280 | 18.2% |
| BUILD_TUPLE | 121,400 | 15.2% |
| LOAD_FAST | 109,260 | 13.7% |
| LOAD_FAST_LOAD_FAST | 108,880 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 605,580 | 75.7% |
| COPY | 120,040 | 15.0% |
| POP_JUMP_IF_TRUE | 25,320 | 3.2% |
| SWAP | 24,000 | 3.0% |
| STORE_FAST | 12,080 | 1.5% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 35,940 | 59.6% |
| BINARY_SUBSCR | 24,000 | 39.8% |
| LOAD_FAST | 240 | 0.4% |
| LOAD_GLOBAL_MODULE | 80 | 0.1% |
| LOAD_ATTR | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 60,320 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,117,388 | 46.6% |
| LOAD_CONST | 252,200 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 227,980 | 9.5% |
| BINARY_OP | 134,383 | 5.6% |
| CONTAINS_OP | 120,040 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 924,388 | 38.5% |
| LOAD_FAST | 456,000 | 19.0% |
| TO_BOOL_BOOL | 326,140 | 13.6% |
| TO_BOOL_NONE | 190,740 | 8.0% |
| TO_BOOL_INT | 162,720 | 6.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 288,572 | 36.9% |
| CACHE | 238,164 | 30.5% |
| CALL | 120,900 | 15.5% |
| LOAD_ATTR_PROPERTY | 83,920 | 10.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,017 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 732,353 | 93.7% |
| RETURN_GENERATOR | 24,600 | 3.1% |
| MAKE_CELL | 24,100 | 3.1% |
| RESUME | 860 | 0.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 108,000 | 51.8% |
| NOP | 24,000 | 11.5% |
| POP_EXCEPT | 24,000 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 23,980 | 11.5% |
| POP_TOP | 16,245 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 108,000 | 51.8% |
| RETURN_CONST | 48,000 | 23.0% |
| LOAD_FAST | 28,245 | 13.6% |
| LOAD_CONST | 12,080 | 5.8% |
| ENTER_EXECUTOR | 11,680 | 5.6% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 432,640 | 90.0% |
| LOAD_ATTR_INSTANCE_VALUE | 36,040 | 7.5% |
| LOAD_ATTR | 12,080 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 480,760 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 704,530 | 55.7% |
| POP_JUMP_IF_TRUE | 147,839 | 11.7% |
| CALL_LIST_APPEND | 98,408 | 7.8% |
| STORE_ATTR_INSTANCE_VALUE | 83,680 | 6.6% |
| EXTENDED_ARG | 60,120 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 363,764 | 28.8% |
| CALL | 225,554 | 17.8% |
| LOAD_FAST | 154,676 | 12.2% |
| RESUME_CHECK | 119,601 | 9.5% |
| JUMP_BACKWARD | 107,780 | 8.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 119,920 | 58.1% |
| POP_JUMP_IF_TRUE | 60,060 | 29.1% |
| COMPARE_OP_STR | 12,180 | 5.9% |
| STORE_ATTR_INSTANCE_VALUE | 11,980 | 5.8% |
| CONTAINS_OP | 460 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 108,000 | 52.3% |
| ENTER_EXECUTOR | 60,120 | 29.1% |
| POP_JUMP_IF_FALSE | 24,680 | 12.0% |
| JUMP_FORWARD | 12,340 | 6.0% |
| FOR_ITER_LIST | 640 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 157,980 | 44.2% |
| GET_ITER | 148,069 | 41.5% |
| SWAP | 24,460 | 6.9% |
| LOAD_FAST | 24,200 | 6.8% |
| FOR_ITER | 2,320 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 134,809 | 37.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 108,000 | 30.2% |
| STORE_FAST | 49,480 | 13.9% |
| LOAD_FAST | 24,340 | 6.8% |
| SWAP | 24,080 | 6.7% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 276,000 | 60.5% |
| LOAD_FAST | 108,000 | 23.7% |
| RETURN_GENERATOR | 60,000 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 11,980 | 2.6% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 456,000 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 680 | 53.1% |
| IMPORT_NAME | 600 | 46.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 1,140 | 89.1% |
| STORE_FAST | 140 | 10.9% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 600 | 52.6% |
| STORE_NAME | 520 | 45.6% |
| STORE_FAST | 20 | 1.8% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 314,960 | 55.4% |
| LOAD_FAST | 108,560 | 19.1% |
| LOAD_CONST | 108,160 | 19.0% |
| LOAD_DEREF | 24,000 | 4.2% |
| LOAD_FAST_LOAD_FAST | 12,360 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 460,440 | 80.9% |
| RETURN_VALUE | 72,100 | 12.7% |
| POP_JUMP_IF_TRUE | 12,360 | 2.2% |
| COPY | 12,000 | 2.1% |
| STORE_FAST | 12,000 | 2.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 219,540 | 56.7% |
| ENTER_EXECUTOR | 107,780 | 27.9% |
| STORE_SUBSCR | 36,020 | 9.3% |
| POP_JUMP_IF_TRUE | 14,820 | 3.8% |
| POP_JUMP_IF_FALSE | 2,120 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 215,960 | 55.8% |
| FOR_ITER | 157,980 | 40.8% |
| FOR_ITER_LIST | 6,640 | 1.7% |
| LOAD_FAST | 2,480 | 0.6% |
| FOR_ITER_RANGE | 1,180 | 0.3% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 167,760 | 99.9% |
| RESUME | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 108,000 | 64.3% |
| SEND | 60,000 | 35.7% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 441,291 | 59.4% |
| POP_TOP | 132,480 | 17.8% |
| STORE_ATTR_INSTANCE_VALUE | 48,353 | 6.5% |
| POP_JUMP_IF_TRUE | 24,380 | 3.3% |
| STORE_ATTR | 24,120 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 474,718 | 63.9% |
| LOAD_CONST | 92,210 | 12.4% |
| LOAD_FAST_LOAD_FAST | 60,340 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 42,272 | 5.7% |
| LOAD_GLOBAL_MODULE | 36,000 | 4.8% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,040 | 91.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 500 | 3.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300 | 2.3% |
| LOAD_FAST | 240 | 1.8% |
| CALL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,180 | 93.0% |
| JUMP_BACKWARD | 920 | 7.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 262,020 | 83.4% |
| LOAD_CONST | 24,020 | 7.6% |
| LOAD_ATTR_SLOT | 15,917 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 11,980 | 3.8% |
| LOAD_DEREF | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 290,137 | 92.4% |
| LOAD_FAST | 24,000 | 7.6% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,601,439 | 64.5% |
| LOAD_ATTR_INSTANCE_VALUE | 872,725 | 15.6% |
| LOAD_ATTR_WITH_HINT | 335,900 | 6.0% |
| LOAD_GLOBAL_MODULE | 303,620 | 5.4% |
| LOAD_DEREF | 151,744 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,177,627 | 21.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 894,124 | 16.0% |
| PUSH_NULL | 669,122 | 12.0% |
| LOAD_CONST | 483,080 | 8.6% |
| CALL_PY_EXACT_ARGS | 322,350 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,337,724 | 20.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,673,096 | 10.5% |
| LOAD_CONST | 1,081,417 | 6.8% |
| POP_JUMP_IF_FALSE | 1,057,955 | 6.6% |
| STORE_ATTR_SLOT | 1,047,824 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,174,570 | 32.3% |
| COMPARE_OP_INT | 1,717,024 | 10.7% |
| STORE_FAST | 1,210,270 | 7.6% |
| LOAD_CONST | 1,081,417 | 6.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 634,620 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 401,382 | 19.2% |
| RESUME_CHECK | 207,422 | 9.9% |
| POP_JUMP_IF_FALSE | 171,442 | 8.2% |
| POP_JUMP_IF_TRUE | 144,340 | 6.9% |
| NOP | 134,769 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,920 | 24.2% |
| LOAD_ATTR_INSTANCE_VALUE | 368,406 | 17.6% |
| PUSH_NULL | 204,500 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 155,680 | 7.4% |
| LOAD_ATTR | 151,744 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,390,698 | 15.4% |
| POP_JUMP_IF_FALSE | 7,299,477 | 9.9% |
| STORE_FAST | 6,647,858 | 9.0% |
| LOAD_CONST | 5,174,570 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 5,140,289 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,774,116 | 29.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,985,104 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 4,942,391 | 6.7% |
| LOAD_ATTR | 3,601,439 | 4.9% |
| CALL_PY_EXACT_ARGS | 3,344,885 | 4.5% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 49,440 | 67.3% |
| LOAD_FAST_AND_CLEAR | 24,000 | 32.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 49,440 | 67.3% |
| LOAD_FAST_AND_CLEAR | 24,000 | 32.7% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 15,402 | 38.5% |
| POP_JUMP_IF_FALSE | 12,000 | 30.0% |
| STORE_FAST | 12,000 | 30.0% |
| POP_TOP | 320 | 0.8% |
| JUMP_FORWARD | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 15,302 | 38.2% |
| LOAD_ATTR | 12,000 | 30.0% |
| LOAD_CONST | 12,000 | 30.0% |
| POP_JUMP_IF_NOT_NONE | 440 | 1.1% |
| LOAD_FAST | 80 | 0.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,303,986 | 12.7% |
| LOAD_GLOBAL_MODULE | 1,093,580 | 10.7% |
| STORE_FAST | 1,064,057 | 10.4% |
| STORE_ATTR_INSTANCE_VALUE | 997,280 | 9.7% |
| POP_JUMP_IF_FALSE | 901,060 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,992,573 | 19.4% |
| STORE_ATTR_SLOT | 1,797,788 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,280,717 | 12.5% |
| LOAD_FAST | 875,265 | 8.5% |
| LOAD_FAST_LOAD_FAST | 734,522 | 7.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,560 | 12.4% |
| POP_JUMP_IF_FALSE | 3,460 | 12.0% |
| RESUME | 2,480 | 8.6% |
| RESUME_CHECK | 2,420 | 8.4% |
| STORE_FAST | 2,320 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,700 | 33.8% |
| LOAD_GLOBAL_BUILTIN | 4,380 | 15.3% |
| LOAD_ATTR | 4,140 | 14.4% |
| LOAD_FAST | 4,060 | 14.1% |
| CALL | 1,740 | 6.1% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,620 | 58.2% |
| LOAD_NAME | 1,200 | 26.7% |
| RESUME | 220 | 4.9% |
| STORE_NAME | 180 | 4.0% |
| LOAD_ATTR | 120 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,260 | 28.0% |
| LOAD_NAME | 1,200 | 26.7% |
| LOAD_ATTR | 660 | 14.7% |
| BUILD_TUPLE | 440 | 9.8% |
| BINARY_SUBSCR | 340 | 7.6% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 820 | 93.2% |
| LOAD_DEREF | 60 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 280 | 31.8% |
| LOAD_FAST | 180 | 20.5% |
| CALL | 120 | 13.6% |
| PUSH_NULL | 100 | 11.4% |
| LOAD_SUPER_ATTR_ATTR | 100 | 11.4% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 187,364 | 51.6% |
| CALL_PY_EXACT_ARGS | 114,937 | 31.6% |
| COPY_FREE_VARS | 24,100 | 6.6% |
| CACHE | 12,360 | 3.4% |
| CALL | 12,320 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 187,364 | 51.6% |
| RESUME_CHECK | 163,417 | 45.0% |
| RETURN_GENERATOR | 12,000 | 3.3% |
| RESUME | 520 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,366,845 | 45.7% |
| COMPARE_OP_INT | 2,660,981 | 19.1% |
| TO_BOOL_NONE | 1,214,534 | 8.7% |
| TO_BOOL | 1,056,275 | 7.6% |
| CONTAINS_OP | 605,580 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,299,477 | 52.4% |
| RETURN_CONST | 1,484,889 | 10.7% |
| LOAD_CONST | 1,057,955 | 7.6% |
| LOAD_GLOBAL_MODULE | 1,008,424 | 7.2% |
| LOAD_FAST_LOAD_FAST | 901,060 | 6.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,035,568 | 56.1% |
| LOAD_FAST | 2,039,684 | 37.7% |
| LOAD_ATTR | 132,960 | 2.5% |
| LOAD_DEREF | 132,080 | 2.4% |
| LOAD_ATTR_WITH_HINT | 34,952 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,469,942 | 82.6% |
| RETURN_CONST | 279,602 | 5.2% |
| LOAD_GLOBAL_MODULE | 276,580 | 5.1% |
| LOAD_FAST_LOAD_FAST | 144,440 | 2.7% |
| NOP | 132,300 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,047,515 | 63.4% |
| LOAD_ATTR_INSTANCE_VALUE | 444,340 | 26.9% |
| LOAD_ATTR | 108,980 | 6.6% |
| LOAD_GLOBAL_MODULE | 12,600 | 0.8% |
| CALL | 12,020 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 580,476 | 35.2% |
| LOAD_FAST_LOAD_FAST | 435,402 | 26.4% |
| LOAD_GLOBAL_MODULE | 332,297 | 20.1% |
| LOAD_CONST | 132,200 | 8.0% |
| LOAD_DEREF | 84,280 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,242,439 | 54.8% |
| COMPARE_OP_INT | 708,520 | 17.3% |
| TO_BOOL_INT | 261,750 | 6.4% |
| TO_BOOL_STR | 240,200 | 5.9% |
| TO_BOOL_NONE | 203,846 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,919,828 | 46.9% |
| LOAD_GLOBAL_BUILTIN | 449,400 | 11.0% |
| NOP | 274,999 | 6.7% |
| LOAD_FAST_LOAD_FAST | 228,460 | 5.6% |
| LOAD_CONST | 228,363 | 5.6% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 12,020 | 49.2% |
| POP_TOP | 12,000 | 49.1% |
| CALL | 380 | 1.6% |
| LOAD_CONST | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 12,020 | 50.0% |
| PUSH_EXC_INFO | 12,000 | 50.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 36,020 | 50.0% |
| POP_TOP | 12,000 | 16.7% |
| CALL_INTRINSIC_1 | 12,000 | 16.7% |
| POP_JUMP_IF_FALSE | 12,000 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 36,020 | 50.0% |
| COPY | 24,000 | 33.3% |
| CALL_INTRINSIC_1 | 12,000 | 16.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,958,222 | 37.4% |
| POP_JUMP_IF_FALSE | 1,484,889 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 760,630 | 9.6% |
| STORE_ATTR_SLOT | 613,182 | 7.8% |
| STORE_FAST | 395,378 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,220,343 | 66.0% |
| INTERPRETER_EXIT | 1,712,485 | 21.7% |
| EXIT_INIT_CHECK | 324,640 | 4.1% |
| STORE_FAST | 176,377 | 2.2% |
| TO_BOOL_BOOL | 132,322 | 1.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 276,400 | 81.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 60,000 | 17.7% |
| SEND | 1,820 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 276,000 | 81.6% |
| YIELD_VALUE | 60,000 | 17.7% |
| SEND | 1,820 | 0.5% |
| POP_TOP | 200 | 0.1% |
| SEND_GEN | 200 | 0.1% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 161,021 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 51,682 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 71,439 | 33.6% |
| SET_FUNCTION_ATTRIBUTE | 51,682 | 24.3% |
| CALL | 39,422 | 18.5% |
| LOAD_FAST | 24,320 | 11.4% |
| CALL_PY_EXACT_ARGS | 12,040 | 5.7% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 20 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180,980 | 62.6% |
| LOAD_FAST_LOAD_FAST | 54,500 | 18.9% |
| LOAD_DEREF | 36,480 | 12.6% |
| STORE_FAST_LOAD_FAST | 12,080 | 4.2% |
| STORE_ATTR | 4,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60,460 | 20.9% |
| LOAD_FAST | 51,560 | 17.8% |
| RETURN_CONST | 49,720 | 17.2% |
| LOAD_GLOBAL_BUILTIN | 35,960 | 12.4% |
| JUMP_FORWARD | 24,120 | 8.3% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60,140 | 49.5% |
| LOAD_CONST | 12,300 | 10.1% |
| CALL | 12,040 | 9.9% |
| MAKE_FUNCTION | 12,000 | 9.9% |
| JUMP_FORWARD | 12,000 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,240 | 39.7% |
| LOAD_GLOBAL_MODULE | 36,120 | 29.7% |
| LOAD_FAST | 24,280 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 12,360 | 10.2% |
| LOAD_GLOBAL | 340 | 0.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,136,179 | 19.8% |
| CALL | 1,947,347 | 18.0% |
| LOAD_CONST | 1,210,270 | 11.2% |
| CALL_BUILTIN_FAST | 814,460 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 707,964 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,647,858 | 61.6% |
| LOAD_FAST_LOAD_FAST | 1,064,057 | 9.9% |
| LOAD_CONST | 587,062 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 483,698 | 4.5% |
| JUMP_FORWARD | 441,291 | 4.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 107,980 | 52.3% |
| COPY | 84,060 | 40.7% |
| STORE_ATTR | 12,000 | 5.8% |
| FOR_ITER_LIST | 940 | 0.5% |
| FOR_ITER | 540 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 108,620 | 52.6% |
| STORE_ATTR_INSTANCE_VALUE | 83,920 | 40.6% |
| STORE_ATTR | 12,080 | 5.8% |
| TO_BOOL_LIST | 520 | 0.3% |
| TO_BOOL_STR | 500 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 714,845 | 73.8% |
| UNPACK_SEQUENCE_LIST | 119,960 | 12.4% |
| UNPACK_SEQUENCE_TUPLE | 72,300 | 7.5% |
| COPY | 24,200 | 2.5% |
| STORE_FAST_STORE_FAST | 24,160 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 534,205 | 55.2% |
| LOAD_GLOBAL_MODULE | 131,880 | 13.6% |
| STORE_FAST | 96,460 | 10.0% |
| LOAD_FAST_LOAD_FAST | 84,800 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 84,180 | 8.7% |


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

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,640 | 36.6% |
| IMPORT_FROM | 1,140 | 25.4% |
| IMPORT_NAME | 520 | 11.6% |
| LOAD_CONST | 460 | 10.3% |
| CALL | 300 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,500 | 55.8% |
| IMPORT_FROM | 680 | 15.2% |
| POP_TOP | 460 | 10.3% |
| LOAD_BUILD_CLASS | 180 | 4.0% |
| LOAD_NAME | 180 | 4.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 567,305 | 41.0% |
| BINARY_OP_SUBTRACT_INT | 333,363 | 24.1% |
| LOAD_FAST | 192,300 | 13.9% |
| LOAD_ATTR | 57,188 | 4.1% |
| BUILD_LIST | 49,440 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 924,388 | 66.9% |
| COPY | 108,280 | 7.8% |
| STORE_FAST | 93,968 | 6.8% |
| LOAD_CONST | 72,280 | 5.2% |
| POP_EXCEPT | 60,080 | 4.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,080 | 86.5% |
| RETURN_VALUE | 540 | 3.9% |
| CALL | 220 | 1.6% |
| FOR_ITER | 220 | 1.6% |
| BINARY_SUBSCR | 160 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 12,800 | 91.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 660 | 4.7% |
| UNPACK_SEQUENCE_TUPLE | 180 | 1.3% |
| UNPACK_SEQUENCE | 160 | 1.1% |
| LOAD_FAST | 80 | 0.6% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 108,100 | 18.7% |
| YIELD_VALUE | 108,000 | 18.7% |
| BINARY_OP_ADD_UNICODE | 107,980 | 18.7% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 107,980 | 18.7% |
| RETURN_VALUE | 60,580 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 253,560 | 43.9% |
| YIELD_VALUE | 108,000 | 18.7% |
| STORE_FAST_LOAD_FAST | 107,980 | 18.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 107,960 | 18.7% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,760 | 51.2% |
| CACHE | 2,020 | 21.7% |
| COPY_FREE_VARS | 860 | 9.2% |
| MAKE_CELL | 520 | 5.6% |
| POP_TOP | 380 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,020 | 43.2% |
| LOAD_GLOBAL | 2,480 | 26.7% |
| NOP | 600 | 6.5% |
| LOAD_CONST | 540 | 5.8% |
| LOAD_FAST_LOAD_FAST | 460 | 4.9% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,240 | 77.3% |
| LOAD_ATTR_INSTANCE_VALUE | 15,637 | 12.8% |
| LOAD_ATTR | 11,960 | 9.8% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,160 | 58.3% |
| LOAD_GLOBAL_MODULE | 35,080 | 28.8% |
| STORE_FAST | 15,657 | 12.8% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 675,965 | 62.4% |
| LOAD_FAST_LOAD_FAST | 263,840 | 24.3% |
| CALL_LEN | 83,960 | 7.7% |
| LOAD_CONST | 59,800 | 5.5% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 567,305 | 52.3% |
| BINARY_SLICE | 311,940 | 28.8% |
| RETURN_VALUE | 71,980 | 6.6% |
| CALL_PY_EXACT_ARGS | 71,960 | 6.6% |
| STORE_FAST | 60,320 | 5.6% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 119,920 | 52.4% |
| RETURN_VALUE | 107,960 | 47.2% |
| LOAD_FAST_LOAD_FAST | 480 | 0.2% |
| BINARY_SUBSCR_LIST_INT | 160 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 107,980 | 47.2% |
| LOAD_GLOBAL_MODULE | 107,960 | 47.2% |
| STORE_FAST | 12,220 | 5.3% |
| CALL | 240 | 0.1% |
| LOAD_FAST | 240 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,960 | 92.0% |
| LOAD_CONST | 1,004 | 7.7% |
| BINARY_OP | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,980 | 92.1% |
| CALL_BUILTIN_O | 1,004 | 7.7% |
| CALL | 20 | 0.2% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 11,960 | 99.0% |
| BINARY_SUBSCR_TUPLE_INT | 100 | 0.8% |
| BINARY_OP | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 11,960 | 99.0% |
| BINARY_OP_ADD_INT | 100 | 0.8% |
| COMPARE_OP | 20 | 0.2% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60,164 | 65.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,960 | 13.0% |
| LOAD_ATTR_WITH_HINT | 11,960 | 13.0% |
| CALL | 7,757 | 8.4% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 59,180 | 64.3% |
| RETURN_VALUE | 11,980 | 13.0% |
| LOAD_FAST | 11,980 | 13.0% |
| STORE_FAST | 8,801 | 9.6% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 563,920 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 95,920 | 11.5% |
| BINARY_OP_SUBTRACT_INT | 83,960 | 10.0% |
| CALL_LEN | 60,080 | 7.2% |
| LOAD_CONST | 33,443 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 333,363 | 39.8% |
| STORE_FAST | 324,000 | 38.7% |
| LOAD_FAST | 84,040 | 10.0% |
| BINARY_OP_SUBTRACT_INT | 83,960 | 10.0% |
| BINARY_SUBSCR_LIST_INT | 11,960 | 1.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 420,140 | 46.5% |
| LOAD_FAST | 350,529 | 38.8% |
| BUILD_TUPLE | 48,080 | 5.3% |
| LOAD_FAST_LOAD_FAST | 36,020 | 4.0% |
| RETURN_VALUE | 23,980 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 432,040 | 47.8% |
| PUSH_EXC_INFO | 348,440 | 38.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 38,149 | 4.2% |
| LOAD_FAST_LOAD_FAST | 35,980 | 4.0% |
| STORE_FAST | 24,340 | 2.7% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 300,000 | 60.9% |
| LOAD_FAST | 192,220 | 39.0% |
| LOAD_CONST | 240 | 0.0% |
| ENTER_EXECUTOR | 160 | 0.0% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 492,660 | 100.0% |
| RESUME | 20 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,844 | 63.8% |
| BINARY_SUBSCR | 12,300 | 17.9% |
| BINARY_OP_SUBTRACT_INT | 11,960 | 17.4% |
| LOAD_FAST | 580 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,240 | 35.3% |
| STORE_FAST | 15,479 | 22.6% |
| LOAD_ATTR_SLOT | 13,316 | 19.4% |
| LOAD_CONST | 11,980 | 17.5% |
| TO_BOOL_BOOL | 2,449 | 3.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,420 | 99.7% |
| LOAD_FAST | 160 | 0.1% |
| BINARY_SUBSCR | 60 | 0.1% |
| ENTER_EXECUTOR | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 108,040 | 99.4% |
| LOAD_CONST | 340 | 0.3% |
| STORE_FAST | 120 | 0.1% |
| PUSH_EXC_INFO | 60 | 0.1% |
| LOAD_ATTR | 60 | 0.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 229,020 | 99.9% |
| BINARY_SUBSCR | 260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 120,040 | 52.4% |
| LOAD_GLOBAL_MODULE | 24,240 | 10.6% |
| LOAD_GLOBAL_BUILTIN | 24,040 | 10.5% |
| LOAD_FAST | 24,020 | 10.5% |
| STORE_FAST | 12,280 | 5.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 132,000 | 40.7% |
| LOAD_ATTR_INSTANCE_VALUE | 84,020 | 25.9% |
| LOAD_FAST_LOAD_FAST | 36,160 | 11.1% |
| LOAD_FAST | 36,140 | 11.1% |
| PUSH_NULL | 11,960 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 324,520 | 100.0% |
| COPY_FREE_VARS | 120 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,380 | 36.9% |
| LOAD_FAST | 85,287 | 29.0% |
| LOAD_FAST_LOAD_FAST | 48,386 | 16.5% |
| BINARY_SLICE | 23,960 | 8.2% |
| CALL_BUILTIN_CLASS | 23,960 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 156,953 | 53.4% |
| POP_TOP | 108,260 | 36.8% |
| COPY_FREE_VARS | 26,017 | 8.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,060 | 0.7% |
| CALL_PY_EXACT_ARGS | 489 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 71,960 | 29.1% |
| LOAD_FAST | 39,897 | 16.1% |
| CALL | 36,480 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 36,160 | 14.6% |
| LOAD_GLOBAL_MODULE | 14,149 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,500 | 39.1% |
| LOAD_FAST | 36,200 | 14.7% |
| RETURN_VALUE | 35,980 | 14.6% |
| GET_ITER | 29,946 | 12.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,960 | 9.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 837,640 | 50.6% |
| LOAD_FAST_LOAD_FAST | 455,120 | 27.5% |
| LOAD_CONST | 289,520 | 17.5% |
| LOAD_GLOBAL_MODULE | 35,920 | 2.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 11,960 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 814,460 | 49.6% |
| RETURN_VALUE | 454,780 | 27.7% |
| TO_BOOL_BOOL | 132,780 | 8.1% |
| COPY | 107,980 | 6.6% |
| POP_TOP | 59,500 | 3.6% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,962 | 53.2% |
| LOAD_FAST | 12,620 | 44.9% |
| LOAD_CONST | 300 | 1.1% |
| CALL_STR_1 | 80 | 0.3% |
| CALL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 15,002 | 53.4% |
| STORE_FAST | 12,380 | 44.1% |
| RETURN_VALUE | 580 | 2.1% |
| BEFORE_WITH | 80 | 0.3% |
| PUSH_EXC_INFO | 60 | 0.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,093 | 86.6% |
| LOAD_ATTR_INSTANCE_VALUE | 5,220 | 9.2% |
| BINARY_OP_MULTIPLY_FLOAT | 1,004 | 1.8% |
| BUILD_TUPLE | 360 | 0.6% |
| CALL | 220 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 23,920 | 42.2% |
| STORE_FAST | 17,300 | 30.5% |
| BINARY_SUBSCR_DICT | 11,960 | 21.1% |
| POP_TOP | 1,613 | 2.8% |
| LOAD_CONST | 1,024 | 1.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,131,323 | 54.2% |
| LOAD_GLOBAL_BUILTIN | 437,100 | 21.0% |
| LOAD_ATTR_MODULE | 298,800 | 14.3% |
| BUILD_TUPLE | 157,180 | 7.5% |
| LOAD_ATTR | 59,960 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,880,223 | 90.2% |
| RETURN_VALUE | 144,240 | 6.9% |
| COPY | 35,980 | 1.7% |
| STORE_FAST | 24,060 | 1.2% |
| TO_BOOL | 980 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 649,720 | 65.8% |
| LOAD_ATTR_INSTANCE_VALUE | 312,771 | 31.7% |
| LOAD_GLOBAL_MODULE | 12,080 | 1.2% |
| BINARY_SUBSCR | 12,060 | 1.2% |
| CALL | 640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 288,234 | 29.2% |
| LOAD_FAST | 226,320 | 22.9% |
| LOAD_CONST | 97,380 | 9.9% |
| BINARY_OP_ADD_INT | 83,960 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 60,080 | 6.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 134,744 | 52.5% |
| BUILD_TUPLE | 65,283 | 25.4% |
| ENTER_EXECUTOR | 31,961 | 12.5% |
| RETURN_VALUE | 24,040 | 9.4% |
| CALL | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120,260 | 46.9% |
| ENTER_EXECUTOR | 98,408 | 38.3% |
| LOAD_FAST | 24,120 | 9.4% |
| NOP | 12,020 | 4.7% |
| JUMP_BACKWARD | 1,740 | 0.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 634,620 | 66.3% |
| LOAD_ATTR_METHOD_NO_DICT | 204,040 | 21.3% |
| LOAD_FAST_LOAD_FAST | 72,200 | 7.5% |
| RETURN_VALUE | 24,040 | 2.5% |
| LOAD_FAST | 20,940 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 622,560 | 65.0% |
| CALL_PY_EXACT_ARGS | 108,040 | 11.3% |
| STORE_FAST | 93,360 | 9.8% |
| LOAD_CONST | 71,980 | 7.5% |
| LOAD_FAST | 24,060 | 2.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 384,520 | 54.0% |
| LOAD_ATTR_METHOD_NO_DICT | 227,960 | 32.0% |
| LOAD_FAST | 59,980 | 8.4% |
| LOAD_ATTR | 24,040 | 3.4% |
| LOAD_FAST_LOAD_FAST | 15,637 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 268,237 | 37.6% |
| UNPACK_SEQUENCE_LIST | 119,920 | 16.8% |
| YIELD_VALUE | 107,980 | 15.2% |
| POP_TOP | 84,100 | 11.8% |
| RETURN_VALUE | 84,000 | 11.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 894,124 | 59.1% |
| LOAD_ATTR_METHOD_NO_DICT | 578,903 | 38.3% |
| LOAD_FAST | 24,040 | 1.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 11,960 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,324 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 927,442 | 61.3% |
| POP_TOP | 152,297 | 10.1% |
| GET_ITER | 144,140 | 9.5% |
| LOAD_FAST | 72,200 | 4.8% |
| STORE_FAST | 67,179 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,235 | 57.5% |
| BUILD_TUPLE | 191,840 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 84,120 | 8.4% |
| LOAD_CONST | 48,400 | 4.8% |
| CALL | 36,880 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 827,995 | 82.7% |
| STORE_FAST | 99,375 | 9.9% |
| LOAD_CONST | 24,300 | 2.4% |
| UNPACK_SEQUENCE_TUPLE | 24,080 | 2.4% |
| PUSH_EXC_INFO | 12,047 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,461,635 | 41.0% |
| LOAD_FAST | 3,344,885 | 30.8% |
| LOAD_FAST_LOAD_FAST | 661,163 | 6.1% |
| LOAD_CONST | 576,120 | 5.3% |
| LOAD_ATTR | 322,350 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,203,466 | 93.8% |
| COPY_FREE_VARS | 288,572 | 2.7% |
| RETURN_GENERATOR | 264,140 | 2.4% |
| MAKE_CELL | 114,937 | 1.1% |
| TO_BOOL_BOOL | 4,848 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 143,680 | 25.3% |
| LOAD_FAST | 131,980 | 23.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 124,045 | 21.8% |
| PUSH_NULL | 72,040 | 12.7% |
| LOAD_ATTR | 35,920 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 556,605 | 97.9% |
| RETURN_GENERATOR | 11,980 | 2.1% |
| MAKE_CELL | 60 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 94.4% |
| CALL | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 77.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 80 | 22.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 700 | 48.6% |
| LOAD_FAST | 540 | 37.5% |
| RETURN_VALUE | 120 | 8.3% |
| LOAD_GLOBAL_MODULE | 80 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 480 | 33.3% |
| LOAD_FAST | 480 | 33.3% |
| STORE_FAST | 340 | 23.6% |
| CALL | 80 | 5.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 4.2% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 204,940 | 99.8% |
| LOAD_CONST | 200 | 0.1% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,300 | 52.8% |
| LOAD_FAST_LOAD_FAST | 48,140 | 23.5% |
| LOAD_GLOBAL_MODULE | 35,960 | 17.5% |
| STORE_FAST | 11,980 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 660 | 0.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 332,441 | 95.5% |
| LOAD_FAST | 15,299 | 4.4% |
| LOAD_GLOBAL_MODULE | 260 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 332,461 | 95.5% |
| POP_JUMP_IF_FALSE | 15,679 | 4.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,717,024 | 50.6% |
| LOAD_ATTR_INSTANCE_VALUE | 953,897 | 28.1% |
| LOAD_ATTR_CLASS | 383,960 | 11.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 119,920 | 3.5% |
| COPY | 108,160 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,660,981 | 78.4% |
| POP_JUMP_IF_TRUE | 708,520 | 20.9% |
| COPY | 24,000 | 0.7% |
| RETURN_VALUE | 100 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 229,200 | 82.5% |
| LOAD_GLOBAL_MODULE | 47,840 | 17.2% |
| COMPARE_OP | 460 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 340 | 0.1% |
| LOAD_FAST | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 217,800 | 78.4% |
| COPY | 23,960 | 8.6% |
| EXTENDED_ARG | 12,180 | 4.4% |
| POP_JUMP_IF_TRUE | 12,020 | 4.3% |
| RETURN_VALUE | 11,980 | 4.3% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 215,960 | 78.3% |
| LOAD_FAST | 47,960 | 17.4% |
| GET_ITER | 11,960 | 4.3% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 215,960 | 78.3% |
| POP_TOP | 59,940 | 21.7% |
| RESUME | 40 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 404,447 | 95.2% |
| SWAP | 12,460 | 2.9% |
| JUMP_BACKWARD | 6,640 | 1.6% |
| FOR_ITER | 780 | 0.2% |
| EXTENDED_ARG | 640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 232,133 | 54.6% |
| LOAD_FAST | 139,997 | 32.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,508 | 7.2% |
| UNPACK_SEQUENCE_TUPLE | 11,960 | 2.8% |
| RETURN_CONST | 8,009 | 1.9% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 29,946 | 95.7% |
| JUMP_BACKWARD | 1,180 | 3.8% |
| FOR_ITER | 100 | 0.3% |
| SWAP | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,726 | 98.2% |
| STORE_FAST_LOAD_FAST | 360 | 1.2% |
| RETURN_CONST | 60 | 0.2% |
| LOAD_CONST | 40 | 0.1% |
| LOAD_GLOBAL | 40 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 73,020 | 84.3% |
| SWAP | 12,460 | 14.4% |
| LOAD_FAST | 700 | 0.8% |
| JUMP_BACKWARD | 400 | 0.5% |
| FOR_ITER | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,060 | 69.3% |
| STORE_FAST | 13,720 | 15.8% |
| SWAP | 11,980 | 13.8% |
| STORE_FAST_LOAD_FAST | 500 | 0.6% |
| ENTER_EXECUTOR | 280 | 0.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 455,800 | 62.2% |
| LOAD_GLOBAL_MODULE | 228,420 | 31.2% |
| LOAD_FAST | 48,600 | 6.6% |
| LOAD_ATTR | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 383,960 | 52.4% |
| LOAD_FAST | 144,440 | 19.7% |
| BINARY_OP | 96,080 | 13.1% |
| CALL | 48,060 | 6.6% |
| RETURN_VALUE | 24,200 | 3.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,774,116 | 86.6% |
| LOAD_FAST_LOAD_FAST | 1,280,717 | 5.1% |
| COPY | 924,388 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 791,180 | 3.1% |
| LOAD_DEREF | 368,406 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,173,536 | 16.6% |
| POP_JUMP_IF_NONE | 3,035,568 | 12.1% |
| RETURN_VALUE | 2,691,182 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 2,275,722 | 9.0% |
| TO_BOOL_BOOL | 2,249,566 | 8.9% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,920 | 99.8% |
| LOAD_ATTR | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,980 | 50.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 11,960 | 49.9% |
| CALL | 20 | 0.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,275,722 | 52.5% |
| LOAD_FAST | 1,165,752 | 26.9% |
| BINARY_SLICE | 251,960 | 5.8% |
| LOAD_CONST | 132,180 | 3.0% |
| STORE_FAST_LOAD_FAST | 108,620 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,884,359 | 43.4% |
| LOAD_CONST | 813,214 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 578,903 | 13.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 227,960 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 204,040 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,985,104 | 68.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,738,557 | 19.9% |
| LOAD_ATTR_SLOT | 588,962 | 6.7% |
| LOAD_DEREF | 123,002 | 1.4% |
| LOAD_FAST_LOAD_FAST | 107,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,461,635 | 51.0% |
| LOAD_FAST | 2,763,531 | 31.6% |
| LOAD_FAST_LOAD_FAST | 675,162 | 7.7% |
| LOAD_CONST | 431,960 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 143,180 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,068,514 | 99.5% |
| LOAD_ATTR_MODULE | 11,960 | 0.4% |
| LOAD_ATTR | 2,940 | 0.1% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,681,942 | 54.5% |
| LOAD_ATTR_CLASS | 455,800 | 14.8% |
| CALL_ISINSTANCE | 298,800 | 9.7% |
| LOAD_GLOBAL_MODULE | 143,800 | 4.7% |
| LOAD_ATTR | 132,240 | 4.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 204,020 | 54.8% |
| LOAD_FAST_LOAD_FAST | 84,020 | 22.6% |
| LOAD_FAST | 71,960 | 19.3% |
| LOAD_DEREF | 11,960 | 3.2% |
| LOAD_ATTR | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 155,880 | 41.8% |
| COMPARE_OP_INT | 119,920 | 32.2% |
| LOAD_FAST | 36,060 | 9.7% |
| STORE_FAST | 35,980 | 9.7% |
| CONTAINS_OP | 23,960 | 6.4% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 72,000 | 59.7% |
| LOAD_FAST | 48,260 | 40.0% |
| LOAD_ATTR | 220 | 0.2% |
| RETURN_VALUE | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 83,920 | 69.6% |
| RESUME_CHECK | 36,640 | 30.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,608,270 | 94.5% |
| BINARY_SUBSCR_TUPLE_INT | 120,040 | 4.3% |
| BINARY_SUBSCR_LIST_INT | 13,316 | 0.5% |
| LOAD_DEREF | 11,960 | 0.4% |
| LOAD_ATTR_SLOT | 5,548 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 855,964 | 31.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 588,962 | 21.3% |
| LOAD_FAST | 349,384 | 12.7% |
| COMPARE_OP_FLOAT | 332,441 | 12.0% |
| TO_BOOL_BOOL | 303,004 | 11.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,644 | 99.9% |
| LOAD_ATTR | 660 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 312 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 335,900 | 43.9% |
| LOAD_CONST | 95,960 | 12.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,752 | 10.8% |
| LOAD_ATTR_METHOD_NO_DICT | 59,960 | 7.8% |
| RETURN_VALUE | 35,980 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,777,672 | 39.9% |
| LOAD_FAST | 797,400 | 11.5% |
| POP_JUMP_IF_FALSE | 640,708 | 9.2% |
| STORE_FAST | 483,698 | 7.0% |
| POP_JUMP_IF_TRUE | 449,400 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,140,289 | 73.9% |
| CALL_ISINSTANCE | 437,100 | 6.3% |
| LOAD_DEREF | 401,382 | 5.8% |
| CHECK_EXC_MATCH | 391,109 | 5.6% |
| BUILD_TUPLE | 156,640 | 2.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,181,612 | 20.7% |
| RESUME_CHECK | 1,968,303 | 18.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,043,920 | 9.9% |
| POP_JUMP_IF_FALSE | 1,008,424 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 785,360 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,068,514 | 29.1% |
| LOAD_FAST | 2,138,519 | 20.3% |
| CALL_ISINSTANCE | 1,131,323 | 10.7% |
| LOAD_FAST_LOAD_FAST | 1,093,580 | 10.4% |
| CALL | 590,051 | 5.6% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,880 | 99.9% |
| LOAD_SUPER_ATTR | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 83,920 | 69.9% |
| PUSH_NULL | 36,020 | 30.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,040 | 93.7% |
| LOAD_DEREF | 11,960 | 6.2% |
| LOAD_SUPER_ATTR | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 86,000 | 44.3% |
| CALL_PY_EXACT_ARGS | 59,200 | 30.5% |
| LOAD_FAST | 25,080 | 12.9% |
| CALL | 12,020 | 6.2% |
| LOAD_CONST | 11,980 | 6.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,203,466 | 52.1% |
| CACHE | 5,376,256 | 27.4% |
| COPY_FREE_VARS | 732,353 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 556,605 | 2.8% |
| BINARY_SUBSCR_GETITEM | 492,660 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,390,698 | 58.2% |
| LOAD_GLOBAL_BUILTIN | 2,777,672 | 14.2% |
| LOAD_GLOBAL_MODULE | 1,968,303 | 10.0% |
| NOP | 1,203,664 | 6.1% |
| LOAD_CONST | 652,042 | 3.3% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 179,600 | 62.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 108,000 | 37.5% |
| SEND | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 179,800 | 62.5% |
| RESUME_CHECK | 107,820 | 37.5% |
| RESUME | 180 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,942,391 | 60.9% |
| LOAD_FAST_LOAD_FAST | 1,992,573 | 24.5% |
| SWAP | 924,388 | 11.4% |
| LOAD_DEREF | 155,680 | 1.9% |
| STORE_FAST_LOAD_FAST | 83,920 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,813,565 | 34.7% |
| LOAD_CONST | 1,673,096 | 20.6% |
| LOAD_FAST_LOAD_FAST | 997,280 | 12.3% |
| LOAD_GLOBAL_MODULE | 785,360 | 9.7% |
| RETURN_CONST | 760,630 | 9.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,808,891 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,797,788 | 49.7% |
| STORE_ATTR_SLOT | 13,067 | 0.4% |
| STORE_ATTR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,303,986 | 36.0% |
| LOAD_CONST | 1,047,824 | 28.9% |
| LOAD_FAST | 618,402 | 17.1% |
| RETURN_CONST | 613,182 | 16.9% |
| ENTER_EXECUTOR | 23,345 | 0.6% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,868 | 79.4% |
| LOAD_FAST_LOAD_FAST | 11,960 | 20.3% |
| STORE_ATTR_INSTANCE_VALUE | 104 | 0.2% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,920 | 81.2% |
| RETURN_CONST | 10,992 | 18.6% |
| STORE_ATTR_INSTANCE_VALUE | 100 | 0.2% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 492,240 | 87.1% |
| LOAD_ATTR | 48,020 | 8.5% |
| CALL_BUILTIN_O | 23,920 | 4.2% |
| STORE_SUBSCR | 340 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 312,260 | 55.3% |
| RETURN_CONST | 216,200 | 38.3% |
| LOAD_GLOBAL_MODULE | 24,200 | 4.3% |
| POP_EXCEPT | 12,000 | 2.1% |
| LOAD_CONST | 140 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 50.0% |
| LOAD_CONST | 80 | 33.3% |
| STORE_SUBSCR | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 50.0% |
| EXTENDED_ARG | 60 | 25.0% |
| JUMP_FORWARD | 60 | 25.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,160 | 75.0% |
| CALL | 11,960 | 24.8% |
| TO_BOOL | 120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 24,260 | 50.3% |
| POP_JUMP_IF_TRUE | 23,980 | 49.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,249,566 | 25.7% |
| RETURN_VALUE | 1,887,222 | 21.6% |
| CALL_ISINSTANCE | 1,880,223 | 21.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 927,442 | 10.6% |
| LOAD_FAST | 402,194 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,366,845 | 72.8% |
| POP_JUMP_IF_TRUE | 2,242,439 | 25.7% |
| EXTENDED_ARG | 119,920 | 1.4% |
| UNARY_NOT | 11,980 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 324,640 | 41.1% |
| BINARY_OP | 290,247 | 36.7% |
| COPY | 162,720 | 20.6% |
| LOAD_ATTR | 11,960 | 1.5% |
| TO_BOOL | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 528,631 | 66.9% |
| POP_JUMP_IF_TRUE | 261,750 | 33.1% |
| TO_BOOL_NONE | 106 | 0.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 137,573 | 98.9% |
| LOAD_FAST | 720 | 0.5% |
| STORE_FAST_LOAD_FAST | 520 | 0.4% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 138,053 | 99.3% |
| POP_JUMP_IF_TRUE | 920 | 0.7% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 855,964 | 60.3% |
| COPY | 190,740 | 13.4% |
| LOAD_FAST | 189,696 | 13.4% |
| LOAD_ATTR | 83,800 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 72,040 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,214,534 | 85.6% |
| POP_JUMP_IF_TRUE | 203,846 | 14.4% |
| TO_BOOL | 189 | 0.0% |
| TO_BOOL_STR | 120 | 0.0% |
| TO_BOOL_INT | 100 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,060 | 79.1% |
| COPY | 36,180 | 12.5% |
| LOAD_ATTR | 11,960 | 4.1% |
| CALL_BUILTIN_FAST | 5,740 | 2.0% |
| ENTER_EXECUTOR | 5,640 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 240,200 | 83.0% |
| POP_JUMP_IF_FALSE | 49,200 | 17.0% |
| TO_BOOL_NONE | 100 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 119,920 | 100.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 119,960 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 24,080 | 28.6% |
| LOAD_FAST | 12,080 | 14.3% |
| END_SEND | 11,960 | 14.2% |
| BINARY_SUBSCR_DICT | 11,960 | 14.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 11,960 | 14.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 72,300 | 85.8% |
| LOAD_FAST | 11,980 | 14.2% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 180,180 | 24.8% |
| RETURN_VALUE | 156,480 | 21.5% |
| FOR_ITER | 108,000 | 14.9% |
| YIELD_VALUE | 107,960 | 14.8% |
| STORE_FAST | 57,008 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 714,845 | 98.3% |
| LOAD_FAST | 12,040 | 1.7% |
| STORE_FAST | 340 | 0.0% |
| STORE_DEREF | 20 | 0.0% |


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
|     deferred | 1,096,237 | 31.4% |
|          hit | 2,389,430 | 68.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 960 | 10.9% |
| Failure | 7,840 | 89.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,496 | 44.6% |
| add other | 1,420 | 18.1% |
| or | 1,240 | 15.8% |
| remainder | 880 | 11.2% |
| add different types | 480 | 6.1% |
| floor divide | 180 | 2.3% |
| multiply different types | 84 | 1.1% |
| true divide other | 60 | 0.8% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>


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
|     deferred | 338,980 | 15.8% |
|          hit | 1,803,693 | 84.0% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 27.3% |
| Failure | 2,720 | 72.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 2,400 | 88.2% |
| other | 160 | 5.9% |
| out of range | 160 | 5.9% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,198,534 | 22.0% |
|          hit | 21,588,979 | 76.5% |
|         miss | 363,973 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,462 | 41.5% |
| Failure | 31,728 | 58.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 6,304 | 19.9% |
| class no vectorcall | 5,460 | 17.2% |
| meth descr method fastcall keywords | 3,860 | 12.2% |
| cfunc noargs | 3,453 | 10.9% |
| meth descr varargs | 3,025 | 9.5% |
| cfunc varargs keywords | 2,260 | 7.1% |
| other | 1,726 | 5.4% |
| class mutable | 1,460 | 4.6% |
| meth descr varargs keywords | 1,300 | 4.1% |
| no dict | 820 | 2.6% |
| init not simple | 680 | 2.1% |
| cfunc varargs | 520 | 1.6% |
| operator wrapper | 500 | 1.6% |
| wrong number arguments | 180 | 0.6% |
| cmethod | 160 | 0.5% |
| init not python | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 181,305 | 4.3% |
|          hit | 4,018,589 | 95.6% |
|         miss | 1,184 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,972 | 50.4% |
| Failure | 1,940 | 49.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 480 | 24.7% |
| bytes | 360 | 18.6% |
| other | 340 | 17.5% |
| float long | 320 | 16.5% |
| tuple | 180 | 9.3% |
| big int | 160 | 8.2% |
| baseobject | 60 | 3.1% |
| bool | 40 | 2.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 353,729 | 30.1% |
|          hit | 818,793 | 69.6% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 30.5% |
| Failure | 2,320 | 69.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 1,340 | 57.8% |
| set | 240 | 10.3% |
| dict keys | 240 | 10.3% |
| other | 180 | 7.8% |
| bytes | 160 | 6.9% |
| ascii string | 120 | 5.2% |
| enumerate | 40 | 1.7% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,512,086 | 10.7% |
|          hit | 45,649,662 | 88.3% |
|         miss | 455,308 | 0.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,419 | 49.9% |
| Failure | 37,606 | 50.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 8,180 | 21.8% |
| method | 8,076 | 21.5% |
| not managed dict | 7,090 | 18.9% |
| not in keys | 6,880 | 18.3% |
| shadowed | 1,880 | 5.0% |
| module attr not found | 1,600 | 4.3% |
| non overriding descriptor | 1,220 | 3.2% |
| metaclass attribute | 920 | 2.4% |
| class attr descriptor | 540 | 1.4% |
| class method obj | 460 | 1.2% |
| non object slot | 380 | 1.0% |
| overridden | 180 | 0.5% |
| builtin class method | 160 | 0.4% |
| mutable class | 40 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 15,460 | 0.1% |
|        deopt | 980 | 0.0% |
|          hit | 17,495,413 | 99.8% |
|         miss | 6,500 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 14,240 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 500 | 0.2% |
|          hit | 314,260 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 100.0% |
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
|     deferred | 336,200 | 53.7% |
|          hit | 287,800 | 46.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 9.9% |
| Failure | 1,820 | 90.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,820 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 263,649 | 2.2% |
|          hit | 11,090,039 | 91.8% |
|         miss | 707,771 | 5.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 21,331 | 83.8% |
| Failure | 4,120 | 16.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,660 | 40.3% |
| not in keys | 680 | 16.5% |
| method | 480 | 11.7% |
| property | 480 | 11.7% |
| not in dict | 480 | 11.7% |
| not managed dict | 240 | 5.8% |
| overridden | 100 | 2.4% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240,780 | 29.8% |
|          hit | 565,320 | 69.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 17.8% |
| Failure | 1,760 | 82.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 1,440 | 81.8% |
| dict subclass no override | 320 | 18.2% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,246,306 | 9.8% |
|          hit | 11,392,886 | 89.8% |
|         miss | 34,407 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,889 | 56.7% |
| Failure | 6,036 | 43.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 1,866 | 30.9% |
| bytes | 1,105 | 18.3% |
| float | 960 | 15.9% |
| dict | 620 | 10.3% |
| mapping | 525 | 8.7% |
| bytearray | 420 | 7.0% |
| tuple | 360 | 6.0% |
| set | 180 | 3.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,920 | 1.4% |
|          hit | 931,485 | 98.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 880 | 84.6% |
| Failure | 160 | 15.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 160 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 176,913,744 | 49.4% |
| Not specialized | 41,638,698 | 11.6% |
| Specialized hits | 137,749,368 | 38.5% |
| Specialized misses | 1,570,574 | 0.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,198,534 | 39.2% |
| LOAD_ATTR | 5,512,086 | 34.9% |
| TO_BOOL | 1,246,306 | 7.9% |
| BINARY_OP | 1,096,237 | 6.9% |
| FOR_ITER | 353,729 | 2.2% |
| BINARY_SUBSCR | 338,980 | 2.1% |
| SEND | 336,200 | 2.1% |
| STORE_ATTR | 263,649 | 1.7% |
| STORE_SUBSCR | 240,780 | 1.5% |
| COMPARE_OP | 181,305 | 1.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 696,139 | 44.3% |
| LOAD_ATTR_SLOT | 296,543 | 18.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 136,729 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 124,973 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,550 | 5.3% |
| CALL_PY_EXACT_ARGS | 65,191 | 4.1% |
| CALL_METHOD_DESCRIPTOR_O | 36,840 | 2.3% |
| LOAD_ATTR_METHOD_NO_DICT | 28,099 | 1.8% |
| TO_BOOL_NONE | 22,100 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 19,476 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 5,737,860 | 29.0% |
| Calls to Python functions inlined | 14,074,620 | 71.0% |
| Calls via PyEval_EvalFrame (total) | 5,737,860 | 29.0% |
| Calls via PyEval_EvalFrame (vector) | 5,387,280 | 27.2% |
| Calls via PyEval_EvalFrame (generator) | 350,580 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 5,386,980 | 27.2% |
| Calls via PyEval_EvalFrame (build class) | 220 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 1,095,001 | 5.5% |
| Calls via PyEval_EvalFrame (function ex) | 132,520 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 206,300 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 915,562 | 4.6% |
| Frame objects created | 824,528 | 4.2% |
| Frames pushed | 13,466,941 | 68.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,852,807 | 40.0% |
| Frees to freelist | 11,907,317 |  |
| Allocations | 17,749,170 | 60.0% |
| Allocations to 512 bytes | 17,425,239 | 58.9% |
| Allocations to 4 kbytes | 91,012 | 0.3% |
| Allocations over 4 kbytes | 232,919 | 0.8% |
| Frees | 18,014,137 |  |
| New values | 158,420 |  |
| Interpreter increfs | 187,691,933 | 77.4% |
| Interpreter decrefs | 202,575,726 | 75.0% |
| Increfs | 54,715,687 | 22.6% |
| Decrefs | 67,646,354 | 25.0% |
| Materialize dict (on request) | 200 | 0.1% |
| Materialize dict (new key) | 24,000 | 15.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 140 | 0.1% |
| Method cache hits | 10,309,363 |  |
| Method cache misses | 408,111 |  |
| Method cache collisions | 455,640 |  |
| Method cache dunder hits | 6,834,968 |  |
| Method cache dunder misses | 52,491 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 1,235 | 1,920 | 12,991,856 |
| 1 | 121 | 11 | 4,344,986 |
| 2 | 3 | 99 | 937,506 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 800 |  |
| Traces created | 660 | 82.5% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 2.5% |
| Trace too long | 40 | 5.0% |
| Trace too short | 140 | 17.5% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 1,264,261 |  |
| Uops executed | 55,160,521 | 43.63 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 9.1% |
| <= 32 | 260 | 39.4% |
| <= 64 | 120 | 18.2% |
| <= 128 | 220 | 33.3% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 3.0% |
| <= 16 | 120 | 18.2% |
| <= 32 | 240 | 36.4% |
| <= 64 | 100 | 15.2% |
| <= 128 | 180 | 27.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 237,323 | 18.8% |
| <= 16 | 272,836 | 21.6% |
| <= 32 | 56,785 | 4.5% |
| <= 64 | 122,883 | 9.7% |
| <= 128 | 572,166 | 45.3% |
| <= 256 | 305 | 0.0% |
| <= 512 | 669 | 0.1% |
| <= 1,024 | 1,035 | 0.1% |
| <= 2,048 | 216 | 0.0% |
| <= 4,096 | 25 | 0.0% |
| <= 8,192 | 18 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 14,455,426 | 26.2% | 26.2% |  |
| LOAD_FAST | 5,317,129 | 9.6% | 35.8% |  |
| _GUARD_TYPE_VERSION | 4,664,668 | 8.5% | 44.3% |  |
| _POP_JUMP_IF_TRUE | 2,571,833 | 4.7% | 49.0% |  |
| STORE_FAST | 2,036,698 | 3.7% | 52.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,634,258 | 3.0% | 55.6% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,634,258 | 3.0% | 58.6% |  |
| _LOAD_ATTR_SLOT | 1,559,522 | 2.8% | 61.4% |  |
| _EXIT_TRACE | 1,239,228 | 2.2% | 63.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 1,113,075 | 2.0% | 65.7% |  |
| TO_BOOL_BOOL | 1,110,589 | 2.0% | 67.7% |  |
| LOAD_CONST | 996,964 | 1.8% | 69.5% |  |
| _GUARD_GLOBALS_VERSION | 923,286 | 1.7% | 71.2% | 0.1% |
| _CHECK_PEP_523 | 666,552 | 1.2% | 72.4% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 666,552 | 1.2% | 73.6% |  |
| _CHECK_STACK_SPACE | 666,552 | 1.2% | 74.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 666,552 | 1.2% | 76.0% |  |
| _PUSH_FRAME | 666,552 | 1.2% | 77.2% |  |
| _SAVE_RETURN_OFFSET | 666,552 | 1.2% | 78.4% |  |
| _ITER_CHECK_LIST | 647,107 | 1.2% | 79.6% |  |
| _IS_ITER_EXHAUSTED_LIST | 647,107 | 1.2% | 80.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 560,800 | 1.0% | 81.8% |  |
| _LOAD_ATTR | 550,738 | 1.0% | 82.8% |  |
| RESUME_CHECK | 546,891 | 1.0% | 83.8% |  |
| _POP_JUMP_IF_FALSE | 487,134 | 0.9% | 84.7% |  |
| _LOAD_GLOBAL_MODULE | 464,189 | 0.8% | 85.5% |  |
| _ITER_CHECK_RANGE | 462,721 | 0.8% | 86.3% |  |
| _IS_ITER_EXHAUSTED_RANGE | 462,721 | 0.8% | 87.2% |  |
| _GUARD_BUILTINS_VERSION | 458,077 | 0.8% | 88.0% |  |
| _LOAD_GLOBAL_BUILTINS | 458,077 | 0.8% | 88.8% |  |
| _ITER_NEXT_RANGE | 435,004 | 0.8% | 89.6% |  |
| _ITER_NEXT_LIST | 415,206 | 0.8% | 90.4% |  |
| PUSH_NULL | 387,104 | 0.7% | 91.1% |  |
| POP_TOP | 368,734 | 0.7% | 91.7% |  |
| BUILD_LIST | 363,764 | 0.7% | 92.4% |  |
| CALL_INTRINSIC_1 | 363,764 | 0.7% | 93.1% |  |
| LIST_EXTEND | 363,764 | 0.7% | 93.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 247,500 | 0.4% | 94.2% |  |
| _GUARD_KEYS_VERSION | 247,500 | 0.4% | 94.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 235,800 | 0.4% | 95.0% |  |
| _JUMP_TO_TOP | 196,473 | 0.4% | 95.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 178,181 | 0.3% | 95.7% |  |
| _IS_NONE | 164,491 | 0.3% | 96.0% |  |
| TO_BOOL_INT | 157,626 | 0.3% | 96.3% |  |
| COMPARE_OP_INT | 146,917 | 0.3% | 96.6% |  |
| CALL_ISINSTANCE | 143,280 | 0.3% | 96.8% |  |
| CALL_LEN | 122,957 | 0.2% | 97.1% |  |
| _TO_BOOL | 121,079 | 0.2% | 97.3% |  |
| CONTAINS_OP | 108,200 | 0.2% | 97.5% |  |
| _BINARY_OP | 104,303 | 0.2% | 97.7% |  |
| COPY | 89,675 | 0.2% | 97.8% |  |
| _BINARY_SUBSCR | 83,700 | 0.2% | 98.0% |  |
| _GUARD_DORV_VALUES | 80,038 | 0.1% | 98.1% |  |
| _STORE_ATTR_INSTANCE_VALUE | 80,038 | 0.1% | 98.3% |  |
| SWAP | 78,371 | 0.1% | 98.4% |  |
| _ITER_CHECK_TUPLE | 63,720 | 0.1% | 98.5% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 63,720 | 0.1% | 98.6% |  |
| BUILD_TUPLE | 58,836 | 0.1% | 98.8% |  |
| LOAD_FAST_CHECK | 56,658 | 0.1% | 98.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 56,658 | 0.1% | 99.0% |  |
| _CHECK_ATTR_MODULE | 54,411 | 0.1% | 99.1% |  |
| _LOAD_ATTR_MODULE | 54,411 | 0.1% | 99.2% |  |
| _ITER_NEXT_TUPLE | 49,880 | 0.1% | 99.2% |  |
| CALL_BUILTIN_FAST | 48,560 | 0.1% | 99.3% |  |
| TO_BOOL_NONE | 47,760 | 0.1% | 99.4% | 25.0% |
| MAKE_CELL | 44,645 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 42,634 | 0.1% | 99.6% |  |
| LOAD_DEREF | 35,020 | 0.1% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 32,239 | 0.1% | 99.7% |  |
| TO_BOOL_LIST | 31,072 | 0.1% | 99.8% |  |
| _STORE_ATTR_SLOT | 30,275 | 0.1% | 99.8% |  |
| _GUARD_BOTH_INT | 23,360 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 23,100 | 0.0% | 99.9% |  |
| _BINARY_OP_SUBTRACT_INT | 23,100 | 0.0% | 99.9% |  |
| _POP_FRAME | 11,980 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,700 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 8,305 | 0.0% | 100.0% |  |
| LIST_APPEND | 680 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 660 | 0.0% | 100.0% |  |
| IS_OP | 500 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 260 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 220 | 0.0% | 100.0% | 27.3% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 220 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 220 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 160 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 60 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| GET_ITER | 40 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 40 | 0.0% | 100.0% |  |
| STORE_DEREF | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 140 |
| FOR_ITER | 100 |
| CALL_LIST_APPEND | 94 |
| YIELD_VALUE | 40 |
| FOR_ITER_GEN | 40 |
| CALL_FUNCTION_EX | 20 |
| CALL_KW | 20 |
| CALL_ALLOC_AND_ENTER_INIT | 20 |


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
Stats gathered on: 2023-11-08
