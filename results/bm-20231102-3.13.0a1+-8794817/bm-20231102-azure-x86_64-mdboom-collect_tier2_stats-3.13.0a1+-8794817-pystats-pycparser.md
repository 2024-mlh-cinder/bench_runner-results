
# Pystats results

- benchmark: pycparser
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,274,348,740 | 28.5% | 28.5% |  |
| LOAD_CONST | 599,857,100 | 7.5% | 36.0% |  |
| STORE_FAST | 510,156,600 | 6.4% | 42.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 412,095,120 | 5.2% | 47.5% | 2.7% |
| POP_JUMP_IF_FALSE | 282,106,180 | 3.5% | 51.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 261,257,280 | 3.3% | 54.3% | 0.0% |
| RESUME_CHECK | 211,586,000 | 2.6% | 56.9% | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 192,431,600 | 2.4% | 59.3% |  |
| LOAD_FAST_LOAD_FAST | 162,710,700 | 2.0% | 61.4% |  |
| COMPARE_OP_INT | 157,640,800 | 2.0% | 63.4% |  |
| BINARY_SUBSCR_LIST_INT | 150,428,580 | 1.9% | 65.2% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 146,087,300 | 1.8% | 67.1% | 0.0% |
| UNARY_NEGATIVE | 139,642,020 | 1.7% | 68.8% |  |
| POP_JUMP_IF_TRUE | 135,640,560 | 1.7% | 70.5% |  |
| BINARY_SUBSCR_DICT | 126,029,940 | 1.6% | 72.1% |  |
| RETURN_VALUE | 118,987,840 | 1.5% | 73.6% |  |
| CALL | 109,170,240 | 1.4% | 74.9% |  |
| EXTENDED_ARG | 103,916,200 | 1.3% | 76.2% |  |
| CALL_LIST_APPEND | 94,016,380 | 1.2% | 77.4% |  |
| RETURN_CONST | 92,602,540 | 1.2% | 78.6% |  |
| ENTER_EXECUTOR | 87,798,100 | 1.1% | 79.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 71,540,440 | 0.9% | 80.6% |  |
| LOAD_GLOBAL_MODULE | 71,198,880 | 0.9% | 81.5% | 0.0% |
| BUILD_SLICE | 69,806,780 | 0.9% | 82.3% |  |
| DELETE_SUBSCR | 69,798,760 | 0.9% | 83.2% |  |
| TO_BOOL_BOOL | 65,601,500 | 0.8% | 84.0% | 0.0% |
| CALL_PY_EXACT_ARGS | 63,978,660 | 0.8% | 84.8% | 31.4% |
| TO_BOOL_ALWAYS_TRUE | 62,816,300 | 0.8% | 85.6% | 27.9% |
| INTERPRETER_EXIT | 61,279,260 | 0.8% | 86.4% |  |
| JUMP_FORWARD | 58,129,160 | 0.7% | 87.1% |  |
| POP_TOP | 55,934,080 | 0.7% | 87.8% |  |
| CALL_ISINSTANCE | 54,434,460 | 0.7% | 88.5% |  |
| STORE_ATTR_SLOT | 48,108,800 | 0.6% | 89.1% | 1.1% |
| TO_BOOL_NONE | 47,478,000 | 0.6% | 89.7% | 46.8% |
| BINARY_SUBSCR_GETITEM | 47,369,400 | 0.6% | 90.3% |  |
| POP_JUMP_IF_NONE | 46,184,880 | 0.6% | 90.9% |  |
| TO_BOOL_INT | 46,114,180 | 0.6% | 91.4% | 0.0% |
| LOAD_ATTR_WITH_HINT | 45,331,880 | 0.6% | 92.0% | 0.3% |
| BINARY_OP_SUBTRACT_INT | 40,196,280 | 0.5% | 92.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 37,594,140 | 0.5% | 93.0% | 50.9% |
| BINARY_SUBSCR | 36,710,440 | 0.5% | 93.4% |  |
| STORE_SUBSCR | 35,761,540 | 0.4% | 93.9% |  |
| NOP | 35,759,880 | 0.4% | 94.3% |  |
| BINARY_SLICE | 35,534,160 | 0.4% | 94.8% |  |
| STORE_SUBSCR_LIST_INT | 34,914,380 | 0.4% | 95.2% |  |
| LOAD_ATTR | 34,266,360 | 0.4% | 95.6% |  |
| PUSH_NULL | 28,190,120 | 0.4% | 96.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 27,215,460 | 0.3% | 96.3% | 0.0% |
| CALL_LEN | 22,235,420 | 0.3% | 96.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 20,212,400 | 0.3% | 96.9% |  |
| LOAD_ATTR_MODULE | 18,081,200 | 0.2% | 97.1% | 0.0% |
| CALL_BUILTIN_FAST | 16,473,700 | 0.2% | 97.3% | 0.0% |
| SWAP | 16,275,780 | 0.2% | 97.5% |  |
| GET_ITER | 14,123,740 | 0.2% | 97.7% |  |
| STORE_FAST_LOAD_FAST | 13,964,520 | 0.2% | 97.8% |  |
| CONTAINS_OP | 13,304,160 | 0.2% | 98.0% |  |
| BINARY_OP_ADD_INT | 12,835,280 | 0.2% | 98.2% |  |
| LOAD_ATTR_SLOT | 11,854,380 | 0.1% | 98.3% | 24.9% |
| CALL_KW | 11,793,080 | 0.1% | 98.5% |  |
| TO_BOOL_LIST | 11,722,420 | 0.1% | 98.6% | 0.0% |
| STORE_ATTR_WITH_HINT | 10,701,900 | 0.1% | 98.8% | 0.0% |
| FOR_ITER_LIST | 10,582,260 | 0.1% | 98.9% | 0.0% |
| BINARY_SUBSCR_STR_INT | 10,423,780 | 0.1% | 99.0% | 0.0% |
| FOR_ITER | 9,631,720 | 0.1% | 99.1% |  |
| POP_JUMP_IF_NOT_NONE | 9,478,180 | 0.1% | 99.3% |  |
| BUILD_LIST | 9,226,980 | 0.1% | 99.4% |  |
| STORE_FAST_STORE_FAST | 7,690,720 | 0.1% | 99.5% |  |
| JUMP_BACKWARD | 6,104,980 | 0.1% | 99.5% |  |
| TO_BOOL_STR | 5,419,500 | 0.1% | 99.6% | 0.1% |
| COMPARE_OP_STR | 4,453,120 | 0.1% | 99.7% | 0.0% |
| TO_BOOL | 4,083,040 | 0.1% | 99.7% |  |
| COPY | 3,514,800 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 3,387,860 | 0.0% | 99.8% |  |
| BINARY_OP | 1,799,880 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 1,672,100 | 0.0% | 99.8% |  |
| LOAD_NAME | 1,611,220 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 1,563,400 | 0.0% | 99.9% |  |
| LOAD_DEREF | 1,456,160 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 1,455,840 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 1,113,780 | 0.0% | 99.9% |  |
| LIST_APPEND | 938,960 | 0.0% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 897,380 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 783,520 | 0.0% | 100.0% |  |
| COMPARE_OP | 551,360 | 0.0% | 100.0% |  |
| STORE_NAME | 532,580 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 257,780 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 240,620 | 0.0% | 100.0% | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 130,900 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 121,960 | 0.0% | 100.0% |  |
| IS_OP | 94,620 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 94,260 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 87,840 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 87,840 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 74,920 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 49,340 | 0.0% | 100.0% |  |
| BUILD_STRING | 43,920 | 0.0% | 100.0% |  |
| CALL_STR_1 | 40,660 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 21,000 | 0.0% | 100.0% |  |
| STORE_ATTR | 20,120 | 0.0% | 100.0% |  |
| BUILD_MAP | 19,320 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 18,720 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 17,840 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 16,800 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 10,920 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 10,800 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 9,980 | 0.0% | 100.0% |  |
| UNARY_NOT | 8,600 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 8,560 | 0.0% | 100.0% |  |
| LIST_EXTEND | 7,220 | 0.0% | 100.0% |  |
| RESUME | 5,580 | 0.0% | 100.0% | 63.8% |
| MAKE_FUNCTION | 5,160 | 0.0% | 100.0% |  |
| UNARY_INVERT | 4,160 | 0.0% | 100.0% |  |
| MAP_ADD | 3,400 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 3,360 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 3,360 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,820 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 2,280 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,520 | 0.0% | 100.0% | 7.9% |
| STORE_GLOBAL | 960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 640 | 0.0% | 100.0% |  |
| BEFORE_WITH | 600 | 0.0% | 100.0% |  |
| IMPORT_NAME | 480 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 400 | 0.0% | 100.0% |  |
| POP_EXCEPT | 400 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 400 | 0.0% | 100.0% |  |
| DICT_MERGE | 360 | 0.0% | 100.0% |  |
| YIELD_VALUE | 320 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 320 | 0.0% | 100.0% |  |
| DICT_UPDATE | 200 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 160 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 120 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 120 | 0.0% | 100.0% |  |
| MAKE_CELL | 80 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| DELETE_NAME | 40 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_FAST | 368,629,260 | 4.6% | 4.6% |
| STORE_FAST LOAD_FAST | 367,336,040 | 4.6% | 9.2% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 321,041,620 | 4.0% | 13.2% |
| LOAD_FAST LOAD_CONST | 320,747,500 | 4.0% | 17.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 251,168,840 | 3.1% | 20.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 177,778,840 | 2.2% | 22.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 160,209,420 | 2.0% | 24.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 150,274,300 | 1.9% | 26.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 149,742,780 | 1.9% | 28.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 146,181,300 | 1.8% | 30.2% |
| LOAD_CONST COMPARE_OP_INT | 145,381,180 | 1.8% | 32.0% |
| LOAD_FAST UNARY_NEGATIVE | 139,642,020 | 1.7% | 33.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 132,564,180 | 1.7% | 35.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 125,317,360 | 1.6% | 37.0% |
| UNARY_NEGATIVE LOAD_CONST | 104,698,080 | 1.3% | 38.3% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 99,728,960 | 1.2% | 39.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 96,763,940 | 1.2% | 40.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 94,623,580 | 1.2% | 41.9% |
| LOAD_FAST CALL_LIST_APPEND | 93,074,520 | 1.2% | 43.1% |
| CALL STORE_FAST | 90,464,840 | 1.1% | 44.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 88,532,160 | 1.1% | 45.3% |
| LOAD_FAST BINARY_SUBSCR_DICT | 81,290,160 | 1.0% | 46.4% |
| LOAD_CONST BUILD_SLICE | 69,806,780 | 0.9% | 47.2% |
| DELETE_SUBSCR LOAD_FAST | 69,798,720 | 0.9% | 48.1% |
| BUILD_SLICE DELETE_SUBSCR | 69,798,720 | 0.9% | 49.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 62,896,780 | 0.8% | 49.8% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 62,365,020 | 0.8% | 50.5% |
| CACHE RESUME_CHECK | 61,286,880 | 0.8% | 51.3% |
| RESUME_CHECK LOAD_FAST | 58,554,060 | 0.7% | 52.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 58,383,960 | 0.7% | 52.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 56,585,920 | 0.7% | 53.5% |
| JUMP_FORWARD LOAD_FAST | 55,850,980 | 0.7% | 54.2% |
| STORE_FAST JUMP_FORWARD | 55,633,500 | 0.7% | 54.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 54,392,800 | 0.7% | 55.6% |
| RETURN_VALUE LOAD_FAST | 53,787,600 | 0.7% | 56.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 52,379,600 | 0.7% | 56.9% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 50,968,140 | 0.6% | 57.5% |
| RETURN_CONST INTERPRETER_EXIT | 50,367,520 | 0.6% | 58.1% |
| LOAD_CONST LOAD_FAST | 49,080,840 | 0.6% | 58.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 48,122,700 | 0.6% | 59.4% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 47,610,460 | 0.6% | 60.0% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 47,407,520 | 0.6% | 60.6% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 47,369,400 | 0.6% | 61.1% |
| LOAD_CONST BINARY_SUBSCR_GETITEM | 47,353,340 | 0.6% | 61.7% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_INSTANCE_VALUE | 47,352,760 | 0.6% | 62.3% |
| LOAD_GLOBAL_MODULE CALL | 47,213,040 | 0.6% | 62.9% |
| CALL_LIST_APPEND LOAD_FAST | 46,819,340 | 0.6% | 63.5% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 46,474,980 | 0.6% | 64.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 46,150,880 | 0.6% | 64.7% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 46,092,560 | 0.6% | 65.2% |
| LOAD_FAST TO_BOOL_INT | 46,084,680 | 0.6% | 65.8% |
| BINARY_SUBSCR_DICT LOAD_ATTR_METHOD_NO_DICT | 46,024,440 | 0.6% | 66.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 45,480,360 | 0.6% | 67.0% |
| EXTENDED_ARG POP_JUMP_IF_NONE | 45,317,680 | 0.6% | 67.5% |
| LOAD_FAST EXTENDED_ARG | 45,317,680 | 0.6% | 68.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 43,194,180 | 0.5% | 68.6% |
| RETURN_CONST POP_TOP | 39,145,520 | 0.5% | 69.1% |
| BINARY_SUBSCR_DICT LOAD_FAST | 38,522,220 | 0.5% | 69.6% |
| EXTENDED_ARG ENTER_EXECUTOR | 38,251,900 | 0.5% | 70.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 37,970,820 | 0.5% | 70.6% |
| POP_TOP LOAD_FAST | 37,581,500 | 0.5% | 71.0% |
| BINARY_SUBSCR_DICT STORE_FAST | 36,833,840 | 0.5% | 71.5% |
| LOAD_CONST BINARY_SUBSCR | 36,688,480 | 0.5% | 72.0% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 36,477,580 | 0.5% | 72.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 36,400,180 | 0.5% | 72.9% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 36,337,920 | 0.5% | 73.3% |
| CALL_LIST_APPEND EXTENDED_ARG | 36,315,080 | 0.5% | 73.8% |
| BINARY_SUBSCR_LIST_INT STORE_ATTR_INSTANCE_VALUE | 36,129,520 | 0.5% | 74.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 35,783,280 | 0.4% | 74.7% |
| NOP LOAD_FAST | 35,749,620 | 0.4% | 75.1% |
| LOAD_CONST STORE_SUBSCR | 35,697,940 | 0.4% | 75.6% |
| BINARY_SUBSCR BINARY_SUBSCR_DICT | 35,692,480 | 0.4% | 76.0% |
| STORE_ATTR_INSTANCE_VALUE NOP | 35,691,440 | 0.4% | 76.5% |
| LOAD_CONST BINARY_SLICE | 35,530,620 | 0.4% | 76.9% |
| STORE_SUBSCR RETURN_CONST | 35,259,660 | 0.4% | 77.3% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 34,977,300 | 0.4% | 77.8% |
| UNARY_NEGATIVE BINARY_SUBSCR_LIST_INT | 34,943,080 | 0.4% | 78.2% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 34,914,980 | 0.4% | 78.7% |
| BINARY_OP_SUBTRACT_INT LOAD_CONST | 34,909,520 | 0.4% | 79.1% |
| BINARY_SLICE STORE_FAST | 34,902,500 | 0.4% | 79.5% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 34,899,660 | 0.4% | 80.0% |
| LOAD_CONST STORE_SUBSCR_LIST_INT | 34,899,320 | 0.4% | 80.4% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 34,649,360 | 0.4% | 80.8% |
| LOAD_FAST TO_BOOL_NONE | 34,619,940 | 0.4% | 81.3% |
| ENTER_EXECUTOR TO_BOOL_ALWAYS_TRUE | 34,608,760 | 0.4% | 81.7% |
| LOAD_FAST LOAD_ATTR | 33,980,060 | 0.4% | 82.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,438,160 | 0.4% | 82.5% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 30,350,540 | 0.4% | 82.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 29,983,540 | 0.4% | 83.3% |
| ENTER_EXECUTOR CALL | 29,960,520 | 0.4% | 83.7% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 27,603,620 | 0.3% | 84.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 26,488,040 | 0.3% | 84.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 24,992,720 | 0.3% | 84.7% |
| LOAD_CONST LOAD_CONST | 24,339,820 | 0.3% | 85.0% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 23,428,200 | 0.3% | 85.3% |
| RETURN_VALUE STORE_FAST | 19,660,580 | 0.2% | 85.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 18,073,640 | 0.2% | 85.7% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 18,021,640 | 0.2% | 86.0% |
| LOAD_FAST PUSH_NULL | 17,423,340 | 0.2% | 86.2% |
| CALL LOAD_FAST | 16,979,920 | 0.2% | 86.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 35,530,620 | 100.0% |
| LOAD_FAST | 3,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,902,500 | 98.2% |
| GET_ITER | 540,640 | 1.5% |
| LOAD_CONST | 55,780 | 0.2% |
| CALL_METHOD_DESCRIPTOR_O | 18,440 | 0.1% |
| LOAD_FAST | 7,040 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 61,286,880 | 100.0% |
| RESUME | 1,800 | 0.0% |
| POP_TOP | 160 | 0.0% |
| COPY_FREE_VARS | 120 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 260 | 43.3% |
| CALL | 180 | 30.0% |
| RETURN_VALUE | 80 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 320 | 53.3% |
| STORE_FAST | 280 | 46.7% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,800 | 76.2% |
| BINARY_SUBSCR_STR_INT | 2,360 | 14.0% |
| LOAD_FAST_LOAD_FAST | 1,400 | 8.3% |
| BINARY_OP_ADD_UNICODE | 240 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 14,200 | 84.5% |
| LOAD_FAST | 2,360 | 14.0% |
| JUMP_BACKWARD | 240 | 1.4% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,688,480 | 99.9% |
| BINARY_SUBSCR | 11,040 | 0.0% |
| BUILD_SLICE | 8,060 | 0.0% |
| LOAD_FAST | 2,420 | 0.0% |
| LOAD_FAST_LOAD_FAST | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 35,692,480 | 97.2% |
| LOAD_FAST | 485,680 | 1.3% |
| LOAD_ATTR_METHOD_NO_DICT | 478,320 | 1.3% |
| STORE_FAST | 17,500 | 0.0% |
| BINARY_SUBSCR | 11,040 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 400 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 69,798,720 | 100.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,798,720 | 100.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,360 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 87,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 84,480 | 96.2% |
| BUILD_STRING | 3,360 | 3.8% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,424,160 | 52.6% |
| CALL_BUILTIN_CLASS | 2,964,600 | 21.0% |
| LOAD_FAST | 2,307,440 | 16.3% |
| LOAD_ATTR_SLOT | 868,920 | 6.2% |
| BINARY_SLICE | 540,640 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 8,000,180 | 56.6% |
| FOR_ITER | 3,510,940 | 24.9% |
| FOR_ITER_LIST | 1,748,000 | 12.4% |
| LOAD_FAST_AND_CLEAR | 837,060 | 5.9% |
| FOR_ITER_TUPLE | 18,400 | 0.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 50,367,520 | 82.2% |
| RETURN_VALUE | 10,911,420 | 17.8% |
| YIELD_VALUE | 320 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,360 | 65.1% |
| LOAD_CONST | 1,680 | 32.6% |
| SET_FUNCTION_ATTRIBUTE | 120 | 2.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 35,691,440 | 99.8% |
| STORE_FAST | 49,960 | 0.1% |
| POP_JUMP_IF_FALSE | 7,600 | 0.0% |
| NOP | 2,980 | 0.0% |
| STORE_FAST_STORE_FAST | 2,980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,749,620 | 100.0% |
| NOP | 2,980 | 0.0% |
| LOAD_GLOBAL_MODULE | 2,560 | 0.0% |
| LOAD_FAST_LOAD_FAST | 2,440 | 0.0% |
| LOAD_CONST | 1,280 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 160 | 40.0% |
| STORE_ATTR_INSTANCE_VALUE | 160 | 40.0% |
| STORE_FAST | 80 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 160 | 40.0% |
| RETURN_CONST | 160 | 40.0% |
| ENTER_EXECUTOR | 80 | 20.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 39,145,520 | 70.0% |
| SWAP | 12,172,360 | 21.8% |
| STORE_FAST | 1,875,120 | 3.4% |
| POP_JUMP_IF_TRUE | 1,344,480 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,068,160 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,581,500 | 67.2% |
| RETURN_VALUE | 12,172,440 | 21.8% |
| RETURN_CONST | 2,629,520 | 4.7% |
| EXTENDED_ARG | 1,895,220 | 3.4% |
| LOAD_GLOBAL_BUILTIN | 846,760 | 1.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 240 | 60.0% |
| BINARY_SUBSCR_STR_INT | 160 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,423,340 | 61.8% |
| LOAD_ATTR_MODULE | 9,299,800 | 33.0% |
| LOAD_DEREF | 1,455,760 | 5.2% |
| STORE_FAST_LOAD_FAST | 5,720 | 0.0% |
| LOAD_NAME | 3,940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,961,020 | 53.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,387,680 | 36.8% |
| LOAD_FAST_LOAD_FAST | 1,461,520 | 5.2% |
| LOAD_CONST | 1,289,380 | 4.6% |
| LOAD_GLOBAL_BUILTIN | 46,720 | 0.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| CALL_PY_WITH_DEFAULTS | 60 | 37.5% |
| CALL | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 75.0% |
| CALL_BUILTIN_CLASS | 40 | 25.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 47,407,520 | 39.8% |
| CALL_BUILTIN_FAST | 16,202,040 | 13.6% |
| POP_TOP | 12,172,440 | 10.2% |
| LOAD_FAST | 10,964,740 | 9.2% |
| CALL_LEN | 10,811,840 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,787,600 | 45.2% |
| STORE_FAST | 19,660,580 | 16.5% |
| INTERPRETER_EXIT | 10,911,420 | 9.2% |
| CALL | 8,213,620 | 6.9% |
| LOAD_CONST | 6,212,640 | 5.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 35,697,940 | 99.8% |
| STORE_SUBSCR | 30,060 | 0.1% |
| ENTER_EXECUTOR | 22,380 | 0.1% |
| LOAD_FAST_LOAD_FAST | 8,740 | 0.0% |
| LOAD_FAST | 2,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 35,259,660 | 98.6% |
| LOAD_FAST | 438,180 | 1.2% |
| STORE_SUBSCR | 30,060 | 0.1% |
| ENTER_EXECUTOR | 24,160 | 0.1% |
| JUMP_FORWARD | 7,000 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,896,060 | 95.4% |
| TO_BOOL_NONE | 89,040 | 2.2% |
| TO_BOOL | 80,160 | 2.0% |
| ENTER_EXECUTOR | 8,080 | 0.2% |
| COPY | 6,300 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,898,100 | 95.5% |
| TO_BOOL_NONE | 89,300 | 2.2% |
| TO_BOOL | 80,160 | 2.0% |
| POP_JUMP_IF_FALSE | 13,640 | 0.3% |
| TO_BOOL_BOOL | 1,100 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,160 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,642,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 104,698,080 | 75.0% |
| BINARY_SUBSCR_LIST_INT | 34,943,080 | 25.0% |
| CALL_BUILTIN_CLASS | 820 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 8,440 | 98.1% |
| TO_BOOL_LIST | 160 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,320 | 50.2% |
| STORE_FAST | 4,120 | 47.9% |
| CALL_PY_EXACT_ARGS | 160 | 1.9% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,085,600 | 60.3% |
| RETURN_VALUE | 541,760 | 30.1% |
| POP_JUMP_IF_TRUE | 105,360 | 5.9% |
| LOAD_GLOBAL_MODULE | 24,600 | 1.4% |
| BUILD_LIST | 23,600 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 678,600 | 37.7% |
| LOAD_CONST | 540,860 | 30.0% |
| BINARY_OP_ADD_UNICODE | 540,700 | 30.0% |
| TO_BOOL_INT | 26,980 | 1.5% |
| STORE_FAST | 5,160 | 0.3% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 121,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,760 | 99.8% |
| STORE_NAME | 80 | 0.1% |
| RETURN_VALUE | 40 | 0.0% |
| DICT_UPDATE | 40 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 2,543,520 | 27.6% |
| RETURN_VALUE | 2,393,680 | 25.9% |
| LOAD_GLOBAL_BUILTIN | 846,380 | 9.2% |
| SWAP | 837,060 | 9.1% |
| LOAD_FAST | 811,520 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 2,543,520 | 27.6% |
| LOAD_FAST | 2,392,960 | 25.9% |
| LOAD_CONST | 1,445,800 | 15.7% |
| STORE_FAST | 1,438,920 | 15.6% |
| SWAP | 837,060 | 9.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,820 | 71.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,180 | 16.5% |
| FOR_ITER | 480 | 2.5% |
| LOAD_CONST | 480 | 2.5% |
| LOAD_FAST | 320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 13,820 | 71.5% |
| LOAD_FAST | 5,000 | 25.9% |
| STORE_FAST | 240 | 1.2% |
| LOAD_CONST | 120 | 0.6% |
| EXTENDED_ARG | 80 | 0.4% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 69,806,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 69,798,720 | 100.0% |
| BINARY_SUBSCR | 8,060 | 0.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,560 | 92.3% |
| FORMAT_SIMPLE | 3,360 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40,560 | 92.3% |
| LOAD_FAST | 3,360 | 7.7% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,251,800 | 80.1% |
| CALL_BUILTIN_FAST | 83,800 | 5.4% |
| LOAD_ATTR | 81,220 | 5.2% |
| BINARY_SUBSCR_TUPLE_INT | 46,520 | 3.0% |
| LOAD_FAST_LOAD_FAST | 41,160 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,285,700 | 82.2% |
| LIST_APPEND | 83,840 | 5.4% |
| CALL_LIST_APPEND | 73,120 | 4.7% |
| RETURN_VALUE | 63,340 | 4.1% |
| STORE_FAST | 17,000 | 1.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 47,213,040 | 43.2% |
| ENTER_EXECUTOR | 29,960,520 | 27.4% |
| LOAD_ATTR_METHOD_NO_DICT | 12,249,680 | 11.2% |
| RETURN_VALUE | 8,213,620 | 7.5% |
| LOAD_FAST_LOAD_FAST | 7,420,800 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 90,464,840 | 82.9% |
| LOAD_FAST | 16,979,920 | 15.6% |
| BINARY_OP_ADD_INT | 1,592,840 | 1.5% |
| TO_BOOL_BOOL | 54,320 | 0.0% |
| CALL | 36,200 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,620 | 91.6% |
| ENTER_EXECUTOR | 5,860 | 7.8% |
| DICT_MERGE | 360 | 0.5% |
| CALL_INTRINSIC_1 | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 74,360 | 99.3% |
| RESUME_CHECK | 320 | 0.4% |
| RETURN_VALUE | 80 | 0.1% |
| COPY_FREE_VARS | 80 | 0.1% |
| CALL | 40 | 0.1% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 66.7% |
| BUILD_MAP | 40 | 33.3% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,793,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,290,080 | 44.9% |
| LOAD_FAST | 2,801,440 | 23.8% |
| STORE_FAST | 2,277,240 | 19.3% |
| RESUME_CHECK | 1,140,220 | 9.7% |
| BUILD_LIST | 216,960 | 1.8% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 541,680 | 98.2% |
| LOAD_GLOBAL_MODULE | 5,740 | 1.0% |
| LOAD_CONST | 2,400 | 0.4% |
| LOAD_FAST | 920 | 0.2% |
| COMPARE_OP | 460 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 546,720 | 99.2% |
| POP_JUMP_IF_TRUE | 2,820 | 0.5% |
| COMPARE_OP_INT | 960 | 0.2% |
| COMPARE_OP | 460 | 0.1% |
| COMPARE_OP_STR | 380 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,396,240 | 78.1% |
| LOAD_CONST | 1,666,980 | 12.5% |
| BINARY_SUBSCR_DICT | 754,660 | 5.7% |
| LOAD_NAME | 261,960 | 2.0% |
| LOAD_ATTR_INSTANCE_VALUE | 131,400 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,679,640 | 87.8% |
| POP_JUMP_IF_TRUE | 1,002,880 | 7.5% |
| STORE_FAST | 599,880 | 4.5% |
| EXTENDED_ARG | 20,300 | 0.2% |
| RETURN_VALUE | 1,460 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,280 | 53.8% |
| LOAD_ATTR_INSTANCE_VALUE | 40,540 | 46.2% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 87,840 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,605,880 | 45.7% |
| LOAD_FAST | 1,027,200 | 29.2% |
| RETURN_VALUE | 746,140 | 21.2% |
| LOAD_CONST | 75,220 | 2.1% |
| CALL_BUILTIN_FAST | 40,540 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,592,840 | 45.3% |
| TO_BOOL_NONE | 1,496,800 | 42.6% |
| TO_BOOL_ALWAYS_TRUE | 153,160 | 4.4% |
| TO_BOOL_LIST | 123,900 | 3.5% |
| LOAD_FAST | 65,360 | 1.9% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 754,180 | 51.8% |
| CALL_PY_EXACT_ARGS | 701,420 | 48.2% |
| CACHE | 120 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,455,720 | 100.0% |
| RETURN_GENERATOR | 80 | 0.0% |
| RESUME | 40 | 0.0% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 20 | 50.0% |
| BUILD_MAP | 20 | 50.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 360 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 160 | 80.0% |
| BUILD_CONST_KEY_MAP | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 120 | 60.0% |
| STORE_NAME | 40 | 20.0% |
| BUILD_LIST | 20 | 10.0% |
| EXTENDED_ARG | 20 | 10.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 38,251,900 | 43.6% |
| POP_JUMP_IF_TRUE | 24,992,720 | 28.5% |
| POP_JUMP_IF_FALSE | 11,208,680 | 12.8% |
| STORE_FAST | 11,198,140 | 12.8% |
| LIST_APPEND | 919,120 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 34,608,760 | 39.4% |
| CALL | 29,960,520 | 34.1% |
| TO_BOOL_NONE | 10,382,060 | 11.8% |
| LOAD_FAST | 10,068,060 | 11.5% |
| ENTER_EXECUTOR | 887,080 | 1.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,317,680 | 43.6% |
| CALL_LIST_APPEND | 36,315,080 | 34.9% |
| COMPARE_OP_INT | 10,374,860 | 10.0% |
| GET_ITER | 8,000,180 | 7.7% |
| POP_TOP | 1,895,220 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 45,317,680 | 43.6% |
| ENTER_EXECUTOR | 38,251,900 | 36.8% |
| POP_JUMP_IF_FALSE | 10,422,660 | 10.0% |
| FOR_ITER_LIST | 7,993,000 | 7.7% |
| JUMP_FORWARD | 1,899,060 | 1.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,091,540 | 63.2% |
| GET_ITER | 3,510,940 | 36.5% |
| EXTENDED_ARG | 22,700 | 0.2% |
| FOR_ITER | 4,680 | 0.0% |
| ENTER_EXECUTOR | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,370,600 | 76.5% |
| RETURN_CONST | 1,187,920 | 12.3% |
| LOAD_CONST | 540,640 | 5.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 483,000 | 5.0% |
| STORE_FAST_LOAD_FAST | 38,000 | 0.4% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 480 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 93,940 | 99.3% |
| LOAD_CONST | 320 | 0.3% |
| LOAD_FAST | 200 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 81,600 | 86.2% |
| POP_JUMP_IF_TRUE | 12,700 | 13.4% |
| COPY | 320 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 4,771,760 | 78.2% |
| POP_JUMP_IF_TRUE | 972,780 | 15.9% |
| STORE_SUBSCR_DICT | 267,760 | 4.4% |
| CALL_LIST_APPEND | 43,180 | 0.7% |
| LIST_APPEND | 19,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 6,091,540 | 99.8% |
| FOR_ITER_LIST | 5,440 | 0.1% |
| EXTENDED_ARG | 3,180 | 0.1% |
| FOR_ITER_TUPLE | 1,500 | 0.0% |
| NOP | 960 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 55,633,500 | 95.7% |
| EXTENDED_ARG | 1,899,060 | 3.3% |
| RETURN_VALUE | 496,640 | 0.9% |
| POP_TOP | 83,460 | 0.1% |
| STORE_SUBSCR | 7,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,850,980 | 96.1% |
| LOAD_FAST_LOAD_FAST | 2,004,080 | 3.4% |
| STORE_FAST | 109,840 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 65,680 | 0.1% |
| LOAD_CONST | 43,440 | 0.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 835,040 | 88.9% |
| BUILD_TUPLE | 83,840 | 8.9% |
| LOAD_FAST | 18,480 | 2.0% |
| CALL_BUILTIN_CLASS | 820 | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 520 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 919,120 | 97.9% |
| JUMP_BACKWARD | 19,840 | 2.1% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,100 | 98.3% |
| LOAD_DEREF | 80 | 1.1% |
| LOAD_FAST | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 3,480 | 48.2% |
| BUILD_LIST | 3,360 | 46.5% |
| STORE_FAST | 240 | 3.3% |
| CALL_INTRINSIC_1 | 120 | 1.7% |
| STORE_NAME | 20 | 0.3% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,980,060 | 99.2% |
| LOAD_GLOBAL_MODULE | 124,580 | 0.4% |
| LOAD_ATTR | 71,460 | 0.2% |
| LOAD_FAST_LOAD_FAST | 41,480 | 0.1% |
| ENTER_EXECUTOR | 33,040 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,488,000 | 45.2% |
| STORE_FAST | 12,297,520 | 35.9% |
| LOAD_ATTR_METHOD_NO_DICT | 3,976,900 | 11.6% |
| LOAD_FAST_LOAD_FAST | 867,320 | 2.5% |
| LOAD_CONST | 700,500 | 2.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,747,500 | 53.5% |
| UNARY_NEGATIVE | 104,698,080 | 17.5% |
| STORE_ATTR_INSTANCE_VALUE | 35,783,280 | 6.0% |
| BINARY_OP_SUBTRACT_INT | 34,909,520 | 5.8% |
| LOAD_CONST | 24,339,820 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 145,381,180 | 24.2% |
| BUILD_SLICE | 69,806,780 | 11.6% |
| LOAD_FAST | 49,080,840 | 8.2% |
| BINARY_SUBSCR_GETITEM | 47,353,340 | 7.9% |
| BINARY_SUBSCR | 36,688,480 | 6.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,455,600 | 100.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |
| BINARY_SLICE | 80 | 0.0% |
| NOP | 80 | 0.0% |
| BUILD_LIST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,455,760 | 100.0% |
| LOAD_FAST | 160 | 0.0% |
| LIST_EXTEND | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 368,629,260 | 16.2% |
| STORE_FAST | 367,336,040 | 16.2% |
| POP_JUMP_IF_FALSE | 251,168,840 | 11.0% |
| LOAD_ATTR_METHOD_NO_DICT | 150,274,300 | 6.6% |
| LOAD_ATTR_INSTANCE_VALUE | 149,742,780 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 368,629,260 | 16.2% |
| LOAD_ATTR_INSTANCE_VALUE | 321,041,620 | 14.1% |
| LOAD_CONST | 320,747,500 | 14.1% |
| STORE_ATTR_INSTANCE_VALUE | 177,778,840 | 7.8% |
| UNARY_NEGATIVE | 139,642,020 | 6.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 837,060 | 50.1% |
| LOAD_FAST_AND_CLEAR | 835,040 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 837,060 | 50.1% |
| LOAD_FAST_AND_CLEAR | 835,040 | 49.9% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 18,480 | 98.7% |
| POP_TOP | 160 | 0.9% |
| LOAD_FAST | 40 | 0.2% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,480 | 98.7% |
| POP_JUMP_IF_NOT_NONE | 160 | 0.9% |
| LOAD_FAST | 40 | 0.2% |
| CALL_LIST_APPEND | 40 | 0.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 50,968,140 | 31.3% |
| STORE_ATTR_SLOT | 30,350,540 | 18.7% |
| STORE_FAST | 29,983,540 | 18.4% |
| STORE_ATTR_INSTANCE_VALUE | 26,488,040 | 16.3% |
| POP_JUMP_IF_FALSE | 12,316,540 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 45,480,360 | 28.0% |
| LOAD_ATTR_INSTANCE_VALUE | 36,337,920 | 22.3% |
| STORE_ATTR_INSTANCE_VALUE | 33,438,160 | 20.6% |
| COMPARE_OP_INT | 12,249,920 | 7.5% |
| BINARY_SUBSCR_LIST_INT | 12,249,400 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600 | 14.7% |
| RESUME | 1,500 | 13.7% |
| RESUME_CHECK | 1,500 | 13.7% |
| POP_JUMP_IF_FALSE | 1,480 | 13.6% |
| LOAD_FAST | 1,060 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,080 | 28.2% |
| LOAD_GLOBAL_BUILTIN | 2,440 | 22.3% |
| LOAD_ATTR | 2,380 | 21.8% |
| LOAD_FAST | 2,180 | 20.0% |
| CALL | 360 | 3.3% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 799,700 | 49.6% |
| STORE_NAME | 265,940 | 16.5% |
| BINARY_SUBSCR_DICT | 261,920 | 16.3% |
| POP_JUMP_IF_FALSE | 248,140 | 15.4% |
| BUILD_MAP | 13,820 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 799,700 | 49.6% |
| STORE_SUBSCR_DICT | 275,620 | 17.1% |
| CONTAINS_OP | 261,960 | 16.3% |
| BINARY_SUBSCR_DICT | 261,880 | 16.3% |
| LOAD_CONST | 7,840 | 0.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 100.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 3,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,800 | 52.9% |
| EXTENDED_ARG | 1,400 | 41.2% |
| DICT_UPDATE | 160 | 4.7% |
| BUILD_MAP | 40 | 1.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 146,181,300 | 51.8% |
| TO_BOOL_BOOL | 56,585,920 | 20.1% |
| TO_BOOL_INT | 46,092,560 | 16.3% |
| CONTAINS_OP | 11,679,640 | 4.1% |
| EXTENDED_ARG | 10,422,660 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 251,168,840 | 89.0% |
| LOAD_FAST_LOAD_FAST | 12,316,540 | 4.4% |
| ENTER_EXECUTOR | 11,208,680 | 4.0% |
| LOAD_GLOBAL_MODULE | 2,305,580 | 0.8% |
| LOAD_CONST | 2,113,320 | 0.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 45,317,680 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 599,820 | 1.3% |
| RETURN_VALUE | 120,980 | 0.3% |
| LOAD_ATTR_WITH_HINT | 65,340 | 0.1% |
| LOAD_ATTR_SLOT | 49,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,150,880 | 99.9% |
| LOAD_FAST_LOAD_FAST | 16,920 | 0.0% |
| LOAD_CONST | 9,860 | 0.0% |
| ENTER_EXECUTOR | 3,840 | 0.0% |
| EXTENDED_ARG | 1,920 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,598,540 | 69.6% |
| BINARY_SUBSCR_DICT | 1,162,280 | 12.3% |
| RETURN_VALUE | 856,120 | 9.0% |
| LOAD_ATTR_SLOT | 562,140 | 5.9% |
| LOAD_ATTR_WITH_HINT | 216,820 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,771,760 | 50.3% |
| LOAD_FAST | 3,999,360 | 42.2% |
| LOAD_GLOBAL_BUILTIN | 663,360 | 7.0% |
| RETURN_CONST | 21,080 | 0.2% |
| LOAD_GLOBAL_MODULE | 9,880 | 0.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 62,365,020 | 46.0% |
| TO_BOOL_NONE | 46,474,980 | 34.3% |
| TO_BOOL_LIST | 11,711,360 | 8.6% |
| TO_BOOL_BOOL | 9,002,560 | 6.6% |
| TO_BOOL | 3,898,100 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,623,580 | 69.8% |
| ENTER_EXECUTOR | 24,992,720 | 18.4% |
| LOAD_GLOBAL_MODULE | 13,091,920 | 9.7% |
| POP_TOP | 1,344,480 | 1.0% |
| JUMP_BACKWARD | 972,780 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 37,970,820 | 41.0% |
| STORE_SUBSCR | 35,259,660 | 38.1% |
| STORE_ATTR_SLOT | 14,583,500 | 15.7% |
| POP_TOP | 2,629,520 | 2.8% |
| FOR_ITER | 1,187,920 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 50,367,520 | 54.4% |
| POP_TOP | 39,145,520 | 42.3% |
| STORE_FAST | 3,055,840 | 3.3% |
| TO_BOOL_BOOL | 30,020 | 0.0% |
| EXIT_INIT_CHECK | 3,360 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| STORE_FAST | 40 | 33.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,440 | 61.8% |
| LOAD_FAST_LOAD_FAST | 6,880 | 34.2% |
| STORE_ATTR | 480 | 2.4% |
| BINARY_SUBSCR | 60 | 0.3% |
| LOAD_ATTR | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,280 | 21.3% |
| LOAD_GLOBAL_BUILTIN | 3,520 | 17.5% |
| STORE_ATTR_SLOT | 2,860 | 14.2% |
| STORE_ATTR_INSTANCE_VALUE | 2,840 | 14.1% |
| LOAD_FAST_LOAD_FAST | 2,100 | 10.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,209,420 | 31.4% |
| CALL | 90,464,840 | 17.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 58,383,960 | 11.4% |
| BINARY_SUBSCR_DICT | 36,833,840 | 7.2% |
| BINARY_SUBSCR_LIST_INT | 34,977,300 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 367,336,040 | 72.0% |
| JUMP_FORWARD | 55,633,500 | 10.9% |
| LOAD_GLOBAL_MODULE | 36,400,180 | 7.1% |
| LOAD_FAST_LOAD_FAST | 29,983,540 | 5.9% |
| ENTER_EXECUTOR | 11,198,140 | 2.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 12,249,420 | 87.7% |
| FOR_ITER_LIST | 1,671,120 | 12.0% |
| FOR_ITER | 38,000 | 0.3% |
| CALL_LEN | 5,720 | 0.0% |
| FOR_ITER_TUPLE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,249,400 | 87.7% |
| LIST_APPEND | 835,040 | 6.0% |
| LOAD_ATTR_SLOT | 835,000 | 6.0% |
| LOAD_CONST | 37,920 | 0.3% |
| PUSH_NULL | 5,720 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,680,400 | 99.9% |
| COPY | 9,860 | 0.1% |
| UNPACK_SEQUENCE_TUPLE | 240 | 0.0% |
| UNPACK_SEQUENCE | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,493,680 | 97.4% |
| LOAD_GLOBAL_BUILTIN | 131,120 | 1.7% |
| LOAD_FAST_LOAD_FAST | 61,660 | 0.8% |
| NOP | 2,980 | 0.0% |
| BUILD_LIST | 720 | 0.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 720 | 75.0% |
| LOAD_FAST | 240 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 265,880 | 49.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 265,800 | 49.9% |
| IMPORT_NAME | 480 | 0.1% |
| LOAD_CONST | 120 | 0.0% |
| BUILD_CONST_KEY_MAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 265,940 | 49.9% |
| STORE_NAME | 265,880 | 49.9% |
| RETURN_CONST | 500 | 0.1% |
| LOAD_CONST | 160 | 0.0% |
| BUILD_MAP | 80 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,172,320 | 74.8% |
| BINARY_OP_ADD_INT | 1,592,860 | 9.8% |
| BUILD_LIST | 837,060 | 5.1% |
| LOAD_FAST_AND_CLEAR | 837,060 | 5.1% |
| ENTER_EXECUTOR | 836,000 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,172,360 | 74.8% |
| STORE_ATTR_INSTANCE_VALUE | 1,592,840 | 9.8% |
| BUILD_LIST | 837,060 | 5.1% |
| STORE_FAST | 836,340 | 5.1% |
| FOR_ITER_LIST | 835,460 | 5.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 420 | 65.6% |
| RETURN_VALUE | 80 | 12.5% |
| FOR_ITER_LIST | 60 | 9.4% |
| LOAD_FAST | 40 | 6.2% |
| BINARY_SUBSCR | 20 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 320 | 50.0% |
| STORE_FAST_STORE_FAST | 220 | 34.4% |
| STORE_NAME | 80 | 12.5% |
| STORE_FAST_LOAD_FAST | 20 | 3.1% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 240 | 75.0% |
| CALL | 80 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 320 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,800 | 32.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,520 | 27.2% |
| CALL | 1,140 | 20.4% |
| CALL_PY_EXACT_ARGS | 920 | 16.5% |
| CALL_KW | 100 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,100 | 37.6% |
| LOAD_GLOBAL | 1,500 | 26.9% |
| LOAD_FAST_LOAD_FAST | 1,120 | 20.1% |
| LOAD_CONST | 720 | 12.9% |
| BUILD_LIST | 60 | 1.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,229,860 | 87.5% |
| CALL | 1,592,840 | 12.4% |
| LOAD_FAST_LOAD_FAST | 10,000 | 0.1% |
| BINARY_OP_MULTIPLY_INT | 2,480 | 0.0% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,199,580 | 87.3% |
| SWAP | 1,592,860 | 12.4% |
| LOAD_FAST | 32,660 | 0.3% |
| CALL_BUILTIN_O | 4,160 | 0.0% |
| CALL_PY_EXACT_ARGS | 4,160 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 543,920 | 48.8% |
| BINARY_OP | 540,700 | 48.5% |
| RETURN_VALUE | 21,880 | 2.0% |
| BINARY_SLICE | 6,760 | 0.6% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 569,460 | 51.1% |
| STORE_FAST | 544,040 | 48.8% |
| BINARY_OP_INPLACE_ADD_UNICODE | 240 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,320 | 77.0% |
| BINARY_SUBSCR_TUPLE_INT | 2,480 | 23.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,160 | 38.5% |
| CALL_BUILTIN_O | 4,160 | 38.5% |
| BINARY_OP_ADD_INT | 2,480 | 23.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,914,980 | 86.9% |
| LOAD_FAST | 5,268,280 | 13.1% |
| CALL_LEN | 12,980 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,909,520 | 86.8% |
| STORE_FAST | 5,263,020 | 13.1% |
| RETURN_VALUE | 12,980 | 0.0% |
| LOAD_FAST_LOAD_FAST | 8,640 | 0.0% |
| LOAD_FAST | 1,820 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,290,160 | 64.5% |
| BINARY_SUBSCR | 35,692,480 | 28.3% |
| LOAD_CONST | 7,715,760 | 6.1% |
| LOAD_FAST_LOAD_FAST | 1,025,740 | 0.8% |
| LOAD_NAME | 261,880 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 46,024,440 | 36.5% |
| LOAD_FAST | 38,522,220 | 30.6% |
| STORE_FAST | 36,833,840 | 29.2% |
| POP_JUMP_IF_NOT_NONE | 1,162,280 | 0.9% |
| CONTAINS_OP | 754,660 | 0.6% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 47,353,340 | 100.0% |
| LOAD_FAST | 7,240 | 0.0% |
| BINARY_SUBSCR | 4,780 | 0.0% |
| ENTER_EXECUTOR | 4,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 47,369,400 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 99,728,960 | 66.3% |
| UNARY_NEGATIVE | 34,943,080 | 23.2% |
| LOAD_FAST_LOAD_FAST | 12,249,400 | 8.1% |
| LOAD_CONST | 3,506,500 | 2.3% |
| BINARY_SUBSCR | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 47,352,760 | 31.5% |
| STORE_ATTR_INSTANCE_VALUE | 36,129,520 | 24.0% |
| STORE_FAST | 34,977,300 | 23.3% |
| LOAD_CONST | 18,021,640 | 12.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,249,560 | 8.1% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,375,160 | 99.5% |
| LOAD_FAST | 29,060 | 0.3% |
| LOAD_CONST | 19,500 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,375,180 | 99.5% |
| STORE_FAST | 26,560 | 0.3% |
| LOAD_CONST | 18,480 | 0.2% |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,360 | 0.0% |
| CALL_BUILTIN_O | 1,020 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 257,480 | 99.9% |
| BINARY_SUBSCR | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 46,520 | 18.0% |
| LOAD_FAST | 44,100 | 17.1% |
| CALL_STR_1 | 40,520 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 40,520 | 15.7% |
| LOAD_GLOBAL_MODULE | 18,200 | 7.1% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 1,780 | 53.0% |
| LOAD_GLOBAL_MODULE | 560 | 16.7% |
| LOAD_ATTR_MODULE | 400 | 11.9% |
| LOAD_FAST | 240 | 7.1% |
| LOAD_ATTR_INSTANCE_VALUE | 200 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,360 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,428,200 | 62.3% |
| PUSH_NULL | 10,387,680 | 27.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,945,720 | 7.8% |
| LOAD_ATTR_WITH_HINT | 433,520 | 1.2% |
| CALL_PY_EXACT_ARGS | 360,700 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 36,477,580 | 97.0% |
| COPY_FREE_VARS | 754,180 | 2.0% |
| CALL_PY_EXACT_ARGS | 360,700 | 1.0% |
| RESUME | 1,520 | 0.0% |
| POP_TOP | 160 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 3,011,760 | 88.9% |
| LOAD_GLOBAL_BUILTIN | 217,560 | 6.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 126,920 | 3.7% |
| LOAD_CONST | 17,820 | 0.5% |
| CALL_LEN | 7,240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,964,600 | 87.5% |
| CALL_LIST_APPEND | 216,760 | 6.4% |
| STORE_FAST | 129,260 | 3.8% |
| LOAD_FAST | 65,780 | 1.9% |
| LOAD_CONST | 7,240 | 0.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,342,720 | 99.2% |
| LOAD_FAST_LOAD_FAST | 83,800 | 0.5% |
| LOAD_ATTR | 40,520 | 0.2% |
| LOAD_FAST | 6,320 | 0.0% |
| CALL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 16,202,040 | 98.4% |
| BUILD_TUPLE | 83,800 | 0.5% |
| STORE_FAST | 81,300 | 0.5% |
| TO_BOOL_BOOL | 59,040 | 0.4% |
| COPY | 40,540 | 0.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 47.4% |
| BINARY_OP | 400 | 26.3% |
| CALL_TUPLE_1 | 160 | 10.5% |
| LOAD_CONST | 120 | 7.9% |
| CALL | 80 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 440 | 28.9% |
| RETURN_VALUE | 400 | 26.3% |
| STORE_FAST | 360 | 23.7% |
| BEFORE_WITH | 260 | 17.1% |
| GET_ITER | 60 | 3.9% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,640 | 37.8% |
| LOAD_GLOBAL_MODULE | 20,440 | 21.7% |
| LOAD_CONST | 9,500 | 10.1% |
| RETURN_VALUE | 7,240 | 7.7% |
| BINARY_SUBSCR_TUPLE_INT | 6,260 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80,540 | 85.4% |
| BUILD_TUPLE | 13,640 | 14.5% |
| STORE_FAST | 40 | 0.0% |
| TO_BOOL_INT | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 48,122,700 | 88.4% |
| LOAD_ATTR_MODULE | 4,962,440 | 9.1% |
| BUILD_TUPLE | 1,285,700 | 2.4% |
| LOAD_ATTR | 40,920 | 0.1% |
| LOAD_GLOBAL_MODULE | 14,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,392,800 | 99.9% |
| RETURN_VALUE | 40,860 | 0.1% |
| TO_BOOL | 640 | 0.0% |
| LOAD_FAST | 160 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,989,400 | 49.4% |
| LOAD_ATTR_INSTANCE_VALUE | 10,801,160 | 48.6% |
| LOAD_ATTR_WITH_HINT | 216,760 | 1.0% |
| BINARY_SUBSCR_DICT | 202,560 | 0.9% |
| POP_JUMP_IF_TRUE | 12,980 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,379,580 | 51.2% |
| RETURN_VALUE | 10,811,840 | 48.6% |
| BINARY_OP_SUBTRACT_INT | 12,980 | 0.1% |
| LOAD_FAST | 9,700 | 0.0% |
| CALL_BUILTIN_CLASS | 7,240 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,074,520 | 99.0% |
| RETURN_VALUE | 484,240 | 0.5% |
| CALL_BUILTIN_CLASS | 216,760 | 0.2% |
| ENTER_EXECUTOR | 80,640 | 0.1% |
| CALL_FUNCTION_EX | 74,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,819,340 | 49.8% |
| EXTENDED_ARG | 36,315,080 | 38.6% |
| LOAD_CONST | 10,374,520 | 11.0% |
| RETURN_CONST | 228,940 | 0.2% |
| ENTER_EXECUTOR | 213,360 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,379,600 | 73.2% |
| LOAD_ATTR_METHOD_NO_DICT | 12,470,560 | 17.4% |
| LOAD_CONST | 6,648,280 | 9.3% |
| LOAD_ATTR | 40,760 | 0.1% |
| CALL | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 58,383,960 | 81.6% |
| LOAD_FAST | 10,899,380 | 15.2% |
| POP_TOP | 1,068,160 | 1.5% |
| POP_JUMP_IF_NONE | 599,820 | 0.8% |
| TO_BOOL_BOOL | 478,320 | 0.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 17,000 | 95.3% |
| LOAD_GLOBAL_MODULE | 820 | 4.6% |
| CALL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,020 | 95.4% |
| LOAD_CONST | 820 | 4.6% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 130,720 | 99.9% |
| CALL | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 126,920 | 97.0% |
| GET_ITER | 1,700 | 1.3% |
| TO_BOOL_BOOL | 1,400 | 1.1% |
| CONTAINS_OP | 860 | 0.7% |
| CALL | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 219,560 | 91.2% |
| BINARY_SLICE | 18,440 | 7.7% |
| LOAD_FAST | 1,500 | 0.6% |
| STORE_FAST | 440 | 0.2% |
| LOAD_CONST | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 220,420 | 91.6% |
| STORE_FAST | 18,540 | 7.7% |
| LIST_APPEND | 520 | 0.2% |
| RETURN_VALUE | 460 | 0.2% |
| CALL_LIST_APPEND | 400 | 0.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,194,180 | 67.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,427,000 | 16.3% |
| LOAD_CONST | 5,826,080 | 9.1% |
| LOAD_FAST_LOAD_FAST | 1,669,540 | 2.6% |
| RETURN_VALUE | 688,600 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 62,896,780 | 98.3% |
| COPY_FREE_VARS | 701,420 | 1.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 360,700 | 0.6% |
| CALL_PY_EXACT_ARGS | 18,760 | 0.0% |
| RESUME | 920 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 851,440 | 94.9% |
| LOAD_FAST | 45,500 | 5.1% |
| CALL | 200 | 0.0% |
| LOAD_FAST_LOAD_FAST | 200 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 897,320 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 40,520 | 99.7% |
| LOAD_FAST | 120 | 0.3% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,540 | 99.7% |
| STORE_FAST | 80 | 0.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 2,600 | 92.2% |
| LOAD_FAST | 160 | 5.7% |
| LOAD_GLOBAL_MODULE | 40 | 1.4% |
| CALL | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,620 | 92.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 160 | 5.7% |
| CALL | 40 | 1.4% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,240 | 98.2% |
| LOAD_GLOBAL_MODULE | 40 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,080 | 91.2% |
| LOAD_FAST | 160 | 7.0% |
| PUSH_NULL | 40 | 1.8% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 145,381,180 | 92.2% |
| LOAD_FAST_LOAD_FAST | 12,249,920 | 7.8% |
| LOAD_GLOBAL_MODULE | 4,480 | 0.0% |
| CALL_LEN | 2,120 | 0.0% |
| LOAD_FAST | 2,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 146,181,300 | 92.7% |
| EXTENDED_ARG | 10,374,860 | 6.6% |
| POP_JUMP_IF_TRUE | 1,084,560 | 0.7% |
| RETURN_VALUE | 40 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,418,000 | 99.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,020 | 0.7% |
| LOAD_FAST_LOAD_FAST | 1,840 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,381,560 | 98.4% |
| POP_JUMP_IF_TRUE | 57,280 | 1.3% |
| EXTENDED_ARG | 14,280 | 0.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 7,993,000 | 75.5% |
| GET_ITER | 1,748,000 | 16.5% |
| SWAP | 835,460 | 7.9% |
| JUMP_BACKWARD | 5,440 | 0.1% |
| FOR_ITER | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,432,740 | 70.2% |
| STORE_FAST_LOAD_FAST | 1,671,120 | 15.8% |
| STORE_FAST | 1,475,520 | 13.9% |
| LOAD_FAST | 1,020 | 0.0% |
| LOAD_FAST_LOAD_FAST | 580 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,080 | 91.0% |
| SWAP | 820 | 8.2% |
| JUMP_BACKWARD | 60 | 0.6% |
| FOR_ITER | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,900 | 99.2% |
| LOAD_FAST | 80 | 0.8% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,400 | 87.6% |
| JUMP_BACKWARD | 1,500 | 7.1% |
| EXTENDED_ARG | 520 | 2.5% |
| SWAP | 460 | 2.2% |
| FOR_ITER | 120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 19,300 | 91.9% |
| EXTENDED_ARG | 640 | 3.0% |
| JUMP_BACKWARD | 320 | 1.5% |
| LOAD_CONST | 320 | 1.5% |
| STORE_FAST_LOAD_FAST | 240 | 1.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 321,041,620 | 77.9% |
| BINARY_SUBSCR_LIST_INT | 47,352,760 | 11.5% |
| LOAD_FAST_LOAD_FAST | 36,337,920 | 8.8% |
| LOAD_ATTR_WITH_HINT | 5,256,120 | 1.3% |
| COPY | 1,592,840 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160,209,420 | 38.9% |
| LOAD_FAST | 149,742,780 | 36.3% |
| RETURN_VALUE | 47,407,520 | 11.5% |
| CALL_LEN | 10,801,160 | 2.6% |
| LOAD_CONST | 8,185,920 | 2.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 132,564,180 | 68.9% |
| BINARY_SUBSCR_DICT | 46,024,440 | 23.9% |
| LOAD_ATTR_INSTANCE_VALUE | 7,327,640 | 3.8% |
| LOAD_ATTR | 3,976,900 | 2.1% |
| LOAD_ATTR_SLOT | 610,680 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,274,300 | 78.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 12,470,560 | 6.5% |
| CALL | 12,249,680 | 6.4% |
| LOAD_CONST | 9,586,640 | 5.0% |
| LOAD_FAST_LOAD_FAST | 7,495,480 | 3.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,701,220 | 61.4% |
| LOAD_ATTR_WITH_HINT | 10,374,920 | 38.1% |
| LOAD_ATTR_INSTANCE_VALUE | 130,800 | 0.5% |
| BINARY_SUBSCR | 4,160 | 0.0% |
| ENTER_EXECUTOR | 2,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,783,180 | 58.0% |
| CALL_PY_EXACT_ARGS | 10,427,000 | 38.3% |
| LOAD_CONST | 1,003,580 | 3.7% |
| LOAD_GLOBAL_MODULE | 840 | 0.0% |
| LOAD_FAST_LOAD_FAST | 520 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,073,640 | 100.0% |
| LOAD_FAST | 2,920 | 0.0% |
| LOAD_ATTR | 2,640 | 0.0% |
| LOAD_FAST_LOAD_FAST | 1,400 | 0.0% |
| BINARY_SUBSCR_DICT | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 9,299,800 | 51.4% |
| CALL_ISINSTANCE | 4,962,440 | 27.4% |
| LOAD_GLOBAL_MODULE | 2,480,860 | 13.7% |
| BUILD_TUPLE | 1,251,800 | 6.9% |
| LOAD_ATTR_METHOD_NO_DICT | 41,240 | 0.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 50.0% |
| LOAD_FAST_LOAD_FAST | 160 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 160 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 160 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,000 | 99.3% |
| LOAD_ATTR_INSTANCE_VALUE | 320 | 0.6% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 49,340 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,950,680 | 50.2% |
| RETURN_VALUE | 2,911,400 | 24.6% |
| BINARY_SUBSCR_LIST_INT | 842,480 | 7.1% |
| STORE_FAST_LOAD_FAST | 835,000 | 7.0% |
| BINARY_SUBSCR_DICT | 623,360 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,255,920 | 19.0% |
| CALL | 2,151,120 | 18.1% |
| STORE_FAST | 1,806,060 | 15.2% |
| LOAD_CONST | 1,723,200 | 14.5% |
| GET_ITER | 868,920 | 7.3% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,649,360 | 76.4% |
| LOAD_ATTR_WITH_HINT | 5,425,560 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,256,120 | 11.6% |
| LOAD_ATTR | 640 | 0.0% |
| LOAD_FAST_LOAD_FAST | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,541,800 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,374,920 | 22.9% |
| LOAD_FAST | 8,267,440 | 18.2% |
| LOAD_ATTR_WITH_HINT | 5,425,560 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,256,120 | 11.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 88,532,160 | 60.6% |
| LOAD_FAST | 47,610,460 | 32.6% |
| STORE_FAST | 5,394,880 | 3.7% |
| RETURN_VALUE | 1,339,760 | 0.9% |
| POP_TOP | 846,760 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,763,940 | 66.2% |
| CALL_ISINSTANCE | 48,122,700 | 32.9% |
| BUILD_LIST | 846,380 | 0.6% |
| CALL_BUILTIN_CLASS | 217,560 | 0.1% |
| LOAD_FAST_LOAD_FAST | 91,680 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,400,180 | 51.1% |
| POP_JUMP_IF_TRUE | 13,091,920 | 18.4% |
| RESUME_CHECK | 10,077,540 | 14.2% |
| LOAD_FAST | 4,975,600 | 7.0% |
| LOAD_ATTR_MODULE | 2,480,860 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 47,213,040 | 66.3% |
| LOAD_ATTR_MODULE | 18,073,640 | 25.4% |
| LOAD_FAST | 5,464,120 | 7.7% |
| LOAD_ATTR | 124,580 | 0.2% |
| IS_OP | 93,940 | 0.1% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 62,896,780 | 29.7% |
| CACHE | 61,286,880 | 29.0% |
| BINARY_SUBSCR_GETITEM | 47,369,400 | 22.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 36,477,580 | 17.2% |
| COPY_FREE_VARS | 1,455,720 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 88,532,160 | 41.8% |
| LOAD_FAST | 58,554,060 | 27.7% |
| LOAD_FAST_LOAD_FAST | 50,968,140 | 24.1% |
| LOAD_GLOBAL_MODULE | 10,077,540 | 4.8% |
| LOAD_CONST | 1,986,840 | 0.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,778,840 | 68.0% |
| BINARY_SUBSCR_LIST_INT | 36,129,520 | 13.8% |
| LOAD_FAST_LOAD_FAST | 33,438,160 | 12.8% |
| STORE_FAST_LOAD_FAST | 12,249,400 | 4.7% |
| SWAP | 1,592,840 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,317,360 | 48.0% |
| RETURN_CONST | 37,970,820 | 14.5% |
| LOAD_CONST | 35,783,280 | 13.7% |
| NOP | 35,691,440 | 13.7% |
| LOAD_FAST_LOAD_FAST | 26,488,040 | 10.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 45,480,360 | 94.5% |
| LOAD_FAST | 2,609,200 | 5.4% |
| STORE_ATTR_SLOT | 9,620 | 0.0% |
| RETURN_VALUE | 6,760 | 0.0% |
| STORE_ATTR | 2,860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 30,350,540 | 63.1% |
| RETURN_CONST | 14,583,500 | 30.3% |
| LOAD_FAST | 3,165,140 | 6.6% |
| STORE_ATTR_SLOT | 9,620 | 0.0% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,701,520 | 100.0% |
| LOAD_ATTR_WITH_HINT | 200 | 0.0% |
| STORE_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,505,660 | 98.2% |
| RETURN_CONST | 196,020 | 1.8% |
| LOAD_CONST | 220 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 506,840 | 64.7% |
| LOAD_NAME | 275,620 | 35.2% |
| LOAD_CONST | 600 | 0.1% |
| STORE_SUBSCR | 380 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 478,360 | 61.1% |
| JUMP_BACKWARD | 267,760 | 34.2% |
| LOAD_GLOBAL_BUILTIN | 18,600 | 2.4% |
| LOAD_NAME | 13,780 | 1.8% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,899,320 | 100.0% |
| LOAD_FAST_LOAD_FAST | 8,640 | 0.0% |
| LOAD_FAST | 6,400 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,899,660 | 100.0% |
| ENTER_EXECUTOR | 4,600 | 0.0% |
| EXTENDED_ARG | 4,400 | 0.0% |
| RETURN_CONST | 4,320 | 0.0% |
| JUMP_BACKWARD | 1,400 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 34,608,760 | 55.1% |
| LOAD_FAST | 27,603,620 | 43.9% |
| TO_BOOL_NONE | 330,080 | 0.5% |
| COPY | 153,160 | 0.2% |
| CALL_KW | 65,320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 62,365,020 | 99.3% |
| TO_BOOL_NONE | 330,060 | 0.5% |
| POP_JUMP_IF_FALSE | 121,160 | 0.2% |
| TO_BOOL_ALWAYS_TRUE | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 54,392,800 | 82.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,979,440 | 7.6% |
| RETURN_VALUE | 3,028,980 | 4.6% |
| LOAD_FAST | 2,565,180 | 3.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 478,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 56,585,920 | 86.3% |
| POP_JUMP_IF_TRUE | 9,002,560 | 13.7% |
| EXTENDED_ARG | 12,960 | 0.0% |
| TO_BOOL_INT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,084,680 | 99.9% |
| BINARY_OP | 26,980 | 0.1% |
| COPY | 2,320 | 0.0% |
| TO_BOOL | 60 | 0.0% |
| TO_BOOL_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,092,560 | 100.0% |
| POP_JUMP_IF_TRUE | 13,120 | 0.0% |
| UNARY_NOT | 8,440 | 0.0% |
| TO_BOOL_BOOL | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,220,760 | 95.7% |
| BINARY_SUBSCR_DICT | 377,440 | 3.2% |
| COPY | 123,900 | 1.1% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |
| TO_BOOL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 11,711,360 | 99.9% |
| POP_JUMP_IF_FALSE | 10,880 | 0.1% |
| UNARY_NOT | 160 | 0.0% |
| TO_BOOL_NONE | 20 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,619,940 | 72.9% |
| ENTER_EXECUTOR | 10,382,060 | 21.9% |
| COPY | 1,496,800 | 3.2% |
| LOAD_ATTR_SLOT | 548,820 | 1.2% |
| TO_BOOL_ALWAYS_TRUE | 330,060 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 46,474,980 | 97.9% |
| POP_JUMP_IF_FALSE | 583,840 | 1.2% |
| TO_BOOL_ALWAYS_TRUE | 330,080 | 0.7% |
| TO_BOOL | 89,040 | 0.2% |
| TO_BOOL_STR | 40 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,397,520 | 99.6% |
| COPY | 13,020 | 0.2% |
| BINARY_SUBSCR_TUPLE_INT | 6,540 | 0.1% |
| LOAD_FAST | 2,000 | 0.0% |
| STORE_FAST_LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,404,260 | 99.7% |
| POP_JUMP_IF_TRUE | 15,180 | 0.3% |
| TO_BOOL_NONE | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,000 | 93.5% |
| BINARY_SUBSCR_TUPLE_INT | 320 | 3.7% |
| RETURN_VALUE | 160 | 1.9% |
| CALL_METHOD_DESCRIPTOR_O | 80 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,320 | 97.2% |
| STORE_FAST_STORE_FAST | 240 | 2.8% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 12,249,560 | 60.6% |
| FOR_ITER_LIST | 7,432,740 | 36.8% |
| FOR_ITER | 483,000 | 2.4% |
| RETURN_VALUE | 45,400 | 0.2% |
| LOAD_CONST | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 12,249,420 | 60.6% |
| STORE_FAST_STORE_FAST | 7,680,400 | 38.0% |
| STORE_NAME | 265,800 | 1.3% |
| STORE_FAST | 16,780 | 0.1% |


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
|     deferred | 1,797,360 | 3.2% |
|          hit | 54,173,000 | 96.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 10.3% |
| Failure | 2,260 | 89.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 880 | 38.9% |
| multiply different types | 640 | 28.3% |
| and int | 360 | 15.9% |
| remainder | 240 | 10.6% |
| or | 120 | 5.3% |
| add different types | 20 | 0.9% |


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
|     deferred | 36,692,660 | 9.9% |
|          hit | 334,499,440 | 90.1% |
|         miss | 10,040 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,880 | 38.7% |
| Failure | 10,900 | 61.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 10,820 | 99.3% |
| buffer slice | 40 | 0.4% |
| other | 20 | 0.2% |
| list slice | 20 | 0.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 108,387,900 | 21.2% |
|          hit | 363,452,780 | 71.0% |
|         miss | 39,233,900 | 7.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 746,400 | 95.4% |
| Failure | 35,940 | 4.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| init not python | 12,200 | 33.9% |
| meth descr method fastcall keywords | 9,140 | 25.4% |
| no dict | 8,120 | 22.6% |
| meth descr varargs | 5,600 | 15.6% |
| class no vectorcall | 220 | 0.6% |
| cfunc varargs | 180 | 0.5% |
| wrong number arguments | 160 | 0.4% |
| cfunc varargs keywords | 160 | 0.4% |
| cfunc noargs | 100 | 0.3% |
| code complex parameters | 60 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 549,560 | 0.3% |
|          hit | 162,093,800 | 99.7% |
|         miss | 160 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 74.4% |
| Failure | 460 | 25.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list | 320 | 69.6% |
| other | 80 | 17.4% |
| tuple | 40 | 8.7% |
| different types | 20 | 4.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,626,520 | 47.6% |
|          hit | 10,612,260 | 52.4% |
|         miss | 980 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 9.6% |
| Failure | 4,700 | 90.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| reversed list | 2,080 | 44.3% |
| dict items | 880 | 18.7% |
| ascii string | 520 | 11.1% |
| zip | 420 | 8.9% |
| dict keys | 260 | 5.5% |
| seq iter | 200 | 4.3% |
| enumerate | 180 | 3.8% |
| dict values | 160 | 3.4% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 33,962,840 | 4.6% |
|          hit | 692,697,440 | 93.4% |
|         miss | 14,361,860 | 1.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 279,940 | 92.2% |
| Failure | 23,580 | 7.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 17,640 | 74.8% |
| not managed dict | 3,360 | 14.2% |
| method | 760 | 3.2% |
| overridden | 680 | 2.9% |
| module attr not found | 660 | 2.8% |
| non object slot | 340 | 1.4% |
| shadowed | 60 | 0.3% |
| builtin class method | 40 | 0.2% |
| metaclass attribute | 20 | 0.1% |
| class attr simple | 20 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,080 | 0.0% |
|        deopt | 80 | 0.0% |
|          hit | 217,259,380 | 100.0% |
|         miss | 26,800 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,920 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 80 | 100.0% |


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
|     deferred | 4,140 | 0.0% |
|          hit | 319,554,320 | 99.8% |
|         miss | 513,660 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 15,500 | 97.0% |
| Failure | 480 | 3.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overriding descriptor | 120 | 25.0% |
| non object slot | 120 | 25.0% |
| not in keys | 120 | 25.0% |
| not in dict | 120 | 25.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 35,731,080 | 50.0% |
|          hit | 35,697,900 | 50.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 1.3% |
| Failure | 30,060 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 30,000 | 99.8% |
| bytearray int | 40 | 0.1% |
| out of range | 20 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,162,480 | 1.3% |
|          hit | 199,422,940 | 82.0% |
|         miss | 39,728,960 | 16.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 751,360 | 81.6% |
| Failure | 169,200 | 18.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 164,260 | 97.1% |
| dict | 3,660 | 2.2% |
| tuple | 1,200 | 0.7% |
| mapping | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 320 | 0.0% |
|          hit | 20,220,960 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 4,574,738,160 | 57.2% |
| Not specialized | 740,967,020 | 9.3% |
| Specialized hits | 2,583,655,960 | 32.3% |
| Specialized misses | 93,879,920 | 1.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 108,387,900 | 47.1% |
| BINARY_SUBSCR | 36,692,660 | 16.0% |
| STORE_SUBSCR | 35,731,080 | 15.5% |
| LOAD_ATTR | 33,962,840 | 14.8% |
| FOR_ITER | 9,626,520 | 4.2% |
| TO_BOOL | 3,162,480 | 1.4% |
| BINARY_OP | 1,797,360 | 0.8% |
| COMPARE_OP | 549,560 | 0.2% |
| LOAD_GLOBAL | 5,080 | 0.0% |
| STORE_ATTR | 4,140 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_NONE | 22,220,380 | 23.7% |
| CALL_PY_EXACT_ARGS | 20,112,200 | 21.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 19,118,760 | 20.4% |
| TO_BOOL_ALWAYS_TRUE | 17,497,680 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 11,289,980 | 12.0% |
| LOAD_ATTR_SLOT | 2,950,720 | 3.1% |
| STORE_ATTR_SLOT | 512,420 | 0.5% |
| LOAD_ATTR_WITH_HINT | 117,400 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 15,880 | 0.0% |
| LOAD_GLOBAL_MODULE | 10,920 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 61,288,960 | 29.0% |
| Calls to Python functions inlined | 150,295,960 | 71.0% |
| Calls via PyEval_EvalFrame (total) | 61,288,960 | 29.0% |
| Calls via PyEval_EvalFrame (vector) | 61,288,480 | 29.0% |
| Calls via PyEval_EvalFrame (generator) | 480 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 520 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 61,287,960 | 29.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 46,520,240 | 22.0% |
| Calls via PyEval_EvalFrame (function ex) | 440 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 98,540 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 19,800 | 0.0% |
| Frames pushed | 110,791,480 | 52.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 85,294,760 | 22.8% |
| Frees to freelist | 85,444,540 |  |
| Allocations | 288,656,420 | 77.2% |
| Allocations to 512 bytes | 251,981,180 | 67.4% |
| Allocations to 4 kbytes | 36,671,440 | 9.8% |
| Allocations over 4 kbytes | 3,800 | 0.0% |
| Frees | 324,906,705 |  |
| New values | 48,025,580 |  |
| Interpreter increfs | 3,968,820,400 | 86.1% |
| Interpreter decrefs | 4,215,004,840 | 85.4% |
| Increfs | 641,556,605 | 13.9% |
| Decrefs | 722,968,494 | 14.6% |
| Materialize dict (on request) | 480 | 0.0% |
| Materialize dict (new key) | 120 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 120 | 0.0% |
| Method cache hits | 65,334,040 |  |
| Method cache misses | 187,360 |  |
| Method cache collisions | 197,802 |  |
| Method cache dunder hits | 118,746,589 |  |
| Method cache dunder misses | 22,271 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 23,360 | 480 | 116,030,840 |
| 1 | 2,120 | 60 | 121,894,320 |
| 2 | 180 | 11,338,080 | 193,901,960 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 358,980 |  |
| Traces created | 780 | 0.2% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 40 | 0.0% |
| Trace too short | 358,200 | 99.8% |
| Inner loop found | 40 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 87,798,100 |  |
| Uops executed | 1,158,765,360 | 13.20 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 5.1% |
| <= 32 | 220 | 28.2% |
| <= 64 | 240 | 30.8% |
| <= 128 | 280 | 35.9% |


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
| <= 16 | 40 | 5.1% |
| <= 32 | 280 | 35.9% |
| <= 64 | 280 | 35.9% |
| <= 128 | 180 | 23.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 12,860 | 0.0% |
| <= 4 | 579,280 | 0.7% |
| <= 8 | 48,509,720 | 55.3% |
| <= 16 | 8,417,600 | 9.6% |
| <= 32 | 25,001,640 | 28.5% |
| <= 64 | 5,212,520 | 5.9% |
| <= 128 | 62,920 | 0.1% |
| <= 256 | 1,200 | 0.0% |
| <= 512 | 60 | 0.0% |
| <= 1,024 | 20 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 20 | 0.0% |
| <= 8,192 | 20 | 0.0% |
| <= 16,384 | 240 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 302,829,720 | 26.1% | 26.1% |  |
| _SET_IP | 284,389,800 | 24.5% | 50.7% |  |
| STORE_FAST | 62,945,220 | 5.4% | 56.1% |  |
| CONTAINS_OP | 59,126,280 | 5.1% | 61.2% |  |
| _POP_JUMP_IF_FALSE | 58,984,540 | 5.1% | 66.3% |  |
| _POP_JUMP_IF_TRUE | 47,883,200 | 4.1% | 70.4% |  |
| _EXIT_TRACE | 42,037,940 | 3.6% | 74.1% |  |
| _GUARD_TYPE_VERSION | 38,537,700 | 3.3% | 77.4% | 1.5% |
| TO_BOOL_NONE | 34,656,080 | 3.0% | 80.4% | 99.9% |
| _ITER_CHECK_LIST | 32,983,120 | 2.8% | 83.2% | 0.0% |
| _IS_ITER_EXHAUSTED_LIST | 32,970,260 | 2.8% | 86.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 30,188,460 | 2.6% | 88.7% |  |
| _ITER_NEXT_LIST | 29,781,940 | 2.6% | 91.2% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 29,220,020 | 2.5% | 93.8% |  |
| BINARY_SUBSCR_STR_INT | 13,078,360 | 1.1% | 94.9% | 0.0% |
| COMPARE_OP_INT | 12,668,040 | 1.1% | 96.0% |  |
| TO_BOOL_ALWAYS_TRUE | 11,120,400 | 1.0% | 96.9% | 93.3% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,421,440 | 0.6% | 97.6% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 7,421,440 | 0.6% | 98.2% |  |
| GET_ITER | 4,899,360 | 0.4% | 98.7% |  |
| POP_TOP | 3,322,780 | 0.3% | 98.9% |  |
| LOAD_CONST | 2,153,180 | 0.2% | 99.1% |  |
| _GUARD_GLOBALS_VERSION | 1,315,140 | 0.1% | 99.2% | 12.7% |
| BINARY_SUBSCR_DICT | 1,039,700 | 0.1% | 99.3% |  |
| _LOAD_GLOBAL_MODULE | 1,003,760 | 0.1% | 99.4% |  |
| _IS_NONE | 877,560 | 0.1% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 819,360 | 0.1% | 99.6% |  |
| UNARY_NEGATIVE | 748,320 | 0.1% | 99.6% |  |
| BINARY_SUBSCR_LIST_INT | 748,320 | 0.1% | 99.7% |  |
| _CHECK_ATTR_MODULE | 212,280 | 0.0% | 99.7% |  |
| _LOAD_ATTR_MODULE | 212,280 | 0.0% | 99.7% |  |
| TO_BOOL_BOOL | 197,900 | 0.0% | 99.7% |  |
| _GUARD_BUILTINS_VERSION | 144,260 | 0.0% | 99.8% |  |
| _LOAD_GLOBAL_BUILTINS | 144,260 | 0.0% | 99.8% |  |
| CALL_ISINSTANCE | 135,940 | 0.0% | 99.8% |  |
| _GUARD_DORV_VALUES | 128,280 | 0.0% | 99.8% |  |
| _STORE_ATTR_INSTANCE_VALUE | 128,280 | 0.0% | 99.8% |  |
| _CHECK_PEP_523 | 126,800 | 0.0% | 99.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 126,800 | 0.0% | 99.8% |  |
| _CHECK_STACK_SPACE | 126,800 | 0.0% | 99.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 126,800 | 0.0% | 99.8% |  |
| _PUSH_FRAME | 126,800 | 0.0% | 99.9% |  |
| _SAVE_RETURN_OFFSET | 126,800 | 0.0% | 99.9% |  |
| RESUME_CHECK | 119,980 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 117,760 | 0.0% | 99.9% |  |
| _POP_FRAME | 114,520 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 114,160 | 0.0% | 99.9% |  |
| _LOAD_ATTR_SLOT | 110,880 | 0.0% | 99.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 106,540 | 0.0% | 99.9% |  |
| _GUARD_KEYS_VERSION | 106,540 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 106,540 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 80,980 | 0.0% | 100.0% |  |
| PUSH_NULL | 68,960 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 50,400 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 49,420 | 0.0% | 100.0% |  |
| _ITER_CHECK_RANGE | 42,000 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 42,000 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 41,360 | 0.0% | 100.0% |  |
| LIST_APPEND | 40,480 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 32,160 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 31,140 | 0.0% | 100.0% |  |
| IS_OP | 22,680 | 0.0% | 100.0% |  |
| _ITER_CHECK_TUPLE | 20,000 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 20,000 | 0.0% | 100.0% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 14,600 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 14,600 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 10,220 | 0.0% | 100.0% |  |
| BINARY_SLICE | 7,180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 7,180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 6,880 | 0.0% | 100.0% |  |
| CALL_LEN | 5,840 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 4,500 | 0.0% | 100.0% |  |
| UNARY_NOT | 4,220 | 0.0% | 100.0% |  |
| COPY | 2,920 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 2,920 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 2,920 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 2,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,880 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,440 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 1,340 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 120 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 120 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 358,280 |
| CALL_LIST_APPEND | 160 |
| CALL | 120 |
| TO_BOOL | 20 |
| CALL_FUNCTION_EX | 20 |
| CALL_KW | 20 |
| LOAD_ATTR | 20 |
| STORE_ATTR | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-11-03
