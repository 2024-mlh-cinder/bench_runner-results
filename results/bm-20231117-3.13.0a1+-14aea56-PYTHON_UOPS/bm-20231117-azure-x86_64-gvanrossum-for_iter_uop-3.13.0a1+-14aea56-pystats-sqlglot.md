
# Pystats results

- benchmark: sqlglot
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 724,564,960 | 21.4% | 21.4% |  |
| LOAD_ATTR_SLOT | 301,540,280 | 8.9% | 30.4% | 4.0% |
| POP_JUMP_IF_FALSE | 175,247,400 | 5.2% | 35.5% |  |
| RESUME_CHECK | 155,075,400 | 4.6% | 40.1% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 115,820,620 | 3.4% | 43.6% | 0.0% |
| STORE_FAST | 100,079,600 | 3.0% | 46.5% |  |
| STORE_ATTR_SLOT | 91,595,940 | 2.7% | 49.2% | 8.8% |
| TO_BOOL_BOOL | 90,005,480 | 2.7% | 51.9% | 0.7% |
| LOAD_ATTR_METHOD_NO_DICT | 89,216,300 | 2.6% | 54.5% | 0.0% |
| RETURN_VALUE | 80,759,560 | 2.4% | 56.9% |  |
| CALL_PY_EXACT_ARGS | 73,821,720 | 2.2% | 59.1% | 2.5% |
| LOAD_GLOBAL_MODULE | 71,627,560 | 2.1% | 61.2% | 0.0% |
| POP_JUMP_IF_TRUE | 67,425,680 | 2.0% | 63.2% |  |
| LOAD_CONST | 66,655,480 | 2.0% | 65.2% |  |
| POP_TOP | 61,640,580 | 1.8% | 67.0% |  |
| RETURN_CONST | 54,271,520 | 1.6% | 68.6% |  |
| CALL_ISINSTANCE | 54,022,240 | 1.6% | 70.2% |  |
| ENTER_EXECUTOR | 51,241,380 | 1.5% | 71.7% |  |
| LOAD_FAST_LOAD_FAST | 50,489,500 | 1.5% | 73.2% |  |
| COPY | 44,397,380 | 1.3% | 74.5% |  |
| SWAP | 43,764,700 | 1.3% | 75.8% |  |
| TO_BOOL_ALWAYS_TRUE | 38,076,340 | 1.1% | 77.0% | 18.3% |
| COMPARE_OP_INT | 33,154,700 | 1.0% | 77.9% |  |
| BINARY_OP_ADD_INT | 33,075,000 | 1.0% | 78.9% |  |
| INTERPRETER_EXIT | 31,186,120 | 0.9% | 79.8% |  |
| BINARY_SUBSCR_STR_INT | 28,527,760 | 0.8% | 80.7% |  |
| TO_BOOL_NONE | 27,339,020 | 0.8% | 81.5% | 16.9% |
| LOAD_ATTR | 25,654,060 | 0.8% | 82.3% |  |
| COMPARE_OP | 23,812,740 | 0.7% | 83.0% |  |
| CALL_PY_WITH_DEFAULTS | 22,593,800 | 0.7% | 83.6% | 0.2% |
| GET_ITER | 22,593,560 | 0.7% | 84.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 22,572,580 | 0.7% | 85.0% | 0.0% |
| YIELD_VALUE | 21,840,640 | 0.6% | 85.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 21,444,040 | 0.6% | 86.2% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 21,405,400 | 0.6% | 86.9% |  |
| BUILD_TUPLE | 20,877,360 | 0.6% | 87.5% |  |
| BINARY_OP_SUBTRACT_INT | 17,747,380 | 0.5% | 88.0% |  |
| TO_BOOL_STR | 16,494,780 | 0.5% | 88.5% | 6.5% |
| FOR_ITER | 16,369,780 | 0.5% | 89.0% |  |
| STORE_FAST_STORE_FAST | 16,013,720 | 0.5% | 89.5% |  |
| LOAD_DEREF | 15,905,220 | 0.5% | 89.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 15,695,000 | 0.5% | 90.4% |  |
| CALL_BUILTIN_O | 14,327,960 | 0.4% | 90.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,196,900 | 0.4% | 91.2% | 27.8% |
| LOAD_FAST_AND_CLEAR | 13,647,760 | 0.4% | 91.6% |  |
| CONTAINS_OP | 13,555,780 | 0.4% | 92.0% |  |
| SEND_GEN | 12,531,800 | 0.4% | 92.4% |  |
| JUMP_FORWARD | 12,495,180 | 0.4% | 92.8% |  |
| FOR_ITER_LIST | 12,428,780 | 0.4% | 93.2% |  |
| EXTENDED_ARG | 11,983,940 | 0.4% | 93.5% |  |
| PUSH_NULL | 11,410,940 | 0.3% | 93.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 10,645,700 | 0.3% | 94.2% | 40.7% |
| LOAD_ATTR_MODULE | 10,279,140 | 0.3% | 94.5% |  |
| TO_BOOL_INT | 9,042,920 | 0.3% | 94.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 8,946,560 | 0.3% | 95.0% |  |
| LOAD_ATTR_PROPERTY | 8,873,100 | 0.3% | 95.3% | 0.6% |
| RETURN_GENERATOR | 8,590,800 | 0.3% | 95.5% |  |
| CALL | 7,449,380 | 0.2% | 95.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 7,376,340 | 0.2% | 96.0% | 0.5% |
| BUILD_LIST | 6,944,040 | 0.2% | 96.2% |  |
| FOR_ITER_GEN | 5,951,420 | 0.2% | 96.3% |  |
| BUILD_MAP | 5,815,680 | 0.2% | 96.5% |  |
| POP_JUMP_IF_NOT_NONE | 5,762,560 | 0.2% | 96.7% |  |
| CALL_TYPE_1 | 5,572,900 | 0.2% | 96.8% |  |
| NOP | 5,564,940 | 0.2% | 97.0% |  |
| TO_BOOL | 5,494,960 | 0.2% | 97.2% |  |
| JUMP_BACKWARD | 5,327,000 | 0.2% | 97.3% |  |
| BINARY_SUBSCR_LIST_INT | 5,302,640 | 0.2% | 97.5% | 0.7% |
| UNPACK_SEQUENCE_TUPLE | 5,121,160 | 0.2% | 97.6% |  |
| COPY_FREE_VARS | 5,035,420 | 0.1% | 97.8% |  |
| MAKE_FUNCTION | 4,697,460 | 0.1% | 97.9% |  |
| MAP_ADD | 4,591,920 | 0.1% | 98.1% |  |
| FORMAT_SIMPLE | 4,412,240 | 0.1% | 98.2% |  |
| CALL_LIST_APPEND | 4,181,060 | 0.1% | 98.3% |  |
| UNARY_NOT | 4,102,720 | 0.1% | 98.4% |  |
| BINARY_SLICE | 3,679,120 | 0.1% | 98.5% |  |
| END_SEND | 3,585,440 | 0.1% | 98.6% |  |
| GET_YIELD_FROM_ITER | 3,585,440 | 0.1% | 98.8% |  |
| CALL_BUILTIN_FAST | 3,378,720 | 0.1% | 98.9% | 0.1% |
| IS_OP | 3,345,400 | 0.1% | 99.0% |  |
| CALL_TUPLE_1 | 3,265,960 | 0.1% | 99.1% |  |
| MAKE_CELL | 3,194,560 | 0.1% | 99.1% |  |
| CALL_KW | 2,683,280 | 0.1% | 99.2% |  |
| BUILD_STRING | 2,667,920 | 0.1% | 99.3% |  |
| COMPARE_OP_STR | 2,451,080 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,363,020 | 0.1% | 99.4% | 69.1% |
| BINARY_SUBSCR_DICT | 2,286,380 | 0.1% | 99.5% |  |
| POP_JUMP_IF_NONE | 1,813,680 | 0.1% | 99.6% |  |
| CALL_LEN | 1,775,300 | 0.1% | 99.6% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,590,740 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,353,900 | 0.0% | 99.7% |  |
| STORE_SUBSCR_DICT | 1,295,180 | 0.0% | 99.7% |  |
| CALL_FUNCTION_EX | 1,216,640 | 0.0% | 99.8% |  |
| DICT_MERGE | 1,177,100 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 1,129,680 | 0.0% | 99.8% |  |
| FOR_ITER_TUPLE | 1,064,300 | 0.0% | 99.9% |  |
| END_FOR | 697,940 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 642,060 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 546,740 | 0.0% | 99.9% |  |
| LIST_APPEND | 330,260 | 0.0% | 99.9% |  |
| STORE_DEREF | 221,680 | 0.0% | 100.0% |  |
| UNPACK_EX | 145,680 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 123,800 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 118,580 | 0.0% | 100.0% | 23.3% |
| CHECK_EXC_MATCH | 110,160 | 0.0% | 100.0% |  |
| POP_EXCEPT | 110,160 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 110,160 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 98,180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 84,560 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 82,720 | 0.0% | 100.0% |  |
| LIST_EXTEND | 75,840 | 0.0% | 100.0% |  |
| CALL_STR_1 | 73,060 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 65,680 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 65,600 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 61,920 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 57,480 | 0.0% | 100.0% |  |
| BINARY_OP | 36,200 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 28,560 | 0.0% | 100.0% |  |
| BUILD_SET | 27,960 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 22,740 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 20,580 | 0.0% | 100.0% |  |
| DICT_UPDATE | 16,480 | 0.0% | 100.0% |  |
| RESUME | 14,660 | 0.0% | 100.0% | 19.9% |
| BINARY_OP_SUBTRACT_FLOAT | 10,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 10,200 | 0.0% | 100.0% | 1.2% |
| STORE_ATTR | 8,740 | 0.0% | 100.0% |  |
| IMPORT_NAME | 6,080 | 0.0% | 100.0% |  |
| SET_ADD | 5,660 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,200 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 1,080 | 0.0% | 100.0% |  |
| SEND | 400 | 0.0% | 100.0% |  |
| SET_UPDATE | 80 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 60 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 242,240,360 | 7.2% | 7.2% |
| LOAD_ATTR_SLOT LOAD_FAST | 117,188,560 | 3.5% | 10.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 111,649,720 | 3.3% | 13.9% |
| RESUME_CHECK LOAD_FAST | 90,740,220 | 2.7% | 16.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 74,843,360 | 2.2% | 18.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 64,545,420 | 1.9% | 20.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 63,001,380 | 1.9% | 22.6% |
| STORE_ATTR_SLOT LOAD_FAST | 61,450,740 | 1.8% | 24.4% |
| LOAD_FAST STORE_ATTR_SLOT | 51,520,060 | 1.5% | 26.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 51,403,160 | 1.5% | 27.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 41,528,480 | 1.2% | 28.7% |
| STORE_FAST LOAD_FAST | 40,636,340 | 1.2% | 29.9% |
| LOAD_FAST COPY | 37,624,400 | 1.1% | 31.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 36,995,760 | 1.1% | 32.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 36,476,420 | 1.1% | 33.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 32,192,200 | 1.0% | 34.1% |
| LOAD_FAST BINARY_OP_ADD_INT | 29,977,520 | 0.9% | 35.0% |
| BINARY_OP_ADD_INT SWAP | 29,274,020 | 0.9% | 35.9% |
| COPY LOAD_ATTR_SLOT | 29,273,720 | 0.9% | 36.8% |
| SWAP STORE_ATTR_SLOT | 29,273,720 | 0.9% | 37.6% |
| LOAD_ATTR_SLOT COMPARE_OP_INT | 28,539,360 | 0.8% | 38.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 28,531,240 | 0.8% | 39.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 27,517,800 | 0.8% | 40.1% |
| BINARY_SUBSCR_STR_INT LOAD_FAST | 27,411,680 | 0.8% | 40.9% |
| CACHE RESUME_CHECK | 26,851,500 | 0.8% | 41.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 25,792,740 | 0.8% | 42.5% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 24,850,400 | 0.7% | 43.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 23,251,160 | 0.7% | 43.9% |
| RETURN_CONST POP_TOP | 22,235,040 | 0.7% | 44.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 21,888,740 | 0.6% | 45.2% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_NO_DICT | 21,655,100 | 0.6% | 45.9% |
| COMPARE_OP POP_JUMP_IF_FALSE | 21,589,440 | 0.6% | 46.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 21,558,080 | 0.6% | 47.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 21,461,820 | 0.6% | 47.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 21,439,480 | 0.6% | 48.4% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 20,772,040 | 0.6% | 49.0% |
| LOAD_ATTR_SLOT LOAD_CONST | 20,632,240 | 0.6% | 49.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 20,210,120 | 0.6% | 50.2% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 19,637,480 | 0.6% | 50.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 19,431,140 | 0.6% | 51.4% |
| POP_TOP LOAD_FAST | 18,793,700 | 0.6% | 51.9% |
| LOAD_FAST RETURN_VALUE | 18,392,700 | 0.5% | 52.5% |
| STORE_ATTR_SLOT RETURN_CONST | 18,351,200 | 0.5% | 53.0% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 18,166,640 | 0.5% | 53.6% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 17,918,820 | 0.5% | 54.1% |
| LOAD_ATTR_SLOT TO_BOOL_ALWAYS_TRUE | 17,749,040 | 0.5% | 54.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 17,622,620 | 0.5% | 55.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 16,285,440 | 0.5% | 55.6% |
| RETURN_VALUE STORE_FAST | 16,116,560 | 0.5% | 56.1% |
| RETURN_VALUE INTERPRETER_EXIT | 16,014,220 | 0.5% | 56.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 15,650,260 | 0.5% | 57.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 14,456,040 | 0.4% | 57.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 14,392,320 | 0.4% | 57.9% |
| RETURN_CONST TO_BOOL_NONE | 14,140,280 | 0.4% | 58.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 13,918,960 | 0.4% | 58.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS GET_ITER | 13,735,960 | 0.4% | 59.1% |
| COMPARE_OP_INT LOAD_FAST | 13,711,520 | 0.4% | 59.5% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_STR_INT | 13,711,440 | 0.4% | 59.9% |
| LOAD_ATTR_SLOT BINARY_SUBSCR_STR_INT | 13,700,080 | 0.4% | 60.3% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 13,335,260 | 0.4% | 60.7% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 13,206,240 | 0.4% | 61.1% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 13,080,540 | 0.4% | 61.5% |
| RESUME_CHECK POP_TOP | 12,893,500 | 0.4% | 61.9% |
| RETURN_VALUE RETURN_VALUE | 12,521,680 | 0.4% | 62.3% |
| CALL_BUILTIN_O RETURN_VALUE | 12,193,580 | 0.4% | 62.6% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 12,176,480 | 0.4% | 63.0% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 11,840,700 | 0.4% | 63.3% |
| LOAD_FAST COMPARE_OP | 11,476,080 | 0.3% | 63.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 11,456,580 | 0.3% | 64.0% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 10,882,060 | 0.3% | 64.3% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 10,870,600 | 0.3% | 64.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT LOAD_ATTR_METHOD_NO_DICT | 10,809,800 | 0.3% | 65.0% |
| TO_BOOL_STR POP_JUMP_IF_TRUE | 10,804,940 | 0.3% | 65.3% |
| LOAD_ATTR_SLOT CALL_METHOD_DESCRIPTOR_FAST | 10,713,200 | 0.3% | 65.6% |
| LOAD_FAST TO_BOOL_BOOL | 10,705,860 | 0.3% | 65.9% |
| LOAD_FAST TO_BOOL_NONE | 10,703,500 | 0.3% | 66.3% |
| LOAD_FAST BUILD_TUPLE | 10,486,000 | 0.3% | 66.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 10,476,140 | 0.3% | 66.9% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 10,292,720 | 0.3% | 67.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 10,266,820 | 0.3% | 67.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 9,799,980 | 0.3% | 67.8% |
| EXTENDED_ARG ENTER_EXECUTOR | 9,738,540 | 0.3% | 68.1% |
| LOAD_ATTR COMPARE_OP | 9,718,080 | 0.3% | 68.3% |
| POP_TOP ENTER_EXECUTOR | 9,592,740 | 0.3% | 68.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,435,120 | 0.3% | 68.9% |
| POP_JUMP_IF_TRUE EXTENDED_ARG | 9,377,840 | 0.3% | 69.2% |
| STORE_FAST STORE_FAST | 9,082,160 | 0.3% | 69.5% |
| LOAD_ATTR_SLOT CALL_ISINSTANCE | 9,037,700 | 0.3% | 69.7% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 9,031,580 | 0.3% | 70.0% |
| LOAD_ATTR_SLOT TO_BOOL_INT | 9,024,320 | 0.3% | 70.3% |
| LOAD_ATTR_SLOT TO_BOOL_STR | 9,013,120 | 0.3% | 70.5% |
| LOAD_FAST_AND_CLEAR LOAD_FAST_AND_CLEAR | 8,965,280 | 0.3% | 70.8% |
| YIELD_VALUE YIELD_VALUE | 8,946,560 | 0.3% | 71.1% |
| SEND_GEN RESUME_CHECK | 8,946,460 | 0.3% | 71.3% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 8,946,440 | 0.3% | 71.6% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 8,946,400 | 0.3% | 71.9% |
| LOAD_FAST LOAD_CONST | 8,865,140 | 0.3% | 72.1% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 8,820,740 | 0.3% | 72.4% |
| GET_ITER FOR_ITER | 8,728,720 | 0.3% | 72.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 8,727,480 | 0.3% | 72.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 3,608,880 | 98.1% |
| LOAD_CONST | 70,160 | 1.9% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,608,960 | 98.1% |
| CALL_BUILTIN_CLASS | 42,000 | 1.1% |
| GET_ITER | 16,800 | 0.5% |
| TO_BOOL_LIST | 11,200 | 0.3% |
| TO_BOOL | 80 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 26,851,500 | 86.1% |
| POP_TOP | 4,307,780 | 13.8% |
| MAKE_CELL | 24,560 | 0.1% |
| RESUME | 2,280 | 0.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,116,000 | 70.2% |
| ENTER_EXECUTOR | 411,960 | 25.9% |
| LOAD_ATTR_SLOT | 62,640 | 3.9% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,590,740 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,480 | 59.3% |
| LOAD_FAST_LOAD_FAST | 6,960 | 30.6% |
| BINARY_SUBSCR | 660 | 2.9% |
| LOAD_FAST | 520 | 2.3% |
| LOAD_ATTR | 320 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 18,720 | 82.3% |
| BINARY_SUBSCR_DICT | 740 | 3.3% |
| BINARY_SUBSCR | 660 | 2.9% |
| BINARY_SUBSCR_LIST_INT | 440 | 1.9% |
| STORE_FAST | 340 | 1.5% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 110,020 | 99.9% |
| LOAD_GLOBAL | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 110,160 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 697,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 678,360 | 97.2% |
| LOAD_FAST | 12,860 | 1.8% |
| LOAD_CONST | 3,520 | 0.5% |
| ENTER_EXECUTOR | 2,620 | 0.4% |
| JUMP_BACKWARD | 500 | 0.1% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,585,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,585,440 | 100.0% |


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
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,612,580 | 36.5% |
| LOAD_FAST | 1,138,400 | 25.8% |
| RETURN_VALUE | 849,920 | 19.3% |
| LOAD_ATTR_SLOT | 800,800 | 18.1% |
| JUMP_FORWARD | 10,240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,248,800 | 51.0% |
| LOAD_FAST | 1,140,160 | 25.8% |
| BUILD_STRING | 1,023,280 | 23.2% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 13,735,960 | 60.8% |
| LOAD_FAST | 6,182,300 | 27.4% |
| LOAD_ATTR_SLOT | 1,132,660 | 5.0% |
| RETURN_GENERATOR | 698,000 | 3.1% |
| BUILD_TUPLE | 458,720 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 8,728,720 | 38.6% |
| FOR_ITER_LIST | 4,851,680 | 21.5% |
| LOAD_FAST_AND_CLEAR | 4,682,480 | 20.7% |
| CALL_PY_EXACT_ARGS | 3,605,080 | 16.0% |
| FOR_ITER_GEN | 690,240 | 3.1% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,585,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,585,440 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 16,014,220 | 51.4% |
| YIELD_VALUE | 7,640,600 | 24.5% |
| RETURN_CONST | 7,531,300 | 24.1% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,697,460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,618,560 | 55.7% |
| SET_FUNCTION_ATTRIBUTE | 1,128,400 | 24.0% |
| LOAD_FAST | 950,340 | 20.2% |
| LOAD_GLOBAL | 80 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,621,800 | 83.1% |
| POP_JUMP_IF_FALSE | 506,800 | 9.1% |
| STORE_FAST | 435,280 | 7.8% |
| POP_JUMP_IF_TRUE | 480 | 0.0% |
| POP_TOP | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,345,200 | 78.1% |
| LOAD_FAST | 1,198,940 | 21.5% |
| LOAD_GLOBAL_MODULE | 18,760 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 1,380 | 0.0% |
| LOAD_DEREF | 320 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 57,560 | 52.3% |
| POP_TOP | 52,560 | 47.7% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 91,760 | 83.3% |
| JUMP_FORWARD | 18,400 | 16.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 22,235,040 | 36.1% |
| RESUME_CHECK | 12,893,500 | 20.9% |
| POP_JUMP_IF_FALSE | 5,979,520 | 9.7% |
| STORE_FAST | 5,029,440 | 8.2% |
| CACHE | 4,307,780 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,793,700 | 30.5% |
| ENTER_EXECUTOR | 9,592,740 | 15.6% |
| RESUME_CHECK | 8,590,100 | 13.9% |
| STORE_FAST | 5,025,280 | 8.2% |
| LOAD_GLOBAL_BUILTIN | 4,182,040 | 6.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 75,960 | 69.0% |
| BINARY_SUBSCR_LIST_INT | 34,080 | 30.9% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 109,880 | 99.7% |
| LOAD_GLOBAL | 280 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,855,220 | 68.8% |
| CALL_BUILTIN_FAST | 1,612,560 | 14.1% |
| LOAD_ATTR_MODULE | 1,113,040 | 9.8% |
| LOAD_DEREF | 317,280 | 2.8% |
| LOAD_FAST_LOAD_FAST | 254,320 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,628,740 | 40.6% |
| LOAD_FAST | 3,410,260 | 29.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,175,380 | 10.3% |
| LOAD_CONST | 1,057,700 | 9.3% |
| CALL_PY_EXACT_ARGS | 947,540 | 8.3% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,086,120 | 82.5% |
| CALL_KW | 676,880 | 7.9% |
| MAKE_CELL | 639,360 | 7.4% |
| ENTER_EXECUTOR | 70,700 | 0.8% |
| CALL_PY_WITH_DEFAULTS | 43,660 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_YIELD_FROM_ITER | 3,585,440 | 41.7% |
| CALL_TUPLE_1 | 3,174,760 | 37.0% |
| GET_ITER | 698,000 | 8.1% |
| CALL_BUILTIN_CLASS | 528,600 | 6.2% |
| CALL_METHOD_DESCRIPTOR_O | 504,520 | 5.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,392,700 | 22.8% |
| RETURN_VALUE | 12,521,680 | 15.5% |
| CALL_BUILTIN_O | 12,193,580 | 15.1% |
| STORE_FAST | 4,443,360 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 4,322,320 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,116,560 | 20.0% |
| INTERPRETER_EXIT | 16,014,220 | 19.8% |
| RETURN_VALUE | 12,521,680 | 15.5% |
| LOAD_ATTR_METHOD_NO_DICT | 6,072,460 | 7.5% |
| LOAD_FAST | 5,770,640 | 7.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 33.3% |
| LOAD_FAST_LOAD_FAST | 320 | 29.6% |
| RETURN_VALUE | 120 | 11.1% |
| CALL | 120 | 11.1% |
| CALL_BUILTIN_O | 120 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 540 | 50.0% |
| JUMP_BACKWARD | 280 | 25.9% |
| LOAD_FAST | 160 | 14.8% |
| POP_EXCEPT | 40 | 3.7% |
| LOAD_GLOBAL | 40 | 3.7% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,451,840 | 99.2% |
| COPY | 13,460 | 0.2% |
| RETURN_CONST | 10,040 | 0.2% |
| CALL | 4,680 | 0.1% |
| TO_BOOL | 4,500 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,455,020 | 99.3% |
| POP_JUMP_IF_TRUE | 15,300 | 0.3% |
| TO_BOOL_BOOL | 8,480 | 0.2% |
| TO_BOOL_NONE | 7,660 | 0.1% |
| TO_BOOL | 4,500 | 0.1% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,084,160 | 99.5% |
| TO_BOOL_ALWAYS_TRUE | 14,400 | 0.4% |
| TO_BOOL_NONE | 3,980 | 0.1% |
| TO_BOOL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,022,400 | 98.0% |
| COPY | 61,920 | 1.5% |
| STORE_FAST | 18,400 | 0.4% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 28,480 | 78.7% |
| LOAD_FAST_LOAD_FAST | 2,480 | 6.9% |
| LOAD_CONST | 1,400 | 3.9% |
| BINARY_OP | 900 | 2.5% |
| LOAD_FAST | 800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 28,380 | 78.4% |
| GET_ITER | 2,080 | 5.7% |
| STORE_FAST | 1,520 | 4.2% |
| BINARY_OP | 900 | 2.5% |
| LOAD_FAST_LOAD_FAST | 800 | 2.2% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 65,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 21,120 | 32.2% |
| LOAD_FAST | 20,800 | 31.7% |
| LOAD_DEREF | 20,640 | 31.4% |
| CALL_FUNCTION_EX | 2,720 | 4.1% |
| STORE_FAST | 400 | 0.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,663,460 | 81.6% |
| STORE_FAST | 503,100 | 7.2% |
| SWAP | 198,480 | 2.9% |
| LOAD_CONST | 173,440 | 2.5% |
| STORE_ATTR_SLOT | 84,400 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,021,900 | 57.9% |
| COMPARE_OP | 1,168,240 | 16.8% |
| STORE_FAST | 1,062,200 | 15.3% |
| LOAD_FAST | 229,920 | 3.3% |
| SWAP | 198,480 | 2.9% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,480,880 | 77.0% |
| LOAD_CONST | 1,096,800 | 18.9% |
| RESUME_CHECK | 63,660 | 1.1% |
| POP_JUMP_IF_NOT_NONE | 57,600 | 1.0% |
| BUILD_TUPLE | 27,760 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,480,880 | 77.0% |
| LOAD_FAST | 1,054,860 | 18.1% |
| STORE_FAST | 137,160 | 2.4% |
| LOAD_GLOBAL_MODULE | 51,280 | 0.9% |
| LOAD_DEREF | 49,440 | 0.9% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,400 | 87.3% |
| SWAP | 3,120 | 11.2% |
| LOAD_GLOBAL_MODULE | 340 | 1.2% |
| JUMP_FORWARD | 80 | 0.3% |
| LOAD_GLOBAL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,360 | 87.1% |
| SWAP | 3,120 | 11.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 320 | 1.1% |
| LOAD_CONST | 80 | 0.3% |
| CALL | 40 | 0.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,644,640 | 61.6% |
| FORMAT_SIMPLE | 1,023,280 | 38.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,612,720 | 60.4% |
| RETURN_VALUE | 998,880 | 37.4% |
| JUMP_FORWARD | 40,960 | 1.5% |
| LOAD_FAST | 10,240 | 0.4% |
| LOAD_FAST_LOAD_FAST | 5,120 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,486,000 | 50.2% |
| LOAD_GLOBAL_BUILTIN | 3,854,300 | 18.5% |
| CALL_TUPLE_1 | 2,618,600 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,446,360 | 11.7% |
| RETURN_VALUE | 460,960 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 6,851,960 | 32.8% |
| CALL_BUILTIN_O | 5,230,280 | 25.1% |
| CALL_ISINSTANCE | 4,366,020 | 20.9% |
| LOAD_CONST | 1,140,460 | 5.5% |
| RETURN_VALUE | 1,137,680 | 5.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,222,640 | 56.7% |
| LOAD_CONST | 1,546,080 | 20.8% |
| LOAD_ATTR_SLOT | 1,427,720 | 19.2% |
| BUILD_LIST | 44,120 | 0.6% |
| LOAD_ATTR_MODULE | 42,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 4,175,220 | 56.0% |
| LOAD_FAST | 1,437,520 | 19.3% |
| CALL_LIST_APPEND | 1,427,500 | 19.2% |
| STORE_FAST | 108,020 | 1.5% |
| TO_BOOL_BOOL | 61,800 | 0.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 1,177,100 | 96.8% |
| ENTER_EXECUTOR | 16,100 | 1.3% |
| BUILD_MAP | 15,360 | 1.3% |
| RETURN_GENERATOR | 4,160 | 0.3% |
| BUILD_CONST_KEY_MAP | 2,720 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 988,240 | 81.2% |
| RETURN_VALUE | 116,880 | 9.6% |
| RESUME_CHECK | 87,540 | 7.2% |
| LOAD_ATTR_METHOD_NO_DICT | 11,160 | 0.9% |
| LIST_APPEND | 5,120 | 0.4% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 50,240 | 76.6% |
| LIST_APPEND | 15,360 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 39,920 | 60.9% |
| BUILD_MAP | 24,880 | 37.9% |
| CALL_FUNCTION_EX | 800 | 1.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,679,220 | 99.8% |
| ENTER_EXECUTOR | 4,060 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,151,380 | 42.9% |
| RETURN_GENERATOR | 676,880 | 25.2% |
| RETURN_VALUE | 665,760 | 24.8% |
| MAKE_CELL | 137,760 | 5.1% |
| STORE_FAST | 44,160 | 1.6% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,476,080 | 48.2% |
| LOAD_ATTR | 9,718,080 | 40.8% |
| BUILD_LIST | 1,168,240 | 4.9% |
| RETURN_VALUE | 907,160 | 3.8% |
| CALL_BUILTIN_CLASS | 263,720 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,589,440 | 90.7% |
| POP_JUMP_IF_TRUE | 1,211,980 | 5.1% |
| RETURN_VALUE | 909,960 | 3.8% |
| COPY | 62,500 | 0.3% |
| STORE_FAST | 20,640 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,573,440 | 41.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,116,460 | 30.4% |
| LOAD_FAST_LOAD_FAST | 1,900,220 | 14.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,875,220 | 13.8% |
| BUILD_TUPLE | 60,020 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,292,720 | 75.9% |
| POP_JUMP_IF_TRUE | 2,126,260 | 15.7% |
| STORE_FAST | 1,136,800 | 8.4% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,624,400 | 84.7% |
| IS_OP | 2,631,360 | 5.9% |
| CALL_ISINSTANCE | 2,056,940 | 4.6% |
| RETURN_CONST | 1,623,600 | 3.7% |
| RETURN_VALUE | 281,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 29,273,720 | 65.9% |
| TO_BOOL_ALWAYS_TRUE | 7,762,500 | 17.5% |
| TO_BOOL_BOOL | 5,224,540 | 11.8% |
| TO_BOOL_NONE | 1,899,200 | 4.3% |
| TO_BOOL_STR | 165,680 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,175,220 | 82.9% |
| CALL_PY_EXACT_ARGS | 774,720 | 15.4% |
| ENTER_EXECUTOR | 63,280 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 18,220 | 0.4% |
| CALL_FUNCTION_EX | 2,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,998,800 | 99.3% |
| RETURN_GENERATOR | 36,080 | 0.7% |
| RESUME | 540 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,036,460 | 88.1% |
| RETURN_VALUE | 51,360 | 4.4% |
| LOAD_DEREF | 49,440 | 4.2% |
| BUILD_CONST_KEY_MAP | 21,120 | 1.8% |
| DICT_UPDATE | 16,480 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,177,100 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,480 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 9,738,540 | 19.0% |
| POP_TOP | 9,592,740 | 18.7% |
| POP_JUMP_IF_TRUE | 7,486,360 | 14.6% |
| FOR_ITER_LIST | 6,292,960 | 12.3% |
| MAP_ADD | 4,589,460 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 13,206,240 | 25.8% |
| FOR_ITER_LIST | 7,323,100 | 14.3% |
| RETURN_CONST | 7,217,120 | 14.1% |
| SWAP | 4,433,040 | 8.7% |
| LOAD_FAST | 3,263,360 | 6.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,377,840 | 78.3% |
| TO_BOOL_BOOL | 1,446,080 | 12.1% |
| POP_TOP | 476,340 | 4.0% |
| TO_BOOL_NONE | 448,340 | 3.7% |
| JUMP_BACKWARD | 152,240 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,738,540 | 81.3% |
| POP_JUMP_IF_FALSE | 1,894,980 | 15.8% |
| FOR_ITER_GEN | 149,840 | 1.3% |
| JUMP_BACKWARD | 120,980 | 1.0% |
| JUMP_FORWARD | 30,960 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,728,720 | 53.3% |
| SWAP | 4,440,000 | 27.1% |
| LOAD_FAST | 3,132,420 | 19.1% |
| EXTENDED_ARG | 29,360 | 0.2% |
| JUMP_BACKWARD | 26,340 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 13,335,260 | 81.5% |
| STORE_FAST | 2,484,440 | 15.2% |
| STORE_FAST_LOAD_FAST | 515,420 | 3.1% |
| FOR_ITER | 12,940 | 0.1% |
| LOAD_FAST | 8,260 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,080 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 2,631,280 | 78.7% |
| LOAD_FAST_LOAD_FAST | 508,560 | 15.2% |
| LOAD_ATTR_INSTANCE_VALUE | 145,660 | 4.4% |
| LOAD_DEREF | 54,680 | 1.6% |
| LOAD_GLOBAL_MODULE | 5,120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,631,360 | 78.7% |
| POP_JUMP_IF_FALSE | 707,560 | 21.2% |
| RETURN_VALUE | 6,480 | 0.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,499,980 | 46.9% |
| POP_JUMP_IF_FALSE | 1,705,580 | 32.0% |
| POP_JUMP_IF_TRUE | 889,740 | 16.7% |
| EXTENDED_ARG | 120,980 | 2.3% |
| STORE_ATTR_SLOT | 47,960 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,107,200 | 95.9% |
| EXTENDED_ARG | 152,240 | 2.9% |
| FOR_ITER | 26,340 | 0.5% |
| FOR_ITER_LIST | 22,420 | 0.4% |
| LOAD_FAST | 8,800 | 0.2% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,946,400 | 100.0% |
| RESUME | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 8,946,440 | 100.0% |
| SEND | 120 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,165,680 | 33.3% |
| RETURN_VALUE | 3,594,600 | 28.8% |
| STORE_FAST | 1,905,840 | 15.3% |
| POP_JUMP_IF_FALSE | 1,448,540 | 11.6% |
| STORE_ATTR_SLOT | 412,740 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,139,680 | 33.1% |
| LOAD_FAST | 3,433,900 | 27.5% |
| YIELD_VALUE | 2,206,480 | 17.7% |
| STORE_FAST | 1,956,640 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 315,240 | 2.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 217,020 | 65.7% |
| BINARY_OP_ADD_INT | 94,000 | 28.5% |
| LOAD_FAST | 13,660 | 4.1% |
| CALL_FUNCTION_EX | 5,120 | 1.6% |
| BINARY_SUBSCR_DICT | 380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 182,620 | 55.3% |
| LOAD_FAST | 128,000 | 38.8% |
| CALL_INTRINSIC_1 | 15,360 | 4.7% |
| JUMP_BACKWARD | 4,280 | 1.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 49,760 | 65.6% |
| STORE_FAST | 25,600 | 33.8% |
| CALL | 480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 50,240 | 66.2% |
| LOAD_FAST | 25,600 | 33.8% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 23,251,160 | 90.6% |
| LOAD_FAST | 2,165,920 | 8.4% |
| LOAD_ATTR_MODULE | 92,700 | 0.4% |
| LOAD_ATTR | 68,220 | 0.3% |
| LOAD_DEREF | 28,480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,882,060 | 42.4% |
| COMPARE_OP | 9,718,080 | 37.9% |
| LOAD_FAST | 2,063,060 | 8.0% |
| LOAD_GLOBAL_MODULE | 910,360 | 3.5% |
| CALL_PY_WITH_DEFAULTS | 859,000 | 3.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 20,632,240 | 31.0% |
| LOAD_FAST | 8,865,140 | 13.3% |
| STORE_FAST | 5,729,360 | 8.6% |
| LOAD_ATTR_METHOD_NO_DICT | 5,623,520 | 8.4% |
| GET_YIELD_FROM_ITER | 3,585,440 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 16,285,440 | 24.4% |
| LOAD_FAST | 7,777,560 | 11.7% |
| STORE_FAST | 7,394,960 | 11.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,978,060 | 7.5% |
| MAKE_FUNCTION | 4,697,460 | 7.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,233,340 | 51.8% |
| POP_JUMP_IF_FALSE | 2,849,840 | 17.9% |
| RESUME_CHECK | 1,964,280 | 12.3% |
| STORE_FAST | 1,113,120 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 366,460 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 8,352,640 | 52.5% |
| LOAD_ATTR_METHOD_NO_DICT | 4,959,540 | 31.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 797,360 | 5.0% |
| RETURN_VALUE | 333,440 | 2.1% |
| PUSH_NULL | 317,280 | 2.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,188,560 | 16.2% |
| POP_JUMP_IF_FALSE | 111,649,720 | 15.4% |
| RESUME_CHECK | 90,740,220 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 74,843,360 | 10.3% |
| STORE_ATTR_SLOT | 61,450,740 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 242,240,360 | 33.4% |
| STORE_ATTR_SLOT | 51,520,060 | 7.1% |
| LOAD_ATTR_METHOD_NO_DICT | 41,528,480 | 5.7% |
| COPY | 37,624,400 | 5.2% |
| LOAD_GLOBAL_BUILTIN | 32,192,200 | 4.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 8,965,280 | 65.7% |
| GET_ITER | 4,682,480 | 34.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 8,965,280 | 65.7% |
| SWAP | 4,682,480 | 34.3% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 61,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 61,800 | 99.8% |
| TO_BOOL | 120 | 0.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,435,120 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 6,055,580 | 12.0% |
| STORE_ATTR_SLOT | 5,182,240 | 10.3% |
| POP_JUMP_IF_FALSE | 4,766,220 | 9.4% |
| PUSH_NULL | 4,628,740 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,392,320 | 28.5% |
| STORE_ATTR_SLOT | 10,476,140 | 20.7% |
| BINARY_SUBSCR_LIST_INT | 4,365,440 | 8.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,483,800 | 6.9% |
| CALL_BUILTIN_FAST | 3,220,440 | 6.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,000 | 15.7% |
| LOAD_ATTR | 8,940 | 15.6% |
| STORE_FAST | 7,660 | 13.3% |
| POP_JUMP_IF_FALSE | 7,280 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 6,280 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20,120 | 35.0% |
| LOAD_ATTR | 12,700 | 22.1% |
| LOAD_FAST | 10,100 | 17.6% |
| LOAD_GLOBAL_BUILTIN | 8,620 | 15.0% |
| LOAD_FAST_LOAD_FAST | 2,400 | 4.2% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,380,560 | 43.2% |
| MAKE_CELL | 764,120 | 23.9% |
| CALL_PY_WITH_DEFAULTS | 658,640 | 20.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 227,080 | 7.1% |
| CALL_KW | 137,760 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,790,240 | 56.0% |
| MAKE_CELL | 764,120 | 23.9% |
| RETURN_GENERATOR | 639,360 | 20.0% |
| RESUME | 840 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,401,800 | 95.9% |
| LOAD_FAST | 139,400 | 3.0% |
| JUMP_FORWARD | 50,720 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,589,460 | 99.9% |
| JUMP_BACKWARD | 2,460 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 63,001,380 | 35.9% |
| COMPARE_OP | 21,589,440 | 12.3% |
| TO_BOOL_NONE | 20,772,040 | 11.9% |
| COMPARE_OP_INT | 19,431,140 | 11.1% |
| TO_BOOL_ALWAYS_TRUE | 13,080,540 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 111,649,720 | 63.7% |
| RETURN_CONST | 21,558,080 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 8,727,480 | 5.0% |
| LOAD_GLOBAL_MODULE | 7,216,560 | 4.1% |
| POP_TOP | 5,979,520 | 3.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,766,080 | 97.4% |
| LOAD_ATTR_INSTANCE_VALUE | 37,280 | 2.1% |
| BINARY_SUBSCR_LIST_INT | 10,260 | 0.6% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,750,560 | 96.5% |
| LOAD_GLOBAL_BUILTIN | 51,600 | 2.8% |
| LOAD_FAST_LOAD_FAST | 10,320 | 0.6% |
| LOAD_GLOBAL_MODULE | 620 | 0.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,232,420 | 90.8% |
| ENTER_EXECUTOR | 505,900 | 8.8% |
| LOAD_ATTR_INSTANCE_VALUE | 12,020 | 0.2% |
| LOAD_ATTR_SLOT | 10,800 | 0.2% |
| STORE_FAST_LOAD_FAST | 1,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,916,160 | 68.0% |
| LOAD_FAST | 1,701,680 | 29.5% |
| BUILD_LIST | 63,160 | 1.1% |
| BUILD_MAP | 57,600 | 1.0% |
| LOAD_GLOBAL_MODULE | 18,360 | 0.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 24,850,400 | 36.9% |
| TO_BOOL_BOOL | 21,461,820 | 31.8% |
| TO_BOOL_STR | 10,804,940 | 16.0% |
| TO_BOOL_NONE | 6,028,140 | 8.9% |
| CONTAINS_OP | 2,126,260 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,995,760 | 54.9% |
| EXTENDED_ARG | 9,377,840 | 13.9% |
| ENTER_EXECUTOR | 7,486,360 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 3,997,400 | 5.9% |
| STORE_FAST | 3,661,280 | 5.4% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,558,080 | 39.7% |
| STORE_ATTR_SLOT | 18,351,200 | 33.8% |
| ENTER_EXECUTOR | 7,217,120 | 13.3% |
| POP_TOP | 3,598,140 | 6.6% |
| POP_JUMP_IF_TRUE | 2,180,320 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 22,235,040 | 41.0% |
| TO_BOOL_NONE | 14,140,280 | 26.1% |
| INTERPRETER_EXIT | 7,531,300 | 13.9% |
| END_SEND | 3,585,440 | 6.6% |
| RETURN_VALUE | 1,780,700 | 3.3% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 70.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 120 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 200 | 50.0% |
| SEND_GEN | 200 | 50.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,200 | 56.5% |
| LOAD_ATTR_PROPERTY | 1,580 | 27.9% |
| LOAD_FAST | 860 | 15.2% |
| LOAD_ATTR | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,980 | 88.0% |
| JUMP_BACKWARD | 680 | 12.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,128,400 | 99.9% |
| SET_FUNCTION_ATTRIBUTE | 1,280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 639,360 | 56.6% |
| CALL_PY_EXACT_ARGS | 450,240 | 39.9% |
| LOAD_FAST | 31,920 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 4,080 | 0.4% |
| STORE_DEREF | 1,920 | 0.2% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 50.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,420 | 62.0% |
| LOAD_FAST_LOAD_FAST | 2,640 | 30.2% |
| SWAP | 600 | 6.9% |
| LOAD_DEREF | 80 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 3,980 | 45.5% |
| LOAD_FAST | 1,300 | 14.9% |
| LOAD_FAST_LOAD_FAST | 780 | 8.9% |
| LOAD_CONST | 580 | 6.6% |
| STORE_ATTR_INSTANCE_VALUE | 560 | 6.4% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 176,080 | 79.4% |
| STORE_FAST | 42,080 | 19.0% |
| SET_FUNCTION_ATTRIBUTE | 1,920 | 0.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 700 | 0.3% |
| BUILD_LIST | 640 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 176,720 | 79.7% |
| LOAD_GLOBAL_BUILTIN | 42,000 | 18.9% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.5% |
| LOAD_FAST | 880 | 0.4% |
| STORE_FAST | 720 | 0.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 16,116,560 | 16.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,456,040 | 14.4% |
| STORE_FAST | 9,082,160 | 9.1% |
| LOAD_FAST | 8,117,400 | 8.1% |
| LOAD_CONST | 7,394,960 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,636,340 | 40.6% |
| LOAD_GLOBAL_BUILTIN | 17,622,620 | 17.6% |
| LOAD_FAST_LOAD_FAST | 9,435,120 | 9.4% |
| STORE_FAST | 9,082,160 | 9.1% |
| LOAD_CONST | 5,729,360 | 5.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 515,420 | 94.3% |
| FOR_ITER_TUPLE | 17,200 | 3.1% |
| YIELD_VALUE | 7,560 | 1.4% |
| FOR_ITER_LIST | 6,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 513,600 | 93.9% |
| TO_BOOL_STR | 15,920 | 2.9% |
| LOAD_ATTR_PROPERTY | 11,280 | 2.1% |
| LOAD_FAST | 2,120 | 0.4% |
| POP_JUMP_IF_NOT_NONE | 1,280 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 15,650,260 | 97.7% |
| UNPACK_EX | 145,680 | 0.9% |
| UNPACK_SEQUENCE | 121,800 | 0.8% |
| UNPACK_SEQUENCE_TUPLE | 95,980 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,799,980 | 61.2% |
| LOAD_GLOBAL_MODULE | 3,277,980 | 20.5% |
| LOAD_GLOBAL_BUILTIN | 2,408,760 | 15.0% |
| LOAD_FAST_LOAD_FAST | 429,920 | 2.7% |
| STORE_FAST | 96,080 | 0.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 29,274,020 | 66.9% |
| LOAD_FAST_AND_CLEAR | 4,682,480 | 10.7% |
| BUILD_MAP | 4,480,880 | 10.2% |
| ENTER_EXECUTOR | 4,433,040 | 10.1% |
| BUILD_TUPLE | 559,340 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 29,273,720 | 66.9% |
| STORE_FAST | 4,565,600 | 10.4% |
| BUILD_MAP | 4,480,880 | 10.2% |
| FOR_ITER | 4,440,000 | 10.1% |
| POP_TOP | 559,820 | 1.3% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 145,660 | 100.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 145,680 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 120,580 | 97.4% |
| FOR_ITER | 1,600 | 1.3% |
| RETURN_VALUE | 480 | 0.4% |
| UNPACK_SEQUENCE | 360 | 0.3% |
| STORE_FAST | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 121,800 | 98.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,240 | 1.0% |
| UNPACK_SEQUENCE | 360 | 0.3% |
| UNPACK_SEQUENCE_TUPLE | 200 | 0.2% |
| STORE_FAST | 180 | 0.1% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,946,560 | 41.0% |
| BUILD_TUPLE | 6,851,960 | 31.4% |
| ENTER_EXECUTOR | 2,390,400 | 10.9% |
| JUMP_FORWARD | 2,206,480 | 10.1% |
| LOAD_FAST | 746,780 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,946,560 | 41.0% |
| INTERPRETER_EXIT | 7,640,600 | 35.0% |
| UNPACK_SEQUENCE_TUPLE | 5,076,360 | 23.2% |
| UNPACK_EX | 145,660 | 0.7% |
| STORE_FAST | 23,760 | 0.1% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 7,820 | 53.3% |
| CACHE | 2,280 | 15.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,080 | 7.4% |
| MAKE_CELL | 840 | 5.7% |
| POP_TOP | 700 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,860 | 60.4% |
| LOAD_GLOBAL | 2,840 | 19.4% |
| LOAD_DEREF | 760 | 5.2% |
| POP_TOP | 580 | 4.0% |
| LOAD_CONST | 520 | 3.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,977,520 | 90.6% |
| LOAD_CONST | 3,002,680 | 9.1% |
| LOAD_FAST_LOAD_FAST | 93,960 | 0.3% |
| BINARY_OP | 720 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 29,274,020 | 88.5% |
| STORE_FAST | 2,243,380 | 6.8% |
| CALL_PY_EXACT_ARGS | 1,438,160 | 4.3% |
| LIST_APPEND | 94,000 | 0.3% |
| BINARY_OP_SUBTRACT_INT | 24,400 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,240 | 99.2% |
| BINARY_OP | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 10,160 | 98.4% |
| BINARY_OP | 160 | 1.6% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,285,440 | 91.8% |
| CALL_LEN | 1,426,800 | 8.0% |
| BINARY_OP_ADD_INT | 24,400 | 0.1% |
| LOAD_ATTR_SLOT | 10,200 | 0.1% |
| BINARY_OP | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 13,711,440 | 77.3% |
| CALL_PY_EXACT_ARGS | 1,457,520 | 8.2% |
| LOAD_CONST | 1,426,880 | 8.0% |
| LOAD_FAST | 1,116,560 | 6.3% |
| RETURN_VALUE | 24,440 | 0.1% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,118,320 | 48.9% |
| LOAD_ATTR_SLOT | 735,400 | 32.2% |
| LOAD_CONST | 256,200 | 11.2% |
| CALL_BUILTIN_O | 108,560 | 4.7% |
| LOAD_FAST | 27,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,624,920 | 71.1% |
| BUILD_TUPLE | 167,960 | 7.3% |
| LOAD_FAST_LOAD_FAST | 156,240 | 6.8% |
| RETURN_VALUE | 94,840 | 4.1% |
| PUSH_EXC_INFO | 75,960 | 3.3% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 20,520 | 99.7% |
| BINARY_SUBSCR | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,580 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,365,440 | 82.3% |
| LOAD_CONST | 936,160 | 17.7% |
| BINARY_SUBSCR_LIST_INT | 600 | 0.0% |
| BINARY_SUBSCR | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,322,320 | 81.5% |
| LOAD_FAST | 908,020 | 17.1% |
| PUSH_EXC_INFO | 34,080 | 0.6% |
| STORE_FAST | 11,860 | 0.2% |
| LOAD_FAST_LOAD_FAST | 10,260 | 0.2% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 13,711,440 | 48.1% |
| LOAD_ATTR_SLOT | 13,700,080 | 48.0% |
| LOAD_FAST | 1,116,000 | 3.9% |
| BINARY_SUBSCR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,411,680 | 96.1% |
| STORE_FAST | 1,116,080 | 3.9% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 42,240 | 50.0% |
| LOAD_FAST | 42,240 | 50.0% |
| BINARY_SUBSCR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 42,280 | 50.0% |
| LOAD_CONST | 42,280 | 50.0% |


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

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,175,380 | 49.7% |
| LOAD_FAST | 1,010,260 | 42.8% |
| LOAD_ATTR_SLOT | 72,000 | 3.0% |
| ENTER_EXECUTOR | 63,880 | 2.7% |
| CALL_PY_EXACT_ARGS | 29,720 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,085,900 | 88.3% |
| MAKE_CELL | 227,080 | 9.6% |
| CALL_PY_EXACT_ARGS | 30,740 | 1.3% |
| COPY_FREE_VARS | 18,220 | 0.8% |
| RESUME | 1,080 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 528,600 | 82.3% |
| CALL_BUILTIN_FAST | 44,160 | 6.9% |
| BINARY_SLICE | 42,000 | 6.5% |
| LOAD_FAST | 12,440 | 1.9% |
| LOAD_ATTR | 10,200 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 263,720 | 41.1% |
| JUMP_FORWARD | 239,320 | 37.3% |
| GET_ITER | 54,300 | 8.5% |
| RETURN_VALUE | 45,240 | 7.0% |
| CALL_LEN | 24,400 | 3.8% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,220,440 | 95.3% |
| LOAD_CONST | 97,880 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 51,600 | 1.5% |
| LOAD_DEREF | 5,080 | 0.2% |
| RETURN_GENERATOR | 3,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,669,240 | 49.4% |
| PUSH_NULL | 1,612,560 | 47.7% |
| STORE_FAST | 51,640 | 1.5% |
| CALL_BUILTIN_CLASS | 44,160 | 1.3% |
| LOAD_FAST_LOAD_FAST | 460 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 24,400 | 85.4% |
| LOAD_DEREF | 4,080 | 14.3% |
| CALL | 80 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,400 | 85.4% |
| GET_ITER | 4,120 | 14.4% |
| LOAD_GLOBAL | 40 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,963,200 | 48.6% |
| BUILD_TUPLE | 5,230,280 | 36.5% |
| LOAD_FAST | 2,116,320 | 14.8% |
| RETURN_VALUE | 16,960 | 0.1% |
| RETURN_GENERATOR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,193,580 | 85.1% |
| TO_BOOL_BOOL | 1,618,320 | 11.3% |
| STORE_FAST | 273,100 | 1.9% |
| STORE_SUBSCR_DICT | 114,640 | 0.8% |
| BINARY_SUBSCR_DICT | 108,560 | 0.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,637,480 | 36.4% |
| LOAD_GLOBAL_MODULE | 12,176,480 | 22.5% |
| LOAD_ATTR_SLOT | 9,037,700 | 16.7% |
| LOAD_ATTR_MODULE | 7,075,700 | 13.1% |
| BUILD_TUPLE | 4,366,020 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 51,403,160 | 95.2% |
| COPY | 2,056,940 | 3.8% |
| STORE_FAST | 496,160 | 0.9% |
| RETURN_VALUE | 61,960 | 0.1% |
| TO_BOOL | 4,020 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,690,080 | 95.2% |
| LOAD_DEREF | 37,840 | 2.1% |
| CALL_BUILTIN_CLASS | 24,400 | 1.4% |
| LOAD_ATTR_SLOT | 11,200 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 10,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 1,426,800 | 80.4% |
| STORE_FAST | 122,480 | 6.9% |
| LOAD_CONST | 67,460 | 3.8% |
| COMPARE_OP_INT | 59,480 | 3.4% |
| LOAD_FAST | 50,360 | 2.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,427,500 | 34.1% |
| ENTER_EXECUTOR | 1,407,280 | 33.7% |
| LOAD_FAST | 1,325,640 | 31.7% |
| RETURN_VALUE | 16,280 | 0.4% |
| BUILD_TUPLE | 4,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,943,720 | 46.5% |
| ENTER_EXECUTOR | 1,860,220 | 44.5% |
| LOAD_FAST | 289,420 | 6.9% |
| RETURN_CONST | 52,020 | 1.2% |
| JUMP_BACKWARD | 32,740 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 10,713,200 | 47.5% |
| LOAD_FAST | 5,424,040 | 24.0% |
| LOAD_CONST | 4,978,060 | 22.1% |
| LOAD_ATTR | 843,680 | 3.7% |
| LOAD_ATTR_METHOD_NO_DICT | 306,100 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,456,040 | 64.0% |
| RETURN_VALUE | 4,234,020 | 18.8% |
| CALL_PY_WITH_DEFAULTS | 3,180,440 | 14.1% |
| TO_BOOL_BOOL | 599,080 | 2.7% |
| LOAD_GLOBAL_MODULE | 44,480 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 67,440 | 68.7% |
| LOAD_CONST | 30,680 | 31.2% |
| CALL | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 67,480 | 68.7% |
| JUMP_FORWARD | 30,700 | 31.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 21,439,480 | 100.0% |
| LOAD_FAST | 2,920 | 0.0% |
| CALL | 1,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 13,735,960 | 64.1% |
| BUILD_TUPLE | 2,446,360 | 11.4% |
| TO_BOOL_BOOL | 1,447,200 | 6.7% |
| CALL_PY_EXACT_ARGS | 1,417,760 | 6.6% |
| RETURN_VALUE | 927,400 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 835,640 | 61.7% |
| RETURN_GENERATOR | 504,520 | 37.3% |
| LOAD_FAST | 12,900 | 1.0% |
| RETURN_VALUE | 440 | 0.0% |
| CALL | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 844,140 | 62.3% |
| RETURN_VALUE | 484,200 | 35.8% |
| STORE_FAST | 20,460 | 1.5% |
| LOAD_CONST | 5,100 | 0.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,531,240 | 38.6% |
| LOAD_ATTR | 10,882,060 | 14.7% |
| LOAD_ATTR_METHOD_NO_DICT | 7,105,660 | 9.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,316,640 | 5.8% |
| LOAD_CONST | 3,844,240 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 64,545,420 | 87.4% |
| RETURN_GENERATOR | 7,086,120 | 9.6% |
| MAKE_CELL | 1,380,560 | 1.9% |
| COPY_FREE_VARS | 774,720 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 29,720 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 13,206,240 | 58.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,180,440 | 14.1% |
| LOAD_ATTR_METHOD_NO_DICT | 2,690,780 | 11.9% |
| LOAD_FAST | 1,627,040 | 7.2% |
| LOAD_ATTR | 859,000 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,888,740 | 96.9% |
| MAKE_CELL | 658,640 | 2.9% |
| RETURN_GENERATOR | 43,660 | 0.2% |
| COPY_FREE_VARS | 1,900 | 0.0% |
| CALL_PY_EXACT_ARGS | 820 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,920 | 99.8% |
| CALL | 140 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,120 | 98.7% |
| STORE_FAST | 940 | 1.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,174,760 | 97.2% |
| LOAD_FAST | 48,920 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 42,000 | 1.3% |
| CALL | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 2,618,600 | 80.2% |
| RETURN_VALUE | 513,320 | 15.7% |
| STORE_FAST | 84,540 | 2.6% |
| JUMP_FORWARD | 48,940 | 1.5% |
| CALL_LEN | 480 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,572,680 | 100.0% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 2,631,280 | 47.2% |
| LOAD_GLOBAL_BUILTIN | 2,631,200 | 47.2% |
| STORE_FAST | 273,540 | 4.9% |
| LOAD_FAST_LOAD_FAST | 36,800 | 0.7% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 28,539,360 | 86.1% |
| LOAD_CONST | 4,460,560 | 13.5% |
| CALL_LEN | 59,480 | 0.2% |
| LOAD_FAST | 39,040 | 0.1% |
| LOAD_DEREF | 24,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,431,140 | 58.6% |
| LOAD_FAST | 13,711,520 | 41.4% |
| POP_JUMP_IF_TRUE | 12,040 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,479,240 | 60.4% |
| RETURN_VALUE | 478,400 | 19.5% |
| LOAD_CONST | 218,720 | 8.9% |
| LOAD_FAST | 186,360 | 7.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 82,440 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,971,740 | 80.4% |
| RETURN_VALUE | 457,400 | 18.7% |
| COPY | 20,540 | 0.8% |
| POP_JUMP_IF_TRUE | 1,400 | 0.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,107,200 | 85.8% |
| GET_ITER | 690,240 | 11.6% |
| EXTENDED_ARG | 149,840 | 2.5% |
| LOAD_FAST | 3,720 | 0.1% |
| FOR_ITER | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,253,620 | 88.3% |
| POP_TOP | 697,580 | 11.7% |
| RESUME | 220 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,323,100 | 58.9% |
| GET_ITER | 4,851,680 | 39.0% |
| SWAP | 187,080 | 1.5% |
| LOAD_FAST | 34,780 | 0.3% |
| JUMP_BACKWARD | 22,420 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,292,960 | 50.6% |
| STORE_FAST | 4,844,160 | 39.0% |
| LOAD_FAST | 1,112,400 | 9.0% |
| SWAP | 90,120 | 0.7% |
| RETURN_CONST | 52,260 | 0.4% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 720 | 60.0% |
| GET_ITER | 240 | 20.0% |
| ENTER_EXECUTOR | 160 | 13.3% |
| FOR_ITER | 80 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 880 | 73.3% |
| LOAD_FAST | 320 | 26.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 528,660 | 49.7% |
| LOAD_FAST | 474,440 | 44.6% |
| SWAP | 55,400 | 5.2% |
| JUMP_BACKWARD | 4,520 | 0.4% |
| GET_ITER | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 528,960 | 49.7% |
| RETURN_CONST | 474,560 | 44.6% |
| SWAP | 42,080 | 4.0% |
| STORE_FAST_LOAD_FAST | 17,200 | 1.6% |
| LOAD_FAST | 1,040 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,214,680 | 97.8% |
| LOAD_FAST_LOAD_FAST | 159,760 | 2.2% |
| LOAD_ATTR | 1,120 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 6,963,200 | 94.4% |
| IS_OP | 145,660 | 2.0% |
| RETURN_VALUE | 69,700 | 0.9% |
| LOAD_ATTR_METHOD_NO_DICT | 42,000 | 0.6% |
| LOAD_FAST | 41,740 | 0.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,528,480 | 46.5% |
| LOAD_ATTR_SLOT | 21,655,100 | 24.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 10,809,800 | 12.1% |
| RETURN_VALUE | 6,072,460 | 6.8% |
| LOAD_DEREF | 4,959,540 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,476,420 | 40.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 21,439,480 | 24.0% |
| LOAD_GLOBAL_MODULE | 13,918,960 | 15.6% |
| CALL_PY_EXACT_ARGS | 7,105,660 | 8.0% |
| LOAD_CONST | 5,623,520 | 6.3% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,456,580 | 80.7% |
| ENTER_EXECUTOR | 1,855,200 | 13.1% |
| LOAD_DEREF | 797,360 | 5.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 73,740 | 0.5% |
| CALL_FUNCTION_EX | 5,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,110,920 | 36.0% |
| CALL_PY_EXACT_ARGS | 3,772,560 | 26.6% |
| LOAD_FAST_LOAD_FAST | 3,591,400 | 25.3% |
| LOAD_CONST | 924,800 | 6.5% |
| CALL_PY_WITH_DEFAULTS | 665,280 | 4.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 10,266,820 | 99.9% |
| LOAD_ATTR | 6,300 | 0.1% |
| LOAD_FAST | 6,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 7,075,700 | 68.8% |
| PUSH_NULL | 1,113,040 | 10.8% |
| LOAD_GLOBAL_MODULE | 646,320 | 6.3% |
| LOAD_FAST | 428,880 | 4.2% |
| BUILD_TUPLE | 398,660 | 3.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,918,820 | 83.7% |
| LOAD_FAST_LOAD_FAST | 3,483,800 | 16.3% |
| LOAD_ATTR | 2,780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 10,809,800 | 50.5% |
| CALL_PY_EXACT_ARGS | 4,316,640 | 20.2% |
| CONTAINS_OP | 4,116,460 | 19.2% |
| STORE_FAST | 1,416,560 | 6.6% |
| LOAD_FAST | 599,960 | 2.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,693,040 | 81.7% |
| LOAD_FAST_LOAD_FAST | 971,900 | 9.1% |
| ENTER_EXECUTOR | 898,220 | 8.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 81,580 | 0.8% |
| LOAD_ATTR | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,670,040 | 25.1% |
| LOAD_GLOBAL_BUILTIN | 2,618,560 | 24.6% |
| CONTAINS_OP | 1,875,220 | 17.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,739,440 | 16.3% |
| FORMAT_SIMPLE | 1,612,580 | 15.1% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,698,140 | 98.0% |
| LOAD_FAST_LOAD_FAST | 83,240 | 0.9% |
| ENTER_EXECUTOR | 40,400 | 0.5% |
| BINARY_SUBSCR_DICT | 16,280 | 0.2% |
| STORE_FAST_LOAD_FAST | 11,280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,820,740 | 99.4% |
| RETURN_VALUE | 24,320 | 0.3% |
| STORE_FAST | 20,200 | 0.2% |
| COPY | 4,400 | 0.0% |
| SET_ADD | 1,580 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,240,360 | 80.3% |
| COPY | 29,273,720 | 9.7% |
| LOAD_ATTR_SLOT | 18,166,640 | 6.0% |
| LOAD_DEREF | 8,352,640 | 2.8% |
| LOAD_FAST_LOAD_FAST | 2,474,180 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,188,560 | 38.9% |
| COMPARE_OP_INT | 28,539,360 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 21,655,100 | 7.2% |
| LOAD_CONST | 20,632,240 | 6.8% |
| LOAD_ATTR_SLOT | 18,166,640 | 6.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,192,200 | 27.8% |
| RESUME_CHECK | 25,792,740 | 22.3% |
| STORE_FAST | 17,622,620 | 15.2% |
| POP_JUMP_IF_FALSE | 8,727,480 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 7,777,940 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,843,360 | 64.6% |
| CALL_ISINSTANCE | 19,637,480 | 17.0% |
| LOAD_GLOBAL_BUILTIN | 7,777,940 | 6.7% |
| LOAD_FAST_LOAD_FAST | 6,055,580 | 5.2% |
| BUILD_TUPLE | 3,854,300 | 3.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,517,800 | 38.4% |
| LOAD_ATTR_METHOD_NO_DICT | 13,918,960 | 19.4% |
| POP_JUMP_IF_FALSE | 7,216,560 | 10.1% |
| RESUME_CHECK | 4,682,220 | 6.5% |
| STORE_FAST_STORE_FAST | 3,277,980 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 23,251,160 | 32.5% |
| LOAD_FAST | 20,210,120 | 28.2% |
| CALL_ISINSTANCE | 12,176,480 | 17.0% |
| LOAD_ATTR_MODULE | 10,266,820 | 14.3% |
| LOAD_FAST_LOAD_FAST | 4,227,580 | 5.9% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 64,545,420 | 41.6% |
| CACHE | 26,851,500 | 17.3% |
| CALL_PY_WITH_DEFAULTS | 21,888,740 | 14.1% |
| SEND_GEN | 8,946,460 | 5.8% |
| LOAD_ATTR_PROPERTY | 8,820,740 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 90,740,220 | 58.5% |
| LOAD_GLOBAL_BUILTIN | 25,792,740 | 16.6% |
| POP_TOP | 12,893,500 | 8.3% |
| JUMP_BACKWARD_NO_INTERRUPT | 8,946,400 | 5.8% |
| LOAD_GLOBAL_MODULE | 4,682,220 | 3.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 8,946,440 | 71.4% |
| LOAD_CONST | 3,585,160 | 28.6% |
| SEND | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,946,460 | 71.4% |
| POP_TOP | 3,585,240 | 28.6% |
| RESUME | 100 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,320 | 83.8% |
| LOAD_FAST_LOAD_FAST | 12,840 | 15.5% |
| STORE_ATTR | 560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,500 | 38.1% |
| BUILD_LIST | 17,500 | 21.2% |
| LOAD_FAST | 16,040 | 19.4% |
| RETURN_CONST | 7,060 | 8.5% |
| LOAD_FAST_LOAD_FAST | 7,000 | 8.5% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,520,060 | 56.2% |
| SWAP | 29,273,720 | 32.0% |
| LOAD_FAST_LOAD_FAST | 10,476,140 | 11.4% |
| STORE_ATTR_SLOT | 152,660 | 0.2% |
| ENTER_EXECUTOR | 144,500 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,450,740 | 67.1% |
| RETURN_CONST | 18,351,200 | 20.0% |
| LOAD_FAST_LOAD_FAST | 5,182,240 | 5.7% |
| ENTER_EXECUTOR | 2,218,000 | 2.4% |
| LOAD_CONST | 1,939,680 | 2.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,061,540 | 82.0% |
| CALL_BUILTIN_O | 114,640 | 8.9% |
| RETURN_VALUE | 103,920 | 8.0% |
| LOAD_FAST_LOAD_FAST | 14,540 | 1.1% |
| STORE_SUBSCR | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,028,900 | 79.4% |
| LOAD_GLOBAL_MODULE | 108,560 | 8.4% |
| LOAD_FAST | 90,400 | 7.0% |
| POP_EXCEPT | 57,560 | 4.4% |
| JUMP_BACKWARD | 9,500 | 0.7% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 17,749,040 | 46.6% |
| LOAD_FAST | 11,840,700 | 31.1% |
| COPY | 7,762,500 | 20.4% |
| STORE_FAST_LOAD_FAST | 513,600 | 1.3% |
| TO_BOOL_ALWAYS_TRUE | 77,140 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 24,850,400 | 65.3% |
| POP_JUMP_IF_FALSE | 13,080,540 | 34.4% |
| TO_BOOL_ALWAYS_TRUE | 77,140 | 0.2% |
| TO_BOOL_NONE | 53,860 | 0.1% |
| UNARY_NOT | 14,400 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 51,403,160 | 57.1% |
| LOAD_ATTR_SLOT | 10,870,600 | 12.1% |
| LOAD_FAST | 10,705,860 | 11.9% |
| COPY | 5,224,540 | 5.8% |
| RETURN_VALUE | 5,203,940 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 63,001,380 | 70.0% |
| POP_JUMP_IF_TRUE | 21,461,820 | 23.8% |
| UNARY_NOT | 4,084,160 | 4.5% |
| EXTENDED_ARG | 1,446,080 | 1.6% |
| TO_BOOL_NONE | 12,040 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 9,024,320 | 99.8% |
| LOAD_FAST | 18,400 | 0.2% |
| TO_BOOL | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,031,580 | 99.9% |
| EXTENDED_ARG | 11,280 | 0.1% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 57,680 | 48.6% |
| LOAD_FAST | 47,620 | 40.2% |
| BINARY_SLICE | 11,200 | 9.4% |
| RETURN_VALUE | 1,200 | 1.0% |
| TO_BOOL_NONE | 500 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 90,560 | 76.4% |
| POP_JUMP_IF_FALSE | 27,520 | 23.2% |
| TO_BOOL_NONE | 500 | 0.4% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,140,280 | 51.7% |
| LOAD_FAST | 10,703,500 | 39.2% |
| COPY | 1,899,200 | 6.9% |
| LOAD_ATTR_SLOT | 294,240 | 1.1% |
| ENTER_EXECUTOR | 73,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20,772,040 | 76.0% |
| POP_JUMP_IF_TRUE | 6,028,140 | 22.0% |
| EXTENDED_ARG | 448,340 | 1.6% |
| TO_BOOL_ALWAYS_TRUE | 53,820 | 0.2% |
| TO_BOOL_STR | 20,020 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 9,013,120 | 54.6% |
| LOAD_FAST | 7,150,120 | 43.3% |
| COPY | 165,680 | 1.0% |
| RETURN_VALUE | 118,120 | 0.7% |
| TO_BOOL_NONE | 20,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 10,804,940 | 65.5% |
| POP_JUMP_IF_FALSE | 5,669,800 | 34.4% |
| TO_BOOL_NONE | 20,040 | 0.1% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,076,360 | 99.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 44,600 | 0.9% |
| UNPACK_SEQUENCE | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,025,180 | 98.1% |
| STORE_FAST_STORE_FAST | 95,980 | 1.9% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 13,335,260 | 85.0% |
| RETURN_VALUE | 1,970,540 | 12.6% |
| LOAD_FAST | 239,280 | 1.5% |
| BUILD_TUPLE | 98,840 | 0.6% |
| STORE_FAST | 43,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 15,650,260 | 99.7% |
| STORE_FAST | 44,040 | 0.3% |
| STORE_DEREF | 700 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 10,160 | 99.6% |
| BINARY_OP | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,200 | 100.0% |


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
|     deferred | 33,900 | 0.1% |
|          hit | 52,433,520 | 99.9% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,520 | 66.1% |
| Failure | 780 | 33.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 720 | 92.3% |
| add different types | 40 | 5.1% |
| subtract other | 20 | 2.6% |


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
|     deferred | 19,920 | 0.1% |
|          hit | 36,187,240 | 99.8% |
|         miss | 34,680 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,160 | 76.6% |
| Failure | 660 | 23.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 440 | 66.7% |
| other | 220 | 33.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,333,520 | 3.0% |
|          hit | 230,331,100 | 95.5% |
|         miss | 3,528,820 | 1.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 103,000 | 88.9% |
| Failure | 12,860 | 11.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 4,180 | 32.5% |
| bound method | 2,540 | 19.8% |
| class no vectorcall | 1,740 | 13.5% |
| no dict | 980 | 7.6% |
| cfunc varargs keywords | 980 | 7.6% |
| cfunc noargs | 720 | 5.6% |
| meth descr varargs | 680 | 5.3% |
| init not python | 520 | 4.0% |
| meth descr varargs keywords | 260 | 2.0% |
| meth descr method fastcall keywords | 120 | 0.9% |
| wrong number arguments | 80 | 0.6% |
| init not simple | 60 | 0.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 23,794,600 | 40.0% |
|          hit | 35,605,780 | 59.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,040 | 11.2% |
| Failure | 16,100 | 88.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 10,960 | 68.1% |
| different types | 3,320 | 20.6% |
| other | 800 | 5.0% |
| set | 440 | 2.7% |
| string | 340 | 2.1% |
| big int | 180 | 1.1% |
| bool | 60 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 16,354,260 | 45.7% |
|          hit | 19,445,700 | 54.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,580 | 16.6% |
| Failure | 12,940 | 83.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 7,220 | 55.8% |
| dict keys | 1,200 | 9.3% |
| dict values | 1,140 | 8.8% |
| enumerate | 1,000 | 7.7% |
| ascii string | 1,000 | 7.7% |
| itertools | 620 | 4.8% |
| other | 340 | 2.6% |
| set | 300 | 2.3% |
| reversed list | 120 | 0.9% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,398,360 | 5.4% |
|        deopt | 1,237,760 | 0.3% |
|          hit | 443,099,500 | 90.6% |
|         miss | 20,433,660 | 4.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 434,780 | 88.1% |
| Failure | 58,680 | 11.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 48,960 | 83.4% |
| method | 8,100 | 13.8% |
| mutable class | 1,240 | 2.1% |
| overridden | 140 | 0.2% |
| class method obj | 140 | 0.2% |
| builtin class method | 100 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 28,420 | 0.0% |
|          hit | 187,431,220 | 100.0% |
|         miss | 16,960 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 29,060 | 100.0% |
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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 12,531,800 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,475,739,525,896,763,980,820 | 1,609,533,617,374,649.0% |
|          hit | 83,576,400 | 91.2% |
|         miss | 8,102,260 | 8.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 157,200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 540 | 0.0% |
|          hit | 1,295,180 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,948,387,285,680 | 395,487,772,312,120.5% |
|          hit | 167,756,280 | 89.9% |
|         miss | 13,320,840 | 7.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 269,380 | 98.3% |
| Failure | 4,540 | 1.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 2,060 | 45.4% |
| other | 1,820 | 40.1% |
| dict | 480 | 10.6% |
| tuple | 100 | 2.2% |
| set | 80 | 1.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 122,000 | 0.6% |
|          hit | 20,816,160 | 99.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,440 | 80.0% |
| Failure | 360 | 20.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 360 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,558,601,920 | 46.1% |
| Not specialized | 334,550,540 | 9.9% |
| Specialized hits | 1,441,646,820 | 42.6% |
| Specialized misses | 45,440,260 | 1.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 1,475,739,525,896,763,980,820 | 66.7% |
| TO_BOOL | 737,869,762,948,387,285,680 | 33.3% |
| LOAD_ATTR | 26,398,360 | 0.0% |
| COMPARE_OP | 23,794,600 | 0.0% |
| FOR_ITER | 16,354,260 | 0.0% |
| CALL | 7,333,520 | 0.0% |
| UNPACK_SEQUENCE | 122,000 | 0.0% |
| BINARY_OP | 33,900 | 0.0% |
| LOAD_GLOBAL | 28,420 | 0.0% |
| BINARY_SUBSCR | 19,920 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 12,071,680 | 26.6% |
| STORE_ATTR_SLOT | 8,102,260 | 17.8% |
| TO_BOOL_ALWAYS_TRUE | 6,961,420 | 15.3% |
| TO_BOOL_NONE | 4,618,240 | 10.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 4,330,680 | 9.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,940,740 | 8.7% |
| CALL_PY_EXACT_ARGS | 1,847,160 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,633,820 | 3.6% |
| TO_BOOL_STR | 1,064,120 | 2.3% |
| TO_BOOL_BOOL | 649,400 | 1.4% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 31,186,120 | 19.1% |
| Calls to Python functions inlined | 132,359,540 | 80.9% |
| Calls via PyEval_EvalFrame (total) | 31,186,120 | 19.1% |
| Calls via PyEval_EvalFrame (vector) | 19,238,100 | 11.8% |
| Calls via PyEval_EvalFrame (generator) | 11,948,020 | 7.3% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 19,238,100 | 11.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,644,700 | 2.2% |
| Calls via PyEval_EvalFrame (function ex) | 89,920 | 0.1% |
| Calls via PyEval_EvalFrame (api) | 12,248,380 | 7.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 110,160 | 0.1% |
| Frames pushed | 112,731,760 | 68.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 75,849,400 | 31.4% |
| Frees to freelist | 76,108,860 |  |
| Allocations | 165,813,800 | 68.6% |
| Allocations to 512 bytes | 165,698,420 | 68.6% |
| Allocations to 4 kbytes | 115,300 | 0.0% |
| Allocations over 4 kbytes | 80 | 0.0% |
| Frees | 166,231,036 |  |
| New values | 1,760,740 |  |
| Interpreter increfs | 1,748,314,980 | 80.1% |
| Interpreter decrefs | 1,936,675,160 | 80.5% |
| Increfs | 435,477,232 | 19.9% |
| Decrefs | 470,621,201 | 19.5% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 78,424,273 |  |
| Method cache misses | 2,881,767 |  |
| Method cache collisions | 3,082,412 |  |
| Method cache dunder hits | 117,849,280 |  |
| Method cache dunder misses | 218,080 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 4,920 | 1,311,800 | 25,315,000 |
| 1 | 460 | 1,194,420 | 11,901,280 |
| 2 | 40 | 90,480 | 8,570,880 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 9,100 |  |
| Traces created | 4,120 | 45.3% |
| Trace stack overflow | 60 | 0.7% |
| Trace stack underflow | 80 | 0.9% |
| Trace too long | 100 | 1.1% |
| Trace too short | 4,980 | 54.7% |
| Inner loop found | 80 | 0.9% |
| Recursive call | 160 | 1.8% |
| Traces executed | 51,241,380 |  |
| Uops executed | 912,635,860 | 17.81 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 320 | 7.8% |
| <= 32 | 960 | 23.3% |
| <= 64 | 1,700 | 41.3% |
| <= 128 | 740 | 18.0% |
| <= 256 | 400 | 9.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 360 | 8.7% |
| <= 16 | 880 | 21.4% |
| <= 32 | 1,540 | 37.4% |
| <= 64 | 860 | 20.9% |
| <= 128 | 380 | 9.2% |
| <= 256 | 100 | 2.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 21,805,920 | 42.6% |
| <= 4 | 160 | 0.0% |
| <= 8 | 3,799,980 | 7.4% |
| <= 16 | 10,454,300 | 20.4% |
| <= 32 | 8,243,960 | 16.1% |
| <= 64 | 3,699,640 | 7.2% |
| <= 128 | 2,998,940 | 5.9% |
| <= 256 | 222,800 | 0.4% |
| <= 512 | 7,480 | 0.0% |
| <= 1,024 | 4,520 | 0.0% |
| <= 2,048 | 1,200 | 0.0% |
| <= 4,096 | 1,440 | 0.0% |
| <= 8,192 | 800 | 0.0% |
| <= 16,384 | 240 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 129,330,800 | 14.2% | 14.2% |  |
| LOAD_FAST | 121,836,500 | 13.3% | 27.5% |  |
| _CHECK_VALIDITY | 110,729,140 | 12.1% | 39.7% |  |
| _GUARD_TYPE_VERSION | 62,665,720 | 6.9% | 46.5% | 6.2% |
| STORE_FAST | 44,850,680 | 4.9% | 51.4% |  |
| _GUARD_GLOBALS_VERSION | 39,904,800 | 4.4% | 55.8% | 4.1% |
| _FOR_ITER_TIER_TWO | 30,278,080 | 3.3% | 59.1% | 53.1% |
| _GUARD_BUILTINS_VERSION | 24,457,560 | 2.7% | 61.8% |  |
| _LOAD_GLOBAL_BUILTINS | 24,457,560 | 2.7% | 64.5% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 23,315,640 | 2.6% | 67.0% |  |
| _LOAD_ATTR_SLOT | 20,526,400 | 2.2% | 69.3% |  |
| _EXIT_TRACE | 17,950,480 | 2.0% | 71.3% |  |
| _GUARD_IS_FALSE_POP | 17,543,800 | 1.9% | 73.2% | 5.0% |
| _GUARD_IS_TRUE_POP | 16,553,060 | 1.8% | 75.0% | 12.0% |
| TO_BOOL_BOOL | 15,550,240 | 1.7% | 76.7% |  |
| _LOAD_GLOBAL_MODULE | 13,828,680 | 1.5% | 78.2% |  |
| CALL_ISINSTANCE | 12,791,400 | 1.4% | 79.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,242,000 | 1.3% | 81.0% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 10,346,760 | 1.1% | 82.1% | 70.8% |
| _ITER_CHECK_LIST | 10,346,760 | 1.1% | 83.2% |  |
| _STORE_ATTR_SLOT | 9,153,560 | 1.0% | 84.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 8,938,320 | 1.0% | 85.2% | 3.4% |
| _CHECK_PEP_523 | 8,938,320 | 1.0% | 86.2% |  |
| _CHECK_STACK_SPACE | 8,636,380 | 0.9% | 87.1% |  |
| _INIT_CALL_PY_EXACT_ARGS | 8,636,380 | 0.9% | 88.1% |  |
| _PUSH_FRAME | 8,636,380 | 0.9% | 89.0% |  |
| _SAVE_RETURN_OFFSET | 8,636,380 | 0.9% | 90.0% |  |
| RESUME_CHECK | 8,501,180 | 0.9% | 90.9% |  |
| TO_BOOL_STR | 6,990,060 | 0.8% | 91.7% |  |
| _POP_FRAME | 6,719,580 | 0.7% | 92.4% |  |
| CONTAINS_OP | 6,457,420 | 0.7% | 93.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,207,580 | 0.6% | 93.7% | 0.0% |
| BUILD_TUPLE | 5,176,000 | 0.6% | 94.2% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,047,500 | 0.6% | 94.8% |  |
| LOAD_CONST | 4,059,320 | 0.4% | 95.2% |  |
| GET_ITER | 3,831,880 | 0.4% | 95.7% |  |
| _JUMP_TO_TOP | 3,308,460 | 0.4% | 96.0% |  |
| BUILD_LIST | 3,108,040 | 0.3% | 96.4% |  |
| _ITER_NEXT_LIST | 3,022,220 | 0.3% | 96.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,246,080 | 0.2% | 96.9% |  |
| _GUARD_IS_NOT_NONE_POP | 2,181,020 | 0.2% | 97.2% | 2.5% |
| MAP_ADD | 1,932,240 | 0.2% | 97.4% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 1,710,320 | 0.2% | 97.6% | 30.9% |
| _ITER_CHECK_TUPLE | 1,710,320 | 0.2% | 97.8% |  |
| _CHECK_ATTR_MODULE | 1,648,580 | 0.2% | 98.0% |  |
| _LOAD_ATTR_MODULE | 1,648,580 | 0.2% | 98.1% |  |
| _COMPARE_OP | 1,457,200 | 0.2% | 98.3% |  |
| _LOAD_ATTR | 1,415,020 | 0.2% | 98.4% |  |
| _BINARY_SUBSCR | 1,404,000 | 0.2% | 98.6% |  |
| COMPARE_OP_STR | 1,298,460 | 0.1% | 98.7% |  |
| COMPARE_OP_INT | 1,272,200 | 0.1% | 98.9% |  |
| _ITER_NEXT_TUPLE | 1,181,660 | 0.1% | 99.0% |  |
| POP_TOP | 1,030,360 | 0.1% | 99.1% |  |
| UNPACK_SEQUENCE_TUPLE | 1,007,920 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 856,820 | 0.1% | 99.3% | 9.6% |
| SWAP | 856,820 | 0.1% | 99.4% |  |
| COPY | 840,140 | 0.1% | 99.5% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 701,620 | 0.1% | 99.6% |  |
| _GUARD_KEYS_VERSION | 701,620 | 0.1% | 99.7% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 619,180 | 0.1% | 99.7% |  |
| TO_BOOL_ALWAYS_TRUE | 514,260 | 0.1% | 99.8% | 12.3% |
| _GUARD_IS_NONE_POP | 499,520 | 0.1% | 99.8% | 90.3% |
| PUSH_NULL | 460,820 | 0.1% | 99.9% |  |
| LOAD_DEREF | 294,620 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 173,380 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 85,760 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 82,440 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 62,320 | 0.0% | 100.0% |  |
| LIST_APPEND | 60,300 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40,300 | 0.0% | 100.0% |  |
| BUILD_MAP | 19,920 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 16,200 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 16,200 | 0.0% | 100.0% |  |
| DICT_MERGE | 16,100 | 0.0% | 100.0% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 9,600 | 0.0% | 100.0% | 1.7% |
| _ITER_CHECK_RANGE | 9,600 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 9,440 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 7,880 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 4,840 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 4,840 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 4,020 | 0.0% | 100.0% |  |
| IS_OP | 3,720 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 3,320 | 0.0% | 100.0% |  |
| SET_ADD | 3,300 | 0.0% | 100.0% |  |
| _TO_BOOL | 680 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 480 | 0.0% | 100.0% |  |
| _BINARY_OP | 340 | 0.0% | 100.0% |  |
| BUILD_SET | 280 | 0.0% | 100.0% |  |
| CALL_LEN | 120 | 0.0% | 100.0% |  |
| MAKE_CELL | 80 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 4,980 |
| LOAD_ATTR_PROPERTY | 580 |
| CALL_PY_WITH_DEFAULTS | 560 |
| YIELD_VALUE | 260 |
| CALL | 200 |
| CALL_LIST_APPEND | 180 |
| CALL_KW | 100 |
| BINARY_OP_INPLACE_ADD_UNICODE | 60 |
| CALL_FUNCTION_EX | 40 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 80 |


</details>

---
Stats gathered on: 2023-11-18