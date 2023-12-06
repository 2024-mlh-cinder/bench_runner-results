
# Pystats results

- benchmark: pickle_list
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,020 | 16.0% | 16.0% |  |
| PUSH_NULL | 900 | 14.2% | 30.2% |  |
| POP_TOP | 660 | 10.4% | 40.6% |  |
| LOAD_FAST_LOAD_FAST | 600 | 9.4% | 50.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 9.4% | 59.4% |  |
| STORE_FAST | 360 | 5.7% | 65.1% |  |
| CALL | 260 | 4.1% | 69.2% |  |
| LOAD_ATTR_MODULE | 220 | 3.5% | 72.6% |  |
| LOAD_GLOBAL_MODULE | 220 | 3.5% | 76.1% |  |
| LOAD_DEREF | 180 | 2.8% | 78.9% |  |
| RETURN_VALUE | 120 | 1.9% | 80.8% |  |
| CALL_FUNCTION_EX | 120 | 1.9% | 82.7% |  |
| LOAD_ATTR | 120 | 1.9% | 84.6% |  |
| LOAD_GLOBAL | 120 | 1.9% | 86.5% |  |
| RESUME_CHECK | 120 | 1.9% | 88.4% |  |
| GET_ITER | 60 | 0.9% | 89.3% |  |
| NOP | 60 | 0.9% | 90.3% |  |
| BUILD_LIST | 60 | 0.9% | 91.2% |  |
| CALL_INTRINSIC_1 | 60 | 0.9% | 92.1% |  |
| COPY_FREE_VARS | 60 | 0.9% | 93.1% |  |
| ENTER_EXECUTOR | 60 | 0.9% | 94.0% |  |
| LIST_EXTEND | 60 | 0.9% | 95.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.9% | 95.9% |  |
| CALL_BUILTIN_CLASS | 60 | 0.9% | 96.9% |  |
| FOR_ITER_RANGE | 60 | 0.9% | 97.8% |  |
| LOAD_ATTR_WITH_HINT | 60 | 0.9% | 98.7% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.9% | 99.7% |  |
| BINARY_OP | 20 | 0.3% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| PUSH_NULL LOAD_FAST_LOAD_FAST | 600 | 9.4% | 9.4% |
| LOAD_FAST PUSH_NULL | 600 | 9.4% | 18.9% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 9.4% | 28.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 600 | 9.4% | 37.7% |
| POP_TOP LOAD_FAST | 540 | 8.5% | 46.2% |
| STORE_FAST LOAD_FAST | 240 | 3.8% | 50.0% |
| PUSH_NULL CALL | 180 | 2.8% | 52.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 2.5% | 55.3% |
| PUSH_NULL LOAD_FAST | 120 | 1.9% | 57.2% |
| LOAD_DEREF PUSH_NULL | 120 | 1.9% | 59.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 1.6% | 60.7% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 1.3% | 61.9% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 1.3% | 63.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 1.3% | 64.5% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.9% | 65.4% |
| NOP LOAD_DEREF | 60 | 0.9% | 66.4% |
| POP_TOP NOP | 60 | 0.9% | 67.3% |
| POP_TOP ENTER_EXECUTOR | 60 | 0.9% | 68.2% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.9% | 69.2% |
| BUILD_LIST LOAD_DEREF | 60 | 0.9% | 70.1% |
| CALL POP_TOP | 60 | 0.9% | 71.1% |
| CALL CALL | 60 | 0.9% | 72.0% |
| CALL LOAD_FAST | 60 | 0.9% | 73.0% |
| CALL STORE_FAST | 60 | 0.9% | 73.9% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.9% | 74.8% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.9% | 75.8% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.9% | 76.7% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.9% | 77.7% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.9% | 78.6% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.9% | 79.6% |
| LOAD_FAST GET_ITER | 60 | 0.9% | 80.5% |
| LOAD_FAST BUILD_LIST | 60 | 0.9% | 81.4% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.9% | 82.4% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.9% | 83.3% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.9% | 84.3% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.9% | 85.2% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.9% | 86.2% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 60 | 0.9% | 87.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.9% | 88.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.9% | 89.0% |
| LOAD_GLOBAL_MODULE STORE_FAST | 60 | 0.9% | 89.9% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.9% | 90.9% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.6% | 91.5% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.6% | 92.1% |
| LOAD_FAST LOAD_ATTR | 40 | 0.6% | 92.8% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.6% | 93.4% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.6% | 94.0% |
| LOAD_FAST LOAD_ATTR_MODULE | 40 | 0.6% | 94.7% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 40 | 0.6% | 95.3% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.6% | 95.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 40 | 0.6% | 96.5% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.3% | 96.9% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.3% | 97.2% |
| CALL CALL_BUILTIN_CLASS | 20 | 0.3% | 97.5% |
| ENTER_EXECUTOR LOAD_GLOBAL | 20 | 0.3% | 97.8% |
| LOAD_ATTR PUSH_NULL | 20 | 0.3% | 98.1% |
| LOAD_ATTR LOAD_ATTR_WITH_HINT | 20 | 0.3% | 98.4% |
| LOAD_FAST BINARY_OP | 20 | 0.3% | 98.7% |
| LOAD_FAST CALL | 20 | 0.3% | 99.1% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.3% | 99.4% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.3% | 99.7% |
| RESUME_CHECK LOAD_GLOBAL | 20 | 0.3% | 100.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 90.9% |
| CALL | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 81.8% |
| NOP | 60 | 9.1% |
| ENTER_EXECUTOR | 60 | 9.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 66.7% |
| LOAD_ATTR_MODULE | 160 | 17.8% |
| LOAD_DEREF | 120 | 13.3% |
| LOAD_ATTR | 20 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 600 | 66.7% |
| CALL | 180 | 20.0% |
| LOAD_FAST | 120 | 13.3% |


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
| LOAD_GLOBAL_MODULE | 60 | 50.0% |
| LOAD_FAST | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 80 | 66.7% |
| PUSH_NULL | 20 | 16.7% |
| LOAD_ATTR_WITH_HINT | 20 | 16.7% |


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
| POP_TOP | 540 | 52.9% |
| STORE_FAST | 240 | 23.5% |
| PUSH_NULL | 120 | 11.8% |
| CALL | 60 | 5.9% |
| LOAD_GLOBAL_BUILTIN | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 600 | 58.8% |
| GET_ITER | 60 | 5.9% |
| BUILD_LIST | 60 | 5.9% |
| CALL_FUNCTION_EX | 60 | 5.9% |
| LOAD_ATTR | 40 | 3.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 100.0% |


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
| CALL | 60 | 16.7% |
| CALL_BUILTIN_CLASS | 60 | 16.7% |
| FOR_ITER_RANGE | 60 | 16.7% |
| LOAD_ATTR_MODULE | 60 | 16.7% |
| LOAD_ATTR_WITH_HINT | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 66.7% |
| LOAD_GLOBAL_MODULE | 80 | 22.2% |
| LOAD_GLOBAL | 40 | 11.1% |


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
| LOAD_FAST_LOAD_FAST | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 100 | 45.5% |
| LOAD_ATTR | 80 | 36.4% |
| LOAD_FAST | 40 | 18.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 72.7% |
| STORE_FAST | 60 | 27.3% |


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
|     deferred | 180 | 19.6% |
|          hit | 660 | 71.7% |

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
|     deferred | 20 | 5.0% |
|          hit | 280 | 70.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
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
| Basic | 4,380 | 68.9% |
| Not specialized | 520 | 8.2% |
| Specialized | 1,460 | 23.0% |

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
| Allocations | 7,480,520 | 100.0% |
| Allocations to 512 bytes | 3,794,120 | 50.7% |
| Allocations to 4 kbytes | 2,457,600 | 32.9% |
| Allocations over 4 kbytes | 1,228,800 | 16.4% |
| Frees | 7,480,500 |  |
| New values | 0 |  |
| Interpreter increfs | 2,860 | 0.0% |
| Interpreter decrefs | 3,660 | 0.0% |
| Increfs | 78,642,460 | 100.0% |
| Decrefs | 81,207,080 | 100.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 1,228,840 |  |
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
| Uops executed | 9,580,380 | 159,673.00 |
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
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 0 | 0.0% |
| <= 131,072 | 0 | 0.0% |
| <= 262,144 | 60 | 100.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 3,684,600 | 38.5% | 38.5% |  |
| _SET_IP | 1,473,960 | 15.4% | 53.8% |  |
| POP_TOP | 1,228,260 | 12.8% | 66.7% |  |
| PUSH_NULL | 1,228,200 | 12.8% | 79.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,228,200 | 12.8% | 92.3% |  |
| _ITER_CHECK_RANGE | 122,880 | 1.3% | 93.6% |  |
| _IS_ITER_EXHAUSTED_RANGE | 122,880 | 1.3% | 94.9% |  |
| _POP_JUMP_IF_TRUE | 122,880 | 1.3% | 96.2% |  |
| STORE_FAST | 122,820 | 1.3% | 97.4% |  |
| _ITER_NEXT_RANGE | 122,820 | 1.3% | 98.7% |  |
| _JUMP_TO_TOP | 122,820 | 1.3% | 100.0% |  |
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
