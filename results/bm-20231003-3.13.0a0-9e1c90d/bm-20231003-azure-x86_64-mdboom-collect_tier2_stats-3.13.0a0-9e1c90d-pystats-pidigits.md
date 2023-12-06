
# Pystats results

- benchmark: pidigits
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 6,293,580 | 16.1% | 16.1% |  |
| BINARY_OP_MULTIPLY_INT | 5,507,820 | 14.1% | 30.2% |  |
| LOAD_FAST_LOAD_FAST | 4,591,620 | 11.8% | 42.0% |  |
| BINARY_OP_ADD_INT | 4,183,020 | 10.7% | 52.7% |  |
| LOAD_CONST | 3,387,000 | 8.7% | 61.4% |  |
| STORE_FAST_STORE_FAST | 2,748,120 | 7.0% | 68.4% |  |
| RETURN_VALUE | 1,832,640 | 4.7% | 73.1% |  |
| RESUME_CHECK | 1,663,440 | 4.3% | 77.4% |  |
| UNPACK_SEQUENCE_TUPLE | 1,374,060 | 3.5% | 80.9% |  |
| CALL_PY_EXACT_ARGS | 1,145,280 | 2.9% | 83.8% |  |
| BUILD_TUPLE | 1,036,200 | 2.7% | 86.5% |  |
| LOAD_GLOBAL_MODULE | 1,025,560 | 2.6% | 89.1% |  |
| STORE_FAST | 916,620 | 2.3% | 91.4% |  |
| BINARY_OP | 916,500 | 2.3% | 93.8% |  |
| POP_JUMP_IF_FALSE | 518,160 | 1.3% | 95.1% |  |
| INTERPRETER_EXIT | 518,160 | 1.3% | 96.4% |  |
| COMPARE_OP_INT | 518,160 | 1.3% | 97.8% |  |
| ENTER_EXECUTOR | 409,140 | 1.0% | 98.8% |  |
| POP_TOP | 120,120 | 0.3% | 99.1% |  |
| YIELD_VALUE | 120,000 | 0.3% | 99.4% |  |
| LOAD_GLOBAL_BUILTIN | 109,020 | 0.3% | 99.7% |  |
| CALL_BUILTIN_FAST | 108,900 | 0.3% | 100.0% |  |
| CALL | 560 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 180 | 0.0% | 100.0% |  |
| NOP | 120 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 4,591,620 | 11.8% | 11.8% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 1,952,460 | 5.0% | 16.8% |
| LOAD_FAST BINARY_OP_ADD_INT | 1,832,520 | 4.7% | 21.5% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 1,832,520 | 4.7% | 26.1% |
| RESUME_CHECK LOAD_FAST | 1,543,260 | 4.0% | 30.1% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 1,494,000 | 3.8% | 33.9% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,374,060 | 3.5% | 37.4% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 1,374,060 | 3.5% | 41.0% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,374,060 | 3.5% | 44.5% |
| LOAD_FAST LOAD_CONST | 1,314,420 | 3.4% | 47.8% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 1,265,100 | 3.2% | 51.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,145,220 | 2.9% | 54.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 1,145,160 | 2.9% | 57.0% |
| RETURN_VALUE STORE_FAST | 916,320 | 2.3% | 59.3% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 916,260 | 2.3% | 61.6% |
| BINARY_OP_ADD_INT BINARY_OP | 916,260 | 2.3% | 64.0% |
| BINARY_OP RETURN_VALUE | 916,260 | 2.3% | 66.3% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 916,200 | 2.3% | 68.7% |
| LOAD_CONST LOAD_FAST | 916,200 | 2.3% | 71.0% |
| BUILD_TUPLE RETURN_VALUE | 916,200 | 2.3% | 73.4% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 916,200 | 2.3% | 75.7% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 916,200 | 2.3% | 78.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 905,220 | 2.3% | 80.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 796,200 | 2.0% | 82.4% |
| LOAD_CONST LOAD_CONST | 638,100 | 1.6% | 84.1% |
| STORE_FAST LOAD_FAST | 518,340 | 1.3% | 85.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 518,160 | 1.3% | 86.7% |
| RETURN_VALUE COMPARE_OP_INT | 518,100 | 1.3% | 88.0% |
| CACHE RESUME_CHECK | 518,100 | 1.3% | 89.4% |
| RETURN_VALUE INTERPRETER_EXIT | 398,160 | 1.0% | 90.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 398,160 | 1.0% | 91.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 398,140 | 1.0% | 92.4% |
| BINARY_OP_ADD_INT LOAD_CONST | 398,100 | 1.0% | 93.5% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 289,200 | 0.7% | 94.2% |
| ENTER_EXECUTOR BINARY_OP_ADD_INT | 289,200 | 0.7% | 94.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 228,900 | 0.6% | 95.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 228,900 | 0.6% | 96.1% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 120,060 | 0.3% | 96.4% |
| YIELD_VALUE INTERPRETER_EXIT | 120,000 | 0.3% | 96.7% |
| LOAD_FAST YIELD_VALUE | 120,000 | 0.3% | 97.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 120,000 | 0.3% | 97.3% |
| LOAD_CONST BUILD_TUPLE | 120,000 | 0.3% | 97.6% |
| BUILD_TUPLE LOAD_FAST | 120,000 | 0.3% | 98.0% |
| RESUME_CHECK POP_TOP | 119,940 | 0.3% | 98.3% |
| POP_TOP ENTER_EXECUTOR | 119,940 | 0.3% | 98.6% |
| ENTER_EXECUTOR LOAD_FAST | 119,940 | 0.3% | 98.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 108,900 | 0.3% | 99.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 108,900 | 0.3% | 99.4% |
| LOAD_FAST CALL_BUILTIN_FAST | 108,900 | 0.3% | 99.7% |
| CALL_BUILTIN_FAST CALL_PY_EXACT_ARGS | 108,900 | 0.3% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 220 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 180 | 0.0% | 100.0% |
| CALL CALL | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS RETURN_VALUE | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| STORE_FAST NOP | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| RETURN_GENERATOR LOAD_FAST | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 60 | 0.0% | 100.0% |
| POP_TOP RESUME_CHECK | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 60 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60 | 0.0% | 100.0% |
| NOP LOAD_GLOBAL_MODULE | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 60 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL | 60 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 60 | 0.0% | 100.0% |
| LOAD_CONST STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_CONST MAKE_FUNCTION | 60 | 0.0% | 100.0% |
| LOAD_CONST CALL | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 RERAISE | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CACHE POP_TOP | 60 | 0.0% | 100.0% |
| CACHE CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 60 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| MAKE_FUNCTION LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |


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
| RESUME_CHECK | 518,100 | 100.0% |
| POP_TOP | 60 | 0.0% |
| CALL_INTRINSIC_1 | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 398,160 | 76.8% |
| YIELD_VALUE | 120,000 | 23.2% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| POP_TOP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 50.0% |
| LOAD_DEREF | 60 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 119,940 | 99.9% |
| CALL | 120 | 0.1% |
| CACHE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 119,940 | 99.9% |
| RESUME_CHECK | 60 | 0.0% |
| NOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| LOAD_DEREF | 60 | 20.0% |
| LOAD_ATTR_MODULE | 40 | 13.3% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 80.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 916,260 | 50.0% |
| BUILD_TUPLE | 916,200 | 50.0% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 916,320 | 50.0% |
| COMPARE_OP_INT | 518,100 | 28.3% |
| INTERPRETER_EXIT | 398,160 | 21.7% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 916,260 | 100.0% |
| BINARY_OP | 220 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 916,260 | 100.0% |
| BINARY_OP | 220 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 916,200 | 88.4% |
| LOAD_CONST | 120,000 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 916,200 | 88.4% |
| LOAD_FAST | 120,000 | 11.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 42.9% |
| CALL | 160 | 28.6% |
| LOAD_FAST | 60 | 10.7% |
| LOAD_CONST | 60 | 10.7% |
| LOAD_GLOBAL_MODULE | 40 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 160 | 28.6% |
| POP_TOP | 120 | 21.4% |
| CALL_BUILTIN_CLASS | 120 | 21.4% |
| STORE_FAST | 60 | 10.7% |
| LOAD_FAST | 60 | 10.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 100.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20 | 100.0% |


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
| POP_JUMP_IF_FALSE | 289,200 | 70.7% |
| POP_TOP | 119,940 | 29.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 289,200 | 70.7% |
| LOAD_FAST | 119,940 | 29.3% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40 | 66.7% |
| PUSH_NULL | 20 | 33.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,314,420 | 38.8% |
| BINARY_OP_MULTIPLY_INT | 916,200 | 27.1% |
| LOAD_CONST | 638,100 | 18.8% |
| BINARY_OP_ADD_INT | 398,100 | 11.8% |
| LOAD_GLOBAL_MODULE | 120,060 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 916,260 | 27.1% |
| LOAD_FAST | 916,200 | 27.1% |
| BINARY_OP_ADD_INT | 796,200 | 23.5% |
| LOAD_CONST | 638,100 | 18.8% |
| BUILD_TUPLE | 120,000 | 3.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| NOP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| PUSH_NULL | 60 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 1,832,520 | 29.1% |
| RESUME_CHECK | 1,543,260 | 24.5% |
| LOAD_CONST | 916,200 | 14.6% |
| LOAD_GLOBAL_MODULE | 905,220 | 14.4% |
| STORE_FAST | 518,340 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,832,520 | 29.1% |
| UNPACK_SEQUENCE_TUPLE | 1,374,060 | 21.8% |
| LOAD_CONST | 1,314,420 | 20.9% |
| BINARY_OP_MULTIPLY_INT | 916,200 | 14.6% |
| LOAD_GLOBAL_MODULE | 398,160 | 6.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,952,460 | 42.5% |
| BINARY_OP_MULTIPLY_INT | 1,494,000 | 32.5% |
| STORE_FAST_STORE_FAST | 1,145,160 | 24.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 4,591,620 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| RETURN_VALUE | 40 | 22.2% |
| STORE_FAST | 20 | 11.1% |
| MAKE_FUNCTION | 20 | 11.1% |
| LOAD_GLOBAL_MODULE | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 22.2% |
| LOAD_ATTR | 20 | 11.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 518,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 289,200 | 55.8% |
| LOAD_GLOBAL_MODULE | 228,900 | 44.2% |
| LOAD_FAST | 60 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 916,320 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,340 | 56.5% |
| LOAD_GLOBAL_MODULE | 398,140 | 43.4% |
| NOP | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,374,060 | 50.0% |
| STORE_FAST_STORE_FAST | 1,374,060 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,374,060 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,145,160 | 41.7% |
| LOAD_FAST | 228,900 | 8.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 120,000 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,832,520 | 43.8% |
| BINARY_OP_MULTIPLY_INT | 1,265,100 | 30.2% |
| LOAD_CONST | 796,200 | 19.0% |
| ENTER_EXECUTOR | 289,200 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,952,460 | 46.7% |
| BINARY_OP | 916,260 | 21.9% |
| BUILD_TUPLE | 916,200 | 21.9% |
| LOAD_CONST | 398,100 | 9.5% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,591,620 | 83.4% |
| LOAD_FAST | 916,200 | 16.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,832,520 | 33.3% |
| LOAD_FAST_LOAD_FAST | 1,494,000 | 27.1% |
| BINARY_OP_ADD_INT | 1,265,100 | 23.0% |
| LOAD_CONST | 916,200 | 16.6% |


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

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 108,900 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 916,260 | 80.0% |
| LOAD_FAST | 120,000 | 10.5% |
| CALL_BUILTIN_FAST | 108,900 | 9.5% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,145,220 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 518,100 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 518,160 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| PUSH_NULL | 40 | 40.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,900 | 99.9% |
| RESUME_CHECK | 80 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,900 | 99.9% |
| LOAD_CONST | 60 | 0.1% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 398,160 | 38.8% |
| STORE_FAST | 398,140 | 38.8% |
| POP_JUMP_IF_FALSE | 228,900 | 22.3% |
| LOAD_GLOBAL | 120 | 0.0% |
| NOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 905,220 | 88.3% |
| LOAD_CONST | 120,060 | 11.7% |
| CALL_PY_EXACT_ARGS | 80 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,145,220 | 68.8% |
| CACHE | 518,100 | 31.1% |
| POP_TOP | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,543,260 | 92.8% |
| POP_TOP | 119,940 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,374,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,374,060 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       916260 | 8.6% |
|          hit |      9690900 | 91.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 8.3% |
| Failure | 220 | 91.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 220 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          360 | 0.0% |
|          hit |      1254300 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 40.0% |
| Failure | 120 | 60.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 50.0% |
| class no vectorcall | 40 | 33.3% |
| other | 20 | 16.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       518160 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 12.5% |
|          hit |          100 | 62.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
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
|          hit |      1134580 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
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

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1374060 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 21,974,100 | 56.3% |
| Not specialized | 1,435,480 | 3.7% |
| Specialized | 15,635,540 | 40.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 916,260 | 100.0% |
| CALL | 360 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 518,220 | 31.2% |
| Calls to Python functions inlined | 1,145,340 | 68.8% |
| Calls via PyEval_EvalFrame (total) | 518,220 | 31.2% |
| Calls via PyEval_EvalFrame (vector) | 398,160 | 23.9% |
| Calls via PyEval_EvalFrame (generator) | 120,060 | 7.2% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 398,160 | 23.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 1,952,640 | 117.4% |
| Frame objects created | 120 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,036,480 | 8.5% |
| Frees to freelist | 1,036,500 |  |
| Allocations | 11,142,680 | 91.5% |
| Allocations to 512 bytes | 3,546,980 | 29.1% |
| Allocations to 4 kbytes | 2,862,840 | 23.5% |
| Allocations over 4 kbytes | 4,732,860 | 38.9% |
| Frees | 11,142,600 |  |
| New values | 0 |  |
| Interpreter increfs | 17,811,040 | 72.2% |
| Interpreter decrefs | 26,553,540 | 72.1% |
| Increfs | 6,852,400 | 27.8% |
| Decrefs | 10,288,940 | 27.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 17 |  |
| Method cache misses | 3 |  |
| Method cache collisions | 3 |  |
| Method cache dunder hits | 60 |  |
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
| Traces executed | 409,140 |  |
| Uops executed | 21,275,280 | 52 |
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
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 409,140 | 100.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 5,029,620 | 23.6% | 23.6% |
| LOAD_FAST | 3,971,460 | 18.7% | 42.3% |
| STORE_FAST | 2,913,300 | 13.7% | 56.0% |
| _GUARD_BOTH_INT | 1,347,360 | 6.3% | 62.3% |
| _BINARY_OP_MULTIPLY_INT | 1,107,480 | 5.2% | 67.5% |
| _GUARD_GLOBALS_VERSION | 818,280 | 3.8% | 71.4% |
| UNPACK_SEQUENCE_TUPLE | 698,340 | 3.3% | 74.7% |
| _SAVE_CURRENT_IP | 529,080 | 2.5% | 77.2% |
| _LOAD_GLOBAL_MODULE | 529,080 | 2.5% | 79.6% |
| _PUSH_FRAME | 409,140 | 1.9% | 81.6% |
| _INIT_CALL_PY_EXACT_ARGS | 409,140 | 1.9% | 83.5% |
| _EXIT_TRACE | 409,140 | 1.9% | 85.4% |
| _CHECK_STACK_SPACE | 409,140 | 1.9% | 87.3% |
| _CHECK_PEP_523 | 409,140 | 1.9% | 89.3% |
| _CHECK_FUNCTION_EXACT_ARGS | 409,140 | 1.9% | 91.2% |
| RESUME_CHECK | 409,140 | 1.9% | 93.1% |
| _LOAD_GLOBAL_BUILTINS | 289,200 | 1.4% | 94.5% |
| _GUARD_BUILTINS_VERSION | 289,200 | 1.4% | 95.8% |
| CALL_BUILTIN_FAST | 289,200 | 1.4% | 97.2% |
| _BINARY_OP_ADD_INT | 239,880 | 1.1% | 98.3% |
| _POP_FRAME | 119,940 | 0.6% | 98.9% |
| LOAD_CONST | 119,940 | 0.6% | 99.4% |
| BINARY_OP | 119,940 | 0.6% | 100.0% |


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
