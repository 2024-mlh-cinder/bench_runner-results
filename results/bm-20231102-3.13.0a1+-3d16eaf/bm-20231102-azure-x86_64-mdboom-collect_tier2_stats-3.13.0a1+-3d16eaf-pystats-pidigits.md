
# Pystats results

- benchmark: pidigits
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 7,783,360 | 17.7% | 17.7% |  |
| BINARY_OP_MULTIPLY_INT | 5,804,000 | 13.2% | 30.9% |  |
| LOAD_FAST_LOAD_FAST | 4,582,640 | 10.4% | 41.3% |  |
| BINARY_OP_ADD_INT | 4,422,020 | 10.0% | 51.3% |  |
| LOAD_CONST | 4,131,040 | 9.4% | 60.7% |  |
| STORE_FAST_STORE_FAST | 2,895,520 | 6.6% | 67.3% |  |
| RETURN_VALUE | 2,218,160 | 5.0% | 72.3% |  |
| RESUME_CHECK | 1,833,120 | 4.2% | 76.5% |  |
| UNPACK_SEQUENCE_TUPLE | 1,447,700 | 3.3% | 79.8% |  |
| BINARY_OP | 1,382,920 | 3.1% | 82.9% |  |
| LOAD_GLOBAL_MODULE | 1,142,480 | 2.6% | 85.5% |  |
| CALL_PY_EXACT_ARGS | 1,142,240 | 2.6% | 88.1% |  |
| STORE_FAST | 996,800 | 2.3% | 90.4% |  |
| BUILD_TUPLE | 996,320 | 2.3% | 92.7% |  |
| INTERPRETER_EXIT | 690,880 | 1.6% | 94.2% |  |
| POP_JUMP_IF_FALSE | 690,880 | 1.6% | 95.8% |  |
| COMPARE_OP_INT | 690,820 | 1.6% | 97.4% |  |
| ENTER_EXECUTOR | 544,880 | 1.2% | 98.6% |  |
| POP_TOP | 160,160 | 0.4% | 99.0% |  |
| YIELD_VALUE | 160,000 | 0.4% | 99.3% |  |
| LOAD_GLOBAL_BUILTIN | 145,620 | 0.3% | 99.7% |  |
| CALL_BUILTIN_FAST | 145,500 | 0.3% | 100.0% |  |
| CALL | 1,040 | 0.0% | 100.0% |  |
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
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 4,582,280 | 10.4% | 10.4% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 2,443,960 | 5.6% | 16.0% |
| LOAD_FAST BINARY_OP_ADD_INT | 2,443,920 | 5.6% | 21.5% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 1,832,980 | 4.2% | 25.7% |
| RESUME_CHECK LOAD_FAST | 1,672,980 | 3.8% | 29.5% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 1,447,760 | 3.3% | 32.8% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,447,700 | 3.3% | 36.1% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,447,640 | 3.3% | 39.4% |
| BINARY_OP RETURN_VALUE | 1,381,600 | 3.1% | 42.5% |
| LOAD_FAST LOAD_CONST | 1,367,600 | 3.1% | 45.6% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 1,222,000 | 2.8% | 48.4% |
| BINARY_OP_ADD_INT BINARY_OP | 1,221,980 | 2.8% | 51.2% |
| LOAD_CONST LOAD_FAST | 1,221,600 | 2.8% | 53.9% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 1,221,540 | 2.8% | 56.7% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 1,221,480 | 2.8% | 59.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 1,142,240 | 2.6% | 62.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,142,180 | 2.6% | 64.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,061,520 | 2.4% | 67.1% |
| RETURN_VALUE STORE_FAST | 996,400 | 2.3% | 69.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 982,140 | 2.2% | 71.6% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 916,440 | 2.1% | 73.7% |
| STORE_FAST LOAD_FAST | 851,040 | 1.9% | 75.6% |
| LOAD_CONST LOAD_CONST | 850,800 | 1.9% | 77.5% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 836,560 | 1.9% | 79.4% |
| BUILD_TUPLE RETURN_VALUE | 836,320 | 1.9% | 81.3% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 836,280 | 1.9% | 83.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 690,820 | 1.6% | 84.8% |
| CACHE RESUME_CHECK | 690,740 | 1.6% | 86.4% |
| RETURN_VALUE COMPARE_OP_INT | 690,720 | 1.6% | 87.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 690,720 | 1.6% | 89.5% |
| RETURN_VALUE INTERPRETER_EXIT | 530,880 | 1.2% | 90.7% |
| BINARY_OP_ADD_INT LOAD_CONST | 530,780 | 1.2% | 91.9% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 385,280 | 0.9% | 92.8% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 385,260 | 0.9% | 93.7% |
| STORE_FAST_STORE_FAST LOAD_FAST | 305,520 | 0.7% | 94.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 305,120 | 0.7% | 95.1% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 160,040 | 0.4% | 95.4% |
| YIELD_VALUE INTERPRETER_EXIT | 160,000 | 0.4% | 95.8% |
| BUILD_TUPLE LOAD_FAST | 160,000 | 0.4% | 96.1% |
| LOAD_CONST BUILD_TUPLE | 160,000 | 0.4% | 96.5% |
| LOAD_FAST YIELD_VALUE | 160,000 | 0.4% | 96.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 159,960 | 0.4% | 97.2% |
| RESUME_CHECK POP_TOP | 159,900 | 0.4% | 97.6% |
| ENTER_EXECUTOR BINARY_OP | 159,600 | 0.4% | 98.0% |
| POP_TOP ENTER_EXECUTOR | 159,580 | 0.4% | 98.3% |
| STORE_FAST LOAD_GLOBAL_MODULE | 145,520 | 0.3% | 98.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 145,500 | 0.3% | 99.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 145,480 | 0.3% | 99.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 145,480 | 0.3% | 99.6% |
| CALL_BUILTIN_FAST CALL_PY_EXACT_ARGS | 145,480 | 0.3% | 100.0% |
| JUMP_BACKWARD LOAD_GLOBAL_MODULE | 620 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 600 | 0.0% | 100.0% |
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
| BINARY_OP | 1,381,600 | 62.3% |
| BUILD_TUPLE | 836,320 | 37.7% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 996,400 | 44.9% |
| COMPARE_OP_INT | 690,720 | 31.1% |
| INTERPRETER_EXIT | 530,880 | 23.9% |
| COMPARE_OP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


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

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,221,980 | 88.4% |
| ENTER_EXECUTOR | 159,600 | 11.5% |
| BINARY_OP | 600 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,381,600 | 99.9% |
| BINARY_OP | 600 | 0.0% |
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
| LOAD_FAST_LOAD_FAST | 385,280 | 70.7% |
| BINARY_OP | 159,600 | 29.3% |


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
| LOAD_FAST | 1,367,600 | 33.1% |
| BINARY_OP_MULTIPLY_INT | 1,221,540 | 29.6% |
| LOAD_CONST | 850,800 | 20.6% |
| BINARY_OP_ADD_INT | 530,780 | 12.8% |
| LOAD_GLOBAL_MODULE | 160,040 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,600 | 29.6% |
| BINARY_OP_ADD_INT | 1,061,520 | 25.7% |
| LOAD_CONST | 850,800 | 20.6% |
| CALL_PY_EXACT_ARGS | 836,560 | 20.3% |
| BUILD_TUPLE | 160,000 | 3.9% |


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
| BINARY_OP_MULTIPLY_INT | 2,443,960 | 31.4% |
| RESUME_CHECK | 1,672,980 | 21.5% |
| LOAD_CONST | 1,221,600 | 15.7% |
| LOAD_GLOBAL_MODULE | 982,140 | 12.6% |
| STORE_FAST | 851,040 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,443,920 | 31.4% |
| UNPACK_SEQUENCE_TUPLE | 1,447,640 | 18.6% |
| LOAD_CONST | 1,367,600 | 17.6% |
| BINARY_OP_MULTIPLY_INT | 1,221,480 | 15.7% |
| LOAD_GLOBAL_MODULE | 690,720 | 8.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,832,980 | 40.0% |
| BINARY_OP_MULTIPLY_INT | 1,222,000 | 26.7% |
| STORE_FAST_STORE_FAST | 1,142,240 | 24.9% |
| ENTER_EXECUTOR | 385,280 | 8.4% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 4,582,280 | 100.0% |
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
| COMPARE_OP_INT | 690,820 | 100.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 385,260 | 55.8% |
| LOAD_GLOBAL_MODULE | 305,120 | 44.2% |
| JUMP_BACKWARD | 340 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 996,400 | 100.0% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 851,040 | 85.4% |
| LOAD_GLOBAL_MODULE | 145,520 | 14.6% |
| NOP | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,447,760 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 1,447,700 | 50.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,447,760 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,142,240 | 39.4% |
| LOAD_FAST | 305,520 | 10.6% |


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
| LOAD_FAST | 2,443,920 | 55.3% |
| LOAD_CONST | 1,061,520 | 24.0% |
| BINARY_OP_MULTIPLY_INT | 916,440 | 20.7% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,832,980 | 41.5% |
| BINARY_OP | 1,221,980 | 27.6% |
| BUILD_TUPLE | 836,280 | 18.9% |
| LOAD_CONST | 530,780 | 12.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,582,280 | 79.0% |
| LOAD_FAST | 1,221,480 | 21.0% |
| BINARY_OP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,443,960 | 42.1% |
| LOAD_FAST_LOAD_FAST | 1,222,000 | 21.1% |
| LOAD_CONST | 1,221,540 | 21.0% |
| BINARY_OP_ADD_INT | 916,440 | 15.8% |
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
| LOAD_FAST | 145,480 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 145,480 | 100.0% |
| CALL | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 836,560 | 73.2% |
| LOAD_FAST | 159,960 | 14.0% |
| CALL_BUILTIN_FAST | 145,480 | 12.7% |
| CALL | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,142,180 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 690,720 | 100.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 690,820 | 100.0% |


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
| LOAD_FAST | 145,480 | 99.9% |
| RESUME_CHECK | 80 | 0.1% |
| LOAD_GLOBAL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 145,500 | 99.9% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 690,720 | 60.5% |
| POP_JUMP_IF_FALSE | 305,120 | 26.7% |
| STORE_FAST | 145,520 | 12.7% |
| JUMP_BACKWARD | 620 | 0.1% |
| LOAD_GLOBAL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 982,140 | 86.0% |
| LOAD_CONST | 160,040 | 14.0% |
| CALL_PY_EXACT_ARGS | 80 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,142,180 | 62.3% |
| CACHE | 690,740 | 37.7% |
| CALL | 80 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,672,980 | 91.3% |
| POP_TOP | 159,900 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,447,640 | 100.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,447,700 | 100.0% |


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
|     deferred | 1,382,000 | 11.9% |
|          hit | 10,226,080 | 88.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 43.5% |
| Failure | 520 | 56.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 520 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 700 | 0.1% |
|          hit | 1,287,860 | 99.9% |

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
|          hit | 690,820 | 100.0% |

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
|     deferred | 300 | 0.0% |
|          hit | 1,288,100 | 100.0% |

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
|          hit | 1,447,700 | 100.0% |

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
| Basic | 25,161,640 | 57.2% |
| Not specialized | 2,075,760 | 4.7% |
| Specialized hits | 16,773,800 | 38.1% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 1,382,000 | 99.9% |
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
| Calls to PyEval_EvalDefault | 690,880 | 37.7% |
| Calls to Python functions inlined | 1,142,480 | 62.3% |
| Calls via PyEval_EvalFrame (total) | 690,880 | 37.7% |
| Calls via PyEval_EvalFrame (vector) | 530,880 | 29.0% |
| Calls via PyEval_EvalFrame (generator) | 160,000 | 8.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 530,880 | 29.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 2,072,400 | 113.0% |


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
| Frees | 14,856,540 |  |
| New values | 0 |  |
| Interpreter increfs | 32,781,720 | 99.7% |
| Interpreter decrefs | 40,899,200 | 83.3% |
| Increfs | 101,880 | 0.3% |
| Decrefs | 8,222,880 | 16.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 21 |  |
| Method cache misses | 19 |  |
| Method cache collisions | 32 |  |
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
| Trace too long | 20 | 50.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 544,880 |  |
| Uops executed | 46,998,000 | 86.25 |

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
| <= 64 | 20 | 50.0% |
| <= 128 | 20 | 50.0% |


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
| <= 64 | 20 | 50.0% |
| <= 128 | 20 | 50.0% |


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
| <= 64 | 159,600 | 29.3% |
| <= 128 | 385,280 | 70.7% |


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
| BINARY_OP | 20 |


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
