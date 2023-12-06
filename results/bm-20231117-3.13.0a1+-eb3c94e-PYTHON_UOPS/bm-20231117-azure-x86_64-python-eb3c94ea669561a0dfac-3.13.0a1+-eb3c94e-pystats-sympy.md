
# Pystats results

- benchmark: sympy
- fork: python
- ref: eb3c94ea669561a0dfacaca715d4b2723bb2c6f4
- commit hash: eb3c94e
- commit date: 2023-11-17T20:58:13-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 898,940,721 | 16.6% | 16.6% |  |
| STORE_FAST | 295,440,266 | 5.4% | 22.0% |  |
| POP_JUMP_IF_FALSE | 262,204,691 | 4.8% | 26.9% |  |
| RESUME_CHECK | 256,659,949 | 4.7% | 31.6% |  |
| LOAD_FAST_LOAD_FAST | 228,244,875 | 4.2% | 35.8% |  |
| LOAD_GLOBAL_BUILTIN | 225,904,905 | 4.2% | 40.0% | 0.0% |
| LOAD_CONST | 178,848,303 | 3.3% | 43.3% |  |
| RETURN_VALUE | 177,413,015 | 3.3% | 46.5% |  |
| TO_BOOL_BOOL | 169,024,200 | 3.1% | 49.6% | 0.1% |
| INTERPRETER_EXIT | 127,302,752 | 2.3% | 52.0% |  |
| LOAD_GLOBAL_MODULE | 117,809,377 | 2.2% | 54.2% | 0.0% |
| FOR_ITER | 103,717,030 | 1.9% | 56.1% |  |
| STORE_FAST_STORE_FAST | 103,453,717 | 1.9% | 58.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 100,571,174 | 1.9% | 59.8% |  |
| LOAD_ATTR_SLOT | 95,509,226 | 1.8% | 61.6% | 38.2% |
| LOAD_ATTR | 91,995,457 | 1.7% | 63.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 89,536,270 | 1.7% | 64.9% | 10.2% |
| POP_JUMP_IF_TRUE | 74,708,619 | 1.4% | 66.3% |  |
| JUMP_BACKWARD | 67,765,210 | 1.2% | 67.6% |  |
| CALL_PY_EXACT_ARGS | 66,414,085 | 1.2% | 68.8% | 11.8% |
| CALL_ISINSTANCE | 62,539,022 | 1.2% | 69.9% |  |
| LOAD_DEREF | 62,355,630 | 1.1% | 71.1% |  |
| ENTER_EXECUTOR | 61,779,310 | 1.1% | 72.2% |  |
| POP_TOP | 61,534,541 | 1.1% | 73.4% |  |
| GET_ITER | 59,475,684 | 1.1% | 74.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,793,538 | 1.0% | 75.5% | 27.8% |
| RETURN_CONST | 56,489,946 | 1.0% | 76.5% |  |
| BUILD_TUPLE | 50,265,648 | 0.9% | 77.5% |  |
| COMPARE_OP_INT | 48,737,664 | 0.9% | 78.4% | 1.2% |
| IS_OP | 45,377,092 | 0.8% | 79.2% |  |
| SWAP | 45,022,473 | 0.8% | 80.0% |  |
| CALL_BUILTIN_FAST | 43,250,066 | 0.8% | 80.8% |  |
| PUSH_NULL | 42,920,303 | 0.8% | 81.6% |  |
| POP_JUMP_IF_NONE | 40,413,454 | 0.7% | 82.4% |  |
| COMPARE_OP | 37,795,249 | 0.7% | 83.1% |  |
| CALL_BUILTIN_O | 37,679,868 | 0.7% | 83.8% | 7.1% |
| BINARY_OP | 35,212,138 | 0.6% | 84.4% |  |
| COPY_FREE_VARS | 31,770,108 | 0.6% | 85.0% |  |
| NOP | 31,472,903 | 0.6% | 85.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,478,386 | 0.5% | 86.1% | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,406,587 | 0.5% | 86.7% | 0.5% |
| BINARY_SUBSCR_LIST_INT | 29,027,648 | 0.5% | 87.2% | 0.0% |
| CALL_LEN | 28,083,158 | 0.5% | 87.7% |  |
| CALL_FUNCTION_EX | 28,013,584 | 0.5% | 88.2% |  |
| LOAD_ATTR_PROPERTY | 27,995,823 | 0.5% | 88.7% | 14.7% |
| BUILD_MAP | 27,215,277 | 0.5% | 89.2% |  |
| CALL | 26,856,393 | 0.5% | 89.7% |  |
| CALL_LIST_APPEND | 24,015,901 | 0.4% | 90.2% |  |
| YIELD_VALUE | 22,957,995 | 0.4% | 90.6% |  |
| FOR_ITER_LIST | 22,798,876 | 0.4% | 91.0% | 2.0% |
| BINARY_SUBSCR | 22,015,425 | 0.4% | 91.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 21,890,386 | 0.4% | 91.8% | 65.4% |
| BUILD_LIST | 21,580,675 | 0.4% | 92.2% |  |
| FOR_ITER_TUPLE | 20,888,157 | 0.4% | 92.6% | 3.6% |
| STORE_SUBSCR_LIST_INT | 20,195,676 | 0.4% | 93.0% |  |
| TO_BOOL_INT | 19,036,869 | 0.4% | 93.3% | 0.1% |
| CONTAINS_OP | 18,940,990 | 0.3% | 93.7% |  |
| POP_JUMP_IF_NOT_NONE | 18,082,660 | 0.3% | 94.0% |  |
| EXTENDED_ARG | 17,085,140 | 0.3% | 94.3% |  |
| LOAD_FAST_AND_CLEAR | 16,788,273 | 0.3% | 94.7% |  |
| DICT_MERGE | 16,700,496 | 0.3% | 95.0% |  |
| CALL_TYPE_1 | 14,852,066 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 14,523,973 | 0.3% | 95.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,385,220 | 0.3% | 95.8% | 0.3% |
| RETURN_GENERATOR | 14,355,367 | 0.3% | 96.0% |  |
| TO_BOOL | 12,897,255 | 0.2% | 96.3% |  |
| MAKE_FUNCTION | 12,406,800 | 0.2% | 96.5% |  |
| CALL_KW | 10,673,213 | 0.2% | 96.7% |  |
| SET_FUNCTION_ATTRIBUTE | 10,390,768 | 0.2% | 96.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,065,218 | 0.2% | 97.1% | 0.0% |
| STORE_ATTR_SLOT | 9,060,085 | 0.2% | 97.2% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,708 | 0.2% | 97.4% | 0.1% |
| IMPORT_FROM | 8,954,937 | 0.2% | 97.6% |  |
| CALL_BUILTIN_CLASS | 8,538,600 | 0.2% | 97.7% |  |
| MAP_ADD | 7,866,584 | 0.1% | 97.9% |  |
| IMPORT_NAME | 7,759,778 | 0.1% | 98.0% |  |
| STORE_DEREF | 7,702,428 | 0.1% | 98.1% |  |
| MAKE_CELL | 6,049,623 | 0.1% | 98.2% |  |
| CALL_TUPLE_1 | 5,849,014 | 0.1% | 98.4% | 0.0% |
| JUMP_FORWARD | 5,743,757 | 0.1% | 98.5% |  |
| UNARY_NOT | 5,273,970 | 0.1% | 98.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,394 | 0.1% | 98.7% | 0.1% |
| COPY | 4,616,701 | 0.1% | 98.7% |  |
| CALL_PY_WITH_DEFAULTS | 4,590,985 | 0.1% | 98.8% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,590,714 | 0.1% | 98.9% | 0.2% |
| BINARY_OP_ADD_INT | 3,742,632 | 0.1% | 99.0% |  |
| LIST_APPEND | 3,516,769 | 0.1% | 99.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,800 | 0.1% | 99.1% | 0.0% |
| STORE_SUBSCR | 3,330,261 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_DICT | 3,165,193 | 0.1% | 99.2% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,770 | 0.1% | 99.3% | 0.0% |
| TO_BOOL_NONE | 2,653,222 | 0.0% | 99.3% | 8.5% |
| BINARY_OP_SUBTRACT_INT | 2,472,796 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 2,286,279 | 0.0% | 99.4% | 0.5% |
| STORE_SUBSCR_DICT | 2,278,724 | 0.0% | 99.5% |  |
| FOR_ITER_RANGE | 2,225,080 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,810,226 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,157 | 0.0% | 99.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,649,013 | 0.0% | 99.6% | 20.7% |
| UNPACK_SEQUENCE_TUPLE | 1,591,360 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,578,350 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,322 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,282 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,231 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,034 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,740 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,622 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,622 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,622 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,466 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,069 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 551,660 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,646 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,320 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,184 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,591 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,516 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,847 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,587 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,256 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 132,560 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,277 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,116 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 72,820 | 0.0% | 100.0% |  |
| BUILD_SET | 50,502 | 0.0% | 100.0% |  |
| RESUME | 47,564 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,831 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,574 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,012 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,206 | 0.0% | 100.0% |  |
| STORE_SLICE | 940 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 480 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 300 | 0.0% | 100.0% | 20.0% |
| DELETE_NAME | 120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |
| DICT_UPDATE | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 159,711,823 | 2.9% | 2.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 156,086,726 | 2.9% | 5.8% |
| RESUME_CHECK LOAD_FAST | 115,560,570 | 2.1% | 8.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 108,689,177 | 2.0% | 10.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 108,490,484 | 2.0% | 12.0% |
| CACHE RESUME_CHECK | 99,064,670 | 1.8% | 13.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 96,768,590 | 1.8% | 15.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,134,772 | 1.7% | 17.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 76,806,292 | 1.4% | 18.7% |
| RETURN_VALUE INTERPRETER_EXIT | 72,899,094 | 1.3% | 20.1% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 70,909,610 | 1.3% | 21.4% |
| JUMP_BACKWARD FOR_ITER | 67,452,588 | 1.2% | 22.6% |
| LOAD_FAST LOAD_CONST | 60,542,507 | 1.1% | 23.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,534,982 | 1.1% | 24.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 58,156,976 | 1.1% | 25.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,856,159 | 1.1% | 27.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,185,138 | 1.0% | 28.0% |
| LOAD_FAST RETURN_VALUE | 52,826,239 | 1.0% | 28.9% |
| LOAD_FAST LOAD_ATTR | 51,080,408 | 0.9% | 29.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 50,491,756 | 0.9% | 30.8% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 49,510,603 | 0.9% | 31.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 49,498,972 | 0.9% | 32.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,302,879 | 0.8% | 33.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,256,263 | 0.8% | 34.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,968,177 | 0.8% | 34.9% |
| LOAD_CONST LOAD_CONST | 40,204,789 | 0.7% | 35.7% |
| RETURN_VALUE STORE_FAST | 38,555,837 | 0.7% | 36.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 36,027,223 | 0.7% | 37.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,787,288 | 0.7% | 37.7% |
| PUSH_NULL LOAD_FAST | 35,360,945 | 0.7% | 38.4% |
| LOAD_ATTR STORE_FAST | 34,995,774 | 0.6% | 39.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,548,190 | 0.6% | 39.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,433,183 | 0.6% | 40.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,161,681 | 0.6% | 40.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,030,149 | 0.6% | 41.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 32,308,337 | 0.6% | 42.1% |
| RETURN_CONST INTERPRETER_EXIT | 32,283,945 | 0.6% | 42.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 31,153,414 | 0.6% | 43.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,793,617 | 0.6% | 43.8% |
| IS_OP POP_JUMP_IF_FALSE | 29,996,979 | 0.6% | 44.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,320,000 | 0.5% | 44.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,702,301 | 0.5% | 45.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 28,611,510 | 0.5% | 45.9% |
| LOAD_FAST CALL_LEN | 27,053,887 | 0.5% | 46.4% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,389,864 | 0.5% | 46.9% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,302,487 | 0.5% | 47.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,472,447 | 0.5% | 47.8% |
| BINARY_OP STORE_FAST | 24,165,643 | 0.4% | 48.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,046,829 | 0.4% | 48.7% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,718 | 0.4% | 49.1% |
| YIELD_VALUE INTERPRETER_EXIT | 22,111,973 | 0.4% | 49.6% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,038,830 | 0.4% | 50.0% |
| COPY_FREE_VARS RESUME_CHECK | 21,778,216 | 0.4% | 50.4% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,342 | 0.4% | 50.8% |
| RESUME_CHECK NOP | 21,364,840 | 0.4% | 51.2% |
| LOAD_FAST GET_ITER | 21,296,335 | 0.4% | 51.5% |
| BUILD_TUPLE RETURN_VALUE | 21,220,585 | 0.4% | 51.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,760 | 0.4% | 52.3% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 20,941,258 | 0.4% | 52.7% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,905,859 | 0.4% | 53.1% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,791,569 | 0.4% | 53.5% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 20,770,795 | 0.4% | 53.9% |
| LOAD_CONST COMPARE_OP_INT | 20,733,676 | 0.4% | 54.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,354,593 | 0.4% | 54.6% |
| GET_ITER FOR_ITER | 19,834,338 | 0.4% | 55.0% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,574 | 0.4% | 55.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 19,357,932 | 0.4% | 55.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 19,059,262 | 0.4% | 56.1% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,938,809 | 0.3% | 56.4% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,849,418 | 0.3% | 56.7% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,814,204 | 0.3% | 57.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 18,719,958 | 0.3% | 57.4% |
| LOAD_FAST TO_BOOL_INT | 18,160,663 | 0.3% | 57.8% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,000,762 | 0.3% | 58.1% |
| LOAD_FAST PUSH_NULL | 17,304,608 | 0.3% | 58.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,262,353 | 0.3% | 58.7% |
| LOAD_FAST BUILD_TUPLE | 17,075,802 | 0.3% | 59.1% |
| DICT_MERGE CALL_FUNCTION_EX | 16,700,496 | 0.3% | 59.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,637,731 | 0.3% | 59.7% |
| BUILD_MAP LOAD_FAST | 16,611,302 | 0.3% | 60.0% |
| LOAD_FAST DICT_MERGE | 16,571,580 | 0.3% | 60.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,185,313 | 0.3% | 60.6% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 16,117,633 | 0.3% | 60.9% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 16,084,395 | 0.3% | 61.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,026,937 | 0.3% | 61.5% |
| LOAD_ATTR LOAD_FAST | 15,962,169 | 0.3% | 61.8% |
| RESUME_CHECK LOAD_CONST | 15,734,561 | 0.3% | 62.1% |
| LOAD_FAST CALL_BUILTIN_O | 15,707,068 | 0.3% | 62.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,656,587 | 0.3% | 62.6% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 15,653,079 | 0.3% | 62.9% |
| LOAD_FAST CALL_LIST_APPEND | 15,554,289 | 0.3% | 63.2% |
| RETURN_VALUE RETURN_VALUE | 15,183,913 | 0.3% | 63.5% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 15,102,422 | 0.3% | 63.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 15,034,817 | 0.3% | 64.0% |
| RESUME_CHECK POP_TOP | 14,973,179 | 0.3% | 64.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 14,965,838 | 0.3% | 64.6% |
| LOAD_ATTR IS_OP | 14,930,659 | 0.3% | 64.9% |
| LOAD_FAST CALL_TYPE_1 | 14,729,127 | 0.3% | 65.1% |
| POP_TOP JUMP_BACKWARD | 14,684,093 | 0.3% | 65.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 14,480,661 | 0.3% | 65.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,709 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,637 | 56.2% |
| RETURN_VALUE | 93,840 | 16.5% |
| GET_ITER | 54,720 | 9.6% |
| BINARY_OP | 39,120 | 6.9% |
| STORE_FAST | 18,960 | 3.3% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 580 | 61.7% |
| JUMP_BACKWARD | 360 | 38.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,064,670 | 77.7% |
| POP_TOP | 13,906,424 | 10.9% |
| COPY_FREE_VARS | 13,000,378 | 10.2% |
| MAKE_CELL | 1,509,067 | 1.2% |
| RESUME | 18,057 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,560 | 46.9% |
| RETURN_VALUE | 10,660 | 28.5% |
| CALL | 7,360 | 19.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,840 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 35,580 | 95.1% |
| STORE_FAST | 1,840 | 4.9% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,020 | 99.0% |
| BINARY_OP | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,705,349 | 57.7% |
| LOAD_DEREF | 6,405,214 | 29.1% |
| BUILD_TUPLE | 1,767,410 | 8.0% |
| LOAD_FAST | 734,366 | 3.3% |
| RETURN_VALUE | 152,432 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,272,148 | 28.5% |
| LOAD_FAST | 6,168,971 | 28.0% |
| RETURN_VALUE | 6,067,289 | 27.6% |
| CALL | 913,197 | 4.1% |
| GET_ITER | 854,999 | 3.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,654 | 73.6% |
| BUILD_TUPLE | 157,292 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,336 | 8.8% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,462 | 100.0% |
| EXTENDED_ARG | 160 | 0.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,900 | 61.3% |
| LOAD_FAST_LOAD_FAST | 1,200 | 38.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,840 | 59.4% |
| JUMP_BACKWARD | 1,200 | 38.7% |
| LOAD_FAST | 60 | 1.9% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 335,800 | 64.7% |
| SEND | 168,540 | 32.5% |
| SEND_GEN | 15,020 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 519,360 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 95,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 95,600 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 282,560 | 100.0% |
| LOAD_FAST | 20 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 140,760 | 49.8% |
| LOAD_CONST | 108,280 | 38.3% |
| LOAD_FAST | 33,560 | 11.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,296,335 | 35.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,416,789 | 24.2% |
| CALL | 10,953,386 | 18.4% |
| RETURN_VALUE | 4,117,007 | 6.9% |
| CALL_BUILTIN_O | 2,591,144 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,834,338 | 33.3% |
| CALL_PY_EXACT_ARGS | 13,026,234 | 21.9% |
| FOR_ITER_TUPLE | 9,902,786 | 16.7% |
| LOAD_FAST_AND_CLEAR | 9,198,427 | 15.5% |
| FOR_ITER_LIST | 4,368,899 | 7.3% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 346,920 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,320 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,899,094 | 57.3% |
| RETURN_CONST | 32,283,945 | 25.4% |
| YIELD_VALUE | 22,111,973 | 17.4% |
| RETURN_GENERATOR | 7,740 | 0.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 2,220 | 83.5% |
| POP_TOP | 420 | 15.8% |
| STORE_GLOBAL | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,660 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,406,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,389,228 | 83.7% |
| LOAD_GLOBAL_BUILTIN | 793,296 | 6.4% |
| STORE_FAST | 669,667 | 5.4% |
| LOAD_FAST | 458,777 | 3.7% |
| STORE_NAME | 33,580 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,364,840 | 67.9% |
| POP_JUMP_IF_TRUE | 4,183,899 | 13.3% |
| STORE_FAST | 1,973,444 | 6.3% |
| POP_JUMP_IF_FALSE | 1,912,944 | 6.1% |
| POP_TOP | 1,392,180 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,281,290 | 39.0% |
| LOAD_DEREF | 10,424,163 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,570 | 20.3% |
| LOAD_FAST_LOAD_FAST | 899,773 | 2.9% |
| LOAD_CONST | 751,162 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,685 | 45.7% |
| POP_TOP | 358,517 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,685 | 45.7% |
| EXTENDED_ARG | 201,440 | 22.2% |
| ENTER_EXECUTOR | 155,357 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,973,179 | 24.3% |
| CACHE | 13,906,424 | 22.6% |
| RETURN_CONST | 9,346,564 | 15.2% |
| STORE_FAST | 5,839,631 | 9.5% |
| SWAP | 5,778,541 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 14,684,093 | 23.9% |
| RESUME_CHECK | 14,349,806 | 23.3% |
| ENTER_EXECUTOR | 9,223,293 | 15.0% |
| LOAD_FAST | 7,247,637 | 11.8% |
| RETURN_VALUE | 5,302,341 | 8.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,613 | 41.3% |
| BINARY_SUBSCR_DICT | 170,005 | 18.8% |
| RAISE_VARARGS | 115,296 | 12.7% |
| ENTER_EXECUTOR | 102,352 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,366 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,816 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,304,608 | 40.3% |
| LOAD_DEREF | 11,886,504 | 27.7% |
| LOAD_ATTR | 8,385,459 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,620 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,182,034 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,360,945 | 82.4% |
| LOAD_FAST_LOAD_FAST | 5,620,374 | 13.1% |
| LOAD_CONST | 1,723,680 | 4.0% |
| LOAD_DEREF | 127,452 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,911,206 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,340 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,215,891 | 71.2% |
| STORE_FAST | 2,660,460 | 18.5% |
| LOAD_FAST | 791,972 | 5.5% |
| GET_YIELD_FROM_ITER | 346,920 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,826,239 | 29.8% |
| LOAD_ATTR_SLOT | 33,433,183 | 18.8% |
| BUILD_TUPLE | 21,220,585 | 12.0% |
| RETURN_VALUE | 15,183,913 | 8.6% |
| CALL_BUILTIN_O | 11,432,929 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,899,094 | 41.1% |
| STORE_FAST | 38,555,837 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,574 | 11.0% |
| RETURN_VALUE | 15,183,913 | 8.6% |
| LOAD_FAST | 5,453,596 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,241,428 | 97.3% |
| BINARY_SUBSCR | 56,960 | 1.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |
| STORE_SUBSCR | 3,543 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,228,348 | 96.9% |
| ENTER_EXECUTOR | 60,440 | 1.8% |
| JUMP_BACKWARD | 19,700 | 0.6% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,543 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.8% |
| LOAD_FAST | 2,199,125 | 17.1% |
| LOAD_GLOBAL_MODULE | 118,957 | 0.9% |
| LOAD_ATTR | 117,980 | 0.9% |
| RETURN_VALUE | 27,319 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,225,455 | 94.8% |
| POP_JUMP_IF_TRUE | 509,850 | 4.0% |
| UNARY_NOT | 84,132 | 0.7% |
| TO_BOOL_BOOL | 41,195 | 0.3% |
| TO_BOOL | 21,389 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,487 | 22.0% |
| LOAD_FAST | 109,458 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,687 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,984 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,846 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,088 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,732 | 65.3% |
| TO_BOOL_BOOL | 1,085,050 | 20.6% |
| TO_BOOL_LIST | 661,887 | 12.6% |
| TO_BOOL | 84,132 | 1.6% |
| TO_BOOL_INT | 169 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,548 | 66.9% |
| STORE_FAST | 882,771 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,901 | 1.6% |
| LOAD_CONST | 34,370 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,752,776 | 33.4% |
| COMPARE_OP_INT | 6,304,740 | 17.9% |
| COMPARE_OP | 6,162,400 | 17.5% |
| CALL_TUPLE_1 | 4,707,160 | 13.4% |
| LOAD_FAST | 2,606,939 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,165,643 | 68.6% |
| RETURN_VALUE | 5,767,032 | 16.4% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,149 | 3.1% |
| LOAD_FAST | 857,892 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,277 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,497 | 97.8% |
| RETURN_VALUE | 1,840 | 1.4% |
| LOAD_CONST | 500 | 0.4% |
| LOAD_FAST | 400 | 0.3% |
| DICT_UPDATE | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,464,447 | 20.7% |
| POP_JUMP_IF_TRUE | 4,083,246 | 18.9% |
| STORE_FAST | 3,816,531 | 17.7% |
| LOAD_FAST | 2,312,248 | 10.7% |
| FOR_ITER | 1,569,989 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,712,820 | 54.3% |
| SWAP | 4,464,447 | 20.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,407 | 10.6% |
| LOAD_FAST | 1,374,622 | 6.4% |
| BUILD_LIST | 748,358 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,164,023 | 44.7% |
| SWAP | 4,715,980 | 17.3% |
| BUILD_TUPLE | 4,430,349 | 16.3% |
| LOAD_CONST | 1,656,760 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,611,302 | 61.0% |
| SWAP | 4,715,980 | 17.3% |
| STORE_FAST | 3,331,429 | 12.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.7% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,422 | 64.2% |
| SWAP | 18,000 | 35.6% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,422 | 64.2% |
| SWAP | 18,000 | 35.6% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,012 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.7% |
| BINARY_SUBSCR | 172 | 4.3% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 140,760 | 99.9% |
| LOAD_CONST | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 106,160 | 75.3% |
| LOAD_CONST | 16,000 | 11.4% |
| LOAD_FAST | 16,000 | 11.4% |
| LIST_APPEND | 2,460 | 1.7% |
| CALL | 300 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,059,262 | 37.9% |
| LOAD_FAST | 17,075,802 | 34.0% |
| LOAD_ATTR_SLOT | 5,042,112 | 10.0% |
| LOAD_ATTR | 3,033,706 | 6.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,585 | 42.2% |
| LOAD_CONST | 10,408,424 | 20.7% |
| LOAD_GLOBAL_BUILTIN | 4,706,960 | 9.4% |
| BUILD_MAP | 4,430,349 | 8.8% |
| CALL_LIST_APPEND | 3,216,080 | 6.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,633,066 | 35.9% |
| LOAD_FAST | 7,281,557 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,866 | 8.5% |
| ENTER_EXECUTOR | 2,006,300 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,949 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,386 | 40.8% |
| STORE_FAST | 5,844,771 | 21.8% |
| RETURN_VALUE | 4,526,972 | 16.9% |
| POP_TOP | 1,136,078 | 4.2% |
| RESUME_CHECK | 1,069,657 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,700,496 | 59.6% |
| ENTER_EXECUTOR | 6,573,160 | 23.5% |
| LOAD_FAST | 2,317,600 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,910 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,958 | 45.0% |
| RESUME_CHECK | 11,673,675 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,877 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,348,062 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,910 | 93.2% |
| BUILD_MAP | 91,312 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,509,003 | 98.5% |
| ENTER_EXECUTOR | 164,210 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,219 | 88.9% |
| POP_TOP | 698,055 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,817 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,760 | 55.8% |
| LOAD_FAST | 7,564,802 | 20.0% |
| CALL_TYPE_1 | 5,882,514 | 15.6% |
| LOAD_GLOBAL_MODULE | 1,179,516 | 3.1% |
| LOAD_CONST | 947,434 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,357,932 | 51.2% |
| BINARY_OP | 6,162,400 | 16.3% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.3% |
| UNARY_NOT | 3,442,732 | 9.1% |
| POP_JUMP_IF_TRUE | 2,277,951 | 6.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,096,560 | 63.9% |
| LOAD_ATTR | 3,188,664 | 16.8% |
| LOAD_GLOBAL_MODULE | 1,645,894 | 8.7% |
| LOAD_DEREF | 1,479,900 | 7.8% |
| LOAD_CONST | 174,994 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,084,395 | 84.9% |
| POP_JUMP_IF_TRUE | 2,846,435 | 15.0% |
| STORE_FAST | 4,560 | 0.0% |
| EXTENDED_ARG | 4,480 | 0.0% |
| RETURN_VALUE | 960 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 170,080 | 60.2% |
| LOAD_FAST | 110,540 | 39.1% |
| STORE_FAST_LOAD_FAST | 1,560 | 0.6% |
| LOAD_GLOBAL_MODULE | 300 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 282,560 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,237,542 | 26.8% |
| COPY | 1,069,360 | 23.2% |
| LOAD_FAST_LOAD_FAST | 868,240 | 18.8% |
| CALL_ISINSTANCE | 525,020 | 11.4% |
| LOAD_CONST | 236,789 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,338,356 | 29.0% |
| COPY | 1,069,360 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,063,080 | 23.0% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,589 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,000,378 | 40.9% |
| CALL_PY_EXACT_ARGS | 11,829,739 | 37.2% |
| LOAD_ATTR_PROPERTY | 5,065,915 | 15.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,196,748 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,778,216 | 68.5% |
| RETURN_GENERATOR | 9,911,206 | 31.2% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,186 | 0.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 98.7% |
| POP_JUMP_IF_NONE | 15,920 | 1.2% |
| FOR_ITER_LIST | 880 | 0.1% |
| STORE_FAST | 160 | 0.0% |
| POP_TOP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 643,240 | 49.4% |
| BUILD_LIST | 642,560 | 49.3% |
| LOAD_FAST | 16,060 | 1.2% |
| LOAD_GLOBAL | 200 | 0.0% |
| RERAISE | 160 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,571,580 | 99.2% |
| LOAD_DEREF | 128,916 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,700,496 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 15,102,422 | 24.4% |
| POP_JUMP_IF_FALSE | 13,520,057 | 21.9% |
| STORE_SUBSCR_LIST_INT | 9,862,194 | 16.0% |
| POP_TOP | 9,223,293 | 14.9% |
| EXTENDED_ARG | 5,757,909 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 9,604,312 | 15.5% |
| RESUME_CHECK | 9,393,822 | 15.2% |
| FOR_ITER_TUPLE | 9,291,761 | 15.0% |
| CALL_FUNCTION_EX | 6,573,160 | 10.6% |
| POP_JUMP_IF_FALSE | 6,486,130 | 10.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,063,555 | 29.6% |
| CALL_LIST_APPEND | 4,571,186 | 26.8% |
| GET_ITER | 2,378,183 | 13.9% |
| ENTER_EXECUTOR | 1,742,167 | 10.2% |
| COMPARE_OP_INT | 1,719,910 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,647,033 | 38.9% |
| ENTER_EXECUTOR | 5,757,909 | 33.7% |
| FOR_ITER_LIST | 2,686,896 | 15.7% |
| FOR_ITER_TUPLE | 767,880 | 4.5% |
| FOR_ITER_RANGE | 642,400 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 67,452,588 | 65.0% |
| GET_ITER | 19,834,338 | 19.1% |
| LOAD_FAST | 7,641,349 | 7.4% |
| SWAP | 7,638,412 | 7.4% |
| ENTER_EXECUTOR | 1,029,720 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 70,909,610 | 68.4% |
| STORE_FAST | 8,367,146 | 8.1% |
| SWAP | 7,602,720 | 7.3% |
| RETURN_CONST | 4,698,117 | 4.5% |
| LOAD_FAST | 4,694,835 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,258 | 86.6% |
| STORE_FAST | 982,429 | 11.0% |
| STORE_DEREF | 185,710 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,821,842 | 76.2% |
| STORE_DEREF | 2,092,495 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,759,658 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,258 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,930,659 | 32.9% |
| LOAD_FAST | 12,709,520 | 28.0% |
| LOAD_CONST | 10,976,741 | 24.2% |
| LOAD_FAST_LOAD_FAST | 5,893,678 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 539,783 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,996,979 | 66.1% |
| YIELD_VALUE | 12,694,181 | 28.0% |
| POP_JUMP_IF_TRUE | 2,641,746 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 20,905,859 | 30.9% |
| POP_JUMP_IF_TRUE | 16,117,633 | 23.8% |
| POP_TOP | 14,684,093 | 21.7% |
| MAP_ADD | 7,866,244 | 11.6% |
| CALL_LIST_APPEND | 2,240,671 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 67,452,588 | 99.5% |
| FOR_ITER_GEN | 100,673 | 0.1% |
| FOR_ITER_TUPLE | 87,317 | 0.1% |
| FOR_ITER_LIST | 60,176 | 0.1% |
| EXTENDED_ARG | 27,574 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 928,400 | 100.0% |
| RESUME | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 661,220 | 71.2% |
| SEND | 267,340 | 28.8% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,138,013 | 72.0% |
| POP_TOP | 734,256 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,884 | 3.3% |
| LOAD_FAST | 137,397 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,997,132 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,009 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,653 | 5.7% |
| STORE_FAST | 118,997 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,568,846 | 44.6% |
| LOAD_FAST | 1,188,827 | 33.8% |
| RETURN_VALUE | 510,873 | 14.5% |
| LOAD_ATTR_PROPERTY | 64,589 | 1.8% |
| BINARY_SUBSCR | 37,832 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,792,973 | 51.0% |
| JUMP_BACKWARD | 1,718,836 | 48.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,347,182 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,348,062 | 99.9% |
| STORE_DEREF | 880 | 0.1% |
| STORE_NAME | 180 | 0.0% |
| STORE_FAST | 160 | 0.0% |
| EXTENDED_ARG | 40 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,080,408 | 55.5% |
| LOAD_GLOBAL_MODULE | 33,548,190 | 36.5% |
| CALL_TYPE_1 | 2,352,443 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,067 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,905,185 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,995,774 | 38.0% |
| LOAD_FAST | 15,962,169 | 17.4% |
| IS_OP | 14,930,659 | 16.2% |
| PUSH_NULL | 8,385,459 | 9.1% |
| CONTAINS_OP | 3,188,664 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,542,507 | 33.9% |
| LOAD_CONST | 40,204,789 | 22.5% |
| RESUME_CHECK | 15,734,561 | 8.8% |
| BUILD_TUPLE | 10,408,424 | 5.8% |
| RETURN_CONST | 9,526,680 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,204,789 | 22.5% |
| CALL_BUILTIN_FAST | 24,046,829 | 13.4% |
| COMPARE_OP_INT | 20,733,676 | 11.6% |
| STORE_FAST | 14,268,246 | 8.0% |
| MAKE_FUNCTION | 12,406,800 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,770,795 | 33.3% |
| NOP | 10,424,163 | 16.7% |
| LOAD_ATTR_SLOT | 6,405,214 | 10.3% |
| POP_JUMP_IF_FALSE | 4,644,704 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,080 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 20,941,258 | 33.6% |
| PUSH_NULL | 11,886,504 | 19.1% |
| LOAD_FAST | 9,394,913 | 15.1% |
| BINARY_SUBSCR | 6,405,214 | 10.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 5.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,711,823 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 156,086,726 | 17.4% |
| RESUME_CHECK | 115,560,570 | 12.9% |
| POP_JUMP_IF_FALSE | 108,490,484 | 12.1% |
| STORE_FAST_STORE_FAST | 40,968,177 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,134,772 | 10.5% |
| LOAD_ATTR_METHOD_NO_DICT | 76,806,292 | 8.5% |
| LOAD_CONST | 60,542,507 | 6.7% |
| LOAD_GLOBAL_MODULE | 58,156,976 | 6.5% |
| RETURN_VALUE | 52,826,239 | 5.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,427 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,766 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,347 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,766 | 45.2% |
| MAKE_CELL | 160 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,557,060 | 98.7% |
| LOAD_FAST | 9,760 | 0.6% |
| POP_TOP | 7,360 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 2,980 | 0.2% |
| POP_JUMP_IF_FALSE | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 1,556,980 | 98.6% |
| COMPARE_OP_INT | 7,680 | 0.5% |
| POP_JUMP_IF_NOT_NONE | 7,360 | 0.5% |
| LOAD_FAST | 3,860 | 0.2% |
| CALL_BUILTIN_CLASS | 1,360 | 0.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 50,491,756 | 22.1% |
| POP_JUMP_IF_FALSE | 31,153,414 | 13.6% |
| LOAD_GLOBAL_BUILTIN | 28,702,301 | 12.6% |
| RESUME_CHECK | 18,719,958 | 8.2% |
| STORE_FAST_STORE_FAST | 15,653,079 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,389,864 | 11.6% |
| COMPARE_OP | 21,088,760 | 9.2% |
| BUILD_TUPLE | 19,059,262 | 8.4% |
| STORE_SUBSCR_LIST_INT | 18,849,418 | 8.3% |
| CALL_BUILTIN_FAST | 17,262,353 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,263 | 19.4% |
| LOAD_FAST | 34,206 | 18.8% |
| STORE_FAST | 26,933 | 14.8% |
| RESUME_CHECK | 10,936 | 6.0% |
| RESUME | 10,780 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,544 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,265 | 22.7% |
| LOAD_FAST | 39,593 | 21.8% |
| LOAD_ATTR | 14,077 | 7.7% |
| CALL | 9,828 | 5.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 28,280 | 38.8% |
| LOAD_NAME | 8,000 | 11.0% |
| CALL | 7,360 | 10.1% |
| LIST_APPEND | 4,800 | 6.6% |
| POP_TOP | 4,740 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 22,500 | 30.9% |
| LOAD_CONST | 19,560 | 26.9% |
| LOAD_NAME | 8,000 | 11.0% |
| CALL | 5,380 | 7.4% |
| EXTENDED_ARG | 4,340 | 6.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,086 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 501 | 41.5% |
| CALL | 325 | 26.9% |
| LOAD_FAST | 180 | 14.9% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,274,941 | 37.6% |
| CACHE | 1,509,067 | 24.9% |
| CALL_PY_EXACT_ARGS | 770,570 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,377 | 10.8% |
| CALL | 523,724 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,122 | 62.3% |
| MAKE_CELL | 2,274,941 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,424 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,866,244 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 108,689,177 | 41.5% |
| COMPARE_OP_INT | 33,161,681 | 12.6% |
| IS_OP | 29,996,979 | 11.4% |
| COMPARE_OP | 19,357,932 | 7.4% |
| CONTAINS_OP | 16,084,395 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,490,484 | 41.4% |
| LOAD_GLOBAL_BUILTIN | 57,856,159 | 22.1% |
| LOAD_FAST_LOAD_FAST | 31,153,414 | 11.9% |
| RETURN_CONST | 28,611,510 | 10.9% |
| ENTER_EXECUTOR | 13,520,057 | 5.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,030,149 | 81.7% |
| BINARY_SUBSCR | 6,272,148 | 15.5% |
| LOAD_DEREF | 1,088,863 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 5,450 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,905,859 | 51.7% |
| LOAD_FAST_LOAD_FAST | 14,133,964 | 35.0% |
| LOAD_FAST | 2,492,359 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 1,438,219 | 3.6% |
| LOAD_CONST | 1,111,435 | 2.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,637,731 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,074 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,227,278 | 67.6% |
| LOAD_FAST_LOAD_FAST | 1,969,953 | 10.9% |
| LOAD_GLOBAL_MODULE | 1,878,657 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,180 | 7.7% |
| ENTER_EXECUTOR | 441,883 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,185,138 | 72.5% |
| TO_BOOL_INT | 8,685,956 | 11.6% |
| CONTAINS_OP | 2,846,435 | 3.8% |
| IS_OP | 2,641,746 | 3.5% |
| COMPARE_OP | 2,277,951 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,027,223 | 48.2% |
| JUMP_BACKWARD | 16,117,633 | 21.6% |
| LOAD_GLOBAL_BUILTIN | 5,255,167 | 7.0% |
| NOP | 4,183,899 | 5.6% |
| BUILD_LIST | 4,083,246 | 5.5% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,956 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,296 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 28,611,510 | 50.6% |
| RESUME_CHECK | 10,045,496 | 17.8% |
| FOR_ITER_LIST | 5,672,278 | 10.0% |
| FOR_ITER | 4,698,117 | 8.3% |
| STORE_SUBSCR | 3,228,348 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,283,945 | 57.1% |
| LOAD_CONST | 9,526,680 | 16.9% |
| POP_TOP | 9,346,564 | 16.5% |
| TO_BOOL_BOOL | 2,744,537 | 4.9% |
| STORE_FAST | 1,541,240 | 2.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 267,340 | 60.4% |
| LOAD_CONST | 172,420 | 38.9% |
| SEND | 2,500 | 0.6% |
| SEND_GEN | 580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 257,060 | 58.0% |
| END_SEND | 168,540 | 38.1% |
| RESUME_CHECK | 10,200 | 2.3% |
| POP_TOP | 3,920 | 0.9% |
| SEND | 2,500 | 0.6% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,200 | 89.2% |
| RETURN_VALUE | 2,040 | 10.6% |
| BINARY_SUBSCR | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 17,700 | 91.8% |
| ENTER_EXECUTOR | 1,580 | 8.2% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 10,389,228 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,838,206 | 94.7% |
| STORE_FAST | 298,266 | 2.9% |
| STORE_DEREF | 95,650 | 0.9% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,880 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,931 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,906 | 0.7% |
| SWAP | 2,157 | 0.4% |
| LOAD_DEREF | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,715 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,296 | 19.7% |
| LOAD_FAST | 89,983 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.5% |
| IMPORT_FROM | 2,092,495 | 27.2% |
| LOAD_ATTR | 1,558,851 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,650 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.5% |
| POP_TOP | 1,906,785 | 24.8% |
| LOAD_DEREF | 1,298,361 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,710 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,555,837 | 13.1% |
| LOAD_ATTR | 34,995,774 | 11.8% |
| BINARY_OP | 24,165,643 | 8.2% |
| LOAD_ATTR_SLOT | 22,510,718 | 7.6% |
| LOAD_CONST | 14,268,246 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,711,823 | 54.1% |
| LOAD_FAST_LOAD_FAST | 50,491,756 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 32,308,337 | 10.9% |
| LOAD_GLOBAL_MODULE | 11,273,480 | 3.8% |
| STORE_FAST | 9,344,900 | 3.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,361 | 69.6% |
| FOR_ITER_TUPLE | 409,464 | 22.6% |
| FOR_ITER | 92,961 | 5.1% |
| FOR_ITER_RANGE | 47,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,323 | 67.5% |
| LOAD_ATTR_PROPERTY | 201,809 | 11.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,544 | 10.4% |
| LOAD_DEREF | 51,440 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 96,768,590 | 93.5% |
| RETURN_VALUE | 3,248,170 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,396,714 | 1.4% |
| STORE_FAST_STORE_FAST | 771,241 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,968,177 | 39.6% |
| LOAD_GLOBAL_BUILTIN | 22,038,830 | 21.3% |
| LOAD_DEREF | 20,770,795 | 20.1% |
| LOAD_FAST_LOAD_FAST | 15,653,079 | 15.1% |
| LOAD_GLOBAL_MODULE | 1,958,122 | 1.9% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 38,060 | 28.7% |
| MAKE_FUNCTION | 33,580 | 25.3% |
| CALL | 21,600 | 16.3% |
| LOAD_CONST | 9,120 | 6.9% |
| SET_FUNCTION_ATTRIBUTE | 7,660 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,660 | 36.7% |
| LOAD_NAME | 28,280 | 21.3% |
| IMPORT_FROM | 26,000 | 19.6% |
| POP_TOP | 12,080 | 9.1% |
| RETURN_CONST | 4,860 | 3.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 9,396,234 | 20.9% |
| LOAD_FAST_AND_CLEAR | 9,198,347 | 20.4% |
| FOR_ITER | 7,602,720 | 16.9% |
| BUILD_MAP | 4,715,980 | 10.5% |
| LOAD_FAST | 4,641,361 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,396,454 | 20.9% |
| STORE_FAST | 7,931,102 | 17.6% |
| FOR_ITER | 7,638,412 | 17.0% |
| POP_TOP | 5,778,541 | 12.8% |
| BUILD_MAP | 4,715,980 | 10.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,454 | 26.2% |
| FOR_ITER | 6,803 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 3,989 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,673 | 46.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,432 | 23.7% |
| STORE_FAST | 8,189 | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,140 | 2.9% |
| UNPACK_SEQUENCE | 917 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,694,181 | 55.3% |
| ENTER_EXECUTOR | 4,756,014 | 20.7% |
| CALL_ISINSTANCE | 2,335,120 | 10.2% |
| LOAD_FAST | 1,146,712 | 5.0% |
| YIELD_VALUE | 677,400 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,111,973 | 96.3% |
| YIELD_VALUE | 677,400 | 3.0% |
| STORE_FAST | 162,982 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,057 | 38.0% |
| CALL | 11,114 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,098 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,696 | 37.2% |
| LOAD_GLOBAL | 10,780 | 22.7% |
| LOAD_CONST | 8,762 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,361 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,594,409 | 69.3% |
| LOAD_FAST_LOAD_FAST | 573,554 | 15.3% |
| BINARY_SUBSCR_DICT | 420,640 | 11.2% |
| CALL_BUILTIN_CLASS | 81,117 | 2.2% |
| LOAD_FAST | 43,688 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,536,035 | 41.0% |
| SWAP | 942,337 | 25.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,122 | 14.4% |
| LOAD_CONST | 268,940 | 7.2% |
| LOAD_FAST | 201,427 | 5.4% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 479,440 | 86.9% |
| CALL_METHOD_DESCRIPTOR_O | 39,600 | 7.2% |
| LOAD_FAST | 15,880 | 2.9% |
| LOAD_FAST_LOAD_FAST | 8,400 | 1.5% |
| BINARY_SUBSCR_LIST_INT | 3,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 498,440 | 90.4% |
| RETURN_VALUE | 41,840 | 7.6% |
| LOAD_FAST | 6,720 | 1.2% |
| CALL_BUILTIN_FAST | 1,760 | 0.3% |
| CALL | 1,720 | 0.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,677 | 60.5% |
| LOAD_ATTR_SLOT | 723,503 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,749 | 9.8% |
| LOAD_FAST | 94,287 | 3.4% |
| BINARY_OP | 1,447 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,866 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,166 | 6.6% |
| STORE_FAST | 175,524 | 6.4% |
| LOAD_FAST | 76,506 | 2.8% |
| LOAD_GLOBAL_MODULE | 25,169 | 0.9% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 83.3% |
| BINARY_OP | 80 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 280 | 58.3% |
| BINARY_OP | 200 | 41.7% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,556,050 | 62.9% |
| LOAD_FAST_LOAD_FAST | 606,781 | 24.5% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,680 | 5.0% |
| BINARY_OP | 2,187 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,080,100 | 43.7% |
| STORE_FAST | 699,460 | 28.3% |
| BINARY_OP | 311,549 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,954 | 32.7% |
| LOAD_FAST_LOAD_FAST | 923,650 | 29.2% |
| LOAD_CONST | 642,800 | 20.3% |
| CALL_TUPLE_1 | 441,520 | 13.9% |
| RETURN_VALUE | 114,424 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,534 | 27.4% |
| RETURN_VALUE | 809,134 | 25.6% |
| BINARY_OP_ADD_INT | 420,640 | 13.3% |
| PUSH_NULL | 376,980 | 11.9% |
| SWAP | 318,100 | 10.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 59,680 | 37.5% |
| LOAD_FAST_LOAD_FAST | 40,800 | 25.6% |
| ENTER_EXECUTOR | 39,680 | 24.9% |
| LOAD_CONST | 14,556 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,250 | 100.0% |
| RETURN_VALUE | 3 | 0.0% |
| LOAD_CONST | 3 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,389,864 | 90.9% |
| COPY | 1,063,080 | 3.7% |
| LOAD_CONST | 1,026,739 | 3.5% |
| CALL_BUILTIN_CLASS | 282,419 | 1.0% |
| LOAD_FAST | 204,126 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,404,594 | 32.4% |
| SWAP | 9,396,234 | 32.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,556,356 | 26.0% |
| LOAD_CONST | 1,063,540 | 3.7% |
| RETURN_VALUE | 432,315 | 1.5% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,880 | 98.0% |
| LOAD_FAST | 360 | 1.9% |
| BINARY_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,880 | 98.0% |
| LIST_APPEND | 380 | 2.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,719,183 | 97.0% |
| LOAD_FAST | 263,248 | 2.9% |
| BINARY_SUBSCR | 2,737 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,547 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,117 | 3.6% |
| BINARY_OP | 205,240 | 2.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,500 | 80.9% |
| LOAD_FAST_LOAD_FAST | 16,820 | 17.6% |
| LOAD_GLOBAL_MODULE | 1,000 | 1.0% |
| CALL | 240 | 0.3% |
| PUSH_NULL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 95,740 | 100.0% |
| COPY_FREE_VARS | 20 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,129,953 | 91.3% |
| BINARY_OP_ADD_INT | 540,122 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,469 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,525,522 | 87.1% |
| COPY_FREE_VARS | 1,196,748 | 8.3% |
| MAKE_CELL | 654,377 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,395 | 32.8% |
| CALL_BUILTIN_CLASS | 1,959,376 | 22.9% |
| LOAD_CONST | 710,920 | 8.3% |
| CALL_LEN | 611,063 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 568,890 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,980,015 | 34.9% |
| CALL_BUILTIN_CLASS | 1,959,376 | 22.9% |
| GET_ITER | 1,728,472 | 20.2% |
| CALL | 284,276 | 3.3% |
| BINARY_SUBSCR_LIST_INT | 282,419 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,046,829 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,262,353 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,136 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 55,476 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,000,762 | 41.8% |
| STORE_FAST | 10,914,183 | 25.4% |
| TO_BOOL | 10,287,220 | 23.9% |
| PUSH_NULL | 2,128,620 | 4.9% |
| RETURN_VALUE | 1,500,146 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,680 | 94.4% |
| LOAD_FAST | 134,897 | 2.6% |
| BINARY_OP | 119,057 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,706,960 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,797 | 2.5% |
| CALL_BUILTIN_CLASS | 119,057 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,707,068 | 41.7% |
| RETURN_GENERATOR | 10,215,891 | 27.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,614,162 | 14.9% |
| LOAD_ATTR_SLOT | 4,878,528 | 12.9% |
| BINARY_OP | 1,095,149 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,590,753 | 36.1% |
| RETURN_VALUE | 11,432,929 | 30.3% |
| TO_BOOL_BOOL | 9,893,670 | 26.3% |
| GET_ITER | 2,591,144 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,787,288 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 18,938,809 | 30.3% |
| LOAD_DEREF | 3,018,036 | 4.8% |
| LOAD_FAST_LOAD_FAST | 2,763,668 | 4.4% |
| LOAD_FAST | 1,614,872 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,534,982 | 95.2% |
| YIELD_VALUE | 2,335,120 | 3.7% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,548 | 0.2% |
| TO_BOOL | 9,664 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,053,887 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,145 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,260 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,675,958 | 34.5% |
| LOAD_CONST | 7,179,371 | 25.6% |
| CALL_BUILTIN_CLASS | 611,063 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,554,289 | 64.8% |
| BUILD_TUPLE | 3,216,080 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 960,680 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,102,422 | 62.9% |
| EXTENDED_ARG | 4,571,186 | 19.0% |
| JUMP_BACKWARD | 2,240,671 | 9.3% |
| LOAD_FAST | 1,681,758 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,034,817 | 68.7% |
| LOAD_CONST | 2,388,281 | 10.9% |
| BUILD_LIST | 2,294,407 | 10.5% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 270,154 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,740,820 | 58.2% |
| STORE_FAST | 3,415,565 | 15.6% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.2% |
| POP_TOP | 908,855 | 4.2% |
| GET_ITER | 737,607 | 3.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,220 | 46.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,620 | 34.0% |
| LOAD_FAST | 800 | 16.8% |
| CALL | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,860 | 39.1% |
| LOAD_FAST_LOAD_FAST | 940 | 19.7% |
| GET_ITER | 880 | 18.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 680 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 220 | 4.6% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 24,472,447 | 83.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,514 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,785 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,416,789 | 48.9% |
| STORE_FAST | 9,687,018 | 32.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,680 | 16.6% |
| CALL_BUILTIN_CLASS | 169,737 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,785 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.2% |
| LOAD_CONST | 1,226,574 | 26.7% |
| LOAD_FAST | 296,920 | 6.5% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.4% |
| LOAD_CONST | 1,224,574 | 26.7% |
| TO_BOOL_NONE | 48,400 | 1.1% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,791,569 | 31.3% |
| LOAD_FAST | 15,656,587 | 23.6% |
| GET_ITER | 13,026,234 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,339,090 | 18.6% |
| LOAD_SUPER_ATTR_METHOD | 1,539,397 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 49,498,972 | 74.5% |
| COPY_FREE_VARS | 11,829,739 | 17.8% |
| RETURN_GENERATOR | 4,117,340 | 6.2% |
| MAKE_CELL | 770,570 | 1.2% |
| CALL_PY_EXACT_ARGS | 145,211 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,622,037 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,373,943 | 29.9% |
| ENTER_EXECUTOR | 1,014,410 | 22.1% |
| RETURN_VALUE | 192,577 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,794 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,071 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,748 | 1.2% |
| CALL_PY_WITH_DEFAULTS | 220 | 0.0% |
| RESUME | 120 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 145,520 | 62.4% |
| RETURN_VALUE | 73,520 | 31.5% |
| LOAD_FAST | 14,020 | 6.0% |
| CALL | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 219,100 | 93.9% |
| BUILD_TUPLE | 6,860 | 2.9% |
| STORE_FAST | 4,380 | 1.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,840 | 0.8% |
| CALL_BUILTIN_O | 980 | 0.4% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,706,960 | 80.5% |
| LOAD_FAST | 1,015,010 | 17.4% |
| STORE_FAST | 105,772 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,152 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,160 | 80.5% |
| BINARY_SUBSCR_DICT | 441,520 | 7.5% |
| STORE_FAST | 353,212 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,729,127 | 99.2% |
| LOAD_CONST | 120,016 | 0.8% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,082 | 0.0% |
| BINARY_SUBSCR_TUPLE_INT | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,647 | 43.3% |
| COMPARE_OP | 5,882,514 | 39.6% |
| LOAD_ATTR | 2,352,443 | 15.8% |
| IS_OP | 64,276 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,781 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,485 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,046 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,733,676 | 42.5% |
| LOAD_FAST_LOAD_FAST | 16,185,313 | 33.2% |
| CALL_LEN | 10,270,260 | 21.1% |
| LOAD_FAST | 1,013,629 | 2.1% |
| LOAD_ATTR_SLOT | 225,394 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,161,681 | 68.0% |
| BINARY_OP | 6,304,740 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,719,910 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,566,000 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,296,325 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,308 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,661 | 99.7% |
| YIELD_VALUE | 40,232 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,604,312 | 42.1% |
| LOAD_FAST | 4,844,198 | 21.2% |
| GET_ITER | 4,368,899 | 19.2% |
| EXTENDED_ARG | 2,686,896 | 11.8% |
| SWAP | 1,221,484 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,055,009 | 39.7% |
| RETURN_CONST | 5,672,278 | 24.9% |
| LOAD_FAST | 4,094,301 | 18.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,774,019 | 7.8% |
| STORE_FAST_LOAD_FAST | 1,260,361 | 5.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 827,369 | 37.2% |
| GET_ITER | 669,133 | 30.1% |
| EXTENDED_ARG | 642,400 | 28.9% |
| SWAP | 38,880 | 1.7% |
| LOAD_FAST | 29,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,807 | 58.7% |
| RETURN_CONST | 630,283 | 28.3% |
| LOAD_FAST | 195,180 | 8.8% |
| STORE_FAST_LOAD_FAST | 47,440 | 2.1% |
| SWAP | 38,520 | 1.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,902,786 | 47.4% |
| ENTER_EXECUTOR | 9,291,761 | 44.5% |
| EXTENDED_ARG | 767,880 | 3.7% |
| LOAD_FAST | 518,588 | 2.5% |
| SWAP | 299,651 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,208,717 | 48.9% |
| LOAD_FAST | 7,494,918 | 35.9% |
| RETURN_CONST | 788,922 | 3.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 651,325 | 3.1% |
| LOAD_GLOBAL_MODULE | 602,516 | 2.9% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 170,180 | 90.7% |
| LOAD_FAST_LOAD_FAST | 16,900 | 9.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.1% |
| LOAD_ATTR | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 146,960 | 78.3% |
| LOAD_FAST | 34,200 | 18.2% |
| STORE_FAST | 6,320 | 3.4% |
| LOAD_ATTR | 120 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,478,870 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,201 | 11.7% |
| LOAD_DEREF | 1,058,661 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,606 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,514 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,136 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,225,074 | 13.5% |
| STORE_FAST | 1,076,361 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,201 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,806,292 | 85.8% |
| RETURN_VALUE | 4,635,656 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.5% |
| LOAD_GLOBAL_MODULE | 1,964,865 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,514 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,793,617 | 34.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,472,447 | 27.3% |
| CALL_PY_EXACT_ARGS | 20,791,569 | 23.2% |
| LOAD_CONST | 4,050,807 | 4.5% |
| LOAD_DEREF | 3,319,080 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 20,941,258 | 71.2% |
| LOAD_ATTR_SLOT | 4,711,060 | 16.0% |
| LOAD_FAST | 3,531,339 | 12.0% |
| LOAD_ATTR | 147,522 | 0.5% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,965,838 | 50.9% |
| LOAD_FAST_LOAD_FAST | 9,297,097 | 31.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,514 | 16.3% |
| CALL_PY_EXACT_ARGS | 321,188 | 1.1% |
| LOAD_CONST | 6,921 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,649 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,402 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,094 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,618 | 6.3% |
| CALL | 57,379 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,510,603 | 87.2% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| ENTER_EXECUTOR | 2,966,400 | 5.2% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 215,741 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,302,879 | 74.5% |
| CALL_BUILTIN_O | 5,614,162 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,447 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,677 | 2.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 994,543 | 60.3% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.0% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| ENTER_EXECUTOR | 10,874 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.0% |
| TO_BOOL_STR | 478,200 | 29.0% |
| TO_BOOL_BOOL | 411,049 | 24.9% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,302,487 | 90.4% |
| ENTER_EXECUTOR | 1,314,292 | 4.7% |
| RETURN_VALUE | 642,554 | 2.3% |
| STORE_FAST_LOAD_FAST | 201,809 | 0.7% |
| LOAD_DEREF | 190,736 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,814,204 | 67.2% |
| COPY_FREE_VARS | 5,065,915 | 18.1% |
| GET_ITER | 1,920,441 | 6.9% |
| TO_BOOL_BOOL | 712,357 | 2.5% |
| STORE_FAST | 505,897 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,134,772 | 98.6% |
| LOAD_ATTR_SLOT | 613,662 | 0.6% |
| ENTER_EXECUTOR | 555,100 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,060 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,974 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,433,183 | 35.0% |
| STORE_FAST | 22,510,718 | 23.6% |
| LOAD_DEREF | 6,405,214 | 6.7% |
| LOAD_FAST | 5,219,449 | 5.5% |
| LOAD_CONST | 5,210,178 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,856,159 | 25.6% |
| RESUME_CHECK | 41,256,263 | 18.3% |
| STORE_FAST | 32,308,337 | 14.3% |
| STORE_FAST_STORE_FAST | 22,038,830 | 9.8% |
| LOAD_FAST | 20,354,593 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,086,726 | 69.1% |
| LOAD_FAST_LOAD_FAST | 28,702,301 | 12.7% |
| CALL_ISINSTANCE | 18,938,809 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 8,972,793 | 4.0% |
| LOAD_DEREF | 3,220,849 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,156,976 | 49.4% |
| RESUME_CHECK | 16,026,937 | 13.6% |
| STORE_FAST | 11,273,480 | 9.6% |
| POP_JUMP_IF_FALSE | 9,672,970 | 8.2% |
| NOP | 6,377,570 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 35,787,288 | 30.4% |
| LOAD_ATTR | 33,548,190 | 28.5% |
| LOAD_FAST | 29,320,000 | 24.9% |
| LOAD_FAST_LOAD_FAST | 3,279,026 | 2.8% |
| LOAD_DEREF | 3,256,083 | 2.8% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,634 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,182,034 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,656 | 100.0% |
| LOAD_SUPER_ATTR | 501 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,397 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,259 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 361 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,064,670 | 38.6% |
| CALL_PY_EXACT_ARGS | 49,498,972 | 19.3% |
| COPY_FREE_VARS | 21,778,216 | 8.5% |
| LOAD_ATTR_PROPERTY | 18,814,204 | 7.3% |
| POP_TOP | 14,349,806 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,560,570 | 45.0% |
| LOAD_GLOBAL_BUILTIN | 41,256,263 | 16.1% |
| NOP | 21,364,840 | 8.3% |
| LOAD_FAST_LOAD_FAST | 18,719,958 | 7.3% |
| LOAD_GLOBAL_MODULE | 16,026,937 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,900 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,840 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,703 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,137 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,669 | 36.0% |
| RETURN_CONST | 887,352 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,320 | 52.2% |
| LOAD_FAST | 4,284,907 | 47.3% |
| STORE_ATTR_SLOT | 41,758 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,100 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,180 | 24.9% |
| LOAD_CONST | 1,890,725 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,862 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,570,457 | 68.9% |
| LOAD_FAST | 396,984 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,339 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,652,380 | 72.5% |
| EXTENDED_ARG | 226,744 | 10.0% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.0% |
| LOAD_FAST | 164,823 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,958 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,849,418 | 93.3% |
| SWAP | 1,063,080 | 5.3% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,418 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,018,974 | 49.6% |
| ENTER_EXECUTOR | 9,862,194 | 48.8% |
| JUMP_BACKWARD | 250,248 | 1.2% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,545 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| ENTER_EXECUTOR | 480 | 0.2% |
| TO_BOOL | 386 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,406 | 95.1% |
| POP_JUMP_IF_FALSE | 9,713 | 4.2% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 52 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,534,982 | 35.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,302,879 | 25.0% |
| LOAD_FAST | 21,602,342 | 12.8% |
| CALL_BUILTIN_FAST | 18,000,762 | 10.6% |
| CALL_BUILTIN_O | 9,893,670 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 108,689,177 | 64.3% |
| POP_JUMP_IF_TRUE | 54,185,138 | 32.1% |
| EXTENDED_ARG | 5,063,555 | 3.0% |
| UNARY_NOT | 1,085,050 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,160,663 | 95.4% |
| BINARY_OP | 721,854 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 63,238 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,278 | 54.4% |
| POP_JUMP_IF_TRUE | 8,685,956 | 45.6% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 169 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,864 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,128 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,147 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 823,847 | 36.0% |
| POP_JUMP_IF_TRUE | 784,585 | 34.3% |
| UNARY_NOT | 661,887 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,587 | 69.4% |
| RETURN_VALUE | 389,167 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,306 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 48,400 | 1.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,935 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,322 | 73.3% |
| POP_JUMP_IF_TRUE | 689,820 | 26.0% |
| EXTENDED_ARG | 15,420 | 0.6% |
| TO_BOOL_BOOL | 1,680 | 0.1% |
| TO_BOOL | 1,500 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 95.1% |
| LOAD_FAST | 11,300 | 2.2% |
| STORE_FAST_LOAD_FAST | 11,200 | 2.2% |
| COPY | 2,120 | 0.4% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 498,580 | 99.1% |
| POP_JUMP_IF_TRUE | 4,520 | 0.9% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,327 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,647 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 884,647 | 55.6% |
| RETURN_VALUE | 660,913 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,396,714 | 87.8% |
| STORE_FAST | 154,726 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 70,909,610 | 70.5% |
| RETURN_VALUE | 19,465,574 | 19.4% |
| BINARY_SUBSCR_LIST_INT | 7,556,356 | 7.5% |
| FOR_ITER_LIST | 1,774,019 | 1.8% |
| FOR_ITER_TUPLE | 651,325 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 96,768,590 | 96.2% |
| STORE_DEREF | 3,577,880 | 3.6% |
| STORE_FAST | 218,464 | 0.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,680 | 0.0% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 22,574 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,574 | 100.0% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 80 | 66.7% |
| POP_TOP | 20 | 16.7% |
| FOR_ITER | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 80 | 66.7% |
| RETURN_CONST | 20 | 16.7% |
| BUILD_LIST | 20 | 16.7% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,920 | 92.3% |
| DELETE_FAST | 160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 320 | 66.7% |
| COPY | 160 | 33.3% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_BUILD_CLASS | 20 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 280 | 93.3% |
| BINARY_OP | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300 | 100.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,673 | 52.6% |
| GET_ITER | 90,743 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,753 | 52.1% |
| POP_TOP | 90,583 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_CONST_KEY_MAP | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 20 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40 | 66.7% |
| CALL | 20 | 33.3% |


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
|     deferred | 35,154,515 | 78.6% |
|          hit | 9,527,618 | 21.3% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,778 | 11.8% |
| Failure | 50,845 | 88.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,468 | 18.6% |
| multiply different types | 7,303 | 14.4% |
| subtract other | 6,780 | 13.3% |
| and int | 4,125 | 8.1% |
| rshift | 3,810 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,861 | 5.6% |
| true divide different types | 2,523 | 5.0% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,149 | 4.2% |
| add different types | 1,817 | 3.6% |
| floor divide | 1,272 | 2.5% |
| subtract different types | 1,187 | 2.3% |
| xor | 583 | 1.1% |
| and other | 377 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 227 | 0.4% |
| true divide float | 3 | 0.0% |


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
|     deferred | 21,992,443 | 34.7% |
|          hit | 41,342,127 | 65.2% |
|         miss | 14,938 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,717 | 33.6% |
| Failure | 15,265 | 66.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 11,881 | 77.8% |
| out of range | 1,960 | 12.8% |
| buffer int | 1,400 | 9.2% |
| array int | 20 | 0.1% |
| tuple slice | 4 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,134,549 | 6.3% |
|        deopt | 22,840 | 0.0% |
|          hit | 354,687,086 | 85.9% |
|         miss | 31,347,256 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 671,898 | 90.2% |
| Failure | 72,786 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,513 | 39.2% |
| code complex parameters | 14,058 | 19.3% |
| class no vectorcall | 9,220 | 12.7% |
| cfunc varargs keywords | 6,386 | 8.8% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,171 | 3.0% |
| meth descr varargs | 1,918 | 2.6% |
| no dict | 1,120 | 1.5% |
| meth descr varargs keywords | 640 | 0.9% |
| operator wrapper | 380 | 0.5% |
| cfunc varargs | 240 | 0.3% |
| meth descr method fastcall keywords | 180 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 37,705,601 | 37.1% |
|          hit | 63,228,315 | 62.2% |
|         miss | 576,968 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,485 | 22.9% |
| Failure | 69,163 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,456 | 26.7% |
| other | 15,251 | 22.1% |
| different types | 12,253 | 17.7% |
| tuple | 10,056 | 14.5% |
| string | 9,960 | 14.4% |
| bool | 1,987 | 2.9% |
| float long | 340 | 0.5% |
| set | 280 | 0.4% |
| baseobject | 280 | 0.4% |
| list | 220 | 0.3% |
| long float | 80 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 103,575,770 | 69.1% |
|          hit | 44,899,773 | 30.0% |
|         miss | 1,203,856 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 34,585 | 24.5% |
| Failure | 106,675 | 75.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 78,518 | 73.6% |
| set | 9,004 | 8.4% |
| zip | 7,600 | 7.1% |
| enumerate | 4,233 | 4.0% |
| other | 2,720 | 2.5% |
| itertools | 1,940 | 1.8% |
| dict keys | 1,640 | 1.5% |
| reversed list | 860 | 0.8% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 90,521,900 | 22.4% |
|        deopt | 20 | 0.0% |
|          hit | 245,481,556 | 60.9% |
|         miss | 65,932,950 | 16.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,321,745 | 89.7% |
| Failure | 151,832 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,674 | 38.6% |
| metaclass attribute | 53,230 | 35.1% |
| method | 10,406 | 6.9% |
| overridden | 8,673 | 5.7% |
| has managed dict | 8,600 | 5.7% |
| shadowed | 5,300 | 3.5% |
| class method obj | 3,900 | 2.6% |
| builtin class method | 1,320 | 0.9% |
| not managed dict | 749 | 0.5% |
| non object slot | 560 | 0.4% |
| not in keys | 300 | 0.2% |
| non overriding descriptor | 60 | 0.0% |
| module attr not found | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 89,878 | 0.0% |
|          hit | 343,693,822 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,969 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 605 | 0.0% |
|          hit | 2,990,191 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 601 | 100.0% |
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
|     deferred | 439,140 | 29.8% |
|          hit | 999,080 | 67.8% |
|         miss | 30,660 | 2.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 16.8% |
| Failure | 3,080 | 83.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list | 3,080 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 540,742 | 4.2% |
|          hit | 10,198,108 | 78.4% |
|         miss | 2,220,777 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,818 | 92.3% |
| Failure | 3,906 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.2% |
| not managed dict | 1,446 | 37.0% |
| overridden | 240 | 6.1% |
| no dict | 200 | 5.1% |
| not in keys | 60 | 1.5% |


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
|     deferred | 3,323,994 | 12.9% |
|          hit | 22,474,400 | 87.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,724 | 43.5% |
| Failure | 3,543 | 56.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,543 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,814,357 | 6.2% |
|          hit | 193,291,921 | 93.5% |
|         miss | 440,340 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,937 | 72.3% |
| Failure | 22,961 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,785 | 47.0% |
| number | 3,512 | 15.3% |
| mapping | 3,300 | 14.4% |
| dict | 2,260 | 9.8% |
| other | 1,631 | 7.1% |
| set | 1,433 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,662 | 0.0% |
|          hit | 102,341,121 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,392 | 93.6% |
| Failure | 777 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 717 | 92.3% |
| iterator | 60 | 7.7% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,914,541,137 | 53.7% |
| Not specialized | 731,057,871 | 13.5% |
| Specialized hits | 1,677,441,310 | 30.9% |
| Specialized misses | 101,788,325 | 1.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 103,575,770 | 31.2% |
| LOAD_ATTR | 90,521,900 | 27.2% |
| COMPARE_OP | 37,705,601 | 11.3% |
| BINARY_OP | 35,154,515 | 10.6% |
| CALL | 26,134,549 | 7.9% |
| BINARY_SUBSCR | 21,992,443 | 6.6% |
| TO_BOOL | 12,814,357 | 3.9% |
| STORE_SUBSCR | 3,323,994 | 1.0% |
| STORE_ATTR | 540,742 | 0.2% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,447,131 | 35.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,764,162 | 15.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,325,169 | 14.1% |
| LOAD_ATTR_METHOD_NO_DICT | 9,121,791 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,806,309 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,265 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,108,124 | 4.0% |
| CALL_BUILTIN_O | 2,661,193 | 2.6% |
| STORE_ATTR_SLOT | 2,219,797 | 2.2% |
| FOR_ITER_TUPLE | 747,738 | 0.7% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,506,336 | 48.8% |
| Calls to Python functions inlined | 133,984,314 | 51.2% |
| Calls via PyEval_EvalFrame (total) | 127,506,336 | 48.8% |
| Calls via PyEval_EvalFrame (vector) | 98,451,865 | 37.7% |
| Calls via PyEval_EvalFrame (generator) | 29,054,471 | 11.1% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,444,565 | 37.6% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,353 | 9.1% |
| Calls via PyEval_EvalFrame (function ex) | 11,825,167 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 53,324,192 | 20.4% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,214 | 0.5% |
| Frames pushed | 112,559,767 | 43.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,427,153 | 54.3% |
| Frees to freelist | 363,670,060 |  |
| Allocations | 305,643,046 | 45.7% |
| Allocations to 512 bytes | 304,578,708 | 45.5% |
| Allocations to 4 kbytes | 1,039,878 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,318,680 |  |
| New values | 1,057,448 |  |
| Interpreter increfs | 2,630,461,482 | 64.8% |
| Interpreter decrefs | 3,055,149,848 | 65.8% |
| Increfs | 1,429,652,746 | 35.2% |
| Decrefs | 1,585,784,241 | 34.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,876,118 |  |
| Method cache misses | 4,151,537 |  |
| Method cache collisions | 5,659,151 |  |
| Method cache dunder hits | 346,867,753 |  |
| Method cache dunder misses | 1,508,315 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 56,144 |  |
| Traces created | 10,044 | 17.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 198 | 0.4% |
| Trace too long | 0 | 0.0% |
| Trace too short | 46,100 | 82.1% |
| Inner loop found | 80 | 0.1% |
| Recursive call | 160 | 0.3% |
| Traces executed | 61,779,310 |  |
| Uops executed | 1,160,032,338 | 18.78 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,547 | 25.4% |
| <= 32 | 3,757 | 37.4% |
| <= 64 | 2,660 | 26.5% |
| <= 128 | 707 | 7.0% |
| <= 256 | 373 | 3.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,527 | 25.2% |
| <= 16 | 3,286 | 32.7% |
| <= 32 | 2,691 | 26.8% |
| <= 64 | 1,247 | 12.4% |
| <= 128 | 253 | 2.5% |
| <= 256 | 40 | 0.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 2,703,790 | 4.4% |
| <= 2 | 14,740,668 | 23.9% |
| <= 4 | 737,909 | 1.2% |
| <= 8 | 4,466,925 | 7.2% |
| <= 16 | 13,263,641 | 21.5% |
| <= 32 | 20,893,008 | 33.8% |
| <= 64 | 1,707,454 | 2.8% |
| <= 128 | 2,249,518 | 3.6% |
| <= 256 | 965,848 | 1.6% |
| <= 512 | 49,657 | 0.1% |
| <= 1,024 | 372 | 0.0% |
| <= 2,048 | 20 | 0.0% |
| <= 4,096 | 40 | 0.0% |
| <= 8,192 | 360 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 100 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 144,912,518 | 12.5% | 12.5% |  |
| LOAD_FAST | 132,252,115 | 11.4% | 23.9% |  |
| _CHECK_VALIDITY | 121,437,445 | 10.5% | 34.4% |  |
| STORE_FAST | 71,669,883 | 6.2% | 40.5% |  |
| _ITER_CHECK_LIST | 51,526,869 | 4.4% | 45.0% | 3.1% |
| _GUARD_NOT_EXHAUSTED_LIST | 49,927,208 | 4.3% | 49.3% | 19.5% |
| _ITER_NEXT_LIST | 40,175,657 | 3.5% | 52.7% |  |
| _GUARD_GLOBALS_VERSION | 36,394,412 | 3.1% | 55.9% | 1.4% |
| CONTAINS_OP | 33,168,641 | 2.9% | 58.7% |  |
| _GUARD_IS_FALSE_POP | 31,997,585 | 2.8% | 61.5% | 13.1% |
| _LOAD_ATTR | 29,719,357 | 2.6% | 64.1% |  |
| _EXIT_TRACE | 28,318,564 | 2.4% | 66.5% |  |
| _LOAD_GLOBAL_MODULE | 27,935,014 | 2.4% | 68.9% |  |
| _JUMP_TO_TOP | 26,982,522 | 2.3% | 71.2% |  |
| _ITER_CHECK_TUPLE | 23,948,538 | 2.1% | 73.3% | 4.6% |
| _GUARD_NOT_EXHAUSTED_TUPLE | 22,844,409 | 2.0% | 75.3% | 39.0% |
| PUSH_NULL | 17,789,625 | 1.5% | 76.8% |  |
| _ITER_NEXT_TUPLE | 13,938,840 | 1.2% | 78.0% |  |
| LOAD_CONST | 13,322,989 | 1.1% | 79.2% |  |
| _GUARD_IS_TRUE_POP | 11,006,380 | 0.9% | 80.1% | 31.1% |
| _CHECK_FUNCTION_EXACT_ARGS | 10,839,351 | 0.9% | 81.0% | 0.4% |
| _CHECK_PEP_523 | 10,839,351 | 0.9% | 82.0% |  |
| _CHECK_STACK_SPACE | 10,800,501 | 0.9% | 82.9% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 10,797,997 | 0.9% | 83.8% |  |
| _PUSH_FRAME | 10,797,997 | 0.9% | 84.8% |  |
| _SAVE_RETURN_OFFSET | 10,797,997 | 0.9% | 85.7% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,733,586 | 0.9% | 86.6% | 7.7% |
| _ITER_CHECK_RANGE | 10,733,586 | 0.9% | 87.6% |  |
| _ITER_NEXT_RANGE | 9,906,217 | 0.9% | 88.4% |  |
| _GUARD_TYPE_VERSION | 9,289,132 | 0.8% | 89.2% | 32.0% |
| _GUARD_BOTH_INT | 9,261,657 | 0.8% | 90.0% |  |
| _BINARY_OP_ADD_INT | 9,234,597 | 0.8% | 90.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,159,174 | 0.8% | 91.6% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,159,174 | 0.8% | 92.4% |  |
| _GUARD_BUILTINS_VERSION | 7,959,355 | 0.7% | 93.1% |  |
| _LOAD_GLOBAL_BUILTINS | 7,959,355 | 0.7% | 93.8% |  |
| BUILD_TUPLE | 6,728,220 | 0.6% | 94.3% |  |
| BUILD_MAP | 6,581,566 | 0.6% | 94.9% |  |
| DICT_MERGE | 6,572,040 | 0.6% | 95.5% |  |
| LOAD_DEREF | 6,265,463 | 0.5% | 96.0% |  |
| CALL_ISINSTANCE | 4,920,608 | 0.4% | 96.4% |  |
| TO_BOOL_BOOL | 3,704,509 | 0.3% | 96.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,178,265 | 0.3% | 97.0% |  |
| LIST_APPEND | 2,671,889 | 0.2% | 97.3% |  |
| COMPARE_OP_INT | 2,437,726 | 0.2% | 97.5% |  |
| IS_OP | 2,318,030 | 0.2% | 97.7% |  |
| CALL_BUILTIN_O | 2,210,960 | 0.2% | 97.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,147,240 | 0.2% | 98.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,046,167 | 0.2% | 98.2% |  |
| _BINARY_SUBSCR | 1,960,555 | 0.2% | 98.4% |  |
| MAKE_FUNCTION | 1,903,978 | 0.2% | 98.5% |  |
| CALL_TYPE_1 | 1,861,034 | 0.2% | 98.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 1,476,329 | 0.1% | 98.8% |  |
| _GUARD_KEYS_VERSION | 1,476,329 | 0.1% | 99.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,476,329 | 0.1% | 99.1% |  |
| RESUME_CHECK | 1,225,767 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_LIST_INT | 1,189,340 | 0.1% | 99.3% | 1.6% |
| STORE_DEREF | 992,964 | 0.1% | 99.4% |  |
| _GUARD_IS_NOT_NONE_POP | 840,143 | 0.1% | 99.5% | 0.2% |
| _POP_FRAME | 724,468 | 0.1% | 99.5% |  |
| _COMPARE_OP | 698,741 | 0.1% | 99.6% |  |
| TO_BOOL_INT | 656,980 | 0.1% | 99.6% | 0.0% |
| CALL_BUILTIN_CLASS | 610,615 | 0.1% | 99.7% |  |
| GET_ITER | 591,954 | 0.1% | 99.7% |  |
| _LOAD_ATTR_SLOT | 532,978 | 0.0% | 99.8% |  |
| COPY | 291,838 | 0.0% | 99.8% |  |
| SWAP | 290,240 | 0.0% | 99.8% |  |
| CALL_BUILTIN_FAST | 247,162 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 183,676 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 145,040 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,557 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,557 | 0.0% | 99.9% |  |
| _BINARY_OP | 112,389 | 0.0% | 99.9% |  |
| LOAD_NAME | 106,000 | 0.0% | 99.9% |  |
| _STORE_SUBSCR | 98,627 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 80,270 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 70,840 | 0.0% | 99.9% | 2.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 59,500 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 57,040 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 55,600 | 0.0% | 100.0% |  |
| BUILD_LIST | 45,840 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 45,378 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 41,072 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 38,506 | 0.0% | 100.0% |  |
| STORE_NAME | 35,420 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,730 | 0.0% | 100.0% |  |
| _TO_BOOL | 27,846 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 17,631 | 0.0% | 100.0% | 30.0% |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,320 | 0.0% | 100.0% |  |
| CALL_LEN | 15,796 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,680 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 13,380 | 0.0% | 100.0% |  |
| POP_TOP | 11,998 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 11,920 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 11,920 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,500 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 6,000 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 4,680 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,560 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,920 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 1,500 | 0.0% | 100.0% |  |
| STORE_SLICE | 1,220 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,220 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 480 | 0.0% | 100.0% | 100.0% |
| BINARY_SUBSCR_STR_INT | 240 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 160 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 45,420 |
| LOAD_ATTR_PROPERTY | 2,847 |
| YIELD_VALUE | 840 |
| FOR_ITER_GEN | 760 |
| CALL | 697 |
| CALL_PY_WITH_DEFAULTS | 460 |
| CALL_LIST_APPEND | 420 |
| CALL_FUNCTION_EX | 380 |
| CALL_KW | 340 |
| BINARY_SUBSCR_GETITEM | 240 |
| IMPORT_NAME | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 80 |


</details>

---
Stats gathered on: 2023-11-19
