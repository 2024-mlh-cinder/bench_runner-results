
# Pystats results

- benchmark: sqlglot
- fork: mdboom
- ref: count-tier2-miss-opcodes
- commit hash: 22212fb
- commit date: 2023-10-09T12:01:25-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 678,320,100 | 21.2% | 21.2% |  |
| LOAD_ATTR_SLOT | 249,093,640 | 7.8% | 29.0% | 4.8% |
| POP_JUMP_IF_FALSE | 168,349,560 | 5.3% | 34.2% |  |
| RESUME_CHECK | 139,582,500 | 4.4% | 38.6% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 132,186,460 | 4.1% | 42.7% | 0.0% |
| STORE_FAST | 102,131,100 | 3.2% | 45.9% |  |
| TO_BOOL_BOOL | 95,961,740 | 3.0% | 48.9% | 0.5% |
| LOAD_ATTR_METHOD_NO_DICT | 91,886,820 | 2.9% | 51.8% | 0.0% |
| STORE_ATTR_SLOT | 77,139,380 | 2.4% | 54.2% | 8.9% |
| LOAD_GLOBAL_MODULE | 77,129,980 | 2.4% | 56.6% |  |
| RETURN_VALUE | 76,717,380 | 2.4% | 59.0% |  |
| CALL_PY_EXACT_ARGS | 70,666,940 | 2.2% | 61.2% | 2.2% |
| CALL_ISINSTANCE | 63,995,340 | 2.0% | 63.2% |  |
| POP_JUMP_IF_TRUE | 58,682,940 | 1.8% | 65.0% |  |
| LOAD_CONST | 58,010,940 | 1.8% | 66.8% |  |
| JUMP_BACKWARD | 53,331,180 | 1.7% | 68.5% |  |
| POP_TOP | 53,275,620 | 1.7% | 70.2% |  |
| LOAD_FAST_LOAD_FAST | 51,043,140 | 1.6% | 71.7% |  |
| RETURN_CONST | 42,723,780 | 1.3% | 73.1% |  |
| FOR_ITER | 42,170,040 | 1.3% | 74.4% |  |
| SWAP | 36,018,720 | 1.1% | 75.5% |  |
| COPY | 35,833,920 | 1.1% | 76.6% |  |
| TO_BOOL_ALWAYS_TRUE | 30,401,920 | 0.9% | 77.6% | 21.1% |
| INTERPRETER_EXIT | 27,297,140 | 0.9% | 78.4% |  |
| STORE_FAST_STORE_FAST | 27,165,900 | 0.8% | 79.3% |  |
| COMPARE_OP_INT | 26,060,160 | 0.8% | 80.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 25,729,980 | 0.8% | 80.9% |  |
| BUILD_TUPLE | 25,168,620 | 0.8% | 81.7% |  |
| BINARY_OP_ADD_INT | 25,026,000 | 0.8% | 82.5% |  |
| GET_ITER | 24,384,540 | 0.8% | 83.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 22,859,320 | 0.7% | 84.0% | 0.0% |
| TO_BOOL_NONE | 22,264,900 | 0.7% | 84.7% | 16.7% |
| BINARY_SUBSCR_STR_INT | 21,565,560 | 0.7% | 85.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 21,235,380 | 0.7% | 86.0% |  |
| LOAD_ATTR | 20,460,520 | 0.6% | 86.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 20,220,600 | 0.6% | 87.3% |  |
| YIELD_VALUE | 20,141,460 | 0.6% | 87.9% |  |
| COMPARE_OP | 19,321,540 | 0.6% | 88.5% |  |
| TO_BOOL_STR | 18,168,420 | 0.6% | 89.1% | 5.0% |
| CALL_PY_WITH_DEFAULTS | 17,496,400 | 0.5% | 89.6% | 0.2% |
| FOR_ITER_LIST | 15,727,980 | 0.5% | 90.1% |  |
| CONTAINS_OP | 15,258,240 | 0.5% | 90.6% |  |
| LOAD_DEREF | 13,878,960 | 0.4% | 91.0% |  |
| BINARY_OP_SUBTRACT_INT | 13,419,900 | 0.4% | 91.4% |  |
| LOAD_ATTR_MODULE | 12,594,940 | 0.4% | 91.8% |  |
| LOAD_FAST_AND_CLEAR | 12,491,040 | 0.4% | 92.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,368,560 | 0.4% | 92.6% | 30.5% |
| CALL_BUILTIN_O | 12,258,240 | 0.4% | 93.0% |  |
| SEND_GEN | 11,203,380 | 0.3% | 93.3% |  |
| EXTENDED_ARG | 10,648,500 | 0.3% | 93.7% |  |
| JUMP_FORWARD | 10,569,780 | 0.3% | 94.0% |  |
| PUSH_NULL | 10,438,920 | 0.3% | 94.3% |  |
| BUILD_LIST | 10,128,180 | 0.3% | 94.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 9,418,680 | 0.3% | 94.9% | 40.6% |
| JUMP_BACKWARD_NO_INTERRUPT | 8,128,020 | 0.3% | 95.2% |  |
| LOAD_ATTR_PROPERTY | 7,951,120 | 0.2% | 95.4% | 0.7% |
| RETURN_GENERATOR | 7,648,920 | 0.2% | 95.7% |  |
| POP_JUMP_IF_NOT_NONE | 7,572,180 | 0.2% | 95.9% |  |
| TO_BOOL_INT | 6,850,080 | 0.2% | 96.1% |  |
| MAP_ADD | 6,402,780 | 0.2% | 96.3% |  |
| CALL | 6,080,360 | 0.2% | 96.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 5,841,600 | 0.2% | 96.7% | 0.6% |
| UNPACK_SEQUENCE_TUPLE | 5,688,180 | 0.2% | 96.9% |  |
| FOR_ITER_GEN | 5,409,180 | 0.2% | 97.0% |  |
| BUILD_MAP | 5,243,880 | 0.2% | 97.2% |  |
| TO_BOOL | 4,996,240 | 0.2% | 97.4% |  |
| CALL_TYPE_1 | 4,830,480 | 0.2% | 97.5% |  |
| NOP | 4,749,960 | 0.1% | 97.7% |  |
| COPY_FREE_VARS | 4,651,560 | 0.1% | 97.8% |  |
| MAKE_FUNCTION | 4,502,280 | 0.1% | 97.9% |  |
| BINARY_SUBSCR_LIST_INT | 4,470,820 | 0.1% | 98.1% | 0.6% |
| FORMAT_SIMPLE | 4,025,520 | 0.1% | 98.2% |  |
| CALL_LIST_APPEND | 3,740,880 | 0.1% | 98.3% |  |
| UNARY_NOT | 3,437,940 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 3,079,260 | 0.1% | 98.5% |  |
| END_SEND | 3,075,360 | 0.1% | 98.6% |  |
| GET_YIELD_FROM_ITER | 3,075,360 | 0.1% | 98.7% |  |
| IS_OP | 3,048,240 | 0.1% | 98.8% |  |
| MAKE_CELL | 3,004,440 | 0.1% | 98.9% |  |
| CALL_BUILTIN_FAST | 2,990,360 | 0.1% | 99.0% | 0.2% |
| COMPARE_OP_STR | 2,977,020 | 0.1% | 99.1% |  |
| BINARY_SLICE | 2,794,920 | 0.1% | 99.2% |  |
| BUILD_STRING | 2,386,920 | 0.1% | 99.3% |  |
| CALL_KW | 2,210,040 | 0.1% | 99.3% |  |
| BINARY_SUBSCR_DICT | 1,986,360 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,919,700 | 0.1% | 99.4% | 69.1% |
| FOR_ITER_TUPLE | 1,908,060 | 0.1% | 99.5% |  |
| STORE_SUBSCR_DICT | 1,562,400 | 0.0% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,560,540 | 0.0% | 99.6% |  |
| POP_JUMP_IF_NONE | 1,447,680 | 0.0% | 99.6% |  |
| CALL_LEN | 1,396,920 | 0.0% | 99.7% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,202,700 | 0.0% | 99.7% |  |
| SET_FUNCTION_ATTRIBUTE | 1,174,260 | 0.0% | 99.8% |  |
| BINARY_SUBSCR | 1,081,300 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 1,045,200 | 0.0% | 99.8% |  |
| CALL_FUNCTION_EX | 985,080 | 0.0% | 99.9% |  |
| DICT_MERGE | 964,140 | 0.0% | 99.9% |  |
| END_FOR | 628,500 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 552,000 | 0.0% | 99.9% |  |
| LIST_APPEND | 380,880 | 0.0% | 99.9% |  |
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
| BINARY_OP | 31,980 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 24,180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 15,600 | 0.0% | 100.0% |  |
| SET_ADD | 13,440 | 0.0% | 100.0% |  |
| DICT_UPDATE | 13,140 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 8,100 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 7,860 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 7,800 | 0.0% | 100.0% | 2.3% |
| IMPORT_NAME | 5,280 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 580 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 203,788,340 | 6.4% | 6.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 104,955,300 | 3.3% | 9.6% |
| LOAD_ATTR_SLOT LOAD_FAST | 97,006,440 | 3.0% | 12.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 80,790,720 | 2.5% | 15.2% |
| RESUME_CHECK LOAD_FAST | 78,671,400 | 2.5% | 17.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 69,175,180 | 2.2% | 19.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 61,789,480 | 1.9% | 21.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 60,054,720 | 1.9% | 23.6% |
| STORE_ATTR_SLOT LOAD_FAST | 53,403,180 | 1.7% | 25.3% |
| LOAD_FAST STORE_ATTR_SLOT | 46,132,700 | 1.4% | 26.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 45,400,580 | 1.4% | 28.1% |
| STORE_FAST LOAD_FAST | 42,481,140 | 1.3% | 29.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 41,202,420 | 1.3% | 30.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 32,565,540 | 1.0% | 31.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 31,623,260 | 1.0% | 32.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 31,235,220 | 1.0% | 33.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 29,888,440 | 0.9% | 34.7% |
| LOAD_FAST COPY | 29,210,040 | 0.9% | 35.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 27,013,020 | 0.8% | 36.4% |
| JUMP_BACKWARD FOR_ITER | 26,259,900 | 0.8% | 37.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 25,639,440 | 0.8% | 38.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 24,737,340 | 0.8% | 38.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 24,087,780 | 0.8% | 39.6% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_NO_DICT | 23,395,860 | 0.7% | 40.3% |
| CACHE RESUME_CHECK | 23,315,240 | 0.7% | 41.0% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 23,153,580 | 0.7% | 41.8% |
| LOAD_FAST BINARY_OP_ADD_INT | 22,664,100 | 0.7% | 42.5% |
| COPY LOAD_ATTR_SLOT | 22,131,480 | 0.7% | 43.2% |
| SWAP STORE_ATTR_SLOT | 22,131,480 | 0.7% | 43.8% |
| BINARY_OP_ADD_INT SWAP | 22,131,480 | 0.7% | 44.5% |
| LOAD_ATTR_SLOT COMPARE_OP_INT | 21,575,580 | 0.7% | 45.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 21,341,860 | 0.7% | 45.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 21,230,940 | 0.7% | 46.5% |
| BINARY_SUBSCR_STR_INT LOAD_FAST | 20,721,660 | 0.6% | 47.2% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 20,016,140 | 0.6% | 47.8% |
| LOAD_FAST RETURN_VALUE | 19,291,020 | 0.6% | 48.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 19,134,740 | 0.6% | 49.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 18,716,960 | 0.6% | 49.6% |
| COMPARE_OP POP_JUMP_IF_FALSE | 17,481,420 | 0.5% | 50.1% |
| RETURN_CONST POP_TOP | 17,179,980 | 0.5% | 50.7% |
| LOAD_ATTR_SLOT LOAD_CONST | 17,173,500 | 0.5% | 51.2% |
| RETURN_VALUE STORE_FAST | 16,935,100 | 0.5% | 51.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 16,886,360 | 0.5% | 52.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 16,576,620 | 0.5% | 52.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 16,505,060 | 0.5% | 53.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 15,679,200 | 0.5% | 53.8% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 15,383,700 | 0.5% | 54.3% |
| POP_TOP LOAD_FAST | 15,204,660 | 0.5% | 54.7% |
| STORE_FAST_STORE_FAST LOAD_FAST | 14,826,840 | 0.5% | 55.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 14,373,660 | 0.4% | 55.7% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 14,354,300 | 0.4% | 56.1% |
| STORE_ATTR_SLOT RETURN_CONST | 13,920,120 | 0.4% | 56.5% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 13,828,300 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 13,817,400 | 0.4% | 57.4% |
| RETURN_VALUE INTERPRETER_EXIT | 13,635,320 | 0.4% | 57.8% |
| LOAD_ATTR_SLOT TO_BOOL_ALWAYS_TRUE | 13,422,560 | 0.4% | 58.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 12,691,380 | 0.4% | 58.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 12,589,520 | 0.4% | 59.0% |
| LOAD_FAST BUILD_TUPLE | 12,584,640 | 0.4% | 59.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS GET_ITER | 12,582,360 | 0.4% | 59.8% |
| JUMP_BACKWARD LOAD_FAST | 12,502,560 | 0.4% | 60.2% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 12,312,720 | 0.4% | 60.6% |
| RESUME_CHECK POP_TOP | 12,013,440 | 0.4% | 61.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 11,846,680 | 0.4% | 61.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_WITH_DEFAULTS | 11,845,420 | 0.4% | 61.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 11,522,100 | 0.4% | 62.1% |
| POP_TOP JUMP_BACKWARD | 11,453,880 | 0.4% | 62.4% |
| LOAD_FAST TO_BOOL_STR | 10,928,600 | 0.3% | 62.8% |
| LOAD_FAST TO_BOOL_BOOL | 10,915,260 | 0.3% | 63.1% |
| RETURN_CONST TO_BOOL_NONE | 10,700,040 | 0.3% | 63.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 10,565,820 | 0.3% | 63.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 10,375,180 | 0.3% | 64.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 10,372,080 | 0.3% | 64.4% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_STR_INT | 10,365,480 | 0.3% | 64.8% |
| COMPARE_OP_INT LOAD_FAST | 10,365,480 | 0.3% | 65.1% |
| RETURN_VALUE RETURN_VALUE | 10,357,560 | 0.3% | 65.4% |
| LOAD_ATTR_SLOT BINARY_SUBSCR_STR_INT | 10,356,180 | 0.3% | 65.7% |
| CALL_BUILTIN_O RETURN_VALUE | 10,327,740 | 0.3% | 66.0% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 10,244,040 | 0.3% | 66.4% |
| LOAD_FAST TO_BOOL_NONE | 9,624,180 | 0.3% | 66.7% |
| LOAD_FAST GET_ITER | 9,558,000 | 0.3% | 67.0% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 9,423,020 | 0.3% | 67.3% |
| LOAD_ATTR_MODULE CALL_ISINSTANCE | 9,206,700 | 0.3% | 67.5% |
| TO_BOOL_STR POP_JUMP_IF_TRUE | 9,192,720 | 0.3% | 67.8% |
| TO_BOOL_STR POP_JUMP_IF_FALSE | 8,958,480 | 0.3% | 68.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 8,930,460 | 0.3% | 68.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 8,720,340 | 0.3% | 68.7% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 8,707,200 | 0.3% | 68.9% |
| LOAD_FAST COMPARE_OP | 8,675,040 | 0.3% | 69.2% |
| LOAD_FAST LOAD_CONST | 8,633,160 | 0.3% | 69.5% |
| GET_ITER FOR_ITER | 8,472,440 | 0.3% | 69.7% |
| LOAD_ATTR COMPARE_OP | 8,444,700 | 0.3% | 70.0% |
| BUILD_TUPLE YIELD_VALUE | 8,394,240 | 0.3% | 70.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT LOAD_ATTR_METHOD_NO_DICT | 8,386,500 | 0.3% | 70.5% |
| LOAD_ATTR_SLOT CALL_METHOD_DESCRIPTOR_FAST | 8,303,280 | 0.3% | 70.8% |
| STORE_FAST STORE_FAST | 8,284,260 | 0.3% | 71.0% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 8,245,440 | 0.3% | 71.3% |
| LOAD_FAST_AND_CLEAR LOAD_FAST_AND_CLEAR | 8,186,520 | 0.3% | 71.6% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 8,128,020 | 0.3% | 71.8% |
| YIELD_VALUE YIELD_VALUE | 8,128,020 | 0.3% | 72.1% |


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
| LOAD_ATTR_SLOT | 358,800 | 29.8% |

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
| JUMP_BACKWARD | 4,680 | 0.7% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |


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

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,582,360 | 51.6% |
| LOAD_FAST | 9,558,000 | 39.2% |
| LOAD_ATTR_SLOT | 883,680 | 3.6% |
| RETURN_GENERATOR | 628,500 | 2.6% |
| BUILD_TUPLE | 387,960 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 8,472,440 | 34.7% |
| FOR_ITER_LIST | 7,591,360 | 31.1% |
| LOAD_FAST_AND_CLEAR | 4,304,520 | 17.7% |
| CALL_PY_EXACT_ARGS | 3,358,560 | 13.8% |
| FOR_ITER_GEN | 617,460 | 2.5% |


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
| LOAD_CONST | 4,502,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,493,480 | 55.4% |
| SET_FUNCTION_ATTRIBUTE | 1,172,460 | 26.0% |
| LOAD_FAST | 836,220 | 18.6% |
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
| RETURN_CONST | 17,179,980 | 32.2% |
| RESUME_CHECK | 12,013,440 | 22.5% |
| POP_JUMP_IF_FALSE | 5,079,540 | 9.5% |
| STORE_FAST | 4,480,260 | 8.4% |
| CACHE | 3,945,060 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,204,660 | 28.5% |
| JUMP_BACKWARD | 11,453,880 | 21.5% |
| RESUME_CHECK | 7,648,920 | 14.4% |
| STORE_FAST | 4,476,240 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 3,539,400 | 6.6% |


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
| LOAD_FAST | 7,000,680 | 67.1% |
| CALL_BUILTIN_FAST | 1,423,980 | 13.6% |
| LOAD_ATTR_MODULE | 1,103,380 | 10.6% |
| LOAD_DEREF | 429,120 | 4.1% |
| LOAD_FAST_LOAD_FAST | 253,500 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,075,500 | 39.0% |
| LOAD_FAST | 3,637,440 | 34.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 940,360 | 9.0% |
| LOAD_CONST | 818,460 | 7.8% |
| CALL_PY_EXACT_ARGS | 784,080 | 7.5% |


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

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,291,020 | 25.1% |
| RETURN_VALUE | 10,357,560 | 13.5% |
| CALL_BUILTIN_O | 10,327,740 | 13.5% |
| BUILD_LIST | 6,094,020 | 7.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,175,040 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,935,100 | 22.1% |
| INTERPRETER_EXIT | 13,635,320 | 17.8% |
| RETURN_VALUE | 10,357,560 | 13.5% |
| MAP_ADD | 6,194,160 | 8.1% |
| LOAD_ATTR_METHOD_NO_DICT | 5,601,240 | 7.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,984,360 | 99.8% |
| COPY | 9,760 | 0.2% |
| TO_BOOL | 1,940 | 0.0% |
| RETURN_CONST | 80 | 0.0% |
| TO_BOOL_NONE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,984,020 | 99.8% |
| POP_JUMP_IF_TRUE | 9,940 | 0.2% |
| TO_BOOL | 1,940 | 0.0% |
| TO_BOOL_NONE | 260 | 0.0% |
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
| RETURN_VALUE | 25,440 | 79.5% |
| LOAD_FAST_LOAD_FAST | 3,360 | 10.5% |
| BUILD_LIST | 1,680 | 5.3% |
| CALL_BUILTIN_CLASS | 1,080 | 3.4% |
| BINARY_OP | 340 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 25,200 | 78.8% |
| GET_ITER | 3,120 | 9.8% |
| LOAD_FAST_LOAD_FAST | 1,680 | 5.3% |
| STORE_FAST | 1,500 | 4.7% |
| BINARY_OP | 340 | 1.1% |


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
| LOAD_FAST | 8,043,540 | 79.4% |
| STORE_FAST | 1,172,760 | 11.6% |
| SWAP | 200,940 | 2.0% |
| RESUME_CHECK | 148,620 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 144,360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,094,020 | 60.2% |
| STORE_FAST | 2,394,660 | 23.6% |
| COMPARE_OP | 882,960 | 8.7% |
| LOAD_FAST | 303,720 | 3.0% |
| SWAP | 200,940 | 2.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,098,900 | 78.2% |
| LOAD_CONST | 860,580 | 16.4% |
| RESUME_CHECK | 69,960 | 1.3% |
| POP_JUMP_IF_NOT_NONE | 55,680 | 1.1% |
| LOAD_FAST | 37,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,098,900 | 78.2% |
| LOAD_FAST | 823,020 | 15.7% |
| STORE_FAST | 141,600 | 2.7% |
| LOAD_DEREF | 74,160 | 1.4% |
| LOAD_GLOBAL_MODULE | 50,160 | 1.0% |


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

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,584,640 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 5,894,340 | 23.4% |
| CALL_TUPLE_1 | 2,493,480 | 9.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,303,520 | 9.2% |
| LOAD_ATTR_MODULE | 540,360 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,394,240 | 33.4% |
| CALL_ISINSTANCE | 6,562,500 | 26.1% |
| CALL_BUILTIN_O | 5,045,160 | 20.0% |
| LOAD_CONST | 1,199,100 | 4.8% |
| CALL_METHOD_DESCRIPTOR_O | 1,120,980 | 4.5% |


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
| DICT_MERGE | 964,140 | 97.9% |
| BUILD_MAP | 11,520 | 1.2% |
| BUILD_CONST_KEY_MAP | 4,080 | 0.4% |
| RETURN_GENERATOR | 4,020 | 0.4% |
| CALL_INTRINSIC_1 | 960 | 0.1% |

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
| LOAD_CONST | 2,210,040 | 100.0% |

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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 6,929,880 | 45.4% |
| LOAD_FAST | 4,226,160 | 27.7% |
| LOAD_FAST_LOAD_FAST | 2,308,680 | 15.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,483,560 | 9.7% |
| BUILD_TUPLE | 265,560 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,691,380 | 83.2% |
| POP_JUMP_IF_TRUE | 1,707,360 | 11.2% |
| STORE_FAST | 859,500 | 5.6% |


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
| TO_BOOL_NONE | 1,522,300 | 4.2% |
| TO_BOOL_STR | 172,840 | 0.5% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,586,980 | 77.1% |
| CALL_PY_EXACT_ARGS | 1,034,900 | 22.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,920 | 0.5% |
| CALL_FUNCTION_EX | 2,880 | 0.1% |
| CALL_PY_WITH_DEFAULTS | 2,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,622,700 | 99.4% |
| RETURN_GENERATOR | 28,860 | 0.6% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 807,000 | 83.7% |
| LOAD_DEREF | 74,160 | 7.7% |
| RETURN_VALUE | 50,160 | 5.2% |
| BUILD_CONST_KEY_MAP | 16,320 | 1.7% |
| DICT_UPDATE | 13,140 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 964,140 | 100.0% |


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

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,202,280 | 67.6% |
| TO_BOOL_BOOL | 2,025,020 | 19.0% |
| JUMP_BACKWARD | 642,120 | 6.0% |
| POP_TOP | 361,200 | 3.4% |
| TO_BOOL_NONE | 338,740 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,571,520 | 71.1% |
| POP_JUMP_IF_FALSE | 2,363,760 | 22.2% |
| FOR_ITER | 440,280 | 4.1% |
| FOR_ITER_GEN | 224,880 | 2.1% |
| JUMP_FORWARD | 23,400 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 26,259,900 | 62.3% |
| GET_ITER | 8,472,440 | 20.1% |
| SWAP | 4,060,200 | 9.6% |
| LOAD_FAST | 2,925,660 | 6.9% |
| EXTENDED_ARG | 440,280 | 1.0% |

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
| CALL_TYPE_1 | 2,253,480 | 73.9% |
| LOAD_FAST_LOAD_FAST | 509,400 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 218,520 | 7.2% |
| LOAD_DEREF | 63,000 | 2.1% |
| LOAD_GLOBAL_MODULE | 3,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,253,480 | 73.9% |
| POP_JUMP_IF_FALSE | 785,040 | 25.8% |
| RETURN_VALUE | 9,720 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,453,880 | 21.5% |
| POP_JUMP_IF_TRUE | 8,095,860 | 15.2% |
| EXTENDED_ARG | 7,571,520 | 14.2% |
| MAP_ADD | 6,402,780 | 12.0% |
| FOR_ITER_LIST | 6,199,860 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 26,259,900 | 49.2% |
| LOAD_FAST | 12,502,560 | 23.4% |
| FOR_ITER_LIST | 7,903,380 | 14.8% |
| FOR_ITER_GEN | 4,561,200 | 8.6% |
| FOR_ITER_TUPLE | 1,452,780 | 2.7% |


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

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,152,820 | 29.8% |
| RETURN_VALUE | 2,878,080 | 27.2% |
| POP_JUMP_IF_FALSE | 1,743,120 | 16.5% |
| STORE_FAST | 1,555,620 | 14.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 337,560 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,268,260 | 30.9% |
| JUMP_BACKWARD | 3,131,220 | 29.6% |
| YIELD_VALUE | 1,826,220 | 17.3% |
| STORE_FAST | 1,596,480 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 276,960 | 2.6% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 272,520 | 71.6% |
| BINARY_OP_ADD_INT | 82,320 | 21.6% |
| LOAD_FAST | 21,600 | 5.7% |
| CALL_FUNCTION_EX | 3,840 | 1.0% |
| BINARY_SUBSCR_DICT | 600 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 273,360 | 71.8% |
| LOAD_FAST | 96,000 | 25.2% |
| CALL_INTRINSIC_1 | 11,520 | 3.0% |


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
| LOAD_ATTR | 20,780 | 0.1% |
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
| LOAD_ATTR_SLOT | 17,173,500 | 29.6% |
| LOAD_FAST | 8,633,160 | 14.9% |
| LOAD_ATTR_METHOD_NO_DICT | 5,397,480 | 9.3% |
| STORE_FAST | 4,349,700 | 7.5% |
| GET_YIELD_FROM_ITER | 3,075,360 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 12,312,720 | 21.2% |
| LOAD_FAST | 6,788,340 | 11.7% |
| STORE_FAST | 5,598,060 | 9.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,891,320 | 8.4% |
| MAKE_FUNCTION | 4,502,280 | 7.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,929,160 | 49.9% |
| POP_JUMP_IF_FALSE | 2,368,080 | 17.1% |
| RESUME_CHECK | 1,756,860 | 12.7% |
| STORE_FAST | 930,720 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 463,200 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,980,160 | 50.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,775,560 | 27.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 764,460 | 5.5% |
| RETURN_VALUE | 435,900 | 3.1% |
| PUSH_NULL | 429,120 | 3.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 104,955,300 | 15.5% |
| LOAD_ATTR_SLOT | 97,006,440 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 80,790,720 | 11.9% |
| RESUME_CHECK | 78,671,400 | 11.6% |
| STORE_ATTR_SLOT | 53,403,180 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 203,788,340 | 30.0% |
| STORE_ATTR_SLOT | 46,132,700 | 6.8% |
| LOAD_ATTR_METHOD_NO_DICT | 45,400,580 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 41,202,420 | 6.1% |
| CALL_PY_EXACT_ARGS | 31,623,260 | 4.7% |


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

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,372,080 | 20.3% |
| POP_JUMP_IF_FALSE | 7,241,580 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 5,980,260 | 11.7% |
| LOAD_GLOBAL_MODULE | 4,865,280 | 9.5% |
| STORE_ATTR_SLOT | 4,237,740 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,817,400 | 27.1% |
| STORE_ATTR_SLOT | 8,720,340 | 17.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,866,260 | 11.5% |
| BINARY_SUBSCR_LIST_INT | 3,303,300 | 6.5% |
| CALL_BUILTIN_FAST | 2,844,960 | 5.6% |


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
| CALL_PY_EXACT_ARGS | 1,443,460 | 48.0% |
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
| JUMP_BACKWARD | 6,402,780 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 69,175,180 | 41.1% |
| COMPARE_OP | 17,481,420 | 10.4% |
| TO_BOOL_NONE | 16,505,060 | 9.8% |
| COMPARE_OP_INT | 15,679,200 | 9.3% |
| CONTAINS_OP | 12,691,380 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 104,955,300 | 62.3% |
| RETURN_CONST | 16,576,620 | 9.8% |
| LOAD_GLOBAL_MODULE | 10,375,180 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 8,930,460 | 5.3% |
| LOAD_FAST_LOAD_FAST | 7,241,580 | 4.3% |


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
| JUMP_BACKWARD | 720 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,543,560 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 18,120 | 0.2% |
| LOAD_ATTR_SLOT | 8,580 | 0.1% |
| STORE_FAST_LOAD_FAST | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,987,340 | 79.1% |
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
| TO_BOOL_BOOL | 21,341,860 | 36.4% |
| TO_BOOL_ALWAYS_TRUE | 20,016,140 | 34.1% |
| TO_BOOL_STR | 9,192,720 | 15.7% |
| TO_BOOL_NONE | 5,344,640 | 9.1% |
| CONTAINS_OP | 1,707,360 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,565,540 | 55.5% |
| JUMP_BACKWARD | 8,095,860 | 13.8% |
| EXTENDED_ARG | 7,202,280 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 3,453,300 | 5.9% |
| STORE_FAST | 3,140,760 | 5.4% |


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
| RETURN_VALUE | 16,935,100 | 16.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 15,383,700 | 15.1% |
| STORE_FAST | 8,284,260 | 8.1% |
| FOR_ITER_LIST | 7,951,020 | 7.8% |
| LOAD_FAST | 7,868,940 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,481,140 | 41.6% |
| LOAD_GLOBAL_BUILTIN | 19,134,740 | 18.7% |
| LOAD_FAST_LOAD_FAST | 10,372,080 | 10.2% |
| STORE_FAST | 8,284,260 | 8.1% |
| POP_TOP | 4,480,260 | 4.4% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 867,600 | 83.0% |
| FOR_ITER_TUPLE | 132,480 | 12.7% |
| FOR_ITER_LIST | 33,720 | 3.2% |
| YIELD_VALUE | 11,400 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 863,880 | 82.7% |
| TO_BOOL_STR | 130,560 | 12.5% |
| LOAD_ATTR_PROPERTY | 35,640 | 3.4% |
| YIELD_VALUE | 6,240 | 0.6% |
| LOAD_FAST | 4,440 | 0.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 25,639,440 | 94.4% |
| UNPACK_SEQUENCE_TUPLE | 1,211,940 | 4.5% |
| UNPACK_EX | 218,520 | 0.8% |
| UNPACK_SEQUENCE | 96,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,826,840 | 54.6% |
| LOAD_GLOBAL_MODULE | 6,182,100 | 22.8% |
| LOAD_GLOBAL_BUILTIN | 4,445,040 | 16.4% |
| STORE_FAST | 1,211,940 | 4.5% |
| LOAD_FAST_LOAD_FAST | 499,980 | 1.8% |


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

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 8,394,240 | 41.7% |
| YIELD_VALUE | 8,128,020 | 40.4% |
| JUMP_FORWARD | 1,826,220 | 9.1% |
| RETURN_VALUE | 956,640 | 4.7% |
| LOAD_FAST | 816,420 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,128,020 | 40.4% |
| INTERPRETER_EXIT | 7,232,760 | 35.9% |
| UNPACK_SEQUENCE_TUPLE | 4,526,400 | 22.5% |
| UNPACK_EX | 218,520 | 1.1% |
| STORE_FAST | 24,360 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,664,100 | 90.6% |
| LOAD_CONST | 2,279,340 | 9.1% |
| LOAD_FAST_LOAD_FAST | 82,320 | 0.3% |
| RETURN_VALUE | 120 | 0.0% |
| RETURN_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 22,131,480 | 88.4% |
| STORE_FAST | 1,697,040 | 6.8% |
| CALL_PY_EXACT_ARGS | 1,088,520 | 4.3% |
| LIST_APPEND | 82,320 | 0.3% |
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
| LOAD_FAST_LOAD_FAST | 847,740 | 42.7% |
| LOAD_ATTR_SLOT | 595,140 | 30.0% |
| LOAD_CONST | 357,840 | 18.0% |
| CALL_BUILTIN_O | 105,360 | 5.3% |
| LOAD_FAST | 36,480 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,230,780 | 62.0% |
| BUILD_TUPLE | 254,760 | 12.8% |
| LOAD_FAST_LOAD_FAST | 156,420 | 7.9% |
| RETURN_VALUE | 100,200 | 5.0% |
| PUSH_EXC_INFO | 83,280 | 4.2% |


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

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 940,360 | 49.0% |
| LOAD_FAST | 892,000 | 46.5% |
| LOAD_ATTR_SLOT | 54,600 | 2.8% |
| CALL_PY_EXACT_ARGS | 25,020 | 1.3% |
| LOAD_ATTR | 7,680 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,699,140 | 88.5% |
| MAKE_CELL | 171,620 | 8.9% |
| CALL_PY_EXACT_ARGS | 25,020 | 1.3% |
| COPY_FREE_VARS | 23,920 | 1.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 446,160 | 80.8% |
| BINARY_SLICE | 39,540 | 7.2% |
| CALL_BUILTIN_FAST | 35,760 | 6.5% |
| LOAD_FAST | 11,240 | 2.0% |
| LOAD_ATTR | 7,800 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 230,280 | 41.7% |
| JUMP_FORWARD | 193,680 | 35.1% |
| GET_ITER | 50,280 | 9.1% |
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

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,282,580 | 43.1% |
| BUILD_TUPLE | 5,045,160 | 41.2% |
| LOAD_FAST | 1,915,380 | 15.6% |
| RETURN_VALUE | 14,040 | 0.1% |
| RETURN_GENERATOR | 1,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,327,740 | 84.3% |
| TO_BOOL_BOOL | 1,428,900 | 11.7% |
| STORE_FAST | 267,960 | 2.2% |
| STORE_SUBSCR_DICT | 110,880 | 0.9% |
| BINARY_SUBSCR_DICT | 105,360 | 0.9% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,087,780 | 37.6% |
| LOAD_GLOBAL_MODULE | 14,373,660 | 22.5% |
| LOAD_ATTR_MODULE | 9,206,700 | 14.4% |
| LOAD_ATTR_SLOT | 7,586,880 | 11.9% |
| BUILD_TUPLE | 6,562,500 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60,054,720 | 93.8% |
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
| LOAD_FAST | 2,641,800 | 70.6% |
| CALL | 1,079,240 | 28.8% |
| RETURN_VALUE | 13,120 | 0.4% |
| BUILD_TUPLE | 6,720 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,711,500 | 45.8% |
| LOAD_FAST_LOAD_FAST | 1,709,220 | 45.7% |
| LOAD_FAST | 264,480 | 7.1% |
| RETURN_CONST | 51,240 | 1.4% |
| EXTENDED_ARG | 4,440 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 8,303,280 | 36.3% |
| LOAD_CONST | 4,891,320 | 21.4% |
| LOAD_FAST | 4,837,200 | 21.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,887,460 | 17.0% |
| LOAD_ATTR | 642,900 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,383,700 | 67.3% |
| RETURN_VALUE | 4,175,040 | 18.3% |
| CALL_PY_WITH_DEFAULTS | 2,622,420 | 11.5% |
| TO_BOOL_BOOL | 537,240 | 2.4% |
| LOAD_GLOBAL_MODULE | 63,000 | 0.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 21,230,940 | 100.0% |
| LOAD_FAST | 4,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,582,360 | 59.3% |
| BUILD_TUPLE | 2,303,520 | 10.8% |
| CALL_PY_EXACT_ARGS | 1,915,320 | 9.0% |
| UNPACK_SEQUENCE_TUPLE | 1,161,780 | 5.5% |
| TO_BOOL_BOOL | 1,094,820 | 5.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,120,980 | 71.8% |
| RETURN_GENERATOR | 422,520 | 27.1% |
| LOAD_FAST | 16,200 | 1.0% |
| RETURN_VALUE | 720 | 0.0% |
| LOAD_ATTR_PROPERTY | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,134,180 | 72.7% |
| RETURN_VALUE | 407,160 | 26.1% |
| STORE_FAST | 15,360 | 1.0% |
| LOAD_CONST | 3,840 | 0.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,623,260 | 44.7% |
| LOAD_ATTR | 8,245,440 | 11.7% |
| LOAD_ATTR_METHOD_NO_DICT | 5,883,240 | 8.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,617,040 | 5.1% |
| LOAD_CONST | 3,495,900 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 61,789,480 | 87.4% |
| RETURN_GENERATOR | 6,369,780 | 9.0% |
| MAKE_CELL | 1,443,460 | 2.0% |
| COPY_FREE_VARS | 1,034,900 | 1.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 25,020 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 11,845,420 | 67.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,622,420 | 15.0% |
| LOAD_FAST | 1,401,520 | 8.0% |
| LOAD_ATTR | 650,280 | 3.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 577,260 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,886,360 | 96.5% |
| MAKE_CELL | 565,560 | 3.2% |
| RETURN_GENERATOR | 40,800 | 0.2% |
| COPY_FREE_VARS | 2,880 | 0.0% |
| CALL_PY_EXACT_ARGS | 800 | 0.0% |


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
| LOAD_ATTR_SLOT | 21,575,580 | 82.8% |
| LOAD_CONST | 4,341,180 | 16.7% |
| CALL_LEN | 52,900 | 0.2% |
| LOAD_FAST | 46,920 | 0.2% |
| LOAD_DEREF | 20,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,679,200 | 60.2% |
| LOAD_FAST | 10,365,480 | 39.8% |
| POP_JUMP_IF_TRUE | 15,480 | 0.1% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,477,020 | 49.6% |
| LOAD_CONST | 505,440 | 17.0% |
| RETURN_VALUE | 470,760 | 15.8% |
| LOAD_FAST | 452,400 | 15.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 62,400 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,504,940 | 84.1% |
| RETURN_VALUE | 439,080 | 14.7% |
| COPY | 30,840 | 1.0% |
| POP_JUMP_IF_TRUE | 2,160 | 0.1% |


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

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,903,380 | 50.3% |
| GET_ITER | 7,591,360 | 48.3% |
| SWAP | 190,800 | 1.2% |
| LOAD_FAST | 27,060 | 0.2% |
| EXTENDED_ARG | 15,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,951,020 | 50.6% |
| JUMP_BACKWARD | 6,199,860 | 39.4% |
| LOAD_FAST | 1,357,500 | 8.6% |
| SWAP | 112,320 | 0.7% |
| RETURN_CONST | 45,600 | 0.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,860 | 97.0% |
| GET_ITER | 240 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,860 | 97.0% |
| LOAD_FAST | 240 | 3.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,452,780 | 76.1% |
| LOAD_FAST | 400,200 | 21.0% |
| SWAP | 53,520 | 2.8% |
| GET_ITER | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,333,560 | 69.9% |
| RETURN_CONST | 400,200 | 21.0% |
| STORE_FAST_LOAD_FAST | 132,480 | 6.9% |
| SWAP | 39,540 | 2.1% |
| LOAD_FAST | 1,560 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,594,940 | 95.8% |
| LOAD_FAST_LOAD_FAST | 246,000 | 4.2% |
| LOAD_ATTR_INSTANCE_VALUE | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 5,282,580 | 90.4% |
| IS_OP | 218,520 | 3.7% |
| RETURN_VALUE | 81,720 | 1.4% |
| LOAD_ATTR_METHOD_NO_DICT | 63,360 | 1.1% |
| LOAD_FAST | 42,720 | 0.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,400,580 | 49.4% |
| LOAD_ATTR_SLOT | 23,395,860 | 25.5% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 8,386,500 | 9.1% |
| RETURN_VALUE | 5,601,240 | 6.1% |
| LOAD_DEREF | 3,775,560 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,235,220 | 34.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 21,230,940 | 23.1% |
| CALL_PY_WITH_DEFAULTS | 11,845,420 | 12.9% |
| LOAD_GLOBAL_MODULE | 10,565,820 | 11.5% |
| CALL_PY_EXACT_ARGS | 5,883,240 | 6.4% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,522,100 | 93.2% |
| LOAD_DEREF | 764,460 | 6.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 71,080 | 0.6% |
| CALL_FUNCTION_EX | 3,840 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,051,020 | 32.8% |
| CALL_PY_EXACT_ARGS | 3,617,040 | 29.2% |
| LOAD_FAST_LOAD_FAST | 3,102,360 | 25.1% |
| LOAD_CONST | 884,280 | 7.1% |
| CALL_PY_WITH_DEFAULTS | 577,260 | 4.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,589,520 | 100.0% |
| LOAD_FAST | 5,280 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 9,206,700 | 73.1% |
| PUSH_NULL | 1,103,380 | 8.8% |
| LOAD_GLOBAL_MODULE | 927,960 | 7.4% |
| BUILD_TUPLE | 540,360 | 4.3% |
| LOAD_FAST | 324,480 | 2.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,354,300 | 71.0% |
| LOAD_FAST_LOAD_FAST | 5,866,260 | 29.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 8,386,500 | 41.5% |
| CONTAINS_OP | 6,929,880 | 34.3% |
| CALL_PY_EXACT_ARGS | 3,269,240 | 16.2% |
| STORE_FAST | 1,071,420 | 5.3% |
| LOAD_FAST | 454,320 | 2.2% |


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
| LOAD_FAST | 7,801,380 | 98.1% |
| LOAD_FAST_LOAD_FAST | 63,720 | 0.8% |
| STORE_FAST_LOAD_FAST | 35,640 | 0.4% |
| BINARY_SUBSCR_DICT | 24,480 | 0.3% |
| LOAD_ATTR_SLOT | 11,640 | 0.1% |

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
| LOAD_FAST | 203,788,340 | 81.8% |
| COPY | 22,131,480 | 8.9% |
| LOAD_ATTR_SLOT | 13,828,300 | 5.6% |
| LOAD_DEREF | 6,980,160 | 2.8% |
| LOAD_FAST_LOAD_FAST | 2,359,800 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,006,440 | 38.9% |
| LOAD_ATTR_METHOD_NO_DICT | 23,395,860 | 9.4% |
| COMPARE_OP_INT | 21,575,580 | 8.7% |
| LOAD_CONST | 17,173,500 | 6.9% |
| LOAD_ATTR_SLOT | 13,828,300 | 5.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,202,420 | 31.2% |
| RESUME_CHECK | 27,013,020 | 20.4% |
| STORE_FAST | 19,134,740 | 14.5% |
| LOAD_GLOBAL_BUILTIN | 11,846,680 | 9.0% |
| POP_JUMP_IF_FALSE | 8,930,460 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,790,720 | 61.1% |
| CALL_ISINSTANCE | 24,087,780 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 11,846,680 | 9.0% |
| LOAD_FAST_LOAD_FAST | 5,980,260 | 4.5% |
| BUILD_TUPLE | 5,894,340 | 4.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,888,440 | 38.8% |
| LOAD_ATTR_METHOD_NO_DICT | 10,565,820 | 13.7% |
| POP_JUMP_IF_FALSE | 10,375,180 | 13.5% |
| STORE_FAST_STORE_FAST | 6,182,100 | 8.0% |
| STORE_FAST | 3,867,080 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,737,340 | 32.1% |
| LOAD_ATTR | 18,716,960 | 24.3% |
| CALL_ISINSTANCE | 14,373,660 | 18.6% |
| LOAD_ATTR_MODULE | 12,589,520 | 16.3% |
| LOAD_FAST_LOAD_FAST | 4,865,280 | 6.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 61,789,480 | 44.3% |
| CACHE | 23,315,240 | 16.7% |
| CALL_PY_WITH_DEFAULTS | 16,886,360 | 12.1% |
| SEND_GEN | 8,128,020 | 5.8% |
| LOAD_ATTR_PROPERTY | 7,892,920 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,671,400 | 56.4% |
| LOAD_GLOBAL_BUILTIN | 27,013,020 | 19.4% |
| POP_TOP | 12,013,440 | 8.6% |
| JUMP_BACKWARD_NO_INTERRUPT | 8,128,020 | 5.8% |
| NOP | 4,021,020 | 2.9% |


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

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,132,700 | 59.8% |
| SWAP | 22,131,480 | 28.7% |
| LOAD_FAST_LOAD_FAST | 8,720,340 | 11.3% |
| STORE_ATTR_SLOT | 129,440 | 0.2% |
| LOAD_DEREF | 25,140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,403,180 | 69.2% |
| RETURN_CONST | 13,920,120 | 18.0% |
| LOAD_FAST_LOAD_FAST | 4,237,740 | 5.5% |
| JUMP_BACKWARD | 2,039,040 | 2.6% |
| LOAD_CONST | 1,522,560 | 2.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,322,400 | 84.6% |
| CALL_BUILTIN_O | 110,880 | 7.1% |
| RETURN_VALUE | 106,200 | 6.8% |
| LOAD_FAST_LOAD_FAST | 22,920 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,303,560 | 83.4% |
| LOAD_GLOBAL_MODULE | 105,360 | 6.7% |
| LOAD_FAST | 97,440 | 6.2% |
| POP_EXCEPT | 55,680 | 3.6% |
| EXTENDED_ARG | 360 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,422,560 | 44.2% |
| LOAD_FAST | 9,423,020 | 31.0% |
| COPY | 6,549,140 | 21.5% |
| STORE_FAST_LOAD_FAST | 863,880 | 2.8% |
| TO_BOOL_ALWAYS_TRUE | 78,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 20,016,140 | 65.8% |
| POP_JUMP_IF_FALSE | 10,244,040 | 33.7% |
| TO_BOOL_ALWAYS_TRUE | 78,040 | 0.3% |
| TO_BOOL_NONE | 42,780 | 0.1% |
| UNARY_NOT | 20,920 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 60,054,720 | 62.6% |
| LOAD_FAST | 10,915,260 | 11.4% |
| LOAD_ATTR_SLOT | 8,707,200 | 9.1% |
| COPY | 5,396,660 | 5.6% |
| RETURN_VALUE | 5,335,560 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 69,175,180 | 72.1% |
| POP_JUMP_IF_TRUE | 21,341,860 | 22.2% |
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
| LOAD_FAST | 9,624,180 | 43.2% |
| COPY | 1,522,300 | 6.8% |
| LOAD_ATTR_SLOT | 236,480 | 1.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 46,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,505,060 | 74.1% |
| POP_JUMP_IF_TRUE | 5,344,640 | 24.0% |
| EXTENDED_ARG | 338,740 | 1.5% |
| TO_BOOL_ALWAYS_TRUE | 42,760 | 0.2% |
| TO_BOOL_STR | 17,260 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,928,600 | 60.2% |
| LOAD_ATTR_SLOT | 6,813,060 | 37.5% |
| COPY | 172,840 | 1.0% |
| STORE_FAST_LOAD_FAST | 130,560 | 0.7% |
| RETURN_VALUE | 104,640 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,192,720 | 50.6% |
| POP_JUMP_IF_FALSE | 8,958,480 | 49.3% |
| TO_BOOL_NONE | 17,220 | 0.1% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,526,400 | 79.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,161,780 | 20.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,476,240 | 78.7% |
| STORE_FAST_STORE_FAST | 1,211,940 | 21.3% |


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
| STORE_FAST_STORE_FAST | 25,639,440 | 99.6% |
| STORE_FAST | 89,460 | 0.3% |
| STORE_DEREF | 1,080 | 0.0% |


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
| JUMP_BACKWARD | 13,440 | 100.0% |


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


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,620 | 0.1% |
|          hit | 39,664,080 | 99.9% |
|         miss | 180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 5.6% |
| Failure | 340 | 94.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 300 | 88.2% |
| add different types | 20 | 5.9% |
| subtract other | 20 | 5.9% |


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
|          hit | 28,172,280 | 96.2% |
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
|     deferred | 6,075,060 | 2.6% |
|        deopt | 55,260 | 0.0% |
|          hit | 227,729,660 | 96.2% |
|         miss | 2,928,740 | 1.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 55,920 | 92.3% |
| Failure | 4,640 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,060 | 44.4% |
| bound method | 520 | 11.2% |
| class no vectorcall | 520 | 11.2% |
| no dict | 320 | 6.9% |
| cfunc varargs keywords | 320 | 6.9% |
| cfunc noargs | 320 | 6.9% |
| meth descr varargs | 240 | 5.2% |
| init not python | 180 | 3.9% |
| meth descr varargs keywords | 80 | 1.7% |
| meth descr method fastcall keywords | 40 | 0.9% |
| wrong number arguments | 20 | 0.4% |
| init not simple | 20 | 0.4% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 19,314,960 | 39.9% |
|          hit | 29,037,180 | 60.0% |

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
|     deferred | 42,158,460 | 64.6% |
|          hit | 23,053,320 | 35.3% |

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
|     deferred | 20,442,800 | 4.8% |
|        deopt | 370,620 | 0.1% |
|          hit | 389,721,240 | 90.7% |
|         miss | 19,654,720 | 4.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 371,420 | 95.6% |
| Failure | 16,920 | 4.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 14,160 | 83.7% |
| method | 2,260 | 13.4% |
| mutable class | 380 | 2.2% |
| overridden | 40 | 0.2% |
| builtin class method | 40 | 0.2% |
| class method obj | 40 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 0.0% |
|        deopt | 40 | 0.0% |
|          hit | 209,314,960 | 100.0% |
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
|        deopt | 129,440 | 0.2% |
|          hit | 70,414,300 | 91.1% |
|         miss | 6,850,000 | 8.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 129,720 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,562,400 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,993,960 | 2.8% |
|        deopt | 217,560 | 0.1% |
|          hit | 162,201,520 | 90.7% |
|         miss | 11,548,180 | 6.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 217,840 | 99.1% |
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
|          hit | 31,418,160 | 99.7% |

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
| Basic | 1,413,504,320 | 44.1% |
| Not specialized | 427,431,180 | 13.3% |
| Specialized | 1,361,177,880 | 42.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 1,475,739,525,896,764,127,200 | 100.0% |
| FOR_ITER | 42,158,460 | 0.0% |
| LOAD_ATTR | 20,442,800 | 0.0% |
| COMPARE_OP | 19,314,960 | 0.0% |
| CALL | 6,075,060 | 0.0% |
| TO_BOOL | 4,993,960 | 0.0% |
| BINARY_SUBSCR | 1,080,900 | 0.0% |
| UNPACK_SEQUENCE | 96,000 | 0.0% |
| BINARY_OP | 31,620 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 11,963,220 | 29.2% |
| STORE_ATTR_SLOT | 6,850,000 | 16.7% |
| TO_BOOL_ALWAYS_TRUE | 6,403,500 | 15.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,823,060 | 9.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,774,540 | 9.2% |
| TO_BOOL_NONE | 3,711,320 | 9.0% |
| CALL_PY_EXACT_ARGS | 1,553,560 | 3.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,326,860 | 3.2% |
| TO_BOOL_STR | 914,600 | 2.2% |
| TO_BOOL_BOOL | 497,580 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 27,297,140 | 18.5% |
| Calls to Python functions inlined | 119,934,280 | 81.5% |
| Calls via PyEval_EvalFrame (total) | 27,297,140 | 18.5% |
| Calls via PyEval_EvalFrame (vector) | 16,119,320 | 10.9% |
| Calls via PyEval_EvalFrame (generator) | 11,177,820 | 7.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 16,119,320 | 10.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,134,160 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 98,880 | 0.1% |
| Calls via PyEval_EvalFrame (api) | 10,384,880 | 7.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 111,300 | 0.1% |
| Frames pushed | 119,441,160 | 81.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 70,093,240 | 32.3% |
| Frees to freelist | 70,170,200 |  |
| Allocations | 147,150,340 | 67.7% |
| Allocations to 512 bytes | 147,037,180 | 67.7% |
| Allocations to 4 kbytes | 113,040 | 0.1% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 148,194,532 |  |
| New values | 1,377,420 |  |
| Interpreter increfs | 1,412,150,480 | 78.1% |
| Interpreter decrefs | 1,574,290,480 | 78.3% |
| Increfs | 396,898,239 | 21.9% |
| Decrefs | 435,229,283 | 21.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 63,882,226 |  |
| Method cache misses | 2,552,274 |  |
| Method cache collisions | 2,733,702 |  |
| Method cache dunder hits | 112,145,349 |  |
| Method cache dunder misses | 182,551 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 3,700 | 1,025,860 | 19,416,520 |
| 1 | 320 | 954,700 | 7,481,200 |
| 2 | 40 | 90,480 | 8,567,520 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
