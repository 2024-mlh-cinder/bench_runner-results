
# Pystats results

- benchmark: tornado_http
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 52776df
- commit date: 2023-10-17T21:47:13-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 59,324,924 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 20,087,357 | 7.0% | 27.8% | 0.1% |
| RESUME_CHECK | 15,081,841 | 5.3% | 33.0% | 0.0% |
| LOAD_CONST | 12,707,974 | 4.4% | 37.5% |  |
| POP_JUMP_IF_FALSE | 11,432,047 | 4.0% | 41.5% |  |
| STORE_FAST | 9,328,161 | 3.3% | 44.7% |  |
| RETURN_VALUE | 8,674,584 | 3.0% | 47.8% |  |
| CALL_PY_EXACT_ARGS | 8,652,882 | 3.0% | 50.8% | 0.6% |
| LOAD_GLOBAL_MODULE | 8,232,158 | 2.9% | 53.7% | 0.0% |
| LOAD_FAST_LOAD_FAST | 7,760,567 | 2.7% | 56.4% |  |
| POP_TOP | 7,655,268 | 2.7% | 59.0% |  |
| TO_BOOL_BOOL | 7,378,837 | 2.6% | 61.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,743,452 | 2.4% | 64.0% | 0.9% |
| STORE_ATTR_INSTANCE_VALUE | 6,148,029 | 2.1% | 66.1% | 0.1% |
| RETURN_CONST | 5,919,758 | 2.1% | 68.2% |  |
| LOAD_GLOBAL_BUILTIN | 5,543,401 | 1.9% | 70.1% | 0.0% |
| CALL | 4,720,134 | 1.6% | 71.8% |  |
| LOAD_ATTR | 4,547,492 | 1.6% | 73.4% |  |
| INTERPRETER_EXIT | 4,283,922 | 1.5% | 74.9% |  |
| POP_JUMP_IF_NONE | 4,123,657 | 1.4% | 76.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,081,799 | 1.4% | 77.7% | 0.5% |
| POP_JUMP_IF_TRUE | 3,340,551 | 1.2% | 78.9% |  |
| LOAD_ATTR_SLOT | 3,233,042 | 1.1% | 80.0% | 6.9% |
| STORE_ATTR_SLOT | 2,736,702 | 1.0% | 81.0% | 19.0% |
| PUSH_NULL | 2,698,666 | 0.9% | 81.9% |  |
| NOP | 2,657,099 | 0.9% | 82.9% |  |
| COMPARE_OP_INT | 2,654,709 | 0.9% | 83.8% | 0.0% |
| LOAD_ATTR_MODULE | 2,350,954 | 0.8% | 84.6% |  |
| COPY | 1,863,389 | 0.7% | 85.3% |  |
| CALL_ISINSTANCE | 1,668,143 | 0.6% | 85.9% |  |
| LOAD_DEREF | 1,591,009 | 0.6% | 86.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,555,152 | 0.5% | 87.0% | 6.0% |
| JUMP_BACKWARD | 1,379,329 | 0.5% | 87.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,291,715 | 0.5% | 87.9% |  |
| CALL_BUILTIN_FAST | 1,276,080 | 0.4% | 88.3% |  |
| SWAP | 1,092,696 | 0.4% | 88.7% |  |
| TO_BOOL_NONE | 1,091,036 | 0.4% | 89.1% | 1.8% |
| BUILD_TUPLE | 1,079,046 | 0.4% | 89.5% |  |
| TO_BOOL | 1,022,202 | 0.4% | 89.8% |  |
| BUILD_LIST | 935,026 | 0.3% | 90.2% |  |
| BINARY_OP | 898,674 | 0.3% | 90.5% |  |
| STORE_FAST_STORE_FAST | 858,182 | 0.3% | 90.8% |  |
| CALL_LEN | 831,524 | 0.3% | 91.1% |  |
| BINARY_OP_ADD_INT | 812,461 | 0.3% | 91.3% |  |
| CALL_FUNCTION_EX | 808,581 | 0.3% | 91.6% |  |
| FOR_ITER_LIST | 800,647 | 0.3% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 792,516 | 0.3% | 92.2% | 3.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 741,001 | 0.3% | 92.4% |  |
| TO_BOOL_INT | 709,443 | 0.2% | 92.7% | 0.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 677,882 | 0.2% | 92.9% |  |
| BINARY_SUBSCR_DICT | 676,859 | 0.2% | 93.2% |  |
| CONTAINS_OP | 676,320 | 0.2% | 93.4% |  |
| BINARY_OP_SUBTRACT_INT | 645,694 | 0.2% | 93.6% |  |
| JUMP_FORWARD | 622,308 | 0.2% | 93.8% |  |
| BUILD_MAP | 593,580 | 0.2% | 94.1% |  |
| GET_ITER | 589,161 | 0.2% | 94.3% |  |
| COPY_FREE_VARS | 582,457 | 0.2% | 94.5% |  |
| LOAD_ATTR_WITH_HINT | 575,637 | 0.2% | 94.7% | 2.2% |
| LOAD_ATTR_CLASS | 550,200 | 0.2% | 94.9% | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 534,472 | 0.2% | 95.0% |  |
| LIST_EXTEND | 508,160 | 0.2% | 95.2% |  |
| CALL_INTRINSIC_1 | 499,160 | 0.2% | 95.4% |  |
| YIELD_VALUE | 432,000 | 0.2% | 95.5% |  |
| CALL_PY_WITH_DEFAULTS | 426,721 | 0.1% | 95.7% |  |
| IS_OP | 423,720 | 0.1% | 95.8% |  |
| STORE_SUBSCR_DICT | 423,360 | 0.1% | 96.0% |  |
| BINARY_SLICE | 414,660 | 0.1% | 96.1% |  |
| FOR_ITER_RANGE | 370,211 | 0.1% | 96.3% |  |
| BINARY_SUBSCR_GETITEM | 369,180 | 0.1% | 96.4% |  |
| DICT_MERGE | 359,220 | 0.1% | 96.5% |  |
| CALL_KW | 345,481 | 0.1% | 96.6% |  |
| GET_AWAITABLE | 342,000 | 0.1% | 96.8% |  |
| PUSH_EXC_INFO | 339,422 | 0.1% | 96.9% |  |
| POP_EXCEPT | 339,422 | 0.1% | 97.0% |  |
| END_SEND | 333,000 | 0.1% | 97.1% |  |
| CHECK_EXC_MATCH | 332,044 | 0.1% | 97.2% |  |
| BINARY_SUBSCR | 316,013 | 0.1% | 97.3% |  |
| MAKE_CELL | 304,557 | 0.1% | 97.4% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 288,240 | 0.1% | 97.5% | 3.1% |
| MAKE_FUNCTION | 271,906 | 0.1% | 97.6% |  |
| COMPARE_OP_FLOAT | 269,267 | 0.1% | 97.7% |  |
| FOR_ITER | 264,032 | 0.1% | 97.8% |  |
| SEND | 252,400 | 0.1% | 97.9% |  |
| RETURN_GENERATOR | 252,060 | 0.1% | 98.0% |  |
| EXIT_INIT_CHECK | 243,240 | 0.1% | 98.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 243,240 | 0.1% | 98.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 220,618 | 0.1% | 98.3% | 45.7% |
| TO_BOOL_STR | 216,740 | 0.1% | 98.3% | 3.5% |
| SEND_GEN | 216,000 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 207,420 | 0.1% | 98.5% |  |
| FOR_ITER_GEN | 207,000 | 0.1% | 98.5% |  |
| STORE_ATTR | 200,420 | 0.1% | 98.6% |  |
| CALL_LIST_APPEND | 191,850 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 180,580 | 0.1% | 98.7% |  |
| BEFORE_WITH | 174,121 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 171,360 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 171,060 | 0.1% | 98.9% |  |
| STORE_FAST_LOAD_FAST | 162,000 | 0.1% | 99.0% |  |
| SET_FUNCTION_ATTRIBUTE | 157,205 | 0.1% | 99.0% |  |
| DELETE_FAST | 156,061 | 0.1% | 99.1% |  |
| EXTENDED_ARG | 153,180 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 153,180 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 143,820 | 0.1% | 99.3% |  |
| COMPARE_OP | 134,920 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 127,187 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 126,000 | 0.0% | 99.4% |  |
| FOR_ITER_TUPLE | 108,660 | 0.0% | 99.4% |  |
| CALL_BUILTIN_CLASS | 104,031 | 0.0% | 99.5% |  |
| STORE_DEREF | 90,360 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 90,060 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 90,060 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 90,000 | 0.0% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 90,000 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_LIST_INT | 83,470 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 81,120 | 0.0% | 99.7% |  |
| BINARY_OP_ADD_FLOAT_LHS | 73,612 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 72,000 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 63,180 | 0.0% | 99.8% |  |
| CALL_BUILTIN_O | 59,051 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 54,060 | 0.0% | 99.8% |  |
| RERAISE | 54,000 | 0.0% | 99.8% |  |
| BUILD_SLICE | 54,000 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_FLOAT_RHS | 51,303 | 0.0% | 99.8% |  |
| UNARY_INVERT | 45,120 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 45,120 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 45,120 | 0.0% | 99.9% |  |
| END_FOR | 45,000 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 44,879 | 0.0% | 99.9% | 9.5% |
| TO_BOOL_ALWAYS_TRUE | 36,000 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20,239 | 0.0% | 99.9% |  |
| BUILD_STRING | 18,060 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 18,060 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 18,000 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 18,000 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT_NEW | 18,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 9,060 | 0.0% | 100.0% |  |
| UNARY_NOT | 9,000 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BUILD_SET | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT_RHS | 9,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,266 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT_NEW | 895 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,480,643 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 8,592,547 | 3.0% | 9.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,114,671 | 2.8% | 11.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,295,609 | 2.2% | 14.1% |
| STORE_FAST LOAD_FAST | 5,952,445 | 2.1% | 16.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,519,624 | 1.9% | 18.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,608,444 | 1.6% | 19.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,082,740 | 1.4% | 21.2% |
| LOAD_CONST LOAD_FAST | 4,031,469 | 1.4% | 22.6% |
| CACHE RESUME_CHECK | 4,027,564 | 1.4% | 24.0% |
| RETURN_CONST POP_TOP | 3,911,884 | 1.4% | 25.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,751,100 | 1.3% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 3,418,278 | 1.2% | 27.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,374,579 | 1.2% | 29.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,179,488 | 1.1% | 30.2% |
| LOAD_FAST LOAD_ATTR_SLOT | 3,095,928 | 1.1% | 31.3% |
| POP_TOP LOAD_FAST | 2,939,345 | 1.0% | 32.3% |
| LOAD_FAST LOAD_ATTR | 2,821,180 | 1.0% | 33.3% |
| RETURN_VALUE INTERPRETER_EXIT | 2,797,604 | 1.0% | 34.3% |
| LOAD_FAST LOAD_CONST | 2,594,609 | 0.9% | 35.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,594,495 | 0.9% | 36.1% |
| LOAD_FAST RETURN_VALUE | 2,375,130 | 0.8% | 36.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,341,356 | 0.8% | 37.7% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 2,276,241 | 0.8% | 38.5% |
| POP_TOP RETURN_CONST | 2,214,553 | 0.8% | 39.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,134,506 | 0.7% | 40.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,129,394 | 0.7% | 40.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,110,081 | 0.7% | 41.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,105,400 | 0.7% | 42.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,086,908 | 0.7% | 43.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,026,519 | 0.7% | 43.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,996,845 | 0.7% | 44.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,760,213 | 0.6% | 45.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,747,860 | 0.6% | 45.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,733,285 | 0.6% | 46.2% |
| RETURN_VALUE STORE_FAST | 1,599,371 | 0.6% | 46.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,595,197 | 0.6% | 47.3% |
| NOP LOAD_FAST | 1,594,880 | 0.6% | 47.9% |
| LOAD_FAST CALL | 1,531,000 | 0.5% | 48.4% |
| CALL STORE_FAST | 1,530,726 | 0.5% | 49.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,514,823 | 0.5% | 49.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,495,794 | 0.5% | 50.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,471,921 | 0.5% | 50.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,466,160 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,451,346 | 0.5% | 51.5% |
| RETURN_VALUE TO_BOOL_BOOL | 1,422,879 | 0.5% | 52.0% |
| LOAD_FAST STORE_ATTR_SLOT | 1,379,217 | 0.5% | 52.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,356,442 | 0.5% | 53.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,347,676 | 0.5% | 53.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,316,607 | 0.5% | 53.9% |
| PUSH_NULL LOAD_FAST | 1,308,347 | 0.5% | 54.4% |
| LOAD_CONST COMPARE_OP_INT | 1,305,780 | 0.5% | 54.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,279,351 | 0.4% | 55.3% |
| RETURN_CONST INTERPRETER_EXIT | 1,279,258 | 0.4% | 55.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,254,686 | 0.4% | 56.2% |
| RESUME_CHECK NOP | 1,207,541 | 0.4% | 56.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,112,369 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,023,748 | 0.4% | 57.3% |
| LOAD_CONST STORE_FAST | 999,200 | 0.3% | 57.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 977,457 | 0.3% | 58.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 910,818 | 0.3% | 58.4% |
| LOAD_ATTR LOAD_FAST | 901,903 | 0.3% | 58.7% |
| LOAD_CONST LOAD_CONST | 893,962 | 0.3% | 59.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 884,203 | 0.3% | 59.3% |
| LOAD_FAST COPY | 855,275 | 0.3% | 59.6% |
| TO_BOOL POP_JUMP_IF_FALSE | 850,551 | 0.3% | 59.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 839,077 | 0.3% | 60.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 831,755 | 0.3% | 60.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 818,460 | 0.3% | 60.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 797,408 | 0.3% | 61.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 791,757 | 0.3% | 61.3% |
| STORE_ATTR_SLOT LOAD_CONST | 785,558 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 783,260 | 0.3% | 61.9% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 778,748 | 0.3% | 62.1% |
| LOAD_ATTR PUSH_NULL | 772,556 | 0.3% | 62.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 769,827 | 0.3% | 62.7% |
| BUILD_LIST LOAD_FAST | 769,340 | 0.3% | 62.9% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 756,180 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 750,713 | 0.3% | 63.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 748,140 | 0.3% | 63.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 738,260 | 0.3% | 64.0% |
| CALL POP_TOP | 737,976 | 0.3% | 64.2% |
| RETURN_VALUE RETURN_VALUE | 729,180 | 0.3% | 64.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 724,472 | 0.3% | 64.8% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 711,095 | 0.2% | 65.0% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 711,095 | 0.2% | 65.3% |
| POP_TOP JUMP_BACKWARD | 691,772 | 0.2% | 65.5% |
| POP_TOP LOAD_CONST | 686,293 | 0.2% | 65.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 675,360 | 0.2% | 66.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 668,762 | 0.2% | 66.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 667,080 | 0.2% | 66.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 662,960 | 0.2% | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 652,141 | 0.2% | 66.9% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 641,918 | 0.2% | 67.1% |
| LOAD_FAST CALL_BUILTIN_FAST | 628,560 | 0.2% | 67.3% |
| CALL LOAD_FAST | 626,828 | 0.2% | 67.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 620,916 | 0.2% | 67.8% |
| CALL_BUILTIN_FAST STORE_FAST | 611,220 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 607,262 | 0.2% | 68.2% |
| STORE_FAST LOAD_CONST | 598,242 | 0.2% | 68.4% |


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
| RESUME_CHECK | 4,027,564 | 93.8% |
| COPY_FREE_VARS | 175,298 | 4.1% |
| POP_TOP | 72,060 | 1.7% |
| RETURN_GENERATOR | 9,000 | 0.2% |
| MAKE_CELL | 9,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 84,001 | 48.2% |
| RETURN_VALUE | 81,000 | 46.5% |
| LOAD_GLOBAL_MODULE | 9,120 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 174,121 | 100.0% |


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
| LOAD_CONST | 315,373 | 99.8% |
| BINARY_SUBSCR | 640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 198,000 | 62.7% |
| LOAD_FAST | 45,000 | 14.2% |
| CONVERT_VALUE | 18,000 | 5.7% |
| BINARY_SUBSCR_LIST_INT | 9,158 | 2.9% |
| CALL_LEN | 9,060 | 2.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 292,983 | 88.2% |
| BUILD_TUPLE | 18,060 | 5.4% |
| LOAD_ATTR_MODULE | 12,001 | 3.6% |
| LOAD_GLOBAL_MODULE | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 332,044 | 100.0% |


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
| LOAD_FAST | 241,736 | 41.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 108,180 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,274 | 12.3% |
| LOAD_ATTR | 54,000 | 9.2% |
| BINARY_SLICE | 27,180 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 303,378 | 51.5% |
| FOR_ITER | 109,992 | 18.7% |
| FOR_ITER_TUPLE | 54,180 | 9.2% |
| CALL_PY_EXACT_ARGS | 54,000 | 9.2% |
| LOAD_FAST_AND_CLEAR | 36,060 | 6.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,797,604 | 65.3% |
| RETURN_CONST | 1,279,258 | 29.9% |
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
| LOAD_CONST | 271,906 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 118,846 | 43.7% |
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
| RESUME_CHECK | 1,207,541 | 45.4% |
| POP_JUMP_IF_FALSE | 345,618 | 13.0% |
| STORE_FAST | 333,720 | 12.6% |
| STORE_ATTR_INSTANCE_VALUE | 272,179 | 10.2% |
| POP_JUMP_IF_TRUE | 206,307 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,594,880 | 60.0% |
| LOAD_GLOBAL_MODULE | 442,060 | 16.6% |
| LOAD_FAST_LOAD_FAST | 225,000 | 8.5% |
| LOAD_DEREF | 109,799 | 4.1% |
| NOP | 91,622 | 3.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 246,361 | 72.6% |
| SWAP | 45,000 | 13.3% |
| COPY | 27,000 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 9,060 | 2.7% |
| STORE_SUBSCR_DICT | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 217,742 | 64.2% |
| RETURN_VALUE | 45,000 | 13.3% |
| RERAISE | 27,000 | 8.0% |
| DELETE_FAST | 18,000 | 5.3% |
| JUMP_BACKWARD | 12,001 | 3.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,911,884 | 51.1% |
| CALL | 737,976 | 9.6% |
| CALL_METHOD_DESCRIPTOR_O | 620,916 | 8.1% |
| POP_JUMP_IF_FALSE | 459,663 | 6.0% |
| CALL_FUNCTION_EX | 374,900 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,939,345 | 38.4% |
| RETURN_CONST | 2,214,553 | 28.9% |
| JUMP_BACKWARD | 691,772 | 9.0% |
| LOAD_CONST | 686,293 | 9.0% |
| RESUME_CHECK | 252,060 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 261,120 | 76.9% |
| RERAISE | 27,000 | 8.0% |
| CALL | 22,623 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 18,060 | 5.3% |
| RAISE_VARARGS | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300,421 | 88.5% |
| LOAD_GLOBAL_MODULE | 30,001 | 8.8% |
| LOAD_FAST | 9,000 | 2.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,279,351 | 47.4% |
| LOAD_ATTR | 772,556 | 28.6% |
| LOAD_FAST | 349,339 | 12.9% |
| LOAD_DEREF | 153,240 | 5.7% |
| RETURN_VALUE | 99,060 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,308,347 | 48.5% |
| CALL | 547,822 | 20.3% |
| LOAD_FAST_LOAD_FAST | 534,078 | 19.8% |
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
| LOAD_FAST | 2,375,130 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,026,519 | 23.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 466,920 | 5.4% |
| CALL | 464,283 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,797,604 | 32.3% |
| STORE_FAST | 1,599,371 | 18.4% |
| TO_BOOL_BOOL | 1,422,879 | 16.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| LOAD_FAST | 452,212 | 5.2% |


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
| LOAD_ATTR_INSTANCE_VALUE | 452,928 | 44.3% |
| LOAD_FAST | 441,524 | 43.2% |
| LOAD_ATTR | 90,150 | 8.8% |
| COPY | 26,420 | 2.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,100 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 850,551 | 83.2% |
| POP_JUMP_IF_TRUE | 169,205 | 16.6% |
| TO_BOOL | 1,526 | 0.1% |
| TO_BOOL_BOOL | 578 | 0.1% |
| TO_BOOL_NONE | 284 | 0.0% |


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
| LOAD_GLOBAL_MODULE | 171,903 | 19.1% |
| LOAD_CONST | 126,983 | 14.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 117,000 | 13.0% |
| LOAD_FAST | 84,457 | 9.4% |
| LOAD_ATTR_MODULE | 78,482 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 240,662 | 26.8% |
| STORE_FAST | 163,294 | 18.2% |
| COPY | 132,602 | 14.8% |
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
| LOAD_ATTR_SLOT | 284,600 | 30.4% |
| STORE_FAST | 83,812 | 9.0% |
| LOAD_FAST_LOAD_FAST | 80,460 | 8.6% |
| RESUME_CHECK | 54,180 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 769,340 | 82.3% |
| STORE_FAST | 102,266 | 10.9% |
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
| LOAD_FAST | 383,138 | 35.5% |
| LOAD_FAST_LOAD_FAST | 288,240 | 26.7% |
| LOAD_GLOBAL_BUILTIN | 153,300 | 14.2% |
| LOAD_GLOBAL_MODULE | 72,180 | 6.7% |
| LOAD_ATTR_MODULE | 54,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 153,300 | 14.2% |
| CALL_METHOD_DESCRIPTOR_O | 144,000 | 13.3% |
| RETURN_VALUE | 135,360 | 12.5% |
| LOAD_CONST | 118,846 | 11.0% |
| CONTAINS_OP | 90,060 | 8.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,531,000 | 32.4% |
| PUSH_NULL | 547,822 | 11.6% |
| LOAD_CONST | 516,572 | 10.9% |
| LOAD_ATTR_INSTANCE_VALUE | 459,160 | 9.7% |
| LOAD_GLOBAL_MODULE | 441,384 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,530,726 | 32.4% |
| POP_TOP | 737,976 | 15.6% |
| LOAD_FAST | 626,828 | 13.3% |
| RETURN_VALUE | 464,283 | 9.8% |
| BINARY_SUBSCR_DICT | 315,060 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 359,220 | 44.4% |
| CALL_INTRINSIC_1 | 329,840 | 40.8% |
| LOAD_FAST | 75,061 | 9.3% |
| BUILD_MAP | 44,400 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 374,900 | 46.4% |
| RETURN_VALUE | 164,461 | 20.3% |
| RESUME_CHECK | 99,060 | 12.3% |
| STORE_FAST | 89,520 | 11.1% |
| CALL | 62,460 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 490,160 | 98.2% |
| RERAISE | 9,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 329,840 | 66.1% |
| BUILD_MAP | 115,920 | 23.2% |
| LOAD_CONST | 44,400 | 8.9% |
| RERAISE | 9,000 | 1.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 345,481 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 198,180 | 57.4% |
| STORE_FAST | 75,001 | 21.7% |
| COPY_FREE_VARS | 18,000 | 5.2% |
| LOAD_FAST | 9,120 | 2.6% |
| RETURN_VALUE | 9,060 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 88,127 | 65.3% |
| LOAD_ATTR | 18,000 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 6.7% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.7% |
| LOAD_ATTR_CLASS | 9,000 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 89,137 | 66.1% |
| POP_JUMP_IF_TRUE | 45,000 | 33.4% |
| COMPARE_OP | 594 | 0.4% |
| COMPARE_OP_INT | 109 | 0.1% |
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
| STORE_FAST | 9,000 | 1.3% |


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
| LOAD_FAST | 855,275 | 45.9% |
| LOAD_CONST | 189,060 | 10.1% |
| STORE_ATTR_INSTANCE_VALUE | 171,000 | 9.2% |
| BINARY_OP | 132,602 | 7.1% |
| SWAP | 99,180 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 711,095 | 38.2% |
| LOAD_FAST | 342,000 | 18.4% |
| TO_BOOL_BOOL | 243,000 | 13.0% |
| TO_BOOL_INT | 153,581 | 8.2% |
| TO_BOOL_NONE | 143,993 | 7.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 216,296 | 37.1% |
| CACHE | 175,298 | 30.1% |
| CALL | 90,120 | 15.5% |
| LOAD_ATTR_PROPERTY | 63,000 | 10.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,503 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 546,337 | 93.8% |
| RETURN_GENERATOR | 18,060 | 3.1% |
| MAKE_CELL | 18,060 | 3.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 81,000 | 51.9% |
| STORE_ATTR_INSTANCE_VALUE | 18,000 | 11.5% |
| POP_EXCEPT | 18,000 | 11.5% |
| NOP | 18,000 | 11.5% |
| POP_TOP | 12,001 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 81,000 | 51.9% |
| RETURN_CONST | 36,000 | 23.1% |
| LOAD_FAST | 21,001 | 13.5% |
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
| STORE_ATTR_INSTANCE_VALUE | 9,000 | 5.9% |
| COMPARE_OP_STR | 9,000 | 5.9% |
| JUMP_BACKWARD | 60 | 0.0% |

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
| GET_ITER | 109,992 | 41.7% |
| SWAP | 18,000 | 6.8% |
| LOAD_FAST | 18,000 | 6.8% |
| FOR_ITER | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 100,872 | 38.2% |
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
| STORE_FAST | 9,000 | 2.1% |
| POP_JUMP_IF_TRUE | 9,000 | 2.1% |
| COPY | 9,000 | 2.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 691,772 | 50.2% |
| POP_JUMP_IF_TRUE | 228,661 | 16.6% |
| FOR_ITER_LIST | 81,060 | 5.9% |
| CALL_LIST_APPEND | 74,790 | 5.4% |
| POP_JUMP_IF_FALSE | 72,166 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 488,149 | 35.4% |
| FOR_ITER_RANGE | 347,660 | 25.2% |
| FOR_ITER_GEN | 162,000 | 11.7% |
| LOAD_FAST | 135,808 | 9.8% |
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
| STORE_FAST | 334,232 | 53.7% |
| POP_TOP | 99,060 | 15.9% |
| POP_JUMP_IF_TRUE | 81,000 | 13.0% |
| STORE_ATTR_INSTANCE_VALUE | 36,334 | 5.8% |
| STORE_ATTR | 18,000 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 422,270 | 67.9% |
| LOAD_CONST | 69,282 | 11.1% |
| LOAD_FAST_LOAD_FAST | 45,000 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 31,496 | 5.1% |
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
| LOAD_ATTR_SLOT | 284,600 | 56.0% |
| LOAD_FAST | 196,440 | 38.7% |
| LOAD_CONST | 18,000 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 1.8% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 490,160 | 96.5% |
| LOAD_FAST | 18,000 | 3.5% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,821,180 | 62.0% |
| LOAD_ATTR_INSTANCE_VALUE | 652,141 | 14.3% |
| LOAD_ATTR_SLOT | 284,600 | 6.3% |
| LOAD_ATTR_WITH_HINT | 252,000 | 5.5% |
| LOAD_GLOBAL_MODULE | 225,718 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 901,903 | 19.8% |
| PUSH_NULL | 772,556 | 17.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 756,180 | 16.6% |
| LOAD_CONST | 360,075 | 7.9% |
| CALL_PY_EXACT_ARGS | 241,949 | 5.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,594,609 | 20.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,254,686 | 9.9% |
| LOAD_CONST | 893,962 | 7.0% |
| POP_JUMP_IF_FALSE | 839,077 | 6.6% |
| STORE_ATTR_SLOT | 785,558 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,031,469 | 31.7% |
| COMPARE_OP_INT | 1,305,780 | 10.3% |
| STORE_FAST | 999,200 | 7.9% |
| LOAD_CONST | 893,962 | 7.0% |
| CALL | 516,572 | 4.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 299,239 | 18.8% |
| RESUME_CHECK | 155,539 | 9.8% |
| POP_JUMP_IF_FALSE | 128,299 | 8.1% |
| NOP | 109,799 | 6.9% |
| POP_JUMP_IF_TRUE | 108,240 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 377,820 | 23.7% |
| LOAD_ATTR_INSTANCE_VALUE | 276,537 | 17.4% |
| PUSH_NULL | 153,240 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 117,000 | 7.4% |
| LOAD_ATTR | 112,578 | 7.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,592,547 | 14.5% |
| POP_JUMP_IF_FALSE | 6,295,609 | 10.6% |
| STORE_FAST | 5,952,445 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 4,082,740 | 6.9% |
| LOAD_CONST | 4,031,469 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,480,643 | 29.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,608,444 | 7.8% |
| STORE_ATTR_INSTANCE_VALUE | 3,751,100 | 6.3% |
| LOAD_ATTR_SLOT | 3,095,928 | 5.2% |
| LOAD_ATTR | 2,821,180 | 4.8% |


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
| STORE_FAST | 9,000 | 12.5% |
| POP_JUMP_IF_FALSE | 9,000 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 54,000 | 75.0% |
| LOAD_CONST | 9,000 | 12.5% |
| LOAD_ATTR | 9,000 | 12.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 977,457 | 12.6% |
| LOAD_GLOBAL_MODULE | 818,460 | 10.5% |
| STORE_FAST | 797,408 | 10.3% |
| STORE_ATTR_INSTANCE_VALUE | 748,140 | 9.6% |
| POP_JUMP_IF_FALSE | 675,360 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,495,794 | 19.3% |
| STORE_ATTR_SLOT | 1,347,676 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,023,748 | 13.2% |
| LOAD_FAST | 662,960 | 8.5% |
| LOAD_FAST_LOAD_FAST | 550,639 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 340 | 15.0% |
| POP_JUMP_IF_FALSE | 293 | 12.9% |
| STORE_FAST | 260 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 180 | 7.9% |
| LOAD_FAST | 133 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,636 | 72.2% |
| LOAD_GLOBAL_BUILTIN | 580 | 25.6% |
| LOAD_ATTR | 35 | 1.5% |
| COMPARE_OP | 15 | 0.7% |


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
| MAKE_CELL | 139,898 | 45.9% |
| CALL_PY_EXACT_ARGS | 119,479 | 39.2% |
| COPY_FREE_VARS | 18,060 | 5.9% |
| CALL_KW | 9,000 | 3.0% |
| CALL | 9,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 155,659 | 51.1% |
| MAKE_CELL | 139,898 | 45.9% |
| RETURN_GENERATOR | 9,000 | 3.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,519,624 | 48.3% |
| COMPARE_OP_INT | 2,105,400 | 18.4% |
| TO_BOOL_NONE | 910,818 | 8.0% |
| TO_BOOL | 850,551 | 7.4% |
| TO_BOOL_INT | 451,083 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,295,609 | 55.1% |
| RETURN_CONST | 1,112,369 | 9.7% |
| LOAD_CONST | 839,077 | 7.3% |
| LOAD_GLOBAL_MODULE | 791,757 | 6.9% |
| LOAD_FAST_LOAD_FAST | 675,360 | 5.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,276,241 | 55.2% |
| LOAD_FAST | 1,595,197 | 38.7% |
| LOAD_DEREF | 99,060 | 2.4% |
| LOAD_ATTR | 99,060 | 2.4% |
| LOAD_ATTR_WITH_HINT | 26,799 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,418,278 | 82.9% |
| RETURN_CONST | 209,539 | 5.1% |
| LOAD_GLOBAL_MODULE | 207,140 | 5.0% |
| LOAD_FAST_LOAD_FAST | 108,240 | 2.6% |
| NOP | 99,060 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 831,755 | 64.4% |
| LOAD_ATTR_INSTANCE_VALUE | 342,000 | 26.5% |
| LOAD_ATTR | 81,360 | 6.3% |
| LOAD_GLOBAL_MODULE | 9,300 | 0.7% |
| RETURN_VALUE | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 482,348 | 37.3% |
| LOAD_FAST_LOAD_FAST | 326,299 | 25.3% |
| LOAD_GLOBAL_MODULE | 257,868 | 20.0% |
| LOAD_CONST | 99,000 | 7.7% |
| LOAD_DEREF | 63,120 | 4.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,760,213 | 52.7% |
| COMPARE_OP_INT | 531,300 | 15.9% |
| TO_BOOL_INT | 258,269 | 7.7% |
| TO_BOOL_STR | 180,360 | 5.4% |
| TO_BOOL_NONE | 179,844 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,466,160 | 43.9% |
| LOAD_GLOBAL_BUILTIN | 369,120 | 11.0% |
| JUMP_BACKWARD | 228,661 | 6.8% |
| LOAD_CONST | 217,362 | 6.5% |
| NOP | 206,307 | 6.2% |


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
| POP_TOP | 2,214,553 | 37.4% |
| POP_JUMP_IF_FALSE | 1,112,369 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 569,380 | 9.6% |
| STORE_ATTR_SLOT | 459,739 | 7.8% |
| STORE_FAST | 296,412 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,911,884 | 66.1% |
| INTERPRETER_EXIT | 1,279,258 | 21.6% |
| EXIT_INIT_CHECK | 243,240 | 4.1% |
| STORE_FAST | 132,008 | 2.2% |
| TO_BOOL_BOOL | 99,009 | 1.7% |


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
| MAKE_FUNCTION | 118,846 | 75.6% |
| SET_FUNCTION_ATTRIBUTE | 38,359 | 24.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,367 | 33.9% |
| SET_FUNCTION_ATTRIBUTE | 38,359 | 24.4% |
| CALL | 29,399 | 18.7% |
| LOAD_FAST | 18,000 | 11.5% |
| CALL_PY_EXACT_ARGS | 9,080 | 5.8% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 126,800 | 63.3% |
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
| RETURN_VALUE | 1,599,371 | 17.1% |
| CALL | 1,530,726 | 16.4% |
| LOAD_CONST | 999,200 | 10.7% |
| CALL_BUILTIN_FAST | 611,220 | 6.6% |
| LOAD_ATTR_INSTANCE_VALUE | 572,813 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,952,445 | 63.8% |
| LOAD_FAST_LOAD_FAST | 797,408 | 8.5% |
| LOAD_CONST | 598,242 | 6.4% |
| LOAD_GLOBAL_BUILTIN | 398,110 | 4.3% |
| JUMP_FORWARD | 334,232 | 3.6% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 668,762 | 77.9% |
| UNPACK_SEQUENCE_LIST | 90,000 | 10.5% |
| UNPACK_SEQUENCE_TUPLE | 54,180 | 6.3% |
| STORE_FAST_STORE_FAST | 18,120 | 2.1% |
| COPY | 18,060 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 470,642 | 54.8% |
| LOAD_FAST_LOAD_FAST | 126,120 | 14.7% |
| LOAD_GLOBAL_MODULE | 99,000 | 11.5% |
| STORE_FAST | 72,180 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 63,000 | 7.3% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 425,401 | 38.9% |
| BINARY_OP_SUBTRACT_INT | 267,694 | 24.5% |
| LOAD_FAST | 144,000 | 13.2% |
| LOAD_ATTR | 66,301 | 6.1% |
| LOAD_FAST_AND_CLEAR | 36,060 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 711,095 | 65.1% |
| COPY | 99,180 | 9.1% |
| STORE_FAST | 93,301 | 8.5% |
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

