
# Pystats results

- benchmark: pickle_dict
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 660 | 13.3% | 13.3% |  |
| PUSH_NULL | 600 | 12.1% | 25.4% |  |
| LOAD_ATTR_MODULE | 460 | 9.3% | 34.7% |  |
| POP_TOP | 360 | 7.3% | 41.9% |  |
| LOAD_FAST_LOAD_FAST | 300 | 6.0% | 48.0% |  |
| STORE_FAST | 300 | 6.0% | 54.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 6.0% | 60.1% |  |
| CALL | 260 | 5.2% | 65.3% |  |
| LOAD_GLOBAL_MODULE | 220 | 4.4% | 69.8% |  |
| LOAD_DEREF | 180 | 3.6% | 73.4% |  |
| RETURN_VALUE | 120 | 2.4% | 75.8% |  |
| CALL_FUNCTION_EX | 120 | 2.4% | 78.2% |  |
| LOAD_GLOBAL | 120 | 2.4% | 80.6% |  |
| RESUME_CHECK | 120 | 2.4% | 83.1% |  |
| LOAD_ATTR | 100 | 2.0% | 85.1% |  |
| GET_ITER | 60 | 1.2% | 86.3% |  |
| NOP | 60 | 1.2% | 87.5% |  |
| BUILD_LIST | 60 | 1.2% | 88.7% |  |
| CALL_INTRINSIC_1 | 60 | 1.2% | 89.9% |  |
| COPY_FREE_VARS | 60 | 1.2% | 91.1% |  |
| ENTER_EXECUTOR | 60 | 1.2% | 92.3% |  |
| LIST_EXTEND | 60 | 1.2% | 93.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 1.2% | 94.8% |  |
| CALL_BUILTIN_CLASS | 60 | 1.2% | 96.0% |  |
| FOR_ITER_RANGE | 60 | 1.2% | 97.2% |  |
| LOAD_ATTR_WITH_HINT | 60 | 1.2% | 98.4% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 1.2% | 99.6% |  |
| BINARY_OP | 20 | 0.4% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_ATTR_MODULE PUSH_NULL | 460 | 9.3% | 9.3% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 300 | 6.0% | 15.3% |
| LOAD_FAST LOAD_ATTR_MODULE | 300 | 6.0% | 21.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 6.0% | 27.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 300 | 6.0% | 33.5% |
| POP_TOP LOAD_FAST | 240 | 4.8% | 38.3% |
| PUSH_NULL CALL | 180 | 3.6% | 41.9% |
| STORE_FAST LOAD_FAST | 180 | 3.6% | 45.6% |
| PUSH_NULL LOAD_FAST | 120 | 2.4% | 48.0% |
| LOAD_DEREF PUSH_NULL | 120 | 2.4% | 50.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 2.0% | 52.4% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 1.6% | 54.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 1.6% | 55.6% |
| GET_ITER FOR_ITER_RANGE | 60 | 1.2% | 56.9% |
| NOP LOAD_DEREF | 60 | 1.2% | 58.1% |
| POP_TOP NOP | 60 | 1.2% | 59.3% |
| POP_TOP ENTER_EXECUTOR | 60 | 1.2% | 60.5% |
| RETURN_VALUE RETURN_VALUE | 60 | 1.2% | 61.7% |
| BUILD_LIST LOAD_DEREF | 60 | 1.2% | 62.9% |
| CALL POP_TOP | 60 | 1.2% | 64.1% |
| CALL CALL | 60 | 1.2% | 65.3% |
| CALL LOAD_FAST | 60 | 1.2% | 66.5% |
| CALL STORE_FAST | 60 | 1.2% | 67.7% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 1.2% | 69.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 1.2% | 70.2% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 1.2% | 71.4% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 1.2% | 72.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 1.2% | 73.8% |
| LOAD_ATTR LOAD_ATTR_MODULE | 60 | 1.2% | 75.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 1.2% | 76.2% |
| LOAD_FAST GET_ITER | 60 | 1.2% | 77.4% |
| LOAD_FAST BUILD_LIST | 60 | 1.2% | 78.6% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 1.2% | 79.8% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 1.2% | 81.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 1.2% | 82.3% |
| FOR_ITER_RANGE STORE_FAST | 60 | 1.2% | 83.5% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 60 | 1.2% | 84.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 1.2% | 85.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 1.2% | 87.1% |
| LOAD_GLOBAL_MODULE STORE_FAST | 60 | 1.2% | 88.3% |
| RESUME_CHECK LOAD_DEREF | 60 | 1.2% | 89.5% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.8% | 90.3% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.8% | 91.1% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.8% | 91.9% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.8% | 92.7% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 40 | 0.8% | 93.5% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.8% | 94.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 40 | 0.8% | 95.2% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.4% | 95.6% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.4% | 96.0% |
| CALL CALL_BUILTIN_CLASS | 20 | 0.4% | 96.4% |
| ENTER_EXECUTOR LOAD_GLOBAL | 20 | 0.4% | 96.8% |
| LOAD_ATTR PUSH_NULL | 20 | 0.4% | 97.2% |
| LOAD_ATTR LOAD_ATTR_WITH_HINT | 20 | 0.4% | 97.6% |
| LOAD_FAST BINARY_OP | 20 | 0.4% | 98.0% |
| LOAD_FAST CALL | 20 | 0.4% | 98.4% |
| LOAD_FAST LOAD_ATTR | 20 | 0.4% | 98.8% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.4% | 99.2% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.4% | 99.6% |
| RESUME_CHECK LOAD_GLOBAL | 20 | 0.4% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 60 | 100.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 83.3% |
| CALL | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 66.7% |
| NOP | 60 | 16.7% |
| ENTER_EXECUTOR | 60 | 16.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 460 | 76.7% |
| LOAD_DEREF | 120 | 20.0% |
| LOAD_ATTR | 20 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 300 | 50.0% |
| CALL | 180 | 30.0% |
| LOAD_FAST | 120 | 20.0% |


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
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 20 | 100.0% |


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
| PUSH_NULL | 180 | 69.2% |
| CALL | 60 | 23.1% |
| LOAD_FAST | 20 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 23.1% |
| CALL | 60 | 23.1% |
| LOAD_FAST | 60 | 23.1% |
| STORE_FAST | 60 | 23.1% |
| CALL_BUILTIN_CLASS | 20 | 7.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


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
| POP_TOP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


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
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_FAST | 20 | 20.0% |
| LOAD_GLOBAL | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 60.0% |
| PUSH_NULL | 20 | 20.0% |
| LOAD_ATTR_WITH_HINT | 20 | 20.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |
| RESUME_CHECK | 60 | 33.3% |

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
| POP_TOP | 240 | 36.4% |
| STORE_FAST | 180 | 27.3% |
| PUSH_NULL | 120 | 18.2% |
| CALL | 60 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 300 | 45.5% |
| GET_ITER | 60 | 9.1% |
| BUILD_LIST | 60 | 9.1% |
| CALL_FUNCTION_EX | 60 | 9.1% |
| BINARY_OP_SUBTRACT_FLOAT | 40 | 6.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 33.3% |
| STORE_FAST | 40 | 33.3% |
| ENTER_EXECUTOR | 20 | 16.7% |
| RESUME_CHECK | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| LOAD_ATTR | 20 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 20 | 16.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 20.0% |
| CALL_BUILTIN_CLASS | 60 | 20.0% |
| FOR_ITER_RANGE | 60 | 20.0% |
| LOAD_ATTR_WITH_HINT | 60 | 20.0% |
| LOAD_GLOBAL_MODULE | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| LOAD_GLOBAL_MODULE | 80 | 26.7% |
| LOAD_GLOBAL | 40 | 13.3% |


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
| LOAD_FAST_LOAD_FAST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 300 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 65.2% |
| LOAD_GLOBAL_MODULE | 100 | 21.7% |
| LOAD_ATTR | 60 | 13.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 460 | 100.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40 | 66.7% |
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
| LOAD_GLOBAL | 80 | 36.4% |
| STORE_FAST | 80 | 36.4% |
| ENTER_EXECUTOR | 40 | 18.2% |
| RETURN_VALUE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 45.5% |
| LOAD_ATTR | 60 | 27.3% |
| STORE_FAST | 60 | 27.3% |


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
| LOAD_GLOBAL_BUILTIN | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


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
|          hit | 60 | 75.0% |

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
|     deferred | 180 | 29.0% |
|          hit | 360 | 58.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 25.0% |
| Failure | 60 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 3.2% |
|          hit | 520 | 83.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 5.0% |
|          hit | 280 | 70.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 3,060 | 61.7% |
| Not specialized | 500 | 10.1% |
| Specialized | 1,400 | 28.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 180 | 81.8% |
| LOAD_ATTR | 20 | 9.1% |
| LOAD_GLOBAL | 20 | 9.1% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |


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
| Frame objects created | 0 | 0.0% |
| Frames pushed | 120 | 100.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 220 | 0.0% |
| Frees to freelist | 180 |  |
| Allocations | 1,090,760 | 100.0% |
| Allocations to 512 bytes | 476,360 | 43.7% |
| Allocations to 4 kbytes | 307,200 | 28.2% |
| Allocations over 4 kbytes | 307,200 | 28.2% |
| Frees | 1,090,740 |  |
| New values | 0 |  |
| Interpreter increfs | 2,440 | 0.0% |
| Interpreter decrefs | 2,940 | 0.0% |
| Increfs | 31,487,560 | 100.0% |
| Decrefs | 31,809,920 | 100.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 153,640 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
| Method cache dunder hits | 0 |  |
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
| Traces executed | 60 |  |
| Uops executed | 1,778,700 | 29,645.00 |
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
| <= 128 | 0 | 0.0% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 60 | 100.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 459,900 | 25.9% | 25.9% |  |
| _SET_IP | 368,040 | 20.7% | 46.5% |  |
| POP_TOP | 153,360 | 8.6% | 55.2% |  |
| PUSH_NULL | 153,300 | 8.6% | 63.8% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 153,300 | 8.6% | 72.4% |  |
| _CHECK_ATTR_MODULE | 153,300 | 8.6% | 81.0% |  |
| _LOAD_ATTR_MODULE | 153,300 | 8.6% | 89.6% |  |
| _ITER_CHECK_RANGE | 30,720 | 1.7% | 91.4% |  |
| _IS_ITER_EXHAUSTED_RANGE | 30,720 | 1.7% | 93.1% |  |
| _POP_JUMP_IF_TRUE | 30,720 | 1.7% | 94.8% |  |
| STORE_FAST | 30,660 | 1.7% | 96.5% |  |
| _ITER_NEXT_RANGE | 30,660 | 1.7% | 98.3% |  |
| _JUMP_TO_TOP | 30,660 | 1.7% | 100.0% |  |
| _EXIT_TRACE | 60 | 0.0% | 100.0% |  |


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