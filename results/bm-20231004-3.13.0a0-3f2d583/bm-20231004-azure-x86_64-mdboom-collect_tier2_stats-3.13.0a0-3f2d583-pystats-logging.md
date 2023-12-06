
# Pystats results

- benchmark: logging
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 409,131,300 | 22.5% | 22.5% |  |
| POP_JUMP_IF_FALSE | 125,337,780 | 6.9% | 29.4% |  |
| RESUME_CHECK | 117,350,940 | 6.5% | 35.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 116,145,000 | 6.4% | 42.3% | 1.1% |
| TO_BOOL_BOOL | 105,062,400 | 5.8% | 48.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 97,935,540 | 5.4% | 53.5% |  |
| LOAD_GLOBAL_MODULE | 83,559,300 | 4.6% | 58.1% |  |
| CALL_PY_EXACT_ARGS | 72,499,380 | 4.0% | 62.1% |  |
| RETURN_VALUE | 69,427,560 | 3.8% | 65.9% |  |
| CALL | 56,540,480 | 3.1% | 69.0% |  |
| POP_TOP | 56,525,520 | 3.1% | 72.1% |  |
| LOAD_CONST | 49,152,360 | 2.7% | 74.8% |  |
| RETURN_CONST | 49,152,180 | 2.7% | 77.5% |  |
| STORE_FAST | 48,538,680 | 2.7% | 80.2% |  |
| NOP | 46,694,580 | 2.6% | 82.8% |  |
| BINARY_SUBSCR_DICT | 41,779,200 | 2.3% | 85.1% |  |
| LOAD_FAST_LOAD_FAST | 34,959,420 | 1.9% | 87.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 27,033,600 | 1.5% | 88.5% |  |
| LOAD_ATTR_MODULE | 22,118,880 | 1.2% | 89.7% |  |
| LOAD_GLOBAL_BUILTIN | 14,745,960 | 0.8% | 90.5% |  |
| LOAD_ATTR | 12,291,660 | 0.7% | 91.2% |  |
| PUSH_NULL | 12,288,900 | 0.7% | 91.9% |  |
| TO_BOOL_NONE | 11,059,200 | 0.6% | 92.5% |  |
| COMPARE_OP_INT | 10,444,980 | 0.6% | 93.1% |  |
| POP_JUMP_IF_TRUE | 9,830,400 | 0.5% | 93.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 8,601,720 | 0.5% | 94.1% |  |
| BINARY_OP | 6,760,260 | 0.4% | 94.5% |  |
| ENTER_EXECUTOR | 6,512,640 | 0.4% | 94.8% |  |
| CALL_ISINSTANCE | 5,529,600 | 0.3% | 95.1% |  |
| TO_BOOL_ALWAYS_TRUE | 4,915,200 | 0.3% | 95.4% |  |
| JUMP_FORWARD | 4,915,200 | 0.3% | 95.7% |  |
| BINARY_SLICE | 4,915,200 | 0.3% | 95.9% |  |
| BINARY_OP_ADD_INT | 4,915,200 | 0.3% | 96.2% |  |
| CALL_BUILTIN_FAST | 4,300,800 | 0.2% | 96.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,686,760 | 0.2% | 96.6% |  |
| GET_ITER | 3,686,580 | 0.2% | 96.9% |  |
| POP_JUMP_IF_NONE | 3,686,400 | 0.2% | 97.1% |  |
| FOR_ITER_LIST | 3,686,400 | 0.2% | 97.3% |  |
| COPY | 3,686,400 | 0.2% | 97.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,686,400 | 0.2% | 97.7% |  |
| BUILD_TUPLE | 3,686,400 | 0.2% | 97.9% |  |
| INTERPRETER_EXIT | 3,072,000 | 0.2% | 98.0% |  |
| TO_BOOL | 2,458,240 | 0.1% | 98.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 2,458,140 | 0.1% | 98.3% |  |
| STORE_FAST_STORE_FAST | 2,457,600 | 0.1% | 98.4% |  |
| POP_JUMP_IF_NOT_NONE | 2,457,600 | 0.1% | 98.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,457,600 | 0.1% | 98.7% |  |
| COMPARE_OP_STR | 2,457,600 | 0.1% | 98.8% |  |
| BEFORE_WITH | 2,457,600 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,843,200 | 0.1% | 99.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,252,620 | 0.1% | 99.2% | 100.0% |
| CALL_FUNCTION_EX | 1,229,160 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_FLOAT | 1,228,980 | 0.1% | 99.3% |  |
| UNPACK_SEQUENCE_TUPLE | 1,228,800 | 0.1% | 99.4% |  |
| TO_BOOL_STR | 1,228,800 | 0.1% | 99.4% |  |
| LOAD_ATTR_PROPERTY | 1,228,800 | 0.1% | 99.5% |  |
| DICT_MERGE | 1,228,800 | 0.1% | 99.6% |  |
| CONTAINS_OP | 1,228,800 | 0.1% | 99.6% |  |
| CALL_STR_1 | 1,228,800 | 0.1% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,228,800 | 0.1% | 99.8% |  |
| BUILD_MAP | 1,228,800 | 0.1% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 1,228,800 | 0.1% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 1,228,800 | 0.1% | 100.0% |  |
| CALL_LEN | 614,580 | 0.0% | 100.0% |  |
| LOAD_DEREF | 540 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 500 | 0.0% | 100.0% |  |
| LIST_EXTEND | 180 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 180 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 180 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 180 | 0.0% | 100.0% |  |
| BUILD_LIST | 180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 120 | 0.0% | 100.0% |  |
| COMPARE_OP | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 115,507,200 | 6.4% | 6.4% |
| RESUME_CHECK LOAD_FAST | 98,304,180 | 5.4% | 11.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 97,689,600 | 5.4% | 17.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 95,477,940 | 5.3% | 22.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 72,499,380 | 4.0% | 26.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 50,688,120 | 2.8% | 29.2% |
| RETURN_CONST POP_TOP | 45,465,780 | 2.5% | 31.7% |
| RETURN_VALUE TO_BOOL_BOOL | 44,236,800 | 2.4% | 34.1% |
| NOP LOAD_FAST | 44,236,800 | 2.4% | 36.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 43,008,000 | 2.4% | 38.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 43,008,000 | 2.4% | 41.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 43,008,000 | 2.4% | 43.7% |
| LOAD_FAST CALL | 42,086,680 | 2.3% | 46.0% |
| POP_JUMP_IF_FALSE NOP | 41,779,200 | 2.3% | 48.3% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 41,779,200 | 2.3% | 50.6% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 41,779,200 | 2.3% | 52.9% |
| POP_TOP LOAD_FAST | 41,410,740 | 2.3% | 55.2% |
| LOAD_FAST BINARY_SUBSCR_DICT | 40,550,400 | 2.2% | 57.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 40,550,400 | 2.2% | 59.7% |
| CALL RESUME_CHECK | 40,550,400 | 2.2% | 61.9% |
| STORE_FAST LOAD_FAST | 30,106,080 | 1.7% | 63.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 25,190,580 | 1.4% | 64.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 19,660,920 | 1.1% | 66.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 17,817,900 | 1.0% | 67.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 14,745,600 | 0.8% | 67.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 12,288,000 | 0.7% | 68.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 11,673,720 | 0.6% | 69.1% |
| LOAD_FAST LOAD_CONST | 11,673,720 | 0.6% | 69.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 11,059,680 | 0.6% | 70.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,059,560 | 0.6% | 71.0% |
| LOAD_FAST LOAD_ATTR | 11,059,380 | 0.6% | 71.6% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 11,059,200 | 0.6% | 72.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 9,830,400 | 0.5% | 72.8% |
| LOAD_FAST RETURN_VALUE | 8,601,780 | 0.5% | 73.2% |
| RETURN_VALUE STORE_FAST | 8,601,600 | 0.5% | 73.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 7,987,380 | 0.4% | 74.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 7,372,800 | 0.4% | 74.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 7,372,800 | 0.4% | 75.0% |
| LOAD_CONST STORE_FAST | 7,372,800 | 0.4% | 75.4% |
| LOAD_CONST LOAD_FAST | 7,372,800 | 0.4% | 75.8% |
| LOAD_CONST COMPARE_OP_INT | 6,758,440 | 0.4% | 76.1% |
| RETURN_VALUE RETURN_VALUE | 6,144,180 | 0.3% | 76.5% |
| POP_TOP RETURN_CONST | 6,144,180 | 0.3% | 76.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 6,144,000 | 0.3% | 77.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 6,144,000 | 0.3% | 77.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 5,529,600 | 0.3% | 77.8% |
| POP_TOP ENTER_EXECUTOR | 5,283,840 | 0.3% | 78.1% |
| CALL STORE_FAST | 4,915,380 | 0.3% | 78.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 4,915,360 | 0.3% | 78.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 4,915,200 | 0.3% | 78.9% |
| RETURN_VALUE LOAD_FAST | 4,915,200 | 0.3% | 79.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 4,915,200 | 0.3% | 79.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 4,915,200 | 0.3% | 79.7% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 4,915,200 | 0.3% | 80.0% |
| LOAD_FAST TO_BOOL_NONE | 4,915,200 | 0.3% | 80.3% |
| LOAD_FAST STORE_FAST | 4,915,200 | 0.3% | 80.5% |
| LOAD_CONST LOAD_CONST | 4,915,200 | 0.3% | 80.8% |
| LOAD_CONST BINARY_OP_ADD_INT | 4,915,200 | 0.3% | 81.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,915,200 | 0.3% | 81.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 4,915,200 | 0.3% | 81.6% |
| LOAD_ATTR_MODULE LOAD_ATTR_MODULE | 4,300,800 | 0.2% | 81.8% |
| ENTER_EXECUTOR CALL | 4,054,860 | 0.2% | 82.1% |
| PUSH_NULL CALL | 3,686,940 | 0.2% | 82.3% |
| PUSH_NULL LOAD_FAST | 3,686,760 | 0.2% | 82.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 3,686,580 | 0.2% | 82.7% |
| LOAD_CONST BINARY_OP | 3,686,440 | 0.2% | 82.9% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 3,686,400 | 0.2% | 83.1% |
| STORE_FAST LOAD_CONST | 3,686,400 | 0.2% | 83.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 3,686,400 | 0.2% | 83.5% |
| RESUME_CHECK NOP | 3,686,400 | 0.2% | 83.7% |
| POP_TOP LOAD_CONST | 3,686,400 | 0.2% | 83.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 3,686,400 | 0.2% | 84.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,686,400 | 0.2% | 84.3% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 3,686,400 | 0.2% | 84.5% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 3,686,400 | 0.2% | 84.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 3,686,400 | 0.2% | 84.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,686,400 | 0.2% | 85.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 3,686,400 | 0.2% | 85.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 3,686,400 | 0.2% | 85.5% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,686,400 | 0.2% | 85.7% |
| LOAD_CONST CALL_BUILTIN_FAST | 3,686,400 | 0.2% | 85.9% |
| LOAD_ATTR_MODULE LOAD_FAST | 3,686,400 | 0.2% | 86.1% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 3,686,400 | 0.2% | 86.3% |
| LOAD_ATTR STORE_FAST | 3,686,400 | 0.2% | 86.5% |
| LOAD_ATTR LOAD_FAST | 3,686,400 | 0.2% | 86.7% |
| GET_ITER FOR_ITER_LIST | 3,686,400 | 0.2% | 86.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 3,686,400 | 0.2% | 87.1% |
| CALL LOAD_CONST | 3,686,400 | 0.2% | 87.3% |
| BINARY_OP_ADD_INT STORE_FAST | 3,686,400 | 0.2% | 87.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 3,072,000 | 0.2% | 87.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 3,072,000 | 0.2% | 87.9% |
| CACHE RESUME_CHECK | 3,072,000 | 0.2% | 88.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 2,457,840 | 0.1% | 88.2% |
| CALL POP_TOP | 2,457,780 | 0.1% | 88.3% |
| CALL LOAD_FAST | 2,457,780 | 0.1% | 88.5% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 2,457,720 | 0.1% | 88.6% |
| LOAD_CONST CALL | 2,457,660 | 0.1% | 88.7% |
| TO_BOOL POP_JUMP_IF_FALSE | 2,457,600 | 0.1% | 88.9% |
| STORE_ATTR_INSTANCE_VALUE JUMP_FORWARD | 2,457,600 | 0.1% | 89.0% |
| RETURN_CONST INTERPRETER_EXIT | 2,457,600 | 0.1% | 89.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,457,600 | 50.0% |
| LOAD_FAST | 1,228,800 | 25.0% |
| BINARY_OP_ADD_INT | 1,228,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,228,800 | 25.0% |
| LOAD_FAST_LOAD_FAST | 1,228,800 | 25.0% |
| LOAD_FAST | 1,228,800 | 25.0% |
| BUILD_TUPLE | 1,228,800 | 25.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,072,000 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,457,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,457,600 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,686,400 | 100.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,686,400 | 100.0% |
| FOR_ITER_RANGE | 180 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,457,600 | 80.0% |
| RETURN_VALUE | 614,400 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 41,779,200 | 89.5% |
| RESUME_CHECK | 3,686,400 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,228,800 | 2.6% |
| POP_TOP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,236,800 | 94.7% |
| LOAD_GLOBAL_MODULE | 2,457,600 | 5.3% |
| LOAD_DEREF | 180 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 45,465,780 | 80.4% |
| CALL | 2,457,780 | 4.3% |
| BEFORE_WITH | 2,457,600 | 4.3% |
| RETURN_VALUE | 1,228,800 | 2.2% |
| ENTER_EXECUTOR | 1,228,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,410,740 | 73.3% |
| RETURN_CONST | 6,144,180 | 10.9% |
| ENTER_EXECUTOR | 5,283,840 | 9.3% |
| LOAD_CONST | 3,686,400 | 6.5% |
| NOP | 180 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 11,059,680 | 90.0% |
| LOAD_ATTR | 1,228,860 | 10.0% |
| LOAD_DEREF | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,686,940 | 30.0% |
| LOAD_FAST | 3,686,760 | 30.0% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 10.0% |
| LOAD_FAST_LOAD_FAST | 1,228,800 | 10.0% |
| LOAD_CONST | 1,228,800 | 10.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 41,779,200 | 60.2% |
| LOAD_FAST | 8,601,780 | 12.4% |
| RETURN_VALUE | 6,144,180 | 8.8% |
| BUILD_TUPLE | 2,457,600 | 3.5% |
| CALL_BUILTIN_FAST | 1,843,200 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 44,236,800 | 63.7% |
| STORE_FAST | 8,601,600 | 12.4% |
| RETURN_VALUE | 6,144,180 | 8.8% |
| LOAD_FAST | 4,915,200 | 7.1% |
| UNPACK_SEQUENCE_TUPLE | 1,228,800 | 1.8% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,228,800 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 50.0% |
| TO_BOOL | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,457,600 | 100.0% |
| TO_BOOL | 640 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,686,440 | 54.5% |
| LOAD_FAST | 1,228,860 | 18.2% |
| CALL | 1,228,800 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 614,400 | 9.1% |
| BINARY_OP | 1,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,457,600 | 36.4% |
| RETURN_VALUE | 1,228,800 | 18.2% |
| LOAD_CONST | 1,228,800 | 18.2% |
| CALL | 1,228,800 | 18.2% |
| STORE_FAST | 614,400 | 9.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 180 | 100.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,228,800 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,228,800 | 33.3% |
| LOAD_FAST | 1,228,800 | 33.3% |
| BINARY_SLICE | 1,228,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,457,600 | 66.7% |
| BUILD_MAP | 1,228,800 | 33.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,086,680 | 74.4% |
| ENTER_EXECUTOR | 4,054,860 | 7.2% |
| PUSH_NULL | 3,686,940 | 6.5% |
| LOAD_CONST | 2,457,660 | 4.3% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40,550,400 | 71.7% |
| STORE_FAST | 4,915,380 | 8.7% |
| LOAD_CONST | 3,686,400 | 6.5% |
| POP_TOP | 2,457,780 | 4.3% |
| LOAD_FAST | 2,457,780 | 4.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 1,228,800 | 100.0% |
| LOAD_FAST | 180 | 0.0% |
| CALL_INTRINSIC_1 | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,228,800 | 100.0% |
| RESUME_CHECK | 180 | 0.0% |
| COPY_FREE_VARS | 180 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 180 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 40 | 66.7% |
| LOAD_CONST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 60 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,228,800 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 33.3% |
| CONTAINS_OP | 1,228,800 | 33.3% |
| COMPARE_OP_STR | 1,228,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,457,600 | 66.7% |
| STORE_FAST | 1,228,800 | 33.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,228,800 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,283,840 | 81.1% |
| POP_JUMP_IF_FALSE | 1,228,800 | 18.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,054,860 | 62.3% |
| POP_TOP | 1,228,800 | 18.9% |
| LOAD_FAST | 1,228,800 | 18.9% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,457,600 | 50.0% |
| STORE_FAST_STORE_FAST | 1,228,800 | 25.0% |
| STORE_FAST | 1,228,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,457,600 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 25.0% |
| LOAD_CONST | 1,228,800 | 25.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 180 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,059,380 | 90.0% |
| LOAD_ATTR | 1,232,000 | 10.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,686,400 | 30.0% |
| LOAD_FAST | 3,686,400 | 30.0% |
| LOAD_ATTR | 1,232,000 | 10.0% |
| PUSH_NULL | 1,228,860 | 10.0% |
| TO_BOOL_BOOL | 1,228,800 | 10.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,673,720 | 23.8% |
| LOAD_CONST | 4,915,200 | 10.0% |
| STORE_FAST | 3,686,400 | 7.5% |
| POP_TOP | 3,686,400 | 7.5% |
| LOAD_FAST_LOAD_FAST | 3,686,400 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,372,800 | 15.0% |
| LOAD_FAST | 7,372,800 | 15.0% |
| COMPARE_OP_INT | 6,758,440 | 13.7% |
| LOAD_CONST | 4,915,200 | 10.0% |
| BINARY_OP_ADD_INT | 4,915,200 | 10.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 33.3% |
| NOP | 180 | 33.3% |
| BUILD_LIST | 180 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 360 | 66.7% |
| LIST_EXTEND | 180 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 98,304,180 | 24.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 50,688,120 | 12.4% |
| NOP | 44,236,800 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 43,008,000 | 10.5% |
| POP_TOP | 41,410,740 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 115,507,200 | 28.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 95,477,940 | 23.3% |
| CALL | 42,086,680 | 10.3% |
| BINARY_SUBSCR_DICT | 40,550,400 | 9.9% |
| CALL_PY_EXACT_ARGS | 19,660,920 | 4.8% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 9,830,400 | 28.1% |
| LOAD_FAST_LOAD_FAST | 6,144,000 | 17.6% |
| STORE_FAST | 4,915,200 | 14.1% |
| POP_JUMP_IF_FALSE | 3,072,000 | 8.8% |
| LOAD_GLOBAL_MODULE | 3,072,000 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,288,000 | 35.1% |
| LOAD_FAST_LOAD_FAST | 6,144,000 | 17.6% |
| LOAD_FAST | 3,686,400 | 10.5% |
| LOAD_CONST | 3,686,400 | 10.5% |
| COMPARE_OP_INT | 2,457,600 | 7.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 40.0% |
| RETURN_VALUE | 120 | 24.0% |
| RESUME_CHECK | 60 | 12.0% |
| POP_TOP | 60 | 12.0% |
| ENTER_EXECUTOR | 60 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 320 | 64.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 24.0% |
| LOAD_ATTR | 60 | 12.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 97,689,600 | 77.9% |
| TO_BOOL_NONE | 11,059,200 | 8.8% |
| COMPARE_OP_INT | 7,987,380 | 6.4% |
| TO_BOOL_ALWAYS_TRUE | 3,686,400 | 2.9% |
| TO_BOOL | 2,457,600 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 43,008,000 | 34.3% |
| NOP | 41,779,200 | 33.3% |
| LOAD_FAST | 25,190,580 | 20.1% |
| LOAD_GLOBAL_MODULE | 4,915,200 | 3.9% |
| LOAD_GLOBAL_BUILTIN | 3,686,400 | 2.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,686,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,457,600 | 66.7% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 33.3% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,457,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,457,600 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,372,800 | 75.0% |
| TO_BOOL_ALWAYS_TRUE | 1,228,800 | 12.5% |
| COMPARE_OP_INT | 1,228,800 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,915,200 | 50.0% |
| LOAD_CONST | 2,457,600 | 25.0% |
| RETURN_VALUE | 1,228,800 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 1,228,800 | 12.5% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 43,008,000 | 87.5% |
| POP_TOP | 6,144,180 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 45,465,780 | 92.5% |
| INTERPRETER_EXIT | 2,457,600 | 5.0% |
| STORE_FAST | 1,228,800 | 2.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,601,600 | 17.7% |
| LOAD_CONST | 7,372,800 | 15.2% |
| CALL | 4,915,380 | 10.1% |
| LOAD_FAST | 4,915,200 | 10.1% |
| LOAD_ATTR | 3,686,400 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,106,080 | 62.0% |
| LOAD_GLOBAL_MODULE | 4,915,360 | 10.1% |
| LOAD_FAST_LOAD_FAST | 4,915,200 | 10.1% |
| LOAD_CONST | 3,686,400 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 2,457,840 | 5.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,228,800 | 50.0% |
| STORE_FAST_STORE_FAST | 1,228,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,228,800 | 50.0% |
| JUMP_FORWARD | 1,228,800 | 50.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,915,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,686,400 | 75.0% |
| BINARY_SLICE | 1,228,800 | 25.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 1,228,800 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 66.7% |
| BINARY_OP | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 80 | 66.7% |
| COMPARE_OP | 40 | 33.3% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,228,800 | 100.0% |
| LOAD_FAST | 120 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,228,800 | 100.0% |
| STORE_FAST | 180 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,228,800 | 100.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,550,400 | 97.1% |
| CALL | 1,228,800 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 41,779,200 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,843,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,228,800 | 66.7% |
| LOAD_GLOBAL_MODULE | 614,400 | 33.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| CALL | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,686,400 | 85.7% |
| LOAD_FAST_LOAD_FAST | 614,400 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,457,600 | 57.1% |
| RETURN_VALUE | 1,843,200 | 42.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,686,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,457,600 | 66.7% |
| RETURN_VALUE | 1,228,800 | 33.3% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,457,600 | 44.4% |
| LOAD_GLOBAL_BUILTIN | 2,457,600 | 44.4% |
| LOAD_ATTR_MODULE | 614,400 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,529,600 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 614,480 | 100.0% |
| CALL | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 614,460 | 100.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,457,720 | 66.7% |
| LOAD_FAST | 1,228,800 | 33.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 120 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,686,400 | 100.0% |
| POP_TOP | 360 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_LAZY_DICT | 1,228,920 | 98.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 23,640 | 1.9% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,228,800 | 98.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 23,640 | 1.9% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |
| CALL_LEN | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,228,800 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,779,200 | 57.6% |
| LOAD_FAST | 19,660,920 | 27.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,915,200 | 6.8% |
| LOAD_FAST_LOAD_FAST | 2,457,600 | 3.4% |
| PUSH_NULL | 1,228,800 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 72,499,380 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,228,800 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,758,440 | 64.7% |
| LOAD_FAST_LOAD_FAST | 2,457,600 | 23.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 11.8% |
| BINARY_OP_MULTIPLY_INT | 80 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,987,380 | 76.5% |
| RETURN_VALUE | 1,228,800 | 11.8% |
| POP_JUMP_IF_TRUE | 1,228,800 | 11.8% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,228,800 | 50.0% |
| LOAD_FAST | 1,228,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,228,800 | 50.0% |
| COPY | 1,228,800 | 50.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,686,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,457,600 | 66.7% |
| STORE_FAST | 1,228,800 | 33.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,507,200 | 99.5% |
| LOAD_FAST_LOAD_FAST | 614,400 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 23,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 43,008,000 | 37.0% |
| LOAD_FAST | 43,008,000 | 37.0% |
| TO_BOOL_NONE | 4,915,200 | 4.2% |
| GET_ITER | 3,686,400 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,457,600 | 2.1% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,229,160 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 50.0% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,228,920 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,228,800 | 50.0% |
| LOAD_CONST | 180 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 0.0% |
| CALL | 120 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,686,400 | 42.9% |
| LOAD_ATTR_MODULE | 2,457,600 | 28.6% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 14.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 14.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,144,000 | 71.4% |
| LOAD_CONST | 2,457,600 | 28.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 80 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,477,940 | 97.5% |
| LOAD_ATTR_INSTANCE_VALUE | 2,457,600 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,688,120 | 51.8% |
| LOAD_GLOBAL_MODULE | 40,550,400 | 41.4% |
| CALL_PY_EXACT_ARGS | 4,915,200 | 5.0% |
| LOAD_FAST_LOAD_FAST | 1,781,820 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 17,817,900 | 80.6% |
| LOAD_ATTR_MODULE | 4,300,800 | 19.4% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 11,059,680 | 50.0% |
| LOAD_ATTR_MODULE | 4,300,800 | 19.4% |
| LOAD_FAST | 3,686,400 | 16.7% |
| LOAD_ATTR_METHOD_NO_DICT | 2,457,600 | 11.1% |
| CALL_ISINSTANCE | 614,400 | 2.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,228,800 | 50.0% |
| LOAD_FAST | 1,228,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,228,800 | 50.0% |
| BINARY_OP_ADD_UNICODE | 1,228,800 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,228,800 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,686,400 | 25.0% |
| LOAD_FAST | 3,686,400 | 25.0% |
| STORE_FAST | 2,457,840 | 16.7% |
| RESUME_CHECK | 2,457,600 | 16.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,228,800 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,059,560 | 75.0% |
| CALL_ISINSTANCE | 2,457,600 | 16.7% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 8.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 40,550,400 | 48.5% |
| RESUME_CHECK | 11,673,720 | 14.0% |
| STORE_ATTR_INSTANCE_VALUE | 7,372,800 | 8.8% |
| STORE_FAST | 4,915,360 | 5.9% |
| POP_JUMP_IF_FALSE | 4,915,200 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 41,779,200 | 50.0% |
| LOAD_ATTR_MODULE | 17,817,900 | 21.3% |
| TO_BOOL_BOOL | 4,915,200 | 5.9% |
| LOAD_FAST | 3,686,580 | 4.4% |
| LOAD_FAST_LOAD_FAST | 3,072,000 | 3.7% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 72,499,380 | 61.8% |
| CALL | 40,550,400 | 34.6% |
| CACHE | 3,072,000 | 2.6% |
| LOAD_ATTR_PROPERTY | 1,228,800 | 1.0% |
| COPY_FREE_VARS | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,304,180 | 83.8% |
| LOAD_GLOBAL_MODULE | 11,673,720 | 9.9% |
| NOP | 3,686,400 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 2,457,600 | 2.1% |
| LOAD_CONST | 1,228,800 | 1.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,745,600 | 54.5% |
| LOAD_FAST_LOAD_FAST | 12,288,000 | 45.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,830,400 | 36.4% |
| LOAD_GLOBAL_MODULE | 7,372,800 | 27.3% |
| LOAD_FAST | 3,686,400 | 13.6% |
| JUMP_FORWARD | 2,457,600 | 9.1% |
| NOP | 1,228,800 | 4.5% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,686,400 | 75.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,686,400 | 75.0% |
| POP_JUMP_IF_TRUE | 1,228,800 | 25.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 44,236,800 | 42.1% |
| LOAD_ATTR_INSTANCE_VALUE | 43,008,000 | 40.9% |
| CALL_ISINSTANCE | 5,529,600 | 5.3% |
| LOAD_GLOBAL_MODULE | 4,915,200 | 4.7% |
| COPY | 2,457,600 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 97,689,600 | 93.0% |
| POP_JUMP_IF_TRUE | 7,372,800 | 7.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,915,200 | 44.4% |
| LOAD_ATTR_INSTANCE_VALUE | 4,915,200 | 44.4% |
| STORE_FAST | 1,228,800 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,059,200 | 100.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,228,800 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,228,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,228,800 | 100.0% |


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
|          hit |     43622400 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2457600 | 2.0% |
|          hit |    122265600 | 98.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 640 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 640 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6758400 | 44.0% |
|          hit |      8601900 | 56.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 5.4% |
| Failure | 1,760 | 94.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 640 | 36.4% |
| remainder | 480 | 27.3% |
| subtract different types | 320 | 18.2% |
| add different types | 320 | 18.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     56525340 | 37.5% |
| specialization.deopt |        23640 | 0.0% |
|          hit |     92775600 | 61.6% |
|         miss |      1252440 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 24,040 | 62.0% |
| Failure | 14,740 | 38.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 10,400 | 70.6% |
| cfunc noargs | 1,460 | 9.9% |
| meth descr varargs | 1,280 | 8.7% |
| class no vectorcall | 640 | 4.3% |
| cfunc varargs | 640 | 4.3% |
| init not simple | 320 | 2.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     12902580 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3686580 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     12288060 | 4.7% |
| specialization.deopt |        23400 | 0.0% |
|          hit |    249705200 | 94.9% |
|         miss |      1240480 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 23,800 | 88.1% |
| Failure | 3,200 | 11.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 1,280 | 40.0% |
| non object slot | 960 | 30.0% |
| class attr descriptor | 320 | 10.0% |
| shadowed | 320 | 10.0% |
| method | 320 | 10.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 0.0% |
|          hit |     98305260 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 100.0% |
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
|          hit |     27033600 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1228800 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 811,261,740 | 44.7% |
| Not specialized | 226,771,500 | 12.5% |
| Specialized | 777,478,460 | 42.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 56,525,340 | 72.4% |
| LOAD_ATTR | 12,288,060 | 15.7% |
| BINARY_OP | 6,758,400 | 8.7% |
| TO_BOOL | 2,457,600 | 3.1% |
| LOAD_GLOBAL | 60 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,252,440 | 50.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,240,480 | 49.8% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 3,072,000 | 2.6% |
| Calls to Python functions inlined | 114,278,940 | 97.4% |
| Calls via PyEval_EvalFrame (total) | 3,072,000 | 2.6% |
| Calls via PyEval_EvalFrame (vector) | 3,072,000 | 2.6% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 3,072,000 | 2.6% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 122,266,140 | 104.2% |
| Frame objects created | 3,686,520 | 3.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 66,970,260 | 64.5% |
| Frees to freelist | 66,970,260 |  |
| Allocations | 36,868,301 | 35.5% |
| Allocations to 512 bytes | 36,868,181 | 35.5% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 36,868,281 |  |
| New values | 1,228,800 |  |
| Interpreter increfs | 753,089,060 | 84.9% |
| Interpreter decrefs | 859,848,581 | 86.6% |
| Increfs | 133,866,822 | 15.1% |
| Decrefs | 133,403,142 | 13.4% |
| Materialize dict (on request) | 1,228,800 | 100.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 1,228,800 | 100.0% |
| Method cache hits | 24,590,831 |  |
| Method cache misses | 9 |  |
| Method cache collisions | 9 |  |
| Method cache dunder hits | 11,059,840 |  |
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
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 6,512,640 |  |
| Uops executed | 262,408,740 | 40 |
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
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,228,980 | 18.9% |
| <= 16 | 4,054,860 | 62.3% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 0 | 0.0% |
| <= 256 | 1,228,800 | 18.9% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 69,918,540 | 26.6% | 26.6% |
| LOAD_FAST | 26,603,100 | 10.1% | 36.8% |
| STORE_FAST | 11,427,660 | 4.4% | 41.1% |
| _LOAD_GLOBAL_MODULE | 9,830,400 | 3.7% | 44.9% |
| _GUARD_GLOBALS_VERSION | 9,830,400 | 3.7% | 48.6% |
| _SAVE_CURRENT_IP | 8,601,600 | 3.3% | 51.9% |
| _POP_JUMP_IF_TRUE | 7,741,440 | 3.0% | 54.9% |
| _LOAD_ATTR_MODULE | 7,372,800 | 2.8% | 57.7% |
| _CHECK_ATTR_MODULE | 7,372,800 | 2.8% | 60.5% |
| LOAD_ATTR | 7,372,800 | 2.8% | 63.3% |
| _EXIT_TRACE | 6,512,640 | 2.5% | 65.8% |
| _PUSH_FRAME | 4,915,200 | 1.9% | 67.6% |
| _POP_JUMP_IF_FALSE | 4,915,200 | 1.9% | 69.5% |
| _INIT_CALL_PY_EXACT_ARGS | 4,915,200 | 1.9% | 71.4% |
| _CHECK_STACK_SPACE | 4,915,200 | 1.9% | 73.3% |
| _CHECK_PEP_523 | 4,915,200 | 1.9% | 75.1% |
| _CHECK_FUNCTION_EXACT_ARGS | 4,915,200 | 1.9% | 77.0% |
| RESUME_CHECK | 4,915,200 | 1.9% | 78.9% |
| _ITER_CHECK_RANGE | 4,055,040 | 1.5% | 80.4% |
| _IS_ITER_EXHAUSTED_RANGE | 4,055,040 | 1.5% | 82.0% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 4,054,860 | 1.5% | 83.5% |
| _ITER_NEXT_RANGE | 4,054,860 | 1.5% | 85.1% |
| _GUARD_TYPE_VERSION | 4,054,860 | 1.5% | 86.6% |
| _GUARD_KEYS_VERSION | 4,054,860 | 1.5% | 88.2% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 4,054,860 | 1.5% | 89.7% |
| _POP_FRAME | 3,686,400 | 1.4% | 91.1% |
| TO_BOOL_BOOL | 3,686,400 | 1.4% | 92.5% |
| _IS_NONE | 2,457,600 | 0.9% | 93.4% |
| PUSH_NULL | 2,457,600 | 0.9% | 94.4% |
| COPY | 2,457,600 | 0.9% | 95.3% |
| COMPARE_OP_STR | 2,457,600 | 0.9% | 96.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,457,600 | 0.9% | 97.2% |
| POP_TOP | 1,228,980 | 0.5% | 97.7% |
| _JUMP_TO_TOP | 1,228,800 | 0.5% | 98.1% |
| _ITER_CHECK_LIST | 1,228,800 | 0.5% | 98.6% |
| _IS_ITER_EXHAUSTED_LIST | 1,228,800 | 0.5% | 99.1% |
| LOAD_CONST | 1,228,800 | 0.5% | 99.5% |
| COMPARE_OP_INT | 1,228,800 | 0.5% | 100.0% |


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
| Number of data files | 60 |


</details>

---
Stats gathered on: 2023-10-04
