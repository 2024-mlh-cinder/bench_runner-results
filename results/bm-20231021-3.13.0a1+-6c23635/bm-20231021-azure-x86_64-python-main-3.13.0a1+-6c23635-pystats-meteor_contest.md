
# Pystats results

- benchmark: meteor_contest
- fork: python
- ref: main
- commit hash: 6c23635
- commit date: 2023-10-21T22:18:34+03:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| STORE_FAST | 64,602,960 | 13.8% | 13.8% |  |
| LOAD_FAST | 60,488,880 | 12.9% | 26.8% |  |
| LOAD_FAST_LOAD_FAST | 58,566,600 | 12.5% | 39.3% |  |
| JUMP_BACKWARD | 46,731,180 | 10.0% | 49.3% |  |
| FOR_ITER_LIST | 38,009,220 | 8.1% | 57.4% |  |
| POP_JUMP_IF_TRUE | 34,382,100 | 7.4% | 64.8% |  |
| COMPARE_OP | 26,469,600 | 5.7% | 70.4% |  |
| FOR_ITER | 18,532,280 | 4.0% | 74.4% |  |
| LOAD_CONST | 16,130,760 | 3.5% | 77.8% |  |
| STORE_SUBSCR_LIST_INT | 15,439,800 | 3.3% | 81.1% |  |
| LOAD_GLOBAL_BUILTIN | 14,097,240 | 3.0% | 84.2% |  |
| CALL_LEN | 11,007,180 | 2.4% | 86.5% |  |
| COMPARE_OP_INT | 11,007,000 | 2.4% | 88.9% |  |
| GET_ITER | 9,805,920 | 2.1% | 91.0% |  |
| BINARY_SUBSCR_LIST_INT | 9,804,060 | 2.1% | 93.1% |  |
| BINARY_OP | 6,173,940 | 1.3% | 94.4% |  |
| BINARY_SLICE | 4,974,660 | 1.1% | 95.4% |  |
| POP_TOP | 3,780,000 | 0.8% | 96.3% |  |
| POP_JUMP_IF_FALSE | 3,088,020 | 0.7% | 96.9% |  |
| CALL | 3,087,340 | 0.7% | 97.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,892,100 | 0.4% | 98.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,888,500 | 0.4% | 98.4% |  |
| LOAD_GLOBAL_MODULE | 1,886,980 | 0.4% | 98.8% |  |
| RESUME_CHECK | 1,886,880 | 0.4% | 99.2% |  |
| RETURN_CONST | 1,886,760 | 0.4% | 99.6% |  |
| CALL_PY_WITH_DEFAULTS | 1,886,760 | 0.4% | 100.0% |  |
| PUSH_NULL | 3,900 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,600 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,600 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 2,100 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 1,820 | 0.0% | 100.0% |  |
| BUILD_SLICE | 1,800 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 280 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| BUILD_LIST | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| RETURN_VALUE | 120 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST_LOAD_FAST | 46,734,000 | 10.0% | 10.0% |
| FOR_ITER_LIST STORE_FAST | 31,294,200 | 6.7% | 16.7% |
| JUMP_BACKWARD FOR_ITER_LIST | 31,291,320 | 6.7% | 23.4% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 29,404,620 | 6.3% | 29.7% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 26,463,060 | 5.7% | 35.3% |
| COMPARE_OP POP_JUMP_IF_TRUE | 26,463,060 | 5.7% | 41.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 22,299,480 | 4.8% | 45.8% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 15,439,800 | 3.3% | 49.1% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 15,439,800 | 3.3% | 52.4% |
| JUMP_BACKWARD FOR_ITER | 15,439,800 | 3.3% | 55.7% |
| FOR_ITER STORE_FAST | 15,439,800 | 3.3% | 59.0% |
| STORE_FAST LOAD_FAST | 11,696,220 | 2.5% | 61.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,009,040 | 2.4% | 63.8% |
| LOAD_FAST GET_ITER | 9,805,920 | 2.1% | 65.9% |
| LOAD_FAST CALL_LEN | 7,920,960 | 1.7% | 67.6% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 7,919,040 | 1.7% | 69.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 6,717,900 | 1.4% | 70.8% |
| GET_ITER FOR_ITER_LIST | 6,717,900 | 1.4% | 72.2% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 6,717,900 | 1.4% | 73.6% |
| LOAD_CONST COMPARE_OP_INT | 6,174,120 | 1.3% | 74.9% |
| CALL_LEN LOAD_CONST | 6,174,120 | 1.3% | 76.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 6,172,400 | 1.3% | 77.6% |
| LOAD_CONST LOAD_CONST | 4,978,260 | 1.1% | 78.7% |
| LOAD_FAST LOAD_CONST | 4,976,520 | 1.1% | 79.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 4,974,660 | 1.1% | 80.8% |
| LOAD_CONST BINARY_SLICE | 4,974,660 | 1.1% | 81.8% |
| BINARY_SLICE STORE_FAST | 4,974,660 | 1.1% | 82.9% |
| LOAD_FAST COMPARE_OP_INT | 4,832,880 | 1.0% | 83.9% |
| CALL_LEN LOAD_FAST | 4,832,880 | 1.0% | 85.0% |
| FOR_ITER_LIST LOAD_GLOBAL_BUILTIN | 4,831,080 | 1.0% | 86.0% |
| LOAD_FAST LOAD_FAST_LOAD_FAST | 3,773,460 | 0.8% | 86.8% |
| GET_ITER FOR_ITER | 3,087,960 | 0.7% | 87.5% |
| FOR_ITER LOAD_GLOBAL_BUILTIN | 3,087,960 | 0.7% | 88.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,087,960 | 0.7% | 88.8% |
| LOAD_FAST CALL | 3,086,260 | 0.7% | 89.5% |
| CALL STORE_FAST | 3,086,220 | 0.7% | 90.1% |
| BINARY_OP STORE_FAST | 3,086,220 | 0.7% | 90.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 3,086,160 | 0.7% | 91.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 3,086,160 | 0.7% | 92.1% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 3,086,160 | 0.7% | 92.8% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 3,086,160 | 0.7% | 93.4% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 3,086,160 | 0.7% | 94.1% |
| BINARY_OP CALL_LEN | 3,086,160 | 0.7% | 94.7% |
| LOAD_FAST LOAD_FAST | 1,890,300 | 0.4% | 95.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,890,300 | 0.4% | 95.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,890,300 | 0.4% | 96.0% |
| RETURN_CONST POP_TOP | 1,886,760 | 0.4% | 96.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 1,886,760 | 0.4% | 96.8% |
| POP_TOP JUMP_BACKWARD | 1,886,760 | 0.4% | 97.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,886,760 | 0.4% | 97.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,886,760 | 0.4% | 98.0% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,886,740 | 0.4% | 98.4% |
| POP_TOP LOAD_GLOBAL_MODULE | 1,886,700 | 0.4% | 98.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,886,700 | 0.4% | 99.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,886,700 | 0.4% | 99.6% |
| FOR_ITER_LIST RETURN_CONST | 1,883,940 | 0.4% | 100.0% |
| COMPARE_OP COMPARE_OP | 6,480 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER | 4,520 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 3,720 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 3,600 | 0.0% | 100.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 3,600 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,600 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 3,600 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS LOAD_FAST | 3,600 | 0.0% | 100.0% |
| POP_TOP RETURN_CONST | 2,820 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE POP_TOP | 2,820 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 1,960 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 1,840 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 1,800 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 1,800 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,800 | 0.0% | 100.0% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 1,800 | 0.0% | 100.0% |
| LOAD_CONST BUILD_SLICE | 1,800 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_BUILTIN | 1,800 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_O STORE_FAST | 1,800 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_METHOD_DESCRIPTOR_O | 1,800 | 0.0% | 100.0% |
| BUILD_SLICE BINARY_SUBSCR | 1,800 | 0.0% | 100.0% |
| BINARY_SUBSCR STORE_FAST | 1,800 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 1,540 | 0.0% | 100.0% |
| CALL CALL | 820 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 160 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| CALL_LEN CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_CONST | 60 | 0.0% | 100.0% |
| STORE_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP POP_TOP | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,974,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,974,660 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 1,800 | 98.9% |
| BINARY_SUBSCR | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,800 | 98.9% |
| BINARY_SUBSCR | 20 | 1.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,805,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 6,717,900 | 68.5% |
| FOR_ITER | 3,087,960 | 31.5% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,886,760 | 49.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,886,700 | 49.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,600 | 0.1% |
| POP_JUMP_IF_TRUE | 2,820 | 0.1% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,886,760 | 49.9% |
| LOAD_GLOBAL_MODULE | 1,886,700 | 49.9% |
| RETURN_CONST | 2,820 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 1,800 | 0.0% |
| LOAD_FAST | 1,800 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,600 | 92.3% |
| LOAD_ATTR_MODULE | 160 | 4.1% |
| LOAD_DEREF | 120 | 3.1% |
| LOAD_ATTR | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,720 | 95.4% |
| CALL | 180 | 4.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_GLOBAL | 40 | 33.3% |
| LOAD_GLOBAL_MODULE | 20 | 16.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,086,160 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 3,086,160 | 50.0% |
| BINARY_OP | 1,540 | 0.0% |
| CALL_LEN | 60 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,086,220 | 50.0% |
| CALL_LEN | 3,086,160 | 50.0% |
| BINARY_OP | 1,540 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |
| LOAD_CONST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| LOAD_DEREF | 60 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 40 | 22.2% |
| LOAD_GLOBAL | 20 | 11.1% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 1,800 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,086,260 | 100.0% |
| CALL | 820 | 0.0% |
| PUSH_NULL | 180 | 0.0% |
| CALL_LEN | 40 | 0.0% |
| CALL_BUILTIN_CLASS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,086,220 | 100.0% |
| CALL | 820 | 0.0% |
| CALL_BUILTIN_CLASS | 100 | 0.0% |
| POP_TOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 26,463,060 | 100.0% |
| COMPARE_OP | 6,480 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,463,060 | 100.0% |
| COMPARE_OP | 6,480 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |


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

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 15,439,800 | 83.3% |
| GET_ITER | 3,087,960 | 16.7% |
| FOR_ITER | 4,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,439,800 | 83.3% |
| LOAD_GLOBAL_BUILTIN | 3,087,960 | 16.7% |
| FOR_ITER | 4,520 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 29,404,620 | 62.9% |
| STORE_SUBSCR_LIST_INT | 15,439,800 | 33.0% |
| POP_TOP | 1,886,760 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 31,291,320 | 67.0% |
| FOR_ITER | 15,439,800 | 33.0% |
| FOR_ITER_RANGE | 60 | 0.0% |


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
| LOAD_GLOBAL_MODULE | 60 | 75.0% |
| LOAD_GLOBAL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 75.0% |
| PUSH_NULL | 20 | 25.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 6,174,120 | 38.3% |
| LOAD_CONST | 4,978,260 | 30.9% |
| LOAD_FAST | 4,976,520 | 30.9% |
| POP_JUMP_IF_FALSE | 1,800 | 0.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 6,174,120 | 38.3% |
| LOAD_CONST | 4,978,260 | 30.9% |
| BINARY_SLICE | 4,974,660 | 30.8% |
| LOAD_ATTR_METHOD_NO_DICT | 1,800 | 0.0% |
| BUILD_SLICE | 1,800 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 22,299,480 | 36.9% |
| STORE_FAST | 11,696,220 | 19.3% |
| LOAD_GLOBAL_BUILTIN | 11,009,040 | 18.2% |
| POP_JUMP_IF_TRUE | 4,974,660 | 8.2% |
| CALL_LEN | 4,832,880 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 15,439,800 | 25.5% |
| GET_ITER | 9,805,920 | 16.2% |
| CALL_LEN | 7,920,960 | 13.1% |
| LOAD_CONST | 4,976,520 | 8.2% |
| COMPARE_OP_INT | 4,832,880 | 8.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,734,000 | 79.8% |
| LOAD_FAST | 3,773,460 | 6.4% |
| POP_JUMP_IF_FALSE | 3,086,160 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 3,086,160 | 5.3% |
| RESUME_CHECK | 1,886,760 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 26,463,060 | 45.2% |
| LOAD_FAST | 22,299,480 | 38.1% |
| BINARY_SUBSCR_LIST_INT | 6,717,900 | 11.5% |
| BINARY_OP | 3,086,160 | 5.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 80 | 28.6% |
| RETURN_VALUE | 40 | 14.3% |
| RESUME_CHECK | 20 | 7.1% |
| LOAD_FAST_CHECK | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160 | 57.1% |
| LOAD_GLOBAL_MODULE | 100 | 35.7% |
| LOAD_ATTR | 20 | 7.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 3,087,960 | 100.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,086,160 | 99.9% |
| LOAD_CONST | 1,800 | 0.1% |
| LOAD_FAST | 60 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 26,463,060 | 77.0% |
| COMPARE_OP_INT | 7,919,040 | 23.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 29,404,620 | 85.5% |
| LOAD_FAST | 4,974,660 | 14.5% |
| POP_TOP | 2,820 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,883,940 | 99.9% |
| POP_TOP | 2,820 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,886,760 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 31,294,200 | 48.4% |
| FOR_ITER | 15,439,800 | 23.9% |
| BINARY_SUBSCR_LIST_INT | 6,717,900 | 10.4% |
| BINARY_SLICE | 4,974,660 | 7.7% |
| CALL | 3,086,220 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,734,000 | 72.3% |
| LOAD_FAST | 11,696,220 | 18.1% |
| LOAD_GLOBAL_BUILTIN | 6,172,400 | 9.6% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


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
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,717,900 | 68.5% |
| LOAD_FAST | 3,086,160 | 31.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,717,900 | 68.5% |
| BINARY_OP | 3,086,160 | 31.5% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,840 | 87.6% |
| CALL | 100 | 4.8% |
| CALL_LEN | 80 | 3.8% |
| CALL_BUILTIN_CLASS | 80 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 1,800 | 85.7% |
| STORE_FAST | 180 | 8.6% |
| CALL_BUILTIN_CLASS | 80 | 3.8% |
| CALL | 40 | 1.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,600 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,920,960 | 72.0% |
| BINARY_OP | 3,086,160 | 28.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,174,120 | 56.1% |
| LOAD_FAST | 4,832,880 | 43.9% |
| CALL_BUILTIN_CLASS | 80 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,600 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,886,700 | 99.9% |
| CALL_BUILTIN_CLASS | 1,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,886,700 | 99.9% |
| STORE_FAST | 1,800 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,886,740 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,886,760 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,174,120 | 56.1% |
| LOAD_FAST | 4,832,880 | 43.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,919,040 | 71.9% |
| POP_JUMP_IF_FALSE | 3,087,960 | 28.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 31,291,320 | 82.3% |
| GET_ITER | 6,717,900 | 17.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,294,200 | 82.3% |
| LOAD_GLOBAL_BUILTIN | 4,831,080 | 12.7% |
| RETURN_CONST | 1,883,940 | 5.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,890,300 | 99.9% |
| LOAD_CONST | 1,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,890,300 | 99.9% |
| LOAD_GLOBAL_BUILTIN | 1,800 | 0.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 62.5% |
| LOAD_ATTR | 60 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,172,400 | 43.8% |
| FOR_ITER_LIST | 4,831,080 | 34.3% |
| FOR_ITER | 3,087,960 | 21.9% |
| LOAD_GLOBAL_BUILTIN | 1,960 | 0.0% |
| POP_TOP | 1,800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,009,040 | 78.1% |
| LOAD_FAST_LOAD_FAST | 3,086,160 | 21.9% |
| LOAD_GLOBAL_BUILTIN | 1,960 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,886,700 | 100.0% |
| LOAD_GLOBAL | 100 | 0.0% |
| STORE_FAST | 80 | 0.0% |
| LOAD_FAST_CHECK | 40 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,886,760 | 100.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |
| COMPARE_OP | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,886,760 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,886,760 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,439,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 15,439,800 | 100.0% |


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
| specialization.deferred |         1800 | 0.0% |
|          hit |      9804060 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| string slice | 20 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     15439800 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6172380 | 100.0% |
|          hit |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.3% |
| Failure | 1,540 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract other | 760 | 49.4% |
| and other | 760 | 49.4% |
| multiply different types | 20 | 1.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3086340 | 17.3% |
|          hit |     14791740 | 82.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 18.0% |
| Failure | 820 | 82.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 760 | 92.7% |
| cfunc noargs | 60 | 7.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     26463120 | 70.6% |
|          hit |     11007000 | 29.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 6,480 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 6,460 | 99.7% |
| list | 20 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     18527760 | 32.8% |
|          hit |     38009340 | 67.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 4,520 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 4,520 | 100.0% |


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
| specialization.deferred |           20 | 0.0% |
|          hit |      1892260 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     15984220 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 100.0% |
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


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 215,268,480 | 46.0% |
| Not specialized | 143,441,300 | 30.7% |
| Specialized | 108,815,360 | 23.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| COMPARE_OP | 26,463,120 | 48.8% |
| FOR_ITER | 18,527,760 | 34.2% |
| BINARY_OP | 6,172,380 | 11.4% |
| CALL | 3,086,340 | 5.7% |
| BINARY_SUBSCR | 1,800 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 1,886,880 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 1,886,880 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,154,820 | 23.0% |
| Frees to freelist | 8,154,840 |  |
| Allocations | 27,315,020 | 77.0% |
| Allocations to 512 bytes | 24,228,740 | 68.3% |
| Allocations to 4 kbytes | 3,086,280 | 8.7% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 27,315,000 |  |
| New values | 0 |  |
| Interpreter increfs | 184,359,280 | 91.8% |
| Interpreter decrefs | 217,009,740 | 93.0% |
| Increfs | 16,512,700 | 8.2% |
| Decrefs | 16,245,500 | 7.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 20 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
| Method cache dunder hits | 1,800 |  |
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
| <= 1 | 0 |  |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

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
Stats gathered on: 2023-10-22
