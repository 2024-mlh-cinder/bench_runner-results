
# Pystats results

- benchmark: concurrent_imap
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 95,386,225 | 17.9% | 17.9% |  |
| RESUME_CHECK | 36,463,886 | 6.8% | 24.7% | 0.0% |
| STORE_FAST | 27,734,762 | 5.2% | 29.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 24,001,027 | 4.5% | 34.4% | 0.9% |
| POP_TOP | 23,716,409 | 4.4% | 38.8% |  |
| RETURN_VALUE | 21,652,663 | 4.1% | 42.9% |  |
| POP_JUMP_IF_FALSE | 18,542,462 | 3.5% | 46.4% |  |
| LOAD_GLOBAL_MODULE | 15,324,064 | 2.9% | 49.2% | 0.0% |
| LOAD_CONST | 14,848,700 | 2.8% | 52.0% |  |
| LOAD_FAST_LOAD_FAST | 14,514,816 | 2.7% | 54.7% |  |
| CALL_PY_EXACT_ARGS | 12,064,743 | 2.3% | 57.0% | 0.0% |
| INTERPRETER_EXIT | 11,811,649 | 2.2% | 59.2% |  |
| CALL | 10,807,040 | 2.0% | 61.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,128,670 | 1.9% | 63.1% | 0.8% |
| LOAD_ATTR | 10,109,389 | 1.9% | 65.0% |  |
| ENTER_EXECUTOR | 10,038,121 | 1.9% | 66.9% |  |
| RETURN_CONST | 9,054,534 | 1.7% | 68.6% |  |
| NOP | 8,723,105 | 1.6% | 70.2% |  |
| JUMP_BACKWARD | 7,843,351 | 1.5% | 71.7% |  |
| LOAD_GLOBAL_BUILTIN | 7,705,876 | 1.4% | 73.2% | 0.0% |
| COPY | 7,147,367 | 1.3% | 74.5% |  |
| YIELD_VALUE | 6,913,660 | 1.3% | 75.8% |  |
| BINARY_OP | 6,834,707 | 1.3% | 77.1% |  |
| TO_BOOL_BOOL | 6,619,803 | 1.2% | 78.3% |  |
| FOR_ITER_GEN | 6,347,440 | 1.2% | 79.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,295,345 | 1.2% | 80.7% |  |
| PUSH_NULL | 5,648,062 | 1.1% | 81.7% |  |
| TO_BOOL_INT | 5,044,078 | 0.9% | 82.7% |  |
| POP_JUMP_IF_NOT_NONE | 4,954,302 | 0.9% | 83.6% |  |
| STORE_FAST_STORE_FAST | 4,798,235 | 0.9% | 84.5% |  |
| BUILD_TUPLE | 4,240,782 | 0.8% | 85.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 4,199,765 | 0.8% | 86.1% | 4.7% |
| COMPARE_OP_INT | 3,683,006 | 0.7% | 86.8% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 2,872,233 | 0.5% | 87.3% |  |
| POP_JUMP_IF_TRUE | 2,688,813 | 0.5% | 87.8% |  |
| SWAP | 2,552,610 | 0.5% | 88.3% |  |
| CALL_FUNCTION_EX | 2,413,966 | 0.5% | 88.8% |  |
| GET_ITER | 2,329,041 | 0.4% | 89.2% |  |
| LOAD_ATTR_MODULE | 2,302,761 | 0.4% | 89.6% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,110,915 | 0.4% | 90.0% |  |
| FOR_ITER_LIST | 2,021,402 | 0.4% | 90.4% |  |
| CALL_BUILTIN_CLASS | 1,966,640 | 0.4% | 90.8% |  |
| BEFORE_WITH | 1,820,615 | 0.3% | 91.1% |  |
| LOAD_DEREF | 1,781,324 | 0.3% | 91.4% |  |
| COPY_FREE_VARS | 1,731,304 | 0.3% | 91.8% |  |
| CONTAINS_OP | 1,710,867 | 0.3% | 92.1% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,671,677 | 0.3% | 92.4% |  |
| BUILD_MAP | 1,657,977 | 0.3% | 92.7% |  |
| JUMP_FORWARD | 1,645,299 | 0.3% | 93.0% |  |
| LOAD_SUPER_ATTR_METHOD | 1,634,984 | 0.3% | 93.3% |  |
| UNARY_INVERT | 1,631,017 | 0.3% | 93.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,618,461 | 0.3% | 93.9% | 0.0% |
| TO_BOOL | 1,576,631 | 0.3% | 94.2% |  |
| CALL_BUILTIN_FAST | 1,562,935 | 0.3% | 94.5% |  |
| COMPARE_OP_STR | 1,475,924 | 0.3% | 94.8% |  |
| BUILD_LIST | 1,470,925 | 0.3% | 95.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,459,967 | 0.3% | 95.3% |  |
| FOR_ITER | 1,305,260 | 0.2% | 95.6% |  |
| STORE_FAST_LOAD_FAST | 1,280,240 | 0.2% | 95.8% |  |
| STORE_SUBSCR_DICT | 1,230,004 | 0.2% | 96.1% |  |
| UNPACK_SEQUENCE_TUPLE | 1,169,499 | 0.2% | 96.3% |  |
| CALL_ISINSTANCE | 1,155,547 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,131,859 | 0.2% | 96.7% | 0.0% |
| BINARY_OP_ADD_INT | 1,108,501 | 0.2% | 96.9% |  |
| POP_JUMP_IF_NONE | 1,090,194 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 1,022,934 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,022,934 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 1,001,615 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 960,677 | 0.2% | 97.9% | 0.0% |
| LOAD_FAST_CHECK | 824,068 | 0.2% | 98.0% |  |
| LIST_APPEND | 800,375 | 0.1% | 98.2% |  |
| LOAD_FAST_AND_CLEAR | 738,346 | 0.1% | 98.3% |  |
| BINARY_SUBSCR | 635,233 | 0.1% | 98.4% |  |
| CALL_LEN | 620,369 | 0.1% | 98.5% |  |
| CALL_TUPLE_1 | 583,120 | 0.1% | 98.7% |  |
| COMPARE_OP | 568,685 | 0.1% | 98.8% |  |
| DICT_MERGE | 564,260 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 531,757 | 0.1% | 99.0% |  |
| LIST_EXTEND | 461,592 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 408,936 | 0.1% | 99.1% |  |
| CALL_KW | 346,868 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 328,471 | 0.1% | 99.3% |  |
| UNARY_NOT | 272,834 | 0.1% | 99.3% |  |
| CALL_LIST_APPEND | 258,555 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 257,929 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 247,301 | 0.0% | 99.4% |  |
| BINARY_SUBSCR_LIST_INT | 242,016 | 0.0% | 99.5% |  |
| TO_BOOL_NONE | 240,507 | 0.0% | 99.5% | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 230,742 | 0.0% | 99.6% |  |
| MAKE_CELL | 137,900 | 0.0% | 99.6% |  |
| STORE_DEREF | 137,620 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 126,920 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 114,880 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 112,600 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 112,600 | 0.0% | 99.7% |  |
| STORE_ATTR | 100,139 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 97,980 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 97,980 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 91,479 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 0.0% | 99.8% |  |
| DELETE_ATTR | 86,376 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 78,204 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 78,193 | 0.0% | 99.9% | 8.2% |
| MAKE_FUNCTION | 63,640 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 55,680 | 0.0% | 99.9% |  |
| POP_EXCEPT | 47,373 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 47,373 | 0.0% | 99.9% |  |
| IS_OP | 46,672 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 41,613 | 0.0% | 99.9% |  |
| BUILD_STRING | 41,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 39,160 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 39,000 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 38,380 | 0.0% | 99.9% |  |
| IMPORT_NAME | 33,760 | 0.0% | 99.9% |  |
| IMPORT_FROM | 33,420 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 31,258 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 28,160 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 27,480 | 0.0% | 100.0% |  |
| BINARY_SLICE | 19,820 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 18,900 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,772 | 0.0% | 100.0% |  |
| RERAISE | 17,280 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 14,500 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,900 | 0.0% | 100.0% |  |
| END_FOR | 11,520 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,940 | 0.0% | 100.0% | 0.1% |
| RAISE_VARARGS | 5,780 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,760 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 3,420 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,660 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 1,440 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 1,023 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,712,196 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 20,360,064 | 3.8% | 7.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 12,018,183 | 2.3% | 10.1% |
| CACHE RESUME_CHECK | 11,697,777 | 2.2% | 12.3% |
| STORE_FAST LOAD_FAST | 11,688,204 | 2.2% | 14.5% |
| LOAD_FAST RETURN_VALUE | 10,549,989 | 2.0% | 16.5% |
| RETURN_VALUE INTERPRETER_EXIT | 10,361,336 | 1.9% | 18.4% |
| LOAD_FAST LOAD_ATTR | 7,716,845 | 1.4% | 19.9% |
| POP_TOP ENTER_EXECUTOR | 7,500,777 | 1.4% | 21.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,485,156 | 1.4% | 22.7% |
| POP_TOP LOAD_FAST | 7,313,860 | 1.4% | 24.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 7,047,949 | 1.3% | 25.4% |
| RESUME_CHECK POP_TOP | 6,913,520 | 1.3% | 26.7% |
| RETURN_CONST POP_TOP | 6,403,704 | 1.2% | 27.9% |
| JUMP_BACKWARD FOR_ITER_GEN | 6,335,920 | 1.2% | 29.1% |
| YIELD_VALUE STORE_FAST | 6,335,920 | 1.2% | 30.2% |
| FOR_ITER_GEN RESUME_CHECK | 6,335,920 | 1.2% | 31.4% |
| STORE_FAST JUMP_BACKWARD | 5,760,000 | 1.1% | 32.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,487,009 | 1.0% | 33.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,390,138 | 1.0% | 34.5% |
| ENTER_EXECUTOR YIELD_VALUE | 5,183,440 | 1.0% | 35.5% |
| NOP LOAD_FAST | 5,156,244 | 1.0% | 36.5% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 5,043,938 | 0.9% | 37.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,038,207 | 0.9% | 38.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,529,706 | 0.8% | 39.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 4,035,610 | 0.8% | 40.0% |
| STORE_FAST NOP | 3,752,904 | 0.7% | 40.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,698,280 | 0.7% | 41.4% |
| LOAD_CONST LOAD_CONST | 3,692,676 | 0.7% | 42.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,679,123 | 0.7% | 42.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 3,659,416 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 3,644,156 | 0.7% | 44.1% |
| LOAD_FAST LOAD_CONST | 3,641,161 | 0.7% | 44.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,550,411 | 0.7% | 45.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,527,501 | 0.7% | 46.1% |
| PUSH_NULL LOAD_FAST | 3,448,868 | 0.6% | 46.8% |
| LOAD_ATTR LOAD_FAST | 3,376,999 | 0.6% | 47.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 3,081,422 | 0.6% | 48.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 3,027,234 | 0.6% | 48.6% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,849,947 | 0.5% | 49.1% |
| BINARY_OP COPY | 2,768,644 | 0.5% | 49.6% |
| COPY TO_BOOL_INT | 2,768,324 | 0.5% | 50.1% |
| COPY STORE_FAST | 2,630,400 | 0.5% | 50.6% |
| STORE_FAST COPY | 2,629,760 | 0.5% | 51.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,623,259 | 0.5% | 51.6% |
| CALL STORE_FAST | 2,596,873 | 0.5% | 52.1% |
| LOAD_FAST PUSH_NULL | 2,567,370 | 0.5% | 52.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,565,250 | 0.5% | 53.1% |
| LOAD_CONST CALL | 2,564,672 | 0.5% | 53.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,451,280 | 0.5% | 54.0% |
| CALL RETURN_VALUE | 2,440,587 | 0.5% | 54.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,381,272 | 0.4% | 54.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,299,519 | 0.4% | 55.3% |
| CALL POP_TOP | 2,239,233 | 0.4% | 55.7% |
| RETURN_VALUE STORE_FAST | 2,225,332 | 0.4% | 56.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 2,122,828 | 0.4% | 56.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,103,895 | 0.4% | 57.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,081,925 | 0.4% | 57.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,003,377 | 0.4% | 57.7% |
| LOAD_CONST COMPARE_OP_INT | 2,003,126 | 0.4% | 58.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 2,001,903 | 0.4% | 58.5% |
| RETURN_VALUE RETURN_VALUE | 1,910,430 | 0.4% | 58.8% |
| POP_TOP RETURN_CONST | 1,882,069 | 0.4% | 59.2% |
| LOAD_FAST CALL_FUNCTION_EX | 1,849,686 | 0.3% | 59.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,817,343 | 0.3% | 59.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,811,040 | 0.3% | 60.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,793,522 | 0.3% | 60.5% |
| NOP LOAD_GLOBAL_MODULE | 1,737,774 | 0.3% | 60.9% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,734,606 | 0.3% | 61.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,730,644 | 0.3% | 61.5% |
| LOAD_DEREF LOAD_FAST | 1,725,024 | 0.3% | 61.8% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,724,504 | 0.3% | 62.2% |
| POP_TOP LOAD_CONST | 1,715,010 | 0.3% | 62.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,710,247 | 0.3% | 62.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,709,588 | 0.3% | 63.1% |
| LOAD_FAST BUILD_TUPLE | 1,699,027 | 0.3% | 63.4% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,669,602 | 0.3% | 63.8% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,667,730 | 0.3% | 64.1% |
| ENTER_EXECUTOR CALL | 1,634,804 | 0.3% | 64.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,634,784 | 0.3% | 64.7% |
| UNARY_INVERT BINARY_OP | 1,631,017 | 0.3% | 65.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,614,964 | 0.3% | 65.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,581,670 | 0.3% | 65.6% |
| LOAD_CONST LOAD_FAST | 1,580,051 | 0.3% | 65.9% |
| GET_ITER FOR_ITER_LIST | 1,539,234 | 0.3% | 66.2% |
| POP_TOP NOP | 1,534,753 | 0.3% | 66.5% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,528,498 | 0.3% | 66.7% |
| LOAD_FAST TO_BOOL | 1,515,193 | 0.3% | 67.0% |
| LOAD_FAST GET_ITER | 1,463,065 | 0.3% | 67.3% |
| RETURN_VALUE POP_TOP | 1,448,235 | 0.3% | 67.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,438,496 | 0.3% | 67.8% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,436,936 | 0.3% | 68.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,434,918 | 0.3% | 68.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,433,999 | 0.3% | 68.7% |
| POP_JUMP_IF_FALSE POP_TOP | 1,426,358 | 0.3% | 68.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,414,380 | 0.3% | 69.2% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,409,804 | 0.3% | 69.4% |
| BINARY_OP STORE_FAST | 1,398,742 | 0.3% | 69.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,359,262 | 0.3% | 70.0% |
| RESUME_CHECK NOP | 1,339,327 | 0.3% | 70.2% |


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
| RESUME_CHECK | 11,697,777 | 99.0% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,248,468 | 68.6% |
| RETURN_VALUE | 477,597 | 26.2% |
| LOAD_GLOBAL_MODULE | 82,432 | 4.5% |
| CALL | 6,360 | 0.3% |
| ENTER_EXECUTOR | 5,258 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,337,358 | 73.5% |
| STORE_FAST | 483,257 | 26.5% |


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
| LOAD_FAST_LOAD_FAST | 576,080 | 90.7% |
| LOAD_CONST | 58,193 | 9.2% |
| BINARY_SUBSCR | 880 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 575,920 | 90.7% |
| STORE_FAST | 57,913 | 9.1% |
| BINARY_SUBSCR | 880 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,453 | 87.6% |
| LOAD_ATTR_MODULE | 5,100 | 12.3% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 41,613 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,892 | 48.5% |
| CALL | 27,512 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,719 | 16.3% |
| LOAD_ATTR | 81 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60,792 | 77.7% |
| RETURN_CONST | 10,232 | 13.1% |
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
| RETURN_CONST | 1,022,934 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,022,934 | 100.0% |


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
| LOAD_FAST | 1,463,065 | 62.8% |
| STORE_FAST_LOAD_FAST | 576,000 | 24.7% |
| CALL_BUILTIN_CLASS | 262,436 | 11.3% |
| CALL | 14,340 | 0.6% |
| RETURN_VALUE | 5,760 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,539,234 | 66.1% |
| LOAD_FAST_AND_CLEAR | 491,651 | 21.1% |
| FOR_ITER_RANGE | 255,522 | 11.0% |
| FOR_ITER | 12,114 | 0.5% |
| FOR_ITER_TUPLE | 11,740 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,361,336 | 87.7% |
| RETURN_CONST | 872,573 | 7.4% |
| YIELD_VALUE | 577,740 | 4.9% |


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
| STORE_FAST | 3,752,904 | 43.0% |
| POP_TOP | 1,534,753 | 17.6% |
| RESUME_CHECK | 1,339,327 | 15.4% |
| POP_JUMP_IF_FALSE | 1,311,479 | 15.0% |
| POP_JUMP_IF_NOT_NONE | 486,326 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,156,244 | 59.1% |
| LOAD_GLOBAL_MODULE | 1,737,774 | 19.9% |
| LOAD_GLOBAL_BUILTIN | 703,827 | 8.1% |
| LOAD_FAST_LOAD_FAST | 583,320 | 6.7% |
| LOAD_CONST | 530,020 | 6.1% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 30,353 | 64.1% |
| COPY | 11,520 | 24.3% |
| POP_TOP | 5,200 | 11.0% |
| STORE_FAST | 280 | 0.6% |
| STORE_SUBSCR_DICT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 29,953 | 63.2% |
| RERAISE | 11,520 | 24.3% |
| JUMP_FORWARD | 5,120 | 10.8% |
| JUMP_BACKWARD | 700 | 1.5% |
| RETURN_CONST | 60 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,913,520 | 29.2% |
| RETURN_CONST | 6,403,704 | 27.0% |
| CALL | 2,239,233 | 9.4% |
| RETURN_VALUE | 1,448,235 | 6.1% |
| POP_JUMP_IF_FALSE | 1,426,358 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,500,777 | 31.6% |
| LOAD_FAST | 7,313,860 | 30.8% |
| RETURN_CONST | 1,882,069 | 7.9% |
| LOAD_CONST | 1,715,010 | 7.2% |
| NOP | 1,534,753 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 36,073 | 76.1% |
| RERAISE | 5,760 | 12.2% |
| CALL_KW | 5,120 | 10.8% |
| BINARY_SUBSCR_DICT | 300 | 0.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,413 | 76.9% |
| WITH_EXCEPT_START | 5,760 | 12.2% |
| LOAD_GLOBAL_MODULE | 5,080 | 10.7% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,567,370 | 45.5% |
| LOAD_ATTR_MODULE | 1,669,602 | 29.6% |
| LOAD_ATTR | 1,284,370 | 22.7% |
| LOAD_SUPER_ATTR_ATTR | 89,520 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,448,868 | 61.1% |
| CALL | 989,077 | 17.5% |
| LOAD_FAST_LOAD_FAST | 820,898 | 14.5% |
| LOAD_CONST | 315,606 | 5.6% |
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
| LOAD_FAST | 10,549,989 | 48.7% |
| CALL | 2,440,587 | 11.3% |
| RETURN_VALUE | 1,910,430 | 8.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,528,498 | 7.1% |
| CALL_FUNCTION_EX | 1,265,506 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 10,361,336 | 47.9% |
| STORE_FAST | 2,225,332 | 10.3% |
| RETURN_VALUE | 1,910,430 | 8.8% |
| POP_TOP | 1,448,235 | 6.7% |
| LOAD_FAST_LOAD_FAST | 1,137,627 | 5.3% |


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
| LOAD_FAST | 1,515,193 | 96.1% |
| LOAD_ATTR_INSTANCE_VALUE | 53,446 | 3.4% |
| TO_BOOL | 3,662 | 0.2% |
| RETURN_VALUE | 926 | 0.1% |
| LOAD_ATTR | 844 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 835,359 | 53.0% |
| POP_JUMP_IF_FALSE | 734,567 | 46.6% |
| TO_BOOL | 3,662 | 0.2% |
| TO_BOOL_BOOL | 2,123 | 0.1% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,137,627 | 69.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 493,310 | 30.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,631,017 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 272,754 | 100.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 272,834 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 3,659,416 | 53.5% |
| UNARY_INVERT | 1,631,017 | 23.9% |
| POP_JUMP_IF_FALSE | 1,137,627 | 16.6% |
| LOAD_ATTR | 260,795 | 3.8% |
| LOAD_FAST_LOAD_FAST | 84,160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,768,644 | 40.5% |
| STORE_FAST | 1,398,742 | 20.5% |
| TO_BOOL_INT | 1,137,687 | 16.6% |
| UNARY_INVERT | 1,137,627 | 16.6% |
| BUILD_TUPLE | 246,695 | 3.6% |


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
| SWAP | 491,651 | 33.4% |
| JUMP_FORWARD | 477,357 | 32.5% |
| LOAD_FAST | 247,361 | 16.8% |
| POP_TOP | 230,016 | 15.6% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 494,597 | 33.6% |
| SWAP | 491,651 | 33.4% |
| STORE_FAST | 478,817 | 32.6% |
| RETURN_VALUE | 5,120 | 0.3% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 576,000 | 34.7% |
| LOAD_FAST | 529,560 | 31.9% |
| RESUME_CHECK | 487,557 | 29.4% |
| LOAD_ATTR_INSTANCE_VALUE | 34,480 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 17,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,064,677 | 64.2% |
| BUILD_TUPLE | 576,020 | 34.7% |
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
| LOAD_FAST | 1,699,027 | 40.1% |
| LOAD_FAST_LOAD_FAST | 1,160,320 | 27.4% |
| BUILD_MAP | 576,020 | 13.6% |
| RETURN_VALUE | 512,000 | 12.1% |
| BINARY_OP | 246,695 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 1,152,060 | 27.2% |
| CALL | 1,139,187 | 26.9% |
| BUILD_MAP | 576,000 | 13.6% |
| STORE_FAST | 512,000 | 12.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 12.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,564,672 | 23.7% |
| ENTER_EXECUTOR | 1,634,804 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,433,999 | 13.3% |
| LOAD_FAST_LOAD_FAST | 1,302,266 | 12.1% |
| BUILD_TUPLE | 1,139,187 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,596,873 | 24.0% |
| RETURN_VALUE | 2,440,587 | 22.6% |
| POP_TOP | 2,239,233 | 20.7% |
| LOAD_FAST | 1,018,238 | 9.4% |
| TO_BOOL_BOOL | 727,037 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,849,686 | 76.6% |
| DICT_MERGE | 564,260 | 23.4% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,265,506 | 52.4% |
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
| LOAD_CONST | 341,428 | 98.4% |
| ENTER_EXECUTOR | 5,440 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 277,296 | 79.9% |
| LOAD_FAST | 28,800 | 8.3% |
| RETURN_VALUE | 21,120 | 6.1% |
| STORE_FAST | 14,220 | 4.1% |
| PUSH_EXC_INFO | 5,120 | 1.5% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 563,952 | 99.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,481 | 0.3% |
| COMPARE_OP | 1,312 | 0.2% |
| LOAD_GLOBAL_MODULE | 380 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 565,393 | 99.4% |
| COMPARE_OP | 1,312 | 0.2% |
| COMPARE_OP_INT | 1,180 | 0.2% |
| COMPARE_OP_STR | 440 | 0.1% |
| POP_JUMP_IF_TRUE | 280 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,709,588 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 99 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,710,247 | 100.0% |
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
| BINARY_OP | 2,768,644 | 38.7% |
| STORE_FAST | 2,629,760 | 36.8% |
| LOAD_CONST | 1,100,800 | 15.4% |
| LOAD_FAST | 586,160 | 8.2% |
| STORE_ATTR_INSTANCE_VALUE | 21,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,768,324 | 38.7% |
| STORE_FAST | 2,630,400 | 36.8% |
| STORE_FAST_STORE_FAST | 1,093,760 | 15.3% |
| LOAD_ATTR_INSTANCE_VALUE | 571,942 | 8.0% |
| LOAD_FAST | 28,160 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,137,627 | 65.7% |
| CALL_ALLOC_AND_ENTER_INIT | 477,317 | 27.6% |
| CACHE | 109,900 | 6.3% |
| CALL | 5,940 | 0.3% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,730,644 | 100.0% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,376 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,584 | 66.7% |
| RETURN_CONST | 27,512 | 31.9% |
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
| POP_TOP | 7,500,777 | 74.7% |
| POP_JUMP_IF_NOT_NONE | 971,732 | 9.7% |
| LIST_APPEND | 686,715 | 6.8% |
| STORE_FAST_STORE_FAST | 575,320 | 5.7% |
| CALL_LIST_APPEND | 246,015 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,183,440 | 51.6% |
| CALL | 1,634,804 | 16.3% |
| LOAD_FAST | 963,360 | 9.6% |
| CALL_PY_WITH_DEFAULTS | 660,070 | 6.6% |
| JUMP_BACKWARD | 575,960 | 5.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,271,226 | 97.4% |
| SWAP | 14,160 | 1.1% |
| GET_ITER | 12,114 | 0.9% |
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
| LOAD_GLOBAL_MODULE | 1,692 | 3.6% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,532 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,760,000 | 73.4% |
| POP_TOP | 1,158,300 | 14.8% |
| ENTER_EXECUTOR | 575,960 | 7.3% |
| POP_JUMP_IF_FALSE | 224,891 | 2.9% |
| LIST_APPEND | 113,660 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 6,335,920 | 80.8% |
| FOR_ITER | 1,271,226 | 16.2% |
| LOAD_FAST | 225,266 | 2.9% |
| FOR_ITER_LIST | 5,177 | 0.1% |
| FOR_ITER_RANGE | 2,207 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,024,743 | 62.3% |
| POP_TOP | 602,336 | 36.6% |
| STORE_ATTR_INSTANCE_VALUE | 7,020 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 5,720 | 0.3% |
| POP_EXCEPT | 5,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,094,137 | 66.5% |
| BUILD_LIST | 477,357 | 29.0% |
| POP_EXCEPT | 30,353 | 1.8% |
| LOAD_GLOBAL_MODULE | 24,812 | 1.5% |
| LOAD_FAST_LOAD_FAST | 7,320 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 440,160 | 55.0% |
| LOAD_ATTR | 246,715 | 30.8% |
| BINARY_SUBSCR_STR_INT | 112,600 | 14.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 686,715 | 85.8% |
| JUMP_BACKWARD | 113,660 | 14.2% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 231,436 | 50.1% |
| RETURN_VALUE | 230,016 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,656 | 50.0% |
| STORE_FAST | 230,016 | 49.8% |
| RETURN_VALUE | 640 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,716,845 | 76.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,793,522 | 17.7% |
| LOAD_GLOBAL_MODULE | 386,938 | 3.8% |
| CALL | 83,860 | 0.8% |
| ENTER_EXECUTOR | 64,160 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,376,999 | 33.4% |
| PUSH_NULL | 1,284,370 | 12.7% |
| STORE_SUBSCR_DICT | 1,137,547 | 11.3% |
| POP_JUMP_IF_NOT_NONE | 1,110,187 | 11.0% |
| STORE_FAST | 721,815 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,692,676 | 24.9% |
| LOAD_FAST | 3,641,161 | 24.5% |
| POP_TOP | 1,715,010 | 11.5% |
| POP_JUMP_IF_FALSE | 909,444 | 6.1% |
| LOAD_ATTR_METHOD_NO_DICT | 731,410 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,692,676 | 24.9% |
| CALL | 2,564,672 | 17.3% |
| COMPARE_OP_INT | 2,003,126 | 13.5% |
| LOAD_FAST | 1,580,051 | 10.6% |
| COPY | 1,100,800 | 7.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,724,504 | 96.8% |
| POP_JUMP_IF_NOT_NONE | 27,520 | 1.5% |
| STORE_DEREF | 27,520 | 1.5% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,725,024 | 96.8% |
| POP_JUMP_IF_NOT_NONE | 55,040 | 3.1% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,360,064 | 21.3% |
| STORE_FAST | 11,688,204 | 12.3% |
| POP_JUMP_IF_FALSE | 7,485,156 | 7.8% |
| POP_TOP | 7,313,860 | 7.7% |
| NOP | 5,156,244 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,712,196 | 22.8% |
| RETURN_VALUE | 10,549,989 | 11.1% |
| LOAD_ATTR | 7,716,845 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,047,949 | 7.4% |
| CALL_PY_EXACT_ARGS | 5,038,207 | 5.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 491,651 | 66.6% |
| LOAD_FAST_AND_CLEAR | 246,695 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 491,651 | 66.6% |
| LOAD_FAST_AND_CLEAR | 246,695 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 576,560 | 70.0% |
| POP_JUMP_IF_NONE | 230,662 | 28.0% |
| LOAD_ATTR_CLASS | 16,526 | 2.0% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 69.9% |
| LOAD_GLOBAL_MODULE | 230,582 | 28.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 16,486 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,565,250 | 17.7% |
| LOAD_FAST_LOAD_FAST | 2,001,903 | 13.8% |
| POP_JUMP_IF_FALSE | 1,434,918 | 9.9% |
| LOAD_SUPER_ATTR_METHOD | 1,151,907 | 7.9% |
| RETURN_VALUE | 1,137,627 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,527,501 | 24.3% |
| LOAD_FAST_LOAD_FAST | 2,001,903 | 13.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,667,730 | 11.5% |
| CALL | 1,302,266 | 9.0% |
| BUILD_TUPLE | 1,160,320 | 8.0% |


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
| LOAD_GLOBAL_MODULE | 6,782 | 38.2% |
| LOAD_ATTR | 3,324 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 2,742 | 15.4% |
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
| TO_BOOL_INT | 5,043,938 | 27.2% |
| TO_BOOL_BOOL | 4,529,706 | 24.4% |
| COMPARE_OP_INT | 3,679,123 | 19.8% |
| CONTAINS_OP | 1,710,247 | 9.2% |
| COMPARE_OP_STR | 1,436,936 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,485,156 | 40.4% |
| RETURN_CONST | 3,081,422 | 16.6% |
| LOAD_FAST_LOAD_FAST | 1,434,918 | 7.7% |
| POP_TOP | 1,426,358 | 7.7% |
| LOAD_GLOBAL_MODULE | 1,414,380 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,029,674 | 94.4% |
| LOAD_ATTR_INSTANCE_VALUE | 30,560 | 2.8% |
| LOAD_ATTR | 28,260 | 2.6% |
| RETURN_VALUE | 1,400 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 284,144 | 26.1% |
| NOP | 267,936 | 24.6% |
| LOAD_FAST | 257,554 | 23.6% |
| LOAD_FAST_CHECK | 230,662 | 21.2% |
| RETURN_CONST | 24,340 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,381,272 | 48.1% |
| LOAD_ATTR | 1,110,187 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 945,631 | 19.1% |
| RETURN_VALUE | 440,800 | 8.9% |
| LOAD_DEREF | 55,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,003,377 | 40.4% |
| RETURN_CONST | 1,110,510 | 22.4% |
| ENTER_EXECUTOR | 971,732 | 19.6% |
| NOP | 486,326 | 9.8% |
| LOAD_CONST | 230,296 | 4.6% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,817,343 | 67.6% |
| TO_BOOL | 835,359 | 31.1% |
| TO_BOOL_NONE | 19,700 | 0.7% |
| COMPARE_OP_STR | 10,908 | 0.4% |
| COMPARE_OP_INT | 3,483 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 953,885 | 35.5% |
| LOAD_FAST_LOAD_FAST | 838,195 | 31.2% |
| RETURN_CONST | 714,221 | 26.6% |
| LOAD_GLOBAL_MODULE | 70,211 | 2.6% |
| RETURN_VALUE | 57,873 | 2.2% |


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
| POP_JUMP_IF_FALSE | 3,081,422 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 2,122,828 | 23.4% |
| POP_TOP | 1,882,069 | 20.8% |
| POP_JUMP_IF_NOT_NONE | 1,110,510 | 12.3% |
| POP_JUMP_IF_TRUE | 714,221 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,403,704 | 70.7% |
| EXIT_INIT_CHECK | 1,022,934 | 11.3% |
| INTERPRETER_EXIT | 872,573 | 9.6% |
| TO_BOOL_BOOL | 658,278 | 7.3% |
| STORE_FAST | 59,713 | 0.7% |


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
| LOAD_FAST | 57,921 | 57.8% |
| LOAD_FAST_LOAD_FAST | 22,040 | 22.0% |
| LOAD_ATTR_INSTANCE_VALUE | 17,280 | 17.3% |
| STORE_ATTR | 2,440 | 2.4% |
| LOAD_ATTR | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 44,840 | 44.8% |
| LOAD_FAST_LOAD_FAST | 14,760 | 14.7% |
| LOAD_FAST | 13,579 | 13.6% |
| LOAD_CONST | 12,321 | 12.3% |
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
| YIELD_VALUE | 6,335,920 | 22.8% |
| COPY | 2,630,400 | 9.5% |
| CALL | 2,596,873 | 9.4% |
| RETURN_VALUE | 2,225,332 | 8.0% |
| BINARY_OP | 1,398,742 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,688,204 | 42.1% |
| JUMP_BACKWARD | 5,760,000 | 20.8% |
| NOP | 3,752,904 | 13.5% |
| COPY | 2,629,760 | 9.5% |
| JUMP_FORWARD | 1,024,743 | 3.7% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 2,103,895 | 43.8% |
| COPY | 1,093,760 | 22.8% |
| UNPACK_SEQUENCE_TUPLE | 1,088,220 | 22.7% |
| STORE_FAST_STORE_FAST | 512,000 | 10.7% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,581,670 | 33.0% |
| STORE_FAST | 1,088,280 | 22.7% |
| LOAD_FAST_LOAD_FAST | 1,019,025 | 21.2% |
| ENTER_EXECUTOR | 575,320 | 12.0% |
| STORE_FAST_STORE_FAST | 512,000 | 10.7% |


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
| BINARY_OP_ADD_INT | 572,001 | 22.4% |
| BUILD_LIST | 491,651 | 19.3% |
| LOAD_FAST_AND_CLEAR | 491,651 | 19.3% |
| ENTER_EXECUTOR | 476,611 | 18.7% |
| LOAD_FAST | 258,462 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 571,942 | 22.4% |
| LOAD_CONST | 505,157 | 19.8% |
| BUILD_LIST | 491,651 | 19.3% |
| STORE_FAST | 491,651 | 19.3% |
| FOR_ITER_LIST | 476,631 | 18.7% |


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
| LOAD_FAST | 247,261 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 247,301 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,089,862 | 98.3% |
| LOAD_FAST_LOAD_FAST | 18,480 | 1.7% |
| BINARY_OP | 159 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 572,001 | 51.6% |
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
| CALL | 230,582 | 99.9% |
| BINARY_OP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 230,742 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,798 | 80.6% |
| LOAD_CONST | 57,793 | 17.6% |
| CALL_LEN | 5,680 | 1.7% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 322,751 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 230,256 | 95.1% |
| LOAD_CONST | 11,640 | 4.8% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 230,296 | 95.2% |
| LOAD_CONST | 11,440 | 4.7% |
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
| LOAD_GLOBAL_MODULE | 504,757 | 49.3% |
| LOAD_FAST | 484,337 | 47.3% |
| CALL | 33,420 | 3.3% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 545,617 | 53.3% |
| COPY_FREE_VARS | 477,317 | 46.7% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,240 | 82.2% |
| LOAD_CONST | 7,000 | 9.0% |
| BINARY_OP_ADD_INT | 5,680 | 7.3% |
| PUSH_NULL | 993 | 1.3% |
| CALL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 71,793 | 91.8% |
| POP_TOP | 6,280 | 8.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 697,367 | 35.5% |
| CALL_FUNCTION_EX | 511,960 | 26.0% |
| LOAD_FAST | 265,041 | 13.5% |
| CALL_BUILTIN_CLASS | 229,936 | 11.7% |
| CALL_LEN | 229,936 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 759,281 | 38.6% |
| STORE_FAST | 697,667 | 35.5% |
| GET_ITER | 262,436 | 13.3% |
| CALL_BUILTIN_CLASS | 229,936 | 11.7% |
| LOAD_FAST | 17,280 | 0.9% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 863,402 | 55.2% |
| LOAD_CONST | 388,216 | 24.8% |
| LOAD_FAST_LOAD_FAST | 173,158 | 11.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 81,239 | 5.2% |
| LOAD_GLOBAL_MODULE | 27,880 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 583,833 | 37.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 442,985 | 28.3% |
| TO_BOOL_BOOL | 378,156 | 24.2% |
| UNPACK_SEQUENCE_TUPLE | 81,239 | 5.2% |
| POP_TOP | 14,942 | 1.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,020 | 45.8% |
| BUILD_TUPLE | 511,960 | 45.2% |
| CALL | 64,973 | 5.7% |
| LOAD_FAST_CHECK | 16,486 | 1.5% |
| LOAD_ATTR | 14,000 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,047,820 | 92.6% |
| RETURN_VALUE | 82,139 | 7.3% |
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
| LOAD_GLOBAL_BUILTIN | 1,155,087 | 100.0% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,155,367 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 592,087 | 95.4% |
| LOAD_ATTR_INSTANCE_VALUE | 27,900 | 4.5% |
| CALL | 382 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 344,238 | 55.5% |
| CALL_BUILTIN_CLASS | 229,936 | 37.1% |
| CALL_PY_EXACT_ARGS | 33,160 | 5.3% |
| LOAD_FAST | 5,720 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 5,680 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 246,615 | 95.4% |
| LOAD_FAST | 11,440 | 4.4% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 246,015 | 95.1% |
| LOAD_GLOBAL_MODULE | 11,440 | 4.4% |
| JUMP_BACKWARD | 640 | 0.2% |
| NOP | 280 | 0.1% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,614,964 | 99.8% |
| LOAD_CONST | 1,240 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 538 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,137,907 | 70.3% |
| STORE_FAST | 478,154 | 29.5% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,359,262 | 93.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 97,725 | 6.7% |
| LOAD_ATTR | 2,480 | 0.2% |
| CALL | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 612,743 | 42.0% |
| STORE_FAST | 575,960 | 39.5% |
| LOAD_FAST | 85,060 | 5.8% |
| CALL_BUILTIN_FAST | 81,239 | 5.6% |
| RETURN_VALUE | 51,612 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 881,238 | 91.7% |
| LOAD_CONST | 33,720 | 3.5% |
| CALL | 29,139 | 3.0% |
| RETURN_VALUE | 14,000 | 1.5% |
| RETURN_GENERATOR | 1,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 910,517 | 94.8% |
| LOAD_CONST | 33,440 | 3.5% |
| RETURN_VALUE | 14,900 | 1.6% |
| BINARY_OP_ADD_UNICODE | 1,240 | 0.1% |
| STORE_FAST | 280 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,390,138 | 44.7% |
| LOAD_FAST | 5,038,207 | 41.8% |
| LOAD_FAST_LOAD_FAST | 820,136 | 6.8% |
| LOAD_SUPER_ATTR_METHOD | 477,277 | 4.0% |
| LOAD_GLOBAL_MODULE | 93,900 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,018,183 | 99.6% |
| MAKE_CELL | 27,800 | 0.2% |
| RETURN_GENERATOR | 18,420 | 0.2% |
| COPY_FREE_VARS | 320 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,207,739 | 42.0% |
| ENTER_EXECUTOR | 660,070 | 23.0% |
| LOAD_ATTR_MODULE | 477,477 | 16.6% |
| LOAD_FAST | 329,655 | 11.5% |
| LOAD_CONST | 107,411 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,734,606 | 60.4% |
| COPY_FREE_VARS | 1,137,627 | 39.6% |


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
| LOAD_CONST | 2,003,126 | 54.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,059,277 | 28.8% |
| LOAD_FAST | 576,980 | 15.7% |
| LOAD_FAST_LOAD_FAST | 18,480 | 0.5% |
| CALL_BUILTIN_FAST | 14,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,679,123 | 99.9% |
| POP_JUMP_IF_TRUE | 3,483 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 100 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,409,804 | 95.5% |
| LOAD_CONST | 59,860 | 4.1% |
| LOAD_FAST | 5,820 | 0.4% |
| COMPARE_OP | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,436,936 | 97.4% |
| COPY | 14,040 | 1.0% |
| LOAD_FAST | 14,040 | 1.0% |
| POP_JUMP_IF_TRUE | 10,908 | 0.7% |


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
| GET_ITER | 1,539,234 | 76.1% |
| SWAP | 476,631 | 23.6% |
| JUMP_BACKWARD | 5,177 | 0.3% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 716,574 | 35.4% |
| STORE_FAST_LOAD_FAST | 576,620 | 28.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 493,370 | 24.4% |
| LOAD_FAST | 231,742 | 11.5% |
| RETURN_CONST | 1,328 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 255,522 | 99.1% |
| JUMP_BACKWARD | 2,207 | 0.9% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 257,089 | 99.7% |
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
| LOAD_GLOBAL_MODULE | 81,199 | 88.8% |
| LOAD_ATTR_MODULE | 10,200 | 11.2% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,953 | 81.9% |
| LOAD_FAST_CHECK | 16,526 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,712,196 | 90.5% |
| LOAD_FAST_LOAD_FAST | 1,667,730 | 6.9% |
| COPY | 571,942 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 23,783 | 0.1% |
| RETURN_VALUE | 14,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,487,009 | 22.9% |
| LOAD_FAST | 3,644,156 | 15.2% |
| TO_BOOL_BOOL | 1,811,040 | 7.5% |
| LOAD_ATTR | 1,793,522 | 7.5% |
| CONTAINS_OP | 1,709,588 | 7.1% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 408,756 | 100.0% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,598 | 39.8% |
| CALL | 148,613 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 97,725 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,487,009 | 87.2% |
| LOAD_FAST | 608,198 | 9.7% |
| LOAD_ATTR | 85,238 | 1.4% |
| LOAD_ATTR_SLOT | 83,760 | 1.3% |
| LOAD_CONST | 15,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,451,280 | 38.9% |
| CALL | 1,433,999 | 22.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,359,262 | 21.6% |
| LOAD_CONST | 731,410 | 11.6% |
| LOAD_FAST_LOAD_FAST | 288,994 | 4.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,047,949 | 69.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,319,213 | 13.0% |
| LOAD_FAST_LOAD_FAST | 1,137,547 | 11.2% |
| BINARY_SUBSCR | 575,920 | 5.7% |
| LOAD_GLOBAL_MODULE | 28,860 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,390,138 | 53.2% |
| LOAD_FAST | 2,623,259 | 25.9% |
| CALL_PY_WITH_DEFAULTS | 1,207,739 | 11.9% |
| LOAD_FAST_LOAD_FAST | 678,560 | 6.7% |
| LOAD_CONST | 125,891 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,299,519 | 99.9% |
| LOAD_ATTR | 2,822 | 0.1% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,669,602 | 72.5% |
| CALL_PY_WITH_DEFAULTS | 477,477 | 20.7% |
| STORE_DEREF | 55,040 | 2.4% |
| LOAD_CONST | 35,840 | 1.6% |
| LOAD_FAST | 28,800 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,147 | 70.5% |
| LOAD_FAST_LOAD_FAST | 493,230 | 29.5% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,137,587 | 68.1% |
| UNARY_INVERT | 493,310 | 29.5% |
| RETURN_VALUE | 14,040 | 0.8% |
| LOAD_CONST | 14,040 | 0.8% |
| LOAD_FAST_LOAD_FAST | 5,720 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 522,401 | 52.2% |
| ENTER_EXECUTOR | 449,994 | 44.9% |
| RETURN_VALUE | 27,440 | 2.7% |
| LOAD_GLOBAL_MODULE | 1,240 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 989,235 | 98.8% |
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
| RESUME_CHECK | 3,550,411 | 46.1% |
| LOAD_FAST | 1,181,727 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 971,832 | 12.6% |
| STORE_FAST | 931,971 | 12.1% |
| NOP | 703,827 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,698,280 | 48.0% |
| LOAD_DEREF | 1,724,504 | 22.4% |
| CALL_ISINSTANCE | 1,155,087 | 15.0% |
| LOAD_GLOBAL_BUILTIN | 971,832 | 12.6% |
| LOAD_GLOBAL_MODULE | 49,720 | 0.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,035,610 | 26.3% |
| RESUME_CHECK | 3,027,234 | 19.8% |
| NOP | 1,737,774 | 11.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,438,496 | 9.4% |
| POP_JUMP_IF_FALSE | 1,414,380 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,659,416 | 23.9% |
| LOAD_FAST_LOAD_FAST | 2,565,250 | 16.7% |
| LOAD_ATTR_MODULE | 2,299,519 | 15.0% |
| LOAD_FAST | 2,081,925 | 13.6% |
| COMPARE_OP_STR | 1,409,804 | 9.2% |


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
| LOAD_FAST | 1,634,784 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,151,907 | 70.5% |
| CALL_PY_EXACT_ARGS | 477,277 | 29.2% |
| LOAD_FAST | 5,760 | 0.4% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,018,183 | 33.0% |
| CACHE | 11,697,777 | 32.1% |
| FOR_ITER_GEN | 6,335,920 | 17.4% |
| CALL_PY_WITH_DEFAULTS | 1,734,606 | 4.8% |
| COPY_FREE_VARS | 1,730,644 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,360,064 | 55.8% |
| POP_TOP | 6,913,520 | 19.0% |
| LOAD_GLOBAL_BUILTIN | 3,550,411 | 9.7% |
| LOAD_GLOBAL_MODULE | 3,027,234 | 8.3% |
| NOP | 1,339,327 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,849,947 | 67.9% |
| LOAD_FAST_LOAD_FAST | 739,057 | 17.6% |
| SWAP | 571,942 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 17,040 | 0.4% |
| STORE_FAST_LOAD_FAST | 14,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,122,828 | 50.5% |
| LOAD_FAST | 909,181 | 21.6% |
| LOAD_GLOBAL_MODULE | 688,457 | 16.4% |
| LOAD_CONST | 213,579 | 5.1% |
| LOAD_FAST_LOAD_FAST | 129,480 | 3.1% |


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
| LOAD_ATTR | 1,137,547 | 92.5% |
| LOAD_FAST | 46,078 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 34,680 | 2.8% |
| CALL | 10,200 | 0.8% |
| LOAD_CONST | 1,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,142,084 | 92.9% |
| RETURN_CONST | 32,520 | 2.6% |
| LOAD_GLOBAL_MODULE | 27,720 | 2.3% |
| LOAD_CONST | 27,480 | 2.2% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,811,040 | 27.4% |
| CALL_ISINSTANCE | 1,155,367 | 17.5% |
| RETURN_VALUE | 880,957 | 13.3% |
| CALL | 727,037 | 11.0% |
| LOAD_FAST | 717,633 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,529,706 | 68.4% |
| POP_JUMP_IF_TRUE | 1,817,343 | 27.5% |
| UNARY_NOT | 272,754 | 4.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,768,324 | 54.9% |
| BINARY_OP | 1,137,687 | 22.6% |
| LOAD_FAST | 1,137,547 | 22.6% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,043,938 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 488,777 | 91.9% |
| LOAD_ATTR_INSTANCE_VALUE | 42,760 | 8.0% |
| TO_BOOL | 200 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 531,597 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 191,447 | 79.6% |
| LOAD_FAST | 27,900 | 11.6% |
| COPY | 13,880 | 5.8% |
| WITH_EXCEPT_START | 5,680 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 220,807 | 91.8% |
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
| CALL_BUILTIN_FAST | 81,239 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,088,220 | 93.1% |
| STORE_FAST | 81,279 | 6.9% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 581,600 | 27.6% |
| LOAD_FAST_CHECK | 575,920 | 27.3% |
| FOR_ITER_LIST | 493,370 | 23.4% |
| CALL_BUILTIN_FAST | 442,985 | 21.0% |
| CALL | 9,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,103,895 | 99.7% |
| LOAD_FAST | 7,000 | 0.3% |
| STORE_DEREF | 20 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 58.7% |
| COPY | 383 | 37.4% |
| TO_BOOL | 40 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 620 | 60.6% |
| POP_JUMP_IF_FALSE | 403 | 39.4% |


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
|     deferred | 6,827,709 | 76.8% |
|          hit | 2,058,515 | 23.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 599 | 8.6% |
| Failure | 6,399 | 91.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,180 | 49.7% |
| or | 1,698 | 26.5% |
| remainder | 781 | 12.2% |
| add different types | 640 | 10.0% |
| add other | 100 | 1.6% |


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
|     deferred | 634,113 | 55.4% |
|          hit | 508,656 | 44.5% |

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
|     deferred | 10,767,945 | 28.0% |
|          hit | 27,598,806 | 71.8% |
|         miss | 7,860 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,161 | 23.4% |
| Failure | 29,934 | 76.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,913 | 26.4% |
| cfunc noargs | 6,045 | 20.2% |
| class no vectorcall | 4,000 | 13.4% |
| meth descr varargs keywords | 3,219 | 10.8% |
| class mutable | 1,278 | 4.3% |
| other | 1,180 | 3.9% |
| bound method | 1,121 | 3.7% |
| cfunc varargs | 1,120 | 3.7% |
| meth descr method fastcall keywords | 920 | 3.1% |
| cfunc varargs keywords | 918 | 3.1% |
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
|     deferred | 565,653 | 9.9% |
|          hit | 5,152,163 | 90.0% |
|         miss | 6,907 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,620 | 53.4% |
| Failure | 1,412 | 46.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 807 | 57.2% |
| big int | 360 | 25.5% |
| different types | 245 | 17.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,302,940 | 13.1% |
|          hit | 8,641,271 | 86.9% |

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
|     deferred | 10,066,712 | 17.9% |
|          hit | 45,688,058 | 81.4% |
|         miss | 311,432 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,197 | 52.0% |
| Failure | 20,480 | 48.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,617 | 22.5% |
| shadowed | 4,268 | 20.8% |
| not managed dict | 3,718 | 18.2% |
| non overriding descriptor | 2,440 | 11.9% |
| has managed dict | 1,120 | 5.5% |
| class attr descriptor | 1,040 | 5.1% |
| metaclass attribute | 960 | 4.7% |
| class method obj | 920 | 4.5% |
| non object slot | 560 | 2.7% |
| class attr simple | 477 | 2.3% |
| mutable class | 280 | 1.4% |
| overridden | 80 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,307 | 0.0% |
|        deopt | 100 | 0.0% |
|          hit | 23,023,545 | 99.9% |
|         miss | 6,395 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,565 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,724,504 | 100.0% |

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
|     deferred | 89,840 | 2.0% |
|          hit | 4,101,645 | 93.3% |
|         miss | 196,100 | 4.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,859 | 76.3% |
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
|     deferred | 30,339 | 2.4% |
|          hit | 1,230,004 | 97.5% |

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
|     deferred | 1,570,006 | 11.2% |
|          hit | 12,438,548 | 88.7% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,963 | 44.7% |
| Failure | 3,662 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,082 | 29.5% |
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
|          hit | 3,280,414 | 100.0% |

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
| Basic | 302,123,154 | 56.6% |
| Not specialized | 59,310,625 | 11.1% |
| Specialized hits | 171,810,736 | 32.2% |
| Specialized misses | 528,980 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 10,767,945 | 33.8% |
| LOAD_ATTR | 10,066,712 | 31.6% |
| BINARY_OP | 6,827,709 | 21.4% |
| TO_BOOL | 1,570,006 | 4.9% |
| FOR_ITER | 1,302,940 | 4.1% |
| BINARY_SUBSCR | 634,113 | 2.0% |
| COMPARE_OP | 565,653 | 1.8% |
| STORE_ATTR | 89,840 | 0.3% |
| STORE_SUBSCR | 30,339 | 0.1% |
| LOAD_GLOBAL | 8,307 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 215,974 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 196,100 | 37.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 81,978 | 15.5% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.3% |
| COMPARE_OP_INT | 6,887 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,400 | 1.2% |
| LOAD_GLOBAL_MODULE | 6,055 | 1.1% |
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
| Calls to PyEval_EvalDefault | 11,817,437 | 32.4% |
| Calls to Python functions inlined | 24,671,249 | 67.6% |
| Calls via PyEval_EvalFrame (total) | 11,817,437 | 32.4% |
| Calls via PyEval_EvalFrame (vector) | 11,232,317 | 30.8% |
| Calls via PyEval_EvalFrame (generator) | 585,120 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 11,231,617 | 30.8% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 625,920 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 535,340 | 1.5% |
| Calls via PyEval_EvalFrame (api) | 615,444 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 47,513 | 0.1% |
| Frames pushed | 18,177,412 | 49.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 18,922,276 | 41.7% |
| Frees to freelist | 18,934,994 |  |
| Allocations | 26,490,012 | 58.3% |
| Allocations to 512 bytes | 26,204,391 | 57.7% |
| Allocations to 4 kbytes | 117,611 | 0.3% |
| Allocations over 4 kbytes | 168,010 | 0.4% |
| Frees | 27,928,197 |  |
| New values | 88,020 |  |
| Interpreter increfs | 229,965,453 | 77.7% |
| Interpreter decrefs | 250,949,455 | 74.5% |
| Increfs | 65,987,924 | 22.3% |
| Decrefs | 85,844,165 | 25.5% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 11,863,091 |  |
| Method cache misses | 54,193 |  |
| Method cache collisions | 73,704 |  |
| Method cache dunder hits | 11,282,544 |  |
| Method cache dunder misses | 23,469 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 40 | 600 | 283,596 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 6,902 |  |
| Traces created | 715 | 10.4% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 6,187 | 89.6% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 10,038,121 |  |
| Uops executed | 98,185,599 | 9.78 |

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
| <= 128 | 55 | 7.7% |


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
| <= 16 | 200 | 28.0% |
| <= 32 | 360 | 50.3% |
| <= 64 | 37 | 5.2% |
| <= 128 | 38 | 5.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 1,023,360 | 10.2% |
| <= 8 | 2,042,710 | 20.3% |
| <= 16 | 5,994,424 | 59.7% |
| <= 32 | 976,364 | 9.7% |
| <= 64 | 770 | 0.0% |
| <= 128 | 430 | 0.0% |
| <= 256 | 2 | 0.0% |
| <= 512 | 3 | 0.0% |
| <= 1,024 | 4 | 0.0% |
| <= 2,048 | 11 | 0.0% |
| <= 4,096 | 11 | 0.0% |
| <= 8,192 | 32 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 23,486,897 | 23.9% | 23.9% |  |
| LOAD_FAST | 10,113,473 | 10.3% | 34.2% |  |
| _EXIT_TRACE | 10,038,121 | 10.2% | 44.4% |  |
| _POP_JUMP_IF_TRUE | 8,373,132 | 8.5% | 53.0% |  |
| _ITER_CHECK_LIST | 7,861,272 | 8.0% | 61.0% |  |
| _IS_ITER_EXHAUSTED_LIST | 7,861,272 | 8.0% | 69.0% |  |
| STORE_FAST | 6,561,757 | 6.7% | 75.7% |  |
| _ITER_NEXT_LIST | 6,080,245 | 6.2% | 81.9% |  |
| _GUARD_GLOBALS_VERSION | 2,050,088 | 2.1% | 83.9% |  |
| POP_TOP | 2,050,034 | 2.1% | 86.0% |  |
| PUSH_NULL | 1,679,791 | 1.7% | 87.7% |  |
| _LOAD_GLOBAL_MODULE | 1,245,032 | 1.3% | 89.0% |  |
| _CHECK_ATTR_MODULE | 1,236,941 | 1.3% | 90.3% |  |
| _LOAD_ATTR_MODULE | 1,236,941 | 1.3% | 91.5% |  |
| _GUARD_BUILTINS_VERSION | 805,056 | 0.8% | 92.4% |  |
| _LOAD_GLOBAL_BUILTINS | 805,056 | 0.8% | 93.2% |  |
| _GUARD_TYPE_VERSION | 778,550 | 0.8% | 94.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 730,270 | 0.7% | 94.7% |  |
| _GUARD_KEYS_VERSION | 730,270 | 0.7% | 95.5% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 730,270 | 0.7% | 96.2% |  |
| _ITER_CHECK_RANGE | 485,312 | 0.5% | 96.7% |  |
| _IS_ITER_EXHAUSTED_RANGE | 485,312 | 0.5% | 97.2% |  |
| LOAD_CONST | 339,106 | 0.3% | 97.5% |  |
| _ITER_NEXT_RANGE | 245,096 | 0.2% | 97.8% |  |
| TO_BOOL_BOOL | 230,087 | 0.2% | 98.0% |  |
| BINARY_SUBSCR_LIST_INT | 229,696 | 0.2% | 98.3% |  |
| CALL_BUILTIN_FAST | 229,696 | 0.2% | 98.5% |  |
| _POP_JUMP_IF_FALSE | 225,290 | 0.2% | 98.7% |  |
| _CHECK_PEP_523 | 134,400 | 0.1% | 98.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 134,400 | 0.1% | 99.0% |  |
| _CHECK_STACK_SPACE | 134,400 | 0.1% | 99.1% |  |
| _INIT_CALL_PY_EXACT_ARGS | 134,400 | 0.1% | 99.3% |  |
| _PUSH_FRAME | 134,400 | 0.1% | 99.4% |  |
| _SAVE_RETURN_OFFSET | 134,400 | 0.1% | 99.5% |  |
| RESUME_CHECK | 134,360 | 0.1% | 99.7% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 64,160 | 0.1% | 99.7% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 64,160 | 0.1% | 99.8% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 30,320 | 0.0% | 99.8% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 30,320 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 25,774 | 0.0% | 99.9% |  |
| _ITER_CHECK_TUPLE | 15,720 | 0.0% | 99.9% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 15,720 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 14,020 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 6,080 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 5,520 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,080 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CONTAINS_OP | 3,940 | 0.0% | 100.0% |  |
| COPY | 3,940 | 0.0% | 100.0% |  |
| SWAP | 3,940 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 3,940 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 3,940 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 3,940 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 3,940 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 3,940 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 2,300 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 460 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _IS_NONE | 420 | 0.0% | 100.0% |  |
| IS_OP | 391 | 0.0% | 100.0% |  |
| _POP_FRAME | 391 | 0.0% | 100.0% |  |
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
| FOR_ITER_GEN | 3,820 |
| FOR_ITER | 1,940 |
| LOAD_ATTR | 507 |
| CALL | 198 |
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
