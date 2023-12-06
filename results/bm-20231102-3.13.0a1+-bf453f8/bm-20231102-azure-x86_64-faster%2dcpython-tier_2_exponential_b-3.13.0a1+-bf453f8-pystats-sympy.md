
# Pystats results

- benchmark: sympy
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 911,972,706 | 16.4% | 16.4% |  |
| STORE_FAST | 297,411,982 | 5.4% | 21.8% |  |
| POP_JUMP_IF_FALSE | 275,733,182 | 5.0% | 26.8% |  |
| RESUME_CHECK | 256,592,630 | 4.6% | 31.4% |  |
| LOAD_FAST_LOAD_FAST | 233,586,127 | 4.2% | 35.6% |  |
| LOAD_GLOBAL_BUILTIN | 225,868,285 | 4.1% | 39.7% | 0.0% |
| LOAD_CONST | 178,956,401 | 3.2% | 42.9% |  |
| RETURN_VALUE | 177,415,850 | 3.2% | 46.1% |  |
| TO_BOOL_BOOL | 169,769,644 | 3.1% | 49.2% | 0.1% |
| INTERPRETER_EXIT | 127,383,278 | 2.3% | 51.4% |  |
| LOAD_ATTR | 121,750,979 | 2.2% | 53.6% |  |
| LOAD_GLOBAL_MODULE | 121,552,769 | 2.2% | 55.8% | 0.0% |
| FOR_ITER | 103,928,045 | 1.9% | 57.7% |  |
| STORE_FAST_STORE_FAST | 103,326,754 | 1.9% | 59.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 100,444,484 | 1.8% | 61.4% |  |
| LOAD_ATTR_SLOT | 95,492,492 | 1.7% | 63.1% | 38.2% |
| LOAD_ATTR_METHOD_NO_DICT | 89,611,434 | 1.6% | 64.7% | 10.2% |
| ENTER_EXECUTOR | 84,098,331 | 1.5% | 66.2% |  |
| POP_JUMP_IF_TRUE | 76,196,968 | 1.4% | 67.6% |  |
| JUMP_BACKWARD | 67,664,760 | 1.2% | 68.8% |  |
| CALL_PY_EXACT_ARGS | 66,231,106 | 1.2% | 70.0% | 11.8% |
| CALL_ISINSTANCE | 62,540,293 | 1.1% | 71.1% |  |
| LOAD_DEREF | 62,389,189 | 1.1% | 72.3% |  |
| POP_TOP | 61,491,882 | 1.1% | 73.4% |  |
| GET_ITER | 59,499,369 | 1.1% | 74.4% |  |
| RETURN_CONST | 57,104,194 | 1.0% | 75.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,872,643 | 1.0% | 76.5% | 27.7% |
| BUILD_TUPLE | 56,803,571 | 1.0% | 77.5% |  |
| PUSH_NULL | 49,491,862 | 0.9% | 78.4% |  |
| COMPARE_OP_INT | 48,774,266 | 0.9% | 79.3% | 1.2% |
| IS_OP | 47,772,330 | 0.9% | 80.2% |  |
| SWAP | 45,032,764 | 0.8% | 81.0% |  |
| CALL_BUILTIN_FAST | 43,262,432 | 0.8% | 81.7% |  |
| POP_JUMP_IF_NONE | 40,969,903 | 0.7% | 82.5% |  |
| COMPARE_OP | 38,392,915 | 0.7% | 83.2% |  |
| CONTAINS_OP | 37,833,916 | 0.7% | 83.9% |  |
| CALL_BUILTIN_O | 37,620,190 | 0.7% | 84.5% | 7.1% |
| BINARY_OP | 35,325,298 | 0.6% | 85.2% |  |
| BUILD_MAP | 33,785,736 | 0.6% | 85.8% |  |
| COPY_FREE_VARS | 31,722,216 | 0.6% | 86.4% |  |
| NOP | 31,472,954 | 0.6% | 86.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,518,982 | 0.5% | 87.5% | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,331,825 | 0.5% | 88.0% | 0.5% |
| BINARY_SUBSCR_LIST_INT | 28,975,581 | 0.5% | 88.5% | 0.0% |
| CALL_LEN | 28,097,073 | 0.5% | 89.0% |  |
| CALL_FUNCTION_EX | 28,013,847 | 0.5% | 89.5% |  |
| LOAD_ATTR_PROPERTY | 27,992,169 | 0.5% | 90.0% | 14.7% |
| CALL | 26,831,774 | 0.5% | 90.5% |  |
| CALL_LIST_APPEND | 24,015,463 | 0.4% | 90.9% |  |
| BINARY_SUBSCR | 23,734,664 | 0.4% | 91.4% |  |
| DICT_MERGE | 23,270,710 | 0.4% | 91.8% |  |
| YIELD_VALUE | 23,035,566 | 0.4% | 92.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 21,968,681 | 0.4% | 92.6% | 65.6% |
| BUILD_LIST | 21,580,819 | 0.4% | 93.0% |  |
| STORE_SUBSCR_LIST_INT | 20,200,741 | 0.4% | 93.3% |  |
| TO_BOOL_INT | 19,060,427 | 0.3% | 93.7% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,122,404 | 0.3% | 94.0% |  |
| LOAD_FAST_AND_CLEAR | 16,788,777 | 0.3% | 94.3% |  |
| EXTENDED_ARG | 15,345,860 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,852,566 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,565,086 | 0.3% | 95.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,551,917 | 0.3% | 95.4% | 0.4% |
| RETURN_GENERATOR | 14,298,843 | 0.3% | 95.6% |  |
| FOR_ITER_LIST | 12,952,368 | 0.2% | 95.9% | 1.6% |
| TO_BOOL | 12,925,062 | 0.2% | 96.1% |  |
| MAKE_FUNCTION | 12,351,146 | 0.2% | 96.3% |  |
| FOR_ITER_TUPLE | 11,682,298 | 0.2% | 96.5% | 3.7% |
| CALL_KW | 10,673,490 | 0.2% | 96.7% |  |
| SET_FUNCTION_ATTRIBUTE | 10,334,097 | 0.2% | 96.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,064,696 | 0.2% | 97.1% | 0.0% |
| STORE_ATTR_SLOT | 9,059,818 | 0.2% | 97.3% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,988,134 | 0.2% | 97.4% | 0.1% |
| IMPORT_FROM | 8,955,171 | 0.2% | 97.6% |  |
| CALL_BUILTIN_CLASS | 8,627,996 | 0.2% | 97.7% |  |
| MAP_ADD | 7,867,553 | 0.1% | 97.9% |  |
| IMPORT_NAME | 7,759,916 | 0.1% | 98.0% |  |
| STORE_DEREF | 7,702,728 | 0.1% | 98.1% |  |
| MAKE_CELL | 6,050,124 | 0.1% | 98.3% |  |
| CALL_TUPLE_1 | 5,851,614 | 0.1% | 98.4% | 0.0% |
| JUMP_FORWARD | 5,743,631 | 0.1% | 98.5% |  |
| LIST_APPEND | 5,743,070 | 0.1% | 98.6% |  |
| UNARY_NOT | 5,273,908 | 0.1% | 98.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,637 | 0.1% | 98.8% | 0.1% |
| COPY | 4,626,822 | 0.1% | 98.8% |  |
| CALL_PY_WITH_DEFAULTS | 4,590,920 | 0.1% | 98.9% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,590,742 | 0.1% | 99.0% | 0.2% |
| BINARY_OP_ADD_INT | 3,784,888 | 0.1% | 99.1% |  |
| STORE_SUBSCR | 3,428,696 | 0.1% | 99.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,359,084 | 0.1% | 99.2% | 0.0% |
| BINARY_SUBSCR_DICT | 3,260,780 | 0.1% | 99.3% |  |
| BINARY_OP_MULTIPLY_INT | 2,764,605 | 0.0% | 99.3% | 0.0% |
| TO_BOOL_NONE | 2,653,851 | 0.0% | 99.4% | 8.6% |
| BINARY_OP_SUBTRACT_INT | 2,485,435 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 2,286,264 | 0.0% | 99.4% | 0.5% |
| STORE_SUBSCR_DICT | 2,281,136 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,810,148 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,149 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,645,540 | 0.0% | 99.6% | 20.5% |
| UNPACK_SEQUENCE_TUPLE | 1,591,135 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,578,351 | 0.0% | 99.6% |  |
| FOR_ITER_RANGE | 1,397,727 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,389 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,349 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,089 | 0.0% | 99.8% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,030 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,836 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,688 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,688 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,688 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,496 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,054 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 552,940 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,659 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,416 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,237 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,541 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,369 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,919 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,599 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,268 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 132,560 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,248 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,130 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 72,820 | 0.0% | 100.0% |  |
| BUILD_SET | 50,533 | 0.0% | 100.0% |  |
| RESUME | 47,582 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,889 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,525 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,008 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,204 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 161,628,299 | 2.9% | 2.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 156,045,367 | 2.8% | 5.7% |
| RESUME_CHECK LOAD_FAST | 115,504,552 | 2.1% | 7.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 109,990,243 | 2.0% | 9.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 109,487,273 | 2.0% | 11.8% |
| CACHE RESUME_CHECK | 99,201,292 | 1.8% | 13.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 96,641,879 | 1.7% | 15.3% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,140,541 | 1.7% | 17.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 76,878,513 | 1.4% | 18.4% |
| RETURN_VALUE INTERPRETER_EXIT | 72,901,749 | 1.3% | 19.7% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 71,263,192 | 1.3% | 21.0% |
| JUMP_BACKWARD FOR_ITER | 67,365,159 | 1.2% | 22.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 61,808,349 | 1.1% | 23.3% |
| LOAD_FAST LOAD_CONST | 60,611,809 | 1.1% | 24.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,536,164 | 1.1% | 25.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,705,279 | 1.0% | 26.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,130,109 | 1.0% | 27.5% |
| LOAD_FAST RETURN_VALUE | 52,829,727 | 1.0% | 28.4% |
| LOAD_FAST LOAD_ATTR | 51,088,235 | 0.9% | 29.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 50,454,381 | 0.9% | 30.3% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 49,590,357 | 0.9% | 31.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 49,357,484 | 0.9% | 32.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,384,988 | 0.8% | 32.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,266,896 | 0.7% | 33.6% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,964,563 | 0.7% | 34.3% |
| LOAD_CONST LOAD_CONST | 40,214,741 | 0.7% | 35.0% |
| RETURN_VALUE STORE_FAST | 38,555,144 | 0.7% | 35.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 37,802,495 | 0.7% | 36.4% |
| LOAD_ATTR STORE_FAST | 36,820,261 | 0.7% | 37.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,788,383 | 0.6% | 37.7% |
| PUSH_NULL LOAD_FAST | 35,366,301 | 0.6% | 38.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 34,608,467 | 0.6% | 39.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,554,888 | 0.6% | 39.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,433,259 | 0.6% | 40.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,197,318 | 0.6% | 40.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,034,712 | 0.6% | 41.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 32,309,871 | 0.6% | 41.9% |
| RETURN_CONST INTERPRETER_EXIT | 32,284,243 | 0.6% | 42.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,794,203 | 0.6% | 43.1% |
| IS_OP POP_JUMP_IF_FALSE | 30,050,158 | 0.5% | 43.6% |
| ENTER_EXECUTOR LOAD_ATTR | 29,616,652 | 0.5% | 44.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,410,786 | 0.5% | 44.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 29,163,444 | 0.5% | 45.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,705,734 | 0.5% | 45.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,643,333 | 0.5% | 46.2% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 27,670,696 | 0.5% | 46.7% |
| LOAD_FAST CALL_LEN | 27,055,715 | 0.5% | 47.2% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,333,234 | 0.5% | 47.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 25,623,971 | 0.5% | 48.2% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,301,007 | 0.5% | 48.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,512,802 | 0.4% | 49.1% |
| BINARY_OP STORE_FAST | 24,216,501 | 0.4% | 49.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,056,487 | 0.4% | 49.9% |
| DICT_MERGE CALL_FUNCTION_EX | 23,270,710 | 0.4% | 50.4% |
| BUILD_MAP LOAD_FAST | 23,181,504 | 0.4% | 50.8% |
| LOAD_FAST DICT_MERGE | 23,141,782 | 0.4% | 51.2% |
| LOAD_ATTR_SLOT STORE_FAST | 22,508,559 | 0.4% | 51.6% |
| YIELD_VALUE INTERPRETER_EXIT | 22,189,546 | 0.4% | 52.0% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 21,982,364 | 0.4% | 52.4% |
| COPY_FREE_VARS RESUME_CHECK | 21,787,127 | 0.4% | 52.8% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,266 | 0.4% | 53.2% |
| RESUME_CHECK NOP | 21,364,910 | 0.4% | 53.6% |
| LOAD_FAST GET_ITER | 21,239,441 | 0.4% | 53.9% |
| BUILD_TUPLE RETURN_VALUE | 21,221,383 | 0.4% | 54.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,885 | 0.4% | 54.7% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,900,486 | 0.4% | 55.1% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 20,874,450 | 0.4% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,801,874 | 0.4% | 55.8% |
| LOAD_CONST COMPARE_OP_INT | 20,756,904 | 0.4% | 56.2% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 20,703,986 | 0.4% | 56.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,354,441 | 0.4% | 56.9% |
| LOAD_ATTR CONTAINS_OP | 20,047,912 | 0.4% | 57.3% |
| GET_ITER FOR_ITER | 19,981,789 | 0.4% | 57.7% |
| COMPARE_OP POP_JUMP_IF_FALSE | 19,954,258 | 0.4% | 58.0% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,466,550 | 0.4% | 58.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,938,673 | 0.3% | 58.7% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,849,837 | 0.3% | 59.1% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,813,169 | 0.3% | 59.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 18,562,417 | 0.3% | 59.7% |
| LOAD_FAST TO_BOOL_INT | 18,173,654 | 0.3% | 60.1% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,002,162 | 0.3% | 60.4% |
| LOAD_FAST PUSH_NULL | 17,303,160 | 0.3% | 60.7% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,264,740 | 0.3% | 61.0% |
| LOAD_ATTR IS_OP | 17,248,751 | 0.3% | 61.3% |
| LOAD_FAST BUILD_TUPLE | 17,047,876 | 0.3% | 61.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,682,762 | 0.3% | 61.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,190,986 | 0.3% | 62.2% |
| LOAD_ATTR LOAD_FAST | 16,074,257 | 0.3% | 62.5% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 16,061,501 | 0.3% | 62.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,028,216 | 0.3% | 63.1% |
| RESUME_CHECK LOAD_CONST | 15,734,733 | 0.3% | 63.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,704,183 | 0.3% | 63.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,665,996 | 0.3% | 63.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 15,653,154 | 0.3% | 64.2% |
| LOAD_FAST CALL_LIST_APPEND | 15,554,696 | 0.3% | 64.5% |
| RETURN_VALUE RETURN_VALUE | 15,184,008 | 0.3% | 64.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 15,112,952 | 0.3% | 65.0% |
| RESUME_CHECK POP_TOP | 15,106,924 | 0.3% | 65.3% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 15,102,417 | 0.3% | 65.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 15,042,407 | 0.3% | 65.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,694 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,634 | 56.2% |
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
| RESUME_CHECK | 99,201,292 | 77.8% |
| POP_TOP | 13,849,853 | 10.9% |
| COPY_FREE_VARS | 13,000,733 | 10.2% |
| MAKE_CELL | 1,509,193 | 1.2% |
| RESUME | 18,061 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 13,271,128 | 55.9% |
| LOAD_DEREF | 6,404,971 | 27.0% |
| BUILD_TUPLE | 1,790,150 | 7.5% |
| ENTER_EXECUTOR | 1,148,431 | 4.8% |
| LOAD_FAST | 734,372 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,825,342 | 28.8% |
| LOAD_FAST | 6,721,078 | 28.3% |
| RETURN_VALUE | 6,067,059 | 25.6% |
| CALL | 895,823 | 3.8% |
| GET_ITER | 895,115 | 3.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,678 | 73.6% |
| BUILD_TUPLE | 157,320 | 17.4% |
| LOAD_GLOBAL_MODULE | 79,350 | 8.8% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,528 | 100.0% |
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
| LOAD_FAST | 21,239,441 | 35.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,456,946 | 24.3% |
| CALL | 10,953,616 | 18.4% |
| RETURN_VALUE | 4,116,956 | 6.9% |
| CALL_BUILTIN_O | 2,591,160 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,981,789 | 33.6% |
| CALL_PY_EXACT_ARGS | 12,969,469 | 21.8% |
| FOR_ITER_TUPLE | 9,886,324 | 16.6% |
| LOAD_FAST_AND_CLEAR | 9,198,687 | 15.5% |
| FOR_ITER_LIST | 4,318,106 | 7.3% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 347,016 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,416 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,901,749 | 57.2% |
| RETURN_CONST | 32,284,243 | 25.3% |
| YIELD_VALUE | 22,189,546 | 17.4% |
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
| LOAD_CONST | 12,351,146 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,332,557 | 83.7% |
| LOAD_GLOBAL_BUILTIN | 794,290 | 6.4% |
| STORE_FAST | 669,679 | 5.4% |
| LOAD_FAST | 458,762 | 3.7% |
| STORE_NAME | 33,580 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,364,910 | 67.9% |
| POP_JUMP_IF_TRUE | 4,184,054 | 13.3% |
| STORE_FAST | 1,973,526 | 6.3% |
| POP_JUMP_IF_FALSE | 1,912,919 | 6.1% |
| POP_TOP | 1,391,978 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,281,221 | 39.0% |
| LOAD_DEREF | 10,424,294 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,663 | 20.3% |
| LOAD_FAST_LOAD_FAST | 899,635 | 2.9% |
| LOAD_CONST | 751,170 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,672 | 45.7% |
| POP_TOP | 358,596 | 39.6% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,672 | 45.7% |
| EXTENDED_ARG | 201,510 | 22.2% |
| ENTER_EXECUTOR | 155,366 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,106,924 | 24.6% |
| CACHE | 13,849,853 | 22.5% |
| RETURN_CONST | 9,243,163 | 15.0% |
| STORE_FAST | 5,839,735 | 9.5% |
| SWAP | 5,778,574 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 14,644,644 | 23.8% |
| RESUME_CHECK | 14,293,281 | 23.2% |
| ENTER_EXECUTOR | 9,275,971 | 15.1% |
| LOAD_FAST | 7,247,383 | 11.8% |
| RETURN_VALUE | 5,302,374 | 8.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,598 | 41.3% |
| BINARY_SUBSCR_DICT | 170,030 | 18.8% |
| RAISE_VARARGS | 115,310 | 12.7% |
| ENTER_EXECUTOR | 96,060 | 10.6% |
| LOAD_ATTR | 95,500 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,418 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,830 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,303,160 | 35.0% |
| LOAD_ATTR | 14,956,982 | 30.2% |
| LOAD_DEREF | 11,886,879 | 24.0% |
| CALL_BUILTIN_FAST | 2,129,900 | 4.3% |
| LOAD_SUPER_ATTR_ATTR | 1,182,030 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,366,301 | 71.5% |
| LOAD_FAST_LOAD_FAST | 12,185,337 | 24.6% |
| LOAD_CONST | 1,723,720 | 3.5% |
| LOAD_DEREF | 128,568 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,854,401 | 68.9% |
| CALL_PY_EXACT_ARGS | 4,117,620 | 28.8% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,159,114 | 71.0% |
| STORE_FAST | 2,660,521 | 18.6% |
| LOAD_FAST | 792,116 | 5.5% |
| GET_YIELD_FROM_ITER | 347,016 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,829,727 | 29.8% |
| LOAD_ATTR_SLOT | 33,433,259 | 18.8% |
| BUILD_TUPLE | 21,221,383 | 12.0% |
| RETURN_VALUE | 15,184,008 | 8.6% |
| CALL_BUILTIN_O | 11,433,131 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,901,749 | 41.1% |
| STORE_FAST | 38,555,144 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,466,550 | 11.0% |
| RETURN_VALUE | 15,184,008 | 8.6% |
| LOAD_FAST | 5,453,615 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,208,863 | 93.6% |
| ENTER_EXECUTOR | 94,665 | 2.8% |
| BINARY_SUBSCR | 93,200 | 2.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,290,448 | 96.0% |
| ENTER_EXECUTOR | 96,680 | 2.8% |
| JUMP_BACKWARD | 19,700 | 0.6% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,640 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.6% |
| LOAD_FAST | 2,207,793 | 17.1% |
| LOAD_GLOBAL_MODULE | 118,928 | 0.9% |
| LOAD_ATTR | 117,991 | 0.9% |
| RETURN_VALUE | 27,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,253,188 | 94.8% |
| POP_JUMP_IF_TRUE | 509,850 | 3.9% |
| UNARY_NOT | 84,100 | 0.7% |
| TO_BOOL_BOOL | 41,193 | 0.3% |
| TO_BOOL | 21,484 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,490 | 22.0% |
| LOAD_FAST | 109,500 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,702 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 132,000 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,840 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,134 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,740 | 65.3% |
| TO_BOOL_BOOL | 1,085,005 | 20.6% |
| TO_BOOL_LIST | 661,899 | 12.6% |
| TO_BOOL | 84,100 | 1.6% |
| TO_BOOL_INT | 164 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,508 | 66.9% |
| STORE_FAST | 882,785 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,864 | 1.6% |
| LOAD_CONST | 34,371 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,759,718 | 33.3% |
| COMPARE_OP_INT | 6,304,740 | 17.8% |
| COMPARE_OP | 6,162,400 | 17.4% |
| CALL_TUPLE_1 | 4,707,391 | 13.3% |
| LOAD_FAST | 2,606,942 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,216,501 | 68.6% |
| RETURN_VALUE | 5,771,310 | 16.3% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,151 | 3.1% |
| LOAD_FAST | 857,915 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,248 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,468 | 97.8% |
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
| SWAP | 4,464,476 | 20.7% |
| POP_JUMP_IF_TRUE | 4,083,164 | 18.9% |
| STORE_FAST | 3,816,555 | 17.7% |
| LOAD_FAST | 2,312,334 | 10.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,712,833 | 54.3% |
| SWAP | 4,464,476 | 20.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,419 | 10.6% |
| LOAD_FAST | 1,374,689 | 6.4% |
| BUILD_LIST | 748,364 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,167,945 | 36.0% |
| BUILD_TUPLE | 10,996,582 | 32.5% |
| SWAP | 4,716,211 | 14.0% |
| LOAD_CONST | 1,656,800 | 4.9% |
| RESUME_CHECK | 1,285,960 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,181,504 | 68.6% |
| SWAP | 4,716,211 | 14.0% |
| STORE_FAST | 3,331,435 | 9.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 4.6% |
| CALL_FUNCTION_EX | 734,880 | 2.2% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,453 | 64.2% |
| SWAP | 18,000 | 35.6% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,453 | 64.2% |
| SWAP | 18,000 | 35.6% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,008 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.8% |
| BINARY_SUBSCR | 168 | 4.2% |


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
| LOAD_FAST_LOAD_FAST | 25,623,971 | 45.1% |
| LOAD_FAST | 17,047,876 | 30.0% |
| LOAD_ATTR_SLOT | 5,042,378 | 8.9% |
| LOAD_ATTR | 3,034,654 | 5.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,221,383 | 37.4% |
| BUILD_MAP | 10,996,582 | 19.4% |
| LOAD_CONST | 10,355,525 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 4,707,191 | 8.3% |
| CALL_LIST_APPEND | 3,216,080 | 5.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,634,143 | 35.9% |
| LOAD_FAST | 7,273,856 | 27.1% |
| LOAD_ATTR | 3,067,202 | 11.4% |
| BINARY_OP_MULTIPLY_INT | 2,291,864 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,962 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,616 | 40.8% |
| STORE_FAST | 5,844,761 | 21.8% |
| RETURN_VALUE | 4,522,634 | 16.9% |
| POP_TOP | 1,118,705 | 4.2% |
| RESUME_CHECK | 1,066,212 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 23,270,710 | 83.1% |
| LOAD_FAST | 2,317,611 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,951 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |
| BINARY_OP | 201,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,601,117 | 45.0% |
| RESUME_CHECK | 11,673,737 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,874 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,348,129 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,951 | 93.2% |
| BUILD_MAP | 91,338 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,509,319 | 98.5% |
| ENTER_EXECUTOR | 164,171 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,489 | 88.9% |
| POP_TOP | 698,059 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,815 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,885 | 54.9% |
| LOAD_FAST | 8,117,023 | 21.1% |
| CALL_TYPE_1 | 5,882,641 | 15.3% |
| LOAD_GLOBAL_MODULE | 1,179,155 | 3.1% |
| LOAD_CONST | 950,551 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,954,258 | 52.0% |
| BINARY_OP | 6,162,400 | 16.1% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.1% |
| UNARY_NOT | 3,442,740 | 9.0% |
| POP_JUMP_IF_TRUE | 2,278,911 | 5.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20,047,912 | 53.0% |
| LOAD_FAST_LOAD_FAST | 10,485,030 | 27.7% |
| LOAD_GLOBAL_MODULE | 5,290,116 | 14.0% |
| LOAD_DEREF | 1,480,880 | 3.9% |
| LOAD_CONST | 174,991 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,608,467 | 91.5% |
| POP_JUMP_IF_TRUE | 3,215,289 | 8.5% |
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
| LOAD_FAST | 1,237,542 | 26.7% |
| COPY | 1,074,000 | 23.2% |
| LOAD_FAST_LOAD_FAST | 872,880 | 18.9% |
| CALL_ISINSTANCE | 525,020 | 11.3% |
| LOAD_CONST | 236,786 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,339,217 | 28.9% |
| COPY | 1,074,000 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,067,720 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,586 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,000,733 | 41.0% |
| CALL_PY_EXACT_ARGS | 11,783,338 | 37.1% |
| LOAD_ATTR_PROPERTY | 5,065,481 | 16.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,196,733 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,787,127 | 68.7% |
| RETURN_GENERATOR | 9,854,401 | 31.1% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,188 | 0.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 98.7% |
| POP_JUMP_IF_NONE | 15,920 | 1.2% |
| ENTER_EXECUTOR | 740 | 0.1% |
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
| LOAD_FAST | 23,141,782 | 99.4% |
| LOAD_DEREF | 128,928 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 23,270,710 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 27,670,696 | 32.9% |
| CALL_LIST_APPEND | 15,102,417 | 18.0% |
| STORE_SUBSCR_LIST_INT | 9,864,723 | 11.7% |
| POP_TOP | 9,275,971 | 11.0% |
| EXTENDED_ARG | 5,758,180 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 29,616,652 | 35.2% |
| LOAD_FAST | 10,209,075 | 12.1% |
| RESUME_CHECK | 9,216,672 | 11.0% |
| RETURN_CONST | 6,600,860 | 7.8% |
| ENTER_EXECUTOR | 5,395,933 | 6.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,065,977 | 33.0% |
| CALL_LIST_APPEND | 4,571,199 | 29.8% |
| GET_ITER | 2,378,209 | 15.5% |
| COMPARE_OP_INT | 1,719,911 | 11.2% |
| POP_JUMP_IF_FALSE | 810,364 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,612,666 | 43.1% |
| ENTER_EXECUTOR | 5,758,180 | 37.5% |
| FOR_ITER_LIST | 1,354,535 | 8.8% |
| FOR_ITER_RANGE | 642,400 | 4.2% |
| FOR_ITER_TUPLE | 395,000 | 2.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 67,365,159 | 64.8% |
| GET_ITER | 19,981,789 | 19.2% |
| SWAP | 7,638,647 | 7.3% |
| LOAD_FAST | 7,584,402 | 7.3% |
| ENTER_EXECUTOR | 1,256,242 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 71,263,192 | 68.6% |
| STORE_FAST | 8,310,660 | 8.0% |
| SWAP | 7,602,951 | 7.3% |
| RETURN_CONST | 4,697,774 | 4.5% |
| LOAD_FAST | 4,677,450 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,396 | 86.6% |
| STORE_FAST | 982,524 | 11.0% |
| STORE_DEREF | 185,711 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,035 | 76.2% |
| STORE_DEREF | 2,092,536 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,759,796 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,396 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 17,248,751 | 36.1% |
| LOAD_FAST | 12,786,354 | 26.8% |
| LOAD_CONST | 10,976,920 | 23.0% |
| LOAD_FAST_LOAD_FAST | 5,893,765 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 539,781 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,050,158 | 62.9% |
| YIELD_VALUE | 12,771,016 | 26.7% |
| POP_JUMP_IF_TRUE | 4,906,972 | 10.3% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 20,900,486 | 30.9% |
| POP_JUMP_IF_TRUE | 16,061,501 | 23.7% |
| POP_TOP | 14,644,644 | 21.6% |
| MAP_ADD | 7,867,213 | 11.6% |
| CALL_LIST_APPEND | 2,240,217 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 67,365,159 | 99.6% |
| FOR_ITER_GEN | 100,575 | 0.1% |
| FOR_ITER_TUPLE | 80,737 | 0.1% |
| FOR_ITER_LIST | 53,846 | 0.1% |
| EXTENDED_ARG | 27,594 | 0.0% |


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
| STORE_FAST | 4,137,905 | 72.0% |
| POP_TOP | 734,268 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,886 | 3.3% |
| LOAD_FAST | 137,368 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,996,992 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,052 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,651 | 5.7% |
| STORE_FAST | 118,968 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,963,490 | 51.6% |
| BUILD_TUPLE | 1,568,859 | 27.3% |
| RETURN_VALUE | 510,735 | 8.9% |
| BINARY_SUBSCR | 489,428 | 8.5% |
| LOAD_ATTR_PROPERTY | 64,731 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,019,286 | 70.0% |
| JUMP_BACKWARD | 1,718,824 | 29.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,347,249 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,348,129 | 99.9% |
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
| LOAD_FAST | 51,088,235 | 42.0% |
| LOAD_GLOBAL_MODULE | 33,554,888 | 27.6% |
| ENTER_EXECUTOR | 29,616,652 | 24.3% |
| CALL_TYPE_1 | 2,352,512 | 1.9% |
| LOAD_ATTR_SLOT | 2,297,079 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,820,261 | 30.2% |
| CONTAINS_OP | 20,047,912 | 16.5% |
| IS_OP | 17,248,751 | 14.2% |
| LOAD_FAST | 16,074,257 | 13.2% |
| PUSH_NULL | 14,956,982 | 12.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,611,809 | 33.9% |
| LOAD_CONST | 40,214,741 | 22.5% |
| RESUME_CHECK | 15,734,733 | 8.8% |
| BUILD_TUPLE | 10,355,525 | 5.8% |
| RETURN_CONST | 9,526,680 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,214,741 | 22.5% |
| CALL_BUILTIN_FAST | 24,056,487 | 13.4% |
| COMPARE_OP_INT | 20,756,904 | 11.6% |
| STORE_FAST | 14,274,855 | 8.0% |
| MAKE_FUNCTION | 12,351,146 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,703,986 | 33.2% |
| NOP | 10,424,294 | 16.7% |
| LOAD_ATTR_SLOT | 6,404,971 | 10.3% |
| POP_JUMP_IF_FALSE | 4,644,712 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,082 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 20,874,450 | 33.5% |
| PUSH_NULL | 11,886,879 | 19.1% |
| LOAD_FAST | 9,396,159 | 15.1% |
| BINARY_SUBSCR | 6,404,971 | 10.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 5.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 161,628,299 | 17.7% |
| LOAD_GLOBAL_BUILTIN | 156,045,367 | 17.1% |
| RESUME_CHECK | 115,504,552 | 12.7% |
| POP_JUMP_IF_FALSE | 109,990,243 | 12.1% |
| STORE_FAST_STORE_FAST | 40,964,563 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,140,541 | 10.3% |
| LOAD_ATTR_METHOD_NO_DICT | 76,878,513 | 8.4% |
| LOAD_GLOBAL_MODULE | 61,808,349 | 6.8% |
| LOAD_CONST | 60,611,809 | 6.6% |
| RETURN_VALUE | 52,829,727 | 5.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,687 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,590,010 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,607 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,590,010 | 45.2% |
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
| STORE_FAST | 50,454,381 | 21.6% |
| LOAD_GLOBAL_BUILTIN | 28,705,734 | 12.3% |
| POP_JUMP_IF_FALSE | 28,643,333 | 12.3% |
| RESUME_CHECK | 18,562,417 | 7.9% |
| STORE_FAST_STORE_FAST | 15,653,154 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,333,234 | 11.3% |
| BUILD_TUPLE | 25,623,971 | 11.0% |
| COMPARE_OP | 21,088,885 | 9.0% |
| STORE_SUBSCR_LIST_INT | 18,849,837 | 8.1% |
| CALL_BUILTIN_FAST | 17,264,740 | 7.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,284 | 19.4% |
| LOAD_FAST | 34,224 | 18.8% |
| STORE_FAST | 26,940 | 14.8% |
| RESUME_CHECK | 10,931 | 6.0% |
| RESUME | 10,791 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,549 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,258 | 22.7% |
| LOAD_FAST | 39,621 | 21.8% |
| LOAD_ATTR | 14,087 | 7.7% |
| CALL | 9,835 | 5.4% |


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
| LOAD_FAST | 1,084 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.5% |
| CALL | 324 | 26.9% |
| LOAD_FAST | 180 | 15.0% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,275,202 | 37.6% |
| CACHE | 1,509,193 | 24.9% |
| CALL_PY_EXACT_ARGS | 770,515 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,486 | 10.8% |
| CALL | 523,750 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,362 | 62.3% |
| MAKE_CELL | 2,275,202 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,854,393 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,867,213 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 109,487,273 | 39.7% |
| CONTAINS_OP | 34,608,467 | 12.6% |
| COMPARE_OP_INT | 33,197,318 | 12.0% |
| IS_OP | 30,050,158 | 10.9% |
| COMPARE_OP | 19,954,258 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 109,990,243 | 39.9% |
| LOAD_GLOBAL_BUILTIN | 57,705,279 | 20.9% |
| RETURN_CONST | 29,163,444 | 10.6% |
| LOAD_FAST_LOAD_FAST | 28,643,333 | 10.4% |
| ENTER_EXECUTOR | 27,670,696 | 10.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,034,712 | 80.6% |
| BINARY_SUBSCR | 6,825,342 | 16.7% |
| LOAD_DEREF | 1,088,878 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 5,451 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,900,486 | 51.0% |
| LOAD_FAST_LOAD_FAST | 14,686,841 | 35.8% |
| LOAD_FAST | 2,501,160 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,438,339 | 3.5% |
| LOAD_CONST | 1,111,456 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,682,762 | 92.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,102 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,226,956 | 67.5% |
| LOAD_FAST_LOAD_FAST | 2,010,065 | 11.1% |
| LOAD_GLOBAL_MODULE | 1,878,808 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,149 | 7.6% |
| ENTER_EXECUTOR | 441,737 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,130,109 | 71.0% |
| TO_BOOL_INT | 8,695,931 | 11.4% |
| IS_OP | 4,906,972 | 6.4% |
| CONTAINS_OP | 3,215,289 | 4.2% |
| COMPARE_OP | 2,278,911 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,802,495 | 49.6% |
| JUMP_BACKWARD | 16,061,501 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 5,256,626 | 6.9% |
| NOP | 4,184,054 | 5.5% |
| BUILD_LIST | 4,083,164 | 5.4% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,970 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,310 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,163,444 | 51.1% |
| RESUME_CHECK | 10,045,813 | 17.6% |
| ENTER_EXECUTOR | 6,600,860 | 11.6% |
| FOR_ITER | 4,697,774 | 8.2% |
| STORE_SUBSCR | 3,290,448 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,284,243 | 56.5% |
| LOAD_CONST | 9,526,680 | 16.7% |
| POP_TOP | 9,243,163 | 16.2% |
| TO_BOOL_BOOL | 3,461,853 | 6.1% |
| STORE_FAST | 1,541,228 | 2.7% |


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
| MAKE_FUNCTION | 10,332,557 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,781,305 | 94.7% |
| STORE_FAST | 298,306 | 2.9% |
| STORE_DEREF | 95,650 | 0.9% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,976 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,957 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,908 | 0.7% |
| SWAP | 2,155 | 0.4% |
| LOAD_DEREF | 16 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,727 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,310 | 19.7% |
| LOAD_FAST | 89,983 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.4% |
| IMPORT_FROM | 2,092,536 | 27.2% |
| LOAD_ATTR | 1,558,875 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,650 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.4% |
| POP_TOP | 1,906,825 | 24.8% |
| LOAD_DEREF | 1,298,386 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,711 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,555,144 | 13.0% |
| LOAD_ATTR | 36,820,261 | 12.4% |
| BINARY_OP | 24,216,501 | 8.1% |
| LOAD_ATTR_SLOT | 22,508,559 | 7.6% |
| LOAD_CONST | 14,274,855 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 161,628,299 | 54.3% |
| LOAD_FAST_LOAD_FAST | 50,454,381 | 17.0% |
| LOAD_GLOBAL_BUILTIN | 32,309,871 | 10.9% |
| LOAD_GLOBAL_MODULE | 11,363,506 | 3.8% |
| STORE_FAST | 9,345,101 | 3.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,382 | 69.6% |
| FOR_ITER_TUPLE | 409,364 | 22.6% |
| FOR_ITER | 92,962 | 5.1% |
| FOR_ITER_RANGE | 47,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,338 | 67.5% |
| LOAD_ATTR_PROPERTY | 201,722 | 11.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,388 | 10.4% |
| LOAD_DEREF | 51,440 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 96,641,879 | 93.5% |
| RETURN_VALUE | 3,248,252 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,396,523 | 1.4% |
| STORE_FAST_STORE_FAST | 771,036 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,964,563 | 39.6% |
| LOAD_GLOBAL_BUILTIN | 21,982,364 | 21.3% |
| LOAD_DEREF | 20,703,986 | 20.0% |
| LOAD_FAST_LOAD_FAST | 15,653,154 | 15.1% |
| LOAD_GLOBAL_MODULE | 1,958,160 | 1.9% |


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
| BINARY_SUBSCR_LIST_INT | 9,396,443 | 20.9% |
| LOAD_FAST_AND_CLEAR | 9,198,607 | 20.4% |
| FOR_ITER | 7,602,951 | 16.9% |
| BUILD_MAP | 4,716,211 | 10.5% |
| LOAD_FAST | 4,641,394 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,396,663 | 20.9% |
| STORE_FAST | 7,931,366 | 17.6% |
| FOR_ITER | 7,638,647 | 17.0% |
| POP_TOP | 5,778,574 | 12.8% |
| BUILD_MAP | 4,716,211 | 10.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,460 | 26.2% |
| FOR_ITER | 6,804 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 4,007 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,684 | 46.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,428 | 23.6% |
| STORE_FAST | 8,236 | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,144 | 2.9% |
| UNPACK_SEQUENCE | 917 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,771,016 | 55.4% |
| ENTER_EXECUTOR | 4,716,424 | 20.5% |
| CALL_ISINSTANCE | 2,335,179 | 10.1% |
| LOAD_FAST | 1,146,952 | 5.0% |
| YIELD_VALUE | 677,496 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,189,546 | 96.3% |
| YIELD_VALUE | 677,496 | 2.9% |
| STORE_FAST | 162,884 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,061 | 38.0% |
| CALL | 11,120 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,096 | 12.8% |
| POP_TOP | 3,962 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,699 | 37.2% |
| LOAD_GLOBAL | 10,791 | 22.7% |
| LOAD_CONST | 8,763 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,362 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,634,432 | 69.6% |
| LOAD_FAST_LOAD_FAST | 573,491 | 15.2% |
| BINARY_SUBSCR_DICT | 422,960 | 11.2% |
| CALL_BUILTIN_CLASS | 81,088 | 2.1% |
| LOAD_FAST | 43,680 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,576,067 | 41.6% |
| SWAP | 944,655 | 25.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 539,958 | 14.3% |
| LOAD_CONST | 268,884 | 7.1% |
| LOAD_FAST | 201,360 | 5.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 480,720 | 86.9% |
| CALL_METHOD_DESCRIPTOR_O | 39,600 | 7.2% |
| LOAD_FAST | 15,880 | 2.9% |
| LOAD_FAST_LOAD_FAST | 8,400 | 1.5% |
| BINARY_SUBSCR_LIST_INT | 3,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 499,720 | 90.4% |
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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,674 | 60.4% |
| LOAD_ATTR_SLOT | 723,527 | 26.2% |
| LOAD_FAST_LOAD_FAST | 276,524 | 10.0% |
| LOAD_FAST | 94,300 | 3.4% |
| BINARY_OP | 1,464 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,864 | 82.9% |
| LOAD_FAST_LOAD_FAST | 181,168 | 6.6% |
| STORE_FAST | 175,500 | 6.3% |
| LOAD_FAST | 83,308 | 3.0% |
| LOAD_GLOBAL_MODULE | 25,193 | 0.9% |


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
| LOAD_CONST | 1,568,860 | 63.1% |
| LOAD_FAST_LOAD_FAST | 606,616 | 24.4% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,667 | 4.9% |
| BINARY_OP | 2,188 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,082,420 | 43.6% |
| STORE_FAST | 709,744 | 28.6% |
| BINARY_OP | 311,568 | 12.5% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,129,394 | 34.6% |
| LOAD_FAST_LOAD_FAST | 923,510 | 28.3% |
| LOAD_CONST | 642,800 | 19.7% |
| CALL_TUPLE_1 | 443,840 | 13.6% |
| RETURN_VALUE | 114,403 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,376 | 26.6% |
| RETURN_VALUE | 809,076 | 24.8% |
| BINARY_OP_ADD_INT | 422,960 | 13.0% |
| PUSH_NULL | 376,980 | 11.6% |
| SWAP | 318,100 | 9.8% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 59,680 | 37.5% |
| LOAD_FAST_LOAD_FAST | 40,800 | 25.6% |
| ENTER_EXECUTOR | 39,680 | 24.9% |
| LOAD_CONST | 14,568 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,264 | 100.0% |
| RETURN_VALUE | 2 | 0.0% |
| LOAD_CONST | 2 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,333,234 | 90.9% |
| COPY | 1,067,720 | 3.7% |
| LOAD_CONST | 1,026,730 | 3.5% |
| CALL_BUILTIN_CLASS | 282,262 | 1.0% |
| LOAD_FAST | 204,215 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,404,803 | 32.5% |
| SWAP | 9,396,443 | 32.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,499,308 | 25.9% |
| LOAD_CONST | 1,068,180 | 3.7% |
| RETURN_VALUE | 432,318 | 1.5% |


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
| LOAD_CONST | 8,721,574 | 97.0% |
| LOAD_FAST | 263,280 | 2.9% |
| BINARY_SUBSCR | 2,740 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,550 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,114 | 3.6% |
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
| LOAD_FAST | 13,221,729 | 90.9% |
| BINARY_OP_ADD_INT | 539,958 | 3.7% |
| LOAD_FAST_LOAD_FAST | 480,454 | 3.3% |
| LOAD_ATTR | 152,040 | 1.0% |
| LOAD_DEREF | 83,580 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,691,905 | 87.2% |
| COPY_FREE_VARS | 1,196,733 | 8.2% |
| MAKE_CELL | 654,486 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| CALL_PY_EXACT_ARGS | 673 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,199 | 32.4% |
| CALL_BUILTIN_CLASS | 1,959,407 | 22.7% |
| LOAD_CONST | 710,920 | 8.2% |
| CALL_LEN | 611,078 | 7.1% |
| BINARY_SUBSCR | 571,578 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,069,806 | 35.6% |
| CALL_BUILTIN_CLASS | 1,959,407 | 22.7% |
| GET_ITER | 1,728,513 | 20.0% |
| CALL | 284,216 | 3.3% |
| BINARY_SUBSCR_LIST_INT | 282,262 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,056,487 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,264,740 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,386 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 55,488 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,002,162 | 41.8% |
| STORE_FAST | 10,923,695 | 25.4% |
| TO_BOOL | 10,287,220 | 23.9% |
| PUSH_NULL | 2,129,900 | 4.9% |
| RETURN_VALUE | 1,500,478 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,911 | 94.4% |
| LOAD_FAST | 134,938 | 2.6% |
| BINARY_OP | 119,028 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,191 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,838 | 2.5% |
| CALL_BUILTIN_CLASS | 119,028 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,704,183 | 41.7% |
| RETURN_GENERATOR | 10,159,114 | 27.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,610,749 | 14.9% |
| LOAD_ATTR_SLOT | 4,881,992 | 13.0% |
| BINARY_OP | 1,095,151 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,587,853 | 36.1% |
| RETURN_VALUE | 11,433,131 | 30.4% |
| TO_BOOL_BOOL | 9,836,675 | 26.1% |
| GET_ITER | 2,591,160 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,788,383 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 18,938,673 | 30.3% |
| LOAD_DEREF | 3,018,109 | 4.8% |
| LOAD_FAST_LOAD_FAST | 2,763,787 | 4.4% |
| LOAD_FAST | 1,614,972 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,536,164 | 95.2% |
| YIELD_VALUE | 2,335,179 | 3.7% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,555 | 0.2% |
| TO_BOOL | 9,664 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,055,715 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 185,800 | 0.7% |
| RETURN_VALUE | 95,144 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,271,148 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,846 | 34.4% |
| LOAD_CONST | 7,191,482 | 25.6% |
| CALL_BUILTIN_CLASS | 611,078 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,554,696 | 64.8% |
| BUILD_TUPLE | 3,216,080 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 959,820 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,102,417 | 62.9% |
| EXTENDED_ARG | 4,571,199 | 19.0% |
| JUMP_BACKWARD | 2,240,217 | 9.3% |
| LOAD_FAST | 1,681,764 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,112,952 | 68.8% |
| LOAD_CONST | 2,388,373 | 10.9% |
| BUILD_LIST | 2,294,419 | 10.4% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 271,625 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,817,654 | 58.3% |
| STORE_FAST | 3,415,547 | 15.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.2% |
| POP_TOP | 908,874 | 4.1% |
| GET_ITER | 737,619 | 3.4% |


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
| LOAD_ATTR_METHOD_NO_DICT | 24,512,802 | 83.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,749 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,791 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,456,946 | 49.0% |
| STORE_FAST | 9,687,224 | 32.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,911 | 16.5% |
| CALL_BUILTIN_CLASS | 169,735 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,791 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.2% |
| LOAD_CONST | 1,226,602 | 26.7% |
| LOAD_FAST | 296,920 | 6.5% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.4% |
| LOAD_CONST | 1,224,602 | 26.7% |
| TO_BOOL_NONE | 48,400 | 1.1% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,801,874 | 31.4% |
| LOAD_FAST | 15,665,996 | 23.7% |
| GET_ITER | 12,969,469 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,195,700 | 18.4% |
| LOAD_SUPER_ATTR_METHOD | 1,539,392 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 49,357,484 | 74.5% |
| COPY_FREE_VARS | 11,783,338 | 17.8% |
| RETURN_GENERATOR | 4,117,620 | 6.2% |
| MAKE_CELL | 770,515 | 1.2% |
| CALL_PY_EXACT_ARGS | 145,003 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,622,076 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,413,478 | 30.8% |
| ENTER_EXECUTOR | 974,902 | 21.2% |
| RETURN_VALUE | 192,548 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,736 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,005 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,755 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,191 | 80.4% |
| LOAD_FAST | 1,017,331 | 17.4% |
| STORE_FAST | 105,796 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,176 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,391 | 80.4% |
| BINARY_SUBSCR_DICT | 443,840 | 7.6% |
| STORE_FAST | 353,236 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,729,616 | 99.2% |
| LOAD_CONST | 120,030 | 0.8% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,798 | 43.3% |
| COMPARE_OP | 5,882,641 | 39.6% |
| LOAD_ATTR | 2,352,512 | 15.8% |
| IS_OP | 64,290 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,504 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,775 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,059 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,756,904 | 42.6% |
| LOAD_FAST_LOAD_FAST | 16,190,986 | 33.2% |
| CALL_LEN | 10,271,148 | 21.1% |
| LOAD_FAST | 1,020,441 | 2.1% |
| LOAD_ATTR_SLOT | 225,467 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,197,318 | 68.1% |
| BINARY_OP | 6,304,740 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,719,911 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,566,000 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 68.9% |
| LOAD_CONST | 4,335,958 | 29.8% |
| LOAD_GLOBAL_MODULE | 192,348 | 1.3% |
| LOAD_ATTR | 3,160 | 0.0% |
| LOAD_FAST | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,646 | 99.4% |
| YIELD_VALUE | 79,920 | 0.5% |
| POP_JUMP_IF_TRUE | 3,520 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,844,911 | 37.4% |
| GET_ITER | 4,318,106 | 33.3% |
| EXTENDED_ARG | 1,354,535 | 10.5% |
| SWAP | 1,221,501 | 9.4% |
| ENTER_EXECUTOR | 1,151,289 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,931,645 | 61.2% |
| LOAD_FAST | 2,085,166 | 16.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,535,117 | 11.9% |
| STORE_FAST_LOAD_FAST | 1,260,382 | 9.7% |
| RETURN_CONST | 85,483 | 0.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 669,149 | 47.9% |
| EXTENDED_ARG | 642,400 | 46.0% |
| SWAP | 38,880 | 2.8% |
| LOAD_FAST | 29,360 | 2.1% |
| JUMP_BACKWARD | 16,538 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,743 | 93.5% |
| STORE_FAST_LOAD_FAST | 47,440 | 3.4% |
| RETURN_CONST | 35,966 | 2.6% |
| LOAD_FAST | 3,780 | 0.3% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,886,324 | 84.6% |
| LOAD_FAST | 518,058 | 4.4% |
| ENTER_EXECUTOR | 488,245 | 4.2% |
| EXTENDED_ARG | 395,000 | 3.4% |
| SWAP | 299,659 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,112,723 | 86.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 466,061 | 4.0% |
| STORE_FAST_LOAD_FAST | 409,364 | 3.5% |
| RETURN_CONST | 369,261 | 3.2% |
| LOAD_GLOBAL_BUILTIN | 117,460 | 1.0% |


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
| LOAD_FAST | 5,479,272 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,736 | 11.7% |
| LOAD_DEREF | 1,058,196 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,612 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,542 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,386 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,225,102 | 13.5% |
| STORE_FAST | 1,075,896 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,736 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,878,513 | 85.8% |
| RETURN_VALUE | 4,635,587 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.5% |
| LOAD_GLOBAL_MODULE | 1,964,977 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,542 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,794,203 | 34.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,512,802 | 27.4% |
| CALL_PY_EXACT_ARGS | 20,801,874 | 23.2% |
| LOAD_CONST | 4,052,352 | 4.5% |
| LOAD_DEREF | 3,319,082 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 20,874,450 | 71.2% |
| LOAD_ATTR_SLOT | 4,711,291 | 16.1% |
| LOAD_FAST | 3,523,287 | 12.0% |
| LOAD_ATTR | 147,522 | 0.5% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,042,407 | 51.3% |
| LOAD_FAST_LOAD_FAST | 9,153,541 | 31.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,749 | 16.4% |
| CALL_PY_EXACT_ARGS | 313,471 | 1.1% |
| LOAD_CONST | 6,773 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,505 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,404 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,043,981 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,588 | 6.3% |
| CALL | 57,380 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR | 19,780 | 1.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,590,357 | 87.2% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| ENTER_EXECUTOR | 2,965,885 | 5.2% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 215,783 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,384,988 | 74.5% |
| CALL_BUILTIN_O | 5,610,749 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,298 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,674 | 2.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 991,179 | 60.2% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| ENTER_EXECUTOR | 10,742 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.1% |
| TO_BOOL_STR | 478,200 | 29.1% |
| TO_BOOL_BOOL | 408,723 | 24.8% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,301,007 | 90.4% |
| ENTER_EXECUTOR | 1,312,254 | 4.7% |
| RETURN_VALUE | 642,520 | 2.3% |
| STORE_FAST_LOAD_FAST | 201,722 | 0.7% |
| LOAD_DEREF | 190,748 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,813,169 | 67.2% |
| COPY_FREE_VARS | 5,065,481 | 18.1% |
| GET_ITER | 1,920,425 | 6.9% |
| TO_BOOL_BOOL | 708,718 | 2.5% |
| STORE_FAST | 506,848 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,140,541 | 98.6% |
| LOAD_ATTR_SLOT | 613,650 | 0.6% |
| ENTER_EXECUTOR | 553,380 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,059 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 70,019 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,433,259 | 35.0% |
| STORE_FAST | 22,508,559 | 23.6% |
| LOAD_DEREF | 6,404,971 | 6.7% |
| LOAD_CONST | 5,202,434 | 5.4% |
| LOAD_FAST | 5,202,359 | 5.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,705,279 | 25.5% |
| RESUME_CHECK | 41,266,896 | 18.3% |
| STORE_FAST | 32,309,871 | 14.3% |
| STORE_FAST_STORE_FAST | 21,982,364 | 9.7% |
| LOAD_FAST | 20,354,441 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,045,367 | 69.1% |
| LOAD_FAST_LOAD_FAST | 28,705,734 | 12.7% |
| CALL_ISINSTANCE | 18,938,673 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 8,972,939 | 4.0% |
| LOAD_DEREF | 3,221,174 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,808,349 | 50.8% |
| RESUME_CHECK | 16,028,216 | 13.2% |
| STORE_FAST | 11,363,506 | 9.3% |
| POP_JUMP_IF_FALSE | 9,673,903 | 8.0% |
| NOP | 6,377,663 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 35,788,383 | 29.4% |
| LOAD_ATTR | 33,554,888 | 27.6% |
| LOAD_FAST | 29,410,786 | 24.2% |
| CONTAINS_OP | 5,290,116 | 4.4% |
| LOAD_FAST_LOAD_FAST | 3,279,072 | 2.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,630 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,182,030 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,649 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,392 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,257 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,201,292 | 38.7% |
| CALL_PY_EXACT_ARGS | 49,357,484 | 19.2% |
| COPY_FREE_VARS | 21,787,127 | 8.5% |
| LOAD_ATTR_PROPERTY | 18,813,169 | 7.3% |
| POP_TOP | 14,293,281 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,504,552 | 45.0% |
| LOAD_GLOBAL_BUILTIN | 41,266,896 | 16.1% |
| NOP | 21,364,910 | 8.3% |
| LOAD_FAST_LOAD_FAST | 18,562,417 | 7.2% |
| LOAD_GLOBAL_MODULE | 16,028,216 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,996 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,936 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,989 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,135 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,811 | 36.0% |
| RETURN_CONST | 887,496 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,229 | 52.2% |
| LOAD_FAST | 4,284,797 | 47.3% |
| STORE_ATTR_SLOT | 41,692 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,009 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,093 | 24.9% |
| LOAD_CONST | 1,890,702 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,862 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,571,895 | 68.9% |
| LOAD_FAST | 397,966 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,335 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,652,380 | 72.4% |
| EXTENDED_ARG | 226,746 | 9.9% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.0% |
| LOAD_FAST | 165,800 | 7.3% |
| LOAD_GLOBAL_MODULE | 38,955 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,849,837 | 93.3% |
| SWAP | 1,067,720 | 5.3% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,424 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,021,503 | 49.6% |
| ENTER_EXECUTOR | 9,864,723 | 48.8% |
| JUMP_BACKWARD | 250,255 | 1.2% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,495 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| ENTER_EXECUTOR | 480 | 0.2% |
| TO_BOOL | 386 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,404 | 95.1% |
| POP_JUMP_IF_FALSE | 9,666 | 4.2% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 51 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,536,164 | 35.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,384,988 | 25.0% |
| LOAD_FAST | 21,602,266 | 12.7% |
| CALL_BUILTIN_FAST | 18,002,162 | 10.6% |
| CALL_BUILTIN_O | 9,836,675 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 109,487,273 | 64.5% |
| POP_JUMP_IF_TRUE | 54,130,109 | 31.9% |
| EXTENDED_ARG | 5,065,977 | 3.0% |
| UNARY_NOT | 1,085,005 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,173,654 | 95.3% |
| BINARY_OP | 732,384 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 63,252 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,861 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,363,864 | 54.4% |
| POP_JUMP_IF_TRUE | 8,695,931 | 45.6% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 164 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,845 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,135 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,144 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 823,845 | 36.0% |
| POP_JUMP_IF_TRUE | 784,560 | 34.3% |
| UNARY_NOT | 661,899 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,719 | 69.4% |
| RETURN_VALUE | 389,376 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,581 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 48,400 | 1.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,950 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,666 | 73.3% |
| POP_JUMP_IF_TRUE | 690,105 | 26.0% |
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
| LOAD_FAST | 120,339 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,659 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 884,404 | 55.6% |
| RETURN_VALUE | 660,927 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,144 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,396,523 | 87.8% |
| STORE_FAST | 154,692 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 71,263,192 | 70.9% |
| RETURN_VALUE | 19,466,550 | 19.4% |
| BINARY_SUBSCR_LIST_INT | 7,499,308 | 7.5% |
| FOR_ITER_LIST | 1,535,117 | 1.5% |
| FOR_ITER_TUPLE | 466,061 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 96,641,879 | 96.2% |
| STORE_DEREF | 3,577,880 | 3.6% |
| STORE_FAST | 218,485 | 0.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,680 | 0.0% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 22,525 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,525 | 100.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,575 | 52.6% |
| GET_ITER | 90,694 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,655 | 52.1% |
| POP_TOP | 90,534 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


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
|     deferred | 35,267,147 | 78.5% |
|          hit | 9,590,628 | 21.4% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,796 | 11.7% |
| Failure | 51,355 | 88.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,463 | 18.4% |
| multiply different types | 7,464 | 14.5% |
| subtract other | 6,800 | 13.2% |
| and int | 4,143 | 8.1% |
| rshift | 3,823 | 7.4% |
| or | 3,700 | 7.2% |
| power | 2,868 | 5.6% |
| true divide different types | 2,524 | 4.9% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,311 | 4.5% |
| add different types | 1,944 | 3.8% |
| floor divide | 1,276 | 2.5% |
| subtract different types | 1,190 | 2.3% |
| xor | 584 | 1.1% |
| and other | 377 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 224 | 0.4% |
| true divide float | 4 | 0.0% |


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
|     deferred | 23,710,987 | 36.4% |
|          hit | 41,388,085 | 63.5% |
|         miss | 14,938 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,720 | 32.6% |
| Failure | 15,957 | 67.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 12,133 | 76.0% |
| out of range | 2,040 | 12.8% |
| buffer int | 1,760 | 11.0% |
| array int | 20 | 0.1% |
| tuple slice | 4 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,107,768 | 6.3% |
|        deopt | 22,840 | 0.0% |
|          hit | 354,919,158 | 85.9% |
|         miss | 31,448,664 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 673,852 | 90.2% |
| Failure | 72,994 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,729 | 39.4% |
| code complex parameters | 14,058 | 19.3% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,384 | 8.7% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,168 | 3.0% |
| meth descr varargs | 1,915 | 2.6% |
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
|     deferred | 38,303,107 | 37.5% |
|          hit | 63,307,081 | 61.9% |
|         miss | 575,930 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,466 | 22.8% |
| Failure | 69,342 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,504 | 26.7% |
| other | 15,271 | 22.0% |
| different types | 12,260 | 17.7% |
| tuple | 10,052 | 14.5% |
| string | 9,960 | 14.4% |
| bool | 2,095 | 3.0% |
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
|     deferred | 103,816,272 | 79.8% |
|          hit | 25,584,691 | 19.7% |
|         miss | 639,071 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 23,955 | 21.4% |
| Failure | 87,818 | 78.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 59,634 | 67.9% |
| set | 9,029 | 10.3% |
| zip | 7,600 | 8.7% |
| enumerate | 4,235 | 4.8% |
| other | 2,720 | 3.1% |
| itertools | 1,940 | 2.2% |
| dict keys | 1,640 | 1.9% |
| reversed list | 860 | 1.0% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120,268,926 | 27.8% |
|        deopt | 20 | 0.0% |
|          hit | 245,535,535 | 56.7% |
|         miss | 65,933,953 | 15.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,321,801 | 89.2% |
| Failure | 160,272 | 10.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 60,851 | 38.0% |
| mutable class | 58,777 | 36.7% |
| method | 10,461 | 6.5% |
| has managed dict | 8,780 | 5.5% |
| overridden | 8,675 | 5.4% |
| shadowed | 5,300 | 3.3% |
| class method obj | 3,900 | 2.4% |
| builtin class method | 1,320 | 0.8% |
| not managed dict | 1,108 | 0.7% |
| non object slot | 680 | 0.4% |
| not in keys | 300 | 0.2% |
| non overriding descriptor | 60 | 0.0% |
| module attr not found | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 89,952 | 0.0% |
|          hit | 347,400,594 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,967 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 604 | 0.0% |
|          hit | 2,990,179 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 100.0% |
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
|          hit | 999,176 | 67.8% |
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
|     deferred | 540,836 | 4.2% |
|          hit | 10,201,702 | 78.4% |
|         miss | 2,217,200 | 17.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,752 | 92.3% |
| Failure | 3,908 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.2% |
| not managed dict | 1,448 | 37.1% |
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
|     deferred | 3,422,336 | 13.2% |
|          hit | 22,481,877 | 86.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,720 | 42.8% |
| Failure | 3,640 | 57.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,640 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,842,063 | 6.2% |
|          hit | 194,061,438 | 93.6% |
|         miss | 440,389 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,944 | 72.2% |
| Failure | 23,055 | 27.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,788 | 46.8% |
| number | 3,524 | 15.3% |
| mapping | 3,300 | 14.3% |
| dict | 2,340 | 10.1% |
| other | 1,627 | 7.1% |
| set | 1,436 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,720 | 0.0% |
|          hit | 102,214,218 | 100.0% |

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
| Basic | 3,005,708,150 | 54.2% |
| Not specialized | 779,169,272 | 14.0% |
| Specialized hits | 1,662,722,502 | 30.0% |
| Specialized misses | 101,321,385 | 1.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 120,268,926 | 33.0% |
| FOR_ITER | 103,816,272 | 28.5% |
| COMPARE_OP | 38,303,107 | 10.5% |
| BINARY_OP | 35,267,147 | 9.7% |
| CALL | 26,107,768 | 7.2% |
| BINARY_SUBSCR | 23,710,987 | 6.5% |
| TO_BOOL | 12,842,063 | 3.5% |
| STORE_SUBSCR | 3,422,336 | 0.9% |
| STORE_ATTR | 540,836 | 0.1% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,451,898 | 36.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,764,614 | 15.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,403,361 | 14.2% |
| LOAD_ATTR_METHOD_NO_DICT | 9,130,214 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,814,217 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,502 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,105,939 | 4.1% |
| CALL_BUILTIN_O | 2,661,211 | 2.6% |
| STORE_ATTR_SLOT | 2,216,220 | 2.2% |
| COMPARE_OP_INT | 574,330 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,586,872 | 48.8% |
| Calls to Python functions inlined | 133,958,491 | 51.2% |
| Calls via PyEval_EvalFrame (total) | 127,586,872 | 48.8% |
| Calls via PyEval_EvalFrame (vector) | 98,455,128 | 37.6% |
| Calls via PyEval_EvalFrame (generator) | 29,131,744 | 11.1% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,447,828 | 37.6% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,841 | 9.0% |
| Calls via PyEval_EvalFrame (function ex) | 11,825,244 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 53,326,529 | 20.4% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,262 | 0.5% |
| Frames pushed | 112,383,571 | 43.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,323,245 | 54.3% |
| Frees to freelist | 363,566,189 |  |
| Allocations | 305,433,142 | 45.7% |
| Allocations to 512 bytes | 304,378,839 | 45.5% |
| Allocations to 4 kbytes | 1,029,843 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,107,819 |  |
| New values | 1,057,637 |  |
| Interpreter increfs | 2,653,658,644 | 65.3% |
| Interpreter decrefs | 3,068,086,616 | 66.0% |
| Increfs | 1,412,626,672 | 34.7% |
| Decrefs | 1,578,711,471 | 34.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,344,782 |  |
| Method cache misses | 4,709,533 |  |
| Method cache collisions | 6,617,345 |  |
| Method cache dunder hits | 346,162,927 |  |
| Method cache dunder misses | 1,908,454 |  |


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
| Optimization attempts | 62,810 |  |
| Traces created | 10,011 | 15.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 117 | 0.2% |
| Trace too long | 40 | 0.1% |
| Trace too short | 52,799 | 84.1% |
| Inner loop found | 80 | 0.1% |
| Recursive call | 160 | 0.3% |
| Traces executed | 84,098,331 |  |
| Uops executed | 1,155,215,889 | 13.74 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.2% |
| <= 16 | 3,335 | 33.3% |
| <= 32 | 4,154 | 41.5% |
| <= 64 | 1,732 | 17.3% |
| <= 128 | 770 | 7.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 20 | 0.2% |
| <= 8 | 20 | 0.2% |
| <= 16 | 4,052 | 40.5% |
| <= 32 | 3,897 | 38.9% |
| <= 64 | 1,692 | 16.9% |
| <= 128 | 330 | 3.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 2,711,887 | 3.2% |
| <= 4 | 16,820 | 0.0% |
| <= 8 | 19,683,746 | 23.4% |
| <= 16 | 39,959,515 | 47.5% |
| <= 32 | 18,772,805 | 22.3% |
| <= 64 | 2,581,727 | 3.1% |
| <= 128 | 327,392 | 0.4% |
| <= 256 | 34,630 | 0.0% |
| <= 512 | 9,629 | 0.0% |
| <= 1,024 | 100 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 275,952,389 | 23.9% | 23.9% |  |
| LOAD_FAST | 107,326,703 | 9.3% | 33.2% |  |
| _POP_JUMP_IF_TRUE | 99,816,872 | 8.6% | 41.8% |  |
| _EXIT_TRACE | 77,778,689 | 6.7% | 48.6% |  |
| STORE_FAST | 69,718,550 | 6.0% | 54.6% |  |
| _ITER_CHECK_LIST | 51,768,733 | 4.5% | 59.1% | 3.4% |
| _IS_ITER_EXHAUSTED_LIST | 50,015,366 | 4.3% | 63.4% |  |
| _ITER_NEXT_LIST | 40,215,807 | 3.5% | 66.9% |  |
| _GUARD_GLOBALS_VERSION | 32,635,190 | 2.8% | 69.7% | 1.5% |
| _LOAD_GLOBAL_MODULE | 24,193,106 | 2.1% | 71.8% |  |
| _ITER_CHECK_TUPLE | 23,765,237 | 2.1% | 73.9% | 4.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 22,806,717 | 2.0% | 75.8% |  |
| POP_TOP | 19,505,862 | 1.7% | 77.5% |  |
| CONTAINS_OP | 14,171,911 | 1.2% | 78.7% |  |
| _ITER_NEXT_TUPLE | 13,938,839 | 1.2% | 80.0% |  |
| LOAD_CONST | 12,442,564 | 1.1% | 81.0% |  |
| PUSH_NULL | 11,216,265 | 1.0% | 82.0% |  |
| _ITER_CHECK_RANGE | 10,733,796 | 0.9% | 82.9% |  |
| _IS_ITER_EXHAUSTED_RANGE | 10,733,796 | 0.9% | 83.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 10,680,578 | 0.9% | 84.8% | 0.1% |
| _CHECK_PEP_523 | 10,680,578 | 0.9% | 85.7% |  |
| _CHECK_STACK_SPACE | 10,665,050 | 0.9% | 86.6% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 10,662,564 | 0.9% | 87.6% |  |
| _PUSH_FRAME | 10,662,564 | 0.9% | 88.5% |  |
| _SAVE_RETURN_OFFSET | 10,662,564 | 0.9% | 89.4% |  |
| _ITER_NEXT_RANGE | 9,906,411 | 0.9% | 90.3% |  |
| _GUARD_BOTH_INT | 9,199,871 | 0.8% | 91.1% |  |
| _BINARY_OP_ADD_INT | 9,192,431 | 0.8% | 91.8% |  |
| _GUARD_TYPE_VERSION | 9,162,131 | 0.8% | 92.6% | 32.5% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 8,974,311 | 0.8% | 93.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 8,974,311 | 0.8% | 94.2% |  |
| _GUARD_BUILTINS_VERSION | 7,942,088 | 0.7% | 94.9% |  |
| _LOAD_GLOBAL_BUILTINS | 7,942,088 | 0.7% | 95.6% |  |
| LOAD_DEREF | 6,205,666 | 0.5% | 96.1% |  |
| CALL_ISINSTANCE | 4,920,658 | 0.4% | 96.5% |  |
| _JUMP_TO_TOP | 4,734,084 | 0.4% | 96.9% |  |
| _POP_JUMP_IF_FALSE | 3,963,245 | 0.3% | 97.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,217,300 | 0.3% | 97.6% |  |
| TO_BOOL_BOOL | 2,902,246 | 0.3% | 97.8% |  |
| COMPARE_OP_INT | 2,396,324 | 0.2% | 98.0% |  |
| CALL_BUILTIN_O | 2,211,588 | 0.2% | 98.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,063,080 | 0.2% | 98.4% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,966,424 | 0.2% | 98.6% |  |
| MAKE_FUNCTION | 1,903,046 | 0.2% | 98.7% |  |
| CALL_TYPE_1 | 1,861,066 | 0.2% | 98.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 1,516,332 | 0.1% | 99.0% |  |
| _GUARD_KEYS_VERSION | 1,516,332 | 0.1% | 99.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,516,332 | 0.1% | 99.3% |  |
| RESUME_CHECK | 1,268,872 | 0.1% | 99.4% |  |
| BINARY_SUBSCR_LIST_INT | 1,184,700 | 0.1% | 99.5% | 1.6% |
| STORE_DEREF | 992,988 | 0.1% | 99.6% |  |
| TO_BOOL_INT | 632,940 | 0.1% | 99.6% | 0.0% |
| _LOAD_ATTR_SLOT | 530,584 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 520,799 | 0.0% | 99.7% |  |
| GET_ITER | 494,669 | 0.0% | 99.8% |  |
| LIST_APPEND | 445,627 | 0.0% | 99.8% |  |
| COPY | 281,600 | 0.0% | 99.8% |  |
| SWAP | 280,960 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 235,808 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 140,400 | 0.0% | 99.9% |  |
| _IS_NONE | 129,788 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,566 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,566 | 0.0% | 99.9% |  |
| LOAD_NAME | 106,000 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 98,807 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 87,930 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 80,271 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 69,420 | 0.0% | 100.0% | 0.8% |
| CALL_METHOD_DESCRIPTOR_O | 57,040 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 55,600 | 0.0% | 100.0% |  |
| BUILD_LIST | 45,840 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 45,396 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| STORE_NAME | 35,420 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,731 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 29,700 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,580 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,320 | 0.0% | 100.0% |  |
| BUILD_MAP | 11,552 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 10,640 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 10,640 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 8,080 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 6,880 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 6,000 | 0.0% | 100.0% |  |
| _POP_FRAME | 5,580 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 2,260 | 0.0% | 100.0% |  |
| DICT_MERGE | 2,020 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,920 | 0.0% | 100.0% |  |
| CALL_LEN | 1,800 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 1,500 | 0.0% | 100.0% |  |
| STORE_SLICE | 1,220 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,220 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 560 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 480 | 0.0% | 100.0% | 100.0% |
| CALL_TUPLE_1 | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 240 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 160 | 0.0% | 100.0% |  |
| IS_OP | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 51,679 |
| LOAD_ATTR_PROPERTY | 2,615 |
| LOAD_ATTR | 1,520 |
| FOR_ITER_GEN | 1,140 |
| YIELD_VALUE | 780 |
| CALL | 497 |
| CALL_LIST_APPEND | 400 |
| CALL_PY_WITH_DEFAULTS | 400 |
| CALL_KW | 320 |
| BINARY_SUBSCR | 260 |
| BINARY_OP | 260 |
| BINARY_SUBSCR_GETITEM | 240 |
| CALL_FUNCTION_EX | 100 |
| TO_BOOL | 60 |
| STORE_SUBSCR | 20 |
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
Stats gathered on: 2023-11-03
