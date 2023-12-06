
# Pystats results

- benchmark: mypy2
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,930,501,449 | 20.7% | 20.7% |  |
| LOAD_CONST | 699,999,426 | 4.9% | 25.7% |  |
| RESUME_CHECK | 690,983,905 | 4.9% | 30.5% | 0.0% |
| STORE_ATTR_SLOT | 611,857,276 | 4.3% | 34.9% | 21.5% |
| LOAD_GLOBAL_MODULE | 611,343,790 | 4.3% | 39.2% | 0.0% |
| LOAD_FAST_LOAD_FAST | 568,009,293 | 4.0% | 43.2% |  |
| LOAD_GLOBAL_BUILTIN | 547,585,216 | 3.9% | 47.1% | 0.0% |
| POP_JUMP_IF_FALSE | 542,992,402 | 3.8% | 50.9% |  |
| STORE_FAST | 497,024,614 | 3.5% | 54.4% |  |
| LOAD_ATTR_SLOT | 495,303,816 | 3.5% | 57.9% | 1.7% |
| CALL_PY_EXACT_ARGS | 435,334,444 | 3.1% | 61.0% | 10.2% |
| TO_BOOL_BOOL | 413,508,940 | 2.9% | 63.9% | 0.0% |
| RETURN_VALUE | 396,196,418 | 2.8% | 66.7% |  |
| RETURN_CONST | 299,998,108 | 2.1% | 68.8% |  |
| CALL_ISINSTANCE | 276,574,684 | 2.0% | 70.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 263,605,014 | 1.9% | 72.7% | 21.7% |
| POP_JUMP_IF_TRUE | 222,212,795 | 1.6% | 74.2% |  |
| POP_TOP | 220,736,208 | 1.6% | 75.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 154,937,161 | 1.1% | 76.9% | 3.6% |
| LOAD_DEREF | 129,908,019 | 0.9% | 77.8% |  |
| GET_ITER | 121,169,088 | 0.9% | 78.7% |  |
| INTERPRETER_EXIT | 120,914,893 | 0.9% | 79.5% |  |
| BINARY_SUBSCR_DICT | 118,591,325 | 0.8% | 80.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 114,239,492 | 0.8% | 81.2% | 12.8% |
| LOAD_ATTR | 114,188,020 | 0.8% | 82.0% |  |
| ENTER_EXECUTOR | 100,905,492 | 0.7% | 82.7% |  |
| POP_JUMP_IF_NOT_NONE | 96,527,620 | 0.7% | 83.4% |  |
| CONTAINS_OP | 94,565,350 | 0.7% | 84.0% |  |
| COPY_FREE_VARS | 93,983,960 | 0.7% | 84.7% |  |
| SWAP | 87,636,000 | 0.6% | 85.3% |  |
| LOAD_SUPER_ATTR_METHOD | 86,018,960 | 0.6% | 85.9% |  |
| BUILD_LIST | 82,656,172 | 0.6% | 86.5% |  |
| POP_JUMP_IF_NONE | 80,397,800 | 0.6% | 87.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 77,998,020 | 0.6% | 87.6% | 2.2% |
| CALL_KW | 76,507,100 | 0.5% | 88.2% |  |
| FOR_ITER_LIST | 75,252,738 | 0.5% | 88.7% | 2.4% |
| CALL | 68,548,400 | 0.5% | 89.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 63,601,887 | 0.4% | 89.6% | 8.7% |
| IS_OP | 56,782,240 | 0.4% | 90.0% |  |
| NOP | 53,211,360 | 0.4% | 90.4% |  |
| COPY | 50,784,902 | 0.4% | 90.8% |  |
| JUMP_FORWARD | 47,248,209 | 0.3% | 91.1% |  |
| COMPARE_OP_STR | 46,659,187 | 0.3% | 91.4% | 0.3% |
| TO_BOOL_LIST | 45,694,120 | 0.3% | 91.8% | 0.7% |
| COMPARE_OP | 42,974,580 | 0.3% | 92.1% |  |
| CALL_BUILTIN_CLASS | 40,326,772 | 0.3% | 92.3% |  |
| BINARY_SUBSCR | 40,299,995 | 0.3% | 92.6% |  |
| COMPARE_OP_INT | 38,291,681 | 0.3% | 92.9% | 1.9% |
| FOR_ITER | 37,929,974 | 0.3% | 93.2% |  |
| CALL_LEN | 35,575,980 | 0.3% | 93.4% |  |
| PUSH_NULL | 35,022,938 | 0.2% | 93.7% |  |
| EXTENDED_ARG | 33,265,960 | 0.2% | 93.9% |  |
| MAKE_CELL | 33,241,200 | 0.2% | 94.1% |  |
| STORE_FAST_STORE_FAST | 33,049,300 | 0.2% | 94.4% |  |
| CALL_LIST_APPEND | 32,144,080 | 0.2% | 94.6% |  |
| TO_BOOL_NONE | 32,071,646 | 0.2% | 94.8% | 8.3% |
| BUILD_TUPLE | 31,992,531 | 0.2% | 95.1% |  |
| LOAD_ATTR_WITH_HINT | 30,842,980 | 0.2% | 95.3% | 2.1% |
| MAP_ADD | 30,828,320 | 0.2% | 95.5% |  |
| TO_BOOL_ALWAYS_TRUE | 29,217,834 | 0.2% | 95.7% | 13.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 28,665,300 | 0.2% | 95.9% | 28.3% |
| LOAD_FAST_AND_CLEAR | 27,827,140 | 0.2% | 96.1% |  |
| LOAD_ATTR_PROPERTY | 27,342,578 | 0.2% | 96.3% | 6.6% |
| LOAD_ATTR_MODULE | 26,209,146 | 0.2% | 96.5% | 0.0% |
| UNARY_NOT | 26,161,500 | 0.2% | 96.7% |  |
| LIST_APPEND | 25,417,570 | 0.2% | 96.8% |  |
| FOR_ITER_TUPLE | 23,194,672 | 0.2% | 97.0% | 7.5% |
| JUMP_BACKWARD | 21,566,880 | 0.2% | 97.2% |  |
| CALL_PY_WITH_DEFAULTS | 20,721,240 | 0.1% | 97.3% | 2.1% |
| TO_BOOL | 20,382,680 | 0.1% | 97.4% |  |
| CALL_TUPLE_1 | 20,335,416 | 0.1% | 97.6% |  |
| BINARY_SUBSCR_LIST_INT | 19,176,340 | 0.1% | 97.7% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 16,806,160 | 0.1% | 97.8% |  |
| CALL_BUILTIN_O | 15,814,764 | 0.1% | 98.0% | 8.4% |
| LOAD_ATTR_CLASS | 14,897,740 | 0.1% | 98.1% | 2.4% |
| UNPACK_SEQUENCE_LIST | 14,624,900 | 0.1% | 98.2% |  |
| CALL_BUILTIN_FAST | 14,038,098 | 0.1% | 98.3% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 12,102,247 | 0.1% | 98.3% | 0.0% |
| STORE_ATTR | 11,621,400 | 0.1% | 98.4% |  |
| DELETE_ATTR | 11,254,400 | 0.1% | 98.5% |  |
| YIELD_VALUE | 11,212,372 | 0.1% | 98.6% |  |
| CALL_TYPE_1 | 11,112,040 | 0.1% | 98.7% |  |
| BUILD_MAP | 11,095,980 | 0.1% | 98.7% |  |
| TO_BOOL_STR | 9,264,580 | 0.1% | 98.8% | 3.9% |
| STORE_FAST_LOAD_FAST | 8,708,368 | 0.1% | 98.9% |  |
| MAKE_FUNCTION | 8,288,960 | 0.1% | 98.9% |  |
| CALL_FUNCTION_EX | 7,966,320 | 0.1% | 99.0% |  |
| RETURN_GENERATOR | 7,785,480 | 0.1% | 99.0% |  |
| BINARY_OP_ADD_INT | 7,601,338 | 0.1% | 99.1% | 0.8% |
| FOR_ITER_RANGE | 6,868,260 | 0.0% | 99.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 6,667,940 | 0.0% | 99.2% | 0.1% |
| BINARY_OP_ADD_UNICODE | 6,661,360 | 0.0% | 99.2% |  |
| EXIT_INIT_CHECK | 6,658,880 | 0.0% | 99.3% |  |
| BINARY_SLICE | 6,272,000 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 5,226,980 | 0.0% | 99.4% |  |
| STORE_SUBSCR_DICT | 4,968,198 | 0.0% | 99.4% |  |
| BINARY_OP | 4,841,400 | 0.0% | 99.4% |  |
| STORE_DEREF | 4,722,240 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 4,152,160 | 0.0% | 99.5% |  |
| POP_EXCEPT | 4,152,160 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 4,152,160 | 0.0% | 99.6% |  |
| DICT_MERGE | 3,864,720 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,793,020 | 0.0% | 99.6% | 0.0% |
| STORE_SUBSCR | 3,770,760 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 3,754,724 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,135,500 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,030,140 | 0.0% | 99.7% | 11.0% |
| LOAD_FAST_CHECK | 2,822,800 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_GETITEM | 2,792,220 | 0.0% | 99.7% | 0.0% |
| FORMAT_SIMPLE | 2,792,080 | 0.0% | 99.8% |  |
| BEFORE_WITH | 2,676,160 | 0.0% | 99.8% |  |
| IMPORT_FROM | 2,427,840 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 2,005,600 | 0.0% | 99.8% |  |
| IMPORT_NAME | 1,983,200 | 0.0% | 99.8% |  |
| UNARY_NEGATIVE | 1,949,600 | 0.0% | 99.8% |  |
| TO_BOOL_INT | 1,883,385 | 0.0% | 99.9% | 4.5% |
| BUILD_STRING | 1,882,100 | 0.0% | 99.9% |  |
| BUILD_SET | 1,879,100 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,666,240 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,643,940 | 0.0% | 99.9% | 3.1% |
| SET_ADD | 1,433,100 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 1,327,900 | 0.0% | 99.9% |  |
| CALL_STR_1 | 1,219,340 | 0.0% | 99.9% |  |
| LOAD_SUPER_ATTR_ATTR | 1,083,160 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,076,040 | 0.0% | 100.0% | 1.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,069,720 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 943,620 | 0.0% | 100.0% | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 573,120 | 0.0% | 100.0% |  |
| RERAISE | 543,680 | 0.0% | 100.0% |  |
| SEND_GEN | 464,132 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 433,000 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 368,192 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 339,600 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 293,220 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 287,820 | 0.0% | 100.0% | 22.1% |
| LOAD_GLOBAL | 242,840 | 0.0% | 100.0% |  |
| DELETE_FAST | 201,920 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 193,100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 150,540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 137,997 | 0.0% | 100.0% |  |
| END_SEND | 96,000 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 96,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 75,880 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 67,960 | 0.0% | 100.0% |  |
| END_FOR | 54,080 | 0.0% | 100.0% |  |
| RESUME | 40,880 | 0.0% | 100.0% | 0.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 32,920 | 0.0% | 100.0% |  |
| BUILD_SLICE | 18,360 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 6,120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 5,480 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 4,820 | 0.0% | 100.0% |  |
| STORE_NAME | 2,240 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,100 | 0.0% | 100.0% |  |
| UNARY_INVERT | 1,540 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 1,260 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,220 | 0.0% | 100.0% |  |
| STORE_SLICE | 960 | 0.0% | 100.0% |  |
| UNPACK_EX | 960 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 520 | 0.0% | 100.0% |  |
| SET_UPDATE | 320 | 0.0% | 100.0% |  |
| SEND | 120 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 80 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 437,050,943 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 380,286,060 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 377,583,407 | 2.7% | 8.4% |
| LOAD_FAST STORE_ATTR_SLOT | 359,762,012 | 2.5% | 11.0% |
| RESUME_CHECK LOAD_FAST | 302,339,263 | 2.1% | 13.1% |
| LOAD_CONST LOAD_FAST | 282,012,212 | 2.0% | 15.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 279,294,674 | 2.0% | 17.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 271,727,218 | 1.9% | 19.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 270,272,736 | 1.9% | 20.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 253,394,799 | 1.8% | 22.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 248,651,120 | 1.8% | 24.5% |
| STORE_FAST LOAD_FAST | 244,623,754 | 1.7% | 26.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 234,111,658 | 1.7% | 27.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 190,251,775 | 1.3% | 29.2% |
| STORE_ATTR_SLOT LOAD_CONST | 170,370,120 | 1.2% | 30.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 168,213,890 | 1.2% | 31.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 162,543,071 | 1.1% | 32.7% |
| LOAD_FAST LOAD_CONST | 158,776,938 | 1.1% | 33.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 141,091,360 | 1.0% | 34.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 133,079,901 | 0.9% | 35.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 124,832,335 | 0.9% | 36.7% |
| STORE_ATTR_SLOT RETURN_CONST | 120,940,980 | 0.9% | 37.5% |
| LOAD_FAST RETURN_VALUE | 118,425,976 | 0.8% | 38.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 117,245,781 | 0.8% | 39.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 116,716,652 | 0.8% | 40.0% |
| STORE_ATTR_SLOT LOAD_FAST | 112,444,672 | 0.8% | 40.8% |
| RETURN_CONST POP_TOP | 105,748,220 | 0.7% | 41.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 102,836,860 | 0.7% | 42.3% |
| LOAD_CONST BINARY_SUBSCR_DICT | 102,017,160 | 0.7% | 43.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 100,955,566 | 0.7% | 43.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 97,899,456 | 0.7% | 44.4% |
| POP_TOP LOAD_FAST | 93,771,048 | 0.7% | 45.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 93,321,931 | 0.7% | 45.7% |
| COPY_FREE_VARS RESUME_CHECK | 93,013,740 | 0.7% | 46.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 92,064,020 | 0.7% | 47.1% |
| RETURN_VALUE STORE_FAST | 90,165,120 | 0.6% | 47.7% |
| LOAD_DEREF LOAD_FAST | 88,336,196 | 0.6% | 48.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 86,016,560 | 0.6% | 48.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 84,689,680 | 0.6% | 49.5% |
| RETURN_VALUE RETURN_VALUE | 80,685,457 | 0.6% | 50.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 79,664,700 | 0.6% | 50.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 79,465,387 | 0.6% | 51.2% |
| LOAD_FAST LOAD_FAST | 77,118,786 | 0.5% | 51.8% |
| LOAD_CONST CALL_KW | 75,015,180 | 0.5% | 52.3% |
| LOAD_FAST LOAD_ATTR | 74,703,760 | 0.5% | 52.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 74,527,956 | 0.5% | 53.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 73,167,146 | 0.5% | 53.9% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 71,619,900 | 0.5% | 54.4% |
| CACHE RESUME_CHECK | 69,740,053 | 0.5% | 54.9% |
| RESUME_CHECK RETURN_CONST | 67,669,080 | 0.5% | 55.3% |
| RETURN_CONST INTERPRETER_EXIT | 61,992,140 | 0.4% | 55.8% |
| RETURN_CONST LOAD_FAST | 61,621,760 | 0.4% | 56.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 60,538,680 | 0.4% | 56.6% |
| LOAD_ATTR_SLOT LOAD_FAST | 59,944,608 | 0.4% | 57.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 59,040,820 | 0.4% | 57.5% |
| LOAD_CONST LOAD_CONST | 53,901,300 | 0.4% | 57.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 53,242,080 | 0.4% | 58.2% |
| LOAD_ATTR LOAD_FAST | 52,302,020 | 0.4% | 58.6% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 52,266,804 | 0.4% | 59.0% |
| RETURN_VALUE LOAD_FAST | 50,110,880 | 0.4% | 59.3% |
| FOR_ITER_LIST STORE_FAST | 49,593,004 | 0.4% | 59.7% |
| RETURN_VALUE INTERPRETER_EXIT | 49,258,953 | 0.3% | 60.0% |
| LOAD_ATTR_SLOT GET_ITER | 47,884,688 | 0.3% | 60.4% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 47,449,860 | 0.3% | 60.7% |
| LOAD_FAST CONTAINS_OP | 46,965,552 | 0.3% | 61.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 46,231,020 | 0.3% | 61.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 46,138,140 | 0.3% | 61.7% |
| LOAD_ATTR_SLOT STORE_FAST | 45,448,160 | 0.3% | 62.0% |
| GET_ITER FOR_ITER_LIST | 45,018,695 | 0.3% | 62.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 44,207,480 | 0.3% | 62.6% |
| CACHE COPY_FREE_VARS | 43,492,280 | 0.3% | 63.0% |
| CALL_KW RESUME_CHECK | 43,426,700 | 0.3% | 63.3% |
| RETURN_CONST RETURN_VALUE | 42,797,460 | 0.3% | 63.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 42,018,984 | 0.3% | 63.9% |
| LOAD_GLOBAL_MODULE IS_OP | 41,593,840 | 0.3% | 64.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 39,638,500 | 0.3% | 64.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 39,416,023 | 0.3% | 64.7% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 39,249,320 | 0.3% | 65.0% |
| COPY TO_BOOL_BOOL | 38,522,624 | 0.3% | 65.3% |
| POP_JUMP_IF_NONE LOAD_FAST | 38,372,120 | 0.3% | 65.5% |
| IS_OP POP_JUMP_IF_FALSE | 38,094,720 | 0.3% | 65.8% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 36,967,860 | 0.3% | 66.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 36,617,660 | 0.3% | 66.3% |
| LOAD_ATTR_SLOT RETURN_VALUE | 36,493,151 | 0.3% | 66.6% |
| POP_TOP LOAD_FAST_LOAD_FAST | 35,282,040 | 0.2% | 66.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 34,753,260 | 0.2% | 67.1% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 34,742,280 | 0.2% | 67.3% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 34,705,787 | 0.2% | 67.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 34,702,420 | 0.2% | 67.8% |
| LOAD_FAST TO_BOOL_LIST | 34,675,660 | 0.2% | 68.1% |
| RETURN_VALUE POP_TOP | 34,488,960 | 0.2% | 68.3% |
| LOAD_FAST TO_BOOL_BOOL | 34,233,660 | 0.2% | 68.5% |
| LOAD_CONST COMPARE_OP_STR | 34,214,048 | 0.2% | 68.8% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 32,524,220 | 0.2% | 69.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 32,504,500 | 0.2% | 69.2% |
| BUILD_LIST STORE_FAST | 31,852,012 | 0.2% | 69.5% |
| STORE_ATTR_SLOT LOAD_GLOBAL_BUILTIN | 31,685,060 | 0.2% | 69.7% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 30,484,320 | 0.2% | 69.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 30,348,740 | 0.2% | 70.1% |
| COMPARE_OP_STR POP_JUMP_IF_TRUE | 30,082,356 | 0.2% | 70.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,869,720 | 77.6% |
| BINARY_OP_SUBTRACT_INT | 890,220 | 14.2% |
| LOAD_FAST | 377,500 | 6.0% |
| BINARY_OP_ADD_INT | 101,380 | 1.6% |
| LOAD_ATTR_SLOT | 23,980 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,339,560 | 37.3% |
| CALL_PY_EXACT_ARGS | 890,980 | 14.2% |
| STORE_FAST | 700,940 | 11.2% |
| GET_ITER | 646,720 | 10.3% |
| BINARY_OP_ADD_UNICODE | 450,740 | 7.2% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 69,740,053 | 57.7% |
| COPY_FREE_VARS | 43,492,280 | 36.0% |
| POP_TOP | 7,592,620 | 6.3% |
| RETURN_GENERATOR | 93,440 | 0.1% |
| PUSH_EXC_INFO | 42,880 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,594,680 | 97.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 48,040 | 1.8% |
| CALL | 33,300 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,381,300 | 89.0% |
| STORE_FAST | 294,860 | 11.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 329,000 | 57.4% |
| RETURN_VALUE | 197,040 | 34.4% |
| BUILD_STRING | 44,360 | 7.7% |
| LOAD_FAST_LOAD_FAST | 1,880 | 0.3% |
| BINARY_SUBSCR_STR_INT | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 524,520 | 91.5% |
| LOAD_FAST | 46,400 | 8.1% |
| JUMP_FORWARD | 1,260 | 0.2% |
| LOAD_FAST_LOAD_FAST | 940 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,881,829 | 49.3% |
| LOAD_FAST_LOAD_FAST | 15,020,680 | 37.3% |
| LOAD_FAST | 3,486,580 | 8.7% |
| LOAD_GLOBAL_MODULE | 1,199,040 | 3.0% |
| COPY | 287,400 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,157,760 | 42.6% |
| CONTAINS_OP | 4,464,740 | 11.1% |
| LOAD_CONST | 4,336,060 | 10.8% |
| LOAD_FAST | 3,199,660 | 7.9% |
| RETURN_VALUE | 2,830,040 | 7.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,134,280 | 99.6% |
| BUILD_TUPLE | 16,640 | 0.4% |
| LOAD_GLOBAL_MODULE | 900 | 0.0% |
| LOAD_GLOBAL | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,152,160 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,180 | 56.9% |
| BUILD_SLICE | 17,280 | 22.8% |
| LOAD_FAST | 12,540 | 16.5% |
| LOAD_FAST_LOAD_FAST | 2,880 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 44,460 | 58.6% |
| LOAD_DEREF | 17,280 | 22.8% |
| JUMP_BACKWARD | 11,200 | 14.8% |
| RETURN_CONST | 1,920 | 2.5% |
| LOAD_FAST | 640 | 0.8% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 54,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 50,560 | 93.5% |
| LOAD_FAST | 2,880 | 5.3% |
| EXTENDED_ARG | 320 | 0.6% |
| JUMP_BACKWARD | 320 | 0.6% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 96,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 96,000 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,658,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,658,880 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,020 | 70.4% |
| RETURN_VALUE | 413,360 | 14.8% |
| BINARY_SUBSCR_TUPLE_INT | 281,600 | 10.1% |
| CONVERT_VALUE | 67,960 | 2.4% |
| LOAD_ATTR_SLOT | 38,660 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,801,380 | 64.5% |
| BUILD_STRING | 990,700 | 35.5% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900 | 73.8% |
| LOAD_CONST | 320 | 26.2% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 47,884,688 | 39.5% |
| LOAD_FAST | 28,902,340 | 23.9% |
| CALL_BUILTIN_CLASS | 19,018,300 | 15.7% |
| BINARY_SUBSCR_DICT | 12,484,600 | 10.3% |
| CALL | 2,651,080 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 45,018,695 | 37.2% |
| LOAD_FAST_AND_CLEAR | 26,579,700 | 21.9% |
| FOR_ITER_TUPLE | 19,154,519 | 15.8% |
| FOR_ITER | 14,578,934 | 12.0% |
| FOR_ITER_RANGE | 5,952,920 | 4.9% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 96,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 96,000 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 61,992,140 | 51.3% |
| RETURN_VALUE | 49,258,953 | 40.7% |
| YIELD_VALUE | 9,570,360 | 7.9% |
| RETURN_GENERATOR | 93,440 | 0.1% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20 | 50.0% |
| STORE_NAME | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,288,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,158,480 | 50.2% |
| SET_FUNCTION_ATTRIBUTE | 4,055,440 | 48.9% |
| LOAD_CONST | 48,060 | 0.6% |
| LOAD_GLOBAL_MODULE | 14,280 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 7,240 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,134,500 | 28.4% |
| POP_JUMP_IF_TRUE | 14,082,560 | 26.5% |
| POP_JUMP_IF_FALSE | 9,167,760 | 17.2% |
| RESUME_CHECK | 6,444,800 | 12.1% |
| CALL_LIST_APPEND | 2,435,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,965,380 | 56.3% |
| LOAD_CONST | 14,777,960 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 4,745,120 | 8.9% |
| LOAD_GLOBAL_MODULE | 3,046,140 | 5.7% |
| LOAD_FAST_LOAD_FAST | 555,500 | 1.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,612,660 | 62.9% |
| SWAP | 1,267,840 | 30.5% |
| COPY | 256,640 | 6.2% |
| STORE_FAST | 13,880 | 0.3% |
| POP_JUMP_IF_FALSE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,611,700 | 62.9% |
| RETURN_VALUE | 1,267,840 | 30.5% |
| RERAISE | 256,640 | 6.2% |
| ENTER_EXECUTOR | 13,440 | 0.3% |
| JUMP_BACKWARD | 1,080 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 105,748,220 | 47.9% |
| RETURN_VALUE | 34,488,960 | 15.6% |
| POP_JUMP_IF_FALSE | 20,664,181 | 9.4% |
| POP_JUMP_IF_TRUE | 17,346,956 | 7.9% |
| RESUME_CHECK | 7,991,480 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,771,048 | 42.5% |
| LOAD_FAST_LOAD_FAST | 35,282,040 | 16.0% |
| ENTER_EXECUTOR | 25,734,007 | 11.7% |
| RETURN_CONST | 23,000,420 | 10.4% |
| LOAD_CONST | 8,837,200 | 4.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 2,282,200 | 55.0% |
| LOAD_ATTR_SLOT | 1,263,960 | 30.4% |
| RERAISE | 213,440 | 5.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 200,400 | 4.8% |
| RAISE_VARARGS | 125,760 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,150,580 | 100.0% |
| LOAD_GLOBAL_MODULE | 840 | 0.0% |
| LOAD_GLOBAL | 740 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,932,958 | 51.2% |
| LOAD_ATTR | 8,407,160 | 24.0% |
| LOAD_ATTR_MODULE | 4,889,780 | 14.0% |
| BINARY_SUBSCR_DICT | 1,481,440 | 4.2% |
| LOAD_SUPER_ATTR_ATTR | 1,077,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,224,798 | 80.6% |
| LOAD_FAST_LOAD_FAST | 5,618,400 | 16.0% |
| CALL | 569,660 | 1.6% |
| LOAD_CONST | 283,100 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 187,540 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,222,940 | 54.2% |
| CALL_FUNCTION_EX | 2,281,920 | 29.3% |
| COPY_FREE_VARS | 967,140 | 12.4% |
| ENTER_EXECUTOR | 215,300 | 2.8% |
| CACHE | 93,440 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 4,748,320 | 61.0% |
| LOAD_FAST | 2,327,360 | 29.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 385,440 | 5.0% |
| GET_YIELD_FROM_ITER | 96,000 | 1.2% |
| CALL | 94,440 | 1.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 118,425,976 | 29.9% |
| RETURN_VALUE | 80,685,457 | 20.4% |
| RETURN_CONST | 42,797,460 | 10.8% |
| LOAD_ATTR_SLOT | 36,493,151 | 9.2% |
| CALL | 12,594,440 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 90,165,120 | 22.8% |
| RETURN_VALUE | 80,685,457 | 20.4% |
| LOAD_FAST | 50,110,880 | 12.6% |
| INTERPRETER_EXIT | 49,258,953 | 12.4% |
| POP_TOP | 34,488,960 | 8.7% |


