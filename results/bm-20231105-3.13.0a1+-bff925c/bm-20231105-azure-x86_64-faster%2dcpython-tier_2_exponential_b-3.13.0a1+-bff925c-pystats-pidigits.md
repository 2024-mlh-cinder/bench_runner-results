
# Pystats results

- benchmark: pidigits
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 6,695,420 | 17.0% | 17.0% |  |
| BINARY_OP_MULTIPLY_INT | 5,484,580 | 13.9% | 30.9% |  |
| LOAD_FAST_LOAD_FAST | 4,263,220 | 10.8% | 41.7% |  |
| BINARY_OP_ADD_INT | 4,102,680 | 10.4% | 52.1% |  |
| LOAD_CONST | 3,971,380 | 10.1% | 62.2% |  |
| STORE_FAST_STORE_FAST | 2,576,120 | 6.5% | 68.7% |  |
| RETURN_VALUE | 1,898,900 | 4.8% | 73.5% |  |
| RESUME_CHECK | 1,673,440 | 4.2% | 77.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,288,000 | 3.3% | 81.0% |  |
| BINARY_OP | 1,063,600 | 2.7% | 83.7% |  |
| BUILD_TUPLE | 996,300 | 2.5% | 86.2% |  |
| CALL_PY_EXACT_ARGS | 982,560 | 2.5% | 88.7% |  |
| LOAD_GLOBAL_MODULE | 837,980 | 2.1% | 90.9% |  |
| STORE_FAST | 837,160 | 2.1% | 93.0% |  |
| INTERPRETER_EXIT | 690,880 | 1.8% | 94.7% |  |
| ENTER_EXECUTOR | 544,920 | 1.4% | 96.1% |  |
| POP_JUMP_IF_FALSE | 531,260 | 1.3% | 97.5% |  |
| COMPARE_OP_INT | 531,200 | 1.3% | 98.8% |  |
| POP_TOP | 160,160 | 0.4% | 99.2% |  |
| YIELD_VALUE | 160,000 | 0.4% | 99.6% |  |
| CALL_BUILTIN_FAST | 145,480 | 0.4% | 100.0% |  |
| CALL | 1,040 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 780 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 640 | 0.0% | 100.0% |  |
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
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_INT | 4,262,860 | 10.8% | 10.8% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 2,124,680 | 5.4% | 16.2% |
| LOAD_FAST BINARY_OP_ADD_INT | 2,124,640 | 5.4% | 21.6% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 1,673,300 | 4.2% | 25.8% |
| RESUME_CHECK LOAD_FAST | 1,513,300 | 3.8% | 29.7% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 1,288,060 | 3.3% | 32.9% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,288,000 | 3.3% | 36.2% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,287,940 | 3.3% | 39.5% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST_LOAD_FAST | 1,221,920 | 3.1% | 42.6% |
| LOAD_CONST LOAD_FAST | 1,221,600 | 3.1% | 45.7% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 1,221,540 | 3.1% | 48.8% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 1,221,480 | 3.1% | 51.8% |
| LOAD_FAST LOAD_CONST | 1,207,940 | 3.1% | 54.9% |
| BINARY_OP RETURN_VALUE | 1,062,360 | 2.7% | 57.6% |
| BINARY_OP_ADD_INT BINARY_OP | 1,062,340 | 2.7% | 60.3% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,061,520 | 2.7% | 63.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 982,560 | 2.5% | 65.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 982,500 | 2.5% | 68.0% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 916,380 | 2.3% | 70.3% |
| LOAD_CONST LOAD_CONST | 850,800 | 2.2% | 72.5% |
| RETURN_VALUE STORE_FAST | 836,760 | 2.1% | 74.6% |
| BUILD_TUPLE RETURN_VALUE | 836,300 | 2.1% | 76.7% |
| BINARY_OP_ADD_INT BUILD_TUPLE | 836,260 | 2.1% | 78.8% |
| STORE_FAST LOAD_FAST | 691,420 | 1.8% | 80.6% |
| CACHE RESUME_CHECK | 690,740 | 1.8% | 82.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 677,640 | 1.7% | 84.0% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 676,900 | 1.7% | 85.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 531,200 | 1.3% | 87.1% |
| RETURN_VALUE COMPARE_OP_INT | 531,100 | 1.3% | 88.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 531,100 | 1.3% | 89.8% |
| RETURN_VALUE INTERPRETER_EXIT | 530,880 | 1.3% | 91.1% |
| BINARY_OP_ADD_INT LOAD_CONST | 530,780 | 1.3% | 92.5% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 385,300 | 1.0% | 93.5% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 385,280 | 1.0% | 94.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 305,500 | 0.8% | 95.2% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 160,040 | 0.4% | 95.6% |
| BUILD_TUPLE LOAD_FAST | 160,000 | 0.4% | 96.0% |
| LOAD_CONST BUILD_TUPLE | 160,000 | 0.4% | 96.4% |
| LOAD_FAST YIELD_VALUE | 160,000 | 0.4% | 96.8% |
| YIELD_VALUE INTERPRETER_EXIT | 160,000 | 0.4% | 97.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 159,960 | 0.4% | 97.6% |
| RESUME_CHECK POP_TOP | 159,900 | 0.4% | 98.1% |
| POP_TOP ENTER_EXECUTOR | 159,600 | 0.4% | 98.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 145,500 | 0.4% | 98.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 145,500 | 0.4% | 99.2% |
| CALL_BUILTIN_FAST CALL_PY_EXACT_ARGS | 145,460 | 0.4% | 99.6% |
| ENTER_EXECUTOR CALL_BUILTIN_FAST | 144,820 | 0.4% | 99.9% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 14,800 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 660 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 640 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 640 | 0.0% | 100.0% |
| JUMP_BACKWARD LOAD_GLOBAL_MODULE | 580 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 520 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 360 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 320 | 0.0% | 100.0% |
| PUSH_NULL CALL | 320 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 320 | 0.0% | 100.0% |
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
| ENTER_EXECUTOR | 159,600 | 99.7% |
| JUMP_BACKWARD | 320 | 0.2% |
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
| BINARY_OP | 1,062,360 | 55.9% |
| BUILD_TUPLE | 836,300 | 44.0% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 836,760 | 44.1% |
| COMPARE_OP_INT | 531,100 | 28.0% |
| INTERPRETER_EXIT | 530,880 | 28.0% |
| COMPARE_OP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,062,340 | 99.9% |
| BINARY_OP | 520 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_FAST | 240 | 0.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,062,360 | 99.9% |
| BINARY_OP | 520 | 0.0% |
| BINARY_OP_MULTIPLY_INT | 240 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| BINARY_OP_ADD_INT | 140 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 836,260 | 83.9% |
| LOAD_CONST | 160,000 | 16.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 836,300 | 83.9% |
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
| POP_JUMP_IF_FALSE | 385,280 | 70.7% |
| POP_TOP | 159,600 | 29.3% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 385,300 | 70.7% |
| CALL_BUILTIN_FAST | 144,820 | 26.6% |
| LOAD_GLOBAL_MODULE | 14,800 | 2.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 320 | 50.0% |
| POP_JUMP_IF_FALSE | 320 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 580 | 90.6% |
| ENTER_EXECUTOR | 40 | 6.2% |
| LOAD_GLOBAL | 20 | 3.1% |


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
| BINARY_OP_MULTIPLY_INT | 1,221,540 | 30.8% |
| LOAD_FAST | 1,207,940 | 30.4% |
| LOAD_CONST | 850,800 | 21.4% |
| BINARY_OP_ADD_INT | 530,780 | 13.4% |
| LOAD_GLOBAL_MODULE | 160,040 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,600 | 30.8% |
| BINARY_OP_ADD_INT | 1,061,520 | 26.7% |
| LOAD_CONST | 850,800 | 21.4% |
| CALL_PY_EXACT_ARGS | 676,900 | 17.0% |
| BUILD_TUPLE | 160,000 | 4.0% |


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
| BINARY_OP_MULTIPLY_INT | 2,124,680 | 31.7% |
| RESUME_CHECK | 1,513,300 | 22.6% |
| LOAD_CONST | 1,221,600 | 18.2% |
| STORE_FAST | 691,420 | 10.3% |
| LOAD_GLOBAL_MODULE | 677,640 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,124,640 | 31.7% |
| UNPACK_SEQUENCE_TUPLE | 1,287,940 | 19.2% |
| BINARY_OP_MULTIPLY_INT | 1,221,480 | 18.2% |
| LOAD_CONST | 1,207,940 | 18.0% |
| LOAD_GLOBAL_MODULE | 531,100 | 7.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,673,300 | 39.2% |
| BINARY_OP_MULTIPLY_INT | 1,221,920 | 28.7% |
| STORE_FAST_STORE_FAST | 982,560 | 23.0% |
| ENTER_EXECUTOR | 385,300 | 9.0% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 4,262,860 | 100.0% |
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
| COMPARE_OP_INT | 531,200 | 100.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 385,280 | 72.5% |
| LOAD_GLOBAL_MODULE | 145,500 | 27.4% |
| JUMP_BACKWARD | 320 | 0.1% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 836,760 | 100.0% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 691,420 | 82.6% |
| LOAD_GLOBAL_MODULE | 145,500 | 17.4% |
| NOP | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,288,060 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 1,288,000 | 50.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,288,060 | 50.0% |
| LOAD_FAST_LOAD_FAST | 982,560 | 38.1% |
| LOAD_FAST | 305,500 | 11.9% |


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
| LOAD_FAST | 2,124,640 | 51.8% |
| LOAD_CONST | 1,061,520 | 25.9% |
| BINARY_OP_MULTIPLY_INT | 916,380 | 22.3% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,673,300 | 40.8% |
| BINARY_OP | 1,062,340 | 25.9% |
| BUILD_TUPLE | 836,260 | 20.4% |
| LOAD_CONST | 530,780 | 12.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,262,860 | 77.7% |
| LOAD_FAST | 1,221,480 | 22.3% |
| BINARY_OP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,124,680 | 38.7% |
| LOAD_FAST_LOAD_FAST | 1,221,920 | 22.3% |
| LOAD_CONST | 1,221,540 | 22.3% |
| BINARY_OP_ADD_INT | 916,380 | 16.7% |
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
| ENTER_EXECUTOR | 144,820 | 99.5% |
| LOAD_FAST | 640 | 0.4% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 145,460 | 100.0% |
| CALL | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 676,900 | 68.9% |
| LOAD_FAST | 159,960 | 16.3% |
| CALL_BUILTIN_FAST | 145,460 | 14.8% |
| CALL | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 982,500 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 531,100 | 100.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 531,200 | 100.0% |


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
| LOAD_FAST | 640 | 82.1% |
| RESUME_CHECK | 80 | 10.3% |
| LOAD_GLOBAL | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 660 | 84.6% |
| LOAD_CONST | 60 | 7.7% |
| LOAD_GLOBAL_MODULE | 40 | 5.1% |
| LOAD_GLOBAL | 20 | 2.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 531,100 | 63.4% |
| POP_JUMP_IF_FALSE | 145,500 | 17.4% |
| STORE_FAST | 145,500 | 17.4% |
| ENTER_EXECUTOR | 14,800 | 1.8% |
| JUMP_BACKWARD | 580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 677,640 | 80.9% |
| LOAD_CONST | 160,040 | 19.1% |
| CALL_PY_EXACT_ARGS | 80 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 982,500 | 58.7% |
| CACHE | 690,740 | 41.3% |
| CALL | 80 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,513,300 | 90.4% |
| POP_TOP | 159,900 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,287,940 | 100.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,288,000 | 100.0% |


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
|     deferred | 1,062,760 | 10.0% |
|          hit | 9,587,320 | 90.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 47.6% |
| Failure | 440 | 52.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 440 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 700 | 0.1% |
|          hit | 1,128,160 | 99.9% |

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
|          hit | 531,200 | 100.0% |

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
|          hit | 838,760 | 99.9% |

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
|          hit | 1,288,000 | 100.0% |

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
| Basic | 22,796,300 | 57.8% |
| Not specialized | 1,596,820 | 4.0% |
| Specialized hits | 15,047,000 | 38.2% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 1,062,760 | 99.9% |
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
| Calls to PyEval_EvalDefault | 690,880 | 41.3% |
| Calls to Python functions inlined | 982,800 | 58.7% |
| Calls via PyEval_EvalFrame (total) | 690,880 | 41.3% |
| Calls via PyEval_EvalFrame (vector) | 530,880 | 31.7% |
| Calls via PyEval_EvalFrame (generator) | 160,000 | 9.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 530,880 | 31.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 2,072,400 | 123.8% |


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
| Frees | 14,856,544 |  |
| New values | 0 |  |
| Interpreter increfs | 32,781,760 | 99.7% |
| Interpreter decrefs | 40,899,240 | 83.3% |
| Increfs | 101,880 | 0.3% |
| Decrefs | 8,222,884 | 16.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 20 |  |
| Method cache misses | 20 |  |
| Method cache collisions | 40 |  |
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
| Traces executed | 544,920 |  |
| Uops executed | 56,285,300 | 103.29 |

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
| <= 128 | 40 | 100.0% |


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
| <= 128 | 40 | 100.0% |


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
| <= 128 | 544,920 | 100.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 12,343,940 | 21.9% | 21.9% |  |
| LOAD_FAST | 10,709,180 | 19.0% | 41.0% |  |
| STORE_FAST | 6,445,480 | 11.5% | 52.4% |  |
| _GUARD_BOTH_INT | 5,129,960 | 9.1% | 61.5% |  |
| _BINARY_OP_MULTIPLY_INT | 3,335,580 | 5.9% | 67.4% |  |
| _BINARY_OP_ADD_INT | 1,794,380 | 3.2% | 70.6% |  |
| _GUARD_GLOBALS_VERSION | 1,764,780 | 3.1% | 73.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,475,140 | 2.6% | 76.4% |  |
| _LOAD_GLOBAL_MODULE | 1,234,660 | 2.2% | 78.6% |  |
| RESUME_CHECK | 1,089,840 | 1.9% | 80.5% |  |
| _CHECK_PEP_523 | 1,089,840 | 1.9% | 82.5% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 1,089,840 | 1.9% | 84.4% |  |
| _CHECK_STACK_SPACE | 1,089,840 | 1.9% | 86.3% |  |
| _INIT_CALL_PY_EXACT_ARGS | 1,089,840 | 1.9% | 88.3% |  |
| _PUSH_FRAME | 1,089,840 | 1.9% | 90.2% |  |
| _SAVE_RETURN_OFFSET | 1,089,840 | 1.9% | 92.1% |  |
| LOAD_CONST | 704,540 | 1.3% | 93.4% |  |
| _POP_FRAME | 704,540 | 1.3% | 94.6% |  |
| _EXIT_TRACE | 544,920 | 1.0% | 95.6% |  |
| _GUARD_BUILTINS_VERSION | 530,120 | 0.9% | 96.6% |  |
| _LOAD_GLOBAL_BUILTINS | 530,120 | 0.9% | 97.5% |  |
| BUILD_TUPLE | 385,300 | 0.7% | 98.2% |  |
| CALL_BUILTIN_FAST | 385,300 | 0.7% | 98.9% |  |
| _BINARY_OP | 319,240 | 0.6% | 99.4% |  |
| COMPARE_OP_INT | 159,620 | 0.3% | 99.7% |  |
| _POP_JUMP_IF_FALSE | 159,620 | 0.3% | 100.0% |  |


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
Stats gathered on: 2023-11-08
