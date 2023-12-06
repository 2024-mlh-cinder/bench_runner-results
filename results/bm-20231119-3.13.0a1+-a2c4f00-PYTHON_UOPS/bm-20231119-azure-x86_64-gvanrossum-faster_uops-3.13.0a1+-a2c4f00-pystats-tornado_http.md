
# Pystats results

- benchmark: tornado_http
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 73,982,578 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 25,179,952 | 7.1% | 27.8% | 0.1% |
| RESUME_CHECK | 19,566,042 | 5.5% | 33.2% | 0.0% |
| LOAD_CONST | 15,998,417 | 4.5% | 37.7% |  |
| POP_JUMP_IF_FALSE | 14,061,154 | 3.9% | 41.7% |  |
| RETURN_VALUE | 11,570,461 | 3.2% | 44.9% |  |
| CALL_PY_EXACT_ARGS | 10,872,919 | 3.0% | 47.9% | 0.6% |
| STORE_FAST | 10,708,179 | 3.0% | 50.9% |  |
| LOAD_GLOBAL_MODULE | 10,549,118 | 3.0% | 53.9% | 0.0% |
| LOAD_FAST_LOAD_FAST | 10,138,034 | 2.8% | 56.7% |  |
| POP_TOP | 10,094,032 | 2.8% | 59.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,755,978 | 2.5% | 62.0% | 0.9% |
| TO_BOOL_BOOL | 8,728,096 | 2.4% | 64.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 8,117,990 | 2.3% | 66.7% | 0.1% |
| RETURN_CONST | 7,886,342 | 2.2% | 68.9% |  |
| LOAD_GLOBAL_BUILTIN | 6,968,277 | 2.0% | 70.9% | 0.1% |
| CALL | 6,253,784 | 1.8% | 72.6% |  |
| INTERPRETER_EXIT | 5,725,407 | 1.6% | 74.3% |  |
| LOAD_ATTR | 5,588,013 | 1.6% | 75.8% |  |
| POP_JUMP_IF_NONE | 5,412,330 | 1.5% | 77.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,311,472 | 1.2% | 78.5% | 0.7% |
| POP_JUMP_IF_TRUE | 4,047,332 | 1.1% | 79.7% |  |
| STORE_ATTR_SLOT | 3,603,543 | 1.0% | 80.7% | 19.3% |
| COMPARE_OP_INT | 3,408,773 | 1.0% | 81.6% | 0.0% |
| PUSH_NULL | 3,218,327 | 0.9% | 82.5% |  |
| LOAD_ATTR_MODULE | 3,062,741 | 0.9% | 83.4% | 0.0% |
| NOP | 2,991,222 | 0.8% | 84.2% |  |
| LOAD_ATTR_SLOT | 2,748,024 | 0.8% | 85.0% | 10.8% |
| COPY | 2,399,083 | 0.7% | 85.7% |  |
| LOAD_DEREF | 2,094,602 | 0.6% | 86.3% |  |
| CALL_ISINSTANCE | 2,084,141 | 0.6% | 86.8% |  |
| POP_JUMP_IF_NOT_NONE | 1,668,788 | 0.5% | 87.3% |  |
| CALL_BUILTIN_FAST | 1,654,780 | 0.5% | 87.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,512,671 | 0.4% | 88.2% | 8.3% |
| TO_BOOL_NONE | 1,418,835 | 0.4% | 88.6% | 1.6% |
| SWAP | 1,383,401 | 0.4% | 89.0% |  |
| ENTER_EXECUTOR | 1,350,511 | 0.4% | 89.4% |  |
| BUILD_TUPLE | 1,306,505 | 0.4% | 89.7% |  |
| TO_BOOL | 1,266,608 | 0.4% | 90.1% |  |
| BINARY_OP | 1,095,305 | 0.3% | 90.4% |  |
| BINARY_OP_ADD_INT | 1,083,969 | 0.3% | 90.7% |  |
| CALL_FUNCTION_EX | 1,080,905 | 0.3% | 91.0% |  |
| CALL_LEN | 1,002,484 | 0.3% | 91.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 981,242 | 0.3% | 91.6% | 3.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 957,693 | 0.3% | 91.8% |  |
| BUILD_LIST | 887,126 | 0.2% | 92.1% |  |
| STORE_FAST_STORE_FAST | 885,480 | 0.2% | 92.3% |  |
| BINARY_SUBSCR_DICT | 880,755 | 0.2% | 92.6% |  |
| BINARY_OP_SUBTRACT_INT | 837,856 | 0.2% | 92.8% |  |
| CONTAINS_OP | 799,440 | 0.2% | 93.0% |  |
| BUILD_MAP | 793,640 | 0.2% | 93.2% |  |
| COPY_FREE_VARS | 782,071 | 0.2% | 93.5% |  |
| LOAD_ATTR_WITH_HINT | 764,664 | 0.2% | 93.7% | 2.1% |
| TO_BOOL_INT | 761,889 | 0.2% | 93.9% | 0.8% |
| JUMP_FORWARD | 747,805 | 0.2% | 94.1% |  |
| LOAD_ATTR_CLASS | 732,052 | 0.2% | 94.3% | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 712,424 | 0.2% | 94.5% |  |
| GET_ITER | 706,267 | 0.2% | 94.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 644,380 | 0.2% | 94.9% |  |
| YIELD_VALUE | 577,520 | 0.2% | 95.0% |  |
| FOR_ITER_LIST | 573,115 | 0.2% | 95.2% |  |
| IS_OP | 568,900 | 0.2% | 95.4% |  |
| CALL_PY_WITH_DEFAULTS | 568,709 | 0.2% | 95.5% |  |
| STORE_SUBSCR_DICT | 565,080 | 0.2% | 95.7% |  |
| BINARY_SLICE | 554,160 | 0.2% | 95.8% |  |
| BINARY_SUBSCR_GETITEM | 492,680 | 0.1% | 96.0% |  |
| DICT_MERGE | 480,760 | 0.1% | 96.1% |  |
| CALL_KW | 463,129 | 0.1% | 96.2% |  |
| GET_AWAITABLE | 456,000 | 0.1% | 96.4% |  |
| PUSH_EXC_INFO | 453,677 | 0.1% | 96.5% |  |
| POP_EXCEPT | 453,557 | 0.1% | 96.6% |  |
| END_SEND | 444,000 | 0.1% | 96.7% |  |
| CHECK_EXC_MATCH | 443,970 | 0.1% | 96.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 372,500 | 0.1% | 97.0% | 3.2% |
| MAKE_FUNCTION | 365,748 | 0.1% | 97.1% |  |
| MAKE_CELL | 363,485 | 0.1% | 97.2% |  |
| COMPARE_OP_FLOAT | 356,103 | 0.1% | 97.3% | 0.0% |
| BINARY_SUBSCR | 342,740 | 0.1% | 97.4% |  |
| SEND | 338,220 | 0.1% | 97.5% |  |
| RETURN_GENERATOR | 337,000 | 0.1% | 97.6% |  |
| EXIT_INIT_CHECK | 324,640 | 0.1% | 97.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 324,640 | 0.1% | 97.7% |  |
| LIST_EXTEND | 314,104 | 0.1% | 97.8% |  |
| CALL_INTRINSIC_1 | 302,084 | 0.1% | 97.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 293,885 | 0.1% | 98.0% | 46.5% |
| TO_BOOL_STR | 289,500 | 0.1% | 98.1% | 2.0% |
| STORE_ATTR | 289,120 | 0.1% | 98.2% |  |
| SEND_GEN | 287,800 | 0.1% | 98.2% |  |
| COMPARE_OP_STR | 277,940 | 0.1% | 98.3% | 0.0% |
| FOR_ITER_GEN | 275,940 | 0.1% | 98.4% |  |
| CALL_LIST_APPEND | 257,068 | 0.1% | 98.5% |  |
| CALL_BUILTIN_CLASS | 247,059 | 0.1% | 98.5% |  |
| BEFORE_WITH | 233,949 | 0.1% | 98.6% |  |
| JUMP_BACKWARD | 231,340 | 0.1% | 98.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 229,280 | 0.1% | 98.7% |  |
| BINARY_OP_ADD_UNICODE | 228,560 | 0.1% | 98.8% |  |
| STORE_SUBSCR | 219,120 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 212,776 | 0.1% | 98.9% |  |
| DELETE_FAST | 208,389 | 0.1% | 99.0% |  |
| STORE_FAST_LOAD_FAST | 206,440 | 0.1% | 99.0% |  |
| EXTENDED_ARG | 206,260 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 205,260 | 0.1% | 99.1% |  |
| FOR_ITER | 201,877 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 194,280 | 0.1% | 99.3% |  |
| COMPARE_OP | 184,718 | 0.1% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 168,000 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 146,736 | 0.0% | 99.4% | 0.1% |
| BINARY_OP_ADD_FLOAT | 121,884 | 0.0% | 99.4% |  |
| STORE_DEREF | 121,560 | 0.0% | 99.5% |  |
| LOAD_ATTR_PROPERTY | 120,560 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 120,440 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 119,980 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 119,960 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 108,700 | 0.0% | 99.6% | 0.1% |
| FOR_ITER_TUPLE | 100,520 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 91,730 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 84,280 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 76,538 | 0.0% | 99.7% | 0.1% |
| LOAD_FAST_AND_CLEAR | 73,440 | 0.0% | 99.8% |  |
| BUILD_SLICE | 72,060 | 0.0% | 99.8% |  |
| RERAISE | 72,020 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 60,400 | 0.0% | 99.8% |  |
| CONVERT_VALUE | 60,320 | 0.0% | 99.8% |  |
| UNARY_INVERT | 60,180 | 0.0% | 99.8% |  |
| END_FOR | 59,980 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 59,028 | 0.0% | 99.9% | 9.0% |
| FOR_ITER_RANGE | 59,003 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 56,684 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 48,240 | 0.0% | 99.9% | 0.1% |
| LOAD_FAST_CHECK | 40,088 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 28,720 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 28,148 | 0.0% | 99.9% | 0.9% |
| RAISE_VARARGS | 24,420 | 0.0% | 100.0% |  |
| BUILD_STRING | 24,240 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 23,960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 13,960 | 0.0% | 100.0% |  |
| LIST_APPEND | 13,120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 12,798 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 12,240 | 0.0% | 100.0% |  |
| UNARY_NOT | 12,140 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 12,080 | 0.0% | 100.0% |  |
| BUILD_SET | 12,020 | 0.0% | 100.0% |  |
| RESUME | 9,300 | 0.0% | 100.0% | 12.7% |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,800,231 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 11,357,070 | 3.2% | 9.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,199,773 | 2.9% | 12.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,417,025 | 2.1% | 14.2% |
| STORE_FAST LOAD_FAST | 6,660,675 | 1.9% | 16.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,373,733 | 1.8% | 17.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,983,062 | 1.7% | 19.5% |
| CACHE RESUME_CHECK | 5,376,331 | 1.5% | 21.0% |
| RETURN_CONST POP_TOP | 5,200,709 | 1.5% | 22.5% |
| LOAD_CONST LOAD_FAST | 5,158,041 | 1.4% | 23.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,153,841 | 1.4% | 25.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,941,367 | 1.4% | 26.8% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,470,362 | 1.3% | 28.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,460,232 | 1.2% | 29.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 4,182,123 | 1.2% | 30.4% |
| POP_TOP LOAD_FAST | 3,904,788 | 1.1% | 31.5% |
| RETURN_VALUE INTERPRETER_EXIT | 3,734,995 | 1.0% | 32.6% |
| LOAD_FAST LOAD_ATTR | 3,602,234 | 1.0% | 33.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,349,364 | 0.9% | 34.5% |
| LOAD_FAST LOAD_CONST | 3,337,173 | 0.9% | 35.5% |
| LOAD_FAST RETURN_VALUE | 3,170,500 | 0.9% | 36.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,047,601 | 0.9% | 37.2% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 3,035,552 | 0.9% | 38.1% |
| POP_TOP RETURN_CONST | 2,938,429 | 0.8% | 38.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,812,461 | 0.8% | 39.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,791,520 | 0.8% | 40.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,766,718 | 0.8% | 41.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,690,080 | 0.8% | 42.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,676,065 | 0.7% | 42.7% |
| LOAD_FAST LOAD_ATTR_SLOT | 2,587,875 | 0.7% | 43.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,255,639 | 0.6% | 44.1% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 2,249,438 | 0.6% | 44.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,222,463 | 0.6% | 45.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,177,107 | 0.6% | 45.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,138,434 | 0.6% | 46.5% |
| RETURN_VALUE STORE_FAST | 2,136,152 | 0.6% | 47.1% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,040,150 | 0.6% | 47.7% |
| LOAD_FAST CALL | 2,006,281 | 0.6% | 48.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,992,578 | 0.6% | 48.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,968,070 | 0.6% | 49.4% |
| CALL STORE_FAST | 1,947,402 | 0.5% | 49.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,900,844 | 0.5% | 50.5% |
| RETURN_VALUE TO_BOOL_BOOL | 1,887,288 | 0.5% | 51.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,878,821 | 0.5% | 51.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,869,000 | 0.5% | 52.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,797,972 | 0.5% | 52.5% |
| LOAD_FAST STORE_ATTR_SLOT | 1,792,159 | 0.5% | 53.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,742,517 | 0.5% | 53.5% |
| LOAD_CONST COMPARE_OP_INT | 1,716,909 | 0.5% | 54.0% |
| RETURN_CONST INTERPRETER_EXIT | 1,712,772 | 0.5% | 54.5% |
| NOP LOAD_FAST | 1,695,309 | 0.5% | 55.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,681,742 | 0.5% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,673,166 | 0.5% | 55.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,484,998 | 0.4% | 56.3% |
| PUSH_NULL LOAD_FAST | 1,361,337 | 0.4% | 56.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,304,124 | 0.4% | 57.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,280,672 | 0.4% | 57.4% |
| LOAD_CONST STORE_FAST | 1,221,576 | 0.3% | 57.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 1,214,550 | 0.3% | 58.1% |
| RESUME_CHECK NOP | 1,203,786 | 0.3% | 58.5% |
| LOAD_ATTR LOAD_FAST | 1,176,828 | 0.3% | 58.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,158,817 | 0.3% | 59.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,131,049 | 0.3% | 59.4% |
| LOAD_FAST COPY | 1,117,705 | 0.3% | 59.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,093,580 | 0.3% | 60.0% |
| LOAD_CONST LOAD_CONST | 1,081,695 | 0.3% | 60.3% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,072,507 | 0.3% | 60.6% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,056,435 | 0.3% | 60.9% |
| STORE_ATTR_SLOT LOAD_CONST | 1,047,916 | 0.3% | 61.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,047,284 | 0.3% | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,043,920 | 0.3% | 61.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,008,238 | 0.3% | 62.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 997,280 | 0.3% | 62.4% |
| CALL POP_TOP | 990,361 | 0.3% | 62.7% |
| RETURN_VALUE RETURN_VALUE | 973,720 | 0.3% | 62.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 956,452 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 953,852 | 0.3% | 63.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 927,428 | 0.3% | 63.7% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 924,705 | 0.3% | 64.0% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 924,705 | 0.3% | 64.2% |
| POP_TOP LOAD_CONST | 917,169 | 0.3% | 64.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 901,060 | 0.3% | 64.8% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 894,256 | 0.3% | 65.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 876,497 | 0.2% | 65.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 872,789 | 0.2% | 65.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 857,891 | 0.2% | 65.7% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 856,056 | 0.2% | 66.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 837,640 | 0.2% | 66.2% |
| CALL LOAD_FAST | 825,192 | 0.2% | 66.4% |
| CALL_BUILTIN_FAST STORE_FAST | 814,460 | 0.2% | 66.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 813,355 | 0.2% | 66.9% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 807,914 | 0.2% | 67.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 796,272 | 0.2% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 791,180 | 0.2% | 67.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 785,548 | 0.2% | 67.8% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 763,701 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 760,660 | 0.2% | 68.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 734,568 | 0.2% | 68.4% |
| COPY_FREE_VARS RESUME_CHECK | 732,511 | 0.2% | 68.6% |
| PUSH_NULL CALL | 731,299 | 0.2% | 68.8% |


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
| RESUME_CHECK | 5,376,331 | 93.7% |
| COPY_FREE_VARS | 238,256 | 4.2% |
| POP_TOP | 97,060 | 1.7% |
| MAKE_CELL | 12,360 | 0.2% |
| RETURN_GENERATOR | 12,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 112,489 | 48.1% |
| RETURN_VALUE | 108,100 | 46.2% |
| LOAD_GLOBAL_MODULE | 12,540 | 5.4% |
| CALL | 380 | 0.2% |
| LOAD_ATTR | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 233,869 | 100.0% |
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
| LOAD_CONST | 338,020 | 98.6% |
| BINARY_SUBSCR | 2,940 | 0.9% |
| BUILD_TUPLE | 640 | 0.2% |
| LOAD_FAST | 460 | 0.1% |
| LOAD_NAME | 340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 180,200 | 52.6% |
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
| LOAD_GLOBAL_BUILTIN | 391,341 | 88.1% |
| BUILD_TUPLE | 24,080 | 5.4% |
| LOAD_ATTR_MODULE | 16,269 | 3.7% |
| LOAD_GLOBAL_MODULE | 11,980 | 2.7% |
| LOAD_GLOBAL | 260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 443,970 | 100.0% |


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
| LOAD_FAST | 241,530 | 34.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 144,140 | 20.4% |
| LOAD_ATTR_INSTANCE_VALUE | 96,558 | 13.7% |
| LOAD_ATTR | 72,140 | 10.2% |
| BINARY_SLICE | 36,240 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 320,547 | 45.4% |
| FOR_ITER | 148,161 | 21.0% |
| FOR_ITER_TUPLE | 73,020 | 10.3% |
| CALL_PY_EXACT_ARGS | 72,720 | 10.3% |
| LOAD_FAST_AND_CLEAR | 49,440 | 7.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,734,995 | 65.2% |
| RETURN_CONST | 1,712,772 | 29.9% |
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
| LOAD_CONST | 365,748 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 161,048 | 44.0% |
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
| RESUME_CHECK | 1,203,786 | 40.2% |
| POP_JUMP_IF_FALSE | 449,941 | 15.0% |
| STORE_FAST | 389,326 | 13.0% |
| STORE_ATTR_INSTANCE_VALUE | 306,416 | 10.2% |
| POP_JUMP_IF_TRUE | 274,980 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,695,309 | 56.7% |
| LOAD_GLOBAL_MODULE | 546,981 | 18.3% |
| LOAD_FAST_LOAD_FAST | 300,220 | 10.0% |
| LOAD_DEREF | 134,855 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 120,140 | 4.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 328,848 | 72.5% |
| SWAP | 60,080 | 13.2% |
| COPY | 36,020 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 12,120 | 2.7% |
| STORE_SUBSCR_DICT | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 290,573 | 64.1% |
| RETURN_VALUE | 60,080 | 13.2% |
| RERAISE | 36,020 | 7.9% |
| DELETE_FAST | 24,000 | 5.3% |
| ENTER_EXECUTOR | 15,689 | 3.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,200,709 | 51.5% |
| CALL | 990,361 | 9.8% |
| CALL_METHOD_DESCRIPTOR_O | 807,914 | 8.0% |
| POP_JUMP_IF_FALSE | 605,138 | 6.0% |
| CALL_FUNCTION_EX | 500,376 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,904,788 | 38.7% |
| RETURN_CONST | 2,938,429 | 29.1% |
| LOAD_CONST | 917,169 | 9.1% |
| ENTER_EXECUTOR | 705,020 | 7.0% |
| RESUME_CHECK | 336,620 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 348,440 | 76.8% |
| RERAISE | 36,020 | 7.9% |
| CALL | 30,622 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 12,067 | 2.7% |
| RAISE_VARARGS | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400,908 | 88.4% |
| LOAD_GLOBAL_MODULE | 40,149 | 8.8% |
| LOAD_FAST | 12,000 | 2.6% |
| LOAD_GLOBAL | 620 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,681,742 | 52.3% |
| LOAD_ATTR | 669,133 | 20.8% |
| LOAD_FAST | 468,752 | 14.6% |
| LOAD_DEREF | 204,500 | 6.4% |
| RETURN_VALUE | 132,080 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,361,337 | 42.3% |
| CALL | 731,299 | 22.7% |
| LOAD_FAST_LOAD_FAST | 713,383 | 22.2% |
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
| LOAD_FAST | 3,170,500 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,690,080 | 23.2% |
| RETURN_VALUE | 973,720 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 622,560 | 5.4% |
| CALL | 621,591 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 3,734,995 | 32.3% |
| STORE_FAST | 2,136,152 | 18.5% |
| TO_BOOL_BOOL | 1,887,288 | 16.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| LOAD_FAST | 603,156 | 5.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,580 | 49.6% |
| LOAD_CONST | 96,180 | 43.9% |
| LOAD_FAST_LOAD_FAST | 12,220 | 5.6% |
| STORE_SUBSCR | 1,740 | 0.8% |
| CALL | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 108,240 | 49.4% |
| LOAD_FAST | 48,240 | 22.0% |
| LOAD_CONST | 24,060 | 11.0% |
| LOAD_DEREF | 24,000 | 11.0% |
| ENTER_EXECUTOR | 11,880 | 5.4% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,742 | 44.3% |
| LOAD_ATTR_INSTANCE_VALUE | 521,104 | 41.1% |
| LOAD_ATTR | 122,800 | 9.7% |
| COPY | 36,800 | 2.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,380 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,056,435 | 83.4% |
| POP_JUMP_IF_TRUE | 196,719 | 15.5% |
| TO_BOOL | 5,874 | 0.5% |
| TO_BOOL_BOOL | 5,200 | 0.4% |
| TO_BOOL_NONE | 1,060 | 0.1% |


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
| LOAD_GLOBAL_MODULE | 188,422 | 17.2% |
| LOAD_CONST | 169,758 | 15.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 155,880 | 14.2% |
| LOAD_FAST | 112,215 | 10.2% |
| LOAD_ATTR_CLASS | 96,080 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 270,638 | 24.7% |
| STORE_FAST | 209,239 | 19.1% |
| COPY | 134,894 | 12.3% |
| RETURN_VALUE | 96,120 | 8.8% |
| LOAD_FAST | 95,472 | 8.7% |


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
| STORE_FAST | 111,844 | 12.6% |
| LOAD_FAST_LOAD_FAST | 107,540 | 12.1% |
| RESUME_CHECK | 72,940 | 8.2% |
| SWAP | 49,440 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 662,904 | 74.7% |
| STORE_FAST | 137,482 | 15.5% |
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
| LOAD_FAST | 649,720 | 81.9% |
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
| LOAD_FAST | 512,656 | 39.2% |
| LOAD_FAST_LOAD_FAST | 300,780 | 23.0% |
| LOAD_GLOBAL_BUILTIN | 156,660 | 12.0% |
| LOAD_GLOBAL_MODULE | 99,540 | 7.6% |
| LOAD_ATTR_MODULE | 71,940 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 191,840 | 14.7% |
| RETURN_VALUE | 180,760 | 13.8% |
| LOAD_CONST | 160,668 | 12.3% |
| CALL_ISINSTANCE | 157,200 | 12.0% |
| CONTAINS_OP | 121,400 | 9.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,006,281 | 32.1% |
| PUSH_NULL | 731,299 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 613,100 | 9.8% |
| LOAD_GLOBAL_MODULE | 589,856 | 9.4% |
| LOAD_CONST | 468,415 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,947,402 | 31.1% |
| POP_TOP | 990,361 | 15.8% |
| LOAD_FAST | 825,192 | 13.2% |
| RETURN_VALUE | 621,591 | 9.9% |
| BINARY_SUBSCR_DICT | 420,140 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 480,760 | 44.5% |
| ENTER_EXECUTOR | 364,012 | 33.7% |
| LOAD_FAST | 100,629 | 9.3% |
| CALL_INTRINSIC_1 | 76,224 | 7.1% |
| BUILD_MAP | 59,200 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 500,376 | 46.3% |
| RETURN_VALUE | 221,349 | 20.5% |
| RESUME_CHECK | 132,220 | 12.2% |
| STORE_FAST | 119,360 | 11.0% |
| CALL | 83,300 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 290,084 | 96.0% |
| RERAISE | 12,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 154,660 | 51.2% |
| CALL_FUNCTION_EX | 76,224 | 25.2% |
| LOAD_CONST | 59,200 | 19.6% |
| RERAISE | 12,000 | 4.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 403,449 | 87.1% |
| ENTER_EXECUTOR | 59,680 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 265,420 | 57.3% |
| STORE_FAST | 100,429 | 21.7% |
| COPY_FREE_VARS | 24,000 | 5.2% |
| RETURN_VALUE | 12,440 | 2.7% |
| LOAD_FAST | 12,180 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 119,318 | 64.6% |
| LOAD_ATTR | 24,440 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,340 | 6.7% |
| LOAD_FAST_LOAD_FAST | 12,000 | 6.5% |
| LOAD_ATTR_CLASS | 12,000 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120,076 | 65.0% |
| POP_JUMP_IF_TRUE | 60,580 | 32.8% |
| COMPARE_OP | 1,914 | 1.0% |
| COMPARE_OP_INT | 1,448 | 0.8% |
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
| LOAD_FAST | 109,280 | 13.7% |
| LOAD_FAST_LOAD_FAST | 108,720 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 605,540 | 75.7% |
| COPY | 120,040 | 15.0% |
| POP_JUMP_IF_TRUE | 25,340 | 3.2% |
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
| LOAD_FAST | 1,117,705 | 46.6% |
| LOAD_CONST | 252,200 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 227,980 | 9.5% |
| BINARY_OP | 134,894 | 5.6% |
| CONTAINS_OP | 120,040 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 924,705 | 38.5% |
| LOAD_FAST | 456,000 | 19.0% |
| TO_BOOL_BOOL | 326,140 | 13.6% |
| TO_BOOL_NONE | 190,751 | 8.0% |
| TO_BOOL_INT | 163,147 | 6.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 288,557 | 36.9% |
| CACHE | 238,256 | 30.5% |
| CALL | 120,900 | 15.5% |
| LOAD_ATTR_PROPERTY | 83,920 | 10.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,098 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 732,511 | 93.7% |
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
| POP_TOP | 16,309 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 108,000 | 51.8% |
| RETURN_CONST | 48,000 | 23.0% |
| LOAD_FAST | 28,309 | 13.6% |
| LOAD_CONST | 12,080 | 5.8% |
| ENTER_EXECUTOR | 11,660 | 5.6% |


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
| POP_TOP | 705,020 | 52.2% |
| POP_JUMP_IF_TRUE | 130,306 | 9.6% |
| FOR_ITER_LIST | 107,660 | 8.0% |
| CALL_LIST_APPEND | 98,746 | 7.3% |
| STORE_ATTR_INSTANCE_VALUE | 83,660 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 364,012 | 27.0% |
| FOR_ITER_LIST | 232,449 | 17.2% |
| CALL | 225,761 | 16.7% |
| RESUME_CHECK | 102,753 | 7.6% |
| YIELD_VALUE | 95,400 | 7.1% |


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
| ENTER_EXECUTOR | 340 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 108,000 | 52.4% |
| ENTER_EXECUTOR | 60,200 | 29.2% |
| POP_JUMP_IF_FALSE | 24,680 | 12.0% |
| JUMP_FORWARD | 12,340 | 6.0% |
| JUMP_BACKWARD | 440 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 148,161 | 73.4% |
| SWAP | 24,460 | 12.1% |
| LOAD_FAST | 24,200 | 12.0% |
| JUMP_BACKWARD | 2,641 | 1.3% |
| FOR_ITER | 2,175 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 108,537 | 53.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,360 | 12.1% |
| LOAD_FAST | 24,340 | 12.1% |
| SWAP | 24,080 | 11.9% |
| STORE_FAST | 16,325 | 8.1% |


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
| POP_TOP | 219,340 | 94.8% |
| POP_JUMP_IF_TRUE | 3,040 | 1.3% |
| POP_JUMP_IF_FALSE | 2,140 | 0.9% |
| CALL_LIST_APPEND | 1,840 | 0.8% |
| LIST_APPEND | 960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 215,960 | 93.4% |
| FOR_ITER_LIST | 6,459 | 2.8% |
| FOR_ITER | 2,641 | 1.1% |
| LOAD_FAST | 2,460 | 1.1% |
| FOR_ITER_RANGE | 1,260 | 0.5% |


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
| STORE_FAST | 446,624 | 59.7% |
| POP_TOP | 132,480 | 17.7% |
| STORE_ATTR_INSTANCE_VALUE | 48,358 | 6.5% |
| POP_JUMP_IF_TRUE | 24,400 | 3.3% |
| STORE_ATTR | 24,120 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 479,938 | 64.2% |
| LOAD_CONST | 92,150 | 12.3% |
| LOAD_FAST_LOAD_FAST | 60,340 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 42,337 | 5.7% |
| LOAD_GLOBAL_MODULE | 36,000 | 4.8% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,040 | 91.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 500 | 3.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 320 | 2.4% |
| LOAD_FAST | 240 | 1.8% |
| CALL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,160 | 92.7% |
| JUMP_BACKWARD | 960 | 7.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 262,020 | 83.4% |
| LOAD_CONST | 24,020 | 7.6% |
| LOAD_ATTR_SLOT | 15,864 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 11,980 | 3.8% |
| LOAD_DEREF | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 290,084 | 92.4% |
| LOAD_FAST | 24,000 | 7.6% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,602,234 | 64.5% |
| LOAD_ATTR_INSTANCE_VALUE | 872,789 | 15.6% |
| LOAD_ATTR_WITH_HINT | 335,900 | 6.0% |
| LOAD_GLOBAL_MODULE | 303,620 | 5.4% |
| LOAD_DEREF | 151,836 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,176,828 | 21.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 894,256 | 16.0% |
| PUSH_NULL | 669,133 | 12.0% |
| LOAD_CONST | 483,080 | 8.6% |
| CALL_PY_EXACT_ARGS | 321,157 | 5.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,337,173 | 20.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,673,166 | 10.5% |
| LOAD_CONST | 1,081,695 | 6.8% |
| POP_JUMP_IF_FALSE | 1,072,507 | 6.7% |
| STORE_ATTR_SLOT | 1,047,916 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,158,041 | 32.2% |
| COMPARE_OP_INT | 1,716,909 | 10.7% |
| STORE_FAST | 1,221,576 | 7.6% |
| LOAD_CONST | 1,081,695 | 6.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 634,620 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 401,428 | 19.2% |
| RESUME_CHECK | 207,468 | 9.9% |
| POP_JUMP_IF_FALSE | 171,488 | 8.2% |
| POP_JUMP_IF_TRUE | 144,340 | 6.9% |
| NOP | 134,855 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,920 | 24.2% |
| LOAD_ATTR_INSTANCE_VALUE | 368,544 | 17.6% |
| PUSH_NULL | 204,500 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 155,680 | 7.4% |
| LOAD_ATTR | 151,836 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,357,070 | 15.4% |
| POP_JUMP_IF_FALSE | 7,417,025 | 10.0% |
| STORE_FAST | 6,660,675 | 9.0% |
| LOAD_CONST | 5,158,041 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 5,153,841 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,800,231 | 29.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,983,062 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 4,941,367 | 6.7% |
| LOAD_ATTR | 3,602,234 | 4.9% |
| CALL_PY_EXACT_ARGS | 3,349,364 | 4.5% |


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
| LOAD_ATTR_METHOD_NO_DICT | 15,468 | 38.6% |
| POP_JUMP_IF_FALSE | 12,000 | 29.9% |
| STORE_FAST | 12,000 | 29.9% |
| POP_TOP | 320 | 0.8% |
| JUMP_FORWARD | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 15,368 | 38.3% |
| LOAD_ATTR | 12,000 | 29.9% |
| LOAD_CONST | 12,000 | 29.9% |
| POP_JUMP_IF_NOT_NONE | 440 | 1.1% |
| LOAD_FAST | 80 | 0.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,304,124 | 12.9% |
| LOAD_GLOBAL_MODULE | 1,093,580 | 10.8% |
| STORE_ATTR_INSTANCE_VALUE | 997,280 | 9.8% |
| STORE_FAST | 956,452 | 9.4% |
| POP_JUMP_IF_FALSE | 901,060 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,992,578 | 19.7% |
| STORE_ATTR_SLOT | 1,797,972 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,280,672 | 12.6% |
| LOAD_FAST | 876,497 | 8.6% |
| LOAD_FAST_LOAD_FAST | 734,568 | 7.2% |


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
| MAKE_CELL | 187,456 | 51.6% |
| CALL_PY_EXACT_ARGS | 115,029 | 31.6% |
| COPY_FREE_VARS | 24,100 | 6.6% |
| CACHE | 12,360 | 3.4% |
| CALL | 12,320 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 187,456 | 51.6% |
| RESUME_CHECK | 163,509 | 45.0% |
| RETURN_GENERATOR | 12,000 | 3.3% |
| RESUME | 520 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,373,733 | 45.3% |
| COMPARE_OP_INT | 2,676,065 | 19.0% |
| TO_BOOL_NONE | 1,214,550 | 8.6% |
| TO_BOOL | 1,056,435 | 7.5% |
| CONTAINS_OP | 605,540 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,417,025 | 52.7% |
| RETURN_CONST | 1,484,998 | 10.6% |
| LOAD_CONST | 1,072,507 | 7.6% |
| LOAD_GLOBAL_MODULE | 1,008,238 | 7.2% |
| LOAD_FAST_LOAD_FAST | 901,060 | 6.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,035,552 | 56.1% |
| LOAD_FAST | 2,040,150 | 37.7% |
| LOAD_ATTR | 132,960 | 2.5% |
| LOAD_DEREF | 132,080 | 2.4% |
| LOAD_ATTR_WITH_HINT | 34,968 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,470,362 | 82.6% |
| RETURN_CONST | 279,648 | 5.2% |
| LOAD_GLOBAL_MODULE | 276,580 | 5.1% |
| LOAD_FAST_LOAD_FAST | 144,440 | 2.7% |
| NOP | 132,300 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,047,284 | 62.8% |
| LOAD_ATTR_INSTANCE_VALUE | 444,360 | 26.6% |
| LOAD_ATTR | 108,980 | 6.5% |
| ENTER_EXECUTOR | 17,984 | 1.1% |
| LOAD_GLOBAL_MODULE | 12,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 587,756 | 35.2% |
| LOAD_FAST_LOAD_FAST | 435,448 | 26.1% |
| LOAD_GLOBAL_MODULE | 342,684 | 20.5% |
| LOAD_CONST | 132,200 | 7.9% |
| LOAD_DEREF | 84,280 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,222,463 | 54.9% |
| COMPARE_OP_INT | 708,520 | 17.5% |
| TO_BOOL_STR | 240,200 | 5.9% |
| TO_BOOL_INT | 232,333 | 5.7% |
| TO_BOOL_NONE | 203,877 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,900,844 | 47.0% |
| LOAD_GLOBAL_BUILTIN | 449,420 | 11.1% |
| NOP | 274,980 | 6.8% |
| LOAD_CONST | 233,694 | 5.8% |
| LOAD_FAST_LOAD_FAST | 228,460 | 5.6% |


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
| POP_TOP | 2,938,429 | 37.3% |
| POP_JUMP_IF_FALSE | 1,484,998 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 760,660 | 9.6% |
| STORE_ATTR_SLOT | 613,228 | 7.8% |
| STORE_FAST | 395,500 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,200,709 | 65.9% |
| INTERPRETER_EXIT | 1,712,772 | 21.7% |
| EXIT_INIT_CHECK | 324,640 | 4.1% |
| STORE_FAST | 176,312 | 2.2% |
| TO_BOOL_BOOL | 132,321 | 1.7% |


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
| MAKE_FUNCTION | 161,048 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 51,728 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 71,420 | 33.6% |
| SET_FUNCTION_ATTRIBUTE | 51,728 | 24.3% |
| CALL | 39,468 | 18.5% |
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
| LOAD_FAST | 181,000 | 62.6% |
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
| RETURN_VALUE | 2,136,152 | 19.9% |
| CALL | 1,947,402 | 18.2% |
| LOAD_CONST | 1,221,576 | 11.4% |
| CALL_BUILTIN_FAST | 814,460 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 708,021 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,660,675 | 62.2% |
| LOAD_FAST_LOAD_FAST | 956,452 | 8.9% |
| LOAD_CONST | 587,356 | 5.5% |
| LOAD_GLOBAL_BUILTIN | 483,374 | 4.5% |
| JUMP_FORWARD | 446,624 | 4.2% |


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
| FOR_ITER_TUPLE | 500 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 108,560 | 52.6% |
| STORE_ATTR_INSTANCE_VALUE | 83,920 | 40.7% |
| STORE_ATTR | 12,080 | 5.9% |
| TO_BOOL_LIST | 540 | 0.3% |
| TO_BOOL_STR | 500 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 631,980 | 71.4% |
| UNPACK_SEQUENCE_LIST | 119,960 | 13.5% |
| UNPACK_SEQUENCE_TUPLE | 72,300 | 8.2% |
| COPY | 24,200 | 2.7% |
| STORE_FAST_STORE_FAST | 24,160 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 451,660 | 51.0% |
| LOAD_GLOBAL_MODULE | 131,880 | 14.9% |
| STORE_FAST | 96,460 | 10.9% |
| LOAD_FAST_LOAD_FAST | 84,660 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 84,180 | 9.5% |


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
| BINARY_OP_ADD_INT | 567,369 | 41.0% |
| BINARY_OP_SUBTRACT_INT | 333,616 | 24.1% |
| LOAD_FAST | 192,300 | 13.9% |
| LOAD_ATTR | 57,576 | 4.2% |
| BUILD_LIST | 49,440 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 924,705 | 66.8% |
| COPY | 108,300 | 7.8% |
| STORE_FAST | 94,356 | 6.8% |
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
| YIELD_VALUE | 108,000 | 18.7% |
| BINARY_OP_ADD_UNICODE | 107,980 | 18.7% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 107,980 | 18.7% |
| ENTER_EXECUTOR | 95,400 | 16.5% |
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
| LOAD_ATTR_INSTANCE_VALUE | 15,564 | 12.8% |
| LOAD_ATTR | 11,960 | 9.8% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,160 | 58.4% |
| LOAD_GLOBAL_MODULE | 35,080 | 28.8% |
| STORE_FAST | 15,584 | 12.8% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 676,029 | 62.4% |
| LOAD_FAST_LOAD_FAST | 263,840 | 24.3% |
| CALL_LEN | 83,960 | 7.7% |
| LOAD_CONST | 59,760 | 5.5% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 567,369 | 52.3% |
| BINARY_SLICE | 311,940 | 28.8% |
| RETURN_VALUE | 71,980 | 6.6% |
| CALL_PY_EXACT_ARGS | 71,960 | 6.6% |
| STORE_FAST | 60,280 | 5.6% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 119,920 | 52.5% |
| RETURN_VALUE | 107,960 | 47.2% |
| LOAD_FAST_LOAD_FAST | 300 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 160 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 107,980 | 47.2% |
| LOAD_GLOBAL_MODULE | 107,960 | 47.2% |
| STORE_FAST | 12,220 | 5.3% |
| LOAD_FAST | 240 | 0.1% |
| RETURN_VALUE | 80 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,960 | 93.5% |
| LOAD_CONST | 798 | 6.2% |
| BINARY_OP | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,980 | 93.6% |
| CALL_BUILTIN_O | 798 | 6.2% |
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
| RETURN_VALUE | 59,958 | 65.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,960 | 13.0% |
| LOAD_ATTR_WITH_HINT | 11,960 | 13.0% |
| CALL | 7,692 | 8.4% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 59,180 | 64.5% |
| RETURN_VALUE | 11,980 | 13.1% |
| LOAD_FAST | 11,980 | 13.1% |
| STORE_FAST | 8,530 | 9.3% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 563,920 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 95,920 | 11.4% |
| BINARY_OP_SUBTRACT_INT | 83,960 | 10.0% |
| CALL_LEN | 60,080 | 7.2% |
| LOAD_CONST | 33,696 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 333,616 | 39.8% |
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
| CALL | 420,140 | 47.7% |
| LOAD_FAST | 350,595 | 39.8% |
| BUILD_TUPLE | 48,080 | 5.5% |
| RETURN_VALUE | 23,980 | 2.7% |
| LOAD_FAST_LOAD_FAST | 12,240 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 432,040 | 49.1% |
| PUSH_EXC_INFO | 348,440 | 39.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 38,215 | 4.3% |
| STORE_FAST | 24,340 | 2.8% |
| LOAD_FAST_LOAD_FAST | 12,200 | 1.4% |


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
| LOAD_CONST | 51,698 | 67.5% |
| BINARY_SUBSCR | 12,300 | 16.1% |
| BINARY_OP_SUBTRACT_INT | 11,960 | 15.6% |
| LOAD_FAST | 580 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,240 | 31.7% |
| LOAD_ATTR_SLOT | 21,152 | 27.7% |
| STORE_FAST | 15,411 | 20.2% |
| LOAD_CONST | 11,980 | 15.7% |
| TO_BOOL_BOOL | 2,535 | 3.3% |


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
| LOAD_ATTR_INSTANCE_VALUE | 84,040 | 25.9% |
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
| LOAD_FAST | 85,190 | 29.0% |
| LOAD_FAST_LOAD_FAST | 48,446 | 16.5% |
| BINARY_SLICE | 23,960 | 8.2% |
| CALL_BUILTIN_CLASS | 23,960 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 156,856 | 53.4% |
| POP_TOP | 108,260 | 36.8% |
| COPY_FREE_VARS | 26,098 | 8.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,060 | 0.7% |
| CALL_PY_EXACT_ARGS | 471 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 71,960 | 29.1% |
| LOAD_FAST | 39,824 | 16.1% |
| CALL | 36,480 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 36,160 | 14.6% |
| LOAD_GLOBAL_MODULE | 14,215 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,500 | 39.1% |
| LOAD_FAST | 36,200 | 14.7% |
| RETURN_VALUE | 35,980 | 14.6% |
| GET_ITER | 29,939 | 12.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,960 | 9.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 837,640 | 50.6% |
| LOAD_FAST_LOAD_FAST | 455,120 | 27.5% |
| LOAD_CONST | 289,540 | 17.5% |
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
| LOAD_ATTR | 15,008 | 53.3% |
| LOAD_FAST | 12,620 | 44.8% |
| LOAD_CONST | 300 | 1.1% |
| CALL_STR_1 | 80 | 0.3% |
| CALL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 15,048 | 53.5% |
| STORE_FAST | 12,380 | 44.0% |
| RETURN_VALUE | 580 | 2.1% |
| BEFORE_WITH | 80 | 0.3% |
| PUSH_EXC_INFO | 60 | 0.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,098 | 86.6% |
| LOAD_ATTR_INSTANCE_VALUE | 5,408 | 9.5% |
| BINARY_OP_MULTIPLY_FLOAT | 798 | 1.4% |
| BUILD_TUPLE | 360 | 0.6% |
| CALL | 220 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 23,920 | 42.2% |
| STORE_FAST | 17,488 | 30.9% |
| BINARY_SUBSCR_DICT | 11,960 | 21.1% |
| POP_TOP | 1,618 | 2.9% |
| LOAD_CONST | 818 | 1.4% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,131,049 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 435,952 | 20.9% |
| LOAD_ATTR_MODULE | 298,800 | 14.3% |
| BUILD_TUPLE | 157,200 | 7.5% |
| LOAD_ATTR | 59,960 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,878,821 | 90.1% |
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
| LOAD_FAST | 649,740 | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE | 327,804 | 32.7% |
| LOAD_GLOBAL_MODULE | 12,080 | 1.2% |
| BINARY_SUBSCR | 12,060 | 1.2% |
| CALL | 640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 303,340 | 30.3% |
| LOAD_FAST | 226,320 | 22.6% |
| LOAD_CONST | 97,380 | 9.7% |
| BINARY_OP_ADD_INT | 83,960 | 8.4% |
| BINARY_OP_SUBTRACT_INT | 60,080 | 6.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,093 | 54.1% |
| BUILD_TUPLE | 66,469 | 25.9% |
| ENTER_EXECUTOR | 26,866 | 10.5% |
| RETURN_VALUE | 24,040 | 9.4% |
| CALL | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120,260 | 46.8% |
| ENTER_EXECUTOR | 98,746 | 38.4% |
| LOAD_FAST | 24,120 | 9.4% |
| NOP | 12,022 | 4.7% |
| JUMP_BACKWARD | 1,840 | 0.7% |


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
| LOAD_FAST | 21,313 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 622,560 | 65.0% |
| CALL_PY_EXACT_ARGS | 108,040 | 11.3% |
| STORE_FAST | 93,733 | 9.8% |
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
| LOAD_FAST_LOAD_FAST | 15,564 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 268,164 | 37.6% |
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
| LOAD_ATTR | 894,256 | 59.1% |
| LOAD_ATTR_METHOD_NO_DICT | 565,963 | 37.4% |
| LOAD_FAST | 24,040 | 1.6% |
| ENTER_EXECUTOR | 12,848 | 0.8% |
| LOAD_ATTR_METHOD_LAZY_DICT | 11,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 927,428 | 61.3% |
| POP_TOP | 152,252 | 10.1% |
| GET_ITER | 144,140 | 9.5% |
| LOAD_FAST | 72,200 | 4.8% |
| STORE_FAST | 67,192 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 555,154 | 56.6% |
| BUILD_TUPLE | 191,840 | 19.6% |
| LOAD_ATTR_INSTANCE_VALUE | 84,120 | 8.6% |
| LOAD_CONST | 48,400 | 4.9% |
| CALL | 36,880 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 807,914 | 82.3% |
| STORE_FAST | 99,421 | 10.1% |
| LOAD_CONST | 24,300 | 2.5% |
| UNPACK_SEQUENCE_TUPLE | 24,080 | 2.5% |
| PUSH_EXC_INFO | 12,067 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,460,232 | 41.0% |
| LOAD_FAST | 3,349,364 | 30.8% |
| LOAD_FAST_LOAD_FAST | 661,169 | 6.1% |
| LOAD_CONST | 576,140 | 5.3% |
| LOAD_ATTR | 321,157 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,199,773 | 93.8% |
| COPY_FREE_VARS | 288,557 | 2.7% |
| RETURN_GENERATOR | 264,140 | 2.4% |
| MAKE_CELL | 115,029 | 1.1% |
| TO_BOOL_BOOL | 4,169 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 143,680 | 25.3% |
| LOAD_FAST | 131,980 | 23.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 124,109 | 21.8% |
| PUSH_NULL | 72,040 | 12.7% |
| LOAD_ATTR | 35,920 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 556,669 | 97.9% |
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
| LOAD_ATTR_SLOT | 332,101 | 93.3% |
| LOAD_FAST | 15,231 | 4.3% |
| LOAD_GLOBAL_MODULE | 8,631 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 332,121 | 93.3% |
| POP_JUMP_IF_FALSE | 23,982 | 6.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,716,909 | 50.4% |
| LOAD_ATTR_INSTANCE_VALUE | 953,852 | 28.0% |
| LOAD_ATTR_CLASS | 383,960 | 11.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 119,920 | 3.5% |
| COPY | 108,180 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,676,065 | 78.5% |
| POP_JUMP_IF_TRUE | 708,520 | 20.8% |
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
| GET_ITER | 320,547 | 55.9% |
| ENTER_EXECUTOR | 232,449 | 40.6% |
| SWAP | 12,460 | 2.2% |
| JUMP_BACKWARD | 6,459 | 1.1% |
| FOR_ITER | 780 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 195,824 | 34.2% |
| STORE_FAST | 148,299 | 25.9% |
| ENTER_EXECUTOR | 107,660 | 18.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,809 | 5.4% |
| RETURN_CONST | 27,885 | 4.9% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 29,939 | 50.7% |
| ENTER_EXECUTOR | 27,644 | 46.9% |
| JUMP_BACKWARD | 1,260 | 2.1% |
| FOR_ITER | 100 | 0.2% |
| SWAP | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,859 | 52.3% |
| LOAD_CONST | 15,604 | 26.4% |
| RETURN_CONST | 12,000 | 20.3% |
| STORE_FAST_LOAD_FAST | 380 | 0.6% |
| LOAD_FAST | 80 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 73,020 | 72.6% |
| ENTER_EXECUTOR | 13,840 | 13.8% |
| SWAP | 12,460 | 12.4% |
| LOAD_FAST | 700 | 0.7% |
| JUMP_BACKWARD | 420 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,220 | 59.9% |
| STORE_FAST | 13,740 | 13.7% |
| SWAP | 12,480 | 12.4% |
| LOAD_CONST | 12,000 | 11.9% |
| RETURN_CONST | 700 | 0.7% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 454,632 | 62.1% |
| LOAD_GLOBAL_MODULE | 228,420 | 31.2% |
| LOAD_FAST | 48,600 | 6.6% |
| LOAD_ATTR | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 383,960 | 52.4% |
| LOAD_FAST | 143,272 | 19.6% |
| BINARY_OP | 96,080 | 13.1% |
| CALL | 48,060 | 6.6% |
| RETURN_VALUE | 24,200 | 3.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,800,231 | 86.6% |
| LOAD_FAST_LOAD_FAST | 1,280,672 | 5.1% |
| COPY | 924,705 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 791,180 | 3.1% |
| LOAD_DEREF | 368,544 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,182,123 | 16.6% |
| POP_JUMP_IF_NONE | 3,035,552 | 12.1% |
| RETURN_VALUE | 2,690,080 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 2,255,639 | 9.0% |
| TO_BOOL_BOOL | 2,249,438 | 8.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 2,255,639 | 52.3% |
| LOAD_FAST | 1,158,817 | 26.9% |
| BINARY_SLICE | 251,960 | 5.8% |
| LOAD_CONST | 132,180 | 3.1% |
| STORE_FAST_LOAD_FAST | 108,560 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,869,000 | 43.3% |
| LOAD_CONST | 813,355 | 18.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 565,963 | 13.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 227,960 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 204,040 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,983,062 | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,742,517 | 19.9% |
| LOAD_ATTR_SLOT | 589,008 | 6.7% |
| LOAD_DEREF | 123,048 | 1.4% |
| LOAD_FAST_LOAD_FAST | 107,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,460,232 | 50.9% |
| LOAD_FAST | 2,766,718 | 31.6% |
| LOAD_FAST_LOAD_FAST | 675,208 | 7.7% |
| LOAD_CONST | 431,980 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 143,180 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,047,601 | 99.5% |
| LOAD_ATTR_MODULE | 11,960 | 0.4% |
| LOAD_ATTR | 2,940 | 0.1% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,681,742 | 54.9% |
| LOAD_ATTR_CLASS | 454,632 | 14.8% |
| CALL_ISINSTANCE | 298,800 | 9.8% |
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
| LOAD_ATTR_INSTANCE_VALUE | 204,040 | 54.8% |
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
| LOAD_FAST | 2,587,875 | 94.2% |
| BINARY_SUBSCR_TUPLE_INT | 120,040 | 4.4% |
| BINARY_SUBSCR_LIST_INT | 21,152 | 0.8% |
| LOAD_DEREF | 11,960 | 0.4% |
| LOAD_ATTR_SLOT | 5,537 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 856,056 | 31.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 589,008 | 21.4% |
| LOAD_FAST | 348,770 | 12.7% |
| COMPARE_OP_FLOAT | 332,101 | 12.1% |
| TO_BOOL_BOOL | 291,420 | 10.6% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,701 | 99.9% |
| LOAD_ATTR | 660 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 303 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 335,900 | 43.9% |
| LOAD_CONST | 95,960 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,768 | 10.8% |
| LOAD_ATTR_METHOD_NO_DICT | 59,960 | 7.8% |
| RETURN_VALUE | 35,980 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,791,520 | 40.1% |
| LOAD_FAST | 796,272 | 11.4% |
| POP_JUMP_IF_FALSE | 640,806 | 9.2% |
| STORE_FAST | 483,374 | 6.9% |
| POP_JUMP_IF_TRUE | 449,420 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,153,841 | 74.0% |
| CALL_ISINSTANCE | 435,952 | 6.3% |
| LOAD_DEREF | 401,428 | 5.8% |
| CHECK_EXC_MATCH | 391,341 | 5.6% |
| BUILD_TUPLE | 156,660 | 2.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,177,107 | 20.6% |
| RESUME_CHECK | 1,968,070 | 18.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,043,920 | 9.9% |
| POP_JUMP_IF_FALSE | 1,008,238 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 785,548 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,047,601 | 28.9% |
| LOAD_FAST | 2,138,434 | 20.3% |
| CALL_ISINSTANCE | 1,131,049 | 10.7% |
| LOAD_FAST_LOAD_FAST | 1,093,580 | 10.4% |
| CALL | 589,856 | 5.6% |


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
| CALL_PY_EXACT_ARGS | 10,199,773 | 52.1% |
| CACHE | 5,376,331 | 27.5% |
| COPY_FREE_VARS | 732,511 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 556,669 | 2.8% |
| BINARY_SUBSCR_GETITEM | 492,660 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,357,070 | 58.0% |
| LOAD_GLOBAL_BUILTIN | 2,791,520 | 14.3% |
| LOAD_GLOBAL_MODULE | 1,968,070 | 10.1% |
| NOP | 1,203,786 | 6.2% |
| LOAD_CONST | 652,088 | 3.3% |


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
| LOAD_FAST | 4,941,367 | 60.9% |
| LOAD_FAST_LOAD_FAST | 1,992,578 | 24.5% |
| SWAP | 924,705 | 11.4% |
| LOAD_DEREF | 155,680 | 1.9% |
| STORE_FAST_LOAD_FAST | 83,920 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,812,461 | 34.6% |
| LOAD_CONST | 1,673,166 | 20.6% |
| LOAD_FAST_LOAD_FAST | 997,280 | 12.3% |
| LOAD_GLOBAL_MODULE | 785,548 | 9.7% |
| RETURN_CONST | 760,660 | 9.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,797,972 | 49.9% |
| LOAD_FAST | 1,792,159 | 49.7% |
| STORE_ATTR_SLOT | 13,052 | 0.4% |
| STORE_ATTR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,304,124 | 36.2% |
| LOAD_CONST | 1,047,916 | 29.1% |
| LOAD_FAST | 618,636 | 17.2% |
| RETURN_CONST | 613,228 | 17.0% |
| STORE_ATTR_SLOT | 13,052 | 0.4% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,887 | 79.4% |
| LOAD_FAST_LOAD_FAST | 11,960 | 20.3% |
| STORE_ATTR_INSTANCE_VALUE | 101 | 0.2% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,920 | 81.2% |
| RETURN_CONST | 11,008 | 18.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 2,249,438 | 25.8% |
| RETURN_VALUE | 1,887,288 | 21.6% |
| CALL_ISINSTANCE | 1,878,821 | 21.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 927,428 | 10.6% |
| LOAD_FAST | 402,084 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,373,733 | 73.0% |
| POP_JUMP_IF_TRUE | 2,222,463 | 25.5% |
| EXTENDED_ARG | 119,920 | 1.4% |
| UNARY_NOT | 11,980 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 315,164 | 41.4% |
| BINARY_OP | 270,638 | 35.5% |
| COPY | 163,147 | 21.4% |
| LOAD_ATTR | 11,960 | 1.6% |
| TO_BOOL | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 529,390 | 69.5% |
| POP_JUMP_IF_TRUE | 232,333 | 30.5% |
| TO_BOOL_NONE | 106 | 0.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 145,256 | 99.0% |
| LOAD_FAST | 720 | 0.5% |
| STORE_FAST_LOAD_FAST | 540 | 0.4% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 145,736 | 99.3% |
| POP_JUMP_IF_TRUE | 940 | 0.6% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 856,056 | 60.3% |
| COPY | 190,751 | 13.4% |
| LOAD_FAST | 189,622 | 13.4% |
| LOAD_ATTR | 83,800 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 72,040 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,214,550 | 85.6% |
| POP_JUMP_IF_TRUE | 203,877 | 14.4% |
| TO_BOOL | 188 | 0.0% |
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
| BINARY_SUBSCR | 180,200 | 28.0% |
| RETURN_VALUE | 156,480 | 24.3% |
| YIELD_VALUE | 107,960 | 16.8% |
| STORE_FAST | 57,396 | 8.9% |
| BINARY_SUBSCR_DICT | 38,215 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 631,980 | 98.1% |
| LOAD_FAST | 12,040 | 1.9% |
| STORE_FAST | 340 | 0.1% |
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
|     deferred | 1,086,443 | 31.2% |
|          hit | 2,388,977 | 68.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 960 | 10.8% |
| Failure | 7,902 | 89.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,485 | 44.1% |
| add other | 1,420 | 18.0% |
| or | 1,240 | 15.7% |
| remainder | 880 | 11.1% |
| add different types | 480 | 6.1% |
| floor divide | 180 | 2.3% |
| true divide other | 140 | 1.8% |
| multiply different types | 77 | 1.0% |


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
|     deferred | 339,000 | 15.9% |
|          hit | 1,787,833 | 83.9% |
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
|     deferred | 6,199,574 | 22.0% |
|          hit | 21,579,520 | 76.5% |
|         miss | 363,503 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,431 | 41.4% |
| Failure | 31,779 | 58.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 6,344 | 20.0% |
| class no vectorcall | 5,460 | 17.2% |
| meth descr method fastcall keywords | 3,860 | 12.1% |
| cfunc noargs | 3,461 | 10.9% |
| meth descr varargs | 3,029 | 9.5% |
| cfunc varargs keywords | 2,260 | 7.1% |
| other | 1,725 | 5.4% |
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
|     deferred | 180,828 | 4.3% |
|          hit | 4,041,838 | 95.6% |
|         miss | 978 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,968 | 50.6% |
| Failure | 1,922 | 49.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 480 | 25.0% |
| bytes | 360 | 18.7% |
| other | 340 | 17.7% |
| float long | 302 | 15.7% |
| tuple | 180 | 9.4% |
| big int | 160 | 8.3% |
| baseobject | 60 | 3.1% |
| bool | 40 | 2.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 198,682 | 16.4% |
|          hit | 1,008,578 | 83.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 31.9% |
| Failure | 2,175 | 68.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 1,300 | 59.8% |
| set | 220 | 10.1% |
| dict keys | 200 | 9.2% |
| other | 180 | 8.3% |
| ascii string | 120 | 5.5% |
| bytes | 115 | 5.3% |
| enumerate | 40 | 1.8% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,513,007 | 10.7% |
|          hit | 45,616,920 | 88.3% |
|         miss | 455,043 | 0.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,396 | 49.9% |
| Failure | 37,610 | 50.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 8,180 | 21.7% |
| method | 8,074 | 21.5% |
| not managed dict | 7,096 | 18.9% |
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
|          hit | 17,510,895 | 99.8% |
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
|     deferred | 263,687 | 2.2% |
|          hit | 11,071,964 | 91.7% |
|         miss | 708,597 | 5.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 21,313 | 83.8% |
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
|     deferred | 217,000 | 27.7% |
|          hit | 565,320 | 72.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 17.9% |
| Failure | 1,740 | 82.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 1,420 | 81.6% |
| dict subclass no override | 320 | 18.4% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,252,660 | 9.9% |
|          hit | 11,358,973 | 89.7% |
|         miss | 34,323 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,886 | 56.5% |
| Failure | 6,062 | 43.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 1,880 | 31.0% |
| bytes | 1,116 | 18.4% |
| float | 960 | 15.8% |
| dict | 620 | 10.2% |
| mapping | 526 | 8.7% |
| bytearray | 420 | 6.9% |
| tuple | 360 | 5.9% |
| set | 180 | 3.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,920 | 1.5% |
|          hit | 848,620 | 98.4% |

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
| Basic | 176,205,191 | 49.3% |
| Not specialized | 41,566,929 | 11.6% |
| Specialized hits | 137,764,839 | 38.6% |
| Specialized misses | 1,570,249 | 0.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,199,574 | 39.7% |
| LOAD_ATTR | 5,513,007 | 35.3% |
| TO_BOOL | 1,252,660 | 8.0% |
| BINARY_OP | 1,086,443 | 7.0% |
| BINARY_SUBSCR | 339,000 | 2.2% |
| SEND | 336,200 | 2.2% |
| STORE_ATTR | 263,687 | 1.7% |
| STORE_SUBSCR | 217,000 | 1.4% |
| FOR_ITER | 198,682 | 1.3% |
| COMPARE_OP | 180,828 | 1.2% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 696,964 | 44.4% |
| LOAD_ATTR_SLOT | 296,102 | 18.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 136,778 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 125,039 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,527 | 5.3% |
| CALL_PY_EXACT_ARGS | 64,606 | 4.1% |
| CALL_METHOD_DESCRIPTOR_O | 36,840 | 2.3% |
| LOAD_ATTR_METHOD_NO_DICT | 28,295 | 1.8% |
| TO_BOOL_NONE | 22,022 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 19,449 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 5,738,027 | 29.0% |
| Calls to Python functions inlined | 14,071,502 | 71.0% |
| Calls via PyEval_EvalFrame (total) | 5,738,027 | 29.0% |
| Calls via PyEval_EvalFrame (vector) | 5,387,447 | 27.2% |
| Calls via PyEval_EvalFrame (generator) | 350,580 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 5,387,147 | 27.2% |
| Calls via PyEval_EvalFrame (build class) | 220 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 1,094,661 | 5.5% |
| Calls via PyEval_EvalFrame (function ex) | 132,520 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 206,300 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 915,608 | 4.6% |
| Frame objects created | 824,743 | 4.2% |
| Frames pushed | 13,466,552 | 68.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,857,908 | 40.1% |
| Frees to freelist | 11,911,998 |  |
| Allocations | 17,746,469 | 59.9% |
| Allocations to 512 bytes | 17,422,428 | 58.9% |
| Allocations to 4 kbytes | 90,946 | 0.3% |
| Allocations over 4 kbytes | 233,095 | 0.8% |
| Frees | 18,010,005 |  |
| New values | 158,420 |  |
| Interpreter increfs | 187,255,640 | 77.2% |
| Interpreter decrefs | 202,665,405 | 75.0% |
| Increfs | 55,253,444 | 22.8% |
| Decrefs | 67,659,889 | 25.0% |
| Materialize dict (on request) | 200 | 0.1% |
| Materialize dict (new key) | 24,000 | 15.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 140 | 0.1% |
| Method cache hits | 10,298,843 |  |
| Method cache misses | 419,945 |  |
| Method cache collisions | 449,053 |  |
| Method cache dunder hits | 6,853,609 |  |
| Method cache dunder misses | 33,647 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 1,226 | 1,920 | 13,039,186 |
| 1 | 119 | 0 | 4,417,662 |
| 2 | 2 | 66 | 624,986 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,120 |  |
| Traces created | 760 | 67.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 18 | 1.6% |
| Trace too long | 0 | 0.0% |
| Trace too short | 360 | 32.1% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 1,350,511 |  |
| Uops executed | 52,862,728 | 39.14 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 5.3% |
| <= 32 | 300 | 39.5% |
| <= 64 | 200 | 26.3% |
| <= 128 | 138 | 18.2% |
| <= 256 | 80 | 10.5% |
| <= 512 | 2 | 0.3% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 100 | 13.2% |
| <= 16 | 280 | 36.8% |
| <= 32 | 140 | 18.4% |
| <= 64 | 100 | 13.2% |
| <= 128 | 138 | 18.2% |
| <= 256 | 2 | 0.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 40 | 0.0% |
| <= 2 | 218,171 | 16.2% |
| <= 4 | 27,724 | 2.1% |
| <= 8 | 32,012 | 2.4% |
| <= 16 | 271,803 | 20.1% |
| <= 32 | 151,730 | 11.2% |
| <= 64 | 99,085 | 7.3% |
| <= 128 | 543,450 | 40.2% |
| <= 256 | 1,863 | 0.1% |
| <= 512 | 2,374 | 0.2% |
| <= 1,024 | 1,926 | 0.1% |
| <= 2,048 | 300 | 0.0% |
| <= 4,096 | 20 | 0.0% |
| <= 8,192 | 13 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 6,459,512 | 12.2% | 12.2% |  |
| _CHECK_VALIDITY | 6,070,735 | 11.5% | 23.7% |  |
| LOAD_FAST | 5,701,914 | 10.8% | 34.5% |  |
| _GUARD_TYPE_VERSION | 4,693,769 | 8.9% | 43.4% |  |
| STORE_FAST | 2,293,023 | 4.3% | 47.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,606,604 | 3.0% | 50.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,606,604 | 3.0% | 53.8% |  |
| _LOAD_ATTR_SLOT | 1,572,559 | 3.0% | 56.8% |  |
| _GUARD_IS_FALSE_POP | 1,310,631 | 2.5% | 59.2% | 4.1% |
| _LOAD_ATTR_METHOD_NO_DICT | 1,141,213 | 2.2% | 61.4% |  |
| TO_BOOL_BOOL | 1,124,107 | 2.1% | 63.5% |  |
| LOAD_CONST | 1,014,050 | 1.9% | 65.4% |  |
| _GUARD_GLOBALS_VERSION | 907,427 | 1.7% | 67.2% | 0.1% |
| _EXIT_TRACE | 886,372 | 1.7% | 68.8% |  |
| _ITER_CHECK_LIST | 732,011 | 1.4% | 70.2% | 0.0% |
| _GUARD_NOT_EXHAUSTED_LIST | 731,971 | 1.4% | 71.6% | 31.8% |
| _CHECK_PEP_523 | 669,903 | 1.3% | 72.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 669,903 | 1.3% | 74.1% |  |
| _CHECK_STACK_SPACE | 669,903 | 1.3% | 75.4% |  |
| _INIT_CALL_PY_EXACT_ARGS | 669,903 | 1.3% | 76.7% |  |
| _PUSH_FRAME | 669,903 | 1.3% | 77.9% |  |
| _SAVE_RETURN_OFFSET | 669,903 | 1.3% | 79.2% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 573,804 | 1.1% | 80.3% | 2.2% |
| RESUME_CHECK | 567,090 | 1.1% | 81.4% |  |
| _LOAD_ATTR | 550,507 | 1.0% | 82.4% |  |
| _ITER_NEXT_LIST | 499,382 | 0.9% | 83.4% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 462,836 | 0.9% | 84.2% | 6.0% |
| _ITER_CHECK_RANGE | 462,836 | 0.9% | 85.1% |  |
| _LOAD_GLOBAL_MODULE | 461,151 | 0.9% | 86.0% |  |
| _GUARD_BUILTINS_VERSION | 444,936 | 0.8% | 86.8% |  |
| _LOAD_GLOBAL_BUILTINS | 444,936 | 0.8% | 87.7% |  |
| _ITER_NEXT_RANGE | 435,192 | 0.8% | 88.5% |  |
| _GUARD_IS_TRUE_POP | 415,204 | 0.8% | 89.3% | 10.0% |
| PUSH_NULL | 386,989 | 0.7% | 90.0% |  |
| BUILD_LIST | 364,012 | 0.7% | 90.7% |  |
| CALL_INTRINSIC_1 | 364,012 | 0.7% | 91.4% |  |
| LIST_EXTEND | 364,012 | 0.7% | 92.1% |  |
| _JUMP_TO_TOP | 266,432 | 0.5% | 92.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 261,559 | 0.5% | 93.1% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 245,471 | 0.5% | 93.5% |  |
| _GUARD_KEYS_VERSION | 245,471 | 0.5% | 94.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 233,791 | 0.4% | 94.4% |  |
| TO_BOOL_INT | 186,796 | 0.4% | 94.8% |  |
| _FOR_ITER_TIER_TWO | 155,400 | 0.3% | 95.1% | 24.7% |
| CALL_ISINSTANCE | 144,388 | 0.3% | 95.4% |  |
| BUILD_TUPLE | 141,579 | 0.3% | 95.6% |  |
| POP_TOP | 135,699 | 0.3% | 95.9% |  |
| COMPARE_OP_INT | 131,560 | 0.2% | 96.1% |  |
| _TO_BOOL | 115,035 | 0.2% | 96.3% |  |
| _BINARY_OP | 114,786 | 0.2% | 96.6% |  |
| CONTAINS_OP | 108,380 | 0.2% | 96.8% |  |
| CALL_LEN | 107,620 | 0.2% | 97.0% |  |
| _GUARD_IS_NOT_NONE_POP | 98,811 | 0.2% | 97.2% | 10.7% |
| COPY | 89,079 | 0.2% | 97.3% |  |
| GET_ITER | 83,800 | 0.2% | 97.5% |  |
| _BINARY_SUBSCR | 83,680 | 0.2% | 97.6% |  |
| _GUARD_DORV_VALUES | 80,777 | 0.2% | 97.8% |  |
| _STORE_ATTR_INSTANCE_VALUE | 80,777 | 0.2% | 98.0% |  |
| SWAP | 77,749 | 0.1% | 98.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 76,738 | 0.1% | 98.2% |  |
| _CHECK_ATTR_MODULE | 75,123 | 0.1% | 98.4% |  |
| _LOAD_ATTR_MODULE | 75,123 | 0.1% | 98.5% |  |
| _GUARD_IS_NONE_POP | 65,332 | 0.1% | 98.7% | 11.3% |
| _GUARD_NOT_EXHAUSTED_TUPLE | 63,700 | 0.1% | 98.8% | 21.7% |
| _ITER_CHECK_TUPLE | 63,700 | 0.1% | 98.9% |  |
| LOAD_FAST_CHECK | 56,592 | 0.1% | 99.0% |  |
| _ITER_NEXT_TUPLE | 49,860 | 0.1% | 99.1% |  |
| CALL_BUILTIN_FAST | 48,540 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 47,740 | 0.1% | 99.3% | 25.0% |
| _STORE_ATTR_SLOT | 47,145 | 0.1% | 99.4% |  |
| MAKE_CELL | 44,599 | 0.1% | 99.4% |  |
| LOAD_DEREF | 35,000 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 34,324 | 0.1% | 99.6% |  |
| _POP_FRAME | 33,274 | 0.1% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 32,015 | 0.1% | 99.7% |  |
| BINARY_SUBSCR_DICT | 23,780 | 0.0% | 99.7% |  |
| _STORE_SUBSCR | 23,780 | 0.0% | 99.8% |  |
| _GUARD_BOTH_INT | 23,037 | 0.0% | 99.8% |  |
| TO_BOOL_LIST | 22,837 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 22,737 | 0.0% | 99.9% |  |
| _BINARY_OP_SUBTRACT_INT | 22,737 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,680 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 1,168 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 1,168 | 0.0% | 100.0% |  |
| LIST_APPEND | 660 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 660 | 0.0% | 100.0% |  |
| IS_OP | 500 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 300 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 240 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 220 | 0.0% | 100.0% | 27.3% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 220 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 220 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 160 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 40 | 0.0% | 100.0% |  |
| STORE_DEREF | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 360 |
| CALL | 162 |
| CALL_LIST_APPEND | 100 |
| YIELD_VALUE | 60 |
| CALL_FUNCTION_EX | 20 |
| CALL_KW | 20 |
| CALL_ALLOC_AND_ENTER_INIT | 20 |
| LOAD_ATTR_PROPERTY | 20 |


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
Stats gathered on: 2023-11-19
