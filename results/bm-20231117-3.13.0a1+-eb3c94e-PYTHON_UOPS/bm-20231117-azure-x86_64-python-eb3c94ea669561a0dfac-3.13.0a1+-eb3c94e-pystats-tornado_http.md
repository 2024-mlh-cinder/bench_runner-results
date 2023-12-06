
# Pystats results

- benchmark: tornado_http
- fork: python
- ref: eb3c94ea669561a0dfacaca715d4b2723bb2c6f4
- commit hash: eb3c94e
- commit date: 2023-11-17T20:58:13-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 74,082,861 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 25,182,040 | 7.0% | 27.7% | 0.1% |
| RESUME_CHECK | 19,569,772 | 5.5% | 33.2% | 0.0% |
| LOAD_CONST | 15,996,580 | 4.5% | 37.6% |  |
| POP_JUMP_IF_FALSE | 14,061,275 | 3.9% | 41.6% |  |
| RETURN_VALUE | 11,573,287 | 3.2% | 44.8% |  |
| CALL_PY_EXACT_ARGS | 10,876,819 | 3.0% | 47.8% | 0.6% |
| STORE_FAST | 10,822,093 | 3.0% | 50.9% |  |
| LOAD_GLOBAL_MODULE | 10,550,582 | 2.9% | 53.8% | 0.0% |
| LOAD_FAST_LOAD_FAST | 10,267,665 | 2.9% | 56.7% |  |
| POP_TOP | 10,091,605 | 2.8% | 59.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,758,800 | 2.4% | 61.9% | 0.9% |
| TO_BOOL_BOOL | 8,729,939 | 2.4% | 64.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 8,118,599 | 2.3% | 66.6% | 0.1% |
| RETURN_CONST | 7,884,716 | 2.2% | 68.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,972,007 | 1.9% | 70.8% | 0.1% |
| CALL | 6,252,928 | 1.7% | 72.5% |  |
| INTERPRETER_EXIT | 5,726,474 | 1.6% | 74.1% |  |
| LOAD_ATTR | 5,586,957 | 1.6% | 75.7% |  |
| POP_JUMP_IF_NONE | 5,411,859 | 1.5% | 77.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,310,417 | 1.2% | 78.4% | 0.7% |
| POP_JUMP_IF_TRUE | 4,055,426 | 1.1% | 79.5% |  |
| STORE_ATTR_SLOT | 3,602,715 | 1.0% | 80.6% | 19.3% |
| COMPARE_OP_INT | 3,408,925 | 1.0% | 81.5% | 0.0% |
| PUSH_NULL | 3,218,064 | 0.9% | 82.4% |  |
| LOAD_ATTR_MODULE | 3,063,161 | 0.9% | 83.3% | 0.0% |
| NOP | 2,990,474 | 0.8% | 84.1% |  |
| LOAD_ATTR_SLOT | 2,750,747 | 0.8% | 84.9% | 10.8% |
| COPY | 2,398,204 | 0.7% | 85.5% |  |
| LOAD_DEREF | 2,093,665 | 0.6% | 86.1% |  |
| CALL_ISINSTANCE | 2,087,068 | 0.6% | 86.7% |  |
| POP_JUMP_IF_NOT_NONE | 1,670,017 | 0.5% | 87.2% |  |
| CALL_BUILTIN_FAST | 1,654,780 | 0.5% | 87.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,512,554 | 0.4% | 88.0% | 8.3% |
| TO_BOOL_NONE | 1,419,069 | 0.4% | 88.4% | 1.6% |
| BUILD_TUPLE | 1,388,846 | 0.4% | 88.8% |  |
| SWAP | 1,382,727 | 0.4% | 89.2% |  |
| TO_BOOL | 1,265,626 | 0.4% | 89.6% |  |
| ENTER_EXECUTOR | 1,226,923 | 0.3% | 89.9% |  |
| BINARY_OP | 1,092,833 | 0.3% | 90.2% |  |
| BINARY_OP_ADD_INT | 1,083,896 | 0.3% | 90.5% |  |
| CALL_FUNCTION_EX | 1,080,523 | 0.3% | 90.8% |  |
| CALL_LEN | 1,002,573 | 0.3% | 91.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 980,842 | 0.3% | 91.4% | 3.8% |
| STORE_FAST_STORE_FAST | 968,201 | 0.3% | 91.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 957,327 | 0.3% | 91.9% |  |
| BINARY_SUBSCR_DICT | 904,422 | 0.3% | 92.2% |  |
| BUILD_LIST | 887,131 | 0.2% | 92.4% |  |
| BINARY_OP_SUBTRACT_INT | 837,615 | 0.2% | 92.7% |  |
| CONTAINS_OP | 799,600 | 0.2% | 92.9% |  |
| BUILD_MAP | 793,640 | 0.2% | 93.1% |  |
| GET_ITER | 789,803 | 0.2% | 93.3% |  |
| COPY_FREE_VARS | 781,800 | 0.2% | 93.5% |  |
| TO_BOOL_INT | 769,958 | 0.2% | 93.7% | 0.8% |
| LOAD_ATTR_WITH_HINT | 764,652 | 0.2% | 94.0% | 2.1% |
| JUMP_FORWARD | 747,552 | 0.2% | 94.2% |  |
| LOAD_ATTR_CLASS | 733,220 | 0.2% | 94.4% | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 727,101 | 0.2% | 94.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 712,430 | 0.2% | 94.8% |  |
| FOR_ITER_LIST | 656,146 | 0.2% | 95.0% |  |
| YIELD_VALUE | 577,520 | 0.2% | 95.1% |  |
| IS_OP | 568,900 | 0.2% | 95.3% |  |
| CALL_PY_WITH_DEFAULTS | 568,636 | 0.2% | 95.4% |  |
| STORE_SUBSCR_DICT | 565,080 | 0.2% | 95.6% |  |
| BINARY_SLICE | 554,160 | 0.2% | 95.8% |  |
| BINARY_SUBSCR_GETITEM | 492,680 | 0.1% | 95.9% |  |
| DICT_MERGE | 480,760 | 0.1% | 96.0% |  |
| CALL_KW | 463,056 | 0.1% | 96.2% |  |
| GET_AWAITABLE | 456,000 | 0.1% | 96.3% |  |
| PUSH_EXC_INFO | 453,374 | 0.1% | 96.4% |  |
| POP_EXCEPT | 453,254 | 0.1% | 96.5% |  |
| END_SEND | 444,000 | 0.1% | 96.7% |  |
| CHECK_EXC_MATCH | 443,550 | 0.1% | 96.8% |  |
| JUMP_BACKWARD | 386,860 | 0.1% | 96.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 372,500 | 0.1% | 97.0% | 3.2% |
| MAKE_FUNCTION | 365,661 | 0.1% | 97.1% |  |
| MAKE_CELL | 363,167 | 0.1% | 97.2% |  |
| COMPARE_OP_FLOAT | 357,855 | 0.1% | 97.3% | 0.0% |
| FOR_ITER | 357,440 | 0.1% | 97.4% |  |
| BINARY_SUBSCR | 342,740 | 0.1% | 97.5% |  |
| SEND | 338,220 | 0.1% | 97.6% |  |
| RETURN_GENERATOR | 337,000 | 0.1% | 97.7% |  |
| EXIT_INIT_CHECK | 324,640 | 0.1% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 324,640 | 0.1% | 97.9% |  |
| LIST_EXTEND | 314,110 | 0.1% | 98.0% |  |
| CALL_INTRINSIC_1 | 302,090 | 0.1% | 98.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 293,519 | 0.1% | 98.1% | 46.7% |
| TO_BOOL_STR | 289,500 | 0.1% | 98.2% | 2.0% |
| STORE_ATTR | 289,120 | 0.1% | 98.3% |  |
| SEND_GEN | 287,800 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 277,940 | 0.1% | 98.4% | 0.0% |
| FOR_ITER_GEN | 275,940 | 0.1% | 98.5% |  |
| CALL_LIST_APPEND | 256,723 | 0.1% | 98.6% |  |
| CALL_BUILTIN_CLASS | 246,952 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 242,920 | 0.1% | 98.7% |  |
| BEFORE_WITH | 233,876 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 229,280 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 228,560 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 212,610 | 0.1% | 99.0% |  |
| DELETE_FAST | 208,316 | 0.1% | 99.0% |  |
| STORE_FAST_LOAD_FAST | 206,520 | 0.1% | 99.1% |  |
| EXTENDED_ARG | 206,460 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 205,260 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 194,280 | 0.1% | 99.3% |  |
| COMPARE_OP | 185,201 | 0.1% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 168,000 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 146,784 | 0.0% | 99.4% | 0.1% |
| BINARY_OP_ADD_FLOAT | 121,890 | 0.0% | 99.4% |  |
| STORE_DEREF | 121,560 | 0.0% | 99.5% |  |
| LOAD_ATTR_PROPERTY | 120,560 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 120,440 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 119,980 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 119,960 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 108,700 | 0.0% | 99.6% | 0.1% |
| FOR_ITER_TUPLE | 100,520 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 92,000 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 84,280 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 76,465 | 0.0% | 99.7% | 0.1% |
| LOAD_FAST_AND_CLEAR | 73,440 | 0.0% | 99.8% |  |
| BUILD_SLICE | 72,060 | 0.0% | 99.8% |  |
| RERAISE | 72,020 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 60,400 | 0.0% | 99.8% |  |
| CONVERT_VALUE | 60,320 | 0.0% | 99.8% |  |
| UNARY_INVERT | 60,180 | 0.0% | 99.8% |  |
| END_FOR | 59,980 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 59,024 | 0.0% | 99.9% | 9.0% |
| FOR_ITER_RANGE | 58,902 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 56,706 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 48,240 | 0.0% | 99.9% | 0.1% |
| LOAD_FAST_CHECK | 40,009 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 28,720 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 28,069 | 0.0% | 99.9% | 0.9% |
| RAISE_VARARGS | 24,420 | 0.0% | 100.0% |  |
| BUILD_STRING | 24,240 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 23,960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 13,960 | 0.0% | 100.0% |  |
| LIST_APPEND | 13,120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 12,997 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 12,240 | 0.0% | 100.0% |  |
| UNARY_NOT | 12,140 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 12,080 | 0.0% | 100.0% |  |
| BUILD_SET | 12,020 | 0.0% | 100.0% |  |
| RESUME | 9,300 | 0.0% | 100.0% | 13.1% |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,802,799 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 11,358,283 | 3.2% | 9.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,203,420 | 2.8% | 12.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,419,178 | 2.1% | 14.2% |
| STORE_FAST LOAD_FAST | 6,668,191 | 1.9% | 16.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,375,978 | 1.8% | 17.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,984,937 | 1.7% | 19.5% |
| CACHE RESUME_CHECK | 5,377,556 | 1.5% | 21.0% |
| RETURN_CONST POP_TOP | 5,199,560 | 1.5% | 22.4% |
| LOAD_CONST LOAD_FAST | 5,157,347 | 1.4% | 23.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,156,942 | 1.4% | 25.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,942,297 | 1.4% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,469,970 | 1.2% | 28.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,461,593 | 1.2% | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 4,181,774 | 1.2% | 30.4% |
| POP_TOP LOAD_FAST | 3,904,390 | 1.1% | 31.5% |
| RETURN_VALUE INTERPRETER_EXIT | 3,736,529 | 1.0% | 32.5% |
| LOAD_FAST LOAD_ATTR | 3,601,411 | 1.0% | 33.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,350,239 | 0.9% | 34.4% |
| LOAD_FAST LOAD_CONST | 3,337,646 | 0.9% | 35.4% |
| LOAD_FAST RETURN_VALUE | 3,170,348 | 0.9% | 36.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,048,021 | 0.9% | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 3,035,556 | 0.8% | 38.0% |
| POP_TOP RETURN_CONST | 2,937,651 | 0.8% | 38.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,813,556 | 0.8% | 39.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,794,340 | 0.8% | 40.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,768,477 | 0.8% | 41.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,691,169 | 0.8% | 41.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,676,216 | 0.7% | 42.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 2,590,561 | 0.7% | 43.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,255,200 | 0.6% | 44.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 2,249,333 | 0.6% | 44.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,222,061 | 0.6% | 45.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,177,906 | 0.6% | 45.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,138,378 | 0.6% | 46.4% |
| RETURN_VALUE STORE_FAST | 2,136,079 | 0.6% | 47.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,039,679 | 0.6% | 47.6% |
| LOAD_FAST CALL | 2,006,200 | 0.6% | 48.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,992,571 | 0.6% | 48.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,968,196 | 0.5% | 49.3% |
| CALL STORE_FAST | 1,947,264 | 0.5% | 49.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,900,090 | 0.5% | 50.3% |
| RETURN_VALUE TO_BOOL_BOOL | 1,887,209 | 0.5% | 50.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,881,748 | 0.5% | 51.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,868,218 | 0.5% | 51.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,797,656 | 0.5% | 52.4% |
| LOAD_FAST STORE_ATTR_SLOT | 1,791,709 | 0.5% | 52.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,743,614 | 0.5% | 53.4% |
| LOAD_CONST COMPARE_OP_INT | 1,716,983 | 0.5% | 53.9% |
| RETURN_CONST INTERPRETER_EXIT | 1,712,305 | 0.5% | 54.4% |
| NOP LOAD_FAST | 1,695,109 | 0.5% | 54.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,681,811 | 0.5% | 55.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,673,088 | 0.5% | 55.8% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,484,844 | 0.4% | 56.2% |
| PUSH_NULL LOAD_FAST | 1,361,292 | 0.4% | 56.6% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,303,887 | 0.4% | 56.9% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,280,743 | 0.4% | 57.3% |
| LOAD_CONST STORE_FAST | 1,220,741 | 0.3% | 57.6% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 1,214,804 | 0.3% | 58.0% |
| RESUME_CHECK NOP | 1,203,515 | 0.3% | 58.3% |
| LOAD_ATTR LOAD_FAST | 1,177,628 | 0.3% | 58.6% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,158,234 | 0.3% | 58.9% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,132,808 | 0.3% | 59.3% |
| LOAD_FAST COPY | 1,117,391 | 0.3% | 59.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,093,580 | 0.3% | 59.9% |
| LOAD_CONST LOAD_CONST | 1,081,397 | 0.3% | 60.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,072,205 | 0.3% | 60.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,064,063 | 0.3% | 60.8% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,055,950 | 0.3% | 61.1% |
| STORE_ATTR_SLOT LOAD_CONST | 1,047,758 | 0.3% | 61.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,047,274 | 0.3% | 61.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,043,920 | 0.3% | 61.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,008,437 | 0.3% | 62.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 997,280 | 0.3% | 62.5% |
| CALL POP_TOP | 990,351 | 0.3% | 62.8% |
| RETURN_VALUE RETURN_VALUE | 973,720 | 0.3% | 63.1% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 953,923 | 0.3% | 63.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 927,429 | 0.3% | 63.6% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 924,391 | 0.3% | 63.8% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 924,391 | 0.3% | 64.1% |
| POP_TOP LOAD_CONST | 916,793 | 0.3% | 64.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 901,060 | 0.3% | 64.6% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 894,098 | 0.2% | 64.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 875,165 | 0.2% | 65.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 872,716 | 0.2% | 65.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 857,761 | 0.2% | 65.6% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 855,898 | 0.2% | 65.8% |
| LOAD_FAST CALL_BUILTIN_FAST | 837,640 | 0.2% | 66.1% |
| CALL LOAD_FAST | 825,263 | 0.2% | 66.3% |
| CALL_BUILTIN_FAST STORE_FAST | 814,460 | 0.2% | 66.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 813,234 | 0.2% | 66.7% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 807,593 | 0.2% | 67.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 797,440 | 0.2% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 791,180 | 0.2% | 67.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 785,378 | 0.2% | 67.6% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 763,683 | 0.2% | 67.8% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 760,585 | 0.2% | 68.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 734,489 | 0.2% | 68.3% |
| COPY_FREE_VARS RESUME_CHECK | 732,240 | 0.2% | 68.5% |
| PUSH_NULL CALL | 731,352 | 0.2% | 68.7% |


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
| RESUME_CHECK | 5,377,556 | 93.7% |
| COPY_FREE_VARS | 238,098 | 4.1% |
| POP_TOP | 97,060 | 1.7% |
| MAKE_CELL | 12,360 | 0.2% |
| RETURN_GENERATOR | 12,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 112,416 | 48.1% |
| RETURN_VALUE | 108,100 | 46.2% |
| LOAD_GLOBAL_MODULE | 12,540 | 5.4% |
| CALL | 380 | 0.2% |
| LOAD_ATTR | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 233,796 | 100.0% |
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
| LOAD_GLOBAL_BUILTIN | 390,994 | 88.2% |
| BUILD_TUPLE | 24,080 | 5.4% |
| LOAD_ATTR_MODULE | 16,196 | 3.7% |
| LOAD_GLOBAL_MODULE | 11,980 | 2.7% |
| LOAD_GLOBAL | 260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 443,550 | 100.0% |


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
| LOAD_FAST | 325,180 | 41.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 144,140 | 18.3% |
| LOAD_ATTR_INSTANCE_VALUE | 96,551 | 12.2% |
| LOAD_ATTR | 72,140 | 9.1% |
| BINARY_SLICE | 36,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 404,312 | 51.2% |
| FOR_ITER | 148,039 | 18.7% |
| FOR_ITER_TUPLE | 73,020 | 9.2% |
| CALL_PY_EXACT_ARGS | 72,720 | 9.2% |
| LOAD_FAST_AND_CLEAR | 49,440 | 6.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,736,529 | 65.3% |
| RETURN_CONST | 1,712,305 | 29.9% |
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
| LOAD_CONST | 365,661 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 160,961 | 44.0% |
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
| RESUME_CHECK | 1,203,515 | 40.2% |
| POP_JUMP_IF_FALSE | 449,750 | 15.0% |
| STORE_FAST | 389,323 | 13.0% |
| STORE_ATTR_INSTANCE_VALUE | 306,258 | 10.2% |
| POP_JUMP_IF_TRUE | 274,972 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,695,109 | 56.7% |
| LOAD_GLOBAL_MODULE | 546,900 | 18.3% |
| LOAD_FAST_LOAD_FAST | 300,220 | 10.0% |
| LOAD_DEREF | 134,742 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 120,140 | 4.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 328,618 | 72.5% |
| SWAP | 60,080 | 13.3% |
| COPY | 36,020 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 12,120 | 2.7% |
| STORE_SUBSCR_DICT | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 290,456 | 64.1% |
| RETURN_VALUE | 60,080 | 13.3% |
| RERAISE | 36,020 | 7.9% |
| DELETE_FAST | 24,000 | 5.3% |
| ENTER_EXECUTOR | 15,616 | 3.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,199,560 | 51.5% |
| CALL | 990,351 | 9.8% |
| CALL_METHOD_DESCRIPTOR_O | 807,593 | 8.0% |
| POP_JUMP_IF_FALSE | 604,630 | 6.0% |
| CALL_FUNCTION_EX | 500,067 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,904,390 | 38.7% |
| RETURN_CONST | 2,937,651 | 29.1% |
| LOAD_CONST | 916,793 | 9.1% |
| ENTER_EXECUTOR | 704,288 | 7.0% |
| RESUME_CHECK | 336,620 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 348,440 | 76.9% |
| RERAISE | 36,020 | 7.9% |
| CALL | 30,432 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 12,069 | 2.7% |
| RAISE_VARARGS | 12,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400,678 | 88.4% |
| LOAD_GLOBAL_MODULE | 40,076 | 8.8% |
| LOAD_FAST | 12,000 | 2.6% |
| LOAD_GLOBAL | 620 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,681,811 | 52.3% |
| LOAD_ATTR | 669,066 | 20.8% |
| LOAD_FAST | 468,487 | 14.6% |
| LOAD_DEREF | 204,500 | 6.4% |
| RETURN_VALUE | 132,080 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,361,292 | 42.3% |
| CALL | 731,352 | 22.7% |
| LOAD_FAST_LOAD_FAST | 713,191 | 22.2% |
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
| LOAD_FAST | 3,170,348 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,691,169 | 23.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 622,560 | 5.4% |
| CALL | 621,723 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 3,736,529 | 32.3% |
| STORE_FAST | 2,136,079 | 18.5% |
| TO_BOOL_BOOL | 1,887,209 | 16.3% |
| RETURN_VALUE | 973,720 | 8.4% |
| LOAD_FAST | 604,330 | 5.2% |


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
| LOAD_FAST | 559,773 | 44.2% |
| LOAD_ATTR_INSTANCE_VALUE | 521,110 | 41.2% |
| LOAD_ATTR | 122,800 | 9.7% |
| COPY | 36,800 | 2.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,380 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,055,950 | 83.4% |
| POP_JUMP_IF_TRUE | 196,237 | 15.5% |
| TO_BOOL | 5,853 | 0.5% |
| TO_BOOL_BOOL | 5,200 | 0.4% |
| TO_BOOL_NONE | 1,066 | 0.1% |


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
| LOAD_GLOBAL_MODULE | 187,621 | 17.2% |
| LOAD_CONST | 169,957 | 15.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 155,880 | 14.3% |
| LOAD_FAST | 113,370 | 10.4% |
| LOAD_ATTR_CLASS | 96,080 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 269,894 | 24.7% |
| STORE_FAST | 208,256 | 19.1% |
| COPY | 134,323 | 12.3% |
| LOAD_FAST | 96,640 | 8.8% |
| RETURN_VALUE | 96,120 | 8.8% |


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
| STORE_FAST | 111,850 | 12.6% |
| LOAD_FAST_LOAD_FAST | 107,540 | 12.1% |
| RESUME_CHECK | 72,940 | 8.2% |
| SWAP | 49,440 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 662,910 | 74.7% |
| STORE_FAST | 137,481 | 15.5% |
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
| LOAD_FAST | 512,498 | 36.9% |
| LOAD_FAST_LOAD_FAST | 384,540 | 27.7% |
| LOAD_GLOBAL_BUILTIN | 156,660 | 11.3% |
| LOAD_GLOBAL_MODULE | 99,540 | 7.2% |
| LOAD_ATTR_MODULE | 71,940 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 191,840 | 13.8% |
| RETURN_VALUE | 180,760 | 13.0% |
| LOAD_CONST | 160,581 | 11.6% |
| CALL_ISINSTANCE | 157,200 | 11.3% |
| CONTAINS_OP | 121,400 | 8.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,006,200 | 32.1% |
| PUSH_NULL | 731,352 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 613,100 | 9.8% |
| LOAD_GLOBAL_MODULE | 590,069 | 9.4% |
| LOAD_CONST | 468,294 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,947,264 | 31.1% |
| POP_TOP | 990,351 | 15.8% |
| LOAD_FAST | 825,263 | 13.2% |
| RETURN_VALUE | 621,723 | 9.9% |
| BINARY_SUBSCR_DICT | 420,140 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 480,760 | 44.5% |
| ENTER_EXECUTOR | 363,697 | 33.7% |
| LOAD_FAST | 100,556 | 9.3% |
| CALL_INTRINSIC_1 | 76,230 | 7.1% |
| BUILD_MAP | 59,200 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 500,067 | 46.3% |
| RETURN_VALUE | 221,276 | 20.5% |
| RESUME_CHECK | 132,220 | 12.2% |
| STORE_FAST | 119,360 | 11.0% |
| CALL | 83,300 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 290,090 | 96.0% |
| RERAISE | 12,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 154,660 | 51.2% |
| CALL_FUNCTION_EX | 76,230 | 25.2% |
| LOAD_CONST | 59,200 | 19.6% |
| RERAISE | 12,000 | 4.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 403,376 | 87.1% |
| ENTER_EXECUTOR | 59,680 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 265,420 | 57.3% |
| STORE_FAST | 100,356 | 21.7% |
| COPY_FREE_VARS | 24,000 | 5.2% |
| RETURN_VALUE | 12,440 | 2.7% |
| LOAD_FAST | 12,180 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 119,589 | 64.6% |
| LOAD_ATTR | 24,440 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,340 | 6.7% |
| LOAD_FAST_LOAD_FAST | 12,000 | 6.5% |
| LOAD_ATTR_CLASS | 12,000 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120,546 | 65.1% |
| POP_JUMP_IF_TRUE | 60,580 | 32.7% |
| COMPARE_OP | 1,926 | 1.0% |
| COMPARE_OP_INT | 1,449 | 0.8% |
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
| LOAD_FAST_LOAD_FAST | 108,880 | 13.6% |

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
| LOAD_FAST | 1,117,391 | 46.6% |
| LOAD_CONST | 252,200 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 227,980 | 9.5% |
| BINARY_OP | 134,323 | 5.6% |
| CONTAINS_OP | 120,040 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 924,391 | 38.5% |
| LOAD_FAST | 456,000 | 19.0% |
| TO_BOOL_BOOL | 326,140 | 13.6% |
| TO_BOOL_NONE | 190,729 | 8.0% |
| TO_BOOL_INT | 162,604 | 6.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 288,546 | 36.9% |
| CACHE | 238,098 | 30.5% |
| CALL | 120,900 | 15.5% |
| LOAD_ATTR_PROPERTY | 83,920 | 10.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 25,996 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 732,240 | 93.7% |
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
| POP_TOP | 16,236 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 108,000 | 51.8% |
| RETURN_CONST | 48,000 | 23.0% |
| LOAD_FAST | 28,236 | 13.6% |
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
| POP_TOP | 704,288 | 57.4% |
| POP_JUMP_IF_TRUE | 127,578 | 10.4% |
| CALL_LIST_APPEND | 98,402 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 83,660 | 6.8% |
| EXTENDED_ARG | 60,080 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 363,697 | 29.6% |
| FOR_ITER_LIST | 231,715 | 18.9% |
| CALL | 225,720 | 18.4% |
| RESUME_CHECK | 102,686 | 8.4% |
| POP_JUMP_IF_FALSE | 94,172 | 7.7% |


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
| ENTER_EXECUTOR | 60,080 | 29.1% |
| POP_JUMP_IF_FALSE | 24,680 | 12.0% |
| JUMP_FORWARD | 12,340 | 6.0% |
| JUMP_BACKWARD | 560 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 157,981 | 44.2% |
| GET_ITER | 148,039 | 41.4% |
| SWAP | 24,460 | 6.8% |
| LOAD_FAST | 24,200 | 6.8% |
| FOR_ITER | 2,320 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 134,899 | 37.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 108,280 | 30.3% |
| STORE_FAST | 49,481 | 13.8% |
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
| POP_TOP | 219,640 | 56.8% |
| FOR_ITER_LIST | 108,200 | 28.0% |
| STORE_SUBSCR | 36,020 | 9.3% |
| POP_JUMP_IF_TRUE | 14,740 | 3.8% |
| POP_JUMP_IF_FALSE | 2,220 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 215,960 | 55.8% |
| FOR_ITER | 157,981 | 40.8% |
| FOR_ITER_LIST | 6,459 | 1.7% |
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
| STORE_FAST | 446,309 | 59.7% |
| POP_TOP | 132,480 | 17.7% |
| STORE_ATTR_INSTANCE_VALUE | 48,351 | 6.5% |
| POP_JUMP_IF_TRUE | 24,400 | 3.3% |
| STORE_ATTR | 24,120 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 479,816 | 64.2% |
| LOAD_CONST | 92,214 | 12.3% |
| LOAD_FAST_LOAD_FAST | 60,340 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 42,142 | 5.6% |
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
| LOAD_ATTR_SLOT | 15,870 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 11,980 | 3.8% |
| LOAD_DEREF | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 290,090 | 92.4% |
| LOAD_FAST | 24,000 | 7.6% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,601,411 | 64.5% |
| LOAD_ATTR_INSTANCE_VALUE | 872,716 | 15.6% |
| LOAD_ATTR_WITH_HINT | 335,900 | 6.0% |
| LOAD_GLOBAL_MODULE | 303,620 | 5.4% |
| LOAD_DEREF | 151,678 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,177,628 | 21.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 894,098 | 16.0% |
| PUSH_NULL | 669,066 | 12.0% |
| LOAD_CONST | 483,080 | 8.6% |
| CALL_PY_EXACT_ARGS | 321,936 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,337,646 | 20.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,673,088 | 10.5% |
| LOAD_CONST | 1,081,397 | 6.8% |
| POP_JUMP_IF_FALSE | 1,072,205 | 6.7% |
| STORE_ATTR_SLOT | 1,047,758 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,157,347 | 32.2% |
| COMPARE_OP_INT | 1,716,983 | 10.7% |
| STORE_FAST | 1,220,741 | 7.6% |
| LOAD_CONST | 1,081,397 | 6.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 634,620 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 401,349 | 19.2% |
| RESUME_CHECK | 207,389 | 9.9% |
| POP_JUMP_IF_FALSE | 171,409 | 8.2% |
| POP_JUMP_IF_TRUE | 144,340 | 6.9% |
| NOP | 134,742 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,920 | 24.2% |
| LOAD_ATTR_INSTANCE_VALUE | 368,307 | 17.6% |
| PUSH_NULL | 204,500 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 155,680 | 7.4% |
| LOAD_ATTR | 151,678 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,358,283 | 15.3% |
| POP_JUMP_IF_FALSE | 7,419,178 | 10.0% |
| STORE_FAST | 6,668,191 | 9.0% |
| LOAD_CONST | 5,157,347 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 5,156,942 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,802,799 | 29.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,984,937 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 4,942,297 | 6.7% |
| LOAD_ATTR | 3,601,411 | 4.9% |
| CALL_PY_EXACT_ARGS | 3,350,239 | 4.5% |


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
| LOAD_ATTR_METHOD_NO_DICT | 15,389 | 38.5% |
| POP_JUMP_IF_FALSE | 12,000 | 30.0% |
| STORE_FAST | 12,000 | 30.0% |
| POP_TOP | 320 | 0.8% |
| JUMP_FORWARD | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 15,289 | 38.2% |
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
| STORE_ATTR_SLOT | 1,303,887 | 12.7% |
| LOAD_GLOBAL_MODULE | 1,093,580 | 10.7% |
| STORE_FAST | 1,064,063 | 10.4% |
| STORE_ATTR_INSTANCE_VALUE | 997,280 | 9.7% |
| POP_JUMP_IF_FALSE | 901,060 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,992,571 | 19.4% |
| STORE_ATTR_SLOT | 1,797,656 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,280,743 | 12.5% |
| LOAD_FAST | 875,165 | 8.5% |
| LOAD_FAST_LOAD_FAST | 734,489 | 7.2% |


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
| MAKE_CELL | 187,298 | 51.6% |
| CALL_PY_EXACT_ARGS | 114,869 | 31.6% |
| COPY_FREE_VARS | 24,100 | 6.6% |
| CACHE | 12,360 | 3.4% |
| CALL | 12,320 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 187,298 | 51.6% |
| RESUME_CHECK | 163,349 | 45.0% |
| RETURN_GENERATOR | 12,000 | 3.3% |
| RESUME | 520 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,375,978 | 45.3% |
| COMPARE_OP_INT | 2,676,216 | 19.0% |
| TO_BOOL_NONE | 1,214,804 | 8.6% |
| TO_BOOL | 1,055,950 | 7.5% |
| CONTAINS_OP | 605,540 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,419,178 | 52.8% |
| RETURN_CONST | 1,484,844 | 10.6% |
| LOAD_CONST | 1,072,205 | 7.6% |
| LOAD_GLOBAL_MODULE | 1,008,437 | 7.2% |
| LOAD_FAST_LOAD_FAST | 901,060 | 6.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,035,556 | 56.1% |
| LOAD_FAST | 2,039,679 | 37.7% |
| LOAD_ATTR | 132,960 | 2.5% |
| LOAD_DEREF | 132,080 | 2.4% |
| LOAD_ATTR_WITH_HINT | 34,964 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,469,970 | 82.6% |
| RETURN_CONST | 279,569 | 5.2% |
| LOAD_GLOBAL_MODULE | 276,580 | 5.1% |
| LOAD_FAST_LOAD_FAST | 144,440 | 2.7% |
| NOP | 132,300 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,047,274 | 62.7% |
| LOAD_ATTR_INSTANCE_VALUE | 444,360 | 26.6% |
| LOAD_ATTR | 108,980 | 6.5% |
| ENTER_EXECUTOR | 19,223 | 1.2% |
| LOAD_GLOBAL_MODULE | 12,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 587,825 | 35.2% |
| LOAD_FAST_LOAD_FAST | 435,369 | 26.1% |
| LOAD_GLOBAL_MODULE | 343,923 | 20.6% |
| LOAD_CONST | 132,200 | 7.9% |
| LOAD_DEREF | 84,280 | 5.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,222,061 | 54.8% |
| COMPARE_OP_INT | 708,520 | 17.5% |
| TO_BOOL_INT | 241,333 | 6.0% |
| TO_BOOL_STR | 240,200 | 5.9% |
| TO_BOOL_NONE | 203,855 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,900,090 | 46.9% |
| LOAD_GLOBAL_BUILTIN | 449,420 | 11.1% |
| NOP | 274,972 | 6.8% |
| LOAD_CONST | 233,422 | 5.8% |
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
| POP_TOP | 2,937,651 | 37.3% |
| POP_JUMP_IF_FALSE | 1,484,844 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 760,585 | 9.6% |
| STORE_ATTR_SLOT | 613,149 | 7.8% |
| STORE_FAST | 395,197 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,199,560 | 65.9% |
| INTERPRETER_EXIT | 1,712,305 | 21.7% |
| EXIT_INIT_CHECK | 324,640 | 4.1% |
| STORE_FAST | 176,383 | 2.2% |
| TO_BOOL_BOOL | 132,319 | 1.7% |


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
| MAKE_FUNCTION | 160,961 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 51,649 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 71,412 | 33.6% |
| SET_FUNCTION_ATTRIBUTE | 51,649 | 24.3% |
| CALL | 39,389 | 18.5% |
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
| RETURN_VALUE | 2,136,079 | 19.7% |
| CALL | 1,947,264 | 18.0% |
| LOAD_CONST | 1,220,741 | 11.3% |
| CALL_BUILTIN_FAST | 814,460 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 707,875 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,668,191 | 61.6% |
| LOAD_FAST_LOAD_FAST | 1,064,063 | 9.8% |
| LOAD_CONST | 587,107 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 483,650 | 4.5% |
| JUMP_FORWARD | 446,309 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 714,701 | 73.8% |
| UNPACK_SEQUENCE_LIST | 119,960 | 12.4% |
| UNPACK_SEQUENCE_TUPLE | 72,300 | 7.5% |
| COPY | 24,200 | 2.5% |
| STORE_FAST_STORE_FAST | 24,160 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 534,221 | 55.2% |
| LOAD_GLOBAL_MODULE | 131,880 | 13.6% |
| STORE_FAST | 96,460 | 10.0% |
| LOAD_FAST_LOAD_FAST | 84,820 | 8.8% |
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
| BINARY_OP_ADD_INT | 567,296 | 41.0% |
| BINARY_OP_SUBTRACT_INT | 333,375 | 24.1% |
| LOAD_FAST | 192,300 | 13.9% |
| LOAD_ATTR | 57,216 | 4.1% |
| BUILD_LIST | 49,440 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 924,391 | 66.9% |
| COPY | 108,300 | 7.8% |
| STORE_FAST | 93,996 | 6.8% |
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
| LOAD_ATTR_INSTANCE_VALUE | 15,570 | 12.8% |
| LOAD_ATTR | 11,960 | 9.8% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,160 | 58.4% |
| LOAD_GLOBAL_MODULE | 35,080 | 28.8% |
| STORE_FAST | 15,590 | 12.8% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 675,956 | 62.4% |
| LOAD_FAST_LOAD_FAST | 263,840 | 24.3% |
| CALL_LEN | 83,960 | 7.7% |
| LOAD_CONST | 59,760 | 5.5% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 567,296 | 52.3% |
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
| RETURN_VALUE | 11,960 | 92.0% |
| LOAD_CONST | 997 | 7.7% |
| BINARY_OP | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,980 | 92.2% |
| CALL_BUILTIN_O | 997 | 7.7% |
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
| RETURN_VALUE | 60,157 | 65.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,960 | 13.0% |
| LOAD_ATTR_WITH_HINT | 11,960 | 13.0% |
| CALL | 7,763 | 8.4% |
| BINARY_OP | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 59,180 | 64.3% |
| RETURN_VALUE | 11,980 | 13.0% |
| LOAD_FAST | 11,980 | 13.0% |
| STORE_FAST | 8,800 | 9.6% |
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
| LOAD_CONST | 33,455 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 333,375 | 39.8% |
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
| LOAD_FAST | 350,482 | 38.8% |
| BUILD_TUPLE | 48,080 | 5.3% |
| LOAD_FAST_LOAD_FAST | 36,020 | 4.0% |
| RETURN_VALUE | 23,980 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 432,040 | 47.8% |
| PUSH_EXC_INFO | 348,440 | 38.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 38,102 | 4.2% |
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
| LOAD_CONST | 51,625 | 67.5% |
| BINARY_SUBSCR | 12,300 | 16.1% |
| BINARY_OP_SUBTRACT_INT | 11,960 | 15.6% |
| LOAD_FAST | 580 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,240 | 31.7% |
| LOAD_ATTR_SLOT | 21,194 | 27.7% |
| STORE_FAST | 15,409 | 20.2% |
| LOAD_CONST | 11,980 | 15.7% |
| TO_BOOL_BOOL | 2,422 | 3.2% |


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
| LOAD_FAST | 84,819 | 28.9% |
| LOAD_FAST_LOAD_FAST | 48,448 | 16.5% |
| BINARY_SLICE | 23,960 | 8.2% |
| CALL_BUILTIN_CLASS | 23,960 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 156,586 | 53.3% |
| POP_TOP | 108,260 | 36.9% |
| COPY_FREE_VARS | 25,996 | 8.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,060 | 0.7% |
| CALL_PY_EXACT_ARGS | 477 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 71,960 | 29.1% |
| LOAD_FAST | 39,830 | 16.1% |
| CALL | 36,480 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 36,160 | 14.6% |
| LOAD_GLOBAL_MODULE | 14,102 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,500 | 39.1% |
| LOAD_FAST | 36,200 | 14.7% |
| RETURN_VALUE | 35,980 | 14.6% |
| GET_ITER | 29,832 | 12.1% |
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
| LOAD_ATTR | 14,929 | 53.2% |
| LOAD_FAST | 12,620 | 45.0% |
| LOAD_CONST | 300 | 1.1% |
| CALL_STR_1 | 80 | 0.3% |
| CALL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,969 | 53.3% |
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
| LOAD_FAST | 49,091 | 86.6% |
| LOAD_ATTR_INSTANCE_VALUE | 5,238 | 9.2% |
| BINARY_OP_MULTIPLY_FLOAT | 997 | 1.8% |
| BUILD_TUPLE | 360 | 0.6% |
| CALL | 220 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 23,920 | 42.2% |
| STORE_FAST | 17,318 | 30.5% |
| BINARY_SUBSCR_DICT | 11,960 | 21.1% |
| POP_TOP | 1,611 | 2.8% |
| LOAD_CONST | 1,017 | 1.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,132,808 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 437,120 | 20.9% |
| LOAD_ATTR_MODULE | 298,800 | 14.3% |
| BUILD_TUPLE | 157,200 | 7.5% |
| LOAD_ATTR | 59,960 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,881,748 | 90.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 327,893 | 32.7% |
| LOAD_GLOBAL_MODULE | 12,080 | 1.2% |
| BINARY_SUBSCR | 12,060 | 1.2% |
| CALL | 640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 303,423 | 30.3% |
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
| LOAD_FAST | 138,998 | 54.1% |
| BUILD_TUPLE | 65,216 | 25.4% |
| ENTER_EXECUTOR | 27,869 | 10.9% |
| RETURN_VALUE | 24,040 | 9.4% |
| CALL | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120,260 | 46.8% |
| ENTER_EXECUTOR | 98,402 | 38.3% |
| LOAD_FAST | 24,120 | 9.4% |
| NOP | 12,021 | 4.7% |
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
| LOAD_FAST | 20,947 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 622,560 | 65.0% |
| CALL_PY_EXACT_ARGS | 108,040 | 11.3% |
| STORE_FAST | 93,367 | 9.8% |
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
| LOAD_FAST_LOAD_FAST | 15,570 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 268,170 | 37.6% |
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
| LOAD_ATTR | 894,098 | 59.1% |
| LOAD_ATTR_METHOD_NO_DICT | 567,175 | 37.5% |
| LOAD_FAST | 24,040 | 1.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 11,960 | 0.8% |
| ENTER_EXECUTOR | 11,680 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 927,429 | 61.3% |
| POP_TOP | 152,323 | 10.1% |
| GET_ITER | 144,140 | 9.5% |
| LOAD_FAST | 72,200 | 4.8% |
| STORE_FAST | 67,119 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 554,833 | 56.6% |
| BUILD_TUPLE | 191,840 | 19.6% |
| LOAD_ATTR_INSTANCE_VALUE | 84,120 | 8.6% |
| LOAD_CONST | 48,400 | 4.9% |
| CALL | 36,880 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 807,593 | 82.3% |
| STORE_FAST | 99,340 | 10.1% |
| LOAD_CONST | 24,300 | 2.5% |
| UNPACK_SEQUENCE_TUPLE | 24,080 | 2.5% |
| PUSH_EXC_INFO | 12,069 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,461,593 | 41.0% |
| LOAD_FAST | 3,350,239 | 30.8% |
| LOAD_FAST_LOAD_FAST | 661,054 | 6.1% |
| LOAD_CONST | 576,140 | 5.3% |
| LOAD_ATTR | 321,936 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,203,420 | 93.8% |
| COPY_FREE_VARS | 288,546 | 2.7% |
| RETURN_GENERATOR | 264,140 | 2.4% |
| MAKE_CELL | 114,869 | 1.1% |
| TO_BOOL_BOOL | 4,580 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 143,680 | 25.3% |
| LOAD_FAST | 131,980 | 23.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 124,036 | 21.8% |
| PUSH_NULL | 72,040 | 12.7% |
| LOAD_ATTR | 35,920 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 556,596 | 97.9% |
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
| LOAD_ATTR_SLOT | 333,939 | 93.3% |
| LOAD_FAST | 15,229 | 4.3% |
| LOAD_GLOBAL_MODULE | 8,547 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 333,959 | 93.3% |
| POP_JUMP_IF_FALSE | 23,896 | 6.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,716,983 | 50.4% |
| LOAD_ATTR_INSTANCE_VALUE | 953,923 | 28.0% |
| LOAD_ATTR_CLASS | 383,960 | 11.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 119,920 | 3.5% |
| COPY | 108,180 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,676,216 | 78.5% |
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
| GET_ITER | 404,312 | 61.6% |
| ENTER_EXECUTOR | 231,715 | 35.3% |
| SWAP | 12,460 | 1.9% |
| JUMP_BACKWARD | 6,459 | 1.0% |
| FOR_ITER | 780 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 232,051 | 35.4% |
| LOAD_FAST | 195,830 | 29.8% |
| JUMP_BACKWARD | 108,200 | 16.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,083 | 4.6% |
| RETURN_CONST | 27,891 | 4.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 29,832 | 50.6% |
| ENTER_EXECUTOR | 27,650 | 46.9% |
| JUMP_BACKWARD | 1,260 | 2.1% |
| FOR_ITER | 100 | 0.2% |
| SWAP | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,752 | 52.2% |
| LOAD_CONST | 15,610 | 26.5% |
| RETURN_CONST | 12,000 | 20.4% |
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
| LOAD_FAST | 21,802,799 | 86.6% |
| LOAD_FAST_LOAD_FAST | 1,280,743 | 5.1% |
| COPY | 924,391 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 791,180 | 3.1% |
| LOAD_DEREF | 368,307 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,181,774 | 16.6% |
| POP_JUMP_IF_NONE | 3,035,556 | 12.1% |
| RETURN_VALUE | 2,691,169 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 2,255,200 | 9.0% |
| TO_BOOL_BOOL | 2,249,333 | 8.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 2,255,200 | 52.3% |
| LOAD_FAST | 1,158,234 | 26.9% |
| BINARY_SLICE | 251,960 | 5.8% |
| LOAD_CONST | 132,180 | 3.1% |
| STORE_FAST_LOAD_FAST | 108,640 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,868,218 | 43.3% |
| LOAD_CONST | 813,234 | 18.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 567,175 | 13.2% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 227,960 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 204,040 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,984,937 | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,743,614 | 19.9% |
| LOAD_ATTR_SLOT | 588,929 | 6.7% |
| LOAD_DEREF | 122,969 | 1.4% |
| LOAD_FAST_LOAD_FAST | 107,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,461,593 | 50.9% |
| LOAD_FAST | 2,768,477 | 31.6% |
| LOAD_FAST_LOAD_FAST | 675,129 | 7.7% |
| LOAD_CONST | 431,980 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 143,180 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,048,021 | 99.5% |
| LOAD_ATTR_MODULE | 11,960 | 0.4% |
| LOAD_ATTR | 2,940 | 0.1% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,681,811 | 54.9% |
| LOAD_ATTR_CLASS | 455,800 | 14.9% |
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
| LOAD_FAST | 2,590,561 | 94.2% |
| BINARY_SUBSCR_TUPLE_INT | 120,040 | 4.4% |
| BINARY_SUBSCR_LIST_INT | 21,194 | 0.8% |
| LOAD_DEREF | 11,960 | 0.4% |
| LOAD_ATTR_SLOT | 5,532 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 855,898 | 31.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 588,929 | 21.4% |
| LOAD_FAST | 350,805 | 12.8% |
| COMPARE_OP_FLOAT | 333,939 | 12.1% |
| TO_BOOL_BOOL | 290,494 | 10.6% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 763,683 | 99.9% |
| LOAD_ATTR | 660 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 309 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 335,900 | 43.9% |
| LOAD_CONST | 95,960 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,764 | 10.8% |
| LOAD_ATTR_METHOD_NO_DICT | 59,960 | 7.8% |
| RETURN_VALUE | 35,980 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,794,340 | 40.1% |
| LOAD_FAST | 797,440 | 11.4% |
| POP_JUMP_IF_FALSE | 640,697 | 9.2% |
| STORE_FAST | 483,650 | 6.9% |
| POP_JUMP_IF_TRUE | 449,420 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,156,942 | 74.0% |
| CALL_ISINSTANCE | 437,120 | 6.3% |
| LOAD_DEREF | 401,349 | 5.8% |
| CHECK_EXC_MATCH | 390,994 | 5.6% |
| BUILD_TUPLE | 156,660 | 2.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,177,906 | 20.6% |
| RESUME_CHECK | 1,968,196 | 18.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,043,920 | 9.9% |
| POP_JUMP_IF_FALSE | 1,008,437 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 785,378 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,048,021 | 28.9% |
| LOAD_FAST | 2,138,378 | 20.3% |
| CALL_ISINSTANCE | 1,132,808 | 10.7% |
| LOAD_FAST_LOAD_FAST | 1,093,580 | 10.4% |
| CALL | 590,069 | 5.6% |


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
| CALL_PY_EXACT_ARGS | 10,203,420 | 52.1% |
| CACHE | 5,377,556 | 27.5% |
| COPY_FREE_VARS | 732,240 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 556,596 | 2.8% |
| BINARY_SUBSCR_GETITEM | 492,660 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,358,283 | 58.0% |
| LOAD_GLOBAL_BUILTIN | 2,794,340 | 14.3% |
| LOAD_GLOBAL_MODULE | 1,968,196 | 10.1% |
| NOP | 1,203,515 | 6.1% |
| LOAD_CONST | 652,009 | 3.3% |


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
| LOAD_FAST | 4,942,297 | 60.9% |
| LOAD_FAST_LOAD_FAST | 1,992,571 | 24.5% |
| SWAP | 924,391 | 11.4% |
| LOAD_DEREF | 155,680 | 1.9% |
| STORE_FAST_LOAD_FAST | 83,920 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,813,556 | 34.7% |
| LOAD_CONST | 1,673,088 | 20.6% |
| LOAD_FAST_LOAD_FAST | 997,280 | 12.3% |
| LOAD_GLOBAL_MODULE | 785,378 | 9.7% |
| RETURN_CONST | 760,585 | 9.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,797,656 | 49.9% |
| LOAD_FAST | 1,791,709 | 49.7% |
| STORE_ATTR_SLOT | 12,990 | 0.4% |
| STORE_ATTR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,303,887 | 36.2% |
| LOAD_CONST | 1,047,758 | 29.1% |
| LOAD_FAST | 618,387 | 17.2% |
| RETURN_CONST | 613,149 | 17.0% |
| STORE_ATTR_SLOT | 12,990 | 0.4% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,881 | 79.4% |
| LOAD_FAST_LOAD_FAST | 11,960 | 20.3% |
| STORE_ATTR_INSTANCE_VALUE | 103 | 0.2% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,920 | 81.2% |
| RETURN_CONST | 11,004 | 18.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 2,249,333 | 25.8% |
| RETURN_VALUE | 1,887,209 | 21.6% |
| CALL_ISINSTANCE | 1,881,748 | 21.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 927,429 | 10.6% |
| LOAD_FAST | 402,226 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,375,978 | 73.0% |
| POP_JUMP_IF_TRUE | 2,222,061 | 25.5% |
| EXTENDED_ARG | 119,920 | 1.4% |
| UNARY_NOT | 11,980 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 324,520 | 42.1% |
| BINARY_OP | 269,894 | 35.1% |
| COPY | 162,604 | 21.1% |
| LOAD_ATTR | 11,960 | 1.6% |
| TO_BOOL | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 528,459 | 68.6% |
| POP_JUMP_IF_TRUE | 241,333 | 31.3% |
| TO_BOOL_NONE | 106 | 0.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 145,304 | 99.0% |
| LOAD_FAST | 720 | 0.5% |
| STORE_FAST_LOAD_FAST | 540 | 0.4% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 145,784 | 99.3% |
| POP_JUMP_IF_TRUE | 940 | 0.6% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 855,898 | 60.3% |
| COPY | 190,729 | 13.4% |
| LOAD_FAST | 190,030 | 13.4% |
| LOAD_ATTR | 83,800 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 72,040 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,214,804 | 85.6% |
| POP_JUMP_IF_TRUE | 203,855 | 14.4% |
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
| BINARY_SUBSCR | 180,200 | 24.8% |
| RETURN_VALUE | 156,480 | 21.5% |
| FOR_ITER | 108,280 | 14.9% |
| YIELD_VALUE | 107,960 | 14.8% |
| STORE_FAST | 57,036 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 714,701 | 98.3% |
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
|     deferred | 1,083,976 | 31.1% |
|          hit | 2,389,138 | 68.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 960 | 10.8% |
| Failure | 7,897 | 89.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,474 | 44.0% |
| add other | 1,420 | 18.0% |
| or | 1,240 | 15.7% |
| remainder | 880 | 11.1% |
| add different types | 480 | 6.1% |
| floor divide | 180 | 2.3% |
| true divide other | 140 | 1.8% |
| multiply different types | 83 | 1.1% |


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
|     deferred | 339,000 | 15.7% |
|          hit | 1,811,427 | 84.1% |
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
|     deferred | 6,198,701 | 22.0% |
|          hit | 21,583,341 | 76.5% |
|         miss | 364,511 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,449 | 41.4% |
| Failure | 31,778 | 58.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 6,345 | 20.0% |
| class no vectorcall | 5,460 | 17.2% |
| meth descr method fastcall keywords | 3,860 | 12.1% |
| cfunc noargs | 3,463 | 10.9% |
| meth descr varargs | 3,025 | 9.5% |
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
|     deferred | 181,297 | 4.3% |
|          hit | 4,043,543 | 95.6% |
|         miss | 1,177 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,969 | 50.4% |
| Failure | 1,935 | 49.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 480 | 24.8% |
| bytes | 360 | 18.6% |
| other | 340 | 17.6% |
| float long | 315 | 16.3% |
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
|     deferred | 354,100 | 24.4% |
|          hit | 1,091,508 | 75.3% |

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
|     deferred | 5,511,946 | 10.7% |
|          hit | 45,625,111 | 88.3% |
|         miss | 455,006 | 0.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,409 | 49.9% |
| Failure | 37,602 | 50.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 8,180 | 21.8% |
| method | 8,074 | 21.5% |
| not managed dict | 7,088 | 18.9% |
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
|          hit | 17,516,089 | 99.8% |
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
|     deferred | 263,747 | 2.2% |
|          hit | 11,074,187 | 91.8% |
|         miss | 706,151 | 5.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 21,253 | 83.8% |
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
|     deferred | 1,251,691 | 9.9% |
|          hit | 11,368,948 | 89.7% |
|         miss | 34,542 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,892 | 56.6% |
| Failure | 6,043 | 43.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 1,880 | 31.1% |
| bytes | 1,100 | 18.2% |
| float | 960 | 15.9% |
| dict | 620 | 10.3% |
| mapping | 523 | 8.7% |
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
|          hit | 931,341 | 98.5% |

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
| Basic | 176,821,707 | 49.4% |
| Not specialized | 41,750,382 | 11.7% |
| Specialized hits | 137,989,309 | 38.5% |
| Specialized misses | 1,569,229 | 0.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,198,701 | 39.3% |
| LOAD_ATTR | 5,511,946 | 34.9% |
| TO_BOOL | 1,251,691 | 7.9% |
| BINARY_OP | 1,083,976 | 6.9% |
| FOR_ITER | 354,100 | 2.2% |
| BINARY_SUBSCR | 339,000 | 2.1% |
| SEND | 336,200 | 2.1% |
| STORE_ATTR | 263,747 | 1.7% |
| STORE_SUBSCR | 240,780 | 1.5% |
| COMPARE_OP | 181,297 | 1.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 694,512 | 44.2% |
| LOAD_ATTR_SLOT | 296,050 | 18.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 137,212 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 124,923 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,577 | 5.3% |
| CALL_PY_EXACT_ARGS | 65,296 | 4.2% |
| CALL_METHOD_DESCRIPTOR_O | 36,840 | 2.3% |
| LOAD_ATTR_METHOD_NO_DICT | 28,242 | 1.8% |
| TO_BOOL_NONE | 22,237 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 19,467 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 5,739,094 | 29.0% |
| Calls to Python functions inlined | 14,074,232 | 71.0% |
| Calls via PyEval_EvalFrame (total) | 5,739,094 | 29.0% |
| Calls via PyEval_EvalFrame (vector) | 5,388,514 | 27.2% |
| Calls via PyEval_EvalFrame (generator) | 350,580 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 5,388,214 | 27.2% |
| Calls via PyEval_EvalFrame (build class) | 220 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 1,096,499 | 5.5% |
| Calls via PyEval_EvalFrame (function ex) | 132,520 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 206,300 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 915,529 | 4.6% |
| Frame objects created | 824,400 | 4.2% |
| Frames pushed | 13,465,165 | 68.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,853,007 | 40.0% |
| Frees to freelist | 11,907,433 |  |
| Allocations | 17,746,555 | 60.0% |
| Allocations to 512 bytes | 17,422,778 | 58.9% |
| Allocations to 4 kbytes | 90,921 | 0.3% |
| Allocations over 4 kbytes | 232,856 | 0.8% |
| Frees | 18,011,983 |  |
| New values | 158,420 |  |
| Interpreter increfs | 187,139,064 | 77.2% |
| Interpreter decrefs | 202,546,639 | 75.0% |
| Increfs | 55,253,057 | 22.8% |
| Decrefs | 67,657,902 | 25.0% |
| Materialize dict (on request) | 200 | 0.1% |
| Materialize dict (new key) | 24,000 | 15.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 140 | 0.1% |
| Method cache hits | 10,286,479 |  |
| Method cache misses | 428,362 |  |
| Method cache collisions | 454,740 |  |
| Method cache dunder hits | 6,858,030 |  |
| Method cache dunder misses | 31,153 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 1,242 | 1,920 | 13,190,672 |
| 1 | 121 | 0 | 4,460,602 |
| 2 | 3 | 99 | 936,438 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,500 |  |
| Traces created | 680 | 45.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 1.3% |
| Trace too long | 0 | 0.0% |
| Trace too short | 820 | 54.7% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 1,226,923 |  |
| Uops executed | 50,601,064 | 41.24 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 5.9% |
| <= 32 | 240 | 35.3% |
| <= 64 | 180 | 26.5% |
| <= 128 | 140 | 20.6% |
| <= 256 | 80 | 11.8% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 11.8% |
| <= 16 | 240 | 35.3% |
| <= 32 | 120 | 17.6% |
| <= 64 | 100 | 14.7% |
| <= 128 | 140 | 20.6% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 192,745 | 15.7% |
| <= 4 | 27,730 | 2.3% |
| <= 8 | 32,083 | 2.6% |
| <= 16 | 270,923 | 22.1% |
| <= 32 | 56,151 | 4.6% |
| <= 64 | 99,497 | 8.1% |
| <= 128 | 542,412 | 44.2% |
| <= 256 | 810 | 0.1% |
| <= 512 | 2,295 | 0.2% |
| <= 1,024 | 1,931 | 0.2% |
| <= 2,048 | 305 | 0.0% |
| <= 4,096 | 20 | 0.0% |
| <= 8,192 | 21 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 6,080,380 | 12.0% | 12.0% |  |
| _CHECK_VALIDITY | 5,729,197 | 11.3% | 23.3% |  |
| LOAD_FAST | 5,339,907 | 10.6% | 33.9% |  |
| _GUARD_TYPE_VERSION | 4,687,379 | 9.3% | 43.2% |  |
| STORE_FAST | 2,010,118 | 4.0% | 47.1% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,605,335 | 3.2% | 50.3% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,605,335 | 3.2% | 53.5% |  |
| _LOAD_ATTR_SLOT | 1,571,662 | 3.1% | 56.6% |  |
| _GUARD_IS_FALSE_POP | 1,300,804 | 2.6% | 59.1% | 4.1% |
| _LOAD_ATTR_METHOD_NO_DICT | 1,140,585 | 2.3% | 61.4% |  |
| TO_BOOL_BOOL | 1,122,742 | 2.2% | 63.6% |  |
| LOAD_CONST | 1,015,902 | 2.0% | 65.6% |  |
| _GUARD_GLOBALS_VERSION | 905,063 | 1.8% | 67.4% | 0.1% |
| _EXIT_TRACE | 803,192 | 1.6% | 69.0% |  |
| _CHECK_PEP_523 | 666,179 | 1.3% | 70.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 666,179 | 1.3% | 71.6% |  |
| _CHECK_STACK_SPACE | 666,179 | 1.3% | 73.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 666,179 | 1.3% | 74.3% |  |
| _PUSH_FRAME | 666,179 | 1.3% | 75.6% |  |
| _SAVE_RETURN_OFFSET | 666,179 | 1.3% | 76.9% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 646,957 | 1.3% | 78.2% | 35.8% |
| _ITER_CHECK_LIST | 646,957 | 1.3% | 79.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 572,399 | 1.1% | 80.6% | 2.0% |
| RESUME_CHECK | 563,433 | 1.1% | 81.7% |  |
| _LOAD_ATTR | 550,465 | 1.1% | 82.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 462,527 | 0.9% | 83.7% | 6.0% |
| _ITER_CHECK_RANGE | 462,527 | 0.9% | 84.6% |  |
| _LOAD_GLOBAL_MODULE | 461,123 | 0.9% | 85.5% |  |
| _GUARD_BUILTINS_VERSION | 442,600 | 0.9% | 86.4% |  |
| _LOAD_GLOBAL_BUILTINS | 442,600 | 0.9% | 87.3% |  |
| _ITER_NEXT_RANGE | 434,877 | 0.9% | 88.1% |  |
| _GUARD_IS_TRUE_POP | 415,370 | 0.8% | 89.0% | 9.7% |
| _ITER_NEXT_LIST | 415,122 | 0.8% | 89.8% |  |
| PUSH_NULL | 387,363 | 0.8% | 90.5% |  |
| BUILD_LIST | 363,697 | 0.7% | 91.3% |  |
| CALL_INTRINSIC_1 | 363,697 | 0.7% | 92.0% |  |
| LIST_EXTEND | 363,697 | 0.7% | 92.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 242,062 | 0.5% | 93.2% |  |
| _GUARD_KEYS_VERSION | 242,062 | 0.5% | 93.7% |  |
| _JUMP_TO_TOP | 233,667 | 0.5% | 94.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 230,382 | 0.5% | 94.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 178,035 | 0.4% | 94.9% |  |
| TO_BOOL_INT | 177,835 | 0.4% | 95.3% |  |
| CALL_ISINSTANCE | 143,220 | 0.3% | 95.6% |  |
| POP_TOP | 135,982 | 0.3% | 95.8% |  |
| COMPARE_OP_INT | 131,560 | 0.3% | 96.1% |  |
| _BINARY_OP | 116,059 | 0.2% | 96.3% |  |
| _TO_BOOL | 115,171 | 0.2% | 96.6% |  |
| CONTAINS_OP | 108,220 | 0.2% | 96.8% |  |
| CALL_LEN | 107,620 | 0.2% | 97.0% |  |
| _GUARD_IS_NOT_NONE_POP | 100,210 | 0.2% | 97.2% | 11.7% |
| COPY | 89,879 | 0.2% | 97.4% |  |
| _BINARY_SUBSCR | 83,680 | 0.2% | 97.5% |  |
| _GUARD_DORV_VALUES | 80,377 | 0.2% | 97.7% |  |
| _STORE_ATTR_INSTANCE_VALUE | 80,377 | 0.2% | 97.8% |  |
| SWAP | 78,568 | 0.2% | 98.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 76,971 | 0.2% | 98.1% |  |
| _CHECK_ATTR_MODULE | 74,928 | 0.1% | 98.3% |  |
| _LOAD_ATTR_MODULE | 74,928 | 0.1% | 98.4% |  |
| _GUARD_IS_NONE_POP | 64,314 | 0.1% | 98.6% | 11.6% |
| _GUARD_NOT_EXHAUSTED_TUPLE | 63,700 | 0.1% | 98.7% | 21.7% |
| _ITER_CHECK_TUPLE | 63,700 | 0.1% | 98.8% |  |
| BUILD_TUPLE | 58,842 | 0.1% | 98.9% |  |
| LOAD_FAST_CHECK | 56,671 | 0.1% | 99.0% |  |
| _ITER_NEXT_TUPLE | 49,860 | 0.1% | 99.1% |  |
| CALL_BUILTIN_FAST | 48,540 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 47,740 | 0.1% | 99.3% | 25.0% |
| _STORE_ATTR_SLOT | 47,358 | 0.1% | 99.4% |  |
| MAKE_CELL | 44,680 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 35,005 | 0.1% | 99.6% |  |
| LOAD_DEREF | 35,000 | 0.1% | 99.7% |  |
| _POP_FRAME | 32,260 | 0.1% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 32,151 | 0.1% | 99.8% |  |
| _GUARD_BOTH_INT | 23,726 | 0.0% | 99.8% |  |
| TO_BOOL_LIST | 23,526 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 23,426 | 0.0% | 99.9% |  |
| _BINARY_OP_SUBTRACT_INT | 23,426 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,680 | 0.0% | 100.0% |  |
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
| FOR_ITER | 460 |
| FOR_ITER_GEN | 360 |
| CALL | 160 |
| CALL_LIST_APPEND | 100 |
| YIELD_VALUE | 40 |
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
