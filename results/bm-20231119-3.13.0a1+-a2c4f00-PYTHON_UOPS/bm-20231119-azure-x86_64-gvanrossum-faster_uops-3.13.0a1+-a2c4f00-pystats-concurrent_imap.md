
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 70,864,900 | 17.6% | 17.6% |  |
| RESUME_CHECK | 28,964,637 | 7.2% | 24.8% | 0.0% |
| STORE_FAST | 21,916,825 | 5.4% | 30.2% |  |
| POP_TOP | 19,199,951 | 4.8% | 35.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,183,361 | 4.8% | 39.7% | 1.1% |
| RETURN_VALUE | 16,841,886 | 4.2% | 43.9% |  |
| POP_JUMP_IF_FALSE | 13,388,155 | 3.3% | 47.2% |  |
| LOAD_CONST | 12,203,938 | 3.0% | 50.2% |  |
| INTERPRETER_EXIT | 10,596,444 | 2.6% | 52.9% |  |
| LOAD_GLOBAL_MODULE | 10,471,198 | 2.6% | 55.5% | 0.0% |
| ENTER_EXECUTOR | 10,019,552 | 2.5% | 58.0% |  |
| CALL | 8,722,601 | 2.2% | 60.1% |  |
| LOAD_FAST_LOAD_FAST | 8,605,494 | 2.1% | 62.3% |  |
| CALL_PY_EXACT_ARGS | 7,950,509 | 2.0% | 64.2% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,122,355 | 1.8% | 66.0% | 1.2% |
| LOAD_ATTR | 6,627,616 | 1.6% | 67.6% |  |
| RETURN_CONST | 6,582,072 | 1.6% | 69.3% |  |
| NOP | 6,548,503 | 1.6% | 70.9% |  |
| YIELD_VALUE | 6,529,020 | 1.6% | 72.5% |  |
| COPY | 6,009,738 | 1.5% | 74.0% |  |
| JUMP_BACKWARD | 5,999,360 | 1.5% | 75.5% |  |
| FOR_ITER_GEN | 5,994,800 | 1.5% | 77.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,094,804 | 1.3% | 78.2% |  |
| TO_BOOL_BOOL | 4,996,111 | 1.2% | 79.5% |  |
| LOAD_GLOBAL_BUILTIN | 4,928,089 | 1.2% | 80.7% | 0.0% |
| PUSH_NULL | 4,524,959 | 1.1% | 81.8% |  |
| BINARY_OP | 4,299,308 | 1.1% | 82.9% |  |
| STORE_FAST_STORE_FAST | 3,783,492 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,767,114 | 0.9% | 84.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,370,363 | 0.8% | 85.6% | 7.3% |
| TO_BOOL_INT | 3,152,070 | 0.8% | 86.4% |  |
| COMPARE_OP_INT | 2,679,999 | 0.7% | 87.0% | 0.3% |
| BUILD_TUPLE | 2,544,694 | 0.6% | 87.7% |  |
| CALL_FUNCTION_EX | 2,308,022 | 0.6% | 88.3% |  |
| FOR_ITER_LIST | 2,248,812 | 0.6% | 88.8% |  |
| POP_JUMP_IF_TRUE | 2,243,500 | 0.6% | 89.4% |  |
| CALL_PY_WITH_DEFAULTS | 2,008,126 | 0.5% | 89.9% |  |
| SWAP | 1,826,829 | 0.5% | 90.3% |  |
| BEFORE_WITH | 1,587,259 | 0.4% | 90.7% |  |
| LOAD_ATTR_MODULE | 1,574,008 | 0.4% | 91.1% | 0.1% |
| TO_BOOL | 1,410,156 | 0.3% | 91.4% |  |
| COMPARE_OP_STR | 1,317,765 | 0.3% | 91.8% |  |
| JUMP_FORWARD | 1,259,776 | 0.3% | 92.1% |  |
| CONTAINS_OP | 1,251,435 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 1,169,171 | 0.3% | 92.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,162,663 | 0.3% | 93.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,159,532 | 0.3% | 93.3% |  |
| LOAD_DEREF | 1,140,264 | 0.3% | 93.5% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,462 | 0.3% | 93.8% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,094,022 | 0.3% | 94.1% | 0.0% |
| COPY_FREE_VARS | 1,091,844 | 0.3% | 94.4% |  |
| BINARY_OP_ADD_INT | 1,076,904 | 0.3% | 94.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,063,817 | 0.3% | 94.9% |  |
| CALL_BUILTIN_FAST | 1,034,784 | 0.3% | 95.2% |  |
| LOAD_SUPER_ATTR_METHOD | 1,030,404 | 0.3% | 95.4% |  |
| UNARY_INVERT | 1,028,277 | 0.3% | 95.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,015,410 | 0.3% | 95.9% | 0.0% |
| GET_ITER | 1,008,790 | 0.3% | 96.2% |  |
| BUILD_LIST | 950,290 | 0.2% | 96.4% |  |
| BUILD_MAP | 910,353 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 830,641 | 0.2% | 96.8% | 0.0% |
| POP_JUMP_IF_NONE | 795,713 | 0.2% | 97.0% |  |
| STORE_SUBSCR_DICT | 792,413 | 0.2% | 97.2% |  |
| CALL_ISINSTANCE | 724,831 | 0.2% | 97.4% |  |
| LOAD_FAST_CHECK | 705,312 | 0.2% | 97.6% |  |
| EXIT_INIT_CHECK | 674,566 | 0.2% | 97.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 674,566 | 0.2% | 97.9% |  |
| LOAD_ATTR_PROPERTY | 651,640 | 0.2% | 98.1% | 1.9% |
| BINARY_SUBSCR | 591,328 | 0.1% | 98.2% |  |
| DICT_MERGE | 561,380 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 527,075 | 0.1% | 98.6% |  |
| LOAD_FAST_AND_CLEAR | 477,667 | 0.1% | 98.7% |  |
| COMPARE_OP | 361,417 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 355,013 | 0.1% | 98.9% |  |
| LIST_EXTEND | 289,402 | 0.1% | 99.0% |  |
| CALL_LEN | 257,783 | 0.1% | 99.1% |  |
| CALL_KW | 249,290 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,548 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 225,220 | 0.1% | 99.2% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 214,372 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 185,461 | 0.0% | 99.3% |  |
| CALL_LIST_APPEND | 171,423 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 160,492 | 0.0% | 99.4% |  |
| UNARY_NOT | 160,143 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 144,650 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 136,160 | 0.0% | 99.5% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.6% |  |
| STORE_DEREF | 132,820 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 95,267 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,591 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 75,014 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 63,600 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,800 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,442 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 44,842 | 0.0% | 99.8% | 13.5% |
| IS_OP | 44,154 | 0.0% | 99.8% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 38,560 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,040 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 37,100 | 0.0% | 99.9% |  |
| POP_EXCEPT | 35,828 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 35,828 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| FOR_ITER | 33,480 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 30,388 | 0.0% | 99.9% |  |
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
| TO_BOOL_ALWAYS_TRUE | 446 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,541,288 | 4.4% | 4.4% |
| RESUME_CHECK LOAD_FAST | 16,528,467 | 4.1% | 8.5% |
| CACHE RESUME_CHECK | 10,520,007 | 2.6% | 11.1% |
| RETURN_VALUE INTERPRETER_EXIT | 9,408,940 | 2.3% | 13.4% |
| LOAD_FAST RETURN_VALUE | 8,724,344 | 2.2% | 15.6% |
| STORE_FAST LOAD_FAST | 8,485,816 | 2.1% | 17.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,906,509 | 2.0% | 19.6% |
| POP_TOP ENTER_EXECUTOR | 7,259,511 | 1.8% | 21.4% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.6% | 23.0% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.5% | 24.5% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.5% | 26.0% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.5% | 27.5% |
| ENTER_EXECUTOR YIELD_VALUE | 5,971,280 | 1.5% | 29.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,509,642 | 1.4% | 30.3% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.3% | 31.7% |
| POP_TOP LOAD_FAST | 5,061,350 | 1.3% | 32.9% |
| LOAD_FAST LOAD_ATTR | 4,854,954 | 1.2% | 34.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,738,047 | 1.2% | 35.3% |
| RETURN_CONST POP_TOP | 4,540,901 | 1.1% | 36.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,499,231 | 1.1% | 37.6% |
| NOP LOAD_FAST | 3,886,479 | 1.0% | 38.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,729,783 | 0.9% | 39.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,340,410 | 0.8% | 40.3% |
| LOAD_CONST LOAD_CONST | 3,245,477 | 0.8% | 41.1% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,151,930 | 0.8% | 41.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,064,535 | 0.8% | 42.6% |
| STORE_FAST NOP | 2,959,040 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,912,090 | 0.7% | 44.1% |
| PUSH_NULL LOAD_FAST | 2,903,899 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,677,639 | 0.7% | 45.5% |
| COPY STORE_FAST | 2,597,760 | 0.6% | 46.1% |
| STORE_FAST COPY | 2,597,440 | 0.6% | 46.8% |
| LOAD_FAST LOAD_CONST | 2,564,338 | 0.6% | 47.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,563,560 | 0.6% | 48.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,459,686 | 0.6% | 48.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,411,435 | 0.6% | 49.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,360,672 | 0.6% | 49.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,283,656 | 0.6% | 50.4% |
| LOAD_CONST CALL | 2,271,914 | 0.6% | 51.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,240,245 | 0.6% | 51.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,164,389 | 0.5% | 52.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,130,745 | 0.5% | 52.6% |
| LOAD_FAST PUSH_NULL | 2,100,321 | 0.5% | 53.1% |
| CALL STORE_FAST | 2,044,074 | 0.5% | 53.6% |
| LOAD_ATTR LOAD_FAST | 2,007,210 | 0.5% | 54.1% |
| CALL RETURN_VALUE | 1,910,031 | 0.5% | 54.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,897,738 | 0.5% | 55.1% |
| CALL POP_TOP | 1,876,196 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,755,467 | 0.4% | 56.0% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,622 | 0.4% | 56.4% |
| BINARY_OP COPY | 1,736,148 | 0.4% | 56.8% |
| COPY TO_BOOL_INT | 1,735,828 | 0.4% | 57.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,700,439 | 0.4% | 57.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,697,501 | 0.4% | 58.1% |
| ENTER_EXECUTOR CALL | 1,676,040 | 0.4% | 58.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,616,123 | 0.4% | 58.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,570,768 | 0.4% | 59.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,544,797 | 0.4% | 59.7% |
| POP_TOP RETURN_CONST | 1,537,959 | 0.4% | 60.1% |
| POP_TOP LOAD_CONST | 1,510,401 | 0.4% | 60.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,495,598 | 0.4% | 60.8% |
| RETURN_VALUE STORE_FAST | 1,430,468 | 0.4% | 61.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,420,652 | 0.4% | 61.5% |
| LOAD_CONST LOAD_FAST | 1,403,938 | 0.3% | 61.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,381,896 | 0.3% | 62.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,376,686 | 0.3% | 62.5% |
| LOAD_FAST TO_BOOL | 1,352,356 | 0.3% | 62.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,329,004 | 0.3% | 63.2% |
| ENTER_EXECUTOR FOR_ITER_LIST | 1,316,628 | 0.3% | 63.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,300,255 | 0.3% | 63.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,285,823 | 0.3% | 64.2% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,283,001 | 0.3% | 64.5% |
| BEFORE_WITH POP_TOP | 1,276,906 | 0.3% | 64.8% |
| LOAD_FAST BUILD_TUPLE | 1,265,431 | 0.3% | 65.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,258,689 | 0.3% | 65.4% |
| LOAD_CONST COMPARE_OP_INT | 1,254,788 | 0.3% | 65.8% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,250,815 | 0.3% | 66.1% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,250,155 | 0.3% | 66.4% |
| LOAD_ATTR PUSH_NULL | 1,211,711 | 0.3% | 66.7% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,196,042 | 0.3% | 67.0% |
| RETURN_VALUE RETURN_VALUE | 1,187,843 | 0.3% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,179,829 | 0.3% | 67.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,153,472 | 0.3% | 67.8% |
| POP_TOP NOP | 1,146,072 | 0.3% | 68.1% |
| NOP LOAD_GLOBAL_MODULE | 1,126,125 | 0.3% | 68.4% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,123,327 | 0.3% | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,122,414 | 0.3% | 69.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,096,899 | 0.3% | 69.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,091,184 | 0.3% | 69.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,088,011 | 0.3% | 69.8% |
| LOAD_DEREF LOAD_FAST | 1,085,884 | 0.3% | 70.0% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,085,364 | 0.3% | 70.3% |
| LOAD_CONST COPY | 1,067,520 | 0.3% | 70.6% |
| COPY STORE_FAST_STORE_FAST | 1,061,440 | 0.3% | 70.8% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,059,864 | 0.3% | 71.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,056,859 | 0.3% | 71.4% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,056,280 | 0.3% | 71.6% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,056,220 | 0.3% | 71.9% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,055,880 | 0.3% | 72.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 1,043,660 | 0.3% | 72.4% |


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
| RESUME_CHECK | 10,520,007 | 99.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,179,829 | 74.3% |
| RETURN_VALUE | 305,013 | 19.2% |
| LOAD_GLOBAL_MODULE | 79,557 | 5.0% |
| LOAD_FAST | 16,320 | 1.0% |
| CALL | 6,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,276,906 | 80.4% |
| STORE_FAST | 310,353 | 19.6% |


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
| LOAD_CONST | 46,328 | 7.8% |
| BINARY_SUBSCR | 840 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 92.0% |
| STORE_FAST | 46,048 | 7.8% |
| BINARY_SUBSCR | 840 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,228 | 83.0% |
| LOAD_ATTR_MODULE | 5,100 | 16.8% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,388 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,937 | 49.2% |
| CALL | 26,557 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,434 | 15.2% |
| LOAD_ATTR | 86 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,557 | 78.1% |
| RETURN_CONST | 10,237 | 13.6% |
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
| RETURN_CONST | 674,566 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 674,566 | 100.0% |


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
| LOAD_FAST | 943,390 | 93.5% |
| CALL_BUILTIN_CLASS | 34,980 | 3.5% |
| CALL | 12,420 | 1.2% |
| STORE_FAST_LOAD_FAST | 6,080 | 0.6% |
| RETURN_VALUE | 5,440 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 622,546 | 61.7% |
| LOAD_FAST_AND_CLEAR | 317,464 | 31.5% |
| FOR_ITER_RANGE | 29,026 | 2.9% |
| FOR_ITER | 11,474 | 1.1% |
| FOR_ITER_TUPLE | 11,100 | 1.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,408,940 | 88.8% |
| RETURN_CONST | 642,404 | 6.1% |
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
| STORE_FAST | 2,959,040 | 45.2% |
| POP_TOP | 1,146,072 | 17.5% |
| POP_JUMP_IF_FALSE | 1,020,216 | 15.6% |
| RESUME_CHECK | 900,931 | 13.8% |
| POP_JUMP_IF_NOT_NONE | 311,943 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,886,479 | 59.3% |
| LOAD_GLOBAL_MODULE | 1,126,125 | 17.2% |
| LOAD_FAST_LOAD_FAST | 550,360 | 8.4% |
| LOAD_CONST | 529,060 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 444,879 | 6.8% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 19,448 | 54.3% |
| COPY | 10,880 | 30.4% |
| POP_TOP | 5,200 | 14.5% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 19,048 | 53.2% |
| RERAISE | 10,880 | 30.4% |
| JUMP_FORWARD | 5,120 | 14.3% |
| JUMP_BACKWARD | 700 | 2.0% |
| RETURN_CONST | 60 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 34.0% |
| RETURN_CONST | 4,540,901 | 23.7% |
| CALL | 1,876,196 | 9.8% |
| BEFORE_WITH | 1,276,906 | 6.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,043,660 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,259,511 | 37.8% |
| LOAD_FAST | 5,061,350 | 26.4% |
| RETURN_CONST | 1,537,959 | 8.0% |
| LOAD_CONST | 1,510,401 | 7.9% |
| NOP | 1,146,072 | 6.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,848 | 69.4% |
| RERAISE | 5,440 | 15.2% |
| CALL_KW | 5,120 | 14.3% |
| BINARY_SUBSCR_DICT | 300 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,188 | 70.3% |
| WITH_EXCEPT_START | 5,440 | 15.2% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.2% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,100,321 | 46.4% |
| LOAD_ATTR | 1,211,711 | 26.8% |
| LOAD_ATTR_MODULE | 1,123,327 | 24.8% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,903,899 | 64.2% |
| LOAD_FAST_LOAD_FAST | 713,224 | 15.8% |
| CALL | 602,829 | 13.3% |
| LOAD_CONST | 237,522 | 5.2% |
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
| LOAD_FAST | 8,724,344 | 51.8% |
| CALL | 1,910,031 | 11.3% |
| CALL_FUNCTION_EX | 1,196,042 | 7.1% |
| RETURN_VALUE | 1,187,843 | 7.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,002,018 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,408,940 | 55.9% |
| STORE_FAST | 1,430,468 | 8.5% |
| RETURN_VALUE | 1,187,843 | 7.1% |
| POP_TOP | 919,802 | 5.5% |
| LOAD_FAST_LOAD_FAST | 707,871 | 4.2% |


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
| LOAD_FAST | 1,352,356 | 95.9% |
| LOAD_ATTR_INSTANCE_VALUE | 49,978 | 3.5% |
| TO_BOOL | 3,442 | 0.2% |
| LOAD_ATTR | 891 | 0.1% |
| RETURN_VALUE | 769 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 716,274 | 50.8% |
| POP_JUMP_IF_FALSE | 687,395 | 48.7% |
| TO_BOOL | 3,442 | 0.2% |
| TO_BOOL_BOOL | 2,165 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 707,871 | 68.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 320,326 | 31.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,028,277 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 160,103 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 160,143 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,283,656 | 53.1% |
| UNARY_INVERT | 1,028,277 | 23.9% |
| POP_JUMP_IF_FALSE | 707,871 | 16.5% |
| LOAD_ATTR | 172,383 | 4.0% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,736,148 | 40.4% |
| STORE_FAST | 880,574 | 20.5% |
| TO_BOOL_INT | 707,931 | 16.5% |
| UNARY_INVERT | 707,871 | 16.5% |
| BUILD_TUPLE | 160,203 | 3.7% |


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
| SWAP | 317,464 | 33.4% |
| JUMP_FORWARD | 304,773 | 32.1% |
| LOAD_FAST | 160,552 | 16.9% |
| POP_TOP | 144,241 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 321,373 | 33.8% |
| SWAP | 317,464 | 33.4% |
| STORE_FAST | 305,593 | 32.2% |
| RETURN_VALUE | 5,120 | 0.5% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 528,600 | 58.1% |
| RESUME_CHECK | 314,973 | 34.6% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 3.6% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.8% |
| POP_TOP | 6,080 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 887,933 | 97.5% |
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
| LOAD_FAST | 1,265,431 | 49.7% |
| LOAD_FAST_LOAD_FAST | 556,800 | 21.9% |
| RETURN_VALUE | 512,000 | 20.1% |
| BINARY_OP | 160,203 | 6.3% |
| LOAD_ATTR_INSTANCE_VALUE | 21,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 708,791 | 27.9% |
| YIELD_VALUE | 550,140 | 21.6% |
| STORE_FAST | 512,000 | 20.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 20.1% |
| CALL_LIST_APPEND | 160,123 | 6.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,271,914 | 26.0% |
| ENTER_EXECUTOR | 1,676,040 | 19.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,329,004 | 15.2% |
| LOAD_FAST_LOAD_FAST | 833,940 | 9.6% |
| BUILD_TUPLE | 708,791 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,044,074 | 23.4% |
| RETURN_VALUE | 1,910,031 | 21.9% |
| POP_TOP | 1,876,196 | 21.5% |
| LOAD_FAST | 759,525 | 8.7% |
| TO_BOOL_BOOL | 682,522 | 7.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,622 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,196,042 | 51.8% |
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
| LOAD_CONST | 244,170 | 97.9% |
| ENTER_EXECUTOR | 5,120 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 186,081 | 74.6% |
| LOAD_FAST | 27,200 | 10.9% |
| RETURN_VALUE | 18,240 | 7.3% |
| STORE_FAST | 12,300 | 4.9% |
| PUSH_EXC_INFO | 5,120 | 2.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 356,563 | 98.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,647 | 0.5% |
| COMPARE_OP | 1,259 | 0.3% |
| LOAD_GLOBAL_MODULE | 376 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 358,166 | 99.1% |
| COMPARE_OP | 1,259 | 0.3% |
| COMPARE_OP_INT | 1,198 | 0.3% |
| COMPARE_OP_STR | 436 | 0.1% |
| POP_JUMP_IF_TRUE | 278 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,250,155 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,250,815 | 100.0% |
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
| STORE_FAST | 2,597,440 | 43.2% |
| BINARY_OP | 1,736,148 | 28.9% |
| LOAD_CONST | 1,067,520 | 17.8% |
| LOAD_FAST | 554,564 | 9.2% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 43.2% |
| TO_BOOL_INT | 1,735,828 | 28.9% |
| STORE_FAST_STORE_FAST | 1,061,440 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 542,264 | 9.0% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 707,871 | 64.8% |
| CALL_ALLOC_AND_ENTER_INIT | 304,733 | 27.9% |
| CACHE | 73,100 | 6.7% |
| CALL | 5,620 | 0.5% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,091,184 | 99.9% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,591 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,394 | 66.7% |
| RETURN_CONST | 26,557 | 32.5% |
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
| POP_TOP | 7,259,511 | 72.5% |
| POP_JUMP_IF_NOT_NONE | 799,882 | 8.0% |
| STORE_FAST_STORE_FAST | 548,100 | 5.5% |
| FOR_ITER_LIST | 543,320 | 5.4% |
| LIST_APPEND | 525,375 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,971,280 | 59.6% |
| CALL | 1,676,040 | 16.7% |
| FOR_ITER_LIST | 1,316,628 | 13.1% |
| CALL_PY_WITH_DEFAULTS | 439,651 | 4.4% |
| LOAD_ATTR_PROPERTY | 416,354 | 4.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,240 | 36.6% |
| GET_ITER | 11,474 | 34.3% |
| LOAD_FAST | 5,740 | 17.1% |
| JUMP_BACKWARD | 3,106 | 9.3% |
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
| LOAD_GLOBAL_MODULE | 1,094 | 2.5% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,014 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,440,000 | 90.7% |
| POP_TOP | 550,363 | 9.2% |
| LIST_APPEND | 1,700 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 1,340 | 0.0% |
| STORE_FAST_STORE_FAST | 1,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,983,920 | 99.7% |
| FOR_ITER_LIST | 4,914 | 0.1% |
| FOR_ITER | 3,106 | 0.1% |
| FOR_ITER_RANGE | 2,154 | 0.0% |
| LOAD_FAST | 1,632 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 656,341 | 52.1% |
| POP_TOP | 586,495 | 46.6% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.4% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 895,618 | 71.1% |
| BUILD_LIST | 304,773 | 24.2% |
| LOAD_GLOBAL_MODULE | 22,577 | 1.8% |
| POP_EXCEPT | 19,448 | 1.5% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 268,712 | 51.0% |
| LOAD_ATTR | 160,223 | 30.4% |
| BINARY_SUBSCR_STR_INT | 97,240 | 18.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 525,375 | 99.7% |
| JUMP_BACKWARD | 1,700 | 0.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 145,021 | 50.1% |
| RETURN_VALUE | 144,241 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,561 | 50.0% |
| STORE_FAST | 144,241 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,854,954 | 73.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,544,797 | 23.3% |
| LOAD_GLOBAL_MODULE | 121,560 | 1.8% |
| CALL | 49,620 | 0.7% |
| LOAD_ATTR | 20,776 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,007,210 | 30.3% |
| PUSH_NULL | 1,211,711 | 18.3% |
| STORE_SUBSCR_DICT | 707,791 | 10.7% |
| POP_JUMP_IF_NOT_NONE | 665,953 | 10.0% |
| STORE_FAST | 478,577 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,245,477 | 26.6% |
| LOAD_FAST | 2,564,338 | 21.0% |
| POP_TOP | 1,510,401 | 12.4% |
| POP_JUMP_IF_FALSE | 786,218 | 6.4% |
| LOAD_ATTR_METHOD_NO_DICT | 683,262 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,245,477 | 26.6% |
| CALL | 2,271,914 | 18.6% |
| LOAD_FAST | 1,403,938 | 11.5% |
| COMPARE_OP_INT | 1,254,788 | 10.3% |
| COPY | 1,067,520 | 8.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,085,364 | 95.2% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.3% |
| STORE_DEREF | 26,560 | 2.3% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,085,884 | 95.2% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 4.7% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,528,467 | 23.3% |
| STORE_FAST | 8,485,816 | 12.0% |
| POP_JUMP_IF_FALSE | 5,509,642 | 7.8% |
| POP_TOP | 5,061,350 | 7.1% |
| NOP | 3,886,479 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,541,288 | 24.8% |
| RETURN_VALUE | 8,724,344 | 12.3% |
| LOAD_ATTR | 4,854,954 | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,738,047 | 6.7% |
| CALL_PY_EXACT_ARGS | 3,064,535 | 4.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 317,464 | 66.5% |
| LOAD_FAST_AND_CLEAR | 160,203 | 33.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 317,464 | 66.5% |
| LOAD_FAST_AND_CLEAR | 160,203 | 33.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 77.2% |
| POP_JUMP_IF_NONE | 144,570 | 20.5% |
| LOAD_ATTR_CLASS | 15,862 | 2.2% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 77.1% |
| LOAD_GLOBAL_MODULE | 144,490 | 20.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,822 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,616,123 | 18.8% |
| POP_JUMP_IF_FALSE | 913,716 | 10.6% |
| LOAD_FAST_LOAD_FAST | 774,771 | 9.0% |
| LOAD_SUPER_ATTR_METHOD | 720,231 | 8.4% |
| POP_JUMP_IF_TRUE | 717,143 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,130,745 | 24.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,056,859 | 12.3% |
| CALL | 833,940 | 9.7% |
| LOAD_FAST_LOAD_FAST | 774,771 | 9.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 707,791 | 8.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,707 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,816 | 38.2% |
| LOAD_ATTR | 3,329 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,744 | 15.4% |
| LOAD_FAST | 2,171 | 12.2% |
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
| TO_BOOL_BOOL | 3,340,410 | 25.0% |
| TO_BOOL_INT | 3,151,930 | 23.5% |
| COMPARE_OP_INT | 2,677,639 | 20.0% |
| COMPARE_OP_STR | 1,283,001 | 9.6% |
| CONTAINS_OP | 1,250,815 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,509,642 | 41.2% |
| RETURN_CONST | 2,360,672 | 17.6% |
| NOP | 1,020,216 | 7.6% |
| LOAD_GLOBAL_MODULE | 938,614 | 7.0% |
| LOAD_FAST_LOAD_FAST | 913,716 | 6.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 725,593 | 91.2% |
| LOAD_ATTR_INSTANCE_VALUE | 44,600 | 5.6% |
| LOAD_ATTR | 24,460 | 3.1% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,712 | 28.9% |
| LOAD_GLOBAL_MODULE | 194,518 | 24.4% |
| NOP | 181,201 | 22.8% |
| LOAD_FAST_CHECK | 144,570 | 18.2% |
| RETURN_CONST | 22,420 | 2.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,164,389 | 57.5% |
| LOAD_ATTR | 665,953 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 593,350 | 15.8% |
| RETURN_VALUE | 269,032 | 7.1% |
| LOAD_DEREF | 53,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,700,439 | 45.1% |
| ENTER_EXECUTOR | 799,882 | 21.2% |
| RETURN_CONST | 666,600 | 17.7% |
| NOP | 311,943 | 8.3% |
| LOAD_CONST | 144,521 | 3.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,495,598 | 66.7% |
| TO_BOOL | 716,274 | 31.9% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,524 | 0.5% |
| COMPARE_OP_INT | 1,946 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 909,425 | 40.5% |
| LOAD_FAST_LOAD_FAST | 717,143 | 32.0% |
| RETURN_CONST | 464,535 | 20.7% |
| LOAD_GLOBAL_MODULE | 57,319 | 2.6% |
| RETURN_VALUE | 46,008 | 2.1% |


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
| POP_JUMP_IF_FALSE | 2,360,672 | 35.9% |
| POP_TOP | 1,537,959 | 23.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,420,652 | 21.6% |
| POP_JUMP_IF_NOT_NONE | 666,600 | 10.1% |
| POP_JUMP_IF_TRUE | 464,535 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,540,901 | 69.0% |
| EXIT_INIT_CHECK | 674,566 | 10.2% |
| INTERPRETER_EXIT | 642,404 | 9.8% |
| TO_BOOL_BOOL | 640,563 | 9.7% |
| STORE_FAST | 47,208 | 0.7% |


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
| LOAD_FAST | 56,327 | 59.1% |
| LOAD_FAST_LOAD_FAST | 19,800 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,320 | 17.1% |
| STORE_ATTR | 2,360 | 2.5% |
| LOAD_ATTR | 240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,920 | 45.1% |
| LOAD_FAST | 12,980 | 13.6% |
| LOAD_FAST_LOAD_FAST | 12,840 | 13.5% |
| LOAD_CONST | 12,006 | 12.6% |
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
| YIELD_VALUE | 5,983,920 | 27.3% |
| COPY | 2,597,760 | 11.9% |
| CALL | 2,044,074 | 9.3% |
| RETURN_VALUE | 1,430,468 | 6.5% |
| STORE_FAST_STORE_FAST | 1,056,280 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,485,816 | 38.7% |
| JUMP_BACKWARD | 5,440,000 | 24.8% |
| NOP | 2,959,040 | 13.5% |
| COPY | 2,597,440 | 11.9% |
| JUMP_FORWARD | 656,341 | 3.0% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,153,472 | 30.5% |
| COPY | 1,061,440 | 28.1% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 27.9% |
| STORE_FAST_STORE_FAST | 512,000 | 13.5% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,376,686 | 36.4% |
| STORE_FAST | 1,056,280 | 27.9% |
| ENTER_EXECUTOR | 548,100 | 14.5% |
| STORE_FAST_STORE_FAST | 512,000 | 13.5% |
| LOAD_FAST_LOAD_FAST | 276,146 | 7.3% |


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
| BINARY_OP_ADD_INT | 542,324 | 29.7% |
| BUILD_LIST | 317,464 | 17.4% |
| LOAD_FAST_AND_CLEAR | 317,464 | 17.4% |
| FOR_ITER_LIST | 304,444 | 16.7% |
| LOAD_FAST | 171,410 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 542,264 | 29.7% |
| LOAD_CONST | 331,613 | 18.2% |
| BUILD_LIST | 317,464 | 17.4% |
| STORE_FAST | 317,464 | 17.4% |
| FOR_ITER_LIST | 304,364 | 16.7% |


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
| LOAD_FAST | 160,452 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160,492 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,059,864 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 542,324 | 50.4% |
| STORE_FAST | 511,980 | 47.5% |
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
| CALL | 144,490 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 144,650 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,884 | 76.0% |
| LOAD_CONST | 45,928 | 21.4% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 208,972 | 97.5% |
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
| LOAD_GLOBAL_MODULE | 331,213 | 49.1% |
| LOAD_FAST | 310,793 | 46.1% |
| CALL | 32,140 | 4.8% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 369,833 | 54.8% |
| COPY_FREE_VARS | 304,733 | 45.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 71.9% |
| LOAD_CONST | 6,360 | 14.2% |
| BINARY_OP_ADD_INT | 5,360 | 12.0% |
| PUSH_NULL | 625 | 1.4% |
| CALL | 157 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,782 | 86.5% |
| POP_TOP | 5,960 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 43.8% |
| RETURN_VALUE | 439,059 | 37.6% |
| LOAD_FAST | 176,952 | 15.1% |
| LOAD_CONST | 12,360 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 10,260 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 672,472 | 57.5% |
| STORE_FAST | 439,359 | 37.6% |
| GET_ITER | 34,980 | 3.0% |
| LOAD_FAST | 16,320 | 1.4% |
| CALL_BUILTIN_CLASS | 6,000 | 0.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 534,857 | 51.7% |
| LOAD_CONST | 295,401 | 28.5% |
| LOAD_FAST_LOAD_FAST | 107,084 | 10.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,202 | 4.7% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 361,827 | 35.0% |
| TO_BOOL_BOOL | 287,581 | 27.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 270,026 | 26.1% |
| UNPACK_SEQUENCE_TUPLE | 48,202 | 4.7% |
| POP_TOP | 12,728 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,460 | 47.1% |
| BUILD_TUPLE | 511,960 | 46.8% |
| CALL | 32,600 | 3.0% |
| LOAD_FAST_CHECK | 15,822 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,043,660 | 95.4% |
| RETURN_VALUE | 49,102 | 4.5% |
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
| LOAD_GLOBAL_BUILTIN | 724,371 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 724,651 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,459 | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 10.5% |
| CALL | 384 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,764 | 80.6% |
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
| BUILD_TUPLE | 160,123 | 93.4% |
| LOAD_FAST | 10,800 | 6.3% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 159,523 | 93.1% |
| LOAD_GLOBAL_MODULE | 10,800 | 6.3% |
| JUMP_BACKWARD | 640 | 0.4% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,012,624 | 99.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 466 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 708,151 | 69.7% |
| STORE_FAST | 305,499 | 30.1% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,096,899 | 94.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 64,024 | 5.5% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 46.8% |
| POP_TOP | 430,469 | 37.0% |
| LOAD_FAST | 50,180 | 4.3% |
| RETURN_VALUE | 48,684 | 4.2% |
| CALL_BUILTIN_FAST | 48,202 | 4.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 758,881 | 91.4% |
| LOAD_CONST | 30,200 | 3.6% |
| CALL | 27,540 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 786,561 | 94.7% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,729,783 | 46.9% |
| LOAD_FAST | 3,064,535 | 38.5% |
| LOAD_FAST_LOAD_FAST | 562,280 | 7.1% |
| LOAD_SUPER_ATTR_METHOD | 304,693 | 3.8% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,906,509 | 99.4% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 925,065 | 46.1% |
| ENTER_EXECUTOR | 439,651 | 21.9% |
| LOAD_ATTR_MODULE | 304,893 | 15.2% |
| LOAD_FAST | 209,243 | 10.4% |
| LOAD_CONST | 73,632 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,300,255 | 64.7% |
| COPY_FREE_VARS | 707,871 | 35.3% |


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
| LOAD_CONST | 1,254,788 | 46.8% |
| LOAD_ATTR_INSTANCE_VALUE | 842,607 | 31.4% |
| LOAD_FAST | 544,980 | 20.3% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.6% |
| CALL_BUILTIN_FAST | 12,080 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,677,639 | 99.9% |
| POP_JUMP_IF_TRUE | 1,946 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 114 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,258,689 | 95.5% |
| LOAD_CONST | 53,140 | 4.0% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 436 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,283,001 | 97.4% |
| COPY | 12,120 | 0.9% |
| LOAD_FAST | 12,120 | 0.9% |
| POP_JUMP_IF_TRUE | 10,524 | 0.8% |


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
| ENTER_EXECUTOR | 1,316,628 | 58.5% |
| GET_ITER | 622,546 | 27.7% |
| SWAP | 304,364 | 13.5% |
| JUMP_BACKWARD | 4,914 | 0.2% |
| FOR_ITER | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 609,546 | 27.1% |
| ENTER_EXECUTOR | 543,320 | 24.2% |
| STORE_FAST | 456,896 | 20.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 320,386 | 14.2% |
| SWAP | 304,444 | 13.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 154,081 | 83.1% |
| GET_ITER | 29,026 | 15.7% |
| JUMP_BACKWARD | 2,154 | 1.2% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,401 | 77.9% |
| STORE_FAST | 30,500 | 16.4% |
| RETURN_CONST | 10,560 | 5.7% |


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
| LOAD_GLOBAL_MODULE | 48,162 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.5% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,580 | 72.9% |
| LOAD_FAST_CHECK | 15,862 | 27.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,541,288 | 91.4% |
| LOAD_FAST_LOAD_FAST | 1,056,859 | 5.5% |
| COPY | 542,264 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 21,246 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,499,231 | 23.5% |
| LOAD_FAST | 2,912,090 | 15.2% |
| LOAD_ATTR | 1,544,797 | 8.1% |
| LOAD_GLOBAL_MODULE | 1,285,823 | 6.7% |
| CONTAINS_OP | 1,250,155 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,368 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,524 | 39.8% |
| CALL | 82,000 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,024 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,499,231 | 88.3% |
| LOAD_FAST | 468,353 | 9.2% |
| LOAD_ATTR | 51,040 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,755,467 | 34.5% |
| CALL | 1,329,004 | 26.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,096,899 | 21.5% |
| LOAD_CONST | 683,262 | 13.4% |
| LOAD_FAST_LOAD_FAST | 201,372 | 4.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,738,047 | 66.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,088,011 | 15.3% |
| LOAD_FAST_LOAD_FAST | 707,791 | 9.9% |
| BINARY_SUBSCR | 543,920 | 7.6% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,729,783 | 52.4% |
| LOAD_FAST | 1,697,501 | 23.8% |
| CALL_PY_WITH_DEFAULTS | 925,065 | 13.0% |
| LOAD_FAST_LOAD_FAST | 610,720 | 8.6% |
| LOAD_CONST | 90,512 | 1.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,570,768 | 99.8% |
| LOAD_ATTR | 2,820 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,123,327 | 71.4% |
| CALL_PY_WITH_DEFAULTS | 304,893 | 19.4% |
| STORE_DEREF | 53,120 | 3.4% |
| LOAD_CONST | 31,040 | 2.0% |
| LOAD_FAST | 27,840 | 1.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 743,271 | 69.9% |
| LOAD_FAST_LOAD_FAST | 320,246 | 30.1% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 707,831 | 66.5% |
| UNARY_INVERT | 320,326 | 30.1% |
| RETURN_VALUE | 12,120 | 1.1% |
| LOAD_CONST | 12,120 | 1.1% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 416,354 | 63.9% |
| LOAD_FAST | 207,666 | 31.9% |
| RETURN_VALUE | 26,480 | 4.1% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 639,260 | 98.1% |
| TO_BOOL_BOOL | 12,160 | 1.9% |
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
| RESUME_CHECK | 2,411,435 | 48.9% |
| LOAD_FAST | 747,811 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.6% |
| STORE_FAST | 464,257 | 9.4% |
| NOP | 444,879 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,459,686 | 49.9% |
| LOAD_DEREF | 1,085,364 | 22.0% |
| CALL_ISINSTANCE | 724,371 | 14.7% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.6% |
| LOAD_GLOBAL_MODULE | 43,000 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,563,560 | 24.5% |
| RESUME_CHECK | 1,897,738 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,285,823 | 12.3% |
| NOP | 1,126,125 | 10.8% |
| POP_JUMP_IF_FALSE | 938,614 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,283,656 | 21.8% |
| LOAD_FAST_LOAD_FAST | 1,616,123 | 15.4% |
| LOAD_ATTR_MODULE | 1,570,768 | 15.0% |
| LOAD_FAST | 1,381,896 | 13.2% |
| COMPARE_OP_STR | 1,258,689 | 12.0% |


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
| LOAD_FAST | 1,030,204 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 720,231 | 69.9% |
| CALL_PY_EXACT_ARGS | 304,693 | 29.6% |
| LOAD_FAST | 5,440 | 0.5% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,520,007 | 36.3% |
| CALL_PY_EXACT_ARGS | 7,906,509 | 27.3% |
| FOR_ITER_GEN | 5,983,920 | 20.7% |
| CALL_PY_WITH_DEFAULTS | 1,300,255 | 4.5% |
| COPY_FREE_VARS | 1,091,184 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,528,467 | 57.1% |
| POP_TOP | 6,528,880 | 22.5% |
| LOAD_GLOBAL_BUILTIN | 2,411,435 | 8.3% |
| LOAD_GLOBAL_MODULE | 1,897,738 | 6.6% |
| NOP | 900,931 | 3.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,240,245 | 66.5% |
| LOAD_FAST_LOAD_FAST | 550,793 | 16.3% |
| SWAP | 542,264 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,420,652 | 42.2% |
| LOAD_FAST | 880,744 | 26.1% |
| LOAD_GLOBAL_MODULE | 530,833 | 15.8% |
| LOAD_CONST | 289,414 | 8.6% |
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
| LOAD_ATTR | 707,791 | 89.3% |
| LOAD_FAST | 40,802 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.1% |
| CALL | 10,200 | 1.3% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 709,933 | 89.6% |
| RETURN_CONST | 29,000 | 3.7% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.4% |
| LOAD_CONST | 26,520 | 3.3% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 62.8% |
| COPY | 126 | 28.3% |
| TO_BOOL | 40 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 67.3% |
| POP_JUMP_IF_FALSE | 146 | 32.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,122,414 | 22.5% |
| CALL_ISINSTANCE | 724,651 | 14.5% |
| CALL | 682,522 | 13.7% |
| LOAD_FAST | 668,008 | 13.4% |
| RETURN_CONST | 640,563 | 12.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,340,410 | 66.9% |
| POP_JUMP_IF_TRUE | 1,495,598 | 29.9% |
| UNARY_NOT | 160,103 | 3.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,735,828 | 55.1% |
| BINARY_OP | 707,931 | 22.5% |
| LOAD_FAST | 707,791 | 22.5% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,151,930 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 315,553 | 88.9% |
| LOAD_ATTR_INSTANCE_VALUE | 39,240 | 11.1% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 354,853 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,000 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,760 | 92.2% |
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
| CALL_BUILTIN_FAST | 48,202 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,242 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_CHECK | 543,920 | 46.9% |
| FOR_ITER_LIST | 320,386 | 27.6% |
| CALL_BUILTIN_FAST | 270,026 | 23.3% |
| FOR_ITER | 11,360 | 1.0% |
| CALL | 7,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,153,472 | 99.5% |
| LOAD_FAST | 6,040 | 0.5% |
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
|     deferred | 4,293,030 | 71.3% |
|          hit | 1,722,318 | 28.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 9.6% |
| Failure | 5,678 | 90.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,808 | 49.5% |
| or | 1,470 | 25.9% |
| remainder | 720 | 12.7% |
| add different types | 600 | 10.6% |
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
|     deferred | 590,248 | 69.4% |
|          hit | 259,120 | 30.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 22.2% |
| Failure | 840 | 77.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 840 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,685,341 | 31.4% |
|          hit | 18,905,513 | 68.4% |
|         miss | 7,520 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,287 | 24.9% |
| Failure | 27,973 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,284 | 26.0% |
| cfunc noargs | 5,800 | 20.7% |
| class no vectorcall | 3,780 | 13.5% |
| meth descr varargs keywords | 3,059 | 10.9% |
| class mutable | 1,134 | 4.1% |
| other | 1,100 | 3.9% |
| bound method | 1,042 | 3.7% |
| cfunc varargs | 1,020 | 3.6% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 794 | 2.8% |
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
|     deferred | 358,410 | 8.2% |
|          hit | 3,990,712 | 91.5% |
|         miss | 7,192 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,634 | 54.3% |
| Failure | 1,373 | 45.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 764 | 55.6% |
| big int | 340 | 24.8% |
| different types | 269 | 19.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,940 | 0.4% |
|          hit | 8,454,433 | 99.6% |

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
|     deferred | 6,586,664 | 15.8% |
|          hit | 34,745,068 | 83.4% |
|         miss | 309,507 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,430 | 54.8% |
| Failure | 18,522 | 45.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,316 | 23.3% |
| shadowed | 3,920 | 21.2% |
| not managed dict | 3,286 | 17.7% |
| non overriding descriptor | 1,984 | 10.7% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.1% |
| metaclass attribute | 900 | 4.9% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 436 | 2.4% |
| mutable class | 260 | 1.4% |
| overridden | 60 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,387 | 0.1% |
|        deopt | 100 | 0.0% |
|          hit | 15,396,044 | 99.9% |
|         miss | 3,243 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,571 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,085,364 | 100.0% |

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
|     deferred | 83,926 | 2.4% |
|          hit | 3,186,923 | 90.3% |
|         miss | 245,260 | 7.0% |

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
|          hit | 792,413 | 96.5% |

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
|     deferred | 1,403,709 | 13.8% |
|          hit | 8,730,240 | 86.1% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,005 | 46.6% |
| Failure | 3,442 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,002 | 29.1% |
| sequence | 840 | 24.4% |
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
|          hit | 2,263,994 | 100.0% |

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
| Basic | 231,730,045 | 57.5% |
| Not specialized | 42,428,673 | 10.5% |
| Specialized hits | 128,431,472 | 31.9% |
| Specialized misses | 573,007 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,685,341 | 39.4% |
| LOAD_ATTR | 6,586,664 | 29.8% |
| BINARY_OP | 4,293,030 | 19.5% |
| TO_BOOL | 1,403,709 | 6.4% |
| BINARY_SUBSCR | 590,248 | 2.7% |
| COMPARE_OP | 358,410 | 1.6% |
| STORE_ATTR | 83,926 | 0.4% |
| FOR_ITER | 31,940 | 0.1% |
| STORE_SUBSCR | 28,100 | 0.1% |
| LOAD_GLOBAL | 8,387 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.8% |
| LOAD_ATTR_INSTANCE_VALUE | 214,000 | 37.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,027 | 14.3% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.2% |
| COMPARE_OP_INT | 7,172 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,903 | 0.5% |
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
| Calls to PyEval_EvalDefault | 10,601,907 | 36.6% |
| Calls to Python functions inlined | 18,385,970 | 63.4% |
| Calls via PyEval_EvalFrame (total) | 10,601,907 | 36.6% |
| Calls via PyEval_EvalFrame (vector) | 10,050,387 | 34.7% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 1.9% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 10,049,687 | 34.7% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.8% |
| Calls via PyEval_EvalFrame (api) | 432,166 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 35,942 | 0.1% |
| Frames pushed | 12,362,088 | 42.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,499,007 | 40.9% |
| Frees to freelist | 14,511,064 |  |
| Allocations | 20,975,258 | 59.1% |
| Allocations to 512 bytes | 20,792,248 | 58.6% |
| Allocations to 4 kbytes | 83,495 | 0.2% |
| Allocations over 4 kbytes | 99,515 | 0.3% |
| Frees | 21,879,808 |  |
| New values | 80,340 |  |
| Interpreter increfs | 180,969,863 | 78.7% |
| Interpreter decrefs | 196,613,782 | 74.9% |
| Increfs | 49,110,618 | 21.3% |
| Decrefs | 65,746,438 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 7,941,235 |  |
| Method cache misses | 46,044 |  |
| Method cache collisions | 87,870 |  |
| Method cache dunder hits | 9,137,227 |  |
| Method cache dunder misses | 45,609 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 28 | 420 | 207,768 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,194 |  |
| Traces created | 794 | 18.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 3,400 | 81.1% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 10,019,552 |  |
| Uops executed | 84,601,091 | 8.44 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 139 | 17.5% |
| <= 32 | 420 | 52.9% |
| <= 64 | 80 | 10.1% |
| <= 128 | 135 | 17.0% |
| <= 256 | 20 | 2.5% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 80 | 10.1% |
| <= 8 | 59 | 7.4% |
| <= 16 | 340 | 42.8% |
| <= 32 | 140 | 17.6% |
| <= 64 | 55 | 6.9% |
| <= 128 | 120 | 15.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,340,793 | 13.4% |
| <= 4 | 1,191,289 | 11.9% |
| <= 8 | 4,895,886 | 48.9% |
| <= 16 | 1,453,967 | 14.5% |
| <= 32 | 962,093 | 9.6% |
| <= 64 | 5,488 | 0.1% |
| <= 128 | 170,012 | 1.7% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 3 | 0.0% |
| <= 2,048 | 2 | 0.0% |
| <= 4,096 | 5 | 0.0% |
| <= 8,192 | 14 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 14,491,959 | 17.1% | 17.1% |  |
| _EXIT_TRACE | 8,508,625 | 10.1% | 27.2% |  |
| STORE_FAST | 8,405,498 | 9.9% | 37.1% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 7,302,925 | 8.6% | 45.8% | 18.0% |
| _ITER_CHECK_LIST | 7,302,925 | 8.6% | 54.4% |  |
| _ITER_NEXT_LIST | 5,986,297 | 7.1% | 61.5% |  |
| _SET_IP | 5,786,654 | 6.8% | 68.3% |  |
| _CHECK_VALIDITY | 5,325,415 | 6.3% | 74.6% |  |
| _GUARD_GLOBALS_VERSION | 2,194,387 | 2.6% | 77.2% |  |
| PUSH_NULL | 1,783,052 | 2.1% | 79.3% |  |
| _FOR_ITER_TIER_TWO | 1,188,440 | 1.4% | 80.7% | 2.4% |
| _GUARD_BUILTINS_VERSION | 1,101,764 | 1.3% | 82.0% |  |
| _LOAD_GLOBAL_BUILTINS | 1,101,764 | 1.3% | 83.3% |  |
| _LOAD_GLOBAL_MODULE | 1,092,623 | 1.3% | 84.6% |  |
| BUILD_TUPLE | 1,081,040 | 1.3% | 85.9% |  |
| _CHECK_ATTR_MODULE | 946,830 | 1.1% | 87.0% |  |
| _LOAD_ATTR_MODULE | 946,830 | 1.1% | 88.1% |  |
| GET_ITER | 676,121 | 0.8% | 88.9% |  |
| _GUARD_TYPE_VERSION | 572,242 | 0.7% | 89.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 538,380 | 0.6% | 90.2% |  |
| BUILD_MAP | 537,920 | 0.6% | 90.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 508,748 | 0.6% | 91.5% |  |
| _GUARD_KEYS_VERSION | 508,748 | 0.6% | 92.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 508,748 | 0.6% | 92.7% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 450,963 | 0.5% | 93.2% | 34.2% |
| _ITER_CHECK_RANGE | 450,963 | 0.5% | 93.7% |  |
| LOAD_CONST | 419,194 | 0.5% | 94.2% |  |
| _CHECK_PEP_523 | 377,139 | 0.4% | 94.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 377,139 | 0.4% | 95.1% |  |
| _CHECK_STACK_SPACE | 377,139 | 0.4% | 95.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 377,139 | 0.4% | 96.0% |  |
| _PUSH_FRAME | 377,139 | 0.4% | 96.5% |  |
| _SAVE_RETURN_OFFSET | 377,139 | 0.4% | 96.9% |  |
| RESUME_CHECK | 377,099 | 0.4% | 97.3% |  |
| _LOAD_ATTR | 308,322 | 0.4% | 97.7% |  |
| _ITER_NEXT_RANGE | 296,882 | 0.4% | 98.1% |  |
| BINARY_SUBSCR_LIST_INT | 282,082 | 0.3% | 98.4% |  |
| CALL_BUILTIN_CLASS | 276,322 | 0.3% | 98.7% |  |
| TO_BOOL_BOOL | 175,853 | 0.2% | 98.9% |  |
| _GUARD_IS_TRUE_POP | 168,802 | 0.2% | 99.1% | 0.0% |
| CALL_BUILTIN_FAST | 143,921 | 0.2% | 99.3% |  |
| CALL_LEN | 138,161 | 0.2% | 99.5% |  |
| POP_TOP | 80,861 | 0.1% | 99.6% |  |
| _POP_FRAME | 63,772 | 0.1% | 99.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 52,506 | 0.1% | 99.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 52,506 | 0.1% | 99.8% |  |
| _GUARD_IS_NOT_NONE_POP | 31,980 | 0.0% | 99.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 22,833 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 13,800 | 0.0% | 99.9% | 88.0% |
| _ITER_CHECK_TUPLE | 13,800 | 0.0% | 99.9% |  |
| _GUARD_IS_FALSE_POP | 10,039 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 9,372 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,440 | 0.0% | 100.0% |  |
| BEFORE_WITH | 5,073 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,756 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,660 | 0.0% | 100.0% |  |
| CONTAINS_OP | 1,616 | 0.0% | 100.0% |  |
| COPY | 1,616 | 0.0% | 100.0% |  |
| SWAP | 1,616 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,616 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 1,616 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 1,616 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 1,616 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 1,616 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 280 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 140 | 0.0% | 100.0% |  |
| IS_OP | 92 | 0.0% | 100.0% |  |
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
| LOAD_ATTR_PROPERTY | 119 |
| CALL_PY_WITH_DEFAULTS | 80 |
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
Stats gathered on: 2023-11-19
