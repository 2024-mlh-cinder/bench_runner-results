
# Pystats results

- benchmark: tomli_loads
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,416,831,660 | 15.0% | 15.0% |  |
| LOAD_FAST_LOAD_FAST | 943,812,000 | 10.0% | 24.9% |  |
| STORE_FAST | 865,719,960 | 9.1% | 34.1% |  |
| LOAD_CONST | 670,608,180 | 7.1% | 41.2% |  |
| POP_JUMP_IF_FALSE | 665,048,640 | 7.0% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 436,441,480 | 4.6% | 52.8% |  |
| CONTAINS_OP | 350,981,040 | 3.7% | 56.5% |  |
| RESUME_CHECK | 309,829,740 | 3.3% | 59.8% | 0.0% |
| BINARY_SUBSCR_STR_INT | 309,387,560 | 3.3% | 63.0% | 0.0% |
| NOP | 306,239,220 | 3.2% | 66.3% |  |
| RETURN_VALUE | 305,566,860 | 3.2% | 69.5% |  |
| CALL_PY_EXACT_ARGS | 271,114,320 | 2.9% | 72.4% |  |
| LOAD_GLOBAL_BUILTIN | 257,044,560 | 2.7% | 75.1% |  |
| TO_BOOL_BOOL | 211,818,300 | 2.2% | 77.3% |  |
| COMPARE_OP_STR | 170,416,980 | 1.8% | 79.1% |  |
| BINARY_OP_ADD_INT | 158,264,040 | 1.7% | 80.8% |  |
| BINARY_SUBSCR_DICT | 145,569,240 | 1.5% | 82.3% |  |
| BUILD_TUPLE | 143,691,420 | 1.5% | 83.9% |  |
| ENTER_EXECUTOR | 141,461,340 | 1.5% | 85.3% |  |
| CALL_ISINSTANCE | 97,501,680 | 1.0% | 86.4% |  |
| STORE_FAST_STORE_FAST | 85,805,340 | 0.9% | 87.3% |  |
| GET_ITER | 83,084,160 | 0.9% | 88.2% |  |
| BINARY_SLICE | 82,761,780 | 0.9% | 89.0% |  |
| LOAD_DEREF | 76,479,480 | 0.8% | 89.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 65,176,020 | 0.7% | 90.5% |  |
| BINARY_SUBSCR | 64,361,040 | 0.7% | 91.2% |  |
| POP_JUMP_IF_TRUE | 58,421,040 | 0.6% | 91.8% |  |
| CALL | 50,689,980 | 0.5% | 92.4% |  |
| LOAD_ATTR | 50,151,200 | 0.5% | 92.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 46,488,840 | 0.5% | 93.4% |  |
| POP_TOP | 46,077,540 | 0.5% | 93.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,335,160 | 0.5% | 94.4% |  |
| FOR_ITER_TUPLE | 43,738,980 | 0.5% | 94.8% |  |
| MAKE_CELL | 37,970,340 | 0.4% | 95.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 27,083,340 | 0.3% | 95.5% |  |
| RETURN_CONST | 24,844,800 | 0.3% | 95.8% |  |
| LOAD_ATTR_CLASS | 23,157,660 | 0.2% | 96.0% |  |
| CALL_BUILTIN_CLASS | 22,393,620 | 0.2% | 96.2% |  |
| STORE_SUBSCR_DICT | 21,993,540 | 0.2% | 96.5% |  |
| BINARY_OP | 21,774,720 | 0.2% | 96.7% |  |
| TO_BOOL | 21,518,740 | 0.2% | 96.9% |  |
| JUMP_FORWARD | 20,851,380 | 0.2% | 97.2% |  |
| COPY | 19,117,920 | 0.2% | 97.4% |  |
| CALL_LEN | 18,985,860 | 0.2% | 97.6% |  |
| FOR_ITER_RANGE | 18,985,260 | 0.2% | 97.8% |  |
| COPY_FREE_VARS | 18,985,200 | 0.2% | 98.0% |  |
| UNPACK_SEQUENCE_TUPLE | 18,985,140 | 0.2% | 98.2% |  |
| STORE_DEREF | 18,985,140 | 0.2% | 98.4% |  |
| SET_FUNCTION_ATTRIBUTE | 18,985,140 | 0.2% | 98.6% |  |
| RETURN_GENERATOR | 18,985,140 | 0.2% | 98.8% |  |
| MAKE_FUNCTION | 18,985,140 | 0.2% | 99.0% |  |
| FOR_ITER_GEN | 18,985,140 | 0.2% | 99.2% |  |
| END_FOR | 18,985,140 | 0.2% | 99.4% |  |
| CALL_KW | 16,774,200 | 0.2% | 99.5% |  |
| BINARY_OP_ADD_UNICODE | 15,129,960 | 0.2% | 99.7% |  |
| PUSH_NULL | 6,605,640 | 0.1% | 99.8% |  |
| TO_BOOL_NONE | 3,349,680 | 0.0% | 99.8% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 3,161,160 | 0.0% | 99.8% |  |
| BUILD_MAP | 3,139,140 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,896,240 | 0.0% | 99.9% |  |
| BUILD_CONST_KEY_MAP | 1,704,180 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 1,674,840 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 1,674,840 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,644,900 | 0.0% | 100.0% |  |
| FOR_ITER | 1,375,180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,374,840 | 0.0% | 100.0% |  |
| BUILD_LIST | 360,120 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 273,300 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 131,220 | 0.0% | 100.0% |  |
| SWAP | 780 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 720 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 420 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 400 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 360 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 300 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 200 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 180 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 120 | 0.0% | 100.0% |  |
| POP_EXCEPT | 120 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| IS_OP | 60 | 0.0% | 100.0% |  |
| CALL_STR_1 | 60 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_CONST | 414,578,940 | 4.4% | 4.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 344,687,160 | 3.6% | 8.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 312,749,520 | 3.3% | 11.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_STR_INT | 308,008,980 | 3.3% | 14.6% |
| STORE_FAST LOAD_FAST | 286,317,000 | 3.0% | 17.6% |
| NOP LOAD_FAST_LOAD_FAST | 248,538,120 | 2.6% | 20.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 243,927,360 | 2.6% | 22.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 233,143,980 | 2.5% | 25.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 205,539,120 | 2.2% | 27.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 174,911,460 | 1.8% | 29.3% |
| LOAD_CONST COMPARE_OP_STR | 170,416,980 | 1.8% | 31.1% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 170,416,980 | 1.8% | 32.9% |
| LOAD_FAST RETURN_VALUE | 170,083,800 | 1.8% | 34.7% |
| RETURN_VALUE STORE_FAST | 168,930,360 | 1.8% | 36.5% |
| BINARY_SUBSCR_STR_INT STORE_FAST | 159,286,500 | 1.7% | 38.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 158,262,600 | 1.7% | 39.8% |
| RESUME_CHECK NOP | 152,017,440 | 1.6% | 41.4% |
| LOAD_FAST CONTAINS_OP | 150,100,920 | 1.6% | 43.0% |
| BINARY_SUBSCR_STR_INT LOAD_FAST | 150,100,860 | 1.6% | 44.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 141,557,000 | 1.5% | 46.1% |
| BINARY_OP_ADD_INT STORE_FAST | 136,621,560 | 1.4% | 47.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 113,713,980 | 1.2% | 48.7% |
| ENTER_EXECUTOR LOAD_FAST | 99,655,440 | 1.1% | 49.8% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 99,520,980 | 1.1% | 50.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 99,178,800 | 1.0% | 51.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 98,151,720 | 1.0% | 52.9% |
| RESUME_CHECK LOAD_FAST | 97,899,360 | 1.0% | 54.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 97,502,400 | 1.0% | 55.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 97,501,680 | 1.0% | 56.0% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 89,255,160 | 0.9% | 57.0% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 89,255,160 | 0.9% | 57.9% |
| BUILD_TUPLE RETURN_VALUE | 82,846,260 | 0.9% | 58.8% |
| BINARY_SUBSCR_DICT STORE_FAST | 82,351,020 | 0.9% | 59.7% |
| LOAD_CONST BINARY_SUBSCR_DICT | 81,197,520 | 0.9% | 60.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 80,941,320 | 0.9% | 61.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 79,747,720 | 0.8% | 62.2% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 78,516,540 | 0.8% | 63.0% |
| STORE_FAST NOP | 76,431,360 | 0.8% | 63.8% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 74,629,980 | 0.8% | 64.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 67,702,980 | 0.7% | 65.3% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 65,176,020 | 0.7% | 66.0% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 65,175,960 | 0.7% | 66.7% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_DICT | 64,102,380 | 0.7% | 67.4% |
| LOAD_CONST BINARY_SUBSCR | 62,765,460 | 0.7% | 68.1% |
| STORE_FAST ENTER_EXECUTOR | 61,713,600 | 0.7% | 68.7% |
| LOAD_FAST BUILD_TUPLE | 59,974,500 | 0.6% | 69.3% |
| LOAD_CONST LOAD_CONST | 59,359,800 | 0.6% | 70.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 59,043,640 | 0.6% | 70.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 58,330,440 | 0.6% | 71.2% |
| BINARY_SUBSCR_DICT CONTAINS_OP | 58,124,340 | 0.6% | 71.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 57,580,320 | 0.6% | 72.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 55,914,520 | 0.6% | 73.0% |
| LOAD_FAST TO_BOOL_BOOL | 54,998,160 | 0.6% | 73.6% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 46,488,720 | 0.5% | 74.1% |
| LOAD_FAST LOAD_ATTR | 45,114,060 | 0.5% | 74.6% |
| LOAD_ATTR LOAD_ATTR_METHOD_WITH_VALUES | 45,113,820 | 0.5% | 75.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 45,031,180 | 0.5% | 75.5% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 43,738,980 | 0.5% | 76.0% |
| GET_ITER FOR_ITER_TUPLE | 43,738,980 | 0.5% | 76.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 43,690,980 | 0.5% | 76.9% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 43,234,800 | 0.5% | 77.4% |
| LOAD_CONST BINARY_SLICE | 42,585,540 | 0.4% | 77.8% |
| FOR_ITER_TUPLE STORE_FAST | 41,938,320 | 0.4% | 78.3% |
| BINARY_SUBSCR STORE_FAST | 41,914,800 | 0.4% | 78.7% |
| LOAD_FAST GET_ITER | 40,989,360 | 0.4% | 79.1% |
| LOAD_FAST STORE_FAST | 39,856,020 | 0.4% | 79.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 39,303,120 | 0.4% | 80.0% |
| LOAD_FAST CALL | 38,825,140 | 0.4% | 80.4% |
| LOAD_FAST_LOAD_FAST BINARY_SLICE | 38,594,340 | 0.4% | 80.8% |
| LOAD_DEREF LOAD_CONST | 37,970,280 | 0.4% | 81.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 36,906,840 | 0.4% | 81.6% |
| NOP NOP | 35,489,940 | 0.4% | 82.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 35,418,960 | 0.4% | 82.3% |
| RETURN_VALUE RETURN_VALUE | 30,530,040 | 0.3% | 82.7% |
| LOAD_GLOBAL_MODULE STORE_FAST | 30,259,920 | 0.3% | 83.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 24,063,500 | 0.3% | 83.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 23,379,600 | 0.2% | 83.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_CLASS | 23,157,660 | 0.2% | 83.7% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 23,080,620 | 0.2% | 84.0% |
| BINARY_SLICE BUILD_TUPLE | 22,874,820 | 0.2% | 84.2% |
| NOP LOAD_FAST | 22,210,440 | 0.2% | 84.4% |
| CALL RESUME_CHECK | 21,940,620 | 0.2% | 84.7% |
| POP_JUMP_IF_FALSE NOP | 21,940,440 | 0.2% | 84.9% |
| BINARY_SLICE GET_ITER | 21,734,820 | 0.2% | 85.1% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 21,559,980 | 0.2% | 85.4% |
| TO_BOOL POP_JUMP_IF_TRUE | 21,513,480 | 0.2% | 85.6% |
| LOAD_FAST TO_BOOL | 21,513,480 | 0.2% | 85.8% |
| LOAD_ATTR_CLASS CALL_PY_EXACT_ARGS | 21,513,480 | 0.2% | 86.0% |
| BINARY_OP STORE_FAST | 21,500,040 | 0.2% | 86.3% |
| BINARY_SUBSCR STORE_FAST_STORE_FAST | 20,629,320 | 0.2% | 86.5% |
| JUMP_FORWARD LOAD_GLOBAL_MODULE | 20,581,320 | 0.2% | 86.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 20,432,080 | 0.2% | 86.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 20,361,360 | 0.2% | 87.1% |
| STORE_FAST JUMP_FORWARD | 20,359,980 | 0.2% | 87.4% |
| BUILD_TUPLE STORE_FAST | 20,359,980 | 0.2% | 87.6% |
| POP_TOP LOAD_FAST_LOAD_FAST | 19,385,100 | 0.2% | 87.8% |
| COPY TO_BOOL_BOOL | 19,117,200 | 0.2% | 88.0% |
| RETURN_VALUE TO_BOOL_BOOL | 19,116,480 | 0.2% | 88.2% |
| POP_JUMP_IF_TRUE POP_TOP | 19,115,760 | 0.2% | 88.4% |
| CONTAINS_OP RETURN_VALUE | 19,115,760 | 0.2% | 88.6% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 42,585,540 | 51.5% |
| LOAD_FAST_LOAD_FAST | 38,594,340 | 46.6% |
| BINARY_OP_ADD_INT | 1,581,900 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 22,874,820 | 27.6% |
| GET_ITER | 21,734,820 | 26.3% |
| LOAD_DEREF | 18,985,140 | 22.9% |
| BINARY_OP_ADD_UNICODE | 15,129,960 | 18.3% |
| LOAD_FAST | 1,644,240 | 2.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,580,580 | 50.0% |
| ENTER_EXECUTOR | 991,020 | 31.3% |
| BINARY_SLICE | 589,560 | 18.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,161,160 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 62,765,460 | 97.5% |
| LOAD_FAST | 1,579,860 | 2.5% |
| BINARY_SUBSCR | 15,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 41,914,800 | 65.1% |
| STORE_FAST_STORE_FAST | 20,629,320 | 32.1% |
| BUILD_TUPLE | 1,579,860 | 2.5% |
| LOAD_CONST | 221,340 | 0.3% |
| BINARY_SUBSCR | 15,720 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,985,140 | 100.0% |


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

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,989,360 | 49.3% |
| BINARY_SLICE | 21,734,820 | 26.2% |
| CALL_BUILTIN_CLASS | 18,985,140 | 22.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,374,840 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 43,738,980 | 52.6% |
| FOR_ITER_GEN | 18,985,140 | 22.9% |
| CALL_PY_EXACT_ARGS | 18,985,140 | 22.9% |
| FOR_ITER | 1,374,840 | 1.7% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 240 | 80.0% |
| RETURN_CONST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 18,985,140 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 152,017,440 | 49.6% |
| STORE_FAST | 76,431,360 | 25.0% |
| NOP | 35,489,940 | 11.6% |
| POP_JUMP_IF_FALSE | 21,940,440 | 7.2% |
| STORE_FAST_STORE_FAST | 18,985,140 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 248,538,120 | 81.2% |
| NOP | 35,489,940 | 11.6% |
| LOAD_FAST | 22,210,440 | 7.3% |
| LOAD_GLOBAL_MODULE | 660 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 19,115,760 | 41.5% |
| FOR_ITER_GEN | 18,985,140 | 41.2% |
| RETURN_CONST | 3,461,760 | 7.5% |
| CALL_METHOD_DESCRIPTOR_O | 1,644,180 | 3.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,374,840 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,385,100 | 42.1% |
| RESUME_CHECK | 18,985,140 | 41.2% |
| RETURN_CONST | 3,360,360 | 7.3% |
| LOAD_FAST | 2,971,020 | 6.4% |
| NOP | 1,374,900 | 3.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 80 | 66.7% |
| LOAD_GLOBAL | 40 | 33.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 5,024,540 | 76.1% |
| LOAD_FAST | 1,580,580 | 23.9% |
| LOAD_ATTR_MODULE | 400 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,605,160 | 100.0% |
| LOAD_FAST | 300 | 0.0% |
| CALL | 180 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,985,140 | 100.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 170,083,800 | 55.7% |
| BUILD_TUPLE | 82,846,260 | 27.1% |
| RETURN_VALUE | 30,530,040 | 10.0% |
| CONTAINS_OP | 19,115,760 | 6.3% |
| CALL | 1,674,900 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 168,930,360 | 55.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 65,175,960 | 21.3% |
| RETURN_VALUE | 30,530,040 | 10.0% |
| TO_BOOL_BOOL | 19,116,480 | 6.3% |
| UNPACK_SEQUENCE_TUPLE | 18,985,140 | 6.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,513,480 | 100.0% |
| TO_BOOL | 5,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 21,513,480 | 100.0% |
| TO_BOOL | 5,260 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,985,220 | 87.2% |
| BUILD_TUPLE | 2,514,840 | 11.5% |
| LOAD_DEREF | 269,340 | 1.2% |
| BINARY_OP | 5,320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,500,040 | 98.7% |
| LOAD_GLOBAL_MODULE | 269,340 | 1.2% |
| BINARY_OP | 5,320 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,704,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,704,180 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 269,340 | 74.8% |
| BUILD_MAP | 90,720 | 25.2% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 269,340 | 74.8% |
| LOAD_FAST_LOAD_FAST | 90,720 | 25.2% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,704,180 | 54.3% |
| ENTER_EXECUTOR | 1,213,500 | 38.7% |
| LOAD_ATTR_METHOD_NO_DICT | 130,620 | 4.2% |
| POP_JUMP_IF_FALSE | 90,720 | 2.9% |
| RESUME_CHECK | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,704,180 | 54.3% |
| LOAD_FAST_LOAD_FAST | 1,213,500 | 38.7% |
| CALL_LIST_APPEND | 130,620 | 4.2% |
| BUILD_LIST | 90,720 | 2.9% |
| LOAD_FAST | 120 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,974,500 | 41.7% |
| BINARY_SLICE | 22,874,820 | 15.9% |
| LOAD_FAST_LOAD_FAST | 21,559,980 | 15.0% |
| LOAD_GLOBAL_BUILTIN | 18,985,140 | 13.2% |
| BINARY_OP_ADD_UNICODE | 15,129,960 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 82,846,260 | 57.7% |
| STORE_FAST | 20,359,980 | 14.2% |
| LOAD_CONST | 18,985,140 | 13.2% |
| CALL_ISINSTANCE | 18,985,140 | 13.2% |
| BINARY_OP | 2,514,840 | 1.8% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,825,140 | 76.6% |
| LOAD_FAST_LOAD_FAST | 6,605,120 | 13.0% |
| LOAD_CONST | 3,350,500 | 6.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,674,840 | 3.3% |
| BINARY_SLICE | 221,340 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,940,620 | 43.3% |
| TO_BOOL_BOOL | 18,686,340 | 36.9% |
| STORE_FAST | 5,025,360 | 9.9% |
| RETURN_VALUE | 1,674,900 | 3.3% |
| TO_BOOL_STR | 1,674,840 | 3.3% |


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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,774,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,774,200 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,100,920 | 42.8% |
| LOAD_FAST_LOAD_FAST | 99,520,980 | 28.4% |
| BINARY_SUBSCR_DICT | 58,124,340 | 16.6% |
| LOAD_GLOBAL_MODULE | 43,234,800 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 312,749,520 | 89.1% |
| RETURN_VALUE | 19,115,760 | 5.4% |
| COPY | 19,115,760 | 5.4% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 19,115,760 | 100.0% |
| SWAP | 720 | 0.0% |
| JUMP_FORWARD | 720 | 0.0% |
| COMPARE_OP_INT | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 19,117,200 | 100.0% |
| COMPARE_OP_INT | 720 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 18,985,140 | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 18,985,140 | 100.0% |
| RESUME_CHECK | 60 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 79,747,720 | 56.4% |
| STORE_FAST | 61,713,600 | 43.6% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 99,655,440 | 70.4% |
| LOAD_GLOBAL_BUILTIN | 35,418,960 | 25.0% |
| LOAD_FAST_LOAD_FAST | 2,743,920 | 1.9% |
| RETURN_VALUE | 1,314,840 | 0.9% |
| BUILD_MAP | 1,213,500 | 0.9% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,374,840 | 100.0% |
| FOR_ITER | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,374,840 | 100.0% |
| FOR_ITER | 340 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140 | 70.0% |
| POP_TOP | 60 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 60.0% |
| FOR_ITER_RANGE | 60 | 30.0% |
| ENTER_EXECUTOR | 20 | 10.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,359,980 | 97.6% |
| LOAD_CONST | 269,340 | 1.3% |
| STORE_FAST_STORE_FAST | 221,340 | 1.1% |
| COMPARE_OP_INT | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20,581,320 | 98.7% |
| BINARY_SUBSCR_DICT | 269,340 | 1.3% |
| COPY | 720 | 0.0% |


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
| LOAD_FAST | 45,114,060 | 90.0% |
| LOAD_GLOBAL_MODULE | 5,024,740 | 10.0% |
| LOAD_ATTR | 12,380 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 45,113,820 | 90.0% |
| PUSH_NULL | 5,024,540 | 10.0% |
| LOAD_ATTR | 12,380 | 0.0% |
| LOAD_ATTR_MODULE | 140 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 414,578,940 | 61.8% |
| LOAD_FAST_LOAD_FAST | 74,629,980 | 11.1% |
| LOAD_CONST | 59,359,800 | 8.9% |
| LOAD_DEREF | 37,970,280 | 5.7% |
| LOAD_ATTR_METHOD_NO_DICT | 20,361,360 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_STR | 170,416,980 | 25.4% |
| BINARY_OP_ADD_INT | 158,262,600 | 23.6% |
| BINARY_SUBSCR_DICT | 81,197,520 | 12.1% |
| BINARY_SUBSCR | 62,765,460 | 9.4% |
| LOAD_CONST | 59,359,800 | 8.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,985,140 | 24.8% |
| STORE_FAST | 18,985,140 | 24.8% |
| LOAD_GLOBAL_BUILTIN | 18,985,140 | 24.8% |
| BINARY_SLICE | 18,985,140 | 24.8% |
| LOAD_DEREF | 269,340 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 37,970,280 | 49.6% |
| LOAD_FAST | 18,985,140 | 24.8% |
| CALL_LEN | 18,985,140 | 24.8% |
| LOAD_DEREF | 269,340 | 0.4% |
| BINARY_OP | 269,340 | 0.4% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 344,687,160 | 24.3% |
| STORE_FAST | 286,317,000 | 20.2% |
| BINARY_SUBSCR_STR_INT | 150,100,860 | 10.6% |
| ENTER_EXECUTOR | 99,655,440 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 99,178,800 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 414,578,940 | 29.3% |
| RETURN_VALUE | 170,083,800 | 12.0% |
| CONTAINS_OP | 150,100,920 | 10.6% |
| LOAD_GLOBAL_BUILTIN | 97,502,400 | 6.9% |
| LOAD_GLOBAL_MODULE | 67,702,980 | 4.8% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 248,538,120 | 26.3% |
| LOAD_GLOBAL_MODULE | 243,927,360 | 25.8% |
| STORE_FAST | 205,539,120 | 21.8% |
| POP_JUMP_IF_FALSE | 113,713,980 | 12.0% |
| LOAD_FAST_LOAD_FAST | 57,580,320 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 308,008,980 | 32.6% |
| CONTAINS_OP | 99,520,980 | 10.5% |
| LOAD_FAST | 98,151,720 | 10.4% |
| LOAD_GLOBAL_MODULE | 89,255,160 | 9.5% |
| CALL_PY_EXACT_ARGS | 80,941,320 | 8.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 28.6% |
| RESUME_CHECK | 80 | 19.0% |
| RETURN_VALUE | 60 | 14.3% |
| PUSH_EXC_INFO | 40 | 9.5% |
| POP_JUMP_IF_FALSE | 40 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 61.9% |
| LOAD_GLOBAL_BUILTIN | 140 | 33.3% |
| LOAD_ATTR | 20 | 4.8% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 18,985,200 | 50.0% |
| MAKE_CELL | 18,985,140 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,985,200 | 50.0% |
| MAKE_CELL | 18,985,140 | 50.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 312,749,520 | 47.0% |
| TO_BOOL_BOOL | 174,911,460 | 26.3% |
| COMPARE_OP_STR | 170,416,980 | 25.6% |
| TO_BOOL_NONE | 3,349,680 | 0.5% |
| TO_BOOL_STR | 1,674,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 344,687,160 | 51.8% |
| LOAD_FAST_LOAD_FAST | 113,713,980 | 17.1% |
| ENTER_EXECUTOR | 79,747,720 | 12.0% |
| LOAD_GLOBAL_MODULE | 55,914,520 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 45,031,180 | 6.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 36,906,840 | 63.2% |
| TO_BOOL | 21,513,480 | 36.8% |
| COMPARE_OP_INT | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,303,120 | 67.3% |
| POP_TOP | 19,115,760 | 32.7% |
| RETURN_VALUE | 720 | 0.0% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 18,985,140 | 76.4% |
| POP_TOP | 3,360,360 | 13.5% |
| POP_JUMP_IF_FALSE | 2,277,720 | 9.2% |
| CALL_LIST_APPEND | 130,620 | 0.5% |
| STORE_SUBSCR_DICT | 90,720 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_FOR | 18,985,140 | 76.4% |
| POP_TOP | 3,461,760 | 13.9% |
| TO_BOOL_BOOL | 2,397,720 | 9.7% |
| EXIT_INIT_CHECK | 120 | 0.0% |
| INTERPRETER_EXIT | 60 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 18,985,140 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 60 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,985,140 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 168,930,360 | 19.5% |
| BINARY_SUBSCR_STR_INT | 159,286,500 | 18.4% |
| BINARY_OP_ADD_INT | 136,621,560 | 15.8% |
| BINARY_SUBSCR_DICT | 82,351,020 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 43,738,980 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 286,317,000 | 33.1% |
| LOAD_FAST_LOAD_FAST | 205,539,120 | 23.7% |
| LOAD_GLOBAL_MODULE | 141,557,000 | 16.4% |
| NOP | 76,431,360 | 8.8% |
| ENTER_EXECUTOR | 61,713,600 | 7.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 65,176,020 | 76.0% |
| BINARY_SUBSCR | 20,629,320 | 24.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,379,600 | 27.2% |
| LOAD_FAST_LOAD_FAST | 23,080,620 | 26.9% |
| NOP | 18,985,140 | 22.1% |
| LOAD_DEREF | 18,985,140 | 22.1% |
| LOAD_GLOBAL_MODULE | 1,153,500 | 1.3% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 92.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 720 | 92.3% |
| LOAD_CONST | 60 | 7.7% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 158,262,600 | 100.0% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 136,621,560 | 86.3% |
| LOAD_FAST_LOAD_FAST | 15,129,960 | 9.6% |
| LOAD_CONST | 1,911,600 | 1.2% |
| LOAD_FAST | 1,644,180 | 1.0% |
| BINARY_SLICE | 1,581,900 | 1.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 15,129,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 15,129,960 | 100.0% |


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

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 81,197,520 | 55.8% |
| LOAD_FAST_LOAD_FAST | 64,102,380 | 44.0% |
| JUMP_FORWARD | 269,340 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 82,351,020 | 56.6% |
| CONTAINS_OP | 58,124,340 | 39.9% |
| LOAD_CONST | 1,805,520 | 1.2% |
| LOAD_FAST | 1,644,180 | 1.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,644,180 | 1.1% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 308,008,980 | 99.6% |
| BINARY_OP_ADD_INT | 1,374,840 | 0.4% |
| ENTER_EXECUTOR | 3,660 | 0.0% |
| BINARY_SUBSCR_STR_INT | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,286,500 | 51.5% |
| LOAD_FAST | 150,100,860 | 48.5% |
| PUSH_EXC_INFO | 120 | 0.0% |
| BINARY_SUBSCR_STR_INT | 80 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 18,985,140 | 84.8% |
| LOAD_GLOBAL_BUILTIN | 3,408,400 | 15.2% |
| LOAD_FAST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,985,140 | 84.8% |
| LOAD_GLOBAL_BUILTIN | 1,704,180 | 7.6% |
| BUILD_MAP | 1,704,180 | 7.6% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 77.8% |
| CALL | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 66.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 33.3% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 720 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 78,516,540 | 80.5% |
| BUILD_TUPLE | 18,985,140 | 19.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 97,501,680 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 18,985,140 | 100.0% |
| LOAD_FAST | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 18,985,140 | 100.0% |
| LOAD_FAST | 720 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 130,620 | 99.5% |
| LOAD_FAST | 600 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 130,620 | 99.5% |
| LOAD_GLOBAL_MODULE | 600 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,674,840 | 88.3% |
| LOAD_CONST | 221,340 | 11.7% |
| LOAD_ATTR | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,674,840 | 88.3% |
| POP_TOP | 221,340 | 11.7% |
| SWAP | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,374,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,374,840 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,644,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,644,180 | 100.0% |
| TO_BOOL_BOOL | 720 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 89,255,160 | 32.9% |
| LOAD_FAST_LOAD_FAST | 80,941,320 | 29.9% |
| LOAD_FAST | 59,043,640 | 21.8% |
| LOAD_ATTR_CLASS | 21,513,480 | 7.9% |
| GET_ITER | 18,985,140 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 233,143,980 | 86.0% |
| MAKE_CELL | 18,985,200 | 7.0% |
| COPY_FREE_VARS | 18,985,140 | 7.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 271,140 | 99.2% |
| LOAD_FAST | 720 | 0.3% |
| LOAD_CONST | 720 | 0.3% |
| COPY | 720 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 271,140 | 99.2% |
| POP_JUMP_IF_TRUE | 720 | 0.3% |
| JUMP_FORWARD | 720 | 0.3% |
| COPY | 720 | 0.3% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 170,416,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 170,416,980 | 100.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 18,985,140 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,985,140 | 100.0% |
| JUMP_BACKWARD | 60 | 0.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 18,985,140 | 100.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 43,738,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 41,938,320 | 95.9% |
| LOAD_FAST | 1,740,660 | 4.0% |
| LOAD_FAST_LOAD_FAST | 60,000 | 0.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 23,157,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 21,513,480 | 92.9% |
| LOAD_CONST | 1,644,180 | 7.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,488,720 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 43,738,980 | 94.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,374,840 | 3.0% |
| GET_ITER | 1,374,840 | 3.0% |
| LOAD_FAST | 120 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,063,500 | 88.8% |
| BINARY_SUBSCR_DICT | 1,644,180 | 6.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,374,840 | 5.1% |
| LOAD_GLOBAL_MODULE | 760 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,361,360 | 75.2% |
| LOAD_FAST | 1,866,840 | 6.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,674,840 | 6.2% |
| CALL | 1,674,840 | 6.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,374,840 | 5.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 45,113,820 | 99.5% |
| LOAD_FAST | 221,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,690,980 | 96.4% |
| CALL_PY_EXACT_ARGS | 1,374,840 | 3.0% |
| LOAD_DEREF | 269,340 | 0.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 65.0% |
| LOAD_ATTR | 140 | 35.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 400 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,502,400 | 37.9% |
| POP_JUMP_IF_FALSE | 45,031,180 | 17.5% |
| ENTER_EXECUTOR | 35,418,960 | 13.8% |
| STORE_FAST | 20,432,080 | 7.9% |
| SET_FUNCTION_ATTRIBUTE | 18,985,140 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 99,178,800 | 38.6% |
| CALL_ISINSTANCE | 78,516,540 | 30.5% |
| LOAD_GLOBAL_BUILTIN | 18,985,140 | 7.4% |
| LOAD_DEREF | 18,985,140 | 7.4% |
| LOAD_CONST | 18,985,140 | 7.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 141,557,000 | 32.4% |
| LOAD_FAST_LOAD_FAST | 89,255,160 | 20.5% |
| LOAD_FAST | 67,702,980 | 15.5% |
| RESUME_CHECK | 58,330,440 | 13.4% |
| POP_JUMP_IF_FALSE | 55,914,520 | 12.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 243,927,360 | 55.9% |
| CALL_PY_EXACT_ARGS | 89,255,160 | 20.5% |
| CONTAINS_OP | 43,234,800 | 9.9% |
| STORE_FAST | 30,259,920 | 6.9% |
| LOAD_ATTR_CLASS | 23,157,660 | 5.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 233,143,980 | 75.2% |
| CALL | 21,940,620 | 7.1% |
| MAKE_CELL | 18,985,200 | 6.1% |
| POP_TOP | 18,985,140 | 6.1% |
| CALL_KW | 16,774,200 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 152,017,440 | 49.1% |
| LOAD_FAST | 97,899,360 | 31.6% |
| LOAD_GLOBAL_MODULE | 58,330,440 | 18.8% |
| LOAD_FAST_LOAD_FAST | 1,581,360 | 0.5% |
| LOAD_CONST | 780 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 66.7% |
| STORE_ATTR | 60 | 16.7% |
| LOAD_FAST_LOAD_FAST | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 66.7% |
| LOAD_FAST | 60 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 11.1% |
| LOAD_GLOBAL | 20 | 5.6% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,985,140 | 86.3% |
| LOAD_FAST_LOAD_FAST | 3,008,400 | 13.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,985,140 | 86.3% |
| LOAD_FAST_LOAD_FAST | 2,917,680 | 13.3% |
| RETURN_CONST | 90,720 | 0.4% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,674,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,674,840 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 97,501,680 | 46.0% |
| LOAD_FAST | 54,998,160 | 26.0% |
| COPY | 19,117,200 | 9.0% |
| RETURN_VALUE | 19,116,480 | 9.0% |
| CALL | 18,686,340 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 174,911,460 | 82.6% |
| POP_JUMP_IF_TRUE | 36,906,840 | 17.4% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,349,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,349,680 | 100.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,674,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,674,840 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 18,985,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,985,140 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 65,175,960 | 100.0% |
| CALL_BUILTIN_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 65,176,020 | 100.0% |


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
| specialization.deferred |     64345320 | 12.4% |
| specialization.deopt |           80 | 0.0% |
|          hit |    454952520 | 87.6% |
|         miss |         4280 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 0.5% |
| Failure | 15,720 | 99.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 15,340 | 97.6% |
| other | 380 | 2.4% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     21993540 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21513480 | 9.0% |
|          hit |    218517660 | 91.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 5,260 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 5,260 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21769380 | 11.0% |
|          hit |    176555220 | 89.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.4% |
| Failure | 5,320 | 99.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 5,320 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     50677080 | 10.9% |
|          hit |    415043940 | 89.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 1.9% |
| Failure | 12,660 | 98.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 5,460 | 43.1% |
| code complex parameters | 5,380 | 42.5% |
| cmethod | 1,260 | 10.0% |
| class no vectorcall | 440 | 3.5% |
| cfunc noargs | 60 | 0.5% |
| class mutable | 20 | 0.2% |
| cfunc varargs keywords | 20 | 0.2% |
| cfunc varargs | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    170690280 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1374840 | 1.7% |
|          hit |     81709380 | 98.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 340 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 340 | 100.0% |


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
| specialization.deferred |     50138600 | 26.1% |
|          hit |    142065460 | 73.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 1.9% |
| Failure | 12,360 | 98.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 11,080 | 89.6% |
| method | 1,260 | 10.2% |
| class attr simple | 20 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |    693486040 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 100.0% |
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
|          hit |          360 | 85.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     84161160 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 5,681,638,740 | 60.0% |
| Not specialized | 1,016,108,360 | 10.7% |
| Specialized | 2,769,004,220 | 29.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,031,240 | 100.0% |
| BINARY_SUBSCR | 64,345,320 | 0.0% |
| CALL | 50,677,080 | 0.0% |
| LOAD_ATTR | 50,138,600 | 0.0% |
| BINARY_OP | 21,769,380 | 0.0% |
| TO_BOOL | 21,513,480 | 0.0% |
| FOR_ITER | 1,374,840 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 4,280 | 66.5% |
| RESUME_CHECK | 1,080 | 16.8% |
| RESUME | 1,080 | 16.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 0 | 0.0% |
| SWAP | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 300 | 0.0% |
| Calls to Python functions inlined | 328,814,580 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 330,411,660 | 100.5% |
| Frame objects created | 120 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 197,836,600 | 13.9% |
| Frees to freelist | 197,836,740 |  |
| Allocations | 1,222,290,820 | 86.1% |
| Allocations to 512 bytes | 1,221,981,800 | 86.0% |
| Allocations to 4 kbytes | 308,120 | 0.0% |
| Allocations over 4 kbytes | 900 | 0.0% |
| Frees | 1,227,318,405 |  |
| New values | 60 |  |
| Interpreter increfs | 4,557,109,360 | 49.1% |
| Interpreter decrefs | 4,869,084,600 | 45.2% |
| Increfs | 4,723,390,946 | 50.9% |
| Decrefs | 5,900,181,051 | 54.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 50,153,754 |  |
| Method cache misses | 66 |  |
| Method cache collisions | 166 |  |
| Method cache dunder hits | 72,687,240 |  |
| Method cache dunder misses | 120 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 2,460 | 0 | 22,781,200 |
| 1 | 220 | 0 | 20,720,960 |
| 2 | 20 | 0 | 4,926,320 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 20 |  |
| Traces created | 20 | 100.0% |
| Traces executed | 141,461,340 |  |
| Uops executed | 24,314,451,420 | 171 |
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
| <= 64 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 540 | 0.0% |
| <= 8 | 24,843,840 | 17.6% |
| <= 16 | 4,582,860 | 3.2% |
| <= 32 | 23,820,660 | 16.8% |
| <= 64 | 53,760,360 | 38.0% |
| <= 128 | 10,320,600 | 7.3% |
| <= 256 | 9,841,920 | 7.0% |
| <= 512 | 1,437,600 | 1.0% |
| <= 1024 | 2,648,820 | 1.9% |
| <= 2048 | 9,716,100 | 6.9% |
| <= 4096 | 476,580 | 0.3% |
| <= 8192 | 8,640 | 0.0% |
| <= 16384 | 2,760 | 0.0% |
| <= 32768 | 60 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST | 5,843,279,400 | 24.0% | 24.0% |
| _SET_IP | 5,435,740,140 | 22.4% | 46.4% |
| LOAD_CONST | 2,213,986,140 | 9.1% | 55.5% |
| _POP_JUMP_IF_TRUE | 2,165,250,360 | 8.9% | 64.4% |
| STORE_FAST | 1,646,922,120 | 6.8% | 71.2% |
| COMPARE_OP_STR | 1,336,540,380 | 5.5% | 76.7% |
| CONTAINS_OP | 933,192,960 | 3.8% | 80.5% |
| BINARY_SUBSCR_STR_INT | 876,345,540 | 3.6% | 84.1% |
| _GUARD_BOTH_INT | 836,329,800 | 3.4% | 87.6% |
| _BINARY_OP_ADD_INT | 836,329,800 | 3.4% | 91.0% |
| _JUMP_TO_TOP | 833,909,460 | 3.4% | 94.4% |
| _POP_JUMP_IF_FALSE | 274,226,160 | 1.1% | 95.5% |
| _EXIT_TRACE | 141,457,680 | 0.6% | 96.1% |
| _GUARD_GLOBALS_VERSION | 111,881,520 | 0.5% | 96.6% |
| _ITER_CHECK_TUPLE | 99,025,260 | 0.4% | 97.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 99,025,260 | 0.4% | 97.4% |
| BINARY_SUBSCR_DICT | 95,342,400 | 0.4% | 97.8% |
| _LOAD_GLOBAL_BUILTINS | 70,717,920 | 0.3% | 98.1% |
| _GUARD_BUILTINS_VERSION | 70,717,920 | 0.3% | 98.4% |
| TO_BOOL_BOOL | 70,717,920 | 0.3% | 98.7% |
| _ITER_NEXT_TUPLE | 57,206,940 | 0.2% | 98.9% |
| POP_TOP | 41,818,320 | 0.2% | 99.1% |
| _LOAD_GLOBAL_MODULE | 41,163,600 | 0.2% | 99.2% |
| CALL_ISINSTANCE | 35,358,960 | 0.1% | 99.4% |
| _SAVE_CURRENT_IP | 20,581,800 | 0.1% | 99.5% |
| _PUSH_FRAME | 20,581,800 | 0.1% | 99.6% |
| _INIT_CALL_PY_EXACT_ARGS | 20,581,800 | 0.1% | 99.6% |
| _CHECK_STACK_SPACE | 20,581,800 | 0.1% | 99.7% |
| _CHECK_PEP_523 | 20,581,800 | 0.1% | 99.8% |
| _CHECK_FUNCTION_EXACT_ARGS | 20,581,800 | 0.1% | 99.9% |
| RESUME_CHECK | 20,581,800 | 0.1% | 100.0% |
| BINARY_SUBSCR | 1,587,000 | 0.0% | 100.0% |
| BUILD_TUPLE | 1,314,840 | 0.0% | 100.0% |
| BINARY_SLICE | 991,020 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|


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
