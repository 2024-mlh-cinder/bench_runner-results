
# Pystats results

- benchmark: tornado_http
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 55,700,840 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,959,945 | 7.1% | 27.8% | 0.1% |
| RESUME_CHECK | 14,725,841 | 5.5% | 33.3% | 0.0% |
| LOAD_CONST | 11,994,180 | 4.5% | 37.7% |  |
| POP_JUMP_IF_FALSE | 10,533,385 | 3.9% | 41.6% |  |
| RETURN_VALUE | 8,669,261 | 3.2% | 44.9% |  |
| CALL_PY_EXACT_ARGS | 8,180,084 | 3.0% | 47.9% | 0.6% |
| STORE_FAST | 8,116,919 | 3.0% | 50.9% |  |
| LOAD_GLOBAL_MODULE | 7,926,244 | 2.9% | 53.9% | 0.0% |
| LOAD_FAST_LOAD_FAST | 7,704,797 | 2.9% | 56.7% |  |
| POP_TOP | 7,578,976 | 2.8% | 59.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,590,711 | 2.5% | 62.0% | 0.9% |
| TO_BOOL_BOOL | 6,584,859 | 2.5% | 64.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 6,084,969 | 2.3% | 66.7% | 0.1% |
| RETURN_CONST | 5,916,093 | 2.2% | 68.9% |  |
| LOAD_GLOBAL_BUILTIN | 5,207,157 | 1.9% | 70.9% | 0.0% |
| CALL | 4,724,124 | 1.8% | 72.6% |  |
| INTERPRETER_EXIT | 4,277,505 | 1.6% | 74.2% |  |
| LOAD_ATTR | 4,129,630 | 1.5% | 75.8% |  |
| POP_JUMP_IF_NONE | 4,071,006 | 1.5% | 77.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,253,932 | 1.2% | 78.5% | 0.6% |
| POP_JUMP_IF_TRUE | 3,059,075 | 1.1% | 79.6% |  |
| STORE_ATTR_SLOT | 2,724,989 | 1.0% | 80.6% | 19.0% |
| COMPARE_OP_INT | 2,555,986 | 1.0% | 81.6% | 0.0% |
| PUSH_NULL | 2,424,031 | 0.9% | 82.5% |  |
| LOAD_ATTR_MODULE | 2,349,195 | 0.9% | 83.4% |  |
| NOP | 2,267,904 | 0.8% | 84.2% |  |
| LOAD_ATTR_SLOT | 2,092,477 | 0.8% | 85.0% | 10.6% |
| COPY | 1,792,595 | 0.7% | 85.7% |  |
| LOAD_DEREF | 1,560,691 | 0.6% | 86.2% |  |
| CALL_ISINSTANCE | 1,555,953 | 0.6% | 86.8% |  |
| POP_JUMP_IF_NOT_NONE | 1,242,736 | 0.5% | 87.3% |  |
| CALL_BUILTIN_FAST | 1,239,480 | 0.5% | 87.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,133,250 | 0.4% | 88.2% | 8.3% |
| TO_BOOL_NONE | 1,062,975 | 0.4% | 88.6% | 1.5% |
| BUILD_TUPLE | 1,033,335 | 0.4% | 88.9% |  |
| SWAP | 1,030,863 | 0.4% | 89.3% |  |
| ENTER_EXECUTOR | 962,613 | 0.4% | 89.7% |  |
| TO_BOOL | 934,381 | 0.3% | 90.0% |  |
| BINARY_OP | 846,820 | 0.3% | 90.3% |  |
| BINARY_OP_ADD_INT | 812,194 | 0.3% | 90.6% |  |
| CALL_FUNCTION_EX | 807,629 | 0.3% | 90.9% |  |
| CALL_LEN | 750,670 | 0.3% | 91.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 749,194 | 0.3% | 91.5% | 3.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 725,399 | 0.3% | 91.8% |  |
| STORE_FAST_STORE_FAST | 721,199 | 0.3% | 92.0% |  |
| BINARY_SUBSCR_DICT | 676,682 | 0.3% | 92.3% |  |
| BUILD_LIST | 662,247 | 0.2% | 92.5% |  |
| BINARY_OP_SUBTRACT_INT | 626,850 | 0.2% | 92.8% |  |
| TO_BOOL_INT | 612,203 | 0.2% | 93.0% | 0.7% |
| CONTAINS_OP | 595,320 | 0.2% | 93.2% |  |
| BUILD_MAP | 593,580 | 0.2% | 93.4% |  |
| GET_ITER | 588,803 | 0.2% | 93.7% |  |
| COPY_FREE_VARS | 581,608 | 0.2% | 93.9% |  |
| LOAD_ATTR_WITH_HINT | 575,646 | 0.2% | 94.1% | 2.2% |
| JUMP_FORWARD | 550,550 | 0.2% | 94.3% |  |
| LOAD_ATTR_CLASS | 550,200 | 0.2% | 94.5% | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 540,899 | 0.2% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 534,474 | 0.2% | 94.9% |  |
| IS_OP | 432,720 | 0.2% | 95.1% |  |
| YIELD_VALUE | 432,000 | 0.2% | 95.2% |  |
| CALL_PY_WITH_DEFAULTS | 426,454 | 0.2% | 95.4% |  |
| STORE_SUBSCR_DICT | 423,360 | 0.2% | 95.5% |  |
| BINARY_SLICE | 414,660 | 0.2% | 95.7% |  |
| BINARY_SUBSCR_GETITEM | 369,180 | 0.1% | 95.8% |  |
| DICT_MERGE | 359,220 | 0.1% | 96.0% |  |
| CALL_KW | 345,214 | 0.1% | 96.1% |  |
| GET_AWAITABLE | 342,000 | 0.1% | 96.2% |  |
| PUSH_EXC_INFO | 338,806 | 0.1% | 96.3% |  |
| POP_EXCEPT | 338,806 | 0.1% | 96.5% |  |
| END_SEND | 333,000 | 0.1% | 96.6% |  |
| CHECK_EXC_MATCH | 331,256 | 0.1% | 96.7% |  |
| FOR_ITER_LIST | 312,927 | 0.1% | 96.8% |  |
| MAKE_CELL | 303,549 | 0.1% | 96.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 288,240 | 0.1% | 97.1% | 3.1% |
| JUMP_BACKWARD | 280,080 | 0.1% | 97.2% |  |
| MAKE_FUNCTION | 271,494 | 0.1% | 97.3% |  |
| COMPARE_OP_FLOAT | 265,367 | 0.1% | 97.4% |  |
| FOR_ITER | 263,840 | 0.1% | 97.5% |  |
| BINARY_SUBSCR | 253,002 | 0.1% | 97.6% |  |
| SEND | 252,400 | 0.1% | 97.6% |  |
| RETURN_GENERATOR | 252,060 | 0.1% | 97.7% |  |
| EXIT_INIT_CHECK | 243,240 | 0.1% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 243,240 | 0.1% | 97.9% |  |
| LIST_EXTEND | 235,374 | 0.1% | 98.0% |  |
| CALL_INTRINSIC_1 | 226,374 | 0.1% | 98.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 220,788 | 0.1% | 98.2% | 45.6% |
| TO_BOOL_STR | 216,740 | 0.1% | 98.3% | 2.2% |
| SEND_GEN | 216,000 | 0.1% | 98.3% |  |
| COMPARE_OP_STR | 207,420 | 0.1% | 98.4% |  |
| FOR_ITER_GEN | 207,000 | 0.1% | 98.5% |  |
| STORE_ATTR | 200,380 | 0.1% | 98.6% |  |
| CALL_LIST_APPEND | 191,476 | 0.1% | 98.6% |  |
| STORE_SUBSCR | 180,580 | 0.1% | 98.7% |  |
| BEFORE_WITH | 173,734 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 171,360 | 0.1% | 98.8% |  |
| BINARY_OP_ADD_UNICODE | 171,060 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 156,457 | 0.1% | 99.0% |  |
| DELETE_FAST | 155,794 | 0.1% | 99.0% |  |
| EXTENDED_ARG | 153,180 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 153,180 | 0.1% | 99.1% |  |
| STORE_FAST_LOAD_FAST | 153,060 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 143,820 | 0.1% | 99.2% |  |
| COMPARE_OP | 133,214 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 126,912 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 126,000 | 0.0% | 99.4% |  |
| CALL_BUILTIN_CLASS | 103,856 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 91,614 | 0.0% | 99.5% |  |
| STORE_DEREF | 90,360 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 90,060 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 90,060 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 90,000 | 0.0% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 90,000 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 81,120 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_LIST_INT | 74,020 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 69,776 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 63,240 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 63,180 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 58,782 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 54,060 | 0.0% | 99.8% |  |
| RERAISE | 54,000 | 0.0% | 99.8% |  |
| BUILD_SLICE | 54,000 | 0.0% | 99.8% |  |
| UNARY_INVERT | 45,120 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 45,120 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 45,120 | 0.0% | 99.9% |  |
| END_FOR | 45,000 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 44,882 | 0.0% | 99.9% | 9.4% |
| TO_BOOL_ALWAYS_TRUE | 36,240 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 28,843 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 22,436 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 19,903 | 0.0% | 100.0% |  |
| BUILD_STRING | 18,060 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 18,000 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 18,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 10,048 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 9,060 | 0.0% | 100.0% |  |
| UNARY_NOT | 9,000 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BUILD_SET | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 9,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,288 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 120 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| IMPORT_FROM | 60 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,436,139 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 8,559,947 | 3.2% | 9.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,678,420 | 2.9% | 12.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,547,150 | 2.1% | 14.2% |
| STORE_FAST LOAD_FAST | 4,987,709 | 1.9% | 16.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,810,983 | 1.8% | 17.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,512,695 | 1.7% | 19.5% |
| CACHE RESUME_CHECK | 4,021,819 | 1.5% | 21.0% |
| RETURN_CONST POP_TOP | 3,909,659 | 1.5% | 22.5% |
| LOAD_CONST LOAD_FAST | 3,887,272 | 1.4% | 23.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,854,034 | 1.4% | 25.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,707,186 | 1.4% | 26.8% |
| POP_JUMP_IF_NONE LOAD_FAST | 3,366,023 | 1.3% | 28.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,356,765 | 1.2% | 29.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,133,659 | 1.2% | 30.4% |
| POP_TOP LOAD_FAST | 2,938,772 | 1.1% | 31.5% |
| RETURN_VALUE INTERPRETER_EXIT | 2,792,544 | 1.0% | 32.6% |
| LOAD_FAST LOAD_ATTR | 2,677,066 | 1.0% | 33.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,523,441 | 0.9% | 34.5% |
| LOAD_FAST LOAD_CONST | 2,495,099 | 0.9% | 35.4% |
| LOAD_FAST RETURN_VALUE | 2,374,460 | 0.9% | 36.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,297,190 | 0.9% | 37.2% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 2,276,178 | 0.8% | 38.0% |
| POP_TOP RETURN_CONST | 2,213,275 | 0.8% | 38.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,109,814 | 0.8% | 39.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,090,865 | 0.8% | 40.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,080,029 | 0.8% | 41.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,026,183 | 0.8% | 41.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,006,673 | 0.7% | 42.7% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,955,645 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,706,184 | 0.6% | 44.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,686,873 | 0.6% | 44.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,674,876 | 0.6% | 45.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,634,300 | 0.6% | 45.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,631,246 | 0.6% | 46.5% |
| RETURN_VALUE STORE_FAST | 1,599,037 | 0.6% | 47.1% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,542,606 | 0.6% | 47.7% |
| CALL STORE_FAST | 1,531,497 | 0.6% | 48.2% |
| LOAD_FAST CALL | 1,531,000 | 0.6% | 48.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,495,799 | 0.6% | 49.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,471,972 | 0.5% | 49.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,434,811 | 0.5% | 50.4% |
| RETURN_VALUE TO_BOOL_BOOL | 1,422,543 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,411,658 | 0.5% | 51.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,402,633 | 0.5% | 52.0% |
| LOAD_FAST STORE_ATTR_SLOT | 1,368,904 | 0.5% | 52.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,346,332 | 0.5% | 53.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,308,097 | 0.5% | 53.5% |
| LOAD_CONST COMPARE_OP_INT | 1,287,911 | 0.5% | 54.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,278,557 | 0.5% | 54.5% |
| RETURN_CONST INTERPRETER_EXIT | 1,277,901 | 0.5% | 54.9% |
| NOP LOAD_FAST | 1,267,803 | 0.5% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,254,431 | 0.5% | 55.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,111,759 | 0.4% | 56.3% |
| PUSH_NULL LOAD_FAST | 1,035,017 | 0.4% | 56.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 976,449 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 961,008 | 0.4% | 57.4% |
| RESUME_CHECK NOP | 934,187 | 0.3% | 57.8% |
| LOAD_CONST STORE_FAST | 911,921 | 0.3% | 58.1% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 909,888 | 0.3% | 58.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 878,411 | 0.3% | 58.8% |
| LOAD_ATTR LOAD_FAST | 877,210 | 0.3% | 59.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 844,013 | 0.3% | 59.4% |
| LOAD_FAST COPY | 836,164 | 0.3% | 59.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 818,460 | 0.3% | 60.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 806,668 | 0.3% | 60.3% |
| LOAD_CONST LOAD_CONST | 802,585 | 0.3% | 60.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 797,853 | 0.3% | 60.9% |
| TO_BOOL POP_JUMP_IF_FALSE | 787,526 | 0.3% | 61.2% |
| STORE_ATTR_SLOT LOAD_CONST | 784,886 | 0.3% | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 783,260 | 0.3% | 61.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 782,776 | 0.3% | 62.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 756,153 | 0.3% | 62.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 748,140 | 0.3% | 62.6% |
| CALL POP_TOP | 737,893 | 0.3% | 62.9% |
| RETURN_VALUE RETURN_VALUE | 729,180 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 716,008 | 0.3% | 63.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 695,103 | 0.3% | 63.7% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 691,984 | 0.3% | 64.0% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 691,984 | 0.3% | 64.2% |
| POP_TOP LOAD_CONST | 685,283 | 0.3% | 64.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 675,360 | 0.3% | 64.7% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 669,866 | 0.2% | 65.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 659,856 | 0.2% | 65.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 653,361 | 0.2% | 65.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 651,874 | 0.2% | 65.7% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 641,246 | 0.2% | 65.9% |
| LOAD_FAST CALL_BUILTIN_FAST | 628,260 | 0.2% | 66.2% |
| CALL LOAD_FAST | 627,028 | 0.2% | 66.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 620,751 | 0.2% | 66.6% |
| CALL_BUILTIN_FAST STORE_FAST | 610,920 | 0.2% | 66.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 605,594 | 0.2% | 67.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 595,080 | 0.2% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 594,120 | 0.2% | 67.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 588,638 | 0.2% | 67.8% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 575,406 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 568,981 | 0.2% | 68.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 550,303 | 0.2% | 68.4% |
| PUSH_NULL CALL | 547,366 | 0.2% | 68.6% |
| COPY_FREE_VARS RESUME_CHECK | 545,488 | 0.2% | 68.8% |


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

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,021,819 | 93.8% |
| COPY_FREE_VARS | 174,626 | 4.1% |
| POP_TOP | 72,060 | 1.7% |
| RETURN_GENERATOR | 9,000 | 0.2% |
| MAKE_CELL | 9,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 83,734 | 48.2% |
| RETURN_VALUE | 81,000 | 46.6% |
| LOAD_GLOBAL_MODULE | 9,000 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 173,734 | 100.0% |


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
| LOAD_CONST | 252,362 | 99.7% |
| BINARY_SUBSCR | 640 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 135,000 | 53.4% |
| LOAD_FAST | 45,000 | 17.8% |
| CONVERT_VALUE | 18,000 | 7.1% |
| BINARY_SUBSCR_LIST_INT | 9,155 | 3.6% |
| CALL_LEN | 9,060 | 3.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 292,462 | 88.3% |
| BUILD_TUPLE | 18,060 | 5.5% |
| LOAD_ATTR_MODULE | 11,734 | 3.5% |
| LOAD_GLOBAL_MODULE | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 331,256 | 100.0% |


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
| LOAD_FAST | 241,548 | 41.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 108,180 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,279 | 12.3% |
| LOAD_ATTR | 54,000 | 9.2% |
| BINARY_SLICE | 27,180 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 303,387 | 51.5% |
| FOR_ITER | 109,800 | 18.6% |
| FOR_ITER_TUPLE | 54,180 | 9.2% |
| CALL_PY_EXACT_ARGS | 54,000 | 9.2% |
| LOAD_FAST_AND_CLEAR | 36,060 | 6.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,792,544 | 65.3% |
| RETURN_CONST | 1,277,901 | 29.9% |
| YIELD_VALUE | 189,000 | 4.4% |
| RETURN_GENERATOR | 18,060 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 271,494 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 118,434 | 43.6% |
| CALL | 90,000 | 33.1% |
| LOAD_FAST | 36,000 | 13.3% |
| CALL_PY_EXACT_ARGS | 18,000 | 6.6% |
| STORE_DEREF | 9,000 | 3.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 934,187 | 41.2% |
| POP_JUMP_IF_FALSE | 336,225 | 14.8% |
| STORE_FAST | 290,585 | 12.8% |
| STORE_ATTR_INSTANCE_VALUE | 228,686 | 10.1% |
| POP_JUMP_IF_TRUE | 206,231 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,267,803 | 55.9% |
| LOAD_GLOBAL_MODULE | 442,220 | 19.5% |
| LOAD_FAST_LOAD_FAST | 225,120 | 9.9% |
| LOAD_DEREF | 100,622 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 90,060 | 4.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 246,012 | 72.6% |
| SWAP | 45,000 | 13.3% |
| COPY | 27,000 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 9,060 | 2.7% |
| STORE_SUBSCR_DICT | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 217,570 | 64.2% |
| RETURN_VALUE | 45,000 | 13.3% |
| RERAISE | 27,000 | 8.0% |
| DELETE_FAST | 18,000 | 5.3% |
| ENTER_EXECUTOR | 11,734 | 3.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,909,659 | 51.6% |
| CALL | 737,893 | 9.7% |
| CALL_METHOD_DESCRIPTOR_O | 620,751 | 8.2% |
| POP_JUMP_IF_FALSE | 450,084 | 5.9% |
| CALL_FUNCTION_EX | 374,215 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,938,772 | 38.8% |
| RETURN_CONST | 2,213,275 | 29.2% |
| LOAD_CONST | 685,283 | 9.0% |
| ENTER_EXECUTOR | 528,535 | 7.0% |
| RESUME_CHECK | 252,060 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 261,120 | 77.1% |
| RERAISE | 27,000 | 8.0% |
| CALL | 22,184 | 6.5% |
| ENTER_EXECUTOR | 9,060 | 2.7% |
| RAISE_VARARGS | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300,072 | 88.6% |
| LOAD_GLOBAL_MODULE | 29,734 | 8.8% |
| LOAD_FAST | 9,000 | 2.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,278,557 | 52.7% |
| LOAD_ATTR | 499,495 | 20.6% |
| LOAD_FAST | 348,559 | 14.4% |
| LOAD_DEREF | 153,240 | 6.3% |
| RETURN_VALUE | 99,060 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,017 | 42.7% |
| CALL | 547,366 | 22.6% |
| LOAD_FAST_LOAD_FAST | 533,565 | 22.0% |
| LOAD_GLOBAL_MODULE | 81,100 | 3.3% |
| LOAD_CONST | 71,580 | 3.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 198,000 | 78.6% |
| COPY_FREE_VARS | 18,060 | 7.2% |
| MAKE_CELL | 9,000 | 3.6% |
| CALL_PY_WITH_DEFAULTS | 9,000 | 3.6% |
| CALL_KW | 9,000 | 3.6% |

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
| LOAD_FAST | 2,374,460 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,026,183 | 23.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 466,920 | 5.4% |
| CALL | 464,163 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,792,544 | 32.2% |
| STORE_FAST | 1,599,037 | 18.4% |
| TO_BOOL_BOOL | 1,422,543 | 16.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| LOAD_FAST | 452,214 | 5.2% |


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
| LOAD_DEREF | 18,000 | 10.0% |
| LOAD_CONST | 18,000 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 416,724 | 44.6% |
| LOAD_ATTR_INSTANCE_VALUE | 389,924 | 41.7% |
| LOAD_ATTR | 90,134 | 9.6% |
| COPY | 26,420 | 2.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,100 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 787,526 | 84.3% |
| POP_JUMP_IF_TRUE | 144,413 | 15.5% |
| TO_BOOL | 1,530 | 0.2% |
| TO_BOOL_BOOL | 575 | 0.1% |
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
| LOAD_GLOBAL_MODULE | 137,989 | 16.3% |
| LOAD_CONST | 127,117 | 15.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 117,000 | 13.8% |
| LOAD_FAST | 84,668 | 10.0% |
| LOAD_ATTR_MODULE | 77,784 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 239,964 | 28.3% |
| STORE_FAST | 154,721 | 18.3% |
| COPY | 99,037 | 11.7% |
| RETURN_VALUE | 72,060 | 8.5% |
| LOAD_FAST | 72,000 | 8.5% |


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
| STORE_FAST | 83,814 | 12.7% |
| LOAD_FAST_LOAD_FAST | 80,460 | 12.1% |
| RESUME_CHECK | 54,180 | 8.2% |
| SWAP | 36,060 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 496,554 | 75.0% |
| STORE_FAST | 102,273 | 15.4% |
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
| LOAD_FAST | 382,466 | 37.0% |
| LOAD_FAST_LOAD_FAST | 288,240 | 27.9% |
| LOAD_GLOBAL_BUILTIN | 117,300 | 11.4% |
| LOAD_GLOBAL_MODULE | 72,180 | 7.0% |
| LOAD_ATTR_MODULE | 54,000 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 144,000 | 13.9% |
| RETURN_VALUE | 135,360 | 13.1% |
| LOAD_CONST | 118,434 | 11.5% |
| CALL_ISINSTANCE | 117,300 | 11.4% |
| CONTAINS_OP | 90,060 | 8.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,531,000 | 32.4% |
| PUSH_NULL | 547,366 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 459,160 | 9.7% |
| LOAD_GLOBAL_MODULE | 443,212 | 9.4% |
| LOAD_CONST | 397,574 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,531,497 | 32.4% |
| POP_TOP | 737,893 | 15.6% |
| LOAD_FAST | 627,028 | 13.3% |
| RETURN_VALUE | 464,163 | 9.8% |
| BINARY_SUBSCR_DICT | 315,060 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 359,220 | 44.5% |
| ENTER_EXECUTOR | 272,101 | 33.7% |
| LOAD_FAST | 74,854 | 9.3% |
| CALL_INTRINSIC_1 | 57,054 | 7.1% |
| BUILD_MAP | 44,400 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 374,215 | 46.3% |
| RETURN_VALUE | 164,194 | 20.3% |
| RESUME_CHECK | 99,060 | 12.3% |
| STORE_FAST | 89,520 | 11.1% |
| CALL | 62,460 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 217,374 | 96.0% |
| RERAISE | 9,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 115,920 | 51.2% |
| CALL_FUNCTION_EX | 57,054 | 25.2% |
| LOAD_CONST | 44,400 | 19.6% |
| RERAISE | 9,000 | 4.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300,214 | 87.0% |
| ENTER_EXECUTOR | 45,000 | 13.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 198,180 | 57.4% |
| STORE_FAST | 74,734 | 21.6% |
| COPY_FREE_VARS | 18,000 | 5.2% |
| LOAD_FAST | 9,120 | 2.6% |
| RETURN_VALUE | 9,060 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 87,481 | 65.7% |
| LOAD_ATTR | 18,000 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 6.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.8% |
| LOAD_ATTR_CLASS | 9,000 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 87,581 | 65.7% |
| POP_JUMP_IF_TRUE | 45,000 | 33.8% |
| COMPARE_OP | 440 | 0.3% |
| COMPARE_OP_INT | 113 | 0.1% |
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
| STORE_FAST | 9,000 | 1.5% |


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
| LOAD_FAST | 836,164 | 46.6% |
| LOAD_CONST | 189,060 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 171,000 | 9.5% |
| BINARY_OP | 99,037 | 5.5% |
| CONTAINS_OP | 90,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 691,984 | 38.6% |
| LOAD_FAST | 342,000 | 19.1% |
| TO_BOOL_BOOL | 243,000 | 13.6% |
| TO_BOOL_NONE | 143,972 | 8.0% |
| TO_BOOL_INT | 120,039 | 6.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 216,275 | 37.2% |
| CACHE | 174,626 | 30.0% |
| CALL | 90,120 | 15.5% |
| LOAD_ATTR_PROPERTY | 63,000 | 10.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,347 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 545,488 | 93.8% |
| RETURN_GENERATOR | 18,060 | 3.1% |
| MAKE_CELL | 18,060 | 3.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 81,000 | 52.0% |
| STORE_ATTR_INSTANCE_VALUE | 18,000 | 11.6% |
| POP_EXCEPT | 18,000 | 11.6% |
| NOP | 18,000 | 11.6% |
| POP_TOP | 11,734 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 81,000 | 52.0% |
| RETURN_CONST | 36,000 | 23.1% |
| LOAD_FAST | 20,734 | 13.3% |
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
| POP_TOP | 528,535 | 54.9% |
| POP_JUMP_IF_TRUE | 110,892 | 11.5% |
| CALL_LIST_APPEND | 74,236 | 7.7% |
| STORE_ATTR_INSTANCE_VALUE | 63,000 | 6.5% |
| POP_JUMP_IF_FALSE | 54,239 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 272,101 | 28.3% |
| CALL | 136,440 | 14.2% |
| LOAD_FAST | 101,971 | 10.6% |
| RESUME_CHECK | 86,488 | 9.0% |
| JUMP_BACKWARD | 81,060 | 8.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 90,000 | 58.8% |
| POP_JUMP_IF_TRUE | 45,000 | 29.4% |
| STORE_ATTR_INSTANCE_VALUE | 9,000 | 5.9% |
| COMPARE_OP_STR | 9,000 | 5.9% |
| JUMP_BACKWARD | 60 | 0.0% |

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
| GET_ITER | 109,800 | 41.6% |
| SWAP | 18,000 | 6.8% |
| LOAD_FAST | 18,000 | 6.8% |
| FOR_ITER | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 100,680 | 38.2% |
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
| LOAD_GLOBAL_MODULE | 234,120 | 54.1% |
| LOAD_FAST | 81,300 | 18.8% |
| LOAD_CONST | 81,060 | 18.7% |
| LOAD_FAST_LOAD_FAST | 18,240 | 4.2% |
| LOAD_DEREF | 18,000 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 351,660 | 81.3% |
| RETURN_VALUE | 54,060 | 12.5% |
| STORE_FAST | 9,000 | 2.1% |
| POP_JUMP_IF_TRUE | 9,000 | 2.1% |
| COPY | 9,000 | 2.1% |


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
| FOR_ITER_TUPLE | 60 | 0.0% |
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
| STORE_FAST | 325,206 | 59.1% |
| POP_TOP | 99,060 | 18.0% |
| STORE_ATTR_INSTANCE_VALUE | 36,339 | 6.6% |
| STORE_ATTR | 18,000 | 3.3% |
| POP_JUMP_IF_TRUE | 18,000 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 359,387 | 65.3% |
| LOAD_CONST | 69,547 | 12.6% |
| LOAD_FAST_LOAD_FAST | 45,000 | 8.2% |
| LOAD_GLOBAL_MODULE | 27,000 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 22,356 | 4.1% |


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
| LOAD_ATTR_SLOT | 11,814 | 5.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 3.8% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 217,374 | 92.4% |
| LOAD_FAST | 18,000 | 7.6% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,677,066 | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE | 651,874 | 15.8% |
| LOAD_ATTR_WITH_HINT | 252,000 | 6.1% |
| LOAD_GLOBAL_MODULE | 225,715 | 5.5% |
| LOAD_DEREF | 111,906 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 877,210 | 21.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 669,866 | 16.2% |
| PUSH_NULL | 499,495 | 12.1% |
| LOAD_CONST | 360,067 | 8.7% |
| CALL_PY_EXACT_ARGS | 239,531 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,495,099 | 20.8% |
| STORE_ATTR_INSTANCE_VALUE | 1,254,431 | 10.5% |
| LOAD_CONST | 802,585 | 6.7% |
| POP_JUMP_IF_FALSE | 797,853 | 6.7% |
| STORE_ATTR_SLOT | 784,886 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,887,272 | 32.4% |
| COMPARE_OP_INT | 1,287,911 | 10.7% |
| STORE_FAST | 911,921 | 7.6% |
| LOAD_CONST | 802,585 | 6.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 476,180 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 298,903 | 19.2% |
| RESUME_CHECK | 155,203 | 9.9% |
| POP_JUMP_IF_FALSE | 127,963 | 8.2% |
| POP_JUMP_IF_TRUE | 108,240 | 6.9% |
| NOP | 100,622 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 377,820 | 24.2% |
| LOAD_ATTR_INSTANCE_VALUE | 275,529 | 17.7% |
| PUSH_NULL | 153,240 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 117,000 | 7.5% |
| LOAD_ATTR | 111,906 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,559,947 | 15.4% |
| POP_JUMP_IF_FALSE | 5,547,150 | 10.0% |
| STORE_FAST | 4,987,709 | 9.0% |
| LOAD_CONST | 3,887,272 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 3,854,034 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,436,139 | 29.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,512,695 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 3,707,186 | 6.7% |
| LOAD_ATTR | 2,677,066 | 4.8% |
| CALL_PY_EXACT_ARGS | 2,523,441 | 4.5% |


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
| LOAD_ATTR_METHOD_NO_DICT | 10,843 | 37.6% |
| STORE_FAST | 9,000 | 31.2% |
| POP_JUMP_IF_FALSE | 9,000 | 31.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 10,843 | 37.6% |
| LOAD_CONST | 9,000 | 31.2% |
| LOAD_ATTR | 9,000 | 31.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 976,449 | 12.7% |
| LOAD_GLOBAL_MODULE | 818,460 | 10.6% |
| STORE_FAST | 806,668 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 748,140 | 9.7% |
| POP_JUMP_IF_FALSE | 675,360 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,495,799 | 19.4% |
| STORE_ATTR_SLOT | 1,346,332 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 961,008 | 12.5% |
| LOAD_FAST | 653,361 | 8.5% |
| LOAD_FAST_LOAD_FAST | 550,303 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 340 | 14.9% |
| STORE_FAST | 282 | 12.3% |
| POP_JUMP_IF_FALSE | 282 | 12.3% |
| STORE_ATTR_INSTANCE_VALUE | 160 | 7.0% |
| POP_TOP | 140 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,630 | 71.2% |
| LOAD_GLOBAL_BUILTIN | 610 | 26.7% |
| LOAD_ATTR | 27 | 1.2% |
| LOAD_GLOBAL | 7 | 0.3% |
| LOAD_CONST | 7 | 0.3% |


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
| MAKE_CELL | 139,226 | 45.9% |
| CALL_PY_EXACT_ARGS | 85,046 | 28.0% |
| ENTER_EXECUTOR | 34,097 | 11.2% |
| COPY_FREE_VARS | 18,060 | 5.9% |
| CALL_KW | 9,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 155,323 | 51.2% |
| MAKE_CELL | 139,226 | 45.9% |
| RETURN_GENERATOR | 9,000 | 3.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,810,983 | 45.7% |
| COMPARE_OP_INT | 2,006,673 | 19.1% |
| TO_BOOL_NONE | 909,888 | 8.6% |
| TO_BOOL | 787,526 | 7.5% |
| CONTAINS_OP | 450,900 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,547,150 | 52.7% |
| RETURN_CONST | 1,111,759 | 10.6% |
| LOAD_CONST | 797,853 | 7.6% |
| LOAD_GLOBAL_MODULE | 756,153 | 7.2% |
| LOAD_FAST_LOAD_FAST | 675,360 | 6.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,276,178 | 55.9% |
| LOAD_FAST | 1,542,606 | 37.9% |
| LOAD_DEREF | 99,060 | 2.4% |
| LOAD_ATTR | 99,060 | 2.4% |
| LOAD_ATTR_WITH_HINT | 26,802 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,366,023 | 82.7% |
| RETURN_CONST | 209,203 | 5.1% |
| LOAD_GLOBAL_MODULE | 207,100 | 5.1% |
| LOAD_FAST_LOAD_FAST | 108,240 | 2.7% |
| NOP | 99,060 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 782,776 | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE | 342,000 | 27.5% |
| LOAD_ATTR | 81,360 | 6.5% |
| LOAD_GLOBAL_MODULE | 9,300 | 0.7% |
| RETURN_VALUE | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 433,445 | 34.9% |
| LOAD_FAST_LOAD_FAST | 325,963 | 26.2% |
| LOAD_GLOBAL_MODULE | 258,128 | 20.8% |
| LOAD_CONST | 99,000 | 8.0% |
| LOAD_DEREF | 63,120 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,674,876 | 54.8% |
| COMPARE_OP_INT | 531,300 | 17.4% |
| TO_BOOL_INT | 194,948 | 6.4% |
| TO_BOOL_STR | 180,420 | 5.9% |
| TO_BOOL_NONE | 152,758 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,434,811 | 46.9% |
| LOAD_GLOBAL_BUILTIN | 333,120 | 10.9% |
| NOP | 206,231 | 6.7% |
| LOAD_CONST | 174,062 | 5.7% |
| LOAD_FAST_LOAD_FAST | 171,240 | 5.6% |


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
| POP_JUMP_IF_FALSE | 9,000 | 16.7% |
| CALL_INTRINSIC_1 | 9,000 | 16.7% |

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
| POP_TOP | 2,213,275 | 37.4% |
| POP_JUMP_IF_FALSE | 1,111,759 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 568,981 | 9.6% |
| STORE_ATTR_SLOT | 459,403 | 7.8% |
| STORE_FAST | 295,729 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,909,659 | 66.1% |
| INTERPRETER_EXIT | 1,277,901 | 21.6% |
| EXIT_INIT_CHECK | 243,240 | 4.1% |
| STORE_FAST | 132,268 | 2.2% |
| TO_BOOL_BOOL | 99,002 | 1.7% |


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
| MAKE_FUNCTION | 118,434 | 75.7% |
| SET_FUNCTION_ATTRIBUTE | 38,023 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,291 | 34.1% |
| SET_FUNCTION_ATTRIBUTE | 38,023 | 24.3% |
| CALL | 29,063 | 18.6% |
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
| SET_FUNCTION_ATTRIBUTE | 9,000 | 10.0% |
| MAKE_FUNCTION | 9,000 | 10.0% |
| LOAD_CONST | 9,000 | 10.0% |
| JUMP_FORWARD | 9,000 | 10.0% |

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
| RETURN_VALUE | 1,599,037 | 19.7% |
| CALL | 1,531,497 | 18.9% |
| LOAD_CONST | 911,921 | 11.2% |
| CALL_BUILTIN_FAST | 610,920 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 529,391 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,987,709 | 61.4% |
| LOAD_FAST_LOAD_FAST | 806,668 | 9.9% |
| LOAD_CONST | 455,538 | 5.6% |
| LOAD_GLOBAL_BUILTIN | 372,250 | 4.6% |
| JUMP_FORWARD | 325,206 | 4.0% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 531,779 | 73.7% |
| UNPACK_SEQUENCE_LIST | 90,000 | 12.5% |
| UNPACK_SEQUENCE_TUPLE | 54,180 | 7.5% |
| STORE_FAST_STORE_FAST | 18,120 | 2.5% |
| COPY | 18,060 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,659 | 55.0% |
| LOAD_GLOBAL_MODULE | 99,000 | 13.7% |
| STORE_FAST | 72,180 | 10.0% |
| LOAD_FAST_LOAD_FAST | 63,120 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 63,000 | 8.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 425,134 | 41.2% |
| BINARY_OP_SUBTRACT_INT | 248,850 | 24.1% |
| LOAD_FAST | 144,000 | 14.0% |
| LOAD_ATTR | 41,699 | 4.0% |
| LOAD_FAST_AND_CLEAR | 36,060 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 691,984 | 67.1% |
| COPY | 81,060 | 7.9% |
| STORE_FAST | 68,699 | 6.7% |
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
| FOR_ITER | 20 | 0.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 9,000 | 97.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 1.3% |
| UNPACK_SEQUENCE_TUPLE | 40 | 0.4% |
| UNPACK_SEQUENCE | 40 | 0.4% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 81,000 | 18.8% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 81,000 | 18.8% |
| BUILD_TUPLE | 81,000 | 18.8% |
| BINARY_OP_ADD_UNICODE | 81,000 | 18.8% |
| SEND | 45,000 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 189,000 | 43.8% |
| YIELD_VALUE | 81,000 | 18.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 81,000 | 18.8% |
| STORE_FAST_LOAD_FAST | 81,000 | 18.8% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,800 | 77.3% |
| LOAD_ATTR_INSTANCE_VALUE | 11,814 | 12.9% |
| LOAD_ATTR | 9,000 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,400 | 58.3% |
| LOAD_GLOBAL_MODULE | 26,400 | 28.8% |
| STORE_FAST | 11,814 | 12.9% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,734 | 62.4% |
| LOAD_FAST_LOAD_FAST | 198,000 | 24.4% |
| CALL_LEN | 63,000 | 7.8% |
| LOAD_CONST | 44,440 | 5.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 425,134 | 52.3% |
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
| RETURN_VALUE | 9,000 | 89.6% |
| LOAD_CONST | 1,033 | 10.3% |
| BINARY_OP | 15 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,000 | 89.6% |
| CALL_BUILTIN_O | 1,033 | 10.3% |
| CALL | 15 | 0.1% |


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
| RETURN_VALUE | 45,433 | 65.1% |
| LOAD_ATTR_WITH_HINT | 9,000 | 12.9% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 12.9% |
| CALL | 6,268 | 9.0% |
| LOAD_FAST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 45,448 | 65.1% |
| RETURN_VALUE | 9,000 | 12.9% |
| LOAD_FAST | 9,000 | 12.9% |
| STORE_FAST | 6,268 | 9.0% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 423,000 | 67.5% |
| LOAD_ATTR_INSTANCE_VALUE | 72,000 | 11.5% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 10.1% |
| CALL_LEN | 45,000 | 7.2% |
| LOAD_CONST | 23,850 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 248,850 | 39.7% |
| STORE_FAST | 243,000 | 38.8% |
| LOAD_FAST | 63,000 | 10.1% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 10.1% |
| BINARY_SUBSCR_LIST_INT | 9,000 | 1.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 315,060 | 46.6% |
| LOAD_FAST | 262,502 | 38.8% |
| BUILD_TUPLE | 36,060 | 5.3% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| RETURN_VALUE | 18,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,000 | 47.9% |
| PUSH_EXC_INFO | 261,120 | 38.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 28,442 | 4.2% |
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
| LOAD_CONST | 55,865 | 75.5% |
| BINARY_SUBSCR | 9,155 | 12.4% |
| BINARY_OP_SUBTRACT_INT | 9,000 | 12.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 33,586 | 45.4% |
| LOAD_FAST | 18,060 | 24.4% |
| STORE_FAST | 11,617 | 15.7% |
| LOAD_CONST | 9,000 | 12.2% |
| TO_BOOL_BOOL | 1,442 | 1.9% |


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
| STORE_FAST | 9,060 | 5.3% |


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
| LOAD_FAST | 64,978 | 29.4% |
| LOAD_FAST_LOAD_FAST | 36,122 | 16.4% |
| CALL_BUILTIN_CLASS | 18,000 | 8.2% |
| BINARY_SLICE | 18,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 118,535 | 53.7% |
| POP_TOP | 81,000 | 36.7% |
| COPY_FREE_VARS | 19,347 | 8.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,580 | 0.7% |
| CALL_PY_EXACT_ARGS | 326 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,974 | 28.9% |
| LOAD_ATTR_INSTANCE_VALUE | 27,120 | 26.1% |
| LOAD_GLOBAL_MODULE | 10,482 | 10.1% |
| LOAD_GLOBAL_BUILTIN | 9,080 | 8.7% |
| RETURN_GENERATOR | 9,000 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,000 | 26.0% |
| GET_ITER | 22,316 | 21.5% |
| LOAD_FAST | 18,120 | 17.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 18,000 | 17.3% |
| LOAD_DEREF | 9,000 | 8.7% |


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
| LOAD_ATTR_WITH_HINT | 9,000 | 0.7% |

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
| LOAD_ATTR | 10,843 | 54.5% |
| LOAD_FAST | 9,060 | 45.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,843 | 54.5% |
| STORE_FAST | 9,060 | 45.5% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,319 | 61.8% |
| LOAD_ATTR_INSTANCE_VALUE | 21,275 | 36.2% |
| BINARY_OP_MULTIPLY_FLOAT | 1,033 | 1.8% |
| CALL | 75 | 0.1% |
| LOAD_CONST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,275 | 51.5% |
| STORE_SUBSCR_DICT | 18,000 | 30.6% |
| BINARY_SUBSCR_DICT | 9,000 | 15.3% |
| LOAD_CONST | 1,048 | 1.8% |
| POP_TOP | 399 | 0.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 844,013 | 54.2% |
| LOAD_GLOBAL_BUILTIN | 325,020 | 20.9% |
| LOAD_ATTR_MODULE | 224,400 | 14.4% |
| BUILD_TUPLE | 117,300 | 7.5% |
| LOAD_ATTR | 45,080 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,402,633 | 90.1% |
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
| LOAD_FAST | 486,240 | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE | 246,250 | 32.8% |
| BINARY_SUBSCR | 9,060 | 1.2% |
| LOAD_GLOBAL_MODULE | 9,000 | 1.2% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 227,956 | 30.4% |
| LOAD_FAST | 169,740 | 22.6% |
| LOAD_CONST | 72,240 | 9.6% |
| BINARY_OP_ADD_INT | 63,000 | 8.4% |
| BINARY_OP_SUBTRACT_INT | 45,000 | 6.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 101,468 | 53.0% |
| BUILD_TUPLE | 48,338 | 25.2% |
| ENTER_EXECUTOR | 23,510 | 12.3% |
| RETURN_VALUE | 18,120 | 9.5% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 90,000 | 47.0% |
| ENTER_EXECUTOR | 74,236 | 38.8% |
| LOAD_FAST | 18,000 | 9.4% |
| NOP | 9,000 | 4.7% |
| JUMP_BACKWARD | 180 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 476,180 | 65.6% |
| LOAD_ATTR_METHOD_NO_DICT | 153,000 | 21.1% |
| LOAD_FAST_LOAD_FAST | 63,120 | 8.7% |
| RETURN_VALUE | 18,060 | 2.5% |
| LOAD_FAST | 14,679 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 466,920 | 64.4% |
| CALL_PY_EXACT_ARGS | 81,080 | 11.2% |
| STORE_FAST | 77,819 | 10.7% |
| LOAD_CONST | 54,000 | 7.4% |
| TO_BOOL_BOOL | 18,000 | 2.5% |


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
| LOAD_FAST_LOAD_FAST | 11,814 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,294 | 37.7% |
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
| LOAD_ATTR | 669,866 | 59.1% |
| LOAD_ATTR_METHOD_NO_DICT | 434,244 | 38.3% |
| LOAD_FAST | 18,060 | 1.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,000 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 695,103 | 61.3% |
| POP_TOP | 114,448 | 10.1% |
| GET_ITER | 108,180 | 9.5% |
| LOAD_FAST | 54,180 | 4.8% |
| STORE_FAST | 49,657 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 431,691 | 57.6% |
| BUILD_TUPLE | 144,000 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 8.4% |
| LOAD_CONST | 36,040 | 4.8% |
| CALL | 27,080 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 620,751 | 82.9% |
| STORE_FAST | 73,843 | 9.9% |
| UNPACK_SEQUENCE_TUPLE | 18,000 | 2.4% |
| LOAD_CONST | 18,000 | 2.4% |
| LOAD_FAST | 9,060 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,356,765 | 41.0% |
| LOAD_FAST | 2,523,441 | 30.8% |
| LOAD_FAST_LOAD_FAST | 495,900 | 6.1% |
| LOAD_CONST | 432,160 | 5.3% |
| LOAD_ATTR | 239,531 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,678,420 | 93.9% |
| COPY_FREE_VARS | 216,275 | 2.6% |
| RETURN_GENERATOR | 198,000 | 2.4% |
| MAKE_CELL | 85,046 | 1.0% |
| TO_BOOL_BOOL | 1,477 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,000 | 25.3% |
| LOAD_FAST | 99,200 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 92,734 | 21.7% |
| PUSH_NULL | 54,260 | 12.7% |
| LOAD_ATTR | 27,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 417,394 | 97.9% |
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
| LOAD_ATTR_SLOT | 247,430 | 93.2% |
| LOAD_FAST | 11,557 | 4.4% |
| LOAD_GLOBAL_MODULE | 6,380 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 247,430 | 93.2% |
| POP_JUMP_IF_FALSE | 17,937 | 6.8% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,287,911 | 50.4% |
| LOAD_ATTR_INSTANCE_VALUE | 716,008 | 28.0% |
| LOAD_ATTR_CLASS | 288,000 | 11.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 90,000 | 3.5% |
| COPY | 81,060 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,006,673 | 78.5% |
| POP_JUMP_IF_TRUE | 531,300 | 20.8% |
| COPY | 18,000 | 0.7% |
| COMPARE_OP | 13 | 0.0% |


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
| POP_JUMP_IF_TRUE | 9,000 | 4.3% |
| EXTENDED_ARG | 9,000 | 4.3% |


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
| GET_ITER | 303,387 | 97.0% |
| SWAP | 9,000 | 2.9% |
| JUMP_BACKWARD | 420 | 0.1% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 171,939 | 54.9% |
| LOAD_FAST | 105,235 | 33.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20,278 | 6.5% |
| UNPACK_SEQUENCE_TUPLE | 9,000 | 2.9% |
| RETURN_CONST | 6,355 | 2.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 22,316 | 99.5% |
| SWAP | 60 | 0.3% |
| JUMP_BACKWARD | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,316 | 99.5% |
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
| LOAD_FAST | 16,436,139 | 86.7% |
| LOAD_FAST_LOAD_FAST | 961,008 | 5.1% |
| COPY | 691,984 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 594,120 | 3.1% |
| LOAD_DEREF | 275,529 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,133,659 | 16.5% |
| POP_JUMP_IF_NONE | 2,276,178 | 12.0% |
| RETURN_VALUE | 2,026,183 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 1,706,184 | 9.0% |
| TO_BOOL_BOOL | 1,686,873 | 8.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 1,706,184 | 52.4% |
| LOAD_FAST | 878,411 | 27.0% |
| BINARY_SLICE | 189,040 | 5.8% |
| LOAD_CONST | 99,040 | 3.0% |
| BINARY_SUBSCR_STR_INT | 81,080 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,411,658 | 43.4% |
| LOAD_CONST | 605,594 | 18.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 434,244 | 13.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 171,000 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 153,000 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,512,695 | 68.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,308,097 | 19.8% |
| LOAD_ATTR_SLOT | 441,343 | 6.7% |
| LOAD_DEREF | 92,143 | 1.4% |
| LOAD_FAST_LOAD_FAST | 81,493 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,356,765 | 50.9% |
| LOAD_FAST | 2,090,865 | 31.7% |
| LOAD_FAST_LOAD_FAST | 506,083 | 7.7% |
| LOAD_CONST | 324,060 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 107,400 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,297,190 | 97.8% |
| ENTER_EXECUTOR | 42,410 | 1.8% |
| LOAD_ATTR_MODULE | 9,000 | 0.4% |
| LOAD_ATTR | 595 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,278,557 | 54.4% |
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
| LOAD_ATTR_INSTANCE_VALUE | 153,000 | 53.1% |
| LOAD_FAST_LOAD_FAST | 63,000 | 21.9% |
| LOAD_FAST | 54,060 | 18.8% |
| LOAD_DEREF | 9,000 | 3.1% |
| ENTER_EXECUTOR | 9,000 | 3.1% |

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
| LOAD_FAST | 1,955,645 | 93.5% |
| BINARY_SUBSCR_TUPLE_INT | 90,060 | 4.3% |
| BINARY_SUBSCR_LIST_INT | 33,586 | 1.6% |
| LOAD_DEREF | 9,000 | 0.4% |
| LOAD_ATTR_SLOT | 4,171 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 641,246 | 30.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 441,343 | 21.1% |
| TO_BOOL_BOOL | 264,690 | 12.6% |
| LOAD_FAST | 258,987 | 12.4% |
| COMPARE_OP_FLOAT | 247,430 | 11.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,406 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.0% |

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
| RESUME_CHECK | 2,080,029 | 39.9% |
| LOAD_FAST | 595,080 | 11.4% |
| POP_JUMP_IF_FALSE | 486,407 | 9.3% |
| STORE_FAST | 372,250 | 7.1% |
| POP_JUMP_IF_TRUE | 333,120 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,854,034 | 74.0% |
| CALL_ISINSTANCE | 325,020 | 6.2% |
| LOAD_DEREF | 298,903 | 5.7% |
| CHECK_EXC_MATCH | 292,462 | 5.6% |
| BUILD_TUPLE | 117,300 | 2.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,634,300 | 20.6% |
| RESUME_CHECK | 1,471,972 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 783,260 | 9.9% |
| POP_JUMP_IF_FALSE | 756,153 | 9.5% |
| STORE_ATTR_INSTANCE_VALUE | 588,638 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,297,190 | 29.0% |
| LOAD_FAST | 1,631,246 | 20.6% |
| CALL_ISINSTANCE | 844,013 | 10.6% |
| LOAD_FAST_LOAD_FAST | 818,460 | 10.3% |
| CALL | 443,212 | 5.6% |


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
| CALL_PY_EXACT_ARGS | 7,678,420 | 52.1% |
| CACHE | 4,021,819 | 27.3% |
| COPY_FREE_VARS | 545,488 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 417,394 | 2.8% |
| BINARY_SUBSCR_GETITEM | 369,180 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,559,947 | 58.1% |
| LOAD_GLOBAL_BUILTIN | 2,080,029 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,471,972 | 10.0% |
| NOP | 934,187 | 6.3% |
| LOAD_CONST | 488,383 | 3.3% |


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
| LOAD_FAST | 3,707,186 | 60.9% |
| LOAD_FAST_LOAD_FAST | 1,495,799 | 24.6% |
| SWAP | 691,984 | 11.4% |
| LOAD_DEREF | 117,000 | 1.9% |
| STORE_FAST_LOAD_FAST | 63,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,109,814 | 34.7% |
| LOAD_CONST | 1,254,431 | 20.6% |
| LOAD_FAST_LOAD_FAST | 748,140 | 12.3% |
| LOAD_GLOBAL_MODULE | 588,638 | 9.7% |
| RETURN_CONST | 568,981 | 9.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,368,904 | 50.2% |
| LOAD_FAST_LOAD_FAST | 1,346,332 | 49.4% |
| STORE_ATTR_SLOT | 9,753 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 976,449 | 35.8% |
| LOAD_CONST | 784,886 | 28.8% |
| LOAD_FAST | 480,678 | 17.6% |
| RETURN_CONST | 459,403 | 16.9% |
| ENTER_EXECUTOR | 13,820 | 0.5% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,802 | 79.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 20.1% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 0.2% |

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
| RETURN_CONST | 60 | 50.0% |
| JUMP_FORWARD | 60 | 50.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,000 | 74.5% |
| CALL | 9,000 | 24.8% |
| LOAD_GLOBAL_MODULE | 240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,240 | 50.3% |
| POP_JUMP_IF_TRUE | 18,000 | 49.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,686,873 | 25.6% |
| RETURN_VALUE | 1,422,543 | 21.6% |
| CALL_ISINSTANCE | 1,402,633 | 21.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 695,103 | 10.6% |
| LOAD_FAST | 300,756 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,810,983 | 73.1% |
| POP_JUMP_IF_TRUE | 1,674,876 | 25.4% |
| EXTENDED_ARG | 90,000 | 1.4% |
| UNARY_NOT | 9,000 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 243,120 | 39.7% |
| BINARY_OP | 239,964 | 39.2% |
| COPY | 120,039 | 19.6% |
| LOAD_ATTR | 9,000 | 1.5% |
| TO_BOOL_NONE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 417,169 | 68.1% |
| POP_JUMP_IF_TRUE | 194,948 | 31.8% |
| TO_BOOL_NONE | 86 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 126,777 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| TO_BOOL | 15 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 126,912 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 641,246 | 60.3% |
| COPY | 143,972 | 13.5% |
| LOAD_FAST | 142,089 | 13.4% |
| LOAD_ATTR | 63,000 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 54,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 909,888 | 85.6% |
| POP_JUMP_IF_TRUE | 152,758 | 14.4% |
| TO_BOOL | 149 | 0.0% |
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
| FOR_ITER_LIST | 9,000 | 14.2% |
| END_SEND | 9,000 | 14.2% |
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
| BINARY_SUBSCR | 135,000 | 25.0% |
| RETURN_VALUE | 117,240 | 21.7% |
| FOR_ITER | 81,040 | 15.0% |
| YIELD_VALUE | 81,000 | 15.0% |
| STORE_FAST | 41,699 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 531,779 | 98.3% |
| LOAD_FAST | 9,060 | 1.7% |
| STORE_FAST | 60 | 0.0% |


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
| specialization.deferred |       252067 | 15.4% |
|          hit |      1381362 | 84.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 295 | 31.6% |
| Failure | 640 | 68.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 560 | 87.5% |
| out of range | 40 | 6.2% |
| other | 40 | 6.2% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       180060 | 29.8% |
|          hit |       423480 | 70.1% |

