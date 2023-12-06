
# Pystats results

- benchmark: pidigits
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 5,126,580 | 17.1% | 17.1% |  |
| BINARY_OP_MULTIPLY_INT | 4,111,140 | 13.7% | 30.7% |  |
| LOAD_FAST_LOAD_FAST | 3,194,940 | 10.6% | 41.4% |  |
| BINARY_OP_ADD_INT | 3,075,540 | 10.2% | 51.6% |  |
| LOAD_CONST | 2,977,860 | 9.9% | 61.5% |  |
| STORE_FAST_STORE_FAST | 2,219,040 | 7.4% | 68.9% |  |
| RETURN_VALUE | 1,423,500 | 4.7% | 73.6% |  |
| RESUME_CHECK | 1,254,300 | 4.2% | 77.8% |  |
| UNPACK_SEQUENCE_TUPLE | 964,920 | 3.2% | 81.0% |  |
| BINARY_OP | 796,520 | 2.6% | 83.6% |  |
| BUILD_TUPLE | 747,000 | 2.5% | 86.1% |  |
| CALL_PY_EXACT_ARGS | 736,140 | 2.4% | 88.6% |  |
| LOAD_GLOBAL_MODULE | 627,520 | 2.1% | 90.6% |  |
| STORE_FAST | 627,420 | 2.1% | 92.7% |  |
| INTERPRETER_EXIT | 518,160 | 1.7% | 94.5% |  |
| ENTER_EXECUTOR | 409,140 | 1.4% | 95.8% |  |
| POP_JUMP_IF_FALSE | 398,220 | 1.3% | 97.1% |  |
| COMPARE_OP_INT | 398,220 | 1.3% | 98.5% |  |
| POP_TOP | 120,120 | 0.4% | 98.9% |  |
| YIELD_VALUE | 120,000 | 0.4% | 99.3% |  |
| LOAD_GLOBAL_BUILTIN | 109,020 | 0.4% | 99.6% |  |
| CALL_BUILTIN_FAST | 108,900 | 0.4% | 100.0% |  |
| CALL | 560 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 180 | 0.0% | 100.0% |  |
| NOP | 120 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 60 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 3,194,940 | 10.6% | 10.6% |
| LOAD_FAST BINARY_OP_ADD_INT | 1,592,640 | 5.3% | 15.9% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 1,592,640 | 5.3% | 21.2% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 1,254,120 | 4.2% | 25.4% |
| RESUME_CHECK LOAD_FAST | 1,134,120 | 3.8% | 29.2% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 1,025,220 | 3.4% | 32.6% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 964,920 | 3.2% | 35.8% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 964,920 | 3.2% | 39.0% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 964,920 | 3.2% | 42.2% |
| LOAD_CONST LOAD_FAST | 916,200 | 3.0% | 45.2% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 916,200 | 3.0% | 48.3% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 916,200 | 3.0% | 51.3% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 915,600 | 3.0% | 54.4% |
| LOAD_FAST LOAD_CONST | 905,280 | 3.0% | 57.4% |
| BINARY_OP RETURN_VALUE | 796,320 | 2.6% | 60.0% |
| BINARY_OP_ADD_INT BINARY_OP | 796,320 | 2.6% | 62.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 796,200 | 2.6% | 65.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 736,080 | 2.4% | 67.8% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 686,700 | 2.3% | 70.1% |
| LOAD_CONST LOAD_CONST | 638,100 | 2.1% | 72.2% |
| RETURN_VALUE STORE_FAST | 627,120 | 2.1% | 74.3% |
| BUILD_TUPLE RETURN_VALUE | 627,000 | 2.1% | 76.4% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 627,000 | 2.1% | 78.5% |
| STORE_FAST LOAD_FAST | 518,340 | 1.7% | 80.2% |
| CACHE RESUME_CHECK | 518,100 | 1.7% | 81.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 507,180 | 1.7% | 83.6% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 507,120 | 1.7% | 85.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 398,220 | 1.3% | 86.6% |
| RETURN_VALUE INTERPRETER_EXIT | 398,160 | 1.3% | 87.9% |
| RETURN_VALUE COMPARE_OP_INT | 398,160 | 1.3% | 89.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 398,160 | 1.3% | 90.6% |
| BINARY_OP_ADD_INT LOAD_CONST | 398,100 | 1.3% | 91.9% |
| ENTER_EXECUTOR STORE_FAST_STORE_FAST | 289,200 | 1.0% | 92.9% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 289,200 | 1.0% | 93.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 228,900 | 0.8% | 94.6% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 120,060 | 0.4% | 95.0% |
| BUILD_TUPLE LOAD_FAST | 120,000 | 0.4% | 95.4% |
| LOAD_CONST BUILD_TUPLE | 120,000 | 0.4% | 95.8% |
| LOAD_FAST YIELD_VALUE | 120,000 | 0.4% | 96.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 120,000 | 0.4% | 96.6% |
| YIELD_VALUE INTERPRETER_EXIT | 120,000 | 0.4% | 97.0% |
| POP_TOP ENTER_EXECUTOR | 119,940 | 0.4% | 97.4% |
| RESUME_CHECK POP_TOP | 119,940 | 0.4% | 97.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 108,960 | 0.4% | 98.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 108,940 | 0.4% | 98.5% |
| LOAD_FAST CALL_BUILTIN_FAST | 108,900 | 0.4% | 98.9% |
| CALL_BUILTIN_FAST CALL_PY_EXACT_ARGS | 108,900 | 0.4% | 99.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 108,900 | 0.4% | 99.6% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 108,840 | 0.4% | 99.9% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 11,100 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 180 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 180 | 0.0% | 100.0% |
| CALL CALL | 160 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS RETURN_VALUE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| CACHE POP_TOP | 60 | 0.0% | 100.0% |
| CACHE CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| NOP LOAD_GLOBAL_MODULE | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 60 | 0.0% | 100.0% |
| POP_TOP RESUME_CHECK | 60 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 60 | 0.0% | 100.0% |
| RETURN_GENERATOR LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 RERAISE | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| LOAD_CONST MAKE_FUNCTION | 60 | 0.0% | 100.0% |
| LOAD_CONST CALL | 60 | 0.0% | 100.0% |
| LOAD_CONST STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 60 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60 | 0.0% | 100.0% |
| STORE_FAST NOP | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 60 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| MAKE_FUNCTION LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| CALL CALL_PY_EXACT_ARGS | 40 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 40 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP_INT | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

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
| POP_TOP | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 60 | 50.0% |


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
| NOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |


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
| BINARY_OP | 796,320 | 55.9% |
| BUILD_TUPLE | 627,000 | 44.0% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 627,120 | 44.1% |
| INTERPRETER_EXIT | 398,160 | 28.0% |
| COMPARE_OP_INT | 398,160 | 28.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 796,320 | 100.0% |
| BINARY_OP | 180 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 796,320 | 100.0% |
| BINARY_OP | 180 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 627,000 | 83.9% |
| LOAD_CONST | 120,000 | 16.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 627,000 | 83.9% |
| LOAD_FAST | 120,000 | 16.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 42.9% |
| CALL | 160 | 28.6% |
| LOAD_CONST | 60 | 10.7% |
| LOAD_FAST | 60 | 10.7% |
| LOAD_GLOBAL_MODULE | 40 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 160 | 28.6% |
| POP_TOP | 120 | 21.4% |
| CALL_BUILTIN_CLASS | 120 | 21.4% |
| LOAD_FAST | 60 | 10.7% |
| STORE_FAST | 60 | 10.7% |


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
| STORE_FAST_STORE_FAST | 289,200 | 70.7% |
| LOAD_GLOBAL_BUILTIN | 108,840 | 26.6% |
| LOAD_GLOBAL_MODULE | 11,100 | 2.7% |


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
| BINARY_OP_MULTIPLY_INT | 916,200 | 30.8% |
| LOAD_FAST | 905,280 | 30.4% |
| LOAD_CONST | 638,100 | 21.4% |
| BINARY_OP_ADD_INT | 398,100 | 13.4% |
| LOAD_GLOBAL_MODULE | 120,060 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 916,200 | 30.8% |
| BINARY_OP_ADD_INT | 796,200 | 26.7% |
| LOAD_CONST | 638,100 | 21.4% |
| CALL_PY_EXACT_ARGS | 507,120 | 17.0% |
| BUILD_TUPLE | 120,000 | 4.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 1,592,640 | 31.1% |
| RESUME_CHECK | 1,134,120 | 22.1% |
| LOAD_CONST | 916,200 | 17.9% |
| STORE_FAST | 518,340 | 10.1% |
| LOAD_GLOBAL_MODULE | 507,180 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,592,640 | 31.1% |
| UNPACK_SEQUENCE_TUPLE | 964,920 | 18.8% |
| BINARY_OP_MULTIPLY_INT | 916,200 | 17.9% |
| LOAD_CONST | 905,280 | 17.7% |
| LOAD_GLOBAL_MODULE | 398,160 | 7.8% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,254,120 | 39.3% |
| STORE_FAST_STORE_FAST | 1,025,220 | 32.1% |
| BINARY_OP_MULTIPLY_INT | 915,600 | 28.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 3,194,940 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| RETURN_VALUE | 40 | 22.2% |
| MAKE_FUNCTION | 20 | 11.1% |
| STORE_FAST | 20 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 20 | 11.1% |

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
| COMPARE_OP_INT | 398,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 289,200 | 72.6% |
| LOAD_GLOBAL_MODULE | 108,960 | 27.4% |
| LOAD_FAST | 60 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 627,120 | 100.0% |
| CALL | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,340 | 82.6% |
| LOAD_GLOBAL_MODULE | 108,940 | 17.4% |
| NOP | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 964,920 | 43.5% |
| UNPACK_SEQUENCE_TUPLE | 964,920 | 43.5% |
| ENTER_EXECUTOR | 289,200 | 13.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,025,220 | 46.2% |
| STORE_FAST_STORE_FAST | 964,920 | 43.5% |
| LOAD_FAST | 228,900 | 10.3% |


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
| LOAD_FAST | 1,592,640 | 51.8% |
| LOAD_CONST | 796,200 | 25.9% |
| BINARY_OP_MULTIPLY_INT | 686,700 | 22.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,254,120 | 40.8% |
| BINARY_OP | 796,320 | 25.9% |
| BUILD_TUPLE | 627,000 | 20.4% |
| LOAD_CONST | 398,100 | 12.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,194,940 | 77.7% |
| LOAD_FAST | 916,200 | 22.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,592,640 | 38.7% |
| LOAD_CONST | 916,200 | 22.3% |
| LOAD_FAST_LOAD_FAST | 915,600 | 22.3% |
| BINARY_OP_ADD_INT | 686,700 | 16.7% |


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
| LOAD_CONST | 507,120 | 68.9% |
| LOAD_FAST | 120,000 | 16.3% |
| CALL_BUILTIN_FAST | 108,900 | 14.8% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 736,080 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 398,160 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 398,220 | 100.0% |


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
| ENTER_EXECUTOR | 108,840 | 99.8% |
| RESUME_CHECK | 80 | 0.1% |
| LOAD_FAST | 60 | 0.1% |
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
| LOAD_FAST | 398,160 | 63.4% |
| POP_JUMP_IF_FALSE | 108,960 | 17.4% |
| STORE_FAST | 108,940 | 17.4% |
| ENTER_EXECUTOR | 11,100 | 1.8% |
| LOAD_GLOBAL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 507,180 | 80.8% |
| LOAD_CONST | 120,060 | 19.1% |
| CALL_PY_EXACT_ARGS | 80 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 736,080 | 58.7% |
| CACHE | 518,100 | 41.3% |
| POP_TOP | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,134,120 | 90.4% |
| POP_TOP | 119,940 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 964,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 964,920 | 100.0% |


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
|     deferred | 796,320 | 10.0% |
|          hit | 7,186,740 | 90.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 10.0% |
| Failure | 180 | 90.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 180 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 360 | 0.0% |
|          hit | 845,160 | 99.9% |

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
|---|---:|---:|
|          hit | 398,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 12.5% |
|          hit | 100 | 62.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 736,540 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 964,920 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 17,484,660 | 58.2% |
| Not specialized | 1,195,560 | 4.0% |
| Specialized | 11,385,980 | 37.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 796,320 | 99.9% |
| CALL | 360 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| MAKE_FUNCTION | 0 | 0.0% |


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
| Calls to PyEval_EvalDefault | 518,220 | 41.3% |
| Calls to Python functions inlined | 736,200 | 58.7% |
| Calls via PyEval_EvalFrame (total) | 518,220 | 41.3% |
| Calls via PyEval_EvalFrame (vector) | 398,160 | 31.7% |
| Calls via PyEval_EvalFrame (generator) | 120,060 | 9.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 398,160 | 31.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 120 | 0.0% |
| Frames pushed | 1,952,640 | 155.7% |


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
| Interpreter increfs | 13,062,880 | 53.0% |
| Interpreter decrefs | 22,841,340 | 62.0% |
| Increfs | 11,600,560 | 47.0% |
| Decrefs | 14,001,140 | 38.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 19 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
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

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 409,140 |  |
| Uops executed | 43,013,940 | 105.13 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
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
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 409,140 | 100.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 10,506,600 | 24.4% | 24.4% |  |
| LOAD_FAST | 7,931,820 | 18.4% | 42.9% |  |
| STORE_FAST | 4,260,660 | 9.9% | 52.8% |  |
| _GUARD_BOTH_INT | 3,851,520 | 9.0% | 61.7% |  |
| _BINARY_OP_MULTIPLY_INT | 2,504,160 | 5.8% | 67.5% |  |
| _BINARY_OP_ADD_INT | 1,347,360 | 3.1% | 70.7% |  |
| _SAVE_CURRENT_IP | 1,347,360 | 3.1% | 73.8% |  |
| _GUARD_GLOBALS_VERSION | 1,216,320 | 2.8% | 76.6% |  |
| UNPACK_SEQUENCE_TUPLE | 1,107,480 | 2.6% | 79.2% |  |
| _LOAD_GLOBAL_MODULE | 927,120 | 2.2% | 81.4% |  |
| RESUME_CHECK | 818,280 | 1.9% | 83.3% |  |
| _CHECK_PEP_523 | 818,280 | 1.9% | 85.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 818,280 | 1.9% | 87.1% |  |
| _CHECK_STACK_SPACE | 818,280 | 1.9% | 89.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 818,280 | 1.9% | 90.9% |  |
| _PUSH_FRAME | 818,280 | 1.9% | 92.8% |  |
| LOAD_CONST | 529,080 | 1.2% | 94.0% |  |
| _POP_FRAME | 529,080 | 1.2% | 95.2% |  |
| _EXIT_TRACE | 409,140 | 1.0% | 96.2% |  |
| BUILD_TUPLE | 289,200 | 0.7% | 96.9% |  |
| CALL_BUILTIN_FAST | 289,200 | 0.7% | 97.5% |  |
| _GUARD_BUILTINS_VERSION | 289,200 | 0.7% | 98.2% |  |
| _LOAD_GLOBAL_BUILTINS | 289,200 | 0.7% | 98.9% |  |
| BINARY_OP | 239,880 | 0.6% | 99.4% |  |
| COMPARE_OP_INT | 119,940 | 0.3% | 99.7% |  |
| _POP_JUMP_IF_FALSE | 119,940 | 0.3% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
