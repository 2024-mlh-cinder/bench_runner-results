
# Pystats results

- benchmark: fannkuch
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 275,098,740 | 18.1% | 18.1% |  |
| LOAD_FAST | 195,871,440 | 12.9% | 31.0% |  |
| LOAD_FAST_LOAD_FAST | 146,527,860 | 9.6% | 40.6% |  |
| POP_JUMP_IF_FALSE | 137,909,580 | 9.1% | 49.7% |  |
| COMPARE_OP_INT | 103,435,980 | 6.8% | 56.5% |  |
| STORE_FAST | 101,824,680 | 6.7% | 63.2% |  |
| BINARY_SUBSCR_LIST_INT | 98,582,400 | 6.5% | 69.7% |  |
| ENTER_EXECUTOR | 57,284,280 | 3.8% | 73.4% |  |
| BINARY_OP_ADD_INT | 50,112,660 | 3.3% | 76.7% |  |
| PUSH_NULL | 43,545,900 | 2.9% | 79.6% |  |
| SWAP | 43,545,600 | 2.9% | 82.5% |  |
| COPY | 43,545,600 | 2.9% | 85.3% |  |
| CALL_BUILTIN_FAST | 43,545,600 | 2.9% | 88.2% |  |
| TO_BOOL_INT | 34,473,600 | 2.3% | 90.5% |  |
| BINARY_OP_SUBTRACT_INT | 21,772,980 | 1.4% | 91.9% |  |
| POP_TOP | 21,772,920 | 1.4% | 93.3% |  |
| STORE_SUBSCR_LIST_INT | 21,772,860 | 1.4% | 94.7% |  |
| BINARY_SUBSCR | 17,241,000 | 1.1% | 95.9% |  |
| STORE_SLICE | 17,236,800 | 1.1% | 97.0% |  |
| BUILD_SLICE | 17,236,800 | 1.1% | 98.2% |  |
| BINARY_SLICE | 17,236,800 | 1.1% | 99.3% |  |
| JUMP_FORWARD | 10,886,400 | 0.7% | 100.0% |  |
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
| LOAD_FAST LOAD_CONST | 129,946,620 | 8.5% | 8.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 103,435,980 | 6.8% | 15.3% |
| STORE_FAST LOAD_FAST | 68,947,680 | 4.5% | 19.9% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 54,432,000 | 3.6% | 23.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 54,295,800 | 3.6% | 27.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 50,112,640 | 3.3% | 30.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 49,239,960 | 3.2% | 33.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 47,024,220 | 3.1% | 36.7% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 45,360,000 | 3.0% | 39.6% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 34,473,600 | 2.3% | 41.9% |
| LOAD_FAST TO_BOOL_INT | 34,473,600 | 2.3% | 44.2% |
| LOAD_CONST LOAD_CONST | 34,473,600 | 2.3% | 46.4% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 34,473,600 | 2.3% | 48.7% |
| BINARY_OP_ADD_INT STORE_FAST | 32,875,800 | 2.2% | 50.9% |
| LOAD_CONST COMPARE_OP_INT | 32,659,360 | 2.1% | 53.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 31,449,600 | 2.1% | 55.1% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 30,759,000 | 2.0% | 57.1% |
| LOAD_FAST PUSH_NULL | 21,772,980 | 1.4% | 58.5% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 21,772,960 | 1.4% | 60.0% |
| SWAP SWAP | 21,772,800 | 1.4% | 61.4% |
| SWAP STORE_SUBSCR_LIST_INT | 21,772,800 | 1.4% | 62.8% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 21,772,800 | 1.4% | 64.3% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 21,772,800 | 1.4% | 65.7% |
| PUSH_NULL LOAD_CONST | 21,772,800 | 1.4% | 67.1% |
| POP_TOP LOAD_FAST_LOAD_FAST | 21,772,800 | 1.4% | 68.6% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 21,772,800 | 1.4% | 70.0% |
| LOAD_FAST_LOAD_FAST COPY | 21,772,800 | 1.4% | 71.4% |
| LOAD_CONST CALL_BUILTIN_FAST | 21,772,800 | 1.4% | 72.9% |
| COPY COPY | 21,772,800 | 1.4% | 74.3% |
| COPY BINARY_SUBSCR_LIST_INT | 21,772,800 | 1.4% | 75.7% |
| CALL_BUILTIN_FAST POP_TOP | 21,772,800 | 1.4% | 77.2% |
| CALL_BUILTIN_FAST CALL_BUILTIN_FAST | 21,772,800 | 1.4% | 78.6% |
| BINARY_OP_SUBTRACT_INT SWAP | 21,772,800 | 1.4% | 80.0% |
| ENTER_EXECUTOR LOAD_FAST | 18,511,800 | 1.2% | 81.2% |
| STORE_FAST LOAD_CONST | 17,236,860 | 1.1% | 82.4% |
| LOAD_CONST STORE_FAST | 17,236,860 | 1.1% | 83.5% |
| LOAD_CONST LOAD_FAST | 17,236,860 | 1.1% | 84.6% |
| STORE_SLICE LOAD_FAST | 17,236,800 | 1.1% | 85.8% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 17,236,800 | 1.1% | 86.9% |
| LOAD_CONST BUILD_SLICE | 17,236,800 | 1.1% | 88.0% |
| LOAD_CONST BINARY_SLICE | 17,236,800 | 1.1% | 89.2% |
| BUILD_SLICE BINARY_SUBSCR | 17,236,800 | 1.1% | 90.3% |
| BINARY_SUBSCR LOAD_FAST | 17,236,800 | 1.1% | 91.4% |
| BINARY_SLICE STORE_FAST | 17,236,800 | 1.1% | 92.6% |
| BINARY_OP_ADD_INT STORE_SLICE | 17,236,800 | 1.1% | 93.7% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 16,329,600 | 1.1% | 94.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 15,639,900 | 1.0% | 95.8% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 15,638,880 | 1.0% | 96.8% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 10,886,400 | 0.7% | 97.6% |
| JUMP_FORWARD ENTER_EXECUTOR | 10,886,400 | 0.7% | 98.3% |
| LOAD_FAST COMPARE_OP_INT | 9,676,800 | 0.6% | 98.9% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 9,676,800 | 0.6% | 99.6% |
| ENTER_EXECUTOR COMPARE_OP_INT | 6,804,000 | 0.4% | 100.0% |
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
| CALL_BUILTIN_FAST | 21,772,800 | 100.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,772,800 | 100.0% |
| NOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,772,980 | 50.0% |
| LOAD_FAST_LOAD_FAST | 21,772,800 | 50.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR_MODULE | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,772,800 | 50.0% |
| LOAD_CONST | 21,772,800 | 50.0% |
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
| LOAD_FAST_LOAD_FAST | 21,772,800 | 50.0% |
| COPY | 21,772,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 21,772,800 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 21,772,800 | 50.0% |


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
| ENTER_EXECUTOR | 15,638,880 | 27.3% |
| JUMP_FORWARD | 10,886,400 | 19.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,511,800 | 32.3% |
| LOAD_FAST_LOAD_FAST | 16,329,600 | 28.5% |
| ENTER_EXECUTOR | 15,638,880 | 27.3% |
| COMPARE_OP_INT | 6,804,000 | 11.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,886,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 10,886,400 | 100.0% |


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
| LOAD_FAST | 129,946,620 | 47.2% |
| BINARY_SUBSCR_LIST_INT | 54,432,000 | 19.8% |
| LOAD_CONST | 34,473,600 | 12.5% |
| PUSH_NULL | 21,772,800 | 7.9% |
| STORE_FAST | 17,236,860 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 50,112,640 | 18.2% |
| BINARY_SUBSCR_LIST_INT | 45,360,000 | 16.5% |
| LOAD_CONST | 34,473,600 | 12.5% |
| COMPARE_OP_INT | 32,659,360 | 11.9% |
| BINARY_OP_SUBTRACT_INT | 21,772,960 | 7.9% |


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
| STORE_FAST | 68,947,680 | 35.2% |
| POP_JUMP_IF_FALSE | 47,024,220 | 24.0% |
| ENTER_EXECUTOR | 18,511,800 | 9.5% |
| LOAD_CONST | 17,236,860 | 8.8% |
| STORE_SLICE | 17,236,800 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,946,620 | 66.3% |
| TO_BOOL_INT | 34,473,600 | 17.6% |
| PUSH_NULL | 21,772,980 | 11.1% |
| COMPARE_OP_INT | 9,676,800 | 4.9% |
| STORE_FAST | 960 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 49,239,960 | 33.6% |
| STORE_SUBSCR_LIST_INT | 21,772,800 | 14.9% |
| PUSH_NULL | 21,772,800 | 14.9% |
| POP_TOP | 21,772,800 | 14.9% |
| ENTER_EXECUTOR | 16,329,600 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 54,295,800 | 37.1% |
| BINARY_SUBSCR_LIST_INT | 31,449,600 | 21.5% |
| PUSH_NULL | 21,772,800 | 14.9% |
| COPY | 21,772,800 | 14.9% |
| LOAD_CONST | 17,236,800 | 11.8% |


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
| COMPARE_OP_INT | 103,435,980 | 75.0% |
| TO_BOOL_INT | 34,473,600 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 49,239,960 | 35.7% |
| LOAD_FAST | 47,024,220 | 34.1% |
| ENTER_EXECUTOR | 30,759,000 | 22.3% |
| JUMP_FORWARD | 10,886,400 | 7.9% |


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
| SWAP | 21,772,800 | 50.0% |
| BINARY_OP_SUBTRACT_INT | 21,772,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 21,772,800 | 50.0% |
| STORE_SUBSCR_LIST_INT | 21,772,800 | 50.0% |


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
| LOAD_CONST | 21,772,960 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 21,772,800 | 100.0% |
| STORE_FAST | 120 | 0.0% |
| STORE_SUBSCR_LIST_INT | 60 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,360,000 | 46.0% |
| LOAD_FAST_LOAD_FAST | 31,449,600 | 31.9% |
| COPY | 21,772,800 | 22.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 54,432,000 | 55.2% |
| STORE_FAST | 34,473,600 | 35.0% |
| LOAD_FAST | 9,676,800 | 9.8% |


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
| LOAD_CONST | 21,772,800 | 50.0% |
| CALL_BUILTIN_FAST | 21,772,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 21,772,800 | 50.0% |
| CALL_BUILTIN_FAST | 21,772,800 | 50.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 54,295,800 | 52.5% |
| LOAD_CONST | 32,659,360 | 31.6% |
| LOAD_FAST | 9,676,800 | 9.4% |
| ENTER_EXECUTOR | 6,804,000 | 6.6% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 103,435,980 | 100.0% |


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
| SWAP | 21,772,800 | 100.0% |
| BINARY_OP_SUBTRACT_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,772,800 | 100.0% |
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
| specialization.deferred |     17236800 | 14.9% |
|          hit |     98582400 | 85.1% |

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
|          hit |     21772860 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     34473600 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     71885700 | 100.0% |

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
|          hit |     43545960 | 100.0% |

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
|          hit |    103435980 | 100.0% |

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
| Basic | 957,140,760 | 63.0% |
| Not specialized | 189,625,100 | 12.5% |
| Specialized | 373,697,180 | 24.6% |

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
| Interpreter increfs | 272,896,660 | 36.3% |
| Interpreter decrefs | 301,796,940 | 27.5% |
| Increfs | 478,185,520 | 63.7% |
| Decrefs | 795,383,660 | 72.5% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 174 |  |
| Method cache misses | 6 |  |
| Method cache collisions | 6 |  |
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
| Traces executed | 57,284,280 |  |
| Uops executed | 4,113,602,280 | 71 |
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
| <= 8 | 10,886,400 | 19.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 5,155,740 | 9.0% |
| <= 64 | 28,238,940 | 49.3% |
| <= 128 | 3,738,960 | 6.5% |
| <= 256 | 4,931,160 | 8.6% |
| <= 512 | 3,842,640 | 6.7% |
| <= 1024 | 490,440 | 0.9% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 963,743,760 | 23.4% | 23.4% |
| LOAD_FAST | 856,527,720 | 20.8% | 44.3% |
| LOAD_CONST | 657,206,580 | 16.0% | 60.2% |
| _GUARD_BOTH_INT | 220,192,620 | 5.4% | 65.6% |
| STORE_FAST | 188,914,740 | 4.6% | 70.2% |
| _BINARY_OP_ADD_INT | 173,275,800 | 4.2% | 74.4% |
| BINARY_SUBSCR_LIST_INT | 138,478,980 | 3.4% | 77.8% |
| _POP_JUMP_IF_FALSE | 134,935,980 | 3.3% | 81.0% |
| TO_BOOL_INT | 86,637,900 | 2.1% | 83.1% |
| STORE_SLICE | 86,637,900 | 2.1% | 85.2% |
| BUILD_SLICE | 86,637,900 | 2.1% | 87.3% |
| BINARY_SUBSCR | 86,637,900 | 2.1% | 89.5% |
| _JUMP_TO_TOP | 71,517,900 | 1.7% | 91.2% |
| COMPARE_OP_INT | 67,162,620 | 1.6% | 92.8% |
| _EXIT_TRACE | 57,284,280 | 1.4% | 94.2% |
| _BINARY_OP_SUBTRACT_INT | 46,916,820 | 1.1% | 95.4% |
| SWAP | 31,277,880 | 0.8% | 96.1% |
| STORE_SUBSCR_LIST_INT | 31,277,880 | 0.8% | 96.9% |
| PUSH_NULL | 31,277,880 | 0.8% | 97.6% |
| COPY | 31,277,880 | 0.8% | 98.4% |
| CALL_BUILTIN_FAST | 31,277,880 | 0.8% | 99.2% |
| _POP_JUMP_IF_TRUE | 18,864,540 | 0.5% | 99.6% |
| POP_TOP | 15,638,940 | 0.4% | 100.0% |


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
Stats gathered on: 2023-10-03
