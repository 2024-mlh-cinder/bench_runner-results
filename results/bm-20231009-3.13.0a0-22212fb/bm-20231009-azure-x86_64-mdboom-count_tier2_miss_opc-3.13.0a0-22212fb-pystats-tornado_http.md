
# Pystats results

- benchmark: tornado_http
- fork: mdboom
- ref: count-tier2-miss-opcodes
- commit hash: 22212fb
- commit date: 2023-10-09T12:01:25-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 59,300,215 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 20,082,971 | 7.0% | 27.8% | 0.1% |
| RESUME_CHECK | 15,074,841 | 5.3% | 33.0% | 0.0% |
| LOAD_CONST | 12,702,673 | 4.4% | 37.5% |  |
| POP_JUMP_IF_FALSE | 11,423,677 | 4.0% | 41.5% |  |
| STORE_FAST | 9,325,628 | 3.3% | 44.7% |  |
| RETURN_VALUE | 8,672,192 | 3.0% | 47.8% |  |
| CALL_PY_EXACT_ARGS | 8,649,152 | 3.0% | 50.8% | 0.5% |
| LOAD_GLOBAL_MODULE | 8,229,241 | 2.9% | 53.7% | 0.0% |
| LOAD_FAST_LOAD_FAST | 7,758,638 | 2.7% | 56.4% |  |
| POP_TOP | 7,650,239 | 2.7% | 59.1% |  |
| TO_BOOL_BOOL | 7,374,333 | 2.6% | 61.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,740,595 | 2.4% | 64.0% | 0.9% |
| STORE_ATTR_INSTANCE_VALUE | 6,146,578 | 2.1% | 66.1% | 0.1% |
| RETURN_CONST | 5,915,343 | 2.1% | 68.2% |  |
| LOAD_GLOBAL_BUILTIN | 5,544,157 | 1.9% | 70.1% | 0.0% |
| CALL | 4,722,599 | 1.7% | 71.8% |  |
| LOAD_ATTR | 4,545,024 | 1.6% | 73.4% |  |
| INTERPRETER_EXIT | 4,280,206 | 1.5% | 74.9% |  |
| POP_JUMP_IF_NONE | 4,123,181 | 1.4% | 76.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,079,114 | 1.4% | 77.8% | 0.5% |
| POP_JUMP_IF_TRUE | 3,339,946 | 1.2% | 78.9% |  |
| LOAD_ATTR_SLOT | 3,226,655 | 1.1% | 80.0% | 6.9% |
| STORE_ATTR_SLOT | 2,733,827 | 1.0% | 81.0% | 18.9% |
| PUSH_NULL | 2,696,267 | 0.9% | 81.9% |  |
| COMPARE_OP_INT | 2,655,479 | 0.9% | 82.9% | 0.0% |
| NOP | 2,654,712 | 0.9% | 83.8% |  |
| LOAD_ATTR_MODULE | 2,349,537 | 0.8% | 84.6% |  |
| COPY | 1,862,126 | 0.7% | 85.3% |  |
| CALL_ISINSTANCE | 1,667,142 | 0.6% | 85.9% |  |
| LOAD_DEREF | 1,587,041 | 0.6% | 86.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,554,540 | 0.5% | 87.0% | 6.0% |
| JUMP_BACKWARD | 1,378,177 | 0.5% | 87.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,292,438 | 0.5% | 87.9% |  |
| CALL_BUILTIN_FAST | 1,276,080 | 0.4% | 88.3% |  |
| SWAP | 1,091,794 | 0.4% | 88.7% |  |
| TO_BOOL_NONE | 1,089,987 | 0.4% | 89.1% | 1.8% |
| BUILD_TUPLE | 1,077,838 | 0.4% | 89.5% |  |
| TO_BOOL | 1,021,487 | 0.4% | 89.8% |  |
| BUILD_LIST | 934,263 | 0.3% | 90.2% |  |
| BINARY_OP | 896,848 | 0.3% | 90.5% |  |
| STORE_FAST_STORE_FAST | 856,846 | 0.3% | 90.8% |  |
| CALL_LEN | 831,951 | 0.3% | 91.1% |  |
| BINARY_OP_ADD_INT | 812,090 | 0.3% | 91.3% |  |
| CALL_FUNCTION_EX | 807,431 | 0.3% | 91.6% |  |
| FOR_ITER_LIST | 799,430 | 0.3% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 792,471 | 0.3% | 92.2% | 3.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 740,620 | 0.3% | 92.4% |  |
| TO_BOOL_INT | 707,958 | 0.2% | 92.7% | 0.6% |
| BINARY_SUBSCR_DICT | 676,666 | 0.2% | 92.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 676,546 | 0.2% | 93.2% |  |
| CONTAINS_OP | 676,320 | 0.2% | 93.4% |  |
| BINARY_OP_SUBTRACT_INT | 645,544 | 0.2% | 93.6% |  |
| JUMP_FORWARD | 622,818 | 0.2% | 93.8% |  |
| BUILD_MAP | 593,580 | 0.2% | 94.1% |  |
| GET_ITER | 588,823 | 0.2% | 94.3% |  |
| COPY_FREE_VARS | 581,468 | 0.2% | 94.5% |  |
| LOAD_ATTR_WITH_HINT | 575,646 | 0.2% | 94.7% | 2.2% |
| LOAD_ATTR_CLASS | 550,200 | 0.2% | 94.9% | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 534,492 | 0.2% | 95.0% |  |
| LIST_EXTEND | 507,381 | 0.2% | 95.2% |  |
| CALL_INTRINSIC_1 | 498,381 | 0.2% | 95.4% |  |
| YIELD_VALUE | 432,000 | 0.2% | 95.5% |  |
| CALL_PY_WITH_DEFAULTS | 426,350 | 0.1% | 95.7% |  |
| IS_OP | 423,720 | 0.1% | 95.8% |  |
| STORE_SUBSCR_DICT | 423,360 | 0.1% | 96.0% |  |
| BINARY_SLICE | 414,660 | 0.1% | 96.1% |  |
| FOR_ITER_RANGE | 369,259 | 0.1% | 96.3% |  |
| BINARY_SUBSCR_GETITEM | 369,180 | 0.1% | 96.4% |  |
| DICT_MERGE | 359,220 | 0.1% | 96.5% |  |
| CALL_KW | 345,110 | 0.1% | 96.6% |  |
| GET_AWAITABLE | 342,000 | 0.1% | 96.8% |  |
| POP_EXCEPT | 338,670 | 0.1% | 96.9% |  |
| PUSH_EXC_INFO | 338,670 | 0.1% | 97.0% |  |
| END_SEND | 333,000 | 0.1% | 97.1% |  |
| CHECK_EXC_MATCH | 331,104 | 0.1% | 97.2% |  |
| BINARY_SUBSCR | 316,008 | 0.1% | 97.3% |  |
| MAKE_CELL | 303,363 | 0.1% | 97.4% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 288,240 | 0.1% | 97.5% | 3.1% |
| MAKE_FUNCTION | 271,477 | 0.1% | 97.6% |  |
| COMPARE_OP_FLOAT | 268,653 | 0.1% | 97.7% |  |
| FOR_ITER | 263,831 | 0.1% | 97.8% |  |
| SEND | 252,400 | 0.1% | 97.9% |  |
| RETURN_GENERATOR | 252,060 | 0.1% | 98.0% |  |
| EXIT_INIT_CHECK | 243,240 | 0.1% | 98.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 243,240 | 0.1% | 98.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 220,399 | 0.1% | 98.3% | 45.7% |
| TO_BOOL_STR | 216,740 | 0.1% | 98.3% | 3.5% |
| SEND_GEN | 216,000 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 207,420 | 0.1% | 98.5% |  |
| FOR_ITER_GEN | 207,000 | 0.1% | 98.5% |  |
| STORE_ATTR | 200,380 | 0.1% | 98.6% |  |
| CALL_LIST_APPEND | 191,195 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 180,580 | 0.1% | 98.7% |  |
| BEFORE_WITH | 173,750 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 171,360 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 171,060 | 0.1% | 98.9% |  |
| STORE_FAST_LOAD_FAST | 162,000 | 0.1% | 99.0% |  |
| SET_FUNCTION_ATTRIBUTE | 156,378 | 0.1% | 99.0% |  |
| DELETE_FAST | 155,690 | 0.1% | 99.1% |  |
| EXTENDED_ARG | 153,180 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 153,180 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 143,820 | 0.1% | 99.3% |  |
| COMPARE_OP | 133,317 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 127,589 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 126,000 | 0.0% | 99.4% |  |
| FOR_ITER_TUPLE | 108,660 | 0.0% | 99.4% |  |
| CALL_BUILTIN_CLASS | 103,858 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 91,632 | 0.0% | 99.5% |  |
| STORE_DEREF | 90,360 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 90,060 | 0.0% | 99.6% |  |
| LOAD_SUPER_ATTR_ATTR | 90,060 | 0.0% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 90,000 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 90,000 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 83,671 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 81,120 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 72,000 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 69,871 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 63,180 | 0.0% | 99.8% |  |
| CALL_BUILTIN_O | 59,405 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 54,060 | 0.0% | 99.8% |  |
| BUILD_SLICE | 54,000 | 0.0% | 99.8% |  |
| RERAISE | 54,000 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 45,120 | 0.0% | 99.9% |  |
| UNARY_INVERT | 45,120 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 45,120 | 0.0% | 99.9% |  |
| END_FOR | 45,000 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 44,882 | 0.0% | 99.9% | 9.4% |
| TO_BOOL_ALWAYS_TRUE | 36,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 19,841 | 0.0% | 100.0% |  |
| BUILD_STRING | 18,060 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 18,000 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 18,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 10,036 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 9,060 | 0.0% | 100.0% |  |
| UNARY_NOT | 9,000 | 0.0% | 100.0% |  |
| BUILD_SET | 9,000 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 9,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,312 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| IMPORT_FROM | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,477,651 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 8,589,242 | 3.0% | 9.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,112,234 | 2.8% | 12.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,289,456 | 2.2% | 14.2% |
| STORE_FAST LOAD_FAST | 5,949,259 | 2.1% | 16.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,514,802 | 1.9% | 18.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,606,169 | 1.6% | 19.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,082,584 | 1.4% | 21.2% |
| LOAD_CONST LOAD_FAST | 4,029,415 | 1.4% | 22.6% |
| CACHE RESUME_CHECK | 4,024,644 | 1.4% | 24.0% |
| RETURN_CONST POP_TOP | 3,909,079 | 1.4% | 25.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,750,214 | 1.3% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 3,418,260 | 1.2% | 27.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,373,886 | 1.2% | 29.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,178,499 | 1.1% | 30.2% |
| LOAD_FAST LOAD_ATTR_SLOT | 3,089,175 | 1.1% | 31.3% |
| POP_TOP LOAD_FAST | 2,938,854 | 1.0% | 32.3% |
| LOAD_FAST LOAD_ATTR | 2,820,639 | 1.0% | 33.3% |
| RETURN_VALUE INTERPRETER_EXIT | 2,795,463 | 1.0% | 34.3% |
| LOAD_FAST LOAD_CONST | 2,594,220 | 0.9% | 35.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,593,718 | 0.9% | 36.1% |
| LOAD_FAST RETURN_VALUE | 2,374,354 | 0.8% | 36.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,339,941 | 0.8% | 37.7% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 2,276,178 | 0.8% | 38.5% |
| POP_TOP RETURN_CONST | 2,212,895 | 0.8% | 39.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,133,960 | 0.7% | 40.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,128,220 | 0.7% | 40.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,109,710 | 0.7% | 41.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,106,168 | 0.7% | 42.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,086,074 | 0.7% | 43.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,026,121 | 0.7% | 43.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,994,637 | 0.7% | 44.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,760,531 | 0.6% | 45.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,747,860 | 0.6% | 45.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,730,668 | 0.6% | 46.2% |
| RETURN_VALUE STORE_FAST | 1,598,993 | 0.6% | 46.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,594,781 | 0.6% | 47.3% |
| NOP LOAD_FAST | 1,593,550 | 0.6% | 47.9% |
| CALL STORE_FAST | 1,531,571 | 0.5% | 48.4% |
| LOAD_FAST CALL | 1,531,000 | 0.5% | 49.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,513,822 | 0.5% | 49.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,495,790 | 0.5% | 50.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,471,681 | 0.5% | 50.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,465,300 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,450,646 | 0.5% | 51.5% |
| RETURN_VALUE TO_BOOL_BOOL | 1,422,481 | 0.5% | 52.0% |
| LOAD_FAST STORE_ATTR_SLOT | 1,378,023 | 0.5% | 52.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,355,686 | 0.5% | 53.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,346,084 | 0.5% | 53.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,314,962 | 0.5% | 53.9% |
| PUSH_NULL LOAD_FAST | 1,307,548 | 0.5% | 54.4% |
| LOAD_CONST COMPARE_OP_INT | 1,306,161 | 0.5% | 54.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,279,067 | 0.4% | 55.3% |
| RETURN_CONST INTERPRETER_EXIT | 1,277,683 | 0.4% | 55.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,254,315 | 0.4% | 56.2% |
| RESUME_CHECK NOP | 1,206,116 | 0.4% | 56.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,111,596 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,024,115 | 0.4% | 57.3% |
| LOAD_CONST STORE_FAST | 998,245 | 0.3% | 57.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 976,263 | 0.3% | 58.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 909,803 | 0.3% | 58.4% |
| LOAD_ATTR LOAD_FAST | 901,476 | 0.3% | 58.7% |
| LOAD_CONST LOAD_CONST | 892,451 | 0.3% | 59.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 883,202 | 0.3% | 59.3% |
| LOAD_FAST COPY | 854,754 | 0.3% | 59.6% |
| TO_BOOL POP_JUMP_IF_FALSE | 850,393 | 0.3% | 59.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 838,368 | 0.3% | 60.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 832,478 | 0.3% | 60.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 818,460 | 0.3% | 60.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 797,775 | 0.3% | 61.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 791,900 | 0.3% | 61.3% |
| STORE_ATTR_SLOT LOAD_CONST | 784,762 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 783,260 | 0.3% | 61.9% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 779,115 | 0.3% | 62.1% |
| LOAD_ATTR PUSH_NULL | 771,403 | 0.3% | 62.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 769,222 | 0.3% | 62.7% |
| BUILD_LIST LOAD_FAST | 768,561 | 0.3% | 62.9% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 756,180 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 751,324 | 0.3% | 63.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 748,140 | 0.3% | 63.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 738,260 | 0.3% | 64.0% |
| CALL POP_TOP | 737,941 | 0.3% | 64.2% |
| RETURN_VALUE RETURN_VALUE | 729,180 | 0.3% | 64.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 724,075 | 0.3% | 64.8% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 710,574 | 0.2% | 65.0% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 710,574 | 0.2% | 65.3% |
| POP_TOP JUMP_BACKWARD | 690,792 | 0.2% | 65.5% |
| POP_TOP LOAD_CONST | 685,103 | 0.2% | 65.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 675,360 | 0.2% | 66.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 667,426 | 0.2% | 66.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 667,080 | 0.2% | 66.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 662,181 | 0.2% | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 651,770 | 0.2% | 66.9% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 641,122 | 0.2% | 67.1% |
| LOAD_FAST CALL_BUILTIN_FAST | 628,560 | 0.2% | 67.3% |
| CALL LOAD_FAST | 627,135 | 0.2% | 67.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 620,871 | 0.2% | 67.8% |
| CALL_BUILTIN_FAST STORE_FAST | 611,220 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 607,439 | 0.2% | 68.2% |
| STORE_FAST LOAD_CONST | 598,459 | 0.2% | 68.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 234,000 | 56.4% |
| LOAD_CONST | 144,480 | 34.8% |
| LOAD_FAST | 36,180 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 189,040 | 45.6% |
| STORE_FAST | 99,060 | 23.9% |
| CALL_PY_EXACT_ARGS | 45,000 | 10.9% |
| GET_ITER | 27,180 | 6.6% |
| RETURN_VALUE | 18,000 | 4.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,024,644 | 93.8% |
| COPY_FREE_VARS | 174,502 | 4.1% |
| POP_TOP | 72,060 | 1.7% |
| RETURN_GENERATOR | 9,000 | 0.2% |
| MAKE_CELL | 9,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 83,630 | 48.1% |
| RETURN_VALUE | 81,000 | 46.6% |
| LOAD_GLOBAL_MODULE | 9,120 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 173,750 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 315,368 | 99.8% |
| BINARY_SUBSCR | 640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 198,000 | 62.7% |
| LOAD_FAST | 45,000 | 14.2% |
| CONVERT_VALUE | 18,000 | 5.7% |
| BINARY_SUBSCR_LIST_INT | 9,156 | 2.9% |
| CALL_LEN | 9,060 | 2.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 292,414 | 88.3% |
| BUILD_TUPLE | 18,060 | 5.5% |
| LOAD_ATTR_MODULE | 11,630 | 3.5% |
| LOAD_GLOBAL_MODULE | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 331,104 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 54,000 | 60.0% |
| LOAD_FAST | 36,060 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 54,000 | 60.0% |
| RETURN_CONST | 27,060 | 30.0% |
| LOAD_FAST | 9,000 | 10.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 45,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 45,000 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 207,000 | 62.2% |
| RETURN_CONST | 99,000 | 29.7% |
| RETURN_VALUE | 27,000 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 216,000 | 64.9% |
| POP_TOP | 108,000 | 32.4% |
| UNPACK_SEQUENCE_TUPLE | 9,000 | 2.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 243,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 243,240 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 45,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,120 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,575 | 41.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 108,180 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,270 | 12.3% |
| LOAD_ATTR | 54,000 | 9.2% |
| BINARY_SLICE | 27,180 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 303,414 | 51.5% |
| FOR_ITER | 109,791 | 18.6% |
| FOR_ITER_TUPLE | 54,180 | 9.2% |
| CALL_PY_EXACT_ARGS | 54,000 | 9.2% |
| LOAD_FAST_AND_CLEAR | 36,060 | 6.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,795,463 | 65.3% |
| RETURN_CONST | 1,277,683 | 29.9% |
| YIELD_VALUE | 189,000 | 4.4% |
| RETURN_GENERATOR | 18,060 | 0.4% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 271,477 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 118,417 | 43.6% |
| CALL | 90,000 | 33.2% |
| LOAD_FAST | 36,000 | 13.3% |
| CALL_PY_EXACT_ARGS | 18,000 | 6.6% |
| STORE_DEREF | 9,000 | 3.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,206,116 | 45.4% |
| POP_JUMP_IF_FALSE | 345,027 | 13.0% |
| STORE_FAST | 334,167 | 12.6% |
| STORE_ATTR_INSTANCE_VALUE | 271,781 | 10.2% |
| POP_JUMP_IF_TRUE | 206,276 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,593,550 | 60.0% |
| LOAD_GLOBAL_MODULE | 442,100 | 16.7% |
| LOAD_FAST_LOAD_FAST | 225,000 | 8.5% |
| LOAD_DEREF | 109,606 | 4.1% |
| NOP | 91,434 | 3.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 245,980 | 72.6% |
| SWAP | 45,000 | 13.3% |
| COPY | 27,000 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 9,060 | 2.7% |
| STORE_SUBSCR_DICT | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 217,554 | 64.2% |
| RETURN_VALUE | 45,000 | 13.3% |
| RERAISE | 27,000 | 8.0% |
| DELETE_FAST | 18,000 | 5.3% |
| JUMP_BACKWARD | 11,630 | 3.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,909,079 | 51.1% |
| CALL | 737,941 | 9.6% |
| CALL_METHOD_DESCRIPTOR_O | 620,871 | 8.1% |
| POP_JUMP_IF_FALSE | 458,530 | 6.0% |
| CALL_FUNCTION_EX | 374,121 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,938,854 | 38.4% |
| RETURN_CONST | 2,212,895 | 28.9% |
| JUMP_BACKWARD | 690,792 | 9.0% |
| LOAD_CONST | 685,103 | 9.0% |
| RESUME_CHECK | 252,060 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 261,120 | 77.1% |
| RERAISE | 27,000 | 8.0% |
| CALL | 22,064 | 6.5% |
| CALL_METHOD_DESCRIPTOR_O | 18,060 | 5.3% |
| RAISE_VARARGS | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300,040 | 88.6% |
| LOAD_GLOBAL_MODULE | 29,630 | 8.7% |
| LOAD_FAST | 9,000 | 2.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,279,067 | 47.4% |
| LOAD_ATTR | 771,403 | 28.6% |
| LOAD_FAST | 348,377 | 12.9% |
| LOAD_DEREF | 153,240 | 5.7% |
| RETURN_VALUE | 99,060 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,307,548 | 48.5% |
| CALL | 547,211 | 20.3% |
| LOAD_FAST_LOAD_FAST | 533,487 | 19.8% |
| LOAD_GLOBAL_MODULE | 81,100 | 3.0% |
| LOAD_CONST | 71,580 | 2.7% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 198,000 | 78.6% |
| COPY_FREE_VARS | 18,060 | 7.2% |
| CACHE | 9,000 | 3.6% |
| CALL_KW | 9,000 | 3.6% |
| MAKE_CELL | 9,000 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 63,000 | 25.0% |
| RETURN_VALUE | 45,000 | 17.9% |
| GET_AWAITABLE | 45,000 | 17.9% |
| GET_ITER | 27,000 | 10.7% |
| CALL | 27,000 | 10.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,374,354 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,026,121 | 23.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 466,920 | 5.4% |
| CALL | 464,070 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,795,463 | 32.2% |
| STORE_FAST | 1,598,993 | 18.4% |
| TO_BOOL_BOOL | 1,422,481 | 16.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| LOAD_FAST | 452,232 | 5.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,000 | 44.9% |
| LOAD_CONST | 72,060 | 39.9% |
| LOAD_FAST_LOAD_FAST | 27,000 | 15.0% |
| STORE_SUBSCR | 420 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 81,000 | 44.9% |
| LOAD_FAST | 36,060 | 20.0% |
| JUMP_BACKWARD | 27,000 | 15.0% |
| LOAD_CONST | 18,000 | 10.0% |
| LOAD_DEREF | 18,000 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 452,944 | 44.3% |
| LOAD_FAST | 440,795 | 43.2% |
| LOAD_ATTR | 90,144 | 8.8% |
| COPY | 26,420 | 2.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,100 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 850,393 | 83.3% |
| POP_JUMP_IF_TRUE | 168,643 | 16.5% |
| TO_BOOL | 1,537 | 0.2% |
| TO_BOOL_BOOL | 576 | 0.1% |
| TO_BOOL_NONE | 282 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 27,060 | 60.0% |
| BINARY_OP | 18,060 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 45,120 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 9,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 170,760 | 19.0% |
| LOAD_CONST | 127,116 | 14.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 117,000 | 13.0% |
| LOAD_FAST | 84,797 | 9.5% |
| LOAD_ATTR_MODULE | 77,720 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 239,900 | 26.7% |
| STORE_FAST | 163,403 | 18.2% |
| COPY | 131,840 | 14.7% |
| RETURN_VALUE | 72,060 | 8.0% |
| LOAD_FAST | 72,000 | 8.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 9,000 | 99.3% |
| LOAD_FAST | 60 | 0.7% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 286,920 | 30.7% |
| LOAD_ATTR_SLOT | 283,821 | 30.4% |
| STORE_FAST | 83,832 | 9.0% |
| LOAD_FAST_LOAD_FAST | 80,460 | 8.6% |
| RESUME_CHECK | 54,180 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 768,561 | 82.3% |
| STORE_FAST | 102,282 | 10.9% |
| SWAP | 36,060 | 3.9% |
| LOAD_CONST | 18,000 | 1.9% |
| CALL_BUILTIN_CLASS | 9,000 | 1.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 206,640 | 34.8% |
| CALL_INTRINSIC_1 | 115,920 | 19.5% |
| RESUME_CHECK | 72,120 | 12.2% |
| STORE_ATTR_INSTANCE_VALUE | 54,300 | 9.1% |
| BUILD_TUPLE | 54,060 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 485,760 | 81.8% |
| CALL_FUNCTION_EX | 44,400 | 7.5% |
| STORE_FAST | 36,180 | 6.1% |
| RETURN_VALUE | 18,000 | 3.0% |
| LOAD_DEREF | 9,000 | 1.5% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 9,000 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 54,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 54,000 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,000 | 49.8% |
| CALL_PY_EXACT_ARGS | 9,000 | 49.8% |
| STORE_DEREF | 60 | 0.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,342 | 35.5% |
| LOAD_FAST_LOAD_FAST | 288,240 | 26.7% |
| LOAD_GLOBAL_BUILTIN | 153,300 | 14.2% |
| LOAD_GLOBAL_MODULE | 72,180 | 6.7% |
| LOAD_ATTR_MODULE | 54,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 153,300 | 14.2% |
| CALL_METHOD_DESCRIPTOR_O | 144,000 | 13.4% |
| RETURN_VALUE | 135,360 | 12.6% |
| LOAD_CONST | 118,417 | 11.0% |
| CONTAINS_OP | 90,060 | 8.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,531,000 | 32.4% |
| PUSH_NULL | 547,211 | 11.6% |
| LOAD_CONST | 516,175 | 10.9% |
| LOAD_ATTR_INSTANCE_VALUE | 459,160 | 9.7% |
| LOAD_GLOBAL_MODULE | 443,521 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,531,571 | 32.4% |
| POP_TOP | 737,941 | 15.6% |
| LOAD_FAST | 627,135 | 13.3% |
| RETURN_VALUE | 464,070 | 9.8% |
| BINARY_SUBSCR_DICT | 315,060 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 359,220 | 44.5% |
| CALL_INTRINSIC_1 | 329,061 | 40.8% |
| LOAD_FAST | 74,750 | 9.3% |
| BUILD_MAP | 44,400 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 374,121 | 46.3% |
| RETURN_VALUE | 164,090 | 20.3% |
| RESUME_CHECK | 99,060 | 12.3% |
| STORE_FAST | 89,520 | 11.1% |
| CALL | 62,460 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 489,381 | 98.2% |
| RERAISE | 9,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 329,061 | 66.0% |
| BUILD_MAP | 115,920 | 23.3% |
| LOAD_CONST | 44,400 | 8.9% |
| RERAISE | 9,000 | 1.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 345,110 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 198,180 | 57.4% |
| STORE_FAST | 74,630 | 21.6% |
| COPY_FREE_VARS | 18,000 | 5.2% |
| LOAD_FAST | 9,120 | 2.6% |
| RETURN_VALUE | 9,060 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 87,586 | 65.7% |
| LOAD_ATTR | 18,000 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 6.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.8% |
| LOAD_ATTR_CLASS | 9,000 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 87,686 | 65.8% |
| POP_JUMP_IF_TRUE | 45,000 | 33.8% |
| COMPARE_OP | 440 | 0.3% |
| COMPARE_OP_INT | 111 | 0.1% |
| COMPARE_OP_STR | 80 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,360 | 24.0% |
| LOAD_ATTR_INSTANCE_VALUE | 153,480 | 22.7% |
| LOAD_CONST | 108,060 | 16.0% |
| BUILD_TUPLE | 90,060 | 13.3% |
| LOAD_FAST_LOAD_FAST | 81,120 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 450,900 | 66.7% |
| POP_JUMP_IF_TRUE | 99,360 | 14.7% |
| COPY | 90,000 | 13.3% |
| SWAP | 18,000 | 2.7% |
| LOAD_FAST | 9,000 | 1.3% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 27,000 | 59.8% |
| BINARY_SUBSCR | 18,000 | 39.9% |
| LOAD_FAST | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 45,120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 854,754 | 45.9% |
| LOAD_CONST | 189,060 | 10.2% |
| STORE_ATTR_INSTANCE_VALUE | 171,000 | 9.2% |
| BINARY_OP | 131,840 | 7.1% |
| SWAP | 99,180 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 710,574 | 38.2% |
| LOAD_FAST | 342,000 | 18.4% |
| TO_BOOL_BOOL | 243,000 | 13.0% |
| TO_BOOL_INT | 152,858 | 8.2% |
| TO_BOOL_NONE | 143,974 | 7.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 216,276 | 37.2% |
| CACHE | 174,502 | 30.0% |
| CALL | 90,120 | 15.5% |
| LOAD_ATTR_PROPERTY | 63,000 | 10.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,330 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 545,348 | 93.8% |
| RETURN_GENERATOR | 18,060 | 3.1% |
| MAKE_CELL | 18,060 | 3.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 81,000 | 52.0% |
| NOP | 18,000 | 11.6% |
| POP_EXCEPT | 18,000 | 11.6% |
| STORE_ATTR_INSTANCE_VALUE | 18,000 | 11.6% |
| POP_TOP | 11,630 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 81,000 | 52.0% |
| RETURN_CONST | 36,000 | 23.1% |
| LOAD_FAST | 20,630 | 13.3% |
| LOAD_CONST | 9,060 | 5.8% |
| JUMP_BACKWARD | 9,000 | 5.8% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 323,220 | 90.0% |
| LOAD_ATTR_INSTANCE_VALUE | 27,000 | 7.5% |
| LOAD_ATTR | 9,000 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 359,220 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 90,000 | 58.8% |
| POP_JUMP_IF_TRUE | 45,000 | 29.4% |
| COMPARE_OP_STR | 9,000 | 5.9% |
| STORE_ATTR_INSTANCE_VALUE | 9,000 | 5.9% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 81,000 | 52.9% |
| JUMP_BACKWARD | 45,060 | 29.4% |
| POP_JUMP_IF_FALSE | 18,000 | 11.8% |
| JUMP_FORWARD | 9,000 | 5.9% |
| FOR_ITER_LIST | 120 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 117,480 | 44.5% |
| GET_ITER | 109,791 | 41.6% |
| LOAD_FAST | 18,000 | 6.8% |
| SWAP | 18,000 | 6.8% |
| FOR_ITER | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 100,671 | 38.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 81,040 | 30.7% |
| STORE_FAST | 36,420 | 13.8% |
| LOAD_FAST | 18,060 | 6.8% |
| SWAP | 18,000 | 6.8% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 207,000 | 60.5% |
| LOAD_FAST | 81,000 | 23.7% |
| RETURN_GENERATOR | 45,000 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 342,000 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 60 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 234,120 | 55.3% |
| LOAD_FAST | 81,300 | 19.2% |
| LOAD_CONST | 81,060 | 19.1% |
| LOAD_DEREF | 18,000 | 4.2% |
| LOAD_FAST_LOAD_FAST | 9,240 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 342,660 | 80.9% |
| RETURN_VALUE | 54,060 | 12.8% |
| COPY | 9,000 | 2.1% |
| POP_JUMP_IF_TRUE | 9,000 | 2.1% |
| STORE_FAST | 9,000 | 2.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 690,792 | 50.1% |
| POP_JUMP_IF_TRUE | 228,280 | 16.6% |
| FOR_ITER_LIST | 81,060 | 5.9% |
| CALL_LIST_APPEND | 74,135 | 5.4% |
| POP_JUMP_IF_FALSE | 73,220 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 486,896 | 35.3% |
| FOR_ITER_RANGE | 346,881 | 25.2% |
| FOR_ITER_GEN | 162,000 | 11.8% |
| LOAD_FAST | 136,889 | 9.9% |
| FOR_ITER | 117,480 | 8.5% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 126,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 81,000 | 64.3% |
| SEND | 45,000 | 35.7% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 334,363 | 53.7% |
| POP_TOP | 99,060 | 15.9% |
| POP_JUMP_IF_TRUE | 81,000 | 13.0% |
| STORE_ATTR_INSTANCE_VALUE | 36,330 | 5.8% |
| POP_JUMP_IF_FALSE | 18,005 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 422,519 | 67.8% |
| LOAD_CONST | 69,645 | 11.2% |
| LOAD_FAST_LOAD_FAST | 45,000 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 31,394 | 5.0% |
| LOAD_GLOBAL_MODULE | 27,000 | 4.3% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 9,000 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 283,821 | 55.9% |
| LOAD_FAST | 196,440 | 38.7% |
| LOAD_CONST | 18,000 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 1.8% |
| BINARY_SLICE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 489,381 | 96.5% |
| LOAD_FAST | 18,000 | 3.5% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,820,639 | 62.1% |
| LOAD_ATTR_INSTANCE_VALUE | 651,770 | 14.3% |
| LOAD_ATTR_SLOT | 283,821 | 6.2% |
| LOAD_ATTR_WITH_HINT | 252,000 | 5.5% |
| LOAD_GLOBAL_MODULE | 225,716 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 901,476 | 19.8% |
| PUSH_NULL | 771,403 | 17.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 756,180 | 16.6% |
| LOAD_CONST | 360,072 | 7.9% |
| CALL_PY_EXACT_ARGS | 241,297 | 5.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,594,220 | 20.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,254,315 | 9.9% |
| LOAD_CONST | 892,451 | 7.0% |
| POP_JUMP_IF_FALSE | 838,368 | 6.6% |
| STORE_ATTR_SLOT | 784,762 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,029,415 | 31.7% |
| COMPARE_OP_INT | 1,306,161 | 10.3% |
| STORE_FAST | 998,245 | 7.9% |
| LOAD_CONST | 892,451 | 7.0% |
| CALL | 516,175 | 4.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 298,841 | 18.8% |
| RESUME_CHECK | 155,141 | 9.8% |
| POP_JUMP_IF_FALSE | 127,901 | 8.1% |
| NOP | 109,606 | 6.9% |
| POP_JUMP_IF_TRUE | 108,240 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 377,820 | 23.8% |
| LOAD_ATTR_INSTANCE_VALUE | 275,343 | 17.3% |
| PUSH_NULL | 153,240 | 9.7% |
| STORE_ATTR_INSTANCE_VALUE | 117,000 | 7.4% |
| LOAD_ATTR | 111,782 | 7.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,589,242 | 14.5% |
| POP_JUMP_IF_FALSE | 6,289,456 | 10.6% |
| STORE_FAST | 5,949,259 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 4,082,584 | 6.9% |
| LOAD_CONST | 4,029,415 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,477,651 | 29.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,606,169 | 7.8% |
| STORE_ATTR_INSTANCE_VALUE | 3,750,214 | 6.3% |
| LOAD_ATTR_SLOT | 3,089,175 | 5.2% |
| LOAD_ATTR | 2,820,639 | 4.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 36,060 | 66.7% |
| LOAD_FAST_AND_CLEAR | 18,000 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 36,060 | 66.7% |
| LOAD_FAST_AND_CLEAR | 18,000 | 33.3% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 54,000 | 75.0% |
| POP_JUMP_IF_FALSE | 9,000 | 12.5% |
| STORE_FAST | 9,000 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 54,000 | 75.0% |
| LOAD_ATTR | 9,000 | 12.5% |
| LOAD_CONST | 9,000 | 12.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 976,263 | 12.6% |
| LOAD_GLOBAL_MODULE | 818,460 | 10.5% |
| STORE_FAST | 797,775 | 10.3% |
| STORE_ATTR_INSTANCE_VALUE | 748,140 | 9.6% |
| POP_JUMP_IF_FALSE | 675,360 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,495,790 | 19.3% |
| STORE_ATTR_SLOT | 1,346,084 | 17.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,024,115 | 13.2% |
| LOAD_FAST | 662,181 | 8.5% |
| LOAD_FAST_LOAD_FAST | 550,241 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 340 | 14.7% |
| POP_JUMP_IF_FALSE | 288 | 12.5% |
| STORE_FAST | 288 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 160 | 6.9% |
| POP_TOP | 140 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,632 | 70.6% |
| LOAD_GLOBAL_BUILTIN | 612 | 26.5% |
| LOAD_ATTR | 32 | 1.4% |
| CALL | 12 | 0.5% |
| LOAD_CONST | 12 | 0.5% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 40 | 66.7% |
| LOAD_SUPER_ATTR_ATTR | 20 | 33.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 139,102 | 45.9% |
| CALL_PY_EXACT_ARGS | 119,081 | 39.3% |
| COPY_FREE_VARS | 18,060 | 6.0% |
| CACHE | 9,000 | 3.0% |
| CALL | 9,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 155,261 | 51.2% |
| MAKE_CELL | 139,102 | 45.9% |
| RETURN_GENERATOR | 9,000 | 3.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,514,802 | 48.3% |
| COMPARE_OP_INT | 2,106,168 | 18.4% |
| TO_BOOL_NONE | 909,803 | 8.0% |
| TO_BOOL | 850,393 | 7.4% |
| CONTAINS_OP | 450,900 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,289,456 | 55.1% |
| RETURN_CONST | 1,111,596 | 9.7% |
| LOAD_CONST | 838,368 | 7.3% |
| LOAD_GLOBAL_MODULE | 791,900 | 6.9% |
| LOAD_FAST_LOAD_FAST | 675,360 | 5.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,276,178 | 55.2% |
| LOAD_FAST | 1,594,781 | 38.7% |
| LOAD_ATTR | 99,060 | 2.4% |
| LOAD_DEREF | 99,060 | 2.4% |
| LOAD_ATTR_WITH_HINT | 26,802 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,418,260 | 82.9% |
| RETURN_CONST | 209,141 | 5.1% |
| LOAD_GLOBAL_MODULE | 207,100 | 5.0% |
| LOAD_FAST_LOAD_FAST | 108,240 | 2.6% |
| NOP | 99,060 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 832,478 | 64.4% |
| LOAD_ATTR_INSTANCE_VALUE | 342,000 | 26.5% |
| LOAD_ATTR | 81,360 | 6.3% |
| LOAD_GLOBAL_MODULE | 9,300 | 0.7% |
| RETURN_VALUE | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 483,102 | 37.4% |
| LOAD_FAST_LOAD_FAST | 325,901 | 25.2% |
| LOAD_GLOBAL_MODULE | 258,235 | 20.0% |
| LOAD_CONST | 99,000 | 7.7% |
| LOAD_DEREF | 63,120 | 4.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,760,531 | 52.7% |
| COMPARE_OP_INT | 531,300 | 15.9% |
| TO_BOOL_INT | 257,935 | 7.7% |
| TO_BOOL_STR | 180,360 | 5.4% |
| TO_BOOL_NONE | 179,817 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,465,300 | 43.9% |
| LOAD_GLOBAL_BUILTIN | 369,120 | 11.1% |
| JUMP_BACKWARD | 228,280 | 6.8% |
| LOAD_CONST | 217,244 | 6.5% |
| NOP | 206,276 | 6.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,000 | 50.0% |
| CALL_KW | 9,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 9,000 | 50.0% |
| COPY | 9,000 | 50.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 27,000 | 50.0% |
| POP_TOP | 9,000 | 16.7% |
| CALL_INTRINSIC_1 | 9,000 | 16.7% |
| POP_JUMP_IF_FALSE | 9,000 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 27,000 | 50.0% |
| COPY | 18,000 | 33.3% |
| CALL_INTRINSIC_1 | 9,000 | 16.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,212,895 | 37.4% |
| POP_JUMP_IF_FALSE | 1,111,596 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 568,919 | 9.6% |
| STORE_ATTR_SLOT | 459,341 | 7.8% |
| STORE_FAST | 295,653 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,909,079 | 66.1% |
| INTERPRETER_EXIT | 1,277,683 | 21.6% |
| EXIT_INIT_CHECK | 243,240 | 4.1% |
| STORE_FAST | 132,375 | 2.2% |
| TO_BOOL_BOOL | 99,005 | 1.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 207,000 | 82.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 45,000 | 17.8% |
| SEND | 400 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 207,000 | 82.0% |
| YIELD_VALUE | 45,000 | 17.8% |
| SEND | 400 | 0.2% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 118,417 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 37,961 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,336 | 34.1% |
| SET_FUNCTION_ATTRIBUTE | 37,961 | 24.3% |
| CALL | 29,001 | 18.5% |
| LOAD_FAST | 18,000 | 11.5% |
| CALL_PY_EXACT_ARGS | 9,080 | 5.8% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 126,760 | 63.3% |
| LOAD_FAST_LOAD_FAST | 36,400 | 18.2% |
| LOAD_DEREF | 27,000 | 13.5% |
| STORE_FAST_LOAD_FAST | 9,000 | 4.5% |
| STORE_ATTR | 980 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 45,000 | 22.5% |
| LOAD_FAST | 36,300 | 18.1% |
| RETURN_CONST | 36,120 | 18.0% |
| LOAD_GLOBAL_BUILTIN | 27,000 | 13.5% |
| JUMP_FORWARD | 18,000 | 9.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,120 | 49.9% |
| MAKE_FUNCTION | 9,000 | 10.0% |
| CALL | 9,000 | 10.0% |
| JUMP_FORWARD | 9,000 | 10.0% |
| LOAD_CONST | 9,000 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,180 | 40.0% |
| LOAD_GLOBAL_MODULE | 27,040 | 29.9% |
| LOAD_FAST | 18,060 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 9,000 | 10.0% |
| BUILD_MAP | 60 | 0.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,598,993 | 17.1% |
| CALL | 1,531,571 | 16.4% |
| LOAD_CONST | 998,245 | 10.7% |
| CALL_BUILTIN_FAST | 611,220 | 6.6% |
| LOAD_ATTR_INSTANCE_VALUE | 572,462 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,949,259 | 63.8% |
| LOAD_FAST_LOAD_FAST | 797,775 | 8.6% |
| LOAD_CONST | 598,459 | 6.4% |
| LOAD_GLOBAL_BUILTIN | 399,655 | 4.3% |
| JUMP_FORWARD | 334,363 | 3.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 81,000 | 50.0% |
| COPY | 63,000 | 38.9% |
| STORE_ATTR | 9,000 | 5.6% |
| FOR_ITER_RANGE | 9,000 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 81,000 | 50.0% |
| STORE_ATTR_INSTANCE_VALUE | 63,000 | 38.9% |
| STORE_ATTR | 9,000 | 5.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,000 | 5.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 667,426 | 77.9% |
| UNPACK_SEQUENCE_LIST | 90,000 | 10.5% |
| UNPACK_SEQUENCE_TUPLE | 54,180 | 6.3% |
| STORE_FAST_STORE_FAST | 18,120 | 2.1% |
| COPY | 18,060 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 469,306 | 54.8% |
| LOAD_FAST_LOAD_FAST | 126,120 | 14.7% |
| LOAD_GLOBAL_MODULE | 99,000 | 11.6% |
| STORE_FAST | 72,180 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 63,000 | 7.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 425,030 | 38.9% |
| BINARY_OP_SUBTRACT_INT | 267,544 | 24.5% |
| LOAD_FAST | 144,000 | 13.2% |
| LOAD_ATTR | 65,920 | 6.0% |
| BUILD_LIST | 36,060 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 710,574 | 65.1% |
| COPY | 99,180 | 9.1% |
| STORE_FAST | 92,920 | 8.5% |
| LOAD_CONST | 54,000 | 4.9% |
| POP_EXCEPT | 45,000 | 4.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,020 | 98.0% |
| RETURN_VALUE | 80 | 0.9% |
| UNPACK_SEQUENCE | 40 | 0.4% |
| BINARY_SLICE | 20 | 0.2% |
| FOR_ITER | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 9,000 | 97.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 1.3% |
| UNPACK_SEQUENCE | 40 | 0.4% |
| UNPACK_SEQUENCE_TUPLE | 40 | 0.4% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 81,000 | 18.8% |
| YIELD_VALUE | 81,000 | 18.8% |
| BINARY_OP_ADD_UNICODE | 81,000 | 18.8% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 81,000 | 18.8% |
| RETURN_VALUE | 45,000 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 189,000 | 43.8% |
| STORE_FAST_LOAD_FAST | 81,000 | 18.8% |
| YIELD_VALUE | 81,000 | 18.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 81,000 | 18.8% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,800 | 77.3% |
| LOAD_ATTR_INSTANCE_VALUE | 11,832 | 12.9% |
| LOAD_ATTR | 9,000 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,400 | 58.3% |
| LOAD_GLOBAL_MODULE | 26,400 | 28.8% |
| STORE_FAST | 11,832 | 12.9% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,630 | 62.4% |
| LOAD_FAST_LOAD_FAST | 198,000 | 24.4% |
| CALL_LEN | 63,000 | 7.8% |
| LOAD_CONST | 44,440 | 5.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 425,030 | 52.3% |
| BINARY_SLICE | 234,000 | 28.8% |
| RETURN_VALUE | 54,000 | 6.6% |
| CALL_PY_EXACT_ARGS | 54,000 | 6.6% |
| STORE_FAST | 45,000 | 5.5% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 90,000 | 52.6% |
| RETURN_VALUE | 81,000 | 47.4% |
| LOAD_ATTR | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 81,000 | 47.4% |
| LOAD_GLOBAL_MODULE | 81,000 | 47.4% |
| STORE_FAST | 9,060 | 5.3% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,000 | 89.7% |
| LOAD_CONST | 1,020 | 10.2% |
| BINARY_OP | 16 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,000 | 89.7% |
| CALL_BUILTIN_O | 1,020 | 10.2% |
| CALL | 16 | 0.2% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 9,000 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,420 | 65.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 12.9% |
| LOAD_ATTR_WITH_HINT | 9,000 | 12.9% |
| CALL | 6,375 | 9.1% |
| LOAD_FAST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 45,436 | 65.0% |
| RETURN_VALUE | 9,000 | 12.9% |
| LOAD_FAST | 9,000 | 12.9% |
| STORE_FAST | 6,375 | 9.1% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 423,000 | 65.5% |
| LOAD_ATTR_INSTANCE_VALUE | 72,000 | 11.2% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 9.8% |
| CALL_LEN | 45,000 | 7.0% |
| LOAD_CONST | 42,544 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 267,544 | 41.4% |
| STORE_FAST | 243,000 | 37.6% |
| LOAD_FAST | 63,000 | 9.8% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 9.8% |
| BINARY_SUBSCR_LIST_INT | 9,000 | 1.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 315,060 | 46.6% |
| LOAD_FAST | 262,486 | 38.8% |
| BUILD_TUPLE | 36,060 | 5.3% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| RETURN_VALUE | 18,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,000 | 47.9% |
| PUSH_EXC_INFO | 261,120 | 38.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 28,426 | 4.2% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| STORE_FAST | 18,120 | 2.7% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 225,000 | 60.9% |
| LOAD_FAST | 144,180 | 39.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 369,180 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 65,515 | 78.3% |
| BINARY_SUBSCR | 9,156 | 10.9% |
| BINARY_OP_SUBTRACT_INT | 9,000 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 34,239 | 40.9% |
| LOAD_FAST | 18,060 | 21.6% |
| STORE_FAST | 11,630 | 13.9% |
| TO_BOOL_BOOL | 10,426 | 12.5% |
| LOAD_CONST | 9,000 | 10.8% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 81,080 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 81,080 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 171,280 | 100.0% |
| BINARY_SUBSCR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 90,060 | 52.6% |
| LOAD_GLOBAL_BUILTIN | 18,060 | 10.5% |
| LOAD_GLOBAL_MODULE | 18,040 | 10.5% |
| LOAD_FAST | 18,000 | 10.5% |
| RETURN_VALUE | 9,060 | 5.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 99,000 | 40.7% |
| LOAD_ATTR_INSTANCE_VALUE | 72,000 | 29.6% |
| LOAD_FAST_LOAD_FAST | 27,100 | 11.1% |
| LOAD_FAST | 27,000 | 11.1% |
| PUSH_NULL | 9,000 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 243,120 | 100.0% |
| COPY_FREE_VARS | 120 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 81,000 | 36.8% |
| LOAD_FAST | 64,779 | 29.4% |
| LOAD_FAST_LOAD_FAST | 35,926 | 16.3% |
| BINARY_SLICE | 18,000 | 8.2% |
| CALL_BUILTIN_CLASS | 18,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 118,156 | 53.6% |
| POP_TOP | 81,000 | 36.8% |
| COPY_FREE_VARS | 19,330 | 8.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,580 | 0.7% |
| CALL_PY_EXACT_ARGS | 333 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,992 | 28.9% |
| LOAD_ATTR_INSTANCE_VALUE | 27,120 | 26.1% |
| LOAD_GLOBAL_MODULE | 10,466 | 10.1% |
| LOAD_GLOBAL_BUILTIN | 9,080 | 8.7% |
| RETURN_GENERATOR | 9,000 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,000 | 26.0% |
| GET_ITER | 22,318 | 21.5% |
| LOAD_FAST | 18,120 | 17.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 18,000 | 17.3% |
| LOAD_CONST | 9,000 | 8.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 628,560 | 49.3% |
| LOAD_FAST_LOAD_FAST | 341,360 | 26.8% |
| LOAD_CONST | 252,060 | 19.8% |
| LOAD_GLOBAL_MODULE | 27,000 | 2.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 611,220 | 48.2% |
| RETURN_VALUE | 340,920 | 26.9% |
| TO_BOOL_BOOL | 99,040 | 7.8% |
| COPY | 81,000 | 6.4% |
| POP_TOP | 44,760 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 10,781 | 54.3% |
| LOAD_FAST | 9,060 | 45.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,781 | 54.3% |
| STORE_FAST | 9,060 | 45.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,310 | 61.1% |
| LOAD_ATTR_INSTANCE_VALUE | 21,919 | 36.9% |
| BINARY_OP_MULTIPLY_FLOAT | 1,020 | 1.7% |
| CALL | 76 | 0.1% |
| BUILD_LIST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,919 | 52.0% |
| STORE_SUBSCR_DICT | 18,000 | 30.3% |
| BINARY_SUBSCR_DICT | 9,000 | 15.2% |
| LOAD_CONST | 1,036 | 1.7% |
| POP_TOP | 390 | 0.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 883,202 | 53.0% |
| LOAD_GLOBAL_BUILTIN | 361,020 | 21.7% |
| LOAD_ATTR_MODULE | 224,400 | 13.5% |
| BUILD_TUPLE | 153,300 | 9.2% |
| LOAD_ATTR | 45,080 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,513,822 | 90.8% |
| RETURN_VALUE | 108,120 | 6.5% |
| COPY | 27,000 | 1.6% |
| STORE_FAST | 18,060 | 1.1% |
| TO_BOOL | 140 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 504,360 | 60.6% |
| LOAD_ATTR_INSTANCE_VALUE | 309,411 | 37.2% |
| BINARY_SUBSCR | 9,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 9,000 | 1.1% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 291,099 | 35.0% |
| LOAD_FAST | 169,740 | 20.4% |
| LOAD_CONST | 72,240 | 8.7% |
| BINARY_OP_ADD_INT | 63,000 | 7.6% |
| BINARY_OP | 45,000 | 5.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,115 | 60.7% |
| BUILD_TUPLE | 56,920 | 29.8% |
| RETURN_VALUE | 18,120 | 9.5% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 90,000 | 47.1% |
| JUMP_BACKWARD | 74,135 | 38.8% |
| LOAD_FAST | 18,000 | 9.4% |
| NOP | 9,000 | 4.7% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 476,180 | 64.3% |
| LOAD_ATTR_METHOD_NO_DICT | 153,000 | 20.7% |
| LOAD_FAST_LOAD_FAST | 54,120 | 7.3% |
| LOAD_FAST | 38,900 | 5.3% |
| RETURN_VALUE | 18,060 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 466,920 | 63.0% |
| STORE_FAST | 93,040 | 12.6% |
| CALL_PY_EXACT_ARGS | 81,080 | 10.9% |
| LOAD_CONST | 54,000 | 7.3% |
| LOAD_FAST | 18,000 | 2.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 288,520 | 54.0% |
| LOAD_ATTR_METHOD_NO_DICT | 171,000 | 32.0% |
| LOAD_FAST | 45,060 | 8.4% |
| LOAD_ATTR | 18,060 | 3.4% |
| LOAD_FAST_LOAD_FAST | 11,832 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,312 | 37.7% |
| UNPACK_SEQUENCE_LIST | 90,000 | 16.8% |
| YIELD_VALUE | 81,000 | 15.2% |
| POP_TOP | 63,120 | 11.8% |
| RETURN_VALUE | 63,000 | 11.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 769,222 | 49.5% |
| LOAD_ATTR | 756,180 | 48.6% |
| LOAD_FAST | 18,060 | 1.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,000 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,778 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 738,260 | 47.5% |
| STORE_FAST | 364,821 | 23.5% |
| POP_TOP | 177,435 | 11.4% |
| GET_ITER | 108,180 | 7.0% |
| LOAD_FAST | 54,180 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 431,811 | 54.5% |
| BUILD_TUPLE | 144,000 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 7.9% |
| LOAD_FAST_CHECK | 54,000 | 6.8% |
| LOAD_CONST | 36,040 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 620,871 | 78.3% |
| STORE_FAST | 107,940 | 13.6% |
| PUSH_EXC_INFO | 18,060 | 2.3% |
| LOAD_CONST | 18,000 | 2.3% |
| UNPACK_SEQUENCE_TUPLE | 18,000 | 2.3% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,373,886 | 39.0% |
| LOAD_FAST | 2,593,718 | 30.0% |
| LOAD_FAST_LOAD_FAST | 496,080 | 5.7% |
| LOAD_CONST | 495,160 | 5.7% |
| LOAD_ATTR_METHOD_NO_DICT | 383,747 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,112,234 | 93.8% |
| COPY_FREE_VARS | 216,276 | 2.5% |
| RETURN_GENERATOR | 198,000 | 2.3% |
| MAKE_CELL | 119,081 | 1.4% |
| TO_BOOL_BOOL | 2,666 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,000 | 25.3% |
| LOAD_FAST | 99,200 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 92,630 | 21.7% |
| PUSH_NULL | 54,260 | 12.7% |
| LOAD_ATTR | 27,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 417,290 | 97.9% |
| RETURN_GENERATOR | 9,000 | 2.1% |
| MAKE_CELL | 60 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 153,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,120 | 53.0% |
| LOAD_FAST_LOAD_FAST | 36,060 | 23.5% |
| LOAD_GLOBAL_MODULE | 27,000 | 17.6% |
| STORE_FAST | 9,000 | 5.9% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 250,681 | 93.3% |
| LOAD_FAST | 11,570 | 4.3% |
| LOAD_GLOBAL_MODULE | 6,402 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 250,681 | 93.3% |
| POP_JUMP_IF_FALSE | 17,972 | 6.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,306,161 | 49.2% |
| LOAD_ATTR_INSTANCE_VALUE | 779,115 | 29.3% |
| LOAD_ATTR_CLASS | 288,000 | 10.8% |
| COPY | 99,180 | 3.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 90,000 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,106,168 | 79.3% |
| POP_JUMP_IF_TRUE | 531,300 | 20.0% |
| COPY | 18,000 | 0.7% |
| COMPARE_OP | 11 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 171,220 | 82.5% |
| LOAD_GLOBAL_MODULE | 36,000 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.1% |
| COMPARE_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 162,420 | 78.3% |
| COPY | 18,000 | 8.7% |
| RETURN_VALUE | 9,000 | 4.3% |
| EXTENDED_ARG | 9,000 | 4.3% |
| POP_JUMP_IF_TRUE | 9,000 | 4.3% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 162,000 | 78.3% |
| LOAD_FAST | 36,000 | 17.4% |
| GET_ITER | 9,000 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 162,000 | 78.3% |
| POP_TOP | 45,000 | 21.7% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 486,896 | 60.9% |
| GET_ITER | 303,414 | 38.0% |
| SWAP | 9,000 | 1.1% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 436,236 | 54.6% |
| LOAD_FAST | 146,952 | 18.4% |
| JUMP_BACKWARD | 81,060 | 10.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 68,720 | 8.6% |
| RETURN_CONST | 21,012 | 2.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 346,881 | 93.9% |
| GET_ITER | 22,318 | 6.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 339,367 | 91.9% |
| LOAD_CONST | 11,832 | 3.2% |
| RETURN_CONST | 9,000 | 2.4% |
| STORE_FAST_LOAD_FAST | 9,000 | 2.4% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 54,180 | 49.9% |
| JUMP_BACKWARD | 45,480 | 41.9% |
| SWAP | 9,000 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 45,480 | 41.9% |
| LOAD_FAST | 45,120 | 41.5% |
| LOAD_CONST | 9,000 | 8.3% |
| SWAP | 9,000 | 8.3% |
| LOAD_FAST_LOAD_FAST | 60 | 0.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 342,000 | 62.2% |
| LOAD_GLOBAL_MODULE | 171,560 | 31.2% |
| LOAD_FAST | 36,600 | 6.7% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 288,000 | 52.3% |
| LOAD_FAST | 108,360 | 19.7% |
| BINARY_OP | 72,120 | 13.1% |
| CALL | 36,100 | 6.6% |
| RETURN_VALUE | 18,180 | 3.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,477,651 | 87.0% |
| LOAD_FAST_LOAD_FAST | 1,024,115 | 5.1% |
| COPY | 710,574 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 594,120 | 3.0% |
| LOAD_DEREF | 275,343 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,178,499 | 15.8% |
| POP_JUMP_IF_NONE | 2,276,178 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,086,074 | 10.4% |
| RETURN_VALUE | 2,026,121 | 10.1% |
| TO_BOOL_BOOL | 1,994,637 | 9.9% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,000 | 50.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,000 | 50.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,086,074 | 51.1% |
| LOAD_FAST | 1,314,962 | 32.2% |
| BINARY_SLICE | 189,040 | 4.6% |
| LOAD_CONST | 99,040 | 2.4% |
| BINARY_SUBSCR_STR_INT | 81,080 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,450,646 | 35.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 769,222 | 18.9% |
| LOAD_CONST | 724,075 | 17.8% |
| CALL_PY_EXACT_ARGS | 383,747 | 9.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 171,000 | 4.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,606,169 | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,355,686 | 20.1% |
| LOAD_ATTR_SLOT | 441,281 | 6.5% |
| LOAD_DEREF | 92,081 | 1.4% |
| LOAD_FAST_LOAD_FAST | 81,480 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,373,886 | 50.1% |
| LOAD_FAST | 2,133,960 | 31.7% |
| LOAD_FAST_LOAD_FAST | 506,021 | 7.5% |
| LOAD_CONST | 369,060 | 5.5% |
| LOAD_GLOBAL_MODULE | 118,241 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,339,941 | 99.6% |
| LOAD_ATTR_MODULE | 9,000 | 0.4% |
| LOAD_ATTR | 596 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,279,067 | 54.4% |
| LOAD_ATTR_CLASS | 342,000 | 14.6% |
| CALL_ISINSTANCE | 224,400 | 9.6% |
| LOAD_GLOBAL_MODULE | 108,040 | 4.6% |
| LOAD_ATTR | 99,060 | 4.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 162,000 | 56.2% |
| LOAD_FAST_LOAD_FAST | 63,000 | 21.9% |
| LOAD_FAST | 54,060 | 18.8% |
| LOAD_DEREF | 9,000 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 117,000 | 40.6% |
| COMPARE_OP_INT | 90,000 | 31.2% |
| LOAD_FAST | 27,060 | 9.4% |
| STORE_FAST | 27,000 | 9.4% |
| CONTAINS_OP | 18,000 | 6.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 54,000 | 60.0% |
| LOAD_FAST | 36,000 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 63,000 | 70.0% |
| RESUME_CHECK | 27,000 | 30.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,089,175 | 95.7% |
| BINARY_SUBSCR_TUPLE_INT | 90,060 | 2.8% |
| BINARY_SUBSCR_LIST_INT | 34,239 | 1.1% |
| LOAD_DEREF | 9,000 | 0.3% |
| LOAD_ATTR_SLOT | 4,165 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 641,122 | 19.9% |
| TO_BOOL_BOOL | 576,536 | 17.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 441,281 | 13.7% |
| BUILD_LIST | 283,821 | 8.8% |
| LIST_EXTEND | 283,821 | 8.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,394 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 252 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,000 | 43.8% |
| LOAD_CONST | 72,000 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,802 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 45,000 | 7.8% |
| RETURN_VALUE | 27,000 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,128,220 | 38.4% |
| LOAD_FAST | 667,080 | 12.0% |
| POP_JUMP_IF_FALSE | 513,396 | 9.3% |
| STORE_FAST | 399,655 | 7.2% |
| POP_JUMP_IF_TRUE | 369,120 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,082,584 | 73.6% |
| CALL_ISINSTANCE | 361,020 | 6.5% |
| LOAD_DEREF | 298,841 | 5.4% |
| CHECK_EXC_MATCH | 292,414 | 5.3% |
| BUILD_TUPLE | 153,300 | 2.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,730,668 | 21.0% |
| RESUME_CHECK | 1,471,681 | 17.9% |
| POP_JUMP_IF_FALSE | 791,900 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 783,260 | 9.5% |
| STORE_ATTR_INSTANCE_VALUE | 607,439 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,339,941 | 28.4% |
| LOAD_FAST | 1,747,860 | 21.2% |
| CALL_ISINSTANCE | 883,202 | 10.7% |
| LOAD_FAST_LOAD_FAST | 818,460 | 9.9% |
| CALL | 443,521 | 5.4% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 90,040 | 100.0% |
| LOAD_SUPER_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 63,000 | 70.0% |
| PUSH_NULL | 27,060 | 30.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 134,780 | 93.7% |
| LOAD_DEREF | 9,000 | 6.3% |
| LOAD_SUPER_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 62,460 | 43.4% |
| CALL_PY_EXACT_ARGS | 44,440 | 30.9% |
| LOAD_FAST | 18,900 | 13.1% |
| CALL | 9,020 | 6.3% |
| LOAD_CONST | 9,000 | 6.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 8,112,234 | 53.8% |
| CACHE | 4,024,644 | 26.7% |
| COPY_FREE_VARS | 545,348 | 3.6% |
| CALL_PY_WITH_DEFAULTS | 417,290 | 2.8% |
| BINARY_SUBSCR_GETITEM | 369,180 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,589,242 | 57.0% |
| LOAD_GLOBAL_BUILTIN | 2,128,220 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,471,681 | 9.8% |
| NOP | 1,206,116 | 8.0% |
| LOAD_CONST | 488,321 | 3.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 135,000 | 62.5% |
| JUMP_BACKWARD_NO_INTERRUPT | 81,000 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 135,000 | 62.5% |
| RESUME_CHECK | 81,000 | 37.5% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,750,214 | 61.0% |
| LOAD_FAST_LOAD_FAST | 1,495,790 | 24.3% |
| SWAP | 710,574 | 11.6% |
| LOAD_DEREF | 117,000 | 1.9% |
| STORE_FAST_LOAD_FAST | 63,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,109,710 | 34.3% |
| LOAD_CONST | 1,254,315 | 20.4% |
| LOAD_FAST_LOAD_FAST | 748,140 | 12.2% |
| LOAD_GLOBAL_MODULE | 607,439 | 9.9% |
| RETURN_CONST | 568,919 | 9.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,378,023 | 50.4% |
| LOAD_FAST_LOAD_FAST | 1,346,084 | 49.2% |
| STORE_ATTR_SLOT | 9,720 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 976,263 | 35.7% |
| LOAD_CONST | 784,762 | 28.7% |
| LOAD_FAST | 481,260 | 17.6% |
| RETURN_CONST | 459,341 | 16.8% |
| JUMP_BACKWARD | 22,481 | 0.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,798 | 79.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 20.1% |
| STORE_ATTR_INSTANCE_VALUE | 84 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,000 | 80.2% |
| RETURN_CONST | 8,802 | 19.6% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 0.2% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 369,060 | 87.2% |
| LOAD_ATTR | 36,060 | 8.5% |
| CALL_BUILTIN_O | 18,000 | 4.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 0.0% |
| STORE_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 234,180 | 55.3% |
| RETURN_CONST | 162,060 | 38.3% |
| LOAD_GLOBAL_MODULE | 18,040 | 4.3% |
| POP_EXCEPT | 9,000 | 2.1% |
| JUMP_BACKWARD | 60 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 66.7% |
| STORE_SUBSCR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 60 | 50.0% |
| RETURN_CONST | 60 | 50.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,000 | 75.0% |
| CALL | 9,000 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,000 | 50.0% |
| POP_JUMP_IF_TRUE | 18,000 | 50.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,994,637 | 27.0% |
| CALL_ISINSTANCE | 1,513,822 | 20.5% |
| RETURN_VALUE | 1,422,481 | 19.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 738,260 | 10.0% |
| LOAD_ATTR_SLOT | 576,536 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,514,802 | 74.8% |
| POP_JUMP_IF_TRUE | 1,760,531 | 23.9% |
| EXTENDED_ARG | 90,000 | 1.2% |
| UNARY_NOT | 9,000 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,120 | 43.2% |
| BINARY_OP | 239,900 | 33.9% |
| COPY | 152,858 | 21.6% |
| LOAD_ATTR | 9,000 | 1.3% |
| TO_BOOL_NONE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 449,940 | 63.6% |
| POP_JUMP_IF_TRUE | 257,935 | 36.4% |
| TO_BOOL_NONE | 83 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 127,453 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| TO_BOOL | 16 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 127,589 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 641,122 | 58.8% |
| COPY | 143,974 | 13.2% |
| LOAD_FAST | 142,126 | 13.0% |
| LOAD_ATTR | 63,000 | 5.8% |
| LOAD_ATTR_INSTANCE_VALUE | 54,120 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 909,803 | 83.5% |
| POP_JUMP_IF_TRUE | 179,817 | 16.5% |
| TO_BOOL | 147 | 0.0% |
| TO_BOOL_STR | 140 | 0.0% |
| TO_BOOL_INT | 80 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 171,320 | 79.0% |
| COPY | 27,000 | 12.5% |
| CALL_BUILTIN_FAST | 9,240 | 4.3% |
| LOAD_ATTR | 9,000 | 4.2% |
| TO_BOOL_NONE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 180,360 | 83.2% |
| POP_JUMP_IF_FALSE | 36,240 | 16.7% |
| TO_BOOL_NONE | 140 | 0.1% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 90,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 90,000 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 18,000 | 28.5% |
| LOAD_FAST | 9,100 | 14.4% |
| END_SEND | 9,000 | 14.2% |
| BINARY_SUBSCR_DICT | 9,000 | 14.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,000 | 14.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 54,180 | 85.8% |
| LOAD_FAST | 9,000 | 14.2% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 198,000 | 29.3% |
| RETURN_VALUE | 117,240 | 17.3% |
| FOR_ITER | 81,040 | 12.0% |
| YIELD_VALUE | 81,000 | 12.0% |
| FOR_ITER_LIST | 68,720 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 667,426 | 98.7% |
| LOAD_FAST | 9,060 | 1.3% |
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
|     deferred | 894,949 | 33.1% |
|          hit | 1,809,293 | 66.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 112 | 5.9% |
| Failure | 1,787 | 94.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 760 | 42.5% |
| add other | 280 | 15.7% |
| or | 272 | 15.2% |
| remainder | 200 | 11.2% |
| add different types | 120 | 6.7% |
| multiply different types | 76 | 4.3% |
| floor divide | 40 | 2.2% |
| true divide other | 39 | 2.2% |


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
|     deferred | 315,072 | 18.6% |
|          hit | 1,381,997 | 81.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 296 | 31.6% |
| Failure | 640 | 68.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 560 | 87.5% |
| other | 40 | 6.2% |
| out of range | 40 | 6.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,712,284 | 21.1% |
|        deopt | 5,126 | 0.0% |
|          hit | 17,331,458 | 77.6% |
|         miss | 268,920 | 1.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,211 | 46.7% |
| Failure | 8,230 | 53.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,564 | 19.0% |
| class no vectorcall | 1,360 | 16.5% |
| cfunc noargs | 1,049 | 12.7% |
| meth descr method fastcall keywords | 920 | 11.2% |
| meth descr varargs | 809 | 9.8% |
| cfunc varargs keywords | 712 | 8.7% |
| class mutable | 420 | 5.1% |
| other | 376 | 4.6% |
| meth descr varargs keywords | 320 | 3.9% |
| no dict | 180 | 2.2% |
| init not simple | 180 | 2.2% |
| operator wrapper | 120 | 1.5% |
| cfunc varargs | 100 | 1.2% |
| wrong number arguments | 60 | 0.7% |
| cmethod | 40 | 0.5% |
| init not python | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 132,686 | 4.1% |
|        deopt | 11 | 0.0% |
|          hit | 3,130,444 | 95.9% |
|         miss | 1,108 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 191 | 29.8% |
| Failure | 451 | 70.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 120 | 26.6% |
| other | 100 | 22.2% |
| bytes | 80 | 17.7% |
| float long | 51 | 11.3% |
| big int | 40 | 8.9% |
| tuple | 40 | 8.9% |
| bool | 20 | 4.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 263,271 | 15.1% |
|          hit | 1,484,349 | 84.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 560 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 340 | 60.7% |
| ascii string | 60 | 10.7% |
| other | 40 | 7.1% |
| set | 40 | 7.1% |
| bytes | 40 | 7.1% |
| dict keys | 40 | 7.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,532,860 | 10.7% |
|        deopt | 6,369 | 0.0% |
|          hit | 37,664,092 | 88.5% |
|         miss | 336,866 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,965 | 48.4% |
| Failure | 9,568 | 51.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 2,012 | 21.0% |
| has managed dict | 1,980 | 20.7% |
| not managed dict | 1,716 | 17.9% |
| not in keys | 1,680 | 17.6% |
| shadowed | 480 | 5.0% |
| module attr not found | 400 | 4.2% |
| non overriding descriptor | 360 | 3.8% |
| metaclass attribute | 280 | 2.9% |
| class method obj | 220 | 2.3% |
| non object slot | 200 | 2.1% |
| class attr descriptor | 120 | 1.3% |
| overridden | 60 | 0.6% |
| builtin class method | 40 | 0.4% |
| mutable class | 20 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 68 | 0.0% |
|          hit | 13,772,558 | 100.0% |
|         miss | 840 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,244 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 233,880 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
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
|     deferred | 252,000 | 53.8% |
|          hit | 216,000 | 46.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 400 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 400 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 198,480 | 2.2% |
|        deopt | 9,884 | 0.1% |
|          hit | 8,401,103 | 92.1% |
|         miss | 524,184 | 5.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 10,804 | 91.7% |
| Failure | 980 | 8.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 420 | 42.9% |
| method | 120 | 12.2% |
| property | 120 | 12.2% |
| not in dict | 120 | 12.2% |
| not managed dict | 80 | 8.2% |
| not in keys | 80 | 8.2% |
| overridden | 40 | 4.1% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 180,060 | 29.8% |
|          hit | 423,480 | 70.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 19.2% |
| Failure | 420 | 80.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 340 | 81.0% |
| dict subclass no override | 80 | 19.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,019,036 | 9.6% |
|        deopt | 590 | 0.0% |
|          hit | 9,521,542 | 90.0% |
|         miss | 31,065 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,357 | 44.6% |
| Failure | 1,684 | 55.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 572 | 34.0% |
| sequence | 400 | 23.8% |
| float | 240 | 14.3% |
| dict | 160 | 9.5% |
| mapping | 112 | 6.7% |
| bytearray | 80 | 4.8% |
| tuple | 80 | 4.8% |
| set | 40 | 2.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,000 | 1.1% |
|          hit | 829,726 | 98.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 80.0% |
| Failure | 40 | 20.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 40 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 139,149,935 | 48.7% |
| Not specialized | 35,680,051 | 12.5% |
| Specialized | 111,137,358 | 38.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,377 | 100.0% |
| CALL | 4,712,284 | 0.0% |
| LOAD_ATTR | 4,532,860 | 0.0% |
| TO_BOOL | 1,019,036 | 0.0% |
| BINARY_OP | 894,949 | 0.0% |
| BINARY_SUBSCR | 315,072 | 0.0% |
| FOR_ITER | 263,271 | 0.0% |
| SEND | 252,000 | 0.0% |
| STORE_ATTR | 198,480 | 0.0% |
| STORE_SUBSCR | 180,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 515,502 | 44.3% |
| LOAD_ATTR_SLOT | 221,081 | 19.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100,743 | 8.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 93,684 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,489 | 5.2% |
| CALL_PY_EXACT_ARGS | 46,833 | 4.0% |
| CALL_METHOD_DESCRIPTOR_O | 27,660 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 19,890 | 1.7% |
| TO_BOOL_NONE | 19,142 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 13,326 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,289,206 | 28.0% |
| Calls to Python functions inlined | 11,037,695 | 72.0% |
| Calls via PyEval_EvalFrame (total) | 4,289,206 | 28.0% |
| Calls via PyEval_EvalFrame (vector) | 4,028,146 | 26.3% |
| Calls via PyEval_EvalFrame (generator) | 261,060 | 1.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 4,028,146 | 26.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 817,801 | 5.3% |
| Calls via PyEval_EvalFrame (function ex) | 99,240 | 0.6% |
| Calls via PyEval_EvalFrame (api) | 153,360 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 686,141 | 4.5% |
| Frame objects created | 616,586 | 4.0% |
| Frames pushed | 14,886,081 | 97.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,945,251 | 40.3% |
| Frees to freelist | 8,965,185 |  |
| Allocations | 13,227,653 | 59.7% |
| Allocations to 512 bytes | 12,987,451 | 58.6% |
| Allocations to 4 kbytes | 66,217 | 0.3% |
| Allocations over 4 kbytes | 173,985 | 0.8% |
| Frees | 13,472,864 |  |
| New values | 117,540 |  |
| Interpreter increfs | 139,548,809 | 77.4% |
| Interpreter decrefs | 150,658,165 | 74.9% |
| Increfs | 40,803,397 | 22.6% |
| Decrefs | 50,578,466 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 18,000 | 15.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,719,431 |  |
| Method cache misses | 232,993 |  |
| Method cache collisions | 244,370 |  |
| Method cache dunder hits | 5,112,702 |  |
| Method cache dunder misses | 12,847 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 945 | 0 | 10,300,650 |
| 1 | 85 | 0 | 2,543,816 |
| 2 | 4 | 132 | 1,242,958 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |

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
Stats gathered on: 2023-10-09
