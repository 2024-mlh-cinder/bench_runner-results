
# Pystats results

- benchmark: mdp
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,288,389,600 | 15.9% | 15.9% |  |
| STORE_FAST | 630,318,600 | 7.8% | 23.8% |  |
| RESUME_CHECK | 435,680,580 | 5.4% | 29.1% | 0.0% |
| LOAD_DEREF | 375,030,960 | 4.6% | 33.8% |  |
| FOR_ITER_LIST | 338,556,480 | 4.2% | 38.0% | 0.1% |
| INTERPRETER_EXIT | 326,917,780 | 4.0% | 42.0% |  |
| JUMP_BACKWARD | 318,923,520 | 3.9% | 46.0% |  |
| BINARY_SUBSCR | 311,407,500 | 3.9% | 49.8% |  |
| POP_TOP | 291,722,640 | 3.6% | 53.4% |  |
| LOAD_FAST_LOAD_FAST | 286,479,480 | 3.5% | 57.0% |  |
| YIELD_VALUE | 243,371,880 | 3.0% | 60.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 220,176,960 | 2.7% | 62.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 210,931,680 | 2.6% | 65.3% |  |
| LOAD_CONST | 194,528,400 | 2.4% | 67.7% |  |
| POP_JUMP_IF_FALSE | 147,576,480 | 1.8% | 69.6% |  |
| RETURN_VALUE | 144,879,420 | 1.8% | 71.4% |  |
| LOAD_GLOBAL_BUILTIN | 129,654,840 | 1.6% | 73.0% |  |
| LOAD_GLOBAL_MODULE | 129,189,340 | 1.6% | 74.6% |  |
| CALL_PY_EXACT_ARGS | 123,722,040 | 1.5% | 76.1% | 1.0% |
| COPY_FREE_VARS | 106,289,220 | 1.3% | 77.4% |  |
| BINARY_OP | 99,975,340 | 1.2% | 78.6% |  |
| LOAD_ATTR_SLOT | 97,512,480 | 1.2% | 79.9% |  |
| BINARY_OP_MULTIPLY_INT | 90,143,100 | 1.1% | 81.0% |  |
| PUSH_NULL | 75,078,240 | 0.9% | 81.9% |  |
| COMPARE_OP_INT | 74,835,300 | 0.9% | 82.8% |  |
| STORE_SUBSCR | 68,569,140 | 0.8% | 83.7% |  |
| CALL | 60,795,560 | 0.8% | 84.4% |  |
| STORE_ATTR_SLOT | 60,078,600 | 0.7% | 85.2% |  |
| STORE_FAST_STORE_FAST | 56,430,420 | 0.7% | 85.9% |  |
| BUILD_TUPLE | 55,928,520 | 0.7% | 86.6% |  |
| LOAD_ATTR | 49,369,180 | 0.6% | 87.2% |  |
| GET_ITER | 49,348,020 | 0.6% | 87.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 47,622,780 | 0.6% | 88.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 47,518,020 | 0.6% | 89.0% |  |
| RETURN_CONST | 47,429,340 | 0.6% | 89.5% |  |
| MAKE_FUNCTION | 47,274,300 | 0.6% | 90.1% |  |
| BINARY_SUBSCR_DICT | 47,274,120 | 0.6% | 90.7% |  |
| RETURN_GENERATOR | 47,124,420 | 0.6% | 91.3% |  |
| NOP | 47,054,640 | 0.6% | 91.9% |  |
| SET_FUNCTION_ATTRIBUTE | 46,765,320 | 0.6% | 92.5% |  |
| SWAP | 46,275,840 | 0.6% | 93.0% |  |
| CALL_BUILTIN_FAST | 44,122,020 | 0.5% | 93.6% |  |
| COPY | 43,834,260 | 0.5% | 94.1% |  |
| LOAD_ATTR_MODULE | 43,683,100 | 0.5% | 94.7% |  |
| CONTAINS_OP | 33,755,700 | 0.4% | 95.1% |  |
| BINARY_SUBSCR_TUPLE_INT | 33,176,640 | 0.4% | 95.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 0.4% | 95.9% |  |
| LOAD_SUPER_ATTR_METHOD | 30,039,300 | 0.4% | 96.3% |  |
| BINARY_OP_ADD_INT | 26,699,820 | 0.3% | 96.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,508,120 | 0.3% | 96.9% |  |
| TO_BOOL_BOOL | 25,914,900 | 0.3% | 97.2% |  |
| POP_JUMP_IF_TRUE | 24,877,680 | 0.3% | 97.5% |  |
| CALL_ISINSTANCE | 24,817,200 | 0.3% | 97.8% |  |
| COMPARE_OP_FLOAT | 23,389,440 | 0.3% | 98.1% |  |
| STORE_FAST_LOAD_FAST | 18,469,260 | 0.2% | 98.4% |  |
| FOR_ITER_RANGE | 17,563,320 | 0.2% | 98.6% |  |
| LIST_APPEND | 17,124,420 | 0.2% | 98.8% |  |
| JUMP_FORWARD | 10,279,860 | 0.1% | 98.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 8,762,280 | 0.1% | 99.0% | 0.4% |
| FOR_ITER | 8,463,460 | 0.1% | 99.1% |  |
| IS_OP | 7,584,780 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 7,584,780 | 0.1% | 99.3% |  |
| POP_JUMP_IF_NOT_NONE | 7,086,360 | 0.1% | 99.4% |  |
| EXTENDED_ARG | 7,086,360 | 0.1% | 99.5% |  |
| CALL_BUILTIN_CLASS | 5,199,960 | 0.1% | 99.6% |  |
| UNARY_NEGATIVE | 4,332,000 | 0.1% | 99.6% |  |
| CALL_LEN | 3,704,880 | 0.0% | 99.7% |  |
| CALL_KW | 3,485,340 | 0.0% | 99.7% |  |
| TO_BOOL | 3,266,620 | 0.0% | 99.7% |  |
| LOAD_ATTR_PROPERTY | 2,436,160 | 0.0% | 99.8% | 0.9% |
| MAP_ADD | 2,318,700 | 0.0% | 99.8% |  |
| FOR_ITER_TUPLE | 2,056,020 | 0.0% | 99.8% | 8.7% |
| TO_BOOL_LIST | 1,854,120 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,634,520 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 1,241,460 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,211,800 | 0.0% | 99.9% | 55.4% |
| COMPARE_OP | 1,205,980 | 0.0% | 99.9% |  |
| COMPARE_OP_STR | 916,740 | 0.0% | 99.9% |  |
| BUILD_LIST | 878,640 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 760,080 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 658,080 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 578,760 | 0.0% | 100.0% |  |
| BUILD_MAP | 540,600 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 289,260 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 289,260 | 0.0% | 100.0% |  |
| POP_EXCEPT | 289,260 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 289,260 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 219,720 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 219,600 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 219,540 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 219,540 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 79,380 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 6,840 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 560 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 360 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 240 | 0.0% | 100.0% |  |
| STORE_DEREF | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 120 | 0.0% | 100.0% |  |
| MAKE_CELL | 120 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 60 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_DEREF LOAD_FAST | 339,014,640 | 4.2% | 4.2% |
| JUMP_BACKWARD FOR_ITER_LIST | 291,298,680 | 3.6% | 7.8% |
| LOAD_FAST BINARY_SUBSCR | 289,703,040 | 3.6% | 11.4% |
| CACHE RESUME_CHECK | 249,754,060 | 3.1% | 14.5% |
| STORE_FAST LOAD_DEREF | 245,153,220 | 3.0% | 17.5% |
| POP_TOP JUMP_BACKWARD | 243,730,080 | 3.0% | 20.5% |
| YIELD_VALUE INTERPRETER_EXIT | 243,371,880 | 3.0% | 23.5% |
| RESUME_CHECK POP_TOP | 243,371,880 | 3.0% | 26.6% |
| BINARY_SUBSCR LOAD_FAST | 232,772,040 | 2.9% | 29.4% |
| STORE_FAST STORE_FAST | 211,332,900 | 2.6% | 32.1% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 210,931,680 | 2.6% | 34.7% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 210,931,680 | 2.6% | 37.3% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 210,931,680 | 2.6% | 39.9% |
| BINARY_OP_MULTIPLY_FLOAT YIELD_VALUE | 210,931,680 | 2.6% | 42.5% |
| LOAD_FAST LOAD_ATTR_SLOT | 97,512,480 | 1.2% | 43.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 94,920,960 | 1.2% | 44.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 86,997,960 | 1.1% | 46.0% |
| LOAD_FAST LOAD_CONST | 85,227,960 | 1.1% | 47.0% |
| FOR_ITER_LIST STORE_FAST | 80,201,040 | 1.0% | 48.0% |
| RESUME_CHECK LOAD_FAST | 80,051,220 | 1.0% | 49.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 76,573,680 | 0.9% | 49.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 74,835,300 | 0.9% | 50.9% |
| LOAD_CONST COMPARE_OP_INT | 71,151,180 | 0.9% | 51.7% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 66,173,160 | 0.8% | 52.6% |
| COPY_FREE_VARS RESUME_CHECK | 59,523,900 | 0.7% | 53.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 59,108,400 | 0.7% | 54.0% |
| STORE_FAST LOAD_FAST | 57,761,520 | 0.7% | 54.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 53,490,660 | 0.7% | 55.4% |
| RETURN_VALUE RETURN_VALUE | 50,774,340 | 0.6% | 56.0% |
| LOAD_ATTR_SLOT LOAD_FAST | 48,756,240 | 0.6% | 56.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 48,602,380 | 0.6% | 57.2% |
| LOAD_FAST BINARY_OP | 48,377,260 | 0.6% | 57.8% |
| LOAD_FAST BUILD_TUPLE | 48,290,880 | 0.6% | 58.4% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 47,622,720 | 0.6% | 59.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 47,622,720 | 0.6% | 59.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 47,344,140 | 0.6% | 60.2% |
| LOAD_CONST MAKE_FUNCTION | 47,274,300 | 0.6% | 60.8% |
| LOAD_FAST BINARY_SUBSCR_DICT | 47,274,120 | 0.6% | 61.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 47,228,560 | 0.6% | 62.0% |
| RETURN_CONST INTERPRETER_EXIT | 47,150,400 | 0.6% | 62.5% |
| POP_TOP RESUME_CHECK | 47,124,420 | 0.6% | 63.1% |
| CACHE POP_TOP | 47,124,420 | 0.6% | 63.7% |
| RETURN_VALUE GET_ITER | 47,054,700 | 0.6% | 64.3% |
| GET_ITER CALL_PY_EXACT_ARGS | 47,054,700 | 0.6% | 64.9% |
| RESUME_CHECK NOP | 47,054,580 | 0.6% | 65.5% |
| NOP LOAD_FAST | 47,054,580 | 0.6% | 66.0% |
| LOAD_FAST STORE_SUBSCR | 46,923,960 | 0.6% | 66.6% |
| BUILD_TUPLE LOAD_CONST | 46,904,760 | 0.6% | 67.2% |
| LOAD_FAST FOR_ITER_LIST | 46,808,640 | 0.6% | 67.8% |
| FOR_ITER_LIST RETURN_CONST | 46,808,640 | 0.6% | 68.4% |
| SET_FUNCTION_ATTRIBUTE LOAD_FAST | 46,765,320 | 0.6% | 68.9% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 46,765,320 | 0.6% | 69.5% |
| COPY_FREE_VARS RETURN_GENERATOR | 46,765,320 | 0.6% | 70.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 46,765,320 | 0.6% | 70.7% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 46,765,320 | 0.6% | 71.3% |
| LOAD_ATTR_SLOT STORE_FAST_STORE_FAST | 45,905,880 | 0.6% | 71.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 43,683,040 | 0.5% | 72.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 42,696,840 | 0.5% | 72.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 40,613,200 | 0.5% | 73.4% |
| CALL_BUILTIN_FAST STORE_FAST | 40,613,040 | 0.5% | 73.9% |
| CALL STORE_FAST | 37,888,440 | 0.5% | 74.4% |
| LOAD_FAST RETURN_VALUE | 37,588,620 | 0.5% | 74.8% |
| RETURN_VALUE INTERPRETER_EXIT | 36,395,500 | 0.5% | 75.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 36,095,880 | 0.4% | 75.7% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 36,079,680 | 0.4% | 76.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 33,829,860 | 0.4% | 76.6% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 33,755,700 | 0.4% | 77.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 33,466,320 | 0.4% | 77.4% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 33,176,640 | 0.4% | 77.8% |
| LOAD_DEREF PUSH_NULL | 32,750,460 | 0.4% | 78.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 31,715,820 | 0.4% | 78.6% |
| RETURN_GENERATOR CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 0.4% | 79.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS LOAD_DEREF | 31,287,480 | 0.4% | 79.4% |
| BINARY_SUBSCR YIELD_VALUE | 30,955,680 | 0.4% | 79.8% |
| LOAD_FAST CALL | 30,917,500 | 0.4% | 80.2% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 30,260,100 | 0.4% | 80.6% |
| STORE_ATTR_SLOT LOAD_FAST | 30,039,300 | 0.4% | 80.9% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 30,039,300 | 0.4% | 81.3% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 30,039,300 | 0.4% | 81.7% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 30,039,300 | 0.4% | 82.0% |
| CACHE COPY_FREE_VARS | 30,039,300 | 0.4% | 82.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 29,441,220 | 0.4% | 82.8% |
| BINARY_OP BINARY_OP_MULTIPLY_INT | 27,195,480 | 0.3% | 83.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 26,461,960 | 0.3% | 83.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 26,419,920 | 0.3% | 83.8% |
| CALL_BOUND_METHOD_EXACT_ARGS COPY_FREE_VARS | 26,218,740 | 0.3% | 84.1% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_MODULE | 26,159,400 | 0.3% | 84.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 25,914,900 | 0.3% | 84.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 24,817,200 | 0.3% | 85.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 24,685,380 | 0.3% | 85.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 24,392,080 | 0.3% | 85.7% |
| BINARY_SUBSCR_TUPLE_INT LOAD_CONST | 23,961,300 | 0.3% | 86.0% |
| BINARY_SUBSCR LOAD_DEREF | 23,468,760 | 0.3% | 86.2% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 23,451,360 | 0.3% | 86.5% |
| STORE_SUBSCR LOAD_GLOBAL_BUILTIN | 23,382,660 | 0.3% | 86.8% |
| COMPARE_OP_FLOAT POP_JUMP_IF_TRUE | 23,382,660 | 0.3% | 87.1% |
| BINARY_SUBSCR COMPARE_OP_FLOAT | 23,382,660 | 0.3% | 87.4% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 23,358,960 | 0.3% | 87.7% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 23,303,340 | 0.3% | 88.0% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 23,172,480 | 0.3% | 88.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 249,754,060 | 76.4% |
| POP_TOP | 47,124,420 | 14.4% |
| COPY_FREE_VARS | 30,039,300 | 9.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,703,040 | 93.0% |
| COPY | 21,628,260 | 6.9% |
| BINARY_SUBSCR | 76,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 232,772,040 | 74.7% |
| YIELD_VALUE | 30,955,680 | 9.9% |
| LOAD_DEREF | 23,468,760 | 7.5% |
| COMPARE_OP_FLOAT | 23,382,660 | 7.5% |
| LOAD_FAST_LOAD_FAST | 666,060 | 0.2% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 289,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 289,260 | 100.0% |


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

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 47,054,700 | 95.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 979,620 | 2.0% |
| LOAD_FAST | 445,860 | 0.9% |
| CALL_BUILTIN_CLASS | 439,080 | 0.9% |
| CALL | 219,600 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 47,054,700 | 95.4% |
| LOAD_FAST_AND_CLEAR | 840,300 | 1.7% |
| FOR_ITER | 798,060 | 1.6% |
| FOR_ITER_LIST | 445,740 | 0.9% |
| FOR_ITER_TUPLE | 209,160 | 0.4% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 243,371,880 | 74.4% |
| RETURN_CONST | 47,150,400 | 14.4% |
| RETURN_VALUE | 36,395,500 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 47,274,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 46,765,320 | 98.9% |
| LOAD_FAST | 289,380 | 0.6% |
| LOAD_CONST | 219,540 | 0.5% |
| CALL | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 47,054,580 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,054,580 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 289,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 289,260 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 243,371,880 | 83.4% |
| CACHE | 47,124,420 | 16.2% |
| CALL_METHOD_DESCRIPTOR_O | 658,080 | 0.2% |
| POP_JUMP_IF_FALSE | 289,260 | 0.1% |
| RETURN_CONST | 278,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 243,730,080 | 83.5% |
| RESUME_CHECK | 47,124,420 | 16.2% |
| LOAD_FAST | 578,640 | 0.2% |
| JUMP_FORWARD | 289,380 | 0.1% |
| RETURN_CONST | 60 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 289,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 289,260 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40,613,200 | 54.1% |
| LOAD_DEREF | 32,750,460 | 43.6% |
| LOAD_FAST | 1,714,560 | 2.3% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 66,173,160 | 88.1% |
| LOAD_FAST | 8,685,360 | 11.6% |
| LOAD_GLOBAL_MODULE | 219,540 | 0.3% |
| CALL | 180 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 46,765,320 | 99.2% |
| CALL_PY_EXACT_ARGS | 359,100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 66.4% |
| CALL | 15,477,840 | 32.8% |
| CALL_METHOD_DESCRIPTOR_O | 289,380 | 0.6% |
| CALL_BUILTIN_CLASS | 69,720 | 0.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 50,774,340 | 35.0% |
| BINARY_SUBSCR_DICT | 46,765,320 | 32.3% |
| LOAD_FAST | 37,588,620 | 25.9% |
| CALL_BUILTIN_FAST | 3,508,980 | 2.4% |
| LOAD_ATTR_SLOT | 2,850,360 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 50,774,340 | 35.0% |
| GET_ITER | 47,054,700 | 32.5% |
| INTERPRETER_EXIT | 36,395,500 | 25.1% |
| STORE_FAST | 7,880,700 | 5.4% |
| CALL | 2,411,340 | 1.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,923,960 | 68.4% |
| SWAP | 21,628,260 | 31.5% |
| STORE_SUBSCR | 16,800 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 23,382,660 | 34.1% |
| JUMP_BACKWARD | 21,628,260 | 31.5% |
| LOAD_DEREF | 15,723,060 | 22.9% |
| JUMP_FORWARD | 7,738,920 | 11.3% |
| LOAD_FAST | 79,380 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,265,820 | 100.0% |
| TO_BOOL | 800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,265,800 | 100.0% |
| TO_BOOL | 800 | 0.0% |
| TO_BOOL_LIST | 20 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,126,360 | 72.2% |
| BINARY_SUBSCR_TUPLE_INT | 1,205,640 | 27.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,126,360 | 72.2% |
| LOAD_FAST | 1,205,640 | 27.8% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,377,260 | 48.4% |
| LOAD_FAST_LOAD_FAST | 30,260,100 | 30.3% |
| LOAD_CONST | 18,005,760 | 18.0% |
| CALL | 1,205,640 | 1.2% |
| BINARY_OP | 690,620 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 27,195,480 | 27.2% |
| SWAP | 21,628,260 | 21.6% |
| STORE_FAST | 19,333,260 | 19.3% |
| LIST_APPEND | 17,124,120 | 17.1% |
| LOAD_FAST_LOAD_FAST | 11,138,940 | 11.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 439,200 | 50.0% |
| LOAD_FAST | 219,660 | 25.0% |
| LOAD_FAST_LOAD_FAST | 219,540 | 25.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 439,200 | 50.0% |
| CALL | 219,600 | 25.0% |
| LOAD_FAST_LOAD_FAST | 219,540 | 25.0% |
| RETURN_VALUE | 120 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 401,100 | 74.2% |
| CALL | 139,440 | 25.8% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 401,100 | 74.2% |
| RETURN_VALUE | 139,440 | 25.8% |
| LOAD_FAST | 60 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,290,880 | 86.3% |
| LOAD_FAST_LOAD_FAST | 3,266,040 | 5.8% |
| BINARY_SUBSCR_TUPLE_INT | 2,318,700 | 4.1% |
| LOAD_CONST | 1,634,580 | 2.9% |
| CALL | 278,880 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 46,904,760 | 83.9% |
| COPY | 3,126,360 | 5.6% |
| YIELD_VALUE | 1,484,520 | 2.7% |
| LOAD_FAST | 1,294,620 | 2.3% |
| RETURN_VALUE | 1,205,640 | 2.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,917,500 | 50.9% |
| RETURN_GENERATOR | 15,477,840 | 25.5% |
| CALL | 3,500,740 | 5.8% |
| LOAD_FAST_LOAD_FAST | 3,265,860 | 5.4% |
| BINARY_OP_ADD_INT | 3,265,800 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 37,888,440 | 62.3% |
| LOAD_DEREF | 15,477,840 | 25.5% |
| CALL | 3,500,740 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 1,205,640 | 2.0% |
| BINARY_OP | 1,205,640 | 2.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 219,600 | 99.9% |
| STORE_FAST | 60 | 0.0% |
| CALL_INTRINSIC_1 | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 219,540 | 99.9% |
| RETURN_VALUE | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |


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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,485,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 3,265,800 | 93.7% |
| STORE_FAST | 219,540 | 6.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,205,640 | 100.0% |
| COMPARE_OP | 300 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,205,640 | 100.0% |
| COMPARE_OP | 300 | 0.0% |
| COMPARE_OP_FLOAT | 40 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 33,755,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,466,320 | 99.1% |
| POP_JUMP_IF_TRUE | 289,380 | 0.9% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 21,628,260 | 49.3% |
| LOAD_FAST_LOAD_FAST | 18,501,900 | 42.2% |
| BUILD_TUPLE | 3,126,360 | 7.1% |
| SWAP | 498,420 | 1.1% |
| BINARY_OP | 79,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 21,628,260 | 49.3% |
| BINARY_SUBSCR | 21,628,260 | 49.3% |
| IS_OP | 498,420 | 1.1% |
| LOAD_DEREF | 79,320 | 0.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 46,765,320 | 44.0% |
| CACHE | 30,039,300 | 28.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,218,740 | 24.7% |
| CALL_KW | 3,265,800 | 3.1% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 59,523,900 | 56.0% |
| RETURN_GENERATOR | 46,765,320 | 44.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,086,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 7,086,360 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,262,160 | 85.8% |
| GET_ITER | 798,060 | 9.4% |
| SWAP | 401,160 | 4.7% |
| FOR_ITER | 2,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,262,160 | 85.8% |
| LOAD_FAST | 519,180 | 6.1% |
| SWAP | 401,160 | 4.7% |
| RETURN_CONST | 278,880 | 3.3% |
| FOR_ITER | 2,080 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,587,940 | 86.9% |
| COPY | 498,420 | 6.6% |
| CALL_TYPE_1 | 498,420 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,584,780 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 243,730,080 | 76.4% |
| POP_JUMP_IF_TRUE | 23,303,340 | 7.3% |
| STORE_SUBSCR | 21,628,260 | 6.8% |
| LIST_APPEND | 17,124,420 | 5.4% |
| POP_JUMP_IF_FALSE | 10,379,580 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 291,298,680 | 91.3% |
| FOR_ITER_RANGE | 17,124,180 | 5.4% |
| FOR_ITER | 7,262,160 | 2.3% |
| LOAD_FAST | 1,641,060 | 0.5% |
| FOR_ITER_TUPLE | 1,597,440 | 0.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 7,738,920 | 75.3% |
| POP_JUMP_IF_FALSE | 498,420 | 4.8% |
| JUMP_FORWARD | 498,420 | 4.8% |
| STORE_FAST | 382,740 | 3.7% |
| LOAD_CONST | 363,120 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 7,738,920 | 75.3% |
| LOAD_FAST | 1,077,060 | 10.5% |
| STORE_FAST | 582,660 | 5.7% |
| JUMP_FORWARD | 498,420 | 4.8% |
| LOAD_FAST_LOAD_FAST | 243,300 | 2.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 17,124,120 | 100.0% |
| LOAD_FAST | 180 | 0.0% |
| JUMP_FORWARD | 60 | 0.0% |
| BUILD_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 17,124,420 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 22,953,000 | 46.5% |
| LOAD_FAST | 18,523,820 | 37.5% |
| LOAD_ATTR | 4,716,280 | 9.6% |
| BINARY_SUBSCR_TUPLE_INT | 3,175,620 | 6.4% |
| LOAD_ATTR_PROPERTY | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 22,952,940 | 46.5% |
| LOAD_DEREF | 6,531,600 | 13.2% |
| LOAD_FAST | 4,802,580 | 9.7% |
| LOAD_ATTR | 4,716,280 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 3,265,800 | 6.6% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 85,227,960 | 43.8% |
| BUILD_TUPLE | 46,904,760 | 24.1% |
| BINARY_SUBSCR_TUPLE_INT | 23,961,300 | 12.3% |
| BINARY_OP_MULTIPLY_INT | 17,563,200 | 9.0% |
| STORE_ATTR_SLOT | 6,587,940 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 71,151,180 | 36.6% |
| MAKE_FUNCTION | 47,274,300 | 24.3% |
| BINARY_SUBSCR_TUPLE_INT | 33,176,640 | 17.1% |
| BINARY_OP | 18,005,760 | 9.3% |
| LOAD_FAST | 12,015,480 | 6.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 245,153,220 | 65.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 8.3% |
| BINARY_SUBSCR | 23,468,760 | 6.3% |
| POP_JUMP_IF_FALSE | 22,953,000 | 6.1% |
| STORE_SUBSCR | 15,723,060 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 339,014,640 | 90.4% |
| PUSH_NULL | 32,750,460 | 8.7% |
| COMPARE_OP_INT | 3,265,800 | 0.9% |
| LIST_EXTEND | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 339,014,640 | 26.3% |
| BINARY_SUBSCR | 232,772,040 | 18.1% |
| LOAD_GLOBAL_BUILTIN | 86,997,960 | 6.8% |
| RESUME_CHECK | 80,051,220 | 6.2% |
| STORE_FAST | 57,761,520 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 289,703,040 | 22.5% |
| BINARY_OP_MULTIPLY_FLOAT | 210,931,680 | 16.4% |
| LOAD_ATTR_SLOT | 97,512,480 | 7.6% |
| LOAD_CONST | 85,227,960 | 6.6% |
| CALL_PY_EXACT_ARGS | 48,602,380 | 3.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 840,300 | 67.7% |
| LOAD_FAST_AND_CLEAR | 401,160 | 32.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 840,300 | 67.7% |
| LOAD_FAST_AND_CLEAR | 401,160 | 32.3% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 219,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 219,540 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 94,920,960 | 33.1% |
| PUSH_NULL | 66,173,160 | 23.1% |
| POP_JUMP_IF_FALSE | 26,419,920 | 9.2% |
| STORE_ATTR_SLOT | 23,451,360 | 8.2% |
| BINARY_OP_MULTIPLY_INT | 23,172,480 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 53,490,660 | 18.7% |
| CALL_BUILTIN_FAST | 42,696,840 | 14.9% |
| BINARY_OP_MULTIPLY_INT | 36,079,680 | 12.6% |
| LOAD_FAST | 33,829,860 | 11.8% |
| CONTAINS_OP | 33,755,700 | 11.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 35.7% |
| LOAD_CONST | 100 | 17.9% |
| LOAD_GLOBAL_MODULE | 80 | 14.3% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 10.7% |
| RETURN_VALUE | 40 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 420 | 75.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 21.4% |
| LOAD_ATTR | 20 | 3.6% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 60 | 50.0% |
| CALL_PY_EXACT_ARGS | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| MAKE_CELL | 60 | 50.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,205,640 | 52.0% |
| LOAD_FAST | 1,113,060 | 48.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,318,700 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 74,835,300 | 50.7% |
| CONTAINS_OP | 33,466,320 | 22.7% |
| TO_BOOL_BOOL | 25,914,900 | 17.6% |
| IS_OP | 7,584,780 | 5.1% |
| TO_BOOL | 3,265,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,095,880 | 24.5% |
| LOAD_FAST_LOAD_FAST | 26,419,920 | 17.9% |
| LOAD_GLOBAL_BUILTIN | 24,685,380 | 16.7% |
| LOAD_GLOBAL_MODULE | 24,392,080 | 16.5% |
| LOAD_DEREF | 22,953,000 | 15.6% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 7,086,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,086,360 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 23,382,660 | 94.0% |
| COMPARE_OP | 1,205,640 | 4.8% |
| CONTAINS_OP | 289,380 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 23,303,340 | 93.7% |
| LOAD_FAST | 1,495,020 | 6.0% |
| LOAD_DEREF | 79,320 | 0.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 46,808,640 | 98.7% |
| FOR_ITER_TUPLE | 315,780 | 0.7% |
| FOR_ITER | 278,880 | 0.6% |
| RESUME_CHECK | 25,980 | 0.1% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 47,150,400 | 99.4% |
| POP_TOP | 278,880 | 0.6% |
| EXIT_INIT_CHECK | 60 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 46,765,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,765,320 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 120 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 50.0% |
| STORE_DEREF | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| STORE_DEREF | 60 | 50.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 211,332,900 | 33.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 210,931,680 | 33.5% |
| FOR_ITER_LIST | 80,201,040 | 12.7% |
| CALL_BUILTIN_FAST | 40,613,040 | 6.4% |
| CALL | 37,888,440 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 245,153,220 | 38.9% |
| STORE_FAST | 211,332,900 | 33.5% |
| LOAD_FAST_LOAD_FAST | 94,920,960 | 15.1% |
| LOAD_FAST | 57,761,520 | 9.2% |
| LOAD_GLOBAL_MODULE | 18,256,480 | 2.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 17,124,120 | 92.7% |
| FOR_ITER_TUPLE | 1,179,120 | 6.4% |
| FOR_ITER_LIST | 166,020 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,124,120 | 92.7% |
| LOAD_CONST | 1,345,140 | 7.3% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 45,905,880 | 81.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,245,280 | 16.4% |
| UNPACK_SEQUENCE_TUPLE | 760,080 | 1.3% |
| BINARY_OP_MULTIPLY_INT | 439,080 | 0.8% |
| STORE_FAST_STORE_FAST | 80,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,441,220 | 52.2% |
| LOAD_GLOBAL_MODULE | 26,159,400 | 46.4% |
| STORE_FAST | 679,980 | 1.2% |
| STORE_FAST_STORE_FAST | 80,100 | 0.1% |
| LOAD_CONST | 69,720 | 0.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 21,628,260 | 46.7% |
| BINARY_OP | 21,628,260 | 46.7% |
| LOAD_FAST_AND_CLEAR | 840,300 | 1.8% |
| LOAD_GLOBAL_BUILTIN | 498,420 | 1.1% |
| BUILD_LIST | 439,200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 21,628,260 | 46.7% |
| STORE_SUBSCR | 21,628,260 | 46.7% |
| STORE_FAST | 840,240 | 1.8% |
| COPY | 498,420 | 1.1% |
| BUILD_LIST | 439,200 | 0.9% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 210,931,680 | 86.7% |
| BINARY_SUBSCR | 30,955,680 | 12.7% |
| BUILD_TUPLE | 1,484,520 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 243,371,880 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 79,360 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 79,380 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 21,628,260 | 81.0% |
| LOAD_FAST | 3,265,800 | 12.2% |
| BINARY_OP | 920,940 | 3.4% |
| LOAD_CONST | 884,820 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,423,160 | 65.3% |
| LOAD_FAST_LOAD_FAST | 5,571,720 | 20.9% |
| CALL | 3,265,800 | 12.2% |
| LOAD_FAST | 439,080 | 1.6% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 210,931,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 210,931,680 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,079,680 | 40.0% |
| BINARY_OP | 27,195,480 | 30.2% |
| LOAD_FAST | 23,358,960 | 25.9% |
| LOAD_ATTR | 2,825,880 | 3.1% |
| LOAD_CONST | 658,620 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,172,480 | 25.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 22,513,860 | 25.0% |
| BINARY_OP_ADD_INT | 21,628,260 | 24.0% |
| LOAD_CONST | 17,563,200 | 19.5% |
| LOAD_FAST | 2,303,340 | 2.6% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 6,700 | 98.0% |
| LOAD_FAST | 80 | 1.2% |
| BINARY_OP | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,720 | 98.2% |
| STORE_FAST | 60 | 0.9% |
| CALL_BUILTIN_O | 40 | 0.6% |
| CALL | 20 | 0.3% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 219,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 219,540 | 100.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,274,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 46,765,320 | 98.9% |
| PUSH_EXC_INFO | 289,260 | 0.6% |
| STORE_FAST | 219,540 | 0.5% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 219,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 219,540 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,176,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,961,300 | 72.2% |
| LOAD_ATTR | 3,175,620 | 9.6% |
| BUILD_TUPLE | 2,318,700 | 7.0% |
| LOAD_FAST | 2,226,120 | 6.7% |
| UNARY_NEGATIVE | 1,205,640 | 3.6% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
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
| BINARY_OP_MULTIPLY_INT | 22,513,860 | 84.9% |
| CALL_BUILTIN_CLASS | 3,265,800 | 12.3% |
| LOAD_FAST_LOAD_FAST | 439,080 | 1.7% |
| LOAD_FAST | 289,380 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 26,218,740 | 98.9% |
| RESUME_CHECK | 289,380 | 1.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,471,480 | 86.0% |
| LOAD_CONST | 439,080 | 8.4% |
| CALL_FUNCTION_EX | 219,540 | 4.2% |
| RETURN_GENERATOR | 69,720 | 1.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 3,265,800 | 62.8% |
| MAP_ADD | 1,205,640 | 23.2% |
| GET_ITER | 439,080 | 8.4% |
| LOAD_CONST | 219,540 | 4.2% |
| STORE_FAST | 69,840 | 1.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 42,696,840 | 96.8% |
| BINARY_OP_MULTIPLY_INT | 1,425,180 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40,613,040 | 92.0% |
| RETURN_VALUE | 3,508,980 | 8.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 31,287,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 31,287,480 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 22,733,400 | 91.6% |
| LOAD_ATTR_MODULE | 1,644,720 | 6.6% |
| LOAD_GLOBAL_BUILTIN | 439,080 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 24,817,200 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,704,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,265,800 | 88.1% |
| BINARY_OP | 439,080 | 11.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,380 | 50.0% |
| BUILD_TUPLE | 289,380 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 578,760 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,634,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,634,520 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,199,160 | 99.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,640 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 979,620 | 80.8% |
| LOAD_CONST | 219,540 | 18.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,640 | 1.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 368,700 | 56.0% |
| RETURN_GENERATOR | 289,380 | 44.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 658,080 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,602,380 | 39.3% |
| GET_ITER | 47,054,700 | 38.0% |
| LOAD_FAST_LOAD_FAST | 22,691,280 | 18.3% |
| UNARY_NEGATIVE | 3,126,360 | 2.5% |
| LOAD_ATTR_MODULE | 1,425,180 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,573,680 | 61.9% |
| COPY_FREE_VARS | 46,765,320 | 37.8% |
| RETURN_GENERATOR | 359,100 | 0.3% |
| CALL_PY_EXACT_ARGS | 23,880 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,584,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,086,360 | 93.4% |
| IS_OP | 498,420 | 6.6% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 23,382,660 | 100.0% |
| LOAD_FAST | 6,740 | 0.0% |
| COMPARE_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 23,382,660 | 100.0% |
| POP_JUMP_IF_FALSE | 6,780 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 71,151,180 | 95.1% |
| LOAD_DEREF | 3,265,800 | 4.4% |
| LOAD_FAST_LOAD_FAST | 418,320 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 74,835,300 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 916,740 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 557,760 | 60.8% |
| POP_JUMP_IF_FALSE | 358,980 | 39.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 291,298,680 | 86.0% |
| LOAD_FAST | 46,808,640 | 13.8% |
| GET_ITER | 445,740 | 0.1% |
| FOR_ITER_TUPLE | 3,360 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 210,931,680 | 62.3% |
| STORE_FAST | 80,201,040 | 23.7% |
| RETURN_CONST | 46,808,640 | 13.8% |
| JUMP_BACKWARD | 439,080 | 0.1% |
| STORE_FAST_LOAD_FAST | 166,020 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 17,124,180 | 97.5% |
| SWAP | 439,080 | 2.5% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 17,124,120 | 97.5% |
| SWAP | 439,080 | 2.5% |
| STORE_FAST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,597,440 | 77.7% |
| LOAD_FAST | 246,060 | 12.0% |
| GET_ITER | 209,160 | 10.2% |
| FOR_ITER_LIST | 3,360 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 1,179,120 | 57.3% |
| RETURN_CONST | 315,780 | 15.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 278,880 | 13.6% |
| STORE_FAST | 139,440 | 6.8% |
| LOAD_FAST | 139,440 | 6.8% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,228,560 | 99.4% |
| LOAD_FAST_LOAD_FAST | 289,260 | 0.6% |
| LOAD_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,344,140 | 99.6% |
| STORE_FAST | 173,580 | 0.4% |
| STORE_SUBSCR | 120 | 0.0% |
| SWAP | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,182,980 | 93.4% |
| RETURN_VALUE | 358,980 | 4.1% |
| LOAD_FAST_CHECK | 219,540 | 2.5% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,638,500 | 64.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,634,520 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,199,160 | 13.7% |
| LOAD_CONST | 289,380 | 3.3% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,622,720 | 100.0% |
| RETURN_VALUE | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,622,720 | 100.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 43,683,040 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40,613,200 | 93.0% |
| CALL_ISINSTANCE | 1,644,720 | 3.8% |
| CALL_PY_EXACT_ARGS | 1,425,180 | 3.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,435,760 | 100.0% |
| LOAD_ATTR | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,414,960 | 99.1% |
| BINARY_OP_MULTIPLY_INT | 20,800 | 0.9% |
| LOAD_ATTR | 400 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,512,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,756,240 | 50.0% |
| STORE_FAST_STORE_FAST | 45,905,880 | 47.1% |
| RETURN_VALUE | 2,850,360 | 2.9% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 59,108,400 | 45.6% |
| POP_JUMP_IF_FALSE | 24,685,380 | 19.0% |
| STORE_SUBSCR | 23,382,660 | 18.0% |
| POP_JUMP_IF_NOT_NONE | 7,086,360 | 5.5% |
| CALL_TYPE_1 | 7,086,360 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,997,960 | 67.1% |
| LOAD_GLOBAL_MODULE | 30,039,300 | 23.2% |
| IS_OP | 6,587,940 | 5.1% |
| LOAD_CONST | 3,924,420 | 3.0% |
| SWAP | 498,420 | 0.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,039,300 | 23.3% |
| LOAD_FAST | 26,461,960 | 20.5% |
| STORE_FAST_STORE_FAST | 26,159,400 | 20.2% |
| POP_JUMP_IF_FALSE | 24,392,080 | 18.9% |
| STORE_FAST | 18,256,480 | 14.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 43,683,040 | 33.8% |
| LOAD_FAST | 31,715,820 | 24.5% |
| LOAD_ATTR | 22,953,000 | 17.8% |
| CALL_ISINSTANCE | 22,733,400 | 17.6% |
| LOAD_FAST_LOAD_FAST | 6,148,200 | 4.8% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,039,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,039,300 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 249,754,060 | 57.3% |
| CALL_PY_EXACT_ARGS | 76,573,680 | 17.6% |
| COPY_FREE_VARS | 59,523,900 | 13.7% |
| POP_TOP | 47,124,420 | 10.8% |
| LOAD_ATTR_PROPERTY | 2,414,960 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 243,371,880 | 55.9% |
| LOAD_FAST | 80,051,220 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 59,108,400 | 13.6% |
| NOP | 47,054,580 | 10.8% |
| LOAD_DEREF | 3,265,860 | 0.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 66.7% |
| STORE_ATTR | 120 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 50.0% |
| LOAD_GLOBAL_MODULE | 80 | 22.2% |
| LOAD_GLOBAL | 60 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 11.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 53,490,660 | 89.0% |
| LOAD_FAST | 6,587,940 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,039,300 | 50.0% |
| LOAD_FAST_LOAD_FAST | 23,451,360 | 39.0% |
| LOAD_CONST | 6,587,940 | 11.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,260 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 24,817,200 | 95.8% |
| LOAD_ATTR | 658,620 | 2.5% |
| LOAD_FAST | 439,080 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,914,900 | 100.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 240 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,854,100 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,854,120 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 760,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 760,080 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 210,931,680 | 95.8% |
| FOR_ITER | 7,262,160 | 3.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,634,520 | 0.7% |
| FOR_ITER_TUPLE | 278,880 | 0.1% |
| LOAD_FAST | 69,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 210,931,680 | 95.8% |
| STORE_FAST_STORE_FAST | 9,245,280 | 4.2% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    311331300 | 79.4% |
|          hit |     80670300 | 20.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 76,200 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 71,780 | 94.2% |
| buffer int | 4,420 | 5.8% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     68552340 | 99.6% |
|          hit |       289260 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 16,800 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 16,800 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3265800 | 10.5% |
|          hit |     27769260 | 89.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.4% |
| Failure | 800 | 97.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 800 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     99950700 | 23.3% |
|          hit |    328080360 | 76.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 0.4% |
| Failure | 24,540 | 99.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 18,440 | 75.1% |
| add other | 5,280 | 21.5% |
| true divide other | 300 | 1.2% |
| true divide different types | 180 | 0.7% |
| multiply other | 160 | 0.7% |
| multiply different types | 120 | 0.5% |
| subtract different types | 60 | 0.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     60780060 | 17.0% |
| specialization.deopt |        36520 | 0.0% |
|          hit |    295600980 | 82.5% |
|         miss |      1936900 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 36,700 | 70.5% |
| Failure | 15,320 | 29.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 13,620 | 88.9% |
| class no vectorcall | 1,040 | 6.8% |
| class mutable | 580 | 3.8% |
| cfunc noargs | 60 | 0.4% |
| meth descr varargs | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1205640 | 1.2% |
|          hit |     99141480 | 98.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 11.8% |
| Failure | 300 | 88.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 300 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8461380 | 2.3% |
| specialization.deopt |         6720 | 0.0% |
|          hit |    357819660 | 97.6% |
|         miss |       356160 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,720 | 76.4% |
| Failure | 2,080 | 23.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 1,900 | 91.3% |
| zip | 180 | 8.7% |


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
| specialization.deferred |     49353920 | 16.6% |
| specialization.deopt |         1120 | 0.0% |
|          hit |    247475460 | 83.4% |
|         miss |        59360 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,420 | 8.7% |
| Failure | 14,960 | 91.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 7,720 | 51.6% |
| metaclass attribute | 5,620 | 37.6% |
| method | 820 | 5.5% |
| class method obj | 800 | 5.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |    258844180 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     30039300 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>

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
|          hit |     60078960 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    220937040 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 4,558,875,940 | 56.4% |
| Not specialized | 1,103,870,640 | 13.7% |
| Specialized | 2,415,917,980 | 29.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,600 | 100.0% |
| BINARY_SUBSCR | 311,331,300 | 0.0% |
| BINARY_OP | 99,950,700 | 0.0% |
| STORE_SUBSCR | 68,552,340 | 0.0% |
| CALL | 60,780,060 | 0.0% |
| LOAD_ATTR | 49,353,920 | 0.0% |
| FOR_ITER | 8,461,380 | 0.0% |
| TO_BOOL | 3,265,800 | 0.0% |
| COMPARE_OP | 1,205,640 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,265,640 | 53.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 671,260 | 28.5% |
| FOR_ITER_TUPLE | 178,080 | 7.6% |
| FOR_ITER_LIST | 178,080 | 7.6% |
| LOAD_ATTR_METHOD_NO_DICT | 38,160 | 1.6% |
| LOAD_ATTR_PROPERTY | 21,200 | 0.9% |
| RESUME_CHECK | 720 | 0.0% |
| RESUME | 720 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 326,917,780 | 67.7% |
| Calls to Python functions inlined | 155,887,220 | 32.3% |
| Calls via PyEval_EvalFrame (total) | 326,917,780 | 67.7% |
| Calls via PyEval_EvalFrame (vector) | 36,421,480 | 7.5% |
| Calls via PyEval_EvalFrame (generator) | 290,496,300 | 60.2% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 36,421,480 | 7.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 25,583,760 | 5.3% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,667,020 | 0.3% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 192,308,760 | 39.8% |
| Frame objects created | 289,260 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 406,754,980 | 52.6% |
| Frees to freelist | 406,887,840 |  |
| Allocations | 366,167,920 | 47.4% |
| Allocations to 512 bytes | 365,712,580 | 47.3% |
| Allocations to 4 kbytes | 453,900 | 0.1% |
| Allocations over 4 kbytes | 1,440 | 0.0% |
| Frees | 366,607,040 |  |
| New values | 0 |  |
| Interpreter increfs | 3,785,750,120 | 70.7% |
| Interpreter decrefs | 4,442,438,380 | 72.6% |
| Increfs | 1,566,880,563 | 29.3% |
| Decrefs | 1,677,337,203 | 27.4% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 76,755,567 |  |
| Method cache misses | 7,493 |  |
| Method cache collisions | 14,984 |  |
| Method cache dunder hits | 53,460,629 |  |
| Method cache dunder misses | 7,491 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 6,220 | 0 | 34,039,280 |
| 1 | 560 | 0 | 31,566,040 |
| 2 | 40 | 0 | 8,884,000 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
