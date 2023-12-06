
# Pystats results

- benchmark: concurrent_imap
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 97,835,648 | 17.9% | 17.9% |  |
| RESUME_CHECK | 37,194,640 | 6.8% | 24.7% | 0.0% |
| STORE_FAST | 28,229,431 | 5.2% | 29.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 24,491,722 | 4.5% | 34.4% | 0.9% |
| POP_TOP | 24,122,739 | 4.4% | 38.8% |  |
| RETURN_VALUE | 22,181,155 | 4.1% | 42.9% |  |
| POP_JUMP_IF_FALSE | 19,088,656 | 3.5% | 46.4% |  |
| LOAD_GLOBAL_MODULE | 15,842,050 | 2.9% | 49.3% | 0.0% |
| LOAD_CONST | 15,061,571 | 2.8% | 52.0% |  |
| LOAD_FAST_LOAD_FAST | 14,958,391 | 2.7% | 54.8% |  |
| CALL_PY_EXACT_ARGS | 12,494,439 | 2.3% | 57.1% | 0.0% |
| INTERPRETER_EXIT | 11,925,362 | 2.2% | 59.2% |  |
| CALL | 10,989,812 | 2.0% | 61.3% |  |
| LOAD_ATTR | 10,440,754 | 1.9% | 63.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,435,456 | 1.9% | 65.1% | 0.8% |
| ENTER_EXECUTOR | 10,152,917 | 1.9% | 66.9% |  |
| RETURN_CONST | 9,298,220 | 1.7% | 68.6% |  |
| NOP | 8,965,273 | 1.6% | 70.3% |  |
| LOAD_GLOBAL_BUILTIN | 7,965,529 | 1.5% | 71.7% | 0.0% |
| JUMP_BACKWARD | 7,853,790 | 1.4% | 73.2% |  |
| COPY | 7,272,447 | 1.3% | 74.5% |  |
| BINARY_OP | 7,134,499 | 1.3% | 75.8% |  |
| YIELD_VALUE | 6,913,660 | 1.3% | 77.1% |  |
| TO_BOOL_BOOL | 6,791,385 | 1.2% | 78.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,411,216 | 1.2% | 79.5% |  |
| FOR_ITER_GEN | 6,347,440 | 1.2% | 80.7% |  |
| PUSH_NULL | 5,699,797 | 1.0% | 81.7% |  |
| TO_BOOL_INT | 5,271,386 | 1.0% | 82.7% |  |
| POP_JUMP_IF_NOT_NONE | 5,079,537 | 0.9% | 83.6% |  |
| STORE_FAST_STORE_FAST | 4,839,551 | 0.9% | 84.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 4,304,524 | 0.8% | 85.3% | 4.6% |
| BUILD_TUPLE | 4,302,797 | 0.8% | 86.1% |  |
| COMPARE_OP_INT | 3,757,865 | 0.7% | 86.8% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 2,956,065 | 0.5% | 87.3% |  |
| POP_JUMP_IF_TRUE | 2,723,743 | 0.5% | 87.8% |  |
| SWAP | 2,636,632 | 0.5% | 88.3% |  |
| CALL_FUNCTION_EX | 2,413,955 | 0.4% | 88.7% |  |
| GET_ITER | 2,401,619 | 0.4% | 89.2% |  |
| LOAD_ATTR_MODULE | 2,364,788 | 0.4% | 89.6% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,152,231 | 0.4% | 90.0% |  |
| FOR_ITER_LIST | 2,083,617 | 0.4% | 90.4% |  |
| CALL_BUILTIN_CLASS | 2,028,780 | 0.4% | 90.7% |  |
| LOAD_DEREF | 1,853,702 | 0.3% | 91.1% |  |
| BEFORE_WITH | 1,841,349 | 0.3% | 91.4% |  |
| COPY_FREE_VARS | 1,803,682 | 0.3% | 91.8% |  |
| CONTAINS_OP | 1,763,575 | 0.3% | 92.1% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,744,068 | 0.3% | 92.4% |  |
| LOAD_SUPER_ATTR_METHOD | 1,707,362 | 0.3% | 92.7% |  |
| UNARY_INVERT | 1,703,408 | 0.3% | 93.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,690,849 | 0.3% | 93.3% | 0.0% |
| JUMP_FORWARD | 1,689,942 | 0.3% | 93.6% |  |
| BUILD_MAP | 1,678,716 | 0.3% | 93.9% |  |
| CALL_BUILTIN_FAST | 1,604,262 | 0.3% | 94.2% |  |
| TO_BOOL | 1,589,208 | 0.3% | 94.5% |  |
| BUILD_LIST | 1,533,141 | 0.3% | 94.8% |  |
| COMPARE_OP_STR | 1,486,309 | 0.3% | 95.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,484,058 | 0.3% | 95.4% |  |
| FOR_ITER | 1,305,260 | 0.2% | 95.6% |  |
| STORE_SUBSCR_DICT | 1,280,584 | 0.2% | 95.8% |  |
| STORE_FAST_LOAD_FAST | 1,280,240 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 1,207,186 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 1,169,513 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,131,873 | 0.2% | 96.7% | 0.0% |
| POP_JUMP_IF_NONE | 1,121,273 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 1,109,569 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 1,064,412 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,064,412 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 1,042,920 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 964,019 | 0.2% | 97.9% | 0.0% |
| LOAD_FAST_CHECK | 834,420 | 0.2% | 98.0% |  |
| LIST_APPEND | 831,351 | 0.2% | 98.2% |  |
| LOAD_FAST_AND_CLEAR | 769,460 | 0.1% | 98.3% |  |
| BINARY_SUBSCR | 636,353 | 0.1% | 98.4% |  |
| CALL_LEN | 630,744 | 0.1% | 98.6% |  |
| COMPARE_OP | 589,055 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 583,120 | 0.1% | 98.8% |  |
| DICT_MERGE | 564,260 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 552,496 | 0.1% | 99.0% |  |
| LIST_EXTEND | 482,316 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 408,992 | 0.1% | 99.1% |  |
| CALL_KW | 357,252 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 329,619 | 0.1% | 99.3% |  |
| UNARY_NOT | 283,309 | 0.1% | 99.3% |  |
| CALL_LIST_APPEND | 268,931 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 268,316 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 257,678 | 0.0% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 252,378 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 241,105 | 0.0% | 99.5% |  |
| TO_BOOL_NONE | 240,500 | 0.0% | 99.6% | 0.1% |
| MAKE_CELL | 137,900 | 0.0% | 99.6% |  |
| STORE_DEREF | 137,620 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 126,920 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 114,880 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 112,600 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 112,600 | 0.0% | 99.7% |  |
| STORE_ATTR | 100,146 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 97,980 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 97,980 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 91,493 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 0.0% | 99.8% |  |
| DELETE_ATTR | 86,394 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 78,218 | 0.0% | 99.8% | 8.2% |
| DELETE_SUBSCR | 78,216 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 63,640 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 55,680 | 0.0% | 99.9% |  |
| POP_EXCEPT | 48,493 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 48,493 | 0.0% | 99.9% |  |
| IS_OP | 46,655 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 42,733 | 0.0% | 99.9% |  |
| BUILD_STRING | 41,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 39,160 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 39,000 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 38,380 | 0.0% | 99.9% |  |
| IMPORT_NAME | 33,760 | 0.0% | 100.0% |  |
| IMPORT_FROM | 33,420 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 31,260 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 28,160 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 27,480 | 0.0% | 100.0% |  |
| BINARY_SLICE | 19,820 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 18,900 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,770 | 0.0% | 100.0% |  |
| RERAISE | 17,280 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 14,500 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,900 | 0.0% | 100.0% |  |
| END_FOR | 11,520 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,940 | 0.0% | 100.0% | 0.0% |
| RAISE_VARARGS | 5,780 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,760 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 3,420 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,660 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 1,440 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 1,004 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,130,691 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 20,759,816 | 3.8% | 7.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 12,447,879 | 2.3% | 10.1% |
| STORE_FAST LOAD_FAST | 11,980,546 | 2.2% | 12.3% |
| CACHE RESUME_CHECK | 11,811,484 | 2.2% | 14.5% |
| LOAD_FAST RETURN_VALUE | 10,756,774 | 2.0% | 16.5% |
| RETURN_VALUE INTERPRETER_EXIT | 10,454,292 | 1.9% | 18.4% |
| LOAD_FAST LOAD_ATTR | 8,016,985 | 1.5% | 19.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,676,695 | 1.4% | 21.3% |
| POP_TOP ENTER_EXECUTOR | 7,552,382 | 1.4% | 22.6% |
| POP_TOP LOAD_FAST | 7,538,839 | 1.4% | 24.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 7,280,215 | 1.3% | 25.4% |
| RESUME_CHECK POP_TOP | 6,913,520 | 1.3% | 26.6% |
| RETURN_CONST POP_TOP | 6,581,728 | 1.2% | 27.8% |
| JUMP_BACKWARD FOR_ITER_GEN | 6,335,920 | 1.2% | 29.0% |
| YIELD_VALUE STORE_FAST | 6,335,920 | 1.2% | 30.1% |
| FOR_ITER_GEN RESUME_CHECK | 6,335,920 | 1.2% | 31.3% |
| STORE_FAST JUMP_BACKWARD | 5,760,000 | 1.1% | 32.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,587,860 | 1.0% | 33.4% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,569,425 | 1.0% | 34.4% |
| NOP LOAD_FAST | 5,295,187 | 1.0% | 35.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 5,271,246 | 1.0% | 36.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,257,551 | 1.0% | 37.3% |
| ENTER_EXECUTOR YIELD_VALUE | 5,183,440 | 0.9% | 38.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,666,263 | 0.9% | 39.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 4,211,249 | 0.8% | 39.9% |
| STORE_FAST NOP | 3,839,019 | 0.7% | 40.6% |
| LOAD_GLOBAL_MODULE BINARY_OP | 3,824,709 | 0.7% | 41.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,812,072 | 0.7% | 42.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,754,004 | 0.7% | 42.7% |
| LOAD_CONST LOAD_CONST | 3,731,926 | 0.7% | 43.4% |
| LOAD_FAST LOAD_CONST | 3,727,341 | 0.7% | 44.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,717,473 | 0.7% | 44.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,674,428 | 0.7% | 45.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,661,879 | 0.7% | 46.1% |
| LOAD_ATTR LOAD_FAST | 3,511,371 | 0.6% | 46.7% |
| PUSH_NULL LOAD_FAST | 3,479,780 | 0.6% | 47.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 3,156,910 | 0.6% | 47.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 3,130,740 | 0.6% | 48.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,932,898 | 0.5% | 49.0% |
| BINARY_OP COPY | 2,892,674 | 0.5% | 49.6% |
| COPY TO_BOOL_INT | 2,892,354 | 0.5% | 50.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,728,958 | 0.5% | 50.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,678,890 | 0.5% | 51.1% |
| CALL STORE_FAST | 2,649,679 | 0.5% | 51.6% |
| COPY STORE_FAST | 2,630,400 | 0.5% | 52.0% |
| STORE_FAST COPY | 2,629,760 | 0.5% | 52.5% |
| LOAD_CONST CALL | 2,586,475 | 0.5% | 53.0% |
| LOAD_FAST PUSH_NULL | 2,577,811 | 0.5% | 53.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,526,982 | 0.5% | 53.9% |
| CALL RETURN_VALUE | 2,492,226 | 0.5% | 54.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,403,227 | 0.4% | 54.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,361,547 | 0.4% | 55.3% |
| RETURN_VALUE STORE_FAST | 2,308,085 | 0.4% | 55.7% |
| CALL POP_TOP | 2,263,328 | 0.4% | 56.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 2,205,784 | 0.4% | 56.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,164,680 | 0.4% | 56.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,145,211 | 0.4% | 57.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 2,063,904 | 0.4% | 57.7% |
| LOAD_CONST COMPARE_OP_INT | 2,055,969 | 0.4% | 58.1% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,035,426 | 0.4% | 58.4% |
| RETURN_VALUE RETURN_VALUE | 1,993,041 | 0.4% | 58.8% |
| POP_TOP RETURN_CONST | 1,905,027 | 0.3% | 59.1% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,883,535 | 0.3% | 59.5% |
| LOAD_FAST CALL_FUNCTION_EX | 1,849,675 | 0.3% | 59.8% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,841,893 | 0.3% | 60.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,814,253 | 0.3% | 60.5% |
| NOP LOAD_GLOBAL_MODULE | 1,809,960 | 0.3% | 60.8% |
| COPY_FREE_VARS RESUME_CHECK | 1,803,022 | 0.3% | 61.2% |
| LOAD_DEREF LOAD_FAST | 1,797,402 | 0.3% | 61.5% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,796,882 | 0.3% | 61.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,766,799 | 0.3% | 62.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,762,955 | 0.3% | 62.5% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,762,295 | 0.3% | 62.8% |
| LOAD_FAST BUILD_TUPLE | 1,750,666 | 0.3% | 63.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,738,873 | 0.3% | 63.4% |
| POP_TOP LOAD_CONST | 1,736,869 | 0.3% | 63.7% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,710,907 | 0.3% | 64.1% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,707,162 | 0.3% | 64.4% |
| UNARY_INVERT BINARY_OP | 1,703,408 | 0.3% | 64.7% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,687,342 | 0.3% | 65.0% |
| ENTER_EXECUTOR CALL | 1,635,922 | 0.3% | 65.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,602,422 | 0.3% | 65.6% |
| LOAD_CONST LOAD_FAST | 1,600,791 | 0.3% | 65.9% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,590,384 | 0.3% | 66.2% |
| GET_ITER FOR_ITER_LIST | 1,580,712 | 0.3% | 66.5% |
| POP_TOP NOP | 1,577,073 | 0.3% | 66.7% |
| LOAD_FAST TO_BOOL | 1,527,752 | 0.3% | 67.0% |
| LOAD_FAST GET_ITER | 1,525,281 | 0.3% | 67.3% |
| RETURN_VALUE POP_TOP | 1,511,370 | 0.3% | 67.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,495,875 | 0.3% | 67.9% |
| POP_JUMP_IF_FALSE POP_TOP | 1,489,474 | 0.3% | 68.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,466,004 | 0.3% | 68.4% |
| BINARY_OP STORE_FAST | 1,460,757 | 0.3% | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,448,864 | 0.3% | 68.9% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,447,298 | 0.3% | 69.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,437,359 | 0.3% | 69.5% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,420,189 | 0.3% | 69.7% |
| RESUME_CHECK NOP | 1,390,966 | 0.3% | 70.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,383,350 | 0.3% | 70.2% |


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
| RESUME_CHECK | 11,811,484 | 99.0% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,248,533 | 67.8% |
| RETURN_VALUE | 498,336 | 27.1% |
| LOAD_GLOBAL_MODULE | 82,438 | 4.5% |
| CALL | 6,360 | 0.3% |
| ENTER_EXECUTOR | 5,182 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,337,353 | 72.6% |
| STORE_FAST | 503,996 | 27.4% |


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
| LOAD_FAST_LOAD_FAST | 576,080 | 90.5% |
| LOAD_CONST | 59,313 | 9.3% |
| BINARY_SUBSCR | 880 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 575,920 | 90.5% |
| STORE_FAST | 59,033 | 9.3% |
| BINARY_SUBSCR | 880 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 37,573 | 87.9% |
| LOAD_ATTR_MODULE | 5,100 | 11.9% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 42,733 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,898 | 48.5% |
| CALL | 27,518 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,715 | 16.3% |
| LOAD_ATTR | 85 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60,798 | 77.7% |
| RETURN_CONST | 10,238 | 13.1% |
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
| RETURN_CONST | 1,064,412 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,064,412 | 100.0% |


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
| LOAD_FAST | 1,525,281 | 63.5% |
| STORE_FAST_LOAD_FAST | 576,000 | 24.0% |
| CALL_BUILTIN_CLASS | 272,798 | 11.4% |
| CALL | 14,340 | 0.6% |
| RETURN_VALUE | 5,760 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,580,712 | 65.8% |
| LOAD_FAST_AND_CLEAR | 512,389 | 21.3% |
| FOR_ITER_RANGE | 265,882 | 11.1% |
| FOR_ITER | 12,116 | 0.5% |
| FOR_ITER_TUPLE | 11,740 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,454,292 | 87.7% |
| RETURN_CONST | 893,330 | 7.5% |
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
| LOAD_CONST | 63,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 39,000 | 61.3% |
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
| STORE_FAST | 3,839,019 | 42.8% |
| POP_TOP | 1,577,073 | 17.6% |
| RESUME_CHECK | 1,390,966 | 15.5% |
| POP_JUMP_IF_FALSE | 1,342,524 | 15.0% |
| POP_JUMP_IF_NOT_NONE | 507,013 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,295,187 | 59.1% |
| LOAD_GLOBAL_MODULE | 1,809,960 | 20.2% |
| LOAD_GLOBAL_BUILTIN | 734,866 | 8.2% |
| LOAD_FAST_LOAD_FAST | 583,320 | 6.5% |
| LOAD_CONST | 530,020 | 5.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 31,473 | 64.9% |
| COPY | 11,520 | 23.8% |
| POP_TOP | 5,200 | 10.7% |
| STORE_FAST | 280 | 0.6% |
| STORE_SUBSCR_DICT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 31,073 | 64.1% |
| RERAISE | 11,520 | 23.8% |
| JUMP_FORWARD | 5,120 | 10.6% |
| JUMP_BACKWARD | 700 | 1.4% |
| RETURN_CONST | 60 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,913,520 | 28.7% |
| RETURN_CONST | 6,581,728 | 27.3% |
| CALL | 2,263,328 | 9.4% |
| RETURN_VALUE | 1,511,370 | 6.3% |
| POP_JUMP_IF_FALSE | 1,489,474 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,552,382 | 31.3% |
| LOAD_FAST | 7,538,839 | 31.3% |
| RETURN_CONST | 1,905,027 | 7.9% |
| LOAD_CONST | 1,736,869 | 7.2% |
| NOP | 1,577,073 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 37,193 | 76.7% |
| RERAISE | 5,760 | 11.9% |
| CALL_KW | 5,120 | 10.6% |
| BINARY_SUBSCR_DICT | 300 | 0.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 37,533 | 77.4% |
| WITH_EXCEPT_START | 5,760 | 11.9% |
| LOAD_GLOBAL_MODULE | 5,080 | 10.5% |
| LOAD_GLOBAL | 120 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,577,811 | 45.2% |
| LOAD_ATTR_MODULE | 1,710,907 | 30.0% |
| LOAD_ATTR | 1,284,359 | 22.5% |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,479,780 | 61.1% |
| CALL | 1,009,840 | 17.7% |
| LOAD_FAST_LOAD_FAST | 820,926 | 14.4% |
| LOAD_CONST | 315,613 | 5.5% |
| CALL_PY_EXACT_ARGS | 49,320 | 0.9% |


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
| LOAD_FAST | 10,756,774 | 48.5% |
| CALL | 2,492,226 | 11.2% |
| RETURN_VALUE | 1,993,041 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,590,384 | 7.2% |
| CALL_FUNCTION_EX | 1,265,495 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 10,454,292 | 47.1% |
| STORE_FAST | 2,308,085 | 10.4% |
| RETURN_VALUE | 1,993,041 | 9.0% |
| POP_TOP | 1,511,370 | 6.8% |
| LOAD_FAST_LOAD_FAST | 1,189,266 | 5.4% |


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
| LOAD_FAST | 1,527,752 | 96.1% |
| LOAD_ATTR_INSTANCE_VALUE | 53,457 | 3.4% |
| TO_BOOL | 3,668 | 0.2% |
| RETURN_VALUE | 927 | 0.1% |
| LOAD_ATTR | 844 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 845,735 | 53.2% |
| POP_JUMP_IF_FALSE | 736,763 | 46.4% |
| TO_BOOL | 3,668 | 0.2% |
| TO_BOOL_BOOL | 2,122 | 0.1% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,189,266 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 514,062 | 30.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,703,408 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 283,229 | 100.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 283,309 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 3,824,709 | 53.6% |
| UNARY_INVERT | 1,703,408 | 23.9% |
| POP_JUMP_IF_FALSE | 1,189,266 | 16.7% |
| LOAD_ATTR | 271,171 | 3.8% |
| LOAD_FAST_LOAD_FAST | 84,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,892,674 | 40.5% |
| STORE_FAST | 1,460,757 | 20.5% |
| TO_BOOL_INT | 1,189,326 | 16.7% |
| UNARY_INVERT | 1,189,266 | 16.7% |
| BUILD_TUPLE | 257,071 | 3.6% |


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
| SWAP | 512,389 | 33.4% |
| JUMP_FORWARD | 498,096 | 32.5% |
| LOAD_FAST | 257,738 | 16.8% |
| POP_TOP | 240,378 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,336 | 33.6% |
| SWAP | 512,389 | 33.4% |
| STORE_FAST | 499,556 | 32.6% |
| RETURN_VALUE | 5,120 | 0.3% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 576,000 | 34.3% |
| LOAD_FAST | 529,560 | 31.5% |
| RESUME_CHECK | 508,296 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 17,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,085,416 | 64.7% |
| BUILD_TUPLE | 576,020 | 34.3% |
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
| LOAD_FAST | 1,750,666 | 40.7% |
| LOAD_FAST_LOAD_FAST | 1,160,320 | 27.0% |
| BUILD_MAP | 576,020 | 13.4% |
| RETURN_VALUE | 512,000 | 11.9% |
| BINARY_OP | 257,071 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,190,826 | 27.7% |
| YIELD_VALUE | 1,152,060 | 26.8% |
| BUILD_MAP | 576,000 | 13.4% |
| STORE_FAST | 512,000 | 11.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 11.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,586,475 | 23.5% |
| ENTER_EXECUTOR | 1,635,922 | 14.9% |
| LOAD_ATTR_METHOD_NO_DICT | 1,437,359 | 13.1% |
| LOAD_FAST_LOAD_FAST | 1,354,045 | 12.3% |
| BUILD_TUPLE | 1,190,826 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,649,679 | 24.1% |
| RETURN_VALUE | 2,492,226 | 22.7% |
| POP_TOP | 2,263,328 | 20.6% |
| LOAD_FAST | 1,049,354 | 9.5% |
| TO_BOOL_BOOL | 729,360 | 6.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,849,675 | 76.6% |
| DICT_MERGE | 564,260 | 23.4% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,265,495 | 52.4% |
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
| LOAD_CONST | 351,812 | 98.5% |
| ENTER_EXECUTOR | 5,440 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 287,658 | 80.5% |
| LOAD_FAST | 28,800 | 8.1% |
| RETURN_VALUE | 21,120 | 5.9% |
| STORE_FAST | 14,220 | 4.0% |
| PUSH_EXC_INFO | 5,120 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 584,672 | 99.3% |
| COMPARE_OP | 1,318 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,128 | 0.2% |
| LOAD_GLOBAL_MODULE | 380 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 585,759 | 99.4% |
| COMPARE_OP | 1,318 | 0.2% |
| COMPARE_OP_INT | 1,178 | 0.2% |
| COMPARE_OP_STR | 440 | 0.1% |
| POP_JUMP_IF_TRUE | 280 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,762,295 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,762,955 | 100.0% |
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
| BINARY_OP | 2,892,674 | 39.8% |
| STORE_FAST | 2,629,760 | 36.2% |
| LOAD_CONST | 1,100,800 | 15.1% |
| LOAD_FAST | 587,229 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 21,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,892,354 | 39.8% |
| STORE_FAST | 2,630,400 | 36.2% |
| STORE_FAST_STORE_FAST | 1,093,760 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 573,009 | 7.9% |
| LOAD_FAST | 28,160 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,189,266 | 65.9% |
| CALL_ALLOC_AND_ENTER_INIT | 498,056 | 27.6% |
| CACHE | 109,900 | 6.1% |
| CALL | 5,940 | 0.3% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,803,022 | 100.0% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,394 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,596 | 66.7% |
| RETURN_CONST | 27,518 | 31.9% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,552,382 | 74.4% |
| POP_JUMP_IF_NOT_NONE | 992,456 | 9.8% |
| LIST_APPEND | 717,691 | 7.1% |
| STORE_FAST_STORE_FAST | 575,320 | 5.7% |
| CALL_LIST_APPEND | 256,391 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,183,440 | 51.1% |
| CALL | 1,635,922 | 16.1% |
| LOAD_FAST | 1,004,811 | 9.9% |
| CALL_PY_WITH_DEFAULTS | 690,970 | 6.8% |
| JUMP_BACKWARD | 575,960 | 5.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,271,224 | 97.4% |
| SWAP | 14,160 | 1.1% |
| GET_ITER | 12,116 | 0.9% |
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
| RETURN_VALUE | 27,520 | 59.0% |
| LOAD_FAST | 17,420 | 37.3% |
| LOAD_GLOBAL_MODULE | 1,675 | 3.6% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,515 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,760,000 | 73.3% |
| POP_TOP | 1,158,345 | 14.7% |
| ENTER_EXECUTOR | 575,960 | 7.3% |
| POP_JUMP_IF_FALSE | 235,285 | 3.0% |
| LIST_APPEND | 113,660 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 6,335,920 | 80.7% |
| FOR_ITER | 1,271,224 | 16.2% |
| LOAD_FAST | 235,680 | 3.0% |
| FOR_ITER_LIST | 5,176 | 0.1% |
| FOR_ITER_RANGE | 2,234 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,068,322 | 63.2% |
| POP_TOP | 603,400 | 35.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,020 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 5,720 | 0.3% |
| POP_EXCEPT | 5,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,116,915 | 66.1% |
| BUILD_LIST | 498,096 | 29.5% |
| POP_EXCEPT | 31,473 | 1.9% |
| LOAD_GLOBAL_MODULE | 24,818 | 1.5% |
| LOAD_FAST_LOAD_FAST | 7,320 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 460,760 | 55.4% |
| LOAD_ATTR | 257,091 | 30.9% |
| BINARY_SUBSCR_STR_INT | 112,600 | 13.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 717,691 | 86.3% |
| JUMP_BACKWARD | 113,660 | 13.7% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,798 | 50.1% |
| RETURN_VALUE | 240,378 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,018 | 50.0% |
| STORE_FAST | 240,378 | 49.8% |
| RETURN_VALUE | 640 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,016,985 | 76.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,814,253 | 17.4% |
| LOAD_GLOBAL_MODULE | 397,299 | 3.8% |
| CALL | 83,860 | 0.8% |
| ENTER_EXECUTOR | 64,160 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,511,371 | 33.6% |
| PUSH_NULL | 1,284,359 | 12.3% |
| STORE_SUBSCR_DICT | 1,189,186 | 11.4% |
| POP_JUMP_IF_NOT_NONE | 1,151,617 | 11.0% |
| STORE_FAST | 742,582 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,731,926 | 24.8% |
| LOAD_FAST | 3,727,341 | 24.7% |
| POP_TOP | 1,736,869 | 11.5% |
| POP_JUMP_IF_FALSE | 919,802 | 6.1% |
| LOAD_ATTR_METHOD_NO_DICT | 733,615 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,731,926 | 24.8% |
| CALL | 2,586,475 | 17.2% |
| COMPARE_OP_INT | 2,055,969 | 13.7% |
| LOAD_FAST | 1,600,791 | 10.6% |
| COPY | 1,100,800 | 7.3% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,796,882 | 96.9% |
| POP_JUMP_IF_NOT_NONE | 27,520 | 1.5% |
| STORE_DEREF | 27,520 | 1.5% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,797,402 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 55,040 | 3.0% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,759,816 | 21.2% |
| STORE_FAST | 11,980,546 | 12.2% |
| POP_JUMP_IF_FALSE | 7,676,695 | 7.8% |
| POP_TOP | 7,538,839 | 7.7% |
| NOP | 5,295,187 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,130,691 | 22.6% |
| RETURN_VALUE | 10,756,774 | 11.0% |
| LOAD_ATTR | 8,016,985 | 8.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,280,215 | 7.4% |
| CALL_PY_EXACT_ARGS | 5,257,551 | 5.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 512,389 | 66.6% |
| LOAD_FAST_AND_CLEAR | 257,071 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 512,389 | 66.6% |
| LOAD_FAST_AND_CLEAR | 257,071 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 576,560 | 69.1% |
| POP_JUMP_IF_NONE | 241,025 | 28.9% |
| LOAD_ATTR_CLASS | 16,515 | 2.0% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 69.0% |
| LOAD_GLOBAL_MODULE | 240,945 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 16,475 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,678,890 | 17.9% |
| LOAD_FAST_LOAD_FAST | 2,063,904 | 13.8% |
| POP_JUMP_IF_FALSE | 1,495,875 | 10.0% |
| LOAD_SUPER_ATTR_METHOD | 1,203,546 | 8.0% |
| RETURN_VALUE | 1,189,266 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,661,879 | 24.5% |
| LOAD_FAST_LOAD_FAST | 2,063,904 | 13.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,738,873 | 11.6% |
| CALL | 1,354,045 | 9.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,189,186 | 7.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.3% |
| RESUME_CHECK | 1,720 | 9.7% |
| POP_JUMP_IF_FALSE | 1,706 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,781 | 38.2% |
| LOAD_ATTR | 3,324 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 2,741 | 15.4% |
| LOAD_FAST | 2,164 | 12.2% |
| CALL | 700 | 3.9% |


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
| TO_BOOL_INT | 5,271,246 | 27.6% |
| TO_BOOL_BOOL | 4,666,263 | 24.4% |
| COMPARE_OP_INT | 3,754,004 | 19.7% |
| CONTAINS_OP | 1,762,955 | 9.2% |
| COMPARE_OP_STR | 1,447,298 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,676,695 | 40.2% |
| RETURN_CONST | 3,156,910 | 16.5% |
| LOAD_FAST_LOAD_FAST | 1,495,875 | 7.8% |
| POP_TOP | 1,489,474 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,466,004 | 7.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,060,753 | 94.6% |
| LOAD_ATTR_INSTANCE_VALUE | 30,560 | 2.7% |
| LOAD_ATTR | 28,260 | 2.5% |
| RETURN_VALUE | 1,400 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 294,502 | 26.3% |
| NOP | 278,298 | 24.8% |
| LOAD_FAST | 257,533 | 23.0% |
| LOAD_FAST_CHECK | 241,025 | 21.5% |
| RETURN_CONST | 24,340 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,403,227 | 47.3% |
| LOAD_ATTR | 1,151,617 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 986,757 | 19.4% |
| RETURN_VALUE | 461,400 | 9.1% |
| LOAD_DEREF | 55,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,035,426 | 40.1% |
| RETURN_CONST | 1,151,921 | 22.7% |
| ENTER_EXECUTOR | 992,456 | 19.5% |
| NOP | 507,013 | 10.0% |
| LOAD_CONST | 240,658 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,841,893 | 67.6% |
| TO_BOOL | 845,735 | 31.1% |
| TO_BOOL_NONE | 19,700 | 0.7% |
| COMPARE_OP_STR | 10,931 | 0.4% |
| COMPARE_OP_INT | 3,464 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 955,391 | 35.1% |
| LOAD_FAST_LOAD_FAST | 848,571 | 31.2% |
| RETURN_CONST | 735,082 | 27.0% |
| LOAD_GLOBAL_MODULE | 71,350 | 2.6% |
| RETURN_VALUE | 58,993 | 2.2% |


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
| POP_JUMP_IF_FALSE | 3,156,910 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 2,205,784 | 23.7% |
| POP_TOP | 1,905,027 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 1,151,921 | 12.4% |
| POP_JUMP_IF_TRUE | 735,082 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,581,728 | 70.8% |
| EXIT_INIT_CHECK | 1,064,412 | 11.4% |
| INTERPRETER_EXIT | 893,330 | 9.6% |
| TO_BOOL_BOOL | 660,461 | 7.1% |
| STORE_FAST | 60,833 | 0.7% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 39,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 37,920 | 97.2% |
| STORE_NAME | 780 | 2.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.7% |
| LOAD_FAST | 20 | 0.1% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,926 | 57.8% |
| LOAD_FAST_LOAD_FAST | 22,040 | 22.0% |
| LOAD_ATTR_INSTANCE_VALUE | 17,280 | 17.3% |
| STORE_ATTR | 2,440 | 2.4% |
| LOAD_ATTR | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 44,840 | 44.8% |
| LOAD_FAST_LOAD_FAST | 14,760 | 14.7% |
| LOAD_FAST | 13,580 | 13.6% |
| LOAD_CONST | 12,325 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 5,680 | 5.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 55,040 | 40.0% |
| LOAD_GLOBAL_MODULE | 55,040 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 27,520 | 20.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |

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
| YIELD_VALUE | 6,335,920 | 22.4% |
| CALL | 2,649,679 | 9.4% |
| COPY | 2,630,400 | 9.3% |
| RETURN_VALUE | 2,308,085 | 8.2% |
| BINARY_OP | 1,460,757 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,980,546 | 42.4% |
| JUMP_BACKWARD | 5,760,000 | 20.4% |
| NOP | 3,839,019 | 13.6% |
| COPY | 2,629,760 | 9.3% |
| JUMP_FORWARD | 1,068,322 | 3.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 688,680 | 53.8% |
| FOR_ITER_LIST | 576,620 | 45.0% |
| COPY | 14,080 | 1.1% |
| FOR_ITER_TUPLE | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 576,600 | 45.0% |
| GET_ITER | 576,000 | 45.0% |
| LOAD_FAST | 112,640 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 14,000 | 1.1% |
| TO_BOOL_STR | 860 | 0.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,145,211 | 44.3% |
| COPY | 1,093,760 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 1,088,220 | 22.5% |
| STORE_FAST_STORE_FAST | 512,000 | 10.6% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,602,422 | 33.1% |
| STORE_FAST | 1,088,280 | 22.5% |
| LOAD_FAST_LOAD_FAST | 1,039,589 | 21.5% |
| ENTER_EXECUTOR | 575,320 | 11.9% |
| STORE_FAST_STORE_FAST | 512,000 | 10.6% |


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
| BINARY_OP_ADD_INT | 573,069 | 21.7% |
| BUILD_LIST | 512,389 | 19.4% |
| LOAD_FAST_AND_CLEAR | 512,389 | 19.4% |
| ENTER_EXECUTOR | 497,349 | 18.9% |
| LOAD_FAST | 268,825 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 573,009 | 21.7% |
| LOAD_CONST | 525,896 | 19.9% |
| BUILD_LIST | 512,389 | 19.4% |
| STORE_FAST | 512,389 | 19.4% |
| FOR_ITER_LIST | 497,369 | 18.9% |


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
| ENTER_EXECUTOR | 5,183,440 | 75.0% |
| BUILD_TUPLE | 1,152,060 | 16.7% |
| STORE_FAST_LOAD_FAST | 576,600 | 8.3% |
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
| CALL | 2,780 | 46.8% |
| CACHE | 2,280 | 38.4% |
| COPY_FREE_VARS | 320 | 5.4% |
| CALL_KW | 200 | 3.4% |
| POP_TOP | 140 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,840 | 47.8% |
| LOAD_GLOBAL | 1,520 | 25.6% |
| LOAD_NAME | 560 | 9.4% |
| NOP | 280 | 4.7% |
| LOAD_CONST | 240 | 4.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 257,638 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 257,678 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,090,929 | 98.3% |
| LOAD_FAST_LOAD_FAST | 18,480 | 1.7% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 573,069 | 51.6% |
| STORE_FAST | 511,980 | 46.1% |
| BINARY_SLICE | 18,520 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,680 | 0.5% |
| LOAD_CONST | 280 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 36.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,240 | 36.3% |
| LOAD_FAST_LOAD_FAST | 600 | 17.5% |
| BINARY_SUBSCR_LIST_INT | 280 | 8.2% |
| BINARY_OP | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,740 | 50.9% |
| LOAD_CONST | 1,260 | 36.8% |
| STORE_FAST | 300 | 8.8% |
| CALL | 120 | 3.5% |


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
| CALL | 240,945 | 99.9% |
| BINARY_OP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 241,105 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,826 | 80.3% |
| LOAD_CONST | 58,913 | 17.9% |
| CALL_LEN | 5,680 | 1.7% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 323,899 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 240,618 | 95.3% |
| LOAD_CONST | 11,640 | 4.6% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,658 | 95.4% |
| LOAD_CONST | 11,440 | 4.5% |
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
| LOAD_GLOBAL_MODULE | 525,496 | 49.4% |
| LOAD_FAST | 505,076 | 47.5% |
| CALL | 33,420 | 3.1% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 566,356 | 53.2% |
| COPY_FREE_VARS | 498,056 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,240 | 82.1% |
| LOAD_CONST | 7,000 | 8.9% |
| BINARY_OP_ADD_INT | 5,680 | 7.3% |
| PUSH_NULL | 1,018 | 1.3% |
| CALL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 71,818 | 91.8% |
| POP_TOP | 6,280 | 8.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 728,406 | 35.9% |
| CALL_FUNCTION_EX | 511,960 | 25.2% |
| LOAD_FAST | 275,418 | 13.6% |
| CALL_BUILTIN_CLASS | 240,298 | 11.8% |
| CALL_LEN | 240,298 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 769,658 | 37.9% |
| STORE_FAST | 728,706 | 35.9% |
| GET_ITER | 272,798 | 13.4% |
| CALL_BUILTIN_CLASS | 240,298 | 11.8% |
| LOAD_FAST | 17,280 | 0.9% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,325 | 55.7% |
| LOAD_CONST | 398,578 | 24.8% |
| LOAD_FAST_LOAD_FAST | 173,186 | 10.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 81,253 | 5.1% |
| LOAD_GLOBAL_MODULE | 27,880 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 594,237 | 37.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 463,549 | 28.9% |
| TO_BOOL_BOOL | 388,518 | 24.2% |
| UNPACK_SEQUENCE_TUPLE | 81,253 | 5.1% |
| POP_TOP | 14,925 | 0.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,020 | 45.8% |
| BUILD_TUPLE | 511,960 | 45.2% |
| CALL | 64,998 | 5.7% |
| LOAD_FAST_CHECK | 16,475 | 1.5% |
| LOAD_ATTR | 14,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,047,820 | 92.6% |
| RETURN_VALUE | 82,153 | 7.3% |
| LOAD_FAST | 1,260 | 0.1% |
| STORE_FAST | 440 | 0.0% |
| BEFORE_WITH | 140 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 112,560 | 88.7% |
| LOAD_FAST | 14,280 | 11.3% |
| CALL | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 112,560 | 88.7% |
| LOAD_FAST | 14,040 | 11.1% |
| STORE_FAST | 140 | 0.1% |
| TO_BOOL_INT | 140 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,206,726 | 100.0% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,207,006 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 602,463 | 95.5% |
| LOAD_ATTR_INSTANCE_VALUE | 27,900 | 4.4% |
| CALL | 381 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 344,266 | 54.6% |
| CALL_BUILTIN_CLASS | 240,298 | 38.1% |
| CALL_PY_EXACT_ARGS | 33,160 | 5.3% |
| LOAD_FAST | 5,720 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 5,680 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 256,991 | 95.6% |
| LOAD_FAST | 11,440 | 4.3% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 256,391 | 95.3% |
| LOAD_GLOBAL_MODULE | 11,440 | 4.3% |
| JUMP_BACKWARD | 640 | 0.2% |
| NOP | 280 | 0.1% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,687,342 | 99.8% |
| LOAD_CONST | 1,240 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 547 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,189,546 | 70.4% |
| STORE_FAST | 498,903 | 29.5% |
| TO_BOOL_NONE | 1,240 | 0.1% |
| LIST_APPEND | 860 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,520 | 84.7% |
| BUILD_TUPLE | 5,680 | 14.8% |
| CALL | 180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 26,900 | 70.1% |
| LOAD_FAST | 11,480 | 29.9% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,383,350 | 93.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 97,728 | 6.6% |
| LOAD_ATTR | 2,480 | 0.2% |
| CALL | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 635,722 | 42.8% |
| STORE_FAST | 575,960 | 38.8% |
| LOAD_FAST | 85,060 | 5.7% |
| CALL_BUILTIN_FAST | 81,253 | 5.5% |
| RETURN_VALUE | 51,590 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 884,579 | 91.8% |
| LOAD_CONST | 33,720 | 3.5% |
| CALL | 29,140 | 3.0% |
| RETURN_VALUE | 14,000 | 1.5% |
| RETURN_GENERATOR | 1,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 913,859 | 94.8% |
| LOAD_CONST | 33,440 | 3.5% |
| RETURN_VALUE | 14,900 | 1.5% |
| BINARY_OP_ADD_UNICODE | 1,240 | 0.1% |
| STORE_FAST | 280 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,569,425 | 44.6% |
| LOAD_FAST | 5,257,551 | 42.1% |
| LOAD_FAST_LOAD_FAST | 830,498 | 6.6% |
| LOAD_SUPER_ATTR_METHOD | 498,016 | 4.0% |
| LOAD_GLOBAL_MODULE | 93,900 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,447,879 | 99.6% |
| MAKE_CELL | 27,800 | 0.2% |
| RETURN_GENERATOR | 18,420 | 0.1% |
| COPY_FREE_VARS | 320 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,229,417 | 41.6% |
| ENTER_EXECUTOR | 690,970 | 23.4% |
| LOAD_ATTR_MODULE | 498,216 | 16.9% |
| LOAD_FAST | 340,031 | 11.5% |
| LOAD_CONST | 107,549 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,766,799 | 59.8% |
| COPY_FREE_VARS | 1,189,266 | 40.2% |


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
| LOAD_CONST | 2,055,969 | 54.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,081,314 | 28.8% |
| LOAD_FAST | 576,980 | 15.4% |
| LOAD_FAST_LOAD_FAST | 18,480 | 0.5% |
| CALL_BUILTIN_FAST | 14,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,754,004 | 99.9% |
| POP_JUMP_IF_TRUE | 3,464 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 97 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,420,189 | 95.6% |
| LOAD_CONST | 59,860 | 4.0% |
| LOAD_FAST | 5,820 | 0.4% |
| COMPARE_OP | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,447,298 | 97.4% |
| COPY | 14,040 | 0.9% |
| LOAD_FAST | 14,040 | 0.9% |
| POP_JUMP_IF_TRUE | 10,931 | 0.7% |


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
| GET_ITER | 1,580,712 | 75.9% |
| SWAP | 497,369 | 23.9% |
| JUMP_BACKWARD | 5,176 | 0.2% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 747,681 | 35.9% |
| STORE_FAST_LOAD_FAST | 576,620 | 27.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 514,122 | 24.7% |
| LOAD_FAST | 242,105 | 11.6% |
| RETURN_CONST | 1,325 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 265,882 | 99.1% |
| JUMP_BACKWARD | 2,234 | 0.8% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 267,476 | 99.7% |
| RETURN_CONST | 480 | 0.2% |
| LOAD_FAST | 360 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,740 | 81.0% |
| LOAD_FAST | 1,260 | 8.7% |
| SWAP | 860 | 5.9% |
| JUMP_BACKWARD | 600 | 4.1% |
| FOR_ITER | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,140 | 90.6% |
| STORE_FAST_LOAD_FAST | 860 | 5.9% |
| RETURN_CONST | 480 | 3.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 81,213 | 88.8% |
| LOAD_ATTR_MODULE | 10,200 | 11.1% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,978 | 81.9% |
| LOAD_FAST_CHECK | 16,515 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,130,691 | 90.4% |
| LOAD_FAST_LOAD_FAST | 1,738,873 | 7.1% |
| COPY | 573,009 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 23,764 | 0.1% |
| RETURN_VALUE | 14,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,587,860 | 22.8% |
| LOAD_FAST | 3,717,473 | 15.2% |
| TO_BOOL_BOOL | 1,883,535 | 7.7% |
| LOAD_ATTR | 1,814,253 | 7.4% |
| CONTAINS_OP | 1,762,295 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 408,812 | 100.0% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,626 | 39.8% |
| CALL | 148,638 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 97,728 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,587,860 | 87.2% |
| LOAD_FAST | 623,216 | 9.7% |
| LOAD_ATTR | 85,240 | 1.3% |
| LOAD_ATTR_SLOT | 83,760 | 1.3% |
| LOAD_CONST | 15,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,526,982 | 39.4% |
| CALL | 1,437,359 | 22.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,383,350 | 21.6% |
| LOAD_CONST | 733,615 | 11.4% |
| LOAD_FAST_LOAD_FAST | 299,510 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,280,215 | 69.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,342,093 | 12.9% |
| LOAD_FAST_LOAD_FAST | 1,189,186 | 11.4% |
| BINARY_SUBSCR | 575,920 | 5.5% |
| LOAD_GLOBAL_MODULE | 28,860 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,569,425 | 53.4% |
| LOAD_FAST | 2,728,958 | 26.2% |
| CALL_PY_WITH_DEFAULTS | 1,229,417 | 11.8% |
| LOAD_FAST_LOAD_FAST | 678,560 | 6.5% |
| LOAD_CONST | 126,029 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,361,547 | 99.9% |
| LOAD_ATTR | 2,821 | 0.1% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,710,907 | 72.3% |
| CALL_PY_WITH_DEFAULTS | 498,216 | 21.1% |
| STORE_DEREF | 55,040 | 2.3% |
| LOAD_CONST | 35,840 | 1.5% |
| LOAD_FAST | 28,800 | 1.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,229,786 | 70.5% |
| LOAD_FAST_LOAD_FAST | 513,982 | 29.5% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,189,226 | 68.2% |
| UNARY_INVERT | 514,062 | 29.5% |
| RETURN_VALUE | 14,040 | 0.8% |
| LOAD_CONST | 14,040 | 0.8% |
| LOAD_FAST_LOAD_FAST | 5,720 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 543,048 | 52.1% |
| ENTER_EXECUTOR | 470,652 | 45.1% |
| RETURN_VALUE | 27,440 | 2.6% |
| LOAD_GLOBAL_MODULE | 1,240 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,030,540 | 98.8% |
| TO_BOOL_BOOL | 12,160 | 1.2% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,900 | 99.9% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 83,760 | 85.5% |
| CALL_BUILTIN_FAST | 14,140 | 14.4% |
| CALL | 40 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,674,428 | 46.1% |
| LOAD_FAST | 1,233,366 | 15.5% |
| LOAD_GLOBAL_BUILTIN | 992,556 | 12.5% |
| STORE_FAST | 963,100 | 12.1% |
| NOP | 734,866 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,812,072 | 47.9% |
| LOAD_DEREF | 1,796,882 | 22.6% |
| CALL_ISINSTANCE | 1,206,726 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 992,556 | 12.5% |
| LOAD_GLOBAL_MODULE | 49,720 | 0.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,211,249 | 26.6% |
| RESUME_CHECK | 3,130,740 | 19.8% |
| NOP | 1,809,960 | 11.4% |
| POP_JUMP_IF_FALSE | 1,466,004 | 9.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,448,864 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,824,709 | 24.1% |
| LOAD_FAST_LOAD_FAST | 2,678,890 | 16.9% |
| LOAD_ATTR_MODULE | 2,361,547 | 14.9% |
| LOAD_FAST | 2,164,680 | 13.7% |
| COMPARE_OP_STR | 1,420,189 | 9.0% |


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
| LOAD_FAST | 1,707,162 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,203,546 | 70.5% |
| CALL_PY_EXACT_ARGS | 498,016 | 29.2% |
| LOAD_FAST | 5,760 | 0.3% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,447,879 | 33.5% |
| CACHE | 11,811,484 | 31.8% |
| FOR_ITER_GEN | 6,335,920 | 17.0% |
| COPY_FREE_VARS | 1,803,022 | 4.8% |
| CALL_PY_WITH_DEFAULTS | 1,766,799 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,759,816 | 55.8% |
| POP_TOP | 6,913,520 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 3,674,428 | 9.9% |
| LOAD_GLOBAL_MODULE | 3,130,740 | 8.4% |
| NOP | 1,390,966 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,932,898 | 68.1% |
| LOAD_FAST_LOAD_FAST | 759,796 | 17.7% |
| SWAP | 573,009 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 17,040 | 0.4% |
| STORE_FAST_LOAD_FAST | 14,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,205,784 | 51.2% |
| LOAD_FAST | 910,249 | 21.1% |
| LOAD_GLOBAL_MODULE | 709,196 | 16.5% |
| LOAD_CONST | 213,575 | 5.0% |
| LOAD_FAST_LOAD_FAST | 129,480 | 3.0% |


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
| LOAD_ATTR | 1,189,186 | 92.9% |
| LOAD_FAST | 45,018 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 34,680 | 2.7% |
| CALL | 10,200 | 0.8% |
| LOAD_CONST | 1,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,192,664 | 93.1% |
| RETURN_CONST | 32,520 | 2.5% |
| LOAD_GLOBAL_MODULE | 27,720 | 2.2% |
| LOAD_CONST | 27,480 | 2.1% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 59.8% |
| COPY | 364 | 36.3% |
| TO_BOOL | 40 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 620 | 61.8% |
| POP_JUMP_IF_FALSE | 384 | 38.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,883,535 | 27.7% |
| CALL_ISINSTANCE | 1,207,006 | 17.8% |
| RETURN_VALUE | 912,294 | 13.4% |
| CALL | 729,360 | 10.7% |
| LOAD_FAST | 718,753 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,666,263 | 68.7% |
| POP_JUMP_IF_TRUE | 1,841,893 | 27.1% |
| UNARY_NOT | 283,229 | 4.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,892,354 | 54.9% |
| BINARY_OP | 1,189,326 | 22.6% |
| LOAD_FAST | 1,189,186 | 22.6% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,271,246 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 509,516 | 92.2% |
| LOAD_ATTR_INSTANCE_VALUE | 42,760 | 7.7% |
| TO_BOOL | 200 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 552,336 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 191,440 | 79.6% |
| LOAD_FAST | 27,900 | 11.6% |
| COPY | 13,880 | 5.8% |
| WITH_EXCEPT_START | 5,680 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 220,800 | 91.8% |
| POP_JUMP_IF_TRUE | 19,700 | 8.2% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 860 | 51.8% |
| LOAD_FAST | 620 | 37.3% |
| COPY | 160 | 9.6% |
| LOAD_GLOBAL_MODULE | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,460 | 88.0% |
| POP_JUMP_IF_TRUE | 200 | 12.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,087,880 | 93.0% |
| CALL_BUILTIN_FAST | 81,253 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,088,220 | 93.0% |
| STORE_FAST | 81,293 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 581,600 | 27.0% |
| LOAD_FAST_CHECK | 575,920 | 26.8% |
| FOR_ITER_LIST | 514,122 | 23.9% |
| CALL_BUILTIN_FAST | 463,549 | 21.5% |
| CALL | 9,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,145,211 | 99.7% |
| LOAD_FAST | 7,000 | 0.3% |
| STORE_DEREF | 20 | 0.0% |


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
|     deferred | 7,127,396 | 77.3% |
|          hit | 2,081,471 | 22.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 8.4% |
| Failure | 6,503 | 91.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,246 | 49.9% |
| or | 1,736 | 26.7% |
| remainder | 781 | 12.0% |
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
|     deferred | 635,233 | 55.0% |
|          hit | 519,018 | 44.9% |

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
|     deferred | 10,950,642 | 27.8% |
|          hit | 28,429,554 | 72.1% |
|         miss | 7,860 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,163 | 23.4% |
| Failure | 30,007 | 76.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,925 | 26.4% |
| cfunc noargs | 6,066 | 20.2% |
| class no vectorcall | 4,000 | 13.3% |
| meth descr varargs keywords | 3,220 | 10.7% |
| class mutable | 1,294 | 4.3% |
| other | 1,180 | 3.9% |
| bound method | 1,128 | 3.8% |
| cfunc varargs | 1,120 | 3.7% |
| cfunc varargs keywords | 934 | 3.1% |
| meth descr method fastcall keywords | 920 | 3.1% |
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
|     deferred | 586,022 | 10.0% |
|          hit | 5,237,554 | 89.8% |
|         miss | 6,760 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,618 | 53.3% |
| Failure | 1,415 | 46.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 820 | 58.0% |
| big int | 360 | 25.4% |
| different types | 235 | 16.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,302,940 | 13.0% |
|          hit | 8,713,873 | 87.0% |

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
|     deferred | 10,397,944 | 18.1% |
|          hit | 46,776,895 | 81.3% |
|         miss | 311,740 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,208 | 51.9% |
| Failure | 20,602 | 48.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,625 | 22.4% |
| shadowed | 4,290 | 20.8% |
| not managed dict | 3,778 | 18.3% |
| non overriding descriptor | 2,464 | 12.0% |
| has managed dict | 1,120 | 5.4% |
| class attr descriptor | 1,040 | 5.0% |
| metaclass attribute | 960 | 4.7% |
| class method obj | 920 | 4.5% |
| non object slot | 560 | 2.7% |
| class attr simple | 485 | 2.4% |
| mutable class | 280 | 1.4% |
| overridden | 80 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,289 | 0.0% |
|        deopt | 100 | 0.0% |
|          hit | 23,801,054 | 99.9% |
|         miss | 6,525 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,581 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,796,882 | 100.0% |

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
|     deferred | 89,845 | 2.0% |
|          hit | 4,206,404 | 93.4% |
|         miss | 196,100 | 4.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,861 | 76.3% |
| Failure | 2,440 | 23.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 1,180 | 48.4% |
| class attr simple | 560 | 23.0% |
| not in keys | 440 | 18.0% |
| no dict | 260 | 10.7% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 30,340 | 2.3% |
|          hit | 1,280,584 | 97.6% |

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
|     deferred | 1,582,578 | 11.0% |
|          hit | 12,858,151 | 89.0% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,962 | 44.7% |
| Failure | 3,668 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,088 | 29.7% |
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
|          hit | 3,321,744 | 100.0% |

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
| Basic | 308,397,114 | 56.5% |
| Not specialized | 60,896,066 | 11.2% |
| Specialized hits | 176,118,524 | 32.3% |
| Specialized misses | 529,267 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 10,950,642 | 33.5% |
| LOAD_ATTR | 10,397,944 | 31.8% |
| BINARY_OP | 7,127,396 | 21.8% |
| TO_BOOL | 1,582,578 | 4.8% |
| FOR_ITER | 1,302,940 | 4.0% |
| BINARY_SUBSCR | 635,233 | 1.9% |
| COMPARE_OP | 586,022 | 1.8% |
| STORE_ATTR | 89,845 | 0.3% |
| STORE_SUBSCR | 30,340 | 0.1% |
| LOAD_GLOBAL | 8,289 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 216,214 | 40.9% |
| STORE_ATTR_INSTANCE_VALUE | 196,100 | 37.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,046 | 15.5% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.3% |
| COMPARE_OP_INT | 6,740 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,400 | 1.2% |
| LOAD_GLOBAL_MODULE | 6,185 | 1.2% |
| LOAD_ATTR_MODULE | 1,100 | 0.2% |
| CALL_PY_EXACT_ARGS | 860 | 0.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 420 | 0.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 11,931,144 | 32.1% |
| Calls to Python functions inlined | 25,288,296 | 67.9% |
| Calls via PyEval_EvalFrame (total) | 11,931,144 | 32.1% |
| Calls via PyEval_EvalFrame (vector) | 11,346,024 | 30.5% |
| Calls via PyEval_EvalFrame (generator) | 585,120 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 11,345,324 | 30.5% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 625,920 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 535,340 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 636,056 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 48,616 | 0.1% |
| Frames pushed | 18,815,146 | 50.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 19,339,903 | 41.8% |
| Frees to freelist | 19,352,618 |  |
| Allocations | 26,878,789 | 58.2% |
| Allocations to 512 bytes | 26,593,264 | 57.5% |
| Allocations to 4 kbytes | 117,522 | 0.3% |
| Allocations over 4 kbytes | 168,003 | 0.4% |
| Frees | 28,368,815 |  |
| New values | 88,020 |  |
| Interpreter increfs | 235,029,548 | 77.7% |
| Interpreter decrefs | 256,546,633 | 74.6% |
| Increfs | 67,383,901 | 22.3% |
| Decrefs | 87,399,920 | 25.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 12,255,815 |  |
| Method cache misses | 55,341 |  |
| Method cache collisions | 75,304 |  |
| Method cache dunder hits | 11,468,240 |  |
| Method cache dunder misses | 23,875 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 39 | 585 | 282,768 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 461,798 |  |
| Traces created | 716 | 0.2% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 461,082 | 99.8% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 10,152,917 |  |
| Uops executed | 99,564,055 | 9.81 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 11.2% |
| <= 16 | 120 | 16.8% |
| <= 32 | 360 | 50.3% |
| <= 64 | 100 | 14.0% |
| <= 128 | 56 | 7.8% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 40 | 5.6% |
| <= 8 | 40 | 5.6% |
| <= 16 | 200 | 27.9% |
| <= 32 | 360 | 50.3% |
| <= 64 | 39 | 5.4% |
| <= 128 | 37 | 5.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 1,023,360 | 10.1% |
| <= 8 | 2,105,990 | 20.7% |
| <= 16 | 6,004,782 | 59.1% |
| <= 32 | 1,017,550 | 10.0% |
| <= 64 | 765 | 0.0% |
| <= 128 | 419 | 0.0% |
| <= 256 | 9 | 0.0% |
| <= 512 | 2 | 0.0% |
| <= 1,024 | 3 | 0.0% |
| <= 2,048 | 4 | 0.0% |
| <= 4,096 | 8 | 0.0% |
| <= 8,192 | 25 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 23,834,475 | 23.9% | 23.9% |  |
| LOAD_FAST | 10,219,372 | 10.3% | 34.2% |  |
| _EXIT_TRACE | 10,152,917 | 10.2% | 44.4% |  |
| _POP_JUMP_IF_TRUE | 8,487,030 | 8.5% | 52.9% |  |
| _ITER_CHECK_LIST | 7,954,388 | 8.0% | 60.9% |  |
| _IS_ITER_EXHAUSTED_LIST | 7,954,388 | 8.0% | 68.9% |  |
| STORE_FAST | 6,622,668 | 6.7% | 75.6% |  |
| _ITER_NEXT_LIST | 6,121,501 | 6.1% | 81.7% |  |
| POP_TOP | 2,111,185 | 2.1% | 83.8% |  |
| _GUARD_GLOBALS_VERSION | 2,091,346 | 2.1% | 85.9% |  |
| PUSH_NULL | 1,679,789 | 1.7% | 87.6% |  |
| _LOAD_GLOBAL_MODULE | 1,275,928 | 1.3% | 88.9% |  |
| _CHECK_ATTR_MODULE | 1,267,839 | 1.3% | 90.2% |  |
| _LOAD_ATTR_MODULE | 1,267,839 | 1.3% | 91.4% |  |
| _GUARD_BUILTINS_VERSION | 815,418 | 0.8% | 92.3% |  |
| _LOAD_GLOBAL_BUILTINS | 815,418 | 0.8% | 93.1% |  |
| _GUARD_TYPE_VERSION | 799,669 | 0.8% | 93.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 761,090 | 0.8% | 94.6% |  |
| _GUARD_KEYS_VERSION | 761,090 | 0.8% | 95.4% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 761,090 | 0.8% | 96.2% |  |
| _ITER_CHECK_RANGE | 506,036 | 0.5% | 96.7% |  |
| _IS_ITER_EXHAUSTED_RANGE | 506,036 | 0.5% | 97.2% |  |
| LOAD_CONST | 351,757 | 0.4% | 97.5% |  |
| _ITER_NEXT_RANGE | 255,458 | 0.3% | 97.8% |  |
| TO_BOOL_BOOL | 240,447 | 0.2% | 98.0% |  |
| BINARY_SUBSCR_LIST_INT | 240,058 | 0.2% | 98.3% |  |
| CALL_BUILTIN_FAST | 240,058 | 0.2% | 98.5% |  |
| _POP_JUMP_IF_FALSE | 234,521 | 0.2% | 98.8% |  |
| _CHECK_PEP_523 | 134,320 | 0.1% | 98.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 134,320 | 0.1% | 99.0% |  |
| _CHECK_STACK_SPACE | 134,320 | 0.1% | 99.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 134,320 | 0.1% | 99.3% |  |
| _PUSH_FRAME | 134,320 | 0.1% | 99.4% |  |
| _SAVE_RETURN_OFFSET | 134,320 | 0.1% | 99.6% |  |
| RESUME_CHECK | 134,280 | 0.1% | 99.7% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 64,160 | 0.1% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 64,160 | 0.1% | 99.8% |  |
| _JUMP_TO_TOP | 24,793 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 23,826 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 23,826 | 0.0% | 99.9% |  |
| _ITER_CHECK_TUPLE | 15,720 | 0.0% | 99.9% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 15,720 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 11,882 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 6,080 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 5,520 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 4,011 | 0.0% | 100.0% |  |
| CONTAINS_OP | 2,871 | 0.0% | 100.0% |  |
| COPY | 2,871 | 0.0% | 100.0% |  |
| SWAP | 2,871 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,871 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 2,871 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 2,871 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 2,871 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 2,871 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 2,300 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 460 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _IS_NONE | 420 | 0.0% | 100.0% |  |
| IS_OP | 389 | 0.0% | 100.0% |  |
| _POP_FRAME | 389 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 140 | 0.0% | 100.0% |  |
| GET_ITER | 40 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40 | 0.0% | 100.0% |  |
| LOAD_DEREF | 40 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 40 | 0.0% | 100.0% |  |
| STORE_DEREF | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 372,660 |
| FOR_ITER | 74,640 |
| LOAD_ATTR | 13,862 |
| CALL | 197 |
| LOAD_ATTR_PROPERTY | 100 |
| YIELD_VALUE | 60 |
| CALL_PY_WITH_DEFAULTS | 60 |
| BEFORE_WITH | 40 |
| TO_BOOL | 40 |
| CALL_KW | 40 |


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
Stats gathered on: 2023-11-03
