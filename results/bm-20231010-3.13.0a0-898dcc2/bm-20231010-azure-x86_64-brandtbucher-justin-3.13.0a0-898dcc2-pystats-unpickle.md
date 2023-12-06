
# Pystats results

- benchmark: unpickle
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 785,460 | 37.2% | 37.2% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 430,860 | 20.4% | 57.6% |  |
| POP_TOP | 430,740 | 20.4% | 78.0% |  |
| PUSH_NULL | 400,440 | 19.0% | 96.9% |  |
| ENTER_EXECUTOR | 61,440 | 2.9% | 99.8% |  |
| STORE_FAST | 540 | 0.0% | 99.9% |  |
| LOAD_ATTR_MODULE | 400 | 0.0% | 99.9% |  |
| LOAD_GLOBAL_MODULE | 340 | 0.0% | 99.9% |  |
| CALL | 320 | 0.0% | 99.9% |  |
| LOAD_ATTR | 220 | 0.0% | 99.9% |  |
| LOAD_DEREF | 180 | 0.0% | 99.9% |  |
| LOAD_ATTR_WITH_HINT | 180 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 160 | 0.0% | 99.9% |  |
| RETURN_VALUE | 120 | 0.0% | 99.9% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| GET_ITER | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |  |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 430,680 | 20.4% | 20.4% |
| PUSH_NULL LOAD_FAST | 400,080 | 18.9% | 39.3% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 399,960 | 18.9% | 58.3% |
| LOAD_FAST PUSH_NULL | 384,660 | 18.2% | 76.5% |
| POP_TOP LOAD_FAST | 384,600 | 18.2% | 94.7% |
| POP_TOP ENTER_EXECUTOR | 46,080 | 2.2% | 96.9% |
| ENTER_EXECUTOR CALL_BUILTIN_FAST_WITH_KEYWORDS | 30,720 | 1.5% | 98.3% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 15,360 | 0.7% | 99.0% |
| ENTER_EXECUTOR PUSH_NULL | 15,300 | 0.7% | 99.8% |
| STORE_FAST LOAD_FAST | 360 | 0.0% | 99.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 340 | 0.0% | 99.8% |
| PUSH_NULL CALL | 180 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 180 | 0.0% | 99.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 180 | 0.0% | 99.8% |
| LOAD_FAST LOAD_ATTR_MODULE | 160 | 0.0% | 99.8% |
| LOAD_FAST LOAD_ATTR | 140 | 0.0% | 99.8% |
| LOAD_ATTR LOAD_ATTR_MODULE | 140 | 0.0% | 99.8% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.8% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.9% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 120 | 0.0% | 99.9% |
| LOAD_FAST GET_ITER | 120 | 0.0% | 99.9% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 99.9% |
| LOAD_ATTR_WITH_HINT CALL_BUILTIN_FAST_WITH_KEYWORDS | 120 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 99.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 60 | 0.0% | 99.9% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_FAST | 60 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 99.9% |
| PUSH_NULL LOAD_GLOBAL | 60 | 0.0% | 99.9% |
| POP_TOP NOP | 60 | 0.0% | 99.9% |
| NOP LOAD_DEREF | 60 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 99.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.0% | 99.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 60 | 0.0% | 99.9% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 99.9% |
| LOAD_FAST BUILD_TUPLE | 60 | 0.0% | 99.9% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 99.9% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 99.9% |
| LOAD_ATTR_WITH_HINT CALL | 60 | 0.0% | 99.9% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 99.9% |
| LOAD_ATTR LOAD_ATTR_WITH_HINT | 60 | 0.0% | 99.9% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 99.9% |
| GET_ITER FOR_ITER_TUPLE | 60 | 0.0% | 99.9% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 99.9% |
| FOR_ITER_TUPLE STORE_FAST | 60 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.0% | 99.9% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 99.9% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 99.9% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 99.9% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |
| CALL CALL | 60 | 0.0% | 100.0% |
| BUILD_TUPLE STORE_FAST | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_FAST CALL | 20 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 20 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 20 | 0.0% | 100.0% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 430,680 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,600 | 89.3% |
| ENTER_EXECUTOR | 46,080 | 10.7% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,660 | 96.1% |
| ENTER_EXECUTOR | 15,300 | 3.8% |
| LOAD_ATTR_MODULE | 340 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,080 | 99.9% |
| CALL | 180 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


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
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 56.2% |
| LOAD_ATTR_WITH_HINT | 60 | 18.8% |
| CALL | 60 | 18.8% |
| LOAD_FAST | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 18.8% |
| POP_TOP | 60 | 18.8% |
| LOAD_FAST | 60 | 18.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 18.8% |
| CALL | 60 | 18.8% |


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
| POP_TOP | 46,080 | 75.0% |
| ENTER_EXECUTOR | 15,360 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 30,720 | 50.0% |
| ENTER_EXECUTOR | 15,360 | 25.0% |
| PUSH_NULL | 15,300 | 24.9% |
| LOAD_GLOBAL_MODULE | 40 | 0.1% |
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
| LOAD_FAST | 140 | 63.6% |
| LOAD_GLOBAL_MODULE | 60 | 27.3% |
| LOAD_GLOBAL | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 140 | 63.6% |
| LOAD_ATTR_WITH_HINT | 60 | 27.3% |
| PUSH_NULL | 20 | 9.1% |


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
| PUSH_NULL | 400,080 | 50.9% |
| POP_TOP | 384,600 | 49.0% |
| STORE_FAST | 360 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 399,960 | 50.9% |
| PUSH_NULL | 384,660 | 49.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_ATTR_WITH_HINT | 120 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 37.5% |
| STORE_FAST | 40 | 25.0% |
| RETURN_VALUE | 40 | 25.0% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 180 | 33.3% |
| LOAD_ATTR_MODULE | 60 | 11.1% |
| FOR_ITER_TUPLE | 60 | 11.1% |
| FOR_ITER_RANGE | 60 | 11.1% |
| CALL_BUILTIN_CLASS | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 66.7% |
| LOAD_FAST_LOAD_FAST | 60 | 11.1% |
| LOAD_GLOBAL_MODULE | 40 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 40 | 7.4% |
| LOAD_GLOBAL | 40 | 7.4% |


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
| LOAD_FAST | 399,960 | 92.8% |
| ENTER_EXECUTOR | 30,720 | 7.1% |
| LOAD_ATTR_WITH_HINT | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 430,680 | 100.0% |
| STORE_FAST | 180 | 0.0% |


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
| LOAD_FAST | 160 | 40.0% |
| LOAD_ATTR | 140 | 35.0% |
| LOAD_GLOBAL_MODULE | 100 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 340 | 85.0% |
| STORE_FAST | 60 | 15.0% |


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
| PUSH_NULL | 120 | 35.3% |
| LOAD_GLOBAL | 120 | 35.3% |
| STORE_FAST | 40 | 11.8% |
| ENTER_EXECUTOR | 40 | 11.8% |
| RETURN_VALUE | 20 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 52.9% |
| LOAD_ATTR_MODULE | 100 | 29.4% |
| LOAD_ATTR | 60 | 17.6% |


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
| specialization.deferred |          180 | 0.0% |
|          hit |       921840 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 57.1% |
| Failure | 60 | 42.9% |

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
| specialization.deferred |           20 | 2.5% |
|          hit |          580 | 72.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
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
| Basic | 1,679,580 | 79.5% |
| Not specialized | 720 | 0.0% |
| Specialized | 432,200 | 20.5% |

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
| Allocations from freelist | 5,530,180 | 7.1% |
| Frees to freelist | 5,530,140 |  |
| Allocations | 72,209,060 | 92.9% |
| Allocations to 512 bytes | 70,979,780 | 91.3% |
| Allocations to 4 kbytes | 1,229,040 | 1.6% |
| Allocations over 4 kbytes | 240 | 0.0% |
| Frees | 74,973,415 |  |
| New values | 0 |  |
| Interpreter increfs | 848,320 | 0.5% |
| Interpreter decrefs | 1,294,620 | 0.5% |
| Increfs | 171,033,836 | 99.5% |
| Decrefs | 238,495,111 | 99.5% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 614,704 |  |
| Method cache misses | 307,276 |  |
| Method cache collisions | 307,296 |  |
| Method cache dunder hits | 614,889 |  |
| Method cache dunder misses | 51 |  |


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
