
# Pystats results

- benchmark: concurrent_imap
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 66,674,349 | 17.2% | 17.2% |  |
| RESUME_CHECK | 27,745,599 | 7.1% | 24.3% | 0.0% |
| STORE_FAST | 21,298,145 | 5.5% | 29.8% |  |
| POP_TOP | 18,405,936 | 4.7% | 34.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,158,384 | 4.7% | 39.2% | 1.2% |
| RETURN_VALUE | 15,768,661 | 4.1% | 43.3% |  |
| POP_JUMP_IF_FALSE | 12,249,129 | 3.2% | 46.5% |  |
| LOAD_CONST | 11,800,311 | 3.0% | 49.5% |  |
| INTERPRETER_EXIT | 10,359,608 | 2.7% | 52.2% |  |
| LOAD_GLOBAL_MODULE | 9,506,406 | 2.4% | 54.6% | 0.0% |
| LOAD_FAST_LOAD_FAST | 9,446,616 | 2.4% | 57.1% |  |
| ENTER_EXECUTOR | 8,455,558 | 2.2% | 59.2% |  |
| CALL | 8,336,610 | 2.1% | 61.4% |  |
| CALL_PY_EXACT_ARGS | 7,356,551 | 1.9% | 63.3% | 0.0% |
| JUMP_BACKWARD | 7,304,231 | 1.9% | 65.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,546,950 | 1.7% | 66.8% | 1.3% |
| YIELD_VALUE | 6,529,020 | 1.7% | 68.5% |  |
| LOAD_ATTR | 6,247,616 | 1.6% | 70.1% |  |
| RETURN_CONST | 6,105,505 | 1.6% | 71.7% |  |
| NOP | 6,051,637 | 1.6% | 73.3% |  |
| FOR_ITER_GEN | 5,994,800 | 1.5% | 74.8% |  |
| COPY | 5,750,966 | 1.5% | 76.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,857,760 | 1.3% | 77.5% |  |
| LOAD_GLOBAL_BUILTIN | 4,803,653 | 1.2% | 78.8% | 0.0% |
| TO_BOOL_BOOL | 4,663,848 | 1.2% | 80.0% |  |
| PUSH_NULL | 4,586,714 | 1.2% | 81.2% |  |
| STORE_FAST_STORE_FAST | 4,235,417 | 1.1% | 82.3% |  |
| BINARY_OP | 3,674,965 | 0.9% | 83.2% |  |
| POP_JUMP_IF_NOT_NONE | 3,523,195 | 0.9% | 84.1% |  |
| BUILD_TUPLE | 3,491,365 | 0.9% | 85.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,014,702 | 0.8% | 85.8% | 6.5% |
| TO_BOOL_INT | 2,678,544 | 0.7% | 86.5% |  |
| COMPARE_OP_INT | 2,530,048 | 0.7% | 87.1% | 0.2% |
| CALL_FUNCTION_EX | 2,308,041 | 0.6% | 87.7% |  |
| POP_JUMP_IF_TRUE | 2,182,992 | 0.6% | 88.3% |  |
| CALL_PY_WITH_DEFAULTS | 1,835,403 | 0.5% | 88.8% |  |
| SWAP | 1,653,708 | 0.4% | 89.2% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,611,457 | 0.4% | 89.6% |  |
| GET_ITER | 1,533,810 | 0.4% | 90.0% |  |
| BEFORE_WITH | 1,532,868 | 0.4% | 90.4% |  |
| LOAD_ATTR_MODULE | 1,445,098 | 0.4% | 90.8% | 0.1% |
| BUILD_MAP | 1,405,110 | 0.4% | 91.1% |  |
| TO_BOOL | 1,387,574 | 0.4% | 91.5% |  |
| FOR_ITER_LIST | 1,340,730 | 0.3% | 91.8% |  |
| CALL_BUILTIN_CLASS | 1,316,110 | 0.3% | 92.2% |  |
| COMPARE_OP_STR | 1,296,184 | 0.3% | 92.5% |  |
| FOR_ITER | 1,222,620 | 0.3% | 92.8% |  |
| STORE_FAST_LOAD_FAST | 1,198,960 | 0.3% | 93.1% |  |
| JUMP_FORWARD | 1,155,994 | 0.3% | 93.4% |  |
| CONTAINS_OP | 1,143,348 | 0.3% | 93.7% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,467 | 0.3% | 94.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,101,916 | 0.3% | 94.3% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,094,027 | 0.3% | 94.6% | 0.0% |
| BINARY_OP_ADD_INT | 1,076,412 | 0.3% | 94.8% |  |
| LOAD_DEREF | 989,507 | 0.3% | 95.1% |  |
| CALL_BUILTIN_FAST | 948,849 | 0.2% | 95.3% |  |
| COPY_FREE_VARS | 941,087 | 0.2% | 95.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 913,073 | 0.2% | 95.8% |  |
| LOAD_SUPER_ATTR_METHOD | 879,647 | 0.2% | 96.1% |  |
| UNARY_INVERT | 877,533 | 0.2% | 96.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 864,608 | 0.2% | 96.5% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 829,261 | 0.2% | 96.7% | 0.0% |
| BUILD_LIST | 820,809 | 0.2% | 96.9% |  |
| POP_JUMP_IF_NONE | 714,784 | 0.2% | 97.1% |  |
| STORE_SUBSCR_DICT | 685,267 | 0.2% | 97.3% |  |
| LOAD_FAST_CHECK | 683,743 | 0.2% | 97.5% |  |
| CALL_ISINSTANCE | 617,237 | 0.2% | 97.6% |  |
| BINARY_SUBSCR | 590,878 | 0.2% | 97.8% |  |
| EXIT_INIT_CHECK | 588,240 | 0.2% | 97.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 588,240 | 0.2% | 98.1% |  |
| LOAD_ATTR_PROPERTY | 565,585 | 0.1% | 98.2% | 2.2% |
| DICT_MERGE | 561,380 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 462,546 | 0.1% | 98.6% |  |
| LOAD_FAST_AND_CLEAR | 412,937 | 0.1% | 98.7% |  |
| CALL_LEN | 374,382 | 0.1% | 98.8% |  |
| COMPARE_OP | 316,843 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 311,850 | 0.1% | 99.0% |  |
| LIST_EXTEND | 246,242 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,568 | 0.1% | 99.1% |  |
| CALL_KW | 227,667 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 225,279 | 0.1% | 99.2% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 213,933 | 0.1% | 99.3% |  |
| UNARY_NOT | 163,886 | 0.0% | 99.3% |  |
| CALL_LIST_APPEND | 149,848 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 147,947 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 138,909 | 0.0% | 99.4% |  |
| BINARY_SUBSCR_LIST_INT | 134,021 | 0.0% | 99.5% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.5% |  |
| STORE_DEREF | 132,820 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 123,062 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 109,640 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 94,538 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,591 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 75,014 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,800 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,447 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 44,847 | 0.0% | 99.9% | 13.6% |
| IS_OP | 44,241 | 0.0% | 99.9% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,040 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 37,100 | 0.0% | 99.9% |  |
| POP_EXCEPT | 35,379 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 35,379 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| IMPORT_NAME | 30,240 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 29,939 | 0.0% | 99.9% |  |
| IMPORT_FROM | 29,900 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 28,978 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 26,520 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 24,320 | 0.0% | 100.0% |  |
| BINARY_SLICE | 18,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,748 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 17,300 | 0.0% | 100.0% |  |
| RERAISE | 16,320 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 13,220 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,260 | 0.0% | 100.0% |  |
| END_FOR | 10,880 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,940 | 0.0% | 100.0% | 0.1% |
| RAISE_VARARGS | 5,460 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,440 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 2,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,660 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 800 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 520 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 505 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,666,911 | 4.3% | 4.3% |
| RESUME_CHECK LOAD_FAST | 15,722,389 | 4.1% | 8.3% |
| CACHE RESUME_CHECK | 10,283,171 | 2.6% | 11.0% |
| RETURN_VALUE INTERPRETER_EXIT | 9,215,267 | 2.4% | 13.4% |
| LOAD_FAST RETURN_VALUE | 8,293,666 | 2.1% | 15.5% |
| STORE_FAST LOAD_FAST | 8,002,549 | 2.1% | 17.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,312,551 | 1.9% | 19.5% |
| POP_TOP ENTER_EXECUTOR | 6,608,317 | 1.7% | 21.2% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.7% | 22.8% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.5% | 24.4% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.5% | 25.9% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.5% | 27.5% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.4% | 28.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,103,717 | 1.3% | 30.2% |
| ENTER_EXECUTOR YIELD_VALUE | 4,895,440 | 1.3% | 31.4% |
| POP_TOP LOAD_FAST | 4,685,034 | 1.2% | 32.6% |
| LOAD_FAST LOAD_ATTR | 4,368,177 | 1.1% | 33.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,309,171 | 1.1% | 34.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,285,856 | 1.1% | 36.0% |
| RETURN_CONST POP_TOP | 4,220,891 | 1.1% | 37.1% |
| NOP LOAD_FAST | 3,604,642 | 0.9% | 38.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,377,292 | 0.9% | 38.9% |
| LOAD_CONST LOAD_CONST | 3,127,404 | 0.8% | 39.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,043,387 | 0.8% | 40.5% |
| PUSH_NULL LOAD_FAST | 2,924,108 | 0.8% | 41.2% |
| STORE_FAST NOP | 2,785,353 | 0.7% | 41.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,761,214 | 0.7% | 42.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,749,605 | 0.7% | 43.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,678,404 | 0.7% | 44.0% |
| COPY STORE_FAST | 2,597,760 | 0.7% | 44.7% |
| STORE_FAST COPY | 2,597,440 | 0.7% | 45.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,527,659 | 0.7% | 46.0% |
| LOAD_FAST LOAD_CONST | 2,390,740 | 0.6% | 46.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,360,888 | 0.6% | 47.3% |
| LOAD_FAST PUSH_NULL | 2,247,862 | 0.6% | 47.8% |
| LOAD_CONST CALL | 2,238,556 | 0.6% | 48.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,208,915 | 0.6% | 49.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,197,702 | 0.6% | 49.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,153,084 | 0.6% | 50.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,127,144 | 0.5% | 50.7% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,103,689 | 0.5% | 51.2% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,939,299 | 0.5% | 51.7% |
| CALL STORE_FAST | 1,936,040 | 0.5% | 52.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,929,360 | 0.5% | 52.7% |
| LOAD_ATTR LOAD_FAST | 1,866,633 | 0.5% | 53.2% |
| CALL POP_TOP | 1,841,904 | 0.5% | 53.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,820,468 | 0.5% | 54.1% |
| CALL RETURN_VALUE | 1,802,437 | 0.5% | 54.6% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,641 | 0.5% | 55.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,619,227 | 0.4% | 55.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,605,397 | 0.4% | 55.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,603,275 | 0.4% | 56.3% |
| ENTER_EXECUTOR CALL | 1,590,843 | 0.4% | 56.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,501,609 | 0.4% | 57.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,481,242 | 0.4% | 57.5% |
| BINARY_OP COPY | 1,477,810 | 0.4% | 57.8% |
| COPY TO_BOOL_INT | 1,477,490 | 0.4% | 58.2% |
| POP_TOP RETURN_CONST | 1,477,147 | 0.4% | 58.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,456,655 | 0.4% | 59.0% |
| POP_TOP LOAD_CONST | 1,450,469 | 0.4% | 59.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,441,865 | 0.4% | 59.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,379,355 | 0.4% | 60.1% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,333,536 | 0.3% | 60.4% |
| LOAD_FAST TO_BOOL | 1,329,878 | 0.3% | 60.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,327,617 | 0.3% | 61.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,321,678 | 0.3% | 61.4% |
| LOAD_CONST LOAD_FAST | 1,275,079 | 0.3% | 61.8% |
| BEFORE_WITH POP_TOP | 1,265,678 | 0.3% | 62.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,264,333 | 0.3% | 62.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,261,421 | 0.3% | 62.7% |
| RETURN_VALUE STORE_FAST | 1,258,216 | 0.3% | 63.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,248,000 | 0.3% | 63.4% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,237,112 | 0.3% | 63.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,235,126 | 0.3% | 64.0% |
| LOAD_ATTR PUSH_NULL | 1,211,722 | 0.3% | 64.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,209,556 | 0.3% | 64.7% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,196,061 | 0.3% | 65.0% |
| JUMP_BACKWARD FOR_ITER | 1,191,547 | 0.3% | 65.3% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,179,726 | 0.3% | 65.6% |
| LOAD_FAST BUILD_TUPLE | 1,157,837 | 0.3% | 65.9% |
| LOAD_CONST COMPARE_OP_INT | 1,146,791 | 0.3% | 66.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,142,728 | 0.3% | 66.5% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,142,069 | 0.3% | 66.8% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,094,720 | 0.3% | 67.0% |
| POP_TOP JUMP_BACKWARD | 1,094,015 | 0.3% | 67.3% |
| BUILD_TUPLE YIELD_VALUE | 1,088,060 | 0.3% | 67.6% |
| GET_ITER FOR_ITER_LIST | 1,074,140 | 0.3% | 67.9% |
| LOAD_CONST COPY | 1,067,520 | 0.3% | 68.2% |
| COPY STORE_FAST_STORE_FAST | 1,061,440 | 0.3% | 68.4% |
| POP_TOP NOP | 1,059,715 | 0.3% | 68.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,059,373 | 0.3% | 69.0% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,056,280 | 0.3% | 69.2% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,056,220 | 0.3% | 69.5% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,055,880 | 0.3% | 69.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,049,142 | 0.3% | 70.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 1,043,660 | 0.3% | 70.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,037,530 | 0.3% | 70.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,036,168 | 0.3% | 70.9% |
| RETURN_VALUE RETURN_VALUE | 1,015,776 | 0.3% | 71.1% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 987,171 | 0.3% | 71.4% |


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
| RESUME_CHECK | 10,283,171 | 99.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,179,726 | 77.0% |
| RETURN_VALUE | 261,850 | 17.1% |
| LOAD_GLOBAL_MODULE | 79,557 | 5.2% |
| CALL | 6,040 | 0.4% |
| ENTER_EXECUTOR | 5,195 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,265,678 | 82.6% |
| STORE_FAST | 267,190 | 17.4% |


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
| LOAD_FAST_LOAD_FAST | 544,080 | 92.1% |
| LOAD_CONST | 45,879 | 7.8% |
| BINARY_SUBSCR | 839 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 92.1% |
| STORE_FAST | 45,599 | 7.7% |
| BINARY_SUBSCR | 839 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,779 | 82.8% |
| LOAD_ATTR_MODULE | 5,100 | 17.0% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,939 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,937 | 49.2% |
| CALL | 26,557 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,440 | 15.3% |
| LOAD_ATTR | 80 | 0.1% |

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
| RETURN_CONST | 588,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 588,240 | 100.0% |


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
| LOAD_FAST | 813,909 | 53.1% |
| STORE_FAST_LOAD_FAST | 544,000 | 35.5% |
| CALL_BUILTIN_CLASS | 151,561 | 9.9% |
| CALL | 12,420 | 0.8% |
| RETURN_VALUE | 5,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,074,140 | 70.0% |
| LOAD_FAST_AND_CLEAR | 274,309 | 17.9% |
| FOR_ITER_RANGE | 145,608 | 9.5% |
| FOR_ITER | 11,473 | 0.7% |
| FOR_ITER_TUPLE | 11,100 | 0.7% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,215,267 | 89.0% |
| RETURN_CONST | 599,241 | 5.8% |
| YIELD_VALUE | 545,100 | 5.3% |


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
| STORE_FAST | 2,785,353 | 46.0% |
| POP_TOP | 1,059,715 | 17.5% |
| POP_JUMP_IF_FALSE | 955,576 | 15.8% |
| RESUME_CHECK | 793,337 | 13.1% |
| POP_JUMP_IF_NOT_NONE | 268,935 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,604,642 | 59.6% |
| LOAD_GLOBAL_MODULE | 975,736 | 16.1% |
| LOAD_FAST_LOAD_FAST | 550,360 | 9.1% |
| LOAD_CONST | 529,060 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 380,239 | 6.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 18,999 | 53.7% |
| COPY | 10,880 | 30.8% |
| POP_TOP | 5,200 | 14.7% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,599 | 52.6% |
| RERAISE | 10,880 | 30.8% |
| JUMP_FORWARD | 5,120 | 14.5% |
| JUMP_BACKWARD | 700 | 2.0% |
| RETURN_CONST | 60 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 35.5% |
| RETURN_CONST | 4,220,891 | 22.9% |
| CALL | 1,841,904 | 10.0% |
| BEFORE_WITH | 1,265,678 | 6.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,043,660 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,608,317 | 35.9% |
| LOAD_FAST | 4,685,034 | 25.5% |
| RETURN_CONST | 1,477,147 | 8.0% |
| LOAD_CONST | 1,450,469 | 7.9% |
| JUMP_BACKWARD | 1,094,015 | 5.9% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,399 | 69.0% |
| RERAISE | 5,440 | 15.4% |
| CALL_KW | 5,120 | 14.5% |
| BINARY_SUBSCR_DICT | 300 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,739 | 69.9% |
| WITH_EXCEPT_START | 5,440 | 15.4% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.4% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,247,862 | 49.0% |
| LOAD_ATTR | 1,211,722 | 26.4% |
| LOAD_ATTR_MODULE | 1,037,530 | 22.6% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,924,108 | 63.8% |
| LOAD_FAST_LOAD_FAST | 713,234 | 15.5% |
| CALL | 644,310 | 14.0% |
| LOAD_CONST | 237,586 | 5.2% |
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
| LOAD_FAST | 8,293,666 | 52.6% |
| CALL | 1,802,437 | 11.4% |
| CALL_FUNCTION_EX | 1,196,061 | 7.6% |
| RETURN_VALUE | 1,015,776 | 6.4% |
| LOAD_ATTR_INSTANCE_VALUE | 873,068 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,215,267 | 58.4% |
| STORE_FAST | 1,258,216 | 8.0% |
| RETURN_VALUE | 1,015,776 | 6.4% |
| POP_TOP | 790,184 | 5.0% |
| LOAD_FAST_LOAD_FAST | 600,277 | 3.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 12,160 | 42.0% |
| LOAD_FAST | 10,438 | 36.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,480 | 18.9% |
| STORE_SUBSCR | 620 | 2.1% |
| LOAD_ATTR | 200 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 17,720 | 61.1% |
| LOAD_GLOBAL_MODULE | 10,200 | 35.2% |
| STORE_SUBSCR | 620 | 2.1% |
| STORE_SUBSCR_DICT | 259 | 0.9% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,329,878 | 95.8% |
| LOAD_ATTR_INSTANCE_VALUE | 49,935 | 3.6% |
| TO_BOOL | 3,438 | 0.2% |
| RETURN_VALUE | 921 | 0.1% |
| LOAD_ATTR | 842 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 694,650 | 50.1% |
| POP_JUMP_IF_FALSE | 686,445 | 49.5% |
| TO_BOOL | 3,438 | 0.2% |
| TO_BOOL_BOOL | 2,121 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 600,277 | 68.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 277,176 | 31.6% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 877,533 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 163,806 | 100.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 163,886 | 100.0% |


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

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,895,440 | 75.0% |
| BUILD_TUPLE | 1,088,060 | 16.7% |
| STORE_FAST_LOAD_FAST | 544,600 | 8.3% |
| CALL_STR_1 | 620 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,983,920 | 91.7% |
| INTERPRETER_EXIT | 545,100 | 8.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,939,299 | 52.8% |
| UNARY_INVERT | 877,533 | 23.9% |
| POP_JUMP_IF_FALSE | 600,277 | 16.3% |
| LOAD_ATTR | 150,808 | 4.1% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,477,810 | 40.2% |
| STORE_FAST | 751,405 | 20.4% |
| TO_BOOL_INT | 600,337 | 16.3% |
| UNARY_INVERT | 600,277 | 16.3% |
| BUILD_TUPLE | 138,628 | 3.8% |


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
| SWAP | 274,309 | 33.4% |
| JUMP_FORWARD | 261,610 | 31.9% |
| LOAD_FAST | 138,969 | 16.9% |
| POP_TOP | 122,661 | 14.9% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 278,210 | 33.9% |
| SWAP | 274,309 | 33.4% |
| STORE_FAST | 262,430 | 32.0% |
| RETURN_VALUE | 5,120 | 0.6% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 544,000 | 38.7% |
| LOAD_FAST | 528,600 | 37.6% |
| RESUME_CHECK | 271,810 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 844,770 | 60.1% |
| BUILD_TUPLE | 544,020 | 38.7% |
| STORE_FAST | 16,320 | 1.2% |


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
| LOAD_FAST | 1,157,837 | 33.2% |
| LOAD_FAST_LOAD_FAST | 1,094,720 | 31.4% |
| BUILD_MAP | 544,020 | 15.6% |
| RETURN_VALUE | 512,000 | 14.7% |
| BINARY_OP | 138,628 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 1,088,060 | 31.2% |
| CALL | 601,197 | 17.2% |
| BUILD_MAP | 544,000 | 15.6% |
| STORE_FAST | 512,000 | 14.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 14.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,238,556 | 26.9% |
| ENTER_EXECUTOR | 1,590,843 | 19.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,327,617 | 15.9% |
| LOAD_FAST_LOAD_FAST | 726,133 | 8.7% |
| PUSH_NULL | 644,310 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,936,040 | 23.2% |
| POP_TOP | 1,841,904 | 22.1% |
| RETURN_VALUE | 1,802,437 | 21.6% |
| TO_BOOL_BOOL | 681,406 | 8.2% |
| LOAD_FAST | 668,179 | 8.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,641 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,196,061 | 51.8% |
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
| LOAD_CONST | 222,547 | 97.8% |
| ENTER_EXECUTOR | 5,120 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 164,501 | 72.3% |
| LOAD_FAST | 27,200 | 11.9% |
| RETURN_VALUE | 18,240 | 8.0% |
| STORE_FAST | 12,300 | 5.4% |
| PUSH_EXC_INFO | 5,120 | 2.2% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 313,439 | 98.9% |
| COMPARE_OP | 1,156 | 0.4% |
| LOAD_GLOBAL_MODULE | 372 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 333 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 313,731 | 99.0% |
| COMPARE_OP_INT | 1,165 | 0.4% |
| COMPARE_OP | 1,156 | 0.4% |
| COMPARE_OP_STR | 432 | 0.1% |
| POP_JUMP_IF_TRUE | 279 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,142,069 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 99 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,142,728 | 99.9% |
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
| STORE_FAST | 2,597,440 | 45.2% |
| BINARY_OP | 1,477,810 | 25.7% |
| LOAD_CONST | 1,067,520 | 18.6% |
| LOAD_FAST | 554,071 | 9.6% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 45.2% |
| TO_BOOL_INT | 1,477,490 | 25.7% |
| STORE_FAST_STORE_FAST | 1,061,440 | 18.5% |
| LOAD_ATTR_INSTANCE_VALUE | 541,773 | 9.4% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 600,277 | 63.8% |
| CALL_ALLOC_AND_ENTER_INIT | 261,570 | 27.8% |
| CACHE | 73,100 | 7.8% |
| CALL | 5,620 | 0.6% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 940,427 | 99.9% |
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
| POP_TOP | 6,608,317 | 78.2% |
| POP_JUMP_IF_NOT_NONE | 756,722 | 8.9% |
| STORE_FAST_STORE_FAST | 543,320 | 6.4% |
| LIST_APPEND | 364,246 | 4.3% |
| CALL_LIST_APPEND | 137,948 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,895,440 | 57.9% |
| CALL | 1,590,843 | 18.8% |
| JUMP_BACKWARD | 543,960 | 6.4% |
| LOAD_FAST | 532,079 | 6.3% |
| CALL_PY_WITH_DEFAULTS | 338,467 | 4.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,191,547 | 97.5% |
| SWAP | 12,240 | 1.0% |
| GET_ITER | 11,473 | 0.9% |
| LOAD_FAST | 5,740 | 0.5% |
| FOR_ITER | 1,620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 641,320 | 52.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 549,280 | 44.9% |
| SWAP | 12,160 | 1.0% |
| RETURN_CONST | 11,180 | 0.9% |
| LOAD_GLOBAL_MODULE | 5,360 | 0.4% |


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
| RETURN_VALUE | 26,560 | 60.0% |
| LOAD_FAST | 16,460 | 37.2% |
| LOAD_GLOBAL_MODULE | 1,181 | 2.7% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,101 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,440,000 | 74.5% |
| POP_TOP | 1,094,015 | 15.0% |
| ENTER_EXECUTOR | 543,960 | 7.4% |
| POP_JUMP_IF_FALSE | 117,824 | 1.6% |
| LIST_APPEND | 98,300 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,983,920 | 81.9% |
| FOR_ITER | 1,191,547 | 16.3% |
| LOAD_FAST | 118,150 | 1.6% |
| FOR_ITER_LIST | 5,021 | 0.1% |
| FOR_ITER_RANGE | 2,139 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 569,728 | 49.3% |
| STORE_FAST | 569,326 | 49.2% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.5% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 835,448 | 72.3% |
| BUILD_LIST | 261,610 | 22.6% |
| LOAD_GLOBAL_MODULE | 22,577 | 2.0% |
| POP_EXCEPT | 18,999 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.6% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 225,758 | 48.8% |
| LOAD_ATTR | 138,648 | 30.0% |
| BINARY_SUBSCR_STR_INT | 97,240 | 21.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 364,246 | 78.7% |
| JUMP_BACKWARD | 98,300 | 21.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 123,441 | 50.1% |
| RETURN_VALUE | 122,661 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,981 | 49.9% |
| STORE_FAST | 122,661 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,368,177 | 69.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,501,609 | 24.0% |
| LOAD_GLOBAL_MODULE | 238,294 | 3.8% |
| CALL | 49,620 | 0.8% |
| ENTER_EXECUTOR | 31,840 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,866,633 | 29.9% |
| PUSH_NULL | 1,211,722 | 19.4% |
| POP_JUMP_IF_NOT_NONE | 611,575 | 9.8% |
| STORE_SUBSCR_DICT | 600,197 | 9.6% |
| STORE_FAST | 435,524 | 7.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,127,404 | 26.5% |
| LOAD_FAST | 2,390,740 | 20.3% |
| POP_TOP | 1,450,469 | 12.3% |
| POP_JUMP_IF_FALSE | 764,694 | 6.5% |
| LOAD_ATTR_METHOD_NO_DICT | 682,316 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,127,404 | 26.5% |
| CALL | 2,238,556 | 19.0% |
| LOAD_FAST | 1,275,079 | 10.8% |
| COMPARE_OP_INT | 1,146,791 | 9.7% |
| COPY | 1,067,520 | 9.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 934,607 | 94.5% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.7% |
| STORE_DEREF | 26,560 | 2.7% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 935,127 | 94.5% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 5.4% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,722,389 | 23.6% |
| STORE_FAST | 8,002,549 | 12.0% |
| POP_JUMP_IF_FALSE | 5,103,717 | 7.7% |
| POP_TOP | 4,685,034 | 7.0% |
| NOP | 3,604,642 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,666,911 | 25.0% |
| RETURN_VALUE | 8,293,666 | 12.4% |
| LOAD_ATTR | 4,368,177 | 6.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,309,171 | 6.5% |
| CALL_PY_EXACT_ARGS | 2,749,605 | 4.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 274,309 | 66.4% |
| LOAD_FAST_AND_CLEAR | 138,628 | 33.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 274,309 | 66.4% |
| LOAD_FAST_AND_CLEAR | 138,628 | 33.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 79.6% |
| POP_JUMP_IF_NONE | 122,982 | 18.0% |
| LOAD_ATTR_CLASS | 15,881 | 2.3% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 79.6% |
| LOAD_GLOBAL_MODULE | 122,902 | 18.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,841 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,379,355 | 14.6% |
| LOAD_FAST_LOAD_FAST | 1,321,678 | 14.0% |
| POP_JUMP_IF_FALSE | 784,994 | 8.3% |
| STORE_FAST_STORE_FAST | 771,221 | 8.2% |
| PUSH_NULL | 713,234 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,127,144 | 22.5% |
| LOAD_FAST_LOAD_FAST | 1,321,678 | 14.0% |
| BUILD_TUPLE | 1,094,720 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 906,869 | 9.6% |
| CALL | 726,133 | 7.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.3% |
| RESUME_CHECK | 1,720 | 9.7% |
| POP_JUMP_IF_FALSE | 1,711 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,765 | 38.1% |
| LOAD_ATTR | 3,321 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 2,741 | 15.4% |
| LOAD_FAST | 2,162 | 12.2% |
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
| TO_BOOL_BOOL | 3,043,387 | 24.8% |
| TO_BOOL_INT | 2,678,404 | 21.9% |
| COMPARE_OP_INT | 2,527,659 | 20.6% |
| COMPARE_OP_STR | 1,261,421 | 10.3% |
| CONTAINS_OP | 1,142,728 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,103,717 | 41.7% |
| RETURN_CONST | 2,208,915 | 18.0% |
| NOP | 955,576 | 7.8% |
| LOAD_GLOBAL_MODULE | 831,015 | 6.8% |
| LOAD_FAST_LOAD_FAST | 784,994 | 6.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 660,984 | 92.5% |
| LOAD_ATTR_INSTANCE_VALUE | 28,320 | 4.0% |
| LOAD_ATTR | 24,420 | 3.4% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 213,525 | 29.9% |
| LOAD_GLOBAL_MODULE | 172,994 | 24.2% |
| NOP | 159,621 | 22.3% |
| LOAD_FAST_CHECK | 122,982 | 17.2% |
| RETURN_CONST | 22,420 | 3.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,689 | 59.7% |
| LOAD_ATTR | 611,575 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 507,669 | 14.4% |
| RETURN_VALUE | 226,078 | 6.4% |
| LOAD_DEREF | 53,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,619,227 | 46.0% |
| ENTER_EXECUTOR | 756,722 | 21.5% |
| RETURN_CONST | 611,700 | 17.4% |
| NOP | 268,935 | 7.6% |
| LOAD_CONST | 122,941 | 3.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,456,655 | 66.7% |
| TO_BOOL | 694,650 | 31.8% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,523 | 0.5% |
| COMPARE_OP_INT | 2,005 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 907,705 | 41.6% |
| LOAD_FAST_LOAD_FAST | 695,568 | 31.9% |
| RETURN_CONST | 428,089 | 19.6% |
| LOAD_GLOBAL_MODULE | 56,937 | 2.6% |
| RETURN_VALUE | 45,559 | 2.1% |


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
| POP_JUMP_IF_FALSE | 2,208,915 | 36.2% |
| POP_TOP | 1,477,147 | 24.2% |
| STORE_ATTR_INSTANCE_VALUE | 1,248,000 | 20.4% |
| POP_JUMP_IF_NOT_NONE | 611,700 | 10.0% |
| POP_JUMP_IF_TRUE | 428,089 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,220,891 | 69.1% |
| TO_BOOL_BOOL | 614,310 | 10.1% |
| INTERPRETER_EXIT | 599,241 | 9.8% |
| EXIT_INIT_CHECK | 588,240 | 9.6% |
| STORE_FAST | 46,759 | 0.8% |


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
| LOAD_FAST | 55,680 | 58.9% |
| LOAD_FAST_LOAD_FAST | 19,800 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 16,320 | 17.3% |
| STORE_ATTR | 2,280 | 2.4% |
| LOAD_ATTR | 240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,920 | 45.4% |
| LOAD_FAST | 12,939 | 13.7% |
| LOAD_FAST_LOAD_FAST | 12,840 | 13.6% |
| LOAD_CONST | 11,680 | 12.4% |
| LOAD_GLOBAL_BUILTIN | 5,360 | 5.7% |


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
| YIELD_VALUE | 5,983,920 | 28.1% |
| COPY | 2,597,760 | 12.2% |
| CALL | 1,936,040 | 9.1% |
| RETURN_VALUE | 1,258,216 | 5.9% |
| STORE_FAST_STORE_FAST | 1,056,280 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,002,549 | 37.6% |
| JUMP_BACKWARD | 5,440,000 | 25.5% |
| NOP | 2,785,353 | 13.1% |
| COPY | 2,597,440 | 12.2% |
| LOAD_CONST | 593,681 | 2.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 641,320 | 53.5% |
| FOR_ITER_LIST | 544,620 | 45.4% |
| COPY | 12,160 | 1.0% |
| FOR_ITER_TUPLE | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 544,600 | 45.4% |
| GET_ITER | 544,000 | 45.4% |
| LOAD_FAST | 97,280 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 12,080 | 1.0% |
| TO_BOOL_STR | 860 | 0.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,605,397 | 37.9% |
| COPY | 1,061,440 | 25.1% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 24.9% |
| STORE_FAST_STORE_FAST | 512,000 | 12.1% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,333,536 | 31.5% |
| STORE_FAST | 1,056,280 | 24.9% |
| LOAD_FAST_LOAD_FAST | 771,221 | 18.2% |
| ENTER_EXECUTOR | 543,320 | 12.8% |
| STORE_FAST_STORE_FAST | 512,000 | 12.1% |


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
| BINARY_OP_ADD_INT | 541,832 | 32.8% |
| BUILD_LIST | 274,309 | 16.6% |
| LOAD_FAST_AND_CLEAR | 274,309 | 16.6% |
| ENTER_EXECUTOR | 261,189 | 15.8% |
| LOAD_FAST | 149,822 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 541,773 | 32.8% |
| LOAD_CONST | 288,450 | 17.4% |
| BUILD_LIST | 274,309 | 16.6% |
| STORE_FAST | 274,309 | 16.6% |
| FOR_ITER_LIST | 261,209 | 15.8% |


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
| LOAD_FAST | 138,869 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 138,909 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,059,373 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 159 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 541,832 | 50.3% |
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
| CALL | 122,902 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 123,062 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,894 | 76.1% |
| LOAD_CONST | 45,479 | 21.3% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 208,533 | 97.5% |
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
| LOAD_FAST_LOAD_FAST | 122,901 | 91.7% |
| LOAD_CONST | 11,000 | 8.2% |
| BINARY_SUBSCR | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 122,941 | 91.7% |
| LOAD_CONST | 10,800 | 8.1% |
| BINARY_OP_ADD_UNICODE | 280 | 0.2% |


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
| LOAD_GLOBAL_MODULE | 288,050 | 49.0% |
| LOAD_FAST | 267,630 | 45.5% |
| CALL | 32,140 | 5.5% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 326,670 | 55.5% |
| COPY_FREE_VARS | 261,570 | 44.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 71.9% |
| LOAD_CONST | 6,360 | 14.2% |
| BINARY_OP_ADD_INT | 5,360 | 12.0% |
| PUSH_NULL | 616 | 1.4% |
| CALL | 151 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,767 | 86.4% |
| POP_TOP | 5,960 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 38.9% |
| RETURN_VALUE | 374,419 | 28.4% |
| LOAD_FAST | 155,369 | 11.8% |
| CALL_BUILTIN_CLASS | 122,581 | 9.3% |
| CALL_LEN | 122,581 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 650,889 | 49.5% |
| STORE_FAST | 374,719 | 28.5% |
| GET_ITER | 151,561 | 11.5% |
| CALL_BUILTIN_CLASS | 122,581 | 9.3% |
| LOAD_FAST | 16,320 | 1.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 470,487 | 49.6% |
| LOAD_CONST | 273,821 | 28.9% |
| LOAD_FAST_LOAD_FAST | 107,094 | 11.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,207 | 5.1% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 340,262 | 35.9% |
| TO_BOOL_BOOL | 266,001 | 28.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 227,181 | 23.9% |
| UNPACK_SEQUENCE_TUPLE | 48,207 | 5.1% |
| POP_TOP | 12,778 | 1.3% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,460 | 47.1% |
| BUILD_TUPLE | 511,960 | 46.8% |
| CALL | 32,586 | 3.0% |
| LOAD_FAST_CHECK | 15,841 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,043,660 | 95.4% |
| RETURN_VALUE | 49,107 | 4.5% |
| LOAD_FAST | 620 | 0.1% |
| STORE_FAST | 440 | 0.0% |
| BEFORE_WITH | 140 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 97,200 | 88.7% |
| LOAD_FAST | 12,360 | 11.3% |
| CALL | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 97,200 | 88.7% |
| LOAD_FAST | 12,120 | 11.1% |
| STORE_FAST | 140 | 0.1% |
| TO_BOOL_INT | 140 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 616,777 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 617,057 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 347,061 | 92.7% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 7.2% |
| CALL | 381 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,774 | 55.5% |
| CALL_BUILTIN_CLASS | 122,581 | 32.7% |
| CALL_PY_EXACT_ARGS | 31,880 | 8.5% |
| LOAD_FAST | 5,400 | 1.4% |
| BINARY_OP_SUBTRACT_INT | 5,360 | 1.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 138,548 | 92.5% |
| LOAD_FAST | 10,800 | 7.2% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 137,948 | 92.1% |
| LOAD_GLOBAL_MODULE | 10,800 | 7.2% |
| JUMP_BACKWARD | 640 | 0.4% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 861,867 | 99.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 422 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600,557 | 69.5% |
| STORE_FAST | 262,291 | 30.3% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,036,168 | 94.0% |
| LOAD_ATTR_METHOD_LAZY_DICT | 64,048 | 5.8% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 49.4% |
| POP_TOP | 370,128 | 33.6% |
| LOAD_FAST | 50,180 | 4.6% |
| RETURN_VALUE | 48,722 | 4.4% |
| CALL_BUILTIN_FAST | 48,207 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 757,502 | 91.3% |
| LOAD_CONST | 30,200 | 3.6% |
| CALL | 27,539 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 785,181 | 94.7% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,377,292 | 45.9% |
| LOAD_FAST | 2,749,605 | 37.4% |
| LOAD_FAST_LOAD_FAST | 678,861 | 9.2% |
| LOAD_SUPER_ATTR_METHOD | 261,530 | 3.6% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,312,551 | 99.4% |
| MAKE_CELL | 26,840 | 0.4% |
| RETURN_GENERATOR | 16,820 | 0.2% |
| COPY_FREE_VARS | 320 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 918,467 | 50.0% |
| ENTER_EXECUTOR | 338,467 | 18.4% |
| LOAD_ATTR_MODULE | 261,730 | 14.3% |
| LOAD_FAST | 187,668 | 10.2% |
| LOAD_CONST | 73,431 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,235,126 | 67.3% |
| COPY_FREE_VARS | 600,277 | 32.7% |


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
| LOAD_CONST | 1,146,791 | 45.3% |
| LOAD_ATTR_INSTANCE_VALUE | 800,627 | 31.6% |
| LOAD_FAST | 544,980 | 21.5% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.7% |
| CALL_BUILTIN_FAST | 12,080 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,527,659 | 99.9% |
| POP_JUMP_IF_TRUE | 2,005 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 84 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,237,112 | 95.4% |
| LOAD_CONST | 53,140 | 4.1% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 432 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,261,421 | 97.3% |
| COPY | 12,120 | 0.9% |
| LOAD_FAST | 12,120 | 0.9% |
| POP_JUMP_IF_TRUE | 10,523 | 0.8% |


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
| GET_ITER | 1,074,140 | 80.1% |
| SWAP | 261,209 | 19.5% |
| JUMP_BACKWARD | 5,021 | 0.4% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 544,620 | 40.6% |
| STORE_FAST | 392,203 | 29.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 277,236 | 20.7% |
| LOAD_FAST | 124,062 | 9.3% |
| SWAP | 960 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 145,608 | 98.4% |
| JUMP_BACKWARD | 2,139 | 1.4% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 147,067 | 99.4% |
| RETURN_CONST | 480 | 0.3% |
| LOAD_FAST | 400 | 0.3% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,100 | 84.0% |
| SWAP | 860 | 6.5% |
| LOAD_FAST | 620 | 4.7% |
| JUMP_BACKWARD | 600 | 4.5% |
| FOR_ITER | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,860 | 89.7% |
| STORE_FAST_LOAD_FAST | 860 | 6.5% |
| RETURN_CONST | 480 | 3.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 48,167 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.5% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,566 | 72.8% |
| LOAD_FAST_CHECK | 15,881 | 27.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,666,911 | 91.8% |
| LOAD_FAST_LOAD_FAST | 906,869 | 5.0% |
| COPY | 541,773 | 3.0% |
| LOAD_ATTR_INSTANCE_VALUE | 21,305 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,285,856 | 23.6% |
| LOAD_FAST | 2,761,214 | 15.2% |
| LOAD_ATTR | 1,501,609 | 8.3% |
| LOAD_GLOBAL_MODULE | 1,264,333 | 7.0% |
| BEFORE_WITH | 1,179,726 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,388 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,534 | 39.8% |
| CALL | 81,986 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,048 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,285,856 | 88.2% |
| LOAD_FAST | 444,726 | 9.2% |
| LOAD_ATTR | 50,998 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,603,275 | 33.0% |
| CALL | 1,327,617 | 27.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,036,168 | 21.3% |
| LOAD_CONST | 682,316 | 14.0% |
| LOAD_FAST_LOAD_FAST | 179,584 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,309,171 | 65.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,049,142 | 16.0% |
| LOAD_FAST_LOAD_FAST | 600,197 | 9.2% |
| BINARY_SUBSCR | 543,920 | 8.3% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,377,292 | 51.6% |
| LOAD_FAST | 1,481,242 | 22.6% |
| CALL_PY_WITH_DEFAULTS | 918,467 | 14.0% |
| LOAD_FAST_LOAD_FAST | 610,720 | 9.3% |
| LOAD_CONST | 90,311 | 1.4% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,441,865 | 99.8% |
| LOAD_ATTR | 2,813 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,037,530 | 71.8% |
| CALL_PY_WITH_DEFAULTS | 261,730 | 18.1% |
| STORE_DEREF | 53,120 | 3.7% |
| LOAD_CONST | 31,040 | 2.1% |
| LOAD_FAST | 27,840 | 1.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 635,677 | 69.6% |
| LOAD_FAST_LOAD_FAST | 277,096 | 30.3% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,237 | 65.7% |
| UNARY_INVERT | 277,176 | 30.4% |
| RETURN_VALUE | 12,120 | 1.3% |
| LOAD_CONST | 12,120 | 1.3% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.6% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 302,851 | 53.5% |
| ENTER_EXECUTOR | 235,114 | 41.6% |
| RETURN_VALUE | 26,480 | 4.7% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 553,205 | 97.8% |
| TO_BOOL_BOOL | 12,160 | 2.1% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,740 | 99.9% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 49,520 | 80.1% |
| CALL_BUILTIN_FAST | 12,220 | 19.8% |
| CALL | 40 | 0.1% |
| LOAD_ATTR | 40 | 0.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,153,084 | 44.8% |
| LOAD_GLOBAL_BUILTIN | 757,122 | 15.8% |
| LOAD_FAST | 640,217 | 13.3% |
| STORE_FAST | 537,685 | 11.2% |
| NOP | 380,239 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,360,888 | 49.1% |
| LOAD_DEREF | 934,607 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 757,122 | 15.8% |
| CALL_ISINSTANCE | 616,777 | 12.8% |
| LOAD_GLOBAL_MODULE | 43,000 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,197,702 | 23.1% |
| RESUME_CHECK | 1,820,468 | 19.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,264,333 | 13.3% |
| NOP | 975,736 | 10.3% |
| POP_JUMP_IF_FALSE | 831,015 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,939,299 | 20.4% |
| LOAD_ATTR_MODULE | 1,441,865 | 15.2% |
| LOAD_FAST_LOAD_FAST | 1,379,355 | 14.5% |
| COMPARE_OP_STR | 1,237,112 | 13.0% |
| LOAD_FAST | 1,209,556 | 12.7% |


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
| LOAD_FAST | 879,447 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 612,637 | 69.6% |
| CALL_PY_EXACT_ARGS | 261,530 | 29.7% |
| LOAD_FAST | 5,440 | 0.6% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,283,171 | 37.1% |
| CALL_PY_EXACT_ARGS | 7,312,551 | 26.4% |
| FOR_ITER_GEN | 5,983,920 | 21.6% |
| CALL_PY_WITH_DEFAULTS | 1,235,126 | 4.5% |
| COPY_FREE_VARS | 940,427 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,722,389 | 56.7% |
| POP_TOP | 6,528,880 | 23.5% |
| LOAD_GLOBAL_BUILTIN | 2,153,084 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,820,468 | 6.6% |
| NOP | 793,337 | 2.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,929,360 | 64.0% |
| SWAP | 541,773 | 18.0% |
| LOAD_FAST_LOAD_FAST | 507,630 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,248,000 | 41.4% |
| LOAD_FAST | 853,732 | 28.3% |
| LOAD_GLOBAL_MODULE | 461,190 | 15.3% |
| LOAD_CONST | 203,980 | 6.8% |
| LOAD_FAST_LOAD_FAST | 121,160 | 4.0% |


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
| LOAD_ATTR | 600,197 | 87.6% |
| LOAD_FAST | 41,251 | 6.0% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.8% |
| CALL | 10,200 | 1.5% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 602,787 | 88.0% |
| RETURN_CONST | 29,000 | 4.2% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.9% |
| LOAD_CONST | 26,520 | 3.9% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 55.4% |
| COPY | 185 | 36.6% |
| TO_BOOL | 40 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 59.4% |
| POP_JUMP_IF_FALSE | 205 | 40.6% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 987,171 | 21.2% |
| CALL | 681,406 | 14.6% |
| LOAD_FAST | 667,559 | 14.3% |
| CALL_ISINSTANCE | 617,057 | 13.2% |
| RETURN_CONST | 614,310 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,043,387 | 65.3% |
| POP_JUMP_IF_TRUE | 1,456,655 | 31.2% |
| UNARY_NOT | 163,806 | 3.5% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,477,490 | 55.2% |
| BINARY_OP | 600,337 | 22.4% |
| LOAD_FAST | 600,197 | 22.4% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,678,404 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 272,390 | 87.3% |
| LOAD_ATTR_INSTANCE_VALUE | 39,240 | 12.6% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 311,690 | 99.9% |
| POP_JUMP_IF_TRUE | 160 | 0.1% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,059 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,819 | 92.2% |
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
| CALL_BUILTIN_FAST | 48,207 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,247 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 549,280 | 34.1% |
| LOAD_FAST_CHECK | 543,920 | 33.8% |
| FOR_ITER_LIST | 277,236 | 17.2% |
| CALL_BUILTIN_FAST | 227,181 | 14.1% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,605,397 | 99.6% |
| LOAD_FAST | 6,040 | 0.4% |
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
|     deferred | 3,668,818 | 68.5% |
|          hit | 1,678,216 | 31.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 599 | 9.7% |
| Failure | 5,548 | 90.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,724 | 49.1% |
| or | 1,417 | 25.5% |
| remainder | 727 | 13.1% |
| add different types | 600 | 10.8% |
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
|     deferred | 589,799 | 61.0% |
|          hit | 375,701 | 38.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 22.2% |
| Failure | 839 | 77.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 839 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,299,802 | 31.7% |
|          hit | 17,861,466 | 68.2% |
|         miss | 7,540 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,150 | 24.9% |
| Failure | 27,658 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,278 | 26.3% |
| cfunc noargs | 5,528 | 20.0% |
| class no vectorcall | 3,780 | 13.7% |
| meth descr varargs keywords | 3,055 | 11.0% |
| class mutable | 1,109 | 4.0% |
| other | 1,100 | 4.0% |
| cfunc varargs | 1,040 | 3.8% |
| bound method | 1,039 | 3.8% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 769 | 2.8% |
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
|     deferred | 314,006 | 7.6% |
|          hit | 3,820,585 | 92.2% |
|         miss | 5,787 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,597 | 56.3% |
| Failure | 1,240 | 43.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 758 | 61.1% |
| big int | 340 | 27.4% |
| different types | 142 | 11.5% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,220,380 | 14.0% |
|          hit | 7,496,697 | 86.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 27.7% |
| Failure | 1,620 | 72.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 500 | 30.9% |
| enumerate | 500 | 30.9% |
| itertools | 380 | 23.5% |
| callable | 240 | 14.8% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,206,819 | 15.9% |
|          hit | 32,540,431 | 83.2% |
|         miss | 309,254 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,137 | 54.3% |
| Failure | 18,660 | 45.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,304 | 23.1% |
| shadowed | 3,891 | 20.9% |
| not managed dict | 3,205 | 17.2% |
| non overriding descriptor | 2,256 | 12.1% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.0% |
| metaclass attribute | 900 | 4.8% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 424 | 2.3% |
| mutable class | 260 | 1.4% |
| overridden | 60 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,333 | 0.1% |
|        deopt | 100 | 0.0% |
|          hit | 14,307,512 | 99.9% |
|         miss | 2,547 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,515 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 934,607 | 99.9% |

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
|     deferred | 84,399 | 2.7% |
|          hit | 2,880,422 | 90.8% |
|         miss | 196,100 | 6.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,859 | 77.5% |
| Failure | 2,280 | 22.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 1,080 | 47.4% |
| class attr simple | 520 | 22.8% |
| not in keys | 440 | 19.3% |
| no dict | 240 | 10.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 28,099 | 3.9% |
|          hit | 685,267 | 95.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 259 | 29.5% |
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
|     deferred | 1,381,175 | 14.9% |
|          hit | 7,881,406 | 85.0% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,961 | 46.3% |
| Failure | 3,438 | 53.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 999 | 29.1% |
| sequence | 839 | 24.4% |
| set | 700 | 20.4% |
| tuple | 700 | 20.4% |
| other | 200 | 5.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 2,715,924 | 100.0% |

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
| Basic | 226,082,838 | 58.3% |
| Not specialized | 40,634,650 | 10.5% |
| Specialized hits | 120,858,541 | 31.1% |
| Specialized misses | 521,513 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,299,802 | 38.1% |
| LOAD_ATTR | 6,206,819 | 28.5% |
| BINARY_OP | 3,668,818 | 16.8% |
| TO_BOOL | 1,381,175 | 6.3% |
| FOR_ITER | 1,220,380 | 5.6% |
| BINARY_SUBSCR | 589,799 | 2.7% |
| COMPARE_OP | 314,006 | 1.4% |
| STORE_ATTR | 84,399 | 0.4% |
| STORE_SUBSCR | 28,099 | 0.1% |
| LOAD_GLOBAL | 8,333 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 213,806 | 41.0% |
| STORE_ATTR_INSTANCE_VALUE | 196,100 | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 81,968 | 15.7% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,080 | 1.2% |
| COMPARE_OP_INT | 5,767 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,207 | 0.4% |
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
| Calls to PyEval_EvalDefault | 10,365,071 | 37.3% |
| Calls to Python functions inlined | 17,403,728 | 62.7% |
| Calls via PyEval_EvalFrame (total) | 10,365,071 | 37.3% |
| Calls via PyEval_EvalFrame (vector) | 9,813,551 | 35.3% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 2.0% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 9,812,851 | 35.3% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.9% |
| Calls via PyEval_EvalFrame (api) | 389,212 | 1.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 35,503 | 0.1% |
| Frames pushed | 11,028,589 | 39.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 13,646,306 | 40.4% |
| Frees to freelist | 13,658,278 |  |
| Allocations | 20,115,793 | 59.6% |
| Allocations to 512 bytes | 19,932,758 | 59.0% |
| Allocations to 4 kbytes | 83,518 | 0.2% |
| Allocations over 4 kbytes | 99,517 | 0.3% |
| Frees | 20,912,601 |  |
| New values | 80,340 |  |
| Interpreter increfs | 168,925,183 | 78.6% |
| Interpreter decrefs | 183,265,107 | 74.6% |
| Increfs | 45,880,178 | 21.4% |
| Decrefs | 62,345,150 | 25.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 7,073,719 |  |
| Method cache misses | 45,896 |  |
| Method cache collisions | 60,515 |  |
| Method cache dunder hits | 8,744,001 |  |
| Method cache dunder misses | 18,537 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 31 | 465 | 232,408 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 429,412 |  |
| Traces created | 614 | 0.1% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 428,798 | 99.9% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 8,455,558 |  |
| Uops executed | 78,724,953 | 9.31 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 13.0% |
| <= 16 | 79 | 12.9% |
| <= 32 | 340 | 55.4% |
| <= 64 | 80 | 13.0% |
| <= 128 | 35 | 5.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 40 | 6.5% |
| <= 8 | 40 | 6.5% |
| <= 16 | 159 | 25.9% |
| <= 32 | 320 | 52.1% |
| <= 64 | 35 | 5.7% |
| <= 128 | 20 | 3.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 1,023,360 | 12.1% |
| <= 8 | 1,350,806 | 16.0% |
| <= 16 | 5,566,465 | 65.8% |
| <= 32 | 514,383 | 6.1% |
| <= 64 | 442 | 0.0% |
| <= 128 | 72 | 0.0% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 1 | 0.0% |
| <= 2,048 | 1 | 0.0% |
| <= 4,096 | 10 | 0.0% |
| <= 8,192 | 18 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 351,960 |
| FOR_ITER | 69,960 |
| LOAD_ATTR | 6,958 |
| CALL | 160 |
| LOAD_ATTR_PROPERTY | 79 |
| YIELD_VALUE | 60 |
| TO_BOOL | 40 |
| CALL_KW | 40 |
| CALL_PY_WITH_DEFAULTS | 40 |
| BEFORE_WITH | 20 |


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
Stats gathered on: 2023-11-02
