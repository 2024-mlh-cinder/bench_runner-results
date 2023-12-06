
# Pystats results

- benchmark: concurrent_imap
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 79,719,106 | 18.1% | 18.1% |  |
| RESUME_CHECK | 29,752,750 | 6.8% | 24.8% | 0.0% |
| STORE_FAST | 22,105,631 | 5.0% | 29.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,854,660 | 4.5% | 34.4% | 0.8% |
| POP_TOP | 19,271,029 | 4.4% | 38.7% |  |
| RETURN_VALUE | 18,326,372 | 4.2% | 42.9% |  |
| POP_JUMP_IF_FALSE | 16,043,742 | 3.6% | 46.5% |  |
| LOAD_GLOBAL_MODULE | 13,324,142 | 3.0% | 49.6% | 0.0% |
| LOAD_CONST | 11,730,120 | 2.7% | 52.2% |  |
| LOAD_FAST_LOAD_FAST | 11,597,160 | 2.6% | 54.9% |  |
| CALL_PY_EXACT_ARGS | 10,271,616 | 2.3% | 57.2% |  |
| CALL | 9,430,304 | 2.1% | 59.3% |  |
| INTERPRETER_EXIT | 9,305,497 | 2.1% | 61.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,699,354 | 2.0% | 63.4% | 0.7% |
| LOAD_ATTR | 8,389,484 | 1.9% | 65.3% |  |
| ENTER_EXECUTOR | 8,196,815 | 1.9% | 67.2% |  |
| RETURN_CONST | 7,639,354 | 1.7% | 68.9% |  |
| NOP | 7,493,391 | 1.7% | 70.6% |  |
| BINARY_OP | 6,310,355 | 1.4% | 72.1% |  |
| LOAD_GLOBAL_BUILTIN | 6,175,565 | 1.4% | 73.5% |  |
| COPY | 5,850,985 | 1.3% | 74.8% |  |
| JUMP_BACKWARD | 5,706,508 | 1.3% | 76.1% |  |
| TO_BOOL_BOOL | 5,578,062 | 1.3% | 77.4% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 78.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,156,144 | 1.2% | 79.7% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 80.8% |  |
| TO_BOOL_INT | 4,684,372 | 1.1% | 81.8% |  |
| PUSH_NULL | 4,435,929 | 1.0% | 82.8% |  |
| POP_JUMP_IF_NOT_NONE | 4,158,421 | 0.9% | 83.8% |  |
| STORE_FAST_STORE_FAST | 3,762,003 | 0.9% | 84.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,559,020 | 0.8% | 85.5% | 4.2% |
| BUILD_TUPLE | 3,425,381 | 0.8% | 86.2% |  |
| COMPARE_OP_INT | 3,052,459 | 0.7% | 86.9% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 2,481,421 | 0.6% | 87.5% |  |
| SWAP | 2,238,779 | 0.5% | 88.0% |  |
| POP_JUMP_IF_TRUE | 2,093,776 | 0.5% | 88.5% |  |
| LOAD_ATTR_MODULE | 1,966,867 | 0.4% | 88.9% |  |
| GET_ITER | 1,823,131 | 0.4% | 89.3% |  |
| CALL_FUNCTION_EX | 1,810,127 | 0.4% | 89.7% |  |
| FOR_ITER_LIST | 1,758,517 | 0.4% | 90.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,746,963 | 0.4% | 90.5% |  |
| LOAD_DEREF | 1,621,680 | 0.4% | 90.9% |  |
| COPY_FREE_VARS | 1,584,600 | 0.4% | 91.3% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,540,837 | 0.3% | 91.6% |  |
| LOAD_SUPER_ATTR_METHOD | 1,512,960 | 0.3% | 92.0% |  |
| UNARY_INVERT | 1,510,117 | 0.3% | 92.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,499,382 | 0.3% | 92.6% |  |
| CONTAINS_OP | 1,486,046 | 0.3% | 93.0% |  |
| BEFORE_WITH | 1,446,478 | 0.3% | 93.3% |  |
| JUMP_FORWARD | 1,402,858 | 0.3% | 93.6% |  |
| BUILD_LIST | 1,347,331 | 0.3% | 93.9% |  |
| CALL_BUILTIN_FAST | 1,335,115 | 0.3% | 94.2% |  |
| BUILD_MAP | 1,325,115 | 0.3% | 94.5% |  |
| TO_BOOL | 1,219,827 | 0.3% | 94.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,187,251 | 0.3% | 95.1% |  |
| COMPARE_OP_STR | 1,147,677 | 0.3% | 95.3% |  |
| STORE_SUBSCR_DICT | 1,128,226 | 0.3% | 95.6% |  |
| CALL_ISINSTANCE | 1,071,045 | 0.2% | 95.8% |  |
| FOR_ITER | 976,760 | 0.2% | 96.1% |  |
| STORE_FAST_LOAD_FAST | 959,040 | 0.2% | 96.3% |  |
| POP_JUMP_IF_NONE | 939,106 | 0.2% | 96.5% |  |
| EXIT_INIT_CHECK | 930,870 | 0.2% | 96.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 930,870 | 0.2% | 96.9% |  |
| LOAD_ATTR_PROPERTY | 914,811 | 0.2% | 97.1% | 1.0% |
| UNPACK_SEQUENCE_TUPLE | 877,011 | 0.2% | 97.3% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 847,731 | 0.2% | 97.5% |  |
| BINARY_OP_ADD_INT | 830,196 | 0.2% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 724,528 | 0.2% | 97.9% |  |
| LIST_APPEND | 722,556 | 0.2% | 98.0% |  |
| LOAD_FAST_AND_CLEAR | 676,077 | 0.2% | 98.2% |  |
| LOAD_FAST_CHECK | 658,386 | 0.1% | 98.3% |  |
| CALL_BUILTIN_CLASS | 656,710 | 0.1% | 98.5% |  |
| COMPARE_OP | 507,152 | 0.1% | 98.6% |  |
| TO_BOOL_LIST | 480,795 | 0.1% | 98.7% |  |
| BINARY_SUBSCR | 478,936 | 0.1% | 98.8% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.9% |  |
| LIST_EXTEND | 427,930 | 0.1% | 99.0% |  |
| DICT_MERGE | 422,880 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,924 | 0.1% | 99.2% |  |
| CALL_KW | 300,437 | 0.1% | 99.2% |  |
| CALL_LEN | 296,620 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 249,859 | 0.1% | 99.4% |  |
| UNARY_NOT | 245,602 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 234,656 | 0.1% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 226,510 | 0.1% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 214,099 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,253 | 0.0% | 99.6% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.6% |  |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,691 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,424 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,788 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 58,552 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 57,783 | 0.0% | 99.9% | 7.6% |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| POP_EXCEPT | 38,557 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 38,557 | 0.0% | 99.9% |  |
| IS_OP | 34,432 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 34,237 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 99.9% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 23,924 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,772 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,961 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 12,960 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 9,600 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 741 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 188 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,856,135 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 16,787,164 | 3.8% | 7.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,237,056 | 2.3% | 10.2% |
| STORE_FAST LOAD_FAST | 9,700,765 | 2.2% | 12.4% |
| CACHE RESUME_CHECK | 9,222,461 | 2.1% | 14.5% |
| LOAD_FAST RETURN_VALUE | 8,730,512 | 2.0% | 16.5% |
| RETURN_VALUE INTERPRETER_EXIT | 8,138,794 | 1.8% | 18.3% |
| LOAD_FAST LOAD_ATTR | 6,749,396 | 1.5% | 19.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,356,629 | 1.4% | 21.3% |
| POP_TOP LOAD_FAST | 6,266,718 | 1.4% | 22.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,101,705 | 1.4% | 24.1% |
| POP_TOP ENTER_EXECUTOR | 5,833,522 | 1.3% | 25.4% |
| RETURN_CONST POP_TOP | 5,403,251 | 1.2% | 26.6% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.8% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 28.9% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.0% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 31.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,698,213 | 1.1% | 32.1% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,684,372 | 1.1% | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,498,693 | 1.0% | 34.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,435,337 | 1.0% | 35.2% |
| NOP LOAD_FAST | 4,410,820 | 1.0% | 36.2% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 37.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,931,159 | 0.9% | 38.1% |
| ENTER_EXECUTOR YIELD_VALUE | 3,888,000 | 0.9% | 39.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,721,642 | 0.8% | 39.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 3,400,271 | 0.8% | 40.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,154,245 | 0.7% | 41.3% |
| STORE_FAST NOP | 3,151,141 | 0.7% | 42.0% |
| LOAD_FAST LOAD_CONST | 3,064,468 | 0.7% | 42.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,050,165 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,023,945 | 0.7% | 44.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,013,005 | 0.7% | 44.8% |
| LOAD_CONST LOAD_CONST | 2,921,036 | 0.7% | 45.4% |
| LOAD_ATTR LOAD_FAST | 2,851,811 | 0.6% | 46.1% |
| CALL STORE_FAST | 2,800,802 | 0.6% | 46.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,758,346 | 0.6% | 47.3% |
| PUSH_NULL LOAD_FAST | 2,707,924 | 0.6% | 48.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,597,831 | 0.6% | 48.6% |
| BINARY_OP COPY | 2,568,202 | 0.6% | 49.1% |
| COPY TO_BOOL_INT | 2,568,202 | 0.6% | 49.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,468,448 | 0.6% | 50.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,468,426 | 0.6% | 50.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,383,319 | 0.5% | 51.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,373,815 | 0.5% | 51.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,129,728 | 0.5% | 52.4% |
| CALL RETURN_VALUE | 2,034,885 | 0.5% | 52.9% |
| LOAD_CONST CALL | 2,001,781 | 0.5% | 53.3% |
| RETURN_VALUE STORE_FAST | 1,994,160 | 0.5% | 53.8% |
| COPY STORE_FAST | 1,972,800 | 0.4% | 54.2% |
| STORE_FAST COPY | 1,972,320 | 0.4% | 54.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,966,780 | 0.4% | 55.1% |
| LOAD_FAST PUSH_NULL | 1,964,334 | 0.4% | 55.6% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,919,820 | 0.4% | 56.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,886,830 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,869,432 | 0.4% | 56.8% |
| CALL POP_TOP | 1,768,674 | 0.4% | 57.3% |
| RETURN_VALUE RETURN_VALUE | 1,759,847 | 0.4% | 57.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,741,683 | 0.4% | 58.0% |
| LOAD_CONST COMPARE_OP_INT | 1,710,394 | 0.4% | 58.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,626,515 | 0.4% | 58.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,596,635 | 0.4% | 59.2% |
| NOP LOAD_GLOBAL_MODULE | 1,589,226 | 0.4% | 59.5% |
| COPY_FREE_VARS RESUME_CHECK | 1,584,600 | 0.4% | 59.9% |
| LOAD_DEREF LOAD_FAST | 1,580,160 | 0.4% | 60.2% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,580,160 | 0.4% | 60.6% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,538,990 | 0.3% | 61.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,538,085 | 0.3% | 61.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,512,960 | 0.3% | 61.6% |
| UNARY_INVERT BINARY_OP | 1,510,117 | 0.3% | 62.0% |
| POP_TOP RETURN_CONST | 1,498,359 | 0.3% | 62.3% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,498,080 | 0.3% | 62.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,486,046 | 0.3% | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,486,041 | 0.3% | 63.3% |
| LOAD_FAST BUILD_TUPLE | 1,478,565 | 0.3% | 63.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,425,863 | 0.3% | 64.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,423,336 | 0.3% | 64.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,415,982 | 0.3% | 64.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,401,301 | 0.3% | 65.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,391,772 | 0.3% | 65.3% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,247 | 0.3% | 65.6% |
| POP_TOP LOAD_CONST | 1,370,872 | 0.3% | 65.9% |
| LOAD_FAST GET_ITER | 1,342,171 | 0.3% | 66.2% |
| RETURN_VALUE POP_TOP | 1,335,138 | 0.3% | 66.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,323,047 | 0.3% | 66.8% |
| POP_JUMP_IF_FALSE POP_TOP | 1,318,599 | 0.3% | 67.1% |
| GET_ITER FOR_ITER_LIST | 1,318,230 | 0.3% | 67.4% |
| POP_TOP NOP | 1,317,357 | 0.3% | 67.7% |
| BINARY_OP STORE_FAST | 1,294,661 | 0.3% | 68.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,268,032 | 0.3% | 68.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,265,328 | 0.3% | 68.6% |
| LOAD_CONST LOAD_FAST | 1,264,943 | 0.3% | 68.9% |
| ENTER_EXECUTOR CALL | 1,231,005 | 0.3% | 69.1% |
| RESUME_CHECK NOP | 1,209,285 | 0.3% | 69.4% |
| LOAD_FAST_LOAD_FAST CALL | 1,180,646 | 0.3% | 69.7% |
| LOAD_FAST TO_BOOL | 1,178,919 | 0.3% | 70.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 1,174,282 | 0.3% | 70.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,120,185 | 0.3% | 70.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,118,285 | 0.3% | 70.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,111,913 | 0.3% | 71.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,222,461 | 99.1% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 936,044 | 64.7% |
| RETURN_VALUE | 439,995 | 30.4% |
| LOAD_GLOBAL_MODULE | 61,916 | 4.3% |
| CALL | 4,320 | 0.3% |
| ENTER_EXECUTOR | 4,203 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,163 | 69.3% |
| STORE_FAST | 444,315 | 30.7% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 20,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,640 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 432,000 | 90.2% |
| LOAD_CONST | 46,717 | 9.8% |
| BINARY_SUBSCR | 219 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.2% |
| STORE_FAST | 46,717 | 9.8% |
| BINARY_SUBSCR | 219 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,396 | 88.8% |
| LOAD_ATTR_MODULE | 3,840 | 11.2% |
| LOAD_GLOBAL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,237 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,316 | 48.4% |
| CALL | 20,636 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,590 | 16.4% |
| LOAD_ATTR | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,596 | 77.9% |
| RETURN_CONST | 7,676 | 13.1% |
| LOAD_FAST | 5,280 | 9.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 4,320 | 50.0% |
| LOAD_FAST | 4,320 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 930,870 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 930,870 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 21,120 | 50.6% |
| LOAD_FAST | 20,640 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,200 | 74.7% |
| BUILD_STRING | 10,560 | 25.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,342,171 | 73.6% |
| STORE_FAST_LOAD_FAST | 432,000 | 23.7% |
| CALL_BUILTIN_CLASS | 28,800 | 1.6% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,318,230 | 72.3% |
| LOAD_FAST_AND_CLEAR | 450,061 | 24.7% |
| FOR_ITER_RANGE | 23,640 | 1.3% |
| FOR_ITER | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,138,794 | 87.5% |
| RETURN_CONST | 733,743 | 7.9% |
| YIELD_VALUE | 432,960 | 4.7% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 44,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 28,320 | 64.1% |
| STORE_FAST | 10,560 | 23.9% |
| LOAD_FAST | 5,280 | 12.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,151,141 | 42.1% |
| POP_TOP | 1,317,357 | 17.6% |
| RESUME_CHECK | 1,209,285 | 16.1% |
| POP_JUMP_IF_FALSE | 1,106,341 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 446,342 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,410,820 | 58.9% |
| LOAD_GLOBAL_MODULE | 1,589,226 | 21.2% |
| LOAD_GLOBAL_BUILTIN | 650,825 | 8.7% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.8% |
| LOAD_CONST | 396,960 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 26,076 | 67.6% |
| COPY | 8,641 | 22.4% |
| POP_TOP | 3,840 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 26,076 | 67.6% |
| RERAISE | 8,641 | 22.4% |
| JUMP_FORWARD | 3,840 | 10.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,403,251 | 28.0% |
| RESUME_CHECK | 5,184,960 | 26.9% |
| CALL | 1,768,674 | 9.2% |
| RETURN_VALUE | 1,335,138 | 6.9% |
| POP_JUMP_IF_FALSE | 1,318,599 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,266,718 | 32.5% |
| ENTER_EXECUTOR | 5,833,522 | 30.3% |
| RETURN_CONST | 1,498,359 | 7.8% |
| LOAD_CONST | 1,370,872 | 7.1% |
| NOP | 1,317,357 | 6.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 30,397 | 78.8% |
| RERAISE | 4,320 | 11.2% |
| CALL_KW | 3,840 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,396 | 78.8% |
| WITH_EXCEPT_START | 4,320 | 11.2% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.0% |
| LOAD_GLOBAL | 1 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,964,334 | 44.3% |
| LOAD_ATTR_MODULE | 1,415,982 | 31.9% |
| LOAD_ATTR | 961,413 | 21.7% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,707,924 | 61.0% |
| CALL | 822,200 | 18.5% |
| LOAD_FAST_LOAD_FAST | 614,502 | 13.9% |
| LOAD_CONST | 235,984 | 5.3% |
| CALL_PY_EXACT_ARGS | 37,440 | 0.8% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,320 | 31.0% |
| LOAD_FAST | 4,320 | 31.0% |
| STORE_FAST | 4,320 | 31.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 6.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,730,512 | 47.6% |
| CALL | 2,034,885 | 11.1% |
| RETURN_VALUE | 1,759,847 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,391,772 | 7.6% |
| CALL_FUNCTION_EX | 948,887 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 8,138,794 | 44.4% |
| STORE_FAST | 1,994,160 | 10.9% |
| RETURN_VALUE | 1,759,847 | 9.6% |
| POP_TOP | 1,335,138 | 7.3% |
| LOAD_FAST_LOAD_FAST | 1,058,085 | 5.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,692 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 7 | 0.0% |
| LOAD_FAST | 5 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,919 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,835 | 3.3% |
| TO_BOOL | 1,055 | 0.1% |
| RETURN_VALUE | 13 | 0.0% |
| LOAD_ATTR | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 666,661 | 54.7% |
| POP_JUMP_IF_FALSE | 552,102 | 45.3% |
| TO_BOOL | 1,055 | 0.1% |
| TO_BOOL_BOOL | 9 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,058,085 | 70.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 452,032 | 29.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,510,117 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 245,602 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 245,602 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 4,320 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,400,271 | 53.9% |
| UNARY_INVERT | 1,510,117 | 23.9% |
| POP_JUMP_IF_FALSE | 1,058,085 | 16.8% |
| LOAD_ATTR | 236,576 | 3.7% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,568,202 | 40.7% |
| STORE_FAST | 1,294,661 | 20.5% |
| UNARY_INVERT | 1,058,085 | 16.8% |
| TO_BOOL_INT | 1,058,085 | 16.8% |
| BUILD_TUPLE | 226,016 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 450,061 | 33.4% |
| JUMP_FORWARD | 439,995 | 32.7% |
| LOAD_FAST | 226,510 | 16.8% |
| POP_TOP | 213,485 | 15.8% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 452,475 | 33.6% |
| SWAP | 450,061 | 33.4% |
| STORE_FAST | 440,955 | 32.7% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 447,675 | 33.8% |
| BUILD_TUPLE | 432,000 | 32.6% |
| LOAD_FAST | 396,960 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 880,155 | 66.4% |
| BUILD_TUPLE | 432,000 | 32.6% |
| STORE_FAST | 12,960 | 1.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,640 | 66.2% |
| FORMAT_SIMPLE | 10,560 | 33.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 66.2% |
| RETURN_VALUE | 10,560 | 33.8% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,478,565 | 43.2% |
| LOAD_FAST_LOAD_FAST | 870,240 | 25.4% |
| BUILD_MAP | 432,000 | 12.6% |
| RETURN_VALUE | 384,000 | 11.2% |
| BINARY_OP | 226,016 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,059,045 | 30.9% |
| YIELD_VALUE | 864,000 | 25.2% |
| BUILD_MAP | 432,000 | 12.6% |
| STORE_FAST | 384,000 | 11.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 11.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,001,781 | 21.2% |
| ENTER_EXECUTOR | 1,231,005 | 13.1% |
| LOAD_FAST_LOAD_FAST | 1,180,646 | 12.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,085,271 | 11.5% |
| BUILD_TUPLE | 1,059,045 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,800,802 | 29.7% |
| RETURN_VALUE | 2,034,885 | 21.6% |
| POP_TOP | 1,768,674 | 18.8% |
| LOAD_FAST | 885,985 | 9.4% |
| TO_BOOL_BOOL | 547,464 | 5.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,247 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,887 | 52.4% |
| RESUME_CHECK | 401,280 | 22.2% |
| CALL_BUILTIN_CLASS | 384,000 | 21.2% |
| POP_TOP | 71,520 | 4.0% |
| STORE_FAST | 4,320 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 296,117 | 98.6% |
| ENTER_EXECUTOR | 4,320 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 248,525 | 82.7% |
| LOAD_FAST | 21,600 | 7.2% |
| RETURN_VALUE | 15,840 | 5.3% |
| STORE_FAST | 10,560 | 3.5% |
| PUSH_EXC_INFO | 3,840 | 1.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 503,678 | 99.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,881 | 0.6% |
| COMPARE_OP | 474 | 0.1% |
| COMPARE_OP_INT | 113 | 0.0% |
| LOAD_GLOBAL_MODULE | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 506,515 | 99.9% |
| COMPARE_OP | 474 | 0.1% |
| COMPARE_OP_INT | 158 | 0.0% |
| COMPARE_OP_STR | 4 | 0.0% |
| POP_JUMP_IF_TRUE | 1 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,486,041 | 100.0% |
| LOAD_ATTR | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,486,046 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 10,560 | 50.0% |
| CALL_BUILTIN_FAST | 10,560 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 21,120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,568,202 | 43.9% |
| STORE_FAST | 1,972,320 | 33.7% |
| LOAD_CONST | 825,600 | 14.1% |
| LOAD_FAST | 438,521 | 7.5% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,568,202 | 43.9% |
| STORE_FAST | 1,972,800 | 33.7% |
| STORE_FAST_STORE_FAST | 820,320 | 14.0% |
| LOAD_ATTR_INSTANCE_VALUE | 427,949 | 7.3% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,058,085 | 66.8% |
| CALL_ALLOC_AND_ENTER_INIT | 439,995 | 27.8% |
| CACHE | 82,080 | 5.2% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,584,600 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,788 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,192 | 66.7% |
| RETURN_CONST | 20,636 | 31.9% |
| LOAD_GLOBAL_MODULE | 960 | 1.5% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,960 | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 422,880 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,833,522 | 71.2% |
| POP_JUMP_IF_NOT_NONE | 811,270 | 9.9% |
| LIST_APPEND | 638,076 | 7.8% |
| STORE_FAST_STORE_FAST | 432,000 | 5.3% |
| CALL_LIST_APPEND | 226,016 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,888,000 | 47.4% |
| CALL | 1,231,005 | 15.0% |
| LOAD_FAST | 887,391 | 10.8% |
| CALL_PY_WITH_DEFAULTS | 666,090 | 8.1% |
| LOAD_ATTR_PROPERTY | 629,033 | 7.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 952,800 | 97.5% |
| SWAP | 10,560 | 1.1% |
| GET_ITER | 8,640 | 0.9% |
| LOAD_FAST | 4,320 | 0.4% |
| FOR_ITER | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 516,480 | 52.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 436,320 | 44.7% |
| SWAP | 10,560 | 1.1% |
| RETURN_CONST | 8,640 | 0.9% |
| LOAD_GLOBAL_MODULE | 4,320 | 0.4% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 24,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,480 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 24,480 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,640 | 59.9% |
| LOAD_FAST | 12,960 | 37.6% |
| LOAD_GLOBAL_MODULE | 832 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,432 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,320,000 | 75.7% |
| POP_TOP | 864,910 | 15.2% |
| ENTER_EXECUTOR | 432,000 | 7.6% |
| LIST_APPEND | 84,480 | 1.5% |
| STORE_FAST_STORE_FAST | 4,320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 4,752,000 | 83.3% |
| FOR_ITER | 952,800 | 16.7% |
| FOR_ITER_LIST | 786 | 0.0% |
| LOAD_FAST | 436 | 0.0% |
| FOR_ITER_RANGE | 284 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 938,768 | 66.9% |
| POP_TOP | 450,650 | 32.1% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 904,631 | 64.5% |
| BUILD_LIST | 439,995 | 31.4% |
| POP_EXCEPT | 26,076 | 1.9% |
| LOAD_GLOBAL_MODULE | 18,716 | 1.3% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 412,060 | 57.0% |
| LOAD_ATTR | 226,016 | 31.3% |
| BINARY_SUBSCR_STR_INT | 84,480 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 638,076 | 88.3% |
| JUMP_BACKWARD | 84,480 | 11.7% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 214,445 | 50.1% |
| RETURN_VALUE | 213,485 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 213,965 | 50.0% |
| STORE_FAST | 213,485 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,749,396 | 80.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,425,863 | 17.0% |
| LOAD_GLOBAL_MODULE | 119,607 | 1.4% |
| CALL | 62,880 | 0.7% |
| LOAD_FAST_LOAD_FAST | 14,892 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,851,811 | 34.0% |
| STORE_SUBSCR_DICT | 1,058,085 | 12.6% |
| PUSH_NULL | 961,413 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 947,946 | 11.3% |
| RETURN_VALUE | 646,025 | 7.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,064,468 | 26.1% |
| LOAD_CONST | 2,921,036 | 24.9% |
| POP_TOP | 1,370,872 | 11.7% |
| POP_JUMP_IF_FALSE | 722,611 | 6.2% |
| LOAD_ATTR_METHOD_NO_DICT | 549,775 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,921,036 | 24.9% |
| CALL | 2,001,781 | 17.1% |
| COMPARE_OP_INT | 1,710,394 | 14.6% |
| LOAD_FAST | 1,264,943 | 10.8% |
| COPY | 825,600 | 7.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,580,160 | 97.4% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.3% |
| STORE_DEREF | 20,640 | 1.3% |
| NOP | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,580,160 | 97.4% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 2.5% |
| PUSH_NULL | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,787,164 | 21.1% |
| STORE_FAST | 9,700,765 | 12.2% |
| POP_JUMP_IF_FALSE | 6,356,629 | 8.0% |
| POP_TOP | 6,266,718 | 7.9% |
| NOP | 4,410,820 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,856,135 | 22.4% |
| RETURN_VALUE | 8,730,512 | 11.0% |
| LOAD_ATTR | 6,749,396 | 8.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,101,705 | 7.7% |
| CALL_PY_EXACT_ARGS | 4,435,337 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 450,061 | 66.6% |
| LOAD_FAST_AND_CLEAR | 226,016 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 450,061 | 66.6% |
| LOAD_FAST_AND_CLEAR | 226,016 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 65.6% |
| POP_JUMP_IF_NONE | 213,979 | 32.5% |
| LOAD_ATTR_CLASS | 12,407 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 65.6% |
| LOAD_GLOBAL_MODULE | 213,979 | 32.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,407 | 1.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,373,815 | 20.5% |
| LOAD_FAST_LOAD_FAST | 1,538,085 | 13.3% |
| POP_JUMP_IF_FALSE | 1,323,047 | 11.4% |
| LOAD_SUPER_ATTR_METHOD | 1,068,645 | 9.2% |
| RETURN_VALUE | 1,058,085 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,758,346 | 23.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,538,990 | 13.3% |
| LOAD_FAST_LOAD_FAST | 1,538,085 | 13.3% |
| CALL | 1,180,646 | 10.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,058,085 | 9.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 42.6% |
| POP_JUMP_IF_FALSE | 40 | 21.3% |
| RESUME_CHECK | 40 | 21.3% |
| POP_JUMP_IF_TRUE | 13 | 6.9% |
| POP_JUMP_IF_NOT_NONE | 8 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 91 | 48.4% |
| LOAD_ATTR | 46 | 24.5% |
| LOAD_GLOBAL_BUILTIN | 43 | 22.9% |
| LOAD_FAST | 5 | 2.7% |
| COMPARE_OP | 1 | 0.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 82,560 | 80.0% |
| CALL_PY_EXACT_ARGS | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 82,560 | 80.0% |
| RESUME_CHECK | 20,640 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 4,684,372 | 29.2% |
| TO_BOOL_BOOL | 3,931,159 | 24.5% |
| COMPARE_OP_INT | 3,050,165 | 19.0% |
| CONTAINS_OP | 1,486,046 | 9.3% |
| COMPARE_OP_STR | 1,118,285 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,356,629 | 39.6% |
| RETURN_CONST | 2,597,831 | 16.2% |
| LOAD_FAST_LOAD_FAST | 1,323,047 | 8.2% |
| POP_TOP | 1,318,599 | 8.2% |
| LOAD_GLOBAL_MODULE | 1,265,328 | 7.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,466 | 95.2% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.4% |
| LOAD_ATTR | 21,120 | 2.2% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 253,651 | 27.0% |
| NOP | 241,805 | 25.7% |
| LOAD_FAST_CHECK | 213,979 | 22.8% |
| LOAD_FAST | 192,601 | 20.5% |
| RETURN_CONST | 18,240 | 1.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,869,432 | 45.0% |
| LOAD_ATTR | 947,946 | 22.8% |
| LOAD_ATTR_INSTANCE_VALUE | 872,313 | 21.0% |
| RETURN_VALUE | 412,540 | 9.9% |
| LOAD_DEREF | 41,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,626,515 | 39.1% |
| RETURN_CONST | 948,207 | 22.8% |
| ENTER_EXECUTOR | 811,270 | 19.5% |
| NOP | 446,342 | 10.7% |
| LOAD_CONST | 213,485 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,401,301 | 66.9% |
| TO_BOOL | 666,661 | 31.8% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,272 | 0.4% |
| COMPARE_OP_INT | 2,181 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 713,557 | 34.1% |
| LOAD_FAST_LOAD_FAST | 669,536 | 32.0% |
| RETURN_CONST | 569,065 | 27.2% |
| LOAD_GLOBAL_MODULE | 55,843 | 2.7% |
| RETURN_VALUE | 46,717 | 2.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,320 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 8,641 | 66.7% |
| POP_JUMP_IF_TRUE | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,321 | 50.0% |
| PUSH_EXC_INFO | 4,320 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,597,831 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,919,820 | 25.1% |
| POP_TOP | 1,498,359 | 19.6% |
| POP_JUMP_IF_NOT_NONE | 948,207 | 12.4% |
| POP_JUMP_IF_TRUE | 569,065 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,403,251 | 70.7% |
| EXIT_INIT_CHECK | 930,870 | 12.2% |
| INTERPRETER_EXIT | 733,743 | 9.6% |
| TO_BOOL_BOOL | 495,943 | 6.5% |
| STORE_FAST | 47,677 | 0.6% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 28,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,320 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,932 | 57.1% |
| LOAD_FAST_LOAD_FAST | 14,880 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 19.5% |
| STORE_ATTR | 640 | 1.0% |
| SWAP | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_CONST | 8,650 | 13.0% |
| LOAD_FAST | 8,645 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 4,320 | 6.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_DEREF | 20,640 | 20.0% |
| LOAD_FAST | 20,640 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,752,000 | 21.5% |
| CALL | 2,800,802 | 12.7% |
| RETURN_VALUE | 1,994,160 | 9.0% |
| COPY | 1,972,800 | 8.9% |
| BINARY_OP | 1,294,661 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,700,765 | 43.9% |
| JUMP_BACKWARD | 4,320,000 | 19.5% |
| NOP | 3,151,141 | 14.3% |
| COPY | 1,972,320 | 8.9% |
| JUMP_FORWARD | 938,768 | 4.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 516,480 | 53.9% |
| FOR_ITER_LIST | 432,000 | 45.0% |
| COPY | 10,560 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 432,000 | 45.0% |
| YIELD_VALUE | 432,000 | 45.0% |
| LOAD_FAST | 84,480 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 10,560 | 1.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,741,683 | 46.3% |
| COPY | 820,320 | 21.8% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 21.7% |
| STORE_FAST_STORE_FAST | 384,000 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,268,032 | 33.7% |
| LOAD_FAST_LOAD_FAST | 846,131 | 22.5% |
| STORE_FAST | 816,000 | 21.7% |
| ENTER_EXECUTOR | 432,000 | 11.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.2% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 450,061 | 20.1% |
| LOAD_FAST_AND_CLEAR | 450,061 | 20.1% |
| ENTER_EXECUTOR | 439,501 | 19.6% |
| BINARY_OP_ADD_INT | 427,956 | 19.1% |
| LOAD_FAST | 234,619 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 460,635 | 20.6% |
| BUILD_LIST | 450,061 | 20.1% |
| STORE_FAST | 450,061 | 20.1% |
| FOR_ITER_LIST | 439,501 | 19.6% |
| STORE_ATTR_INSTANCE_VALUE | 427,949 | 19.1% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,888,000 | 75.0% |
| BUILD_TUPLE | 864,000 | 16.7% |
| STORE_FAST_LOAD_FAST | 432,000 | 8.3% |
| CALL_STR_1 | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,752,000 | 91.6% |
| INTERPRETER_EXIT | 432,960 | 8.4% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 226,510 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 226,510 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 816,269 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 427,956 | 51.5% |
| STORE_FAST | 384,000 | 46.3% |
| BINARY_SLICE | 13,920 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,320 | 0.5% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 50.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 50.0% |
| LOAD_FAST | 960 | 50.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 213,979 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 214,099 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,822 | 79.6% |
| LOAD_CONST | 46,717 | 18.7% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 245,539 | 98.3% |
| CALL_BUILTIN_CLASS | 4,320 | 1.7% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 74,880 | 87.6% |
| LOAD_CONST | 10,560 | 12.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 74,880 | 87.6% |
| CONVERT_VALUE | 10,560 | 12.4% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 66.7% |
| LOAD_FAST_LOAD_FAST | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 66.7% |
| STORE_FAST | 4,320 | 33.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 84,480 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 24,480 | 85.0% |
| JUMP_FORWARD | 4,320 | 15.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 460,635 | 49.5% |
| LOAD_FAST | 445,275 | 47.8% |
| CALL | 24,960 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 490,875 | 52.7% |
| COPY_FREE_VARS | 439,995 | 47.3% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,000 | 83.1% |
| LOAD_CONST | 4,800 | 8.3% |
| BINARY_OP_ADD_INT | 4,320 | 7.5% |
| PUSH_NULL | 599 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,403 | 92.4% |
| POP_TOP | 4,320 | 7.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 58.5% |
| LOAD_FAST | 240,030 | 36.6% |
| LOAD_CONST | 11,040 | 1.7% |
| LOAD_GLOBAL_BUILTIN | 7,680 | 1.2% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 610,510 | 93.0% |
| GET_ITER | 28,800 | 4.4% |
| LOAD_FAST | 12,960 | 2.0% |
| CALL_BUILTIN_CLASS | 4,320 | 0.7% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 770,597 | 57.7% |
| LOAD_CONST | 331,565 | 24.8% |
| LOAD_FAST_LOAD_FAST | 129,702 | 9.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 61,011 | 4.6% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 479,078 | 35.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 414,131 | 31.0% |
| TO_BOOL_BOOL | 324,365 | 24.3% |
| UNPACK_SEQUENCE_TUPLE | 61,011 | 4.6% |
| POP_TOP | 10,930 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 387,840 | 45.8% |
| BUILD_TUPLE | 384,000 | 45.3% |
| CALL | 48,604 | 5.7% |
| LOAD_FAST_CHECK | 12,407 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 785,760 | 92.7% |
| RETURN_VALUE | 61,011 | 7.2% |
| LOAD_FAST | 960 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 88.9% |
| LOAD_FAST | 10,560 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 84,480 | 88.9% |
| LOAD_FAST | 10,560 | 11.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,071,045 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,071,045 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,977 | 93.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 7.0% |
| CALL | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,342 | 87.1% |
| CALL_PY_EXACT_ARGS | 24,960 | 8.4% |
| LOAD_FAST | 4,320 | 1.5% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 1.5% |
| CALL_BUILTIN_CLASS | 4,320 | 1.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 226,016 | 96.3% |
| LOAD_FAST | 8,640 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 226,016 | 96.3% |
| LOAD_GLOBAL_MODULE | 8,640 | 3.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,498,080 | 99.9% |
| LOAD_CONST | 960 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 335 | 0.0% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,058,085 | 70.6% |
| STORE_FAST | 440,337 | 29.4% |
| TO_BOOL_NONE | 960 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,480 | 85.0% |
| BUILD_TUPLE | 4,320 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20,160 | 70.0% |
| LOAD_FAST | 8,640 | 30.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,111,913 | 93.7% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,418 | 6.2% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 548,309 | 46.2% |
| STORE_FAST | 432,000 | 36.4% |
| LOAD_FAST | 63,840 | 5.4% |
| CALL_BUILTIN_FAST | 61,011 | 5.1% |
| RETURN_VALUE | 38,734 | 3.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 666,921 | 92.0% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,607 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 688,528 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,698,213 | 45.7% |
| LOAD_FAST | 4,435,337 | 43.2% |
| LOAD_FAST_LOAD_FAST | 446,880 | 4.4% |
| LOAD_SUPER_ATTR_METHOD | 439,995 | 4.3% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,237,056 | 99.7% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 939,472 | 37.9% |
| ENTER_EXECUTOR | 666,090 | 26.8% |
| LOAD_ATTR_MODULE | 439,995 | 17.7% |
| LOAD_FAST | 288,416 | 11.6% |
| LOAD_CONST | 80,721 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,423,336 | 57.4% |
| COPY_FREE_VARS | 1,058,085 | 42.6% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 88.9% |
| YIELD_VALUE | 960 | 11.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 436,320 | 99.8% |
| LOAD_FAST | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 436,320 | 99.8% |
| LOAD_FAST | 960 | 0.2% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 960 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,710,394 | 56.0% |
| LOAD_ATTR_INSTANCE_VALUE | 877,966 | 28.8% |
| LOAD_FAST | 432,000 | 14.2% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,050,165 | 99.9% |
| POP_JUMP_IF_TRUE | 2,181 | 0.1% |
| COMPARE_OP | 113 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,098,713 | 95.7% |
| LOAD_CONST | 44,640 | 3.9% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,118,285 | 97.4% |
| COPY | 10,560 | 0.9% |
| LOAD_FAST | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,272 | 0.7% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,752,000 | 99.8% |
| GET_ITER | 8,640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,752,000 | 99.8% |
| POP_TOP | 8,640 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,318,230 | 75.0% |
| SWAP | 439,501 | 25.0% |
| JUMP_BACKWARD | 786 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 659,458 | 37.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 452,032 | 25.7% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.6% |
| LOAD_FAST | 213,979 | 12.2% |
| RETURN_CONST | 855 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 23,640 | 98.8% |
| JUMP_BACKWARD | 284 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,904 | 99.9% |
| LOAD_FAST | 20 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,640 | 90.0% |
| LOAD_FAST | 960 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,600 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 61,011 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,284 | 81.9% |
| LOAD_FAST_CHECK | 12,407 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,856,135 | 89.9% |
| LOAD_FAST_LOAD_FAST | 1,538,990 | 7.8% |
| COPY | 427,949 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 18,081 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,498,693 | 22.7% |
| LOAD_FAST | 3,023,945 | 15.2% |
| TO_BOOL_BOOL | 1,596,635 | 8.0% |
| CONTAINS_OP | 1,486,041 | 7.5% |
| LOAD_ATTR | 1,425,863 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,924 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,022 | 39.8% |
| CALL | 111,484 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,418 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,498,693 | 87.2% |
| LOAD_FAST | 509,597 | 9.9% |
| LOAD_ATTR | 62,894 | 1.2% |
| LOAD_ATTR_SLOT | 62,880 | 1.2% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,129,728 | 41.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,111,913 | 21.6% |
| CALL | 1,085,271 | 21.0% |
| LOAD_CONST | 549,775 | 10.7% |
| LOAD_FAST_LOAD_FAST | 257,857 | 5.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,101,705 | 70.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,074,305 | 12.3% |
| LOAD_FAST_LOAD_FAST | 1,058,085 | 12.2% |
| BINARY_SUBSCR | 432,000 | 5.0% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,698,213 | 54.0% |
| LOAD_FAST | 2,383,319 | 27.4% |
| CALL_PY_WITH_DEFAULTS | 939,472 | 10.8% |
| LOAD_FAST_LOAD_FAST | 508,800 | 5.8% |
| LOAD_CONST | 94,641 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,966,780 | 100.0% |
| LOAD_ATTR | 87 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,415,982 | 72.0% |
| CALL_PY_WITH_DEFAULTS | 439,995 | 22.4% |
| STORE_DEREF | 41,280 | 2.1% |
| LOAD_CONST | 26,400 | 1.3% |
| LOAD_FAST | 20,640 | 1.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,088,805 | 70.7% |
| LOAD_FAST_LOAD_FAST | 452,032 | 29.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,058,085 | 68.7% |
| UNARY_INVERT | 452,032 | 29.3% |
| RETURN_VALUE | 10,560 | 0.7% |
| LOAD_CONST | 10,560 | 0.7% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 629,033 | 68.8% |
| LOAD_FAST | 264,018 | 28.9% |
| RETURN_VALUE | 20,640 | 2.3% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 905,691 | 99.0% |
| TO_BOOL_BOOL | 8,960 | 1.0% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 62,880 | 85.6% |
| CALL_BUILTIN_FAST | 10,560 | 14.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,154,245 | 51.1% |
| LOAD_FAST | 1,091,205 | 17.7% |
| NOP | 650,825 | 10.5% |
| STORE_FAST | 612,417 | 9.9% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,013,005 | 48.8% |
| LOAD_DEREF | 1,580,160 | 25.6% |
| CALL_ISINSTANCE | 1,071,045 | 17.3% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 6.4% |
| LOAD_GLOBAL_MODULE | 36,960 | 0.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,721,642 | 27.9% |
| RESUME_CHECK | 2,468,426 | 18.5% |
| NOP | 1,589,226 | 11.9% |
| POP_JUMP_IF_FALSE | 1,265,328 | 9.5% |
| LOAD_GLOBAL_MODULE | 1,174,282 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,400,271 | 25.5% |
| LOAD_FAST_LOAD_FAST | 2,373,815 | 17.8% |
| LOAD_ATTR_MODULE | 1,966,780 | 14.8% |
| LOAD_FAST | 1,886,830 | 14.2% |
| LOAD_GLOBAL_MODULE | 1,174,282 | 8.8% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 67,200 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,512,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,068,645 | 70.6% |
| CALL_PY_EXACT_ARGS | 439,995 | 29.1% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,237,056 | 34.4% |
| CACHE | 9,222,461 | 31.0% |
| FOR_ITER_GEN | 4,752,000 | 16.0% |
| COPY_FREE_VARS | 1,584,600 | 5.3% |
| CALL_PY_WITH_DEFAULTS | 1,423,336 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,787,164 | 56.4% |
| POP_TOP | 5,184,960 | 17.4% |
| LOAD_GLOBAL_BUILTIN | 3,154,245 | 10.6% |
| LOAD_GLOBAL_MODULE | 2,468,426 | 8.3% |
| NOP | 1,209,285 | 4.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,468,448 | 69.4% |
| LOAD_FAST_LOAD_FAST | 636,315 | 17.9% |
| SWAP | 427,949 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,919,820 | 53.9% |
| LOAD_FAST | 680,916 | 19.1% |
| LOAD_GLOBAL_MODULE | 599,355 | 16.8% |
| LOAD_CONST | 160,310 | 4.5% |
| LOAD_FAST_LOAD_FAST | 96,960 | 2.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,880 | 85.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 14.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,440 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 1,058,085 | 93.8% |
| LOAD_FAST | 35,574 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.3% |
| CALL | 7,680 | 0.7% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,062,466 | 94.2% |
| RETURN_CONST | 24,480 | 2.2% |
| LOAD_CONST | 20,640 | 1.8% |
| LOAD_GLOBAL_MODULE | 20,640 | 1.8% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 64.8% |
| COPY | 261 | 35.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 64.8% |
| POP_JUMP_IF_FALSE | 261 | 35.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,596,635 | 28.6% |
| CALL_ISINSTANCE | 1,071,045 | 19.2% |
| RETURN_VALUE | 784,174 | 14.1% |
| CALL | 547,464 | 9.8% |
| LOAD_FAST | 541,117 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,931,159 | 70.5% |
| POP_JUMP_IF_TRUE | 1,401,301 | 25.1% |
| UNARY_NOT | 245,602 | 4.4% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,568,202 | 54.8% |
| BINARY_OP | 1,058,085 | 22.6% |
| LOAD_FAST | 1,058,085 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,684,372 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 448,635 | 93.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 480,795 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,773 | 79.8% |
| LOAD_FAST | 20,640 | 11.5% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,373 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 61,011 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 61,011 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 452,032 | 25.9% |
| FOR_ITER | 436,320 | 25.0% |
| LOAD_FAST_CHECK | 432,000 | 24.7% |
| CALL_BUILTIN_FAST | 414,131 | 23.7% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,741,683 | 99.7% |
| LOAD_FAST | 5,280 | 0.3% |


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
|     deferred | 6,308,031 | 79.5% |
|          hit | 1,627,704 | 20.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 47 | 2.0% |
| Failure | 2,277 | 98.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,164 | 51.1% |
| or | 680 | 29.9% |
| remainder | 233 | 10.2% |
| add different types | 160 | 7.0% |
| add other | 40 | 1.8% |


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
|     deferred | 478,717 | 69.3% |
|          hit | 211,680 | 30.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 219 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 219 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,421,062 | 29.8% |
|        deopt | 60 | 0.0% |
|          hit | 22,214,471 | 70.2% |
|         miss | 4,380 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 128 | 1.4% |
| Failure | 9,174 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,541 | 27.7% |
| cfunc noargs | 1,832 | 20.0% |
| class no vectorcall | 1,290 | 14.1% |
| meth descr varargs keywords | 831 | 9.1% |
| class mutable | 452 | 4.9% |
| cfunc varargs keywords | 372 | 4.1% |
| other | 360 | 3.9% |
| cfunc varargs | 320 | 3.5% |
| bound method | 296 | 3.2% |
| operator wrapper | 240 | 2.6% |
| cmethod | 200 | 2.2% |
| meth descr method fastcall keywords | 200 | 2.2% |
| wrong number arguments | 160 | 1.7% |
| method wrapper | 80 | 0.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 506,516 | 10.8% |
|        deopt | 113 | 0.0% |
|          hit | 4,193,386 | 89.1% |
|         miss | 6,750 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 162 | 21.6% |
| Failure | 587 | 78.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 332 | 56.6% |
| float long | 175 | 29.8% |
| big int | 80 | 13.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 976,320 | 13.0% |
|          hit | 6,552,681 | 87.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 440 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 140 | 31.8% |
| enumerate | 140 | 31.8% |
| itertools | 80 | 18.2% |
| callable | 80 | 18.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,383,110 | 17.8% |
|        deopt | 4,192 | 0.0% |
|          hit | 38,351,472 | 81.6% |
|         miss | 230,256 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,365 | 41.3% |
| Failure | 6,201 | 58.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,425 | 23.0% |
| not managed dict | 1,348 | 21.7% |
| shadowed | 1,245 | 20.1% |
| non overriding descriptor | 598 | 9.6% |
| class attr descriptor | 360 | 5.8% |
| class method obj | 280 | 4.5% |
| metaclass attribute | 280 | 4.5% |
| has managed dict | 240 | 3.9% |
| non object slot | 160 | 2.6% |
| class attr simple | 145 | 2.3% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 54 | 0.0% |
|        deopt | 41 | 0.0% |
|          hit | 19,493,926 | 100.0% |
|         miss | 5,781 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 175 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,580,160 | 100.0% |


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
|     deferred | 65,776 | 1.8% |
|        deopt | 2,780 | 0.1% |
|          hit | 3,484,340 | 94.2% |
|         miss | 148,120 | 4.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,788 | 81.3% |
| Failure | 640 | 18.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 400 | 62.5% |
| class attr simple | 160 | 25.0% |
| no dict | 80 | 12.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 22,565 | 2.0% |
|          hit | 1,128,226 | 98.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7 | 3.4% |
| Failure | 200 | 96.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 120 | 60.0% |
| other | 80 | 40.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,218,763 | 10.0% |
|          hit | 10,924,223 | 90.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9 | 0.8% |
| Failure | 1,055 | 99.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 336 | 31.8% |
| tuple | 220 | 20.9% |
| sequence | 219 | 20.8% |
| set | 200 | 19.0% |
| other | 80 | 7.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 2,623,974 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 241,718,977 | 54.9% |
| Not specialized | 56,752,966 | 12.9% |
| Specialized | 142,085,586 | 32.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 73,786,976,294,838,206,460 | 100.0% |
| CALL | 9,421,062 | 0.0% |
| LOAD_ATTR | 8,383,110 | 0.0% |
| BINARY_OP | 6,308,031 | 0.0% |
| TO_BOOL | 1,218,763 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| COMPARE_OP | 506,516 | 0.0% |
| BINARY_SUBSCR | 478,717 | 0.0% |
| STORE_ATTR | 65,776 | 0.0% |
| STORE_SUBSCR | 22,565 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,430 | 40.6% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,706 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| COMPARE_OP_INT | 6,750 | 1.7% |
| LOAD_GLOBAL_MODULE | 5,781 | 1.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
| RESUME | 4 | 0.0% |
| RESUME_CHECK | 4 | 0.0% |
| CACHE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 9,309,821 | 31.3% |
| Calls to Python functions inlined | 20,456,849 | 68.7% |
| Calls via PyEval_EvalFrame (total) | 9,309,821 | 31.3% |
| Calls via PyEval_EvalFrame (vector) | 8,871,581 | 29.8% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,871,581 | 29.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.6% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.3% |
| Calls via PyEval_EvalFrame (api) | 542,452 | 1.8% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 38,620 | 0.1% |
| Frames pushed | 26,067,411 | 87.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 16,474,462 | 43.6% |
| Frees to freelist | 16,475,940 |  |
| Allocations | 21,325,058 | 56.4% |
| Allocations to 512 bytes | 21,112,993 | 55.9% |
| Allocations to 4 kbytes | 86,278 | 0.2% |
| Allocations over 4 kbytes | 125,787 | 0.3% |
| Frees | 22,646,688 |  |
| New values | 65,280 |  |
| Interpreter increfs | 176,604,687 | 71.4% |
| Interpreter decrefs | 191,943,167 | 68.2% |
| Increfs | 70,755,631 | 28.6% |
| Decrefs | 89,396,795 | 31.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 10,427,502 |  |
| Method cache misses | 16,562 |  |
| Method cache collisions | 25,949 |  |
| Method cache dunder hits | 9,192,683 |  |
| Method cache dunder misses | 9,387 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 16 | 384 | 114,802 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 335,742 |  |
| Traces created | 202 | 0.1% |
| Traces executed | 8,196,815 |  |
| Uops executed | 97,594,515 | 11.91 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 335,540 | 166,108.9% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 29.7% |
| <= 32 | 40 | 19.8% |
| <= 64 | 40 | 19.8% |
| <= 128 | 62 | 30.7% |


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
| <= 16 | 60 | 29.7% |
| <= 32 | 80 | 39.6% |
| <= 64 | 12 | 5.9% |
| <= 128 | 50 | 24.8% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 768,000 | 9.4% |
| <= 8 | 1,784,030 | 21.8% |
| <= 16 | 4,537,898 | 55.4% |
| <= 32 | 848,738 | 10.4% |
| <= 64 | 9 | 0.0% |
| <= 128 | 258,071 | 3.1% |
| <= 256 | 2 | 0.0% |
| <= 512 | 5 | 0.0% |
| <= 1,024 | 5 | 0.0% |
| <= 2,048 | 11 | 0.0% |
| <= 4,096 | 15 | 0.0% |
| <= 8,192 | 31 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 23,638,882 | 24.2% | 24.2% |  |
| LOAD_FAST | 11,540,387 | 11.8% | 36.0% |  |
| _EXIT_TRACE | 8,196,815 | 8.4% | 44.4% |  |
| _POP_JUMP_IF_TRUE | 6,991,229 | 7.2% | 51.6% |  |
| _ITER_CHECK_LIST | 6,267,341 | 6.4% | 58.0% |  |
| _IS_ITER_EXHAUSTED_LIST | 6,267,341 | 6.4% | 64.5% |  |
| STORE_FAST | 5,796,321 | 5.9% | 70.4% |  |
| _ITER_NEXT_LIST | 4,724,637 | 4.8% | 75.2% |  |
| _GUARD_GLOBALS_VERSION | 2,538,773 | 2.6% | 77.8% |  |
| POP_TOP | 1,884,077 | 1.9% | 79.8% |  |
| _GUARD_BUILTINS_VERSION | 1,272,980 | 1.3% | 81.1% |  |
| _LOAD_GLOBAL_BUILTINS | 1,272,980 | 1.3% | 82.4% |  |
| _LOAD_GLOBAL_MODULE | 1,265,793 | 1.3% | 83.7% |  |
| PUSH_NULL | 1,262,049 | 1.3% | 85.0% |  |
| _CHECK_ATTR_MODULE | 1,051,439 | 1.1% | 86.0% |  |
| _LOAD_ATTR_MODULE | 1,051,439 | 1.1% | 87.1% |  |
| _GUARD_TYPE_VERSION | 862,163 | 0.9% | 88.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 768,511 | 0.8% | 88.8% |  |
| _GUARD_KEYS_VERSION | 768,511 | 0.8% | 89.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 768,511 | 0.8% | 90.4% |  |
| _SAVE_CURRENT_IP | 666,100 | 0.7% | 91.0% |  |
| _ITER_CHECK_RANGE | 656,615 | 0.7% | 91.7% |  |
| _IS_ITER_EXHAUSTED_RANGE | 656,615 | 0.7% | 92.4% |  |
| LOAD_CONST | 614,746 | 0.6% | 93.0% |  |
| RESUME_CHECK | 568,751 | 0.6% | 93.6% |  |
| _CHECK_PEP_523 | 568,751 | 0.6% | 94.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 568,751 | 0.6% | 94.8% |  |
| _CHECK_STACK_SPACE | 568,751 | 0.6% | 95.4% |  |
| _INIT_CALL_PY_EXACT_ARGS | 568,751 | 0.6% | 95.9% |  |
| _PUSH_FRAME | 568,751 | 0.6% | 96.5% |  |
| LOAD_ATTR | 467,290 | 0.5% | 97.0% |  |
| _ITER_NEXT_RANGE | 434,870 | 0.4% | 97.4% |  |
| BINARY_SUBSCR_LIST_INT | 422,650 | 0.4% | 97.9% |  |
| CALL_BUILTIN_CLASS | 418,330 | 0.4% | 98.3% |  |
| TO_BOOL_BOOL | 262,354 | 0.3% | 98.6% |  |
| _POP_JUMP_IF_FALSE | 258,549 | 0.3% | 98.8% |  |
| CALL_BUILTIN_FAST | 213,485 | 0.2% | 99.1% |  |
| GET_ITER | 209,165 | 0.2% | 99.3% |  |
| CALL_LEN | 209,165 | 0.2% | 99.5% |  |
| _POP_FRAME | 97,349 | 0.1% | 99.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 77,695 | 0.1% | 99.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 77,695 | 0.1% | 99.7% |  |
| _IS_NONE | 48,480 | 0.0% | 99.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 48,480 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 48,480 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 20,019 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 11,918 | 0.0% | 99.9% |  |
| _ITER_CHECK_TUPLE | 10,560 | 0.0% | 99.9% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 10,560 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,800 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 4,320 | 0.0% | 100.0% |  |
| CONTAINS_OP | 4,039 | 0.0% | 100.0% |  |
| COPY | 4,039 | 0.0% | 100.0% |  |
| SWAP | 4,039 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 4,039 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 4,039 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 4,039 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 4,039 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 4,039 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 4,039 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,840 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 960 | 0.0% | 100.0% |  |
| IS_OP | 389 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 279,520 |
| FOR_ITER | 56,020 |
| CALL | 70 |
| LOAD_ATTR_PROPERTY | 40 |
| BEFORE_WITH | 20 |
| CALL_KW | 20 |
| YIELD_VALUE | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |


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
Stats gathered on: 2023-10-09
