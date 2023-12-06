
# Pystats results

- benchmark: pickle_dict
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| PUSH_NULL | 153,900 | 16.6% | 16.6% |  |
| LOAD_ATTR_MODULE | 153,760 | 16.6% | 33.3% |  |
| POP_TOP | 153,660 | 16.6% | 49.9% |  |
| LOAD_FAST_LOAD_FAST | 153,600 | 16.6% | 66.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 153,600 | 16.6% | 83.1% |  |
| LOAD_FAST | 123,300 | 13.3% | 96.4% |  |
| ENTER_EXECUTOR | 30,720 | 3.3% | 99.8% |  |
| STORE_FAST | 300 | 0.0% | 99.8% |  |
| CALL | 260 | 0.0% | 99.8% |  |
| LOAD_GLOBAL_MODULE | 220 | 0.0% | 99.8% |  |
| LOAD_DEREF | 180 | 0.0% | 99.9% |  |
| RETURN_VALUE | 120 | 0.0% | 99.9% |  |
| RESUME_CHECK | 120 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 120 | 0.0% | 99.9% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 99.9% |  |
| LOAD_ATTR | 100 | 0.0% | 99.9% |  |
| NOP | 60 | 0.0% | 99.9% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 99.9% |  |
| LOAD_ATTR_WITH_HINT | 60 | 0.0% | 99.9% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| GET_ITER | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_ATTR_MODULE PUSH_NULL | 153,760 | 16.6% | 16.6% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 153,600 | 16.6% | 33.2% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 153,600 | 16.6% | 49.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 153,600 | 16.6% | 66.5% |
| LOAD_FAST LOAD_ATTR_MODULE | 122,940 | 13.3% | 79.8% |
| POP_TOP LOAD_FAST | 122,880 | 13.3% | 93.0% |
| POP_TOP ENTER_EXECUTOR | 30,720 | 3.3% | 96.4% |
| ENTER_EXECUTOR LOAD_ATTR_MODULE | 30,660 | 3.3% | 99.7% |
| STORE_FAST LOAD_FAST | 180 | 0.0% | 99.7% |
| PUSH_NULL CALL | 180 | 0.0% | 99.7% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 99.7% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 99.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 99.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 0.0% | 99.8% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 0.0% | 99.8% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 99.8% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 99.8% |
| POP_TOP NOP | 60 | 0.0% | 99.8% |
| NOP LOAD_DEREF | 60 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE STORE_FAST | 60 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 99.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.0% | 99.8% |
| LOAD_FAST GET_ITER | 60 | 0.0% | 99.8% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 99.8% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 99.8% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 99.8% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 60 | 0.0% | 99.8% |
| LOAD_ATTR LOAD_ATTR_MODULE | 60 | 0.0% | 99.9% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 99.9% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.0% | 99.9% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 99.9% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 99.9% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 99.9% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 99.9% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 99.9% |
| CALL STORE_FAST | 60 | 0.0% | 99.9% |
| CALL POP_TOP | 60 | 0.0% | 99.9% |
| CALL LOAD_FAST | 60 | 0.0% | 99.9% |
| CALL CALL | 60 | 0.0% | 99.9% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 99.9% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.0% | 99.9% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_FAST CALL | 20 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 20 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 20 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_WITH_HINT | 20 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 20 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% | 100.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 153,600 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,880 | 80.0% |
| ENTER_EXECUTOR | 30,720 | 20.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 153,760 | 99.9% |
| LOAD_DEREF | 120 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 153,600 | 99.8% |
| CALL | 180 | 0.1% |
| LOAD_FAST | 120 | 0.1% |


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
| STORE_FAST | 60 | 23.1% |
| POP_TOP | 60 | 23.1% |
| LOAD_FAST | 60 | 23.1% |
| CALL | 60 | 23.1% |
| CALL_BUILTIN_CLASS | 20 | 7.7% |


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
| POP_TOP | 30,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 30,660 | 99.8% |
| LOAD_GLOBAL_MODULE | 40 | 0.1% |
| LOAD_GLOBAL | 20 | 0.1% |


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
| LOAD_GLOBAL | 20 | 20.0% |
| LOAD_FAST | 20 | 20.0% |

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
| POP_TOP | 122,880 | 99.7% |
| STORE_FAST | 180 | 0.1% |
| PUSH_NULL | 120 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 122,940 | 99.7% |
| GET_ITER | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |
| LOAD_ATTR_WITH_HINT | 40 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 153,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 153,600 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 33.3% |
| RETURN_VALUE | 40 | 33.3% |
| RESUME_CHECK | 20 | 16.7% |
| ENTER_EXECUTOR | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| LOAD_GLOBAL_BUILTIN | 20 | 16.7% |
| LOAD_ATTR | 20 | 16.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 20.0% |
| LOAD_ATTR_WITH_HINT | 60 | 20.0% |
| FOR_ITER_RANGE | 60 | 20.0% |
| CALL_BUILTIN_CLASS | 60 | 20.0% |
| CALL | 60 | 20.0% |

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
| LOAD_FAST_LOAD_FAST | 153,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 153,600 | 100.0% |


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
| LOAD_FAST | 122,940 | 80.0% |
| ENTER_EXECUTOR | 30,660 | 19.9% |
| LOAD_GLOBAL_MODULE | 100 | 0.1% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 153,760 | 100.0% |


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
| STORE_FAST | 80 | 36.4% |
| LOAD_GLOBAL | 80 | 36.4% |
| ENTER_EXECUTOR | 40 | 18.2% |
| RETURN_VALUE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 45.5% |
| STORE_FAST | 60 | 27.3% |
| LOAD_ATTR | 60 | 27.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| CALL_FUNCTION_EX | 60 | 50.0% |

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
|---|---|---|
|          hit |           60 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          180 | 0.1% |
|          hit |       153660 | 99.8% |

#### Specialization attempts

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
|---|---|---|
|          hit |           60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |       153820 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 5.0% |
|          hit |          280 | 70.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 616,260 | 66.6% |
| Not specialized | 500 | 0.1% |
| Specialized | 308,000 | 33.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 180 | 81.8% |
| LOAD_GLOBAL | 20 | 9.1% |
| LOAD_ATTR | 20 | 9.1% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR | 0 | 0.0% |
| SEND | 0 | 0.0% |


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
| Frames pushed | 120 | 100.0% |
| Frame objects created | 0 | 0.0% |


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
| Interpreter increfs | 462,340 | 1.5% |
| Interpreter decrefs | 616,140 | 1.9% |
| Increfs | 31,058,320 | 98.5% |
| Decrefs | 31,227,380 | 98.1% |
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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
