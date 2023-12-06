
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 71,623,759 | 17.6% | 17.6% |  |
| RESUME_CHECK | 29,190,722 | 7.2% | 24.8% | 0.0% |
| STORE_FAST | 22,064,609 | 5.4% | 30.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,336,769 | 4.8% | 34.9% | 1.1% |
| POP_TOP | 19,328,551 | 4.7% | 39.7% |  |
| RETURN_VALUE | 17,011,549 | 4.2% | 43.9% |  |
| POP_JUMP_IF_FALSE | 13,561,630 | 3.3% | 47.2% |  |
| LOAD_CONST | 12,267,329 | 3.0% | 50.2% |  |
| LOAD_GLOBAL_MODULE | 10,634,277 | 2.6% | 52.8% | 0.0% |
| INTERPRETER_EXIT | 10,632,988 | 2.6% | 55.4% |  |
| ENTER_EXECUTOR | 10,059,741 | 2.5% | 57.9% |  |
| CALL | 8,780,223 | 2.2% | 60.1% |  |
| LOAD_FAST_LOAD_FAST | 8,732,100 | 2.1% | 62.2% |  |
| CALL_PY_EXACT_ARGS | 8,080,675 | 2.0% | 64.2% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,218,995 | 1.8% | 66.0% | 1.1% |
| LOAD_ATTR | 6,727,157 | 1.7% | 67.6% |  |
| RETURN_CONST | 6,658,369 | 1.6% | 69.3% |  |
| NOP | 6,626,093 | 1.6% | 70.9% |  |
| YIELD_VALUE | 6,529,020 | 1.6% | 72.5% |  |
| COPY | 6,049,402 | 1.5% | 74.0% |  |
| JUMP_BACKWARD | 5,999,407 | 1.5% | 75.5% |  |
| FOR_ITER_GEN | 5,994,800 | 1.5% | 76.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,130,234 | 1.3% | 78.2% |  |
| TO_BOOL_BOOL | 5,049,002 | 1.2% | 79.4% |  |
| LOAD_GLOBAL_BUILTIN | 5,001,493 | 1.2% | 80.7% | 0.0% |
| PUSH_NULL | 4,541,652 | 1.1% | 81.8% |  |
| BINARY_OP | 4,395,730 | 1.1% | 82.9% |  |
| POP_JUMP_IF_NOT_NONE | 3,807,090 | 0.9% | 83.8% |  |
| STORE_FAST_STORE_FAST | 3,796,784 | 0.9% | 84.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,403,210 | 0.8% | 85.6% | 7.2% |
| TO_BOOL_INT | 3,225,226 | 0.8% | 86.4% |  |
| COMPARE_OP_INT | 2,704,528 | 0.7% | 87.0% | 0.3% |
| BUILD_TUPLE | 2,564,643 | 0.6% | 87.7% |  |
| CALL_FUNCTION_EX | 2,308,024 | 0.6% | 88.2% |  |
| FOR_ITER_LIST | 2,285,181 | 0.6% | 88.8% |  |
| POP_JUMP_IF_TRUE | 2,253,358 | 0.6% | 89.3% |  |
| CALL_PY_WITH_DEFAULTS | 2,034,436 | 0.5% | 89.8% |  |
| SWAP | 1,853,069 | 0.5% | 90.3% |  |
| LOAD_ATTR_MODULE | 1,593,905 | 0.4% | 90.7% | 0.1% |
| BEFORE_WITH | 1,593,834 | 0.4% | 91.1% |  |
| TO_BOOL | 1,413,493 | 0.3% | 91.4% |  |
| COMPARE_OP_STR | 1,321,083 | 0.3% | 91.8% |  |
| JUMP_FORWARD | 1,273,397 | 0.3% | 92.1% |  |
| CONTAINS_OP | 1,267,847 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 1,182,439 | 0.3% | 92.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,172,824 | 0.3% | 93.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,170,225 | 0.3% | 93.2% |  |
| LOAD_DEREF | 1,163,505 | 0.3% | 93.5% |  |
| COPY_FREE_VARS | 1,115,085 | 0.3% | 93.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,487 | 0.3% | 94.1% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,094,047 | 0.3% | 94.3% | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,087,086 | 0.3% | 94.6% |  |
| BINARY_OP_ADD_INT | 1,076,687 | 0.3% | 94.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,053,645 | 0.3% | 95.1% |  |
| UNARY_INVERT | 1,051,546 | 0.3% | 95.4% |  |
| CALL_BUILTIN_FAST | 1,048,117 | 0.3% | 95.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,038,720 | 0.3% | 95.9% | 0.0% |
| GET_ITER | 1,028,629 | 0.3% | 96.2% |  |
| BUILD_LIST | 970,129 | 0.2% | 96.4% |  |
| BUILD_MAP | 916,965 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 831,091 | 0.2% | 96.8% | 0.0% |
| STORE_SUBSCR_DICT | 809,328 | 0.2% | 97.0% |  |
| POP_JUMP_IF_NONE | 805,616 | 0.2% | 97.2% |  |
| CALL_ISINSTANCE | 741,460 | 0.2% | 97.4% |  |
| LOAD_FAST_CHECK | 708,606 | 0.2% | 97.6% |  |
| EXIT_INIT_CHECK | 687,790 | 0.2% | 97.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 687,790 | 0.2% | 97.9% |  |
| LOAD_ATTR_PROPERTY | 664,891 | 0.2% | 98.1% | 1.9% |
| BINARY_SUBSCR | 591,636 | 0.1% | 98.2% |  |
| DICT_MERGE | 561,380 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 537,073 | 0.1% | 98.6% |  |
| LOAD_FAST_AND_CLEAR | 487,602 | 0.1% | 98.8% |  |
| COMPARE_OP | 367,464 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 361,625 | 0.1% | 98.9% |  |
| LIST_EXTEND | 295,992 | 0.1% | 99.0% |  |
| CALL_LEN | 257,818 | 0.1% | 99.1% |  |
| CALL_KW | 252,589 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,648 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 225,209 | 0.1% | 99.2% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 214,729 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 188,779 | 0.0% | 99.3% |  |
| CALL_LIST_APPEND | 174,743 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 163,809 | 0.0% | 99.4% |  |
| UNARY_NOT | 163,440 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 147,942 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 136,160 | 0.0% | 99.5% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.6% |  |
| STORE_DEREF | 132,820 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 95,263 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,600 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 75,020 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 63,600 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,800 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,467 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 44,864 | 0.0% | 99.8% | 13.5% |
| IS_OP | 44,130 | 0.0% | 99.8% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 38,560 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,040 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 37,100 | 0.0% | 99.9% |  |
| POP_EXCEPT | 36,135 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 36,135 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| FOR_ITER | 33,480 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 30,695 | 0.0% | 99.9% |  |
| IMPORT_NAME | 30,240 | 0.0% | 99.9% |  |
| IMPORT_FROM | 29,900 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 28,980 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 26,520 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 25,360 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 24,320 | 0.0% | 100.0% |  |
| BINARY_SLICE | 18,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,858 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 17,440 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 17,300 | 0.0% | 100.0% |  |
| RERAISE | 16,320 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,260 | 0.0% | 100.0% |  |
| END_FOR | 10,880 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,980 | 0.0% | 100.0% | 0.1% |
| RAISE_VARARGS | 5,460 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,440 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 2,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,660 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 800 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 520 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 429 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,671,360 | 4.3% | 4.3% |
| RESUME_CHECK LOAD_FAST | 16,654,934 | 4.1% | 8.4% |
| CACHE RESUME_CHECK | 10,556,548 | 2.6% | 11.0% |
| RETURN_VALUE INTERPRETER_EXIT | 9,438,863 | 2.3% | 13.3% |
| LOAD_FAST RETURN_VALUE | 8,790,800 | 2.2% | 15.5% |
| STORE_FAST LOAD_FAST | 8,575,570 | 2.1% | 17.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,036,675 | 2.0% | 19.6% |
| POP_TOP ENTER_EXECUTOR | 7,276,143 | 1.8% | 21.4% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.6% | 23.0% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.5% | 24.5% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.5% | 25.9% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.5% | 27.4% |
| ENTER_EXECUTOR YIELD_VALUE | 5,971,280 | 1.5% | 28.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,569,913 | 1.4% | 30.2% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.3% | 31.6% |
| POP_TOP LOAD_FAST | 5,132,540 | 1.3% | 32.8% |
| LOAD_FAST LOAD_ATTR | 4,947,871 | 1.2% | 34.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,811,489 | 1.2% | 35.2% |
| RETURN_CONST POP_TOP | 4,597,205 | 1.1% | 36.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,530,186 | 1.1% | 37.5% |
| NOP LOAD_FAST | 3,930,846 | 1.0% | 38.4% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,786,336 | 0.9% | 39.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,383,470 | 0.8% | 40.2% |
| LOAD_CONST LOAD_CONST | 3,258,097 | 0.8% | 41.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,225,086 | 0.8% | 41.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,131,562 | 0.8% | 42.6% |
| STORE_FAST NOP | 2,986,519 | 0.7% | 43.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,935,745 | 0.7% | 44.0% |
| PUSH_NULL LOAD_FAST | 2,913,864 | 0.7% | 44.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,702,192 | 0.7% | 45.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,620,035 | 0.6% | 46.0% |
| COPY STORE_FAST | 2,597,760 | 0.6% | 46.7% |
| STORE_FAST COPY | 2,597,440 | 0.6% | 47.3% |
| LOAD_FAST LOAD_CONST | 2,591,950 | 0.6% | 48.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,492,913 | 0.6% | 48.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,451,305 | 0.6% | 49.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,383,594 | 0.6% | 49.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,336,863 | 0.6% | 50.3% |
| LOAD_CONST CALL | 2,278,244 | 0.6% | 50.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,266,697 | 0.6% | 51.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,171,186 | 0.5% | 52.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,167,323 | 0.5% | 52.5% |
| LOAD_FAST PUSH_NULL | 2,103,720 | 0.5% | 53.0% |
| CALL STORE_FAST | 2,061,069 | 0.5% | 53.5% |
| LOAD_ATTR LOAD_FAST | 2,047,054 | 0.5% | 54.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,927,633 | 0.5% | 54.5% |
| CALL RETURN_VALUE | 1,926,660 | 0.5% | 55.0% |
| CALL POP_TOP | 1,883,734 | 0.5% | 55.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,779,177 | 0.4% | 55.9% |
| BINARY_OP COPY | 1,776,046 | 0.4% | 56.3% |
| COPY TO_BOOL_INT | 1,775,726 | 0.4% | 56.8% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,624 | 0.4% | 57.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,731,278 | 0.4% | 57.6% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,710,703 | 0.4% | 58.0% |
| ENTER_EXECUTOR CALL | 1,676,354 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,652,676 | 0.4% | 58.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,590,663 | 0.4% | 59.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,551,412 | 0.4% | 59.6% |
| POP_TOP RETURN_CONST | 1,545,158 | 0.4% | 60.0% |
| POP_TOP LOAD_CONST | 1,517,320 | 0.4% | 60.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,502,132 | 0.4% | 60.7% |
| RETURN_VALUE STORE_FAST | 1,457,061 | 0.4% | 61.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,447,100 | 0.4% | 61.5% |
| LOAD_CONST LOAD_FAST | 1,410,561 | 0.3% | 61.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,408,454 | 0.3% | 62.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,383,326 | 0.3% | 62.5% |
| LOAD_FAST TO_BOOL | 1,355,693 | 0.3% | 62.8% |
| ENTER_EXECUTOR FOR_ITER_LIST | 1,333,184 | 0.3% | 63.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,329,925 | 0.3% | 63.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,309,936 | 0.3% | 63.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,289,115 | 0.3% | 64.1% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,286,296 | 0.3% | 64.4% |
| LOAD_FAST BUILD_TUPLE | 1,282,060 | 0.3% | 64.7% |
| BEFORE_WITH POP_TOP | 1,276,869 | 0.3% | 65.1% |
| LOAD_CONST COMPARE_OP_INT | 1,271,884 | 0.3% | 65.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,267,227 | 0.3% | 65.7% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,266,567 | 0.3% | 66.0% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,262,005 | 0.3% | 66.3% |
| RETURN_VALUE RETURN_VALUE | 1,214,475 | 0.3% | 66.6% |
| LOAD_ATTR PUSH_NULL | 1,211,711 | 0.3% | 66.9% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,196,044 | 0.3% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,179,789 | 0.3% | 67.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,166,764 | 0.3% | 67.8% |
| POP_TOP NOP | 1,159,735 | 0.3% | 68.1% |
| NOP LOAD_GLOBAL_MODULE | 1,149,397 | 0.3% | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,145,464 | 0.3% | 68.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,136,621 | 0.3% | 68.9% |
| COPY_FREE_VARS RESUME_CHECK | 1,114,425 | 0.3% | 69.2% |
| LOAD_DEREF LOAD_FAST | 1,109,125 | 0.3% | 69.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,108,605 | 0.3% | 69.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,104,434 | 0.3% | 70.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,094,579 | 0.3% | 70.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,080,426 | 0.3% | 70.5% |
| LOAD_CONST COPY | 1,067,520 | 0.3% | 70.8% |
| COPY STORE_FAST_STORE_FAST | 1,061,440 | 0.3% | 71.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,059,647 | 0.3% | 71.3% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,056,280 | 0.3% | 71.6% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,056,220 | 0.3% | 71.8% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,055,880 | 0.3% | 72.1% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,053,445 | 0.3% | 72.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 16,920 | 92.9% |
| LOAD_CONST | 980 | 5.4% |
| LOAD_FAST | 280 | 1.5% |
| BINARY_OP | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 17,300 | 95.0% |
| BUILD_TUPLE | 280 | 1.5% |
| LOAD_DEREF | 280 | 1.5% |
| STORE_FAST | 280 | 1.5% |
| CALL | 80 | 0.4% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,556,548 | 99.2% |
| COPY_FREE_VARS | 73,100 | 0.7% |
| POP_TOP | 6,500 | 0.1% |
| RESUME | 2,280 | 0.0% |
| MAKE_CELL | 20 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,179,789 | 74.0% |
| RETURN_VALUE | 311,625 | 19.6% |
| LOAD_GLOBAL_MODULE | 79,560 | 5.0% |
| LOAD_FAST | 16,320 | 1.0% |
| CALL | 6,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,276,869 | 80.1% |
| STORE_FAST | 316,965 | 19.9% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 26,480 | 99.8% |
| BINARY_OP | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,520 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 544,080 | 92.0% |
| LOAD_CONST | 46,635 | 7.9% |
| BINARY_SUBSCR | 841 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 91.9% |
| STORE_FAST | 46,355 | 7.8% |
| BINARY_SUBSCR | 841 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,535 | 83.2% |
| LOAD_ATTR_MODULE | 5,100 | 16.6% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,695 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,940 | 49.2% |
| CALL | 26,560 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,438 | 15.2% |
| LOAD_ATTR | 82 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,560 | 78.1% |
| RETURN_CONST | 10,240 | 13.6% |
| LOAD_FAST | 6,080 | 8.1% |
| LOAD_GLOBAL_MODULE | 140 | 0.2% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 10,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 5,440 | 50.0% |
| LOAD_FAST | 5,440 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 687,790 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 687,790 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,560 | 52.2% |
| CONVERT_VALUE | 24,320 | 47.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,720 | 76.1% |
| BUILD_STRING | 12,160 | 23.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 963,229 | 93.6% |
| CALL_BUILTIN_CLASS | 34,980 | 3.4% |
| CALL | 12,420 | 1.2% |
| STORE_FAST_LOAD_FAST | 6,080 | 0.6% |
| RETURN_VALUE | 5,440 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 635,770 | 61.8% |
| LOAD_FAST_AND_CLEAR | 324,079 | 31.5% |
| FOR_ITER_RANGE | 29,024 | 2.8% |
| FOR_ITER | 11,476 | 1.1% |
| FOR_ITER_TUPLE | 11,100 | 1.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,438,863 | 88.8% |
| RETURN_CONST | 649,025 | 6.1% |
| YIELD_VALUE | 545,100 | 5.1% |


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
| LOAD_CONST | 59,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 38,040 | 63.6% |
| STORE_FAST | 12,160 | 20.3% |
| LOAD_FAST | 6,080 | 10.2% |
| STORE_NAME | 2,480 | 4.1% |
| LOAD_CONST | 560 | 0.9% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,986,519 | 45.1% |
| POP_TOP | 1,159,735 | 17.5% |
| POP_JUMP_IF_FALSE | 1,030,170 | 15.5% |
| RESUME_CHECK | 917,560 | 13.8% |
| POP_JUMP_IF_NOT_NONE | 318,513 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,930,846 | 59.3% |
| LOAD_GLOBAL_MODULE | 1,149,397 | 17.3% |
| LOAD_FAST_LOAD_FAST | 550,360 | 8.3% |
| LOAD_CONST | 529,060 | 8.0% |
| LOAD_GLOBAL_BUILTIN | 454,830 | 6.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 19,755 | 54.7% |
| COPY | 10,880 | 30.1% |
| POP_TOP | 5,200 | 14.4% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 19,355 | 53.6% |
| RERAISE | 10,880 | 30.1% |
| JUMP_FORWARD | 5,120 | 14.2% |
| JUMP_BACKWARD | 700 | 1.9% |
| RETURN_CONST | 60 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 33.8% |
| RETURN_CONST | 4,597,205 | 23.8% |
| CALL | 1,883,734 | 9.7% |
| BEFORE_WITH | 1,276,869 | 6.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,043,660 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,276,143 | 37.6% |
| LOAD_FAST | 5,132,540 | 26.6% |
| RETURN_CONST | 1,545,158 | 8.0% |
| LOAD_CONST | 1,517,320 | 7.9% |
| NOP | 1,159,735 | 6.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 25,155 | 69.6% |
| RERAISE | 5,440 | 15.1% |
| CALL_KW | 5,120 | 14.2% |
| BINARY_SUBSCR_DICT | 300 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,495 | 70.6% |
| WITH_EXCEPT_START | 5,440 | 15.1% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.1% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,720 | 46.3% |
| LOAD_ATTR | 1,211,711 | 26.7% |
| LOAD_ATTR_MODULE | 1,136,621 | 25.0% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,913,864 | 64.2% |
| LOAD_FAST_LOAD_FAST | 713,274 | 15.7% |
| CALL | 609,472 | 13.4% |
| LOAD_CONST | 237,536 | 5.2% |
| CALL_PY_EXACT_ARGS | 44,840 | 1.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 16,820 | 97.2% |
| COPY_FREE_VARS | 340 | 2.0% |
| CALL | 140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,440 | 31.4% |
| LOAD_FAST | 5,440 | 31.4% |
| STORE_FAST | 5,440 | 31.4% |
| CALL_METHOD_DESCRIPTOR_O | 660 | 3.8% |
| CALL | 320 | 1.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,790,800 | 51.7% |
| CALL | 1,926,660 | 11.3% |
| RETURN_VALUE | 1,214,475 | 7.1% |
| CALL_FUNCTION_EX | 1,196,044 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,021,930 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,438,863 | 55.5% |
| STORE_FAST | 1,457,061 | 8.6% |
| RETURN_VALUE | 1,214,475 | 7.1% |
| POP_TOP | 940,058 | 5.5% |
| LOAD_FAST_LOAD_FAST | 724,500 | 4.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 12,160 | 42.0% |
| LOAD_FAST | 10,440 | 36.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,480 | 18.9% |
| STORE_SUBSCR | 620 | 2.1% |
| LOAD_ATTR | 200 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 17,720 | 61.1% |
| LOAD_GLOBAL_MODULE | 10,200 | 35.2% |
| STORE_SUBSCR | 620 | 2.1% |
| STORE_SUBSCR_DICT | 260 | 0.9% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,355,693 | 95.9% |
| LOAD_ATTR_INSTANCE_VALUE | 49,984 | 3.5% |
| TO_BOOL | 3,442 | 0.2% |
| LOAD_ATTR | 888 | 0.1% |
| RETURN_VALUE | 766 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 719,591 | 50.9% |
| POP_JUMP_IF_FALSE | 687,414 | 48.6% |
| TO_BOOL | 3,442 | 0.2% |
| TO_BOOL_BOOL | 2,166 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 724,500 | 68.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 326,966 | 31.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,051,546 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 163,400 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 163,440 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 5,360 | 98.5% |
| TO_BOOL | 80 | 1.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,336,863 | 53.2% |
| UNARY_INVERT | 1,051,546 | 23.9% |
| POP_JUMP_IF_FALSE | 724,500 | 16.5% |
| LOAD_ATTR | 175,703 | 4.0% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,776,046 | 40.4% |
| STORE_FAST | 900,523 | 20.5% |
| TO_BOOL_INT | 724,560 | 16.5% |
| UNARY_INVERT | 724,500 | 16.5% |
| BUILD_TUPLE | 163,523 | 3.7% |


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
| SWAP | 324,079 | 33.4% |
| JUMP_FORWARD | 311,385 | 32.1% |
| LOAD_FAST | 163,869 | 16.9% |
| POP_TOP | 147,536 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 327,985 | 33.8% |
| SWAP | 324,079 | 33.4% |
| STORE_FAST | 312,205 | 32.2% |
| RETURN_VALUE | 5,120 | 0.5% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 528,600 | 57.6% |
| RESUME_CHECK | 321,585 | 35.1% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 3.6% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.8% |
| POP_TOP | 6,080 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,545 | 97.6% |
| STORE_FAST | 16,320 | 1.8% |
| BUILD_TUPLE | 6,100 | 0.7% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,560 | 68.6% |
| FORMAT_SIMPLE | 12,160 | 31.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 26,480 | 68.4% |
| RETURN_VALUE | 12,160 | 31.4% |
| BINARY_OP | 80 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,282,060 | 50.0% |
| LOAD_FAST_LOAD_FAST | 556,800 | 21.7% |
| RETURN_VALUE | 512,000 | 20.0% |
| BINARY_OP | 163,523 | 6.4% |
| LOAD_ATTR_INSTANCE_VALUE | 21,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 725,420 | 28.3% |
| YIELD_VALUE | 550,140 | 21.5% |
| STORE_FAST | 512,000 | 20.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 20.0% |
| CALL_LIST_APPEND | 163,443 | 6.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,278,244 | 25.9% |
| ENTER_EXECUTOR | 1,676,354 | 19.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,329,925 | 15.1% |
| LOAD_FAST_LOAD_FAST | 850,496 | 9.7% |
| BUILD_TUPLE | 725,420 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,061,069 | 23.5% |
| RETURN_VALUE | 1,926,660 | 21.9% |
| POP_TOP | 1,883,734 | 21.5% |
| LOAD_FAST | 769,454 | 8.8% |
| TO_BOOL_BOOL | 682,466 | 7.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,624 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,196,044 | 51.8% |
| RESUME_CHECK | 533,760 | 23.1% |
| CALL_BUILTIN_CLASS | 511,960 | 22.2% |
| POP_TOP | 60,480 | 2.6% |
| STORE_FAST | 5,440 | 0.2% |


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
| LOAD_CONST | 247,465 | 98.0% |
| ENTER_EXECUTOR | 5,124 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 189,376 | 75.0% |
| LOAD_FAST | 27,200 | 10.8% |
| RETURN_VALUE | 18,240 | 7.2% |
| STORE_FAST | 12,300 | 4.9% |
| PUSH_EXC_INFO | 5,120 | 2.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 363,152 | 98.8% |
| COMPARE_OP | 1,220 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,148 | 0.3% |
| LOAD_GLOBAL_MODULE | 378 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 364,257 | 99.1% |
| COMPARE_OP | 1,220 | 0.3% |
| COMPARE_OP_INT | 1,190 | 0.3% |
| COMPARE_OP_STR | 438 | 0.1% |
| POP_JUMP_IF_TRUE | 279 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,266,567 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,267,227 | 100.0% |
| POP_JUMP_IF_TRUE | 480 | 0.0% |
| STORE_FAST | 140 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 12,120 | 49.8% |
| CALL_BUILTIN_FAST | 12,120 | 49.8% |
| BINARY_SUBSCR | 40 | 0.2% |
| CALL | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 24,320 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,440 | 42.9% |
| BINARY_OP | 1,776,046 | 29.4% |
| LOAD_CONST | 1,067,520 | 17.6% |
| LOAD_FAST | 554,347 | 9.2% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 42.9% |
| TO_BOOL_INT | 1,775,726 | 29.4% |
| STORE_FAST_STORE_FAST | 1,061,440 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 542,047 | 9.0% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 724,500 | 65.0% |
| CALL_ALLOC_AND_ENTER_INIT | 311,345 | 27.9% |
| CACHE | 73,100 | 6.6% |
| CALL | 5,620 | 0.5% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,114,425 | 99.9% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,400 | 66.7% |
| RETURN_CONST | 26,560 | 32.5% |
| LOAD_GLOBAL_MODULE | 600 | 0.7% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 528,740 | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 5.8% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 561,380 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,276,143 | 72.3% |
| POP_JUMP_IF_NOT_NONE | 806,472 | 8.0% |
| STORE_FAST_STORE_FAST | 548,100 | 5.4% |
| FOR_ITER_LIST | 543,320 | 5.4% |
| LIST_APPEND | 535,373 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,971,280 | 59.4% |
| CALL | 1,676,354 | 16.7% |
| FOR_ITER_LIST | 1,333,184 | 13.3% |
| CALL_PY_WITH_DEFAULTS | 449,710 | 4.5% |
| LOAD_ATTR_PROPERTY | 426,293 | 4.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,240 | 36.6% |
| GET_ITER | 11,476 | 34.3% |
| LOAD_FAST | 5,740 | 17.1% |
| JUMP_BACKWARD | 3,104 | 9.3% |
| FOR_ITER | 920 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 18,840 | 56.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,360 | 33.9% |
| FOR_ITER | 920 | 2.7% |
| STORE_FAST | 760 | 2.3% |
| LOAD_GLOBAL_MODULE | 560 | 1.7% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 29,560 | 98.9% |
| STORE_NAME | 340 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,120 | 97.4% |
| STORE_NAME | 780 | 2.6% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 30,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 29,560 | 97.8% |
| STORE_NAME | 680 | 2.2% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 26,560 | 60.2% |
| LOAD_FAST | 16,460 | 37.3% |
| LOAD_GLOBAL_MODULE | 1,070 | 2.4% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 43,990 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,440,000 | 90.7% |
| POP_TOP | 550,361 | 9.2% |
| LIST_APPEND | 1,700 | 0.0% |
| POP_JUMP_IF_FALSE | 1,357 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 1,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,983,920 | 99.7% |
| FOR_ITER_LIST | 4,888 | 0.1% |
| FOR_ITER | 3,104 | 0.1% |
| FOR_ITER_RANGE | 2,179 | 0.0% |
| LOAD_FAST | 1,676 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 670,245 | 52.6% |
| POP_TOP | 586,212 | 46.0% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.4% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 902,317 | 70.9% |
| BUILD_LIST | 311,385 | 24.5% |
| LOAD_GLOBAL_MODULE | 22,580 | 1.8% |
| POP_EXCEPT | 19,755 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 275,390 | 51.3% |
| LOAD_ATTR | 163,543 | 30.5% |
| BINARY_SUBSCR_STR_INT | 97,240 | 18.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 535,373 | 99.7% |
| JUMP_BACKWARD | 1,700 | 0.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 148,316 | 50.1% |
| RETURN_VALUE | 147,536 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 147,856 | 50.0% |
| STORE_FAST | 147,536 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,947,871 | 73.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,551,412 | 23.1% |
| LOAD_GLOBAL_MODULE | 121,562 | 1.8% |
| CALL | 49,620 | 0.7% |
| LOAD_ATTR | 20,785 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,047,054 | 30.4% |
| PUSH_NULL | 1,211,711 | 18.0% |
| STORE_SUBSCR_DICT | 724,420 | 10.8% |
| POP_JUMP_IF_NOT_NONE | 679,246 | 10.1% |
| STORE_FAST | 485,239 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,258,097 | 26.6% |
| LOAD_FAST | 2,591,950 | 21.1% |
| POP_TOP | 1,517,320 | 12.4% |
| POP_JUMP_IF_FALSE | 789,518 | 6.4% |
| LOAD_ATTR_METHOD_NO_DICT | 683,279 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,258,097 | 26.6% |
| CALL | 2,278,244 | 18.6% |
| LOAD_FAST | 1,410,561 | 11.5% |
| COMPARE_OP_INT | 1,271,884 | 10.4% |
| COPY | 1,067,520 | 8.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,108,605 | 95.3% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.3% |
| STORE_DEREF | 26,560 | 2.3% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,109,125 | 95.3% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 4.6% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,654,934 | 23.3% |
| STORE_FAST | 8,575,570 | 12.0% |
| POP_JUMP_IF_FALSE | 5,569,913 | 7.8% |
| POP_TOP | 5,132,540 | 7.2% |
| NOP | 3,930,846 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,671,360 | 24.7% |
| RETURN_VALUE | 8,790,800 | 12.3% |
| LOAD_ATTR | 4,947,871 | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,811,489 | 6.7% |
| CALL_PY_EXACT_ARGS | 3,131,562 | 4.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 324,079 | 66.5% |
| LOAD_FAST_AND_CLEAR | 163,523 | 33.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 324,079 | 66.5% |
| LOAD_FAST_AND_CLEAR | 163,523 | 33.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 76.8% |
| POP_JUMP_IF_NONE | 147,862 | 20.9% |
| LOAD_ATTR_CLASS | 15,864 | 2.2% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 76.8% |
| LOAD_GLOBAL_MODULE | 147,782 | 20.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,824 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,652,676 | 18.9% |
| POP_JUMP_IF_FALSE | 933,951 | 10.7% |
| LOAD_FAST_LOAD_FAST | 791,400 | 9.1% |
| LOAD_SUPER_ATTR_METHOD | 736,860 | 8.4% |
| RETURN_VALUE | 724,500 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,167,323 | 24.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,080,426 | 12.4% |
| CALL | 850,496 | 9.7% |
| LOAD_FAST_LOAD_FAST | 791,400 | 9.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 724,420 | 8.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,714 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,820 | 38.2% |
| LOAD_ATTR | 3,327 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,744 | 15.4% |
| LOAD_FAST | 2,168 | 12.1% |
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
| MAKE_CELL | 106,240 | 79.8% |
| CALL_PY_EXACT_ARGS | 26,840 | 20.2% |
| CACHE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 106,240 | 79.8% |
| RESUME_CHECK | 26,860 | 20.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,383,470 | 24.9% |
| TO_BOOL_INT | 3,225,086 | 23.8% |
| COMPARE_OP_INT | 2,702,192 | 19.9% |
| COMPARE_OP_STR | 1,286,296 | 9.5% |
| CONTAINS_OP | 1,267,227 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,569,913 | 41.1% |
| RETURN_CONST | 2,383,594 | 17.6% |
| NOP | 1,030,170 | 7.6% |
| LOAD_GLOBAL_MODULE | 955,218 | 7.0% |
| LOAD_FAST_LOAD_FAST | 933,951 | 6.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 735,496 | 91.3% |
| LOAD_ATTR_INSTANCE_VALUE | 44,600 | 5.5% |
| LOAD_ATTR | 24,460 | 3.0% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,719 | 28.5% |
| LOAD_GLOBAL_MODULE | 197,818 | 24.6% |
| NOP | 184,496 | 22.9% |
| LOAD_FAST_CHECK | 147,862 | 18.4% |
| RETURN_CONST | 22,420 | 2.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,171,186 | 57.0% |
| LOAD_ATTR | 679,246 | 17.8% |
| LOAD_ATTR_INSTANCE_VALUE | 606,646 | 15.9% |
| RETURN_VALUE | 275,710 | 7.2% |
| LOAD_DEREF | 53,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,710,703 | 44.9% |
| ENTER_EXECUTOR | 806,472 | 21.2% |
| RETURN_CONST | 679,861 | 17.9% |
| NOP | 318,513 | 8.4% |
| LOAD_CONST | 147,816 | 3.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,502,132 | 66.7% |
| TO_BOOL | 719,591 | 31.9% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,547 | 0.5% |
| COMPARE_OP_INT | 1,929 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 908,819 | 40.3% |
| LOAD_FAST_LOAD_FAST | 720,463 | 32.0% |
| RETURN_CONST | 470,996 | 20.9% |
| LOAD_GLOBAL_MODULE | 57,655 | 2.6% |
| RETURN_VALUE | 46,315 | 2.1% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,440 | 99.6% |
| CALL_KW | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,440 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 10,880 | 66.7% |
| POP_JUMP_IF_TRUE | 5,440 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,440 | 50.0% |
| COPY | 5,440 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,383,594 | 35.8% |
| POP_TOP | 1,545,158 | 23.2% |
| STORE_ATTR_INSTANCE_VALUE | 1,447,100 | 21.7% |
| POP_JUMP_IF_NOT_NONE | 679,861 | 10.2% |
| POP_JUMP_IF_TRUE | 470,996 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,597,205 | 69.0% |
| EXIT_INIT_CHECK | 687,790 | 10.3% |
| INTERPRETER_EXIT | 649,025 | 9.7% |
| TO_BOOL_BOOL | 640,492 | 9.6% |
| STORE_FAST | 47,515 | 0.7% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 38,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,960 | 97.2% |
| STORE_NAME | 780 | 2.1% |
| LOAD_GLOBAL_MODULE | 280 | 0.7% |
| LOAD_FAST | 20 | 0.1% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,323 | 59.1% |
| LOAD_FAST_LOAD_FAST | 19,800 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,320 | 17.1% |
| STORE_ATTR | 2,360 | 2.5% |
| LOAD_ATTR | 240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,920 | 45.1% |
| LOAD_FAST | 12,980 | 13.6% |
| LOAD_FAST_LOAD_FAST | 12,840 | 13.5% |
| LOAD_CONST | 12,002 | 12.6% |
| LOAD_GLOBAL_BUILTIN | 5,360 | 5.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 53,120 | 40.0% |
| LOAD_GLOBAL_MODULE | 53,120 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 26,560 | 20.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 53,040 | 39.9% |
| LOAD_DEREF | 26,560 | 20.0% |
| LOAD_FAST | 26,560 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 26,520 | 20.0% |
| LOAD_GLOBAL | 120 | 0.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,983,920 | 27.1% |
| COPY | 2,597,760 | 11.8% |
| CALL | 2,061,069 | 9.3% |
| RETURN_VALUE | 1,457,061 | 6.6% |
| STORE_FAST_STORE_FAST | 1,056,280 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,575,570 | 38.9% |
| JUMP_BACKWARD | 5,440,000 | 24.7% |
| NOP | 2,986,519 | 13.5% |
| COPY | 2,597,440 | 11.8% |
| JUMP_FORWARD | 670,245 | 3.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,840 | 48.9% |
| COPY | 12,160 | 31.5% |
| FOR_ITER_LIST | 6,700 | 17.4% |
| FOR_ITER_TUPLE | 860 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,720 | 33.0% |
| STORE_ATTR_INSTANCE_VALUE | 12,080 | 31.3% |
| YIELD_VALUE | 6,680 | 17.3% |
| GET_ITER | 6,080 | 15.8% |
| TO_BOOL_STR | 860 | 2.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,166,764 | 30.7% |
| COPY | 1,061,440 | 28.0% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 27.8% |
| STORE_FAST_STORE_FAST | 512,000 | 13.5% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,383,326 | 36.4% |
| STORE_FAST | 1,056,280 | 27.8% |
| ENTER_EXECUTOR | 548,100 | 14.4% |
| STORE_FAST_STORE_FAST | 512,000 | 13.5% |
| LOAD_FAST_LOAD_FAST | 282,798 | 7.4% |


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
| BINARY_OP_ADD_INT | 542,107 | 29.3% |
| BUILD_LIST | 324,079 | 17.5% |
| LOAD_FAST_AND_CLEAR | 324,079 | 17.5% |
| FOR_ITER_LIST | 311,059 | 16.8% |
| LOAD_FAST | 174,702 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 542,047 | 29.3% |
| LOAD_CONST | 338,225 | 18.3% |
| BUILD_LIST | 324,079 | 17.5% |
| STORE_FAST | 324,079 | 17.5% |
| FOR_ITER_LIST | 310,979 | 16.8% |


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
| ENTER_EXECUTOR | 5,971,280 | 91.5% |
| BUILD_TUPLE | 550,140 | 8.4% |
| STORE_FAST_LOAD_FAST | 6,680 | 0.1% |
| CALL_STR_1 | 620 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,983,920 | 91.7% |
| INTERPRETER_EXIT | 545,100 | 8.3% |


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
| LOAD_FAST | 163,769 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 163,809 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,059,647 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 542,107 | 50.3% |
| STORE_FAST | 511,980 | 47.6% |
| BINARY_SLICE | 16,920 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,360 | 0.5% |
| LOAD_CONST | 280 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 28.0% |
| LOAD_FAST_LOAD_FAST | 600 | 28.0% |
| CALL_METHOD_DESCRIPTOR_O | 600 | 28.0% |
| BINARY_SUBSCR_LIST_INT | 280 | 13.1% |
| BINARY_OP | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,100 | 51.4% |
| LOAD_CONST | 620 | 29.0% |
| STORE_FAST | 300 | 14.0% |
| CALL | 120 | 5.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,200 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 97,200 | 100.0% |
| CALL | 40 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 147,782 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 147,942 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,934 | 75.9% |
| LOAD_CONST | 46,235 | 21.5% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,329 | 97.5% |
| CALL_BUILTIN_CLASS | 5,360 | 2.5% |
| CALL | 40 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 96,020 | 88.0% |
| LOAD_CONST | 12,360 | 11.3% |
| LOAD_FAST | 700 | 0.6% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 96,020 | 88.0% |
| CONVERT_VALUE | 12,120 | 11.1% |
| STORE_FAST | 400 | 0.4% |
| PUSH_EXC_INFO | 300 | 0.3% |
| LOAD_FAST | 140 | 0.1% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,000 | 63.1% |
| LOAD_FAST_LOAD_FAST | 6,320 | 36.2% |
| BINARY_SUBSCR | 120 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,800 | 61.9% |
| STORE_FAST | 6,360 | 36.5% |
| BINARY_OP_ADD_UNICODE | 280 | 1.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 97,200 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 97,240 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 35,280 | 99.9% |
| BINARY_SUBSCR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 29,500 | 83.5% |
| JUMP_FORWARD | 5,400 | 15.3% |
| STORE_FAST | 420 | 1.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 337,825 | 49.1% |
| LOAD_FAST | 317,405 | 46.1% |
| CALL | 32,140 | 4.7% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 376,445 | 54.7% |
| COPY_FREE_VARS | 311,345 | 45.3% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 71.9% |
| LOAD_CONST | 6,360 | 14.2% |
| BINARY_OP_ADD_INT | 5,360 | 11.9% |
| PUSH_NULL | 646 | 1.4% |
| CALL | 158 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,804 | 86.5% |
| POP_TOP | 5,960 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 43.3% |
| RETURN_VALUE | 449,010 | 38.0% |
| LOAD_FAST | 180,269 | 15.2% |
| LOAD_CONST | 12,360 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 10,260 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 675,789 | 57.2% |
| STORE_FAST | 449,310 | 38.0% |
| GET_ITER | 34,980 | 3.0% |
| LOAD_FAST | 16,320 | 1.4% |
| CALL_BUILTIN_CLASS | 6,000 | 0.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 544,820 | 52.0% |
| LOAD_CONST | 298,696 | 28.5% |
| LOAD_FAST_LOAD_FAST | 107,134 | 10.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,227 | 4.6% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 365,197 | 34.8% |
| TO_BOOL_BOOL | 290,876 | 27.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 276,678 | 26.4% |
| UNPACK_SEQUENCE_TUPLE | 48,227 | 4.6% |
| POP_TOP | 12,719 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,460 | 47.1% |
| BUILD_TUPLE | 511,960 | 46.8% |
| CALL | 32,623 | 3.0% |
| LOAD_FAST_CHECK | 15,824 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,043,660 | 95.4% |
| RETURN_VALUE | 49,127 | 4.5% |
| LOAD_FAST | 620 | 0.1% |
| STORE_FAST | 440 | 0.0% |
| BEFORE_WITH | 140 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 97,200 | 71.4% |
| LOAD_ATTR | 26,480 | 19.4% |
| LOAD_FAST | 12,360 | 9.1% |
| CALL | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 97,200 | 71.4% |
| LOAD_FAST | 38,640 | 28.4% |
| STORE_FAST | 140 | 0.1% |
| TO_BOOL_INT | 140 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 741,000 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 741,280 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,494 | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 10.4% |
| CALL | 384 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,814 | 80.6% |
| CALL_PY_EXACT_ARGS | 31,880 | 12.4% |
| CALL_BUILTIN_CLASS | 6,000 | 2.3% |
| LOAD_FAST | 5,400 | 2.1% |
| BINARY_OP_SUBTRACT_INT | 5,360 | 2.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 163,443 | 93.5% |
| LOAD_FAST | 10,800 | 6.2% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 162,843 | 93.2% |
| LOAD_GLOBAL_MODULE | 10,800 | 6.2% |
| JUMP_BACKWARD | 640 | 0.4% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,865 | 99.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 535 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 724,780 | 69.8% |
| STORE_FAST | 312,180 | 30.1% |
| LIST_APPEND | 860 | 0.1% |
| TO_BOOL_NONE | 600 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,560 | 85.1% |
| BUILD_TUPLE | 5,360 | 14.4% |
| CALL | 180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 26,260 | 70.8% |
| LOAD_FAST | 10,840 | 29.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,104,434 | 94.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 64,051 | 5.5% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 46.5% |
| POP_TOP | 437,695 | 37.4% |
| LOAD_FAST | 50,180 | 4.3% |
| RETURN_VALUE | 48,688 | 4.2% |
| CALL_BUILTIN_FAST | 48,227 | 4.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 759,331 | 91.4% |
| LOAD_CONST | 30,200 | 3.6% |
| CALL | 27,540 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 787,011 | 94.7% |
| LOAD_CONST | 29,920 | 3.6% |
| RETURN_VALUE | 12,980 | 1.6% |
| BINARY_OP_ADD_UNICODE | 600 | 0.1% |
| STORE_FAST | 280 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,786,336 | 46.9% |
| LOAD_FAST | 3,131,562 | 38.8% |
| LOAD_FAST_LOAD_FAST | 562,280 | 7.0% |
| LOAD_SUPER_ATTR_METHOD | 311,305 | 3.9% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,036,675 | 99.5% |
| MAKE_CELL | 26,840 | 0.3% |
| RETURN_GENERATOR | 16,820 | 0.2% |
| COPY_FREE_VARS | 320 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 931,446 | 45.8% |
| ENTER_EXECUTOR | 449,710 | 22.1% |
| LOAD_ATTR_MODULE | 311,505 | 15.3% |
| LOAD_FAST | 212,563 | 10.4% |
| LOAD_CONST | 73,569 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,309,936 | 64.4% |
| COPY_FREE_VARS | 724,500 | 35.6% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,220 | 99.6% |
| CALL | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,220 | 90.8% |
| YIELD_VALUE | 620 | 5.5% |
| STORE_FAST | 280 | 2.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 140 | 1.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 549,420 | 99.9% |
| LOAD_FAST | 600 | 0.1% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 549,400 | 99.9% |
| LOAD_FAST | 620 | 0.1% |
| CALL | 140 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 75.0% |
| LOAD_GLOBAL_MODULE | 140 | 17.5% |
| CALL | 60 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 620 | 77.5% |
| PUSH_NULL | 140 | 17.5% |
| LOAD_GLOBAL | 40 | 5.0% |


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
| LOAD_CONST | 1,271,884 | 47.0% |
| LOAD_ATTR_INSTANCE_VALUE | 850,065 | 31.4% |
| LOAD_FAST | 544,980 | 20.2% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.6% |
| CALL_BUILTIN_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,702,192 | 99.9% |
| POP_JUMP_IF_TRUE | 1,929 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 107 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,262,005 | 95.5% |
| LOAD_CONST | 53,140 | 4.0% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 438 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,286,296 | 97.4% |
| COPY | 12,120 | 0.9% |
| LOAD_FAST | 12,120 | 0.9% |
| POP_JUMP_IF_TRUE | 10,547 | 0.8% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,983,920 | 99.8% |
| GET_ITER | 10,800 | 0.2% |
| FOR_ITER | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,983,920 | 99.8% |
| POP_TOP | 10,800 | 0.2% |
| RESUME | 80 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,333,184 | 58.3% |
| GET_ITER | 635,770 | 27.8% |
| SWAP | 310,979 | 13.6% |
| JUMP_BACKWARD | 4,888 | 0.2% |
| FOR_ITER | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 622,770 | 27.3% |
| ENTER_EXECUTOR | 543,320 | 23.8% |
| STORE_FAST | 466,786 | 20.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 327,026 | 14.3% |
| SWAP | 311,059 | 13.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 157,376 | 83.4% |
| GET_ITER | 29,024 | 15.4% |
| JUMP_BACKWARD | 2,179 | 1.2% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 147,696 | 78.2% |
| STORE_FAST | 30,523 | 16.2% |
| RETURN_CONST | 10,560 | 5.6% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,140 | 47.9% |
| GET_ITER | 11,100 | 43.8% |
| SWAP | 860 | 3.4% |
| LOAD_FAST | 620 | 2.4% |
| JUMP_BACKWARD | 600 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,860 | 46.8% |
| LOAD_FAST | 10,460 | 41.2% |
| RETURN_CONST | 1,280 | 5.0% |
| STORE_FAST_LOAD_FAST | 860 | 3.4% |
| SWAP | 860 | 3.4% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 48,187 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.4% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,603 | 72.9% |
| LOAD_FAST_CHECK | 15,864 | 27.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,671,360 | 91.4% |
| LOAD_FAST_LOAD_FAST | 1,080,426 | 5.6% |
| COPY | 542,047 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 21,229 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,530,186 | 23.4% |
| LOAD_FAST | 2,935,745 | 15.2% |
| LOAD_ATTR | 1,551,412 | 8.0% |
| LOAD_GLOBAL_MODULE | 1,289,115 | 6.7% |
| CONTAINS_OP | 1,266,567 | 6.6% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,468 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,574 | 39.8% |
| CALL | 82,023 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,051 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,530,186 | 88.3% |
| LOAD_FAST | 472,828 | 9.2% |
| LOAD_ATTR | 51,040 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,779,177 | 34.7% |
| CALL | 1,329,925 | 25.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,104,434 | 21.5% |
| LOAD_CONST | 683,279 | 13.3% |
| LOAD_FAST_LOAD_FAST | 204,619 | 4.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,811,489 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,094,579 | 15.2% |
| LOAD_FAST_LOAD_FAST | 724,420 | 10.0% |
| BINARY_SUBSCR | 543,920 | 7.5% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,786,336 | 52.4% |
| LOAD_FAST | 1,731,278 | 24.0% |
| CALL_PY_WITH_DEFAULTS | 931,446 | 12.9% |
| LOAD_FAST_LOAD_FAST | 610,720 | 8.5% |
| LOAD_CONST | 90,449 | 1.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,590,663 | 99.8% |
| LOAD_ATTR | 2,822 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,136,621 | 71.3% |
| CALL_PY_WITH_DEFAULTS | 311,505 | 19.5% |
| STORE_DEREF | 53,120 | 3.3% |
| LOAD_CONST | 31,040 | 1.9% |
| LOAD_FAST | 27,840 | 1.7% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 759,900 | 69.9% |
| LOAD_FAST_LOAD_FAST | 326,886 | 30.1% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 724,460 | 66.6% |
| UNARY_INVERT | 326,966 | 30.1% |
| RETURN_VALUE | 12,120 | 1.1% |
| LOAD_CONST | 12,120 | 1.1% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 426,293 | 64.1% |
| LOAD_FAST | 210,978 | 31.7% |
| RETURN_VALUE | 26,480 | 4.0% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 652,511 | 98.1% |
| TO_BOOL_BOOL | 12,160 | 1.8% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,200 | 97.8% |
| LOAD_ATTR_MODULE | 1,180 | 1.9% |
| RETURN_VALUE | 140 | 0.2% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 49,520 | 77.9% |
| CALL_BUILTIN_FAST | 12,220 | 19.2% |
| LOAD_FAST | 1,040 | 1.6% |
| LOAD_CONST | 600 | 0.9% |
| STORE_FAST | 140 | 0.2% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,451,305 | 49.0% |
| LOAD_FAST | 764,440 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.5% |
| STORE_FAST | 470,919 | 9.4% |
| NOP | 454,830 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,492,913 | 49.8% |
| LOAD_DEREF | 1,108,605 | 22.2% |
| CALL_ISINSTANCE | 741,000 | 14.8% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.5% |
| LOAD_GLOBAL_MODULE | 43,000 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,620,035 | 24.6% |
| RESUME_CHECK | 1,927,633 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,289,115 | 12.1% |
| NOP | 1,149,397 | 10.8% |
| POP_JUMP_IF_FALSE | 955,218 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,336,863 | 22.0% |
| LOAD_FAST_LOAD_FAST | 1,652,676 | 15.5% |
| LOAD_ATTR_MODULE | 1,590,663 | 15.0% |
| LOAD_FAST | 1,408,454 | 13.2% |
| COMPARE_OP_STR | 1,262,005 | 11.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,880 | 99.9% |
| LOAD_SUPER_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 54,960 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,053,445 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 736,860 | 69.9% |
| CALL_PY_EXACT_ARGS | 311,305 | 29.5% |
| LOAD_FAST | 5,440 | 0.5% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,556,548 | 36.2% |
| CALL_PY_EXACT_ARGS | 8,036,675 | 27.5% |
| FOR_ITER_GEN | 5,983,920 | 20.5% |
| CALL_PY_WITH_DEFAULTS | 1,309,936 | 4.5% |
| COPY_FREE_VARS | 1,114,425 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,654,934 | 57.1% |
| POP_TOP | 6,528,880 | 22.4% |
| LOAD_GLOBAL_BUILTIN | 2,451,305 | 8.4% |
| LOAD_GLOBAL_MODULE | 1,927,633 | 6.6% |
| NOP | 917,560 | 3.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,266,697 | 66.6% |
| LOAD_FAST_LOAD_FAST | 557,405 | 16.4% |
| SWAP | 542,047 | 15.9% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,447,100 | 42.5% |
| LOAD_FAST | 880,527 | 25.9% |
| LOAD_GLOBAL_MODULE | 537,445 | 15.8% |
| LOAD_CONST | 289,418 | 8.5% |
| LOAD_FAST_LOAD_FAST | 121,160 | 3.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,520 | 80.1% |
| LOAD_FAST_LOAD_FAST | 12,220 | 19.8% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,820 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 724,420 | 89.5% |
| LOAD_FAST | 41,088 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.0% |
| CALL | 10,200 | 1.3% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 726,848 | 89.8% |
| RETURN_CONST | 29,000 | 3.6% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.3% |
| LOAD_CONST | 26,520 | 3.3% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,145,464 | 22.7% |
| CALL_ISINSTANCE | 741,280 | 14.7% |
| CALL | 682,466 | 13.5% |
| LOAD_FAST | 668,315 | 13.2% |
| RETURN_CONST | 640,492 | 12.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,383,470 | 67.0% |
| POP_JUMP_IF_TRUE | 1,502,132 | 29.8% |
| UNARY_NOT | 163,400 | 3.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,775,726 | 55.1% |
| BINARY_OP | 724,560 | 22.5% |
| LOAD_FAST | 724,420 | 22.5% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,225,086 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 322,165 | 89.1% |
| LOAD_ATTR_INSTANCE_VALUE | 39,240 | 10.9% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 361,465 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 179,989 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,749 | 92.2% |
| POP_JUMP_IF_TRUE | 17,460 | 7.8% |


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
| LOAD_FAST | 1,055,880 | 95.6% |
| CALL_BUILTIN_FAST | 48,227 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,267 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_CHECK | 543,920 | 46.4% |
| FOR_ITER_LIST | 327,026 | 27.9% |
| CALL_BUILTIN_FAST | 276,678 | 23.6% |
| FOR_ITER | 11,360 | 1.0% |
| CALL | 7,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,166,764 | 99.5% |
| LOAD_FAST | 6,040 | 0.5% |
| STORE_DEREF | 20 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 65.3% |
| COPY | 109 | 25.4% |
| TO_BOOL | 40 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 69.9% |
| POP_JUMP_IF_FALSE | 129 | 30.1% |


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
|     deferred | 4,389,441 | 71.7% |
|          hit | 1,729,067 | 28.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 9.5% |
| Failure | 5,689 | 90.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,814 | 49.5% |
| or | 1,475 | 25.9% |
| remainder | 720 | 12.7% |
| add different types | 600 | 10.5% |
| add other | 80 | 1.4% |


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
|     deferred | 590,555 | 69.4% |
|          hit | 259,120 | 30.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 22.2% |
| Failure | 841 | 77.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 841 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,742,947 | 31.3% |
|          hit | 19,153,189 | 68.5% |
|         miss | 7,520 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,289 | 24.9% |
| Failure | 27,987 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,286 | 26.0% |
| cfunc noargs | 5,803 | 20.7% |
| class no vectorcall | 3,780 | 13.5% |
| meth descr varargs keywords | 3,063 | 10.9% |
| class mutable | 1,137 | 4.1% |
| other | 1,100 | 3.9% |
| bound method | 1,041 | 3.7% |
| cfunc varargs | 1,020 | 3.6% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 797 | 2.8% |
| operator wrapper | 720 | 2.6% |
| cmethod | 640 | 2.3% |
| wrong number arguments | 440 | 1.6% |
| method wrapper | 260 | 0.9% |
| meth descr varargs | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 364,509 | 8.3% |
|          hit | 4,018,595 | 91.5% |
|         miss | 7,156 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,628 | 55.1% |
| Failure | 1,327 | 44.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 763 | 57.5% |
| big int | 340 | 25.6% |
| different types | 224 | 16.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,940 | 0.4% |
|          hit | 8,494,120 | 99.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 40.3% |
| Failure | 920 | 59.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| itertools | 260 | 28.3% |
| other | 220 | 23.9% |
| enumerate | 220 | 23.9% |
| callable | 220 | 23.9% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,686,182 | 15.9% |
|          hit | 35,087,381 | 83.3% |
|         miss | 309,214 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,436 | 54.8% |
| Failure | 18,539 | 45.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,319 | 23.3% |
| shadowed | 3,924 | 21.2% |
| not managed dict | 3,293 | 17.8% |
| non overriding descriptor | 1,984 | 10.7% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.1% |
| metaclass attribute | 900 | 4.9% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 439 | 2.4% |
| mutable class | 260 | 1.4% |
| overridden | 60 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,384 | 0.1% |
|        deopt | 100 | 0.0% |
|          hit | 15,633,338 | 99.9% |
|         miss | 2,432 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,574 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,108,605 | 100.0% |

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
|     deferred | 83,922 | 2.4% |
|          hit | 3,219,770 | 90.4% |
|         miss | 245,260 | 6.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,981 | 79.2% |
| Failure | 2,360 | 20.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 1,080 | 45.8% |
| not in keys | 520 | 22.0% |
| class attr simple | 520 | 22.0% |
| no dict | 240 | 10.2% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 28,100 | 3.4% |
|          hit | 809,328 | 96.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 29.5% |
| Failure | 620 | 70.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 420 | 67.7% |
| other | 200 | 32.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,407,045 | 13.7% |
|          hit | 8,862,871 | 86.2% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,006 | 46.6% |
| Failure | 3,442 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,001 | 29.1% |
| sequence | 841 | 24.4% |
| set | 700 | 20.3% |
| tuple | 700 | 20.3% |
| other | 200 | 5.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 2,277,311 | 100.0% |

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
| Basic | 233,674,653 | 57.4% |
| Not specialized | 42,925,158 | 10.5% |
| Specialized hits | 129,778,090 | 31.9% |
| Specialized misses | 571,865 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,742,947 | 39.1% |
| LOAD_ATTR | 6,686,182 | 29.9% |
| BINARY_OP | 4,389,441 | 19.7% |
| TO_BOOL | 1,407,045 | 6.3% |
| BINARY_SUBSCR | 590,555 | 2.6% |
| COMPARE_OP | 364,509 | 1.6% |
| STORE_ATTR | 83,922 | 0.4% |
| FOR_ITER | 31,940 | 0.1% |
| STORE_SUBSCR | 28,100 | 0.1% |
| LOAD_GLOBAL | 8,384 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.9% |
| LOAD_ATTR_INSTANCE_VALUE | 213,790 | 37.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 81,944 | 14.3% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.2% |
| COMPARE_OP_INT | 7,136 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,092 | 0.4% |
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
| Calls to PyEval_EvalDefault | 10,638,448 | 36.4% |
| Calls to Python functions inlined | 18,575,514 | 63.6% |
| Calls via PyEval_EvalFrame (total) | 10,638,448 | 36.4% |
| Calls via PyEval_EvalFrame (vector) | 10,086,928 | 34.5% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 1.9% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 10,086,228 | 34.5% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.8% |
| Calls via PyEval_EvalFrame (api) | 438,850 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 36,251 | 0.1% |
| Frames pushed | 12,564,931 | 43.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,632,019 | 40.9% |
| Frees to freelist | 14,644,079 |  |
| Allocations | 21,099,666 | 59.1% |
| Allocations to 512 bytes | 20,916,563 | 58.5% |
| Allocations to 4 kbytes | 83,589 | 0.2% |
| Allocations over 4 kbytes | 99,514 | 0.3% |
| Frees | 22,020,713 |  |
| New values | 80,340 |  |
| Interpreter increfs | 182,590,445 | 78.7% |
| Interpreter decrefs | 198,404,365 | 75.0% |
| Increfs | 49,551,676 | 21.3% |
| Decrefs | 66,238,398 | 25.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 8,078,642 |  |
| Method cache misses | 34,250 |  |
| Method cache collisions | 70,416 |  |
| Method cache dunder hits | 9,202,656 |  |
| Method cache dunder misses | 39,925 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 26 | 390 | 191,692 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,200 |  |
| Traces created | 800 | 19.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 3,400 | 81.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 10,059,741 |  |
| Uops executed | 85,159,492 | 8.47 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 141 | 17.6% |
| <= 32 | 420 | 52.5% |
| <= 64 | 80 | 10.0% |
| <= 128 | 139 | 17.4% |
| <= 256 | 20 | 2.5% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 80 | 10.0% |
| <= 8 | 61 | 7.6% |
| <= 16 | 340 | 42.5% |
| <= 32 | 140 | 17.5% |
| <= 64 | 59 | 7.4% |
| <= 128 | 120 | 15.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,357,393 | 13.5% |
| <= 4 | 1,194,891 | 11.9% |
| <= 8 | 4,895,900 | 48.7% |
| <= 16 | 1,460,601 | 14.5% |
| <= 32 | 972,066 | 9.7% |
| <= 64 | 5,541 | 0.1% |
| <= 128 | 173,314 | 1.7% |
| <= 256 | 2 | 0.0% |
| <= 512 | 3 | 0.0% |
| <= 1,024 | 3 | 0.0% |
| <= 2,048 | 7 | 0.0% |
| <= 4,096 | 5 | 0.0% |
| <= 8,192 | 15 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 14,582,926 | 17.1% | 17.1% |  |
| _EXIT_TRACE | 8,528,941 | 10.0% | 27.1% |  |
| STORE_FAST | 8,435,519 | 9.9% | 37.0% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 7,332,810 | 8.6% | 45.7% | 18.2% |
| _ITER_CHECK_LIST | 7,332,810 | 8.6% | 54.3% |  |
| _ITER_NEXT_LIST | 5,999,626 | 7.0% | 61.3% |  |
| _SET_IP | 5,837,937 | 6.9% | 68.2% |  |
| _CHECK_VALIDITY | 5,366,596 | 6.3% | 74.5% |  |
| _GUARD_GLOBALS_VERSION | 2,220,893 | 2.6% | 77.1% |  |
| PUSH_NULL | 1,783,059 | 2.1% | 79.2% |  |
| _FOR_ITER_TIER_TWO | 1,188,440 | 1.4% | 80.6% | 2.4% |
| _GUARD_BUILTINS_VERSION | 1,114,944 | 1.3% | 81.9% |  |
| _LOAD_GLOBAL_BUILTINS | 1,114,944 | 1.3% | 83.2% |  |
| _LOAD_GLOBAL_MODULE | 1,105,949 | 1.3% | 84.5% |  |
| BUILD_TUPLE | 1,081,040 | 1.3% | 85.8% |  |
| _CHECK_ATTR_MODULE | 956,854 | 1.1% | 86.9% |  |
| _LOAD_ATTR_MODULE | 956,854 | 1.1% | 88.0% |  |
| GET_ITER | 679,416 | 0.8% | 88.8% |  |
| _GUARD_TYPE_VERSION | 584,412 | 0.7% | 89.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 538,380 | 0.6% | 90.1% |  |
| BUILD_MAP | 537,920 | 0.6% | 90.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 518,863 | 0.6% | 91.4% |  |
| _GUARD_KEYS_VERSION | 518,863 | 0.6% | 92.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 518,863 | 0.6% | 92.6% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 460,848 | 0.5% | 93.1% | 34.1% |
| _ITER_CHECK_RANGE | 460,848 | 0.5% | 93.7% |  |
| LOAD_CONST | 426,937 | 0.5% | 94.2% |  |
| _CHECK_PEP_523 | 383,785 | 0.5% | 94.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 383,785 | 0.5% | 95.1% |  |
| _CHECK_STACK_SPACE | 383,785 | 0.5% | 95.5% |  |
| _INIT_CALL_PY_EXACT_ARGS | 383,785 | 0.5% | 96.0% |  |
| _PUSH_FRAME | 383,785 | 0.5% | 96.4% |  |
| _SAVE_RETURN_OFFSET | 383,785 | 0.5% | 96.9% |  |
| RESUME_CHECK | 383,745 | 0.5% | 97.3% |  |
| _LOAD_ATTR | 314,912 | 0.4% | 97.7% |  |
| _ITER_NEXT_RANGE | 303,472 | 0.4% | 98.0% |  |
| BINARY_SUBSCR_LIST_INT | 288,672 | 0.3% | 98.4% |  |
| CALL_BUILTIN_CLASS | 282,912 | 0.3% | 98.7% |  |
| TO_BOOL_BOOL | 179,155 | 0.2% | 98.9% |  |
| _GUARD_IS_TRUE_POP | 172,358 | 0.2% | 99.1% | 0.0% |
| CALL_BUILTIN_FAST | 147,216 | 0.2% | 99.3% |  |
| CALL_LEN | 141,456 | 0.2% | 99.5% |  |
| POP_TOP | 81,127 | 0.1% | 99.6% |  |
| _POP_FRAME | 63,779 | 0.1% | 99.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 53,906 | 0.1% | 99.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 53,906 | 0.1% | 99.8% |  |
| _GUARD_IS_NOT_NONE_POP | 31,980 | 0.0% | 99.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 22,984 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 13,800 | 0.0% | 99.9% | 88.0% |
| _ITER_CHECK_TUPLE | 13,800 | 0.0% | 99.9% |  |
| _GUARD_IS_FALSE_POP | 10,009 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 9,810 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,440 | 0.0% | 100.0% |  |
| BEFORE_WITH | 5,115 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,973 | 0.0% | 100.0% |  |
| CONTAINS_OP | 1,833 | 0.0% | 100.0% |  |
| COPY | 1,833 | 0.0% | 100.0% |  |
| SWAP | 1,833 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,833 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 1,833 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 1,833 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 1,833 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 1,833 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,660 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 280 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 140 | 0.0% | 100.0% |  |
| IS_OP | 99 | 0.0% | 100.0% |  |
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
| FOR_ITER_GEN | 3,420 |
| CALL | 220 |
| YIELD_VALUE | 140 |
| LOAD_ATTR_PROPERTY | 120 |
| CALL_PY_WITH_DEFAULTS | 80 |
| CALL_KW | 41 |
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
Stats gathered on: 2023-11-18
