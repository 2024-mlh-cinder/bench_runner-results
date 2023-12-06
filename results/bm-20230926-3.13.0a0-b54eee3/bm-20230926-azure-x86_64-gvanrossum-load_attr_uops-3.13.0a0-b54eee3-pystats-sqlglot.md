
# Pystats results

- benchmark: sqlglot
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 618,133,920 | 21.6% | 21.6% |  |
| LOAD_ATTR_SLOT | 241,561,440 | 8.5% | 30.1% | 3.8% |
| POP_JUMP_IF_FALSE | 150,791,940 | 5.3% | 35.4% |  |
| RESUME_CHECK | 122,693,400 | 4.3% | 39.6% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 105,214,960 | 3.7% | 43.3% | 0.0% |
| STORE_FAST | 88,419,900 | 3.1% | 46.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 84,457,800 | 3.0% | 49.4% | 0.0% |
| TO_BOOL_BOOL | 79,179,940 | 2.8% | 52.1% | 0.6% |
| STORE_ATTR_SLOT | 75,565,960 | 2.6% | 54.8% | 8.1% |
| RETURN_VALUE | 65,609,340 | 2.3% | 57.1% |  |
| LOAD_GLOBAL_MODULE | 64,107,100 | 2.2% | 59.3% |  |
| CALL_PY_EXACT_ARGS | 61,861,920 | 2.2% | 61.5% | 2.3% |
| POP_JUMP_IF_TRUE | 54,680,160 | 1.9% | 63.4% |  |
| LOAD_CONST | 53,036,100 | 1.9% | 65.3% |  |
| CALL_ISINSTANCE | 50,113,560 | 1.8% | 67.0% |  |
| POP_TOP | 47,002,680 | 1.6% | 68.7% |  |
| LOAD_FAST_LOAD_FAST | 46,050,720 | 1.6% | 70.3% |  |
| JUMP_BACKWARD | 44,904,540 | 1.6% | 71.8% |  |
| RETURN_CONST | 40,703,640 | 1.4% | 73.3% |  |
| FOR_ITER | 34,982,200 | 1.2% | 74.5% |  |
| COPY | 33,928,140 | 1.2% | 75.7% |  |
| SWAP | 33,466,140 | 1.2% | 76.8% |  |
| TO_BOOL_ALWAYS_TRUE | 28,904,720 | 1.0% | 77.9% | 19.2% |
| COMPARE_OP_INT | 25,821,120 | 0.9% | 78.8% |  |
| BINARY_OP_ADD_INT | 24,818,940 | 0.9% | 79.6% |  |
| INTERPRETER_EXIT | 23,386,480 | 0.8% | 80.4% |  |
| STORE_FAST_STORE_FAST | 21,912,780 | 0.8% | 81.2% |  |
| BINARY_SUBSCR_STR_INT | 21,396,000 | 0.7% | 82.0% |  |
| TO_BOOL_NONE | 21,085,720 | 0.7% | 82.7% | 16.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20,953,680 | 0.7% | 83.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 20,879,520 | 0.7% | 84.2% | 0.0% |
| LOAD_ATTR | 20,201,320 | 0.7% | 84.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 19,841,760 | 0.7% | 85.6% |  |
| GET_ITER | 19,819,080 | 0.7% | 86.3% |  |
| BUILD_TUPLE | 19,540,020 | 0.7% | 86.9% |  |
| COMPARE_OP | 18,943,980 | 0.7% | 87.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 17,768,820 | 0.6% | 88.2% |  |
| TO_BOOL_STR | 17,612,240 | 0.6% | 88.8% | 4.5% |
| CALL_PY_WITH_DEFAULTS | 16,947,100 | 0.6% | 89.4% | 0.2% |
| YIELD_VALUE | 16,380,480 | 0.6% | 90.0% |  |
| CONTAINS_OP | 15,009,900 | 0.5% | 90.5% |  |
| BINARY_OP_SUBTRACT_INT | 13,310,940 | 0.5% | 91.0% |  |
| LOAD_DEREF | 12,149,880 | 0.4% | 91.4% |  |
| FOR_ITER_LIST | 11,589,600 | 0.4% | 91.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,122,460 | 0.4% | 92.2% | 29.8% |
| CALL_BUILTIN_O | 10,746,720 | 0.4% | 92.6% |  |
| LOAD_FAST_AND_CLEAR | 10,235,820 | 0.4% | 93.0% |  |
| JUMP_FORWARD | 9,970,800 | 0.3% | 93.3% |  |
| EXTENDED_ARG | 9,458,760 | 0.3% | 93.6% |  |
| SEND_GEN | 9,399,000 | 0.3% | 94.0% |  |
| LOAD_ATTR_MODULE | 8,950,420 | 0.3% | 94.3% |  |
| PUSH_NULL | 8,903,820 | 0.3% | 94.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 8,046,980 | 0.3% | 94.9% | 40.4% |
| BUILD_LIST | 7,539,060 | 0.3% | 95.1% |  |
| TO_BOOL_INT | 6,782,340 | 0.2% | 95.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 6,709,920 | 0.2% | 95.6% |  |
| LOAD_ATTR_PROPERTY | 6,657,280 | 0.2% | 95.8% | 0.6% |
| RETURN_GENERATOR | 6,443,100 | 0.2% | 96.1% |  |
| POP_JUMP_IF_NOT_NONE | 5,952,900 | 0.2% | 96.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 5,536,680 | 0.2% | 96.5% | 0.5% |
| CALL | 5,526,900 | 0.2% | 96.7% |  |
| MAP_ADD | 4,893,120 | 0.2% | 96.8% |  |
| NOP | 4,669,260 | 0.2% | 97.0% |  |
| UNPACK_SEQUENCE_TUPLE | 4,596,960 | 0.2% | 97.2% |  |
| FOR_ITER_GEN | 4,463,880 | 0.2% | 97.3% |  |
| BUILD_MAP | 4,376,700 | 0.2% | 97.5% |  |
| CALL_TYPE_1 | 4,179,840 | 0.1% | 97.6% |  |
| TO_BOOL | 4,091,920 | 0.1% | 97.8% |  |
| BINARY_SUBSCR_LIST_INT | 3,977,340 | 0.1% | 97.9% | 0.7% |
| COPY_FREE_VARS | 3,779,580 | 0.1% | 98.0% |  |
| MAKE_FUNCTION | 3,553,320 | 0.1% | 98.1% |  |
| FORMAT_SIMPLE | 3,309,180 | 0.1% | 98.3% |  |
| CALL_LIST_APPEND | 3,136,320 | 0.1% | 98.4% |  |
| UNARY_NOT | 3,077,040 | 0.1% | 98.5% |  |
| COMPARE_OP_STR | 2,812,740 | 0.1% | 98.6% |  |
| BINARY_SLICE | 2,759,340 | 0.1% | 98.7% |  |
| GET_YIELD_FROM_ITER | 2,689,080 | 0.1% | 98.8% |  |
| END_SEND | 2,689,080 | 0.1% | 98.9% |  |
| IS_OP | 2,555,040 | 0.1% | 99.0% |  |
| CALL_BUILTIN_FAST | 2,534,320 | 0.1% | 99.0% | 0.1% |
| CALL_TUPLE_1 | 2,449,680 | 0.1% | 99.1% |  |
| MAKE_CELL | 2,395,980 | 0.1% | 99.2% |  |
| CALL_KW | 2,012,460 | 0.1% | 99.3% |  |
| BUILD_STRING | 2,000,940 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,773,420 | 0.1% | 99.4% | 69.2% |
| BINARY_SUBSCR_DICT | 1,762,080 | 0.1% | 99.5% |  |
| FOR_ITER_TUPLE | 1,684,680 | 0.1% | 99.5% |  |
| POP_JUMP_IF_NONE | 1,360,260 | 0.0% | 99.6% |  |
| CALL_LEN | 1,332,300 | 0.0% | 99.6% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,193,160 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,145,700 | 0.0% | 99.7% |  |
| BINARY_SUBSCR | 1,067,680 | 0.0% | 99.7% |  |
| STORE_SUBSCR_DICT | 977,700 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 925,980 | 0.0% | 99.8% |  |
| CALL_FUNCTION_EX | 912,480 | 0.0% | 99.8% |  |
| DICT_MERGE | 894,900 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 847,260 | 0.0% | 99.9% |  |
| END_FOR | 523,500 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 484,620 | 0.0% | 99.9% |  |
| LIST_APPEND | 292,920 | 0.0% | 100.0% |  |
| STORE_DEREF | 166,260 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 127,800 | 0.0% | 100.0% |  |
| UNPACK_EX | 109,260 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 90,540 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 88,640 | 0.0% | 100.0% | 23.1% |
| PUSH_EXC_INFO | 82,620 | 0.0% | 100.0% |  |
| POP_EXCEPT | 82,620 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 82,620 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 73,680 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 62,460 | 0.0% | 100.0% |  |
| LIST_EXTEND | 56,880 | 0.0% | 100.0% |  |
| CALL_STR_1 | 54,900 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 49,260 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 49,200 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 46,440 | 0.0% | 100.0% |  |
| BINARY_OP | 24,980 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 21,480 | 0.0% | 100.0% |  |
| BUILD_SET | 21,180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 15,480 | 0.0% | 100.0% |  |
| DICT_UPDATE | 12,360 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 8,040 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 7,800 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 7,680 | 0.0% | 100.0% | 1.6% |
| SET_ADD | 6,720 | 0.0% | 100.0% |  |
| IMPORT_NAME | 4,560 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,520 | 0.0% | 100.0% |  |
| STORE_ATTR | 340 | 0.0% | 100.0% |  |
| SET_UPDATE | 60 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 60 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 197,461,900 | 6.9% | 6.9% |
| LOAD_ATTR_SLOT LOAD_FAST | 95,579,220 | 3.3% | 10.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 93,921,720 | 3.3% | 13.5% |
| RESUME_CHECK LOAD_FAST | 71,775,600 | 2.5% | 16.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 65,431,800 | 2.3% | 18.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 56,026,960 | 2.0% | 20.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 54,809,100 | 1.9% | 22.2% |
| STORE_ATTR_SLOT LOAD_FAST | 52,907,580 | 1.9% | 24.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 47,199,080 | 1.7% | 25.7% |
| LOAD_FAST STORE_ATTR_SLOT | 45,461,900 | 1.6% | 27.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 42,809,220 | 1.5% | 28.8% |
| STORE_FAST LOAD_FAST | 38,292,060 | 1.3% | 30.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 31,735,560 | 1.1% | 31.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 31,081,680 | 1.1% | 32.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 29,166,780 | 1.0% | 33.4% |
| LOAD_FAST COPY | 28,218,300 | 1.0% | 34.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 25,769,360 | 0.9% | 35.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 24,418,460 | 0.9% | 36.1% |
| LOAD_FAST BINARY_OP_ADD_INT | 22,483,620 | 0.8% | 36.9% |
| SWAP STORE_ATTR_SLOT | 21,955,740 | 0.8% | 37.7% |
| COPY LOAD_ATTR_SLOT | 21,955,740 | 0.8% | 38.4% |
| BINARY_OP_ADD_INT SWAP | 21,955,740 | 0.8% | 39.2% |
| JUMP_BACKWARD FOR_ITER | 21,511,440 | 0.8% | 40.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 21,444,580 | 0.8% | 40.7% |
| LOAD_ATTR_SLOT COMPARE_OP_INT | 21,404,880 | 0.7% | 41.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 20,885,100 | 0.7% | 42.2% |
| BINARY_SUBSCR_STR_INT LOAD_FAST | 20,558,880 | 0.7% | 42.9% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_NO_DICT | 20,168,560 | 0.7% | 43.6% |
| CACHE RESUME_CHECK | 20,137,540 | 0.7% | 44.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 19,139,880 | 0.7% | 45.0% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 18,972,480 | 0.7% | 45.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 18,842,500 | 0.7% | 46.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,657,660 | 0.7% | 47.0% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 18,504,640 | 0.6% | 47.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 18,499,680 | 0.6% | 48.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 17,766,460 | 0.6% | 48.9% |
| COMPARE_OP POP_JUMP_IF_FALSE | 17,251,500 | 0.6% | 49.5% |
| LOAD_ATTR_SLOT LOAD_CONST | 16,837,080 | 0.6% | 50.1% |
| RETURN_CONST POP_TOP | 16,676,280 | 0.6% | 50.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 16,417,940 | 0.6% | 51.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 16,168,560 | 0.6% | 51.8% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 15,722,580 | 0.6% | 52.3% |
| LOAD_FAST RETURN_VALUE | 15,625,380 | 0.5% | 52.9% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 15,573,800 | 0.5% | 53.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 15,525,840 | 0.5% | 54.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 14,783,160 | 0.5% | 54.5% |
| POP_TOP LOAD_FAST | 14,095,140 | 0.5% | 55.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 14,022,880 | 0.5% | 55.5% |
| STORE_ATTR_SLOT RETURN_CONST | 13,763,760 | 0.5% | 56.0% |
| RETURN_VALUE STORE_FAST | 13,720,360 | 0.5% | 56.4% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 13,667,600 | 0.5% | 56.9% |
| LOAD_ATTR_SLOT TO_BOOL_ALWAYS_TRUE | 13,309,260 | 0.5% | 57.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 12,494,400 | 0.4% | 57.8% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 12,214,600 | 0.4% | 58.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 12,192,720 | 0.4% | 58.7% |
| RETURN_VALUE INTERPRETER_EXIT | 12,007,900 | 0.4% | 59.1% |
| JUMP_BACKWARD LOAD_FAST | 12,004,260 | 0.4% | 59.5% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_WITH_DEFAULTS | 11,750,440 | 0.4% | 59.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 11,737,260 | 0.4% | 60.3% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 11,676,940 | 0.4% | 60.7% |
| RETURN_CONST TO_BOOL_NONE | 10,607,440 | 0.4% | 61.1% |
| LOAD_FAST TO_BOOL_STR | 10,492,040 | 0.4% | 61.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 10,448,160 | 0.4% | 61.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 10,396,720 | 0.4% | 62.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS GET_ITER | 10,332,120 | 0.4% | 62.6% |
| COMPARE_OP_INT LOAD_FAST | 10,283,700 | 0.4% | 62.9% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_STR_INT | 10,283,700 | 0.4% | 63.3% |
| LOAD_ATTR_SLOT BINARY_SUBSCR_STR_INT | 10,275,180 | 0.4% | 63.6% |
| LOAD_FAST BUILD_TUPLE | 9,992,220 | 0.3% | 64.0% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 9,817,580 | 0.3% | 64.3% |
| RESUME_CHECK POP_TOP | 9,670,560 | 0.3% | 64.7% |
| LOAD_FAST TO_BOOL_BOOL | 9,486,180 | 0.3% | 65.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,461,400 | 0.3% | 65.3% |
| RETURN_VALUE RETURN_VALUE | 9,390,540 | 0.3% | 65.7% |
| POP_TOP JUMP_BACKWARD | 9,199,260 | 0.3% | 66.0% |
| CALL_BUILTIN_O RETURN_VALUE | 9,145,260 | 0.3% | 66.3% |
| TO_BOOL_STR POP_JUMP_IF_TRUE | 9,057,980 | 0.3% | 66.6% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 9,023,640 | 0.3% | 66.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 8,945,260 | 0.3% | 67.3% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 8,887,000 | 0.3% | 67.6% |
| LOAD_FAST TO_BOOL_NONE | 8,663,220 | 0.3% | 67.9% |
| LOAD_FAST COMPARE_OP | 8,606,820 | 0.3% | 68.2% |
| TO_BOOL_STR POP_JUMP_IF_FALSE | 8,539,180 | 0.3% | 68.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 8,462,880 | 0.3% | 68.8% |
| LOAD_ATTR COMPARE_OP | 8,348,880 | 0.3% | 69.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 8,322,200 | 0.3% | 69.4% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 8,168,960 | 0.3% | 69.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT LOAD_ATTR_METHOD_NO_DICT | 8,107,940 | 0.3% | 69.9% |
| LOAD_ATTR_SLOT CALL_METHOD_DESCRIPTOR_FAST | 8,035,200 | 0.3% | 70.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 8,013,720 | 0.3% | 70.5% |
| LOAD_FAST LOAD_CONST | 7,605,480 | 0.3% | 70.8% |
| LOAD_FAST GET_ITER | 7,480,620 | 0.3% | 71.0% |
| GET_ITER FOR_ITER | 7,443,800 | 0.3% | 71.3% |
| EXTENDED_ARG JUMP_BACKWARD | 7,394,640 | 0.3% | 71.5% |
| LOAD_FAST STORE_FAST | 7,276,260 | 0.3% | 71.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 7,107,300 | 0.2% | 72.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 7,088,880 | 0.2% | 72.3% |
| POP_JUMP_IF_TRUE EXTENDED_ARG | 7,033,380 | 0.2% | 72.5% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 6,924,660 | 0.2% | 72.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT CONTAINS_OP | 6,873,540 | 0.2% | 73.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,706,720 | 98.1% |
| LOAD_CONST | 52,620 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,706,720 | 98.1% |
| CALL_BUILTIN_CLASS | 31,560 | 1.1% |
| GET_ITER | 12,600 | 0.5% |
| TO_BOOL_LIST | 8,460 | 0.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,137,540 | 86.1% |
| POP_TOP | 3,230,520 | 13.8% |
| MAKE_CELL | 18,420 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 837,120 | 70.2% |
| LOAD_ATTR_SLOT | 356,040 | 29.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,193,160 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,062,500 | 99.5% |
| LOAD_FAST_LOAD_FAST | 4,780 | 0.4% |
| BINARY_SUBSCR | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,067,220 | 100.0% |
| BINARY_SUBSCR | 400 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 82,620 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 82,620 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,332,120 | 52.1% |
| LOAD_FAST | 7,480,620 | 37.7% |
| LOAD_ATTR_SLOT | 849,720 | 4.3% |
| RETURN_GENERATOR | 523,500 | 2.6% |
| BUILD_TUPLE | 344,040 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 7,443,800 | 37.6% |
| FOR_ITER_LIST | 5,585,320 | 28.2% |
| LOAD_FAST_AND_CLEAR | 3,511,860 | 17.7% |
| CALL_PY_EXACT_ARGS | 2,734,020 | 13.8% |
| FOR_ITER_GEN | 517,980 | 2.6% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,007,900 | 51.3% |
| YIELD_VALUE | 5,730,180 | 24.5% |
| RETURN_CONST | 5,648,400 | 24.2% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,553,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,963,980 | 55.3% |
| SET_FUNCTION_ATTRIBUTE | 846,300 | 23.8% |
| LOAD_FAST | 742,980 | 20.9% |
| STORE_FAST | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,962,100 | 84.9% |
| POP_JUMP_IF_FALSE | 380,100 | 8.1% |
| STORE_FAST | 326,460 | 7.0% |
| POP_JUMP_IF_TRUE | 360 | 0.0% |
| POP_TOP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,258,900 | 69.8% |
| LOAD_FAST | 1,394,760 | 29.9% |
| LOAD_GLOBAL_MODULE | 14,100 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 1,080 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 43,200 | 52.3% |
| POP_TOP | 39,420 | 47.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 68,820 | 83.3% |
| JUMP_FORWARD | 13,800 | 16.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 16,676,280 | 35.5% |
| RESUME_CHECK | 9,670,560 | 20.6% |
| POP_JUMP_IF_FALSE | 4,484,640 | 9.5% |
| STORE_FAST | 3,772,080 | 8.0% |
| CACHE | 3,230,520 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,095,140 | 30.0% |
| JUMP_BACKWARD | 9,199,260 | 19.6% |
| RESUME_CHECK | 6,443,100 | 13.7% |
| STORE_FAST | 3,768,960 | 8.0% |
| LOAD_GLOBAL_BUILTIN | 3,136,800 | 6.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 57,000 | 69.0% |
| BINARY_SUBSCR_LIST_INT | 25,560 | 30.9% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 82,600 | 100.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,186,180 | 69.5% |
| CALL_BUILTIN_FAST | 1,209,480 | 13.6% |
| LOAD_ATTR_MODULE | 848,020 | 9.5% |
| LOAD_DEREF | 238,380 | 2.7% |
| LOAD_FAST_LOAD_FAST | 228,720 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,517,440 | 39.5% |
| LOAD_FAST | 2,733,180 | 30.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 931,380 | 10.5% |
| LOAD_CONST | 795,780 | 8.9% |
| CALL_PY_EXACT_ARGS | 777,340 | 8.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,625,380 | 23.8% |
| RETURN_VALUE | 9,390,540 | 14.3% |
| CALL_BUILTIN_O | 9,145,260 | 13.9% |
| BUILD_LIST | 4,644,120 | 7.1% |
| STORE_FAST | 3,332,520 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,720,360 | 20.9% |
| INTERPRETER_EXIT | 12,007,900 | 18.3% |
| RETURN_VALUE | 9,390,540 | 14.3% |
| MAP_ADD | 4,750,200 | 7.2% |
| LOAD_FAST | 4,637,220 | 7.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,082,200 | 99.8% |
| COPY | 7,540 | 0.2% |
| TO_BOOL | 1,720 | 0.0% |
| RETURN_CONST | 200 | 0.0% |
| CALL_ISINSTANCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,081,920 | 99.8% |
| POP_JUMP_IF_TRUE | 7,560 | 0.2% |
| TO_BOOL | 1,720 | 0.0% |
| TO_BOOL_NONE | 380 | 0.0% |
| TO_BOOL_BOOL | 200 | 0.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,063,240 | 99.6% |
| TO_BOOL_ALWAYS_TRUE | 9,860 | 0.3% |
| TO_BOOL_NONE | 3,940 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,016,800 | 98.0% |
| COPY | 46,440 | 1.5% |
| STORE_FAST | 13,800 | 0.4% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,360 | 85.5% |
| LOAD_FAST_LOAD_FAST | 1,680 | 6.7% |
| BUILD_LIST | 840 | 3.4% |
| CALL_BUILTIN_CLASS | 540 | 2.2% |
| BINARY_OP | 340 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,240 | 85.0% |
| GET_ITER | 1,560 | 6.2% |
| STORE_FAST | 840 | 3.4% |
| LOAD_FAST_LOAD_FAST | 840 | 3.4% |
| BINARY_OP | 340 | 1.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 49,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 15,840 | 32.2% |
| LOAD_FAST | 15,600 | 31.7% |
| LOAD_DEREF | 15,480 | 31.4% |
| CALL_FUNCTION_EX | 2,040 | 4.1% |
| STORE_FAST | 300 | 0.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,156,900 | 81.7% |
| STORE_FAST | 694,560 | 9.2% |
| SWAP | 148,860 | 2.0% |
| LOAD_CONST | 130,080 | 1.7% |
| RESUME_CHECK | 116,760 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,644,120 | 61.6% |
| STORE_FAST | 1,431,120 | 19.0% |
| COMPARE_OP | 876,180 | 11.6% |
| LOAD_FAST | 240,600 | 3.2% |
| SWAP | 148,860 | 2.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,360,660 | 76.8% |
| LOAD_CONST | 822,600 | 18.8% |
| RESUME_CHECK | 48,420 | 1.1% |
| POP_JUMP_IF_NOT_NONE | 43,200 | 1.0% |
| LOAD_FAST | 28,500 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,360,660 | 76.8% |
| LOAD_FAST | 803,220 | 18.4% |
| STORE_FAST | 103,440 | 2.4% |
| LOAD_GLOBAL_MODULE | 38,520 | 0.9% |
| LOAD_DEREF | 37,080 | 0.8% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,992,220 | 51.1% |
| LOAD_GLOBAL_BUILTIN | 4,485,420 | 23.0% |
| CALL_TUPLE_1 | 1,963,980 | 10.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,834,800 | 9.4% |
| RETURN_VALUE | 345,720 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 6,482,160 | 33.2% |
| CALL_ISINSTANCE | 4,875,300 | 25.0% |
| CALL_BUILTIN_O | 3,922,860 | 20.1% |
| SWAP | 1,062,120 | 5.4% |
| LOAD_CONST | 867,420 | 4.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,156,620 | 57.1% |
| LOAD_CONST | 1,155,420 | 20.9% |
| LOAD_ATTR_SLOT | 1,070,260 | 19.4% |
| BUILD_LIST | 32,840 | 0.6% |
| LOAD_ATTR_MODULE | 30,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 3,131,100 | 56.7% |
| LOAD_FAST | 1,078,020 | 19.5% |
| CALL_LIST_APPEND | 1,070,260 | 19.4% |
| STORE_FAST | 79,500 | 1.4% |
| TO_BOOL_BOOL | 46,440 | 0.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 894,900 | 98.1% |
| BUILD_MAP | 11,520 | 1.3% |
| RETURN_GENERATOR | 3,120 | 0.3% |
| BUILD_CONST_KEY_MAP | 2,040 | 0.2% |
| CALL_INTRINSIC_1 | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 741,180 | 81.2% |
| RETURN_VALUE | 87,660 | 9.6% |
| RESUME_CHECK | 65,880 | 7.2% |
| LOAD_ATTR_METHOD_NO_DICT | 8,500 | 0.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,840 | 0.4% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 37,680 | 76.6% |
| LIST_APPEND | 11,520 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,940 | 60.9% |
| BUILD_MAP | 18,660 | 37.9% |
| CALL_FUNCTION_EX | 600 | 1.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,012,460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 863,940 | 42.9% |
| RETURN_GENERATOR | 507,660 | 25.2% |
| RETURN_VALUE | 499,320 | 24.8% |
| MAKE_CELL | 103,320 | 5.1% |
| STORE_FAST | 33,120 | 1.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,606,820 | 45.4% |
| LOAD_ATTR | 8,348,880 | 44.1% |
| BUILD_LIST | 876,180 | 4.6% |
| RETURN_VALUE | 680,280 | 3.6% |
| CALL_BUILTIN_CLASS | 197,820 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,251,500 | 91.1% |
| POP_JUMP_IF_TRUE | 941,040 | 5.0% |
| RETURN_VALUE | 682,440 | 3.6% |
| COPY | 46,860 | 0.2% |
| STORE_FAST | 15,480 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 6,873,540 | 45.8% |
| LOAD_FAST | 4,182,780 | 27.9% |
| LOAD_FAST_LOAD_FAST | 2,261,640 | 15.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,468,320 | 9.8% |
| BUILD_TUPLE | 197,580 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,494,400 | 83.2% |
| POP_JUMP_IF_TRUE | 1,662,900 | 11.1% |
| STORE_FAST | 852,600 | 5.7% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,218,300 | 83.2% |
| CALL_ISINSTANCE | 2,172,480 | 6.4% |
| IS_OP | 1,973,520 | 5.8% |
| RETURN_CONST | 1,217,700 | 3.6% |
| RETURN_VALUE | 211,840 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,955,740 | 64.7% |
| TO_BOOL_ALWAYS_TRUE | 5,822,980 | 17.2% |
| TO_BOOL_BOOL | 4,550,620 | 13.4% |
| TO_BOOL_NONE | 1,422,740 | 4.2% |
| TO_BOOL_STR | 125,020 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,131,100 | 82.8% |
| CALL_PY_EXACT_ARGS | 621,840 | 16.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,640 | 0.6% |
| CALL_FUNCTION_EX | 1,560 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,752,520 | 99.3% |
| RETURN_GENERATOR | 27,060 | 0.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 789,420 | 88.2% |
| RETURN_VALUE | 38,520 | 4.3% |
| LOAD_DEREF | 37,080 | 4.1% |
| BUILD_CONST_KEY_MAP | 15,840 | 1.8% |
| DICT_UPDATE | 12,360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 894,900 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 12,360 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,033,380 | 74.4% |
| TO_BOOL_BOOL | 1,238,040 | 13.1% |
| JUMP_BACKWARD | 433,500 | 4.6% |
| POP_TOP | 357,240 | 3.8% |
| TO_BOOL_NONE | 335,760 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,394,640 | 78.2% |
| POP_JUMP_IF_FALSE | 1,573,800 | 16.6% |
| FOR_ITER | 338,460 | 3.6% |
| FOR_ITER_GEN | 112,440 | 1.2% |
| JUMP_FORWARD | 23,220 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 21,511,440 | 61.5% |
| GET_ITER | 7,443,800 | 21.3% |
| SWAP | 3,329,520 | 9.5% |
| LOAD_FAST | 2,349,120 | 6.7% |
| EXTENDED_ARG | 338,460 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 18,504,640 | 52.9% |
| RETURN_CONST | 5,415,900 | 15.5% |
| STORE_FAST | 3,624,300 | 10.4% |
| SWAP | 3,324,960 | 9.5% |
| LOAD_FAST | 2,453,580 | 7.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 1,973,520 | 77.2% |
| LOAD_FAST_LOAD_FAST | 424,620 | 16.6% |
| LOAD_ATTR_INSTANCE_VALUE | 109,260 | 4.3% |
| LOAD_DEREF | 43,800 | 1.7% |
| LOAD_GLOBAL_MODULE | 3,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,973,520 | 77.2% |
| POP_JUMP_IF_FALSE | 576,660 | 22.6% |
| RETURN_VALUE | 4,860 | 0.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,199,260 | 20.5% |
| EXTENDED_ARG | 7,394,640 | 16.5% |
| POP_JUMP_IF_TRUE | 6,924,660 | 15.4% |
| MAP_ADD | 4,893,120 | 10.9% |
| FOR_ITER_LIST | 4,724,280 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 21,511,440 | 47.9% |
| LOAD_FAST | 12,004,260 | 26.7% |
| FOR_ITER_LIST | 5,829,720 | 13.0% |
| FOR_ITER_GEN | 3,830,640 | 8.5% |
| FOR_ITER_TUPLE | 1,286,340 | 2.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,124,260 | 31.3% |
| RETURN_VALUE | 2,696,040 | 27.0% |
| POP_JUMP_IF_FALSE | 1,729,020 | 17.3% |
| STORE_FAST | 1,386,180 | 13.9% |
| STORE_ATTR_SLOT | 309,600 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,218,040 | 32.3% |
| JUMP_BACKWARD | 3,105,780 | 31.1% |
| YIELD_VALUE | 1,654,860 | 16.6% |
| STORE_FAST | 1,467,480 | 14.7% |
| LOAD_FAST_LOAD_FAST | 205,260 | 2.1% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 37,320 | 65.6% |
| STORE_FAST | 19,200 | 33.8% |
| CALL | 360 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 37,680 | 66.2% |
| LOAD_FAST | 19,200 | 33.8% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,499,680 | 91.6% |
| LOAD_FAST | 1,576,280 | 7.8% |
| LOAD_ATTR_MODULE | 69,660 | 0.3% |
| LOAD_ATTR | 20,320 | 0.1% |
| LOAD_DEREF | 15,700 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 8,348,880 | 41.3% |
| CALL_PY_EXACT_ARGS | 8,168,960 | 40.4% |
| LOAD_FAST | 1,538,580 | 7.6% |
| LOAD_GLOBAL_MODULE | 683,280 | 3.4% |
| CALL_PY_WITH_DEFAULTS | 644,560 | 3.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 16,837,080 | 31.7% |
| LOAD_FAST | 7,605,480 | 14.3% |
| STORE_FAST | 4,297,020 | 8.1% |
| LOAD_ATTR_METHOD_NO_DICT | 4,218,960 | 8.0% |
| GET_YIELD_FROM_ITER | 2,689,080 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 12,214,600 | 23.0% |
| LOAD_FAST | 6,487,860 | 12.2% |
| STORE_FAST | 5,546,220 | 10.5% |
| COMPARE_OP_INT | 4,300,360 | 8.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,737,560 | 7.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,178,020 | 50.8% |
| POP_JUMP_IF_FALSE | 2,137,380 | 17.6% |
| RESUME_CHECK | 1,473,780 | 12.1% |
| STORE_FAST | 900,000 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 274,980 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,264,900 | 51.6% |
| LOAD_ATTR_METHOD_NO_DICT | 3,724,520 | 30.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 655,860 | 5.4% |
| RETURN_VALUE | 250,080 | 2.1% |
| PUSH_NULL | 238,380 | 2.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 95,579,220 | 15.5% |
| POP_JUMP_IF_FALSE | 93,921,720 | 15.2% |
| RESUME_CHECK | 71,775,600 | 11.6% |
| LOAD_GLOBAL_BUILTIN | 65,431,800 | 10.6% |
| STORE_ATTR_SLOT | 52,907,580 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 197,461,900 | 31.9% |
| STORE_ATTR_SLOT | 45,461,900 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 42,809,220 | 6.9% |
| LOAD_GLOBAL_BUILTIN | 31,735,560 | 5.1% |
| COPY | 28,218,300 | 4.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 46,440 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,461,400 | 20.5% |
| POP_JUMP_IF_FALSE | 7,088,880 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 4,844,700 | 10.5% |
| LOAD_GLOBAL_MODULE | 4,486,620 | 9.7% |
| STORE_ATTR_SLOT | 3,910,500 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,737,260 | 25.5% |
| STORE_ATTR_SLOT | 8,013,720 | 17.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,818,800 | 12.6% |
| BINARY_SUBSCR_LIST_INT | 3,274,340 | 7.1% |
| CALL_BUILTIN_FAST | 2,415,520 | 5.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 740 | 29.4% |
| LOAD_ATTR_METHOD_NO_DICT | 420 | 16.7% |
| RESUME_CHECK | 320 | 12.7% |
| RETURN_VALUE | 180 | 7.1% |
| POP_JUMP_IF_FALSE | 160 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,880 | 74.6% |
| LOAD_GLOBAL_BUILTIN | 560 | 22.2% |
| LOAD_ATTR | 80 | 3.2% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,036,600 | 43.3% |
| MAKE_CELL | 573,120 | 23.9% |
| CALL_PY_WITH_DEFAULTS | 494,280 | 20.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 170,060 | 7.1% |
| CALL_KW | 103,320 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,343,340 | 56.1% |
| MAKE_CELL | 573,120 | 23.9% |
| RETURN_GENERATOR | 479,520 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 56,026,960 | 37.2% |
| COMPARE_OP | 17,251,500 | 11.4% |
| TO_BOOL_NONE | 15,573,800 | 10.3% |
| COMPARE_OP_INT | 15,525,840 | 10.3% |
| CONTAINS_OP | 12,494,400 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,921,720 | 62.3% |
| RETURN_CONST | 16,168,560 | 10.7% |
| LOAD_GLOBAL_MODULE | 8,322,200 | 5.5% |
| LOAD_GLOBAL_BUILTIN | 7,107,300 | 4.7% |
| LOAD_FAST_LOAD_FAST | 7,088,880 | 4.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,324,560 | 97.4% |
| LOAD_ATTR_INSTANCE_VALUE | 27,960 | 2.1% |
| BINARY_SUBSCR_LIST_INT | 7,740 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,312,920 | 96.5% |
| LOAD_GLOBAL_BUILTIN | 38,760 | 2.8% |
| LOAD_FAST_LOAD_FAST | 7,740 | 0.6% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |
| JUMP_BACKWARD | 360 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,934,720 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 9,060 | 0.2% |
| LOAD_ATTR_SLOT | 8,160 | 0.1% |
| STORE_FAST_LOAD_FAST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,691,700 | 78.8% |
| LOAD_FAST | 1,116,480 | 18.8% |
| BUILD_LIST | 83,700 | 1.4% |
| BUILD_MAP | 43,200 | 0.7% |
| LOAD_GLOBAL_MODULE | 13,800 | 0.2% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 18,972,480 | 34.7% |
| TO_BOOL_BOOL | 18,842,500 | 34.5% |
| TO_BOOL_STR | 9,057,980 | 16.6% |
| TO_BOOL_NONE | 5,106,960 | 9.3% |
| CONTAINS_OP | 1,662,900 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,081,680 | 56.8% |
| EXTENDED_ARG | 7,033,380 | 12.9% |
| JUMP_BACKWARD | 6,924,660 | 12.7% |
| LOAD_GLOBAL_BUILTIN | 2,998,500 | 5.5% |
| STORE_FAST | 2,745,960 | 5.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,168,560 | 39.7% |
| STORE_ATTR_SLOT | 13,763,760 | 33.8% |
| FOR_ITER | 5,415,900 | 13.3% |
| POP_TOP | 2,698,560 | 6.6% |
| POP_JUMP_IF_TRUE | 1,635,240 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 16,676,280 | 41.0% |
| TO_BOOL_NONE | 10,607,440 | 26.1% |
| INTERPRETER_EXIT | 5,648,400 | 13.9% |
| END_SEND | 2,689,080 | 6.6% |
| RETURN_VALUE | 1,335,540 | 3.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 846,300 | 99.9% |
| SET_FUNCTION_ATTRIBUTE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 479,520 | 56.6% |
| CALL_PY_EXACT_ARGS | 338,040 | 39.9% |
| LOAD_FAST | 23,940 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 3,120 | 0.4% |
| STORE_DEREF | 1,440 | 0.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 58.8% |
| LOAD_FAST_LOAD_FAST | 140 | 41.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 280 | 82.4% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 17.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 132,060 | 79.4% |
| STORE_FAST | 31,560 | 19.0% |
| SET_FUNCTION_ATTRIBUTE | 1,440 | 0.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 540 | 0.3% |
| BUILD_LIST | 480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 132,540 | 79.7% |
| LOAD_GLOBAL_BUILTIN | 31,560 | 19.0% |
| LOAD_GLOBAL_MODULE | 960 | 0.6% |
| LOAD_FAST | 660 | 0.4% |
| STORE_FAST | 540 | 0.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 14,783,160 | 16.7% |
| RETURN_VALUE | 13,720,360 | 15.5% |
| LOAD_FAST | 7,276,260 | 8.2% |
| STORE_FAST | 6,811,620 | 7.7% |
| FOR_ITER_LIST | 5,887,320 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,292,060 | 43.3% |
| LOAD_GLOBAL_BUILTIN | 15,722,580 | 17.8% |
| LOAD_FAST_LOAD_FAST | 9,461,400 | 10.7% |
| STORE_FAST | 6,811,620 | 7.7% |
| LOAD_CONST | 4,297,020 | 4.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 20,885,100 | 95.3% |
| UNPACK_SEQUENCE_TUPLE | 828,000 | 3.8% |
| UNPACK_EX | 109,260 | 0.5% |
| UNPACK_SEQUENCE | 90,420 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,192,720 | 55.6% |
| LOAD_GLOBAL_MODULE | 4,791,480 | 21.9% |
| LOAD_GLOBAL_BUILTIN | 3,744,600 | 17.1% |
| STORE_FAST | 828,000 | 3.8% |
| LOAD_FAST_LOAD_FAST | 355,980 | 1.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 21,955,740 | 65.6% |
| LOAD_FAST_AND_CLEAR | 3,511,860 | 10.5% |
| BUILD_MAP | 3,360,660 | 10.0% |
| FOR_ITER | 3,324,960 | 9.9% |
| BUILD_TUPLE | 1,062,120 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 21,955,740 | 65.6% |
| STORE_FAST | 3,424,200 | 10.2% |
| BUILD_MAP | 3,360,660 | 10.0% |
| FOR_ITER | 3,329,520 | 9.9% |
| POP_TOP | 1,062,480 | 3.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 90,420 | 99.9% |
| UNPACK_SEQUENCE | 80 | 0.1% |
| FOR_ITER_LIST | 20 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 90,420 | 99.9% |
| UNPACK_SEQUENCE | 80 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,680 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,483,620 | 90.6% |
| LOAD_CONST | 2,255,020 | 9.1% |
| LOAD_FAST_LOAD_FAST | 80,160 | 0.3% |
| RETURN_VALUE | 60 | 0.0% |
| RETURN_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 21,955,740 | 88.5% |
| STORE_FAST | 1,682,700 | 6.8% |
| CALL_PY_EXACT_ARGS | 1,078,740 | 4.3% |
| LIST_APPEND | 80,160 | 0.3% |
| BINARY_OP_SUBTRACT_INT | 18,360 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,760 | 99.5% |
| BINARY_OP | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 7,680 | 98.5% |
| BINARY_OP | 120 | 1.5% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,214,600 | 91.8% |
| CALL_LEN | 1,070,220 | 8.0% |
| BINARY_OP_ADD_INT | 18,360 | 0.1% |
| LOAD_ATTR_SLOT | 7,720 | 0.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 10,283,700 | 77.3% |
| CALL_PY_EXACT_ARGS | 1,093,420 | 8.2% |
| LOAD_CONST | 1,070,220 | 8.0% |
| LOAD_FAST | 837,480 | 6.3% |
| RETURN_VALUE | 18,360 | 0.1% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 839,040 | 47.6% |
| LOAD_ATTR_SLOT | 589,860 | 33.5% |
| LOAD_CONST | 192,360 | 10.9% |
| CALL_BUILTIN_O | 81,480 | 4.6% |
| LOAD_FAST | 29,760 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,218,960 | 69.2% |
| LOAD_FAST_LOAD_FAST | 155,220 | 8.8% |
| BUILD_TUPLE | 127,380 | 7.2% |
| RETURN_VALUE | 71,220 | 4.0% |
| PUSH_EXC_INFO | 57,000 | 3.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 15,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,480 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,274,340 | 82.3% |
| LOAD_CONST | 702,460 | 17.7% |
| BINARY_SUBSCR_LIST_INT | 480 | 0.0% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,241,860 | 81.5% |
| LOAD_FAST | 681,060 | 17.1% |
| PUSH_EXC_INFO | 25,560 | 0.6% |
| STORE_FAST | 8,940 | 0.2% |
| POP_JUMP_IF_NONE | 7,740 | 0.2% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 10,283,700 | 48.1% |
| LOAD_ATTR_SLOT | 10,275,180 | 48.0% |
| LOAD_FAST | 837,120 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,558,880 | 96.1% |
| STORE_FAST | 837,120 | 3.9% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 931,380 | 52.5% |
| LOAD_FAST | 756,980 | 42.7% |
| LOAD_ATTR_SLOT | 54,160 | 3.1% |
| CALL_PY_EXACT_ARGS | 23,140 | 1.3% |
| LOAD_ATTR | 7,680 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,556,560 | 87.8% |
| MAKE_CELL | 170,060 | 9.6% |
| COPY_FREE_VARS | 23,640 | 1.3% |
| CALL_PY_EXACT_ARGS | 23,160 | 1.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 396,720 | 81.9% |
| CALL_BUILTIN_FAST | 33,240 | 6.9% |
| BINARY_SLICE | 31,560 | 6.5% |
| LOAD_FAST | 9,560 | 2.0% |
| LOAD_ATTR | 7,720 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 197,820 | 40.8% |
| JUMP_FORWARD | 179,520 | 37.0% |
| GET_ITER | 40,920 | 8.4% |
| RETURN_VALUE | 34,020 | 7.0% |
| CALL_LEN | 18,360 | 3.8% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,415,520 | 95.3% |
| LOAD_CONST | 73,560 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 38,760 | 1.5% |
| LOAD_DEREF | 3,840 | 0.2% |
| RETURN_GENERATOR | 2,280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,252,080 | 49.4% |
| PUSH_NULL | 1,209,480 | 47.7% |
| STORE_FAST | 38,760 | 1.5% |
| CALL_BUILTIN_CLASS | 33,240 | 1.3% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,222,400 | 48.6% |
| BUILD_TUPLE | 3,922,860 | 36.5% |
| LOAD_FAST | 1,588,140 | 14.8% |
| RETURN_VALUE | 12,780 | 0.1% |
| RETURN_GENERATOR | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,145,260 | 85.1% |
| TO_BOOL_BOOL | 1,213,860 | 11.3% |
| STORE_FAST | 205,260 | 1.9% |
| STORE_SUBSCR_DICT | 86,160 | 0.8% |
| BINARY_SUBSCR_DICT | 81,480 | 0.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 18,657,660 | 37.2% |
| LOAD_GLOBAL_MODULE | 11,676,940 | 23.3% |
| LOAD_ATTR_SLOT | 6,780,480 | 13.5% |
| LOAD_ATTR_MODULE | 6,531,420 | 13.0% |
| BUILD_TUPLE | 4,875,300 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 47,199,080 | 94.2% |
| COPY | 2,172,480 | 4.3% |
| STORE_FAST | 695,400 | 1.4% |
| RETURN_VALUE | 46,500 | 0.1% |
| TO_BOOL | 100 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,268,560 | 95.2% |
| LOAD_DEREF | 28,440 | 2.1% |
| CALL_BUILTIN_CLASS | 18,360 | 1.4% |
| LOAD_ATTR_SLOT | 8,500 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 7,720 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 1,070,220 | 80.3% |
| STORE_FAST | 92,040 | 6.9% |
| LOAD_CONST | 50,820 | 3.8% |
| COMPARE_OP_INT | 44,880 | 3.4% |
| LOAD_FAST | 37,860 | 2.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,050,380 | 65.4% |
| CALL | 1,070,260 | 34.1% |
| RETURN_VALUE | 12,340 | 0.4% |
| BUILD_TUPLE | 3,340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,457,880 | 46.5% |
| JUMP_BACKWARD | 1,419,960 | 45.3% |
| LOAD_FAST | 217,200 | 6.9% |
| RETURN_CONST | 39,060 | 1.2% |
| EXTENDED_ARG | 2,220 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 8,035,200 | 38.5% |
| LOAD_FAST | 4,363,540 | 20.9% |
| LOAD_ATTR_METHOD_NO_DICT | 3,830,160 | 18.3% |
| LOAD_CONST | 3,737,560 | 17.9% |
| LOAD_ATTR | 632,940 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,783,160 | 70.8% |
| RETURN_VALUE | 3,175,620 | 15.2% |
| CALL_PY_WITH_DEFAULTS | 2,385,540 | 11.4% |
| TO_BOOL_BOOL | 449,400 | 2.2% |
| LOAD_GLOBAL_MODULE | 33,420 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 17,766,460 | 100.0% |
| LOAD_FAST | 2,220 | 0.0% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,332,120 | 58.1% |
| CALL_PY_EXACT_ARGS | 1,899,600 | 10.7% |
| BUILD_TUPLE | 1,834,800 | 10.3% |
| TO_BOOL_BOOL | 1,085,660 | 6.1% |
| UNPACK_SEQUENCE_TUPLE | 789,480 | 4.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,769,360 | 41.7% |
| LOAD_ATTR | 8,168,960 | 13.2% |
| LOAD_ATTR_METHOD_NO_DICT | 5,829,540 | 9.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,239,240 | 5.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,212,140 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 54,809,100 | 88.6% |
| RETURN_GENERATOR | 5,367,900 | 8.7% |
| MAKE_CELL | 1,036,600 | 1.7% |
| COPY_FREE_VARS | 621,840 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,140 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 11,750,440 | 69.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,385,540 | 14.1% |
| LOAD_FAST | 1,346,900 | 7.9% |
| LOAD_ATTR | 644,560 | 3.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 499,560 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,417,940 | 96.9% |
| MAKE_CELL | 494,280 | 2.9% |
| RETURN_GENERATOR | 32,820 | 0.2% |
| COPY_FREE_VARS | 1,440 | 0.0% |
| CALL_PY_EXACT_ARGS | 620 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,880 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 54,180 | 98.7% |
| STORE_FAST | 720 | 1.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,179,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,973,520 | 47.2% |
| IS_OP | 1,973,520 | 47.2% |
| STORE_FAST | 205,200 | 4.9% |
| LOAD_FAST_LOAD_FAST | 27,600 | 0.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,404,880 | 82.9% |
| LOAD_CONST | 4,300,360 | 16.7% |
| CALL_LEN | 44,880 | 0.2% |
| LOAD_FAST | 29,340 | 0.1% |
| LOAD_DEREF | 18,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,525,840 | 60.1% |
| LOAD_FAST | 10,283,700 | 39.8% |
| POP_JUMP_IF_TRUE | 11,580 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,464,960 | 52.1% |
| LOAD_CONST | 473,480 | 16.8% |
| LOAD_FAST | 448,920 | 16.0% |
| RETURN_VALUE | 358,920 | 12.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 61,920 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,453,160 | 87.2% |
| RETURN_VALUE | 343,080 | 12.2% |
| COPY | 15,420 | 0.5% |
| POP_JUMP_IF_TRUE | 1,080 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,829,720 | 50.3% |
| GET_ITER | 5,585,320 | 48.2% |
| SWAP | 140,700 | 1.2% |
| LOAD_FAST | 26,160 | 0.2% |
| EXTENDED_ARG | 7,680 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,887,320 | 50.8% |
| JUMP_BACKWARD | 4,724,280 | 40.8% |
| LOAD_FAST | 834,420 | 7.2% |
| SWAP | 67,680 | 0.6% |
| RETURN_CONST | 39,300 | 0.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,800 | 97.0% |
| GET_ITER | 240 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,800 | 97.0% |
| LOAD_FAST | 240 | 3.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,413,120 | 97.8% |
| LOAD_FAST_LOAD_FAST | 123,000 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 540 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 5,222,400 | 94.3% |
| IS_OP | 109,260 | 2.0% |
| RETURN_VALUE | 52,380 | 0.9% |
| LOAD_FAST | 32,880 | 0.6% |
| LOAD_ATTR_METHOD_NO_DICT | 31,680 | 0.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,809,220 | 50.7% |
| LOAD_ATTR_SLOT | 20,168,560 | 23.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 8,107,940 | 9.6% |
| RETURN_VALUE | 4,554,820 | 5.4% |
| LOAD_DEREF | 3,724,520 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,166,780 | 34.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 17,766,460 | 21.0% |
| CALL_PY_WITH_DEFAULTS | 11,750,440 | 13.9% |
| LOAD_GLOBAL_MODULE | 10,448,160 | 12.4% |
| CALL_PY_EXACT_ARGS | 5,829,540 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,396,720 | 93.5% |
| LOAD_DEREF | 655,860 | 5.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,300 | 0.6% |
| CALL_FUNCTION_EX | 3,840 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,892,140 | 35.0% |
| CALL_PY_EXACT_ARGS | 3,212,140 | 28.9% |
| LOAD_FAST_LOAD_FAST | 2,717,040 | 24.4% |
| LOAD_CONST | 694,080 | 6.2% |
| CALL_PY_WITH_DEFAULTS | 499,560 | 4.5% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,945,260 | 99.9% |
| LOAD_FAST | 4,560 | 0.1% |
| LOAD_ATTR | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 6,531,420 | 73.0% |
| PUSH_NULL | 848,020 | 9.5% |
| LOAD_GLOBAL_MODULE | 486,660 | 5.4% |
| LOAD_FAST | 321,960 | 3.6% |
| BUILD_TUPLE | 300,540 | 3.4% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,022,880 | 70.7% |
| LOAD_FAST_LOAD_FAST | 5,818,800 | 29.3% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 8,107,940 | 40.9% |
| CONTAINS_OP | 6,873,540 | 34.6% |
| CALL_PY_EXACT_ARGS | 3,239,240 | 16.3% |
| STORE_FAST | 1,062,480 | 5.4% |
| LOAD_FAST | 450,120 | 2.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,521,000 | 81.0% |
| LOAD_FAST_LOAD_FAST | 1,464,540 | 18.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 61,340 | 0.8% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,002,800 | 24.9% |
| LOAD_GLOBAL_BUILTIN | 1,963,980 | 24.4% |
| CONTAINS_OP | 1,468,320 | 18.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,304,760 | 16.2% |
| FORMAT_SIMPLE | 1,209,480 | 15.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,548,260 | 98.4% |
| LOAD_FAST_LOAD_FAST | 62,580 | 0.9% |
| STORE_FAST_LOAD_FAST | 17,820 | 0.3% |
| BINARY_SUBSCR_DICT | 12,240 | 0.2% |
| LOAD_ATTR_SLOT | 7,740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,618,260 | 99.4% |
| RETURN_VALUE | 19,140 | 0.3% |
| STORE_FAST | 15,080 | 0.2% |
| COPY | 2,780 | 0.0% |
| LOAD_ATTR_PROPERTY | 700 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 197,461,900 | 81.7% |
| COPY | 21,955,740 | 9.1% |
| LOAD_ATTR_SLOT | 13,667,600 | 5.7% |
| LOAD_DEREF | 6,264,900 | 2.6% |
| LOAD_FAST_LOAD_FAST | 2,208,160 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,579,220 | 39.6% |
| COMPARE_OP_INT | 21,404,880 | 8.9% |
| LOAD_ATTR_METHOD_NO_DICT | 20,168,560 | 8.3% |
| LOAD_CONST | 16,837,080 | 7.0% |
| LOAD_ATTR_SLOT | 13,667,600 | 5.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,735,560 | 30.2% |
| RESUME_CHECK | 21,444,580 | 20.4% |
| STORE_FAST | 15,722,580 | 14.9% |
| LOAD_GLOBAL_BUILTIN | 9,023,640 | 8.6% |
| POP_JUMP_IF_FALSE | 7,107,300 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,431,800 | 62.2% |
| CALL_ISINSTANCE | 18,657,660 | 17.7% |
| LOAD_GLOBAL_BUILTIN | 9,023,640 | 8.6% |
| LOAD_FAST_LOAD_FAST | 4,844,700 | 4.6% |
| BUILD_TUPLE | 4,485,420 | 4.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,418,460 | 38.1% |
| LOAD_ATTR_METHOD_NO_DICT | 10,448,160 | 16.3% |
| POP_JUMP_IF_FALSE | 8,322,200 | 13.0% |
| STORE_FAST_STORE_FAST | 4,791,480 | 7.5% |
| RESUME_CHECK | 3,513,240 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,139,880 | 29.9% |
| LOAD_ATTR | 18,499,680 | 28.9% |
| CALL_ISINSTANCE | 11,676,940 | 18.2% |
| LOAD_ATTR_MODULE | 8,945,260 | 14.0% |
| LOAD_FAST_LOAD_FAST | 4,486,620 | 7.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 54,809,100 | 44.7% |
| CACHE | 20,137,540 | 16.4% |
| CALL_PY_WITH_DEFAULTS | 16,417,940 | 13.4% |
| SEND_GEN | 6,709,920 | 5.5% |
| LOAD_ATTR_PROPERTY | 6,618,260 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,775,600 | 58.5% |
| LOAD_GLOBAL_BUILTIN | 21,444,580 | 17.5% |
| POP_TOP | 9,670,560 | 7.9% |
| JUMP_BACKWARD_NO_INTERRUPT | 6,709,920 | 5.5% |
| NOP | 3,962,100 | 3.2% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,461,900 | 60.2% |
| SWAP | 21,955,740 | 29.1% |
| LOAD_FAST_LOAD_FAST | 8,013,720 | 10.6% |
| STORE_ATTR_SLOT | 115,600 | 0.2% |
| LOAD_DEREF | 18,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,907,580 | 70.0% |
| RETURN_CONST | 13,763,760 | 18.2% |
| LOAD_FAST_LOAD_FAST | 3,910,500 | 5.2% |
| JUMP_BACKWARD | 1,722,900 | 2.3% |
| LOAD_CONST | 1,455,060 | 1.9% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 798,180 | 81.6% |
| CALL_BUILTIN_O | 86,160 | 8.8% |
| RETURN_VALUE | 78,060 | 8.0% |
| LOAD_FAST_LOAD_FAST | 15,280 | 1.6% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 784,920 | 80.3% |
| LOAD_GLOBAL_MODULE | 81,480 | 8.3% |
| LOAD_FAST | 67,920 | 6.9% |
| POP_EXCEPT | 43,200 | 4.4% |
| EXTENDED_ARG | 180 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,309,260 | 46.0% |
| LOAD_FAST | 8,887,000 | 30.7% |
| COPY | 5,822,980 | 20.1% |
| STORE_FAST_LOAD_FAST | 770,040 | 2.7% |
| TO_BOOL_ALWAYS_TRUE | 64,300 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 18,972,480 | 65.6% |
| POP_JUMP_IF_FALSE | 9,817,580 | 34.0% |
| TO_BOOL_ALWAYS_TRUE | 64,300 | 0.2% |
| TO_BOOL_NONE | 40,500 | 0.1% |
| UNARY_NOT | 9,860 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 47,199,080 | 59.6% |
| LOAD_FAST | 9,486,180 | 12.0% |
| LOAD_ATTR_SLOT | 8,462,880 | 10.7% |
| COPY | 4,550,620 | 5.7% |
| RETURN_VALUE | 4,533,160 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 56,026,960 | 70.8% |
| POP_JUMP_IF_TRUE | 18,842,500 | 23.8% |
| UNARY_NOT | 3,063,240 | 3.9% |
| EXTENDED_ARG | 1,238,040 | 1.6% |
| TO_BOOL_NONE | 9,200 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,768,460 | 99.8% |
| LOAD_FAST | 13,840 | 0.2% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,773,760 | 99.9% |
| EXTENDED_ARG | 8,520 | 0.1% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 43,500 | 49.1% |
| LOAD_FAST | 35,320 | 39.8% |
| BINARY_SLICE | 8,460 | 9.5% |
| RETURN_VALUE | 960 | 1.1% |
| TO_BOOL_NONE | 380 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 67,500 | 76.2% |
| POP_JUMP_IF_FALSE | 20,760 | 23.4% |
| TO_BOOL_NONE | 380 | 0.4% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 10,607,440 | 50.3% |
| LOAD_FAST | 8,663,220 | 41.1% |
| COPY | 1,422,740 | 6.7% |
| LOAD_ATTR_SLOT | 224,080 | 1.1% |
| LOAD_FAST_CHECK | 46,440 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,573,800 | 73.9% |
| POP_JUMP_IF_TRUE | 5,106,960 | 24.2% |
| EXTENDED_ARG | 335,760 | 1.6% |
| TO_BOOL_ALWAYS_TRUE | 40,500 | 0.2% |
| TO_BOOL_STR | 15,120 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,492,040 | 59.6% |
| LOAD_ATTR_SLOT | 6,759,960 | 38.4% |
| STORE_FAST_LOAD_FAST | 130,560 | 0.7% |
| COPY | 125,020 | 0.7% |
| RETURN_VALUE | 88,800 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,057,980 | 51.4% |
| POP_JUMP_IF_FALSE | 8,539,180 | 48.5% |
| TO_BOOL_NONE | 15,080 | 0.1% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,504,640 | 88.3% |
| RETURN_VALUE | 2,120,880 | 10.1% |
| LOAD_FAST | 179,520 | 0.9% |
| BUILD_TUPLE | 74,220 | 0.4% |
| STORE_FAST | 68,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,885,100 | 99.7% |
| STORE_FAST | 68,040 | 0.3% |
| STORE_DEREF | 540 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 523,500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 508,800 | 97.2% |
| LOAD_FAST | 9,660 | 1.8% |
| LOAD_CONST | 2,640 | 0.5% |
| JUMP_BACKWARD | 2,340 | 0.4% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,689,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,689,080 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,209,480 | 36.5% |
| LOAD_FAST | 853,800 | 25.8% |
| RETURN_VALUE | 637,440 | 19.3% |
| LOAD_ATTR_SLOT | 600,720 | 18.2% |
| JUMP_FORWARD | 7,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,686,600 | 51.0% |
| LOAD_FAST | 855,120 | 25.8% |
| BUILD_STRING | 767,460 | 23.2% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,689,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,689,080 | 100.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,367,900 | 83.3% |
| CALL_KW | 507,660 | 7.9% |
| MAKE_CELL | 479,520 | 7.4% |
| CALL_PY_WITH_DEFAULTS | 32,820 | 0.5% |
| CALL | 28,140 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_YIELD_FROM_ITER | 2,689,080 | 41.7% |
| CALL_TUPLE_1 | 2,381,360 | 37.0% |
| GET_ITER | 523,500 | 8.1% |
| CALL_BUILTIN_CLASS | 396,720 | 6.2% |
| CALL_METHOD_DESCRIPTOR_O | 378,600 | 5.9% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,300 | 86.4% |
| SWAP | 2,340 | 11.0% |
| LOAD_GLOBAL_MODULE | 480 | 2.3% |
| JUMP_FORWARD | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 18,300 | 86.4% |
| SWAP | 2,340 | 11.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 2.3% |
| LOAD_CONST | 60 | 0.3% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,233,480 | 61.6% |
| FORMAT_SIMPLE | 767,460 | 38.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,209,540 | 60.4% |
| RETURN_VALUE | 749,160 | 37.4% |
| JUMP_FORWARD | 30,720 | 1.5% |
| LOAD_FAST | 7,680 | 0.4% |
| LOAD_FAST_LOAD_FAST | 3,840 | 0.2% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,560 | 100.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,709,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 6,709,920 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 197,820 | 67.5% |
| BINARY_OP_ADD_INT | 80,160 | 27.4% |
| LOAD_FAST | 10,800 | 3.7% |
| CALL_FUNCTION_EX | 3,840 | 1.3% |
| BINARY_SUBSCR_DICT | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 185,400 | 63.3% |
| LOAD_FAST | 96,000 | 32.8% |
| CALL_INTRINSIC_1 | 11,520 | 3.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 6,723,960 | 65.7% |
| GET_ITER | 3,511,860 | 34.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 6,723,960 | 65.7% |
| SWAP | 3,511,860 | 34.3% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,750,200 | 97.1% |
| LOAD_FAST | 104,880 | 2.1% |
| JUMP_FORWARD | 38,040 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,893,120 | 100.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,120 | 46.4% |
| RETURN_VALUE | 3,060 | 45.5% |
| LOAD_ATTR_PROPERTY | 540 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,720 | 100.0% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 771,900 | 83.4% |
| FOR_ITER_TUPLE | 131,520 | 14.2% |
| FOR_ITER_LIST | 16,860 | 1.8% |
| YIELD_VALUE | 5,700 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 770,040 | 83.2% |
| TO_BOOL_STR | 130,560 | 14.1% |
| LOAD_ATTR_PROPERTY | 17,820 | 1.9% |
| YIELD_VALUE | 3,120 | 0.3% |
| LOAD_FAST | 2,220 | 0.2% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 109,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 109,260 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 6,709,920 | 41.0% |
| BUILD_TUPLE | 6,482,160 | 39.6% |
| JUMP_FORWARD | 1,654,860 | 10.1% |
| RETURN_VALUE | 856,740 | 5.2% |
| LOAD_FAST | 663,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 6,709,920 | 41.0% |
| INTERPRETER_EXIT | 5,730,180 | 35.0% |
| UNPACK_SEQUENCE_TUPLE | 3,807,480 | 23.2% |
| UNPACK_EX | 109,260 | 0.7% |
| STORE_FAST | 17,940 | 0.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 63,900 | 50.0% |
| LOAD_CONST | 63,900 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 63,900 | 50.0% |
| COMPARE_OP | 63,900 | 50.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 18,360 | 85.5% |
| LOAD_DEREF | 3,120 | 14.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 18,360 | 85.5% |
| GET_ITER | 3,120 | 14.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 50,640 | 68.7% |
| LOAD_CONST | 23,040 | 31.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 50,640 | 68.7% |
| JUMP_FORWARD | 23,040 | 31.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 756,660 | 66.0% |
| RETURN_GENERATOR | 378,600 | 33.0% |
| LOAD_FAST | 10,020 | 0.9% |
| RETURN_VALUE | 360 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 763,260 | 66.6% |
| RETURN_VALUE | 363,240 | 31.7% |
| STORE_FAST | 15,360 | 1.3% |
| LOAD_CONST | 3,840 | 0.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,381,360 | 97.2% |
| LOAD_FAST | 36,720 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 31,560 | 1.3% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,963,980 | 80.2% |
| RETURN_VALUE | 385,020 | 15.7% |
| STORE_FAST | 63,480 | 2.6% |
| JUMP_FORWARD | 36,720 | 1.5% |
| CALL_LEN | 440 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,830,640 | 85.8% |
| GET_ITER | 517,980 | 11.6% |
| EXTENDED_ARG | 112,440 | 2.5% |
| LOAD_FAST | 2,820 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,940,380 | 88.3% |
| POP_TOP | 523,500 | 11.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,286,340 | 76.4% |
| LOAD_FAST | 355,920 | 21.1% |
| SWAP | 41,640 | 2.5% |
| GET_ITER | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,164,540 | 69.1% |
| RETURN_CONST | 355,920 | 21.1% |
| STORE_FAST_LOAD_FAST | 131,520 | 7.8% |
| SWAP | 31,560 | 1.9% |
| LOAD_FAST | 780 | 0.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 6,709,920 | 71.4% |
| LOAD_CONST | 2,689,080 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,709,920 | 71.4% |
| POP_TOP | 2,689,080 | 28.6% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,640 | 84.3% |
| LOAD_FAST_LOAD_FAST | 9,760 | 15.6% |
| STORE_ATTR | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,760 | 38.0% |
| BUILD_LIST | 13,200 | 21.1% |
| LOAD_FAST | 12,120 | 19.4% |
| RETURN_CONST | 5,340 | 8.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 8.5% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,807,480 | 82.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 789,480 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,768,960 | 82.0% |
| STORE_FAST_STORE_FAST | 828,000 | 18.0% |


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
| specialization.deferred |      1067220 | 3.8% |
| specialization.deopt |          480 | 0.0% |
|          hit |     27252660 | 96.1% |
|         miss |        26040 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 57.4% |
| Failure | 400 | 42.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 320 | 80.0% |
| other | 80 | 20.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       977700 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4089480 | 2.6% |
| specialization.deopt |       194720 | 0.1% |
|          hit |    143315760 | 90.9% |
|         miss |     10337840 | 6.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 195,400 | 99.1% |
| Failure | 1,760 | 0.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 920 | 52.3% |
| sequence | 500 | 28.4% |
| dict | 260 | 14.8% |
| tuple | 40 | 2.3% |
| set | 40 | 2.3% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        24540 | 0.1% |
|          hit |     39338400 | 99.9% |
|         miss |          120 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 22.7% |
| Failure | 340 | 77.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 280 | 82.4% |
| add different types | 40 | 11.8% |
| subtract other | 20 | 5.9% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5519700 | 2.7% |
| specialization.deopt |        50300 | 0.0% |
|          hit |    194584900 | 96.0% |
|         miss |      2668080 | 1.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 53,060 | 92.3% |
| Failure | 4,440 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 1,920 | 43.2% |
| bound method | 520 | 11.7% |
| class no vectorcall | 500 | 11.3% |
| cfunc noargs | 320 | 7.2% |
| cfunc varargs keywords | 320 | 7.2% |
| no dict | 320 | 7.2% |
| meth descr varargs | 200 | 4.5% |
| init not python | 160 | 3.6% |
| meth descr varargs keywords | 80 | 1.8% |
| meth descr method fastcall keywords | 40 | 0.9% |
| wrong number arguments | 40 | 0.9% |
| init not simple | 20 | 0.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     18937320 | 39.8% |
|          hit |     28633860 | 60.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 2.7% |
| Failure | 6,480 | 97.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 5,000 | 77.2% |
| different types | 1,000 | 15.4% |
| other | 200 | 3.1% |
| set | 80 | 1.2% |
| big int | 80 | 1.2% |
| string | 80 | 1.2% |
| bool | 40 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     34972320 | 66.3% |
|          hit |     17746200 | 33.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.2% |
| Failure | 9,860 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 6,840 | 69.4% |
| ascii string | 760 | 7.7% |
| dict keys | 760 | 7.7% |
| dict values | 520 | 5.3% |
| enumerate | 480 | 4.9% |
| itertools | 200 | 2.0% |
| set | 140 | 1.4% |
| reversed list | 80 | 0.8% |
| other | 80 | 0.8% |


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
| specialization.deferred |     20181860 | 5.0% |
| specialization.deopt |       298460 | 0.1% |
|          hit |    370342600 | 91.1% |
|         miss |     15832220 | 3.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 301,460 | 94.8% |
| Failure | 16,460 | 5.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 13,740 | 83.5% |
| method | 2,220 | 13.5% |
| mutable class | 380 | 2.3% |
| class method obj | 40 | 0.2% |
| builtin class method | 40 | 0.2% |
| overridden | 40 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           80 | 0.0% |
| specialization.deopt |           40 | 0.0% |
|          hit |    169320580 | 100.0% |
|         miss |         1480 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,480 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      9399000 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |       115600 | 0.2% |
|          hit |     69504900 | 91.9% |
|         miss |      6123520 | 8.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 115,940 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        90420 | 0.4% |
|          hit |     25550640 | 99.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 33.3% |
| Failure | 80 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 80 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,260,978,400 | 44.1% |
| Not specialized | 380,372,860 | 13.3% |
| Specialized | 1,216,909,560 | 42.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 1,475,739,525,896,764,127,260 | 100.0% |
| FOR_ITER | 34,972,320 | 0.0% |
| LOAD_ATTR | 20,181,860 | 0.0% |
| COMPARE_OP | 18,937,320 | 0.0% |
| CALL | 5,519,700 | 0.0% |
| TO_BOOL | 4,089,480 | 0.0% |
| BINARY_SUBSCR | 1,067,220 | 0.0% |
| UNPACK_SEQUENCE | 90,420 | 0.0% |
| BINARY_OP | 24,540 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 9,201,160 | 26.3% |
| STORE_ATTR_SLOT | 6,123,520 | 17.5% |
| TO_BOOL_ALWAYS_TRUE | 5,558,340 | 15.9% |
| TO_BOOL_NONE | 3,467,180 | 9.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,311,660 | 9.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,251,220 | 9.3% |
| CALL_PY_EXACT_ARGS | 1,404,760 | 4.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,227,920 | 3.5% |
| TO_BOOL_STR | 800,560 | 2.3% |
| TO_BOOL_BOOL | 491,320 | 1.4% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 23,386,480 | 18.1% |
| Calls to Python functions inlined | 105,750,020 | 81.9% |
| Calls via PyEval_EvalFrame (total) | 23,386,480 | 18.1% |
| Calls via PyEval_EvalFrame (vector) | 14,425,780 | 11.2% |
| Calls via PyEval_EvalFrame (generator) | 8,960,700 | 6.9% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 14,425,780 | 11.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 2,733,480 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 67,440 | 0.1% |
| Calls via PyEval_EvalFrame (api) | 9,183,580 | 7.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 106,312,980 | 82.3% |
| Frame objects created | 82,620 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 56,884,720 | 31.4% |
| Frees to freelist | 56,980,180 |  |
| Allocations | 124,357,700 | 68.6% |
| Allocations to 512 bytes | 124,272,860 | 68.6% |
| Allocations to 4 kbytes | 84,780 | 0.0% |
| Allocations over 4 kbytes | 60 | 0.0% |
| Frees | 124,879,406 |  |
| New values | 1,320,540 |  |
| Interpreter increfs | 1,274,124,540 | 79.6% |
| Interpreter decrefs | 1,414,403,440 | 80.0% |
| Increfs | 325,829,530 | 20.4% |
| Decrefs | 353,280,248 | 20.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 59,313,018 |  |
| Method cache misses | 2,137,942 |  |
| Method cache collisions | 2,291,061 |  |
| Method cache dunder hits | 88,397,557 |  |
| Method cache dunder misses | 154,923 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 3,560 | 983,660 | 18,608,800 |
| 1 | 300 | 895,560 | 6,951,800 |
| 2 | 40 | 90,480 | 8,591,840 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 80 |


</details>

---
Stats gathered on: 2023-09-27
