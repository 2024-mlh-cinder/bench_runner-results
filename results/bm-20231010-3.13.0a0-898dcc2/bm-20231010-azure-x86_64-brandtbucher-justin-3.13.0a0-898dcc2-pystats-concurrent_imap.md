
# Pystats results

- benchmark: concurrent_imap
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 72,212,294 | 17.9% | 17.9% |  |
| RESUME_CHECK | 27,513,505 | 6.8% | 24.7% | 0.0% |
| STORE_FAST | 20,645,999 | 5.1% | 29.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,333,477 | 4.5% | 34.4% | 0.9% |
| POP_TOP | 18,000,158 | 4.5% | 38.9% |  |
| RETURN_VALUE | 16,649,872 | 4.1% | 43.0% |  |
| POP_JUMP_IF_FALSE | 14,328,629 | 3.6% | 46.5% |  |
| LOAD_GLOBAL_MODULE | 11,713,412 | 2.9% | 49.4% | 0.0% |
| LOAD_CONST | 11,101,298 | 2.8% | 52.2% |  |
| LOAD_FAST_LOAD_FAST | 10,348,305 | 2.6% | 54.8% |  |
| CALL_PY_EXACT_ARGS | 8,982,511 | 2.2% | 57.0% |  |
| INTERPRETER_EXIT | 8,944,499 | 2.2% | 59.2% |  |
| CALL | 8,761,742 | 2.2% | 61.4% |  |
| ENTER_EXECUTOR | 7,800,253 | 1.9% | 63.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,739,954 | 1.9% | 65.2% | 0.8% |
| LOAD_ATTR | 7,404,374 | 1.8% | 67.1% |  |
| RETURN_CONST | 6,879,680 | 1.7% | 68.8% |  |
| NOP | 6,727,824 | 1.7% | 70.4% |  |
| JUMP_BACKWARD | 5,706,451 | 1.4% | 71.9% |  |
| COPY | 5,458,708 | 1.4% | 73.2% |  |
| LOAD_GLOBAL_BUILTIN | 5,450,773 | 1.4% | 74.6% |  |
| BINARY_OP | 5,358,386 | 1.3% | 75.9% |  |
| YIELD_VALUE | 5,184,960 | 1.3% | 77.2% |  |
| TO_BOOL_BOOL | 5,048,058 | 1.3% | 78.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,806,540 | 1.2% | 79.6% |  |
| FOR_ITER_GEN | 4,760,640 | 1.2% | 80.8% |  |
| PUSH_NULL | 4,271,805 | 1.1% | 81.9% |  |
| TO_BOOL_INT | 3,962,358 | 1.0% | 82.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,762,066 | 0.9% | 83.8% |  |
| STORE_FAST_STORE_FAST | 3,630,775 | 0.9% | 84.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,232,182 | 0.8% | 85.5% | 4.6% |
| BUILD_TUPLE | 3,228,453 | 0.8% | 86.3% |  |
| COMPARE_OP_INT | 2,819,650 | 0.7% | 87.0% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 2,220,403 | 0.6% | 87.5% |  |
| POP_JUMP_IF_TRUE | 1,991,361 | 0.5% | 88.0% |  |
| SWAP | 1,977,643 | 0.5% | 88.5% |  |
| CALL_FUNCTION_EX | 1,810,132 | 0.4% | 89.0% |  |
| LOAD_ATTR_MODULE | 1,770,025 | 0.4% | 89.4% |  |
| GET_ITER | 1,626,124 | 0.4% | 89.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,615,735 | 0.4% | 90.2% |  |
| FOR_ITER_LIST | 1,561,523 | 0.4% | 90.6% |  |
| LOAD_DEREF | 1,391,928 | 0.3% | 90.9% |  |
| BEFORE_WITH | 1,380,817 | 0.3% | 91.3% |  |
| COPY_FREE_VARS | 1,354,848 | 0.3% | 91.6% |  |
| CONTAINS_OP | 1,323,487 | 0.3% | 91.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,311,060 | 0.3% | 92.3% |  |
| LOAD_SUPER_ATTR_METHOD | 1,283,208 | 0.3% | 92.6% |  |
| UNARY_INVERT | 1,280,340 | 0.3% | 92.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,269,549 | 0.3% | 93.2% |  |
| JUMP_FORWARD | 1,267,787 | 0.3% | 93.5% |  |
| BUILD_MAP | 1,259,442 | 0.3% | 93.8% |  |
| CALL_BUILTIN_FAST | 1,203,828 | 0.3% | 94.1% |  |
| TO_BOOL | 1,185,862 | 0.3% | 94.4% |  |
| BUILD_LIST | 1,150,324 | 0.3% | 94.7% |  |
| COMPARE_OP_STR | 1,114,820 | 0.3% | 95.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,113,451 | 0.3% | 95.3% |  |
| FOR_ITER | 976,760 | 0.2% | 95.5% |  |
| STORE_SUBSCR_DICT | 962,546 | 0.2% | 95.8% |  |
| STORE_FAST_LOAD_FAST | 959,040 | 0.2% | 96.0% |  |
| CALL_ISINSTANCE | 906,966 | 0.2% | 96.2% |  |
| UNPACK_SEQUENCE_TUPLE | 876,974 | 0.2% | 96.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 847,694 | 0.2% | 96.6% |  |
| POP_JUMP_IF_NONE | 840,709 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 831,714 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 799,524 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 799,524 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 783,642 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 720,579 | 0.2% | 97.8% |  |
| LOAD_FAST_CHECK | 625,567 | 0.2% | 98.0% |  |
| LIST_APPEND | 624,103 | 0.2% | 98.1% |  |
| CALL_BUILTIN_CLASS | 623,849 | 0.2% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 577,567 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 476,239 | 0.1% | 98.6% |  |
| COMPARE_OP | 438,913 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 415,122 | 0.1% | 99.0% |  |
| LIST_EXTEND | 362,306 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,776 | 0.1% | 99.1% |  |
| CALL_LEN | 296,586 | 0.1% | 99.2% |  |
| CALL_KW | 267,629 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 247,085 | 0.1% | 99.3% |  |
| UNARY_NOT | 212,775 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 201,807 | 0.1% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 193,649 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 181,275 | 0.0% | 99.5% |  |
| TO_BOOL_NONE | 180,326 | 0.0% | 99.6% |  |
| STORE_DEREF | 103,200 | 0.0% | 99.6% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.7% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,654 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,417 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,809 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 58,566 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 57,734 | 0.0% | 99.9% | 7.6% |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 35,857 | 0.0% | 99.9% |  |
| POP_EXCEPT | 35,857 | 0.0% | 99.9% |  |
| IS_OP | 34,492 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 31,537 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 28,800 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 99.9% |  |
| IMPORT_NAME | 24,480 | 0.0% | 99.9% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 23,882 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,774 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,961 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 12,960 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 9,600 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 800 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 212 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,564,585 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 15,532,594 | 3.9% | 8.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,947,951 | 2.2% | 10.2% |
| CACHE RESUME_CHECK | 8,861,456 | 2.2% | 12.4% |
| STORE_FAST LOAD_FAST | 8,812,854 | 2.2% | 14.6% |
| LOAD_FAST RETURN_VALUE | 8,074,043 | 2.0% | 16.6% |
| RETURN_VALUE INTERPRETER_EXIT | 7,843,448 | 1.9% | 18.5% |
| LOAD_FAST LOAD_ATTR | 5,830,206 | 1.4% | 20.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,760,899 | 1.4% | 21.4% |
| POP_TOP ENTER_EXECUTOR | 5,669,531 | 1.4% | 22.8% |
| POP_TOP LOAD_FAST | 5,562,954 | 1.4% | 24.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,373,079 | 1.3% | 25.5% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.3% | 26.8% |
| RETURN_CONST POP_TOP | 4,844,406 | 1.2% | 28.0% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.2% | 29.2% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.2% | 30.3% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.2% | 31.5% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.1% | 32.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,192,806 | 1.0% | 33.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,136,487 | 1.0% | 34.7% |
| NOP LOAD_FAST | 3,973,322 | 1.0% | 35.6% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,962,358 | 1.0% | 36.6% |
| ENTER_EXECUTOR YIELD_VALUE | 3,888,000 | 1.0% | 37.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,773,557 | 0.9% | 38.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,503,568 | 0.9% | 39.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,163,792 | 0.8% | 40.2% |
| STORE_FAST NOP | 2,880,428 | 0.7% | 40.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,875,185 | 0.7% | 41.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,817,339 | 0.7% | 42.3% |
| LOAD_CONST LOAD_CONST | 2,795,118 | 0.7% | 43.0% |
| LOAD_FAST LOAD_CONST | 2,793,592 | 0.7% | 43.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,791,584 | 0.7% | 44.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,760,414 | 0.7% | 45.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,684,744 | 0.7% | 45.7% |
| PUSH_NULL LOAD_FAST | 2,609,565 | 0.6% | 46.4% |
| CALL STORE_FAST | 2,535,497 | 0.6% | 47.0% |
| LOAD_ATTR LOAD_FAST | 2,458,028 | 0.6% | 47.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,397,339 | 0.6% | 48.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,368,820 | 0.6% | 48.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,205,765 | 0.5% | 49.3% |
| COPY TO_BOOL_INT | 2,174,346 | 0.5% | 49.9% |
| BINARY_OP COPY | 2,174,346 | 0.5% | 50.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,173,007 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,049,719 | 0.5% | 51.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,012,845 | 0.5% | 52.0% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 52.5% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 52.9% |
| LOAD_CONST CALL | 1,937,716 | 0.5% | 53.4% |
| LOAD_FAST PUSH_NULL | 1,931,383 | 0.5% | 53.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,896,020 | 0.5% | 54.4% |
| CALL RETURN_VALUE | 1,870,806 | 0.5% | 54.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,801,090 | 0.4% | 55.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,769,932 | 0.4% | 55.7% |
| RETURN_VALUE STORE_FAST | 1,731,537 | 0.4% | 56.2% |
| CALL POP_TOP | 1,694,915 | 0.4% | 56.6% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,657,128 | 0.4% | 57.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,624,217 | 0.4% | 57.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,610,455 | 0.4% | 57.8% |
| LOAD_CONST COMPARE_OP_INT | 1,543,397 | 0.4% | 58.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,525,510 | 0.4% | 58.6% |
| RETURN_VALUE RETURN_VALUE | 1,497,325 | 0.4% | 58.9% |
| POP_TOP RETURN_CONST | 1,427,366 | 0.4% | 59.3% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,252 | 0.3% | 59.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,374,006 | 0.3% | 60.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,367,052 | 0.3% | 60.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,360,189 | 0.3% | 60.6% |
| NOP LOAD_GLOBAL_MODULE | 1,359,632 | 0.3% | 61.0% |
| COPY_FREE_VARS RESUME_CHECK | 1,354,848 | 0.3% | 61.3% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,350,408 | 0.3% | 61.6% |
| LOAD_DEREF LOAD_FAST | 1,350,408 | 0.3% | 62.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,331,715 | 0.3% | 62.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,326,397 | 0.3% | 62.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,323,487 | 0.3% | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,323,480 | 0.3% | 63.3% |
| LOAD_FAST BUILD_TUPLE | 1,314,486 | 0.3% | 63.6% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,307,780 | 0.3% | 63.9% |
| POP_TOP LOAD_CONST | 1,302,499 | 0.3% | 64.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,284,798 | 0.3% | 64.6% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,283,208 | 0.3% | 64.9% |
| UNARY_INVERT BINARY_OP | 1,280,340 | 0.3% | 65.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,268,328 | 0.3% | 65.5% |
| ENTER_EXECUTOR CALL | 1,228,304 | 0.3% | 65.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,202,334 | 0.3% | 66.1% |
| LOAD_CONST LOAD_FAST | 1,199,299 | 0.3% | 66.4% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,195,058 | 0.3% | 66.7% |
| GET_ITER FOR_ITER_LIST | 1,186,884 | 0.3% | 67.0% |
| POP_TOP NOP | 1,183,449 | 0.3% | 67.3% |
| LOAD_FAST GET_ITER | 1,145,164 | 0.3% | 67.6% |
| LOAD_FAST TO_BOOL | 1,144,959 | 0.3% | 67.9% |
| RETURN_VALUE POP_TOP | 1,135,510 | 0.3% | 68.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,124,520 | 0.3% | 68.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,119,030 | 0.3% | 68.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,101,289 | 0.3% | 69.0% |
| BINARY_OP STORE_FAST | 1,097,733 | 0.3% | 69.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,087,381 | 0.3% | 69.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,085,473 | 0.3% | 69.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,077,171 | 0.3% | 70.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,065,849 | 0.3% | 70.3% |
| RESUME_CHECK NOP | 1,045,206 | 0.3% | 70.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,038,145 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,861,456 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 936,035 | 67.8% |
| RETURN_VALUE | 374,322 | 27.1% |
| LOAD_GLOBAL_MODULE | 61,923 | 4.5% |
| CALL | 4,320 | 0.3% |
| ENTER_EXECUTOR | 4,217 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,175 | 72.6% |
| STORE_FAST | 378,642 | 27.4% |


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
| LOAD_FAST_LOAD_FAST | 432,000 | 90.7% |
| LOAD_CONST | 44,017 | 9.2% |
| BINARY_SUBSCR | 222 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.7% |
| STORE_FAST | 44,017 | 9.2% |
| BINARY_SUBSCR | 222 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 27,696 | 87.8% |
| LOAD_ATTR_MODULE | 3,840 | 12.2% |
| LOAD_GLOBAL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 31,537 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,323 | 48.4% |
| CALL | 20,643 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,599 | 16.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,603 | 77.9% |
| RETURN_CONST | 7,683 | 13.1% |
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
| RETURN_CONST | 799,524 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 799,524 | 100.0% |


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
| LOAD_FAST | 1,145,164 | 70.4% |
| STORE_FAST_LOAD_FAST | 432,000 | 26.6% |
| CALL_BUILTIN_CLASS | 28,800 | 1.8% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,186,884 | 73.0% |
| LOAD_FAST_AND_CLEAR | 384,400 | 23.6% |
| FOR_ITER_RANGE | 23,640 | 1.5% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,843,448 | 87.7% |
| RETURN_CONST | 668,091 | 7.5% |
| YIELD_VALUE | 432,960 | 4.8% |

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
| STORE_FAST | 2,880,428 | 42.8% |
| POP_TOP | 1,183,449 | 17.6% |
| RESUME_CHECK | 1,045,206 | 15.5% |
| POP_JUMP_IF_FALSE | 1,007,873 | 15.0% |
| POP_JUMP_IF_NOT_NONE | 380,755 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,973,322 | 59.1% |
| LOAD_GLOBAL_MODULE | 1,359,632 | 20.2% |
| LOAD_GLOBAL_BUILTIN | 552,350 | 8.2% |
| LOAD_FAST_LOAD_FAST | 437,280 | 6.5% |
| LOAD_CONST | 396,960 | 5.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 23,376 | 65.2% |
| COPY | 8,641 | 24.1% |
| POP_TOP | 3,840 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 23,376 | 65.2% |
| RERAISE | 8,641 | 24.1% |
| JUMP_FORWARD | 3,840 | 10.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.8% |
| RETURN_CONST | 4,844,406 | 26.9% |
| CALL | 1,694,915 | 9.4% |
| RETURN_VALUE | 1,135,510 | 6.3% |
| POP_JUMP_IF_FALSE | 1,119,030 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,669,531 | 31.5% |
| LOAD_FAST | 5,562,954 | 30.9% |
| RETURN_CONST | 1,427,366 | 7.9% |
| LOAD_CONST | 1,302,499 | 7.2% |
| NOP | 1,183,449 | 6.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,697 | 77.2% |
| RERAISE | 4,320 | 12.0% |
| CALL_KW | 3,840 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 27,696 | 77.2% |
| WITH_EXCEPT_START | 4,320 | 12.0% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.7% |
| LOAD_GLOBAL | 1 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,931,383 | 45.2% |
| LOAD_ATTR_MODULE | 1,284,798 | 30.1% |
| LOAD_ATTR | 961,424 | 22.5% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,609,565 | 61.1% |
| CALL | 756,529 | 17.7% |
| LOAD_FAST_LOAD_FAST | 614,428 | 14.4% |
| LOAD_CONST | 236,020 | 5.5% |
| CALL_PY_EXACT_ARGS | 37,440 | 0.9% |


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
| LOAD_FAST | 8,074,043 | 48.5% |
| CALL | 1,870,806 | 11.2% |
| RETURN_VALUE | 1,497,325 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,195,058 | 7.2% |
| CALL_FUNCTION_EX | 948,892 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,843,448 | 47.1% |
| STORE_FAST | 1,731,537 | 10.4% |
| RETURN_VALUE | 1,497,325 | 9.0% |
| POP_TOP | 1,135,510 | 6.8% |
| LOAD_FAST_LOAD_FAST | 894,006 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,694 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 7 | 0.0% |
| LOAD_FAST | 7 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,144,959 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,848 | 3.4% |
| TO_BOOL | 1,048 | 0.1% |
| LOAD_ATTR | 5 | 0.0% |
| RETURN_VALUE | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 633,812 | 53.4% |
| POP_JUMP_IF_FALSE | 551,000 | 46.5% |
| TO_BOOL | 1,048 | 0.1% |
| TO_BOOL_BOOL | 2 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 894,006 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 386,334 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,280,340 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 212,775 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 212,775 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,875,185 | 53.7% |
| UNARY_INVERT | 1,280,340 | 23.9% |
| POP_JUMP_IF_FALSE | 894,006 | 16.7% |
| LOAD_ATTR | 203,727 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,174,346 | 40.6% |
| STORE_FAST | 1,097,733 | 20.5% |
| UNARY_INVERT | 894,006 | 16.7% |
| TO_BOOL_INT | 894,006 | 16.7% |
| BUILD_TUPLE | 193,167 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 384,400 | 33.4% |
| JUMP_FORWARD | 374,322 | 32.5% |
| LOAD_FAST | 193,649 | 16.8% |
| POP_TOP | 180,673 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,802 | 33.6% |
| SWAP | 384,400 | 33.4% |
| STORE_FAST | 375,282 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.3% |
| LOAD_FAST | 396,960 | 31.5% |
| RESUME_CHECK | 382,002 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 814,482 | 64.7% |
| BUILD_TUPLE | 432,000 | 34.3% |
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
| LOAD_FAST | 1,314,486 | 40.7% |
| LOAD_FAST_LOAD_FAST | 870,240 | 27.0% |
| BUILD_MAP | 432,000 | 13.4% |
| RETURN_VALUE | 384,000 | 11.9% |
| BINARY_OP | 193,167 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 894,966 | 27.7% |
| YIELD_VALUE | 864,000 | 26.8% |
| BUILD_MAP | 432,000 | 13.4% |
| STORE_FAST | 384,000 | 11.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 11.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,937,716 | 22.1% |
| ENTER_EXECUTOR | 1,228,304 | 14.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,077,171 | 12.3% |
| LOAD_FAST_LOAD_FAST | 1,016,495 | 11.6% |
| BUILD_TUPLE | 894,966 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,535,497 | 28.9% |
| RETURN_VALUE | 1,870,806 | 21.4% |
| POP_TOP | 1,694,915 | 19.3% |
| LOAD_FAST | 787,451 | 9.0% |
| TO_BOOL_BOOL | 546,281 | 6.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,252 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,892 | 52.4% |
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
| LOAD_CONST | 263,309 | 98.4% |
| ENTER_EXECUTOR | 4,320 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 215,713 | 80.6% |
| LOAD_FAST | 21,600 | 8.1% |
| RETURN_VALUE | 15,840 | 5.9% |
| STORE_FAST | 10,560 | 3.9% |
| PUSH_EXC_INFO | 3,840 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 438,051 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 477 | 0.1% |
| COMPARE_OP | 295 | 0.1% |
| COMPARE_OP_INT | 71 | 0.0% |
| LOAD_GLOBAL_MODULE | 11 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 438,487 | 99.9% |
| COMPARE_OP | 295 | 0.1% |
| COMPARE_OP_INT | 113 | 0.0% |
| COMPARE_OP_STR | 11 | 0.0% |
| POP_JUMP_IF_TRUE | 7 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,323,480 | 100.0% |
| LOAD_ATTR | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,323,487 | 100.0% |


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
| BINARY_OP | 2,174,346 | 39.8% |
| STORE_FAST | 1,972,320 | 36.1% |
| LOAD_CONST | 825,600 | 15.1% |
| LOAD_FAST | 440,041 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,174,346 | 39.8% |
| STORE_FAST | 1,972,800 | 36.1% |
| STORE_FAST_STORE_FAST | 820,320 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 429,467 | 7.9% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 894,006 | 66.0% |
| CALL_ALLOC_AND_ENTER_INIT | 374,322 | 27.6% |
| CACHE | 82,080 | 6.1% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,354,848 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,809 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,206 | 66.7% |
| RETURN_CONST | 20,643 | 31.9% |
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
| POP_TOP | 5,669,531 | 72.7% |
| POP_JUMP_IF_NOT_NONE | 745,646 | 9.6% |
| LIST_APPEND | 539,623 | 6.9% |
| STORE_FAST_STORE_FAST | 432,000 | 5.5% |
| CALL_LIST_APPEND | 193,167 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,888,000 | 49.8% |
| CALL | 1,228,304 | 15.7% |
| LOAD_FAST | 756,021 | 9.7% |
| CALL_PY_WITH_DEFAULTS | 567,684 | 7.3% |
| LOAD_ATTR_PROPERTY | 530,613 | 6.8% |


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
| RETURN_VALUE | 20,640 | 59.8% |
| LOAD_FAST | 12,960 | 37.6% |
| LOAD_GLOBAL_MODULE | 892 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,492 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,320,000 | 75.7% |
| POP_TOP | 864,858 | 15.2% |
| ENTER_EXECUTOR | 432,000 | 7.6% |
| LIST_APPEND | 84,480 | 1.5% |
| STORE_FAST_STORE_FAST | 4,320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 4,752,000 | 83.3% |
| FOR_ITER | 952,800 | 16.7% |
| FOR_ITER_LIST | 799 | 0.0% |
| LOAD_FAST | 403 | 0.0% |
| FOR_ITER_RANGE | 242 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 802,091 | 63.3% |
| POP_TOP | 452,256 | 35.7% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 837,926 | 66.1% |
| BUILD_LIST | 374,322 | 29.5% |
| POP_EXCEPT | 23,376 | 1.8% |
| LOAD_GLOBAL_MODULE | 18,723 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 346,456 | 55.5% |
| LOAD_ATTR | 193,167 | 31.0% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 539,623 | 86.5% |
| JUMP_BACKWARD | 84,480 | 13.5% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,633 | 50.1% |
| RETURN_VALUE | 180,673 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,153 | 50.0% |
| STORE_FAST | 180,673 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,830,206 | 78.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,360,189 | 18.4% |
| LOAD_GLOBAL_MODULE | 119,613 | 1.6% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,894 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,458,028 | 33.2% |
| PUSH_NULL | 961,424 | 13.0% |
| STORE_SUBSCR_DICT | 894,006 | 12.1% |
| POP_JUMP_IF_NOT_NONE | 816,573 | 11.0% |
| STORE_FAST | 556,750 | 7.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,795,118 | 25.2% |
| LOAD_FAST | 2,793,592 | 25.2% |
| POP_TOP | 1,302,499 | 11.7% |
| POP_JUMP_IF_FALSE | 689,809 | 6.2% |
| LOAD_ATTR_METHOD_NO_DICT | 548,668 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,795,118 | 25.2% |
| CALL | 1,937,716 | 17.5% |
| COMPARE_OP_INT | 1,543,397 | 13.9% |
| LOAD_FAST | 1,199,299 | 10.8% |
| COPY | 825,600 | 7.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,350,408 | 97.0% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,350,408 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 3.0% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,532,594 | 21.5% |
| STORE_FAST | 8,812,854 | 12.2% |
| POP_JUMP_IF_FALSE | 5,760,899 | 8.0% |
| POP_TOP | 5,562,954 | 7.7% |
| NOP | 3,973,322 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,564,585 | 22.9% |
| RETURN_VALUE | 8,074,043 | 11.2% |
| LOAD_ATTR | 5,830,206 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,373,079 | 7.4% |
| CALL_PY_EXACT_ARGS | 3,773,557 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 384,400 | 66.6% |
| LOAD_FAST_AND_CLEAR | 193,167 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 384,400 | 66.6% |
| LOAD_FAST_AND_CLEAR | 193,167 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 69.1% |
| POP_JUMP_IF_NONE | 181,155 | 29.0% |
| LOAD_ATTR_CLASS | 12,412 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 69.1% |
| LOAD_GLOBAL_MODULE | 181,155 | 29.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,412 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,012,845 | 19.5% |
| LOAD_FAST_LOAD_FAST | 1,374,006 | 13.3% |
| POP_JUMP_IF_FALSE | 1,124,520 | 10.9% |
| LOAD_SUPER_ATTR_METHOD | 904,566 | 8.7% |
| RETURN_VALUE | 894,006 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,397,339 | 23.2% |
| LOAD_FAST_LOAD_FAST | 1,374,006 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,307,780 | 12.6% |
| CALL | 1,016,495 | 9.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 894,006 | 8.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 37.7% |
| RESUME_CHECK | 40 | 18.9% |
| POP_JUMP_IF_FALSE | 40 | 18.9% |
| POP_JUMP_IF_TRUE | 25 | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE | 11 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 104 | 49.1% |
| LOAD_ATTR | 52 | 24.5% |
| LOAD_GLOBAL_BUILTIN | 42 | 19.8% |
| COMPARE_OP | 7 | 3.3% |
| LOAD_FAST | 5 | 2.4% |


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
| TO_BOOL_INT | 3,962,358 | 27.7% |
| TO_BOOL_BOOL | 3,503,568 | 24.5% |
| COMPARE_OP_INT | 2,817,339 | 19.7% |
| CONTAINS_OP | 1,323,487 | 9.2% |
| COMPARE_OP_STR | 1,085,473 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,760,899 | 40.2% |
| RETURN_CONST | 2,368,820 | 16.5% |
| LOAD_FAST_LOAD_FAST | 1,124,520 | 7.8% |
| POP_TOP | 1,119,030 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,101,289 | 7.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 796,069 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 220,849 | 26.3% |
| NOP | 208,993 | 24.9% |
| LOAD_FAST | 192,657 | 22.9% |
| LOAD_FAST_CHECK | 181,155 | 21.5% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,801,090 | 47.9% |
| LOAD_ATTR | 816,573 | 21.7% |
| LOAD_ATTR_INSTANCE_VALUE | 741,297 | 19.7% |
| RETURN_VALUE | 346,936 | 9.2% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,525,510 | 40.5% |
| RETURN_CONST | 816,893 | 21.7% |
| ENTER_EXECUTOR | 745,646 | 19.8% |
| NOP | 380,755 | 10.1% |
| LOAD_CONST | 180,673 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,331,715 | 66.9% |
| TO_BOOL | 633,812 | 31.8% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,227 | 0.4% |
| COMPARE_OP_INT | 2,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 715,101 | 35.9% |
| LOAD_FAST_LOAD_FAST | 636,687 | 32.0% |
| RETURN_CONST | 503,387 | 25.3% |
| LOAD_GLOBAL_MODULE | 53,110 | 2.7% |
| RETURN_VALUE | 44,017 | 2.2% |


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
| POP_EXCEPT | 8,641 | 66.7% |
| POP_JUMP_IF_TRUE | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,321 | 50.0% |
| PUSH_EXC_INFO | 4,320 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,368,820 | 34.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,657,128 | 24.1% |
| POP_TOP | 1,427,366 | 20.7% |
| POP_JUMP_IF_NOT_NONE | 816,893 | 11.9% |
| POP_JUMP_IF_TRUE | 503,387 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,844,406 | 70.4% |
| EXIT_INIT_CHECK | 799,524 | 11.6% |
| INTERPRETER_EXIT | 668,091 | 9.7% |
| TO_BOOL_BOOL | 494,832 | 7.2% |
| STORE_FAST | 44,977 | 0.7% |


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
| LOAD_FAST | 37,923 | 57.1% |
| LOAD_FAST_LOAD_FAST | 14,880 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 19.5% |
| STORE_ATTR | 640 | 1.0% |
| SWAP | 14 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,647 | 13.0% |
| LOAD_CONST | 8,641 | 13.0% |
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
| YIELD_VALUE | 4,752,000 | 23.0% |
| CALL | 2,535,497 | 12.3% |
| COPY | 1,972,800 | 9.6% |
| RETURN_VALUE | 1,731,537 | 8.4% |
| BINARY_OP | 1,097,733 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,812,854 | 42.7% |
| JUMP_BACKWARD | 4,320,000 | 20.9% |
| NOP | 2,880,428 | 14.0% |
| COPY | 1,972,320 | 9.6% |
| JUMP_FORWARD | 802,091 | 3.9% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,610,455 | 44.4% |
| COPY | 820,320 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,202,334 | 33.1% |
| STORE_FAST | 816,000 | 22.5% |
| LOAD_FAST_LOAD_FAST | 780,601 | 21.5% |
| ENTER_EXECUTOR | 432,000 | 11.9% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 429,474 | 21.7% |
| LOAD_FAST_AND_CLEAR | 384,400 | 19.4% |
| BUILD_LIST | 384,400 | 19.4% |
| ENTER_EXECUTOR | 373,840 | 18.9% |
| LOAD_FAST | 201,795 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 429,467 | 21.7% |
| LOAD_CONST | 394,962 | 20.0% |
| STORE_FAST | 384,400 | 19.4% |
| BUILD_LIST | 384,400 | 19.4% |
| FOR_ITER_LIST | 373,840 | 18.9% |


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
| LOAD_FAST | 193,649 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 193,649 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 817,787 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 429,474 | 51.6% |
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
| CALL | 181,155 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 181,275 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,748 | 80.4% |
| LOAD_CONST | 44,017 | 17.8% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 242,765 | 98.3% |
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
| LOAD_GLOBAL_MODULE | 394,962 | 49.4% |
| LOAD_FAST | 379,602 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 425,202 | 53.2% |
| COPY_FREE_VARS | 374,322 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,000 | 83.1% |
| LOAD_CONST | 4,800 | 8.3% |
| BINARY_OP_ADD_INT | 4,320 | 7.5% |
| PUSH_NULL | 543 | 0.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,354 | 92.4% |
| POP_TOP | 4,320 | 7.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 61.6% |
| LOAD_FAST | 207,169 | 33.2% |
| LOAD_CONST | 11,040 | 1.8% |
| LOAD_GLOBAL_BUILTIN | 7,680 | 1.2% |
| CALL_LEN | 4,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 577,649 | 92.6% |
| GET_ITER | 28,800 | 4.6% |
| LOAD_FAST | 12,960 | 2.1% |
| CALL_BUILTIN_CLASS | 4,320 | 0.7% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 672,233 | 55.8% |
| LOAD_CONST | 298,753 | 24.8% |
| LOAD_FAST_LOAD_FAST | 129,628 | 10.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60,974 | 5.1% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 446,155 | 37.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 348,601 | 29.0% |
| TO_BOOL_BOOL | 291,553 | 24.2% |
| UNPACK_SEQUENCE_TUPLE | 60,974 | 5.1% |
| POP_TOP | 10,945 | 0.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 387,840 | 45.8% |
| BUILD_TUPLE | 384,000 | 45.3% |
| CALL | 48,562 | 5.7% |
| LOAD_FAST_CHECK | 12,412 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 785,760 | 92.7% |
| RETURN_VALUE | 60,974 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 906,966 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 906,966 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,944 | 93.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 7.0% |
| CALL | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,268 | 87.1% |
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
| BUILD_TUPLE | 193,167 | 95.7% |
| LOAD_FAST | 8,640 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 193,167 | 95.7% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,268,328 | 99.9% |
| LOAD_CONST | 960 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 254 | 0.0% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 894,006 | 70.4% |
| STORE_FAST | 374,583 | 29.5% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,038,145 | 93.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,386 | 6.6% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 477,236 | 42.9% |
| STORE_FAST | 432,000 | 38.8% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 60,974 | 5.5% |
| RETURN_VALUE | 38,744 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 662,972 | 92.0% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,607 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 684,579 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,136,487 | 46.1% |
| LOAD_FAST | 3,773,557 | 42.0% |
| LOAD_FAST_LOAD_FAST | 446,880 | 5.0% |
| LOAD_SUPER_ATTR_METHOD | 374,322 | 4.2% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,947,951 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 875,445 | 39.4% |
| ENTER_EXECUTOR | 567,684 | 25.6% |
| LOAD_ATTR_MODULE | 374,322 | 16.9% |
| LOAD_FAST | 255,567 | 11.5% |
| LOAD_CONST | 80,664 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,326,397 | 59.7% |
| COPY_FREE_VARS | 894,006 | 40.3% |


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
| LOAD_CONST | 1,543,397 | 54.7% |
| LOAD_ATTR_INSTANCE_VALUE | 812,140 | 28.8% |
| LOAD_FAST | 432,000 | 15.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,817,339 | 99.9% |
| POP_JUMP_IF_TRUE | 2,240 | 0.1% |
| COMPARE_OP | 71 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,065,849 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 11 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,085,473 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,227 | 0.7% |


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
| GET_ITER | 1,186,884 | 76.0% |
| SWAP | 373,840 | 23.9% |
| JUMP_BACKWARD | 799 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 560,968 | 35.9% |
| STORE_FAST_LOAD_FAST | 432,000 | 27.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 386,334 | 24.7% |
| LOAD_FAST | 181,155 | 11.6% |
| RETURN_CONST | 867 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 23,640 | 99.0% |
| JUMP_BACKWARD | 242 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,862 | 99.9% |
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
| LOAD_GLOBAL_MODULE | 60,974 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,242 | 81.9% |
| LOAD_FAST_CHECK | 12,412 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,564,585 | 90.4% |
| LOAD_FAST_LOAD_FAST | 1,307,780 | 7.1% |
| COPY | 429,467 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 18,140 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,192,806 | 22.9% |
| LOAD_FAST | 2,791,584 | 15.2% |
| TO_BOOL_BOOL | 1,367,052 | 7.5% |
| LOAD_ATTR | 1,360,189 | 7.4% |
| CONTAINS_OP | 1,323,480 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,776 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,948 | 39.8% |
| CALL | 111,442 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,386 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,192,806 | 87.2% |
| LOAD_FAST | 465,880 | 9.7% |
| LOAD_ATTR | 62,894 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,896,020 | 39.4% |
| CALL | 1,077,171 | 22.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,038,145 | 21.6% |
| LOAD_CONST | 548,668 | 11.4% |
| LOAD_FAST_LOAD_FAST | 224,936 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,373,079 | 69.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,007,615 | 13.0% |
| LOAD_FAST_LOAD_FAST | 894,006 | 11.6% |
| BINARY_SUBSCR | 432,000 | 5.6% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,136,487 | 53.4% |
| LOAD_FAST | 2,049,719 | 26.5% |
| CALL_PY_WITH_DEFAULTS | 875,445 | 11.3% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.6% |
| LOAD_CONST | 94,584 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,769,932 | 100.0% |
| LOAD_ATTR | 93 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,284,798 | 72.6% |
| CALL_PY_WITH_DEFAULTS | 374,322 | 21.1% |
| STORE_DEREF | 41,280 | 2.3% |
| LOAD_CONST | 26,400 | 1.5% |
| LOAD_FAST | 20,640 | 1.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 924,726 | 70.5% |
| LOAD_FAST_LOAD_FAST | 386,334 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,006 | 68.2% |
| UNARY_INVERT | 386,334 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 530,613 | 67.7% |
| LOAD_FAST | 231,269 | 29.5% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 774,522 | 98.8% |
| TO_BOOL_BOOL | 8,960 | 1.1% |
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
| RESUME_CHECK | 2,760,414 | 50.6% |
| LOAD_FAST | 927,126 | 17.0% |
| NOP | 552,350 | 10.1% |
| STORE_FAST | 546,670 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,684,744 | 49.3% |
| LOAD_DEREF | 1,350,408 | 24.8% |
| CALL_ISINSTANCE | 906,966 | 16.6% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 7.2% |
| LOAD_GLOBAL_MODULE | 36,960 | 0.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,163,792 | 27.0% |
| RESUME_CHECK | 2,173,007 | 18.6% |
| NOP | 1,359,632 | 11.6% |
| POP_JUMP_IF_FALSE | 1,101,289 | 9.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,087,381 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,875,185 | 24.5% |
| LOAD_FAST_LOAD_FAST | 2,012,845 | 17.2% |
| LOAD_ATTR_MODULE | 1,769,932 | 15.1% |
| LOAD_FAST | 1,624,217 | 13.9% |
| COMPARE_OP_STR | 1,065,849 | 9.1% |


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
| LOAD_FAST | 1,283,208 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 904,566 | 70.5% |
| CALL_PY_EXACT_ARGS | 374,322 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 8,947,951 | 32.5% |
| CACHE | 8,861,456 | 32.2% |
| FOR_ITER_GEN | 4,752,000 | 17.3% |
| COPY_FREE_VARS | 1,354,848 | 4.9% |
| CALL_PY_WITH_DEFAULTS | 1,326,397 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,532,594 | 56.5% |
| POP_TOP | 5,184,960 | 18.8% |
| LOAD_GLOBAL_BUILTIN | 2,760,414 | 10.0% |
| LOAD_GLOBAL_MODULE | 2,173,007 | 7.9% |
| NOP | 1,045,206 | 3.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,205,765 | 68.2% |
| LOAD_FAST_LOAD_FAST | 570,642 | 17.7% |
| SWAP | 429,467 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,657,128 | 51.3% |
| LOAD_FAST | 682,434 | 21.1% |
| LOAD_GLOBAL_MODULE | 533,682 | 16.5% |
| LOAD_CONST | 160,319 | 5.0% |
| LOAD_FAST_LOAD_FAST | 96,960 | 3.0% |


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
| LOAD_ATTR | 894,006 | 92.9% |
| LOAD_FAST | 33,973 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 896,786 | 93.2% |
| RETURN_CONST | 24,480 | 2.5% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.1% |
| LOAD_CONST | 20,640 | 2.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,367,052 | 27.1% |
| CALL_ISINSTANCE | 906,966 | 18.0% |
| RETURN_VALUE | 685,665 | 13.6% |
| CALL | 546,281 | 10.8% |
| LOAD_FAST | 538,417 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,503,568 | 69.4% |
| POP_JUMP_IF_TRUE | 1,331,715 | 26.4% |
| UNARY_NOT | 212,775 | 4.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,174,346 | 54.9% |
| LOAD_FAST | 894,006 | 22.6% |
| BINARY_OP | 894,006 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,962,358 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,962 | 92.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 415,122 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,846 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,446 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 60,974 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 60,974 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 27.0% |
| LOAD_FAST_CHECK | 432,000 | 26.7% |
| FOR_ITER_LIST | 386,334 | 23.9% |
| CALL_BUILTIN_FAST | 348,601 | 21.6% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,610,455 | 99.7% |
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
| STORE_FAST | 480 | 60.0% |
| COPY | 320 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 60.0% |
| POP_JUMP_IF_FALSE | 320 | 40.0% |


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
| specialization.deferred |       476017 | 45.6% |
|          hit |       568706 | 54.4% |

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
| specialization.deferred |        22567 | 2.3% |
|          hit |       962546 | 97.7% |

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
| specialization.deferred |      1184812 | 10.7% |
|          hit |      9836205 | 89.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2 | 0.2% |
| Failure | 1,048 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 326 | 31.1% |
| sequence | 222 | 21.2% |
| tuple | 220 | 21.0% |
| set | 200 | 19.1% |
| other | 80 | 7.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5356308 | 77.4% |
|          hit |      1563282 | 22.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 47 | 2.3% |
| Failure | 2,031 | 97.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,014 | 49.9% |
| or | 590 | 29.0% |
| remainder | 227 | 11.2% |
| add different types | 160 | 7.9% |
| add other | 40 | 2.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8752654 | 29.3% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21139204 | 70.7% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 128 | 1.4% |
| Failure | 9,020 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,524 | 28.0% |
| cfunc noargs | 1,792 | 19.9% |
| class no vectorcall | 1,264 | 14.0% |
| meth descr varargs keywords | 850 | 9.4% |
| class mutable | 412 | 4.6% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 332 | 3.7% |
| cfunc varargs | 320 | 3.5% |
| bound method | 286 | 3.2% |
| operator wrapper | 240 | 2.7% |
| meth descr method fastcall keywords | 200 | 2.2% |
| cmethod | 200 | 2.2% |
| wrong number arguments | 160 | 1.8% |
| method wrapper | 80 | 0.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       438494 | 10.0% |
| specialization.deopt |           71 | 0.0% |
|          hit |      3929558 | 89.9% |
|         miss |         4912 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 124 | 25.3% |
| Failure | 366 | 74.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 158 | 43.2% |
| different types | 128 | 35.0% |
| big int | 80 | 21.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 13.3% |
|          hit |      6355645 | 86.7% |

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
| specialization.deferred |      7398252 | 16.7% |
| specialization.deopt |         4193 | 0.0% |
|          hit |     36663934 | 82.8% |
|         miss |       230248 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,366 | 42.3% |
| Failure | 5,949 | 57.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,405 | 23.6% |
| not managed dict | 1,208 | 20.3% |
| shadowed | 1,187 | 20.0% |
| non overriding descriptor | 584 | 9.8% |
| class attr descriptor | 360 | 6.1% |
| metaclass attribute | 280 | 4.7% |
| class method obj | 280 | 4.7% |
| has managed dict | 240 | 4.0% |
| non object slot | 160 | 2.7% |
| class attr simple | 125 | 2.1% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           66 | 0.0% |
| specialization.deopt |           14 | 0.0% |
|          hit |     19438100 | 100.0% |
|         miss |         2390 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1350408 | 100.0% |


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
| specialization.deferred |        65769 | 1.9% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3160021 | 93.6% |
|         miss |       148120 | 4.4% |

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
|          hit |      2492709 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 222,486,345 | 55.2% |
| Not specialized | 51,724,867 | 12.8% |
| Specialized | 129,076,914 | 32.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 36,893,488,147,419,103,230 | 100.0% |
| CALL | 8,752,654 | 0.0% |
| LOAD_ATTR | 7,398,252 | 0.0% |
| BINARY_OP | 5,356,308 | 0.0% |
| TO_BOOL | 1,184,812 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| BINARY_SUBSCR | 476,017 | 0.0% |
| COMPARE_OP | 438,494 | 0.0% |
| STORE_ATTR | 65,769 | 0.0% |
| STORE_SUBSCR | 22,567 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,408 | 41.1% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 38.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,720 | 15.6% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| COMPARE_OP_INT | 4,912 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,390 | 0.6% |
| RESUME_CHECK | 2 | 0.0% |
| RESUME | 2 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,948,816 | 31.9% |
| Calls to Python functions inlined | 19,081,748 | 68.1% |
| Calls via PyEval_EvalFrame (total) | 8,948,816 | 31.9% |
| Calls via PyEval_EvalFrame (vector) | 8,510,576 | 30.4% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,510,576 | 30.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 476,862 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,631,208 | 84.3% |
| Frame objects created | 35,886 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,059,233 | 42.8% |
| Frees to freelist | 15,060,646 |  |
| Allocations | 20,096,256 | 57.2% |
| Allocations to 512 bytes | 19,884,133 | 56.6% |
| Allocations to 4 kbytes | 86,346 | 0.2% |
| Allocations over 4 kbytes | 125,777 | 0.4% |
| Frees | 21,253,997 |  |
| New values | 65,280 |  |
| Interpreter increfs | 161,743,087 | 71.3% |
| Interpreter decrefs | 175,532,650 | 67.9% |
| Increfs | 65,173,276 | 28.7% |
| Decrefs | 83,081,284 | 32.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,175,019 |  |
| Method cache misses | 21,352 |  |
| Method cache collisions | 36,587 |  |
| Method cache dunder hits | 8,596,008 |  |
| Method cache dunder misses | 15,235 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 17 | 384 | 114,954 |
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
| Optimization attempts | 335,747 |  |
| Traces created | 207 | 0.1% |
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
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
| <= 16 | 60 | 29.0% |
| <= 32 | 40 | 19.3% |
| <= 64 | 40 | 19.3% |
| <= 128 | 67 | 32.4% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 29.0% |
| <= 32 | 80 | 38.6% |
| <= 64 | 9 | 4.3% |
| <= 128 | 58 | 28.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER_GEN | 279,520 |
| FOR_ITER | 56,020 |
| CALL | 78 |
| LOAD_ATTR_PROPERTY | 40 |
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
Stats gathered on: 2023-10-11
