
# Pystats results

- benchmark: mypy2
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,935,617,442 | 20.7% | 20.7% |  |
| LOAD_CONST | 699,905,567 | 4.9% | 25.6% |  |
| RESUME_CHECK | 693,144,180 | 4.9% | 30.5% | 0.0% |
| LOAD_GLOBAL_MODULE | 614,396,237 | 4.3% | 34.9% | 0.0% |
| STORE_ATTR_SLOT | 611,031,970 | 4.3% | 39.2% | 21.6% |
| LOAD_FAST_LOAD_FAST | 567,571,890 | 4.0% | 43.2% |  |
| LOAD_GLOBAL_BUILTIN | 550,819,093 | 3.9% | 47.1% | 0.0% |
| POP_JUMP_IF_FALSE | 545,133,051 | 3.8% | 50.9% |  |
| STORE_FAST | 497,233,456 | 3.5% | 54.4% |  |
| LOAD_ATTR_SLOT | 494,505,865 | 3.5% | 57.9% | 1.6% |
| CALL_PY_EXACT_ARGS | 436,275,302 | 3.1% | 61.0% | 10.2% |
| TO_BOOL_BOOL | 415,515,198 | 2.9% | 63.9% | 0.0% |
| RETURN_VALUE | 396,286,680 | 2.8% | 66.7% |  |
| RETURN_CONST | 300,021,920 | 2.1% | 68.8% |  |
| CALL_ISINSTANCE | 278,314,938 | 2.0% | 70.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 263,592,084 | 1.9% | 72.6% | 21.7% |
| POP_JUMP_IF_TRUE | 222,796,164 | 1.6% | 74.2% |  |
| POP_TOP | 220,788,068 | 1.6% | 75.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 154,989,000 | 1.1% | 76.9% | 3.6% |
| LOAD_DEREF | 129,910,862 | 0.9% | 77.8% |  |
| GET_ITER | 121,500,760 | 0.9% | 78.6% |  |
| INTERPRETER_EXIT | 120,915,728 | 0.9% | 79.5% |  |
| LOAD_ATTR | 118,430,284 | 0.8% | 80.3% |  |
| BINARY_SUBSCR_DICT | 118,044,907 | 0.8% | 81.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 114,314,150 | 0.8% | 82.0% | 12.8% |
| ENTER_EXECUTOR | 102,069,475 | 0.7% | 82.7% |  |
| POP_JUMP_IF_NOT_NONE | 96,642,940 | 0.7% | 83.4% |  |
| CONTAINS_OP | 94,591,012 | 0.7% | 84.0% |  |
| COPY_FREE_VARS | 93,984,380 | 0.7% | 84.7% |  |
| SWAP | 87,832,500 | 0.6% | 85.3% |  |
| LOAD_SUPER_ATTR_METHOD | 86,018,980 | 0.6% | 85.9% |  |
| BUILD_LIST | 83,998,929 | 0.6% | 86.5% |  |
| POP_JUMP_IF_NONE | 79,942,980 | 0.6% | 87.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 77,998,060 | 0.6% | 87.6% | 2.2% |
| CALL_KW | 76,507,100 | 0.5% | 88.2% |  |
| FOR_ITER_LIST | 75,569,108 | 0.5% | 88.7% | 2.4% |
| CALL | 68,548,400 | 0.5% | 89.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 63,477,490 | 0.4% | 89.6% | 8.7% |
| IS_OP | 56,868,760 | 0.4% | 90.0% |  |
| NOP | 53,425,160 | 0.4% | 90.4% |  |
| COPY | 50,853,009 | 0.4% | 90.8% |  |
| JUMP_FORWARD | 47,381,776 | 0.3% | 91.1% |  |
| COMPARE_OP_STR | 46,667,549 | 0.3% | 91.4% | 0.3% |
| TO_BOOL_LIST | 45,717,200 | 0.3% | 91.7% | 0.7% |
| COMPARE_OP | 43,093,340 | 0.3% | 92.1% |  |
| BINARY_SUBSCR | 40,857,260 | 0.3% | 92.3% |  |
| CALL_BUILTIN_CLASS | 40,346,918 | 0.3% | 92.6% |  |
| COMPARE_OP_INT | 38,805,695 | 0.3% | 92.9% | 1.9% |
| FOR_ITER | 37,925,530 | 0.3% | 93.2% |  |
| CALL_LEN | 35,581,280 | 0.3% | 93.4% |  |
| PUSH_NULL | 34,785,785 | 0.2% | 93.7% |  |
| EXTENDED_ARG | 33,266,380 | 0.2% | 93.9% |  |
| MAKE_CELL | 33,241,300 | 0.2% | 94.1% |  |
| STORE_FAST_STORE_FAST | 33,109,240 | 0.2% | 94.4% |  |
| CALL_LIST_APPEND | 32,144,080 | 0.2% | 94.6% |  |
| TO_BOOL_NONE | 32,071,560 | 0.2% | 94.8% | 8.3% |
| BUILD_TUPLE | 32,025,657 | 0.2% | 95.0% |  |
| LOAD_ATTR_WITH_HINT | 30,953,520 | 0.2% | 95.3% | 2.1% |
| MAP_ADD | 30,828,340 | 0.2% | 95.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 30,039,160 | 0.2% | 95.7% | 26.8% |
| TO_BOOL_ALWAYS_TRUE | 29,218,100 | 0.2% | 95.9% | 13.1% |
| LOAD_FAST_AND_CLEAR | 27,921,060 | 0.2% | 96.1% |  |
| LOAD_ATTR_PROPERTY | 27,342,401 | 0.2% | 96.3% | 6.6% |
| LOAD_ATTR_MODULE | 26,326,226 | 0.2% | 96.5% | 0.0% |
| UNARY_NOT | 26,161,520 | 0.2% | 96.7% |  |
| LIST_APPEND | 25,464,664 | 0.2% | 96.8% |  |
| FOR_ITER_TUPLE | 23,199,425 | 0.2% | 97.0% | 7.5% |
| JUMP_BACKWARD | 20,729,680 | 0.1% | 97.1% |  |
| CALL_PY_WITH_DEFAULTS | 20,721,240 | 0.1% | 97.3% | 2.1% |
| TO_BOOL | 20,402,260 | 0.1% | 97.4% |  |
| CALL_TUPLE_1 | 20,335,388 | 0.1% | 97.6% |  |
| BINARY_SUBSCR_LIST_INT | 19,316,540 | 0.1% | 97.7% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 16,805,380 | 0.1% | 97.8% |  |
| CALL_BUILTIN_O | 15,814,759 | 0.1% | 97.9% | 8.4% |
| LOAD_ATTR_CLASS | 14,900,340 | 0.1% | 98.0% | 2.4% |
| UNPACK_SEQUENCE_LIST | 14,624,920 | 0.1% | 98.2% |  |
| CALL_BUILTIN_FAST | 14,091,605 | 0.1% | 98.3% | 0.0% |
| STORE_ATTR | 12,448,700 | 0.1% | 98.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 12,132,284 | 0.1% | 98.4% | 0.0% |
| BUILD_MAP | 11,306,300 | 0.1% | 98.5% |  |
| DELETE_ATTR | 11,254,400 | 0.1% | 98.6% |  |
| YIELD_VALUE | 11,207,492 | 0.1% | 98.7% |  |
| CALL_TYPE_1 | 11,112,060 | 0.1% | 98.7% |  |
| TO_BOOL_STR | 9,265,100 | 0.1% | 98.8% | 3.9% |
| STORE_FAST_LOAD_FAST | 8,709,386 | 0.1% | 98.9% |  |
| MAKE_FUNCTION | 8,289,000 | 0.1% | 98.9% |  |
| CALL_FUNCTION_EX | 7,966,320 | 0.1% | 99.0% |  |
| RETURN_GENERATOR | 7,785,480 | 0.1% | 99.0% |  |
| BINARY_OP_ADD_INT | 7,694,278 | 0.1% | 99.1% | 0.8% |
| FOR_ITER_RANGE | 6,888,980 | 0.0% | 99.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 6,667,940 | 0.0% | 99.2% | 0.1% |
| BINARY_OP_ADD_UNICODE | 6,663,040 | 0.0% | 99.2% |  |
| EXIT_INIT_CHECK | 6,658,880 | 0.0% | 99.3% |  |
| BINARY_SLICE | 6,272,060 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 5,227,000 | 0.0% | 99.4% |  |
| STORE_SUBSCR_DICT | 5,017,185 | 0.0% | 99.4% |  |
| BINARY_OP | 4,890,400 | 0.0% | 99.4% |  |
| STORE_DEREF | 4,722,300 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 4,152,160 | 0.0% | 99.5% |  |
| POP_EXCEPT | 4,152,160 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 4,152,160 | 0.0% | 99.6% |  |
| DICT_MERGE | 3,864,720 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 3,805,325 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,793,040 | 0.0% | 99.6% | 0.0% |
| STORE_SUBSCR | 3,771,940 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,135,600 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,034,660 | 0.0% | 99.7% | 10.9% |
| FORMAT_SIMPLE | 2,999,720 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 2,822,800 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_GETITEM | 2,792,220 | 0.0% | 99.8% | 0.0% |
| BEFORE_WITH | 2,676,160 | 0.0% | 99.8% |  |
| IMPORT_FROM | 2,427,840 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 2,025,880 | 0.0% | 99.8% |  |
| IMPORT_NAME | 1,983,200 | 0.0% | 99.8% |  |
| BUILD_STRING | 1,966,800 | 0.0% | 99.8% |  |
| UNARY_NEGATIVE | 1,949,620 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 1,894,196 | 0.0% | 99.9% | 4.5% |
| BUILD_SET | 1,879,120 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,666,380 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,643,940 | 0.0% | 99.9% | 3.1% |
| SET_ADD | 1,433,240 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 1,327,900 | 0.0% | 99.9% |  |
| CALL_STR_1 | 1,219,380 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 1,133,780 | 0.0% | 99.9% | 0.0% |
| LOAD_SUPER_ATTR_ATTR | 1,083,160 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,076,620 | 0.0% | 100.0% | 1.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,069,720 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 573,120 | 0.0% | 100.0% |  |
| RERAISE | 543,680 | 0.0% | 100.0% |  |
| SEND_GEN | 459,252 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 433,000 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 363,312 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 339,600 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 293,220 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 287,820 | 0.0% | 100.0% | 22.1% |
| LOAD_GLOBAL | 242,840 | 0.0% | 100.0% |  |
| DELETE_FAST | 201,920 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 193,100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 150,540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 138,053 | 0.0% | 100.0% |  |
| END_SEND | 96,000 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 96,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 75,900 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 67,960 | 0.0% | 100.0% |  |
| END_FOR | 54,080 | 0.0% | 100.0% |  |
| RESUME | 40,880 | 0.0% | 100.0% | 0.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 32,920 | 0.0% | 100.0% |  |
| BUILD_SLICE | 18,360 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 6,120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 5,480 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 4,820 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 2,880 | 0.0% | 100.0% |  |
| STORE_NAME | 2,240 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,100 | 0.0% | 100.0% |  |
| UNARY_INVERT | 1,560 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 1,260 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 436,159,151 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 382,090,665 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 378,525,056 | 2.7% | 8.4% |
| LOAD_FAST STORE_ATTR_SLOT | 358,936,493 | 2.5% | 11.0% |
| RESUME_CHECK LOAD_FAST | 302,604,830 | 2.1% | 13.1% |
| LOAD_CONST LOAD_FAST | 282,002,769 | 2.0% | 15.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 280,999,030 | 2.0% | 17.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 272,153,948 | 1.9% | 19.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 272,012,714 | 1.9% | 20.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 254,022,395 | 1.8% | 22.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 248,651,140 | 1.8% | 24.5% |
| STORE_FAST LOAD_FAST | 244,693,839 | 1.7% | 26.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 234,472,052 | 1.7% | 27.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 190,693,971 | 1.3% | 29.2% |
| STORE_ATTR_SLOT LOAD_CONST | 170,370,120 | 1.2% | 30.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 169,829,558 | 1.2% | 31.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 163,164,227 | 1.2% | 32.7% |
| LOAD_FAST LOAD_CONST | 158,344,705 | 1.1% | 33.8% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 141,091,380 | 1.0% | 34.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 133,107,263 | 0.9% | 35.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 124,914,538 | 0.9% | 36.7% |
| STORE_ATTR_SLOT RETURN_CONST | 120,940,980 | 0.9% | 37.5% |
| LOAD_FAST RETURN_VALUE | 118,449,268 | 0.8% | 38.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 117,050,417 | 0.8% | 39.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 116,801,009 | 0.8% | 40.0% |
| STORE_ATTR_SLOT LOAD_FAST | 111,618,993 | 0.8% | 40.8% |
| RETURN_CONST POP_TOP | 105,766,640 | 0.7% | 41.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 102,868,480 | 0.7% | 42.3% |
| LOAD_CONST BINARY_SUBSCR_DICT | 101,470,200 | 0.7% | 43.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 101,257,428 | 0.7% | 43.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 98,044,041 | 0.7% | 44.4% |
| POP_TOP LOAD_FAST | 93,780,864 | 0.7% | 45.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 93,392,147 | 0.7% | 45.7% |
| COPY_FREE_VARS RESUME_CHECK | 93,014,160 | 0.7% | 46.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 92,064,060 | 0.6% | 47.0% |
| RETURN_VALUE STORE_FAST | 90,165,220 | 0.6% | 47.6% |
| LOAD_DEREF LOAD_FAST | 88,336,791 | 0.6% | 48.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 86,016,580 | 0.6% | 48.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 84,781,700 | 0.6% | 49.5% |
| RETURN_VALUE RETURN_VALUE | 80,686,084 | 0.6% | 50.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 79,711,880 | 0.6% | 50.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 79,467,627 | 0.6% | 51.2% |
| LOAD_FAST LOAD_FAST | 77,365,297 | 0.5% | 51.7% |
| LOAD_FAST LOAD_ATTR | 76,326,542 | 0.5% | 52.2% |
| LOAD_CONST CALL_KW | 75,037,860 | 0.5% | 52.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 74,527,940 | 0.5% | 53.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 73,322,666 | 0.5% | 53.8% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 71,619,920 | 0.5% | 54.3% |
| CACHE RESUME_CHECK | 69,740,888 | 0.5% | 54.8% |
| RESUME_CHECK RETURN_CONST | 67,669,080 | 0.5% | 55.3% |
| RETURN_CONST INTERPRETER_EXIT | 61,992,140 | 0.4% | 55.7% |
| RETURN_CONST LOAD_FAST | 61,621,760 | 0.4% | 56.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 60,538,700 | 0.4% | 56.6% |
| LOAD_ATTR_SLOT LOAD_FAST | 59,427,360 | 0.4% | 57.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 58,687,300 | 0.4% | 57.4% |
| LOAD_ATTR LOAD_FAST | 55,321,932 | 0.4% | 57.8% |
| LOAD_CONST LOAD_CONST | 53,935,540 | 0.4% | 58.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 53,311,720 | 0.4% | 58.6% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 51,951,046 | 0.4% | 58.9% |
| RETURN_VALUE LOAD_FAST | 50,110,860 | 0.4% | 59.3% |
| FOR_ITER_LIST STORE_FAST | 49,784,224 | 0.4% | 59.6% |
| RETURN_VALUE INTERPRETER_EXIT | 49,259,788 | 0.3% | 60.0% |
| LOAD_ATTR_SLOT GET_ITER | 47,911,940 | 0.3% | 60.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 47,455,960 | 0.3% | 60.7% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 47,450,260 | 0.3% | 61.0% |
| LOAD_FAST CONTAINS_OP | 46,966,649 | 0.3% | 61.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 46,249,480 | 0.3% | 61.7% |
| LOAD_ATTR_SLOT STORE_FAST | 45,561,460 | 0.3% | 62.0% |
| GET_ITER FOR_ITER_LIST | 45,234,672 | 0.3% | 62.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 44,207,520 | 0.3% | 62.6% |
| CACHE COPY_FREE_VARS | 43,492,280 | 0.3% | 62.9% |
| CALL_KW RESUME_CHECK | 43,426,700 | 0.3% | 63.2% |
| RETURN_CONST RETURN_VALUE | 42,797,460 | 0.3% | 63.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 42,042,732 | 0.3% | 63.8% |
| LOAD_GLOBAL_MODULE IS_OP | 41,593,140 | 0.3% | 64.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 40,661,500 | 0.3% | 64.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 39,436,636 | 0.3% | 64.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 39,177,080 | 0.3% | 65.0% |
| COPY TO_BOOL_BOOL | 38,524,084 | 0.3% | 65.2% |
| IS_OP POP_JUMP_IF_FALSE | 38,094,000 | 0.3% | 65.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 38,057,580 | 0.3% | 65.8% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 36,988,940 | 0.3% | 66.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 36,617,660 | 0.3% | 66.3% |
| LOAD_ATTR_SLOT RETURN_VALUE | 36,469,518 | 0.3% | 66.5% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 36,160,020 | 0.3% | 66.8% |
| POP_TOP LOAD_FAST_LOAD_FAST | 35,282,040 | 0.2% | 67.0% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 34,765,420 | 0.2% | 67.3% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 34,706,843 | 0.2% | 67.5% |
| LOAD_FAST TO_BOOL_LIST | 34,698,760 | 0.2% | 67.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 34,584,380 | 0.2% | 68.0% |
| RETURN_VALUE POP_TOP | 34,488,960 | 0.2% | 68.3% |
| LOAD_FAST TO_BOOL_BOOL | 34,233,680 | 0.2% | 68.5% |
| LOAD_CONST COMPARE_OP_STR | 34,172,620 | 0.2% | 68.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 33,752,980 | 0.2% | 69.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 32,504,500 | 0.2% | 69.2% |
| BUILD_LIST STORE_FAST | 31,872,269 | 0.2% | 69.4% |
| STORE_ATTR_SLOT LOAD_GLOBAL_BUILTIN | 31,685,060 | 0.2% | 69.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 30,625,920 | 0.2% | 69.9% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 30,484,380 | 0.2% | 70.1% |
| NOP LOAD_FAST | 30,179,320 | 0.2% | 70.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,869,760 | 77.6% |
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
| RESUME_CHECK | 69,740,888 | 57.7% |
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
| LOAD_CONST | 19,974,669 | 48.9% |
| LOAD_FAST_LOAD_FAST | 15,020,700 | 36.8% |
| LOAD_FAST | 3,486,580 | 8.5% |
| LOAD_GLOBAL_MODULE | 1,199,040 | 2.9% |
| ENTER_EXECUTOR | 464,211 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,180,880 | 42.1% |
| CONTAINS_OP | 4,464,740 | 10.9% |
| LOAD_CONST | 4,422,640 | 10.8% |
| LOAD_FAST | 3,199,660 | 7.8% |
| RETURN_VALUE | 2,830,040 | 6.9% |


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
| LOAD_CONST | 43,200 | 56.9% |
| BUILD_SLICE | 17,280 | 22.8% |
| LOAD_FAST | 12,540 | 16.5% |
| LOAD_FAST_LOAD_FAST | 2,880 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 44,440 | 58.6% |
| LOAD_DEREF | 17,280 | 22.8% |
| JUMP_BACKWARD | 11,240 | 14.8% |
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
| LOAD_FAST | 2,173,440 | 72.5% |
| RETURN_VALUE | 413,360 | 13.8% |
| BINARY_SUBSCR_TUPLE_INT | 281,600 | 9.4% |
| CONVERT_VALUE | 67,960 | 2.3% |
| LOAD_ATTR_SLOT | 38,660 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,924,360 | 64.2% |
| BUILD_STRING | 1,075,360 | 35.8% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 88.9% |
| LOAD_CONST | 320 | 11.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 47,911,940 | 39.4% |
| LOAD_FAST | 28,893,140 | 23.8% |
| CALL_BUILTIN_CLASS | 19,038,540 | 15.7% |
| BINARY_SUBSCR_DICT | 12,587,800 | 10.4% |
| CALL | 2,651,080 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 45,234,672 | 37.2% |
| LOAD_FAST_AND_CLEAR | 26,673,600 | 22.0% |
| FOR_ITER_TUPLE | 19,158,103 | 15.8% |
| FOR_ITER | 14,576,965 | 12.0% |
| FOR_ITER_RANGE | 5,973,100 | 4.9% |


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
| RETURN_VALUE | 49,259,788 | 40.7% |
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
| LOAD_CONST | 8,289,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,158,500 | 50.2% |
| SET_FUNCTION_ATTRIBUTE | 4,055,460 | 48.9% |
| LOAD_CONST | 48,060 | 0.6% |
| LOAD_GLOBAL_MODULE | 14,280 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 7,240 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,134,560 | 28.3% |
| POP_JUMP_IF_TRUE | 14,082,560 | 26.4% |
| POP_JUMP_IF_FALSE | 9,167,800 | 17.2% |
| RESUME_CHECK | 6,658,660 | 12.5% |
| CALL_LIST_APPEND | 2,435,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,179,320 | 56.5% |
| LOAD_CONST | 14,777,960 | 27.7% |
| LOAD_GLOBAL_BUILTIN | 4,745,140 | 8.9% |
| LOAD_GLOBAL_MODULE | 3,045,980 | 5.7% |
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
| ENTER_EXECUTOR | 13,560 | 0.3% |
| JUMP_BACKWARD | 960 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 105,766,640 | 47.9% |
| RETURN_VALUE | 34,488,960 | 15.6% |
| POP_JUMP_IF_FALSE | 20,696,031 | 9.4% |
| POP_JUMP_IF_TRUE | 17,347,300 | 7.9% |
| RESUME_CHECK | 7,991,480 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,780,864 | 42.5% |
| LOAD_FAST_LOAD_FAST | 35,282,040 | 16.0% |
| ENTER_EXECUTOR | 25,741,148 | 11.7% |
| RETURN_CONST | 23,024,760 | 10.4% |
| LOAD_CONST | 8,837,200 | 4.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 2,286,680 | 55.1% |
| LOAD_ATTR_SLOT | 1,263,960 | 30.4% |
| RERAISE | 213,440 | 5.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 200,420 | 4.8% |
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
| LOAD_FAST | 17,666,565 | 50.8% |
| LOAD_ATTR | 8,423,120 | 24.2% |
| LOAD_ATTR_MODULE | 4,903,040 | 14.1% |
| BINARY_SUBSCR_DICT | 1,481,440 | 4.3% |
| LOAD_SUPER_ATTR_ATTR | 1,077,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,974,385 | 80.4% |
| LOAD_FAST_LOAD_FAST | 5,622,900 | 16.2% |
| CALL | 578,400 | 1.7% |
| LOAD_CONST | 283,100 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 187,560 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,222,960 | 54.2% |
| CALL_FUNCTION_EX | 2,281,920 | 29.3% |
| COPY_FREE_VARS | 967,140 | 12.4% |
| ENTER_EXECUTOR | 215,280 | 2.8% |
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
| LOAD_FAST | 118,449,268 | 29.9% |
| RETURN_VALUE | 80,686,084 | 20.4% |
| RETURN_CONST | 42,797,460 | 10.8% |
| LOAD_ATTR_SLOT | 36,469,518 | 9.2% |
| CALL | 12,594,440 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 90,165,220 | 22.8% |
| RETURN_VALUE | 80,686,084 | 20.4% |
| LOAD_FAST | 50,110,860 | 12.6% |
| INTERPRETER_EXIT | 49,259,788 | 12.4% |
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
| LOAD_ATTR | 9,397,780 | 46.1% |
| LOAD_FAST | 6,940,600 | 34.0% |
| LOAD_ATTR_SLOT | 2,685,200 | 13.2% |
| COPY | 1,088,700 | 5.3% |
| LOAD_ATTR_WITH_HINT | 73,100 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,072,940 | 83.7% |
| POP_JUMP_IF_TRUE | 2,878,620 | 14.1% |
| UNARY_NOT | 294,700 | 1.4% |
| TO_BOOL_BOOL | 48,620 | 0.2% |
| TO_BOOL | 43,940 | 0.2% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,340 | 85.9% |
| LOAD_FAST | 220 | 14.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,560 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,008,820 | 51.7% |
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
| TO_BOOL_BOOL | 22,824,820 | 87.2% |
| TO_BOOL_LIST | 2,525,220 | 9.7% |
| TO_BOOL_STR | 369,580 | 1.4% |
| TO_BOOL | 294,700 | 1.1% |
| TO_BOOL_INT | 139,280 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,688,620 | 52.3% |
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
| CALL_LEN | 2,644,140 | 54.1% |
| LOAD_FAST | 483,760 | 9.9% |
| BUILD_LIST | 374,160 | 7.7% |
| STORE_FAST | 346,600 | 7.1% |
| LOAD_CONST | 244,080 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,900,760 | 38.9% |
| STORE_FAST | 1,219,440 | 24.9% |
| CALL_PY_EXACT_ARGS | 507,920 | 10.4% |
| LOAD_CONST | 288,380 | 5.9% |
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
| SWAP | 24,272,100 | 28.9% |
| STORE_FAST | 18,511,800 | 22.0% |
| LOAD_GLOBAL_MODULE | 12,122,780 | 14.4% |
| RESUME_CHECK | 8,677,460 | 10.3% |
| STORE_ATTR_SLOT | 4,211,900 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,872,269 | 37.9% |
| SWAP | 24,272,100 | 28.9% |
| CALL | 12,492,700 | 14.9% |
| LOAD_FAST | 8,091,560 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 2,538,120 | 3.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,105,940 | 36.3% |
| LOAD_CONST | 1,666,280 | 14.7% |
| STORE_ATTR_INSTANCE_VALUE | 960,220 | 8.5% |
| RESUME_CHECK | 929,000 | 8.2% |
| POP_JUMP_IF_FALSE | 796,480 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,354,680 | 56.2% |
| STORE_FAST | 1,717,800 | 15.2% |
| LOAD_CONST | 1,611,560 | 14.3% |
| SWAP | 654,220 | 5.8% |
| RETURN_VALUE | 271,360 | 2.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,747,280 | 93.0% |
| LOAD_CONST | 109,760 | 5.8% |
| LOAD_FAST | 21,760 | 1.2% |
| POP_JUMP_IF_FALSE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,747,280 | 93.0% |
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
| FORMAT_SIMPLE | 1,075,360 | 54.7% |
| LOAD_CONST | 891,440 | 45.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 560,100 | 28.5% |
| CALL | 513,200 | 26.1% |
| RETURN_VALUE | 376,640 | 19.1% |
| LOAD_FAST | 167,720 | 8.5% |
| CALL_PY_EXACT_ARGS | 85,400 | 4.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,103,036 | 34.7% |
| LOAD_GLOBAL_MODULE | 5,216,760 | 16.3% |
| LOAD_ATTR_SLOT | 5,109,433 | 16.0% |
| LOAD_FAST_LOAD_FAST | 4,352,280 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,366,980 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,312,260 | 26.0% |
| CALL_BUILTIN_O | 5,669,901 | 17.7% |
| CALL_ISINSTANCE | 4,530,120 | 14.1% |
| LOAD_CONST | 4,057,060 | 12.7% |
| LOAD_FAST | 3,557,320 | 11.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,581,156 | 18.4% |
| BUILD_LIST | 12,492,700 | 18.2% |
| LOAD_FAST_LOAD_FAST | 6,961,780 | 10.2% |
| RETURN_VALUE | 5,677,264 | 8.3% |
| ENTER_EXECUTOR | 5,384,216 | 7.9% |

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
| LOAD_CONST | 75,037,860 | 98.1% |
| ENTER_EXECUTOR | 1,469,240 | 1.9% |

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
| LOAD_ATTR_SLOT | 18,254,590 | 42.4% |
| LOAD_GLOBAL_MODULE | 8,646,720 | 20.1% |
| LOAD_CONST | 7,813,163 | 18.1% |
| LOAD_ATTR_MODULE | 3,272,780 | 7.6% |
| LOAD_FAST | 2,161,120 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 16,886,892 | 39.2% |
| POP_JUMP_IF_FALSE | 13,702,563 | 31.8% |
| RETURN_VALUE | 8,407,208 | 19.5% |
| POP_JUMP_IF_TRUE | 2,803,040 | 6.5% |
| EXTENDED_ARG | 1,029,600 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,966,649 | 49.7% |
| LOAD_FAST_LOAD_FAST | 18,215,287 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 7,843,482 | 8.3% |
| LOAD_ATTR_SLOT | 4,855,206 | 5.1% |
| BINARY_SUBSCR | 4,464,740 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 79,467,627 | 84.0% |
| POP_JUMP_IF_TRUE | 11,426,785 | 12.1% |
| RETURN_VALUE | 2,852,620 | 3.0% |
| EXTENDED_ARG | 466,960 | 0.5% |
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
| COMPARE_OP | 16,886,892 | 33.2% |
| LOAD_FAST | 6,215,560 | 12.2% |
| CALL_ISINSTANCE | 4,261,580 | 8.4% |
| SWAP | 3,592,320 | 7.1% |
| COMPARE_OP_STR | 3,095,580 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 38,524,084 | 75.8% |
| COMPARE_OP_INT | 3,580,400 | 7.0% |
| TO_BOOL_NONE | 1,795,240 | 3.5% |
| TO_BOOL_STR | 1,506,780 | 3.0% |
| TO_BOOL | 1,088,700 | 2.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 47,450,260 | 50.5% |
| CACHE | 43,492,280 | 46.3% |
| CALL | 1,923,440 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 450,680 | 0.5% |
| CALL_KW | 424,320 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,014,160 | 99.0% |
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
| JUMP_BACKWARD | 340 | 0.2% |
| ENTER_EXECUTOR | 300 | 0.1% |


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
| POP_JUMP_IF_TRUE | 26,804,620 | 26.3% |
| POP_TOP | 25,741,148 | 25.2% |
| LIST_APPEND | 25,344,684 | 24.8% |
| CALL_LIST_APPEND | 8,855,400 | 8.7% |
| EXTENDED_ARG | 4,445,580 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,744,338 | 27.2% |
| RETURN_CONST | 12,496,354 | 12.2% |
| SWAP | 11,105,424 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 7,884,281 | 7.7% |
| CALL | 5,384,216 | 5.3% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,433,280 | 31.4% |
| GET_ITER | 4,744,880 | 14.3% |
| POP_TOP | 3,534,420 | 10.6% |
| JUMP_BACKWARD | 3,213,980 | 9.7% |
| LOAD_ATTR_SLOT | 1,255,320 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,950,140 | 44.9% |
| FOR_ITER | 6,336,920 | 19.0% |
| ENTER_EXECUTOR | 4,445,580 | 13.4% |
| POP_JUMP_IF_NONE | 2,423,400 | 7.3% |
| JUMP_BACKWARD | 2,153,880 | 6.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 16,086,767 | 42.4% |
| GET_ITER | 14,576,965 | 38.4% |
| EXTENDED_ARG | 6,336,920 | 16.7% |
| SWAP | 723,760 | 1.9% |
| LOAD_FAST | 82,460 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 13,824,400 | 36.5% |
| STORE_FAST | 5,935,043 | 15.6% |
| RETURN_CONST | 5,604,800 | 14.8% |
| LOAD_FAST | 4,700,734 | 12.4% |
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
| LOAD_GLOBAL_MODULE | 41,593,140 | 73.1% |
| LOAD_CONST | 7,193,980 | 12.7% |
| LOAD_FAST | 6,995,440 | 12.3% |
| LOAD_FAST_LOAD_FAST | 890,240 | 1.6% |
| LOAD_ATTR | 95,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 38,094,000 | 67.0% |
| POP_JUMP_IF_TRUE | 11,627,840 | 20.4% |
| RETURN_VALUE | 4,099,520 | 7.2% |
| LOAD_FAST | 1,637,440 | 2.9% |
| COPY | 824,600 | 1.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,420,002 | 21.3% |
| STORE_SUBSCR | 3,032,100 | 14.6% |
| POP_JUMP_IF_NOT_NONE | 2,553,800 | 12.3% |
| EXTENDED_ARG | 2,153,880 | 10.4% |
| MAP_ADD | 1,806,820 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 16,086,767 | 77.6% |
| EXTENDED_ARG | 3,213,980 | 15.5% |
| FOR_ITER_GEN | 1,230,940 | 5.9% |
| FOR_ITER_LIST | 157,012 | 0.8% |
| FOR_ITER_TUPLE | 14,101 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 363,252 | 100.0% |
| RESUME | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 363,272 | 100.0% |
| SEND | 40 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 14,018,240 | 29.6% |
| LOAD_ATTR_SLOT | 13,640,820 | 28.8% |
| LOAD_FAST | 6,605,720 | 13.9% |
| STORE_ATTR_SLOT | 5,506,940 | 11.6% |
| STORE_FAST | 3,878,096 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,644,676 | 49.9% |
| STORE_FAST | 14,581,440 | 30.8% |
| MAP_ADD | 6,275,520 | 13.2% |
| LOAD_CONST | 1,026,560 | 2.2% |
| LOAD_GLOBAL_MODULE | 958,507 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,141,020 | 59.5% |
| CALL | 7,028,600 | 27.6% |
| LOAD_FAST | 1,604,804 | 6.3% |
| BINARY_SUBSCR_LIST_INT | 336,300 | 1.3% |
| LOAD_ATTR_SLOT | 308,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 25,344,684 | 99.5% |
| JUMP_BACKWARD | 119,980 | 0.5% |


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
| LOAD_FAST | 76,326,542 | 64.4% |
| LOAD_GLOBAL_MODULE | 30,625,920 | 25.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,611,180 | 2.2% |
| ENTER_EXECUTOR | 2,213,162 | 1.9% |
| LOAD_FAST_LOAD_FAST | 2,057,360 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,321,932 | 46.7% |
| LOAD_FAST_LOAD_FAST | 11,093,100 | 9.4% |
| TO_BOOL | 9,397,780 | 7.9% |
| PUSH_NULL | 8,423,120 | 7.1% |
| CALL_PY_EXACT_ARGS | 6,827,680 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 170,370,120 | 24.3% |
| LOAD_FAST | 158,344,705 | 22.6% |
| LOAD_CONST | 53,935,540 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 27,793,300 | 4.0% |
| MAP_ADD | 27,390,400 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 282,002,769 | 40.3% |
| BINARY_SUBSCR_DICT | 101,470,200 | 14.5% |
| CALL_KW | 75,037,860 | 10.7% |
| LOAD_CONST | 53,935,540 | 7.7% |
| COMPARE_OP_STR | 34,172,620 | 4.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 92,064,060 | 70.9% |
| LOAD_DEREF | 12,941,260 | 10.0% |
| LOAD_FAST | 5,488,268 | 4.2% |
| LOAD_GLOBAL_MODULE | 5,011,880 | 3.9% |
| POP_JUMP_IF_FALSE | 2,605,176 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,336,791 | 68.0% |
| LOAD_DEREF | 12,941,260 | 10.0% |
| LOAD_ATTR_SLOT | 7,774,220 | 6.0% |
| LOAD_CONST | 4,305,703 | 3.3% |
| LOAD_FAST_LOAD_FAST | 3,638,320 | 2.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 382,090,665 | 13.0% |
| RESUME_CHECK | 302,604,830 | 10.3% |
| LOAD_CONST | 282,002,769 | 9.6% |
| POP_JUMP_IF_FALSE | 254,022,395 | 8.7% |
| STORE_FAST | 244,693,839 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 436,159,151 | 14.9% |
| STORE_ATTR_SLOT | 358,936,493 | 12.2% |
| LOAD_GLOBAL_MODULE | 272,153,948 | 9.3% |
| LOAD_ATTR_METHOD_NO_DICT | 190,693,971 | 6.5% |
| CALL_PY_EXACT_ARGS | 163,164,227 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,673,600 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,460 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,662,720 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,460 | 4.5% |
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
| STORE_ATTR_SLOT | 141,091,380 | 24.9% |
| LOAD_SUPER_ATTR_METHOD | 71,619,920 | 12.6% |
| RESUME_CHECK | 60,538,700 | 10.7% |
| LOAD_GLOBAL_MODULE | 46,249,480 | 8.1% |
| STORE_FAST | 42,042,732 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 248,651,140 | 43.8% |
| CALL_PY_EXACT_ARGS | 102,868,480 | 18.1% |
| STORE_ATTR_INSTANCE_VALUE | 44,207,520 | 7.8% |
| LOAD_FAST | 39,436,636 | 6.9% |
| CONTAINS_OP | 18,215,287 | 3.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,600 | 18.8% |
| POP_JUMP_IF_FALSE | 44,610 | 18.4% |
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
| MAKE_CELL | 21,839,240 | 65.7% |
| CALL_PY_EXACT_ARGS | 4,902,300 | 14.7% |
| CALL_KW | 4,870,760 | 14.7% |
| BINARY_SUBSCR_GETITEM | 940,780 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 585,560 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,839,240 | 65.7% |
| RESUME_CHECK | 11,386,980 | 34.3% |
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
| JUMP_BACKWARD | 1,806,820 | 5.9% |
| CALL_FUNCTION_EX | 1,611,200 | 5.2% |
| ENTER_EXECUTOR | 19,920 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 280,999,030 | 51.5% |
| CONTAINS_OP | 79,467,627 | 14.6% |
| IS_OP | 38,094,000 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 25,229,551 | 4.6% |
| TO_BOOL_NONE | 23,003,729 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 254,022,395 | 46.6% |
| LOAD_GLOBAL_BUILTIN | 133,107,263 | 24.4% |
| LOAD_GLOBAL_MODULE | 47,455,960 | 8.7% |
| LOAD_FAST_LOAD_FAST | 27,856,523 | 5.1% |
| POP_TOP | 20,696,031 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,177,080 | 49.0% |
| LOAD_ATTR_SLOT | 30,484,380 | 38.1% |
| LOAD_ATTR | 4,245,220 | 5.3% |
| EXTENDED_ARG | 2,423,400 | 3.0% |
| BINARY_SUBSCR_DICT | 2,092,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,057,580 | 47.6% |
| RETURN_CONST | 15,863,360 | 19.8% |
| JUMP_FORWARD | 14,018,240 | 17.5% |
| LOAD_CONST | 4,549,000 | 5.7% |
| LOAD_GLOBAL_BUILTIN | 2,981,310 | 3.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,781,700 | 87.7% |
| LOAD_ATTR_SLOT | 4,806,700 | 5.0% |
| BINARY_SUBSCR_DICT | 3,950,580 | 4.1% |
| LOAD_FAST_CHECK | 2,008,560 | 2.1% |
| BINARY_SUBSCR | 298,060 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,988,940 | 38.3% |
| LOAD_FAST | 19,822,400 | 20.5% |
| LOAD_CONST | 13,982,280 | 14.5% |
| LOAD_FAST_LOAD_FAST | 10,715,080 | 11.1% |
| RETURN_CONST | 4,657,980 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 101,257,428 | 45.4% |
| TO_BOOL_LIST | 34,765,420 | 15.6% |
| COMPARE_OP_STR | 30,040,140 | 13.5% |
| COMPARE_OP_INT | 11,991,391 | 5.4% |
| IS_OP | 11,627,840 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,044,041 | 44.0% |
| ENTER_EXECUTOR | 26,804,620 | 12.0% |
| LOAD_GLOBAL_MODULE | 25,071,833 | 11.3% |
| POP_TOP | 17,347,300 | 7.8% |
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
| POP_TOP | 23,024,760 | 7.7% |
| POP_JUMP_IF_FALSE | 17,989,480 | 6.0% |
| POP_JUMP_IF_NONE | 15,863,360 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 105,766,640 | 35.3% |
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
| BINARY_OP_ADD_UNICODE | 1,280,880 | 89.4% |
| STORE_FAST_LOAD_FAST | 64,000 | 4.5% |
| LOAD_ATTR_INSTANCE_VALUE | 63,180 | 4.4% |
| LOAD_FAST | 17,600 | 1.2% |
| RETURN_VALUE | 6,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,342,120 | 93.6% |
| JUMP_BACKWARD | 91,120 | 6.4% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,055,460 | 77.6% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,712,980 | 32.8% |
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
| LOAD_FAST_LOAD_FAST | 9,406,480 | 75.6% |
| LOAD_FAST | 2,884,040 | 23.2% |
| SWAP | 118,440 | 1.0% |
| STORE_ATTR | 26,620 | 0.2% |
| LOAD_ATTR_SLOT | 9,680 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,386,860 | 43.3% |
| LOAD_FAST | 3,213,780 | 25.8% |
| RETURN_CONST | 3,177,280 | 25.5% |
| LOAD_CONST | 262,020 | 2.1% |
| LOAD_GLOBAL_MODULE | 257,880 | 2.1% |


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
| FOR_ITER_LIST | 37,580 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,929,040 | 62.0% |
| LOAD_FAST | 1,131,200 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 258,860 | 5.5% |
| LOAD_CONST | 189,160 | 4.0% |
| LOAD_DEREF | 177,000 | 3.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 90,165,220 | 18.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 51,951,046 | 10.4% |
| FOR_ITER_LIST | 49,784,224 | 10.0% |
| LOAD_ATTR_SLOT | 45,561,460 | 9.2% |
| BUILD_LIST | 31,872,269 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 244,693,839 | 49.2% |
| LOAD_GLOBAL_BUILTIN | 73,322,666 | 14.7% |
| LOAD_GLOBAL_MODULE | 58,687,300 | 11.8% |
| LOAD_FAST_LOAD_FAST | 42,042,732 | 8.5% |
| LOAD_CONST | 18,815,109 | 3.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,306,126 | 60.9% |
| FOR_ITER_TUPLE | 1,749,480 | 20.1% |
| FOR_ITER | 1,317,820 | 15.1% |
| FOR_ITER_RANGE | 334,960 | 3.8% |
| CALL_LEN | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,977,120 | 34.2% |
| LOAD_CONST | 1,720,726 | 19.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,246,160 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 880,880 | 10.1% |
| LOAD_ATTR_METHOD_NO_DICT | 525,300 | 6.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 15,631,760 | 47.2% |
| UNPACK_SEQUENCE_LIST | 14,619,180 | 44.2% |
| UNPACK_SEQUENCE_TUPLE | 1,884,820 | 5.7% |
| COPY | 611,800 | 1.8% |
| BINARY_SUBSCR_LIST_INT | 105,580 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,555,940 | 74.2% |
| LOAD_FAST_LOAD_FAST | 3,690,220 | 11.1% |
| STORE_FAST | 2,032,220 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,893,100 | 5.7% |
| LOAD_GLOBAL_MODULE | 367,620 | 1.1% |


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
| LOAD_FAST_AND_CLEAR | 26,662,720 | 30.4% |
| BUILD_LIST | 24,272,100 | 27.6% |
| ENTER_EXECUTOR | 11,105,424 | 12.6% |
| FOR_ITER_LIST | 9,013,496 | 10.3% |
| LOAD_FAST | 4,831,800 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 24,272,100 | 27.6% |
| FOR_ITER_LIST | 22,402,680 | 25.5% |
| STORE_FAST | 21,419,080 | 24.4% |
| COPY | 3,592,320 | 4.1% |
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
| FOR_ITER_LIST | 8,113 | 5.9% |
| FOR_ITER | 4,540 | 3.3% |
| RETURN_VALUE | 3,680 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 98,493 | 71.3% |
| STORE_FAST_STORE_FAST | 33,300 | 24.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,120 | 3.0% |
| UNPACK_SEQUENCE_TUPLE | 980 | 0.7% |
| UNPACK_SEQUENCE | 880 | 0.6% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,524,560 | 22.5% |
| LOAD_CONST | 1,885,440 | 16.8% |
| ENTER_EXECUTOR | 1,707,232 | 15.2% |
| LOAD_FAST | 1,142,140 | 10.2% |
| CALL_ISINSTANCE | 797,780 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,570,360 | 85.4% |
| STORE_FAST | 897,560 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 376,200 | 3.4% |
| YIELD_VALUE | 363,312 | 3.2% |
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
| LOAD_CONST | 4,337,265 | 56.4% |
| CALL_LEN | 1,511,400 | 19.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,467,800 | 19.1% |
| LOAD_FAST | 194,320 | 2.5% |
| LOAD_FAST_LOAD_FAST | 178,333 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,159,380 | 41.1% |
| LOAD_FAST | 2,066,353 | 26.9% |
| SWAP | 991,000 | 12.9% |
| LOAD_FAST_LOAD_FAST | 688,900 | 9.0% |
| LOAD_CONST | 213,940 | 2.8% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,342,320 | 35.2% |
| LOAD_FAST | 1,396,860 | 21.0% |
| CALL_METHOD_DESCRIPTOR_O | 984,600 | 14.8% |
| LOAD_FAST_LOAD_FAST | 984,220 | 14.8% |
| BINARY_SLICE | 450,740 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,924,320 | 28.9% |
| RETURN_VALUE | 1,346,260 | 20.2% |
| SET_ADD | 1,280,880 | 19.2% |
| STORE_FAST | 1,071,060 | 16.1% |
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
| LOAD_CONST | 3,566,345 | 93.7% |
| LOAD_FAST | 124,360 | 3.3% |
| CALL_LEN | 99,780 | 2.6% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.2% |
| LOAD_ATTR_SLOT | 3,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,849,840 | 48.6% |
| BINARY_SLICE | 890,220 | 23.4% |
| SWAP | 290,120 | 7.6% |
| STORE_FAST | 275,320 | 7.2% |
| BINARY_SUBSCR_LIST_INT | 263,540 | 6.9% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 101,470,200 | 86.0% |
| LOAD_FAST | 9,114,527 | 7.7% |
| BINARY_SUBSCR_DICT | 3,040,560 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 1,821,400 | 1.5% |
| LOAD_DEREF | 1,502,160 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,857,780 | 18.5% |
| STORE_FAST | 20,022,776 | 17.0% |
| LOAD_CONST | 19,994,560 | 16.9% |
| GET_ITER | 12,587,800 | 10.7% |
| CALL_PY_EXACT_ARGS | 9,517,360 | 8.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,533,080 | 54.9% |
| ENTER_EXECUTOR | 852,980 | 30.5% |
| LOAD_FAST_LOAD_FAST | 398,620 | 14.3% |
| LOAD_CONST | 7,020 | 0.3% |
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
| LOAD_CONST | 8,581,060 | 44.4% |
| LOAD_FAST | 5,636,320 | 29.2% |
| LOAD_FAST_LOAD_FAST | 4,697,500 | 24.3% |
| BINARY_OP_SUBTRACT_INT | 263,540 | 1.4% |
| BINARY_OP_ADD_INT | 91,000 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,856,100 | 14.8% |
| STORE_FAST | 2,782,440 | 14.4% |
| LOAD_GLOBAL_MODULE | 2,255,320 | 11.7% |
| BINARY_SUBSCR_DICT | 1,821,400 | 9.4% |
| CALL_PY_EXACT_ARGS | 1,606,500 | 8.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 745,820 | 65.8% |
| LOAD_FAST_LOAD_FAST | 231,280 | 20.4% |
| BINARY_OP_ADD_INT | 117,560 | 10.4% |
| BINARY_OP_SUBTRACT_INT | 36,960 | 3.3% |
| LOAD_FAST | 1,700 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 632,080 | 55.7% |
| LOAD_FAST | 349,800 | 30.9% |
| CALL_BUILTIN_O | 67,820 | 6.0% |
| LOAD_FAST_LOAD_FAST | 33,880 | 3.0% |
| COMPARE_OP_STR | 33,840 | 3.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,660,540 | 99.6% |
| LOAD_FAST_LOAD_FAST | 4,400 | 0.3% |
| BINARY_SUBSCR | 1,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 307,600 | 18.5% |
| FORMAT_SIMPLE | 281,600 | 16.9% |
| LOAD_FAST_LOAD_FAST | 208,980 | 12.5% |
| STORE_FAST | 201,680 | 12.1% |
| CALL | 155,500 | 9.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,126,680 | 46.9% |
| LOAD_FAST | 1,826,580 | 27.4% |
| LOAD_GLOBAL_MODULE | 700,860 | 10.5% |
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
| LOAD_FAST | 19,592,400 | 65.2% |
| BINARY_SUBSCR_DICT | 6,452,840 | 21.5% |
| LOAD_CONST | 2,692,860 | 9.0% |
| ENTER_EXECUTOR | 923,460 | 3.1% |
| CALL_PY_EXACT_ARGS | 101,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 27,261,800 | 90.8% |
| POP_TOP | 2,625,160 | 8.7% |
| CALL_PY_EXACT_ARGS | 101,160 | 0.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 49,740 | 0.2% |
| RESUME | 980 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,067,220 | 29.9% |
| LOAD_GLOBAL_BUILTIN | 7,134,500 | 17.7% |
| LOAD_ATTR_SLOT | 4,493,398 | 11.1% |
| LOAD_ATTR_CLASS | 3,789,040 | 9.4% |
| CALL_LEN | 3,073,740 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,038,540 | 47.2% |
| LOAD_FAST | 10,530,140 | 26.1% |
| STORE_FAST | 3,772,660 | 9.4% |
| RETURN_VALUE | 2,544,960 | 6.3% |
| MAP_ADD | 1,674,520 | 4.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,937,185 | 42.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,659,640 | 33.1% |
| LOAD_FAST_LOAD_FAST | 2,638,980 | 18.7% |
| LOAD_FAST | 664,900 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 90,280 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,896,460 | 20.6% |
| RETURN_VALUE | 2,325,720 | 16.5% |
| PUSH_EXC_INFO | 2,286,680 | 16.2% |
| POP_TOP | 2,104,220 | 14.9% |
| TO_BOOL_BOOL | 2,040,500 | 14.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,215,060 | 84.8% |
| RETURN_GENERATOR | 385,440 | 10.2% |
| CALL_BUILTIN_CLASS | 141,720 | 3.7% |
| RETURN_VALUE | 47,920 | 1.3% |
| LOAD_CONST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,621,500 | 69.1% |
| COPY | 335,360 | 8.8% |
| LOAD_CONST | 304,300 | 8.0% |
| PUSH_EXC_INFO | 200,420 | 5.3% |
| RETURN_VALUE | 144,500 | 3.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 5,669,901 | 35.9% |
| RETURN_GENERATOR | 4,748,320 | 30.0% |
| LOAD_FAST | 2,121,180 | 13.4% |
| LOAD_GLOBAL_MODULE | 1,203,240 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 653,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,973,586 | 44.1% |
| LOAD_FAST | 4,956,413 | 31.3% |
| TO_BOOL_BOOL | 1,700,040 | 10.7% |
| CALL_PY_EXACT_ARGS | 904,580 | 5.7% |
| STORE_FAST | 459,400 | 2.9% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 234,472,052 | 84.2% |
| LOAD_GLOBAL_BUILTIN | 36,160,020 | 13.0% |
| BUILD_TUPLE | 4,530,120 | 1.6% |
| LOAD_ATTR | 1,896,660 | 0.7% |
| LOAD_ATTR_MODULE | 940,926 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 272,012,714 | 97.7% |
| COPY | 4,261,580 | 1.5% |
| YIELD_VALUE | 797,780 | 0.3% |
| RETURN_VALUE | 745,284 | 0.3% |
| STORE_FAST | 395,980 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,220,160 | 56.8% |
| LOAD_ATTR_SLOT | 11,056,960 | 31.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,904,620 | 5.4% |
| LOAD_DEREF | 1,900,680 | 5.3% |
| LOAD_ATTR | 217,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,429,840 | 26.5% |
| COMPARE_OP_INT | 5,967,340 | 16.8% |
| LOAD_GLOBAL_BUILTIN | 4,564,260 | 12.8% |
| SWAP | 3,580,440 | 10.1% |
| CALL_BUILTIN_CLASS | 3,073,740 | 8.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,024,300 | 77.9% |
| RETURN_VALUE | 2,635,720 | 8.2% |
| ENTER_EXECUTOR | 1,408,684 | 4.4% |
| LOAD_CONST | 567,720 | 1.8% |
| BUILD_TUPLE | 548,216 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,527,100 | 54.5% |
| ENTER_EXECUTOR | 8,855,400 | 27.5% |
| NOP | 2,435,240 | 7.6% |
| EXTENDED_ARG | 683,180 | 2.1% |
| LOAD_CONST | 680,720 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,584,380 | 54.5% |
| LOAD_ATTR_METHOD_NO_DICT | 20,434,920 | 32.2% |
| LOAD_CONST | 2,720,280 | 4.3% |
| ENTER_EXECUTOR | 1,886,940 | 3.0% |
| LOAD_GLOBAL_MODULE | 1,311,890 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 51,951,046 | 81.8% |
| POP_TOP | 4,744,140 | 7.5% |
| LOAD_FAST | 2,743,264 | 4.3% |
| CALL_PY_EXACT_ARGS | 923,140 | 1.5% |
| LOAD_ATTR_METHOD_NO_DICT | 708,360 | 1.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,829,260 | 90.2% |
| LOAD_FAST | 187,400 | 6.0% |
| LOAD_ATTR_MODULE | 92,440 | 2.9% |
| LOAD_ATTR_METHOD_NO_DICT | 25,800 | 0.8% |
| CALL | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,195,900 | 70.0% |
| LOAD_CONST | 343,240 | 10.9% |
| UNPACK_SEQUENCE_LIST | 192,800 | 6.1% |
| GET_ITER | 188,420 | 6.0% |
| CONTAINS_OP | 92,460 | 2.9% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,980,900 | 98.2% |
| ENTER_EXECUTOR | 40,100 | 1.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,200 | 0.2% |
| LOAD_ATTR | 5,640 | 0.2% |
| CALL | 1,540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,727,860 | 56.9% |
| LOAD_FAST | 574,900 | 18.9% |
| POP_TOP | 320,620 | 10.6% |
| CALL_BUILTIN_CLASS | 239,760 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 89,560 | 3.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,516,600 | 53.7% |
| LOAD_FAST | 3,966,344 | 32.7% |
| RETURN_VALUE | 631,520 | 5.2% |
| LOAD_ATTR_SLOT | 257,100 | 2.1% |
| BUILD_TUPLE | 243,160 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,077,660 | 41.9% |
| POP_TOP | 4,324,684 | 35.6% |
| BINARY_OP_ADD_INT | 1,467,800 | 12.1% |
| BINARY_OP_ADD_UNICODE | 984,600 | 8.1% |
| STORE_FAST | 194,100 | 1.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 163,164,227 | 37.4% |
| LOAD_FAST_LOAD_FAST | 102,868,480 | 23.6% |
| LOAD_ATTR_METHOD_NO_DICT | 74,527,940 | 17.1% |
| LOAD_ATTR_SLOT | 13,871,729 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,341,460 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 378,525,056 | 86.8% |
| COPY_FREE_VARS | 47,450,260 | 10.9% |
| MAKE_CELL | 4,902,300 | 1.1% |
| RETURN_GENERATOR | 4,222,960 | 1.0% |
| CALL_PY_EXACT_ARGS | 721,226 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 7,932,960 | 38.3% |
| LOAD_FAST | 6,914,420 | 33.4% |
| LOAD_FAST_LOAD_FAST | 1,837,940 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,245,960 | 6.0% |
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
| LOAD_FAST | 1,218,980 | 100.0% |
| UNARY_NOT | 280 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,660 | 80.7% |
| CALL_BUILTIN_O | 187,180 | 15.4% |
| STORE_FAST | 33,140 | 2.7% |
| CALL | 15,040 | 1.2% |
| BUILD_TUPLE | 300 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,818,540 | 92.5% |
| LOAD_ATTR_SLOT | 1,464,688 | 7.2% |
| RETURN_VALUE | 22,540 | 0.1% |
| LOAD_FAST_CHECK | 19,480 | 0.1% |
| RETURN_GENERATOR | 8,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,960,180 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 762,360 | 3.7% |
| BUILD_TUPLE | 531,088 | 2.6% |
| CALL_PY_EXACT_ARGS | 33,560 | 0.2% |
| RETURN_VALUE | 24,440 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,111,500 | 100.0% |
| LOAD_CONST | 300 | 0.0% |
| CALL | 200 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,950,040 | 62.5% |
| STORE_FAST | 1,538,460 | 13.8% |
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
| LOAD_CONST | 14,888,211 | 38.4% |
| CALL_LEN | 5,967,340 | 15.4% |
| LOAD_GLOBAL_MODULE | 3,637,820 | 9.4% |
| COPY | 3,580,400 | 9.2% |
| LOAD_ATTR_CLASS | 3,555,000 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 22,383,415 | 57.7% |
| POP_JUMP_IF_TRUE | 11,991,391 | 30.9% |
| COPY | 2,105,732 | 5.4% |
| RETURN_VALUE | 1,277,561 | 3.3% |
| EXTENDED_ARG | 626,880 | 1.6% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,172,620 | 73.2% |
| LOAD_FAST | 9,063,660 | 19.4% |
| RETURN_VALUE | 957,820 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 836,346 | 1.8% |
| LOAD_ATTR_MODULE | 633,760 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 30,040,140 | 64.4% |
| POP_JUMP_IF_FALSE | 11,435,280 | 24.5% |
| COPY | 3,095,580 | 6.6% |
| RETURN_VALUE | 1,230,489 | 2.6% |
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
| GET_ITER | 45,234,672 | 59.9% |
| SWAP | 22,402,680 | 29.6% |
| LOAD_FAST | 5,163,980 | 6.8% |
| EXTENDED_ARG | 1,470,080 | 1.9% |
| ENTER_EXECUTOR | 1,096,345 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 49,784,224 | 65.9% |
| SWAP | 9,013,496 | 11.9% |
| LOAD_FAST | 5,760,842 | 7.6% |
| STORE_FAST_LOAD_FAST | 5,306,126 | 7.0% |
| RETURN_CONST | 3,428,486 | 4.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,973,100 | 86.7% |
| SWAP | 790,400 | 11.5% |
| EXTENDED_ARG | 117,360 | 1.7% |
| JUMP_BACKWARD | 7,460 | 0.1% |
| FOR_ITER | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,543,838 | 36.9% |
| LOAD_FAST | 1,909,360 | 27.7% |
| RETURN_CONST | 1,441,660 | 20.9% |
| LOAD_GLOBAL_MODULE | 658,260 | 9.6% |
| STORE_FAST_LOAD_FAST | 334,960 | 4.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,158,103 | 82.6% |
| SWAP | 2,756,760 | 11.9% |
| ENTER_EXECUTOR | 1,185,421 | 5.1% |
| EXTENDED_ARG | 35,480 | 0.2% |
| FOR_ITER_LIST | 31,053 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,685,992 | 59.0% |
| STORE_FAST | 6,721,476 | 29.0% |
| STORE_FAST_LOAD_FAST | 1,749,480 | 7.5% |
| SWAP | 709,900 | 3.1% |
| RETURN_CONST | 298,300 | 1.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,225,900 | 88.8% |
| LOAD_FAST | 1,544,160 | 10.4% |
| COPY | 105,520 | 0.7% |
| ENTER_EXECUTOR | 13,940 | 0.1% |
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
| LOAD_FAST | 124,914,538 | 80.6% |
| LOAD_FAST_LOAD_FAST | 12,634,402 | 8.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,948,940 | 3.8% |
| LOAD_GLOBAL_MODULE | 4,175,120 | 2.7% |
| LOAD_DEREF | 1,804,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,125,242 | 18.8% |
| LOAD_CONST | 27,793,300 | 17.9% |
| LOAD_ATTR_METHOD_NO_DICT | 14,290,290 | 9.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,941,900 | 8.4% |
| CONTAINS_OP | 7,843,482 | 5.1% |


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
| LOAD_FAST | 190,693,971 | 72.3% |
| LOAD_ATTR_SLOT | 26,325,340 | 10.0% |
| LOAD_ATTR_INSTANCE_VALUE | 14,290,290 | 5.4% |
| LOAD_GLOBAL_MODULE | 10,018,040 | 3.8% |
| ENTER_EXECUTOR | 7,884,281 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,050,417 | 44.4% |
| CALL_PY_EXACT_ARGS | 74,527,940 | 28.3% |
| LOAD_CONST | 25,432,420 | 9.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 20,434,920 | 7.8% |
| LOAD_GLOBAL_MODULE | 18,014,249 | 6.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,392,147 | 81.7% |
| LOAD_ATTR_INSTANCE_VALUE | 12,941,900 | 11.3% |
| LOAD_DEREF | 2,566,320 | 2.2% |
| LOAD_FAST_LOAD_FAST | 1,358,880 | 1.2% |
| LOAD_ATTR_WITH_HINT | 1,358,040 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,711,880 | 69.7% |
| LOAD_FAST_LOAD_FAST | 15,974,620 | 14.0% |
| CALL_PY_EXACT_ARGS | 11,341,460 | 9.9% |
| LOAD_CONST | 2,703,800 | 2.4% |
| LOAD_DEREF | 2,126,500 | 1.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 17,476,726 | 66.4% |
| LOAD_ATTR_MODULE | 5,854,680 | 22.2% |
| LOAD_ATTR_CLASS | 1,544,160 | 5.9% |
| LOAD_FAST_LOAD_FAST | 1,235,000 | 4.7% |
| LOAD_FAST | 202,480 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,854,680 | 22.2% |
| PUSH_NULL | 4,903,040 | 18.6% |
| LOAD_FAST | 4,144,500 | 15.7% |
| COMPARE_OP | 3,272,780 | 12.4% |
| LOAD_GLOBAL_MODULE | 1,606,640 | 6.1% |


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
| LOAD_FAST | 376,500 | 35.0% |
| BINARY_SUBSCR_DICT | 6,160 | 0.6% |
| LOAD_FAST_LOAD_FAST | 3,440 | 0.3% |
| STORE_FAST_LOAD_FAST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 690,720 | 64.2% |
| CALL_LEN | 137,880 | 12.8% |
| RETURN_VALUE | 105,260 | 9.8% |
| LOAD_FAST | 95,560 | 8.9% |
| POP_JUMP_IF_NONE | 35,960 | 3.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,106,067 | 55.2% |
| LOAD_ATTR_SLOT | 6,460,414 | 23.6% |
| ENTER_EXECUTOR | 4,949,700 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 482,920 | 1.8% |
| CALL | 93,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,544,084 | 93.4% |
| RETURN_VALUE | 1,067,172 | 3.9% |
| LOAD_FAST | 239,400 | 0.9% |
| STORE_FAST | 238,600 | 0.9% |
| LOAD_CONST | 105,300 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 436,159,151 | 88.2% |
| LOAD_ATTR_SLOT | 34,706,843 | 7.0% |
| LOAD_DEREF | 7,774,220 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,554,106 | 1.3% |
| STORE_FAST_LOAD_FAST | 2,977,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,427,360 | 12.0% |
| GET_ITER | 47,911,940 | 9.7% |
| STORE_FAST | 45,561,460 | 9.2% |
| RETURN_VALUE | 36,469,518 | 7.4% |
| LOAD_ATTR_SLOT | 34,706,843 | 7.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,671,120 | 57.1% |
| LOAD_FAST_LOAD_FAST | 6,461,320 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 6,299,880 | 20.4% |
| LOAD_ATTR_WITH_HINT | 500,740 | 1.6% |
| LOAD_DEREF | 10,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,686,140 | 31.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,625,480 | 11.7% |
| TO_BOOL_BOOL | 3,617,000 | 11.7% |
| COPY | 2,789,480 | 9.0% |
| LOAD_FAST | 2,485,120 | 8.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 169,829,558 | 30.8% |
| POP_JUMP_IF_FALSE | 133,107,263 | 24.2% |
| STORE_FAST | 73,322,666 | 13.3% |
| LOAD_FAST | 40,661,500 | 7.4% |
| POP_JUMP_IF_NOT_NONE | 36,988,940 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,090,665 | 69.4% |
| LOAD_DEREF | 92,064,060 | 16.7% |
| CALL_ISINSTANCE | 36,160,020 | 6.6% |
| CALL_BUILTIN_CLASS | 7,134,500 | 1.3% |
| LOAD_FAST_LOAD_FAST | 6,518,000 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 272,153,948 | 44.3% |
| STORE_FAST | 58,687,300 | 9.6% |
| RESUME_CHECK | 53,311,720 | 8.7% |
| POP_JUMP_IF_FALSE | 47,455,960 | 7.7% |
| LOAD_GLOBAL_MODULE | 33,752,980 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 234,472,052 | 38.2% |
| LOAD_FAST | 116,801,009 | 19.0% |
| LOAD_FAST_LOAD_FAST | 46,249,480 | 7.5% |
| IS_OP | 41,593,140 | 6.8% |
| LOAD_GLOBAL_MODULE | 33,752,980 | 5.5% |


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
| LOAD_FAST | 86,016,580 | 100.0% |
| LOAD_SUPER_ATTR | 2,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,619,920 | 83.3% |
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
| CALL_PY_EXACT_ARGS | 378,525,056 | 54.6% |
| COPY_FREE_VARS | 93,014,160 | 13.4% |
| CACHE | 69,740,888 | 10.1% |
| CALL_KW | 43,426,700 | 6.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 27,261,800 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 302,604,830 | 43.7% |
| LOAD_GLOBAL_BUILTIN | 169,829,558 | 24.5% |
| RETURN_CONST | 67,669,080 | 9.8% |
| LOAD_FAST_LOAD_FAST | 60,538,700 | 8.7% |
| LOAD_GLOBAL_MODULE | 53,311,720 | 7.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 363,272 | 79.1% |
| LOAD_CONST | 95,920 | 20.9% |
| SEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 363,272 | 79.1% |
| POP_TOP | 95,940 | 20.9% |
| RESUME | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 44,207,520 | 56.7% |
| LOAD_FAST | 32,504,500 | 41.7% |
| SWAP | 794,320 | 1.0% |
| BINARY_SUBSCR | 449,520 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 32,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,617,660 | 46.9% |
| RETURN_CONST | 13,692,200 | 17.6% |
| LOAD_FAST | 13,002,020 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 5,133,860 | 6.6% |
| LOAD_GLOBAL_MODULE | 3,667,940 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 358,936,493 | 58.7% |
| LOAD_FAST_LOAD_FAST | 248,651,140 | 40.7% |
| STORE_ATTR_SLOT | 2,484,217 | 0.4% |
| LOAD_ATTR_SLOT | 847,760 | 0.1% |
| ENTER_EXECUTOR | 83,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 170,370,120 | 27.9% |
| LOAD_FAST_LOAD_FAST | 141,091,380 | 23.1% |
| RETURN_CONST | 120,940,980 | 19.8% |
| LOAD_FAST | 111,618,993 | 18.3% |
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
| LOAD_FAST | 3,702,325 | 73.8% |
| LOAD_FAST_LOAD_FAST | 439,000 | 8.7% |
| LOAD_ATTR_SLOT | 410,400 | 8.2% |
| SWAP | 367,960 | 7.3% |
| LOAD_ATTR_INSTANCE_VALUE | 47,240 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,497,460 | 49.8% |
| LOAD_FAST | 973,085 | 19.4% |
| JUMP_BACKWARD | 853,560 | 17.0% |
| ENTER_EXECUTOR | 466,480 | 9.3% |
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
| ENTER_EXECUTOR | 430,140 | 99.3% |
| EXTENDED_ARG | 1,380 | 0.3% |
| LOAD_FAST | 840 | 0.2% |
| JUMP_BACKWARD | 320 | 0.1% |
| RETURN_CONST | 320 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,146,851 | 75.8% |
| LOAD_ATTR_SLOT | 5,611,640 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 553,760 | 1.9% |
| COPY | 234,540 | 0.8% |
| LOAD_ATTR | 225,500 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,229,551 | 86.3% |
| POP_JUMP_IF_TRUE | 2,924,160 | 10.0% |
| EXTENDED_ARG | 992,840 | 3.4% |
| TO_BOOL_NONE | 36,527 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 33,682 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 272,012,714 | 65.5% |
| COPY | 38,524,084 | 9.3% |
| LOAD_FAST | 34,233,680 | 8.2% |
| RETURN_VALUE | 25,446,700 | 6.1% |
| LOAD_ATTR_SLOT | 11,730,820 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 280,999,030 | 67.6% |
| POP_JUMP_IF_TRUE | 101,257,428 | 24.4% |
| UNARY_NOT | 22,824,820 | 5.5% |
| EXTENDED_ARG | 10,433,280 | 2.5% |
| TO_BOOL_STR | 640 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,185,016 | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE | 356,080 | 18.8% |
| RETURN_VALUE | 148,400 | 7.8% |
| LOAD_ATTR_SLOT | 138,880 | 7.3% |
| BINARY_OP | 53,900 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,352,656 | 71.4% |
| POP_JUMP_IF_TRUE | 400,660 | 21.2% |
| UNARY_NOT | 139,280 | 7.4% |
| TO_BOOL_STR | 1,280 | 0.1% |
| TO_BOOL_BOOL | 320 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,698,760 | 75.9% |
| LOAD_ATTR_SLOT | 6,507,680 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,594,720 | 5.7% |
| COPY | 888,220 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 393,200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 34,765,420 | 76.0% |
| POP_JUMP_IF_FALSE | 7,629,740 | 16.7% |
| UNARY_NOT | 2,525,220 | 5.5% |
| EXTENDED_ARG | 790,880 | 1.7% |
| TO_BOOL | 4,300 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,342,129 | 63.4% |
| LOAD_ATTR_SLOT | 7,746,200 | 24.2% |
| COPY | 1,795,240 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 582,760 | 1.8% |
| LOAD_ATTR_MODULE | 518,960 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,003,729 | 71.7% |
| POP_JUMP_IF_TRUE | 8,234,180 | 25.7% |
| EXTENDED_ARG | 776,420 | 2.4% |
| TO_BOOL_ALWAYS_TRUE | 36,851 | 0.1% |
| UNARY_NOT | 7,920 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,661,720 | 71.9% |
| COPY | 1,506,780 | 16.3% |
| LOAD_ATTR_SLOT | 436,820 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 349,280 | 3.8% |
| STORE_FAST_LOAD_FAST | 187,940 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,434,480 | 58.7% |
| POP_JUMP_IF_TRUE | 3,454,200 | 37.3% |
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
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 192,800 | 1.3% |
| LOAD_FAST | 15,920 | 0.1% |
| BINARY_SLICE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,619,180 | 100.0% |
| STORE_FAST | 5,740 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 777,560 | 38.4% |
| YIELD_VALUE | 376,200 | 18.6% |
| STORE_FAST | 373,640 | 18.4% |
| FOR_ITER | 242,800 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 93,080 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,884,820 | 93.0% |
| STORE_FAST | 141,020 | 7.0% |
| STORE_DEREF | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 13,824,400 | 82.3% |
| RETURN_VALUE | 1,471,900 | 8.8% |
| FOR_ITER_LIST | 503,360 | 3.0% |
| STORE_FAST | 371,320 | 2.2% |
| RETURN_CONST | 290,360 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 15,631,760 | 93.0% |
| STORE_FAST | 1,143,560 | 6.8% |
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
|     deferred | 4,868,600 | 20.1% |
|          hit | 19,196,063 | 79.3% |
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
|     deferred | 40,816,540 | 22.2% |
|          hit | 142,952,247 | 77.8% |
|         miss | 1,580 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,320 | 30.3% |
| Failure | 28,400 | 69.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 16,640 | 58.6% |
| other | 7,140 | 25.1% |
| code complex parameters | 4,280 | 15.1% |
| buffer int | 260 | 0.9% |
| tuple slice | 80 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 67,187,634 | 6.0% |
|          hit | 994,637,529 | 88.5% |
|         miss | 60,185,115 | 5.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,247,286 | 91.7% |
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
|     deferred | 42,980,707 | 33.4% |
|          hit | 84,594,640 | 65.8% |
|         miss | 884,724 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 29,656 | 26.3% |
| Failure | 82,977 | 73.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 47,981 | 57.8% |
| baseobject | 13,820 | 16.7% |
| other | 6,100 | 7.4% |
| different types | 5,760 | 6.9% |
| bool | 3,456 | 4.2% |
| tuple | 3,020 | 3.6% |
| list | 2,240 | 2.7% |
| set | 320 | 0.4% |
| string | 280 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 37,805,658 | 26.1% |
|          hit | 103,474,525 | 71.4% |
|         miss | 3,510,888 | 2.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 78,519 | 65.5% |
| Failure | 41,353 | 34.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 9,900 | 23.9% |
| set | 9,373 | 22.7% |
| zip | 7,220 | 17.5% |
| dict items | 5,860 | 14.2% |
| reversed list | 4,680 | 11.3% |
| dict keys | 2,220 | 5.4% |
| dict values | 1,140 | 2.8% |
| itertools | 480 | 1.2% |
| map | 260 | 0.6% |
| other | 220 | 0.5% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 116,402,550 | 9.3% |
|        deopt | 1,580 | 0.0% |
|          hit | 1,040,882,395 | 83.4% |
|         miss | 88,220,451 | 7.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,817,954 | 89.6% |
| Failure | 211,360 | 10.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 103,340 | 48.9% |
| not managed dict | 37,360 | 17.7% |
| shadowed | 28,080 | 13.3% |
| metaclass attribute | 9,240 | 4.4% |
| class method obj | 9,160 | 4.3% |
| non overriding descriptor | 8,060 | 3.8% |
| method | 5,760 | 2.7% |
| class attr simple | 4,120 | 1.9% |
| module attr not found | 3,000 | 1.4% |
| non object slot | 2,540 | 1.2% |
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
|          hit | 1,165,208,850 | 100.0% |
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
|          hit | 87,102,140 | 100.0% |

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
|          hit | 459,252 | 100.0% |

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
|     deferred | 9,881,623 | 1.4% |
|          hit | 557,211,845 | 79.2% |
|         miss | 133,462,125 | 19.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,540,297 | 99.0% |
| Failure | 26,780 | 1.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 17,280 | 64.5% |
| not in dict | 7,200 | 26.9% |
| not in keys | 800 | 3.0% |
| non object slot | 780 | 2.9% |
| overridden | 720 | 2.7% |


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
|     deferred | 3,768,080 | 40.9% |
|          hit | 5,450,185 | 59.1% |

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
|     deferred | 20,150,400 | 3.6% |
|          hit | 526,403,969 | 95.0% |
|         miss | 7,277,385 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 196,440 | 78.0% |
| Failure | 55,420 | 22.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 25,260 | 45.6% |
| tuple | 17,780 | 32.1% |
| dict | 5,820 | 10.5% |
| other | 2,440 | 4.4% |
| set | 2,160 | 3.9% |
| mapping | 1,960 | 3.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 131,813 | 0.4% |
|          hit | 33,456,180 | 99.6% |

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
| Basic | 7,156,636,390 | 50.5% |
| Not specialized | 1,302,115,222 | 9.2% |
| Specialized hits | 5,427,015,240 | 38.3% |
| Specialized misses | 293,676,348 | 2.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 116,402,550 | 33.8% |
| CALL | 67,187,634 | 19.5% |
| COMPARE_OP | 42,980,707 | 12.5% |
| BINARY_SUBSCR | 40,816,540 | 11.9% |
| FOR_ITER | 37,805,658 | 11.0% |
| TO_BOOL | 20,150,400 | 5.9% |
| STORE_ATTR | 9,881,623 | 2.9% |
| BINARY_OP | 4,868,600 | 1.4% |
| STORE_SUBSCR | 3,768,080 | 1.1% |
| UNPACK_SEQUENCE | 131,813 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 131,682,445 | 44.8% |
| LOAD_ATTR_METHOD_NO_DICT | 57,155,649 | 19.5% |
| CALL_PY_EXACT_ARGS | 44,521,315 | 15.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,588,989 | 5.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,038,080 | 2.7% |
| LOAD_ATTR_SLOT | 8,016,576 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,638,060 | 1.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,525,760 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 3,825,260 | 1.3% |
| TO_BOOL_NONE | 2,650,705 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120,967,748 | 17.3% |
| Calls to Python functions inlined | 577,846,932 | 82.7% |
| Calls via PyEval_EvalFrame (total) | 120,967,748 | 17.3% |
| Calls via PyEval_EvalFrame (vector) | 106,569,988 | 15.3% |
| Calls via PyEval_EvalFrame (generator) | 14,397,760 | 2.1% |
| Calls via PyEval_EvalFrame (legacy) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 106,569,848 | 15.3% |
| Calls via PyEval_EvalFrame (build class) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,901,212 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 2,475,100 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 23,660,996 | 3.4% |
| Calls via PyEval_EvalFrame (method) | 100 | 0.0% |
| Frame objects created | 4,745,560 | 0.7% |
| Frames pushed | 487,186,135 | 69.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 307,065,727 | 28.5% |
| Frees to freelist | 307,135,741 |  |
| Allocations | 769,267,920 | 71.5% |
| Allocations to 512 bytes | 768,219,259 | 71.4% |
| Allocations to 4 kbytes | 730,561 | 0.1% |
| Allocations over 4 kbytes | 318,100 | 0.0% |
| Frees | 794,813,485 |  |
| New values | 8,867,540 |  |
| Interpreter increfs | 7,397,790,635 | 75.0% |
| Interpreter decrefs | 8,038,511,855 | 74.7% |
| Increfs | 2,459,490,846 | 25.0% |
| Decrefs | 2,722,623,474 | 25.3% |
| Materialize dict (on request) | 660 | 0.0% |
| Materialize dict (new key) | 2,300 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 400 | 0.0% |
| Method cache hits | 421,067,001 |  |
| Method cache misses | 10,357,039 |  |
| Method cache collisions | 13,128,453 |  |
| Method cache dunder hits | 355,009,783 |  |
| Method cache dunder misses | 3,022,339 |  |


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
| Optimization attempts | 1,216,065 |  |
| Traces created | 12,180 | 1.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 40 | 0.0% |
| Trace too long | 991 | 0.1% |
| Trace too short | 1,203,885 | 99.0% |
| Inner loop found | 100 | 0.0% |
| Recursive call | 300 | 0.0% |
| Traces executed | 102,069,475 |  |
| Uops executed | 1,834,263,831 | 17.97 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.2% |
| <= 16 | 820 | 6.7% |
| <= 32 | 5,465 | 44.9% |
| <= 64 | 3,403 | 27.9% |
| <= 128 | 2,472 | 20.3% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 20 | 0.2% |
| <= 8 | 0 | 0.0% |
| <= 16 | 1,560 | 12.8% |
| <= 32 | 5,945 | 48.8% |
| <= 64 | 2,748 | 22.6% |
| <= 128 | 1,907 | 15.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 2,263,031 | 2.2% |
| <= 4 | 847,040 | 0.8% |
| <= 8 | 51,713,426 | 50.7% |
| <= 16 | 23,269,513 | 22.8% |
| <= 32 | 8,124,113 | 8.0% |
| <= 64 | 13,419,106 | 13.1% |
| <= 128 | 2,109,893 | 2.1% |
| <= 256 | 96,385 | 0.1% |
| <= 512 | 143,799 | 0.1% |
| <= 1,024 | 44,129 | 0.0% |
| <= 2,048 | 8,320 | 0.0% |
| <= 4,096 | 14,720 | 0.0% |
| <= 8,192 | 15,680 | 0.0% |
| <= 16,384 | 320 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 470,587,554 | 25.7% | 25.7% |  |
| LOAD_FAST | 160,312,738 | 8.7% | 34.4% |  |
| _POP_JUMP_IF_TRUE | 144,063,225 | 7.9% | 42.2% |  |
| _ITER_CHECK_LIST | 96,392,152 | 5.3% | 47.5% | 0.6% |
| _IS_ITER_EXHAUSTED_LIST | 95,787,869 | 5.2% | 52.7% |  |
| _EXIT_TRACE | 84,104,990 | 4.6% | 57.3% |  |
| STORE_FAST | 73,386,698 | 4.0% | 61.3% |  |
| POP_TOP | 59,104,085 | 3.2% | 64.5% |  |
| _GUARD_TYPE_VERSION | 57,246,689 | 3.1% | 67.7% | 18.9% |
| _GUARD_GLOBALS_VERSION | 52,560,809 | 2.9% | 70.5% | 1.1% |
| _ITER_NEXT_LIST | 48,049,366 | 2.6% | 73.1% |  |
| LOAD_CONST | 35,057,667 | 1.9% | 75.1% |  |
| _LOAD_GLOBAL_MODULE | 27,611,415 | 1.5% | 76.6% |  |
| _GUARD_BUILTINS_VERSION | 24,347,594 | 1.3% | 77.9% |  |
| _LOAD_GLOBAL_BUILTINS | 24,347,594 | 1.3% | 79.2% |  |
| _POP_JUMP_IF_FALSE | 22,089,551 | 1.2% | 80.4% |  |
| _LOAD_ATTR_SLOT | 19,194,445 | 1.0% | 81.5% |  |
| _JUMP_TO_TOP | 17,971,785 | 1.0% | 82.4% |  |
| TO_BOOL_BOOL | 14,299,574 | 0.8% | 83.2% |  |
| CALL_ISINSTANCE | 13,799,754 | 0.8% | 84.0% |  |
| _ITER_CHECK_TUPLE | 13,754,168 | 0.7% | 84.7% | 12.1% |
| _CHECK_FUNCTION_EXACT_ARGS | 13,308,384 | 0.7% | 85.4% | 13.6% |
| _CHECK_PEP_523 | 13,308,384 | 0.7% | 86.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 13,202,618 | 0.7% | 86.9% |  |
| BINARY_SUBSCR_LIST_INT | 12,921,920 | 0.7% | 87.6% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 12,086,000 | 0.7% | 88.3% |  |
| _IS_NONE | 12,050,980 | 0.7% | 88.9% |  |
| _CHECK_STACK_SPACE | 11,492,224 | 0.6% | 89.5% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 11,490,624 | 0.6% | 90.2% |  |
| _PUSH_FRAME | 11,490,624 | 0.6% | 90.8% |  |
| _SAVE_RETURN_OFFSET | 11,490,624 | 0.6% | 91.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,322,912 | 0.6% | 92.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,322,912 | 0.6% | 92.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 9,623,760 | 0.5% | 93.2% |  |
| RESUME_CHECK | 9,291,884 | 0.5% | 93.7% |  |
| COMPARE_OP_STR | 8,867,260 | 0.5% | 94.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 7,410,030 | 0.4% | 94.6% | 25.5% |
| CONTAINS_OP | 6,886,424 | 0.4% | 95.0% |  |
| _ITER_CHECK_RANGE | 6,039,560 | 0.3% | 95.3% |  |
| _IS_ITER_EXHAUSTED_RANGE | 6,039,560 | 0.3% | 95.6% |  |
| _ITER_NEXT_TUPLE | 4,672,752 | 0.3% | 95.9% |  |
| PUSH_NULL | 4,313,515 | 0.2% | 96.1% |  |
| COMPARE_OP_INT | 4,002,325 | 0.2% | 96.3% |  |
| LIST_APPEND | 3,846,176 | 0.2% | 96.5% |  |
| _GUARD_BOTH_INT | 3,608,917 | 0.2% | 96.7% |  |
| TO_BOOL_NONE | 3,551,080 | 0.2% | 96.9% | 4.8% |
| _ITER_NEXT_RANGE | 3,490,102 | 0.2% | 97.1% |  |
| _BINARY_OP_SUBTRACT_INT | 3,211,195 | 0.2% | 97.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,952,500 | 0.2% | 97.4% |  |
| _CHECK_ATTR_MODULE | 2,816,434 | 0.2% | 97.6% |  |
| _LOAD_ATTR_MODULE | 2,816,434 | 0.2% | 97.8% |  |
| BINARY_SUBSCR_DICT | 2,726,093 | 0.1% | 97.9% |  |
| _GUARD_BOTH_UNICODE | 2,723,400 | 0.1% | 98.0% |  |
| _BINARY_OP_ADD_UNICODE | 2,723,400 | 0.1% | 98.2% |  |
| SET_ADD | 2,683,640 | 0.1% | 98.3% |  |
| LOAD_DEREF | 2,413,894 | 0.1% | 98.5% |  |
| TO_BOOL_STR | 2,277,320 | 0.1% | 98.6% |  |
| CALL_STR_1 | 2,266,480 | 0.1% | 98.7% |  |
| CALL_BUILTIN_O | 2,261,680 | 0.1% | 98.8% |  |
| _GUARD_KEYS_VERSION | 2,186,000 | 0.1% | 99.0% | 10.2% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,186,000 | 0.1% | 99.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,891,020 | 0.1% | 99.2% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 1,675,260 | 0.1% | 99.3% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 1,675,260 | 0.1% | 99.4% |  |
| CALL_BUILTIN_FAST | 1,382,115 | 0.1% | 99.4% |  |
| _POP_FRAME | 1,269,792 | 0.1% | 99.5% |  |
| BUILD_LIST | 1,188,471 | 0.1% | 99.6% |  |
| GET_ITER | 817,060 | 0.0% | 99.6% |  |
| TO_BOOL_LIST | 718,980 | 0.0% | 99.7% |  |
| CALL_LEN | 604,220 | 0.0% | 99.7% |  |
| CALL_TYPE_1 | 481,280 | 0.0% | 99.7% |  |
| _STORE_ATTR_SLOT | 450,760 | 0.0% | 99.7% |  |
| FORMAT_SIMPLE | 445,720 | 0.0% | 99.8% |  |
| BUILD_STRING | 445,520 | 0.0% | 99.8% |  |
| _BINARY_OP_ADD_INT | 397,722 | 0.0% | 99.8% |  |
| IS_OP | 347,340 | 0.0% | 99.8% |  |
| UNARY_NOT | 332,840 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 272,104 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 270,200 | 0.0% | 99.9% |  |
| STORE_SUBSCR_DICT | 241,275 | 0.0% | 99.9% |  |
| SWAP | 217,520 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 177,740 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 141,624 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 140,740 | 0.0% | 99.9% | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 136,380 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 115,800 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 105,520 | 0.0% | 100.0% | 91.8% |
| COPY_FREE_VARS | 92,620 | 0.0% | 100.0% |  |
| COPY | 90,535 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 83,040 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 71,680 | 0.0% | 100.0% |  |
| BINARY_SLICE | 66,960 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 57,740 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 54,920 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 52,640 | 0.0% | 100.0% | 76.2% |
| MAKE_CELL | 42,680 | 0.0% | 100.0% |  |
| _CHECK_ATTR_WITH_HINT | 41,280 | 0.0% | 100.0% |  |
| _LOAD_ATTR_WITH_HINT | 41,280 | 0.0% | 100.0% |  |
| STORE_DEREF | 38,720 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 25,396 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 17,600 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 15,460 | 0.0% | 100.0% | 90.2% |
| _GUARD_DORV_VALUES | 13,520 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 13,520 | 0.0% | 100.0% |  |
| BUILD_MAP | 8,860 | 0.0% | 100.0% |  |
| MAP_ADD | 8,860 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 8,460 | 0.0% | 100.0% |  |
| BUILD_SET | 7,040 | 0.0% | 100.0% |  |
| _SPECIALIZE_UNPACK_SEQUENCE | 6,707 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 6,707 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 4,960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 2,000 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 1,520 | 0.0% | 100.0% |  |
| UNARY_INVERT | 580 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 540 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 1,131,765 |
| FOR_ITER_GEN | 72,340 |
| LOAD_ATTR | 1,533 |
| CALL | 856 |
| YIELD_VALUE | 620 |
| CALL_LIST_APPEND | 600 |
| LOAD_ATTR_PROPERTY | 580 |
| CALL_KW | 520 |
| CALL_PY_WITH_DEFAULTS | 460 |
| COMPARE_OP | 260 |
| BINARY_SUBSCR | 240 |
| CALL_ALLOC_AND_ENTER_INIT | 140 |
| TO_BOOL | 100 |
| BINARY_OP | 80 |
| STORE_ATTR | 40 |
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
Stats gathered on: 2023-11-03
