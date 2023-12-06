
# Pystats results

- benchmark: regex_compile
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 179,452,540 | 20.7% | 20.7% |  |
| STORE_FAST | 53,294,840 | 6.1% | 26.8% |  |
| POP_JUMP_IF_FALSE | 49,061,380 | 5.7% | 32.5% |  |
| LOAD_CONST | 44,872,980 | 5.2% | 37.6% |  |
| LOAD_GLOBAL_MODULE | 43,986,340 | 5.1% | 42.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 33,180,140 | 3.8% | 46.5% |  |
| LOAD_GLOBAL_BUILTIN | 32,505,240 | 3.7% | 50.3% |  |
| RESUME_CHECK | 28,857,300 | 3.3% | 53.6% |  |
| POP_TOP | 24,442,980 | 2.8% | 56.4% |  |
| LOAD_FAST_LOAD_FAST | 21,775,840 | 2.5% | 58.9% |  |
| PUSH_NULL | 20,707,140 | 2.4% | 61.3% |  |
| RETURN_VALUE | 18,493,680 | 2.1% | 63.4% |  |
| EXTENDED_ARG | 15,340,760 | 1.8% | 65.2% |  |
| ENTER_EXECUTOR | 14,872,460 | 1.7% | 66.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,294,340 | 1.6% | 68.5% |  |
| CALL_BUILTIN_O | 13,178,760 | 1.5% | 70.1% |  |
| RETURN_CONST | 11,792,760 | 1.4% | 71.4% |  |
| TO_BOOL_BOOL | 11,433,060 | 1.3% | 72.7% |  |
| CALL_PY_EXACT_ARGS | 10,957,140 | 1.3% | 74.0% |  |
| CONTAINS_OP | 10,544,980 | 1.2% | 75.2% |  |
| IS_OP | 10,296,180 | 1.2% | 76.4% |  |
| BINARY_OP_ADD_INT | 9,997,380 | 1.2% | 77.5% | 0.3% |
| COMPARE_OP_STR | 9,901,260 | 1.1% | 78.7% | 1.3% |
| TO_BOOL_INT | 9,176,280 | 1.1% | 79.7% |  |
| POP_JUMP_IF_TRUE | 8,977,440 | 1.0% | 80.8% |  |
| CALL_ISINSTANCE | 8,659,680 | 1.0% | 81.8% |  |
| BINARY_OP | 8,571,160 | 1.0% | 82.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 8,368,420 | 1.0% | 83.7% |  |
| CALL_LEN | 8,256,480 | 1.0% | 84.7% |  |
| BINARY_SUBSCR_LIST_INT | 7,597,080 | 0.9% | 85.6% | 12.6% |
| BINARY_SUBSCR_STR_INT | 7,052,240 | 0.8% | 86.4% | 2.5% |
| STORE_FAST_STORE_FAST | 6,929,020 | 0.8% | 87.2% |  |
| NOP | 6,645,740 | 0.8% | 87.9% |  |
| JUMP_FORWARD | 6,612,780 | 0.8% | 88.7% |  |
| BUILD_TUPLE | 6,228,060 | 0.7% | 89.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,093,720 | 0.7% | 90.1% |  |
| INTERPRETER_EXIT | 5,990,040 | 0.7% | 90.8% |  |
| LOAD_ATTR | 5,944,560 | 0.7% | 91.5% |  |
| CALL | 5,498,120 | 0.6% | 92.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,056,860 | 0.6% | 92.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,046,060 | 0.6% | 93.3% |  |
| GET_ITER | 4,484,460 | 0.5% | 93.8% |  |
| BINARY_SUBSCR_GETITEM | 3,963,960 | 0.5% | 94.3% |  |
| FOR_ITER | 3,365,040 | 0.4% | 94.6% |  |
| CALL_LIST_APPEND | 3,186,720 | 0.4% | 95.0% |  |
| BUILD_LIST | 3,043,020 | 0.4% | 95.4% |  |
| POP_JUMP_IF_NOT_NONE | 2,942,420 | 0.3% | 95.7% |  |
| BINARY_OP_SUBTRACT_INT | 2,430,540 | 0.3% | 96.0% |  |
| COPY | 2,277,540 | 0.3% | 96.2% |  |
| FOR_ITER_LIST | 2,057,180 | 0.2% | 96.5% | 1.4% |
| COMPARE_OP_INT | 1,935,900 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 1,871,640 | 0.2% | 96.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,851,240 | 0.2% | 97.1% |  |
| TO_BOOL_NONE | 1,774,680 | 0.2% | 97.3% | 5.2% |
| TO_BOOL_LIST | 1,458,840 | 0.2% | 97.5% | 0.9% |
| LOAD_ATTR_MODULE | 1,345,300 | 0.2% | 97.7% |  |
| STORE_SUBSCR_LIST_INT | 1,310,340 | 0.2% | 97.8% |  |
| BINARY_SUBSCR | 1,176,840 | 0.1% | 97.9% |  |
| CALL_BUILTIN_CLASS | 1,102,980 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 1,062,480 | 0.1% | 98.2% |  |
| TO_BOOL | 1,052,140 | 0.1% | 98.3% |  |
| UNARY_NOT | 1,051,980 | 0.1% | 98.4% |  |
| BUILD_SLICE | 955,380 | 0.1% | 98.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 936,660 | 0.1% | 98.7% |  |
| STORE_SUBSCR | 923,440 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_DICT | 807,600 | 0.1% | 98.9% |  |
| CALL_TYPE_1 | 679,860 | 0.1% | 98.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 629,940 | 0.1% | 99.0% |  |
| COMPARE_OP | 619,320 | 0.1% | 99.1% |  |
| TO_BOOL_STR | 598,680 | 0.1% | 99.1% | 1.0% |
| LOAD_ATTR_PROPERTY | 531,000 | 0.1% | 99.2% |  |
| STORE_FAST_LOAD_FAST | 463,140 | 0.1% | 99.3% |  |
| EXIT_INIT_CHECK | 459,240 | 0.1% | 99.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 459,240 | 0.1% | 99.4% |  |
| UNPACK_SEQUENCE_TUPLE | 448,800 | 0.1% | 99.4% |  |
| PUSH_EXC_INFO | 424,620 | 0.0% | 99.5% |  |
| POP_EXCEPT | 424,620 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 424,620 | 0.0% | 99.6% |  |
| CALL_PY_WITH_DEFAULTS | 339,540 | 0.0% | 99.6% |  |
| STORE_SUBSCR_DICT | 336,660 | 0.0% | 99.6% |  |
| BUILD_MAP | 336,420 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 335,640 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 335,640 | 0.0% | 99.8% |  |
| BINARY_OP_MULTIPLY_INT | 319,380 | 0.0% | 99.8% |  |
| BINARY_SLICE | 253,500 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 219,960 | 0.0% | 99.8% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 219,240 | 0.0% | 99.9% |  |
| LIST_APPEND | 210,240 | 0.0% | 99.9% |  |
| CALL_TUPLE_1 | 167,820 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 167,820 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 142,580 | 0.0% | 100.0% |  |
| UNARY_INVERT | 122,040 | 0.0% | 100.0% |  |
| SWAP | 79,860 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 59,880 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 38,960 | 0.0% | 100.0% | 100.0% |
| STORE_SLICE | 34,620 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 25,200 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 24,420 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 24,420 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 5,700 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 2,820 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 42,167,800 | 4.9% | 4.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 30,079,940 | 3.5% | 8.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 25,272,780 | 2.9% | 11.2% |
| STORE_FAST LOAD_FAST | 22,785,140 | 2.6% | 13.9% |
| LOAD_FAST LOAD_CONST | 22,110,960 | 2.5% | 16.4% |
| LOAD_FAST PUSH_NULL | 19,060,380 | 2.2% | 18.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 17,545,500 | 2.0% | 20.6% |
| POP_TOP LOAD_FAST | 14,317,320 | 1.6% | 22.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 12,025,260 | 1.4% | 23.7% |
| RESUME_CHECK LOAD_FAST | 11,673,960 | 1.3% | 25.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 11,326,900 | 1.3% | 26.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,957,140 | 1.3% | 27.6% |
| PUSH_NULL LOAD_FAST | 10,640,580 | 1.2% | 28.8% |
| CALL_BUILTIN_O POP_TOP | 10,510,980 | 1.2% | 30.0% |
| LOAD_GLOBAL_MODULE IS_OP | 9,940,260 | 1.1% | 31.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 9,514,380 | 1.1% | 32.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 9,428,580 | 1.1% | 33.3% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 9,316,380 | 1.1% | 34.4% |
| LOAD_CONST COMPARE_OP_STR | 8,454,000 | 1.0% | 35.4% |
| RETURN_CONST POP_TOP | 8,318,220 | 1.0% | 36.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 8,156,220 | 0.9% | 37.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 7,979,820 | 0.9% | 38.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 7,841,640 | 0.9% | 39.1% |
| IS_OP POP_JUMP_IF_FALSE | 7,506,300 | 0.9% | 40.0% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 7,476,360 | 0.9% | 40.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,454,100 | 0.9% | 41.7% |
| LOAD_FAST CALL_BUILTIN_O | 7,098,000 | 0.8% | 42.5% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 7,017,480 | 0.8% | 43.3% |
| CACHE RESUME_CHECK | 6,929,100 | 0.8% | 44.1% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 6,726,360 | 0.8% | 44.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,665,820 | 0.8% | 45.6% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 6,314,100 | 0.7% | 46.4% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 6,222,620 | 0.7% | 47.1% |
| LOAD_GLOBAL_MODULE BINARY_OP | 6,034,200 | 0.7% | 47.8% |
| NOP LOAD_FAST | 5,898,800 | 0.7% | 48.5% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 5,694,360 | 0.7% | 49.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,690,700 | 0.7% | 49.8% |
| LOAD_FAST LOAD_ATTR | 5,648,460 | 0.7% | 50.4% |
| STORE_FAST NOP | 5,626,680 | 0.6% | 51.1% |
| BINARY_OP_ADD_INT STORE_FAST | 5,624,580 | 0.6% | 51.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 5,617,420 | 0.6% | 52.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 5,500,480 | 0.6% | 53.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 5,466,420 | 0.6% | 53.6% |
| LOAD_ATTR STORE_FAST | 5,143,440 | 0.6% | 54.2% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 5,056,860 | 0.6% | 54.8% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,045,340 | 0.6% | 55.4% |
| LOAD_FAST RETURN_VALUE | 4,976,520 | 0.6% | 56.0% |
| LOAD_CONST STORE_FAST | 4,972,500 | 0.6% | 56.5% |
| BINARY_OP TO_BOOL_INT | 4,867,620 | 0.6% | 57.1% |
| STORE_FAST LOAD_CONST | 4,842,600 | 0.6% | 57.6% |
| RETURN_VALUE INTERPRETER_EXIT | 4,830,540 | 0.6% | 58.2% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 4,574,940 | 0.5% | 58.7% |
| LOAD_FAST CALL_LEN | 4,554,960 | 0.5% | 59.3% |
| LOAD_GLOBAL_MODULE STORE_FAST | 4,543,260 | 0.5% | 59.8% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 4,459,320 | 0.5% | 60.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 4,250,640 | 0.5% | 60.8% |
| LOAD_FAST BINARY_SUBSCR_STR_INT | 4,131,780 | 0.5% | 61.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 4,082,940 | 0.5% | 61.7% |
| BINARY_OP_ADD_INT LOAD_FAST | 4,052,400 | 0.5% | 62.2% |
| STORE_FAST ENTER_EXECUTOR | 4,038,420 | 0.5% | 62.7% |
| LOAD_FAST TO_BOOL_INT | 4,032,660 | 0.5% | 63.1% |
| EXTENDED_ARG ENTER_EXECUTOR | 3,987,400 | 0.5% | 63.6% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 3,963,960 | 0.5% | 64.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,925,140 | 0.5% | 64.5% |
| ENTER_EXECUTOR LOAD_FAST | 3,811,520 | 0.4% | 64.9% |
| BINARY_SUBSCR_STR_INT STORE_FAST | 3,747,300 | 0.4% | 65.4% |
| EXTENDED_ARG JUMP_FORWARD | 3,697,860 | 0.4% | 65.8% |
| STORE_FAST STORE_FAST | 3,564,720 | 0.4% | 66.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 3,507,180 | 0.4% | 66.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,487,740 | 0.4% | 67.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,391,260 | 0.4% | 67.4% |
| JUMP_FORWARD EXTENDED_ARG | 3,379,140 | 0.4% | 67.8% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 3,354,520 | 0.4% | 68.2% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 3,176,820 | 0.4% | 68.5% |
| POP_TOP ENTER_EXECUTOR | 3,023,160 | 0.3% | 68.9% |
| EXTENDED_ARG FOR_ITER | 3,009,020 | 0.3% | 69.2% |
| RETURN_VALUE POP_TOP | 2,995,440 | 0.3% | 69.6% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 2,947,860 | 0.3% | 69.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,942,420 | 0.3% | 70.3% |
| ENTER_EXECUTOR EXTENDED_ARG | 2,939,280 | 0.3% | 70.6% |
| LOAD_GLOBAL_BUILTIN STORE_FAST | 2,934,960 | 0.3% | 70.9% |
| LOAD_CONST BINARY_SUBSCR_STR_INT | 2,917,200 | 0.3% | 71.3% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 2,837,020 | 0.3% | 71.6% |
| BINARY_SUBSCR_STR_INT LOAD_CONST | 2,814,420 | 0.3% | 71.9% |
| CALL STORE_FAST | 2,803,920 | 0.3% | 72.2% |
| IS_OP POP_JUMP_IF_TRUE | 2,777,460 | 0.3% | 72.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,776,560 | 0.3% | 72.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 2,760,600 | 0.3% | 73.2% |
| CALL_LEN RETURN_VALUE | 2,760,600 | 0.3% | 73.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 2,751,000 | 0.3% | 73.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,699,880 | 0.3% | 74.1% |
| LOAD_FAST CALL_LIST_APPEND | 2,679,060 | 0.3% | 74.5% |
| CALL_LIST_APPEND RETURN_CONST | 2,679,060 | 0.3% | 74.8% |
| POP_TOP EXTENDED_ARG | 2,676,000 | 0.3% | 75.1% |
| LOAD_FAST LOAD_FAST | 2,635,140 | 0.3% | 75.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 2,602,740 | 0.3% | 75.7% |
| BUILD_LIST STORE_FAST | 2,601,180 | 0.3% | 76.0% |
| CONTAINS_OP EXTENDED_ARG | 2,574,880 | 0.3% | 76.3% |
| PUSH_NULL LOAD_CONST | 2,557,440 | 0.3% | 76.6% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 2,480,580 | 0.3% | 76.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 228,300 | 90.1% |
| LOAD_FAST | 24,420 | 9.6% |
| BINARY_OP_ADD_INT | 780 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 228,120 | 90.0% |
| LOAD_CONST | 25,200 | 9.9% |
| CALL | 180 | 0.1% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 33,840 | 97.7% |
| LOAD_CONST | 780 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 33,840 | 97.7% |
| LOAD_FAST | 780 | 2.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,929,100 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 216,660 | 98.8% |
| RETURN_VALUE | 1,020 | 0.5% |
| LOAD_FAST_LOAD_FAST | 780 | 0.4% |
| ENTER_EXECUTOR | 780 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 218,460 | 99.6% |
| LOAD_GLOBAL_BUILTIN | 780 | 0.4% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 955,380 | 81.2% |
| LOAD_FAST | 123,600 | 10.5% |
| LOAD_CONST | 97,500 | 8.3% |
| BINARY_SUBSCR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 930,960 | 79.1% |
| CALL_ALLOC_AND_ENTER_INIT | 123,600 | 10.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 97,500 | 8.3% |
| STORE_FAST | 24,420 | 2.1% |
| BINARY_SUBSCR | 360 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 424,620 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 424,620 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040 | 72.3% |
| LOAD_CONST | 780 | 27.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,040 | 72.3% |
| ENTER_EXECUTOR | 780 | 27.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 459,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 459,240 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,664,820 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,430,340 | 31.9% |
| BINARY_SUBSCR | 930,960 | 20.8% |
| BINARY_SUBSCR_TUPLE_INT | 177,660 | 4.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 167,820 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 2,275,320 | 50.7% |
| FOR_ITER_RANGE | 1,038,000 | 23.1% |
| FOR_ITER_LIST | 804,420 | 17.9% |
| FOR_ITER | 336,600 | 7.5% |
| LOAD_FAST_AND_CLEAR | 24,420 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,830,540 | 80.6% |
| RETURN_CONST | 1,159,500 | 19.4% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,626,680 | 84.7% |
| POP_JUMP_IF_FALSE | 604,080 | 9.1% |
| STORE_FAST_STORE_FAST | 129,480 | 1.9% |
| NOP | 129,480 | 1.9% |
| RESUME_CHECK | 86,880 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,898,800 | 88.8% |
| LOAD_GLOBAL_MODULE | 262,620 | 4.0% |
| LOAD_FAST_LOAD_FAST | 216,660 | 3.3% |
| NOP | 129,480 | 1.9% |
| LOAD_CONST | 69,060 | 1.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 256,020 | 60.3% |
| STORE_ATTR_INSTANCE_VALUE | 167,820 | 39.5% |
| STORE_FAST | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 256,020 | 60.3% |
| RETURN_CONST | 167,820 | 39.5% |
| EXTENDED_ARG | 780 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,510,980 | 43.0% |
| RETURN_CONST | 8,318,220 | 34.0% |
| RETURN_VALUE | 2,995,440 | 12.3% |
| POP_JUMP_IF_FALSE | 834,480 | 3.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 768,060 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,317,320 | 58.6% |
| ENTER_EXECUTOR | 3,023,160 | 12.4% |
| EXTENDED_ARG | 2,676,000 | 10.9% |
| RETURN_CONST | 1,427,040 | 5.8% |
| LOAD_GLOBAL_MODULE | 1,324,920 | 5.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 256,020 | 60.3% |
| BINARY_SUBSCR_STR_INT | 167,820 | 39.5% |
| STORE_SUBSCR | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 424,620 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,060,380 | 92.0% |
| LOAD_ATTR_MODULE | 1,183,480 | 5.7% |
| STORE_FAST_LOAD_FAST | 463,140 | 2.2% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,640,580 | 51.4% |
| LOAD_GLOBAL_MODULE | 4,459,320 | 21.5% |
| LOAD_CONST | 2,557,440 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,506,180 | 7.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,040,100 | 5.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,314,100 | 34.1% |
| LOAD_FAST | 4,976,520 | 26.9% |
| CALL_LEN | 2,760,600 | 14.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,197,900 | 6.5% |
| BINARY_OP_SUBTRACT_INT | 605,280 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 4,830,540 | 26.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,574,940 | 24.7% |
| POP_TOP | 2,995,440 | 16.2% |
| STORE_FAST | 2,360,040 | 12.8% |
| CALL_BUILTIN_O | 930,960 | 5.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 640,020 | 69.3% |
| LOAD_FAST | 157,440 | 17.0% |
| LOAD_CONST | 123,600 | 13.4% |
| BINARY_OP | 1,980 | 0.2% |
| STORE_SUBSCR | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 597,240 | 64.7% |
| RETURN_CONST | 157,440 | 17.0% |
| EXTENDED_ARG | 123,600 | 13.4% |
| ENTER_EXECUTOR | 26,700 | 2.9% |
| LOAD_FAST_LOAD_FAST | 15,900 | 1.7% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 669,080 | 63.6% |
| LOAD_ATTR | 167,820 | 16.0% |
| BINARY_OP | 167,820 | 16.0% |
| ENTER_EXECUTOR | 43,080 | 4.1% |
| TO_BOOL | 2,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 784,980 | 74.6% |
| POP_JUMP_IF_TRUE | 262,800 | 25.0% |
| TO_BOOL | 2,960 | 0.3% |
| TO_BOOL_NONE | 1,400 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 122,040 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 24,420 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_LIST | 746,880 | 71.0% |
| TO_BOOL_INT | 305,100 | 29.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 746,880 | 71.0% |
| COPY | 305,100 | 29.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,034,200 | 70.4% |
| LOAD_CONST | 1,139,100 | 13.3% |
| LOAD_FAST_LOAD_FAST | 549,360 | 6.4% |
| LOAD_FAST | 177,080 | 2.1% |
| RETURN_VALUE | 168,600 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 4,867,620 | 56.8% |
| STORE_FAST | 1,436,220 | 16.8% |
| CALL | 1,240,620 | 14.5% |
| LOAD_FAST | 290,640 | 3.4% |
| TO_BOOL | 167,820 | 2.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,000,020 | 32.9% |
| RESUME_CHECK | 624,300 | 20.5% |
| STORE_FAST | 497,100 | 16.3% |
| LOAD_CONST | 415,860 | 13.7% |
| POP_JUMP_IF_FALSE | 217,680 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,601,180 | 85.5% |
| LOAD_FAST | 335,640 | 11.0% |
| LOAD_GLOBAL_BUILTIN | 80,220 | 2.6% |
| SWAP | 24,420 | 0.8% |
| LOAD_GLOBAL_MODULE | 780 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 335,640 | 99.8% |
| STORE_FAST | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 335,640 | 99.8% |
| STORE_FAST | 780 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 955,380 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 955,380 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 2,341,980 | 37.6% |
| LOAD_FAST_LOAD_FAST | 1,314,900 | 21.1% |
| CALL | 1,073,580 | 17.2% |
| LOAD_FAST | 500,220 | 8.0% |
| BUILD_TUPLE | 370,800 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 2,402,580 | 38.6% |
| LOAD_FAST | 1,196,400 | 19.2% |
| CALL_BUILTIN_O | 605,160 | 9.7% |
| RETURN_VALUE | 422,940 | 6.8% |
| BUILD_TUPLE | 370,800 | 6.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,367,760 | 24.9% |
| LOAD_FAST | 1,258,880 | 22.9% |
| BINARY_OP | 1,240,620 | 22.6% |
| LOAD_GLOBAL_MODULE | 1,239,900 | 22.6% |
| ENTER_EXECUTOR | 232,620 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,803,920 | 51.0% |
| BUILD_TUPLE | 1,073,580 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 1,072,800 | 19.5% |
| LIST_APPEND | 210,240 | 3.8% |
| RETURN_VALUE | 167,820 | 3.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_INTRINSIC_1 | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 378,960 | 61.2% |
| LOAD_FAST | 133,680 | 21.6% |
| LOAD_ATTR_INSTANCE_VALUE | 101,640 | 16.4% |
| COMPARE_OP | 2,700 | 0.4% |
| COMPARE_OP_STR | 2,340 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 458,820 | 74.1% |
| POP_JUMP_IF_TRUE | 155,460 | 25.1% |
| COMPARE_OP | 2,700 | 0.4% |
| COMPARE_OP_STR | 2,340 | 0.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,726,360 | 63.8% |
| LOAD_FAST_LOAD_FAST | 2,837,020 | 26.9% |
| LOAD_CONST | 960,420 | 9.1% |
| ENTER_EXECUTOR | 20,400 | 0.2% |
| LOAD_FAST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,841,640 | 74.4% |
| EXTENDED_ARG | 2,574,880 | 24.4% |
| RETURN_VALUE | 105,960 | 1.0% |
| POP_JUMP_IF_TRUE | 22,500 | 0.2% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,073,040 | 47.1% |
| LOAD_ATTR_INSTANCE_VALUE | 605,280 | 26.6% |
| UNARY_NOT | 305,100 | 13.4% |
| LOAD_FAST | 144,660 | 6.4% |
| BINARY_OP | 137,040 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,072,800 | 47.1% |
| TO_BOOL_STR | 598,080 | 26.3% |
| TO_BOOL_BOOL | 317,520 | 13.9% |
| TO_BOOL_INT | 274,080 | 12.0% |
| TO_BOOL_NONE | 7,200 | 0.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,038,420 | 27.2% |
| EXTENDED_ARG | 3,987,400 | 26.8% |
| POP_TOP | 3,023,160 | 20.3% |
| POP_JUMP_IF_TRUE | 2,602,740 | 17.5% |
| STORE_SUBSCR_LIST_INT | 813,240 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,811,520 | 25.6% |
| EXTENDED_ARG | 2,939,280 | 19.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,480,580 | 16.7% |
| BINARY_SUBSCR_GETITEM | 2,243,580 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 1,081,800 | 7.3% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 3,379,140 | 22.0% |
| ENTER_EXECUTOR | 2,939,280 | 19.2% |
| POP_TOP | 2,676,000 | 17.4% |
| CONTAINS_OP | 2,574,880 | 16.8% |
| GET_ITER | 2,275,320 | 14.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,987,400 | 26.0% |
| JUMP_FORWARD | 3,697,860 | 24.1% |
| POP_JUMP_IF_FALSE | 3,354,520 | 21.9% |
| FOR_ITER | 3,009,020 | 19.6% |
| FOR_ITER_LIST | 1,252,100 | 8.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,009,020 | 89.4% |
| GET_ITER | 336,600 | 10.0% |
| JUMP_BACKWARD | 15,480 | 0.5% |
| FOR_ITER | 3,400 | 0.1% |
| FOR_ITER_LIST | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,109,380 | 62.7% |
| RETURN_CONST | 899,640 | 26.7% |
| LOAD_GLOBAL_MODULE | 167,820 | 5.0% |
| LOAD_FAST | 167,820 | 5.0% |
| STORE_FAST | 15,900 | 0.5% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,940,260 | 96.5% |
| LOAD_GLOBAL_BUILTIN | 167,820 | 1.6% |
| LOAD_FAST | 167,820 | 1.6% |
| LOAD_CONST | 12,420 | 0.1% |
| ENTER_EXECUTOR | 7,860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,506,300 | 72.9% |
| POP_JUMP_IF_TRUE | 2,777,460 | 27.0% |
| COPY | 12,240 | 0.1% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 87,060 | 61.1% |
| EXTENDED_ARG | 39,860 | 28.0% |
| POP_JUMP_IF_TRUE | 14,640 | 10.3% |
| ENTER_EXECUTOR | 900 | 0.6% |
| POP_JUMP_IF_FALSE | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 87,060 | 61.1% |
| EXTENDED_ARG | 39,800 | 27.9% |
| FOR_ITER | 15,480 | 10.9% |
| FOR_ITER_LIST | 120 | 0.1% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,697,860 | 55.9% |
| POP_TOP | 819,840 | 12.4% |
| STORE_FAST | 712,680 | 10.8% |
| STORE_SUBSCR | 597,240 | 9.0% |
| POP_JUMP_IF_TRUE | 305,100 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,379,140 | 51.1% |
| LOAD_GLOBAL_BUILTIN | 1,572,300 | 23.8% |
| LOAD_FAST | 1,154,160 | 17.5% |
| LOAD_GLOBAL_MODULE | 285,720 | 4.3% |
| LOAD_FAST_LOAD_FAST | 152,400 | 2.3% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 210,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 210,240 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,648,460 | 95.0% |
| LOAD_GLOBAL_MODULE | 256,080 | 4.3% |
| LOAD_GLOBAL_BUILTIN | 38,220 | 0.6% |
| LOAD_ATTR | 1,780 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,143,440 | 86.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 256,020 | 4.3% |
| LOAD_FAST | 206,040 | 3.5% |
| TO_BOOL | 167,820 | 2.8% |
| LOAD_FAST_LOAD_FAST | 167,820 | 2.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,110,960 | 49.3% |
| STORE_FAST | 4,842,600 | 10.8% |
| BINARY_SUBSCR_STR_INT | 2,814,420 | 6.3% |
| PUSH_NULL | 2,557,440 | 5.7% |
| LOAD_CONST | 2,142,900 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 9,428,580 | 21.0% |
| COMPARE_OP_STR | 8,454,000 | 18.8% |
| STORE_FAST | 4,972,500 | 11.1% |
| BINARY_SUBSCR_STR_INT | 2,917,200 | 6.5% |
| LOAD_FAST | 2,354,280 | 5.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 66.7% |
| LIST_EXTEND | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 42,167,800 | 23.5% |
| STORE_FAST | 22,785,140 | 12.7% |
| LOAD_GLOBAL_BUILTIN | 17,545,500 | 9.8% |
| POP_TOP | 14,317,320 | 8.0% |
| LOAD_ATTR_INSTANCE_VALUE | 12,025,260 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 30,079,940 | 16.8% |
| LOAD_GLOBAL_MODULE | 25,272,780 | 14.1% |
| LOAD_CONST | 22,110,960 | 12.3% |
| PUSH_NULL | 19,060,380 | 10.6% |
| LOAD_GLOBAL_BUILTIN | 7,979,820 | 4.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 24,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 24,420 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 59,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,880 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 4,082,940 | 18.7% |
| RESUME_CHECK | 2,947,860 | 13.5% |
| LOAD_GLOBAL_MODULE | 2,378,760 | 10.9% |
| STORE_FAST_STORE_FAST | 2,369,620 | 10.9% |
| LOAD_GLOBAL_BUILTIN | 1,704,780 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 6,665,820 | 30.6% |
| CONTAINS_OP | 2,837,020 | 13.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,254,320 | 10.4% |
| CALL_PY_EXACT_ARGS | 1,510,980 | 6.9% |
| CALL | 1,367,760 | 6.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 40.0% |
| STORE_FAST | 20 | 20.0% |
| RESUME_CHECK | 20 | 20.0% |
| FOR_ITER_RANGE | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 20.0% |
| LOAD_ATTR | 20 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 9,514,380 | 19.4% |
| COMPARE_OP_STR | 9,316,380 | 19.0% |
| CONTAINS_OP | 7,841,640 | 16.0% |
| IS_OP | 7,506,300 | 15.3% |
| TO_BOOL_INT | 5,694,360 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,167,800 | 85.9% |
| LOAD_GLOBAL_MODULE | 1,715,220 | 3.5% |
| LOAD_CONST | 866,160 | 1.8% |
| POP_TOP | 834,480 | 1.7% |
| LOAD_FAST_LOAD_FAST | 764,520 | 1.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,365,900 | 73.0% |
| LOAD_FAST | 505,740 | 27.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,072,800 | 57.3% |
| LOAD_FAST | 666,360 | 35.6% |
| ENTER_EXECUTOR | 85,260 | 4.6% |
| LOAD_GLOBAL_BUILTIN | 47,040 | 2.5% |
| RETURN_CONST | 180 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,942,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,275,180 | 43.3% |
| BUILD_LIST | 1,000,020 | 34.0% |
| LOAD_GLOBAL_BUILTIN | 315,900 | 10.7% |
| LOAD_GLOBAL_MODULE | 167,820 | 5.7% |
| LOAD_FAST_LOAD_FAST | 123,600 | 4.2% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,176,820 | 35.4% |
| IS_OP | 2,777,460 | 30.9% |
| TO_BOOL_BOOL | 1,721,580 | 19.2% |
| TO_BOOL_STR | 598,080 | 6.7% |
| TO_BOOL | 262,800 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,250,640 | 47.3% |
| ENTER_EXECUTOR | 2,602,740 | 29.0% |
| CALL_LEN | 598,260 | 6.7% |
| LOAD_FAST_LOAD_FAST | 311,820 | 3.5% |
| JUMP_FORWARD | 305,100 | 3.4% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,045,340 | 42.8% |
| CALL_LIST_APPEND | 2,679,060 | 22.7% |
| POP_TOP | 1,427,040 | 12.1% |
| FOR_ITER | 899,640 | 7.6% |
| POP_JUMP_IF_FALSE | 738,600 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,318,220 | 70.5% |
| TO_BOOL_BOOL | 1,517,280 | 12.9% |
| INTERPRETER_EXIT | 1,159,500 | 9.8% |
| EXIT_INIT_CHECK | 459,240 | 3.9% |
| STORE_FAST | 338,520 | 2.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,222,620 | 11.7% |
| BINARY_OP_ADD_INT | 5,624,580 | 10.6% |
| LOAD_ATTR | 5,143,440 | 9.7% |
| LOAD_CONST | 4,972,500 | 9.3% |
| LOAD_GLOBAL_MODULE | 4,543,260 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,785,140 | 42.8% |
| NOP | 5,626,680 | 10.6% |
| LOAD_GLOBAL_MODULE | 5,500,480 | 10.3% |
| LOAD_CONST | 4,842,600 | 9.1% |
| ENTER_EXECUTOR | 4,038,420 | 7.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 463,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 463,140 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 5,617,420 | 81.1% |
| COPY | 1,072,800 | 15.5% |
| UNPACK_SEQUENCE_TUPLE | 214,260 | 3.1% |
| STORE_FAST_STORE_FAST | 24,540 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,507,180 | 50.6% |
| LOAD_FAST_LOAD_FAST | 2,369,620 | 34.2% |
| LOAD_GLOBAL_BUILTIN | 683,880 | 9.9% |
| STORE_FAST | 189,720 | 2.7% |
| NOP | 129,480 | 1.9% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 24,420 | 30.6% |
| ENTER_EXECUTOR | 24,420 | 30.6% |
| BUILD_LIST | 24,420 | 30.6% |
| BINARY_OP | 6,600 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,420 | 30.6% |
| FOR_ITER_RANGE | 24,420 | 30.6% |
| BUILD_LIST | 24,420 | 30.6% |
| STORE_ATTR_INSTANCE_VALUE | 6,600 | 8.3% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,428,580 | 94.3% |
| LOAD_FAST_LOAD_FAST | 321,060 | 3.2% |
| BINARY_OP | 124,140 | 1.2% |
| BINARY_OP_MULTIPLY_INT | 123,600 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,624,580 | 56.3% |
| LOAD_FAST | 4,052,400 | 40.5% |
| CALL_PY_EXACT_ARGS | 137,280 | 1.4% |
| CALL_BUILTIN_O | 97,500 | 1.0% |
| STORE_SLICE | 33,840 | 0.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 195,000 | 61.1% |
| BINARY_SUBSCR_TUPLE_INT | 123,600 | 38.7% |
| LOAD_ATTR | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 123,600 | 38.7% |
| LOAD_CONST | 97,500 | 30.5% |
| CALL_BUILTIN_O | 97,500 | 30.5% |
| LOAD_GLOBAL_BUILTIN | 780 | 0.2% |


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
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,195,260 | 49.2% |
| LOAD_CONST | 630,000 | 25.9% |
| CALL_LEN | 605,280 | 24.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,083,480 | 44.6% |
| RETURN_VALUE | 605,280 | 24.9% |
| LOAD_FAST | 255,780 | 10.5% |
| LOAD_CONST | 218,820 | 9.0% |
| STORE_FAST | 176,580 | 7.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 404,340 | 50.1% |
| BUILD_TUPLE | 256,020 | 31.7% |
| LOAD_FAST_LOAD_FAST | 147,240 | 18.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 256,020 | 31.7% |
| CALL_BUILTIN_O | 228,960 | 28.4% |
| RETURN_VALUE | 167,820 | 20.8% |
| LOAD_CONST | 141,540 | 17.5% |
| STORE_FAST | 6,600 | 0.8% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,243,580 | 56.6% |
| LOAD_FAST | 929,760 | 23.5% |
| LOAD_CONST | 790,620 | 19.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,963,960 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,017,480 | 92.4% |
| LOAD_CONST | 364,080 | 4.8% |
| LOAD_FAST_LOAD_FAST | 131,640 | 1.7% |
| BINARY_OP_SUBTRACT_INT | 65,820 | 0.9% |
| BINARY_SUBSCR_LIST_INT | 18,060 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,314,100 | 94.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 87,060 | 1.3% |
| STORE_FAST | 70,980 | 1.1% |
| LOAD_FAST_LOAD_FAST | 65,820 | 1.0% |
| COMPARE_OP_INT | 65,820 | 1.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,131,780 | 58.6% |
| LOAD_CONST | 2,917,200 | 41.4% |
| BINARY_SUBSCR_STR_INT | 3,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,747,300 | 53.1% |
| LOAD_CONST | 2,814,420 | 39.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 216,660 | 3.1% |
| PUSH_EXC_INFO | 167,820 | 2.4% |
| CALL_BUILTIN_O | 102,780 | 1.5% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,811,640 | 97.9% |
| ENTER_EXECUTOR | 39,600 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 478,560 | 25.9% |
| CALL_BUILTIN_O | 437,940 | 23.7% |
| GET_ITER | 177,660 | 9.6% |
| LOAD_FAST | 150,000 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 123,600 | 6.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 167,820 | 36.5% |
| LOAD_FAST | 167,820 | 36.5% |
| BINARY_SUBSCR | 123,600 | 26.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 459,240 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 2,402,580 | 47.5% |
| LOAD_CONST | 1,407,540 | 27.8% |
| PUSH_NULL | 1,040,100 | 20.6% |
| LOAD_FAST | 206,400 | 4.1% |
| BINARY_SUBSCR_LIST_INT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,056,860 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,011,180 | 91.7% |
| CALL_BUILTIN_FAST | 38,220 | 3.5% |
| BINARY_OP_ADD_INT | 26,160 | 2.4% |
| UNARY_NEGATIVE | 24,420 | 2.2% |
| LOAD_FAST_LOAD_FAST | 1,380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 930,960 | 84.4% |
| GET_ITER | 107,160 | 9.7% |
| RETURN_VALUE | 38,220 | 3.5% |
| STORE_FAST | 26,220 | 2.4% |
| CALL_BUILTIN_O | 420 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,220 | 98.1% |
| CALL_BUILTIN_FAST | 740 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 38,220 | 98.1% |
| CALL_BUILTIN_FAST | 740 | 1.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 167,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 167,820 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,098,000 | 53.9% |
| LOAD_GLOBAL_MODULE | 1,498,260 | 11.4% |
| LOAD_CONST | 1,149,900 | 8.7% |
| RETURN_VALUE | 930,960 | 7.1% |
| CALL_LEN | 764,100 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 10,510,980 | 79.8% |
| BUILD_TUPLE | 2,341,980 | 17.8% |
| TO_BOOL_BOOL | 182,280 | 1.4% |
| STORE_FAST | 143,520 | 1.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,476,360 | 86.3% |
| LOAD_GLOBAL_MODULE | 512,040 | 5.9% |
| BUILD_TUPLE | 335,640 | 3.9% |
| LOAD_ATTR_SLOT | 167,820 | 1.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 167,820 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 8,156,220 | 94.2% |
| RETURN_VALUE | 335,640 | 3.9% |
| LOAD_FAST | 167,820 | 1.9% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,554,960 | 55.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,760,600 | 33.4% |
| POP_JUMP_IF_TRUE | 598,260 | 7.2% |
| LOAD_GLOBAL_MODULE | 335,640 | 4.1% |
| LOAD_CONST | 7,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,760,600 | 33.4% |
| LOAD_FAST | 1,147,800 | 13.9% |
| CALL_BUILTIN_CLASS | 1,011,180 | 12.2% |
| LOAD_CONST | 795,120 | 9.6% |
| CALL_BUILTIN_O | 764,100 | 9.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,679,060 | 84.1% |
| BUILD_TUPLE | 242,340 | 7.6% |
| LOAD_GLOBAL_MODULE | 167,820 | 5.3% |
| LOAD_CONST | 97,500 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,679,060 | 84.1% |
| LOAD_FAST | 265,320 | 8.3% |
| EXTENDED_ARG | 90,660 | 2.8% |
| JUMP_BACKWARD | 87,060 | 2.7% |
| ENTER_EXECUTOR | 38,220 | 1.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 326,580 | 51.8% |
| LOAD_CONST | 256,020 | 40.6% |
| LOAD_FAST_LOAD_FAST | 45,420 | 7.2% |
| BUILD_TUPLE | 1,920 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 628,020 | 99.7% |
| POP_TOP | 1,920 | 0.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 24,420 | 96.9% |
| LOAD_CONST | 780 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,420 | 96.9% |
| STORE_FAST | 780 | 3.1% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 680,640 | 72.7% |
| LOAD_ATTR | 256,020 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 768,060 | 82.0% |
| GET_ITER | 167,820 | 17.9% |
| RETURN_VALUE | 780 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,020 | 63.2% |
| RETURN_VALUE | 80,220 | 36.5% |
| BUILD_LIST | 720 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 219,960 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,690,700 | 51.9% |
| LOAD_FAST | 1,714,380 | 15.6% |
| LOAD_FAST_LOAD_FAST | 1,510,980 | 13.8% |
| UNARY_NOT | 746,880 | 6.8% |
| LOAD_CONST | 304,860 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,957,140 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 171,720 | 50.6% |
| LOAD_FAST_LOAD_FAST | 167,820 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 339,540 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 167,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 167,820 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 679,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 512,040 | 75.3% |
| LOAD_FAST | 167,820 | 24.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,307,940 | 67.6% |
| LOAD_GLOBAL_MODULE | 433,140 | 22.4% |
| CALL_LEN | 105,840 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 65,820 | 3.4% |
| LOAD_FAST | 22,020 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,934,160 | 99.9% |
| POP_JUMP_IF_TRUE | 1,560 | 0.1% |
| COPY | 180 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,454,000 | 85.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,442,940 | 14.6% |
| COMPARE_OP | 2,340 | 0.0% |
| LOAD_FAST | 1,980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,316,380 | 94.1% |
| EXTENDED_ARG | 582,540 | 5.9% |
| COMPARE_OP | 2,340 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 1,252,100 | 60.9% |
| GET_ITER | 804,420 | 39.1% |
| FOR_ITER | 540 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,583,300 | 77.0% |
| STORE_FAST | 380,100 | 18.5% |
| LOAD_FAST_LOAD_FAST | 81,240 | 3.9% |
| RETURN_CONST | 10,680 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 1,320 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,038,000 | 97.7% |
| SWAP | 24,420 | 2.3% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,042,560 | 98.1% |
| LOAD_FAST | 19,860 | 1.9% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,700 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,079,940 | 90.7% |
| LOAD_FAST_LOAD_FAST | 2,254,320 | 6.8% |
| LOAD_ATTR_INSTANCE_VALUE | 839,280 | 2.5% |
| COPY | 6,600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,025,260 | 36.2% |
| STORE_FAST | 6,222,620 | 18.8% |
| LOAD_ATTR_METHOD_NO_DICT | 2,776,560 | 8.4% |
| CALL_LEN | 2,760,600 | 8.3% |
| COMPARE_OP_STR | 1,442,940 | 4.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,776,560 | 55.0% |
| LOAD_GLOBAL_MODULE | 1,140,060 | 22.6% |
| LOAD_FAST | 1,116,240 | 22.1% |
| ENTER_EXECUTOR | 12,420 | 0.2% |
| CALL | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,487,740 | 69.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 680,640 | 13.5% |
| LOAD_CONST | 403,800 | 8.0% |
| LOAD_GLOBAL_MODULE | 335,820 | 6.7% |
| LOAD_FAST_LOAD_FAST | 138,060 | 2.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,391,260 | 55.7% |
| ENTER_EXECUTOR | 2,480,580 | 40.7% |
| BINARY_SUBSCR_TUPLE_INT | 123,600 | 2.0% |
| BINARY_SUBSCR | 97,500 | 1.6% |
| LOAD_FAST_LOAD_FAST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,690,700 | 93.4% |
| LOAD_FAST | 195,960 | 3.2% |
| LOAD_CONST | 137,820 | 2.3% |
| LOAD_GLOBAL_MODULE | 69,060 | 1.1% |
| LOAD_FAST_LOAD_FAST | 180 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,089,280 | 81.0% |
| ENTER_EXECUTOR | 255,960 | 19.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,183,480 | 88.0% |
| STORE_FAST | 122,040 | 9.1% |
| RETURN_VALUE | 39,000 | 2.9% |
| COMPARE_OP_INT | 780 | 0.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 167,820 | 50.0% |
| LOAD_FAST | 167,820 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 167,820 | 50.0% |
| CALL_ISINSTANCE | 167,820 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 335,640 | 63.2% |
| LOAD_FAST | 195,000 | 36.7% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 531,000 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 167,820 | 50.0% |
| LOAD_FAST | 167,820 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 167,820 | 50.0% |
| CALL_ISINSTANCE | 167,820 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,326,900 | 34.8% |
| LOAD_FAST | 7,979,820 | 24.5% |
| STORE_FAST | 3,925,140 | 12.1% |
| JUMP_FORWARD | 1,572,300 | 4.8% |
| LOAD_GLOBAL_BUILTIN | 1,329,660 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,545,500 | 54.0% |
| CALL_ISINSTANCE | 7,476,360 | 23.0% |
| STORE_FAST | 2,934,960 | 9.0% |
| LOAD_FAST_LOAD_FAST | 1,704,780 | 5.2% |
| LOAD_GLOBAL_BUILTIN | 1,329,660 | 4.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,272,780 | 57.5% |
| STORE_FAST | 5,500,480 | 12.5% |
| PUSH_NULL | 4,459,320 | 10.1% |
| RESUME_CHECK | 1,948,500 | 4.4% |
| POP_JUMP_IF_FALSE | 1,715,220 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 9,940,260 | 22.6% |
| CONTAINS_OP | 6,726,360 | 15.3% |
| BINARY_OP | 6,034,200 | 13.7% |
| LOAD_FAST | 5,466,420 | 12.4% |
| STORE_FAST | 4,543,260 | 10.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,957,140 | 38.0% |
| CACHE | 6,929,100 | 24.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,056,860 | 17.5% |
| BINARY_SUBSCR_GETITEM | 3,963,960 | 13.7% |
| ENTER_EXECUTOR | 620,340 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,673,960 | 40.5% |
| LOAD_GLOBAL_BUILTIN | 11,326,900 | 39.3% |
| LOAD_FAST_LOAD_FAST | 2,947,860 | 10.2% |
| LOAD_GLOBAL_MODULE | 1,948,500 | 6.8% |
| BUILD_LIST | 624,300 | 2.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,454,100 | 52.1% |
| LOAD_FAST_LOAD_FAST | 6,665,820 | 46.6% |
| LOAD_ATTR_INSTANCE_VALUE | 167,820 | 1.2% |
| SWAP | 6,600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,045,340 | 35.3% |
| LOAD_FAST_LOAD_FAST | 4,082,940 | 28.6% |
| LOAD_FAST | 2,699,880 | 18.9% |
| LOAD_CONST | 1,794,900 | 12.6% |
| BUILD_MAP | 335,640 | 2.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 336,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 168,840 | 50.2% |
| LOAD_GLOBAL_BUILTIN | 167,820 | 49.8% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,149,300 | 87.7% |
| LOAD_FAST | 161,040 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 813,240 | 62.1% |
| RETURN_CONST | 264,600 | 20.2% |
| EXTENDED_ARG | 214,560 | 16.4% |
| LOAD_FAST | 17,940 | 1.4% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 8,156,220 | 71.3% |
| RETURN_CONST | 1,517,280 | 13.3% |
| LOAD_FAST | 571,440 | 5.0% |
| RETURN_VALUE | 454,020 | 4.0% |
| COPY | 317,520 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,514,380 | 83.2% |
| POP_JUMP_IF_TRUE | 1,721,580 | 15.1% |
| EXTENDED_ARG | 197,100 | 1.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,867,620 | 53.0% |
| LOAD_FAST | 4,032,660 | 43.9% |
| COPY | 274,080 | 3.0% |
| ENTER_EXECUTOR | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,694,360 | 62.1% |
| POP_JUMP_IF_TRUE | 3,176,820 | 34.6% |
| UNARY_NOT | 305,100 | 3.3% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,371,720 | 94.0% |
| LOAD_ATTR_INSTANCE_VALUE | 86,880 | 6.0% |
| TO_BOOL_NONE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNARY_NOT | 746,880 | 51.2% |
| POP_JUMP_IF_FALSE | 457,740 | 31.4% |
| POP_JUMP_IF_TRUE | 253,980 | 17.4% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,765,720 | 99.5% |
| COPY | 7,200 | 0.4% |
| TO_BOOL | 1,400 | 0.1% |
| TO_BOOL_LIST | 240 | 0.0% |
| TO_BOOL_STR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,765,740 | 99.5% |
| POP_JUMP_IF_TRUE | 7,200 | 0.4% |
| TO_BOOL | 1,380 | 0.1% |
| TO_BOOL_LIST | 240 | 0.0% |
| TO_BOOL_STR | 120 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 598,080 | 99.9% |
| LOAD_FAST | 480 | 0.1% |
| TO_BOOL_NONE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 598,080 | 99.9% |
| POP_JUMP_IF_FALSE | 480 | 0.1% |
| TO_BOOL_NONE | 120 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,140 | 53.7% |
| RETURN_VALUE | 189,720 | 42.3% |
| BINARY_SUBSCR_TUPLE_INT | 17,940 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 234,540 | 52.3% |
| STORE_FAST_STORE_FAST | 214,260 | 47.7% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,574,940 | 54.7% |
| FOR_ITER | 2,109,380 | 25.2% |
| FOR_ITER_LIST | 1,583,300 | 18.9% |
| BINARY_SUBSCR_LIST_INT | 87,060 | 1.0% |
| LOAD_CONST | 13,740 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 5,617,420 | 67.1% |
| STORE_FAST | 2,751,000 | 32.9% |


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

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1176480 | 5.2% |
| specialization.deopt |        21320 | 0.1% |
|          hit |     20140920 | 89.7% |
|         miss |      1131200 | 5.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 21,320 | 98.3% |
| Failure | 360 | 1.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 240 | 66.7% |
| buffer slice | 40 | 11.1% |
| list slice | 40 | 11.1% |
| out of range | 40 | 11.1% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       923040 | 35.9% |
|          hit |      1647000 | 64.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 400 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 300 | 75.0% |
| py simple | 60 | 15.0% |
| list slice | 40 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1047780 | 4.1% |
| specialization.deopt |         2100 | 0.0% |
|          hit |     24329620 | 95.4% |
|         miss |       111920 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,120 | 32.8% |
| Failure | 4,340 | 67.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 3,780 | 87.1% |
| mapping | 200 | 4.6% |
| dict | 180 | 4.1% |
| other | 140 | 3.2% |
| number | 40 | 0.9% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8567220 | 39.8% |
| specialization.deopt |          540 | 0.0% |
|          hit |     12937400 | 60.1% |
|         miss |        29200 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 560 | 12.5% |
| Failure | 3,920 | 87.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,980 | 50.5% |
| add different types | 880 | 22.4% |
| or | 320 | 8.2% |
| subtract different types | 300 | 7.7% |
| add other | 200 | 5.1% |
| multiply different types | 160 | 4.1% |
| floor divide | 40 | 1.0% |
| and different types | 40 | 1.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5496360 | 8.5% |
| specialization.deopt |          740 | 0.0% |
|          hit |     59081520 | 91.4% |
|         miss |        38960 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 30.4% |
| Failure | 1,740 | 69.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 920 | 52.9% |
| class no vectorcall | 360 | 20.7% |
| wrong number arguments | 280 | 16.1% |
| meth descr varargs | 80 | 4.6% |
| cfunc noargs | 60 | 3.4% |
| class mutable | 40 | 2.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       614280 | 4.9% |
| specialization.deopt |         2340 | 0.0% |
|          hit |     11713140 | 94.0% |
|         miss |       124020 | 1.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,340 | 31.7% |
| Failure | 5,040 | 68.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 4,840 | 96.0% |
| big int | 80 | 1.6% |
| other | 80 | 1.6% |
| tuple | 40 | 0.8% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3361100 | 51.8% |
| specialization.deopt |          540 | 0.0% |
|          hit |      3096740 | 47.7% |
|         miss |        28620 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 12.1% |
| Failure | 3,940 | 87.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| seq iter | 3,820 | 97.0% |
| map | 40 | 1.0% |
| dict items | 40 | 1.0% |
| dict keys | 40 | 1.0% |


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
| specialization.deferred |      5942720 | 11.3% |
|          hit |     46867500 | 88.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.3% |
| Failure | 1,780 | 96.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,440 | 80.9% |
| not managed dict | 140 | 7.9% |
| metaclass attribute | 120 | 6.7% |
| builtin class method | 40 | 2.2% |
| mutable class | 40 | 2.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     76491580 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     14294340 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      8817220 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 473,161,980 | 54.5% |
| Not specialized | 91,898,220 | 10.6% |
| Specialized | 303,217,420 | 34.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 8,567,220 | 31.6% |
| LOAD_ATTR | 5,942,720 | 21.9% |
| CALL | 5,496,360 | 20.3% |
| FOR_ITER | 3,361,100 | 12.4% |
| BINARY_SUBSCR | 1,176,480 | 4.3% |
| TO_BOOL | 1,047,780 | 3.9% |
| STORE_SUBSCR | 923,040 | 3.4% |
| COMPARE_OP | 614,280 | 2.3% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 957,120 | 65.4% |
| BINARY_SUBSCR_STR_INT | 174,080 | 11.9% |
| COMPARE_OP_STR | 124,020 | 8.5% |
| TO_BOOL_NONE | 93,020 | 6.4% |
| CALL_BUILTIN_FAST | 38,960 | 2.7% |
| BINARY_OP_ADD_INT | 29,200 | 2.0% |
| FOR_ITER_LIST | 28,620 | 2.0% |
| TO_BOOL_LIST | 12,720 | 0.9% |
| TO_BOOL_STR | 6,180 | 0.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 6,929,100 | 24.5% |
| Calls to Python functions inlined | 21,307,860 | 75.5% |
| Calls via PyEval_EvalFrame (total) | 6,929,100 | 24.5% |
| Calls via PyEval_EvalFrame (vector) | 6,929,100 | 24.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 6,929,100 | 24.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,733,660 | 20.3% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 31,225,500 | 110.6% |
| Frame objects created | 2,302,740 | 8.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 17,215,200 | 26.1% |
| Frees to freelist | 17,215,200 |  |
| Allocations | 48,707,560 | 73.9% |
| Allocations to 512 bytes | 48,676,020 | 73.8% |
| Allocations to 4 kbytes | 29,980 | 0.0% |
| Allocations over 4 kbytes | 1,560 | 0.0% |
| Frees | 50,725,320 |  |
| New values | 1,000,020 |  |
| Interpreter increfs | 326,692,460 | 64.3% |
| Interpreter decrefs | 338,858,880 | 59.1% |
| Increfs | 181,706,300 | 35.7% |
| Decrefs | 234,046,040 | 40.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 6,150,452 |  |
| Method cache misses | 8 |  |
| Method cache collisions | 8 |  |
| Method cache dunder hits | 15,278,060 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
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
| Optimization attempts | 8,360 |  |
| Traces created | 40 | 0.5% |
| Traces executed | 14,872,460 |  |
| Uops executed | 567,365,300 | 38 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 20 |  |
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
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 40 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 40 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,946,000 | 13.1% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,656,200 | 17.9% |
| <= 16 | 4,215,420 | 28.3% |
| <= 32 | 1,577,460 | 10.6% |
| <= 64 | 4,316,700 | 29.0% |
| <= 128 | 29,580 | 0.2% |
| <= 256 | 68,340 | 0.5% |
| <= 512 | 33,600 | 0.2% |
| <= 1024 | 28,080 | 0.2% |
| <= 2048 | 0 | 0.0% |
| <= 4096 | 0 | 0.0% |
| <= 8192 | 60 | 0.0% |
| <= 16384 | 720 | 0.0% |
| <= 32768 | 0 | 0.0% |
| <= 65536 | 0 | 0.0% |
| <= 131072 | 0 | 0.0% |
| <= 262144 | 0 | 0.0% |
| <= 524288 | 0 | 0.0% |
| <= 1048576 | 300 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 128,384,280 | 22.6% | 22.6% |
| LOAD_FAST | 85,902,900 | 15.1% | 37.8% |
| _POP_JUMP_IF_TRUE | 43,676,640 | 7.7% | 45.5% |
| STORE_FAST | 37,267,880 | 6.6% | 52.0% |
| LOAD_CONST | 25,560,420 | 4.5% | 56.5% |
| _ITER_CHECK_RANGE | 23,348,580 | 4.1% | 60.7% |
| _IS_ITER_EXHAUSTED_RANGE | 23,348,580 | 4.1% | 64.8% |
| _ITER_NEXT_RANGE | 22,306,380 | 3.9% | 68.7% |
| _JUMP_TO_TOP | 21,603,480 | 3.8% | 72.5% |
| STORE_SUBSCR | 20,292,960 | 3.6% | 76.1% |
| _EXIT_TRACE | 12,883,380 | 2.3% | 78.4% |
| _GUARD_GLOBALS_VERSION | 9,870,480 | 1.7% | 80.1% |
| _LOAD_GLOBAL_MODULE | 9,864,240 | 1.7% | 81.8% |
| _ITER_CHECK_LIST | 9,694,840 | 1.7% | 83.5% |
| _IS_ITER_EXHAUSTED_LIST | 7,748,840 | 1.4% | 84.9% |
| IS_OP | 6,006,240 | 1.1% | 86.0% |
| _ITER_NEXT_LIST | 5,973,800 | 1.1% | 87.0% |
| PUSH_NULL | 5,625,600 | 1.0% | 88.0% |
| CONTAINS_OP | 5,009,480 | 0.9% | 88.9% |
| _LOAD_ATTR_INSTANCE_VALUE | 4,604,260 | 0.8% | 89.7% |
| _GUARD_TYPE_VERSION | 4,604,260 | 0.8% | 90.5% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 4,604,260 | 0.8% | 91.3% |
| POP_TOP | 4,389,480 | 0.8% | 92.1% |
| _POP_JUMP_IF_FALSE | 3,932,600 | 0.7% | 92.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,414,740 | 0.6% | 93.4% |
| _IS_NONE | 2,873,860 | 0.5% | 93.9% |
| _SAVE_CURRENT_IP | 2,529,300 | 0.4% | 94.4% |
| _PUSH_FRAME | 2,529,300 | 0.4% | 94.8% |
| _INIT_CALL_PY_EXACT_ARGS | 2,529,300 | 0.4% | 95.2% |
| _CHECK_STACK_SPACE | 2,529,300 | 0.4% | 95.7% |
| _CHECK_PEP_523 | 2,529,300 | 0.4% | 96.1% |
| _CHECK_FUNCTION_EXACT_ARGS | 2,529,300 | 0.4% | 96.6% |
| RESUME_CHECK | 1,908,960 | 0.3% | 96.9% |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 1,860,240 | 0.3% | 97.2% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 1,860,240 | 0.3% | 97.6% |
| _GUARD_BOTH_INT | 1,793,100 | 0.3% | 97.9% |
| CALL_BUILTIN_O | 1,713,000 | 0.3% | 98.2% |
| TO_BOOL_INT | 1,281,420 | 0.2% | 98.4% |
| CALL_LEN | 1,246,920 | 0.2% | 98.6% |
| _BINARY_OP_SUBTRACT_INT | 966,720 | 0.2% | 98.8% |
| BINARY_OP | 855,180 | 0.2% | 99.0% |
| _BINARY_OP_ADD_INT | 826,380 | 0.1% | 99.1% |
| TO_BOOL_BOOL | 771,900 | 0.1% | 99.2% |
| STORE_SUBSCR_LIST_INT | 762,240 | 0.1% | 99.4% |
| TO_BOOL | 692,460 | 0.1% | 99.5% |
| COPY | 627,480 | 0.1% | 99.6% |
| UNARY_NOT | 625,860 | 0.1% | 99.7% |
| BINARY_SUBSCR_LIST_INT | 440,400 | 0.1% | 99.8% |
| BINARY_SLICE | 384,720 | 0.1% | 99.9% |
| COMPARE_OP_INT | 312,960 | 0.1% | 99.9% |
| TO_BOOL_NONE | 228,060 | 0.0% | 100.0% |
| BINARY_SUBSCR_DICT | 196,080 | 0.0% | 100.0% |
| _ITER_CHECK_TUPLE | 9,720 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 9,720 | 0.0% | 100.0% |
| _LOAD_GLOBAL_BUILTINS | 6,240 | 0.0% | 100.0% |
| _GUARD_BUILTINS_VERSION | 6,240 | 0.0% | 100.0% |
| _ITER_NEXT_TUPLE | 4,440 | 0.0% | 100.0% |
| TO_BOOL_LIST | 1,920 | 0.0% | 100.0% |
| STORE_SUBSCR_DICT | 1,620 | 0.0% | 100.0% |
| DELETE_SUBSCR | 1,260 | 0.0% | 100.0% |
| GET_ITER | 780 | 0.0% | 100.0% |
| BINARY_SUBSCR_TUPLE_INT | 780 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_METHOD_NO_DICT | 5,120 |
| FOR_ITER | 3,200 |
| LOAD_ATTR_METHOD_WITH_VALUES | 20 |


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
Stats gathered on: 2023-10-03
