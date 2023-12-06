
# Pystats results

- benchmark: unpickle
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,058,680 | 37.2% | 37.2% |  |
| POP_TOP | 579,520 | 20.4% | 57.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 579,220 | 20.4% | 77.9% |  |
| PUSH_NULL | 539,320 | 18.9% | 96.9% |  |
| ENTER_EXECUTOR | 81,320 | 2.9% | 99.7% |  |
| STORE_FAST | 1,520 | 0.1% | 99.8% |  |
| CALL | 1,260 | 0.0% | 99.8% |  |
| FOR_ITER_TUPLE | 660 | 0.0% | 99.8% |  |
| JUMP_BACKWARD | 640 | 0.0% | 99.9% |  |
| GET_ITER | 460 | 0.0% | 99.9% |  |
| LOAD_ATTR_MODULE | 420 | 0.0% | 99.9% |  |
| LOAD_ATTR | 400 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 360 | 0.0% | 99.9% |  |
| LOAD_GLOBAL_MODULE | 360 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 280 | 0.0% | 99.9% |  |
| LOAD_DEREF | 240 | 0.0% | 99.9% |  |
| LOAD_ATTR_WITH_HINT | 180 | 0.0% | 100.0% |  |
| RETURN_VALUE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| BUILD_LIST | 80 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| FOR_ITER | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 40 | 0.0% | 100.0% |  |
| RESUME | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 579,040 | 20.3% | 20.3% |
| PUSH_NULL LOAD_FAST | 538,840 | 18.9% | 39.3% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 537,880 | 18.9% | 58.2% |
| LOAD_FAST PUSH_NULL | 518,580 | 18.2% | 76.4% |
| POP_TOP LOAD_FAST | 518,000 | 18.2% | 94.6% |
| POP_TOP ENTER_EXECUTOR | 61,120 | 2.1% | 96.7% |
| ENTER_EXECUTOR CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,760 | 1.4% | 98.2% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 20,160 | 0.7% | 98.9% |
| ENTER_EXECUTOR PUSH_NULL | 20,100 | 0.7% | 99.6% |
| STORE_FAST LOAD_FAST | 1,280 | 0.0% | 99.6% |
| LOAD_FAST CALL | 840 | 0.0% | 99.7% |
| FOR_ITER_TUPLE STORE_FAST | 560 | 0.0% | 99.7% |
| CALL POP_TOP | 480 | 0.0% | 99.7% |
| CALL CALL_BUILTIN_FAST_WITH_KEYWORDS | 460 | 0.0% | 99.7% |
| LOAD_FAST GET_ITER | 460 | 0.0% | 99.7% |
| GET_ITER FOR_ITER_TUPLE | 360 | 0.0% | 99.7% |
| FOR_ITER_RANGE STORE_FAST | 360 | 0.0% | 99.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 360 | 0.0% | 99.8% |
| POP_TOP JUMP_BACKWARD | 320 | 0.0% | 99.8% |
| JUMP_BACKWARD FOR_ITER_RANGE | 280 | 0.0% | 99.8% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 280 | 0.0% | 99.8% |
| LOAD_FAST LOAD_ATTR | 280 | 0.0% | 99.8% |
| PUSH_NULL CALL | 240 | 0.0% | 99.8% |
| ENTER_EXECUTOR JUMP_BACKWARD | 220 | 0.0% | 99.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 180 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 180 | 0.0% | 99.8% |
| CALL STORE_FAST | 160 | 0.0% | 99.8% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 99.9% |
| LOAD_FAST LOAD_ATTR_MODULE | 160 | 0.0% | 99.9% |
| LOAD_ATTR LOAD_ATTR_MODULE | 140 | 0.0% | 99.9% |
| PUSH_NULL LOAD_GLOBAL | 120 | 0.0% | 99.9% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.9% |
| LOAD_ATTR PUSH_NULL | 120 | 0.0% | 99.9% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 120 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.9% |
| LOAD_ATTR_WITH_HINT CALL_BUILTIN_FAST_WITH_KEYWORDS | 120 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 120 | 0.0% | 99.9% |
| FOR_ITER_TUPLE JUMP_BACKWARD | 100 | 0.0% | 99.9% |
| NOP LOAD_DEREF | 80 | 0.0% | 99.9% |
| POP_TOP NOP | 80 | 0.0% | 99.9% |
| RETURN_VALUE RETURN_VALUE | 80 | 0.0% | 99.9% |
| BUILD_LIST LOAD_DEREF | 80 | 0.0% | 99.9% |
| BUILD_TUPLE STORE_FAST | 80 | 0.0% | 99.9% |
| CALL LOAD_FAST | 80 | 0.0% | 99.9% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 99.9% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 80 | 0.0% | 99.9% |
| LIST_EXTEND CALL_INTRINSIC_1 | 80 | 0.0% | 99.9% |
| LOAD_DEREF LIST_EXTEND | 80 | 0.0% | 99.9% |
| LOAD_FAST BUILD_LIST | 80 | 0.0% | 99.9% |
| LOAD_FAST BUILD_TUPLE | 80 | 0.0% | 99.9% |
| LOAD_FAST CALL_FUNCTION_EX | 80 | 0.0% | 99.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 80 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_FAST | 80 | 0.0% | 99.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 80 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL | 80 | 0.0% | 99.9% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 99.9% |
| CALL CALL | 60 | 0.0% | 99.9% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 99.9% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| LOAD_ATTR CALL | 60 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_WITH_HINT | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR_WITH_HINT CALL | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| FOR_ITER STORE_FAST | 40 | 0.0% | 100.0% |
| JUMP_BACKWARD ENTER_EXECUTOR | 40 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| BINARY_OP RETURN_VALUE | 20 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 20 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME | 20 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME | 20 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER_RANGE | 20 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER_TUPLE | 20 | 0.0% | 100.0% |
| LOAD_ATTR STORE_FAST | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.0% | 100.0% |
| RESUME LOAD_DEREF | 20 | 0.0% | 100.0% |
| RESUME LOAD_FAST | 20 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 360 | 78.3% |
| FOR_ITER_RANGE | 60 | 13.0% |
| FOR_ITER | 40 | 8.7% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 579,040 | 99.9% |
| CALL | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,000 | 89.4% |
| ENTER_EXECUTOR | 61,120 | 10.5% |
| JUMP_BACKWARD | 320 | 0.1% |
| NOP | 80 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 518,580 | 96.2% |
| ENTER_EXECUTOR | 20,100 | 3.7% |
| LOAD_ATTR_MODULE | 360 | 0.1% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_ATTR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 538,840 | 99.9% |
| CALL | 240 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |


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

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 50.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 50.0% |


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

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840 | 66.7% |
| PUSH_NULL | 240 | 19.0% |
| CALL | 60 | 4.8% |
| LOAD_ATTR | 60 | 4.8% |
| LOAD_ATTR_WITH_HINT | 60 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480 | 38.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 460 | 36.5% |
| STORE_FAST | 160 | 12.7% |
| LOAD_FAST | 80 | 6.3% |
| CALL | 60 | 4.8% |


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
| POP_TOP | 61,120 | 75.2% |
| ENTER_EXECUTOR | 20,160 | 24.8% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40,760 | 50.1% |
| ENTER_EXECUTOR | 20,160 | 24.8% |
| PUSH_NULL | 20,100 | 24.7% |
| JUMP_BACKWARD | 220 | 0.3% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 40 | 50.0% |
| JUMP_BACKWARD | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 50.0% |
| FOR_ITER_RANGE | 20 | 25.0% |
| FOR_ITER_TUPLE | 20 | 25.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 320 | 50.0% |
| ENTER_EXECUTOR | 220 | 34.4% |
| FOR_ITER_TUPLE | 100 | 15.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 280 | 43.8% |
| FOR_ITER_TUPLE | 280 | 43.8% |
| ENTER_EXECUTOR | 40 | 6.2% |
| FOR_ITER | 40 | 6.2% |


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
| LOAD_FAST | 280 | 70.0% |
| LOAD_GLOBAL | 60 | 15.0% |
| LOAD_GLOBAL_MODULE | 60 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 140 | 35.0% |
| PUSH_NULL | 120 | 30.0% |
| CALL | 60 | 15.0% |
| LOAD_ATTR_WITH_HINT | 60 | 15.0% |
| STORE_FAST | 20 | 5.0% |


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
| PUSH_NULL | 538,840 | 50.9% |
| POP_TOP | 518,000 | 48.9% |
| STORE_FAST | 1,280 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 537,880 | 50.8% |
| PUSH_NULL | 518,580 | 49.0% |
| CALL | 840 | 0.1% |
| GET_ITER | 460 | 0.0% |
| LOAD_ATTR | 280 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 42.9% |
| STORE_FAST | 80 | 28.6% |
| RETURN_VALUE | 40 | 14.3% |
| ENTER_EXECUTOR | 40 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 42.9% |
| LOAD_FAST | 80 | 28.6% |
| LOAD_ATTR | 60 | 21.4% |
| LOAD_GLOBAL_BUILTIN | 20 | 7.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 560 | 36.8% |
| FOR_ITER_RANGE | 360 | 23.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 180 | 11.8% |
| CALL | 160 | 10.5% |
| BUILD_TUPLE | 80 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,280 | 84.2% |
| LOAD_FAST_LOAD_FAST | 80 | 5.3% |
| LOAD_GLOBAL | 80 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 40 | 2.6% |
| LOAD_GLOBAL_MODULE | 40 | 2.6% |


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
| LOAD_FAST | 20 | 50.0% |


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

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 537,880 | 92.9% |
| ENTER_EXECUTOR | 40,760 | 7.0% |
| CALL | 460 | 0.1% |
| LOAD_ATTR_WITH_HINT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 579,040 | 100.0% |
| STORE_FAST | 180 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 280 | 77.8% |
| GET_ITER | 60 | 16.7% |
| FOR_ITER | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 100.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 360 | 54.5% |
| JUMP_BACKWARD | 280 | 42.4% |
| FOR_ITER | 20 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 560 | 84.8% |
| JUMP_BACKWARD | 100 | 15.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 38.1% |
| LOAD_ATTR | 140 | 33.3% |
| LOAD_GLOBAL_MODULE | 120 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 360 | 85.7% |
| STORE_FAST | 60 | 14.3% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| LOAD_ATTR | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 120 | 66.7% |
| CALL | 60 | 33.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 33.3% |
| LOAD_GLOBAL | 120 | 33.3% |
| RETURN_VALUE | 40 | 11.1% |
| ENTER_EXECUTOR | 40 | 11.1% |
| STORE_FAST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 50.0% |
| LOAD_ATTR_MODULE | 120 | 33.3% |
| LOAD_ATTR | 60 | 16.7% |


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
| LOAD_FAST | 60 | 50.0% |


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
|     deferred | 20 | 20.0% |
|          hit | 60 | 60.0% |

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
|     deferred | 720 | 0.1% |
|          hit | 579,280 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 480 | 88.9% |
| Failure | 60 | 11.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 3.6% |
|          hit | 1,020 | 92.7% |

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
|     deferred | 200 | 20.0% |
|          hit | 600 | 60.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 140 | 20.0% |
|          hit | 420 | 60.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,262,620 | 79.5% |
| Not specialized | 2,060 | 0.1% |
| Specialized hits | 581,500 | 20.4% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 720 | 64.3% |
| LOAD_ATTR | 200 | 17.9% |
| LOAD_GLOBAL | 140 | 12.5% |
| FOR_ITER | 40 | 3.6% |
| BINARY_OP | 20 | 1.8% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |


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
| Allocations from freelist | 7,373,600 | 7.1% |
| Frees to freelist | 7,373,540 |  |
| Allocations | 96,278,780 | 92.9% |
| Allocations to 512 bytes | 94,639,700 | 91.3% |
| Allocations to 4 kbytes | 1,638,760 | 1.6% |
| Allocations over 4 kbytes | 320 | 0.0% |
| Frees | 99,961,955 |  |
| New values | 0 |  |
| Interpreter increfs | 2,623,560 | 1.1% |
| Interpreter decrefs | 3,893,980 | 1.2% |
| Increfs | 226,552,356 | 98.9% |
| Decrefs | 315,822,800 | 98.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 819,676 |  |
| Method cache misses | 409,784 |  |
| Method cache collisions | 409,307 |  |
| Method cache dunder hits | 819,826 |  |
| Method cache dunder misses | 94 |  |


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
| Traces executed | 81,320 |  |
| Uops executed | 4,849,540 | 59.64 |

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
| <= 8 | 20,460 | 25.2% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 60,860 | 74.8% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,420,440 | 29.3% | 29.3% |  |
| _SET_IP | 852,200 | 17.6% | 46.9% |  |
| PUSH_NULL | 690,120 | 14.2% | 61.1% |  |
| POP_TOP | 669,820 | 13.8% | 74.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 649,360 | 13.4% | 88.3% |  |
| _POP_JUMP_IF_TRUE | 101,420 | 2.1% | 90.4% |  |
| _EXIT_TRACE | 81,320 | 1.7% | 92.1% |  |
| _ITER_CHECK_TUPLE | 81,240 | 1.7% | 93.7% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 81,240 | 1.7% | 95.4% |  |
| STORE_FAST | 80,960 | 1.7% | 97.1% |  |
| _ITER_NEXT_TUPLE | 60,860 | 1.3% | 98.3% |  |
| _ITER_CHECK_RANGE | 20,180 | 0.4% | 98.8% |  |
| _IS_ITER_EXHAUSTED_RANGE | 20,180 | 0.4% | 99.2% |  |
| GET_ITER | 20,100 | 0.4% | 99.6% |  |
| _ITER_NEXT_RANGE | 20,100 | 0.4% | 100.0% |  |


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
