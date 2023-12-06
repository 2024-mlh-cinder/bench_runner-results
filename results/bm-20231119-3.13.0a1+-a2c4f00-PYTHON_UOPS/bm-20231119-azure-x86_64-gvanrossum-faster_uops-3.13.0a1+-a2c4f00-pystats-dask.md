
# Pystats results

- benchmark: dask
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 320,742,090 | 20.3% | 20.3% |  |
| STORE_FAST | 79,424,344 | 5.0% | 25.3% |  |
| RESUME_CHECK | 76,246,391 | 4.8% | 30.1% | 0.0% |
| LOAD_CONST | 66,109,015 | 4.2% | 34.3% |  |
| POP_JUMP_IF_FALSE | 63,467,544 | 4.0% | 38.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 57,572,137 | 3.6% | 41.9% | 0.6% |
| RETURN_VALUE | 54,275,492 | 3.4% | 45.3% |  |
| LOAD_FAST_LOAD_FAST | 46,864,111 | 3.0% | 48.3% |  |
| LOAD_GLOBAL_MODULE | 43,055,233 | 2.7% | 51.0% | 0.0% |
| POP_TOP | 42,821,349 | 2.7% | 53.7% |  |
| LOAD_GLOBAL_BUILTIN | 36,698,375 | 2.3% | 56.0% | 0.0% |
| LOAD_ATTR_SLOT | 32,934,547 | 2.1% | 58.1% | 3.5% |
| CALL_PY_EXACT_ARGS | 30,210,110 | 1.9% | 60.0% | 0.4% |
| CALL | 27,146,672 | 1.7% | 61.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 26,417,919 | 1.7% | 63.4% | 1.4% |
| INTERPRETER_EXIT | 25,102,809 | 1.6% | 65.0% |  |
| TO_BOOL_BOOL | 24,841,340 | 1.6% | 66.6% | 0.0% |
| LOAD_ATTR_WITH_HINT | 21,039,802 | 1.3% | 67.9% | 0.3% |
| RETURN_CONST | 20,775,167 | 1.3% | 69.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,228,425 | 1.3% | 70.5% | 0.1% |
| LOAD_ATTR | 20,155,802 | 1.3% | 71.8% |  |
| PUSH_NULL | 19,578,869 | 1.2% | 73.0% |  |
| NOP | 17,269,558 | 1.1% | 74.1% |  |
| SWAP | 15,798,976 | 1.0% | 75.1% |  |
| STORE_ATTR_SLOT | 15,146,017 | 1.0% | 76.0% | 6.0% |
| BUILD_MAP | 14,574,948 | 0.9% | 77.0% |  |
| GET_ITER | 13,935,384 | 0.9% | 77.8% |  |
| POP_JUMP_IF_TRUE | 13,039,498 | 0.8% | 78.7% |  |
| CALL_FUNCTION_EX | 11,716,412 | 0.7% | 79.4% |  |
| ENTER_EXECUTOR | 11,314,017 | 0.7% | 80.1% |  |
| BUILD_LIST | 10,975,280 | 0.7% | 80.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 10,509,179 | 0.7% | 81.5% | 0.0% |
| COPY | 10,359,525 | 0.7% | 82.1% |  |
| BINARY_SUBSCR_DICT | 10,198,527 | 0.6% | 82.8% |  |
| CONTAINS_OP | 10,129,932 | 0.6% | 83.4% |  |
| IS_OP | 9,340,695 | 0.6% | 84.0% |  |
| BUILD_TUPLE | 9,189,819 | 0.6% | 84.6% |  |
| DICT_MERGE | 8,838,425 | 0.6% | 85.1% |  |
| LOAD_DEREF | 8,732,739 | 0.6% | 85.7% |  |
| TO_BOOL | 8,559,640 | 0.5% | 86.2% |  |
| COMPARE_OP_INT | 8,113,174 | 0.5% | 86.8% | 0.3% |
| LIST_EXTEND | 8,034,086 | 0.5% | 87.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 8,023,655 | 0.5% | 87.8% | 0.1% |
| CALL_INTRINSIC_1 | 7,954,322 | 0.5% | 88.3% |  |
| LOAD_ATTR_MODULE | 7,873,829 | 0.5% | 88.8% | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 7,721,424 | 0.5% | 89.3% | 1.2% |
| CALL_TYPE_1 | 7,692,489 | 0.5% | 89.7% |  |
| CALL_BUILTIN_CLASS | 7,120,987 | 0.4% | 90.2% |  |
| FOR_ITER_TUPLE | 6,924,034 | 0.4% | 90.6% |  |
| POP_JUMP_IF_NONE | 6,551,256 | 0.4% | 91.0% |  |
| POP_JUMP_IF_NOT_NONE | 6,129,150 | 0.4% | 91.4% |  |
| FOR_ITER | 6,078,456 | 0.4% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 6,020,062 | 0.4% | 92.2% | 3.0% |
| CALL_LEN | 5,563,572 | 0.4% | 92.5% |  |
| COMPARE_OP_STR | 5,555,359 | 0.4% | 92.9% | 0.0% |
| BINARY_OP_ADD_INT | 5,083,445 | 0.3% | 93.2% | 0.0% |
| CALL_ISINSTANCE | 4,480,999 | 0.3% | 93.5% |  |
| STORE_SUBSCR_DICT | 4,470,842 | 0.3% | 93.8% |  |
| STORE_FAST_STORE_FAST | 4,404,121 | 0.3% | 94.1% |  |
| MAKE_CELL | 4,168,035 | 0.3% | 94.3% |  |
| TO_BOOL_NONE | 4,167,909 | 0.3% | 94.6% | 0.2% |
| COPY_FREE_VARS | 3,860,786 | 0.2% | 94.8% |  |
| JUMP_FORWARD | 3,640,048 | 0.2% | 95.1% |  |
| BINARY_OP | 3,636,679 | 0.2% | 95.3% |  |
| CALL_KW | 3,498,840 | 0.2% | 95.5% |  |
| FOR_ITER_LIST | 3,441,679 | 0.2% | 95.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,296,331 | 0.2% | 95.9% |  |
| LOAD_ATTR_PROPERTY | 2,729,485 | 0.2% | 96.1% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 2,423,504 | 0.2% | 96.3% | 0.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,251,145 | 0.1% | 96.4% | 0.1% |
| LOAD_FAST_AND_CLEAR | 2,170,425 | 0.1% | 96.5% |  |
| BEFORE_WITH | 2,150,320 | 0.1% | 96.7% |  |
| BINARY_OP_SUBTRACT_INT | 1,946,370 | 0.1% | 96.8% |  |
| CALL_BUILTIN_FAST | 1,939,644 | 0.1% | 96.9% | 0.0% |
| COMPARE_OP_FLOAT | 1,712,017 | 0.1% | 97.0% | 0.1% |
| TO_BOOL_INT | 1,703,915 | 0.1% | 97.1% | 0.0% |
| CALL_BUILTIN_O | 1,585,428 | 0.1% | 97.2% | 0.1% |
| EXTENDED_ARG | 1,530,911 | 0.1% | 97.3% |  |
| TO_BOOL_LIST | 1,516,687 | 0.1% | 97.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,486,586 | 0.1% | 97.5% |  |
| YIELD_VALUE | 1,483,538 | 0.1% | 97.6% |  |
| COMPARE_OP | 1,460,510 | 0.1% | 97.7% |  |
| BINARY_SUBSCR | 1,432,242 | 0.1% | 97.8% |  |
| STORE_ATTR_WITH_HINT | 1,418,730 | 0.1% | 97.9% | 0.3% |
| DELETE_SUBSCR | 1,400,419 | 0.1% | 98.0% |  |
| SET_FUNCTION_ATTRIBUTE | 1,341,914 | 0.1% | 98.1% |  |
| MAKE_FUNCTION | 1,312,155 | 0.1% | 98.1% |  |
| UNPACK_SEQUENCE_TUPLE | 1,242,269 | 0.1% | 98.2% |  |
| BINARY_OP_ADD_FLOAT | 1,165,727 | 0.1% | 98.3% | 0.1% |
| BUILD_CONST_KEY_MAP | 1,158,484 | 0.1% | 98.4% |  |
| STORE_ATTR | 1,048,227 | 0.1% | 98.4% |  |
| BINARY_SUBSCR_LIST_INT | 929,607 | 0.1% | 98.5% | 0.1% |
| RETURN_GENERATOR | 911,470 | 0.1% | 98.6% |  |
| PUSH_EXC_INFO | 861,056 | 0.1% | 98.6% |  |
| POP_EXCEPT | 861,049 | 0.1% | 98.7% |  |
| TO_BOOL_ALWAYS_TRUE | 831,294 | 0.1% | 98.7% | 0.9% |
| STORE_FAST_LOAD_FAST | 823,869 | 0.1% | 98.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 814,910 | 0.1% | 98.8% | 0.3% |
| STORE_DEREF | 802,256 | 0.1% | 98.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 771,268 | 0.0% | 98.9% |  |
| CHECK_EXC_MATCH | 727,808 | 0.0% | 99.0% |  |
| BINARY_SLICE | 722,282 | 0.0% | 99.0% |  |
| MAP_ADD | 688,163 | 0.0% | 99.1% |  |
| CALL_LIST_APPEND | 658,636 | 0.0% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 650,362 | 0.0% | 99.1% |  |
| LOAD_SUPER_ATTR_METHOD | 638,492 | 0.0% | 99.2% |  |
| BUILD_SET | 601,889 | 0.0% | 99.2% |  |
| SEND_GEN | 589,739 | 0.0% | 99.3% | 0.0% |
| BINARY_SUBSCR_GETITEM | 584,546 | 0.0% | 99.3% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 582,648 | 0.0% | 99.3% |  |
| TO_BOOL_STR | 563,229 | 0.0% | 99.4% | 0.3% |
| STORE_SUBSCR | 542,621 | 0.0% | 99.4% |  |
| LIST_APPEND | 519,492 | 0.0% | 99.4% |  |
| FORMAT_SIMPLE | 517,289 | 0.0% | 99.5% |  |
| END_SEND | 516,910 | 0.0% | 99.5% |  |
| GET_AWAITABLE | 515,794 | 0.0% | 99.5% |  |
| SEND | 514,156 | 0.0% | 99.6% |  |
| BUILD_STRING | 465,833 | 0.0% | 99.6% |  |
| LOAD_ATTR_CLASS | 458,923 | 0.0% | 99.6% | 0.5% |
| FOR_ITER_RANGE | 453,361 | 0.0% | 99.6% |  |
| CALL_TUPLE_1 | 363,274 | 0.0% | 99.7% |  |
| RERAISE | 359,384 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 337,228 | 0.0% | 99.7% | 0.4% |
| DELETE_FAST | 334,853 | 0.0% | 99.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 297,173 | 0.0% | 99.8% | 0.3% |
| EXIT_INIT_CHECK | 296,093 | 0.0% | 99.8% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 263,960 | 0.0% | 99.8% |  |
| BINARY_OP_ADD_UNICODE | 260,053 | 0.0% | 99.8% | 0.1% |
| CALL_STR_1 | 258,378 | 0.0% | 99.8% |  |
| LOAD_FAST_CHECK | 248,904 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 242,808 | 0.0% | 99.9% | 0.2% |
| BINARY_OP_MULTIPLY_FLOAT | 206,954 | 0.0% | 99.9% | 1.1% |
| IMPORT_FROM | 202,425 | 0.0% | 99.9% |  |
| IMPORT_NAME | 201,685 | 0.0% | 99.9% |  |
| WITH_EXCEPT_START | 178,430 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 177,399 | 0.0% | 99.9% |  |
| SET_ADD | 176,880 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 167,583 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 130,275 | 0.0% | 99.9% | 30.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 120,880 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 109,087 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 97,891 | 0.0% | 100.0% | 0.4% |
| SET_UPDATE | 88,020 | 0.0% | 100.0% |  |
| UNPACK_EX | 88,000 | 0.0% | 100.0% |  |
| UNARY_INVERT | 83,488 | 0.0% | 100.0% |  |
| BUILD_SLICE | 82,921 | 0.0% | 100.0% |  |
| DICT_UPDATE | 42,391 | 0.0% | 100.0% |  |
| STORE_SLICE | 40,683 | 0.0% | 100.0% |  |
| RESUME | 26,151 | 0.0% | 100.0% | 22.3% |
| STORE_NAME | 14,380 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 10,732 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 8,828 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 8,716 | 0.0% | 100.0% |  |
| DELETE_ATTR | 8,435 | 0.0% | 100.0% |  |
| LOAD_NAME | 6,720 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 5,932 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,964 | 0.0% | 100.0% | 89.8% |
| LOAD_SUPER_ATTR_ATTR | 3,932 | 0.0% | 100.0% |  |
| END_FOR | 3,692 | 0.0% | 100.0% |  |
| UNARY_NOT | 2,700 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,840 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 1,760 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 1,220 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 940 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 886 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 460 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 440 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 50,314,418 | 3.2% | 3.2% |
| STORE_FAST LOAD_FAST | 44,985,809 | 2.8% | 6.0% |
| RESUME_CHECK LOAD_FAST | 44,660,881 | 2.8% | 8.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 34,243,465 | 2.2% | 11.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 30,415,001 | 1.9% | 12.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 28,606,857 | 1.8% | 14.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 22,725,579 | 1.4% | 16.2% |
| CACHE RESUME_CHECK | 22,016,051 | 1.4% | 17.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 19,642,425 | 1.2% | 18.8% |
| LOAD_CONST LOAD_FAST | 18,474,020 | 1.2% | 20.0% |
| RETURN_VALUE INTERPRETER_EXIT | 17,467,133 | 1.1% | 21.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 17,405,727 | 1.1% | 22.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 15,207,010 | 1.0% | 23.1% |
| POP_TOP LOAD_FAST | 15,020,935 | 0.9% | 24.1% |
| LOAD_FAST LOAD_ATTR | 14,442,716 | 0.9% | 25.0% |
| RETURN_VALUE STORE_FAST | 13,915,678 | 0.9% | 25.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 13,636,306 | 0.9% | 26.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 13,541,453 | 0.9% | 27.6% |
| LOAD_FAST LOAD_CONST | 12,612,950 | 0.8% | 28.4% |
| RETURN_CONST POP_TOP | 12,350,192 | 0.8% | 29.2% |
| PUSH_NULL LOAD_FAST | 12,195,494 | 0.8% | 29.9% |
| LOAD_FAST RETURN_VALUE | 11,884,028 | 0.8% | 30.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 10,842,768 | 0.7% | 31.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 10,444,704 | 0.7% | 32.0% |
| LOAD_FAST CALL | 10,142,606 | 0.6% | 32.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 9,616,089 | 0.6% | 33.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,241,856 | 0.6% | 33.9% |
| DICT_MERGE CALL_FUNCTION_EX | 8,838,425 | 0.6% | 34.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,714,688 | 0.6% | 35.0% |
| BUILD_MAP LOAD_FAST | 8,607,337 | 0.5% | 35.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 8,601,823 | 0.5% | 36.1% |
| BUILD_LIST LOAD_FAST | 8,403,568 | 0.5% | 36.6% |
| LOAD_FAST DICT_MERGE | 8,232,932 | 0.5% | 37.1% |
| NOP LOAD_FAST | 8,213,466 | 0.5% | 37.6% |
| LOAD_FAST STORE_ATTR_SLOT | 8,153,655 | 0.5% | 38.1% |
| LOAD_FAST PUSH_NULL | 8,046,016 | 0.5% | 38.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 7,953,000 | 0.5% | 39.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 7,645,672 | 0.5% | 39.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 7,610,805 | 0.5% | 40.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 7,607,782 | 0.5% | 40.6% |
| LOAD_FAST CALL_TYPE_1 | 7,602,649 | 0.5% | 41.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 7,536,196 | 0.5% | 41.6% |
| STORE_FAST NOP | 7,418,472 | 0.5% | 42.0% |
| RETURN_VALUE RETURN_VALUE | 7,359,013 | 0.5% | 42.5% |
| IS_OP POP_JUMP_IF_FALSE | 7,322,994 | 0.5% | 42.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,321,113 | 0.5% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 7,308,190 | 0.5% | 43.9% |
| LOAD_FAST BUILD_LIST | 7,028,530 | 0.4% | 44.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 7,016,571 | 0.4% | 44.8% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 6,962,723 | 0.4% | 45.2% |
| LOAD_FAST LIST_EXTEND | 6,683,549 | 0.4% | 45.6% |
| LOAD_CONST LOAD_CONST | 6,557,641 | 0.4% | 46.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 6,542,258 | 0.4% | 46.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 6,525,035 | 0.4% | 46.9% |
| RETURN_CONST INTERPRETER_EXIT | 6,381,155 | 0.4% | 47.3% |
| BINARY_SUBSCR_DICT STORE_FAST | 6,331,932 | 0.4% | 47.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,287,867 | 0.4% | 48.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 6,242,869 | 0.4% | 48.5% |
| POP_TOP RETURN_CONST | 6,074,641 | 0.4% | 48.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 5,934,513 | 0.4% | 49.2% |
| TO_BOOL POP_JUMP_IF_FALSE | 5,789,165 | 0.4% | 49.6% |
| CALL_INTRINSIC_1 BUILD_MAP | 5,758,910 | 0.4% | 49.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,734,129 | 0.4% | 50.3% |
| CALL_FUNCTION_EX RESUME_CHECK | 5,704,450 | 0.4% | 50.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 5,703,981 | 0.4% | 51.0% |
| FOR_ITER_TUPLE STORE_FAST | 5,676,244 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 5,527,991 | 0.3% | 51.7% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_NO_DICT | 5,452,970 | 0.3% | 52.1% |
| POP_TOP RETURN_VALUE | 5,407,503 | 0.3% | 52.4% |
| GET_ITER FOR_ITER_TUPLE | 5,401,819 | 0.3% | 52.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 5,391,102 | 0.3% | 53.1% |
| RETURN_VALUE TO_BOOL_BOOL | 5,343,717 | 0.3% | 53.4% |
| RESUME_CHECK NOP | 5,266,152 | 0.3% | 53.8% |
| CALL POP_TOP | 5,238,870 | 0.3% | 54.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,195,581 | 0.3% | 54.4% |
| POP_TOP ENTER_EXECUTOR | 5,150,974 | 0.3% | 54.8% |
| LOAD_CONST STORE_FAST | 5,124,816 | 0.3% | 55.1% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 5,087,499 | 0.3% | 55.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 5,067,575 | 0.3% | 55.7% |
| CALL RETURN_VALUE | 5,056,156 | 0.3% | 56.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 5,032,234 | 0.3% | 56.4% |
| NOP LOAD_FAST_LOAD_FAST | 4,977,043 | 0.3% | 56.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 4,972,121 | 0.3% | 57.0% |
| LOAD_FAST SWAP | 4,935,696 | 0.3% | 57.3% |
| STORE_ATTR_SLOT LOAD_CONST | 4,874,295 | 0.3% | 57.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_DICT | 4,742,673 | 0.3% | 57.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_BUILTIN | 4,665,280 | 0.3% | 58.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,644,313 | 0.3% | 58.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,628,192 | 0.3% | 58.8% |
| GET_ITER FOR_ITER | 4,605,482 | 0.3% | 59.1% |
| LOAD_FAST_LOAD_FAST IS_OP | 4,601,119 | 0.3% | 59.4% |
| LOAD_CONST COMPARE_OP_INT | 4,586,737 | 0.3% | 59.7% |
| CALL STORE_FAST | 4,565,497 | 0.3% | 59.9% |
| SWAP POP_TOP | 4,526,577 | 0.3% | 60.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 4,523,068 | 0.3% | 60.5% |
| LOAD_ATTR GET_ITER | 4,521,400 | 0.3% | 60.8% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 4,520,157 | 0.3% | 61.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 4,300,444 | 0.3% | 61.4% |
| LOAD_FAST TO_BOOL | 4,248,555 | 0.3% | 61.6% |
| LOAD_FAST COPY | 4,204,385 | 0.3% | 61.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 463,231 | 64.1% |
| LOAD_FAST | 215,668 | 29.9% |
| BINARY_OP_ADD_INT | 43,003 | 6.0% |
| LOAD_ATTR_INSTANCE_VALUE | 300 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 112,105 | 15.5% |
| CALL_BUILTIN_CLASS | 89,170 | 12.3% |
| CALL_METHOD_DESCRIPTOR_O | 87,960 | 12.2% |
| CALL_PY_WITH_DEFAULTS | 87,960 | 12.2% |
| STORE_FAST | 71,648 | 9.9% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,383 | 99.3% |
| LOAD_FAST | 160 | 0.4% |
| BINARY_OP_ADD_INT | 140 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,383 | 99.3% |
| LOAD_CONST | 160 | 0.4% |
| ENTER_EXECUTOR | 140 | 0.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 22,016,051 | 86.8% |
| COPY_FREE_VARS | 2,331,323 | 9.2% |
| POP_TOP | 580,287 | 2.3% |
| MAKE_CELL | 267,168 | 1.1% |
| RETURN_GENERATOR | 129,510 | 0.5% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,010 | 93.3% |
| LOAD_ATTR_WITH_HINT | 462 | 4.3% |
| CALL | 160 | 1.5% |
| CALL_KW | 80 | 0.7% |
| LOAD_ATTR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 10,732 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,587,597 | 73.8% |
| LOAD_GLOBAL_MODULE | 186,281 | 8.7% |
| LOAD_ATTR_WITH_HINT | 176,780 | 8.2% |
| LOAD_FAST | 176,240 | 8.2% |
| CALL | 11,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,145,361 | 99.8% |
| STORE_FAST | 4,959 | 0.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 108,760 | 90.0% |
| LOAD_FAST_LOAD_FAST | 10,000 | 8.3% |
| LOAD_CONST | 1,720 | 1.4% |
| BINARY_SUBSCR_STR_INT | 220 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 118,240 | 97.8% |
| LOAD_GLOBAL_MODULE | 1,720 | 1.4% |
| LOAD_FAST | 360 | 0.3% |
| JUMP_BACKWARD | 320 | 0.3% |
| STORE_FAST | 220 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 852,648 | 59.5% |
| COPY | 354,385 | 24.7% |
| LOAD_CONST | 217,017 | 15.2% |
| BINARY_SUBSCR | 4,792 | 0.3% |
| BUILD_SLICE | 1,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 344,260 | 24.0% |
| LOAD_CONST | 267,011 | 18.6% |
| LOAD_FAST | 176,983 | 12.4% |
| STORE_FAST | 176,676 | 12.3% |
| LOAD_ATTR_METHOD_NO_DICT | 162,703 | 11.4% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 643,400 | 88.4% |
| LOAD_ATTR_MODULE | 78,346 | 10.8% |
| BUILD_TUPLE | 4,882 | 0.7% |
| LOAD_GLOBAL | 724 | 0.1% |
| LOAD_GLOBAL_MODULE | 362 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 727,808 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 886 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 644 | 72.7% |
| JUMP_BACKWARD | 242 | 27.3% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 964,413 | 68.9% |
| LOAD_FAST_LOAD_FAST | 265,425 | 19.0% |
| LOAD_ATTR_SLOT | 88,040 | 6.3% |
| BUILD_SLICE | 81,721 | 5.8% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 433,856 | 33.1% |
| PUSH_EXC_INFO | 352,000 | 26.8% |
| RETURN_CONST | 258,239 | 19.7% |
| LOAD_FAST_LOAD_FAST | 88,555 | 6.7% |
| LOAD_CONST | 88,507 | 6.7% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,692 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,450 | 39.3% |
| LOAD_CONST | 880 | 23.8% |
| STORE_FAST | 742 | 20.1% |
| SWAP | 300 | 8.1% |
| RETURN_CONST | 180 | 4.9% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 268,537 | 52.0% |
| SEND | 190,301 | 36.8% |
| RETURN_CONST | 57,670 | 11.2% |
| JUMP_BACKWARD | 242 | 0.0% |
| SEND_GEN | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 301,131 | 58.3% |
| POP_TOP | 117,021 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 88,242 | 17.1% |
| SWAP | 10,010 | 1.9% |
| LOAD_DEREF | 163 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 296,093 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 296,093 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 373,874 | 72.3% |
| LOAD_FAST | 130,707 | 25.3% |
| CONVERT_VALUE | 8,828 | 1.7% |
| LOAD_GLOBAL_MODULE | 3,340 | 0.6% |
| CALL_LEN | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 421,156 | 81.4% |
| LOAD_CONST | 54,110 | 10.5% |
| LOAD_FAST | 42,023 | 8.1% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,521,400 | 32.4% |
| LOAD_FAST | 3,403,332 | 24.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,530,772 | 18.2% |
| LOAD_ATTR_SLOT | 1,450,262 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 911,442 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 5,401,819 | 38.8% |
| FOR_ITER | 4,605,482 | 33.0% |
| FOR_ITER_LIST | 2,075,762 | 14.9% |
| LOAD_FAST_AND_CLEAR | 1,386,575 | 10.0% |
| CALL_PY_EXACT_ARGS | 256,033 | 1.8% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,740 | 98.9% |
| LOAD_ATTR | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,760 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 17,467,133 | 69.6% |
| RETURN_CONST | 6,381,155 | 25.4% |
| YIELD_VALUE | 1,124,848 | 4.5% |
| RETURN_GENERATOR | 129,673 | 0.5% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 540 | 57.4% |
| POP_TOP | 300 | 31.9% |
| POP_JUMP_IF_FALSE | 40 | 4.3% |
| STORE_SUBSCR | 20 | 2.1% |
| JUMP_BACKWARD | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 940 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,312,155 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,129,170 | 86.1% |
| STORE_DEREF | 88,007 | 6.7% |
| CALL | 41,303 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 40,993 | 3.1% |
| LOAD_FAST | 6,580 | 0.5% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,418,472 | 43.0% |
| RESUME_CHECK | 5,266,152 | 30.5% |
| POP_JUMP_IF_FALSE | 1,495,395 | 8.7% |
| STORE_ATTR_INSTANCE_VALUE | 597,929 | 3.5% |
| POP_JUMP_IF_TRUE | 537,931 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,213,466 | 47.6% |
| LOAD_FAST_LOAD_FAST | 4,977,043 | 28.8% |
| LOAD_GLOBAL_MODULE | 2,007,691 | 11.6% |
| LOAD_CONST | 501,518 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 478,983 | 2.8% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 519,861 | 60.4% |
| COPY | 179,231 | 20.8% |
| STORE_FAST | 144,773 | 16.8% |
| STORE_SUBSCR_DICT | 9,277 | 1.1% |
| SWAP | 6,245 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 436,290 | 50.7% |
| RERAISE | 179,231 | 20.8% |
| EXTENDED_ARG | 129,321 | 15.0% |
| DELETE_FAST | 40,623 | 4.7% |
| LOAD_CONST | 40,295 | 4.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 12,350,192 | 28.8% |
| CALL_METHOD_DESCRIPTOR_O | 7,645,672 | 17.9% |
| CALL | 5,238,870 | 12.2% |
| SWAP | 4,526,577 | 10.6% |
| CALL_FUNCTION_EX | 2,968,579 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,020,935 | 35.1% |
| RETURN_CONST | 6,074,641 | 14.2% |
| RETURN_VALUE | 5,407,503 | 12.6% |
| ENTER_EXECUTOR | 5,150,974 | 12.0% |
| LOAD_FAST_LOAD_FAST | 2,439,897 | 5.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 352,000 | 40.9% |
| BINARY_SUBSCR_DICT | 187,727 | 21.8% |
| CALL | 97,156 | 11.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 88,104 | 10.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 78,565 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 601,359 | 69.8% |
| WITH_EXCEPT_START | 178,430 | 20.7% |
| LOAD_GLOBAL_MODULE | 79,465 | 9.2% |
| LOAD_GLOBAL | 1,683 | 0.2% |
| DELETE_FAST | 79 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,046,016 | 41.1% |
| LOAD_ATTR_MODULE | 6,242,869 | 31.9% |
| LOAD_ATTR | 4,035,298 | 20.6% |
| LOAD_DEREF | 931,533 | 4.8% |
| RETURN_VALUE | 226,476 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,195,494 | 62.3% |
| LOAD_FAST_LOAD_FAST | 2,465,680 | 12.6% |
| CALL | 2,465,275 | 12.6% |
| LOAD_CONST | 1,192,665 | 6.1% |
| CALL_BUILTIN_CLASS | 437,646 | 2.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 297,545 | 32.6% |
| CALL_KW | 131,214 | 14.4% |
| CACHE | 129,510 | 14.2% |
| CALL_PY_EXACT_ARGS | 103,277 | 11.3% |
| CALL_PY_WITH_DEFAULTS | 84,695 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 294,403 | 32.3% |
| CALL_TUPLE_1 | 176,440 | 19.4% |
| INTERPRETER_EXIT | 129,673 | 14.2% |
| CALL_BUILTIN_O | 118,284 | 13.0% |
| CALL | 83,442 | 9.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,884,028 | 21.9% |
| RETURN_VALUE | 7,359,013 | 13.6% |
| POP_TOP | 5,407,503 | 10.0% |
| CALL | 5,056,156 | 9.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,860,798 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 17,467,133 | 32.2% |
| STORE_FAST | 13,915,678 | 25.6% |
| RETURN_VALUE | 7,359,013 | 13.6% |
| TO_BOOL_BOOL | 5,343,717 | 9.8% |
| LOAD_FAST | 1,509,431 | 2.8% |


