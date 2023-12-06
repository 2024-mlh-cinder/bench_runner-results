
# Pystats results

- benchmark: meteor_contest
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 57,544,500 | 19.3% | 19.3% |  |
| STORE_FAST | 34,054,920 | 11.4% | 30.8% |  |
| LOAD_FAST_LOAD_FAST | 30,962,940 | 10.4% | 41.2% |  |
| FOR_ITER | 18,532,280 | 6.2% | 47.4% |  |
| LOAD_CONST | 16,130,760 | 5.4% | 52.8% |  |
| JUMP_BACKWARD | 15,439,860 | 5.2% | 58.0% |  |
| STORE_SUBSCR_LIST_INT | 15,439,800 | 5.2% | 63.2% |  |
| LOAD_GLOBAL_BUILTIN | 14,097,240 | 4.7% | 67.9% |  |
| ENTER_EXECUTOR | 11,997,540 | 4.0% | 72.0% |  |
| CALL_LEN | 11,007,180 | 3.7% | 75.7% |  |
| COMPARE_OP_INT | 11,007,000 | 3.7% | 79.3% |  |
| POP_JUMP_IF_TRUE | 9,722,820 | 3.3% | 82.6% |  |
| GET_ITER | 6,861,540 | 2.3% | 84.9% |  |
| BINARY_SUBSCR_LIST_INT | 6,859,680 | 2.3% | 87.2% |  |
| BINARY_OP | 6,173,940 | 2.1% | 89.3% |  |
| BINARY_SLICE | 4,974,660 | 1.7% | 91.0% |  |
| POP_TOP | 3,780,000 | 1.3% | 92.2% |  |
| FOR_ITER_LIST | 3,773,520 | 1.3% | 93.5% |  |
| POP_JUMP_IF_FALSE | 3,088,020 | 1.0% | 94.5% |  |
| CALL | 3,087,340 | 1.0% | 95.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,892,100 | 0.6% | 96.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,888,500 | 0.6% | 96.9% |  |
| LOAD_GLOBAL_MODULE | 1,886,980 | 0.6% | 97.5% |  |
| RESUME_CHECK | 1,886,880 | 0.6% | 98.1% |  |
| RETURN_CONST | 1,886,760 | 0.6% | 98.8% |  |
| CALL_PY_WITH_DEFAULTS | 1,886,760 | 0.6% | 99.4% |  |
| COMPARE_OP | 1,804,300 | 0.6% | 100.0% |  |
| PUSH_NULL | 3,900 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,600 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,600 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 2,100 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 1,820 | 0.0% | 100.0% |  |
| BUILD_SLICE | 1,800 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 280 | 0.0% | 100.0% |  |
| BUILD_LIST | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| RETURN_VALUE | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST_LOAD_FAST LOAD_FAST | 22,299,480 | 7.5% | 7.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 19,130,340 | 6.4% | 13.9% |
| FOR_ITER STORE_FAST | 15,439,800 | 5.2% | 19.1% |
| JUMP_BACKWARD FOR_ITER | 15,439,800 | 5.2% | 24.3% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 15,439,800 | 5.2% | 29.5% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 15,439,800 | 5.2% | 34.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,009,040 | 3.7% | 38.4% |
| STORE_FAST LOAD_FAST | 8,751,840 | 2.9% | 41.3% |
| LOAD_FAST CALL_LEN | 7,920,960 | 2.7% | 44.0% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 7,919,040 | 2.7% | 46.6% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 7,635,540 | 2.6% | 49.2% |
| LOAD_FAST GET_ITER | 6,861,540 | 2.3% | 51.5% |
| LOAD_CONST COMPARE_OP_INT | 6,174,120 | 2.1% | 53.6% |
| CALL_LEN LOAD_CONST | 6,174,120 | 2.1% | 55.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 6,172,400 | 2.1% | 57.7% |
| LOAD_CONST LOAD_CONST | 4,978,260 | 1.7% | 59.4% |
| LOAD_FAST LOAD_CONST | 4,976,520 | 1.7% | 61.1% |
| BINARY_SLICE STORE_FAST | 4,974,660 | 1.7% | 62.7% |
| LOAD_CONST BINARY_SLICE | 4,974,660 | 1.7% | 64.4% |
| LOAD_FAST COMPARE_OP_INT | 4,832,880 | 1.6% | 66.0% |
| CALL_LEN LOAD_FAST | 4,832,880 | 1.6% | 67.6% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 4,748,100 | 1.6% | 69.2% |
| GET_ITER FOR_ITER_LIST | 3,773,520 | 1.3% | 70.5% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 3,773,520 | 1.3% | 71.8% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,773,520 | 1.3% | 73.0% |
| LOAD_FAST LOAD_FAST_LOAD_FAST | 3,773,460 | 1.3% | 74.3% |
| FOR_ITER_LIST STORE_FAST | 3,690,540 | 1.2% | 75.6% |
| GET_ITER FOR_ITER | 3,087,960 | 1.0% | 76.6% |
| FOR_ITER LOAD_GLOBAL_BUILTIN | 3,087,960 | 1.0% | 77.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,087,960 | 1.0% | 78.7% |
| LOAD_FAST CALL | 3,086,260 | 1.0% | 79.7% |
| BINARY_OP STORE_FAST | 3,086,220 | 1.0% | 80.7% |
| CALL STORE_FAST | 3,086,220 | 1.0% | 81.8% |
| BINARY_OP CALL_LEN | 3,086,160 | 1.0% | 82.8% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 3,086,160 | 1.0% | 83.8% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 3,086,160 | 1.0% | 84.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 3,086,160 | 1.0% | 85.9% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 3,086,160 | 1.0% | 87.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 3,086,160 | 1.0% | 88.0% |
| ENTER_EXECUTOR LOAD_FAST | 2,890,200 | 1.0% | 89.0% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 2,475,300 | 0.8% | 89.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,084,460 | 0.7% | 90.5% |
| LOAD_FAST LOAD_FAST | 1,890,300 | 0.6% | 91.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,890,300 | 0.6% | 91.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,890,300 | 0.6% | 92.4% |
| RETURN_CONST POP_TOP | 1,886,760 | 0.6% | 93.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,886,760 | 0.6% | 93.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,886,760 | 0.6% | 94.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 1,886,760 | 0.6% | 94.9% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,886,740 | 0.6% | 95.6% |
| POP_TOP ENTER_EXECUTOR | 1,886,700 | 0.6% | 96.2% |
| POP_TOP LOAD_GLOBAL_MODULE | 1,886,700 | 0.6% | 96.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,886,700 | 0.6% | 97.5% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 1,886,700 | 0.6% | 98.1% |
| ENTER_EXECUTOR RETURN_CONST | 1,883,940 | 0.6% | 98.7% |
| COMPARE_OP POP_JUMP_IF_TRUE | 1,803,780 | 0.6% | 99.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 1,803,780 | 0.6% | 100.0% |
| FOR_ITER_LIST LOAD_GLOBAL_BUILTIN | 82,980 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER | 4,520 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 3,720 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 3,600 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,600 | 0.0% | 100.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 3,600 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS LOAD_FAST | 3,600 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 3,600 | 0.0% | 100.0% |
| POP_TOP RETURN_CONST | 2,820 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE POP_TOP | 2,820 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 1,960 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 1,840 | 0.0% | 100.0% |
| BINARY_SUBSCR STORE_FAST | 1,800 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 1,800 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 1,800 | 0.0% | 100.0% |
| BUILD_SLICE BINARY_SUBSCR | 1,800 | 0.0% | 100.0% |
| LOAD_CONST BUILD_SLICE | 1,800 | 0.0% | 100.0% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 1,800 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,800 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_METHOD_DESCRIPTOR_O | 1,800 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_O STORE_FAST | 1,800 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_BUILTIN | 1,800 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 1,540 | 0.0% | 100.0% |
| CALL CALL | 820 | 0.0% | 100.0% |
| COMPARE_OP COMPARE_OP | 460 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 160 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| CALL_LEN CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP POP_TOP | 60 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 60 | 0.0% | 100.0% |


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
| LOAD_FAST | 6,861,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,773,520 | 55.0% |
| FOR_ITER | 3,087,960 | 45.0% |
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
| ENTER_EXECUTOR | 1,886,700 | 49.9% |
| LOAD_GLOBAL_MODULE | 1,886,700 | 49.9% |
| RETURN_CONST | 2,820 | 0.1% |
| LOAD_FAST | 1,800 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,800 | 0.0% |


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
| LOAD_CONST | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
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
| CALL_BUILTIN_CLASS | 40 | 0.0% |
| CALL_LEN | 40 | 0.0% |

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
| CALL_INTRINSIC_1 | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


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
| LOAD_FAST_LOAD_FAST | 1,803,780 | 100.0% |
| COMPARE_OP | 460 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,803,780 | 100.0% |
| COMPARE_OP | 460 | 0.0% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,635,540 | 63.6% |
| ENTER_EXECUTOR | 2,475,300 | 20.6% |
| POP_TOP | 1,886,700 | 15.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,748,100 | 39.6% |
| LOAD_FAST | 2,890,200 | 24.1% |
| ENTER_EXECUTOR | 2,475,300 | 20.6% |
| RETURN_CONST | 1,883,940 | 15.7% |


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
| STORE_SUBSCR_LIST_INT | 15,439,800 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 15,439,800 | 100.0% |
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
| BUILD_SLICE | 1,800 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,800 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |
| RESUME_CHECK | 60 | 33.3% |

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
| LOAD_FAST_LOAD_FAST | 22,299,480 | 38.8% |
| LOAD_GLOBAL_BUILTIN | 11,009,040 | 19.1% |
| STORE_FAST | 8,751,840 | 15.2% |
| CALL_LEN | 4,832,880 | 8.4% |
| ENTER_EXECUTOR | 2,890,200 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 15,439,800 | 26.8% |
| CALL_LEN | 7,920,960 | 13.8% |
| GET_ITER | 6,861,540 | 11.9% |
| LOAD_CONST | 4,976,520 | 8.6% |
| COMPARE_OP_INT | 4,832,880 | 8.4% |


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
| STORE_FAST | 19,130,340 | 61.8% |
| LOAD_FAST | 3,773,460 | 12.2% |
| POP_JUMP_IF_FALSE | 3,086,160 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 3,086,160 | 10.0% |
| RESUME_CHECK | 1,886,760 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,299,480 | 72.0% |
| BINARY_SUBSCR_LIST_INT | 3,773,520 | 12.2% |
| BINARY_OP | 3,086,160 | 10.0% |
| COMPARE_OP | 1,803,780 | 5.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 80 | 28.6% |
| RETURN_VALUE | 40 | 14.3% |
| BUILD_LIST | 20 | 7.1% |
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
| COMPARE_OP_INT | 7,919,040 | 81.4% |
| COMPARE_OP | 1,803,780 | 18.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,635,540 | 78.5% |
| LOAD_FAST | 2,084,460 | 21.4% |
| POP_TOP | 2,820 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,883,940 | 99.9% |
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
| FOR_ITER | 15,439,800 | 45.3% |
| BINARY_SLICE | 4,974,660 | 14.6% |
| BINARY_SUBSCR_LIST_INT | 3,773,520 | 11.1% |
| FOR_ITER_LIST | 3,690,540 | 10.8% |
| BINARY_OP | 3,086,220 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,130,340 | 56.2% |
| LOAD_FAST | 8,751,840 | 25.7% |
| LOAD_GLOBAL_BUILTIN | 6,172,400 | 18.1% |
| LOAD_GLOBAL | 80 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 3,773,520 | 55.0% |
| LOAD_FAST | 3,086,160 | 45.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,773,520 | 55.0% |
| BINARY_OP | 3,086,160 | 45.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,840 | 87.6% |
| CALL | 100 | 4.8% |
| CALL_BUILTIN_CLASS | 80 | 3.8% |
| CALL_LEN | 80 | 3.8% |

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
| GET_ITER | 3,773,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,690,540 | 97.8% |
| LOAD_GLOBAL_BUILTIN | 82,980 | 2.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 50.0% |
| JUMP_BACKWARD | 60 | 50.0% |

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
| ENTER_EXECUTOR | 4,748,100 | 33.7% |
| FOR_ITER | 3,087,960 | 21.9% |
| FOR_ITER_LIST | 82,980 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 1,960 | 0.0% |

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
| COMPARE_OP | 60 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,886,760 | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

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

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,172,380 | 100.0% |
|          hit | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.3% |
| Failure | 1,540 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and other | 760 | 49.4% |
| subtract other | 760 | 49.4% |
| multiply different types | 20 | 1.3% |


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
|     deferred | 1,800 | 0.0% |
|          hit | 6,859,680 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| string slice | 20 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,086,340 | 17.3% |
|          hit | 14,791,740 | 82.7% |

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
|---|---:|---:|
|     deferred | 1,803,840 | 14.1% |
|          hit | 11,007,000 | 85.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 460 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 440 | 95.7% |
| list | 20 | 4.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 18,527,760 | 83.1% |
|          hit | 3,773,640 | 16.9% |

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


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 1,892,260 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 15,984,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 15,439,800 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 163,225,560 | 54.8% |
| Not specialized | 62,825,400 | 21.1% |
| Specialized | 71,635,280 | 24.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 18,527,760 | 62.6% |
| BINARY_OP | 6,172,380 | 20.9% |
| CALL | 3,086,340 | 10.4% |
| COMPARE_OP | 1,803,840 | 6.1% |
| BINARY_SUBSCR | 1,800 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>


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
| Frame objects created | 0 | 0.0% |
| Frames pushed | 1,886,880 | 100.0% |


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
| Interpreter increfs | 113,545,840 | 53.3% |
| Interpreter decrefs | 120,944,280 | 49.3% |
| Increfs | 99,323,680 | 46.7% |
| Decrefs | 124,308,500 | 50.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 18 |  |
| Method cache misses | 2 |  |
| Method cache collisions | 2 |  |
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

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 908,220 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 11,997,540 |  |
| Uops executed | 408,216,240 | 34.02 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 908,220 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,927,280 | 24.4% |
| <= 16 | 1,121,280 | 9.3% |
| <= 32 | 4,120,200 | 34.3% |
| <= 64 | 2,022,060 | 16.9% |
| <= 128 | 1,548,600 | 12.9% |
| <= 256 | 258,120 | 2.2% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 96,075,060 | 23.5% | 23.5% |  |
| _POP_JUMP_IF_TRUE | 58,894,980 | 14.4% | 38.0% |  |
| LOAD_FAST | 58,151,700 | 14.2% | 52.2% |  |
| _ITER_CHECK_LIST | 34,235,700 | 8.4% | 60.6% |  |
| _IS_ITER_EXHAUSTED_LIST | 34,235,700 | 8.4% | 69.0% |  |
| STORE_FAST | 30,548,040 | 7.5% | 76.5% |  |
| _ITER_NEXT_LIST | 27,603,660 | 6.8% | 83.2% |  |
| COMPARE_OP | 24,659,280 | 6.0% | 89.3% |  |
| _JUMP_TO_TOP | 19,293,780 | 4.7% | 94.0% |  |
| _EXIT_TRACE | 11,997,540 | 2.9% | 96.9% |  |
| POP_TOP | 6,632,040 | 1.6% | 98.6% |  |
| GET_ITER | 2,944,380 | 0.7% | 99.3% |  |
| BINARY_SUBSCR_LIST_INT | 2,944,380 | 0.7% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 908,220 |


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
Stats gathered on: 2023-10-09
