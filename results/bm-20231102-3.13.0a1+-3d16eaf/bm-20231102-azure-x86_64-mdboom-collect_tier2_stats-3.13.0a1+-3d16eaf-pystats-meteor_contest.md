
# Pystats results

- benchmark: meteor_contest
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 76,726,280 | 15.7% | 15.7% |  |
| POP_JUMP_IF_TRUE | 45,842,800 | 9.4% | 25.1% |  |
| STORE_FAST | 45,408,180 | 9.3% | 34.4% |  |
| ENTER_EXECUTOR | 41,720,160 | 8.5% | 42.9% |  |
| LOAD_FAST_LOAD_FAST | 41,285,260 | 8.5% | 51.4% |  |
| COMPARE_OP | 35,293,140 | 7.2% | 58.6% |  |
| FOR_ITER | 24,710,020 | 5.1% | 63.7% |  |
| LOAD_CONST | 21,507,680 | 4.4% | 68.1% |  |
| JUMP_BACKWARD | 20,588,180 | 4.2% | 72.3% |  |
| STORE_SUBSCR_LIST_INT | 20,586,380 | 4.2% | 76.5% |  |
| LOAD_GLOBAL_BUILTIN | 18,796,020 | 3.8% | 80.4% |  |
| CALL_LEN | 14,676,100 | 3.0% | 83.4% |  |
| COMPARE_OP_INT | 14,675,920 | 3.0% | 86.4% |  |
| GET_ITER | 9,149,000 | 1.9% | 88.2% |  |
| BINARY_SUBSCR_LIST_INT | 9,146,460 | 1.9% | 90.1% |  |
| BINARY_OP | 8,232,300 | 1.7% | 91.8% |  |
| BINARY_SLICE | 6,632,880 | 1.4% | 93.2% |  |
| POP_TOP | 5,040,000 | 1.0% | 94.2% |  |
| FOR_ITER_LIST | 5,033,200 | 1.0% | 95.2% |  |
| POP_JUMP_IF_FALSE | 4,117,360 | 0.8% | 96.1% |  |
| CALL | 4,117,220 | 0.8% | 96.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 2,522,720 | 0.5% | 97.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,517,960 | 0.5% | 97.9% |  |
| LOAD_GLOBAL_MODULE | 2,515,880 | 0.5% | 98.4% |  |
| RESUME_CHECK | 2,515,780 | 0.5% | 99.0% |  |
| RETURN_CONST | 2,515,680 | 0.5% | 99.5% |  |
| CALL_PY_WITH_DEFAULTS | 2,515,640 | 0.5% | 100.0% |  |
| PUSH_NULL | 5,200 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 4,760 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 2,680 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 2,620 | 0.0% | 100.0% |  |
| BUILD_SLICE | 2,400 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 840 | 0.0% | 100.0% |  |
| LOAD_ATTR | 280 | 0.0% | 100.0% |  |
| BUILD_LIST | 240 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 180 | 0.0% | 100.0% |  |
| RETURN_VALUE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 140 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |  |
| RESUME | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 39,204,800 | 8.0% | 8.0% |
| COMPARE_OP POP_JUMP_IF_TRUE | 35,284,140 | 7.2% | 15.3% |
| ENTER_EXECUTOR COMPARE_OP | 32,877,980 | 6.7% | 22.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 29,732,640 | 6.1% | 28.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 25,508,460 | 5.2% | 33.3% |
| FOR_ITER STORE_FAST | 20,586,460 | 4.2% | 37.5% |
| JUMP_BACKWARD FOR_ITER | 20,586,420 | 4.2% | 41.7% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 20,586,380 | 4.2% | 45.9% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 20,586,360 | 4.2% | 50.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 14,678,540 | 3.0% | 53.2% |
| STORE_FAST LOAD_FAST | 11,669,400 | 2.4% | 55.5% |
| LOAD_FAST CALL_LEN | 10,561,120 | 2.2% | 57.7% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 10,558,660 | 2.2% | 59.9% |
| LOAD_FAST GET_ITER | 9,149,000 | 1.9% | 61.7% |
| CALL_LEN LOAD_CONST | 8,232,120 | 1.7% | 63.4% |
| LOAD_CONST COMPARE_OP_INT | 8,232,080 | 1.7% | 65.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 8,229,760 | 1.7% | 66.8% |
| LOAD_CONST LOAD_CONST | 6,637,680 | 1.4% | 68.2% |
| LOAD_FAST LOAD_CONST | 6,635,360 | 1.4% | 69.5% |
| BINARY_SLICE STORE_FAST | 6,632,880 | 1.4% | 70.9% |
| LOAD_CONST BINARY_SLICE | 6,632,880 | 1.4% | 72.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,632,880 | 1.4% | 73.6% |
| CALL_LEN LOAD_FAST | 6,443,800 | 1.3% | 74.9% |
| LOAD_FAST COMPARE_OP_INT | 6,443,760 | 1.3% | 76.2% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 6,330,280 | 1.3% | 77.5% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 5,031,600 | 1.0% | 78.6% |
| GET_ITER FOR_ITER_LIST | 5,031,560 | 1.0% | 79.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 5,031,560 | 1.0% | 80.6% |
| LOAD_FAST LOAD_FAST_LOAD_FAST | 5,031,280 | 1.0% | 81.6% |
| FOR_ITER_LIST STORE_FAST | 4,922,020 | 1.0% | 82.7% |
| GET_ITER FOR_ITER | 4,117,380 | 0.8% | 83.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 4,117,260 | 0.8% | 84.3% |
| FOR_ITER LOAD_GLOBAL_BUILTIN | 4,117,240 | 0.8% | 85.2% |
| LOAD_FAST CALL | 4,115,480 | 0.8% | 86.0% |
| CALL STORE_FAST | 4,115,040 | 0.8% | 86.9% |
| BINARY_OP STORE_FAST | 4,114,980 | 0.8% | 87.7% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 4,114,880 | 0.8% | 88.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 4,114,880 | 0.8% | 89.4% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 4,114,860 | 0.8% | 90.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 4,114,860 | 0.8% | 91.1% |
| BINARY_OP CALL_LEN | 4,114,840 | 0.8% | 91.9% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 4,114,840 | 0.8% | 92.8% |
| LOAD_FAST LOAD_FAST | 2,520,400 | 0.5% | 93.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,520,340 | 0.5% | 93.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 2,520,280 | 0.5% | 94.3% |
| RETURN_CONST POP_TOP | 2,515,680 | 0.5% | 94.8% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 2,515,660 | 0.5% | 95.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 2,515,640 | 0.5% | 95.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,515,640 | 0.5% | 96.4% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 2,515,600 | 0.5% | 96.9% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 2,515,580 | 0.5% | 97.4% |
| POP_TOP LOAD_GLOBAL_MODULE | 2,515,560 | 0.5% | 97.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 2,515,560 | 0.5% | 98.4% |
| POP_TOP ENTER_EXECUTOR | 2,515,260 | 0.5% | 99.0% |
| ENTER_EXECUTOR RETURN_CONST | 2,511,880 | 0.5% | 99.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 2,406,100 | 0.5% | 100.0% |
| FOR_ITER_LIST LOAD_GLOBAL_BUILTIN | 111,120 | 0.0% | 100.0% |
| COMPARE_OP COMPARE_OP | 8,820 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER | 6,220 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 4,960 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 4,800 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS LOAD_FAST | 4,760 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 4,760 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,720 | 0.0% | 100.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 4,720 | 0.0% | 100.0% |
| POP_TOP RETURN_CONST | 3,760 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE POP_TOP | 3,760 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 2,520 | 0.0% | 100.0% |
| BINARY_SUBSCR STORE_FAST | 2,440 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 2,420 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 2,400 | 0.0% | 100.0% |
| BUILD_SLICE BINARY_SUBSCR | 2,400 | 0.0% | 100.0% |
| LOAD_CONST BUILD_SLICE | 2,400 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 2,400 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,400 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_O STORE_FAST | 2,380 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 2,360 | 0.0% | 100.0% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 2,360 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_METHOD_DESCRIPTOR_O | 2,360 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_BUILTIN | 2,360 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 1,600 | 0.0% | 100.0% |
| CALL CALL | 1,360 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 1,360 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 420 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 300 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 240 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_FAST | 220 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 180 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 180 | 0.0% | 100.0% |
| CALL LOAD_FAST | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 100.0% |
| CALL POP_TOP | 140 | 0.0% | 100.0% |
| CALL CALL_LEN | 140 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 100 | 0.0% | 100.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 100 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,632,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,632,880 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 2,400 | 91.6% |
| BINARY_SUBSCR | 100 | 3.8% |
| LOAD_FAST_LOAD_FAST | 80 | 3.1% |
| LOAD_FAST | 40 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,440 | 93.1% |
| BINARY_SUBSCR | 100 | 3.8% |
| BINARY_SUBSCR_LIST_INT | 60 | 2.3% |
| BINARY_OP | 20 | 0.8% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,149,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,031,560 | 55.0% |
| FOR_ITER | 4,117,380 | 45.0% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,515,680 | 49.9% |
| CALL_METHOD_DESCRIPTOR_O | 2,515,580 | 49.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,760 | 0.1% |
| POP_JUMP_IF_TRUE | 3,760 | 0.1% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,515,560 | 49.9% |
| ENTER_EXECUTOR | 2,515,260 | 49.9% |
| RETURN_CONST | 3,760 | 0.1% |
| LOAD_FAST | 2,400 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 2,360 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800 | 92.3% |
| LOAD_ATTR_MODULE | 180 | 3.5% |
| LOAD_DEREF | 160 | 3.1% |
| LOAD_ATTR | 60 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,960 | 95.4% |
| CALL | 240 | 4.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 50.0% |
| LOAD_GLOBAL | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20 | 50.0% |
| STORE_SUBSCR_LIST_INT | 20 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,114,880 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 4,114,860 | 50.0% |
| BINARY_OP | 2,420 | 0.0% |
| CALL_LEN | 60 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,114,980 | 50.0% |
| CALL_LEN | 4,114,840 | 50.0% |
| BINARY_OP | 2,420 | 0.0% |
| CALL | 40 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 33.3% |
| LOAD_FAST | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |
| LOAD_GLOBAL | 40 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 16.7% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 2,400 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,115,480 | 100.0% |
| CALL | 1,360 | 0.0% |
| PUSH_NULL | 240 | 0.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,115,040 | 99.9% |
| CALL | 1,360 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| POP_TOP | 140 | 0.0% |
| CALL_LEN | 140 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| RESUME_CHECK | 60 | 37.5% |
| RESUME | 20 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 32,877,980 | 93.2% |
| LOAD_FAST_LOAD_FAST | 2,406,100 | 6.8% |
| COMPARE_OP | 8,820 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 35,284,140 | 100.0% |
| COMPARE_OP | 8,820 | 0.0% |
| POP_JUMP_IF_FALSE | 100 | 0.0% |
| COMPARE_OP_INT | 80 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 39,204,800 | 94.0% |
| POP_TOP | 2,515,260 | 6.0% |
| JUMP_BACKWARD | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 32,877,980 | 78.8% |
| LOAD_GLOBAL_BUILTIN | 6,330,280 | 15.2% |
| RETURN_CONST | 2,511,880 | 6.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,586,420 | 83.3% |
| GET_ITER | 4,117,380 | 16.7% |
| FOR_ITER | 6,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,586,460 | 83.3% |
| LOAD_GLOBAL_BUILTIN | 4,117,240 | 16.7% |
| FOR_ITER | 6,220 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| FOR_ITER_LIST | 40 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 20,586,380 | 100.0% |
| POP_JUMP_IF_TRUE | 1,360 | 0.0% |
| POP_TOP | 420 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20,586,420 | 100.0% |
| FOR_ITER_LIST | 1,600 | 0.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 42.9% |
| LOAD_GLOBAL | 60 | 21.4% |
| LOAD_GLOBAL_MODULE | 60 | 21.4% |
| LOAD_CONST | 40 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 80 | 28.6% |
| PUSH_NULL | 60 | 21.4% |
| LOAD_FAST | 60 | 21.4% |
| LOAD_ATTR_MODULE | 60 | 21.4% |
| LOAD_GLOBAL | 20 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 8,232,120 | 38.3% |
| LOAD_CONST | 6,637,680 | 30.9% |
| LOAD_FAST | 6,635,360 | 30.9% |
| POP_JUMP_IF_FALSE | 2,400 | 0.0% |
| STORE_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 8,232,080 | 38.3% |
| LOAD_CONST | 6,637,680 | 30.9% |
| BINARY_SLICE | 6,632,880 | 30.8% |
| BUILD_SLICE | 2,400 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 2,360 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| BUILD_LIST | 80 | 33.3% |
| RESUME_CHECK | 60 | 25.0% |
| RESUME | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 66.7% |
| LIST_EXTEND | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 29,732,640 | 38.8% |
| LOAD_GLOBAL_BUILTIN | 14,678,540 | 19.1% |
| STORE_FAST | 11,669,400 | 15.2% |
| POP_JUMP_IF_TRUE | 6,632,880 | 8.6% |
| CALL_LEN | 6,443,800 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 20,586,360 | 26.8% |
| CALL_LEN | 10,561,120 | 13.8% |
| GET_ITER | 9,149,000 | 11.9% |
| LOAD_CONST | 6,635,360 | 8.6% |
| COMPARE_OP_INT | 6,443,760 | 8.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 50.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 25,508,460 | 61.8% |
| LOAD_FAST | 5,031,280 | 12.2% |
| POP_JUMP_IF_FALSE | 4,114,880 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 4,114,860 | 10.0% |
| RESUME_CHECK | 2,515,660 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,732,640 | 72.0% |
| BINARY_SUBSCR_LIST_INT | 5,031,560 | 12.2% |
| BINARY_OP | 4,114,880 | 10.0% |
| COMPARE_OP | 2,406,100 | 5.8% |
| BINARY_SUBSCR | 80 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 28.6% |
| LOAD_GLOBAL | 100 | 11.9% |
| LOAD_GLOBAL_BUILTIN | 100 | 11.9% |
| POP_TOP | 80 | 9.5% |
| RETURN_VALUE | 40 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300 | 35.7% |
| LOAD_FAST | 220 | 26.2% |
| LOAD_GLOBAL_MODULE | 120 | 14.3% |
| LOAD_GLOBAL | 100 | 11.9% |
| LOAD_ATTR | 60 | 7.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 4,117,260 | 100.0% |
| COMPARE_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,114,880 | 99.9% |
| LOAD_CONST | 2,400 | 0.1% |
| LOAD_FAST | 80 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 35,284,140 | 77.0% |
| COMPARE_OP_INT | 10,558,660 | 23.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 39,204,800 | 85.5% |
| LOAD_FAST | 6,632,880 | 14.5% |
| POP_TOP | 3,760 | 0.0% |
| JUMP_BACKWARD | 1,360 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,511,880 | 99.8% |
| POP_TOP | 3,760 | 0.1% |
| FOR_ITER_LIST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,515,680 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20,586,460 | 45.3% |
| BINARY_SLICE | 6,632,880 | 14.6% |
| BINARY_SUBSCR_LIST_INT | 5,031,600 | 11.1% |
| FOR_ITER_LIST | 4,922,020 | 10.8% |
| CALL | 4,115,040 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 25,508,460 | 56.2% |
| LOAD_FAST | 11,669,400 | 25.7% |
| LOAD_GLOBAL_BUILTIN | 8,229,760 | 18.1% |
| LOAD_GLOBAL | 240 | 0.0% |
| BUILD_LIST | 80 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 33.3% |
| CALL_FUNCTION_EX | 20 | 33.3% |
| COPY_FREE_VARS | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 20 | 33.3% |
| LOAD_FAST_LOAD_FAST | 20 | 33.3% |
| LOAD_GLOBAL | 20 | 33.3% |


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
| LOAD_FAST_LOAD_FAST | 5,031,560 | 55.0% |
| LOAD_FAST | 4,114,840 | 45.0% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,031,600 | 55.0% |
| BINARY_OP | 4,114,860 | 45.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,400 | 89.6% |
| CALL | 120 | 4.5% |
| CALL_BUILTIN_CLASS | 80 | 3.0% |
| CALL_LEN | 80 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 2,360 | 88.1% |
| STORE_FAST | 180 | 6.7% |
| CALL_BUILTIN_CLASS | 80 | 3.0% |
| CALL | 60 | 2.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,720 | 99.2% |
| CALL | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,760 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,561,120 | 72.0% |
| BINARY_OP | 4,114,840 | 28.0% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,232,120 | 56.1% |
| LOAD_FAST | 6,443,800 | 43.9% |
| CALL_BUILTIN_CLASS | 80 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,720 | 99.2% |
| CALL | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,760 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,515,560 | 99.9% |
| CALL_BUILTIN_CLASS | 2,360 | 0.1% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,515,580 | 99.9% |
| STORE_FAST | 2,380 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,515,600 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,515,640 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,232,080 | 56.1% |
| LOAD_FAST | 6,443,760 | 43.9% |
| COMPARE_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 10,558,660 | 71.9% |
| POP_JUMP_IF_FALSE | 4,117,260 | 28.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,031,560 | 100.0% |
| JUMP_BACKWARD | 1,600 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,922,020 | 97.8% |
| LOAD_GLOBAL_BUILTIN | 111,120 | 2.2% |
| RETURN_CONST | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 42.9% |
| JUMP_BACKWARD | 60 | 42.9% |
| FOR_ITER | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 42.9% |
| LOAD_GLOBAL | 40 | 28.6% |
| LOAD_GLOBAL_MODULE | 40 | 28.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,520,280 | 99.9% |
| LOAD_CONST | 2,360 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,520,340 | 99.9% |
| LOAD_GLOBAL_BUILTIN | 2,360 | 0.1% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| LOAD_ATTR | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,229,760 | 43.8% |
| ENTER_EXECUTOR | 6,330,280 | 33.7% |
| FOR_ITER | 4,117,240 | 21.9% |
| FOR_ITER_LIST | 111,120 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 2,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,678,540 | 78.1% |
| LOAD_FAST_LOAD_FAST | 4,114,860 | 21.9% |
| LOAD_GLOBAL_BUILTIN | 2,520 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,515,560 | 100.0% |
| LOAD_GLOBAL | 120 | 0.0% |
| STORE_FAST | 80 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| LOAD_FAST_CHECK | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,515,640 | 100.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 2,515,640 | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,515,660 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,586,360 | 100.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,586,380 | 100.0% |


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
|     deferred | 8,229,860 | 100.0% |
|          hit | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.8% |
| Failure | 2,420 | 99.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and other | 1,200 | 49.6% |
| subtract other | 1,200 | 49.6% |
| multiply different types | 20 | 0.8% |


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
|     deferred | 2,460 | 0.0% |
|          hit | 9,146,460 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 37.5% |
| Failure | 100 | 62.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| string slice | 100 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,115,540 | 17.3% |
|          hit | 19,721,900 | 82.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 25.0% |
| Failure | 1,260 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 1,200 | 95.2% |
| cfunc noargs | 60 | 4.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 35,284,240 | 70.6% |
|          hit | 14,675,920 | 29.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 0.9% |
| Failure | 8,820 | 99.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 8,800 | 99.8% |
| list | 20 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 24,703,740 | 83.1% |
|          hit | 5,033,340 | 16.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 1.0% |
| Failure | 6,220 | 99.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 6,220 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 140 | 0.0% |
|          hit | 2,522,900 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 420 | 0.0% |
|          hit | 21,311,900 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 100.0% |
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
|     deferred | 20 | 0.0% |
|          hit | 20,586,380 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 263,949,280 | 54.0% |
| Not specialized | 128,949,500 | 26.4% |
| Specialized hits | 95,514,640 | 19.6% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| COMPARE_OP | 35,284,240 | 48.8% |
| FOR_ITER | 24,703,740 | 34.2% |
| BINARY_OP | 8,229,860 | 11.4% |
| CALL | 4,115,540 | 5.7% |
| BINARY_SUBSCR | 2,460 | 0.0% |
| LOAD_GLOBAL | 420 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |


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
| Calls to Python functions inlined | 2,515,840 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 2,515,640 | 100.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 10,872,960 | 23.0% |
| Frees to freelist | 10,873,140 |  |
| Allocations | 36,420,280 | 77.0% |
| Allocations to 512 bytes | 32,305,220 | 68.3% |
| Allocations to 4 kbytes | 4,115,060 | 8.7% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 36,420,000 |  |
| New values | 0 |  |
| Interpreter increfs | 287,532,340 | 92.9% |
| Interpreter decrefs | 331,066,500 | 93.9% |
| Increfs | 22,017,260 | 7.1% |
| Decrefs | 21,660,800 | 6.1% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 185 |  |
| Method cache misses | 35 |  |
| Method cache collisions | 46 |  |
| Method cache dunder hits | 2,389 |  |
| Method cache dunder misses | 11 |  |


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
| Optimization attempts | 1,211,060 |  |
| Traces created | 100 | 0.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 1,210,960 | 100.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 41,720,160 |  |
| Uops executed | 445,632,900 | 10.68 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 80 | 80.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 20.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 80 | 80.0% |
| <= 32 | 20 | 20.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 8,768,280 | 21.0% |
| <= 16 | 29,026,320 | 69.6% |
| <= 32 | 3,925,560 | 9.4% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 1,210,960 |
| COMPARE_OP | 100 |


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
Stats gathered on: 2023-11-02
