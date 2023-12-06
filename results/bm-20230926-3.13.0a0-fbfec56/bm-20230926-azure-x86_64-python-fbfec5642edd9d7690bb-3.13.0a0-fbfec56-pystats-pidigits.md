
# Pystats results

- benchmark: pidigits
- fork: python
- ref: fbfec5642edd9d7690bbff088ee43c08e8067044
- commit hash: fbfec56
- commit date: 2023-09-26T20:46:52+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 8,050,080 | 16.9% | 16.9% |  |
| BINARY_OP_MULTIPLY_INT | 6,615,300 | 13.9% | 30.7% |  |
| LOAD_FAST_LOAD_FAST | 5,699,100 | 11.9% | 42.6% |  |
| BINARY_OP_ADD_INT | 4,422,900 | 9.3% | 51.9% |  |
| STORE_FAST_STORE_FAST | 4,144,800 | 8.7% | 60.6% |  |
| LOAD_CONST | 3,506,940 | 7.3% | 67.9% |  |
| RESUME_CHECK | 2,072,580 | 4.3% | 72.3% |  |
| UNPACK_SEQUENCE_TUPLE | 2,072,400 | 4.3% | 76.6% |  |
| RETURN_VALUE | 1,952,580 | 4.1% | 80.7% |  |
| LOAD_GLOBAL_MODULE | 1,554,640 | 3.3% | 83.9% |  |
| CALL_PY_EXACT_ARGS | 1,554,420 | 3.3% | 87.2% |  |
| STORE_FAST | 1,036,560 | 2.2% | 89.4% |  |
| BINARY_OP | 1,036,460 | 2.2% | 91.5% |  |
| BUILD_TUPLE | 1,036,200 | 2.2% | 93.7% |  |
| POP_JUMP_IF_FALSE | 518,160 | 1.1% | 94.8% |  |
| INTERPRETER_EXIT | 518,160 | 1.1% | 95.9% |  |
| COMPARE_OP_INT | 518,160 | 1.1% | 97.0% |  |
| JUMP_BACKWARD | 409,140 | 0.9% | 97.8% |  |
| LOAD_GLOBAL_BUILTIN | 398,220 | 0.8% | 98.7% |  |
| CALL_BUILTIN_FAST | 398,100 | 0.8% | 99.5% |  |
| POP_TOP | 120,120 | 0.3% | 99.7% |  |
| YIELD_VALUE | 120,000 | 0.3% | 100.0% |  |
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
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 5,699,100 | 11.9% | 11.9% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 2,072,400 | 4.3% | 16.3% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 2,072,400 | 4.3% | 20.6% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 2,072,400 | 4.3% | 25.0% |
| LOAD_FAST BINARY_OP_ADD_INT | 2,072,400 | 4.3% | 29.3% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 2,072,400 | 4.3% | 33.6% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 2,072,400 | 4.3% | 38.0% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 2,072,400 | 4.3% | 42.3% |
| RESUME_CHECK LOAD_FAST | 1,952,400 | 4.1% | 46.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,554,360 | 3.3% | 49.7% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 1,554,300 | 3.3% | 52.9% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 1,554,300 | 3.3% | 56.2% |
| LOAD_FAST LOAD_CONST | 1,434,360 | 3.0% | 59.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,434,300 | 3.0% | 62.2% |
| RETURN_VALUE STORE_FAST | 1,036,260 | 2.2% | 64.3% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 1,036,200 | 2.2% | 66.5% |
| BINARY_OP_ADD_INT BINARY_OP | 1,036,200 | 2.2% | 68.7% |
| BINARY_OP RETURN_VALUE | 1,036,200 | 2.2% | 70.8% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 916,200 | 1.9% | 72.8% |
| LOAD_CONST LOAD_FAST | 916,200 | 1.9% | 74.7% |
| BUILD_TUPLE RETURN_VALUE | 916,200 | 1.9% | 76.6% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 916,200 | 1.9% | 78.5% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 916,200 | 1.9% | 80.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 796,200 | 1.7% | 82.1% |
| STORE_FAST LOAD_FAST | 638,280 | 1.3% | 83.4% |
| LOAD_CONST LOAD_CONST | 638,100 | 1.3% | 84.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 518,160 | 1.1% | 85.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 518,100 | 1.1% | 86.9% |
| RETURN_VALUE COMPARE_OP_INT | 518,100 | 1.1% | 88.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 518,100 | 1.1% | 89.1% |
| CACHE RESUME_CHECK | 518,100 | 1.1% | 90.2% |
| JUMP_BACKWARD LOAD_GLOBAL_MODULE | 409,140 | 0.9% | 91.1% |
| RETURN_VALUE INTERPRETER_EXIT | 398,160 | 0.8% | 91.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 398,140 | 0.8% | 92.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 398,100 | 0.8% | 93.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 398,100 | 0.8% | 94.4% |
| LOAD_FAST CALL_BUILTIN_FAST | 398,100 | 0.8% | 95.2% |
| CALL_BUILTIN_FAST CALL_PY_EXACT_ARGS | 398,100 | 0.8% | 96.1% |
| BINARY_OP_ADD_INT LOAD_CONST | 398,100 | 0.8% | 96.9% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 289,200 | 0.6% | 97.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 228,900 | 0.5% | 98.0% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 120,060 | 0.3% | 98.2% |
| YIELD_VALUE INTERPRETER_EXIT | 120,000 | 0.3% | 98.5% |
| LOAD_FAST YIELD_VALUE | 120,000 | 0.3% | 98.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 120,000 | 0.3% | 99.0% |
| LOAD_CONST BUILD_TUPLE | 120,000 | 0.3% | 99.2% |
| BUILD_TUPLE LOAD_FAST | 120,000 | 0.3% | 99.5% |
| RESUME_CHECK POP_TOP | 119,940 | 0.3% | 99.7% |
| POP_TOP JUMP_BACKWARD | 119,940 | 0.3% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 240 | 0.0% | 100.0% |
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
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |


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
| JUMP_BACKWARD | 119,940 | 99.9% |
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
| BINARY_OP | 1,036,200 | 53.1% |
| BUILD_TUPLE | 916,200 | 46.9% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,036,260 | 53.1% |
| COMPARE_OP_INT | 518,100 | 26.5% |
| INTERPRETER_EXIT | 398,160 | 20.4% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,036,200 | 100.0% |
| BINARY_OP | 240 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,036,200 | 100.0% |
| BINARY_OP | 240 | 0.0% |
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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 289,200 | 70.7% |
| POP_TOP | 119,940 | 29.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 409,140 | 100.0% |


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
| LOAD_FAST | 1,434,360 | 40.9% |
| BINARY_OP_MULTIPLY_INT | 916,200 | 26.1% |
| LOAD_CONST | 638,100 | 18.2% |
| BINARY_OP_ADD_INT | 398,100 | 11.4% |
| LOAD_GLOBAL_MODULE | 120,060 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,036,200 | 29.5% |
| LOAD_FAST | 916,200 | 26.1% |
| BINARY_OP_ADD_INT | 796,200 | 22.7% |
| LOAD_CONST | 638,100 | 18.2% |
| BUILD_TUPLE | 120,000 | 3.4% |


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
| BINARY_OP_MULTIPLY_INT | 2,072,400 | 25.7% |
| RESUME_CHECK | 1,952,400 | 24.3% |
| LOAD_GLOBAL_MODULE | 1,434,300 | 17.8% |
| LOAD_CONST | 916,200 | 11.4% |
| STORE_FAST | 638,280 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 2,072,400 | 25.7% |
| BINARY_OP_ADD_INT | 2,072,400 | 25.7% |
| LOAD_CONST | 1,434,360 | 17.8% |
| BINARY_OP_MULTIPLY_INT | 916,200 | 11.4% |
| LOAD_GLOBAL_MODULE | 518,100 | 6.4% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 2,072,400 | 36.4% |
| BINARY_OP_ADD_INT | 2,072,400 | 36.4% |
| STORE_FAST_STORE_FAST | 1,554,300 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 5,699,100 | 100.0% |


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
| JUMP_BACKWARD | 289,200 | 55.8% |
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
| RETURN_VALUE | 1,036,260 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 638,280 | 61.6% |
| LOAD_GLOBAL_MODULE | 398,140 | 38.4% |
| NOP | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 2,072,400 | 50.0% |
| STORE_FAST_STORE_FAST | 2,072,400 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,072,400 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,554,300 | 37.5% |
| LOAD_FAST | 518,100 | 12.5% |


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
| LOAD_FAST | 2,072,400 | 46.9% |
| BINARY_OP_MULTIPLY_INT | 1,554,300 | 35.1% |
| LOAD_CONST | 796,200 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,072,400 | 46.9% |
| BINARY_OP | 1,036,200 | 23.4% |
| BUILD_TUPLE | 916,200 | 20.7% |
| LOAD_CONST | 398,100 | 9.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,699,100 | 86.2% |
| LOAD_FAST | 916,200 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,072,400 | 31.3% |
| LOAD_FAST | 2,072,400 | 31.3% |
| BINARY_OP_ADD_INT | 1,554,300 | 23.5% |
| LOAD_CONST | 916,200 | 13.8% |


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
| LOAD_FAST | 398,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 398,100 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,036,200 | 66.7% |
| CALL_BUILTIN_FAST | 398,100 | 25.6% |
| LOAD_FAST | 120,000 | 7.7% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,554,360 | 100.0% |
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
| LOAD_FAST | 398,100 | 100.0% |
| RESUME_CHECK | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 398,100 | 100.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,100 | 33.3% |
| JUMP_BACKWARD | 409,140 | 26.3% |
| STORE_FAST | 398,140 | 25.6% |
| POP_JUMP_IF_FALSE | 228,900 | 14.7% |
| LOAD_GLOBAL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,434,300 | 92.3% |
| LOAD_CONST | 120,060 | 7.7% |
| CALL_PY_EXACT_ARGS | 80 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,554,360 | 75.0% |
| CACHE | 518,100 | 25.0% |
| POP_TOP | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,952,400 | 94.2% |
| POP_TOP | 119,940 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,072,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,072,400 | 100.0% |


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
| specialization.deferred |      1036200 | 8.6% |
|          hit |     11038260 | 91.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 7.7% |
| Failure | 240 | 92.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 240 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          360 | 0.0% |
|          hit |      1952640 | 100.0% |

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
|          hit |      1952860 | 100.0% |

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
|          hit |      2072400 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 26,185,440 | 54.8% |
| Not specialized | 1,964,580 | 4.1% |
| Specialized | 19,607,000 | 41.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 1,036,200 | 100.0% |
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
| Calls to PyEval_EvalDefault | 518,220 | 25.0% |
| Calls to Python functions inlined | 1,554,480 | 75.0% |
| Calls via PyEval_EvalFrame (total) | 518,220 | 25.0% |
| Calls via PyEval_EvalFrame (vector) | 398,160 | 19.2% |
| Calls via PyEval_EvalFrame (generator) | 120,060 | 5.8% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 398,160 | 19.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 1,952,640 | 94.2% |
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
| Interpreter increfs | 24,177,880 | 99.7% |
| Interpreter decrefs | 30,265,740 | 83.1% |
| Increfs | 76,420 | 0.3% |
| Decrefs | 6,167,600 | 16.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 20 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
