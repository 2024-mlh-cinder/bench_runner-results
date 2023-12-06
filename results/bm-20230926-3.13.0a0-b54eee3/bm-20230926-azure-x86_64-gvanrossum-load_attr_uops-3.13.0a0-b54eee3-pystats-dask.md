
# Pystats results

- benchmark: dask
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 628,370,121 | 20.3% | 20.3% |  |
| LOAD_CONST | 210,255,761 | 6.8% | 27.1% |  |
| POP_JUMP_IF_FALSE | 209,094,444 | 6.7% | 33.8% |  |
| STORE_FAST | 168,216,367 | 5.4% | 39.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 142,032,488 | 4.6% | 43.8% | 0.2% |
| COMPARE_OP_INT | 107,976,792 | 3.5% | 47.3% | 0.1% |
| LOAD_GLOBAL_BUILTIN | 103,140,567 | 3.3% | 50.6% | 0.0% |
| LOAD_GLOBAL_MODULE | 100,617,339 | 3.2% | 53.9% | 0.0% |
| RESUME_CHECK | 100,141,212 | 3.2% | 57.1% | 0.0% |
| LOAD_FAST_LOAD_FAST | 67,824,454 | 2.2% | 59.3% |  |
| TO_BOOL_BOOL | 67,053,212 | 2.2% | 61.5% |  |
| RETURN_VALUE | 65,992,151 | 2.1% | 63.6% |  |
| POP_TOP | 60,593,356 | 2.0% | 65.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 56,261,944 | 1.8% | 67.4% | 0.0% |
| PUSH_NULL | 52,850,557 | 1.7% | 69.1% |  |
| CALL_PY_EXACT_ARGS | 44,708,133 | 1.4% | 70.5% | 0.2% |
| CALL_ISINSTANCE | 34,852,573 | 1.1% | 71.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 33,500,344 | 1.1% | 72.7% | 0.9% |
| LOAD_DEREF | 33,349,195 | 1.1% | 73.8% |  |
| RETURN_CONST | 32,829,580 | 1.1% | 74.9% |  |
| BINARY_OP_SUBTRACT_INT | 31,302,012 | 1.0% | 75.9% |  |
| BINARY_OP | 29,239,671 | 0.9% | 76.8% |  |
| LOAD_ATTR_SLOT | 27,491,066 | 0.9% | 77.7% | 3.7% |
| CALL_LEN | 26,967,203 | 0.9% | 78.6% |  |
| SWAP | 26,421,288 | 0.9% | 79.4% |  |
| BUILD_TUPLE | 26,089,434 | 0.8% | 80.3% |  |
| BINARY_OP_ADD_INT | 23,802,443 | 0.8% | 81.0% | 0.0% |
| COPY | 22,306,965 | 0.7% | 81.7% |  |
| CALL | 21,321,353 | 0.7% | 82.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 20,883,595 | 0.7% | 83.1% | 0.0% |
| NOP | 19,992,426 | 0.6% | 83.8% |  |
| EXTENDED_ARG | 19,967,656 | 0.6% | 84.4% |  |
| CALL_PY_WITH_DEFAULTS | 19,468,254 | 0.6% | 85.0% | 0.0% |
| INTERPRETER_EXIT | 18,831,293 | 0.6% | 85.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 16,869,765 | 0.5% | 86.2% | 0.0% |
| LOAD_ATTR | 16,791,139 | 0.5% | 86.7% |  |
| JUMP_BACKWARD | 16,570,030 | 0.5% | 87.3% |  |
| LOAD_ATTR_WITH_HINT | 16,441,556 | 0.5% | 87.8% | 0.9% |
| LOAD_ATTR_MODULE | 14,701,067 | 0.5% | 88.3% | 0.0% |
| STORE_FAST_STORE_FAST | 14,170,101 | 0.5% | 88.7% |  |
| GET_ITER | 13,277,930 | 0.4% | 89.1% |  |
| STORE_ATTR_SLOT | 12,225,923 | 0.4% | 89.5% | 6.9% |
| POP_JUMP_IF_TRUE | 12,106,601 | 0.4% | 89.9% |  |
| COMPARE_OP | 11,953,414 | 0.4% | 90.3% |  |
| BUILD_MAP | 11,945,183 | 0.4% | 90.7% |  |
| FOR_ITER | 11,437,508 | 0.4% | 91.1% |  |
| POP_JUMP_IF_NOT_NONE | 11,194,332 | 0.4% | 91.4% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 10,299,318 | 0.3% | 91.8% |  |
| BINARY_SUBSCR_DICT | 10,175,462 | 0.3% | 92.1% |  |
| JUMP_FORWARD | 10,141,010 | 0.3% | 92.4% |  |
| MAKE_CELL | 9,607,927 | 0.3% | 92.7% |  |
| BUILD_LIST | 9,225,357 | 0.3% | 93.0% |  |
| CALL_FUNCTION_EX | 9,190,519 | 0.3% | 93.3% |  |
| BINARY_SUBSCR | 8,223,948 | 0.3% | 93.6% |  |
| CONTAINS_OP | 8,158,390 | 0.3% | 93.9% |  |
| UNPACK_SEQUENCE_TUPLE | 8,155,865 | 0.3% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 8,108,665 | 0.3% | 94.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 8,036,226 | 0.3% | 94.6% | 1.0% |
| POP_JUMP_IF_NONE | 7,877,584 | 0.3% | 94.9% |  |
| IS_OP | 7,572,679 | 0.2% | 95.1% |  |
| CALL_BUILTIN_FAST | 7,478,129 | 0.2% | 95.4% | 0.0% |
| FOR_ITER_RANGE | 7,293,407 | 0.2% | 95.6% |  |
| CALL_BUILTIN_CLASS | 7,243,653 | 0.2% | 95.8% |  |
| DICT_MERGE | 6,906,401 | 0.2% | 96.1% |  |
| CALL_KW | 6,806,701 | 0.2% | 96.3% |  |
| TO_BOOL | 6,714,303 | 0.2% | 96.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 6,537,884 | 0.2% | 96.7% |  |
| LIST_EXTEND | 6,427,410 | 0.2% | 96.9% |  |
| CALL_INTRINSIC_1 | 6,356,594 | 0.2% | 97.1% |  |
| FOR_ITER_TUPLE | 6,123,631 | 0.2% | 97.3% |  |
| CALL_TYPE_1 | 6,059,854 | 0.2% | 97.5% |  |
| STORE_SUBSCR_DICT | 6,056,031 | 0.2% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,571,799 | 0.2% | 97.9% | 2.4% |
| BINARY_SLICE | 4,627,743 | 0.1% | 98.0% |  |
| COMPARE_OP_STR | 4,542,524 | 0.1% | 98.2% | 0.0% |
| CALL_BUILTIN_O | 3,671,494 | 0.1% | 98.3% | 0.0% |
| FOR_ITER_LIST | 3,632,201 | 0.1% | 98.4% |  |
| TO_BOOL_NONE | 3,492,389 | 0.1% | 98.5% | 0.2% |
| COPY_FREE_VARS | 3,110,192 | 0.1% | 98.6% |  |
| LOAD_ATTR_PROPERTY | 2,051,497 | 0.1% | 98.7% | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,920,123 | 0.1% | 98.8% | 0.0% |
| BINARY_SUBSCR_TUPLE_INT | 1,867,519 | 0.1% | 98.8% | 7.2% |
| TO_BOOL_INT | 1,690,683 | 0.1% | 98.9% |  |
| BEFORE_WITH | 1,666,390 | 0.1% | 98.9% |  |
| LOAD_FAST_AND_CLEAR | 1,634,662 | 0.1% | 99.0% |  |
| COMPARE_OP_FLOAT | 1,463,841 | 0.0% | 99.0% | 0.1% |
| CALL_LIST_APPEND | 1,425,066 | 0.0% | 99.1% |  |
| BINARY_SUBSCR_LIST_INT | 1,377,586 | 0.0% | 99.1% | 9.7% |
| TO_BOOL_LIST | 1,277,526 | 0.0% | 99.2% |  |
| MAKE_FUNCTION | 1,209,957 | 0.0% | 99.2% |  |
| SET_FUNCTION_ATTRIBUTE | 1,194,677 | 0.0% | 99.2% |  |
| YIELD_VALUE | 1,160,207 | 0.0% | 99.3% |  |
| STORE_ATTR_WITH_HINT | 1,067,159 | 0.0% | 99.3% | 0.4% |
| DELETE_SUBSCR | 1,063,246 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 901,089 | 0.0% | 99.4% | 0.2% |
| BUILD_CONST_KEY_MAP | 890,032 | 0.0% | 99.4% |  |
| STORE_ATTR | 755,617 | 0.0% | 99.4% |  |
| STORE_FAST_LOAD_FAST | 749,033 | 0.0% | 99.5% |  |
| RETURN_GENERATOR | 722,066 | 0.0% | 99.5% |  |
| CALL_TUPLE_1 | 694,719 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 690,671 | 0.0% | 99.5% |  |
| POP_EXCEPT | 690,666 | 0.0% | 99.6% |  |
| STORE_DEREF | 665,799 | 0.0% | 99.6% |  |
| MAP_ADD | 653,200 | 0.0% | 99.6% |  |
| TO_BOOL_ALWAYS_TRUE | 640,482 | 0.0% | 99.6% | 1.0% |
| BINARY_OP_SUBTRACT_FLOAT | 619,853 | 0.0% | 99.6% |  |
| TO_BOOL_STR | 611,525 | 0.0% | 99.7% | 0.0% |
| CHECK_EXC_MATCH | 590,955 | 0.0% | 99.7% |  |
| LIST_APPEND | 579,646 | 0.0% | 99.7% |  |
| SEND_GEN | 522,126 | 0.0% | 99.7% | 0.0% |
| BINARY_OP_MULTIPLY_INT | 514,958 | 0.0% | 99.7% |  |
| LOAD_SUPER_ATTR_METHOD | 508,356 | 0.0% | 99.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 487,090 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_GETITEM | 469,818 | 0.0% | 99.8% | 0.0% |
| BUILD_SET | 451,985 | 0.0% | 99.8% |  |
| END_SEND | 437,222 | 0.0% | 99.8% |  |
| GET_AWAITABLE | 436,356 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 420,980 | 0.0% | 99.8% | 0.3% |
| FORMAT_SIMPLE | 419,308 | 0.0% | 99.8% |  |
| SEND | 403,734 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 400,455 | 0.0% | 99.9% |  |
| BUILD_STRING | 373,193 | 0.0% | 99.9% |  |
| DELETE_FAST | 327,618 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 308,838 | 0.0% | 99.9% | 0.1% |
| RERAISE | 272,480 | 0.0% | 99.9% |  |
| CALL_STR_1 | 240,214 | 0.0% | 99.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 220,789 | 0.0% | 99.9% | 0.4% |
| EXIT_INIT_CHECK | 219,949 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 205,983 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 191,568 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 168,958 | 0.0% | 100.0% | 18.4% |
| IMPORT_FROM | 152,891 | 0.0% | 100.0% |  |
| IMPORT_NAME | 152,411 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 148,882 | 0.0% | 100.0% | 1.1% |
| BINARY_SUBSCR_STR_INT | 145,260 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 133,803 | 0.0% | 100.0% |  |
| SET_ADD | 133,320 | 0.0% | 100.0% |  |
| UNARY_INVERT | 76,278 | 0.0% | 100.0% |  |
| BUILD_SLICE | 75,439 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 75,352 | 0.0% | 100.0% | 0.4% |
| UNPACK_EX | 66,000 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 66,000 | 0.0% | 100.0% |  |
| SET_UPDATE | 66,000 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 65,769 | 0.0% | 100.0% |  |
| DICT_UPDATE | 38,799 | 0.0% | 100.0% |  |
| STORE_SLICE | 37,419 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,489 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 9,625 | 0.0% | 100.0% |  |
| DELETE_ATTR | 8,097 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 8,040 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 7,469 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,183 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,720 | 0.0% | 100.0% | 95.2% |
| END_FOR | 3,045 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 2,580 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,860 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 1,323 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 900 | 0.0% | 100.0% |  |
| UNARY_NOT | 783 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 591 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 300 | 0.0% | 100.0% |  |
| RESUME | 169 | 0.0% | 100.0% | 2816.0% |
| FORMAT_WITH_SPEC | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 140,153,123 | 4.5% | 4.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 110,021,266 | 3.6% | 8.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 100,731,796 | 3.3% | 11.3% |
| STORE_FAST LOAD_FAST | 96,626,631 | 3.1% | 14.4% |
| LOAD_FAST LOAD_CONST | 71,430,402 | 2.3% | 16.7% |
| LOAD_CONST COMPARE_OP_INT | 62,077,018 | 2.0% | 18.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 55,315,032 | 1.8% | 20.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 45,777,170 | 1.5% | 22.0% |
| RESUME_CHECK LOAD_FAST | 45,283,038 | 1.5% | 23.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 43,014,150 | 1.4% | 24.9% |
| PUSH_NULL LOAD_FAST | 39,280,861 | 1.3% | 26.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 38,950,231 | 1.3% | 27.4% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 37,059,974 | 1.2% | 28.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 36,428,741 | 1.2% | 29.8% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 36,381,982 | 1.2% | 30.9% |
| LOAD_FAST PUSH_NULL | 35,022,091 | 1.1% | 32.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 34,502,722 | 1.1% | 33.2% |
| LOAD_CONST LOAD_FAST | 31,022,893 | 1.0% | 34.2% |
| POP_TOP LOAD_FAST | 29,723,381 | 1.0% | 35.1% |
| LOAD_CONST BINARY_OP | 26,322,601 | 0.8% | 36.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 25,773,276 | 0.8% | 36.8% |
| RETURN_CONST POP_TOP | 25,561,645 | 0.8% | 37.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 24,624,435 | 0.8% | 38.4% |
| BINARY_OP LOAD_CONST | 22,348,648 | 0.7% | 39.2% |
| LOAD_CONST STORE_FAST | 22,207,574 | 0.7% | 39.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 19,580,438 | 0.6% | 40.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 19,291,706 | 0.6% | 41.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 19,042,145 | 0.6% | 41.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 18,804,680 | 0.6% | 42.3% |
| RETURN_VALUE STORE_FAST | 18,693,282 | 0.6% | 43.0% |
| LOAD_FAST RETURN_VALUE | 18,647,275 | 0.6% | 43.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 17,873,928 | 0.6% | 44.1% |
| CACHE RESUME_CHECK | 17,222,067 | 0.6% | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 16,659,766 | 0.5% | 45.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 15,421,592 | 0.5% | 45.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,228,526 | 0.5% | 46.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 14,578,627 | 0.5% | 46.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 14,446,793 | 0.5% | 47.2% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 14,423,994 | 0.5% | 47.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 14,352,612 | 0.5% | 48.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 14,347,152 | 0.5% | 48.5% |
| STORE_FAST LOAD_CONST | 14,081,717 | 0.5% | 49.0% |
| LOAD_FAST CALL_LEN | 13,658,096 | 0.4% | 49.4% |
| LOAD_DEREF LOAD_ATTR_INSTANCE_VALUE | 13,648,221 | 0.4% | 49.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 13,601,377 | 0.4% | 50.3% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 13,460,946 | 0.4% | 50.8% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 13,354,080 | 0.4% | 51.2% |
| RETURN_VALUE INTERPRETER_EXIT | 12,846,457 | 0.4% | 51.6% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 12,705,728 | 0.4% | 52.0% |
| CALL_LEN LOAD_FAST | 12,649,513 | 0.4% | 52.4% |
| NOP LOAD_FAST | 12,583,926 | 0.4% | 52.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 12,577,897 | 0.4% | 53.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 12,450,623 | 0.4% | 53.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 12,444,196 | 0.4% | 54.0% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 12,349,355 | 0.4% | 54.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 12,267,068 | 0.4% | 54.8% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 11,965,369 | 0.4% | 55.2% |
| LOAD_GLOBAL_BUILTIN BUILD_TUPLE | 11,860,708 | 0.4% | 55.6% |
| LOAD_FAST LOAD_ATTR | 11,843,938 | 0.4% | 56.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 11,744,765 | 0.4% | 56.4% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 11,714,268 | 0.4% | 56.7% |
| STORE_FAST NOP | 11,633,196 | 0.4% | 57.1% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST | 11,613,676 | 0.4% | 57.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_INT | 11,608,276 | 0.4% | 57.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 11,398,652 | 0.4% | 58.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 11,356,635 | 0.4% | 58.6% |
| COMPARE_OP POP_JUMP_IF_FALSE | 10,795,514 | 0.3% | 58.9% |
| LOAD_FAST COPY | 10,773,656 | 0.3% | 59.3% |
| LOAD_CONST LOAD_CONST | 10,768,513 | 0.3% | 59.6% |
| LOAD_FAST SWAP | 10,567,175 | 0.3% | 60.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_LAZY_DICT | 10,299,318 | 0.3% | 60.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 10,291,604 | 0.3% | 60.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 10,222,894 | 0.3% | 61.0% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 10,191,202 | 0.3% | 61.3% |
| LOAD_FAST BINARY_OP_ADD_INT | 10,021,639 | 0.3% | 61.6% |
| LOAD_GLOBAL_MODULE STORE_FAST | 9,974,800 | 0.3% | 61.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 9,930,426 | 0.3% | 62.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 9,867,717 | 0.3% | 62.6% |
| BINARY_OP_ADD_INT SWAP | 9,655,914 | 0.3% | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 9,569,661 | 0.3% | 63.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 8,843,133 | 0.3% | 63.5% |
| POP_TOP RETURN_CONST | 8,600,876 | 0.3% | 63.8% |
| LOAD_FAST CALL | 8,594,629 | 0.3% | 64.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,587,475 | 0.3% | 64.3% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 8,567,688 | 0.3% | 64.6% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 8,567,688 | 0.3% | 64.9% |
| STORE_FAST LOAD_DEREF | 8,260,804 | 0.3% | 65.1% |
| LOAD_FAST BUILD_TUPLE | 8,259,941 | 0.3% | 65.4% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 8,075,100 | 0.3% | 65.7% |
| STORE_FAST_STORE_FAST STORE_FAST | 8,073,537 | 0.3% | 65.9% |
| BUILD_TUPLE RETURN_VALUE | 8,014,346 | 0.3% | 66.2% |
| RETURN_VALUE POP_TOP | 7,933,489 | 0.3% | 66.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 7,873,614 | 0.3% | 66.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 7,791,894 | 0.3% | 66.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 7,775,157 | 0.3% | 67.2% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS STORE_FAST | 7,764,306 | 0.3% | 67.4% |
| MAKE_CELL RESUME_CHECK | 7,688,883 | 0.2% | 67.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 7,605,700 | 0.2% | 67.9% |
| RESUME_CHECK LOAD_CONST | 7,563,796 | 0.2% | 68.2% |
| LOAD_ATTR_INSTANCE_VALUE CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 7,512,520 | 0.2% | 68.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,131,482 | 89.3% |
| LOAD_CONST | 300,453 | 6.5% |
| LOAD_FAST | 195,148 | 4.2% |
| LOAD_ATTR_INSTANCE_VALUE | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,136,972 | 89.4% |
| CALL_BUILTIN_CLASS | 73,860 | 1.6% |
| GET_ITER | 67,680 | 1.5% |
| CALL_PY_WITH_DEFAULTS | 66,000 | 1.4% |
| CALL_METHOD_DESCRIPTOR_O | 66,000 | 1.4% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 37,299 | 99.7% |
| LOAD_FAST | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,299 | 99.7% |
| LOAD_CONST | 120 | 0.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 17,222,067 | 90.5% |
| COPY_FREE_VARS | 1,033,892 | 5.4% |
| POP_TOP | 437,768 | 2.3% |
| MAKE_CELL | 199,680 | 1.0% |
| RETURN_GENERATOR | 101,291 | 0.5% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,500 | 93.3% |
| LOAD_ATTR_WITH_HINT | 360 | 4.5% |
| CALL | 120 | 1.5% |
| CALL_KW | 60 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 8,040 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,249,132 | 75.0% |
| LOAD_GLOBAL_MODULE | 139,213 | 8.4% |
| LOAD_FAST | 132,060 | 7.9% |
| LOAD_ATTR_WITH_HINT | 132,020 | 7.9% |
| RETURN_VALUE | 7,409 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,662,800 | 99.8% |
| STORE_FAST | 3,590 | 0.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,320 | 71.0% |
| BINARY_OP_ADD_UNICODE | 420 | 22.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,320 | 71.0% |
| JUMP_BACKWARD | 420 | 22.6% |
| LOAD_FAST | 120 | 6.5% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,075,950 | 86.0% |
| LOAD_FAST | 698,199 | 8.5% |
| COPY | 265,740 | 3.2% |
| LOAD_CONST | 180,796 | 2.2% |
| BINARY_SUBSCR | 3,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,207,926 | 87.6% |
| RETURN_VALUE | 258,060 | 3.1% |
| LOAD_CONST | 199,120 | 2.4% |
| LOAD_FAST | 132,014 | 1.6% |
| LOAD_ATTR_METHOD_NO_DICT | 122,740 | 1.5% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 514,317 | 87.0% |
| LOAD_ATTR_MODULE | 72,659 | 12.3% |
| BUILD_TUPLE | 3,660 | 0.6% |
| LOAD_GLOBAL_MODULE | 277 | 0.0% |
| LOAD_GLOBAL | 38 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 590,955 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 591 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 434 | 73.4% |
| JUMP_BACKWARD | 157 | 26.6% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 722,124 | 67.9% |
| LOAD_FAST_LOAD_FAST | 199,263 | 18.7% |
| BUILD_SLICE | 75,379 | 7.1% |
| LOAD_ATTR_SLOT | 66,060 | 6.2% |
| LOAD_DEREF | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 338,920 | 34.0% |
| PUSH_EXC_INFO | 264,000 | 26.5% |
| RETURN_CONST | 193,741 | 19.4% |
| LOAD_FAST_LOAD_FAST | 66,481 | 6.7% |
| LOAD_CONST | 66,364 | 6.7% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,045 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 39.4% |
| STORE_FAST | 699 | 23.0% |
| LOAD_CONST | 660 | 21.7% |
| SWAP | 240 | 7.9% |
| RETURN_CONST | 126 | 4.1% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 229,909 | 52.6% |
| SEND | 156,743 | 35.8% |
| RETURN_CONST | 50,293 | 11.5% |
| JUMP_BACKWARD | 157 | 0.0% |
| SEND_GEN | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 261,015 | 59.7% |
| POP_TOP | 101,917 | 23.3% |
| UNPACK_SEQUENCE_TUPLE | 66,240 | 15.2% |
| SWAP | 7,500 | 1.7% |
| LOAD_DEREF | 180 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 219,949 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 219,949 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 285,996 | 68.2% |
| LOAD_FAST | 123,020 | 29.3% |
| CONVERT_VALUE | 7,469 | 1.8% |
| LOAD_GLOBAL_MODULE | 2,400 | 0.6% |
| CALL_LEN | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 328,318 | 78.3% |
| LOAD_CONST | 52,491 | 12.5% |
| LOAD_FAST | 38,499 | 9.2% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,565,466 | 26.9% |
| LOAD_ATTR | 3,555,347 | 26.8% |
| CALL_BUILTIN_CLASS | 2,130,807 | 16.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,899,900 | 14.3% |
| LOAD_ATTR_SLOT | 1,213,239 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 4,296,710 | 32.4% |
| FOR_ITER_TUPLE | 4,232,413 | 31.9% |
| FOR_ITER_RANGE | 1,764,648 | 13.3% |
| FOR_ITER_LIST | 1,625,065 | 12.2% |
| LOAD_FAST_AND_CLEAR | 1,046,662 | 7.9% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,320 | 99.8% |
| RETURN_GENERATOR | 3 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,323 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,846,457 | 68.2% |
| RETURN_CONST | 5,036,893 | 26.7% |
| YIELD_VALUE | 846,472 | 4.5% |
| RETURN_GENERATOR | 101,471 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,209,957 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,001,551 | 82.8% |
| STORE_DEREF | 66,005 | 5.5% |
| LOAD_FAST | 63,180 | 5.2% |
| CALL | 37,962 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 37,939 | 3.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,633,196 | 58.2% |
| RESUME_CHECK | 4,466,926 | 22.3% |
| POP_JUMP_IF_FALSE | 1,216,508 | 6.1% |
| STORE_ATTR_INSTANCE_VALUE | 503,589 | 2.5% |
| POP_JUMP_IF_TRUE | 452,871 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,583,926 | 62.9% |
| LOAD_FAST_LOAD_FAST | 3,905,874 | 19.5% |
| LOAD_GLOBAL_MODULE | 1,737,302 | 8.7% |
| LOAD_CONST | 476,886 | 2.4% |
| LOAD_GLOBAL_BUILTIN | 380,095 | 1.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 424,829 | 61.5% |
| COPY | 134,379 | 19.5% |
| STORE_FAST | 114,582 | 16.6% |
| STORE_SUBSCR_DICT | 11,057 | 1.6% |
| SWAP | 4,813 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 348,943 | 50.5% |
| RERAISE | 134,379 | 19.5% |
| EXTENDED_ARG | 104,264 | 15.1% |
| DELETE_FAST | 37,456 | 5.4% |
| LOAD_CONST | 37,121 | 5.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 25,561,645 | 42.2% |
| CALL_METHOD_DESCRIPTOR_O | 10,222,894 | 16.9% |
| RETURN_VALUE | 7,933,489 | 13.1% |
| CALL | 4,001,934 | 6.6% |
| SWAP | 3,558,344 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,723,381 | 49.1% |
| RETURN_CONST | 8,600,876 | 14.2% |
| JUMP_BACKWARD | 7,447,283 | 12.3% |
| RETURN_VALUE | 4,218,685 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 2,390,371 | 3.9% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 264,000 | 38.2% |
| BINARY_SUBSCR_DICT | 157,179 | 22.8% |
| CALL | 79,693 | 11.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 72,715 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 66,059 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 482,972 | 69.9% |
| WITH_EXCEPT_START | 133,803 | 19.4% |
| LOAD_GLOBAL_MODULE | 73,555 | 10.6% |
| LOAD_GLOBAL | 282 | 0.0% |
| DELETE_FAST | 59 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,022,091 | 66.3% |
| LOAD_ATTR_MODULE | 13,601,377 | 25.7% |
| LOAD_ATTR | 3,175,543 | 6.0% |
| LOAD_DEREF | 787,481 | 1.5% |
| RETURN_VALUE | 194,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,280,861 | 74.3% |
| LOAD_CONST | 6,815,380 | 12.9% |
| LOAD_FAST_LOAD_FAST | 3,742,222 | 7.1% |
| CALL | 1,947,912 | 3.7% |
| CALL_BUILTIN_CLASS | 328,440 | 0.6% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 208,530 | 28.9% |
| CALL_PY_EXACT_ARGS | 150,676 | 20.9% |
| CALL_KW | 105,582 | 14.6% |
| CACHE | 101,291 | 14.0% |
| CALL_PY_WITH_DEFAULTS | 77,666 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 256,056 | 35.5% |
| CALL_TUPLE_1 | 132,000 | 18.3% |
| INTERPRETER_EXIT | 101,471 | 14.1% |
| CALL_BUILTIN_O | 75,670 | 10.5% |
| CALL | 61,003 | 8.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,647,275 | 28.3% |
| BUILD_TUPLE | 8,014,346 | 12.1% |
| CALL_METHOD_DESCRIPTOR_O | 6,487,253 | 9.8% |
| RETURN_VALUE | 5,850,876 | 8.9% |
| POP_TOP | 4,218,685 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,693,282 | 28.3% |
| INTERPRETER_EXIT | 12,846,457 | 19.5% |
| POP_TOP | 7,933,489 | 12.0% |
| UNPACK_SEQUENCE_TUPLE | 6,039,422 | 9.2% |
| RETURN_VALUE | 5,850,876 | 8.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 265,740 | 66.4% |
| LOAD_FAST | 66,484 | 16.6% |
| LOAD_ATTR_INSTANCE_VALUE | 66,080 | 16.5% |
| LOAD_CONST | 960 | 0.2% |
| LOAD_ATTR_SLOT | 573 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 199,913 | 49.9% |
| LOAD_CONST | 66,360 | 16.6% |
| RETURN_CONST | 66,304 | 16.6% |
| LOAD_GLOBAL_MODULE | 66,120 | 16.5% |
| STORE_SUBSCR_DICT | 1,120 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,228,057 | 48.1% |
| LOAD_ATTR_SLOT | 1,326,220 | 19.8% |
| LOAD_ATTR_INSTANCE_VALUE | 835,748 | 12.4% |
| RETURN_VALUE | 720,608 | 10.7% |
| COPY | 317,627 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,469,558 | 66.6% |
| POP_JUMP_IF_TRUE | 2,157,114 | 32.1% |
| EXTENDED_ARG | 78,024 | 1.2% |
| TO_BOOL | 5,791 | 0.1% |
| TO_BOOL_BOOL | 2,353 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 38,259 | 50.2% |
| BINARY_OP | 38,019 | 49.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 76,278 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 66,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,000 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 720 | 92.0% |
| TO_BOOL_INT | 60 | 7.7% |
| TO_BOOL | 3 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 660 | 84.3% |
| STORE_FAST | 63 | 8.0% |
| COPY | 60 | 7.7% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 133,803 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 133,003 | 99.4% |
| TO_BOOL_BOOL | 780 | 0.6% |
| TO_BOOL | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,322,601 | 90.0% |
| LOAD_FAST | 599,799 | 2.1% |
| LOAD_FAST_LOAD_FAST | 537,451 | 1.8% |
| LOAD_GLOBAL_MODULE | 394,782 | 1.4% |
| LOAD_ATTR_WITH_HINT | 205,040 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 22,348,648 | 76.4% |
| STORE_FAST | 5,023,126 | 17.2% |
| TO_BOOL_INT | 517,897 | 1.8% |
| COPY | 219,648 | 0.8% |
| LOAD_FAST_LOAD_FAST | 197,397 | 0.7% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 890,032 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 328,697 | 36.9% |
| RETURN_VALUE | 145,217 | 16.3% |
| CALL_LIST_APPEND | 132,780 | 14.9% |
| LOAD_FAST | 104,559 | 11.7% |
| CALL_PY_EXACT_ARGS | 67,560 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,488,758 | 59.5% |
| LOAD_ATTR_SLOT | 1,112,980 | 12.1% |
| RESUME_CHECK | 822,159 | 8.9% |
| STORE_FAST | 368,579 | 4.0% |
| SWAP | 263,962 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,698,706 | 72.6% |
| STORE_FAST | 1,045,409 | 11.3% |
| RETURN_VALUE | 482,336 | 5.2% |
| BUILD_TUPLE | 384,160 | 4.2% |
| SWAP | 300,361 | 3.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 4,515,309 | 37.8% |
| STORE_FAST | 1,940,050 | 16.2% |
| LOAD_FAST | 1,364,324 | 11.4% |
| POP_JUMP_IF_NONE | 728,700 | 6.1% |
| SWAP | 588,960 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,722,975 | 56.3% |
| STORE_FAST | 3,788,245 | 31.7% |
| SWAP | 588,960 | 4.9% |
| LOAD_GLOBAL_MODULE | 325,120 | 2.7% |
| BUILD_LIST | 186,000 | 1.6% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 193,740 | 42.9% |
| LOAD_GLOBAL_MODULE | 132,245 | 29.3% |
| LOAD_ATTR | 66,000 | 14.6% |
| LOAD_CONST | 60,000 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 193,740 | 42.9% |
| CONTAINS_OP | 132,245 | 29.3% |
| LOAD_CONST | 66,000 | 14.6% |
| BINARY_OP | 60,000 | 13.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,718 | 99.0% |
| LOAD_CONST | 721 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 75,379 | 99.9% |
| BINARY_SUBSCR | 60 | 0.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 328,318 | 88.0% |
| LOAD_CONST | 44,875 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 153,999 | 41.3% |
| LOAD_CONST | 66,000 | 17.7% |
| BUILD_MAP | 66,000 | 17.7% |
| LOAD_FAST | 38,379 | 10.3% |
| LOAD_FAST_LOAD_FAST | 37,419 | 10.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 11,860,708 | 45.5% |
| LOAD_FAST | 8,259,941 | 31.7% |
| LOAD_FAST_LOAD_FAST | 1,870,862 | 7.2% |
| LOAD_GLOBAL_MODULE | 1,550,164 | 5.9% |
| CALL | 1,072,110 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,014,346 | 30.7% |
| CALL_ISINSTANCE | 6,965,748 | 26.7% |
| STORE_FAST | 6,360,265 | 24.4% |
| LOAD_CONST | 1,266,755 | 4.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,224,142 | 4.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,594,629 | 40.3% |
| LOAD_GLOBAL_MODULE | 2,837,445 | 13.3% |
| LOAD_FAST_LOAD_FAST | 2,154,747 | 10.1% |
| LOAD_CONST | 2,087,072 | 9.8% |
| PUSH_NULL | 1,947,912 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,213,120 | 19.8% |
| POP_TOP | 4,001,934 | 18.8% |
| STORE_FAST | 3,717,877 | 17.4% |
| RESUME_CHECK | 2,921,280 | 13.7% |
| LOAD_FAST | 1,075,399 | 5.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 6,906,401 | 75.1% |
| CALL_INTRINSIC_1 | 1,387,983 | 15.1% |
| LOAD_FAST | 734,336 | 8.0% |
| LOAD_ATTR_INSTANCE_VALUE | 66,000 | 0.7% |
| BUILD_MAP | 53,700 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,506,393 | 49.0% |
| POP_TOP | 2,334,682 | 25.4% |
| RETURN_VALUE | 860,364 | 9.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 462,000 | 5.0% |
| UNPACK_SEQUENCE_TUPLE | 324,000 | 3.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 6,352,572 | 99.9% |
| CACHE | 3,002 | 0.0% |
| RERAISE | 997 | 0.0% |
| RAISE_VARARGS | 23 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 4,515,309 | 71.0% |
| CALL_FUNCTION_EX | 1,387,983 | 21.8% |
| LOAD_CONST | 449,280 | 7.1% |
| RERAISE | 4,022 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,806,701 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,005,788 | 88.2% |
| MAKE_CELL | 351,327 | 5.2% |
| STORE_FAST | 128,289 | 1.9% |
| RETURN_GENERATOR | 105,582 | 1.6% |
| RETURN_VALUE | 75,255 | 1.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,579,153 | 46.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,346,818 | 44.7% |
| COPY | 533,748 | 4.5% |
| LOAD_FAST | 137,260 | 1.1% |
| LOAD_ATTR | 134,664 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,795,514 | 90.3% |
| EXTENDED_ARG | 1,147,312 | 9.6% |
| COMPARE_OP | 4,926 | 0.0% |
| COMPARE_OP_INT | 3,175 | 0.0% |
| POP_JUMP_IF_TRUE | 2,107 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,492,095 | 30.5% |
| LOAD_ATTR_INSTANCE_VALUE | 2,040,855 | 25.0% |
| LOAD_ATTR_WITH_HINT | 1,177,104 | 14.4% |
| LOAD_GLOBAL_MODULE | 546,147 | 6.7% |
| BUILD_TUPLE | 423,643 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,962,317 | 73.1% |
| RETURN_VALUE | 859,380 | 10.5% |
| POP_JUMP_IF_TRUE | 811,740 | 9.9% |
| COPY | 391,743 | 4.8% |
| SWAP | 132,250 | 1.6% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,300 | 71.0% |
| BINARY_SLICE | 1,200 | 16.1% |
| LOAD_FAST | 966 | 12.9% |
| LOAD_ATTR | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 7,469 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,773,656 | 48.3% |
| SWAP | 6,874,203 | 30.8% |
| COPY | 1,090,210 | 4.9% |
| CALL_BUILTIN_FAST | 522,821 | 2.3% |
| LOAD_ATTR_SLOT | 456,540 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,567,688 | 38.4% |
| COMPARE_OP_INT | 6,209,235 | 27.8% |
| TO_BOOL_BOOL | 1,461,824 | 6.6% |
| COPY | 1,090,210 | 4.9% |
| LOAD_ATTR_WITH_HINT | 1,056,143 | 4.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,475,866 | 47.5% |
| CACHE | 1,033,892 | 33.2% |
| CALL | 333,239 | 10.7% |
| BINARY_SUBSCR_GETITEM | 198,000 | 6.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 64,080 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,900,335 | 93.3% |
| RETURN_GENERATOR | 208,530 | 6.7% |
| MAKE_CELL | 1,320 | 0.0% |
| RESUME | 7 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,857 | 97.0% |
| LOAD_GLOBAL_MODULE | 240 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,558 | 43.9% |
| PUSH_EXC_INFO | 1,800 | 22.2% |
| NOP | 1,599 | 19.7% |
| RETURN_CONST | 1,020 | 12.6% |
| LOAD_GLOBAL_MODULE | 120 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 75,158 | 22.9% |
| STORE_FAST | 73,560 | 22.5% |
| POP_TOP | 66,250 | 20.2% |
| NOP | 37,636 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 37,499 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 102,462 | 31.3% |
| RETURN_VALUE | 75,158 | 22.9% |
| RETURN_CONST | 75,092 | 22.9% |
| LOAD_FAST | 37,504 | 11.4% |
| JUMP_BACKWARD | 36,766 | 11.2% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,438,369 | 93.2% |
| RETURN_VALUE | 325,200 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 66,665 | 1.0% |
| LOAD_DEREF | 37,424 | 0.5% |
| LOAD_GLOBAL_MODULE | 37,419 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 6,906,401 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 37,419 | 96.4% |
| BUILD_MAP | 540 | 1.4% |
| RETURN_VALUE | 480 | 1.2% |
| MAP_ADD | 180 | 0.5% |
| BUILD_CONST_KEY_MAP | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,959 | 97.8% |
| STORE_FAST | 540 | 1.4% |
| LOAD_DEREF | 120 | 0.3% |
| RETURN_VALUE | 60 | 0.2% |
| LOAD_CONST | 60 | 0.2% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,190,672 | 36.0% |
| COMPARE_OP_INT | 5,813,860 | 29.1% |
| STORE_FAST | 4,620,560 | 23.1% |
| COMPARE_OP | 1,147,312 | 5.7% |
| STORE_ATTR_WITH_HINT | 324,000 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,423,994 | 72.2% |
| JUMP_FORWARD | 5,144,680 | 25.8% |
| JUMP_BACKWARD | 316,562 | 1.6% |
| POP_JUMP_IF_NOT_NONE | 66,000 | 0.3% |
| LOAD_ATTR | 4,800 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,064,462 | 53.0% |
| GET_ITER | 4,296,710 | 37.6% |
| SWAP | 904,244 | 7.9% |
| LOAD_FAST | 165,319 | 1.4% |
| FOR_ITER | 6,647 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,843,400 | 33.6% |
| STORE_FAST | 1,855,386 | 16.2% |
| LOAD_FAST | 1,732,788 | 15.2% |
| RETURN_CONST | 1,718,813 | 15.0% |
| SWAP | 837,300 | 7.3% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 256,056 | 58.7% |
| RETURN_VALUE | 148,860 | 34.1% |
| LOAD_FAST | 14,940 | 3.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,040 | 1.8% |
| BEFORE_ASYNC_WITH | 8,040 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 436,356 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 152,231 | 99.6% |
| STORE_FAST | 660 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 152,771 | 99.9% |
| PUSH_EXC_INFO | 120 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 152,411 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 152,231 | 99.9% |
| STORE_FAST | 180 | 0.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,615,944 | 47.7% |
| LOAD_GLOBAL_BUILTIN | 2,069,880 | 27.3% |
| LOAD_GLOBAL_MODULE | 876,155 | 11.6% |
| LOAD_CONST | 346,119 | 4.6% |
| LOAD_FAST | 196,200 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,912,509 | 78.1% |
| POP_JUMP_IF_TRUE | 953,381 | 12.6% |
| COPY | 271,606 | 3.6% |
| RETURN_VALUE | 237,174 | 3.1% |
| EXTENDED_ARG | 198,000 | 2.6% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,447,283 | 44.9% |
| STORE_SUBSCR_DICT | 3,356,840 | 20.3% |
| POP_JUMP_IF_FALSE | 1,193,031 | 7.2% |
| CALL_LIST_APPEND | 1,052,505 | 6.4% |
| POP_JUMP_IF_TRUE | 978,304 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 6,064,462 | 36.6% |
| FOR_ITER_RANGE | 5,528,339 | 33.4% |
| FOR_ITER_LIST | 1,960,711 | 11.8% |
| FOR_ITER_TUPLE | 1,650,228 | 10.0% |
| LOAD_FAST | 927,105 | 5.6% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 487,075 | 100.0% |
| RESUME | 15 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 245,683 | 50.4% |
| SEND_GEN | 241,407 | 49.6% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 5,144,680 | 50.7% |
| POP_JUMP_IF_FALSE | 2,155,084 | 21.3% |
| STORE_FAST | 1,550,936 | 15.3% |
| POP_TOP | 807,822 | 8.0% |
| DELETE_FAST | 102,462 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,844,204 | 47.8% |
| LOAD_FAST | 2,870,855 | 28.3% |
| LOAD_GLOBAL_MODULE | 1,583,661 | 15.6% |
| LOAD_GLOBAL_BUILTIN | 390,615 | 3.9% |
| NOP | 194,160 | 1.9% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 126,007 | 21.7% |
| LOAD_ATTR_SLOT | 126,000 | 21.7% |
| RETURN_VALUE | 103,419 | 17.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 67,200 | 11.6% |
| BINARY_SUBSCR_DICT | 66,120 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 579,646 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,313,045 | 82.7% |
| LOAD_ATTR_SLOT | 1,112,980 | 17.3% |
| BINARY_SLICE | 1,320 | 0.0% |
| LOAD_DEREF | 65 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 6,352,572 | 98.8% |
| STORE_FAST | 74,838 | 1.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,843,938 | 70.5% |
| LOAD_ATTR_SLOT | 1,113,957 | 6.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,095,498 | 6.5% |
| LOAD_GLOBAL_MODULE | 968,581 | 5.8% |
| LOAD_DEREF | 871,454 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,555,347 | 21.2% |
| PUSH_NULL | 3,175,543 | 18.9% |
| LOAD_FAST | 2,917,855 | 17.4% |
| LOAD_FAST_LOAD_FAST | 1,840,477 | 11.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 995,159 | 5.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,430,402 | 34.0% |
| BINARY_OP | 22,348,648 | 10.6% |
| POP_JUMP_IF_FALSE | 17,873,928 | 8.5% |
| STORE_FAST | 14,081,717 | 6.7% |
| LOAD_CONST | 10,768,513 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 62,077,018 | 29.5% |
| LOAD_FAST | 31,022,893 | 14.8% |
| BINARY_OP | 26,322,601 | 12.5% |
| STORE_FAST | 22,207,574 | 10.6% |
| LOAD_CONST | 10,768,513 | 5.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,260,804 | 24.8% |
| RESUME_CHECK | 7,012,448 | 21.0% |
| POP_JUMP_IF_FALSE | 5,220,956 | 15.7% |
| LOAD_CONST | 3,839,798 | 11.5% |
| POP_JUMP_IF_NONE | 1,323,704 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,648,221 | 40.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,349,355 | 37.0% |
| LOAD_FAST | 986,699 | 3.0% |
| LOAD_ATTR | 871,454 | 2.6% |
| CALL_PY_EXACT_ARGS | 819,568 | 2.5% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140,153,123 | 22.3% |
| STORE_FAST | 96,626,631 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 45,777,170 | 7.3% |
| RESUME_CHECK | 45,283,038 | 7.2% |
| PUSH_NULL | 39,280,861 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 110,021,266 | 17.5% |
| LOAD_CONST | 71,430,402 | 11.4% |
| LOAD_GLOBAL_MODULE | 43,014,150 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 38,950,231 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 36,381,982 | 5.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,046,662 | 64.0% |
| LOAD_FAST_AND_CLEAR | 588,000 | 36.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,046,662 | 64.0% |
| LOAD_FAST_AND_CLEAR | 588,000 | 36.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 66,000 | 34.5% |
| POP_JUMP_IF_FALSE | 66,000 | 34.5% |
| LOAD_ATTR_METHOD_NO_DICT | 41,348 | 21.6% |
| POP_TOP | 5,560 | 2.9% |
| LOAD_FAST_CHECK | 5,160 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 132,960 | 69.4% |
| CALL_METHOD_DESCRIPTOR_O | 41,228 | 21.5% |
| LOAD_FAST_CHECK | 5,160 | 2.7% |
| POP_JUMP_IF_NOT_NONE | 4,800 | 2.5% |
| LOAD_CONST | 4,440 | 2.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,398,652 | 16.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,356,635 | 16.7% |
| JUMP_FORWARD | 4,844,204 | 7.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,590,803 | 6.8% |
| NOP | 3,905,874 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,446,793 | 21.3% |
| LOAD_CONST | 10,191,202 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 8,587,475 | 12.7% |
| STORE_ATTR_SLOT | 5,310,663 | 7.8% |
| BINARY_SUBSCR_DICT | 3,737,084 | 5.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,020 | 11.6% |
| STORE_FAST | 1,857 | 10.6% |
| RESUME_CHECK | 1,588 | 9.1% |
| POP_TOP | 1,573 | 9.0% |
| LOAD_GLOBAL_MODULE | 1,540 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,409 | 71.0% |
| LOAD_GLOBAL_BUILTIN | 4,596 | 26.3% |
| LOAD_FAST | 99 | 0.6% |
| LOAD_ATTR | 91 | 0.5% |
| CALL | 55 | 0.3% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 75.0% |
| EXTENDED_ARG | 60 | 15.0% |
| LOAD_DEREF | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 300 | 75.0% |
| LOAD_SUPER_ATTR_ATTR | 100 | 25.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,586,265 | 68.6% |
| MAKE_CELL | 1,843,101 | 19.2% |
| CALL_PY_WITH_DEFAULTS | 585,788 | 6.1% |
| CALL_KW | 351,327 | 3.7% |
| CACHE | 199,680 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,688,883 | 80.0% |
| MAKE_CELL | 1,843,101 | 19.2% |
| RETURN_GENERATOR | 75,923 | 0.8% |
| RESUME | 20 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 258,080 | 39.5% |
| STORE_FAST | 126,120 | 19.3% |
| RETURN_VALUE | 66,180 | 10.1% |
| BINARY_OP | 66,008 | 10.1% |
| CALL_KW | 66,000 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 645,940 | 98.9% |
| LOAD_CONST | 6,840 | 1.0% |
| DICT_UPDATE | 180 | 0.0% |
| BUILD_MAP | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 100,731,796 | 48.2% |
| TO_BOOL_BOOL | 55,315,032 | 26.5% |
| EXTENDED_ARG | 14,423,994 | 6.9% |
| COMPARE_OP | 10,795,514 | 5.2% |
| CONTAINS_OP | 5,962,317 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,153,123 | 67.0% |
| LOAD_CONST | 17,873,928 | 8.5% |
| RETURN_CONST | 15,421,592 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 12,267,068 | 5.9% |
| LOAD_GLOBAL_MODULE | 7,873,614 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,134,265 | 52.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,210,990 | 40.8% |
| LOAD_DEREF | 261,605 | 3.3% |
| LOAD_ATTR_SLOT | 192,000 | 2.4% |
| LOAD_ATTR_WITH_HINT | 73,926 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,079,553 | 51.8% |
| LOAD_DEREF | 1,323,704 | 16.8% |
| BUILD_MAP | 728,700 | 9.3% |
| RETURN_CONST | 546,383 | 6.9% |
| LOAD_GLOBAL_MODULE | 291,105 | 3.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,930,426 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 768,892 | 6.9% |
| LOAD_DEREF | 338,228 | 3.0% |
| LOAD_GLOBAL_MODULE | 68,585 | 0.6% |
| EXTENDED_ARG | 66,000 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,791,894 | 69.6% |
| LOAD_FAST_LOAD_FAST | 1,032,350 | 9.2% |
| LOAD_GLOBAL_MODULE | 967,968 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 507,298 | 4.5% |
| RETURN_CONST | 316,244 | 2.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,546,788 | 37.6% |
| TO_BOOL | 2,157,114 | 17.8% |
| COMPARE_OP_INT | 1,388,505 | 11.5% |
| IS_OP | 953,381 | 7.9% |
| TO_BOOL_INT | 946,973 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,229,653 | 51.5% |
| JUMP_BACKWARD | 978,304 | 8.1% |
| LOAD_CONST | 951,727 | 7.9% |
| LOAD_FAST_LOAD_FAST | 664,498 | 5.5% |
| POP_TOP | 555,948 | 4.6% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,923 | 46.0% |
| CALL_KW | 1,020 | 24.4% |
| LOAD_GLOBAL_MODULE | 723 | 17.3% |
| LOAD_CONST | 300 | 7.2% |
| LOAD_FAST | 217 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,543 | 74.1% |
| COPY | 300 | 14.4% |
| LOAD_CONST | 217 | 10.4% |
| CALL_INTRINSIC_1 | 23 | 1.1% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 134,379 | 49.3% |
| POP_JUMP_IF_TRUE | 133,023 | 48.8% |
| CALL_INTRINSIC_1 | 4,022 | 1.5% |
| POP_JUMP_IF_FALSE | 780 | 0.3% |
| DELETE_FAST | 276 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 134,079 | 98.2% |
| PUSH_EXC_INFO | 1,405 | 1.0% |
| CALL_INTRINSIC_1 | 997 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,421,592 | 47.0% |
| POP_TOP | 8,600,876 | 26.2% |
| STORE_ATTR_SLOT | 1,874,990 | 5.7% |
| FOR_ITER | 1,718,813 | 5.2% |
| STORE_FAST | 1,291,659 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 25,561,645 | 77.9% |
| INTERPRETER_EXIT | 5,036,893 | 15.3% |
| RETURN_VALUE | 1,000,677 | 3.0% |
| TO_BOOL_BOOL | 478,506 | 1.5% |
| EXIT_INIT_CHECK | 219,949 | 0.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 245,683 | 60.9% |
| LOAD_CONST | 157,307 | 39.0% |
| SEND | 744 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 245,893 | 60.9% |
| END_SEND | 156,743 | 38.8% |
| SEND | 744 | 0.2% |
| SEND_GEN | 347 | 0.1% |
| POP_TOP | 7 | 0.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 60,000 | 45.0% |
| RETURN_VALUE | 60,000 | 45.0% |
| RETURN_GENERATOR | 6,000 | 4.5% |
| LOAD_FAST | 6,000 | 4.5% |
| JUMP_FORWARD | 1,320 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 133,320 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,001,551 | 83.8% |
| SET_FUNCTION_ATTRIBUTE | 193,126 | 16.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 447,310 | 37.4% |
| CALL | 234,975 | 19.7% |
| LOAD_FAST | 206,250 | 17.3% |
| SET_FUNCTION_ATTRIBUTE | 193,126 | 16.2% |
| STORE_DEREF | 74,577 | 6.2% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 66,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 66,000 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 533,229 | 70.6% |
| LOAD_GLOBAL_MODULE | 198,900 | 26.3% |
| LOAD_FAST_LOAD_FAST | 10,185 | 1.3% |
| LOAD_DEREF | 7,600 | 1.0% |
| STORE_ATTR | 4,140 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 334,902 | 44.3% |
| LOAD_GLOBAL_MODULE | 134,469 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 132,770 | 17.6% |
| LOAD_CONST | 68,227 | 9.0% |
| LOAD_FAST_LOAD_FAST | 66,498 | 8.8% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 149,856 | 22.5% |
| LOAD_CONST | 104,424 | 15.7% |
| SET_FUNCTION_ATTRIBUTE | 74,577 | 11.2% |
| CALL_BUILTIN_CLASS | 67,140 | 10.1% |
| MAKE_FUNCTION | 66,005 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 207,711 | 31.2% |
| LOAD_CONST | 177,982 | 26.7% |
| LOAD_FAST | 161,350 | 24.2% |
| LOAD_DEREF | 44,414 | 6.7% |
| JUMP_FORWARD | 36,939 | 5.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 22,207,574 | 13.2% |
| RETURN_VALUE | 18,693,282 | 11.1% |
| BINARY_OP_SUBTRACT_INT | 11,714,268 | 7.0% |
| LOAD_GLOBAL_MODULE | 9,974,800 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 9,569,661 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,626,631 | 57.4% |
| LOAD_CONST | 14,081,717 | 8.4% |
| NOP | 11,633,196 | 6.9% |
| LOAD_FAST_LOAD_FAST | 11,398,652 | 6.8% |
| LOAD_DEREF | 8,260,804 | 4.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 559,624 | 74.7% |
| FOR_ITER_TUPLE | 67,200 | 9.0% |
| COPY | 66,123 | 8.8% |
| SWAP | 37,239 | 5.0% |
| FOR_ITER_LIST | 18,780 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 306,000 | 40.9% |
| TO_BOOL_STR | 67,200 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 66,003 | 8.8% |
| STORE_ATTR_SLOT | 66,000 | 8.8% |
| LOAD_GLOBAL_MODULE | 66,000 | 8.8% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 8,075,100 | 57.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 5,952,392 | 42.0% |
| STORE_FAST_STORE_FAST | 67,023 | 0.5% |
| UNPACK_EX | 66,000 | 0.5% |
| UNPACK_SEQUENCE | 7,686 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,073,537 | 57.0% |
| LOAD_FAST | 5,580,512 | 39.4% |
| LOAD_GLOBAL_MODULE | 143,698 | 1.0% |
| NOP | 111,720 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 103,479 | 0.7% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 120 | 40.0% |
| BINARY_OP_ADD_INT | 120 | 40.0% |
| LOAD_FAST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 40.0% |
| LOAD_CONST | 120 | 40.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,567,175 | 40.0% |
| BINARY_OP_ADD_INT | 9,655,914 | 36.5% |
| SWAP | 1,090,210 | 4.1% |
| LOAD_FAST_AND_CLEAR | 1,046,662 | 4.0% |
| FOR_ITER | 837,300 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 8,567,688 | 32.4% |
| COPY | 6,874,203 | 26.0% |
| POP_TOP | 3,558,344 | 13.5% |
| SWAP | 1,090,210 | 4.1% |
| STORE_ATTR_WITH_HINT | 1,056,143 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 66,000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 9,120 | 94.8% |
| RETURN_VALUE | 163 | 1.7% |
| FOR_ITER | 99 | 1.0% |
| UNPACK_SEQUENCE | 80 | 0.8% |
| YIELD_VALUE | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 7,686 | 79.9% |
| STORE_FAST | 1,451 | 15.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 308 | 3.2% |
| UNPACK_SEQUENCE_TUPLE | 80 | 0.8% |
| UNPACK_SEQUENCE | 80 | 0.8% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 301,873 | 26.0% |
| SEND | 245,893 | 21.2% |
| YIELD_VALUE | 241,728 | 20.8% |
| BUILD_TUPLE | 80,760 | 7.0% |
| LOAD_FAST | 75,198 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 846,472 | 73.0% |
| YIELD_VALUE | 241,728 | 20.8% |
| STORE_FAST | 71,880 | 6.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 45 | 26.6% |
| CACHE | 44 | 26.0% |
| MAKE_CELL | 20 | 11.8% |
| POP_TOP | 16 | 9.5% |
| CALL_KW | 16 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83 | 49.1% |
| LOAD_GLOBAL | 42 | 24.9% |
| JUMP_BACKWARD_NO_INTERRUPT | 15 | 8.9% |
| LOAD_CONST | 9 | 5.3% |
| POP_TOP | 6 | 3.6% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 254,280 | 28.2% |
| LOAD_ATTR_INSTANCE_VALUE | 215,078 | 23.9% |
| LOAD_FAST_LOAD_FAST | 204,080 | 22.6% |
| BINARY_OP | 159,731 | 17.7% |
| BINARY_OP_MULTIPLY_FLOAT | 66,060 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 357,491 | 39.7% |
| LOAD_FAST | 289,969 | 32.2% |
| STORE_FAST | 251,769 | 27.9% |
| CALL_ALLOC_AND_ENTER_INIT | 1,500 | 0.2% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,021,639 | 42.1% |
| LOAD_CONST | 7,605,700 | 32.0% |
| CALL_LEN | 4,395,299 | 18.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 932,617 | 3.9% |
| CALL | 520,327 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,655,914 | 40.6% |
| LOAD_FAST | 4,215,920 | 17.7% |
| BINARY_SLICE | 4,131,482 | 17.4% |
| CALL_BUILTIN_FAST | 4,040,040 | 17.0% |
| RETURN_VALUE | 999,788 | 4.2% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 67,200 | 32.6% |
| RETURN_VALUE | 67,180 | 32.6% |
| LOAD_CONST | 66,280 | 32.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,743 | 0.8% |
| LOAD_FAST | 1,440 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 66,000 | 32.0% |
| LIST_APPEND | 66,000 | 32.0% |
| LOAD_FAST | 34,020 | 16.5% |
| CALL | 33,840 | 16.4% |
| CALL_METHOD_DESCRIPTOR_O | 1,743 | 0.8% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 138,180 | 92.8% |
| LOAD_CONST | 7,622 | 5.1% |
| LOAD_FAST_LOAD_FAST | 2,860 | 1.9% |
| BINARY_OP | 180 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 66,060 | 44.4% |
| LOAD_CONST | 65,940 | 44.3% |
| CALL_BUILTIN_O | 7,862 | 5.3% |
| COMPARE_OP_FLOAT | 5,820 | 3.9% |
| STORE_FAST | 2,860 | 1.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 259,618 | 50.4% |
| LOAD_FAST_LOAD_FAST | 131,157 | 25.5% |
| LOAD_CONST | 68,716 | 13.3% |
| BINARY_OP_ADD_INT | 37,419 | 7.3% |
| LOAD_GLOBAL_MODULE | 17,400 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 260,058 | 50.5% |
| BINARY_OP | 131,157 | 25.5% |
| COMPARE_OP_INT | 66,000 | 12.8% |
| STORE_FAST | 49,072 | 9.5% |
| LIST_APPEND | 5,880 | 1.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 331,250 | 53.4% |
| LOAD_FAST | 131,968 | 21.3% |
| CALL | 66,532 | 10.7% |
| RETURN_VALUE | 63,255 | 10.2% |
| LOAD_ATTR_INSTANCE_VALUE | 16,275 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 205,868 | 33.2% |
| LOAD_CONST | 199,863 | 32.2% |
| SWAP | 131,924 | 21.3% |
| CALL | 64,255 | 10.4% |
| LOAD_FAST | 16,701 | 2.7% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,965,369 | 38.2% |
| LOAD_ATTR_INSTANCE_VALUE | 11,608,276 | 37.1% |
| LOAD_CONST | 7,220,470 | 23.1% |
| BINARY_OP_MULTIPLY_INT | 260,058 | 0.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 198,000 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,714,268 | 37.4% |
| LOAD_FAST | 11,613,676 | 37.1% |
| CALL_PY_WITH_DEFAULTS | 5,934,220 | 19.0% |
| SWAP | 801,475 | 2.6% |
| CALL_PY_EXACT_ARGS | 728,700 | 2.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,285,879 | 42.1% |
| LOAD_FAST_LOAD_FAST | 3,737,084 | 36.7% |
| LOAD_CONST | 1,056,826 | 10.4% |
| COPY | 824,350 | 8.1% |
| CALL | 196,627 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,277,880 | 51.9% |
| UNPACK_SEQUENCE_TUPLE | 1,240,598 | 12.2% |
| LOAD_CONST | 1,114,046 | 10.9% |
| RETURN_VALUE | 835,506 | 8.2% |
| LOAD_FAST | 673,073 | 6.6% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 469,198 | 99.9% |
| LOAD_FAST_LOAD_FAST | 540 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 271,698 | 57.8% |
| COPY_FREE_VARS | 198,000 | 42.1% |
| BUILD_TUPLE | 120 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 723,511 | 52.5% |
| LOAD_CONST | 583,699 | 42.4% |
| LOAD_FAST | 48,421 | 3.5% |
| BINARY_OP_SUBTRACT_INT | 19,280 | 1.4% |
| BINARY_SUBSCR_TUPLE_INT | 2,535 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 725,461 | 52.7% |
| STORE_FAST | 239,352 | 17.4% |
| LOAD_ATTR_SLOT | 188,790 | 13.7% |
| TO_BOOL_BOOL | 66,480 | 4.8% |
| LOAD_ATTR_METHOD_NO_DICT | 48,000 | 3.5% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 135,780 | 93.5% |
| LOAD_FAST_LOAD_FAST | 9,000 | 6.2% |
| CALL_BUILTIN_O | 480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 132,180 | 91.0% |
| LOAD_ATTR_METHOD_NO_DICT | 12,600 | 8.7% |
| LIST_APPEND | 480 | 0.3% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,538,622 | 82.4% |
| LOAD_FAST_LOAD_FAST | 326,262 | 17.5% |
| BINARY_SUBSCR_LIST_INT | 2,535 | 0.1% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 599,480 | 32.1% |
| CALL_PY_EXACT_ARGS | 516,000 | 27.6% |
| LOAD_FAST | 207,945 | 11.1% |
| LOAD_ATTR_SLOT | 194,520 | 10.4% |
| CALL_BUILTIN_O | 132,000 | 7.1% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 133,080 | 60.3% |
| LOAD_FAST_LOAD_FAST | 69,519 | 31.5% |
| LOAD_CONST | 6,040 | 2.7% |
| LOAD_FAST | 5,800 | 2.6% |
| BINARY_OP_ADD_FLOAT | 1,500 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 219,049 | 99.2% |
| COPY_FREE_VARS | 1,020 | 0.5% |
| POP_TOP | 720 | 0.3% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,480 | 45.9% |
| LOAD_FAST_LOAD_FAST | 39,039 | 23.1% |
| LOAD_CONST | 15,139 | 9.0% |
| PUSH_NULL | 14,576 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 10,317 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 87,441 | 51.8% |
| COPY_FREE_VARS | 64,080 | 37.9% |
| GET_AWAITABLE | 8,040 | 4.8% |
| POP_TOP | 7,539 | 4.5% |
| MAKE_CELL | 782 | 0.5% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,239,710 | 44.7% |
| LOAD_GLOBAL_BUILTIN | 1,651,431 | 22.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 847,696 | 11.7% |
| LOAD_ATTR_SLOT | 714,160 | 9.9% |
| PUSH_NULL | 328,440 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,130,807 | 29.4% |
| STORE_FAST | 1,610,710 | 22.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,014,498 | 14.0% |
| LOAD_FAST | 909,837 | 12.6% |
| CALL | 780,174 | 10.8% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,040,040 | 54.0% |
| LOAD_FAST | 1,960,626 | 26.2% |
| LOAD_CONST | 850,886 | 11.4% |
| LOAD_FAST_LOAD_FAST | 354,161 | 4.7% |
| LOAD_GLOBAL_MODULE | 132,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 5,902,819 | 78.9% |
| COPY | 522,821 | 7.0% |
| TO_BOOL_BOOL | 429,644 | 5.7% |
| RETURN_VALUE | 203,632 | 2.7% |
| POP_TOP | 186,120 | 2.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,014,498 | 52.8% |
| LOAD_ATTR_INSTANCE_VALUE | 402,707 | 21.0% |
| LOAD_FAST | 138,816 | 7.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 126,100 | 6.6% |
| LOAD_ATTR | 76,729 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 932,617 | 48.6% |
| LOAD_CONST | 464,360 | 24.2% |
| RETURN_VALUE | 216,919 | 11.3% |
| STORE_FAST | 82,907 | 4.3% |
| POP_TOP | 77,629 | 4.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,926,583 | 79.7% |
| LOAD_ATTR_INSTANCE_VALUE | 317,827 | 8.7% |
| BINARY_SUBSCR_TUPLE_INT | 132,000 | 3.6% |
| RETURN_GENERATOR | 75,670 | 2.1% |
| LOAD_ATTR_WITH_HINT | 66,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,657,275 | 72.4% |
| TO_BOOL_BOOL | 512,487 | 14.0% |
| RETURN_VALUE | 333,229 | 9.1% |
| LOAD_FAST | 67,560 | 1.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 66,000 | 1.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,624,435 | 70.7% |
| BUILD_TUPLE | 6,965,748 | 20.0% |
| LOAD_FAST_LOAD_FAST | 1,645,345 | 4.7% |
| LOAD_GLOBAL_MODULE | 1,237,638 | 3.6% |
| LOAD_ATTR | 277,521 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 34,502,722 | 99.0% |
| RETURN_VALUE | 216,600 | 0.6% |
| COPY | 131,231 | 0.4% |
| YIELD_VALUE | 1,560 | 0.0% |
| TO_BOOL | 460 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,658,096 | 50.6% |
| LOAD_ATTR_INSTANCE_VALUE | 12,705,728 | 47.1% |
| LOAD_ATTR_SLOT | 324,380 | 1.2% |
| LOAD_ATTR_WITH_HINT | 273,165 | 1.0% |
| LOAD_DEREF | 3,660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,649,513 | 46.9% |
| STORE_FAST | 6,232,711 | 23.1% |
| BINARY_OP_ADD_INT | 4,395,299 | 16.3% |
| LOAD_CONST | 2,378,192 | 8.8% |
| RETURN_VALUE | 698,035 | 2.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 910,860 | 63.9% |
| LOAD_FAST | 203,364 | 14.3% |
| BUILD_CONST_KEY_MAP | 132,780 | 9.3% |
| BUILD_TUPLE | 73,845 | 5.2% |
| BINARY_OP_ADD_INT | 63,360 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,052,505 | 73.9% |
| LOAD_FAST | 230,501 | 16.2% |
| NOP | 67,083 | 4.7% |
| LOAD_FAST_LOAD_FAST | 66,780 | 4.7% |
| JUMP_FORWARD | 6,120 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,284,588 | 41.0% |
| LOAD_CONST | 2,015,186 | 36.2% |
| BUILD_TUPLE | 396,000 | 7.1% |
| LOAD_GLOBAL_BUILTIN | 326,700 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 145,877 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,493,672 | 80.7% |
| BINARY_OP_SUBTRACT_INT | 198,000 | 3.6% |
| LOAD_FAST | 139,260 | 2.5% |
| POP_TOP | 133,420 | 2.4% |
| CALL_METHOD_DESCRIPTOR_O | 126,000 | 2.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,512,520 | 92.6% |
| LOAD_FAST | 236,499 | 2.9% |
| LOAD_FAST_LOAD_FAST | 178,679 | 2.2% |
| LOAD_ATTR_METHOD_NO_DICT | 114,769 | 1.4% |
| LOAD_ATTR | 38,019 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,764,306 | 95.8% |
| POP_TOP | 274,519 | 3.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 66,000 | 0.8% |
| GET_ITER | 1,320 | 0.0% |
| LOAD_CONST | 900 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,999,664 | 87.1% |
| LOAD_ATTR | 995,159 | 12.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 37,419 | 0.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,484 | 0.0% |
| CALL | 1,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,899,900 | 23.6% |
| STORE_FAST | 1,594,885 | 19.8% |
| POP_TOP | 1,019,896 | 12.7% |
| CALL_BUILTIN_CLASS | 847,696 | 10.5% |
| LOAD_FAST | 815,301 | 10.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,843,133 | 52.4% |
| CALL_BUILTIN_FAST | 5,902,819 | 35.0% |
| BUILD_TUPLE | 1,224,142 | 7.3% |
| LOAD_ATTR_INSTANCE_VALUE | 253,000 | 1.5% |
| LOAD_CONST | 149,139 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,222,894 | 60.6% |
| RETURN_VALUE | 6,487,253 | 38.5% |
| LOAD_CONST | 75,579 | 0.4% |
| STORE_FAST | 40,207 | 0.2% |
| BUILD_LIST | 37,359 | 0.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,228,526 | 34.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,444,196 | 27.8% |
| LOAD_GLOBAL_MODULE | 6,426,043 | 14.4% |
| CALL_TYPE_1 | 3,555,384 | 8.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,528,680 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 36,428,741 | 81.5% |
| MAKE_CELL | 6,586,265 | 14.7% |
| COPY_FREE_VARS | 1,475,866 | 3.3% |
| RETURN_GENERATOR | 150,676 | 0.3% |
| TO_BOOL_BOOL | 64,985 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,694,267 | 34.4% |
| LOAD_CONST | 6,013,626 | 30.9% |
| BINARY_OP_SUBTRACT_INT | 5,934,220 | 30.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 407,902 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 191,880 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,804,680 | 96.6% |
| MAKE_CELL | 585,788 | 3.0% |
| RETURN_GENERATOR | 77,666 | 0.4% |
| COPY_FREE_VARS | 120 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 104,964 | 43.7% |
| CALL_TYPE_1 | 66,000 | 27.5% |
| CALL_TUPLE_1 | 66,000 | 27.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,743 | 0.7% |
| LOAD_FAST | 1,164 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 104,964 | 43.7% |
| LOAD_ATTR_METHOD_NO_DICT | 66,000 | 27.5% |
| CONTAINS_OP | 66,000 | 27.5% |
| STORE_FAST | 2,107 | 0.9% |
| LIST_APPEND | 720 | 0.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 429,459 | 61.8% |
| RETURN_GENERATOR | 132,000 | 19.0% |
| CALL_BUILTIN_CLASS | 66,600 | 9.6% |
| STORE_FAST | 66,000 | 9.5% |
| LOAD_ATTR_MODULE | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 554,259 | 79.8% |
| CALL_STR_1 | 66,000 | 9.5% |
| BINARY_OP | 66,000 | 9.5% |
| LOAD_FAST_LOAD_FAST | 7,200 | 1.0% |
| STORE_FAST | 780 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,993,494 | 98.9% |
| BINARY_SUBSCR_TUPLE_INT | 66,000 | 1.1% |
| LOAD_DEREF | 240 | 0.0% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,555,384 | 58.7% |
| STORE_FAST | 1,567,020 | 25.9% |
| LOAD_GLOBAL_BUILTIN | 342,060 | 5.6% |
| LOAD_GLOBAL_MODULE | 195,791 | 3.2% |
| LOAD_FAST | 134,880 | 2.2% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 511,562 | 34.9% |
| LOAD_CONST | 324,112 | 22.1% |
| LOAD_FAST | 312,722 | 21.4% |
| BINARY_OP | 137,877 | 9.4% |
| COPY | 131,157 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 951,159 | 65.0% |
| RETURN_VALUE | 511,562 | 34.9% |
| POP_JUMP_IF_TRUE | 720 | 0.0% |
| EXTENDED_ARG | 360 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 62,077,018 | 57.5% |
| LOAD_GLOBAL_MODULE | 37,059,974 | 34.3% |
| COPY | 6,209,235 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,357,662 | 1.3% |
| LOAD_ATTR_INSTANCE_VALUE | 514,734 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 100,731,796 | 93.3% |
| EXTENDED_ARG | 5,813,860 | 5.4% |
| POP_JUMP_IF_TRUE | 1,388,505 | 1.3% |
| RETURN_VALUE | 39,342 | 0.0% |
| COMPARE_OP | 2,726 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,363,391 | 74.0% |
| LOAD_FAST | 452,164 | 10.0% |
| LOAD_FAST_LOAD_FAST | 324,040 | 7.1% |
| LOAD_GLOBAL_MODULE | 270,309 | 6.0% |
| LOAD_ATTR_SLOT | 66,000 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,069,115 | 89.6% |
| POP_JUMP_IF_TRUE | 402,180 | 8.9% |
| RETURN_VALUE | 66,000 | 1.5% |
| COPY | 5,229 | 0.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 71,467 | 94.8% |
| GET_ITER | 2,820 | 3.7% |
| SWAP | 919 | 1.2% |
| LOAD_FAST | 120 | 0.2% |
| FOR_ITER | 26 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 71,347 | 94.7% |
| POP_TOP | 3,699 | 4.9% |
| RETURN_CONST | 180 | 0.2% |
| STORE_FAST | 120 | 0.2% |
| RESUME | 6 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,960,711 | 54.0% |
| GET_ITER | 1,625,065 | 44.7% |
| SWAP | 41,179 | 1.1% |
| LOAD_FAST | 2,560 | 0.1% |
| EXTENDED_ARG | 2,340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,740,280 | 47.9% |
| LOAD_FAST | 965,943 | 26.6% |
| RETURN_CONST | 652,942 | 18.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 242,490 | 6.7% |
| STORE_FAST_LOAD_FAST | 18,780 | 0.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,528,339 | 75.8% |
| GET_ITER | 1,764,648 | 24.2% |
| SWAP | 180 | 0.0% |
| LOAD_FAST | 180 | 0.0% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,532,599 | 75.9% |
| LOAD_DEREF | 1,150,959 | 15.8% |
| RETURN_CONST | 422,439 | 5.8% |
| LOAD_CONST | 178,679 | 2.4% |
| LOAD_GLOBAL_BUILTIN | 7,200 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,232,413 | 69.1% |
| JUMP_BACKWARD | 1,650,228 | 26.9% |
| LOAD_FAST | 140,830 | 2.3% |
| SWAP | 100,140 | 1.6% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,138,914 | 83.9% |
| LOAD_FAST | 581,802 | 9.5% |
| RETURN_CONST | 139,288 | 2.3% |
| SWAP | 100,140 | 1.6% |
| STORE_FAST_LOAD_FAST | 67,200 | 1.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 228,914 | 54.4% |
| LOAD_ATTR_MODULE | 187,432 | 44.5% |
| LOAD_FAST | 2,640 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 1,874 | 0.4% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 150,396 | 35.7% |
| COMPARE_OP_INT | 112,497 | 26.7% |
| CALL_PY_EXACT_ARGS | 74,935 | 17.8% |
| LOAD_FAST | 41,419 | 9.8% |
| CALL | 38,199 | 9.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,021,266 | 77.5% |
| LOAD_DEREF | 13,648,221 | 9.6% |
| LOAD_FAST_LOAD_FAST | 8,587,475 | 6.0% |
| COPY | 8,567,688 | 6.0% |
| LOAD_ATTR_SLOT | 990,175 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 19,291,706 | 13.6% |
| LOAD_FAST | 16,659,766 | 11.7% |
| CALL_LEN | 12,705,728 | 8.9% |
| BINARY_OP_SUBTRACT_INT | 11,608,276 | 8.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 10,299,318 | 7.3% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 10,299,318 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,902,819 | 57.3% |
| LOAD_FAST | 4,290,260 | 41.7% |
| LOAD_CONST | 68,820 | 0.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 37,419 | 0.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,580,438 | 58.4% |
| LOAD_ATTR_INSTANCE_VALUE | 6,882,205 | 20.5% |
| LOAD_ATTR_WITH_HINT | 4,352,760 | 13.0% |
| LOAD_ATTR_SLOT | 1,494,160 | 4.5% |
| RETURN_VALUE | 400,320 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,744,765 | 35.1% |
| LOAD_CONST | 9,867,717 | 29.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,999,664 | 20.9% |
| CALL_PY_EXACT_ARGS | 1,528,680 | 4.6% |
| LOAD_FAST_LOAD_FAST | 1,150,061 | 3.4% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,950,231 | 69.2% |
| LOAD_DEREF | 12,349,355 | 21.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,008,673 | 3.6% |
| LOAD_ATTR_SLOT | 1,264,872 | 2.2% |
| LOAD_ATTR_WITH_HINT | 917,980 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,352,612 | 25.5% |
| CALL_PY_EXACT_ARGS | 12,444,196 | 22.1% |
| LOAD_FAST_LOAD_FAST | 11,356,635 | 20.2% |
| LOAD_GLOBAL_MODULE | 6,567,496 | 11.7% |
| LOAD_CONST | 6,477,862 | 11.5% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 14,578,627 | 99.2% |
| LOAD_FAST | 86,398 | 0.6% |
| LOAD_ATTR_MODULE | 28,535 | 0.2% |
| LOAD_ATTR | 5,787 | 0.0% |
| BINARY_SUBSCR_DICT | 1,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 13,601,377 | 92.5% |
| LOAD_ATTR_CLASS | 187,432 | 1.3% |
| LOAD_ATTR | 170,050 | 1.2% |
| BINARY_OP | 143,250 | 1.0% |
| LOAD_FAST | 143,010 | 1.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,060 | 82.3% |
| LOAD_FAST_LOAD_FAST | 660 | 17.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,320 | 35.5% |
| TO_BOOL_BOOL | 900 | 24.2% |
| LOAD_FAST | 660 | 17.7% |
| CALL_BUILTIN_FAST | 660 | 17.7% |
| CALL | 180 | 4.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 188,275 | 61.0% |
| LOAD_FAST | 81,081 | 26.3% |
| LOAD_FAST_LOAD_FAST | 39,222 | 12.7% |
| LOAD_ATTR | 220 | 0.1% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 113,597 | 36.8% |
| COMPARE_OP_INT | 74,958 | 24.3% |
| LOAD_FAST | 38,679 | 12.5% |
| LOAD_CONST | 37,599 | 12.2% |
| STORE_FAST | 37,479 | 12.1% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,820,511 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 133,000 | 6.5% |
| RETURN_VALUE | 75,770 | 3.7% |
| STORE_FAST_LOAD_FAST | 18,000 | 0.9% |
| LOAD_DEREF | 2,439 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,049,637 | 99.9% |
| COPY_FREE_VARS | 1,440 | 0.1% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,773,276 | 93.8% |
| LOAD_FAST_LOAD_FAST | 720,431 | 2.6% |
| STORE_FAST_LOAD_FAST | 306,000 | 1.1% |
| COPY | 269,924 | 1.0% |
| BINARY_SUBSCR_TUPLE_INT | 194,520 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,834,012 | 10.3% |
| TO_BOOL_NONE | 2,718,544 | 9.9% |
| LOAD_CONST | 2,519,288 | 9.2% |
| STORE_FAST | 2,164,395 | 7.9% |
| TO_BOOL_BOOL | 1,973,476 | 7.2% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,460,946 | 81.9% |
| COPY | 1,056,143 | 6.4% |
| LOAD_FAST_LOAD_FAST | 872,410 | 5.3% |
| LOAD_DEREF | 712,140 | 4.3% |
| LOAD_ATTR_INSTANCE_VALUE | 330,440 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,352,760 | 26.5% |
| LOAD_FAST | 3,111,864 | 18.9% |
| TO_BOOL_BOOL | 1,945,740 | 11.8% |
| LOAD_CONST | 1,465,600 | 8.9% |
| RETURN_VALUE | 1,390,874 | 8.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,381,982 | 35.3% |
| RESUME_CHECK | 19,042,145 | 18.5% |
| LOAD_GLOBAL_BUILTIN | 13,354,080 | 12.9% |
| POP_JUMP_IF_FALSE | 12,267,068 | 11.9% |
| STORE_FAST | 7,199,028 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,777,170 | 44.4% |
| CALL_ISINSTANCE | 24,624,435 | 23.9% |
| LOAD_GLOBAL_BUILTIN | 13,354,080 | 12.9% |
| BUILD_TUPLE | 11,860,708 | 11.5% |
| IS_OP | 2,069,880 | 2.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,014,150 | 42.8% |
| RESUME_CHECK | 12,577,897 | 12.5% |
| POP_JUMP_IF_FALSE | 7,873,614 | 7.8% |
| STORE_FAST | 6,929,289 | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,567,496 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 37,059,974 | 36.8% |
| LOAD_ATTR_MODULE | 14,578,627 | 14.5% |
| LOAD_FAST | 14,347,152 | 14.3% |
| STORE_FAST | 9,974,800 | 9.9% |
| CALL_PY_EXACT_ARGS | 6,426,043 | 6.4% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,360 | 91.5% |
| EXTENDED_ARG | 120 | 4.7% |
| LOAD_SUPER_ATTR | 100 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,440 | 55.8% |
| PUSH_NULL | 1,140 | 44.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 507,976 | 99.9% |
| LOAD_SUPER_ATTR | 300 | 0.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 307,359 | 60.5% |
| LOAD_FAST_LOAD_FAST | 161,079 | 31.7% |
| CALL_PY_EXACT_ARGS | 39,301 | 7.7% |
| CALL | 340 | 0.1% |
| LOAD_CONST | 217 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 36,428,741 | 36.4% |
| CALL_PY_WITH_DEFAULTS | 18,804,680 | 18.8% |
| CACHE | 17,222,067 | 17.2% |
| MAKE_CELL | 7,688,883 | 7.7% |
| CALL_KW | 6,005,788 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,283,038 | 45.2% |
| LOAD_GLOBAL_BUILTIN | 19,042,145 | 19.0% |
| LOAD_GLOBAL_MODULE | 12,577,897 | 12.6% |
| LOAD_CONST | 7,563,796 | 7.6% |
| LOAD_DEREF | 7,012,448 | 7.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280,372 | 53.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 241,407 | 46.2% |
| SEND | 347 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 280,592 | 53.7% |
| RESUME_CHECK | 241,343 | 46.2% |
| END_SEND | 120 | 0.0% |
| YIELD_VALUE | 60 | 0.0% |
| RESUME | 11 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,291,604 | 49.3% |
| SWAP | 8,567,688 | 41.0% |
| LOAD_FAST_LOAD_FAST | 1,842,090 | 8.8% |
| LOAD_DEREF | 78,309 | 0.4% |
| BINARY_SUBSCR_DICT | 60,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,450,623 | 59.6% |
| LOAD_FAST_LOAD_FAST | 2,427,902 | 11.6% |
| LOAD_CONST | 2,203,042 | 10.5% |
| RETURN_CONST | 815,666 | 3.9% |
| LOAD_GLOBAL_BUILTIN | 755,268 | 3.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,562,820 | 53.7% |
| LOAD_FAST_LOAD_FAST | 5,310,663 | 43.4% |
| SWAP | 269,924 | 2.2% |
| STORE_FAST_LOAD_FAST | 66,000 | 0.5% |
| STORE_ATTR_SLOT | 15,859 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,884,202 | 31.8% |
| LOAD_FAST_LOAD_FAST | 3,383,253 | 27.7% |
| LOAD_FAST | 2,009,563 | 16.4% |
| RETURN_CONST | 1,874,990 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 529,060 | 4.3% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,056,143 | 99.0% |
| LOAD_FAST_LOAD_FAST | 7,306 | 0.7% |
| LOAD_DEREF | 1,560 | 0.1% |
| LOAD_FAST | 1,320 | 0.1% |
| STORE_ATTR | 677 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740,390 | 69.4% |
| EXTENDED_ARG | 324,000 | 30.4% |
| RETURN_CONST | 900 | 0.1% |
| LOAD_CONST | 556 | 0.1% |
| LOAD_GLOBAL_MODULE | 400 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,189,200 | 52.7% |
| LOAD_FAST | 881,344 | 14.6% |
| SWAP | 824,350 | 13.6% |
| LOAD_CONST | 669,550 | 11.1% |
| LOAD_ATTR_SLOT | 384,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,356,840 | 55.4% |
| LOAD_FAST | 1,408,472 | 23.3% |
| LOAD_FAST_LOAD_FAST | 661,500 | 10.9% |
| RETURN_CONST | 144,631 | 2.4% |
| LOAD_CONST | 133,564 | 2.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 37,939 | 57.7% |
| LOAD_FAST_LOAD_FAST | 21,690 | 33.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000 | 9.1% |
| SWAP | 120 | 0.2% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 43,419 | 66.0% |
| JUMP_BACKWARD | 11,710 | 17.8% |
| LOAD_FAST_LOAD_FAST | 9,980 | 15.2% |
| RETURN_CONST | 600 | 0.9% |
| LOAD_FAST | 60 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 330,700 | 51.6% |
| LOAD_FAST | 277,551 | 43.3% |
| LOAD_ATTR_INSTANCE_VALUE | 23,450 | 3.7% |
| LOAD_ATTR_SLOT | 6,000 | 0.9% |
| CALL | 780 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 367,928 | 57.4% |
| POP_JUMP_IF_TRUE | 272,451 | 42.5% |
| TO_BOOL_NONE | 103 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 34,502,722 | 51.5% |
| LOAD_ATTR_INSTANCE_VALUE | 19,291,706 | 28.8% |
| RETURN_VALUE | 4,286,795 | 6.4% |
| LOAD_ATTR_SLOT | 1,973,476 | 2.9% |
| LOAD_ATTR_WITH_HINT | 1,945,740 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 55,315,032 | 82.5% |
| EXTENDED_ARG | 7,190,672 | 10.7% |
| POP_JUMP_IF_TRUE | 4,546,788 | 6.8% |
| UNARY_NOT | 720 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 517,897 | 30.6% |
| COPY | 503,056 | 29.8% |
| LOAD_FAST | 301,514 | 17.8% |
| RETURN_VALUE | 131,812 | 7.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 123,039 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 946,973 | 56.0% |
| POP_JUMP_IF_FALSE | 743,650 | 44.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 796,207 | 62.3% |
| LOAD_FAST | 337,021 | 26.4% |
| LOAD_ATTR_WITH_HINT | 143,418 | 11.2% |
| LOAD_DEREF | 360 | 0.0% |
| LOAD_FAST_CHECK | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,234,075 | 96.6% |
| POP_JUMP_IF_TRUE | 43,391 | 3.4% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,718,544 | 77.8% |
| LOAD_FAST | 320,799 | 9.2% |
| WITH_EXCEPT_START | 133,003 | 3.8% |
| LOAD_ATTR | 123,971 | 3.5% |
| COPY | 114,116 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,062,317 | 87.7% |
| POP_JUMP_IF_TRUE | 429,657 | 12.3% |
| EXTENDED_ARG | 300 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 115 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 401,662 | 65.7% |
| STORE_FAST_LOAD_FAST | 67,200 | 11.0% |
| LOAD_ATTR | 66,000 | 10.8% |
| LOAD_ATTR_WITH_HINT | 60,780 | 9.9% |
| COPY | 13,780 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 464,525 | 76.0% |
| POP_JUMP_IF_TRUE | 147,000 | 24.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 840 | 93.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 4.4% |
| UNPACK_SEQUENCE | 20 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 900 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,039,422 | 74.1% |
| BINARY_SUBSCR_DICT | 1,240,598 | 15.2% |
| LOAD_FAST | 399,580 | 4.9% |
| CALL_FUNCTION_EX | 324,000 | 4.0% |
| END_SEND | 66,240 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 8,075,100 | 99.0% |
| STORE_FAST | 80,765 | 1.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 3,843,400 | 58.8% |
| RETURN_VALUE | 663,818 | 10.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 642,240 | 9.8% |
| CALL_FUNCTION_EX | 462,000 | 7.1% |
| BINARY_SUBSCR_DICT | 304,259 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 5,952,392 | 91.0% |
| STORE_FAST | 517,512 | 7.9% |
| LOAD_FAST_LOAD_FAST | 66,000 | 1.0% |
| LOAD_FAST | 1,740 | 0.0% |
| STORE_DEREF | 180 | 0.0% |


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

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8220232 | 36.9% |
| specialization.deopt |         5070 | 0.0% |
|          hit |     13766917 | 61.8% |
|         miss |       268728 | 1.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,666 | 64.5% |
| Failure | 3,120 | 35.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 2,000 | 64.1% |
| other | 960 | 30.8% |
| code complex parameters | 80 | 2.6% |
| out of range | 60 | 1.9% |
| list slice | 20 | 0.6% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       398817 | 6.1% |
|          hit |      6121800 | 93.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,140 | 69.6% |
| Failure | 498 | 30.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 260 | 52.2% |
| py simple | 238 | 47.8% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6704699 | 8.2% |
| specialization.deopt |          218 | 0.0% |
|          hit |     74752934 | 91.7% |
|         miss |        12883 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,031 | 41.0% |
| Failure | 5,791 | 59.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 2,175 | 37.6% |
| set | 1,374 | 23.7% |
| tuple | 700 | 12.1% |
| sequence | 580 | 10.0% |
| float | 340 | 5.9% |
| mapping | 320 | 5.5% |
| bytes | 162 | 2.8% |
| other | 100 | 1.7% |
| bytearray | 40 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     29227195 | 33.7% |
| specialization.deopt |           40 | 0.0% |
|          hit |     57493544 | 66.3% |
|         miss |         3536 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 954 | 7.6% |
| Failure | 11,562 | 92.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 7,340 | 63.5% |
| multiply different types | 788 | 6.8% |
| or | 740 | 6.4% |
| true divide different types | 528 | 4.6% |
| remainder | 460 | 4.0% |
| add other | 360 | 3.1% |
| true divide other | 220 | 1.9% |
| add different types | 220 | 1.9% |
| subtract different types | 200 | 1.7% |
| true divide float | 154 | 1.3% |
| lshift | 140 | 1.2% |
| floor divide | 140 | 1.2% |
| rshift | 92 | 0.8% |
| subtract other | 80 | 0.7% |
| power | 60 | 0.5% |
| and other | 40 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21282793 | 9.9% |
| specialization.deopt |         6170 | 0.0% |
|          hit |    193514220 | 89.9% |
|         miss |       344296 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,971 | 42.4% |
| Failure | 25,759 | 57.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 5,568 | 21.6% |
| cfunc noargs | 5,035 | 19.5% |
| class no vectorcall | 3,904 | 15.2% |
| cfunc varargs keywords | 1,800 | 7.0% |
| meth descr varargs keywords | 1,507 | 5.9% |
| meth descr varargs | 1,506 | 5.8% |
| meth descr method fastcall keywords | 1,280 | 5.0% |
| other | 1,135 | 4.4% |
| cfunc varargs | 1,106 | 4.3% |
| no dict | 872 | 3.4% |
| wrong number arguments | 720 | 2.8% |
| class mutable | 530 | 2.1% |
| init not simple | 360 | 1.4% |
| operator wrapper | 296 | 1.1% |
| init not python | 60 | 0.2% |
| cmethod | 60 | 0.2% |
| str | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     11944933 | 9.5% |
| specialization.deopt |         2786 | 0.0% |
|          hit |    113835071 | 90.4% |
|         miss |       148086 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,595 | 31.9% |
| Failure | 7,672 | 68.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 6,107 | 79.6% |
| float long | 438 | 5.7% |
| baseobject | 367 | 4.8% |
| long float | 260 | 3.4% |
| different types | 240 | 3.1% |
| other | 200 | 2.6% |
| tuple | 40 | 0.5% |
| bool | 20 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     11430409 | 40.0% |
|          hit |     17124291 | 60.0% |
|         miss |          300 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 452 | 6.4% |
| Failure | 6,647 | 93.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 2,650 | 39.9% |
| set | 2,335 | 35.1% |
| dict values | 440 | 6.6% |
| dict keys | 320 | 4.8% |
| zip | 300 | 4.5% |
| itertools | 220 | 3.3% |
| other | 160 | 2.4% |
| enumerate | 120 | 1.8% |
| reversed list | 63 | 0.9% |
| bytes | 39 | 0.6% |


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
| specialization.deferred |     16742934 | 5.2% |
| specialization.deopt |        33252 | 0.0% |
|          hit |    301734513 | 94.2% |
|         miss |      1778305 | 0.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 56,012 | 68.8% |
| Failure | 25,445 | 31.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 9,355 | 36.8% |
| has managed dict | 5,727 | 22.5% |
| metaclass attribute | 3,136 | 12.3% |
| not managed dict | 2,481 | 9.8% |
| non object slot | 1,023 | 4.0% |
| module attr not found | 631 | 2.5% |
| shadowed | 555 | 2.2% |
| class attr descriptor | 554 | 2.2% |
| mutable class | 543 | 2.1% |
| overridden | 540 | 2.1% |
| non overriding descriptor | 420 | 1.7% |
| class method obj | 260 | 1.0% |
| builtin class method | 80 | 0.3% |
| class attr simple | 60 | 0.2% |
| not in keys | 60 | 0.2% |
| property | 20 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          484 | 0.0% |
| specialization.deopt |           40 | 0.0% |
|          hit |    203756654 | 100.0% |
|         miss |         1252 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 17,045 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       510936 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 100.0% |
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
| specialization.deferred |       402643 | 43.5% |
|          hit |       521946 | 56.4% |
|         miss |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 347 | 31.8% |
| Failure | 744 | 68.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 704 | 94.6% |
| dict keys | 40 | 5.4% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       743678 | 2.1% |
| specialization.deopt |        15952 | 0.0% |
|          hit |     33327207 | 95.4% |
|         miss |       849470 | 2.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 23,751 | 85.2% |
| Failure | 4,140 | 14.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 2,920 | 70.5% |
| property | 460 | 11.1% |
| overridden | 220 | 5.3% |
| method | 180 | 4.3% |
| class attr simple | 140 | 3.4% |
| overriding descriptor | 80 | 1.9% |
| no dict | 60 | 1.4% |
| not in keys | 40 | 1.0% |
| not managed dict | 40 | 1.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         9137 | 0.1% |
|          hit |     14694649 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 408 | 83.6% |
| Failure | 80 | 16.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 80 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,595,559,975 | 51.5% |
| Not specialized | 372,188,604 | 12.0% |
| Specialized | 1,131,138,236 | 36.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,027,561 | 100.0% |
| BINARY_OP | 29,227,195 | 0.0% |
| CALL | 21,282,793 | 0.0% |
| LOAD_ATTR | 16,742,934 | 0.0% |
| COMPARE_OP | 11,944,933 | 0.0% |
| FOR_ITER | 11,430,409 | 0.0% |
| BINARY_SUBSCR | 8,220,232 | 0.0% |
| TO_BOOL | 6,704,699 | 0.0% |
| STORE_ATTR | 743,678 | 0.0% |
| SEND | 402,643 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,012,011 | 29.6% |
| STORE_ATTR_SLOT | 841,468 | 24.6% |
| LOAD_ATTR_METHOD_NO_DICT | 306,934 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 292,544 | 8.6% |
| COMPARE_OP_INT | 146,626 | 4.3% |
| LOAD_ATTR_WITH_HINT | 142,000 | 4.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 136,361 | 4.0% |
| BINARY_SUBSCR_TUPLE_INT | 134,355 | 3.9% |
| BINARY_SUBSCR_LIST_INT | 134,253 | 3.9% |
| CALL_PY_EXACT_ARGS | 87,581 | 2.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 19,035,396 | 18.9% |
| Calls to Python functions inlined | 81,868,705 | 81.1% |
| Calls via PyEval_EvalFrame (total) | 19,035,396 | 18.9% |
| Calls via PyEval_EvalFrame (vector) | 17,750,128 | 17.6% |
| Calls via PyEval_EvalFrame (generator) | 1,285,268 | 1.3% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 17,750,128 | 17.6% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 2,638,113 | 2.6% |
| Calls via PyEval_EvalFrame (function ex) | 4,548,010 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 3,215,750 | 3.2% |
| Calls via PyEval_EvalFrame (method) | 1,242,477 | 1.2% |
| Frames pushed | 99,241,837 | 98.4% |
| Frame objects created | 1,176,283 | 1.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 98,168,389 | 38.2% |
| Frees to freelist | 98,450,920 |  |
| Allocations | 158,530,741 | 61.8% |
| Allocations to 512 bytes | 157,559,269 | 61.4% |
| Allocations to 4 kbytes | 809,682 | 0.3% |
| Allocations over 4 kbytes | 161,790 | 0.1% |
| Frees | 154,638,475 |  |
| New values | 292,884 |  |
| Interpreter increfs | 1,144,934,782 | 81.1% |
| Interpreter decrefs | 1,308,287,537 | 79.7% |
| Increfs | 266,130,745 | 18.9% |
| Decrefs | 334,112,375 | 20.3% |
| Materialize dict (on request) | 1,743 | 0.6% |
| Materialize dict (new key) | 180 | 0.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 1,743 | 0.6% |
| Method cache hits | 19,350,735 |  |
| Method cache misses | 248,362 |  |
| Method cache collisions | 485,800 |  |
| Method cache dunder hits | 56,360,280 |  |
| Method cache dunder misses | 237,730 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 6,599 | 584,186 | 45,299,346 |
| 1 | 609 | 226,209 | 29,397,412 |
| 2 | 60 | 34,056 | 75,366,986 |


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
