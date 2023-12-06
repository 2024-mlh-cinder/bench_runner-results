
# Pystats results

- benchmark: tornado_http
- fork: python
- ref: main
- commit hash: 6c23635
- commit date: 2023-10-21T22:18:34+03:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 59,308,622 | 20.7% | 20.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 20,083,306 | 7.0% | 27.8% | 0.1% |
| RESUME_CHECK | 15,075,821 | 5.3% | 33.0% | 0.0% |
| LOAD_CONST | 12,702,007 | 4.4% | 37.5% |  |
| POP_JUMP_IF_FALSE | 11,426,805 | 4.0% | 41.5% |  |
| STORE_FAST | 9,324,959 | 3.3% | 44.7% |  |
| RETURN_VALUE | 8,673,596 | 3.0% | 47.8% |  |
| CALL_PY_EXACT_ARGS | 8,648,536 | 3.0% | 50.8% | 0.5% |
| LOAD_GLOBAL_MODULE | 8,230,979 | 2.9% | 53.7% | 0.0% |
| LOAD_FAST_LOAD_FAST | 7,757,195 | 2.7% | 56.4% |  |
| POP_TOP | 7,650,090 | 2.7% | 59.1% |  |
| TO_BOOL_BOOL | 7,375,856 | 2.6% | 61.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,740,129 | 2.4% | 64.0% | 0.9% |
| STORE_ATTR_INSTANCE_VALUE | 6,146,467 | 2.1% | 66.1% | 0.1% |
| RETURN_CONST | 5,914,926 | 2.1% | 68.2% |  |
| LOAD_GLOBAL_BUILTIN | 5,544,215 | 1.9% | 70.1% | 0.0% |
| CALL | 4,720,769 | 1.7% | 71.8% |  |
| LOAD_ATTR | 4,544,977 | 1.6% | 73.4% |  |
| INTERPRETER_EXIT | 4,281,433 | 1.5% | 74.9% |  |
| POP_JUMP_IF_NONE | 4,123,308 | 1.4% | 76.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,079,313 | 1.4% | 77.7% | 0.5% |
| POP_JUMP_IF_TRUE | 3,340,375 | 1.2% | 78.9% |  |
| LOAD_ATTR_SLOT | 3,229,695 | 1.1% | 80.0% | 6.8% |
| STORE_ATTR_SLOT | 2,733,130 | 1.0% | 81.0% | 18.6% |
| PUSH_NULL | 2,695,609 | 0.9% | 81.9% |  |
| COMPARE_OP_INT | 2,655,863 | 0.9% | 82.9% | 0.0% |
| NOP | 2,654,635 | 0.9% | 83.8% |  |
| LOAD_ATTR_MODULE | 2,349,188 | 0.8% | 84.6% |  |
| COPY | 1,862,060 | 0.7% | 85.3% |  |
| CALL_ISINSTANCE | 1,669,023 | 0.6% | 85.9% |  |
| LOAD_DEREF | 1,586,307 | 0.6% | 86.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,554,599 | 0.5% | 87.0% | 6.0% |
| JUMP_BACKWARD | 1,378,062 | 0.5% | 87.4% |  |
| POP_JUMP_IF_NOT_NONE | 1,292,871 | 0.5% | 87.9% |  |
| CALL_BUILTIN_FAST | 1,276,080 | 0.4% | 88.3% |  |
| SWAP | 1,091,714 | 0.4% | 88.7% |  |
| TO_BOOL_NONE | 1,090,170 | 0.4% | 89.1% | 1.8% |
| BUILD_TUPLE | 1,077,743 | 0.4% | 89.5% |  |
| TO_BOOL | 1,021,005 | 0.4% | 89.8% |  |
| BUILD_LIST | 934,194 | 0.3% | 90.2% |  |
| BINARY_OP | 896,737 | 0.3% | 90.5% |  |
| STORE_FAST_STORE_FAST | 856,791 | 0.3% | 90.8% |  |
| CALL_LEN | 832,202 | 0.3% | 91.1% |  |
| BINARY_OP_ADD_INT | 811,931 | 0.3% | 91.3% |  |
| CALL_FUNCTION_EX | 807,176 | 0.3% | 91.6% |  |
| FOR_ITER_LIST | 799,058 | 0.3% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 792,697 | 0.3% | 92.2% | 3.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 740,604 | 0.3% | 92.4% |  |
| TO_BOOL_INT | 707,942 | 0.2% | 92.7% | 0.6% |
| BINARY_SUBSCR_DICT | 676,659 | 0.2% | 92.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 676,491 | 0.2% | 93.2% |  |
| CONTAINS_OP | 676,320 | 0.2% | 93.4% |  |
| BINARY_OP_SUBTRACT_INT | 645,639 | 0.2% | 93.6% |  |
| JUMP_FORWARD | 623,512 | 0.2% | 93.8% |  |
| BUILD_MAP | 593,580 | 0.2% | 94.1% |  |
| GET_ITER | 588,915 | 0.2% | 94.3% |  |
| COPY_FREE_VARS | 581,301 | 0.2% | 94.5% |  |
| LOAD_ATTR_WITH_HINT | 575,640 | 0.2% | 94.7% | 2.2% |
| LOAD_ATTR_CLASS | 550,200 | 0.2% | 94.9% | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 534,522 | 0.2% | 95.0% |  |
| LIST_EXTEND | 507,285 | 0.2% | 95.2% |  |
| CALL_INTRINSIC_1 | 498,285 | 0.2% | 95.4% |  |
| YIELD_VALUE | 432,000 | 0.2% | 95.5% |  |
| CALL_PY_WITH_DEFAULTS | 426,191 | 0.1% | 95.7% |  |
| IS_OP | 423,720 | 0.1% | 95.8% |  |
| STORE_SUBSCR_DICT | 423,360 | 0.1% | 96.0% |  |
| BINARY_SLICE | 414,660 | 0.1% | 96.1% |  |
| FOR_ITER_RANGE | 369,186 | 0.1% | 96.3% |  |
| BINARY_SUBSCR_GETITEM | 369,180 | 0.1% | 96.4% |  |
| DICT_MERGE | 359,220 | 0.1% | 96.5% |  |
| CALL_KW | 344,951 | 0.1% | 96.6% |  |
| GET_AWAITABLE | 342,000 | 0.1% | 96.8% |  |
| PUSH_EXC_INFO | 338,495 | 0.1% | 96.9% |  |
| POP_EXCEPT | 338,495 | 0.1% | 97.0% |  |
| END_SEND | 333,000 | 0.1% | 97.1% |  |
| CHECK_EXC_MATCH | 330,920 | 0.1% | 97.2% |  |
| BINARY_SUBSCR | 316,011 | 0.1% | 97.3% |  |
| MAKE_CELL | 303,123 | 0.1% | 97.4% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 288,240 | 0.1% | 97.5% | 3.1% |
| MAKE_FUNCTION | 271,478 | 0.1% | 97.6% |  |
| COMPARE_OP_FLOAT | 270,618 | 0.1% | 97.7% |  |
| FOR_ITER | 263,843 | 0.1% | 97.8% |  |
| SEND | 252,400 | 0.1% | 97.9% |  |
| RETURN_GENERATOR | 252,060 | 0.1% | 98.0% |  |
| EXIT_INIT_CHECK | 243,240 | 0.1% | 98.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 243,240 | 0.1% | 98.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 220,557 | 0.1% | 98.3% | 45.6% |
| TO_BOOL_STR | 216,740 | 0.1% | 98.3% | 3.5% |
| SEND_GEN | 216,000 | 0.1% | 98.4% |  |
| COMPARE_OP_STR | 207,420 | 0.1% | 98.5% |  |
| FOR_ITER_GEN | 207,000 | 0.1% | 98.5% |  |
| STORE_ATTR | 200,420 | 0.1% | 98.6% |  |
| CALL_LIST_APPEND | 191,038 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 180,580 | 0.1% | 98.7% |  |
| BEFORE_WITH | 173,591 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 171,360 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 171,060 | 0.1% | 98.9% |  |
| STORE_FAST_LOAD_FAST | 162,000 | 0.1% | 99.0% |  |
| SET_FUNCTION_ATTRIBUTE | 156,299 | 0.1% | 99.0% |  |
| DELETE_FAST | 155,531 | 0.1% | 99.1% |  |
| EXTENDED_ARG | 153,180 | 0.1% | 99.1% |  |
| CALL_TYPE_1 | 153,180 | 0.1% | 99.2% |  |
| LOAD_SUPER_ATTR_METHOD | 143,820 | 0.1% | 99.3% |  |
| COMPARE_OP | 135,438 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 127,767 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 126,000 | 0.0% | 99.4% |  |
| FOR_ITER_TUPLE | 108,660 | 0.0% | 99.4% |  |
| CALL_BUILTIN_CLASS | 103,881 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 91,662 | 0.0% | 99.5% |  |
| STORE_DEREF | 90,360 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_ATTR | 90,060 | 0.0% | 99.6% |  |
| DELETE_SUBSCR | 90,060 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 90,000 | 0.0% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 90,000 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 83,852 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 81,120 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 72,000 | 0.0% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 69,891 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 63,180 | 0.0% | 99.8% |  |
| CALL_BUILTIN_O | 59,517 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 54,060 | 0.0% | 99.8% |  |
| RERAISE | 54,000 | 0.0% | 99.8% |  |
| BUILD_SLICE | 54,000 | 0.0% | 99.9% |  |
| UNARY_INVERT | 45,120 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 45,120 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 45,120 | 0.0% | 99.9% |  |
| END_FOR | 45,000 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 44,880 | 0.0% | 99.9% | 9.4% |
| TO_BOOL_ALWAYS_TRUE | 36,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 19,761 | 0.0% | 100.0% |  |
| BUILD_STRING | 18,060 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 18,000 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 18,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 9,895 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 9,060 | 0.0% | 100.0% |  |
| UNARY_NOT | 9,000 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,000 | 0.0% | 100.0% |  |
| BUILD_SET | 9,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 9,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,262 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,478,083 | 6.1% | 6.1% |
| RESUME_CHECK LOAD_FAST | 8,588,733 | 3.0% | 9.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,112,116 | 2.8% | 12.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,292,796 | 2.2% | 14.2% |
| STORE_FAST LOAD_FAST | 5,948,836 | 2.1% | 16.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,515,936 | 1.9% | 18.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,607,052 | 1.6% | 19.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,084,826 | 1.4% | 21.2% |
| LOAD_CONST LOAD_FAST | 4,029,072 | 1.4% | 22.6% |
| CACHE RESUME_CHECK | 4,026,031 | 1.4% | 24.0% |
| RETURN_CONST POP_TOP | 3,908,835 | 1.4% | 25.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,750,130 | 1.3% | 26.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 3,418,407 | 1.2% | 27.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,373,723 | 1.2% | 29.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,178,222 | 1.1% | 30.2% |
| LOAD_FAST LOAD_ATTR_SLOT | 3,092,079 | 1.1% | 31.3% |
| POP_TOP LOAD_FAST | 2,939,094 | 1.0% | 32.3% |
| LOAD_FAST LOAD_ATTR | 2,821,035 | 1.0% | 33.3% |
| RETURN_VALUE INTERPRETER_EXIT | 2,796,946 | 1.0% | 34.3% |
| LOAD_FAST LOAD_CONST | 2,595,181 | 0.9% | 35.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,593,670 | 0.9% | 36.1% |
| LOAD_FAST RETURN_VALUE | 2,374,224 | 0.8% | 36.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,339,590 | 0.8% | 37.7% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 2,276,240 | 0.8% | 38.5% |
| POP_TOP RETURN_CONST | 2,212,848 | 0.8% | 39.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,134,018 | 0.7% | 40.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,130,124 | 0.7% | 40.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,109,551 | 0.7% | 41.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,106,556 | 0.7% | 42.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,086,402 | 0.7% | 43.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,026,041 | 0.7% | 43.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,994,108 | 0.7% | 44.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,760,920 | 0.6% | 45.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,747,860 | 0.6% | 45.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,733,633 | 0.6% | 46.2% |
| RETURN_VALUE STORE_FAST | 1,598,943 | 0.6% | 46.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,594,848 | 0.6% | 47.3% |
| NOP LOAD_FAST | 1,593,769 | 0.6% | 47.9% |
| LOAD_FAST CALL | 1,531,000 | 0.5% | 48.4% |
| CALL STORE_FAST | 1,530,637 | 0.5% | 49.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,515,703 | 0.5% | 49.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,495,787 | 0.5% | 50.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,471,491 | 0.5% | 50.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,465,223 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,450,715 | 0.5% | 51.6% |
| RETURN_VALUE TO_BOOL_BOOL | 1,422,401 | 0.5% | 52.0% |
| LOAD_FAST STORE_ATTR_SLOT | 1,377,783 | 0.5% | 52.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,355,481 | 0.5% | 53.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,345,764 | 0.5% | 53.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,314,849 | 0.5% | 53.9% |
| PUSH_NULL LOAD_FAST | 1,307,406 | 0.5% | 54.4% |
| LOAD_CONST COMPARE_OP_INT | 1,306,358 | 0.5% | 54.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,278,909 | 0.4% | 55.3% |
| RETURN_CONST INTERPRETER_EXIT | 1,277,427 | 0.4% | 55.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,254,151 | 0.4% | 56.2% |
| RESUME_CHECK NOP | 1,205,991 | 0.4% | 56.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,111,359 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,024,276 | 0.4% | 57.4% |
| LOAD_CONST STORE_FAST | 998,579 | 0.3% | 57.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 976,023 | 0.3% | 58.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 909,995 | 0.3% | 58.4% |
| LOAD_ATTR LOAD_FAST | 901,554 | 0.3% | 58.7% |
| LOAD_CONST LOAD_CONST | 891,894 | 0.3% | 59.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 885,083 | 0.3% | 59.3% |
| LOAD_FAST COPY | 854,690 | 0.3% | 59.6% |
| TO_BOOL POP_JUMP_IF_FALSE | 849,884 | 0.3% | 59.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 838,235 | 0.3% | 60.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 832,911 | 0.3% | 60.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 818,460 | 0.3% | 60.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 797,936 | 0.3% | 61.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 791,757 | 0.3% | 61.3% |
| STORE_ATTR_SLOT LOAD_CONST | 784,602 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 783,260 | 0.3% | 61.9% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 779,276 | 0.3% | 62.1% |
| LOAD_ATTR PUSH_NULL | 771,149 | 0.3% | 62.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 769,280 | 0.3% | 62.7% |
| BUILD_LIST LOAD_FAST | 768,465 | 0.3% | 62.9% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 756,180 | 0.3% | 63.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 751,768 | 0.3% | 63.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 748,140 | 0.3% | 63.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 738,260 | 0.3% | 64.0% |
| CALL POP_TOP | 738,024 | 0.3% | 64.3% |
| RETURN_VALUE RETURN_VALUE | 729,180 | 0.3% | 64.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 724,082 | 0.3% | 64.8% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 710,510 | 0.2% | 65.0% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 710,510 | 0.2% | 65.3% |
| POP_TOP JUMP_BACKWARD | 690,708 | 0.2% | 65.5% |
| POP_TOP LOAD_CONST | 684,938 | 0.2% | 65.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 675,360 | 0.2% | 66.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 667,371 | 0.2% | 66.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 667,080 | 0.2% | 66.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 662,085 | 0.2% | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 651,611 | 0.2% | 66.9% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 640,962 | 0.2% | 67.1% |
| LOAD_FAST CALL_BUILTIN_FAST | 628,560 | 0.2% | 67.3% |
| CALL LOAD_FAST | 627,356 | 0.2% | 67.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 621,097 | 0.2% | 67.8% |
| CALL_BUILTIN_FAST STORE_FAST | 611,220 | 0.2% | 68.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 607,735 | 0.2% | 68.2% |
| STORE_FAST LOAD_CONST | 598,715 | 0.2% | 68.4% |


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
| RESUME_CHECK | 4,026,031 | 93.8% |
| COPY_FREE_VARS | 174,342 | 4.1% |
| POP_TOP | 72,060 | 1.7% |
| RETURN_GENERATOR | 9,000 | 0.2% |
| MAKE_CELL | 9,000 | 0.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 83,471 | 48.1% |
| RETURN_VALUE | 81,000 | 46.7% |
| LOAD_GLOBAL_MODULE | 9,120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 173,591 | 100.0% |


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
| LOAD_CONST | 315,371 | 99.8% |
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
| LOAD_GLOBAL_BUILTIN | 292,389 | 88.4% |
| BUILD_TUPLE | 18,060 | 5.5% |
| LOAD_ATTR_MODULE | 11,471 | 3.5% |
| LOAD_GLOBAL_MODULE | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 330,920 | 100.0% |


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
| LOAD_FAST | 241,647 | 41.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 108,180 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,267 | 12.3% |
| LOAD_ATTR | 54,000 | 9.2% |
| BINARY_SLICE | 27,180 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 303,471 | 51.5% |
| FOR_ITER | 109,803 | 18.6% |
| FOR_ITER_TUPLE | 54,180 | 9.2% |
| CALL_PY_EXACT_ARGS | 54,000 | 9.2% |
| LOAD_FAST_AND_CLEAR | 36,060 | 6.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,796,946 | 65.3% |
| RETURN_CONST | 1,277,427 | 29.8% |
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
| LOAD_CONST | 271,478 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 118,418 | 43.6% |
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
| RESUME_CHECK | 1,205,991 | 45.4% |
| POP_JUMP_IF_FALSE | 344,940 | 13.0% |
| STORE_FAST | 334,298 | 12.6% |
| STORE_ATTR_INSTANCE_VALUE | 271,701 | 10.2% |
| POP_JUMP_IF_TRUE | 206,357 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,593,769 | 60.0% |
| LOAD_GLOBAL_MODULE | 442,060 | 16.7% |
| LOAD_FAST_LOAD_FAST | 225,000 | 8.5% |
| LOAD_DEREF | 109,599 | 4.1% |
| NOP | 91,425 | 3.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 245,964 | 72.7% |
| SWAP | 45,000 | 13.3% |
| COPY | 27,000 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 9,060 | 2.7% |
| STORE_SUBSCR_DICT | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 217,545 | 64.3% |
| RETURN_VALUE | 45,000 | 13.3% |
| RERAISE | 27,000 | 8.0% |
| DELETE_FAST | 18,000 | 5.3% |
| JUMP_BACKWARD | 11,471 | 3.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,908,835 | 51.1% |
| CALL | 738,024 | 9.6% |
| CALL_METHOD_DESCRIPTOR_O | 621,097 | 8.1% |
| POP_JUMP_IF_FALSE | 458,339 | 6.0% |
| CALL_FUNCTION_EX | 374,025 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,939,094 | 38.4% |
| RETURN_CONST | 2,212,848 | 28.9% |
| JUMP_BACKWARD | 690,708 | 9.0% |
| LOAD_CONST | 684,938 | 9.0% |
| RESUME_CHECK | 252,060 | 3.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 261,120 | 77.1% |
| RERAISE | 27,000 | 8.0% |
| CALL | 21,896 | 6.5% |
| CALL_METHOD_DESCRIPTOR_O | 18,060 | 5.3% |
| RAISE_VARARGS | 9,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300,024 | 88.6% |
| LOAD_GLOBAL_MODULE | 29,471 | 8.7% |
| LOAD_FAST | 9,000 | 2.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,278,909 | 47.4% |
| LOAD_ATTR | 771,149 | 28.6% |
| LOAD_FAST | 348,131 | 12.9% |
| LOAD_DEREF | 153,240 | 5.7% |
| RETURN_VALUE | 99,060 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,307,406 | 48.5% |
| CALL | 546,862 | 20.3% |
| LOAD_FAST_LOAD_FAST | 533,400 | 19.8% |
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
| LOAD_FAST | 2,374,224 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,026,041 | 23.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 466,920 | 5.4% |
| CALL | 463,801 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,796,946 | 32.2% |
| STORE_FAST | 1,598,943 | 18.4% |
| TO_BOOL_BOOL | 1,422,401 | 16.4% |
| RETURN_VALUE | 729,180 | 8.4% |
| LOAD_FAST | 452,262 | 5.2% |


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
| LOAD_ATTR_INSTANCE_VALUE | 452,978 | 44.4% |
| LOAD_FAST | 440,274 | 43.1% |
| LOAD_ATTR | 90,146 | 8.8% |
| COPY | 26,420 | 2.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,100 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 849,884 | 83.2% |
| POP_JUMP_IF_TRUE | 168,669 | 16.5% |
| TO_BOOL | 1,532 | 0.2% |
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
| LOAD_GLOBAL_MODULE | 170,712 | 19.0% |
| LOAD_CONST | 126,979 | 14.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 117,000 | 13.0% |
| LOAD_FAST | 84,927 | 9.5% |
| LOAD_ATTR_MODULE | 77,688 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 239,868 | 26.7% |
| STORE_FAST | 163,421 | 18.2% |
| COPY | 131,808 | 14.7% |
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
| LOAD_ATTR_SLOT | 283,725 | 30.4% |
| STORE_FAST | 83,862 | 9.0% |
| LOAD_FAST_LOAD_FAST | 80,460 | 8.6% |
| RESUME_CHECK | 54,180 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 768,465 | 82.3% |
| STORE_FAST | 102,309 | 11.0% |
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
| LOAD_FAST | 382,182 | 35.5% |
| LOAD_FAST_LOAD_FAST | 288,240 | 26.7% |
| LOAD_GLOBAL_BUILTIN | 153,300 | 14.2% |
| LOAD_GLOBAL_MODULE | 72,180 | 6.7% |
| LOAD_ATTR_MODULE | 54,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 153,300 | 14.2% |
| CALL_METHOD_DESCRIPTOR_O | 144,000 | 13.4% |
| RETURN_VALUE | 135,360 | 12.6% |
| LOAD_CONST | 118,418 | 11.0% |
| CONTAINS_OP | 90,060 | 8.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,531,000 | 32.4% |
| PUSH_NULL | 546,862 | 11.6% |
| LOAD_CONST | 516,182 | 10.9% |
| LOAD_ATTR_INSTANCE_VALUE | 459,160 | 9.7% |
| LOAD_GLOBAL_MODULE | 442,968 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,530,637 | 32.4% |
| POP_TOP | 738,024 | 15.6% |
| LOAD_FAST | 627,356 | 13.3% |
| RETURN_VALUE | 463,801 | 9.8% |
| BINARY_SUBSCR_DICT | 315,060 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 359,220 | 44.5% |
| CALL_INTRINSIC_1 | 328,965 | 40.8% |
| LOAD_FAST | 74,531 | 9.2% |
| BUILD_MAP | 44,400 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 374,025 | 46.3% |
| RETURN_VALUE | 163,931 | 20.3% |
| RESUME_CHECK | 99,060 | 12.3% |
| STORE_FAST | 89,520 | 11.1% |
| CALL | 62,460 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 489,285 | 98.2% |
| RERAISE | 9,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 328,965 | 66.0% |
| BUILD_MAP | 115,920 | 23.3% |
| LOAD_CONST | 44,400 | 8.9% |
| RERAISE | 9,000 | 1.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 344,951 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 198,180 | 57.5% |
| STORE_FAST | 74,471 | 21.6% |
| COPY_FREE_VARS | 18,000 | 5.2% |
| LOAD_FAST | 9,120 | 2.6% |
| RETURN_VALUE | 9,060 | 2.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 88,651 | 65.5% |
| LOAD_ATTR | 18,000 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 6.7% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.6% |
| LOAD_ATTR_CLASS | 9,000 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 89,659 | 66.2% |
| POP_JUMP_IF_TRUE | 45,000 | 33.2% |
| COMPARE_OP | 592 | 0.4% |
| COMPARE_OP_INT | 107 | 0.1% |
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
| LOAD_FAST | 854,690 | 45.9% |
| LOAD_CONST | 189,060 | 10.2% |
| STORE_ATTR_INSTANCE_VALUE | 171,000 | 9.2% |
| BINARY_OP | 131,808 | 7.1% |
| SWAP | 99,180 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 710,510 | 38.2% |
| LOAD_FAST | 342,000 | 18.4% |
| TO_BOOL_BOOL | 243,000 | 13.1% |
| TO_BOOL_INT | 152,874 | 8.2% |
| TO_BOOL_NONE | 143,956 | 7.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 216,268 | 37.2% |
| CACHE | 174,342 | 30.0% |
| CALL | 90,120 | 15.5% |
| LOAD_ATTR_PROPERTY | 63,000 | 10.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,331 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 545,181 | 93.8% |
| RETURN_GENERATOR | 18,060 | 3.1% |
| MAKE_CELL | 18,060 | 3.1% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 81,000 | 52.1% |
| STORE_ATTR_INSTANCE_VALUE | 18,000 | 11.6% |
| POP_EXCEPT | 18,000 | 11.6% |
| NOP | 18,000 | 11.6% |
| POP_TOP | 11,471 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 81,000 | 52.1% |
| RETURN_CONST | 36,000 | 23.1% |
| LOAD_FAST | 20,471 | 13.2% |
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
| GET_ITER | 109,803 | 41.6% |
| SWAP | 18,000 | 6.8% |
| LOAD_FAST | 18,000 | 6.8% |
| FOR_ITER | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 100,683 | 38.2% |
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
| POP_TOP | 690,708 | 50.1% |
| POP_JUMP_IF_TRUE | 228,264 | 16.6% |
| FOR_ITER_LIST | 81,060 | 5.9% |
| CALL_LIST_APPEND | 73,978 | 5.4% |
| POP_JUMP_IF_FALSE | 73,697 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 486,467 | 35.3% |
| FOR_ITER_RANGE | 346,785 | 25.2% |
| FOR_ITER_GEN | 162,000 | 11.8% |
| LOAD_FAST | 137,287 | 10.0% |
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
| STORE_FAST | 334,864 | 53.7% |
| POP_TOP | 99,060 | 15.9% |
| POP_JUMP_IF_TRUE | 81,000 | 13.0% |
| STORE_ATTR_INSTANCE_VALUE | 36,327 | 5.8% |
| POP_JUMP_IF_FALSE | 18,201 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 422,850 | 67.8% |
| LOAD_CONST | 69,803 | 11.2% |
| LOAD_FAST_LOAD_FAST | 45,000 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 31,599 | 5.1% |
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
| LOAD_ATTR_SLOT | 283,725 | 55.9% |
| LOAD_FAST | 196,440 | 38.7% |
| LOAD_CONST | 18,000 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 1.8% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 489,285 | 96.5% |
| LOAD_FAST | 18,000 | 3.5% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,821,035 | 62.1% |
| LOAD_ATTR_INSTANCE_VALUE | 651,611 | 14.3% |
| LOAD_ATTR_SLOT | 283,725 | 6.2% |
| LOAD_ATTR_WITH_HINT | 252,000 | 5.5% |
| LOAD_GLOBAL_MODULE | 225,718 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 901,554 | 19.8% |
| PUSH_NULL | 771,149 | 17.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 756,180 | 16.6% |
| LOAD_CONST | 360,073 | 7.9% |
| CALL_PY_EXACT_ARGS | 241,104 | 5.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,595,181 | 20.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,254,151 | 9.9% |
| LOAD_CONST | 891,894 | 7.0% |
| POP_JUMP_IF_FALSE | 838,235 | 6.6% |
| STORE_ATTR_SLOT | 784,602 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,029,072 | 31.7% |
| COMPARE_OP_INT | 1,306,358 | 10.3% |
| STORE_FAST | 998,579 | 7.9% |
| LOAD_CONST | 891,894 | 7.0% |
| CALL | 516,182 | 4.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 298,761 | 18.8% |
| RESUME_CHECK | 155,061 | 9.8% |
| POP_JUMP_IF_FALSE | 127,821 | 8.1% |
| NOP | 109,599 | 6.9% |
| POP_JUMP_IF_TRUE | 108,240 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 377,820 | 23.8% |
| LOAD_ATTR_INSTANCE_VALUE | 275,103 | 17.3% |
| PUSH_NULL | 153,240 | 9.7% |
| STORE_ATTR_INSTANCE_VALUE | 117,000 | 7.4% |
| LOAD_ATTR | 111,622 | 7.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,588,733 | 14.5% |
| POP_JUMP_IF_FALSE | 6,292,796 | 10.6% |
| STORE_FAST | 5,948,836 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 4,084,826 | 6.9% |
| LOAD_CONST | 4,029,072 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,478,083 | 29.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,607,052 | 7.8% |
| STORE_ATTR_INSTANCE_VALUE | 3,750,130 | 6.3% |
| LOAD_ATTR_SLOT | 3,092,079 | 5.2% |
| LOAD_ATTR | 2,821,035 | 4.8% |


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
| STORE_ATTR_SLOT | 976,023 | 12.6% |
| LOAD_GLOBAL_MODULE | 818,460 | 10.6% |
| STORE_FAST | 797,936 | 10.3% |
| STORE_ATTR_INSTANCE_VALUE | 748,140 | 9.6% |
| POP_JUMP_IF_FALSE | 675,360 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,495,787 | 19.3% |
| STORE_ATTR_SLOT | 1,345,764 | 17.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,024,276 | 13.2% |
| LOAD_FAST | 662,085 | 8.5% |
| LOAD_FAST_LOAD_FAST | 550,161 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 340 | 15.0% |
| POP_JUMP_IF_FALSE | 291 | 12.9% |
| STORE_FAST | 260 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 180 | 8.0% |
| LOAD_FAST | 131 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,636 | 72.3% |
| LOAD_GLOBAL_BUILTIN | 580 | 25.6% |
| LOAD_ATTR | 33 | 1.5% |
| COMPARE_OP | 13 | 0.6% |


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
| MAKE_CELL | 138,942 | 45.8% |
| CALL_PY_EXACT_ARGS | 119,001 | 39.3% |
| COPY_FREE_VARS | 18,060 | 6.0% |
| CALL_KW | 9,000 | 3.0% |
| CALL | 9,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 155,181 | 51.2% |
| MAKE_CELL | 138,942 | 45.8% |
| RETURN_GENERATOR | 9,000 | 3.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,515,936 | 48.3% |
| COMPARE_OP_INT | 2,106,556 | 18.4% |
| TO_BOOL_NONE | 909,995 | 8.0% |
| TO_BOOL | 849,884 | 7.4% |
| CONTAINS_OP | 450,900 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,292,796 | 55.1% |
| RETURN_CONST | 1,111,359 | 9.7% |
| LOAD_CONST | 838,235 | 7.3% |
| LOAD_GLOBAL_MODULE | 791,757 | 6.9% |
| LOAD_FAST_LOAD_FAST | 675,360 | 5.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,276,240 | 55.2% |
| LOAD_FAST | 1,594,848 | 38.7% |
| LOAD_DEREF | 99,060 | 2.4% |
| LOAD_ATTR | 99,060 | 2.4% |
| LOAD_ATTR_WITH_HINT | 26,800 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,418,407 | 82.9% |
| RETURN_CONST | 209,061 | 5.1% |
| LOAD_GLOBAL_MODULE | 207,140 | 5.0% |
| LOAD_FAST_LOAD_FAST | 108,240 | 2.6% |
| NOP | 99,060 | 2.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 832,911 | 64.4% |
| LOAD_ATTR_INSTANCE_VALUE | 342,000 | 26.5% |
| LOAD_ATTR | 81,360 | 6.3% |
| LOAD_GLOBAL_MODULE | 9,300 | 0.7% |
| RETURN_VALUE | 9,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 483,454 | 37.4% |
| LOAD_FAST_LOAD_FAST | 325,821 | 25.2% |
| LOAD_GLOBAL_MODULE | 258,396 | 20.0% |
| LOAD_CONST | 99,000 | 7.7% |
| LOAD_DEREF | 63,120 | 4.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,760,920 | 52.7% |
| COMPARE_OP_INT | 531,300 | 15.9% |
| TO_BOOL_INT | 257,966 | 7.7% |
| TO_BOOL_STR | 180,360 | 5.4% |
| TO_BOOL_NONE | 179,800 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,465,223 | 43.9% |
| LOAD_GLOBAL_BUILTIN | 369,120 | 11.1% |
| JUMP_BACKWARD | 228,264 | 6.8% |
| LOAD_CONST | 217,414 | 6.5% |
| NOP | 206,357 | 6.2% |


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
| POP_TOP | 2,212,848 | 37.4% |
| POP_JUMP_IF_FALSE | 1,111,359 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 568,901 | 9.6% |
| STORE_ATTR_SLOT | 459,261 | 7.8% |
| STORE_FAST | 295,587 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,908,835 | 66.1% |
| INTERPRETER_EXIT | 1,277,427 | 21.6% |
| EXIT_INIT_CHECK | 243,240 | 4.1% |
| STORE_FAST | 132,536 | 2.2% |
| TO_BOOL_BOOL | 99,007 | 1.7% |


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
| MAKE_FUNCTION | 118,418 | 75.8% |
| SET_FUNCTION_ATTRIBUTE | 37,881 | 24.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,417 | 34.2% |
| SET_FUNCTION_ATTRIBUTE | 37,881 | 24.2% |
| CALL | 28,921 | 18.5% |
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
| RETURN_VALUE | 1,598,943 | 17.1% |
| CALL | 1,530,637 | 16.4% |
| LOAD_CONST | 998,579 | 10.7% |
| CALL_BUILTIN_FAST | 611,220 | 6.6% |
| LOAD_ATTR_INSTANCE_VALUE | 572,333 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,948,836 | 63.8% |
| LOAD_FAST_LOAD_FAST | 797,936 | 8.6% |
| LOAD_CONST | 598,715 | 6.4% |
| LOAD_GLOBAL_BUILTIN | 398,686 | 4.3% |
| JUMP_FORWARD | 334,864 | 3.6% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 667,371 | 77.9% |
| UNPACK_SEQUENCE_LIST | 90,000 | 10.5% |
| UNPACK_SEQUENCE_TUPLE | 54,180 | 6.3% |
| STORE_FAST_STORE_FAST | 18,120 | 2.1% |
| COPY | 18,060 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 469,251 | 54.8% |
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
| BINARY_OP_ADD_INT | 424,871 | 38.9% |
| BINARY_OP_SUBTRACT_INT | 267,639 | 24.5% |
| LOAD_FAST | 144,000 | 13.2% |
| LOAD_ATTR | 65,904 | 6.0% |
| LOAD_FAST_AND_CLEAR | 36,060 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 710,510 | 65.1% |
| COPY | 99,180 | 9.1% |
| STORE_FAST | 92,904 | 8.5% |
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

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,800 | 77.2% |
| LOAD_ATTR_INSTANCE_VALUE | 11,862 | 12.9% |
| LOAD_ATTR | 9,000 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,400 | 58.3% |
| LOAD_GLOBAL_MODULE | 26,400 | 28.8% |
| STORE_FAST | 11,862 | 12.9% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,471 | 62.4% |
| LOAD_FAST_LOAD_FAST | 198,000 | 24.4% |
| CALL_LEN | 63,000 | 7.8% |
| LOAD_CONST | 44,440 | 5.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 424,871 | 52.3% |
| BINARY_SLICE | 234,000 | 28.8% |
| RETURN_VALUE | 54,000 | 6.7% |
| CALL_PY_EXACT_ARGS | 54,000 | 6.7% |
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
| RETURN_VALUE | 9,000 | 91.0% |
| LOAD_CONST | 877 | 8.9% |
| BINARY_OP | 18 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,000 | 91.0% |
| CALL_BUILTIN_O | 877 | 8.9% |
| CALL | 18 | 0.2% |


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
| RETURN_VALUE | 45,277 | 64.8% |
| LOAD_ATTR_WITH_HINT | 9,000 | 12.9% |
| LOAD_ATTR_INSTANCE_VALUE | 9,000 | 12.9% |
| CALL | 6,536 | 9.4% |
| LOAD_FAST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 44,400 | 63.5% |
| RETURN_VALUE | 9,000 | 12.9% |
| LOAD_FAST | 9,000 | 12.9% |
| STORE_FAST | 7,431 | 10.6% |
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
| LOAD_CONST | 42,639 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 267,639 | 41.5% |
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
| LOAD_FAST | 262,479 | 38.8% |
| BUILD_TUPLE | 36,060 | 5.3% |
| LOAD_FAST_LOAD_FAST | 27,000 | 4.0% |
| RETURN_VALUE | 18,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 324,000 | 47.9% |
| PUSH_EXC_INFO | 261,120 | 38.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 28,419 | 4.2% |
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
| LOAD_CONST | 65,694 | 78.3% |
| BINARY_SUBSCR | 9,158 | 10.9% |
| BINARY_OP_SUBTRACT_INT | 9,000 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 34,390 | 41.0% |
| LOAD_FAST | 18,060 | 21.5% |
| STORE_FAST | 11,665 | 13.9% |
| TO_BOOL_BOOL | 10,419 | 12.4% |
| LOAD_CONST | 9,000 | 10.7% |


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
| LOAD_FAST | 64,886 | 29.4% |
| LOAD_FAST_LOAD_FAST | 35,979 | 16.3% |
| CALL_BUILTIN_CLASS | 18,000 | 8.2% |
| BINARY_SLICE | 18,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 118,316 | 53.6% |
| POP_TOP | 81,000 | 36.7% |
| COPY_FREE_VARS | 19,331 | 8.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,580 | 0.7% |
| CALL_PY_EXACT_ARGS | 330 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,022 | 28.9% |
| LOAD_ATTR_INSTANCE_VALUE | 27,120 | 26.1% |
| LOAD_GLOBAL_MODULE | 10,459 | 10.1% |
| LOAD_GLOBAL_BUILTIN | 9,080 | 8.7% |
| RETURN_GENERATOR | 9,000 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,000 | 26.0% |
| GET_ITER | 22,341 | 21.5% |
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
| LOAD_ATTR | 10,701 | 54.2% |
| LOAD_FAST | 9,060 | 45.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,701 | 54.2% |
| STORE_FAST | 9,060 | 45.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,307 | 61.0% |
| LOAD_ATTR_INSTANCE_VALUE | 22,175 | 37.3% |
| BINARY_OP_MULTIPLY_FLOAT | 877 | 1.5% |
| CALL | 78 | 0.1% |
| LOAD_CONST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,175 | 52.4% |
| STORE_SUBSCR_DICT | 18,000 | 30.2% |
| BINARY_SUBSCR_DICT | 9,000 | 15.1% |
| LOAD_CONST | 895 | 1.5% |
| POP_TOP | 387 | 0.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 885,083 | 53.0% |
| LOAD_GLOBAL_BUILTIN | 361,020 | 21.6% |
| LOAD_ATTR_MODULE | 224,400 | 13.4% |
| BUILD_TUPLE | 153,300 | 9.2% |
| LOAD_ATTR | 45,080 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,515,703 | 90.8% |
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
| LOAD_ATTR_INSTANCE_VALUE | 309,662 | 37.2% |
| BINARY_SUBSCR | 9,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 9,000 | 1.1% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 291,320 | 35.0% |
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
| LOAD_FAST | 115,974 | 60.7% |
| BUILD_TUPLE | 56,904 | 29.8% |
| RETURN_VALUE | 18,120 | 9.5% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 90,000 | 47.1% |
| JUMP_BACKWARD | 73,978 | 38.7% |
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
| LOAD_FAST | 38,884 | 5.3% |
| RETURN_VALUE | 18,060 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 466,920 | 63.0% |
| STORE_FAST | 93,024 | 12.6% |
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
| LOAD_FAST_LOAD_FAST | 11,862 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,342 | 37.7% |
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
| LOAD_ATTR_METHOD_NO_DICT | 769,280 | 49.5% |
| LOAD_ATTR | 756,180 | 48.6% |
| LOAD_FAST | 18,060 | 1.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,000 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,779 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 738,260 | 47.5% |
| STORE_FAST | 364,725 | 23.5% |
| POP_TOP | 177,596 | 11.4% |
| GET_ITER | 108,180 | 7.0% |
| LOAD_FAST | 54,180 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 432,037 | 54.5% |
| BUILD_TUPLE | 144,000 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 63,000 | 7.9% |
| LOAD_FAST_CHECK | 54,000 | 6.8% |
| LOAD_CONST | 36,040 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 621,097 | 78.4% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,373,723 | 39.0% |
| LOAD_FAST | 2,593,670 | 30.0% |
| LOAD_FAST_LOAD_FAST | 496,020 | 5.7% |
| LOAD_CONST | 495,160 | 5.7% |
| LOAD_ATTR_METHOD_NO_DICT | 383,644 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,112,116 | 93.8% |
| COPY_FREE_VARS | 216,268 | 2.5% |
| RETURN_GENERATOR | 198,000 | 2.3% |
| MAKE_CELL | 119,001 | 1.4% |
| TO_BOOL_BOOL | 2,268 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 108,000 | 25.3% |
| LOAD_FAST | 99,200 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 92,471 | 21.7% |
| PUSH_NULL | 54,260 | 12.7% |
| LOAD_ATTR | 27,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 417,131 | 97.9% |
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
| LOAD_ATTR_SLOT | 252,642 | 93.4% |
| LOAD_FAST | 11,605 | 4.3% |
| LOAD_GLOBAL_MODULE | 6,371 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 252,642 | 93.4% |
| POP_JUMP_IF_FALSE | 17,976 | 6.6% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,306,358 | 49.2% |
| LOAD_ATTR_INSTANCE_VALUE | 779,276 | 29.3% |
| LOAD_ATTR_CLASS | 288,000 | 10.8% |
| COPY | 99,180 | 3.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 90,000 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,106,556 | 79.3% |
| POP_JUMP_IF_TRUE | 531,300 | 20.0% |
| COPY | 18,000 | 0.7% |
| COMPARE_OP | 7 | 0.0% |


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
| JUMP_BACKWARD | 486,467 | 60.9% |
| GET_ITER | 303,471 | 38.0% |
| SWAP | 9,000 | 1.1% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 435,839 | 54.5% |
| LOAD_FAST | 146,982 | 18.4% |
| JUMP_BACKWARD | 81,060 | 10.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 68,688 | 8.6% |
| RETURN_CONST | 21,042 | 2.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 346,785 | 93.9% |
| GET_ITER | 22,341 | 6.1% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 339,264 | 91.9% |
| LOAD_CONST | 11,862 | 3.2% |
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
| LOAD_FAST | 17,478,083 | 87.0% |
| LOAD_FAST_LOAD_FAST | 1,024,276 | 5.1% |
| COPY | 710,510 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 594,120 | 3.0% |
| LOAD_DEREF | 275,103 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,178,222 | 15.8% |
| POP_JUMP_IF_NONE | 2,276,240 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,086,402 | 10.4% |
| RETURN_VALUE | 2,026,041 | 10.1% |
| TO_BOOL_BOOL | 1,994,108 | 9.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 2,086,402 | 51.1% |
| LOAD_FAST | 1,314,849 | 32.2% |
| BINARY_SLICE | 189,040 | 4.6% |
| LOAD_CONST | 99,040 | 2.4% |
| BINARY_SUBSCR_STR_INT | 81,080 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,450,715 | 35.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 769,280 | 18.9% |
| LOAD_CONST | 724,082 | 17.8% |
| CALL_PY_EXACT_ARGS | 383,644 | 9.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 171,000 | 4.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,607,052 | 68.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,355,481 | 20.1% |
| LOAD_ATTR_SLOT | 441,201 | 6.5% |
| LOAD_DEREF | 92,001 | 1.4% |
| LOAD_FAST_LOAD_FAST | 80,460 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,373,723 | 50.1% |
| LOAD_FAST | 2,134,018 | 31.7% |
| LOAD_FAST_LOAD_FAST | 505,941 | 7.5% |
| LOAD_CONST | 369,060 | 5.5% |
| LOAD_GLOBAL_MODULE | 118,161 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,339,590 | 99.6% |
| LOAD_ATTR_MODULE | 9,000 | 0.4% |
| LOAD_ATTR | 598 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,278,909 | 54.4% |
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
| LOAD_FAST | 3,092,079 | 95.7% |
| BINARY_SUBSCR_TUPLE_INT | 90,060 | 2.8% |
| BINARY_SUBSCR_LIST_INT | 34,390 | 1.1% |
| LOAD_DEREF | 9,000 | 0.3% |
| LOAD_ATTR_SLOT | 4,148 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 640,962 | 19.8% |
| TO_BOOL_BOOL | 576,305 | 17.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 441,201 | 13.7% |
| LOAD_ATTR | 283,725 | 8.8% |
| LIST_EXTEND | 283,725 | 8.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 575,397 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 243 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,000 | 43.8% |
| LOAD_CONST | 72,000 | 12.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,800 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 45,000 | 7.8% |
| RETURN_VALUE | 27,000 | 4.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,130,124 | 38.4% |
| LOAD_FAST | 667,080 | 12.0% |
| POP_JUMP_IF_FALSE | 513,382 | 9.3% |
| STORE_FAST | 398,686 | 7.2% |
| POP_JUMP_IF_TRUE | 369,120 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,084,826 | 73.7% |
| CALL_ISINSTANCE | 361,020 | 6.5% |
| LOAD_DEREF | 298,761 | 5.4% |
| CHECK_EXC_MATCH | 292,389 | 5.3% |
| BUILD_TUPLE | 153,300 | 2.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,733,633 | 21.1% |
| RESUME_CHECK | 1,471,491 | 17.9% |
| POP_JUMP_IF_FALSE | 791,757 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 783,260 | 9.5% |
| STORE_ATTR_INSTANCE_VALUE | 607,735 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,339,590 | 28.4% |
| LOAD_FAST | 1,747,860 | 21.2% |
| CALL_ISINSTANCE | 885,083 | 10.8% |
| LOAD_FAST_LOAD_FAST | 818,460 | 9.9% |
| CALL | 442,968 | 5.4% |


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
| CALL_PY_EXACT_ARGS | 8,112,116 | 53.8% |
| CACHE | 4,026,031 | 26.7% |
| COPY_FREE_VARS | 545,181 | 3.6% |
| CALL_PY_WITH_DEFAULTS | 417,131 | 2.8% |
| BINARY_SUBSCR_GETITEM | 369,180 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,588,733 | 57.0% |
| LOAD_GLOBAL_BUILTIN | 2,130,124 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,471,491 | 9.8% |
| NOP | 1,205,991 | 8.0% |
| LOAD_CONST | 488,301 | 3.2% |


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
| LOAD_FAST | 3,750,130 | 61.0% |
| LOAD_FAST_LOAD_FAST | 1,495,787 | 24.3% |
| SWAP | 710,510 | 11.6% |
| LOAD_DEREF | 117,000 | 1.9% |
| STORE_FAST_LOAD_FAST | 63,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,109,551 | 34.3% |
| LOAD_CONST | 1,254,151 | 20.4% |
| LOAD_FAST_LOAD_FAST | 748,140 | 12.2% |
| LOAD_GLOBAL_MODULE | 607,735 | 9.9% |
| RETURN_CONST | 568,901 | 9.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,377,783 | 50.4% |
| LOAD_FAST_LOAD_FAST | 1,345,764 | 49.2% |
| STORE_ATTR_SLOT | 9,583 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 976,023 | 35.7% |
| LOAD_CONST | 784,602 | 28.7% |
| LOAD_FAST | 481,436 | 17.6% |
| RETURN_CONST | 459,261 | 16.8% |
| JUMP_BACKWARD | 22,225 | 0.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,799 | 79.8% |
| LOAD_FAST_LOAD_FAST | 9,000 | 20.1% |
| STORE_ATTR_INSTANCE_VALUE | 81 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,000 | 80.2% |
| RETURN_CONST | 8,800 | 19.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,994,108 | 27.0% |
| CALL_ISINSTANCE | 1,515,703 | 20.5% |
| RETURN_VALUE | 1,422,401 | 19.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 738,260 | 10.0% |
| LOAD_ATTR_SLOT | 576,305 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,515,936 | 74.8% |
| POP_JUMP_IF_TRUE | 1,760,920 | 23.9% |
| EXTENDED_ARG | 90,000 | 1.2% |
| UNARY_NOT | 9,000 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,120 | 43.2% |
| BINARY_OP | 239,868 | 33.9% |
| COPY | 152,874 | 21.6% |
| LOAD_ATTR | 9,000 | 1.3% |
| TO_BOOL_NONE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 449,892 | 63.5% |
| POP_JUMP_IF_TRUE | 257,966 | 36.4% |
| TO_BOOL_NONE | 84 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 127,629 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| TO_BOOL | 18 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 127,767 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 640,962 | 58.8% |
| COPY | 143,956 | 13.2% |
| LOAD_FAST | 142,484 | 13.1% |
| LOAD_ATTR | 63,000 | 5.8% |
| LOAD_ATTR_INSTANCE_VALUE | 54,120 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 909,995 | 83.5% |
| POP_JUMP_IF_TRUE | 179,800 | 16.5% |
| TO_BOOL | 155 | 0.0% |
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
| BINARY_SUBSCR | 198,000 | 29.3% |
| RETURN_VALUE | 117,240 | 17.3% |
| FOR_ITER | 81,040 | 12.0% |
| YIELD_VALUE | 81,000 | 12.0% |
| FOR_ITER_LIST | 68,688 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 667,371 | 98.7% |
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
| specialization.deferred |       315073 | 18.6% |
|          hit |      1382171 | 81.4% |

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
| specialization.deferred |      1018553 | 9.6% |
| specialization.deopt |          599 | 0.0% |
|          hit |      9523296 | 90.1% |
|         miss |        31179 | 0.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,364 | 44.7% |
| Failure | 1,687 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 577 | 34.2% |
| sequence | 400 | 23.7% |
| float | 240 | 14.2% |
| dict | 160 | 9.5% |
| mapping | 110 | 6.5% |
| tuple | 80 | 4.7% |
| bytearray | 80 | 4.7% |
| set | 40 | 2.4% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       894845 | 33.1% |
|          hit |      1809138 | 66.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 116 | 6.1% |
| Failure | 1,776 | 93.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 750 | 42.2% |
| add other | 280 | 15.8% |
| or | 270 | 15.2% |
| remainder | 200 | 11.3% |
| add different types | 120 | 6.8% |
| multiply different types | 76 | 4.3% |
| true divide other | 40 | 2.3% |
| floor divide | 40 | 2.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4710608 | 21.1% |
| specialization.deopt |         5112 | 0.0% |
|          hit |     17334058 | 77.7% |
|         miss |       268190 | 1.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,243 | 47.4% |
| Failure | 8,030 | 52.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,563 | 19.5% |
| class no vectorcall | 1,360 | 16.9% |
| cfunc noargs | 1,006 | 12.5% |
| meth descr method fastcall keywords | 920 | 11.5% |
| meth descr varargs | 807 | 10.0% |
| cfunc varargs keywords | 560 | 7.0% |
| class mutable | 420 | 5.2% |
| other | 374 | 4.7% |
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
| specialization.deferred |       134659 | 4.1% |
| specialization.deopt |            7 | 0.0% |
|          hit |      3132933 | 95.8% |
|         miss |          968 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 187 | 23.8% |
| Failure | 599 | 76.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 199 | 33.2% |
| different types | 120 | 20.0% |
| other | 100 | 16.7% |
| bytes | 80 | 13.4% |
| tuple | 40 | 6.7% |
| big int | 40 | 6.7% |
| bool | 20 | 3.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       263283 | 15.1% |
|          hit |      1483904 | 84.9% |

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
| specialization.deferred |      4532727 | 10.7% |
| specialization.deopt |         6330 | 0.0% |
|          hit |     37667975 | 88.5% |
|         miss |       335736 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,018 | 48.5% |
| Failure | 9,562 | 51.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 2,012 | 21.0% |
| has managed dict | 1,980 | 20.7% |
| not managed dict | 1,710 | 17.9% |
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
| specialization.deferred |           46 | 0.0% |
|          hit |     13774354 | 100.0% |
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
| specialization.deopt |         9744 | 0.1% |
|          hit |      8406673 | 92.1% |
|         miss |       517804 | 5.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 10,704 | 91.6% |
| Failure | 980 | 8.4% |

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
|          hit |       829671 | 98.9% |

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
| Basic | 139,154,638 | 48.7% |
| Not specialized | 35,675,456 | 12.5% |
| Specialized | 111,155,778 | 38.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,364 | 100.0% |
| CALL | 4,710,608 | 0.0% |
| LOAD_ATTR | 4,532,727 | 0.0% |
| TO_BOOL | 1,018,553 | 0.0% |
| BINARY_OP | 894,845 | 0.0% |
| BINARY_SUBSCR | 315,073 | 0.0% |
| FOR_ITER | 263,283 | 0.0% |
| SEND | 252,000 | 0.0% |
| STORE_ATTR | 198,480 | 0.0% |
| STORE_SUBSCR | 180,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 509,123 | 44.0% |
| LOAD_ATTR_SLOT | 220,315 | 19.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100,579 | 8.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 93,678 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,500 | 5.2% |
| CALL_PY_EXACT_ARGS | 46,273 | 4.0% |
| CALL_METHOD_DESCRIPTOR_O | 27,660 | 2.4% |
| LOAD_ATTR_METHOD_NO_DICT | 19,518 | 1.7% |
| TO_BOOL_NONE | 19,255 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 13,323 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,290,433 | 28.0% |
| Calls to Python functions inlined | 11,037,448 | 72.0% |
| Calls via PyEval_EvalFrame (total) | 4,290,433 | 28.0% |
| Calls via PyEval_EvalFrame (vector) | 4,029,373 | 26.3% |
| Calls via PyEval_EvalFrame (generator) | 261,060 | 1.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 4,029,373 | 26.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 819,762 | 5.3% |
| Calls via PyEval_EvalFrame (function ex) | 99,240 | 0.6% |
| Calls via PyEval_EvalFrame (api) | 153,360 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 686,061 | 4.5% |
| Frames pushed | 14,887,061 | 97.1% |
| Frame objects created | 616,563 | 4.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,941,434 | 40.3% |
| Frees to freelist | 8,960,931 |  |
| Allocations | 13,225,342 | 59.7% |
| Allocations to 512 bytes | 12,985,148 | 58.6% |
| Allocations to 4 kbytes | 66,206 | 0.3% |
| Allocations over 4 kbytes | 173,988 | 0.8% |
| Frees | 13,467,964 |  |
| New values | 117,540 |  |
| Interpreter increfs | 139,561,669 | 77.4% |
| Interpreter decrefs | 150,663,939 | 74.9% |
| Increfs | 40,765,666 | 22.6% |
| Decrefs | 50,541,498 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 18,000 | 15.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,734,489 |  |
| Method cache misses | 210,717 |  |
| Method cache collisions | 226,698 |  |
| Method cache dunder hits | 5,109,354 |  |
| Method cache dunder misses | 17,378 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 983 | 0 | 10,714,616 |
| 1 | 84 | 0 | 2,602,584 |
| 2 | 3 | 99 | 933,434 |


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
Stats gathered on: 2023-10-22
