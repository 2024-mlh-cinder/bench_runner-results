
# Pystats results

- benchmark: mdp
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 779,106,120 | 14.4% | 14.4% |  |
| RESUME_CHECK | 419,841,060 | 7.8% | 22.2% | 0.0% |
| INTERPRETER_EXIT | 326,917,780 | 6.0% | 28.2% |  |
| POP_TOP | 291,433,320 | 5.4% | 33.6% |  |
| ENTER_EXECUTOR | 275,703,960 | 5.1% | 38.7% |  |
| YIELD_VALUE | 243,371,880 | 4.5% | 43.2% |  |
| LOAD_FAST_LOAD_FAST | 235,770,480 | 4.4% | 47.5% |  |
| STORE_FAST | 206,391,000 | 3.8% | 51.4% |  |
| LOAD_DEREF | 179,908,920 | 3.3% | 54.7% |  |
| RETURN_VALUE | 129,249,060 | 2.4% | 57.1% |  |
| LOAD_GLOBAL_MODULE | 129,049,900 | 2.4% | 59.5% |  |
| LOAD_CONST | 124,495,380 | 2.3% | 61.8% |  |
| LOAD_GLOBAL_BUILTIN | 114,024,480 | 2.1% | 63.9% |  |
| COPY_FREE_VARS | 106,289,220 | 2.0% | 65.8% |  |
| BINARY_SUBSCR | 99,548,720 | 1.8% | 67.7% |  |
| LOAD_ATTR_SLOT | 97,512,480 | 1.8% | 69.5% |  |
| POP_JUMP_IF_FALSE | 95,035,380 | 1.8% | 71.2% |  |
| CALL_PY_EXACT_ARGS | 92,252,160 | 1.7% | 72.9% | 1.4% |
| PUSH_NULL | 75,078,240 | 1.4% | 74.3% |  |
| BINARY_OP_MULTIPLY_INT | 73,458,060 | 1.4% | 75.7% |  |
| BINARY_OP | 66,318,220 | 1.2% | 76.9% |  |
| CALL | 60,795,560 | 1.1% | 78.0% |  |
| STORE_ATTR_SLOT | 60,078,600 | 1.1% | 79.1% |  |
| COMPARE_OP_INT | 55,690,680 | 1.0% | 80.2% |  |
| STORE_FAST_STORE_FAST | 54,656,520 | 1.0% | 81.2% |  |
| STORE_SUBSCR | 51,880,040 | 1.0% | 82.1% |  |
| LOAD_ATTR | 48,811,340 | 0.9% | 83.0% |  |
| RETURN_CONST | 47,429,340 | 0.9% | 83.9% |  |
| FOR_ITER_LIST | 47,275,680 | 0.9% | 84.8% | 0.1% |
| RETURN_GENERATOR | 47,124,420 | 0.9% | 85.7% |  |
| CALL_BUILTIN_FAST | 44,122,020 | 0.8% | 86.5% |  |
| LOAD_ATTR_MODULE | 43,683,100 | 0.8% | 87.3% |  |
| BUILD_TUPLE | 39,869,400 | 0.7% | 88.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 38,758,860 | 0.7% | 88.7% |  |
| GET_ITER | 33,711,060 | 0.6% | 89.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 31,887,660 | 0.6% | 89.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 31,852,980 | 0.6% | 90.5% |  |
| MAKE_FUNCTION | 31,643,940 | 0.6% | 91.1% |  |
| BINARY_SUBSCR_DICT | 31,643,760 | 0.6% | 91.7% |  |
| NOP | 31,424,280 | 0.6% | 92.3% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 0.6% | 92.9% |  |
| BINARY_OP_MULTIPLY_FLOAT | 31,287,480 | 0.6% | 93.4% |  |
| SET_FUNCTION_ATTRIBUTE | 31,134,960 | 0.6% | 94.0% |  |
| LOAD_SUPER_ATTR_METHOD | 30,039,300 | 0.6% | 94.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,508,120 | 0.5% | 95.1% |  |
| BINARY_OP_ADD_INT | 26,414,340 | 0.5% | 95.6% |  |
| TO_BOOL_BOOL | 25,914,900 | 0.5% | 96.0% |  |
| POP_JUMP_IF_TRUE | 24,877,680 | 0.5% | 96.5% |  |
| CALL_ISINSTANCE | 24,817,200 | 0.5% | 97.0% |  |
| COMPARE_OP_FLOAT | 23,389,440 | 0.4% | 97.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 15,666,480 | 0.3% | 97.7% |  |
| SWAP | 12,905,760 | 0.2% | 97.9% |  |
| COPY | 10,464,180 | 0.2% | 98.1% |  |
| JUMP_FORWARD | 10,279,860 | 0.2% | 98.3% |  |
| FOR_ITER | 8,463,460 | 0.2% | 98.5% |  |
| IS_OP | 7,584,780 | 0.1% | 98.6% |  |
| CALL_TYPE_1 | 7,584,780 | 0.1% | 98.7% |  |
| JUMP_BACKWARD | 7,262,280 | 0.1% | 98.9% |  |
| POP_JUMP_IF_NOT_NONE | 7,086,360 | 0.1% | 99.0% |  |
| EXTENDED_ARG | 7,086,360 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,549,180 | 0.1% | 99.2% | 0.6% |
| CALL_BUILTIN_CLASS | 5,199,960 | 0.1% | 99.3% |  |
| UNARY_NEGATIVE | 4,332,000 | 0.1% | 99.4% |  |
| CALL_LEN | 3,704,880 | 0.1% | 99.5% |  |
| CALL_KW | 3,485,340 | 0.1% | 99.6% |  |
| TO_BOOL | 3,266,620 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 2,436,160 | 0.0% | 99.7% | 0.9% |
| MAP_ADD | 2,318,700 | 0.0% | 99.7% |  |
| TO_BOOL_LIST | 1,854,120 | 0.0% | 99.7% |  |
| STORE_FAST_LOAD_FAST | 1,714,500 | 0.0% | 99.8% |  |
| FOR_ITER_TUPLE | 1,635,600 | 0.0% | 99.8% | 4.1% |
| LOAD_FAST_AND_CLEAR | 1,241,460 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,211,800 | 0.0% | 99.8% | 55.4% |
| COMPARE_OP | 1,205,980 | 0.0% | 99.9% |  |
| BUILD_LIST | 878,640 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 760,080 | 0.0% | 99.9% |  |
| COMPARE_OP_STR | 637,860 | 0.0% | 99.9% |  |
| CALL_LIST_APPEND | 578,760 | 0.0% | 99.9% |  |
| BUILD_MAP | 540,600 | 0.0% | 99.9% |  |
| LIST_APPEND | 439,380 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 439,200 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 368,760 | 0.0% | 100.0% |  |
| CONTAINS_OP | 289,500 | 0.0% | 100.0% |  |
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
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 60 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| CACHE RESUME_CHECK | 249,754,060 | 4.6% | 4.6% |
| POP_TOP ENTER_EXECUTOR | 243,730,080 | 4.5% | 9.1% |
| YIELD_VALUE INTERPRETER_EXIT | 243,371,880 | 4.5% | 13.6% |
| RESUME_CHECK POP_TOP | 243,371,880 | 4.5% | 18.1% |
| ENTER_EXECUTOR YIELD_VALUE | 195,261,480 | 3.6% | 21.7% |
| LOAD_DEREF LOAD_FAST | 143,892,600 | 2.7% | 24.4% |
| LOAD_FAST LOAD_ATTR_SLOT | 97,512,480 | 1.8% | 26.2% |
| LOAD_FAST BINARY_SUBSCR | 94,581,000 | 1.7% | 27.9% |
| RESUME_CHECK LOAD_FAST | 79,981,500 | 1.5% | 29.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 71,367,600 | 1.3% | 30.7% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 66,173,160 | 1.2% | 32.0% |
| LOAD_FAST LOAD_CONST | 65,159,940 | 1.2% | 33.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 60,734,160 | 1.1% | 34.3% |
| COPY_FREE_VARS RESUME_CHECK | 59,523,900 | 1.1% | 35.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 59,108,400 | 1.1% | 36.5% |
| STORE_FAST LOAD_FAST | 57,615,480 | 1.1% | 37.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 55,690,680 | 1.0% | 38.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 53,490,660 | 1.0% | 39.6% |
| LOAD_CONST COMPARE_OP_INT | 52,215,720 | 1.0% | 40.5% |
| RETURN_VALUE RETURN_VALUE | 50,774,340 | 0.9% | 41.5% |
| STORE_FAST LOAD_DEREF | 50,031,180 | 0.9% | 42.4% |
| LOAD_ATTR_SLOT LOAD_FAST | 48,756,240 | 0.9% | 43.3% |
| RETURN_CONST INTERPRETER_EXIT | 47,150,400 | 0.9% | 44.2% |
| POP_TOP RESUME_CHECK | 47,124,420 | 0.9% | 45.0% |
| CACHE POP_TOP | 47,124,420 | 0.9% | 45.9% |
| LOAD_FAST STORE_SUBSCR | 46,923,960 | 0.9% | 46.8% |
| ENTER_EXECUTOR RETURN_CONST | 46,904,760 | 0.9% | 47.6% |
| LOAD_FAST FOR_ITER_LIST | 46,780,320 | 0.9% | 48.5% |
| COPY_FREE_VARS RETURN_GENERATOR | 46,765,320 | 0.9% | 49.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 45,975,360 | 0.8% | 50.2% |
| LOAD_ATTR_SLOT STORE_FAST_STORE_FAST | 45,905,880 | 0.8% | 51.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 43,683,040 | 0.8% | 51.9% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 42,696,840 | 0.8% | 52.7% |
| LOAD_ATTR_MODULE PUSH_NULL | 40,613,200 | 0.8% | 53.4% |
| CALL_BUILTIN_FAST STORE_FAST | 40,613,040 | 0.8% | 54.2% |
| CALL STORE_FAST | 37,888,440 | 0.7% | 54.9% |
| LOAD_FAST RETURN_VALUE | 37,588,620 | 0.7% | 55.6% |
| BINARY_SUBSCR LOAD_FAST | 36,442,800 | 0.7% | 56.2% |
| RETURN_VALUE INTERPRETER_EXIT | 36,395,500 | 0.7% | 56.9% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 36,079,680 | 0.7% | 57.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 33,550,980 | 0.6% | 58.2% |
| LOAD_DEREF PUSH_NULL | 32,750,460 | 0.6% | 58.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 32,693,140 | 0.6% | 59.4% |
| LOAD_FAST BUILD_TUPLE | 32,660,520 | 0.6% | 60.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 31,852,920 | 0.6% | 60.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 31,852,920 | 0.6% | 61.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 31,715,820 | 0.6% | 61.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 31,713,780 | 0.6% | 62.4% |
| LOAD_FAST BINARY_OP | 31,692,220 | 0.6% | 62.9% |
| STORE_FAST STORE_FAST | 31,688,700 | 0.6% | 63.5% |
| LOAD_CONST MAKE_FUNCTION | 31,643,940 | 0.6% | 64.1% |
| LOAD_FAST BINARY_SUBSCR_DICT | 31,643,760 | 0.6% | 64.7% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 31,598,200 | 0.6% | 65.3% |
| RETURN_VALUE GET_ITER | 31,424,340 | 0.6% | 65.9% |
| GET_ITER CALL_PY_EXACT_ARGS | 31,424,340 | 0.6% | 66.4% |
| RESUME_CHECK NOP | 31,424,220 | 0.6% | 67.0% |
| NOP LOAD_FAST | 31,424,220 | 0.6% | 67.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 31,287,480 | 0.6% | 68.2% |
| RETURN_GENERATOR CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 0.6% | 68.8% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 31,287,480 | 0.6% | 69.3% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 31,287,480 | 0.6% | 69.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS LOAD_DEREF | 31,287,480 | 0.6% | 70.5% |
| BINARY_OP_MULTIPLY_FLOAT YIELD_VALUE | 31,287,480 | 0.6% | 71.1% |
| BUILD_TUPLE LOAD_CONST | 31,274,400 | 0.6% | 71.6% |
| SET_FUNCTION_ATTRIBUTE LOAD_FAST | 31,134,960 | 0.6% | 72.2% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 31,134,960 | 0.6% | 72.8% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 31,134,960 | 0.6% | 73.4% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 31,134,960 | 0.6% | 74.0% |
| LOAD_FAST CALL | 30,917,500 | 0.6% | 74.5% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 30,260,100 | 0.6% | 75.1% |
| STORE_ATTR_SLOT LOAD_FAST | 30,039,300 | 0.6% | 75.6% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 30,039,300 | 0.6% | 76.2% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 30,039,300 | 0.6% | 76.7% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 30,039,300 | 0.6% | 77.3% |
| CACHE COPY_FREE_VARS | 30,039,300 | 0.6% | 77.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 27,667,320 | 0.5% | 78.4% |
| BINARY_OP BINARY_OP_MULTIPLY_INT | 27,195,480 | 0.5% | 78.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 26,461,960 | 0.5% | 79.4% |
| CALL_BOUND_METHOD_EXACT_ARGS COPY_FREE_VARS | 26,218,740 | 0.5% | 79.8% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_MODULE | 26,159,400 | 0.5% | 80.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 25,914,900 | 0.5% | 80.8% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 24,817,200 | 0.5% | 81.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 24,715,740 | 0.5% | 81.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 24,392,080 | 0.5% | 82.2% |
| BINARY_SUBSCR LOAD_DEREF | 23,468,760 | 0.4% | 82.6% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 23,451,360 | 0.4% | 83.0% |
| STORE_SUBSCR LOAD_GLOBAL_BUILTIN | 23,382,660 | 0.4% | 83.5% |
| COMPARE_OP_FLOAT POP_JUMP_IF_TRUE | 23,382,660 | 0.4% | 83.9% |
| BINARY_SUBSCR COMPARE_OP_FLOAT | 23,382,660 | 0.4% | 84.3% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 23,303,340 | 0.4% | 84.8% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 23,172,480 | 0.4% | 85.2% |
| POP_JUMP_IF_FALSE LOAD_DEREF | 22,953,000 | 0.4% | 85.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 22,953,000 | 0.4% | 86.0% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 22,952,940 | 0.4% | 86.5% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 22,733,400 | 0.4% | 86.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 22,691,280 | 0.4% | 87.3% |
| BINARY_OP_MULTIPLY_INT CALL_BOUND_METHOD_EXACT_ARGS | 22,513,860 | 0.4% | 87.7% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 21,628,260 | 0.4% | 88.1% |
| BINARY_OP STORE_FAST | 19,333,260 | 0.4% | 88.5% |
| LOAD_FAST LOAD_ATTR | 18,523,820 | 0.3% | 88.8% |


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
| LOAD_FAST | 94,581,000 | 95.0% |
| COPY | 4,943,220 | 5.0% |
| BINARY_SUBSCR | 24,500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,442,800 | 36.6% |
| LOAD_DEREF | 23,468,760 | 23.6% |
| COMPARE_OP_FLOAT | 23,382,660 | 23.5% |
| YIELD_VALUE | 15,477,840 | 15.5% |
| LOAD_FAST_LOAD_FAST | 666,060 | 0.7% |


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
| RETURN_VALUE | 31,424,340 | 93.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 979,620 | 2.9% |
| LOAD_FAST | 439,260 | 1.3% |
| CALL_BUILTIN_CLASS | 439,080 | 1.3% |
| CALL | 219,600 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 31,424,340 | 93.2% |
| LOAD_FAST_AND_CLEAR | 840,300 | 2.5% |
| FOR_ITER | 798,060 | 2.4% |
| FOR_ITER_LIST | 439,140 | 1.3% |
| FOR_ITER_TUPLE | 209,160 | 0.6% |


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
| LOAD_CONST | 31,643,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 31,134,960 | 98.4% |
| LOAD_FAST | 289,380 | 0.9% |
| LOAD_CONST | 219,540 | 0.7% |
| CALL | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 31,424,220 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,424,220 | 100.0% |
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
| RESUME_CHECK | 243,371,880 | 83.5% |
| CACHE | 47,124,420 | 16.2% |
| CALL_METHOD_DESCRIPTOR_O | 368,760 | 0.1% |
| POP_JUMP_IF_FALSE | 289,260 | 0.1% |
| RETURN_CONST | 278,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 243,730,080 | 83.6% |
| RESUME_CHECK | 47,124,420 | 16.2% |
| JUMP_FORWARD | 289,380 | 0.1% |
| LOAD_FAST | 289,320 | 0.1% |
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
| RETURN_VALUE | 50,774,340 | 39.3% |
| LOAD_FAST | 37,588,620 | 29.1% |
| BINARY_SUBSCR_DICT | 31,134,960 | 24.1% |
| CALL_BUILTIN_FAST | 3,508,980 | 2.7% |
| LOAD_ATTR_SLOT | 2,850,360 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 50,774,340 | 39.3% |
| INTERPRETER_EXIT | 36,395,500 | 28.2% |
| GET_ITER | 31,424,340 | 24.3% |
| STORE_FAST | 7,880,700 | 6.1% |
| CALL | 2,411,340 | 1.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,923,960 | 90.4% |
| SWAP | 4,943,220 | 9.5% |
| STORE_SUBSCR | 12,740 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 23,382,660 | 45.1% |
| LOAD_DEREF | 15,723,060 | 30.3% |
| JUMP_FORWARD | 7,738,920 | 14.9% |
| JUMP_BACKWARD | 4,504,140 | 8.7% |
| ENTER_EXECUTOR | 439,080 | 0.8% |


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
| LOAD_FAST | 31,692,220 | 47.8% |
| LOAD_FAST_LOAD_FAST | 30,260,100 | 45.6% |
| LOAD_CONST | 1,320,720 | 2.0% |
| CALL | 1,205,640 | 1.8% |
| BINARY_OP | 682,460 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 27,195,480 | 41.0% |
| STORE_FAST | 19,333,260 | 29.2% |
| LOAD_FAST_LOAD_FAST | 11,138,940 | 16.8% |
| SWAP | 4,943,220 | 7.5% |
| RETURN_VALUE | 1,205,700 | 1.8% |


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
| LOAD_FAST | 32,660,520 | 81.9% |
| LOAD_FAST_LOAD_FAST | 3,196,320 | 8.0% |
| BINARY_SUBSCR_TUPLE_INT | 2,318,700 | 5.8% |
| LOAD_CONST | 1,275,540 | 3.2% |
| CALL | 278,880 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,274,400 | 78.4% |
| COPY | 3,126,360 | 7.8% |
| YIELD_VALUE | 1,345,080 | 3.4% |
| LOAD_FAST | 1,294,620 | 3.2% |
| RETURN_VALUE | 1,205,640 | 3.0% |


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
| LOAD_FAST_LOAD_FAST | 289,500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 289,380 | 100.0% |
| POP_JUMP_IF_FALSE | 120 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,943,220 | 47.2% |
| BUILD_TUPLE | 3,126,360 | 29.9% |
| LOAD_FAST_LOAD_FAST | 1,816,860 | 17.4% |
| SWAP | 498,420 | 4.8% |
| BINARY_OP | 79,320 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,943,220 | 47.2% |
| BINARY_SUBSCR | 4,943,220 | 47.2% |
| IS_OP | 498,420 | 4.8% |
| LOAD_DEREF | 79,320 | 0.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 31,134,960 | 29.3% |
| CACHE | 30,039,300 | 28.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,218,740 | 24.7% |
| ENTER_EXECUTOR | 15,630,360 | 14.7% |
| CALL_KW | 3,265,800 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 59,523,900 | 56.0% |
| RETURN_GENERATOR | 46,765,320 | 44.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 243,730,080 | 88.4% |
| POP_JUMP_IF_TRUE | 23,303,340 | 8.5% |
| ENTER_EXECUTOR | 6,151,320 | 2.2% |
| POP_JUMP_IF_FALSE | 1,641,060 | 0.6% |
| STORE_SUBSCR | 439,080 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 195,261,480 | 70.8% |
| RETURN_CONST | 46,904,760 | 17.0% |
| COPY_FREE_VARS | 15,630,360 | 5.7% |
| LOAD_FAST | 7,346,520 | 2.7% |
| ENTER_EXECUTOR | 6,151,320 | 2.2% |


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
| STORE_SUBSCR | 4,504,140 | 62.0% |
| MAP_ADD | 2,318,700 | 31.9% |
| ENTER_EXECUTOR | 439,080 | 6.0% |
| LIST_APPEND | 300 | 0.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 7,262,160 | 100.0% |
| FOR_ITER_RANGE | 60 | 0.0% |
| FOR_ITER_LIST | 60 | 0.0% |


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
| BINARY_OP | 439,080 | 99.9% |
| LOAD_FAST | 180 | 0.0% |
| JUMP_FORWARD | 60 | 0.0% |
| BUILD_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 439,080 | 99.9% |
| JUMP_BACKWARD | 300 | 0.1% |


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
| LOAD_GLOBAL_MODULE | 22,953,000 | 47.0% |
| LOAD_FAST | 18,523,820 | 37.9% |
| LOAD_ATTR | 4,437,320 | 9.1% |
| BINARY_SUBSCR_TUPLE_INT | 2,896,740 | 5.9% |
| LOAD_ATTR_PROPERTY | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 22,952,940 | 47.0% |
| LOAD_DEREF | 6,531,600 | 13.4% |
| LOAD_FAST | 4,802,580 | 9.8% |
| LOAD_ATTR | 4,437,320 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 3,265,800 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,159,940 | 52.3% |
| BUILD_TUPLE | 31,274,400 | 25.1% |
| BINARY_SUBSCR_TUPLE_INT | 6,730,020 | 5.4% |
| STORE_ATTR_SLOT | 6,587,940 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 3,924,420 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 52,215,720 | 41.9% |
| MAKE_FUNCTION | 31,643,940 | 25.4% |
| BINARY_SUBSCR_TUPLE_INT | 15,666,480 | 12.6% |
| LOAD_FAST | 11,597,160 | 9.3% |
| CALL_KW | 3,485,340 | 2.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 50,031,180 | 27.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,287,480 | 17.4% |
| BINARY_SUBSCR | 23,468,760 | 13.0% |
| POP_JUMP_IF_FALSE | 22,953,000 | 12.8% |
| STORE_SUBSCR | 15,723,060 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,892,600 | 80.0% |
| PUSH_NULL | 32,750,460 | 18.2% |
| COMPARE_OP_INT | 3,265,800 | 1.8% |
| LIST_EXTEND | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 143,892,600 | 18.5% |
| RESUME_CHECK | 79,981,500 | 10.3% |
| LOAD_GLOBAL_BUILTIN | 71,367,600 | 9.2% |
| STORE_FAST | 57,615,480 | 7.4% |
| LOAD_ATTR_SLOT | 48,756,240 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 97,512,480 | 12.5% |
| BINARY_SUBSCR | 94,581,000 | 12.1% |
| LOAD_CONST | 65,159,940 | 8.4% |
| STORE_SUBSCR | 46,923,960 | 6.0% |
| FOR_ITER_LIST | 46,780,320 | 6.0% |


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
| PUSH_NULL | 66,173,160 | 28.1% |
| STORE_FAST | 45,975,360 | 19.5% |
| POP_JUMP_IF_FALSE | 24,715,740 | 10.5% |
| STORE_ATTR_SLOT | 23,451,360 | 9.9% |
| BINARY_OP_MULTIPLY_INT | 23,172,480 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 53,490,660 | 22.7% |
| CALL_BUILTIN_FAST | 42,696,840 | 18.1% |
| BINARY_OP_MULTIPLY_INT | 36,079,680 | 15.3% |
| LOAD_FAST | 33,550,980 | 14.2% |
| BINARY_OP | 30,260,100 | 12.8% |


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
| COMPARE_OP_INT | 55,690,680 | 58.6% |
| TO_BOOL_BOOL | 25,914,900 | 27.3% |
| IS_OP | 7,584,780 | 8.0% |
| TO_BOOL | 3,265,800 | 3.4% |
| TO_BOOL_LIST | 1,854,120 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 24,715,740 | 26.0% |
| LOAD_GLOBAL_MODULE | 24,392,080 | 25.7% |
| LOAD_DEREF | 22,953,000 | 24.2% |
| LOAD_FAST | 11,228,760 | 11.8% |
| LOAD_GLOBAL_BUILTIN | 7,454,100 | 7.8% |


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
| ENTER_EXECUTOR | 23,303,340 | 93.7% |
| LOAD_FAST | 1,495,020 | 6.0% |
| LOAD_DEREF | 79,320 | 0.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 46,904,760 | 98.9% |
| FOR_ITER | 278,880 | 0.6% |
| FOR_ITER_TUPLE | 208,980 | 0.4% |
| RESUME_CHECK | 25,980 | 0.1% |
| FOR_ITER_LIST | 10,680 | 0.0% |

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
| MAKE_FUNCTION | 31,134,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,134,960 | 100.0% |


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
| CALL_BUILTIN_FAST | 40,613,040 | 19.7% |
| CALL | 37,888,440 | 18.4% |
| STORE_FAST | 31,688,700 | 15.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 31,287,480 | 15.2% |
| BINARY_OP | 19,333,260 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,615,480 | 27.9% |
| LOAD_DEREF | 50,031,180 | 24.2% |
| LOAD_FAST_LOAD_FAST | 45,975,360 | 22.3% |
| STORE_FAST | 31,688,700 | 15.4% |
| LOAD_GLOBAL_MODULE | 18,256,480 | 8.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,216,200 | 70.9% |
| FOR_ITER_RANGE | 439,080 | 25.6% |
| FOR_ITER_LIST | 59,220 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,275,420 | 74.4% |
| LOAD_FAST | 439,080 | 25.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 45,905,880 | 84.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,471,380 | 13.7% |
| UNPACK_SEQUENCE_TUPLE | 760,080 | 1.4% |
| BINARY_OP_MULTIPLY_INT | 439,080 | 0.8% |
| STORE_FAST_STORE_FAST | 80,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,667,320 | 50.6% |
| LOAD_GLOBAL_MODULE | 26,159,400 | 47.9% |
| STORE_FAST | 679,980 | 1.2% |
| STORE_FAST_STORE_FAST | 80,100 | 0.1% |
| LOAD_CONST | 69,720 | 0.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,943,220 | 38.3% |
| BINARY_OP | 4,943,220 | 38.3% |
| LOAD_FAST_AND_CLEAR | 840,300 | 6.5% |
| LOAD_GLOBAL_BUILTIN | 498,420 | 3.9% |
| BUILD_LIST | 439,200 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,943,220 | 38.3% |
| STORE_SUBSCR | 4,943,220 | 38.3% |
| STORE_FAST | 840,240 | 6.5% |
| COPY | 498,420 | 3.9% |
| BUILD_LIST | 439,200 | 3.4% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 195,261,480 | 80.2% |
| BINARY_OP_MULTIPLY_FLOAT | 31,287,480 | 12.9% |
| BINARY_SUBSCR | 15,477,840 | 6.4% |
| BUILD_TUPLE | 1,345,080 | 0.6% |

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
| BINARY_OP_MULTIPLY_INT | 21,628,260 | 81.9% |
| LOAD_FAST | 3,265,800 | 12.4% |
| LOAD_CONST | 878,220 | 3.3% |
| BINARY_OP | 642,060 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,137,680 | 64.9% |
| LOAD_FAST_LOAD_FAST | 5,571,720 | 21.1% |
| CALL | 3,265,800 | 12.4% |
| LOAD_FAST | 439,080 | 1.7% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,287,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 31,287,480 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,079,680 | 49.1% |
| BINARY_OP | 27,195,480 | 37.0% |
| LOAD_FAST | 6,673,920 | 9.1% |
| LOAD_ATTR | 2,825,880 | 3.8% |
| LOAD_CONST | 658,620 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,172,480 | 31.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 22,513,860 | 30.6% |
| BINARY_OP_ADD_INT | 21,628,260 | 29.4% |
| LOAD_FAST | 2,303,340 | 3.1% |
| CALL_BUILTIN_FAST | 1,425,180 | 1.9% |


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
| LOAD_FAST | 31,643,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 31,134,960 | 98.4% |
| PUSH_EXC_INFO | 289,260 | 0.9% |
| STORE_FAST | 219,540 | 0.7% |


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
| LOAD_CONST | 15,666,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,730,020 | 43.0% |
| LOAD_ATTR | 2,896,740 | 18.5% |
| BUILD_TUPLE | 2,318,700 | 14.8% |
| LOAD_FAST | 2,226,120 | 14.2% |
| UNARY_NEGATIVE | 1,205,640 | 7.7% |


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
| ENTER_EXECUTOR | 289,320 | 50.0% |
| BUILD_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 578,760 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 100.0% |


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
| RETURN_GENERATOR | 289,380 | 78.5% |
| LOAD_FAST | 79,380 | 21.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 368,760 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,693,140 | 35.4% |
| GET_ITER | 31,424,340 | 34.1% |
| LOAD_FAST_LOAD_FAST | 22,691,280 | 24.6% |
| UNARY_NEGATIVE | 3,126,360 | 3.4% |
| LOAD_ATTR_MODULE | 1,425,180 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60,734,160 | 65.8% |
| COPY_FREE_VARS | 31,134,960 | 33.7% |
| RETURN_GENERATOR | 359,100 | 0.4% |
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
| LOAD_CONST | 52,215,720 | 93.8% |
| LOAD_DEREF | 3,265,800 | 5.9% |
| LOAD_FAST_LOAD_FAST | 209,160 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 55,690,680 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 637,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 358,980 | 56.3% |
| BINARY_OP | 278,880 | 43.7% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,780,320 | 99.0% |
| GET_ITER | 439,140 | 0.9% |
| ENTER_EXECUTOR | 54,840 | 0.1% |
| FOR_ITER_TUPLE | 1,260 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 31,287,480 | 66.2% |
| STORE_FAST | 15,917,040 | 33.7% |
| STORE_FAST_LOAD_FAST | 59,220 | 0.1% |
| RETURN_CONST | 10,680 | 0.0% |
| FOR_ITER_TUPLE | 1,260 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 439,080 | 100.0% |
| JUMP_BACKWARD | 60 | 0.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 439,080 | 100.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,150,800 | 70.4% |
| LOAD_FAST | 274,380 | 16.8% |
| GET_ITER | 209,160 | 12.8% |
| FOR_ITER_LIST | 1,260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 1,216,200 | 74.4% |
| RETURN_CONST | 208,980 | 12.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 139,440 | 8.5% |
| STORE_FAST | 69,720 | 4.3% |
| FOR_ITER_LIST | 1,260 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,598,200 | 99.1% |
| LOAD_FAST_LOAD_FAST | 289,260 | 0.9% |
| LOAD_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,713,780 | 99.5% |
| STORE_FAST | 173,580 | 0.5% |
| STORE_SUBSCR | 120 | 0.0% |
| SWAP | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,969,880 | 91.2% |
| RETURN_VALUE | 358,980 | 5.5% |
| LOAD_FAST_CHECK | 219,540 | 3.4% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,059,860 | 77.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,199,160 | 18.3% |
| LOAD_CONST | 289,380 | 4.4% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,852,920 | 100.0% |
| RETURN_VALUE | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,852,920 | 100.0% |
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
| RESUME_CHECK | 59,108,400 | 51.8% |
| STORE_SUBSCR | 23,382,660 | 20.5% |
| POP_JUMP_IF_FALSE | 7,454,100 | 6.5% |
| POP_JUMP_IF_NOT_NONE | 7,086,360 | 6.2% |
| CALL_TYPE_1 | 7,086,360 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,367,600 | 62.6% |
| LOAD_GLOBAL_MODULE | 30,039,300 | 26.3% |
| IS_OP | 6,587,940 | 5.8% |
| LOAD_CONST | 3,924,420 | 3.4% |
| SWAP | 498,420 | 0.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,039,300 | 23.3% |
| LOAD_FAST | 26,461,960 | 20.5% |
| STORE_FAST_STORE_FAST | 26,159,400 | 20.3% |
| POP_JUMP_IF_FALSE | 24,392,080 | 18.9% |
| STORE_FAST | 18,256,480 | 14.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 43,683,040 | 33.8% |
| LOAD_FAST | 31,715,820 | 24.6% |
| LOAD_ATTR | 22,953,000 | 17.8% |
| CALL_ISINSTANCE | 22,733,400 | 17.6% |
| LOAD_FAST_LOAD_FAST | 6,008,760 | 4.7% |


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
| CACHE | 249,754,060 | 59.5% |
| CALL_PY_EXACT_ARGS | 60,734,160 | 14.5% |
| COPY_FREE_VARS | 59,523,900 | 14.2% |
| POP_TOP | 47,124,420 | 11.2% |
| LOAD_ATTR_PROPERTY | 2,414,960 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 243,371,880 | 58.0% |
| LOAD_FAST | 79,981,500 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 59,108,400 | 14.1% |
| NOP | 31,424,220 | 7.5% |
| LOAD_DEREF | 3,265,860 | 0.8% |


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
| FOR_ITER_LIST | 31,287,480 | 80.7% |
| FOR_ITER | 7,262,160 | 18.7% |
| FOR_ITER_TUPLE | 139,440 | 0.4% |
| LOAD_FAST | 69,720 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,287,480 | 80.7% |
| STORE_FAST_STORE_FAST | 7,471,380 | 19.3% |


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
| specialization.deferred |     99524220 | 67.7% |
|          hit |     47529780 | 32.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 24,500 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 24,140 | 98.5% |
| buffer int | 360 | 1.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     51867300 | 99.4% |
|          hit |       289260 | 0.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 12,740 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 12,740 | 100.0% |


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
| specialization.deferred |     66301740 | 33.5% |
|          hit |    131465640 | 66.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 0.6% |
| Failure | 16,380 | 99.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 14,380 | 87.8% |
| add other | 1,220 | 7.4% |
| true divide other | 300 | 1.8% |
| true divide different types | 180 | 1.1% |
| multiply other | 160 | 1.0% |
| multiply different types | 80 | 0.5% |
| subtract different types | 60 | 0.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     60780060 | 18.7% |
| specialization.deopt |        36520 | 0.0% |
|          hit |    262207320 | 80.7% |
|         miss |      1936900 | 0.6% |

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
| specialization.deferred |      1205640 | 1.5% |
|          hit |     79717980 | 98.5% |

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
| specialization.deferred |      8461380 | 14.6% |
| specialization.deopt |         2520 | 0.0% |
|          hit |     49216920 | 85.1% |
|         miss |       133560 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,520 | 54.8% |
| Failure | 2,080 | 45.2% |

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
| specialization.deferred |     48796160 | 18.6% |
| specialization.deopt |         1120 | 0.0% |
|          hit |    213862200 | 81.4% |
|         miss |        59360 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,420 | 8.7% |
| Failure | 14,880 | 91.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 7,640 | 51.3% |
| metaclass attribute | 5,620 | 37.8% |
| method | 820 | 5.5% |
| class method obj | 800 | 5.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |    243074380 | 100.0% |

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
|          hit |     39518940 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 3,355,577,860 | 62.0% |
| Not specialized | 476,682,860 | 8.8% |
| Specialized | 1,578,102,160 | 29.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,600 | 100.0% |
| BINARY_SUBSCR | 99,524,220 | 0.0% |
| BINARY_OP | 66,301,740 | 0.0% |
| CALL | 60,780,060 | 0.0% |
| STORE_SUBSCR | 51,867,300 | 0.0% |
| LOAD_ATTR | 48,796,160 | 0.0% |
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
| CALL_PY_EXACT_ARGS | 1,265,640 | 59.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 671,260 | 31.5% |
| FOR_ITER_TUPLE | 66,780 | 3.1% |
| FOR_ITER_LIST | 66,780 | 3.1% |
| LOAD_ATTR_METHOD_NO_DICT | 38,160 | 1.8% |
| LOAD_ATTR_PROPERTY | 21,200 | 1.0% |
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
| Calls to PyEval_EvalDefault | 326,917,780 | 72.4% |
| Calls to Python functions inlined | 124,417,340 | 27.6% |
| Calls via PyEval_EvalFrame (total) | 326,917,780 | 72.4% |
| Calls via PyEval_EvalFrame (vector) | 36,421,480 | 8.1% |
| Calls via PyEval_EvalFrame (generator) | 290,496,300 | 64.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 36,421,480 | 8.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 25,583,760 | 5.7% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,667,020 | 0.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 192,308,760 | 42.6% |
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
| Interpreter increfs | 2,573,469,740 | 45.7% |
| Interpreter decrefs | 2,738,963,260 | 42.8% |
| Increfs | 3,054,981,764 | 54.3% |
| Decrefs | 3,656,633,144 | 57.2% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 76,697,116 |  |
| Method cache misses | 65,864 |  |
| Method cache collisions | 131,846 |  |
| Method cache dunder hits | 53,350,438 |  |
| Method cache dunder misses | 65,982 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 6,220 | 0 | 34,039,280 |
| 1 | 560 | 0 | 31,566,040 |
| 2 | 40 | 0 | 8,859,520 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 427,160 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 275,703,960 |  |
| Uops executed | 6,157,880,280 | 22 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,205,640 | 0.4% |
| <= 4 | 0 | 0.0% |
| <= 8 | 47,050,860 | 17.1% |
| <= 16 | 27,022,320 | 9.8% |
| <= 32 | 182,920,260 | 66.3% |
| <= 64 | 632,520 | 0.2% |
| <= 128 | 15,994,200 | 5.8% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1024 | 878,160 | 0.3% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 1,752,094,260 | 28.5% | 28.5% |
| LOAD_FAST | 627,456,240 | 10.2% | 38.6% |
| STORE_FAST | 444,230,160 | 7.2% | 45.9% |
| _POP_JUMP_IF_TRUE | 349,498,140 | 5.7% | 51.5% |
| _ITER_CHECK_LIST | 292,484,340 | 4.7% | 56.3% |
| _IS_ITER_EXHAUSTED_LIST | 291,278,700 | 4.7% | 61.0% |
| _EXIT_TRACE | 274,498,320 | 4.5% | 65.5% |
| _ITER_NEXT_LIST | 243,997,920 | 4.0% | 69.4% |
| BINARY_SUBSCR | 211,807,080 | 3.4% | 72.9% |
| LOAD_DEREF | 195,122,040 | 3.2% | 76.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 181,418,100 | 2.9% | 79.0% |
| _GUARD_BOTH_FLOAT | 179,644,200 | 2.9% | 81.9% |
| _BINARY_OP_MULTIPLY_FLOAT | 179,644,200 | 2.9% | 84.8% |
| LOAD_CONST | 70,033,020 | 1.1% | 86.0% |
| POP_TOP | 48,218,340 | 0.8% | 86.7% |
| _SAVE_CURRENT_IP | 47,100,240 | 0.8% | 87.5% |
| _JUMP_TO_TOP | 35,957,280 | 0.6% | 88.1% |
| BINARY_OP | 33,648,960 | 0.5% | 88.6% |
| _GUARD_TYPE_VERSION | 33,613,260 | 0.5% | 89.2% |
| CONTAINS_OP | 33,466,200 | 0.5% | 89.7% |
| SWAP | 33,370,080 | 0.5% | 90.3% |
| COPY | 33,370,080 | 0.5% | 90.8% |
| _PUSH_FRAME | 31,469,880 | 0.5% | 91.3% |
| _INIT_CALL_PY_EXACT_ARGS | 31,469,880 | 0.5% | 91.8% |
| _CHECK_STACK_SPACE | 31,469,880 | 0.5% | 92.3% |
| _CHECK_PEP_523 | 31,469,880 | 0.5% | 92.9% |
| _CHECK_FUNCTION_EXACT_ARGS | 31,469,880 | 0.5% | 93.4% |
| COMPARE_OP_INT | 19,144,620 | 0.3% | 93.7% |
| BINARY_SUBSCR_TUPLE_INT | 17,510,160 | 0.3% | 94.0% |
| _ITER_CHECK_RANGE | 17,124,120 | 0.3% | 94.2% |
| _IS_ITER_EXHAUSTED_RANGE | 17,124,120 | 0.3% | 94.5% |
| _GUARD_BOTH_INT | 16,970,520 | 0.3% | 94.8% |
| _ITER_NEXT_RANGE | 16,685,040 | 0.3% | 95.1% |
| _BINARY_OP_MULTIPLY_INT | 16,685,040 | 0.3% | 95.3% |
| STORE_SUBSCR | 16,685,040 | 0.3% | 95.6% |
| LIST_APPEND | 16,685,040 | 0.3% | 95.9% |
| BUILD_TUPLE | 16,059,120 | 0.3% | 96.1% |
| RESUME_CHECK | 15,839,520 | 0.3% | 96.4% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 15,769,800 | 0.3% | 96.6% |
| _GUARD_KEYS_VERSION | 15,769,800 | 0.3% | 96.9% |
| _GUARD_GLOBALS_VERSION | 15,769,800 | 0.3% | 97.2% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 15,769,800 | 0.3% | 97.4% |
| GET_ITER | 15,636,960 | 0.3% | 97.7% |
| _POP_FRAME | 15,630,360 | 0.3% | 97.9% |
| _LOAD_GLOBAL_BUILTINS | 15,630,360 | 0.3% | 98.2% |
| _LOAD_ATTR_INSTANCE_VALUE | 15,630,360 | 0.3% | 98.4% |
| _GUARD_BUILTINS_VERSION | 15,630,360 | 0.3% | 98.7% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 15,630,360 | 0.3% | 98.9% |
| SET_FUNCTION_ATTRIBUTE | 15,630,360 | 0.3% | 99.2% |
| MAKE_FUNCTION | 15,630,360 | 0.3% | 99.4% |
| BINARY_SUBSCR_DICT | 15,630,360 | 0.3% | 99.7% |
| _POP_JUMP_IF_FALSE | 11,864,100 | 0.2% | 99.9% |
| _LOAD_ATTR_METHOD_NO_DICT | 2,213,100 | 0.0% | 99.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,634,460 | 0.0% | 100.0% |
| LOAD_ATTR | 557,760 | 0.0% | 100.0% |
| _ITER_CHECK_TUPLE | 418,320 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 418,320 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_O | 289,320 | 0.0% | 100.0% |
| _BINARY_OP_ADD_INT | 285,480 | 0.0% | 100.0% |
| COMPARE_OP_STR | 278,880 | 0.0% | 100.0% |
| _ITER_NEXT_TUPLE | 209,160 | 0.0% | 100.0% |
| _LOAD_GLOBAL_MODULE | 139,440 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER | 427,160 |


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
Stats gathered on: 2023-10-04