#### Specialization attempts

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
|---|---|---|
| specialization.deferred |       931939 | 8.9% |
| specialization.deopt |          495 | 0.0% |
|          hit |      9524010 | 90.8% |
|         miss |        25543 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,258 | 42.8% |
| Failure | 1,679 | 57.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 575 | 34.2% |
| sequence | 400 | 23.8% |
| float | 240 | 14.3% |
| dict | 160 | 9.5% |
| mapping | 104 | 6.2% |
| tuple | 80 | 4.8% |
| bytearray | 80 | 4.8% |
| set | 40 | 2.4% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       844914 | 31.8% |
|          hit |      1808759 | 68.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 110 | 5.8% |
| Failure | 1,796 | 94.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 758 | 42.2% |
| or | 280 | 15.6% |
| add other | 280 | 15.6% |
| remainder | 200 | 11.1% |
| add different types | 120 | 6.7% |
| multiply different types | 78 | 4.3% |
| true divide other | 40 | 2.2% |
| floor divide | 40 | 2.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4713877 | 21.1% |
| specialization.deopt |         5092 | 0.0% |
|          hit |     17337777 | 77.6% |
|         miss |       267208 | 1.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,171 | 46.8% |
| Failure | 8,168 | 53.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,565 | 19.2% |
| class no vectorcall | 1,360 | 16.7% |
| cfunc noargs | 1,006 | 12.3% |
| meth descr method fastcall keywords | 920 | 11.3% |
| meth descr varargs | 806 | 9.9% |
| cfunc varargs keywords | 716 | 8.8% |
| class mutable | 420 | 5.1% |
| other | 375 | 4.6% |
| meth descr varargs keywords | 320 | 3.9% |
| init not simple | 180 | 2.2% |
| no dict | 180 | 2.2% |
| operator wrapper | 120 | 1.5% |
| cfunc varargs | 80 | 1.0% |
| wrong number arguments | 60 | 0.7% |
| cmethod | 40 | 0.5% |
| init not python | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       132581 | 4.1% |
| specialization.deopt |           13 | 0.0% |
|          hit |      3126898 | 95.9% |
|         miss |         1115 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 193 | 29.9% |
| Failure | 453 | 70.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 120 | 26.5% |
| other | 100 | 22.1% |
| bytes | 80 | 17.7% |
| float long | 53 | 11.7% |
| tuple | 40 | 8.8% |
| big int | 40 | 8.8% |
| bool | 20 | 4.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       263280 | 30.3% |
|          hit |       605603 | 69.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 560 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 340 | 60.7% |
| ascii string | 60 | 10.7% |
| dict keys | 40 | 7.1% |
| bytes | 40 | 7.1% |
| set | 40 | 7.1% |
| other | 40 | 7.1% |


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
| specialization.deferred |      4117496 | 9.8% |
| specialization.deopt |         6349 | 0.0% |
|          hit |     37665264 | 89.4% |
|         miss |       337404 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,939 | 48.4% |
| Failure | 9,544 | 51.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,996 | 20.9% |
| has managed dict | 1,980 | 20.7% |
| not managed dict | 1,708 | 17.9% |
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
|---|---|---|
| specialization.deferred |           48 | 0.0% |
|          hit |     13765572 | 100.0% |
|         miss |         1440 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,240 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       233880 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
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
| specialization.deferred |       252000 | 53.8% |
|          hit |       216000 | 46.1% |

