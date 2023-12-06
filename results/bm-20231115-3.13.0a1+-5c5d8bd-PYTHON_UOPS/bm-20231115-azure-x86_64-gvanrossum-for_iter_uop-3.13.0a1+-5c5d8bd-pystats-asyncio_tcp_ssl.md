
# Pystats results

- benchmark: asyncio_tcp_ssl
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 103,591,419 | 22.2% | 22.2% |  |
| POP_JUMP_IF_FALSE | 26,745,466 | 5.7% | 27.9% |  |
| STORE_FAST | 26,216,479 | 5.6% | 33.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 23,185,830 | 5.0% | 38.5% |  |
| RESUME_CHECK | 21,230,109 | 4.5% | 43.0% | 0.0% |
| TO_BOOL_BOOL | 18,646,623 | 4.0% | 47.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 14,095,751 | 3.0% | 50.0% |  |
| LOAD_CONST | 13,920,234 | 3.0% | 53.0% |  |
| POP_TOP | 13,806,802 | 3.0% | 56.0% |  |
| POP_JUMP_IF_TRUE | 11,187,160 | 2.4% | 58.4% |  |
| LOAD_ATTR | 10,954,818 | 2.3% | 60.7% |  |
| CALL_PY_EXACT_ARGS | 10,819,308 | 2.3% | 63.0% | 0.0% |
| RETURN_VALUE | 10,579,170 | 2.3% | 65.3% |  |
| LOAD_ATTR_WITH_HINT | 10,171,544 | 2.2% | 67.5% |  |
| RETURN_CONST | 10,058,328 | 2.2% | 69.6% |  |
| CALL | 8,850,420 | 1.9% | 71.5% |  |
| ENTER_EXECUTOR | 7,856,269 | 1.7% | 73.2% |  |
| TO_BOOL | 7,521,517 | 1.6% | 74.8% |  |
| LOAD_FAST_LOAD_FAST | 7,439,784 | 1.6% | 76.4% |  |
| POP_JUMP_IF_NONE | 7,405,031 | 1.6% | 78.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,549,011 | 1.4% | 79.4% | 0.0% |
| LOAD_GLOBAL_MODULE | 6,457,077 | 1.4% | 80.8% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 5,451,300 | 1.2% | 81.9% |  |
| CALL_LIST_APPEND | 4,846,147 | 1.0% | 83.0% |  |
| LOAD_FAST_CHECK | 4,800,154 | 1.0% | 84.0% |  |
| STORE_ATTR_SLOT | 4,664,597 | 1.0% | 85.0% | 0.1% |
| COMPARE_OP_INT | 4,662,099 | 1.0% | 86.0% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 4,178,137 | 0.9% | 86.9% | 0.0% |
| LOAD_ATTR_SLOT | 4,133,993 | 0.9% | 87.8% | 0.1% |
| NOP | 3,997,423 | 0.9% | 88.6% |  |
| TO_BOOL_INT | 3,099,229 | 0.7% | 89.3% |  |
| CALL_LEN | 2,968,888 | 0.6% | 89.9% |  |
| LOAD_ATTR_MODULE | 2,397,524 | 0.5% | 90.5% | 0.0% |
| INTERPRETER_EXIT | 2,345,197 | 0.5% | 91.0% |  |
| BINARY_OP | 2,125,000 | 0.5% | 91.4% |  |
| PUSH_NULL | 2,045,063 | 0.4% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,739,233 | 0.4% | 92.2% | 0.0% |
| LOAD_DEREF | 1,652,082 | 0.4% | 92.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,638,964 | 0.4% | 92.9% |  |
| SEND_GEN | 1,637,730 | 0.4% | 93.3% |  |
| POP_JUMP_IF_NOT_NONE | 1,367,431 | 0.3% | 93.6% |  |
| BUILD_TUPLE | 1,357,535 | 0.3% | 93.9% |  |
| JUMP_FORWARD | 1,321,894 | 0.3% | 94.1% |  |
| YIELD_VALUE | 1,308,568 | 0.3% | 94.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 1,308,328 | 0.3% | 94.7% |  |
| TO_BOOL_NONE | 1,305,421 | 0.3% | 95.0% | 0.0% |
| FOR_ITER_LIST | 1,287,951 | 0.3% | 95.3% |  |
| COPY | 1,029,900 | 0.2% | 95.5% |  |
| CALL_FUNCTION_EX | 1,019,075 | 0.2% | 95.7% |  |
| COMPARE_OP | 989,059 | 0.2% | 95.9% |  |
| END_SEND | 987,826 | 0.2% | 96.1% |  |
| GET_AWAITABLE | 987,826 | 0.2% | 96.3% |  |
| GET_ITER | 984,246 | 0.2% | 96.5% |  |
| STORE_FAST_STORE_FAST | 973,627 | 0.2% | 96.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 973,067 | 0.2% | 97.0% |  |
| BUILD_LIST | 968,109 | 0.2% | 97.2% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 700,358 | 0.1% | 97.3% | 0.2% |
| STORE_ATTR_WITH_HINT | 691,080 | 0.1% | 97.5% |  |
| BINARY_SLICE | 688,616 | 0.1% | 97.6% |  |
| BINARY_OP_ADD_INT | 667,364 | 0.1% | 97.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 661,083 | 0.1% | 97.9% |  |
| SEND | 659,604 | 0.1% | 98.0% |  |
| RETURN_GENERATOR | 659,324 | 0.1% | 98.2% |  |
| CONTAINS_OP | 652,164 | 0.1% | 98.3% |  |
| TO_BOOL_LIST | 645,424 | 0.1% | 98.5% |  |
| FOR_ITER_RANGE | 644,804 | 0.1% | 98.6% |  |
| CALL_BUILTIN_CLASS | 384,731 | 0.1% | 98.7% |  |
| SWAP | 350,140 | 0.1% | 98.8% |  |
| COPY_FREE_VARS | 349,970 | 0.1% | 98.8% |  |
| CALL_KW | 341,119 | 0.1% | 98.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 329,479 | 0.1% | 99.0% | 0.1% |
| DELETE_SUBSCR | 328,722 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 323,282 | 0.1% | 99.1% | 0.0% |
| LIST_EXTEND | 322,842 | 0.1% | 99.2% |  |
| CALL_INTRINSIC_1 | 322,782 | 0.1% | 99.3% |  |
| BINARY_OP_ADD_FLOAT | 322,142 | 0.1% | 99.3% |  |
| CHECK_EXC_MATCH | 321,942 | 0.1% | 99.4% |  |
| POP_EXCEPT | 321,942 | 0.1% | 99.5% |  |
| PUSH_EXC_INFO | 321,942 | 0.1% | 99.5% |  |
| MAKE_CELL | 321,920 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 321,822 | 0.1% | 99.7% |  |
| MAKE_FUNCTION | 321,780 | 0.1% | 99.7% |  |
| SET_FUNCTION_ATTRIBUTE | 321,140 | 0.1% | 99.8% |  |
| BINARY_OP_MULTIPLY_INT | 320,962 | 0.1% | 99.9% |  |
| BUILD_SLICE | 320,722 | 0.1% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 53,972 | 0.0% | 100.0% | 0.2% |
| CALL_ISINSTANCE | 28,934 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 17,280 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 16,720 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 16,540 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 13,980 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 13,182 | 0.0% | 100.0% |  |
| MAP_ADD | 12,920 | 0.0% | 100.0% |  |
| STORE_ATTR | 12,580 | 0.0% | 100.0% |  |
| FOR_ITER | 9,820 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 9,777 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 9,377 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 8,700 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 6,531 | 0.0% | 100.0% |  |
| RESUME | 5,620 | 0.0% | 100.0% | 0.4% |
| JUMP_BACKWARD | 5,263 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 3,519 | 0.0% | 100.0% |  |
| IS_OP | 2,280 | 0.0% | 100.0% |  |
| BUILD_MAP | 2,180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 1,780 | 0.0% | 100.0% | 1.1% |
| TO_BOOL_STR | 1,200 | 0.0% | 100.0% | 5.0% |
| CALL_BUILTIN_O | 1,180 | 0.0% | 100.0% | 5.1% |
| STORE_NAME | 1,160 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 1,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,020 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 960 | 0.0% | 100.0% | 2.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 880 | 0.0% | 100.0% | 13.6% |
| UNARY_INVERT | 880 | 0.0% | 100.0% |  |
| STORE_DEREF | 880 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 860 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 820 | 0.0% | 100.0% |  |
| DICT_UPDATE | 760 | 0.0% | 100.0% |  |
| LOAD_NAME | 760 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 760 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 720 | 0.0% | 100.0% | 2.8% |
| EXIT_INIT_CHECK | 700 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 700 | 0.0% | 100.0% |  |
| LIST_APPEND | 680 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 680 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 620 | 0.0% | 100.0% |  |
| BEFORE_WITH | 560 | 0.0% | 100.0% |  |
| UNARY_NOT | 520 | 0.0% | 100.0% |  |
| DICT_MERGE | 460 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 400 | 0.0% | 100.0% | 10.0% |
| BUILD_SET | 400 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 400 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 380 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 360 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 220 | 0.0% | 100.0% | 63.6% |
| IMPORT_NAME | 200 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 200 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 140 | 0.0% | 100.0% |  |
| CALL_STR_1 | 120 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 100 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 100 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 100 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 80 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 80 | 0.0% | 100.0% |  |
| RERAISE | 80 | 0.0% | 100.0% |  |
| IMPORT_FROM | 60 | 0.0% | 100.0% |  |
| STORE_SLICE | 40 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 40 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 40 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 23,161,056 | 5.0% | 5.0% |
| STORE_FAST LOAD_FAST | 17,575,511 | 3.8% | 8.7% |
| RESUME_CHECK LOAD_FAST | 16,507,345 | 3.5% | 12.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 16,277,342 | 3.5% | 15.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 13,604,702 | 2.9% | 18.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 12,318,030 | 2.6% | 21.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,150,989 | 2.2% | 23.5% |
| LOAD_FAST TO_BOOL_BOOL | 9,929,936 | 2.1% | 25.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 8,840,479 | 1.9% | 27.5% |
| RETURN_CONST POP_TOP | 8,365,835 | 1.8% | 29.3% |
| RETURN_VALUE STORE_FAST | 7,784,101 | 1.7% | 30.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 7,467,200 | 1.6% | 32.5% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 7,243,096 | 1.6% | 34.1% |
| TO_BOOL POP_JUMP_IF_TRUE | 7,163,737 | 1.5% | 35.6% |
| LOAD_FAST RETURN_VALUE | 7,120,189 | 1.5% | 37.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 7,080,649 | 1.5% | 38.7% |
| CALL STORE_FAST | 6,817,045 | 1.5% | 40.1% |
| LOAD_FAST TO_BOOL | 6,430,006 | 1.4% | 41.5% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,423,906 | 1.4% | 42.9% |
| LOAD_FAST CALL | 6,107,459 | 1.3% | 44.2% |
| LOAD_FAST LOAD_ATTR | 5,703,621 | 1.2% | 45.4% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 5,451,180 | 1.2% | 46.6% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 5,119,680 | 1.1% | 47.7% |
| LOAD_CONST LOAD_FAST | 4,972,775 | 1.1% | 48.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 4,845,040 | 1.0% | 49.8% |
| POP_TOP RETURN_CONST | 4,694,022 | 1.0% | 50.8% |
| LOAD_CONST STORE_FAST | 4,570,877 | 1.0% | 51.8% |
| LOAD_FAST CALL_LIST_APPEND | 4,479,073 | 1.0% | 52.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_CHECK | 4,478,893 | 1.0% | 53.7% |
| LOAD_FAST_CHECK LOAD_ATTR_METHOD_NO_DICT | 4,478,853 | 1.0% | 54.6% |
| POP_TOP LOAD_FAST | 4,357,378 | 0.9% | 55.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 4,340,297 | 0.9% | 56.5% |
| LOAD_FAST LOAD_ATTR_SLOT | 4,117,442 | 0.9% | 57.4% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 3,922,838 | 0.8% | 58.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 3,921,034 | 0.8% | 59.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,824,190 | 0.8% | 59.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,697,698 | 0.8% | 60.7% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,490,673 | 0.7% | 61.4% |
| NOP LOAD_FAST | 3,335,384 | 0.7% | 62.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 2,640,532 | 0.6% | 62.7% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,637,083 | 0.6% | 63.3% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 2,614,552 | 0.6% | 63.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,405,803 | 0.5% | 64.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,395,044 | 0.5% | 64.8% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,368,841 | 0.5% | 65.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 2,284,831 | 0.5% | 65.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,074,242 | 0.4% | 66.3% |
| LOAD_FAST STORE_ATTR_SLOT | 2,023,445 | 0.4% | 66.7% |
| CACHE RESUME_CHECK | 2,020,798 | 0.4% | 67.2% |
| POP_TOP LOAD_CONST | 1,984,239 | 0.4% | 67.6% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,979,854 | 0.4% | 68.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_WITH_HINT | 1,949,250 | 0.4% | 68.4% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 1,949,130 | 0.4% | 68.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 1,768,409 | 0.4% | 69.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,729,834 | 0.4% | 69.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,703,597 | 0.4% | 69.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,692,390 | 0.4% | 70.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,679,736 | 0.4% | 70.7% |
| LOAD_FAST LOAD_CONST | 1,656,878 | 0.4% | 71.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,629,744 | 0.3% | 71.4% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 1,621,706 | 0.3% | 71.7% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,606,608 | 0.3% | 72.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,387,930 | 0.3% | 72.4% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,378,437 | 0.3% | 72.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,358,455 | 0.3% | 72.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,355,940 | 0.3% | 73.2% |
| RETURN_CONST INTERPRETER_EXIT | 1,353,351 | 0.3% | 73.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,353,237 | 0.3% | 73.8% |
| STORE_FAST RETURN_CONST | 1,339,677 | 0.3% | 74.1% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,330,740 | 0.3% | 74.4% |
| POP_JUMP_IF_FALSE NOP | 1,329,517 | 0.3% | 74.7% |
| STORE_ATTR_SLOT LOAD_CONST | 1,329,173 | 0.3% | 75.0% |
| STORE_FAST JUMP_FORWARD | 1,312,925 | 0.3% | 75.2% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 1,307,848 | 0.3% | 75.5% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 1,305,361 | 0.3% | 75.8% |
| LOAD_CONST COMPARE_OP_INT | 1,304,182 | 0.3% | 76.1% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 1,303,202 | 0.3% | 76.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,301,384 | 0.3% | 76.6% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,124,150 | 0.2% | 76.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,112,644 | 0.2% | 77.1% |
| POP_TOP ENTER_EXECUTOR | 1,077,907 | 0.2% | 77.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,043,469 | 0.2% | 77.6% |
| LOAD_FAST CALL_LEN | 1,040,978 | 0.2% | 77.8% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,040,734 | 0.2% | 78.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,031,232 | 0.2% | 78.2% |
| CALL_FUNCTION_EX POP_TOP | 1,017,975 | 0.2% | 78.5% |
| COPY TO_BOOL_INT | 1,010,420 | 0.2% | 78.7% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,010,380 | 0.2% | 78.9% |
| LOAD_ATTR LOAD_FAST | 996,004 | 0.2% | 79.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 988,702 | 0.2% | 79.3% |
| GET_AWAITABLE LOAD_CONST | 987,826 | 0.2% | 79.5% |
| COMPARE_OP POP_JUMP_IF_FALSE | 985,299 | 0.2% | 79.7% |
| LOAD_ATTR COMPARE_OP | 983,039 | 0.2% | 79.9% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR | 979,764 | 0.2% | 80.2% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 979,426 | 0.2% | 80.4% |
| YIELD_VALUE YIELD_VALUE | 979,346 | 0.2% | 80.6% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 979,046 | 0.2% | 80.8% |
| SEND_GEN RESUME_CHECK | 978,946 | 0.2% | 81.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 972,907 | 0.2% | 81.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 972,227 | 0.2% | 81.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 641,684 | 93.2% |
| LOAD_CONST | 46,772 | 6.8% |
| BINARY_OP_ADD_INT | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 358,337 | 52.0% |
| CALL | 320,742 | 46.6% |
| STORE_FAST | 8,657 | 1.3% |
| LIST_EXTEND | 240 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 200 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,020,798 | 86.2% |
| COPY_FREE_VARS | 322,599 | 13.8% |
| RESUME | 940 | 0.0% |
| POP_TOP | 480 | 0.0% |
| RETURN_GENERATOR | 320 | 0.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 80 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 42.9% |
| RETURN_VALUE | 120 | 21.4% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 21.4% |
| LOAD_GLOBAL | 40 | 7.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 520 | 92.9% |
| STORE_FAST | 40 | 7.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,280 | 95.2% |
| BINARY_SUBSCR | 160 | 1.8% |
| LOAD_FAST | 160 | 1.8% |
| BUILD_SLICE | 60 | 0.7% |
| RETURN_VALUE | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,080 | 93.1% |
| BINARY_SUBSCR | 160 | 1.8% |
| BINARY_SUBSCR_LIST_INT | 100 | 1.2% |
| BINARY_SUBSCR_DICT | 80 | 0.9% |
| LOAD_ATTR | 60 | 0.7% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 321,002 | 99.7% |
| LOAD_GLOBAL_BUILTIN | 680 | 0.2% |
| BUILD_TUPLE | 160 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 321,942 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 320,662 | 97.5% |
| LOAD_CONST | 8,000 | 2.4% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 328,662 | 100.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 337,142 | 34.1% |
| SEND | 328,982 | 33.3% |
| RETURN_VALUE | 321,702 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 666,284 | 67.4% |
| STORE_FAST | 321,142 | 32.5% |
| UNPACK_SEQUENCE | 120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 700 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 653,444 | 66.4% |
| CALL_BUILTIN_CLASS | 322,102 | 32.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,140 | 0.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 180 | 0.0% |
| BINARY_SLICE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 644,604 | 65.5% |
| FOR_ITER_RANGE | 322,022 | 32.7% |
| FOR_ITER | 8,720 | 0.9% |
| FOR_ITER_TUPLE | 8,060 | 0.8% |
| LOAD_FAST_AND_CLEAR | 680 | 0.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,353,351 | 57.7% |
| RETURN_VALUE | 662,224 | 28.2% |
| YIELD_VALUE | 329,222 | 14.0% |
| RETURN_GENERATOR | 400 | 0.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 100 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 321,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 321,140 | 99.8% |
| STORE_NAME | 500 | 0.2% |
| LOAD_CONST | 100 | 0.0% |
| CALL_BUILTIN_FAST | 40 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,329,517 | 33.3% |
| POP_JUMP_IF_TRUE | 650,621 | 16.3% |
| STORE_FAST | 645,785 | 16.2% |
| NOP | 641,865 | 16.1% |
| RESUME_CHECK | 358,752 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,335,384 | 83.4% |
| NOP | 641,865 | 16.1% |
| LOAD_GLOBAL_MODULE | 18,874 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 340 | 0.0% |
| LOAD_CONST | 300 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 321,582 | 99.9% |
| STORE_FAST | 160 | 0.0% |
| SWAP | 100 | 0.0% |
| COPY | 80 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 320,522 | 99.6% |
| RETURN_CONST | 660 | 0.2% |
| JUMP_BACKWARD | 340 | 0.1% |
| RETURN_VALUE | 100 | 0.0% |
| POP_TOP | 80 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,365,835 | 60.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,729,834 | 12.5% |
| CALL_FUNCTION_EX | 1,017,975 | 7.4% |
| POP_JUMP_IF_FALSE | 689,536 | 5.0% |
| END_SEND | 666,284 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,694,022 | 34.0% |
| LOAD_FAST | 4,357,378 | 31.6% |
| LOAD_CONST | 1,984,239 | 14.4% |
| ENTER_EXECUTOR | 1,077,907 | 7.8% |
| RESUME_CHECK | 658,844 | 4.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 320,802 | 99.6% |
| BINARY_SUBSCR_DICT | 520 | 0.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 360 | 0.1% |
| RERAISE | 80 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 320,942 | 99.7% |
| LOAD_GLOBAL_BUILTIN | 720 | 0.2% |
| LOAD_GLOBAL | 280 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,692,390 | 82.8% |
| LOAD_ATTR | 324,542 | 15.9% |
| LOAD_DEREF | 24,231 | 1.2% |
| LOAD_FAST | 3,220 | 0.2% |
| LOAD_NAME | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 717,570 | 35.1% |
| LOAD_FAST_LOAD_FAST | 669,975 | 32.8% |
| CALL | 655,498 | 32.1% |
| LOAD_CONST | 840 | 0.0% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 337,522 | 51.2% |
| ENTER_EXECUTOR | 320,262 | 48.6% |
| CALL_KW | 400 | 0.1% |
| CACHE | 320 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 658,444 | 99.9% |
| INTERPRETER_EXIT | 400 | 0.1% |
| CALL | 200 | 0.0% |
| STORE_FAST | 160 | 0.0% |
| LIST_APPEND | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,120,189 | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,040,734 | 9.8% |
| CALL | 690,516 | 6.5% |
| LOAD_ATTR | 641,403 | 6.1% |
| BINARY_OP_ADD_INT | 337,442 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,784,101 | 73.6% |
| TO_BOOL_BOOL | 694,235 | 6.6% |
| LOAD_FAST | 690,136 | 6.5% |
| INTERPRETER_EXIT | 662,224 | 6.3% |
| POP_TOP | 339,292 | 3.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 240 | 27.9% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 16.3% |
| LOAD_CONST | 120 | 14.0% |
| LOAD_FAST | 120 | 14.0% |
| LOAD_ATTR | 100 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 220 | 25.6% |
| RETURN_CONST | 180 | 20.9% |
| STORE_SUBSCR_DICT | 160 | 18.6% |
| ENTER_EXECUTOR | 80 | 9.3% |
| JUMP_FORWARD | 80 | 9.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,430,006 | 85.5% |
| LOAD_ATTR_INSTANCE_VALUE | 743,468 | 9.9% |
| LOAD_ATTR_WITH_HINT | 336,983 | 4.5% |
| TO_BOOL | 4,760 | 0.1% |
| LOAD_ATTR | 2,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,163,737 | 95.2% |
| POP_JUMP_IF_FALSE | 349,040 | 4.6% |
| TO_BOOL | 4,760 | 0.1% |
| TO_BOOL_BOOL | 2,860 | 0.0% |
| TO_BOOL_INT | 460 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 440 | 50.0% |
| BINARY_OP | 400 | 45.5% |
| LOAD_ATTR | 40 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 880 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 340 | 65.4% |
| TO_BOOL | 80 | 15.4% |
| TO_BOOL_INT | 80 | 15.4% |
| TO_BOOL_LIST | 20 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 260 | 50.0% |
| RETURN_VALUE | 160 | 30.8% |
| STORE_FAST | 80 | 15.4% |
| CALL_PY_EXACT_ARGS | 20 | 3.8% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,010,380 | 47.5% |
| LOAD_ATTR_MODULE | 695,614 | 32.7% |
| LOAD_ATTR | 366,754 | 17.3% |
| POP_JUMP_IF_FALSE | 46,012 | 2.2% |
| BINARY_OP | 2,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 688,838 | 32.4% |
| TO_BOOL_INT | 688,237 | 32.4% |
| STORE_FAST | 368,794 | 17.4% |
| BUILD_TUPLE | 366,594 | 17.3% |
| LOAD_FAST_LOAD_FAST | 7,937 | 0.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 40.0% |
| STORE_FAST | 40 | 40.0% |
| DICT_UPDATE | 20 | 20.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 322,122 | 33.3% |
| LOAD_ATTR_SLOT | 322,002 | 33.3% |
| LOAD_FAST | 321,545 | 33.2% |
| SWAP | 680 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 643,387 | 66.5% |
| LOAD_FAST | 323,322 | 33.4% |
| SWAP | 680 | 0.1% |
| RETURN_VALUE | 240 | 0.0% |
| STORE_DEREF | 160 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_UPDATE | 720 | 33.0% |
| LOAD_FAST | 540 | 24.8% |
| BUILD_TUPLE | 240 | 11.0% |
| STORE_ATTR_INSTANCE_VALUE | 180 | 8.3% |
| STORE_FAST | 120 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 780 | 35.8% |
| EXTENDED_ARG | 580 | 26.6% |
| CALL_FUNCTION_EX | 320 | 14.7% |
| STORE_FAST | 280 | 12.8% |
| LOAD_CONST | 180 | 8.3% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 360 | 90.0% |
| LOAD_ATTR | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 400 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,662 | 100.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 320,662 | 100.0% |
| BINARY_SUBSCR | 60 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 649,304 | 47.8% |
| BINARY_OP | 366,594 | 27.0% |
| LOAD_FAST | 322,220 | 23.7% |
| LOAD_FAST_LOAD_FAST | 9,137 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 9,060 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 649,304 | 47.8% |
| CALL_LIST_APPEND | 366,674 | 27.0% |
| LOAD_CONST | 321,100 | 23.7% |
| CALL_ISINSTANCE | 8,920 | 0.7% |
| CALL_PY_EXACT_ARGS | 8,617 | 0.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,107,459 | 69.0% |
| LOAD_FAST_LOAD_FAST | 660,878 | 7.5% |
| PUSH_NULL | 655,498 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 650,641 | 7.4% |
| LOAD_CONST | 339,639 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,817,045 | 77.0% |
| RETURN_VALUE | 690,516 | 7.8% |
| RESUME_CHECK | 333,036 | 3.8% |
| POP_TOP | 333,002 | 3.8% |
| LOAD_CONST | 320,862 | 3.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 695,633 | 68.3% |
| CALL_INTRINSIC_1 | 322,422 | 31.6% |
| DICT_MERGE | 460 | 0.0% |
| BUILD_MAP | 320 | 0.0% |
| LOAD_FAST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,017,975 | 99.9% |
| STORE_FAST | 360 | 0.0% |
| RESUME_CHECK | 260 | 0.0% |
| GET_AWAITABLE | 160 | 0.0% |
| RETURN_VALUE | 140 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 322,782 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 322,422 | 99.9% |
| LOAD_CONST | 320 | 0.1% |
| BUILD_MAP | 40 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 341,119 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 329,082 | 96.5% |
| COPY_FREE_VARS | 8,017 | 2.4% |
| RESUME_CHECK | 1,280 | 0.4% |
| STORE_FAST | 1,200 | 0.4% |
| POP_TOP | 480 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 983,039 | 99.4% |
| COMPARE_OP | 2,380 | 0.2% |
| LOAD_CONST | 1,400 | 0.1% |
| LOAD_ATTR_MODULE | 940 | 0.1% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 985,299 | 99.6% |
| COMPARE_OP | 2,380 | 0.2% |
| COMPARE_OP_INT | 760 | 0.1% |
| POP_JUMP_IF_TRUE | 420 | 0.0% |
| COMPARE_OP_STR | 80 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 649,304 | 99.6% |
| LOAD_FAST | 900 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 0.1% |
| BUILD_SET | 400 | 0.1% |
| LOAD_GLOBAL_MODULE | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 651,364 | 99.9% |
| POP_JUMP_IF_TRUE | 720 | 0.1% |
| STORE_FAST | 60 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 688,838 | 66.9% |
| CALL_LEN | 321,842 | 31.2% |
| LOAD_FAST | 17,440 | 1.7% |
| SWAP | 720 | 0.1% |
| UNARY_NOT | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,010,420 | 98.1% |
| LOAD_ATTR_WITH_HINT | 16,040 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 840 | 0.1% |
| COMPARE_OP_INT | 600 | 0.1% |
| TO_BOOL | 500 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 322,599 | 92.2% |
| CALL_PY_EXACT_ARGS | 10,177 | 2.9% |
| CALL_KW | 8,017 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 7,997 | 2.3% |
| LOAD_ATTR_PROPERTY | 580 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 349,070 | 99.7% |
| RESUME | 660 | 0.2% |
| RETURN_GENERATOR | 160 | 0.0% |
| MAKE_CELL | 80 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 91.3% |
| CALL | 40 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 460 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 740 | 97.4% |
| BUILD_CONST_KEY_MAP | 20 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 720 | 94.7% |
| EXTENDED_ARG | 20 | 2.6% |
| STORE_NAME | 20 | 2.6% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 4,845,040 | 61.7% |
| POP_TOP | 1,077,907 | 13.7% |
| JUMP_FORWARD | 640,954 | 8.2% |
| POP_JUMP_IF_FALSE | 321,462 | 4.1% |
| POP_JUMP_IF_TRUE | 321,082 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 5,119,680 | 65.2% |
| CALL_FUNCTION_EX | 695,633 | 8.9% |
| FOR_ITER_LIST | 641,367 | 8.2% |
| FOR_ITER_RANGE | 321,782 | 4.1% |
| RESUME_CHECK | 321,462 | 4.1% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 9,480 | 56.7% |
| LOAD_CONST | 5,420 | 32.4% |
| BUILD_MAP | 580 | 3.5% |
| STORE_NAME | 360 | 2.2% |
| PUSH_NULL | 200 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,080 | 96.2% |
| ENTER_EXECUTOR | 220 | 1.3% |
| POP_JUMP_IF_FALSE | 120 | 0.7% |
| FOR_ITER_LIST | 120 | 0.7% |
| JUMP_FORWARD | 60 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,720 | 88.8% |
| JUMP_BACKWARD | 700 | 7.1% |
| FOR_ITER | 260 | 2.6% |
| LOAD_FAST | 80 | 0.8% |
| EXTENDED_ARG | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,420 | 85.7% |
| RETURN_CONST | 480 | 4.9% |
| FOR_ITER_LIST | 280 | 2.9% |
| FOR_ITER | 260 | 2.6% |
| LOAD_FAST | 120 | 1.2% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 658,444 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 320,562 | 32.5% |
| LOAD_FAST | 8,160 | 0.8% |
| RETURN_VALUE | 240 | 0.0% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 987,826 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 40 | 66.7% |
| STORE_FAST | 20 | 33.3% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 40.0% |
| IMPORT_FROM | 60 | 30.0% |
| STORE_NAME | 60 | 30.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 820 | 36.0% |
| LOAD_FAST | 800 | 35.1% |
| LOAD_CONST | 560 | 24.6% |
| LOAD_FAST_LOAD_FAST | 80 | 3.5% |
| LOAD_GLOBAL_BUILTIN | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,600 | 70.2% |
| RETURN_VALUE | 400 | 17.5% |
| LOAD_DEREF | 160 | 7.0% |
| POP_JUMP_IF_TRUE | 120 | 5.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,880 | 35.7% |
| POP_JUMP_IF_FALSE | 903 | 17.2% |
| CALL_LIST_APPEND | 607 | 11.5% |
| STORE_FAST | 580 | 11.0% |
| POP_EXCEPT | 340 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,523 | 28.9% |
| FOR_ITER_LIST | 1,520 | 28.9% |
| FOR_ITER_RANGE | 900 | 17.1% |
| FOR_ITER | 700 | 13.3% |
| FOR_ITER_TUPLE | 360 | 6.8% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,307,848 | 100.0% |
| RESUME | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 979,046 | 74.8% |
| SEND | 329,282 | 25.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,312,925 | 99.3% |
| POP_JUMP_IF_FALSE | 6,391 | 0.5% |
| POP_TOP | 1,217 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 480 | 0.0% |
| STORE_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 640,954 | 48.5% |
| LOAD_FAST | 350,833 | 26.5% |
| LOAD_GLOBAL_BUILTIN | 328,453 | 24.8% |
| LOAD_FAST_LOAD_FAST | 500 | 0.0% |
| NOP | 341 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 560 | 82.4% |
| RETURN_GENERATOR | 80 | 11.8% |
| CALL_BUILTIN_CLASS | 40 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 600 | 88.2% |
| JUMP_BACKWARD | 80 | 11.8% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 322,002 | 99.7% |
| LOAD_FAST | 520 | 0.2% |
| BINARY_SLICE | 240 | 0.1% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 322,782 | 100.0% |
| LOAD_NAME | 60 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,703,621 | 52.1% |
| LOAD_GLOBAL_MODULE | 2,284,831 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,301,384 | 11.9% |
| LOAD_ATTR_WITH_HINT | 979,764 | 8.9% |
| LOAD_ATTR_SLOT | 322,402 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,922,838 | 35.8% |
| LOAD_FAST | 996,004 | 9.1% |
| COMPARE_OP | 983,039 | 9.0% |
| LOAD_GLOBAL_MODULE | 658,225 | 6.0% |
| LOAD_CONST | 651,643 | 5.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,637,083 | 18.9% |
| POP_TOP | 1,984,239 | 14.3% |
| LOAD_FAST | 1,656,878 | 11.9% |
| STORE_ATTR_SLOT | 1,329,173 | 9.5% |
| GET_AWAITABLE | 987,826 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,972,775 | 35.7% |
| STORE_FAST | 4,570,877 | 32.8% |
| COMPARE_OP_INT | 1,304,182 | 9.4% |
| SEND_GEN | 658,224 | 4.7% |
| CALL_PY_EXACT_ARGS | 641,963 | 4.6% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 649,137 | 39.3% |
| STORE_FAST | 328,977 | 19.9% |
| POP_JUMP_IF_FALSE | 321,158 | 19.4% |
| LOAD_CONST | 320,480 | 19.4% |
| LOAD_ATTR | 16,074 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 961,318 | 58.2% |
| LOAD_ATTR | 321,360 | 19.5% |
| STORE_ATTR_WITH_HINT | 320,360 | 19.4% |
| PUSH_NULL | 24,231 | 1.5% |
| LOAD_FAST | 13,036 | 0.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,575,511 | 17.0% |
| RESUME_CHECK | 16,507,345 | 15.9% |
| POP_JUMP_IF_FALSE | 13,604,702 | 13.1% |
| LOAD_ATTR_METHOD_NO_DICT | 12,318,030 | 11.9% |
| POP_JUMP_IF_TRUE | 8,840,479 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 23,161,056 | 22.4% |
| TO_BOOL_BOOL | 9,929,936 | 9.6% |
| LOAD_ATTR_WITH_HINT | 7,243,096 | 7.0% |
| RETURN_VALUE | 7,120,189 | 6.9% |
| TO_BOOL | 6,430,006 | 6.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 680 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,478,893 | 93.3% |
| STORE_FAST | 320,525 | 6.7% |
| LOAD_ATTR_METHOD_NO_DICT | 359 | 0.0% |
| POP_TOP | 240 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,478,853 | 93.3% |
| LOAD_FAST | 320,545 | 6.7% |
| CALL_METHOD_DESCRIPTOR_O | 319 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 240 | 0.0% |
| CALL | 80 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,979,854 | 26.6% |
| STORE_FAST | 1,387,930 | 18.7% |
| POP_JUMP_IF_FALSE | 988,702 | 13.3% |
| LOAD_ATTR_METHOD_NO_DICT | 743,005 | 10.0% |
| PUSH_NULL | 669,975 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 2,640,532 | 35.5% |
| LOAD_ATTR_WITH_HINT | 1,949,250 | 26.2% |
| LOAD_FAST | 1,031,232 | 13.9% |
| CALL | 660,878 | 8.9% |
| LOAD_FAST_LOAD_FAST | 654,481 | 8.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,960 | 14.0% |
| LOAD_ATTR | 1,460 | 10.4% |
| RESUME_CHECK | 1,100 | 7.9% |
| RESUME | 1,080 | 7.7% |
| STORE_FAST | 1,040 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,740 | 33.9% |
| LOAD_ATTR | 3,100 | 22.2% |
| LOAD_GLOBAL_BUILTIN | 2,260 | 16.2% |
| LOAD_FAST | 1,140 | 8.2% |
| CALL | 620 | 4.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 200 | 26.3% |
| STORE_NAME | 120 | 15.8% |
| LOAD_CONST | 100 | 13.2% |
| RESUME | 100 | 13.2% |
| BINARY_OP | 80 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 480 | 63.2% |
| LOAD_ATTR | 140 | 18.4% |
| STORE_NAME | 100 | 13.2% |
| LOAD_NAME | 40 | 5.3% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 980 | 96.1% |
| LOAD_GLOBAL | 20 | 2.0% |
| LOAD_GLOBAL_MODULE | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 440 | 43.1% |
| LOAD_FAST | 200 | 19.6% |
| CALL | 160 | 15.7% |
| LOAD_FAST_LOAD_FAST | 100 | 9.8% |
| LOAD_SUPER_ATTR_ATTR | 60 | 5.9% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 320,600 | 99.6% |
| MAKE_CELL | 880 | 0.3% |
| CALL_KW | 160 | 0.0% |
| CACHE | 80 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,720 | 99.6% |
| MAKE_CELL | 880 | 0.3% |
| RETURN_GENERATOR | 240 | 0.1% |
| RESUME | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 9,480 | 73.4% |
| LOAD_CONST | 2,680 | 20.7% |
| DICT_UPDATE | 740 | 5.7% |
| BUILD_MAP | 20 | 0.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 16,277,342 | 60.9% |
| COMPARE_OP_INT | 4,340,297 | 16.2% |
| TO_BOOL_INT | 1,768,409 | 6.6% |
| TO_BOOL_NONE | 1,305,361 | 4.9% |
| COMPARE_OP | 985,299 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,604,702 | 50.9% |
| LOAD_FAST_CHECK | 4,478,893 | 16.7% |
| LOAD_CONST | 2,637,083 | 9.9% |
| RETURN_CONST | 1,679,736 | 6.3% |
| NOP | 1,329,517 | 5.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,423,906 | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE | 979,426 | 13.2% |
| LOAD_ATTR | 959 | 0.0% |
| LOAD_ATTR_WITH_HINT | 280 | 0.0% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,080,649 | 95.6% |
| LOAD_CONST | 321,122 | 4.3% |
| RETURN_CONST | 1,520 | 0.0% |
| LOAD_GLOBAL_MODULE | 440 | 0.0% |
| LOAD_FAST_LOAD_FAST | 400 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,043,469 | 76.3% |
| LOAD_ATTR_INSTANCE_VALUE | 321,902 | 23.5% |
| LOAD_ATTR_WITH_HINT | 600 | 0.0% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |
| CALL_BUILTIN_FAST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 702,513 | 51.4% |
| LOAD_GLOBAL_MODULE | 331,676 | 24.3% |
| LOAD_FAST_LOAD_FAST | 330,422 | 24.2% |
| RETURN_CONST | 620 | 0.0% |
| LOAD_GLOBAL | 600 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 7,163,737 | 64.0% |
| TO_BOOL_BOOL | 2,368,841 | 21.2% |
| TO_BOOL_INT | 1,330,740 | 11.9% |
| COMPARE_OP_INT | 321,702 | 2.9% |
| CONTAINS_OP | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,840,479 | 79.0% |
| NOP | 650,621 | 5.8% |
| RETURN_CONST | 367,294 | 3.3% |
| LOAD_CONST | 362,439 | 3.2% |
| STORE_FAST | 321,862 | 2.9% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 80 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,694,022 | 46.7% |
| POP_JUMP_IF_FALSE | 1,679,736 | 16.7% |
| STORE_FAST | 1,339,677 | 13.3% |
| STORE_ATTR_SLOT | 669,595 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 643,822 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,365,835 | 83.2% |
| INTERPRETER_EXIT | 1,353,351 | 13.5% |
| END_SEND | 337,142 | 3.4% |
| EXIT_INIT_CHECK | 700 | 0.0% |
| STORE_FAST | 460 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 329,602 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 329,282 | 49.9% |
| SEND | 720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 328,982 | 49.9% |
| YIELD_VALUE | 328,982 | 49.9% |
| SEND | 720 | 0.1% |
| POP_TOP | 460 | 0.1% |
| SEND_GEN | 460 | 0.1% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 321,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320,940 | 99.9% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| STORE_NAME | 40 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,340 | 66.3% |
| LOAD_FAST_LOAD_FAST | 2,520 | 20.0% |
| STORE_ATTR | 680 | 5.4% |
| SWAP | 400 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 3,560 | 28.3% |
| LOAD_FAST | 2,760 | 21.9% |
| LOAD_CONST | 1,760 | 14.0% |
| RETURN_CONST | 1,000 | 7.9% |
| STORE_ATTR | 680 | 5.4% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 36.4% |
| BUILD_LIST | 160 | 18.2% |
| CALL_KW | 160 | 18.2% |
| BINARY_OP_ADD_INT | 120 | 13.6% |
| CALL | 80 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 54.5% |
| LOAD_CONST | 160 | 18.2% |
| BUILD_LIST | 80 | 9.1% |
| LOAD_DEREF | 80 | 9.1% |
| LOAD_FAST_LOAD_FAST | 80 | 9.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,784,101 | 29.7% |
| CALL | 6,817,045 | 26.0% |
| LOAD_CONST | 4,570,877 | 17.4% |
| CALL_LEN | 697,159 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 689,036 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,575,511 | 67.0% |
| LOAD_FAST_LOAD_FAST | 1,387,930 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,355,940 | 5.2% |
| RETURN_CONST | 1,339,677 | 5.1% |
| JUMP_FORWARD | 1,312,925 | 5.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 560 | 90.3% |
| CALL_LEN | 40 | 6.5% |
| COPY | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 560 | 90.3% |
| PUSH_NULL | 40 | 6.5% |
| LOAD_ATTR | 20 | 3.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 972,907 | 99.9% |
| UNPACK_SEQUENCE | 300 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 160 | 0.0% |
| COPY | 100 | 0.0% |
| POP_TOP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 972,227 | 99.9% |
| LOAD_FAST_LOAD_FAST | 340 | 0.0% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| STORE_FAST | 180 | 0.0% |
| NOP | 160 | 0.0% |


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
| MAKE_FUNCTION | 500 | 43.1% |
| CALL | 220 | 19.0% |
| LOAD_CONST | 160 | 13.8% |
| LOAD_NAME | 100 | 8.6% |
| IMPORT_NAME | 60 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 400 | 34.5% |
| EXTENDED_ARG | 360 | 31.0% |
| LOAD_NAME | 120 | 10.3% |
| RETURN_CONST | 120 | 10.3% |
| LOAD_BUILD_CLASS | 100 | 8.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 329,560 | 94.1% |
| BINARY_OP_ADD_INT | 8,680 | 2.5% |
| BINARY_OP_SUBTRACT_INT | 8,400 | 2.4% |
| BUILD_LIST | 680 | 0.2% |
| LOAD_FAST_AND_CLEAR | 680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 330,160 | 94.3% |
| STORE_ATTR_WITH_HINT | 16,040 | 4.6% |
| STORE_ATTR_INSTANCE_VALUE | 840 | 0.2% |
| COPY | 720 | 0.2% |
| BUILD_LIST | 680 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 160 | 21.1% |
| STORE_FAST | 160 | 21.1% |
| END_SEND | 120 | 15.8% |
| LOAD_FAST | 80 | 10.5% |
| FOR_ITER_LIST | 80 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 320 | 42.1% |
| STORE_FAST_STORE_FAST | 300 | 39.5% |
| UNPACK_SEQUENCE_TUPLE | 60 | 7.9% |
| STORE_FAST | 40 | 5.3% |
| POP_TOP | 20 | 2.6% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 979,346 | 74.8% |
| SEND | 328,982 | 25.1% |
| LOAD_CONST | 160 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 979,346 | 74.8% |
| INTERPRETER_EXIT | 329,222 | 25.2% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,920 | 52.0% |
| CACHE | 940 | 16.7% |
| COPY_FREE_VARS | 660 | 11.7% |
| POP_TOP | 480 | 8.5% |
| SEND_GEN | 400 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 52.3% |
| LOAD_GLOBAL | 1,080 | 19.2% |
| JUMP_BACKWARD_NO_INTERRUPT | 480 | 8.5% |
| LOAD_CONST | 340 | 6.0% |
| NOP | 260 | 4.6% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 321,822 | 99.9% |
| LOAD_FAST | 280 | 0.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 321,842 | 99.9% |
| LOAD_FAST | 300 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 337,422 | 50.6% |
| CALL_LEN | 328,502 | 49.2% |
| LOAD_CONST | 1,240 | 0.2% |
| BINARY_OP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 337,442 | 50.6% |
| STORE_FAST | 320,762 | 48.1% |
| SWAP | 8,680 | 1.3% |
| BINARY_SLICE | 160 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 600 | 85.7% |
| BINARY_SUBSCR_LIST_INT | 80 | 11.4% |
| BINARY_OP | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 68.6% |
| CALL | 120 | 17.1% |
| STORE_FAST | 80 | 11.4% |
| LOAD_GLOBAL | 20 | 2.9% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 85.7% |
| BINARY_OP | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 120 | 85.7% |
| CALL | 20 | 14.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 320,542 | 99.9% |
| LOAD_CONST | 320 | 0.1% |
| BINARY_OP | 60 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 320,582 | 99.9% |
| STORE_FAST | 300 | 0.1% |
| COMPARE_OP | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 60.0% |
| BINARY_OP | 40 | 20.0% |
| LOAD_FAST | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,040 | 48.6% |
| LOAD_FAST_LOAD_FAST | 7,960 | 48.1% |
| LOAD_CONST | 400 | 2.4% |
| BINARY_OP | 100 | 0.6% |
| CALL_LEN | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,400 | 50.8% |
| STORE_FAST | 8,000 | 48.4% |
| LOAD_FAST | 60 | 0.4% |
| RETURN_VALUE | 40 | 0.2% |
| LOAD_FAST_LOAD_FAST | 40 | 0.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,057 | 82.4% |
| LOAD_FAST | 1,540 | 15.8% |
| BINARY_SUBSCR | 80 | 0.8% |
| LOAD_CONST | 80 | 0.8% |
| BUILD_TUPLE | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,157 | 83.4% |
| RETURN_VALUE | 940 | 9.6% |
| PUSH_EXC_INFO | 520 | 5.3% |
| LOAD_FAST | 120 | 1.2% |
| CALL_BUILTIN_CLASS | 40 | 0.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 75.0% |
| LOAD_FAST_LOAD_FAST | 80 | 20.0% |
| BINARY_SUBSCR | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 400 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,062 | 99.1% |
| BINARY_SUBSCR | 100 | 0.8% |
| LOAD_FAST | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,651 | 50.5% |
| STORE_FAST | 6,271 | 47.6% |
| BINARY_OP_ADD_UNICODE | 80 | 0.6% |
| LOAD_ATTR | 60 | 0.5% |
| RETURN_VALUE | 40 | 0.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 45.5% |
| ENTER_EXECUTOR | 60 | 27.3% |
| LOAD_FAST | 60 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 45.5% |
| STORE_FAST | 100 | 45.5% |
| PUSH_EXC_INFO | 20 | 9.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 55.6% |
| RETURN_VALUE | 80 | 22.2% |
| LOAD_GLOBAL_MODULE | 80 | 22.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 47.2% |
| LOAD_FAST_LOAD_FAST | 160 | 22.2% |
| CALL | 120 | 16.7% |
| PUSH_NULL | 40 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 640 | 88.9% |
| COPY_FREE_VARS | 60 | 8.3% |
| STORE_FAST | 20 | 2.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 320,862 | 97.4% |
| CALL_BUILTIN_CLASS | 7,977 | 2.4% |
| LOAD_CONST | 360 | 0.1% |
| LOAD_FAST | 180 | 0.1% |
| PUSH_NULL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 321,242 | 97.5% |
| COPY_FREE_VARS | 7,997 | 2.4% |
| POP_TOP | 240 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 330,219 | 85.8% |
| LOAD_ATTR_INSTANCE_VALUE | 53,572 | 13.9% |
| CALL | 280 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 220 | 0.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 322,102 | 83.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 53,412 | 13.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 7,977 | 2.1% |
| STORE_FAST | 540 | 0.1% |
| LOAD_FAST | 240 | 0.1% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,060 | 59.6% |
| LOAD_FAST | 320 | 18.0% |
| LOAD_ATTR_SLOT | 180 | 10.1% |
| CALL | 120 | 6.7% |
| LOAD_FAST_LOAD_FAST | 60 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 560 | 31.5% |
| TO_BOOL_BOOL | 520 | 29.2% |
| POP_JUMP_IF_NOT_NONE | 360 | 20.2% |
| COPY | 220 | 12.4% |
| TO_BOOL | 60 | 3.4% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 53,412 | 99.0% |
| LOAD_FAST | 360 | 0.7% |
| LOAD_CONST | 120 | 0.2% |
| CALL_STR_1 | 40 | 0.1% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 53,792 | 99.7% |
| STORE_FAST | 140 | 0.3% |
| BEFORE_WITH | 40 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 40.7% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 23.7% |
| CALL | 120 | 10.2% |
| BINARY_OP_MULTIPLY_FLOAT | 120 | 10.2% |
| LOAD_CONST | 80 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 500 | 42.4% |
| STORE_FAST | 340 | 28.8% |
| LOAD_CONST | 140 | 11.9% |
| BUILD_TUPLE | 80 | 6.8% |
| TO_BOOL_INT | 60 | 5.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,074 | 65.9% |
| BUILD_TUPLE | 8,920 | 30.8% |
| CALL | 380 | 1.3% |
| LOAD_GLOBAL_MODULE | 360 | 1.2% |
| LOAD_ATTR_MODULE | 160 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 28,494 | 98.5% |
| TO_BOOL | 380 | 1.3% |
| RETURN_VALUE | 40 | 0.1% |
| LOAD_FAST | 20 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,606,608 | 54.1% |
| LOAD_FAST | 1,040,978 | 35.1% |
| LOAD_ATTR_WITH_HINT | 320,862 | 10.8% |
| CALL | 320 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 697,159 | 23.5% |
| TO_BOOL_INT | 650,264 | 21.9% |
| LOAD_FAST | 641,342 | 21.6% |
| BINARY_OP_ADD_INT | 328,502 | 11.1% |
| COPY | 321,842 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,479,073 | 92.4% |
| BUILD_TUPLE | 366,674 | 7.6% |
| CALL | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,845,040 | 100.0% |
| JUMP_BACKWARD | 607 | 0.0% |
| JUMP_FORWARD | 140 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 329,542 | 49.8% |
| LOAD_FAST | 321,264 | 48.6% |
| LOAD_FAST_LOAD_FAST | 8,937 | 1.4% |
| LOAD_GLOBAL_MODULE | 680 | 0.1% |
| RETURN_VALUE | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 651,086 | 98.5% |
| RETURN_VALUE | 9,097 | 1.4% |
| LIST_APPEND | 560 | 0.1% |
| POP_TOP | 220 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 321,822 | 99.5% |
| LOAD_FAST | 480 | 0.1% |
| LOAD_ATTR | 360 | 0.1% |
| LOAD_CONST | 280 | 0.1% |
| CALL | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 322,002 | 99.6% |
| POP_TOP | 1,020 | 0.3% |
| RETURN_VALUE | 140 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 369,896 | 52.8% |
| LOAD_ATTR | 329,222 | 47.0% |
| CALL | 840 | 0.1% |
| LOAD_FAST | 360 | 0.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 367,637 | 52.5% |
| TO_BOOL_BOOL | 329,342 | 47.0% |
| POP_TOP | 920 | 0.1% |
| RETURN_VALUE | 699 | 0.1% |
| LOAD_FAST | 460 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,378,437 | 79.3% |
| BINARY_SLICE | 358,337 | 20.6% |
| CALL | 840 | 0.0% |
| LOAD_CONST | 600 | 0.0% |
| STORE_FAST | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,729,834 | 99.5% |
| RETURN_VALUE | 8,560 | 0.5% |
| CALL_PY_EXACT_ARGS | 319 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,922,838 | 36.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,490,673 | 32.3% |
| LOAD_FAST | 2,405,803 | 22.2% |
| LOAD_CONST | 641,963 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 330,839 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,150,989 | 93.8% |
| RETURN_GENERATOR | 337,522 | 3.1% |
| MAKE_CELL | 320,600 | 3.0% |
| COPY_FREE_VARS | 10,177 | 0.1% |
| RESUME | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,119,680 | 93.9% |
| LOAD_ATTR | 321,343 | 5.9% |
| LOAD_FAST | 8,877 | 0.2% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,451,180 | 100.0% |
| RETURN_GENERATOR | 120 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 66.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 33.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 80.0% |
| LOAD_FAST | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 80.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 20.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 980 | 94.2% |
| LOAD_GLOBAL_MODULE | 40 | 3.8% |
| CALL | 20 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740 | 71.2% |
| LOAD_GLOBAL_MODULE | 200 | 19.2% |
| PUSH_NULL | 40 | 3.8% |
| LOAD_FAST_LOAD_FAST | 40 | 3.8% |
| LOAD_GLOBAL | 20 | 1.9% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,251 | 95.7% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 1.8% |
| LOAD_ATTR_SLOT | 120 | 1.8% |
| COMPARE_OP | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,391 | 97.9% |
| RETURN_VALUE | 140 | 2.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 1,949,130 | 41.8% |
| LOAD_CONST | 1,304,182 | 28.0% |
| LOAD_GLOBAL_MODULE | 321,862 | 6.9% |
| LOAD_FAST | 321,582 | 6.9% |
| BINARY_OP_MULTIPLY_INT | 320,582 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,340,297 | 93.1% |
| POP_JUMP_IF_TRUE | 321,702 | 6.9% |
| RETURN_VALUE | 60 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 720 | 75.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 12.5% |
| COMPARE_OP | 80 | 8.3% |
| LOAD_FAST | 40 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 820 | 85.4% |
| COPY | 60 | 6.2% |
| STORE_FAST | 60 | 6.2% |
| EXTENDED_ARG | 20 | 2.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 644,604 | 50.0% |
| ENTER_EXECUTOR | 641,367 | 49.8% |
| JUMP_BACKWARD | 1,520 | 0.1% |
| FOR_ITER | 280 | 0.0% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 642,427 | 49.9% |
| RETURN_CONST | 322,042 | 25.0% |
| LOAD_FAST | 321,942 | 25.0% |
| STORE_FAST | 1,020 | 0.1% |
| LOAD_DEREF | 140 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 322,022 | 49.9% |
| ENTER_EXECUTOR | 321,782 | 49.9% |
| JUMP_BACKWARD | 900 | 0.1% |
| FOR_ITER | 60 | 0.0% |
| SWAP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 322,762 | 50.1% |
| LOAD_CONST | 321,862 | 49.9% |
| LOAD_FAST | 100 | 0.0% |
| SWAP | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,260 | 47.8% |
| GET_ITER | 8,060 | 46.6% |
| SWAP | 560 | 3.2% |
| JUMP_BACKWARD | 360 | 2.1% |
| FOR_ITER | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,060 | 46.6% |
| NOP | 8,000 | 46.3% |
| STORE_FAST_LOAD_FAST | 560 | 3.2% |
| SWAP | 560 | 3.2% |
| LOAD_GLOBAL | 40 | 0.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 94.7% |
| LOAD_ATTR | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,161,056 | 99.9% |
| LOAD_FAST_LOAD_FAST | 9,497 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,037 | 0.0% |
| LOAD_ATTR | 4,880 | 0.0% |
| COPY | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 7,467,200 | 32.2% |
| TO_BOOL_BOOL | 3,921,034 | 16.9% |
| CALL_LEN | 1,606,608 | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,358,455 | 5.9% |
| LOAD_ATTR | 1,301,384 | 5.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,467,200 | 53.0% |
| LOAD_FAST_CHECK | 4,478,853 | 31.8% |
| LOAD_FAST | 1,112,644 | 7.9% |
| LOAD_ATTR_WITH_HINT | 658,524 | 4.7% |
| LOAD_ATTR | 376,911 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,318,030 | 87.4% |
| LOAD_FAST_LOAD_FAST | 743,005 | 5.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 369,896 | 2.6% |
| CALL_PY_EXACT_ARGS | 330,839 | 2.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 329,542 | 2.3% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,824,190 | 58.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,358,455 | 20.7% |
| LOAD_ATTR_SLOT | 677,272 | 10.3% |
| LOAD_ATTR_WITH_HINT | 675,797 | 10.3% |
| RETURN_VALUE | 9,017 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,490,673 | 53.3% |
| LOAD_FAST | 2,074,242 | 31.7% |
| LOAD_FAST_LOAD_FAST | 659,978 | 10.1% |
| LOAD_CONST | 321,161 | 4.9% |
| CALL | 1,820 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,395,044 | 99.9% |
| LOAD_ATTR | 2,280 | 0.1% |
| LOAD_FAST | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,692,390 | 70.6% |
| BINARY_OP | 695,614 | 29.0% |
| CALL | 1,280 | 0.1% |
| LOAD_CONST | 1,040 | 0.0% |
| LOAD_FAST | 1,040 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740 | 84.1% |
| LOAD_ATTR | 120 | 13.6% |
| LOAD_FAST_LOAD_FAST | 20 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 580 | 65.9% |
| CALL | 140 | 15.9% |
| BINARY_OP | 120 | 13.6% |
| CALL_ISINSTANCE | 20 | 2.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 2.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 320,166 | 99.5% |
| LOAD_FAST | 1,236 | 0.4% |
| LOAD_ATTR | 220 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 321,242 | 99.8% |
| COPY_FREE_VARS | 580 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,117,442 | 99.6% |
| LOAD_FAST_LOAD_FAST | 7,980 | 0.2% |
| BINARY_SUBSCR_LIST_INT | 6,651 | 0.2% |
| LOAD_ATTR | 940 | 0.0% |
| LOAD_ATTR_MODULE | 820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 1,303,202 | 31.5% |
| TO_BOOL_BOOL | 1,124,150 | 27.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 677,272 | 16.4% |
| LOAD_ATTR | 322,402 | 7.8% |
| BUILD_LIST | 322,002 | 7.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,243,096 | 71.2% |
| LOAD_FAST_LOAD_FAST | 1,949,250 | 19.2% |
| LOAD_DEREF | 961,318 | 9.5% |
| COPY | 16,040 | 0.2% |
| LOAD_ATTR | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,614,552 | 25.7% |
| COMPARE_OP_INT | 1,949,130 | 19.2% |
| LOAD_GLOBAL_MODULE | 1,621,706 | 15.9% |
| LOAD_ATTR | 979,764 | 9.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 675,797 | 6.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,355,940 | 32.5% |
| POP_JUMP_IF_FALSE | 636,491 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 445,326 | 10.7% |
| RESUME_CHECK | 406,388 | 9.7% |
| LOAD_FAST | 348,556 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,697,698 | 88.5% |
| LOAD_GLOBAL_BUILTIN | 445,326 | 10.7% |
| CALL_ISINSTANCE | 19,074 | 0.5% |
| BUILD_TUPLE | 9,060 | 0.2% |
| LOAD_DEREF | 4,199 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,703,597 | 26.4% |
| LOAD_ATTR_WITH_HINT | 1,621,706 | 25.1% |
| RESUME_CHECK | 1,353,237 | 21.0% |
| LOAD_ATTR | 658,225 | 10.2% |
| POP_TOP | 375,911 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,395,044 | 37.1% |
| LOAD_ATTR | 2,284,831 | 35.4% |
| BINARY_OP | 1,010,380 | 15.6% |
| COMPARE_OP_INT | 321,862 | 5.0% |
| CHECK_EXC_MATCH | 321,002 | 5.0% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 78.0% |
| LOAD_GLOBAL_MODULE | 120 | 14.6% |
| LOAD_SUPER_ATTR | 60 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 640 | 78.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 14.6% |
| LOAD_GLOBAL | 40 | 4.9% |
| LOAD_ATTR | 20 | 2.4% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,079 | 87.5% |
| LOAD_SUPER_ATTR | 440 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,400 | 39.8% |
| LOAD_FAST_LOAD_FAST | 1,220 | 34.7% |
| CALL_PY_EXACT_ARGS | 759 | 21.6% |
| CALL | 140 | 4.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,150,989 | 47.8% |
| CALL_PY_WITH_DEFAULTS | 5,451,180 | 25.7% |
| CACHE | 2,020,798 | 9.5% |
| SEND_GEN | 978,946 | 4.6% |
| POP_TOP | 658,844 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,507,345 | 77.8% |
| LOAD_GLOBAL_MODULE | 1,353,237 | 6.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,307,848 | 6.2% |
| LOAD_DEREF | 649,137 | 3.1% |
| LOAD_CONST | 644,022 | 3.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 979,046 | 59.8% |
| LOAD_CONST | 658,224 | 40.2% |
| SEND | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 978,946 | 59.8% |
| POP_TOP | 658,384 | 40.2% |
| RESUME | 400 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,629,744 | 99.4% |
| LOAD_FAST_LOAD_FAST | 4,200 | 0.3% |
| STORE_ATTR | 3,560 | 0.2% |
| SWAP | 840 | 0.1% |
| LOAD_DEREF | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 661,562 | 40.4% |
| RETURN_CONST | 643,822 | 39.3% |
| NOP | 320,622 | 19.6% |
| LOAD_CONST | 6,199 | 0.4% |
| LOAD_FAST_LOAD_FAST | 2,140 | 0.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,640,532 | 56.6% |
| LOAD_FAST | 2,023,445 | 43.4% |
| STORE_ATTR | 560 | 0.0% |
| STORE_ATTR_SLOT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,979,854 | 42.4% |
| LOAD_CONST | 1,329,173 | 28.5% |
| LOAD_FAST | 669,955 | 14.4% |
| RETURN_CONST | 669,595 | 14.4% |
| NOP | 15,960 | 0.3% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 353,120 | 51.1% |
| LOAD_DEREF | 320,360 | 46.4% |
| SWAP | 16,040 | 2.3% |
| LOAD_FAST_LOAD_FAST | 1,120 | 0.2% |
| STORE_ATTR | 440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 337,320 | 48.8% |
| RETURN_CONST | 329,420 | 47.7% |
| NOP | 15,800 | 2.3% |
| ENTER_EXECUTOR | 7,660 | 1.1% |
| LOAD_CONST | 420 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 8,337 | 88.9% |
| LOAD_FAST | 480 | 5.1% |
| LOAD_CONST | 280 | 3.0% |
| STORE_SUBSCR | 160 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,677 | 92.5% |
| NOP | 220 | 2.3% |
| LOAD_CONST | 140 | 1.5% |
| RETURN_CONST | 140 | 1.5% |
| LOAD_GLOBAL_MODULE | 120 | 1.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 20 | 50.0% |
| RETURN_CONST | 20 | 50.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 70.0% |
| TO_BOOL | 80 | 20.0% |
| TO_BOOL_NONE | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 260 | 65.0% |
| POP_JUMP_IF_TRUE | 140 | 35.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,929,936 | 53.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,921,034 | 21.0% |
| LOAD_ATTR_WITH_HINT | 2,614,552 | 14.0% |
| LOAD_ATTR_SLOT | 1,124,150 | 6.0% |
| RETURN_VALUE | 694,235 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,277,342 | 87.3% |
| POP_JUMP_IF_TRUE | 2,368,841 | 12.7% |
| UNARY_NOT | 340 | 0.0% |
| EXTENDED_ARG | 100 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,010,420 | 32.6% |
| BINARY_OP | 688,237 | 22.2% |
| CALL_LEN | 650,264 | 21.0% |
| LOAD_FAST | 375,034 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 374,714 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,768,409 | 57.1% |
| POP_JUMP_IF_TRUE | 1,330,740 | 42.9% |
| UNARY_NOT | 80 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 644,924 | 99.9% |
| LOAD_FAST | 320 | 0.0% |
| TO_BOOL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 645,184 | 100.0% |
| POP_JUMP_IF_TRUE | 220 | 0.0% |
| UNARY_NOT | 20 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,303,202 | 99.8% |
| LOAD_FAST | 1,379 | 0.1% |
| LOAD_ATTR | 600 | 0.0% |
| TO_BOOL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,305,361 | 100.0% |
| TO_BOOL_ALWAYS_TRUE | 40 | 0.0% |
| POP_JUMP_IF_TRUE | 20 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 560 | 46.7% |
| LOAD_FAST | 400 | 33.3% |
| COPY | 160 | 13.3% |
| TO_BOOL | 80 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 920 | 76.7% |
| POP_JUMP_IF_TRUE | 280 | 23.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 28.6% |
| CALL_METHOD_DESCRIPTOR_O | 80 | 28.6% |
| UNPACK_SEQUENCE | 60 | 21.4% |
| BINARY_SUBSCR_LIST_INT | 40 | 14.3% |
| RETURN_VALUE | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 160 | 57.1% |
| POP_TOP | 60 | 21.4% |
| STORE_FAST | 60 | 21.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 642,427 | 66.0% |
| STORE_FAST | 329,400 | 33.9% |
| RETURN_VALUE | 480 | 0.0% |
| UNPACK_SEQUENCE | 320 | 0.0% |
| BINARY_SLICE | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 972,907 | 100.0% |
| STORE_FAST | 100 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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
|     deferred | 2,122,000 | 61.5% |
|          hit | 1,328,048 | 38.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 480 | 16.0% |
| Failure | 2,520 | 84.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,720 | 68.3% |
| or | 600 | 23.8% |
| floor divide | 120 | 4.8% |
| multiply different types | 60 | 2.4% |
| add different types | 20 | 0.8% |


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
|     deferred | 8,340 | 25.6% |
|          hit | 23,799 | 72.9% |
|         miss | 140 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 55.6% |
| Failure | 160 | 44.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 140 | 87.5% |
| out of range | 20 | 12.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,833,940 | 23.6% |
|          hit | 28,638,074 | 76.4% |
|         miss | 2,820 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,420 | 51.1% |
| Failure | 8,060 | 48.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 1,960 | 24.3% |
| class no vectorcall | 1,340 | 16.6% |
| code complex parameters | 940 | 11.7% |
| cfunc noargs | 800 | 9.9% |
| meth descr method fastcall keywords | 760 | 9.4% |
| no dict | 640 | 7.9% |
| other | 380 | 4.7% |
| cfunc varargs keywords | 340 | 4.2% |
| class mutable | 300 | 3.7% |
| meth descr varargs keywords | 260 | 3.2% |
| operator wrapper | 140 | 1.7% |
| cfunc varargs | 100 | 1.2% |
| wrong number arguments | 40 | 0.5% |
| cmethod | 40 | 0.5% |
| init not simple | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 985,799 | 17.4% |
|          hit | 4,669,410 | 82.5% |
|         miss | 180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 880 | 27.0% |
| Failure | 2,380 | 73.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 1,780 | 74.8% |
| other | 220 | 9.2% |
| tuple | 140 | 5.9% |
| different types | 120 | 5.0% |
| float long | 80 | 3.4% |
| bool | 40 | 1.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,180 | 0.5% |
|          hit | 1,950,035 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 59.4% |
| Failure | 260 | 40.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 140 | 53.8% |
| dict items | 80 | 30.8% |
| set | 40 | 15.4% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,922,716 | 15.2% |
|          hit | 60,853,095 | 84.7% |
|         miss | 3,640 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 15,740 | 49.0% |
| Failure | 16,362 | 51.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 7,742 | 47.3% |
| metaclass attribute | 3,680 | 22.5% |
| not managed dict | 2,620 | 16.0% |
| method | 1,200 | 7.3% |
| shadowed | 720 | 4.4% |
| class method obj | 180 | 1.1% |
| non object slot | 80 | 0.5% |
| class attr descriptor | 60 | 0.4% |
| class attr simple | 40 | 0.2% |
| module attr not found | 20 | 0.1% |
| builtin class method | 20 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,060 | 0.1% |
|        deopt | 80 | 0.0% |
|          hit | 10,635,034 | 99.9% |
|         miss | 180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,000 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 520 | 9.7% |
|          hit | 4,339 | 81.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 100.0% |
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
|     deferred | 658,424 | 28.7% |
|          hit | 1,637,730 | 71.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 460 | 39.0% |
| Failure | 720 | 61.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 720 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,280 | 0.1% |
|          hit | 6,988,381 | 99.7% |
|         miss | 6,260 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,620 | 87.2% |
| Failure | 680 | 12.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 320 | 47.1% |
| overridden | 80 | 11.8% |
| overriding descriptor | 80 | 11.8% |
| not in dict | 80 | 11.8% |
| no dict | 40 | 5.9% |
| property | 40 | 5.9% |
| not in keys | 40 | 5.9% |


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 640 | 6.2% |
|          hit | 9,417 | 91.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 72.7% |
| Failure | 60 | 27.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 40 | 66.7% |
| bytearray int | 20 | 33.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,512,817 | 24.1% |
|          hit | 23,698,117 | 75.9% |
|         miss | 180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,940 | 45.3% |
| Failure | 4,760 | 54.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 2,420 | 50.8% |
| sequence | 1,380 | 29.0% |
| bytearray | 260 | 5.5% |
| mapping | 260 | 5.5% |
| dict | 160 | 3.4% |
| memory view | 140 | 2.9% |
| set | 100 | 2.1% |
| float | 20 | 0.4% |
| tuple | 20 | 0.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 380 | 0.0% |
|          hit | 973,347 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 226,188,592 | 48.4% |
| Not specialized | 78,541,882 | 16.8% |
| Specialized hits | 162,309,676 | 34.8% |
| Specialized misses | 13,420 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 10,922,716 | 35.2% |
| CALL | 8,833,940 | 28.4% |
| TO_BOOL | 7,512,817 | 24.2% |
| BINARY_OP | 2,122,000 | 6.8% |
| COMPARE_OP | 985,799 | 3.2% |
| SEND | 658,424 | 2.1% |
| FOR_ITER | 9,180 | 0.0% |
| BINARY_SUBSCR | 8,340 | 0.0% |
| STORE_ATTR | 7,280 | 0.0% |
| LOAD_GLOBAL | 7,060 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,260 | 46.6% |
| LOAD_ATTR_SLOT | 3,000 | 22.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,420 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 540 | 4.0% |
| CALL_PY_EXACT_ARGS | 280 | 2.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 280 | 2.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 240 | 1.8% |
| LOAD_ATTR_MODULE | 240 | 1.8% |
| COMPARE_OP_INT | 160 | 1.2% |
| BINARY_SUBSCR_STR_INT | 140 | 1.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,345,217 | 11.0% |
| Calls to Python functions inlined | 18,908,112 | 89.0% |
| Calls via PyEval_EvalFrame (total) | 2,345,217 | 11.0% |
| Calls via PyEval_EvalFrame (vector) | 2,015,515 | 9.5% |
| Calls via PyEval_EvalFrame (generator) | 329,702 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,015,375 | 9.5% |
| Calls via PyEval_EvalFrame (build class) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 380 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 440 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,920 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 659,804 | 3.1% |
| Frame objects created | 643,404 | 3.0% |
| Frames pushed | 18,596,152 | 87.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,685,412 | 41.2% |
| Frees to freelist | 14,693,449 |  |
| Allocations | 20,965,611 | 58.8% |
| Allocations to 512 bytes | 14,551,788 | 40.8% |
| Allocations to 4 kbytes | 323,178 | 0.9% |
| Allocations over 4 kbytes | 6,090,645 | 17.1% |
| Frees | 21,347,331 |  |
| New values | 1,560 |  |
| Interpreter increfs | 231,326,110 | 76.6% |
| Interpreter decrefs | 256,035,595 | 76.3% |
| Increfs | 70,576,825 | 23.4% |
| Decrefs | 79,336,312 | 23.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 160 | 10.3% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 20,395,280 |  |
| Method cache misses | 78,512 |  |
| Method cache collisions | 77,968 |  |
| Method cache dunder hits | 1,046,328 |  |
| Method cache dunder misses | 1,481 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,980 | 139,880 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 220 |  |
| Traces created | 220 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 20 | 9.1% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 7,856,269 |  |
| Uops executed | 161,943,104 | 20.61 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 60 | 27.3% |
| <= 64 | 60 | 27.3% |
| <= 128 | 100 | 45.5% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 9.1% |
| <= 32 | 60 | 27.3% |
| <= 64 | 100 | 45.5% |
| <= 128 | 40 | 18.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 656,787 | 8.4% |
| <= 4 | 321,858 | 4.1% |
| <= 8 | 540 | 0.0% |
| <= 16 | 321,522 | 4.1% |
| <= 32 | 5,531,803 | 70.4% |
| <= 64 | 320,346 | 4.1% |
| <= 128 | 703,293 | 9.0% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 40 | 0.0% |
| <= 2,048 | 40 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 40 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 25,627,716 | 15.8% | 15.8% |  |
| _CHECK_VALIDITY | 24,541,205 | 15.2% | 31.0% |  |
| LOAD_FAST | 17,511,768 | 10.8% | 41.8% |  |
| _GUARD_TYPE_VERSION | 17,484,316 | 10.8% | 52.6% |  |
| _EXIT_TRACE | 6,785,363 | 4.2% | 56.8% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 6,096,890 | 3.8% | 60.5% |  |
| _GUARD_KEYS_VERSION | 6,096,890 | 3.8% | 64.3% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 6,096,890 | 3.8% | 68.1% |  |
| _LOAD_ATTR | 5,913,855 | 3.7% | 71.7% |  |
| _CHECK_ATTR_WITH_HINT | 5,439,846 | 3.4% | 75.1% |  |
| _LOAD_ATTR_WITH_HINT | 5,439,846 | 3.4% | 78.4% |  |
| _LOAD_ATTR_SLOT | 2,782,592 | 1.7% | 80.2% |  |
| _GUARD_IS_FALSE_POP | 2,077,824 | 1.3% | 81.4% | 2.2% |
| TO_BOOL_BOOL | 2,039,754 | 1.3% | 82.7% |  |
| STORE_FAST | 1,786,211 | 1.1% | 83.8% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 1,757,682 | 1.1% | 84.9% |  |
| _CHECK_PEP_523 | 1,672,963 | 1.0% | 85.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 1,672,963 | 1.0% | 87.0% |  |
| _CHECK_STACK_SPACE | 1,672,963 | 1.0% | 88.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 1,672,963 | 1.0% | 89.0% |  |
| _PUSH_FRAME | 1,672,963 | 1.0% | 90.1% |  |
| _SAVE_RETURN_OFFSET | 1,672,963 | 1.0% | 91.1% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,407,266 | 0.9% | 92.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,407,266 | 0.9% | 92.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 1,036,395 | 0.6% | 93.5% | 31.0% |
| _ITER_CHECK_RANGE | 1,036,395 | 0.6% | 94.1% |  |
| RESUME_CHECK | 1,031,239 | 0.6% | 94.7% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 733,128 | 0.5% | 95.2% | 87.5% |
| _ITER_CHECK_LIST | 733,128 | 0.5% | 95.7% |  |
| _ITER_NEXT_RANGE | 714,613 | 0.4% | 96.1% |  |
| PUSH_NULL | 696,953 | 0.4% | 96.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 695,693 | 0.4% | 97.0% |  |
| BUILD_LIST | 695,633 | 0.4% | 97.4% |  |
| CALL_INTRINSIC_1 | 695,633 | 0.4% | 97.8% |  |
| LIST_EXTEND | 695,633 | 0.4% | 98.2% |  |
| _GUARD_GLOBALS_VERSION | 443,123 | 0.3% | 98.5% | 0.1% |
| _LOAD_GLOBAL_MODULE | 412,343 | 0.3% | 98.8% |  |
| LOAD_CONST | 341,786 | 0.2% | 99.0% |  |
| LOAD_FAST_CHECK | 320,166 | 0.2% | 99.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 320,166 | 0.2% | 99.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 136,852 | 0.1% | 99.5% |  |
| _GUARD_IS_TRUE_POP | 117,001 | 0.1% | 99.5% | 38.9% |
| _BINARY_OP | 100,921 | 0.1% | 99.6% |  |
| _ITER_NEXT_LIST | 91,681 | 0.1% | 99.7% |  |
| TO_BOOL_INT | 90,921 | 0.1% | 99.7% |  |
| _TO_BOOL | 53,070 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 46,110 | 0.0% | 99.8% |  |
| _CHECK_ATTR_MODULE | 45,491 | 0.0% | 99.8% |  |
| _LOAD_ATTR_MODULE | 45,491 | 0.0% | 99.8% |  |
| COPY | 45,470 | 0.0% | 99.9% |  |
| SWAP | 45,451 | 0.0% | 99.9% |  |
| _GUARD_BUILTINS_VERSION | 30,540 | 0.0% | 99.9% | 0.2% |
| _LOAD_GLOBAL_BUILTINS | 30,480 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 15,200 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 11,960 | 0.0% | 99.9% |  |
| _GUARD_BOTH_INT | 11,340 | 0.0% | 99.9% |  |
| BINARY_SLICE | 11,320 | 0.0% | 100.0% |  |
| _STORE_SUBSCR | 10,120 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 10,100 | 0.0% | 100.0% |  |
| CONTAINS_OP | 10,080 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 10,040 | 0.0% | 100.0% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 8,900 | 0.0% | 100.0% | 92.8% |
| _ITER_CHECK_TUPLE | 8,900 | 0.0% | 100.0% |  |
| _FOR_ITER_TIER_TWO | 7,680 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 7,640 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,880 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 1,240 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 1,240 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 640 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 640 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 360 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 360 | 0.0% | 100.0% |  |
| IS_OP | 120 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 120 | 0.0% | 100.0% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 80 | 0.0% | 100.0% | 75.0% |
| _GUARD_IS_NOT_NONE_POP | 60 | 0.0% | 100.0% | 33.3% |
| COMPARE_OP_STR | 60 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 60 | 0.0% | 100.0% |  |
| _POP_FRAME | 60 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 40 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| RETURN_GENERATOR | 20 |
| CALL | 20 |
| CALL_FUNCTION_EX | 20 |
| CALL_LIST_APPEND | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |
| LOAD_ATTR_PROPERTY | 20 |
| STORE_ATTR_WITH_HINT | 20 |


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
Stats gathered on: 2023-11-16
