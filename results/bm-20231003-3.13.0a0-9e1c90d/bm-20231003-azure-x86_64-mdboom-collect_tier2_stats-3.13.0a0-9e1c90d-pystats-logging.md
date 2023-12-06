
# Pystats results

- benchmark: logging
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 434,014,380 | 22.4% | 22.4% |  |
| POP_JUMP_IF_FALSE | 131,481,780 | 6.8% | 29.2% |  |
| RESUME_CHECK | 124,723,740 | 6.4% | 35.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 123,517,800 | 6.4% | 42.0% | 1.0% |
| TO_BOOL_BOOL | 108,748,800 | 5.6% | 47.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 106,905,600 | 5.5% | 53.2% |  |
| LOAD_GLOBAL_MODULE | 88,474,500 | 4.6% | 57.7% |  |
| CALL_PY_EXACT_ARGS | 79,872,180 | 4.1% | 61.8% |  |
| RETURN_VALUE | 73,113,960 | 3.8% | 65.6% |  |
| POP_TOP | 61,440,720 | 3.2% | 68.8% |  |
| CALL | 56,540,440 | 2.9% | 71.7% |  |
| RETURN_CONST | 54,067,380 | 2.8% | 74.5% |  |
| STORE_FAST | 50,996,280 | 2.6% | 77.1% |  |
| NOP | 49,152,180 | 2.5% | 79.7% |  |
| LOAD_CONST | 43,008,360 | 2.2% | 81.9% |  |
| BINARY_SUBSCR_DICT | 41,779,200 | 2.2% | 84.1% |  |
| LOAD_FAST_LOAD_FAST | 35,020,800 | 1.8% | 85.9% |  |
| LOAD_ATTR_MODULE | 29,491,680 | 1.5% | 87.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 27,033,600 | 1.4% | 88.8% |  |
| LOAD_ATTR | 17,208,060 | 0.9% | 89.7% |  |
| PUSH_NULL | 14,746,500 | 0.8% | 90.4% |  |
| LOAD_GLOBAL_BUILTIN | 14,745,960 | 0.8% | 91.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 13,516,920 | 0.7% | 91.9% |  |
| POP_JUMP_IF_TRUE | 13,516,800 | 0.7% | 92.6% |  |
| COMPARE_OP_INT | 11,673,780 | 0.6% | 93.2% |  |
| TO_BOOL_NONE | 11,059,200 | 0.6% | 93.8% |  |
| TO_BOOL_ALWAYS_TRUE | 9,830,400 | 0.5% | 94.3% |  |
| ENTER_EXECUTOR | 7,741,440 | 0.4% | 94.7% |  |
| BINARY_OP | 6,760,260 | 0.3% | 95.0% |  |
| COPY | 6,144,000 | 0.3% | 95.3% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 6,144,000 | 0.3% | 95.7% |  |
| CALL_ISINSTANCE | 5,529,600 | 0.3% | 95.9% |  |
| JUMP_FORWARD | 4,915,200 | 0.3% | 96.2% |  |
| COMPARE_OP_STR | 4,915,200 | 0.3% | 96.4% |  |
| BINARY_SLICE | 4,915,200 | 0.3% | 96.7% |  |
| BINARY_OP_ADD_INT | 4,915,200 | 0.3% | 97.0% |  |
| CALL_BUILTIN_FAST | 4,300,800 | 0.2% | 97.2% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,710,220 | 0.2% | 97.4% | 33.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,686,760 | 0.2% | 97.6% |  |
| GET_ITER | 3,686,580 | 0.2% | 97.7% |  |
| POP_JUMP_IF_NONE | 3,686,400 | 0.2% | 97.9% |  |
| FOR_ITER_LIST | 3,686,400 | 0.2% | 98.1% |  |
| BUILD_TUPLE | 3,686,400 | 0.2% | 98.3% |  |
| INTERPRETER_EXIT | 3,072,000 | 0.2% | 98.5% |  |
| TO_BOOL | 2,458,240 | 0.1% | 98.6% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 2,458,140 | 0.1% | 98.7% |  |
| STORE_FAST_STORE_FAST | 2,457,600 | 0.1% | 98.9% |  |
| POP_JUMP_IF_NOT_NONE | 2,457,600 | 0.1% | 99.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,457,600 | 0.1% | 99.1% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,843,200 | 0.1% | 99.2% |  |
| CALL_FUNCTION_EX | 1,229,160 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_FLOAT | 1,228,980 | 0.1% | 99.3% |  |
| UNPACK_SEQUENCE_TUPLE | 1,228,800 | 0.1% | 99.4% |  |
| TO_BOOL_STR | 1,228,800 | 0.1% | 99.5% |  |
| LOAD_ATTR_PROPERTY | 1,228,800 | 0.1% | 99.5% |  |
| DICT_MERGE | 1,228,800 | 0.1% | 99.6% |  |
| CONTAINS_OP | 1,228,800 | 0.1% | 99.7% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 122,880,000 | 6.3% | 6.3% |
| RESUME_CHECK LOAD_FAST | 103,219,380 | 5.3% | 11.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 100,393,140 | 5.2% | 16.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 97,689,600 | 5.0% | 21.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 79,872,180 | 4.1% | 26.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 54,681,600 | 2.8% | 28.9% |
| RETURN_CONST POP_TOP | 50,380,980 | 2.6% | 31.5% |
| NOP LOAD_FAST | 46,694,400 | 2.4% | 33.9% |
| LOAD_FAST CALL | 46,080,160 | 2.4% | 36.2% |
| RETURN_VALUE TO_BOOL_BOOL | 45,465,600 | 2.3% | 38.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 43,008,000 | 2.2% | 40.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 43,008,000 | 2.2% | 43.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 43,008,000 | 2.2% | 45.3% |
| POP_JUMP_IF_FALSE NOP | 41,779,200 | 2.2% | 47.4% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 41,779,200 | 2.2% | 49.6% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 41,779,200 | 2.2% | 51.7% |
| POP_TOP LOAD_FAST | 41,410,740 | 2.1% | 53.9% |
| LOAD_FAST BINARY_SUBSCR_DICT | 40,550,400 | 2.1% | 56.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 40,550,400 | 2.1% | 58.0% |
| CALL RESUME_CHECK | 40,550,400 | 2.1% | 60.1% |
| STORE_FAST LOAD_FAST | 32,563,680 | 1.7% | 61.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 30,105,780 | 1.6% | 63.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 20,275,500 | 1.0% | 64.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 19,660,920 | 1.0% | 65.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 14,745,600 | 0.8% | 66.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 14,131,320 | 0.7% | 66.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 13,517,280 | 0.7% | 67.6% |
| LOAD_FAST LOAD_ATTR | 13,516,980 | 0.7% | 68.3% |
| LOAD_FAST LOAD_CONST | 12,902,520 | 0.7% | 69.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 12,288,000 | 0.6% | 69.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,059,560 | 0.6% | 70.2% |
| POP_TOP RETURN_CONST | 11,059,380 | 0.6% | 70.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 11,059,200 | 0.6% | 71.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 11,059,200 | 0.6% | 71.9% |
| RETURN_VALUE STORE_FAST | 11,059,200 | 0.6% | 72.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 9,830,400 | 0.5% | 73.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 9,830,400 | 0.5% | 73.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 9,216,180 | 0.5% | 74.0% |
| LOAD_FAST RETURN_VALUE | 8,601,780 | 0.4% | 74.4% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 8,601,600 | 0.4% | 74.9% |
| LOAD_CONST COMPARE_OP_INT | 7,987,240 | 0.4% | 75.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 7,372,800 | 0.4% | 75.7% |
| LOAD_CONST STORE_FAST | 7,372,800 | 0.4% | 76.0% |
| LOAD_CONST LOAD_FAST | 7,372,800 | 0.4% | 76.4% |
| LOAD_ATTR_MODULE LOAD_ATTR_MODULE | 6,758,400 | 0.3% | 76.8% |
| PUSH_NULL LOAD_FAST | 6,144,360 | 0.3% | 77.1% |
| RETURN_VALUE RETURN_VALUE | 6,144,180 | 0.3% | 77.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,144,000 | 0.3% | 77.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 6,144,000 | 0.3% | 78.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 6,144,000 | 0.3% | 78.4% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 6,144,000 | 0.3% | 78.7% |
| LOAD_ATTR_MODULE LOAD_FAST | 6,144,000 | 0.3% | 79.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 6,144,000 | 0.3% | 79.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_ALWAYS_TRUE | 6,144,000 | 0.3% | 79.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 6,144,000 | 0.3% | 79.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 5,529,600 | 0.3% | 80.2% |
| POP_TOP ENTER_EXECUTOR | 5,283,840 | 0.3% | 80.5% |
| CALL STORE_FAST | 4,915,380 | 0.3% | 80.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 4,915,360 | 0.3% | 81.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 4,915,200 | 0.3% | 81.3% |
| RETURN_VALUE LOAD_FAST | 4,915,200 | 0.3% | 81.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 4,915,200 | 0.3% | 81.8% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 4,915,200 | 0.3% | 82.0% |
| LOAD_FAST TO_BOOL_NONE | 4,915,200 | 0.3% | 82.3% |
| LOAD_FAST STORE_FAST | 4,915,200 | 0.3% | 82.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 4,915,200 | 0.3% | 82.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 4,915,200 | 0.3% | 83.0% |
| COPY TO_BOOL_BOOL | 4,915,200 | 0.3% | 83.3% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 4,054,860 | 0.2% | 83.5% |
| LOAD_ATTR LOAD_ATTR | 3,690,800 | 0.2% | 83.7% |
| PUSH_NULL CALL | 3,686,940 | 0.2% | 83.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 3,686,580 | 0.2% | 84.1% |
| LOAD_CONST BINARY_OP | 3,686,440 | 0.2% | 84.3% |
| STORE_FAST LOAD_CONST | 3,686,400 | 0.2% | 84.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 3,686,400 | 0.2% | 84.6% |
| RESUME_CHECK NOP | 3,686,400 | 0.2% | 84.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 3,686,400 | 0.2% | 85.0% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 3,686,400 | 0.2% | 85.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,686,400 | 0.2% | 85.4% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 3,686,400 | 0.2% | 85.6% |
| LOAD_FAST TO_BOOL_ALWAYS_TRUE | 3,686,400 | 0.2% | 85.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 3,686,400 | 0.2% | 86.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 3,686,400 | 0.2% | 86.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 3,686,400 | 0.2% | 86.4% |
| LOAD_CONST CALL_BUILTIN_FAST | 3,686,400 | 0.2% | 86.5% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 3,686,400 | 0.2% | 86.7% |
| LOAD_ATTR STORE_FAST | 3,686,400 | 0.2% | 86.9% |
| LOAD_ATTR LOAD_FAST | 3,686,400 | 0.2% | 87.1% |
| LOAD_ATTR CALL_PY_EXACT_ARGS | 3,686,400 | 0.2% | 87.3% |
| GET_ITER FOR_ITER_LIST | 3,686,400 | 0.2% | 87.5% |
| COMPARE_OP_STR COPY | 3,686,400 | 0.2% | 87.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS POP_TOP | 3,686,400 | 0.2% | 87.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 3,686,400 | 0.2% | 88.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS RETURN_VALUE | 3,686,400 | 0.2% | 88.3% |
| CALL LOAD_CONST | 3,686,400 | 0.2% | 88.4% |
| BINARY_OP_ADD_INT STORE_FAST | 3,686,400 | 0.2% | 88.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 3,072,000 | 0.2% | 88.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 3,072,000 | 0.2% | 89.0% |
| CACHE RESUME_CHECK | 3,072,000 | 0.2% | 89.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 2,457,840 | 0.1% | 89.2% |


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

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 41,779,200 | 85.0% |
| RESUME_CHECK | 3,686,400 | 7.5% |
| POP_TOP | 2,457,780 | 5.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,228,800 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,694,400 | 95.0% |
| LOAD_GLOBAL_MODULE | 2,457,600 | 5.0% |
| LOAD_DEREF | 180 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 50,380,980 | 82.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,686,400 | 6.0% |
| CALL | 2,457,780 | 4.0% |
| RETURN_VALUE | 1,228,800 | 2.0% |
| POP_JUMP_IF_TRUE | 1,228,800 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,410,740 | 67.4% |
| RETURN_CONST | 11,059,380 | 18.0% |
| ENTER_EXECUTOR | 5,283,840 | 8.6% |
| NOP | 2,457,780 | 4.0% |
| LOAD_CONST | 1,228,800 | 2.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 13,517,280 | 91.7% |
| LOAD_ATTR | 1,228,860 | 8.3% |
| LOAD_DEREF | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,144,360 | 41.7% |
| CALL | 3,686,940 | 25.0% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 8.3% |
| LOAD_FAST_LOAD_FAST | 1,228,800 | 8.3% |
| LOAD_CONST | 1,228,800 | 8.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 41,779,200 | 57.1% |
| LOAD_FAST | 8,601,780 | 11.8% |
| RETURN_VALUE | 6,144,180 | 8.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,686,400 | 5.0% |
| POP_JUMP_IF_TRUE | 2,457,600 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 45,465,600 | 62.2% |
| STORE_FAST | 11,059,200 | 15.1% |
| RETURN_VALUE | 6,144,180 | 8.4% |
| LOAD_FAST | 4,915,200 | 6.7% |
| UNPACK_SEQUENCE_TUPLE | 1,228,800 | 1.7% |


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

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,080,160 | 81.5% |
| PUSH_NULL | 3,686,940 | 6.5% |
| LOAD_ATTR_METHOD_NO_DICT | 2,457,640 | 4.3% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 2.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,228,800 | 2.2% |

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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,283,840 | 68.3% |
| POP_JUMP_IF_FALSE | 2,457,600 | 31.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,054,860 | 52.4% |
| LOAD_ATTR_MODULE | 2,457,600 | 31.7% |
| LOAD_FAST | 1,228,800 | 15.9% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


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
| LOAD_FAST | 13,516,980 | 78.6% |
| LOAD_ATTR | 3,690,800 | 21.4% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,690,800 | 21.4% |
| STORE_FAST | 3,686,400 | 21.4% |
| LOAD_FAST | 3,686,400 | 21.4% |
| CALL_PY_EXACT_ARGS | 3,686,400 | 21.4% |
| PUSH_NULL | 1,228,860 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,902,520 | 30.0% |
| STORE_FAST | 3,686,400 | 8.6% |
| LOAD_FAST_LOAD_FAST | 3,686,400 | 8.6% |
| CALL | 3,686,400 | 8.6% |
| POP_JUMP_IF_TRUE | 2,457,600 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 7,987,240 | 18.6% |
| STORE_FAST | 7,372,800 | 17.1% |
| LOAD_FAST | 7,372,800 | 17.1% |
| BINARY_OP_ADD_INT | 4,915,200 | 11.4% |
| BINARY_OP | 3,686,440 | 8.6% |


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
| RESUME_CHECK | 103,219,380 | 23.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 54,681,600 | 12.6% |
| NOP | 46,694,400 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 43,008,000 | 9.9% |
| POP_TOP | 41,410,740 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 122,880,000 | 28.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 100,393,140 | 23.1% |
| CALL | 46,080,160 | 10.6% |
| BINARY_SUBSCR_DICT | 40,550,400 | 9.3% |
| CALL_PY_EXACT_ARGS | 19,660,920 | 4.5% |


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
| TO_BOOL_BOOL | 97,689,600 | 74.3% |
| TO_BOOL_NONE | 11,059,200 | 8.4% |
| COMPARE_OP_INT | 9,216,180 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 8,601,600 | 6.5% |
| TO_BOOL | 2,457,600 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 43,008,000 | 32.7% |
| NOP | 41,779,200 | 31.8% |
| LOAD_FAST | 30,105,780 | 22.9% |
| LOAD_GLOBAL_MODULE | 4,915,200 | 3.7% |
| LOAD_GLOBAL_BUILTIN | 3,686,400 | 2.8% |


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
| TO_BOOL_BOOL | 11,059,200 | 81.8% |
| TO_BOOL_ALWAYS_TRUE | 1,228,800 | 9.1% |
| COMPARE_OP_INT | 1,228,800 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,144,000 | 45.5% |
| RETURN_VALUE | 2,457,600 | 18.2% |
| LOAD_CONST | 2,457,600 | 18.2% |
| POP_TOP | 1,228,800 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 1,228,800 | 9.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 43,008,000 | 79.5% |
| POP_TOP | 11,059,380 | 20.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 50,380,980 | 93.2% |
| INTERPRETER_EXIT | 2,457,600 | 4.5% |
| STORE_FAST | 1,228,800 | 2.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,059,200 | 21.7% |
| LOAD_CONST | 7,372,800 | 14.5% |
| CALL | 4,915,380 | 9.6% |
| LOAD_FAST | 4,915,200 | 9.6% |
| LOAD_ATTR | 3,686,400 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,563,680 | 63.9% |
| LOAD_GLOBAL_MODULE | 4,915,360 | 9.6% |
| LOAD_FAST_LOAD_FAST | 4,915,200 | 9.6% |
| LOAD_CONST | 3,686,400 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 2,457,840 | 4.8% |


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

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,457,600 | 66.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 1,228,920 | 33.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 23,640 | 0.6% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,686,400 | 99.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 23,640 | 0.6% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |
| CALL_LEN | 40 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,779,200 | 52.3% |
| LOAD_FAST | 19,660,920 | 24.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,830,400 | 12.3% |
| LOAD_ATTR | 3,686,400 | 4.6% |
| LOAD_FAST_LOAD_FAST | 2,457,600 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 79,872,180 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,987,240 | 68.4% |
| LOAD_FAST_LOAD_FAST | 2,457,600 | 21.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 10.5% |
| BINARY_OP_MULTIPLY_INT | 80 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,216,180 | 78.9% |
| RETURN_VALUE | 1,228,800 | 10.5% |
| POP_JUMP_IF_TRUE | 1,228,800 | 10.5% |


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
| LOAD_FAST | 122,880,000 | 99.5% |
| LOAD_FAST_LOAD_FAST | 614,400 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 23,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 43,008,000 | 34.8% |
| LOAD_FAST | 43,008,000 | 34.8% |
| TO_BOOL_ALWAYS_TRUE | 6,144,000 | 5.0% |
| LOAD_ATTR_METHOD_NO_DICT | 6,144,000 | 5.0% |
| TO_BOOL_NONE | 4,915,200 | 4.0% |


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

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,393,140 | 93.9% |
| ENTER_EXECUTOR | 4,054,860 | 3.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,457,600 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,681,600 | 51.1% |
| LOAD_GLOBAL_MODULE | 40,550,400 | 37.9% |
| CALL_PY_EXACT_ARGS | 9,830,400 | 9.2% |
| LOAD_FAST_LOAD_FAST | 1,843,200 | 1.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20,275,500 | 68.7% |
| LOAD_ATTR_MODULE | 6,758,400 | 22.9% |
| ENTER_EXECUTOR | 2,457,600 | 8.3% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 13,517,280 | 45.8% |
| LOAD_ATTR_MODULE | 6,758,400 | 22.9% |
| LOAD_FAST | 6,144,000 | 20.8% |
| LOAD_ATTR_METHOD_NO_DICT | 2,457,600 | 8.3% |
| CALL_ISINSTANCE | 614,400 | 2.1% |


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
| LOAD_ATTR_METHOD_WITH_VALUES | 40,550,400 | 45.8% |
| RESUME_CHECK | 14,131,320 | 16.0% |
| STORE_ATTR_INSTANCE_VALUE | 7,372,800 | 8.3% |
| LOAD_FAST | 6,144,000 | 6.9% |
| STORE_FAST | 4,915,360 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 41,779,200 | 47.2% |
| LOAD_ATTR_MODULE | 20,275,500 | 22.9% |
| TO_BOOL_BOOL | 4,915,200 | 5.6% |
| LOAD_FAST | 3,686,580 | 4.2% |
| COMPARE_OP_STR | 3,686,400 | 4.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 79,872,180 | 64.0% |
| CALL | 40,550,400 | 32.5% |
| CACHE | 3,072,000 | 2.5% |
| LOAD_ATTR_PROPERTY | 1,228,800 | 1.0% |
| COPY_FREE_VARS | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 103,219,380 | 82.8% |
| LOAD_GLOBAL_MODULE | 14,131,320 | 11.3% |
| NOP | 3,686,400 | 3.0% |
| LOAD_GLOBAL_BUILTIN | 2,457,600 | 2.0% |
| LOAD_CONST | 1,228,800 | 1.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,465,600 | 41.8% |
| LOAD_ATTR_INSTANCE_VALUE | 43,008,000 | 39.5% |
| CALL_ISINSTANCE | 5,529,600 | 5.1% |
| LOAD_GLOBAL_MODULE | 4,915,200 | 4.5% |
| COPY | 4,915,200 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 97,689,600 | 89.8% |
| POP_JUMP_IF_TRUE | 11,059,200 | 10.2% |


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
| COMPARE_OP_STR | 3,686,400 | 60.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,228,800 | 20.0% |
| CONTAINS_OP | 1,228,800 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,915,200 | 80.0% |
| STORE_FAST | 1,228,800 | 20.0% |


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

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 9,830,400 | 28.1% |
| LOAD_FAST_LOAD_FAST | 6,144,000 | 17.5% |
| STORE_FAST | 4,915,200 | 14.0% |
| POP_JUMP_IF_FALSE | 3,072,000 | 8.8% |
| LOAD_GLOBAL_MODULE | 3,072,000 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,288,000 | 35.1% |
| LOAD_FAST_LOAD_FAST | 6,144,000 | 17.5% |
| LOAD_FAST | 3,686,400 | 10.5% |
| LOAD_CONST | 3,686,400 | 10.5% |
| COMPARE_OP_INT | 2,457,600 | 7.0% |


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
| LOAD_FAST | 6,144,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,686,400 | 60.0% |
| STORE_FAST | 2,457,600 | 40.0% |


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

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,686,400 | 75.0% |
| LOAD_FAST | 1,228,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,686,400 | 75.0% |
| POP_JUMP_IF_FALSE | 1,228,800 | 25.0% |


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

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,144,000 | 45.5% |
| LOAD_FAST | 3,686,400 | 27.3% |
| LOAD_ATTR_MODULE | 2,457,600 | 18.2% |
| LOAD_GLOBAL_MODULE | 1,228,800 | 9.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,144,000 | 45.5% |
| CALL | 2,457,640 | 18.2% |
| LOAD_CONST | 2,457,600 | 18.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,457,600 | 18.2% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 80 | 0.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 6,144,000 | 62.5% |
| LOAD_FAST | 3,686,400 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,601,600 | 87.5% |
| POP_JUMP_IF_TRUE | 1,228,800 | 12.5% |


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
| specialization.deferred |      2457600 | 1.8% |
|          hit |    130867200 | 98.2% |

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
| specialization.deferred |     56525340 | 34.7% |
| specialization.deopt |        23640 | 0.0% |
|          hit |    105063600 | 64.5% |
|         miss |      1252440 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 24,040 | 62.1% |
| Failure | 14,700 | 37.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 10,400 | 70.7% |
| cfunc noargs | 1,460 | 9.9% |
| meth descr varargs | 1,280 | 8.7% |
| class no vectorcall | 640 | 4.4% |
| meth descr varargs keywords | 600 | 4.1% |
| init not simple | 320 | 2.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     16588980 | 100.0% |

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
| specialization.deferred |     17203260 | 5.8% |
| specialization.deopt |        23400 | 0.0% |
|          hit |    278336060 | 93.8% |
|         miss |      1240480 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 23,800 | 84.4% |
| Failure | 4,400 | 15.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 1,880 | 42.7% |
| non object slot | 1,560 | 35.5% |
| class attr descriptor | 320 | 7.3% |
| shadowed | 320 | 7.3% |
| method | 320 | 7.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 0.0% |
|          hit |    103220460 | 100.0% |

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
| Basic | 852,180,600 | 44.0% |
| Not specialized | 241,518,260 | 12.5% |
| Specialized | 842,973,320 | 43.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 56,525,340 | 68.1% |
| LOAD_ATTR | 17,203,260 | 20.7% |
| BINARY_OP | 6,758,400 | 8.1% |
| TO_BOOL | 2,457,600 | 3.0% |
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
| Calls to PyEval_EvalDefault | 3,072,000 | 2.5% |
| Calls to Python functions inlined | 121,651,740 | 97.5% |
| Calls via PyEval_EvalFrame (total) | 3,072,000 | 2.5% |
| Calls via PyEval_EvalFrame (vector) | 3,072,000 | 2.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 3,072,000 | 2.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 127,181,340 | 102.0% |
| Frame objects created | 3,686,520 | 3.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 64,512,660 | 66.9% |
| Frees to freelist | 64,512,660 |  |
| Allocations | 31,953,363 | 33.1% |
| Allocations to 512 bytes | 31,953,243 | 33.1% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 31,953,343 |  |
| New values | 1,228,800 |  |
| Interpreter increfs | 819,013,760 | 89.2% |
| Interpreter decrefs | 911,458,443 | 89.7% |
| Increfs | 98,693,095 | 10.8% |
| Decrefs | 105,171,715 | 10.3% |
| Materialize dict (on request) | 1,228,800 | 100.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 1,228,800 | 100.0% |
| Method cache hits | 24,561,065 |  |
| Method cache misses | 30,975 |  |
| Method cache collisions | 30,975 |  |
| Method cache dunder hits | 6,144,640 |  |
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
| Traces executed | 7,741,440 |  |
| Uops executed | 113,909,400 | 14 |
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
| <= 8 | 1,228,980 | 15.9% |
| <= 16 | 4,054,860 | 52.4% |
| <= 32 | 2,457,600 | 31.7% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 27,770,880 | 24.4% | 24.4% |
| LOAD_FAST | 13,885,260 | 12.2% | 36.6% |
| STORE_FAST | 8,970,060 | 7.9% | 44.4% |
| _POP_JUMP_IF_TRUE | 7,741,440 | 6.8% | 51.2% |
| _EXIT_TRACE | 7,741,440 | 6.8% | 58.0% |
| _LOAD_GLOBAL_MODULE | 4,915,200 | 4.3% | 62.4% |
| _GUARD_GLOBALS_VERSION | 4,915,200 | 4.3% | 66.7% |
| _ITER_CHECK_RANGE | 4,055,040 | 3.6% | 70.2% |
| _IS_ITER_EXHAUSTED_RANGE | 4,055,040 | 3.6% | 73.8% |
| _ITER_NEXT_RANGE | 4,054,860 | 3.6% | 77.3% |
| _SAVE_CURRENT_IP | 2,457,600 | 2.2% | 79.5% |
| _PUSH_FRAME | 2,457,600 | 2.2% | 81.7% |
| _IS_NONE | 2,457,600 | 2.2% | 83.8% |
| _INIT_CALL_PY_EXACT_ARGS | 2,457,600 | 2.2% | 86.0% |
| _CHECK_STACK_SPACE | 2,457,600 | 2.2% | 88.1% |
| _CHECK_PEP_523 | 2,457,600 | 2.2% | 90.3% |
| _CHECK_FUNCTION_EXACT_ARGS | 2,457,600 | 2.2% | 92.4% |
| RESUME_CHECK | 2,457,600 | 2.2% | 94.6% |
| LOAD_ATTR | 2,457,600 | 2.2% | 96.8% |
| POP_TOP | 1,228,980 | 1.1% | 97.8% |
| _ITER_CHECK_LIST | 1,228,800 | 1.1% | 98.9% |
| _IS_ITER_EXHAUSTED_LIST | 1,228,800 | 1.1% | 100.0% |


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
Stats gathered on: 2023-10-03
