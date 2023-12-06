
# Pystats results

- benchmark: sqlglot
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 638,012,480 | 20.8% | 20.8% |  |
| LOAD_ATTR_SLOT | 237,112,500 | 7.7% | 28.5% | 5.0% |
| POP_JUMP_IF_FALSE | 159,125,000 | 5.2% | 33.7% |  |
| RESUME_CHECK | 138,248,480 | 4.5% | 38.2% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 131,747,580 | 4.3% | 42.5% | 0.0% |
| STORE_FAST | 95,560,120 | 3.1% | 45.7% |  |
| TO_BOOL_BOOL | 94,461,020 | 3.1% | 48.7% | 0.5% |
| LOAD_ATTR_METHOD_NO_DICT | 76,779,540 | 2.5% | 51.2% | 0.0% |
| RETURN_VALUE | 76,321,140 | 2.5% | 53.7% |  |
| LOAD_GLOBAL_MODULE | 75,759,700 | 2.5% | 56.2% |  |
| STORE_ATTR_SLOT | 70,199,700 | 2.3% | 58.5% | 9.7% |
| CALL_PY_EXACT_ARGS | 69,299,960 | 2.3% | 60.8% | 2.2% |
| CALL_ISINSTANCE | 63,651,580 | 2.1% | 62.8% |  |
| POP_JUMP_IF_TRUE | 57,484,740 | 1.9% | 64.7% |  |
| LOAD_CONST | 57,351,860 | 1.9% | 66.6% |  |
| POP_TOP | 53,218,420 | 1.7% | 68.3% |  |
| LOAD_FAST_LOAD_FAST | 45,678,720 | 1.5% | 69.8% |  |
| RETURN_CONST | 42,723,780 | 1.4% | 71.2% |  |
| FOR_ITER | 42,170,040 | 1.4% | 72.6% |  |
| SWAP | 36,018,720 | 1.2% | 73.7% |  |
| COPY | 35,832,240 | 1.2% | 74.9% |  |
| JUMP_BACKWARD | 31,458,020 | 1.0% | 75.9% |  |
| TO_BOOL_ALWAYS_TRUE | 30,398,780 | 1.0% | 76.9% | 21.1% |
| INTERPRETER_EXIT | 27,297,140 | 0.9% | 77.8% |  |
| STORE_FAST_STORE_FAST | 26,040,460 | 0.8% | 78.7% |  |
| COMPARE_OP_INT | 25,748,160 | 0.8% | 79.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 25,725,520 | 0.8% | 80.3% |  |
| BINARY_OP_ADD_INT | 25,010,020 | 0.8% | 81.2% |  |
| BUILD_TUPLE | 23,959,020 | 0.8% | 81.9% |  |
| GET_ITER | 23,443,980 | 0.8% | 82.7% |  |
| TO_BOOL_NONE | 22,264,900 | 0.7% | 83.4% | 16.7% |
| BINARY_SUBSCR_STR_INT | 21,565,560 | 0.7% | 84.1% |  |
| ENTER_EXECUTOR | 21,355,080 | 0.7% | 84.8% |  |
| LOAD_ATTR | 20,458,820 | 0.7% | 85.5% |  |
| YIELD_VALUE | 20,141,460 | 0.7% | 86.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 19,703,440 | 0.6% | 86.8% | 0.0% |
| COMPARE_OP | 19,321,540 | 0.6% | 87.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,179,260 | 0.6% | 88.1% |  |
| CALL_PY_WITH_DEFAULTS | 17,496,400 | 0.6% | 88.6% | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 17,488,360 | 0.6% | 89.2% |  |
| LOAD_DEREF | 13,805,500 | 0.5% | 89.7% |  |
| BINARY_OP_SUBTRACT_INT | 13,419,900 | 0.4% | 90.1% |  |
| TO_BOOL_STR | 13,298,460 | 0.4% | 90.5% | 6.9% |
| LOAD_ATTR_MODULE | 12,571,420 | 0.4% | 90.9% |  |
| CONTAINS_OP | 12,512,200 | 0.4% | 91.3% |  |
| LOAD_FAST_AND_CLEAR | 12,491,040 | 0.4% | 91.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,306,500 | 0.4% | 92.1% | 30.7% |
| CALL_BUILTIN_O | 12,257,080 | 0.4% | 92.5% |  |
| SEND_GEN | 11,203,380 | 0.4% | 92.9% |  |
| EXTENDED_ARG | 10,639,780 | 0.3% | 93.3% |  |
| JUMP_FORWARD | 10,569,780 | 0.3% | 93.6% |  |
| PUSH_NULL | 10,244,800 | 0.3% | 93.9% |  |
| BUILD_LIST | 10,033,780 | 0.3% | 94.3% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 9,418,680 | 0.3% | 94.6% | 40.6% |
| JUMP_BACKWARD_NO_INTERRUPT | 8,128,020 | 0.3% | 94.8% |  |
| LOAD_ATTR_PROPERTY | 7,951,120 | 0.3% | 95.1% | 0.7% |
| FOR_ITER_LIST | 7,817,560 | 0.3% | 95.4% |  |
| RETURN_GENERATOR | 7,648,920 | 0.2% | 95.6% |  |
| POP_JUMP_IF_NOT_NONE | 7,567,140 | 0.2% | 95.9% |  |
| TO_BOOL_INT | 6,850,080 | 0.2% | 96.1% |  |
| MAP_ADD | 6,402,780 | 0.2% | 96.3% |  |
| CALL | 6,084,440 | 0.2% | 96.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 5,833,920 | 0.2% | 96.7% | 0.6% |
| FOR_ITER_GEN | 5,409,180 | 0.2% | 96.8% |  |
| BUILD_MAP | 5,221,480 | 0.2% | 97.0% |  |
| TO_BOOL | 4,995,520 | 0.2% | 97.2% |  |
| CALL_TYPE_1 | 4,830,480 | 0.2% | 97.3% |  |
| NOP | 4,749,960 | 0.2% | 97.5% |  |
| COPY_FREE_VARS | 4,645,520 | 0.2% | 97.6% |  |
| UNPACK_SEQUENCE_TUPLE | 4,567,200 | 0.1% | 97.8% |  |
| MAKE_FUNCTION | 4,500,600 | 0.1% | 97.9% |  |
| BINARY_SUBSCR_LIST_INT | 4,470,820 | 0.1% | 98.1% | 0.6% |
| FORMAT_SIMPLE | 4,025,520 | 0.1% | 98.2% |  |
| CALL_LIST_APPEND | 3,740,880 | 0.1% | 98.3% |  |
| UNARY_NOT | 3,437,940 | 0.1% | 98.5% |  |
| CALL_TUPLE_1 | 3,079,260 | 0.1% | 98.6% |  |
| END_SEND | 3,075,360 | 0.1% | 98.7% |  |
| GET_YIELD_FROM_ITER | 3,075,360 | 0.1% | 98.8% |  |
| IS_OP | 3,042,240 | 0.1% | 98.9% |  |
| MAKE_CELL | 3,004,440 | 0.1% | 99.0% |  |
| CALL_BUILTIN_FAST | 2,990,360 | 0.1% | 99.0% | 0.2% |
| BINARY_SLICE | 2,794,920 | 0.1% | 99.1% |  |
| BUILD_STRING | 2,386,920 | 0.1% | 99.2% |  |
| CALL_KW | 2,210,040 | 0.1% | 99.3% |  |
| COMPARE_OP_STR | 1,992,780 | 0.1% | 99.4% |  |
| BINARY_SUBSCR_DICT | 1,934,820 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,916,980 | 0.1% | 99.5% | 69.0% |
| STORE_SUBSCR_DICT | 1,552,560 | 0.1% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,503,900 | 0.0% | 99.6% |  |
| POP_JUMP_IF_NONE | 1,447,680 | 0.0% | 99.6% |  |
| CALL_LEN | 1,396,920 | 0.0% | 99.7% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,202,700 | 0.0% | 99.7% |  |
| SET_FUNCTION_ATTRIBUTE | 1,174,260 | 0.0% | 99.7% |  |
| BINARY_SUBSCR | 1,081,300 | 0.0% | 99.8% |  |
| CALL_FUNCTION_EX | 985,080 | 0.0% | 99.8% |  |
| DICT_MERGE | 948,840 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 900,440 | 0.0% | 99.9% |  |
| END_FOR | 628,500 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 546,960 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 455,480 | 0.0% | 99.9% |  |
| LIST_APPEND | 299,400 | 0.0% | 99.9% |  |
| UNPACK_EX | 218,520 | 0.0% | 99.9% |  |
| STORE_DEREF | 178,200 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 162,360 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 124,920 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 111,300 | 0.0% | 100.0% |  |
| POP_EXCEPT | 111,300 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 111,300 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 102,640 | 0.0% | 100.0% | 20.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 101,280 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 96,080 | 0.0% | 100.0% |  |
| LIST_EXTEND | 94,320 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 86,640 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 56,220 | 0.0% | 100.0% |  |
| CALL_STR_1 | 56,040 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 46,800 | 0.0% | 100.0% |  |
| BUILD_SET | 42,360 | 0.0% | 100.0% |  |
| BINARY_OP | 30,880 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 24,180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 15,600 | 0.0% | 100.0% |  |
| SET_ADD | 13,440 | 0.0% | 100.0% |  |
| DICT_UPDATE | 13,140 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 7,860 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 7,800 | 0.0% | 100.0% | 2.3% |
| IMPORT_NAME | 5,280 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 580 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 420 | 0.0% | 100.0% |  |
| STORE_ATTR | 280 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| SET_UPDATE | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 192,162,020 | 6.3% | 6.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 100,555,580 | 3.3% | 9.5% |
| LOAD_ATTR_SLOT LOAD_FAST | 89,843,880 | 2.9% | 12.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 80,446,280 | 2.6% | 15.1% |
| RESUME_CHECK LOAD_FAST | 77,504,480 | 2.5% | 17.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 67,893,700 | 2.2% | 19.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 60,450,140 | 2.0% | 21.8% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,710,960 | 1.9% | 23.8% |
| STORE_ATTR_SLOT LOAD_FAST | 46,512,180 | 1.5% | 25.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 41,121,900 | 1.3% | 26.6% |
| LOAD_FAST STORE_ATTR_SLOT | 39,241,700 | 1.3% | 27.9% |
| STORE_FAST LOAD_FAST | 37,572,900 | 1.2% | 29.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 34,366,740 | 1.1% | 30.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 31,609,980 | 1.0% | 31.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 31,108,720 | 1.0% | 32.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,727,260 | 1.0% | 33.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 29,615,600 | 1.0% | 34.3% |
| LOAD_FAST COPY | 29,210,040 | 1.0% | 35.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 26,935,260 | 0.9% | 36.1% |
| JUMP_BACKWARD FOR_ITER | 26,259,900 | 0.9% | 36.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 25,634,980 | 0.8% | 37.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 24,598,860 | 0.8% | 38.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 24,017,340 | 0.8% | 39.4% |
| CACHE RESUME_CHECK | 23,315,240 | 0.8% | 40.1% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 23,153,580 | 0.8% | 40.9% |
| LOAD_FAST BINARY_OP_ADD_INT | 22,664,100 | 0.7% | 41.6% |
| COPY LOAD_ATTR_SLOT | 22,131,480 | 0.7% | 42.3% |
| SWAP STORE_ATTR_SLOT | 22,131,480 | 0.7% | 43.1% |
| BINARY_OP_ADD_INT SWAP | 22,131,480 | 0.7% | 43.8% |
| LOAD_ATTR_SLOT COMPARE_OP_INT | 21,575,580 | 0.7% | 44.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 21,122,620 | 0.7% | 45.2% |
| BINARY_SUBSCR_STR_INT LOAD_FAST | 20,721,660 | 0.7% | 45.9% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_NO_DICT | 20,263,620 | 0.7% | 46.5% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 20,015,580 | 0.7% | 47.2% |
| LOAD_FAST RETURN_VALUE | 19,211,820 | 0.6% | 47.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 19,174,820 | 0.6% | 48.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 18,876,900 | 0.6% | 49.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 18,716,960 | 0.6% | 49.7% |
| COMPARE_OP POP_JUMP_IF_FALSE | 17,481,420 | 0.6% | 50.2% |
| RETURN_CONST POP_TOP | 17,179,980 | 0.6% | 50.8% |
| RETURN_VALUE STORE_FAST | 16,930,060 | 0.6% | 51.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 16,886,360 | 0.6% | 51.9% |
| LOAD_ATTR_SLOT LOAD_CONST | 16,861,500 | 0.5% | 52.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 16,576,620 | 0.5% | 53.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 16,506,040 | 0.5% | 53.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 15,367,200 | 0.5% | 54.0% |
| POP_TOP LOAD_FAST | 15,204,660 | 0.5% | 54.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 14,825,760 | 0.5% | 55.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 14,354,300 | 0.5% | 55.5% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 14,117,260 | 0.5% | 55.9% |
| STORE_ATTR_SLOT RETURN_CONST | 13,920,120 | 0.5% | 56.4% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 13,789,320 | 0.4% | 56.8% |
| RETURN_VALUE INTERPRETER_EXIT | 13,635,320 | 0.4% | 57.3% |
| LOAD_ATTR_SLOT TO_BOOL_ALWAYS_TRUE | 13,422,560 | 0.4% | 57.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 12,639,780 | 0.4% | 58.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS GET_ITER | 12,582,360 | 0.4% | 58.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 12,566,000 | 0.4% | 58.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 12,312,720 | 0.4% | 59.3% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 12,246,980 | 0.4% | 59.7% |
| RESUME_CHECK POP_TOP | 12,013,440 | 0.4% | 60.1% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 11,834,920 | 0.4% | 60.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 11,516,800 | 0.4% | 60.9% |
| LOAD_FAST BUILD_TUPLE | 11,391,720 | 0.4% | 61.3% |
| RETURN_CONST TO_BOOL_NONE | 10,700,040 | 0.3% | 61.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 10,565,820 | 0.3% | 62.0% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_STR_INT | 10,365,480 | 0.3% | 62.3% |
| COMPARE_OP_INT LOAD_FAST | 10,365,480 | 0.3% | 62.6% |
| RETURN_VALUE RETURN_VALUE | 10,357,560 | 0.3% | 63.0% |
| LOAD_ATTR_SLOT BINARY_SUBSCR_STR_INT | 10,356,180 | 0.3% | 63.3% |
| CALL_BUILTIN_O RETURN_VALUE | 10,327,740 | 0.3% | 63.7% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 10,241,500 | 0.3% | 64.0% |
| LOAD_FAST TO_BOOL_BOOL | 10,070,300 | 0.3% | 64.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 9,959,140 | 0.3% | 64.6% |
| LOAD_FAST TO_BOOL_NONE | 9,625,140 | 0.3% | 65.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 9,492,300 | 0.3% | 65.3% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 9,470,240 | 0.3% | 65.6% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 9,419,940 | 0.3% | 65.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,234,420 | 0.3% | 66.2% |
| LOAD_ATTR_MODULE CALL_ISINSTANCE | 9,203,940 | 0.3% | 66.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 8,928,780 | 0.3% | 66.8% |
| LOAD_FAST COMPARE_OP | 8,675,040 | 0.3% | 67.1% |
| LOAD_FAST GET_ITER | 8,617,440 | 0.3% | 67.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 8,555,100 | 0.3% | 67.6% |
| LOAD_ATTR COMPARE_OP | 8,444,700 | 0.3% | 67.9% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 8,395,200 | 0.3% | 68.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT LOAD_ATTR_METHOD_NO_DICT | 8,386,500 | 0.3% | 68.4% |
| LOAD_FAST LOAD_CONST | 8,315,000 | 0.3% | 68.7% |
| LOAD_ATTR_SLOT CALL_METHOD_DESCRIPTOR_FAST | 8,303,280 | 0.3% | 69.0% |
| STORE_FAST STORE_FAST | 8,284,260 | 0.3% | 69.2% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 8,245,440 | 0.3% | 69.5% |
| TO_BOOL_STR POP_JUMP_IF_TRUE | 8,229,800 | 0.3% | 69.8% |
| LOAD_FAST_AND_CLEAR LOAD_FAST_AND_CLEAR | 8,186,520 | 0.3% | 70.1% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 8,128,020 | 0.3% | 70.3% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 8,128,020 | 0.3% | 70.6% |
| YIELD_VALUE YIELD_VALUE | 8,128,020 | 0.3% | 70.8% |
| SEND_GEN RESUME_CHECK | 8,128,020 | 0.3% | 71.1% |
| LOAD_FAST BUILD_LIST | 8,036,380 | 0.3% | 71.4% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 7,892,920 | 0.3% | 71.6% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 7,870,480 | 0.3% | 71.9% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 7,758,780 | 0.3% | 72.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,729,460 | 97.7% |
| LOAD_CONST | 65,460 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,729,460 | 97.7% |
| CALL_BUILTIN_CLASS | 39,540 | 1.4% |
| GET_ITER | 15,180 | 0.5% |
| TO_BOOL_LIST | 10,740 | 0.4% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 23,315,240 | 85.4% |
| POP_TOP | 3,945,060 | 14.5% |
| MAKE_CELL | 36,840 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 843,900 | 70.2% |
| ENTER_EXECUTOR | 312,000 | 25.9% |
| LOAD_ATTR_SLOT | 46,800 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,202,700 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,071,440 | 99.1% |
| LOAD_FAST_LOAD_FAST | 9,480 | 0.9% |
| BINARY_SUBSCR | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,080,900 | 100.0% |
| BINARY_SUBSCR | 380 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 111,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 111,300 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,582,360 | 53.7% |
| LOAD_FAST | 8,617,440 | 36.8% |
| LOAD_ATTR_SLOT | 883,680 | 3.8% |
| RETURN_GENERATOR | 628,500 | 2.7% |
| BUILD_TUPLE | 387,960 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 7,585,940 | 32.4% |
| FOR_ITER | 7,537,300 | 32.2% |
| LOAD_FAST_AND_CLEAR | 4,304,520 | 18.4% |
| CALL_PY_EXACT_ARGS | 3,358,560 | 14.3% |
| FOR_ITER_GEN | 617,460 | 2.6% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 13,635,320 | 50.0% |
| YIELD_VALUE | 7,232,760 | 26.5% |
| RETURN_CONST | 6,429,060 | 23.6% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,500,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,493,480 | 55.4% |
| SET_FUNCTION_ATTRIBUTE | 1,172,460 | 26.1% |
| LOAD_FAST | 834,540 | 18.5% |
| STORE_FAST | 120 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,021,020 | 84.7% |
| POP_JUMP_IF_FALSE | 398,340 | 8.4% |
| STORE_FAST | 329,640 | 6.9% |
| POP_JUMP_IF_TRUE | 720 | 0.0% |
| POP_TOP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,287,700 | 69.2% |
| LOAD_FAST | 1,431,480 | 30.1% |
| LOAD_GLOBAL_MODULE | 28,200 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 1,980 | 0.0% |
| LOAD_CONST | 360 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 55,680 | 50.0% |
| POP_TOP | 55,620 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 83,700 | 75.2% |
| JUMP_FORWARD | 27,600 | 24.8% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 17,179,980 | 32.3% |
| RESUME_CHECK | 12,013,440 | 22.6% |
| POP_JUMP_IF_FALSE | 5,079,540 | 9.5% |
| STORE_FAST | 4,480,260 | 8.4% |
| CACHE | 3,945,060 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,204,660 | 28.6% |
| RESUME_CHECK | 7,648,920 | 14.4% |
| JUMP_BACKWARD | 6,638,860 | 12.5% |
| ENTER_EXECUTOR | 4,757,820 | 8.9% |
| STORE_FAST | 4,476,240 | 8.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 83,280 | 74.8% |
| BINARY_SUBSCR_LIST_INT | 27,900 | 25.1% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 111,300 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,859,840 | 67.0% |
| CALL_BUILTIN_FAST | 1,423,980 | 13.9% |
| LOAD_ATTR_MODULE | 1,089,100 | 10.6% |
| LOAD_DEREF | 429,000 | 4.2% |
| LOAD_FAST_LOAD_FAST | 214,620 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,060,860 | 39.6% |
| LOAD_FAST | 3,582,400 | 35.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 888,580 | 8.7% |
| LOAD_CONST | 818,460 | 8.0% |
| CALL_PY_EXACT_ARGS | 717,620 | 7.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,211,820 | 25.2% |
| RETURN_VALUE | 10,357,560 | 13.6% |
| CALL_BUILTIN_O | 10,327,740 | 13.5% |
| BUILD_LIST | 6,088,980 | 8.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,175,040 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,930,060 | 22.2% |
| INTERPRETER_EXIT | 13,635,320 | 17.9% |
| RETURN_VALUE | 10,357,560 | 13.6% |
| MAP_ADD | 6,194,160 | 8.1% |
| LOAD_ATTR_METHOD_NO_DICT | 5,601,240 | 7.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,984,360 | 99.8% |
| COPY | 9,040 | 0.2% |
| TO_BOOL | 1,940 | 0.0% |
| RETURN_CONST | 80 | 0.0% |
| TO_BOOL_NONE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,984,020 | 99.8% |
| POP_JUMP_IF_TRUE | 9,240 | 0.2% |
| TO_BOOL | 1,940 | 0.0% |
| TO_BOOL_NONE | 240 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 20 | 0.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,410,340 | 99.2% |
| TO_BOOL_ALWAYS_TRUE | 20,920 | 0.6% |
| TO_BOOL_NONE | 6,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,363,540 | 97.8% |
| COPY | 46,800 | 1.4% |
| STORE_FAST | 27,600 | 0.8% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 25,440 | 82.4% |
| LOAD_FAST_LOAD_FAST | 3,360 | 10.9% |
| CALL_BUILTIN_CLASS | 1,080 | 3.5% |
| BUILD_LIST | 620 | 2.0% |
| BINARY_OP | 300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 25,200 | 81.6% |
| GET_ITER | 3,120 | 10.1% |
| STORE_FAST | 1,500 | 4.9% |
| LOAD_FAST_LOAD_FAST | 620 | 2.0% |
| BINARY_OP | 300 | 1.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 56,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,620 | 34.9% |
| DICT_MERGE | 16,320 | 29.0% |
| LOAD_DEREF | 15,600 | 27.7% |
| CALL_FUNCTION_EX | 4,080 | 7.3% |
| STORE_FAST | 600 | 1.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,036,380 | 80.1% |
| STORE_FAST | 1,172,760 | 11.7% |
| SWAP | 200,940 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 144,360 | 1.4% |
| LOAD_CONST | 138,600 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,088,980 | 60.7% |
| STORE_FAST | 2,394,660 | 23.9% |
| COMPARE_OP | 882,960 | 8.8% |
| LOAD_FAST | 216,480 | 2.2% |
| SWAP | 200,940 | 2.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,098,900 | 78.5% |
| LOAD_CONST | 860,580 | 16.5% |
| RESUME_CHECK | 67,900 | 1.3% |
| POP_JUMP_IF_NOT_NONE | 55,680 | 1.1% |
| CALL_INTRINSIC_1 | 37,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,098,900 | 78.5% |
| LOAD_FAST | 807,720 | 15.5% |
| STORE_FAST | 139,540 | 2.7% |
| LOAD_DEREF | 74,160 | 1.4% |
| LOAD_GLOBAL_MODULE | 50,160 | 1.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,391,720 | 47.5% |
| LOAD_GLOBAL_BUILTIN | 5,889,300 | 24.6% |
| CALL_TUPLE_1 | 2,493,480 | 10.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,303,520 | 9.6% |
| LOAD_ATTR_MODULE | 537,360 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,273,260 | 30.4% |
| CALL_ISINSTANCE | 6,548,820 | 27.3% |
| CALL_BUILTIN_O | 5,045,160 | 21.1% |
| LOAD_CONST | 1,183,800 | 4.9% |
| SWAP | 1,070,700 | 4.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,636,340 | 59.8% |
| LOAD_CONST | 1,179,840 | 19.4% |
| LOAD_ATTR_SLOT | 1,079,240 | 17.7% |
| RETURN_GENERATOR | 46,920 | 0.8% |
| BUILD_LIST | 40,800 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 3,586,980 | 59.0% |
| LOAD_FAST | 1,087,080 | 17.9% |
| CALL_LIST_APPEND | 1,079,240 | 17.7% |
| STORE_FAST | 106,920 | 1.8% |
| GET_ITER | 53,640 | 0.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 948,840 | 96.3% |
| ENTER_EXECUTOR | 15,300 | 1.6% |
| BUILD_MAP | 11,520 | 1.2% |
| BUILD_CONST_KEY_MAP | 4,080 | 0.4% |
| RETURN_GENERATOR | 4,020 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 747,720 | 75.9% |
| RETURN_VALUE | 121,500 | 12.3% |
| RESUME_CHECK | 96,000 | 9.7% |
| LOAD_ATTR_METHOD_NO_DICT | 9,280 | 0.9% |
| LIST_APPEND | 3,840 | 0.4% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 75,120 | 86.7% |
| LIST_APPEND | 11,520 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,360 | 55.8% |
| BUILD_MAP | 37,320 | 43.1% |
| CALL_FUNCTION_EX | 960 | 1.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,205,940 | 99.8% |
| ENTER_EXECUTOR | 4,100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 906,600 | 41.0% |
| RETURN_GENERATOR | 604,740 | 27.4% |
| RETURN_VALUE | 513,600 | 23.2% |
| MAKE_CELL | 125,760 | 5.7% |
| STORE_FAST | 52,980 | 2.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,675,040 | 44.9% |
| LOAD_ATTR | 8,444,700 | 43.7% |
| BUILD_LIST | 882,960 | 4.6% |
| RETURN_VALUE | 780,300 | 4.0% |
| CALL_BUILTIN_CLASS | 230,280 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,481,420 | 90.5% |
| POP_JUMP_IF_TRUE | 966,060 | 5.0% |
| RETURN_VALUE | 784,620 | 4.1% |
| COPY | 67,260 | 0.3% |
| STORE_FAST | 15,600 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,220,400 | 33.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,197,640 | 33.5% |
| LOAD_FAST_LOAD_FAST | 2,308,680 | 18.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,483,560 | 11.9% |
| BUILD_TUPLE | 265,560 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,959,140 | 79.6% |
| POP_JUMP_IF_TRUE | 1,693,560 | 13.5% |
| STORE_FAST | 859,500 | 6.9% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,210,040 | 81.5% |
| CALL_ISINSTANCE | 2,699,640 | 7.5% |
| IS_OP | 2,253,480 | 6.3% |
| RETURN_CONST | 1,228,140 | 3.4% |
| RETURN_VALUE | 257,400 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 22,131,480 | 61.8% |
| TO_BOOL_ALWAYS_TRUE | 6,549,140 | 18.3% |
| TO_BOOL_BOOL | 5,396,660 | 15.1% |
| TO_BOOL_NONE | 1,521,340 | 4.2% |
| TO_BOOL_STR | 172,840 | 0.5% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,586,980 | 77.2% |
| CALL_PY_EXACT_ARGS | 1,007,540 | 21.7% |
| ENTER_EXECUTOR | 31,320 | 0.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 13,920 | 0.3% |
| CALL_FUNCTION_EX | 2,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,616,660 | 99.4% |
| RETURN_GENERATOR | 28,860 | 0.6% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 791,700 | 83.4% |
| LOAD_DEREF | 74,160 | 7.8% |
| RETURN_VALUE | 50,160 | 5.3% |
| BUILD_CONST_KEY_MAP | 16,320 | 1.7% |
| DICT_UPDATE | 13,140 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 948,840 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 13,140 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 7,167,520 | 33.6% |
| POP_TOP | 4,757,820 | 22.3% |
| JUMP_FORWARD | 3,131,100 | 14.7% |
| POP_JUMP_IF_FALSE | 2,563,480 | 12.0% |
| POP_JUMP_IF_TRUE | 1,241,140 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 9,470,240 | 44.3% |
| JUMP_BACKWARD | 5,310,840 | 24.9% |
| LOAD_FAST | 1,610,680 | 7.5% |
| YIELD_VALUE | 1,327,080 | 6.2% |
| FOR_ITER | 935,140 | 4.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,202,280 | 67.7% |
| TO_BOOL_BOOL | 2,025,020 | 19.0% |
| JUMP_BACKWARD | 633,400 | 6.0% |
| POP_TOP | 361,200 | 3.4% |
| TO_BOOL_NONE | 338,740 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,167,520 | 67.4% |
| POP_JUMP_IF_FALSE | 2,363,760 | 22.2% |
| FOR_ITER | 440,280 | 4.1% |
| JUMP_BACKWARD | 404,000 | 3.8% |
| FOR_ITER_GEN | 224,880 | 2.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 26,259,900 | 62.3% |
| GET_ITER | 7,537,300 | 17.9% |
| SWAP | 4,060,200 | 9.6% |
| LOAD_FAST | 2,925,660 | 6.9% |
| ENTER_EXECUTOR | 935,140 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 23,153,580 | 54.9% |
| RETURN_CONST | 6,535,620 | 15.5% |
| SWAP | 4,054,920 | 9.6% |
| STORE_FAST | 3,733,080 | 8.9% |
| LOAD_FAST | 2,919,060 | 6.9% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 2,253,480 | 74.1% |
| LOAD_FAST_LOAD_FAST | 509,400 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 218,520 | 7.2% |
| LOAD_DEREF | 57,000 | 1.9% |
| LOAD_GLOBAL_MODULE | 3,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,253,480 | 74.1% |
| POP_JUMP_IF_FALSE | 779,040 | 25.6% |
| RETURN_VALUE | 9,720 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,758,240 | 21.5% |
| POP_TOP | 6,638,860 | 21.1% |
| MAP_ADD | 6,275,540 | 19.9% |
| ENTER_EXECUTOR | 5,310,840 | 16.9% |
| POP_JUMP_IF_FALSE | 1,418,540 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 26,259,900 | 83.5% |
| FOR_ITER_GEN | 4,561,200 | 14.5% |
| EXTENDED_ARG | 633,400 | 2.0% |
| FOR_ITER_LIST | 2,060 | 0.0% |
| ENTER_EXECUTOR | 500 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,152,820 | 29.8% |
| RETURN_VALUE | 2,878,080 | 27.2% |
| STORE_FAST | 1,555,620 | 14.7% |
| POP_JUMP_IF_FALSE | 1,118,040 | 10.6% |
| ENTER_EXECUTOR | 625,080 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,268,260 | 30.9% |
| ENTER_EXECUTOR | 3,131,100 | 29.6% |
| YIELD_VALUE | 1,826,220 | 17.3% |
| STORE_FAST | 1,596,480 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 276,960 | 2.6% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 74,400 | 78.9% |
| STORE_FAST | 19,200 | 20.4% |
| CALL | 720 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 75,120 | 79.6% |
| LOAD_FAST | 19,200 | 20.4% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,716,960 | 91.5% |
| LOAD_FAST | 1,609,700 | 7.9% |
| LOAD_ATTR_MODULE | 70,200 | 0.3% |
| LOAD_ATTR | 20,760 | 0.1% |
| LOAD_FAST_LOAD_FAST | 18,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 8,444,700 | 41.3% |
| CALL_PY_EXACT_ARGS | 8,245,440 | 40.3% |
| LOAD_FAST | 1,580,160 | 7.7% |
| LOAD_GLOBAL_MODULE | 689,280 | 3.4% |
| CALL_PY_WITH_DEFAULTS | 650,280 | 3.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 16,861,500 | 29.4% |
| LOAD_FAST | 8,315,000 | 14.5% |
| LOAD_ATTR_METHOD_NO_DICT | 5,396,360 | 9.4% |
| STORE_FAST | 4,349,700 | 7.6% |
| GET_YIELD_FROM_ITER | 3,075,360 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 12,312,720 | 21.5% |
| LOAD_FAST | 6,773,040 | 11.8% |
| STORE_FAST | 5,598,060 | 9.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,884,420 | 8.5% |
| MAKE_FUNCTION | 4,500,600 | 7.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,923,120 | 50.1% |
| POP_JUMP_IF_FALSE | 2,367,120 | 17.1% |
| RESUME_CHECK | 1,756,860 | 12.7% |
| STORE_FAST | 863,340 | 6.3% |
| LOAD_GLOBAL_BUILTIN | 463,200 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,980,160 | 50.6% |
| LOAD_ATTR_METHOD_NO_DICT | 3,775,560 | 27.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 706,860 | 5.1% |
| RETURN_VALUE | 435,900 | 3.2% |
| PUSH_NULL | 429,000 | 3.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 100,555,580 | 15.8% |
| LOAD_ATTR_SLOT | 89,843,880 | 14.1% |
| LOAD_GLOBAL_BUILTIN | 80,446,280 | 12.6% |
| RESUME_CHECK | 77,504,480 | 12.1% |
| STORE_ATTR_SLOT | 46,512,180 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 192,162,020 | 30.1% |
| LOAD_GLOBAL_BUILTIN | 41,121,900 | 6.4% |
| STORE_ATTR_SLOT | 39,241,700 | 6.2% |
| LOAD_ATTR_METHOD_NO_DICT | 34,366,740 | 5.4% |
| CALL_PY_EXACT_ARGS | 31,108,720 | 4.9% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 46,800 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,234,420 | 20.2% |
| LOAD_GLOBAL_BUILTIN | 5,979,780 | 13.1% |
| STORE_ATTR_SLOT | 4,213,980 | 9.2% |
| POP_JUMP_IF_FALSE | 4,197,340 | 9.2% |
| PUSH_NULL | 4,060,860 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,639,780 | 27.7% |
| STORE_ATTR_SLOT | 8,555,100 | 18.7% |
| BINARY_SUBSCR_LIST_INT | 3,303,300 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,134,020 | 6.9% |
| CALL_BUILTIN_FAST | 2,844,960 | 6.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 34.5% |
| RETURN_VALUE | 160 | 27.6% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 10.3% |
| RESUME_CHECK | 40 | 6.9% |
| STORE_ATTR_SLOT | 40 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 340 | 58.6% |
| LOAD_GLOBAL_BUILTIN | 160 | 27.6% |
| LOAD_ATTR | 80 | 13.8% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,443,420 | 48.0% |
| MAKE_CELL | 660,840 | 22.0% |
| CALL_PY_WITH_DEFAULTS | 565,560 | 18.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 171,620 | 5.7% |
| CALL_KW | 125,760 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,774,140 | 59.1% |
| MAKE_CELL | 660,840 | 22.0% |
| RETURN_GENERATOR | 569,460 | 19.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 67,893,700 | 42.7% |
| COMPARE_OP | 17,481,420 | 11.0% |
| TO_BOOL_NONE | 16,506,040 | 10.4% |
| COMPARE_OP_INT | 15,367,200 | 9.7% |
| TO_BOOL_ALWAYS_TRUE | 10,241,500 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,555,580 | 63.2% |
| RETURN_CONST | 16,576,620 | 10.4% |
| LOAD_GLOBAL_MODULE | 9,492,300 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 8,928,780 | 5.6% |
| POP_TOP | 5,079,540 | 3.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,407,000 | 97.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,880 | 2.3% |
| BINARY_SUBSCR_LIST_INT | 7,800 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,560 | 95.8% |
| LOAD_GLOBAL_BUILTIN | 50,640 | 3.5% |
| LOAD_FAST_LOAD_FAST | 7,800 | 0.5% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| ENTER_EXECUTOR | 620 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,538,520 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 18,120 | 0.2% |
| LOAD_ATTR_SLOT | 8,580 | 0.1% |
| STORE_FAST_LOAD_FAST | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,982,300 | 79.1% |
| LOAD_FAST | 1,349,160 | 17.8% |
| BUILD_LIST | 144,360 | 1.9% |
| BUILD_MAP | 55,680 | 0.7% |
| LOAD_GLOBAL_MODULE | 27,600 | 0.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 21,122,620 | 36.7% |
| TO_BOOL_ALWAYS_TRUE | 20,015,580 | 34.8% |
| TO_BOOL_STR | 8,229,800 | 14.3% |
| TO_BOOL_NONE | 5,343,660 | 9.3% |
| CONTAINS_OP | 1,693,560 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,609,980 | 55.0% |
| EXTENDED_ARG | 7,202,280 | 12.5% |
| JUMP_BACKWARD | 6,758,240 | 11.8% |
| LOAD_GLOBAL_BUILTIN | 3,453,300 | 6.0% |
| STORE_FAST | 3,140,760 | 5.5% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,576,620 | 38.8% |
| STORE_ATTR_SLOT | 13,920,120 | 32.6% |
| FOR_ITER | 6,535,620 | 15.3% |
| POP_TOP | 2,768,880 | 6.5% |
| POP_JUMP_IF_TRUE | 1,715,460 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 17,179,980 | 40.2% |
| TO_BOOL_NONE | 10,700,040 | 25.0% |
| INTERPRETER_EXIT | 6,429,060 | 15.0% |
| END_SEND | 3,075,360 | 7.2% |
| RETURN_VALUE | 1,390,440 | 3.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,172,460 | 99.8% |
| SET_FUNCTION_ATTRIBUTE | 1,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 571,000 | 48.6% |
| LOAD_CONST | 569,460 | 48.5% |
| LOAD_FAST | 24,840 | 2.1% |
| LOAD_GLOBAL_BUILTIN | 4,020 | 0.3% |
| STORE_DEREF | 2,760 | 0.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 57.1% |
| LOAD_FAST_LOAD_FAST | 120 | 42.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 280 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 133,500 | 74.9% |
| STORE_FAST | 39,540 | 22.2% |
| SET_FUNCTION_ATTRIBUTE | 2,760 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,080 | 0.6% |
| BUILD_LIST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 134,460 | 75.5% |
| LOAD_GLOBAL_BUILTIN | 39,540 | 22.2% |
| LOAD_GLOBAL_MODULE | 1,800 | 1.0% |
| LOAD_FAST | 1,320 | 0.7% |
| STORE_FAST | 1,080 | 0.6% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 16,930,060 | 17.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 12,246,980 | 12.8% |
| STORE_FAST | 8,284,260 | 8.7% |
| FOR_ITER_LIST | 7,395,540 | 7.7% |
| LOAD_FAST | 7,025,060 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,572,900 | 39.3% |
| LOAD_GLOBAL_BUILTIN | 18,876,900 | 19.8% |
| LOAD_FAST_LOAD_FAST | 9,234,420 | 9.7% |
| STORE_FAST | 8,284,260 | 8.7% |
| POP_TOP | 4,480,260 | 4.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 25,634,980 | 98.4% |
| UNPACK_EX | 218,520 | 0.8% |
| UNPACK_SEQUENCE | 96,000 | 0.4% |
| UNPACK_SEQUENCE_TUPLE | 90,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,825,760 | 56.9% |
| LOAD_GLOBAL_MODULE | 6,181,720 | 23.7% |
| LOAD_GLOBAL_BUILTIN | 4,445,040 | 17.1% |
| LOAD_FAST_LOAD_FAST | 496,980 | 1.9% |
| STORE_FAST | 90,960 | 0.3% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 22,131,480 | 61.4% |
| LOAD_FAST_AND_CLEAR | 4,304,520 | 12.0% |
| BUILD_MAP | 4,098,900 | 11.4% |
| FOR_ITER | 4,054,920 | 11.3% |
| BUILD_TUPLE | 1,070,700 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 22,131,480 | 61.4% |
| STORE_FAST | 4,206,780 | 11.7% |
| BUILD_MAP | 4,098,900 | 11.4% |
| FOR_ITER | 4,060,200 | 11.3% |
| POP_TOP | 1,071,420 | 3.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 96,000 | 99.9% |
| UNPACK_SEQUENCE | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 96,000 | 99.9% |
| UNPACK_SEQUENCE | 80 | 0.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 7,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,800 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,664,100 | 90.6% |
| LOAD_CONST | 2,273,560 | 9.1% |
| LOAD_FAST_LOAD_FAST | 72,120 | 0.3% |
| RETURN_VALUE | 120 | 0.0% |
| RETURN_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 22,131,480 | 88.5% |
| STORE_FAST | 1,697,040 | 6.8% |
| CALL_PY_EXACT_ARGS | 1,088,520 | 4.4% |
| LIST_APPEND | 72,120 | 0.3% |
| BINARY_OP_SUBTRACT_INT | 20,160 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,840 | 99.7% |
| BINARY_OP | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 7,800 | 99.2% |
| BINARY_OP | 60 | 0.8% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,312,720 | 91.7% |
| CALL_LEN | 1,079,220 | 8.0% |
| BINARY_OP_ADD_INT | 20,160 | 0.2% |
| LOAD_ATTR_SLOT | 7,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 10,365,480 | 77.2% |
| CALL_PY_EXACT_ARGS | 1,102,620 | 8.2% |
| LOAD_CONST | 1,079,220 | 8.0% |
| LOAD_FAST | 844,620 | 6.3% |
| RETURN_VALUE | 20,160 | 0.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 847,740 | 43.8% |
| LOAD_ATTR_SLOT | 556,260 | 28.7% |
| LOAD_CONST | 357,840 | 18.5% |
| CALL_BUILTIN_O | 105,360 | 5.4% |
| BUILD_TUPLE | 27,600 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,230,780 | 63.6% |
| BUILD_TUPLE | 251,760 | 13.0% |
| LOAD_FAST_LOAD_FAST | 117,540 | 6.1% |
| RETURN_VALUE | 100,200 | 5.2% |
| PUSH_EXC_INFO | 83,280 | 4.3% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 15,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,600 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,303,300 | 73.9% |
| LOAD_CONST | 1,166,980 | 26.1% |
| BINARY_SUBSCR_LIST_INT | 520 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,269,100 | 73.1% |
| LOAD_FAST | 1,141,920 | 25.5% |
| PUSH_EXC_INFO | 27,900 | 0.6% |
| STORE_FAST | 11,700 | 0.3% |
| LOAD_FAST_LOAD_FAST | 7,800 | 0.2% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 10,365,480 | 48.1% |
| LOAD_ATTR_SLOT | 10,356,180 | 48.0% |
| LOAD_FAST | 843,900 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,721,660 | 96.1% |
| STORE_FAST | 843,900 | 3.9% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 892,000 | 46.5% |
| PUSH_NULL | 888,580 | 46.4% |
| LOAD_ATTR_SLOT | 54,600 | 2.8% |
| ENTER_EXECUTOR | 49,180 | 2.6% |
| CALL_PY_EXACT_ARGS | 24,220 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,706,460 | 89.0% |
| MAKE_CELL | 171,620 | 9.0% |
| CALL_PY_EXACT_ARGS | 24,980 | 1.3% |
| COPY_FREE_VARS | 13,920 | 0.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 446,160 | 81.6% |
| BINARY_SLICE | 39,540 | 7.2% |
| CALL_BUILTIN_FAST | 35,760 | 6.5% |
| LOAD_FAST | 11,240 | 2.1% |
| LOAD_ATTR | 7,800 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 230,280 | 42.1% |
| JUMP_FORWARD | 193,680 | 35.4% |
| GET_ITER | 50,280 | 9.2% |
| RETURN_VALUE | 37,320 | 6.8% |
| CALL_LEN | 20,160 | 3.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,844,960 | 95.1% |
| LOAD_CONST | 85,680 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 50,640 | 1.7% |
| RETURN_GENERATOR | 4,560 | 0.2% |
| LOAD_DEREF | 3,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,478,460 | 49.4% |
| PUSH_NULL | 1,423,980 | 47.6% |
| STORE_FAST | 50,640 | 1.7% |
| CALL_BUILTIN_CLASS | 35,760 | 1.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,282,580 | 43.1% |
| BUILD_TUPLE | 5,045,160 | 41.2% |
| LOAD_FAST | 1,914,220 | 15.6% |
| RETURN_VALUE | 14,040 | 0.1% |
| RETURN_GENERATOR | 1,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,327,740 | 84.3% |
| TO_BOOL_BOOL | 1,428,900 | 11.7% |
| STORE_FAST | 266,800 | 2.2% |
| STORE_SUBSCR_DICT | 110,880 | 0.9% |
| BINARY_SUBSCR_DICT | 105,360 | 0.9% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,017,340 | 37.7% |
| LOAD_GLOBAL_MODULE | 14,117,260 | 22.2% |
| LOAD_ATTR_MODULE | 9,203,940 | 14.5% |
| LOAD_ATTR_SLOT | 7,586,880 | 11.9% |
| BUILD_TUPLE | 6,548,820 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,710,960 | 93.8% |
| COPY | 2,699,640 | 4.2% |
| STORE_FAST | 1,174,440 | 1.8% |
| RETURN_VALUE | 66,540 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,323,260 | 94.7% |
| LOAD_DEREF | 35,520 | 2.5% |
| CALL_BUILTIN_CLASS | 20,160 | 1.4% |
| LOAD_ATTR_SLOT | 9,280 | 0.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 7,800 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 1,079,220 | 77.3% |
| STORE_FAST | 110,820 | 7.9% |
| LOAD_FAST | 56,220 | 4.0% |
| LOAD_CONST | 54,120 | 3.9% |
| COMPARE_OP_INT | 52,900 | 3.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,641,320 | 70.6% |
| CALL | 1,079,240 | 28.8% |
| RETURN_VALUE | 13,120 | 0.4% |
| BUILD_TUPLE | 6,720 | 0.2% |
| ENTER_EXECUTOR | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,709,220 | 45.7% |
| JUMP_BACKWARD | 1,121,120 | 30.0% |
| ENTER_EXECUTOR | 590,380 | 15.8% |
| LOAD_FAST | 264,480 | 7.1% |
| RETURN_CONST | 51,240 | 1.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 8,303,280 | 42.1% |
| LOAD_CONST | 4,884,420 | 24.8% |
| LOAD_FAST | 4,835,520 | 24.5% |
| LOAD_ATTR_METHOD_NO_DICT | 756,340 | 3.8% |
| LOAD_ATTR | 642,900 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,246,980 | 62.2% |
| RETURN_VALUE | 4,175,040 | 21.2% |
| CALL_PY_WITH_DEFAULTS | 2,622,420 | 13.3% |
| TO_BOOL_BOOL | 537,240 | 2.7% |
| LOAD_GLOBAL_MODULE | 63,000 | 0.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 19,174,820 | 100.0% |
| LOAD_FAST | 4,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,582,360 | 65.6% |
| BUILD_TUPLE | 2,303,520 | 12.0% |
| TO_BOOL_BOOL | 1,094,820 | 5.7% |
| CALL_PY_EXACT_ARGS | 1,071,440 | 5.6% |
| RETURN_VALUE | 893,280 | 4.7% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,108,720 | 44.9% |
| LOAD_ATTR | 8,245,440 | 11.9% |
| LOAD_ATTR_METHOD_NO_DICT | 5,883,240 | 8.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,617,040 | 5.2% |
| LOAD_CONST | 3,495,900 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60,450,140 | 87.2% |
| RETURN_GENERATOR | 6,369,780 | 9.2% |
| MAKE_CELL | 1,443,420 | 2.1% |
| COPY_FREE_VARS | 1,007,540 | 1.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 24,220 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,470,240 | 54.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,622,420 | 15.0% |
| LOAD_ATTR_METHOD_NO_DICT | 2,535,620 | 14.5% |
| LOAD_FAST | 1,255,600 | 7.2% |
| LOAD_ATTR | 650,280 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,886,360 | 96.5% |
| MAKE_CELL | 565,560 | 3.2% |
| RETURN_GENERATOR | 40,800 | 0.2% |
| COPY_FREE_VARS | 2,880 | 0.0% |
| CALL_PY_EXACT_ARGS | 800 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 54,600 | 97.4% |
| STORE_FAST | 1,440 | 2.6% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,830,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 2,253,480 | 46.7% |
| LOAD_GLOBAL_BUILTIN | 2,253,480 | 46.7% |
| STORE_FAST | 268,320 | 5.6% |
| LOAD_FAST_LOAD_FAST | 55,200 | 1.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,575,580 | 83.8% |
| LOAD_CONST | 4,029,180 | 15.6% |
| CALL_LEN | 52,900 | 0.2% |
| LOAD_FAST | 46,920 | 0.2% |
| LOAD_DEREF | 20,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,367,200 | 59.7% |
| LOAD_FAST | 10,365,480 | 40.3% |
| POP_JUMP_IF_TRUE | 15,480 | 0.1% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,118,220 | 56.1% |
| RETURN_VALUE | 470,760 | 23.6% |
| LOAD_CONST | 193,440 | 9.7% |
| LOAD_FAST | 140,400 | 7.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 62,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,520,700 | 76.3% |
| RETURN_VALUE | 439,080 | 22.0% |
| COPY | 30,840 | 1.5% |
| POP_JUMP_IF_TRUE | 2,160 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,585,940 | 97.0% |
| SWAP | 190,800 | 2.4% |
| LOAD_FAST | 27,060 | 0.3% |
| EXTENDED_ARG | 6,640 | 0.1% |
| ENTER_EXECUTOR | 5,040 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,395,540 | 94.6% |
| JUMP_BACKWARD | 185,980 | 2.4% |
| LOAD_FAST | 155,300 | 2.0% |
| SWAP | 44,180 | 0.6% |
| RETURN_CONST | 16,980 | 0.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 240 | 57.1% |
| JUMP_BACKWARD | 180 | 42.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300 | 71.4% |
| LOAD_FAST | 120 | 28.6% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,593,260 | 95.9% |
| LOAD_FAST_LOAD_FAST | 240,000 | 4.1% |
| LOAD_ATTR_INSTANCE_VALUE | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 5,282,580 | 90.5% |
| IS_OP | 218,520 | 3.7% |
| RETURN_VALUE | 81,720 | 1.4% |
| LOAD_ATTR_METHOD_NO_DICT | 63,360 | 1.1% |
| LOAD_FAST | 39,720 | 0.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,366,740 | 44.8% |
| LOAD_ATTR_SLOT | 20,263,620 | 26.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 8,386,500 | 10.9% |
| RETURN_VALUE | 5,601,240 | 7.3% |
| LOAD_DEREF | 3,775,560 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,727,260 | 40.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,174,820 | 25.0% |
| LOAD_GLOBAL_MODULE | 10,565,820 | 13.8% |
| CALL_PY_EXACT_ARGS | 5,883,240 | 7.7% |
| LOAD_CONST | 5,396,360 | 7.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,516,800 | 93.6% |
| LOAD_DEREF | 706,860 | 5.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 71,080 | 0.6% |
| CALL_FUNCTION_EX | 3,840 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,993,040 | 32.4% |
| CALL_PY_EXACT_ARGS | 3,617,040 | 29.4% |
| LOAD_FAST_LOAD_FAST | 3,102,360 | 25.2% |
| LOAD_CONST | 884,280 | 7.2% |
| CALL_PY_WITH_DEFAULTS | 577,260 | 4.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,566,000 | 100.0% |
| LOAD_FAST | 5,280 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 9,203,940 | 73.2% |
| PUSH_NULL | 1,089,100 | 8.7% |
| LOAD_GLOBAL_MODULE | 924,720 | 7.4% |
| BUILD_TUPLE | 537,360 | 4.3% |
| LOAD_FAST | 324,480 | 2.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,354,300 | 82.1% |
| LOAD_FAST_LOAD_FAST | 3,134,020 | 17.9% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 8,386,500 | 48.0% |
| CONTAINS_OP | 4,197,640 | 24.0% |
| CALL_PY_EXACT_ARGS | 3,269,240 | 18.7% |
| STORE_FAST | 1,071,420 | 6.1% |
| LOAD_FAST | 454,320 | 2.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,870,480 | 83.6% |
| LOAD_FAST_LOAD_FAST | 1,476,000 | 15.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 72,120 | 0.8% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,597,160 | 27.6% |
| LOAD_GLOBAL_BUILTIN | 2,493,480 | 26.5% |
| CONTAINS_OP | 1,483,560 | 15.8% |
| FORMAT_SIMPLE | 1,423,980 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,310,460 | 13.9% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,758,780 | 97.6% |
| LOAD_FAST_LOAD_FAST | 63,720 | 0.8% |
| ENTER_EXECUTOR | 63,020 | 0.8% |
| BINARY_SUBSCR_DICT | 24,480 | 0.3% |
| STORE_FAST_LOAD_FAST | 15,820 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,892,920 | 99.3% |
| RETURN_VALUE | 25,320 | 0.3% |
| STORE_FAST | 21,080 | 0.3% |
| COPY | 6,240 | 0.1% |
| SET_ADD | 2,940 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 192,162,020 | 81.0% |
| COPY | 22,131,480 | 9.3% |
| LOAD_ATTR_SLOT | 13,789,320 | 5.8% |
| LOAD_DEREF | 6,980,160 | 2.9% |
| LOAD_FAST_LOAD_FAST | 2,008,920 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,843,880 | 37.9% |
| COMPARE_OP_INT | 21,575,580 | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 20,263,620 | 8.5% |
| LOAD_CONST | 16,861,500 | 7.1% |
| LOAD_ATTR_SLOT | 13,789,320 | 5.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,121,900 | 31.2% |
| RESUME_CHECK | 26,935,260 | 20.4% |
| STORE_FAST | 18,876,900 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 11,834,920 | 9.0% |
| POP_JUMP_IF_FALSE | 8,928,780 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,446,280 | 61.1% |
| CALL_ISINSTANCE | 24,017,340 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 11,834,920 | 9.0% |
| LOAD_FAST_LOAD_FAST | 5,979,780 | 4.5% |
| BUILD_TUPLE | 5,889,300 | 4.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,615,600 | 39.1% |
| LOAD_ATTR_METHOD_NO_DICT | 10,565,820 | 13.9% |
| POP_JUMP_IF_FALSE | 9,492,300 | 12.5% |
| STORE_FAST_STORE_FAST | 6,181,720 | 8.2% |
| STORE_FAST | 3,667,220 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,598,860 | 32.5% |
| LOAD_ATTR | 18,716,960 | 24.7% |
| CALL_ISINSTANCE | 14,117,260 | 18.6% |
| LOAD_ATTR_MODULE | 12,566,000 | 16.6% |
| LOAD_FAST_LOAD_FAST | 4,018,400 | 5.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 60,450,140 | 43.7% |
| CACHE | 23,315,240 | 16.9% |
| CALL_PY_WITH_DEFAULTS | 16,886,360 | 12.2% |
| SEND_GEN | 8,128,020 | 5.9% |
| LOAD_ATTR_PROPERTY | 7,892,920 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,504,480 | 56.1% |
| LOAD_GLOBAL_BUILTIN | 26,935,260 | 19.5% |
| POP_TOP | 12,013,440 | 8.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 8,128,020 | 5.9% |
| NOP | 4,021,020 | 2.9% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,241,700 | 55.9% |
| SWAP | 22,131,480 | 31.5% |
| LOAD_FAST_LOAD_FAST | 8,555,100 | 12.2% |
| STORE_ATTR_SLOT | 128,280 | 0.2% |
| ENTER_EXECUTOR | 117,720 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,512,180 | 66.3% |
| RETURN_CONST | 13,920,120 | 19.8% |
| LOAD_FAST_LOAD_FAST | 4,213,980 | 6.0% |
| LOAD_CONST | 1,522,560 | 2.2% |
| JUMP_BACKWARD | 1,210,200 | 1.7% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,322,400 | 85.2% |
| CALL_BUILTIN_O | 110,880 | 7.1% |
| RETURN_VALUE | 106,200 | 6.8% |
| LOAD_FAST_LOAD_FAST | 13,080 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,281,240 | 82.5% |
| LOAD_GLOBAL_MODULE | 105,360 | 6.8% |
| LOAD_FAST | 97,440 | 6.3% |
| POP_EXCEPT | 55,680 | 3.6% |
| ENTER_EXECUTOR | 12,480 | 0.8% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,422,560 | 44.2% |
| LOAD_FAST | 9,419,940 | 31.0% |
| COPY | 6,549,140 | 21.5% |
| STORE_FAST_LOAD_FAST | 863,880 | 2.8% |
| TO_BOOL_ALWAYS_TRUE | 77,980 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 20,015,580 | 65.8% |
| POP_JUMP_IF_FALSE | 10,241,500 | 33.7% |
| TO_BOOL_ALWAYS_TRUE | 77,980 | 0.3% |
| TO_BOOL_NONE | 42,800 | 0.1% |
| UNARY_NOT | 20,920 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,710,960 | 63.2% |
| LOAD_FAST | 10,070,300 | 10.7% |
| LOAD_ATTR_SLOT | 8,395,200 | 8.9% |
| COPY | 5,396,660 | 5.7% |
| RETURN_VALUE | 5,335,560 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 67,893,700 | 71.9% |
| POP_JUMP_IF_TRUE | 21,122,620 | 22.4% |
| UNARY_NOT | 3,410,340 | 3.6% |
| EXTENDED_ARG | 2,025,020 | 2.1% |
| TO_BOOL_NONE | 9,340 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,822,340 | 99.6% |
| LOAD_FAST | 27,720 | 0.4% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,840,660 | 99.9% |
| EXTENDED_ARG | 9,300 | 0.1% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 51,740 | 50.4% |
| LOAD_FAST | 37,840 | 36.9% |
| BINARY_SLICE | 10,740 | 10.5% |
| RETURN_VALUE | 1,920 | 1.9% |
| TO_BOOL_NONE | 380 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 77,160 | 75.2% |
| POP_JUMP_IF_FALSE | 25,080 | 24.4% |
| TO_BOOL_NONE | 400 | 0.4% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 10,700,040 | 48.1% |
| LOAD_FAST | 9,625,140 | 43.2% |
| COPY | 1,521,340 | 6.8% |
| LOAD_ATTR_SLOT | 236,480 | 1.1% |
| LOAD_FAST_CHECK | 46,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,506,040 | 74.1% |
| POP_JUMP_IF_TRUE | 5,343,660 | 24.0% |
| EXTENDED_ARG | 338,740 | 1.5% |
| TO_BOOL_ALWAYS_TRUE | 42,760 | 0.2% |
| TO_BOOL_STR | 17,260 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,813,060 | 51.2% |
| LOAD_FAST | 6,177,680 | 46.5% |
| COPY | 172,840 | 1.3% |
| RETURN_VALUE | 104,640 | 0.8% |
| TO_BOOL_NONE | 17,260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 8,229,800 | 61.9% |
| POP_JUMP_IF_FALSE | 5,051,440 | 38.0% |
| TO_BOOL_NONE | 17,220 | 0.1% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 23,153,580 | 90.0% |
| RETURN_VALUE | 2,169,780 | 8.4% |
| LOAD_FAST | 193,680 | 0.8% |
| BUILD_TUPLE | 110,760 | 0.4% |
| STORE_FAST | 89,460 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 25,634,980 | 99.6% |
| STORE_FAST | 89,460 | 0.3% |
| STORE_DEREF | 1,080 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 628,500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 606,900 | 96.6% |
| LOAD_FAST | 11,520 | 1.8% |
| LOAD_CONST | 5,280 | 0.8% |
| ENTER_EXECUTOR | 4,440 | 0.7% |
| JUMP_BACKWARD | 240 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,075,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,075,360 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,423,980 | 35.4% |
| LOAD_FAST | 1,030,020 | 25.6% |
| LOAD_ATTR_SLOT | 831,600 | 20.7% |
| RETURN_VALUE | 732,120 | 18.2% |
| JUMP_FORWARD | 7,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,997,700 | 49.6% |
| LOAD_FAST | 1,093,680 | 27.2% |
| BUILD_STRING | 934,140 | 23.2% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,075,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,075,360 | 100.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,369,780 | 83.3% |
| CALL_KW | 604,740 | 7.9% |
| MAKE_CELL | 569,460 | 7.4% |
| CALL_PY_WITH_DEFAULTS | 40,800 | 0.5% |
| CALL | 35,280 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_YIELD_FROM_ITER | 3,075,360 | 40.2% |
| CALL_TUPLE_1 | 2,966,280 | 38.8% |
| GET_ITER | 628,500 | 8.2% |
| CALL_BUILTIN_CLASS | 446,160 | 5.8% |
| CALL_METHOD_DESCRIPTOR_O | 422,520 | 5.5% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,600 | 86.4% |
| SWAP | 4,680 | 11.0% |
| LOAD_GLOBAL_MODULE | 960 | 2.3% |
| JUMP_FORWARD | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,600 | 86.4% |
| SWAP | 4,680 | 11.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 2.3% |
| LOAD_CONST | 120 | 0.3% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,452,780 | 60.9% |
| FORMAT_SIMPLE | 934,140 | 39.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,424,100 | 59.7% |
| RETURN_VALUE | 920,580 | 38.6% |
| JUMP_FORWARD | 30,720 | 1.3% |
| LOAD_FAST | 7,680 | 0.3% |
| LOAD_FAST_LOAD_FAST | 3,840 | 0.2% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,280 | 100.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,128,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 8,128,020 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 202,080 | 67.5% |
| BINARY_OP_ADD_INT | 72,120 | 24.1% |
| LOAD_FAST | 20,760 | 6.9% |
| CALL_FUNCTION_EX | 3,840 | 1.3% |
| BINARY_SUBSCR_DICT | 600 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 190,180 | 63.5% |
| LOAD_FAST | 96,000 | 32.1% |
| CALL_INTRINSIC_1 | 11,520 | 3.8% |
| JUMP_BACKWARD | 1,700 | 0.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 8,186,520 | 65.5% |
| GET_ITER | 4,304,520 | 34.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 8,186,520 | 65.5% |
| SWAP | 4,304,520 | 34.5% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,194,160 | 96.7% |
| LOAD_FAST | 132,540 | 2.1% |
| JUMP_FORWARD | 76,080 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,275,540 | 98.0% |
| ENTER_EXECUTOR | 127,240 | 2.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,240 | 46.4% |
| RETURN_VALUE | 4,260 | 31.7% |
| LOAD_ATTR_PROPERTY | 2,940 | 21.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,200 | 53.6% |
| JUMP_BACKWARD | 6,240 | 46.4% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 867,600 | 96.4% |
| FOR_ITER_TUPLE | 13,440 | 1.5% |
| YIELD_VALUE | 11,400 | 1.3% |
| FOR_ITER_LIST | 8,000 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 863,880 | 95.9% |
| LOAD_ATTR_PROPERTY | 15,820 | 1.8% |
| TO_BOOL_STR | 11,520 | 1.3% |
| LOAD_FAST | 3,940 | 0.4% |
| POP_JUMP_IF_NOT_NONE | 1,920 | 0.2% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 218,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 218,520 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,128,020 | 40.4% |
| BUILD_TUPLE | 7,273,260 | 36.1% |
| JUMP_FORWARD | 1,826,220 | 9.1% |
| ENTER_EXECUTOR | 1,327,080 | 6.6% |
| RETURN_VALUE | 956,640 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,128,020 | 40.4% |
| INTERPRETER_EXIT | 7,232,760 | 35.9% |
| UNPACK_SEQUENCE_TUPLE | 4,526,400 | 22.5% |
| UNPACK_EX | 218,520 | 1.1% |
| STORE_FAST | 24,360 | 0.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 81,180 | 50.0% |
| LOAD_FAST | 81,180 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 81,180 | 50.0% |
| LOAD_CONST | 81,180 | 50.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,160 | 83.4% |
| LOAD_DEREF | 4,020 | 16.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 20,160 | 83.4% |
| GET_ITER | 4,020 | 16.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 78,240 | 77.3% |
| LOAD_CONST | 23,040 | 22.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 78,240 | 77.3% |
| JUMP_FORWARD | 23,040 | 22.7% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,064,340 | 70.8% |
| RETURN_GENERATOR | 422,520 | 28.1% |
| LOAD_FAST | 16,200 | 1.1% |
| RETURN_VALUE | 720 | 0.0% |
| LOAD_ATTR_PROPERTY | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,077,540 | 71.6% |
| RETURN_VALUE | 407,160 | 27.1% |
| STORE_FAST | 15,360 | 1.0% |
| LOAD_CONST | 3,840 | 0.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,966,280 | 96.3% |
| LOAD_FAST | 73,440 | 2.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 39,540 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 2,493,480 | 81.0% |
| RETURN_VALUE | 431,940 | 14.0% |
| STORE_FAST | 79,800 | 2.6% |
| JUMP_FORWARD | 73,440 | 2.4% |
| CALL_LEN | 600 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,561,200 | 84.3% |
| GET_ITER | 617,460 | 11.4% |
| EXTENDED_ARG | 224,880 | 4.2% |
| LOAD_FAST | 5,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,780,680 | 88.4% |
| POP_TOP | 628,500 | 11.6% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,200 | 87.9% |
| SWAP | 53,520 | 11.8% |
| GET_ITER | 1,560 | 0.3% |
| JUMP_BACKWARD | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 441,120 | 96.8% |
| STORE_FAST_LOAD_FAST | 13,440 | 3.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 720 | 0.2% |
| LOAD_FAST | 120 | 0.0% |
| RETURN_CONST | 80 | 0.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 8,128,020 | 72.5% |
| LOAD_CONST | 3,075,360 | 27.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,128,020 | 72.5% |
| POP_TOP | 3,075,360 | 27.5% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 105,360 | 84.3% |
| LOAD_FAST_LOAD_FAST | 19,560 | 15.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 47,520 | 38.0% |
| BUILD_LIST | 26,400 | 21.1% |
| LOAD_FAST | 24,240 | 19.4% |
| RETURN_CONST | 10,680 | 8.5% |
| LOAD_FAST_LOAD_FAST | 10,560 | 8.5% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,526,400 | 99.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40,800 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,476,240 | 98.0% |
| STORE_FAST_STORE_FAST | 90,960 | 2.0% |


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
|     deferred | 30,560 | 0.1% |
|          hit | 39,648,100 | 99.9% |
|         miss | 180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 6.2% |
| Failure | 300 | 93.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 260 | 86.7% |
| add different types | 20 | 6.7% |
| subtract other | 20 | 6.7% |


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
|     deferred | 1,080,900 | 3.7% |
|        deopt | 520 | 0.0% |
|          hit | 28,120,740 | 96.2% |
|         miss | 28,420 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 58.7% |
| Failure | 380 | 41.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 320 | 84.2% |
| other | 60 | 15.8% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,077,780 | 2.6% |
|        deopt | 54,980 | 0.0% |
|          hit | 220,763,040 | 96.1% |
|         miss | 2,915,100 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 55,640 | 90.3% |
| Failure | 6,000 | 9.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,060 | 34.3% |
| bound method | 1,880 | 31.3% |
| class no vectorcall | 520 | 8.7% |
| no dict | 320 | 5.3% |
| cfunc varargs keywords | 320 | 5.3% |
| cfunc noargs | 320 | 5.3% |
| meth descr varargs | 240 | 4.0% |
| init not python | 180 | 3.0% |
| meth descr varargs keywords | 80 | 1.3% |
| meth descr method fastcall keywords | 40 | 0.7% |
| wrong number arguments | 20 | 0.3% |
| init not simple | 20 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 19,314,960 | 41.0% |
|          hit | 27,740,940 | 58.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.3% |
| Failure | 6,560 | 99.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 5,060 | 77.1% |
| different types | 1,000 | 15.2% |
| other | 220 | 3.4% |
| string | 80 | 1.2% |
| big int | 80 | 1.2% |
| set | 80 | 1.2% |
| bool | 40 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 42,158,460 | 75.5% |
|          hit | 13,682,640 | 24.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.2% |
| Failure | 11,560 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 8,460 | 73.2% |
| dict keys | 760 | 6.6% |
| ascii string | 760 | 6.6% |
| dict values | 520 | 4.5% |
| enumerate | 480 | 4.2% |
| itertools | 240 | 2.1% |
| set | 160 | 1.4% |
| other | 100 | 0.9% |
| reversed list | 80 | 0.7% |


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
|     deferred | 20,441,120 | 5.1% |
|        deopt | 370,520 | 0.1% |
|          hit | 359,812,620 | 90.0% |
|         miss | 19,649,420 | 4.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 371,320 | 95.6% |
| Failure | 16,900 | 4.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 14,160 | 83.8% |
| method | 2,260 | 13.4% |
| mutable class | 380 | 2.2% |
| overridden | 40 | 0.2% |
| class method obj | 40 | 0.2% |
| builtin class method | 20 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 0.0% |
|        deopt | 40 | 0.0% |
|          hit | 207,505,800 | 100.0% |
|         miss | 1,480 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 100.0% |
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
|          hit | 11,203,380 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|        deopt | 128,280 | 0.2% |
|          hit | 63,537,620 | 90.3% |
|         miss | 6,787,000 | 9.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 128,560 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,552,560 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,993,260 | 2.9% |
|        deopt | 217,520 | 0.1% |
|          hit | 155,829,340 | 90.4% |
|         miss | 11,546,540 | 6.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 217,780 | 99.1% |
| Failure | 2,000 | 0.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,020 | 51.0% |
| sequence | 580 | 29.0% |
| dict | 360 | 18.0% |
| set | 20 | 1.0% |
| tuple | 20 | 1.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 96,000 | 0.3% |
|          hit | 30,292,720 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 80 | 100.0% |

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
| Basic | 1,374,832,180 | 44.8% |
| Not specialized | 395,047,180 | 12.9% |
| Specialized | 1,296,032,860 | 42.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 1,475,739,525,896,764,127,220 | 100.0% |
| FOR_ITER | 42,158,460 | 0.0% |
| LOAD_ATTR | 20,441,120 | 0.0% |
| COMPARE_OP | 19,314,960 | 0.0% |
| CALL | 6,077,780 | 0.0% |
| TO_BOOL | 4,993,260 | 0.0% |
| BINARY_SUBSCR | 1,080,900 | 0.0% |
| UNPACK_SEQUENCE | 96,000 | 0.0% |
| BINARY_OP | 30,560 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 11,958,400 | 29.2% |
| STORE_ATTR_SLOT | 6,787,000 | 16.6% |
| TO_BOOL_ALWAYS_TRUE | 6,401,620 | 15.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,823,060 | 9.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,774,060 | 9.2% |
| TO_BOOL_NONE | 3,711,560 | 9.1% |
| CALL_PY_EXACT_ARGS | 1,543,280 | 3.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,323,500 | 3.2% |
| TO_BOOL_STR | 914,600 | 2.2% |
| TO_BOOL_BOOL | 497,580 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 27,297,140 | 18.7% |
| Calls to Python functions inlined | 118,567,580 | 81.3% |
| Calls via PyEval_EvalFrame (total) | 27,297,140 | 18.7% |
| Calls via PyEval_EvalFrame (vector) | 16,119,320 | 11.1% |
| Calls via PyEval_EvalFrame (generator) | 11,177,820 | 7.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 16,119,320 | 11.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,134,160 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 98,880 | 0.1% |
| Calls via PyEval_EvalFrame (api) | 10,384,880 | 7.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 111,300 | 0.1% |
| Frames pushed | 119,441,160 | 81.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 70,093,240 | 32.3% |
| Frees to freelist | 70,170,200 |  |
| Allocations | 147,150,840 | 67.7% |
| Allocations to 512 bytes | 147,037,400 | 67.7% |
| Allocations to 4 kbytes | 113,320 | 0.1% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 148,194,653 |  |
| New values | 1,377,420 |  |
| Interpreter increfs | 1,362,423,640 | 74.5% |
| Interpreter decrefs | 1,514,280,160 | 74.6% |
| Increfs | 467,452,386 | 25.5% |
| Decrefs | 516,066,386 | 25.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 64,186,580 |  |
| Method cache misses | 2,179,580 |  |
| Method cache collisions | 2,349,624 |  |
| Method cache dunder hits | 112,156,537 |  |
| Method cache dunder misses | 171,363 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 3,700 | 1,025,600 | 19,416,080 |
| 1 | 320 | 954,700 | 7,482,480 |
| 2 | 40 | 90,480 | 8,568,080 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,850,780 |  |
| Traces created | 500 | 0.0% |
| Traces executed | 21,355,080 |  |
| Uops executed | 332,943,400 | 15.59 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 20 | 4.0% |
| Trace too short | 1,850,280 | 370,056.0% |
| Inner loop found | 20 | 4.0% |
| Recursive call | 20 | 4.0% |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 120 | 24.0% |
| <= 32 | 80 | 16.0% |
| <= 64 | 160 | 32.0% |
| <= 128 | 140 | 28.0% |


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
| <= 16 | 140 | 28.0% |
| <= 32 | 120 | 24.0% |
| <= 64 | 160 | 32.0% |
| <= 128 | 80 | 16.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 34,560 | 0.2% |
| <= 8 | 7,822,080 | 36.6% |
| <= 16 | 7,797,900 | 36.5% |
| <= 32 | 4,354,540 | 20.4% |
| <= 64 | 1,284,560 | 6.0% |
| <= 128 | 45,000 | 0.2% |
| <= 256 | 15,840 | 0.1% |
| <= 512 | 600 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 94,049,280 | 28.2% | 28.2% |  |
| LOAD_FAST | 51,181,220 | 15.4% | 43.6% |  |
| _GUARD_TYPE_VERSION | 36,982,420 | 11.1% | 54.7% | 0.4% |
| _EXIT_TRACE | 21,084,680 | 6.3% | 61.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 15,107,280 | 4.5% | 65.6% |  |
| _POP_JUMP_IF_TRUE | 12,318,720 | 3.7% | 69.3% |  |
| _LOAD_ATTR_SLOT | 11,981,040 | 3.6% | 72.9% |  |
| STORE_FAST | 8,966,620 | 2.7% | 75.6% |  |
| POP_TOP | 7,912,020 | 2.4% | 78.0% |  |
| _ITER_CHECK_LIST | 7,910,420 | 2.4% | 80.3% |  |
| _IS_ITER_EXHAUSTED_LIST | 7,910,420 | 2.4% | 82.7% |  |
| _POP_JUMP_IF_FALSE | 7,479,760 | 2.2% | 85.0% |  |
| _STORE_ATTR_SLOT | 6,938,520 | 2.1% | 87.0% |  |
| TO_BOOL_STR | 4,869,960 | 1.5% | 88.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,155,880 | 0.9% | 89.5% |  |
| CONTAINS_OP | 2,746,040 | 0.8% | 90.3% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,732,240 | 0.8% | 91.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,056,120 | 0.6% | 91.7% |  |
| _GUARD_GLOBALS_VERSION | 1,809,160 | 0.5% | 92.3% |  |
| _SAVE_CURRENT_IP | 1,762,940 | 0.5% | 92.8% |  |
| TO_BOOL_BOOL | 1,500,720 | 0.5% | 93.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 1,483,500 | 0.4% | 93.7% | 7.9% |
| _CHECK_PEP_523 | 1,483,500 | 0.4% | 94.1% |  |
| _ITER_CHECK_TUPLE | 1,452,580 | 0.4% | 94.6% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 1,452,580 | 0.4% | 95.0% |  |
| _LOAD_GLOBAL_MODULE | 1,370,280 | 0.4% | 95.4% |  |
| _CHECK_STACK_SPACE | 1,366,700 | 0.4% | 95.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 1,366,700 | 0.4% | 96.2% |  |
| _PUSH_FRAME | 1,366,700 | 0.4% | 96.7% |  |
| RESUME_CHECK | 1,334,020 | 0.4% | 97.1% |  |
| BUILD_TUPLE | 1,209,600 | 0.4% | 97.4% |  |
| UNPACK_SEQUENCE_TUPLE | 1,120,980 | 0.3% | 97.8% |  |
| _ITER_NEXT_TUPLE | 997,500 | 0.3% | 98.1% |  |
| COMPARE_OP_STR | 984,240 | 0.3% | 98.3% |  |
| GET_ITER | 940,560 | 0.3% | 98.6% |  |
| LOAD_CONST | 659,080 | 0.2% | 98.8% |  |
| _JUMP_TO_TOP | 518,580 | 0.2% | 99.0% |  |
| _ITER_NEXT_LIST | 510,800 | 0.2% | 99.1% |  |
| _GUARD_BUILTINS_VERSION | 438,880 | 0.1% | 99.3% |  |
| _LOAD_GLOBAL_BUILTINS | 438,880 | 0.1% | 99.4% |  |
| _POP_FRAME | 396,240 | 0.1% | 99.5% |  |
| CALL_ISINSTANCE | 343,760 | 0.1% | 99.6% |  |
| COMPARE_OP_INT | 312,000 | 0.1% | 99.7% |  |
| PUSH_NULL | 194,120 | 0.1% | 99.8% |  |
| BUILD_LIST | 94,400 | 0.0% | 99.8% |  |
| LIST_APPEND | 81,480 | 0.0% | 99.8% |  |
| LOAD_DEREF | 73,460 | 0.0% | 99.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 62,060 | 0.0% | 99.9% |  |
| _GUARD_KEYS_VERSION | 62,060 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 62,060 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 56,640 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 51,540 | 0.0% | 99.9% |  |
| _CHECK_ATTR_MODULE | 23,520 | 0.0% | 99.9% |  |
| _LOAD_ATTR_MODULE | 23,520 | 0.0% | 100.0% |  |
| BUILD_MAP | 22,400 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 15,980 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 15,980 | 0.0% | 100.0% |  |
| DICT_MERGE | 15,300 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 9,840 | 0.0% | 100.0% |  |
| _ITER_CHECK_RANGE | 7,680 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 7,680 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,680 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 7,680 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 7,560 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 6,040 | 0.0% | 100.0% |  |
| IS_OP | 6,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 5,040 | 0.0% | 100.0% |  |
| _IS_NONE | 5,040 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,460 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 2,120 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 1,680 | 0.0% | 100.0% |  |
| TO_BOOL | 1,680 | 0.0% | 100.0% |  |
| COPY | 1,680 | 0.0% | 100.0% |  |
| LOAD_ATTR | 1,680 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 1,160 | 0.0% | 100.0% |  |
| BINARY_OP | 1,060 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 1,569,100 |
| FOR_ITER_GEN | 281,200 |
| LOAD_ATTR_PROPERTY | 220 |
| CALL_KW | 40 |
| CALL | 20 |
| CALL_LIST_APPEND | 20 |
| MAKE_CELL | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |


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
Stats gathered on: 2023-10-09
