
# Pystats results

- benchmark: docutils
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,600,265,820 | 19.8% | 19.8% |  |
| STORE_FAST | 440,791,980 | 5.5% | 25.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 346,109,360 | 4.3% | 29.6% | 30.3% |
| RESUME_CHECK | 317,235,900 | 3.9% | 33.5% | 0.0% |
| LOAD_FAST_LOAD_FAST | 296,011,980 | 3.7% | 37.2% |  |
| LOAD_CONST | 284,155,440 | 3.5% | 40.7% |  |
| POP_JUMP_IF_FALSE | 254,306,220 | 3.2% | 43.9% |  |
| LOAD_GLOBAL_BUILTIN | 225,920,360 | 2.8% | 46.7% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 209,122,700 | 2.6% | 49.3% | 41.6% |
| JUMP_BACKWARD | 207,255,960 | 2.6% | 51.8% |  |
| CALL_PY_EXACT_ARGS | 195,337,560 | 2.4% | 54.3% | 4.9% |
| POP_TOP | 175,807,360 | 2.2% | 56.4% |  |
| TO_BOOL_BOOL | 168,887,380 | 2.1% | 58.5% | 0.0% |
| FOR_ITER_LIST | 165,725,740 | 2.1% | 60.6% | 11.4% |
| RETURN_CONST | 162,590,280 | 2.0% | 62.6% |  |
| LOAD_ATTR | 149,367,140 | 1.9% | 64.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 147,552,280 | 1.8% | 66.3% | 0.8% |
| RETURN_VALUE | 147,129,760 | 1.8% | 68.1% |  |
| POP_JUMP_IF_TRUE | 132,726,660 | 1.6% | 69.8% |  |
| GET_ITER | 122,971,560 | 1.5% | 71.3% |  |
| NOP | 120,478,680 | 1.5% | 72.8% |  |
| CALL_ISINSTANCE | 94,505,220 | 1.2% | 74.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 93,436,260 | 1.2% | 75.1% | 57.7% |
| LOAD_GLOBAL_MODULE | 93,208,920 | 1.2% | 76.3% | 0.0% |
| LOAD_ATTR_WITH_HINT | 85,900,560 | 1.1% | 77.3% | 1.2% |
| FOR_ITER_TUPLE | 69,350,540 | 0.9% | 78.2% | 27.2% |
| CALL_BUILTIN_FAST | 67,752,060 | 0.8% | 79.0% |  |
| CONTAINS_OP | 66,540,780 | 0.8% | 79.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 66,467,080 | 0.8% | 80.7% | 70.9% |
| TO_BOOL_NONE | 64,928,880 | 0.8% | 81.5% | 9.5% |
| CALL | 61,696,920 | 0.8% | 82.3% |  |
| PUSH_NULL | 60,592,800 | 0.8% | 83.0% |  |
| BUILD_LIST | 59,123,280 | 0.7% | 83.7% |  |
| POP_JUMP_IF_NOT_NONE | 58,020,540 | 0.7% | 84.5% |  |
| BINARY_SUBSCR_DICT | 50,369,160 | 0.6% | 85.1% |  |
| STORE_FAST_STORE_FAST | 48,253,800 | 0.6% | 85.7% |  |
| FOR_ITER | 45,340,760 | 0.6% | 86.2% |  |
| LOAD_ATTR_SLOT | 44,243,100 | 0.5% | 86.8% | 79.8% |
| STORE_SUBSCR_DICT | 41,723,820 | 0.5% | 87.3% |  |
| FOR_ITER_GEN | 41,703,600 | 0.5% | 87.8% |  |
| CALL_LIST_APPEND | 41,464,300 | 0.5% | 88.3% | 0.1% |
| INTERPRETER_EXIT | 39,027,960 | 0.5% | 88.8% |  |
| BUILD_TUPLE | 37,434,900 | 0.5% | 89.3% |  |
| RETURN_GENERATOR | 37,113,120 | 0.5% | 89.8% |  |
| END_FOR | 36,887,100 | 0.5% | 90.2% |  |
| FORMAT_SIMPLE | 30,225,960 | 0.4% | 90.6% |  |
| CONVERT_VALUE | 30,207,900 | 0.4% | 91.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,160,980 | 0.4% | 91.3% |  |
| CALL_LEN | 29,646,600 | 0.4% | 91.7% |  |
| LOAD_ATTR_MODULE | 28,793,580 | 0.4% | 92.1% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 27,224,860 | 0.3% | 92.4% | 0.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 25,295,160 | 0.3% | 92.7% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 24,100,920 | 0.3% | 93.0% |  |
| BINARY_OP_ADD_INT | 22,797,360 | 0.3% | 93.3% |  |
| COMPARE_OP_INT | 22,288,980 | 0.3% | 93.6% | 0.1% |
| BINARY_SUBSCR_LIST_INT | 22,014,320 | 0.3% | 93.8% | 9.8% |
| STORE_ATTR | 22,003,820 | 0.3% | 94.1% |  |
| BINARY_SLICE | 21,448,800 | 0.3% | 94.4% |  |
| BINARY_OP | 21,067,920 | 0.3% | 94.6% |  |
| LIST_APPEND | 20,213,100 | 0.3% | 94.9% |  |
| BINARY_OP_ADD_UNICODE | 19,374,960 | 0.2% | 95.1% |  |
| COPY | 19,121,700 | 0.2% | 95.4% |  |
| UNPACK_SEQUENCE_TUPLE | 18,026,320 | 0.2% | 95.6% | 0.0% |
| CALL_BUILTIN_O | 17,482,140 | 0.2% | 95.8% |  |
| SWAP | 17,143,200 | 0.2% | 96.0% |  |
| TO_BOOL_INT | 16,955,460 | 0.2% | 96.2% | 1.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 15,341,220 | 0.2% | 96.4% |  |
| LOAD_ATTR_CLASS | 15,286,960 | 0.2% | 96.6% | 7.1% |
| TO_BOOL_STR | 15,145,240 | 0.2% | 96.8% | 4.3% |
| BUILD_STRING | 15,106,200 | 0.2% | 97.0% |  |
| BUILD_MAP | 14,712,660 | 0.2% | 97.2% |  |
| STORE_FAST_LOAD_FAST | 14,345,700 | 0.2% | 97.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 14,047,380 | 0.2% | 97.5% | 12.5% |
| COMPARE_OP_STR | 12,747,760 | 0.2% | 97.7% | 1.9% |
| CALL_FUNCTION_EX | 11,631,900 | 0.1% | 97.8% |  |
| TO_BOOL_LIST | 11,374,260 | 0.1% | 98.0% | 9.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 9,937,380 | 0.1% | 98.1% | 45.3% |
| BINARY_SUBSCR_TUPLE_INT | 8,653,560 | 0.1% | 98.2% |  |
| BINARY_SUBSCR_GETITEM | 8,354,400 | 0.1% | 98.3% | 0.1% |
| POP_JUMP_IF_NONE | 8,068,680 | 0.1% | 98.4% |  |
| STORE_ATTR_WITH_HINT | 7,613,400 | 0.1% | 98.5% | 0.0% |
| CALL_STR_1 | 7,151,640 | 0.1% | 98.6% |  |
| BINARY_SUBSCR_STR_INT | 6,734,080 | 0.1% | 98.7% | 0.1% |
| JUMP_FORWARD | 6,557,460 | 0.1% | 98.7% |  |
| PUSH_EXC_INFO | 6,134,820 | 0.1% | 98.8% |  |
| POP_EXCEPT | 6,134,820 | 0.1% | 98.9% |  |
| LOAD_ATTR_PROPERTY | 5,895,920 | 0.1% | 99.0% | 68.6% |
| CHECK_EXC_MATCH | 5,778,720 | 0.1% | 99.0% |  |
| CALL_BUILTIN_CLASS | 5,726,400 | 0.1% | 99.1% |  |
| BINARY_OP_SUBTRACT_INT | 5,440,860 | 0.1% | 99.2% |  |
| TO_BOOL_ALWAYS_TRUE | 5,146,980 | 0.1% | 99.2% | 62.8% |
| YIELD_VALUE | 4,946,760 | 0.1% | 99.3% |  |
| CALL_KW | 4,656,420 | 0.1% | 99.4% |  |
| CALL_TYPE_1 | 4,194,360 | 0.1% | 99.4% |  |
| TO_BOOL | 3,998,940 | 0.0% | 99.5% |  |
| STORE_SLICE | 3,974,040 | 0.0% | 99.5% |  |
| FOR_ITER_RANGE | 3,461,940 | 0.0% | 99.6% |  |
| DICT_MERGE | 3,461,880 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 2,779,860 | 0.0% | 99.6% |  |
| LIST_EXTEND | 2,731,500 | 0.0% | 99.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 2,694,500 | 0.0% | 99.7% | 63.3% |
| LOAD_FAST_AND_CLEAR | 2,480,940 | 0.0% | 99.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,220,720 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 1,885,920 | 0.0% | 99.8% |  |
| BUILD_CONST_KEY_MAP | 1,876,560 | 0.0% | 99.8% |  |
| EXTENDED_ARG | 1,788,780 | 0.0% | 99.8% |  |
| COMPARE_OP | 1,693,320 | 0.0% | 99.9% |  |
| RERAISE | 1,465,320 | 0.0% | 99.9% |  |
| RAISE_VARARGS | 1,175,460 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 1,169,960 | 0.0% | 99.9% |  |
| EXIT_INIT_CHECK | 988,840 | 0.0% | 99.9% |  |
| LOAD_DEREF | 904,140 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 879,600 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 840,600 | 0.0% | 99.9% | 0.3% |
| COPY_FREE_VARS | 823,860 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 787,980 | 0.0% | 100.0% |  |
| IS_OP | 637,440 | 0.0% | 100.0% |  |
| BUILD_SLICE | 443,220 | 0.0% | 100.0% |  |
| UNARY_NOT | 361,260 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 331,920 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 230,880 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 228,360 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 176,880 | 0.0% | 100.0% |  |
| MAKE_CELL | 156,300 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 104,980 | 0.0% | 100.0% | 1.5% |
| LOAD_SUPER_ATTR_METHOD | 75,960 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 73,620 | 0.0% | 100.0% |  |
| MAP_ADD | 49,980 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 21,840 | 0.0% | 100.0% |  |
| IMPORT_NAME | 14,700 | 0.0% | 100.0% |  |
| STORE_DEREF | 10,920 | 0.0% | 100.0% |  |
| UNARY_INVERT | 8,820 | 0.0% | 100.0% |  |
| BEFORE_WITH | 7,320 | 0.0% | 100.0% |  |
| IMPORT_FROM | 5,880 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 4,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,780 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 3,660 | 0.0% | 100.0% |  |
| RESUME | 3,420 | 0.0% | 100.0% | 722.2% |
| DELETE_ATTR | 3,360 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 2,940 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 2,940 | 0.0% | 100.0% | 2.0% |
| LOAD_GLOBAL | 1,920 | 0.0% | 100.0% |  |
| DELETE_FAST | 780 | 0.0% | 100.0% |  |
| STORE_NAME | 540 | 0.0% | 100.0% |  |
| LOAD_NAME | 300 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 260 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 180 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 286,511,980 | 3.6% | 3.6% |
| STORE_FAST LOAD_FAST | 209,349,300 | 2.6% | 6.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 162,690,040 | 2.0% | 8.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 157,197,040 | 1.9% | 10.1% |
| RESUME_CHECK LOAD_FAST | 145,573,020 | 1.8% | 11.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 142,716,300 | 1.8% | 13.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 125,967,000 | 1.6% | 15.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 120,574,140 | 1.5% | 16.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 118,816,700 | 1.5% | 18.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 115,746,120 | 1.4% | 19.7% |
| JUMP_BACKWARD FOR_ITER_LIST | 107,588,980 | 1.3% | 21.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 100,557,800 | 1.2% | 22.2% |
| FOR_ITER_LIST STORE_FAST | 96,575,680 | 1.2% | 23.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 93,413,760 | 1.2% | 24.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 92,009,460 | 1.1% | 25.7% |
| LOAD_FAST LOAD_ATTR | 90,635,800 | 1.1% | 26.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 89,740,480 | 1.1% | 28.0% |
| RETURN_CONST POP_TOP | 84,716,580 | 1.1% | 29.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 84,057,840 | 1.0% | 30.1% |
| LOAD_FAST LOAD_CONST | 81,135,840 | 1.0% | 31.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 72,388,720 | 0.9% | 32.0% |
| NOP LOAD_FAST | 70,428,780 | 0.9% | 32.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 68,702,220 | 0.9% | 33.7% |
| LOAD_CONST LOAD_FAST | 65,755,080 | 0.8% | 34.5% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 64,514,840 | 0.8% | 35.3% |
| POP_TOP LOAD_FAST | 63,859,600 | 0.8% | 36.1% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 61,657,320 | 0.8% | 36.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 61,385,540 | 0.8% | 37.6% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 60,225,440 | 0.7% | 38.4% |
| LOAD_FAST_LOAD_FAST CALL_ISINSTANCE | 56,935,080 | 0.7% | 39.1% |
| GET_ITER FOR_ITER_LIST | 56,407,660 | 0.7% | 39.8% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 53,115,260 | 0.7% | 40.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 49,989,740 | 0.6% | 41.1% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 49,224,860 | 0.6% | 41.7% |
| FOR_ITER_TUPLE STORE_FAST | 48,528,440 | 0.6% | 42.3% |
| PUSH_NULL LOAD_FAST | 48,258,840 | 0.6% | 42.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 47,853,420 | 0.6% | 43.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 46,955,600 | 0.6% | 44.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 44,009,500 | 0.5% | 44.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 43,559,160 | 0.5% | 45.1% |
| LOAD_ATTR_SLOT LOAD_ATTR | 42,337,740 | 0.5% | 45.7% |
| LOAD_FAST BINARY_SUBSCR_DICT | 41,863,920 | 0.5% | 46.2% |
| CACHE RESUME_CHECK | 39,861,360 | 0.5% | 46.7% |
| JUMP_BACKWARD FOR_ITER | 37,120,620 | 0.5% | 47.1% |
| POP_TOP RESUME_CHECK | 37,113,120 | 0.5% | 47.6% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 36,963,540 | 0.5% | 48.0% |
| FOR_ITER_GEN POP_TOP | 36,917,820 | 0.5% | 48.5% |
| RETURN_GENERATOR GET_ITER | 36,917,340 | 0.5% | 49.0% |
| GET_ITER FOR_ITER_GEN | 36,914,160 | 0.5% | 49.4% |
| RETURN_CONST END_FOR | 36,887,100 | 0.5% | 49.9% |
| END_FOR JUMP_BACKWARD | 36,786,240 | 0.5% | 50.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 36,754,080 | 0.5% | 50.8% |
| POP_JUMP_IF_FALSE RETURN_CONST | 34,939,800 | 0.4% | 51.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 34,597,160 | 0.4% | 51.7% |
| FOR_ITER_LIST RETURN_CONST | 34,441,920 | 0.4% | 52.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 34,351,440 | 0.4% | 52.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 32,935,140 | 0.4% | 52.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 32,884,600 | 0.4% | 53.3% |
| LOAD_ATTR STORE_FAST | 32,115,180 | 0.4% | 53.7% |
| CALL_BUILTIN_FAST STORE_FAST | 32,105,340 | 0.4% | 54.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 32,046,680 | 0.4% | 54.5% |
| BUILD_TUPLE RETURN_VALUE | 31,696,080 | 0.4% | 54.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 31,454,760 | 0.4% | 55.3% |
| STORE_FAST NOP | 30,959,640 | 0.4% | 55.7% |
| POP_TOP JUMP_BACKWARD | 30,768,120 | 0.4% | 56.1% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 30,261,540 | 0.4% | 56.4% |
| CONVERT_VALUE FORMAT_SIMPLE | 30,207,900 | 0.4% | 56.8% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 30,182,640 | 0.4% | 57.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_CONST | 29,684,620 | 0.4% | 57.6% |
| LOAD_FAST CALL_LIST_APPEND | 29,455,880 | 0.4% | 57.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 29,411,280 | 0.4% | 58.3% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 29,266,360 | 0.4% | 58.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 29,125,680 | 0.4% | 59.0% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 28,740,240 | 0.4% | 59.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 28,675,400 | 0.4% | 59.7% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 28,509,720 | 0.4% | 60.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 27,183,180 | 0.3% | 60.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 25,987,780 | 0.3% | 60.7% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 25,942,680 | 0.3% | 61.1% |
| BUILD_LIST LOAD_FAST | 25,463,340 | 0.3% | 61.4% |
| LOAD_CONST LOAD_CONST | 25,339,500 | 0.3% | 61.7% |
| LOAD_ATTR LOAD_FAST | 24,907,380 | 0.3% | 62.0% |
| LOAD_CONST STORE_FAST | 24,632,580 | 0.3% | 62.3% |
| LOAD_FAST BUILD_TUPLE | 24,471,060 | 0.3% | 62.6% |
| CALL RESUME_CHECK | 24,128,080 | 0.3% | 62.9% |
| CALL_LIST_APPEND JUMP_BACKWARD | 23,904,480 | 0.3% | 63.2% |
| LOAD_FAST PUSH_NULL | 23,799,360 | 0.3% | 63.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 23,403,680 | 0.3% | 63.8% |
| STORE_FAST BUILD_LIST | 23,341,740 | 0.3% | 64.1% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_WITH_VALUES | 23,209,420 | 0.3% | 64.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST | 22,852,200 | 0.3% | 64.6% |
| CALL STORE_FAST | 22,729,220 | 0.3% | 64.9% |
| STORE_SUBSCR_DICT LOAD_FAST | 22,528,080 | 0.3% | 65.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 22,493,700 | 0.3% | 65.5% |
| RETURN_VALUE STORE_FAST | 22,247,340 | 0.3% | 65.8% |
| STORE_ATTR_INSTANCE_VALUE NOP | 22,151,220 | 0.3% | 66.0% |
| NOP LOAD_GLOBAL_BUILTIN | 21,623,740 | 0.3% | 66.3% |
| LOAD_FAST RETURN_VALUE | 21,493,020 | 0.3% | 66.6% |
| BINARY_SUBSCR_DICT STORE_FAST | 21,096,300 | 0.3% | 66.8% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 21,061,180 | 0.3% | 67.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,227,240 | 61.7% |
| BINARY_OP_ADD_INT | 2,907,240 | 13.6% |
| LOAD_FAST | 2,287,320 | 10.7% |
| LOAD_ATTR | 2,053,260 | 9.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 476,940 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,043,780 | 37.5% |
| RETURN_VALUE | 3,030,120 | 14.1% |
| LOAD_FAST | 2,578,140 | 12.0% |
| LIST_APPEND | 1,427,940 | 6.7% |
| STORE_FAST | 1,196,400 | 5.6% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,706,920 | 93.3% |
| LOAD_FAST_LOAD_FAST | 258,360 | 6.5% |
| LOAD_ATTR | 8,040 | 0.2% |
| BINARY_OP_ADD_INT | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,701,940 | 93.2% |
| RETURN_CONST | 268,380 | 6.8% |
| LOAD_GLOBAL_BUILTIN | 2,700 | 0.1% |
| LOAD_CONST | 540 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 39,861,360 | 99.4% |
| POP_TOP | 195,300 | 0.5% |
| CALL_INTRINSIC_1 | 51,420 | 0.1% |
| COPY_FREE_VARS | 9,600 | 0.0% |
| RESUME | 3,420 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,380 | 59.8% |
| CALL | 2,940 | 40.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,380 | 59.8% |
| POP_TOP | 2,940 | 40.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 531,360 | 67.4% |
| LOAD_FAST_LOAD_FAST | 162,420 | 20.6% |
| CALL_FUNCTION_EX | 60,360 | 7.7% |
| BINARY_OP_ADD_UNICODE | 17,700 | 2.2% |
| LOAD_CONST | 10,980 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 695,520 | 88.3% |
| LOAD_CONST | 60,360 | 7.7% |
| JUMP_BACKWARD | 19,920 | 2.5% |
| LOAD_GLOBAL_MODULE | 8,820 | 1.1% |
| LOAD_FAST_LOAD_FAST | 2,940 | 0.4% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 834,480 | 71.3% |
| COPY | 138,320 | 11.8% |
| LOAD_FAST | 112,560 | 9.6% |
| COMPARE_OP_STR | 76,440 | 6.5% |
| BINARY_SUBSCR_LIST_INT | 4,900 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 670,680 | 57.3% |
| LOAD_CONST | 174,480 | 14.9% |
| BUILD_TUPLE | 101,340 | 8.7% |
| LOAD_ATTR_METHOD_NO_DICT | 83,940 | 7.2% |
| STORE_FAST | 77,160 | 6.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,049,600 | 87.4% |
| LOAD_GLOBAL_MODULE | 381,660 | 6.6% |
| BUILD_TUPLE | 325,500 | 5.6% |
| LOAD_ATTR_MODULE | 21,960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,778,720 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 991,800 | 52.6% |
| BUILD_SLICE | 443,220 | 23.5% |
| LOAD_CONST | 233,100 | 12.4% |
| LOAD_FAST | 217,800 | 11.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 981,960 | 52.1% |
| LOAD_FAST | 381,420 | 20.2% |
| RETURN_CONST | 308,760 | 16.4% |
| LOAD_FAST_LOAD_FAST | 208,140 | 11.0% |
| LOAD_CONST | 2,940 | 0.2% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 36,887,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 36,786,240 | 99.7% |
| RETURN_CONST | 92,520 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 4,200 | 0.0% |
| LOAD_FAST | 3,120 | 0.0% |
| NOP | 660 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 988,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 988,840 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 30,207,900 | 99.9% |
| LOAD_FAST | 18,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,513,980 | 54.6% |
| BUILD_STRING | 11,595,060 | 38.4% |
| LOAD_FAST | 2,108,100 | 7.0% |
| LOAD_GLOBAL_MODULE | 8,820 | 0.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 36,917,340 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 28,509,720 | 23.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 19,275,920 | 15.7% |
| LOAD_FAST | 16,501,740 | 13.4% |
| BINARY_SLICE | 8,043,780 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 56,407,660 | 45.9% |
| FOR_ITER_GEN | 36,914,160 | 30.0% |
| FOR_ITER_TUPLE | 19,472,660 | 15.8% |
| FOR_ITER | 7,413,300 | 6.0% |
| LOAD_FAST_AND_CLEAR | 2,222,880 | 1.8% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,031,620 | 51.3% |
| RETURN_CONST | 18,866,080 | 48.3% |
| YIELD_VALUE | 130,260 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FROM_DICT_OR_DEREF | 180 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 331,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 228,360 | 68.8% |
| LOAD_FAST | 103,200 | 31.1% |
| LOAD_FAST_CHECK | 360 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,959,640 | 25.7% |
| STORE_ATTR_INSTANCE_VALUE | 22,151,220 | 18.4% |
| POP_JUMP_IF_TRUE | 20,618,520 | 17.1% |
| RESUME_CHECK | 14,513,280 | 12.0% |
| NOP | 14,252,340 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,428,780 | 58.5% |
| LOAD_GLOBAL_BUILTIN | 21,623,740 | 17.9% |
| NOP | 14,252,340 | 11.8% |
| LOAD_FAST_LOAD_FAST | 5,439,300 | 4.5% |
| BUILD_LIST | 3,483,960 | 2.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,152,540 | 67.7% |
| COPY | 922,200 | 15.0% |
| SWAP | 911,040 | 14.9% |
| STORE_FAST | 139,080 | 2.3% |
| CALL_LIST_APPEND | 9,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,618,960 | 59.0% |
| RERAISE | 922,200 | 15.0% |
| RETURN_VALUE | 911,040 | 14.9% |
| EXTENDED_ARG | 596,280 | 9.7% |
| JUMP_BACKWARD | 69,780 | 1.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 84,716,580 | 48.2% |
| FOR_ITER_GEN | 36,917,820 | 21.0% |
| RETURN_VALUE | 15,248,400 | 8.7% |
| POP_JUMP_IF_FALSE | 7,313,400 | 4.2% |
| CALL | 5,491,740 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 63,859,600 | 36.3% |
| RESUME_CHECK | 37,113,120 | 21.1% |
| JUMP_BACKWARD | 30,768,120 | 17.5% |
| RETURN_CONST | 14,169,000 | 8.1% |
| NOP | 10,521,600 | 6.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,246,180 | 52.9% |
| RERAISE | 922,200 | 15.0% |
| BINARY_SUBSCR_LIST_INT | 814,620 | 13.3% |
| RAISE_VARARGS | 753,540 | 12.3% |
| CALL | 229,020 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,058,460 | 82.5% |
| LOAD_GLOBAL_MODULE | 698,360 | 11.4% |
| LOAD_FAST | 377,940 | 6.2% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,799,360 | 39.3% |
| LOAD_ATTR_MODULE | 19,695,400 | 32.5% |
| LOAD_ATTR | 8,403,140 | 13.9% |
| LOAD_ATTR_CLASS | 8,282,760 | 13.7% |
| LOAD_ATTR_INSTANCE_VALUE | 289,980 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,258,840 | 79.6% |
| LOAD_FAST_LOAD_FAST | 9,648,720 | 15.9% |
| LOAD_CONST | 1,615,740 | 2.7% |
| CALL_PY_EXACT_ARGS | 653,040 | 1.1% |
| CALL | 306,660 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 36,963,540 | 99.6% |
| CALL_KW | 118,560 | 0.3% |
| CALL_PY_WITH_DEFAULTS | 31,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 36,917,340 | 99.5% |
| CALL_METHOD_DESCRIPTOR_O | 100,260 | 0.3% |
| CALL_BUILTIN_FAST | 86,220 | 0.2% |
| CALL_TUPLE_1 | 2,940 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,940 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 31,696,080 | 21.5% |
| LOAD_FAST | 21,493,020 | 14.6% |
| RETURN_CONST | 15,188,380 | 10.3% |
| BINARY_SUBSCR_LIST_INT | 11,448,000 | 7.8% |
| BINARY_SUBSCR_DICT | 7,969,560 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,247,340 | 15.1% |
| TO_BOOL_BOOL | 20,888,960 | 14.2% |
| INTERPRETER_EXIT | 20,031,620 | 13.6% |
| LOAD_FAST_LOAD_FAST | 16,723,500 | 11.4% |
| POP_TOP | 15,248,400 | 10.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 716,520 | 81.5% |
| SWAP | 146,200 | 16.6% |
| LOAD_FAST | 11,500 | 1.3% |
| STORE_SUBSCR | 2,500 | 0.3% |
| LOAD_FAST_LOAD_FAST | 2,100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 428,260 | 48.7% |
| LOAD_CONST | 228,600 | 26.0% |
| JUMP_FORWARD | 140,160 | 15.9% |
| JUMP_BACKWARD | 33,840 | 3.8% |
| BUILD_LIST | 19,860 | 2.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,859,940 | 46.5% |
| COPY | 1,164,320 | 29.1% |
| LOAD_ATTR_INSTANCE_VALUE | 507,580 | 12.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 183,240 | 4.6% |
| TO_BOOL | 94,880 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,534,300 | 63.4% |
| POP_JUMP_IF_TRUE | 1,297,180 | 32.4% |
| TO_BOOL | 94,880 | 2.4% |
| TO_BOOL_NONE | 51,780 | 1.3% |
| TO_BOOL_LIST | 20,120 | 0.5% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 8,820 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 176,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 176,880 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 323,040 | 89.4% |
| TO_BOOL_BOOL | 38,220 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 316,800 | 87.7% |
| RETURN_VALUE | 43,380 | 12.0% |
| BUILD_TUPLE | 1,080 | 0.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 11,580,660 | 55.0% |
| LOAD_FAST | 2,739,320 | 13.0% |
| RETURN_VALUE | 2,249,100 | 10.7% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,010,960 | 9.5% |
| LOAD_FAST_LOAD_FAST | 1,127,880 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 11,609,480 | 55.1% |
| STORE_FAST | 4,342,740 | 20.6% |
| GET_ITER | 2,421,720 | 11.5% |
| SWAP | 1,295,580 | 6.1% |
| LOAD_FAST | 623,160 | 3.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,876,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,819,620 | 97.0% |
| STORE_FAST | 46,800 | 2.5% |
| LOAD_CONST | 10,140 | 0.5% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,341,740 | 39.5% |
| LOAD_CONST | 10,022,700 | 17.0% |
| RESUME_CHECK | 6,965,100 | 11.8% |
| LOAD_FAST | 5,339,100 | 9.0% |
| NOP | 3,483,960 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,463,340 | 43.1% |
| STORE_FAST | 15,326,580 | 25.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,385,660 | 7.4% |
| CALL_PY_EXACT_ARGS | 4,039,140 | 6.8% |
| BUILD_TUPLE | 2,768,520 | 4.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,591,460 | 38.0% |
| POP_TOP | 2,429,100 | 16.5% |
| NOP | 1,937,520 | 13.2% |
| CALL_INTRINSIC_1 | 1,848,660 | 12.6% |
| LOAD_CONST | 889,680 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,852,920 | 53.4% |
| STORE_FAST | 6,363,840 | 43.3% |
| CALL_BUILTIN_FAST | 361,920 | 2.5% |
| BUILD_TUPLE | 66,240 | 0.5% |
| CALL_FUNCTION_EX | 61,800 | 0.4% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 263,400 | 59.4% |
| LOAD_CONST | 179,820 | 40.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 443,220 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 11,595,060 | 76.8% |
| LOAD_CONST | 3,511,140 | 23.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 11,581,020 | 76.7% |
| BINARY_OP_ADD_UNICODE | 2,010,960 | 13.3% |
| CALL_LIST_APPEND | 1,398,120 | 9.3% |
| STORE_FAST | 112,320 | 0.7% |
| LIST_APPEND | 3,660 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,471,060 | 65.4% |
| LOAD_FAST_LOAD_FAST | 7,453,320 | 19.9% |
| BUILD_LIST | 2,768,520 | 7.4% |
| LOAD_CONST | 958,920 | 2.6% |
| LOAD_ATTR_MODULE | 711,180 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 31,696,080 | 84.7% |
| LIST_APPEND | 2,241,360 | 6.0% |
| CALL_ISINSTANCE | 751,620 | 2.0% |
| BUILD_MAP | 654,360 | 1.7% |
| BINARY_SUBSCR_DICT | 570,720 | 1.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 14,300,060 | 23.2% |
| LOAD_FAST | 13,131,400 | 21.3% |
| BINARY_OP | 11,609,480 | 18.8% |
| BUILD_STRING | 11,581,020 | 18.8% |
| LOAD_CONST | 3,515,640 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 24,128,080 | 39.1% |
| STORE_FAST | 22,729,220 | 36.8% |
| POP_TOP | 5,491,740 | 8.9% |
| RETURN_VALUE | 2,292,180 | 3.7% |
| LOAD_FAST | 1,477,560 | 2.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,311,000 | 62.9% |
| DICT_MERGE | 3,461,880 | 29.8% |
| CALL_INTRINSIC_1 | 794,280 | 6.8% |
| BUILD_MAP | 61,800 | 0.5% |
| MAP_ADD | 2,940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,815,580 | 32.8% |
| POP_TOP | 3,473,100 | 29.9% |
| RESUME_CHECK | 1,826,760 | 15.7% |
| STORE_FAST | 1,791,480 | 15.4% |
| CALL_LIST_APPEND | 453,560 | 3.9% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 2,728,440 | 98.2% |
| CACHE | 51,420 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 1,848,660 | 66.5% |
| CALL_FUNCTION_EX | 794,280 | 28.6% |
| LOAD_CONST | 61,800 | 2.2% |
| RERAISE | 51,420 | 1.8% |
| LOAD_FAST | 20,760 | 0.7% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,656,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,100,500 | 66.6% |
| RETURN_VALUE | 1,010,940 | 21.7% |
| STORE_FAST | 393,900 | 8.5% |
| RETURN_GENERATOR | 118,560 | 2.5% |
| LOAD_FAST | 17,640 | 0.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,034,680 | 61.1% |
| BUILD_LIST | 519,300 | 30.7% |
| LOAD_FAST_LOAD_FAST | 113,340 | 6.7% |
| LOAD_ATTR_INSTANCE_VALUE | 12,200 | 0.7% |
| COMPARE_OP | 8,020 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,139,920 | 67.3% |
| POP_JUMP_IF_TRUE | 540,140 | 31.9% |
| COMPARE_OP | 8,020 | 0.5% |
| COMPARE_OP_STR | 4,760 | 0.3% |
| COMPARE_OP_INT | 480 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 28,740,240 | 43.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,942,680 | 39.0% |
| LOAD_CONST | 3,640,440 | 5.5% |
| LOAD_FAST | 3,021,060 | 4.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,229,600 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,351,440 | 51.6% |
| POP_JUMP_IF_TRUE | 30,261,540 | 45.5% |
| RETURN_VALUE | 1,647,840 | 2.5% |
| COPY | 279,300 | 0.4% |
| EXTENDED_ARG | 660 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,635,840 | 45.1% |
| LOAD_ATTR | 11,580,660 | 38.3% |
| CALL_METHOD_DESCRIPTOR_O | 2,010,960 | 6.7% |
| RETURN_VALUE | 1,416,480 | 4.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,385,580 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 30,207,900 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,739,640 | 40.5% |
| LOAD_ATTR | 6,964,980 | 36.4% |
| BINARY_SUBSCR_DICT | 902,940 | 4.7% |
| RERAISE | 491,700 | 2.6% |
| COPY | 441,120 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 6,329,640 | 33.1% |
| LOAD_ATTR_INSTANCE_VALUE | 5,860,600 | 30.6% |
| TO_BOOL_INT | 1,252,980 | 6.6% |
| TO_BOOL | 1,164,320 | 6.1% |
| POP_EXCEPT | 922,200 | 4.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 813,900 | 98.8% |
| CACHE | 9,600 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 300 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 823,860 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,360 | 100.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 660 | 84.6% |
| RERAISE | 60 | 7.7% |
| JUMP_BACKWARD | 60 | 7.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,362,520 | 97.1% |
| LOAD_ATTR_INSTANCE_VALUE | 99,120 | 2.9% |
| RETURN_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,461,880 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 596,280 | 33.3% |
| TO_BOOL_LIST | 281,280 | 15.7% |
| JUMP_BACKWARD | 195,420 | 10.9% |
| TO_BOOL_ALWAYS_TRUE | 161,460 | 9.0% |
| TO_BOOL_INT | 154,740 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 711,120 | 39.8% |
| JUMP_FORWARD | 562,860 | 31.5% |
| JUMP_BACKWARD | 214,140 | 12.0% |
| FOR_ITER_LIST | 135,360 | 7.6% |
| FOR_ITER_GEN | 96,480 | 5.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 37,120,620 | 81.9% |
| GET_ITER | 7,413,300 | 16.4% |
| SWAP | 776,700 | 1.7% |
| EXTENDED_ARG | 18,240 | 0.0% |
| FOR_ITER | 11,900 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,349,420 | 44.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 18,589,920 | 41.0% |
| LOAD_FAST | 4,725,540 | 10.4% |
| RETURN_CONST | 1,051,920 | 2.3% |
| SWAP | 415,080 | 0.9% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 5,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,880 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,820 | 60.0% |
| IMPORT_FROM | 5,880 | 40.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 300,600 | 47.2% |
| LOAD_CONST | 271,320 | 42.6% |
| LOAD_FAST | 49,500 | 7.8% |
| LOAD_ATTR_MODULE | 16,020 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 348,960 | 54.7% |
| LOAD_CONST | 253,620 | 39.8% |
| POP_JUMP_IF_TRUE | 23,040 | 3.6% |
| STORE_FAST | 11,760 | 1.8% |
| COPY | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 61,657,320 | 29.7% |
| END_FOR | 36,786,240 | 17.7% |
| POP_TOP | 30,768,120 | 14.8% |
| CALL_LIST_APPEND | 23,904,480 | 11.5% |
| LIST_APPEND | 20,213,100 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 107,588,980 | 51.9% |
| FOR_ITER_TUPLE | 49,224,860 | 23.8% |
| FOR_ITER | 37,120,620 | 17.9% |
| FOR_ITER_GEN | 4,692,240 | 2.3% |
| LOAD_FAST | 3,089,100 | 1.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,883,880 | 28.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,545,960 | 23.6% |
| POP_JUMP_IF_FALSE | 783,660 | 12.0% |
| EXTENDED_ARG | 562,860 | 8.6% |
| JUMP_FORWARD | 517,380 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,217,600 | 33.8% |
| LOAD_FAST_LOAD_FAST | 1,324,740 | 20.2% |
| LOAD_GLOBAL_BUILTIN | 1,121,140 | 17.1% |
| LOAD_CONST | 602,160 | 9.2% |
| JUMP_FORWARD | 517,380 | 7.9% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,351,400 | 56.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,244,120 | 11.1% |
| BUILD_TUPLE | 2,241,360 | 11.1% |
| BINARY_SUBSCR_DICT | 2,139,000 | 10.6% |
| BINARY_SLICE | 1,427,940 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,213,100 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,711,280 | 99.3% |
| RETURN_VALUE | 12,180 | 0.4% |
| LOAD_ATTR_INSTANCE_VALUE | 4,560 | 0.2% |
| LOAD_CONST | 3,060 | 0.1% |
| BINARY_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 2,728,440 | 99.9% |
| BUILD_TUPLE | 2,940 | 0.1% |
| LOAD_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 90,635,800 | 60.7% |
| LOAD_ATTR_SLOT | 42,337,740 | 28.3% |
| LOAD_GLOBAL_MODULE | 8,370,540 | 5.6% |
| LOAD_ATTR | 4,154,780 | 2.8% |
| LOAD_FAST_LOAD_FAST | 1,108,580 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,115,180 | 21.5% |
| LOAD_FAST | 24,907,380 | 16.7% |
| POP_JUMP_IF_NOT_NONE | 12,997,280 | 8.7% |
| CONVERT_VALUE | 11,580,660 | 7.8% |
| CALL_BUILTIN_FAST | 11,580,660 | 7.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,135,840 | 28.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,684,620 | 10.4% |
| LOAD_CONST | 25,339,500 | 8.9% |
| LOAD_ATTR_METHOD_NO_DICT | 18,401,520 | 6.5% |
| STORE_FAST | 18,290,280 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,755,080 | 23.1% |
| CALL_BUILTIN_FAST | 32,935,140 | 11.6% |
| LOAD_CONST | 25,339,500 | 8.9% |
| STORE_FAST | 24,632,580 | 8.7% |
| LOAD_ATTR_METHOD_NO_DICT | 15,180,960 | 5.3% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 798,360 | 88.3% |
| LOAD_ATTR | 42,000 | 4.6% |
| LOAD_ATTR_METHOD_NO_DICT | 35,280 | 3.9% |
| LOAD_FAST | 10,920 | 1.2% |
| POP_TOP | 10,860 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 798,300 | 88.3% |
| LOAD_ATTR_INSTANCE_VALUE | 42,000 | 4.6% |
| LOAD_CONST | 35,280 | 3.9% |
| CALL_PY_EXACT_ARGS | 10,900 | 1.2% |
| RETURN_VALUE | 10,860 | 1.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,349,300 | 13.1% |
| RESUME_CHECK | 145,573,020 | 9.1% |
| POP_JUMP_IF_FALSE | 142,716,300 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120,574,140 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 115,746,120 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 286,511,980 | 17.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 162,690,040 | 10.2% |
| CALL_PY_EXACT_ARGS | 125,967,000 | 7.9% |
| LOAD_ATTR | 90,635,800 | 5.7% |
| LOAD_ATTR_METHOD_NO_DICT | 89,740,480 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,222,880 | 89.6% |
| LOAD_FAST_AND_CLEAR | 258,060 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,222,880 | 89.6% |
| LOAD_FAST_AND_CLEAR | 258,060 | 10.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,260 | 26.2% |
| FOR_ITER_LIST | 14,220 | 19.3% |
| STORE_FAST | 11,760 | 16.0% |
| FOR_ITER | 9,660 | 13.1% |
| LOAD_FAST_LOAD_FAST | 4,380 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 25,560 | 34.7% |
| RETURN_VALUE | 17,160 | 23.3% |
| LOAD_FAST | 9,960 | 13.5% |
| TO_BOOL_NONE | 9,160 | 12.4% |
| BINARY_OP | 3,240 | 4.4% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 84,057,840 | 28.4% |
| STORE_FAST | 68,702,220 | 23.2% |
| POP_JUMP_IF_FALSE | 29,125,680 | 9.8% |
| RESUME_CHECK | 18,476,760 | 6.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 17,665,180 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 56,935,080 | 19.2% |
| LOAD_FAST | 36,754,080 | 12.4% |
| LOAD_ATTR_INSTANCE_VALUE | 34,597,160 | 11.7% |
| CONTAINS_OP | 28,740,240 | 9.7% |
| STORE_ATTR_INSTANCE_VALUE | 25,987,780 | 8.8% |


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_LOCALS | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 300 | 15.6% |
| STORE_FAST | 240 | 12.5% |
| LOAD_FAST | 200 | 10.4% |
| RESUME_CHECK | 180 | 9.4% |
| RETURN_VALUE | 140 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,280 | 66.7% |
| LOAD_GLOBAL_BUILTIN | 620 | 32.3% |
| LOAD_ATTR | 20 | 1.0% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 240 | 80.0% |
| RESUME_CHECK | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 60.0% |
| STORE_NAME | 60 | 20.0% |
| UNPACK_SEQUENCE_TUPLE | 40 | 13.3% |
| UNPACK_SEQUENCE | 20 | 6.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 145,380 | 93.0% |
| MAKE_CELL | 10,920 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 145,380 | 93.0% |
| MAKE_CELL | 10,920 | 7.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,160 | 82.4% |
| LOAD_ATTR_MODULE | 5,880 | 11.8% |
| LOAD_CONST | 2,940 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 47,040 | 94.1% |
| CALL_FUNCTION_EX | 2,940 | 5.9% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 118,816,700 | 46.7% |
| TO_BOOL_NONE | 44,009,500 | 17.3% |
| CONTAINS_OP | 34,351,440 | 13.5% |
| COMPARE_OP_INT | 15,379,060 | 6.0% |
| TO_BOOL_LIST | 10,687,460 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 142,716,300 | 56.1% |
| RETURN_CONST | 34,939,800 | 13.7% |
| LOAD_FAST_LOAD_FAST | 29,125,680 | 11.5% |
| LOAD_GLOBAL_BUILTIN | 14,649,240 | 5.8% |
| LOAD_CONST | 9,947,760 | 3.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,135,240 | 76.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,925,880 | 23.9% |
| CALL_BUILTIN_FAST | 3,060 | 0.0% |
| LOAD_ATTR_WITH_HINT | 2,880 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 1,620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,204,140 | 52.1% |
| RETURN_CONST | 2,604,720 | 32.3% |
| LOAD_GLOBAL_BUILTIN | 1,129,380 | 14.0% |
| LOAD_CONST | 111,720 | 1.4% |
| LOAD_FAST_LOAD_FAST | 8,160 | 0.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,454,760 | 54.2% |
| LOAD_ATTR | 12,997,280 | 22.4% |
| STORE_FAST_LOAD_FAST | 8,868,180 | 15.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,578,260 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,004,100 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,853,420 | 82.5% |
| NOP | 3,840,600 | 6.6% |
| LOAD_GLOBAL_BUILTIN | 2,567,560 | 4.4% |
| RETURN_CONST | 2,318,220 | 4.0% |
| LOAD_FAST_LOAD_FAST | 1,043,640 | 1.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 49,989,740 | 37.7% |
| CONTAINS_OP | 30,261,540 | 22.8% |
| TO_BOOL_NONE | 20,699,840 | 15.6% |
| TO_BOOL_INT | 12,876,960 | 9.7% |
| TO_BOOL_STR | 7,117,940 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 61,657,320 | 46.5% |
| LOAD_FAST | 22,493,700 | 16.9% |
| NOP | 20,618,520 | 15.5% |
| RETURN_CONST | 12,446,100 | 9.4% |
| POP_TOP | 5,365,200 | 4.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 583,740 | 49.7% |
| LOAD_GLOBAL_BUILTIN | 543,240 | 46.2% |
| POP_JUMP_IF_FALSE | 32,160 | 2.7% |
| LOAD_CONST | 11,760 | 1.0% |
| CALL | 3,900 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 753,540 | 64.1% |
| COPY | 421,860 | 35.9% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 922,200 | 62.9% |
| POP_TOP | 377,940 | 25.8% |
| POP_JUMP_IF_FALSE | 113,700 | 7.8% |
| CALL_INTRINSIC_1 | 51,420 | 3.5% |
| DELETE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 922,200 | 65.2% |
| COPY | 491,700 | 34.8% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,939,800 | 21.5% |
| FOR_ITER_LIST | 34,441,920 | 21.2% |
| RESUME_CHECK | 16,878,540 | 10.4% |
| POP_TOP | 14,169,000 | 8.7% |
| POP_JUMP_IF_TRUE | 12,446,100 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 84,716,580 | 52.1% |
| END_FOR | 36,887,100 | 22.7% |
| INTERPRETER_EXIT | 18,866,080 | 11.6% |
| RETURN_VALUE | 15,188,380 | 9.3% |
| TO_BOOL_NONE | 3,193,360 | 2.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 228,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 134,400 | 58.9% |
| STORE_FAST | 93,840 | 41.1% |
| STORE_NAME | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,260,960 | 69.4% |
| LOAD_FAST_LOAD_FAST | 5,828,840 | 26.5% |
| SWAP | 857,600 | 3.9% |
| LOAD_ATTR_MODULE | 38,220 | 0.2% |
| STORE_ATTR | 11,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,116,100 | 59.6% |
| RETURN_CONST | 6,125,220 | 27.8% |
| LOAD_GLOBAL_MODULE | 1,838,580 | 8.4% |
| LOAD_FAST_LOAD_FAST | 619,380 | 2.8% |
| JUMP_BACKWARD | 121,680 | 0.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 10,860 | 99.5% |
| CALL | 60 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,860 | 99.5% |
| LOAD_GLOBAL_MODULE | 40 | 0.4% |
| LOAD_GLOBAL | 20 | 0.2% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 96,575,680 | 21.9% |
| FOR_ITER_TUPLE | 48,528,440 | 11.0% |
| LOAD_ATTR | 32,115,180 | 7.3% |
| CALL_BUILTIN_FAST | 32,105,340 | 7.3% |
| LOAD_CONST | 24,632,580 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 209,349,300 | 47.5% |
| LOAD_FAST_LOAD_FAST | 68,702,220 | 15.6% |
| LOAD_GLOBAL_BUILTIN | 61,385,540 | 13.9% |
| NOP | 30,959,640 | 7.0% |
| BUILD_LIST | 23,341,740 | 5.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 11,779,680 | 82.1% |
| FOR_ITER_RANGE | 2,242,080 | 15.6% |
| FOR_ITER_TUPLE | 317,520 | 2.2% |
| FOR_ITER | 4,800 | 0.0% |
| YIELD_VALUE | 900 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 8,868,180 | 61.8% |
| LOAD_ATTR_METHOD_NO_DICT | 2,341,440 | 16.3% |
| LOAD_FAST | 2,247,300 | 15.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 372,420 | 2.6% |
| TO_BOOL_STR | 318,540 | 2.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 29,411,280 | 61.0% |
| UNPACK_SEQUENCE_TUPLE | 18,019,800 | 37.3% |
| STORE_FAST_STORE_FAST | 716,760 | 1.5% |
| UNPACK_SEQUENCE_LIST | 104,880 | 0.2% |
| LOAD_FAST_LOAD_FAST | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,623,680 | 36.5% |
| LOAD_FAST | 12,939,960 | 26.8% |
| LOAD_GLOBAL_MODULE | 11,756,640 | 24.4% |
| LOAD_GLOBAL_BUILTIN | 2,474,100 | 5.1% |
| LOAD_FAST_LOAD_FAST | 2,457,420 | 5.1% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 180 | 33.3% |
| STORE_NAME | 120 | 22.2% |
| UNPACK_SEQUENCE_TUPLE | 60 | 11.1% |
| SET_FUNCTION_ATTRIBUTE | 60 | 11.1% |
| LOAD_NAME | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 240 | 44.4% |
| STORE_NAME | 120 | 22.2% |
| RETURN_CONST | 60 | 11.1% |
| LOAD_FAST | 60 | 11.1% |
| LOAD_CONST | 60 | 11.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,669,080 | 27.2% |
| RETURN_VALUE | 2,394,900 | 14.0% |
| LOAD_FAST_AND_CLEAR | 2,222,880 | 13.0% |
| BUILD_LIST | 2,222,880 | 13.0% |
| BINARY_OP | 1,295,580 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,860,600 | 34.2% |
| POP_TOP | 2,600,760 | 15.2% |
| BUILD_LIST | 2,222,880 | 13.0% |
| STORE_FAST | 1,248,420 | 7.3% |
| FOR_ITER_LIST | 1,134,480 | 6.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 220 | 84.6% |
| LOAD_NAME | 20 | 7.7% |
| LOAD_ATTR | 20 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 69.2% |
| UNPACK_SEQUENCE_TUPLE | 60 | 23.1% |
| UNPACK_SEQUENCE_LIST | 20 | 7.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,794,300 | 96.9% |
| CALL_METHOD_DESCRIPTOR_O | 87,600 | 1.8% |
| BUILD_TUPLE | 48,900 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,360 | 0.2% |
| RETURN_VALUE | 4,740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,766,700 | 96.4% |
| INTERPRETER_EXIT | 130,260 | 2.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 48,900 | 1.0% |
| STORE_FAST_LOAD_FAST | 900 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 3,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,420 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 2,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,940 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,379,080 | 45.5% |
| LOAD_FAST | 8,800,320 | 38.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,956,660 | 8.6% |
| CALL_LEN | 1,130,400 | 5.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 367,380 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,316,960 | 23.3% |
| SWAP | 4,669,080 | 20.5% |
| LOAD_FAST | 3,359,640 | 14.7% |
| BINARY_SLICE | 2,907,240 | 12.8% |
| LOAD_GLOBAL_BUILTIN | 2,792,400 | 12.2% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,863,780 | 76.7% |
| BUILD_STRING | 2,010,960 | 10.4% |
| LOAD_CONST | 868,400 | 4.5% |
| LOAD_ATTR | 603,300 | 3.1% |
| RETURN_VALUE | 411,960 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,200,440 | 73.3% |
| RETURN_VALUE | 2,037,360 | 10.5% |
| STORE_FAST | 1,438,860 | 7.4% |
| SWAP | 1,171,500 | 6.0% |
| LOAD_CONST | 344,940 | 1.8% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,940 | 62.0% |
| BINARY_OP_ADD_INT | 1,620 | 34.2% |
| BINARY_OP_SUBTRACT_INT | 180 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,940 | 62.0% |
| BINARY_OP_SUBTRACT_INT | 1,620 | 34.2% |
| STORE_FAST | 180 | 3.8% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 2,940 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,190,120 | 58.6% |
| CALL_LEN | 916,860 | 16.9% |
| LOAD_ATTR_INSTANCE_VALUE | 836,520 | 15.4% |
| LOAD_FAST | 483,240 | 8.9% |
| LOAD_FAST_LOAD_FAST | 12,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,708,140 | 31.4% |
| LOAD_CONST | 1,087,980 | 20.0% |
| CALL_PY_EXACT_ARGS | 910,720 | 16.7% |
| BINARY_SUBSCR_LIST_INT | 662,900 | 12.2% |
| LOAD_FAST | 325,440 | 6.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,863,920 | 83.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,451,100 | 4.9% |
| CALL_BUILTIN_O | 2,139,000 | 4.2% |
| LOAD_CONST | 1,112,580 | 2.2% |
| LOAD_FAST_LOAD_FAST | 1,108,260 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,096,300 | 41.9% |
| UNPACK_SEQUENCE_TUPLE | 14,259,900 | 28.3% |
| RETURN_VALUE | 7,969,560 | 15.8% |
| LIST_APPEND | 2,139,000 | 4.2% |
| TO_BOOL_ALWAYS_TRUE | 1,032,000 | 2.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,739,360 | 56.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,355,020 | 40.2% |
| LOAD_FAST_LOAD_FAST | 143,700 | 1.7% |
| LOAD_FAST | 98,040 | 1.2% |
| BINARY_OP_ADD_INT | 8,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,344,240 | 99.9% |
| LOAD_ATTR_METHOD_NO_DICT | 5,300 | 0.1% |
| LOAD_FAST | 1,920 | 0.0% |
| CONTAINS_OP | 1,020 | 0.0% |
| PUSH_EXC_INFO | 900 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,625,460 | 75.5% |
| LOAD_FAST_LOAD_FAST | 2,853,400 | 13.0% |
| LOAD_CONST | 1,591,800 | 7.2% |
| BINARY_OP_SUBTRACT_INT | 662,900 | 3.0% |
| BINARY_OP_ADD_INT | 130,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,448,000 | 54.6% |
| STORE_FAST | 2,955,660 | 14.1% |
| LOAD_CONST | 1,996,260 | 9.5% |
| LOAD_FAST | 1,604,820 | 7.7% |
| PUSH_EXC_INFO | 814,620 | 3.9% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,711,600 | 55.1% |
| LOAD_CONST | 2,337,000 | 34.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 246,480 | 3.7% |
| BINARY_OP_SUBTRACT_INT | 246,480 | 3.7% |
| LOAD_FAST_LOAD_FAST | 159,360 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,711,600 | 55.1% |
| LOAD_CONST | 2,294,400 | 34.1% |
| STORE_FAST | 617,700 | 9.2% |
| LOAD_FAST | 85,740 | 1.3% |
| COMPARE_OP_STR | 17,460 | 0.3% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,653,540 | 100.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 3,815,040 | 44.1% |
| CALL_LIST_APPEND | 3,815,040 | 44.1% |
| LOAD_CONST | 337,140 | 3.9% |
| LOAD_GLOBAL_BUILTIN | 296,940 | 3.4% |
| COMPARE_OP_INT | 205,500 | 2.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,904,280 | 70.7% |
| LOAD_FAST | 386,160 | 14.3% |
| LOAD_GLOBAL_MODULE | 193,440 | 7.2% |
| LOAD_FAST_LOAD_FAST | 63,880 | 2.4% |
| LOAD_ATTR_WITH_HINT | 60,300 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,661,000 | 61.6% |
| RESUME_CHECK | 988,840 | 36.7% |
| CALL_ALLOC_AND_ENTER_INIT | 32,180 | 1.2% |
| STORE_FAST | 12,480 | 0.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,833,660 | 99.0% |
| CALL_PY_EXACT_ARGS | 84,280 | 0.8% |
| LOAD_FAST_LOAD_FAST | 9,660 | 0.1% |
| LOAD_CONST | 2,940 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,849,120 | 99.1% |
| CALL_PY_EXACT_ARGS | 84,600 | 0.9% |
| POP_TOP | 2,940 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 360 | 0.0% |
| COPY_FREE_VARS | 300 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,932,000 | 33.7% |
| LOAD_FAST | 1,621,540 | 28.3% |
| CALL_BUILTIN_CLASS | 1,486,320 | 26.0% |
| CALL_LEN | 455,640 | 8.0% |
| CALL_FUNCTION_EX | 87,600 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,620,560 | 45.8% |
| CALL_BUILTIN_CLASS | 1,486,320 | 26.0% |
| LOAD_FAST | 1,089,600 | 19.0% |
| BINARY_OP | 297,780 | 5.2% |
| STORE_FAST | 143,940 | 2.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,935,140 | 48.6% |
| LOAD_FAST_LOAD_FAST | 21,061,180 | 31.1% |
| LOAD_ATTR | 11,580,660 | 17.1% |
| BINARY_SUBSCR_DICT | 981,960 | 1.4% |
| LOAD_FAST | 503,220 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,105,340 | 47.4% |
| TO_BOOL_BOOL | 30,182,640 | 44.5% |
| POP_TOP | 4,242,660 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 536,400 | 0.8% |
| COPY | 137,220 | 0.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,011,320 | 90.6% |
| STORE_FAST | 131,640 | 5.9% |
| LOAD_FAST | 68,880 | 3.1% |
| RETURN_GENERATOR | 2,940 | 0.1% |
| LOAD_FAST_LOAD_FAST | 2,940 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,192,700 | 98.7% |
| PUSH_EXC_INFO | 17,700 | 0.8% |
| POP_TOP | 5,940 | 0.3% |
| RETURN_VALUE | 4,380 | 0.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,383,440 | 99.4% |
| RETURN_VALUE | 48,660 | 0.3% |
| CALL_BUILTIN_FAST | 35,280 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,880 | 0.0% |
| BINARY_SLICE | 4,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 12,835,620 | 73.4% |
| LOAD_CONST | 2,452,140 | 14.0% |
| BINARY_SUBSCR_DICT | 2,139,000 | 12.2% |
| TO_BOOL_BOOL | 41,160 | 0.2% |
| LOAD_FAST | 5,340 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 56,935,080 | 60.2% |
| LOAD_GLOBAL_MODULE | 15,788,040 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 14,444,140 | 15.3% |
| LOAD_ATTR_MODULE | 5,546,540 | 5.9% |
| LOAD_FAST | 1,021,500 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 93,413,760 | 98.8% |
| RETURN_VALUE | 1,091,280 | 1.2% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,469,200 | 55.6% |
| LOAD_FAST | 12,428,220 | 41.9% |
| LOAD_ATTR | 293,400 | 1.0% |
| RETURN_VALUE | 177,540 | 0.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 108,240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 7,331,080 | 24.7% |
| LOAD_CONST | 5,234,040 | 17.7% |
| RETURN_VALUE | 4,728,120 | 15.9% |
| LOAD_FAST | 3,903,060 | 13.2% |
| CALL_PY_EXACT_ARGS | 2,759,460 | 9.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,455,880 | 71.0% |
| BINARY_SUBSCR_TUPLE_INT | 3,815,040 | 9.2% |
| RETURN_VALUE | 2,079,740 | 5.0% |
| LOAD_CONST | 2,045,660 | 4.9% |
| BUILD_STRING | 1,398,120 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 23,904,480 | 57.7% |
| RETURN_CONST | 9,282,660 | 22.4% |
| LOAD_GLOBAL_MODULE | 2,634,240 | 6.4% |
| LOAD_FAST | 2,459,660 | 5.9% |
| LOAD_CONST | 932,220 | 2.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 11,036,560 | 43.6% |
| LOAD_CONST | 4,558,660 | 18.0% |
| LOAD_FAST_LOAD_FAST | 4,489,920 | 17.8% |
| BUILD_LIST | 4,385,660 | 17.3% |
| LOAD_FAST | 716,400 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,971,820 | 27.6% |
| RETURN_VALUE | 4,497,120 | 17.8% |
| TO_BOOL_STR | 3,814,020 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 2,259,120 | 8.9% |
| LIST_APPEND | 2,244,120 | 8.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,481,000 | 60.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,625,380 | 25.8% |
| LOAD_CONST | 1,775,680 | 12.6% |
| LOAD_FAST_LOAD_FAST | 123,960 | 0.9% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 33,180 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 6,935,320 | 49.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,438,040 | 17.4% |
| BINARY_OP | 2,010,960 | 14.3% |
| STORE_FAST | 1,092,000 | 7.8% |
| RETURN_VALUE | 802,860 | 5.7% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 15,332,320 | 99.9% |
| LOAD_ATTR | 8,880 | 0.1% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,267,580 | 34.3% |
| STORE_FAST | 3,410,580 | 22.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,011,320 | 13.1% |
| STORE_SUBSCR_DICT | 1,473,660 | 9.6% |
| CONVERT_VALUE | 1,385,580 | 9.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,913,040 | 45.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 6,935,320 | 28.8% |
| LOAD_ATTR | 3,012,180 | 12.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,011,000 | 8.3% |
| STORE_FAST | 414,060 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,649,560 | 27.6% |
| POP_TOP | 5,100,480 | 21.2% |
| RETURN_VALUE | 4,908,360 | 20.4% |
| LOAD_FAST | 2,056,080 | 8.5% |
| LOAD_CONST | 2,017,380 | 8.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,967,000 | 64.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 32,046,680 | 16.4% |
| LOAD_FAST_LOAD_FAST | 11,376,560 | 5.8% |
| LOAD_ATTR_INSTANCE_VALUE | 6,173,920 | 3.2% |
| BUILD_LIST | 4,039,140 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 157,197,040 | 80.5% |
| RETURN_GENERATOR | 36,963,540 | 18.9% |
| COPY_FREE_VARS | 813,900 | 0.4% |
| MAKE_CELL | 145,380 | 0.1% |
| CALL_PY_EXACT_ARGS | 94,480 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,466,380 | 75.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,453,280 | 12.7% |
| CALL_STR_1 | 1,385,580 | 5.1% |
| LOAD_CONST | 1,267,920 | 4.7% |
| LOAD_FAST_LOAD_FAST | 355,680 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 27,183,180 | 99.8% |
| RETURN_GENERATOR | 31,020 | 0.1% |
| STORE_FAST | 5,080 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,120 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,260 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,420,860 | 75.8% |
| RETURN_VALUE | 1,724,700 | 24.1% |
| CALL_LEN | 4,920 | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,140 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,023,340 | 42.3% |
| RETURN_VALUE | 1,923,420 | 26.9% |
| CALL_PY_WITH_DEFAULTS | 1,385,580 | 19.4% |
| STORE_SUBSCR_DICT | 718,500 | 10.0% |
| CALL | 75,720 | 1.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 163,260 | 70.7% |
| POP_JUMP_IF_TRUE | 35,280 | 15.3% |
| LOAD_CONST | 17,640 | 7.6% |
| LOAD_FAST | 11,760 | 5.1% |
| RETURN_GENERATOR | 2,940 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 166,200 | 72.0% |
| LOAD_FAST | 61,740 | 26.7% |
| BINARY_OP | 2,940 | 1.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,577,200 | 85.3% |
| LOAD_FAST | 617,160 | 14.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,200 | 85.3% |
| LOAD_FAST_LOAD_FAST | 586,560 | 14.0% |
| LOAD_FAST | 17,640 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 8,820 | 0.2% |
| PUSH_NULL | 3,660 | 0.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,554,780 | 33.9% |
| CALL_LEN | 7,331,080 | 32.9% |
| LOAD_FAST_LOAD_FAST | 3,203,580 | 14.4% |
| LOAD_ATTR_WITH_HINT | 2,250,420 | 10.1% |
| LOAD_FAST | 1,383,720 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,379,060 | 69.0% |
| POP_JUMP_IF_TRUE | 3,877,180 | 17.4% |
| RETURN_VALUE | 2,713,260 | 12.2% |
| COPY | 319,020 | 1.4% |
| COMPARE_OP | 280 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,574,700 | 75.1% |
| RETURN_VALUE | 2,834,340 | 22.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 212,400 | 1.7% |
| LOAD_FAST | 42,060 | 0.3% |
| LOAD_FAST_LOAD_FAST | 28,860 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,670,740 | 60.2% |
| RETURN_VALUE | 2,965,740 | 23.3% |
| POP_JUMP_IF_TRUE | 1,967,520 | 15.4% |
| BINARY_SUBSCR | 76,440 | 0.6% |
| LOAD_GLOBAL_MODULE | 38,220 | 0.3% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 36,914,160 | 88.5% |
| JUMP_BACKWARD | 4,692,240 | 11.3% |
| EXTENDED_ARG | 96,480 | 0.2% |
| SWAP | 360 | 0.0% |
| LOAD_FAST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 36,917,820 | 88.5% |
| RESUME_CHECK | 4,785,780 | 11.5% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 107,588,980 | 64.9% |
| GET_ITER | 56,407,660 | 34.0% |
| SWAP | 1,134,480 | 0.7% |
| FOR_ITER_TUPLE | 356,060 | 0.2% |
| EXTENDED_ARG | 135,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,575,680 | 58.3% |
| RETURN_CONST | 34,441,920 | 20.8% |
| LOAD_FAST | 13,384,620 | 8.1% |
| STORE_FAST_LOAD_FAST | 11,779,680 | 7.1% |
| LOAD_FAST_LOAD_FAST | 4,122,320 | 2.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,064,860 | 88.5% |
| GET_ITER | 365,040 | 10.5% |
| SWAP | 32,040 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 2,242,080 | 64.8% |
| STORE_FAST | 845,460 | 24.4% |
| LOAD_FAST | 189,060 | 5.5% |
| RETURN_CONST | 108,300 | 3.1% |
| SWAP | 31,500 | 0.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 49,224,860 | 71.0% |
| GET_ITER | 19,472,660 | 28.1% |
| FOR_ITER_LIST | 356,080 | 0.5% |
| SWAP | 279,300 | 0.4% |
| EXTENDED_ARG | 17,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 48,528,440 | 70.0% |
| RETURN_CONST | 10,758,120 | 15.5% |
| LOAD_FAST | 6,008,460 | 8.7% |
| LOAD_FAST_LOAD_FAST | 3,047,200 | 4.4% |
| FOR_ITER_LIST | 356,060 | 0.5% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 14,457,680 | 94.6% |
| LOAD_FAST_LOAD_FAST | 591,660 | 3.9% |
| LOAD_FAST | 208,200 | 1.4% |
| LOAD_ATTR_CLASS | 20,560 | 0.1% |
| LOAD_ATTR_MODULE | 8,820 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 8,282,760 | 54.2% |
| TO_BOOL_BOOL | 2,450,640 | 16.0% |
| LOAD_FAST | 2,090,760 | 13.7% |
| CONTAINS_OP | 1,750,380 | 11.5% |
| CALL_PY_EXACT_ARGS | 253,380 | 1.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 286,511,980 | 82.8% |
| LOAD_FAST_LOAD_FAST | 34,597,160 | 10.0% |
| LOAD_ATTR_INSTANCE_VALUE | 18,092,500 | 5.2% |
| COPY | 5,860,600 | 1.7% |
| LOAD_ATTR | 558,540 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,557,800 | 29.1% |
| TO_BOOL_NONE | 32,884,600 | 9.5% |
| GET_ITER | 28,509,720 | 8.2% |
| CONTAINS_OP | 25,942,680 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 18,092,500 | 5.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,740,480 | 60.8% |
| LOAD_ATTR_INSTANCE_VALUE | 15,495,800 | 10.5% |
| LOAD_CONST | 15,180,960 | 10.3% |
| LOAD_ATTR_WITH_HINT | 7,483,800 | 5.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,898,060 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,009,460 | 62.4% |
| LOAD_CONST | 18,401,520 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 15,332,320 | 10.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 11,036,560 | 7.5% |
| LOAD_FAST_LOAD_FAST | 6,040,380 | 4.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,690,040 | 77.8% |
| LOAD_ATTR_WITH_HINT | 23,209,420 | 11.1% |
| LOAD_ATTR_INSTANCE_VALUE | 12,669,760 | 6.1% |
| LOAD_FAST_LOAD_FAST | 5,249,460 | 2.5% |
| RETURN_VALUE | 2,114,020 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,574,140 | 57.7% |
| CALL_PY_EXACT_ARGS | 32,046,680 | 15.3% |
| LOAD_CONST | 29,684,620 | 14.2% |
| LOAD_FAST_LOAD_FAST | 17,665,180 | 8.4% |
| CALL_PY_WITH_DEFAULTS | 3,453,280 | 1.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 28,675,400 | 99.6% |
| LOAD_ATTR_MODULE | 71,180 | 0.2% |
| LOAD_FAST | 24,120 | 0.1% |
| LOAD_ATTR_WITH_HINT | 12,540 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 19,695,400 | 68.4% |
| CALL_ISINSTANCE | 5,546,540 | 19.3% |
| LOAD_GLOBAL_MODULE | 801,600 | 2.8% |
| BUILD_TUPLE | 711,180 | 2.5% |
| LOAD_CONST | 646,380 | 2.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,720 | 98.4% |
| LOAD_ATTR | 60 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,680 | 97.4% |
| CALL | 60 | 1.6% |
| LOAD_ATTR | 40 | 1.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,514,840 | 97.1% |
| LOAD_FAST_LOAD_FAST | 914,280 | 1.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 687,120 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 195,540 | 0.3% |
| STORE_FAST_LOAD_FAST | 148,360 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,852,200 | 34.4% |
| GET_ITER | 19,275,920 | 29.0% |
| STORE_FAST | 4,201,680 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,898,060 | 5.9% |
| CALL_PY_EXACT_ARGS | 3,754,860 | 5.6% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,802,880 | 98.4% |
| LOAD_ATTR_PROPERTY | 76,020 | 1.3% |
| LOAD_ATTR | 17,020 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 3,114,180 | 52.8% |
| RESUME_CHECK | 1,852,240 | 31.4% |
| LOAD_ATTR_WITH_HINT | 402,480 | 6.8% |
| LOAD_FAST | 383,760 | 6.5% |
| LOAD_ATTR_PROPERTY | 76,020 | 1.3% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,559,160 | 98.5% |
| LOAD_ATTR_SLOT | 666,300 | 1.5% |
| LOAD_FAST_LOAD_FAST | 17,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 42,337,740 | 95.7% |
| LOAD_FAST | 1,010,880 | 2.3% |
| LOAD_ATTR_SLOT | 666,300 | 1.5% |
| PUSH_NULL | 84,960 | 0.2% |
| LOAD_GLOBAL_MODULE | 76,320 | 0.2% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,115,260 | 61.8% |
| LOAD_ATTR_WITH_HINT | 16,586,460 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 13,738,840 | 16.0% |
| LOAD_FAST_LOAD_FAST | 1,269,740 | 1.5% |
| RETURN_VALUE | 489,720 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,266,360 | 34.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 23,209,420 | 27.0% |
| LOAD_ATTR_WITH_HINT | 16,586,460 | 19.3% |
| LOAD_ATTR_METHOD_NO_DICT | 7,483,800 | 8.7% |
| TO_BOOL_BOOL | 2,831,640 | 3.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 72,388,720 | 32.0% |
| STORE_FAST | 61,385,540 | 27.2% |
| NOP | 21,623,740 | 9.6% |
| LOAD_FAST | 15,506,200 | 6.9% |
| POP_JUMP_IF_FALSE | 14,649,240 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,746,120 | 51.2% |
| LOAD_FAST_LOAD_FAST | 84,057,840 | 37.2% |
| CALL_ISINSTANCE | 14,444,140 | 6.4% |
| CHECK_EXC_MATCH | 5,049,600 | 2.2% |
| LOAD_CONST | 3,594,960 | 1.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 23,403,680 | 25.1% |
| LOAD_FAST | 18,913,800 | 20.3% |
| STORE_FAST_STORE_FAST | 11,756,640 | 12.6% |
| STORE_FAST | 9,019,720 | 9.7% |
| POP_JUMP_IF_FALSE | 4,970,520 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 28,675,400 | 30.8% |
| CALL_ISINSTANCE | 15,788,040 | 16.9% |
| LOAD_ATTR_CLASS | 14,457,680 | 15.5% |
| LOAD_FAST | 12,659,520 | 13.6% |
| LOAD_ATTR | 8,370,540 | 9.0% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,660 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,020 | 96.1% |
| CALL | 2,940 | 3.9% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 157,197,040 | 49.6% |
| CACHE | 39,861,360 | 12.6% |
| POP_TOP | 37,113,120 | 11.7% |
| CALL_PY_WITH_DEFAULTS | 27,183,180 | 8.6% |
| CALL | 24,128,080 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 145,573,020 | 45.9% |
| LOAD_GLOBAL_BUILTIN | 72,388,720 | 22.8% |
| LOAD_GLOBAL_MODULE | 23,403,680 | 7.4% |
| LOAD_FAST_LOAD_FAST | 18,476,760 | 5.8% |
| RETURN_CONST | 16,878,540 | 5.3% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,225,440 | 64.5% |
| LOAD_FAST_LOAD_FAST | 25,987,780 | 27.8% |
| SWAP | 5,860,600 | 6.3% |
| STORE_ATTR_INSTANCE_VALUE | 1,016,980 | 1.1% |
| RETURN_VALUE | 224,100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,955,600 | 50.3% |
| NOP | 22,151,220 | 23.7% |
| LOAD_GLOBAL_BUILTIN | 8,305,400 | 8.9% |
| RETURN_CONST | 6,764,700 | 7.2% |
| LOAD_FAST_LOAD_FAST | 2,638,740 | 2.8% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,040 | 50.5% |
| LOAD_FAST | 10,800 | 49.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,800 | 49.5% |
| LOAD_FAST_LOAD_FAST | 7,320 | 33.5% |
| RETURN_CONST | 3,720 | 17.0% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,897,120 | 51.2% |
| LOAD_FAST | 3,490,340 | 45.8% |
| SWAP | 220,980 | 2.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,860 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,763,680 | 49.4% |
| LOAD_FAST | 3,702,180 | 48.6% |
| LOAD_GLOBAL_MODULE | 75,540 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 59,280 | 0.8% |
| BUILD_LIST | 4,980 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 16,754,460 | 40.2% |
| LOAD_FAST | 16,746,840 | 40.1% |
| BINARY_SUBSCR_TUPLE_INT | 3,815,040 | 9.1% |
| LOAD_CONST | 1,639,260 | 3.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,473,660 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,528,080 | 54.0% |
| JUMP_BACKWARD | 15,178,260 | 36.4% |
| RETURN_CONST | 2,580,840 | 6.2% |
| LOAD_CONST | 898,800 | 2.2% |
| LOAD_FAST_LOAD_FAST | 226,560 | 0.5% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 469,320 | 55.8% |
| LOAD_FAST | 341,360 | 40.6% |
| LOAD_FAST_LOAD_FAST | 29,880 | 3.6% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 373,340 | 44.4% |
| JUMP_BACKWARD | 304,620 | 36.2% |
| STORE_FAST | 122,940 | 14.6% |
| RETURN_CONST | 37,260 | 4.4% |
| JUMP_FORWARD | 2,220 | 0.3% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,815,120 | 74.1% |
| BINARY_SUBSCR_DICT | 1,032,000 | 20.1% |
| CALL | 84,040 | 1.6% |
| RETURN_CONST | 65,720 | 1.3% |
| RETURN_VALUE | 65,400 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,657,140 | 71.1% |
| POP_JUMP_IF_FALSE | 1,267,460 | 24.6% |
| EXTENDED_ARG | 161,460 | 3.1% |
| TO_BOOL_NONE | 48,160 | 0.9% |
| TO_BOOL_ALWAYS_TRUE | 12,760 | 0.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 93,413,760 | 55.3% |
| CALL_BUILTIN_FAST | 30,182,640 | 17.9% |
| RETURN_VALUE | 20,888,960 | 12.4% |
| LOAD_FAST | 12,371,460 | 7.3% |
| LOAD_ATTR_WITH_HINT | 2,831,640 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 118,816,700 | 70.4% |
| POP_JUMP_IF_TRUE | 49,989,740 | 29.6% |
| EXTENDED_ARG | 41,700 | 0.0% |
| UNARY_NOT | 38,220 | 0.0% |
| TO_BOOL_INT | 980 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 12,835,620 | 75.7% |
| COPY | 1,252,980 | 7.4% |
| LOAD_FAST | 1,144,660 | 6.8% |
| LOAD_ATTR | 512,480 | 3.0% |
| CALL_LEN | 384,940 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 12,876,960 | 75.9% |
| POP_JUMP_IF_FALSE | 3,919,220 | 23.1% |
| EXTENDED_ARG | 154,740 | 0.9% |
| TO_BOOL_NONE | 3,580 | 0.0% |
| TO_BOOL_BOOL | 960 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,862,540 | 77.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,712,020 | 15.1% |
| RETURN_VALUE | 296,280 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 289,800 | 2.5% |
| BINARY_SUBSCR_DICT | 104,100 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,687,460 | 94.0% |
| POP_JUMP_IF_TRUE | 385,500 | 3.4% |
| EXTENDED_ARG | 281,280 | 2.5% |
| TO_BOOL | 19,960 | 0.2% |
| TO_BOOL_NONE | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 32,884,600 | 50.6% |
| LOAD_FAST | 16,772,060 | 25.8% |
| COPY | 6,329,640 | 9.7% |
| RETURN_CONST | 3,193,360 | 4.9% |
| LOAD_ATTR_PROPERTY | 3,114,180 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,009,500 | 67.8% |
| POP_JUMP_IF_TRUE | 20,699,840 | 31.9% |
| EXTENDED_ARG | 103,740 | 0.2% |
| TO_BOOL | 51,680 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 48,200 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,674,680 | 63.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,814,020 | 25.2% |
| COPY | 731,940 | 4.8% |
| STORE_FAST_LOAD_FAST | 318,540 | 2.1% |
| LOAD_ATTR | 286,960 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,691,620 | 50.8% |
| POP_JUMP_IF_TRUE | 7,117,940 | 47.0% |
| UNARY_NOT | 323,040 | 2.1% |
| TO_BOOL_NONE | 12,280 | 0.1% |
| EXTENDED_ARG | 360 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 101,940 | 97.1% |
| BINARY_SLICE | 2,940 | 2.8% |
| UNPACK_SEQUENCE_TUPLE | 40 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 104,880 | 99.9% |
| STORE_FAST | 60 | 0.1% |
| UNPACK_SEQUENCE_TUPLE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 14,259,900 | 79.1% |
| RETURN_VALUE | 3,378,940 | 18.7% |
| FOR_ITER_TUPLE | 279,300 | 1.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 66,240 | 0.4% |
| LOAD_FAST | 22,500 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,019,800 | 100.0% |
| STORE_FAST | 6,420 | 0.0% |
| STORE_NAME | 60 | 0.0% |
| UNPACK_SEQUENCE_LIST | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,589,920 | 61.6% |
| RETURN_VALUE | 8,405,160 | 27.9% |
| FOR_ITER_LIST | 2,838,600 | 9.4% |
| BINARY_SUBSCR_LIST_INT | 207,300 | 0.7% |
| YIELD_VALUE | 48,900 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 29,411,280 | 97.5% |
| LOAD_FAST | 702,000 | 2.3% |
| STORE_FAST | 47,700 | 0.2% |


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
| specialization.deferred |      1161400 | 1.2% |
| specialization.deopt |        40780 | 0.0% |
|          hit |     93959620 | 96.6% |
|         miss |      2165900 | 2.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 41,380 | 83.9% |
| Failure | 7,960 | 16.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 7,780 | 97.7% |
| other | 180 | 2.3% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       876940 | 2.0% |
| specialization.deopt |           40 | 0.0% |
|          hit |     42562200 | 98.0% |
|         miss |         2220 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 5.9% |
| Failure | 2,540 | 94.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 2,280 | 89.8% |
| out of range | 220 | 8.7% |
| other | 40 | 1.6% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3831540 | 1.3% |
| specialization.deopt |       214580 | 0.1% |
|          hit |    271063620 | 94.6% |
|         miss |     11374580 | 4.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 215,460 | 56.4% |
| Failure | 166,520 | 43.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 121,160 | 72.8% |
| tuple | 41,540 | 24.9% |
| mapping | 2,260 | 1.4% |
| dict | 1,420 | 0.9% |
| other | 140 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21055680 | 30.3% |
|          hit |     48411720 | 69.7% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 1.6% |
| Failure | 12,040 | 98.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 4,980 | 41.4% |
| add other | 3,220 | 26.7% |
| add different types | 3,160 | 26.2% |
| or | 320 | 2.7% |
| multiply different types | 180 | 1.5% |
| and int | 160 | 1.3% |
| true divide other | 20 | 0.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     61666980 | 9.4% |
| specialization.deopt |       334840 | 0.1% |
|          hit |    576525460 | 87.9% |
|         miss |     17762220 | 2.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 337,940 | 92.6% |
| Failure | 26,840 | 7.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,680 | 28.6% |
| meth descr method fastcall keywords | 5,480 | 20.4% |
| meth descr varargs | 3,020 | 11.3% |
| init not simple | 2,580 | 9.6% |
| meth descr varargs keywords | 1,740 | 6.5% |
| init not python | 1,140 | 4.2% |
| cfunc varargs keywords | 1,120 | 4.2% |
| class mutable | 1,040 | 3.9% |
| class no vectorcall | 900 | 3.4% |
| other | 700 | 2.6% |
| cmethod | 380 | 1.4% |
| bound method | 360 | 1.3% |
| wrong number arguments | 280 | 1.0% |
| cfunc noargs | 180 | 0.7% |
| cfunc varargs | 160 | 0.6% |
| operator wrapper | 40 | 0.1% |
| str | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1680060 | 4.6% |
| specialization.deopt |         4900 | 0.0% |
|          hit |     34776960 | 94.7% |
|         miss |       259780 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,240 | 28.9% |
| Failure | 12,920 | 71.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 12,440 | 96.3% |
| list | 200 | 1.5% |
| big int | 100 | 0.8% |
| tuple | 80 | 0.6% |
| baseobject | 40 | 0.3% |
| other | 40 | 0.3% |
| long float | 20 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     45328860 | 13.9% |
| specialization.deopt |       712140 | 0.2% |
|          hit |    242497060 | 74.5% |
|         miss |     37744760 | 11.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 712,140 | 98.4% |
| Failure | 11,900 | 1.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 4,280 | 36.0% |
| dict values | 2,480 | 20.8% |
| dict items | 1,840 | 15.5% |
| ascii string | 1,600 | 13.4% |
| set | 780 | 6.6% |
| seq iter | 560 | 4.7% |
| dict keys | 220 | 1.8% |
| reversed list | 40 | 0.3% |
| zip | 40 | 0.3% |
| other | 40 | 0.3% |
| map | 20 | 0.2% |


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
| specialization.deferred |    149255600 | 13.6% |
| specialization.deopt |      5317460 | 0.5% |
|          hit |    667530920 | 60.8% |
|         miss |    281844400 | 25.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,323,880 | 98.1% |
| Failure | 105,120 | 1.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 47,740 | 45.4% |
| shadowed | 28,440 | 27.1% |
| metaclass attribute | 13,920 | 13.2% |
| method | 5,540 | 5.3% |
| non object slot | 2,920 | 2.8% |
| overridden | 2,840 | 2.7% |
| not managed dict | 2,520 | 2.4% |
| mutable class | 640 | 0.6% |
| class method obj | 300 | 0.3% |
| class attr descriptor | 200 | 0.2% |
| class attr simple | 40 | 0.0% |
| module attr not found | 20 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
| specialization.deopt |           40 | 0.0% |
|          hit |    319127500 | 100.0% |
|         miss |         1780 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,940 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        79620 | 100.0% |


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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21991300 | 17.9% |
| specialization.deopt |      1017520 | 0.8% |
|          hit |     47146920 | 38.3% |
|         miss |     53924580 | 43.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,017,840 | 98.8% |
| Failure | 12,200 | 1.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 10,700 | 87.7% |
| not in dict | 940 | 7.7% |
| not in keys | 320 | 2.6% |
| property | 200 | 1.6% |
| overridden | 40 | 0.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |           80 | 0.0% |
|          hit |     48288580 | 100.0% |
|         miss |         3700 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 3,966,972,420 | 49.2% |
| Not specialized | 1,398,130,140 | 17.3% |
| Specialized | 2,699,247,000 | 33.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,007,620 | 100.0% |
| LOAD_ATTR | 149,255,600 | 0.0% |
| CALL | 61,666,980 | 0.0% |
| FOR_ITER | 45,328,860 | 0.0% |
| STORE_ATTR | 21,991,300 | 0.0% |
| BINARY_OP | 21,055,680 | 0.0% |
| TO_BOOL | 3,831,540 | 0.0% |
| COMPARE_OP | 1,680,060 | 0.0% |
| BINARY_SUBSCR | 1,161,400 | 0.0% |
| STORE_SUBSCR | 876,940 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 105,025,660 | 25.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 86,964,560 | 21.5% |
| STORE_ATTR_INSTANCE_VALUE | 53,921,400 | 13.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 47,103,300 | 11.6% |
| LOAD_ATTR_SLOT | 35,314,820 | 8.7% |
| FOR_ITER_LIST | 18,872,780 | 4.7% |
| FOR_ITER_TUPLE | 18,871,980 | 4.7% |
| CALL_PY_EXACT_ARGS | 9,620,080 | 2.4% |
| TO_BOOL_NONE | 6,137,240 | 1.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,506,460 | 1.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 40,121,100 | 11.3% |
| Calls to Python functions inlined | 314,282,760 | 88.7% |
| Calls via PyEval_EvalFrame (total) | 40,121,100 | 11.3% |
| Calls via PyEval_EvalFrame (vector) | 39,764,820 | 11.2% |
| Calls via PyEval_EvalFrame (generator) | 356,280 | 0.1% |
| Calls via PyEval_EvalFrame (legacy) | 3,420 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 39,761,340 | 11.2% |
| Calls via PyEval_EvalFrame (build class) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,645,460 | 3.9% |
| Calls via PyEval_EvalFrame (function ex) | 1,826,820 | 0.5% |
| Calls via PyEval_EvalFrame (api) | 8,643,440 | 2.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 313,332,820 | 88.4% |
| Frame objects created | 9,649,500 | 2.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 277,257,900 | 30.3% |
| Frees to freelist | 279,498,160 |  |
| Allocations | 636,936,460 | 69.7% |
| Allocations to 512 bytes | 636,105,640 | 69.6% |
| Allocations to 4 kbytes | 486,780 | 0.1% |
| Allocations over 4 kbytes | 344,040 | 0.0% |
| Frees | 672,440,578 |  |
| New values | 7,893,140 |  |
| Interpreter increfs | 3,295,161,060 | 61.4% |
| Interpreter decrefs | 4,085,656,720 | 67.2% |
| Increfs | 2,070,918,198 | 38.6% |
| Decrefs | 1,990,172,828 | 32.8% |
| Materialize dict (on request) | 28,580 | 0.4% |
| Materialize dict (new key) | 112,720 | 1.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,160 | 0.0% |
| Method cache hits | 447,165,227 |  |
| Method cache misses | 38,325,413 |  |
| Method cache collisions | 40,260,556 |  |
| Method cache dunder hits | 214,675,275 |  |
| Method cache dunder misses | 1,936,565 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 67,940 | 32,276,280 | 848,930,200 |
| 1 | 6,180 | 17,270,880 | 363,357,680 |
| 2 | 560 | 23,514,360 | 487,941,320 |


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
