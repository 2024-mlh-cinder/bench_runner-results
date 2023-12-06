
# Pystats results

- benchmark: concurrent_imap
- fork: python
- ref: main
- commit hash: 53eb9a6
- commit date: 2023-09-30T22:37:23+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 51,880,511 | 16.8% | 16.8% |  |
| RESUME_CHECK | 20,922,251 | 6.8% | 23.6% | 0.0% |
| STORE_FAST | 16,564,918 | 5.4% | 29.0% |  |
| POP_TOP | 13,855,754 | 4.5% | 33.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 13,683,090 | 4.4% | 37.9% | 1.2% |
| RETURN_VALUE | 11,866,331 | 3.8% | 41.8% |  |
| JUMP_BACKWARD | 11,845,917 | 3.8% | 45.6% |  |
| POP_JUMP_IF_FALSE | 9,327,447 | 3.0% | 48.6% |  |
| LOAD_CONST | 9,002,282 | 2.9% | 51.6% |  |
| LOAD_GLOBAL_MODULE | 7,832,579 | 2.5% | 54.1% | 0.0% |
| INTERPRETER_EXIT | 7,775,258 | 2.5% | 56.6% |  |
| LOAD_FAST_LOAD_FAST | 7,625,060 | 2.5% | 59.1% |  |
| CALL | 6,526,514 | 2.1% | 61.2% |  |
| FOR_ITER_LIST | 5,946,276 | 1.9% | 63.1% |  |
| CALL_PY_EXACT_ARGS | 5,586,127 | 1.8% | 64.9% |  |
| NOP | 5,352,108 | 1.7% | 66.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,227,859 | 1.7% | 68.4% | 1.2% |
| YIELD_VALUE | 4,896,480 | 1.6% | 70.0% |  |
| LOAD_ATTR | 4,677,788 | 1.5% | 71.5% |  |
| PUSH_NULL | 4,652,087 | 1.5% | 73.0% |  |
| RETURN_CONST | 4,599,884 | 1.5% | 74.5% |  |
| STORE_FAST_LOAD_FAST | 4,570,080 | 1.5% | 76.0% |  |
| FOR_ITER_GEN | 4,496,160 | 1.5% | 77.4% |  |
| COPY | 4,325,012 | 1.4% | 78.8% |  |
| LOAD_GLOBAL_BUILTIN | 4,122,853 | 1.3% | 80.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,670,271 | 1.2% | 81.4% |  |
| TO_BOOL_BOOL | 3,609,004 | 1.2% | 82.5% |  |
| STORE_FAST_STORE_FAST | 3,179,478 | 1.0% | 83.6% |  |
| BINARY_OP | 2,777,041 | 0.9% | 84.5% |  |
| POP_JUMP_IF_NOT_NONE | 2,650,825 | 0.9% | 85.3% |  |
| BUILD_TUPLE | 2,626,707 | 0.9% | 86.2% |  |
| STORE_ATTR_INSTANCE_VALUE | 2,272,109 | 0.7% | 86.9% | 6.5% |
| TO_BOOL_INT | 2,027,612 | 0.7% | 87.6% |  |
| COMPARE_OP_INT | 1,905,137 | 0.6% | 88.2% | 0.2% |
| LOAD_ATTR_MODULE | 1,748,159 | 0.6% | 88.7% |  |
| CALL_FUNCTION_EX | 1,730,699 | 0.6% | 89.3% |  |
| POP_JUMP_IF_TRUE | 1,640,984 | 0.5% | 89.8% |  |
| CALL_PY_WITH_DEFAULTS | 1,384,156 | 0.4% | 90.3% |  |
| SWAP | 1,246,669 | 0.4% | 90.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,211,958 | 0.4% | 91.1% |  |
| GET_ITER | 1,155,342 | 0.4% | 91.5% |  |
| BEFORE_WITH | 1,150,524 | 0.4% | 91.8% |  |
| BUILD_MAP | 1,055,308 | 0.3% | 92.2% |  |
| TO_BOOL | 1,037,499 | 0.3% | 92.5% |  |
| COMPARE_OP_STR | 972,775 | 0.3% | 92.8% |  |
| FOR_ITER | 914,840 | 0.3% | 93.1% |  |
| JUMP_FORWARD | 873,056 | 0.3% | 93.4% |  |
| CONTAINS_OP | 862,459 | 0.3% | 93.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 833,253 | 0.3% | 94.0% |  |
| UNPACK_SEQUENCE_TUPLE | 828,229 | 0.3% | 94.2% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 823,669 | 0.3% | 94.5% |  |
| BINARY_OP_ADD_INT | 808,790 | 0.3% | 94.8% |  |
| CALL_BUILTIN_FAST | 807,025 | 0.3% | 95.0% |  |
| LOAD_DEREF | 747,047 | 0.2% | 95.3% |  |
| COPY_FREE_VARS | 711,167 | 0.2% | 95.5% |  |
| CALL_BUILTIN_CLASS | 709,127 | 0.2% | 95.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 691,115 | 0.2% | 95.9% |  |
| LOAD_SUPER_ATTR_METHOD | 665,687 | 0.2% | 96.2% |  |
| UNARY_INVERT | 664,235 | 0.2% | 96.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 654,692 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 625,057 | 0.2% | 96.8% |  |
| BUILD_LIST | 619,283 | 0.2% | 97.0% |  |
| POP_JUMP_IF_NONE | 537,406 | 0.2% | 97.2% |  |
| STORE_SUBSCR_DICT | 517,864 | 0.2% | 97.3% |  |
| LOAD_FAST_CHECK | 513,079 | 0.2% | 97.5% |  |
| CALL_ISINSTANCE | 466,699 | 0.2% | 97.7% |  |
| EXIT_INIT_CHECK | 444,536 | 0.1% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 444,536 | 0.1% | 97.9% |  |
| BINARY_SUBSCR | 443,926 | 0.1% | 98.1% |  |
| LOAD_ATTR_PROPERTY | 427,390 | 0.1% | 98.2% | 2.1% |
| DICT_MERGE | 420,720 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 412,560 | 0.1% | 98.5% |  |
| LIST_APPEND | 348,802 | 0.1% | 98.6% |  |
| FOR_ITER_RANGE | 316,067 | 0.1% | 98.7% |  |
| LOAD_FAST_AND_CLEAR | 311,795 | 0.1% | 98.8% |  |
| CALL_LEN | 281,232 | 0.1% | 98.9% |  |
| COMPARE_OP | 236,191 | 0.1% | 99.0% |  |
| TO_BOOL_LIST | 235,708 | 0.1% | 99.1% |  |
| BINARY_SUBSCR_LIST_INT | 193,958 | 0.1% | 99.1% |  |
| LIST_EXTEND | 186,278 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 182,116 | 0.1% | 99.2% |  |
| CALL_KW | 170,968 | 0.1% | 99.3% |  |
| TO_BOOL_NONE | 168,872 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 162,164 | 0.1% | 99.4% |  |
| UNARY_NOT | 124,002 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 113,048 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 105,129 | 0.0% | 99.5% |  |
| STORE_DEREF | 99,600 | 0.0% | 99.5% |  |
| MAKE_CELL | 99,600 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_FLOAT | 93,260 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 82,080 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 81,120 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 72,960 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 72,960 | 0.0% | 99.7% |  |
| STORE_ATTR | 62,321 | 0.0% | 99.7% |  |
| DELETE_ATTR | 61,191 | 0.0% | 99.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 56,984 | 0.0% | 99.8% | 7.3% |
| DELETE_SUBSCR | 56,154 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 46,320 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 46,320 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 43,909 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 41,280 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 41,280 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 38,160 | 0.0% | 99.9% |  |
| IS_OP | 32,798 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 31,680 | 0.0% | 99.9% |  |
| BUILD_STRING | 29,040 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 27,786 | 0.0% | 99.9% |  |
| POP_EXCEPT | 27,786 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 27,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 25,920 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 23,706 | 0.0% | 99.9% |  |
| IMPORT_NAME | 21,840 | 0.0% | 99.9% |  |
| IMPORT_FROM | 21,840 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 21,100 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 19,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 18,240 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 17,760 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 12,720 | 0.0% | 100.0% |  |
| BINARY_SLICE | 12,720 | 0.0% | 100.0% |  |
| RERAISE | 12,240 | 0.0% | 100.0% |  |
| END_FOR | 8,160 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,160 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,080 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,080 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 960 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 480 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 398 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 212 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 12,561,928 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 11,882,150 | 3.9% | 7.9% |
| CACHE RESUME_CHECK | 7,720,301 | 2.5% | 10.4% |
| RETURN_VALUE INTERPRETER_EXIT | 6,918,199 | 2.2% | 12.7% |
| STORE_FAST LOAD_FAST | 6,389,415 | 2.1% | 14.7% |
| LOAD_FAST RETURN_VALUE | 6,236,030 | 2.0% | 16.8% |
| POP_TOP JUMP_BACKWARD | 5,788,446 | 1.9% | 18.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 5,553,487 | 1.8% | 20.4% |
| JUMP_BACKWARD FOR_ITER_LIST | 4,939,393 | 1.6% | 22.1% |
| RESUME_CHECK POP_TOP | 4,896,480 | 1.6% | 23.6% |
| YIELD_VALUE STORE_FAST | 4,488,000 | 1.5% | 25.1% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,488,000 | 1.5% | 26.6% |
| FOR_ITER_GEN RESUME_CHECK | 4,488,000 | 1.5% | 28.0% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,080,000 | 1.3% | 29.3% |
| STORE_FAST JUMP_BACKWARD | 4,080,000 | 1.3% | 30.7% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,080,000 | 1.3% | 32.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 3,931,208 | 1.3% | 33.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,543,727 | 1.1% | 34.4% |
| POP_TOP LOAD_FAST | 3,542,254 | 1.1% | 35.5% |
| NOP LOAD_FAST | 3,510,612 | 1.1% | 36.7% |
| LOAD_FAST LOAD_ATTR | 3,308,398 | 1.1% | 37.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,233,342 | 1.0% | 38.8% |
| RETURN_CONST POP_TOP | 3,181,127 | 1.0% | 39.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,581,882 | 0.8% | 40.7% |
| LOAD_FAST PUSH_NULL | 2,488,590 | 0.8% | 41.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,387,588 | 0.8% | 42.3% |
| LOAD_CONST LOAD_CONST | 2,371,917 | 0.8% | 43.0% |
| PUSH_NULL LOAD_FAST | 2,198,599 | 0.7% | 43.7% |
| STORE_FAST NOP | 2,099,294 | 0.7% | 44.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,082,250 | 0.7% | 45.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,080,568 | 0.7% | 45.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,027,612 | 0.7% | 46.4% |
| COPY STORE_FAST | 1,948,320 | 0.6% | 47.1% |
| STORE_FAST COPY | 1,948,080 | 0.6% | 47.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,921,914 | 0.6% | 48.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,903,956 | 0.6% | 48.9% |
| LOAD_FAST LOAD_CONST | 1,893,365 | 0.6% | 49.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,870,883 | 0.6% | 50.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,748,061 | 0.6% | 50.7% |
| CALL STORE_FAST | 1,740,249 | 0.6% | 51.3% |
| LOAD_CONST CALL | 1,694,013 | 0.5% | 51.8% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,663,465 | 0.5% | 52.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,624,866 | 0.5% | 52.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,613,124 | 0.5% | 53.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,579,512 | 0.5% | 53.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,468,265 | 0.5% | 54.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,457,391 | 0.5% | 54.9% |
| LOAD_ATTR LOAD_FAST | 1,407,256 | 0.5% | 55.3% |
| CALL POP_TOP | 1,385,212 | 0.4% | 55.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,378,771 | 0.4% | 56.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,371,541 | 0.4% | 56.7% |
| CALL RETURN_VALUE | 1,355,659 | 0.4% | 57.1% |
| LOAD_FAST CALL_FUNCTION_EX | 1,309,979 | 0.4% | 57.6% |
| PUSH_NULL CALL | 1,255,502 | 0.4% | 58.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,216,370 | 0.4% | 58.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,213,531 | 0.4% | 58.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,207,398 | 0.4% | 59.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,190,190 | 0.4% | 59.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,126,787 | 0.4% | 59.9% |
| COPY TO_BOOL_INT | 1,118,694 | 0.4% | 60.3% |
| BINARY_OP COPY | 1,118,694 | 0.4% | 60.6% |
| POP_TOP RETURN_CONST | 1,110,955 | 0.4% | 61.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,097,414 | 0.4% | 61.3% |
| POP_TOP LOAD_CONST | 1,090,534 | 0.4% | 61.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,047,177 | 0.3% | 62.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,001,776 | 0.3% | 62.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,000,158 | 0.3% | 62.7% |
| LOAD_FAST TO_BOOL | 999,260 | 0.3% | 63.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 996,398 | 0.3% | 63.3% |
| LOAD_CONST LOAD_FAST | 956,092 | 0.3% | 63.6% |
| LOAD_FAST_LOAD_FAST CALL | 956,067 | 0.3% | 63.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 949,636 | 0.3% | 64.2% |
| BEFORE_WITH POP_TOP | 948,416 | 0.3% | 64.6% |
| RETURN_VALUE STORE_FAST | 948,011 | 0.3% | 64.9% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 946,579 | 0.3% | 65.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 943,072 | 0.3% | 65.5% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 941,738 | 0.3% | 65.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 929,697 | 0.3% | 66.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 929,078 | 0.3% | 66.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 911,696 | 0.3% | 66.7% |
| LOAD_ATTR PUSH_NULL | 906,947 | 0.3% | 67.0% |
| CALL_FUNCTION_EX RETURN_VALUE | 896,819 | 0.3% | 67.3% |
| JUMP_BACKWARD FOR_ITER | 893,040 | 0.3% | 67.6% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 888,659 | 0.3% | 67.8% |
| LOAD_FAST BUILD_TUPLE | 876,139 | 0.3% | 68.1% |
| LOAD_CONST COMPARE_OP_INT | 865,722 | 0.3% | 68.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 862,459 | 0.3% | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 862,449 | 0.3% | 69.0% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 821,040 | 0.3% | 69.2% |
| BUILD_TUPLE YIELD_VALUE | 816,000 | 0.3% | 69.5% |
| GET_ITER FOR_ITER_LIST | 809,096 | 0.3% | 69.8% |
| LOAD_CONST COPY | 800,640 | 0.3% | 70.0% |
| POP_TOP NOP | 798,694 | 0.3% | 70.3% |
| COPY STORE_FAST_STORE_FAST | 796,080 | 0.3% | 70.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 796,060 | 0.3% | 70.8% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 792,000 | 0.3% | 71.1% |
| STORE_FAST_STORE_FAST STORE_FAST | 792,000 | 0.3% | 71.3% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 792,000 | 0.3% | 71.6% |
| JUMP_BACKWARD NOP | 792,000 | 0.3% | 71.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 791,066 | 0.3% | 72.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 12,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,720 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,720,301 | 99.2% |
| COPY_FREE_VARS | 54,480 | 0.7% |
| POP_TOP | 4,560 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 888,659 | 77.2% |
| RETURN_VALUE | 198,028 | 17.2% |
| LOAD_GLOBAL_MODULE | 59,757 | 5.2% |
| CALL | 4,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 948,416 | 82.4% |
| STORE_FAST | 202,108 | 17.6% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 19,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,920 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 408,000 | 91.9% |
| LOAD_CONST | 35,706 | 8.0% |
| BINARY_SUBSCR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 408,000 | 91.9% |
| STORE_FAST | 35,706 | 8.0% |
| BINARY_SUBSCR | 220 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,866 | 83.8% |
| LOAD_ATTR_MODULE | 3,840 | 16.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,706 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,597 | 49.1% |
| CALL | 19,917 | 35.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,639 | 15.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,917 | 78.2% |
| RETURN_CONST | 7,677 | 13.7% |
| LOAD_FAST | 4,560 | 8.1% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 4,080 | 50.0% |
| LOAD_FAST | 4,080 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 444,536 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 444,536 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,920 | 52.2% |
| CONVERT_VALUE | 18,240 | 47.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,040 | 76.1% |
| BUILD_STRING | 9,120 | 23.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 614,843 | 53.2% |
| STORE_FAST_LOAD_FAST | 408,000 | 35.3% |
| CALL_BUILTIN_CLASS | 114,739 | 9.9% |
| CALL | 9,120 | 0.8% |
| RETURN_VALUE | 4,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 809,096 | 70.0% |
| LOAD_FAST_AND_CLEAR | 206,907 | 17.9% |
| FOR_ITER_RANGE | 110,299 | 9.5% |
| FOR_ITER_TUPLE | 8,160 | 0.7% |
| FOR_ITER_GEN | 8,160 | 0.7% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,918,199 | 89.0% |
| RETURN_CONST | 448,579 | 5.8% |
| YIELD_VALUE | 408,480 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 41,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 27,600 | 66.9% |
| STORE_FAST | 9,120 | 22.1% |
| LOAD_FAST | 4,560 | 11.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,099,294 | 39.2% |
| POP_TOP | 798,694 | 14.9% |
| JUMP_BACKWARD | 792,000 | 14.8% |
| POP_JUMP_IF_FALSE | 719,102 | 13.4% |
| RESUME_CHECK | 599,179 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,510,612 | 65.6% |
| LOAD_GLOBAL_MODULE | 736,831 | 13.8% |
| LOAD_FAST_LOAD_FAST | 412,560 | 7.7% |
| LOAD_CONST | 396,240 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 287,825 | 5.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 15,786 | 56.8% |
| COPY | 8,160 | 29.4% |
| POP_TOP | 3,840 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 15,786 | 56.8% |
| RERAISE | 8,160 | 29.4% |
| JUMP_FORWARD | 3,840 | 13.8% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,896,480 | 35.3% |
| RETURN_CONST | 3,181,127 | 23.0% |
| CALL | 1,385,212 | 10.0% |
| BEFORE_WITH | 948,416 | 6.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 786,960 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,788,446 | 41.8% |
| LOAD_FAST | 3,542,254 | 25.6% |
| RETURN_CONST | 1,110,955 | 8.0% |
| LOAD_CONST | 1,090,534 | 7.9% |
| NOP | 798,694 | 5.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,866 | 71.5% |
| RERAISE | 4,080 | 14.7% |
| CALL_KW | 3,840 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,866 | 71.5% |
| WITH_EXCEPT_START | 4,080 | 14.7% |
| LOAD_GLOBAL_MODULE | 3,840 | 13.8% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,488,590 | 53.5% |
| LOAD_ATTR_MODULE | 1,190,190 | 25.6% |
| LOAD_ATTR | 906,947 | 19.5% |
| LOAD_SUPER_ATTR_ATTR | 41,280 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,198,599 | 47.3% |
| CALL | 1,255,502 | 27.0% |
| LOAD_FAST_LOAD_FAST | 941,738 | 20.2% |
| LOAD_CONST | 181,581 | 3.9% |
| CALL_PY_EXACT_ARGS | 34,080 | 0.7% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,080 | 32.1% |
| RETURN_VALUE | 4,080 | 32.1% |
| LOAD_FAST | 4,080 | 32.1% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 3.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,236,030 | 52.6% |
| CALL | 1,355,659 | 11.4% |
| CALL_FUNCTION_EX | 896,819 | 7.6% |
| RETURN_VALUE | 767,889 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 659,542 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 6,918,199 | 58.3% |
| STORE_FAST | 948,011 | 8.0% |
| RETURN_VALUE | 767,889 | 6.5% |
| POP_TOP | 599,133 | 5.0% |
| LOAD_FAST_LOAD_FAST | 454,459 | 3.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 9,120 | 43.2% |
| LOAD_FAST | 7,700 | 36.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,080 | 19.3% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 13,200 | 62.6% |
| LOAD_GLOBAL_MODULE | 7,680 | 36.4% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 10 | 0.0% |
| LOAD_FAST | 10 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 999,260 | 96.3% |
| LOAD_ATTR_INSTANCE_VALUE | 37,195 | 3.6% |
| TO_BOOL | 1,041 | 0.1% |
| LOAD_ATTR | 2 | 0.0% |
| RETURN_VALUE | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 521,050 | 50.2% |
| POP_JUMP_IF_FALSE | 515,407 | 49.7% |
| TO_BOOL | 1,041 | 0.1% |
| TO_BOOL_BOOL | 1 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 454,459 | 68.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 209,776 | 31.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 664,235 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 124,002 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 124,002 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 4,080 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,468,265 | 52.9% |
| UNARY_INVERT | 664,235 | 23.9% |
| POP_JUMP_IF_FALSE | 454,459 | 16.4% |
| LOAD_ATTR | 114,008 | 4.1% |
| LOAD_FAST_LOAD_FAST | 37,200 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,118,694 | 40.3% |
| STORE_FAST | 568,467 | 20.5% |
| UNARY_INVERT | 454,459 | 16.4% |
| TO_BOOL_INT | 454,459 | 16.4% |
| BUILD_TUPLE | 104,888 | 3.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 206,907 | 33.4% |
| JUMP_FORWARD | 198,028 | 32.0% |
| LOAD_FAST | 105,129 | 17.0% |
| POP_TOP | 92,899 | 15.0% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 210,028 | 33.9% |
| SWAP | 206,907 | 33.4% |
| STORE_FAST | 198,508 | 32.1% |
| RETURN_VALUE | 3,840 | 0.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 408,000 | 38.7% |
| LOAD_FAST | 396,240 | 37.5% |
| RESUME_CHECK | 205,708 | 19.5% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 12,240 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 635,068 | 60.2% |
| BUILD_TUPLE | 408,000 | 38.7% |
| STORE_FAST | 12,240 | 1.2% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,920 | 68.6% |
| FORMAT_SIMPLE | 9,120 | 31.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 19,920 | 68.6% |
| RETURN_VALUE | 9,120 | 31.4% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 876,139 | 33.4% |
| LOAD_FAST_LOAD_FAST | 821,040 | 31.3% |
| BUILD_MAP | 408,000 | 15.5% |
| RETURN_VALUE | 384,000 | 14.6% |
| BINARY_OP | 104,888 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 816,000 | 31.1% |
| CALL | 454,939 | 17.3% |
| BUILD_MAP | 408,000 | 15.5% |
| STORE_FAST | 384,000 | 14.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 14.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,694,013 | 26.0% |
| PUSH_NULL | 1,255,502 | 19.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,000,158 | 15.3% |
| LOAD_FAST_LOAD_FAST | 956,067 | 14.6% |
| BUILD_TUPLE | 454,939 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,740,249 | 26.7% |
| POP_TOP | 1,385,212 | 21.2% |
| RETURN_VALUE | 1,355,659 | 20.8% |
| TO_BOOL_BOOL | 512,780 | 7.9% |
| LOAD_FAST | 503,197 | 7.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,309,979 | 75.7% |
| DICT_MERGE | 420,720 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 896,819 | 51.8% |
| RESUME_CHECK | 400,320 | 23.1% |
| CALL_BUILTIN_CLASS | 384,000 | 22.2% |
| POP_TOP | 45,360 | 2.6% |
| STORE_FAST | 4,080 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 170,968 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 123,859 | 72.4% |
| LOAD_FAST | 20,400 | 11.9% |
| RETURN_VALUE | 13,680 | 8.0% |
| STORE_FAST | 9,120 | 5.3% |
| PUSH_EXC_INFO | 3,840 | 2.2% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 235,670 | 99.8% |
| COMPARE_OP | 260 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 175 | 0.1% |
| COMPARE_OP_INT | 63 | 0.0% |
| LOAD_GLOBAL_MODULE | 17 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 235,804 | 99.8% |
| COMPARE_OP | 260 | 0.1% |
| COMPARE_OP_INT | 104 | 0.0% |
| COMPARE_OP_STR | 17 | 0.0% |
| POP_JUMP_IF_TRUE | 6 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 862,449 | 100.0% |
| LOAD_ATTR | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 862,459 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 9,120 | 50.0% |
| BINARY_SUBSCR_DICT | 9,120 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 18,240 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,948,080 | 45.0% |
| BINARY_OP | 1,118,694 | 25.9% |
| LOAD_CONST | 800,640 | 18.5% |
| LOAD_FAST | 417,120 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 13,680 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,948,320 | 45.0% |
| TO_BOOL_INT | 1,118,694 | 25.9% |
| STORE_FAST_STORE_FAST | 796,080 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 407,980 | 9.4% |
| LOAD_FAST | 18,240 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 454,459 | 63.9% |
| CALL_ALLOC_AND_ENTER_INIT | 198,028 | 27.8% |
| CACHE | 54,480 | 7.7% |
| CALL | 4,080 | 0.6% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 711,167 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,191 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,794 | 66.7% |
| RETURN_CONST | 19,917 | 32.5% |
| LOAD_GLOBAL_MODULE | 480 | 0.8% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,240 | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 420,720 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 893,040 | 97.6% |
| SWAP | 9,120 | 1.0% |
| GET_ITER | 8,160 | 0.9% |
| LOAD_FAST | 4,080 | 0.4% |
| FOR_ITER | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 480,960 | 52.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 412,080 | 45.0% |
| SWAP | 9,120 | 1.0% |
| RETURN_CONST | 8,160 | 0.9% |
| LOAD_GLOBAL_MODULE | 4,080 | 0.4% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 21,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,840 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 21,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 21,840 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 19,920 | 60.7% |
| LOAD_FAST | 12,240 | 37.3% |
| LOAD_GLOBAL_MODULE | 638 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 32,798 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,788,446 | 48.9% |
| STORE_FAST | 4,080,000 | 34.4% |
| POP_JUMP_IF_NOT_NONE | 570,038 | 4.8% |
| STORE_FAST_STORE_FAST | 412,080 | 3.5% |
| FOR_ITER_LIST | 408,000 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,939,393 | 41.7% |
| FOR_ITER_GEN | 4,488,000 | 37.9% |
| FOR_ITER | 893,040 | 7.5% |
| NOP | 792,000 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 408,000 | 3.4% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 433,194 | 49.6% |
| POP_TOP | 427,382 | 49.0% |
| STORE_ATTR_INSTANCE_VALUE | 4,560 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 4,080 | 0.5% |
| POP_EXCEPT | 3,840 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 629,725 | 72.1% |
| BUILD_LIST | 198,028 | 22.7% |
| LOAD_GLOBAL_MODULE | 17,037 | 2.0% |
| POP_EXCEPT | 15,786 | 1.8% |
| LOAD_FAST_LOAD_FAST | 4,560 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 170,954 | 49.0% |
| LOAD_ATTR | 104,888 | 30.1% |
| BINARY_SUBSCR_STR_INT | 72,960 | 20.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 348,802 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,379 | 50.1% |
| RETURN_VALUE | 92,899 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,139 | 50.0% |
| STORE_FAST | 92,899 | 49.9% |
| RETURN_VALUE | 240 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,308,398 | 70.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,126,787 | 24.1% |
| LOAD_GLOBAL_MODULE | 177,717 | 3.8% |
| CALL | 37,200 | 0.8% |
| LOAD_FAST_LOAD_FAST | 13,220 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,407,256 | 30.1% |
| PUSH_NULL | 906,947 | 19.4% |
| POP_JUMP_IF_NOT_NONE | 462,063 | 9.9% |
| STORE_SUBSCR_DICT | 454,459 | 9.7% |
| STORE_FAST | 327,606 | 7.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,371,917 | 26.3% |
| LOAD_FAST | 1,893,365 | 21.0% |
| POP_TOP | 1,090,534 | 12.1% |
| POP_JUMP_IF_FALSE | 574,007 | 6.4% |
| LOAD_ATTR_METHOD_NO_DICT | 516,201 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,371,917 | 26.3% |
| CALL | 1,694,013 | 18.8% |
| LOAD_FAST | 956,092 | 10.6% |
| COMPARE_OP_INT | 865,722 | 9.6% |
| COPY | 800,640 | 8.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 706,967 | 94.6% |
| STORE_DEREF | 19,920 | 2.7% |
| POP_JUMP_IF_NOT_NONE | 19,920 | 2.7% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 706,967 | 94.6% |
| POP_JUMP_IF_NOT_NONE | 39,840 | 5.3% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,882,150 | 22.9% |
| STORE_FAST | 6,389,415 | 12.3% |
| POP_JUMP_IF_FALSE | 3,931,208 | 7.6% |
| POP_TOP | 3,542,254 | 6.8% |
| NOP | 3,510,612 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 12,561,928 | 24.2% |
| RETURN_VALUE | 6,236,030 | 12.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,543,727 | 6.8% |
| LOAD_ATTR | 3,308,398 | 6.4% |
| PUSH_NULL | 2,488,590 | 4.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 206,907 | 66.4% |
| LOAD_FAST_AND_CLEAR | 104,888 | 33.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 206,907 | 66.4% |
| LOAD_FAST_AND_CLEAR | 104,888 | 33.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 408,000 | 79.5% |
| POP_JUMP_IF_NONE | 93,140 | 18.2% |
| LOAD_ATTR_CLASS | 11,939 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 408,000 | 79.5% |
| LOAD_GLOBAL_MODULE | 93,140 | 18.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 11,939 | 2.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,047,177 | 13.7% |
| LOAD_FAST_LOAD_FAST | 996,398 | 13.1% |
| PUSH_NULL | 941,738 | 12.4% |
| POP_JUMP_IF_FALSE | 593,722 | 7.8% |
| STORE_FAST_STORE_FAST | 580,022 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,613,124 | 21.2% |
| LOAD_FAST_LOAD_FAST | 996,398 | 13.1% |
| CALL | 956,067 | 12.5% |
| BUILD_TUPLE | 821,040 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 686,276 | 9.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 37.7% |
| RESUME_CHECK | 40 | 18.9% |
| POP_JUMP_IF_FALSE | 40 | 18.9% |
| POP_JUMP_IF_TRUE | 26 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 17 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 115 | 54.2% |
| LOAD_ATTR | 48 | 22.6% |
| LOAD_GLOBAL_BUILTIN | 41 | 19.3% |
| COMPARE_OP | 6 | 2.8% |
| LOAD_FAST | 2 | 0.9% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 79,680 | 80.0% |
| CALL_PY_EXACT_ARGS | 19,920 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 79,680 | 80.0% |
| RESUME_CHECK | 19,920 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,387,588 | 25.6% |
| TO_BOOL_INT | 2,027,612 | 21.7% |
| COMPARE_OP_INT | 1,903,956 | 20.4% |
| COMPARE_OP_STR | 946,579 | 10.1% |
| CONTAINS_OP | 862,459 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,931,208 | 42.1% |
| RETURN_CONST | 1,663,465 | 17.8% |
| NOP | 719,102 | 7.7% |
| LOAD_GLOBAL_MODULE | 627,216 | 6.7% |
| LOAD_FAST_LOAD_FAST | 593,722 | 6.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 497,806 | 92.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,880 | 3.9% |
| LOAD_ATTR | 18,240 | 3.4% |
| RETURN_VALUE | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,630 | 29.7% |
| LOAD_GLOBAL_MODULE | 130,247 | 24.2% |
| NOP | 120,499 | 22.4% |
| LOAD_FAST_CHECK | 93,140 | 17.3% |
| RETURN_CONST | 16,800 | 3.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,579,512 | 59.6% |
| LOAD_ATTR | 462,063 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 383,372 | 14.5% |
| RETURN_VALUE | 171,194 | 6.5% |
| LOAD_DEREF | 39,840 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,216,370 | 45.9% |
| JUMP_BACKWARD | 570,038 | 21.5% |
| RETURN_CONST | 462,221 | 17.4% |
| NOP | 203,180 | 7.7% |
| LOAD_CONST | 92,899 | 3.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,097,414 | 66.9% |
| TO_BOOL | 521,050 | 31.8% |
| TO_BOOL_NONE | 13,200 | 0.8% |
| COMPARE_OP_STR | 7,956 | 0.5% |
| COMPARE_OP_INT | 1,118 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680,697 | 41.5% |
| LOAD_FAST_LOAD_FAST | 522,488 | 31.8% |
| RETURN_CONST | 322,977 | 19.7% |
| LOAD_GLOBAL_MODULE | 44,086 | 2.7% |
| RETURN_VALUE | 35,706 | 2.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,080 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 8,160 | 66.7% |
| POP_JUMP_IF_TRUE | 4,080 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,080 | 50.0% |
| COPY | 4,080 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,663,465 | 36.2% |
| POP_TOP | 1,110,955 | 24.2% |
| STORE_ATTR_INSTANCE_VALUE | 943,072 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 462,221 | 10.0% |
| POP_JUMP_IF_TRUE | 322,977 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,181,127 | 69.2% |
| TO_BOOL_BOOL | 462,372 | 10.1% |
| INTERPRETER_EXIT | 448,579 | 9.8% |
| EXIT_INIT_CHECK | 444,536 | 9.7% |
| STORE_FAST | 36,186 | 0.8% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 27,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 27,600 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,241 | 58.2% |
| LOAD_FAST_LOAD_FAST | 13,200 | 21.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,240 | 19.6% |
| STORE_ATTR | 620 | 1.0% |
| SWAP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 32,160 | 51.6% |
| LOAD_FAST_LOAD_FAST | 9,120 | 14.6% |
| LOAD_FAST | 8,170 | 13.1% |
| LOAD_CONST | 8,161 | 13.1% |
| LOAD_GLOBAL_BUILTIN | 4,080 | 6.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 39,840 | 40.0% |
| LOAD_ATTR_MODULE | 39,840 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 19,920 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 39,840 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 19,920 | 20.0% |
| LOAD_FAST | 19,920 | 20.0% |
| LOAD_DEREF | 19,920 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,488,000 | 27.1% |
| COPY | 1,948,320 | 11.8% |
| CALL | 1,740,249 | 10.5% |
| RETURN_VALUE | 948,011 | 5.7% |
| STORE_FAST_STORE_FAST | 792,000 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,389,415 | 38.6% |
| JUMP_BACKWARD | 4,080,000 | 24.6% |
| NOP | 2,099,294 | 12.7% |
| COPY | 1,948,080 | 11.8% |
| LOAD_GLOBAL_BUILTIN | 498,524 | 3.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,080,000 | 89.3% |
| FOR_ITER | 480,960 | 10.5% |
| COPY | 9,120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,080,000 | 89.3% |
| GET_ITER | 408,000 | 8.9% |
| LOAD_FAST | 72,960 | 1.6% |
| STORE_ATTR_INSTANCE_VALUE | 9,120 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,207,398 | 38.0% |
| COPY | 796,080 | 25.0% |
| UNPACK_SEQUENCE_TUPLE | 792,000 | 24.9% |
| STORE_FAST_STORE_FAST | 384,000 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,001,776 | 31.5% |
| STORE_FAST | 792,000 | 24.9% |
| LOAD_FAST_LOAD_FAST | 580,022 | 18.2% |
| JUMP_BACKWARD | 412,080 | 13.0% |
| STORE_FAST_STORE_FAST | 384,000 | 12.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 407,990 | 32.7% |
| LOAD_FAST_AND_CLEAR | 206,907 | 16.6% |
| BUILD_LIST | 206,907 | 16.6% |
| FOR_ITER_LIST | 197,787 | 15.9% |
| LOAD_FAST | 113,060 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 407,980 | 32.7% |
| LOAD_CONST | 217,948 | 17.5% |
| STORE_FAST | 206,907 | 16.6% |
| BUILD_LIST | 206,907 | 16.6% |
| FOR_ITER_LIST | 197,787 | 15.9% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,080,000 | 83.3% |
| BUILD_TUPLE | 816,000 | 16.7% |
| CALL_STR_1 | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,488,000 | 91.7% |
| INTERPRETER_EXIT | 408,480 | 8.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 105,129 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 105,129 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 796,060 | 98.4% |
| LOAD_FAST_LOAD_FAST | 12,720 | 1.6% |
| BINARY_OP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 407,990 | 50.4% |
| STORE_FAST | 384,000 | 47.5% |
| BINARY_SLICE | 12,720 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,080 | 0.5% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 50.0% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 50.0% |
| LOAD_CONST | 480 | 50.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 72,960 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 93,140 | 99.9% |
| LOAD_FAST | 80 | 0.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 93,260 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 122,378 | 75.5% |
| LOAD_CONST | 35,706 | 22.0% |
| CALL_LEN | 4,080 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 158,084 | 97.5% |
| CALL_BUILTIN_CLASS | 4,080 | 2.5% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 72,000 | 88.8% |
| LOAD_CONST | 9,120 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,000 | 88.8% |
| CONVERT_VALUE | 9,120 | 11.2% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 185,798 | 95.8% |
| LOAD_CONST | 8,160 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 185,798 | 95.8% |
| LOAD_CONST | 8,160 | 4.2% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 72,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 72,960 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 25,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,840 | 84.3% |
| JUMP_FORWARD | 4,080 | 15.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 217,948 | 49.0% |
| LOAD_FAST | 202,588 | 45.6% |
| CALL | 24,000 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 246,508 | 55.5% |
| COPY_FREE_VARS | 198,028 | 44.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 24,267 | 42.6% |
| LOAD_FAST | 24,000 | 42.1% |
| LOAD_CONST | 4,560 | 8.0% |
| BINARY_OP_ADD_INT | 4,080 | 7.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,844 | 92.7% |
| POP_TOP | 4,080 | 7.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 54.2% |
| LOAD_FAST | 117,689 | 16.6% |
| CALL_LEN | 92,899 | 13.1% |
| CALL_BUILTIN_CLASS | 92,899 | 13.1% |
| LOAD_CONST | 9,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 489,129 | 69.0% |
| GET_ITER | 114,739 | 16.2% |
| CALL_BUILTIN_CLASS | 92,899 | 13.1% |
| LOAD_FAST | 12,240 | 1.7% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 355,580 | 44.1% |
| LOAD_CONST | 298,598 | 37.0% |
| LOAD_FAST_LOAD_FAST | 80,138 | 9.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 36,229 | 4.5% |
| LOAD_GLOBAL_MODULE | 18,240 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 293,078 | 36.3% |
| STORE_FAST | 256,306 | 31.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 172,022 | 21.3% |
| UNPACK_SEQUENCE_TUPLE | 36,229 | 4.5% |
| POP_TOP | 9,310 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,400 | 46.9% |
| BUILD_TUPLE | 384,000 | 46.6% |
| CALL | 24,290 | 2.9% |
| LOAD_FAST_CHECK | 11,939 | 1.4% |
| LOAD_ATTR | 9,120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 786,960 | 95.5% |
| RETURN_VALUE | 36,229 | 4.4% |
| LOAD_FAST | 480 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 72,960 | 88.9% |
| LOAD_FAST | 9,120 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 72,960 | 88.9% |
| LOAD_FAST | 9,120 | 11.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 466,699 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 466,699 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 261,311 | 92.9% |
| LOAD_ATTR_INSTANCE_VALUE | 19,920 | 7.1% |
| CALL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 155,978 | 55.5% |
| CALL_BUILTIN_CLASS | 92,899 | 33.0% |
| CALL_PY_EXACT_ARGS | 24,000 | 8.5% |
| LOAD_FAST | 4,080 | 1.5% |
| BINARY_OP_SUBTRACT_INT | 4,080 | 1.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 104,888 | 92.8% |
| LOAD_FAST | 8,160 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 104,888 | 92.8% |
| LOAD_GLOBAL_MODULE | 8,160 | 7.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 652,487 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,715 | 0.3% |
| LOAD_CONST | 480 | 0.1% |
| CALL | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 454,459 | 69.4% |
| STORE_FAST | 199,753 | 30.5% |
| TO_BOOL_NONE | 480 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,600 | 87.1% |
| BUILD_TUPLE | 4,080 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 23,520 | 74.2% |
| LOAD_FAST | 8,160 | 25.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 784,125 | 94.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 48,168 | 5.8% |
| LOAD_ATTR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 408,000 | 49.0% |
| POP_TOP | 282,640 | 33.9% |
| LOAD_FAST | 37,680 | 4.5% |
| RETURN_VALUE | 36,598 | 4.4% |
| CALL_BUILTIN_FAST | 36,229 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 573,207 | 91.7% |
| LOAD_CONST | 21,840 | 3.5% |
| CALL | 20,410 | 3.3% |
| RETURN_VALUE | 9,120 | 1.5% |
| RETURN_GENERATOR | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 593,617 | 95.0% |
| LOAD_CONST | 21,840 | 3.5% |
| RETURN_VALUE | 9,120 | 1.5% |
| BINARY_OP_ADD_UNICODE | 480 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 2,581,882 | 46.2% |
| LOAD_FAST | 2,082,250 | 37.3% |
| LOAD_FAST_LOAD_FAST | 510,019 | 9.1% |
| LOAD_SUPER_ATTR_METHOD | 198,028 | 3.5% |
| LOAD_GLOBAL_MODULE | 67,920 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,553,487 | 99.4% |
| MAKE_CELL | 19,920 | 0.4% |
| RETURN_GENERATOR | 12,720 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 691,416 | 50.0% |
| LOAD_ATTR_MODULE | 454,459 | 32.8% |
| LOAD_FAST | 141,848 | 10.2% |
| LOAD_CONST | 55,393 | 4.0% |
| BINARY_OP | 37,200 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 929,697 | 67.2% |
| COPY_FREE_VARS | 454,459 | 32.8% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 94.1% |
| YIELD_VALUE | 480 | 5.9% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 412,080 | 99.9% |
| LOAD_FAST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 412,080 | 99.9% |
| LOAD_FAST | 480 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 480 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 865,722 | 45.4% |
| LOAD_ATTR_INSTANCE_VALUE | 603,793 | 31.7% |
| LOAD_FAST | 408,000 | 21.4% |
| LOAD_FAST_LOAD_FAST | 12,720 | 0.7% |
| CALL_BUILTIN_FAST | 9,120 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,903,956 | 99.9% |
| POP_JUMP_IF_TRUE | 1,118 | 0.1% |
| COMPARE_OP | 63 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 929,078 | 95.5% |
| LOAD_CONST | 39,600 | 4.1% |
| LOAD_FAST | 4,080 | 0.4% |
| COMPARE_OP | 17 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 946,579 | 97.3% |
| LOAD_FAST | 9,120 | 0.9% |
| COPY | 9,120 | 0.9% |
| POP_JUMP_IF_TRUE | 7,956 | 0.8% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,488,000 | 99.8% |
| GET_ITER | 8,160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,488,000 | 99.8% |
| POP_TOP | 8,160 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,939,393 | 83.1% |
| GET_ITER | 809,096 | 13.6% |
| SWAP | 197,787 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,080,000 | 68.6% |
| STORE_FAST | 649,617 | 10.9% |
| JUMP_BACKWARD | 408,000 | 6.9% |
| LOAD_FAST | 396,056 | 6.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 209,776 | 3.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 205,768 | 65.1% |
| GET_ITER | 110,299 | 34.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 215,128 | 68.1% |
| LOAD_FAST | 93,019 | 29.4% |
| RETURN_CONST | 7,920 | 2.5% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 9,120 | 51.4% |
| GET_ITER | 8,160 | 45.9% |
| LOAD_FAST | 480 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,120 | 51.4% |
| LOAD_FAST | 7,680 | 43.2% |
| RETURN_CONST | 960 | 5.4% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 36,229 | 82.5% |
| LOAD_ATTR_MODULE | 7,680 | 17.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,970 | 72.8% |
| LOAD_FAST_CHECK | 11,939 | 27.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,561,928 | 91.8% |
| LOAD_FAST_LOAD_FAST | 686,276 | 5.0% |
| COPY | 407,980 | 3.0% |
| LOAD_ATTR_INSTANCE_VALUE | 16,258 | 0.1% |
| RETURN_VALUE | 9,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,233,342 | 23.6% |
| LOAD_FAST | 2,080,568 | 15.2% |
| LOAD_ATTR | 1,126,787 | 8.2% |
| LOAD_GLOBAL_MODULE | 949,636 | 6.9% |
| BEFORE_WITH | 888,659 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,116 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,458 | 39.8% |
| CALL | 61,490 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,168 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,233,342 | 88.1% |
| LOAD_FAST | 343,789 | 9.4% |
| LOAD_ATTR | 37,220 | 1.0% |
| LOAD_ATTR_SLOT | 37,200 | 1.0% |
| LOAD_CONST | 9,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,213,531 | 33.1% |
| CALL | 1,000,158 | 27.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 784,125 | 21.4% |
| LOAD_CONST | 516,201 | 14.1% |
| LOAD_FAST_LOAD_FAST | 135,856 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,543,727 | 67.8% |
| LOAD_ATTR_INSTANCE_VALUE | 791,066 | 15.1% |
| LOAD_FAST_LOAD_FAST | 454,459 | 8.7% |
| BINARY_SUBSCR | 408,000 | 7.8% |
| LOAD_GLOBAL_MODULE | 20,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,581,882 | 49.4% |
| LOAD_FAST | 1,378,771 | 26.4% |
| CALL_PY_WITH_DEFAULTS | 691,416 | 13.2% |
| LOAD_FAST_LOAD_FAST | 457,920 | 8.8% |
| LOAD_CONST | 68,113 | 1.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,748,061 | 100.0% |
| LOAD_ATTR | 98 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,190,190 | 68.1% |
| CALL_PY_WITH_DEFAULTS | 454,459 | 26.0% |
| STORE_DEREF | 39,840 | 2.3% |
| LOAD_CONST | 22,800 | 1.3% |
| LOAD_FAST | 19,920 | 1.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,339 | 69.6% |
| LOAD_FAST_LOAD_FAST | 209,776 | 30.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 454,459 | 65.8% |
| UNARY_INVERT | 209,776 | 30.4% |
| RETURN_VALUE | 9,120 | 1.3% |
| LOAD_CONST | 9,120 | 1.3% |
| LOAD_FAST_LOAD_FAST | 4,080 | 0.6% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 406,830 | 95.2% |
| RETURN_VALUE | 19,920 | 4.7% |
| LOAD_GLOBAL_MODULE | 480 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 418,270 | 97.9% |
| TO_BOOL_BOOL | 8,960 | 2.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 37,200 | 80.3% |
| CALL_BUILTIN_FAST | 9,120 | 19.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,624,866 | 39.4% |
| LOAD_GLOBAL_BUILTIN | 569,798 | 13.8% |
| STORE_FAST | 498,524 | 12.1% |
| LOAD_FAST | 484,459 | 11.8% |
| JUMP_BACKWARD | 408,000 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,870,883 | 45.4% |
| LOAD_DEREF | 706,967 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 569,798 | 13.8% |
| CALL_ISINSTANCE | 466,699 | 11.3% |
| LOAD_GLOBAL_MODULE | 439,920 | 10.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,921,914 | 24.5% |
| RESUME_CHECK | 1,371,541 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 949,636 | 12.1% |
| NOP | 736,831 | 9.4% |
| POP_JUMP_IF_FALSE | 627,216 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,748,061 | 22.3% |
| BINARY_OP | 1,468,265 | 18.7% |
| LOAD_FAST_LOAD_FAST | 1,047,177 | 13.4% |
| COMPARE_OP_STR | 929,078 | 11.9% |
| LOAD_FAST | 911,696 | 11.6% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 41,280 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 665,687 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 463,579 | 69.6% |
| CALL_PY_EXACT_ARGS | 198,028 | 29.7% |
| LOAD_FAST | 4,080 | 0.6% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 7,720,301 | 36.9% |
| CALL_PY_EXACT_ARGS | 5,553,487 | 26.5% |
| FOR_ITER_GEN | 4,488,000 | 21.5% |
| CALL_PY_WITH_DEFAULTS | 929,697 | 4.4% |
| COPY_FREE_VARS | 711,167 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,882,150 | 56.8% |
| POP_TOP | 4,896,480 | 23.4% |
| LOAD_GLOBAL_BUILTIN | 1,624,866 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,371,541 | 6.6% |
| NOP | 599,179 | 2.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,457,391 | 64.1% |
| SWAP | 407,980 | 18.0% |
| LOAD_FAST_LOAD_FAST | 382,588 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 12,240 | 0.5% |
| STORE_FAST_LOAD_FAST | 9,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 943,072 | 41.5% |
| LOAD_FAST | 641,990 | 28.3% |
| LOAD_GLOBAL_MODULE | 348,748 | 15.3% |
| LOAD_CONST | 153,119 | 6.7% |
| LOAD_FAST_LOAD_FAST | 90,720 | 4.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,200 | 80.3% |
| LOAD_FAST_LOAD_FAST | 9,120 | 19.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,320 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 454,459 | 87.8% |
| LOAD_FAST | 30,755 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 4.7% |
| CALL | 7,680 | 1.5% |
| LOAD_CONST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 456,184 | 88.1% |
| RETURN_CONST | 21,840 | 4.2% |
| LOAD_GLOBAL_MODULE | 19,920 | 3.8% |
| LOAD_CONST | 19,920 | 3.8% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 60.3% |
| COPY | 158 | 39.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 240 | 60.3% |
| POP_JUMP_IF_FALSE | 158 | 39.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 746,971 | 20.7% |
| CALL | 512,780 | 14.2% |
| LOAD_FAST | 501,786 | 13.9% |
| CALL_ISINSTANCE | 466,699 | 12.9% |
| RETURN_CONST | 462,372 | 12.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,387,588 | 66.2% |
| POP_JUMP_IF_TRUE | 1,097,414 | 30.4% |
| UNARY_NOT | 124,002 | 3.4% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,118,694 | 55.2% |
| LOAD_FAST | 454,459 | 22.4% |
| BINARY_OP | 454,459 | 22.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,027,612 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 206,188 | 87.5% |
| LOAD_ATTR_INSTANCE_VALUE | 29,520 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 235,708 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 135,272 | 80.1% |
| LOAD_FAST | 19,920 | 11.8% |
| COPY | 9,120 | 5.4% |
| WITH_EXCEPT_START | 4,080 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 155,672 | 92.2% |
| POP_JUMP_IF_TRUE | 13,200 | 7.8% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 792,000 | 95.6% |
| CALL_BUILTIN_FAST | 36,229 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 792,000 | 95.6% |
| STORE_FAST | 36,229 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 412,080 | 34.0% |
| LOAD_FAST_CHECK | 408,000 | 33.7% |
| FOR_ITER_LIST | 209,776 | 17.3% |
| CALL_BUILTIN_FAST | 172,022 | 14.2% |
| CALL | 5,520 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,207,398 | 99.6% |
| LOAD_FAST | 4,560 | 0.4% |


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

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       443706 | 54.3% |
|          hit |       373958 | 45.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 220 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 220 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        20890 | 3.9% |
|          hit |       517864 | 96.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 10 | 4.8% |
| Failure | 200 | 95.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 120 | 60.0% |
| other | 80 | 40.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1036457 | 14.6% |
|          hit |      6041594 | 85.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1 | 0.1% |
| Failure | 1,041 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 321 | 30.8% |
| tuple | 220 | 21.1% |
| sequence | 220 | 21.1% |
| set | 200 | 19.2% |
| other | 80 | 7.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2775532 | 68.7% |
|          hit |      1263183 | 31.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 50 | 3.3% |
| Failure | 1,459 | 96.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 681 | 46.7% |
| or | 373 | 25.6% |
| remainder | 205 | 14.1% |
| add different types | 160 | 11.0% |
| add other | 40 | 2.7% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6518165 | 32.8% |
| specialization.deopt |           60 | 0.0% |
|          hit |     13369269 | 67.2% |
|         miss |         4140 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 138 | 1.6% |
| Failure | 8,271 | 98.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,452 | 29.6% |
| cfunc noargs | 1,557 | 18.8% |
| class no vectorcall | 1,183 | 14.3% |
| meth descr varargs keywords | 806 | 9.7% |
| other | 360 | 4.4% |
| class mutable | 306 | 3.7% |
| bound method | 281 | 3.4% |
| operator wrapper | 240 | 2.9% |
| cfunc varargs | 240 | 2.9% |
| cfunc varargs keywords | 226 | 2.7% |
| meth descr method fastcall keywords | 200 | 2.4% |
| cmethod | 200 | 2.4% |
| wrong number arguments | 160 | 1.9% |
| method wrapper | 60 | 0.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       235810 | 7.6% |
| specialization.deopt |           63 | 0.0% |
|          hit |      2873665 | 92.3% |
|         miss |         4247 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 121 | 27.3% |
| Failure | 323 | 72.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 147 | 45.5% |
| different types | 96 | 29.7% |
| big int | 80 | 24.8% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       914400 | 7.8% |
|          hit |     10776263 | 92.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 440 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 140 | 31.8% |
| other | 140 | 31.8% |
| callable | 80 | 18.2% |
| itertools | 80 | 18.2% |


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
| specialization.deferred |      4672326 | 15.4% |
| specialization.deopt |         4147 | 0.0% |
|          hit |     25491427 | 83.9% |
|         miss |       228802 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,353 | 45.3% |
| Failure | 5,256 | 54.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,305 | 24.8% |
| shadowed | 982 | 18.7% |
| not managed dict | 880 | 16.7% |
| non overriding descriptor | 584 | 11.1% |
| class attr descriptor | 360 | 6.8% |
| metaclass attribute | 280 | 5.3% |
| class method obj | 280 | 5.3% |
| has managed dict | 240 | 4.6% |
| non object slot | 160 | 3.0% |
| class attr simple | 85 | 1.6% |
| mutable class | 80 | 1.5% |
| overridden | 20 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           56 | 0.0% |
| specialization.deopt |            5 | 0.0% |
|          hit |     11954315 | 100.0% |
|         miss |         1117 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 161 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       706967 | 100.0% |


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
| specialization.deferred |        61691 | 2.6% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      2170309 | 91.2% |
|         miss |       148120 | 6.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,790 | 81.8% |
| Failure | 620 | 18.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 400 | 64.5% |
| class attr simple | 140 | 22.6% |
| no dict | 80 | 12.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2040187 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 166,775,820 | 54.1% |
| Not specialized | 43,099,158 | 14.0% |
| Specialized | 98,448,407 | 31.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 18,446,744,073,709,551,615 | 100.0% |
| CALL | 6,518,165 | 0.0% |
| LOAD_ATTR | 4,672,326 | 0.0% |
| BINARY_OP | 2,775,532 | 0.0% |
| TO_BOOL | 1,036,457 | 0.0% |
| FOR_ITER | 914,400 | 0.0% |
| BINARY_SUBSCR | 443,706 | 0.0% |
| COMPARE_OP | 235,810 | 0.0% |
| STORE_ATTR | 61,691 | 0.0% |
| STORE_SUBSCR | 20,890 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 159,012 | 41.1% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 38.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,670 | 15.7% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.4% |
| COMPARE_OP_INT | 4,247 | 1.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,140 | 1.1% |
| LOAD_GLOBAL_MODULE | 1,117 | 0.3% |
| RESUME_CHECK | 1 | 0.0% |
| RESUME | 1 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 7,779,341 | 37.2% |
| Calls to Python functions inlined | 13,155,630 | 62.8% |
| Calls via PyEval_EvalFrame (total) | 7,779,341 | 37.2% |
| Calls via PyEval_EvalFrame (vector) | 7,366,301 | 35.2% |
| Calls via PyEval_EvalFrame (generator) | 413,040 | 2.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 7,366,301 | 35.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 442,080 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 400,440 | 1.9% |
| Calls via PyEval_EvalFrame (api) | 292,468 | 1.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 16,470,307 | 78.7% |
| Frame objects created | 27,812 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 10,548,620 | 41.2% |
| Frees to freelist | 10,549,376 |  |
| Allocations | 15,051,941 | 58.8% |
| Allocations to 512 bytes | 14,916,880 | 58.3% |
| Allocations to 4 kbytes | 60,648 | 0.2% |
| Allocations over 4 kbytes | 74,413 | 0.3% |
| Frees | 15,691,944 |  |
| New values | 59,520 |  |
| Interpreter increfs | 120,731,508 | 77.8% |
| Interpreter decrefs | 131,505,616 | 73.7% |
| Increfs | 34,353,518 | 22.2% |
| Decrefs | 47,012,174 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 5,292,401 |  |
| Method cache misses | 30,654 |  |
| Method cache collisions | 40,319 |  |
| Method cache dunder hits | 6,563,016 |  |
| Method cache dunder misses | 9,665 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 11 | 264 | 80,272 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-10-01
