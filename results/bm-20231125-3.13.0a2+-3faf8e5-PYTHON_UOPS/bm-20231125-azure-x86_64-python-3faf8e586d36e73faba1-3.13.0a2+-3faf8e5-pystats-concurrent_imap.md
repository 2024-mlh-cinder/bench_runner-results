
# Pystats results

- benchmark: concurrent_imap
- fork: python
- ref: 3faf8e586d36e73faba13d9b61663afed6a24cb4
- commit hash: 3faf8e5
- commit date: 2023-11-25T15:40:19-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 70,003,522 | 17.6% | 17.6% |  |
| RESUME_CHECK | 28,711,409 | 7.2% | 24.7% | 0.0% |
| STORE_FAST | 21,748,819 | 5.5% | 30.2% |  |
| POP_TOP | 19,049,752 | 4.8% | 35.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,001,774 | 4.8% | 39.7% | 1.1% |
| RETURN_VALUE | 16,656,259 | 4.2% | 43.9% |  |
| POP_JUMP_IF_FALSE | 13,191,826 | 3.3% | 47.2% |  |
| LOAD_CONST | 12,128,671 | 3.0% | 50.3% |  |
| INTERPRETER_EXIT | 10,556,610 | 2.6% | 52.9% |  |
| LOAD_GLOBAL_MODULE | 10,293,255 | 2.6% | 55.5% | 0.0% |
| ENTER_EXECUTOR | 9,975,140 | 2.5% | 58.0% |  |
| CALL | 8,654,415 | 2.2% | 60.2% |  |
| LOAD_FAST_LOAD_FAST | 8,469,402 | 2.1% | 62.3% |  |
| CALL_PY_EXACT_ARGS | 7,803,716 | 2.0% | 64.2% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,010,188 | 1.8% | 66.0% | 1.2% |
| YIELD_VALUE | 6,529,020 | 1.6% | 67.6% |  |
| LOAD_ATTR | 6,518,470 | 1.6% | 69.3% |  |
| RETURN_CONST | 6,492,548 | 1.6% | 70.9% |  |
| NOP | 6,461,585 | 1.6% | 72.5% |  |
| JUMP_BACKWARD | 5,999,453 | 1.5% | 74.0% |  |
| FOR_ITER_GEN | 5,994,800 | 1.5% | 75.5% |  |
| COPY | 5,965,212 | 1.5% | 77.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,046,864 | 1.3% | 78.3% |  |
| TO_BOOL_BOOL | 4,931,656 | 1.2% | 79.5% |  |
| LOAD_GLOBAL_BUILTIN | 4,847,537 | 1.2% | 80.7% | 0.0% |
| PUSH_NULL | 4,506,668 | 1.1% | 81.9% |  |
| BINARY_OP | 4,194,689 | 1.1% | 82.9% |  |
| STORE_FAST_STORE_FAST | 3,769,051 | 0.9% | 83.9% |  |
| POP_JUMP_IF_NOT_NONE | 3,722,459 | 0.9% | 84.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,332,470 | 0.8% | 85.6% | 7.4% |
| TO_BOOL_INT | 3,072,810 | 0.8% | 86.4% |  |
| COMPARE_OP_INT | 2,652,847 | 0.7% | 87.1% | 0.3% |
| BUILD_TUPLE | 2,523,035 | 0.6% | 87.7% |  |
| CALL_FUNCTION_EX | 2,307,973 | 0.6% | 88.3% |  |
| POP_JUMP_IF_TRUE | 2,228,175 | 0.6% | 88.8% |  |
| FOR_ITER_LIST | 2,208,459 | 0.6% | 89.4% |  |
| CALL_PY_WITH_DEFAULTS | 1,977,911 | 0.5% | 89.9% |  |
| SWAP | 1,796,267 | 0.5% | 90.3% |  |
| BEFORE_WITH | 1,579,817 | 0.4% | 90.7% |  |
| LOAD_ATTR_MODULE | 1,552,209 | 0.4% | 91.1% | 0.1% |
| TO_BOOL | 1,404,251 | 0.4% | 91.5% |  |
| COMPARE_OP_STR | 1,314,131 | 0.3% | 91.8% |  |
| JUMP_FORWARD | 1,242,148 | 0.3% | 92.1% |  |
| CONTAINS_OP | 1,232,246 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 1,154,602 | 0.3% | 92.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,152,192 | 0.3% | 93.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,145,091 | 0.3% | 93.3% |  |
| LOAD_DEREF | 1,114,957 | 0.3% | 93.6% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,422 | 0.3% | 93.8% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,093,982 | 0.3% | 94.1% | 0.0% |
| BINARY_OP_ADD_INT | 1,075,686 | 0.3% | 94.4% |  |
| COPY_FREE_VARS | 1,066,537 | 0.3% | 94.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,038,470 | 0.3% | 94.9% |  |
| CALL_BUILTIN_FAST | 1,020,278 | 0.3% | 95.2% |  |
| LOAD_SUPER_ATTR_METHOD | 1,005,097 | 0.3% | 95.4% |  |
| UNARY_INVERT | 1,002,930 | 0.3% | 95.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 990,088 | 0.2% | 95.9% | 0.0% |
| GET_ITER | 986,782 | 0.2% | 96.2% |  |
| BUILD_LIST | 928,282 | 0.2% | 96.4% |  |
| BUILD_MAP | 903,017 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 827,344 | 0.2% | 96.8% | 0.0% |
| POP_JUMP_IF_NONE | 784,658 | 0.2% | 97.0% |  |
| STORE_SUBSCR_DICT | 775,645 | 0.2% | 97.2% |  |
| CALL_ISINSTANCE | 706,860 | 0.2% | 97.4% |  |
| LOAD_FAST_CHECK | 701,615 | 0.2% | 97.6% |  |
| EXIT_INIT_CHECK | 659,894 | 0.2% | 97.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 659,894 | 0.2% | 97.9% |  |
| LOAD_ATTR_PROPERTY | 637,264 | 0.2% | 98.1% | 1.9% |
| BINARY_SUBSCR | 590,328 | 0.1% | 98.2% |  |
| DICT_MERGE | 561,380 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 516,297 | 0.1% | 98.6% |  |
| LOAD_FAST_AND_CLEAR | 466,643 | 0.1% | 98.7% |  |
| COMPARE_OP | 353,914 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 347,677 | 0.1% | 98.9% |  |
| LIST_EXTEND | 282,106 | 0.1% | 99.0% |  |
| CALL_LEN | 257,696 | 0.1% | 99.1% |  |
| CALL_KW | 245,721 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,388 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 225,228 | 0.1% | 99.2% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 213,293 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 181,822 | 0.0% | 99.3% |  |
| CALL_LIST_APPEND | 167,735 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 156,804 | 0.0% | 99.4% |  |
| UNARY_NOT | 156,446 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 141,002 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 136,160 | 0.0% | 99.5% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.6% |  |
| STORE_DEREF | 132,820 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 95,262 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,588 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 75,012 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 63,600 | 0.0% | 99.7% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,800 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,402 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 44,851 | 0.0% | 99.8% | 13.5% |
| IS_OP | 44,171 | 0.0% | 99.8% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 38,560 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,040 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 37,100 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| POP_EXCEPT | 34,829 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 34,829 | 0.0% | 99.9% |  |
| FOR_ITER | 33,480 | 0.0% | 99.9% |  |
| IMPORT_NAME | 30,240 | 0.0% | 99.9% |  |
| IMPORT_FROM | 29,900 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 29,389 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 28,980 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 26,520 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 25,360 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 24,320 | 0.0% | 100.0% |  |
| BINARY_SLICE | 18,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,854 | 0.0% | 100.0% |  |
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
| TO_BOOL_ALWAYS_TRUE | 456 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,384,741 | 4.4% | 4.4% |
| RESUME_CHECK LOAD_FAST | 16,383,876 | 4.1% | 8.5% |
| CACHE RESUME_CHECK | 10,480,174 | 2.6% | 11.1% |
| RETURN_VALUE INTERPRETER_EXIT | 9,376,445 | 2.4% | 13.4% |
| LOAD_FAST RETURN_VALUE | 8,652,031 | 2.2% | 15.6% |
| STORE_FAST LOAD_FAST | 8,384,746 | 2.1% | 17.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,759,716 | 1.9% | 19.7% |
| POP_TOP ENTER_EXECUTOR | 7,241,547 | 1.8% | 21.5% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.6% | 23.1% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.5% | 24.6% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.5% | 26.1% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.5% | 27.6% |
| ENTER_EXECUTOR YIELD_VALUE | 5,971,280 | 1.5% | 29.1% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.4% | 30.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,439,157 | 1.4% | 31.8% |
| POP_TOP LOAD_FAST | 4,977,833 | 1.2% | 33.1% |
| LOAD_FAST LOAD_ATTR | 4,753,234 | 1.2% | 34.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,653,417 | 1.2% | 35.4% |
| RETURN_CONST POP_TOP | 4,477,005 | 1.1% | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,459,103 | 1.1% | 37.7% |
| NOP LOAD_FAST | 3,835,463 | 1.0% | 38.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,664,612 | 0.9% | 39.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,291,310 | 0.8% | 40.4% |
| LOAD_CONST LOAD_CONST | 3,232,771 | 0.8% | 41.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,072,670 | 0.8% | 42.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,990,225 | 0.7% | 42.7% |
| STORE_FAST NOP | 2,927,048 | 0.7% | 43.5% |
| PUSH_NULL LOAD_FAST | 2,893,112 | 0.7% | 44.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,886,059 | 0.7% | 44.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,650,478 | 0.7% | 45.6% |
| COPY STORE_FAST | 2,597,760 | 0.7% | 46.2% |
| STORE_FAST COPY | 2,597,440 | 0.7% | 46.9% |
| LOAD_FAST LOAD_CONST | 2,532,116 | 0.6% | 47.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,502,328 | 0.6% | 48.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,423,411 | 0.6% | 48.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,368,157 | 0.6% | 49.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,332,195 | 0.6% | 49.9% |
| LOAD_CONST CALL | 2,263,320 | 0.6% | 50.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,226,055 | 0.6% | 51.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,210,906 | 0.6% | 51.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,155,774 | 0.5% | 52.1% |
| LOAD_FAST PUSH_NULL | 2,096,560 | 0.5% | 52.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,091,115 | 0.5% | 53.2% |
| CALL STORE_FAST | 2,025,021 | 0.5% | 53.7% |
| LOAD_ATTR LOAD_FAST | 1,963,967 | 0.5% | 54.2% |
| CALL RETURN_VALUE | 1,892,060 | 0.5% | 54.7% |
| CALL POP_TOP | 1,865,813 | 0.5% | 55.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,865,022 | 0.5% | 55.6% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,573 | 0.4% | 56.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,726,928 | 0.4% | 56.5% |
| BINARY_OP COPY | 1,692,830 | 0.4% | 56.9% |
| COPY TO_BOOL_INT | 1,692,510 | 0.4% | 57.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,688,608 | 0.4% | 57.7% |
| ENTER_EXECUTOR CALL | 1,675,034 | 0.4% | 58.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,659,103 | 0.4% | 58.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,576,533 | 0.4% | 59.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,548,968 | 0.4% | 59.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,537,413 | 0.4% | 59.7% |
| POP_TOP RETURN_CONST | 1,528,655 | 0.4% | 60.1% |
| POP_TOP LOAD_CONST | 1,502,066 | 0.4% | 60.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,483,940 | 0.4% | 60.9% |
| RETURN_VALUE STORE_FAST | 1,401,354 | 0.4% | 61.2% |
| LOAD_CONST LOAD_FAST | 1,396,571 | 0.4% | 61.6% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,391,308 | 0.3% | 61.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,369,310 | 0.3% | 62.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,352,901 | 0.3% | 62.6% |
| LOAD_FAST TO_BOOL | 1,346,462 | 0.3% | 62.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,326,007 | 0.3% | 63.3% |
| ENTER_EXECUTOR FOR_ITER_LIST | 1,298,258 | 0.3% | 63.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,288,011 | 0.3% | 63.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,282,204 | 0.3% | 64.3% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,279,353 | 0.3% | 64.6% |
| BEFORE_WITH POP_TOP | 1,276,800 | 0.3% | 64.9% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,255,053 | 0.3% | 65.2% |
| LOAD_FAST BUILD_TUPLE | 1,247,460 | 0.3% | 65.5% |
| LOAD_CONST COMPARE_OP_INT | 1,235,532 | 0.3% | 65.8% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,231,626 | 0.3% | 66.1% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,230,966 | 0.3% | 66.4% |
| LOAD_ATTR PUSH_NULL | 1,211,659 | 0.3% | 66.7% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,195,993 | 0.3% | 67.0% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,179,724 | 0.3% | 67.3% |
| RETURN_VALUE RETURN_VALUE | 1,159,064 | 0.3% | 67.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,139,031 | 0.3% | 67.9% |
| POP_TOP NOP | 1,130,893 | 0.3% | 68.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,108,849 | 0.3% | 68.5% |
| NOP LOAD_GLOBAL_MODULE | 1,101,104 | 0.3% | 68.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,096,834 | 0.3% | 69.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,086,517 | 0.3% | 69.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,078,445 | 0.3% | 69.6% |
| LOAD_CONST COPY | 1,067,520 | 0.3% | 69.8% |
| COPY_FREE_VARS RESUME_CHECK | 1,065,877 | 0.3% | 70.1% |
| COPY STORE_FAST_STORE_FAST | 1,061,440 | 0.3% | 70.4% |
| LOAD_DEREF LOAD_FAST | 1,060,577 | 0.3% | 70.6% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,060,057 | 0.3% | 70.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,058,646 | 0.3% | 71.2% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,056,280 | 0.3% | 71.4% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,056,220 | 0.3% | 71.7% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,055,880 | 0.3% | 72.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 1,043,660 | 0.3% | 72.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,033,026 | 0.3% | 72.5% |


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
| RESUME_CHECK | 10,480,174 | 99.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,179,724 | 74.7% |
| RETURN_VALUE | 297,677 | 18.8% |
| LOAD_GLOBAL_MODULE | 79,556 | 5.0% |
| LOAD_FAST | 16,320 | 1.0% |
| CALL | 6,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,276,800 | 80.8% |
| STORE_FAST | 303,017 | 19.2% |


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
| LOAD_FAST_LOAD_FAST | 544,080 | 92.2% |
| LOAD_CONST | 45,329 | 7.7% |
| BINARY_SUBSCR | 839 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 92.1% |
| STORE_FAST | 45,049 | 7.6% |
| BINARY_SUBSCR | 839 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,229 | 82.4% |
| LOAD_ATTR_MODULE | 5,100 | 17.4% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,389 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,936 | 49.2% |
| CALL | 26,556 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,439 | 15.2% |
| LOAD_ATTR | 81 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,556 | 78.1% |
| RETURN_CONST | 10,236 | 13.6% |
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
| RETURN_CONST | 659,894 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 659,894 | 100.0% |


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
| LOAD_FAST | 921,382 | 93.4% |
| CALL_BUILTIN_CLASS | 34,980 | 3.5% |
| CALL | 12,420 | 1.3% |
| STORE_FAST_LOAD_FAST | 6,080 | 0.6% |
| RETURN_VALUE | 5,440 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 607,874 | 61.6% |
| LOAD_FAST_AND_CLEAR | 310,128 | 31.4% |
| FOR_ITER_RANGE | 29,028 | 2.9% |
| FOR_ITER | 11,472 | 1.2% |
| FOR_ITER_TUPLE | 11,100 | 1.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,376,445 | 88.8% |
| RETURN_CONST | 635,065 | 6.0% |
| YIELD_VALUE | 545,100 | 5.2% |


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
| STORE_FAST | 2,927,048 | 45.3% |
| POP_TOP | 1,130,893 | 17.5% |
| POP_JUMP_IF_FALSE | 1,009,334 | 15.6% |
| RESUME_CHECK | 882,960 | 13.7% |
| POP_JUMP_IF_NOT_NONE | 304,697 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,835,463 | 59.4% |
| LOAD_GLOBAL_MODULE | 1,101,104 | 17.0% |
| LOAD_FAST_LOAD_FAST | 550,360 | 8.5% |
| LOAD_CONST | 529,060 | 8.2% |
| LOAD_GLOBAL_BUILTIN | 433,998 | 6.7% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 18,449 | 53.0% |
| COPY | 10,880 | 31.2% |
| POP_TOP | 5,200 | 14.9% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,049 | 51.8% |
| RERAISE | 10,880 | 31.2% |
| JUMP_FORWARD | 5,120 | 14.7% |
| JUMP_BACKWARD | 700 | 2.0% |
| RETURN_CONST | 60 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 34.3% |
| RETURN_CONST | 4,477,005 | 23.5% |
| CALL | 1,865,813 | 9.8% |
| BEFORE_WITH | 1,276,800 | 6.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,043,660 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,241,547 | 38.0% |
| LOAD_FAST | 4,977,833 | 26.1% |
| RETURN_CONST | 1,528,655 | 8.0% |
| LOAD_CONST | 1,502,066 | 7.9% |
| NOP | 1,130,893 | 5.9% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 23,849 | 68.5% |
| RERAISE | 5,440 | 15.6% |
| CALL_KW | 5,120 | 14.7% |
| BINARY_SUBSCR_DICT | 300 | 0.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,189 | 69.5% |
| WITH_EXCEPT_START | 5,440 | 15.6% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.6% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,096,560 | 46.5% |
| LOAD_ATTR | 1,211,659 | 26.9% |
| LOAD_ATTR_MODULE | 1,108,849 | 24.6% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,893,112 | 64.2% |
| LOAD_FAST_LOAD_FAST | 713,144 | 15.8% |
| CALL | 595,429 | 13.2% |
| LOAD_CONST | 237,490 | 5.3% |
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
| LOAD_FAST | 8,652,031 | 51.9% |
| CALL | 1,892,060 | 11.4% |
| CALL_FUNCTION_EX | 1,195,993 | 7.2% |
| RETURN_VALUE | 1,159,064 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 980,562 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,376,445 | 56.3% |
| STORE_FAST | 1,401,354 | 8.4% |
| RETURN_VALUE | 1,159,064 | 7.0% |
| POP_TOP | 897,144 | 5.4% |
| LOAD_FAST_LOAD_FAST | 689,900 | 4.1% |


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
| LOAD_FAST | 1,346,462 | 95.9% |
| LOAD_ATTR_INSTANCE_VALUE | 49,975 | 3.6% |
| TO_BOOL | 3,439 | 0.2% |
| LOAD_ATTR | 888 | 0.1% |
| RETURN_VALUE | 767 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 712,583 | 50.7% |
| POP_JUMP_IF_FALSE | 685,184 | 48.8% |
| TO_BOOL | 3,439 | 0.2% |
| TO_BOOL_BOOL | 2,165 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 689,900 | 68.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 312,950 | 31.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,002,930 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 156,406 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 156,446 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,226,055 | 53.1% |
| UNARY_INVERT | 1,002,930 | 23.9% |
| POP_JUMP_IF_FALSE | 689,900 | 16.4% |
| LOAD_ATTR | 168,695 | 4.0% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,692,830 | 40.4% |
| STORE_FAST | 858,915 | 20.5% |
| TO_BOOL_INT | 689,960 | 16.4% |
| UNARY_INVERT | 689,900 | 16.4% |
| BUILD_TUPLE | 156,515 | 3.7% |


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
| SWAP | 310,128 | 33.4% |
| JUMP_FORWARD | 297,437 | 32.0% |
| LOAD_FAST | 156,864 | 16.9% |
| POP_TOP | 140,593 | 15.1% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 314,037 | 33.8% |
| SWAP | 310,128 | 33.4% |
| STORE_FAST | 298,257 | 32.1% |
| RETURN_VALUE | 5,120 | 0.6% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 528,600 | 58.5% |
| RESUME_CHECK | 307,637 | 34.1% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 3.6% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.8% |
| POP_TOP | 6,080 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 880,597 | 97.5% |
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
| LOAD_FAST | 1,247,460 | 49.4% |
| LOAD_FAST_LOAD_FAST | 556,800 | 22.1% |
| RETURN_VALUE | 512,000 | 20.3% |
| BINARY_OP | 156,515 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 21,600 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 690,820 | 27.4% |
| YIELD_VALUE | 550,140 | 21.8% |
| STORE_FAST | 512,000 | 20.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 20.3% |
| CALL_LIST_APPEND | 156,435 | 6.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,263,320 | 26.2% |
| ENTER_EXECUTOR | 1,675,034 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,326,007 | 15.3% |
| LOAD_FAST_LOAD_FAST | 815,773 | 9.4% |
| BUILD_TUPLE | 690,820 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,025,021 | 23.4% |
| RETURN_VALUE | 1,892,060 | 21.9% |
| POP_TOP | 1,865,813 | 21.6% |
| LOAD_FAST | 748,501 | 8.6% |
| TO_BOOL_BOOL | 680,120 | 7.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,573 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,195,993 | 51.8% |
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
| LOAD_CONST | 240,590 | 97.9% |
| ENTER_EXECUTOR | 5,131 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 182,433 | 74.2% |
| LOAD_FAST | 27,200 | 11.1% |
| RETURN_VALUE | 18,240 | 7.4% |
| STORE_FAST | 12,300 | 5.0% |
| PUSH_EXC_INFO | 5,120 | 2.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 349,233 | 98.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,484 | 0.4% |
| COMPARE_OP | 1,248 | 0.4% |
| LOAD_GLOBAL_MODULE | 378 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 350,677 | 99.1% |
| COMPARE_OP | 1,248 | 0.4% |
| COMPARE_OP_INT | 1,193 | 0.3% |
| COMPARE_OP_STR | 438 | 0.1% |
| POP_JUMP_IF_TRUE | 278 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,230,966 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,231,626 | 99.9% |
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
| STORE_FAST | 2,597,440 | 43.5% |
| BINARY_OP | 1,692,830 | 28.4% |
| LOAD_CONST | 1,067,520 | 17.9% |
| LOAD_FAST | 553,346 | 9.3% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 43.5% |
| TO_BOOL_INT | 1,692,510 | 28.4% |
| STORE_FAST_STORE_FAST | 1,061,440 | 17.8% |
| LOAD_ATTR_INSTANCE_VALUE | 541,046 | 9.1% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 689,900 | 64.7% |
| CALL_ALLOC_AND_ENTER_INIT | 297,397 | 27.9% |
| CACHE | 73,100 | 6.9% |
| CALL | 5,620 | 0.5% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,065,877 | 99.9% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,588 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,392 | 66.7% |
| RETURN_CONST | 26,556 | 32.5% |
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
| POP_TOP | 7,241,547 | 72.6% |
| POP_JUMP_IF_NOT_NONE | 792,586 | 7.9% |
| STORE_FAST_STORE_FAST | 548,100 | 5.5% |
| FOR_ITER_LIST | 543,320 | 5.4% |
| LIST_APPEND | 514,597 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,971,280 | 59.9% |
| CALL | 1,675,034 | 16.8% |
| FOR_ITER_LIST | 1,298,258 | 13.0% |
| CALL_PY_WITH_DEFAULTS | 429,072 | 4.3% |
| LOAD_ATTR_PROPERTY | 405,505 | 4.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,240 | 36.6% |
| GET_ITER | 11,472 | 34.3% |
| LOAD_FAST | 5,740 | 17.1% |
| JUMP_BACKWARD | 3,108 | 9.3% |
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
| RETURN_VALUE | 26,560 | 60.1% |
| LOAD_FAST | 16,460 | 37.3% |
| LOAD_GLOBAL_MODULE | 1,111 | 2.5% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,031 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,440,000 | 90.7% |
| POP_TOP | 550,469 | 9.2% |
| LIST_APPEND | 1,700 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 1,340 | 0.0% |
| STORE_FAST_STORE_FAST | 1,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,983,920 | 99.7% |
| FOR_ITER_LIST | 4,939 | 0.1% |
| FOR_ITER | 3,108 | 0.1% |
| FOR_ITER_RANGE | 2,161 | 0.0% |
| LOAD_FAST | 1,688 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 639,917 | 51.5% |
| POP_TOP | 585,291 | 47.1% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.4% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 886,326 | 71.4% |
| BUILD_LIST | 297,437 | 23.9% |
| LOAD_GLOBAL_MODULE | 22,576 | 1.8% |
| POP_EXCEPT | 18,449 | 1.5% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 261,622 | 50.7% |
| LOAD_ATTR | 156,535 | 30.3% |
| BINARY_SUBSCR_STR_INT | 97,240 | 18.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 514,597 | 99.7% |
| JUMP_BACKWARD | 1,700 | 0.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 141,373 | 50.1% |
| RETURN_VALUE | 140,593 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,913 | 50.0% |
| STORE_FAST | 140,593 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,753,234 | 72.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,537,413 | 23.6% |
| LOAD_GLOBAL_MODULE | 121,561 | 1.9% |
| CALL | 49,620 | 0.8% |
| LOAD_ATTR | 20,736 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,963,967 | 30.1% |
| PUSH_NULL | 1,211,659 | 18.6% |
| STORE_SUBSCR_DICT | 689,820 | 10.6% |
| POP_JUMP_IF_NOT_NONE | 651,344 | 10.0% |
| STORE_FAST | 471,161 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,232,771 | 26.7% |
| LOAD_FAST | 2,532,116 | 20.9% |
| POP_TOP | 1,502,066 | 12.4% |
| POP_JUMP_IF_FALSE | 782,540 | 6.5% |
| LOAD_ATTR_METHOD_NO_DICT | 681,124 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,232,771 | 26.7% |
| CALL | 2,263,320 | 18.7% |
| LOAD_FAST | 1,396,571 | 11.5% |
| COMPARE_OP_INT | 1,235,532 | 10.2% |
| COPY | 1,067,520 | 8.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,060,057 | 95.1% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.4% |
| STORE_DEREF | 26,560 | 2.4% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,060,577 | 95.1% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 4.8% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,383,876 | 23.4% |
| STORE_FAST | 8,384,746 | 12.0% |
| POP_JUMP_IF_FALSE | 5,439,157 | 7.8% |
| POP_TOP | 4,977,833 | 7.1% |
| NOP | 3,835,463 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,384,741 | 24.8% |
| RETURN_VALUE | 8,652,031 | 12.4% |
| LOAD_ATTR | 4,753,234 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,653,417 | 6.6% |
| CALL_PY_EXACT_ARGS | 2,990,225 | 4.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 310,128 | 66.5% |
| LOAD_FAST_AND_CLEAR | 156,515 | 33.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 310,128 | 66.5% |
| LOAD_FAST_AND_CLEAR | 156,515 | 33.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 77.6% |
| POP_JUMP_IF_NONE | 140,922 | 20.1% |
| LOAD_ATTR_CLASS | 15,813 | 2.3% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 77.5% |
| LOAD_GLOBAL_MODULE | 140,842 | 20.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,773 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,576,533 | 18.6% |
| POP_JUMP_IF_FALSE | 893,260 | 10.5% |
| LOAD_FAST_LOAD_FAST | 756,800 | 8.9% |
| POP_JUMP_IF_TRUE | 713,455 | 8.4% |
| PUSH_NULL | 713,144 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,091,115 | 24.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,033,026 | 12.2% |
| CALL | 815,773 | 9.6% |
| LOAD_FAST_LOAD_FAST | 756,800 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 689,820 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,704 | 9.5% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,819 | 38.2% |
| LOAD_ATTR | 3,326 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,743 | 15.4% |
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
| TO_BOOL_BOOL | 3,291,310 | 24.9% |
| TO_BOOL_INT | 3,072,670 | 23.3% |
| COMPARE_OP_INT | 2,650,478 | 20.1% |
| COMPARE_OP_STR | 1,279,353 | 9.7% |
| CONTAINS_OP | 1,231,626 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,439,157 | 41.2% |
| RETURN_CONST | 2,332,195 | 17.7% |
| NOP | 1,009,334 | 7.7% |
| LOAD_GLOBAL_MODULE | 920,636 | 7.0% |
| LOAD_FAST_LOAD_FAST | 893,260 | 6.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,538 | 91.1% |
| LOAD_ATTR_INSTANCE_VALUE | 44,600 | 5.7% |
| LOAD_ATTR | 24,460 | 3.1% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,646 | 29.3% |
| LOAD_GLOBAL_MODULE | 190,840 | 24.3% |
| NOP | 177,553 | 22.6% |
| LOAD_FAST_CHECK | 140,922 | 18.0% |
| RETURN_CONST | 22,420 | 2.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,155,774 | 57.9% |
| LOAD_ATTR | 651,344 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 579,215 | 15.6% |
| RETURN_VALUE | 261,942 | 7.0% |
| LOAD_DEREF | 53,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,688,608 | 45.4% |
| ENTER_EXECUTOR | 792,586 | 21.3% |
| RETURN_CONST | 651,991 | 17.5% |
| NOP | 304,697 | 8.2% |
| LOAD_CONST | 140,873 | 3.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,483,940 | 66.6% |
| TO_BOOL | 712,583 | 32.0% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,538 | 0.5% |
| COMPARE_OP_INT | 1,956 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 907,487 | 40.7% |
| LOAD_FAST_LOAD_FAST | 713,455 | 32.0% |
| RETURN_CONST | 456,747 | 20.5% |
| LOAD_GLOBAL_MODULE | 56,349 | 2.5% |
| RETURN_VALUE | 45,009 | 2.0% |


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
| POP_JUMP_IF_FALSE | 2,332,195 | 35.9% |
| POP_TOP | 1,528,655 | 23.5% |
| STORE_ATTR_INSTANCE_VALUE | 1,391,308 | 21.4% |
| POP_JUMP_IF_NOT_NONE | 651,991 | 10.0% |
| POP_JUMP_IF_TRUE | 456,747 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,477,005 | 69.0% |
| EXIT_INIT_CHECK | 659,894 | 10.2% |
| TO_BOOL_BOOL | 638,151 | 9.8% |
| INTERPRETER_EXIT | 635,065 | 9.8% |
| STORE_FAST | 46,209 | 0.7% |


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
| LOAD_FAST | 56,322 | 59.1% |
| LOAD_FAST_LOAD_FAST | 19,800 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,320 | 17.1% |
| STORE_ATTR | 2,360 | 2.5% |
| LOAD_ATTR | 240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,920 | 45.1% |
| LOAD_FAST | 12,980 | 13.6% |
| LOAD_FAST_LOAD_FAST | 12,840 | 13.5% |
| LOAD_CONST | 12,001 | 12.6% |
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
| YIELD_VALUE | 5,983,920 | 27.5% |
| COPY | 2,597,760 | 11.9% |
| CALL | 2,025,021 | 9.3% |
| RETURN_VALUE | 1,401,354 | 6.4% |
| STORE_FAST_STORE_FAST | 1,056,280 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,384,746 | 38.6% |
| JUMP_BACKWARD | 5,440,000 | 25.0% |
| NOP | 2,927,048 | 13.5% |
| COPY | 2,597,440 | 11.9% |
| JUMP_FORWARD | 639,917 | 2.9% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,139,031 | 30.2% |
| COPY | 1,061,440 | 28.2% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 28.0% |
| STORE_FAST_STORE_FAST | 512,000 | 13.6% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,369,310 | 36.3% |
| STORE_FAST | 1,056,280 | 28.0% |
| ENTER_EXECUTOR | 548,100 | 14.5% |
| STORE_FAST_STORE_FAST | 512,000 | 13.6% |
| LOAD_FAST_LOAD_FAST | 269,081 | 7.1% |


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
| BINARY_OP_ADD_INT | 541,106 | 30.1% |
| BUILD_LIST | 310,128 | 17.3% |
| LOAD_FAST_AND_CLEAR | 310,128 | 17.3% |
| FOR_ITER_LIST | 297,108 | 16.5% |
| LOAD_FAST | 167,762 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 541,046 | 30.1% |
| LOAD_CONST | 324,277 | 18.1% |
| BUILD_LIST | 310,128 | 17.3% |
| STORE_FAST | 310,128 | 17.3% |
| FOR_ITER_LIST | 297,028 | 16.5% |


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
| LOAD_FAST | 156,764 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 156,804 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,058,646 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 541,106 | 50.3% |
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
| CALL | 140,842 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 141,002 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,804 | 76.3% |
| LOAD_CONST | 44,929 | 21.1% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,893 | 97.5% |
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
| LOAD_GLOBAL_MODULE | 323,877 | 49.1% |
| LOAD_FAST | 303,457 | 46.0% |
| CALL | 32,140 | 4.9% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 362,497 | 54.9% |
| COPY_FREE_VARS | 297,397 | 45.1% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 71.9% |
| LOAD_CONST | 6,360 | 14.2% |
| BINARY_OP_ADD_INT | 5,360 | 12.0% |
| PUSH_NULL | 633 | 1.4% |
| CALL | 158 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,791 | 86.5% |
| POP_TOP | 5,960 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 44.3% |
| RETURN_VALUE | 428,178 | 37.1% |
| LOAD_FAST | 173,264 | 15.0% |
| LOAD_CONST | 12,360 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 10,260 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 668,784 | 57.9% |
| STORE_FAST | 428,478 | 37.1% |
| GET_ITER | 34,980 | 3.0% |
| LOAD_FAST | 16,320 | 1.4% |
| CALL_BUILTIN_CLASS | 6,000 | 0.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 524,119 | 51.4% |
| LOAD_CONST | 291,753 | 28.6% |
| LOAD_FAST_LOAD_FAST | 107,004 | 10.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,162 | 4.7% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 358,059 | 35.1% |
| TO_BOOL_BOOL | 283,933 | 27.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 262,961 | 25.8% |
| UNPACK_SEQUENCE_TUPLE | 48,162 | 4.7% |
| POP_TOP | 12,743 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,460 | 47.1% |
| BUILD_TUPLE | 511,960 | 46.8% |
| CALL | 32,609 | 3.0% |
| LOAD_FAST_CHECK | 15,773 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,043,660 | 95.4% |
| RETURN_VALUE | 49,062 | 4.5% |
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
| LOAD_GLOBAL_BUILTIN | 706,400 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 706,680 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,373 | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 10.5% |
| CALL | 383 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,684 | 80.6% |
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
| BUILD_TUPLE | 156,435 | 93.3% |
| LOAD_FAST | 10,800 | 6.4% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 155,835 | 92.9% |
| LOAD_GLOBAL_MODULE | 10,800 | 6.4% |
| JUMP_BACKWARD | 640 | 0.4% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 987,317 | 99.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 451 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 690,180 | 69.7% |
| STORE_FAST | 298,148 | 30.1% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,086,517 | 94.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 63,935 | 5.5% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 47.2% |
| POP_TOP | 421,135 | 36.6% |
| LOAD_FAST | 50,180 | 4.4% |
| RETURN_VALUE | 48,586 | 4.2% |
| CALL_BUILTIN_FAST | 48,162 | 4.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 755,584 | 91.3% |
| LOAD_CONST | 30,200 | 3.7% |
| CALL | 27,540 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 783,264 | 94.7% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,664,612 | 47.0% |
| LOAD_FAST | 2,990,225 | 38.3% |
| LOAD_FAST_LOAD_FAST | 562,280 | 7.2% |
| LOAD_SUPER_ATTR_METHOD | 297,357 | 3.8% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,759,716 | 99.4% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 916,698 | 46.3% |
| ENTER_EXECUTOR | 429,072 | 21.7% |
| LOAD_ATTR_MODULE | 297,557 | 15.0% |
| LOAD_FAST | 205,555 | 10.4% |
| LOAD_CONST | 73,386 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,288,011 | 65.1% |
| COPY_FREE_VARS | 689,900 | 34.9% |


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
| LOAD_CONST | 1,235,532 | 46.6% |
| LOAD_ATTR_INSTANCE_VALUE | 834,706 | 31.5% |
| LOAD_FAST | 544,980 | 20.5% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.6% |
| CALL_BUILTIN_FAST | 12,080 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,650,478 | 99.9% |
| POP_JUMP_IF_TRUE | 1,956 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 113 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,255,053 | 95.5% |
| LOAD_CONST | 53,140 | 4.0% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 438 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,279,353 | 97.4% |
| COPY | 12,120 | 0.9% |
| LOAD_FAST | 12,120 | 0.9% |
| POP_JUMP_IF_TRUE | 10,538 | 0.8% |


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
| ENTER_EXECUTOR | 1,298,258 | 58.8% |
| GET_ITER | 607,874 | 27.5% |
| SWAP | 297,028 | 13.4% |
| JUMP_BACKWARD | 4,939 | 0.2% |
| FOR_ITER | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 594,874 | 26.9% |
| ENTER_EXECUTOR | 543,320 | 24.6% |
| STORE_FAST | 445,927 | 20.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 313,010 | 14.2% |
| SWAP | 297,108 | 13.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 150,433 | 82.7% |
| GET_ITER | 29,028 | 16.0% |
| JUMP_BACKWARD | 2,161 | 1.2% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,753 | 77.4% |
| STORE_FAST | 30,509 | 16.8% |
| RETURN_CONST | 10,560 | 5.8% |


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
| LOAD_GLOBAL_MODULE | 48,122 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.5% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,589 | 72.9% |
| LOAD_FAST_CHECK | 15,813 | 27.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,384,741 | 91.5% |
| LOAD_FAST_LOAD_FAST | 1,033,026 | 5.4% |
| COPY | 541,046 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 21,255 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,459,103 | 23.5% |
| LOAD_FAST | 2,886,059 | 15.2% |
| LOAD_ATTR | 1,537,413 | 8.1% |
| LOAD_GLOBAL_MODULE | 1,282,204 | 6.7% |
| CONTAINS_OP | 1,230,966 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,208 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,444 | 39.8% |
| CALL | 82,009 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 63,935 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,459,103 | 88.4% |
| LOAD_FAST | 460,541 | 9.1% |
| LOAD_ATTR | 51,040 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,726,928 | 34.2% |
| CALL | 1,326,007 | 26.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,086,517 | 21.5% |
| LOAD_CONST | 681,124 | 13.5% |
| LOAD_FAST_LOAD_FAST | 197,488 | 3.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,653,417 | 66.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,078,445 | 15.4% |
| LOAD_FAST_LOAD_FAST | 689,820 | 9.8% |
| BINARY_SUBSCR | 543,920 | 7.8% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,664,612 | 52.3% |
| LOAD_FAST | 1,659,103 | 23.7% |
| CALL_PY_WITH_DEFAULTS | 916,698 | 13.1% |
| LOAD_FAST_LOAD_FAST | 610,720 | 8.7% |
| LOAD_CONST | 90,266 | 1.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,548,968 | 99.8% |
| LOAD_ATTR | 2,821 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,108,849 | 71.4% |
| CALL_PY_WITH_DEFAULTS | 297,557 | 19.2% |
| STORE_DEREF | 53,120 | 3.4% |
| LOAD_CONST | 31,040 | 2.0% |
| LOAD_FAST | 27,840 | 1.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 725,300 | 69.8% |
| LOAD_FAST_LOAD_FAST | 312,870 | 30.1% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 689,860 | 66.4% |
| UNARY_INVERT | 312,950 | 30.1% |
| RETURN_VALUE | 12,120 | 1.2% |
| LOAD_CONST | 12,120 | 1.2% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 405,505 | 63.6% |
| LOAD_FAST | 204,139 | 32.0% |
| RETURN_VALUE | 26,480 | 4.2% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 624,884 | 98.1% |
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
| RESUME_CHECK | 2,368,157 | 48.9% |
| LOAD_FAST | 729,840 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.8% |
| STORE_FAST | 456,841 | 9.4% |
| NOP | 433,998 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,423,411 | 50.0% |
| LOAD_DEREF | 1,060,057 | 21.9% |
| CALL_ISINSTANCE | 706,400 | 14.6% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.8% |
| LOAD_GLOBAL_MODULE | 43,000 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,502,328 | 24.3% |
| RESUME_CHECK | 1,865,022 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,282,204 | 12.5% |
| NOP | 1,101,104 | 10.7% |
| POP_JUMP_IF_FALSE | 920,636 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,226,055 | 21.6% |
| LOAD_FAST_LOAD_FAST | 1,576,533 | 15.3% |
| LOAD_ATTR_MODULE | 1,548,968 | 15.0% |
| LOAD_FAST | 1,352,901 | 13.1% |
| COMPARE_OP_STR | 1,255,053 | 12.2% |


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
| LOAD_FAST | 1,004,897 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 702,260 | 69.9% |
| CALL_PY_EXACT_ARGS | 297,357 | 29.6% |
| LOAD_FAST | 5,440 | 0.5% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,480,174 | 36.5% |
| CALL_PY_EXACT_ARGS | 7,759,716 | 27.0% |
| FOR_ITER_GEN | 5,983,920 | 20.8% |
| CALL_PY_WITH_DEFAULTS | 1,288,011 | 4.5% |
| COPY_FREE_VARS | 1,065,877 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,383,876 | 57.1% |
| POP_TOP | 6,528,880 | 22.7% |
| LOAD_GLOBAL_BUILTIN | 2,368,157 | 8.2% |
| LOAD_GLOBAL_MODULE | 1,865,022 | 6.5% |
| NOP | 882,960 | 3.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,210,906 | 66.3% |
| LOAD_FAST_LOAD_FAST | 543,457 | 16.3% |
| SWAP | 541,046 | 16.2% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,391,308 | 41.8% |
| LOAD_FAST | 879,526 | 26.4% |
| LOAD_GLOBAL_MODULE | 523,497 | 15.7% |
| LOAD_CONST | 289,419 | 8.7% |
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
| LOAD_ATTR | 689,820 | 88.9% |
| LOAD_FAST | 42,005 | 5.4% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.2% |
| CALL | 10,200 | 1.3% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 693,165 | 89.4% |
| RETURN_CONST | 29,000 | 3.7% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.5% |
| LOAD_CONST | 26,520 | 3.4% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,096,834 | 22.2% |
| CALL_ISINSTANCE | 706,680 | 14.3% |
| CALL | 680,120 | 13.8% |
| LOAD_FAST | 667,009 | 13.5% |
| RETURN_CONST | 638,151 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,291,310 | 66.7% |
| POP_JUMP_IF_TRUE | 1,483,940 | 30.1% |
| UNARY_NOT | 156,406 | 3.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,692,510 | 55.1% |
| BINARY_OP | 689,960 | 22.5% |
| LOAD_FAST | 689,820 | 22.4% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,072,670 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 308,217 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 39,240 | 11.3% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 347,517 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,008 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,768 | 92.2% |
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
| CALL_BUILTIN_FAST | 48,162 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,202 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_CHECK | 543,920 | 47.5% |
| FOR_ITER_LIST | 313,010 | 27.3% |
| CALL_BUILTIN_FAST | 262,961 | 23.0% |
| FOR_ITER | 11,360 | 1.0% |
| CALL | 7,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,139,031 | 99.5% |
| LOAD_FAST | 6,040 | 0.5% |
| STORE_DEREF | 20 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 61.4% |
| COPY | 136 | 29.8% |
| TO_BOOL | 40 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 65.8% |
| POP_JUMP_IF_FALSE | 156 | 34.2% |


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
|     deferred | 4,188,432 | 70.9% |
|          hit | 1,712,685 | 29.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 9.6% |
| Failure | 5,657 | 90.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,793 | 49.4% |
| or | 1,462 | 25.8% |
| remainder | 722 | 12.8% |
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
|     deferred | 589,249 | 69.4% |
|          hit | 259,120 | 30.5% |

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
|     deferred | 8,617,176 | 31.6% |
|          hit | 18,623,900 | 68.3% |
|         miss | 7,520 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,287 | 24.9% |
| Failure | 27,952 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,283 | 26.1% |
| cfunc noargs | 5,795 | 20.7% |
| class no vectorcall | 3,780 | 13.5% |
| meth descr varargs keywords | 3,052 | 10.9% |
| class mutable | 1,131 | 4.0% |
| other | 1,100 | 3.9% |
| bound method | 1,040 | 3.7% |
| cfunc varargs | 1,020 | 3.6% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 791 | 2.8% |
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
|     deferred | 350,922 | 8.1% |
|          hit | 3,959,764 | 91.6% |
|         miss | 7,354 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,631 | 54.5% |
| Failure | 1,361 | 45.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 760 | 55.8% |
| big int | 340 | 25.0% |
| different types | 261 | 19.2% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,940 | 0.4% |
|          hit | 8,410,441 | 99.6% |

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
|     deferred | 6,477,548 | 15.7% |
|          hit | 34,341,934 | 83.4% |
|         miss | 309,225 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,432 | 54.8% |
| Failure | 18,490 | 45.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,314 | 23.3% |
| shadowed | 3,909 | 21.1% |
| not managed dict | 3,273 | 17.7% |
| non overriding descriptor | 1,980 | 10.7% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.1% |
| metaclass attribute | 900 | 4.9% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 434 | 2.3% |
| mutable class | 260 | 1.4% |
| overridden | 60 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,381 | 0.1% |
|        deopt | 100 | 0.0% |
|          hit | 15,137,827 | 99.9% |
|         miss | 2,965 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,573 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,060,057 | 100.0% |

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
|     deferred | 83,921 | 2.4% |
|          hit | 3,149,030 | 90.2% |
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
|     deferred | 28,100 | 3.5% |
|          hit | 775,645 | 96.4% |

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
|     deferred | 1,397,807 | 14.0% |
|          hit | 8,579,207 | 85.9% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,005 | 46.6% |
| Failure | 3,439 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,000 | 29.1% |
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
|          hit | 2,249,513 | 100.0% |

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
| Basic | 229,534,063 | 57.5% |
| Not specialized | 41,864,941 | 10.5% |
| Specialized hits | 126,905,217 | 31.8% |
| Specialized misses | 572,608 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,617,176 | 39.6% |
| LOAD_ATTR | 6,477,548 | 29.7% |
| BINARY_OP | 4,188,432 | 19.2% |
| TO_BOOL | 1,397,807 | 6.4% |
| BINARY_SUBSCR | 589,249 | 2.7% |
| COMPARE_OP | 350,922 | 1.6% |
| STORE_ATTR | 83,921 | 0.4% |
| FOR_ITER | 31,940 | 0.1% |
| STORE_SUBSCR | 28,100 | 0.1% |
| LOAD_GLOBAL | 8,381 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.8% |
| LOAD_ATTR_INSTANCE_VALUE | 213,785 | 37.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 81,960 | 14.3% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.2% |
| COMPARE_OP_INT | 7,334 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,625 | 0.5% |
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
| Calls to PyEval_EvalDefault | 10,562,074 | 36.8% |
| Calls to Python functions inlined | 18,172,575 | 63.2% |
| Calls via PyEval_EvalFrame (total) | 10,562,074 | 36.8% |
| Calls via PyEval_EvalFrame (vector) | 10,010,554 | 34.8% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 1.9% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 10,009,854 | 34.8% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.9% |
| Calls via PyEval_EvalFrame (api) | 425,074 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 34,951 | 0.1% |
| Frames pushed | 12,134,115 | 42.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,350,281 | 40.8% |
| Frees to freelist | 14,362,349 |  |
| Allocations | 20,834,963 | 59.2% |
| Allocations to 512 bytes | 20,651,773 | 58.7% |
| Allocations to 4 kbytes | 83,667 | 0.2% |
| Allocations over 4 kbytes | 99,523 | 0.3% |
| Frees | 21,721,106 |  |
| New values | 80,340 |  |
| Interpreter increfs | 179,156,472 | 78.7% |
| Interpreter decrefs | 194,609,686 | 74.9% |
| Increfs | 48,601,720 | 21.3% |
| Decrefs | 65,179,377 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 7,821,234 |  |
| Method cache misses | 27,485 |  |
| Method cache collisions | 61,850 |  |
| Method cache dunder hits | 9,079,407 |  |
| Method cache dunder misses | 38,152 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 29 | 435 | 215,662 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,197 |  |
| Traces created | 797 | 19.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 3,400 | 81.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 9,975,140 |  |
| Uops executed | 84,074,882 | 8.43 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 143 | 17.9% |
| <= 32 | 420 | 52.7% |
| <= 64 | 80 | 10.0% |
| <= 128 | 134 | 16.8% |
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
| <= 8 | 63 | 7.9% |
| <= 16 | 340 | 42.7% |
| <= 32 | 140 | 17.6% |
| <= 64 | 54 | 6.8% |
| <= 128 | 120 | 15.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,322,526 | 13.3% |
| <= 4 | 1,186,642 | 11.9% |
| <= 8 | 4,895,889 | 49.1% |
| <= 16 | 1,446,774 | 14.5% |
| <= 32 | 951,355 | 9.5% |
| <= 64 | 5,538 | 0.1% |
| <= 128 | 166,371 | 1.7% |
| <= 256 | 3 | 0.0% |
| <= 512 | 1 | 0.0% |
| <= 1,024 | 3 | 0.0% |
| <= 2,048 | 6 | 0.0% |
| <= 4,096 | 8 | 0.0% |
| <= 8,192 | 24 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 14,402,846 | 17.1% | 17.1% |  |
| _EXIT_TRACE | 8,486,202 | 10.1% | 27.2% |  |
| STORE_FAST | 8,374,178 | 10.0% | 37.2% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 7,270,257 | 8.6% | 45.8% | 17.9% |
| _ITER_CHECK_LIST | 7,270,257 | 8.6% | 54.5% |  |
| _ITER_NEXT_LIST | 5,971,999 | 7.1% | 61.6% |  |
| _SET_IP | 5,740,969 | 6.8% | 68.4% |  |
| _CHECK_VALIDITY | 5,289,456 | 6.3% | 74.7% |  |
| _GUARD_GLOBALS_VERSION | 2,165,498 | 2.6% | 77.3% |  |
| PUSH_NULL | 1,783,045 | 2.1% | 79.4% |  |
| _FOR_ITER_TIER_TWO | 1,188,440 | 1.4% | 80.8% | 2.4% |
| _GUARD_BUILTINS_VERSION | 1,087,172 | 1.3% | 82.1% |  |
| _LOAD_GLOBAL_BUILTINS | 1,087,172 | 1.3% | 83.4% |  |
| BUILD_TUPLE | 1,081,040 | 1.3% | 84.7% |  |
| _LOAD_GLOBAL_MODULE | 1,078,326 | 1.3% | 86.0% |  |
| _CHECK_ATTR_MODULE | 936,188 | 1.1% | 87.1% |  |
| _LOAD_ATTR_MODULE | 936,188 | 1.1% | 88.2% |  |
| GET_ITER | 672,473 | 0.8% | 89.0% |  |
| _GUARD_TYPE_VERSION | 572,776 | 0.7% | 89.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 538,380 | 0.6% | 90.3% |  |
| BUILD_MAP | 537,920 | 0.6% | 91.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 498,211 | 0.6% | 91.5% |  |
| _GUARD_KEYS_VERSION | 498,211 | 0.6% | 92.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 498,211 | 0.6% | 92.7% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 440,019 | 0.5% | 93.3% | 34.2% |
| _ITER_CHECK_RANGE | 440,019 | 0.5% | 93.8% |  |
| LOAD_CONST | 410,134 | 0.5% | 94.3% |  |
| _CHECK_PEP_523 | 369,885 | 0.4% | 94.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 369,885 | 0.4% | 95.1% |  |
| _CHECK_STACK_SPACE | 369,885 | 0.4% | 95.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 369,885 | 0.4% | 96.0% |  |
| _PUSH_FRAME | 369,885 | 0.4% | 96.5% |  |
| _SAVE_RETURN_OFFSET | 369,885 | 0.4% | 96.9% |  |
| RESUME_CHECK | 369,845 | 0.4% | 97.3% |  |
| _LOAD_ATTR | 301,026 | 0.4% | 97.7% |  |
| _ITER_NEXT_RANGE | 289,586 | 0.3% | 98.0% |  |
| BINARY_SUBSCR_LIST_INT | 274,786 | 0.3% | 98.4% |  |
| CALL_BUILTIN_CLASS | 269,026 | 0.3% | 98.7% |  |
| TO_BOOL_BOOL | 172,198 | 0.2% | 98.9% |  |
| _GUARD_IS_TRUE_POP | 166,475 | 0.2% | 99.1% | 0.0% |
| CALL_BUILTIN_FAST | 140,273 | 0.2% | 99.3% |  |
| CALL_LEN | 134,513 | 0.2% | 99.4% |  |
| POP_TOP | 82,128 | 0.1% | 99.5% |  |
| _POP_FRAME | 63,765 | 0.1% | 99.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 59,912 | 0.1% | 99.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 59,912 | 0.1% | 99.7% |  |
| _GUARD_IS_NOT_NONE_POP | 31,980 | 0.0% | 99.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 23,919 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 13,800 | 0.0% | 99.9% | 88.0% |
| _ITER_CHECK_TUPLE | 13,800 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 11,819 | 0.0% | 99.9% |  |
| _GUARD_IS_FALSE_POP | 9,922 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,440 | 0.0% | 99.9% |  |
| BEFORE_WITH | 5,129 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,974 | 0.0% | 100.0% |  |
| CONTAINS_OP | 2,834 | 0.0% | 100.0% |  |
| COPY | 2,834 | 0.0% | 100.0% |  |
| SWAP | 2,834 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,834 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 2,834 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 2,834 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 2,834 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 2,834 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,660 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 280 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 140 | 0.0% | 100.0% |  |
| IS_OP | 85 | 0.0% | 100.0% |  |
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
| CALL_KW | 44 |
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
Stats gathered on: 2023-11-26
