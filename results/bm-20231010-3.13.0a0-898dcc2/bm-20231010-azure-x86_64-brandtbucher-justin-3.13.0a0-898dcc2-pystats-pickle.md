
# Pystats results

- benchmark: pickle
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| POP_TOP | 952,920 | 20.1% | 20.1% |  |
| LOAD_FAST_LOAD_FAST | 952,860 | 20.1% | 40.2% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 952,860 | 20.1% | 60.3% |  |
| PUSH_NULL | 891,720 | 18.8% | 79.2% |  |
| LOAD_FAST | 861,240 | 18.2% | 97.3% |  |
| ENTER_EXECUTOR | 122,880 | 2.6% | 99.9% |  |
| STORE_FAST | 420 | 0.0% | 99.9% |  |
| LOAD_GLOBAL_MODULE | 340 | 0.0% | 100.0% |  |
| CALL | 260 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 160 | 0.0% | 100.0% |  |
| RETURN_VALUE | 120 | 0.0% | 100.0% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 120 | 0.0% | 100.0% |  |
| GET_ITER | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_WITH_HINT | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 952,860 | 20.1% | 20.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 952,860 | 20.1% | 40.2% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 891,420 | 18.8% | 59.0% |
| LOAD_FAST PUSH_NULL | 860,760 | 18.2% | 77.2% |
| POP_TOP LOAD_FAST | 860,700 | 18.2% | 95.4% |
| POP_TOP ENTER_EXECUTOR | 92,160 | 1.9% | 97.3% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 61,440 | 1.3% | 98.6% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 30,720 | 0.6% | 99.3% |
| ENTER_EXECUTOR PUSH_NULL | 30,660 | 0.6% | 99.9% |
| STORE_FAST LOAD_FAST | 300 | 0.0% | 99.9% |
| PUSH_NULL CALL | 180 | 0.0% | 99.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 99.9% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.9% |
| LOAD_FAST GET_ITER | 120 | 0.0% | 99.9% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 80 | 0.0% | 99.9% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE BUILD_TUPLE | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_TUPLE | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| FOR_ITER_TUPLE STORE_FAST | 60 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL CALL | 60 | 0.0% | 100.0% |
| BUILD_TUPLE STORE_FAST | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 40 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_MODULE | 40 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
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
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 60 | 50.0% |
| FOR_ITER_RANGE | 60 | 50.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 952,860 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 860,700 | 90.3% |
| ENTER_EXECUTOR | 92,160 | 9.7% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 860,760 | 96.5% |
| ENTER_EXECUTOR | 30,660 | 3.4% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 891,420 | 100.0% |
| CALL | 180 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


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

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


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
| POP_TOP | 92,160 | 75.0% |
| ENTER_EXECUTOR | 30,720 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 61,440 | 50.0% |
| ENTER_EXECUTOR | 30,720 | 25.0% |
| PUSH_NULL | 30,660 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


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
| POP_TOP | 860,700 | 99.9% |
| STORE_FAST | 300 | 0.0% |
| PUSH_NULL | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 860,760 | 99.9% |
| GET_ITER | 120 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |
| LOAD_ATTR_WITH_HINT | 40 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 891,420 | 93.6% |
| ENTER_EXECUTOR | 61,440 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 952,860 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 25.0% |
| RETURN_VALUE | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |
| RESUME_CHECK | 20 | 12.5% |
| ENTER_EXECUTOR | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 75.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 12.5% |
| LOAD_ATTR | 20 | 12.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 60 | 14.3% |
| LOAD_ATTR_MODULE | 60 | 14.3% |
| FOR_ITER_TUPLE | 60 | 14.3% |
| FOR_ITER_RANGE | 60 | 14.3% |
| CALL_BUILTIN_CLASS | 60 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 71.4% |
| LOAD_GLOBAL_MODULE | 80 | 19.0% |
| LOAD_GLOBAL | 40 | 9.5% |


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
| LOAD_FAST_LOAD_FAST | 952,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 952,860 | 100.0% |


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

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

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
| LOAD_GLOBAL | 120 | 35.3% |
| STORE_FAST | 80 | 23.5% |
| LOAD_GLOBAL_MODULE | 80 | 23.5% |
| ENTER_EXECUTOR | 40 | 11.8% |
| RETURN_VALUE | 20 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 29.4% |
| LOAD_GLOBAL_MODULE | 80 | 23.5% |
| LOAD_ATTR | 60 | 17.6% |
| BUILD_TUPLE | 60 | 17.6% |
| LOAD_GLOBAL | 40 | 11.8% |


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
| specialization.deferred |          180 | 0.0% |
|          hit |      1843260 | 100.0% |

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
|          hit |          120 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

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

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 3.6% |
|          hit |          400 | 71.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
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
| Basic | 3,782,940 | 79.9% |
| Not specialized | 560 | 0.0% |
| Specialized | 953,900 | 20.1% |

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
| Allocations from freelist | 3,072,280 | 16.6% |
| Frees to freelist | 3,072,240 |  |
| Allocations | 15,406,280 | 83.4% |
| Allocations to 512 bytes | 10,491,080 | 56.8% |
| Allocations to 4 kbytes | 2,457,600 | 13.3% |
| Allocations over 4 kbytes | 2,457,600 | 13.3% |
| Frees | 15,406,260 |  |
| New values | 0 |  |
| Interpreter increfs | 1,938,340 | 1.1% |
| Interpreter decrefs | 2,860,560 | 1.5% |
| Increfs | 172,215,520 | 98.9% |
| Decrefs | 182,398,940 | 98.5% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 2,457,635 |  |
| Method cache misses | 614,405 |  |
| Method cache collisions | 614,425 |  |
| Method cache dunder hits | 5,529,580 |  |
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
Stats gathered on: 2023-10-11