### BINARY_OP_ADD_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,800 | 84.0% |
| LOAD_ATTR_INSTANCE_VALUE | 11,812 | 16.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,400 | 72.5% |
| STORE_FAST | 11,812 | 16.0% |
| LOAD_GLOBAL_MODULE | 8,400 | 11.4% |


</details>

### BINARY_OP_ADD_FLOAT_NEW

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT_NEW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,000 | 50.0% |
| LOAD_ATTR | 9,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,000 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 507,001 | 62.4% |
| LOAD_FAST_LOAD_FAST | 198,000 | 24.4% |
| CALL_LEN | 63,000 | 7.8% |
| LOAD_CONST | 44,440 | 5.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 425,401 | 52.4% |
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

### BINARY_OP_MULTIPLY_FLOAT_NEW

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT_NEW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 877 | 98.0% |
| BINARY_OP | 18 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 877 | 98.0% |
| CALL | 18 | 2.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT_RHS

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT_RHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,000 | 100.0% |


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

### BINARY_OP_SUBTRACT_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 9,000 | 49.8% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 49.8% |
| LOAD_FAST | 40 | 0.2% |
| BINARY_OP | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,000 | 49.8% |
| LOAD_FAST | 9,000 | 49.8% |
| LOAD_DEREF | 60 | 0.3% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_RHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_RHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,277 | 88.3% |
| CALL | 6,008 | 11.7% |
| BINARY_OP | 18 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 44,400 | 86.5% |
| STORE_FAST | 6,903 | 13.5% |


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
| LOAD_CONST | 42,694 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 267,694 | 41.5% |
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
| CALL | 315,060 | 46.5% |
| LOAD_FAST | 262,679 | 38.8% |
| BUILD_TUPLE | 36,060 | 5.3% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| RETURN_VALUE | 18,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,000 | 47.9% |
| PUSH_EXC_INFO | 261,120 | 38.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 28,619 | 4.2% |
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
| LOAD_CONST | 65,312 | 78.2% |
| BINARY_SUBSCR | 9,158 | 11.0% |
| BINARY_OP_SUBTRACT_INT | 9,000 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 33,859 | 40.6% |
| LOAD_FAST | 18,060 | 21.6% |
| STORE_FAST | 11,614 | 13.9% |
| TO_BOOL_BOOL | 10,619 | 12.7% |
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
| STORE_FAST | 9,060 | 5.3% |


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
| LOAD_CONST | 81,000 | 36.7% |
| LOAD_FAST | 64,977 | 29.5% |
| LOAD_FAST_LOAD_FAST | 35,948 | 16.3% |
| CALL_BUILTIN_CLASS | 18,000 | 8.2% |
| BINARY_SLICE | 18,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 118,203 | 53.6% |
| POP_TOP | 81,000 | 36.7% |
| COPY_FREE_VARS | 19,503 | 8.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,580 | 0.7% |
| CALL_PY_EXACT_ARGS | 332 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,972 | 28.8% |
| LOAD_ATTR_INSTANCE_VALUE | 27,120 | 26.1% |
| LOAD_GLOBAL_MODULE | 10,659 | 10.2% |
| LOAD_GLOBAL_BUILTIN | 9,080 | 8.7% |
| RETURN_GENERATOR | 9,000 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,000 | 26.0% |
| GET_ITER | 22,491 | 21.6% |
| LOAD_FAST | 18,120 | 17.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 18,000 | 17.3% |
| LOAD_DEREF | 9,000 | 8.7% |


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
| LOAD_ATTR_WITH_HINT | 9,000 | 0.7% |

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
| LOAD_ATTR | 11,179 | 55.2% |
| LOAD_FAST | 9,060 | 44.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,179 | 55.2% |
| STORE_FAST | 9,060 | 44.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,314 | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE | 21,702 | 36.8% |
| BINARY_OP_MULTIPLY_FLOAT_NEW | 877 | 1.5% |
| CALL | 78 | 0.1% |
| LOAD_CONST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,702 | 52.0% |
| STORE_SUBSCR_DICT | 18,000 | 30.5% |
| BINARY_SUBSCR_DICT | 9,000 | 15.2% |
| LOAD_CONST | 895 | 1.5% |
| POP_TOP | 394 | 0.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 884,203 | 53.0% |
| LOAD_GLOBAL_BUILTIN | 361,020 | 21.6% |
| LOAD_ATTR_MODULE | 224,400 | 13.5% |
| BUILD_TUPLE | 153,300 | 9.2% |
| LOAD_ATTR | 45,080 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,514,823 | 90.8% |
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
| LOAD_FAST | 504,360 | 60.7% |
| LOAD_ATTR_INSTANCE_VALUE | 308,984 | 37.2% |
| BINARY_SUBSCR | 9,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 9,000 | 1.1% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 290,692 | 35.0% |
| LOAD_FAST | 169,740 | 20.4% |
| LOAD_CONST | 72,240 | 8.7% |
| BINARY_OP_ADD_INT | 63,000 | 7.6% |
| BINARY_OP_SUBTRACT_INT | 45,000 | 5.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,389 | 60.7% |
| BUILD_TUPLE | 57,301 | 29.9% |
| RETURN_VALUE | 18,120 | 9.4% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 90,000 | 46.9% |
| JUMP_BACKWARD | 74,790 | 39.0% |
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
| LOAD_ATTR_METHOD_NO_DICT | 153,000 | 20.6% |
| LOAD_FAST_LOAD_FAST | 54,120 | 7.3% |
| LOAD_FAST | 39,281 | 5.3% |
| RETURN_VALUE | 18,060 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 466,920 | 63.0% |
| STORE_FAST | 93,421 | 12.6% |
| CALL_PY_EXACT_ARGS | 81,080 | 10.9% |
| LOAD_CONST | 54,000 | 7.3% |
| TO_BOOL_BOOL | 18,000 | 2.4% |


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
| LOAD_FAST_LOAD_FAST | 11,812 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,292 | 37.7% |
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
| LOAD_ATTR_METHOD_NO_DICT | 769,827 | 49.5% |
| LOAD_ATTR | 756,180 | 48.6% |
| LOAD_FAST | 18,060 | 1.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,000 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,785 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 738,260 | 47.5% |
| STORE_FAST | 365,600 | 23.5% |
| POP_TOP | 177,068 | 11.4% |
| GET_ITER | 108,180 | 7.0% |
| LOAD_FAST | 54,180 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 431,856 | 54.5% |
| BUILD_TUPLE | 144,000 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 7.9% |
| LOAD_FAST_CHECK | 54,000 | 6.8% |
| LOAD_CONST | 36,040 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 620,916 | 78.3% |
| STORE_FAST | 107,940 | 13.6% |
| PUSH_EXC_INFO | 18,060 | 2.3% |
| UNPACK_SEQUENCE_TUPLE | 18,000 | 2.3% |
| LOAD_CONST | 18,000 | 2.3% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,374,579 | 39.0% |
| LOAD_FAST | 2,594,495 | 30.0% |
| LOAD_FAST_LOAD_FAST | 496,251 | 5.7% |
| LOAD_CONST | 495,160 | 5.7% |
| LOAD_ATTR_METHOD_NO_DICT | 384,719 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,114,671 | 93.8% |
| COPY_FREE_VARS | 216,296 | 2.5% |
| RETURN_GENERATOR | 198,000 | 2.3% |
| MAKE_CELL | 119,479 | 1.4% |
| TO_BOOL_BOOL | 3,519 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,000 | 25.3% |
| LOAD_FAST | 99,200 | 23.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 93,001 | 21.8% |
| PUSH_NULL | 54,260 | 12.7% |
| LOAD_ATTR | 27,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 417,661 | 97.9% |
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
| LOAD_ATTR_SLOT | 251,284 | 93.3% |
| LOAD_FAST | 11,554 | 4.3% |
| LOAD_GLOBAL_MODULE | 6,429 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 251,284 | 93.3% |
| POP_JUMP_IF_FALSE | 17,983 | 6.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,305,780 | 49.2% |
| LOAD_ATTR_INSTANCE_VALUE | 778,748 | 29.3% |
| LOAD_ATTR_CLASS | 288,000 | 10.8% |
| COPY | 99,180 | 3.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 90,000 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,105,400 | 79.3% |
| POP_JUMP_IF_TRUE | 531,300 | 20.0% |
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
| JUMP_BACKWARD | 488,149 | 61.0% |
| GET_ITER | 303,378 | 37.9% |
| SWAP | 9,000 | 1.1% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 436,727 | 54.5% |
| LOAD_FAST | 146,932 | 18.4% |
| JUMP_BACKWARD | 81,060 | 10.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 69,482 | 8.7% |
| RETURN_CONST | 20,992 | 2.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 347,660 | 93.9% |
| GET_ITER | 22,491 | 6.1% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 340,339 | 91.9% |
| LOAD_CONST | 11,812 | 3.2% |
| STORE_FAST_LOAD_FAST | 9,000 | 2.4% |
| RETURN_CONST | 9,000 | 2.4% |
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
| SWAP | 9,000 | 8.3% |
| LOAD_CONST | 9,000 | 8.3% |
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
| LOAD_FAST | 17,480,643 | 87.0% |
| LOAD_FAST_LOAD_FAST | 1,023,748 | 5.1% |
| COPY | 711,095 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 594,120 | 3.0% |
| LOAD_DEREF | 276,537 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,179,488 | 15.8% |
| POP_JUMP_IF_NONE | 2,276,241 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,086,908 | 10.4% |
| RETURN_VALUE | 2,026,519 | 10.1% |
| TO_BOOL_BOOL | 1,996,845 | 9.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 2,086,908 | 51.1% |
| LOAD_FAST | 1,316,607 | 32.3% |
| BINARY_SLICE | 189,040 | 4.6% |
| LOAD_CONST | 99,040 | 2.4% |
| BINARY_SUBSCR_STR_INT | 81,080 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,451,346 | 35.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 769,827 | 18.9% |
| LOAD_CONST | 724,472 | 17.7% |
| CALL_PY_EXACT_ARGS | 384,719 | 9.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 171,000 | 4.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,608,444 | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,356,442 | 20.1% |
| LOAD_ATTR_SLOT | 441,679 | 6.5% |
| LOAD_DEREF | 92,479 | 1.4% |
| LOAD_FAST_LOAD_FAST | 80,460 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,374,579 | 50.0% |
| LOAD_FAST | 2,134,506 | 31.7% |
| LOAD_FAST_LOAD_FAST | 506,419 | 7.5% |
| LOAD_CONST | 369,060 | 5.5% |
| LOAD_GLOBAL_MODULE | 118,639 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,341,356 | 99.6% |
| LOAD_ATTR_MODULE | 9,000 | 0.4% |
| LOAD_ATTR | 598 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,279,351 | 54.4% |
| LOAD_ATTR_CLASS | 342,000 | 14.5% |
| CALL_ISINSTANCE | 224,400 | 9.5% |
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
| LOAD_FAST | 3,095,928 | 95.8% |
| BINARY_SUBSCR_TUPLE_INT | 90,060 | 2.8% |
| BINARY_SUBSCR_LIST_INT | 33,859 | 1.0% |
| LOAD_DEREF | 9,000 | 0.3% |
| LOAD_ATTR_SLOT | 4,177 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 641,918 | 19.9% |
| TO_BOOL_BOOL | 578,331 | 17.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 441,679 | 13.7% |
| LOAD_ATTR | 284,600 | 8.8% |
| LIST_EXTEND | 284,600 | 8.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,376 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 261 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,000 | 43.8% |
| LOAD_CONST | 72,000 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,799 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 45,000 | 7.8% |
| RETURN_VALUE | 27,000 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,129,394 | 38.4% |
| LOAD_FAST | 667,080 | 12.0% |
| POP_JUMP_IF_FALSE | 513,580 | 9.3% |
| STORE_FAST | 398,110 | 7.2% |
| POP_JUMP_IF_TRUE | 369,120 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,082,740 | 73.7% |
| CALL_ISINSTANCE | 361,020 | 6.5% |
| LOAD_DEREF | 299,239 | 5.4% |
| CHECK_EXC_MATCH | 292,983 | 5.3% |
| BUILD_TUPLE | 153,300 | 2.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,733,285 | 21.1% |
| RESUME_CHECK | 1,471,921 | 17.9% |
| POP_JUMP_IF_FALSE | 791,757 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 783,260 | 9.5% |
| STORE_ATTR_INSTANCE_VALUE | 607,262 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,341,356 | 28.4% |
| LOAD_FAST | 1,747,860 | 21.2% |
| CALL_ISINSTANCE | 884,203 | 10.7% |
| LOAD_FAST_LOAD_FAST | 818,460 | 9.9% |
| CALL | 441,384 | 5.4% |


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
| CALL_PY_EXACT_ARGS | 8,114,671 | 53.8% |
| CACHE | 4,027,564 | 26.7% |
| COPY_FREE_VARS | 546,337 | 3.6% |
| CALL_PY_WITH_DEFAULTS | 417,661 | 2.8% |
| BINARY_SUBSCR_GETITEM | 369,180 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,592,547 | 57.0% |
| LOAD_GLOBAL_BUILTIN | 2,129,394 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,471,921 | 9.8% |
| NOP | 1,207,541 | 8.0% |
| LOAD_CONST | 488,779 | 3.2% |


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
| LOAD_FAST | 3,751,100 | 61.0% |
| LOAD_FAST_LOAD_FAST | 1,495,794 | 24.3% |
| SWAP | 711,095 | 11.6% |
| LOAD_DEREF | 117,000 | 1.9% |
| STORE_FAST_LOAD_FAST | 63,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,110,081 | 34.3% |
| LOAD_CONST | 1,254,686 | 20.4% |
| LOAD_FAST_LOAD_FAST | 748,140 | 12.2% |
| LOAD_GLOBAL_MODULE | 607,262 | 9.9% |
| RETURN_CONST | 569,380 | 9.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,379,217 | 50.4% |
| LOAD_FAST_LOAD_FAST | 1,347,676 | 49.2% |
| STORE_ATTR_SLOT | 9,809 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 977,457 | 35.7% |
| LOAD_CONST | 785,558 | 28.7% |
| LOAD_FAST | 481,441 | 17.6% |
| RETURN_CONST | 459,739 | 16.8% |
| JUMP_BACKWARD | 22,698 | 0.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,792 | 79.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 20.1% |
| STORE_ATTR_INSTANCE_VALUE | 87 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,000 | 80.2% |
| RETURN_CONST | 8,799 | 19.6% |
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
| LOAD_FAST | 27,000 | 75.0% |
| CALL | 9,000 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 18,000 | 50.0% |
| POP_JUMP_IF_FALSE | 18,000 | 50.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,996,845 | 27.1% |
| CALL_ISINSTANCE | 1,514,823 | 20.5% |
| RETURN_VALUE | 1,422,879 | 19.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 738,260 | 10.0% |
| LOAD_ATTR_SLOT | 578,331 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,519,624 | 74.8% |
| POP_JUMP_IF_TRUE | 1,760,213 | 23.9% |
| EXTENDED_ARG | 90,000 | 1.2% |
| UNARY_NOT | 9,000 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,120 | 43.1% |
| BINARY_OP | 240,662 | 33.9% |
| COPY | 153,581 | 21.6% |
| LOAD_ATTR | 9,000 | 1.3% |
| TO_BOOL_NONE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 451,083 | 63.6% |
| POP_JUMP_IF_TRUE | 258,269 | 36.4% |
| TO_BOOL_NONE | 91 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 127,049 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| TO_BOOL | 18 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 127,187 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 641,918 | 58.8% |
| COPY | 143,993 | 13.2% |
| LOAD_FAST | 142,350 | 13.0% |
| LOAD_ATTR | 63,000 | 5.8% |
| LOAD_ATTR_INSTANCE_VALUE | 54,120 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 910,818 | 83.5% |
| POP_JUMP_IF_TRUE | 179,844 | 16.5% |
| TO_BOOL | 154 | 0.0% |
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
| BINARY_SUBSCR | 198,000 | 29.2% |
| RETURN_VALUE | 117,240 | 17.3% |
| FOR_ITER | 81,040 | 12.0% |
| YIELD_VALUE | 81,000 | 11.9% |
| FOR_ITER_LIST | 69,482 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 668,762 | 98.7% |
| LOAD_FAST | 9,060 | 1.3% |
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
| specialization.deferred |       315075 | 18.6% |
|          hit |      1381989 | 81.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 298 | 31.8% |
| Failure | 640 | 68.2% |

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
| specialization.deferred |      1019756 | 9.6% |
| specialization.deopt |          605 | 0.0% |
|          hit |      9528003 | 90.0% |
|         miss |        31240 | 0.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,371 | 44.9% |
| Failure | 1,680 | 55.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 569 | 33.9% |
| sequence | 398 | 23.7% |
| float | 240 | 14.3% |
| dict | 160 | 9.5% |
| mapping | 113 | 6.7% |
| tuple | 80 | 4.8% |
| bytearray | 80 | 4.8% |
| set | 40 | 2.4% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       896763 | 33.1% |
|          hit |      1809145 | 66.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 116 | 6.1% |
| Failure | 1,795 | 93.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 765 | 42.6% |
| add other | 280 | 15.6% |
| or | 273 | 15.2% |
| remainder | 200 | 11.1% |
| add different types | 120 | 6.7% |
| multiply different types | 77 | 4.3% |
| true divide other | 40 | 2.2% |
| floor divide | 40 | 2.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4709914 | 21.1% |
| specialization.deopt |         5154 | 0.0% |
|          hit |     17337206 | 77.7% |
|         miss |       269999 | 1.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,286 | 47.4% |
| Failure | 8,088 | 52.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,570 | 19.4% |
| class no vectorcall | 1,360 | 16.8% |
| cfunc noargs | 1,047 | 12.9% |
| meth descr method fastcall keywords | 920 | 11.4% |
| meth descr varargs | 811 | 10.0% |
| cfunc varargs keywords | 560 | 6.9% |
| class mutable | 420 | 5.2% |
| other | 380 | 4.7% |
| meth descr varargs keywords | 320 | 4.0% |
| init not simple | 180 | 2.2% |
| no dict | 180 | 2.2% |
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
|---|---|---|
| specialization.deferred |       134137 | 4.1% |
| specialization.deopt |            9 | 0.0% |
|          hit |      3130426 | 95.8% |
|         miss |          970 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 189 | 23.9% |
| Failure | 603 | 76.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 203 | 33.7% |
| different types | 120 | 19.9% |
| other | 100 | 16.6% |
| bytes | 80 | 13.3% |
| tuple | 40 | 6.6% |
| big int | 40 | 6.6% |
| bool | 20 | 3.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       263472 | 15.1% |
|          hit |      1486518 | 84.9% |

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
| specialization.deferred |      4535237 | 10.7% |
| specialization.deopt |         6414 | 0.0% |
|          hit |     37680323 | 88.5% |
|         miss |       338358 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,102 | 48.8% |
| Failure | 9,567 | 51.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 2,010 | 21.0% |
| has managed dict | 1,980 | 20.7% |
| not managed dict | 1,719 | 18.0% |
| not in keys | 1,680 | 17.6% |
| shadowed | 478 | 5.0% |
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
| specialization.deferred |           50 | 0.0% |
|          hit |     13774719 | 100.0% |
|         miss |          840 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,216 | 100.0% |
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
| specialization.deopt |         9976 | 0.1% |
|          hit |      8401110 | 92.0% |
|         miss |       528500 | 5.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 10,936 | 91.8% |
| Failure | 980 | 8.2% |

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
|          hit |       831062 | 98.9% |

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
| Basic | 139,223,717 | 48.7% |
| Not specialized | 35,701,128 | 12.5% |
| Specialized | 111,178,328 | 38.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,451 | 100.0% |
| CALL | 4,709,914 | 0.0% |
| LOAD_ATTR | 4,535,237 | 0.0% |
| TO_BOOL | 1,019,756 | 0.0% |
| BINARY_OP | 896,763 | 0.0% |
| BINARY_SUBSCR | 315,075 | 0.0% |
| FOR_ITER | 263,472 | 0.0% |
| SEND | 252,000 | 0.0% |
| STORE_ATTR | 198,480 | 0.0% |
| STORE_SUBSCR | 180,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 519,802 | 44.4% |
| LOAD_ATTR_SLOT | 221,708 | 18.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100,750 | 8.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 93,884 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,648 | 5.2% |
| CALL_PY_EXACT_ARGS | 47,705 | 4.1% |
| CALL_METHOD_DESCRIPTOR_O | 27,660 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 20,548 | 1.8% |
| TO_BOOL_NONE | 19,300 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 13,359 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,292,922 | 28.0% |
| Calls to Python functions inlined | 11,040,979 | 72.0% |
| Calls via PyEval_EvalFrame (total) | 4,292,922 | 28.0% |
| Calls via PyEval_EvalFrame (vector) | 4,031,862 | 26.3% |
| Calls via PyEval_EvalFrame (generator) | 261,060 | 1.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 4,031,862 | 26.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 818,404 | 5.3% |
| Calls via PyEval_EvalFrame (function ex) | 99,240 | 0.6% |
| Calls via PyEval_EvalFrame (api) | 153,360 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 686,539 | 4.5% |
| Frames pushed | 14,893,081 | 97.1% |
| Frame objects created | 617,160 | 4.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,957,029 | 40.4% |
| Frees to freelist | 8,976,640 |  |
| Allocations | 13,225,252 | 59.6% |
| Allocations to 512 bytes | 12,984,692 | 58.5% |
| Allocations to 4 kbytes | 66,186 | 0.3% |
| Allocations over 4 kbytes | 174,374 | 0.8% |
| Frees | 13,468,623 |  |
| New values | 117,540 |  |
| Interpreter increfs | 139,616,567 | 77.4% |
| Interpreter decrefs | 150,728,761 | 74.8% |
| Increfs | 40,867,665 | 22.6% |
| Decrefs | 50,647,979 | 25.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 18,000 | 15.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,697,442 |  |
| Method cache misses | 263,130 |  |
| Method cache collisions | 275,619 |  |
| Method cache dunder hits | 5,113,877 |  |
| Method cache dunder misses | 13,972 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 884 | 0 | 9,600,712 |
| 1 | 81 | 0 | 2,496,114 |
| 2 | 3 | 99 | 935,374 |


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
