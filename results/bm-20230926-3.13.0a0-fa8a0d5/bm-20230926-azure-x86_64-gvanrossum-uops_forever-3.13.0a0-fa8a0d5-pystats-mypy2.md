
# Pystats results

- benchmark: mypy2
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,199,471,833 | 20.7% | 20.7% |  |
| LOAD_CONST | 524,005,962 | 4.9% | 25.6% |  |
| RESUME_CHECK | 519,154,928 | 4.9% | 30.5% | 0.0% |
| LOAD_GLOBAL_MODULE | 458,690,987 | 4.3% | 34.8% |  |
| STORE_ATTR_SLOT | 457,507,094 | 4.3% | 39.1% | 21.6% |
| LOAD_FAST_LOAD_FAST | 425,596,880 | 4.0% | 43.1% |  |
| LOAD_GLOBAL_BUILTIN | 413,002,670 | 3.9% | 47.0% | 0.0% |
| POP_JUMP_IF_FALSE | 408,041,570 | 3.8% | 50.8% |  |
| STORE_FAST | 372,237,583 | 3.5% | 54.4% |  |
| LOAD_ATTR_SLOT | 370,612,453 | 3.5% | 57.8% | 1.6% |
| CALL_PY_EXACT_ARGS | 326,940,874 | 3.1% | 60.9% | 10.2% |
| TO_BOOL_BOOL | 310,521,102 | 2.9% | 63.8% | 0.0% |
| RETURN_VALUE | 297,578,728 | 2.8% | 66.6% |  |
| RETURN_CONST | 225,025,452 | 2.1% | 68.7% |  |
| CALL_ISINSTANCE | 207,680,688 | 2.0% | 70.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 197,587,732 | 1.9% | 72.6% | 21.7% |
| POP_JUMP_IF_TRUE | 166,614,806 | 1.6% | 74.1% |  |
| POP_TOP | 165,579,590 | 1.6% | 75.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 116,595,244 | 1.1% | 76.8% | 3.6% |
| LOAD_DEREF | 97,483,792 | 0.9% | 77.7% |  |
| GET_ITER | 90,872,752 | 0.9% | 78.6% |  |
| INTERPRETER_EXIT | 90,684,914 | 0.9% | 79.4% |  |
| BINARY_SUBSCR_DICT | 88,301,112 | 0.8% | 80.2% |  |
| LOAD_ATTR | 86,350,892 | 0.8% | 81.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 85,783,830 | 0.8% | 81.9% | 12.9% |
| ENTER_EXECUTOR | 78,236,092 | 0.7% | 82.6% |  |
| POP_JUMP_IF_NOT_NONE | 72,395,940 | 0.7% | 83.3% |  |
| CONTAINS_OP | 71,413,092 | 0.7% | 83.9% |  |
| COPY_FREE_VARS | 70,547,340 | 0.7% | 84.6% |  |
| SWAP | 65,708,200 | 0.6% | 85.2% |  |
| LOAD_SUPER_ATTR_METHOD | 64,576,560 | 0.6% | 85.8% |  |
| BUILD_LIST | 62,535,740 | 0.6% | 86.4% |  |
| POP_JUMP_IF_NONE | 59,788,480 | 0.6% | 87.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 58,499,260 | 0.6% | 87.5% | 2.2% |
| CALL_KW | 57,378,960 | 0.5% | 88.1% |  |
| FOR_ITER_LIST | 56,336,743 | 0.5% | 88.6% | 2.4% |
| CALL | 51,428,320 | 0.5% | 89.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 47,443,196 | 0.4% | 89.5% | 8.7% |
| IS_OP | 42,656,660 | 0.4% | 89.9% |  |
| NOP | 39,900,780 | 0.4% | 90.3% |  |
| COPY | 38,054,382 | 0.4% | 90.7% |  |
| JUMP_FORWARD | 35,429,928 | 0.3% | 91.0% |  |
| COMPARE_OP_STR | 34,878,883 | 0.3% | 91.3% | 0.3% |
| TO_BOOL_LIST | 34,271,020 | 0.3% | 91.7% | 0.7% |
| COMPARE_OP | 32,186,689 | 0.3% | 92.0% |  |
| BINARY_SUBSCR | 30,257,740 | 0.3% | 92.2% |  |
| CALL_BUILTIN_CLASS | 30,007,218 | 0.3% | 92.5% |  |
| COMPARE_OP_INT | 28,815,434 | 0.3% | 92.8% | 2.0% |
| FOR_ITER | 28,407,771 | 0.3% | 93.1% |  |
| PUSH_NULL | 27,671,232 | 0.3% | 93.3% |  |
| CALL_LEN | 26,676,500 | 0.3% | 93.6% |  |
| MAKE_CELL | 24,962,400 | 0.2% | 93.8% |  |
| EXTENDED_ARG | 24,924,880 | 0.2% | 94.0% |  |
| STORE_FAST_STORE_FAST | 24,771,920 | 0.2% | 94.3% |  |
| CALL_LIST_APPEND | 24,108,420 | 0.2% | 94.5% |  |
| TO_BOOL_NONE | 24,010,864 | 0.2% | 94.7% | 8.2% |
| BUILD_TUPLE | 23,998,371 | 0.2% | 95.0% |  |
| LOAD_ATTR_WITH_HINT | 23,253,420 | 0.2% | 95.2% | 2.1% |
| MAP_ADD | 23,121,120 | 0.2% | 95.4% |  |
| TO_BOOL_ALWAYS_TRUE | 21,890,636 | 0.2% | 95.6% | 13.2% |
| LOAD_ATTR_MODULE | 21,860,800 | 0.2% | 95.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 21,597,980 | 0.2% | 96.0% | 27.9% |
| LOAD_FAST_AND_CLEAR | 20,861,060 | 0.2% | 96.2% |  |
| LIST_APPEND | 20,831,760 | 0.2% | 96.4% |  |
| LOAD_ATTR_PROPERTY | 20,512,730 | 0.2% | 96.6% | 6.6% |
| UNARY_NOT | 19,620,480 | 0.2% | 96.8% |  |
| FOR_ITER_TUPLE | 17,383,418 | 0.2% | 96.9% | 7.5% |
| CALL_PY_WITH_DEFAULTS | 15,545,380 | 0.1% | 97.1% | 2.1% |
| JUMP_BACKWARD | 15,399,860 | 0.1% | 97.2% |  |
| CALL_TUPLE_1 | 15,250,744 | 0.1% | 97.4% |  |
| TO_BOOL | 15,220,640 | 0.1% | 97.5% |  |
| BINARY_SUBSCR_LIST_INT | 14,401,200 | 0.1% | 97.7% |  |
| CALL_BUILTIN_O | 13,550,713 | 0.1% | 97.8% | 7.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,598,680 | 0.1% | 97.9% |  |
| LOAD_ATTR_CLASS | 11,177,660 | 0.1% | 98.0% | 2.5% |
| UNPACK_SEQUENCE_LIST | 10,968,480 | 0.1% | 98.1% |  |
| CALL_BUILTIN_FAST | 10,531,632 | 0.1% | 98.2% |  |
| STORE_ATTR | 9,288,600 | 0.1% | 98.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 9,087,860 | 0.1% | 98.4% |  |
| DELETE_ATTR | 8,440,800 | 0.1% | 98.5% |  |
| YIELD_VALUE | 8,414,448 | 0.1% | 98.5% |  |
| CALL_TYPE_1 | 8,332,800 | 0.1% | 98.6% |  |
| BUILD_MAP | 8,320,560 | 0.1% | 98.7% |  |
| TO_BOOL_STR | 6,947,620 | 0.1% | 98.8% | 3.9% |
| STORE_FAST_LOAD_FAST | 6,520,200 | 0.1% | 98.8% |  |
| MAKE_FUNCTION | 6,225,920 | 0.1% | 98.9% |  |
| CALL_FUNCTION_EX | 5,974,200 | 0.1% | 98.9% |  |
| RETURN_GENERATOR | 5,838,480 | 0.1% | 99.0% |  |
| BINARY_OP_ADD_INT | 5,695,248 | 0.1% | 99.0% | 0.8% |
| FOR_ITER_RANGE | 5,145,820 | 0.0% | 99.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 5,001,220 | 0.0% | 99.1% | 0.1% |
| EXIT_INIT_CHECK | 4,994,400 | 0.0% | 99.2% |  |
| BINARY_OP_ADD_UNICODE | 4,993,920 | 0.0% | 99.2% |  |
| BINARY_SLICE | 4,702,560 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 3,930,240 | 0.0% | 99.3% |  |
| STORE_SUBSCR_DICT | 3,726,912 | 0.0% | 99.3% |  |
| BINARY_OP | 3,610,380 | 0.0% | 99.4% |  |
| STORE_DEREF | 3,540,240 | 0.0% | 99.4% |  |
| PUSH_EXC_INFO | 3,113,760 | 0.0% | 99.4% |  |
| POP_EXCEPT | 3,113,760 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 3,113,760 | 0.0% | 99.5% |  |
| DICT_MERGE | 2,898,000 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,851,260 | 0.0% | 99.6% |  |
| STORE_SUBSCR | 2,823,820 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 2,811,144 | 0.0% | 99.6% |  |
| CALL_STR_1 | 2,610,480 | 0.0% | 99.6% |  |
| RERAISE | 2,513,760 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,351,040 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,276,540 | 0.0% | 99.7% | 10.9% |
| CALL_INTRINSIC_1 | 2,250,780 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 2,116,800 | 0.0% | 99.7% |  |
| FORMAT_SIMPLE | 2,093,040 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_GETITEM | 2,091,360 | 0.0% | 99.8% | 0.0% |
| BEFORE_WITH | 2,006,700 | 0.0% | 99.8% |  |
| IMPORT_FROM | 1,819,920 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,502,940 | 0.0% | 99.8% |  |
| IMPORT_NAME | 1,487,040 | 0.0% | 99.8% |  |
| UNARY_NEGATIVE | 1,462,080 | 0.0% | 99.9% |  |
| BUILD_STRING | 1,411,440 | 0.0% | 99.9% |  |
| BUILD_SET | 1,409,040 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 1,405,920 | 0.0% | 99.9% | 4.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,242,240 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,233,120 | 0.0% | 99.9% | 3.2% |
| SET_ADD | 1,073,280 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 996,000 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 855,860 | 0.0% | 100.0% | 1.7% |
| LOAD_SUPER_ATTR_ATTR | 812,400 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 802,320 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 704,160 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 429,600 | 0.0% | 100.0% |  |
| SEND_GEN | 346,608 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 323,760 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 274,608 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 254,640 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 220,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 216,060 | 0.0% | 100.0% | 22.1% |
| DELETE_FAST | 151,440 | 0.0% | 100.0% |  |
| LIST_EXTEND | 112,860 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 94,920 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 72,000 | 0.0% | 100.0% |  |
| END_SEND | 72,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 56,640 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 50,880 | 0.0% | 100.0% |  |
| END_FOR | 40,560 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 24,720 | 0.0% | 100.0% |  |
| BUILD_SLICE | 13,440 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 4,560 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 3,360 | 0.0% | 100.0% |  |
| UNARY_INVERT | 960 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 960 | 0.0% | 100.0% |  |
| UNPACK_EX | 720 | 0.0% | 100.0% |  |
| STORE_SLICE | 720 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 720 | 0.0% | 100.0% |  |
| SET_UPDATE | 240 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 140 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 327,092,937 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 287,171,172 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 283,628,336 | 2.7% | 8.4% |
| LOAD_FAST STORE_ATTR_SLOT | 268,484,667 | 2.5% | 11.0% |
| RESUME_CHECK LOAD_FAST | 227,289,986 | 2.1% | 13.1% |
| LOAD_CONST LOAD_FAST | 211,214,700 | 2.0% | 15.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 209,818,980 | 2.0% | 17.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 203,826,739 | 1.9% | 19.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 203,001,752 | 1.9% | 20.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 190,665,185 | 1.8% | 22.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 186,557,760 | 1.8% | 24.4% |
| STORE_FAST LOAD_FAST | 183,039,704 | 1.7% | 26.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 175,506,048 | 1.7% | 27.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 142,710,244 | 1.3% | 29.2% |
| STORE_ATTR_SLOT LOAD_CONST | 126,971,520 | 1.2% | 30.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 126,535,534 | 1.2% | 31.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 122,167,160 | 1.1% | 32.7% |
| LOAD_FAST LOAD_CONST | 118,414,132 | 1.1% | 33.8% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 105,820,320 | 1.0% | 34.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 99,779,027 | 0.9% | 35.7% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 93,929,664 | 0.9% | 36.6% |
| STORE_ATTR_SLOT RETURN_CONST | 90,707,040 | 0.9% | 37.5% |
| LOAD_FAST RETURN_VALUE | 89,198,160 | 0.8% | 38.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 87,803,300 | 0.8% | 39.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 87,482,360 | 0.8% | 40.0% |
| STORE_ATTR_SLOT LOAD_FAST | 83,669,307 | 0.8% | 40.8% |
| RETURN_CONST POP_TOP | 79,308,000 | 0.7% | 41.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 77,145,700 | 0.7% | 42.2% |
| LOAD_CONST BINARY_SUBSCR_DICT | 75,875,040 | 0.7% | 42.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 75,757,002 | 0.7% | 43.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 73,361,800 | 0.7% | 44.3% |
| POP_TOP LOAD_FAST | 70,317,446 | 0.7% | 45.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 70,101,660 | 0.7% | 45.7% |
| COPY_FREE_VARS RESUME_CHECK | 69,822,300 | 0.7% | 46.3% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 69,111,360 | 0.7% | 47.0% |
| RETURN_VALUE STORE_FAST | 67,596,800 | 0.6% | 47.6% |
| LOAD_DEREF LOAD_FAST | 66,309,752 | 0.6% | 48.2% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 64,576,560 | 0.6% | 48.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 63,515,920 | 0.6% | 49.4% |
| RETURN_VALUE RETURN_VALUE | 60,510,866 | 0.6% | 50.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 60,079,300 | 0.6% | 50.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 59,823,280 | 0.6% | 51.1% |
| LOAD_FAST LOAD_FAST | 57,900,996 | 0.5% | 51.7% |
| LOAD_FAST LOAD_ATTR | 56,680,772 | 0.5% | 52.2% |
| LOAD_CONST CALL_KW | 56,361,840 | 0.5% | 52.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 55,898,544 | 0.5% | 53.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 54,888,571 | 0.5% | 53.8% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 53,775,840 | 0.5% | 54.3% |
| CACHE RESUME_CHECK | 52,310,354 | 0.5% | 54.8% |
| RESUME_CHECK RETURN_CONST | 50,785,440 | 0.5% | 55.3% |
| RETURN_CONST INTERPRETER_EXIT | 46,489,260 | 0.4% | 55.7% |
| RETURN_CONST LOAD_FAST | 46,216,320 | 0.4% | 56.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 45,401,580 | 0.4% | 56.6% |
| LOAD_ATTR_SLOT LOAD_FAST | 44,373,086 | 0.4% | 57.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 43,854,460 | 0.4% | 57.4% |
| LOAD_CONST LOAD_CONST | 40,419,480 | 0.4% | 57.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 39,967,800 | 0.4% | 58.1% |
| LOAD_ATTR LOAD_FAST | 39,947,626 | 0.4% | 58.5% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 38,899,440 | 0.4% | 58.9% |
| RETURN_VALUE LOAD_FAST | 37,582,460 | 0.4% | 59.2% |
| FOR_ITER_LIST STORE_FAST | 37,153,158 | 0.3% | 59.6% |
| RETURN_VALUE INTERPRETER_EXIT | 36,941,174 | 0.3% | 59.9% |
| LOAD_ATTR_SLOT GET_ITER | 35,915,712 | 0.3% | 60.3% |
| LOAD_FAST CONTAINS_OP | 35,661,120 | 0.3% | 60.6% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 35,588,160 | 0.3% | 60.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 34,761,640 | 0.3% | 61.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 34,708,160 | 0.3% | 61.6% |
| LOAD_ATTR_SLOT STORE_FAST | 34,148,640 | 0.3% | 61.9% |
| GET_ITER FOR_ITER_LIST | 33,770,960 | 0.3% | 62.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,158,220 | 0.3% | 62.5% |
| CACHE COPY_FREE_VARS | 32,616,960 | 0.3% | 62.9% |
| CALL_KW RESUME_CHECK | 32,570,160 | 0.3% | 63.2% |
| RETURN_CONST RETURN_VALUE | 32,131,200 | 0.3% | 63.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 31,524,480 | 0.3% | 63.8% |
| LOAD_GLOBAL_MODULE IS_OP | 31,202,400 | 0.3% | 64.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 29,736,720 | 0.3% | 64.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 29,672,600 | 0.3% | 64.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 29,302,240 | 0.3% | 64.9% |
| COPY TO_BOOL_BOOL | 28,864,830 | 0.3% | 65.2% |
| IS_OP POP_JUMP_IF_FALSE | 28,561,440 | 0.3% | 65.4% |
| POP_JUMP_IF_NONE LOAD_FAST | 28,381,440 | 0.3% | 65.7% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 27,674,080 | 0.3% | 66.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 27,463,920 | 0.3% | 66.2% |
| LOAD_ATTR_SLOT RETURN_VALUE | 27,350,228 | 0.3% | 66.5% |
| POP_TOP LOAD_FAST_LOAD_FAST | 26,461,260 | 0.2% | 66.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 26,363,760 | 0.2% | 67.0% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 26,056,960 | 0.2% | 67.2% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 26,030,636 | 0.2% | 67.5% |
| LOAD_FAST TO_BOOL_LIST | 26,007,240 | 0.2% | 67.7% |
| RETURN_VALUE POP_TOP | 25,899,120 | 0.2% | 67.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 25,711,680 | 0.2% | 68.2% |
| LOAD_FAST TO_BOOL_BOOL | 25,679,280 | 0.2% | 68.4% |
| LOAD_CONST COMPARE_OP_STR | 25,550,392 | 0.2% | 68.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 24,579,120 | 0.2% | 68.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 24,383,580 | 0.2% | 69.1% |
| BUILD_LIST STORE_FAST | 24,266,220 | 0.2% | 69.4% |
| STORE_ATTR_SLOT LOAD_GLOBAL_BUILTIN | 23,764,560 | 0.2% | 69.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 22,921,500 | 0.2% | 69.8% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 22,863,600 | 0.2% | 70.0% |
| NOP LOAD_FAST | 22,468,880 | 0.2% | 70.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,651,120 | 77.6% |
| BINARY_OP_SUBTRACT_INT | 667,680 | 14.2% |
| LOAD_FAST | 282,960 | 6.0% |
| BINARY_OP_ADD_INT | 76,080 | 1.6% |
| LOAD_ATTR_SLOT | 18,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,754,640 | 37.3% |
| CALL_PY_EXACT_ARGS | 668,160 | 14.2% |
| STORE_FAST | 525,120 | 11.2% |
| GET_ITER | 485,040 | 10.3% |
| BINARY_OP_ADD_UNICODE | 338,160 | 7.2% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,310,354 | 56.4% |
| COPY_FREE_VARS | 32,616,960 | 35.1% |
| POP_TOP | 5,693,760 | 6.1% |
| CALL_INTRINSIC_1 | 2,106,000 | 2.3% |
| RETURN_GENERATOR | 70,080 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,945,920 | 97.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 36,060 | 1.8% |
| CALL | 24,720 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,785,600 | 89.0% |
| STORE_FAST | 221,100 | 11.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 246,720 | 57.4% |
| RETURN_VALUE | 147,840 | 34.4% |
| BUILD_STRING | 33,360 | 7.8% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.3% |
| LOAD_ATTR_MODULE | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 393,360 | 91.6% |
| LOAD_FAST | 34,560 | 8.0% |
| JUMP_FORWARD | 960 | 0.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,963,112 | 49.5% |
| LOAD_FAST_LOAD_FAST | 11,262,960 | 37.2% |
| LOAD_FAST | 2,610,720 | 8.6% |
| LOAD_GLOBAL_MODULE | 899,520 | 3.0% |
| COPY | 215,520 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,866,400 | 42.5% |
| CONTAINS_OP | 3,348,480 | 11.1% |
| LOAD_CONST | 3,315,600 | 11.0% |
| LOAD_FAST | 2,398,560 | 7.9% |
| RETURN_VALUE | 2,122,080 | 7.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,100,560 | 99.6% |
| BUILD_TUPLE | 12,480 | 0.4% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,113,760 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,160 | 56.8% |
| BUILD_SLICE | 12,960 | 22.9% |
| LOAD_FAST | 9,360 | 16.5% |
| LOAD_FAST_LOAD_FAST | 2,160 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 33,600 | 59.3% |
| LOAD_DEREF | 12,960 | 22.9% |
| JUMP_BACKWARD | 7,920 | 14.0% |
| RETURN_CONST | 1,440 | 2.5% |
| LOAD_FAST | 480 | 0.8% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 40,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 37,920 | 93.5% |
| LOAD_FAST | 2,160 | 5.3% |
| JUMP_BACKWARD | 240 | 0.6% |
| EXTENDED_ARG | 240 | 0.6% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 72,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 72,000 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,994,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,994,400 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,474,320 | 70.4% |
| RETURN_VALUE | 310,080 | 14.8% |
| BINARY_SUBSCR_TUPLE_INT | 211,200 | 10.1% |
| CONVERT_VALUE | 50,880 | 2.4% |
| LOAD_ATTR_SLOT | 29,040 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,348,800 | 64.4% |
| BUILD_STRING | 744,240 | 35.6% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 66.7% |
| LOAD_CONST | 240 | 33.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 35,915,712 | 39.5% |
| LOAD_FAST | 21,664,660 | 23.8% |
| CALL_BUILTIN_CLASS | 14,265,420 | 15.7% |
| BINARY_SUBSCR_DICT | 9,363,600 | 10.3% |
| CALL | 1,986,240 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 33,770,960 | 37.2% |
| LOAD_FAST_AND_CLEAR | 19,925,780 | 21.9% |
| FOR_ITER_TUPLE | 14,372,212 | 15.8% |
| FOR_ITER | 10,927,980 | 12.0% |
| FOR_ITER_RANGE | 4,464,540 | 4.9% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 72,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,000 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 46,489,260 | 51.3% |
| RETURN_VALUE | 36,941,174 | 40.7% |
| YIELD_VALUE | 7,184,400 | 7.9% |
| RETURN_GENERATOR | 70,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,225,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,118,160 | 50.1% |
| SET_FUNCTION_ATTRIBUTE | 3,051,600 | 49.0% |
| LOAD_CONST | 36,000 | 0.6% |
| LOAD_GLOBAL_MODULE | 10,800 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 5,520 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,347,280 | 28.4% |
| POP_JUMP_IF_TRUE | 10,561,920 | 26.5% |
| POP_JUMP_IF_FALSE | 6,874,800 | 17.2% |
| RESUME_CHECK | 4,832,400 | 12.1% |
| CALL_LIST_APPEND | 1,826,400 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,468,880 | 56.3% |
| LOAD_CONST | 11,083,200 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 3,558,880 | 8.9% |
| LOAD_GLOBAL_MODULE | 2,283,840 | 5.7% |
| LOAD_FAST_LOAD_FAST | 416,160 | 1.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,959,360 | 62.9% |
| SWAP | 950,880 | 30.5% |
| COPY | 192,480 | 6.2% |
| STORE_FAST | 10,320 | 0.3% |
| POP_JUMP_IF_FALSE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,958,640 | 62.9% |
| RETURN_VALUE | 950,880 | 30.5% |
| RERAISE | 192,480 | 6.2% |
| ENTER_EXECUTOR | 10,080 | 0.3% |
| JUMP_BACKWARD | 720 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 79,308,000 | 47.9% |
| RETURN_VALUE | 25,899,120 | 15.6% |
| POP_JUMP_IF_FALSE | 15,495,890 | 9.4% |
| POP_JUMP_IF_TRUE | 13,009,744 | 7.9% |
| RESUME_CHECK | 6,001,680 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,317,446 | 42.5% |
| LOAD_FAST_LOAD_FAST | 26,461,260 | 16.0% |
| ENTER_EXECUTOR | 19,388,984 | 11.7% |
| RETURN_CONST | 17,247,120 | 10.4% |
| LOAD_CONST | 6,626,880 | 4.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 1,715,040 | 55.1% |
| LOAD_ATTR_SLOT | 948,000 | 30.4% |
| RERAISE | 160,080 | 5.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 154,320 | 5.0% |
| RAISE_VARARGS | 94,320 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,113,040 | 100.0% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,122,912 | 47.4% |
| LOAD_ATTR | 6,303,620 | 22.8% |
| LOAD_ATTR_MODULE | 5,401,300 | 19.5% |
| BINARY_SUBSCR_DICT | 1,110,720 | 4.0% |
| LOAD_SUPER_ATTR_ATTR | 808,080 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,860,152 | 75.4% |
| LOAD_FAST_LOAD_FAST | 4,219,200 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 1,836,720 | 6.6% |
| CALL | 440,520 | 1.6% |
| LOAD_CONST | 209,760 | 0.8% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,167,360 | 54.2% |
| CALL_FUNCTION_EX | 1,711,440 | 29.3% |
| COPY_FREE_VARS | 725,040 | 12.4% |
| ENTER_EXECUTOR | 161,920 | 2.8% |
| CACHE | 70,080 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 3,563,280 | 61.0% |
| LOAD_FAST | 1,745,520 | 29.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 289,440 | 5.0% |
| GET_YIELD_FROM_ITER | 72,000 | 1.2% |
| INTERPRETER_EXIT | 70,080 | 1.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,198,160 | 30.0% |
| RETURN_VALUE | 60,510,866 | 20.3% |
| RETURN_CONST | 32,131,200 | 10.8% |
| LOAD_ATTR_SLOT | 27,350,228 | 9.2% |
| CALL | 9,479,520 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 67,596,800 | 22.7% |
| RETURN_VALUE | 60,510,866 | 20.3% |
| LOAD_FAST | 37,582,460 | 12.6% |
| INTERPRETER_EXIT | 36,941,174 | 12.4% |
| POP_TOP | 25,899,120 | 8.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,273,760 | 80.5% |
| LOAD_FAST | 258,480 | 9.2% |
| SWAP | 215,520 | 7.6% |
| LOAD_CONST | 59,280 | 2.1% |
| LOAD_ATTR_SLOT | 12,960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,273,760 | 80.5% |
| LOAD_CONST | 257,520 | 9.1% |
| LOAD_FAST | 180,000 | 6.4% |
| RETURN_CONST | 111,360 | 3.9% |
| STORE_SUBSCR | 940 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 7,044,460 | 46.3% |
| LOAD_FAST | 5,204,800 | 34.2% |
| LOAD_ATTR_SLOT | 2,020,920 | 13.3% |
| COPY | 809,460 | 5.3% |
| LOAD_ATTR_WITH_HINT | 53,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,781,280 | 84.0% |
| POP_JUMP_IF_TRUE | 2,157,540 | 14.2% |
| UNARY_NOT | 220,620 | 1.4% |
| EXTENDED_ARG | 28,080 | 0.2% |
| TO_BOOL | 24,720 | 0.2% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 960 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 756,480 | 51.7% |
| CALL_LEN | 667,920 | 45.7% |
| LOAD_GLOBAL_MODULE | 17,760 | 1.2% |
| CALL | 12,960 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 6,960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 667,680 | 45.7% |
| COMPARE_OP_INT | 667,680 | 45.7% |
| CALL_PY_EXACT_ARGS | 64,800 | 4.4% |
| RETURN_VALUE | 19,920 | 1.4% |
| BUILD_TUPLE | 17,760 | 1.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,118,960 | 87.3% |
| TO_BOOL_LIST | 1,893,840 | 9.7% |
| TO_BOOL_STR | 277,200 | 1.4% |
| TO_BOOL | 220,620 | 1.1% |
| TO_BOOL_INT | 104,160 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,266,240 | 52.3% |
| RETURN_VALUE | 6,898,080 | 35.2% |
| COPY | 1,927,440 | 9.8% |
| LOAD_FAST | 342,720 | 1.7% |
| STORE_FAST | 114,240 | 0.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,983,120 | 54.9% |
| LOAD_FAST | 360,960 | 10.0% |
| BUILD_LIST | 280,560 | 7.8% |
| STORE_FAST | 259,920 | 7.2% |
| LOAD_CONST | 179,040 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,424,880 | 39.5% |
| STORE_FAST | 911,760 | 25.3% |
| CALL_PY_EXACT_ARGS | 381,120 | 10.6% |
| LOAD_CONST | 215,520 | 6.0% |
| GET_ITER | 157,920 | 4.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 18,125,060 | 29.0% |
| STORE_FAST | 13,867,740 | 22.2% |
| LOAD_GLOBAL_MODULE | 8,346,960 | 13.3% |
| RESUME_CHECK | 6,507,840 | 10.4% |
| STORE_ATTR_SLOT | 3,159,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,266,220 | 38.8% |
| SWAP | 18,125,060 | 29.0% |
| CALL | 8,622,720 | 13.8% |
| LOAD_FAST | 6,068,160 | 9.7% |
| LOAD_GLOBAL_BUILTIN | 1,903,920 | 3.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,078,960 | 37.0% |
| LOAD_CONST | 1,249,680 | 15.0% |
| STORE_ATTR_INSTANCE_VALUE | 720,720 | 8.7% |
| RESUME_CHECK | 696,960 | 8.4% |
| POP_JUMP_IF_FALSE | 597,360 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,765,200 | 57.3% |
| LOAD_CONST | 1,208,640 | 14.5% |
| STORE_FAST | 1,130,160 | 13.6% |
| SWAP | 490,560 | 5.9% |
| RETURN_VALUE | 203,520 | 2.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,310,160 | 93.0% |
| LOAD_CONST | 82,320 | 5.8% |
| LOAD_FAST | 16,320 | 1.2% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,310,160 | 93.0% |
| STORE_FAST | 48,240 | 3.4% |
| CALL_PY_EXACT_ARGS | 34,080 | 2.4% |
| BINARY_OP | 8,400 | 0.6% |
| LOAD_CONST | 8,160 | 0.6% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 12,960 | 96.4% |
| BINARY_SUBSCR | 480 | 3.6% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 744,240 | 52.7% |
| LOAD_CONST | 667,200 | 47.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 384,480 | 27.2% |
| STORE_FAST | 358,080 | 25.4% |
| RETURN_VALUE | 282,480 | 20.0% |
| LOAD_FAST | 125,520 | 8.9% |
| CALL_PY_EXACT_ARGS | 64,080 | 4.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,336,160 | 34.7% |
| LOAD_GLOBAL_MODULE | 3,910,100 | 16.3% |
| LOAD_ATTR_SLOT | 3,832,347 | 16.0% |
| LOAD_FAST_LOAD_FAST | 3,263,580 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,775,280 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,233,820 | 26.0% |
| CALL_BUILTIN_O | 4,252,531 | 17.7% |
| CALL_ISINSTANCE | 3,398,160 | 14.2% |
| LOAD_CONST | 3,052,800 | 12.7% |
| LOAD_FAST | 2,666,880 | 11.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,551,600 | 18.6% |
| BUILD_LIST | 8,622,720 | 16.8% |
| LOAD_FAST_LOAD_FAST | 5,209,440 | 10.1% |
| RETURN_VALUE | 4,693,920 | 9.1% |
| ENTER_EXECUTOR | 4,356,660 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,395,440 | 39.7% |
| RETURN_VALUE | 9,479,520 | 18.4% |
| LIST_APPEND | 5,271,360 | 10.2% |
| RESUME_CHECK | 3,350,940 | 6.5% |
| TO_BOOL_BOOL | 2,759,520 | 5.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 2,898,000 | 48.5% |
| LOAD_FAST | 1,532,460 | 25.7% |
| MAP_ADD | 1,208,400 | 20.2% |
| LOAD_ATTR | 206,400 | 3.5% |
| CALL_INTRINSIC_1 | 108,540 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,025,200 | 50.6% |
| RETURN_GENERATOR | 1,711,440 | 28.6% |
| POP_TOP | 812,160 | 13.6% |
| STORE_FAST | 276,960 | 4.6% |
| RESUME_CHECK | 106,380 | 1.8% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,106,000 | 93.6% |
| LIST_EXTEND | 112,620 | 5.0% |
| RERAISE | 32,160 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 2,138,160 | 95.0% |
| CALL_FUNCTION_EX | 108,540 | 4.8% |
| BUILD_MAP | 4,080 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 56,361,840 | 98.2% |
| ENTER_EXECUTOR | 1,017,120 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 32,570,160 | 56.8% |
| UNPACK_SEQUENCE_LIST | 10,636,560 | 18.5% |
| RETURN_VALUE | 4,061,760 | 7.1% |
| MAKE_CELL | 3,653,040 | 6.4% |
| CALL_PY_EXACT_ARGS | 2,814,480 | 4.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,690,340 | 42.5% |
| LOAD_GLOBAL_MODULE | 6,483,840 | 20.1% |
| LOAD_CONST | 5,816,298 | 18.1% |
| LOAD_ATTR_MODULE | 2,470,320 | 7.7% |
| LOAD_FAST | 1,620,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 12,663,964 | 39.3% |
| POP_JUMP_IF_FALSE | 10,168,478 | 31.6% |
| RETURN_VALUE | 6,305,214 | 19.6% |
| POP_JUMP_IF_TRUE | 2,100,480 | 6.5% |
| EXTENDED_ARG | 771,840 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,661,120 | 49.9% |
| LOAD_FAST_LOAD_FAST | 13,658,240 | 19.1% |
| LOAD_ATTR_INSTANCE_VALUE | 5,939,040 | 8.3% |
| LOAD_ATTR_SLOT | 3,640,320 | 5.1% |
| BINARY_SUBSCR | 3,348,480 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60,079,300 | 84.1% |
| POP_JUMP_IF_TRUE | 8,563,472 | 12.0% |
| RETURN_VALUE | 2,139,120 | 3.0% |
| EXTENDED_ARG | 348,480 | 0.5% |
| COPY | 167,520 | 0.2% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,400 | 99.1% |
| RETURN_CONST | 480 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 50,880 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 12,663,964 | 33.3% |
| LOAD_FAST | 4,661,280 | 12.2% |
| CALL_ISINSTANCE | 3,167,040 | 8.3% |
| SWAP | 2,687,520 | 7.1% |
| COMPARE_OP_STR | 2,321,688 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 28,864,830 | 75.9% |
| COMPARE_OP_INT | 2,685,360 | 7.1% |
| TO_BOOL_NONE | 1,346,520 | 3.5% |
| TO_BOOL_STR | 1,130,020 | 3.0% |
| TO_BOOL | 809,460 | 2.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,588,160 | 50.4% |
| CACHE | 32,616,960 | 46.2% |
| CALL | 1,440,960 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 338,160 | 0.5% |
| CALL_KW | 318,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 69,822,300 | 99.0% |
| RETURN_GENERATOR | 725,040 | 1.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,440,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,603,120 | 78.2% |
| NOP | 1,711,440 | 20.3% |
| RETURN_CONST | 126,240 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 151,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 150,960 | 99.7% |
| ENTER_EXECUTOR | 300 | 0.2% |
| JUMP_BACKWARD | 180 | 0.1% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,898,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,898,000 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 20,770,800 | 26.5% |
| POP_JUMP_IF_TRUE | 19,950,236 | 25.5% |
| POP_TOP | 19,388,984 | 24.8% |
| CALL_LIST_APPEND | 6,655,860 | 8.5% |
| EXTENDED_ARG | 3,339,800 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,909,920 | 26.7% |
| RETURN_CONST | 9,404,572 | 12.0% |
| SWAP | 8,338,080 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 6,215,200 | 7.9% |
| CALL | 4,356,660 | 5.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,825,680 | 31.4% |
| GET_ITER | 3,557,040 | 14.3% |
| POP_TOP | 2,649,120 | 10.6% |
| JUMP_BACKWARD | 2,398,960 | 9.6% |
| LOAD_ATTR_SLOT | 941,520 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,209,200 | 45.0% |
| FOR_ITER | 4,750,080 | 19.1% |
| ENTER_EXECUTOR | 3,339,800 | 13.4% |
| POP_JUMP_IF_NONE | 1,817,280 | 7.3% |
| JUMP_BACKWARD | 1,604,920 | 6.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 12,057,600 | 42.4% |
| GET_ITER | 10,927,980 | 38.5% |
| EXTENDED_ARG | 4,750,080 | 16.7% |
| SWAP | 539,520 | 1.9% |
| LOAD_FAST | 60,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 10,369,440 | 36.5% |
| STORE_FAST | 4,445,874 | 15.7% |
| RETURN_CONST | 4,202,400 | 14.8% |
| LOAD_FAST | 3,526,359 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,356,240 | 4.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 1,369,440 | 75.2% |
| STORE_FAST | 450,480 | 24.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,819,920 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,487,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,369,440 | 92.1% |
| STORE_FAST | 117,360 | 7.9% |
| STORE_DEREF | 240 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 31,202,400 | 73.1% |
| LOAD_CONST | 5,394,980 | 12.6% |
| LOAD_FAST | 5,246,160 | 12.3% |
| LOAD_FAST_LOAD_FAST | 667,680 | 1.6% |
| LOAD_ATTR | 71,760 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 28,561,440 | 67.0% |
| POP_JUMP_IF_TRUE | 8,735,520 | 20.5% |
| RETURN_VALUE | 3,074,640 | 7.2% |
| LOAD_FAST | 1,228,080 | 2.9% |
| COPY | 618,240 | 1.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,291,104 | 21.4% |
| STORE_SUBSCR | 2,273,760 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,913,400 | 12.4% |
| EXTENDED_ARG | 1,604,920 | 10.4% |
| MAP_ADD | 1,354,800 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 12,057,600 | 78.3% |
| EXTENDED_ARG | 2,398,960 | 15.6% |
| FOR_ITER_GEN | 923,280 | 6.0% |
| FOR_ITER_LIST | 14,840 | 0.1% |
| ENTER_EXECUTOR | 1,640 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 274,608 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 274,608 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 10,513,680 | 29.7% |
| LOAD_ATTR_SLOT | 10,230,720 | 28.9% |
| LOAD_FAST | 4,954,080 | 14.0% |
| STORE_ATTR_SLOT | 4,130,400 | 11.7% |
| STORE_FAST | 2,845,680 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,630,568 | 49.8% |
| STORE_FAST | 10,936,080 | 30.9% |
| MAP_ADD | 4,706,640 | 13.3% |
| LOAD_CONST | 769,920 | 2.2% |
| LOAD_GLOBAL_MODULE | 719,040 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,355,840 | 54.5% |
| CALL | 5,271,360 | 25.3% |
| CALL_BUILTIN_O | 1,836,480 | 8.8% |
| LOAD_FAST | 1,271,280 | 6.1% |
| BINARY_SUBSCR_LIST_INT | 252,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 20,770,800 | 99.7% |
| JUMP_BACKWARD | 60,960 | 0.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,440 | 81.0% |
| RETURN_VALUE | 14,160 | 12.5% |
| BINARY_SLICE | 6,720 | 6.0% |
| STORE_FAST | 240 | 0.2% |
| LOAD_CONST | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 112,620 | 99.8% |
| LOAD_CONST | 240 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,680,772 | 65.6% |
| LOAD_GLOBAL_MODULE | 22,921,500 | 26.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,952,160 | 2.3% |
| LOAD_FAST_LOAD_FAST | 1,528,320 | 1.8% |
| CALL_TYPE_1 | 1,082,880 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,947,626 | 46.3% |
| LOAD_FAST_LOAD_FAST | 8,270,880 | 9.6% |
| TO_BOOL | 7,044,460 | 8.2% |
| PUSH_NULL | 6,303,620 | 7.3% |
| CALL_PY_EXACT_ARGS | 5,020,620 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 126,971,520 | 24.2% |
| LOAD_FAST | 118,414,132 | 22.6% |
| LOAD_CONST | 40,419,480 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20,943,860 | 4.0% |
| MAP_ADD | 20,542,800 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 211,214,700 | 40.3% |
| BINARY_SUBSCR_DICT | 75,875,040 | 14.5% |
| CALL_KW | 56,361,840 | 10.8% |
| LOAD_CONST | 40,419,480 | 7.7% |
| COMPARE_OP_STR | 25,550,392 | 4.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 69,111,360 | 70.9% |
| LOAD_DEREF | 9,703,680 | 10.0% |
| LOAD_FAST | 4,112,912 | 4.2% |
| LOAD_GLOBAL_MODULE | 3,757,520 | 3.9% |
| POP_JUMP_IF_FALSE | 1,954,188 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,309,752 | 68.0% |
| LOAD_DEREF | 9,703,680 | 10.0% |
| LOAD_ATTR_SLOT | 5,834,880 | 6.0% |
| LOAD_CONST | 3,229,752 | 3.3% |
| LOAD_FAST_LOAD_FAST | 2,728,560 | 2.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 287,171,172 | 13.1% |
| RESUME_CHECK | 227,289,986 | 10.3% |
| LOAD_CONST | 211,214,700 | 9.6% |
| POP_JUMP_IF_FALSE | 190,665,185 | 8.7% |
| STORE_FAST | 183,039,704 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 327,092,937 | 14.9% |
| STORE_ATTR_SLOT | 268,484,667 | 12.2% |
| LOAD_GLOBAL_MODULE | 203,826,739 | 9.3% |
| LOAD_ATTR_METHOD_NO_DICT | 142,710,244 | 6.5% |
| CALL_PY_EXACT_ARGS | 122,167,160 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,925,780 | 95.5% |
| LOAD_FAST_AND_CLEAR | 935,280 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 19,917,620 | 95.5% |
| LOAD_FAST_AND_CLEAR | 935,280 | 4.5% |
| MAKE_CELL | 8,160 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,616,880 | 76.4% |
| POP_JUMP_IF_FALSE | 229,200 | 10.8% |
| LOAD_GLOBAL_BUILTIN | 202,080 | 9.5% |
| POP_JUMP_IF_TRUE | 18,480 | 0.9% |
| LOAD_FAST_CHECK | 16,080 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,506,240 | 71.2% |
| LOAD_ATTR_SLOT | 133,200 | 6.3% |
| EXTENDED_ARG | 122,160 | 5.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 114,480 | 5.4% |
| TO_BOOL_BOOL | 75,120 | 3.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 105,820,320 | 24.9% |
| LOAD_SUPER_ATTR_METHOD | 53,775,840 | 12.6% |
| RESUME_CHECK | 45,401,580 | 10.7% |
| LOAD_GLOBAL_MODULE | 34,708,160 | 8.2% |
| STORE_FAST | 31,524,480 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 186,557,760 | 43.8% |
| CALL_PY_EXACT_ARGS | 77,145,700 | 18.1% |
| STORE_ATTR_INSTANCE_VALUE | 33,158,220 | 7.8% |
| LOAD_FAST | 29,672,600 | 7.0% |
| CONTAINS_OP | 13,658,240 | 3.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 28.6% |
| RETURN_VALUE | 40 | 28.6% |
| RESUME_CHECK | 20 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 57.1% |
| LOAD_GLOBAL_BUILTIN | 40 | 28.6% |
| LOAD_ATTR | 20 | 14.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 16,389,840 | 65.7% |
| CALL_PY_EXACT_ARGS | 3,677,360 | 14.7% |
| CALL_KW | 3,653,040 | 14.6% |
| BINARY_SUBSCR_GETITEM | 705,600 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 439,440 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 16,389,840 | 65.7% |
| RESUME_CHECK | 8,562,480 | 34.3% |
| SWAP | 8,160 | 0.0% |
| RETURN_GENERATOR | 1,920 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 15,836,160 | 68.5% |
| JUMP_FORWARD | 4,706,640 | 20.4% |
| CALL_BUILTIN_CLASS | 1,255,920 | 5.4% |
| CALL_BUILTIN_FAST | 613,200 | 2.7% |
| LOAD_FAST_LOAD_FAST | 334,080 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,542,800 | 88.8% |
| JUMP_BACKWARD | 1,354,800 | 5.9% |
| CALL_FUNCTION_EX | 1,208,400 | 5.2% |
| ENTER_EXECUTOR | 15,120 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 209,818,980 | 51.4% |
| CONTAINS_OP | 60,079,300 | 14.7% |
| IS_OP | 28,561,440 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 18,899,410 | 4.6% |
| TO_BOOL_NONE | 17,221,230 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 190,665,185 | 46.7% |
| LOAD_GLOBAL_BUILTIN | 99,779,027 | 24.5% |
| LOAD_GLOBAL_MODULE | 34,761,640 | 8.5% |
| LOAD_FAST_LOAD_FAST | 20,968,320 | 5.1% |
| POP_TOP | 15,495,890 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,302,240 | 49.0% |
| LOAD_ATTR_SLOT | 22,863,600 | 38.2% |
| LOAD_ATTR | 3,097,680 | 5.2% |
| EXTENDED_ARG | 1,817,280 | 3.0% |
| BINARY_SUBSCR_DICT | 1,569,360 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,381,440 | 47.5% |
| RETURN_CONST | 11,897,520 | 19.9% |
| JUMP_FORWARD | 10,513,680 | 17.6% |
| LOAD_CONST | 3,406,560 | 5.7% |
| LOAD_GLOBAL_BUILTIN | 2,236,000 | 3.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 63,515,920 | 87.7% |
| LOAD_ATTR_SLOT | 3,605,060 | 5.0% |
| BINARY_SUBSCR_DICT | 2,963,040 | 4.1% |
| LOAD_FAST_CHECK | 1,506,240 | 2.1% |
| BINARY_SUBSCR | 223,440 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 27,674,080 | 38.2% |
| LOAD_FAST | 14,799,620 | 20.4% |
| LOAD_CONST | 10,566,720 | 14.6% |
| LOAD_FAST_LOAD_FAST | 8,013,840 | 11.1% |
| RETURN_CONST | 3,494,160 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 75,757,002 | 45.5% |
| TO_BOOL_LIST | 26,056,960 | 15.6% |
| COMPARE_OP_STR | 22,452,684 | 13.5% |
| COMPARE_OP_INT | 8,808,108 | 5.3% |
| IS_OP | 8,735,520 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,361,800 | 44.0% |
| ENTER_EXECUTOR | 19,950,236 | 12.0% |
| LOAD_GLOBAL_MODULE | 18,730,080 | 11.2% |
| POP_TOP | 13,009,744 | 7.8% |
| NOP | 10,561,920 | 6.3% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,960 | 59.3% |
| RETURN_VALUE | 55,440 | 21.8% |
| CALL | 38,640 | 15.2% |
| LOAD_CONST | 9,120 | 3.6% |
| POP_TOP | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 150,960 | 59.3% |
| PUSH_EXC_INFO | 94,320 | 37.0% |
| COPY | 9,360 | 3.7% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 2,138,160 | 85.1% |
| POP_EXCEPT | 192,480 | 7.7% |
| DELETE_FAST | 150,960 | 6.0% |
| POP_JUMP_IF_FALSE | 32,160 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 183,120 | 48.8% |
| PUSH_EXC_INFO | 160,080 | 42.6% |
| CALL_INTRINSIC_1 | 32,160 | 8.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 90,707,040 | 40.3% |
| RESUME_CHECK | 50,785,440 | 22.6% |
| POP_TOP | 17,247,120 | 7.7% |
| POP_JUMP_IF_FALSE | 13,483,200 | 6.0% |
| POP_JUMP_IF_NONE | 11,897,520 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 79,308,000 | 35.2% |
| INTERPRETER_EXIT | 46,489,260 | 20.7% |
| LOAD_FAST | 46,216,320 | 20.5% |
| RETURN_VALUE | 32,131,200 | 14.3% |
| TO_BOOL_BOOL | 8,579,280 | 3.8% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 959,760 | 89.4% |
| STORE_FAST_LOAD_FAST | 48,000 | 4.5% |
| LOAD_ATTR_INSTANCE_VALUE | 47,280 | 4.4% |
| LOAD_FAST | 13,200 | 1.2% |
| RETURN_VALUE | 4,800 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,007,280 | 93.9% |
| JUMP_BACKWARD | 66,000 | 6.1% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,051,600 | 77.6% |
| SET_FUNCTION_ATTRIBUTE | 878,640 | 22.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,284,960 | 32.7% |
| SET_FUNCTION_ATTRIBUTE | 878,640 | 22.4% |
| STORE_FAST | 766,560 | 19.5% |
| LOAD_FAST | 338,640 | 8.6% |
| LOAD_GLOBAL_MODULE | 332,160 | 8.5% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,040,640 | 75.8% |
| LOAD_FAST | 2,141,280 | 23.1% |
| SWAP | 88,560 | 1.0% |
| STORE_ATTR | 10,320 | 0.1% |
| LOAD_ATTR_SLOT | 6,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,035,360 | 43.4% |
| LOAD_FAST | 2,405,520 | 25.9% |
| RETURN_CONST | 2,380,080 | 25.6% |
| LOAD_GLOBAL_MODULE | 193,440 | 2.1% |
| LOAD_CONST | 193,440 | 2.1% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,916,480 | 82.4% |
| SET_FUNCTION_ATTRIBUTE | 318,720 | 9.0% |
| RETURN_VALUE | 120,720 | 3.4% |
| LOAD_ATTR_SLOT | 77,280 | 2.2% |
| FOR_ITER_LIST | 27,360 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,196,720 | 62.1% |
| LOAD_FAST | 847,920 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 193,920 | 5.5% |
| LOAD_CONST | 141,840 | 4.0% |
| LOAD_DEREF | 132,720 | 3.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 67,596,800 | 18.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 38,899,440 | 10.5% |
| FOR_ITER_LIST | 37,153,158 | 10.0% |
| LOAD_ATTR_SLOT | 34,148,640 | 9.2% |
| BUILD_LIST | 24,266,220 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 183,039,704 | 49.2% |
| LOAD_GLOBAL_BUILTIN | 54,888,571 | 14.7% |
| LOAD_GLOBAL_MODULE | 43,854,460 | 11.8% |
| LOAD_FAST_LOAD_FAST | 31,524,480 | 8.5% |
| LOAD_CONST | 14,482,320 | 3.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,971,400 | 60.9% |
| FOR_ITER_TUPLE | 1,310,880 | 20.1% |
| FOR_ITER | 986,880 | 15.1% |
| FOR_ITER_RANGE | 251,040 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,230,820 | 34.2% |
| LOAD_CONST | 1,289,040 | 19.8% |
| LOAD_ATTR_INSTANCE_VALUE | 933,840 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 660,720 | 10.1% |
| LOAD_ATTR_METHOD_NO_DICT | 393,360 | 6.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 11,719,980 | 47.3% |
| UNPACK_SEQUENCE_LIST | 10,964,160 | 44.3% |
| UNPACK_SEQUENCE_TUPLE | 1,397,580 | 5.6% |
| COPY | 458,160 | 1.8% |
| BINARY_SUBSCR_LIST_INT | 75,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,396,300 | 74.3% |
| LOAD_FAST_LOAD_FAST | 2,766,080 | 11.2% |
| STORE_FAST | 1,503,540 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,420,080 | 5.7% |
| LOAD_GLOBAL_MODULE | 276,000 | 1.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 19,917,620 | 30.3% |
| BUILD_LIST | 18,125,060 | 27.6% |
| ENTER_EXECUTOR | 8,338,080 | 12.7% |
| FOR_ITER_LIST | 6,752,720 | 10.3% |
| LOAD_FAST | 3,623,760 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 18,125,060 | 27.6% |
| FOR_ITER_LIST | 16,725,800 | 25.5% |
| STORE_FAST | 16,063,920 | 24.4% |
| COPY | 2,687,520 | 4.1% |
| POP_TOP | 2,643,600 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 720 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 67,920 | 71.6% |
| COPY | 19,920 | 21.0% |
| FOR_ITER_LIST | 5,360 | 5.6% |
| CALL_BUILTIN_CLASS | 960 | 1.0% |
| CALL_FUNCTION_EX | 480 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 73,200 | 77.1% |
| STORE_FAST_STORE_FAST | 21,440 | 22.6% |
| UNPACK_SEQUENCE | 260 | 0.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,893,120 | 22.5% |
| LOAD_CONST | 1,414,080 | 16.8% |
| ENTER_EXECUTOR | 1,293,520 | 15.4% |
| LOAD_FAST | 856,160 | 10.2% |
| CALL_ISINSTANCE | 597,280 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,184,400 | 85.4% |
| STORE_FAST | 673,200 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 282,240 | 3.4% |
| YIELD_VALUE | 274,608 | 3.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 215,040 | 99.5% |
| BINARY_OP_ADD_INT | 900 | 0.4% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 215,040 | 99.5% |
| BINARY_OP_ADD_INT | 900 | 0.4% |
| STORE_FAST | 120 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,178,908 | 55.8% |
| CALL_LEN | 1,133,760 | 19.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,100,880 | 19.3% |
| LOAD_FAST | 145,920 | 2.6% |
| LOAD_FAST_LOAD_FAST | 133,680 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,366,880 | 41.6% |
| LOAD_FAST | 1,546,476 | 27.2% |
| SWAP | 743,280 | 13.1% |
| LOAD_FAST_LOAD_FAST | 516,720 | 9.1% |
| LOAD_CONST | 160,560 | 2.8% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,754,880 | 35.1% |
| LOAD_FAST | 1,047,120 | 21.0% |
| CALL_METHOD_DESCRIPTOR_O | 738,480 | 14.8% |
| LOAD_FAST_LOAD_FAST | 738,000 | 14.8% |
| BINARY_SLICE | 338,160 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,442,640 | 28.9% |
| RETURN_VALUE | 1,009,680 | 20.2% |
| SET_ADD | 959,760 | 19.2% |
| STORE_FAST | 802,800 | 16.1% |
| BUILD_TUPLE | 327,360 | 6.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 960 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,360 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 134,520 | 61.1% |
| LOAD_FAST_LOAD_FAST | 85,440 | 38.8% |
| LOAD_ATTR_WITH_HINT | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 176,880 | 80.3% |
| LOAD_FAST_LOAD_FAST | 42,480 | 19.3% |
| LOAD_GLOBAL_BUILTIN | 480 | 0.2% |
| LOAD_FAST | 240 | 0.1% |
| BINARY_OP_ADD_FLOAT | 120 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,637,792 | 93.8% |
| LOAD_FAST | 88,872 | 3.2% |
| CALL_LEN | 73,920 | 2.6% |
| LOAD_FAST_LOAD_FAST | 5,760 | 0.2% |
| LOAD_ATTR_SLOT | 2,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,387,440 | 49.4% |
| BINARY_SLICE | 667,680 | 23.8% |
| SWAP | 217,680 | 7.7% |
| STORE_FAST | 205,440 | 7.3% |
| BINARY_SUBSCR_LIST_INT | 197,760 | 7.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 75,875,040 | 85.9% |
| LOAD_FAST | 6,835,992 | 7.7% |
| BINARY_SUBSCR_DICT | 2,280,480 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 1,366,080 | 1.5% |
| LOAD_DEREF | 1,125,840 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,393,680 | 18.6% |
| STORE_FAST | 14,940,480 | 16.9% |
| LOAD_CONST | 14,918,400 | 16.9% |
| GET_ITER | 9,363,600 | 10.6% |
| CALL_PY_EXACT_ARGS | 7,138,560 | 8.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,149,840 | 55.0% |
| ENTER_EXECUTOR | 635,520 | 30.4% |
| LOAD_FAST_LOAD_FAST | 298,800 | 14.3% |
| LOAD_CONST | 7,200 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,385,280 | 66.2% |
| MAKE_CELL | 705,600 | 33.7% |
| LOAD_ATTR_SLOT | 480 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,438,480 | 44.7% |
| LOAD_FAST | 4,211,040 | 29.2% |
| LOAD_FAST_LOAD_FAST | 3,487,200 | 24.2% |
| BINARY_OP_SUBTRACT_INT | 197,760 | 1.4% |
| BINARY_OP_ADD_INT | 35,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,134,320 | 14.8% |
| STORE_FAST | 2,085,600 | 14.5% |
| LOAD_GLOBAL_MODULE | 1,692,240 | 11.8% |
| BINARY_SUBSCR_DICT | 1,366,080 | 9.5% |
| CALL_PY_EXACT_ARGS | 1,205,520 | 8.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 557,520 | 79.2% |
| BINARY_OP_ADD_INT | 88,320 | 12.5% |
| LOAD_FAST_LOAD_FAST | 30,480 | 4.3% |
| BINARY_OP_SUBTRACT_INT | 27,840 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 472,320 | 67.1% |
| LOAD_FAST | 119,520 | 17.0% |
| CALL_BUILTIN_O | 50,880 | 7.2% |
| LOAD_FAST_LOAD_FAST | 25,440 | 3.6% |
| COMPARE_OP_STR | 25,440 | 3.6% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,238,880 | 99.7% |
| LOAD_FAST_LOAD_FAST | 3,360 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 230,880 | 18.6% |
| FORMAT_SIMPLE | 211,200 | 17.0% |
| LOAD_FAST_LOAD_FAST | 155,520 | 12.5% |
| STORE_FAST | 151,200 | 12.2% |
| CALL | 116,640 | 9.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,345,280 | 46.9% |
| LOAD_FAST | 1,370,160 | 27.4% |
| LOAD_GLOBAL_MODULE | 526,080 | 10.5% |
| CALL | 322,800 | 6.5% |
| RETURN_VALUE | 274,320 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,656,000 | 93.1% |
| COPY_FREE_VARS | 338,160 | 6.8% |
| CALL_PY_EXACT_ARGS | 4,800 | 0.1% |
| STORE_FAST | 1,920 | 0.0% |
| MAKE_CELL | 240 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,718,520 | 63.5% |
| BINARY_SUBSCR_DICT | 4,840,080 | 22.4% |
| LOAD_CONST | 2,020,320 | 9.4% |
| ENTER_EXECUTOR | 738,720 | 3.4% |
| CALL_PY_EXACT_ARGS | 75,960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,514,180 | 90.4% |
| POP_TOP | 1,969,920 | 9.1% |
| CALL_PY_EXACT_ARGS | 75,980 | 0.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 37,660 | 0.2% |
| COPY_FREE_VARS | 240 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,900,740 | 29.7% |
| LOAD_GLOBAL_BUILTIN | 5,352,960 | 17.8% |
| LOAD_ATTR_SLOT | 3,370,458 | 11.2% |
| LOAD_ATTR_CLASS | 2,841,840 | 9.5% |
| CALL_LEN | 2,305,440 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,265,420 | 47.5% |
| LOAD_FAST | 7,887,840 | 26.3% |
| STORE_FAST | 2,811,120 | 9.4% |
| RETURN_VALUE | 1,872,720 | 6.2% |
| MAP_ADD | 1,255,920 | 4.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,416,432 | 41.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,494,640 | 33.2% |
| LOAD_FAST_LOAD_FAST | 1,979,040 | 18.8% |
| LOAD_FAST | 498,720 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 67,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,172,240 | 20.6% |
| RETURN_VALUE | 1,744,320 | 16.6% |
| PUSH_EXC_INFO | 1,715,040 | 16.3% |
| POP_TOP | 1,578,000 | 15.0% |
| TO_BOOL_BOOL | 1,530,240 | 14.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,418,000 | 84.8% |
| RETURN_GENERATOR | 289,440 | 10.2% |
| CALL_BUILTIN_CLASS | 106,320 | 3.7% |
| RETURN_VALUE | 36,000 | 1.3% |
| LOAD_CONST | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,968,720 | 69.0% |
| COPY | 251,520 | 8.8% |
| LOAD_CONST | 228,240 | 8.0% |
| PUSH_EXC_INFO | 154,320 | 5.4% |
| RETURN_VALUE | 108,000 | 3.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 4,252,531 | 31.4% |
| RETURN_GENERATOR | 3,563,280 | 26.3% |
| CALL_STR_1 | 1,836,480 | 13.6% |
| LOAD_FAST | 1,587,600 | 11.7% |
| LOAD_GLOBAL_MODULE | 901,248 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,230,566 | 38.6% |
| LOAD_FAST | 3,717,387 | 27.4% |
| LIST_APPEND | 1,836,480 | 13.6% |
| TO_BOOL_BOOL | 1,276,560 | 9.4% |
| CALL_PY_EXACT_ARGS | 678,480 | 5.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 175,506,048 | 84.5% |
| LOAD_GLOBAL_BUILTIN | 26,363,760 | 12.7% |
| BUILD_TUPLE | 3,398,160 | 1.6% |
| LOAD_ATTR | 1,421,520 | 0.7% |
| LOAD_ATTR_MODULE | 772,800 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 203,001,752 | 97.7% |
| COPY | 3,167,040 | 1.5% |
| YIELD_VALUE | 597,280 | 0.3% |
| RETURN_VALUE | 557,976 | 0.3% |
| STORE_FAST | 297,120 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,164,180 | 56.8% |
| LOAD_ATTR_SLOT | 8,291,040 | 31.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,426,800 | 5.3% |
| LOAD_DEREF | 1,425,600 | 5.3% |
| LOAD_ATTR | 163,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,072,100 | 26.5% |
| COMPARE_OP_INT | 4,471,680 | 16.8% |
| LOAD_GLOBAL_BUILTIN | 3,423,600 | 12.8% |
| SWAP | 2,685,360 | 10.1% |
| CALL_BUILTIN_CLASS | 2,305,440 | 8.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,693,960 | 77.5% |
| RETURN_VALUE | 1,977,360 | 8.2% |
| ENTER_EXECUTOR | 1,141,920 | 4.7% |
| LOAD_CONST | 426,000 | 1.8% |
| BUILD_TUPLE | 411,360 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,146,000 | 54.5% |
| ENTER_EXECUTOR | 6,655,860 | 27.6% |
| NOP | 1,826,400 | 7.6% |
| EXTENDED_ARG | 512,400 | 2.1% |
| LOAD_CONST | 510,780 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,711,680 | 54.2% |
| LOAD_ATTR_METHOD_NO_DICT | 15,325,476 | 32.3% |
| LOAD_CONST | 2,040,720 | 4.3% |
| ENTER_EXECUTOR | 1,422,480 | 3.0% |
| LOAD_GLOBAL_MODULE | 1,039,680 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 38,899,440 | 82.0% |
| POP_TOP | 3,558,156 | 7.5% |
| LOAD_FAST | 2,100,000 | 4.4% |
| CALL_PY_EXACT_ARGS | 692,400 | 1.5% |
| LOAD_ATTR_METHOD_NO_DICT | 531,420 | 1.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,121,600 | 90.2% |
| LOAD_FAST | 140,640 | 6.0% |
| LOAD_ATTR_MODULE | 69,360 | 3.0% |
| LOAD_ATTR_METHOD_NO_DICT | 19,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,646,880 | 70.0% |
| LOAD_CONST | 257,040 | 10.9% |
| UNPACK_SEQUENCE_LIST | 144,480 | 6.1% |
| GET_ITER | 141,360 | 6.0% |
| CONTAINS_OP | 69,360 | 3.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,237,040 | 98.3% |
| ENTER_EXECUTOR | 30,240 | 1.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,700 | 0.2% |
| LOAD_ATTR | 4,320 | 0.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,296,000 | 56.9% |
| LOAD_FAST | 431,280 | 18.9% |
| POP_TOP | 240,720 | 10.6% |
| CALL_BUILTIN_CLASS | 180,000 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 67,200 | 3.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,887,600 | 53.8% |
| LOAD_FAST | 2,981,280 | 32.8% |
| RETURN_VALUE | 474,240 | 5.2% |
| LOAD_ATTR_SLOT | 192,980 | 2.1% |
| BUILD_TUPLE | 182,400 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,808,320 | 41.9% |
| POP_TOP | 3,249,620 | 35.8% |
| BINARY_OP_ADD_INT | 1,100,880 | 12.1% |
| BINARY_OP_ADD_UNICODE | 738,480 | 8.1% |
| STORE_FAST | 128,400 | 1.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,167,160 | 37.4% |
| LOAD_FAST_LOAD_FAST | 77,145,700 | 23.6% |
| LOAD_ATTR_METHOD_NO_DICT | 55,898,544 | 17.1% |
| LOAD_ATTR_SLOT | 10,409,120 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,503,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 283,628,336 | 86.8% |
| COPY_FREE_VARS | 35,588,160 | 10.9% |
| MAKE_CELL | 3,677,360 | 1.1% |
| RETURN_GENERATOR | 3,167,360 | 1.0% |
| CALL_PY_EXACT_ARGS | 543,538 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 5,951,040 | 38.3% |
| LOAD_FAST | 5,071,440 | 32.6% |
| LOAD_FAST_LOAD_FAST | 1,382,160 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 930,960 | 6.0% |
| LOAD_ATTR_SLOT | 484,560 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,923,680 | 96.0% |
| MAKE_CELL | 439,440 | 2.8% |
| COPY_FREE_VARS | 175,440 | 1.1% |
| CALL_PY_EXACT_ARGS | 6,000 | 0.0% |
| RETURN_GENERATOR | 720 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,610,240 | 100.0% |
| UNARY_NOT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 1,836,480 | 70.4% |
| LOAD_FAST | 737,760 | 28.3% |
| STORE_FAST | 24,720 | 0.9% |
| CALL | 11,280 | 0.4% |
| BUILD_TUPLE | 240 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,113,680 | 92.5% |
| LOAD_ATTR_SLOT | 1,098,664 | 7.2% |
| RETURN_VALUE | 16,800 | 0.1% |
| LOAD_FAST_CHECK | 14,640 | 0.1% |
| RETURN_GENERATOR | 5,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,220,000 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 571,920 | 3.8% |
| BUILD_TUPLE | 398,344 | 2.6% |
| CALL_PY_EXACT_ARGS | 25,200 | 0.2% |
| RETURN_VALUE | 18,000 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,332,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,212,320 | 62.6% |
| STORE_FAST | 1,153,440 | 13.8% |
| LOAD_ATTR | 1,082,880 | 13.0% |
| PUSH_NULL | 667,680 | 8.0% |
| LOAD_GLOBAL_MODULE | 90,000 | 1.1% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,560 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,165,096 | 38.7% |
| CALL_LEN | 4,471,680 | 15.5% |
| LOAD_GLOBAL_MODULE | 2,694,960 | 9.4% |
| COPY | 2,685,360 | 9.3% |
| LOAD_ATTR_CLASS | 2,666,400 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,684,332 | 57.9% |
| POP_JUMP_IF_TRUE | 8,808,108 | 30.6% |
| COPY | 1,579,466 | 5.5% |
| RETURN_VALUE | 957,167 | 3.3% |
| EXTENDED_ARG | 470,400 | 1.6% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 25,550,392 | 73.3% |
| LOAD_FAST | 6,797,904 | 19.5% |
| RETURN_VALUE | 718,500 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 625,562 | 1.8% |
| LOAD_ATTR_MODULE | 475,440 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 22,452,684 | 64.4% |
| POP_JUMP_IF_FALSE | 8,532,760 | 24.5% |
| COPY | 2,321,688 | 6.7% |
| RETURN_VALUE | 923,031 | 2.6% |
| EXTENDED_ARG | 582,000 | 1.7% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 923,280 | 92.7% |
| GET_ITER | 72,720 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 923,280 | 92.7% |
| POP_TOP | 72,720 | 7.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 33,770,960 | 59.9% |
| SWAP | 16,725,800 | 29.7% |
| LOAD_FAST | 3,875,520 | 6.9% |
| EXTENDED_ARG | 1,092,400 | 1.9% |
| ENTER_EXECUTOR | 832,002 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 37,153,158 | 65.9% |
| SWAP | 6,752,720 | 12.0% |
| LOAD_FAST | 4,213,864 | 7.5% |
| STORE_FAST_LOAD_FAST | 3,971,400 | 7.0% |
| RETURN_CONST | 2,555,880 | 4.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,464,540 | 86.8% |
| SWAP | 592,800 | 11.5% |
| EXTENDED_ARG | 87,600 | 1.7% |
| JUMP_BACKWARD | 880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,890,400 | 36.7% |
| LOAD_FAST | 1,430,940 | 27.8% |
| RETURN_CONST | 1,080,240 | 21.0% |
| LOAD_GLOBAL_MODULE | 493,200 | 9.6% |
| STORE_FAST_LOAD_FAST | 251,040 | 4.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,372,212 | 82.7% |
| SWAP | 2,067,660 | 11.9% |
| ENTER_EXECUTOR | 881,053 | 5.1% |
| EXTENDED_ARG | 25,920 | 0.1% |
| FOR_ITER_LIST | 23,381 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,261,253 | 59.0% |
| STORE_FAST | 5,032,311 | 28.9% |
| STORE_FAST_LOAD_FAST | 1,310,880 | 7.5% |
| SWAP | 531,040 | 3.1% |
| RETURN_CONST | 223,340 | 1.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,899,040 | 88.6% |
| LOAD_FAST | 1,158,240 | 10.4% |
| COPY | 79,200 | 0.7% |
| ENTER_EXECUTOR | 34,080 | 0.3% |
| LOAD_ATTR_CLASS | 5,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,841,840 | 25.4% |
| COMPARE_OP_INT | 2,666,400 | 23.9% |
| LOAD_ATTR_METHOD_NO_DICT | 2,028,240 | 18.1% |
| CALL | 1,925,520 | 17.2% |
| LOAD_ATTR_MODULE | 1,158,240 | 10.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,929,664 | 80.6% |
| LOAD_FAST_LOAD_FAST | 9,532,860 | 8.2% |
| LOAD_ATTR_INSTANCE_VALUE | 4,462,440 | 3.8% |
| LOAD_GLOBAL_MODULE | 3,131,760 | 2.7% |
| LOAD_DEREF | 1,353,600 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,050,362 | 18.9% |
| LOAD_CONST | 20,943,860 | 18.0% |
| LOAD_ATTR_METHOD_NO_DICT | 10,774,080 | 9.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,710,640 | 8.3% |
| CONTAINS_OP | 5,939,040 | 5.1% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,480 | 99.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 240 | 1.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 142,710,244 | 72.2% |
| LOAD_ATTR_SLOT | 19,708,272 | 10.0% |
| LOAD_ATTR_INSTANCE_VALUE | 10,774,080 | 5.5% |
| LOAD_GLOBAL_MODULE | 7,435,680 | 3.8% |
| ENTER_EXECUTOR | 6,215,200 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 87,803,300 | 44.4% |
| CALL_PY_EXACT_ARGS | 55,898,544 | 28.3% |
| LOAD_CONST | 19,069,932 | 9.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 15,325,476 | 7.8% |
| LOAD_GLOBAL_MODULE | 13,511,640 | 6.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,101,660 | 81.7% |
| LOAD_ATTR_INSTANCE_VALUE | 9,710,640 | 11.3% |
| LOAD_DEREF | 1,925,760 | 2.2% |
| LOAD_ATTR_WITH_HINT | 1,020,000 | 1.2% |
| LOAD_FAST_LOAD_FAST | 1,019,760 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,823,280 | 69.7% |
| LOAD_FAST_LOAD_FAST | 11,992,900 | 14.0% |
| CALL_PY_EXACT_ARGS | 8,503,440 | 9.9% |
| LOAD_CONST | 2,029,440 | 2.4% |
| LOAD_DEREF | 1,595,280 | 1.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,086,951 | 59.9% |
| LOAD_ATTR_MODULE | 4,548,720 | 20.8% |
| ENTER_EXECUTOR | 1,987,309 | 9.1% |
| LOAD_ATTR_CLASS | 1,158,240 | 5.3% |
| LOAD_FAST_LOAD_FAST | 926,400 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,401,300 | 24.7% |
| LOAD_ATTR_MODULE | 4,548,720 | 20.8% |
| LOAD_FAST | 3,214,800 | 14.7% |
| COMPARE_OP | 2,470,320 | 11.3% |
| LOAD_GLOBAL_MODULE | 1,217,280 | 5.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 802,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 737,760 | 92.0% |
| LOAD_FAST | 32,400 | 4.0% |
| IS_OP | 32,160 | 4.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 516,960 | 60.4% |
| LOAD_FAST | 281,360 | 32.9% |
| ENTER_EXECUTOR | 54,400 | 6.4% |
| LOAD_FAST_LOAD_FAST | 2,640 | 0.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 538,800 | 63.0% |
| CALL_LEN | 103,440 | 12.1% |
| RETURN_VALUE | 78,960 | 9.2% |
| LOAD_FAST | 71,760 | 8.4% |
| TO_BOOL_BOOL | 34,560 | 4.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,324,198 | 55.2% |
| LOAD_ATTR_SLOT | 4,846,700 | 23.6% |
| ENTER_EXECUTOR | 3,725,592 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 362,160 | 1.8% |
| CALL | 70,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,154,190 | 93.4% |
| RETURN_VALUE | 805,340 | 3.9% |
| STORE_FAST | 181,200 | 0.9% |
| LOAD_FAST | 180,220 | 0.9% |
| LOAD_CONST | 80,000 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 327,092,937 | 88.3% |
| LOAD_ATTR_SLOT | 26,030,636 | 7.0% |
| LOAD_DEREF | 5,834,880 | 1.6% |
| LOAD_FAST_LOAD_FAST | 4,916,640 | 1.3% |
| STORE_FAST_LOAD_FAST | 2,230,820 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,373,086 | 12.0% |
| GET_ITER | 35,915,712 | 9.7% |
| STORE_FAST | 34,148,640 | 9.2% |
| RETURN_VALUE | 27,350,228 | 7.4% |
| LOAD_ATTR_SLOT | 26,030,636 | 7.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,138,400 | 56.5% |
| LOAD_FAST_LOAD_FAST | 4,829,520 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,727,280 | 20.3% |
| LOAD_ATTR_WITH_HINT | 376,860 | 1.6% |
| ENTER_EXECUTOR | 172,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,265,280 | 31.2% |
| TO_BOOL_BOOL | 2,745,840 | 11.8% |
| LOAD_ATTR_METHOD_NO_DICT | 2,720,640 | 11.7% |
| COPY | 2,092,320 | 9.0% |
| LOAD_FAST | 1,864,560 | 8.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 126,535,534 | 30.6% |
| POP_JUMP_IF_FALSE | 99,779,027 | 24.2% |
| STORE_FAST | 54,888,571 | 13.3% |
| LOAD_FAST | 29,736,720 | 7.2% |
| POP_JUMP_IF_NOT_NONE | 27,674,080 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 287,171,172 | 69.5% |
| LOAD_DEREF | 69,111,360 | 16.7% |
| CALL_ISINSTANCE | 26,363,760 | 6.4% |
| CALL_BUILTIN_CLASS | 5,352,960 | 1.3% |
| LOAD_FAST_LOAD_FAST | 4,872,540 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 203,826,739 | 44.4% |
| STORE_FAST | 43,854,460 | 9.6% |
| RESUME_CHECK | 39,967,800 | 8.7% |
| POP_JUMP_IF_FALSE | 34,761,640 | 7.6% |
| LOAD_GLOBAL_MODULE | 24,579,120 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 175,506,048 | 38.3% |
| LOAD_FAST | 87,482,360 | 19.1% |
| LOAD_FAST_LOAD_FAST | 34,708,160 | 7.6% |
| IS_OP | 31,202,400 | 6.8% |
| LOAD_GLOBAL_MODULE | 24,579,120 | 5.4% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 812,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 808,080 | 99.5% |
| STORE_FAST | 4,320 | 0.5% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,576,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 53,775,840 | 83.3% |
| CALL_PY_WITH_DEFAULTS | 5,951,040 | 9.2% |
| CALL_PY_EXACT_ARGS | 2,446,800 | 3.8% |
| LOAD_FAST | 1,556,880 | 2.4% |
| LOAD_GLOBAL_MODULE | 516,960 | 0.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 283,628,336 | 54.6% |
| COPY_FREE_VARS | 69,822,300 | 13.4% |
| CACHE | 52,310,354 | 10.1% |
| CALL_KW | 32,570,160 | 6.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,514,180 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 227,289,986 | 43.8% |
| LOAD_GLOBAL_BUILTIN | 126,535,534 | 24.4% |
| RETURN_CONST | 50,785,440 | 9.8% |
| LOAD_FAST_LOAD_FAST | 45,401,580 | 8.7% |
| LOAD_GLOBAL_MODULE | 39,967,800 | 7.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 274,608 | 79.2% |
| LOAD_CONST | 72,000 | 20.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 274,608 | 79.2% |
| POP_TOP | 72,000 | 20.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 33,158,220 | 56.7% |
| LOAD_FAST | 24,383,580 | 41.7% |
| SWAP | 595,920 | 1.0% |
| BINARY_SUBSCR | 337,200 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 24,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,463,920 | 46.9% |
| RETURN_CONST | 10,268,220 | 17.6% |
| LOAD_FAST | 9,750,720 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 3,851,520 | 6.6% |
| LOAD_GLOBAL_MODULE | 2,751,840 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 268,484,667 | 58.7% |
| LOAD_FAST_LOAD_FAST | 186,557,760 | 40.8% |
| STORE_ATTR_SLOT | 1,862,747 | 0.4% |
| LOAD_ATTR_SLOT | 589,200 | 0.1% |
| LOAD_DEREF | 11,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 126,971,520 | 27.8% |
| LOAD_FAST_LOAD_FAST | 105,820,320 | 23.1% |
| RETURN_CONST | 90,707,040 | 19.8% |
| LOAD_FAST | 83,669,307 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 23,764,560 | 5.2% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 708,000 | 57.4% |
| LOAD_FAST_LOAD_FAST | 523,200 | 42.4% |
| SWAP | 720 | 0.1% |
| STORE_ATTR_WITH_HINT | 600 | 0.0% |
| LOAD_DEREF | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 384,240 | 31.2% |
| LOAD_GLOBAL_MODULE | 336,480 | 27.3% |
| RETURN_CONST | 258,480 | 21.0% |
| LOAD_FAST | 192,960 | 15.6% |
| LOAD_GLOBAL_BUILTIN | 59,040 | 4.8% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,741,232 | 73.6% |
| LOAD_FAST_LOAD_FAST | 329,280 | 8.8% |
| LOAD_ATTR_SLOT | 307,920 | 8.3% |
| SWAP | 276,000 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 35,520 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,873,200 | 50.3% |
| LOAD_FAST | 693,792 | 18.6% |
| JUMP_BACKWARD | 638,600 | 17.1% |
| ENTER_EXECUTOR | 351,400 | 9.4% |
| LOAD_GLOBAL_BUILTIN | 71,520 | 1.9% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 323,280 | 99.9% |
| LOAD_FAST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 322,800 | 99.7% |
| LOAD_FAST | 480 | 0.1% |
| EXTENDED_ARG | 480 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,629,764 | 76.0% |
| LOAD_ATTR_SLOT | 4,237,340 | 19.4% |
| LOAD_ATTR_INSTANCE_VALUE | 416,520 | 1.9% |
| COPY | 176,420 | 0.8% |
| LOAD_ATTR | 170,160 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,899,410 | 86.3% |
| POP_JUMP_IF_TRUE | 2,188,060 | 10.0% |
| EXTENDED_ARG | 748,900 | 3.4% |
| TO_BOOL_NONE | 27,688 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 25,678 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 203,001,752 | 65.4% |
| COPY | 28,864,830 | 9.3% |
| LOAD_FAST | 25,679,280 | 8.3% |
| RETURN_VALUE | 19,061,860 | 6.1% |
| LOAD_ATTR_SLOT | 8,797,860 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 209,818,980 | 67.6% |
| POP_JUMP_IF_TRUE | 75,757,002 | 24.4% |
| UNARY_NOT | 17,118,960 | 5.5% |
| EXTENDED_ARG | 7,825,680 | 2.5% |
| TO_BOOL_STR | 480 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 886,320 | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE | 267,120 | 19.0% |
| RETURN_VALUE | 111,360 | 7.9% |
| LOAD_ATTR_SLOT | 104,160 | 7.4% |
| BINARY_OP | 35,520 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,008,480 | 71.7% |
| POP_JUMP_IF_TRUE | 292,080 | 20.8% |
| UNARY_NOT | 104,160 | 7.4% |
| TO_BOOL_STR | 960 | 0.1% |
| TO_BOOL_BOOL | 240 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,007,240 | 75.9% |
| LOAD_ATTR_SLOT | 4,881,480 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,946,160 | 5.7% |
| COPY | 666,300 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 294,960 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,056,960 | 76.0% |
| POP_JUMP_IF_FALSE | 5,722,440 | 16.7% |
| UNARY_NOT | 1,893,840 | 5.5% |
| EXTENDED_ARG | 593,280 | 1.7% |
| TO_BOOL | 3,240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,233,716 | 63.4% |
| LOAD_ATTR_SLOT | 5,800,720 | 24.2% |
| COPY | 1,346,520 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 436,440 | 1.8% |
| LOAD_ATTR_MODULE | 389,280 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,221,230 | 71.7% |
| POP_JUMP_IF_TRUE | 6,168,620 | 25.7% |
| EXTENDED_ARG | 578,300 | 2.4% |
| TO_BOOL_ALWAYS_TRUE | 27,734 | 0.1% |
| UNARY_NOT | 5,700 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,996,260 | 71.9% |
| COPY | 1,130,020 | 16.3% |
| LOAD_ATTR_SLOT | 327,420 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 262,320 | 3.8% |
| STORE_FAST_LOAD_FAST | 140,480 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,075,440 | 58.7% |
| POP_JUMP_IF_TRUE | 2,589,800 | 37.3% |
| UNARY_NOT | 277,200 | 4.0% |
| TO_BOOL_NONE | 3,740 | 0.1% |
| TO_BOOL_INT | 1,200 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 10,636,560 | 97.0% |
| RETURN_VALUE | 174,720 | 1.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 144,480 | 1.3% |
| LOAD_FAST | 12,000 | 0.1% |
| BINARY_SLICE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 10,964,160 | 100.0% |
| STORE_FAST | 4,320 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 583,680 | 38.8% |
| YIELD_VALUE | 282,240 | 18.8% |
| STORE_FAST | 280,320 | 18.7% |
| FOR_ITER | 182,400 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 69,840 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,397,580 | 93.0% |
| STORE_FAST | 105,360 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 10,369,440 | 82.3% |
| RETURN_VALUE | 1,103,320 | 8.8% |
| FOR_ITER_LIST | 374,220 | 3.0% |
| STORE_FAST | 278,640 | 2.2% |
| RETURN_CONST | 217,920 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 11,719,980 | 93.0% |
| STORE_FAST | 856,140 | 6.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 22,560 | 0.2% |


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
| specialization.deferred |     30247032 | 19.3% |
|          hit |    126264240 | 80.7% |
|         miss |          480 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 10,708 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 5,508 | 51.4% |
| other | 3,740 | 34.9% |
| code complex parameters | 1,340 | 12.5% |
| buffer int | 80 | 0.7% |
| tuple slice | 40 | 0.4% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2822880 | 39.8% |
|          hit |      4268640 | 60.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 940 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 820 | 87.2% |
| out of range | 120 | 12.8% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     15187520 | 3.5% |
| specialization.deopt |       102640 | 0.0% |
|          hit |    410418458 | 95.2% |
|         miss |      5446364 | 1.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 102,640 | 75.6% |
| Failure | 33,120 | 24.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 14,540 | 43.9% |
| tuple | 11,620 | 35.1% |
| dict | 3,360 | 10.1% |
| other | 1,780 | 5.4% |
| mapping | 1,140 | 3.4% |
| set | 680 | 2.1% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3606000 | 15.8% |
| specialization.deopt |         1800 | 0.0% |
|          hit |     19139460 | 83.8% |
|         miss |        95460 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,800 | 29.1% |
| Failure | 4,380 | 70.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 1,760 | 40.2% |
| multiply different types | 1,080 | 24.7% |
| remainder | 480 | 11.0% |
| or | 480 | 11.0% |
| subtract other | 360 | 8.2% |
| and int | 80 | 1.8% |
| true divide different types | 40 | 0.9% |
| subtract different types | 40 | 0.9% |
| and other | 40 | 0.9% |
| and different types | 20 | 0.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     51390960 | 5.9% |
| specialization.deopt |       851758 | 0.1% |
|          hit |    775458363 | 88.9% |
|         miss |     45231494 | 5.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 851,818 | 95.8% |
| Failure | 37,300 | 4.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 14,420 | 38.7% |
| code complex parameters | 8,580 | 23.0% |
| meth descr varargs | 3,400 | 9.1% |
| class no vectorcall | 2,880 | 7.7% |
| class mutable | 2,180 | 5.8% |
| cfunc noargs | 1,840 | 4.9% |
| cfunc varargs keywords | 1,080 | 2.9% |
| meth descr varargs keywords | 640 | 1.7% |
| wrong number arguments | 420 | 1.1% |
| other | 400 | 1.1% |
| init not simple | 380 | 1.0% |
| meth descr method fastcall keywords | 320 | 0.9% |
| cfunc varargs | 300 | 0.8% |
| bound method | 240 | 0.6% |
| init not python | 100 | 0.3% |
| cmethod | 80 | 0.2% |
| operator wrapper | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     32135736 | 30.3% |
| specialization.deopt |        12841 | 0.0% |
|          hit |     73109798 | 69.0% |
|         miss |       680275 | 0.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,821 | 20.1% |
| Failure | 50,973 | 79.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 36,581 | 71.8% |
| baseobject | 4,820 | 9.5% |
| different types | 3,320 | 6.5% |
| bool | 2,092 | 4.1% |
| other | 2,040 | 4.0% |
| tuple | 1,340 | 2.6% |
| list | 640 | 1.3% |
| set | 80 | 0.2% |
| string | 60 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     28393593 | 26.2% |
| specialization.deopt |        49715 | 0.0% |
|          hit |     77228917 | 71.3% |
|         miss |      2633064 | 2.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 49,714 | 77.8% |
| Failure | 14,179 | 22.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 4,499 | 31.7% |
| enumerate | 2,980 | 21.0% |
| reversed list | 2,000 | 14.1% |
| dict items | 1,820 | 12.8% |
| zip | 1,640 | 11.6% |
| dict keys | 620 | 4.4% |
| dict values | 280 | 2.0% |
| itertools | 180 | 1.3% |
| map | 120 | 0.8% |
| other | 40 | 0.3% |


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
| specialization.deferred |     86271092 | 8.9% |
| specialization.deopt |      1246334 | 0.1% |
|          hit |    817166160 | 84.3% |
|         miss |     66133613 | 6.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,246,414 | 94.0% |
| Failure | 79,720 | 6.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 44,780 | 56.2% |
| not managed dict | 9,720 | 12.2% |
| shadowed | 8,880 | 11.1% |
| metaclass attribute | 5,000 | 6.3% |
| class method obj | 3,660 | 4.6% |
| non overriding descriptor | 3,060 | 3.8% |
| method | 1,700 | 2.1% |
| class attr simple | 1,080 | 1.4% |
| module attr not found | 880 | 1.1% |
| non object slot | 600 | 0.8% |
| builtin class method | 160 | 0.2% |
| class attr descriptor | 120 | 0.2% |
| mutable class | 80 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
| specialization.deopt |           20 | 0.0% |
|          hit |    912869315 | 100.0% |
|         miss |           40 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     65388960 | 100.0% |


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
|          hit |       346608 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      9278160 | 1.8% |
| specialization.deopt |      1887807 | 0.4% |
|          hit |    417496371 | 79.2% |
|         miss |    100056783 | 19.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,887,807 | 99.5% |
| Failure | 10,440 | 0.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 5,200 | 49.8% |
| not in dict | 4,640 | 44.4% |
| overridden | 260 | 2.5% |
| non object slot | 180 | 1.7% |
| not in keys | 160 | 1.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        94640 | 0.3% |
|          hit |     27436860 | 99.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 7.1% |
| Failure | 260 | 92.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 140 | 53.8% |
| iterator | 120 | 46.2% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 5,356,346,479 | 50.4% |
| Not specialized | 1,206,891,513 | 11.4% |
| Specialized | 4,067,296,632 | 38.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,228 | 100.0% |
| LOAD_ATTR | 86,271,092 | 0.0% |
| CALL | 51,390,960 | 0.0% |
| COMPARE_OP | 32,135,736 | 0.0% |
| BINARY_SUBSCR | 30,247,032 | 0.0% |
| FOR_ITER | 28,393,593 | 0.0% |
| TO_BOOL | 15,187,520 | 0.0% |
| STORE_ATTR | 9,278,160 | 0.0% |
| BINARY_OP | 3,606,000 | 0.0% |
| STORE_SUBSCR | 2,822,880 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 98,725,983 | 44.8% |
| LOAD_ATTR_METHOD_NO_DICT | 42,899,177 | 19.5% |
| CALL_PY_EXACT_ARGS | 33,476,154 | 15.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,058,684 | 5.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,034,840 | 2.7% |
| LOAD_ATTR_SLOT | 5,797,852 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 4,240,060 | 1.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,145,000 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 2,878,626 | 1.3% |
| TO_BOOL_NONE | 1,965,478 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 92,829,314 | 17.4% |
| Calls to Python functions inlined | 441,976,434 | 82.6% |
| Calls via PyEval_EvalFrame (total) | 92,829,314 | 17.4% |
| Calls via PyEval_EvalFrame (vector) | 79,918,994 | 14.9% |
| Calls via PyEval_EvalFrame (generator) | 12,910,320 | 2.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 79,918,994 | 14.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 10,417,688 | 1.9% |
| Calls via PyEval_EvalFrame (function ex) | 1,856,280 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 17,748,126 | 3.3% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 525,547,220 | 98.3% |
| Frame objects created | 6,893,580 | 1.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 230,515,707 | 28.3% |
| Frees to freelist | 230,518,544 |  |
| Allocations | 584,447,828 | 71.7% |
| Allocations to 512 bytes | 583,666,972 | 71.6% |
| Allocations to 4 kbytes | 542,476 | 0.1% |
| Allocations over 4 kbytes | 238,380 | 0.0% |
| Frees | 591,418,560 |  |
| New values | 6,648,780 |  |
| Interpreter increfs | 5,313,901,118 | 71.8% |
| Interpreter decrefs | 5,693,282,026 | 70.5% |
| Increfs | 2,089,438,895 | 28.2% |
| Decrefs | 2,377,286,978 | 29.5% |
| Materialize dict (on request) | 480 | 0.0% |
| Materialize dict (new key) | 1,720 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 280 | 0.0% |
| Method cache hits | 317,330,664 |  |
| Method cache misses | 5,808,204 |  |
| Method cache collisions | 7,019,019 |  |
| Method cache dunder hits | 267,270,126 |  |
| Method cache dunder misses | 1,216,358 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 280 | 324,973 | 670,257,076 |
| 1 | 20 | 24,616,840 | 527,204,374 |
| 2 | 0 | 0 | 0 |


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
