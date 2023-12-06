
# Pystats results

- benchmark: concurrent_imap
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 78,671,409 | 18.1% | 18.1% |  |
| RESUME_CHECK | 29,438,495 | 6.8% | 24.8% | 0.0% |
| STORE_FAST | 21,901,574 | 5.0% | 29.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,646,421 | 4.5% | 34.4% | 0.8% |
| POP_TOP | 19,095,768 | 4.4% | 38.8% |  |
| RETURN_VALUE | 18,089,484 | 4.2% | 42.9% |  |
| POP_JUMP_IF_FALSE | 15,805,237 | 3.6% | 46.5% |  |
| LOAD_GLOBAL_MODULE | 13,096,667 | 3.0% | 49.6% | 0.0% |
| LOAD_CONST | 11,643,525 | 2.7% | 52.2% |  |
| LOAD_FAST_LOAD_FAST | 11,419,766 | 2.6% | 54.9% |  |
| CALL_PY_EXACT_ARGS | 10,090,972 | 2.3% | 57.2% |  |
| CALL | 9,337,971 | 2.1% | 59.3% |  |
| INTERPRETER_EXIT | 9,254,501 | 2.1% | 61.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,566,129 | 2.0% | 63.4% | 0.7% |
| LOAD_ATTR | 8,249,999 | 1.9% | 65.3% |  |
| ENTER_EXECUTOR | 8,141,043 | 1.9% | 67.2% |  |
| RETURN_CONST | 7,534,124 | 1.7% | 68.9% |  |
| NOP | 7,386,297 | 1.7% | 70.6% |  |
| BINARY_OP | 6,175,839 | 1.4% | 72.0% |  |
| LOAD_GLOBAL_BUILTIN | 6,073,408 | 1.4% | 73.4% |  |
| COPY | 5,796,373 | 1.3% | 74.7% |  |
| JUMP_BACKWARD | 5,706,446 | 1.3% | 76.1% |  |
| TO_BOOL_BOOL | 5,505,042 | 1.3% | 77.3% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 78.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,110,890 | 1.2% | 79.7% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 80.8% |  |
| TO_BOOL_INT | 4,582,392 | 1.1% | 81.8% |  |
| PUSH_NULL | 4,412,707 | 1.0% | 82.8% |  |
| POP_JUMP_IF_NOT_NONE | 4,102,499 | 0.9% | 83.8% |  |
| STORE_FAST_STORE_FAST | 3,743,425 | 0.9% | 84.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,513,443 | 0.8% | 85.5% | 4.2% |
| BUILD_TUPLE | 3,397,556 | 0.8% | 86.2% |  |
| COMPARE_OP_INT | 3,018,732 | 0.7% | 86.9% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 2,445,351 | 0.6% | 87.5% |  |
| SWAP | 2,202,526 | 0.5% | 88.0% |  |
| POP_JUMP_IF_TRUE | 2,080,285 | 0.5% | 88.5% |  |
| LOAD_ATTR_MODULE | 1,938,921 | 0.4% | 88.9% |  |
| CALL_FUNCTION_EX | 1,810,134 | 0.4% | 89.3% |  |
| GET_ITER | 1,795,154 | 0.4% | 89.7% |  |
| FOR_ITER_LIST | 1,730,533 | 0.4% | 90.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,728,385 | 0.4% | 90.5% |  |
| LOAD_DEREF | 1,589,189 | 0.4% | 90.9% |  |
| COPY_FREE_VARS | 1,552,109 | 0.4% | 91.3% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,508,352 | 0.3% | 91.6% |  |
| LOAD_SUPER_ATTR_METHOD | 1,480,469 | 0.3% | 92.0% |  |
| UNARY_INVERT | 1,477,632 | 0.3% | 92.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,466,850 | 0.3% | 92.6% |  |
| CONTAINS_OP | 1,463,929 | 0.3% | 93.0% |  |
| BEFORE_WITH | 1,437,170 | 0.3% | 93.3% |  |
| JUMP_FORWARD | 1,385,234 | 0.3% | 93.6% |  |
| BUILD_LIST | 1,319,354 | 0.3% | 93.9% |  |
| CALL_BUILTIN_FAST | 1,316,524 | 0.3% | 94.2% |  |
| BUILD_MAP | 1,315,789 | 0.3% | 94.5% |  |
| TO_BOOL | 1,216,180 | 0.3% | 94.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,177,686 | 0.3% | 95.1% |  |
| COMPARE_OP_STR | 1,143,010 | 0.3% | 95.3% |  |
| STORE_SUBSCR_DICT | 1,103,972 | 0.3% | 95.6% |  |
| CALL_ISINSTANCE | 1,047,880 | 0.2% | 95.8% |  |
| FOR_ITER | 976,760 | 0.2% | 96.1% |  |
| STORE_FAST_LOAD_FAST | 959,040 | 0.2% | 96.3% |  |
| POP_JUMP_IF_NONE | 925,130 | 0.2% | 96.5% |  |
| EXIT_INIT_CHECK | 912,218 | 0.2% | 96.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 912,218 | 0.2% | 96.9% |  |
| LOAD_ATTR_PROPERTY | 896,246 | 0.2% | 97.1% | 1.0% |
| UNPACK_SEQUENCE_TUPLE | 877,016 | 0.2% | 97.3% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 847,736 | 0.2% | 97.5% |  |
| BINARY_OP_ADD_INT | 831,243 | 0.2% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 725,424 | 0.2% | 97.9% |  |
| LIST_APPEND | 708,670 | 0.2% | 98.0% |  |
| LOAD_FAST_AND_CLEAR | 662,092 | 0.2% | 98.2% |  |
| LOAD_FAST_CHECK | 653,727 | 0.2% | 98.3% |  |
| CALL_BUILTIN_CLASS | 652,049 | 0.1% | 98.5% |  |
| COMPARE_OP | 498,975 | 0.1% | 98.6% |  |
| BINARY_SUBSCR | 478,853 | 0.1% | 98.7% |  |
| TO_BOOL_LIST | 471,469 | 0.1% | 98.8% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.9% |  |
| DICT_MERGE | 422,880 | 0.1% | 99.0% |  |
| LIST_EXTEND | 418,600 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,944 | 0.1% | 99.2% |  |
| CALL_LEN | 296,633 | 0.1% | 99.2% |  |
| CALL_KW | 295,770 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 249,783 | 0.1% | 99.4% |  |
| UNARY_NOT | 240,840 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 229,996 | 0.1% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 221,849 | 0.1% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 209,433 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,266 | 0.0% | 99.6% |  |
| STORE_DEREF | 103,200 | 0.0% | 99.6% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.7% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,696 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,419 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,821 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 58,574 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 57,782 | 0.0% | 99.9% | 7.6% |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 38,471 | 0.0% | 99.9% |  |
| POP_EXCEPT | 38,471 | 0.0% | 99.9% |  |
| IS_OP | 34,413 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 34,151 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 28,800 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 99.9% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 23,922 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,773 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,960 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 12,960 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 9,600 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 732 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 180 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,680,369 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 16,612,165 | 3.8% | 7.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,056,412 | 2.3% | 10.2% |
| STORE_FAST LOAD_FAST | 9,576,133 | 2.2% | 12.4% |
| CACHE RESUME_CHECK | 9,171,454 | 2.1% | 14.5% |
| LOAD_FAST RETURN_VALUE | 8,637,710 | 2.0% | 16.5% |
| RETURN_VALUE INTERPRETER_EXIT | 8,097,091 | 1.9% | 18.3% |
| LOAD_FAST LOAD_ATTR | 6,619,289 | 1.5% | 19.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,275,052 | 1.4% | 21.3% |
| POP_TOP LOAD_FAST | 6,169,644 | 1.4% | 22.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,999,995 | 1.4% | 24.1% |
| POP_TOP ENTER_EXECUTOR | 5,810,337 | 1.3% | 25.4% |
| RETURN_CONST POP_TOP | 5,325,160 | 1.2% | 26.7% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.8% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 28.9% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 30.0% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 31.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,619,907 | 1.1% | 32.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,582,392 | 1.1% | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,458,552 | 1.0% | 34.3% |
| NOP LOAD_FAST | 4,350,111 | 1.0% | 35.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,342,354 | 1.0% | 36.3% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 37.2% |
| ENTER_EXECUTOR YIELD_VALUE | 3,888,000 | 0.9% | 38.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,871,719 | 0.9% | 39.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,642,801 | 0.8% | 39.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 3,326,116 | 0.8% | 40.6% |
| STORE_FAST NOP | 3,113,731 | 0.7% | 41.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,098,589 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 3,027,079 | 0.7% | 42.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,016,444 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,991,388 | 0.7% | 44.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,966,588 | 0.7% | 44.8% |
| LOAD_CONST LOAD_CONST | 2,902,588 | 0.7% | 45.5% |
| LOAD_ATTR LOAD_FAST | 2,796,149 | 0.6% | 46.1% |
| CALL STORE_FAST | 2,763,656 | 0.6% | 46.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,707,356 | 0.6% | 47.4% |
| PUSH_NULL LOAD_FAST | 2,693,990 | 0.6% | 48.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,567,421 | 0.6% | 48.6% |
| COPY TO_BOOL_INT | 2,512,552 | 0.6% | 49.2% |
| BINARY_OP COPY | 2,512,552 | 0.6% | 49.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,431,150 | 0.6% | 50.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,426,643 | 0.6% | 50.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,336,663 | 0.5% | 51.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,322,820 | 0.5% | 51.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,098,082 | 0.5% | 52.4% |
| CALL RETURN_VALUE | 2,011,720 | 0.5% | 52.9% |
| LOAD_CONST CALL | 1,993,566 | 0.5% | 53.3% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 53.8% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 54.2% |
| LOAD_FAST PUSH_NULL | 1,959,704 | 0.5% | 54.7% |
| RETURN_VALUE STORE_FAST | 1,957,016 | 0.4% | 55.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,938,835 | 0.4% | 55.6% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,882,516 | 0.4% | 56.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,859,937 | 0.4% | 56.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,849,678 | 0.4% | 56.9% |
| CALL POP_TOP | 1,759,109 | 0.4% | 57.3% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,723,105 | 0.4% | 57.7% |
| RETURN_VALUE RETURN_VALUE | 1,722,791 | 0.4% | 58.1% |
| LOAD_CONST COMPARE_OP_INT | 1,687,184 | 0.4% | 58.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,612,557 | 0.4% | 58.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,563,945 | 0.4% | 59.2% |
| NOP LOAD_GLOBAL_MODULE | 1,556,780 | 0.4% | 59.5% |
| COPY_FREE_VARS RESUME_CHECK | 1,552,109 | 0.4% | 59.9% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,547,669 | 0.4% | 60.2% |
| LOAD_DEREF LOAD_FAST | 1,547,669 | 0.4% | 60.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,514,920 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,505,478 | 0.3% | 61.3% |
| POP_TOP RETURN_CONST | 1,488,847 | 0.3% | 61.6% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,480,469 | 0.3% | 62.0% |
| UNARY_INVERT BINARY_OP | 1,477,632 | 0.3% | 62.3% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,465,589 | 0.3% | 62.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,463,929 | 0.3% | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,463,923 | 0.3% | 63.3% |
| LOAD_FAST BUILD_TUPLE | 1,455,400 | 0.3% | 63.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,416,544 | 0.3% | 64.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,410,431 | 0.3% | 64.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,397,385 | 0.3% | 64.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,392,483 | 0.3% | 65.0% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,254 | 0.3% | 65.3% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,363,972 | 0.3% | 65.6% |
| POP_TOP LOAD_CONST | 1,361,460 | 0.3% | 65.9% |
| LOAD_FAST GET_ITER | 1,314,194 | 0.3% | 66.2% |
| RETURN_VALUE POP_TOP | 1,307,227 | 0.3% | 66.5% |
| GET_ITER FOR_ITER_LIST | 1,299,578 | 0.3% | 66.8% |
| POP_TOP NOP | 1,298,819 | 0.3% | 67.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,294,134 | 0.3% | 67.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,290,679 | 0.3% | 67.7% |
| BINARY_OP STORE_FAST | 1,266,836 | 0.3% | 68.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,258,712 | 0.3% | 68.3% |
| LOAD_CONST LOAD_FAST | 1,255,624 | 0.3% | 68.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,242,165 | 0.3% | 68.8% |
| ENTER_EXECUTOR CALL | 1,230,930 | 0.3% | 69.1% |
| RESUME_CHECK NOP | 1,186,120 | 0.3% | 69.4% |
| LOAD_FAST TO_BOOL | 1,175,255 | 0.3% | 69.7% |
| LOAD_FAST_LOAD_FAST CALL | 1,157,374 | 0.3% | 69.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 1,151,113 | 0.3% | 70.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,115,498 | 0.3% | 70.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,113,620 | 0.3% | 70.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,102,336 | 0.3% | 71.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,171,454 | 99.1% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 935,986 | 65.1% |
| RETURN_VALUE | 430,669 | 30.0% |
| LOAD_GLOBAL_MODULE | 61,927 | 4.3% |
| CALL | 4,320 | 0.3% |
| ENTER_EXECUTOR | 4,268 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,181 | 69.7% |
| STORE_FAST | 434,989 | 30.3% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 20,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,640 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 432,000 | 90.2% |
| LOAD_CONST | 46,631 | 9.7% |
| BINARY_SUBSCR | 222 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.2% |
| STORE_FAST | 46,631 | 9.7% |
| BINARY_SUBSCR | 222 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,311 | 88.8% |
| LOAD_ATTR_MODULE | 3,840 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,151 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,327 | 48.4% |
| CALL | 20,647 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,595 | 16.4% |
| LOAD_ATTR | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,607 | 77.9% |
| RETURN_CONST | 7,687 | 13.1% |
| LOAD_FAST | 5,280 | 9.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 4,320 | 50.0% |
| LOAD_FAST | 4,320 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 912,218 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 912,218 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 21,120 | 50.6% |
| LOAD_FAST | 20,640 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,200 | 74.7% |
| BUILD_STRING | 10,560 | 25.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,314,194 | 73.2% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.1% |
| CALL_BUILTIN_CLASS | 28,800 | 1.6% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,299,578 | 72.4% |
| LOAD_FAST_AND_CLEAR | 440,736 | 24.6% |
| FOR_ITER_RANGE | 23,640 | 1.3% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,097,091 | 87.5% |
| RETURN_CONST | 724,450 | 7.8% |
| YIELD_VALUE | 432,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 44,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 28,320 | 64.1% |
| STORE_FAST | 10,560 | 23.9% |
| LOAD_FAST | 5,280 | 12.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,113,731 | 42.2% |
| POP_TOP | 1,298,819 | 17.6% |
| RESUME_CHECK | 1,186,120 | 16.1% |
| POP_JUMP_IF_FALSE | 1,092,413 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 436,954 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,350,111 | 58.9% |
| LOAD_GLOBAL_MODULE | 1,556,780 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 636,886 | 8.6% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.9% |
| LOAD_CONST | 396,960 | 5.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 25,991 | 67.6% |
| COPY | 8,640 | 22.5% |
| POP_TOP | 3,840 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 25,991 | 67.6% |
| RERAISE | 8,640 | 22.5% |
| JUMP_FORWARD | 3,840 | 10.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,325,160 | 27.9% |
| RESUME_CHECK | 5,184,960 | 27.2% |
| CALL | 1,759,109 | 9.2% |
| RETURN_VALUE | 1,307,227 | 6.8% |
| POP_JUMP_IF_FALSE | 1,290,679 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,169,644 | 32.3% |
| ENTER_EXECUTOR | 5,810,337 | 30.4% |
| RETURN_CONST | 1,488,847 | 7.8% |
| LOAD_CONST | 1,361,460 | 7.1% |
| NOP | 1,298,819 | 6.8% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 30,311 | 78.8% |
| RERAISE | 4,320 | 11.2% |
| CALL_KW | 3,840 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,311 | 78.8% |
| WITH_EXCEPT_START | 4,320 | 11.2% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,959,704 | 44.4% |
| LOAD_ATTR_MODULE | 1,397,385 | 31.7% |
| LOAD_ATTR | 961,418 | 21.8% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,693,990 | 61.1% |
| CALL | 812,885 | 18.4% |
| LOAD_FAST_LOAD_FAST | 614,512 | 13.9% |
| LOAD_CONST | 236,002 | 5.3% |
| CALL_PY_EXACT_ARGS | 37,440 | 0.8% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,320 | 31.0% |
| RETURN_VALUE | 4,320 | 31.0% |
| LOAD_FAST | 4,320 | 31.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 6.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,637,710 | 47.7% |
| CALL | 2,011,720 | 11.1% |
| RETURN_VALUE | 1,722,791 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,363,972 | 7.5% |
| CALL_FUNCTION_EX | 948,894 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 8,097,091 | 44.8% |
| STORE_FAST | 1,957,016 | 10.8% |
| RETURN_VALUE | 1,722,791 | 9.5% |
| POP_TOP | 1,307,227 | 7.2% |
| LOAD_FAST_LOAD_FAST | 1,034,920 | 5.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,693 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 7 | 0.0% |
| LOAD_FAST | 6 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,175,255 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,854 | 3.3% |
| TO_BOOL | 1,055 | 0.1% |
| RETURN_VALUE | 11 | 0.0% |
| LOAD_ATTR | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 662,000 | 54.4% |
| POP_JUMP_IF_FALSE | 553,120 | 45.5% |
| TO_BOOL | 1,055 | 0.1% |
| TO_BOOL_BOOL | 4 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 1 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,034,920 | 70.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 442,712 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,477,632 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 240,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 240,840 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 4,320 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,326,116 | 53.9% |
| UNARY_INVERT | 1,477,632 | 23.9% |
| POP_JUMP_IF_FALSE | 1,034,920 | 16.8% |
| LOAD_ATTR | 231,916 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,512,552 | 40.7% |
| STORE_FAST | 1,266,836 | 20.5% |
| UNARY_INVERT | 1,034,920 | 16.8% |
| TO_BOOL_INT | 1,034,920 | 16.8% |
| BUILD_TUPLE | 221,356 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 440,736 | 33.4% |
| JUMP_FORWARD | 430,669 | 32.6% |
| LOAD_FAST | 221,849 | 16.8% |
| POP_TOP | 208,820 | 15.8% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 443,149 | 33.6% |
| SWAP | 440,736 | 33.4% |
| STORE_FAST | 431,629 | 32.7% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 438,349 | 33.3% |
| BUILD_TUPLE | 432,000 | 32.8% |
| LOAD_FAST | 396,960 | 30.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 870,829 | 66.2% |
| BUILD_TUPLE | 432,000 | 32.8% |
| STORE_FAST | 12,960 | 1.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,640 | 66.2% |
| FORMAT_SIMPLE | 10,560 | 33.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 66.2% |
| RETURN_VALUE | 10,560 | 33.8% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,455,400 | 42.8% |
| LOAD_FAST_LOAD_FAST | 870,240 | 25.6% |
| BUILD_MAP | 432,000 | 12.7% |
| RETURN_VALUE | 384,000 | 11.3% |
| BINARY_OP | 221,356 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,035,880 | 30.5% |
| YIELD_VALUE | 864,000 | 25.4% |
| BUILD_MAP | 432,000 | 12.7% |
| STORE_FAST | 384,000 | 11.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 11.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,993,566 | 21.3% |
| ENTER_EXECUTOR | 1,230,930 | 13.2% |
| LOAD_FAST_LOAD_FAST | 1,157,374 | 12.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,085,013 | 11.6% |
| BUILD_TUPLE | 1,035,880 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,763,656 | 29.6% |
| RETURN_VALUE | 2,011,720 | 21.5% |
| POP_TOP | 1,759,109 | 18.8% |
| LOAD_FAST | 871,998 | 9.3% |
| TO_BOOL_BOOL | 548,353 | 5.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,254 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,894 | 52.4% |
| RESUME_CHECK | 401,280 | 22.2% |
| CALL_BUILTIN_CLASS | 384,000 | 21.2% |
| POP_TOP | 71,520 | 4.0% |
| STORE_FAST | 4,320 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 291,450 | 98.5% |
| ENTER_EXECUTOR | 4,320 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 243,860 | 82.4% |
| LOAD_FAST | 21,600 | 7.3% |
| RETURN_VALUE | 15,840 | 5.4% |
| STORE_FAST | 10,560 | 3.6% |
| PUSH_EXC_INFO | 3,840 | 1.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 494,338 | 99.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,043 | 0.8% |
| COMPARE_OP | 473 | 0.1% |
| COMPARE_OP_INT | 116 | 0.0% |
| LOAD_GLOBAL_MODULE | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 498,342 | 99.9% |
| COMPARE_OP | 473 | 0.1% |
| COMPARE_OP_INT | 156 | 0.0% |
| COMPARE_OP_STR | 4 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,463,923 | 100.0% |
| LOAD_ATTR | 6 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,463,929 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,560 | 50.0% |
| BINARY_SUBSCR_DICT | 10,560 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 21,120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,512,552 | 43.3% |
| STORE_FAST | 1,972,320 | 34.0% |
| LOAD_CONST | 825,600 | 14.2% |
| LOAD_FAST | 439,569 | 7.6% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,512,552 | 43.3% |
| STORE_FAST | 1,972,800 | 34.0% |
| STORE_FAST_STORE_FAST | 820,320 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 428,996 | 7.4% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,034,920 | 66.7% |
| CALL_ALLOC_AND_ENTER_INIT | 430,669 | 27.7% |
| CACHE | 82,080 | 5.3% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,552,109 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,821 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,214 | 66.7% |
| RETURN_CONST | 20,647 | 31.9% |
| LOAD_GLOBAL_MODULE | 960 | 1.5% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,960 | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 422,880 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,810,337 | 71.4% |
| POP_JUMP_IF_NOT_NONE | 801,940 | 9.9% |
| LIST_APPEND | 624,190 | 7.7% |
| STORE_FAST_STORE_FAST | 432,000 | 5.3% |
| CALL_LIST_APPEND | 221,356 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,888,000 | 47.8% |
| CALL | 1,230,930 | 15.1% |
| LOAD_FAST | 868,739 | 10.7% |
| CALL_PY_WITH_DEFAULTS | 652,251 | 8.0% |
| LOAD_ATTR_PROPERTY | 615,098 | 7.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 952,800 | 97.5% |
| SWAP | 10,560 | 1.1% |
| GET_ITER | 8,640 | 0.9% |
| LOAD_FAST | 4,320 | 0.4% |
| FOR_ITER | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 516,480 | 52.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 436,320 | 44.7% |
| SWAP | 10,560 | 1.1% |
| RETURN_CONST | 8,640 | 0.9% |
| LOAD_GLOBAL_MODULE | 4,320 | 0.4% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 24,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,480 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 24,480 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,640 | 60.0% |
| LOAD_FAST | 12,960 | 37.7% |
| LOAD_GLOBAL_MODULE | 813 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,413 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,320,000 | 75.7% |
| POP_TOP | 864,894 | 15.2% |
| ENTER_EXECUTOR | 432,000 | 7.6% |
| LIST_APPEND | 84,480 | 1.5% |
| STORE_FAST_STORE_FAST | 4,320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 4,752,000 | 83.3% |
| FOR_ITER | 952,800 | 16.7% |
| FOR_ITER_LIST | 779 | 0.0% |
| LOAD_FAST | 386 | 0.0% |
| FOR_ITER_RANGE | 282 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 920,045 | 66.4% |
| POP_TOP | 451,749 | 32.6% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 896,407 | 64.7% |
| BUILD_LIST | 430,669 | 31.1% |
| POP_EXCEPT | 25,991 | 1.9% |
| LOAD_GLOBAL_MODULE | 18,727 | 1.4% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 402,834 | 56.8% |
| LOAD_ATTR | 221,356 | 31.2% |
| BINARY_SUBSCR_STR_INT | 84,480 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 624,190 | 88.1% |
| JUMP_BACKWARD | 84,480 | 11.9% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 209,780 | 50.1% |
| RETURN_VALUE | 208,820 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 209,300 | 50.0% |
| STORE_FAST | 208,820 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,619,289 | 80.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,416,544 | 17.2% |
| LOAD_GLOBAL_MODULE | 119,607 | 1.4% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,893 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,149 | 33.9% |
| STORE_SUBSCR_DICT | 1,034,920 | 12.5% |
| PUSH_NULL | 961,418 | 11.7% |
| POP_JUMP_IF_NOT_NONE | 929,351 | 11.3% |
| RETURN_VALUE | 632,086 | 7.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,027,079 | 26.0% |
| LOAD_CONST | 2,902,588 | 24.9% |
| POP_TOP | 1,361,460 | 11.7% |
| POP_JUMP_IF_FALSE | 717,941 | 6.2% |
| LOAD_ATTR_METHOD_NO_DICT | 550,769 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,902,588 | 24.9% |
| CALL | 1,993,566 | 17.1% |
| COMPARE_OP_INT | 1,687,184 | 14.5% |
| LOAD_FAST | 1,255,624 | 10.8% |
| COPY | 825,600 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,547,669 | 97.4% |
| STORE_DEREF | 20,640 | 1.3% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.3% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,547,669 | 97.4% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 2.6% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,612,165 | 21.1% |
| STORE_FAST | 9,576,133 | 12.2% |
| POP_JUMP_IF_FALSE | 6,275,052 | 8.0% |
| POP_TOP | 6,169,644 | 7.8% |
| NOP | 4,350,111 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,680,369 | 22.5% |
| RETURN_VALUE | 8,637,710 | 11.0% |
| LOAD_ATTR | 6,619,289 | 8.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,999,995 | 7.6% |
| CALL_PY_EXACT_ARGS | 4,342,354 | 5.5% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 440,736 | 66.6% |
| LOAD_FAST_AND_CLEAR | 221,356 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 440,736 | 66.6% |
| LOAD_FAST_AND_CLEAR | 221,356 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 66.1% |
| POP_JUMP_IF_NONE | 209,313 | 32.0% |
| LOAD_ATTR_CLASS | 12,414 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 66.1% |
| LOAD_GLOBAL_MODULE | 209,313 | 32.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,414 | 1.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,322,820 | 20.3% |
| LOAD_FAST_LOAD_FAST | 1,514,920 | 13.3% |
| POP_JUMP_IF_FALSE | 1,294,134 | 11.3% |
| LOAD_SUPER_ATTR_METHOD | 1,045,480 | 9.2% |
| RETURN_VALUE | 1,034,920 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,707,356 | 23.7% |
| LOAD_FAST_LOAD_FAST | 1,514,920 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,505,478 | 13.2% |
| CALL | 1,157,374 | 10.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,034,920 | 9.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 44.4% |
| RESUME_CHECK | 40 | 22.2% |
| POP_JUMP_IF_FALSE | 40 | 22.2% |
| POP_JUMP_IF_TRUE | 9 | 5.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 92 | 51.1% |
| LOAD_ATTR | 44 | 24.4% |
| LOAD_GLOBAL_BUILTIN | 40 | 22.2% |
| LOAD_FAST | 4 | 2.2% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 82,560 | 80.0% |
| CALL_PY_EXACT_ARGS | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 82,560 | 80.0% |
| RESUME_CHECK | 20,640 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 4,582,392 | 29.0% |
| TO_BOOL_BOOL | 3,871,719 | 24.5% |
| COMPARE_OP_INT | 3,016,444 | 19.1% |
| CONTAINS_OP | 1,463,929 | 9.3% |
| COMPARE_OP_STR | 1,113,620 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,275,052 | 39.7% |
| RETURN_CONST | 2,567,421 | 16.2% |
| LOAD_FAST_LOAD_FAST | 1,294,134 | 8.2% |
| POP_TOP | 1,290,679 | 8.2% |
| LOAD_GLOBAL_MODULE | 1,242,165 | 7.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 880,490 | 95.2% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.4% |
| LOAD_ATTR | 21,120 | 2.3% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 248,980 | 26.9% |
| NOP | 237,140 | 25.6% |
| LOAD_FAST_CHECK | 209,313 | 22.6% |
| LOAD_FAST | 192,603 | 20.8% |
| RETURN_CONST | 18,240 | 2.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,859,937 | 45.3% |
| LOAD_ATTR | 929,351 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 853,811 | 20.8% |
| RETURN_VALUE | 403,314 | 9.8% |
| LOAD_DEREF | 41,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,612,557 | 39.3% |
| RETURN_CONST | 929,603 | 22.7% |
| ENTER_EXECUTOR | 801,940 | 19.5% |
| NOP | 436,954 | 10.7% |
| LOAD_CONST | 208,820 | 5.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,392,483 | 66.9% |
| TO_BOOL | 662,000 | 31.8% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,270 | 0.4% |
| COMPARE_OP_INT | 2,172 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,265 | 34.3% |
| LOAD_FAST_LOAD_FAST | 664,876 | 32.0% |
| RETURN_CONST | 559,643 | 26.9% |
| LOAD_GLOBAL_MODULE | 55,743 | 2.7% |
| RETURN_VALUE | 46,631 | 2.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,320 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 8,640 | 66.7% |
| POP_JUMP_IF_TRUE | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,320 | 50.0% |
| COPY | 4,320 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,567,421 | 34.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,882,516 | 25.0% |
| POP_TOP | 1,488,847 | 19.8% |
| POP_JUMP_IF_NOT_NONE | 929,603 | 12.3% |
| POP_JUMP_IF_TRUE | 559,643 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,325,160 | 70.7% |
| EXIT_INIT_CHECK | 912,218 | 12.1% |
| INTERPRETER_EXIT | 724,450 | 9.6% |
| TO_BOOL_BOOL | 496,939 | 6.6% |
| STORE_FAST | 47,591 | 0.6% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 28,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,320 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,926 | 57.1% |
| LOAD_FAST_LOAD_FAST | 14,880 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 19.5% |
| STORE_ATTR | 640 | 1.0% |
| SWAP | 13 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,646 | 13.0% |
| LOAD_CONST | 8,645 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 4,320 | 6.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_ATTR_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |
| LOAD_FAST | 20,640 | 20.0% |
| LOAD_DEREF | 20,640 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,752,000 | 21.7% |
| CALL | 2,763,656 | 12.6% |
| COPY | 1,972,800 | 9.0% |
| RETURN_VALUE | 1,957,016 | 8.9% |
| BINARY_OP | 1,266,836 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,576,133 | 43.7% |
| JUMP_BACKWARD | 4,320,000 | 19.7% |
| NOP | 3,113,731 | 14.2% |
| COPY | 1,972,320 | 9.0% |
| JUMP_FORWARD | 920,045 | 4.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 516,480 | 53.9% |
| FOR_ITER_LIST | 432,000 | 45.0% |
| COPY | 10,560 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 432,000 | 45.0% |
| GET_ITER | 432,000 | 45.0% |
| LOAD_FAST | 84,480 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 10,560 | 1.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,723,105 | 46.0% |
| COPY | 820,320 | 21.9% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 21.8% |
| STORE_FAST_STORE_FAST | 384,000 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,258,712 | 33.6% |
| LOAD_FAST_LOAD_FAST | 836,873 | 22.4% |
| STORE_FAST | 816,000 | 21.8% |
| ENTER_EXECUTOR | 432,000 | 11.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.3% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 440,736 | 20.0% |
| BUILD_LIST | 440,736 | 20.0% |
| ENTER_EXECUTOR | 430,176 | 19.5% |
| BINARY_OP_ADD_INT | 429,003 | 19.5% |
| LOAD_FAST | 229,953 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 451,309 | 20.5% |
| STORE_FAST | 440,736 | 20.0% |
| BUILD_LIST | 440,736 | 20.0% |
| FOR_ITER_LIST | 430,176 | 19.5% |
| STORE_ATTR_INSTANCE_VALUE | 428,996 | 19.5% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,888,000 | 75.0% |
| BUILD_TUPLE | 864,000 | 16.7% |
| STORE_FAST_LOAD_FAST | 432,000 | 8.3% |
| CALL_STR_1 | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,752,000 | 91.6% |
| INTERPRETER_EXIT | 432,960 | 8.4% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 221,849 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 221,849 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 817,316 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 429,003 | 51.6% |
| STORE_FAST | 384,000 | 46.2% |
| BINARY_SLICE | 13,920 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,320 | 0.5% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 209,313 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,433 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,832 | 79.6% |
| LOAD_CONST | 46,631 | 18.7% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 245,463 | 98.3% |
| CALL_BUILTIN_CLASS | 4,320 | 1.7% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 74,880 | 87.6% |
| LOAD_CONST | 10,560 | 12.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 74,880 | 87.6% |
| CONVERT_VALUE | 10,560 | 12.4% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 66.7% |
| LOAD_FAST_LOAD_FAST | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 66.7% |
| STORE_FAST | 4,320 | 33.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 84,480 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 24,480 | 85.0% |
| JUMP_FORWARD | 4,320 | 15.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 451,309 | 49.5% |
| LOAD_FAST | 435,949 | 47.8% |
| CALL | 24,960 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 481,549 | 52.8% |
| COPY_FREE_VARS | 430,669 | 47.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,000 | 83.1% |
| LOAD_CONST | 4,800 | 8.3% |
| BINARY_OP_ADD_INT | 4,320 | 7.5% |
| PUSH_NULL | 598 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,402 | 92.4% |
| POP_TOP | 4,320 | 7.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 58.9% |
| LOAD_FAST | 235,369 | 36.1% |
| LOAD_CONST | 11,040 | 1.7% |
| LOAD_GLOBAL_BUILTIN | 7,680 | 1.2% |
| CALL_LEN | 4,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 605,849 | 92.9% |
| GET_ITER | 28,800 | 4.4% |
| LOAD_FAST | 12,960 | 2.0% |
| CALL_BUILTIN_CLASS | 4,320 | 0.7% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 756,656 | 57.5% |
| LOAD_CONST | 326,900 | 24.8% |
| LOAD_FAST_LOAD_FAST | 129,712 | 9.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 61,016 | 4.6% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 474,428 | 36.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 404,873 | 30.8% |
| TO_BOOL_BOOL | 319,700 | 24.3% |
| UNPACK_SEQUENCE_TUPLE | 61,016 | 4.6% |
| POP_TOP | 10,907 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 387,840 | 45.8% |
| BUILD_TUPLE | 384,000 | 45.3% |
| CALL | 48,602 | 5.7% |
| LOAD_FAST_CHECK | 12,414 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 785,760 | 92.7% |
| RETURN_VALUE | 61,016 | 7.2% |
| LOAD_FAST | 960 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 88.9% |
| LOAD_FAST | 10,560 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 84,480 | 88.9% |
| LOAD_FAST | 10,560 | 11.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,047,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,047,880 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,993 | 93.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,352 | 87.1% |
| CALL_PY_EXACT_ARGS | 24,960 | 8.4% |
| LOAD_FAST | 4,320 | 1.5% |
| CALL_BUILTIN_CLASS | 4,320 | 1.5% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 1.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 221,356 | 96.2% |
| LOAD_FAST | 8,640 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 221,356 | 96.2% |
| LOAD_GLOBAL_MODULE | 8,640 | 3.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,465,589 | 99.9% |
| LOAD_CONST | 960 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 294 | 0.0% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,034,920 | 70.6% |
| STORE_FAST | 430,970 | 29.4% |
| TO_BOOL_NONE | 960 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,480 | 85.0% |
| BUILD_TUPLE | 4,320 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20,160 | 70.0% |
| LOAD_FAST | 8,640 | 30.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,102,336 | 93.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,430 | 6.2% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 538,811 | 45.8% |
| STORE_FAST | 432,000 | 36.7% |
| LOAD_FAST | 63,840 | 5.4% |
| CALL_BUILTIN_FAST | 61,016 | 5.2% |
| RETURN_VALUE | 38,748 | 3.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 667,816 | 92.1% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,608 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 689,424 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,619,907 | 45.8% |
| LOAD_FAST | 4,342,354 | 43.0% |
| LOAD_FAST_LOAD_FAST | 446,880 | 4.4% |
| LOAD_SUPER_ATTR_METHOD | 430,669 | 4.3% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,056,412 | 99.7% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 931,327 | 38.1% |
| ENTER_EXECUTOR | 652,251 | 26.7% |
| LOAD_ATTR_MODULE | 430,669 | 17.6% |
| LOAD_FAST | 283,756 | 11.6% |
| LOAD_CONST | 80,622 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,410,431 | 57.7% |
| COPY_FREE_VARS | 1,034,920 | 42.3% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 88.9% |
| YIELD_VALUE | 960 | 11.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 436,320 | 99.8% |
| LOAD_FAST | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 436,320 | 99.8% |
| LOAD_FAST | 960 | 0.2% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,687,184 | 55.9% |
| LOAD_ATTR_INSTANCE_VALUE | 867,461 | 28.7% |
| LOAD_FAST | 432,000 | 14.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,016,444 | 99.9% |
| POP_JUMP_IF_TRUE | 2,172 | 0.1% |
| COMPARE_OP | 116 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,094,046 | 95.7% |
| LOAD_CONST | 44,640 | 3.9% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,113,620 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,270 | 0.7% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,752,000 | 99.8% |
| GET_ITER | 8,640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,752,000 | 99.8% |
| POP_TOP | 8,640 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,299,578 | 75.1% |
| SWAP | 430,176 | 24.9% |
| JUMP_BACKWARD | 779 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 645,449 | 37.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 442,712 | 25.6% |
| STORE_FAST_LOAD_FAST | 432,000 | 25.0% |
| LOAD_FAST | 209,313 | 12.1% |
| RETURN_CONST | 858 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 23,640 | 98.8% |
| JUMP_BACKWARD | 282 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,902 | 99.9% |
| LOAD_FAST | 20 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,640 | 90.0% |
| LOAD_FAST | 960 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,600 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 61,016 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,282 | 81.9% |
| LOAD_FAST_CHECK | 12,414 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,680,369 | 90.0% |
| LOAD_FAST_LOAD_FAST | 1,505,478 | 7.7% |
| COPY | 428,996 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 18,071 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,458,552 | 22.7% |
| LOAD_FAST | 2,991,388 | 15.2% |
| TO_BOOL_BOOL | 1,563,945 | 8.0% |
| CONTAINS_OP | 1,463,923 | 7.5% |
| LOAD_ATTR | 1,416,544 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,944 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,032 | 39.8% |
| CALL | 111,482 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,430 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,458,552 | 87.2% |
| LOAD_FAST | 504,484 | 9.9% |
| LOAD_ATTR | 62,895 | 1.2% |
| LOAD_ATTR_SLOT | 62,880 | 1.2% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,098,082 | 41.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,102,336 | 21.6% |
| CALL | 1,085,013 | 21.2% |
| LOAD_CONST | 550,769 | 10.8% |
| LOAD_FAST_LOAD_FAST | 253,090 | 5.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,999,995 | 70.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,065,949 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,034,920 | 12.1% |
| BINARY_SUBSCR | 432,000 | 5.0% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,619,907 | 53.9% |
| LOAD_FAST | 2,336,663 | 27.3% |
| CALL_PY_WITH_DEFAULTS | 931,327 | 10.9% |
| LOAD_FAST_LOAD_FAST | 508,800 | 5.9% |
| LOAD_CONST | 94,542 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,938,835 | 100.0% |
| LOAD_ATTR | 86 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,397,385 | 72.1% |
| CALL_PY_WITH_DEFAULTS | 430,669 | 22.2% |
| STORE_DEREF | 41,280 | 2.1% |
| LOAD_CONST | 26,400 | 1.4% |
| LOAD_FAST | 20,640 | 1.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,065,640 | 70.6% |
| LOAD_FAST_LOAD_FAST | 442,712 | 29.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,034,920 | 68.6% |
| UNARY_INVERT | 442,712 | 29.4% |
| RETURN_VALUE | 10,560 | 0.7% |
| LOAD_CONST | 10,560 | 0.7% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 615,098 | 68.6% |
| LOAD_FAST | 259,387 | 28.9% |
| RETURN_VALUE | 20,640 | 2.3% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 887,126 | 99.0% |
| TO_BOOL_BOOL | 8,960 | 1.0% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 62,880 | 85.6% |
| CALL_BUILTIN_FAST | 10,560 | 14.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,098,589 | 51.0% |
| LOAD_FAST | 1,068,040 | 17.6% |
| NOP | 636,886 | 10.5% |
| STORE_FAST | 603,101 | 9.9% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,966,588 | 48.8% |
| LOAD_DEREF | 1,547,669 | 25.5% |
| CALL_ISINSTANCE | 1,047,880 | 17.3% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 6.5% |
| LOAD_GLOBAL_MODULE | 36,960 | 0.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,642,801 | 27.8% |
| RESUME_CHECK | 2,426,643 | 18.5% |
| NOP | 1,556,780 | 11.9% |
| POP_JUMP_IF_FALSE | 1,242,165 | 9.5% |
| LOAD_GLOBAL_MODULE | 1,151,113 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,326,116 | 25.4% |
| LOAD_FAST_LOAD_FAST | 2,322,820 | 17.7% |
| LOAD_ATTR_MODULE | 1,938,835 | 14.8% |
| LOAD_FAST | 1,849,678 | 14.1% |
| LOAD_GLOBAL_MODULE | 1,151,113 | 8.8% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 67,200 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,480,469 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,045,480 | 70.6% |
| CALL_PY_EXACT_ARGS | 430,669 | 29.1% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,056,412 | 34.2% |
| CACHE | 9,171,454 | 31.2% |
| FOR_ITER_GEN | 4,752,000 | 16.1% |
| COPY_FREE_VARS | 1,552,109 | 5.3% |
| CALL_PY_WITH_DEFAULTS | 1,410,431 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,612,165 | 56.4% |
| POP_TOP | 5,184,960 | 17.6% |
| LOAD_GLOBAL_BUILTIN | 3,098,589 | 10.5% |
| LOAD_GLOBAL_MODULE | 2,426,643 | 8.2% |
| NOP | 1,186,120 | 4.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,431,150 | 69.2% |
| LOAD_FAST_LOAD_FAST | 626,989 | 17.8% |
| SWAP | 428,996 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,882,516 | 53.6% |
| LOAD_FAST | 681,963 | 19.4% |
| LOAD_GLOBAL_MODULE | 590,029 | 16.8% |
| LOAD_CONST | 160,315 | 4.6% |
| LOAD_FAST_LOAD_FAST | 96,960 | 2.8% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,880 | 85.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 14.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,440 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 1,034,920 | 93.7% |
| LOAD_FAST | 34,485 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.3% |
| CALL | 7,680 | 0.7% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,038,212 | 94.0% |
| RETURN_CONST | 24,480 | 2.2% |
| LOAD_GLOBAL_MODULE | 20,640 | 1.9% |
| LOAD_CONST | 20,640 | 1.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,563,945 | 28.4% |
| CALL_ISINSTANCE | 1,047,880 | 19.0% |
| RETURN_VALUE | 769,984 | 14.0% |
| CALL | 548,353 | 10.0% |
| LOAD_FAST | 541,031 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,871,719 | 70.3% |
| POP_JUMP_IF_TRUE | 1,392,483 | 25.3% |
| UNARY_NOT | 240,840 | 4.4% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,512,552 | 54.8% |
| LOAD_FAST | 1,034,920 | 22.6% |
| BINARY_OP | 1,034,920 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,582,392 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 439,309 | 93.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 471,469 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,786 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,386 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 61,016 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 61,016 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 442,712 | 25.6% |
| FOR_ITER | 436,320 | 25.2% |
| LOAD_FAST_CHECK | 432,000 | 25.0% |
| CALL_BUILTIN_FAST | 404,873 | 23.4% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,723,105 | 99.7% |
| LOAD_FAST | 5,280 | 0.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 50.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 50.0% |
| LOAD_CONST | 960 | 50.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 960 | 100.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 65.6% |
| COPY | 251 | 34.3% |
| TO_BOOL | 1 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 65.6% |
| POP_JUMP_IF_FALSE | 252 | 34.4% |


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
| specialization.deferred |       478631 | 69.3% |
|          hit |       211680 | 30.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 222 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 222 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        22566 | 2.0% |
|          hit |      1103972 | 98.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7 | 3.4% |
| Failure | 200 | 96.6% |

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
| specialization.deferred |      1215120 | 10.2% |
|          hit |     10739901 | 89.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5 | 0.5% |
| Failure | 1,055 | 99.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 333 | 31.6% |
| sequence | 222 | 21.0% |
| tuple | 220 | 20.9% |
| set | 200 | 19.0% |
| other | 80 | 7.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6173569 | 79.2% |
|          hit |      1619348 | 20.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 47 | 2.1% |
| Failure | 2,223 | 97.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,131 | 50.9% |
| or | 661 | 29.7% |
| remainder | 231 | 10.4% |
| add different types | 160 | 7.2% |
| add other | 40 | 1.8% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      9328759 | 29.9% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21886843 | 70.1% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 129 | 1.4% |
| Failure | 9,143 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,534 | 27.7% |
| cfunc noargs | 1,819 | 19.9% |
| class no vectorcall | 1,288 | 14.1% |
| meth descr varargs keywords | 841 | 9.2% |
| class mutable | 444 | 4.9% |
| cfunc varargs keywords | 364 | 4.0% |
| other | 360 | 3.9% |
| cfunc varargs | 320 | 3.5% |
| bound method | 293 | 3.2% |
| operator wrapper | 240 | 2.6% |
| meth descr method fastcall keywords | 200 | 2.2% |
| cmethod | 200 | 2.2% |
| wrong number arguments | 160 | 1.7% |
| method wrapper | 80 | 0.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       498342 | 10.7% |
| specialization.deopt |          116 | 0.0% |
|          hit |      4154554 | 89.1% |
|         miss |         7188 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 21.4% |
| Failure | 589 | 78.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 341 | 57.9% |
| float long | 168 | 28.5% |
| big int | 80 | 13.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 13.0% |
|          hit |      6524695 | 87.0% |

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
| specialization.deferred |      8243675 | 17.8% |
| specialization.deopt |         4195 | 0.0% |
|          hit |     37885855 | 81.7% |
|         miss |       230184 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,374 | 41.6% |
| Failure | 6,145 | 58.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,418 | 23.1% |
| not managed dict | 1,318 | 21.4% |
| shadowed | 1,243 | 20.2% |
| non overriding descriptor | 588 | 9.6% |
| class attr descriptor | 360 | 5.9% |
| metaclass attribute | 280 | 4.6% |
| class method obj | 280 | 4.6% |
| has managed dict | 240 | 3.9% |
| non object slot | 160 | 2.6% |
| class attr simple | 138 | 2.2% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           48 | 0.0% |
| specialization.deopt |           26 | 0.0% |
|          hit |     19165443 | 100.0% |
|         miss |         4632 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 158 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1547669 | 100.0% |


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
| specialization.deferred |        65771 | 1.8% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3438763 | 94.1% |
|         miss |       148120 | 4.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,788 | 81.3% |
| Failure | 640 | 18.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 400 | 62.5% |
| class attr simple | 160 | 25.0% |
| no dict | 80 | 12.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2605401 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 239,029,550 | 54.9% |
| Not specialized | 56,051,971 | 12.9% |
| Specialized | 140,269,216 | 32.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 18,446,744,073,709,551,615 | 100.0% |
| CALL | 9,328,759 | 0.0% |
| LOAD_ATTR | 8,243,675 | 0.0% |
| BINARY_OP | 6,173,569 | 0.0% |
| TO_BOOL | 1,215,120 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| COMPARE_OP | 498,342 | 0.0% |
| BINARY_SUBSCR | 478,631 | 0.0% |
| STORE_ATTR | 65,771 | 0.0% |
| STORE_SUBSCR | 22,566 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,324 | 40.6% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,740 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| COMPARE_OP_INT | 7,188 | 1.8% |
| LOAD_GLOBAL_MODULE | 4,632 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
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
| Calls to PyEval_EvalDefault | 9,258,814 | 31.4% |
| Calls to Python functions inlined | 20,193,601 | 68.6% |
| Calls via PyEval_EvalFrame (total) | 9,258,814 | 31.4% |
| Calls via PyEval_EvalFrame (vector) | 8,820,574 | 29.9% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,820,574 | 29.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.6% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 533,248 | 1.8% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 25,725,259 | 87.3% |
| Frame objects created | 38,513 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 16,275,659 | 43.5% |
| Frees to freelist | 16,277,176 |  |
| Allocations | 21,151,938 | 56.5% |
| Allocations to 512 bytes | 20,939,893 | 55.9% |
| Allocations to 4 kbytes | 86,264 | 0.2% |
| Allocations over 4 kbytes | 125,781 | 0.3% |
| Frees | 22,450,641 |  |
| New values | 65,280 |  |
| Interpreter increfs | 174,528,677 | 71.4% |
| Interpreter decrefs | 189,649,872 | 68.2% |
| Increfs | 69,973,229 | 28.6% |
| Decrefs | 88,511,972 | 31.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 10,234,648 |  |
| Method cache misses | 32,507 |  |
| Method cache collisions | 42,294 |  |
| Method cache dunder hits | 9,108,699 |  |
| Method cache dunder misses | 9,787 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 15 | 360 | 103,964 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 335,739 |  |
| Traces created | 199 | 0.1% |
| Traces executed | 8,141,043 |  |
| Uops executed | 96,535,957 | 11 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 59 | 29.6% |
| <= 32 | 40 | 20.1% |
| <= 64 | 40 | 20.1% |
| <= 128 | 60 | 30.2% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 59 | 29.6% |
| <= 32 | 80 | 40.2% |
| <= 64 | 8 | 4.0% |
| <= 128 | 52 | 26.1% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 768,000 | 9.4% |
| <= 8 | 1,756,010 | 21.6% |
| <= 16 | 4,533,241 | 55.7% |
| <= 32 | 830,299 | 10.2% |
| <= 64 | 16 | 0.0% |
| <= 128 | 253,421 | 3.1% |
| <= 256 | 11 | 0.0% |
| <= 512 | 3 | 0.0% |
| <= 1024 | 2 | 0.0% |
| <= 2048 | 6 | 0.0% |
| <= 4096 | 10 | 0.0% |
| <= 8192 | 24 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 23,373,577 | 24.2% | 24.2% |
| LOAD_FAST | 11,407,648 | 11.8% | 36.0% |
| _EXIT_TRACE | 8,141,043 | 8.4% | 44.5% |
| _POP_JUMP_IF_TRUE | 6,935,394 | 7.2% | 51.6% |
| _ITER_CHECK_LIST | 6,225,533 | 6.4% | 58.1% |
| _IS_ITER_EXHAUSTED_LIST | 6,225,533 | 6.4% | 64.5% |
| STORE_FAST | 5,753,462 | 6.0% | 70.5% |
| _ITER_NEXT_LIST | 4,706,151 | 4.9% | 75.4% |
| _GUARD_GLOBALS_VERSION | 2,501,629 | 2.6% | 78.0% |
| POP_TOP | 1,855,052 | 1.9% | 79.9% |
| PUSH_NULL | 1,262,059 | 1.3% | 81.2% |
| _LOAD_GLOBAL_BUILTINS | 1,254,320 | 1.3% | 82.5% |
| _GUARD_BUILTINS_VERSION | 1,254,320 | 1.3% | 83.8% |
| _LOAD_GLOBAL_MODULE | 1,247,309 | 1.3% | 85.1% |
| _LOAD_ATTR_MODULE | 1,037,610 | 1.1% | 86.2% |
| _CHECK_ATTR_MODULE | 1,037,610 | 1.1% | 87.2% |
| _GUARD_TYPE_VERSION | 839,062 | 0.9% | 88.1% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 754,757 | 0.8% | 88.9% |
| _GUARD_KEYS_VERSION | 754,757 | 0.8% | 89.7% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 754,757 | 0.8% | 90.5% |
| _SAVE_CURRENT_IP | 656,865 | 0.7% | 91.1% |
| _ITER_CHECK_RANGE | 642,620 | 0.7% | 91.8% |
| _IS_ITER_EXHAUSTED_RANGE | 642,620 | 0.7% | 92.5% |
| LOAD_CONST | 604,123 | 0.6% | 93.1% |
| _PUSH_FRAME | 559,506 | 0.6% | 93.7% |
| _INIT_CALL_PY_EXACT_ARGS | 559,506 | 0.6% | 94.3% |
| _CHECK_STACK_SPACE | 559,506 | 0.6% | 94.8% |
| _CHECK_PEP_523 | 559,506 | 0.6% | 95.4% |
| _CHECK_FUNCTION_EXACT_ARGS | 559,506 | 0.6% | 96.0% |
| RESUME_CHECK | 559,506 | 0.6% | 96.6% |
| LOAD_ATTR | 457,960 | 0.5% | 97.0% |
| _ITER_NEXT_RANGE | 425,540 | 0.4% | 97.5% |
| BINARY_SUBSCR_LIST_INT | 413,320 | 0.4% | 97.9% |
| CALL_BUILTIN_CLASS | 409,000 | 0.4% | 98.3% |
| TO_BOOL_BOOL | 257,699 | 0.3% | 98.6% |
| _POP_JUMP_IF_FALSE | 252,888 | 0.3% | 98.9% |
| CALL_BUILTIN_FAST | 208,820 | 0.2% | 99.1% |
| GET_ITER | 204,500 | 0.2% | 99.3% |
| CALL_LEN | 204,500 | 0.2% | 99.5% |
| _POP_FRAME | 97,359 | 0.1% | 99.6% |
| _LOAD_ATTR_INSTANCE_VALUE | 71,492 | 0.1% | 99.7% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 71,492 | 0.1% | 99.8% |
| _IS_NONE | 48,480 | 0.1% | 99.8% |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 48,480 | 0.1% | 99.9% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 48,480 | 0.1% | 99.9% |
| _JUMP_TO_TOP | 18,920 | 0.0% | 99.9% |
| _ITER_CHECK_TUPLE | 10,560 | 0.0% | 99.9% |
| _IS_ITER_EXHAUSTED_TUPLE | 10,560 | 0.0% | 99.9% |
| _LOAD_ATTR_METHOD_NO_DICT | 9,822 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,800 | 0.0% | 100.0% |
| BUILD_TUPLE | 4,320 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,840 | 0.0% | 100.0% |
| _STORE_ATTR_INSTANCE_VALUE | 2,991 | 0.0% | 100.0% |
| _GUARD_DORV_VALUES | 2,991 | 0.0% | 100.0% |
| _GUARD_BOTH_INT | 2,991 | 0.0% | 100.0% |
| _BINARY_OP_ADD_INT | 2,991 | 0.0% | 100.0% |
| SWAP | 2,991 | 0.0% | 100.0% |
| COPY | 2,991 | 0.0% | 100.0% |
| CONTAINS_OP | 2,991 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_O | 2,991 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,991 | 0.0% | 100.0% |
| _ITER_NEXT_TUPLE | 960 | 0.0% | 100.0% |
| IS_OP | 399 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER_GEN | 279,520 |
| FOR_ITER | 56,020 |
| CALL | 72 |
| LOAD_ATTR_PROPERTY | 39 |
| YIELD_VALUE | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |
| CALL_KW | 20 |
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
Stats gathered on: 2023-10-04
