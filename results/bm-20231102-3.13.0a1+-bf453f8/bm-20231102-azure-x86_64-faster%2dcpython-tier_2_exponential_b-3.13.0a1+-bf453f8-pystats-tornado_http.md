
# Pystats results

- benchmark: tornado_http
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 75,714,807 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 25,508,100 | 7.0% | 27.7% | 0.1% |
| RESUME_CHECK | 19,643,521 | 5.4% | 33.0% | 0.0% |
| LOAD_CONST | 16,340,131 | 4.5% | 37.5% |  |
| POP_JUMP_IF_FALSE | 14,225,270 | 3.9% | 41.4% |  |
| RETURN_VALUE | 11,571,322 | 3.2% | 44.5% |  |
| STORE_FAST | 11,077,841 | 3.0% | 47.6% |  |
| CALL_PY_EXACT_ARGS | 11,025,407 | 3.0% | 50.6% | 0.6% |
| LOAD_GLOBAL_MODULE | 10,779,640 | 2.9% | 53.5% | 0.0% |
| LOAD_FAST_LOAD_FAST | 10,361,242 | 2.8% | 56.3% |  |
| POP_TOP | 10,226,017 | 2.8% | 59.1% |  |
| TO_BOOL_BOOL | 8,824,827 | 2.4% | 61.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,823,014 | 2.4% | 64.0% | 0.9% |
| STORE_ATTR_INSTANCE_VALUE | 8,174,608 | 2.2% | 66.2% | 0.1% |
| RETURN_CONST | 7,903,975 | 2.2% | 68.4% |  |
| LOAD_GLOBAL_BUILTIN | 6,970,342 | 1.9% | 70.3% | 0.1% |
| CALL | 6,250,979 | 1.7% | 72.0% |  |
| LOAD_ATTR | 6,150,470 | 1.7% | 73.6% |  |
| INTERPRETER_EXIT | 5,724,422 | 1.6% | 75.2% |  |
| POP_JUMP_IF_NONE | 5,488,684 | 1.5% | 76.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,491,438 | 1.2% | 77.9% | 0.6% |
| POP_JUMP_IF_TRUE | 4,183,923 | 1.1% | 79.1% |  |
| STORE_ATTR_SLOT | 3,610,064 | 1.0% | 80.1% | 19.1% |
| PUSH_NULL | 3,580,987 | 1.0% | 81.0% |  |
| LOAD_ATTR_SLOT | 3,501,899 | 1.0% | 82.0% | 8.4% |
| COMPARE_OP_INT | 3,492,557 | 1.0% | 83.0% | 0.0% |
| NOP | 3,147,954 | 0.9% | 83.8% |  |
| LOAD_ATTR_MODULE | 3,112,378 | 0.9% | 84.7% | 0.0% |
| COPY | 2,440,516 | 0.7% | 85.3% |  |
| LOAD_DEREF | 2,092,532 | 0.6% | 85.9% |  |
| CALL_ISINSTANCE | 2,085,565 | 0.6% | 86.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,709,551 | 0.5% | 86.9% | 7.3% |
| CALL_BUILTIN_FAST | 1,654,780 | 0.5% | 87.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,650,561 | 0.5% | 87.8% |  |
| TO_BOOL_NONE | 1,418,457 | 0.4% | 88.2% | 1.6% |
| SWAP | 1,413,780 | 0.4% | 88.6% |  |
| BUILD_TUPLE | 1,399,480 | 0.4% | 89.0% |  |
| TO_BOOL | 1,381,165 | 0.4% | 89.4% |  |
| ENTER_EXECUTOR | 1,255,639 | 0.3% | 89.7% |  |
| BUILD_LIST | 1,250,659 | 0.3% | 90.1% |  |
| BINARY_OP | 1,208,786 | 0.3% | 90.4% |  |
| BINARY_OP_ADD_INT | 1,083,882 | 0.3% | 90.7% |  |
| STORE_FAST_STORE_FAST | 1,082,814 | 0.3% | 91.0% |  |
| CALL_FUNCTION_EX | 1,080,351 | 0.3% | 91.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,057,679 | 0.3% | 91.6% | 3.5% |
| CALL_LEN | 1,002,500 | 0.3% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 957,296 | 0.3% | 92.1% |  |
| BINARY_SUBSCR_DICT | 904,400 | 0.2% | 92.4% |  |
| TO_BOOL_INT | 863,961 | 0.2% | 92.6% | 0.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 841,714 | 0.2% | 92.8% |  |
| BINARY_OP_SUBTRACT_INT | 837,517 | 0.2% | 93.0% |  |
| CONTAINS_OP | 799,380 | 0.2% | 93.3% |  |
| BUILD_MAP | 793,620 | 0.2% | 93.5% |  |
| GET_ITER | 789,715 | 0.2% | 93.7% |  |
| COPY_FREE_VARS | 781,536 | 0.2% | 93.9% |  |
| LOAD_ATTR_WITH_HINT | 764,634 | 0.2% | 94.1% | 2.1% |
| JUMP_FORWARD | 747,648 | 0.2% | 94.3% |  |
| LOAD_ATTR_CLASS | 731,468 | 0.2% | 94.5% | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 712,415 | 0.2% | 94.7% |  |
| LIST_EXTEND | 677,649 | 0.2% | 94.9% |  |
| CALL_INTRINSIC_1 | 665,629 | 0.2% | 95.1% |  |
| YIELD_VALUE | 577,520 | 0.2% | 95.2% |  |
| IS_OP | 568,740 | 0.2% | 95.4% |  |
| CALL_PY_WITH_DEFAULTS | 568,622 | 0.2% | 95.6% |  |
| STORE_SUBSCR_DICT | 565,080 | 0.2% | 95.7% |  |
| BINARY_SLICE | 554,160 | 0.2% | 95.9% |  |
| BINARY_SUBSCR_GETITEM | 492,680 | 0.1% | 96.0% |  |
| DICT_MERGE | 480,760 | 0.1% | 96.1% |  |
| CALL_KW | 463,042 | 0.1% | 96.3% |  |
| GET_AWAITABLE | 456,000 | 0.1% | 96.4% |  |
| PUSH_EXC_INFO | 453,323 | 0.1% | 96.5% |  |
| POP_EXCEPT | 453,203 | 0.1% | 96.6% |  |
| END_SEND | 444,000 | 0.1% | 96.7% |  |
| CHECK_EXC_MATCH | 443,484 | 0.1% | 96.9% |  |
| BINARY_SUBSCR | 426,480 | 0.1% | 97.0% |  |
| FOR_ITER_LIST | 424,285 | 0.1% | 97.1% |  |
| MAKE_CELL | 407,484 | 0.1% | 97.2% |  |
| JUMP_BACKWARD | 386,660 | 0.1% | 97.3% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 372,500 | 0.1% | 97.4% | 3.2% |
| MAKE_FUNCTION | 365,431 | 0.1% | 97.5% |  |
| FOR_ITER | 357,255 | 0.1% | 97.6% |  |
| COMPARE_OP_FLOAT | 356,500 | 0.1% | 97.7% | 0.0% |
| SEND | 338,220 | 0.1% | 97.8% |  |
| RETURN_GENERATOR | 337,000 | 0.1% | 97.9% |  |
| EXIT_INIT_CHECK | 324,640 | 0.1% | 98.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 324,640 | 0.1% | 98.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 294,132 | 0.1% | 98.2% | 46.4% |
| TO_BOOL_STR | 289,500 | 0.1% | 98.2% | 2.0% |
| STORE_ATTR | 288,820 | 0.1% | 98.3% |  |
| SEND_GEN | 287,800 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 277,940 | 0.1% | 98.5% | 0.0% |
| FOR_ITER_GEN | 275,940 | 0.1% | 98.5% |  |
| CALL_LIST_APPEND | 256,711 | 0.1% | 98.6% |  |
| CALL_BUILTIN_CLASS | 246,915 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 242,920 | 0.1% | 98.7% |  |
| BEFORE_WITH | 233,862 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 229,240 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 228,560 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 212,259 | 0.1% | 99.0% |  |
| DELETE_FAST | 208,302 | 0.1% | 99.1% |  |
| STORE_FAST_LOAD_FAST | 206,520 | 0.1% | 99.1% |  |
| EXTENDED_ARG | 206,040 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 205,260 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 194,280 | 0.1% | 99.3% |  |
| COMPARE_OP | 185,105 | 0.1% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 168,000 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 146,611 | 0.0% | 99.4% | 0.1% |
| BINARY_OP_ADD_FLOAT | 121,875 | 0.0% | 99.4% |  |
| STORE_DEREF | 121,560 | 0.0% | 99.5% |  |
| LOAD_ATTR_PROPERTY | 120,560 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 120,440 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 119,980 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 119,960 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 108,700 | 0.0% | 99.6% | 0.1% |
| LOAD_FAST_CHECK | 96,680 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 91,959 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 86,680 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 84,280 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 76,277 | 0.0% | 99.8% | 0.1% |
| LOAD_FAST_AND_CLEAR | 73,440 | 0.0% | 99.8% |  |
| BUILD_SLICE | 72,060 | 0.0% | 99.8% |  |
| RERAISE | 72,020 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 60,400 | 0.0% | 99.8% |  |
| CONVERT_VALUE | 60,320 | 0.0% | 99.8% |  |
| UNARY_INVERT | 60,180 | 0.0% | 99.9% |  |
| END_FOR | 59,980 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 59,018 | 0.0% | 99.9% | 9.0% |
| CALL_BUILTIN_O | 56,471 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 48,240 | 0.0% | 99.9% | 0.1% |
| FOR_ITER_RANGE | 31,215 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 28,680 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 27,948 | 0.0% | 99.9% | 0.9% |
| RAISE_VARARGS | 24,420 | 0.0% | 100.0% |  |
| BUILD_STRING | 24,240 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 23,960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 13,960 | 0.0% | 100.0% |  |
| LIST_APPEND | 13,120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 12,944 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 12,240 | 0.0% | 100.0% |  |
| UNARY_NOT | 12,140 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 12,080 | 0.0% | 100.0% |  |
| BUILD_SET | 12,020 | 0.0% | 100.0% |  |
| RESUME | 9,300 | 0.0% | 100.0% | 12.6% |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,045,642 | 6.0% | 6.0% |
| RESUME_CHECK LOAD_FAST | 11,389,514 | 3.1% | 9.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,306,468 | 2.8% | 12.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,570,635 | 2.1% | 14.0% |
| STORE_FAST LOAD_FAST | 6,779,821 | 1.9% | 15.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,394,031 | 1.7% | 17.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,049,544 | 1.7% | 19.3% |
| CACHE RESUME_CHECK | 5,375,746 | 1.5% | 20.7% |
| LOAD_CONST LOAD_FAST | 5,221,429 | 1.4% | 22.2% |
| RETURN_CONST POP_TOP | 5,219,330 | 1.4% | 23.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,155,472 | 1.4% | 25.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,998,494 | 1.4% | 26.4% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,546,916 | 1.2% | 27.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,461,311 | 1.2% | 28.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 4,181,652 | 1.1% | 30.0% |
| POP_TOP LOAD_FAST | 3,924,676 | 1.1% | 31.0% |
| RETURN_VALUE INTERPRETER_EXIT | 3,734,877 | 1.0% | 32.1% |
| LOAD_FAST LOAD_ATTR | 3,712,414 | 1.0% | 33.1% |
| LOAD_FAST LOAD_CONST | 3,421,135 | 0.9% | 34.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,414,309 | 0.9% | 34.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 3,342,684 | 0.9% | 35.9% |
| LOAD_FAST RETURN_VALUE | 3,170,091 | 0.9% | 36.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,097,238 | 0.8% | 37.6% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 3,035,562 | 0.8% | 38.4% |
| POP_TOP RETURN_CONST | 2,957,517 | 0.8% | 39.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,833,363 | 0.8% | 40.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,813,442 | 0.8% | 40.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,792,760 | 0.8% | 41.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,759,849 | 0.8% | 42.3% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,691,048 | 0.7% | 43.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,415,681 | 0.7% | 43.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,298,896 | 0.6% | 44.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,277,720 | 0.6% | 44.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,270,175 | 0.6% | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 2,248,766 | 0.6% | 46.1% |
| RETURN_VALUE STORE_FAST | 2,135,943 | 0.6% | 46.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,116,504 | 0.6% | 47.3% |
| LOAD_FAST CALL | 2,050,880 | 0.6% | 47.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,992,575 | 0.5% | 48.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,968,007 | 0.5% | 48.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,951,606 | 0.5% | 49.5% |
| CALL STORE_FAST | 1,947,021 | 0.5% | 50.0% |
| RETURN_VALUE TO_BOOL_BOOL | 1,887,088 | 0.5% | 50.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,886,306 | 0.5% | 51.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,880,245 | 0.5% | 51.6% |
| LOAD_FAST STORE_ATTR_SLOT | 1,799,598 | 0.5% | 52.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,797,172 | 0.5% | 52.5% |
| NOP LOAD_FAST | 1,751,517 | 0.5% | 53.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,743,482 | 0.5% | 53.5% |
| PUSH_NULL LOAD_FAST | 1,724,682 | 0.5% | 54.0% |
| LOAD_CONST COMPARE_OP_INT | 1,716,939 | 0.5% | 54.4% |
| RETURN_CONST INTERPRETER_EXIT | 1,711,905 | 0.5% | 54.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,681,366 | 0.5% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,672,960 | 0.5% | 55.8% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,484,707 | 0.4% | 56.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,364,435 | 0.4% | 56.6% |
| LOAD_CONST STORE_FAST | 1,333,956 | 0.4% | 57.0% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,303,524 | 0.4% | 57.3% |
| RESUME_CHECK NOP | 1,248,044 | 0.3% | 57.7% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 1,214,203 | 0.3% | 58.0% |
| LOAD_ATTR LOAD_FAST | 1,209,244 | 0.3% | 58.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,178,793 | 0.3% | 58.6% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,139,975 | 0.3% | 59.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,131,305 | 0.3% | 59.3% |
| LOAD_FAST COPY | 1,117,279 | 0.3% | 59.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,093,580 | 0.3% | 59.9% |
| LOAD_CONST LOAD_CONST | 1,081,234 | 0.3% | 60.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,064,075 | 0.3% | 60.5% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,063,373 | 0.3% | 60.7% |
| STORE_ATTR_SLOT LOAD_CONST | 1,047,516 | 0.3% | 61.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,047,041 | 0.3% | 61.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,043,920 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 1,037,615 | 0.3% | 61.9% |
| LOAD_ATTR PUSH_NULL | 1,032,591 | 0.3% | 62.2% |
| BUILD_LIST LOAD_FAST | 1,026,449 | 0.3% | 62.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,008,344 | 0.3% | 62.7% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 1,007,440 | 0.3% | 63.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 997,280 | 0.3% | 63.3% |
| CALL POP_TOP | 990,360 | 0.3% | 63.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 984,100 | 0.3% | 63.8% |
| RETURN_VALUE RETURN_VALUE | 973,720 | 0.3% | 64.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 941,189 | 0.3% | 64.3% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 924,279 | 0.3% | 64.6% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 924,279 | 0.3% | 64.8% |
| POP_TOP LOAD_CONST | 916,606 | 0.3% | 65.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 900,980 | 0.2% | 65.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 886,029 | 0.2% | 65.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 872,742 | 0.2% | 65.8% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 855,656 | 0.2% | 66.1% |
| LOAD_FAST CALL_BUILTIN_FAST | 837,640 | 0.2% | 66.3% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 829,314 | 0.2% | 66.5% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 827,759 | 0.2% | 66.7% |
| CALL LOAD_FAST | 825,135 | 0.2% | 67.0% |
| CALL_BUILTIN_FAST STORE_FAST | 814,460 | 0.2% | 67.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 813,215 | 0.2% | 67.4% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 797,440 | 0.2% | 67.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 791,180 | 0.2% | 67.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 785,212 | 0.2% | 68.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 763,671 | 0.2% | 68.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 760,470 | 0.2% | 68.5% |


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
| RESUME_CHECK | 5,375,746 | 93.7% |
| COPY_FREE_VARS | 237,856 | 4.1% |
| POP_TOP | 97,060 | 1.7% |
| MAKE_CELL | 12,360 | 0.2% |
| RETURN_GENERATOR | 12,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 112,402 | 48.1% |
| RETURN_VALUE | 108,100 | 46.2% |
| LOAD_GLOBAL_MODULE | 12,540 | 5.4% |
| CALL | 380 | 0.2% |
| LOAD_ATTR | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 233,782 | 100.0% |
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
| LOAD_CONST | 421,700 | 98.9% |
| BINARY_SUBSCR | 3,000 | 0.7% |
| BUILD_TUPLE | 640 | 0.2% |
| LOAD_FAST | 460 | 0.1% |
| LOAD_NAME | 340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 263,880 | 61.9% |
| LOAD_FAST | 60,140 | 14.1% |
| CONVERT_VALUE | 24,000 | 5.6% |
| LOAD_CONST | 12,960 | 3.0% |
| BINARY_SUBSCR_LIST_INT | 12,300 | 2.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 390,942 | 88.2% |
| BUILD_TUPLE | 24,080 | 5.4% |
| LOAD_ATTR_MODULE | 16,182 | 3.6% |
| LOAD_GLOBAL_MODULE | 11,980 | 2.7% |
| LOAD_GLOBAL | 260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 443,484 | 100.0% |


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
| LOAD_FAST | 325,125 | 41.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 144,140 | 18.3% |
| LOAD_ATTR_INSTANCE_VALUE | 96,555 | 12.2% |
| LOAD_ATTR | 72,140 | 9.1% |
| BINARY_SLICE | 36,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 404,285 | 51.2% |
| FOR_ITER | 148,015 | 18.7% |
| FOR_ITER_TUPLE | 73,020 | 9.2% |
| CALL_PY_EXACT_ARGS | 72,720 | 9.2% |
| LOAD_FAST_AND_CLEAR | 49,440 | 6.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,734,877 | 65.2% |
| RETURN_CONST | 1,711,905 | 29.9% |
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
| LOAD_CONST | 365,431 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 160,731 | 44.0% |
| CALL | 120,080 | 32.9% |
| LOAD_FAST | 48,400 | 13.2% |
| CALL_PY_EXACT_ARGS | 23,920 | 6.5% |
| STORE_DEREF | 12,000 | 3.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,248,044 | 39.6% |
| POP_JUMP_IF_FALSE | 449,606 | 14.3% |
| STORE_FAST | 445,992 | 14.2% |
| STORE_ATTR_INSTANCE_VALUE | 362,808 | 11.5% |
| POP_JUMP_IF_TRUE | 274,863 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,751,517 | 55.6% |
| LOAD_GLOBAL_MODULE | 591,580 | 18.8% |
| LOAD_FAST_LOAD_FAST | 300,220 | 9.5% |
| LOAD_DEREF | 134,720 | 4.3% |
| LOAD_GLOBAL_BUILTIN | 120,140 | 3.8% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 328,581 | 72.5% |
| SWAP | 60,080 | 13.3% |
| COPY | 36,020 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 12,120 | 2.7% |
| STORE_SUBSCR_DICT | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 290,441 | 64.1% |
| RETURN_VALUE | 60,080 | 13.3% |
| RERAISE | 36,020 | 7.9% |
| DELETE_FAST | 24,000 | 5.3% |
| ENTER_EXECUTOR | 15,602 | 3.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,219,330 | 51.0% |
| CALL | 990,360 | 9.7% |
| CALL_METHOD_DESCRIPTOR_O | 827,759 | 8.1% |
| POP_JUMP_IF_FALSE | 615,564 | 6.0% |
| CALL_FUNCTION_EX | 499,909 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,924,676 | 38.4% |
| RETURN_CONST | 2,957,517 | 28.9% |
| LOAD_CONST | 916,606 | 9.0% |
| ENTER_EXECUTOR | 704,246 | 6.9% |
| RESUME_CHECK | 336,620 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 348,440 | 76.9% |
| RERAISE | 36,020 | 7.9% |
| CALL | 30,403 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 24,060 | 5.3% |
| RAISE_VARARGS | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400,641 | 88.4% |
| LOAD_GLOBAL_MODULE | 40,062 | 8.8% |
| LOAD_FAST | 12,000 | 2.6% |
| LOAD_GLOBAL | 620 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,681,366 | 47.0% |
| LOAD_ATTR | 1,032,591 | 28.8% |
| LOAD_FAST | 468,330 | 13.1% |
| LOAD_DEREF | 204,500 | 5.7% |
| RETURN_VALUE | 132,080 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,724,682 | 48.2% |
| CALL | 731,149 | 20.4% |
| LOAD_FAST_LOAD_FAST | 713,048 | 19.9% |
| LOAD_GLOBAL_MODULE | 108,380 | 3.0% |
| LOAD_CONST | 96,100 | 2.7% |


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
| LOAD_FAST | 3,170,091 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,691,048 | 23.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 622,560 | 5.4% |
| CALL | 621,641 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 3,734,877 | 32.3% |
| STORE_FAST | 2,135,943 | 18.5% |
| TO_BOOL_BOOL | 1,887,088 | 16.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| LOAD_FAST | 604,315 | 5.2% |


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
| LOAD_FAST | 560,055 | 40.5% |
| LOAD_ATTR_INSTANCE_VALUE | 521,095 | 37.7% |
| LOAD_ATTR | 122,800 | 8.9% |
| ENTER_EXECUTOR | 115,165 | 8.3% |
| COPY | 36,800 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,139,975 | 82.5% |
| POP_JUMP_IF_TRUE | 227,651 | 16.5% |
| TO_BOOL | 5,960 | 0.4% |
| TO_BOOL_BOOL | 5,200 | 0.4% |
| TO_BOOL_NONE | 1,059 | 0.1% |


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
| LOAD_GLOBAL_MODULE | 230,023 | 19.0% |
| LOAD_CONST | 169,904 | 14.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 155,880 | 12.9% |
| LOAD_FAST | 111,665 | 9.2% |
| LOAD_ATTR_MODULE | 104,482 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 321,322 | 26.6% |
| STORE_FAST | 219,200 | 18.1% |
| COPY | 176,762 | 14.6% |
| LOAD_FAST | 96,640 | 8.0% |
| RETURN_VALUE | 96,120 | 8.0% |


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
| LOAD_FAST | 382,940 | 30.6% |
| LOAD_ATTR_SLOT | 379,409 | 30.3% |
| STORE_FAST | 111,835 | 8.9% |
| LOAD_FAST_LOAD_FAST | 107,540 | 8.6% |
| RESUME_CHECK | 72,940 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,026,449 | 82.1% |
| STORE_FAST | 137,470 | 11.0% |
| SWAP | 49,440 | 4.0% |
| LOAD_CONST | 24,120 | 1.9% |
| CALL_BUILTIN_CLASS | 11,960 | 1.0% |


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
| LOAD_FAST | 512,256 | 36.6% |
| LOAD_FAST_LOAD_FAST | 384,540 | 27.5% |
| LOAD_GLOBAL_BUILTIN | 156,660 | 11.2% |
| LOAD_GLOBAL_MODULE | 99,540 | 7.1% |
| LOAD_ATTR_MODULE | 71,940 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 191,840 | 13.7% |
| RETURN_VALUE | 180,760 | 12.9% |
| LOAD_CONST | 160,351 | 11.5% |
| CALL_ISINSTANCE | 157,200 | 11.2% |
| CONTAINS_OP | 121,400 | 8.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,050,880 | 32.8% |
| PUSH_NULL | 731,149 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 613,100 | 9.8% |
| LOAD_GLOBAL_MODULE | 590,005 | 9.4% |
| LOAD_CONST | 468,395 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,947,021 | 31.1% |
| POP_TOP | 990,360 | 15.8% |
| LOAD_FAST | 825,135 | 13.2% |
| RETURN_VALUE | 621,641 | 9.9% |
| BINARY_SUBSCR_DICT | 420,140 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 480,760 | 44.5% |
| CALL_INTRINSIC_1 | 439,769 | 40.7% |
| LOAD_FAST | 100,542 | 9.3% |
| BUILD_MAP | 59,200 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,909 | 46.3% |
| RETURN_VALUE | 221,262 | 20.5% |
| RESUME_CHECK | 132,220 | 12.2% |
| STORE_FAST | 119,360 | 11.0% |
| CALL | 83,300 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 653,629 | 98.2% |
| RERAISE | 12,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 439,769 | 66.1% |
| BUILD_MAP | 154,660 | 23.2% |
| LOAD_CONST | 59,200 | 8.9% |
| RERAISE | 12,000 | 1.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 403,362 | 87.1% |
| ENTER_EXECUTOR | 59,680 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 265,420 | 57.3% |
| STORE_FAST | 100,342 | 21.7% |
| COPY_FREE_VARS | 24,000 | 5.2% |
| RETURN_VALUE | 12,440 | 2.7% |
| LOAD_FAST | 12,180 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 119,547 | 64.6% |
| LOAD_ATTR | 24,440 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,340 | 6.7% |
| LOAD_FAST_LOAD_FAST | 12,000 | 6.5% |
| LOAD_ATTR_CLASS | 12,000 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120,451 | 65.1% |
| POP_JUMP_IF_TRUE | 60,580 | 32.7% |
| COMPARE_OP | 1,926 | 1.0% |
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
| LOAD_FAST_LOAD_FAST | 108,660 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 605,460 | 75.7% |
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
| LOAD_FAST | 1,117,279 | 45.8% |
| LOAD_CONST | 252,200 | 10.3% |
| STORE_ATTR_INSTANCE_VALUE | 227,980 | 9.3% |
| BINARY_OP | 176,762 | 7.2% |
| CONTAINS_OP | 120,040 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 924,279 | 37.9% |
| LOAD_FAST | 456,000 | 18.7% |
| TO_BOOL_BOOL | 326,140 | 13.4% |
| TO_BOOL_INT | 205,039 | 8.4% |
| TO_BOOL_NONE | 190,718 | 7.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 288,540 | 36.9% |
| CACHE | 237,856 | 30.4% |
| CALL | 120,900 | 15.5% |
| LOAD_ATTR_PROPERTY | 83,920 | 10.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 25,980 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 731,976 | 93.7% |
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
| POP_TOP | 16,222 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 108,000 | 51.8% |
| RETURN_CONST | 48,000 | 23.0% |
| LOAD_FAST | 28,222 | 13.5% |
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
| POP_TOP | 704,246 | 56.1% |
| POP_JUMP_IF_TRUE | 147,841 | 11.8% |
| CALL_LIST_APPEND | 98,389 | 7.8% |
| STORE_ATTR_INSTANCE_VALUE | 83,660 | 6.7% |
| EXTENDED_ARG | 60,140 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 451,550 | 36.0% |
| CALL | 181,015 | 14.4% |
| LOAD_FAST | 115,516 | 9.2% |
| TO_BOOL | 115,165 | 9.2% |
| JUMP_BACKWARD | 107,760 | 8.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 119,920 | 58.2% |
| POP_JUMP_IF_TRUE | 60,060 | 29.1% |
| COMPARE_OP_STR | 12,180 | 5.9% |
| STORE_ATTR_INSTANCE_VALUE | 11,980 | 5.8% |
| GET_ITER | 320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 108,000 | 52.4% |
| ENTER_EXECUTOR | 60,140 | 29.2% |
| POP_JUMP_IF_FALSE | 24,540 | 11.9% |
| JUMP_FORWARD | 12,340 | 6.0% |
| JUMP_BACKWARD | 500 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 157,980 | 44.2% |
| GET_ITER | 148,015 | 41.4% |
| SWAP | 24,460 | 6.8% |
| LOAD_FAST | 24,200 | 6.8% |
| FOR_ITER | 2,320 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 134,855 | 37.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 108,140 | 30.3% |
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
| LOAD_GLOBAL_MODULE | 314,800 | 55.4% |
| LOAD_FAST | 108,560 | 19.1% |
| LOAD_CONST | 108,160 | 19.0% |
| LOAD_DEREF | 24,000 | 4.2% |
| LOAD_FAST_LOAD_FAST | 12,360 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 460,280 | 80.9% |
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
| POP_TOP | 219,500 | 56.8% |
| ENTER_EXECUTOR | 107,760 | 27.9% |
| STORE_SUBSCR | 36,020 | 9.3% |
| POP_JUMP_IF_TRUE | 14,740 | 3.8% |
| POP_JUMP_IF_FALSE | 2,220 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 215,960 | 55.9% |
| FOR_ITER | 157,980 | 40.9% |
| FOR_ITER_LIST | 6,460 | 1.7% |
| LOAD_FAST | 2,460 | 0.6% |
| FOR_ITER_RANGE | 1,260 | 0.3% |


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
| STORE_FAST | 446,397 | 59.7% |
| POP_TOP | 132,480 | 17.7% |
| STORE_ATTR_INSTANCE_VALUE | 48,355 | 6.5% |
| POP_JUMP_IF_TRUE | 24,400 | 3.3% |
| STORE_ATTR | 24,120 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 479,866 | 64.2% |
| LOAD_CONST | 92,230 | 12.3% |
| LOAD_FAST_LOAD_FAST | 60,340 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 42,172 | 5.6% |
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
| LOAD_ATTR_SLOT | 379,409 | 56.0% |
| LOAD_FAST | 262,020 | 38.7% |
| LOAD_CONST | 24,020 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 11,980 | 1.8% |
| LOAD_DEREF | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 653,629 | 96.5% |
| LOAD_FAST | 24,000 | 3.5% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,712,414 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 872,742 | 14.2% |
| ENTER_EXECUTOR | 451,550 | 7.3% |
| LOAD_ATTR_WITH_HINT | 335,900 | 5.5% |
| LOAD_GLOBAL_MODULE | 303,620 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,209,244 | 19.7% |
| PUSH_NULL | 1,032,591 | 16.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,007,440 | 16.4% |
| LOAD_CONST | 483,560 | 7.9% |
| CALL_PY_EXACT_ARGS | 323,291 | 5.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,421,135 | 20.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,672,960 | 10.2% |
| LOAD_CONST | 1,081,234 | 6.6% |
| POP_JUMP_IF_FALSE | 1,063,373 | 6.5% |
| STORE_ATTR_SLOT | 1,047,516 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,221,429 | 32.0% |
| COMPARE_OP_INT | 1,716,939 | 10.5% |
| STORE_FAST | 1,333,956 | 8.2% |
| LOAD_CONST | 1,081,234 | 6.6% |
| CALL_PY_EXACT_ARGS | 659,820 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 401,228 | 19.2% |
| RESUME_CHECK | 207,268 | 9.9% |
| POP_JUMP_IF_FALSE | 171,288 | 8.2% |
| POP_JUMP_IF_TRUE | 144,340 | 6.9% |
| NOP | 134,720 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,920 | 24.2% |
| LOAD_ATTR_INSTANCE_VALUE | 367,944 | 17.6% |
| PUSH_NULL | 204,500 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 155,680 | 7.4% |
| LOAD_ATTR | 151,436 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,389,514 | 15.0% |
| POP_JUMP_IF_FALSE | 7,570,635 | 10.0% |
| STORE_FAST | 6,779,821 | 9.0% |
| LOAD_CONST | 5,221,429 | 6.9% |
| LOAD_GLOBAL_BUILTIN | 5,155,472 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,045,642 | 29.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,049,544 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 4,998,494 | 6.6% |
| LOAD_ATTR | 3,712,414 | 4.9% |
| LOAD_CONST | 3,421,135 | 4.5% |


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
| LOAD_ATTR_METHOD_NO_DICT | 72,060 | 74.5% |
| POP_JUMP_IF_FALSE | 12,000 | 12.4% |
| STORE_FAST | 12,000 | 12.4% |
| POP_TOP | 320 | 0.3% |
| JUMP_FORWARD | 180 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 71,960 | 74.4% |
| LOAD_ATTR | 12,000 | 12.4% |
| LOAD_CONST | 12,000 | 12.4% |
| POP_JUMP_IF_NOT_NONE | 440 | 0.5% |
| LOAD_FAST | 80 | 0.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,303,524 | 12.6% |
| LOAD_GLOBAL_MODULE | 1,093,580 | 10.6% |
| STORE_FAST | 1,064,075 | 10.3% |
| STORE_ATTR_INSTANCE_VALUE | 997,280 | 9.6% |
| POP_JUMP_IF_FALSE | 900,980 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,992,575 | 19.2% |
| STORE_ATTR_SLOT | 1,797,172 | 17.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,364,435 | 13.2% |
| LOAD_FAST | 886,029 | 8.6% |
| LOAD_FAST_LOAD_FAST | 734,368 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,560 | 12.4% |
| POP_JUMP_IF_FALSE | 3,460 | 12.1% |
| RESUME | 2,480 | 8.6% |
| RESUME_CHECK | 2,420 | 8.4% |
| STORE_FAST | 2,320 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,680 | 33.8% |
| LOAD_GLOBAL_BUILTIN | 4,380 | 15.3% |
| LOAD_ATTR | 4,140 | 14.4% |
| LOAD_FAST | 4,060 | 14.2% |
| CALL | 1,720 | 6.0% |


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
| MAKE_CELL | 187,056 | 45.9% |
| CALL_PY_EXACT_ARGS | 159,428 | 39.1% |
| COPY_FREE_VARS | 24,100 | 5.9% |
| CACHE | 12,360 | 3.0% |
| CALL | 12,320 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 207,908 | 51.0% |
| MAKE_CELL | 187,056 | 45.9% |
| RETURN_GENERATOR | 12,000 | 2.9% |
| RESUME | 520 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,394,031 | 44.9% |
| COMPARE_OP_INT | 2,759,849 | 19.4% |
| TO_BOOL_NONE | 1,214,203 | 8.5% |
| TO_BOOL | 1,139,975 | 8.0% |
| CONTAINS_OP | 605,460 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,570,635 | 53.2% |
| RETURN_CONST | 1,484,707 | 10.4% |
| LOAD_CONST | 1,063,373 | 7.5% |
| LOAD_GLOBAL_MODULE | 1,008,344 | 7.1% |
| LOAD_FAST_LOAD_FAST | 900,980 | 6.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,035,562 | 55.3% |
| LOAD_FAST | 2,116,504 | 38.6% |
| LOAD_ATTR | 132,960 | 2.4% |
| LOAD_DEREF | 132,080 | 2.4% |
| LOAD_ATTR_WITH_HINT | 34,958 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,546,916 | 82.8% |
| RETURN_CONST | 279,448 | 5.1% |
| LOAD_GLOBAL_MODULE | 276,580 | 5.0% |
| LOAD_FAST_LOAD_FAST | 144,440 | 2.6% |
| NOP | 132,300 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,047,041 | 63.4% |
| LOAD_ATTR_INSTANCE_VALUE | 444,360 | 26.9% |
| LOAD_ATTR | 108,980 | 6.6% |
| LOAD_GLOBAL_MODULE | 12,600 | 0.8% |
| CALL | 12,020 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 580,218 | 35.2% |
| LOAD_FAST_LOAD_FAST | 435,248 | 26.4% |
| LOAD_GLOBAL_MODULE | 332,255 | 20.1% |
| LOAD_CONST | 132,200 | 8.0% |
| LOAD_DEREF | 84,280 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,298,896 | 54.9% |
| COMPARE_OP_INT | 708,520 | 16.9% |
| TO_BOOL_INT | 261,592 | 6.3% |
| TO_BOOL_STR | 240,200 | 5.7% |
| TO_BOOL | 227,651 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,951,606 | 46.6% |
| LOAD_GLOBAL_BUILTIN | 449,420 | 10.7% |
| LOAD_CONST | 290,131 | 6.9% |
| NOP | 274,863 | 6.6% |
| LOAD_FAST_LOAD_FAST | 228,460 | 5.5% |


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
| POP_TOP | 2,957,517 | 37.4% |
| POP_JUMP_IF_FALSE | 1,484,707 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 760,470 | 9.6% |
| STORE_ATTR_SLOT | 613,028 | 7.8% |
| STORE_FAST | 395,024 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,219,330 | 66.0% |
| INTERPRETER_EXIT | 1,711,905 | 21.7% |
| EXIT_INIT_CHECK | 324,640 | 4.1% |
| STORE_FAST | 176,395 | 2.2% |
| TO_BOOL_BOOL | 132,317 | 1.7% |


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
| MAKE_FUNCTION | 160,731 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 51,528 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 71,303 | 33.6% |
| SET_FUNCTION_ATTRIBUTE | 51,528 | 24.3% |
| CALL | 39,268 | 18.5% |
| LOAD_FAST | 24,320 | 11.5% |
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
| LOAD_FAST | 180,740 | 62.6% |
| LOAD_FAST_LOAD_FAST | 54,500 | 18.9% |
| LOAD_DEREF | 36,480 | 12.6% |
| STORE_FAST_LOAD_FAST | 12,080 | 4.2% |
| STORE_ATTR | 4,080 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60,460 | 20.9% |
| LOAD_FAST | 51,540 | 17.8% |
| RETURN_CONST | 49,720 | 17.2% |
| LOAD_GLOBAL_BUILTIN | 35,960 | 12.5% |
| JUMP_FORWARD | 24,120 | 8.4% |


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
| RETURN_VALUE | 2,135,943 | 19.3% |
| CALL | 1,947,021 | 17.6% |
| LOAD_CONST | 1,333,956 | 12.0% |
| CALL_BUILTIN_FAST | 814,460 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 707,725 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,779,821 | 61.2% |
| LOAD_FAST_LOAD_FAST | 1,064,075 | 9.6% |
| LOAD_CONST | 643,692 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 483,594 | 4.4% |
| JUMP_FORWARD | 446,397 | 4.0% |


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
| LOAD_ATTR_METHOD_NO_DICT | 108,640 | 52.6% |
| STORE_ATTR_INSTANCE_VALUE | 83,920 | 40.6% |
| STORE_ATTR | 12,080 | 5.8% |
| TO_BOOL_LIST | 540 | 0.3% |
| TO_BOOL_STR | 500 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 829,314 | 76.6% |
| UNPACK_SEQUENCE_LIST | 119,960 | 11.1% |
| UNPACK_SEQUENCE_TUPLE | 72,300 | 6.7% |
| COPY | 24,200 | 2.2% |
| STORE_FAST_STORE_FAST | 24,160 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 565,294 | 52.2% |
| LOAD_FAST_LOAD_FAST | 168,360 | 15.5% |
| LOAD_GLOBAL_MODULE | 131,880 | 12.2% |
| STORE_FAST | 96,460 | 8.9% |
| LOAD_GLOBAL_BUILTIN | 84,180 | 7.8% |


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
| BINARY_OP_ADD_INT | 567,282 | 40.1% |
| BINARY_OP_SUBTRACT_INT | 333,277 | 23.6% |
| LOAD_FAST | 192,300 | 13.6% |
| LOAD_ATTR | 88,381 | 6.3% |
| BUILD_LIST | 49,440 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 924,279 | 65.4% |
| STORE_FAST | 125,161 | 8.9% |
| COPY | 108,300 | 7.7% |
| LOAD_CONST | 72,280 | 5.1% |
| POP_EXCEPT | 60,080 | 4.2% |


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
| BUILD_TUPLE | 108,060 | 18.7% |
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
| LOAD_ATTR_INSTANCE_VALUE | 15,555 | 12.8% |
| LOAD_ATTR | 11,960 | 9.8% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,160 | 58.4% |
| LOAD_GLOBAL_MODULE | 35,080 | 28.8% |
| STORE_FAST | 15,575 | 12.8% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 675,942 | 62.4% |
| LOAD_FAST_LOAD_FAST | 263,840 | 24.3% |
| CALL_LEN | 83,960 | 7.7% |
| LOAD_CONST | 59,760 | 5.5% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 567,282 | 52.3% |
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
| RETURN_VALUE | 11,960 | 92.4% |
| LOAD_CONST | 944 | 7.3% |
| BINARY_OP | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,980 | 92.6% |
| CALL_BUILTIN_O | 944 | 7.3% |
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
| RETURN_VALUE | 60,104 | 65.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,960 | 13.0% |
| LOAD_ATTR_WITH_HINT | 11,960 | 13.0% |
| CALL | 7,775 | 8.5% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 59,180 | 64.4% |
| RETURN_VALUE | 11,980 | 13.0% |
| LOAD_FAST | 11,980 | 13.0% |
| STORE_FAST | 8,759 | 9.5% |
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
| LOAD_CONST | 33,357 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 333,277 | 39.8% |
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
| LOAD_FAST | 350,460 | 38.8% |
| BUILD_TUPLE | 48,080 | 5.3% |
| LOAD_FAST_LOAD_FAST | 36,020 | 4.0% |
| RETURN_VALUE | 23,980 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 432,040 | 47.8% |
| PUSH_EXC_INFO | 348,440 | 38.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 38,080 | 4.2% |
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
| ENTER_EXECUTOR | 200 | 0.0% |
| LOAD_CONST | 200 | 0.0% |
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
| LOAD_CONST | 51,437 | 67.4% |
| BINARY_SUBSCR | 12,300 | 16.1% |
| BINARY_OP_SUBTRACT_INT | 11,960 | 15.7% |
| LOAD_FAST | 580 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,240 | 31.8% |
| LOAD_ATTR_SLOT | 21,036 | 27.6% |
| STORE_FAST | 15,401 | 20.2% |
| LOAD_CONST | 11,980 | 15.7% |
| TO_BOOL_BOOL | 2,400 | 3.1% |


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
| LOAD_CONST | 228,980 | 99.9% |
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
| LOAD_CONST | 108,380 | 36.8% |
| LOAD_FAST | 85,405 | 29.0% |
| LOAD_FAST_LOAD_FAST | 48,484 | 16.5% |
| BINARY_SLICE | 23,960 | 8.1% |
| CALL_BUILTIN_CLASS | 23,960 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 157,209 | 53.4% |
| POP_TOP | 108,260 | 36.8% |
| COPY_FREE_VARS | 25,980 | 8.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,060 | 0.7% |
| CALL_PY_EXACT_ARGS | 483 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 71,960 | 29.1% |
| LOAD_FAST | 39,815 | 16.1% |
| CALL | 36,480 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 36,160 | 14.6% |
| LOAD_GLOBAL_MODULE | 14,080 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,500 | 39.1% |
| LOAD_FAST | 36,200 | 14.7% |
| RETURN_VALUE | 35,980 | 14.6% |
| GET_ITER | 29,795 | 12.1% |
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
| LOAD_ATTR | 14,808 | 53.0% |
| LOAD_FAST | 12,620 | 45.2% |
| LOAD_CONST | 300 | 1.1% |
| CALL_STR_1 | 80 | 0.3% |
| CALL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,848 | 53.1% |
| STORE_FAST | 12,380 | 44.3% |
| RETURN_VALUE | 580 | 2.1% |
| BEFORE_WITH | 80 | 0.3% |
| PUSH_EXC_INFO | 60 | 0.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,095 | 86.9% |
| LOAD_ATTR_INSTANCE_VALUE | 5,152 | 9.1% |
| BINARY_OP_MULTIPLY_FLOAT | 944 | 1.7% |
| BUILD_TUPLE | 360 | 0.6% |
| CALL | 200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 23,920 | 42.4% |
| STORE_FAST | 17,232 | 30.5% |
| BINARY_SUBSCR_DICT | 11,960 | 21.2% |
| POP_TOP | 1,615 | 2.9% |
| LOAD_CONST | 964 | 1.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,131,305 | 54.2% |
| LOAD_GLOBAL_BUILTIN | 437,120 | 21.0% |
| LOAD_ATTR_MODULE | 298,800 | 14.3% |
| BUILD_TUPLE | 157,200 | 7.5% |
| LOAD_ATTR | 59,960 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,880,245 | 90.2% |
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
| LOAD_FAST | 649,700 | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE | 327,860 | 32.7% |
| LOAD_GLOBAL_MODULE | 12,080 | 1.2% |
| BINARY_SUBSCR | 12,060 | 1.2% |
| CALL | 640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 303,405 | 30.3% |
| LOAD_FAST | 226,320 | 22.6% |
| LOAD_CONST | 97,340 | 9.7% |
| BINARY_OP_ADD_INT | 83,960 | 8.4% |
| BINARY_OP_SUBTRACT_INT | 60,080 | 6.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 136,951 | 53.3% |
| BUILD_TUPLE | 76,201 | 29.7% |
| RETURN_VALUE | 24,040 | 9.4% |
| ENTER_EXECUTOR | 18,919 | 7.4% |
| CALL | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120,260 | 46.8% |
| ENTER_EXECUTOR | 98,389 | 38.3% |
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
| LOAD_FAST | 20,916 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 622,560 | 65.0% |
| CALL_PY_EXACT_ARGS | 108,040 | 11.3% |
| STORE_FAST | 93,336 | 9.7% |
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
| LOAD_FAST_LOAD_FAST | 15,555 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 268,155 | 37.6% |
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
| LOAD_ATTR | 1,007,440 | 58.9% |
| LOAD_ATTR_METHOD_NO_DICT | 662,510 | 38.8% |
| LOAD_FAST | 24,040 | 1.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 11,960 | 0.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,321 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 984,100 | 57.6% |
| POP_TOP | 236,015 | 13.8% |
| GET_ITER | 144,140 | 8.4% |
| STORE_FAST | 123,775 | 7.2% |
| LOAD_FAST | 72,200 | 4.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 574,999 | 54.4% |
| BUILD_TUPLE | 191,840 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 84,120 | 8.0% |
| LOAD_FAST_CHECK | 71,960 | 6.8% |
| LOAD_CONST | 48,400 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 827,759 | 78.3% |
| STORE_FAST | 144,020 | 13.6% |
| LOAD_CONST | 24,300 | 2.3% |
| UNPACK_SEQUENCE_TUPLE | 24,080 | 2.3% |
| PUSH_EXC_INFO | 24,060 | 2.3% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,461,311 | 40.5% |
| LOAD_FAST | 3,414,309 | 31.0% |
| LOAD_FAST_LOAD_FAST | 660,996 | 6.0% |
| LOAD_CONST | 659,820 | 6.0% |
| LOAD_ATTR | 323,291 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,306,468 | 93.5% |
| COPY_FREE_VARS | 288,540 | 2.6% |
| RETURN_GENERATOR | 264,140 | 2.4% |
| MAKE_CELL | 159,428 | 1.4% |
| TO_BOOL_BOOL | 5,560 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 143,680 | 25.3% |
| LOAD_FAST | 131,980 | 23.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 124,022 | 21.8% |
| PUSH_NULL | 72,040 | 12.7% |
| LOAD_ATTR | 35,920 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 556,582 | 97.9% |
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
| LOAD_ATTR_SLOT | 332,557 | 93.3% |
| LOAD_FAST | 15,221 | 4.3% |
| LOAD_GLOBAL_MODULE | 8,582 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 332,577 | 93.3% |
| POP_JUMP_IF_FALSE | 23,923 | 6.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,716,939 | 49.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,037,615 | 29.7% |
| LOAD_ATTR_CLASS | 383,960 | 11.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 119,920 | 3.4% |
| COPY | 108,180 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,759,849 | 79.0% |
| POP_JUMP_IF_TRUE | 708,520 | 20.3% |
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
| GET_ITER | 404,285 | 95.3% |
| SWAP | 12,460 | 2.9% |
| JUMP_BACKWARD | 6,460 | 1.5% |
| FOR_ITER | 780 | 0.2% |
| EXTENDED_ARG | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 232,037 | 54.7% |
| LOAD_FAST | 139,999 | 33.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,013 | 7.1% |
| UNPACK_SEQUENCE_TUPLE | 11,960 | 2.8% |
| RETURN_CONST | 7,816 | 1.8% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 29,795 | 95.5% |
| JUMP_BACKWARD | 1,260 | 4.0% |
| FOR_ITER | 100 | 0.3% |
| SWAP | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,635 | 98.1% |
| STORE_FAST_LOAD_FAST | 380 | 1.2% |
| RETURN_CONST | 60 | 0.2% |
| LOAD_CONST | 40 | 0.1% |
| LOAD_GLOBAL | 40 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 73,020 | 84.2% |
| SWAP | 12,460 | 14.4% |
| LOAD_FAST | 700 | 0.8% |
| JUMP_BACKWARD | 420 | 0.5% |
| FOR_ITER | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,060 | 69.3% |
| STORE_FAST | 13,740 | 15.9% |
| SWAP | 11,980 | 13.8% |
| STORE_FAST_LOAD_FAST | 500 | 0.6% |
| ENTER_EXECUTOR | 280 | 0.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 454,048 | 62.1% |
| LOAD_GLOBAL_MODULE | 228,420 | 31.2% |
| LOAD_FAST | 48,600 | 6.6% |
| LOAD_ATTR | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 383,960 | 52.5% |
| LOAD_FAST | 142,688 | 19.5% |
| BINARY_OP | 96,080 | 13.1% |
| CALL | 48,060 | 6.6% |
| RETURN_VALUE | 24,200 | 3.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,045,642 | 86.4% |
| LOAD_FAST_LOAD_FAST | 1,364,435 | 5.3% |
| COPY | 924,279 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 791,180 | 3.1% |
| LOAD_DEREF | 367,944 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,181,652 | 16.4% |
| POP_JUMP_IF_NONE | 3,035,562 | 11.9% |
| RETURN_VALUE | 2,691,048 | 10.5% |
| LOAD_ATTR_METHOD_NO_DICT | 2,415,681 | 9.5% |
| TO_BOOL_BOOL | 2,248,766 | 8.8% |


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
| LOAD_ATTR_INSTANCE_VALUE | 2,415,681 | 53.8% |
| LOAD_FAST | 1,178,793 | 26.2% |
| BINARY_SLICE | 251,960 | 5.6% |
| LOAD_CONST | 132,180 | 2.9% |
| STORE_FAST_LOAD_FAST | 108,640 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,886,306 | 42.0% |
| LOAD_CONST | 813,215 | 18.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 662,510 | 14.8% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 227,960 | 5.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 204,040 | 4.5% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,049,544 | 68.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,743,482 | 19.8% |
| LOAD_ATTR_SLOT | 588,808 | 6.7% |
| LOAD_DEREF | 122,848 | 1.4% |
| LOAD_FAST_LOAD_FAST | 107,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,461,311 | 50.6% |
| LOAD_FAST | 2,833,363 | 32.1% |
| LOAD_FAST_LOAD_FAST | 675,008 | 7.7% |
| LOAD_CONST | 431,980 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 143,180 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,097,238 | 99.5% |
| LOAD_ATTR_MODULE | 11,960 | 0.4% |
| LOAD_ATTR | 2,940 | 0.1% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,681,366 | 54.0% |
| LOAD_ATTR_CLASS | 454,048 | 14.6% |
| CALL_ISINSTANCE | 298,800 | 9.6% |
| LOAD_GLOBAL_MODULE | 143,800 | 4.6% |
| LOAD_ATTR | 132,880 | 4.3% |


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
| LOAD_FAST | 3,342,684 | 95.5% |
| BINARY_SUBSCR_TUPLE_INT | 120,040 | 3.4% |
| BINARY_SUBSCR_LIST_INT | 21,036 | 0.6% |
| LOAD_DEREF | 11,960 | 0.3% |
| LOAD_ATTR_SLOT | 5,519 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 855,656 | 24.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 588,808 | 16.8% |
| BUILD_LIST | 379,409 | 10.8% |
| LIST_EXTEND | 379,409 | 10.8% |
| LOAD_FAST | 348,802 | 10.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,671 | 99.9% |
| LOAD_ATTR | 660 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 303 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 335,900 | 43.9% |
| LOAD_CONST | 95,960 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,758 | 10.8% |
| LOAD_ATTR_METHOD_NO_DICT | 59,960 | 7.8% |
| RETURN_VALUE | 35,980 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,792,760 | 40.1% |
| LOAD_FAST | 797,440 | 11.4% |
| POP_JUMP_IF_FALSE | 640,675 | 9.2% |
| STORE_FAST | 483,594 | 6.9% |
| POP_JUMP_IF_TRUE | 449,420 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,155,472 | 74.0% |
| CALL_ISINSTANCE | 437,120 | 6.3% |
| LOAD_DEREF | 401,228 | 5.8% |
| CHECK_EXC_MATCH | 390,942 | 5.6% |
| BUILD_TUPLE | 156,660 | 2.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,270,175 | 21.1% |
| RESUME_CHECK | 1,968,007 | 18.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,043,920 | 9.7% |
| POP_JUMP_IF_FALSE | 1,008,344 | 9.4% |
| STORE_ATTR_INSTANCE_VALUE | 785,212 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,097,238 | 28.7% |
| LOAD_FAST | 2,277,720 | 21.1% |
| CALL_ISINSTANCE | 1,131,305 | 10.5% |
| LOAD_FAST_LOAD_FAST | 1,093,580 | 10.1% |
| CALL | 590,005 | 5.5% |


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
| CALL_PY_EXACT_ARGS | 10,306,468 | 52.5% |
| CACHE | 5,375,746 | 27.4% |
| COPY_FREE_VARS | 731,976 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 556,582 | 2.8% |
| BINARY_SUBSCR_GETITEM | 492,660 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,389,514 | 58.0% |
| LOAD_GLOBAL_BUILTIN | 2,792,760 | 14.2% |
| LOAD_GLOBAL_MODULE | 1,968,007 | 10.0% |
| NOP | 1,248,044 | 6.4% |
| LOAD_CONST | 651,888 | 3.3% |


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
| LOAD_FAST | 4,998,494 | 61.1% |
| LOAD_FAST_LOAD_FAST | 1,992,575 | 24.4% |
| SWAP | 924,279 | 11.3% |
| LOAD_DEREF | 155,680 | 1.9% |
| STORE_FAST_LOAD_FAST | 83,920 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,813,442 | 34.4% |
| LOAD_CONST | 1,672,960 | 20.5% |
| LOAD_FAST_LOAD_FAST | 997,280 | 12.2% |
| LOAD_GLOBAL_MODULE | 785,212 | 9.6% |
| RETURN_CONST | 760,470 | 9.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,799,598 | 49.8% |
| LOAD_FAST_LOAD_FAST | 1,797,172 | 49.8% |
| STORE_ATTR_SLOT | 12,934 | 0.4% |
| STORE_ATTR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,303,524 | 36.1% |
| LOAD_CONST | 1,047,516 | 29.0% |
| LOAD_FAST | 618,180 | 17.1% |
| RETURN_CONST | 613,028 | 17.0% |
| ENTER_EXECUTOR | 14,562 | 0.4% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,877 | 79.4% |
| LOAD_FAST_LOAD_FAST | 11,960 | 20.3% |
| STORE_ATTR_INSTANCE_VALUE | 101 | 0.2% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,920 | 81.2% |
| RETURN_CONST | 10,998 | 18.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 2,248,766 | 25.5% |
| RETURN_VALUE | 1,887,088 | 21.4% |
| CALL_ISINSTANCE | 1,880,245 | 21.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 984,100 | 11.2% |
| LOAD_FAST | 402,250 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,394,031 | 72.5% |
| POP_JUMP_IF_TRUE | 2,298,896 | 26.1% |
| EXTENDED_ARG | 119,920 | 1.4% |
| UNARY_NOT | 11,980 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 324,660 | 37.6% |
| BINARY_OP | 321,322 | 37.2% |
| COPY | 205,039 | 23.7% |
| LOAD_ATTR | 11,960 | 1.4% |
| TO_BOOL | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 602,203 | 69.7% |
| POP_JUMP_IF_TRUE | 261,592 | 30.3% |
| TO_BOOL_NONE | 106 | 0.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 145,131 | 99.0% |
| LOAD_FAST | 720 | 0.5% |
| STORE_FAST_LOAD_FAST | 540 | 0.4% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 145,611 | 99.3% |
| POP_JUMP_IF_TRUE | 940 | 0.6% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 855,656 | 60.3% |
| COPY | 190,718 | 13.4% |
| LOAD_FAST | 189,678 | 13.4% |
| LOAD_ATTR | 83,800 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 72,040 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,214,203 | 85.6% |
| POP_JUMP_IF_TRUE | 203,844 | 14.4% |
| TO_BOOL | 190 | 0.0% |
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
| BINARY_SUBSCR | 263,880 | 31.4% |
| RETURN_VALUE | 156,480 | 18.6% |
| FOR_ITER | 108,140 | 12.8% |
| YIELD_VALUE | 107,960 | 12.8% |
| STORE_FAST | 88,201 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 829,314 | 98.5% |
| LOAD_FAST | 12,040 | 1.4% |
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
|     deferred | 1,199,807 | 33.3% |
|          hit | 2,388,917 | 66.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 960 | 10.7% |
| Failure | 8,019 | 89.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,590 | 44.8% |
| add other | 1,420 | 17.7% |
| or | 1,246 | 15.5% |
| remainder | 880 | 11.0% |
| add different types | 480 | 6.0% |
| floor divide | 180 | 2.2% |
| true divide other | 140 | 1.7% |
| multiply different types | 83 | 1.0% |


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
|     deferred | 422,680 | 18.9% |
|          hit | 1,811,177 | 80.9% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 26.8% |
| Failure | 2,780 | 73.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 2,460 | 88.5% |
| other | 160 | 5.8% |
| out of range | 160 | 5.8% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,196,760 | 21.7% |
|          hit | 22,005,367 | 76.9% |
|         miss | 364,109 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,441 | 41.4% |
| Failure | 31,778 | 58.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 6,302 | 19.8% |
| class no vectorcall | 5,460 | 17.2% |
| meth descr method fastcall keywords | 3,860 | 12.1% |
| cfunc noargs | 3,468 | 10.9% |
| meth descr varargs | 3,026 | 9.5% |
| cfunc varargs keywords | 2,260 | 7.1% |
| other | 1,722 | 5.4% |
| class mutable | 1,460 | 4.6% |
| meth descr varargs keywords | 1,300 | 4.1% |
| no dict | 820 | 2.6% |
| init not simple | 680 | 2.1% |
| cfunc varargs | 560 | 1.8% |
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
|     deferred | 181,203 | 4.2% |
|          hit | 4,125,873 | 95.7% |
|         miss | 1,124 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,968 | 50.4% |
| Failure | 1,934 | 49.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 480 | 24.8% |
| bytes | 360 | 18.6% |
| other | 340 | 17.6% |
| float long | 314 | 16.2% |
| tuple | 180 | 9.3% |
| big int | 160 | 8.3% |
| baseobject | 60 | 3.1% |
| bool | 40 | 2.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 353,915 | 30.1% |
|          hit | 818,120 | 69.6% |

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
|     deferred | 6,075,057 | 11.3% |
|          hit | 46,995,975 | 87.7% |
|         miss | 454,036 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,340 | 49.5% |
| Failure | 38,073 | 50.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 8,260 | 21.7% |
| method | 8,195 | 21.5% |
| not managed dict | 7,178 | 18.9% |
| not in keys | 6,880 | 18.1% |
| shadowed | 1,880 | 4.9% |
| module attr not found | 1,600 | 4.2% |
| non overriding descriptor | 1,220 | 3.2% |
| metaclass attribute | 920 | 2.4% |
| non object slot | 560 | 1.5% |
| class attr descriptor | 540 | 1.4% |
| class method obj | 460 | 1.2% |
| overridden | 180 | 0.5% |
| builtin class method | 160 | 0.4% |
| mutable class | 40 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 15,440 | 0.1% |
|        deopt | 980 | 0.0% |
|          hit | 17,743,482 | 99.8% |
|         miss | 6,500 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 14,220 | 100.0% |
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
|     deferred | 263,625 | 2.2% |
|          hit | 11,140,988 | 91.8% |
|         miss | 702,702 | 5.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 21,115 | 83.8% |
| Failure | 4,080 | 16.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,660 | 40.7% |
| not in keys | 640 | 15.7% |
| method | 480 | 11.8% |
| property | 480 | 11.8% |
| not in dict | 480 | 11.8% |
| not managed dict | 240 | 5.9% |
| overridden | 100 | 2.5% |


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
|     deferred | 1,367,130 | 10.5% |
|          hit | 11,557,258 | 89.1% |
|         miss | 34,338 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,885 | 56.2% |
| Failure | 6,150 | 43.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 1,920 | 31.2% |
| bytes | 1,124 | 18.3% |
| float | 960 | 15.6% |
| dict | 620 | 10.1% |
| mapping | 566 | 9.2% |
| bytearray | 420 | 6.8% |
| tuple | 360 | 5.9% |
| set | 180 | 2.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,920 | 1.2% |
|          hit | 1,045,954 | 98.7% |

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
| Basic | 181,232,136 | 49.5% |
| Not specialized | 42,976,418 | 11.7% |
| Specialized hits | 140,260,952 | 38.3% |
| Specialized misses | 1,564,105 | 0.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,196,760 | 37.2% |
| LOAD_ATTR | 6,075,057 | 36.5% |
| TO_BOOL | 1,367,130 | 8.2% |
| BINARY_OP | 1,199,807 | 7.2% |
| BINARY_SUBSCR | 422,680 | 2.5% |
| FOR_ITER | 353,915 | 2.1% |
| SEND | 336,200 | 2.0% |
| STORE_ATTR | 263,625 | 1.6% |
| STORE_SUBSCR | 240,780 | 1.4% |
| COMPARE_OP | 181,203 | 1.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 691,079 | 44.2% |
| LOAD_ATTR_SLOT | 295,153 | 18.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 136,493 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 124,901 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,482 | 5.3% |
| CALL_PY_EXACT_ARGS | 65,635 | 4.2% |
| CALL_METHOD_DESCRIPTOR_O | 36,840 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 28,312 | 1.8% |
| TO_BOOL_NONE | 22,026 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 19,449 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 5,737,042 | 28.7% |
| Calls to Python functions inlined | 14,222,062 | 71.3% |
| Calls via PyEval_EvalFrame (total) | 5,737,042 | 28.7% |
| Calls via PyEval_EvalFrame (vector) | 5,386,462 | 27.0% |
| Calls via PyEval_EvalFrame (generator) | 350,580 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 5,386,162 | 27.0% |
| Calls via PyEval_EvalFrame (build class) | 220 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 1,095,117 | 5.5% |
| Calls via PyEval_EvalFrame (function ex) | 132,520 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 206,300 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 915,408 | 4.6% |
| Frame objects created | 824,341 | 4.1% |
| Frames pushed | 13,465,926 | 67.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,849,886 | 40.0% |
| Frees to freelist | 11,904,037 |  |
| Allocations | 17,746,185 | 60.0% |
| Allocations to 512 bytes | 17,422,495 | 58.9% |
| Allocations to 4 kbytes | 90,874 | 0.3% |
| Allocations over 4 kbytes | 232,816 | 0.8% |
| Frees | 18,009,715 |  |
| New values | 158,420 |  |
| Interpreter increfs | 187,653,930 | 77.4% |
| Interpreter decrefs | 202,534,811 | 75.0% |
| Increfs | 54,738,582 | 22.6% |
| Decrefs | 67,667,241 | 25.0% |
| Materialize dict (on request) | 200 | 0.1% |
| Materialize dict (new key) | 24,000 | 15.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 140 | 0.1% |
| Method cache hits | 10,297,734 |  |
| Method cache misses | 425,334 |  |
| Method cache collisions | 497,665 |  |
| Method cache dunder hits | 6,810,626 |  |
| Method cache dunder misses | 77,062 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 1,242 | 1,920 | 13,233,886 |
| 1 | 122 | 0 | 4,494,472 |
| 2 | 2 | 66 | 624,288 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,780 |  |
| Traces created | 680 | 38.2% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 20 | 1.1% |
| Trace too short | 1,100 | 61.8% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 1,255,639 |  |
| Uops executed | 39,244,904 | 31.25 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 80 | 11.8% |
| <= 32 | 400 | 58.8% |
| <= 64 | 120 | 17.6% |
| <= 128 | 80 | 11.8% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 2.9% |
| <= 16 | 240 | 35.3% |
| <= 32 | 260 | 38.2% |
| <= 64 | 120 | 17.6% |
| <= 128 | 40 | 5.9% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 40 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 237,423 | 18.9% |
| <= 16 | 368,422 | 29.3% |
| <= 32 | 170,166 | 13.6% |
| <= 64 | 403,045 | 32.1% |
| <= 128 | 73,952 | 5.9% |
| <= 256 | 365 | 0.0% |
| <= 512 | 854 | 0.1% |
| <= 1,024 | 1,065 | 0.1% |
| <= 2,048 | 269 | 0.0% |
| <= 4,096 | 24 | 0.0% |
| <= 8,192 | 14 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 9,863,966 | 25.1% | 25.1% |  |
| LOAD_FAST | 3,507,384 | 8.9% | 34.1% |  |
| _GUARD_TYPE_VERSION | 3,278,055 | 8.4% | 42.4% |  |
| _POP_JUMP_IF_TRUE | 2,407,479 | 6.1% | 48.6% |  |
| STORE_FAST | 1,523,644 | 3.9% | 52.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,276,003 | 3.3% | 55.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,276,003 | 3.3% | 58.9% |  |
| _EXIT_TRACE | 1,242,259 | 3.2% | 62.1% |  |
| TO_BOOL_BOOL | 1,025,310 | 2.6% | 64.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 958,987 | 2.4% | 67.2% |  |
| _LOAD_ATTR_SLOT | 803,495 | 2.0% | 69.2% |  |
| _GUARD_GLOBALS_VERSION | 673,377 | 1.7% | 70.9% | 0.2% |
| LOAD_CONST | 649,517 | 1.7% | 72.6% |  |
| _ITER_CHECK_LIST | 647,475 | 1.6% | 74.2% | 0.0% |
| _IS_ITER_EXHAUSTED_LIST | 647,435 | 1.6% | 75.9% |  |
| _CHECK_PEP_523 | 517,373 | 1.3% | 77.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 517,373 | 1.3% | 78.5% |  |
| _CHECK_STACK_SPACE | 517,373 | 1.3% | 79.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 517,373 | 1.3% | 81.2% |  |
| _PUSH_FRAME | 517,373 | 1.3% | 82.5% |  |
| _SAVE_RETURN_OFFSET | 517,373 | 1.3% | 83.8% |  |
| RESUME_CHECK | 486,656 | 1.2% | 85.0% |  |
| _ITER_CHECK_RANGE | 462,369 | 1.2% | 86.2% |  |
| _IS_ITER_EXHAUSTED_RANGE | 462,369 | 1.2% | 87.4% |  |
| _GUARD_BUILTINS_VERSION | 442,640 | 1.1% | 88.5% |  |
| _LOAD_GLOBAL_BUILTINS | 442,640 | 1.1% | 89.6% |  |
| _ITER_NEXT_RANGE | 434,734 | 1.1% | 90.8% |  |
| _ITER_NEXT_LIST | 415,645 | 1.1% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 363,554 | 0.9% | 92.7% |  |
| POP_TOP | 273,805 | 0.7% | 93.4% |  |
| _LOAD_GLOBAL_MODULE | 229,397 | 0.6% | 94.0% |  |
| _JUMP_TO_TOP | 205,109 | 0.5% | 94.5% |  |
| _POP_JUMP_IF_FALSE | 179,584 | 0.5% | 95.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 177,039 | 0.5% | 95.5% |  |
| _GUARD_KEYS_VERSION | 177,039 | 0.5% | 95.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 165,359 | 0.4% | 96.3% |  |
| CALL_ISINSTANCE | 143,220 | 0.4% | 96.7% |  |
| CONTAINS_OP | 108,440 | 0.3% | 97.0% |  |
| CALL_LEN | 107,660 | 0.3% | 97.2% |  |
| _IS_NONE | 87,684 | 0.2% | 97.5% |  |
| TO_BOOL_INT | 83,680 | 0.2% | 97.7% |  |
| _ITER_CHECK_TUPLE | 63,700 | 0.2% | 97.8% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 63,700 | 0.2% | 98.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 63,289 | 0.2% | 98.2% |  |
| _ITER_NEXT_TUPLE | 49,860 | 0.1% | 98.3% |  |
| CALL_BUILTIN_FAST | 48,540 | 0.1% | 98.4% |  |
| COMPARE_OP_INT | 47,920 | 0.1% | 98.5% |  |
| BUILD_TUPLE | 47,820 | 0.1% | 98.7% |  |
| TO_BOOL_NONE | 47,740 | 0.1% | 98.8% | 25.0% |
| COPY | 47,085 | 0.1% | 98.9% |  |
| SWAP | 47,085 | 0.1% | 99.0% |  |
| _STORE_ATTR_SLOT | 39,106 | 0.1% | 99.1% |  |
| LOAD_DEREF | 35,000 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_LIST_INT | 34,731 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 32,145 | 0.1% | 99.4% |  |
| _CHECK_ATTR_MODULE | 24,897 | 0.1% | 99.4% |  |
| _LOAD_ATTR_MODULE | 24,897 | 0.1% | 99.5% |  |
| _GUARD_BOTH_INT | 23,445 | 0.1% | 99.6% |  |
| _GUARD_DORV_VALUES | 23,425 | 0.1% | 99.6% |  |
| _STORE_ATTR_INSTANCE_VALUE | 23,425 | 0.1% | 99.7% |  |
| PUSH_NULL | 23,385 | 0.1% | 99.7% |  |
| TO_BOOL_LIST | 23,245 | 0.1% | 99.8% |  |
| CALL_BUILTIN_O | 23,145 | 0.1% | 99.9% |  |
| _BINARY_OP_SUBTRACT_INT | 23,145 | 0.1% | 99.9% |  |
| _POP_FRAME | 11,960 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,680 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 1,752 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 1,752 | 0.0% | 100.0% |  |
| IS_OP | 660 | 0.0% | 100.0% |  |
| LIST_APPEND | 660 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 660 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 300 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 240 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 220 | 0.0% | 100.0% | 27.3% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 220 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 220 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 160 | 0.0% | 100.0% |  |
| GET_ITER | 40 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 40 | 0.0% | 100.0% |  |
| STORE_DEREF | 40 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 620 |
| FOR_ITER_GEN | 480 |
| CALL | 140 |
| LOAD_ATTR | 100 |
| CALL_LIST_APPEND | 47 |
| TO_BOOL | 40 |
| YIELD_VALUE | 40 |
| BINARY_OP | 20 |
| CALL_KW | 20 |
| COMPARE_OP | 20 |
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
Stats gathered on: 2023-11-03
