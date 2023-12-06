
# Pystats results

- benchmark: generators
- fork: python
- ref: main
- commit hash: 84b7e9e
- commit date: 2023-10-14T23:32:57+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| RESUME_CHECK | 418,551,420 | 17.5% | 17.5% | 0.0% |
| YIELD_VALUE | 376,548,780 | 15.8% | 33.3% |  |
| SEND_GEN | 376,548,480 | 15.8% | 49.1% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 352,548,180 | 14.8% | 63.8% |  |
| LOAD_FAST | 138,007,080 | 5.8% | 69.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 96,002,100 | 4.0% | 73.6% |  |
| POP_TOP | 72,001,560 | 3.0% | 76.6% |  |
| LOAD_CONST | 60,004,200 | 2.5% | 79.1% |  |
| POP_JUMP_IF_FALSE | 60,002,520 | 2.5% | 81.6% |  |
| STORE_FAST | 42,002,340 | 1.8% | 83.4% |  |
| RETURN_CONST | 36,001,920 | 1.5% | 84.9% |  |
| LOAD_FAST_LOAD_FAST | 30,003,000 | 1.3% | 86.2% |  |
| TO_BOOL_NONE | 24,207,680 | 1.0% | 87.2% | 45.2% |
| TO_BOOL_ALWAYS_TRUE | 24,206,720 | 1.0% | 88.2% | 45.2% |
| INTERPRETER_EXIT | 24,001,260 | 1.0% | 89.2% |  |
| RETURN_GENERATOR | 24,000,600 | 1.0% | 90.2% |  |
| GET_YIELD_FROM_ITER | 24,000,300 | 1.0% | 91.2% |  |
| END_SEND | 24,000,300 | 1.0% | 92.2% |  |
| JUMP_BACKWARD | 24,000,240 | 1.0% | 93.2% |  |
| FOR_ITER_GEN | 24,000,240 | 1.0% | 94.2% |  |
| LOAD_GLOBAL_MODULE | 18,002,080 | 0.8% | 95.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 18,001,800 | 0.8% | 95.7% |  |
| LOAD_GLOBAL_BUILTIN | 12,001,680 | 0.5% | 96.2% |  |
| RETURN_VALUE | 12,001,320 | 0.5% | 96.7% |  |
| COMPARE_OP_INT | 12,001,320 | 0.5% | 97.2% |  |
| CALL_PY_EXACT_ARGS | 12,001,320 | 0.5% | 97.7% |  |
| CALL_LEN | 12,001,320 | 0.5% | 98.2% |  |
| BINARY_SLICE | 12,001,200 | 0.5% | 98.7% |  |
| BINARY_OP | 6,002,080 | 0.3% | 99.0% |  |
| BINARY_SUBSCR | 6,002,060 | 0.3% | 99.2% |  |
| EXIT_INIT_CHECK | 6,000,600 | 0.3% | 99.5% |  |
| CALL_ALLOC_AND_ENTER_INIT | 6,000,600 | 0.3% | 99.7% |  |
| BINARY_OP_ADD_INT | 6,000,600 | 0.3% | 100.0% |  |
| CALL | 400 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 360 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| GET_ITER | 300 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 240 | 0.0% | 100.0% |  |
| END_FOR | 240 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| COMPARE_OP | 80 | 0.0% | 100.0% |  |
| POP_JUMP_IF_TRUE | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| YIELD_VALUE YIELD_VALUE | 352,548,180 | 14.8% | 14.8% |
| SEND_GEN RESUME_CHECK | 352,548,180 | 14.8% | 29.5% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 352,548,180 | 14.8% | 44.3% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 352,548,180 | 14.8% | 59.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 96,002,100 | 4.0% | 63.1% |
| POP_TOP LOAD_FAST | 39,729,360 | 1.7% | 64.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 38,272,740 | 1.6% | 66.3% |
| LOAD_FAST LOAD_CONST | 24,002,520 | 1.0% | 67.3% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 24,001,080 | 1.0% | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 24,001,080 | 1.0% | 69.3% |
| RETURN_GENERATOR INTERPRETER_EXIT | 24,000,600 | 1.0% | 70.3% |
| RESUME_CHECK POP_TOP | 24,000,600 | 1.0% | 71.3% |
| RESUME_CHECK LOAD_FAST | 24,000,600 | 1.0% | 72.4% |
| POP_TOP RESUME_CHECK | 24,000,600 | 1.0% | 73.4% |
| LOAD_ATTR_INSTANCE_VALUE YIELD_VALUE | 24,000,600 | 1.0% | 74.4% |
| CACHE RETURN_GENERATOR | 24,000,600 | 1.0% | 75.4% |
| SEND_GEN POP_TOP | 24,000,300 | 1.0% | 76.4% |
| RETURN_CONST END_SEND | 24,000,300 | 1.0% | 77.4% |
| LOAD_CONST SEND_GEN | 24,000,300 | 1.0% | 78.4% |
| LOAD_ATTR_INSTANCE_VALUE GET_YIELD_FROM_ITER | 24,000,300 | 1.0% | 79.4% |
| GET_YIELD_FROM_ITER LOAD_CONST | 24,000,300 | 1.0% | 80.4% |
| END_SEND POP_TOP | 24,000,300 | 1.0% | 81.4% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 24,000,120 | 1.0% | 82.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_ALWAYS_TRUE | 24,000,120 | 1.0% | 83.4% |
| YIELD_VALUE STORE_FAST | 24,000,000 | 1.0% | 84.4% |
| STORE_FAST JUMP_BACKWARD | 24,000,000 | 1.0% | 85.4% |
| JUMP_BACKWARD FOR_ITER_GEN | 24,000,000 | 1.0% | 86.4% |
| FOR_ITER_GEN RESUME_CHECK | 24,000,000 | 1.0% | 87.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 21,729,780 | 0.9% | 88.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 18,001,800 | 0.8% | 89.1% |
| STORE_FAST LOAD_FAST | 12,001,620 | 0.5% | 89.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 12,001,380 | 0.5% | 90.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 12,001,360 | 0.5% | 90.6% |
| LOAD_FAST CALL_LEN | 12,001,320 | 0.5% | 91.1% |
| LOAD_CONST COMPARE_OP_INT | 12,001,320 | 0.5% | 91.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 12,001,320 | 0.5% | 92.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 12,001,320 | 0.5% | 92.6% |
| CALL_LEN STORE_FAST | 12,001,320 | 0.5% | 93.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 12,001,200 | 0.5% | 93.6% |
| BINARY_SLICE CALL_PY_EXACT_ARGS | 12,001,200 | 0.5% | 94.1% |
| POP_TOP RETURN_CONST | 8,271,540 | 0.3% | 94.5% |
| STORE_FAST LOAD_GLOBAL_MODULE | 6,000,680 | 0.3% | 94.7% |
| RETURN_VALUE RETURN_VALUE | 6,000,660 | 0.3% | 95.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 6,000,600 | 0.3% | 95.2% |
| RETURN_CONST EXIT_INIT_CHECK | 6,000,600 | 0.3% | 95.5% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 6,000,600 | 0.3% | 95.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 6,000,600 | 0.3% | 96.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 6,000,600 | 0.3% | 96.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 6,000,600 | 0.3% | 96.5% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 6,000,600 | 0.3% | 96.7% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 6,000,600 | 0.3% | 97.0% |
| LOAD_FAST BINARY_SLICE | 6,000,600 | 0.3% | 97.2% |
| LOAD_CONST LOAD_FAST | 6,000,600 | 0.3% | 97.5% |
| LOAD_CONST BINARY_SLICE | 6,000,600 | 0.3% | 97.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 6,000,600 | 0.3% | 98.0% |
| LOAD_CONST BINARY_OP | 6,000,600 | 0.3% | 98.2% |
| EXIT_INIT_CHECK RETURN_VALUE | 6,000,600 | 0.3% | 98.5% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 6,000,600 | 0.3% | 98.7% |
| BINARY_SUBSCR LOAD_GLOBAL_MODULE | 6,000,600 | 0.3% | 99.0% |
| BINARY_OP_ADD_INT LOAD_CONST | 6,000,600 | 0.3% | 99.2% |
| BINARY_OP STORE_FAST | 6,000,600 | 0.3% | 99.5% |
| RETURN_CONST CALL_ALLOC_AND_ENTER_INIT | 3,932,580 | 0.2% | 99.6% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 3,932,460 | 0.2% | 99.8% |
| RETURN_CONST LOAD_FAST_LOAD_FAST | 2,068,140 | 0.1% | 99.9% |
| RETURN_VALUE CALL_ALLOC_AND_ENTER_INIT | 2,068,020 | 0.1% | 100.0% |
| TO_BOOL_NONE TO_BOOL_ALWAYS_TRUE | 206,600 | 0.0% | 100.0% |
| TO_BOOL_ALWAYS_TRUE TO_BOOL_NONE | 206,600 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 1,460 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 1,460 | 0.0% | 100.0% |
| YIELD_VALUE INTERPRETER_EXIT | 600 | 0.0% | 100.0% |
| CACHE RESUME_CHECK | 600 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 300 | 0.0% | 100.0% |
| RETURN_CONST END_FOR | 240 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 240 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_GEN | 240 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 240 | 0.0% | 100.0% |
| FOR_ITER_GEN POP_TOP | 240 | 0.0% | 100.0% |
| END_FOR JUMP_BACKWARD | 240 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 180 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_CONST CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 60 | 0.0% | 100.0% |
| RETURN_CONST INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_CONST CALL | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,600 | 50.0% |
| LOAD_CONST | 6,000,600 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,001,200 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 24,000,600 | 100.0% |
| RESUME_CHECK | 600 | 0.0% |
| POP_TOP | 60 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000,600 | 100.0% |
| BINARY_SUBSCR | 1,460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,000,600 | 100.0% |
| BINARY_SUBSCR | 1,460 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 24,000,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 24,000,300 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,000,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,000,600 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 240 | 80.0% |
| FOR_ITER_RANGE | 60 | 20.0% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 24,000,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,000,300 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 24,000,600 | 100.0% |
| YIELD_VALUE | 600 | 0.0% |
| RETURN_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


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
| RESUME_CHECK | 24,000,600 | 33.3% |
| SEND_GEN | 24,000,300 | 33.3% |
| END_SEND | 24,000,300 | 33.3% |
| FOR_ITER_GEN | 240 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,729,360 | 55.2% |
| RESUME_CHECK | 24,000,600 | 33.3% |
| RETURN_CONST | 8,271,540 | 11.5% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 160 | 53.3% |
| LOAD_DEREF | 120 | 40.0% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 180 | 60.0% |
| LOAD_FAST | 120 | 40.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 24,000,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 24,000,600 | 100.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,000,660 | 50.0% |
| EXIT_INIT_CHECK | 6,000,600 | 50.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,000,660 | 50.0% |
| LOAD_FAST_LOAD_FAST | 3,932,460 | 32.8% |
| CALL_ALLOC_AND_ENTER_INIT | 2,068,020 | 17.2% |
| STORE_FAST | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,600 | 100.0% |
| BINARY_OP | 1,460 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,600 | 100.0% |
| BINARY_OP | 1,460 | 0.0% |
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
| PUSH_NULL | 180 | 45.0% |
| LOAD_CONST | 60 | 15.0% |
| CALL_BUILTIN_CLASS | 60 | 15.0% |
| CALL | 60 | 15.0% |
| RETURN_VALUE | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 120 | 30.0% |
| STORE_FAST | 60 | 15.0% |
| POP_TOP | 60 | 15.0% |
| LOAD_FAST | 60 | 15.0% |
| CALL | 60 | 15.0% |


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

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 60 | 75.0% |
| COMPARE_OP | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 60 | 75.0% |
| COMPARE_OP | 20 | 25.0% |


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
| STORE_FAST | 24,000,000 | 100.0% |
| END_FOR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 24,000,000 | 100.0% |
| FOR_ITER_RANGE | 240 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 352,548,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 352,548,180 | 100.0% |


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
| LOAD_FAST | 24,002,520 | 40.0% |
| GET_YIELD_FROM_ITER | 24,000,300 | 40.0% |
| LOAD_FAST_LOAD_FAST | 6,000,600 | 10.0% |
| BINARY_OP_ADD_INT | 6,000,600 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 24,000,300 | 40.0% |
| COMPARE_OP_INT | 12,001,320 | 20.0% |
| LOAD_FAST | 6,000,600 | 10.0% |
| BINARY_SLICE | 6,000,600 | 10.0% |
| BINARY_OP_ADD_INT | 6,000,600 | 10.0% |


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
| POP_TOP | 39,729,360 | 28.8% |
| POP_JUMP_IF_FALSE | 38,272,740 | 27.7% |
| RESUME_CHECK | 24,000,600 | 17.4% |
| STORE_FAST | 12,001,620 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 12,001,380 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 96,002,100 | 69.6% |
| LOAD_CONST | 24,002,520 | 17.4% |
| CALL_LEN | 12,001,320 | 8.7% |
| BINARY_SLICE | 6,000,600 | 4.3% |
| GET_ITER | 300 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,001,200 | 40.0% |
| RESUME_CHECK | 6,000,600 | 20.0% |
| LOAD_GLOBAL_MODULE | 6,000,600 | 20.0% |
| RETURN_VALUE | 3,932,460 | 13.1% |
| RETURN_CONST | 2,068,140 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 18,001,800 | 60.0% |
| LOAD_CONST | 6,000,600 | 20.0% |
| BINARY_SUBSCR | 6,000,600 | 20.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 16.7% |
| RETURN_VALUE | 40 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 16.7% |
| RESUME_CHECK | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 50.0% |
| LOAD_GLOBAL_MODULE | 100 | 41.7% |
| LOAD_ATTR | 20 | 8.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 24,001,080 | 40.0% |
| TO_BOOL_ALWAYS_TRUE | 24,000,120 | 40.0% |
| COMPARE_OP_INT | 12,001,320 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,272,740 | 63.8% |
| RETURN_CONST | 21,729,780 | 36.2% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,729,780 | 60.4% |
| POP_TOP | 8,271,540 | 23.0% |
| STORE_ATTR_INSTANCE_VALUE | 6,000,600 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 24,000,300 | 66.7% |
| EXIT_INIT_CHECK | 6,000,600 | 16.7% |
| CALL_ALLOC_AND_ENTER_INIT | 3,932,580 | 10.9% |
| LOAD_FAST_LOAD_FAST | 2,068,140 | 5.7% |
| END_FOR | 240 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 24,000,000 | 57.1% |
| CALL_LEN | 12,001,320 | 28.6% |
| BINARY_OP | 6,000,600 | 14.3% |
| FOR_ITER_RANGE | 240 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 24,000,000 | 57.1% |
| LOAD_FAST | 12,001,620 | 28.6% |
| LOAD_GLOBAL_MODULE | 6,000,680 | 14.3% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 352,548,180 | 93.6% |
| LOAD_ATTR_INSTANCE_VALUE | 24,000,600 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 352,548,180 | 93.6% |
| STORE_FAST | 24,000,000 | 6.4% |
| INTERPRETER_EXIT | 600 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,600 | 100.0% |


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

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,932,580 | 65.5% |
| RETURN_VALUE | 2,068,020 | 34.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,000,600 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 33.3% |
| CALL | 120 | 33.3% |
| RETURN_VALUE | 40 | 11.1% |
| LOAD_FAST | 40 | 11.1% |
| CALL_BUILTIN_CLASS | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 80 | 22.2% |
| STORE_FAST | 60 | 16.7% |
| COMPARE_OP | 60 | 16.7% |
| CALL | 60 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 11.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,001,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,001,320 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 12,001,200 | 100.0% |
| CALL_BUILTIN_CLASS | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,001,320 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,001,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,001,320 | 100.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 24,000,000 | 100.0% |
| GET_ITER | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 24,000,000 | 100.0% |
| POP_TOP | 240 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 80.0% |
| GET_ITER | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 80.0% |
| LOAD_GLOBAL_MODULE | 40 | 13.3% |
| LOAD_GLOBAL | 20 | 6.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,002,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 24,001,080 | 25.0% |
| YIELD_VALUE | 24,000,600 | 25.0% |
| GET_YIELD_FROM_ITER | 24,000,300 | 25.0% |
| TO_BOOL_ALWAYS_TRUE | 24,000,120 | 25.0% |


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
| RESUME_CHECK | 12,001,360 | 100.0% |
| LOAD_GLOBAL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| POP_JUMP_IF_TRUE | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,001,380 | 100.0% |
| LOAD_CONST | 180 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,680 | 33.3% |
| LOAD_GLOBAL_MODULE | 6,000,600 | 33.3% |
| BINARY_SUBSCR | 6,000,600 | 33.3% |
| LOAD_GLOBAL | 100 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,000,600 | 33.3% |
| LOAD_FAST_LOAD_FAST | 6,000,600 | 33.3% |
| LOAD_FAST | 6,000,600 | 33.3% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 352,548,180 | 84.2% |
| POP_TOP | 24,000,600 | 5.7% |
| FOR_ITER_GEN | 24,000,000 | 5.7% |
| CALL_PY_EXACT_ARGS | 12,001,320 | 2.9% |
| CALL_ALLOC_AND_ENTER_INIT | 6,000,600 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 352,548,180 | 84.2% |
| POP_TOP | 24,000,600 | 5.7% |
| LOAD_FAST | 24,000,600 | 5.7% |
| LOAD_GLOBAL_BUILTIN | 12,001,360 | 2.9% |
| LOAD_FAST_LOAD_FAST | 6,000,600 | 1.4% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 352,548,180 | 93.6% |
| LOAD_CONST | 24,000,300 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 352,548,180 | 93.6% |
| POP_TOP | 24,000,300 | 6.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,001,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,001,200 | 66.7% |
| RETURN_CONST | 6,000,600 | 33.3% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 24,000,120 | 99.1% |
| TO_BOOL_NONE | 206,600 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 24,000,120 | 99.1% |
| TO_BOOL_NONE | 206,600 | 0.9% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 24,001,080 | 99.1% |
| TO_BOOL_ALWAYS_TRUE | 206,600 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 24,001,080 | 99.1% |
| TO_BOOL_ALWAYS_TRUE | 206,600 | 0.9% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6000600 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 1,460 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence int | 1,460 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |       413200 | 0.9% |
|          hit |     26514620 | 54.8% |
|         miss |     21899780 | 45.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 413,200 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6000600 | 50.0% |
|          hit |      6000660 | 50.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.4% |
| Failure | 1,460 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 1,460 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          180 | 0.0% |
|          hit |     30003600 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 72.7% |
| Failure | 60 | 27.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 0.0% |
|          hit |     12001320 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     24000540 | 100.0% |


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
| specialization.deferred |           20 | 0.0% |
|          hit |     96002260 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
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
|          hit |     30003760 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 100.0% |
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

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    376548480 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     18001800 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,221,122,880 | 51.1% |
| Not specialized | 129,917,260 | 5.4% |
| Specialized | 1,037,619,940 | 43.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,023,800 | 100.0% |
| BINARY_SUBSCR | 6,000,600 | 0.0% |
| BINARY_OP | 6,000,600 | 0.0% |
| CALL | 180 | 0.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_NONE | 10,949,980 | 50.0% |
| TO_BOOL_ALWAYS_TRUE | 10,949,800 | 50.0% |
| RESUME_CHECK | 8,520 | 0.0% |
| RESUME | 8,520 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |
| SEND_GEN | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RETURN_GENERATOR | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 24,001,260 | 5.4% |
| Calls to Python functions inlined | 418,550,760 | 94.6% |
| Calls via PyEval_EvalFrame (total) | 24,001,260 | 5.4% |
| Calls via PyEval_EvalFrame (vector) | 24,000,600 | 5.4% |
| Calls via PyEval_EvalFrame (generator) | 660 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 24,000,600 | 5.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 24,000,600 | 5.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 48,003,240 | 10.8% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 0 | 0.0% |
| Frees to freelist | 300 |  |
| Allocations | 78,035,460 | 100.0% |
| Allocations to 512 bytes | 78,035,460 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 78,035,400 |  |
| New values | 0 |  |
| Interpreter increfs | 384,048,220 | 92.7% |
| Interpreter decrefs | 432,082,560 | 86.7% |
| Increfs | 30,154,480 | 7.3% |
| Decrefs | 66,155,960 | 13.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 19 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
| Method cache dunder hits | 24,002,120 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 7,760 | 0 | 43,469,680 |
| 1 | 700 | 0 | 45,418,680 |
| 2 | 60 | 0 | 36,797,840 |


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
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
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
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


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
Stats gathered on: 2023-10-15