#### Specialization attempts

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
|---|---|---|
| specialization.deferred |       198480 | 2.2% |
| specialization.deopt |         9913 | 0.1% |
|          hit |      8398936 | 92.0% |
|         miss |       526523 | 5.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 10,833 | 91.7% |
| Failure | 980 | 8.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 420 | 42.9% |
| not in dict | 120 | 12.2% |
| property | 120 | 12.2% |
| method | 120 | 12.2% |
| not in keys | 80 | 8.2% |
| not managed dict | 80 | 8.2% |
| overridden | 40 | 4.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         9000 | 1.1% |
|          hit |       829838 | 98.9% |

#### Specialization attempts

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
| Basic | 132,458,800 | 49.3% |
| Not specialized | 32,691,012 | 12.2% |
| Specialized | 103,613,168 | 38.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,402 | 100.0% |
| CALL | 4,713,877 | 0.0% |
| LOAD_ATTR | 4,117,496 | 0.0% |
| TO_BOOL | 931,939 | 0.0% |
| BINARY_OP | 844,914 | 0.0% |
| FOR_ITER | 263,280 | 0.0% |
| BINARY_SUBSCR | 252,067 | 0.0% |
| SEND | 252,000 | 0.0% |
| STORE_ATTR | 198,480 | 0.0% |
| STORE_SUBSCR | 180,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 517,845 | 44.6% |
| LOAD_ATTR_SLOT | 221,414 | 19.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100,596 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 93,702 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,493 | 5.2% |
| CALL_PY_EXACT_ARGS | 45,250 | 3.9% |
| CALL_METHOD_DESCRIPTOR_O | 27,660 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 20,103 | 1.7% |
| TO_BOOL_NONE | 16,355 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 13,314 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,286,505 | 28.0% |
| Calls to Python functions inlined | 11,038,231 | 72.0% |
| Calls via PyEval_EvalFrame (total) | 4,286,505 | 28.0% |
| Calls via PyEval_EvalFrame (vector) | 4,025,445 | 26.3% |
| Calls via PyEval_EvalFrame (generator) | 261,060 | 1.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 4,025,445 | 26.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 814,550 | 5.3% |
| Calls via PyEval_EvalFrame (function ex) | 99,240 | 0.6% |
| Calls via PyEval_EvalFrame (api) | 153,360 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 686,203 | 4.5% |
| Frames pushed | 14,883,916 | 97.1% |
| Frame objects created | 616,634 | 4.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,948,074 | 40.4% |
| Frees to freelist | 8,966,424 |  |
| Allocations | 13,226,006 | 59.6% |
| Allocations to 512 bytes | 12,985,779 | 58.6% |
| Allocations to 4 kbytes | 66,217 | 0.3% |
| Allocations over 4 kbytes | 174,010 | 0.8% |
| Frees | 13,463,077 |  |
| New values | 117,540 |  |
| Interpreter increfs | 132,972,669 | 73.3% |
| Interpreter decrefs | 144,270,619 | 71.3% |
| Increfs | 48,423,887 | 26.7% |
| Decrefs | 58,011,017 | 28.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 18,000 | 15.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,673,497 |  |
| Method cache misses | 281,809 |  |
| Method cache collisions | 303,237 |  |
| Method cache dunder hits | 5,099,702 |  |
| Method cache dunder misses | 22,820 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 922 | 0 | 10,011,872 |
| 1 | 84 | 0 | 2,570,900 |
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
Stats gathered on: 2023-09-27
