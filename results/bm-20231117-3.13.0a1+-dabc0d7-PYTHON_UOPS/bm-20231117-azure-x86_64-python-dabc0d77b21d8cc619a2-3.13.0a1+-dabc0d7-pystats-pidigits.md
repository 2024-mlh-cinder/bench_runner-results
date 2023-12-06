
# Pystats results

- benchmark: pidigits
- fork: python
- ref: dabc0d77b21d8cc619a2ffcf859f684b6c1c7020
- commit hash: dabc0d7
- commit date: 2023-11-17T15:11:30-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 4,479,760 | 16.0% | 16.0% |  |
| BINARY_OP_MULTIPLY_INT | 4,135,040 | 14.8% | 30.8% |  |
| LOAD_CONST | 3,586,160 | 12.8% | 43.7% |  |
| BINARY_OP_ADD_INT | 3,187,460 | 11.4% | 55.1% |  |
| LOAD_FAST_LOAD_FAST | 2,383,600 | 8.5% | 63.6% |  |
| RETURN_VALUE | 1,513,680 | 5.4% | 69.0% |  |
| STORE_FAST_STORE_FAST | 1,226,560 | 4.4% | 73.4% |  |
| RESUME_CHECK | 1,143,440 | 4.1% | 77.5% |  |
| BUILD_TUPLE | 996,320 | 3.6% | 81.1% |  |
| INTERPRETER_EXIT | 690,880 | 2.5% | 83.5% |  |
| BINARY_OP | 678,280 | 2.4% | 86.0% |  |
| UNPACK_SEQUENCE_TUPLE | 613,220 | 2.2% | 88.2% |  |
| POP_JUMP_IF_FALSE | 546,080 | 2.0% | 90.1% |  |
| ENTER_EXECUTOR | 544,880 | 2.0% | 92.1% |  |
| COMPARE_OP_INT | 531,220 | 1.9% | 94.0% |  |
| LOAD_GLOBAL_MODULE | 452,800 | 1.6% | 95.6% |  |
| CALL_PY_EXACT_ARGS | 452,560 | 1.6% | 97.2% |  |
| STORE_FAST | 451,920 | 1.6% | 98.8% |  |
| POP_TOP | 160,160 | 0.6% | 99.4% |  |
| YIELD_VALUE | 160,000 | 0.6% | 100.0% |  |
| CALL | 1,040 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 820 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 700 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 680 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 600 | 0.0% | 100.0% |  |
| PUSH_NULL | 400 | 0.0% | 100.0% |  |
| NOP | 160 | 0.0% | 100.0% |  |
| LOAD_DEREF | 160 | 0.0% | 100.0% |  |
| RESUME | 160 | 0.0% | 100.0% |  |
| COMPARE_OP | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 80 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 80 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 2,383,240 | 8.5% | 8.5% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 1,354,200 | 4.8% | 13.4% |
| LOAD_FAST BINARY_OP_ADD_INT | 1,354,160 | 4.8% | 18.2% |
| LOAD_CONST LOAD_FAST | 1,221,600 | 4.4% | 22.6% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 1,221,540 | 4.4% | 27.0% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 1,221,480 | 4.4% | 31.3% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 1,143,300 | 4.1% | 35.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,061,520 | 3.8% | 39.2% |
| RESUME_CHECK LOAD_FAST | 983,300 | 3.5% | 42.8% |
| LOAD_CONST LOAD_CONST | 850,800 | 3.0% | 45.8% |
| BUILD_TUPLE RETURN_VALUE | 836,320 | 3.0% | 48.8% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 836,280 | 3.0% | 51.8% |
| LOAD_FAST LOAD_CONST | 822,720 | 2.9% | 54.7% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 787,600 | 2.8% | 57.5% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 771,640 | 2.8% | 60.3% |
| CACHE RESUME_CHECK | 690,740 | 2.5% | 62.8% |
| BINARY_OP RETURN_VALUE | 677,120 | 2.4% | 65.2% |
| BINARY_OP_ADD_INT BINARY_OP | 677,100 | 2.4% | 67.6% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 613,280 | 2.2% | 69.8% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 613,220 | 2.2% | 72.0% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 613,160 | 2.2% | 74.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 531,220 | 1.9% | 76.1% |
| RETURN_VALUE COMPARE_OP_INT | 531,120 | 1.9% | 78.0% |
| RETURN_VALUE INTERPRETER_EXIT | 530,880 | 1.9% | 79.9% |
| BINARY_OP_ADD_INT LOAD_CONST | 530,780 | 1.9% | 81.8% |
| ENTER_EXECUTOR BINARY_OP_MULTIPLY_INT | 530,080 | 1.9% | 83.7% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 452,560 | 1.6% | 85.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 452,500 | 1.6% | 86.9% |
| RETURN_VALUE STORE_FAST | 451,520 | 1.6% | 88.6% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 385,260 | 1.4% | 89.9% |
| STORE_FAST LOAD_FAST | 306,160 | 1.1% | 91.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 292,460 | 1.0% | 92.1% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 291,680 | 1.0% | 93.1% |
| STORE_FAST_STORE_FAST LOAD_FAST | 160,720 | 0.6% | 93.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 160,320 | 0.6% | 94.3% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 160,040 | 0.6% | 94.9% |
| BUILD_TUPLE LOAD_FAST | 160,000 | 0.6% | 95.4% |
| LOAD_CONST BUILD_TUPLE | 160,000 | 0.6% | 96.0% |
| LOAD_FAST YIELD_VALUE | 160,000 | 0.6% | 96.6% |
| YIELD_VALUE INTERPRETER_EXIT | 160,000 | 0.6% | 97.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 159,960 | 0.6% | 97.7% |
| RESUME_CHECK POP_TOP | 159,900 | 0.6% | 98.3% |
| POP_TOP ENTER_EXECUTOR | 159,580 | 0.6% | 98.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 145,840 | 0.5% | 99.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 145,520 | 0.5% | 99.9% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 14,800 | 0.1% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 700 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 680 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 680 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST CALL_PY_EXACT_ARGS | 680 | 0.0% | 100.0% |
| JUMP_BACKWARD LOAD_GLOBAL_MODULE | 620 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 440 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 360 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| PUSH_NULL CALL | 320 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_MULTIPLY_INT | 240 | 0.0% | 100.0% |
| LOAD_CONST CALL | 240 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 240 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 240 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 240 | 0.0% | 100.0% |
| CALL CALL | 220 | 0.0% | 100.0% |
| CALL POP_TOP | 160 | 0.0% | 100.0% |
| CALL CALL_PY_EXACT_ARGS | 160 | 0.0% | 100.0% |
| LOAD_FAST CALL | 160 | 0.0% | 100.0% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 140 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_INT | 140 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL | 120 | 0.0% | 100.0% |
| LOAD_FAST UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_FAST | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS RETURN_VALUE | 120 | 0.0% | 100.0% |
| CACHE POP_TOP | 80 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 80 | 0.0% | 100.0% |
| POP_TOP NOP | 80 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 80 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 80 | 0.0% | 100.0% |
| RETURN_GENERATOR LOAD_FAST | 80 | 0.0% | 100.0% |
| RETURN_VALUE COMPARE_OP | 80 | 0.0% | 100.0% |
| BINARY_OP LOAD_CONST | 80 | 0.0% | 100.0% |
| CALL LOAD_FAST | 80 | 0.0% | 100.0% |
| CALL STORE_FAST | 80 | 0.0% | 100.0% |
| CALL RESUME_CHECK | 80 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 100.0% |
| LOAD_CONST MAKE_FUNCTION | 80 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP | 80 | 0.0% | 100.0% |
| LOAD_CONST STORE_FAST | 80 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 80 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 80 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 80 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| STORE_FAST NOP | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 80 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| CACHE RESUME | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 690,740 | 100.0% |
| POP_TOP | 80 | 0.0% |
| RESUME | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 530,880 | 76.8% |
| YIELD_VALUE | 160,000 | 23.2% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 50.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 50.0% |
| LOAD_GLOBAL_MODULE | 60 | 37.5% |
| LOAD_GLOBAL | 20 | 12.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 159,900 | 99.8% |
| CALL | 160 | 0.1% |
| CACHE | 80 | 0.0% |
| RESUME | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 159,580 | 99.6% |
| JUMP_BACKWARD | 340 | 0.2% |
| NOP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 60.0% |
| LOAD_DEREF | 80 | 20.0% |
| LOAD_ATTR_MODULE | 60 | 15.0% |
| LOAD_ATTR | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 320 | 80.0% |
| LOAD_FAST | 80 | 20.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 836,320 | 55.3% |
| BINARY_OP | 677,120 | 44.7% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 531,120 | 35.1% |
| INTERPRETER_EXIT | 530,880 | 35.1% |
| STORE_FAST | 451,520 | 29.8% |
| COMPARE_OP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 677,100 | 99.8% |
| BINARY_OP | 440 | 0.1% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |
| LOAD_FAST | 240 | 0.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 677,120 | 99.8% |
| BINARY_OP | 440 | 0.1% |
| BINARY_OP_MULTIPLY_INT | 240 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| BINARY_OP_ADD_INT | 140 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 836,280 | 83.9% |
| LOAD_CONST | 160,000 | 16.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 836,320 | 83.9% |
| LOAD_FAST | 160,000 | 16.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 320 | 30.8% |
| LOAD_CONST | 240 | 23.1% |
| CALL | 220 | 21.2% |
| LOAD_FAST | 160 | 15.4% |
| LOAD_GLOBAL | 40 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 220 | 21.2% |
| POP_TOP | 160 | 15.4% |
| CALL_PY_EXACT_ARGS | 160 | 15.4% |
| CALL_BUILTIN_CLASS | 120 | 11.5% |
| LOAD_FAST | 80 | 7.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 66.7% |
| LOAD_CONST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 50.0% |
| COMPARE_OP_INT | 60 | 50.0% |


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
| POP_JUMP_IF_FALSE | 385,260 | 70.7% |
| POP_TOP | 159,580 | 29.3% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 530,080 | 97.3% |
| POP_JUMP_IF_FALSE | 14,800 | 2.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 340 | 50.0% |
| POP_JUMP_IF_FALSE | 340 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 620 | 91.2% |
| ENTER_EXECUTOR | 40 | 5.9% |
| LOAD_GLOBAL | 20 | 2.9% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40 | 50.0% |
| PUSH_NULL | 20 | 25.0% |
| STORE_FAST | 20 | 25.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 1,221,540 | 34.1% |
| LOAD_CONST | 850,800 | 23.7% |
| LOAD_FAST | 822,720 | 22.9% |
| BINARY_OP_ADD_INT | 530,780 | 14.8% |
| LOAD_GLOBAL_MODULE | 160,040 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,600 | 34.1% |
| BINARY_OP_ADD_INT | 1,061,520 | 29.6% |
| LOAD_CONST | 850,800 | 23.7% |
| CALL_PY_EXACT_ARGS | 291,680 | 8.1% |
| BUILD_TUPLE | 160,000 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 1,354,200 | 30.2% |
| LOAD_CONST | 1,221,600 | 27.3% |
| RESUME_CHECK | 983,300 | 21.9% |
| STORE_FAST | 306,160 | 6.8% |
| LOAD_GLOBAL_MODULE | 292,460 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,354,160 | 30.2% |
| BINARY_OP_MULTIPLY_INT | 1,221,480 | 27.3% |
| LOAD_CONST | 822,720 | 18.4% |
| UNPACK_SEQUENCE_TUPLE | 613,160 | 13.7% |
| YIELD_VALUE | 160,000 | 3.6% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,143,300 | 48.0% |
| BINARY_OP_MULTIPLY_INT | 787,600 | 33.0% |
| STORE_FAST_STORE_FAST | 452,560 | 19.0% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 2,383,240 | 100.0% |
| BINARY_OP | 360 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 20.0% |
| POP_JUMP_IF_FALSE | 80 | 13.3% |
| STORE_FAST | 80 | 13.3% |
| RESUME | 60 | 10.0% |
| RESUME_CHECK | 60 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240 | 40.0% |
| LOAD_FAST | 120 | 20.0% |
| LOAD_CONST | 60 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 10.0% |
| CALL | 40 | 6.7% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 531,220 | 97.3% |
| ENTER_EXECUTOR | 14,800 | 2.7% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 385,260 | 70.6% |
| LOAD_GLOBAL_MODULE | 160,320 | 29.4% |
| JUMP_BACKWARD | 340 | 0.1% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 451,520 | 99.9% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,160 | 67.7% |
| LOAD_GLOBAL_MODULE | 145,520 | 32.2% |
| NOP | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 613,280 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 613,220 | 50.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 613,280 | 50.0% |
| LOAD_FAST_LOAD_FAST | 452,560 | 36.9% |
| LOAD_FAST | 160,720 | 13.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 50.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 160,000 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 60 | 37.5% |
| CALL | 60 | 37.5% |
| POP_TOP | 20 | 12.5% |
| COPY_FREE_VARS | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 37.5% |
| LOAD_GLOBAL | 60 | 37.5% |
| POP_TOP | 20 | 12.5% |
| LOAD_CONST | 20 | 12.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,354,160 | 42.5% |
| LOAD_CONST | 1,061,520 | 33.3% |
| BINARY_OP_MULTIPLY_INT | 771,640 | 24.2% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,143,300 | 35.9% |
| BUILD_TUPLE | 836,280 | 26.2% |
| BINARY_OP | 677,100 | 21.2% |
| LOAD_CONST | 530,780 | 16.7% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,383,240 | 57.6% |
| LOAD_FAST | 1,221,480 | 29.5% |
| ENTER_EXECUTOR | 530,080 | 12.8% |
| BINARY_OP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,354,200 | 32.7% |
| LOAD_CONST | 1,221,540 | 29.5% |
| LOAD_FAST_LOAD_FAST | 787,600 | 19.0% |
| BINARY_OP_ADD_INT | 771,640 | 18.7% |
| BINARY_OP | 60 | 0.0% |


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
| LOAD_FAST | 680 | 97.1% |
| CALL | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 680 | 97.1% |
| CALL | 20 | 2.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 291,680 | 64.5% |
| LOAD_FAST | 159,960 | 35.3% |
| CALL_BUILTIN_FAST | 680 | 0.2% |
| CALL | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 452,500 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 531,120 | 100.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 531,220 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| LOAD_ATTR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 82.9% |
| RESUME_CHECK | 80 | 9.8% |
| LOAD_GLOBAL | 60 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 700 | 85.4% |
| LOAD_CONST | 60 | 7.3% |
| LOAD_GLOBAL_MODULE | 40 | 4.9% |
| LOAD_GLOBAL | 20 | 2.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 160,320 | 35.4% |
| LOAD_FAST | 145,840 | 32.2% |
| STORE_FAST | 145,520 | 32.1% |
| JUMP_BACKWARD | 620 | 0.1% |
| LOAD_GLOBAL | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 292,460 | 64.6% |
| LOAD_CONST | 160,040 | 35.3% |
| CALL_PY_EXACT_ARGS | 80 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 690,740 | 60.4% |
| CALL_PY_EXACT_ARGS | 452,500 | 39.6% |
| CALL | 80 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,300 | 86.0% |
| POP_TOP | 159,900 | 14.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 613,160 | 100.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 613,220 | 100.0% |


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
|     deferred | 677,520 | 8.5% |
|          hit | 7,322,560 | 91.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 52.6% |
| Failure | 360 | 47.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 360 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 700 | 0.2% |
|          hit | 453,380 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 64.7% |
| Failure | 120 | 35.3% |

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
|     deferred | 60 | 0.0% |
|          hit | 531,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 20.0% |
|          hit | 120 | 60.0% |

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
|     deferred | 300 | 0.1% |
|          hit | 453,620 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 300 | 100.0% |
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
|     deferred | 60 | 0.0% |
|          hit | 613,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 16,195,800 | 58.0% |
| Not specialized | 1,226,320 | 4.4% |
| Specialized hits | 10,517,560 | 37.6% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 677,520 | 99.8% |
| CALL | 700 | 0.1% |
| LOAD_GLOBAL | 300 | 0.0% |
| COMPARE_OP | 60 | 0.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 0 | 0.0% |


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
| Calls to PyEval_EvalDefault | 690,880 | 60.4% |
| Calls to Python functions inlined | 452,800 | 39.6% |
| Calls via PyEval_EvalFrame (total) | 690,880 | 60.4% |
| Calls via PyEval_EvalFrame (vector) | 530,880 | 46.4% |
| Calls via PyEval_EvalFrame (generator) | 160,000 | 14.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 530,880 | 46.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 2,072,400 | 181.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,382,000 | 8.5% |
| Frees to freelist | 1,382,020 |  |
| Allocations | 14,856,680 | 91.5% |
| Allocations to 512 bytes | 4,729,040 | 29.1% |
| Allocations to 4 kbytes | 3,817,160 | 23.5% |
| Allocations over 4 kbytes | 6,310,480 | 38.9% |
| Frees | 14,856,541 |  |
| New values | 0 |  |
| Interpreter increfs | 32,781,720 | 99.7% |
| Interpreter decrefs | 40,899,200 | 83.3% |
| Increfs | 101,880 | 0.3% |
| Decrefs | 8,222,881 | 16.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 14 |  |
| Method cache misses | 26 |  |
| Method cache collisions | 29 |  |
| Method cache dunder hits | 60 |  |
| Method cache dunder misses | 20 |  |


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
| Trace too long | 40 | 100.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 544,880 |  |
| Uops executed | 79,639,040 | 146.16 |

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
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 0 | 0.0% |
| <= 256 | 40 | 100.0% |


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
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 0 | 0.0% |
| <= 256 | 40 | 100.0% |


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
| <= 128 | 14,800 | 2.7% |
| <= 256 | 530,080 | 97.3% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 16,684,080 | 20.9% | 20.9% |  |
| _SET_IP | 11,883,760 | 14.9% | 35.9% |  |
| STORE_FAST | 9,529,840 | 12.0% | 47.8% |  |
| _GUARD_BOTH_INT | 7,394,720 | 9.3% | 57.1% |  |
| _BINARY_OP_MULTIPLY_INT | 4,685,120 | 5.9% | 63.0% |  |
| _CHECK_VALIDITY | 3,784,560 | 4.8% | 67.8% |  |
| _BINARY_OP_ADD_INT | 2,709,600 | 3.4% | 71.2% |  |
| UNPACK_SEQUENCE_TUPLE | 2,149,920 | 2.7% | 73.9% |  |
| _GUARD_GLOBALS_VERSION | 2,149,920 | 2.7% | 76.6% |  |
| RESUME_CHECK | 1,619,840 | 2.0% | 78.6% |  |
| _LOAD_GLOBAL_MODULE | 1,619,840 | 2.0% | 80.6% |  |
| _CHECK_PEP_523 | 1,619,840 | 2.0% | 82.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 1,619,840 | 2.0% | 84.7% |  |
| _CHECK_STACK_SPACE | 1,619,840 | 2.0% | 86.7% |  |
| _INIT_CALL_PY_EXACT_ARGS | 1,619,840 | 2.0% | 88.8% |  |
| _PUSH_FRAME | 1,619,840 | 2.0% | 90.8% |  |
| _SAVE_RETURN_OFFSET | 1,619,840 | 2.0% | 92.8% |  |
| LOAD_CONST | 1,089,760 | 1.4% | 94.2% |  |
| _POP_FRAME | 1,089,760 | 1.4% | 95.6% |  |
| _BINARY_OP | 704,480 | 0.9% | 96.5% |  |
| CALL_BUILTIN_FAST | 530,080 | 0.7% | 97.1% |  |
| _EXIT_TRACE | 530,080 | 0.7% | 97.8% |  |
| _GUARD_BUILTINS_VERSION | 530,080 | 0.7% | 98.4% |  |
| _LOAD_GLOBAL_BUILTINS | 530,080 | 0.7% | 99.1% |  |
| BUILD_TUPLE | 385,280 | 0.5% | 99.6% |  |
| _GUARD_IS_TRUE_POP | 159,600 | 0.2% | 99.8% | 9.3% |
| COMPARE_OP_INT | 159,600 | 0.2% | 100.0% |  |


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
Stats gathered on: 2023-11-18
