
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 102,891,197 | 17.7% | 17.7% |  |
| RESUME_CHECK | 37,743,279 | 6.5% | 24.2% | 0.0% |
| STORE_FAST | 29,993,043 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 24,862,336 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 24,421,006 | 4.2% | 37.8% |  |
| RETURN_VALUE | 22,436,263 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 19,658,914 | 3.4% | 45.0% |  |
| JUMP_BACKWARD | 18,098,437 | 3.1% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 17,437,862 | 3.0% | 51.1% | 0.0% |
| LOAD_FAST_LOAD_FAST | 16,024,013 | 2.8% | 53.9% |  |
| LOAD_CONST | 15,661,503 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 12,820,119 | 2.2% | 58.8% | 0.0% |
| INTERPRETER_EXIT | 11,985,438 | 2.1% | 60.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,404,002 | 2.0% | 62.8% | 0.7% |
| CALL | 11,117,831 | 1.9% | 64.7% |  |
| LOAD_ATTR | 10,613,488 | 1.8% | 66.6% |  |
| NOP | 10,191,696 | 1.8% | 68.3% |  |
| FOR_ITER_LIST | 10,119,419 | 1.7% | 70.0% |  |
| RETURN_CONST | 9,479,504 | 1.6% | 71.7% |  |
| LOAD_GLOBAL_BUILTIN | 8,926,119 | 1.5% | 73.2% | 0.0% |
| PUSH_NULL | 7,406,296 | 1.3% | 74.5% |  |
| COPY | 7,340,843 | 1.3% | 75.7% |  |
| BINARY_OP | 7,293,055 | 1.3% | 77.0% |  |
| TO_BOOL_BOOL | 7,152,501 | 1.2% | 78.2% |  |
| YIELD_VALUE | 6,913,660 | 1.2% | 79.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,524,996 | 1.1% | 80.5% |  |
| STORE_FAST_LOAD_FAST | 6,464,820 | 1.1% | 81.7% |  |
| FOR_ITER_GEN | 6,347,440 | 1.1% | 82.7% |  |
| TO_BOOL_INT | 5,391,812 | 0.9% | 83.7% |  |
| POP_JUMP_IF_NOT_NONE | 5,166,689 | 0.9% | 84.6% |  |
| STORE_FAST_STORE_FAST | 4,861,657 | 0.8% | 85.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 4,506,506 | 0.8% | 86.2% | 5.4% |
| BUILD_TUPLE | 4,341,118 | 0.7% | 86.9% |  |
| COMPARE_OP_INT | 3,802,893 | 0.7% | 87.6% | 0.2% |
| LOAD_ATTR_MODULE | 3,681,337 | 0.6% | 88.2% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 3,000,660 | 0.5% | 88.7% |  |
| POP_JUMP_IF_TRUE | 2,772,820 | 0.5% | 89.2% |  |
| SWAP | 2,682,707 | 0.5% | 89.7% |  |
| GET_ITER | 2,439,470 | 0.4% | 90.1% |  |
| CALL_FUNCTION_EX | 2,413,948 | 0.4% | 90.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,174,377 | 0.4% | 90.9% |  |
| CALL_BUILTIN_CLASS | 2,061,327 | 0.4% | 91.2% |  |
| LOAD_DEREF | 1,891,952 | 0.3% | 91.5% |  |
| CALL_BUILTIN_FAST | 1,871,280 | 0.3% | 91.9% |  |
| BEFORE_WITH | 1,869,422 | 0.3% | 92.2% |  |
| COPY_FREE_VARS | 1,841,892 | 0.3% | 92.5% |  |
| CONTAINS_OP | 1,793,858 | 0.3% | 92.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,782,258 | 0.3% | 93.1% |  |
| LOAD_SUPER_ATTR_METHOD | 1,745,572 | 0.3% | 93.4% |  |
| UNARY_INVERT | 1,741,598 | 0.3% | 93.7% |  |
| JUMP_FORWARD | 1,736,990 | 0.3% | 94.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,731,958 | 0.3% | 94.3% | 0.0% |
| BUILD_MAP | 1,689,514 | 0.3% | 94.6% |  |
| TO_BOOL | 1,599,176 | 0.3% | 94.9% |  |
| BUILD_LIST | 1,565,539 | 0.3% | 95.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,522,228 | 0.3% | 95.4% |  |
| COMPARE_OP_STR | 1,491,707 | 0.3% | 95.7% |  |
| STORE_SUBSCR_DICT | 1,306,884 | 0.2% | 95.9% |  |
| FOR_ITER | 1,305,260 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 1,234,598 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 1,169,489 | 0.2% | 96.5% |  |
| POP_JUMP_IF_NONE | 1,154,579 | 0.2% | 96.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,137,929 | 0.2% | 96.9% | 0.0% |
| BINARY_OP_ADD_INT | 1,112,440 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 1,086,008 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,086,008 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 1,064,745 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 973,624 | 0.2% | 97.8% | 0.0% |
| LIST_APPEND | 848,956 | 0.1% | 98.0% |  |
| LOAD_FAST_CHECK | 839,822 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 790,574 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 785,651 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 639,743 | 0.1% | 98.5% |  |
| CALL_LEN | 636,119 | 0.1% | 98.6% |  |
| COMPARE_OP | 599,582 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 583,120 | 0.1% | 98.8% |  |
| DICT_MERGE | 564,260 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 563,434 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 503,262 | 0.1% | 99.1% |  |
| LIST_EXTEND | 493,142 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 408,896 | 0.1% | 99.3% |  |
| CALL_KW | 362,687 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 332,961 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 274,320 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 263,063 | 0.0% | 99.5% |  |
| UNARY_NOT | 262,339 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 246,514 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 240,427 | 0.0% | 99.6% | 0.1% |
| CALL_BUILTIN_O | 154,400 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 142,341 | 0.0% | 99.6% | 4.5% |
| MAKE_CELL | 137,900 | 0.0% | 99.7% |  |
| STORE_DEREF | 137,660 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 114,880 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 112,600 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 112,600 | 0.0% | 99.8% |  |
| STORE_ATTR | 100,864 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 99,760 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 97,980 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 91,469 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 0.0% | 99.8% |  |
| DELETE_ATTR | 86,400 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 78,220 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 63,680 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 55,680 | 0.0% | 99.9% |  |
| POP_EXCEPT | 51,883 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 51,883 | 0.0% | 99.9% |  |
| IS_OP | 46,967 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 46,123 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 43,340 | 0.0% | 99.9% |  |
| BUILD_STRING | 41,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 39,160 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 39,040 | 0.0% | 99.9% |  |
| IMPORT_NAME | 33,760 | 0.0% | 100.0% |  |
| IMPORT_FROM | 33,420 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 31,260 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 30,220 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 28,160 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 27,480 | 0.0% | 100.0% |  |
| BINARY_SLICE | 19,820 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 18,900 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,850 | 0.0% | 100.0% |  |
| RERAISE | 17,280 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,900 | 0.0% | 100.0% |  |
| END_FOR | 11,520 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,980 | 0.0% | 100.0% | 0.0% |
| RAISE_VARARGS | 5,780 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,760 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 3,840 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 2,800 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 1,440 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 927 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 520 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,461,147 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 21,134,110 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 13,131,478 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 12,773,519 | 2.2% | 11.9% |
| CACHE RESUME_CHECK | 11,871,558 | 2.0% | 14.0% |
| LOAD_FAST RETURN_VALUE | 10,865,971 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 10,503,564 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 8,749,016 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR | 8,238,906 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 8,206,154 | 1.4% | 22.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 8,041,949 | 1.4% | 23.4% |
| JUMP_BACKWARD FOR_ITER_LIST | 8,008,580 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 7,666,120 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 6,913,520 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 6,696,846 | 1.2% | 28.4% |
| NOP LOAD_FAST | 6,466,685 | 1.1% | 29.5% |
| JUMP_BACKWARD FOR_ITER_GEN | 6,335,920 | 1.1% | 30.6% |
| YIELD_VALUE STORE_FAST | 6,335,920 | 1.1% | 31.7% |
| FOR_ITER_GEN RESUME_CHECK | 6,335,920 | 1.1% | 32.8% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 5,760,060 | 1.0% | 33.8% |
| STORE_FAST JUMP_BACKWARD | 5,760,000 | 1.0% | 34.8% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 5,760,000 | 1.0% | 35.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,757,635 | 1.0% | 36.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,676,753 | 1.0% | 37.7% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 5,391,672 | 0.9% | 38.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,378,877 | 0.9% | 39.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 5,017,619 | 0.9% | 40.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,004,569 | 0.9% | 41.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,117,464 | 0.7% | 42.0% |
| LOAD_FAST LOAD_CONST | 4,026,356 | 0.7% | 42.7% |
| LOAD_GLOBAL_MODULE BINARY_OP | 3,912,334 | 0.7% | 43.4% |
| STORE_FAST NOP | 3,892,784 | 0.7% | 44.0% |
| LOAD_CONST LOAD_CONST | 3,849,760 | 0.7% | 44.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,799,111 | 0.7% | 45.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,760,854 | 0.6% | 46.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,743,798 | 0.6% | 46.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,740,050 | 0.6% | 47.3% |
| LOAD_FAST PUSH_NULL | 3,686,059 | 0.6% | 47.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,678,096 | 0.6% | 48.6% |
| LOAD_ATTR LOAD_FAST | 3,581,393 | 0.6% | 49.2% |
| PUSH_NULL LOAD_FAST | 3,502,539 | 0.6% | 49.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 3,497,530 | 0.6% | 50.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 3,200,968 | 0.6% | 50.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 3,185,042 | 0.5% | 51.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,120,092 | 0.5% | 52.0% |
| BINARY_OP COPY | 2,958,276 | 0.5% | 52.5% |
| COPY TO_BOOL_INT | 2,957,956 | 0.5% | 53.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,744,627 | 0.5% | 53.5% |
| CALL STORE_FAST | 2,680,439 | 0.5% | 54.0% |
| COPY STORE_FAST | 2,630,400 | 0.5% | 54.4% |
| STORE_FAST COPY | 2,629,760 | 0.5% | 54.9% |
| LOAD_CONST CALL | 2,622,363 | 0.5% | 55.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,576,644 | 0.4% | 55.8% |
| CALL RETURN_VALUE | 2,519,638 | 0.4% | 56.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,435,886 | 0.4% | 56.6% |
| RETURN_VALUE STORE_FAST | 2,351,548 | 0.4% | 57.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,309,165 | 0.4% | 57.4% |
| CALL POP_TOP | 2,274,091 | 0.4% | 57.8% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 2,248,976 | 0.4% | 58.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,208,775 | 0.4% | 58.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,167,317 | 0.4% | 58.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 2,096,729 | 0.4% | 59.3% |
| LOAD_CONST COMPARE_OP_INT | 2,086,613 | 0.4% | 59.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,072,641 | 0.4% | 60.0% |
| PUSH_NULL CALL | 2,049,261 | 0.4% | 60.4% |
| RETURN_VALUE RETURN_VALUE | 2,036,813 | 0.4% | 60.7% |
| LOAD_FAST_LOAD_FAST CALL | 1,956,753 | 0.3% | 61.1% |
| POP_TOP RETURN_CONST | 1,940,773 | 0.3% | 61.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,938,732 | 0.3% | 61.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,885,633 | 0.3% | 62.0% |
| LOAD_FAST CALL_FUNCTION_EX | 1,849,668 | 0.3% | 62.4% |
| NOP LOAD_GLOBAL_MODULE | 1,848,549 | 0.3% | 62.7% |
| COPY_FREE_VARS RESUME_CHECK | 1,841,232 | 0.3% | 63.0% |
| LOAD_DEREF LOAD_FAST | 1,835,612 | 0.3% | 63.3% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,835,092 | 0.3% | 63.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,825,082 | 0.3% | 63.9% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,793,238 | 0.3% | 64.2% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,792,578 | 0.3% | 64.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,783,982 | 0.3% | 64.9% |
| LOAD_FAST BUILD_TUPLE | 1,783,558 | 0.3% | 65.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,776,081 | 0.3% | 65.5% |
| POP_TOP LOAD_CONST | 1,768,337 | 0.3% | 65.8% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,745,372 | 0.3% | 66.1% |
| UNARY_INVERT BINARY_OP | 1,741,598 | 0.3% | 66.4% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,725,552 | 0.3% | 66.7% |
| FOR_ITER_LIST STORE_FAST | 1,723,560 | 0.3% | 67.0% |
| LOAD_CONST LOAD_FAST | 1,701,150 | 0.3% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,623,208 | 0.3% | 67.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,613,200 | 0.3% | 67.8% |
| POP_TOP NOP | 1,602,615 | 0.3% | 68.1% |
| GET_ITER FOR_ITER_LIST | 1,602,308 | 0.3% | 68.4% |
| LOAD_FAST GET_ITER | 1,557,719 | 0.3% | 68.6% |
| RETURN_VALUE POP_TOP | 1,547,561 | 0.3% | 68.9% |
| LOAD_FAST TO_BOOL | 1,537,641 | 0.3% | 69.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,527,564 | 0.3% | 69.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,525,588 | 0.3% | 69.7% |
| BINARY_OP STORE_FAST | 1,493,558 | 0.3% | 70.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,493,422 | 0.3% | 70.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,454,574 | 0.3% | 70.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,452,711 | 0.2% | 70.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 18,520 | 93.4% |
| LOAD_CONST | 980 | 4.9% |
| LOAD_FAST | 280 | 1.4% |
| BINARY_OP | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 18,900 | 95.4% |
| BUILD_TUPLE | 280 | 1.4% |
| LOAD_DEREF | 280 | 1.4% |
| STORE_FAST | 280 | 1.4% |
| CALL | 80 | 0.4% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,871,558 | 99.0% |
| COPY_FREE_VARS | 109,900 | 0.9% |
| POP_TOP | 7,460 | 0.1% |
| RESUME | 2,280 | 0.0% |
| MAKE_CELL | 20 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,253,708 | 67.1% |
| RETURN_VALUE | 509,134 | 27.2% |
| LOAD_GLOBAL_MODULE | 82,440 | 4.4% |
| LOAD_FAST | 17,280 | 0.9% |
| CALL | 6,360 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,354,628 | 72.5% |
| STORE_FAST | 514,794 | 27.5% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 27,440 | 99.9% |
| BINARY_OP | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,480 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 576,080 | 90.0% |
| LOAD_CONST | 62,703 | 9.8% |
| BINARY_SUBSCR | 880 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 575,920 | 90.0% |
| STORE_FAST | 62,423 | 9.8% |
| BINARY_SUBSCR | 880 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40,963 | 88.8% |
| LOAD_ATTR_MODULE | 5,100 | 11.1% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,123 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,900 | 48.5% |
| CALL | 27,520 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,716 | 16.3% |
| LOAD_ATTR | 84 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60,800 | 77.7% |
| RETURN_CONST | 10,240 | 13.1% |
| LOAD_FAST | 7,040 | 9.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.2% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 11,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 5,760 | 50.0% |
| LOAD_FAST | 5,760 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,086,008 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,086,008 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 28,160 | 50.6% |
| LOAD_FAST | 27,520 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 41,600 | 74.7% |
| BUILD_STRING | 14,080 | 25.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,557,719 | 63.9% |
| STORE_FAST_LOAD_FAST | 576,000 | 23.6% |
| CALL_BUILTIN_CLASS | 278,211 | 11.4% |
| CALL | 14,340 | 0.6% |
| RETURN_VALUE | 5,760 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,602,308 | 65.7% |
| LOAD_FAST_AND_CLEAR | 523,191 | 21.4% |
| FOR_ITER_RANGE | 271,296 | 11.1% |
| FOR_ITER | 12,115 | 0.5% |
| FOR_ITER_TUPLE | 11,740 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,503,564 | 87.6% |
| RETURN_CONST | 904,134 | 7.5% |
| YIELD_VALUE | 577,740 | 4.8% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 500 | 89.3% |
| POP_TOP | 60 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 560 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 63,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 39,040 | 61.3% |
| STORE_FAST | 14,080 | 22.1% |
| LOAD_FAST | 7,040 | 11.1% |
| STORE_NAME | 2,480 | 3.9% |
| LOAD_CONST | 560 | 0.9% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,892,784 | 38.2% |
| POP_TOP | 1,602,615 | 15.7% |
| RESUME_CHECK | 1,418,378 | 13.9% |
| POP_JUMP_IF_FALSE | 1,358,862 | 13.3% |
| JUMP_BACKWARD | 1,088,000 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,466,685 | 63.5% |
| LOAD_GLOBAL_MODULE | 1,848,549 | 18.1% |
| LOAD_GLOBAL_BUILTIN | 751,202 | 7.4% |
| LOAD_FAST_LOAD_FAST | 583,320 | 5.7% |
| LOAD_CONST | 530,020 | 5.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 34,863 | 67.2% |
| COPY | 11,520 | 22.2% |
| POP_TOP | 5,200 | 10.0% |
| STORE_FAST | 280 | 0.5% |
| STORE_SUBSCR_DICT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 35,163 | 67.8% |
| RERAISE | 11,520 | 22.2% |
| JUMP_FORWARD | 5,120 | 9.9% |
| RETURN_CONST | 60 | 0.1% |
| LOAD_FAST | 20 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,913,520 | 28.3% |
| RETURN_CONST | 6,696,846 | 27.4% |
| CALL | 2,274,091 | 9.3% |
| RETURN_VALUE | 1,547,561 | 6.3% |
| POP_JUMP_IF_FALSE | 1,525,588 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 8,749,016 | 35.8% |
| LOAD_FAST | 7,666,120 | 31.4% |
| RETURN_CONST | 1,940,773 | 7.9% |
| LOAD_CONST | 1,768,337 | 7.2% |
| NOP | 1,602,615 | 6.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 40,583 | 78.2% |
| RERAISE | 5,760 | 11.1% |
| CALL_KW | 5,120 | 9.9% |
| BINARY_SUBSCR_DICT | 300 | 0.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40,923 | 78.9% |
| WITH_EXCEPT_START | 5,760 | 11.1% |
| LOAD_GLOBAL_MODULE | 5,080 | 9.8% |
| LOAD_GLOBAL | 120 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,686,059 | 49.8% |
| LOAD_ATTR_MODULE | 2,309,165 | 31.2% |
| LOAD_ATTR | 1,284,352 | 17.3% |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,502,539 | 47.3% |
| CALL | 2,049,261 | 27.7% |
| LOAD_FAST_LOAD_FAST | 1,396,238 | 18.9% |
| LOAD_CONST | 320,956 | 4.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 64,682 | 0.9% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 18,420 | 97.5% |
| COPY_FREE_VARS | 340 | 1.8% |
| CALL | 140 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,760 | 30.5% |
| LOAD_FAST | 5,760 | 30.5% |
| STORE_FAST | 5,760 | 30.5% |
| CALL_METHOD_DESCRIPTOR_O | 1,300 | 6.9% |
| CALL | 320 | 1.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,865,971 | 48.4% |
| CALL | 2,519,638 | 11.2% |
| RETURN_VALUE | 2,036,813 | 9.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,623,208 | 7.2% |
| CALL_FUNCTION_EX | 1,265,488 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 10,503,564 | 46.8% |
| STORE_FAST | 2,351,548 | 10.5% |
| RETURN_VALUE | 2,036,813 | 9.1% |
| POP_TOP | 1,547,561 | 6.9% |
| LOAD_FAST_LOAD_FAST | 1,216,678 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 14,080 | 45.0% |
| LOAD_FAST | 10,440 | 33.4% |
| LOAD_ATTR_INSTANCE_VALUE | 5,800 | 18.6% |
| STORE_SUBSCR | 660 | 2.1% |
| LOAD_ATTR | 200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 19,960 | 63.9% |
| LOAD_GLOBAL_MODULE | 10,200 | 32.6% |
| STORE_SUBSCR | 660 | 2.1% |
| STORE_SUBSCR_DICT | 260 | 0.8% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,537,641 | 96.2% |
| LOAD_ATTR_INSTANCE_VALUE | 53,501 | 3.3% |
| TO_BOOL | 3,667 | 0.2% |
| LOAD_ATTR | 884 | 0.1% |
| RETURN_VALUE | 763 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 851,164 | 53.2% |
| POP_JUMP_IF_FALSE | 741,304 | 46.4% |
| TO_BOOL | 3,667 | 0.2% |
| TO_BOOL_BOOL | 2,161 | 0.1% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,216,678 | 69.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 524,840 | 30.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,741,598 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 262,299 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 262,339 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 5,680 | 98.6% |
| TO_BOOL | 80 | 1.4% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,912,334 | 53.6% |
| UNARY_INVERT | 1,741,598 | 23.9% |
| POP_JUMP_IF_FALSE | 1,216,678 | 16.7% |
| LOAD_ATTR | 276,560 | 3.8% |
| LOAD_FAST_LOAD_FAST | 84,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,958,276 | 40.6% |
| STORE_FAST | 1,493,558 | 20.5% |
| TO_BOOL_INT | 1,216,738 | 16.7% |
| UNARY_INVERT | 1,216,678 | 16.7% |
| BUILD_TUPLE | 262,460 | 3.6% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 140 | 50.0% |
| STORE_FAST | 140 | 50.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 523,191 | 33.4% |
| JUMP_FORWARD | 508,894 | 32.5% |
| LOAD_FAST | 263,123 | 16.8% |
| POP_TOP | 245,791 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 526,134 | 33.6% |
| SWAP | 523,191 | 33.4% |
| STORE_FAST | 510,354 | 32.6% |
| RETURN_VALUE | 5,120 | 0.3% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 576,000 | 34.1% |
| LOAD_FAST | 529,560 | 31.3% |
| RESUME_CHECK | 519,094 | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 17,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,096,214 | 64.9% |
| BUILD_TUPLE | 576,020 | 34.1% |
| STORE_FAST | 17,280 | 1.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,520 | 66.2% |
| FORMAT_SIMPLE | 14,080 | 33.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 27,440 | 66.0% |
| RETURN_VALUE | 14,080 | 33.8% |
| BINARY_OP | 80 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,783,558 | 41.1% |
| LOAD_FAST_LOAD_FAST | 1,160,320 | 26.7% |
| BUILD_MAP | 576,020 | 13.3% |
| RETURN_VALUE | 512,000 | 11.8% |
| BINARY_OP | 262,460 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,218,238 | 28.1% |
| YIELD_VALUE | 1,152,100 | 26.5% |
| BUILD_MAP | 576,000 | 13.3% |
| STORE_FAST | 512,000 | 11.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 11.8% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,622,363 | 23.6% |
| PUSH_NULL | 2,049,261 | 18.4% |
| LOAD_FAST_LOAD_FAST | 1,956,753 | 17.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,447,569 | 13.0% |
| BUILD_TUPLE | 1,218,238 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,680,439 | 24.1% |
| RETURN_VALUE | 2,519,638 | 22.7% |
| POP_TOP | 2,274,091 | 20.5% |
| LOAD_FAST | 1,093,097 | 9.8% |
| TO_BOOL_BOOL | 733,596 | 6.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,849,668 | 76.6% |
| DICT_MERGE | 564,260 | 23.4% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,265,488 | 52.4% |
| RESUME_CHECK | 535,040 | 22.2% |
| CALL_BUILTIN_CLASS | 511,960 | 21.2% |
| POP_TOP | 95,360 | 4.0% |
| STORE_FAST | 5,760 | 0.2% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 140 | 87.5% |
| CALL_FUNCTION_EX | 20 | 12.5% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 362,687 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 293,071 | 80.8% |
| LOAD_FAST | 28,800 | 7.9% |
| RETURN_VALUE | 21,120 | 5.8% |
| STORE_FAST | 14,220 | 3.9% |
| PUSH_EXC_INFO | 5,120 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 595,389 | 99.3% |
| COMPARE_OP | 1,296 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 962 | 0.2% |
| LOAD_GLOBAL_MODULE | 380 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 596,311 | 99.5% |
| COMPARE_OP | 1,296 | 0.2% |
| COMPARE_OP_INT | 1,175 | 0.2% |
| COMPARE_OP_STR | 440 | 0.1% |
| POP_JUMP_IF_TRUE | 280 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,792,578 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,793,238 | 100.0% |
| POP_JUMP_IF_TRUE | 480 | 0.0% |
| STORE_FAST | 140 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 14,040 | 49.9% |
| CALL_BUILTIN_FAST | 14,040 | 49.9% |
| BINARY_SUBSCR | 40 | 0.1% |
| CALL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 28,160 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,958,276 | 40.3% |
| STORE_FAST | 2,629,760 | 35.8% |
| LOAD_CONST | 1,100,800 | 15.0% |
| LOAD_FAST | 590,100 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 21,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,957,956 | 40.3% |
| STORE_FAST | 2,630,400 | 35.8% |
| STORE_FAST_STORE_FAST | 1,093,760 | 14.9% |
| LOAD_ATTR_INSTANCE_VALUE | 575,880 | 7.8% |
| LOAD_FAST | 28,160 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,216,678 | 66.1% |
| CALL_ALLOC_AND_ENTER_INIT | 508,854 | 27.6% |
| CACHE | 109,900 | 6.0% |
| CALL | 5,940 | 0.3% |
| CALL_PY_EXACT_ARGS | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,841,232 | 100.0% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,600 | 66.7% |
| RETURN_CONST | 27,520 | 31.9% |
| LOAD_GLOBAL_MODULE | 1,240 | 1.4% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 529,700 | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 6.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 564,260 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,271,225 | 97.4% |
| SWAP | 14,160 | 1.1% |
| GET_ITER | 12,115 | 0.9% |
| LOAD_FAST | 6,060 | 0.5% |
| FOR_ITER | 1,700 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 688,680 | 52.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 581,600 | 44.6% |
| SWAP | 14,080 | 1.1% |
| RETURN_CONST | 11,820 | 0.9% |
| LOAD_GLOBAL_MODULE | 5,680 | 0.4% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 33,080 | 99.0% |
| STORE_NAME | 340 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,640 | 97.7% |
| STORE_NAME | 780 | 2.3% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 33,080 | 98.0% |
| STORE_NAME | 680 | 2.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 27,520 | 58.6% |
| LOAD_FAST | 17,420 | 37.1% |
| LOAD_GLOBAL_MODULE | 1,987 | 4.2% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,827 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,749,016 | 48.3% |
| STORE_FAST | 5,760,000 | 31.8% |
| POP_JUMP_IF_NOT_NONE | 1,004,642 | 5.6% |
| LIST_APPEND | 848,956 | 4.7% |
| STORE_FAST_STORE_FAST | 581,760 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 8,008,580 | 44.3% |
| FOR_ITER_GEN | 6,335,920 | 35.0% |
| FOR_ITER | 1,271,225 | 7.0% |
| NOP | 1,088,000 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 575,960 | 3.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,096,976 | 63.2% |
| POP_TOP | 621,794 | 35.8% |
| STORE_ATTR_INSTANCE_VALUE | 7,020 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 5,720 | 0.3% |
| POP_EXCEPT | 5,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,149,773 | 66.2% |
| BUILD_LIST | 508,894 | 29.3% |
| POP_EXCEPT | 34,863 | 2.0% |
| LOAD_GLOBAL_MODULE | 24,820 | 1.4% |
| LOAD_FAST_LOAD_FAST | 7,320 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 471,836 | 55.6% |
| LOAD_ATTR | 262,480 | 30.9% |
| BINARY_SUBSCR_STR_INT | 112,600 | 13.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,000 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 848,956 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,211 | 50.1% |
| RETURN_VALUE | 245,791 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 246,431 | 50.0% |
| STORE_FAST | 245,791 | 49.8% |
| RETURN_VALUE | 640 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,238,906 | 77.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,825,082 | 17.2% |
| LOAD_GLOBAL_MODULE | 402,712 | 3.8% |
| CALL | 83,860 | 0.8% |
| LOAD_ATTR | 22,864 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,581,393 | 33.7% |
| PUSH_NULL | 1,284,352 | 12.1% |
| STORE_SUBSCR_DICT | 1,216,598 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 1,173,314 | 11.1% |
| STORE_FAST | 753,232 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,026,356 | 25.7% |
| LOAD_CONST | 3,849,760 | 24.6% |
| POP_TOP | 1,768,337 | 11.3% |
| POP_JUMP_IF_FALSE | 925,110 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 743,097 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,849,760 | 24.6% |
| CALL | 2,622,363 | 16.7% |
| COMPARE_OP_INT | 2,086,613 | 13.3% |
| LOAD_FAST | 1,701,150 | 10.9% |
| COPY | 1,100,800 | 7.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,835,092 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 27,520 | 1.5% |
| STORE_DEREF | 27,520 | 1.5% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,835,612 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 55,040 | 2.9% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,134,110 | 20.5% |
| STORE_FAST | 13,131,478 | 12.8% |
| POP_JUMP_IF_FALSE | 8,041,949 | 7.8% |
| POP_TOP | 7,666,120 | 7.5% |
| NOP | 6,466,685 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,461,147 | 21.8% |
| RETURN_VALUE | 10,865,971 | 10.6% |
| LOAD_ATTR | 8,238,906 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,206,154 | 8.0% |
| CALL_PY_EXACT_ARGS | 5,378,877 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 523,191 | 66.6% |
| LOAD_FAST_AND_CLEAR | 262,460 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 523,191 | 66.6% |
| LOAD_FAST_AND_CLEAR | 262,460 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 576,560 | 68.7% |
| POP_JUMP_IF_NONE | 246,434 | 29.3% |
| LOAD_ATTR_CLASS | 16,508 | 2.0% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 68.6% |
| LOAD_GLOBAL_MODULE | 246,354 | 29.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 16,468 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,744,627 | 17.1% |
| LOAD_FAST_LOAD_FAST | 2,096,729 | 13.1% |
| POP_JUMP_IF_FALSE | 1,527,564 | 9.5% |
| PUSH_NULL | 1,396,238 | 8.7% |
| LOAD_SUPER_ATTR_METHOD | 1,230,958 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,743,798 | 23.4% |
| LOAD_FAST_LOAD_FAST | 2,096,729 | 13.1% |
| CALL | 1,956,753 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,776,081 | 11.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,216,598 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,710 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,821 | 38.2% |
| LOAD_ATTR | 3,324 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,741 | 15.4% |
| LOAD_FAST | 2,164 | 12.1% |
| CALL | 740 | 4.1% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 820 | 37.3% |
| LOAD_CONST | 600 | 27.3% |
| RESUME | 560 | 25.5% |
| PUSH_NULL | 120 | 5.5% |
| POP_TOP | 80 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 640 | 29.1% |
| CALL | 500 | 22.7% |
| LOAD_ATTR | 420 | 19.1% |
| LOAD_CONST | 380 | 17.3% |
| PUSH_NULL | 220 | 10.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 200 | 38.5% |
| PUSH_NULL | 80 | 15.4% |
| LOAD_FAST_LOAD_FAST | 80 | 15.4% |
| LOAD_SUPER_ATTR_ATTR | 80 | 15.4% |
| CALL | 40 | 7.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 110,080 | 79.8% |
| CALL_PY_EXACT_ARGS | 27,800 | 20.2% |
| CACHE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 110,080 | 79.8% |
| RESUME_CHECK | 27,820 | 20.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 5,391,672 | 27.4% |
| TO_BOOL_BOOL | 5,004,569 | 25.5% |
| COMPARE_OP_INT | 3,799,111 | 19.3% |
| CONTAINS_OP | 1,793,238 | 9.1% |
| COMPARE_OP_STR | 1,452,711 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,041,949 | 40.9% |
| RETURN_CONST | 3,200,968 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,527,564 | 7.8% |
| POP_TOP | 1,525,588 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,493,422 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,076,779 | 93.3% |
| LOAD_ATTR_INSTANCE_VALUE | 47,800 | 4.1% |
| LOAD_ATTR | 28,300 | 2.5% |
| RETURN_VALUE | 1,400 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 299,810 | 26.0% |
| NOP | 283,711 | 24.6% |
| LOAD_FAST | 274,618 | 23.8% |
| LOAD_FAST_CHECK | 246,434 | 21.3% |
| RETURN_CONST | 24,340 | 2.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,435,886 | 47.1% |
| LOAD_ATTR | 1,173,314 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,008,587 | 19.5% |
| RETURN_VALUE | 472,476 | 9.1% |
| LOAD_DEREF | 55,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,072,641 | 40.1% |
| RETURN_CONST | 1,174,692 | 22.7% |
| JUMP_BACKWARD | 1,004,642 | 19.4% |
| NOP | 517,566 | 10.0% |
| LOAD_CONST | 246,071 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,885,633 | 68.0% |
| TO_BOOL | 851,164 | 30.7% |
| TO_BOOL_NONE | 19,700 | 0.7% |
| COMPARE_OP_STR | 10,916 | 0.4% |
| COMPARE_OP_INT | 3,387 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 956,685 | 34.5% |
| LOAD_FAST_LOAD_FAST | 853,960 | 30.8% |
| RETURN_CONST | 770,595 | 27.8% |
| LOAD_GLOBAL_MODULE | 74,642 | 2.7% |
| RETURN_VALUE | 62,383 | 2.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,760 | 99.7% |
| CALL_KW | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,760 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 11,520 | 66.7% |
| POP_JUMP_IF_TRUE | 5,760 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,760 | 50.0% |
| COPY | 5,760 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,200,968 | 33.8% |
| STORE_ATTR_INSTANCE_VALUE | 2,248,976 | 23.7% |
| POP_TOP | 1,940,773 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 1,174,692 | 12.4% |
| POP_JUMP_IF_TRUE | 770,595 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,696,846 | 70.6% |
| EXIT_INIT_CHECK | 1,086,008 | 11.5% |
| INTERPRETER_EXIT | 904,134 | 9.5% |
| TO_BOOL_BOOL | 690,927 | 7.3% |
| STORE_FAST | 64,223 | 0.7% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 39,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 37,920 | 97.1% |
| STORE_NAME | 780 | 2.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.7% |
| LOAD_FAST | 60 | 0.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,564 | 58.1% |
| LOAD_FAST_LOAD_FAST | 22,040 | 21.9% |
| LOAD_ATTR_INSTANCE_VALUE | 17,280 | 17.1% |
| STORE_ATTR | 2,520 | 2.5% |
| LOAD_ATTR | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 44,840 | 44.5% |
| LOAD_FAST_LOAD_FAST | 14,760 | 14.6% |
| LOAD_FAST | 13,620 | 13.5% |
| LOAD_CONST | 12,644 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 5,680 | 5.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 55,040 | 40.0% |
| LOAD_GLOBAL_MODULE | 55,040 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 27,520 | 20.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 54,960 | 39.9% |
| LOAD_DEREF | 27,520 | 20.0% |
| LOAD_FAST | 27,520 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 27,480 | 20.0% |
| LOAD_GLOBAL | 120 | 0.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 6,335,920 | 21.1% |
| CALL | 2,680,439 | 8.9% |
| COPY | 2,630,400 | 8.8% |
| RETURN_VALUE | 2,351,548 | 7.8% |
| FOR_ITER_LIST | 1,723,560 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,131,478 | 43.8% |
| JUMP_BACKWARD | 5,760,000 | 19.2% |
| NOP | 3,892,784 | 13.0% |
| COPY | 2,629,760 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 1,224,734 | 4.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,760,060 | 89.1% |
| FOR_ITER | 688,680 | 10.7% |
| COPY | 14,080 | 0.2% |
| FOR_ITER_TUPLE | 2,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,760,000 | 89.1% |
| GET_ITER | 576,000 | 8.9% |
| LOAD_FAST | 112,640 | 1.7% |
| STORE_ATTR_INSTANCE_VALUE | 14,000 | 0.2% |
| TO_BOOL_STR | 2,000 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,167,317 | 44.6% |
| COPY | 1,093,760 | 22.5% |
| UNPACK_SEQUENCE_TUPLE | 1,088,220 | 22.4% |
| STORE_FAST_STORE_FAST | 512,000 | 10.5% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,613,200 | 33.2% |
| STORE_FAST | 1,088,280 | 22.4% |
| LOAD_FAST_LOAD_FAST | 1,050,497 | 21.6% |
| JUMP_BACKWARD | 581,760 | 12.0% |
| STORE_FAST_STORE_FAST | 512,000 | 10.5% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 2,480 | 33.2% |
| CALL | 1,200 | 16.0% |
| IMPORT_FROM | 780 | 10.4% |
| SET_FUNCTION_ATTRIBUTE | 780 | 10.4% |
| IMPORT_NAME | 680 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,640 | 62.0% |
| LOAD_NAME | 820 | 11.0% |
| RETURN_CONST | 700 | 9.4% |
| LOAD_BUILD_CLASS | 500 | 6.7% |
| POP_TOP | 440 | 5.9% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 575,940 | 21.5% |
| BUILD_LIST | 523,191 | 19.5% |
| LOAD_FAST_AND_CLEAR | 523,191 | 19.5% |
| FOR_ITER_LIST | 508,251 | 18.9% |
| LOAD_FAST | 274,234 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 575,880 | 21.5% |
| LOAD_CONST | 536,694 | 20.0% |
| BUILD_LIST | 523,191 | 19.5% |
| STORE_FAST | 523,191 | 19.5% |
| FOR_ITER_LIST | 508,171 | 18.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 260 | 28.3% |
| FOR_ITER | 240 | 26.1% |
| LOAD_FAST | 120 | 13.0% |
| RETURN_VALUE | 80 | 8.7% |
| LOAD_FAST_CHECK | 80 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 360 | 39.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 340 | 37.0% |
| UNPACK_SEQUENCE_TUPLE | 100 | 10.9% |
| LOAD_FAST | 40 | 4.3% |
| STORE_FAST | 40 | 4.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 5,760,000 | 83.3% |
| BUILD_TUPLE | 1,152,100 | 16.7% |
| CALL_STR_1 | 1,260 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,335,920 | 91.6% |
| INTERPRETER_EXIT | 577,740 | 8.4% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,820 | 47.2% |
| CACHE | 2,280 | 38.1% |
| COPY_FREE_VARS | 320 | 5.4% |
| CALL_KW | 200 | 3.3% |
| POP_TOP | 140 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880 | 48.2% |
| LOAD_GLOBAL | 1,520 | 25.4% |
| LOAD_NAME | 560 | 9.4% |
| NOP | 280 | 4.7% |
| LOAD_CONST | 240 | 4.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 263,023 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 263,063 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,093,800 | 98.3% |
| LOAD_FAST_LOAD_FAST | 18,480 | 1.7% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 575,940 | 51.8% |
| STORE_FAST | 511,980 | 46.0% |
| BINARY_SLICE | 18,520 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,680 | 0.5% |
| LOAD_CONST | 280 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 32.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,240 | 32.3% |
| LOAD_FAST_LOAD_FAST | 960 | 25.0% |
| BINARY_SUBSCR_LIST_INT | 280 | 7.3% |
| LOAD_FAST | 80 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,740 | 45.3% |
| LOAD_CONST | 1,260 | 32.8% |
| CALL | 480 | 12.5% |
| STORE_FAST | 360 | 9.4% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 112,560 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 112,560 | 100.0% |
| CALL | 40 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 246,354 | 99.9% |
| BINARY_OP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 246,514 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,778 | 79.5% |
| LOAD_CONST | 62,303 | 18.7% |
| CALL_LEN | 5,680 | 1.7% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 327,241 | 98.3% |
| CALL_BUILTIN_CLASS | 5,680 | 1.7% |
| CALL | 40 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 99,860 | 86.9% |
| LOAD_CONST | 14,280 | 12.4% |
| LOAD_FAST | 700 | 0.6% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 99,860 | 86.9% |
| CONVERT_VALUE | 14,040 | 12.2% |
| STORE_FAST | 400 | 0.3% |
| PUSH_EXC_INFO | 300 | 0.3% |
| LOAD_FAST | 140 | 0.1% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 491,502 | 97.7% |
| LOAD_CONST | 11,640 | 2.3% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 491,542 | 97.7% |
| LOAD_CONST | 11,440 | 2.3% |
| BINARY_OP_ADD_UNICODE | 280 | 0.1% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 112,560 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 112,600 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 39,120 | 99.9% |
| BINARY_SUBSCR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,020 | 84.3% |
| JUMP_FORWARD | 5,720 | 14.6% |
| STORE_FAST | 420 | 1.1% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 536,294 | 49.4% |
| LOAD_FAST | 516,014 | 47.5% |
| CALL | 33,420 | 3.1% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 577,154 | 53.1% |
| COPY_FREE_VARS | 508,854 | 46.9% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 64,682 | 45.4% |
| LOAD_FAST | 64,240 | 45.1% |
| LOAD_CONST | 7,480 | 5.3% |
| BINARY_OP_ADD_INT | 5,680 | 4.0% |
| CALL | 159 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 135,961 | 95.5% |
| POP_TOP | 6,280 | 4.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 744,742 | 36.1% |
| CALL_FUNCTION_EX | 511,960 | 24.8% |
| LOAD_FAST | 280,803 | 13.6% |
| CALL_BUILTIN_CLASS | 245,711 | 11.9% |
| CALL_LEN | 245,711 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 775,043 | 37.6% |
| STORE_FAST | 745,042 | 36.1% |
| GET_ITER | 278,211 | 13.5% |
| CALL_BUILTIN_CLASS | 245,711 | 11.9% |
| LOAD_FAST | 17,280 | 0.8% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 910,531 | 48.7% |
| LOAD_CONST | 649,462 | 34.7% |
| LOAD_FAST_LOAD_FAST | 173,138 | 9.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 81,229 | 4.3% |
| LOAD_GLOBAL_MODULE | 27,880 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 639,402 | 34.2% |
| STORE_FAST | 599,578 | 32.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 474,457 | 25.4% |
| UNPACK_SEQUENCE_TUPLE | 81,229 | 4.3% |
| POP_TOP | 14,834 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 519,140 | 45.6% |
| BUILD_TUPLE | 511,960 | 45.0% |
| CALL | 64,981 | 5.7% |
| LOAD_FAST_CHECK | 16,468 | 1.4% |
| LOAD_ATTR | 14,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,053,900 | 92.6% |
| RETURN_VALUE | 82,129 | 7.2% |
| LOAD_FAST | 1,260 | 0.1% |
| STORE_FAST | 440 | 0.0% |
| BEFORE_WITH | 140 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 112,560 | 72.9% |
| LOAD_ATTR | 27,440 | 17.8% |
| LOAD_FAST | 14,280 | 9.2% |
| CALL | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 112,560 | 72.9% |
| LOAD_FAST | 41,520 | 26.9% |
| STORE_FAST | 140 | 0.1% |
| TO_BOOL_INT | 140 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,234,138 | 100.0% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,234,418 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 607,838 | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE | 27,900 | 4.4% |
| CALL | 381 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 344,218 | 54.1% |
| CALL_BUILTIN_CLASS | 245,711 | 38.6% |
| CALL_PY_EXACT_ARGS | 33,160 | 5.2% |
| LOAD_FAST | 5,720 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 5,680 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 262,380 | 95.6% |
| LOAD_FAST | 11,440 | 4.2% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 262,420 | 95.7% |
| LOAD_GLOBAL_MODULE | 11,440 | 4.2% |
| NOP | 280 | 0.1% |
| RETURN_CONST | 140 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,725,552 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,306 | 0.1% |
| LOAD_GLOBAL_MODULE | 2,280 | 0.1% |
| LOAD_CONST | 1,240 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,216,958 | 70.3% |
| STORE_FAST | 511,460 | 29.5% |
| LIST_APPEND | 2,000 | 0.1% |
| TO_BOOL_NONE | 1,240 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 37,480 | 86.5% |
| BUILD_TUPLE | 5,680 | 13.1% |
| CALL | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 31,860 | 73.5% |
| LOAD_FAST | 11,480 | 26.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,421,511 | 93.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 97,697 | 6.4% |
| LOAD_ATTR | 2,480 | 0.2% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 670,540 | 44.0% |
| STORE_FAST | 575,960 | 37.8% |
| LOAD_FAST | 85,060 | 5.6% |
| CALL_BUILTIN_FAST | 81,229 | 5.3% |
| RETURN_VALUE | 51,576 | 3.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,184 | 91.8% |
| LOAD_CONST | 33,720 | 3.5% |
| CALL | 29,140 | 3.0% |
| RETURN_VALUE | 14,000 | 1.4% |
| RETURN_GENERATOR | 1,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 923,464 | 94.8% |
| LOAD_CONST | 33,440 | 3.4% |
| RETURN_VALUE | 14,900 | 1.5% |
| BINARY_OP_ADD_UNICODE | 1,240 | 0.1% |
| STORE_FAST | 280 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,757,635 | 44.9% |
| LOAD_FAST | 5,378,877 | 42.0% |
| LOAD_FAST_LOAD_FAST | 835,911 | 6.5% |
| LOAD_SUPER_ATTR_METHOD | 508,814 | 4.0% |
| LOAD_GLOBAL_MODULE | 93,900 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,773,519 | 99.6% |
| MAKE_CELL | 27,800 | 0.2% |
| RETURN_GENERATOR | 18,420 | 0.1% |
| COPY_FREE_VARS | 360 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,241,487 | 41.4% |
| LOAD_ATTR_MODULE | 1,216,598 | 40.5% |
| LOAD_FAST | 345,420 | 11.5% |
| LOAD_CONST | 107,275 | 3.6% |
| BINARY_OP | 83,760 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,783,982 | 59.5% |
| COPY_FREE_VARS | 1,216,678 | 40.5% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,860 | 99.7% |
| CALL | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,220 | 85.9% |
| YIELD_VALUE | 1,260 | 10.6% |
| STORE_FAST | 280 | 2.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 140 | 1.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 581,740 | 99.8% |
| LOAD_FAST | 1,240 | 0.2% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 581,720 | 99.8% |
| LOAD_FAST | 1,260 | 0.2% |
| CALL | 140 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,240 | 86.1% |
| LOAD_GLOBAL_MODULE | 140 | 9.7% |
| CALL | 60 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 1,260 | 87.5% |
| PUSH_NULL | 140 | 9.7% |
| LOAD_GLOBAL | 40 | 2.8% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,086,613 | 54.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,095,778 | 28.8% |
| LOAD_FAST | 576,980 | 15.2% |
| LOAD_FAST_LOAD_FAST | 18,480 | 0.5% |
| CALL_BUILTIN_FAST | 14,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,799,111 | 99.9% |
| POP_JUMP_IF_TRUE | 3,387 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 95 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,425,587 | 95.6% |
| LOAD_CONST | 59,860 | 4.0% |
| LOAD_FAST | 5,820 | 0.4% |
| COMPARE_OP | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,452,711 | 97.4% |
| COPY | 14,040 | 0.9% |
| LOAD_FAST | 14,040 | 0.9% |
| POP_JUMP_IF_TRUE | 10,916 | 0.7% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,335,920 | 99.8% |
| GET_ITER | 11,440 | 0.2% |
| FOR_ITER | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,335,920 | 99.8% |
| POP_TOP | 11,440 | 0.2% |
| RESUME | 80 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 8,008,580 | 79.1% |
| GET_ITER | 1,602,308 | 15.8% |
| SWAP | 508,171 | 5.0% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 5,760,060 | 56.9% |
| STORE_FAST | 1,723,560 | 17.0% |
| LOAD_FAST | 1,017,788 | 10.1% |
| JUMP_BACKWARD | 576,000 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 525,320 | 5.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 519,078 | 65.7% |
| GET_ITER | 271,296 | 34.3% |
| FOR_ITER | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 533,743 | 67.5% |
| LOAD_FAST | 245,951 | 31.1% |
| RETURN_CONST | 10,880 | 1.4% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 16,320 | 54.0% |
| GET_ITER | 11,740 | 38.8% |
| LOAD_FAST | 1,260 | 4.2% |
| SWAP | 860 | 2.8% |
| FOR_ITER | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,260 | 47.2% |
| LOAD_FAST | 10,460 | 34.6% |
| RETURN_CONST | 2,560 | 8.5% |
| STORE_FAST_LOAD_FAST | 2,000 | 6.6% |
| SWAP | 860 | 2.8% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 81,189 | 88.8% |
| LOAD_ATTR_MODULE | 10,200 | 11.2% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,961 | 82.0% |
| LOAD_FAST_CHECK | 16,508 | 18.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,461,147 | 90.3% |
| LOAD_FAST_LOAD_FAST | 1,776,081 | 7.1% |
| COPY | 575,880 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 23,687 | 0.1% |
| RETURN_VALUE | 14,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,676,753 | 22.8% |
| LOAD_FAST | 3,760,854 | 15.1% |
| TO_BOOL_BOOL | 1,938,732 | 7.8% |
| LOAD_ATTR | 1,825,082 | 7.3% |
| CONTAINS_OP | 1,792,578 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 408,716 | 100.0% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,578 | 39.8% |
| CALL | 148,621 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 97,697 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,676,753 | 87.0% |
| LOAD_FAST | 648,063 | 9.9% |
| LOAD_ATTR | 85,280 | 1.3% |
| LOAD_ATTR_SLOT | 83,760 | 1.3% |
| LOAD_CONST | 15,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,576,644 | 39.5% |
| CALL | 1,447,569 | 22.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,421,511 | 21.8% |
| LOAD_CONST | 743,097 | 11.4% |
| LOAD_FAST_LOAD_FAST | 304,635 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,206,154 | 72.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,357,229 | 11.9% |
| LOAD_FAST_LOAD_FAST | 1,216,598 | 10.7% |
| BINARY_SUBSCR | 575,920 | 5.1% |
| LOAD_GLOBAL_MODULE | 28,860 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,757,635 | 50.5% |
| LOAD_FAST | 3,497,530 | 30.7% |
| CALL_PY_WITH_DEFAULTS | 1,241,487 | 10.9% |
| LOAD_FAST_LOAD_FAST | 678,560 | 6.0% |
| LOAD_CONST | 125,755 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,678,096 | 99.9% |
| LOAD_ATTR | 2,821 | 0.1% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,309,165 | 62.7% |
| CALL_PY_WITH_DEFAULTS | 1,216,598 | 33.0% |
| STORE_DEREF | 55,040 | 1.5% |
| LOAD_CONST | 35,840 | 1.0% |
| LOAD_FAST | 28,800 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,257,198 | 70.5% |
| LOAD_FAST_LOAD_FAST | 524,760 | 29.4% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,216,638 | 68.3% |
| UNARY_INVERT | 524,840 | 29.4% |
| RETURN_VALUE | 14,040 | 0.8% |
| LOAD_CONST | 14,040 | 0.8% |
| LOAD_FAST_LOAD_FAST | 5,720 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,525 | 97.3% |
| RETURN_VALUE | 27,440 | 2.6% |
| LOAD_GLOBAL_MODULE | 1,240 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,052,365 | 98.8% |
| TO_BOOL_BOOL | 12,160 | 1.1% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,360 | 98.6% |
| LOAD_ATTR_MODULE | 1,180 | 1.2% |
| RETURN_VALUE | 140 | 0.1% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 83,760 | 84.0% |
| CALL_BUILTIN_FAST | 14,140 | 14.2% |
| LOAD_FAST | 1,040 | 1.0% |
| LOAD_CONST | 600 | 0.6% |
| STORE_FAST | 140 | 0.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,740,050 | 41.9% |
| LOAD_FAST | 1,260,778 | 14.1% |
| STORE_FAST | 1,224,734 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 1,003,382 | 11.2% |
| NOP | 751,202 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,117,464 | 46.1% |
| LOAD_DEREF | 1,835,092 | 20.6% |
| CALL_ISINSTANCE | 1,234,138 | 13.8% |
| LOAD_GLOBAL_BUILTIN | 1,003,382 | 11.2% |
| LOAD_GLOBAL_MODULE | 625,080 | 7.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,017,619 | 28.8% |
| RESUME_CHECK | 3,185,042 | 18.3% |
| NOP | 1,848,549 | 10.6% |
| POP_JUMP_IF_FALSE | 1,493,422 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,454,574 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,912,334 | 22.4% |
| LOAD_ATTR_MODULE | 3,678,096 | 21.1% |
| LOAD_FAST_LOAD_FAST | 2,744,627 | 15.7% |
| LOAD_FAST | 2,208,775 | 12.7% |
| COMPARE_OP_STR | 1,425,587 | 8.2% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,440 | 99.9% |
| LOAD_SUPER_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 89,520 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,745,372 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,230,958 | 70.5% |
| CALL_PY_EXACT_ARGS | 508,814 | 29.1% |
| LOAD_FAST | 5,760 | 0.3% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,773,519 | 33.8% |
| CACHE | 11,871,558 | 31.5% |
| FOR_ITER_GEN | 6,335,920 | 16.8% |
| COPY_FREE_VARS | 1,841,232 | 4.9% |
| CALL_PY_WITH_DEFAULTS | 1,783,982 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,134,110 | 56.0% |
| POP_TOP | 6,913,520 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 3,740,050 | 9.9% |
| LOAD_GLOBAL_MODULE | 3,185,042 | 8.4% |
| NOP | 1,418,378 | 3.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,120,092 | 69.2% |
| LOAD_FAST_LOAD_FAST | 770,594 | 17.1% |
| SWAP | 575,880 | 12.8% |
| LOAD_ATTR_INSTANCE_VALUE | 17,040 | 0.4% |
| STORE_FAST_LOAD_FAST | 14,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,248,976 | 49.9% |
| LOAD_FAST | 940,600 | 20.9% |
| LOAD_GLOBAL_MODULE | 747,434 | 16.6% |
| LOAD_CONST | 302,856 | 6.7% |
| LOAD_FAST_LOAD_FAST | 129,480 | 2.9% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,760 | 85.5% |
| LOAD_FAST_LOAD_FAST | 14,140 | 14.4% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,980 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 1,216,598 | 93.1% |
| LOAD_FAST | 43,906 | 3.4% |
| LOAD_ATTR_INSTANCE_VALUE | 34,680 | 2.7% |
| CALL | 10,200 | 0.8% |
| LOAD_CONST | 1,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,218,964 | 93.3% |
| RETURN_CONST | 32,520 | 2.5% |
| LOAD_GLOBAL_MODULE | 27,720 | 2.1% |
| LOAD_CONST | 27,480 | 2.1% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,938,732 | 27.1% |
| CALL_ISINSTANCE | 1,234,418 | 17.3% |
| RETURN_VALUE | 902,036 | 12.6% |
| CALL | 733,596 | 10.3% |
| LOAD_FAST | 722,143 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,004,569 | 70.0% |
| POP_JUMP_IF_TRUE | 1,885,633 | 26.4% |
| UNARY_NOT | 262,299 | 3.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,957,956 | 54.9% |
| BINARY_OP | 1,216,738 | 22.6% |
| LOAD_FAST | 1,216,598 | 22.6% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,391,672 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520,314 | 92.3% |
| LOAD_ATTR_INSTANCE_VALUE | 42,900 | 7.6% |
| TO_BOOL | 200 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 563,274 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 191,367 | 79.6% |
| LOAD_FAST | 27,900 | 11.6% |
| COPY | 13,880 | 5.8% |
| WITH_EXCEPT_START | 5,680 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 220,727 | 91.8% |
| POP_JUMP_IF_TRUE | 19,700 | 8.2% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 2,000 | 71.4% |
| LOAD_FAST | 620 | 22.1% |
| COPY | 160 | 5.7% |
| LOAD_GLOBAL_MODULE | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,600 | 92.9% |
| POP_JUMP_IF_TRUE | 200 | 7.1% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,087,880 | 93.0% |
| CALL_BUILTIN_FAST | 81,229 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,088,220 | 93.1% |
| STORE_FAST | 81,269 | 6.9% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 581,600 | 26.7% |
| LOAD_FAST_CHECK | 575,920 | 26.5% |
| FOR_ITER_LIST | 525,320 | 24.2% |
| CALL_BUILTIN_FAST | 474,457 | 21.8% |
| CALL | 9,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,167,317 | 99.7% |
| LOAD_FAST | 7,000 | 0.3% |
| STORE_DEREF | 60 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 64.7% |
| COPY | 287 | 31.0% |
| TO_BOOL | 40 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 620 | 66.9% |
| POP_JUMP_IF_FALSE | 307 | 33.1% |


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
|     deferred | 7,285,937 | 77.6% |
|          hit | 2,098,898 | 22.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 8.4% |
| Failure | 6,518 | 91.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,255 | 49.9% |
| or | 1,743 | 26.7% |
| remainder | 780 | 12.0% |
| add different types | 640 | 9.8% |
| add other | 100 | 1.5% |


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
|     deferred | 638,623 | 45.3% |
|          hit | 769,902 | 54.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 21.4% |
| Failure | 880 | 78.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 880 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 11,078,284 | 27.3% |
|          hit | 29,414,832 | 72.6% |
|         miss | 7,840 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,281 | 23.5% |
| Failure | 30,266 | 76.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,919 | 26.2% |
| cfunc noargs | 6,344 | 21.0% |
| class no vectorcall | 4,000 | 13.2% |
| meth descr varargs keywords | 3,220 | 10.6% |
| class mutable | 1,298 | 4.3% |
| other | 1,180 | 3.9% |
| bound method | 1,127 | 3.7% |
| cfunc varargs | 1,100 | 3.6% |
| cfunc varargs keywords | 938 | 3.1% |
| meth descr method fastcall keywords | 920 | 3.0% |
| operator wrapper | 780 | 2.6% |
| cmethod | 640 | 2.1% |
| wrong number arguments | 480 | 1.6% |
| method wrapper | 280 | 0.9% |
| meth descr varargs | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 596,576 | 10.1% |
|          hit | 5,288,069 | 89.7% |
|         miss | 6,671 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,615 | 53.7% |
| Failure | 1,391 | 46.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 817 | 58.7% |
| big int | 360 | 25.9% |
| different types | 214 | 15.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,302,940 | 7.0% |
|          hit | 17,287,653 | 93.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 26.7% |
| Failure | 1,700 | 73.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 520 | 30.6% |
| enumerate | 520 | 30.6% |
| itertools | 400 | 23.5% |
| callable | 260 | 15.3% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,570,408 | 17.5% |
|          hit | 49,608,338 | 82.0% |
|         miss | 311,461 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,463 | 52.1% |
| Failure | 20,617 | 47.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,627 | 22.4% |
| shadowed | 4,299 | 20.9% |
| not managed dict | 3,788 | 18.4% |
| non overriding descriptor | 2,456 | 11.9% |
| has managed dict | 1,120 | 5.4% |
| class attr descriptor | 1,040 | 5.0% |
| metaclass attribute | 960 | 4.7% |
| class method obj | 920 | 4.5% |
| non object slot | 560 | 2.7% |
| class attr simple | 487 | 2.4% |
| mutable class | 280 | 1.4% |
| overridden | 80 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,335 | 0.0% |
|        deopt | 100 | 0.0% |
|          hit | 26,357,310 | 99.9% |
|         miss | 6,671 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,615 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,835,092 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 100.0% |
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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 89,364 | 1.9% |
|          hit | 4,359,226 | 92.6% |
|         miss | 245,260 | 5.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,980 | 78.1% |
| Failure | 2,520 | 21.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 1,180 | 46.8% |
| class attr simple | 560 | 22.2% |
| not in keys | 520 | 20.6% |
| no dict | 260 | 10.3% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 30,340 | 2.3% |
|          hit | 1,306,884 | 97.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 28.3% |
| Failure | 660 | 71.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 440 | 66.7% |
| other | 220 | 33.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,592,508 | 10.7% |
|          hit | 13,351,621 | 89.3% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,001 | 45.0% |
| Failure | 3,667 | 55.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,087 | 29.6% |
| sequence | 880 | 24.0% |
| set | 740 | 20.2% |
| tuple | 740 | 20.2% |
| other | 220 | 6.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 3,343,866 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 326,428,525 | 56.1% |
| Not specialized | 62,119,851 | 10.7% |
| Specialized hits | 192,601,527 | 33.1% |
| Specialized misses | 578,185 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 11,078,284 | 33.4% |
| LOAD_ATTR | 10,570,408 | 31.8% |
| BINARY_OP | 7,285,937 | 21.9% |
| TO_BOOL | 1,592,508 | 4.8% |
| FOR_ITER | 1,302,940 | 3.9% |
| BINARY_SUBSCR | 638,623 | 1.9% |
| COMPARE_OP | 596,576 | 1.8% |
| STORE_ATTR | 89,364 | 0.3% |
| STORE_SUBSCR | 30,340 | 0.1% |
| LOAD_GLOBAL | 8,335 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.4% |
| LOAD_ATTR_INSTANCE_VALUE | 215,938 | 37.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,043 | 14.2% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.1% |
| COMPARE_OP_INT | 6,651 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,380 | 1.1% |
| LOAD_GLOBAL_MODULE | 6,331 | 1.1% |
| LOAD_ATTR_MODULE | 1,100 | 0.2% |
| CALL_PY_EXACT_ARGS | 860 | 0.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 420 | 0.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 11,991,218 | 31.7% |
| Calls to Python functions inlined | 25,776,941 | 68.3% |
| Calls via PyEval_EvalFrame (total) | 11,991,218 | 31.7% |
| Calls via PyEval_EvalFrame (vector) | 11,406,098 | 30.2% |
| Calls via PyEval_EvalFrame (generator) | 585,120 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 11,405,398 | 30.2% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 625,920 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 535,340 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 647,136 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 52,027 | 0.1% |
| Frames pushed | 19,180,261 | 50.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 19,555,418 | 41.9% |
| Frees to freelist | 19,568,116 |  |
| Allocations | 27,156,031 | 58.1% |
| Allocations to 512 bytes | 26,870,732 | 57.5% |
| Allocations to 4 kbytes | 117,306 | 0.3% |
| Allocations over 4 kbytes | 167,993 | 0.4% |
| Frees | 28,673,506 |  |
| New values | 88,020 |  |
| Interpreter increfs | 227,886,017 | 76.9% |
| Interpreter decrefs | 249,907,020 | 73.9% |
| Increfs | 68,506,363 | 23.1% |
| Decrefs | 88,452,957 | 26.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 12,529,909 |  |
| Method cache misses | 36,105 |  |
| Method cache collisions | 96,662 |  |
| Method cache dunder hits | 11,560,572 |  |
| Method cache dunder misses | 64,297 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 39 | 585 | 275,612 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-11-16
