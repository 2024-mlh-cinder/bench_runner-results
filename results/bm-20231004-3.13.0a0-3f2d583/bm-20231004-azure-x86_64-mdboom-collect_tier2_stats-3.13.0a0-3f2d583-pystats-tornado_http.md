
# Pystats results

- benchmark: tornado_http
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 55,496,052 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,853,787 | 7.0% | 27.8% | 0.1% |
| RESUME_CHECK | 14,702,465 | 5.5% | 33.3% | 0.0% |
| LOAD_CONST | 11,951,014 | 4.5% | 37.7% |  |
| POP_JUMP_IF_FALSE | 10,416,804 | 3.9% | 41.6% |  |
| RETURN_VALUE | 8,662,666 | 3.2% | 44.8% |  |
| CALL_PY_EXACT_ARGS | 8,149,122 | 3.0% | 47.9% | 0.6% |
| STORE_FAST | 8,076,718 | 3.0% | 50.9% |  |
| LOAD_GLOBAL_MODULE | 7,912,235 | 3.0% | 53.8% | 0.0% |
| LOAD_FAST_LOAD_FAST | 7,691,933 | 2.9% | 56.7% |  |
| POP_TOP | 7,586,852 | 2.8% | 59.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,563,679 | 2.5% | 62.0% | 0.9% |
| TO_BOOL_BOOL | 6,540,656 | 2.4% | 64.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 6,087,444 | 2.3% | 66.7% | 0.1% |
| RETURN_CONST | 5,922,392 | 2.2% | 68.9% |  |
| LOAD_GLOBAL_BUILTIN | 5,196,138 | 1.9% | 70.9% | 0.0% |
| CALL | 4,723,874 | 1.8% | 72.6% |  |
| INTERPRETER_EXIT | 4,282,076 | 1.6% | 74.2% |  |
| LOAD_ATTR | 4,134,891 | 1.5% | 75.8% |  |
| POP_JUMP_IF_NONE | 4,056,677 | 1.5% | 77.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,249,008 | 1.2% | 78.5% | 0.7% |
| POP_JUMP_IF_TRUE | 3,057,056 | 1.1% | 79.6% |  |
| STORE_ATTR_SLOT | 2,707,962 | 1.0% | 80.7% | 19.3% |
| COMPARE_OP_INT | 2,543,131 | 0.9% | 81.6% | 0.0% |
| PUSH_NULL | 2,408,929 | 0.9% | 82.5% |  |
| LOAD_ATTR_MODULE | 2,309,172 | 0.9% | 83.4% |  |
| NOP | 2,270,884 | 0.8% | 84.2% |  |
| LOAD_ATTR_SLOT | 2,055,688 | 0.8% | 85.0% | 10.8% |
| COPY | 1,796,008 | 0.7% | 85.7% |  |
| LOAD_DEREF | 1,566,388 | 0.6% | 86.2% |  |
| CALL_ISINSTANCE | 1,556,567 | 0.6% | 86.8% |  |
| CALL_BUILTIN_FAST | 1,239,480 | 0.5% | 87.3% |  |
| POP_JUMP_IF_NOT_NONE | 1,233,749 | 0.5% | 87.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,134,012 | 0.4% | 88.2% | 8.3% |
| TO_BOOL_NONE | 1,064,212 | 0.4% | 88.6% | 1.5% |
| BUILD_TUPLE | 1,036,227 | 0.4% | 89.0% |  |
| SWAP | 1,033,463 | 0.4% | 89.3% |  |
| ENTER_EXECUTOR | 945,532 | 0.4% | 89.7% |  |
| TO_BOOL | 931,405 | 0.3% | 90.0% |  |
| BINARY_OP | 821,350 | 0.3% | 90.3% |  |
| BINARY_OP_ADD_INT | 812,712 | 0.3% | 90.6% |  |
| CALL_FUNCTION_EX | 809,397 | 0.3% | 91.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 749,965 | 0.3% | 91.2% | 3.7% |
| CALL_LEN | 738,268 | 0.3% | 91.5% |  |
| STORE_FAST_STORE_FAST | 724,238 | 0.3% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 717,298 | 0.3% | 92.0% |  |
| BINARY_SUBSCR_DICT | 677,024 | 0.3% | 92.3% |  |
| BUILD_LIST | 662,124 | 0.2% | 92.5% |  |
| BINARY_OP_SUBTRACT_INT | 628,033 | 0.2% | 92.8% |  |
| CONTAINS_OP | 595,320 | 0.2% | 93.0% |  |
| BUILD_MAP | 593,580 | 0.2% | 93.2% |  |
| TO_BOOL_INT | 591,232 | 0.2% | 93.4% | 0.8% |
| GET_ITER | 589,306 | 0.2% | 93.7% |  |
| COPY_FREE_VARS | 583,064 | 0.2% | 93.9% |  |
| LOAD_ATTR_WITH_HINT | 575,694 | 0.2% | 94.1% | 2.2% |
| JUMP_FORWARD | 554,838 | 0.2% | 94.3% |  |
| LOAD_ATTR_CLASS | 549,300 | 0.2% | 94.5% | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 543,938 | 0.2% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 534,409 | 0.2% | 94.9% |  |
| YIELD_VALUE | 432,000 | 0.2% | 95.1% |  |
| CALL_PY_WITH_DEFAULTS | 426,972 | 0.2% | 95.2% |  |
| IS_OP | 423,720 | 0.2% | 95.4% |  |
| STORE_SUBSCR_DICT | 423,360 | 0.2% | 95.5% |  |
| BINARY_SLICE | 414,660 | 0.2% | 95.7% |  |
| BINARY_SUBSCR_GETITEM | 369,180 | 0.1% | 95.8% |  |
| DICT_MERGE | 359,220 | 0.1% | 96.0% |  |
| CALL_KW | 345,732 | 0.1% | 96.1% |  |
| GET_AWAITABLE | 342,000 | 0.1% | 96.2% |  |
| PUSH_EXC_INFO | 340,017 | 0.1% | 96.4% |  |
| POP_EXCEPT | 340,017 | 0.1% | 96.5% |  |
| END_SEND | 333,000 | 0.1% | 96.6% |  |
| CHECK_EXC_MATCH | 332,818 | 0.1% | 96.7% |  |
| FOR_ITER_LIST | 312,804 | 0.1% | 96.9% |  |
| MAKE_CELL | 305,220 | 0.1% | 97.0% |  |
| JUMP_BACKWARD | 280,080 | 0.1% | 97.1% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 279,240 | 0.1% | 97.2% | 3.2% |
| MAKE_FUNCTION | 272,090 | 0.1% | 97.3% |  |
| FOR_ITER | 264,189 | 0.1% | 97.4% |  |
| COMPARE_OP_FLOAT | 258,984 | 0.1% | 97.5% |  |
| BINARY_SUBSCR | 253,015 | 0.1% | 97.6% |  |
| SEND | 252,400 | 0.1% | 97.7% |  |
| RETURN_GENERATOR | 252,060 | 0.1% | 97.8% |  |
| EXIT_INIT_CHECK | 243,240 | 0.1% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 243,240 | 0.1% | 97.9% |  |
| LIST_EXTEND | 235,309 | 0.1% | 98.0% |  |
| CALL_INTRINSIC_1 | 226,309 | 0.1% | 98.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 220,354 | 0.1% | 98.2% | 45.9% |
| TO_BOOL_STR | 216,740 | 0.1% | 98.3% | 2.2% |
| SEND_GEN | 216,000 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 207,420 | 0.1% | 98.4% |  |
| FOR_ITER_GEN | 207,000 | 0.1% | 98.5% |  |
| STORE_ATTR | 200,380 | 0.1% | 98.6% |  |
| CALL_LIST_APPEND | 192,610 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 180,580 | 0.1% | 98.7% |  |
| BEFORE_WITH | 174,372 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 171,360 | 0.1% | 98.8% |  |
| BINARY_OP_ADD_UNICODE | 171,060 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 157,610 | 0.1% | 99.0% |  |
| DELETE_FAST | 156,312 | 0.1% | 99.0% |  |
| EXTENDED_ARG | 153,180 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 153,180 | 0.1% | 99.1% |  |
| STORE_FAST_LOAD_FAST | 153,060 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 143,820 | 0.1% | 99.3% |  |
| COMPARE_OP | 132,680 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 126,000 | 0.0% | 99.4% |  |
| CALL_BUILTIN_CLASS | 104,133 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 102,725 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 91,549 | 0.0% | 99.5% |  |
| STORE_DEREF | 90,360 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 90,060 | 0.0% | 99.5% |  |
| DELETE_SUBSCR | 90,060 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 90,000 | 0.0% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 90,000 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 81,120 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 68,982 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 63,240 | 0.0% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 63,180 | 0.0% | 99.7% |  |
| LOAD_FAST_AND_CLEAR | 54,060 | 0.0% | 99.8% |  |
| RERAISE | 54,000 | 0.0% | 99.8% |  |
| BUILD_SLICE | 54,000 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_LIST_INT | 50,257 | 0.0% | 99.8% |  |
| UNARY_INVERT | 45,120 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 45,120 | 0.0% | 99.8% |  |
| CONVERT_VALUE | 45,120 | 0.0% | 99.9% |  |
| END_FOR | 45,000 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 44,898 | 0.0% | 99.9% | 9.5% |
| CALL_BUILTIN_O | 41,021 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 36,000 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 29,400 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 22,713 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20,460 | 0.0% | 100.0% |  |
| BUILD_STRING | 18,060 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 18,000 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 18,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 9,772 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 9,060 | 0.0% | 100.0% |  |
| UNARY_NOT | 9,000 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BUILD_SET | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 9,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,340 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,327,112 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 8,536,428 | 3.2% | 9.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,645,328 | 2.9% | 12.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,458,445 | 2.0% | 14.2% |
| STORE_FAST LOAD_FAST | 4,975,811 | 1.9% | 16.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,766,009 | 1.8% | 17.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,489,240 | 1.7% | 19.5% |
| CACHE RESUME_CHECK | 4,025,276 | 1.5% | 21.0% |
| RETURN_CONST POP_TOP | 3,913,555 | 1.5% | 22.5% |
| LOAD_CONST LOAD_FAST | 3,869,588 | 1.4% | 23.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,841,624 | 1.4% | 25.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,707,953 | 1.4% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 3,351,137 | 1.3% | 28.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,346,597 | 1.2% | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,128,696 | 1.2% | 30.4% |
| POP_TOP LOAD_FAST | 2,939,478 | 1.1% | 31.5% |
| RETURN_VALUE INTERPRETER_EXIT | 2,794,751 | 1.0% | 32.5% |
| LOAD_FAST LOAD_ATTR | 2,680,720 | 1.0% | 33.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,506,037 | 0.9% | 34.5% |
| LOAD_FAST LOAD_CONST | 2,494,248 | 0.9% | 35.4% |
| LOAD_FAST RETURN_VALUE | 2,375,509 | 0.9% | 36.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,299,572 | 0.9% | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 2,276,162 | 0.8% | 38.0% |
| POP_TOP RETURN_CONST | 2,215,565 | 0.8% | 38.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,109,432 | 0.8% | 39.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,078,231 | 0.8% | 40.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,071,785 | 0.8% | 41.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,016,840 | 0.8% | 41.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,993,827 | 0.7% | 42.7% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,942,885 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,706,658 | 0.6% | 44.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,688,690 | 0.6% | 44.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,675,647 | 0.6% | 45.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,631,431 | 0.6% | 45.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,625,454 | 0.6% | 46.5% |
| RETURN_VALUE STORE_FAST | 1,599,529 | 0.6% | 47.1% |
| CALL STORE_FAST | 1,531,656 | 0.6% | 47.7% |
| LOAD_FAST CALL | 1,531,000 | 0.6% | 48.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,528,277 | 0.6% | 48.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,495,806 | 0.6% | 49.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,471,956 | 0.5% | 49.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,436,469 | 0.5% | 50.4% |
| RETURN_VALUE TO_BOOL_BOOL | 1,414,100 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,413,846 | 0.5% | 51.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,403,247 | 0.5% | 52.0% |
| LOAD_FAST STORE_ATTR_SLOT | 1,349,542 | 0.5% | 52.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,348,560 | 0.5% | 53.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,303,644 | 0.5% | 53.5% |
| LOAD_CONST COMPARE_OP_INT | 1,287,337 | 0.5% | 54.0% |
| RETURN_CONST INTERPRETER_EXIT | 1,280,265 | 0.5% | 54.5% |
| NOP LOAD_FAST | 1,268,659 | 0.5% | 54.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,261,577 | 0.5% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,254,956 | 0.5% | 55.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,112,834 | 0.4% | 56.3% |
| PUSH_NULL LOAD_FAST | 1,017,717 | 0.4% | 56.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 978,120 | 0.4% | 57.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 960,490 | 0.4% | 57.4% |
| RESUME_CHECK NOP | 935,030 | 0.3% | 57.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 911,095 | 0.3% | 58.1% |
| LOAD_CONST STORE_FAST | 905,866 | 0.3% | 58.4% |
| LOAD_ATTR LOAD_FAST | 878,148 | 0.3% | 58.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 872,883 | 0.3% | 59.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 844,627 | 0.3% | 59.4% |
| LOAD_FAST COPY | 837,865 | 0.3% | 59.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 818,460 | 0.3% | 60.0% |
| LOAD_CONST LOAD_CONST | 804,936 | 0.3% | 60.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 797,150 | 0.3% | 60.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 792,238 | 0.3% | 60.9% |
| TO_BOOL POP_JUMP_IF_FALSE | 787,967 | 0.3% | 61.2% |
| STORE_ATTR_SLOT LOAD_CONST | 786,000 | 0.3% | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 783,260 | 0.3% | 61.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 782,789 | 0.3% | 62.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 755,632 | 0.3% | 62.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 748,140 | 0.3% | 62.7% |
| CALL POP_TOP | 737,932 | 0.3% | 62.9% |
| RETURN_VALUE RETURN_VALUE | 729,180 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 715,490 | 0.3% | 63.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 695,660 | 0.3% | 63.7% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 693,685 | 0.3% | 64.0% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 693,685 | 0.3% | 64.2% |
| POP_TOP LOAD_CONST | 686,986 | 0.3% | 64.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 675,360 | 0.3% | 64.8% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 670,980 | 0.3% | 65.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 655,657 | 0.2% | 65.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 652,392 | 0.2% | 65.5% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 642,360 | 0.2% | 65.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 636,416 | 0.2% | 66.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 628,260 | 0.2% | 66.2% |
| CALL LOAD_FAST | 626,510 | 0.2% | 66.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 620,965 | 0.2% | 66.7% |
| CALL_BUILTIN_FAST STORE_FAST | 610,920 | 0.2% | 66.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 605,945 | 0.2% | 67.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 595,080 | 0.2% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 594,120 | 0.2% | 67.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 589,303 | 0.2% | 67.8% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 575,439 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 569,522 | 0.2% | 68.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 550,860 | 0.2% | 68.4% |
| PUSH_NULL CALL | 548,108 | 0.2% | 68.6% |
| COPY_FREE_VARS RESUME_CHECK | 546,944 | 0.2% | 68.8% |


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
| RESUME_CHECK | 4,025,276 | 93.8% |
| COPY_FREE_VARS | 175,740 | 4.1% |
| POP_TOP | 72,060 | 1.7% |
| RETURN_GENERATOR | 9,000 | 0.2% |
| MAKE_CELL | 9,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 84,252 | 48.3% |
| RETURN_VALUE | 81,000 | 46.5% |
| LOAD_GLOBAL_MODULE | 9,120 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 174,372 | 100.0% |


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
| LOAD_CONST | 252,375 | 99.7% |
| BINARY_SUBSCR | 640 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 135,000 | 53.4% |
| LOAD_FAST | 45,000 | 17.8% |
| CONVERT_VALUE | 18,000 | 7.1% |
| BINARY_SUBSCR_LIST_INT | 9,160 | 3.6% |
| CALL_LEN | 9,060 | 3.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 293,506 | 88.2% |
| BUILD_TUPLE | 18,060 | 5.4% |
| LOAD_ATTR_MODULE | 12,252 | 3.7% |
| LOAD_GLOBAL_MODULE | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 332,818 | 100.0% |


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
| LOAD_FAST | 241,767 | 41.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 108,180 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,286 | 12.3% |
| LOAD_ATTR | 54,000 | 9.2% |
| BINARY_SLICE | 27,180 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 303,264 | 51.5% |
| FOR_ITER | 110,149 | 18.7% |
| FOR_ITER_TUPLE | 54,180 | 9.2% |
| CALL_PY_EXACT_ARGS | 54,000 | 9.2% |
| LOAD_FAST_AND_CLEAR | 36,060 | 6.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,794,751 | 65.3% |
| RETURN_CONST | 1,280,265 | 29.9% |
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
| LOAD_CONST | 272,090 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 119,030 | 43.7% |
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
| RESUME_CHECK | 935,030 | 41.2% |
| POP_JUMP_IF_FALSE | 337,004 | 14.8% |
| STORE_FAST | 290,559 | 12.8% |
| STORE_ATTR_INSTANCE_VALUE | 229,800 | 10.1% |
| POP_JUMP_IF_TRUE | 206,270 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,268,659 | 55.9% |
| LOAD_GLOBAL_MODULE | 442,100 | 19.5% |
| LOAD_FAST_LOAD_FAST | 225,000 | 9.9% |
| LOAD_DEREF | 100,964 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 90,060 | 4.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 246,705 | 72.6% |
| SWAP | 45,000 | 13.2% |
| COPY | 27,000 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 9,060 | 2.7% |
| STORE_SUBSCR_DICT | 9,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 217,921 | 64.1% |
| RETURN_VALUE | 45,000 | 13.2% |
| RERAISE | 27,000 | 7.9% |
| DELETE_FAST | 18,000 | 5.3% |
| ENTER_EXECUTOR | 12,252 | 3.6% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,913,555 | 51.6% |
| CALL | 737,932 | 9.7% |
| CALL_METHOD_DESCRIPTOR_O | 620,965 | 8.2% |
| POP_JUMP_IF_FALSE | 452,173 | 6.0% |
| CALL_FUNCTION_EX | 375,465 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,939,478 | 38.7% |
| RETURN_CONST | 2,215,565 | 29.2% |
| LOAD_CONST | 686,986 | 9.1% |
| ENTER_EXECUTOR | 530,134 | 7.0% |
| RESUME_CHECK | 252,060 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 261,120 | 76.8% |
| RERAISE | 27,000 | 7.9% |
| CALL | 23,053 | 6.8% |
| ENTER_EXECUTOR | 9,058 | 2.7% |
| CALL_METHOD_DESCRIPTOR_O | 9,002 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300,765 | 88.5% |
| LOAD_GLOBAL_MODULE | 30,252 | 8.9% |
| LOAD_FAST | 9,000 | 2.6% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,261,577 | 52.4% |
| LOAD_ATTR | 499,956 | 20.8% |
| LOAD_FAST | 349,976 | 14.5% |
| LOAD_DEREF | 153,240 | 6.4% |
| RETURN_VALUE | 99,060 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,017,717 | 42.2% |
| CALL | 548,108 | 22.8% |
| LOAD_FAST_LOAD_FAST | 534,464 | 22.2% |
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
| LOAD_FAST | 2,375,509 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,016,840 | 23.3% |
| RETURN_VALUE | 729,180 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 466,920 | 5.4% |
| CALL | 464,348 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,794,751 | 32.3% |
| STORE_FAST | 1,599,529 | 18.5% |
| TO_BOOL_BOOL | 1,414,100 | 16.3% |
| RETURN_VALUE | 729,180 | 8.4% |
| LOAD_FAST | 452,149 | 5.2% |


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
| LOAD_FAST | 418,397 | 44.9% |
| LOAD_ATTR_INSTANCE_VALUE | 385,268 | 41.4% |
| LOAD_ATTR | 90,150 | 9.7% |
| COPY | 26,420 | 2.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,100 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 787,967 | 84.6% |
| POP_JUMP_IF_TRUE | 140,995 | 15.1% |
| TO_BOOL | 1,519 | 0.2% |
| TO_BOOL_BOOL | 580 | 0.1% |
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
| LOAD_GLOBAL_MODULE | 140,459 | 17.1% |
| LOAD_CONST | 126,862 | 15.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 117,000 | 14.2% |
| LOAD_FAST | 76,870 | 9.4% |
| LOAD_ATTR_CLASS | 72,120 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 217,303 | 26.5% |
| STORE_FAST | 155,674 | 19.0% |
| COPY | 100,814 | 12.3% |
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
| STORE_FAST | 83,749 | 12.6% |
| LOAD_FAST_LOAD_FAST | 80,460 | 12.2% |
| RESUME_CHECK | 54,180 | 8.2% |
| SWAP | 36,060 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 496,489 | 75.0% |
| STORE_FAST | 102,215 | 15.4% |
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
| LOAD_FAST | 383,580 | 37.0% |
| LOAD_FAST_LOAD_FAST | 288,240 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 117,300 | 11.3% |
| LOAD_GLOBAL_MODULE | 72,180 | 7.0% |
| LOAD_ATTR_MODULE | 54,000 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 144,000 | 13.9% |
| RETURN_VALUE | 135,360 | 13.1% |
| LOAD_CONST | 119,030 | 11.5% |
| CALL_ISINSTANCE | 117,300 | 11.3% |
| CONTAINS_OP | 90,060 | 8.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,531,000 | 32.4% |
| PUSH_NULL | 548,108 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 459,160 | 9.7% |
| LOAD_GLOBAL_MODULE | 441,382 | 9.3% |
| LOAD_CONST | 398,045 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,531,656 | 32.4% |
| POP_TOP | 737,932 | 15.6% |
| LOAD_FAST | 626,510 | 13.3% |
| RETURN_VALUE | 464,348 | 9.8% |
| BINARY_SUBSCR_DICT | 315,060 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 359,220 | 44.4% |
| ENTER_EXECUTOR | 273,416 | 33.8% |
| LOAD_FAST | 75,372 | 9.3% |
| CALL_INTRINSIC_1 | 56,989 | 7.0% |
| BUILD_MAP | 44,400 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 375,465 | 46.4% |
| RETURN_VALUE | 164,712 | 20.3% |
| RESUME_CHECK | 99,060 | 12.2% |
| STORE_FAST | 89,520 | 11.1% |
| CALL | 62,460 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 217,309 | 96.0% |
| RERAISE | 9,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 115,920 | 51.2% |
| CALL_FUNCTION_EX | 56,989 | 25.2% |
| LOAD_CONST | 44,400 | 19.6% |
| RERAISE | 9,000 | 4.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300,732 | 87.0% |
| ENTER_EXECUTOR | 45,000 | 13.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 198,180 | 57.3% |
| STORE_FAST | 75,252 | 21.8% |
| COPY_FREE_VARS | 18,000 | 5.2% |
| LOAD_FAST | 9,120 | 2.6% |
| RETURN_VALUE | 9,060 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 86,954 | 65.5% |
| LOAD_ATTR | 18,000 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 6.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.8% |
| LOAD_ATTR_CLASS | 9,000 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 87,054 | 65.6% |
| POP_JUMP_IF_TRUE | 45,000 | 33.9% |
| COMPARE_OP | 442 | 0.3% |
| COMPARE_OP_INT | 104 | 0.1% |
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
| LOAD_FAST | 837,865 | 46.7% |
| LOAD_CONST | 189,060 | 10.5% |
| STORE_ATTR_INSTANCE_VALUE | 171,000 | 9.5% |
| BINARY_OP | 100,814 | 5.6% |
| CONTAINS_OP | 90,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 693,685 | 38.6% |
| LOAD_FAST | 342,000 | 19.0% |
| TO_BOOL_BOOL | 243,000 | 13.5% |
| TO_BOOL_NONE | 143,994 | 8.0% |
| TO_BOOL_INT | 121,729 | 6.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 216,336 | 37.1% |
| CACHE | 175,740 | 30.1% |
| CALL | 90,120 | 15.5% |
| LOAD_ATTR_PROPERTY | 63,000 | 10.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,628 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 546,944 | 93.8% |
| RETURN_GENERATOR | 18,060 | 3.1% |
| MAKE_CELL | 18,060 | 3.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 81,000 | 51.8% |
| STORE_ATTR_INSTANCE_VALUE | 18,000 | 11.5% |
| POP_EXCEPT | 18,000 | 11.5% |
| NOP | 18,000 | 11.5% |
| POP_TOP | 12,252 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 81,000 | 51.8% |
| RETURN_CONST | 36,000 | 23.0% |
| LOAD_FAST | 21,252 | 13.6% |
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
| POP_TOP | 530,134 | 56.1% |
| POP_JUMP_IF_TRUE | 111,585 | 11.8% |
| CALL_LIST_APPEND | 75,370 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 63,000 | 6.7% |
| EXTENDED_ARG | 45,000 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 273,416 | 28.9% |
| CALL | 136,789 | 14.5% |
| LOAD_FAST | 119,193 | 12.6% |
| RESUME_CHECK | 90,870 | 9.6% |
| JUMP_BACKWARD | 81,060 | 8.6% |


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
| GET_ITER | 110,149 | 41.7% |
| SWAP | 18,000 | 6.8% |
| LOAD_FAST | 18,000 | 6.8% |
| FOR_ITER | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 101,029 | 38.2% |
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
| STORE_FAST | 330,065 | 59.5% |
| POP_TOP | 99,060 | 17.9% |
| STORE_ATTR_INSTANCE_VALUE | 36,346 | 6.6% |
| STORE_ATTR | 18,000 | 3.2% |
| POP_JUMP_IF_TRUE | 18,000 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 355,043 | 64.0% |
| LOAD_CONST | 69,036 | 12.4% |
| LOAD_FAST_LOAD_FAST | 45,000 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 31,499 | 5.7% |
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
| LOAD_ATTR_SLOT | 11,749 | 5.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 3.8% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 217,309 | 92.4% |
| LOAD_FAST | 18,000 | 7.6% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,680,720 | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE | 652,392 | 15.8% |
| LOAD_ATTR_WITH_HINT | 252,000 | 6.1% |
| LOAD_GLOBAL_MODULE | 225,720 | 5.5% |
| LOAD_DEREF | 113,020 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 878,148 | 21.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 670,980 | 16.2% |
| PUSH_NULL | 499,956 | 12.1% |
| LOAD_CONST | 360,075 | 8.7% |
| CALL_PY_EXACT_ARGS | 239,871 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,494,248 | 20.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,254,956 | 10.5% |
| LOAD_CONST | 804,936 | 6.7% |
| POP_JUMP_IF_FALSE | 792,238 | 6.6% |
| STORE_ATTR_SLOT | 786,000 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,869,588 | 32.4% |
| COMPARE_OP_INT | 1,287,337 | 10.8% |
| STORE_FAST | 905,866 | 7.6% |
| LOAD_CONST | 804,936 | 6.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 476,180 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 299,460 | 19.1% |
| RESUME_CHECK | 155,760 | 9.9% |
| POP_JUMP_IF_FALSE | 128,520 | 8.2% |
| POP_JUMP_IF_TRUE | 108,240 | 6.9% |
| NOP | 100,964 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 377,820 | 24.1% |
| LOAD_ATTR_INSTANCE_VALUE | 277,200 | 17.7% |
| PUSH_NULL | 153,240 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 117,000 | 7.5% |
| LOAD_ATTR | 113,020 | 7.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,536,428 | 15.4% |
| POP_JUMP_IF_FALSE | 5,458,445 | 9.8% |
| STORE_FAST | 4,975,811 | 9.0% |
| LOAD_CONST | 3,869,588 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 3,841,624 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,327,112 | 29.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,489,240 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 3,707,953 | 6.7% |
| LOAD_ATTR | 2,680,720 | 4.8% |
| CALL_PY_EXACT_ARGS | 2,506,037 | 4.5% |


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
| LOAD_ATTR_METHOD_NO_DICT | 11,400 | 38.8% |
| STORE_FAST | 9,000 | 30.6% |
| POP_JUMP_IF_FALSE | 9,000 | 30.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 11,400 | 38.8% |
| LOAD_CONST | 9,000 | 30.6% |
| LOAD_ATTR | 9,000 | 30.6% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 978,120 | 12.7% |
| LOAD_GLOBAL_MODULE | 818,460 | 10.6% |
| STORE_FAST | 797,150 | 10.4% |
| STORE_ATTR_INSTANCE_VALUE | 748,140 | 9.7% |
| POP_JUMP_IF_FALSE | 675,360 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,495,806 | 19.4% |
| STORE_ATTR_SLOT | 1,348,560 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 960,490 | 12.5% |
| LOAD_FAST | 655,657 | 8.5% |
| LOAD_FAST_LOAD_FAST | 550,860 | 7.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 340 | 14.5% |
| STORE_FAST | 295 | 12.6% |
| POP_JUMP_IF_FALSE | 295 | 12.6% |
| STORE_ATTR_INSTANCE_VALUE | 160 | 6.8% |
| POP_TOP | 140 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,640 | 70.1% |
| LOAD_GLOBAL_BUILTIN | 620 | 26.5% |
| LOAD_ATTR | 35 | 1.5% |
| LOAD_GLOBAL | 15 | 0.6% |
| LOAD_CONST | 15 | 0.6% |


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
| MAKE_CELL | 140,340 | 46.0% |
| CALL_PY_EXACT_ARGS | 86,158 | 28.2% |
| ENTER_EXECUTOR | 33,542 | 11.0% |
| COPY_FREE_VARS | 18,060 | 5.9% |
| CALL_KW | 9,000 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 155,880 | 51.1% |
| MAKE_CELL | 140,340 | 46.0% |
| RETURN_GENERATOR | 9,000 | 2.9% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,766,009 | 45.8% |
| COMPARE_OP_INT | 1,993,827 | 19.1% |
| TO_BOOL_NONE | 911,095 | 8.7% |
| TO_BOOL | 787,967 | 7.6% |
| CONTAINS_OP | 450,900 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,458,445 | 52.4% |
| RETURN_CONST | 1,112,834 | 10.7% |
| LOAD_CONST | 792,238 | 7.6% |
| LOAD_GLOBAL_MODULE | 755,632 | 7.3% |
| LOAD_FAST_LOAD_FAST | 675,360 | 6.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,276,162 | 56.1% |
| LOAD_FAST | 1,528,277 | 37.7% |
| LOAD_DEREF | 99,060 | 2.4% |
| LOAD_ATTR | 99,060 | 2.4% |
| LOAD_ATTR_WITH_HINT | 26,818 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,351,137 | 82.6% |
| RETURN_CONST | 209,760 | 5.2% |
| LOAD_GLOBAL_MODULE | 207,100 | 5.1% |
| LOAD_FAST_LOAD_FAST | 108,240 | 2.7% |
| NOP | 99,060 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 782,789 | 63.4% |
| LOAD_ATTR_INSTANCE_VALUE | 333,000 | 27.0% |
| LOAD_ATTR | 81,360 | 6.6% |
| LOAD_GLOBAL_MODULE | 9,300 | 0.8% |
| RETURN_VALUE | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 433,419 | 35.1% |
| LOAD_FAST_LOAD_FAST | 326,520 | 26.5% |
| LOAD_GLOBAL_MODULE | 248,610 | 20.2% |
| LOAD_CONST | 99,000 | 8.0% |
| LOAD_DEREF | 63,120 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,675,647 | 54.8% |
| COMPARE_OP_INT | 531,300 | 17.4% |
| TO_BOOL_INT | 195,548 | 6.4% |
| TO_BOOL_STR | 180,420 | 5.9% |
| TO_BOOL_NONE | 152,786 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,436,469 | 47.0% |
| LOAD_GLOBAL_BUILTIN | 333,120 | 10.9% |
| NOP | 206,270 | 6.7% |
| LOAD_FAST_LOAD_FAST | 171,240 | 5.6% |
| LOAD_CONST | 170,793 | 5.6% |


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
| POP_TOP | 2,215,565 | 37.4% |
| POP_JUMP_IF_FALSE | 1,112,834 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 569,522 | 9.6% |
| STORE_ATTR_SLOT | 459,960 | 7.8% |
| STORE_FAST | 296,914 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,913,555 | 66.1% |
| INTERPRETER_EXIT | 1,280,265 | 21.6% |
| EXIT_INIT_CHECK | 243,240 | 4.1% |
| STORE_FAST | 131,750 | 2.2% |
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
| MAKE_FUNCTION | 119,030 | 75.5% |
| SET_FUNCTION_ATTRIBUTE | 38,580 | 24.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,330 | 33.8% |
| SET_FUNCTION_ATTRIBUTE | 38,580 | 24.5% |
| CALL | 29,620 | 18.8% |
| LOAD_FAST | 18,000 | 11.4% |
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
| RETURN_VALUE | 1,599,529 | 19.8% |
| CALL | 1,531,656 | 19.0% |
| LOAD_CONST | 905,866 | 11.2% |
| CALL_BUILTIN_FAST | 610,920 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 530,401 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,975,811 | 61.6% |
| LOAD_FAST_LOAD_FAST | 797,150 | 9.9% |
| LOAD_CONST | 438,603 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 362,118 | 4.5% |
| JUMP_FORWARD | 330,065 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 534,818 | 73.8% |
| UNPACK_SEQUENCE_LIST | 90,000 | 12.4% |
| UNPACK_SEQUENCE_TUPLE | 54,180 | 7.5% |
| STORE_FAST_STORE_FAST | 18,120 | 2.5% |
| COPY | 18,060 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 399,698 | 55.2% |
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
| BINARY_OP_ADD_INT | 425,652 | 41.2% |
| BINARY_OP_SUBTRACT_INT | 250,033 | 24.2% |
| LOAD_FAST | 144,000 | 13.9% |
| LOAD_ATTR | 42,598 | 4.1% |
| LOAD_FAST_AND_CLEAR | 36,060 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 693,685 | 67.1% |
| COPY | 81,060 | 7.8% |
| STORE_FAST | 69,598 | 6.7% |
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
| LOAD_ATTR_INSTANCE_VALUE | 11,749 | 12.8% |
| LOAD_ATTR | 9,000 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,400 | 58.3% |
| LOAD_GLOBAL_MODULE | 26,400 | 28.8% |
| STORE_FAST | 11,749 | 12.8% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 507,252 | 62.4% |
| LOAD_FAST_LOAD_FAST | 198,000 | 24.4% |
| CALL_LEN | 63,000 | 7.8% |
| LOAD_CONST | 44,440 | 5.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 425,652 | 52.4% |
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
| RETURN_VALUE | 9,000 | 92.1% |
| LOAD_CONST | 752 | 7.7% |
| BINARY_OP | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,000 | 92.1% |
| CALL_BUILTIN_O | 752 | 7.7% |
| CALL | 20 | 0.2% |


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
| RETURN_VALUE | 45,152 | 65.5% |
| LOAD_ATTR_WITH_HINT | 9,000 | 13.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 13.0% |
| CALL | 5,750 | 8.3% |
| LOAD_FAST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 45,172 | 65.5% |
| RETURN_VALUE | 9,000 | 13.0% |
| LOAD_FAST | 9,000 | 13.0% |
| STORE_FAST | 5,750 | 8.3% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 423,000 | 67.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,000 | 11.5% |
| BINARY_OP_SUBTRACT_INT | 63,000 | 10.0% |
| CALL_LEN | 45,000 | 7.2% |
| LOAD_CONST | 25,033 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 250,033 | 39.8% |
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
| CALL | 315,060 | 46.5% |
| LOAD_FAST | 262,844 | 38.8% |
| BUILD_TUPLE | 36,060 | 5.3% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| RETURN_VALUE | 18,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,000 | 47.9% |
| PUSH_EXC_INFO | 261,120 | 38.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 28,784 | 4.3% |
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
| LOAD_CONST | 32,097 | 63.9% |
| BINARY_SUBSCR | 9,160 | 18.2% |
| BINARY_OP_SUBTRACT_INT | 9,000 | 17.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,060 | 35.9% |
| STORE_FAST | 11,557 | 23.0% |
| LOAD_ATTR_SLOT | 9,536 | 19.0% |
| LOAD_CONST | 9,000 | 17.9% |
| TO_BOOL_BOOL | 1,784 | 3.5% |


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
| LOAD_CONST | 81,000 | 36.8% |
| LOAD_FAST | 64,798 | 29.4% |
| LOAD_FAST_LOAD_FAST | 35,854 | 16.3% |
| CALL_BUILTIN_CLASS | 18,000 | 8.2% |
| BINARY_SLICE | 18,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 117,805 | 53.5% |
| POP_TOP | 81,000 | 36.8% |
| COPY_FREE_VARS | 19,628 | 8.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,580 | 0.7% |
| CALL_PY_EXACT_ARGS | 341 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,909 | 28.7% |
| LOAD_ATTR_INSTANCE_VALUE | 27,120 | 26.0% |
| LOAD_GLOBAL_MODULE | 10,824 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 9,080 | 8.7% |
| RETURN_GENERATOR | 9,000 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,000 | 25.9% |
| GET_ITER | 22,593 | 21.7% |
| LOAD_FAST | 18,120 | 17.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 18,000 | 17.3% |
| LOAD_DEREF | 9,000 | 8.6% |


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
| LOAD_ATTR | 11,400 | 55.7% |
| LOAD_FAST | 9,060 | 44.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,400 | 55.7% |
| STORE_FAST | 9,060 | 44.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,326 | 88.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,783 | 9.2% |
| BINARY_OP_MULTIPLY_FLOAT | 752 | 1.8% |
| CALL | 80 | 0.2% |
| LOAD_CONST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 18,000 | 43.9% |
| STORE_FAST | 12,783 | 31.2% |
| BINARY_SUBSCR_DICT | 9,000 | 21.9% |
| LOAD_CONST | 772 | 1.9% |
| POP_TOP | 406 | 1.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 844,627 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 325,020 | 20.9% |
| LOAD_ATTR_MODULE | 224,400 | 14.4% |
| BUILD_TUPLE | 117,300 | 7.5% |
| LOAD_ATTR | 45,080 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,403,247 | 90.2% |
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
| LOAD_FAST | 486,240 | 65.9% |
| LOAD_ATTR_INSTANCE_VALUE | 233,848 | 31.7% |
| BINARY_SUBSCR | 9,060 | 1.2% |
| LOAD_GLOBAL_MODULE | 9,000 | 1.2% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 215,619 | 29.2% |
| LOAD_FAST | 169,740 | 23.0% |
| LOAD_CONST | 72,240 | 9.8% |
| BINARY_OP_ADD_INT | 63,000 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 45,000 | 6.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 102,543 | 53.2% |
| BUILD_TUPLE | 50,077 | 26.0% |
| ENTER_EXECUTOR | 21,830 | 11.3% |
| RETURN_VALUE | 18,120 | 9.4% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 90,000 | 46.7% |
| ENTER_EXECUTOR | 75,370 | 39.1% |
| LOAD_FAST | 18,000 | 9.3% |
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
| LOAD_FAST_LOAD_FAST | 54,120 | 7.5% |
| RETURN_VALUE | 18,060 | 2.5% |
| LOAD_FAST | 15,578 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 466,920 | 65.1% |
| CALL_PY_EXACT_ARGS | 81,080 | 11.3% |
| STORE_FAST | 69,718 | 9.7% |
| LOAD_CONST | 54,000 | 7.5% |
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
| LOAD_FAST_LOAD_FAST | 11,749 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,229 | 37.7% |
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
| LOAD_ATTR | 670,980 | 59.2% |
| LOAD_ATTR_METHOD_NO_DICT | 433,883 | 38.3% |
| LOAD_FAST | 18,060 | 1.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,000 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,789 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 695,660 | 61.3% |
| POP_TOP | 113,810 | 10.0% |
| GET_ITER | 108,180 | 9.5% |
| LOAD_FAST | 54,180 | 4.8% |
| STORE_FAST | 50,149 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 431,905 | 57.6% |
| BUILD_TUPLE | 144,000 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 8.4% |
| LOAD_CONST | 36,040 | 4.8% |
| CALL | 27,080 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 620,965 | 82.8% |
| STORE_FAST | 74,398 | 9.9% |
| UNPACK_SEQUENCE_TUPLE | 18,000 | 2.4% |
| LOAD_CONST | 18,000 | 2.4% |
| LOAD_FAST | 9,060 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,346,597 | 41.1% |
| LOAD_FAST | 2,506,037 | 30.8% |
| LOAD_FAST_LOAD_FAST | 496,510 | 6.1% |
| LOAD_CONST | 432,160 | 5.3% |
| LOAD_ATTR | 239,871 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,645,328 | 93.8% |
| COPY_FREE_VARS | 216,336 | 2.7% |
| RETURN_GENERATOR | 198,000 | 2.4% |
| MAKE_CELL | 86,158 | 1.1% |
| TO_BOOL_BOOL | 2,402 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,000 | 25.3% |
| LOAD_FAST | 99,200 | 23.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 93,252 | 21.8% |
| PUSH_NULL | 54,260 | 12.7% |
| LOAD_ATTR | 27,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 417,912 | 97.9% |
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
| LOAD_ATTR_SLOT | 247,487 | 95.6% |
| LOAD_FAST | 11,497 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 247,487 | 95.6% |
| POP_JUMP_IF_FALSE | 11,497 | 4.4% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,287,337 | 50.6% |
| LOAD_ATTR_INSTANCE_VALUE | 715,490 | 28.1% |
| LOAD_ATTR_CLASS | 288,000 | 11.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 90,000 | 3.5% |
| COPY | 81,060 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,993,827 | 78.4% |
| POP_JUMP_IF_TRUE | 531,300 | 20.9% |
| COPY | 18,000 | 0.7% |
| COMPARE_OP | 4 | 0.0% |


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
| GET_ITER | 303,264 | 97.0% |
| SWAP | 9,000 | 2.9% |
| JUMP_BACKWARD | 420 | 0.1% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 171,946 | 55.0% |
| LOAD_FAST | 104,271 | 33.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 22,076 | 7.1% |
| UNPACK_SEQUENCE_TUPLE | 9,000 | 2.9% |
| RETURN_CONST | 5,391 | 1.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 22,593 | 99.5% |
| SWAP | 60 | 0.3% |
| JUMP_BACKWARD | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,593 | 99.5% |
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
| LOAD_FAST | 16,327,112 | 86.6% |
| LOAD_FAST_LOAD_FAST | 960,490 | 5.1% |
| COPY | 693,685 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 594,120 | 3.2% |
| LOAD_DEREF | 277,200 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,128,696 | 16.6% |
| POP_JUMP_IF_NONE | 2,276,162 | 12.1% |
| RETURN_VALUE | 2,016,840 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 1,706,658 | 9.1% |
| TO_BOOL_BOOL | 1,688,690 | 9.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 1,706,658 | 52.5% |
| LOAD_FAST | 872,883 | 26.9% |
| BINARY_SLICE | 189,040 | 5.8% |
| LOAD_CONST | 99,040 | 3.0% |
| BINARY_SUBSCR_STR_INT | 81,080 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,413,846 | 43.5% |
| LOAD_CONST | 605,945 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 433,883 | 13.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 171,000 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 153,000 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,489,240 | 68.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,303,644 | 19.9% |
| LOAD_ATTR_SLOT | 441,900 | 6.7% |
| LOAD_DEREF | 92,700 | 1.4% |
| LOAD_FAST_LOAD_FAST | 81,212 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,346,597 | 51.0% |
| LOAD_FAST | 2,071,785 | 31.6% |
| LOAD_FAST_LOAD_FAST | 506,640 | 7.7% |
| LOAD_CONST | 324,060 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 107,400 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,299,572 | 99.6% |
| LOAD_ATTR_MODULE | 9,000 | 0.4% |
| LOAD_ATTR | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,261,577 | 54.6% |
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
| LOAD_FAST | 1,942,885 | 94.5% |
| BINARY_SUBSCR_TUPLE_INT | 90,060 | 4.4% |
| BINARY_SUBSCR_LIST_INT | 9,536 | 0.5% |
| LOAD_DEREF | 9,000 | 0.4% |
| LOAD_ATTR_SLOT | 4,187 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 642,360 | 31.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 441,900 | 21.5% |
| LOAD_FAST | 258,984 | 12.6% |
| COMPARE_OP_FLOAT | 247,487 | 12.0% |
| TO_BOOL_BOOL | 226,631 | 11.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,439 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 255 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,000 | 43.8% |
| LOAD_CONST | 72,000 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,818 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 45,000 | 7.8% |
| RETURN_VALUE | 27,000 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,078,231 | 40.0% |
| LOAD_FAST | 595,080 | 11.5% |
| POP_JUMP_IF_FALSE | 477,753 | 9.2% |
| STORE_FAST | 362,118 | 7.0% |
| POP_JUMP_IF_TRUE | 333,120 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,841,624 | 73.9% |
| CALL_ISINSTANCE | 325,020 | 6.3% |
| LOAD_DEREF | 299,460 | 5.8% |
| CHECK_EXC_MATCH | 293,506 | 5.6% |
| BUILD_TUPLE | 117,300 | 2.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,625,454 | 20.5% |
| RESUME_CHECK | 1,471,956 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 783,260 | 9.9% |
| POP_JUMP_IF_FALSE | 755,632 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 589,303 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,299,572 | 29.1% |
| LOAD_FAST | 1,631,431 | 20.6% |
| CALL_ISINSTANCE | 844,627 | 10.7% |
| LOAD_FAST_LOAD_FAST | 818,460 | 10.3% |
| CALL | 441,382 | 5.6% |


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
| CALL_PY_EXACT_ARGS | 7,645,328 | 52.0% |
| CACHE | 4,025,276 | 27.4% |
| COPY_FREE_VARS | 546,944 | 3.7% |
| CALL_PY_WITH_DEFAULTS | 417,912 | 2.8% |
| BINARY_SUBSCR_GETITEM | 369,180 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,536,428 | 58.1% |
| LOAD_GLOBAL_BUILTIN | 2,078,231 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,471,956 | 10.0% |
| NOP | 935,030 | 6.4% |
| LOAD_CONST | 488,940 | 3.3% |


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
| LOAD_FAST | 3,707,953 | 60.9% |
| LOAD_FAST_LOAD_FAST | 1,495,806 | 24.6% |
| SWAP | 693,685 | 11.4% |
| LOAD_DEREF | 117,000 | 1.9% |
| STORE_FAST_LOAD_FAST | 63,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,109,432 | 34.7% |
| LOAD_CONST | 1,254,956 | 20.6% |
| LOAD_FAST_LOAD_FAST | 748,140 | 12.3% |
| LOAD_GLOBAL_MODULE | 589,303 | 9.7% |
| RETURN_CONST | 569,522 | 9.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,349,542 | 49.8% |
| LOAD_FAST_LOAD_FAST | 1,348,560 | 49.8% |
| STORE_ATTR_SLOT | 9,860 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 978,120 | 36.1% |
| LOAD_CONST | 786,000 | 29.0% |
| LOAD_FAST | 463,743 | 17.1% |
| RETURN_CONST | 459,960 | 17.0% |
| ENTER_EXECUTOR | 10,279 | 0.4% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,813 | 79.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 20.0% |
| STORE_ATTR_INSTANCE_VALUE | 85 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,000 | 80.2% |
| RETURN_CONST | 8,818 | 19.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,688,690 | 25.8% |
| RETURN_VALUE | 1,414,100 | 21.6% |
| CALL_ISINSTANCE | 1,403,247 | 21.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 695,660 | 10.6% |
| LOAD_FAST | 299,720 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,766,009 | 72.9% |
| POP_JUMP_IF_TRUE | 1,675,647 | 25.6% |
| EXTENDED_ARG | 90,000 | 1.4% |
| UNARY_NOT | 9,000 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 243,120 | 41.1% |
| BINARY_OP | 217,303 | 36.8% |
| COPY | 121,729 | 20.6% |
| LOAD_ATTR | 9,000 | 1.5% |
| TO_BOOL_NONE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 395,592 | 66.9% |
| POP_JUMP_IF_TRUE | 195,548 | 33.1% |
| TO_BOOL_NONE | 92 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 102,585 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 102,725 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 642,360 | 60.4% |
| COPY | 143,994 | 13.5% |
| LOAD_FAST | 142,182 | 13.4% |
| LOAD_ATTR | 63,000 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 54,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 911,095 | 85.6% |
| POP_JUMP_IF_TRUE | 152,786 | 14.4% |
| TO_BOOL | 151 | 0.0% |
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
| BINARY_SUBSCR | 135,000 | 24.8% |
| RETURN_VALUE | 117,240 | 21.6% |
| FOR_ITER | 81,040 | 14.9% |
| YIELD_VALUE | 81,000 | 14.9% |
| STORE_FAST | 42,598 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 534,818 | 98.3% |
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
| specialization.deferred |       252075 | 15.7% |
|          hit |      1348941 | 84.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 300 | 31.9% |
| Failure | 640 | 68.1% |

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
| specialization.deferred |       928962 | 9.8% |
| specialization.deopt |          503 | 0.0% |
|          hit |      8525942 | 89.9% |
|         miss |        25623 | 0.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,276 | 43.3% |
| Failure | 1,670 | 56.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 578 | 34.6% |
| sequence | 381 | 22.8% |
| float | 240 | 14.4% |
| dict | 160 | 9.6% |
| mapping | 111 | 6.6% |
| tuple | 80 | 4.8% |
| bytearray | 80 | 4.8% |
| set | 40 | 2.4% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       819458 | 31.4% |
|          hit |      1791168 | 68.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 6.3% |
| Failure | 1,772 | 93.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 773 | 43.6% |
| add other | 280 | 15.8% |
| or | 279 | 15.7% |
| remainder | 200 | 11.3% |
| add different types | 122 | 6.9% |
| multiply different types | 78 | 4.4% |
| floor divide | 40 | 2.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4713541 | 22.4% |
| specialization.deopt |         5148 | 0.0% |
|          hit |     16087532 | 76.3% |
|         miss |       269670 | 1.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,236 | 46.7% |
| Failure | 8,245 | 53.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,571 | 19.1% |
| class no vectorcall | 1,360 | 16.5% |
| cfunc noargs | 1,040 | 12.6% |
| meth descr method fastcall keywords | 920 | 11.2% |
| meth descr varargs | 812 | 9.8% |
| cfunc varargs keywords | 716 | 8.7% |
| class mutable | 420 | 5.1% |
| other | 382 | 4.6% |
| meth descr varargs keywords | 324 | 3.9% |
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
| specialization.deferred |       132054 | 4.2% |
| specialization.deopt |            4 | 0.0% |
|          hit |      3008688 | 95.8% |
|         miss |          847 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 184 | 29.2% |
| Failure | 446 | 70.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 120 | 26.9% |
| other | 100 | 22.4% |
| bytes | 80 | 17.9% |
| float long | 46 | 10.3% |
| tuple | 40 | 9.0% |
| big int | 40 | 9.0% |
| bool | 20 | 4.5% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       263629 | 30.3% |
|          hit |       605757 | 69.6% |

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
| specialization.deferred |      4122726 | 10.7% |
| specialization.deopt |         6430 | 0.0% |
|          hit |     34204031 | 88.4% |
|         miss |       339537 | 0.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,050 | 48.7% |
| Failure | 9,545 | 51.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,990 | 20.8% |
| has managed dict | 1,978 | 20.7% |
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
| specialization.deferred |           80 | 0.0% |
|          hit |     13107533 | 100.0% |
|         miss |          840 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,260 | 100.0% |
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
| specialization.deopt |        10025 | 0.1% |
|          hit |      8308296 | 91.9% |
|         miss |       532008 | 5.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 10,945 | 91.8% |
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
| specialization.deferred |         9000 | 1.3% |
|          hit |       697118 | 98.7% |

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
| Basic | 132,166,767 | 49.3% |
| Not specialized | 32,534,742 | 12.1% |
| Specialized | 103,123,893 | 38.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,493 | 100.0% |
| CALL | 4,713,541 | 0.0% |
| LOAD_ATTR | 4,122,726 | 0.0% |
| TO_BOOL | 928,962 | 0.0% |
| BINARY_OP | 819,458 | 0.0% |
| FOR_ITER | 263,629 | 0.0% |
| BINARY_SUBSCR | 252,075 | 0.0% |
| SEND | 252,000 | 0.0% |
| STORE_ATTR | 198,480 | 0.0% |
| STORE_SUBSCR | 180,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 523,309 | 44.7% |
| LOAD_ATTR_SLOT | 222,227 | 19.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 101,034 | 8.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 94,053 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,591 | 5.2% |
| CALL_PY_EXACT_ARGS | 46,923 | 4.0% |
| CALL_METHOD_DESCRIPTOR_O | 27,660 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 21,262 | 1.8% |
| TO_BOOL_NONE | 16,431 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 13,329 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,291,076 | 28.9% |
| Calls to Python functions inlined | 10,539,037 | 71.1% |
| Calls via PyEval_EvalFrame (total) | 4,291,076 | 28.9% |
| Calls via PyEval_EvalFrame (vector) | 4,030,016 | 27.2% |
| Calls via PyEval_EvalFrame (generator) | 261,060 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 4,030,016 | 27.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 814,607 | 5.5% |
| Calls via PyEval_EvalFrame (function ex) | 99,240 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 153,360 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 686,760 | 4.6% |
| Frames pushed | 14,892,962 | 100.4% |
| Frame objects created | 617,669 | 4.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,966,245 | 40.4% |
| Frees to freelist | 8,985,211 |  |
| Allocations | 13,228,158 | 59.6% |
| Allocations to 512 bytes | 12,987,247 | 58.5% |
| Allocations to 4 kbytes | 66,201 | 0.3% |
| Allocations over 4 kbytes | 174,710 | 0.8% |
| Frees | 13,468,207 |  |
| New values | 117,540 |  |
| Interpreter increfs | 132,569,997 | 73.1% |
| Interpreter decrefs | 143,919,350 | 71.1% |
| Increfs | 48,855,058 | 26.9% |
| Decrefs | 58,409,211 | 28.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 18,000 | 15.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,715,799 |  |
| Method cache misses | 250,366 |  |
| Method cache collisions | 267,430 |  |
| Method cache dunder hits | 5,107,032 |  |
| Method cache dunder misses | 18,691 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 845 | 0 | 9,146,836 |
| 1 | 76 | 0 | 2,426,794 |
| 2 | 1 | 33 | 311,580 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 16,400 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 945,532 |  |
| Uops executed | 41,866,408 | 44 |
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
| <= 8 | 178,295 | 18.9% |
| <= 16 | 199,570 | 21.1% |
| <= 32 | 41,265 | 4.4% |
| <= 64 | 93,213 | 9.9% |
| <= 128 | 431,377 | 45.6% |
| <= 256 | 241 | 0.0% |
| <= 512 | 432 | 0.0% |
| <= 1024 | 881 | 0.1% |
| <= 2048 | 236 | 0.0% |
| <= 4096 | 10 | 0.0% |
| <= 8192 | 12 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 11,312,334 | 27.0% | 27.0% |
| LOAD_FAST | 3,977,077 | 9.5% | 36.5% |
| _GUARD_TYPE_VERSION | 3,522,398 | 8.4% | 44.9% |
| _POP_JUMP_IF_TRUE | 1,925,795 | 4.6% | 49.5% |
| STORE_FAST | 1,533,693 | 3.7% | 53.2% |
| _LOAD_ATTR_INSTANCE_VALUE | 1,232,648 | 2.9% | 56.1% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,232,648 | 2.9% | 59.1% |
| _LOAD_ATTR_SLOT | 1,173,548 | 2.8% | 61.9% |
| _EXIT_TRACE | 927,474 | 2.2% | 64.1% |
| TO_BOOL_BOOL | 837,066 | 2.0% | 66.1% |
| _LOAD_ATTR_METHOD_NO_DICT | 835,158 | 2.0% | 68.1% |
| LOAD_CONST | 758,235 | 1.8% | 69.9% |
| _GUARD_GLOBALS_VERSION | 662,602 | 1.6% | 71.5% |
| _SAVE_CURRENT_IP | 512,669 | 1.2% | 72.7% |
| _PUSH_FRAME | 503,669 | 1.2% | 73.9% |
| _INIT_CALL_PY_EXACT_ARGS | 503,669 | 1.2% | 75.1% |
| _CHECK_STACK_SPACE | 503,669 | 1.2% | 76.3% |
| _CHECK_PEP_523 | 503,669 | 1.2% | 77.5% |
| _CHECK_FUNCTION_EXACT_ARGS | 503,669 | 1.2% | 78.7% |
| _ITER_CHECK_LIST | 489,668 | 1.2% | 79.9% |
| _IS_ITER_EXHAUSTED_LIST | 489,668 | 1.2% | 81.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 421,616 | 1.0% | 82.1% |
| LOAD_ATTR | 414,278 | 1.0% | 83.1% |
| RESUME_CHECK | 379,257 | 0.9% | 84.0% |
| _POP_JUMP_IF_FALSE | 379,128 | 0.9% | 84.9% |
| _ITER_CHECK_RANGE | 348,165 | 0.8% | 85.7% |
| _IS_ITER_EXHAUSTED_RANGE | 348,165 | 0.8% | 86.5% |
| _LOAD_GLOBAL_BUILTINS | 345,409 | 0.8% | 87.4% |
| _GUARD_BUILTINS_VERSION | 345,409 | 0.8% | 88.2% |
| _ITER_NEXT_RANGE | 327,356 | 0.8% | 89.0% |
| _LOAD_GLOBAL_MODULE | 317,193 | 0.8% | 89.7% |
| _ITER_NEXT_LIST | 314,126 | 0.8% | 90.5% |
| PUSH_NULL | 290,500 | 0.7% | 91.2% |
| POP_TOP | 277,200 | 0.7% | 91.8% |
| LIST_EXTEND | 273,416 | 0.7% | 92.5% |
| CALL_INTRINSIC_1 | 273,416 | 0.7% | 93.1% |
| BUILD_LIST | 273,416 | 0.7% | 93.8% |
| _GUARD_KEYS_VERSION | 190,122 | 0.5% | 94.3% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 190,122 | 0.5% | 94.7% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 181,122 | 0.4% | 95.1% |
| _JUMP_TO_TOP | 154,945 | 0.4% | 95.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 135,141 | 0.3% | 95.8% |
| _IS_NONE | 124,570 | 0.3% | 96.1% |
| TO_BOOL_INT | 119,523 | 0.3% | 96.4% |
| COMPARE_OP_INT | 110,929 | 0.3% | 96.7% |
| CALL_ISINSTANCE | 108,000 | 0.3% | 96.9% |
| CALL_LEN | 92,809 | 0.2% | 97.2% |
| TO_BOOL | 91,648 | 0.2% | 97.4% |
| CONTAINS_OP | 81,000 | 0.2% | 97.6% |
| BINARY_OP | 79,127 | 0.2% | 97.8% |
| COPY | 67,680 | 0.2% | 97.9% |
| BINARY_SUBSCR | 63,000 | 0.2% | 98.1% |
| _STORE_ATTR_INSTANCE_VALUE | 60,584 | 0.1% | 98.2% |
| _GUARD_DORV_VALUES | 60,584 | 0.1% | 98.4% |
| SWAP | 59,251 | 0.1% | 98.5% |
| _ITER_CHECK_TUPLE | 45,420 | 0.1% | 98.6% |
| _IS_ITER_EXHAUSTED_TUPLE | 45,420 | 0.1% | 98.7% |
| BUILD_TUPLE | 43,568 | 0.1% | 98.8% |
| LOAD_FAST_CHECK | 42,600 | 0.1% | 98.9% |
| CALL_METHOD_DESCRIPTOR_O | 42,600 | 0.1% | 99.0% |
| _LOAD_ATTR_MODULE | 42,031 | 0.1% | 99.1% |
| _CHECK_ATTR_MODULE | 42,031 | 0.1% | 99.2% |
| CALL_BUILTIN_FAST | 36,600 | 0.1% | 99.3% |
| _ITER_NEXT_TUPLE | 36,300 | 0.1% | 99.4% |
| TO_BOOL_NONE | 36,000 | 0.1% | 99.5% |
| BINARY_SUBSCR_LIST_INT | 32,294 | 0.1% | 99.6% |
| _STORE_ATTR_SLOT | 30,338 | 0.1% | 99.6% |
| LOAD_DEREF | 26,940 | 0.1% | 99.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 24,047 | 0.1% | 99.8% |
| TO_BOOL_LIST | 23,366 | 0.1% | 99.8% |
| _GUARD_BOTH_INT | 17,084 | 0.0% | 99.9% |
| _BINARY_OP_SUBTRACT_INT | 17,084 | 0.0% | 99.9% |
| CALL_BUILTIN_O | 17,084 | 0.0% | 99.9% |
| _POP_FRAME | 9,000 | 0.0% | 100.0% |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 9,000 | 0.0% | 100.0% |
| COMPARE_OP_FLOAT | 6,568 | 0.0% | 100.0% |
| _LOAD_ATTR_CLASS | 900 | 0.0% | 100.0% |
| _CHECK_ATTR_CLASS | 900 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
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
Stats gathered on: 2023-10-04
