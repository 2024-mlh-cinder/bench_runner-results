
# Pystats results

- benchmark: tornado_http
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 55,482,148 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,848,562 | 7.0% | 27.8% | 0.1% |
| RESUME_CHECK | 14,699,278 | 5.5% | 33.3% | 0.0% |
| LOAD_CONST | 11,948,936 | 4.5% | 37.7% |  |
| POP_JUMP_IF_FALSE | 10,413,168 | 3.9% | 41.6% |  |
| RETURN_VALUE | 8,663,074 | 3.2% | 44.8% |  |
| CALL_PY_EXACT_ARGS | 8,148,582 | 3.0% | 47.9% | 0.6% |
| STORE_FAST | 8,071,732 | 3.0% | 50.9% |  |
| LOAD_GLOBAL_MODULE | 7,910,458 | 3.0% | 53.9% | 0.0% |
| LOAD_FAST_LOAD_FAST | 7,688,425 | 2.9% | 56.7% |  |
| POP_TOP | 7,581,200 | 2.8% | 59.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,561,146 | 2.5% | 62.0% | 0.9% |
| TO_BOOL_BOOL | 6,539,681 | 2.4% | 64.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 6,084,834 | 2.3% | 66.7% | 0.1% |
| RETURN_CONST | 5,917,694 | 2.2% | 68.9% |  |
| LOAD_GLOBAL_BUILTIN | 5,197,929 | 1.9% | 70.9% | 0.0% |
| CALL | 4,722,204 | 1.8% | 72.6% |  |
| INTERPRETER_EXIT | 4,280,887 | 1.6% | 74.2% |  |
| LOAD_ATTR | 4,131,312 | 1.5% | 75.8% |  |
| POP_JUMP_IF_NONE | 4,055,785 | 1.5% | 77.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,245,322 | 1.2% | 78.5% | 0.6% |
| POP_JUMP_IF_TRUE | 3,055,230 | 1.1% | 79.7% |  |
| STORE_ATTR_SLOT | 2,710,850 | 1.0% | 80.7% | 19.1% |
| COMPARE_OP_INT | 2,544,069 | 1.0% | 81.6% | 0.0% |
| PUSH_NULL | 2,406,496 | 0.9% | 82.5% |  |
| LOAD_ATTR_MODULE | 2,306,637 | 0.9% | 83.4% |  |
| NOP | 2,268,709 | 0.8% | 84.2% |  |
| LOAD_ATTR_SLOT | 2,058,027 | 0.8% | 85.0% | 10.8% |
| COPY | 1,793,386 | 0.7% | 85.7% |  |
| LOAD_DEREF | 1,562,242 | 0.6% | 86.2% |  |
| CALL_ISINSTANCE | 1,558,394 | 0.6% | 86.8% |  |
| CALL_BUILTIN_FAST | 1,239,480 | 0.5% | 87.3% |  |
| POP_JUMP_IF_NOT_NONE | 1,233,877 | 0.5% | 87.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,133,450 | 0.4% | 88.2% | 8.3% |
| TO_BOOL_NONE | 1,063,323 | 0.4% | 88.6% | 1.5% |
| BUILD_TUPLE | 1,034,387 | 0.4% | 89.0% |  |
| SWAP | 1,031,416 | 0.4% | 89.3% |  |
| ENTER_EXECUTOR | 949,770 | 0.4% | 89.7% |  |
| TO_BOOL | 930,006 | 0.3% | 90.0% |  |
| BINARY_OP | 817,362 | 0.3% | 90.3% |  |
| BINARY_OP_ADD_INT | 812,260 | 0.3% | 90.7% |  |
| CALL_FUNCTION_EX | 808,057 | 0.3% | 91.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 749,561 | 0.3% | 91.2% | 3.7% |
| CALL_LEN | 738,818 | 0.3% | 91.5% |  |
| STORE_FAST_STORE_FAST | 721,994 | 0.3% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 716,629 | 0.3% | 92.0% |  |
| BINARY_SUBSCR_DICT | 676,787 | 0.3% | 92.3% |  |
| BUILD_LIST | 662,218 | 0.2% | 92.5% |  |
| BINARY_OP_SUBTRACT_INT | 627,107 | 0.2% | 92.8% |  |
| CONTAINS_OP | 595,320 | 0.2% | 93.0% |  |
| BUILD_MAP | 593,580 | 0.2% | 93.2% |  |
| GET_ITER | 588,964 | 0.2% | 93.4% |  |
| TO_BOOL_INT | 588,849 | 0.2% | 93.7% | 0.8% |
| COPY_FREE_VARS | 582,011 | 0.2% | 93.9% |  |
| LOAD_ATTR_WITH_HINT | 575,652 | 0.2% | 94.1% | 2.2% |
| JUMP_FORWARD | 555,482 | 0.2% | 94.3% |  |
| LOAD_ATTR_CLASS | 549,300 | 0.2% | 94.5% | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 541,694 | 0.2% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 534,461 | 0.2% | 94.9% |  |
| YIELD_VALUE | 432,000 | 0.2% | 95.1% |  |
| CALL_PY_WITH_DEFAULTS | 426,520 | 0.2% | 95.2% |  |
| IS_OP | 423,720 | 0.2% | 95.4% |  |
| STORE_SUBSCR_DICT | 423,360 | 0.2% | 95.5% |  |
| BINARY_SLICE | 414,660 | 0.2% | 95.7% |  |
| BINARY_SUBSCR_GETITEM | 369,180 | 0.1% | 95.8% |  |
| DICT_MERGE | 359,220 | 0.1% | 96.0% |  |
| CALL_KW | 345,280 | 0.1% | 96.1% |  |
| GET_AWAITABLE | 342,000 | 0.1% | 96.2% |  |
| POP_EXCEPT | 339,085 | 0.1% | 96.4% |  |
| PUSH_EXC_INFO | 339,085 | 0.1% | 96.5% |  |
| END_SEND | 333,000 | 0.1% | 96.6% |  |
| CHECK_EXC_MATCH | 331,643 | 0.1% | 96.7% |  |
| FOR_ITER_LIST | 312,898 | 0.1% | 96.9% |  |
| MAKE_CELL | 303,996 | 0.1% | 97.0% |  |
| JUMP_BACKWARD | 280,080 | 0.1% | 97.1% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 279,240 | 0.1% | 97.2% | 3.2% |
| MAKE_FUNCTION | 271,720 | 0.1% | 97.3% |  |
| FOR_ITER | 263,938 | 0.1% | 97.4% |  |
| COMPARE_OP_FLOAT | 261,265 | 0.1% | 97.5% |  |
| BINARY_SUBSCR | 253,010 | 0.1% | 97.6% |  |
| SEND | 252,400 | 0.1% | 97.7% |  |
| RETURN_GENERATOR | 252,060 | 0.1% | 97.8% |  |
| EXIT_INIT_CHECK | 243,240 | 0.1% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 243,240 | 0.1% | 97.9% |  |
| LIST_EXTEND | 235,361 | 0.1% | 98.0% |  |
| CALL_INTRINSIC_1 | 226,361 | 0.1% | 98.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 220,752 | 0.1% | 98.2% | 45.6% |
| TO_BOOL_STR | 216,740 | 0.1% | 98.3% | 2.2% |
| SEND_GEN | 216,000 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 207,420 | 0.1% | 98.4% |  |
| FOR_ITER_GEN | 207,000 | 0.1% | 98.5% |  |
| STORE_ATTR | 200,380 | 0.1% | 98.6% |  |
| CALL_LIST_APPEND | 191,726 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 180,580 | 0.1% | 98.7% |  |
| BEFORE_WITH | 173,920 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 171,360 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 171,060 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 156,832 | 0.1% | 99.0% |  |
| DELETE_FAST | 155,860 | 0.1% | 99.0% |  |
| EXTENDED_ARG | 153,180 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 153,180 | 0.1% | 99.1% |  |
| STORE_FAST_LOAD_FAST | 153,060 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 143,820 | 0.1% | 99.3% |  |
| COMPARE_OP | 133,135 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 126,000 | 0.0% | 99.4% |  |
| CALL_BUILTIN_CLASS | 103,948 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 102,636 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 91,601 | 0.0% | 99.5% |  |
| STORE_DEREF | 90,360 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 90,060 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 90,060 | 0.0% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 90,000 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 90,000 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 81,120 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 69,589 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 63,240 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 63,180 | 0.0% | 99.7% |  |
| LOAD_FAST_AND_CLEAR | 54,060 | 0.0% | 99.8% |  |
| BUILD_SLICE | 54,000 | 0.0% | 99.8% |  |
| RERAISE | 54,000 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_LIST_INT | 49,925 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 45,120 | 0.0% | 99.8% |  |
| UNARY_INVERT | 45,120 | 0.0% | 99.8% |  |
| CONVERT_VALUE | 45,120 | 0.0% | 99.9% |  |
| END_FOR | 45,000 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 44,884 | 0.0% | 99.9% | 9.4% |
| CALL_BUILTIN_O | 40,692 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 36,000 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 28,992 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 22,528 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20,052 | 0.0% | 100.0% |  |
| BUILD_STRING | 18,060 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 18,000 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 18,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 9,933 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 9,060 | 0.0% | 100.0% |  |
| UNARY_NOT | 9,000 | 0.0% | 100.0% |  |
| BUILD_SET | 9,000 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 9,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,320 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,324,052 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 8,533,263 | 3.2% | 9.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,644,896 | 2.9% | 12.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,458,086 | 2.0% | 14.2% |
| STORE_FAST LOAD_FAST | 4,972,749 | 1.9% | 16.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,765,444 | 1.8% | 17.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,487,800 | 1.7% | 19.5% |
| CACHE RESUME_CHECK | 4,024,903 | 1.5% | 21.0% |
| RETURN_CONST POP_TOP | 3,910,529 | 1.5% | 22.5% |
| LOAD_CONST LOAD_FAST | 3,872,964 | 1.4% | 23.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,844,461 | 1.4% | 25.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,706,731 | 1.4% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 3,350,653 | 1.3% | 28.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,346,901 | 1.3% | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,127,599 | 1.2% | 30.4% |
| POP_TOP LOAD_FAST | 2,939,114 | 1.1% | 31.5% |
| RETURN_VALUE INTERPRETER_EXIT | 2,795,266 | 1.0% | 32.5% |
| LOAD_FAST LOAD_ATTR | 2,678,375 | 1.0% | 33.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,504,260 | 0.9% | 34.5% |
| LOAD_FAST LOAD_CONST | 2,494,899 | 0.9% | 35.4% |
| LOAD_FAST RETURN_VALUE | 2,374,745 | 0.9% | 36.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,297,040 | 0.9% | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 2,276,176 | 0.9% | 38.0% |
| POP_TOP RETURN_CONST | 2,213,827 | 0.8% | 38.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,108,980 | 0.8% | 39.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,079,821 | 0.8% | 40.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,070,633 | 0.8% | 41.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,016,432 | 0.8% | 41.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,994,760 | 0.7% | 42.7% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,945,373 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,706,549 | 0.6% | 44.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,687,326 | 0.6% | 44.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,675,237 | 0.6% | 45.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,631,284 | 0.6% | 45.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,625,690 | 0.6% | 46.5% |
| RETURN_VALUE STORE_FAST | 1,599,173 | 0.6% | 47.1% |
| CALL STORE_FAST | 1,531,640 | 0.6% | 47.7% |
| LOAD_FAST CALL | 1,531,000 | 0.6% | 48.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,527,385 | 0.6% | 48.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,495,796 | 0.6% | 49.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,471,759 | 0.5% | 49.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,434,764 | 0.5% | 50.5% |
| RETURN_VALUE TO_BOOL_BOOL | 1,413,692 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,411,337 | 0.5% | 51.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,405,074 | 0.5% | 52.0% |
| LOAD_FAST STORE_ATTR_SLOT | 1,354,152 | 0.5% | 52.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,346,928 | 0.5% | 53.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,303,226 | 0.5% | 53.5% |
| LOAD_CONST COMPARE_OP_INT | 1,287,824 | 0.5% | 54.0% |
| RETURN_CONST INTERPRETER_EXIT | 1,278,561 | 0.5% | 54.5% |
| NOP LOAD_FAST | 1,268,188 | 0.5% | 55.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,260,643 | 0.5% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,254,500 | 0.5% | 55.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,111,968 | 0.4% | 56.3% |
| PUSH_NULL LOAD_FAST | 1,016,986 | 0.4% | 56.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 976,896 | 0.4% | 57.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 960,936 | 0.4% | 57.4% |
| RESUME_CHECK NOP | 934,431 | 0.3% | 57.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 910,222 | 0.3% | 58.1% |
| LOAD_CONST STORE_FAST | 903,914 | 0.3% | 58.4% |
| LOAD_ATTR LOAD_FAST | 877,517 | 0.3% | 58.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 869,563 | 0.3% | 59.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 846,454 | 0.3% | 59.4% |
| LOAD_FAST COPY | 836,487 | 0.3% | 59.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 818,460 | 0.3% | 60.0% |
| LOAD_CONST LOAD_CONST | 803,172 | 0.3% | 60.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 797,596 | 0.3% | 60.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 791,701 | 0.3% | 60.9% |
| TO_BOOL POP_JUMP_IF_FALSE | 787,568 | 0.3% | 61.2% |
| STORE_ATTR_SLOT LOAD_CONST | 785,184 | 0.3% | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 783,260 | 0.3% | 61.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 782,917 | 0.3% | 62.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 755,796 | 0.3% | 62.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 748,140 | 0.3% | 62.7% |
| CALL POP_TOP | 737,964 | 0.3% | 62.9% |
| RETURN_VALUE RETURN_VALUE | 729,180 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 715,936 | 0.3% | 63.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 695,252 | 0.3% | 63.7% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 692,307 | 0.3% | 64.0% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 692,307 | 0.3% | 64.3% |
| POP_TOP LOAD_CONST | 685,698 | 0.3% | 64.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 675,360 | 0.3% | 64.8% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 670,164 | 0.3% | 65.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 654,187 | 0.2% | 65.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 651,940 | 0.2% | 65.5% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 641,544 | 0.2% | 65.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 635,841 | 0.2% | 66.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 628,260 | 0.2% | 66.2% |
| CALL LOAD_FAST | 626,956 | 0.2% | 66.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 620,969 | 0.2% | 66.7% |
| CALL_BUILTIN_FAST STORE_FAST | 610,920 | 0.2% | 66.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 605,690 | 0.2% | 67.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 595,080 | 0.2% | 67.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 594,120 | 0.2% | 67.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 588,823 | 0.2% | 67.8% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 575,403 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 569,128 | 0.2% | 68.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 550,452 | 0.2% | 68.4% |
| PUSH_NULL CALL | 547,459 | 0.2% | 68.6% |
| COPY_FREE_VARS RESUME_CHECK | 545,891 | 0.2% | 68.8% |


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
| RESUME_CHECK | 4,024,903 | 93.8% |
| COPY_FREE_VARS | 174,924 | 4.1% |
| POP_TOP | 72,060 | 1.7% |
| RETURN_GENERATOR | 9,000 | 0.2% |
| MAKE_CELL | 9,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 83,800 | 48.2% |
| RETURN_VALUE | 81,000 | 46.6% |
| LOAD_GLOBAL_MODULE | 9,120 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 173,920 | 100.0% |


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
| LOAD_CONST | 252,370 | 99.7% |
| BINARY_SUBSCR | 640 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 135,000 | 53.4% |
| LOAD_FAST | 45,000 | 17.8% |
| CONVERT_VALUE | 18,000 | 7.1% |
| BINARY_SUBSCR_LIST_INT | 9,157 | 3.6% |
| CALL_LEN | 9,060 | 3.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 292,783 | 88.3% |
| BUILD_TUPLE | 18,060 | 5.4% |
| LOAD_ATTR_MODULE | 11,800 | 3.6% |
| LOAD_GLOBAL_MODULE | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 331,643 | 100.0% |


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
| LOAD_FAST | 241,620 | 41.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 108,180 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,276 | 12.3% |
| LOAD_ATTR | 54,000 | 9.2% |
| BINARY_SLICE | 27,180 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 303,358 | 51.5% |
| FOR_ITER | 109,898 | 18.7% |
| FOR_ITER_TUPLE | 54,180 | 9.2% |
| CALL_PY_EXACT_ARGS | 54,000 | 9.2% |
| LOAD_FAST_AND_CLEAR | 36,060 | 6.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,795,266 | 65.3% |
| RETURN_CONST | 1,278,561 | 29.9% |
| YIELD_VALUE | 189,000 | 4.4% |
| RETURN_GENERATOR | 18,060 | 0.4% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 271,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 118,660 | 43.7% |
| CALL | 90,000 | 33.1% |
| LOAD_FAST | 36,000 | 13.2% |
| CALL_PY_EXACT_ARGS | 18,000 | 6.6% |
| STORE_DEREF | 9,000 | 3.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 934,431 | 41.2% |
| POP_JUMP_IF_FALSE | 336,359 | 14.8% |
| STORE_FAST | 290,649 | 12.8% |
| STORE_ATTR_INSTANCE_VALUE | 228,984 | 10.1% |
| POP_JUMP_IF_TRUE | 206,308 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,268,188 | 55.9% |
| LOAD_GLOBAL_MODULE | 442,100 | 19.5% |
| LOAD_FAST_LOAD_FAST | 225,000 | 9.9% |
| LOAD_DEREF | 100,727 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 90,060 | 4.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 246,225 | 72.6% |
| SWAP | 45,000 | 13.3% |
| COPY | 27,000 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 9,060 | 2.7% |
| STORE_SUBSCR_DICT | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 217,678 | 64.2% |
| RETURN_VALUE | 45,000 | 13.3% |
| RERAISE | 27,000 | 8.0% |
| DELETE_FAST | 18,000 | 5.3% |
| ENTER_EXECUTOR | 11,800 | 3.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,910,529 | 51.6% |
| CALL | 737,964 | 9.7% |
| CALL_METHOD_DESCRIPTOR_O | 620,969 | 8.2% |
| POP_JUMP_IF_FALSE | 450,614 | 5.9% |
| CALL_FUNCTION_EX | 374,577 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,939,114 | 38.8% |
| RETURN_CONST | 2,213,827 | 29.2% |
| LOAD_CONST | 685,698 | 9.0% |
| ENTER_EXECUTOR | 528,995 | 7.0% |
| RESUME_CHECK | 252,060 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 261,120 | 77.0% |
| RERAISE | 27,000 | 8.0% |
| CALL | 22,358 | 6.6% |
| ENTER_EXECUTOR | 9,059 | 2.7% |
| CALL_METHOD_DESCRIPTOR_O | 9,001 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300,285 | 88.6% |
| LOAD_GLOBAL_MODULE | 29,800 | 8.8% |
| LOAD_FAST | 9,000 | 2.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,260,643 | 52.4% |
| LOAD_ATTR | 499,554 | 20.8% |
| LOAD_FAST | 348,879 | 14.5% |
| LOAD_DEREF | 153,240 | 6.4% |
| RETURN_VALUE | 99,060 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,016,986 | 42.3% |
| CALL | 547,459 | 22.7% |
| LOAD_FAST_LOAD_FAST | 533,819 | 22.2% |
| LOAD_GLOBAL_MODULE | 81,100 | 3.4% |
| LOAD_CONST | 71,580 | 3.0% |


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
| LOAD_FAST | 2,374,745 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,016,432 | 23.3% |
| RETURN_VALUE | 729,180 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 466,920 | 5.4% |
| CALL | 464,107 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,795,266 | 32.3% |
| STORE_FAST | 1,599,173 | 18.5% |
| TO_BOOL_BOOL | 1,413,692 | 16.3% |
| RETURN_VALUE | 729,180 | 8.4% |
| LOAD_FAST | 452,201 | 5.2% |


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
| LOAD_FAST | 417,084 | 44.8% |
| LOAD_ATTR_INSTANCE_VALUE | 385,194 | 41.4% |
| LOAD_ATTR | 90,146 | 9.7% |
| COPY | 26,420 | 2.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,100 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 787,568 | 84.7% |
| POP_JUMP_IF_TRUE | 140,007 | 15.1% |
| TO_BOOL | 1,514 | 0.2% |
| TO_BOOL_BOOL | 577 | 0.1% |
| TO_BOOL_NONE | 283 | 0.0% |


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
| LOAD_GLOBAL_MODULE | 138,683 | 17.0% |
| LOAD_CONST | 127,016 | 15.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 117,000 | 14.3% |
| LOAD_FAST | 77,316 | 9.5% |
| LOAD_ATTR_CLASS | 72,120 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 216,154 | 26.4% |
| STORE_FAST | 155,217 | 19.0% |
| COPY | 99,518 | 12.2% |
| RETURN_VALUE | 72,060 | 8.8% |
| LOAD_FAST | 71,100 | 8.7% |


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
| LOAD_FAST | 286,920 | 43.3% |
| STORE_FAST | 83,801 | 12.7% |
| LOAD_FAST_LOAD_FAST | 80,460 | 12.2% |
| RESUME_CHECK | 54,180 | 8.2% |
| SWAP | 36,060 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 496,541 | 75.0% |
| STORE_FAST | 102,257 | 15.4% |
| SWAP | 36,060 | 5.4% |
| LOAD_CONST | 18,000 | 2.7% |
| CALL_BUILTIN_CLASS | 9,000 | 1.4% |


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
| LOAD_FAST | 382,764 | 37.0% |
| LOAD_FAST_LOAD_FAST | 288,240 | 27.9% |
| LOAD_GLOBAL_BUILTIN | 117,300 | 11.3% |
| LOAD_GLOBAL_MODULE | 72,180 | 7.0% |
| LOAD_ATTR_MODULE | 54,000 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 144,000 | 13.9% |
| RETURN_VALUE | 135,360 | 13.1% |
| LOAD_CONST | 118,660 | 11.5% |
| CALL_ISINSTANCE | 117,300 | 11.3% |
| CONTAINS_OP | 90,060 | 8.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,531,000 | 32.4% |
| PUSH_NULL | 547,459 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 459,160 | 9.7% |
| LOAD_GLOBAL_MODULE | 442,881 | 9.4% |
| LOAD_CONST | 397,790 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,531,640 | 32.4% |
| POP_TOP | 737,964 | 15.6% |
| LOAD_FAST | 626,956 | 13.3% |
| RETURN_VALUE | 464,107 | 9.8% |
| BINARY_SUBSCR_DICT | 315,060 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 359,220 | 44.5% |
| ENTER_EXECUTOR | 272,476 | 33.7% |
| LOAD_FAST | 74,920 | 9.3% |
| CALL_INTRINSIC_1 | 57,041 | 7.1% |
| BUILD_MAP | 44,400 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 374,577 | 46.4% |
| RETURN_VALUE | 164,260 | 20.3% |
| RESUME_CHECK | 99,060 | 12.3% |
| STORE_FAST | 89,520 | 11.1% |
| CALL | 62,460 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 217,361 | 96.0% |
| RERAISE | 9,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 115,920 | 51.2% |
| CALL_FUNCTION_EX | 57,041 | 25.2% |
| LOAD_CONST | 44,400 | 19.6% |
| RERAISE | 9,000 | 4.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300,280 | 87.0% |
| ENTER_EXECUTOR | 45,000 | 13.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 198,180 | 57.4% |
| STORE_FAST | 74,800 | 21.7% |
| COPY_FREE_VARS | 18,000 | 5.2% |
| LOAD_FAST | 9,120 | 2.6% |
| RETURN_VALUE | 9,060 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 87,405 | 65.7% |
| LOAD_ATTR | 18,000 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 6.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.8% |
| LOAD_ATTR_CLASS | 9,000 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 87,505 | 65.7% |
| POP_JUMP_IF_TRUE | 45,000 | 33.8% |
| COMPARE_OP | 441 | 0.3% |
| COMPARE_OP_INT | 109 | 0.1% |
| COMPARE_OP_STR | 80 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 153,480 | 25.8% |
| LOAD_CONST | 108,060 | 18.2% |
| BUILD_TUPLE | 90,060 | 15.1% |
| LOAD_FAST | 81,360 | 13.7% |
| LOAD_FAST_LOAD_FAST | 81,120 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 450,900 | 75.7% |
| COPY | 90,000 | 15.1% |
| POP_JUMP_IF_TRUE | 18,360 | 3.1% |
| SWAP | 18,000 | 3.0% |
| LOAD_FAST | 9,000 | 1.5% |


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
| LOAD_FAST | 836,487 | 46.6% |
| LOAD_CONST | 189,060 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 171,000 | 9.5% |
| BINARY_OP | 99,518 | 5.5% |
| CONTAINS_OP | 90,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 692,307 | 38.6% |
| LOAD_FAST | 342,000 | 19.1% |
| TO_BOOL_BOOL | 243,000 | 13.5% |
| TO_BOOL_NONE | 143,984 | 8.0% |
| TO_BOOL_INT | 120,495 | 6.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 216,276 | 37.2% |
| CACHE | 174,924 | 30.1% |
| CALL | 90,120 | 15.5% |
| LOAD_ATTR_PROPERTY | 63,000 | 10.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,451 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 545,891 | 93.8% |
| RETURN_GENERATOR | 18,060 | 3.1% |
| MAKE_CELL | 18,060 | 3.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 81,000 | 52.0% |
| NOP | 18,000 | 11.5% |
| POP_EXCEPT | 18,000 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 18,000 | 11.5% |
| POP_TOP | 11,800 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 81,000 | 52.0% |
| RETURN_CONST | 36,000 | 23.1% |
| LOAD_FAST | 20,800 | 13.3% |
| LOAD_CONST | 9,060 | 5.8% |
| ENTER_EXECUTOR | 9,000 | 5.8% |


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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 528,995 | 55.7% |
| POP_JUMP_IF_TRUE | 111,105 | 11.7% |
| CALL_LIST_APPEND | 74,486 | 7.8% |
| STORE_ATTR_INSTANCE_VALUE | 63,000 | 6.6% |
| EXTENDED_ARG | 45,000 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 272,476 | 28.7% |
| CALL | 136,538 | 14.4% |
| LOAD_FAST | 117,326 | 12.4% |
| RESUME_CHECK | 90,460 | 9.5% |
| JUMP_BACKWARD | 81,060 | 8.5% |


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
| ENTER_EXECUTOR | 45,000 | 29.4% |
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
| GET_ITER | 109,898 | 41.6% |
| LOAD_FAST | 18,000 | 6.8% |
| SWAP | 18,000 | 6.8% |
| FOR_ITER | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 100,778 | 38.2% |
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
| POP_TOP | 162,060 | 57.9% |
| ENTER_EXECUTOR | 81,060 | 28.9% |
| STORE_SUBSCR | 27,000 | 9.6% |
| POP_JUMP_IF_TRUE | 9,420 | 3.4% |
| STORE_FAST | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 162,000 | 57.8% |
| FOR_ITER | 117,480 | 41.9% |
| FOR_ITER_LIST | 420 | 0.1% |
| EXTENDED_ARG | 60 | 0.0% |
| FOR_ITER_RANGE | 60 | 0.0% |


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
| STORE_FAST | 330,227 | 59.4% |
| POP_TOP | 99,060 | 17.8% |
| STORE_ATTR_INSTANCE_VALUE | 36,336 | 6.5% |
| POP_JUMP_IF_TRUE | 18,000 | 3.2% |
| STORE_ATTR | 18,000 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 355,312 | 64.0% |
| LOAD_CONST | 69,472 | 12.5% |
| LOAD_FAST_LOAD_FAST | 45,000 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 31,438 | 5.7% |
| LOAD_GLOBAL_MODULE | 27,000 | 4.9% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,000 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 196,440 | 83.5% |
| LOAD_CONST | 18,000 | 7.6% |
| LOAD_ATTR_SLOT | 11,801 | 5.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 3.8% |
| BINARY_SLICE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 217,361 | 92.4% |
| LOAD_FAST | 18,000 | 7.6% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,678,375 | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE | 651,940 | 15.8% |
| LOAD_ATTR_WITH_HINT | 252,000 | 6.1% |
| LOAD_GLOBAL_MODULE | 225,717 | 5.5% |
| LOAD_DEREF | 112,204 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 877,517 | 21.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 670,164 | 16.2% |
| PUSH_NULL | 499,554 | 12.1% |
| LOAD_CONST | 360,073 | 8.7% |
| CALL_PY_EXACT_ARGS | 241,718 | 5.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,494,899 | 20.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,254,500 | 10.5% |
| LOAD_CONST | 803,172 | 6.7% |
| POP_JUMP_IF_FALSE | 791,701 | 6.6% |
| STORE_ATTR_SLOT | 785,184 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,872,964 | 32.4% |
| COMPARE_OP_INT | 1,287,824 | 10.8% |
| STORE_FAST | 903,914 | 7.6% |
| LOAD_CONST | 803,172 | 6.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 476,180 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 299,052 | 19.1% |
| RESUME_CHECK | 155,352 | 9.9% |
| POP_JUMP_IF_FALSE | 128,112 | 8.2% |
| POP_JUMP_IF_TRUE | 108,240 | 6.9% |
| NOP | 100,727 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 377,820 | 24.2% |
| LOAD_ATTR_INSTANCE_VALUE | 275,976 | 17.7% |
| PUSH_NULL | 153,240 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 117,000 | 7.5% |
| LOAD_ATTR | 112,204 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,533,263 | 15.4% |
| POP_JUMP_IF_FALSE | 5,458,086 | 9.8% |
| STORE_FAST | 4,972,749 | 9.0% |
| LOAD_CONST | 3,872,964 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 3,844,461 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,324,052 | 29.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,487,800 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 3,706,731 | 6.7% |
| LOAD_ATTR | 2,678,375 | 4.8% |
| CALL_PY_EXACT_ARGS | 2,504,260 | 4.5% |


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
| LOAD_ATTR_METHOD_NO_DICT | 10,992 | 37.9% |
| POP_JUMP_IF_FALSE | 9,000 | 31.0% |
| STORE_FAST | 9,000 | 31.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 10,992 | 37.9% |
| LOAD_ATTR | 9,000 | 31.0% |
| LOAD_CONST | 9,000 | 31.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 976,896 | 12.7% |
| LOAD_GLOBAL_MODULE | 818,460 | 10.6% |
| STORE_FAST | 797,596 | 10.4% |
| STORE_ATTR_INSTANCE_VALUE | 748,140 | 9.7% |
| POP_JUMP_IF_FALSE | 675,360 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,495,796 | 19.5% |
| STORE_ATTR_SLOT | 1,346,928 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 960,936 | 12.5% |
| LOAD_FAST | 654,187 | 8.5% |
| LOAD_FAST_LOAD_FAST | 550,452 | 7.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 340 | 14.7% |
| POP_JUMP_IF_FALSE | 290 | 12.5% |
| STORE_FAST | 290 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 160 | 6.9% |
| POP_TOP | 140 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,634 | 70.4% |
| LOAD_GLOBAL_BUILTIN | 614 | 26.5% |
| LOAD_ATTR | 33 | 1.4% |
| CALL | 13 | 0.6% |
| LOAD_CONST | 13 | 0.6% |


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
| MAKE_CELL | 139,524 | 45.9% |
| CALL_PY_EXACT_ARGS | 85,343 | 28.1% |
| ENTER_EXECUTOR | 33,949 | 11.2% |
| COPY_FREE_VARS | 18,060 | 5.9% |
| CACHE | 9,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 155,472 | 51.1% |
| MAKE_CELL | 139,524 | 45.9% |
| RETURN_GENERATOR | 9,000 | 3.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,765,444 | 45.8% |
| COMPARE_OP_INT | 1,994,760 | 19.2% |
| TO_BOOL_NONE | 910,222 | 8.7% |
| TO_BOOL | 787,568 | 7.6% |
| CONTAINS_OP | 450,900 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,458,086 | 52.4% |
| RETURN_CONST | 1,111,968 | 10.7% |
| LOAD_CONST | 791,701 | 7.6% |
| LOAD_GLOBAL_MODULE | 755,796 | 7.3% |
| LOAD_FAST_LOAD_FAST | 675,360 | 6.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,276,176 | 56.1% |
| LOAD_FAST | 1,527,385 | 37.7% |
| LOAD_ATTR | 99,060 | 2.4% |
| LOAD_DEREF | 99,060 | 2.4% |
| LOAD_ATTR_WITH_HINT | 26,804 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,350,653 | 82.6% |
| RETURN_CONST | 209,352 | 5.2% |
| LOAD_GLOBAL_MODULE | 207,100 | 5.1% |
| LOAD_FAST_LOAD_FAST | 108,240 | 2.7% |
| NOP | 99,060 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 782,917 | 63.5% |
| LOAD_ATTR_INSTANCE_VALUE | 333,000 | 27.0% |
| LOAD_ATTR | 81,360 | 6.6% |
| LOAD_GLOBAL_MODULE | 9,300 | 0.8% |
| RETURN_VALUE | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 433,509 | 35.1% |
| LOAD_FAST_LOAD_FAST | 326,112 | 26.4% |
| LOAD_GLOBAL_MODULE | 249,056 | 20.2% |
| LOAD_CONST | 99,000 | 8.0% |
| LOAD_DEREF | 63,120 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,675,237 | 54.8% |
| COMPARE_OP_INT | 531,300 | 17.4% |
| TO_BOOL_INT | 195,133 | 6.4% |
| TO_BOOL_STR | 180,420 | 5.9% |
| TO_BOOL_NONE | 152,773 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,434,764 | 47.0% |
| LOAD_GLOBAL_BUILTIN | 333,120 | 10.9% |
| NOP | 206,308 | 6.8% |
| LOAD_FAST_LOAD_FAST | 171,240 | 5.6% |
| LOAD_CONST | 170,208 | 5.6% |


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
| POP_TOP | 2,213,827 | 37.4% |
| POP_JUMP_IF_FALSE | 1,111,968 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 569,128 | 9.6% |
| STORE_ATTR_SLOT | 459,552 | 7.8% |
| STORE_FAST | 296,078 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,910,529 | 66.1% |
| INTERPRETER_EXIT | 1,278,561 | 21.6% |
| EXIT_INIT_CHECK | 243,240 | 4.1% |
| STORE_FAST | 132,196 | 2.2% |
| END_SEND | 99,000 | 1.7% |


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
| MAKE_FUNCTION | 118,660 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 38,172 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,368 | 34.0% |
| SET_FUNCTION_ATTRIBUTE | 38,172 | 24.3% |
| CALL | 29,212 | 18.6% |
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
| RETURN_VALUE | 1,599,173 | 19.8% |
| CALL | 1,531,640 | 19.0% |
| LOAD_CONST | 903,914 | 11.2% |
| CALL_BUILTIN_FAST | 610,920 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 529,593 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,972,749 | 61.6% |
| LOAD_FAST_LOAD_FAST | 797,596 | 9.9% |
| LOAD_CONST | 437,715 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 362,939 | 4.5% |
| JUMP_FORWARD | 330,227 | 4.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 81,000 | 52.9% |
| COPY | 63,000 | 41.2% |
| STORE_ATTR | 9,000 | 5.9% |
| FOR_ITER_RANGE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 81,000 | 52.9% |
| STORE_ATTR_INSTANCE_VALUE | 63,000 | 41.2% |
| STORE_ATTR | 9,000 | 5.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 532,574 | 73.8% |
| UNPACK_SEQUENCE_LIST | 90,000 | 12.5% |
| UNPACK_SEQUENCE_TUPLE | 54,180 | 7.5% |
| STORE_FAST_STORE_FAST | 18,120 | 2.5% |
| COPY | 18,060 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 397,454 | 55.0% |
| LOAD_GLOBAL_MODULE | 99,000 | 13.7% |
| STORE_FAST | 72,180 | 10.0% |
| LOAD_FAST_LOAD_FAST | 63,120 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 63,000 | 8.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 425,200 | 41.2% |
| BINARY_OP_SUBTRACT_INT | 249,107 | 24.2% |
| LOAD_FAST | 144,000 | 14.0% |
| LOAD_ATTR | 41,929 | 4.1% |
| BUILD_LIST | 36,060 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 692,307 | 67.1% |
| COPY | 81,060 | 7.9% |
| STORE_FAST | 68,929 | 6.7% |
| LOAD_CONST | 54,000 | 5.2% |
| POP_EXCEPT | 45,000 | 4.4% |


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
| LOAD_ATTR_INSTANCE_VALUE | 11,801 | 12.9% |
| LOAD_ATTR | 9,000 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,400 | 58.3% |
| LOAD_GLOBAL_MODULE | 26,400 | 28.8% |
| STORE_FAST | 11,801 | 12.9% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,800 | 62.4% |
| LOAD_FAST_LOAD_FAST | 198,000 | 24.4% |
| CALL_LEN | 63,000 | 7.8% |
| LOAD_CONST | 44,440 | 5.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 425,200 | 52.3% |
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
| RETURN_VALUE | 9,000 | 90.6% |
| LOAD_CONST | 916 | 9.2% |
| BINARY_OP | 17 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,000 | 90.6% |
| CALL_BUILTIN_O | 916 | 9.2% |
| CALL | 17 | 0.2% |


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
| RETURN_VALUE | 45,316 | 65.1% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 12.9% |
| LOAD_ATTR_WITH_HINT | 9,000 | 12.9% |
| CALL | 6,196 | 8.9% |
| LOAD_FAST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 45,333 | 65.1% |
| RETURN_VALUE | 9,000 | 12.9% |
| LOAD_FAST | 9,000 | 12.9% |
| STORE_FAST | 6,196 | 8.9% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 423,000 | 67.5% |
| LOAD_ATTR_INSTANCE_VALUE | 72,000 | 11.5% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 10.0% |
| CALL_LEN | 45,000 | 7.2% |
| LOAD_CONST | 24,107 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 249,107 | 39.7% |
| STORE_FAST | 243,000 | 38.7% |
| LOAD_FAST | 63,000 | 10.0% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 10.0% |
| BINARY_SUBSCR_LIST_INT | 9,000 | 1.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 315,060 | 46.6% |
| LOAD_FAST | 262,607 | 38.8% |
| BUILD_TUPLE | 36,060 | 5.3% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| RETURN_VALUE | 18,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,000 | 47.9% |
| PUSH_EXC_INFO | 261,120 | 38.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 28,547 | 4.2% |
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
| LOAD_CONST | 31,768 | 63.6% |
| BINARY_SUBSCR | 9,157 | 18.3% |
| BINARY_OP_SUBTRACT_INT | 9,000 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,060 | 36.2% |
| STORE_FAST | 11,603 | 23.2% |
| LOAD_ATTR_SLOT | 9,398 | 18.8% |
| LOAD_CONST | 9,000 | 18.0% |
| TO_BOOL_BOOL | 1,547 | 3.1% |


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
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 25.9% |
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
| LOAD_CONST | 81,000 | 36.7% |
| LOAD_FAST | 65,053 | 29.5% |
| LOAD_FAST_LOAD_FAST | 36,007 | 16.3% |
| BINARY_SLICE | 18,000 | 8.2% |
| CALL_BUILTIN_CLASS | 18,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 118,394 | 53.6% |
| POP_TOP | 81,000 | 36.7% |
| COPY_FREE_VARS | 19,451 | 8.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,580 | 0.7% |
| CALL_PY_EXACT_ARGS | 327 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,961 | 28.8% |
| LOAD_ATTR_INSTANCE_VALUE | 27,120 | 26.1% |
| LOAD_GLOBAL_MODULE | 10,587 | 10.2% |
| LOAD_GLOBAL_BUILTIN | 9,080 | 8.7% |
| RETURN_GENERATOR | 9,000 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,000 | 26.0% |
| GET_ITER | 22,408 | 21.6% |
| LOAD_FAST | 18,120 | 17.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 18,000 | 17.3% |
| LOAD_CONST | 9,000 | 8.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 628,260 | 50.7% |
| LOAD_FAST_LOAD_FAST | 341,060 | 27.5% |
| LOAD_CONST | 216,060 | 17.4% |
| LOAD_GLOBAL_MODULE | 27,000 | 2.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 610,920 | 49.6% |
| RETURN_VALUE | 340,920 | 27.7% |
| TO_BOOL_BOOL | 99,040 | 8.0% |
| COPY | 81,000 | 6.6% |
| POP_TOP | 44,460 | 3.6% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 10,992 | 54.8% |
| LOAD_FAST | 9,060 | 45.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,992 | 54.8% |
| STORE_FAST | 9,060 | 45.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,316 | 89.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,303 | 8.1% |
| BINARY_OP_MULTIPLY_FLOAT | 916 | 2.3% |
| CALL | 77 | 0.2% |
| BUILD_LIST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 18,000 | 44.2% |
| STORE_FAST | 12,303 | 30.2% |
| BINARY_SUBSCR_DICT | 9,000 | 22.1% |
| LOAD_CONST | 933 | 2.3% |
| POP_TOP | 396 | 1.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 846,454 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 325,020 | 20.9% |
| LOAD_ATTR_MODULE | 224,400 | 14.4% |
| BUILD_TUPLE | 117,300 | 7.5% |
| LOAD_ATTR | 45,080 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,405,074 | 90.2% |
| RETURN_VALUE | 108,120 | 6.9% |
| COPY | 27,000 | 1.7% |
| STORE_FAST | 18,060 | 1.2% |
| TO_BOOL | 140 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 486,240 | 65.8% |
| LOAD_ATTR_INSTANCE_VALUE | 234,398 | 31.7% |
| BINARY_SUBSCR | 9,060 | 1.2% |
| LOAD_GLOBAL_MODULE | 9,000 | 1.2% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 216,117 | 29.3% |
| LOAD_FAST | 169,740 | 23.0% |
| LOAD_CONST | 72,240 | 9.8% |
| BINARY_OP_ADD_INT | 63,000 | 8.5% |
| BINARY_OP | 45,000 | 6.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,699 | 52.5% |
| BUILD_TUPLE | 49,015 | 25.6% |
| ENTER_EXECUTOR | 23,852 | 12.4% |
| RETURN_VALUE | 18,120 | 9.5% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 90,000 | 46.9% |
| ENTER_EXECUTOR | 74,486 | 38.9% |
| LOAD_FAST | 18,000 | 9.4% |
| NOP | 9,000 | 4.7% |
| JUMP_BACKWARD | 180 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 476,180 | 66.4% |
| LOAD_ATTR_METHOD_NO_DICT | 153,000 | 21.3% |
| LOAD_FAST_LOAD_FAST | 54,120 | 7.6% |
| RETURN_VALUE | 18,060 | 2.5% |
| LOAD_FAST | 14,909 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 466,920 | 65.2% |
| CALL_PY_EXACT_ARGS | 81,080 | 11.3% |
| STORE_FAST | 69,049 | 9.6% |
| LOAD_CONST | 54,000 | 7.5% |
| LOAD_FAST | 18,000 | 2.5% |


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
| LOAD_FAST_LOAD_FAST | 11,801 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,281 | 37.7% |
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
| LOAD_ATTR | 670,164 | 59.1% |
| LOAD_ATTR_METHOD_NO_DICT | 434,144 | 38.3% |
| LOAD_FAST | 18,060 | 1.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,000 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,782 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 695,252 | 61.3% |
| POP_TOP | 114,256 | 10.1% |
| GET_ITER | 108,180 | 9.5% |
| LOAD_FAST | 54,180 | 4.8% |
| STORE_FAST | 49,793 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 431,909 | 57.6% |
| BUILD_TUPLE | 144,000 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 8.4% |
| LOAD_CONST | 36,040 | 4.8% |
| CALL | 27,080 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 620,969 | 82.8% |
| STORE_FAST | 73,991 | 9.9% |
| LOAD_CONST | 18,000 | 2.4% |
| UNPACK_SEQUENCE_TUPLE | 18,000 | 2.4% |
| LOAD_FAST | 9,060 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,346,901 | 41.1% |
| LOAD_FAST | 2,504,260 | 30.7% |
| LOAD_FAST_LOAD_FAST | 496,120 | 6.1% |
| LOAD_CONST | 432,160 | 5.3% |
| LOAD_ATTR | 241,718 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,644,896 | 93.8% |
| COPY_FREE_VARS | 216,276 | 2.7% |
| RETURN_GENERATOR | 198,000 | 2.4% |
| MAKE_CELL | 85,343 | 1.0% |
| TO_BOOL_BOOL | 3,164 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,000 | 25.3% |
| LOAD_FAST | 99,200 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 92,800 | 21.8% |
| PUSH_NULL | 54,260 | 12.7% |
| LOAD_ATTR | 27,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 417,460 | 97.9% |
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
| LOAD_ATTR_SLOT | 249,722 | 95.6% |
| LOAD_FAST | 11,543 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 249,722 | 95.6% |
| POP_JUMP_IF_FALSE | 11,543 | 4.4% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,287,824 | 50.6% |
| LOAD_ATTR_INSTANCE_VALUE | 715,936 | 28.1% |
| LOAD_ATTR_CLASS | 288,000 | 11.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 90,000 | 3.5% |
| COPY | 81,060 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,994,760 | 78.4% |
| POP_JUMP_IF_TRUE | 531,300 | 20.9% |
| COPY | 18,000 | 0.7% |
| COMPARE_OP | 9 | 0.0% |


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
| GET_ITER | 303,358 | 97.0% |
| SWAP | 9,000 | 2.9% |
| JUMP_BACKWARD | 420 | 0.1% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 171,936 | 54.9% |
| LOAD_FAST | 104,992 | 33.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20,738 | 6.6% |
| UNPACK_SEQUENCE_TUPLE | 9,000 | 2.9% |
| RETURN_CONST | 6,112 | 2.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 22,408 | 99.5% |
| JUMP_BACKWARD | 60 | 0.3% |
| SWAP | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,408 | 99.5% |
| STORE_FAST_LOAD_FAST | 60 | 0.3% |
| LOAD_GLOBAL_MODULE | 40 | 0.2% |
| LOAD_GLOBAL | 20 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 54,180 | 85.7% |
| SWAP | 9,000 | 14.2% |
| JUMP_BACKWARD | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,060 | 71.3% |
| STORE_FAST | 9,180 | 14.5% |
| SWAP | 9,000 | 14.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 341,100 | 62.1% |
| LOAD_GLOBAL_MODULE | 171,560 | 31.2% |
| LOAD_FAST | 36,600 | 6.7% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 288,000 | 52.4% |
| LOAD_FAST | 107,460 | 19.6% |
| BINARY_OP | 72,120 | 13.1% |
| CALL | 36,100 | 6.6% |
| RETURN_VALUE | 18,180 | 3.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,324,052 | 86.6% |
| LOAD_FAST_LOAD_FAST | 960,936 | 5.1% |
| COPY | 692,307 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 594,120 | 3.2% |
| LOAD_DEREF | 275,976 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,127,599 | 16.6% |
| POP_JUMP_IF_NONE | 2,276,176 | 12.1% |
| RETURN_VALUE | 2,016,432 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 1,706,549 | 9.1% |
| TO_BOOL_BOOL | 1,687,326 | 9.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 1,706,549 | 52.6% |
| LOAD_FAST | 869,563 | 26.8% |
| BINARY_SLICE | 189,040 | 5.8% |
| LOAD_CONST | 99,040 | 3.1% |
| BINARY_SUBSCR_STR_INT | 81,080 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,411,337 | 43.5% |
| LOAD_CONST | 605,690 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 434,144 | 13.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 171,000 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 153,000 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,487,800 | 68.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,303,226 | 19.9% |
| LOAD_ATTR_SLOT | 441,492 | 6.7% |
| LOAD_DEREF | 92,292 | 1.4% |
| LOAD_FAST_LOAD_FAST | 81,376 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,346,901 | 51.0% |
| LOAD_FAST | 2,070,633 | 31.6% |
| LOAD_FAST_LOAD_FAST | 506,232 | 7.7% |
| LOAD_CONST | 324,060 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 107,400 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,297,040 | 99.6% |
| LOAD_ATTR_MODULE | 9,000 | 0.4% |
| LOAD_ATTR | 597 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,260,643 | 54.7% |
| LOAD_ATTR_CLASS | 341,100 | 14.8% |
| CALL_ISINSTANCE | 224,400 | 9.7% |
| LOAD_GLOBAL_MODULE | 108,040 | 4.7% |
| LOAD_ATTR | 99,060 | 4.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 153,000 | 54.8% |
| LOAD_FAST_LOAD_FAST | 63,000 | 22.6% |
| LOAD_FAST | 54,060 | 19.4% |
| LOAD_DEREF | 9,000 | 3.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 117,000 | 41.9% |
| COMPARE_OP_INT | 90,000 | 32.2% |
| LOAD_FAST | 27,060 | 9.7% |
| STORE_FAST | 27,000 | 9.7% |
| CONTAINS_OP | 18,000 | 6.4% |


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
| LOAD_FAST | 1,945,373 | 94.5% |
| BINARY_SUBSCR_TUPLE_INT | 90,060 | 4.4% |
| BINARY_SUBSCR_LIST_INT | 9,398 | 0.5% |
| LOAD_DEREF | 9,000 | 0.4% |
| LOAD_ATTR_SLOT | 4,179 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 641,544 | 31.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 441,492 | 21.5% |
| LOAD_FAST | 261,265 | 12.7% |
| COMPARE_OP_FLOAT | 249,722 | 12.1% |
| TO_BOOL_BOOL | 225,369 | 11.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,403 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 249 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,000 | 43.8% |
| LOAD_CONST | 72,000 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,804 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 45,000 | 7.8% |
| RETURN_VALUE | 27,000 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,079,821 | 40.0% |
| LOAD_FAST | 595,080 | 11.4% |
| POP_JUMP_IF_FALSE | 477,516 | 9.2% |
| STORE_FAST | 362,939 | 7.0% |
| POP_JUMP_IF_TRUE | 333,120 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,844,461 | 74.0% |
| CALL_ISINSTANCE | 325,020 | 6.3% |
| LOAD_DEREF | 299,052 | 5.8% |
| CHECK_EXC_MATCH | 292,783 | 5.6% |
| BUILD_TUPLE | 117,300 | 2.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,625,690 | 20.6% |
| RESUME_CHECK | 1,471,759 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 783,260 | 9.9% |
| POP_JUMP_IF_FALSE | 755,796 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 588,823 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,297,040 | 29.0% |
| LOAD_FAST | 1,631,284 | 20.6% |
| CALL_ISINSTANCE | 846,454 | 10.7% |
| LOAD_FAST_LOAD_FAST | 818,460 | 10.3% |
| CALL | 442,881 | 5.6% |


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
| CALL_PY_EXACT_ARGS | 7,644,896 | 52.0% |
| CACHE | 4,024,903 | 27.4% |
| COPY_FREE_VARS | 545,891 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 417,460 | 2.8% |
| BINARY_SUBSCR_GETITEM | 369,180 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,533,263 | 58.1% |
| LOAD_GLOBAL_BUILTIN | 2,079,821 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,471,759 | 10.0% |
| NOP | 934,431 | 6.4% |
| LOAD_CONST | 488,532 | 3.3% |


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
| LOAD_FAST | 3,706,731 | 60.9% |
| LOAD_FAST_LOAD_FAST | 1,495,796 | 24.6% |
| SWAP | 692,307 | 11.4% |
| LOAD_DEREF | 117,000 | 1.9% |
| STORE_FAST_LOAD_FAST | 63,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,108,980 | 34.7% |
| LOAD_CONST | 1,254,500 | 20.6% |
| LOAD_FAST_LOAD_FAST | 748,140 | 12.3% |
| LOAD_GLOBAL_MODULE | 588,823 | 9.7% |
| RETURN_CONST | 569,128 | 9.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,354,152 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,346,928 | 49.7% |
| STORE_ATTR_SLOT | 9,770 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 976,896 | 36.0% |
| LOAD_CONST | 785,184 | 29.0% |
| LOAD_FAST | 462,855 | 17.1% |
| RETURN_CONST | 459,552 | 17.0% |
| ENTER_EXECUTOR | 16,593 | 0.6% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,801 | 79.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 20.1% |
| STORE_ATTR_INSTANCE_VALUE | 83 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,000 | 80.2% |
| RETURN_CONST | 8,804 | 19.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,687,326 | 25.8% |
| RETURN_VALUE | 1,413,692 | 21.6% |
| CALL_ISINSTANCE | 1,405,074 | 21.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 695,252 | 10.6% |
| LOAD_FAST | 300,612 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,765,444 | 72.9% |
| POP_JUMP_IF_TRUE | 1,675,237 | 25.6% |
| EXTENDED_ARG | 90,000 | 1.4% |
| UNARY_NOT | 9,000 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 243,120 | 41.3% |
| BINARY_OP | 216,154 | 36.7% |
| COPY | 120,495 | 20.5% |
| LOAD_ATTR | 9,000 | 1.5% |
| TO_BOOL_NONE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 393,627 | 66.8% |
| POP_JUMP_IF_TRUE | 195,133 | 33.1% |
| TO_BOOL_NONE | 89 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 102,499 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| TO_BOOL | 17 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 102,636 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 641,544 | 60.3% |
| COPY | 143,984 | 13.5% |
| LOAD_FAST | 142,123 | 13.4% |
| LOAD_ATTR | 63,000 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 54,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 910,222 | 85.6% |
| POP_JUMP_IF_TRUE | 152,773 | 14.4% |
| TO_BOOL | 148 | 0.0% |
| TO_BOOL_STR | 100 | 0.0% |
| TO_BOOL_INT | 80 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 171,320 | 79.0% |
| COPY | 27,000 | 12.5% |
| LOAD_ATTR | 9,000 | 4.2% |
| CALL_BUILTIN_FAST | 4,680 | 2.2% |
| ENTER_EXECUTOR | 4,600 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 180,420 | 83.2% |
| POP_JUMP_IF_FALSE | 36,240 | 16.7% |
| TO_BOOL_NONE | 80 | 0.0% |


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
| BINARY_SUBSCR | 135,000 | 24.9% |
| RETURN_VALUE | 117,240 | 21.6% |
| FOR_ITER | 81,040 | 15.0% |
| YIELD_VALUE | 81,000 | 15.0% |
| STORE_FAST | 41,929 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 532,574 | 98.3% |
| LOAD_FAST | 9,060 | 1.7% |
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
|     deferred | 815,490 | 31.3% |
|          hit | 1,790,610 | 68.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 114 | 6.1% |
| Failure | 1,758 | 93.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 760 | 43.2% |
| add other | 280 | 15.9% |
| or | 279 | 15.9% |
| remainder | 200 | 11.4% |
| add different types | 121 | 6.9% |
| multiply different types | 78 | 4.4% |
| floor divide | 40 | 2.3% |


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
|     deferred | 252,073 | 15.7% |
|          hit | 1,348,372 | 84.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 297 | 31.7% |
| Failure | 640 | 68.3% |

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
|     deferred | 4,711,846 | 22.4% |
|        deopt | 5,132 | 0.0% |
|          hit | 16,086,984 | 76.3% |
|         miss | 269,195 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,215 | 46.6% |
| Failure | 8,275 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,566 | 18.9% |
| class no vectorcall | 1,360 | 16.4% |
| cfunc noargs | 1,087 | 13.1% |
| meth descr method fastcall keywords | 920 | 11.1% |
| meth descr varargs | 807 | 9.8% |
| cfunc varargs keywords | 716 | 8.7% |
| class mutable | 420 | 5.1% |
| other | 376 | 4.5% |
| meth descr varargs keywords | 323 | 3.9% |
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
|     deferred | 132,505 | 4.2% |
|        deopt | 9 | 0.0% |
|          hit | 3,011,748 | 95.7% |
|         miss | 1,006 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 189 | 29.6% |
| Failure | 450 | 70.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 120 | 26.7% |
| other | 100 | 22.2% |
| bytes | 80 | 17.8% |
| float long | 50 | 11.1% |
| big int | 40 | 8.9% |
| tuple | 40 | 8.9% |
| bool | 20 | 4.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 263,378 | 30.3% |
|          hit | 605,666 | 69.6% |

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
|     deferred | 4,119,168 | 10.7% |
|        deopt | 6,390 | 0.0% |
|          hit | 34,194,188 | 88.4% |
|         miss | 337,698 | 0.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,992 | 48.5% |
| Failure | 9,542 | 51.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,991 | 20.9% |
| has managed dict | 1,978 | 20.7% |
| not managed dict | 1,711 | 17.9% |
| not in keys | 1,680 | 17.6% |
| shadowed | 482 | 5.1% |
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
|     deferred | 72 | 0.0% |
|          hit | 13,107,547 | 100.0% |
|         miss | 840 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,248 | 100.0% |
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
|        deopt | 9,933 | 0.1% |
|          hit | 8,314,098 | 92.0% |
|         miss | 526,470 | 5.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 10,853 | 91.7% |
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
|     deferred | 927,575 | 9.8% |
|        deopt | 497 | 0.0% |
|          hit | 8,521,657 | 89.9% |
|         miss | 25,572 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,266 | 43.2% |
| Failure | 1,662 | 56.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 571 | 34.4% |
| sequence | 384 | 23.1% |
| float | 240 | 14.4% |
| dict | 160 | 9.6% |
| mapping | 107 | 6.4% |
| bytearray | 80 | 4.8% |
| tuple | 80 | 4.8% |
| set | 40 | 2.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,000 | 1.3% |
|          hit | 694,874 | 98.7% |

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
| Basic | 132,108,823 | 49.3% |
| Not specialized | 32,510,364 | 12.1% |
| Specialized | 103,110,812 | 38.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,444 | 100.0% |
| CALL | 4,711,846 | 0.0% |
| LOAD_ATTR | 4,119,168 | 0.0% |
| TO_BOOL | 927,575 | 0.0% |
| BINARY_OP | 815,490 | 0.0% |
| FOR_ITER | 263,378 | 0.0% |
| BINARY_SUBSCR | 252,073 | 0.0% |
| SEND | 252,000 | 0.0% |
| STORE_ATTR | 198,480 | 0.0% |
| STORE_SUBSCR | 180,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 517,791 | 44.5% |
| LOAD_ATTR_SLOT | 221,468 | 19.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100,625 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 93,809 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,475 | 5.2% |
| CALL_PY_EXACT_ARGS | 47,101 | 4.1% |
| CALL_METHOD_DESCRIPTOR_O | 27,660 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 20,358 | 1.8% |
| TO_BOOL_NONE | 16,389 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 13,317 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,289,887 | 28.9% |
| Calls to Python functions inlined | 10,537,042 | 71.1% |
| Calls via PyEval_EvalFrame (total) | 4,289,887 | 28.9% |
| Calls via PyEval_EvalFrame (vector) | 4,028,827 | 27.2% |
| Calls via PyEval_EvalFrame (generator) | 261,060 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 4,028,827 | 27.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 816,842 | 5.5% |
| Calls via PyEval_EvalFrame (function ex) | 99,240 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 153,360 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 686,352 | 4.6% |
| Frame objects created | 616,952 | 4.2% |
| Frames pushed | 14,888,435 | 100.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,953,679 | 40.4% |
| Frees to freelist | 8,972,466 |  |
| Allocations | 13,226,275 | 59.6% |
| Allocations to 512 bytes | 12,985,840 | 58.5% |
| Allocations to 4 kbytes | 66,219 | 0.3% |
| Allocations over 4 kbytes | 174,216 | 0.8% |
| Frees | 13,465,334 |  |
| New values | 117,540 |  |
| Interpreter increfs | 132,534,768 | 73.1% |
| Interpreter decrefs | 143,875,702 | 71.1% |
| Increfs | 48,842,273 | 26.9% |
| Decrefs | 58,391,756 | 28.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 18,000 | 15.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,694,002 |  |
| Method cache misses | 262,696 |  |
| Method cache collisions | 279,718 |  |
| Method cache dunder hits | 5,107,100 |  |
| Method cache dunder misses | 18,496 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 900 | 0 | 9,782,422 |
| 1 | 81 | 0 | 2,493,062 |
| 2 | 1 | 33 | 311,892 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 16,400 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 949,770 |  |
| Uops executed | 41,854,946 | 44.07 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 16,400 |  |
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
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 177,016 | 18.6% |
| <= 16 | 205,004 | 21.6% |
| <= 32 | 42,702 | 4.5% |
| <= 64 | 92,710 | 9.8% |
| <= 128 | 430,653 | 45.3% |
| <= 256 | 180 | 0.0% |
| <= 512 | 385 | 0.0% |
| <= 1,024 | 899 | 0.1% |
| <= 2,048 | 187 | 0.0% |
| <= 4,096 | 16 | 0.0% |
| <= 8,192 | 18 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 11,307,944 | 27.0% | 27.0% |  |
| LOAD_FAST | 3,978,489 | 9.5% | 36.5% |  |
| _GUARD_TYPE_VERSION | 3,517,429 | 8.4% | 44.9% |  |
| _POP_JUMP_IF_TRUE | 1,929,525 | 4.6% | 49.5% |  |
| STORE_FAST | 1,536,274 | 3.7% | 53.2% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,235,515 | 3.0% | 56.2% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,235,515 | 3.0% | 59.1% |  |
| _LOAD_ATTR_SLOT | 1,169,794 | 2.8% | 61.9% |  |
| _EXIT_TRACE | 931,711 | 2.2% | 64.1% |  |
| TO_BOOL_BOOL | 836,046 | 2.0% | 66.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 835,646 | 2.0% | 68.1% |  |
| LOAD_CONST | 755,820 | 1.8% | 69.9% |  |
| _GUARD_GLOBALS_VERSION | 664,441 | 1.6% | 71.5% |  |
| _SAVE_CURRENT_IP | 511,326 | 1.2% | 72.7% |  |
| _CHECK_PEP_523 | 502,326 | 1.2% | 73.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 502,326 | 1.2% | 75.1% |  |
| _CHECK_STACK_SPACE | 502,326 | 1.2% | 76.3% |  |
| _INIT_CALL_PY_EXACT_ARGS | 502,326 | 1.2% | 77.5% |  |
| _PUSH_FRAME | 502,326 | 1.2% | 78.7% |  |
| _ITER_CHECK_LIST | 487,595 | 1.2% | 79.9% |  |
| _IS_ITER_EXHAUSTED_LIST | 487,595 | 1.2% | 81.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 421,492 | 1.0% | 82.1% |  |
| LOAD_ATTR | 415,114 | 1.0% | 83.1% |  |
| RESUME_CHECK | 377,917 | 0.9% | 84.0% |  |
| _POP_JUMP_IF_FALSE | 374,548 | 0.9% | 84.9% |  |
| _ITER_CHECK_RANGE | 347,277 | 0.8% | 85.7% |  |
| _IS_ITER_EXHAUSTED_RANGE | 347,277 | 0.8% | 86.5% |  |
| _GUARD_BUILTINS_VERSION | 345,461 | 0.8% | 87.4% |  |
| _LOAD_GLOBAL_BUILTINS | 345,461 | 0.8% | 88.2% |  |
| _ITER_NEXT_RANGE | 326,416 | 0.8% | 89.0% |  |
| _LOAD_GLOBAL_MODULE | 318,980 | 0.8% | 89.7% |  |
| _ITER_NEXT_LIST | 313,401 | 0.7% | 90.5% |  |
| PUSH_NULL | 290,749 | 0.7% | 91.2% |  |
| POP_TOP | 276,051 | 0.7% | 91.8% |  |
| BUILD_LIST | 272,476 | 0.7% | 92.5% |  |
| CALL_INTRINSIC_1 | 272,476 | 0.7% | 93.1% |  |
| LIST_EXTEND | 272,476 | 0.7% | 93.8% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 189,789 | 0.5% | 94.2% |  |
| _GUARD_KEYS_VERSION | 189,789 | 0.5% | 94.7% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 180,789 | 0.4% | 95.1% |  |
| _JUMP_TO_TOP | 149,138 | 0.4% | 95.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 135,708 | 0.3% | 95.8% |  |
| _IS_NONE | 125,868 | 0.3% | 96.1% |  |
| TO_BOOL_INT | 120,048 | 0.3% | 96.4% |  |
| COMPARE_OP_INT | 110,981 | 0.3% | 96.6% |  |
| CALL_ISINSTANCE | 108,000 | 0.3% | 96.9% |  |
| CALL_LEN | 92,861 | 0.2% | 97.1% |  |
| TO_BOOL | 91,957 | 0.2% | 97.3% | 9.8% |
| CONTAINS_OP | 81,000 | 0.2% | 97.5% |  |
| BINARY_OP | 80,690 | 0.2% | 97.7% |  |
| COPY | 69,205 | 0.2% | 97.9% |  |
| BINARY_SUBSCR | 63,000 | 0.2% | 98.0% |  |
| _GUARD_DORV_VALUES | 62,181 | 0.1% | 98.2% |  |
| _STORE_ATTR_INSTANCE_VALUE | 62,181 | 0.1% | 98.3% |  |
| SWAP | 60,629 | 0.1% | 98.5% |  |
| _ITER_CHECK_TUPLE | 45,420 | 0.1% | 98.6% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 45,420 | 0.1% | 98.7% |  |
| BUILD_TUPLE | 44,150 | 0.1% | 98.8% |  |
| _CHECK_ATTR_MODULE | 43,409 | 0.1% | 98.9% |  |
| _LOAD_ATTR_MODULE | 43,409 | 0.1% | 99.0% |  |
| LOAD_FAST_CHECK | 43,008 | 0.1% | 99.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 43,008 | 0.1% | 99.2% |  |
| CALL_BUILTIN_FAST | 36,600 | 0.1% | 99.3% |  |
| _ITER_NEXT_TUPLE | 36,300 | 0.1% | 99.4% |  |
| TO_BOOL_NONE | 36,000 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 33,361 | 0.1% | 99.6% |  |
| LOAD_DEREF | 26,940 | 0.1% | 99.6% |  |
| _STORE_ATTR_SLOT | 24,504 | 0.1% | 99.7% |  |
| TO_BOOL_LIST | 24,439 | 0.1% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 24,236 | 0.1% | 99.8% |  |
| CALL_BUILTIN_O | 18,273 | 0.0% | 99.8% |  |
| _GUARD_BOTH_INT | 18,273 | 0.0% | 99.9% |  |
| _BINARY_OP_SUBTRACT_INT | 18,273 | 0.0% | 99.9% |  |
| _POP_FRAME | 9,000 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 9,000 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 6,442 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 900 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 900 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 9,520 |
| FOR_ITER | 6,880 |


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
