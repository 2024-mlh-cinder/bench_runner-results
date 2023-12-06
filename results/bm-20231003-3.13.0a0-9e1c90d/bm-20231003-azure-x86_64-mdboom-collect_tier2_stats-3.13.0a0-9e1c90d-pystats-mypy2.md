
# Pystats results

- benchmark: mypy2
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,233,814,411 | 20.7% | 20.7% |  |
| LOAD_CONST | 539,209,280 | 5.0% | 25.6% |  |
| RESUME_CHECK | 521,086,658 | 4.8% | 30.5% | 0.0% |
| LOAD_GLOBAL_MODULE | 464,603,183 | 4.3% | 34.8% |  |
| STORE_ATTR_SLOT | 457,813,405 | 4.2% | 39.0% | 21.6% |
| LOAD_FAST_LOAD_FAST | 431,616,620 | 4.0% | 43.0% |  |
| POP_JUMP_IF_FALSE | 420,148,738 | 3.9% | 46.9% |  |
| LOAD_GLOBAL_BUILTIN | 418,430,218 | 3.9% | 50.7% | 0.0% |
| LOAD_ATTR_SLOT | 385,311,273 | 3.6% | 54.3% | 1.5% |
| STORE_FAST | 380,313,613 | 3.5% | 57.8% |  |
| CALL_PY_EXACT_ARGS | 330,454,669 | 3.1% | 60.9% | 10.3% |
| TO_BOOL_BOOL | 314,832,000 | 2.9% | 63.8% | 0.0% |
| RETURN_VALUE | 298,064,462 | 2.8% | 66.6% |  |
| RETURN_CONST | 225,041,508 | 2.1% | 68.6% |  |
| CALL_ISINSTANCE | 211,427,906 | 2.0% | 70.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 207,613,005 | 1.9% | 72.5% | 21.0% |
| POP_JUMP_IF_TRUE | 170,278,402 | 1.6% | 74.1% |  |
| POP_TOP | 165,624,400 | 1.5% | 75.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 118,441,948 | 1.1% | 76.7% | 3.6% |
| LOAD_DEREF | 97,586,620 | 0.9% | 77.6% |  |
| GET_ITER | 91,285,748 | 0.8% | 78.5% |  |
| INTERPRETER_EXIT | 90,678,630 | 0.8% | 79.3% |  |
| BINARY_SUBSCR_DICT | 88,653,564 | 0.8% | 80.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 87,171,602 | 0.8% | 80.9% | 12.7% |
| LOAD_ATTR | 86,741,476 | 0.8% | 81.7% |  |
| ENTER_EXECUTOR | 84,001,028 | 0.8% | 82.5% |  |
| POP_JUMP_IF_NOT_NONE | 73,560,400 | 0.7% | 83.2% |  |
| CONTAINS_OP | 72,143,484 | 0.7% | 83.8% |  |
| COPY_FREE_VARS | 70,547,340 | 0.7% | 84.5% |  |
| SWAP | 65,796,480 | 0.6% | 85.1% |  |
| POP_JUMP_IF_NONE | 65,078,080 | 0.6% | 85.7% |  |
| LOAD_SUPER_ATTR_METHOD | 64,576,560 | 0.6% | 86.3% |  |
| BUILD_LIST | 63,477,960 | 0.6% | 86.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 58,506,940 | 0.5% | 87.4% | 2.2% |
| CALL_KW | 57,378,960 | 0.5% | 88.0% |  |
| FOR_ITER_LIST | 56,603,184 | 0.5% | 88.5% | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 51,751,640 | 0.5% | 89.0% | 8.0% |
| CALL | 51,420,160 | 0.5% | 89.4% |  |
| IS_OP | 42,656,880 | 0.4% | 89.8% |  |
| NOP | 39,932,460 | 0.4% | 90.2% |  |
| COMPARE_OP_STR | 39,648,416 | 0.4% | 90.6% | 0.3% |
| COPY | 38,150,148 | 0.4% | 90.9% |  |
| JUMP_FORWARD | 35,502,240 | 0.3% | 91.3% |  |
| TO_BOOL_LIST | 34,739,100 | 0.3% | 91.6% | 0.7% |
| COMPARE_OP | 32,283,075 | 0.3% | 91.9% |  |
| COMPARE_OP_INT | 31,582,895 | 0.3% | 92.2% | 1.7% |
| BINARY_SUBSCR | 30,395,901 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 30,050,248 | 0.3% | 92.7% |  |
| PUSH_NULL | 29,260,128 | 0.3% | 93.0% |  |
| FOR_ITER | 28,407,458 | 0.3% | 93.3% |  |
| CALL_LEN | 27,018,980 | 0.2% | 93.5% |  |
| TO_BOOL_NONE | 26,543,930 | 0.2% | 93.8% | 7.6% |
| MAKE_CELL | 24,962,400 | 0.2% | 94.0% |  |
| EXTENDED_ARG | 24,936,160 | 0.2% | 94.2% |  |
| STORE_FAST_STORE_FAST | 24,854,840 | 0.2% | 94.4% |  |
| BUILD_TUPLE | 24,118,389 | 0.2% | 94.7% |  |
| CALL_LIST_APPEND | 24,108,180 | 0.2% | 94.9% |  |
| LOAD_ATTR_WITH_HINT | 23,253,420 | 0.2% | 95.1% | 2.1% |
| MAP_ADD | 23,127,840 | 0.2% | 95.3% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 22,010,060 | 0.2% | 95.5% | 28.3% |
| TO_BOOL_ALWAYS_TRUE | 21,941,970 | 0.2% | 95.7% | 13.3% |
| LOAD_ATTR_MODULE | 21,859,840 | 0.2% | 95.9% |  |
| LIST_APPEND | 21,340,320 | 0.2% | 96.1% |  |
| LOAD_FAST_AND_CLEAR | 20,907,360 | 0.2% | 96.3% |  |
| LOAD_ATTR_PROPERTY | 20,512,628 | 0.2% | 96.5% | 6.6% |
| UNARY_NOT | 19,870,320 | 0.2% | 96.7% |  |
| BINARY_SUBSCR_LIST_INT | 19,496,640 | 0.2% | 96.9% |  |
| FOR_ITER_TUPLE | 17,380,454 | 0.2% | 97.0% | 7.4% |
| CALL_PY_WITH_DEFAULTS | 15,545,380 | 0.1% | 97.2% | 2.1% |
| JUMP_BACKWARD | 15,481,796 | 0.1% | 97.3% |  |
| CALL_TUPLE_1 | 15,250,764 | 0.1% | 97.5% |  |
| TO_BOOL | 15,226,040 | 0.1% | 97.6% |  |
| CALL_BUILTIN_O | 13,550,625 | 0.1% | 97.7% | 7.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,598,680 | 0.1% | 97.8% |  |
| LOAD_ATTR_CLASS | 11,177,660 | 0.1% | 98.0% | 2.5% |
| UNPACK_SEQUENCE_LIST | 10,970,400 | 0.1% | 98.1% |  |
| CALL_BUILTIN_FAST | 10,577,568 | 0.1% | 98.1% |  |
| STORE_ATTR | 9,289,120 | 0.1% | 98.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 9,118,560 | 0.1% | 98.3% |  |
| CALL_TYPE_1 | 8,649,840 | 0.1% | 98.4% |  |
| DELETE_ATTR | 8,440,800 | 0.1% | 98.5% |  |
| YIELD_VALUE | 8,405,508 | 0.1% | 98.6% |  |
| BUILD_MAP | 8,335,920 | 0.1% | 98.6% |  |
| TO_BOOL_STR | 6,950,860 | 0.1% | 98.7% | 3.9% |
| STORE_FAST_LOAD_FAST | 6,520,660 | 0.1% | 98.8% |  |
| MAKE_FUNCTION | 6,415,040 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_TUPLE_INT | 5,980,800 | 0.1% | 98.9% |  |
| CALL_FUNCTION_EX | 5,974,200 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_INT | 5,861,748 | 0.1% | 99.0% | 0.8% |
| RETURN_GENERATOR | 5,838,480 | 0.1% | 99.0% |  |
| FOR_ITER_RANGE | 5,188,540 | 0.0% | 99.1% |  |
| BINARY_OP_SUBTRACT_INT | 5,188,368 | 0.0% | 99.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 5,001,220 | 0.0% | 99.2% | 0.1% |
| EXIT_INIT_CHECK | 4,994,400 | 0.0% | 99.2% |  |
| BINARY_OP_ADD_UNICODE | 4,993,920 | 0.0% | 99.3% |  |
| BINARY_SLICE | 4,723,200 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 3,957,600 | 0.0% | 99.4% |  |
| STORE_SUBSCR_DICT | 3,919,488 | 0.0% | 99.4% |  |
| BINARY_OP | 3,645,900 | 0.0% | 99.4% |  |
| STORE_DEREF | 3,540,240 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 3,113,760 | 0.0% | 99.5% |  |
| POP_EXCEPT | 3,113,760 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 3,113,760 | 0.0% | 99.5% |  |
| DICT_MERGE | 2,898,000 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,851,020 | 0.0% | 99.6% |  |
| STORE_SUBSCR | 2,823,820 | 0.0% | 99.6% |  |
| CALL_STR_1 | 2,610,480 | 0.0% | 99.6% |  |
| FORMAT_SIMPLE | 2,517,120 | 0.0% | 99.7% |  |
| RERAISE | 2,513,760 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,454,480 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,286,380 | 0.0% | 99.7% | 10.9% |
| CALL_INTRINSIC_1 | 2,250,780 | 0.0% | 99.8% |  |
| LOAD_FAST_CHECK | 2,116,800 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_GETITEM | 2,091,360 | 0.0% | 99.8% | 0.0% |
| BEFORE_WITH | 2,006,700 | 0.0% | 99.8% |  |
| IMPORT_FROM | 1,819,920 | 0.0% | 99.8% |  |
| BUILD_STRING | 1,804,560 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,533,660 | 0.0% | 99.9% |  |
| IMPORT_NAME | 1,487,040 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 1,465,920 | 0.0% | 99.9% |  |
| BUILD_SET | 1,414,560 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 1,405,920 | 0.0% | 99.9% | 4.5% |
| STORE_ATTR_WITH_HINT | 1,233,120 | 0.0% | 99.9% | 3.2% |
| SET_ADD | 1,090,560 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 996,000 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 855,860 | 0.0% | 100.0% | 1.7% |
| BINARY_SUBSCR_STR_INT | 846,960 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 812,400 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 802,320 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 429,600 | 0.0% | 100.0% |  |
| SEND_GEN | 345,348 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 324,240 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 273,348 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 333,653,983 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 291,588,824 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 286,889,184 | 2.7% | 8.4% |
| LOAD_FAST STORE_ATTR_SLOT | 268,738,825 | 2.5% | 10.9% |
| RESUME_CHECK LOAD_FAST | 228,661,404 | 2.1% | 13.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 213,358,282 | 2.0% | 15.0% |
| LOAD_CONST LOAD_FAST | 211,952,940 | 2.0% | 17.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 206,700,780 | 1.9% | 18.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 205,034,523 | 1.9% | 20.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 195,678,941 | 1.8% | 22.6% |
| STORE_FAST LOAD_FAST | 190,077,456 | 1.8% | 24.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 186,557,760 | 1.7% | 26.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 178,403,426 | 1.6% | 27.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 143,167,116 | 1.3% | 29.0% |
| STORE_ATTR_SLOT LOAD_CONST | 126,971,520 | 1.2% | 30.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 126,879,906 | 1.2% | 31.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 124,929,360 | 1.2% | 32.5% |
| LOAD_FAST LOAD_CONST | 123,643,348 | 1.1% | 33.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 106,074,480 | 1.0% | 34.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 100,742,345 | 0.9% | 35.6% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 95,200,672 | 0.9% | 36.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 93,837,000 | 0.9% | 37.4% |
| STORE_ATTR_SLOT RETURN_CONST | 90,707,040 | 0.8% | 38.2% |
| LOAD_FAST RETURN_VALUE | 89,671,360 | 0.8% | 39.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 88,427,560 | 0.8% | 39.8% |
| STORE_ATTR_SLOT LOAD_FAST | 83,717,065 | 0.8% | 40.6% |
| RETURN_CONST POP_TOP | 79,313,760 | 0.7% | 41.3% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 77,369,040 | 0.7% | 42.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 76,278,758 | 0.7% | 42.8% |
| LOAD_CONST BINARY_SUBSCR_DICT | 76,203,360 | 0.7% | 43.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 74,092,488 | 0.7% | 44.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 70,647,660 | 0.7% | 44.8% |
| POP_TOP LOAD_FAST | 70,324,120 | 0.7% | 45.5% |
| COPY_FREE_VARS RESUME_CHECK | 69,822,300 | 0.6% | 46.1% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 69,111,360 | 0.6% | 46.7% |
| RETURN_VALUE STORE_FAST | 67,764,000 | 0.6% | 47.4% |
| LOAD_DEREF LOAD_FAST | 66,314,204 | 0.6% | 48.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 64,604,560 | 0.6% | 48.6% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 64,576,560 | 0.6% | 49.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 60,926,080 | 0.6% | 49.7% |
| RETURN_VALUE RETURN_VALUE | 60,510,100 | 0.6% | 50.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 60,395,860 | 0.6% | 50.9% |
| LOAD_FAST LOAD_FAST | 58,123,776 | 0.5% | 51.4% |
| LOAD_FAST LOAD_ATTR | 56,954,136 | 0.5% | 51.9% |
| LOAD_CONST CALL_KW | 56,656,800 | 0.5% | 52.5% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 55,922,256 | 0.5% | 53.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 55,386,897 | 0.5% | 53.5% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 53,775,840 | 0.5% | 54.0% |
| CACHE RESUME_CHECK | 52,304,070 | 0.5% | 54.5% |
| RESUME_CHECK RETURN_CONST | 50,785,440 | 0.5% | 54.9% |
| RETURN_CONST INTERPRETER_EXIT | 46,489,260 | 0.4% | 55.4% |
| RETURN_CONST LOAD_FAST | 46,216,320 | 0.4% | 55.8% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 45,426,540 | 0.4% | 56.2% |
| LOAD_ATTR_SLOT LOAD_FAST | 45,231,114 | 0.4% | 56.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 44,076,220 | 0.4% | 57.0% |
| LOAD_CONST LOAD_CONST | 40,572,600 | 0.4% | 57.4% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 40,491,840 | 0.4% | 57.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40,073,880 | 0.4% | 58.2% |
| LOAD_ATTR LOAD_FAST | 40,024,668 | 0.4% | 58.5% |
| RETURN_VALUE LOAD_FAST | 37,582,400 | 0.3% | 58.9% |
| FOR_ITER_LIST STORE_FAST | 37,307,169 | 0.3% | 59.2% |
| RETURN_VALUE INTERPRETER_EXIT | 36,942,570 | 0.3% | 59.6% |
| LOAD_ATTR_SLOT STORE_FAST | 36,625,920 | 0.3% | 59.9% |
| LOAD_ATTR_SLOT GET_ITER | 35,968,008 | 0.3% | 60.2% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 35,930,160 | 0.3% | 60.6% |
| LOAD_FAST CONTAINS_OP | 35,678,160 | 0.3% | 60.9% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 35,650,560 | 0.3% | 61.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 35,158,320 | 0.3% | 61.5% |
| GET_ITER FOR_ITER_LIST | 33,957,193 | 0.3% | 61.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,162,060 | 0.3% | 62.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 32,759,440 | 0.3% | 62.5% |
| CACHE COPY_FREE_VARS | 32,616,960 | 0.3% | 62.8% |
| CALL_KW RESUME_CHECK | 32,570,160 | 0.3% | 63.1% |
| RETURN_CONST RETURN_VALUE | 32,131,200 | 0.3% | 63.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 31,593,840 | 0.3% | 63.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 31,352,160 | 0.3% | 64.0% |
| LOAD_GLOBAL_MODULE IS_OP | 31,202,400 | 0.3% | 64.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 30,563,520 | 0.3% | 64.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 29,722,200 | 0.3% | 64.8% |
| COPY TO_BOOL_BOOL | 28,908,900 | 0.3% | 65.1% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 28,860,720 | 0.3% | 65.3% |
| IS_OP POP_JUMP_IF_FALSE | 28,561,440 | 0.3% | 65.6% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 28,113,760 | 0.3% | 65.9% |
| LOAD_CONST COMPARE_OP_STR | 27,996,628 | 0.3% | 66.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 27,463,920 | 0.3% | 66.4% |
| LOAD_ATTR_SLOT RETURN_VALUE | 27,349,893 | 0.3% | 66.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 27,186,480 | 0.3% | 66.9% |
| POP_TOP LOAD_FAST_LOAD_FAST | 26,461,260 | 0.2% | 67.1% |
| LOAD_FAST TO_BOOL_LIST | 26,193,400 | 0.2% | 67.4% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 26,074,480 | 0.2% | 67.6% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 26,046,281 | 0.2% | 67.8% |
| RETURN_VALUE POP_TOP | 25,899,120 | 0.2% | 68.1% |
| LOAD_FAST TO_BOOL_BOOL | 25,686,000 | 0.2% | 68.3% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 25,332,960 | 0.2% | 68.6% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 24,543,840 | 0.2% | 68.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 24,383,580 | 0.2% | 69.0% |
| BUILD_LIST STORE_FAST | 24,350,460 | 0.2% | 69.2% |
| LOAD_ATTR_SLOT LOAD_GLOBAL_MODULE | 23,832,720 | 0.2% | 69.5% |
| STORE_ATTR_SLOT LOAD_GLOBAL_BUILTIN | 23,764,560 | 0.2% | 69.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 23,350,080 | 0.2% | 69.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,650,880 | 77.3% |
| BINARY_OP_SUBTRACT_INT | 667,680 | 14.1% |
| LOAD_FAST | 300,000 | 6.4% |
| BINARY_OP_ADD_INT | 76,080 | 1.6% |
| LOAD_ATTR_SLOT | 18,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,754,640 | 37.1% |
| CALL_PY_EXACT_ARGS | 668,160 | 14.1% |
| STORE_FAST | 525,120 | 11.1% |
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
| RESUME_CHECK | 52,304,070 | 56.3% |
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
| LOAD_CONST | 14,977,884 | 49.3% |
| LOAD_FAST_LOAD_FAST | 11,280,480 | 37.1% |
| LOAD_FAST | 2,716,560 | 8.9% |
| LOAD_GLOBAL_MODULE | 899,520 | 3.0% |
| COPY | 215,520 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,883,920 | 42.4% |
| CONTAINS_OP | 3,348,480 | 11.0% |
| LOAD_CONST | 3,315,600 | 10.9% |
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
| LOAD_FAST | 1,896,480 | 75.3% |
| RETURN_VALUE | 310,080 | 12.3% |
| BINARY_SUBSCR_TUPLE_INT | 211,200 | 8.4% |
| CONVERT_VALUE | 50,880 | 2.0% |
| LOAD_ATTR_SLOT | 29,040 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,741,920 | 69.2% |
| BUILD_STRING | 775,200 | 30.8% |


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
| LOAD_ATTR_SLOT | 35,968,008 | 39.4% |
| LOAD_FAST | 21,682,880 | 23.8% |
| CALL_BUILTIN_CLASS | 14,308,140 | 15.7% |
| BINARY_SUBSCR_DICT | 9,363,600 | 10.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,015,280 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 33,957,193 | 37.2% |
| LOAD_FAST_AND_CLEAR | 19,966,560 | 21.9% |
| FOR_ITER_TUPLE | 14,370,422 | 15.7% |
| FOR_ITER | 10,938,633 | 12.0% |
| FOR_ITER_RANGE | 4,479,900 | 4.9% |


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
| RETURN_VALUE | 36,942,570 | 40.7% |
| YIELD_VALUE | 7,176,720 | 7.9% |
| RETURN_GENERATOR | 70,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,415,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,279,920 | 51.1% |
| SET_FUNCTION_ATTRIBUTE | 3,078,960 | 48.0% |
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
| POP_JUMP_IF_TRUE | 10,561,920 | 26.4% |
| POP_JUMP_IF_FALSE | 6,881,520 | 17.2% |
| RESUME_CHECK | 4,857,360 | 12.2% |
| CALL_LIST_APPEND | 1,826,400 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,493,840 | 56.3% |
| LOAD_CONST | 11,083,200 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 3,558,880 | 8.9% |
| LOAD_GLOBAL_MODULE | 2,290,560 | 5.7% |
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
| RETURN_CONST | 79,313,760 | 47.9% |
| RETURN_VALUE | 25,899,120 | 15.6% |
| POP_JUMP_IF_FALSE | 15,519,736 | 9.4% |
| POP_JUMP_IF_TRUE | 13,015,776 | 7.9% |
| RESUME_CHECK | 5,994,000 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,324,120 | 42.5% |
| LOAD_FAST_LOAD_FAST | 26,461,260 | 16.0% |
| ENTER_EXECUTOR | 19,398,204 | 11.7% |
| RETURN_CONST | 17,265,600 | 10.4% |
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
| LOAD_FAST | 14,712,288 | 50.3% |
| LOAD_ATTR | 6,303,620 | 21.5% |
| LOAD_ATTR_MODULE | 5,400,820 | 18.5% |
| BINARY_SUBSCR_DICT | 1,110,720 | 3.8% |
| LOAD_SUPER_ATTR_ATTR | 808,080 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,449,288 | 76.7% |
| LOAD_FAST_LOAD_FAST | 4,218,960 | 14.4% |
| LOAD_GLOBAL_BUILTIN | 1,836,720 | 6.3% |
| CALL | 440,520 | 1.5% |
| LOAD_CONST | 209,760 | 0.7% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,329,120 | 57.0% |
| CALL_FUNCTION_EX | 1,711,440 | 29.3% |
| COPY_FREE_VARS | 725,040 | 12.4% |
| CACHE | 70,080 | 1.2% |
| MAKE_CELL | 1,920 | 0.0% |

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
| LOAD_FAST | 89,671,360 | 30.1% |
| RETURN_VALUE | 60,510,100 | 20.3% |
| RETURN_CONST | 32,131,200 | 10.8% |
| LOAD_ATTR_SLOT | 27,349,893 | 9.2% |
| CALL | 9,479,520 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 67,764,000 | 22.7% |
| RETURN_VALUE | 60,510,100 | 20.3% |
| LOAD_FAST | 37,582,400 | 12.6% |
| INTERPRETER_EXIT | 36,942,570 | 12.4% |
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
| LOAD_ATTR_SLOT | 2,026,320 | 13.3% |
| COPY | 809,460 | 5.3% |
| LOAD_ATTR_WITH_HINT | 53,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,786,260 | 84.0% |
| POP_JUMP_IF_TRUE | 2,157,960 | 14.2% |
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
| LOAD_FAST | 760,320 | 51.9% |
| CALL_LEN | 667,920 | 45.6% |
| LOAD_GLOBAL_MODULE | 17,760 | 1.2% |
| CALL | 12,960 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 6,960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 667,680 | 45.5% |
| COMPARE_OP_INT | 667,680 | 45.5% |
| CALL_PY_EXACT_ARGS | 64,800 | 4.4% |
| RETURN_VALUE | 19,920 | 1.4% |
| BUILD_TUPLE | 17,760 | 1.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,368,800 | 87.4% |
| TO_BOOL_LIST | 1,893,840 | 9.5% |
| TO_BOOL_STR | 277,200 | 1.4% |
| TO_BOOL | 220,620 | 1.1% |
| TO_BOOL_INT | 104,160 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,516,080 | 52.9% |
| RETURN_VALUE | 6,898,080 | 34.7% |
| COPY | 1,927,440 | 9.7% |
| LOAD_FAST | 342,720 | 1.7% |
| STORE_FAST | 114,240 | 0.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,983,120 | 54.4% |
| LOAD_FAST | 379,440 | 10.4% |
| BUILD_LIST | 297,600 | 8.2% |
| STORE_FAST | 259,920 | 7.1% |
| LOAD_CONST | 179,040 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,424,880 | 39.1% |
| STORE_FAST | 911,760 | 25.0% |
| CALL_PY_EXACT_ARGS | 381,120 | 10.5% |
| LOAD_CONST | 215,520 | 5.9% |
| GET_ITER | 157,920 | 4.3% |


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
| SWAP | 18,160,320 | 28.6% |
| STORE_FAST | 13,910,460 | 21.9% |
| LOAD_GLOBAL_MODULE | 9,092,400 | 14.3% |
| RESUME_CHECK | 6,518,160 | 10.3% |
| STORE_ATTR_SLOT | 3,159,120 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,350,460 | 38.4% |
| SWAP | 18,160,320 | 28.6% |
| CALL | 9,368,160 | 14.8% |
| LOAD_FAST | 6,086,640 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 1,903,920 | 3.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,078,960 | 36.9% |
| LOAD_CONST | 1,249,680 | 15.0% |
| STORE_ATTR_INSTANCE_VALUE | 720,720 | 8.6% |
| RESUME_CHECK | 696,960 | 8.4% |
| POP_JUMP_IF_FALSE | 597,360 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,765,200 | 57.2% |
| LOAD_CONST | 1,208,640 | 14.5% |
| STORE_FAST | 1,145,520 | 13.7% |
| SWAP | 490,560 | 5.9% |
| RETURN_VALUE | 203,520 | 2.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,315,680 | 93.0% |
| LOAD_CONST | 82,320 | 5.8% |
| LOAD_FAST | 16,320 | 1.2% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,315,680 | 93.0% |
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
| LOAD_CONST | 998,400 | 55.3% |
| FORMAT_SIMPLE | 775,200 | 43.0% |
| ENTER_EXECUTOR | 30,960 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 711,840 | 39.4% |
| STORE_FAST | 420,000 | 23.3% |
| RETURN_VALUE | 282,480 | 15.7% |
| LOAD_FAST | 125,520 | 7.0% |
| CALL_PY_EXACT_ARGS | 64,080 | 3.6% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,433,360 | 35.0% |
| LOAD_GLOBAL_MODULE | 3,917,780 | 16.2% |
| LOAD_ATTR_SLOT | 3,832,345 | 15.9% |
| LOAD_FAST_LOAD_FAST | 3,263,580 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,775,280 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,233,580 | 25.8% |
| CALL_BUILTIN_O | 4,252,549 | 17.6% |
| CALL_ISINSTANCE | 3,398,880 | 14.1% |
| LOAD_CONST | 3,080,160 | 12.8% |
| LOAD_FAST | 2,666,880 | 11.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,623,120 | 18.7% |
| BUILD_LIST | 9,368,160 | 18.2% |
| LOAD_FAST_LOAD_FAST | 5,209,440 | 10.1% |
| RETURN_VALUE | 4,693,920 | 9.1% |
| LOAD_ATTR_SLOT | 3,396,240 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,394,960 | 39.7% |
| RETURN_VALUE | 9,479,520 | 18.4% |
| LIST_APPEND | 5,271,360 | 10.3% |
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
| LOAD_CONST | 56,656,800 | 98.7% |
| ENTER_EXECUTOR | 722,160 | 1.3% |

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
| LOAD_ATTR_SLOT | 13,690,765 | 42.4% |
| LOAD_GLOBAL_MODULE | 6,483,840 | 20.1% |
| LOAD_CONST | 5,876,866 | 18.2% |
| LOAD_ATTR_MODULE | 2,470,320 | 7.7% |
| LOAD_FAST | 1,627,680 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 12,664,412 | 39.2% |
| POP_JUMP_IF_FALSE | 10,266,026 | 31.8% |
| RETURN_VALUE | 6,305,093 | 19.5% |
| POP_JUMP_IF_TRUE | 2,100,480 | 6.5% |
| EXTENDED_ARG | 771,840 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,678,160 | 49.5% |
| LOAD_FAST_LOAD_FAST | 13,675,760 | 19.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,228,720 | 8.6% |
| LOAD_ATTR_SLOT | 4,057,440 | 5.6% |
| BINARY_SUBSCR | 3,348,480 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60,395,860 | 83.7% |
| POP_JUMP_IF_TRUE | 8,977,304 | 12.4% |
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
| COMPARE_OP | 12,664,412 | 33.2% |
| LOAD_FAST | 4,668,000 | 12.2% |
| CALL_ISINSTANCE | 3,210,720 | 8.4% |
| SWAP | 2,694,240 | 7.1% |
| COMPARE_OP_STR | 2,321,652 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 28,908,900 | 75.8% |
| COMPARE_OP_INT | 2,685,360 | 7.0% |
| TO_BOOL_NONE | 1,353,340 | 3.5% |
| TO_BOOL_STR | 1,129,920 | 3.0% |
| TO_BOOL | 809,460 | 2.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,650,560 | 50.5% |
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
| POP_JUMP_IF_TRUE | 22,844,232 | 27.2% |
| LIST_APPEND | 21,279,360 | 25.3% |
| POP_TOP | 19,398,204 | 23.1% |
| CALL_LIST_APPEND | 6,655,620 | 7.9% |
| POP_JUMP_IF_FALSE | 4,168,004 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,250,620 | 24.1% |
| LOAD_ATTR_METHOD_NO_DICT | 12,174,652 | 14.5% |
| RETURN_CONST | 9,391,828 | 11.2% |
| LOAD_ATTR_SLOT | 8,610,560 | 10.3% |
| SWAP | 8,338,080 | 9.9% |


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
| FOR_ITER | 4,750,080 | 19.0% |
| ENTER_EXECUTOR | 3,340,760 | 13.4% |
| POP_JUMP_IF_NONE | 1,827,600 | 7.3% |
| JUMP_BACKWARD | 1,604,920 | 6.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 12,057,600 | 42.4% |
| GET_ITER | 10,938,633 | 38.5% |
| EXTENDED_ARG | 4,750,080 | 16.7% |
| SWAP | 545,040 | 1.9% |
| LOAD_FAST | 60,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 10,369,440 | 36.5% |
| STORE_FAST | 4,445,408 | 15.6% |
| RETURN_CONST | 4,202,400 | 14.8% |
| LOAD_FAST | 3,526,327 | 12.4% |
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
| LOAD_CONST | 5,395,200 | 12.6% |
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
| POP_JUMP_IF_TRUE | 3,290,984 | 21.3% |
| STORE_SUBSCR | 2,273,760 | 14.7% |
| POP_JUMP_IF_NOT_NONE | 1,913,400 | 12.4% |
| EXTENDED_ARG | 1,604,920 | 10.4% |
| MAP_ADD | 1,354,800 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 12,057,600 | 77.9% |
| EXTENDED_ARG | 2,398,960 | 15.5% |
| FOR_ITER_GEN | 923,280 | 6.0% |
| LOAD_FAST | 78,500 | 0.5% |
| FOR_ITER_LIST | 14,840 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 273,348 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 273,348 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 10,513,680 | 29.6% |
| LOAD_ATTR_SLOT | 10,230,720 | 28.8% |
| LOAD_FAST | 4,954,080 | 14.0% |
| STORE_ATTR_SLOT | 4,130,400 | 11.6% |
| STORE_FAST | 2,908,320 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,702,880 | 49.9% |
| STORE_FAST | 10,936,080 | 30.8% |
| MAP_ADD | 4,706,640 | 13.3% |
| LOAD_CONST | 769,920 | 2.2% |
| LOAD_GLOBAL_MODULE | 719,040 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,616,960 | 54.4% |
| CALL | 5,271,360 | 24.7% |
| CALL_BUILTIN_O | 1,836,480 | 8.6% |
| LOAD_FAST | 1,272,000 | 6.0% |
| LOAD_ATTR_SLOT | 426,000 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 21,279,360 | 99.7% |
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
| LOAD_FAST | 56,954,136 | 65.7% |
| LOAD_GLOBAL_MODULE | 22,950,780 | 26.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,967,520 | 2.3% |
| LOAD_FAST_LOAD_FAST | 1,535,040 | 1.8% |
| CALL_TYPE_1 | 1,082,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,024,668 | 46.1% |
| LOAD_FAST_LOAD_FAST | 8,314,320 | 9.6% |
| TO_BOOL | 7,044,460 | 8.1% |
| PUSH_NULL | 6,303,620 | 7.3% |
| CALL_PY_EXACT_ARGS | 5,125,020 | 5.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 126,971,520 | 23.5% |
| LOAD_FAST | 123,643,348 | 22.9% |
| LOAD_CONST | 40,572,600 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 20,957,300 | 3.9% |
| MAP_ADD | 20,542,800 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 211,952,940 | 39.3% |
| BINARY_SUBSCR_DICT | 76,203,360 | 14.1% |
| CALL_KW | 56,656,800 | 10.5% |
| LOAD_CONST | 40,572,600 | 7.5% |
| COMPARE_OP_STR | 27,996,628 | 5.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 69,111,360 | 70.8% |
| LOAD_DEREF | 9,723,360 | 10.0% |
| LOAD_FAST | 4,163,384 | 4.3% |
| LOAD_GLOBAL_MODULE | 3,757,520 | 3.9% |
| POP_JUMP_IF_FALSE | 1,953,876 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,314,204 | 68.0% |
| LOAD_DEREF | 9,723,360 | 10.0% |
| LOAD_ATTR_SLOT | 5,834,880 | 6.0% |
| LOAD_CONST | 3,234,204 | 3.3% |
| LOAD_FAST_LOAD_FAST | 2,728,560 | 2.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 291,588,824 | 13.1% |
| RESUME_CHECK | 228,661,404 | 10.2% |
| LOAD_CONST | 211,952,940 | 9.5% |
| POP_JUMP_IF_FALSE | 195,678,941 | 8.8% |
| STORE_FAST | 190,077,456 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 333,653,983 | 14.9% |
| STORE_ATTR_SLOT | 268,738,825 | 12.0% |
| LOAD_GLOBAL_MODULE | 205,034,523 | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 143,167,116 | 6.4% |
| CALL_PY_EXACT_ARGS | 124,929,360 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,966,560 | 95.5% |
| LOAD_FAST_AND_CLEAR | 940,800 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 19,958,400 | 95.5% |
| LOAD_FAST_AND_CLEAR | 940,800 | 4.5% |
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
| STORE_ATTR_SLOT | 106,074,480 | 24.6% |
| LOAD_SUPER_ATTR_METHOD | 53,775,840 | 12.5% |
| RESUME_CHECK | 45,426,540 | 10.5% |
| LOAD_GLOBAL_MODULE | 35,158,320 | 8.1% |
| STORE_FAST | 31,593,840 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 186,557,760 | 43.2% |
| CALL_PY_EXACT_ARGS | 77,369,040 | 17.9% |
| STORE_ATTR_INSTANCE_VALUE | 33,162,060 | 7.7% |
| LOAD_FAST | 29,722,200 | 6.9% |
| CONTAINS_OP | 13,675,760 | 3.2% |


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
| CALL_PY_EXACT_ARGS | 3,698,160 | 14.8% |
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
| ENTER_EXECUTOR | 21,840 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 213,358,282 | 50.8% |
| CONTAINS_OP | 60,395,860 | 14.4% |
| IS_OP | 28,561,440 | 6.8% |
| COMPARE_OP_INT | 19,389,030 | 4.6% |
| TO_BOOL_ALWAYS_TRUE | 18,947,340 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 195,678,941 | 46.6% |
| LOAD_GLOBAL_BUILTIN | 100,742,345 | 24.0% |
| LOAD_GLOBAL_MODULE | 35,930,160 | 8.6% |
| LOAD_FAST_LOAD_FAST | 23,350,080 | 5.6% |
| POP_TOP | 15,519,736 | 3.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,759,440 | 50.3% |
| LOAD_ATTR_SLOT | 24,543,840 | 37.7% |
| LOAD_ATTR | 3,174,480 | 4.9% |
| EXTENDED_ARG | 1,827,600 | 2.8% |
| BINARY_SUBSCR_DICT | 1,569,360 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,352,160 | 48.2% |
| RETURN_CONST | 11,897,520 | 18.3% |
| JUMP_FORWARD | 10,513,680 | 16.2% |
| LOAD_GLOBAL_BUILTIN | 3,981,520 | 6.1% |
| LOAD_CONST | 3,881,040 | 6.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,604,560 | 87.8% |
| LOAD_ATTR_SLOT | 3,667,680 | 5.0% |
| BINARY_SUBSCR_DICT | 2,963,040 | 4.0% |
| LOAD_FAST_CHECK | 1,506,240 | 2.0% |
| BINARY_SUBSCR | 223,440 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 28,113,760 | 38.2% |
| LOAD_FAST | 15,314,400 | 20.8% |
| LOAD_CONST | 10,569,840 | 14.4% |
| LOAD_FAST_LOAD_FAST | 8,035,920 | 10.9% |
| RETURN_CONST | 3,494,160 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 76,278,758 | 44.8% |
| TO_BOOL_LIST | 26,074,480 | 15.3% |
| COMPARE_OP_STR | 22,562,496 | 13.3% |
| CONTAINS_OP | 8,977,304 | 5.3% |
| COMPARE_OP_INT | 8,871,324 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,092,488 | 43.5% |
| ENTER_EXECUTOR | 22,844,232 | 13.4% |
| LOAD_GLOBAL_MODULE | 18,739,920 | 11.0% |
| POP_TOP | 13,015,776 | 7.6% |
| NOP | 10,561,920 | 6.2% |


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
| POP_TOP | 17,265,600 | 7.7% |
| POP_JUMP_IF_FALSE | 13,493,520 | 6.0% |
| POP_JUMP_IF_NONE | 11,897,520 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 79,313,760 | 35.2% |
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
| BINARY_OP_ADD_UNICODE | 959,760 | 88.0% |
| STORE_FAST_LOAD_FAST | 48,000 | 4.4% |
| LOAD_ATTR_INSTANCE_VALUE | 47,280 | 4.3% |
| BINARY_SUBSCR_LIST_INT | 17,520 | 1.6% |
| LOAD_FAST | 13,200 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,024,560 | 93.9% |
| JUMP_BACKWARD | 66,000 | 6.1% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,078,960 | 77.8% |
| SET_FUNCTION_ATTRIBUTE | 878,640 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,312,320 | 33.2% |
| SET_FUNCTION_ATTRIBUTE | 878,640 | 22.2% |
| STORE_FAST | 766,560 | 19.4% |
| LOAD_FAST | 338,640 | 8.6% |
| LOAD_GLOBAL_MODULE | 332,160 | 8.4% |


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
| STORE_ATTR | 10,360 | 0.1% |
| LOAD_ATTR_SLOT | 6,720 | 0.1% |

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
| RETURN_VALUE | 67,764,000 | 17.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 40,491,840 | 10.6% |
| FOR_ITER_LIST | 37,307,169 | 9.8% |
| LOAD_ATTR_SLOT | 36,625,920 | 9.6% |
| BUILD_LIST | 24,350,460 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 190,077,456 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 55,386,897 | 14.6% |
| LOAD_GLOBAL_MODULE | 44,076,220 | 11.6% |
| LOAD_FAST_LOAD_FAST | 31,593,840 | 8.3% |
| LOAD_CONST | 14,606,400 | 3.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,971,860 | 60.9% |
| FOR_ITER_TUPLE | 1,310,880 | 20.1% |
| FOR_ITER | 986,880 | 15.1% |
| FOR_ITER_RANGE | 251,040 | 3.8% |

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
| UNPACK_SEQUENCE_TWO_TUPLE | 11,719,980 | 47.2% |
| UNPACK_SEQUENCE_LIST | 10,966,080 | 44.1% |
| UNPACK_SEQUENCE_TUPLE | 1,428,300 | 5.7% |
| COPY | 458,160 | 1.8% |
| BINARY_SUBSCR_LIST_INT | 79,200 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,428,220 | 74.1% |
| LOAD_FAST_LOAD_FAST | 2,766,080 | 11.1% |
| STORE_FAST | 1,523,100 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,420,800 | 5.7% |
| LOAD_GLOBAL_MODULE | 276,000 | 1.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 19,958,400 | 30.3% |
| BUILD_LIST | 18,160,320 | 27.6% |
| ENTER_EXECUTOR | 8,338,080 | 12.7% |
| FOR_ITER_LIST | 6,752,720 | 10.3% |
| LOAD_FAST | 3,623,760 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 18,160,320 | 27.6% |
| FOR_ITER_LIST | 16,731,780 | 25.4% |
| STORE_FAST | 16,063,920 | 24.4% |
| COPY | 2,694,240 | 4.1% |
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
| LOAD_ATTR_SLOT | 1,961,280 | 23.3% |
| LOAD_CONST | 1,414,080 | 16.8% |
| ENTER_EXECUTOR | 1,220,500 | 14.5% |
| LOAD_FAST | 856,160 | 10.2% |
| CALL_ISINSTANCE | 601,920 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,176,720 | 85.4% |
| STORE_FAST | 673,200 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 282,240 | 3.4% |
| YIELD_VALUE | 273,348 | 3.3% |


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
| LOAD_CONST | 3,345,408 | 57.1% |
| CALL_LEN | 1,133,760 | 19.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,100,880 | 18.8% |
| LOAD_FAST | 145,920 | 2.5% |
| LOAD_FAST_LOAD_FAST | 133,680 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,370,720 | 40.4% |
| LOAD_FAST | 1,548,480 | 26.4% |
| SWAP | 743,280 | 12.7% |
| LOAD_FAST_LOAD_FAST | 605,760 | 10.3% |
| LOAD_CONST | 160,560 | 2.7% |


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
| LOAD_CONST | 5,011,248 | 96.6% |
| LOAD_FAST | 92,640 | 1.8% |
| CALL_LEN | 73,920 | 1.4% |
| LOAD_FAST_LOAD_FAST | 5,760 | 0.1% |
| LOAD_ATTR_SLOT | 2,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,540,640 | 49.0% |
| CALL_BUILTIN_CLASS | 1,387,440 | 26.7% |
| BINARY_SLICE | 667,680 | 12.9% |
| SWAP | 217,680 | 4.2% |
| BINARY_SUBSCR_LIST_INT | 197,760 | 3.8% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 76,203,360 | 86.0% |
| LOAD_FAST | 6,840,444 | 7.7% |
| BINARY_SUBSCR_DICT | 2,280,480 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 1,366,080 | 1.5% |
| LOAD_DEREF | 1,145,520 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,503,120 | 18.6% |
| STORE_FAST | 15,049,920 | 17.0% |
| LOAD_CONST | 15,027,840 | 17.0% |
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
| LOAD_FAST_LOAD_FAST | 8,206,080 | 42.1% |
| LOAD_CONST | 6,495,120 | 33.3% |
| LOAD_FAST | 4,491,360 | 23.0% |
| BINARY_OP_SUBTRACT_INT | 197,760 | 1.0% |
| BINARY_OP_ADD_INT | 68,160 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,117,040 | 26.2% |
| STORE_FAST | 2,281,440 | 11.7% |
| LOAD_FAST | 2,177,280 | 11.2% |
| LOAD_GLOBAL_MODULE | 1,699,200 | 8.7% |
| BINARY_SUBSCR_DICT | 1,366,080 | 7.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 557,520 | 65.8% |
| LOAD_FAST_LOAD_FAST | 173,280 | 20.5% |
| BINARY_OP_ADD_INT | 88,320 | 10.4% |
| BINARY_OP_SUBTRACT_INT | 27,840 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 472,320 | 55.8% |
| LOAD_FAST | 262,320 | 31.0% |
| CALL_BUILTIN_O | 50,880 | 6.0% |
| LOAD_FAST_LOAD_FAST | 25,440 | 3.0% |
| COMPARE_OP_STR | 25,440 | 3.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,977,440 | 99.9% |
| LOAD_FAST_LOAD_FAST | 3,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,473,200 | 41.4% |
| COMPARE_OP_STR | 2,397,120 | 40.1% |
| LOAD_CONST | 230,880 | 3.9% |
| STORE_FAST | 216,240 | 3.6% |
| FORMAT_SIMPLE | 211,200 | 3.5% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,345,280 | 46.9% |
| LOAD_FAST | 1,370,160 | 27.4% |
| LOAD_GLOBAL_MODULE | 528,720 | 10.6% |
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
| LOAD_FAST | 14,865,600 | 67.5% |
| BINARY_SUBSCR_DICT | 4,840,080 | 22.0% |
| LOAD_CONST | 2,020,320 | 9.2% |
| CALL_PY_EXACT_ARGS | 79,680 | 0.4% |
| RETURN_VALUE | 70,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,922,540 | 90.5% |
| POP_TOP | 1,969,920 | 9.0% |
| CALL_PY_EXACT_ARGS | 79,700 | 0.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 37,660 | 0.2% |
| COPY_FREE_VARS | 240 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,928,100 | 29.7% |
| LOAD_GLOBAL_BUILTIN | 5,352,960 | 17.8% |
| LOAD_ATTR_SLOT | 3,370,768 | 11.2% |
| LOAD_ATTR_CLASS | 2,841,840 | 9.5% |
| CALL_LEN | 2,305,440 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,308,140 | 47.6% |
| LOAD_FAST | 7,887,840 | 26.2% |
| STORE_FAST | 2,811,120 | 9.4% |
| RETURN_VALUE | 1,873,200 | 6.2% |
| MAP_ADD | 1,255,920 | 4.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,454,688 | 42.1% |
| LOAD_ATTR_INSTANCE_VALUE | 3,502,320 | 33.1% |
| LOAD_FAST_LOAD_FAST | 1,979,040 | 18.7% |
| LOAD_FAST | 498,720 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 67,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,172,240 | 20.5% |
| RETURN_VALUE | 1,744,320 | 16.5% |
| PUSH_EXC_INFO | 1,715,040 | 16.2% |
| POP_TOP | 1,585,680 | 15.0% |
| TO_BOOL_BOOL | 1,530,240 | 14.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,417,760 | 84.8% |
| RETURN_GENERATOR | 289,440 | 10.2% |
| CALL_BUILTIN_CLASS | 106,320 | 3.7% |
| RETURN_VALUE | 36,000 | 1.3% |
| LOAD_CONST | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,968,480 | 69.0% |
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
| BUILD_TUPLE | 4,252,549 | 31.4% |
| RETURN_GENERATOR | 3,563,280 | 26.3% |
| CALL_STR_1 | 1,836,480 | 13.6% |
| LOAD_FAST | 1,587,600 | 11.7% |
| LOAD_GLOBAL_MODULE | 901,140 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,230,480 | 38.6% |
| LOAD_FAST | 3,717,385 | 27.4% |
| LIST_APPEND | 1,836,480 | 13.6% |
| TO_BOOL_BOOL | 1,276,560 | 9.4% |
| CALL_PY_EXACT_ARGS | 678,480 | 5.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 178,403,426 | 84.4% |
| LOAD_GLOBAL_BUILTIN | 27,186,480 | 12.9% |
| BUILD_TUPLE | 3,398,880 | 1.6% |
| LOAD_ATTR | 1,421,520 | 0.7% |
| LOAD_ATTR_MODULE | 772,800 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 206,700,780 | 97.8% |
| COPY | 3,210,720 | 1.5% |
| YIELD_VALUE | 601,920 | 0.3% |
| RETURN_VALUE | 557,846 | 0.3% |
| STORE_FAST | 297,120 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,476,180 | 57.3% |
| LOAD_ATTR_SLOT | 8,321,520 | 30.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,426,800 | 5.3% |
| LOAD_DEREF | 1,425,600 | 5.3% |
| LOAD_ATTR | 163,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,378,820 | 27.3% |
| COMPARE_OP_INT | 4,478,160 | 16.6% |
| LOAD_GLOBAL_BUILTIN | 3,425,520 | 12.7% |
| SWAP | 2,685,360 | 9.9% |
| CALL_BUILTIN_CLASS | 2,305,440 | 8.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,788,600 | 82.1% |
| RETURN_VALUE | 1,977,360 | 8.2% |
| LOAD_CONST | 426,000 | 1.8% |
| BUILD_TUPLE | 415,920 | 1.7% |
| BUILD_LIST | 366,240 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,146,000 | 54.5% |
| ENTER_EXECUTOR | 6,655,620 | 27.6% |
| NOP | 1,826,400 | 7.6% |
| EXTENDED_ARG | 512,400 | 2.1% |
| LOAD_CONST | 510,780 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,860,720 | 55.8% |
| LOAD_ATTR_METHOD_NO_DICT | 17,719,200 | 34.2% |
| LOAD_CONST | 2,195,040 | 4.2% |
| LOAD_GLOBAL_MODULE | 1,039,680 | 2.0% |
| CALL_BUILTIN_CLASS | 549,600 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40,491,840 | 78.2% |
| POP_TOP | 3,562,320 | 6.9% |
| LOAD_CONST | 2,832,480 | 5.5% |
| LOAD_FAST | 2,100,000 | 4.1% |
| CALL_PY_EXACT_ARGS | 729,840 | 1.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,225,040 | 90.7% |
| LOAD_FAST | 140,640 | 5.7% |
| LOAD_ATTR_MODULE | 69,360 | 2.8% |
| LOAD_ATTR_METHOD_NO_DICT | 19,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,712,160 | 69.8% |
| LOAD_CONST | 292,080 | 11.9% |
| UNPACK_SEQUENCE_LIST | 145,680 | 5.9% |
| GET_ITER | 141,360 | 5.8% |
| CONTAINS_OP | 69,360 | 2.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,277,120 | 99.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,700 | 0.2% |
| LOAD_ATTR | 4,320 | 0.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,301,520 | 56.9% |
| LOAD_FAST | 431,280 | 18.9% |
| POP_TOP | 240,720 | 10.5% |
| CALL_BUILTIN_CLASS | 180,000 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 67,200 | 2.9% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,887,600 | 53.6% |
| LOAD_FAST | 2,990,880 | 32.8% |
| RETURN_VALUE | 474,240 | 5.2% |
| LOAD_ATTR_SLOT | 193,200 | 2.1% |
| BUILD_TUPLE | 182,400 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,808,320 | 41.8% |
| POP_TOP | 3,259,440 | 35.7% |
| BINARY_OP_ADD_INT | 1,100,880 | 12.1% |
| BINARY_OP_ADD_UNICODE | 738,480 | 8.1% |
| STORE_FAST | 149,280 | 1.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,929,360 | 37.8% |
| LOAD_FAST_LOAD_FAST | 77,369,040 | 23.4% |
| LOAD_ATTR_METHOD_NO_DICT | 55,922,256 | 16.9% |
| LOAD_ATTR_SLOT | 10,990,160 | 3.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,697,120 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 286,889,184 | 86.8% |
| COPY_FREE_VARS | 35,650,560 | 10.8% |
| MAKE_CELL | 3,698,160 | 1.1% |
| RETURN_GENERATOR | 3,329,120 | 1.0% |
| CALL_PY_EXACT_ARGS | 547,805 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 5,951,040 | 38.3% |
| LOAD_FAST | 5,227,200 | 33.6% |
| LOAD_FAST_LOAD_FAST | 1,382,160 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 946,560 | 6.1% |
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
| LOAD_ATTR_SLOT | 1,098,684 | 7.2% |
| RETURN_VALUE | 16,800 | 0.1% |
| LOAD_FAST_CHECK | 14,640 | 0.1% |
| RETURN_GENERATOR | 5,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,220,000 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 571,920 | 3.8% |
| BUILD_TUPLE | 398,364 | 2.6% |
| CALL_PY_EXACT_ARGS | 25,200 | 0.2% |
| RETURN_VALUE | 18,000 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,649,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,212,320 | 60.3% |
| STORE_FAST | 1,470,480 | 17.0% |
| LOAD_ATTR | 1,082,880 | 12.5% |
| PUSH_NULL | 667,680 | 7.7% |
| LOAD_GLOBAL_MODULE | 90,000 | 1.0% |


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
| LOAD_CONST | 13,746,170 | 43.5% |
| CALL_LEN | 4,478,160 | 14.2% |
| LOAD_GLOBAL_MODULE | 2,694,960 | 8.5% |
| COPY | 2,685,360 | 8.5% |
| LOAD_ATTR_CLASS | 2,666,400 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,389,030 | 61.4% |
| POP_JUMP_IF_TRUE | 8,871,324 | 28.1% |
| COPY | 1,579,468 | 5.0% |
| RETURN_VALUE | 957,281 | 3.0% |
| EXTENDED_ARG | 470,400 | 1.5% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,996,628 | 70.6% |
| LOAD_FAST | 6,797,856 | 17.1% |
| BINARY_SUBSCR_TUPLE_INT | 2,397,120 | 6.0% |
| RETURN_VALUE | 718,500 | 1.8% |
| LOAD_ATTR_INSTANCE_VALUE | 625,574 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 22,562,496 | 56.9% |
| POP_JUMP_IF_FALSE | 13,192,300 | 33.3% |
| COPY | 2,321,652 | 5.9% |
| RETURN_VALUE | 923,268 | 2.3% |
| EXTENDED_ARG | 582,000 | 1.5% |


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
| GET_ITER | 33,957,193 | 60.0% |
| SWAP | 16,731,780 | 29.6% |
| LOAD_FAST | 3,875,520 | 6.8% |
| EXTENDED_ARG | 1,092,400 | 1.9% |
| ENTER_EXECUTOR | 906,193 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 37,307,169 | 65.9% |
| SWAP | 6,752,720 | 11.9% |
| LOAD_FAST | 4,319,313 | 7.6% |
| STORE_FAST_LOAD_FAST | 3,971,860 | 7.0% |
| RETURN_CONST | 2,555,880 | 4.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,479,900 | 86.3% |
| SWAP | 620,160 | 12.0% |
| EXTENDED_ARG | 87,600 | 1.7% |
| JUMP_BACKWARD | 880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,933,120 | 37.3% |
| LOAD_FAST | 1,430,940 | 27.6% |
| RETURN_CONST | 1,080,240 | 20.8% |
| LOAD_GLOBAL_MODULE | 493,200 | 9.5% |
| STORE_FAST_LOAD_FAST | 251,040 | 4.8% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,370,422 | 82.7% |
| SWAP | 2,069,580 | 11.9% |
| ENTER_EXECUTOR | 877,999 | 5.1% |
| EXTENDED_ARG | 25,920 | 0.1% |
| FOR_ITER_LIST | 23,331 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,260,616 | 59.0% |
| STORE_FAST | 5,030,028 | 28.9% |
| STORE_FAST_LOAD_FAST | 1,310,880 | 7.5% |
| SWAP | 531,040 | 3.1% |
| RETURN_CONST | 223,340 | 1.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,899,280 | 88.6% |
| LOAD_FAST | 1,158,240 | 10.4% |
| COPY | 79,200 | 0.7% |
| ENTER_EXECUTOR | 33,840 | 0.3% |
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
| LOAD_FAST | 95,200,672 | 80.4% |
| LOAD_FAST_LOAD_FAST | 10,080,060 | 8.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,462,520 | 3.8% |
| LOAD_GLOBAL_MODULE | 3,131,760 | 2.6% |
| LOAD_DEREF | 1,380,480 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,488,374 | 19.0% |
| LOAD_CONST | 20,957,300 | 17.7% |
| LOAD_ATTR_METHOD_NO_DICT | 11,133,600 | 9.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,776,160 | 8.3% |
| CONTAINS_OP | 6,228,720 | 5.3% |


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
| LOAD_FAST | 143,167,116 | 69.0% |
| LOAD_ATTR_SLOT | 22,902,648 | 11.0% |
| ENTER_EXECUTOR | 12,174,652 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 11,133,600 | 5.4% |
| LOAD_GLOBAL_MODULE | 7,435,680 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,837,000 | 45.2% |
| CALL_PY_EXACT_ARGS | 55,922,256 | 26.9% |
| LOAD_CONST | 19,657,608 | 9.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 17,719,200 | 8.5% |
| LOAD_GLOBAL_MODULE | 14,253,160 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,647,660 | 81.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,776,160 | 11.2% |
| LOAD_DEREF | 1,925,760 | 2.2% |
| ENTER_EXECUTOR | 1,175,380 | 1.3% |
| LOAD_ATTR_WITH_HINT | 1,020,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,926,080 | 69.9% |
| LOAD_FAST_LOAD_FAST | 12,052,800 | 13.8% |
| CALL_PY_EXACT_ARGS | 8,697,120 | 10.0% |
| LOAD_CONST | 2,031,360 | 2.3% |
| LOAD_DEREF | 1,595,280 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,165,757 | 60.2% |
| LOAD_ATTR_MODULE | 4,548,480 | 20.8% |
| ENTER_EXECUTOR | 1,907,783 | 8.7% |
| LOAD_ATTR_CLASS | 1,158,240 | 5.3% |
| LOAD_FAST_LOAD_FAST | 926,400 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,400,820 | 24.7% |
| LOAD_ATTR_MODULE | 4,548,480 | 20.8% |
| LOAD_FAST | 3,214,560 | 14.7% |
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
| LOAD_FAST | 11,459,712 | 55.9% |
| LOAD_ATTR_SLOT | 5,095,228 | 24.8% |
| ENTER_EXECUTOR | 3,341,448 | 16.3% |
| LOAD_ATTR_INSTANCE_VALUE | 362,160 | 1.8% |
| CALL | 70,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,153,616 | 93.4% |
| RETURN_VALUE | 805,803 | 3.9% |
| STORE_FAST | 181,200 | 0.9% |
| LOAD_FAST | 180,220 | 0.9% |
| LOAD_CONST | 80,000 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 333,653,983 | 86.6% |
| LOAD_ATTR_SLOT | 26,046,281 | 6.8% |
| ENTER_EXECUTOR | 8,610,560 | 2.2% |
| LOAD_DEREF | 5,834,880 | 1.5% |
| LOAD_FAST_LOAD_FAST | 4,917,120 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,231,114 | 11.7% |
| STORE_FAST | 36,625,920 | 9.5% |
| GET_ITER | 35,968,008 | 9.3% |
| RETURN_VALUE | 27,349,893 | 7.1% |
| LOAD_ATTR_SLOT | 26,046,281 | 6.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,262,000 | 57.0% |
| LOAD_FAST_LOAD_FAST | 4,846,560 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,727,280 | 20.3% |
| LOAD_ATTR_WITH_HINT | 376,860 | 1.6% |
| ENTER_EXECUTOR | 31,360 | 0.1% |

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
| RESUME_CHECK | 126,879,906 | 30.3% |
| POP_JUMP_IF_FALSE | 100,742,345 | 24.1% |
| STORE_FAST | 55,386,897 | 13.2% |
| LOAD_FAST | 30,563,520 | 7.3% |
| POP_JUMP_IF_NOT_NONE | 28,113,760 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 291,588,824 | 69.7% |
| LOAD_DEREF | 69,111,360 | 16.5% |
| CALL_ISINSTANCE | 27,186,480 | 6.5% |
| CALL_BUILTIN_CLASS | 5,352,960 | 1.3% |
| LOAD_FAST_LOAD_FAST | 4,896,060 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 205,034,523 | 44.1% |
| STORE_FAST | 44,076,220 | 9.5% |
| RESUME_CHECK | 40,073,880 | 8.6% |
| POP_JUMP_IF_FALSE | 35,930,160 | 7.7% |
| LOAD_GLOBAL_MODULE | 25,332,960 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 178,403,426 | 38.4% |
| LOAD_FAST | 88,427,560 | 19.0% |
| LOAD_FAST_LOAD_FAST | 35,158,320 | 7.6% |
| IS_OP | 31,202,400 | 6.7% |
| LOAD_GLOBAL_MODULE | 25,332,960 | 5.5% |


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
| CALL_PY_EXACT_ARGS | 286,889,184 | 55.1% |
| COPY_FREE_VARS | 69,822,300 | 13.4% |
| CACHE | 52,304,070 | 10.0% |
| CALL_KW | 32,570,160 | 6.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,922,540 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 228,661,404 | 43.9% |
| LOAD_GLOBAL_BUILTIN | 126,879,906 | 24.3% |
| RETURN_CONST | 50,785,440 | 9.7% |
| LOAD_FAST_LOAD_FAST | 45,426,540 | 8.7% |
| LOAD_GLOBAL_MODULE | 40,073,880 | 7.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 273,348 | 79.2% |
| LOAD_CONST | 72,000 | 20.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 273,348 | 79.2% |
| POP_TOP | 72,000 | 20.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 33,162,060 | 56.7% |
| LOAD_FAST | 24,383,580 | 41.7% |
| SWAP | 595,920 | 1.0% |
| BINARY_SUBSCR | 337,200 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 24,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,463,920 | 46.9% |
| RETURN_CONST | 10,268,220 | 17.6% |
| LOAD_FAST | 9,754,560 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 3,851,520 | 6.6% |
| LOAD_GLOBAL_MODULE | 2,751,840 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 268,738,825 | 58.7% |
| LOAD_FAST_LOAD_FAST | 186,557,760 | 40.7% |
| STORE_ATTR_SLOT | 1,863,060 | 0.4% |
| LOAD_ATTR_SLOT | 636,960 | 0.1% |
| LOAD_DEREF | 11,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 126,971,520 | 27.7% |
| LOAD_FAST_LOAD_FAST | 106,074,480 | 23.2% |
| RETURN_CONST | 90,707,040 | 19.8% |
| LOAD_FAST | 83,717,065 | 18.3% |
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
| LOAD_FAST | 2,779,488 | 70.9% |
| LOAD_FAST_LOAD_FAST | 483,600 | 12.3% |
| LOAD_ATTR_SLOT | 307,920 | 7.9% |
| SWAP | 276,000 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 35,520 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,873,200 | 47.8% |
| LOAD_FAST | 732,048 | 18.7% |
| JUMP_BACKWARD | 638,600 | 16.3% |
| ENTER_EXECUTOR | 505,720 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 71,520 | 1.8% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 323,280 | 99.7% |
| LOAD_FAST | 960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 322,800 | 99.6% |
| LOAD_FAST | 960 | 0.3% |
| EXTENDED_ARG | 480 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,629,935 | 75.8% |
| LOAD_ATTR_SLOT | 4,321,180 | 19.7% |
| LOAD_ATTR_INSTANCE_VALUE | 416,520 | 1.9% |
| COPY | 176,420 | 0.8% |
| LOAD_ATTR | 170,160 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,947,340 | 86.4% |
| POP_JUMP_IF_TRUE | 2,190,820 | 10.0% |
| EXTENDED_ARG | 748,900 | 3.4% |
| TO_BOOL_NONE | 28,365 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 25,645 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 206,700,780 | 65.7% |
| COPY | 28,908,900 | 9.2% |
| LOAD_FAST | 25,686,000 | 8.2% |
| RETURN_VALUE | 19,091,620 | 6.1% |
| LOAD_ATTR_SLOT | 9,038,780 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 213,358,282 | 67.8% |
| POP_JUMP_IF_TRUE | 76,278,758 | 24.2% |
| UNARY_NOT | 17,368,800 | 5.5% |
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
| LOAD_FAST | 26,193,400 | 75.4% |
| LOAD_ATTR_SLOT | 5,049,000 | 14.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,946,160 | 5.6% |
| COPY | 666,300 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 294,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,074,480 | 75.1% |
| POP_JUMP_IF_FALSE | 6,172,680 | 17.8% |
| UNARY_NOT | 1,893,840 | 5.5% |
| EXTENDED_ARG | 593,280 | 1.7% |
| TO_BOOL | 3,240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,264,345 | 57.5% |
| LOAD_ATTR_SLOT | 8,362,400 | 31.5% |
| COPY | 1,353,340 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 436,440 | 1.6% |
| LOAD_ATTR_MODULE | 389,280 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,247,700 | 65.0% |
| POP_JUMP_IF_TRUE | 8,674,220 | 32.7% |
| EXTENDED_ARG | 578,300 | 2.2% |
| TO_BOOL_ALWAYS_TRUE | 28,410 | 0.1% |
| UNARY_NOT | 5,700 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,996,260 | 71.9% |
| COPY | 1,129,920 | 16.3% |
| LOAD_ATTR_SLOT | 327,420 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 266,160 | 3.8% |
| STORE_FAST_LOAD_FAST | 140,480 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,075,440 | 58.6% |
| POP_JUMP_IF_TRUE | 2,593,040 | 37.3% |
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
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 145,680 | 1.3% |
| LOAD_FAST | 12,000 | 0.1% |
| LOAD_ATTR_SLOT | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 10,966,080 | 100.0% |
| STORE_FAST | 4,320 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 583,680 | 38.1% |
| YIELD_VALUE | 282,240 | 18.4% |
| STORE_FAST | 280,320 | 18.3% |
| FOR_ITER | 182,400 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 69,840 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,428,300 | 93.1% |
| STORE_FAST | 105,360 | 6.9% |


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
| specialization.deferred |     30385164 | 20.6% |
|          hit |    117068844 | 79.4% |
|         miss |          480 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 10,737 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 5,517 | 51.4% |
| other | 3,760 | 35.0% |
| code complex parameters | 1,340 | 12.5% |
| buffer int | 80 | 0.7% |
| tuple slice | 40 | 0.4% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2822880 | 39.9% |
|          hit |      4243728 | 60.0% |

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
| specialization.deferred |     15192920 | 3.6% |
| specialization.deopt |       104600 | 0.0% |
|          hit |    400862975 | 95.1% |
|         miss |      5550805 | 1.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 104,600 | 76.0% |
| Failure | 33,120 | 24.0% |

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
| specialization.deferred |      3641520 | 17.7% |
| specialization.deopt |         1800 | 0.0% |
|          hit |     16818756 | 81.8% |
|         miss |        95460 | 0.5% |

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
| specialization.deferred |     51382800 | 6.0% |
| specialization.deopt |       863465 | 0.1% |
|          hit |    758867298 | 88.6% |
|         miss |     45850362 | 5.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 863,525 | 95.9% |
| Failure | 37,300 | 4.1% |

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
| specialization.deferred |     32233611 | 31.1% |
| specialization.deopt |        12252 | 0.0% |
|          hit |     70587223 | 68.2% |
|         miss |       648648 | 0.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,212 | 19.8% |
| Failure | 49,504 | 80.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 35,113 | 70.9% |
| baseobject | 4,820 | 9.7% |
| different types | 3,320 | 6.7% |
| bool | 2,091 | 4.2% |
| other | 2,040 | 4.1% |
| tuple | 1,340 | 2.7% |
| list | 640 | 1.3% |
| set | 80 | 0.2% |
| string | 60 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     28393095 | 26.2% |
| specialization.deopt |        49712 | 0.0% |
|          hit |     77535407 | 71.4% |
|         miss |      2632771 | 2.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 49,711 | 77.6% |
| Failure | 14,364 | 22.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 4,684 | 32.6% |
| enumerate | 2,980 | 20.7% |
| reversed list | 2,000 | 13.9% |
| dict items | 1,820 | 12.7% |
| zip | 1,640 | 11.4% |
| dict keys | 620 | 4.3% |
| dict values | 280 | 1.9% |
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
| specialization.deferred |     86661576 | 9.0% |
| specialization.deopt |      1258273 | 0.1% |
|          hit |    810259095 | 84.1% |
|         miss |     66765181 | 6.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,258,353 | 94.0% |
| Failure | 79,820 | 6.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 44,800 | 56.1% |
| not managed dict | 9,720 | 12.2% |
| shadowed | 8,960 | 11.2% |
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
|          hit |    883033361 | 100.0% |
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
|          hit |       345348 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      9278640 | 1.8% |
| specialization.deopt |      1888120 | 0.4% |
|          hit |    417480119 | 79.2% |
|         miss |    100073346 | 19.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,888,120 | 99.4% |
| Failure | 10,480 | 0.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 5,240 | 50.0% |
| not in dict | 4,640 | 44.3% |
| overridden | 260 | 2.5% |
| non object slot | 180 | 1.7% |
| not in keys | 160 | 1.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        94640 | 0.4% |
|          hit |     25102740 | 99.6% |

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
| Basic | 5,432,450,565 | 50.2% |
| Not specialized | 1,231,216,479 | 11.4% |
| Specialized | 4,148,680,812 | 38.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,280 | 100.0% |
| LOAD_ATTR | 86,661,576 | 0.0% |
| CALL | 51,382,800 | 0.0% |
| COMPARE_OP | 32,233,611 | 0.0% |
| BINARY_SUBSCR | 30,385,164 | 0.0% |
| FOR_ITER | 28,393,095 | 0.0% |
| TO_BOOL | 15,192,920 | 0.0% |
| STORE_ATTR | 9,278,640 | 0.0% |
| BINARY_OP | 3,641,520 | 0.0% |
| STORE_SUBSCR | 2,822,880 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 98,742,546 | 44.6% |
| LOAD_ATTR_METHOD_NO_DICT | 43,516,751 | 19.6% |
| CALL_PY_EXACT_ARGS | 33,897,862 | 15.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,056,101 | 5.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,232,000 | 2.8% |
| LOAD_ATTR_SLOT | 5,809,677 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 4,244,340 | 1.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,145,000 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 2,912,665 | 1.3% |
| TO_BOOL_NONE | 2,018,920 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 92,823,030 | 17.6% |
| Calls to Python functions inlined | 436,048,588 | 82.4% |
| Calls via PyEval_EvalFrame (total) | 92,823,030 | 17.6% |
| Calls via PyEval_EvalFrame (vector) | 79,920,390 | 15.1% |
| Calls via PyEval_EvalFrame (generator) | 12,902,640 | 2.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 79,920,390 | 15.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 10,418,946 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 1,856,280 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 17,748,264 | 3.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 525,547,490 | 99.4% |
| Frame objects created | 6,893,580 | 1.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 230,532,311 | 28.3% |
| Frees to freelist | 230,526,409 |  |
| Allocations | 584,407,037 | 71.7% |
| Allocations to 512 bytes | 583,626,584 | 71.6% |
| Allocations to 4 kbytes | 542,073 | 0.1% |
| Allocations over 4 kbytes | 238,380 | 0.0% |
| Frees | 597,615,080 |  |
| New values | 6,648,780 |  |
| Interpreter increfs | 5,404,234,650 | 72.9% |
| Interpreter decrefs | 5,763,380,338 | 71.3% |
| Increfs | 2,006,297,218 | 27.1% |
| Decrefs | 2,323,748,211 | 28.7% |
| Materialize dict (on request) | 480 | 0.0% |
| Materialize dict (new key) | 1,720 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 280 | 0.0% |
| Method cache hits | 317,020,521 |  |
| Method cache misses | 6,764,342 |  |
| Method cache collisions | 8,550,159 |  |
| Method cache dunder hits | 266,697,298 |  |
| Method cache dunder misses | 1,791,062 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 280 | 312,800 | 670,418,520 |
| 1 | 20 | 28,138,360 | 523,872,000 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 910,605 |  |
| Traces created | 1,640 | 0.2% |
| Traces executed | 84,001,028 |  |
| Uops executed | 1,047,468,862 | 12 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 20 |  |
| Trace too long | 280 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 1.2% |
| <= 16 | 540 | 32.9% |
| <= 32 | 600 | 36.6% |
| <= 64 | 480 | 29.3% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 40 | 2.4% |
| <= 16 | 760 | 46.3% |
| <= 32 | 460 | 28.0% |
| <= 64 | 380 | 23.2% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,709,533 | 2.0% |
| <= 4 | 635,520 | 0.8% |
| <= 8 | 40,424,548 | 48.1% |
| <= 16 | 28,033,159 | 33.4% |
| <= 32 | 5,325,792 | 6.3% |
| <= 64 | 7,527,152 | 9.0% |
| <= 128 | 284,808 | 0.3% |
| <= 256 | 51,516 | 0.1% |
| <= 512 | 7,800 | 0.0% |
| <= 1024 | 960 | 0.0% |
| <= 2048 | 240 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 275,477,329 | 26.3% | 26.3% |
| _POP_JUMP_IF_TRUE | 95,060,679 | 9.1% | 35.4% |
| _EXIT_TRACE | 80,556,879 | 7.7% | 43.1% |
| LOAD_FAST | 75,198,695 | 7.2% | 50.2% |
| _ITER_CHECK_LIST | 72,362,856 | 6.9% | 57.2% |
| _IS_ITER_EXHAUSTED_LIST | 71,918,963 | 6.9% | 64.0% |
| STORE_FAST | 47,542,803 | 4.5% | 68.6% |
| POP_TOP | 44,313,152 | 4.2% | 72.8% |
| _ITER_NEXT_LIST | 36,077,411 | 3.4% | 76.2% |
| _GUARD_GLOBALS_VERSION | 30,288,606 | 2.9% | 79.1% |
| _LOAD_GLOBAL_MODULE | 16,896,803 | 1.6% | 80.7% |
| _LOAD_GLOBAL_BUILTINS | 12,941,323 | 1.2% | 82.0% |
| _GUARD_BUILTINS_VERSION | 12,941,323 | 1.2% | 83.2% |
| LOAD_CONST | 11,103,032 | 1.1% | 84.3% |
| _ITER_CHECK_TUPLE | 10,337,440 | 1.0% | 85.3% |
| _IS_ITER_EXHAUSTED_TUPLE | 9,071,800 | 0.9% | 86.1% |
| _POP_JUMP_IF_FALSE | 8,846,712 | 0.8% | 87.0% |
| CALL_ISINSTANCE | 7,664,320 | 0.7% | 87.7% |
| _GUARD_TYPE_VERSION | 7,563,456 | 0.7% | 88.4% |
| TO_BOOL_BOOL | 7,540,720 | 0.7% | 89.1% |
| _LOAD_ATTR_INSTANCE_VALUE | 6,280,760 | 0.6% | 89.7% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 6,280,760 | 0.6% | 90.3% |
| _JUMP_TO_TOP | 6,070,528 | 0.6% | 90.9% |
| _SAVE_CURRENT_IP | 5,966,980 | 0.6% | 91.5% |
| _CHECK_STACK_SPACE | 5,926,660 | 0.6% | 92.1% |
| _CHECK_PEP_523 | 5,926,660 | 0.6% | 92.6% |
| _CHECK_FUNCTION_EXACT_ARGS | 5,926,660 | 0.6% | 93.2% |
| _PUSH_FRAME | 5,925,460 | 0.6% | 93.8% |
| _INIT_CALL_PY_EXACT_ARGS | 5,925,460 | 0.6% | 94.3% |
| RESUME_CHECK | 5,733,780 | 0.5% | 94.9% |
| BINARY_SUBSCR_LIST_INT | 4,681,200 | 0.4% | 95.3% |
| _ITER_CHECK_RANGE | 4,505,600 | 0.4% | 95.7% |
| _IS_ITER_EXHAUSTED_RANGE | 4,505,600 | 0.4% | 96.2% |
| CONTAINS_OP | 3,950,172 | 0.4% | 96.5% |
| _ITER_NEXT_TUPLE | 3,507,540 | 0.3% | 96.9% |
| _IS_NONE | 2,830,960 | 0.3% | 97.2% |
| _ITER_NEXT_RANGE | 2,590,320 | 0.2% | 97.4% |
| BINARY_SUBSCR_TUPLE_INT | 2,482,560 | 0.2% | 97.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,214,900 | 0.2% | 97.8% |
| _GUARD_BOTH_UNICODE | 2,046,480 | 0.2% | 98.0% |
| _BINARY_OP_ADD_UNICODE | 2,046,480 | 0.2% | 98.2% |
| COMPARE_OP_STR | 1,996,920 | 0.2% | 98.4% |
| SET_ADD | 1,996,800 | 0.2% | 98.6% |
| BINARY_SUBSCR_DICT | 1,927,236 | 0.2% | 98.8% |
| LOAD_ATTR | 1,759,860 | 0.2% | 99.0% |
| TO_BOOL_STR | 1,704,580 | 0.2% | 99.1% |
| LOAD_DEREF | 1,652,576 | 0.2% | 99.3% |
| CALL_BUILTIN_FAST | 1,026,912 | 0.1% | 99.4% |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 899,760 | 0.1% | 99.5% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 899,760 | 0.1% | 99.6% |
| LIST_APPEND | 642,000 | 0.1% | 99.6% |
| COMPARE_OP_INT | 493,936 | 0.0% | 99.7% |
| GET_ITER | 447,280 | 0.0% | 99.7% |
| BUILD_LIST | 408,960 | 0.0% | 99.8% |
| _GUARD_BOTH_INT | 274,224 | 0.0% | 99.8% |
| IS_OP | 240,720 | 0.0% | 99.8% |
| SWAP | 239,520 | 0.0% | 99.8% |
| BINARY_SUBSCR | 216,516 | 0.0% | 99.8% |
| _BINARY_OP_ADD_INT | 202,272 | 0.0% | 99.9% |
| BUILD_MAP | 149,520 | 0.0% | 99.9% |
| LOAD_FAST_AND_CLEAR | 119,760 | 0.0% | 99.9% |
| UNPACK_SEQUENCE_TUPLE | 119,220 | 0.0% | 99.9% |
| CALL_LEN | 116,860 | 0.0% | 99.9% |
| TO_BOOL_INT | 114,720 | 0.0% | 99.9% |
| BINARY_SUBSCR_STR_INT | 104,160 | 0.0% | 99.9% |
| BUILD_TUPLE | 95,980 | 0.0% | 99.9% |
| TO_BOOL_LIST | 90,200 | 0.0% | 100.0% |
| _BINARY_OP_SUBTRACT_INT | 71,952 | 0.0% | 100.0% |
| FORMAT_SIMPLE | 65,520 | 0.0% | 100.0% |
| COPY | 52,512 | 0.0% | 100.0% |
| PUSH_NULL | 46,752 | 0.0% | 100.0% |
| CALL_TYPE_1 | 44,160 | 0.0% | 100.0% |
| _POP_FRAME | 41,520 | 0.0% | 100.0% |
| COMPARE_OP | 32,880 | 0.0% | 100.0% |
| STORE_DEREF | 30,000 | 0.0% | 100.0% |
| BINARY_SLICE | 30,000 | 0.0% | 100.0% |
| STORE_SUBSCR_DICT | 24,912 | 0.0% | 100.0% |
| DELETE_SUBSCR | 13,440 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS | 11,460 | 0.0% | 100.0% |
| COPY_FREE_VARS | 7,440 | 0.0% | 100.0% |
| UNPACK_SEQUENCE | 5,200 | 0.0% | 100.0% |
| CALL_STR_1 | 3,840 | 0.0% | 100.0% |
| BUILD_STRING | 3,600 | 0.0% | 100.0% |
| MAKE_FUNCTION | 3,040 | 0.0% | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 2,880 | 0.0% | 100.0% |
| TO_BOOL_NONE | 2,400 | 0.0% | 100.0% |
| TO_BOOL_ALWAYS_TRUE | 1,920 | 0.0% | 100.0% |
| FORMAT_WITH_SPEC | 1,440 | 0.0% | 100.0% |
| BINARY_OP | 1,440 | 0.0% | 100.0% |
| UNARY_INVERT | 480 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER | 849,908 |
| FOR_ITER_GEN | 54,280 |
| LOAD_ATTR_METHOD_NO_DICT | 5,177 |
| LOAD_ATTR_METHOD_WITH_VALUES | 280 |
| LOAD_ATTR_SLOT | 220 |
| YIELD_VALUE | 80 |
| LOAD_ATTR_WITH_HINT | 60 |
| CALL_KW | 40 |
| CALL | 40 |
| LOAD_ATTR_PROPERTY | 20 |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |


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
Stats gathered on: 2023-10-03
