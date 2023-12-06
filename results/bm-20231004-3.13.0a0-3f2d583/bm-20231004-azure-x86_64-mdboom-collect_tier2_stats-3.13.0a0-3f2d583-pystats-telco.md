
# Pystats results

- benchmark: telco
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 40,833,200 | 41.0% | 41.0% |  |
| STORE_FAST | 19,218,080 | 19.3% | 60.2% |  |
| BINARY_OP | 13,214,400 | 13.3% | 73.5% |  |
| CALL | 6,007,320 | 6.0% | 79.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,603,360 | 3.6% | 83.1% |  |
| LOAD_CONST | 2,404,780 | 2.4% | 85.5% |  |
| POP_TOP | 2,401,280 | 2.4% | 87.9% |  |
| LOAD_GLOBAL_BUILTIN | 2,400,720 | 2.4% | 90.4% |  |
| POP_JUMP_IF_FALSE | 2,400,480 | 2.4% | 92.8% |  |
| ENTER_EXECUTOR | 2,400,320 | 2.4% | 95.2% |  |
| CALL_KW | 2,400,060 | 2.4% | 97.6% |  |
| TO_BOOL_INT | 2,400,000 | 2.4% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 2,400 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,700 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 1,640 | 0.0% | 100.0% |  |
| LOAD_ATTR | 700 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 700 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 700 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 660 | 0.0% | 100.0% |  |
| GET_ITER | 540 | 0.0% | 100.0% |  |
| COMPARE_OP | 500 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 480 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 480 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 480 | 0.0% | 100.0% |  |
| PUSH_NULL | 420 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 360 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 280 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 180 | 0.0% | 100.0% |  |
| RETURN_VALUE | 120 | 0.0% | 100.0% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 16,816,100 | 16.9% | 16.9% |
| LOAD_FAST LOAD_FAST | 15,611,040 | 15.7% | 32.5% |
| LOAD_FAST BINARY_OP | 13,210,580 | 13.3% | 45.8% |
| BINARY_OP STORE_FAST | 13,210,560 | 13.3% | 59.0% |
| CALL STORE_FAST | 6,005,160 | 6.0% | 65.1% |
| LOAD_FAST CALL | 3,603,860 | 3.6% | 68.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 3,603,360 | 3.6% | 72.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,603,360 | 3.6% | 75.9% |
| LOAD_FAST LOAD_CONST | 2,401,020 | 2.4% | 78.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 2,400,560 | 2.4% | 80.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,400,120 | 2.4% | 83.1% |
| LOAD_CONST CALL_KW | 2,400,060 | 2.4% | 85.5% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,400,000 | 2.4% | 87.9% |
| POP_TOP ENTER_EXECUTOR | 2,400,000 | 2.4% | 90.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 2,400,000 | 2.4% | 92.7% |
| LOAD_FAST TO_BOOL_INT | 2,400,000 | 2.4% | 95.2% |
| CALL_KW POP_TOP | 2,400,000 | 2.4% | 97.6% |
| ENTER_EXECUTOR CALL | 2,399,800 | 2.4% | 100.0% |
| BINARY_OP BINARY_OP | 3,340 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 1,940 | 0.0% | 100.0% |
| CALL CALL | 1,820 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_LAZY_DICT | 1,640 | 0.0% | 100.0% |
| LOAD_CONST CALL | 1,440 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,200 | 0.0% | 100.0% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 1,160 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_LAZY_DICT LOAD_CONST | 1,160 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 1,160 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 680 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 540 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 540 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS GET_ITER | 540 | 0.0% | 100.0% |
| LOAD_CONST CALL_BUILTIN_CLASS | 520 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 480 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 480 | 0.0% | 100.0% |
| POP_TOP EXTENDED_ARG | 480 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 480 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 480 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 480 | 0.0% | 100.0% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 480 | 0.0% | 100.0% |
| LOAD_CONST LOAD_FAST | 480 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP | 480 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP | 480 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_LAZY_DICT CALL_METHOD_DESCRIPTOR_FAST | 480 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_FAST | 480 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 480 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 480 | 0.0% | 100.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 480 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST UNPACK_SEQUENCE_TUPLE | 480 | 0.0% | 100.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 480 | 0.0% | 100.0% |
| BINARY_OP LOAD_FAST | 480 | 0.0% | 100.0% |
| EXTENDED_ARG ENTER_EXECUTOR | 300 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 280 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 260 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 240 | 0.0% | 100.0% |
| EXTENDED_ARG FOR_ITER_RANGE | 220 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 180 | 0.0% | 100.0% |
| EXTENDED_ARG JUMP_BACKWARD | 180 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 160 | 0.0% | 100.0% |
| JUMP_BACKWARD EXTENDED_ARG | 160 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 100 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_CONST | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL | 60 | 0.0% | 100.0% |
| LOAD_FAST_CHECK CALL | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| GET_ITER EXTENDED_ARG | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_KW STORE_FAST | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS BEFORE_WITH | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_ATTR | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.0% | 100.0% |
| BEFORE_WITH STORE_FAST | 60 | 0.0% | 100.0% |
| STORE_ATTR LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 480 | 88.9% |
| EXTENDED_ARG | 60 | 11.1% |


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
| CALL_KW | 2,400,000 | 99.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,160 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,400,000 | 99.9% |
| LOAD_FAST | 480 | 0.0% |
| EXTENDED_ARG | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 280 | 66.7% |
| LOAD_DEREF | 120 | 28.6% |
| LOAD_ATTR | 20 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 57.1% |
| LOAD_FAST | 120 | 28.6% |
| LOAD_FAST_CHECK | 60 | 14.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 50.0% |

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
| LOAD_FAST | 13,210,580 | 100.0% |
| BINARY_OP | 3,340 | 0.0% |
| LOAD_CONST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,210,560 | 100.0% |
| BINARY_OP | 3,340 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,603,860 | 60.0% |
| ENTER_EXECUTOR | 2,399,800 | 39.9% |
| CALL | 1,820 | 0.0% |
| LOAD_CONST | 1,440 | 0.0% |
| PUSH_NULL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,005,160 | 100.0% |
| CALL | 1,820 | 0.0% |
| POP_TOP | 120 | 0.0% |
| STORE_ATTR | 60 | 0.0% |
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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,400,000 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 96.0% |
| COMPARE_OP | 20 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 480 | 96.0% |
| COMPARE_OP | 20 | 4.0% |


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
| POP_TOP | 2,400,000 | 100.0% |
| EXTENDED_ARG | 300 | 0.0% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,399,800 | 100.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480 | 68.6% |
| JUMP_BACKWARD | 160 | 22.9% |
| GET_ITER | 60 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 300 | 42.9% |
| FOR_ITER_RANGE | 220 | 31.4% |
| JUMP_BACKWARD | 180 | 25.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 160 | 88.9% |
| ENTER_EXECUTOR | 20 | 11.1% |


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
| LOAD_FAST | 540 | 77.1% |
| LOAD_GLOBAL_MODULE | 100 | 14.3% |
| LOAD_ATTR | 40 | 5.7% |
| LOAD_GLOBAL | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 68.6% |
| LOAD_ATTR_MODULE | 100 | 14.3% |
| LOAD_ATTR | 40 | 5.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 5.7% |
| PUSH_NULL | 20 | 2.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,401,020 | 99.8% |
| LOAD_GLOBAL_MODULE | 1,940 | 0.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 1,160 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 480 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 2,400,060 | 99.8% |
| CALL | 1,440 | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,160 | 0.0% |
| CALL_BUILTIN_CLASS | 520 | 0.0% |
| LOAD_FAST | 480 | 0.0% |


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
| STORE_FAST | 16,816,100 | 41.2% |
| LOAD_FAST | 15,611,040 | 38.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,603,360 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 2,400,120 | 5.9% |
| POP_JUMP_IF_FALSE | 2,400,000 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,611,040 | 38.2% |
| BINARY_OP | 13,210,580 | 32.4% |
| CALL | 3,603,860 | 8.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,603,360 | 8.8% |
| LOAD_CONST | 2,401,020 | 5.9% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 44.4% |
| RETURN_VALUE | 40 | 11.1% |
| LOAD_GLOBAL_MODULE | 40 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 40 | 11.1% |
| STORE_ATTR | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 72.2% |
| LOAD_GLOBAL_BUILTIN | 80 | 22.2% |
| LOAD_ATTR | 20 | 5.6% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,400,000 | 100.0% |
| COMPARE_OP | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,400,000 | 100.0% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 75.0% |
| STORE_ATTR | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 50.0% |
| STORE_ATTR | 20 | 25.0% |
| LOAD_GLOBAL | 20 | 25.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 13,210,560 | 68.7% |
| CALL | 6,005,160 | 31.2% |
| FOR_ITER_RANGE | 680 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 540 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,816,100 | 87.5% |
| LOAD_GLOBAL_BUILTIN | 2,400,560 | 12.5% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


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
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 520 | 78.8% |
| CALL | 60 | 9.1% |
| LOAD_FAST | 40 | 6.1% |
| CALL_BUILTIN_CLASS | 40 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 540 | 81.8% |
| STORE_FAST | 60 | 9.1% |
| CALL_BUILTIN_CLASS | 40 | 6.1% |
| CALL | 20 | 3.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 480 | 100.0% |


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
| LOAD_CONST | 1,160 | 68.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 480 | 28.2% |
| LOAD_ATTR | 40 | 2.4% |
| CALL | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,160 | 68.2% |
| STORE_FAST | 540 | 31.8% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 480 | 68.6% |
| EXTENDED_ARG | 220 | 31.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 680 | 97.1% |
| LOAD_GLOBAL | 20 | 2.9% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,160 | 70.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 29.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,603,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,603,360 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 64.3% |
| LOAD_ATTR | 100 | 35.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 280 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400,560 | 100.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| STORE_ATTR | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,400,120 | 100.0% |
| LOAD_CONST | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200 | 50.0% |
| POP_JUMP_IF_FALSE | 480 | 20.0% |
| LOAD_GLOBAL | 260 | 10.8% |
| POP_TOP | 240 | 10.0% |
| LOAD_GLOBAL_MODULE | 80 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,940 | 80.8% |
| LOAD_ATTR_MODULE | 180 | 7.5% |
| LOAD_ATTR | 100 | 4.2% |
| LOAD_GLOBAL_MODULE | 80 | 3.3% |
| CALL | 60 | 2.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| CALL_FUNCTION_EX | 60 | 50.0% |

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
| LOAD_FAST | 2,400,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,400,000 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 100.0% |


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
|          hit |          480 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2400000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     13211040 | 100.0% |
|          hit |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.6% |
| Failure | 3,340 | 99.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 2,400 | 71.9% |
| multiply other | 900 | 26.9% |
| multiply different types | 20 | 0.6% |
| and int | 20 | 0.6% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6005400 | 99.9% |
|          hit |         2900 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 5.2% |
| Failure | 1,820 | 94.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs keywords | 900 | 49.5% |
| cfunc varargs | 620 | 34.1% |
| class no vectorcall | 220 | 12.1% |
| cfunc noargs | 80 | 4.4% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          480 | 96.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          700 | 100.0% |


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
| specialization.deferred |          560 | 0.0% |
|          hit |      3605280 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 71.4% |
| Failure | 40 | 28.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 20 | 50.0% |
| overridden | 20 | 50.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      2403120 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 100.0% |
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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 20 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          480 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 69,660,220 | 69.9% |
| Not specialized | 21,624,020 | 21.7% |
| Specialized | 8,413,140 | 8.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 13,211,040 | 68.7% |
| CALL | 6,005,400 | 31.2% |
| LOAD_ATTR | 560 | 0.0% |
| COMPARE_OP | 480 | 0.0% |
| STORE_ATTR | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_INT | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 120 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 100.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 120 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 10,805,980 | 20.8% |
| Frees to freelist | 10,806,000 |  |
| Allocations | 41,264,320 | 79.2% |
| Allocations to 512 bytes | 41,264,200 | 79.2% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 41,264,220 |  |
| New values | 120 |  |
| Interpreter increfs | 49,241,940 | 24.4% |
| Interpreter decrefs | 73,259,400 | 29.1% |
| Increfs | 152,967,120 | 75.6% |
| Decrefs | 178,617,660 | 70.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,201,539 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
| Method cache dunder hits | 180 |  |
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
| Optimization attempts | 20 |  |
| Traces created | 20 | 100.0% |
| Traces executed | 2,400,320 |  |
| Uops executed | 119,985,520 | 49 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 32 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 520 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 280 | 0.0% |
| <= 64 | 2,399,520 | 100.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 28,796,680 | 24.0% | 24.0% |
| LOAD_FAST | 23,995,480 | 20.0% | 44.0% |
| STORE_FAST | 11,997,880 | 10.0% | 54.0% |
| LOAD_CONST | 9,598,640 | 8.0% | 62.0% |
| _POP_JUMP_IF_TRUE | 4,799,840 | 4.0% | 66.0% |
| BINARY_OP | 4,799,040 | 4.0% | 70.0% |
| _ITER_CHECK_RANGE | 2,400,320 | 2.0% | 72.0% |
| _IS_ITER_EXHAUSTED_RANGE | 2,400,320 | 2.0% | 74.0% |
| _EXIT_TRACE | 2,400,320 | 2.0% | 76.0% |
| _LOAD_GLOBAL_MODULE | 2,399,800 | 2.0% | 78.0% |
| _LOAD_ATTR_METHOD_LAZY_DICT | 2,399,800 | 2.0% | 80.0% |
| _ITER_NEXT_RANGE | 2,399,800 | 2.0% | 82.0% |
| _GUARD_TYPE_VERSION | 2,399,800 | 2.0% | 84.0% |
| _GUARD_GLOBALS_VERSION | 2,399,800 | 2.0% | 86.0% |
| _CHECK_ATTR_METHOD_LAZY_DICT | 2,399,800 | 2.0% | 88.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,399,800 | 2.0% | 90.0% |
| UNPACK_SEQUENCE_TUPLE | 2,399,520 | 2.0% | 92.0% |
| LOAD_ATTR | 2,399,520 | 2.0% | 94.0% |
| COMPARE_OP | 2,399,520 | 2.0% | 96.0% |
| CALL_BUILTIN_FAST | 2,399,520 | 2.0% | 98.0% |
| BINARY_SUBSCR_LIST_INT | 2,399,520 | 2.0% | 100.0% |
| POP_TOP | 800 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| CALL | 20 |


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
