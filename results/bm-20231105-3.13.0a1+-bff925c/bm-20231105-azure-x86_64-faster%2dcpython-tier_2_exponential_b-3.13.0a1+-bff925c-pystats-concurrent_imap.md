
# Pystats results

- benchmark: concurrent_imap
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 106,181,801 | 18.1% | 18.1% |  |
| RESUME_CHECK | 39,574,602 | 6.7% | 24.8% | 0.0% |
| STORE_FAST | 29,424,855 | 5.0% | 29.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 26,448,969 | 4.5% | 34.4% | 0.8% |
| POP_TOP | 25,660,479 | 4.4% | 38.7% |  |
| RETURN_VALUE | 24,326,309 | 4.1% | 42.9% |  |
| POP_JUMP_IF_FALSE | 21,321,308 | 3.6% | 46.5% |  |
| LOAD_GLOBAL_MODULE | 17,723,565 | 3.0% | 49.5% | 0.0% |
| LOAD_CONST | 15,748,949 | 2.7% | 52.2% |  |
| LOAD_FAST_LOAD_FAST | 15,408,106 | 2.6% | 54.9% |  |
| CALL_PY_EXACT_ARGS | 13,643,367 | 2.3% | 57.2% | 0.0% |
| INTERPRETER_EXIT | 12,393,419 | 2.1% | 59.3% |  |
| CALL | 11,736,924 | 2.0% | 61.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,554,637 | 2.0% | 63.3% | 0.7% |
| LOAD_ATTR | 11,182,659 | 1.9% | 65.2% |  |
| ENTER_EXECUTOR | 10,898,025 | 1.9% | 67.0% |  |
| RETURN_CONST | 10,192,103 | 1.7% | 68.8% |  |
| NOP | 9,951,317 | 1.7% | 70.5% |  |
| BINARY_OP | 8,369,058 | 1.4% | 71.9% |  |
| LOAD_GLOBAL_BUILTIN | 8,201,390 | 1.4% | 73.3% | 0.0% |
| COPY | 7,780,813 | 1.3% | 74.6% |  |
| JUMP_BACKWARD | 7,622,268 | 1.3% | 75.9% |  |
| TO_BOOL_BOOL | 7,424,087 | 1.3% | 77.2% |  |
| YIELD_VALUE | 6,913,660 | 1.2% | 78.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,865,905 | 1.2% | 79.5% |  |
| FOR_ITER_GEN | 6,347,440 | 1.1% | 80.6% |  |
| TO_BOOL_INT | 6,207,906 | 1.1% | 81.7% |  |
| PUSH_NULL | 5,911,802 | 1.0% | 82.7% |  |
| POP_JUMP_IF_NOT_NONE | 5,545,924 | 0.9% | 83.6% |  |
| STORE_FAST_STORE_FAST | 5,009,979 | 0.9% | 84.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 4,872,287 | 0.8% | 85.3% | 5.0% |
| BUILD_TUPLE | 4,558,204 | 0.8% | 86.1% |  |
| COMPARE_OP_INT | 4,056,791 | 0.7% | 86.8% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 3,293,968 | 0.6% | 87.3% |  |
| SWAP | 2,974,277 | 0.5% | 87.8% |  |
| POP_JUMP_IF_TRUE | 2,813,132 | 0.5% | 88.3% |  |
| LOAD_ATTR_MODULE | 2,619,396 | 0.4% | 88.8% | 0.0% |
| GET_ITER | 2,422,552 | 0.4% | 89.2% |  |
| CALL_FUNCTION_EX | 2,413,916 | 0.4% | 89.6% |  |
| FOR_ITER_LIST | 2,339,098 | 0.4% | 90.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,322,659 | 0.4% | 90.4% |  |
| LOAD_DEREF | 2,151,620 | 0.4% | 90.8% |  |
| COPY_FREE_VARS | 2,101,560 | 0.4% | 91.1% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,041,909 | 0.3% | 91.5% |  |
| LOAD_SUPER_ATTR_METHOD | 2,005,240 | 0.3% | 91.8% |  |
| UNARY_INVERT | 2,001,249 | 0.3% | 92.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,989,920 | 0.3% | 92.5% | 0.0% |
| CONTAINS_OP | 1,974,185 | 0.3% | 92.8% |  |
| BEFORE_WITH | 1,938,261 | 0.3% | 93.1% |  |
| JUMP_FORWARD | 1,878,654 | 0.3% | 93.5% |  |
| BUILD_LIST | 1,788,092 | 0.3% | 93.8% |  |
| CALL_BUILTIN_FAST | 1,774,197 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,763,701 | 0.3% | 94.4% |  |
| CALL_BUILTIN_CLASS | 1,730,843 | 0.3% | 94.7% |  |
| TO_BOOL | 1,631,195 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,591,437 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,528,823 | 0.3% | 95.5% |  |
| STORE_SUBSCR_DICT | 1,495,813 | 0.3% | 95.7% |  |
| CALL_ISINSTANCE | 1,420,079 | 0.2% | 96.0% |  |
| FOR_ITER | 1,305,260 | 0.2% | 96.2% |  |
| STORE_FAST_LOAD_FAST | 1,281,380 | 0.2% | 96.4% |  |
| POP_JUMP_IF_NONE | 1,265,807 | 0.2% | 96.6% |  |
| EXIT_INIT_CHECK | 1,234,382 | 0.2% | 96.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,234,382 | 0.2% | 97.1% |  |
| LOAD_ATTR_PROPERTY | 1,213,121 | 0.2% | 97.3% | 1.0% |
| UNPACK_SEQUENCE_TUPLE | 1,169,480 | 0.2% | 97.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,131,840 | 0.2% | 97.7% | 0.0% |
| BINARY_OP_ADD_INT | 1,107,287 | 0.2% | 97.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 965,181 | 0.2% | 98.0% | 0.0% |
| LIST_APPEND | 960,237 | 0.2% | 98.2% |  |
| LOAD_FAST_AND_CLEAR | 896,915 | 0.2% | 98.3% |  |
| LOAD_FAST_CHECK | 876,892 | 0.1% | 98.5% |  |
| COMPARE_OP | 676,511 | 0.1% | 98.6% |  |
| BINARY_SUBSCR | 638,108 | 0.1% | 98.7% |  |
| TO_BOOL_LIST | 637,621 | 0.1% | 98.8% |  |
| CALL_TUPLE_1 | 583,120 | 0.1% | 98.9% |  |
| LIST_EXTEND | 567,330 | 0.1% | 99.0% |  |
| DICT_MERGE | 564,260 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 408,860 | 0.1% | 99.2% |  |
| CALL_KW | 399,788 | 0.1% | 99.2% |  |
| CALL_LEN | 396,656 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 331,308 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 311,405 | 0.1% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 300,156 | 0.1% | 99.5% |  |
| UNARY_NOT | 299,401 | 0.1% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 283,616 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 240,415 | 0.0% | 99.6% | 0.1% |
| CALL_BUILTIN_O | 154,400 | 0.0% | 99.6% |  |
| MAKE_CELL | 137,900 | 0.0% | 99.7% |  |
| STORE_DEREF | 137,620 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 114,880 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 112,600 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 112,600 | 0.0% | 99.7% |  |
| STORE_ATTR | 100,865 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 99,760 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 97,980 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 91,460 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 0.0% | 99.8% |  |
| DELETE_ATTR | 86,394 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 78,216 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 78,204 | 0.0% | 99.9% | 8.2% |
| MAKE_FUNCTION | 63,640 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 55,680 | 0.0% | 99.9% |  |
| POP_EXCEPT | 50,248 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 50,248 | 0.0% | 99.9% |  |
| IS_OP | 46,547 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 44,488 | 0.0% | 99.9% |  |
| BUILD_STRING | 41,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 39,160 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 39,000 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 38,380 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 34,164 | 0.0% | 99.9% |  |
| IMPORT_NAME | 33,760 | 0.0% | 100.0% |  |
| IMPORT_FROM | 33,420 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 31,258 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 28,160 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 27,480 | 0.0% | 100.0% |  |
| BINARY_SLICE | 19,820 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 18,900 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 18,360 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,850 | 0.0% | 100.0% |  |
| RERAISE | 17,280 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 16,460 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,900 | 0.0% | 100.0% |  |
| END_FOR | 11,520 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,980 | 0.0% | 100.0% | 0.1% |
| RAISE_VARARGS | 5,780 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,760 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 3,780 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 2,800 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 1,440 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 919 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 23,789,800 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 22,331,468 | 3.8% | 7.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 13,596,807 | 2.3% | 10.2% |
| STORE_FAST LOAD_FAST | 12,911,890 | 2.2% | 12.4% |
| CACHE RESUME_CHECK | 12,279,541 | 2.1% | 14.5% |
| LOAD_FAST RETURN_VALUE | 11,607,864 | 2.0% | 16.5% |
| RETURN_VALUE INTERPRETER_EXIT | 10,837,364 | 1.8% | 18.3% |
| LOAD_FAST LOAD_ATTR | 8,973,918 | 1.5% | 19.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 8,461,594 | 1.4% | 21.3% |
| POP_TOP LOAD_FAST | 8,295,975 | 1.4% | 22.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 8,107,506 | 1.4% | 24.1% |
| POP_TOP ENTER_EXECUTOR | 7,765,379 | 1.3% | 25.4% |
| RETURN_CONST POP_TOP | 7,193,620 | 1.2% | 26.6% |
| RESUME_CHECK POP_TOP | 6,913,520 | 1.2% | 27.8% |
| JUMP_BACKWARD FOR_ITER_GEN | 6,335,920 | 1.1% | 28.9% |
| YIELD_VALUE STORE_FAST | 6,335,920 | 1.1% | 30.0% |
| FOR_ITER_GEN RESUME_CHECK | 6,335,920 | 1.1% | 31.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 6,246,982 | 1.1% | 32.1% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 6,207,766 | 1.1% | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,992,098 | 1.0% | 34.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,878,046 | 1.0% | 35.2% |
| NOP LOAD_FAST | 5,855,304 | 1.0% | 36.2% |
| STORE_FAST JUMP_BACKWARD | 5,760,000 | 1.0% | 37.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,235,880 | 0.9% | 38.1% |
| ENTER_EXECUTOR YIELD_VALUE | 5,183,440 | 0.9% | 38.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 4,934,785 | 0.8% | 39.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 4,505,862 | 0.8% | 40.5% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 4,185,199 | 0.7% | 41.3% |
| STORE_FAST NOP | 4,184,640 | 0.7% | 42.0% |
| LOAD_FAST LOAD_CONST | 4,072,679 | 0.7% | 42.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 4,052,961 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 4,017,228 | 0.7% | 44.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,003,483 | 0.7% | 44.7% |
| LOAD_CONST LOAD_CONST | 3,932,817 | 0.7% | 45.4% |
| LOAD_ATTR LOAD_FAST | 3,786,629 | 0.6% | 46.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,662,103 | 0.6% | 46.7% |
| PUSH_NULL LOAD_FAST | 3,607,268 | 0.6% | 47.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 3,451,725 | 0.6% | 47.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,416,837 | 0.6% | 48.5% |
| BINARY_OP COPY | 3,403,408 | 0.6% | 49.0% |
| COPY TO_BOOL_INT | 3,403,088 | 0.6% | 49.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 3,279,434 | 0.6% | 50.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 3,157,547 | 0.5% | 50.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 3,147,183 | 0.5% | 51.2% |
| CALL STORE_FAST | 2,864,260 | 0.5% | 51.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,826,141 | 0.5% | 52.2% |
| CALL RETURN_VALUE | 2,705,119 | 0.5% | 52.7% |
| LOAD_CONST CALL | 2,658,807 | 0.5% | 53.1% |
| RETURN_VALUE STORE_FAST | 2,648,251 | 0.5% | 53.6% |
| COPY STORE_FAST | 2,630,400 | 0.4% | 54.0% |
| STORE_FAST COPY | 2,629,760 | 0.4% | 54.5% |
| LOAD_FAST PUSH_NULL | 2,620,145 | 0.4% | 54.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,616,155 | 0.4% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 2,545,724 | 0.4% | 55.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,508,352 | 0.4% | 56.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,505,536 | 0.4% | 56.7% |
| CALL POP_TOP | 2,343,338 | 0.4% | 57.1% |
| RETURN_VALUE RETURN_VALUE | 2,333,566 | 0.4% | 57.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,315,639 | 0.4% | 57.9% |
| LOAD_CONST COMPARE_OP_INT | 2,270,382 | 0.4% | 58.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,182,201 | 0.4% | 58.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 2,133,774 | 0.4% | 59.0% |
| NOP LOAD_GLOBAL_MODULE | 2,108,266 | 0.4% | 59.3% |
| COPY_FREE_VARS RESUME_CHECK | 2,100,900 | 0.4% | 59.7% |
| LOAD_DEREF LOAD_FAST | 2,095,280 | 0.4% | 60.0% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 2,094,760 | 0.4% | 60.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 2,042,779 | 0.3% | 60.8% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 2,039,223 | 0.3% | 61.1% |
| POP_TOP RETURN_CONST | 2,011,730 | 0.3% | 61.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 2,005,040 | 0.3% | 61.8% |
| UNARY_INVERT BINARY_OP | 2,001,249 | 0.3% | 62.1% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,985,220 | 0.3% | 62.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,973,565 | 0.3% | 62.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,972,906 | 0.3% | 63.1% |
| LOAD_FAST BUILD_TUPLE | 1,963,559 | 0.3% | 63.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,899,239 | 0.3% | 63.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,891,809 | 0.3% | 64.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,888,846 | 0.3% | 64.4% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,880,617 | 0.3% | 64.8% |
| LOAD_FAST CALL_FUNCTION_EX | 1,849,636 | 0.3% | 65.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,845,772 | 0.3% | 65.4% |
| POP_TOP LOAD_CONST | 1,840,889 | 0.3% | 65.7% |
| LOAD_FAST GET_ITER | 1,780,232 | 0.3% | 66.0% |
| LOAD_CONST LOAD_FAST | 1,775,258 | 0.3% | 66.3% |
| RETURN_VALUE POP_TOP | 1,768,492 | 0.3% | 66.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,753,577 | 0.3% | 66.9% |
| GET_ITER FOR_ITER_LIST | 1,750,682 | 0.3% | 67.2% |
| POP_TOP NOP | 1,749,372 | 0.3% | 67.5% |
| POP_JUMP_IF_FALSE POP_TOP | 1,746,511 | 0.3% | 67.8% |
| BINARY_OP STORE_FAST | 1,716,124 | 0.3% | 68.1% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,687,370 | 0.3% | 68.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,678,893 | 0.3% | 68.7% |
| ENTER_EXECUTOR CALL | 1,637,400 | 0.3% | 69.0% |
| RESUME_CHECK NOP | 1,603,859 | 0.3% | 69.2% |
| LOAD_FAST TO_BOOL | 1,569,647 | 0.3% | 69.5% |
| LOAD_FAST_LOAD_FAST CALL | 1,566,788 | 0.3% | 69.8% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 1,557,198 | 0.3% | 70.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,491,270 | 0.3% | 70.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,490,761 | 0.3% | 70.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,489,805 | 0.3% | 70.8% |


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
| RESUME_CHECK | 12,279,541 | 99.0% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,248,362 | 64.4% |
| RETURN_VALUE | 583,321 | 30.1% |
| LOAD_GLOBAL_MODULE | 82,438 | 4.3% |
| LOAD_FAST | 17,280 | 0.9% |
| CALL | 6,360 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,349,280 | 69.6% |
| STORE_FAST | 588,981 | 30.4% |


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
| LOAD_FAST_LOAD_FAST | 576,080 | 90.3% |
| LOAD_CONST | 61,068 | 9.6% |
| BINARY_SUBSCR | 880 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 575,920 | 90.3% |
| STORE_FAST | 60,788 | 9.5% |
| BINARY_SUBSCR | 880 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 39,328 | 88.4% |
| LOAD_ATTR_MODULE | 5,100 | 11.5% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,488 | 100.0% |


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
| RETURN_CONST | 1,234,382 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,234,382 | 100.0% |


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
| LOAD_FAST | 1,780,232 | 73.5% |
| STORE_FAST_LOAD_FAST | 576,000 | 23.8% |
| CALL_BUILTIN_CLASS | 38,780 | 1.6% |
| CALL | 14,340 | 0.6% |
| RETURN_VALUE | 5,760 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,750,682 | 72.3% |
| LOAD_FAST_AND_CLEAR | 597,370 | 24.7% |
| FOR_ITER_RANGE | 31,870 | 1.3% |
| FOR_ITER | 12,110 | 0.5% |
| FOR_ITER_TUPLE | 11,740 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,837,364 | 87.4% |
| RETURN_CONST | 978,315 | 7.9% |
| YIELD_VALUE | 577,740 | 4.7% |


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
| STORE_FAST | 4,184,640 | 42.1% |
| POP_TOP | 1,749,372 | 17.6% |
| RESUME_CHECK | 1,603,859 | 16.1% |
| POP_JUMP_IF_FALSE | 1,470,145 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 591,816 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,855,304 | 58.8% |
| LOAD_GLOBAL_MODULE | 2,108,266 | 21.2% |
| LOAD_GLOBAL_BUILTIN | 862,487 | 8.7% |
| LOAD_FAST_LOAD_FAST | 583,320 | 5.9% |
| LOAD_CONST | 530,020 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 33,228 | 66.1% |
| COPY | 11,520 | 22.9% |
| POP_TOP | 5,200 | 10.3% |
| STORE_FAST | 280 | 0.6% |
| STORE_SUBSCR_DICT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 32,588 | 64.9% |
| RERAISE | 11,520 | 22.9% |
| JUMP_FORWARD | 5,120 | 10.2% |
| JUMP_BACKWARD | 940 | 1.9% |
| RETURN_CONST | 60 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 7,193,620 | 28.0% |
| RESUME_CHECK | 6,913,520 | 26.9% |
| CALL | 2,343,338 | 9.1% |
| RETURN_VALUE | 1,768,492 | 6.9% |
| POP_JUMP_IF_FALSE | 1,746,511 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,295,975 | 32.3% |
| ENTER_EXECUTOR | 7,765,379 | 30.3% |
| RETURN_CONST | 2,011,730 | 7.8% |
| LOAD_CONST | 1,840,889 | 7.2% |
| NOP | 1,749,372 | 6.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 38,948 | 77.5% |
| RERAISE | 5,760 | 11.5% |
| CALL_KW | 5,120 | 10.2% |
| BINARY_SUBSCR_DICT | 300 | 0.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 39,288 | 78.2% |
| WITH_EXCEPT_START | 5,760 | 11.5% |
| LOAD_GLOBAL_MODULE | 5,080 | 10.1% |
| LOAD_GLOBAL | 120 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,620,145 | 44.3% |
| LOAD_ATTR_MODULE | 1,880,617 | 31.8% |
| LOAD_ATTR | 1,284,320 | 21.7% |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 1.5% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,607,268 | 61.0% |
| CALL | 1,094,595 | 18.5% |
| LOAD_FAST_LOAD_FAST | 820,820 | 13.9% |
| LOAD_CONST | 315,495 | 5.3% |
| CALL_PY_EXACT_ARGS | 49,320 | 0.8% |


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
| LOAD_FAST | 11,607,864 | 47.7% |
| CALL | 2,705,119 | 11.1% |
| RETURN_VALUE | 2,333,566 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,845,772 | 7.6% |
| CALL_FUNCTION_EX | 1,265,456 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 10,837,364 | 44.5% |
| STORE_FAST | 2,648,251 | 10.9% |
| RETURN_VALUE | 2,333,566 | 9.6% |
| POP_TOP | 1,768,492 | 7.3% |
| LOAD_FAST_LOAD_FAST | 1,402,159 | 5.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 14,080 | 45.0% |
| LOAD_FAST | 10,438 | 33.4% |
| LOAD_ATTR_INSTANCE_VALUE | 5,800 | 18.6% |
| STORE_SUBSCR | 660 | 2.1% |
| LOAD_ATTR | 200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 19,960 | 63.9% |
| LOAD_GLOBAL_MODULE | 10,200 | 32.6% |
| STORE_SUBSCR | 660 | 2.1% |
| STORE_SUBSCR_DICT | 259 | 0.8% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,569,647 | 96.2% |
| LOAD_ATTR_INSTANCE_VALUE | 53,497 | 3.3% |
| TO_BOOL | 3,676 | 0.2% |
| LOAD_ATTR | 884 | 0.1% |
| RETURN_VALUE | 771 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 888,249 | 54.5% |
| POP_JUMP_IF_FALSE | 736,227 | 45.1% |
| TO_BOOL | 3,676 | 0.2% |
| TO_BOOL_BOOL | 2,163 | 0.1% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,402,159 | 70.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 599,010 | 29.9% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,001,249 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 299,361 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 299,401 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 4,505,862 | 53.8% |
| UNARY_INVERT | 2,001,249 | 23.9% |
| POP_JUMP_IF_FALSE | 1,402,159 | 16.8% |
| LOAD_ATTR | 313,645 | 3.7% |
| LOAD_FAST_LOAD_FAST | 84,160 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,403,408 | 40.7% |
| STORE_FAST | 1,716,124 | 20.5% |
| TO_BOOL_INT | 1,402,219 | 16.8% |
| UNARY_INVERT | 1,402,159 | 16.8% |
| BUILD_TUPLE | 299,545 | 3.6% |


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
| SWAP | 597,370 | 33.4% |
| JUMP_FORWARD | 583,081 | 32.6% |
| LOAD_FAST | 300,216 | 16.8% |
| POP_TOP | 282,885 | 15.8% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,321 | 33.6% |
| SWAP | 597,370 | 33.4% |
| STORE_FAST | 584,541 | 32.7% |
| RETURN_VALUE | 5,120 | 0.3% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 593,281 | 33.6% |
| BUILD_TUPLE | 576,000 | 32.7% |
| LOAD_FAST | 529,560 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 17,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,170,401 | 66.4% |
| BUILD_TUPLE | 576,020 | 32.7% |
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
| LOAD_FAST | 1,963,559 | 43.1% |
| LOAD_FAST_LOAD_FAST | 1,160,320 | 25.5% |
| BUILD_MAP | 576,020 | 12.6% |
| RETURN_VALUE | 512,000 | 11.2% |
| BINARY_OP | 299,545 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,403,719 | 30.8% |
| YIELD_VALUE | 1,152,100 | 25.3% |
| BUILD_MAP | 576,000 | 12.6% |
| STORE_FAST | 512,000 | 11.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 11.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,658,807 | 22.7% |
| ENTER_EXECUTOR | 1,637,400 | 14.0% |
| LOAD_FAST_LOAD_FAST | 1,566,788 | 13.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,442,664 | 12.3% |
| BUILD_TUPLE | 1,403,719 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,864,260 | 24.4% |
| RETURN_VALUE | 2,705,119 | 23.0% |
| POP_TOP | 2,343,338 | 20.0% |
| LOAD_FAST | 1,204,377 | 10.3% |
| TO_BOOL_BOOL | 728,531 | 6.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,849,636 | 76.6% |
| DICT_MERGE | 564,260 | 23.4% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,265,456 | 52.4% |
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
| LOAD_CONST | 394,348 | 98.6% |
| ENTER_EXECUTOR | 5,440 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 330,165 | 82.6% |
| LOAD_FAST | 28,800 | 7.2% |
| RETURN_VALUE | 21,120 | 5.3% |
| STORE_FAST | 14,220 | 3.6% |
| PUSH_EXC_INFO | 5,120 | 1.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 669,576 | 99.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,455 | 0.5% |
| COMPARE_OP | 1,489 | 0.2% |
| LOAD_GLOBAL_MODULE | 380 | 0.1% |
| LOAD_FAST | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 672,994 | 99.5% |
| COMPARE_OP | 1,489 | 0.2% |
| COMPARE_OP_INT | 1,228 | 0.2% |
| COMPARE_OP_STR | 440 | 0.1% |
| POP_JUMP_IF_TRUE | 280 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,972,906 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 99 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,973,565 | 100.0% |
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
| BINARY_OP | 3,403,408 | 43.7% |
| STORE_FAST | 2,629,760 | 33.8% |
| LOAD_CONST | 1,100,800 | 14.1% |
| LOAD_FAST | 584,946 | 7.5% |
| STORE_ATTR_INSTANCE_VALUE | 21,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,403,088 | 43.7% |
| STORE_FAST | 2,630,400 | 33.8% |
| STORE_FAST_STORE_FAST | 1,093,760 | 14.1% |
| LOAD_ATTR_INSTANCE_VALUE | 570,728 | 7.3% |
| LOAD_FAST | 28,160 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,402,159 | 66.7% |
| CALL_ALLOC_AND_ENTER_INIT | 583,041 | 27.7% |
| CACHE | 109,900 | 5.2% |
| CALL | 5,940 | 0.3% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,100,900 | 100.0% |
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
| POP_TOP | 7,765,379 | 71.3% |
| POP_JUMP_IF_NOT_NONE | 1,077,130 | 9.9% |
| LIST_APPEND | 844,637 | 7.8% |
| STORE_FAST_STORE_FAST | 575,360 | 5.3% |
| CALL_LIST_APPEND | 298,905 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,183,440 | 47.6% |
| CALL | 1,637,400 | 15.0% |
| LOAD_FAST | 1,174,945 | 10.8% |
| CALL_PY_WITH_DEFAULTS | 887,912 | 8.1% |
| LOAD_ATTR_PROPERTY | 832,336 | 7.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,271,230 | 97.4% |
| SWAP | 14,160 | 1.1% |
| GET_ITER | 12,110 | 0.9% |
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
| RETURN_VALUE | 27,520 | 59.1% |
| LOAD_FAST | 17,420 | 37.4% |
| LOAD_GLOBAL_MODULE | 1,567 | 3.4% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,407 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,760,000 | 75.6% |
| POP_TOP | 1,158,124 | 15.2% |
| ENTER_EXECUTOR | 575,960 | 7.6% |
| LIST_APPEND | 115,600 | 1.5% |
| STORE_FAST_STORE_FAST | 6,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 6,335,920 | 83.1% |
| FOR_ITER | 1,271,230 | 16.7% |
| FOR_ITER_LIST | 5,706 | 0.1% |
| FOR_ITER_TUPLE | 2,560 | 0.0% |
| FOR_ITER_RANGE | 2,094 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,242,089 | 66.1% |
| POP_TOP | 618,345 | 32.9% |
| STORE_ATTR_INSTANCE_VALUE | 7,020 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 5,720 | 0.3% |
| POP_EXCEPT | 5,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,218,887 | 64.9% |
| BUILD_LIST | 583,081 | 31.0% |
| POP_EXCEPT | 33,228 | 1.8% |
| LOAD_GLOBAL_MODULE | 24,818 | 1.3% |
| LOAD_FAST_LOAD_FAST | 7,320 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 546,032 | 56.9% |
| LOAD_ATTR | 299,565 | 31.2% |
| BINARY_SUBSCR_STR_INT | 112,600 | 11.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,000 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 844,637 | 88.0% |
| JUMP_BACKWARD | 115,600 | 12.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 284,305 | 50.1% |
| RETURN_VALUE | 282,885 | 49.9% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 283,525 | 50.0% |
| STORE_FAST | 282,885 | 49.9% |
| RETURN_VALUE | 640 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,973,918 | 80.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,899,239 | 17.0% |
| LOAD_GLOBAL_MODULE | 162,801 | 1.5% |
| CALL | 83,860 | 0.7% |
| LOAD_ATTR | 22,781 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,786,629 | 33.9% |
| STORE_SUBSCR_DICT | 1,402,079 | 12.5% |
| PUSH_NULL | 1,284,320 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 1,257,503 | 11.2% |
| RETURN_VALUE | 856,367 | 7.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,072,679 | 25.9% |
| LOAD_CONST | 3,932,817 | 25.0% |
| POP_TOP | 1,840,889 | 11.7% |
| POP_JUMP_IF_FALSE | 962,195 | 6.1% |
| LOAD_ATTR_METHOD_NO_DICT | 733,065 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,932,817 | 25.0% |
| CALL | 2,658,807 | 16.9% |
| COMPARE_OP_INT | 2,270,382 | 14.4% |
| LOAD_FAST | 1,775,258 | 11.3% |
| COPY | 1,100,800 | 7.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,094,760 | 97.4% |
| POP_JUMP_IF_NOT_NONE | 27,520 | 1.3% |
| STORE_DEREF | 27,520 | 1.3% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,095,280 | 97.4% |
| POP_JUMP_IF_NOT_NONE | 55,040 | 2.6% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 22,331,468 | 21.0% |
| STORE_FAST | 12,911,890 | 12.2% |
| POP_JUMP_IF_FALSE | 8,461,594 | 8.0% |
| POP_TOP | 8,295,975 | 7.8% |
| NOP | 5,855,304 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 23,789,800 | 22.4% |
| RETURN_VALUE | 11,607,864 | 10.9% |
| LOAD_ATTR | 8,973,918 | 8.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,107,506 | 7.6% |
| CALL_PY_EXACT_ARGS | 5,878,046 | 5.5% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 597,370 | 66.6% |
| LOAD_FAST_AND_CLEAR | 299,545 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 597,370 | 66.6% |
| LOAD_FAST_AND_CLEAR | 299,545 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 576,560 | 65.8% |
| POP_JUMP_IF_NONE | 283,536 | 32.3% |
| LOAD_ATTR_CLASS | 16,476 | 1.9% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 65.7% |
| LOAD_GLOBAL_MODULE | 283,456 | 32.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 16,436 | 1.9% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,147,183 | 20.4% |
| LOAD_FAST_LOAD_FAST | 2,042,779 | 13.3% |
| POP_JUMP_IF_FALSE | 1,753,577 | 11.4% |
| LOAD_SUPER_ATTR_METHOD | 1,416,439 | 9.2% |
| RETURN_VALUE | 1,402,159 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,662,103 | 23.8% |
| LOAD_FAST_LOAD_FAST | 2,042,779 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,039,223 | 13.2% |
| CALL | 1,566,788 | 10.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,402,079 | 9.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,706 | 9.6% |
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
| TO_BOOL_INT | 6,207,766 | 29.1% |
| TO_BOOL_BOOL | 5,235,880 | 24.6% |
| COMPARE_OP_INT | 4,052,961 | 19.0% |
| CONTAINS_OP | 1,973,565 | 9.3% |
| COMPARE_OP_STR | 1,489,805 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,461,594 | 39.7% |
| RETURN_CONST | 3,451,725 | 16.2% |
| LOAD_FAST_LOAD_FAST | 1,753,577 | 8.2% |
| POP_TOP | 1,746,511 | 8.2% |
| LOAD_GLOBAL_MODULE | 1,678,893 | 7.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,188,007 | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE | 47,800 | 3.8% |
| LOAD_ATTR | 28,300 | 2.2% |
| RETURN_VALUE | 1,400 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 336,895 | 26.6% |
| NOP | 320,805 | 25.3% |
| LOAD_FAST_CHECK | 283,536 | 22.4% |
| LOAD_FAST | 274,589 | 21.7% |
| RETURN_CONST | 24,340 | 1.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,508,352 | 45.2% |
| LOAD_ATTR | 1,257,503 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,156,979 | 20.9% |
| RETURN_VALUE | 546,672 | 9.9% |
| LOAD_DEREF | 55,040 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,182,201 | 39.3% |
| RETURN_CONST | 1,258,851 | 22.7% |
| ENTER_EXECUTOR | 1,077,130 | 19.4% |
| NOP | 591,816 | 10.7% |
| LOAD_CONST | 283,165 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,888,846 | 67.1% |
| TO_BOOL | 888,249 | 31.6% |
| TO_BOOL_NONE | 19,700 | 0.7% |
| COMPARE_OP_STR | 10,938 | 0.4% |
| COMPARE_OP_INT | 3,379 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 953,202 | 33.9% |
| LOAD_FAST_LOAD_FAST | 891,045 | 31.7% |
| RETURN_CONST | 780,577 | 27.7% |
| LOAD_GLOBAL_MODULE | 73,031 | 2.6% |
| RETURN_VALUE | 60,748 | 2.2% |


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
| POP_JUMP_IF_FALSE | 3,451,725 | 33.9% |
| STORE_ATTR_INSTANCE_VALUE | 2,545,724 | 25.0% |
| POP_TOP | 2,011,730 | 19.7% |
| POP_JUMP_IF_NOT_NONE | 1,258,851 | 12.4% |
| POP_JUMP_IF_TRUE | 780,577 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,193,620 | 70.6% |
| EXIT_INIT_CHECK | 1,234,382 | 12.1% |
| INTERPRETER_EXIT | 978,315 | 9.6% |
| TO_BOOL_BOOL | 685,840 | 6.7% |
| STORE_FAST | 62,588 | 0.6% |


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
| LOAD_FAST | 58,567 | 58.1% |
| LOAD_FAST_LOAD_FAST | 22,040 | 21.9% |
| LOAD_ATTR_INSTANCE_VALUE | 17,280 | 17.1% |
| STORE_ATTR | 2,520 | 2.5% |
| LOAD_ATTR | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 44,840 | 44.5% |
| LOAD_FAST_LOAD_FAST | 14,760 | 14.6% |
| LOAD_FAST | 13,619 | 13.5% |
| LOAD_CONST | 12,645 | 12.5% |
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
| YIELD_VALUE | 6,335,920 | 21.5% |
| CALL | 2,864,260 | 9.7% |
| RETURN_VALUE | 2,648,251 | 9.0% |
| COPY | 2,630,400 | 8.9% |
| BINARY_OP | 1,716,124 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,911,890 | 43.9% |
| JUMP_BACKWARD | 5,760,000 | 19.6% |
| NOP | 4,184,640 | 14.2% |
| COPY | 2,629,760 | 8.9% |
| JUMP_FORWARD | 1,242,089 | 4.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 688,680 | 53.7% |
| FOR_ITER_LIST | 576,620 | 45.0% |
| COPY | 14,080 | 1.1% |
| FOR_ITER_TUPLE | 2,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 576,560 | 45.0% |
| GET_ITER | 576,000 | 45.0% |
| LOAD_FAST | 112,640 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 14,000 | 1.1% |
| TO_BOOL_STR | 2,000 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,315,639 | 46.2% |
| COPY | 1,093,760 | 21.8% |
| UNPACK_SEQUENCE_TUPLE | 1,088,220 | 21.7% |
| STORE_FAST_STORE_FAST | 512,000 | 10.2% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,687,370 | 33.7% |
| LOAD_FAST_LOAD_FAST | 1,124,709 | 22.4% |
| STORE_FAST | 1,088,280 | 21.7% |
| ENTER_EXECUTOR | 575,360 | 11.5% |
| STORE_FAST_STORE_FAST | 512,000 | 10.2% |


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
| BUILD_LIST | 597,370 | 20.1% |
| LOAD_FAST_AND_CLEAR | 597,370 | 20.1% |
| ENTER_EXECUTOR | 581,550 | 19.6% |
| BINARY_OP_ADD_INT | 570,787 | 19.2% |
| LOAD_FAST | 311,336 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 610,881 | 20.5% |
| BUILD_LIST | 597,370 | 20.1% |
| STORE_FAST | 597,370 | 20.1% |
| FOR_ITER_LIST | 582,350 | 19.6% |
| STORE_ATTR_INSTANCE_VALUE | 570,728 | 19.2% |


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
| BUILD_TUPLE | 1,152,100 | 16.7% |
| STORE_FAST_LOAD_FAST | 576,560 | 8.3% |
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
| LOAD_FAST | 300,116 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300,156 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,088,648 | 98.3% |
| LOAD_FAST_LOAD_FAST | 18,480 | 1.7% |
| BINARY_OP | 159 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 570,787 | 51.5% |
| STORE_FAST | 511,980 | 46.2% |
| BINARY_SLICE | 18,520 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,680 | 0.5% |
| LOAD_CONST | 280 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 32.8% |
| CALL_METHOD_DESCRIPTOR_O | 1,240 | 32.8% |
| LOAD_FAST_LOAD_FAST | 960 | 25.4% |
| BINARY_SUBSCR_LIST_INT | 280 | 7.4% |
| BINARY_OP | 40 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,740 | 46.0% |
| LOAD_CONST | 1,260 | 33.3% |
| CALL | 480 | 12.7% |
| STORE_FAST | 300 | 7.9% |


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
| CALL | 283,456 | 99.9% |
| BINARY_OP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 283,616 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,760 | 79.9% |
| LOAD_CONST | 60,668 | 18.3% |
| CALL_LEN | 5,680 | 1.7% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 325,588 | 98.3% |
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
| LOAD_CONST | 11,640 | 63.4% |
| LOAD_FAST_LOAD_FAST | 6,600 | 35.9% |
| BINARY_SUBSCR | 120 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,440 | 62.3% |
| STORE_FAST | 6,640 | 36.2% |
| BINARY_OP_ADD_UNICODE | 280 | 1.5% |


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
| LOAD_GLOBAL_MODULE | 610,481 | 49.5% |
| LOAD_FAST | 590,201 | 47.8% |
| CALL | 33,420 | 2.7% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 651,341 | 52.8% |
| COPY_FREE_VARS | 583,041 | 47.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,240 | 82.1% |
| LOAD_CONST | 7,000 | 9.0% |
| BINARY_OP_ADD_INT | 5,680 | 7.3% |
| PUSH_NULL | 1,004 | 1.3% |
| CALL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 71,804 | 91.8% |
| POP_TOP | 6,280 | 8.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 856,027 | 49.5% |
| CALL_FUNCTION_EX | 511,960 | 29.6% |
| LOAD_FAST | 317,896 | 18.4% |
| LOAD_CONST | 14,600 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 10,260 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 856,327 | 49.5% |
| RETURN_VALUE | 812,136 | 46.9% |
| GET_ITER | 38,780 | 2.2% |
| LOAD_FAST | 17,280 | 1.0% |
| CALL_BUILTIN_CLASS | 6,280 | 0.4% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,021,852 | 57.6% |
| LOAD_CONST | 441,085 | 24.9% |
| LOAD_FAST_LOAD_FAST | 173,120 | 9.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 81,220 | 4.6% |
| LOAD_GLOBAL_MODULE | 27,880 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 636,645 | 35.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 548,669 | 30.9% |
| TO_BOOL_BOOL | 431,025 | 24.3% |
| UNPACK_SEQUENCE_TUPLE | 81,220 | 4.6% |
| POP_TOP | 14,858 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,020 | 45.8% |
| BUILD_TUPLE | 511,960 | 45.2% |
| CALL | 65,004 | 5.7% |
| LOAD_FAST_CHECK | 16,436 | 1.5% |
| LOAD_ATTR | 14,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,047,820 | 92.6% |
| RETURN_VALUE | 82,120 | 7.3% |
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
| LOAD_GLOBAL_BUILTIN | 1,419,619 | 100.0% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,419,899 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 368,375 | 92.9% |
| LOAD_ATTR_INSTANCE_VALUE | 27,900 | 7.0% |
| CALL | 381 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 344,200 | 86.8% |
| CALL_PY_EXACT_ARGS | 33,160 | 8.4% |
| CALL_BUILTIN_CLASS | 6,280 | 1.6% |
| LOAD_FAST | 5,720 | 1.4% |
| BINARY_OP_SUBTRACT_INT | 5,680 | 1.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 299,465 | 96.2% |
| LOAD_FAST | 11,440 | 3.7% |
| LOAD_CONST | 140 | 0.0% |
| LOAD_FAST_CHECK | 140 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 298,905 | 96.0% |
| LOAD_GLOBAL_MODULE | 11,440 | 3.7% |
| JUMP_BACKWARD | 600 | 0.2% |
| NOP | 280 | 0.1% |
| RETURN_CONST | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,985,220 | 99.8% |
| LOAD_GLOBAL_MODULE | 2,280 | 0.1% |
| LOAD_CONST | 1,240 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 601 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,402,439 | 70.5% |
| STORE_FAST | 583,941 | 29.3% |
| LIST_APPEND | 2,000 | 0.1% |
| TO_BOOL_NONE | 1,240 | 0.1% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,490,761 | 93.7% |
| LOAD_ATTR_METHOD_LAZY_DICT | 97,656 | 6.1% |
| LOAD_ATTR | 2,480 | 0.2% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 741,457 | 46.6% |
| STORE_FAST | 575,960 | 36.2% |
| LOAD_FAST | 85,060 | 5.3% |
| CALL_BUILTIN_FAST | 81,220 | 5.1% |
| RETURN_VALUE | 51,512 | 3.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,742 | 91.8% |
| LOAD_CONST | 33,720 | 3.5% |
| CALL | 29,139 | 3.0% |
| RETURN_VALUE | 14,000 | 1.5% |
| RETURN_GENERATOR | 1,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 915,021 | 94.8% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 6,246,982 | 45.8% |
| LOAD_FAST | 5,878,046 | 43.1% |
| LOAD_FAST_LOAD_FAST | 596,480 | 4.4% |
| LOAD_SUPER_ATTR_METHOD | 583,001 | 4.3% |
| LOAD_GLOBAL_MODULE | 93,900 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,596,807 | 99.7% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 1,243,228 | 37.7% |
| ENTER_EXECUTOR | 887,912 | 27.0% |
| LOAD_ATTR_MODULE | 583,181 | 17.7% |
| LOAD_FAST | 382,505 | 11.6% |
| LOAD_CONST | 107,258 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,891,809 | 57.4% |
| COPY_FREE_VARS | 1,402,159 | 42.6% |


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
| LOAD_CONST | 2,270,382 | 56.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,165,862 | 28.7% |
| LOAD_FAST | 576,980 | 14.2% |
| LOAD_FAST_LOAD_FAST | 18,480 | 0.5% |
| CALL_BUILTIN_FAST | 14,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,052,961 | 99.9% |
| POP_JUMP_IF_TRUE | 3,379 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| COMPARE_OP | 151 | 0.0% |
| STORE_FAST | 140 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,462,703 | 95.7% |
| LOAD_CONST | 59,860 | 3.9% |
| LOAD_FAST | 5,820 | 0.4% |
| COMPARE_OP | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,489,805 | 97.4% |
| COPY | 14,040 | 0.9% |
| LOAD_FAST | 14,040 | 0.9% |
| POP_JUMP_IF_TRUE | 10,938 | 0.7% |


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
| GET_ITER | 1,750,682 | 74.8% |
| SWAP | 582,350 | 24.9% |
| JUMP_BACKWARD | 5,706 | 0.2% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 875,534 | 37.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 599,430 | 25.6% |
| STORE_FAST_LOAD_FAST | 576,620 | 24.7% |
| LOAD_FAST | 284,556 | 12.2% |
| RETURN_CONST | 1,338 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 31,870 | 93.3% |
| JUMP_BACKWARD | 2,094 | 6.1% |
| FOR_ITER | 200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 33,444 | 97.9% |
| RETURN_CONST | 420 | 1.2% |
| LOAD_FAST | 300 | 0.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,740 | 71.3% |
| JUMP_BACKWARD | 2,560 | 15.6% |
| LOAD_FAST | 1,260 | 7.7% |
| SWAP | 860 | 5.2% |
| FOR_ITER | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,140 | 79.8% |
| STORE_FAST_LOAD_FAST | 2,000 | 12.2% |
| SWAP | 860 | 5.2% |
| RETURN_CONST | 440 | 2.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 81,180 | 88.8% |
| LOAD_ATTR_MODULE | 10,200 | 11.2% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,984 | 82.0% |
| LOAD_FAST_CHECK | 16,476 | 18.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,789,800 | 89.9% |
| LOAD_FAST_LOAD_FAST | 2,039,223 | 7.7% |
| COPY | 570,728 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 23,676 | 0.1% |
| RETURN_VALUE | 14,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,992,098 | 22.7% |
| LOAD_FAST | 4,017,228 | 15.2% |
| TO_BOOL_BOOL | 2,133,774 | 8.1% |
| CONTAINS_OP | 1,972,906 | 7.5% |
| LOAD_ATTR | 1,899,239 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 408,680 | 100.0% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,560 | 39.8% |
| CALL | 148,644 | 36.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 97,656 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,992,098 | 87.3% |
| LOAD_FAST | 673,629 | 9.8% |
| LOAD_ATTR | 85,278 | 1.2% |
| LOAD_ATTR_SLOT | 83,760 | 1.2% |
| LOAD_CONST | 15,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,826,141 | 41.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,490,761 | 21.7% |
| CALL | 1,442,664 | 21.0% |
| LOAD_CONST | 733,065 | 10.7% |
| LOAD_FAST_LOAD_FAST | 341,734 | 5.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,107,506 | 70.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,421,028 | 12.3% |
| LOAD_FAST_LOAD_FAST | 1,402,079 | 12.1% |
| BINARY_SUBSCR | 575,920 | 5.0% |
| LOAD_GLOBAL_MODULE | 28,860 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,246,982 | 54.1% |
| LOAD_FAST | 3,157,547 | 27.3% |
| CALL_PY_WITH_DEFAULTS | 1,243,228 | 10.8% |
| LOAD_FAST_LOAD_FAST | 678,560 | 5.9% |
| LOAD_CONST | 125,738 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,616,155 | 99.9% |
| LOAD_ATTR | 2,821 | 0.1% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,880,617 | 71.8% |
| CALL_PY_WITH_DEFAULTS | 583,181 | 22.3% |
| STORE_DEREF | 55,040 | 2.1% |
| LOAD_CONST | 35,840 | 1.4% |
| LOAD_FAST | 28,800 | 1.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,442,679 | 70.7% |
| LOAD_FAST_LOAD_FAST | 598,930 | 29.3% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,402,119 | 68.7% |
| UNARY_INVERT | 599,010 | 29.3% |
| RETURN_VALUE | 14,040 | 0.7% |
| LOAD_CONST | 14,040 | 0.7% |
| LOAD_FAST_LOAD_FAST | 5,720 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 832,336 | 68.6% |
| LOAD_FAST | 351,565 | 29.0% |
| RETURN_VALUE | 27,440 | 2.3% |
| LOAD_GLOBAL_MODULE | 1,240 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,200,741 | 99.0% |
| TO_BOOL_BOOL | 12,160 | 1.0% |
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
| RESUME_CHECK | 4,185,199 | 51.0% |
| LOAD_FAST | 1,446,259 | 17.6% |
| NOP | 862,487 | 10.5% |
| STORE_FAST | 814,001 | 9.9% |
| LOAD_GLOBAL_BUILTIN | 524,520 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,003,483 | 48.8% |
| LOAD_DEREF | 2,094,760 | 25.5% |
| CALL_ISINSTANCE | 1,419,619 | 17.3% |
| LOAD_GLOBAL_BUILTIN | 524,520 | 6.4% |
| LOAD_GLOBAL_MODULE | 49,680 | 0.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,934,785 | 27.8% |
| RESUME_CHECK | 3,279,434 | 18.5% |
| NOP | 2,108,266 | 11.9% |
| POP_JUMP_IF_FALSE | 1,678,893 | 9.5% |
| LOAD_GLOBAL_MODULE | 1,557,198 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,505,862 | 25.4% |
| LOAD_FAST_LOAD_FAST | 3,147,183 | 17.8% |
| LOAD_ATTR_MODULE | 2,616,155 | 14.8% |
| LOAD_FAST | 2,505,536 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,557,198 | 8.8% |


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
| LOAD_FAST | 2,005,040 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,416,439 | 70.6% |
| CALL_PY_EXACT_ARGS | 583,001 | 29.1% |
| LOAD_FAST | 5,760 | 0.3% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,596,807 | 34.4% |
| CACHE | 12,279,541 | 31.0% |
| FOR_ITER_GEN | 6,335,920 | 16.0% |
| COPY_FREE_VARS | 2,100,900 | 5.3% |
| CALL_PY_WITH_DEFAULTS | 1,891,809 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,331,468 | 56.4% |
| POP_TOP | 6,913,520 | 17.5% |
| LOAD_GLOBAL_BUILTIN | 4,185,199 | 10.6% |
| LOAD_GLOBAL_MODULE | 3,279,434 | 8.3% |
| NOP | 1,603,859 | 4.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,416,837 | 70.1% |
| LOAD_FAST_LOAD_FAST | 844,781 | 17.3% |
| SWAP | 570,728 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 17,040 | 0.3% |
| STORE_FAST_LOAD_FAST | 14,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,545,724 | 52.2% |
| LOAD_FAST | 935,447 | 19.2% |
| LOAD_GLOBAL_MODULE | 821,621 | 16.9% |
| LOAD_CONST | 302,855 | 6.2% |
| LOAD_FAST_LOAD_FAST | 129,480 | 2.7% |


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
| LOAD_ATTR | 1,402,079 | 93.7% |
| LOAD_FAST | 47,355 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 34,680 | 2.3% |
| CALL | 10,200 | 0.7% |
| LOAD_CONST | 1,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,407,893 | 94.1% |
| RETURN_CONST | 32,520 | 2.2% |
| LOAD_GLOBAL_MODULE | 27,720 | 1.9% |
| LOAD_CONST | 27,480 | 1.8% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,133,774 | 28.7% |
| CALL_ISINSTANCE | 1,419,899 | 19.1% |
| RETURN_VALUE | 1,013,269 | 13.6% |
| CALL | 728,531 | 9.8% |
| LOAD_FAST | 720,508 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,235,880 | 70.5% |
| POP_JUMP_IF_TRUE | 1,888,846 | 25.4% |
| UNARY_NOT | 299,361 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,403,088 | 54.8% |
| BINARY_OP | 1,402,219 | 22.6% |
| LOAD_FAST | 1,402,079 | 22.6% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,207,766 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 594,501 | 93.2% |
| LOAD_ATTR_INSTANCE_VALUE | 42,900 | 6.7% |
| TO_BOOL | 200 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 637,461 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 191,355 | 79.6% |
| LOAD_FAST | 27,900 | 11.6% |
| COPY | 13,880 | 5.8% |
| WITH_EXCEPT_START | 5,680 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 220,715 | 91.8% |
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
| CALL_BUILTIN_FAST | 81,220 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,088,220 | 93.1% |
| STORE_FAST | 81,260 | 6.9% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 599,430 | 25.8% |
| FOR_ITER | 581,600 | 25.0% |
| LOAD_FAST_CHECK | 575,920 | 24.8% |
| CALL_BUILTIN_FAST | 548,669 | 23.6% |
| CALL | 9,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,315,639 | 99.7% |
| LOAD_FAST | 7,000 | 0.3% |
| STORE_DEREF | 20 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 65.3% |
| COPY | 279 | 30.4% |
| TO_BOOL | 40 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 620 | 67.5% |
| POP_JUMP_IF_FALSE | 299 | 32.5% |


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
|     deferred | 8,361,671 | 79.4% |
|          hit | 2,166,227 | 20.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 599 | 8.1% |
| Failure | 6,788 | 91.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,423 | 50.4% |
| or | 1,846 | 27.2% |
| remainder | 779 | 11.5% |
| add different types | 640 | 9.4% |
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
|     deferred | 636,988 | 69.0% |
|          hit | 285,000 | 30.9% |

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
|     deferred | 11,697,202 | 27.7% |
|          hit | 30,414,663 | 72.1% |
|         miss | 7,860 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,304 | 23.4% |
| Failure | 30,418 | 76.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,937 | 26.1% |
| cfunc noargs | 6,375 | 21.0% |
| class no vectorcall | 4,000 | 13.2% |
| meth descr varargs keywords | 3,220 | 10.6% |
| class mutable | 1,345 | 4.4% |
| other | 1,180 | 3.9% |
| bound method | 1,136 | 3.7% |
| cfunc varargs | 1,100 | 3.6% |
| cfunc varargs keywords | 985 | 3.2% |
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
|     deferred | 673,203 | 10.8% |
|          hit | 5,576,309 | 89.0% |
|         miss | 9,445 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,668 | 50.4% |
| Failure | 1,640 | 49.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 834 | 50.9% |
| different types | 446 | 27.2% |
| big int | 360 | 22.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,302,940 | 13.0% |
|          hit | 8,737,162 | 87.0% |

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
|     deferred | 11,139,668 | 17.8% |
|          hit | 51,032,657 | 81.6% |
|         miss | 311,360 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,462 | 52.2% |
| Failure | 20,529 | 47.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,642 | 22.6% |
| shadowed | 4,344 | 21.2% |
| not managed dict | 3,947 | 19.2% |
| non overriding descriptor | 2,134 | 10.4% |
| has managed dict | 1,120 | 5.5% |
| class attr descriptor | 1,040 | 5.1% |
| metaclass attribute | 960 | 4.7% |
| class method obj | 920 | 4.5% |
| non object slot | 560 | 2.7% |
| class attr simple | 502 | 2.4% |
| mutable class | 280 | 1.4% |
| overridden | 80 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,327 | 0.0% |
|        deopt | 100 | 0.0% |
|          hit | 25,918,694 | 99.9% |
|         miss | 6,261 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,623 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 2,094,760 | 100.0% |

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
|     deferred | 89,364 | 1.8% |
|          hit | 4,725,007 | 93.2% |
|         miss | 245,260 | 4.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,981 | 78.1% |
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
|     deferred | 30,339 | 2.0% |
|          hit | 1,495,813 | 98.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 259 | 28.2% |
| Failure | 660 | 71.8% |

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
|     deferred | 1,624,516 | 10.1% |
|          hit | 14,513,468 | 89.9% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,003 | 45.0% |
| Failure | 3,676 | 55.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,096 | 29.8% |
| sequence | 880 | 23.9% |
| set | 740 | 20.1% |
| tuple | 740 | 20.1% |
| other | 220 | 6.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 3,492,139 | 100.0% |

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
| Basic | 329,473,562 | 56.2% |
| Not specialized | 66,684,599 | 11.4% |
| Specialized hits | 189,927,213 | 32.4% |
| Specialized misses | 580,470 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 11,697,202 | 32.9% |
| LOAD_ATTR | 11,139,668 | 31.3% |
| BINARY_OP | 8,361,671 | 23.5% |
| TO_BOOL | 1,624,516 | 4.6% |
| FOR_ITER | 1,302,940 | 3.7% |
| COMPARE_OP | 673,203 | 1.9% |
| BINARY_SUBSCR | 636,988 | 1.8% |
| STORE_ATTR | 89,364 | 0.3% |
| STORE_SUBSCR | 30,339 | 0.1% |
| LOAD_GLOBAL | 8,327 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.3% |
| LOAD_ATTR_INSTANCE_VALUE | 215,865 | 37.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,015 | 14.1% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.1% |
| COMPARE_OP_INT | 9,425 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,400 | 1.1% |
| LOAD_GLOBAL_MODULE | 5,921 | 1.0% |
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
| Calls to PyEval_EvalDefault | 12,399,201 | 31.3% |
| Calls to Python functions inlined | 27,200,241 | 68.7% |
| Calls via PyEval_EvalFrame (total) | 12,399,201 | 31.3% |
| Calls via PyEval_EvalFrame (vector) | 11,814,081 | 29.8% |
| Calls via PyEval_EvalFrame (generator) | 585,120 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 11,813,381 | 29.8% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 625,920 | 1.6% |
| Calls via PyEval_EvalFrame (function ex) | 535,340 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 721,328 | 1.8% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 50,398 | 0.1% |
| Frames pushed | 21,429,552 | 54.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 21,031,946 | 42.4% |
| Frees to freelist | 21,044,700 |  |
| Allocations | 28,521,805 | 57.6% |
| Allocations to 512 bytes | 28,236,140 | 57.0% |
| Allocations to 4 kbytes | 117,651 | 0.2% |
| Allocations over 4 kbytes | 168,014 | 0.3% |
| Frees | 30,224,594 |  |
| New values | 88,020 |  |
| Interpreter increfs | 256,351,830 | 77.8% |
| Interpreter decrefs | 280,108,782 | 74.9% |
| Increfs | 73,294,150 | 22.2% |
| Decrefs | 93,938,077 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 13,917,107 |  |
| Method cache misses | 57,968 |  |
| Method cache collisions | 134,345 |  |
| Method cache dunder hits | 12,212,448 |  |
| Method cache dunder misses | 80,048 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 40 | 600 | 290,698 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 990 |  |
| Traces created | 750 | 75.8% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 240 | 24.2% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 10,898,025 |  |
| Uops executed | 128,617,966 | 11.80 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 10.7% |
| <= 16 | 120 | 16.0% |
| <= 32 | 280 | 37.3% |
| <= 64 | 100 | 13.3% |
| <= 128 | 170 | 22.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 40 | 5.3% |
| <= 8 | 40 | 5.3% |
| <= 16 | 160 | 21.3% |
| <= 32 | 300 | 40.0% |
| <= 64 | 59 | 7.9% |
| <= 128 | 151 | 20.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 1,023,400 | 9.4% |
| <= 8 | 2,363,212 | 21.7% |
| <= 16 | 6,046,805 | 55.5% |
| <= 32 | 1,118,043 | 10.3% |
| <= 64 | 5,326 | 0.0% |
| <= 128 | 341,149 | 3.1% |
| <= 256 | 4 | 0.0% |
| <= 512 | 3 | 0.0% |
| <= 1,024 | 7 | 0.0% |
| <= 2,048 | 20 | 0.0% |
| <= 4,096 | 14 | 0.0% |
| <= 8,192 | 42 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 30,512,805 | 23.7% | 23.7% |  |
| LOAD_FAST | 15,322,862 | 11.9% | 35.6% |  |
| _EXIT_TRACE | 10,898,025 | 8.5% | 44.1% |  |
| _POP_JUMP_IF_TRUE | 9,292,891 | 7.2% | 51.3% |  |
| _ITER_CHECK_LIST | 8,336,713 | 6.5% | 57.8% |  |
| _IS_ITER_EXHAUSTED_LIST | 8,336,713 | 6.5% | 64.3% |  |
| STORE_FAST | 7,707,754 | 6.0% | 70.3% |  |
| _ITER_NEXT_LIST | 6,291,195 | 4.9% | 75.2% |  |
| _GUARD_GLOBALS_VERSION | 3,366,287 | 2.6% | 77.8% |  |
| POP_TOP | 2,501,603 | 1.9% | 79.7% |  |
| _GUARD_BUILTINS_VERSION | 1,687,540 | 1.3% | 81.1% |  |
| _LOAD_GLOBAL_BUILTINS | 1,687,540 | 1.3% | 82.4% |  |
| PUSH_NULL | 1,679,932 | 1.3% | 83.7% |  |
| _LOAD_GLOBAL_MODULE | 1,678,747 | 1.3% | 85.0% |  |
| _CHECK_ATTR_MODULE | 1,395,830 | 1.1% | 86.1% |  |
| _LOAD_ATTR_MODULE | 1,395,830 | 1.1% | 87.2% |  |
| _GUARD_TYPE_VERSION | 1,149,908 | 0.9% | 88.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 1,022,890 | 0.8% | 88.8% |  |
| _GUARD_KEYS_VERSION | 1,022,890 | 0.8% | 89.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,022,890 | 0.8% | 90.4% |  |
| _ITER_CHECK_RANGE | 867,715 | 0.7% | 91.1% |  |
| _IS_ITER_EXHAUSTED_RANGE | 867,715 | 0.7% | 91.8% |  |
| LOAD_CONST | 806,840 | 0.6% | 92.4% |  |
| _CHECK_PEP_523 | 751,768 | 0.6% | 93.0% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 751,768 | 0.6% | 93.6% |  |
| _CHECK_STACK_SPACE | 751,768 | 0.6% | 94.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 751,768 | 0.6% | 94.7% |  |
| _PUSH_FRAME | 751,768 | 0.6% | 95.3% |  |
| _SAVE_RETURN_OFFSET | 751,768 | 0.6% | 95.9% |  |
| RESUME_CHECK | 751,728 | 0.6% | 96.5% |  |
| _LOAD_ATTR | 617,710 | 0.5% | 97.0% |  |
| _ITER_NEXT_RANGE | 574,510 | 0.4% | 97.4% |  |
| BINARY_SUBSCR_LIST_INT | 559,090 | 0.4% | 97.9% |  |
| CALL_BUILTIN_CLASS | 553,050 | 0.4% | 98.3% |  |
| TO_BOOL_BOOL | 347,157 | 0.3% | 98.6% |  |
| _POP_JUMP_IF_FALSE | 342,200 | 0.3% | 98.8% |  |
| CALL_BUILTIN_FAST | 282,565 | 0.2% | 99.0% |  |
| GET_ITER | 276,565 | 0.2% | 99.3% |  |
| CALL_LEN | 276,525 | 0.2% | 99.5% |  |
| _POP_FRAME | 128,772 | 0.1% | 99.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 106,556 | 0.1% | 99.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 106,556 | 0.1% | 99.7% |  |
| _IS_NONE | 64,180 | 0.0% | 99.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 64,180 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 64,180 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 25,759 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 15,308 | 0.0% | 99.9% |  |
| _ITER_CHECK_TUPLE | 13,760 | 0.0% | 99.9% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 13,760 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 6,080 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 5,480 | 0.0% | 100.0% |  |
| BEFORE_WITH | 5,314 | 0.0% | 100.0% |  |
| CONTAINS_OP | 5,154 | 0.0% | 100.0% |  |
| COPY | 5,154 | 0.0% | 100.0% |  |
| SWAP | 5,154 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,154 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 5,154 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 5,154 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 5,154 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 5,154 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 5,154 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,160 | 0.0% | 100.0% |  |
| IS_OP | 412 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 100 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 60 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 40 | 0.0% | 100.0% |  |
| STORE_DEREF | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 211 |
| FOR_ITER | 160 |
| LOAD_ATTR_PROPERTY | 140 |
| CALL_PY_WITH_DEFAULTS | 120 |
| FOR_ITER_GEN | 80 |
| YIELD_VALUE | 60 |
| CALL_KW | 40 |
| CALL_LIST_APPEND | 40 |


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
Stats gathered on: 2023-11-08