</details>

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 40 | 50.0% |
| RESUME | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 50.0% |
| LOAD_NAME | 40 | 50.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,032,460 | 80.4% |
| LOAD_FAST | 346,800 | 9.2% |
| SWAP | 287,400 | 7.6% |
| LOAD_CONST | 79,980 | 2.1% |
| LOAD_ATTR_SLOT | 17,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,032,100 | 80.4% |
| LOAD_CONST | 343,480 | 9.1% |
| LOAD_FAST | 240,600 | 6.4% |
| RETURN_CONST | 149,180 | 4.0% |
| STORE_SUBSCR | 2,360 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 9,397,760 | 46.1% |
| LOAD_FAST | 6,940,560 | 34.1% |
| LOAD_ATTR_SLOT | 2,685,160 | 13.2% |
| COPY | 1,088,700 | 5.3% |
| LOAD_ATTR_WITH_HINT | 73,100 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,053,900 | 83.7% |
| POP_JUMP_IF_TRUE | 2,878,160 | 14.1% |
| UNARY_NOT | 294,700 | 1.4% |
| TO_BOOL_BOOL | 48,620 | 0.2% |
| TO_BOOL | 43,860 | 0.2% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,320 | 85.7% |
| LOAD_FAST | 220 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,540 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,008,800 | 51.7% |
| CALL_LEN | 890,520 | 45.7% |
| LOAD_GLOBAL_MODULE | 23,660 | 1.2% |
| CALL | 17,320 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 9,260 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 890,240 | 45.7% |
| COMPARE_OP_INT | 890,200 | 45.7% |
| CALL_PY_EXACT_ARGS | 86,360 | 4.4% |
| RETURN_VALUE | 26,560 | 1.4% |
| BUILD_TUPLE | 23,680 | 1.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 22,824,800 | 87.2% |
| TO_BOOL_LIST | 2,525,220 | 9.7% |
| TO_BOOL_STR | 369,580 | 1.4% |
| TO_BOOL | 294,700 | 1.1% |
| TO_BOOL_INT | 139,280 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,688,600 | 52.3% |
| RETURN_VALUE | 9,197,440 | 35.2% |
| COPY | 2,570,320 | 9.8% |
| LOAD_FAST | 456,960 | 1.7% |
| STORE_FAST | 152,320 | 0.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 2,644,140 | 54.6% |
| LOAD_FAST | 483,760 | 10.0% |
| BUILD_LIST | 374,160 | 7.7% |
| STORE_FAST | 346,600 | 7.2% |
| LOAD_CONST | 244,080 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,900,760 | 39.3% |
| STORE_FAST | 1,219,440 | 25.2% |
| CALL_PY_EXACT_ARGS | 507,920 | 10.5% |
| LOAD_CONST | 288,380 | 6.0% |
| GET_ITER | 210,600 | 4.3% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 61.5% |
| STORE_FAST | 140 | 26.9% |
| RETURN_VALUE | 60 | 11.5% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 24,178,240 | 29.3% |
| STORE_FAST | 18,491,560 | 22.4% |
| LOAD_GLOBAL_MODULE | 10,894,180 | 13.2% |
| RESUME_CHECK | 8,677,460 | 10.5% |
| STORE_ATTR_SLOT | 4,211,900 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,852,012 | 38.5% |
| SWAP | 24,178,240 | 29.3% |
| CALL | 11,264,080 | 13.6% |
| LOAD_FAST | 8,091,560 | 9.8% |
| LOAD_GLOBAL_BUILTIN | 2,538,120 | 3.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,105,940 | 37.0% |
| LOAD_CONST | 1,666,280 | 15.0% |
| STORE_ATTR_INSTANCE_VALUE | 960,220 | 8.7% |
| RESUME_CHECK | 929,000 | 8.4% |
| POP_JUMP_IF_FALSE | 796,480 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,354,680 | 57.3% |
| LOAD_CONST | 1,611,560 | 14.5% |
| STORE_FAST | 1,507,500 | 13.6% |
| SWAP | 654,200 | 5.9% |
| RETURN_VALUE | 271,360 | 2.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,747,260 | 93.0% |
| LOAD_CONST | 109,760 | 5.8% |
| LOAD_FAST | 21,760 | 1.2% |
| POP_JUMP_IF_FALSE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,747,260 | 93.0% |
| STORE_FAST | 64,320 | 3.4% |
| CALL_PY_EXACT_ARGS | 45,400 | 2.4% |
| BINARY_OP | 11,200 | 0.6% |
| LOAD_CONST | 10,880 | 0.6% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 17,280 | 94.1% |
| BINARY_SUBSCR | 1,080 | 5.9% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 990,700 | 52.6% |
| LOAD_CONST | 891,400 | 47.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 510,700 | 27.1% |
| STORE_FAST | 478,140 | 25.4% |
| RETURN_VALUE | 376,640 | 20.0% |
| LOAD_FAST | 167,520 | 8.9% |
| CALL_PY_EXACT_ARGS | 85,400 | 4.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,103,283 | 34.7% |
| LOAD_GLOBAL_MODULE | 5,216,700 | 16.3% |
| LOAD_ATTR_SLOT | 5,109,452 | 16.0% |
| LOAD_FAST_LOAD_FAST | 4,347,800 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,366,980 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,312,260 | 26.0% |
| CALL_BUILTIN_O | 5,669,948 | 17.7% |
| CALL_ISINSTANCE | 4,530,100 | 14.2% |
| LOAD_CONST | 4,057,040 | 12.7% |
| LOAD_FAST | 3,557,320 | 11.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,581,069 | 18.4% |
| BUILD_LIST | 11,264,080 | 16.4% |
| LOAD_FAST_LOAD_FAST | 6,961,840 | 10.2% |
| ENTER_EXECUTOR | 6,629,335 | 9.7% |
| RETURN_VALUE | 5,677,254 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 27,175,220 | 39.6% |
| RETURN_VALUE | 12,594,440 | 18.4% |
| LIST_APPEND | 7,028,600 | 10.3% |
| RESUME_CHECK | 4,504,360 | 6.6% |
| TO_BOOL_BOOL | 3,682,780 | 5.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 3,864,720 | 48.5% |
| LOAD_FAST | 2,043,280 | 25.6% |
| MAP_ADD | 1,611,200 | 20.2% |
| LOAD_ATTR | 275,200 | 3.5% |
| CALL_INTRINSIC_1 | 144,720 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,034,260 | 50.6% |
| RETURN_GENERATOR | 2,281,920 | 28.6% |
| POP_TOP | 1,082,880 | 13.6% |
| STORE_FAST | 369,280 | 4.6% |
| RESUME_CHECK | 141,800 | 1.8% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 150,220 | 77.8% |
| RERAISE | 42,880 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 144,720 | 74.9% |
| RERAISE | 42,880 | 22.2% |
| BUILD_MAP | 5,500 | 2.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 75,015,180 | 98.0% |
| ENTER_EXECUTOR | 1,491,920 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 43,426,700 | 56.8% |
| UNPACK_SEQUENCE_LIST | 14,181,920 | 18.5% |
| RETURN_VALUE | 5,415,940 | 7.1% |
| MAKE_CELL | 4,870,760 | 6.4% |
| CALL_PY_EXACT_ARGS | 3,752,480 | 4.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 18,252,671 | 42.5% |
| LOAD_GLOBAL_MODULE | 8,646,720 | 20.1% |
| LOAD_CONST | 7,831,335 | 18.2% |
| LOAD_ATTR_MODULE | 3,251,980 | 7.6% |
| LOAD_FAST | 2,161,100 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 16,886,824 | 39.3% |
| POP_JUMP_IF_FALSE | 13,587,615 | 31.6% |
| RETURN_VALUE | 8,404,909 | 19.6% |
| POP_JUMP_IF_TRUE | 2,802,640 | 6.5% |
| EXTENDED_ARG | 1,029,600 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,965,552 | 49.7% |
| LOAD_FAST_LOAD_FAST | 18,216,338 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 7,852,326 | 8.3% |
| LOAD_ATTR_SLOT | 4,855,105 | 5.1% |
| BINARY_SUBSCR | 4,464,740 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 79,465,387 | 84.0% |
| POP_JUMP_IF_TRUE | 11,402,523 | 12.1% |
| RETURN_VALUE | 2,852,620 | 3.0% |
| EXTENDED_ARG | 467,800 | 0.5% |
| COPY | 223,360 | 0.2% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,260 | 99.0% |
| RETURN_CONST | 640 | 0.9% |
| LOAD_GLOBAL_MODULE | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 67,960 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 16,886,824 | 33.3% |
| LOAD_FAST | 6,215,560 | 12.2% |
| CALL_ISINSTANCE | 4,261,560 | 8.4% |
| SWAP | 3,583,620 | 7.1% |
| COMPARE_OP_STR | 3,095,592 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 38,522,624 | 75.9% |
| COMPARE_OP_INT | 3,580,400 | 7.1% |
| TO_BOOL_NONE | 1,795,240 | 3.5% |
| TO_BOOL_STR | 1,506,760 | 3.0% |
| TO_BOOL | 1,088,700 | 2.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 47,449,860 | 50.5% |
| CACHE | 43,492,280 | 46.3% |
| CALL | 1,923,440 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 450,680 | 0.5% |
| CALL_KW | 424,320 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,013,740 | 99.0% |
| RETURN_GENERATOR | 967,140 | 1.0% |
| RESUME | 3,080 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,254,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,804,160 | 78.2% |
| NOP | 2,281,920 | 20.3% |
| RETURN_CONST | 168,320 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 201,280 | 99.7% |
| ENTER_EXECUTOR | 320 | 0.2% |
| JUMP_BACKWARD | 320 | 0.2% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,864,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,864,720 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,535,512 | 26.3% |
| POP_TOP | 25,734,007 | 25.5% |
| LIST_APPEND | 25,300,050 | 25.1% |
| CALL_LIST_APPEND | 8,856,700 | 8.8% |
| EXTENDED_ARG | 4,444,440 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,404,365 | 28.1% |
| RETURN_CONST | 12,519,851 | 12.4% |
| SWAP | 11,106,410 | 11.0% |
| LOAD_ATTR_METHOD_NO_DICT | 8,097,423 | 8.0% |
| CALL | 6,629,335 | 6.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,433,260 | 31.4% |
| GET_ITER | 4,744,880 | 14.3% |
| POP_TOP | 3,534,420 | 10.6% |
| JUMP_BACKWARD | 3,214,740 | 9.7% |
| LOAD_ATTR_SLOT | 1,255,320 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,950,980 | 44.9% |
| FOR_ITER | 6,337,880 | 19.1% |
| ENTER_EXECUTOR | 4,444,440 | 13.4% |
| POP_JUMP_IF_NONE | 2,423,400 | 7.3% |
| JUMP_BACKWARD | 2,153,980 | 6.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 16,086,770 | 42.4% |
| GET_ITER | 14,578,934 | 38.4% |
| EXTENDED_ARG | 6,337,880 | 16.7% |
| SWAP | 723,740 | 1.9% |
| LOAD_FAST | 82,460 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 13,825,240 | 36.4% |
| STORE_FAST | 5,937,782 | 15.7% |
| RETURN_CONST | 5,604,920 | 14.8% |
| LOAD_FAST | 4,701,621 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,808,360 | 4.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 1,826,360 | 75.2% |
| STORE_FAST | 600,640 | 24.7% |
| STORE_NAME | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,426,560 | 99.9% |
| STORE_NAME | 1,280 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,983,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,826,360 | 92.1% |
| STORE_FAST | 156,480 | 7.9% |
| STORE_DEREF | 320 | 0.0% |
| STORE_NAME | 40 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,593,840 | 73.3% |
| LOAD_CONST | 7,106,820 | 12.5% |
| LOAD_FAST | 6,995,420 | 12.3% |
| LOAD_FAST_LOAD_FAST | 890,240 | 1.6% |
| LOAD_ATTR | 95,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 38,094,720 | 67.1% |
| POP_JUMP_IF_TRUE | 11,627,760 | 20.5% |
| RETURN_VALUE | 4,012,940 | 7.1% |
| LOAD_FAST | 1,637,440 | 2.9% |
| COPY | 824,060 | 1.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,418,216 | 20.5% |
| STORE_SUBSCR | 3,032,100 | 14.1% |
| POP_JUMP_IF_NOT_NONE | 2,553,800 | 11.8% |
| EXTENDED_ARG | 2,153,980 | 10.0% |
| MAP_ADD | 1,806,800 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 16,086,770 | 74.6% |
| EXTENDED_ARG | 3,214,740 | 14.9% |
| FOR_ITER_GEN | 1,230,940 | 5.7% |
| LOAD_FAST_LOAD_FAST | 848,560 | 3.9% |
| FOR_ITER_LIST | 147,052 | 0.7% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 368,132 | 100.0% |
| RESUME | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 368,152 | 100.0% |
| SEND | 40 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 14,018,240 | 29.7% |
| LOAD_ATTR_SLOT | 13,640,820 | 28.9% |
| LOAD_FAST | 6,605,700 | 14.0% |
| STORE_ATTR_SLOT | 5,506,940 | 11.7% |
| STORE_FAST | 3,796,169 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,511,129 | 49.8% |
| STORE_FAST | 14,581,440 | 30.9% |
| MAP_ADD | 6,275,520 | 13.3% |
| LOAD_CONST | 1,026,560 | 2.2% |
| LOAD_GLOBAL_MODULE | 958,510 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,141,000 | 59.6% |
| CALL | 7,028,600 | 27.7% |
| LOAD_FAST | 1,595,550 | 6.3% |
| BINARY_SUBSCR_LIST_INT | 336,300 | 1.3% |
| LOAD_ATTR_SLOT | 308,460 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 25,300,050 | 99.5% |
| JUMP_BACKWARD | 117,520 | 0.5% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,980 | 81.0% |
| RETURN_VALUE | 18,880 | 12.5% |
| BINARY_SLICE | 8,960 | 6.0% |
| LOAD_CONST | 320 | 0.2% |
| STORE_FAST | 320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 150,220 | 99.8% |
| LOAD_CONST | 320 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,703,760 | 65.4% |
| LOAD_GLOBAL_MODULE | 30,348,740 | 26.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,611,160 | 2.3% |
| LOAD_FAST_LOAD_FAST | 2,048,660 | 1.8% |
| CALL_TYPE_1 | 1,443,800 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,302,020 | 45.8% |
| LOAD_FAST_LOAD_FAST | 11,035,580 | 9.7% |
| TO_BOOL | 9,397,760 | 8.2% |
| PUSH_NULL | 8,407,160 | 7.4% |
| CALL_PY_EXACT_ARGS | 6,681,200 | 5.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 170,370,120 | 24.3% |
| LOAD_FAST | 158,776,938 | 22.7% |
| LOAD_CONST | 53,901,300 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 27,787,460 | 4.0% |
| MAP_ADD | 27,390,400 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 282,012,212 | 40.3% |
| BINARY_SUBSCR_DICT | 102,017,160 | 14.6% |
| CALL_KW | 75,015,180 | 10.7% |
| LOAD_CONST | 53,901,300 | 7.7% |
| COMPARE_OP_STR | 34,214,048 | 4.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 92,064,020 | 70.9% |
| LOAD_DEREF | 12,941,020 | 10.0% |
| LOAD_FAST | 5,487,869 | 4.2% |
| LOAD_GLOBAL_MODULE | 5,011,760 | 3.9% |
| POP_JUMP_IF_FALSE | 2,605,189 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,336,196 | 68.0% |
| LOAD_DEREF | 12,941,020 | 10.0% |
| LOAD_ATTR_SLOT | 7,774,160 | 6.0% |
| LOAD_CONST | 4,305,241 | 3.3% |
| LOAD_FAST_LOAD_FAST | 3,638,320 | 2.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 380,286,060 | 13.0% |
| RESUME_CHECK | 302,339,263 | 10.3% |
| LOAD_CONST | 282,012,212 | 9.6% |
| POP_JUMP_IF_FALSE | 253,394,799 | 8.6% |
| STORE_FAST | 244,623,754 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 437,050,943 | 14.9% |
| STORE_ATTR_SLOT | 359,762,012 | 12.3% |
| LOAD_GLOBAL_MODULE | 271,727,218 | 9.3% |
| LOAD_ATTR_METHOD_NO_DICT | 190,251,775 | 6.5% |
| CALL_PY_EXACT_ARGS | 162,543,071 | 5.5% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,579,700 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,440 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,568,820 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,440 | 4.5% |
| MAKE_CELL | 10,880 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,156,080 | 76.4% |
| POP_JUMP_IF_FALSE | 305,600 | 10.8% |
| LOAD_GLOBAL_BUILTIN | 269,360 | 9.5% |
| POP_JUMP_IF_TRUE | 24,640 | 0.9% |
| LOAD_FAST_CHECK | 21,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 2,008,560 | 71.2% |
| LOAD_ATTR_SLOT | 177,560 | 6.3% |
| EXTENDED_ARG | 162,880 | 5.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 152,360 | 5.4% |
| TO_BOOL_BOOL | 100,080 | 3.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 141,091,360 | 24.8% |
| LOAD_SUPER_ATTR_METHOD | 71,619,900 | 12.6% |
| RESUME_CHECK | 60,538,680 | 10.7% |
| LOAD_GLOBAL_MODULE | 46,231,020 | 8.1% |
| STORE_FAST | 42,018,984 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 248,651,120 | 43.8% |
| CALL_PY_EXACT_ARGS | 102,836,860 | 18.1% |
| STORE_ATTR_INSTANCE_VALUE | 44,207,480 | 7.8% |
| LOAD_FAST | 39,416,023 | 6.9% |
| CONTAINS_OP | 18,216,338 | 3.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,600 | 18.8% |
| POP_JUMP_IF_FALSE | 44,571 | 18.4% |
| STORE_FAST | 38,320 | 15.8% |
| RESUME_CHECK | 12,440 | 5.1% |
| RESUME | 12,340 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 75,380 | 31.0% |
| LOAD_FAST | 52,680 | 21.7% |
| LOAD_GLOBAL_BUILTIN | 46,100 | 19.0% |
| CALL | 26,740 | 11.0% |
| LOAD_ATTR | 11,580 | 4.8% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,080 | 51.4% |
| LOAD_NAME | 580 | 27.6% |
| STORE_NAME | 200 | 9.5% |
| STORE_SUBSCR | 100 | 4.8% |
| SETUP_ANNOTATIONS | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 580 | 27.6% |
| LOAD_NAME | 580 | 27.6% |
| BUILD_TUPLE | 380 | 18.1% |
| BINARY_SUBSCR | 300 | 14.3% |
| GET_ITER | 80 | 3.8% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 2,400 | 49.8% |
| CALL | 1,040 | 21.6% |
| LOAD_FAST | 680 | 14.1% |
| LOAD_FAST_LOAD_FAST | 420 | 8.7% |
| LOAD_GLOBAL | 180 | 3.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,839,180 | 65.7% |
| CALL_PY_EXACT_ARGS | 4,902,260 | 14.7% |
| CALL_KW | 4,870,760 | 14.7% |
| BINARY_SUBSCR_GETITEM | 940,780 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 585,560 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,839,180 | 65.7% |
| RESUME_CHECK | 11,386,940 | 34.3% |
| SWAP | 10,880 | 0.0% |
| RETURN_GENERATOR | 2,560 | 0.0% |
| RESUME | 1,640 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,114,540 | 68.5% |
| JUMP_FORWARD | 6,275,520 | 20.4% |
| CALL_BUILTIN_CLASS | 1,674,520 | 5.4% |
| CALL_BUILTIN_FAST | 817,580 | 2.7% |
| LOAD_FAST_LOAD_FAST | 445,440 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,390,400 | 88.8% |
| JUMP_BACKWARD | 1,806,800 | 5.9% |
| CALL_FUNCTION_EX | 1,611,200 | 5.2% |
| ENTER_EXECUTOR | 19,920 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 279,294,674 | 51.4% |
| CONTAINS_OP | 79,465,387 | 14.6% |
| IS_OP | 38,094,720 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 25,229,309 | 4.6% |
| TO_BOOL_NONE | 23,003,931 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 253,394,799 | 46.7% |
| LOAD_GLOBAL_BUILTIN | 133,079,901 | 24.5% |
| LOAD_GLOBAL_MODULE | 46,138,140 | 8.5% |
| LOAD_FAST_LOAD_FAST | 27,809,738 | 5.1% |
| POP_TOP | 20,664,181 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,638,500 | 49.3% |
| LOAD_ATTR_SLOT | 30,484,320 | 37.9% |
| LOAD_ATTR | 4,238,700 | 5.3% |
| EXTENDED_ARG | 2,423,400 | 3.0% |
| BINARY_SUBSCR_DICT | 2,092,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,372,120 | 47.7% |
| RETURN_CONST | 15,863,360 | 19.7% |
| JUMP_FORWARD | 14,018,240 | 17.4% |
| LOAD_CONST | 4,689,420 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 2,981,211 | 3.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,689,680 | 87.7% |
| LOAD_ATTR_SLOT | 4,806,700 | 5.0% |
| BINARY_SUBSCR_DICT | 3,950,580 | 4.1% |
| LOAD_FAST_CHECK | 2,008,560 | 2.1% |
| BINARY_SUBSCR | 298,060 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,967,860 | 38.3% |
| LOAD_FAST | 19,774,040 | 20.5% |
| LOAD_CONST | 13,980,340 | 14.5% |
| LOAD_FAST_LOAD_FAST | 10,686,200 | 11.1% |
| RETURN_CONST | 4,652,580 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 100,955,566 | 45.4% |
| TO_BOOL_LIST | 34,742,280 | 15.6% |
| COMPARE_OP_STR | 30,082,356 | 13.5% |
| COMPARE_OP_INT | 11,725,190 | 5.3% |
| IS_OP | 11,627,760 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,899,456 | 44.1% |
| ENTER_EXECUTOR | 26,535,512 | 11.9% |
| LOAD_GLOBAL_MODULE | 24,968,330 | 11.2% |
| POP_TOP | 17,346,956 | 7.8% |
| NOP | 14,082,560 | 6.3% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 201,280 | 59.3% |
| RETURN_VALUE | 73,920 | 21.8% |
| CALL | 51,600 | 15.2% |
| LOAD_CONST | 12,160 | 3.6% |
| POP_TOP | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 201,280 | 59.3% |
| PUSH_EXC_INFO | 125,760 | 37.0% |
| COPY | 12,480 | 3.7% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 256,640 | 47.2% |
| DELETE_FAST | 201,280 | 37.0% |
| CALL_INTRINSIC_1 | 42,880 | 7.9% |
| POP_JUMP_IF_FALSE | 42,880 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 244,160 | 48.8% |
| PUSH_EXC_INFO | 213,440 | 42.6% |
| CALL_INTRINSIC_1 | 42,880 | 8.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 120,940,980 | 40.3% |
| RESUME_CHECK | 67,669,080 | 22.6% |
| POP_TOP | 23,000,420 | 7.7% |
| POP_JUMP_IF_FALSE | 17,978,500 | 6.0% |
| POP_JUMP_IF_NONE | 15,863,360 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 105,748,220 | 35.2% |
| INTERPRETER_EXIT | 61,992,140 | 20.7% |
| LOAD_FAST | 61,621,760 | 20.5% |
| RETURN_VALUE | 42,797,460 | 14.3% |
| TO_BOOL_BOOL | 11,436,160 | 3.8% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 66.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 50.0% |
| SEND_GEN | 60 | 50.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 1,280,760 | 89.4% |
| STORE_FAST_LOAD_FAST | 64,000 | 4.5% |
| LOAD_ATTR_INSTANCE_VALUE | 63,180 | 4.4% |
| LOAD_FAST | 17,600 | 1.2% |
| RETURN_VALUE | 6,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,342,140 | 93.7% |
| JUMP_BACKWARD | 90,960 | 6.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,055,440 | 77.6% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,712,960 | 32.8% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.4% |
| STORE_FAST | 1,022,300 | 19.6% |
| LOAD_FAST | 452,140 | 8.7% |
| LOAD_GLOBAL_MODULE | 427,620 | 8.2% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,406,480 | 80.9% |
| LOAD_FAST | 2,058,280 | 17.7% |
| SWAP | 118,440 | 1.0% |
| STORE_ATTR | 25,760 | 0.2% |
| LOAD_ATTR_SLOT | 9,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,386,860 | 46.4% |
| RETURN_CONST | 3,177,280 | 27.3% |
| LOAD_FAST | 2,388,120 | 20.5% |
| LOAD_CONST | 262,020 | 2.3% |
| LOAD_GLOBAL_MODULE | 257,880 | 2.2% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,888,640 | 82.3% |
| SET_FUNCTION_ATTRIBUTE | 424,960 | 9.0% |
| RETURN_VALUE | 160,920 | 3.4% |
| LOAD_ATTR_SLOT | 103,000 | 2.2% |
| FOR_ITER_LIST | 37,520 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,929,020 | 62.0% |
| LOAD_FAST | 1,131,160 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 258,860 | 5.5% |
| LOAD_CONST | 189,160 | 4.0% |
| LOAD_DEREF | 177,000 | 3.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 90,165,120 | 18.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 52,266,804 | 10.5% |
| FOR_ITER_LIST | 49,593,004 | 10.0% |
| LOAD_ATTR_SLOT | 45,448,160 | 9.1% |
| BUILD_LIST | 31,852,012 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 244,623,754 | 49.2% |
| LOAD_GLOBAL_BUILTIN | 73,167,146 | 14.7% |
| LOAD_GLOBAL_MODULE | 59,040,820 | 11.9% |
| LOAD_FAST_LOAD_FAST | 42,018,984 | 8.5% |
| LOAD_CONST | 18,814,632 | 3.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,305,248 | 60.9% |
| FOR_ITER_TUPLE | 1,749,340 | 20.1% |
| FOR_ITER | 1,317,820 | 15.1% |
| FOR_ITER_RANGE | 334,960 | 3.8% |
| CALL_LEN | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,976,800 | 34.2% |
| LOAD_CONST | 1,720,548 | 19.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,246,060 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 880,880 | 10.1% |
| LOAD_ATTR_METHOD_NO_DICT | 525,240 | 6.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 15,632,560 | 47.3% |
| UNPACK_SEQUENCE_LIST | 14,619,160 | 44.2% |
| UNPACK_SEQUENCE_TUPLE | 1,864,540 | 5.6% |
| COPY | 611,800 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 105,580 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,535,520 | 74.2% |
| LOAD_FAST_LOAD_FAST | 3,691,040 | 11.2% |
| STORE_FAST | 2,011,960 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,893,100 | 5.7% |
| LOAD_GLOBAL_MODULE | 367,600 | 1.1% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,280 | 57.1% |
| SET_FUNCTION_ATTRIBUTE | 560 | 25.0% |
| LOAD_CONST | 120 | 5.4% |
| CALL | 80 | 3.6% |
| BUILD_STRING | 60 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 840 | 37.5% |
| LOAD_CONST | 620 | 27.7% |
| POP_TOP | 440 | 19.6% |
| LOAD_NAME | 200 | 8.9% |
| RETURN_CONST | 60 | 2.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 26,568,820 | 30.3% |
| BUILD_LIST | 24,178,240 | 27.6% |
| ENTER_EXECUTOR | 11,106,410 | 12.7% |
| FOR_ITER_LIST | 9,012,610 | 10.3% |
| LOAD_FAST | 4,831,800 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 24,178,240 | 27.6% |
| FOR_ITER_LIST | 22,306,320 | 25.5% |
| STORE_FAST | 21,419,080 | 24.4% |
| COPY | 3,583,620 | 4.1% |
| POP_TOP | 3,524,980 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 960 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 90,560 | 65.6% |
| COPY | 26,560 | 19.2% |
| FOR_ITER_LIST | 8,057 | 5.8% |
| FOR_ITER | 4,540 | 3.3% |
| RETURN_VALUE | 3,680 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 98,457 | 71.3% |
| STORE_FAST_STORE_FAST | 33,280 | 24.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,120 | 3.0% |
| UNPACK_SEQUENCE_TUPLE | 980 | 0.7% |
| UNPACK_SEQUENCE | 880 | 0.6% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,524,480 | 22.5% |
| LOAD_CONST | 1,885,440 | 16.8% |
| ENTER_EXECUTOR | 1,721,077 | 15.3% |
| LOAD_FAST | 1,142,140 | 10.2% |
| CALL_ISINSTANCE | 797,700 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,570,360 | 85.4% |
| STORE_FAST | 897,560 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 376,200 | 3.4% |
| YIELD_VALUE | 368,192 | 3.3% |
| UNPACK_SEQUENCE | 60 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 19,900 | 48.7% |
| CALL_PY_EXACT_ARGS | 5,500 | 13.5% |
| CACHE | 5,480 | 13.4% |
| COPY_FREE_VARS | 3,080 | 7.5% |
| POP_TOP | 2,420 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,400 | 47.5% |
| LOAD_GLOBAL | 12,340 | 30.2% |
| LOAD_FAST_LOAD_FAST | 2,060 | 5.0% |
| LOAD_CONST | 1,920 | 4.7% |
| POP_TOP | 1,820 | 4.5% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 286,480 | 99.5% |
| BINARY_OP_ADD_INT | 1,200 | 0.4% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 286,480 | 99.5% |
| BINARY_OP_ADD_INT | 1,200 | 0.4% |
| STORE_FAST | 140 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,244,361 | 55.8% |
| CALL_LEN | 1,511,400 | 19.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,467,800 | 19.3% |
| LOAD_FAST | 194,320 | 2.6% |
| LOAD_FAST_LOAD_FAST | 178,297 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,159,800 | 41.6% |
| LOAD_FAST | 2,065,540 | 27.2% |
| SWAP | 991,000 | 13.0% |
| LOAD_FAST_LOAD_FAST | 688,900 | 9.1% |
| LOAD_CONST | 213,940 | 2.8% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,340,520 | 35.1% |
| LOAD_FAST | 1,396,800 | 21.0% |
| CALL_METHOD_DESCRIPTOR_O | 984,600 | 14.8% |
| LOAD_FAST_LOAD_FAST | 984,400 | 14.8% |
| BINARY_SLICE | 450,740 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,924,300 | 28.9% |
| RETURN_VALUE | 1,346,260 | 20.2% |
| SET_ADD | 1,280,760 | 19.2% |
| STORE_FAST | 1,071,020 | 16.1% |
| BUILD_TUPLE | 436,460 | 6.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 98.4% |
| BINARY_OP | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,240 | 98.4% |
| CALL | 20 | 1.6% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,840 | 88.3% |
| BINARY_SUBSCR_TUPLE_INT | 640 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,480 | 81.8% |
| BINARY_OP_ADD_INT | 640 | 11.7% |
| LOAD_CONST | 180 | 3.3% |
| CALL_BUILTIN_O | 180 | 3.3% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 178,960 | 61.0% |
| LOAD_FAST_LOAD_FAST | 113,600 | 38.7% |
| BINARY_OP | 380 | 0.1% |
| LOAD_ATTR_WITH_HINT | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 235,600 | 80.3% |
| LOAD_FAST_LOAD_FAST | 56,580 | 19.3% |
| LOAD_GLOBAL_BUILTIN | 560 | 0.2% |
| LOAD_FAST | 300 | 0.1% |
| BINARY_OP_ADD_FLOAT | 120 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,517,298 | 93.7% |
| LOAD_FAST | 122,806 | 3.3% |
| CALL_LEN | 99,780 | 2.7% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.2% |
| LOAD_ATTR_SLOT | 3,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,849,840 | 49.3% |
| BINARY_SLICE | 890,220 | 23.7% |
| SWAP | 290,120 | 7.7% |
| STORE_FAST | 275,240 | 7.3% |
| BINARY_SUBSCR_LIST_INT | 263,540 | 7.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 102,017,160 | 86.0% |
| LOAD_FAST | 9,114,085 | 7.7% |
| BINARY_SUBSCR_DICT | 3,040,560 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 1,821,400 | 1.5% |
| LOAD_DEREF | 1,502,120 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,003,620 | 18.6% |
| STORE_FAST | 20,484,449 | 17.3% |
| LOAD_CONST | 20,037,220 | 16.9% |
| GET_ITER | 12,484,600 | 10.5% |
| CALL_PY_EXACT_ARGS | 9,517,360 | 8.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,533,080 | 54.9% |
| LOAD_FAST_LOAD_FAST | 1,245,660 | 44.6% |
| LOAD_CONST | 7,240 | 0.3% |
| ENTER_EXECUTOR | 5,720 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,850,800 | 66.3% |
| MAKE_CELL | 940,780 | 33.7% |
| LOAD_ATTR_SLOT | 640 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,580,980 | 44.7% |
| LOAD_FAST | 5,583,700 | 29.1% |
| LOAD_FAST_LOAD_FAST | 4,653,580 | 24.3% |
| BINARY_OP_SUBTRACT_INT | 263,540 | 1.4% |
| BINARY_OP_ADD_INT | 47,440 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,824,420 | 14.7% |
| STORE_FAST | 2,782,280 | 14.5% |
| LOAD_GLOBAL_MODULE | 2,255,320 | 11.8% |
| BINARY_SUBSCR_DICT | 1,821,400 | 9.5% |
| CALL_PY_EXACT_ARGS | 1,585,660 | 8.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 745,800 | 79.0% |
| BINARY_OP_ADD_INT | 117,560 | 12.5% |
| LOAD_FAST_LOAD_FAST | 41,140 | 4.4% |
| BINARY_OP_SUBTRACT_INT | 36,960 | 3.9% |
| LOAD_FAST | 1,700 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 632,080 | 67.0% |
| LOAD_FAST | 159,660 | 16.9% |
| CALL_BUILTIN_O | 67,820 | 7.2% |
| LOAD_FAST_LOAD_FAST | 33,880 | 3.6% |
| COMPARE_OP_STR | 33,840 | 3.6% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,660,400 | 99.6% |
| LOAD_FAST_LOAD_FAST | 4,400 | 0.3% |
| BINARY_SUBSCR | 1,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 307,600 | 18.5% |
| FORMAT_SIMPLE | 281,600 | 16.9% |
| LOAD_FAST_LOAD_FAST | 208,860 | 12.5% |
| STORE_FAST | 201,660 | 12.1% |
| CALL | 155,500 | 9.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,126,160 | 46.9% |
| LOAD_FAST | 1,826,580 | 27.4% |
| LOAD_GLOBAL_MODULE | 700,840 | 10.5% |
| CALL | 431,800 | 6.5% |
| RETURN_VALUE | 365,640 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,207,900 | 93.1% |
| COPY_FREE_VARS | 450,680 | 6.8% |
| CALL_PY_EXACT_ARGS | 6,400 | 0.1% |
| STORE_FAST | 2,560 | 0.0% |
| MAKE_CELL | 300 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,329,480 | 63.9% |
| BINARY_SUBSCR_DICT | 6,452,840 | 22.5% |
| LOAD_CONST | 2,692,860 | 9.4% |
| ENTER_EXECUTOR | 811,140 | 2.8% |
| CALL_PY_EXACT_ARGS | 102,500 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,886,580 | 90.3% |
| POP_TOP | 2,625,160 | 9.2% |
| CALL_PY_EXACT_ARGS | 102,520 | 0.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 49,740 | 0.2% |
| RESUME | 980 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,067,160 | 29.9% |
| LOAD_GLOBAL_BUILTIN | 7,134,480 | 17.7% |
| LOAD_ATTR_SLOT | 4,516,872 | 11.2% |
| LOAD_ATTR_CLASS | 3,789,040 | 9.4% |
| CALL_LEN | 3,073,740 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,018,300 | 47.2% |
| LOAD_FAST | 10,530,120 | 26.1% |
| STORE_FAST | 3,772,640 | 9.4% |
| RETURN_VALUE | 2,544,960 | 6.3% |
| MAP_ADD | 1,674,520 | 4.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,888,198 | 41.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,659,620 | 33.2% |
| LOAD_FAST_LOAD_FAST | 2,638,960 | 18.8% |
| LOAD_FAST | 664,900 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 90,280 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,896,440 | 20.6% |
| RETURN_VALUE | 2,325,720 | 16.6% |
| PUSH_EXC_INFO | 2,282,200 | 16.3% |
| POP_TOP | 2,104,200 | 15.0% |
| TO_BOOL_BOOL | 2,040,480 | 14.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,215,040 | 84.8% |
| RETURN_GENERATOR | 385,440 | 10.2% |
| CALL_BUILTIN_CLASS | 141,720 | 3.7% |
| RETURN_VALUE | 47,920 | 1.3% |
| LOAD_CONST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,621,500 | 69.1% |
| COPY | 335,360 | 8.8% |
| LOAD_CONST | 304,300 | 8.0% |
| PUSH_EXC_INFO | 200,400 | 5.3% |
| RETURN_VALUE | 144,500 | 3.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 5,669,948 | 35.9% |
| RETURN_GENERATOR | 4,748,320 | 30.0% |
| LOAD_FAST | 2,121,180 | 13.4% |
| LOAD_GLOBAL_MODULE | 1,203,200 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 653,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,973,592 | 44.1% |
| LOAD_FAST | 4,956,432 | 31.3% |
| TO_BOOL_BOOL | 1,700,040 | 10.7% |
| CALL_PY_EXACT_ARGS | 904,580 | 5.7% |
| STORE_FAST | 459,400 | 2.9% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 234,111,658 | 84.6% |
| LOAD_GLOBAL_BUILTIN | 34,753,260 | 12.6% |
| BUILD_TUPLE | 4,530,100 | 1.6% |
| LOAD_ATTR | 1,896,300 | 0.7% |
| LOAD_ATTR_MODULE | 947,406 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 270,272,736 | 97.7% |
| COPY | 4,261,560 | 1.5% |
| YIELD_VALUE | 797,700 | 0.3% |
| RETURN_VALUE | 745,108 | 0.3% |
| STORE_FAST | 395,980 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,220,280 | 56.8% |
| LOAD_ATTR_SLOT | 11,051,540 | 31.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,904,620 | 5.4% |
| LOAD_DEREF | 1,900,680 | 5.3% |
| LOAD_ATTR | 217,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,430,060 | 26.5% |
| COMPARE_OP_INT | 5,961,880 | 16.8% |
| LOAD_GLOBAL_BUILTIN | 4,564,240 | 12.8% |
| SWAP | 3,580,440 | 10.1% |
| CALL_BUILTIN_CLASS | 3,073,740 | 8.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,926,480 | 77.5% |
| RETURN_VALUE | 2,635,720 | 8.2% |
| ENTER_EXECUTOR | 1,531,757 | 4.8% |
| LOAD_CONST | 567,720 | 1.8% |
| BUILD_TUPLE | 548,503 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,527,100 | 54.5% |
| ENTER_EXECUTOR | 8,856,700 | 27.6% |
| NOP | 2,435,240 | 7.6% |
| EXTENDED_ARG | 683,180 | 2.1% |
| LOAD_CONST | 680,720 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,702,420 | 54.6% |
| LOAD_ATTR_METHOD_NO_DICT | 20,433,713 | 32.1% |
| LOAD_CONST | 2,720,260 | 4.3% |
| ENTER_EXECUTOR | 1,894,500 | 3.0% |
| LOAD_GLOBAL_MODULE | 1,311,914 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 52,266,804 | 82.2% |
| POP_TOP | 4,743,913 | 7.5% |
| LOAD_FAST | 2,743,250 | 4.3% |
| CALL_PY_EXACT_ARGS | 923,140 | 1.5% |
| LOAD_ATTR_METHOD_NO_DICT | 707,920 | 1.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,829,160 | 90.2% |
| LOAD_FAST | 187,400 | 6.0% |
| LOAD_ATTR_MODULE | 92,440 | 2.9% |
| LOAD_ATTR_METHOD_NO_DICT | 25,800 | 0.8% |
| CALL | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,195,880 | 70.0% |
| LOAD_CONST | 343,200 | 10.9% |
| UNPACK_SEQUENCE_LIST | 192,780 | 6.1% |
| GET_ITER | 188,420 | 6.0% |
| CONTAINS_OP | 92,460 | 2.9% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,980,840 | 98.4% |
| ENTER_EXECUTOR | 40,120 | 1.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,200 | 0.2% |
| CALL | 1,540 | 0.1% |
| LOAD_ATTR | 1,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,727,840 | 57.0% |
| LOAD_FAST | 574,900 | 19.0% |
| POP_TOP | 320,620 | 10.6% |
| CALL_BUILTIN_CLASS | 239,760 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 89,560 | 3.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,516,600 | 53.8% |
| LOAD_FAST | 3,958,967 | 32.7% |
| RETURN_VALUE | 631,520 | 5.2% |
| LOAD_ATTR_SLOT | 257,100 | 2.1% |
| BUILD_TUPLE | 243,160 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,077,660 | 42.0% |
| POP_TOP | 4,317,307 | 35.7% |
| BINARY_OP_ADD_INT | 1,467,800 | 12.1% |
| BINARY_OP_ADD_UNICODE | 984,600 | 8.1% |
| STORE_FAST | 171,440 | 1.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,543,071 | 37.3% |
| LOAD_FAST_LOAD_FAST | 102,836,860 | 23.6% |
| LOAD_ATTR_METHOD_NO_DICT | 74,527,956 | 17.1% |
| LOAD_ATTR_SLOT | 13,881,092 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,335,060 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 377,583,407 | 86.7% |
| COPY_FREE_VARS | 47,449,860 | 10.9% |
| MAKE_CELL | 4,902,260 | 1.1% |
| RETURN_GENERATOR | 4,222,940 | 1.0% |
| CALL_PY_EXACT_ARGS | 721,097 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 7,932,960 | 38.3% |
| LOAD_FAST | 6,751,960 | 32.6% |
| LOAD_FAST_LOAD_FAST | 1,837,940 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,245,940 | 6.0% |
| LOAD_ATTR_SLOT | 645,240 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,893,460 | 96.0% |
| MAKE_CELL | 585,560 | 2.8% |
| COPY_FREE_VARS | 233,200 | 1.1% |
| CALL_PY_EXACT_ARGS | 7,960 | 0.0% |
| RETURN_GENERATOR | 940 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,218,940 | 100.0% |
| UNARY_NOT | 280 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,660 | 80.7% |
| CALL_BUILTIN_O | 187,160 | 15.3% |
| STORE_FAST | 33,120 | 2.7% |
| CALL | 15,040 | 1.2% |
| BUILD_TUPLE | 300 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,818,540 | 92.5% |
| LOAD_ATTR_SLOT | 1,464,716 | 7.2% |
| RETURN_VALUE | 22,540 | 0.1% |
| LOAD_FAST_CHECK | 19,480 | 0.1% |
| RETURN_GENERATOR | 8,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,960,180 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 762,360 | 3.7% |
| BUILD_TUPLE | 531,116 | 2.6% |
| CALL_PY_EXACT_ARGS | 33,560 | 0.2% |
| RETURN_VALUE | 24,440 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,111,480 | 100.0% |
| LOAD_CONST | 300 | 0.0% |
| CALL | 200 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,950,040 | 62.5% |
| STORE_FAST | 1,538,440 | 13.8% |
| LOAD_ATTR | 1,443,800 | 13.0% |
| PUSH_NULL | 890,280 | 8.0% |
| LOAD_GLOBAL_MODULE | 120,000 | 1.1% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,040 | 98.7% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 1.0% |
| COMPARE_OP | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,060 | 99.0% |
| POP_JUMP_IF_FALSE | 60 | 1.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,825,117 | 38.7% |
| CALL_LEN | 5,961,880 | 15.6% |
| LOAD_GLOBAL_MODULE | 3,592,440 | 9.4% |
| COPY | 3,580,400 | 9.4% |
| LOAD_ATTR_CLASS | 3,555,000 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 22,134,661 | 57.8% |
| POP_JUMP_IF_TRUE | 11,725,190 | 30.6% |
| COPY | 2,105,760 | 5.5% |
| RETURN_VALUE | 1,278,686 | 3.3% |
| EXTENDED_ARG | 626,880 | 1.6% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,214,048 | 73.3% |
| LOAD_FAST | 9,063,676 | 19.4% |
| RETURN_VALUE | 957,820 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 836,356 | 1.8% |
| LOAD_ATTR_MODULE | 633,760 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 30,082,356 | 64.5% |
| POP_JUMP_IF_FALSE | 11,384,680 | 24.4% |
| COPY | 3,095,592 | 6.6% |
| RETURN_VALUE | 1,230,479 | 2.6% |
| EXTENDED_ARG | 777,260 | 1.7% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,230,940 | 92.7% |
| GET_ITER | 96,860 | 7.3% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,230,960 | 92.7% |
| POP_TOP | 96,860 | 7.3% |
| RESUME | 80 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 45,018,695 | 59.8% |
| SWAP | 22,306,320 | 29.6% |
| LOAD_FAST | 5,163,980 | 6.9% |
| EXTENDED_ARG | 1,469,020 | 2.0% |
| ENTER_EXECUTOR | 1,103,327 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 49,593,004 | 65.9% |
| SWAP | 9,012,610 | 12.0% |
| LOAD_FAST | 5,640,965 | 7.5% |
| STORE_FAST_LOAD_FAST | 5,305,248 | 7.0% |
| RETURN_CONST | 3,426,677 | 4.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,952,920 | 86.7% |
| SWAP | 790,380 | 11.5% |
| EXTENDED_ARG | 117,320 | 1.7% |
| JUMP_BACKWARD | 6,980 | 0.1% |
| FOR_ITER | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,523,380 | 36.7% |
| LOAD_FAST | 1,909,240 | 27.8% |
| RETURN_CONST | 1,441,620 | 21.0% |
| LOAD_GLOBAL_MODULE | 658,220 | 9.6% |
| STORE_FAST_LOAD_FAST | 334,960 | 4.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,154,519 | 82.6% |
| SWAP | 2,759,260 | 11.9% |
| ENTER_EXECUTOR | 1,182,788 | 5.1% |
| EXTENDED_ARG | 35,420 | 0.2% |
| FOR_ITER_LIST | 31,104 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,685,656 | 59.0% |
| STORE_FAST | 6,717,494 | 29.0% |
| STORE_FAST_LOAD_FAST | 1,749,340 | 7.5% |
| SWAP | 709,840 | 3.1% |
| RETURN_CONST | 298,240 | 1.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,180,980 | 88.5% |
| LOAD_FAST | 1,544,160 | 10.4% |
| COPY | 105,520 | 0.7% |
| ENTER_EXECUTOR | 56,260 | 0.4% |
| LOAD_ATTR_CLASS | 6,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 3,789,040 | 25.4% |
| COMPARE_OP_INT | 3,555,000 | 23.9% |
| LOAD_ATTR_METHOD_NO_DICT | 2,703,560 | 18.1% |
| CALL | 2,566,780 | 17.2% |
| LOAD_ATTR_MODULE | 1,544,160 | 10.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,832,335 | 80.6% |
| LOAD_FAST_LOAD_FAST | 12,640,546 | 8.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,948,900 | 3.8% |
| LOAD_GLOBAL_MODULE | 4,175,120 | 2.7% |
| LOAD_DEREF | 1,803,980 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,112,985 | 18.8% |
| LOAD_CONST | 27,787,460 | 17.9% |
| LOAD_ATTR_METHOD_NO_DICT | 14,290,234 | 9.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,941,780 | 8.4% |
| CONTAINS_OP | 7,852,326 | 5.1% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,880 | 99.9% |
| LOAD_ATTR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,620 | 99.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 280 | 0.9% |
| CALL | 20 | 0.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 190,251,775 | 72.2% |
| LOAD_ATTR_SLOT | 26,317,648 | 10.0% |
| LOAD_ATTR_INSTANCE_VALUE | 14,290,234 | 5.4% |
| LOAD_GLOBAL_MODULE | 10,333,800 | 3.9% |
| ENTER_EXECUTOR | 8,097,423 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,245,781 | 44.5% |
| CALL_PY_EXACT_ARGS | 74,527,956 | 28.3% |
| LOAD_CONST | 25,431,788 | 9.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 20,433,713 | 7.8% |
| LOAD_GLOBAL_MODULE | 18,023,612 | 6.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,321,931 | 81.7% |
| LOAD_ATTR_INSTANCE_VALUE | 12,941,780 | 11.3% |
| LOAD_DEREF | 2,566,240 | 2.2% |
| LOAD_FAST_LOAD_FAST | 1,358,880 | 1.2% |
| LOAD_ATTR_WITH_HINT | 1,358,040 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,664,700 | 69.7% |
| LOAD_FAST_LOAD_FAST | 15,953,700 | 14.0% |
| CALL_PY_EXACT_ARGS | 11,335,060 | 9.9% |
| LOAD_CONST | 2,703,780 | 2.4% |
| LOAD_DEREF | 2,126,500 | 1.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 17,404,746 | 66.4% |
| LOAD_ATTR_MODULE | 5,810,280 | 22.2% |
| LOAD_ATTR_CLASS | 1,544,160 | 5.9% |
| LOAD_FAST_LOAD_FAST | 1,235,000 | 4.7% |
| LOAD_FAST | 202,480 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,810,280 | 22.2% |
| PUSH_NULL | 4,889,780 | 18.7% |
| LOAD_FAST | 4,099,480 | 15.6% |
| COMPARE_OP | 3,251,980 | 12.4% |
| LOAD_GLOBAL_MODULE | 1,606,620 | 6.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,069,640 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 983,660 | 92.0% |
| LOAD_FAST | 43,200 | 4.0% |
| IS_OP | 42,860 | 4.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 689,200 | 64.0% |
| LOAD_FAST | 375,940 | 34.9% |
| BINARY_SUBSCR_DICT | 6,160 | 0.6% |
| LOAD_FAST_LOAD_FAST | 3,440 | 0.3% |
| STORE_FAST_LOAD_FAST | 580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 690,680 | 64.2% |
| CALL_LEN | 137,880 | 12.8% |
| RETURN_VALUE | 104,740 | 9.7% |
| LOAD_FAST | 95,560 | 8.9% |
| POP_JUMP_IF_NONE | 35,960 | 3.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,992,865 | 54.8% |
| LOAD_ATTR_SLOT | 6,459,445 | 23.6% |
| ENTER_EXECUTOR | 5,064,088 | 18.5% |
| LOAD_ATTR_INSTANCE_VALUE | 482,920 | 1.8% |
| CALL | 93,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,543,473 | 93.4% |
| RETURN_VALUE | 1,067,944 | 3.9% |
| LOAD_FAST | 239,400 | 0.9% |
| STORE_FAST | 238,600 | 0.9% |
| LOAD_CONST | 105,300 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 437,050,943 | 88.2% |
| LOAD_ATTR_SLOT | 34,705,787 | 7.0% |
| LOAD_DEREF | 7,774,160 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,554,045 | 1.3% |
| STORE_FAST_LOAD_FAST | 2,976,800 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,944,608 | 12.1% |
| GET_ITER | 47,884,688 | 9.7% |
| STORE_FAST | 45,448,160 | 9.2% |
| RETURN_VALUE | 36,493,151 | 7.4% |
| LOAD_ATTR_SLOT | 34,705,787 | 7.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,584,520 | 57.0% |
| LOAD_FAST_LOAD_FAST | 6,438,440 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 6,298,820 | 20.4% |
| LOAD_ATTR_WITH_HINT | 500,740 | 1.6% |
| LOAD_DEREF | 10,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,599,560 | 31.1% |
| LOAD_ATTR_METHOD_NO_DICT | 3,625,480 | 11.8% |
| TO_BOOL_BOOL | 3,616,980 | 11.7% |
| COPY | 2,789,480 | 9.0% |
| LOAD_FAST | 2,484,360 | 8.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 168,213,890 | 30.7% |
| POP_JUMP_IF_FALSE | 133,079,901 | 24.3% |
| STORE_FAST | 73,167,146 | 13.4% |
| LOAD_FAST | 39,249,320 | 7.2% |
| POP_JUMP_IF_NOT_NONE | 36,967,860 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380,286,060 | 69.4% |
| LOAD_DEREF | 92,064,020 | 16.8% |
| CALL_ISINSTANCE | 34,753,260 | 6.3% |
| CALL_BUILTIN_CLASS | 7,134,480 | 1.3% |
| LOAD_FAST_LOAD_FAST | 6,497,740 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 271,727,218 | 44.4% |
| STORE_FAST | 59,040,820 | 9.7% |
| RESUME_CHECK | 53,242,080 | 8.7% |
| POP_JUMP_IF_FALSE | 46,138,140 | 7.5% |
| LOAD_GLOBAL_MODULE | 32,524,220 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 234,111,658 | 38.3% |
| LOAD_FAST | 116,716,652 | 19.1% |
| LOAD_FAST_LOAD_FAST | 46,231,020 | 7.6% |
| IS_OP | 41,593,840 | 6.8% |
| LOAD_GLOBAL_MODULE | 32,524,220 | 5.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,083,100 | 100.0% |
| LOAD_SUPER_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,077,400 | 99.5% |
| STORE_FAST | 5,760 | 0.5% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,016,560 | 100.0% |
| LOAD_SUPER_ATTR | 2,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,619,900 | 83.3% |
| CALL_PY_WITH_DEFAULTS | 7,932,960 | 9.2% |
| CALL_PY_EXACT_ARGS | 3,262,080 | 3.8% |
| LOAD_FAST | 2,075,160 | 2.4% |
| LOAD_GLOBAL_MODULE | 689,240 | 0.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 377,583,407 | 54.6% |
| COPY_FREE_VARS | 93,013,740 | 13.5% |
| CACHE | 69,740,053 | 10.1% |
| CALL_KW | 43,426,700 | 6.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 25,886,580 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 302,339,263 | 43.8% |
| LOAD_GLOBAL_BUILTIN | 168,213,890 | 24.3% |
| RETURN_CONST | 67,669,080 | 9.8% |
| LOAD_FAST_LOAD_FAST | 60,538,680 | 8.8% |
| LOAD_GLOBAL_MODULE | 53,242,080 | 7.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 368,152 | 79.3% |
| LOAD_CONST | 95,920 | 20.7% |
| SEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 368,152 | 79.3% |
| POP_TOP | 95,940 | 20.7% |
| RESUME | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 44,207,480 | 56.7% |
| LOAD_FAST | 32,504,500 | 41.7% |
| SWAP | 794,320 | 1.0% |
| BINARY_SUBSCR | 449,520 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 32,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,617,660 | 46.9% |
| RETURN_CONST | 13,692,200 | 17.6% |
| LOAD_FAST | 13,002,000 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 5,133,860 | 6.6% |
| LOAD_GLOBAL_MODULE | 3,667,940 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 359,762,012 | 58.8% |
| LOAD_FAST_LOAD_FAST | 248,651,120 | 40.6% |
| STORE_ATTR_SLOT | 2,483,904 | 0.4% |
| LOAD_ATTR_SLOT | 847,800 | 0.1% |
| ENTER_EXECUTOR | 83,060 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 170,370,120 | 27.8% |
| LOAD_FAST_LOAD_FAST | 141,091,360 | 23.1% |
| RETURN_CONST | 120,940,980 | 19.8% |
| LOAD_FAST | 112,444,672 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 31,685,060 | 5.2% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 943,280 | 57.4% |
| LOAD_FAST_LOAD_FAST | 697,880 | 42.5% |
| SWAP | 840 | 0.1% |
| STORE_ATTR_WITH_HINT | 700 | 0.0% |
| STORE_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 512,260 | 31.2% |
| LOAD_GLOBAL_MODULE | 448,360 | 27.3% |
| RETURN_CONST | 344,580 | 21.0% |
| LOAD_FAST | 257,540 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 78,680 | 4.8% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,653,358 | 73.5% |
| LOAD_FAST_LOAD_FAST | 438,980 | 8.8% |
| LOAD_ATTR_SLOT | 410,400 | 8.3% |
| SWAP | 367,960 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 47,240 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,497,460 | 50.3% |
| LOAD_FAST | 924,118 | 18.6% |
| JUMP_BACKWARD | 853,400 | 17.2% |
| ENTER_EXECUTOR | 466,620 | 9.4% |
| LOAD_GLOBAL_BUILTIN | 95,380 | 1.9% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 431,960 | 99.8% |
| LOAD_FAST | 960 | 0.2% |
| STORE_SUBSCR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 430,160 | 99.3% |
| EXTENDED_ARG | 1,380 | 0.3% |
| LOAD_FAST | 840 | 0.2% |
| RETURN_CONST | 320 | 0.1% |
| JUMP_BACKWARD | 300 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,146,609 | 75.8% |
| LOAD_ATTR_SLOT | 5,611,620 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 553,760 | 1.9% |
| COPY | 234,540 | 0.8% |
| LOAD_ATTR | 225,500 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,229,309 | 86.3% |
| POP_JUMP_IF_TRUE | 2,924,140 | 10.0% |
| EXTENDED_ARG | 992,840 | 3.4% |
| TO_BOOL_NONE | 36,529 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 33,676 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 270,272,736 | 65.4% |
| COPY | 38,522,624 | 9.3% |
| LOAD_FAST | 34,233,660 | 8.3% |
| RETURN_VALUE | 25,359,600 | 6.1% |
| LOAD_ATTR_SLOT | 11,723,600 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 279,294,674 | 67.5% |
| POP_JUMP_IF_TRUE | 100,955,566 | 24.4% |
| UNARY_NOT | 22,824,800 | 5.5% |
| EXTENDED_ARG | 10,433,260 | 2.5% |
| TO_BOOL_STR | 640 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,184,965 | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE | 356,080 | 18.9% |
| RETURN_VALUE | 148,400 | 7.9% |
| LOAD_ATTR_SLOT | 138,880 | 7.4% |
| BINARY_OP | 52,100 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,350,825 | 71.7% |
| POP_JUMP_IF_TRUE | 391,680 | 20.8% |
| UNARY_NOT | 139,280 | 7.4% |
| TO_BOOL_STR | 1,280 | 0.1% |
| TO_BOOL_BOOL | 320 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,675,660 | 75.9% |
| LOAD_ATTR_SLOT | 6,507,680 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,594,780 | 5.7% |
| COPY | 888,220 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 393,200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 34,742,280 | 76.0% |
| POP_JUMP_IF_FALSE | 7,629,800 | 16.7% |
| UNARY_NOT | 2,525,220 | 5.5% |
| EXTENDED_ARG | 790,880 | 1.7% |
| TO_BOOL | 4,300 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,342,331 | 63.4% |
| LOAD_ATTR_SLOT | 8,021,280 | 25.0% |
| COPY | 1,795,240 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 582,760 | 1.8% |
| LOAD_ATTR_MODULE | 518,960 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,003,931 | 71.7% |
| POP_JUMP_IF_TRUE | 8,234,060 | 25.7% |
| EXTENDED_ARG | 776,420 | 2.4% |
| TO_BOOL_ALWAYS_TRUE | 36,855 | 0.1% |
| UNARY_NOT | 7,920 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,661,280 | 71.9% |
| COPY | 1,506,760 | 16.3% |
| LOAD_ATTR_SLOT | 436,820 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 349,240 | 3.8% |
| STORE_FAST_LOAD_FAST | 187,920 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,434,000 | 58.7% |
| POP_JUMP_IF_TRUE | 3,454,160 | 37.3% |
| UNARY_NOT | 369,580 | 4.0% |
| TO_BOOL_NONE | 4,940 | 0.1% |
| TO_BOOL_INT | 1,580 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 14,181,920 | 97.0% |
| RETURN_VALUE | 232,840 | 1.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 192,780 | 1.3% |
| LOAD_FAST | 15,920 | 0.1% |
| BINARY_SLICE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,619,160 | 100.0% |
| STORE_FAST | 5,740 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 777,560 | 38.8% |
| YIELD_VALUE | 376,200 | 18.8% |
| STORE_FAST | 373,640 | 18.6% |
| FOR_ITER | 242,800 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 93,080 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,864,540 | 93.0% |
| STORE_FAST | 141,020 | 7.0% |
| STORE_DEREF | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 13,825,240 | 82.3% |
| RETURN_VALUE | 1,471,900 | 8.8% |
| FOR_ITER_LIST | 503,300 | 3.0% |
| STORE_FAST | 371,320 | 2.2% |
| RETURN_CONST | 290,360 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 15,632,560 | 93.0% |
| STORE_FAST | 1,143,540 | 6.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,040 | 0.2% |
| UNPACK_SEQUENCE | 20 | 0.0% |


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
|     deferred | 4,819,600 | 20.1% |
|          hit | 19,050,842 | 79.3% |
|         miss | 127,480 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,500 | 34.4% |
| Failure | 14,300 | 65.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 6,440 | 45.0% |
| multiply different types | 3,520 | 24.6% |
| or | 1,280 | 9.0% |
| remainder | 1,140 | 8.0% |
| subtract other | 980 | 6.9% |
| and int | 420 | 2.9% |
| and different types | 160 | 1.1% |
| subtract different types | 160 | 1.1% |
| true divide different types | 140 | 1.0% |
| and other | 60 | 0.4% |


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
|     deferred | 40,259,449 | 21.9% |
|          hit | 143,168,165 | 78.0% |
|         miss | 1,580 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,320 | 30.4% |
| Failure | 28,226 | 69.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 16,546 | 58.6% |
| other | 7,080 | 25.1% |
| code complex parameters | 4,280 | 15.2% |
| buffer int | 240 | 0.9% |
| tuple slice | 80 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 67,185,023 | 6.0% |
|          hit | 989,214,947 | 88.5% |
|         miss | 60,323,985 | 5.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,249,897 | 91.7% |
| Failure | 113,480 | 8.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 39,960 | 35.2% |
| code complex parameters | 27,580 | 24.3% |
| meth descr varargs | 12,860 | 11.3% |
| class no vectorcall | 8,900 | 7.8% |
| class mutable | 5,720 | 5.0% |
| cfunc noargs | 5,380 | 4.7% |
| cfunc varargs keywords | 3,760 | 3.3% |
| meth descr varargs keywords | 1,620 | 1.4% |
| wrong number arguments | 1,440 | 1.3% |
| init not simple | 1,340 | 1.2% |
| meth descr method fastcall keywords | 1,180 | 1.0% |
| bound method | 1,060 | 0.9% |
| other | 1,040 | 0.9% |
| cfunc varargs | 580 | 0.5% |
| init not python | 540 | 0.5% |
| cmethod | 400 | 0.4% |
| operator wrapper | 120 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 42,863,184 | 33.5% |
|          hit | 84,082,022 | 65.7% |
|         miss | 874,966 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 29,484 | 26.5% |
| Failure | 81,912 | 73.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 47,133 | 57.5% |
| baseobject | 13,800 | 16.8% |
| other | 6,080 | 7.4% |
| different types | 5,720 | 7.0% |
| bool | 3,439 | 4.2% |
| tuple | 3,020 | 3.7% |
| list | 2,120 | 2.6% |
| set | 320 | 0.4% |
| string | 280 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 37,810,272 | 26.2% |
|          hit | 103,134,090 | 71.3% |
|         miss | 3,509,480 | 2.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 78,491 | 65.6% |
| Failure | 41,211 | 34.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 9,900 | 24.0% |
| set | 9,211 | 22.4% |
| zip | 7,220 | 17.5% |
| dict items | 5,860 | 14.2% |
| reversed list | 4,680 | 11.4% |
| dict keys | 2,220 | 5.4% |
| dict values | 1,140 | 2.8% |
| itertools | 480 | 1.2% |
| map | 260 | 0.6% |
| other | 220 | 0.5% |
| seq iter | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 112,159,542 | 9.0% |
|        deopt | 1,580 | 0.0% |
|          hit | 1,041,057,366 | 83.7% |
|         miss | 88,499,241 | 7.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,823,418 | 89.8% |
| Failure | 206,640 | 10.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 102,740 | 49.7% |
| not managed dict | 37,220 | 18.0% |
| shadowed | 27,260 | 13.2% |
| metaclass attribute | 9,240 | 4.5% |
| class method obj | 8,760 | 4.2% |
| non overriding descriptor | 8,020 | 3.9% |
| method | 5,660 | 2.7% |
| class attr simple | 4,060 | 2.0% |
| module attr not found | 2,980 | 1.4% |
| builtin class method | 400 | 0.2% |
| class attr descriptor | 180 | 0.1% |
| mutable class | 120 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 122,060 | 0.0% |
|        deopt | 840 | 0.0% |
|          hit | 1,158,922,526 | 100.0% |
|         miss | 6,480 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 121,620 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,360 | 0.0% |
|          hit | 87,102,120 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,460 | 100.0% |
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
|     deferred | 60 | 0.0% |
|          hit | 464,132 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,055,436 | 1.3% |
|          hit | 558,053,684 | 79.4% |
|         miss | 133,445,552 | 19.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,540,044 | 99.0% |
| Failure | 25,920 | 1.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 17,200 | 66.4% |
| not in dict | 7,200 | 27.8% |
| not in keys | 800 | 3.1% |
| overridden | 720 | 2.8% |


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
|     deferred | 3,766,900 | 41.1% |
|          hit | 5,401,198 | 58.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,500 | 38.9% |
| Failure | 2,360 | 61.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,720 | 72.9% |
| out of range | 640 | 27.1% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,130,900 | 3.6% |
|          hit | 524,363,108 | 95.0% |
|         miss | 7,277,397 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 196,440 | 78.0% |
| Failure | 55,340 | 22.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 25,240 | 45.6% |
| tuple | 17,740 | 32.1% |
| dict | 5,820 | 10.5% |
| other | 2,420 | 4.4% |
| set | 2,160 | 3.9% |
| mapping | 1,960 | 3.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 131,757 | 0.4% |
|          hit | 33,436,660 | 99.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,380 | 86.2% |
| Failure | 860 | 13.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 620 | 72.1% |
| iterator | 240 | 27.9% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 7,148,454,012 | 50.5% |
| Not specialized | 1,293,919,683 | 9.1% |
| Specialized hits | 5,412,515,485 | 38.3% |
| Specialized misses | 294,066,281 | 2.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 112,159,542 | 33.2% |
| CALL | 67,185,023 | 19.9% |
| COMPARE_OP | 42,863,184 | 12.7% |
| BINARY_SUBSCR | 40,259,449 | 11.9% |
| FOR_ITER | 37,810,272 | 11.2% |
| TO_BOOL | 20,130,900 | 6.0% |
| STORE_ATTR | 9,055,436 | 2.7% |
| BINARY_OP | 4,819,600 | 1.4% |
| STORE_SUBSCR | 3,766,900 | 1.1% |
| UNPACK_SEQUENCE | 131,757 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 131,665,872 | 44.8% |
| LOAD_ATTR_METHOD_NO_DICT | 57,155,628 | 19.4% |
| CALL_PY_EXACT_ARGS | 44,587,245 | 15.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,586,972 | 5.0% |
| LOAD_ATTR_SLOT | 8,296,556 | 2.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,111,020 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 5,638,120 | 1.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,525,760 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 3,825,066 | 1.3% |
| TO_BOOL_NONE | 2,650,911 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120,966,913 | 17.4% |
| Calls to Python functions inlined | 575,533,872 | 82.6% |
| Calls via PyEval_EvalFrame (total) | 120,966,913 | 17.4% |
| Calls via PyEval_EvalFrame (vector) | 106,569,153 | 15.3% |
| Calls via PyEval_EvalFrame (generator) | 14,397,760 | 2.1% |
| Calls via PyEval_EvalFrame (legacy) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 106,569,013 | 15.3% |
| Calls via PyEval_EvalFrame (build class) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,899,338 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 2,475,100 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 23,662,035 | 3.4% |
| Calls via PyEval_EvalFrame (method) | 100 | 0.0% |
| Frame objects created | 4,745,560 | 0.7% |
| Frames pushed | 487,049,289 | 69.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 307,065,772 | 28.5% |
| Frees to freelist | 307,135,788 |  |
| Allocations | 769,267,771 | 71.5% |
| Allocations to 512 bytes | 768,218,182 | 71.4% |
| Allocations to 4 kbytes | 731,489 | 0.1% |
| Allocations over 4 kbytes | 318,100 | 0.0% |
| Frees | 794,812,003 |  |
| New values | 8,867,540 |  |
| Interpreter increfs | 7,397,337,852 | 75.1% |
| Interpreter decrefs | 8,037,049,612 | 74.7% |
| Increfs | 2,457,275,883 | 24.9% |
| Decrefs | 2,721,418,731 | 25.3% |
| Materialize dict (on request) | 660 | 0.0% |
| Materialize dict (new key) | 2,300 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 400 | 0.0% |
| Method cache hits | 419,267,307 |  |
| Method cache misses | 10,292,146 |  |
| Method cache collisions | 13,349,616 |  |
| Method cache dunder hits | 354,720,080 |  |
| Method cache dunder misses | 3,308,202 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 360 | 406,300 | 860,956,240 |
| 1 | 40 | 42,188,720 | 747,080,400 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 17,380 |  |
| Traces created | 13,280 | 76.4% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 80 | 0.5% |
| Trace too long | 1,388 | 8.0% |
| Trace too short | 4,100 | 23.6% |
| Inner loop found | 239 | 1.4% |
| Recursive call | 340 | 2.0% |
| Traces executed | 100,905,492 |  |
| Uops executed | 1,909,363,129 | 18.92 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 280 | 2.1% |
| <= 32 | 5,560 | 41.9% |
| <= 64 | 3,816 | 28.7% |
| <= 128 | 3,624 | 27.3% |


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
| <= 16 | 960 | 7.2% |
| <= 32 | 5,940 | 44.7% |
| <= 64 | 3,447 | 26.0% |
| <= 128 | 2,933 | 22.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 2,277,414 | 2.3% |
| <= 4 | 0 | 0.0% |
| <= 8 | 51,634,872 | 51.2% |
| <= 16 | 22,185,523 | 22.0% |
| <= 32 | 8,051,766 | 8.0% |
| <= 64 | 12,899,891 | 12.8% |
| <= 128 | 3,508,270 | 3.5% |
| <= 256 | 115,810 | 0.1% |
| <= 512 | 148,130 | 0.1% |
| <= 1,024 | 44,436 | 0.0% |
| <= 2,048 | 8,340 | 0.0% |
| <= 4,096 | 14,720 | 0.0% |
| <= 8,192 | 15,700 | 0.0% |
| <= 16,384 | 620 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 491,956,085 | 25.8% | 25.8% |  |
| LOAD_FAST | 164,553,735 | 8.6% | 34.4% |  |
| _POP_JUMP_IF_TRUE | 144,562,815 | 7.6% | 42.0% |  |
| _ITER_CHECK_LIST | 96,693,706 | 5.1% | 47.0% | 0.6% |
| _IS_ITER_EXHAUSTED_LIST | 96,101,803 | 5.0% | 52.1% |  |
| _EXIT_TRACE | 82,862,806 | 4.3% | 56.4% |  |
| STORE_FAST | 73,716,454 | 3.9% | 60.3% |  |
| POP_TOP | 59,280,811 | 3.1% | 63.4% |  |
| _GUARD_GLOBALS_VERSION | 58,841,262 | 3.1% | 66.4% | 1.0% |
| _GUARD_TYPE_VERSION | 58,227,857 | 3.0% | 69.5% | 19.0% |
| _ITER_NEXT_LIST | 48,240,593 | 2.5% | 72.0% |  |
| LOAD_CONST | 34,988,042 | 1.8% | 73.8% |  |
| _LOAD_GLOBAL_MODULE | 30,661,948 | 1.6% | 75.5% |  |
| _GUARD_BUILTINS_VERSION | 27,577,754 | 1.4% | 76.9% |  |
| _LOAD_GLOBAL_BUILTINS | 27,577,754 | 1.4% | 78.3% |  |
| _POP_JUMP_IF_FALSE | 24,309,812 | 1.3% | 79.6% |  |
| _LOAD_ATTR_SLOT | 19,700,683 | 1.0% | 80.6% |  |
| _JUMP_TO_TOP | 18,299,684 | 1.0% | 81.6% |  |
| TO_BOOL_BOOL | 16,303,754 | 0.9% | 82.5% |  |
| CALL_ISINSTANCE | 15,538,134 | 0.8% | 83.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 15,392,117 | 0.8% | 84.1% | 10.3% |
| _CHECK_PEP_523 | 15,392,117 | 0.8% | 84.9% |  |
| _CHECK_STACK_SPACE | 13,809,577 | 0.7% | 85.6% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 13,807,977 | 0.7% | 86.3% |  |
| _PUSH_FRAME | 13,807,977 | 0.7% | 87.1% |  |
| _SAVE_RETURN_OFFSET | 13,807,977 | 0.7% | 87.8% |  |
| _ITER_CHECK_TUPLE | 13,774,110 | 0.7% | 88.5% | 12.2% |
| _LOAD_ATTR_METHOD_NO_DICT | 13,189,711 | 0.7% | 89.2% |  |
| BINARY_SUBSCR_LIST_INT | 13,062,120 | 0.7% | 89.9% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 12,088,599 | 0.6% | 90.5% |  |
| _IS_NONE | 11,711,480 | 0.6% | 91.1% |  |
| RESUME_CHECK | 11,455,617 | 0.6% | 91.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,374,771 | 0.6% | 92.3% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,374,771 | 0.6% | 92.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 9,623,900 | 0.5% | 93.4% |  |
| COMPARE_OP_STR | 8,878,220 | 0.5% | 93.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 7,293,193 | 0.4% | 94.3% | 26.0% |
| CONTAINS_OP | 6,911,830 | 0.4% | 94.6% |  |
| _ITER_CHECK_RANGE | 6,060,280 | 0.3% | 94.9% |  |
| _IS_ITER_EXHAUSTED_RANGE | 6,060,280 | 0.3% | 95.3% |  |
| _ITER_NEXT_TUPLE | 4,673,458 | 0.2% | 95.5% |  |
| COMPARE_OP_INT | 4,499,506 | 0.2% | 95.7% |  |
| PUSH_NULL | 4,076,362 | 0.2% | 96.0% |  |
| LIST_APPEND | 3,893,270 | 0.2% | 96.2% |  |
| _GUARD_BOTH_INT | 3,752,458 | 0.2% | 96.4% |  |
| TO_BOOL_NONE | 3,551,220 | 0.2% | 96.5% | 4.8% |
| _ITER_NEXT_RANGE | 3,510,520 | 0.2% | 96.7% |  |
| _BINARY_OP_SUBTRACT_INT | 3,261,796 | 0.2% | 96.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,951,720 | 0.2% | 97.1% |  |
| _LOAD_ATTR | 2,942,100 | 0.2% | 97.2% |  |
| _CHECK_ATTR_MODULE | 2,933,514 | 0.2% | 97.4% |  |
| _LOAD_ATTR_MODULE | 2,933,514 | 0.2% | 97.5% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 2,812,700 | 0.1% | 97.7% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 2,812,700 | 0.1% | 97.8% |  |
| _GUARD_BOTH_UNICODE | 2,725,080 | 0.1% | 97.9% |  |
| _BINARY_OP_ADD_UNICODE | 2,725,080 | 0.1% | 98.1% |  |
| SET_ADD | 2,683,780 | 0.1% | 98.2% |  |
| BUILD_LIST | 2,531,228 | 0.1% | 98.4% |  |
| LOAD_DEREF | 2,416,481 | 0.1% | 98.5% |  |
| TO_BOOL_STR | 2,277,840 | 0.1% | 98.6% |  |
| CALL_STR_1 | 2,266,520 | 0.1% | 98.7% |  |
| CALL_BUILTIN_O | 2,261,700 | 0.1% | 98.8% |  |
| _GUARD_KEYS_VERSION | 2,258,700 | 0.1% | 99.0% | 9.9% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,258,700 | 0.1% | 99.1% |  |
| BINARY_SUBSCR_DICT | 2,179,675 | 0.1% | 99.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,963,080 | 0.1% | 99.3% |  |
| CALL_BUILTIN_FAST | 1,435,622 | 0.1% | 99.4% |  |
| _POP_FRAME | 1,382,444 | 0.1% | 99.4% |  |
| GET_ITER | 1,148,740 | 0.1% | 99.5% |  |
| TO_BOOL_LIST | 742,060 | 0.0% | 99.5% |  |
| FORMAT_SIMPLE | 653,360 | 0.0% | 99.6% |  |
| CALL_LEN | 609,520 | 0.0% | 99.6% |  |
| _BINARY_SUBSCR | 557,091 | 0.0% | 99.6% |  |
| BUILD_STRING | 530,220 | 0.0% | 99.7% |  |
| _BINARY_OP_ADD_INT | 490,662 | 0.0% | 99.7% |  |
| CALL_TYPE_1 | 481,300 | 0.0% | 99.7% |  |
| _STORE_ATTR_SLOT | 450,820 | 0.0% | 99.7% |  |
| IS_OP | 433,860 | 0.0% | 99.8% |  |
| SWAP | 414,020 | 0.0% | 99.8% |  |
| UNARY_NOT | 332,860 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 330,900 | 0.0% | 99.8% | 0.0% |
| BUILD_TUPLE | 305,277 | 0.0% | 99.8% |  |
| STORE_SUBSCR_DICT | 290,262 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 270,240 | 0.0% | 99.9% |  |
| BUILD_MAP | 219,180 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 209,720 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 198,020 | 0.0% | 99.9% |  |
| COPY | 158,622 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 152,435 | 0.0% | 99.9% |  |
| _CHECK_ATTR_WITH_HINT | 151,820 | 0.0% | 99.9% |  |
| _LOAD_ATTR_WITH_HINT | 151,820 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 136,480 | 0.0% | 99.9% |  |
| _COMPARE_OP | 132,120 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 105,560 | 0.0% | 100.0% | 91.8% |
| COPY_FREE_VARS | 93,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 83,060 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 78,040 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 72,260 | 0.0% | 100.0% |  |
| BINARY_SLICE | 67,020 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 60,380 | 0.0% | 100.0% | 93.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 57,180 | 0.0% | 100.0% | 70.2% |
| CALL_METHOD_DESCRIPTOR_O | 55,433 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 54,940 | 0.0% | 100.0% |  |
| _BINARY_OP | 49,000 | 0.0% | 100.0% |  |
| MAKE_CELL | 42,780 | 0.0% | 100.0% |  |
| STORE_DEREF | 38,780 | 0.0% | 100.0% |  |
| _TO_BOOL | 19,500 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 17,620 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 13,560 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 13,560 | 0.0% | 100.0% |  |
| MAP_ADD | 8,880 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 8,480 | 0.0% | 100.0% |  |
| BUILD_SET | 7,060 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 6,763 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 4,980 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 4,120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 2,020 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,660 | 0.0% | 100.0% |  |
| _STORE_SUBSCR | 1,180 | 0.0% | 100.0% |  |
| _STORE_ATTR | 840 | 0.0% | 100.0% |  |
| UNARY_INVERT | 600 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 540 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 4,160 |
| CALL | 1,613 |
| CALL_LIST_APPEND | 819 |
| LOAD_ATTR_PROPERTY | 760 |
| CALL_KW | 680 |
| YIELD_VALUE | 680 |
| CALL_PY_WITH_DEFAULTS | 580 |
| CALL_ALLOC_AND_ENTER_INIT | 160 |
| FOR_ITER_GEN | 160 |
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
Stats gathered on: 2023-11-08