</details>

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 300 | 68.2% |
| RESUME | 140 | 31.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 440 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 354,385 | 65.3% |
| LOAD_FAST | 90,807 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 88,120 | 16.2% |
| LOAD_CONST | 4,880 | 0.9% |
| STORE_SUBSCR | 1,938 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 267,473 | 49.3% |
| LOAD_CONST | 89,600 | 16.5% |
| RETURN_CONST | 89,390 | 16.5% |
| LOAD_GLOBAL_MODULE | 88,080 | 16.2% |
| STORE_SUBSCR_DICT | 3,460 | 0.6% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,248,555 | 49.6% |
| LOAD_ATTR_SLOT | 1,492,023 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,063,029 | 12.4% |
| RETURN_VALUE | 964,989 | 11.3% |
| COPY | 397,951 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,789,165 | 67.6% |
| POP_JUMP_IF_TRUE | 2,630,775 | 30.7% |
| EXTENDED_ARG | 100,300 | 1.2% |
| TO_BOOL | 21,245 | 0.2% |
| TO_BOOL_BOOL | 12,068 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 41,625 | 49.9% |
| BINARY_OP | 41,343 | 49.5% |
| LOAD_FAST | 480 | 0.6% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 83,488 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 1,180 | 96.7% |
| CALL | 20 | 1.6% |
| LOAD_FAST | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 98.4% |
| CALL_BUILTIN_CLASS | 20 | 1.6% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,060 | 39.3% |
| TO_BOOL_INT | 960 | 35.6% |
| TO_BOOL_LIST | 620 | 23.0% |
| TO_BOOL | 60 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 980 | 36.3% |
| STORE_DEREF | 880 | 32.6% |
| CALL_PY_EXACT_ARGS | 620 | 23.0% |
| RETURN_VALUE | 140 | 5.2% |
| STORE_FAST | 80 | 3.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 178,430 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 177,300 | 99.4% |
| TO_BOOL_BOOL | 960 | 0.5% |
| TO_BOOL | 170 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 714,606 | 19.6% |
| LOAD_FAST | 586,712 | 16.1% |
| LOAD_GLOBAL_MODULE | 412,002 | 11.3% |
| LOAD_ATTR_WITH_HINT | 272,849 | 7.5% |
| LOAD_CONST | 230,263 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,317,846 | 36.2% |
| TO_BOOL_INT | 567,778 | 15.6% |
| LOAD_CONST | 260,683 | 7.2% |
| COPY | 209,108 | 5.7% |
| BINARY_OP_ADD_FLOAT | 202,472 | 5.6% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,158,484 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 433,567 | 37.4% |
| RETURN_VALUE | 188,814 | 16.3% |
| CALL_LIST_APPEND | 176,880 | 15.3% |
| LOAD_FAST | 130,028 | 11.2% |
| CALL_PY_EXACT_ARGS | 89,959 | 7.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,028,530 | 64.0% |
| LOAD_ATTR_SLOT | 1,348,550 | 12.3% |
| RESUME_CHECK | 536,508 | 4.9% |
| STORE_FAST | 466,454 | 4.3% |
| SWAP | 344,006 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,403,568 | 76.6% |
| STORE_FAST | 1,268,668 | 11.6% |
| BUILD_TUPLE | 512,695 | 4.7% |
| SWAP | 383,339 | 3.5% |
| LOAD_FAST_LOAD_FAST | 184,000 | 1.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 5,758,910 | 39.5% |
| STORE_FAST | 2,585,971 | 17.7% |
| LOAD_FAST | 1,773,334 | 12.2% |
| SWAP | 785,129 | 5.4% |
| BUILD_TUPLE | 661,006 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,607,337 | 59.1% |
| STORE_FAST | 4,078,441 | 28.0% |
| SWAP | 785,129 | 5.4% |
| LOAD_GLOBAL_MODULE | 433,440 | 3.0% |
| BUILD_LIST | 248,000 | 1.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 257,440 | 42.8% |
| LOAD_GLOBAL_MODULE | 176,289 | 29.3% |
| LOAD_ATTR | 88,080 | 14.6% |
| LOAD_CONST | 80,020 | 13.3% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 257,440 | 42.8% |
| CONTAINS_OP | 176,409 | 29.3% |
| LOAD_CONST | 88,020 | 14.6% |
| BINARY_OP | 80,020 | 13.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,926 | 97.6% |
| LOAD_CONST | 1,995 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 81,721 | 98.6% |
| BINARY_SUBSCR | 1,200 | 1.4% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 421,156 | 90.4% |
| LOAD_CONST | 44,677 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 197,914 | 42.5% |
| BUILD_MAP | 88,000 | 18.9% |
| LOAD_CONST | 88,000 | 18.9% |
| LOAD_FAST | 41,883 | 9.0% |
| LOAD_FAST_LOAD_FAST | 40,543 | 8.7% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,789,632 | 30.4% |
| LOAD_FAST_LOAD_FAST | 2,406,999 | 26.2% |
| CALL | 1,423,789 | 15.5% |
| BUILD_LIST | 512,695 | 5.6% |
| LOAD_GLOBAL_BUILTIN | 458,682 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,720,132 | 29.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,549,520 | 16.9% |
| LOAD_CONST | 1,479,781 | 16.1% |
| BUILD_MAP | 661,006 | 7.2% |
| CONTAINS_OP | 554,394 | 6.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,142,606 | 37.4% |
| LOAD_GLOBAL_MODULE | 3,532,224 | 13.0% |
| LOAD_CONST | 2,588,187 | 9.5% |
| PUSH_NULL | 2,465,275 | 9.1% |
| LOAD_FAST_LOAD_FAST | 2,269,437 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,238,870 | 19.3% |
| RETURN_VALUE | 5,056,156 | 18.6% |
| STORE_FAST | 4,565,497 | 16.8% |
| RESUME_CHECK | 3,979,615 | 14.7% |
| BUILD_TUPLE | 1,423,789 | 5.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 8,838,425 | 75.4% |
| CALL_INTRINSIC_1 | 1,609,885 | 13.7% |
| LOAD_FAST | 979,083 | 8.4% |
| ENTER_EXECUTOR | 97,962 | 0.8% |
| LOAD_ATTR_INSTANCE_VALUE | 88,040 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,704,450 | 48.7% |
| POP_TOP | 2,968,579 | 25.3% |
| RETURN_VALUE | 1,155,813 | 9.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 615,920 | 5.3% |
| UNPACK_SEQUENCE_TUPLE | 431,960 | 3.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 7,953,000 | 100.0% |
| RERAISE | 1,322 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 5,758,910 | 72.4% |
| CALL_FUNCTION_EX | 1,609,885 | 20.2% |
| LOAD_CONST | 584,205 | 7.3% |
| RERAISE | 1,322 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,895,805 | 82.8% |
| ENTER_EXECUTOR | 603,035 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,542,878 | 72.7% |
| MAKE_CELL | 378,276 | 10.8% |
| STORE_FAST | 157,207 | 4.5% |
| RETURN_GENERATOR | 131,214 | 3.8% |
| RETURN_VALUE | 100,411 | 2.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 630,577 | 43.2% |
| LOAD_FAST | 184,659 | 12.6% |
| LOAD_ATTR | 179,919 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 129,121 | 8.8% |
| BINARY_OP | 97,500 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,443,487 | 98.8% |
| COMPARE_OP | 5,797 | 0.4% |
| POP_JUMP_IF_TRUE | 4,959 | 0.3% |
| COMPARE_OP_INT | 3,944 | 0.3% |
| COMPARE_OP_STR | 1,583 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,067,522 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,673,899 | 26.4% |
| LOAD_ATTR_WITH_HINT | 1,488,971 | 14.7% |
| LOAD_GLOBAL_MODULE | 633,435 | 6.3% |
| BUILD_TUPLE | 554,394 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,536,196 | 74.4% |
| RETURN_VALUE | 1,146,110 | 11.3% |
| POP_JUMP_IF_TRUE | 743,310 | 7.3% |
| COPY | 522,420 | 5.2% |
| SWAP | 176,336 | 1.7% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,168 | 58.5% |
| LOAD_FAST | 1,680 | 19.0% |
| BINARY_SLICE | 1,600 | 18.1% |
| LOAD_GLOBAL_MODULE | 280 | 3.2% |
| LOAD_ATTR | 100 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 8,828 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,204,385 | 40.6% |
| COPY | 1,380,140 | 13.3% |
| CALL_BUILTIN_FAST | 682,617 | 6.6% |
| LOAD_ATTR_SLOT | 608,664 | 5.9% |
| CONTAINS_OP | 522,420 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,919,393 | 18.5% |
| LOAD_ATTR_WITH_HINT | 1,407,840 | 13.6% |
| COPY | 1,380,140 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,361,456 | 13.1% |
| BINARY_SUBSCR_DICT | 1,025,635 | 9.9% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,331,323 | 60.4% |
| CALL_PY_EXACT_ARGS | 758,378 | 19.6% |
| CALL | 411,663 | 10.7% |
| BINARY_SUBSCR_GETITEM | 263,960 | 6.8% |
| ENTER_EXECUTOR | 87,200 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,559,792 | 92.2% |
| RETURN_GENERATOR | 297,545 | 7.7% |
| MAKE_CELL | 1,762 | 0.0% |
| RESUME | 1,687 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,115 | 96.2% |
| LOAD_GLOBAL_MODULE | 280 | 3.3% |
| LOAD_GLOBAL | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,870 | 45.9% |
| NOP | 1,715 | 20.3% |
| PUSH_EXC_INFO | 1,650 | 19.6% |
| RETURN_CONST | 1,040 | 12.3% |
| LOAD_GLOBAL_MODULE | 120 | 1.4% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 88,336 | 26.4% |
| CALL | 81,486 | 24.3% |
| STORE_FAST | 42,843 | 12.8% |
| NOP | 40,865 | 12.2% |
| POP_EXCEPT | 40,623 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 90,548 | 27.0% |
| RETURN_CONST | 81,488 | 24.3% |
| RETURN_VALUE | 81,486 | 24.3% |
| LOAD_FAST | 40,628 | 12.1% |
| ENTER_EXECUTOR | 38,973 | 11.6% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,232,932 | 93.1% |
| RETURN_VALUE | 433,600 | 4.9% |
| LOAD_ATTR_INSTANCE_VALUE | 88,851 | 1.0% |
| LOAD_DEREF | 40,590 | 0.5% |
| LOAD_GLOBAL_MODULE | 40,523 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 8,838,425 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,523 | 95.6% |
| BUILD_MAP | 724 | 1.7% |
| RETURN_VALUE | 644 | 1.5% |
| MAP_ADD | 240 | 0.6% |
| BUILD_CONST_KEY_MAP | 160 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,267 | 97.3% |
| STORE_FAST | 724 | 1.7% |
| LOAD_DEREF | 160 | 0.4% |
| RETURN_VALUE | 80 | 0.2% |
| BUILD_MAP | 80 | 0.2% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,150,974 | 45.5% |
| POP_JUMP_IF_FALSE | 1,467,625 | 13.0% |
| STORE_SUBSCR_DICT | 929,420 | 8.2% |
| MAP_ADD | 673,343 | 6.0% |
| POP_JUMP_IF_TRUE | 647,013 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,571,036 | 13.9% |
| RESUME_CHECK | 1,483,760 | 13.1% |
| FOR_ITER_LIST | 1,269,479 | 11.2% |
| FOR_ITER_TUPLE | 1,192,031 | 10.5% |
| LOAD_FAST | 954,579 | 8.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 431,980 | 28.2% |
| COMPARE_OP_INT | 352,562 | 23.0% |
| IS_OP | 176,160 | 11.5% |
| POP_EXCEPT | 129,321 | 8.4% |
| POP_JUMP_IF_FALSE | 102,194 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 662,955 | 43.3% |
| JUMP_FORWARD | 441,280 | 28.8% |
| ENTER_EXECUTOR | 313,779 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 88,020 | 5.7% |
| LOAD_ATTR | 6,880 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,605,482 | 75.8% |
| SWAP | 1,205,310 | 19.8% |
| LOAD_FAST | 212,696 | 3.5% |
| JUMP_BACKWARD | 34,876 | 0.6% |
| FOR_ITER | 18,232 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,514,845 | 24.9% |
| LOAD_FAST | 1,347,273 | 22.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 821,492 | 13.5% |
| RETURN_CONST | 802,712 | 13.2% |
| STORE_FAST_LOAD_FAST | 644,029 | 10.6% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 294,403 | 57.1% |
| RETURN_VALUE | 179,819 | 34.9% |
| LOAD_FAST | 19,623 | 3.8% |
| BEFORE_ASYNC_WITH | 10,732 | 2.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,612 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 515,794 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 199,805 | 98.7% |
| STORE_NAME | 1,740 | 0.9% |
| STORE_FAST | 880 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 198,065 | 97.8% |
| STORE_NAME | 4,200 | 2.1% |
| PUSH_EXC_INFO | 160 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 201,685 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 199,805 | 99.1% |
| STORE_FAST | 1,180 | 0.6% |
| STORE_NAME | 660 | 0.3% |
| PUSH_EXC_INFO | 40 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,601,119 | 49.3% |
| LOAD_GLOBAL_BUILTIN | 2,533,720 | 27.1% |
| LOAD_GLOBAL_MODULE | 1,102,486 | 11.8% |
| LOAD_CONST | 389,257 | 4.2% |
| LOAD_ATTR_INSTANCE_VALUE | 255,784 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,322,994 | 78.4% |
| POP_JUMP_IF_TRUE | 1,175,165 | 12.6% |
| COPY | 359,448 | 3.8% |
| RETURN_VALUE | 306,888 | 3.3% |
| EXTENDED_ARG | 176,160 | 1.9% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 109,311 | 61.6% |
| STORE_SUBSCR_DICT | 12,580 | 7.1% |
| POP_JUMP_IF_TRUE | 11,780 | 6.6% |
| POP_JUMP_IF_FALSE | 8,195 | 4.6% |
| LIST_APPEND | 6,939 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 92,979 | 52.4% |
| FOR_ITER | 34,876 | 19.7% |
| FOR_ITER_LIST | 20,342 | 11.5% |
| FOR_ITER_TUPLE | 8,140 | 4.6% |
| LOAD_FAST | 7,641 | 4.3% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 581,415 | 99.8% |
| RESUME | 1,233 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 319,017 | 54.8% |
| SEND_GEN | 263,631 | 45.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,419,758 | 39.0% |
| POP_TOP | 1,064,788 | 29.3% |
| EXTENDED_ARG | 441,280 | 12.1% |
| POP_JUMP_IF_FALSE | 194,878 | 5.4% |
| STORE_SUBSCR_DICT | 96,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,508,246 | 68.9% |
| LOAD_GLOBAL_BUILTIN | 432,563 | 11.9% |
| NOP | 258,726 | 7.1% |
| LOAD_CONST | 211,994 | 5.8% |
| LOAD_GLOBAL_MODULE | 100,302 | 2.8% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 160,340 | 30.9% |
| RETURN_VALUE | 128,603 | 24.8% |
| BINARY_SUBSCR_DICT | 88,120 | 17.0% |
| BINARY_OP_ADD_UNICODE | 87,980 | 16.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 46,880 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 512,553 | 98.7% |
| JUMP_BACKWARD | 6,939 | 1.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,683,549 | 83.2% |
| LOAD_ATTR_SLOT | 1,348,550 | 16.8% |
| BINARY_SLICE | 1,760 | 0.0% |
| LOAD_DEREF | 207 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 7,953,000 | 99.0% |
| STORE_FAST | 81,086 | 1.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,442,716 | 71.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,446,601 | 7.2% |
| LOAD_ATTR_SLOT | 1,350,496 | 6.7% |
| LOAD_GLOBAL_MODULE | 1,181,066 | 5.9% |
| LOAD_DEREF | 908,295 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,521,400 | 22.4% |
| PUSH_NULL | 4,035,298 | 20.0% |
| LOAD_FAST | 3,307,312 | 16.4% |
| LOAD_FAST_LOAD_FAST | 1,958,081 | 9.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,171,497 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,612,950 | 19.1% |
| LOAD_CONST | 6,557,641 | 9.9% |
| POP_JUMP_IF_FALSE | 5,734,129 | 8.7% |
| STORE_ATTR_SLOT | 4,874,295 | 7.4% |
| LOAD_ATTR_SLOT | 2,928,869 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,474,020 | 27.9% |
| LOAD_CONST | 6,557,641 | 9.9% |
| STORE_FAST | 5,124,816 | 7.8% |
| COMPARE_OP_INT | 4,586,737 | 6.9% |
| COMPARE_OP_STR | 3,953,785 | 6.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,120,484 | 12.8% |
| LOAD_GLOBAL_BUILTIN | 1,023,563 | 11.7% |
| POP_TOP | 866,118 | 9.9% |
| POP_JUMP_IF_FALSE | 768,740 | 8.8% |
| LOAD_GLOBAL_MODULE | 739,980 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,053,928 | 12.1% |
| PUSH_NULL | 931,533 | 10.7% |
| CALL_PY_EXACT_ARGS | 916,935 | 10.5% |
| LOAD_ATTR | 908,295 | 10.4% |
| LOAD_DEREF | 708,679 | 8.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 44,985,809 | 14.0% |
| RESUME_CHECK | 44,660,881 | 13.9% |
| POP_JUMP_IF_FALSE | 34,243,465 | 10.7% |
| LOAD_GLOBAL_BUILTIN | 22,725,579 | 7.1% |
| LOAD_CONST | 18,474,020 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 50,314,418 | 15.7% |
| LOAD_ATTR_SLOT | 30,415,001 | 9.5% |
| LOAD_ATTR_WITH_HINT | 17,405,727 | 5.4% |
| LOAD_ATTR | 14,442,716 | 4.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,541,453 | 4.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,386,575 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,850 | 36.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,386,575 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,850 | 36.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 88,020 | 35.4% |
| STORE_ATTR_SLOT | 87,980 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 46,272 | 18.6% |
| POP_TOP | 10,605 | 4.3% |
| LOAD_FAST_CHECK | 5,078 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,908 | 71.5% |
| CALL_METHOD_DESCRIPTOR_O | 45,432 | 18.3% |
| POP_JUMP_IF_NOT_NONE | 9,460 | 3.8% |
| LOAD_CONST | 5,626 | 2.3% |
| LOAD_FAST_CHECK | 5,078 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,241,856 | 19.7% |
| NOP | 4,977,043 | 10.6% |
| STORE_ATTR_SLOT | 4,105,028 | 8.8% |
| POP_JUMP_IF_FALSE | 2,750,150 | 5.9% |
| RESUME_CHECK | 2,675,457 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,525,035 | 13.9% |
| LOAD_FAST | 5,527,991 | 11.8% |
| BINARY_SUBSCR_DICT | 4,742,673 | 10.1% |
| IS_OP | 4,601,119 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 3,653,169 | 7.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,917 | 11.8% |
| POP_JUMP_IF_FALSE | 11,211 | 10.3% |
| LOAD_FAST | 10,699 | 9.8% |
| RESUME_CHECK | 7,227 | 6.6% |
| RESUME | 7,099 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,601 | 32.6% |
| LOAD_GLOBAL_BUILTIN | 18,803 | 17.2% |
| LOAD_FAST | 16,140 | 14.8% |
| LOAD_ATTR | 14,226 | 13.0% |
| CALL | 7,348 | 6.7% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,420 | 50.9% |
| RESUME | 940 | 14.0% |
| STORE_NAME | 920 | 13.7% |
| LOAD_NAME | 900 | 13.4% |
| POP_TOP | 200 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,300 | 34.2% |
| STORE_NAME | 1,060 | 15.8% |
| LOAD_NAME | 900 | 13.4% |
| CALL | 620 | 9.2% |
| LOAD_ATTR | 600 | 8.9% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,640 | 89.1% |
| EXTENDED_ARG | 120 | 6.5% |
| LOAD_DEREF | 80 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 720 | 39.1% |
| CALL | 300 | 16.3% |
| LOAD_FAST | 260 | 14.1% |
| LOAD_SUPER_ATTR_ATTR | 220 | 12.0% |
| PUSH_NULL | 160 | 8.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,058,184 | 49.4% |
| CALL_PY_WITH_DEFAULTS | 721,432 | 17.3% |
| CALL_PY_EXACT_ARGS | 651,827 | 15.6% |
| CALL_KW | 378,276 | 9.1% |
| CACHE | 267,168 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,058,184 | 49.4% |
| RESUME_CHECK | 2,025,933 | 48.6% |
| RETURN_GENERATOR | 82,378 | 2.0% |
| RESUME | 1,540 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 249,280 | 36.2% |
| STORE_FAST | 168,160 | 24.4% |
| RETURN_VALUE | 88,220 | 12.8% |
| CALL_KW | 88,000 | 12.8% |
| LOAD_ATTR_SLOT | 80,100 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 673,343 | 97.8% |
| LOAD_CONST | 9,120 | 1.3% |
| JUMP_BACKWARD | 5,140 | 0.7% |
| DICT_UPDATE | 240 | 0.0% |
| BUILD_MAP | 160 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 19,642,425 | 30.9% |
| CONTAINS_OP | 7,536,196 | 11.9% |
| IS_OP | 7,322,994 | 11.5% |
| COMPARE_OP_INT | 7,016,571 | 11.1% |
| TO_BOOL | 5,789,165 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,243,465 | 54.0% |
| LOAD_CONST | 5,734,129 | 9.0% |
| LOAD_GLOBAL_MODULE | 5,703,981 | 9.0% |
| RETURN_CONST | 5,032,234 | 7.9% |
| LOAD_GLOBAL_BUILTIN | 2,844,246 | 4.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,644,313 | 70.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,480,266 | 22.6% |
| LOAD_DEREF | 315,925 | 4.8% |
| LOAD_ATTR_WITH_HINT | 95,944 | 1.5% |
| LOAD_GLOBAL_MODULE | 2,922 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,628,192 | 70.6% |
| RETURN_CONST | 675,069 | 10.3% |
| LOAD_GLOBAL_MODULE | 265,027 | 4.0% |
| NOP | 232,660 | 3.6% |
| LOAD_CONST | 203,080 | 3.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,523,068 | 73.8% |
| LOAD_ATTR_INSTANCE_VALUE | 947,993 | 15.5% |
| LOAD_DEREF | 363,336 | 5.9% |
| LOAD_GLOBAL_MODULE | 92,789 | 1.5% |
| EXTENDED_ARG | 88,020 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,149,497 | 35.1% |
| LOAD_FAST_LOAD_FAST | 1,247,718 | 20.4% |
| LOAD_GLOBAL_MODULE | 1,242,062 | 20.3% |
| LOAD_GLOBAL_BUILTIN | 579,422 | 9.5% |
| RETURN_CONST | 421,547 | 6.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,195,581 | 39.8% |
| TO_BOOL | 2,630,775 | 20.2% |
| IS_OP | 1,175,165 | 9.0% |
| TO_BOOL_INT | 930,551 | 7.1% |
| CONTAINS_OP | 743,310 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,287,867 | 48.2% |
| LOAD_CONST | 1,190,078 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 805,142 | 6.2% |
| LOAD_FAST_LOAD_FAST | 770,777 | 5.9% |
| ENTER_EXECUTOR | 647,013 | 5.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,800 | 47.2% |
| CALL_KW | 1,520 | 25.6% |
| LOAD_GLOBAL_MODULE | 863 | 14.5% |
| LOAD_CONST | 400 | 6.7% |
| LOAD_FAST | 322 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,690 | 70.1% |
| COPY | 400 | 16.6% |
| LOAD_CONST | 322 | 13.3% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 179,231 | 49.9% |
| POP_JUMP_IF_TRUE | 177,390 | 49.4% |
| CALL_INTRINSIC_1 | 1,322 | 0.4% |
| POP_JUMP_IF_FALSE | 1,040 | 0.3% |
| DELETE_FAST | 401 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 178,831 | 98.3% |
| PUSH_EXC_INFO | 1,829 | 1.0% |
| CALL_INTRINSIC_1 | 1,322 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,074,641 | 29.2% |
| POP_JUMP_IF_FALSE | 5,032,234 | 24.2% |
| STORE_ATTR_SLOT | 2,329,992 | 11.2% |
| STORE_FAST | 1,582,020 | 7.6% |
| STORE_ATTR_INSTANCE_VALUE | 997,486 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,350,192 | 59.4% |
| INTERPRETER_EXIT | 6,381,155 | 30.7% |
| TO_BOOL_BOOL | 614,706 | 3.0% |
| STORE_FAST | 356,339 | 1.7% |
| RETURN_VALUE | 311,510 | 1.5% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 319,017 | 62.0% |
| LOAD_CONST | 193,042 | 37.5% |
| SEND | 2,097 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 318,563 | 62.0% |
| END_SEND | 190,301 | 37.0% |
| SEND | 2,097 | 0.4% |
| POP_TOP | 1,599 | 0.3% |
| SEND_GEN | 1,596 | 0.3% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80,000 | 45.2% |
| STORE_FAST_LOAD_FAST | 80,000 | 45.2% |
| RETURN_GENERATOR | 8,000 | 4.5% |
| LOAD_FAST | 8,000 | 4.5% |
| JUMP_FORWARD | 880 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 175,180 | 99.0% |
| JUMP_BACKWARD | 1,700 | 1.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,129,170 | 84.1% |
| SET_FUNCTION_ATTRIBUTE | 212,744 | 15.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 523,124 | 39.0% |
| CALL | 272,413 | 20.3% |
| SET_FUNCTION_ATTRIBUTE | 212,744 | 15.9% |
| LOAD_FAST | 196,137 | 14.6% |
| STORE_DEREF | 80,678 | 6.0% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 88,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 88,000 | 100.0% |
| STORE_NAME | 20 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 737,161 | 70.3% |
| LOAD_GLOBAL_MODULE | 265,184 | 25.3% |
| LOAD_FAST_LOAD_FAST | 22,745 | 2.2% |
| LOAD_DEREF | 10,960 | 1.0% |
| STORE_ATTR | 7,940 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 455,811 | 43.5% |
| LOAD_GLOBAL_MODULE | 179,156 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 176,978 | 16.9% |
| LOAD_CONST | 95,700 | 9.1% |
| LOAD_FAST_LOAD_FAST | 91,684 | 8.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 173,036 | 21.6% |
| LOAD_CONST | 130,565 | 16.3% |
| CALL_BUILTIN_CLASS | 89,500 | 11.2% |
| MAKE_FUNCTION | 88,007 | 11.0% |
| JUMP_FORWARD | 88,007 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 268,211 | 33.4% |
| LOAD_CONST | 210,526 | 26.2% |
| LOAD_FAST | 191,999 | 23.9% |
| LOAD_DEREF | 50,139 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 39,920 | 5.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 13,915,678 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 6,962,723 | 8.8% |
| BINARY_SUBSCR_DICT | 6,331,932 | 8.0% |
| FOR_ITER_TUPLE | 5,676,244 | 7.1% |
| LOAD_CONST | 5,124,816 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,985,809 | 56.6% |
| LOAD_FAST_LOAD_FAST | 9,241,856 | 11.6% |
| NOP | 7,418,472 | 9.3% |
| LOAD_GLOBAL_MODULE | 3,459,302 | 4.4% |
| LOAD_CONST | 2,642,700 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 644,029 | 78.2% |
| COPY | 88,380 | 10.7% |
| FOR_ITER_TUPLE | 46,940 | 5.7% |
| SWAP | 40,301 | 4.9% |
| FOR_ITER_LIST | 3,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 400,160 | 48.6% |
| STORE_ATTR_SLOT | 87,960 | 10.7% |
| LOAD_DEREF | 80,600 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 80,500 | 9.8% |
| SET_ADD | 80,000 | 9.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,107,069 | 70.5% |
| UNPACK_SEQUENCE_TUPLE | 1,159,323 | 26.3% |
| UNPACK_EX | 88,000 | 2.0% |
| STORE_FAST_STORE_FAST | 41,308 | 0.9% |
| UNPACK_SEQUENCE | 3,803 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,900,241 | 65.9% |
| STORE_FAST | 1,149,966 | 26.1% |
| NOP | 112,120 | 2.5% |
| LOAD_FAST_LOAD_FAST | 97,603 | 2.2% |
| LOAD_GLOBAL_MODULE | 56,078 | 1.3% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 140 | 30.4% |
| BINARY_OP_SUBTRACT_INT | 140 | 30.4% |
| LOAD_FAST | 80 | 17.4% |
| BINARY_OP | 40 | 8.7% |
| CALL | 40 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 39.1% |
| LOAD_GLOBAL_MODULE | 120 | 26.1% |
| LOAD_FAST | 80 | 17.4% |
| LOAD_GLOBAL | 80 | 17.4% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 4,200 | 29.2% |
| SET_FUNCTION_ATTRIBUTE | 3,580 | 24.9% |
| LOAD_CONST | 1,540 | 10.7% |
| CALL | 1,260 | 8.8% |
| LOAD_NAME | 1,060 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,420 | 44.6% |
| POP_TOP | 2,460 | 17.1% |
| IMPORT_FROM | 1,740 | 12.1% |
| RETURN_CONST | 980 | 6.8% |
| LOAD_NAME | 920 | 6.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,935,696 | 31.2% |
| BINARY_OP_ADD_INT | 2,772,096 | 17.5% |
| LOAD_FAST_AND_CLEAR | 1,386,575 | 8.8% |
| SWAP | 1,380,140 | 8.7% |
| BINARY_OP_SUBTRACT_INT | 1,050,350 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,526,577 | 28.7% |
| STORE_ATTR_WITH_HINT | 1,407,840 | 8.9% |
| SWAP | 1,380,140 | 8.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,361,456 | 8.6% |
| STORE_FAST | 1,359,518 | 8.6% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 88,000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,220 | 25.5% |
| FOR_ITER | 1,860 | 21.3% |
| RETURN_VALUE | 1,420 | 16.3% |
| RETURN_GENERATOR | 813 | 9.3% |
| CALL | 420 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,803 | 43.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,040 | 23.4% |
| STORE_FAST | 1,953 | 22.4% |
| UNPACK_SEQUENCE_TUPLE | 520 | 6.0% |
| UNPACK_SEQUENCE | 260 | 3.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 386,392 | 26.0% |
| SEND | 318,563 | 21.5% |
| YIELD_VALUE | 264,891 | 17.9% |
| BUILD_TUPLE | 91,410 | 6.2% |
| LOAD_FAST | 82,186 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,124,848 | 75.8% |
| YIELD_VALUE | 264,891 | 17.9% |
| STORE_FAST | 93,440 | 6.3% |
| UNPACK_SEQUENCE_TUPLE | 200 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 9,869 | 37.7% |
| CACHE | 7,442 | 28.5% |
| POP_TOP | 2,379 | 9.1% |
| COPY_FREE_VARS | 1,687 | 6.5% |
| MAKE_CELL | 1,540 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,205 | 39.0% |
| LOAD_GLOBAL | 7,099 | 27.1% |
| LOAD_CONST | 1,500 | 5.7% |
| LOAD_FAST_LOAD_FAST | 1,427 | 5.5% |
| NOP | 1,380 | 5.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 323,817 | 27.8% |
| LOAD_ATTR_INSTANCE_VALUE | 272,703 | 23.4% |
| LOAD_FAST_LOAD_FAST | 271,920 | 23.3% |
| BINARY_OP | 202,472 | 17.4% |
| BINARY_OP_MULTIPLY_FLOAT | 87,923 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 471,189 | 40.4% |
| LOAD_FAST | 361,927 | 31.0% |
| STORE_FAST | 330,301 | 28.3% |
| CALL_ALLOC_AND_ENTER_INIT | 1,930 | 0.2% |
| RETURN_VALUE | 320 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,091,036 | 41.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,165,252 | 22.9% |
| CALL | 649,058 | 12.8% |
| LOAD_FAST | 488,495 | 9.6% |
| CALL_LEN | 354,003 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,772,096 | 54.5% |
| RETURN_VALUE | 1,259,143 | 24.8% |
| LOAD_GLOBAL_MODULE | 365,032 | 7.2% |
| LOAD_CONST | 337,630 | 6.6% |
| LOAD_FAST | 112,760 | 2.2% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,142 | 42.4% |
| RETURN_VALUE | 89,368 | 34.4% |
| LOAD_FAST_LOAD_FAST | 52,760 | 20.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,300 | 0.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,560 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 108,760 | 41.8% |
| LIST_APPEND | 87,980 | 33.8% |
| LOAD_FAST | 45,482 | 17.5% |
| CALL | 8,040 | 3.1% |
| STORE_FAST | 2,426 | 0.9% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,080 | 88.9% |
| LOAD_CONST | 18,289 | 8.8% |
| LOAD_FAST_LOAD_FAST | 4,313 | 2.1% |
| BINARY_OP | 232 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 87,923 | 42.5% |
| LOAD_CONST | 87,900 | 42.5% |
| CALL_BUILTIN_O | 18,803 | 9.1% |
| COMPARE_OP_FLOAT | 7,720 | 3.7% |
| STORE_FAST | 4,333 | 2.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 324,569 | 49.9% |
| LOAD_FAST_LOAD_FAST | 174,954 | 26.9% |
| LOAD_CONST | 96,259 | 14.8% |
| BINARY_OP_ADD_INT | 40,503 | 6.2% |
| LOAD_GLOBAL_MODULE | 12,733 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 325,333 | 50.0% |
| BINARY_OP | 175,014 | 26.9% |
| COMPARE_OP_INT | 87,960 | 13.5% |
| STORE_FAST | 52,423 | 8.1% |
| LOAD_CONST | 6,171 | 0.9% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 446,054 | 54.7% |
| LOAD_FAST | 175,784 | 21.6% |
| CALL | 87,851 | 10.8% |
| RETURN_VALUE | 78,264 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 15,849 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 292,651 | 35.9% |
| LOAD_CONST | 266,400 | 32.7% |
| SWAP | 175,832 | 21.6% |
| CALL | 57,473 | 7.1% |
| LOAD_FAST | 16,243 | 2.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 782,210 | 40.2% |
| LOAD_FAST | 523,839 | 26.9% |
| BINARY_OP_MULTIPLY_INT | 325,333 | 16.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 263,880 | 13.6% |
| BINARY_OP_SUBTRACT_INT | 40,583 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,050,350 | 54.0% |
| RETURN_VALUE | 326,229 | 16.8% |
| BINARY_OP | 175,354 | 9.0% |
| STORE_FAST | 172,600 | 8.9% |
| BINARY_SUBSCR_LIST_INT | 64,522 | 3.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,742,673 | 46.5% |
| LOAD_FAST | 2,772,904 | 27.2% |
| LOAD_CONST | 1,326,314 | 13.0% |
| COPY | 1,025,635 | 10.1% |
| CALL | 229,303 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,331,932 | 62.1% |
| LOAD_CONST | 1,405,399 | 13.8% |
| RETURN_VALUE | 1,072,206 | 10.5% |
| LOAD_FAST | 662,372 | 6.5% |
| PUSH_EXC_INFO | 187,727 | 1.8% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 574,906 | 98.4% |
| ENTER_EXECUTOR | 7,220 | 1.2% |
| LOAD_CONST | 1,500 | 0.3% |
| LOAD_FAST_LOAD_FAST | 740 | 0.1% |
| BINARY_SUBSCR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,426 | 54.8% |
| COPY_FREE_VARS | 263,960 | 45.2% |
| BUILD_TUPLE | 160 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 721,875 | 77.7% |
| LOAD_FAST | 79,155 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 64,522 | 6.9% |
| LOAD_FAST_LOAD_FAST | 62,915 | 6.8% |
| BINARY_SUBSCR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 259,355 | 27.9% |
| LOAD_ATTR_SLOT | 255,672 | 27.5% |
| LOAD_FAST_LOAD_FAST | 116,680 | 12.6% |
| TO_BOOL_BOOL | 88,562 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 63,840 | 6.9% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 233,694 | 96.2% |
| LOAD_FAST_LOAD_FAST | 5,094 | 2.1% |
| LOAD_FAST | 2,860 | 1.2% |
| CALL_BUILTIN_O | 600 | 0.2% |
| ENTER_EXECUTOR | 400 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 207,080 | 85.3% |
| LOAD_ATTR_METHOD_NO_DICT | 31,548 | 13.0% |
| STORE_FAST | 2,760 | 1.1% |
| LIST_APPEND | 620 | 0.3% |
| PUSH_EXC_INFO | 440 | 0.2% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,482,946 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,920 | 0.2% |
| BINARY_SUBSCR | 640 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 688,240 | 46.3% |
| LOAD_ATTR_SLOT | 226,436 | 15.2% |
| CALL_BUILTIN_O | 176,880 | 11.9% |
| STORE_FAST | 102,382 | 6.9% |
| RETURN_VALUE | 99,528 | 6.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 177,162 | 59.6% |
| LOAD_FAST_LOAD_FAST | 93,457 | 31.4% |
| LOAD_FAST | 8,562 | 2.9% |
| LOAD_CONST | 8,000 | 2.7% |
| LOAD_GLOBAL_MODULE | 2,231 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 295,049 | 99.3% |
| COPY_FREE_VARS | 1,144 | 0.4% |
| POP_TOP | 920 | 0.3% |
| RESUME | 40 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 42,671 | 32.8% |
| LOAD_CONST | 24,224 | 18.6% |
| LOAD_FAST | 19,382 | 14.9% |
| PUSH_NULL | 16,054 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 10,661 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 103,350 | 79.3% |
| POP_TOP | 11,992 | 9.2% |
| GET_AWAITABLE | 10,612 | 8.1% |
| COPY_FREE_VARS | 2,106 | 1.6% |
| MAKE_CELL | 824 | 0.6% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,088,927 | 29.3% |
| LOAD_FAST | 1,989,189 | 27.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,085,961 | 15.3% |
| LOAD_ATTR_SLOT | 952,040 | 13.4% |
| PUSH_NULL | 437,646 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,058,232 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,274,854 | 17.9% |
| LOAD_FAST | 1,067,523 | 15.0% |
| CALL | 975,787 | 13.7% |
| GET_ITER | 797,086 | 11.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,143,007 | 58.9% |
| LOAD_FAST_LOAD_FAST | 408,168 | 21.0% |
| BUILD_TUPLE | 167,920 | 8.7% |
| LOAD_GLOBAL_MODULE | 88,200 | 4.5% |
| LOAD_FAST | 71,206 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 682,617 | 35.2% |
| TO_BOOL_BOOL | 492,087 | 25.4% |
| POP_TOP | 235,615 | 12.1% |
| RETURN_VALUE | 230,266 | 11.9% |
| STORE_FAST | 135,562 | 7.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,274,854 | 56.6% |
| LOAD_FAST | 527,418 | 23.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 168,080 | 7.5% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 88,000 | 3.9% |
| LOAD_ATTR | 83,903 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,165,252 | 51.8% |
| STORE_FAST | 423,476 | 18.8% |
| RETURN_VALUE | 299,871 | 13.3% |
| POP_TOP | 93,766 | 4.2% |
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 3.9% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 458,497 | 28.9% |
| LOAD_ATTR_INSTANCE_VALUE | 408,561 | 25.8% |
| BINARY_SUBSCR_TUPLE_INT | 176,880 | 11.2% |
| RETURN_GENERATOR | 118,284 | 7.5% |
| LOAD_ATTR_SLOT | 118,140 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 551,037 | 34.8% |
| RETURN_VALUE | 443,502 | 28.0% |
| STORE_FAST | 332,693 | 21.0% |
| LOAD_FAST | 90,347 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 87,265 | 5.5% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,842,974 | 41.1% |
| LOAD_GLOBAL_MODULE | 1,424,534 | 31.8% |
| LOAD_FAST_LOAD_FAST | 443,063 | 9.9% |
| LOAD_ATTR | 376,662 | 8.4% |
| BUILD_TUPLE | 279,902 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,038,260 | 90.1% |
| RETURN_VALUE | 278,091 | 6.2% |
| COPY | 159,728 | 3.6% |
| TO_BOOL | 2,460 | 0.1% |
| YIELD_VALUE | 2,020 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,474,633 | 62.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,285,359 | 23.1% |
| LOAD_ATTR_SLOT | 432,280 | 7.8% |
| LOAD_ATTR_WITH_HINT | 359,609 | 6.5% |
| LOAD_DEREF | 4,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,060,142 | 37.0% |
| LOAD_CONST | 1,186,611 | 21.3% |
| RETURN_VALUE | 884,538 | 15.9% |
| LOAD_FAST | 389,696 | 7.0% |
| BINARY_OP_ADD_INT | 354,003 | 6.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 271,762 | 41.3% |
| BUILD_CONST_KEY_MAP | 176,880 | 26.9% |
| ENTER_EXECUTOR | 88,540 | 13.4% |
| BUILD_TUPLE | 65,924 | 10.0% |
| BINARY_SLICE | 40,503 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 299,113 | 45.4% |
| ENTER_EXECUTOR | 154,070 | 23.4% |
| NOP | 90,721 | 13.8% |
| LOAD_FAST_LOAD_FAST | 89,000 | 13.5% |
| RETURN_CONST | 10,400 | 1.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,456,904 | 40.8% |
| LOAD_CONST | 2,200,088 | 36.5% |
| BUILD_TUPLE | 527,960 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 435,523 | 7.2% |
| LOAD_ATTR_INSTANCE_VALUE | 104,580 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,972,121 | 82.6% |
| BINARY_OP_SUBTRACT_INT | 263,880 | 4.4% |
| POP_TOP | 179,655 | 3.0% |
| CALL_METHOD_DESCRIPTOR_O | 167,960 | 2.8% |
| LOAD_FAST | 99,620 | 1.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 305,807 | 39.6% |
| LOAD_FAST_LOAD_FAST | 233,410 | 30.3% |
| LOAD_ATTR_METHOD_NO_DICT | 132,847 | 17.2% |
| LOAD_CONST | 57,201 | 7.4% |
| LOAD_ATTR | 41,303 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 347,190 | 45.0% |
| STORE_FAST | 330,785 | 42.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 88,000 | 11.4% |
| GET_ITER | 1,880 | 0.2% |
| RETURN_VALUE | 1,320 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,542,258 | 84.7% |
| LOAD_ATTR | 1,171,497 | 15.2% |
| CALL | 3,980 | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,603 | 0.0% |
| LOAD_FAST | 1,444 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,530,772 | 32.8% |
| POP_TOP | 1,322,668 | 17.1% |
| CALL_BUILTIN_CLASS | 1,085,961 | 14.1% |
| TO_BOOL_BOOL | 976,473 | 12.6% |
| STORE_FAST | 814,177 | 10.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,391,102 | 67.2% |
| BUILD_TUPLE | 1,549,520 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 337,880 | 4.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 167,960 | 2.1% |
| CALL | 155,821 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,645,672 | 95.3% |
| RETURN_VALUE | 169,281 | 2.1% |
| LOAD_CONST | 101,745 | 1.3% |
| STORE_FAST | 45,751 | 0.6% |
| BUILD_LIST | 40,443 | 0.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,842,768 | 35.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,607,782 | 25.2% |
| CALL_TYPE_1 | 4,520,157 | 15.0% |
| LOAD_FAST_LOAD_FAST | 1,610,407 | 5.3% |
| LOAD_DEREF | 916,935 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 28,606,857 | 94.7% |
| COPY_FREE_VARS | 758,378 | 2.5% |
| MAKE_CELL | 651,827 | 2.2% |
| RETURN_GENERATOR | 103,277 | 0.3% |
| TO_BOOL_BOOL | 86,669 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,089,604 | 45.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 481,853 | 19.9% |
| ENTER_EXECUTOR | 353,629 | 14.6% |
| LOAD_ATTR_INSTANCE_VALUE | 177,123 | 7.3% |
| LOAD_FAST_LOAD_FAST | 90,500 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,615,077 | 66.6% |
| MAKE_CELL | 721,432 | 29.8% |
| RETURN_GENERATOR | 84,695 | 3.5% |
| CALL | 1,060 | 0.0% |
| STORE_FAST | 1,040 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 88,000 | 34.1% |
| CALL_TYPE_1 | 87,960 | 34.0% |
| LOAD_ATTR | 76,671 | 29.7% |
| LOAD_FAST | 2,967 | 1.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,300 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 34.1% |
| CONTAINS_OP | 87,980 | 34.1% |
| BUILD_TUPLE | 76,691 | 29.7% |
| STORE_FAST | 4,107 | 1.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 640 | 0.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 176,440 | 48.6% |
| CALL_BUILTIN_CLASS | 88,760 | 24.4% |
| STORE_FAST | 87,960 | 24.2% |
| LOAD_FAST | 8,470 | 2.3% |
| LOAD_GLOBAL_MODULE | 680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 176,680 | 48.6% |
| CALL_STR_1 | 88,000 | 24.2% |
| BINARY_OP | 87,980 | 24.2% |
| LOAD_FAST_LOAD_FAST | 7,030 | 1.9% |
| STORE_FAST | 1,240 | 0.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,602,649 | 98.8% |
| BINARY_SUBSCR_TUPLE_INT | 87,960 | 1.1% |
| CALL | 780 | 0.0% |
| LOAD_GLOBAL_MODULE | 640 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,520,157 | 58.8% |
| STORE_FAST | 1,914,320 | 24.9% |
| LOAD_GLOBAL_BUILTIN | 484,780 | 6.3% |
| LOAD_GLOBAL_MODULE | 238,693 | 3.1% |
| LOAD_FAST | 180,552 | 2.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 535,722 | 31.3% |
| LOAD_CONST | 431,163 | 25.2% |
| LOAD_FAST | 337,719 | 19.7% |
| BINARY_OP | 181,586 | 10.6% |
| COPY | 174,954 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,175,852 | 68.7% |
| RETURN_VALUE | 534,902 | 31.2% |
| POP_JUMP_IF_TRUE | 920 | 0.1% |
| EXTENDED_ARG | 303 | 0.0% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,586,737 | 56.5% |
| LOAD_FAST_LOAD_FAST | 1,693,830 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 506,768 | 6.2% |
| LOAD_GLOBAL_MODULE | 363,513 | 4.5% |
| LOAD_ATTR_WITH_HINT | 183,311 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,016,571 | 86.5% |
| POP_JUMP_IF_TRUE | 738,708 | 9.1% |
| EXTENDED_ARG | 352,562 | 4.3% |
| RETURN_VALUE | 3,320 | 0.0% |
| COPY | 947 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,953,785 | 71.2% |
| LOAD_FAST | 603,335 | 10.9% |
| LOAD_FAST_LOAD_FAST | 456,020 | 8.2% |
| LOAD_GLOBAL_MODULE | 360,236 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 90,460 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,087,499 | 91.6% |
| POP_JUMP_IF_TRUE | 369,540 | 6.7% |
| RETURN_VALUE | 88,040 | 1.6% |
| COPY | 7,240 | 0.1% |
| EXTENDED_ARG | 2,920 | 0.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 92,979 | 95.0% |
| GET_ITER | 3,490 | 3.6% |
| SWAP | 922 | 0.9% |
| FOR_ITER | 260 | 0.3% |
| EXTENDED_ARG | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 92,979 | 95.0% |
| POP_TOP | 4,412 | 4.5% |
| RETURN_CONST | 240 | 0.2% |
| STORE_FAST | 160 | 0.2% |
| RESUME | 100 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,075,762 | 60.3% |
| ENTER_EXECUTOR | 1,269,479 | 36.9% |
| SWAP | 44,683 | 1.3% |
| LOAD_FAST | 24,533 | 0.7% |
| JUMP_BACKWARD | 20,342 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,272,572 | 37.0% |
| STORE_FAST | 1,132,076 | 32.9% |
| RETURN_CONST | 882,299 | 25.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 136,026 | 4.0% |
| LOAD_GLOBAL_BUILTIN | 4,302 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 247,735 | 54.6% |
| GET_ITER | 201,383 | 44.4% |
| JUMP_BACKWARD | 3,543 | 0.8% |
| FOR_ITER | 300 | 0.1% |
| LOAD_FAST | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 233,450 | 51.5% |
| STORE_FAST | 204,810 | 45.2% |
| LOAD_FAST | 7,431 | 1.6% |
| LOAD_GLOBAL_BUILTIN | 7,010 | 1.5% |
| RETURN_CONST | 260 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,401,819 | 78.0% |
| ENTER_EXECUTOR | 1,192,031 | 17.2% |
| LOAD_FAST | 185,784 | 2.7% |
| SWAP | 135,460 | 2.0% |
| JUMP_BACKWARD | 8,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,676,244 | 82.0% |
| LOAD_FAST | 762,058 | 11.0% |
| RETURN_CONST | 183,028 | 2.6% |
| SWAP | 135,580 | 2.0% |
| ENTER_EXECUTOR | 80,200 | 1.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 248,876 | 54.2% |
| LOAD_ATTR_MODULE | 203,037 | 44.2% |
| LOAD_FAST | 3,244 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 2,126 | 0.5% |
| ENTER_EXECUTOR | 1,060 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 163,048 | 35.5% |
| COMPARE_OP_INT | 121,911 | 26.6% |
| CALL_PY_EXACT_ARGS | 81,422 | 17.7% |
| LOAD_FAST | 45,991 | 10.0% |
| CALL | 41,585 | 9.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,314,418 | 87.4% |
| LOAD_FAST_LOAD_FAST | 3,653,169 | 6.3% |
| COPY | 1,361,456 | 2.4% |
| LOAD_ATTR_SLOT | 1,312,283 | 2.3% |
| LOAD_DEREF | 650,046 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,714,688 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 7,308,190 | 12.7% |
| STORE_FAST | 6,962,723 | 12.1% |
| TO_BOOL_BOOL | 5,067,575 | 8.8% |
| RETURN_VALUE | 3,860,798 | 6.7% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 263,900 | 100.0% |
| LOAD_FAST | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 263,920 | 100.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,444,704 | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE | 7,308,190 | 27.7% |
| LOAD_ATTR_WITH_HINT | 5,452,970 | 20.6% |
| LOAD_ATTR_SLOT | 1,801,121 | 6.8% |
| RETURN_VALUE | 528,172 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,636,306 | 51.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,542,258 | 24.8% |
| LOAD_CONST | 2,632,540 | 10.0% |
| LOAD_FAST_LOAD_FAST | 1,388,639 | 5.3% |
| CALL | 978,245 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,541,453 | 66.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,438,993 | 12.1% |
| LOAD_ATTR_SLOT | 1,523,246 | 7.5% |
| LOAD_ATTR_WITH_HINT | 1,222,288 | 6.0% |
| LOAD_DEREF | 543,154 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,607,782 | 37.6% |
| LOAD_GLOBAL_BUILTIN | 4,665,280 | 23.1% |
| LOAD_FAST | 4,072,200 | 20.1% |
| LOAD_FAST_LOAD_FAST | 1,626,922 | 8.0% |
| LOAD_GLOBAL_MODULE | 802,354 | 4.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,610,805 | 96.7% |
| LOAD_FAST | 142,913 | 1.8% |
| LOAD_ATTR_MODULE | 105,038 | 1.3% |
| LOAD_ATTR | 13,243 | 0.2% |
| BINARY_SUBSCR_DICT | 1,790 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,242,869 | 79.3% |
| LOAD_FAST | 319,125 | 4.1% |
| LOAD_ATTR_CLASS | 203,037 | 2.6% |
| LOAD_ATTR | 183,362 | 2.3% |
| BINARY_OP | 148,678 | 1.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840 | 77.4% |
| LOAD_FAST_LOAD_FAST | 864 | 17.4% |
| LOAD_ATTR | 180 | 3.6% |
| LOAD_CONST | 80 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,590 | 32.0% |
| TO_BOOL_BOOL | 1,126 | 22.7% |
| LOAD_FAST | 944 | 19.0% |
| CALL_BUILTIN_FAST | 864 | 17.4% |
| CALL | 240 | 4.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 204,001 | 60.5% |
| LOAD_FAST | 89,204 | 26.5% |
| LOAD_FAST_LOAD_FAST | 43,263 | 12.8% |
| LOAD_ATTR | 700 | 0.2% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 123,299 | 36.6% |
| COMPARE_OP_INT | 81,106 | 24.1% |
| LOAD_FAST | 42,147 | 12.5% |
| LOAD_CONST | 40,703 | 12.1% |
| STORE_FAST | 40,603 | 12.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,420,807 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 177,924 | 6.5% |
| RETURN_VALUE | 101,007 | 3.7% |
| ENTER_EXECUTOR | 22,960 | 0.8% |
| LOAD_ATTR | 2,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,727,135 | 99.9% |
| COPY_FREE_VARS | 1,848 | 0.1% |
| LOAD_GLOBAL_MODULE | 382 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,415,001 | 92.3% |
| LOAD_FAST_LOAD_FAST | 946,978 | 2.9% |
| STORE_FAST_LOAD_FAST | 400,160 | 1.2% |
| COPY | 359,732 | 1.1% |
| BINARY_SUBSCR_LIST_INT | 255,672 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,778,991 | 11.5% |
| TO_BOOL_NONE | 3,206,057 | 9.7% |
| LOAD_CONST | 2,928,869 | 8.9% |
| STORE_FAST | 2,879,822 | 8.7% |
| LOAD_FAST | 2,504,822 | 7.6% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,405,727 | 82.7% |
| COPY | 1,407,840 | 6.7% |
| LOAD_FAST_LOAD_FAST | 1,159,552 | 5.5% |
| LOAD_DEREF | 447,226 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 440,840 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,452,970 | 25.9% |
| LOAD_FAST | 3,747,609 | 17.8% |
| TO_BOOL_BOOL | 2,593,005 | 12.3% |
| LOAD_CONST | 1,952,932 | 9.3% |
| RETURN_VALUE | 1,849,868 | 8.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,616,089 | 26.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,665,280 | 12.7% |
| LOAD_FAST | 4,300,444 | 11.7% |
| POP_JUMP_IF_FALSE | 2,844,246 | 7.8% |
| STORE_FAST | 2,543,255 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,725,579 | 61.9% |
| IS_OP | 2,533,720 | 6.9% |
| LOAD_GLOBAL_BUILTIN | 2,323,756 | 6.3% |
| CALL_BUILTIN_CLASS | 2,088,927 | 5.7% |
| CALL_ISINSTANCE | 1,842,974 | 5.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,601,823 | 20.0% |
| LOAD_FAST | 5,934,513 | 13.8% |
| POP_JUMP_IF_FALSE | 5,703,981 | 13.2% |
| STORE_FAST | 3,459,302 | 8.0% |
| LOAD_GLOBAL_MODULE | 3,277,707 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,207,010 | 35.3% |
| LOAD_ATTR_MODULE | 7,610,805 | 17.7% |
| CALL | 3,532,224 | 8.2% |
| LOAD_GLOBAL_MODULE | 3,277,707 | 7.6% |
| LOAD_FAST_LOAD_FAST | 2,460,666 | 5.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,592 | 91.4% |
| LOAD_SUPER_ATTR | 220 | 5.6% |
| EXTENDED_ARG | 120 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,044 | 52.0% |
| LOAD_GLOBAL_MODULE | 1,848 | 47.0% |
| LOAD_GLOBAL | 40 | 1.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 637,692 | 99.9% |
| LOAD_SUPER_ATTR | 720 | 0.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,547 | 62.7% |
| LOAD_FAST_LOAD_FAST | 194,178 | 30.4% |
| CALL_PY_EXACT_ARGS | 43,025 | 6.7% |
| CALL | 380 | 0.1% |
| LOAD_CONST | 302 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 28,606,857 | 37.5% |
| CACHE | 22,016,051 | 28.9% |
| CALL_FUNCTION_EX | 5,704,450 | 7.5% |
| CALL | 3,979,615 | 5.2% |
| COPY_FREE_VARS | 3,559,792 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,660,881 | 58.6% |
| LOAD_GLOBAL_BUILTIN | 9,616,089 | 12.6% |
| LOAD_GLOBAL_MODULE | 8,601,823 | 11.3% |
| NOP | 5,266,152 | 6.9% |
| LOAD_FAST_LOAD_FAST | 2,675,457 | 3.5% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 324,512 | 55.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 263,631 | 44.7% |
| SEND | 1,596 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 325,172 | 55.1% |
| RESUME_CHECK | 263,384 | 44.7% |
| RESUME | 943 | 0.2% |
| END_SEND | 160 | 0.0% |
| YIELD_VALUE | 80 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,321,113 | 69.7% |
| LOAD_FAST_LOAD_FAST | 1,603,209 | 15.3% |
| SWAP | 1,361,456 | 13.0% |
| LOAD_DEREF | 85,463 | 0.8% |
| BINARY_SUBSCR_DICT | 79,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,721,043 | 25.9% |
| LOAD_CONST | 2,704,741 | 25.7% |
| RETURN_CONST | 997,486 | 9.5% |
| LOAD_FAST_LOAD_FAST | 902,720 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 847,205 | 8.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,153,655 | 53.8% |
| LOAD_FAST_LOAD_FAST | 6,525,035 | 43.1% |
| SWAP | 359,732 | 2.4% |
| STORE_FAST_LOAD_FAST | 87,960 | 0.6% |
| STORE_ATTR_SLOT | 16,912 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,874,295 | 32.2% |
| LOAD_FAST_LOAD_FAST | 4,105,028 | 27.1% |
| LOAD_FAST | 2,496,478 | 16.5% |
| RETURN_CONST | 2,329,992 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 704,944 | 4.7% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,407,840 | 99.2% |
| LOAD_FAST_LOAD_FAST | 7,338 | 0.5% |
| LOAD_DEREF | 1,406 | 0.1% |
| LOAD_FAST | 1,046 | 0.1% |
| STORE_ATTR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,919 | 69.4% |
| EXTENDED_ARG | 431,980 | 30.4% |
| RETURN_CONST | 1,040 | 0.1% |
| LOAD_CONST | 511 | 0.0% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,105,657 | 24.7% |
| SWAP | 1,025,635 | 22.9% |
| LOAD_CONST | 885,329 | 19.8% |
| LOAD_FAST_LOAD_FAST | 810,860 | 18.1% |
| LOAD_ATTR_SLOT | 496,480 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,794,751 | 40.1% |
| ENTER_EXECUTOR | 929,420 | 20.8% |
| LOAD_FAST_LOAD_FAST | 881,442 | 19.7% |
| RETURN_CONST | 189,488 | 4.2% |
| LOAD_CONST | 178,097 | 4.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 117,880 | 70.3% |
| LOAD_CONST | 41,143 | 24.6% |
| LOAD_ATTR_INSTANCE_VALUE | 7,960 | 4.7% |
| LOAD_FAST | 320 | 0.2% |
| STORE_SUBSCR | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 59,370 | 35.4% |
| LOAD_FAST_LOAD_FAST | 56,730 | 33.9% |
| LOAD_DEREF | 48,503 | 28.9% |
| RETURN_CONST | 1,460 | 0.9% |
| JUMP_BACKWARD | 940 | 0.6% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 440,722 | 53.0% |
| LOAD_FAST | 378,424 | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,786 | 1.1% |
| CALL | 1,000 | 0.1% |
| TO_BOOL | 802 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 474,713 | 57.1% |
| POP_JUMP_IF_TRUE | 356,456 | 42.9% |
| TO_BOOL_NONE | 125 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,343,717 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 5,067,575 | 20.4% |
| CALL_ISINSTANCE | 4,038,260 | 16.3% |
| LOAD_ATTR_WITH_HINT | 2,593,005 | 10.4% |
| COPY | 1,919,393 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,642,425 | 79.1% |
| POP_JUMP_IF_TRUE | 5,195,581 | 20.9% |
| EXTENDED_ARG | 2,254 | 0.0% |
| UNARY_NOT | 1,060 | 0.0% |
| TO_BOOL_INT | 20 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 567,778 | 33.3% |
| COPY | 531,852 | 31.2% |
| LOAD_FAST | 215,478 | 12.6% |
| RETURN_VALUE | 174,925 | 10.3% |
| LOAD_GLOBAL_MODULE | 96,737 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 930,551 | 54.6% |
| POP_JUMP_IF_FALSE | 772,404 | 45.3% |
| UNARY_NOT | 960 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 875,023 | 57.7% |
| LOAD_FAST | 451,232 | 29.8% |
| LOAD_ATTR_WITH_HINT | 187,357 | 12.4% |
| TO_BOOL | 940 | 0.1% |
| STORE_FAST_LOAD_FAST | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,504,133 | 99.2% |
| POP_JUMP_IF_TRUE | 11,874 | 0.8% |
| UNARY_NOT | 620 | 0.0% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 3,206,057 | 76.9% |
| LOAD_FAST | 421,126 | 10.1% |
| WITH_EXCEPT_START | 177,300 | 4.3% |
| LOAD_ATTR | 150,695 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 102,227 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,788,389 | 90.9% |
| POP_JUMP_IF_TRUE | 379,021 | 9.1% |
| EXTENDED_ARG | 380 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 118 | 0.0% |
| TO_BOOL | 1 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 284,492 | 50.5% |
| LOAD_ATTR | 87,960 | 15.6% |
| LOAD_ATTR_WITH_HINT | 80,923 | 14.4% |
| COPY | 48,794 | 8.7% |
| STORE_FAST_LOAD_FAST | 46,880 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 325,491 | 57.8% |
| POP_JUMP_IF_TRUE | 226,518 | 40.2% |
| EXTENDED_ARG | 11,220 | 2.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 66.7% |
| UNPACK_SEQUENCE | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 530,460 | 42.7% |
| CALL_FUNCTION_EX | 431,960 | 34.8% |
| RETURN_VALUE | 90,900 | 7.3% |
| END_SEND | 88,242 | 7.1% |
| CALL_BUILTIN_FAST | 40,503 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,159,323 | 93.3% |
| STORE_FAST | 82,946 | 6.7% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 889,642 | 27.0% |
| FOR_ITER | 821,492 | 24.9% |
| CALL_FUNCTION_EX | 615,920 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 353,802 | 10.7% |
| FOR_ITER_LIST | 136,026 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,107,069 | 94.3% |
| STORE_FAST | 98,780 | 3.0% |
| LOAD_FAST_LOAD_FAST | 87,980 | 2.7% |
| LOAD_FAST | 2,242 | 0.1% |
| STORE_DEREF | 200 | 0.0% |


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
|     deferred | 3,615,434 | 26.0% |
|          hit | 10,241,859 | 73.8% |
|         miss | 6,842 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,703 | 22.1% |
| Failure | 16,542 | 77.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 4,001 | 24.2% |
| or | 2,315 | 14.0% |
| multiply different types | 2,303 | 13.9% |
| add other | 1,707 | 10.3% |
| true divide different types | 1,700 | 10.3% |
| remainder | 920 | 5.6% |
| add different types | 863 | 5.2% |
| subtract different types | 846 | 5.1% |
| true divide other | 443 | 2.7% |
| true divide float | 400 | 2.4% |
| floor divide | 260 | 1.6% |
| lshift | 200 | 1.2% |
| power | 200 | 1.2% |
| subtract other | 160 | 1.0% |
| rshift | 124 | 0.7% |
| and other | 80 | 0.5% |
| and different types | 20 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|         miss | 220 | 0.2% |


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
|     deferred | 1,422,650 | 9.6% |
|          hit | 13,440,454 | 90.4% |
|         miss | 1,620 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,800 | 50.0% |
| Failure | 4,792 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 3,208 | 66.9% |
| buffer int | 964 | 20.1% |
| code complex parameters | 400 | 8.3% |
| out of range | 200 | 4.2% |
| list slice | 20 | 0.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,018,367 | 23.5% |
|          hit | 87,178,873 | 76.0% |
|         miss | 440,159 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 58,357 | 45.5% |
| Failure | 69,948 | 54.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 16,089 | 23.0% |
| cfunc noargs | 13,805 | 19.7% |
| class no vectorcall | 8,296 | 11.9% |
| meth descr varargs | 5,284 | 7.6% |
| meth descr method fastcall keywords | 4,086 | 5.8% |
| meth descr varargs keywords | 4,035 | 5.8% |
| cfunc varargs keywords | 4,025 | 5.8% |
| cfunc varargs | 3,867 | 5.5% |
| other | 3,847 | 5.5% |
| no dict | 2,277 | 3.3% |
| class mutable | 1,397 | 2.0% |
| wrong number arguments | 1,340 | 1.9% |
| operator wrapper | 620 | 0.9% |
| init not simple | 580 | 0.8% |
| cmethod | 260 | 0.4% |
| init not python | 100 | 0.1% |
| str | 20 | 0.0% |
| method wrapper | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,448,260 | 8.6% |
|          hit | 15,353,208 | 91.2% |
|         miss | 27,342 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,007 | 49.0% |
| Failure | 6,243 | 51.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 2,003 | 32.1% |
| long float | 1,029 | 16.5% |
| baseobject | 1,020 | 16.3% |
| big int | 834 | 13.4% |
| different types | 717 | 11.5% |
| other | 520 | 8.3% |
| tuple | 80 | 1.3% |
| bool | 40 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,056,524 | 35.6% |
|          hit | 10,916,565 | 64.2% |
|         miss | 400 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,700 | 16.9% |
| Failure | 18,232 | 83.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 9,107 | 50.0% |
| dict items | 5,029 | 27.6% |
| zip | 844 | 4.6% |
| dict keys | 820 | 4.5% |
| dict values | 740 | 4.1% |
| other | 480 | 2.6% |
| enumerate | 372 | 2.0% |
| itertools | 360 | 2.0% |
| bytes | 200 | 1.1% |
| reversed list | 140 | 0.8% |
| map | 120 | 0.7% |
| ascii string | 20 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,330,014 | 10.7% |
|        deopt | 356,472 | 0.2% |
|          hit | 167,863,520 | 88.3% |
|         miss | 1,997,699 | 1.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 118,454 | 65.0% |
| Failure | 63,806 | 35.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 19,324 | 30.3% |
| method | 17,894 | 28.0% |
| metaclass attribute | 7,897 | 12.4% |
| not managed dict | 7,762 | 12.2% |
| module attr not found | 2,340 | 3.7% |
| shadowed | 2,101 | 3.3% |
| overridden | 1,443 | 2.3% |
| class attr descriptor | 1,280 | 2.0% |
| mutable class | 1,040 | 1.6% |
| non object slot | 825 | 1.3% |
| non overriding descriptor | 820 | 1.3% |
| class method obj | 540 | 0.8% |
| builtin class method | 200 | 0.3% |
| class attr simple | 200 | 0.3% |
| not in keys | 80 | 0.1% |
| property | 60 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 55,203 | 0.1% |
|        deopt | 1,060 | 0.0% |
|          hit | 79,741,828 | 99.8% |
|         miss | 11,780 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 54,944 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 900 | 0.1% |
|          hit | 642,424 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 940 | 100.0% |
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
|     deferred | 510,463 | 46.2% |
|          hit | 589,499 | 53.4% |
|         miss | 240 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,596 | 43.2% |
| Failure | 2,097 | 56.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,857 | 88.6% |
| dict keys | 240 | 11.4% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,002,392 | 3.6% |
|          hit | 26,163,544 | 93.0% |
|         miss | 910,382 | 3.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,895 | 82.7% |
| Failure | 7,940 | 17.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 3,420 | 43.1% |
| property | 1,440 | 18.1% |
| overridden | 1,080 | 13.6% |
| method | 740 | 9.3% |
| not in keys | 480 | 6.0% |
| class attr simple | 360 | 4.5% |
| not managed dict | 160 | 2.0% |
| overriding descriptor | 140 | 1.8% |
| no dict | 120 | 1.5% |


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
|     deferred | 537,063 | 10.4% |
|          hit | 4,638,425 | 89.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,620 | 65.1% |
| Failure | 1,938 | 34.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,140 | 58.8% |
| py simple | 778 | 40.1% |
| other | 20 | 1.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,520,036 | 20.2% |
|          hit | 33,606,179 | 79.7% |
|         miss | 18,195 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,358 | 46.4% |
| Failure | 21,246 | 53.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 6,328 | 29.8% |
| set | 5,740 | 27.0% |
| tuple | 3,220 | 15.2% |
| sequence | 2,505 | 11.8% |
| mapping | 1,187 | 5.6% |
| bytes | 888 | 4.2% |
| float | 863 | 4.1% |
| other | 300 | 1.4% |
| bytearray | 195 | 0.9% |
| number | 20 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,876 | 0.1% |
|          hit | 4,538,660 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,580 | 90.8% |
| Failure | 260 | 9.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 260 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 888,027,115 | 56.1% |
| Not specialized | 160,765,941 | 10.2% |
| Specialized hits | 530,927,926 | 33.5% |
| Specialized misses | 3,420,273 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 27,018,367 | 38.3% |
| LOAD_ATTR | 20,330,014 | 28.8% |
| TO_BOOL | 8,520,036 | 12.1% |
| FOR_ITER | 6,056,524 | 8.6% |
| BINARY_OP | 3,615,434 | 5.1% |
| COMPARE_OP | 1,448,260 | 2.1% |
| BINARY_SUBSCR | 1,422,650 | 2.0% |
| STORE_ATTR | 1,002,392 | 1.4% |
| STORE_SUBSCR | 537,063 | 0.8% |
| SEND | 510,463 | 0.7% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,138,117 | 33.2% |
| STORE_ATTR_SLOT | 901,407 | 26.3% |
| LOAD_ATTR_INSTANCE_VALUE | 369,773 | 10.8% |
| LOAD_ATTR_METHOD_NO_DICT | 362,552 | 10.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 181,773 | 5.3% |
| CALL_PY_EXACT_ARGS | 114,200 | 3.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 91,677 | 2.7% |
| LOAD_ATTR_WITH_HINT | 58,979 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 40,299 | 1.2% |
| LOAD_ATTR_MODULE | 35,300 | 1.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 25,372,838 | 33.6% |
| Calls to Python functions inlined | 50,158,861 | 66.4% |
| Calls via PyEval_EvalFrame (total) | 25,372,838 | 33.6% |
| Calls via PyEval_EvalFrame (vector) | 23,672,195 | 31.3% |
| Calls via PyEval_EvalFrame (generator) | 1,700,643 | 2.3% |
| Calls via PyEval_EvalFrame (legacy) | 640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 23,670,615 | 31.3% |
| Calls via PyEval_EvalFrame (build class) | 940 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,340,245 | 4.4% |
| Calls via PyEval_EvalFrame (function ex) | 5,750,378 | 7.6% |
| Calls via PyEval_EvalFrame (api) | 5,269,242 | 7.0% |
| Calls via PyEval_EvalFrame (method) | 1,469,157 | 1.9% |
| Frame objects created | 1,430,253 | 1.9% |
| Frames pushed | 38,695,236 | 51.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 100,452,227 | 47.9% |
| Frees to freelist | 100,821,002 |  |
| Allocations | 109,283,320 | 52.1% |
| Allocations to 512 bytes | 108,095,558 | 51.5% |
| Allocations to 4 kbytes | 915,427 | 0.4% |
| Allocations over 4 kbytes | 272,335 | 0.1% |
| Frees | 102,632,408 |  |
| New values | 297,352 |  |
| Interpreter increfs | 796,349,434 | 74.9% |
| Interpreter decrefs | 903,553,006 | 73.0% |
| Increfs | 266,206,585 | 25.1% |
| Decrefs | 334,749,762 | 27.0% |
| Materialize dict (on request) | 2,560 | 0.9% |
| Materialize dict (new key) | 240 | 0.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,520 | 0.8% |
| Method cache hits | 24,048,117 |  |
| Method cache misses | 297,556 |  |
| Method cache collisions | 535,467 |  |
| Method cache dunder hits | 34,254,645 |  |
| Method cache dunder misses | 241,824 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 8,619 | 590,588 | 60,636,882 |
| 1 | 780 | 268,749 | 39,423,926 |
| 2 | 80 | 37,089 | 88,363,694 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,383 |  |
| Traces created | 4,076 | 93.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 76 | 1.7% |
| Trace too long | 0 | 0.0% |
| Trace too short | 307 | 7.0% |
| Inner loop found | 100 | 2.3% |
| Recursive call | 0 | 0.0% |
| Traces executed | 11,314,017 |  |
| Uops executed | 206,224,358 | 18.23 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.5% |
| <= 16 | 200 | 4.9% |
| <= 32 | 1,664 | 40.8% |
| <= 64 | 1,168 | 28.7% |
| <= 128 | 722 | 17.7% |
| <= 256 | 300 | 7.4% |
| <= 512 | 2 | 0.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 40 | 1.0% |
| <= 8 | 260 | 6.4% |
| <= 16 | 1,262 | 31.0% |
| <= 32 | 1,430 | 35.1% |
| <= 64 | 742 | 18.2% |
| <= 128 | 300 | 7.4% |
| <= 256 | 42 | 1.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 180 | 0.0% |
| <= 2 | 5,357,342 | 47.4% |
| <= 4 | 292,643 | 2.6% |
| <= 8 | 168,486 | 1.5% |
| <= 16 | 1,576,470 | 13.9% |
| <= 32 | 1,782,256 | 15.8% |
| <= 64 | 1,952,327 | 17.3% |
| <= 128 | 168,902 | 1.5% |
| <= 256 | 3,616 | 0.0% |
| <= 512 | 618 | 0.0% |
| <= 1,024 | 1,374 | 0.0% |
| <= 2,048 | 3,722 | 0.0% |
| <= 4,096 | 4,261 | 0.0% |
| <= 8,192 | 1,820 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 30,221,230 | 14.7% | 14.7% |  |
| LOAD_FAST | 26,215,262 | 12.7% | 27.4% |  |
| _CHECK_VALIDITY | 24,074,459 | 11.7% | 39.0% |  |
| _GUARD_TYPE_VERSION | 13,131,141 | 6.4% | 45.4% | 1.7% |
| STORE_FAST | 11,867,765 | 5.8% | 51.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 5,758,818 | 2.8% | 54.0% |  |
| _GUARD_IS_FALSE_POP | 5,285,697 | 2.6% | 56.5% | 4.5% |
| _FOR_ITER_TIER_TWO | 5,147,749 | 2.5% | 59.0% | 58.9% |
| _EXIT_TRACE | 4,712,869 | 2.3% | 61.3% |  |
| LOAD_CONST | 3,494,124 | 1.7% | 63.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 3,332,597 | 1.6% | 64.6% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 3,332,597 | 1.6% | 66.2% |  |
| _GUARD_GLOBALS_VERSION | 3,304,972 | 1.6% | 67.8% | 0.3% |
| _ITER_CHECK_LIST | 2,709,767 | 1.3% | 69.1% | 0.0% |
| _GUARD_NOT_EXHAUSTED_LIST | 2,709,587 | 1.3% | 70.5% | 46.9% |
| _LOAD_ATTR_SLOT | 2,558,133 | 1.2% | 71.7% |  |
| TO_BOOL_BOOL | 2,441,826 | 1.2% | 72.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 2,184,792 | 1.1% | 73.9% | 54.6% |
| _ITER_CHECK_TUPLE | 2,184,792 | 1.1% | 75.0% |  |
| _CHECK_PEP_523 | 2,182,511 | 1.1% | 76.1% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 2,182,511 | 1.1% | 77.1% |  |
| _CHECK_STACK_SPACE | 2,182,511 | 1.1% | 78.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 2,182,511 | 1.1% | 79.2% |  |
| _PUSH_FRAME | 2,182,511 | 1.1% | 80.3% |  |
| _SAVE_RETURN_OFFSET | 2,182,511 | 1.1% | 81.3% |  |
| _LOAD_GLOBAL_MODULE | 2,144,679 | 1.0% | 82.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,670,887 | 0.8% | 83.2% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,645,431 | 0.8% | 84.0% |  |
| LOAD_DEREF | 1,585,020 | 0.8% | 84.8% |  |
| _JUMP_TO_TOP | 1,552,888 | 0.8% | 85.5% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 1,542,360 | 0.7% | 86.3% | 16.1% |
| _ITER_CHECK_RANGE | 1,542,360 | 0.7% | 87.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,469,376 | 0.7% | 87.7% |  |
| _ITER_NEXT_LIST | 1,438,308 | 0.7% | 88.4% |  |
| _GUARD_IS_TRUE_POP | 1,398,689 | 0.7% | 89.1% | 17.6% |
| _ITER_NEXT_RANGE | 1,294,625 | 0.6% | 89.7% |  |
| _GUARD_BUILTINS_VERSION | 1,150,073 | 0.6% | 90.3% | 0.6% |
| _LOAD_GLOBAL_BUILTINS | 1,142,813 | 0.6% | 90.8% |  |
| _LOAD_ATTR | 1,108,486 | 0.5% | 91.4% |  |
| _ITER_NEXT_TUPLE | 992,761 | 0.5% | 91.9% |  |
| POP_TOP | 836,672 | 0.4% | 92.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 811,400 | 0.4% | 92.7% |  |
| COMPARE_OP_STR | 790,016 | 0.4% | 93.0% |  |
| _CHECK_ATTR_WITH_HINT | 759,676 | 0.4% | 93.4% |  |
| _LOAD_ATTR_WITH_HINT | 759,676 | 0.4% | 93.8% |  |
| BINARY_SUBSCR_DICT | 738,400 | 0.4% | 94.1% |  |
| CONTAINS_OP | 732,590 | 0.4% | 94.5% |  |
| TO_BOOL_STR | 674,436 | 0.3% | 94.8% |  |
| GET_ITER | 564,624 | 0.3% | 95.1% |  |
| _GUARD_IS_NOT_NONE_POP | 558,093 | 0.3% | 95.4% | 0.3% |
| _TO_BOOL | 537,892 | 0.3% | 95.6% |  |
| RESUME_CHECK | 489,160 | 0.2% | 95.9% | 0.0% |
| IS_OP | 471,720 | 0.2% | 96.1% |  |
| _GUARD_KEYS_VERSION | 399,689 | 0.2% | 96.3% | 8.6% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 399,689 | 0.2% | 96.5% |  |
| _COMPARE_OP | 398,416 | 0.2% | 96.7% |  |
| BUILD_TUPLE | 370,860 | 0.2% | 96.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 365,103 | 0.2% | 97.0% |  |
| PUSH_NULL | 359,095 | 0.2% | 97.2% |  |
| TO_BOOL_INT | 341,484 | 0.2% | 97.4% |  |
| MAKE_CELL | 300,546 | 0.1% | 97.5% |  |
| _BINARY_OP | 292,562 | 0.1% | 97.7% |  |
| BUILD_LIST | 278,272 | 0.1% | 97.8% |  |
| _GUARD_IS_NONE_POP | 259,950 | 0.1% | 97.9% | 31.6% |
| LIST_APPEND | 241,050 | 0.1% | 98.0% |  |
| CALL_BUILTIN_CLASS | 240,332 | 0.1% | 98.2% |  |
| CALL_TYPE_1 | 198,560 | 0.1% | 98.2% |  |
| STORE_SUBSCR_DICT | 195,717 | 0.1% | 98.3% |  |
| MAP_ADD | 182,021 | 0.1% | 98.4% |  |
| MAKE_FUNCTION | 166,080 | 0.1% | 98.5% |  |
| _GUARD_BOTH_INT | 151,280 | 0.1% | 98.6% | 0.2% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 144,639 | 0.1% | 98.7% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 144,639 | 0.1% | 98.7% |  |
| _BINARY_SUBSCR | 139,871 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 129,033 | 0.1% | 98.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 124,740 | 0.1% | 98.9% |  |
| _GUARD_BOTH_UNICODE | 124,400 | 0.1% | 99.0% |  |
| _BINARY_OP_ADD_UNICODE | 124,400 | 0.1% | 99.0% |  |
| _CHECK_ATTR_MODULE | 122,903 | 0.1% | 99.1% |  |
| _LOAD_ATTR_MODULE | 122,903 | 0.1% | 99.2% |  |
| COMPARE_OP_INT | 110,949 | 0.1% | 99.2% | 9.7% |
| UNPACK_SEQUENCE_TUPLE | 110,862 | 0.1% | 99.3% |  |
| CALL_ISINSTANCE | 103,700 | 0.1% | 99.3% |  |
| CALL_LEN | 101,281 | 0.0% | 99.4% |  |
| CALL_INTRINSIC_1 | 97,962 | 0.0% | 99.4% |  |
| LIST_EXTEND | 97,962 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST | 92,320 | 0.0% | 99.5% |  |
| _BINARY_OP_ADD_INT | 90,647 | 0.0% | 99.5% |  |
| BEFORE_WITH | 88,002 | 0.0% | 99.6% |  |
| SET_FUNCTION_ATTRIBUTE | 87,200 | 0.0% | 99.6% |  |
| UNARY_NEGATIVE | 86,800 | 0.0% | 99.7% |  |
| _STORE_ATTR_SLOT | 86,800 | 0.0% | 99.7% |  |
| COPY_FREE_VARS | 83,480 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_LIST_INT | 71,306 | 0.0% | 99.8% |  |
| COPY | 64,500 | 0.0% | 99.8% |  |
| COMPARE_OP_FLOAT | 56,994 | 0.0% | 99.9% | 2.8% |
| _BINARY_OP_SUBTRACT_INT | 55,555 | 0.0% | 99.9% |  |
| SWAP | 41,418 | 0.0% | 99.9% |  |
| DELETE_FAST | 36,866 | 0.0% | 99.9% |  |
| _POP_FRAME | 26,062 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 18,966 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 14,154 | 0.0% | 99.9% | 2.8% |
| _GUARD_DORV_VALUES | 13,880 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 13,880 | 0.0% | 100.0% |  |
| BUILD_MAP | 11,162 | 0.0% | 100.0% |  |
| DICT_MERGE | 11,162 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 8,290 | 0.0% | 100.0% |  |
| BINARY_SLICE | 7,890 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 7,600 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 7,170 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 7,050 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 5,000 | 0.0% | 100.0% |  |
| BUILD_STRING | 5,000 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 4,798 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 4,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 3,100 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 1,120 | 0.0% | 100.0% | 94.6% |
| _STORE_SUBSCR | 1,080 | 0.0% | 100.0% |  |
| BUILD_SET | 880 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 880 | 0.0% | 100.0% |  |
| SET_ADD | 880 | 0.0% | 100.0% |  |
| CALL_STR_1 | 420 | 0.0% | 100.0% |  |
| STORE_DEREF | 400 | 0.0% | 100.0% |  |
| UNARY_NOT | 200 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 62 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 60 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 824 |
| FOR_ITER_GEN | 307 |
| CALL_PY_WITH_DEFAULTS | 280 |
| CALL_KW | 264 |
| YIELD_VALUE | 180 |
| CALL_LIST_APPEND | 124 |
| CALL_FUNCTION_EX | 100 |
| LOAD_ATTR_PROPERTY | 80 |
| CALL_ALLOC_AND_ENTER_INIT | 40 |
| BINARY_SUBSCR_GETITEM | 20 |


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
