
# Pystats results

- benchmark: fannkuch
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 271,923,540 | 18.4% | 18.4% |  |
| LOAD_FAST | 194,813,040 | 13.1% | 31.5% |  |
| LOAD_FAST_LOAD_FAST | 142,647,060 | 9.6% | 41.1% |  |
| POP_JUMP_IF_FALSE | 130,047,180 | 8.8% | 49.9% |  |
| STORE_FAST | 101,824,680 | 6.9% | 56.8% |  |
| BINARY_SUBSCR_LIST_INT | 96,465,600 | 6.5% | 63.3% |  |
| COMPARE_OP_INT | 94,867,980 | 6.4% | 69.7% |  |
| ENTER_EXECUTOR | 57,284,280 | 3.9% | 73.6% |  |
| BINARY_OP_ADD_INT | 50,112,660 | 3.4% | 76.9% |  |
| PUSH_NULL | 41,429,100 | 2.8% | 79.7% |  |
| SWAP | 41,428,800 | 2.8% | 82.5% |  |
| COPY | 41,428,800 | 2.8% | 85.3% |  |
| CALL_BUILTIN_FAST | 41,428,800 | 2.8% | 88.1% |  |
| TO_BOOL_INT | 34,473,600 | 2.3% | 90.4% |  |
| BINARY_OP_SUBTRACT_INT | 20,714,580 | 1.4% | 91.8% |  |
| POP_TOP | 20,714,520 | 1.4% | 93.2% |  |
| STORE_SUBSCR_LIST_INT | 20,714,460 | 1.4% | 94.6% |  |
| BINARY_SUBSCR | 17,241,000 | 1.2% | 95.8% |  |
| STORE_SLICE | 17,236,800 | 1.2% | 97.0% |  |
| BUILD_SLICE | 17,236,800 | 1.2% | 98.1% |  |
| BINARY_SLICE | 17,236,800 | 1.2% | 99.3% |  |
| JUMP_FORWARD | 10,533,600 | 0.7% | 100.0% |  |
| CALL | 440 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 360 | 0.0% | 100.0% |  |
| LOAD_ATTR | 220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 180 | 0.0% | 100.0% |  |
| RETURN_VALUE | 120 | 0.0% | 100.0% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| NOP | 120 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_CONST | 129,946,620 | 8.8% | 8.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 94,867,980 | 6.4% | 15.2% |
| STORE_FAST LOAD_FAST | 68,947,680 | 4.7% | 19.8% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 53,590,200 | 3.6% | 23.4% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 52,315,200 | 3.5% | 27.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 50,112,640 | 3.4% | 30.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 48,534,360 | 3.3% | 33.6% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 45,360,000 | 3.1% | 36.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 40,220,220 | 2.7% | 39.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 34,473,600 | 2.3% | 41.7% |
| LOAD_FAST TO_BOOL_INT | 34,473,600 | 2.3% | 44.1% |
| LOAD_CONST LOAD_CONST | 34,473,600 | 2.3% | 46.4% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 34,473,600 | 2.3% | 48.7% |
| BINARY_OP_ADD_INT STORE_FAST | 32,875,800 | 2.2% | 50.9% |
| LOAD_CONST COMPARE_OP_INT | 31,600,960 | 2.1% | 53.1% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 30,759,000 | 2.1% | 55.1% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 30,391,200 | 2.1% | 57.2% |
| ENTER_EXECUTOR LOAD_FAST | 24,257,400 | 1.6% | 58.8% |
| LOAD_FAST PUSH_NULL | 20,714,580 | 1.4% | 60.2% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 20,714,560 | 1.4% | 61.6% |
| SWAP SWAP | 20,714,400 | 1.4% | 63.0% |
| SWAP STORE_SUBSCR_LIST_INT | 20,714,400 | 1.4% | 64.4% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 20,714,400 | 1.4% | 65.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 20,714,400 | 1.4% | 67.2% |
| PUSH_NULL LOAD_CONST | 20,714,400 | 1.4% | 68.6% |
| POP_TOP LOAD_FAST_LOAD_FAST | 20,714,400 | 1.4% | 70.0% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 20,714,400 | 1.4% | 71.4% |
| LOAD_FAST_LOAD_FAST COPY | 20,714,400 | 1.4% | 72.8% |
| LOAD_CONST CALL_BUILTIN_FAST | 20,714,400 | 1.4% | 74.2% |
| COPY COPY | 20,714,400 | 1.4% | 75.6% |
| COPY BINARY_SUBSCR_LIST_INT | 20,714,400 | 1.4% | 77.0% |
| CALL_BUILTIN_FAST POP_TOP | 20,714,400 | 1.4% | 78.4% |
| CALL_BUILTIN_FAST CALL_BUILTIN_FAST | 20,714,400 | 1.4% | 79.8% |
| BINARY_OP_SUBTRACT_INT SWAP | 20,714,400 | 1.4% | 81.2% |
| STORE_FAST LOAD_CONST | 17,236,860 | 1.2% | 82.4% |
| LOAD_CONST STORE_FAST | 17,236,860 | 1.2% | 83.5% |
| LOAD_CONST LOAD_FAST | 17,236,860 | 1.2% | 84.7% |
| STORE_SLICE LOAD_FAST | 17,236,800 | 1.2% | 85.8% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 17,236,800 | 1.2% | 87.0% |
| LOAD_CONST BUILD_SLICE | 17,236,800 | 1.2% | 88.2% |
| LOAD_CONST BINARY_SLICE | 17,236,800 | 1.2% | 89.3% |
| BUILD_SLICE BINARY_SUBSCR | 17,236,800 | 1.2% | 90.5% |
| BINARY_SUBSCR LOAD_FAST | 17,236,800 | 1.2% | 91.7% |
| BINARY_SLICE STORE_FAST | 17,236,800 | 1.2% | 92.8% |
| BINARY_OP_ADD_INT STORE_SLICE | 17,236,800 | 1.2% | 94.0% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 16,329,600 | 1.1% | 95.1% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 15,991,680 | 1.1% | 96.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 15,639,900 | 1.1% | 97.2% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 10,533,600 | 0.7% | 97.9% |
| JUMP_FORWARD ENTER_EXECUTOR | 10,533,600 | 0.7% | 98.6% |
| LOAD_FAST COMPARE_OP_INT | 9,676,800 | 0.7% | 99.3% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 9,676,800 | 0.7% | 100.0% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 705,600 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 4,200 | 0.0% | 100.0% |
| LOAD_FAST STORE_FAST | 960 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 120 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 120 | 0.0% | 100.0% |
| LOAD_ATTR STORE_FAST | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 120 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| CALL CALL | 80 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 60 | 0.0% | 100.0% |
| STORE_FAST NOP | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 60 | 0.0% | 100.0% |
| NOP LOAD_FAST | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 60 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CACHE RESUME_CHECK | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_INT STORE_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 40 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 17,236,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,236,800 | 100.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 17,236,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,236,800 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 17,236,800 | 100.0% |
| BINARY_SUBSCR | 4,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,236,800 | 100.0% |
| BINARY_SUBSCR | 4,200 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| POP_TOP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| LOAD_DEREF | 60 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 20,714,400 | 100.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,714,400 | 100.0% |
| NOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,714,580 | 50.0% |
| LOAD_FAST_LOAD_FAST | 20,714,400 | 50.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR_MODULE | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,714,400 | 50.0% |
| LOAD_CONST | 20,714,400 | 50.0% |
| CALL | 240 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 60 | 50.0% |
| LOAD_GLOBAL | 40 | 33.3% |
| LOAD_GLOBAL_MODULE | 20 | 16.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| LOAD_FAST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 20 | 33.3% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 33.3% |
| BINARY_OP_ADD_INT | 20 | 33.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 17,236,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 17,236,800 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 54.5% |
| CALL | 80 | 18.2% |
| CALL_BUILTIN_CLASS | 60 | 13.6% |
| LOAD_FAST | 40 | 9.1% |
| BINARY_OP_ADD_INT | 20 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 27.3% |
| CALL_BUILTIN_CLASS | 120 | 27.3% |
| CALL | 80 | 18.2% |
| STORE_FAST | 60 | 13.6% |
| LOAD_FAST | 60 | 13.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,714,400 | 50.0% |
| COPY | 20,714,400 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 20,714,400 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 20,714,400 | 50.0% |


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
| POP_JUMP_IF_FALSE | 30,759,000 | 53.7% |
| ENTER_EXECUTOR | 15,991,680 | 27.9% |
| JUMP_FORWARD | 10,533,600 | 18.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,257,400 | 42.3% |
| LOAD_FAST_LOAD_FAST | 16,329,600 | 28.5% |
| ENTER_EXECUTOR | 15,991,680 | 27.9% |
| POP_JUMP_IF_FALSE | 705,600 | 1.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,533,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 10,533,600 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 54.5% |
| LOAD_GLOBAL_MODULE | 40 | 18.2% |
| LOAD_ATTR | 40 | 18.2% |
| LOAD_GLOBAL | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 54.5% |
| LOAD_ATTR_MODULE | 40 | 18.2% |
| LOAD_ATTR | 40 | 18.2% |
| PUSH_NULL | 20 | 9.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 129,946,620 | 47.8% |
| BINARY_SUBSCR_LIST_INT | 52,315,200 | 19.2% |
| LOAD_CONST | 34,473,600 | 12.7% |
| PUSH_NULL | 20,714,400 | 7.6% |
| STORE_FAST | 17,236,860 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 50,112,640 | 18.4% |
| BINARY_SUBSCR_LIST_INT | 45,360,000 | 16.7% |
| LOAD_CONST | 34,473,600 | 12.7% |
| COMPARE_OP_INT | 31,600,960 | 11.6% |
| BINARY_OP_SUBTRACT_INT | 20,714,560 | 7.6% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| NOP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| PUSH_NULL | 60 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 68,947,680 | 35.4% |
| POP_JUMP_IF_FALSE | 40,220,220 | 20.6% |
| ENTER_EXECUTOR | 24,257,400 | 12.5% |
| LOAD_CONST | 17,236,860 | 8.8% |
| STORE_SLICE | 17,236,800 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,946,620 | 66.7% |
| TO_BOOL_INT | 34,473,600 | 17.7% |
| PUSH_NULL | 20,714,580 | 10.6% |
| COMPARE_OP_INT | 9,676,800 | 5.0% |
| STORE_FAST | 960 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 48,534,360 | 34.0% |
| STORE_SUBSCR_LIST_INT | 20,714,400 | 14.5% |
| PUSH_NULL | 20,714,400 | 14.5% |
| POP_TOP | 20,714,400 | 14.5% |
| ENTER_EXECUTOR | 16,329,600 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 53,590,200 | 37.6% |
| BINARY_SUBSCR_LIST_INT | 30,391,200 | 21.3% |
| PUSH_NULL | 20,714,400 | 14.5% |
| COPY | 20,714,400 | 14.5% |
| LOAD_CONST | 17,236,800 | 12.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 33.3% |
| STORE_FAST | 40 | 22.2% |
| RETURN_VALUE | 40 | 22.2% |
| RESUME_CHECK | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 66.7% |
| LOAD_GLOBAL_MODULE | 40 | 22.2% |
| LOAD_ATTR | 20 | 11.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 94,867,980 | 72.9% |
| TO_BOOL_INT | 34,473,600 | 26.5% |
| ENTER_EXECUTOR | 705,600 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,534,360 | 37.3% |
| LOAD_FAST | 40,220,220 | 30.9% |
| ENTER_EXECUTOR | 30,759,000 | 23.7% |
| JUMP_FORWARD | 10,533,600 | 8.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 34,473,600 | 33.9% |
| BINARY_OP_ADD_INT | 32,875,800 | 32.3% |
| LOAD_CONST | 17,236,860 | 16.9% |
| BINARY_SLICE | 17,236,800 | 16.9% |
| LOAD_FAST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,947,680 | 67.7% |
| LOAD_CONST | 17,236,860 | 16.9% |
| LOAD_FAST_LOAD_FAST | 15,639,900 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20,714,400 | 50.0% |
| BINARY_OP_SUBTRACT_INT | 20,714,400 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20,714,400 | 50.0% |
| STORE_SUBSCR_LIST_INT | 20,714,400 | 50.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 50,112,640 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,875,800 | 65.6% |
| STORE_SLICE | 17,236,800 | 34.4% |
| CALL_BUILTIN_CLASS | 40 | 0.0% |
| CALL | 20 | 0.0% |


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

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,714,560 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20,714,400 | 100.0% |
| STORE_FAST | 120 | 0.0% |
| STORE_SUBSCR_LIST_INT | 60 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,360,000 | 47.0% |
| LOAD_FAST_LOAD_FAST | 30,391,200 | 31.5% |
| COPY | 20,714,400 | 21.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 52,315,200 | 54.2% |
| STORE_FAST | 34,473,600 | 35.7% |
| LOAD_FAST | 9,676,800 | 10.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 120 | 33.3% |
| CALL | 120 | 33.3% |
| LOAD_FAST | 80 | 22.2% |
| BINARY_OP_ADD_INT | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 50.0% |
| CALL_BUILTIN_CLASS | 120 | 33.3% |
| CALL | 60 | 16.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,714,400 | 50.0% |
| CALL_BUILTIN_FAST | 20,714,400 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20,714,400 | 50.0% |
| CALL_BUILTIN_FAST | 20,714,400 | 50.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 53,590,200 | 56.5% |
| LOAD_CONST | 31,600,960 | 33.3% |
| LOAD_FAST | 9,676,800 | 10.2% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 94,867,980 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| PUSH_NULL | 40 | 40.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 33.3% |
| LOAD_GLOBAL | 120 | 33.3% |
| STORE_FAST | 80 | 22.2% |
| RESUME_CHECK | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 33.3% |
| LOAD_FAST | 120 | 33.3% |
| LOAD_GLOBAL | 60 | 16.7% |
| LOAD_CONST | 60 | 16.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40 | 40.0% |
| LOAD_GLOBAL | 40 | 40.0% |
| RETURN_VALUE | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| CACHE | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 40 | 33.3% |
| LOAD_GLOBAL | 40 | 33.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20,714,400 | 100.0% |
| BINARY_OP_SUBTRACT_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,714,400 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,473,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,473,600 | 100.0% |


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

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     17236800 | 6.8% |
|          hit |    237061380 | 93.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 4,200 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list slice | 4,200 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     53050740 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    121111500 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    292078320 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          240 | 0.0% |
|          hit |     74823840 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 60.0% |
| Failure | 80 | 40.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| other | 20 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    170598600 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          140 | 43.8% |
|          hit |          100 | 31.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 50.0% |
| Failure | 40 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 40 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 3.1% |
|          hit |          460 | 71.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
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


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 941,264,760 | 63.5% |
| Not specialized | 181,762,700 | 12.3% |
| Specialized | 358,778,780 | 24.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 17,236,800 | 100.0% |
| CALL | 240 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_INT | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 60 | 50.0% |
| Calls to Python functions inlined | 60 | 50.0% |
| Calls via PyEval_EvalFrame (total) | 60 | 50.0% |
| Calls via PyEval_EvalFrame (vector) | 60 | 50.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 60 | 50.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 50.0% |
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
| Allocations from freelist | 121,111,600 | 47.8% |
| Frees to freelist | 121,111,740 |  |
| Allocations | 131,998,760 | 52.2% |
| Allocations to 512 bytes | 131,998,760 | 52.2% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 131,998,560 |  |
| New values | 0 |  |
| Interpreter increfs | 267,604,660 | 35.6% |
| Interpreter decrefs | 296,504,940 | 27.0% |
| Increfs | 483,477,520 | 64.4% |
| Decrefs | 800,675,660 | 73.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 177 |  |
| Method cache misses | 3 |  |
| Method cache collisions | 3 |  |
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
