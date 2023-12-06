
# Pystats results

- benchmark: unpickle_list
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,680 | 25.5% | 25.5% |  |
| PUSH_NULL | 960 | 14.6% | 40.1% |  |
| POP_TOP | 660 | 10.0% | 50.2% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 660 | 10.0% | 60.2% |  |
| STORE_FAST | 300 | 4.6% | 64.7% |  |
| LOAD_ATTR_MODULE | 280 | 4.3% | 69.0% |  |
| CALL | 280 | 4.3% | 73.3% |  |
| LOAD_GLOBAL_MODULE | 220 | 3.3% | 76.6% |  |
| LOAD_DEREF | 180 | 2.7% | 79.3% |  |
| LOAD_ATTR | 140 | 2.1% | 81.5% |  |
| RETURN_VALUE | 120 | 1.8% | 83.3% |  |
| RESUME_CHECK | 120 | 1.8% | 85.1% |  |
| LOAD_GLOBAL | 120 | 1.8% | 86.9% |  |
| CALL_FUNCTION_EX | 120 | 1.8% | 88.8% |  |
| NOP | 60 | 0.9% | 89.7% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.9% | 90.6% |  |
| LOAD_ATTR_WITH_HINT | 60 | 0.9% | 91.5% |  |
| LIST_EXTEND | 60 | 0.9% | 92.4% |  |
| GET_ITER | 60 | 0.9% | 93.3% |  |
| FOR_ITER_RANGE | 60 | 0.9% | 94.2% |  |
| ENTER_EXECUTOR | 60 | 0.9% | 95.1% |  |
| COPY_FREE_VARS | 60 | 0.9% | 96.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.9% | 97.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.9% | 97.9% |  |
| BUILD_LIST | 60 | 0.9% | 98.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.9% | 99.7% |  |
| BINARY_OP | 20 | 0.3% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| PUSH_NULL LOAD_FAST | 720 | 10.9% | 10.9% |
| LOAD_FAST PUSH_NULL | 600 | 9.1% | 20.1% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 9.1% | 29.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 600 | 9.1% | 38.3% |
| POP_TOP LOAD_FAST | 540 | 8.2% | 46.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 220 | 3.3% | 49.8% |
| STORE_FAST LOAD_FAST | 180 | 2.7% | 52.6% |
| PUSH_NULL CALL | 180 | 2.7% | 55.3% |
| LOAD_DEREF PUSH_NULL | 120 | 1.8% | 57.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 1.5% | 58.7% |
| LOAD_ATTR LOAD_ATTR_MODULE | 100 | 1.5% | 60.2% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 1.2% | 61.4% |
| LOAD_FAST LOAD_ATTR_MODULE | 80 | 1.2% | 62.6% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.9% | 63.5% |
| RESUME_CHECK LOAD_FAST | 60 | 0.9% | 64.4% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.9% | 65.3% |
| POP_TOP NOP | 60 | 0.9% | 66.3% |
| POP_TOP ENTER_EXECUTOR | 60 | 0.9% | 67.2% |
| NOP LOAD_DEREF | 60 | 0.9% | 68.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.9% | 69.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.9% | 69.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.9% | 70.8% |
| LOAD_FAST LOAD_ATTR | 60 | 0.9% | 71.7% |
| LOAD_FAST GET_ITER | 60 | 0.9% | 72.6% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.9% | 73.6% |
| LOAD_FAST BUILD_LIST | 60 | 0.9% | 74.5% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.9% | 75.4% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.9% | 76.3% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.9% | 77.2% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.9% | 78.1% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.9% | 79.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.9% | 79.9% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.9% | 80.9% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.9% | 81.8% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.9% | 82.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 60 | 0.9% | 83.6% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.9% | 84.5% |
| CALL STORE_FAST | 60 | 0.9% | 85.4% |
| CALL POP_TOP | 60 | 0.9% | 86.3% |
| CALL LOAD_FAST | 60 | 0.9% | 87.2% |
| CALL CALL | 60 | 0.9% | 88.1% |
| BUILD_LIST LOAD_DEREF | 60 | 0.9% | 89.1% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.9% | 90.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 40 | 0.6% | 90.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 40 | 0.6% | 91.2% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.6% | 91.8% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.6% | 92.4% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 40 | 0.6% | 93.0% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 40 | 0.6% | 93.6% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.6% | 94.2% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.6% | 94.8% |
| LOAD_ATTR_WITH_HINT CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.6% | 95.4% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.6% | 96.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.3% | 96.4% |
| PUSH_NULL LOAD_GLOBAL | 20 | 0.3% | 96.7% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.3% | 97.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.3% | 97.3% |
| LOAD_FAST CALL | 20 | 0.3% | 97.6% |
| LOAD_FAST BINARY_OP | 20 | 0.3% | 97.9% |
| LOAD_ATTR_WITH_HINT CALL | 20 | 0.3% | 98.2% |
| LOAD_ATTR PUSH_NULL | 20 | 0.3% | 98.5% |
| LOAD_ATTR LOAD_ATTR_WITH_HINT | 20 | 0.3% | 98.8% |
| ENTER_EXECUTOR LOAD_GLOBAL | 20 | 0.3% | 99.1% |
| CALL CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 0.3% | 99.4% |
| CALL CALL_BUILTIN_CLASS | 20 | 0.3% | 99.7% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.3% | 100.0% |


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
| LOAD_FAST | 600 | 62.5% |
| LOAD_ATTR_MODULE | 220 | 22.9% |
| LOAD_DEREF | 120 | 12.5% |
| LOAD_ATTR | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 75.0% |
| CALL | 180 | 18.8% |
| LOAD_GLOBAL_MODULE | 40 | 4.2% |
| LOAD_GLOBAL | 20 | 2.1% |


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
| PUSH_NULL | 180 | 64.3% |
| CALL | 60 | 21.4% |
| LOAD_FAST | 20 | 7.1% |
| LOAD_ATTR_WITH_HINT | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 21.4% |
| POP_TOP | 60 | 21.4% |
| LOAD_FAST | 60 | 21.4% |
| CALL | 60 | 21.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 7.1% |


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
| LOAD_GLOBAL_MODULE | 60 | 42.9% |
| LOAD_FAST | 60 | 42.9% |
| LOAD_GLOBAL | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 71.4% |
| PUSH_NULL | 20 | 14.3% |
| LOAD_ATTR_WITH_HINT | 20 | 14.3% |


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
| PUSH_NULL | 720 | 42.9% |
| POP_TOP | 540 | 32.1% |
| STORE_FAST | 180 | 10.7% |
| RESUME_CHECK | 60 | 3.6% |
| LOAD_GLOBAL_MODULE | 60 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 600 | 35.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 35.7% |
| LOAD_ATTR_MODULE | 80 | 4.8% |
| LOAD_ATTR | 60 | 3.6% |
| GET_ITER | 60 | 3.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 33.3% |
| RETURN_VALUE | 40 | 33.3% |
| PUSH_NULL | 20 | 16.7% |
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
| LOAD_ATTR_MODULE | 60 | 20.0% |
| FOR_ITER_RANGE | 60 | 20.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 20.0% |
| CALL_BUILTIN_CLASS | 60 | 20.0% |
| CALL | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| LOAD_GLOBAL_MODULE | 40 | 13.3% |
| LOAD_GLOBAL_BUILTIN | 40 | 13.3% |
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
| LOAD_FAST | 600 | 90.9% |
| LOAD_ATTR_WITH_HINT | 40 | 6.1% |
| CALL | 20 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600 | 90.9% |
| STORE_FAST | 60 | 9.1% |


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
| LOAD_GLOBAL_MODULE | 100 | 35.7% |
| LOAD_ATTR | 100 | 35.7% |
| LOAD_FAST | 80 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 220 | 78.6% |
| STORE_FAST | 60 | 21.4% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 66.7% |
| CALL | 20 | 33.3% |


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
| LOAD_GLOBAL | 80 | 36.4% |
| STORE_FAST | 40 | 18.2% |
| PUSH_NULL | 40 | 18.2% |
| ENTER_EXECUTOR | 40 | 18.2% |
| RETURN_VALUE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 45.5% |
| LOAD_FAST | 60 | 27.3% |
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
| LOAD_FAST | 60 | 50.0% |
| LOAD_DEREF | 60 | 50.0% |


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
| specialization.deferred |          180 | 18.0% |
|          hit |          720 | 72.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 40.0% |
| Failure | 60 | 60.0% |

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
| specialization.deferred |           20 | 4.2% |
|          hit |          340 | 70.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
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
| Basic | 4,440 | 67.5% |
| Not specialized | 560 | 8.5% |
| Specialized | 1,580 | 24.0% |

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
| Allocations from freelist | 76,185,820 | 62.6% |
| Frees to freelist | 76,185,780 |  |
| Allocations | 45,573,680 | 37.4% |
| Allocations to 512 bytes | 45,573,500 | 37.4% |
| Allocations to 4 kbytes | 120 | 0.0% |
| Allocations over 4 kbytes | 60 | 0.0% |
| Frees | 86,124,060 |  |
| New values | 0 |  |
| Interpreter increfs | 2,980 | 0.0% |
| Interpreter decrefs | 3,840 | 0.0% |
| Increfs | 119,196,580 | 100.0% |
| Decrefs | 197,946,860 | 100.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 95 |  |
| Method cache misses | 5 |  |
| Method cache collisions | 5 |  |
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

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 60 |  |
| Uops executed | 8,352,180 | 139,203 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 1024 | 0 | 0.0% |
| <= 2048 | 0 | 0.0% |
| <= 4096 | 0 | 0.0% |
| <= 8192 | 0 | 0.0% |
| <= 16384 | 0 | 0.0% |
| <= 32768 | 0 | 0.0% |
| <= 65536 | 0 | 0.0% |
| <= 131072 | 0 | 0.0% |
| <= 262144 | 60 | 100.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST | 2,456,400 | 29.4% | 29.4% |
| _SET_IP | 1,473,960 | 17.6% | 47.1% |
| POP_TOP | 1,228,260 | 14.7% | 61.8% |
| PUSH_NULL | 1,228,200 | 14.7% | 76.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,228,200 | 14.7% | 91.2% |
| _POP_JUMP_IF_TRUE | 122,880 | 1.5% | 92.6% |
| _ITER_CHECK_RANGE | 122,880 | 1.5% | 94.1% |
| _IS_ITER_EXHAUSTED_RANGE | 122,880 | 1.5% | 95.6% |
| _JUMP_TO_TOP | 122,820 | 1.5% | 97.1% |
| _ITER_NEXT_RANGE | 122,820 | 1.5% | 98.5% |
| STORE_FAST | 122,820 | 1.5% | 100.0% |
| _EXIT_TRACE | 60 | 0.0% | 100.0% |


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
Stats gathered on: 2023-10-04
