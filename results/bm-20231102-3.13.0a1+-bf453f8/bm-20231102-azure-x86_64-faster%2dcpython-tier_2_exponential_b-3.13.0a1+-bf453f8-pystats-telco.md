
# Pystats results

- benchmark: telco
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 80,039,880 | 39.4% | 39.4% |  |
| STORE_FAST | 35,222,920 | 17.3% | 56.7% |  |
| BINARY_OP | 24,021,100 | 11.8% | 68.5% |  |
| LOAD_CONST | 9,605,920 | 4.7% | 73.2% |  |
| CALL | 8,010,620 | 3.9% | 77.2% |  |
| POP_JUMP_IF_FALSE | 6,400,000 | 3.1% | 80.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,804,440 | 2.4% | 82.7% |  |
| LOAD_GLOBAL_MODULE | 3,202,340 | 1.6% | 84.3% |  |
| POP_TOP | 3,201,800 | 1.6% | 85.8% |  |
| LOAD_ATTR | 3,201,520 | 1.6% | 87.4% |  |
| COMPARE_OP | 3,200,980 | 1.6% | 89.0% |  |
| LOAD_GLOBAL_BUILTIN | 3,200,840 | 1.6% | 90.6% |  |
| CALL_KW | 3,200,080 | 1.6% | 92.1% |  |
| ENTER_EXECUTOR | 3,200,000 | 1.6% | 93.7% |  |
| BINARY_SUBSCR_LIST_INT | 3,199,980 | 1.6% | 95.3% |  |
| CALL_BUILTIN_FAST | 3,199,980 | 1.6% | 96.8% |  |
| TO_BOOL_INT | 3,199,980 | 1.6% | 98.4% |  |
| UNPACK_SEQUENCE_TUPLE | 3,199,980 | 1.6% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,580 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 2,520 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,320 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 1,040 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 920 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 800 | 0.0% | 100.0% |  |
| GET_ITER | 720 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 680 | 0.0% | 100.0% |  |
| PUSH_NULL | 560 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 300 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| RETURN_VALUE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 100 | 0.0% | 100.0% |  |
| BEFORE_WITH | 80 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| BUILD_LIST | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| FOR_ITER | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |
| TO_BOOL | 40 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |
| RESUME | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 32,020,280 | 15.7% | 15.7% |
| LOAD_FAST LOAD_FAST | 27,213,440 | 13.4% | 29.1% |
| LOAD_FAST BINARY_OP | 20,813,480 | 10.2% | 39.4% |
| BINARY_OP STORE_FAST | 20,813,440 | 10.2% | 49.6% |
| CALL STORE_FAST | 8,006,940 | 3.9% | 53.5% |
| LOAD_FAST CALL | 8,004,560 | 3.9% | 57.5% |
| LOAD_FAST LOAD_CONST | 6,401,040 | 3.1% | 60.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 4,804,440 | 2.4% | 63.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 4,804,400 | 2.4% | 65.4% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 3,201,860 | 1.6% | 66.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,200,640 | 1.6% | 68.5% |
| LOAD_FAST LOAD_ATTR | 3,200,320 | 1.6% | 70.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,200,100 | 1.6% | 71.7% |
| LOAD_CONST CALL_KW | 3,200,080 | 1.6% | 73.2% |
| LOAD_ATTR LOAD_FAST | 3,200,040 | 1.6% | 74.8% |
| BINARY_OP LOAD_FAST | 3,200,000 | 1.6% | 76.4% |
| CALL_KW POP_TOP | 3,200,000 | 1.6% | 77.9% |
| COMPARE_OP POP_JUMP_IF_FALSE | 3,200,000 | 1.6% | 79.5% |
| LOAD_CONST BINARY_OP | 3,200,000 | 1.6% | 81.1% |
| LOAD_CONST LOAD_FAST | 3,200,000 | 1.6% | 82.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 3,200,000 | 1.6% | 84.2% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,199,980 | 1.6% | 85.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,199,980 | 1.6% | 87.4% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 3,199,980 | 1.6% | 89.0% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 3,199,960 | 1.6% | 90.5% |
| LOAD_FAST CALL_BUILTIN_FAST | 3,199,960 | 1.6% | 92.1% |
| LOAD_FAST TO_BOOL_INT | 3,199,960 | 1.6% | 93.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 3,199,960 | 1.6% | 95.3% |
| CALL_BUILTIN_FAST UNPACK_SEQUENCE_TUPLE | 3,199,960 | 1.6% | 96.8% |
| POP_TOP ENTER_EXECUTOR | 3,199,660 | 1.6% | 98.4% |
| ENTER_EXECUTOR COMPARE_OP | 3,199,040 | 1.6% | 100.0% |
| BINARY_OP BINARY_OP | 7,620 | 0.0% | 100.0% |
| CALL CALL | 3,000 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_LAZY_DICT | 2,440 | 0.0% | 100.0% |
| LOAD_CONST CALL | 2,200 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_LAZY_DICT LOAD_CONST | 1,900 | 0.0% | 100.0% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 1,840 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 1,580 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,440 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 1,280 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR | 1,000 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,000 | 0.0% | 100.0% |
| COMPARE_OP COMPARE_OP | 980 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP | 960 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS GET_ITER | 680 | 0.0% | 100.0% |
| POP_TOP EXTENDED_ARG | 640 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 640 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 640 | 0.0% | 100.0% |
| LOAD_CONST CALL_BUILTIN_CLASS | 640 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 620 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 620 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_LAZY_DICT CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 480 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 360 | 0.0% | 100.0% |
| EXTENDED_ARG FOR_ITER_RANGE | 360 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| EXTENDED_ARG JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 340 | 0.0% | 100.0% |
| PUSH_NULL CALL | 320 | 0.0% | 100.0% |
| JUMP_BACKWARD EXTENDED_ARG | 320 | 0.0% | 100.0% |
| EXTENDED_ARG ENTER_EXECUTOR | 300 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 300 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 300 | 0.0% | 100.0% |
| ENTER_EXECUTOR CALL | 280 | 0.0% | 100.0% |
| CALL POP_TOP | 220 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_CONST | 200 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 200 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 160 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| CALL CALL_METHOD_DESCRIPTOR_FAST | 100 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 100 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 100 | 0.0% | 100.0% |
| BEFORE_WITH STORE_FAST | 80 | 0.0% | 100.0% |
| GET_ITER EXTENDED_ARG | 80 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 80 | 0.0% | 100.0% |
| POP_TOP NOP | 80 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 80 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 80 | 0.0% | 100.0% |
| CALL LOAD_FAST | 80 | 0.0% | 100.0% |
| CALL STORE_ATTR | 80 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |
| CALL_KW STORE_FAST | 80 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_METHOD_LAZY_DICT | 80 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 80 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |
| LOAD_FAST_CHECK CALL | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_CONST | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 50.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 680 | 94.4% |
| CALL | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 620 | 86.1% |
| EXTENDED_ARG | 80 | 11.1% |
| FOR_ITER | 20 | 2.8% |


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
| CALL_KW | 3,200,000 | 99.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,580 | 0.0% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,199,660 | 99.9% |
| EXTENDED_ARG | 640 | 0.0% |
| LOAD_FAST | 640 | 0.0% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 300 | 53.6% |
| LOAD_DEREF | 160 | 28.6% |
| LOAD_ATTR | 100 | 17.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 320 | 57.1% |
| LOAD_FAST | 160 | 28.6% |
| LOAD_FAST_CHECK | 80 | 14.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 50.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 37.5% |
| BINARY_OP | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 50.0% |
| LOAD_GLOBAL | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20 | 50.0% |
| TO_BOOL_INT | 20 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,813,480 | 86.6% |
| LOAD_CONST | 3,200,000 | 13.3% |
| BINARY_OP | 7,620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,813,440 | 86.6% |
| LOAD_FAST | 3,200,000 | 13.3% |
| BINARY_OP | 7,620 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,004,560 | 99.9% |
| CALL | 3,000 | 0.0% |
| LOAD_CONST | 2,200 | 0.0% |
| PUSH_NULL | 320 | 0.0% |
| ENTER_EXECUTOR | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,006,940 | 100.0% |
| CALL | 3,000 | 0.0% |
| POP_TOP | 220 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 100 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,200,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,200,000 | 100.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,199,040 | 99.9% |
| COMPARE_OP | 980 | 0.0% |
| LOAD_CONST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,200,000 | 100.0% |
| COMPARE_OP | 980 | 0.0% |


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
| POP_TOP | 3,199,660 | 100.0% |
| EXTENDED_ARG | 300 | 0.0% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,199,040 | 100.0% |
| LOAD_FAST | 640 | 0.0% |
| CALL | 280 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 640 | 61.5% |
| JUMP_BACKWARD | 320 | 30.8% |
| GET_ITER | 80 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 360 | 34.6% |
| JUMP_BACKWARD | 340 | 32.7% |
| ENTER_EXECUTOR | 300 | 28.8% |
| FOR_ITER | 40 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 40 | 50.0% |
| GET_ITER | 20 | 25.0% |
| JUMP_BACKWARD | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 50.0% |
| FOR_ITER_RANGE | 40 | 50.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 340 | 50.0% |
| EXTENDED_ARG | 340 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 320 | 47.1% |
| FOR_ITER_RANGE | 300 | 44.1% |
| ENTER_EXECUTOR | 40 | 5.9% |
| FOR_ITER | 20 | 2.9% |


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
| LOAD_FAST | 3,200,320 | 100.0% |
| LOAD_ATTR | 1,000 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |
| LOAD_GLOBAL_MODULE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,200,040 | 100.0% |
| LOAD_ATTR | 1,000 | 0.0% |
| PUSH_NULL | 100 | 0.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_ATTR_METHOD_LAZY_DICT | 80 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,401,040 | 66.6% |
| LOAD_GLOBAL_MODULE | 3,201,860 | 33.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 1,900 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 620 | 0.0% |
| LOAD_GLOBAL | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 3,200,080 | 33.3% |
| BINARY_OP | 3,200,000 | 33.3% |
| LOAD_FAST | 3,200,000 | 33.3% |
| CALL | 2,200 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,840 | 0.0% |


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
| STORE_FAST | 32,020,280 | 40.0% |
| LOAD_FAST | 27,213,440 | 34.0% |
| LOAD_ATTR_METHOD_NO_DICT | 4,804,440 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 3,200,100 | 4.0% |
| LOAD_ATTR | 3,200,040 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,213,440 | 34.0% |
| BINARY_OP | 20,813,480 | 26.0% |
| CALL | 8,004,560 | 10.0% |
| LOAD_CONST | 6,401,040 | 8.0% |
| LOAD_ATTR_METHOD_NO_DICT | 4,804,400 | 6.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 52.2% |
| POP_TOP | 80 | 8.7% |
| LOAD_GLOBAL | 80 | 8.7% |
| RETURN_VALUE | 40 | 4.3% |
| POP_JUMP_IF_FALSE | 40 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 340 | 37.0% |
| LOAD_CONST | 200 | 21.7% |
| LOAD_GLOBAL_BUILTIN | 120 | 13.0% |
| LOAD_ATTR | 100 | 10.9% |
| LOAD_GLOBAL | 80 | 8.7% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,200,000 | 50.0% |
| TO_BOOL_INT | 3,199,980 | 50.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,200,000 | 50.0% |
| LOAD_GLOBAL_MODULE | 3,199,960 | 50.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 80.0% |
| STORE_ATTR | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 40.0% |
| STORE_ATTR | 20 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 20,813,440 | 59.1% |
| CALL | 8,006,940 | 22.7% |
| BINARY_SUBSCR_LIST_INT | 3,199,980 | 9.1% |
| UNPACK_SEQUENCE_TUPLE | 3,199,980 | 9.1% |
| FOR_ITER_RANGE | 1,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,020,280 | 90.9% |
| LOAD_GLOBAL_BUILTIN | 3,200,640 | 9.1% |
| LOAD_GLOBAL_MODULE | 1,440 | 0.0% |
| LOAD_GLOBAL | 480 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 50.0% |
| CALL_BUILTIN_FAST | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 20 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 20 | 50.0% |
| COPY_FREE_VARS | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 20 | 50.0% |
| LOAD_GLOBAL | 20 | 50.0% |


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

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,199,960 | 100.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,199,980 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 640 | 80.0% |
| CALL | 80 | 10.0% |
| LOAD_FAST | 40 | 5.0% |
| CALL_BUILTIN_CLASS | 40 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 680 | 85.0% |
| STORE_FAST | 60 | 7.5% |
| CALL_BUILTIN_CLASS | 40 | 5.0% |
| CALL | 20 | 2.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,199,960 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 3,199,960 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BEFORE_WITH | 60 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,840 | 71.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 600 | 23.3% |
| CALL | 100 | 3.9% |
| LOAD_ATTR | 40 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,580 | 61.2% |
| STORE_FAST | 1,000 | 38.8% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 620 | 47.0% |
| EXTENDED_ARG | 360 | 27.3% |
| JUMP_BACKWARD | 300 | 22.7% |
| FOR_ITER | 40 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,280 | 97.0% |
| LOAD_GLOBAL | 40 | 3.0% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,440 | 96.8% |
| LOAD_ATTR | 80 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,900 | 75.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 23.8% |
| CALL | 20 | 0.8% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,804,400 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,804,440 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 200 | 66.7% |
| LOAD_ATTR | 100 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 300 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,200,640 | 100.0% |
| LOAD_GLOBAL | 120 | 0.0% |
| STORE_ATTR | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,200,100 | 100.0% |
| LOAD_CONST | 620 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,199,960 | 99.9% |
| STORE_FAST | 1,440 | 0.0% |
| POP_TOP | 360 | 0.0% |
| LOAD_GLOBAL | 340 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,201,860 | 100.0% |
| LOAD_ATTR_MODULE | 200 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| CALL | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,199,960 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,199,980 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,199,960 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,199,980 | 100.0% |


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
|     deferred | 24,013,460 | 100.0% |
|          hit | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.3% |
| Failure | 7,620 | 99.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 4,100 | 53.8% |
| multiply other | 1,560 | 20.5% |
| and int | 980 | 12.9% |
| multiply different types | 980 | 12.9% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 3,199,980 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,007,420 | 71.4% |
|          hit | 3,203,420 | 28.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 6.9% |
| Failure | 2,980 | 93.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs keywords | 1,560 | 52.3% |
| cfunc varargs | 1,000 | 33.6% |
| class no vectorcall | 340 | 11.4% |
| cfunc noargs | 80 | 2.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,200,000 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 980 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 980 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 2.9% |
|          hit | 1,320 | 94.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,200,300 | 40.0% |
|          hit | 4,807,260 | 60.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 18.0% |
| Failure | 1,000 | 82.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 980 | 98.0% |
| not managed dict | 20 | 2.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 460 | 0.0% |
|          hit | 6,403,180 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 460 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 80.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 3,199,980 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 3,199,980 | 100.0% |

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
| Basic | 134,474,760 | 66.1% |
| Not specialized | 44,835,440 | 22.1% |
| Specialized hits | 24,015,300 | 11.8% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 24,013,460 | 62.5% |
| CALL | 8,007,420 | 20.8% |
| LOAD_ATTR | 3,200,300 | 8.3% |
| COMPARE_OP | 3,200,000 | 8.3% |
| LOAD_GLOBAL | 460 | 0.0% |
| STORE_ATTR | 80 | 0.0% |
| FOR_ITER | 40 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |
| TO_BOOL | 20 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


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
| Calls to Python functions inlined | 160 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 100.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,408,060 | 20.8% |
| Frees to freelist | 14,408,040 |  |
| Allocations | 55,019,360 | 79.2% |
| Allocations to 512 bytes | 55,019,200 | 79.2% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 160 | 0.0% |
| Frees | 55,019,014 |  |
| New values | 200 |  |
| Interpreter increfs | 103,118,800 | 38.2% |
| Interpreter decrefs | 144,577,320 | 43.0% |
| Increfs | 166,493,312 | 61.8% |
| Decrefs | 191,258,766 | 57.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,602,143 |  |
| Method cache misses | 217 |  |
| Method cache collisions | 162 |  |
| Method cache dunder hits | 232 |  |
| Method cache dunder misses | 8 |  |


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
| Optimization attempts | 40 |  |
| Traces created | 40 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 3,200,000 |  |
| Uops executed | 60,792,400 | 19.00 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 40 | 100.0% |


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
| <= 16 | 0 | 0.0% |
| <= 32 | 40 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 680 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 3,199,320 | 100.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 12,798,920 | 21.1% | 21.1% |  |
| LOAD_CONST | 6,398,640 | 10.5% | 31.6% |  |
| LOAD_FAST | 6,398,360 | 10.5% | 42.1% |  |
| STORE_FAST | 6,398,360 | 10.5% | 52.6% |  |
| _EXIT_TRACE | 3,200,000 | 5.3% | 57.9% |  |
| _ITER_CHECK_RANGE | 3,200,000 | 5.3% | 63.2% |  |
| _IS_ITER_EXHAUSTED_RANGE | 3,200,000 | 5.3% | 68.4% |  |
| _POP_JUMP_IF_TRUE | 3,200,000 | 5.3% | 73.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,199,320 | 5.3% | 78.9% |  |
| _GUARD_TYPE_VERSION | 3,199,320 | 5.3% | 84.2% |  |
| _ITER_NEXT_RANGE | 3,199,320 | 5.3% | 89.5% |  |
| _CHECK_ATTR_METHOD_LAZY_DICT | 3,199,320 | 5.3% | 94.7% |  |
| _LOAD_ATTR_METHOD_LAZY_DICT | 3,199,320 | 5.3% | 100.0% |  |
| POP_TOP | 960 | 0.0% | 100.0% |  |
| _GUARD_GLOBALS_VERSION | 280 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_MODULE | 280 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 20 |
| COMPARE_OP | 20 |


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
Stats gathered on: 2023-11-03
